---
title: Pathway to Correcting Windows Backup Settings
date: 2024-10-05T09:24:37.036Z
updated: 2024-10-06T18:50:45.782Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Pathway to Correcting Windows Backup Settings
excerpt: This Article Describes Pathway to Correcting Windows Backup Settings
keywords: Fix Windows Backup Issues,Update Backup Settings,Adjust Windows Backup,Change Backup Schedule,Reset Backup Preferences,Modify Backup Options,Correct Backup Configuration
thumbnail: https://thmb.techidaily.com/d2e4e8d37dd44251b856b042284c1dfc0b019c21a2404b925ef4f20286104a39.jpg
---

## Pathway to Correcting Windows Backup Settings

 System failure or data loss can cause huge amounts of damage and that’s why Windows offers a backup feature to protect your critical data. If your backups corrupt or otherwise function incorrectly, you can reset Windows Backup to its default settings. This guide will teach you some methods to reset Windows Backup to its default on Windows.

## How Do I Know if I Need to Reset Windows Backup?

 You may need to reset Windows Backup if your backups aren't working, taking too long to create, or you can't access the stored files. If you are experiencing these issues, resetting Windows Backup may resolve them.

 For this, either use the Command Prompt or create a batch file. The steps for both methods are outlined below and should help you get your backups running again.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105867/7443" target="_top" id="2105867">
  <img src="//a.impactradius-go.com/display-ad/7443-2105867" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105867/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Is Resetting Window Backup Risky?

 While resetting Windows Backup is generally safe, there are some risks associated with it.

 Firstly, you may lose all existing backups if you reset Windows Backup. To ensure you don't lose data, [create a backup of the existing Windows files](https://www.makeuseof.com/tag/backup-windows-files-folders/) before resetting Windows Backup.

 Furthermore, the reset may affect some third-party apps. It's wise to check with your software vendor before resetting Windows Backup.

 If something goes wrong during the reset, you may have a corrupted backup configuration. In such cases, reinstall the operating system and start from scratch.

 Overall, resetting Windows Backup helps resolve existing issues, but take the necessary precautions to avoid potential risks.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1959707/19272" target="_top" id="1959707">
  <img src="//a.impactradius-go.com/display-ad/19272-1959707" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959707/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Reset Windows Backup to Its Factory Settings

 Now you know how to proceed with caution, here's how to reset Windows Backup to its factory settings.

### 1\. Using Command Prompt

 If your current backup configuration isn't working, reset Windows Backup to its default settings. To get started, [run the Command Prompt with admin access](https://www.makeuseof.com/windows-run-command-prompt-admin/). In the Command Prompt window, run the following command:

`reg delete HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup /f`

 This will reset to the default configuration and remove all existing backups.

 After that, copy and paste the following command into the Command Prompt window and press **Enter**:

`reg add HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup`

 This will recreate the WindowsBackup entry in the registry editor. Next, type in and run the below command to delete the Automatic Backup scheduled task on Windows:

`schtasks /delete /tn "Microsoft\Windows\WindowsBackup\AutomaticBackup" /f`

 Finally, execute the below command to delete the backup monitor scheduled task:

`schtasks /delete /tn "Microsoft\Windows\WindowsBackup\Windows Backup Monitor" /f`

 After executing the above commands, restart your computer. This will reset Windows Backup to its default settings.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043603/7443" target="_top" id="2043603">
  <img src="//a.impactradius-go.com/display-ad/7443-2043603" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043603/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2\. Creating a Batch File

 If you're not comfortable with the command line interface, reset Windows Backup by creating a batch file.

 To do this, [open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) and paste the below code.

`<code>reg delete HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup /f  
reg add HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup  
schtasks /delete /tn "Microsoft\Windows\WindowsBackup\AutomaticBackup" /f  
schtasks /delete /tn "Microsoft\Windows\WindowsBackup\Windows Backup Monitor" /f`

 Click the **File** menu and select **Save as**. On the Save as dialog, type **reset-backup.bat** as the file name. Then choose **All Files** from the drop-down menu next to the Save as type. From the left panel, select **Desktop** and click the **Save** button.

 Now, close the Notepad window and right-click on the batch file. From the context menu, select **Run as administrator**. This will reset Windows Backup to its default settings.

 Lastly, restart your computer and you're done. These are two methods to reset Windows Backup to its default settings.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902309/19272" target="_top" id="1902309">
  <img src="//a.impactradius-go.com/display-ad/19272-1902309" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902309/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get Your Backups Working Again on Windows

 Whether you use the command line interface or create a batch file, it's easy to reset Windows Backup. Just remember to restart your computer after the process completes successfully.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-real-time-broadcast-logging-made-simple/"><u>[New] 2024 Approved Real-Time Broadcast Logging Made Simple</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-top-15-youtube-openings-elevate-your-contents-impact/"><u>[New] Top 15 YouTube Openings Elevate Your Content's Impact</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-mastering-the-art-of-downloading-instagram-media-for-2024/"><u>[Updated] Mastering the Art of Downloading Instagram Media for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-pros-tips-capturing-slow-motion-on-gopro-hero-10/"><u>2024 Approved Pro's Tips Capturing Slow Motion on GoPro Hero 10</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/expert-insights-on-technology-from-toms-computer-solutions/"><u>Expert Insights on Technology From Tom's Computer Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-steps-for-swiftly-dealing-with-unspecified-obs-recording-problem/"><u>Expert Steps for Swiftly Dealing with Unspecified OBS Recording Problem</u></a></li>
<li><a href="https://windows11.techidaily.com/exposing-the-trojan-terror-defending-your-windows-against-wacatacbml/"><u>Exposing the Trojan Terror: Defending Your Windows Against Wacatac.B!ml</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-your-pcs-missing-piece-how-to-restore-bluetooth-on-windows-11/"><u>Fix Your PC's Missing Piece: How to Restore Bluetooth on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/from-version-6-to-7-smoothly-upgrading-virtualbox-on-your-win11-device/"><u>From Version 6 to 7: Smoothly Upgrading VirtualBox on Your Win11 Device</u></a></li>
<li><a href="https://windows11.techidaily.com/get-ahead-top-strategies-to-master-the-windows-11-taskbar/"><u>Get Ahead: Top Strategies to Master the Windows 11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-snapping-windows-uac-alerts/"><u>How-To: Snapping Windows UAC Alerts</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-stream-anything-from-itel-p55plus-to-apple-tv-drfone-by-drfone-android/"><u>In 2024, How To Stream Anything From Itel P55+ to Apple TV | Dr.fone</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/in-2024-top-10-best-introduction-editors-apps/"><u>In 2024, Top 10 Best Introduction Editors (Apps)</u></a></li>
<li><a href="https://windows11.techidaily.com/rush-your-print-jobs-how-to-spur-a-slow-windows-printer/"><u>Rush Your Print Jobs: How to Spur a Slow Windows Printer</u></a></li>
<li><a href="https://hardware-help.techidaily.com/toms-tech-insights-in-depth-reviews-and-gadget-analysis/"><u>Tom's Tech Insights: In-Depth Reviews & Gadget Analysis</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-unresponsive-programs-in-windows-os/"><u>Troubleshooting Unresponsive Programs in Windows OS</u></a></li>
<li><a href="https://techtrends.techidaily.com/unveiling-the-contrast-neo-qled-and-oled-display-differences-explored/"><u>Unveiling The Contrast: Neo QLED and OLED Display Differences Explored</u></a></li>
</ul></div>

