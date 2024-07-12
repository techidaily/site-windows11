---
title: Troubleshooting Windows' Error X80780119
date: 2024-07-11T22:03:04.457Z
updated: 2024-07-12T22:03:04.457Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Windows' Error X80780119
excerpt: This Article Describes Troubleshooting Windows' Error X80780119
keywords: Windows Error Fixing Guide,X80780119 Resolution Steps,Troubleshoot X80780119 Error,Solving Windows X80780119 Issue,X80780119 Fix in Windows 10,How to Fix X80780119 on PC,Resolve Windows X80780119 Error
thumbnail: https://thmb.techidaily.com/ed85d5260878e7afe5eab5cc1189d2e4580a5c9f5e7d77e30ca04d5bf449b804.jpg
---

## Troubleshooting Windows' Error X80780119

 Creating a system image backup is essential in protecting your data and ensuring system recoverability, but the process of doing so might not always go smoothly. One such error that the users often encounter is the System Restore error 0x80780119, which prevents the users from completing the backup process.

 Below, we take a look at the common causes of this issue and discuss the different solutions you can try to get rid of this error for good.

## Why Are You Unable to Create a System Image?

 If you are unable to create a system image due to the error 0x80780119, it might be because of one or more of the following reasons:

* **Insufficient disk space**: Restore points take up space in the drive they are saved, and so to create new restore points on your computer, you must have sufficient disk space available. In case you are running out of space on your system, you are likely to face the error at hand.
* **Incorrect backup settings**: Your backup settings must be configured correctly. If there is an issue with these settings, the System Restore will encounter issues while creating a restore point.
* **External drive issues**: If you are using an external drive for backup, it is essential to ensure that it is connected to the system properly and is functioning. In case there is an issue with the external drive due to any of these problems, the System Restore utility might return the error 0x80780119\.
* **Corrupt system files**: The critical system files that are essential to create restore points and use the System Restore utility might have gotten corrupt, which is leading to the error under discussion.
* **Antivirus interruption**: If you are using a security program on your computer, there is a chance that it is blocking the restore tool from functioning properly. This typically happens when you are using a third-party antivirus solution.

 Regardless of what might be resulting in the problem in your case, the solutions we have listed below are sure to help you get the restore utility back on track. Proceed with the solutions one by one and follow the steps carefully for successful execution.

## 1\. Free Up Disk Space

 When you create a restore point in Windows, the system requires sufficient space on the destination drive to store all the backup files. If you do not have enough space, the System Restore is likely to return errors like the 0x80780119 error.

 This is why, before moving onto the complex troubleshooting methods, we recommend you ensure you have sufficient space available on the destination drive. If you are low on space, you can free it up by removing unnecessary files. Here are a few areas to focus on:

