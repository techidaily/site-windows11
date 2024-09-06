---
title: "Strategies to Tackle 'Corrupted' Files & Directories: Win10-11 Edition"
date: 2024-09-05T02:12:53.339Z
updated: 2024-09-06T02:12:53.339Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Strategies to Tackle 'Corrupted' Files & Directories: Win10-11 Edition"
excerpt: "This Article Describes Strategies to Tackle 'Corrupted' Files & Directories: Win10-11 Edition"
keywords: Corrupted Files Fix,File Recovery Strategies,Windows File Repair,Win10/Win11 Corruption Solutions,Directories Cleanup Tips,Data Integrity Restoration,System Directory Rescue
thumbnail: https://thmb.techidaily.com/e6889a658e4bba9c2827feba4ea063c236adc8db7e5b5caf8c7f574f84c4eaab.jpg
---

## Strategies to Tackle 'Corrupted' Files & Directories: Win10-11 Edition

 Error 0x80070570 is a Windows issue that sometimes pops up when you try to delete files on external hard drives. This error also occurs when users try to transfer files between PCs and external drives. The error 0x80070570 message says, “The file or directory is corrupted and unreadable.”

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.

## 1\. Repair System Files With an SFC Scan

 Some users have confirmed repairing system files resolved error 0x80070570 on their PCs. System File Checker is a command-line tool with which you can check for and repair corrupted system files that might be causing file operation issues. Check out our guide to [utilizing System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) for details about how to run an SFC scan within the Command Prompt.

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command2.jpg)

## 2\. Utilize the Check Disk Tool

 Drive file system issues often cause error 0x80070570\. The most widely confirmed solution for that error is to run a CHKDSK scan of the drive you can’t delete files on or transfer files to. The CHKDSK tool can repair file system errors on the drive it’s scanning.

![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/chkdsk-scan-command.jpg)

 Our [guide to running CHKDSK on Windows](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) tells you how to initiate a Check Disk scan. You’ll need to run the Check Disk scan for the drive that includes the files you can’t delete or copy to. If that’s an external drive, you’ll need to connect the storage device to the PC and specify its letter within the command. For example, a CHKDSK command for scanning an external E: drive would be:

`chkdsk /r E:`

## 3\. Try Moving Files to a Different Location

 If error 0x80070570 when you’re trying to transfer a file, try moving (or copying) the file into a different folder location on the target drive. You can do that by right-clicking an affected file and selecting either **Cut** or **Copy**. Then right-click inside a different folder location and select **Paste** to see if the error occurs.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886003/19272" target="_top" id="1886003">
  <img src="//a.impactradius-go.com/display-ad/19272-1886003" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886003/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Turn Off Real-Time Antivirus Shields

 Another possible factor for error 0x80070570 occurring is your PC’s antivirus shield is hindering the file operation. That could happen if your antivirus software wrongly flags files you’re trying to transfer between drives as suspicious. So, try temporarily disabling your antivirus shield before performing the required file operation.

