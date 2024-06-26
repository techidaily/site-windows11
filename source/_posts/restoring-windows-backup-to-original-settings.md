---
title: Restoring Windows Backup to Original Settings
date: 2024-06-25T12:01:18.455Z
updated: 2024-06-26T12:01:18.455Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Windows Backup to Original Settings
excerpt: This Article Describes Restoring Windows Backup to Original Settings
keywords: Windows Restore Options,System Recovery Tool,Data Backup Reinstall,Default Settings Restore,PC Factory Reset,OS Configuration Overhaul,Backup to Original Setup
thumbnail: https://thmb.techidaily.com/d8f2922d20e310fe909f77a8d8b81c6fbacf60f301e5bf6586c75f1b0b08c5ac.jpeg
---

## Restoring Windows Backup to Original Settings

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
<li><a href="https://windows11.techidaily.com/quick-fix-guide-to-restore-windows-11-troubleshooters/"><u>Quick FIX Guide to Restore Windows 11 Troubleshooters</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-audio-error-devices-being-used-by-non-targeted-apps/"><u>Clearing Up Audio Error: Devices Being Used by Non-Targeted Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-to-activate-rgb-settings-in-windows-11/"><u>Step-by-Step to Activate RGB Settings in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-nitpicking-colors-8-tips-for-a-neutral-desktop/"><u>Navigating Nitpicking Colors: 8 Tips for a Neutral Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-isarcextract-error-a-window-11-solution/"><u>Overcoming ISArcExtract Error: A Window 11 Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/the-future-of-personal-computing-transforming-window-11-widgets/"><u>The Future of Personal Computing: Transforming Window 11 Widgets</u></a></li>
<li><a href="https://windows11.techidaily.com/revamp-outlooks-speed-for-better-windows-experience/"><u>Revamp Outlook's Speed for Better Windows Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/simplify-software-management-with-new-context-menu-addition/"><u>Simplify Software Management with New Context Menu Addition</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-from-screens-to-spreads-the-dos-and-donts-of-live-blogging/"><u>[New] 2024 Approved  From Screens to Spreads  The Do's and Don'ts of Live Blogging</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-navigate-through-screens-the-best-recorders-for-w11w10/"><u>2024 Approved  Navigate Through Screens  The Best Recorders for W11/W10</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-mastering-podcast-rss-feed-development/"><u>2024 Approved  Mastering Podcast RSS Feed Development</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fixing-foneazy-mockgo-not-working-on-poco-c50-drfone-by-drfone-virtual-android/"><u>In 2024, Fixing Foneazy MockGo Not Working On Poco C50 | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-reviewing-the-pinnacle-of-tv-tech-lg-27ud88-uhd-oled-hdtv/"><u>2024 Approved  Reviewing the Pinnacle of TV Tech - LG 27UD88-UHD OLED HDTV</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-seamless-screens-and-cameras-recording-methods/"><u>[New] Seamless Screens & Cameras Recording Methods</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-mastering-the-art-of-filters-on-instagram-your-2023-manual/"><u>[New] In 2024, Mastering the Art of Filters on Instagram  Your 2023 Manual</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-ultimate-guide-to-jaunt-vr-immersion/"><u>The Ultimate Guide to Jaunt VR Immersion</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-2024-approved-the-ultimate-tutorial-streamlining-audio-recording-on-windows-10-pcs/"><u>New 2024 Approved The Ultimate Tutorial Streamlining Audio Recording on Windows 10 PCs</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>