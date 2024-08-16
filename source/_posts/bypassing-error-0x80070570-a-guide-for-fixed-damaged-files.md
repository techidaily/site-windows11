---
title: "Bypassing Error 0X80070570: A Guide for Fixed Damaged Files"
date: 2024-08-15T16:12:12.196Z
updated: 2024-08-16T16:12:12.196Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Bypassing Error 0X80070570: A Guide for Fixed Damaged Files"
excerpt: "This Article Describes Bypassing Error 0X80070570: A Guide for Fixed Damaged Files"
keywords: File Corruption Fix,Error Code X80070570 Solution,Repairing File System Errors,Overcoming 0X80070570 Error,Damaged Files Recovery Guide,Windows Error 0X80070570 Fix,Solving X70070570 File Issue
thumbnail: https://thmb.techidaily.com/42f2023e8fbcdfdd01f86d9db51a4f7bd6fa603af8cb31396f717d24438f83e9.jpg
---

## Bypassing Error 0X80070570: A Guide for Fixed Damaged Files

 Error 0x80070570 is a Windows issue that sometimes pops up when you try to delete files on external hard drives. This error also occurs when users try to transfer files between PCs and external drives. The error 0x80070570 message says, “The file or directory is corrupted and unreadable.”

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.

## 1\. Repair System Files With an SFC Scan

 Some users have confirmed repairing system files resolved error 0x80070570 on their PCs. System File Checker is a command-line tool with which you can check for and repair corrupted system files that might be causing file operation issues. Check out our guide to [utilizing System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) for details about how to run an SFC scan within the Command Prompt.

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command2.jpg)

## 2\. Utilize the Check Disk Tool

 Drive file system issues often cause error 0x80070570\. The most widely confirmed solution for that error is to run a CHKDSK scan of the drive you can’t delete files on or transfer files to. The CHKDSK tool can repair file system errors on the drive it’s scanning.

![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/chkdsk-scan-command.jpg)
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Our [guide to running CHKDSK on Windows](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) tells you how to initiate a Check Disk scan. You’ll need to run the Check Disk scan for the drive that includes the files you can’t delete or copy to. If that’s an external drive, you’ll need to connect the storage device to the PC and specify its letter within the command. For example, a CHKDSK command for scanning an external E: drive would be:

`chkdsk /r E:`

## 3\. Try Moving Files to a Different Location

 If error 0x80070570 when you’re trying to transfer a file, try moving (or copying) the file into a different folder location on the target drive. You can do that by right-clicking an affected file and selecting either **Cut** or **Copy**. Then right-click inside a different folder location and select **Paste** to see if the error occurs.

<!-- affiliate ads begin -->

<!-- affiliate ads end -->
## 4\. Turn Off Real-Time Antivirus Shields

 Another possible factor for error 0x80070570 occurring is your PC’s antivirus shield is hindering the file operation. That could happen if your antivirus software wrongly flags files you’re trying to transfer between drives as suspicious. So, try temporarily disabling your antivirus shield before performing the required file operation.

![The Real-time protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/real-time-protection-option.jpg)

 If you don’t have third-party security software, turn off Windows Security’s real-time antivirus shield, as covered in our article about [disabling Microsoft Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/). .

 Users with third-party antivirus utilities will need to turn off their antivirus shields via the apps’ system tray context menus. Right-click the antivirus app’s icon in the system tray and select a disable or turn off shield protection setting.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-platform-ui-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
## 5\. Perform a Startup Repair

 This resolution is recommended if error 0x80070570 occurs when trying to delete files on the C: hard drive or transfer them there. Startup Repair is primarily a utility for fixing Windows startup issues. However, that tool can remedy corrupted system files and C: drive issues. This is how you can utilize Startup Repair:

