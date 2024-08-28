---
title: "Tackling Disk Errors on Windows 10/11: A Step-by-Step Guide"
date: 2024-08-27T16:12:15.637Z
updated: 2024-08-28T16:12:15.637Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Tackling Disk Errors on Windows 10/11: A Step-by-Step Guide"
excerpt: "This Article Describes Tackling Disk Errors on Windows 10/11: A Step-by-Step Guide"
keywords: Win Disk Repair,Fixing Disk Errors,10/11 Disk Troubleshooting,Windows Disk Fix Steps,Stop Disk Issues,Clearing Disk Errors,Disk Correction Guide
thumbnail: https://thmb.techidaily.com/e475d95ff83684e67af3ed3b0fb046f03e477b4f885c10acf9d70c8e5fd03d37.jpg
---

## Tackling Disk Errors on Windows 10/11: A Step-by-Step Guide

 A file system error can occur in Windows 10 and 11 when you try to open files or Microsoft Store apps. When such an error occurs, a message pops up that says, “File system error (code).” File system errors have variable error codes like -2147219195, -2147219196, -2147163893, and -1073741521.

 The causes of such errors vary, but the result is much the same. Users can’t open the files or apps for which file system errors arise. These general resolutions can fix a wide variety of file system errors in Windows 10 and 11.

## 1\. Run the SFC and DISM Command Line Tools

 File system errors can often be related to system file corruption. Windows 11 and 10 have the same SFC and DISM command-line tools for repairing system files and Windows system image. Running those utilities in the Command Prompt could feasibly resolve numerous file system errors.

 Our guide on[how to run the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) tells you how to initiate an SFC scan. You can also run a Deployment Image Servicing Management scan in the Command Prompt before or after running the SFC tool. To do so, you’ll need to execute the following command:

`DISM.exe /Online /Cleanup-image /Restorehealth`

## 2\. Scan Your Hard Drive

 Hard drive integrity issues such as bad sectors also cause file system errors to occur in Windows 11/10\. For that reason, scanning your hard drive with the Check Disk tool is a recommended troubleshooting method for file system errors. The Check Disk utility (otherwise CHKDSK) scans for and repairs bad drive sectors detected. This is how you can run CHKDSK in the Command Prompt:

1. Open the file and app search box by pressing the**Win + S** key combination.
2. Select Command Prompt’s**Run as administrator** option within the search results to launch the app with elevated privileges.
3. Then type this command in the Prompt’s window and press**Enter** :  
`chkdsk c: /f /r`
4. You’ll need to press**Y** to schedule the scan for a restart.  
![The chkdsk command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/chkdsk.jpg)
5. Exit the Command Prompt window.
6. Click**Start > Power** to select**Restart** . The CHKDSK scan will start after the restart.

## 3\. Run the Windows Store App Troubleshooter

 If a file system error occurs when you try launching MS Store apps or opening files with them, the Windows Store App troubleshooter might be useful for fixing it. That troubleshooter is there to resolve issues that stop UWP apps from working as they should. These are the steps for opening the Windows Store App troubleshooter:

1. To access Settings, press the**Windows** logo key +**E** keyboard shortcut that opens that app.
2. Scroll down the tab and click a**Troubleshoot navigation** option.
3. Select**Other trouble-shooters** to bring up a list of tools for troubleshooting Windows.
4. Then press the**Run** button for launching the Windows Store App troubleshooter.  
![The troubleshooter list in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-store-apps-troubleshooter1.jpg)
5. Apply any suggestions the troubleshooter provides.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
![The Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-store-app-window.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 4\. Check That the Windows License Manager Service Is Running

 Some file system errors can arise for opening files with UWP apps when the Windows License Manager service is disabled. That’s a service required for MS Store infrastructure support, and apps downloaded from the store don’t always work right when it’s disabled. This is how you can check that service is enabled and start it if necessary:

1. Bring up the Windows search tool and input**Services** inside its text box.
2. Select**Services** within the search results.
3. Double-click**Windows License Manager Service** to access its properties window.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-services-window2.jpg)
4. Click on the**Startup type** menu to open it and select**Automatic** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![The Windows License Manager server window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-license-service-manager.jpg)
5. If the service isn’t running, press**Start** within the properties window.
6. Select**Apply** to save settings for the Windows License Manager Service.
7. Click**OK** to close the Windows License Manager Service Properties window.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
## 5\. Reinstall Any Affected App

 This potential solution is more applicable to fixing file system errors that occur for opening specific UWP apps. Reinstalling the app for which the error arises might resolve it in such a scenario. For example, users confirmed reinstalling Microsoft Photos can resolve file system error -2147219196.

 You can remove UWP apps with some of the methods in our guide for uninstalling software in Windows 11\. You can uninstall most apps with the Apps & Features tool in Settings. However, you might need to use the PowerShell method in our guide to remove some pre-installed Windows 11 apps.

