---
title: Overcoming Windows Restore Error 0X80042306 Quickly
date: 2024-08-15T16:15:16.532Z
updated: 2024-08-16T16:15:16.532Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Windows Restore Error 0X80042306 Quickly
excerpt: This Article Describes Overcoming Windows Restore Error 0X80042306 Quickly
keywords: Fix Restore Error Windows,Solve WinError 0X80042306,Windows Restore Issue Resolution,Eliminate X80042306 Restore Failure,Quick Windows Recovery Fix,Overcome Error WINERROR42306,Fast Solve WinRestError 0X80042306
thumbnail: https://thmb.techidaily.com/c6b4aa7955ba2d8b8f78045fdb4fec883a94ff6f2b309e9331565432f2ce8641.jpg
---

## Overcoming Windows Restore Error 0X80042306 Quickly

 The error code 0x80042306 occurs when attempting to create a restore point in Windows. It prevents the creation of new restore points in the system and typically occurs when your system does not have sufficient free space, there is a problem with the Volume Shadow Copy service (VSS), or a background process is conflicting with the restore utility.

 Below, we talk about the different troubleshooting methods you can try to fix the system restore error 0x80042306 in Windows. We recommend booting into the administrator account before you proceed.

## 1\. Make Sure You Have Sufficient Space

 Restore points require free space on the disk they are stored. This amount of space required by a restore point typically depends on on the size and complexity of your system configuration.

 If you do not have sufficient space on the disk, the restore utility is likely to return a 0x80042306 error. This is why, we recommend getting started by making sure that enough free space for the System Restore to function correctly. You can delete unnecessary items to increase the space manually, or [use the Disk Cleanup](https://www.makeuseof.com/tag/best-way-clean-windows-10-step-step-guide/) utility that is offered by Microsoft by default.

 Alternatively, you can also increase the amount of disk space allocated for System Restore in the System Protection settings. Here is how you can do that:

1. Type "Create a restore point" in the Windows search utility and click**Open** .
2. In the following dialog, head over to the**System Protection** tab.
3. Click on the**Configure** button and use the Max usage to slider to adjust the disk percentage according to your preference.  
![Adjust the Max usage slider](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/restore-point-usage.jpg)
4. Click**Apply** \>**OK** to save the changes.

 Once the changes are made, check if you can now create a restore point without any issues.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3727260&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. Restart the Volume Shadow Copy Service

 You might also be facing the problem if the Volume Shadow Copy service is disabled or simply not functioning properly.

 This service allows the creation of backup copies for files and volumes in Windows. It is used to by the restore utility to create snapshots of the items that are being backed up and if it fails to work due to any reason, you might encounter the problem at hand.

 To ensure this service is working properly, you can restart it using the Services utility. Follow the steps below to proceed:

1. Press the**Win** +**R** keys together to open Run.
2. Type "services.msc" in Run and click**Enter** .
3. In the services window, scroll down to locate the**Volume Shadow Copy** service and right-click on it.  
![Volume Shadow Copy service in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/volume-shadow-copy.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->
4. Choose**Properties** from the context menu.
5. Now, click on the**Stop** button, wait for a few seconds, and hit**Start** again.
6. Make sure the Startup type is set to**Automatic** .  
![Start the VSS service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/start-vss-service.jpg)
7. Finally, click**Apply** \>**OK** to save the changes.

 Do the same for the Windows Backup service and check if the issue is resolved.

<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
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

## 4\. Create a Restore Point in Safe Mode

 In some cases, a conflicting background process can also prevent the System Restore utility from creating a restore point successfully. The best way to ensure there are no applications or programs in the background interrupting the functionality of System Restore, try creating a restore point in Safe Mode.

 This mode launches Windows with a minimal set of drivers and services, which can help isolate the issue and prevent any conflicts that may be occurring in normal mode.

Here is how you can boot in Safe Mode:

1. Type "System Configuration" in Windows search and click**Open** .
2. Head over to the**Boot** tab and under Boot Options, checkmark the Safe Boot option.
3. Choose**Minimal** and click on**Apply** \>**OK** to save the changes.  
![Minimal mode of Safe Boot](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/msconfig-boot-safe-mode-minimal.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->

 You can now restart your computer and upon reboot, you should enter the Safe Mode automatically. Try recreating a restore point and check if the problem is resolved.

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Scan the System For Corruption Errors

![Running Sfc scan in CMD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/running-sfc-scan.jpg)

 The System Restore utility itself might be dealing with a corruption error, which is preventing it from functioning properly.

 To fix any corrupt system files, we suggest using the System File Checker (SFC) and Deployment Image Servicing and Management (DISM) tools. SFC works by scanning the protected system files for underlying problems. If an issue is discovered, it will replace the faulty file with its healthier cached counterpart.

 DISM, on the other hand, works by repairing corrupt system images. We have a guide on [how to use SFC and DISM in Windows](https://www.makeuseof.com/windows-built-in-repair-tools/) which you can refer to, to perform the steps correctly.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-activity-recording.techidaily.com/new-efficient-methods-for-nvidia-screen-recording-for-2024/"><u>[New] Efficient Methods for NVIDIA Screen Recording for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-exploring-the-neuroscience-of-decision-making-and-its-implications-for-leadership/"><u>[New] Exploring the Neuroscience of Decision-Making and Its Implications for Leadership</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-guided-approach-to-saving-exact-youtube-segments-for-2024/"><u>[New] Guided Approach to Saving Exact YouTube Segments for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-how-to-tackle-missing-thumbnails-on-youtube-shorts/"><u>[New] In 2024, How to Tackle Missing Thumbnails on YouTube Shorts</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-integrating-subtitles-into-your-vimeo-projects/"><u>[New] In 2024, Integrating Subtitles Into Your Vimeo Projects</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-best-ranked-affordable-video-players-and-streaming-services-pc-and-mobile/"><u>[Updated] Best-Ranked Affordable Video Players and Streaming Services (PC & Mobile)</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-cutting-edge-gaming-setup-unpacking-samsungs-ue590-panel-for-2024/"><u>[Updated] Cutting Edge Gaming Setup  Unpacking Samsung's UE590 Panel for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-premium-podcast-partners-in-academia/"><u>[Updated] Premium Podcast Partners in Academia</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-best-online-tools-discovering-the-top-10-dynamic-image-changers/"><u>2024 Approved  Best Online Tools  Discovering the Top 10 Dynamic Image Changers</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-pure-joy-of-gratuitous-screen-mingle-games/"><u>2024 Approved  Pure Joy of Gratuitous Screen Mingle Games</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-ultimate-guide-to-screen-grabbers/"><u>2024 Approved  Ultimate Guide to Screen Grabbers</u></a></li>
<li><a href="https://buynow-info.techidaily.com/1722773008533-amazonbasics-7-port-usb-30-hub-reviewed-the-ultimate-multipurpose-connector-for-tech-lovers/"><u>AmazonBasics 7-Port USB 3.0 Hub Reviewed: The Ultimate Multipurpose Connector for Tech Lovers!</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/android-unlock-code-sim-unlock-your-asus-rog-phone-7-phone-and-remove-locked-screen-by-drfone-android/"><u>Android Unlock Code Sim Unlock Your Asus ROG Phone 7 Phone and Remove Locked Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/dodgy-deals-understanding-the-threats-of-low-price-windows-licenses/"><u>Dodgy Deals: Understanding the Threats of Low-Price Windows Licenses</u></a></li>
<li><a href="https://windows11.techidaily.com/drive-dynamics-streamlining-storage-space-in-win11/"><u>Drive Dynamics: Streamlining Storage Space in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/drive-success-top-5-windows-productivity-hacks-you-cant-miss/"><u>Drive Success: Top 5 Windows Productivity Hacks You Can't Miss</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-command-line-master-20-key-cmd-commands/"><u>Efficient Command Line: Master 20 Key CMD Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-local-drive-usage-keeping-your-data-safe-in-win11-max-156-chars/"><u>Efficient Local Drive Usage: Keeping Your Data Safe in Win11 (Max 156 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-windows-partition-integration-strategies/"><u>Efficient Windows Partition Integration Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-managing-your-c-drive-usage-on-windows/"><u>Efficiently Managing Your C: Drive Usage on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-resolving-windows-audio-glitches-error-code-9999/"><u>Efficiently Resolving Windows Audio Glitches: Error Code 9999</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-focus-discover-these-8-premier-timers-for-pc-tasks/"><u>Effortless Focus: Discover These 8 Premier Timers For PC Tasks</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-windows-method-to-determine-ram-specifications/"><u>Effortless Windows Method to Determine RAM Specifications</u></a></li>
<li><a href="https://windows11.techidaily.com/effortlessly-create-win-11-boot-drive-using-these-3-methods/"><u>Effortlessly Create Win 11 Boot Drive Using These 3 Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-internet-safety-in-windows-11-trusted-site-listing/"><u>Elevate Internet Safety in Windows 11: Trusted Site Listing</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-usability-and-style-for-windows-1011-in-8-ways/"><u>Elevate Usability and Style for Windows 10/11 in 8 Ways</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-audio-experience-with-windows-11-settings/"><u>Elevate Your Audio Experience with Windows 11 Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-game-amplifying-graphics-power-in-windows-1011/"><u>Elevate Your Game: Amplifying Graphics Power in Windows 10/11</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723125257451-elevate-your-raspberry-pi-projects-with-the-premier-selection-of-2024s-top-hat-devices/"><u>Elevate Your Raspberry Pi Projects with the Premier Selection of 2024'S Top HAT Devices!</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-workflow-master-the-taskbar-in-win-11/"><u>Elevate Your Workflow: Master the Taskbar in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-device-safety-with-custom-lock-patterns-in-windows-11/"><u>Elevating Device Safety with Custom Lock Patterns in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminate-no-errors-comprehensible-guide-to-fixing-win11-issues/"><u>Eliminate No Errors: Comprehensible Guide to Fixing Win11 Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminate-old-wallpaper-3-efficient-methods/"><u>Eliminate Old Wallpaper: 3 Efficient Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-we-encountered-an-error-oculus-w11w10-guide/"><u>Eliminating We Encountered an Error: Oculus W11/W10 Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/embarking-on-a-journey-with-ai-copilot-in-windows-11/"><u>Embarking on a Journey with AI Copilot in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/emergency-printer-deletion-in-windows-os-a-step-by-step-approach/"><u>Emergency Printer Deletion in Windows OS: A Step-by-Step Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/empowering-windows-11-android-phone-webcam-utilization/"><u>Empowering Windows 11: Android Phone Webcam Utilization</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/endless-viewing-with-iphone-writes-of-video-for-2024/"><u>Endless Viewing with iPhone' Writes of Video for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-windows-security-today-the-best-7-free-password-creator-apps/"><u>Enhance Windows Security Today: The Best 7 Free Password Creator Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-wordsmithing-effortlessly-with-top-apps-windows/"><u>Enhance Wordsmithing Effortlessly With Top Apps (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-qbittorrent-performance-after-a-halt/"><u>Enhancing qBittorrent Performance After a Halt</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-search-capabilities-of-windows-11-os/"><u>Enhancing Search Capabilities of Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/enriching-macos-with-windows-powered-innovations/"><u>Enriching macOS with Windows-Powered Innovations</u></a></li>
<li><a href="https://windows11.techidaily.com/enriching-windows-taskmanager-with-cli-tab-feature/"><u>Enriching Windows TaskManager with CLI Tab Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-high-visibility-of-taskmanager/"><u>Ensuring High Visibility of TaskManager</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicate-black-screen-on-win11-top-easy-fixes/"><u>Eradicate Black Screen on Win11: Top Easy Fixes!</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicating-glitch-windows-edition-geforce-x0001/"><u>Eradicating Glitch: Windows Edition, GeForce X0001</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicating-share-error-in-windows-11/"><u>Eradicating Share Error in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-3d-paint-keyboard-tricks/"><u>Essential 3D Paint Keyboard Tricks</u></a></li>
<li><a href="https://howto.techidaily.com/full-guide-how-to-fix-connection-is-not-private-on-tecno-spark-10c-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Guide How To Fix Connection Is Not Private on Tecno Spark 10C | Dr.fone</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-captivating-yt-cover-art-for-maximum-traffic/"><u>In 2024, Captivating YT Cover Art for Maximum Traffic</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-crafting-immersive-experiences-with-captions-on-stories-and-reels/"><u>In 2024, Crafting Immersive Experiences with Captions on Stories & Reels</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-lenovo-thinkphone-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>In 2024, How to Cast Lenovo ThinkPhone to Computer for iPhone and Android? | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/leveraging-vr-to-shape-modern-business-practices/"><u>Leveraging VR to Shape Modern Business Practices</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-learn-how-everything-works-on-oppo-reno-11-5g-drfone-by-drfone-virtual-android/"><u>Life360 Learn How Everything Works On Oppo Reno 11 5G | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/mastering-igtv-with-a-phone-or-dslr-camera-the-ultimate-guide/"><u>Mastering IGTV with a Phone or DSLR Camera  The Ultimate Guide</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/-unrequested-youtube-video-selections/"><u>Pause Unrequested YouTube Video Selections</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/seamless-visuals-on-screen-zooming-into-clarity/"><u>Seamless Visuals on Screen  Zooming Into Clarity</u></a></li>
<li><a href="https://fake-location.techidaily.com/which-is-the-best-fake-gps-joystick-app-on-motorola-moto-g23-drfone-by-drfone-virtual-android/"><u>Which is the Best Fake GPS Joystick App On Motorola Moto G23? | Dr.fone</u></a></li>
</ul></div>
