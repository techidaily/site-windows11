---
title: How to Remove the OneDrive Icon From File Explorer in Windows 11
date: 2024-11-19T23:35:00.394Z
updated: 2024-11-24T17:12:58.760Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Remove the OneDrive Icon From File Explorer in Windows 11
excerpt: This Article Describes How to Remove the OneDrive Icon From File Explorer in Windows 11
keywords: Remove OneDrive Folder,Delete OneDrive Icon,Unlink OneDrive Files,Stop OneDrive Sync,Remove OneDrive Explorer,Disable OneDrive Search,Hide OneDrive From Windows 11
thumbnail: https://thmb.techidaily.com/76cb87841297f436650576e356aab992c1ddd1148ccda3c73b6601c2eaf3c2ce.jpg
---

## How to Remove the OneDrive Icon From File Explorer in Windows 11

 The OneDrive cloud storage client comes pre-installed on your Windows 11 computer. By default, you'll notice a OneDrive shortcut in the left pane of File Explorer, allowing quick access to your OneDrive files and folders.

 However, if you find the shortcut cluttering or ruining your File Explorer experience, you can remove it using a registry hack. Here's how to remove the OneDrive icon from File Explorer without uninstalling OneDrive.

## How to Remove OneDrive Shortcut From File Explorer via the Registry Editor

 You can remove the OneDrive icon from File Explorer using a registry hack. This way, you can get rid of the icon in File Explorer without uninstalling the OneDrive client. If you would rather remove the app entirely, follow our guide on[removing OneDrive on Windows 11](https://www.makeuseof.com/windows-11-disable-remove-onedrive/) .

 Note that modifying the Windows registry involves risk. We recommend you[create a system restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed with the steps below. A restore point will help you restore your computer in case something goes wrong.

 Once done, follow these steps to remove the OneDrive shortcut from File Explorer:

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open Registry Editor. Click**Yes** if prompted by**User Account Control (UAC).**
3. Next, in the Registry Editor, navigate to the following location. Copy and paste the registry path in the editor for quicker navigation:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
4. In the right pane, right-click on**System.IsPinnedToNameSpaceTree** DWORD value and select**Modify** .  
![remove onedrive icon windows 11 registry editor modify system is pinned to name space free](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-modify-system-is-pinnedtonamespace-free.jpg)
5. In the**Value data** field, type**0** and click**OK** .  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![remove onedrive icon windows 11 registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor.jpg)
6. Next, navigate to the following location in Registry Editor:  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c1yHj02oP3w?si=mwi3FyP0p68gkBqV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace`
7. In the left pane, right-click on**{018D5C66-4533-4307-9B53-224DE2ED1FE6}** and select**Delete** to remove the entry.  
![remove onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)
8. Once done, close the Registry Editor.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q-mXUpVQijU?si=f1MzflPJ8-bD2_iQ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

9. When you open File Explorer, the OneDrive icon will not be visible anymore.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vfq0vw0Spz8?si=2EAk6hW-Gb-o33_L&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show the OneDrive Icon Again in File Explorer

![show onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/show-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Rxyki8-Y630?si=dHLkIxG59zdlZeN0&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To show the OneDrive icon in File Explorer, you’ll need to modify a registry entry again. Here’s how to do it.

1. Press**Win + R** to open**Registry Editor.**
2. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
3. In the right pane, double-click on**System.IsPinnedToNameSpaceTree** DWORD value.
4. Next, type**1** in the**Value data f** ield and click**OK** to save the changes.
5. Relaunch File Explorer to see the changes.

## Remove OneDrive Icon Without Uninstalling OneDrive

 This registry hack is a handy way to make the OneDrive icon disappear without deleting the app entirely from your PC. Alternatively, if you don’t use the service, you can completely remove OneDrive on Windows 11 or disable the service using Group Policy Editor.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-daily-dollars-and-cents-average-income-from-youtubes-adsense-per-thousand-viewer-hours/"><u>[New] 2024 Approved Daily Dollars and Cents Average Income From YouTube's AdSense Per Thousand Viewer Hours</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-instagram-vids-determining-the-perfect-dimensions/"><u>[New] 2024 Approved Instagram Vids Determining the Perfect Dimensions</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-efficiently-recording-desktop-screens-for-various-purposes/"><u>[New] Efficiently Recording Desktop Screens for Various Purposes</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/comprehensive-guide-to-photo-to-video-conversion-via-pixiz/"><u>Comprehensive Guide to Photo-to-Video Conversion via Pixiz</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ing-captivating-life-enriching-video-content-for-2024/"><u>Creating Captivating Life-Enriching Video Content for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-windows-iscsi-initiator-functionality/"><u>Exploring Windows iSCSI Initiator Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-common-photo-errors-on-windows-1011/"><u>Fixing Common Photo Errors on Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/get-rid-of-bloatware-in-a-flash-with-windows-11/"><u>Get Rid of Bloatware in a Flash with Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-address-windows-memory-write-faults/"><u>How to Address Windows Memory Write Faults</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-5-quick-methods-to-bypass-nokia-c300-frp-by-drfone-android/"><u>In 2024, 5 Quick Methods to Bypass Nokia C300 FRP</u></a></li>
<li><a href="https://fox-links.techidaily.com/in-2024-instant-improvement-in-visuals-the-canva-technique-for-borderless-images/"><u>In 2024, Instant Improvement in Visuals The Canva Technique for Borderless Images</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-dormant-workflow-rules-in-microsoft-outlook/"><u>Reviving Dormant Workflow Rules in Microsoft Outlook</u></a></li>
<li><a href="https://windows11.techidaily.com/skillful-art-of-masking-the-search-on-11-taskbar/"><u>Skillful Art of Masking the Search on 11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/stealthy-start-concealing-win11s-power-button-in-start-menu/"><u>Stealthy Start: Concealing Win11's Power Button in Start Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-securely-storing-credentials-in-windows-files/"><u>Step-by-Step: Securely Storing Credentials in Windows Files</u></a></li>
<li><a href="https://youtube-web.techidaily.com/twork-or-not-a-detailed-guide-for-youtubers-considering-mncs-for-2024/"><u>To Network, Or Not A Detailed Guide for YouTubers Considering MNCs for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/your-gateway-to-digital-proficiency-understanding-screen-capture-on-macbook-air/"><u>Your Gateway to Digital Proficiency Understanding Screen Capture on MacBook Air</u></a></li>
</ul></div>

