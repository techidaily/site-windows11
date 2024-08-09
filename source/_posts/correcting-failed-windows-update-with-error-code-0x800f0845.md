---
title: Correcting Failed Windows Update with Error Code 0X800f0845
date: 2024-08-08T05:56:37.654Z
updated: 2024-08-09T05:56:37.654Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting Failed Windows Update with Error Code 0X800f0845
excerpt: This Article Describes Correcting Failed Windows Update with Error Code 0X800f0845
keywords: Windows Update Fix Code 0X800F,Errorexcode800F Windows Repair,Error 0X800F Update Correction,Fix Windows Update Error 0X800F,Resolve 0X800F Update Failure,XP800F Update Fix Strategies,Eliminating Error Code 0X800F
thumbnail: https://thmb.techidaily.com/5b8a360ae2beb8ae28dded746595b2ec0252b7304ad9ab12b451e3ff69d2619e.jpg
---

## Correcting Failed Windows Update with Error Code 0X800f0845

 Windows Update brings new features to your PC while installing important security updates and bug fixes. So it's vital to keep your system updated to work and play hassle-free on Windows.

 However, some unexpected errors occur, resulting in updates failing to install on your system. And 0x800f0845 is one such error.

 But you can get past the 0x800f0845 error and continue to install essential updates by trying the following fixes.

## What Is the Windows Update 0x800f0845 Error?

 0x800f0845 is an error that mostly occurs while installing cumulative updates on your Windows PC. You may experience this update error if Windows components and services are corrupted or if there are damaged or missing system files. Sometimes, this error happens by the interactions of third-party apps with the system apps.

 You may not come to know of the error while updating, as Windows will appear to be updating normally with messages of the updates installing—such as**Updates are underway. Please keep your computer on** .

 However, just before your PC reboots, the following message on your computer screen may appear: **Something didn't go as planned. No need to worry—undoing changes. Please keep your computer on** . This message indicates a problem with the update. When your computer restarts, the cumulative update would have failed to install.

 You can check for the same by going to**Settings > Windows Update** and then clicking**Update history** . In**Update history** , you will get the message that the cumulative update has failed to install with the error code**0x800f0845** like the screenshot below.

![0x800f0845 Error in Windows Update History](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/0x800f0845-error-update-history.jpg)

 So what can you do now? Cumulative updates are quality updates, so these must be installed. Fortunately, as there are ways to get past the 0x800f0845 error and install the failed updates.

## 1\. Run the Windows Update Troubleshooter

 It's always better to try fixing Windows update errors first by using the Windows Update Troubleshooter. It scans your PC for problems, attempts to resolve them, and then applies the fixes.

1. Right-click the**Windows icon** on the taskbar and select**Settings** . Or use the [many ways to open Settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. On the left pane in**Settings** , click**System** . On the**System** page, click**Troubleshoot** on the right pane.
3. In the**Troubleshoot** page, select**Other troubleshooters** .  
![Select Other Trouble-shooters in Troubleshoot Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/troubleshoot-other-trouble-shooters.jpg)
4. Then click**Run** on the**Windows Update** troubleshooter.  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Run Windows Update Troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-windows-update-troubleshooter.jpg)

 The Windows Update troubleshooter will automatically run its scans to diagnose problems. After troubleshooting completes, you'll get the message that changes have been made to your system and you should try attempting the tasks you were doing earlier.

![Windows Update Troubleshooting Complete Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-update-troubleshooting-complete.jpg)

 So close the troubleshooter and restart your computer. Then try updating Windows again and check if the failed update gets installed.

## 2\. Temporarily Disable Your Antivirus Software

 Sometimes, third-party antivirus installed on your PC may cause problems when you're updating Windows. So try temporarily disabling it and then installing updates.

 Your antivirus may have options to disable it temporarily. Or right-click on the Windows icon on the taskbar and select**Task Manager** .

 In**Task Manager** , click the**Startup** tab and look for your antivirus software. Then, right-click on it and choose**Disable** .

