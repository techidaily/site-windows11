---
title: Recover Lost Windows Customizations on Reboot
date: 2024-07-11T22:01:48.212Z
updated: 2024-07-12T22:01:48.212Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Recover Lost Windows Customizations on Reboot
excerpt: This Article Describes Recover Lost Windows Customizations on Reboot
keywords: Regain Windows Settings Post-Reboot,Restore PC Window Preferences,Retrieve Customized Windows,Reclaim Windows Layout,Reinstate Windows Theme,Resurrect Lost Windows,Reboot Windows Configs
thumbnail: https://thmb.techidaily.com/fe961e2cb838e9277b3f939887a164216256186200a3f57210ef49bd6287bae1.jpg
---

## Recover Lost Windows Customizations on Reboot

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
<li><a href="https://windows11.techidaily.com/how-to-enhance-copy-paste-efficiency-across-browsers/"><u>How to Enhance Copy-Paste Efficiency Across Browsers</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-customize-and-reset-your-command-prompt/"><u>Guide to Customize and Reset Your Command Prompt</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-terminal-for-quake-in-windows/"><u>Configuring Terminal for Quake in Windows</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-windows-10-dvd-playback-made-easy-top-10-free-players/"><u>New In 2024, Windows 10 DVD Playback Made Easy Top 10 Free Players</u></a></li>
<li><a href="https://audio-editing.techidaily.com/15-best-montage-music-for-different-video-types/"><u>15 Best Montage Music for Different Video Types</u></a></li>
<li><a href="https://windows11.techidaily.com/maintaining-constant-calc-display-in-windows/"><u>Maintaining Constant Calc Display in Windows</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-ending-grey-shades-in-live-stream-translations/"><u>In 2024, Ending Grey Shades in Live Stream Translations</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-the-dichotomy-microsoft-vs-native-user-account-on-windows-os/"><u>Dissecting the Dichotomy: Microsoft vs Native User Account on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-advice-for-seamlessly-entering-fullscreen-mode/"><u>Expert Advice for Seamlessly Entering Fullscreen Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-tips-for-efficient-toolbar-usage-in-microsoft-win11-pcm/"><u>Advanced Tips for Efficient Toolbar Usage in Microsoft Win11 PCM</u></a></li>
<li><a href="https://windows11.techidaily.com/6-quick-ways-to-fix-the-powerpoint-cant-save-file-error-in-windows-11/"><u>6 Quick Ways to Fix the PowerPoint Can't Save File Error in Windows 11</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-2023s-secretive-vids-downloader-list-top-8-edition/"><u>[Updated] In 2024, 2023'S Secretive Vids Downloader List  Top 8 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-the-maze-of-windows-error-code-0xc00000f/"><u>Navigating Through the Maze of Windows Error Code 0Xc00000f</u></a></li>
<li><a href="https://windows11.techidaily.com/initiating-chatgpt-with-windows-operating-system/"><u>Initiating ChatGPT with Windows Operating System</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-win-os-extract-issues-saving-time-with-error-1152-solution/"><u>Overcoming Win OS Extract Issues: Saving Time with Error 1152 Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-convergence-of-windows-and-wsl-with-win-11-upgrade/"><u>Ensuring Convergence of Windows & WSL with Win 11 Upgrade</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-resolving-winirq-conflicts-for-clear-audio/"><u>Decoding and Resolving WinIRQ Conflicts for Clear Audio</u></a></li>
<li><a href="https://windows11.techidaily.com/cut-the-clutter-quickly-reduce-programs-with-system-tray-keys/"><u>Cut the Clutter: Quickly Reduce Programs with System Tray Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-stable-windows-printer-connections/"><u>Ensuring Stable Windows-Printer Connections</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-interactive-content-the-key-to-boosted-facebook-pages/"><u>[New] Interactive Content  The Key to Boosted Facebook Pages</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/detailed-review-of-doctorsim-unlock-service-for-apple-iphone-15-drfone-by-drfone-ios/"><u>Detailed Review of doctorSIM Unlock Service For Apple iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-the-nvidia-setup-not-available-glitch/"><u>Fixing the 'Nvidia Setup Not Available' Glitch</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-discord-updates-from-triggering-at-system-startup/"><u>Preventing Discord Updates From Triggering at System Startup</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-pointer-design-in-microsoft-systems/"><u>Customize Pointer Design in Microsoft Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/overcome-hurdles-in-windows-hello-fingerprint-failures/"><u>Overcome Hurdles in Windows Hello Fingerprint Failures</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-vivetool-your-ticket-to-access-latest-windows-innovations/"><u>Discover ViVeTool: Your Ticket to Access Latest Windows Innovations</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-integration-portable-software-menus-for-w11plus/"><u>Easy Integration: Portable Software Menus for W11+</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicating-your-input-cant-be-opened-vlc-error/"><u>Eradicating 'Your Input Can't Be Opened' VLC Error</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-advanced-control-enhancing-your-live-broadcast-experience-for-2024/"><u>[Updated] Advanced Control  Enhancing Your Live Broadcast Experience for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/expertly-blending-tracks-using-audacity-crossfade-tools/"><u>Expertly Blending Tracks Using Audacity Crossfade Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-error-printer-spooler-not-active-on-windows/"><u>Overcoming Error: “Printer Spooler Not Active” On Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/curating-edthemes-experience-on-windows-11/"><u>Curating EdThemes Experience on Windows 11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-go-green-for-effective-ctas-via-subscription/"><u>2024 Approved  Go Green for Effective CTAs via Subscription</u></a></li>
<li><a href="https://windows11.techidaily.com/dive-into-digital-dreams-with-paint-cocreator-and-windows-11-creating-vivid-ai-visuals/"><u>Dive Into Digital Dreams with Paint Cocreator & Windows 11, Creating Vivid AI Visuals</u></a></li>
<li><a href="https://win11.techidaily.com/reinstalling-windows-11-step-by-step-guide/"><u>Reinstalling Windows 11: Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/instructions-for-resetting-customized-windows-settings/"><u>Instructions for Resetting Customized Windows Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-sniping-techniques-alternatives-to-windows-snipping-capability/"><u>Quick Sniping Techniques: Alternatives to Windows' Snipping Capability</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-windows-11-camera-app-error-0xa00f425d-fixes/"><u>Disabling Windows 11 Camera App Error 0xA00F425D Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/meeting-prep-101-test-your-windows-webcam-microphone/"><u>Meeting Prep 101: Test Your Windows Webcam, Microphone</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-machine-wattage-determining-computational-power-use/"><u>Windows Machine Wattage: Determining Computational Power Use</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-at-learning-7-efficient-techniques-for-windows/"><u>Winning at Learning: 7 Efficient Techniques for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-unpredictable-power-estimator-display-on-windows-11/"><u>Correcting Unpredictable Power Estimator Display on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/essentials-of-implementing-windows-law-filters-effectively/"><u>Essentials of Implementing Windows LAW Filters Effectively</u></a></li>
<li><a href="https://vp-tips.techidaily.com/insightful-analysis-the-phenomenon-of-mixed-reality-for-2024/"><u>Insightful Analysis  The Phenomenon of Mixed Reality for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-shift-script-moving-windows-11-selected-files/"><u>Quick Shift Script: Moving Windows 11 Selected Files</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-windows-11-video-tools-list/"><u>Essential Windows 11 Video Tools List</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-ultimate-step-by-step-youtube-editing-walkthrough/"><u>2024 Approved  The Ultimate Step-by-Step YouTube Editing Walkthrough</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-the-screencast-primer-fundamental-knowledge-for-video-enthusiasts/"><u>[Updated] In 2024, The Screencast Primer  Fundamental Knowledge for Video Enthusiasts</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-monochrome-errors-with-marketplace/"><u>Fixing Monochrome Errors with Marketplace</u></a></li>
</ul></div>
