---
title: Strategies for Disabling OneDrive Icon on Windows 11 Explore
date: 2024-06-25T11:55:19.549Z
updated: 2024-06-26T11:55:19.549Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strategies for Disabling OneDrive Icon on Windows 11 Explore
excerpt: This Article Describes Strategies for Disabling OneDrive Icon on Windows 11 Explore
keywords: Win11 Stop OneDrive,Turn Off Drivе Icon,OneDrive Removal Steps,Disable OneDrive Windows,Hide OneDrive Icon W11,Stop OneDrive on PC,OneDrive Icon Control
thumbnail: https://thmb.techidaily.com/21bab4f1638ef86b0e7d7d0a727f5b3a087b8ff6581d699ffea02276f1c5717e.jpg
---

## Strategies for Disabling OneDrive Icon on Windows 11 Explore

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
![remove onedrive icon windows 11 registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor.jpg)
6. Next, navigate to the following location in Registry Editor:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace`
7. In the left pane, right-click on**{018D5C66-4533-4307-9B53-224DE2ED1FE6}** and select**Delete** to remove the entry.  
![remove onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)
8. Once done, close the Registry Editor.
9. When you open File Explorer, the OneDrive icon will not be visible anymore.

## How to Show the OneDrive Icon Again in File Explorer

![show onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/show-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)

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
<li><a href="https://windows11.techidaily.com/disentangling-compact-icons-on-desktop-shelf/"><u>Disentangling Compact Icons on Desktop Shelf</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-manual-reverting-windows-to-a-previous-state/"><u>Step-by-Step Manual: Reverting Windows to a Previous State</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-app-management-in-windows-the-power-of-winget/"><u>Mastering App Management in Windows: The Power of Winget</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-local-security-authority-protection-is-off-security-warning-on-windows/"><u>How to Fix the “Local Security Authority Protection Is Off” Security Warning on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/breathing-life-into-winget-a-windows-11-solution/"><u>Breathing Life Into Winget: A Windows 11 Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-turning-onoff-windows-10s-smartscreen/"><u>Tips for Turning On/Off Windows 10'S SmartScreen</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-smooth-operation-fix-frozen-epic-games-launcher/"><u>Securing Smooth Operation: Fix Frozen Epic Games Launcher</u></a></li>
<li><a href="https://windows11.techidaily.com/unblock-windows-task-scheduler-issues-quickly/"><u>Unblock Windows Task Scheduler Issues Quickly</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-navigating-screen-capture-across-pcs-and-mobile-devices/"><u>2024 Approved  Navigating Screen Capture Across PCs and Mobile Devices</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-effortless-editing-a-beginners-guide-to-multi-snaps-in-snapchat/"><u>In 2024, Effortless Editing  A Beginner's Guide to Multi-Snaps in Snapchat</u></a></li>
<li><a href="https://extra-hints.techidaily.com/ushering-bliss-in-unboxing-7-strategies/"><u>Ushering Bliss in Unboxing  7 Strategies</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-snapchats-speed-control-hacks-for-cutting-edge-creators/"><u>[Updated] Snapchat's Speed Control Hacks for Cutting-Edge Creators</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-from-soundcloud-to-mp3-mastering-the-art-of-music-conversion/"><u>New 2024 Approved From Soundcloud to MP3 Mastering the Art of Music Conversion</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-frp-from-xiaomi-redmi-note-12-proplus-5g-by-drfone-android/"><u>How to Bypass FRP from Xiaomi Redmi Note 12 Pro+ 5G?</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/8-best-apps-for-screen-mirroring-oppo-k11x-pc-drfone-by-drfone-android/"><u>8 Best Apps for Screen Mirroring Oppo K11x PC | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-use-chroma-keying-in-video-making-for-2024/"><u>[Updated] How to Use Chroma Keying in Video Making for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-crafting-a-seamless-social-journey-from-instaplustik/"><u>2024 Approved  Crafting a Seamless Social Journey From Insta+Tik</u></a></li>
</ul></div>
