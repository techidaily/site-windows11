---
title: Trimming Down OneDrive Icon From the File Explorer Palette
date: 2024-08-31T22:08:22.004Z
updated: 2024-09-01T22:08:22.004Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Trimming Down OneDrive Icon From the File Explorer Palette
excerpt: This Article Describes Trimming Down OneDrive Icon From the File Explorer Palette
keywords: Reduce OneDrive Size,Slash Drive Icon,Cut File Explorer Apps,Minimize Storage Icons,Decrease Explorer Space,Lighten Up Drive Folder,Dim Down Filespace Palette
thumbnail: https://thmb.techidaily.com/b89ffcd4bf4187d5ce782fa255f3d31e70eba20fbf846963d325dce5a6f79e5f.jpg
---

## Trimming Down OneDrive Icon From the File Explorer Palette

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

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-easy-guide-to-screenshots-and-recordings-with-macos/"><u>[New] 2024 Approved  Easy Guide to Screenshots & Recordings with macOS</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-best-mac-visual-snapshot-list-limit-156-chars/"><u>[New] Best Mac Visual Snapshot List (Limit  156 Chars)</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-crafting-the-ideal-youtube-playlist-an-easy-step-by-step-method/"><u>[New] Crafting the Ideal YouTube Playlist  An Easy, Step-by-Step Method</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-efficient-strategies-to-record-ppt-sessions/"><u>[New] Efficient Strategies to Record PPT Sessions</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-exclusive-review-10-best-free-video-meeting-apps-iosandroid-for-2024/"><u>[New] Exclusive Review  10 Best Free Video Meeting Apps iOS/Android for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-from-novice-to-pro-building-an-insta-highlight-showcase-for-2024/"><u>[New] From Novice to Pro  Building an Insta Highlight Showcase for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-win11s-top-5-no-cost-screen-recorders-updated-guide-for-2024/"><u>[New] Win11's Top 5 No-Cost Screen Recorders - Updated Guide for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-20plus-secrets-to-insta-wonderful-videos-for-2024/"><u>[Updated] 20+ Secrets to Insta-Wonderful Videos for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/1716068818113-updated-2024-approved-capture-share-enjoy/"><u>[Updated] 2024 Approved  Capture, Share, Enjoy!</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-exploring-the-youtube-content-manager-toolkit-for-2024/"><u>[Updated] Exploring the YouTube Content Manager Toolkit for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-brief-glimpses-in-the-social-space/"><u>[Updated] In 2024, Brief Glimpses in the Social Space</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-speech-clarity-achieved-by-googles-advanced-conversion/"><u>[Updated] In 2024, Speech Clarity Achieved by Google's Advanced Conversion</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-navigating-the-route-to-social-stardom-a-quick-overview-of-6-key-steps-on-instagram/"><u>[Updated] Navigating the Route to Social Stardom  A Quick Overview of 6 Key Steps on Instagram</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-speaking-through-screens-effective-communication-on-youtube/"><u>[Updated] Speaking Through Screens  Effective Communication on YouTube</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-the-art-of-vivid-visuals-on-your-computer-with-windows-hdr/"><u>2024 Approved  The Art of Vivid Visuals on Your Computer with Windows HDR</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-to-customizing-windows-11-default-apps/"><u>Essential Guide to Customizing Windows 11 Default Apps</u></a></li>
<li><a href="https://howto.techidaily.com/fix-app-not-available-in-your-country-play-store-problem-on-samsung-galaxy-a54-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix App Not Available in Your Country Play Store Problem on Samsung Galaxy A54 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-filenames-5-windows-utilities-for-date-manipulation/"><u>Fix Filenames: 5 Windows Utilities for Date Manipulation</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-absent-mfc71udll-steps-for-windows-users/"><u>Fixing Absent Mfc71u.dll: Steps for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-nvidias-geforce-now-error-code-xc0f1103f/"><u>Fixing NVIDIA's GeForce Now Error Code: Xc0f1103f</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-video-playback-issues-with-error-0xc10100bf/"><u>Fixing Video Playback Issues with Error 0XC10100BF</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-windows-components-administration-tool/"><u>Guide to Windows Components Administration Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/has-windows-subsystem-shifted-linux-desktops/"><u>Has Windows Subsystem Shifted Linux Desktops?</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/how-to-correctly-address-the-fixed-unexpected-store-exception-error-in-windows-10-systems/"><u>How to Correctly Address the Fixed 'Unexpected Store Exception' Error in Windows 10 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-windows-activation-error-0x803f700f/"><u>How to Fix the Windows Activation Error 0X803F700F</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-restore-windows-network-access/"><u>How To Restore Windows Network Access</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-swiftly-overcome-directdraw-errors-in-win1011-environments/"><u>How to Swiftly Overcome DirectDraw Errors in Win10/11 Environments</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-xiaomi-civi-3-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Xiaomi Civi 3 to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/mp4-conversion-made-simple-fb-video-to-720p-1080p-at-zero-charge-for-2024/"><u>MP4 Conversion Made Simple  FB Video to 720P, 1080P at Zero Charge for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-winscombsvr-crashes-in-windows/"><u>Navigating Through WinScombSvr Crashes in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/optimal-pc-protection-activating-tpm-and-secure-boot-in-win-11/"><u>Optimal PC Protection: Activating TPM & Secure Boot in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-security-updating-user-passwords-on-win-11/"><u>Optimizing Security: Updating User Passwords on Win 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/prank-your-friends-easy-ways-to-fake-and-share-google-maps-location-on-samsung-galaxy-f15-5g-drfone-by-drfone-virtual-android/"><u>Prank Your Friends! Easy Ways to Fake and Share Google Maps Location On Samsung Galaxy F15 5G | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/procure-no-cost-media-content-from-prime-4-youtube-vids-for-2024/"><u>Procure No-Cost Media Content From Prime 4 YouTube Vids for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/repair-guide-reactivating-night-light-feature-in-windows-11-operating-system/"><u>Repair Guide: Reactivating Night Light Feature in Windows 11 Operating System</u></a></li>
<li><a href="https://windows11.techidaily.com/secrets-for-locating-vanished-registry-management-utility/"><u>Secrets for Locating Vanished Registry Management Utility</u></a></li>
<li><a href="https://windows11.techidaily.com/simplified-steps-to-alter-your-cursors-look/"><u>Simplified Steps to Alter Your Cursor's Look</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-inability-to-run-os-disk-organizer/"><u>Tackling Inability to Run OS Disk Organizer</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-pubg-save-settings-breakdown-on-win-oses/"><u>Tackling PUBG Save Settings Breakdown on Win OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-to-conceal-windows-11s-task-control-icon/"><u>Tactics to Conceal Windows 11'S Task Control Icon</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-repairing-disp-settings-missing-error/"><u>Tips for Repairing Disp Settings Missing Error</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshoot-windows-not-recognizing-an-interface/"><u>Troubleshoot Windows Not Recognizing an Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-upgraded-widget-choice-interface-in-win11/"><u>Unlocking Upgraded Widget Choice Interface in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11-with-non-admin-steps/"><u>Unlocking Windows 11 With Non-Admin Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secrets-of-fax-cover-page-editing-in-win11/"><u>Unveiling the Secrets of Fax Cover Page Editing in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/your-guide-to-next-gen-computing-at-ifa-2023/"><u>Your Guide to Next-Gen Computing at IFA 2023</u></a></li>
</ul></div>
