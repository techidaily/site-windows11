---
title: Unnoticeable Disk Usage for WS11/10 Users
date: 2024-07-11T21:52:31.808Z
updated: 2024-07-12T21:52:31.808Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unnoticeable Disk Usage for WS11/10 Users
excerpt: This Article Describes Unnoticeable Disk Usage for WS11/10 Users
keywords: Low-Usage Drives,Silent Storage Impact,Efficient Hardware Use,Discreet Drive Space,Optimized Disk Performance,Stealthy Storage Usage,Minimal Disk Consumption
thumbnail: https://thmb.techidaily.com/ef372663750da3323ed4b8491ee9b4b175fd85bfcc73dd50c99f11aa454f80c7.jpg
---

## Unnoticeable Disk Usage for WS11/10 Users

 File Explorer in Windows displays any internal or external drives that are connected to your system by default. However, if you don't want a certain drive to appear in File Explorer, you can always hide it.

 By hiding a drive on Windows, you can prevent others from accessing sensitive files within that drive and keep them safe. If you're interested in doing that, this guide will walk you through four different methods to hide drives on Windows.

## 1\. Hide a Drive Using the Disk Management App

 The Disk Management tool on Windows makes it easy to perform various storage-related tasks such as formatting hard disk partitions, assigning drive letters, managing disk space, and more. You can also use it to hide a drive partition on Windows. Here's how:

