---
title: "Instructional Path: Resetting Windows Preferences Post-Reboot"
date: 2024-07-11T21:16:12.057Z
updated: 2024-07-12T21:16:12.057Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Instructional Path: Resetting Windows Preferences Post-Reboot"
excerpt: "This Article Describes Instructional Path: Resetting Windows Preferences Post-Reboot"
keywords: Reset Windows Settings,Reboot Windows Config,PC Preference Restart,System Reboot Options,Windows Login Adjustment,OS Reboot Customize,Relaunch Windows Props
thumbnail: https://thmb.techidaily.com/a1248d9b4e7ad7b3aedb40cb2befdc93715f7a75414c6458bd1e077bee973ffa.jpg
---

## Instructional Path: Resetting Windows Preferences Post-Reboot

 Imagine you’ve just spent hours tweaking your Windows settings—and then you reboot. What you find is that all changes you made have been reset to default settings. Before you give up and reset your computer to factory defaults, give these solutions a shot.

 In this article, we’ll explain what causes the issue and how you can fix it.

## Why Does Windows Reset Its Settings on Reboot?

 The Windows settings reset on reboot for several reasons. The most common cause is a user profile change, either due to a system update or a user’s action. In other cases, a running background application can corrupt user profiles. This can happen if an application crashes or is not updated. It’s also possible that malware is responsible for the issue.

 Sometimes, if there is a system error or a hardware issue like a faulty hard drive, Windows settings may reset when the computer restarts. This could happen due to an unforeseen power outage.

## How to Fix Windows Settings Resetting Upon Reboot

 The best way to fix Windows settings resetting upon reboot is to identify the cause of the problem and take corrective action. Here are some tips to get your settings back.

### 1\. Look Out for Suspicious Programs

 The first step is to check for malicious programs and other suspicious applications that may be causing your issue. If you find any, remove them immediately and check if it solves the problem. Here's how to do it.

1. Right-click on your Taskbar area and select**Task Manager** from the context menu. You can also press**Ctrl + Shift + Esc** if you prefer using shortcut keys.  
![Look Out for Suspicious Programs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/look-out-for-suspicious-programs.jpg)
2. In the Task Manager window, switch to the**Processes** tab and look for any unfamiliar program or process that is hogging up your system resources.
3. Once you find a suspicious program, right-click on it and select**End task** to terminate the process.
4. Now go to the Windows Control Panel and uninstall the program.

 After uninstalling the program, restart your computer and check if the settings reset issue is resolved.

### 2\. Run Automatic Startup Repair

 If Windows continues to reset its settings upon reboot, you should try running the Automatic Startup Repair feature. This will help fix any system errors or corrupted files that may be causing the issue.

To run Automatic Startup Repair, follow these steps:

1. Press**Win + I** to open the Settings window.
2. From the left-hand menu, click the**System** tab.
3. On the right side of the window, scroll down and click the**Recovery** option.  
![Advanced startup in Recovery options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/advanced-startup-in-recovery-options.jpg)
4. Next to**Advanced startup** , click the**Restart now** button.
5. When your PC restarts, select**Troubleshoot** from the Choose an option screen.
6. Select**Advanced options** and then click**Startup Repair** .  
![Startup repair in Windows 10.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/startup-repair-1.jpg)

 Follow the on-screen instructions to run the automatic repair tool. After you complete the above process, restart your computer and check if it solves the issue.

### 3\. Check Your User Profile

 If the issue persists, check your user profile and make sure it’s not corrupt. If your user profile is corrupted, Windows will reset the settings when you restart. Here’s how to check it:

 Press**Windows + R** to open the Run command. In the dialog box, type**regedit** , and press Enter. If the User Account Control (UAC) window appears, click**Yes** to grant administrative privileges. This will launch the Registry Editor.

On the next screen, navigate to the following path:

`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\ProfileList`

 In the**ProfileList** folder, you should see several profiles starting with**S-1-5** . Each of these profiles corresponds to a user account on your computer. Now you have to identify which profile belongs to your user account.

 To do this, click on each**S-1-5 profile** and look for**ProfileImagePath** in the right pane. Check if anyone of them matches your username.

![Modify Registry to repair user profile](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/modify-registry-to-repair-user-profile.jpg)

 Once you find the correct profile, double-click on the**State** field and change the value from**1 to 0** . Similarly, change the**RefCount** field from**1 to 0** .

 In case the RefCount field is missing in the right pane, you’ll have to create it manually. For this, right-click on the right pane and select**New > DWORD (32-bit) Value** . Name the new value**RefCount** and press**Enter** .

 Then double-click on the newly created RefCount and enter**0** in the Value data field. Click**OK** to save your changes and exit Registry Editor. After this, restart your computer and check whether the settings reset problem is fixed.