Try updating Windows now and see if the update gets installed.

## 3\. Run the System File Checker and the DISM Tool

 Corrupted Windows system files could also be the cause of the 0x800f0845 error. To scan, repair, and replace such damaged files, run the System File Checker or SFC scan.

 And if the SFC doesn't work properly, and can’t repair your system files, you should run the DISM or Deployment Image Servicing and Management tool. DISM is a command-line tool that can be used to service and repair Windows images, including those used for Windows Recovery and Windows Setup.

 To know how to run the SFC and DSIM, you can explore our guide on [CHKSDK, SFC, and DISM, and how they work](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) .

 These scans will take a few minutes to run. If the 0x800f0845 error was caused by corrupted files, it should have been fixed. So try updating Windows again.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Reset Windows Update Components

 Error 0x800f0845 could occur if some Windows Update components have got corrupted. You could reset Windows components to get the Windows update running fine again. Here's how:

[Open Windows Terminal](https://www.makeuseof.com/windows-11-open-windows-terminal/) using one of the many ways. Or type**Windows Terminal** in**Windows Search** . Then, right-click**Windows Terminal** under**Best match** and select**Run as administrator.**

 First, you need to stop the update services. In the Windows Terminal window, type the following four commands one by one, making sure that you press**enter** after each command:

`net stop bits  
net stop wuauserv  
net stop appidsvc  
net stop cryptsvc`

 Then to set up a new SoftwareDistribution folder, you need to rename it. So enter the following command and press**enter** :

`Ren %systemroot%\SoftwareDistribution SoftwareDistribution.old`

 Next, rename the catroot2 folder for Windows to set up a new one. Type the following command and press**enter** :

`Ren %systemroot%\System32\catroot2 catroot2.old`

 Finally, you need to restart the stopped services. Type the following four commands one after the other, while pressing**enter** after each command:

`net start bits  
net start wuauserv  
net start appidsvc  
net start cryptsvc`

 Once you have run all the commands, the update error should have got fixed. Restart your PC and try installing the updates again.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
## 5\. Install the Update Manually via the Microsoft Update Catalog

 What if none of the above solutions works for you? No worries, just install the update manually from the Microsoft Update Catalog.

1. Open your browser to search for and visit the [Microsoft Update Catalog website](https://www.catalog.update.microsoft.com/Home.aspx) .
2. Copy the number of the cumulative update or any other update that failed to install from the**Windows Update history** page. Type the update number in the**Search bar** on the**Microsoft Update Catalog** page and hit the**Search** button.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
<!-- affiliate ads end -->
![Search For Update On Microsoft Update Catalog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/search-on-microsoft-update-catalog.jpg)
3. The matching updates will show up on the results page. Check the update that applies to your Windows PC—whether it is for Windows 10 or 11, and whether it is for an ARM64-based system or an x64-based system.  
![Microsoft Update Catalog Search Results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/microsoft-update-catalog-search-results.jpg)
4. To know the build of your PC, search for**About** in**Windows Search** and click on**About your PC** under**Best match** . In the**About** page, under**Device specifications** , check your**System type** to know whether it is x64-based or another.  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
<!-- affiliate ads end -->
![Device Specifications in About Your PC Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/screenshot-10065.jpg)  
 Select the update that matches your system in Microsoft Update Catalog and click the**Download** button.
5. The**Download** page will open with the file download link. Click on the link to download the update.  
<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Download Update From Microsoft Update Catalog Link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/download-update-from-link.jpg)
6. Double-click on the downloaded file to open the**Windows Update Standalone Installer** and click**Yes** when prompted to download the update.  
![Windows Update Standalone Installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-update-standalone-installer.jpg)  
 The update will begin installing and this could take some time.  
![Cumulative Update Installation in Progress](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/cumulative-update-installing-progress.jpg)  
 Finally, the**Installation complete** window will appear.  
<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
![Click Restart Now to Complete Installation](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/restart-now-to-complete-installation.jpg)
7. Just click the**Restart Now** button to complete the installation.
8. After your PC restarts, go to the**Windows Update history** page.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->
![Cumulative Update Successfully Installed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/cumulative-update-successfully-installed.jpg)  
 The update that failed to install would have been successfully installed—as you can see in the screenshot above, the KB5023706 update was installed.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->
## Stay Updated for a Secure and Smooth Windows Experience

 Update errors like 0x800fo845 can be annoying, especially when you've spent considerable time on an update that fails to install. Try the fixes discussed above to install important updates and enjoy a smooth, secure, and hassle-free Windows experience.


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
<li><a href="https://instagram-video-files.techidaily.com/new-demystifying-instagram-selfies-a-comprehensive-guide/"><u>[New] Demystifying Instagram Selfies  A Comprehensive Guide</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-in-2024-samsung-gear-360-vs-lg-360-cam-which-360-degree-camera-is-better/"><u>[New] In 2024, Samsung Gear 360 vs LG 360 Cam  Which 360 Degree Camera Is Better</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-uncovering-superior-free-viewers-for-your-webm-media-files/"><u>[New] Uncovering Superior, Free Viewers for Your WebM Media Files</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-premier-short-frame-gatherer-top-lapses/"><u>[Updated] 2024 Approved  Premier Short Frame Gatherer - Top Lapses</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-capture-clearness-without-a-tripod-tool/"><u>[Updated] In 2024, Capture Clearness Without a Tripod Tool</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unleash-creativity-with-the-best-online-screen-changers/"><u>[Updated] Unleash Creativity with the Best Online Screen Changers</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-scripted-synergy-systems/"><u>2024 Approved  Scripted Synergy Systems</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-securing-youtube-srt-files-a-threefold-procedure/"><u>2024 Approved  Securing YouTube SRT Files  A Threefold Procedure</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-supercharge-your-social-media-scrapping-the-best-5-chrome-plugins/"><u>2024 Approved  Supercharge Your Social Media Scrapping  The Best 5 Chrome Plugins</u></a></li>
<li><a href="https://windows11.techidaily.com/4-ways-to-check-your-network-adapter-speed-on-windows/"><u>4 Ways to Check Your Network Adapter Speed on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/6-fixes-for-windows-gone-dark-and-unresponsive/"><u>6 Fixes for Windows Gone Dark and Unresponsive</u></a></li>
<li><a href="https://windows11.techidaily.com/a-detailed-guide-turning-off-windows-update-restrictions/"><u>A Detailed Guide: Turning Off Windows Update Restrictions</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/a-guide-to-gathering-gold-from-guided-goods-gazes-online/"><u>A Guide to Gathering Gold From Guided Goods' Gazes Online</u></a></li>
<li><a href="https://windows11.techidaily.com/a-short-tale-on-wintoys-unveiling-a-compelling-windows-application/"><u>A Short Tale on 'WinToys': Unveiling a Compelling Windows Application</u></a></li>
<li><a href="https://windows11.techidaily.com/adding-comprehensive-firewall-tools-to-windows-11s-menu-bar/"><u>Adding Comprehensive Firewall Tools to Windows 11’S Menu Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-security-automating-passwords-in-windows-texts/"><u>Advanced Security: Automating Passwords in Windows Texts</u></a></li>
<li><a href="https://windows11.techidaily.com/archiving-acumen-covertly-concealing-zip-in-photos-win11/"><u>Archiving Acumen: Covertly Concealing ZIP in Photos (Win11)</u></a></li>
<li><a href="https://windows11.techidaily.com/avoidance-of-memory-limitations-strategies-for-windows/"><u>Avoidance of Memory Limitations: Strategies for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/awaken-slumbering-screens-remedy-key-mouse-woes-on-windows/"><u>Awaken Slumbering Screens: Remedy Key, Mouse Woes on Windows</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/behind-the-lens-nikon-d500s-4k-innovation/"><u>Behind the Lens  Nikon D500's 4K Innovation</u></a></li>
<li><a href="https://windows11.techidaily.com/blue-screen-decoded-understanding-and-fixing-0x0000003b-in-win-os/"><u>Blue Screen Decoded: Understanding and Fixing 0X0000003B in Win OS</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/can-i-bypass-a-forgotten-phone-password-of-poco-by-drfone-android/"><u>Can I Bypass a Forgotten Phone Password Of Poco?</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-windows-11s-directive-non-empty-problem-0x80070091/"><u>Clearing Up Windows 11'S Directive Non-Empty Problem #0X80070091</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-common-downloads-dilemmas-on-windows-pcs/"><u>Combatting Common Downloads Dilemmas on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/command-center-for-direct-access-to-windows-11s-appsfolders/"><u>Command Center for Direct Access to Windows 11'S AppsFolders</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-compatibility-issues-windows-troubleshooting-blueprint/"><u>Conquer Compatibility Issues: Windows Troubleshooting Blueprint</u></a></li>
<li><a href="https://windows11.techidaily.com/control-windows-11s-emphasis-and-search-highlight/"><u>Control Windows 11'S Emphasis and Search Highlight</u></a></li>
<li><a href="https://windows11.techidaily.com/cool-off-cycles-in-the-world-of-computers/"><u>Cool-Off Cycles in the World of Computers</u></a></li>
<li><a href="https://windows11.techidaily.com/countering-compromised-windows-defender-on-win-11/"><u>Countering Compromised Windows Defender on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-unique-room-backgrounds-with-windows-spotlight-pics/"><u>Crafting Unique Room Backgrounds with Windows Spotlight Pics</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-pc-audio-with-windows-11s-volume-mixer-tutorial/"><u>Customize PC Audio with Windows 11'S Volume Mixer Tutorial</u></a></li>
<li><a href="https://windows11.techidaily.com/decode-and-resolve-uninitialized-disk-message-on-pc/"><u>Decode and Resolve Uninitialized Disk Message on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-bsod-0x0000003b-and-resolution-steps-in-windows-os/"><u>Decoding BSOD -0X0000003B & Resolution Steps in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/diagnosing-and-repairing-dormant-window-control/"><u>Diagnosing and Repairing Dormant Window Control</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-fatal-component-error-in-win10win11-system/"><u>Disabling Fatal Component Error in Win10/Win11 System</u></a></li>
<li><a href="https://windows11.techidaily.com/1719271997711-enable-high-contrast-mode-go-to-ease-of-access-settings-and-enable-high-contrast-mode-if-it-improves-visibility/"><u>Enable High Contrast Mode: Go to 'Ease of Access' Settings and Enable High Contrast Mode if It Improves Visibility.</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ssing-the-power-of-asynchronous-programming-in-javascript-for-2024/"><u>Harnessing the Power of Asynchronous Programming in JavaScript for 2024</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-easy-guide-to-oppo-reno-11-pro-5g-frp-bypass-with-best-methods-by-drfone-android/"><u>In 2024, Easy Guide to Oppo Reno 11 Pro 5G FRP Bypass With Best Methods</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-from-samsung-galaxy-s23plus-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock from Samsung Galaxy S23+ Phones with/without a PC</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-synching-release-timings-to-audience-trends/"><u>In 2024, Synching Release Timings to Audience Trends</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/in-2024-video-marketing-mastery-for-youtube-success/"><u>In 2024, Video Marketing Mastery for YouTube Success</u></a></li>
<li><a href="https://printer-issues.techidaily.com/simplifying-canon-printer-wireless-connection/"><u>Simplifying Canon Printer Wireless Connection</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/snagting-smiles-on-iphones-and-androids-from-twitters-timeline-for-2024/"><u>Snagting Smiles on iPhones & Androids From Twitter's Timeline for 2024</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-vivo-y100-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Vivo Y100 Reset Code | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unveiling-the-reasons-behind-chatgpts-inability-to-identify-its-generated-texts/"><u>Unveiling the Reasons Behind ChatGPT's Inability to Identify Its Generated Texts</u></a></li>
</ul></div>
