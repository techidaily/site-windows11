---
title: Decoding the File Error Puzzle - Finding Solution for 0X80070570 on Windows 11
date: 2024-08-15T15:28:46.000Z
updated: 2024-08-16T15:28:46.000Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Decoding the File Error Puzzle - Finding Solution for 0X80070570 on Windows 11
excerpt: This Article Describes Decoding the File Error Puzzle - Finding Solution for 0X80070570 on Windows 11
keywords: FileErrorSolutionWin11,X80070570Fix,Windows11ZeroX80070570,0XErrorWindowsSolver,Win11FilePuzzleResolver,X8070570FixWin11,WindowsErrorCodeX8070570
thumbnail: https://thmb.techidaily.com/ca553c30ee84db192e99fa5840738c6a29a319bf3596b8900296a25dc73f79cf.png
---

## Decoding the File Error Puzzle - Finding Solution for 0X80070570 on Windows 11

 Error 0x80070570 is a Windows issue that sometimes pops up when you try to delete files on external hard drives. This error also occurs when users try to transfer files between PCs and external drives. The error 0x80070570 message says, “The file or directory is corrupted and unreadable.”

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.

## 1\. Repair System Files With an SFC Scan

 Some users have confirmed repairing system files resolved error 0x80070570 on their PCs. System File Checker is a command-line tool with which you can check for and repair corrupted system files that might be causing file operation issues. Check out our guide to [utilizing System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) for details about how to run an SFC scan within the Command Prompt.

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command2.jpg)

## 2\. Utilize the Check Disk Tool

 Drive file system issues often cause error 0x80070570\. The most widely confirmed solution for that error is to run a CHKDSK scan of the drive you can’t delete files on or transfer files to. The CHKDSK tool can repair file system errors on the drive it’s scanning.

![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/chkdsk-scan-command.jpg)

 Our [guide to running CHKDSK on Windows](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) tells you how to initiate a Check Disk scan. You’ll need to run the Check Disk scan for the drive that includes the files you can’t delete or copy to. If that’s an external drive, you’ll need to connect the storage device to the PC and specify its letter within the command. For example, a CHKDSK command for scanning an external E: drive would be:

`chkdsk /r E:`

<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Try Moving Files to a Different Location

 If error 0x80070570 when you’re trying to transfer a file, try moving (or copying) the file into a different folder location on the target drive. You can do that by right-clicking an affected file and selecting either **Cut** or **Copy**. Then right-click inside a different folder location and select **Paste** to see if the error occurs.

## 4\. Turn Off Real-Time Antivirus Shields

 Another possible factor for error 0x80070570 occurring is your PC’s antivirus shield is hindering the file operation. That could happen if your antivirus software wrongly flags files you’re trying to transfer between drives as suspicious. So, try temporarily disabling your antivirus shield before performing the required file operation.

