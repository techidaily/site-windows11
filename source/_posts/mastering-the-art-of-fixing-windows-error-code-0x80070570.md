---
title: Mastering the Art of Fixing Windows Error Code 0X80070570
date: 2024-09-11T23:27:27.526Z
updated: 2024-09-15T21:22:39.517Z
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

 Our [guide to running CHKDSK on Windows](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) tells you how to initiate a Check Disk scan. You’ll need to run the Check Disk scan for the drive that includes the files you can’t delete or copy to. If that’s an external drive, you’ll need to connect the storage device to the PC and specify its letter within the command. For example, a CHKDSK command for scanning an external E: drive would be:

`chkdsk /r E:`

## 3\. Try Moving Files to a Different Location

 If error 0x80070570 when you’re trying to transfer a file, try moving (or copying) the file into a different folder location on the target drive. You can do that by right-clicking an affected file and selecting either **Cut** or **Copy**. Then right-click inside a different folder location and select **Paste** to see if the error occurs.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2129738/7443" target="_top" id="2129738">
  <img src="//a.impactradius-go.com/display-ad/7443-2129738" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2129738/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Turn Off Real-Time Antivirus Shields

 Another possible factor for error 0x80070570 occurring is your PC’s antivirus shield is hindering the file operation. That could happen if your antivirus software wrongly flags files you’re trying to transfer between drives as suspicious. So, try temporarily disabling your antivirus shield before performing the required file operation.

![The Real-time protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/real-time-protection-option.jpg)

 If you don’t have third-party security software, turn off Windows Security’s real-time antivirus shield, as covered in our article about [disabling Microsoft Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/). .

 Users with third-party antivirus utilities will need to turn off their antivirus shields via the apps’ system tray context menus. Right-click the antivirus app’s icon in the system tray and select a disable or turn off shield protection setting.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115939/19272" target="_top" id="2115939">
  <img src="//a.impactradius-go.com/display-ad/19272-2115939" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115939/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135349/19272" target="_top" id="2135349">
  <img src="//a.impactradius-go.com/display-ad/19272-2135349" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135349/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can format an external drive with the Windows Disk Management utility or in File Explorer. Connect the drive to your PC, and then follow the steps in this guide on [how to format a USB drive](https://www.makeuseof.com/tag/format-usb-drive/) to do this within File Explorer.

## Perform the Required File Operations Again on Windows

 The potential error 0x80070570 solutions covered here have worked for many Windows 11/10 users. Repairing drive errors with the CHKDSK tool usually does the trick. You could also utilize a third-party utility like Hard Disk Sentinel and HDDScan to check for and repair drive issues. With error 0x80070570 fixed, you can copy or delete files as required again.

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-quick-fix-getting-snapchat-installed-on-mac/"><u>[New] In 2024, Quick Fix Getting Snapchat Installed on Mac</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-leveraging-windows-media-player-your-cd-conversion-companion/"><u>2024 Approved Leveraging Windows Media Player Your CD Conversion Companion</u></a></li>
<li><a href="https://vp-tips.techidaily.com/dvd-11/"><u>家庭で安全にDVDを保存するための無料ソフトウェアガイド - 一般的な問題とその修正法 | 11ページ目</u></a></li>
<li><a href="https://win-solutions.techidaily.com/cracking-the-freezing-problem-effective-solutions-to-overwatch-lag-issues/"><u>Cracking the Freezing Problem: Effective Solutions to Overwatch Lag Issues</u></a></li>
<li><a href="https://tech-haven.techidaily.com/effortless-cover-letters-leveraging-chatgpt-for-standout-applications/"><u>Effortless Cover Letters: Leveraging ChatGPT for Standout Applications</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-disable-auto-open-of-search-menu-on-windows-11/"><u>How To Disable Auto-Open of Search Menu on Windows 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-lock-your-samsung-galaxy-f15-5g-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>In 2024, Lock Your Samsung Galaxy F15 5G Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-top-4-sim-location-trackers-to-easily-find-your-lost-oppo-find-x6-device-by-drfone-android/"><u>In 2024, Top 4 SIM Location Trackers To Easily Find Your Lost Oppo Find X6 Device</u></a></li>
<li><a href="https://windows11.techidaily.com/leap-into-productivity-windows-11s-multiple-folder-creation-tricks/"><u>Leap Into Productivity: Windows 11'S Multiple Folder Creation Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/pinpointing-your-pcs-drive-type-with-windows/"><u>Pinpointing Your PC's Drive Type with Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-unresponsive-windows-11-activation-codes/"><u>Resolving Unresponsive Windows 11 Activation Codes</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-latency-ledger-chatgpt-4-versus-its-gpt-35-counterpart/"><u>The Latency Ledger: ChatGPT-4 Versus Its GPT-3.5 Counterpart</u></a></li>
<li><a href="https://windows11.techidaily.com/transformative-ui-update-command-line-in-windows-11s-taskbar/"><u>Transformative UI Update: Command Line in Windows 11'S TaskBar</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-permissions-violation-during-setup/"><u>Troubleshooting Windows Permissions Violation During Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-resurrecting-old-folder-tools/"><u>Windows 11: Resurrecting Old Folder Tools</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    