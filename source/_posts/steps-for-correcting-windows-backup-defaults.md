---
title: Steps for Correcting Windows Backup Defaults
date: 2024-11-18T02:04:19.256Z
updated: 2024-11-25T01:03:49.815Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps for Correcting Windows Backup Defaults
excerpt: This Article Describes Steps for Correcting Windows Backup Defaults
keywords: Fix Windows Backup Issues,Change Default Windows Backup,Reset Windows Backup Settings,Customize Windows Backup,Alter Backup Schedule,Modify Backup Destination,Adjust Backup Preferences
thumbnail: https://thmb.techidaily.com/f86f99b6d8051e2301c0b59b59f0f49d547931786fc3f8df51522ef8e8e5d47b.jpg
---

## Steps for Correcting Windows Backup Defaults

 System failure or data loss can cause huge amounts of damage and that’s why Windows offers a backup feature to protect your critical data. If your backups corrupt or otherwise function incorrectly, you can reset Windows Backup to its default settings. This guide will teach you some methods to reset Windows Backup to its default on Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YpnYKIrpgZQ?si=94zicAHp1CH-0oso&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Do I Know if I Need to Reset Windows Backup?

 You may need to reset Windows Backup if your backups aren't working, taking too long to create, or you can't access the stored files. If you are experiencing these issues, resetting Windows Backup may resolve them.

 For this, either use the Command Prompt or create a batch file. The steps for both methods are outlined below and should help you get your backups running again.

## Is Resetting Window Backup Risky?

 While resetting Windows Backup is generally safe, there are some risks associated with it.

 Firstly, you may lose all existing backups if you reset Windows Backup. To ensure you don't lose data, [create a backup of the existing Windows files](https://www.makeuseof.com/tag/backup-windows-files-folders/) before resetting Windows Backup.

 Furthermore, the reset may affect some third-party apps. It's wise to check with your software vendor before resetting Windows Backup.

 If something goes wrong during the reset, you may have a corrupted backup configuration. In such cases, reinstall the operating system and start from scratch.

 Overall, resetting Windows Backup helps resolve existing issues, but take the necessary precautions to avoid potential risks.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kx-Pb0otJCs?si=Mvr49yQVesmJA8-O&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Reset Windows Backup to Its Factory Settings

 Now you know how to proceed with caution, here's how to reset Windows Backup to its factory settings.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/465CTOm8om0?si=63RxowNMCFA4fPUa&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=lhdUUVYMVQjzHXBh&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/uSfA74aeYeA?si=HdJSMdeS7HVtS6-j&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://article-helps.techidaily.com/2024-approved-high-performance-hardware-for-live-video-feeds/"><u>2024 Approved High-Performance Hardware for Live Video Feeds</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-superior-cameras-for-clear-smooth-podcast-sessions/"><u>2024 Approved Superior Cameras for Clear, Smooth Podcast Sessions</u></a></li>
<li><a href="https://activate-lock.techidaily.com/bypass-icloud-activation-lock-with-imei-code-on-apple-iphone-se-2022-by-drfone-ios/"><u>Bypass iCloud Activation Lock with IMEI Code On Apple iPhone SE (2022)</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-android-unlock-code-sim-unlock-your-zte-nubia-flip-5g-phone-and-remove-locked-screen-by-drfone-android/"><u>In 2024, Android Unlock Code Sim Unlock Your ZTE Nubia Flip 5G Phone and Remove Locked Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-language-diversity-windows-font-download/"><u>Navigating Language Diversity: Windows Font Download</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-the-maze-of-print-error-xfffee/"><u>Navigating Through the Maze of Print Error XFFFEE</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-marketplace-malfunction-error-0x80073cf3/"><u>Overcoming the Marketplace Malfunction: Error 0X80073CF3</u></a></li>
<li><a href="https://win-answers.techidaily.com/phasmophobia-update-woes-solutions-for-the-notorious-stuck-at-warty-90-screen-problem/"><u>Phasmophobia Update Woes? Solutions for the Notorious Stuck at Warty 90% Screen Problem!</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-update-error-code-x8024a205/"><u>Resolving Windows Update: Error Code X8024A205</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-full-operations-win1011-and-ccleaner-interaction/"><u>Restoring Full Operations: Win10/11 & CCleaner Interaction</u></a></li>
<li><a href="https://windows11.techidaily.com/the-strategy-for-concealing-the-search-bar-on-taskbar/"><u>The Strategy for Concealing the Search Bar on Taskbar</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ultimate-guide-to-get-the-meltan-box-pokemon-go-for-nokia-g22-drfone-by-drfone-virtual-android/"><u>Ultimate guide to get the meltan box pokemon go For Nokia G22 | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/wav-webm-online/"><u>WAV 및 WebM 형식으로 비용 해제 영상 바이트 변환 - Online</u></a></li>
</ul></div>

