---
title: Bringing Windows Backups Back to Basics
date: 2024-07-03T11:20:00.919Z
updated: 2024-07-04T11:20:00.919Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Bringing Windows Backups Back to Basics
excerpt: This Article Describes Bringing Windows Backups Back to Basics
keywords: Basic WinBackup Tips,Essential Windows Backup Guide,Fundamentals of WinBackup,Simplifying WinBackup Process,WinBackup Recovery Basics,Easy WinBackup Techniques,Restoring with Simple WinBackup
thumbnail: https://thmb.techidaily.com/c773b247e1e0895c35ac3965c0957524900af663f812d6e184693495dab0728b.jpg
---

## Bringing Windows Backups Back to Basics

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
<li><a href="https://windows11.techidaily.com/mastering-terminal-personalize-colors-and-style/"><u>Mastering Terminal: Personalize Colors & Style</u></a></li>
<li><a href="https://windows11.techidaily.com/revamp-desktop-by-removing-windows-11s-highlighted-icon/"><u>Revamp Desktop by Removing Windows 11'S Highlighted Icon</u></a></li>
<li><a href="https://windows11.techidaily.com/1719366391353-keyboards-on-the-ropes-reclaim-your-arrows/"><u>Keyboards on the Ropes? Reclaim Your Arrows!</u></a></li>
<li><a href="https://windows11.techidaily.com/win-error-restoring-lost-or-absent-mfc71udll/"><u>Win Error: Restoring Lost or Absent Mfc71u.dll</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-windows-11s-0x8007045d-bluescreen-troubleshooting/"><u>Navigating Through Windows 11'S 0X8007045D Bluescreen Troubleshooting</u></a></li>
<li><a href="https://windows11.techidaily.com/audio-visual-verification-a-windows-users-pre-meet-checklist/"><u>Audio Visual Verification: A Windows User’s Pre-Meet Checklist</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-win11-pointer-adjustments-for-access/"><u>Mastering Win11 Pointer Adjustments for Access</u></a></li>
<li><a href="https://windows11.techidaily.com/a-guide-to-understanding-windows-program-files-format/"><u>A Guide to Understanding Windows' Program Files Format</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-the-ultimate-guide-to-ipados-drawing-wonders/"><u>[Updated] 2024 Approved  The Ultimate Guide to iPadOS Drawing Wonders</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-creative-freedom-on-a-budget-essential-green-screen-effects-from-top-4-tutorial-sources/"><u>[New] Creative Freedom on a Budget  Essential Green Screen Effects From Top 4 Tutorial Sources</u></a></li>
<li><a href="https://android-frp.techidaily.com/easy-guide-how-to-bypass-motorola-razr-40-frp-android-10111213-by-drfone-android/"><u>Easy Guide How To Bypass Motorola Razr 40 FRP Android 10/11/12/13</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-future-of-audio-extraction-with-pazera-tools-analysis/"><u>[Updated] The Future of Audio Extraction with Pazera Tools Analysis</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-cross-platform-sync-made-simple-post-tiktok-vids-on-fb/"><u>In 2024, Cross-Platform Sync Made Simple  Post TikTok Vids on FB</u></a></li>
<li><a href="https://extra-resources.techidaily.com/perfecting-the-introduction-writing-impressive-summaries/"><u>Perfecting the Introduction  Writing Impressive Summaries</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-enhance-digital-communication-on-chrome-review-of-the-best-web-based-tts-tools/"><u>[Updated] 2024 Approved  Enhance Digital Communication on Chrome  Review of the Best Web-Based TTS Tools</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-a-comprehensive-look-at-decelerating-youtube-video-speed-50-chars/"><u>[New] 2024 Approved  A Comprehensive Look at Decelerating YouTube Video Speed (50 Chars)</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ipogo-will-be-the-new-ispoofer-on-tecno-phantom-v-flip-drfone-by-drfone-virtual-android/"><u>iPogo will be the new iSpoofer On Tecno Phantom V Flip? | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>