![The Real-time protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/real-time-protection-option.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118323/7443" target="_top" id="2118323">
  <img src="//a.impactradius-go.com/display-ad/7443-2118323" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118323/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If you don’t have third-party security software, turn off Windows Security’s real-time antivirus shield, as covered in our article about [disabling Microsoft Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/). .

 Users with third-party antivirus utilities will need to turn off their antivirus shields via the apps’ system tray context menus. Right-click the antivirus app’s icon in the system tray and select a disable or turn off shield protection setting.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918684/19272" target="_top" id="1918684">
  <img src="//a.impactradius-go.com/display-ad/19272-1918684" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918684/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Perform a Startup Repair

 This resolution is recommended if error 0x80070570 occurs when trying to delete files on the C: hard drive or transfer them there. Startup Repair is primarily a utility for fixing Windows startup issues. However, that tool can remedy corrupted system files and C: drive issues. This is how you can utilize Startup Repair:

1. First, [bring up the Advanced Startup Options menu](https://www.makeuseof.com/windows-11-access-advanced-startup-options/) via the Settings app.
2. Select **Startup Repair** within the Advanced options menu.  
![The Start-up Repair option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-up-repair.jpg)
3. Next, select your Windows user account.
4. Input your user account password.
5. Select **Continue** to initiate the repair.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105874/7443" target="_top" id="2105874">
  <img src="//a.impactradius-go.com/display-ad/7443-2105874" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105874/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Format an External Drive

 Formatting an affected external drive to which you can’t transfer files or delete data because of error 0x80070570 is suggested only as a last resort. Applying this potential fix will wipe all data on the drive, so do not format your PC’s C: drive. However, some users have confirmed formatting affected external drives fixes error 0x80070570\.

![The format drive utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-format-tool.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2024329/7443" target="_top" id="2024329">
  <img src="//a.impactradius-go.com/display-ad/7443-2024329" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2024329/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You can format an external drive with the Windows Disk Management utility or in File Explorer. Connect the drive to your PC, and then follow the steps in this guide on [how to format a USB drive](https://www.makeuseof.com/tag/format-usb-drive/) to do this within File Explorer.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2030381/7443" target="_top" id="2030381">
  <img src="//a.impactradius-go.com/display-ad/7443-2030381" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2030381/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Perform the Required File Operations Again on Windows

 The potential error 0x80070570 solutions covered here have worked for many Windows 11/10 users. Repairing drive errors with the CHKDSK tool usually does the trick. You could also utilize a third-party utility like Hard Disk Sentinel and HDDScan to check for and repair drive issues. With error 0x80070570 fixed, you can copy or delete files as required again.

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-video-capture.techidaily.com/new-discovering-expert-seed-selection-for-valheimers-for-2024/"><u>[New] Discovering Expert Seed Selection for Valheimers for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-discover-the-top-8-services-to-amplify-video-content-for-2024/"><u>[Updated] Discover the Top 8 Services to Amplify Video Content for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-mastering-flight-time-selecting-premium-uav-power-sources/"><u>[Updated] Mastering Flight Time  Selecting Premium UAV Power Sources</u></a></li>
<li><a href="https://unlock-android.techidaily.com/complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-xiaomi-14-by-drfone-android/"><u>Complete Review & Guide to Techeligible FRP Bypass and More For Xiaomi 14</u></a></li>
<li><a href="https://win-blog.techidaily.com/demystifying-wsappx-strategies-for-combating-heavy-disk-and-cpu-consumption/"><u>Demystifying WSAPPX: Strategies for Combating Heavy Disk and CPU Consumption</u></a></li>
<li><a href="https://extra-tips.techidaily.com/essential-steps-for-a-richer-photo-view-with-audio-filters/"><u>Essential Steps for a Richer Photo View with Audio-Filters</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-the-unattainable-package-error-on-windows-10-11/"><u>Fixing the Unattainable Package Error on Windows 10, 11</u></a></li>
<li><a href="https://windows11.techidaily.com/from-ios-to-windows-mastering-the-use-of-imessage/"><u>From iOS to Windows: Mastering the Use of iMessage</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-restoring-malwarebytes-database-connection-on-win-oses/"><u>Guide to Restoring Malwarebytes Database Connection on WIN OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-unable-to-find-the-ubisoft-game-launcher-error/"><u>How to Fix the “Unable to Find the Ubisoft Game Launcher” Error</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-overcome-error-403-in-roblox-windows/"><u>How to Overcome Error 403 in Roblox (Windows)</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-show-wi-fi-password-on-samsung-galaxy-xcover-6-pro-tactical-edition-by-drfone-android/"><u>How to Show Wi-Fi Password on Samsung Galaxy XCover 6 Pro Tactical Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/implementing-user-specific-windows-11-volume-keys/"><u>Implementing User-Specific Windows 11 Volume Keys</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-explore-the-best-photo-enhancement-apps-for-android-and-iphone/"><u>In 2024, Explore the Best Photo Enhancement Apps for Android and iPhone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-eyecapture-master-series-version-x/"><u>In 2024, EyeCapture Master Series - Version X</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-inside-the-magic-box-how-does-vr-function/"><u>In 2024, Inside the Magic Box  How Does VR Function?</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-the-ultimate-iphone-playlist-podcast-tips/"><u>In 2024, The Ultimate iPhone Playlist  Podcast Tips</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-unveiling-the-secrets-of-simultaneous-iphone-shots-and-videos/"><u>In 2024, Unveiling the Secrets of Simultaneous iPhone Shots & Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-use-of-windows-11-desktop-widgets/"><u>Mastering the Use of Windows 11 Desktop Widgets</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-microsoft-store-app-not-installed-issue/"><u>Navigating Microsoft Store App Not Installed Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-network-setbacks-in-obs-studio-windows-edition-7-ways/"><u>Navigating Network Setbacks in OBS Studio, Windows Edition (7 Ways)</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11s-app-guard-for-cammic/"><u>Navigating Windows 11’S App Guard for Cam/Mic</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-your-routine-nircmds-win-commands-for-speed/"><u>Optimize Your Routine: NirCmd's Win Commands for Speed</u></a></li>
<li><a href="https://windows11.techidaily.com/overcome-cc-woes-a-handy-guide-for-win-10-users/"><u>Overcome CC Woes: A Handy Guide for Win 10 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-deadly-script-error-a-win-11-discord-fix-guide/"><u>Overcoming the Deadly Script Error: A Win 11 Discord Fix Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-deadly-windows-error-c0000022-breakdown/"><u>Overcoming the Deadly Window's Error C0000022 Breakdown</u></a></li>
<li><a href="https://windows11.techidaily.com/painting-a-picture-sketching-on-windows-11-devices/"><u>Painting a Picture: Sketching on Windows 11 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/perfect-images-at-fingertips-top-4-webp-viewer-windows/"><u>Perfect Images at Fingertips: Top 4 WebP Viewer Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/personalized-voice-recognition-program-for-windows-whisper-and-autohotkey-methods/"><u>Personalized Voice Recognition Program for Windows: Whisper & AutoHotkey Methods</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-music-from-lava-by-fonelab-android-recover-music/"><u>Possible solutions to restore deleted music from Lava</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-failed-attachment-of-usb-device-to-virtualbox/"><u>Quick Fixes for Failed Attachment of USB Device to VirtualBox</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-ensuring-equal-web-pace-on-your-devices/"><u>Quick Fixes: Ensuring Equal Web Pace on Your Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/refine-outdated-media-mastering-the-madvr-technique-for-windows/"><u>Refine Outdated Media: Mastering the MadVR Technique for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-11-sign-in-issues-quickly/"><u>Resolving Windows 11 Sign-In Issues Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-sync-immediate-notebook-access-after-boot-up/"><u>Seamless Sync: Immediate Notebook Access After Boot-Up</u></a></li>
<li><a href="https://windows11.techidaily.com/smart-sort-how-to-effortlessly-move-folders-in-w11/"><u>Smart Sort: How to Effortlessly Move Folders in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-a-stuck-windows-11-taskbar/"><u>Solutions for a Stuck Windows 11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/start-with-style-not-sponsorship-in-w11/"><u>Start with Style, Not Sponsorship in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-reclaim-your-pcs-lossed-graphic-support/"><u>Steps to Reclaim Your PC's Lossed Graphic Support</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-stop-windows-task-moving-apps/"><u>Strategies to Stop Windows Task Moving Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/supercharge-windows-5-top-auto-click-wizards/"><u>Supercharge Windows: 5 Top Auto Click Wizards</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-solutions-bypassing-user-account-requirements-in-windows/"><u>Swift Solutions: Bypassing User Account Requirements in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-network-link-lost-on-windows/"><u>Tackling Network Link Lost on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-8-best-pomodoro-timers-for-windows/"><u>The 8 Best Pomodoro Timers for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-strategies-to-overcome-steam-login-stalls-rustwindows-approach/"><u>Unveiling Strategies to Overcome Steam Login Stalls: Rust/Windows Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-adding-movescopies-context-menu-commands/"><u>Win 11: Adding Moves/Copies Context Menu Commands</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>