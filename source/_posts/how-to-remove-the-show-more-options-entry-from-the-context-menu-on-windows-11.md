---
title: How to Remove the Show More Options Entry From the Context Menu on Windows 11
date: 2024-07-11T22:06:46.680Z
updated: 2024-07-12T22:06:46.680Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Remove the Show More Options Entry From the Context Menu on Windows 11
excerpt: This Article Describes How to Remove the Show More Options Entry From the Context Menu on Windows 11
keywords: Remove Show More in Menu,Hide Context Menu Options,Disable Show More,Eliminate Extra Menu Items,Minimize UI Clutter,Reduce Context Overflow,Tidy Windows Menu
thumbnail: https://thmb.techidaily.com/71ccc2fedcffdaa9357153f28278ee3778285e29e6f3d8460fc68588e03103f5.jpg
---

## How to Remove the Show More Options Entry From the Context Menu on Windows 11

 Windows 11 comes with a fresh new look and has mainly got a positive response for its new interface. However, there are a couple of features that are not being welcomed by the users. For instance, the addition of the "show more options" entry to the right-click context menu.

 Although it was introduced to simplify things, many users still prefer the old context menu from Windows 10\. Fortunately, you can remove Show more options from the context menu on Windows 11 by following the below methods.

## 1\. How to Remove "Show More Options" From the Context Menu With Folder Options

 The [Windows Folder Options](https://www.makeuseof.com/windows-folder-options-guide/) in File Explorer is the go-to place to view and manage File Explorer settings. You can use it to [enable compact view in File Explorer on Windows 11](https://www.makeuseof.com/how-to-enable-compact-view-windows-11-file-explorer/) , manage file thumbnails, remove the "show more options" entry, and much more.

 Here's how to use the folder option to remove the "show more options" entry from the context menu:

1. Press the**Win + E** hotkey to open the**File Explorer.**
2. Click the three horizontal dots at the top bar and choose**Options.**
3. In the**Folder Options,** switch to the**View** tab.
4. Check the**Launch folder** **windows in a separate process** box.  
![Launch folder windows in a separate process box in the Folder option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/launch-folder-windows-in-a-separate-process-box.jpg)
5. Click**Apply** \>**OK** to save the changes.

Next, restart your computer for the changes to take effect.

## 2\. Remove Show More Options From the Context Menu Using the Command Prompt

 If you're a power user, you can use Command Prompt to remove the "show more options" entry from the context menu. Here's how:

1. Open the**Start Menu** by pressing the**Win** key.
2. In the search bar, type**Command Prompt** and choose**Run as administrator** from the right pane.
3. Click**Yes** to the UAC that crops up.
4. In the elevated Command Prompt window, type the following command and press**Enter** :  
`reg add "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f /ve`

![Command to Remove Context menu in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/command-to-remove-context-menu.jpg)

 After executing the command, you'll see the "The operation completed successfully" message to confirm that it went through.

 Now, you will have to restart Windows Explorer to see the changes. To do that, open the**Task Manager** (see how to [launch the Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) ), right-click on**Windows Explorer,** and choose**Restart.**

 Check if you can see the changes. If not, then you will have to restart your computer for the changes to take effect.

 In the future, if you want to add the "show more options" entry to the context menu, then open Command Prompt with admin rights and run the following command:

`reg delete "HKEY_CURRENT_USER\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}" /f​`

## 3\. Remove Show More Options From the Context Menu Using the Registry Editor

 Another quick way to remove the "show more options" entry is through the Registry Editor. Here's what you need to do:

 Before making any changes to the registry, ensure you've [created a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) or [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . This will ensure your system settings and files are secure, and you can quickly access them if something goes wrong.

1. Open the Start Menu, type**Registry Editor** in the search bar, and press Enter.
2. In the Registry Editor, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID`
3. Right-click on the empty space on the right pane, click**New,** and then select**DWORD** **(32-bit) Value** from the context menu.
4. Name the value as**"UndockingDisabled"** and press**Enter** .  
![UndockingDisabled entry in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/undockingdisabled-entry.jpg)
5. Double-click on the UndockingDisabled key, type**1** in the**Value data,** and click**OK** to save the changes.  
![Editing UndockingDisabled in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/editing-undockingdisabled.jpg)

## 4\. Remove the "Show More Options" Entry From the Context Menu Using Winaero Tweaker

 There are plenty of third-party tools using which you can customize the look of your Windows 11 computer. For this guide, we will use Winaero Tweaker.

 Here's how to download Winaero Tweaker and use it to remove the "show more options" entry from the context menu:

1. Download the [Winaero Tweaker zip file](https://winaero.com/downloads/winaerotweaker.zip) on your computer.
2. Unzip the file, open the executable, and then follow the on-screen instructions to install it on your computer.
3. Launch Winaero Tweaker and choose the**Classic Full Context Menus** option from the left sidebar.  
![Classic Full Context Menus option of Winaero](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/classic-full-context-menus-option.jpg)
4. Check the**Enable classic full context menus** box.  
![Enable classic full context menus option in Winaero](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-classic-full-context-menus.jpg)
5. Click the**Restart Explorer** button that appears.

## Enjoy an Old School Context Menu on Windows 11

 The desktop context menu lets you quickly access areas like the personalization menu, display settings, and much more. In Windows 11, you get the new "Show more options" entry in the context menu. But if you prefer the old design, you can quickly disable the "Show more options" entry from the context using either of the above methods.


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
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-correcting-roblox-error-262/"><u>Mastering the Art of Correcting Roblox Error 262</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-unlock-realme-11-5g-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>In 2024, Unlock Realme 11 5G Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-ethereal-time-extended-recording/"><u>2024 Approved  Ethereal Time-Extended Recording</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-apple-image-import-failures-in-windows-10-and-11/"><u>Solutions for Apple Image Import Failures in Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/swapping-windows-11s-standard-programs-best-choices/"><u>Swapping Windows 11'S Standard Programs: Best Choices</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/deciphering-ios-mechanism-for-image-capture-for-2024/"><u>Deciphering IO's Mechanism for Image Capture for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/11-common-windows-11-problems-with-easy-solutions/"><u>11 Common Windows 11 Problems With Easy Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/maximize-mouse-efficiency-altering-double-click-speed-in-windows/"><u>Maximize Mouse Efficiency: Altering Double-Click Speed in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-new-horizinas-with-ease-top-8-windows-11-avoidances/"><u>Navigating New Horizinas with Ease: Top 8 Windows 11 Avoidances</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-2024-approved-navigating-spatial-audio-management-a-guide-to-efficient-ducking-in-video-production/"><u>New 2024 Approved Navigating Spatial Audio Management A Guide to Efficient Ducking in Video Production</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-14-plus-without-passcode-or-face-id-drfone-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone 14 Plus without Passcode or Face ID | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-guide-syncing-with-apples-calendar-app/"><u>Windows 11 Guide: Syncing with Apple's Calendar App</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-remedy-for-windows-uninitialized-disk-issue/"><u>Quick Remedy for Windows 'Uninitialized' Disk Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-discord-from-launching-with-every-system-boots/"><u>Preventing Discord From Launching with Every System Boots</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-master-the-art-of-conducting-virtual-meetings-with-zoom-win10-for-2024/"><u>[Updated] Master the Art of Conducting Virtual Meetings with Zoom (Win10) for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-how-to-blur-background-of-your-youtube-video-2-easy-ways/"><u>[Updated] In 2024, How to Blur Background of Your YouTube Video - 2 Easy Ways</u></a></li>
<li><a href="https://windows11.techidaily.com/proactive-protection-with-powertoys-locksmith-toolkit/"><u>Proactive Protection with PowerToys' Locksmith Toolkit</u></a></li>
<li><a href="https://article-tips.techidaily.com/20-must-have-mp4-devices/"><u>20 Must-Have MP4 Devices</u></a></li>
<li><a href="https://network-issues.techidaily.com/ending-intermittent-windows-display-flashes/"><u>Ending Intermittent Windows Display Flashes</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-package-registration-failures-on-windows-devices/"><u>Resolving Package Registration Failures on Windows Devices</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-cross-platform-creative-dimensioning-techniques/"><u>In 2024, Cross-Platform Creative Dimensioning Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-clearing-xbox-game-pass-errors-on-windows-11-systems/"><u>Strategies for Clearing Xbox Game Pass Errors on Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/tweak-display-posture-in-windows-software/"><u>Tweak Display Posture in Windows Software</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-and-reviving-winget-a-guide-for-windows-11-users/"><u>Navigating and Reviving Winget: A Guide for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/1719382274392-is-your-hardware-upgraded-for-win11-find-out/"><u>Is Your Hardware Upgraded For Win11? Find Out</u></a></li>
<li><a href="https://windows11.techidaily.com/optimal-start-menu-no-commercials-here/"><u>Optimal Start Menu: No Commercials Here!</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-the-soundtrack-to-instagram-fame/"><u>In 2024, The Soundtrack to Instagram Fame</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-22h2-windows-woes/"><u>Navigating Through 22H2 Windows Woes</u></a></li>
<li><a href="https://windows11.techidaily.com/title-managing-icons-alignment-and-separation-on-win-oss/"><u>Title: Managing Icons' Alignment and Separation on WIN OSs</u></a></li>
<li><a href="https://windows11.techidaily.com/supercharge-win11s-notes-via-wise-mentor/"><u>Supercharge Win11's Notes via Wise Mentor</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-application-could-not-find-qt-plugin/"><u>Unblocking Application Could Not Find Qt Plugin</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-change-motorola-edge-40-lock-screen-clock-in-seconds-by-drfone-android/"><u>How To Change Motorola Edge 40 Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://extra-hints.techidaily.com/ultimate-guide-best-zero-cost-image-editors-online/"><u>Ultimate Guide  Best Zero-Cost Image Editors Online</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-xp709-system-failure/"><u>Strategies for XP709 System Failure</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-malfunctioning-outlook-mail-signals-on-pc/"><u>Mending Malfunctioning Outlook Mail Signals on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/revitalize-your-services-explorer-effective-solutions-for-7-common-issues/"><u>Revitalize Your Services Explorer: Effective Solutions for 7 Common Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-error-non-compliant-windows-generic-audio-problems/"><u>Stop Error: Non-Compliant Windows Generic Audio Problems</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-lunar-luster-online-a-curated-list-of-hdr-sky-images/"><u>[Updated] Lunar Luster Online  A Curated List of HDR Sky Images</u></a></li>
<li><a href="https://windows11.techidaily.com/prove-your-prowess-top-7-zero-cost-pc-password-apps/"><u>Prove Your Prowess: Top 7 Zero-Cost PC Password Apps</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-infinix-hot-30-5g-to-other-android-devices-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Infinix Hot 30 5G to Other Android Devices Devices? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-unsupported-drive-issue-in-windows/"><u>Unraveling the 'Unsupported Drive' Issue in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-for-printer-not-available-errors/"><u>Quick Fix for Printer Not Available Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-domain-user-biometric-control-in-windows-11/"><u>Mastering Domain User Biometric Control in Windows 11</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-mastering-youtubes-visual-flow-five-budget-friendly-methods/"><u>In 2024, Mastering YouTube's Visual Flow - Five Budget-Friendly Methods</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-transfer-music-from-itel-a60-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways to Transfer Music from Itel A60 to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-clouds-hurdle-7-ways-to-reconnect-google-drive/"><u>Overcoming the Cloud's Hurdle: 7 Ways to Reconnect Google Drive</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-windows-from-s-mode-shackles/"><u>Unraveling Windows: From S Mode Shackles</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-your-excel-layout-fixing-failed-new-cell-insertions-on-pc/"><u>Reviving Your Excel Layout: Fixing Failed New Cell Insertions on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-ethernet-signal-in-windows-os/"><u>Securing Ethernet Signal in Windows OS</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-premier-toolkit-7-stealth-film-apps/"><u>[New] Premier Toolkit  7 Stealth Film Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-and-linux-how-wsl-changes-the-game/"><u>Windows and Linux: How WSL Changes the Game?</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-mspcm-bar-with-finesse-in-windows-11-environment/"><u>Navigating MSPCM Bar with Finesse in Windows 11 Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-gameplay-low-lag-high-fps-on-roblox-pcs/"><u>Optimizing Gameplay: Low Lag, High FPS on Roblox PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-windows-pre-format-drive-errors/"><u>Solving Windows' Pre-Format Drive Errors</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-ideal-microphones-for-precision-in-4k-video-and-sound-recording/"><u>[New] Ideal Microphones for Precision in 4K Video & Sound Recording</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-dynamic-ui-embracing-the-new-widget-era/"><u>Windows 11'S Dynamic UI: Embracing the New Widget Era</u></a></li>
</ul></div>
