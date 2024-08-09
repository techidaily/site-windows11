---
title: Combatting FileSystem Crashes in Win11
date: 2024-08-08T05:56:15.226Z
updated: 2024-08-09T05:56:15.226Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Combatting FileSystem Crashes in Win11
excerpt: This Article Describes Combatting FileSystem Crashes in Win11
keywords: Win11 Stability Fixing,Stop Windows Filesystem Failure,Prevent Win11 System Crashes,Mitigate FileSystem Errors Win11,Enhance Win11 Reliability,Win11 Crash Resilience Strategies,Techniques for Win11 Filesystem Protection
thumbnail: https://thmb.techidaily.com/efc2d305e478474af3e17a5e089941fb3280acaab989de35873f384ab0ed53cb.jpg
---

## Combatting FileSystem Crashes in Win11

 A file system error can occur in Windows 10 and 11 when you try to open files or Microsoft Store apps. When such an error occurs, a message pops up that says, “File system error (code).” File system errors have variable error codes like -2147219195, -2147219196, -2147163893, and -1073741521.

 The causes of such errors vary, but the result is much the same. Users can’t open the files or apps for which file system errors arise. These general resolutions can fix a wide variety of file system errors in Windows 10 and 11.

## 1\. Run the SFC and DISM Command Line Tools

 File system errors can often be related to system file corruption. Windows 11 and 10 have the same SFC and DISM command-line tools for repairing system files and Windows system image. Running those utilities in the Command Prompt could feasibly resolve numerous file system errors.

 Our guide on [how to run the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) tells you how to initiate an SFC scan. You can also run a Deployment Image Servicing Management scan in the Command Prompt before or after running the SFC tool. To do so, you’ll need to execute the following command:

`DISM.exe /Online /Cleanup-image /Restorehealth`

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. Scan Your Hard Drive

 Hard drive integrity issues such as bad sectors also cause file system errors to occur in Windows 11/10\. For that reason, scanning your hard drive with the Check Disk tool is a recommended troubleshooting method for file system errors. The Check Disk utility (otherwise CHKDSK) scans for and repairs bad drive sectors detected. This is how you can run CHKDSK in the Command Prompt:

1. Open the file and app search box by pressing the**Win + S** key combination.
2. Select Command Prompt’s**Run as administrator** option within the search results to launch the app with elevated privileges.
3. Then type this command in the Prompt’s window and press**Enter** :  
`chkdsk c: /f /r`
4. You’ll need to press**Y** to schedule the scan for a restart.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
![The chkdsk command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/chkdsk.jpg)
5. Exit the Command Prompt window.
6. Click**Start > Power** to select**Restart** . The CHKDSK scan will start after the restart.

<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Run the Windows Store App Troubleshooter

 If a file system error occurs when you try launching MS Store apps or opening files with them, the Windows Store App troubleshooter might be useful for fixing it. That troubleshooter is there to resolve issues that stop UWP apps from working as they should. These are the steps for opening the Windows Store App troubleshooter:

1. To access Settings, press the**Windows** logo key +**E** keyboard shortcut that opens that app.
2. Scroll down the tab and click a**Troubleshoot navigation** option.
3. Select**Other trouble-shooters** to bring up a list of tools for troubleshooting Windows.
4. Then press the**Run** button for launching the Windows Store App troubleshooter.  
![The troubleshooter list in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-store-apps-troubleshooter1.jpg)
5. Apply any suggestions the troubleshooter provides.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-store-app-window.jpg)

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
## 4\. Check That the Windows License Manager Service Is Running

 Some file system errors can arise for opening files with UWP apps when the Windows License Manager service is disabled. That’s a service required for MS Store infrastructure support, and apps downloaded from the store don’t always work right when it’s disabled. This is how you can check that service is enabled and start it if necessary:

1. Bring up the Windows search tool and input**Services** inside its text box.
2. Select**Services** within the search results.
3. Double-click**Windows License Manager Service** to access its properties window.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-services-window2.jpg)
4. Click on the**Startup type** menu to open it and select**Automatic** .  
![The Windows License Manager server window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-license-service-manager.jpg)
5. If the service isn’t running, press**Start** within the properties window.
6. Select**Apply** to save settings for the Windows License Manager Service.
7. Click**OK** to close the Windows License Manager Service Properties window.

## 5\. Reinstall Any Affected App

 This potential solution is more applicable to fixing file system errors that occur for opening specific UWP apps. Reinstalling the app for which the error arises might resolve it in such a scenario. For example, users confirmed reinstalling Microsoft Photos can resolve file system error -2147219196.

 You can remove UWP apps with some of the methods in our guide for uninstalling software in Windows 11\. You can uninstall most apps with the Apps & Features tool in Settings. However, you might need to use the PowerShell method in our guide to remove some pre-installed Windows 11 apps.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->
