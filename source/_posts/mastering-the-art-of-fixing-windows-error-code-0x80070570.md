---
title: Mastering the Art of Fixing Windows Error Code 0X80070570
date: 2024-12-24T18:56:00.734Z
updated: 2024-12-25T20:01:50.689Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering the Art of Fixing Windows Error Code 0X80070570
excerpt: This Article Describes Mastering the Art of Fixing Windows Error Code 0X80070570
keywords: WinErrorCode0X80070570Solved,FixWindowsError070570,ResolveWinErrors,Error0X80070570Fixation,WindowsErrorCodesRepair,0X80070570WindowsError,WindowsErrorCodeZeroX80070570
thumbnail: https://thmb.techidaily.com/482b831c6b34c789ab00f688124bfef762b7175eaa7e3a93f998add3b31aa3c1.jpg
---

## Mastering the Art of Fixing Windows Error Code 0X80070570

 Error 0x80070570 is a Windows issue that sometimes pops up when you try to delete files on external hard drives. This error also occurs when users try to transfer files between PCs and external drives. The error 0x80070570 message says, “The file or directory is corrupted and unreadable.”

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MPoakxUNf9o?si=S-ppSqzHzN9VrxC7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Repair System Files With an SFC Scan

 Some users have confirmed repairing system files resolved error 0x80070570 on their PCs. System File Checker is a command-line tool with which you can check for and repair corrupted system files that might be causing file operation issues. Check out our guide to [utilizing System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) for details about how to run an SFC scan within the Command Prompt.

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eMEJvwMM0vk?si=EQF_jo_4u9v5iJ_C" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Utilize the Check Disk Tool

 Drive file system issues often cause error 0x80070570\. The most widely confirmed solution for that error is to run a CHKDSK scan of the drive you can’t delete files on or transfer files to. The CHKDSK tool can repair file system errors on the drive it’s scanning.

![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/chkdsk-scan-command.jpg)

 Our [guide to running CHKDSK on Windows](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) tells you how to initiate a Check Disk scan. You’ll need to run the Check Disk scan for the drive that includes the files you can’t delete or copy to. If that’s an external drive, you’ll need to connect the storage device to the PC and specify its letter within the command. For example, a CHKDSK command for scanning an external E: drive would be:

`chkdsk /r E:`

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5FWCFI3f_cs?si=Kt2Onr_E4c616tbH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Try Moving Files to a Different Location

 If error 0x80070570 when you’re trying to transfer a file, try moving (or copying) the file into a different folder location on the target drive. You can do that by right-clicking an affected file and selecting either **Cut** or **Copy**. Then right-click inside a different folder location and select **Paste** to see if the error occurs.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uzb-0C0xUYA?si=F4MPhdVqyVgx7_8X" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Turn Off Real-Time Antivirus Shields

 Another possible factor for error 0x80070570 occurring is your PC’s antivirus shield is hindering the file operation. That could happen if your antivirus software wrongly flags files you’re trying to transfer between drives as suspicious. So, try temporarily disabling your antivirus shield before performing the required file operation.

![The Real-time protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/real-time-protection-option.jpg)

 If you don’t have third-party security software, turn off Windows Security’s real-time antivirus shield, as covered in our article about [disabling Microsoft Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/). .

 Users with third-party antivirus utilities will need to turn off their antivirus shields via the apps’ system tray context menus. Right-click the antivirus app’s icon in the system tray and select a disable or turn off shield protection setting.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Iz2LYWd8EqI?si=G_3CqFRAmeVPczjj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Perform a Startup Repair

 This resolution is recommended if error 0x80070570 occurs when trying to delete files on the C: hard drive or transfer them there. Startup Repair is primarily a utility for fixing Windows startup issues. However, that tool can remedy corrupted system files and C: drive issues. This is how you can utilize Startup Repair:

1. First, [bring up the Advanced Startup Options menu](https://www.makeuseof.com/windows-11-access-advanced-startup-options/) via the Settings app.
2. Select **Startup Repair** within the Advanced options menu.  
![The Start-up Repair option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-up-repair.jpg)
3. Next, select your Windows user account.

4. Input your user account password.
5. Select **Continue** to initiate the repair.

## 6\. Format an External Drive

 Formatting an affected external drive to which you can’t transfer files or delete data because of error 0x80070570 is suggested only as a last resort. Applying this potential fix will wipe all data on the drive, so do not format your PC’s C: drive. However, some users have confirmed formatting affected external drives fixes error 0x80070570\.

![The format drive utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-format-tool.jpg)

 You can format an external drive with the Windows Disk Management utility or in File Explorer. Connect the drive to your PC, and then follow the steps in this guide on [how to format a USB drive](https://www.makeuseof.com/tag/format-usb-drive/) to do this within File Explorer.

## Perform the Required File Operations Again on Windows

 The potential error 0x80070570 solutions covered here have worked for many Windows 11/10 users. Repairing drive errors with the CHKDSK tool usually does the trick. You could also utilize a third-party utility like Hard Disk Sentinel and HDDScan to check for and repair drive issues. With error 0x80070570 fixed, you can copy or delete files as required again.

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-tips.techidaily.com/updated-big-waters-better-views-top-5-fishing-cams/"><u>[Updated] Big Waters, Better Views - Top 5 Fishing Cams</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-mastering-online-meetings-zoom-tips-for-chromebooks/"><u>[Updated] Mastering Online Meetings Zoom Tips for Chromebooks</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-unlocking-the-power-of-seamless-youtube-content-flow-onto-facebook/"><u>[Updated] Unlocking the Power of Seamless YouTube Content Flow Onto Facebook</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-streamlining-your-gaming-experience-with-easy-recordings/"><u>2024 Approved Streamlining Your Gaming Experience with Easy Recordings</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-visual-polishing-in-meetings-blurring-backgrounds-on-teammeeting/"><u>2024 Approved Visual Polishing in Meetings Blurring Backgrounds on TeamMeeting</u></a></li>
<li><a href="https://games-able.techidaily.com/essential-tips-for-efficient-use-of-ea-play-on-ps5/"><u>Essential Tips for Efficient Use of EA Play on PS5</u></a></li>
<li><a href="https://data-wizards.techidaily.com/fix-corrupted-and-damaged-mpeg-videos-with-advanced-mpeg-repair-solutions/"><u>Fix Corrupted & Damaged MPEG Videos with Advanced MPeg Repair Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-error-fixes-successfully-loading-a-plugin-in-google-chrome-for-windows-10/"><u>Mastering Error Fixes: Successfully Loading a Plugin in Google Chrome for Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-solutions-to-csgo-opens-issue-w11/"><u>Quick Solutions to CS:GO Opens Issue W11</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-tips-how-to-overcome-restricted-file-viewers-in-windows/"><u>Quick Tips: How to Overcome Restricted File Viewers in Windows</u></a></li>
<li><a href="https://win-solutions.techidaily.com/resolving-performance-hiccups-in-bloodhunt-a-guide-to-pc-optimization/"><u>Resolving Performance Hiccups in Bloodhunt: A Guide to PC Optimization</u></a></li>
<li><a href="https://windows11.techidaily.com/revisiting-the-classics-uncovering-7-older-windows-functionalities-in-11/"><u>Revisiting the Classics: Uncovering 7 Older Windows Functionalities in 11</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlined-windows-11-upsize-an-in-place-methodology-overview/"><u>Streamlined Windows 11 Upsize: An In-Place Methodology Overview</u></a></li>
<li><a href="https://windows11.techidaily.com/top-techniques-for-maximizing-windows-11-features/"><u>Top Techniques for Maximizing Windows 11 Features</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-chrome-blackout-on-pcs/"><u>Troubleshooting Chrome Blackout on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-non-operational-event-viewer/"><u>Troubleshooting Non-Operational Event Viewer</u></a></li>
</ul></div>