* **Temporary files**: Temporary files and other unnecessary data can be cleaned up by [using the Disk Cleanup tool](https://www.makeuseof.com/tag/best-way-clean-windows-10-step-step-guide/). It will list down all such files, and you can then specify which to remove. Simply type “Disk Cleanup” in the search area on your taskbar and click **Open** to launch the utility.
* **Downloads folder**: Access the Download folder in File Explorer and delete all the files you no longer need.
* **Uninstall unused programs**: If there are apps that you do not use anymore, head over to the Control Panel to uninstall them from the system. This will free up a great amount of space that can be used by the System Restore utility.

 In case you have large files or folders that you do not want to remove but also don’t need immediately, you can consider moving them to an external drive to free up space.

## 2\. Check and Repair Disk Errors

 You might also be facing the system restore issue due to disk errors in the system.

 During the backup process, the system needs to read data from the targeted disk and write it to the backup destination. If there is an issue with the disk, the system may have issues reading the data or might write corrupted data in the backup file, which can result in different errors.

 Additionally, your disk might have bad sectors which cannot store data properly and might also prevent the system from reading data during the backup process.

 To ensure this isn’t the case in your situation, it is best to check the disk for errors using the built-in utilities offered by Windows. The first tool that we recommend [using is the CHKDSK utility](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) which can be used via Command Prompt. It works by scanning the system and checking the integrity of the disk. If a problem is identified, CHKDSK will attempt to fix it automatically.

 Alternatively, you can head over to the File Explorer and follow these steps:

1. In File Explorer, head over to the root of the drive you want to check and right-click on it.
2. Choose **Properties** from the context menu.
3. In the Properties dialog, navigate to the **Tools** tab and move to the **Error checking** section.
4. Click on the **Check** button here and wait for the system to complete the scan. This may take some time, depending upon the size of your disk.  
![Run the error checking tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/error-checking-tool.jpg)

 If any issues are found, Windows will prompt you to repair them. Follow the on-screen instructions to proceed.

## 3\. Enable System Protection

 Several users also noticed that they were facing the problem due to the system protection feature being disabled for the targeted drive. If you have this option disabled in your system, we suggest enabling it and checking if that makes any difference.

 Here is how you can do that:

1. Press the **Win** \+ **I** keys together to open the Settings app.
2. Navigate to **System** \> **About**.
3. Head over to the **Device specifications** section and click on the **System protection** option.  
![Click on the System protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-protection-options.jpg)
4. In the following dialog, head over to the **System Protection** tab.
5. Choose the targeted drive and click on the **Configure** button.  
![Click on the Configure button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/configure-button.jpg)
6. Enable the **Turn on system protection** option and click **Apply** \> **OK** to save the changes.  
![Enable system protection](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/enable-system-protection.jpg)

 You can now close the System Protection dialog and check if the issue is resolved.

## 4\. Delete USN Journal

 The USN Journal (Update Sequence Number Journal) is a feature in the NTFS file system that tracks all the changes made on a disk. It is stored in the reserved partition and over time, it can consume a significant amount of your disk space, which may be preventing a restore point from being created.

 You can reclaim this disk space by deleting the USN Journal. Doing so will also eliminate the possibility of any conflicts that might be arising due to inconsistencies between the journal and the files being backed up.

 Here is how you can do that:

1. Type "Create and format hard disk partitions" in Windows search and click **Open**.
2. In the following window, right-click on the **System Reserved** volume and choose **Change Drive Letter and Paths** from the context menu.
3. Now, click on the **Add** button.
4. In the next dialog, choose **Assign the following drive letter** and click **OK**.  
![Change the USB Drive Letter Using Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/change-the-usb-drive-letter-using-disk-management.jpg)
5. Once done, press the **Win** \+ **R** keys together to open Run.
6. Type "cmd" in Run and click **Ctrl** \+ **Shift** \+ **Enter** to open Command Prompt as an administrator.
7. Confirm your action in the UAC prompt.
8. Execute the following commands in Command Prompt one by one:  
`fsutil usn queryjournal F:fsutil usn deletejournal /N /D F:`

 After the commands are executed, you can close Command Prompt and check if the issue is resolved.

## Create a Backup Without Any More Errors on Windows

 Ensuring the protection of your data should be your foremost priority, and a system image backup plays a vital role in safeguarding against unforeseen data loss. With the solutions above, you should be able to get the System Restore utility up and running in no time. However, if the problem persists, you can consider reporting the issue to Microsoft and try the specific solutions they suggest. Till then, you can switch to a third-party backup tool to safeguard your data.

 Below, we take a look at the common causes of this issue and discuss the different solutions you can try to get rid of this error for good.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/mastering-windows-fixing-exit-code-errors/"><u>Mastering Windows: Fixing Exit Code Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/realign-your-windows-clock-through-chrome-settings/"><u>Realign Your Windows Clock Through Chrome Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/revealing-the-make-of-your-windows-machine-in-six-steps/"><u>Revealing the Make of Your Windows Machine in Six Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/resetting-the-explorer-view-for-better-management/"><u>Resetting the Explorer View for Better Management</u></a></li>
<li><a href="https://windows11.techidaily.com/simplify-your-workflow-adding-context-menu-assistance/"><u>Simplify Your Workflow: Adding Context Menu Assistance</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-unfreezing-photo-booth-recordings-a-guide-to-smoother-playback/"><u>2024 Approved  Unfreezing Photo Booth Recordings  A Guide to Smoother Playback</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-transforming-gamers-with-funimate-knowledge/"><u>2024 Approved  Transforming Gamers with Funimate Knowledge</u></a></li>
<li><a href="https://windows11.techidaily.com/top-7-fixes-for-rename-restrictions-on-files-and-directories-of-windows-11/"><u>Top 7 Fixes for Rename Restrictions on Files and Directories of Windows 11</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/maximizing-your-android-game-adventure-with-kinemaster-review-for-2024/"><u>Maximizing Your Android Game Adventure with KineMaster Review for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-new-reset-limit-on-account-lockouts-in-windows-1011/"><u>Setting New Reset Limit on Account Lockouts in Windows 10/11</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-the-ultimate-guide-to-enhancing-tiktok-video-themes/"><u>[Updated] 2024 Approved  The Ultimate Guide to Enhancing TikTok Video Themes</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-leaving-s-mode-on-win-1110/"><u>The Ultimate Guide: Leaving S Mode on Win 11/10</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerate-vm-performance-on-windows-6-precise-tips-and-tricks/"><u>Accelerate VM Performance on Windows: 6 Precise Tips & Tricks</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/hot-30i-video-recovery-recover-deleted-videos-from-hot-30i-by-fonelab-android-recover-video/"><u>Hot 30i Video Recovery - Recover Deleted Videos from Hot 30i</u></a></li>
<li><a href="https://windows11.techidaily.com/ceasing-chrome-notifications-on-windows-desktop/"><u>Ceasing Chrome Notifications on Windows Desktop</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-paving-the-way-to-success-with-professional-insights-into-youtube-banners/"><u>2024 Approved  Paving the Way to Success with Professional Insights Into YouTube Banners</u></a></li>
<li><a href="https://windows11.techidaily.com/trends-in-firmware-enhancement-what-every-surface-user-needs-to-know/"><u>Trends in Firmware Enhancement: What Every Surface User Needs to Know</u></a></li>
<li><a href="https://windows11.techidaily.com/smart-scheduling-for-improved-resource-allocation-on-android-wsl/"><u>Smart Scheduling for Improved Resource Allocation on Android WSL</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-uncontrollable-scroll-troubleshooting-steps/"><u>Windows Uncontrollable Scroll: Troubleshooting Steps</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-freely-accessible-cutting-edge-video-editor-tools/"><u>[New] 2024 Approved  Freely Accessible Cutting Edge Video Editor Tools</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/1719578590735-become-a-home-cooking-wizard-in-just-three-easy-steps/"><u>Become a Home Cooking Wizard in Just Three Easy Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-your-productivity-with-w11-desktop-organization/"><u>Boost Your Productivity with W11 Desktop Organization</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-network-nuances-7-fixes-for-connectivity-in-obs-studio/"><u>Navigating Network Nuances: 7 Fixes for Connectivity in OBS Studio</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-making-intellij-unison-function-in-win11/"><u>Quick Fixes: Making IntelliJ Unison Function in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-windows-11-zoom-malfunction-1132/"><u>Steps to Resolve Windows 11 Zoom Malfunction #1132</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-re-establishing-obs-audio-recording-capabilities/"><u>[Updated] In 2024, Re-Establishing OBS Audio Recording Capabilities</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/calculating-image-resolution-a-guide-to-aspect-ratios-for-2024/"><u>Calculating Image Resolution A Guide to Aspect Ratios for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-door-with-elongated-pin-strategies-for-windows-1011/"><u>Unlock the Door with Elongated Pin Strategies for Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-access-to-troubleshooters-in-windows-11-with-custom-keys/"><u>Quick Access to Troubleshooters in Windows 11 with Custom Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-two-less-known-yet-crucial-windows-tools/"><u>Unveiling Two Less-Known, Yet Crucial Windows Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-isarcextract-error-a-window-11-solution/"><u>Overcoming ISArcExtract Error: A Window 11 Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/9-steps-to-resolve-windows-hello-fingerprint-lockout/"><u>9 Steps to Resolve Windows Hello Fingerprint Lockout</u></a></li>
<li><a href="https://windows11.techidaily.com/altering-failed-logon-wait-duration-settings-in-windows/"><u>Altering Failed Logon Wait Duration Settings in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-the-crashes-resource-monitor-on-windows-11/"><u>Addressing the Crashes: Resource Monitor on Windows 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-your-music-after-vivo-t2-5g-has-been-deleted-by-fonelab-android-recover-music/"><u>Recover your music after Vivo T2 5G has been deleted</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-android-usage-a-windows-11-webcam-setup/"><u>Optimizing Android Usage: A Windows 11 Webcam Setup</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-prime-methods-to-adapt-track-paceplay-in-spotify-app/"><u>[New] 2024 Approved  Prime Methods to Adapt Track Paceplay in Spotify App</u></a></li>
<li><a href="https://android-unlock.techidaily.com/pattern-locks-are-unsafe-secure-your-oppo-a2-phone-now-with-these-tips-by-drfone-android/"><u>Pattern Locks Are Unsafe Secure Your Oppo A2 Phone Now with These Tips</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-streamline-sound-capture-using-audacity-efficiently-on-a-mac/"><u>2024 Approved  Streamline Sound Capture  Using Audacity Efficiently on a Mac</u></a></li>
<li><a href="https://windows11.techidaily.com/uncharted-territory-innovations-to-windows-11s-explorer-interface/"><u>Uncharted Territory: Innovations to Windows 11'S Explorer Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-xp709-crash-in-windows/"><u>Addressing XP709 Crash in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/trailblazing-through-windows-11-the-mac-hunt-guide/"><u>Trailblazing Through Windows 11: The MAC Hunt Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-overcome-audio-glitch-in-win1011/"><u>Strategies to Overcome Audio Glitch in Win10/11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-6-best-sim-unlock-services-that-actually-work-on-your-poco-x6-pro-device-by-drfone-android/"><u>In 2024, The 6 Best SIM Unlock Services That Actually Work On Your Poco X6 Pro Device</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-second-screen-harmony-windows-plus-android-tablets/"><u>Mastering Second Screen Harmony: Windows + Android Tablets</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-overcome-onedrive-errors-on-w11-systems/"><u>Strategies to Overcome OneDrive Errors on W11 Systems</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-enjoy-your-content-youtube-shorts-are-shown-again-for-2024/"><u>[New] Enjoy Your Content – YouTube Shorts Are Shown Again for 2024</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-2024-approved-crafting-clarity-a-detailed-exploration-of-audio-editing-in-audacity/"><u>New 2024 Approved Crafting Clarity A Detailed Exploration of Audio Editing in Audacity</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-recovering-battlenet-login-on-pcs/"><u>Mastering the Art of Recovering Battle.net Login on PCs</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-video-editing-essentials-how-to-speed-up-clips-in-quicktime-player-windowsmac/"><u>New In 2024, Video Editing Essentials How to Speed Up Clips in QuickTime Player Windows/Mac</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-openers-dive-into-windows-performance-data/"><u>Quick Openers: Dive Into Windows Performance Data</u></a></li>
<li><a href="https://windows11.techidaily.com/invisible-to-others-windows-network-concealment/"><u>Invisible to Others: Windows Network Concealment</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-windows-update-failures-0x800736cc-issue/"><u>Solving Windows Update Failures: 0X800736CC Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/jumpstart-your-system-reviving-windows-11s-error-detection/"><u>Jumpstart Your System: Reviving Windows 11'S Error Detection</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-guide-on-how-to-remove-apple-id-from-apple-iphone-14-by-drfone-ios/"><u>In 2024, Guide on How To Remove Apple ID From Apple iPhone 14</u></a></li>
</ul></div>
