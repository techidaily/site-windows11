---
title: Steps for Windows Backup Configuration Recollection
date: 2024-06-25T12:21:37.554Z
updated: 2024-06-26T12:21:37.554Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps for Windows Backup Configuration Recollection
excerpt: This Article Describes Steps for Windows Backup Configuration Recollection
keywords: Windows Backup Guide,Configuring Backups Windows,System Backup Setup Win,Windows Data Protection,Restore Windows Settings,Recovering Windows Files,Backup & Restore Win
thumbnail: https://thmb.techidaily.com/3be6004f814f322eb7c81e59f5f3e6dc5377a1a28f18fb94887b3ff8d1dce543.jpg
---

## Steps for Windows Backup Configuration Recollection

 System failure or data loss can cause huge amounts of damage and that’s why Windows offers a backup feature to protect your critical data. If your backups corrupt or otherwise function incorrectly, you can reset Windows Backup to its default settings. This guide will teach you some methods to reset Windows Backup to its default on Windows.

## How Do I Know if I Need to Reset Windows Backup?

 You may need to reset Windows Backup if your backups aren't working, taking too long to create, or you can't access the stored files. If you are experiencing these issues, resetting Windows Backup may resolve them.

 For this, either use the Command Prompt or create a batch file. The steps for both methods are outlined below and should help you get your backups running again.

## Is Resetting Window Backup Risky?

 While resetting Windows Backup is generally safe, there are some risks associated with it.

 Firstly, you may lose all existing backups if you reset Windows Backup. To ensure you don't lose data, [create a backup of the existing Windows files](https://www.makeuseof.com/tag/backup-windows-files-folders/) before resetting Windows Backup.

 Furthermore, the reset may affect some third-party apps. It's wise to check with your software vendor before resetting Windows Backup.

 If something goes wrong during the reset, you may have a corrupted backup configuration. In such cases, reinstall the operating system and start from scratch.

 Overall, resetting Windows Backup helps resolve existing issues, but take the necessary precautions to avoid potential risks.

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

## Get Your Backups Working Again on Windows

 Whether you use the command line interface or create a batch file, it's easy to reset Windows Backup. Just remember to restart your computer after the process completes successfully.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/a-stepwise-guide-to-banishing-the-onedrive-icon-from-explorer/"><u>A Stepwise Guide to Banishing the OneDrive Icon From Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-recovery-overcoming-black-screen-issues-in-wins/"><u>Swift Recovery: Overcoming Black-Screen Issues in Wins</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-endure-no-more-teams-login-troubles-in-windows/"><u>How to Endure No More Teams Login Troubles in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-alt-key-code-issues-in-windows-systems/"><u>Solving ALT Key Code Issues in Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-file-error-puzzle-finding-solution-for-0x80070570-on-windows-11/"><u>Decoding the File Error Puzzle - Finding Solution for 0X80070570 on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/a-peek-at-your-gadgets-soul-6-methods-to-discover-its-make/"><u>A Peek at Your Gadget's Soul: 6 Methods to Discover Its Make</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-failed-app-install-in-windows-store/"><u>Troubleshooting Failed App Install in Windows Store</u></a></li>
<li><a href="https://windows11.techidaily.com/fast-startup-mastery-in-windows-11-a-comprehensible-guide/"><u>Fast Startup Mastery in Windows 11 - A Comprehensible Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11s-multi-task-abilities-efficiently/"><u>Navigating Windows 11'S Multi-Task Abilities Efficiently</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-behind-the-scenes-insight-how-vimeo-record-works-for-2024/"><u>[Updated] Behind-the-Scenes Insight  How Vimeo Record Works for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/audio-formats-guide-how-to-choose-best-audio-formats-solved-for-2024/"><u>Audio Formats Guide How to Choose Best Audio Formats Solved for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-subtle-soundscape-selection-for-video-creators/"><u>Updated 2024 Approved Subtle Soundscape Selection for Video Creators</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-apex-design-studio-examination/"><u>In 2024, Apex Design Studio Examination</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-unbrick-a-dead-honor-magic-6-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Unbrick a Dead Honor Magic 6 Pro | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-ultimate-list-6-videos-that-grab-attention/"><u>[Updated] The Ultimate List  6 Videos That Grab Attention</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-the-freestyle-producers-guide-2023s-no-cost-audio-mixing-leaders/"><u>2024 Approved The Freestyle Producers Guide 2023S No-Cost Audio Mixing Leaders</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-a-list-top-desktops-for-enthusiasts/"><u>[New] A-List Top Desktops for Enthusiasts</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-perfectcam-pro-hd-recorders/"><u>[New] 2024 Approved  PerfectCam Pro HD Recorders</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/ringtone-repository-prime-picks-for-downloadable-calls-for-2024/"><u>Ringtone Repository  Prime Picks for Downloadable Calls for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>