![The Real-time protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/real-time-protection-option.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
<!-- affiliate ads end -->

 If you don’t have third-party security software, turn off Windows Security’s real-time antivirus shield, as covered in our article about [disabling Microsoft Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/). .

 Users with third-party antivirus utilities will need to turn off their antivirus shields via the apps’ system tray context menus. Right-click the antivirus app’s icon in the system tray and select a disable or turn off shield protection setting.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=14095146&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8b6cc3ee5ec407721ce3bf5ff4c0f56b/PRO_BUY_728x90-EN.jpg" border="0"></a>
<!-- affiliate ads end -->
## 5\. Perform a Startup Repair

 This resolution is recommended if error 0x80070570 occurs when trying to delete files on the C: hard drive or transfer them there. Startup Repair is primarily a utility for fixing Windows startup issues. However, that tool can remedy corrupted system files and C: drive issues. This is how you can utilize Startup Repair:

1. First, [bring up the Advanced Startup Options menu](https://www.makeuseof.com/windows-11-access-advanced-startup-options/) via the Settings app.
2. Select **Startup Repair** within the Advanced options menu.  
![The Start-up Repair option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-up-repair.jpg)
3. Next, select your Windows user account.
4. Input your user account password.
5. Select **Continue** to initiate the repair.

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Format an External Drive

 Formatting an affected external drive to which you can’t transfer files or delete data because of error 0x80070570 is suggested only as a last resort. Applying this potential fix will wipe all data on the drive, so do not format your PC’s C: drive. However, some users have confirmed formatting affected external drives fixes error 0x80070570\.

![The format drive utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-format-tool.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-boxes.techidaily.com/new-exhaustive-breakdown-of-vsco-photography-tool-for-2024/"><u>[New] Exhaustive Breakdown of VSCO Photography Tool for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-in-2024-prime-window-viewer-for-speedy-images/"><u>[New] In 2024, Prime Window Viewer for Speedy Images</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-ace-your-online-presence-youtubes-studio-command-center/"><u>[Updated] Ace Your Online Presence  YouTube's Studio Command Center</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-ace-your-valorant-soundscape-exclusive-access-to-the-top-voice-changer-at-no-cost/"><u>[Updated] Ace Your Valorant Soundscape - Exclusive Access to the Top Voice Changer at No Cost</u></a></li>
<li><a href="https://youtube-web.techidaily.com/approved-step-by-step-guide-for-elevating-your-youtube-feedback-with-emojis/"><u>2024 Approved  Step-by-Step Guide for Elevating Your Youtube Feedback with Emojis</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-sticky-note-opening-on-windows-11/"><u>Breaking Down Sticky Note Opening on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-chromes-dark-window/"><u>Clearing Up Chrome's Dark Window</u></a></li>
<li><a href="https://windows11.techidaily.com/controlling-registry-tools-access-on-windows-11/"><u>Controlling Registry Tools Access on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/crystal-clear-in-minutes-mastering-fuzzy-window-fixes/"><u>Crystal Clear in Minutes: Mastering Fuzzy Window Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-windows-11-ease-of-use-with-improved-run-feature/"><u>Enhancing Windows 11 Ease of Use with Improved Run Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-command-prompt-tactics-for-registry-optimization/"><u>Expert Command Prompt Tactics for Registry Optimization</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-instantly-generate-multiple-directories-in-modern-windows-environments/"><u>How to Instantly Generate Multiple Directories in Modern Windows Environments</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-infinix-smart-8-hd-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>In 2024, Infinix Smart 8 HD ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-perfect-habits-to-embrace-with-podcasts-playing/"><u>In 2024, Perfect Habits to Embrace with Podcasts Playing</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-execution-descriptor-labels-in-software/"><u>Leveraging Execution Descriptor Labels in Software</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-jdk-installation-for-windows-11-users/"><u>Mastering JDK Installation for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-win11-avoid-and-fix-0x0-error-instantly/"><u>Mastering Win11: Avoid and Fix 0X0 Error Instantly</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/navigating-new-tech-frontiers-toms-hardware-evaluations-and-reviews/"><u>Navigating New Tech Frontiers: Tom's Hardware Evaluations and Reviews</u></a></li>
<li><a href="https://windows11.techidaily.com/perfectly-pivoting-to-windows-11-in-place-strategies/"><u>Perfectly Pivoting to Windows 11: In-Place Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-troubleshooting-guide-no-audio-output-error/"><u>Quick Troubleshooting Guide: No Audio Output Error</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/replace-missing-watch-playback-icons-for-2024/"><u>Replace Missing Watch Playback Icons for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/resolve-cannot-open-error-on-closed-folders-in-microsoft-mail-for-pc/"><u>Resolve Cannot Open Error on Closed Folders in Microsoft Mail for PC</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-steam-game-locks-in-windows-environment/"><u>Resolving Steam Game Locks in Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/reworking-default-view-of-task-manager-in-win11/"><u>Reworking Default View of Task Manager in Win11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/step-into-virtuality-comparing-best-vr-treadmills-for-2024/"><u>Step Into Virtuality  Comparing Best VR Treadmills for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-customizing-your-windows-11-notepad-appearance/"><u>Step-by-Step: Customizing Your Windows 11 Notepad Appearance</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-frustration-with-non-responsive-photoshop/"><u>Tackling Frustration with Non-Responsive Photoshop</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-break-the-bond-onedrive-from-ms-account-on-windows/"><u>Techniques to Break the Bond: OneDrive From MS Account on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-the-best-encoding-methods-on-pc/"><u>Understanding the Best Encoding Methods on PC</u></a></li>
<li><a href="https://howto.techidaily.com/vivo-v29-not-connecting-to-wi-fi-12-quick-ways-to-fix-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Vivo V29 Not Connecting to Wi-Fi? 12 Quick Ways to Fix | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-the-angle-game-rotate-images-in-6-steps-w11/"><u>Winning the Angle Game: Rotate Images in 6 Steps W11</u></a></li>
</ul></div>