### 4\. Create a New User Profile

 If you weren’t able to repair the corrupt profile in the Registry Editor, you may have to [create a new user profile on Windows](https://www.makeuseof.com/windows-11-create-local-user-account/) . Creating a new user profile does not delete the old one, so all your data will remain intact, but you will have to reconfigure your settings. After creating it, log out of your current user account and switch to the newly created one. Check if this fixes the settings reset issue.

### 5\. Uninstall Recent Updates

 Microsoft releases Windows updates periodically to keep your system secure. But sometimes these updates fail to install properly and cause various issues. If you recently installed any programs or updates, uninstall them to check if that fixes the problem.

 You can also try rolling back any drivers that might be causing the issue. To do this, right-click on Start and select**Device Manager** . In the Device Manager window, find the device you want to roll back and right-click on it. Select**Properties** from the context menu and then click on the**Driver** tab.

 Click**Roll Back Driver** and then follow the instructions on-screen to complete the process. After rolling back the driver, restart your computer to apply the changes and check if it solves the settings reset issue.

### 6\. Perform Some Generic Windows Fixes

 There are some general Windows-based fixes you can apply to fix this issue.

[Running your Windows computer in a Clean Boot state](https://www.makeuseof.com/clean-boot-windows-11/) is another way to fix the reset settings problem. Clean Boot helps you identify any third-party applications that might be causing the issue. It stops all non-Microsoft services and programs from running during startup, which helps you pinpoint the cause of the issue.

 If the methods mentioned earlier don't fix the issue,[consider doing a System Restore](https://www.makeuseof.com/windows-11-create-restore-point/) . This will take your computer back to a previous state when it was functioning well.

 Keep in mind that all files and applications installed after the selected restore point will be deleted. To avoid losing important data, create a backup before performing a System Restore.

## Fixing Windows Settings Reset on Reboot

 The Windows settings reset on reboot issue can occur for a number of reasons, including corrupt user profiles, corrupted installed programs or updates, and driver issues. This guide provides several methods to fix this issue. Check out these solutions and see which one work for you.


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
<li><a href="https://windows11.techidaily.com/surviving-windows-11-blue-screen-adopting-11-key-approaches/"><u>Surviving Windows 11 Blue Screen: Adopting 11 Key Approaches</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-preventing-windows-autolock-timed-out/"><u>Tips for Preventing Windows Autolock Timed Out</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-pause-auto-updates-no-more-prompts/"><u>Windows Pause Auto-Updates: No More Prompts!</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-telnet-enablement-steps-explained/"><u>Windows 11 Telnet Enablement Steps Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/reactivating-hidden-remove-option-for-pin-access-control/"><u>Reactivating Hidden 'Remove' Option for PIN Access Control</u></a></li>
<li><a href="https://windows11.techidaily.com/blueprints-to-build-secure-window-for-hardware-unhook/"><u>Blueprints to Build Secure Window for Hardware Unhook</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-user-interface-integrating-emoji-15-into-win11/"><u>Boosting User Interface: Integrating Emoji 15 Into Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/reimagining-microsofts-device-link-capabilities-in-windows-11/"><u>Reimagining Microsoft's Device Link Capabilities in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-importance-of-keeping-active-wins-11-notification-sounds/"><u>The Importance of Keeping Active Wins 11 Notification Sounds</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-renowned-crafters-exquisite-instagram-hlv-designers-online/"><u>[New] Renowned Crafters  Exquisite Instagram HLV Designers Online</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-winerror-x80780119-resolution/"><u>Techniques for WinError X80780119 Resolution</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-app-functionality-after-qt-plugin-initialization-breakdown/"><u>Restoring App Functionality After Qt Plugin Initialization Breakdown</u></a></li>
<li><a href="https://change-location.techidaily.com/preparation-to-beat-giovani-in-pokemon-go-for-vivo-v29-pro-drfone-by-drfone-virtual-android/"><u>Preparation to Beat Giovani in Pokemon Go For Vivo V29 Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-camera-app-malfunction-in-windows-11/"><u>Addressing Camera App Malfunction in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-non-functional-inbox-alerts-on-windows-os/"><u>Tackling Non-Functional Inbox Alerts on Windows OS</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-in-2024-the-ultimate-list-5-free-video-stabilizer-apps-for-android-users/"><u>Updated In 2024, The Ultimate List 5 Free Video Stabilizer Apps for Android Users</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-overcoming-connectivity-issues-in-remote-recording/"><u>[Updated] 2024 Approved  Overcoming Connectivity Issues in Remote Recording</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-recording-skype-meetings-on-modern-operating-systems/"><u>[Updated] In 2024, Recording Skype Meetings on Modern Operating Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-to-repair-keyboard-issues-with-windows-snipper/"><u>Tips to Repair Keyboard Issues with Windows Snipper</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-icloud-separation-how-to-disconnect-iphone-14-pro-and-ipad-by-drfone-ios/"><u>In 2024, iCloud Separation How To Disconnect iPhone 14 Pro and iPad</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-regain-lost-connection-on-pcs-running-windows/"><u>Strategies to Regain Lost Connection on PCs Running Windows</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-maximize-space-free-20plus-storage-options-with-limits-up-to-1tb/"><u>[Updated] Maximize Space  Free 20+ Storage Options With Limits (Up To 1TB)</u></a></li>
<li><a href="https://windows11.techidaily.com/start-up-synergy-for-notes-windows-plus-sticky-notes-together/"><u>Start-Up Synergy for Notes: Windows + Sticky Notes Together</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/in-2024-how-to-start-a-video-editing-career/"><u>In 2024, How to Start a Video Editing Career</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/top-20-adobe-premiere-shortcuts-you-will-use/"><u>Top 20 Adobe Premiere Shortcuts You Will Use</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-skill-elevation-rising-through-the-ranks-in-designing/"><u>[New] Skill Elevation  Rising Through the Ranks in Designing</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/5-best-alternatives-to-tiktok-you-should-know/"><u>5 Best Alternatives to TikTok You Should Know</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-the-elusive-gpeditmsc-error-in-windows/"><u>Remedying the Elusive Gpedit.msc Error in Windows</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-unbrick-a-dead-tecno-spark-10-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Unbrick a Dead Tecno Spark 10 5G | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-new-guide-how-to-check-icloud-activation-lock-status-on-your-iphone-14-plus-by-drfone-ios/"><u>In 2024, New Guide How To Check iCloud Activation Lock Status On Your iPhone 14 Plus</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-for-fixing-unopenable-windows-folders-on-double-click/"><u>Tactics for Fixing Unopenable Windows Folders on Double-Click</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-nvidia-opengl-glitches-in-windows-11/"><u>Troubleshooting NVIDIA OpenGL Glitches in Windows 11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-exploring-2023s-standout-professional-360cameras/"><u>[Updated] Exploring 2023'S Standout Professional 360°Cameras</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-diagnostics-enhancing-windows-11-troubleshooters/"><u>Reviving Diagnostics: Enhancing Windows 11 Troubleshooters</u></a></li>
<li><a href="https://extra-resources.techidaily.com/unlocking-tiktok-video-potential-with-zoom/"><u>Unlocking TikTok Video Potential with Zoom</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-and-tricks-solving-the-try-connecting-bluetooth-issue/"><u>Tips and Tricks: Solving the 'Try Connecting' Bluetooth Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-role-of-ai-in-windows-11-updates/"><u>Unveiling the Role of AI in Windows 11 Updates</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-pause-life360-location-sharing-for-vivo-y27-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How To Pause Life360 Location Sharing For Vivo Y27 5G | Dr.fone</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-in-2024-expert-video-exposure-correction-tools/"><u>Updated In 2024, Expert Video Exposure Correction Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/the-anticipation-surrounding-windows-11s-moment-22h2/"><u>The Anticipation Surrounding Windows 11’S Moment #22H2</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-power-start-cmd-as-administrator/"><u>Boosting Power: Start CMD as Administrator</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-the-art-of-selecting-podcasts-for-iphone-devices-for-2024/"><u>[Updated] The Art of Selecting Podcasts for iPhone Devices for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/winerror-correction-bypassing-the-perplexing-0x80072746-mail-issue/"><u>WinError Correction: Bypassing the Perplexing 0X80072746 Mail Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-secure-logins-with-5-tips-against-key-conflicts-in-win11/"><u>Streamlining Secure Logins with 5 Tips Against Key Conflicts in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/reconnecting-bluetooth-on-windows-audio-only-fix-guide/"><u>Reconnecting Bluetooth on Windows: Audio Only Fix Guide</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-screencaptureelite-the-5-star-apeaksoft-evaluation/"><u>[New] ScreenCaptureElite – The 5-Star Apeaksoft Evaluation</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-making-excel-viewable-in-notepad/"><u>Strategies: Making Excel Viewable in Notepad</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-causes-of-pc-disk-issues/"><u>Addressing Causes of PC Disk Issues</u></a></li>
</ul></div>