![Apps & features in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/apps-features-window.jpg)

 When you’ve uninstalled the app, reinstall it from the MS Store. Bring up the Microsoft Store, and input the app’s title in its search box. Then select the app to reinstall in the search results, and click the**Get** button for it.

## 6\. Set Up a New Local User Account on Windows

 File system errors can arise because of user account issues. Such errors might not arise if you set up and utilize a new local user account in Windows 11\. That might not be the most ideal resolution, but you can migrate user files to a newly established account.

 Our guide on[how to fix Windows issues by creating new accounts](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/) includes full instructions for how to apply this solution.

![The Add account button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/add-account-button.jpg)

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
## 7\. Restore Windows to an Earlier Date

 System Restore is a troubleshooting tool that can potentially address various causes for file system errors, be it system file corruption, app conflicts, or recent Windows updates. It fixes many things by restoring Windows to an earlier date (system snapshot). However, restoring Windows to an earlier time will only likely work if you can select a restore point that predates the file system error on your PC.

 To apply this potential solution, read through our guide to[utilizing System Restore and creating restore points](https://www.makeuseof.com/windows-11-create-restore-point/) . Select a restoration date that will take your PC back to a time when there wasn’t a system file error on it. The oldest restore point available is the most likely one to do that.

![The System Restore tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/system-restore-window.jpg)

 However, restoring Windows to a previous time removes software not installed on the restoration point’s date. So, it’s likely you’ll have to reinstall some apps after rolling back Windows. Clicking**Scan for affected programs** in System Restore provides an overview of software that will be removed for a restore point.

## 8\. Reset Windows

 This final system file error solution is the most drastic of all since it amounts to reinstalling Windows 10 or 11\. Factory resetting restores Windows to a default system state, which can fix many errors caused by registry, third-party software, and system file issues. If you can’t fix a system file error with any other potential fix in this guide, then resetting is the last thing to try.

 Windows 11 and 10 have a Reset this PC tool that makes it easy to factory reset the platform. That tool also includes an option that enables you to keep user files in the process. Our guide on[how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) includes instructions for applying this potential resolution with this tool.

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->
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
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-master-blending-techniques-for-clips-harmony/"><u>[New] 2024 Approved  Master Blending Techniques for Clips Harmony</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-the-video-editor-face-off-making-an-informed-decision-filmora-vs-democracy-creator/"><u>[New] 2024 Approved  The Video Editor Face-Off  Making an Informed Decision (Filmora Vs. Democracy Creator)</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-chart-success-using-youtube-statistics-to-grow-engagement-for-2024/"><u>[Updated] Chart Success  Using YouTube Statistics to Grow Engagement for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-comprehensive-insight-into-high-end-hdr-cameras/"><u>[Updated] Comprehensive Insight Into High-End HDR Cameras</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-google-meet-live-streaming-for-beginners-stepwise-guide-to-youtube-for-2024/"><u>[Updated] Google Meet Live-Streaming for Beginners  Stepwise Guide to YouTube for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-crafting-a-legacy-youtubers-playbook-for-success/"><u>[Updated] In 2024, Crafting a Legacy  YouTuber’s Playbook for Success</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-uncover-the-secret-correcting-mobile-video-sharing-on-fb-messenger/"><u>[Updated] In 2024, Uncover the Secret  Correcting Mobile Video Sharing on FB Messenger</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-director-of-dishes-behind-the-scenes-of-food-filming/"><u>[Updated] The Director of Dishes  Behind-the-Scenes of Food Filming</u></a></li>
<li><a href="https://driver-install.techidaily.com/correct-windows-10-printer-connectivity-errors/"><u>Correct Windows 10 Printer Connectivity Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-strategies-to-correct-steam-login-pause-in-rust-os/"><u>Essential Strategies to Correct Steam Login Pause in Rust OS</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-microsoft-store-blockage-on-windows-11/"><u>Fixing Microsoft Store Blockage on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-implementing-rgb-in-windows-11/"><u>Guide to Implementing RGB in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-turning-msi-on-or-off-through-group-policy/"><u>Guide to Turning MSI On or Off Through Group Policy</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-resolve-error-x80780119-in-windows-image-id/"><u>How To Resolve Error X80780119 in Windows Image ID</u></a></li>
<li><a href="https://windows11.techidaily.com/identifying-your-cpus-gen-in-windows-top-8-techniques/"><u>Identifying Your CPU's Gen in Windows: Top 8 Techniques</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-datasafe-experts-assessment/"><u>In 2024, DataSafe Experts Assessment</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-fix-auto-lock-greyed-out-on-apple-iphone-x-by-drfone-ios/"><u>In 2024, How To Fix Auto Lock Greyed Out on Apple iPhone X</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-nokia-c32-phone-without-any-data-loss-by-drfone-android/"><u>In 2024, How to Unlock Nokia C32 Phone without Any Data Loss</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-navigating-the-needle-speed-of-videos-in-snapchat/"><u>In 2024, Navigating the Needle-Speed of Videos in Snapchat</u></a></li>
<li><a href="https://buynow-info.techidaily.com/invest-in-petcubes-budget-friendly-hd-pet-monitor/"><u>Invest in Petcube's Budget-Friendly HD Pet Monitor</u></a></li>
<li><a href="https://windows11.techidaily.com/jump-starting-windows-setup-with-nine-troubleshooting-steps/"><u>Jump-Starting Windows Setup with Nine Troubleshooting Steps</u></a></li>
<li><a href="https://win-blog.techidaily.com/left-4-dead-2-game-crashes-diagnosed-and-fixed-comprehensive-solutions-provided/"><u>Left 4 Dead 2 Game Crashes - Diagnosed & Fixed: Comprehensive Solutions Provided</u></a></li>
<li><a href="https://windows11.techidaily.com/leverage-ifttt-to-optimize-to-do-usage/"><u>Leverage IFTTT to Optimize To-Do Usage</u></a></li>
<li><a href="https://extra-hints.techidaily.com/lighten-up-your-digital-presence-kapwing-maker/"><u>Lighten Up Your Digital Presence - Kapwing Maker</u></a></li>
<li><a href="https://windows11.techidaily.com/master-snippet-pasting-windows-shortcuts-for-speed/"><u>Master Snippet Pasting: Windows Shortcuts for Speed</u></a></li>
<li><a href="https://windows11.techidaily.com/masterful-icloud-setup-tips-for-windows-os/"><u>Masterful iCloud Setup Tips for Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-for-rectifying-windows-11-search-box-malfunctions/"><u>Methods for Rectifying Windows 11 Search Box Malfunctions</u></a></li>
<li><a href="https://windows11.techidaily.com/microsoft-woes-solutions-to-ease-your-way/"><u>Microsoft Woes? Solutions to Ease Your Way!</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-network-stability-in-windows-1011/"><u>Navigating Network Stability in Windows 10/11</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-in-2024-mastering-the-art-of-deleting-percussive-sounds-from-audio-tracks/"><u>New In 2024, Mastering the Art of Deleting Percussive Sounds From Audio Tracks</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-command-line-interface-use-set-as-primary-app/"><u>Optimize Command Line Interface Use: Set As Primary App</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-common-rpc-fails-on-windows-platform/"><u>Overcoming Common RPC Fails on Windows Platform</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-color-calibration-challenges/"><u>Overcoming Windows Color Calibration Challenges</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-tips-for-changing-your-windows-11-login-password/"><u>Quick Tips for Changing Your Windows 11 Login Password</u></a></li>
<li><a href="https://windows11.techidaily.com/reignite-non-operational-usb-connections-microsoft-os/"><u>Reignite Non-Operational USB Connections, Microsoft OS</u></a></li>
<li><a href="https://windows11.techidaily.com/removing-automatic-system-restarts-in-windows-11/"><u>Removing Automatic System Restarts in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-the-0x80004005-problem-in-windows-virtualbox/"><u>Resolving the 0X80004005 Problem in Windows Virtualbox</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-11s-filesystem-anomalies/"><u>Resolving Windows 11'S Filesystem Anomalies</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-graphics-connectivity-dxgi-fix-methods/"><u>Restoring Graphics Connectivity: DXGI Fix Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/revealing-resolution-riddles-making-windows-monitor-work/"><u>Revealing Resolution Riddles: Making Windows Monitor Work</u></a></li>
<li><a href="https://windows11.techidaily.com/savor-ultimate-digital-windows-world/"><u>Savor Ultimate Digital Windows World</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-and-streamlining-user-and-group-management-on-win1110-home/"><u>Securing & Streamlining User and Group Management on WIN11/10 Home</u></a></li>
<li><a href="https://windows11.techidaily.com/snooze-steadfast-windows-use-keyboard-and-mouse-to-wake-up/"><u>Snooze Steadfast Windows? Use Keyboard & Mouse to Wake Up</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-correcting-windows-xps-c0000005-error/"><u>Steps to Correcting Windows XP's C0000005 Error</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-counteract-unwritable-files-error-in-windows-11/"><u>Steps to Counteract Unwritable Files Error in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-and-simplifying-docker-operations-on-windows/"><u>Streamlining and Simplifying Docker Operations on Windows</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/streamlining-video-uploads-tips-for-transforming-h-vids-for-igtv/"><u>Streamlining Video Uploads  Tips for Transforming H-Vids for IGTV</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/subtitle-strategies-for-multilingual-instagram-videos-for-2024/"><u>Subtitle Strategies for Multilingual Instagram Videos for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/swiftly-delve-into-windows-system-statistics/"><u>Swiftly Delve Into Windows System Statistics</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-stopping-unwanted-terminal-surface/"><u>Techniques for Stopping Unwanted Terminal Surface</u></a></li>
<li><a href="https://extra-resources.techidaily.com/the-quick-and-the-funny-with-kinemaster-memes/"><u>The Quick and the Funny with KineMaster Memes</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-to-regain-access-to-mb-services-on-win11-systems/"><u>Tips to Regain Access to MB Services on Win11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/top-8-microsoft-syncs-for-android-from-a-windows-pc/"><u>Top 8 Microsoft Syncs for Android From a Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-roblox-code-403-problem/"><u>Troubleshooting Windows Roblox Code 403 Problem</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-full-potential-of-emojis-in-windows-11/"><u>Unleash Full Potential of Emojis in Windows 11</u></a></li>
<li><a href="https://techidaily.com/unlock-iphone-14-pro-lock-with-itunes-by-drfone-ios-unlock-ios-unlock/"><u>Unlock iPhone 14 Pro lock with iTunes</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-secrets-of-your-system-quick-guide-for-model-names/"><u>Unlock the Secrets of Your System: Quick Guide for Model Names</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-4-secrets-how-to-delete-a-disks-division-in-windows/"><u>Unveiling 4 Secrets: How to Delete a Disk's Division in Windows</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/where-is-the-best-place-to-catch-dratini-on-apple-iphone-11-drfone-by-drfone-virtual-ios/"><u>Where Is the Best Place to Catch Dratini On Apple iPhone 11 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-driver-upgrade-modernizing-audio-compatibility/"><u>Windows Driver Upgrade: Modernizing Audio Compatibility</u></a></li>
<li><a href="https://windows11.techidaily.com/xbox-app-setup-steps-for-seamless-windows-players/"><u>Xbox App Setup: Steps for Seamless Windows Players</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/youtube-earning-blueprint-achieving-bank-balances/"><u>YouTube Earning Blueprint  Achieving Bank Balances</u></a></li>
</ul></div>
