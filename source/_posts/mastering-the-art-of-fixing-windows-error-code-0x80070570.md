---
title: Mastering the Art of Fixing Windows Error Code 0X80070570
date: 2024-09-13T21:11:43.658Z
updated: 2024-09-20T17:37:35.834Z
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
<a href="https://bluettius.sjv.io/c/5597632/2139118/17108" target="_top" id="2139118">
  <img src="//a.impactradius-go.com/display-ad/17108-2139118" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139118/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Turn Off Real-Time Antivirus Shields

 Another possible factor for error 0x80070570 occurring is your PC’s antivirus shield is hindering the file operation. That could happen if your antivirus software wrongly flags files you’re trying to transfer between drives as suspicious. So, try temporarily disabling your antivirus shield before performing the required file operation.

![The Real-time protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/real-time-protection-option.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137202/26400" target="_top" id="2137202">
  <img src="//a.impactradius-go.com/display-ad/26400-2137202" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137202/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you don’t have third-party security software, turn off Windows Security’s real-time antivirus shield, as covered in our article about [disabling Microsoft Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/). .

 Users with third-party antivirus utilities will need to turn off their antivirus shields via the apps’ system tray context menus. Right-click the antivirus app’s icon in the system tray and select a disable or turn off shield protection setting.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036467/19272" target="_top" id="2036467">
  <img src="//a.impactradius-go.com/display-ad/19272-2036467" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036467/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-links.techidaily.com/new-are-reviews-on-merchandise-streamed-for-cash-in-2024/"><u>[New] Are Reviews on Merchandise Streamed for Cash, In 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-getting-acquainted-with-quantum-hdr-techniques/"><u>[Updated] Getting Acquainted with Quantum HDR Techniques</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-locked-or-disabled-on-iphone-13-pro-7-mehtods-you-cant-miss-by-drfone-ios/"><u>Apple ID Locked or Disabled On iPhone 13 Pro? 7 Mehtods You Cant-Miss</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dell-laptop-display-woes-heres-the-full-manual-to-turn-it-back-on/"><u>Dell Laptop Display Woes? Here's the Full Manual to Turn It Back On</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-forgotten-the-voicemail-password-of-samsung-galaxy-m14-4g-try-these-fixes-by-drfone-android/"><u>In 2024, Forgotten The Voicemail Password Of Samsung Galaxy M14 4G? Try These Fixes</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-reset-itunes-backup-password-of-iphone-8-prevention-and-solution-drfone-by-drfone-ios/"><u>In 2024, Reset iTunes Backup Password Of iPhone 8 Prevention & Solution | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-and-repairing-rdp-fails-in-windows-11/"><u>Preventing and Repairing RDP Fails in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/reducing-memory-waste-with-microsoft-edges-webview2/"><u>Reducing Memory Waste with Microsoft Edge's WebView2</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-disrupted-touchpad-interactions-on-windows-devices/"><u>Resolving Disrupted Touchpad Interactions on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionize-desktop-top-5-clock-saver-software/"><u>Revolutionize Desktop - Top 5 Clock Saver Software</u></a></li>
<li><a href="https://techidaily.com/the-way-to-convert-mts-for-samsung-galaxy-f14-5g-by-aiseesoft-video-converter-play-mts-on-android/"><u>The way to convert MTS for Samsung Galaxy F14 5G</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unlocking-dual-potential-seamlessly-using-android-apps-with-windows-11-setup/"><u>Unlocking Dual Potential: Seamlessly Using Android Apps with Windows 11 Setup</u></a></li>
<li><a href="https://techidaily.com/what-you-need-to-know-to-improve-your-samsung-galaxy-m14-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>What You Need To Know To Improve Your Samsung Galaxy M14 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-at-your-fingertips-crafting-unique-shortcuts/"><u>Windows 11 at Your Fingertips: Crafting Unique Shortcuts</u></a></li>
</ul></div>

