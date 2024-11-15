---
title: Mastering the Art of Fixing Windows Error Code 0X80070570
date: 2024-11-10T17:19:47.821Z
updated: 2024-11-15T16:52:29.632Z
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

## 1\. Repair System Files With an SFC Scan

 Some users have confirmed repairing system files resolved error 0x80070570 on their PCs. System File Checker is a command-line tool with which you can check for and repair corrupted system files that might be causing file operation issues. Check out our guide to [utilizing System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) for details about how to run an SFC scan within the Command Prompt.

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command2.jpg)

## 2\. Utilize the Check Disk Tool

 Drive file system issues often cause error 0x80070570\. The most widely confirmed solution for that error is to run a CHKDSK scan of the drive you can’t delete files on or transfer files to. The CHKDSK tool can repair file system errors on the drive it’s scanning.

![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/chkdsk-scan-command.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148633/16836" target="_top" id="2148633">
  <img src="//a.impactradius-go.com/display-ad/16836-2148633" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148633/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Our [guide to running CHKDSK on Windows](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) tells you how to initiate a Check Disk scan. You’ll need to run the Check Disk scan for the drive that includes the files you can’t delete or copy to. If that’s an external drive, you’ll need to connect the storage device to the PC and specify its letter within the command. For example, a CHKDSK command for scanning an external E: drive would be:

`chkdsk /r E:`

## 3\. Try Moving Files to a Different Location

 If error 0x80070570 when you’re trying to transfer a file, try moving (or copying) the file into a different folder location on the target drive. You can do that by right-clicking an affected file and selecting either **Cut** or **Copy**. Then right-click inside a different folder location and select **Paste** to see if the error occurs.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006960/19272" target="_top" id="2006960">
  <img src="//a.impactradius-go.com/display-ad/19272-2006960" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006960/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Turn Off Real-Time Antivirus Shields

 Another possible factor for error 0x80070570 occurring is your PC’s antivirus shield is hindering the file operation. That could happen if your antivirus software wrongly flags files you’re trying to transfer between drives as suspicious. So, try temporarily disabling your antivirus shield before performing the required file operation.

![The Real-time protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/real-time-protection-option.jpg)

 If you don’t have third-party security software, turn off Windows Security’s real-time antivirus shield, as covered in our article about [disabling Microsoft Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/). .

 Users with third-party antivirus utilities will need to turn off their antivirus shields via the apps’ system tray context menus. Right-click the antivirus app’s icon in the system tray and select a disable or turn off shield protection setting.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

## 5\. Perform a Startup Repair

 This resolution is recommended if error 0x80070570 occurs when trying to delete files on the C: hard drive or transfer them there. Startup Repair is primarily a utility for fixing Windows startup issues. However, that tool can remedy corrupted system files and C: drive issues. This is how you can utilize Startup Repair:

1. First, [bring up the Advanced Startup Options menu](https://www.makeuseof.com/windows-11-access-advanced-startup-options/) via the Settings app.
2. Select **Startup Repair** within the Advanced options menu.  
![The Start-up Repair option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-up-repair.jpg)
3. Next, select your Windows user account.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915805/19272" target="_top" id="1915805">
  <img src="//a.impactradius-go.com/display-ad/19272-1915805" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915805/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Input your user account password.
5. Select **Continue** to initiate the repair.

## 6\. Format an External Drive

 Formatting an affected external drive to which you can’t transfer files or delete data because of error 0x80070570 is suggested only as a last resort. Applying this potential fix will wipe all data on the drive, so do not format your PC’s C: drive. However, some users have confirmed formatting affected external drives fixes error 0x80070570\.

![The format drive utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-format-tool.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134492/18498" target="_top" id="2134492">
  <img src="//a.impactradius-go.com/display-ad/18498-2134492" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134492/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://fox-http.techidaily.com/new-breakthrough-the-top-8-web-based-photo-blender/"><u>[New] Breakthrough The Top 8 Web-Based Photo Blender</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-dissecting-the-best-app-for-video-editing-is-inshot-it-for-2024/"><u>[New] Dissecting the Best App for Video Editing - Is InShot It for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/n-2024-gamers-quest-1000plus-game-adventures-unfolded/"><u>[New] In 2024, Gamer's Quest 1,000+ Game Adventures Unfolded</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-photography-revolution-toolwizs-2023-app-insights/"><u>[Updated] Photography Revolution Toolwiz's 2023 App Insights</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-swift-recovery-reviving-windows-photo-viewer-on-modern-os/"><u>2024 Approved Swift Recovery Reviving Windows Photo Viewer on Modern OS</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/discovering-the-benefits-of-the-garmin-vivomove-hr-watch-where-elegance-meets-exercise/"><u>Discovering the Benefits of the Garmin Vivomove HR Watch - Where Elegance Meets Exercise</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-swipe-tap-save-the-ultimate-guide-for-igtv-videos-on-devices/"><u>In 2024, Swipe, Tap, Save The Ultimate Guide for IGTV Videos on Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/mute-irrelevant-suggestions-on-windows-11/"><u>Mute Irrelevant Suggestions on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-enhancing-result-visibility-on-windows-1011/"><u>Techniques for Enhancing Result Visibility on Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-blueprint-for-direct-access-in-windows-11/"><u>The Essential Blueprint for Direct Access in Windows 11</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-guide-fixing-the-crash-error-in-mount-and-blade-bannerlord-game/"><u>Troubleshooting Guide - Fixing the Crash Error in Mount & Blade ˈBannerlord Game</u></a></li>
<li><a href="https://windows11.techidaily.com/why-stick-with-traditional-skip-the-boredom-for-new-outlook/"><u>Why Stick with Traditional? Skip the Boredom for New Outlook</u></a></li>
</ul></div>