1. First, [bring up the Advanced Startup Options menu](https://www.makeuseof.com/windows-11-access-advanced-startup-options/) via the Settings app.
2. Select **Startup Repair** within the Advanced options menu.  
![The Start-up Repair option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-up-repair.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
3. Next, select your Windows user account.
4. Input your user account password.
5. Select **Continue** to initiate the repair.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075475/7443" target="_top" id="2075475"><img src="//a.impactradius-go.com/display-ad/7443-2075475" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Format an External Drive

 Formatting an affected external drive to which you can’t transfer files or delete data because of error 0x80070570 is suggested only as a last resort. Applying this potential fix will wipe all data on the drive, so do not format your PC’s C: drive. However, some users have confirmed formatting affected external drives fixes error 0x80070570\.

![The format drive utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-format-tool.jpg)

 You can format an external drive with the Windows Disk Management utility or in File Explorer. Connect the drive to your PC, and then follow the steps in this guide on [how to format a USB drive](https://www.makeuseof.com/tag/format-usb-drive/) to do this within File Explorer.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->
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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-mac-based-strategies-for-shorter-insta-videos/"><u>[New] 2024 Approved  Mac-Based Strategies for Shorter Insta Videos</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-exploiting-youtubes-creative-commons-in-media-making-for-2024/"><u>[New] Exploiting YouTube's Creative Commons in Media Making for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-learn-cinematic-techniques-with-youtube-veterans-and-novices/"><u>[New] Learn Cinematic Techniques with YouTube Veterans and Novices</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-audiovisual-alchemy-formulating-your-youtube-playlist/"><u>[Updated] Audiovisual Alchemy  Formulating Your YouTube Playlist</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-making-marks-trendsetting-on-social-media-platforms/"><u>[Updated] Making Marks  Trendsetting on Social Media Platforms</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-mastering-facebook-live-embedding-techniques-on-websites-for-2024/"><u>[Updated] Mastering Facebook Live Embedding Techniques on Websites for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-advanced-system-stitching-gopro-images-into-a-circular-videography-canvas/"><u>2024 Approved  Advanced System  Stitching GoPro Images Into a Circular Videography Canvas</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-maximizing-revenue-a-youtube-channelers-guide/"><u>2024 Approved  Maximizing Revenue  A YouTube Channeler’s Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-windows-pathways-to-filefolder-secrets/"><u>Expert Windows Pathways to File/Folder Secrets</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-error-0x8019-in-windows-updates/"><u>Fixing Error 0X8019 in Windows Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/from-novice-to-pro-mastering-github-desktop-on-windows-11/"><u>From Novice to Pro: Mastering GitHub Desktop on Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fake-gps-on-samsung-galaxy-xcover-7-for-mobile-legends-drfone-by-drfone-virtual-android/"><u>How To Fake GPS On Samsung Galaxy XCover 7 For Mobile Legends? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-stop-win11-from-showing-00-error-codes/"><u>How to Stop Win11 From Showing 00 Error Codes</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/immediate-fixes-fb-messenger-video-sending-hitch-on-mobile-devices-for-2024/"><u>Immediate Fixes  FB Messenger Video Sending Hitch on Mobile Devices for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-8-best-video-conferencing-software-for-small-business-safely/"><u>In 2024, 8 Best Video Conferencing Software for Small Business Safely</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-a-deep-dive-into-vscos-creative-palette/"><u>In 2024, A Deep Dive Into VSCO's Creative Palette</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-spotify-location-after-moving-to-another-country-on-oppo-reno-10-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Spotify Location After Moving to Another Country On Oppo Reno 10 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-revolutionary-entry-points-for-zooids/"><u>In 2024, Revolutionary Entry Points for Zooids</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-10-best-spy-watches-for-your-oneplus-nord-n30-se-drfone-by-drfone-virtual-android/"><u>In 2024, Top 10 Best Spy Watches For your OnePlus Nord N30 SE | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/integrate-video-archives-for-streaming-companionship/"><u>Integrate Video Archives for Streaming Companionship</u></a></li>
<li><a href="https://windows11.techidaily.com/managing-windows-modules-installer-resource-demand/"><u>Managing Windows Modules Installer Resource Demand</u></a></li>
<li><a href="https://windows11.techidaily.com/master-note-taking-on-win11-easy-as-pie/"><u>Master Note-Taking on Win11, Easy as Pie</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-fixes-for-hardware-detection-faults/"><u>Mastering Fixes for Hardware Detection Faults</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-sefx-windows-11-sfx-creation/"><u>Mastering SEFX: Windows 11 SFX Creation</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-for-resolving-process-termination-failure-on-pcs/"><u>Methods for Resolving 'Process Termination Failure' On PCs</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-chrome-file-uploading-woes-a-guide-for-windows-devices/"><u>Navigate Chrome File Uploading Woes: A Guide for Windows Devices</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-free-video-fx-apps-the-ultimate-list-for-ios-and-android-for-2024/"><u>New Free Video FX Apps The Ultimate List for iOS and Android for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-microphone-performance-with-xbox-app-windows-11/"><u>Optimizing Microphone Performance with Xbox App Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-grayscale-windows-backdrops-tips-for-enhancement/"><u>Overcoming Grayscale Windows Backdrops: Tips for Enhancement</u></a></li>
<li><a href="https://windows11.techidaily.com/preventive-measures-for-csgo-launch-woes-on-windows-11/"><u>Preventive Measures for CS:GO Launch Woes on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-lsa-errors-on-windows-pcs/"><u>Quick Fixes for LSA Errors on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/reflect-on-one-misconception-about-cultural-relativism-mentioned-in-class-then-describe-how-you-would-address-this-misunderstanding-with-someone-from-a-diff21/"><u>Reflect on One Misconception About Cultural Relativism Mentioned in Class, Then Describe How You Would Address This Misunderstanding with Someone From a Different Culture</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-issues-for-microsoft-store-access-on-windows-11/"><u>Resolving Issues for Microsoft Store Access on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-unresizable-gif-error-tips-for-discord-on-windows-11/"><u>Resolving Unresizable GIF Error: Tips for Discord on Windows 11</u></a></li>
<li><a href="https://win-answers.techidaily.com/silence-no-more-essential-tips-for-addressing-audio-problems-in-minecraft-on-desktop-systems/"><u>Silence No More! Essential Tips for Addressing Audio Problems in Minecraft on Desktop Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-to-reduce-cpu-consumption-fixing-dropbox-on-windows/"><u>Solutions to Reduce CPU Consumption: Fixing Dropbox on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-ax201-wi-fi-6-error-on-windows/"><u>Steps to Resolve AX201 Wi-Fi 6 Error on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/systematic-steps-for-nullifying-your-windows-drive-partitions/"><u>Systematic Steps for Nullifying Your Windows Drive Partitions</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-deal-with-missing-values-on-pcs-running-winos/"><u>Techniques to Deal with Missing Values on PCs Running WinOS</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-ultimate-language-battle-evaluating-the-performance-of-chatgpt-against-google-translate/"><u>The Ultimate Language Battle: Evaluating the Performance of ChatGPT Against Google Translate</u></a></li>
<li><a href="https://windows11.techidaily.com/top-7-photo-arrangers-for-a-clutter-free-pc-desktop/"><u>Top 7 Photo Arrangers for a Clutter-Free PC Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-winservicesexe-on-your-pc/"><u>Troubleshooting Winservices.exe on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-peak-performance-why-choose-windows-for-gaming/"><u>Unleashing Peak Performance: Why Choose Windows for Gaming</u></a></li>
<li><a href="https://android-unlock.techidaily.com/unlock-your-vivo-x90ss-potential-the-top-20-lock-screen-apps-you-need-to-try-by-drfone-android/"><u>Unlock Your Vivo X90Ss Potential The Top 20 Lock Screen Apps You Need to Try</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-hidden-potential-in-vintage-video-gaming-titles-using-retroarch/"><u>Unlocking Hidden Potential in Vintage Video Gaming Titles Using Retroarch</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-microsoft-family-safety-potential/"><u>Unlocking Microsoft Family Safety Potential</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unlocking-potential-top-six-uses-of-the-chatgpt-code-interpretation-tool/"><u>Unlocking Potential: Top Six Uses of the ChatGPT Code Interpretation Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-vivetool-enable-unseen-features-on-windows-pcs/"><u>Unraveling ViVeTool: Enable Unseen Features on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-windows-odbc-command-center/"><u>Unveiling the Windows ODBC Command Center</u></a></li>
<li><a href="https://windows11.techidaily.com/win10win11-diagnostics-tackling-0x0000004e-faults/"><u>Win10/Win11 Diagnostics: Tackling 0X0000004E Faults</u></a></li>
</ul></div>
