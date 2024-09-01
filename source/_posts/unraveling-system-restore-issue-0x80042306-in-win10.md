---
title: Unraveling System Restore Issue 0X80042306 in Win10
date: 2024-08-31T22:16:55.713Z
updated: 2024-09-01T22:16:55.713Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unraveling System Restore Issue 0X80042306 in Win10
excerpt: This Article Describes Unraveling System Restore Issue 0X80042306 in Win10
keywords: Win10 Restore Error,0X80042306 Fix,System Recovery Issue,Win10 Backup Failure,OS Restoration Problems,Bootloader Troubleshoot,Data Recovery in Windows
thumbnail: https://thmb.techidaily.com/e576fa6a569d314a929d202ace0124c24bb9f5c7c863ef858ebb7371b469a682.jpg
---

## Unraveling System Restore Issue 0X80042306 in Win10

 The error code 0x80042306 occurs when attempting to create a restore point in Windows. It prevents the creation of new restore points in the system and typically occurs when your system does not have sufficient free space, there is a problem with the Volume Shadow Copy service (VSS), or a background process is conflicting with the restore utility.

 Below, we talk about the different troubleshooting methods you can try to fix the system restore error 0x80042306 in Windows. We recommend booting into the administrator account before you proceed.

## 1\. Make Sure You Have Sufficient Space

 Restore points require free space on the disk they are stored. This amount of space required by a restore point typically depends on on the size and complexity of your system configuration.

 If you do not have sufficient space on the disk, the restore utility is likely to return a 0x80042306 error. This is why, we recommend getting started by making sure that enough free space for the System Restore to function correctly. You can delete unnecessary items to increase the space manually, or[use the Disk Cleanup](https://www.makeuseof.com/tag/best-way-clean-windows-10-step-step-guide/) utility that is offered by Microsoft by default.

 Alternatively, you can also increase the amount of disk space allocated for System Restore in the System Protection settings. Here is how you can do that:

1. Type "Create a restore point" in the Windows search utility and click**Open** .
2. In the following dialog, head over to the**System Protection** tab.
3. Click on the**Configure** button and use the Max usage to slider to adjust the disk percentage according to your preference.  
![Adjust the Max usage slider](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/restore-point-usage.jpg)
4. Click**Apply** \>**OK** to save the changes.

 Once the changes are made, check if you can now create a restore point without any issues.

## 2\. Restart the Volume Shadow Copy Service

 You might also be facing the problem if the Volume Shadow Copy service is disabled or simply not functioning properly.

 This service allows the creation of backup copies for files and volumes in Windows. It is used to by the restore utility to create snapshots of the items that are being backed up and if it fails to work due to any reason, you might encounter the problem at hand.

 To ensure this service is working properly, you can restart it using the Services utility. Follow the steps below to proceed:

1. Press the**Win** +**R** keys together to open Run.
2. Type "services.msc" in Run and click**Enter** .
3. In the services window, scroll down to locate the**Volume Shadow Copy** service and right-click on it.  
![Volume Shadow Copy service in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/volume-shadow-copy.jpg)
4. Choose**Properties** from the context menu.
5. Now, click on the**Stop** button, wait for a few seconds, and hit**Start** again.
6. Make sure the Startup type is set to**Automatic** .  
![Start the VSS service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/start-vss-service.jpg)
7. Finally, click**Apply** \>**OK** to save the changes.

 Do the same for the Windows Backup service and check if the issue is resolved.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Re-Register VSS Components

 If restarting the Volume Shadow Copy service did not work, then you can also try re-registering the VSS components via Command Prompt.

Here is how to proceed:

1. Press the**Win** +**R** keys together to open Run.
2. Type "cmd" in Run and press the**Ctrl** +**Shift** +**Enter** keys together to open Command Prompt as an administrator.
3. Click**Yes** in the User Account Control prompt.
4. Now, execute the following commands one by one:  
`cd /d %windir%\system32net stop vssnet stop swprvregsvr32 /s ole32.dllregsvr32 /s oleaut32.dllregsvr32 /s vss_ps.dllvssvc /registerregsvr32 /s /i  

swprv.dllregsvr32 /s /i eventcls.dllregsvr32 /s es.dllregsvr32 /s stdprov.dllregsvr32 /s vssui.dllregsvr32 /s msxml.dllregsvr32 /s  

msxml3.dllregsvr32 /s msxml4.dllvssvc /registernet start swprvnet start vss`
5. Once you have re-registered VSS components, close Command Prompt and try creating a restore point again.

 If an issue within the VSS components was causing the problem, restarting the components should fix it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->
## 4\. Create a Restore Point in Safe Mode

 In some cases, a conflicting background process can also prevent the System Restore utility from creating a restore point successfully. The best way to ensure there are no applications or programs in the background interrupting the functionality of System Restore, try creating a restore point in Safe Mode.

 This mode launches Windows with a minimal set of drivers and services, which can help isolate the issue and prevent any conflicts that may be occurring in normal mode.

Here is how you can boot in Safe Mode:

1. Type "System Configuration" in Windows search and click**Open** .
2. Head over to the**Boot** tab and under Boot Options, checkmark the Safe Boot option.
3. Choose**Minimal** and click on**Apply** \>**OK** to save the changes.  
![Minimal mode of Safe Boot](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/msconfig-boot-safe-mode-minimal.jpg)

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
 You can now restart your computer and upon reboot, you should enter the Safe Mode automatically. Try recreating a restore point and check if the problem is resolved.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
## 5\. Scan the System For Corruption Errors

![Running Sfc scan in CMD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/running-sfc-scan.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
 The System Restore utility itself might be dealing with a corruption error, which is preventing it from functioning properly.

 To fix any corrupt system files, we suggest using the System File Checker (SFC) and Deployment Image Servicing and Management (DISM) tools. SFC works by scanning the protected system files for underlying problems. If an issue is discovered, it will replace the faulty file with its healthier cached counterpart.

 DISM, on the other hand, works by repairing corrupt system images. We have a guide on[how to use SFC and DISM in Windows](https://www.makeuseof.com/windows-built-in-repair-tools/) which you can refer to, to perform the steps correctly.

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254762&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/11_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
## System Restore Back On Track

 The System Restore utility in Windows is a powerful tool that can save you from losing important data in case of unexpected system issues. That said, it can be annoying if you cannot create a restore point easily, especially when you are trying to do it before performing a critical action.

 By following the methods outlined in this guideline, you can diagnose the error and take necessary steps to resolve it. We recommend making sure all the relevant services stay enabled, and your system is up-to-date to avoid any such issues in the future.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-sure.techidaily.com/024-approved-masterful-seo-approaches-for-soaring-in-youtube-video-popularity/"><u>[New] 2024 Approved  Masterful SEO Approaches for Soaring in YouTube Video Popularity</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-ffpm-demystified-your-guide-to-multi-tasking/"><u>[New] FFPM Demystified  Your Guide to Multi-Tasking</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-social-media-momentum-linking-igtv-and-fb/"><u>[New] In 2024, Social Media Momentum  Linking IGTV and FB</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-ensuring-legitimacy-of-your-youtube-sign-in/"><u>[Updated] Ensuring Legitimacy of Your YouTube Sign-In</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-excellent-webcam-recorders-on-windows-10/"><u>[Updated] In 2024, Excellent Webcam Recorders on Windows 10</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-leading-edge-apps-for-mobile-screen-recording/"><u>[Updated] In 2024, Leading Edge Apps for Mobile Screen Recording</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-revolutionary-audio-alteration-for-enhanced-pubg-experience-for-2024/"><u>[Updated] Revolutionary Audio Alteration for Enhanced PUBG Experience for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-simplified-approaches-to-recording-your-iptv-viewing/"><u>[Updated] Simplified Approaches to Recording Your IPTV Viewing</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-unveilingeaseinusingyourwebcamforrecord-for-2024/"><u>[Updated] UnveilingEaseInUsingYourWebCamForRecord for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-channel-honor-roll-play-button-and-follower-awards/"><u>2024 Approved  Channel Honor Roll - Play Button & Follower Awards</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-cutting-and-compositing-for-youtube-videos-using-premiere-pro/"><u>2024 Approved  Cutting and Compositing for YouTube Videos Using Premiere Pro</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-finding-your-ideal-viewing-experience-with-projection-or-television/"><u>2024 Approved  Finding Your Ideal Viewing Experience with Projection or Television</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-leveraging-instagrams-video-features-a-how-to-guide/"><u>2024 Approved  Leveraging Instagram's Video Features  A How-To Guide</u></a></li>
<li><a href="https://techtrends.techidaily.com/elite-list-of-the-most-secure-email-services-online/"><u>Elite List of the Most Secure Email Services Online</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/essential-forgotten-free-text-from-mac-speech-devices/"><u>Essential, Forgotten Free Text From Mac Speech Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/expedite-data-access-seamless-entry-into-windows-11-disk-editor/"><u>Expedite Data Access: Seamless Entry Into Windows 11 Disk Editor</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-advice-how-to-reset-win11-search-default-configurations/"><u>Expert Advice: How to Reset Win11 Search Default Configurations</u></a></li>
<li><a href="https://facebook.techidaily.com/face-theft-head-on-immediate-steps-for-social-media-safety/"><u>Face Theft Head-On: Immediate Steps for Social Media Safety</u></a></li>
<li><a href="https://windows11.techidaily.com/fast-track-to-enabling-telnet-in-win11-pcs/"><u>Fast Track to Enabling Telnet in Win11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-roblox-on-screen-stop-issues-on-windows-systems/"><u>Fixing Roblox On-Screen Stop Issues on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-turn-off-windows-from-starting-spotify/"><u>Guide to Turn Off Windows From Starting Spotify</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-a-portable-software-menu-to-windows-10-and-11/"><u>How to Add a Portable Software Menu to Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-copy-and-paste-not-working-in-windows-11/"><u>How to Fix Copy and Paste Not Working in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-irq-problems-with-your-soundcard-on-windows/"><u>How to Fix IRQ Problems With Your Soundcard on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-rectify-unmovable-scrolling-in-excel-windows/"><u>How to Rectify Unmovable Scrolling in Excel (Windows)</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-elevate-engagement-enhancing-videos-with-pro-editing-skills/"><u>In 2024, Elevate Engagement  Enhancing Videos with Pro Editing Skills</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-the-ultimate-blueprint-for-perfecting-zooms-screen-cast/"><u>In 2024, The Ultimate Blueprint for Perfecting Zoom's Screen Cast</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/leading-edge-speech-recognition-tools/"><u>Leading Edge Speech Recognition Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-monitors-choosing-personalized-themes-in-win-1011/"><u>Maximizing Monitors: Choosing Personalized Themes in Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-disconnected-spotify-sessions-in-w10w11/"><u>Mending Disconnected Spotify Sessions in W10/W11</u></a></li>
<li><a href="https://windows11.techidaily.com/modify-your-windows-personalized-spotlight-image/"><u>Modify Your Windows Personalized Spotlight Image</u></a></li>
<li><a href="https://windows11.techidaily.com/muting-mayhem-reverse-sound-suppression-in-windows/"><u>Muting Mayhem? Reverse Sound Suppression in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-and-understanding-how-to-use-imessage-on-your-computer/"><u>Navigating and Understanding How to Use iMessage on Your Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-windows-11-registry-for-obscured-themes/"><u>Navigating the Windows 11 Registry for Obscured Themes</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-the-ultimate-guide-to-tiktok-watermark-removal-online/"><u>New The Ultimate Guide to TikTok Watermark Removal Online</u></a></li>
<li><a href="https://windows11.techidaily.com/peering-into-major-complaints-about-windows-11-launch/"><u>Peering Into Major Complaints About Windows 11 Launch</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/pioneering-changes-to-your-pubg-characters-speech/"><u>Pioneering Changes to Your PUBG Character's Speech</u></a></li>
<li><a href="https://windows11.techidaily.com/pioneering-retro-upgrades-atlasos-transformation/"><u>Pioneering Retro Upgrades: AtlasOS Transformation</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-recovery-reviving-a-vanished-windows-update/"><u>Quick Recovery: Reviving a Vanished Windows Update</u></a></li>
<li><a href="https://windows11.techidaily.com/recover-lost-audio-output-in-non-responsive-os/"><u>Recover Lost Audio Output in Non-Responsive OS</u></a></li>
<li><a href="https://windows11.techidaily.com/reversing-game-launch-hurdles-with-epic-logins/"><u>Reversing Game Launch Hurdles with Epic Logins</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-browsing-at-fingertips-activating-gestures-in-microsoft-edge-win-11-edition/"><u>Seamless Browsing at Fingertips: Activating Gestures in Microsoft Edge, Win 11 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-the-mystery-of-error-0x0000004e-on-windows/"><u>Solving the Mystery of Error 0X0000004E on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/spotting-the-green-light-and-red-alert-windows-login-status/"><u>Spotting the Green Light & Red Alert: Windows Login Status</u></a></li>
<li><a href="https://windows11.techidaily.com/stopping-missteps-in-mouse-travel-with-simple-fixes/"><u>Stopping Missteps in Mouse Travel with Simple Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-voice-input-in-windows-11-with-shortcuts-guide/"><u>Streamlining Voice Input in Windows 11 with Shortcuts Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-your-workspace-integrating-directories-into-taskbar-menu/"><u>Streamlining Your Workspace: Integrating Directories Into Taskbar Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/tackle-non-working-shift-with-simple-tweaks/"><u>Tackle Non-Working Shift with Simple Tweaks</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-your-first-load-webpage-on-win11/"><u>Tailoring Your First Load Webpage on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-winning-package-tool-for-you-a-choco-vs-wm-quest/"><u>The Winning Package Tool for You: A Choco VS. WM Quest</u></a></li>
<li><a href="https://howto.techidaily.com/top-4-android-system-repair-software-for-lava-yuva-2-bricked-devices-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 4 Android System Repair Software for Lava Yuva 2 Bricked Devices | Dr.fone</u></a></li>
<li><a href="https://win-solutions.techidaily.com/troubleshooting-guide-solving-new-world-game-lags-and-connectivity-problems/"><u>Troubleshooting Guide: Solving 'New World' Game Lags and Connectivity Problems</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/unveiling-the-20-core-strategies-for-effective-facebook-video-ads-for-2024/"><u>Unveiling the 20 Core Strategies for Effective Facebook Video Ads for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-free-and-fabulous-the-top-10-4k-video-converters-you-need-for-2024/"><u>Updated Free and Fabulous The Top 10 4K Video Converters You Need for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-against-windowss-notorious-pink-screens/"><u>Winning Against Windows's Notorious Pink Screens</u></a></li>
</ul></div>