1. Press**Win + R** or use one of the [many ways to open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**diskmgmt.msc** in the text field and press**Enter** .
3. In the Disk Management window that opens, right-click on the drive you wish to hide and select**Change Drive Letter and Paths** .
4. Now, click the**Remove** button from the pop-up window.
5. Choose**Yes** when the warning message appears.  
![Hide a Drive Using Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/hide-a-drive-using-disk-management.jpg)

 Once you complete the above steps, your drive will no longer appear in File Explorer.

## 2\. Hide a Drive in Windows With Diskpart Command

 If you're a power user who prefers to make changes via the command-line interface, you can use the diskpart command to hide a drive on Windows. Fortunately, this isn't as intimidating as it might sound.

To hide a drive in Windows with Command Prompt, follow these steps:

1. Press**Win + X** and select**Terminal (Admin)** from the menu that appears.
2. Select**Yes** when the User Account Control (UAC) prompt shows up.
3. In the console, type**diskpart** and press**Enter** .
4. Input the following command in the console and press**Enter** to view a list of drives connected to your system:  
`list volume`  
![List of Drives in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/list-of-drives-in-command-prompt.jpg)
5. Note down the letter of the drive you want to hide from the**Ltr** column.
6. Type the following command to select your drive. Make sure you replace**X** in the command with the drive letter noted in the last step.  
`select volume X`
7. Lastly, run the following command to remove the drive letter and hide the volume.  
`remove letter X`  
![Hide a Drive Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/hide-a-drive-using-command-prompt.jpg)

 You should see a message that reads **Diskpart successfully removed the drive letter or mount point** . Following that, the drive will no longer appear on your PC.

 If you like using Command Prompt, why not check our guide on [how to master the Command Prompt in Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) ?

## 3\. Hide a Drive Using the Group Policy Editor

 The Local Group Policy Editor is a tool that allows you to configure a wide range of settings on your computer. You can use it to hide a drive from your Windows computer.

 The Local Group Policy Editor is only available in Professional, Enterprise, and Education editions of Windows. If you're using the Windows Home edition, check our guide on [how to access the Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

Here's what you need to do:

1. Press**Win + R** to open the Run dialog box.
2. Type**gpedit.msc** in the box and click**OK** .
3. Select**Yes** when the User Account Control (UAC) prompt shows up.
4. In the Local Group Policy Editor window, use the left pane to navigate to **User Configuration > Administrative Templates > Windows Components > File Explorer** .
5. Double-click the**Hide these specified drives in My Computer** policy on your right.  
![Hide a Drive With Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/hide-a-drive-with-group-policy-editor.jpg)
6. Select the**Enabled** option.
7. Under**Options** , select the drive you want to hide.
8. Click**Apply** followed by**OK** .

 Once you complete the above steps, Windows will hide the specified drive from File Explorer. If you want to unhide the drive later, use the same steps and set the**Hide these specified drives in My Computer policy** to**Not configured** .

## 4\. Hide a Drive in Windows via the Registry Editor

 Another brilliant tool that allows you to configure system settings in Windows easily is the Registry Editor. You can use Registry Editor to hide a drive if none of the above methods work. However, you must be careful [not to accidentally mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/) in the process.

 To be safe, you should back up all the registry files before proceeding. If you need help with that, check our guide on [how to back up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and follow the steps outlined there.

 Once you're done with that, use the following steps to hide a drive using Windows Registry:

1. Press**Win + S** to open the search menu.
2. Type**registry editor** in the box and select the first result that appears.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > Software > Microsoft > Windows > CurrentVersion > Policies > Explorer** .
5. Right-click on the**Explorer** key and go to**New** and select**DWORD (32-bit) Value** from the sub-menu.
6. Rename the DWORD to**NoDrives** .
7. Double-click the**NoDrives** DWORD.
8. In the**Edit DWORD (32-bit) Value** dialog box, select**Decimal** as the Base.  
![Hide a Drive via Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/hide-a-drive-via-registry-editor.jpg)
9. Enter a number corresponding to the drive you want to hide in the**Value data** field and click**OK** . Refer to the table below to determine which number to use.  
![Drive Letter Refrence for Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/drive-letter-refrence-for-registry-editor.jpg)

 For instance, if you were to hide the**E:** drive from your computer, you'd enter**16** in the Value data field.

 You can also use this method to hide multiple drives at the same time. To do so, add the decimal numbers for both drives and enter the total in the Value data field. For example, if you're looking to hide drive**G:** and**H:** from your computer, you should enter**192** (64 + 128) in the Value data field.

 You'll have to restart your PC to apply the changes. Following that, the drive will not appear in File Explorer. You can undo the above changes at any point by deleting the**NoDrives** DWORD.

## Hiding Drives in Windows Is Easy

 Regardless of the method you use, hiding a drive on Windows is fairly simple and shouldn't take more than a few minutes.

 Alternatively, if you don't want to hide an entire drive, Windows also lets you hide specific files and folders in a few easy steps.


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
<li><a href="https://extra-resources.techidaily.com/text-temporal-tinkering-tools/"><u>Text Temporal Tinkering Tools</u></a></li>
<li><a href="https://fox-access.techidaily.com/unlocking-the-secrets-of-effective-podcast-names-plus-50plus-inspirations-for-2024/"><u>Unlocking the Secrets of Effective Podcast Names, Plus 50+ Inspirations for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-secure-transfer-of-textual-data-via-edges-guardspace-win11-version/"><u>Enabling Secure Transfer of Textual Data via Edges Guardspace, Win11 Version</u></a></li>
<li><a href="https://windows11.techidaily.com/keyboard-and-mouse-failure-windows-11-sleep-troubleshoot/"><u>Keyboard & Mouse Failure: Windows 11 Sleep Troubleshoot</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-navigating-exit-the-guide-to-disconnecting-from-a-discord-community/"><u>[New] 2024 Approved  Navigating Exit  The Guide to Disconnecting From a Discord Community</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/ideal-cameras-to-elevate-live-stream-engagement-on-twitch/"><u>Ideal Cameras to Elevate Live Stream Engagement on Twitch</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-pc-issues-amidst-minimum-specifications-and-intel-graphic-errors/"><u>Rectifying PC Issues Amidst Minimum Specifications and Intel Graphic Errors</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-find-your-ideal-21-hdmi-display-a-comparative-overview/"><u>2024 Approved  Find Your Ideal 2.1 HDMI Display  A Comparative Overview</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-iphone-techniques-for-video-opposite-playback/"><u>[New] IPhone Techniques for Video Opposite Playback</u></a></li>
<li><a href="https://windows11.techidaily.com/resolve-poor-internet-access-in-windows-apps-now/"><u>Resolve Poor Internet Access in Windows Apps Now</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/eyedome-recorder-chromeos-screen-snapshots/"><u>EyeDome Recorder  ChromeOS Screen Snapshots</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-restore-windows-photo-viewer-in-windows-1111/"><u>How to Restore Windows Photo Viewer in Windows 11/11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-intercept-text-messages-on-xiaomi-redmi-a2-drfone-by-drfone-virtual-android/"><u>In 2024, How to Intercept Text Messages on Xiaomi Redmi A2 | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/why-is-ipogo-not-working-on-oneplus-ace-2v-fixed-drfone-by-drfone-virtual-android/"><u>Why is iPogo not working On OnePlus Ace 2V? Fixed | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-skyrocketing-view-figures-by-sustaining-youtubes-creative-commons-license/"><u>[New] Skyrocketing View Figures by Sustaining YouTube's Creative Commons License</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-audio-liberation-from-youtube-three-safe-methods/"><u>2024 Approved  Audio Liberation From YouTube  Three Safe Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/revive-vanished-steam-game-icons-immediately/"><u>Revive Vanished Steam Game Icons Immediately</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-bypass-windows-defenders-exclusive-software-lockdown/"><u>How to Bypass Windows Defender's Exclusive Software Lockdown</u></a></li>
<li><a href="https://windows11.techidaily.com/masterful-methods-to-overcome-security-errors-in-windows-11/"><u>Masterful Methods to Overcome Security Errors in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-visibility-of-missing-cameras-on-device-management-screen/"><u>Enhance Visibility of Missing Cameras on Device Management Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/enablingdisabling-text-emphasis-in-windows-11/"><u>Enabling/Disabling Text Emphasis in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/easily-solve-nvidiae-experience-scanner-woes-on-windows/"><u>Easily Solve Nvidia'e Experience Scanner Woes on Windows</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-sonic-visuals-on-the-move-a-deep-dive-into-sonys-xperia-xz/"><u>2024 Approved  Sonic Visuals on the Move - A Deep Dive Into Sony's Xperia XZ</u></a></li>
<li><a href="https://windows11.techidaily.com/discerning-win-credentials-success-from-failure-scenarios/"><u>Discerning Win Credentials Success From Failure Scenarios</u></a></li>
<li><a href="https://network-issues.techidaily.com/stabilize-line-artwork-precision/"><u>Stabilize Line Artwork Precision</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-microsoft-store-error-0x00000000-in-windows-os/"><u>Eliminating Microsoft Store Error 0X00000000 in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-through-utorrent-sync-failures-on-windows-devices/"><u>Guiding Through uTorrent Sync Failures on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-tweak-the-mouse-pointer-accessibility-settings-on-windows-11/"><u>How to Tweak the Mouse Pointer Accessibility Settings on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/get-rid-of-the-standout-wallpaper-icon-in-win11/"><u>Get Rid of the Standout Wallpaper Icon in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tuning-win11-startup-processes/"><u>Fine-Tuning Win11 Startup Processes</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-samsung-galaxy-a05-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Samsung Galaxy A05 to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/howtomakenotepadwindowssmoothatnight/"><u>HowToMakeNotepadWIndowsSmoothAtNight</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/uninterrupted-snapstreaks-achievable-or-impossible-for-2024/"><u>Uninterrupted Snapstreaks  Achievable or Impossible for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/full-tutorial-to-bypass-your-motorola-moto-g34-5g-face-lock-by-drfone-android/"><u>Full Tutorial to Bypass Your Motorola Moto G34 5G Face Lock?</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/mastering-cross-platform-collaboration-your-youtube-and-tiktok-guide/"><u>Mastering Cross-Platform Collaboration  Your YouTube & TikTok Guide</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-enhanced-engagement-with-effective-youtube-video-outros-strategies/"><u>[New] In 2024, Enhanced Engagement with Effective YouTube Video Outros Strategies</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-wiped-call-history-on-redmi-note-12-pro-5g-by-fonelab-android-recover-call-logs/"><u>How to restore wiped call history on Redmi Note 12 Pro 5G?</u></a></li>
<li><a href="https://windows11.techidaily.com/monitoring-login-trials-detecting-successfulfailed-windows-access/"><u>Monitoring Login Trials: Detecting Successful/Failed Windows Access</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-system-stability-post-windows-update-with-wsl-in-focus/"><u>Enhancing System Stability Post-Windows Update with WSL in Focus</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11-for-sticky-note-usage/"><u>Navigating Windows 11 for Sticky Note Usage</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-effortless-offline-viewing-how-to-save-youtube-videos-for-iphoneipad/"><u>[New] Effortless Offline Viewing  How to Save YouTube Videos for iPhone/iPad</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-music-from-oppo-reno-10-pro-5g-by-fonelab-android-recover-music/"><u>How to Rescue Lost Music from Oppo Reno 10 Pro 5G</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-expert-video-grabbing-kit-perfect-for-firefox-browser-users-for-2024/"><u>[New] Expert Video Grabbing Kit  Perfect for FireFox Browser Users for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-compact-icons-arrangement-in-system-interface/"><u>Fixing Compact Icons Arrangement in System Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-absence-of-display-in-boot-process/"><u>Remedying Absence of Display in Boot Process</u></a></li>
</ul></div>
