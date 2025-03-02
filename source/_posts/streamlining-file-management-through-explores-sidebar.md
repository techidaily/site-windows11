---
title: Streamlining File Management Through Explore's Sidebar
date: 2025-02-26T03:59:28.813Z
updated: 2025-03-01T22:40:41.622Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Streamlining File Management Through Explore's Sidebar
excerpt: This Article Describes Streamlining File Management Through Explore's Sidebar
keywords: File Streamline,Explore Organize,Easy File Access,Sidebar Navigation,Quick File Find,Explore Sync,Simplified File Views
thumbnail: https://thmb.techidaily.com/668fe014e6bae21be4d1f17bf36923c523f3242cbf8f9156a716780e5d4eeb63.jpg
---

## Streamlining File Management Through Explore's Sidebar

 To access the D: drive, you normally have to open File Explorer, click on **This PC** in the Navigation pane, and expand the **Devices and drives** section. With a simple hack, you can add it to the Navigation pane so you can easily access it straight from there. It will require you to tweak the Windows Registry, but don’t worry; we'll show you an extremely easy way of going about it.

## Before You Proceed…

 We are going to [create a Registry file](https://www.makeuseof.com/windows-registry-file-guide/) to add the D: drive to the Navigation Pane. This file will make changes to the Windows registry, and you need to be careful [not to mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/). A slip-up could make Windows unusable.

 Furthermore, we highly recommend that you learn how to [back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). That way, you have a way of returning it to the state it was in before you made any changes that broke it.

## How Do I Add the D: Drive to the Navigation Pane in File Explorer?

 Start by pressing **Win + S** to bring up Windows Search. Then, type **notepad** in the Search box, and when Notepad shows up in the search results, click on it to launch it.

![The Notepad search result](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/notepad-search-result.png)

 Then copy and paste the below text into Notepad:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}]  
@="D: Drive"  
"System.IsPinnedToNamespaceTree"=dword:00000001  
"SortOrderIndex"=dword:00000050  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\DefaultIcon]  
@=hex(2):69,00,6d,00,61,00,67,00,65,00,72,00,65,00,73,00,2e,00,64,00,6c,00,6c,\  
  00,2c,00,2d,00,33,00,32,00,00,00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\InProcServer32]  
@=hex(2):43,00,3a,00,5c,00,57,00,49,00,4e,00,44,00,4f,00,57,00,53,00,5c,00,73,\  
  00,79,00,73,00,74,00,65,00,6d,00,33,00,32,00,5c,00,73,00,68,00,65,00,6c,00,\  
  6c,00,33,00,32,00,2e,00,64,00,6c,00,6c,00,00,00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\Instance]  
"CLSID"="{0E5AAE11-A475-4c5b-AB00-C66DE400274E}"  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\Instance\InitPropertyBag]  
"Attributes"=dword:00000011  
"TargetFolderPath"=hex(2):44,00,3a,00,5c,00,00,00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\ShellFolder]  
"FolderValueFlags"=dword:00000028  
"Attributes"=dword:f080004d  
  
[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\HideDesktopIcons\NewStartPanel]  
"{0525388b-89d9-4112-bf4d-2aaccb716a7f}"=dword:00000001  
  
[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace\{0525388b-89d9-4112-bf4d-2aaccb716a7f}]  
@="D: Drive"`

 Press **Ctrl + S**, name the file **add-d-drive-file-explorer.reg**, and then click **Save**. Don’t forget to add the REG file extension to let Windows know it’s working with a Registry file.

![saving a registry file in Notepad on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/save-reg-file-add-drive-nav-pane.jpg)

 Next, double-click the Registry file you just created and click **Yes** on the UAC prompt. You’ll then be asked if you want to continue with the merge, so click **Yes**. Afterward, press **Win + E** to open File Explorer.

![the D drive showing in the bottom section of the Navigation pane on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/d-drive-nav-pane.jpg)

 The D: drive should now be visible in the bottom part of the Navigation pane.

## How Do I Remove the D: Drive From the Navigation Pane in File Explorer?

 To remove the D: drive from the navigation pane, open Notepad and then copy and paste the below text:

`Windows Registry Editor Version 5.00  
  
[-HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}][HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\HideDesktopIcons\NewStartPanel]  
"{0525388b-89d9-4112-bf4d-2aaccb716a7f}"=-  
  
[-HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace\{0525388b-89d9-4112-bf4d-2aaccb716a7f}]`

 Save the file as **remove-d-drive-file-explorer.reg**. Afterward, double-click the registry file and click **Yes** on the UAC prompt. When asked if you want to continue with the merge, click **Yes** again.

 Now the D: drive should be gone from the navigation pane in File Explorer.

## Create an Easier Way to Access the D: Drive on Your Windows Computer

 With this guide, you will remove an extra step when accessing the D: drive on your Windows computer. Once you have created the registry files, adding and removing the D: drive from the Navigation pane will be easy. While the registry files are safe, don’t forget to create a backup of your Registry or a system restore point for good measure.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-effortless-image-blur-for-iphones-top-4-methods-revealed/"><u>[Updated] In 2024, Effortless Image Blur for iPhones Top 4 Methods Revealed</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-revolutionize-your-lessons-implementing-youtube-in-the-academic-realm/"><u>[Updated] Revolutionize Your Lessons Implementing YouTube in the Academic Realm</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-unmask-subject-with-backdrop-blanket-removal/"><u>2024 Approved Unmask Subject with Backdrop Blanket Removal</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-instantly-get-the-latest-asus-touchpad-drivers-on-windows-11-made-simple/"><u>How to Instantly Get the Latest ASUS Touchpad Drivers on Windows 11 Made Simple</u></a></li>
<li><a href="https://win-web3.techidaily.com/launch-your-own-singing-journey-with-our-fifty-song-friday-kickoff-top-50-karaoke-tracks-for-a-subscription-service/"><u>Launch Your Own Singing Journey with Our 'Fifty-Song Friday' Kickoff - Top 50 Karaoke Tracks for a Subscription Service</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-11-version-22h2-update-non-installation-barrier/"><u>Overcoming Windows 11 Version 22H2 Update Non-Installation Barrier</u></a></li>
<li><a href="https://windows11.techidaily.com/securely-delete-saved-wi-fi-from-win-11/"><u>Securely Delete Saved Wi-Fi From Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-full-potential-mastering-windows-11s-launchpad/"><u>Unleashing Full Potential: Mastering Windows 11'S Launchpad</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-and-tackling-error-code-0x803f700f-in-windows-activation/"><u>Unraveling and Tackling Error Code 0X803f700f in Windows Activation</u></a></li>
<li><a href="https://buynow-help.techidaily.com/unveiling-the-truth-about-tp-link-av1n300-extender-a-comprehensive-review/"><u>Unveiling the Truth About TP-Link AV1n300 Extender: A Comprehensive Review</u></a></li>
</ul></div>

