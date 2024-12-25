---
title: "Mastering Error 0X80070570: Restoring Broken Files on Windows 11"
date: 2024-12-18T18:20:41.922Z
updated: 2024-12-25T19:20:52.159Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Error 0X80070570: Restoring Broken Files on Windows 11"
excerpt: "This Article Describes Mastering Error 0X80070570: Restoring Broken Files on Windows 11"
keywords: WinError0X80070570 Fix,WinErrorRestoration,ErrorCode070FileCorrect,FileRepairWin11,Windows11BrokenFiles,XOZeroWindowsFix,0X8070FileRecovery
thumbnail: https://thmb.techidaily.com/8ff604b1994b08eb94688e168989c0566c68ac5579a7ef54ad52cac70e587e21.jpg
---

## Mastering Error 0X80070570: Restoring Broken Files on Windows 11

 Error 0x80070570 is a Windows issue that sometimes pops up when you try to delete files on external hard drives. This error also occurs when users try to transfer files between PCs and external drives. The error 0x80070570 message says, “The file or directory is corrupted and unreadable.”

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.

## 1\. Repair System Files With an SFC Scan

 Some users have confirmed repairing system files resolved error 0x80070570 on their PCs. System File Checker is a command-line tool with which you can check for and repair corrupted system files that might be causing file operation issues. Check out our guide to [utilizing System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) for details about how to run an SFC scan within the Command Prompt.

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/620kcQ7Dw7w?si=a5ussGs5HV7sG3hF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Utilize the Check Disk Tool

 Drive file system issues often cause error 0x80070570\. The most widely confirmed solution for that error is to run a CHKDSK scan of the drive you can’t delete files on or transfer files to. The CHKDSK tool can repair file system errors on the drive it’s scanning.

![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/chkdsk-scan-command.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GPk8_xpN_rA?si=YbAdgsjAKsCn_UsB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Our [guide to running CHKDSK on Windows](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) tells you how to initiate a Check Disk scan. You’ll need to run the Check Disk scan for the drive that includes the files you can’t delete or copy to. If that’s an external drive, you’ll need to connect the storage device to the PC and specify its letter within the command. For example, a CHKDSK command for scanning an external E: drive would be:

`chkdsk /r E:`

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tkpBmccvJ_Q?si=J7ellPL1G1l8Axi_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Try Moving Files to a Different Location

 If error 0x80070570 when you’re trying to transfer a file, try moving (or copying) the file into a different folder location on the target drive. You can do that by right-clicking an affected file and selecting either **Cut** or **Copy**. Then right-click inside a different folder location and select **Paste** to see if the error occurs.

## 4\. Turn Off Real-Time Antivirus Shields

 Another possible factor for error 0x80070570 occurring is your PC’s antivirus shield is hindering the file operation. That could happen if your antivirus software wrongly flags files you’re trying to transfer between drives as suspicious. So, try temporarily disabling your antivirus shield before performing the required file operation.

![The Real-time protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/real-time-protection-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GyfJUhsz_AY?si=x2HjoLX1B89oEPgZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you don’t have third-party security software, turn off Windows Security’s real-time antivirus shield, as covered in our article about [disabling Microsoft Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/). .

 Users with third-party antivirus utilities will need to turn off their antivirus shields via the apps’ system tray context menus. Right-click the antivirus app’s icon in the system tray and select a disable or turn off shield protection setting.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/0OxkndZbIA4?si=TWJlkTbYKsVag8-q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://article-tips.techidaily.com/new-in-2024-a-compreited-list-of-top-8-gaming-monitors-5k/"><u>[New] In 2024, A Compreited List of Top 8 Gaming Monitors, 5K</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-starting-and-participating-in-zoom-meetings-from-android-devices/"><u>[New] Starting and Participating in Zoom Meetings From Android Devices</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-rewind-to-glory-with-top-5-pc-ps1-emulation-tools/"><u>[Updated] 2024 Approved Rewind to Glory with Top 5 PC PS1 Emulation Tools</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-2024-approved-script-crafting-basics/"><u>[Updated] 2024 Approved Script Crafting Basics</u></a></li>
<li><a href="https://win-web3.techidaily.com/iuinoplusaxuuwklue9ruehroeinplusiorewumummrplusiqpdog5zub5pa56z2i55qe6lplusf6ycf5pu05q2j5rovig/"><u>解決外置硬碟設定錯誤: 四方面的迅速更正法</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/aprende-a-agradecernos-con-nombres-animales-hispanos/"><u>Aprende a Agradecernos Con Nombres Animales Hispanos</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-power-settings-on-windows-desktops/"><u>Exploring Power Settings on Windows Desktops</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-the-best-ispoofer-alternative-to-try-on-samsung-galaxy-f15-5g-drfone-by-drfone-virtual-android/"><u>In 2024, The Best iSpoofer Alternative to Try On Samsung Galaxy F15 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/managing-antivirus-softwares-ram-consumption/"><u>Managing Antivirus Software’s RAM Consumption</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-blocked-app-warning-on-windows-os/"><u>Overcoming Blocked App Warning on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-pink-screens-with-ease-and-speed/"><u>Overcoming Windows Pink Screens with Ease and Speed</u></a></li>
<li><a href="https://windows11.techidaily.com/resuscitation-guide-bring-back-function-of-wsreset-on-pcs/"><u>Resuscitation Guide: Bring Back Function of WSReset on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-package-unregistered-photo-problems-in-windows-os/"><u>Solving 'Package Unregistered' Photo Problems in Windows OS</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-removing-memory-dump-files-on-windows-10/"><u>Step-by-Step Guide: Removing Memory Dump Files on Windows 10</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-lava-agni-2-5g-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Lava Agni 2 5G Reset Code | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-for-functional-thx-audio/"><u>Troubleshooting Windows for Functional THX Audio</u></a></li>
</ul></div>