![Apps & features in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/apps-features-window.jpg)

 When you’ve uninstalled the app, reinstall it from the MS Store. Bring up the Microsoft Store, and input the app’s title in its search box. Then select the app to reinstall in the search results, and click the**Get** button for it.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
## 6\. Set Up a New Local User Account on Windows

 File system errors can arise because of user account issues. Such errors might not arise if you set up and utilize a new local user account in Windows 11\. That might not be the most ideal resolution, but you can migrate user files to a newly established account.

 Our guide on [how to fix Windows issues by creating new accounts](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/) includes full instructions for how to apply this solution.

![The Add account button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/add-account-button.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 7\. Restore Windows to an Earlier Date

 System Restore is a troubleshooting tool that can potentially address various causes for file system errors, be it system file corruption, app conflicts, or recent Windows updates. It fixes many things by restoring Windows to an earlier date (system snapshot). However, restoring Windows to an earlier time will only likely work if you can select a restore point that predates the file system error on your PC.

 To apply this potential solution, read through our guide to [utilizing System Restore and creating restore points](https://www.makeuseof.com/windows-11-create-restore-point/) . Select a restoration date that will take your PC back to a time when there wasn’t a system file error on it. The oldest restore point available is the most likely one to do that.

![The System Restore tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/system-restore-window.jpg)

 However, restoring Windows to a previous time removes software not installed on the restoration point’s date. So, it’s likely you’ll have to reinstall some apps after rolling back Windows. Clicking**Scan for affected programs** in System Restore provides an overview of software that will be removed for a restore point.

## 8\. Reset Windows

 This final system file error solution is the most drastic of all since it amounts to reinstalling Windows 10 or 11\. Factory resetting restores Windows to a default system state, which can fix many errors caused by registry, third-party software, and system file issues. If you can’t fix a system file error with any other potential fix in this guide, then resetting is the last thing to try.

 Windows 11 and 10 have a Reset this PC tool that makes it easy to factory reset the platform. That tool also includes an option that enables you to keep user files in the process. Our guide on [how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) includes instructions for applying this potential resolution with this tool.

## Get File System Errors Sorted in Windows

 Users often report file system errors on support forums much the same as BSOD (Blue Screen of Death) and missing DLL file issues. You can't ignore them when they stop you from opening important user files or apps. Whatever file system error you need to fix in Windows 10 and 11, you’ll probably be able to resolve it with at least one of the potential resolutions above.

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
<li><a href="https://youtube-docs.techidaily.com/ecrypting-youtubes-view-count-calculation-system/"><u>[New] Decrypting YouTube’s View-Count Calculation System</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-unlocking-idevice-screen-playback-perfection/"><u>[New] In 2024, Unlocking iDevice Screen Playback Perfection</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-capturing-your-macs-display-live-easy-steps-included/"><u>[Updated] 2024 Approved  Capturing Your Mac's Display Live - Easy Steps Included</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-apple-podcasts-a-quick-download-method/"><u>[Updated] Apple Podcasts  A Quick Download Method</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-harnessing-zooms-potential-with-key-conversion-techniques/"><u>2024 Approved  Harnessing Zoom's Potential with Key Conversion Techniques</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-top-places-for-discovering-premium-soundtracks-from-instagram-and-designing-exceptional-ringtone-alerts/"><u>2024 Approved  Top Places for Discovering Premium Soundtracks From Instagram & Designing Exceptional Ringtone Alerts</u></a></li>
<li><a href="https://fox-helps.techidaily.com/champion-complimentary-timer-tech-for-2024/"><u>Champion Complimentary Timer Tech for 2024</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/daily-narratives-of-a-korean-week/"><u>Daily Narratives of a Korean Week</u></a></li>
<li><a href="https://windows11.techidaily.com/drive-letter-dilemma-in-windows-understanding-the-issues-fixes-presented/"><u>Drive Letter Dilemma in Windows - Understanding The Issues, Fixes Presented</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-steps-to-activatedeactivate-secure-boot-and-tpm-in-virtualbox/"><u>Easy Steps to Activate/Deactivate Secure Boot & TPM in VirtualBox</u></a></li>
<li><a href="https://activate-lock.techidaily.com/easy-tutorial-for-activating-icloud-from-apple-iphone-14-plus-safe-and-legal-by-drfone-ios/"><u>Easy Tutorial for Activating iCloud from Apple iPhone 14 Plus Safe and Legal</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-methods-to-cut-edges-background-activity/"><u>Effective Methods to Cut Edge's Background Activity</u></a></li>
<li><a href="https://windows11.techidaily.com/effortlessly-syncing-files-in-windows-1011/"><u>Effortlessly Syncing Files in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-workflow-choosing-the-best-6-to-do-list-apps-on-windows-11/"><u>Elevate Your Workflow: Choosing the Best 6 To-Do List Apps on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-gaming-experience-fixing-valorant-lags/"><u>Elevating Gaming Experience: Fixing Valorant Lags</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-virtual-battles-why-windows-reigns-supreme/"><u>Elevating Virtual Battles: Why Windows Reigns Supreme</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-your-touch-sensitivity-experience-on-a-windows-laptop/"><u>Elevating Your Touch Sensitivity Experience on a Windows Laptop</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminate-chrome-aw-snap-glitch-on-windows/"><u>Eliminate Chrome “Aw, Snap!” Glitch on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminate-cursor-blanking-on-win11-instantly/"><u>Eliminate Cursor Blanking on Win11 Instantly</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-microsoft-shop-errors-0x80131500/"><u>Eliminating Microsoft Shop Errors #0X80131500</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-non-functional-behavior-of-ccleaner-in-windows/"><u>Eliminating Non-Functional Behavior of CCleaner in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-steam-hurdles-to-play-your-favorite-game-on-win-11/"><u>Eliminating Steam Hurdles to Play Your Favorite Game on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/empowered-scripting-in-windows-mastering-execution-policies/"><u>Empowered Scripting in Windows: Mastering Execution Policies</u></a></li>
<li><a href="https://windows11.techidaily.com/enablingdisabling-windows-software-configuration-service/"><u>Enabling/Disabling Windows Software Configuration Service</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-creativity-ranking-the-best-drawers-for-win-11/"><u>Enhance Creativity: Ranking the Best Drawers for Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-taskbar-clarity-separate-groups-on-win-11/"><u>Enhance Taskbar Clarity: Separate Groups on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-efficiency-microsoft-adds-artificial-intelligence-to-windows-11-taskbar/"><u>Enhancing Efficiency: Microsoft Adds Artificial Intelligence to Windows 11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-note-visibility-with-windows-tools/"><u>Enhancing Note Visibility with Windows Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-performance-with-virtual-memory-on-windows-11/"><u>Enhancing Performance with Virtual Memory on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-user-experience-with-automatic-updates-toolbar-in-windows-11plus11/"><u>Enhancing User Experience with Automatic Updates Toolbar in Windows 11+11</u></a></li>
<li><a href="https://youtube-web.techidaily.com/cing-video-appeal-mac-thumbnails-tutorial/"><u>Enhancing Video Appeal  Mac Thumbnails Tutorial</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-wi-fi-setup-accuracy-ensuring-complete-actions/"><u>Enhancing Wi-Fi Setup Accuracy: Ensuring Complete Actions</u></a></li>
<li><a href="https://windows11.techidaily.com/entering-quake-modes-through-windows-terminal/"><u>Entering Quake Modes Through Windows Terminal</u></a></li>
<li><a href="https://windows11.techidaily.com/epic-launcher-insights-best-practices-for-saving-your-playtime/"><u>Epic Launcher Insights: Best Practices for Saving Your Playtime</u></a></li>
<li><a href="https://windows11.techidaily.com/escalate-emulation-faster-yuzu-win-users/"><u>Escalate Emulation: Faster Yuzu, WIN Users</u></a></li>
<li><a href="https://screen-capture.techidaily.com/from-first-steps-to-expertise-lenovos-guide-to-recording-success/"><u>From First Steps to Expertise  Lenovo’s Guide to Recording Success</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-frp-from-vivo-x100-pro-by-drfone-android/"><u>How to Bypass FRP from Vivo X100 Pro?</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-fake-snapchat-location-without-jailbreak-on-itel-a60-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location without Jailbreak On Itel A60 | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-explore-high-quality-android-videos-top-10-apps/"><u>In 2024, Explore High-Quality Android Videos  Top 10 Apps</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-revolutionizing-video-views-conquering-youtube-millions/"><u>In 2024, Revolutionizing Video Views, Conquering YouTube Millions</u></a></li>
<li><a href="https://fix-guide.techidaily.com/itel-p55-5g-screen-unresponsive-heres-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Itel P55 5G Screen Unresponsive? Heres How to Fix It | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/learn-everything-about-3d-lut-creator-and-mobile-app-for-2024/"><u>Learn Everything About 3D LUT Creator & Mobile App for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/live-stream-archive-a-users-blueprint-to-downloadability/"><u>Live Stream Archive  A User's Blueprint to Downloadability</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-s-best-stop-motion-animation-programs-for-creatives/"><u>New 2024 Approved S Best Stop Motion Animation Programs for Creatives</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ame-changer-creating-eye-catching-logo-templates-for-2024/"><u>The Game-Changer  Creating Eye-Catching Logo Templates for 2024</u></a></li>
</ul></div>
