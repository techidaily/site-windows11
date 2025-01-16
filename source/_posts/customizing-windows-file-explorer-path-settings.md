---
title: Customizing Windows File Explorer Path Settings
date: 2025-01-09T14:45:43.741Z
updated: 2025-01-16T11:36:58.260Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Customizing Windows File Explorer Path Settings
excerpt: This Article Describes Customizing Windows File Explorer Path Settings
keywords: Customize File Explore,Adjust File Paths,Windows Explorer Options,Navigate Directories,Alter Explore Layout,Personalize Folder View,Modify Explore Settings
thumbnail: https://thmb.techidaily.com/8383b1955265d208bd65863f99fa93e0506dbf01fc1cf31d37490fb679a3c33d.png
---

## Customizing Windows File Explorer Path Settings

 To access the D: drive, you normally have to open File Explorer, click on **This PC** in the Navigation pane, and expand the **Devices and drives** section. With a simple hack, you can add it to the Navigation pane so you can easily access it straight from there. It will require you to tweak the Windows Registry, but don’t worry; we'll show you an extremely easy way of going about it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oP8grXxuy2o?si=uIRNhTYbecTcaC7J" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Before You Proceed…

 We are going to [create a Registry file](https://www.makeuseof.com/windows-registry-file-guide/) to add the D: drive to the Navigation Pane. This file will make changes to the Windows registry, and you need to be careful [not to mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/). A slip-up could make Windows unusable.

 Furthermore, we highly recommend that you learn how to [back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). That way, you have a way of returning it to the state it was in before you made any changes that broke it.

## How Do I Add the D: Drive to the Navigation Pane in File Explorer?

 Start by pressing **Win + S** to bring up Windows Search. Then, type **notepad** in the Search box, and when Notepad shows up in the search results, click on it to launch it.

![The Notepad search result](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/notepad-search-result.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zAzTErKy6h8?si=vi5z3M9_7fW6qiAJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xa2_mFu-obA?si=_xDGF1pv-dnuaDOr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Next, double-click the Registry file you just created and click **Yes** on the UAC prompt. You’ll then be asked if you want to continue with the merge, so click **Yes**. Afterward, press **Win + E** to open File Explorer.

![the D drive showing in the bottom section of the Navigation pane on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/d-drive-nav-pane.jpg)

 The D: drive should now be visible in the bottom part of the Navigation pane.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YB7Ou4-iKVM?si=7Fq8iUwI8voccMLx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Do I Remove the D: Drive From the Navigation Pane in File Explorer?

 To remove the D: drive from the navigation pane, open Notepad and then copy and paste the below text:

`Windows Registry Editor Version 5.00  
  
[-HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}][HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\HideDesktopIcons\NewStartPanel]  
"{0525388b-89d9-4112-bf4d-2aaccb716a7f}"=-  
  
[-HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace\{0525388b-89d9-4112-bf4d-2aaccb716a7f}]`

 Save the file as **remove-d-drive-file-explorer.reg**. Afterward, double-click the registry file and click **Yes** on the UAC prompt. When asked if you want to continue with the merge, click **Yes** again.

 Now the D: drive should be gone from the navigation pane in File Explorer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/omWG4u39lmE?si=yk1AEo_gzDpGjYbl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://youtube-webster.techidaily.com/n-2024-designing-effective-video-previews-for-channels/"><u>[New] In 2024, Designing Effective Video Previews for Channels</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-tailoring-video-content-to-youtubes-niche-needs/"><u>[New] In 2024, Tailoring Video Content to Youtube's Niche Needs</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-pursuing-passion-professionally-a-guide-for-aspiring-designers/"><u>[New] Pursuing Passion Professionally A Guide for Aspiring Designers</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-allocating-money-wisely-in-youtube-advertising/"><u>[Updated] Allocating Money Wisely in YouTube Advertising</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-visual-branding-mastery-implementing-watermarks-and-logos-into-video-content/"><u>[Updated] Visual Branding Mastery Implementing Watermarks & Logos Into Video Content</u></a></li>
<li><a href="https://win-premium.techidaily.com/1728461863615-2024/"><u>2024年に失われたリングの動画を取り戻せる手順</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-the-geforce-experience-settings-not-available-hurdle-windows-11/"><u>Fixing the 'GeForce Experience Settings Not Available' Hurdle, Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-the-powershell-not-found-issue-on-windows-os/"><u>Fixing the PowerShell Not Found Issue on Windows OS</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/get-your-hands-on-macos-15-sequoia-early-access-download-instructions-for-mac-users-zdnet-coverage/"><u>Get Your Hands on MacOS 15 Sequoia Early Access! Download Instructions for Mac Users | ZDNet Coverage.</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-mastering-quantum-hdr-principles/"><u>In 2024, Mastering Quantum HDR Principles</u></a></li>
<li><a href="https://windows11.techidaily.com/innovative-designs-and-advanced-tech-years-best-windows-laptops/"><u>Innovative Designs and Advanced Tech - Year's Best Windows Laptops</u></a></li>
<li><a href="https://video-capture.techidaily.com/mp4mov-3/"><u>MP4からMOVへの変換: 3つの最優秀無料ツール</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-high-dynamic-range-hdr-in-windows-11-a-step-by-step-manual/"><u>Navigating High Dynamic Range (HDR) in Windows 11: A Step-by-Step Manual</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-to-system32-in-windows-11/"><u>Navigating to System32 in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-audio-clarity-and-functionality-in-valorant-windows/"><u>Restoring Audio Clarity and Functionality in Valorant (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/retrieve-missing-5ghz-connection-now-easily-for-windows-11/"><u>Retrieve Missing 5GHz Connection, Now Easily for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-obsidian-way-to-uncluttered-vivid-note-taking/"><u>The Obsidian Way to Uncluttered, Vivid Note-Taking</u></a></li>
<li><a href="https://tech-revival.techidaily.com/top-5-benefits-of-using-chatgpt-for-enhanced-cryptocurrency-investments/"><u>Top 5 Benefits of Using ChatGPT for Enhanced Cryptocurrency Investments</u></a></li>
<li><a href="https://windows11.techidaily.com/which-offers-smoother-windows-setup-chocolatey-or-wm/"><u>Which Offers Smoother Windows Setup? Chocolatey or WM</u></a></li>
</ul></div>

