---
title: Dealing with FileHistoryFaults in Windows OS
date: 2024-08-08T06:00:34.312Z
updated: 2024-08-09T06:00:34.312Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Dealing with FileHistoryFaults in Windows OS
excerpt: This Article Describes Dealing with FileHistoryFaults in Windows OS
keywords: WinOSFileHistoryIssues,Fixing FileHistoryErrors,Windows FileHistoryTroubleshoot,Resolve WinOSBackupFaults,Correcting Windows SaveError,Addressing OS BackupFailure,Repairing FileHistoryWindows
thumbnail: https://thmb.techidaily.com/a362218194355c666b0860326aa79761dfe27d2518f12f424f4610cd1ffe517b.jpg
---

## Dealing with FileHistoryFaults in Windows OS

 File History is a nifty feature on Windows that allows you to back up your important files and folders to an external drive. Although the feature works as expected most of the time, it can occasionally trouble you with errors like the “We found errors in your File History settings” on Windows.

 Let’s see how you can resolve this error and get the File History feature to work again on Windows.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->
## 1\. Restart the File History Service

 File History Service is a small program that needs to be running in the background for the File History feature to work. If this service is experiencing any problems, you could run into the "We found errors in your File History settings" error. In most cases, you can fix any temporary issues with File History Service by simply restarting it.

To restart the File History Service in Windows:

1. Right-click on the**Start icon** and select**Run** from the resulting menu.
2. Type**services.msc** in the text box and press**Enter** .
3. In the Services windows, scroll down to locate**File History Service** . Right-click on it and select**Restart** . If the service is not running, select**Start** .  
<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
![Restart File Hisotry Service Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/restart-file-hisotry-service-windows.jpg)

## 2\. Disconnect and Reconnect the Backup Drive

 Connection problems with your external drive can also cause Windows to display the "We found errors in your File History settings" error. If it’s nothing major, you should be able to resolve the error by disconnecting and reconnecting your backup drive.

 While you're at it, try using a different USB port. This will help you determine if there’s a [problem with the USB port](https://www.makeuseof.com/tag/dead-usb-port-heres-how-to-diagnose-and-fix-it/) you’re using. If you suspect a port is malfunctioning, check out how to diagnose and fix a faulty USB port on Windows.

## 3\. Re-Select the Backup Drive and Restart File History

 Next, you can try re-selecting your backup drive in File History settings and see if that helps. Here are the steps for the same.

1. Press**Win + R** or use one of the [many ways to open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**control** in the box and press**Enter** .
3. Click the**View by** drop-down menu and select**Large icons** .
4. Select**File History** from the Control Panel menu items.
5. Click the**Select drive** option from the left sidebar.
6. Select your preferred drive from the list and click**OK** .  
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35408920&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/FR-200-1.png" border="0">Glarysoft File Recovery Pro - Helps to recover your lost file/data, even permanently deleted data. </a>
<!-- affiliate ads end -->
![Select File History Drive Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/select-file-history-drive-windows.jpg)

 After selecting your preferred drive, you’ll have to restart the File History feature on Windows. To do so, use the following steps:

1. Click the magnifying icon on the taskbar or use the**Win + S** keyboard shortcut to open the search menu.
2. Type**file history** in the search box and select the first result that appears.
3. In the Control Panel window that opens, click the**Turn off** button.
4. Wait for a few seconds and click the**Turn on** button.  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->
![Turn On File History in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-on-file-history-in-windows.jpg)

 If the error message persists even after this, you can try using a different drive for the File History backup and see if that works.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. Reset File History

 Finally, if nothing else works, resetting File History may be your only option. You can accomplish this by deleting the File History data files from your computer.

 In order to delete File History data files, you’ll have to ensure that your PC is configured to [show hidden files and folders on Windows](https://www.makeuseof.com/windows-11-show-hidden-files-folders/) . Here’s how to check.

1. Open the Windows search menu.
2. Type**File Explorer Options** in the search box and press**Enter** .
3. Switch to the**View** tab and check the**Show hidden files, folders, and drives** option.
4. Hit**Apply** followed by**OK** .

 Now, delete the File History data from your system by following the steps below.

1. Press**Win + E** to open File Explorer.
2. Type the following path in the File Explorer’s address bar and press**Enter** .  
`%UserProfile%\AppData\Local\Microsoft\Windows\FileHistory`
3. Press**Ctrl + A** to select all the folders and click the**trash icon** at the top to delete them.  
![Delete File Hisotry AppData](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/delete-file-hisotry-appdata.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
## Fixing File History Errors on Windows

 After you apply the fixes listed above, the File History error should no longer bother you.

 Tired of dealing with File History errors on your Windows device? It might be a good idea to use a cloud storage service or third-party backup software to protect your important data.


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
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-gif-galore-how-to-seamlessly-share-emojis-and-animations-on-instagram/"><u>[New] 2024 Approved  GIF Galore  How to Seamlessly Share Emojis & Animations on Instagram</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-streamlined-process-step-by-step-telegram-web-guide/"><u>[New] Streamlined Process  Step-by-Step Telegram Web Guide</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-harness-googles-skill-for-accurate-speech-to-text-conversion/"><u>[Updated] 2024 Approved  Harness Google's Skill for Accurate Speech to Text Conversion</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-how-to-make-a-thumbnail-for-your-youtube-free-easily/"><u>[Updated] 2024 Approved  How to Make a Thumbnail for Your YouTube Free Easily!</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-visual-vanguard-leading-webcams-for-professional-podcasts/"><u>[Updated] 2024 Approved  Visual Vanguard  Leading Webcams for Professional Podcasts</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-conquer-the-camera-prostrate-techniques-with-gopro-hero5-black/"><u>[Updated] Conquer the Camera  Prostrate Techniques With GoPro Hero5 Black</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-mastering-snap-camera-in-ms-teams/"><u>[Updated] In 2024, Mastering Snap Camera in MS Teams</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unveiling-the-mystery-scriptwriting-for-documentaries/"><u>[Updated] Unveiling the Mystery  Scriptwriting for Documentaries</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-essential-tips-record-powerpoint-live-with-webcam/"><u>2024 Approved  Essential Tips  Record PowerPoint Live with Webcam</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-transform-your-visuals-with-these-11-expert-strategies/"><u>2024 Approved  Transform Your Visuals with These 11 Expert Strategies</u></a></li>
<li><a href="https://extra-tips.techidaily.com/advanced-tips-for-3d-color-grading/"><u>Advanced Tips for 3D Color Grading</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/bypass-reset-f23-5g-phone-screen-passcode-pattern-pin-by-drfone-android-unlock-android-unlock/"><u>Bypass/Reset F23 5G Phone Screen Passcode/Pattern/Pin</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-deadly-windows-1011-error-0x8007045d/"><u>Bypassing Deadly Windows 10/11 Error 0X8007045D</u></a></li>
<li><a href="https://windows11.techidaily.com/deactivating-file-read-only-mode-in-windows/"><u>Deactivating File Read-Only Mode in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-debugs-top-windows-troubleshooting-apps/"><u>Deciphering Debugs: Top Windows Troubleshooting Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-9-compelling-arguments-for-pc-dominance-over-macs/"><u>Demystifying: 9 Compelling Arguments for PC Dominance over Macs</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-change-from-mkv-to-mp4-format-with-windows-tools/"><u>Easy Change From MKV to MP4 Format with Windows Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-pc-safety-introducing-your-unique-window-pin-design/"><u>Elevate PC Safety: Introducing Your Unique Window Pin Design</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminate-loadlibrary-error-87-misconfiguration/"><u>Eliminate LoadLibrary Error 87 Misconfiguration</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-steam-data-flow-stopping-frustrating-speed-drops/"><u>Enhance Steam Data Flow: Stopping Frustrating Speed Drops</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/tial-editing-techniques-for-yt-channel-summaries/"><u>Essential Editing Techniques for YT Channel Summaries</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-to-fixing-0x80071a90-windows-error/"><u>Essential Guide to Fixing 0X80071A90 Windows Error</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-missing-initialization-message-on-windows-pc/"><u>Fixing 'Missing Initialization' Message on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-non-starting-windows-speech-to-text-feature/"><u>Fixing Non-Starting Windows Speech to Text Feature</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-infinix-note-30-vip-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Infinix Note 30 VIP | Dr.fone</u></a></li>
<li><a href="https://driver-download.techidaily.com/get-your-bcm207driver-downloaded-on-windows-in-no-time/"><u>Get Your BCM207#Driver Downloaded on Windows in No Time!</u></a></li>
<li><a href="https://windows11.techidaily.com/hide-your-contacts-delete-email-post-login-in-windows/"><u>Hide Your Contacts: Delete Email Post Login in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-conquer-common-errors-during-windows-11-rollout/"><u>How to Conquer Common Errors During Windows 11 Rollout</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-remove-iphone-xs-activation-lock-by-drfone-ios/"><u>How to Remove iPhone XS Activation Lock</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-poco-x6-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Poco X6 without Losing Data | Dr.fone</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-cooking-crusaders-youtube-stars-serving-up-deliciousness/"><u>In 2024, Cooking Crusaders  YouTube Stars Serving Up Deliciousness</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-hdr-video-power-windows-edition-explained/"><u>In 2024, HDR Video Power  Windows Edition Explained</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-simplify-your-multitasking-using-shortcut-keys-for-macs-screen-capture/"><u>In 2024, Simplify Your Multitasking  Using Shortcut Keys for Mac's Screen Capture</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-strategies-to-integrate-b-roll-footage-seamlessly/"><u>In 2024, Strategies to Integrate B-Roll Footage Seamlessly</u></a></li>
<li><a href="https://screen-recording.techidaily.com/leading-video-conference-software-picks/"><u>Leading Video-Conference Software Picks</u></a></li>
<li><a href="https://win-dash.techidaily.com/lenovo-t430-windows-driver-pack-compatible-with-windows-1187-easy-downloading-options/"><u>Lenovo T430 Windows Driver Pack: Compatible with Windows 11/8/7 - Easy Downloading Options</u></a></li>
<li><a href="https://windows11.techidaily.com/managing-wlanextexe-to-keep-cpu-cool/"><u>Managing Wlanext.EXE to Keep CPU Cool</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-take-your-edits-to-the-next-level-10-free-fcpx-plugins-for-2024/"><u>New Take Your Edits to the Next Level 10 Free FCPX Plugins for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/optimal-pc-performance-tests/"><u>Optimal PC Performance Tests</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-reactivating-windows-1011-explorer/"><u>Quick Fixes: Reactivating Windows 10/11 Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-marketplace-failures-x80131500/"><u>Resolving Windows Marketplace Failures X80131500</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-screens-how-to-fix-stutter-with-these-9-tips/"><u>Seamless Screens: How to Fix Stutter with These 9 Tips</u></a></li>
<li><a href="https://android-location-track.techidaily.com/solutions-to-spy-on-samsung-galaxy-a34-5g-with-and-without-jailbreak-drfone-by-drfone-virtual-android/"><u>Solutions to Spy on Samsung Galaxy A34 5G with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-fix-printer-spooler-not-running-windows/"><u>Strategies to Fix Printer Spooler Not Running Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/switching-file-permissions-disabling-read-only-on-win-os/"><u>Switching File Permissions: Disabling Read-Only on Win OS</u></a></li>
<li><a href="https://windows11.techidaily.com/switchnotepaddisplaytodarkwin/"><u>SwitchNotepadDisplayToDarkWin</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-missing-printmanagement-component-on-your-pc/"><u>Tackling Missing 'PrintManagement' Component on Your PC</u></a></li>
<li><a href="https://android-frp.techidaily.com/the-complete-guide-to-lava-yuva-3-pro-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>The Complete Guide to Lava Yuva 3 Pro FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://windows11.techidaily.com/the-quickest-quality-nine-fixes-to-enhance-your-video-on-pc/"><u>The Quickest Quality: Nine Fixes to Enhance Your Video on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-to-reinstate-functional-utorrent-installer-after-failure-on-winos/"><u>Tips to Reinstate Functional uTorrent Installer After Failure on WinOS</u></a></li>
<li><a href="https://android-unlock.techidaily.com/top-10-fingerprint-lock-apps-to-lock-your-oppo-find-x7-phone-by-drfone-android/"><u>Top 10 Fingerprint Lock Apps to Lock Your Oppo Find X7 Phone</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-app-non-installation-microsoft-tips/"><u>Troubleshooting App Non-Installation: Microsoft Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-xp709-on-windows/"><u>Troubleshooting XP709 on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-a-non-responsive-search-bar-on-windows-11s-ui/"><u>Unblocking a Non-Responsive Search Bar on Windows 11’S UI</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-diminished-window-11-icon-size/"><u>Understanding Diminished Window 11 Icon Size</u></a></li>
<li><a href="https://android-unlock.techidaily.com/unlocking-the-power-of-smart-lock-a-beginners-guide-for-vivo-y100i-users-by-drfone-android/"><u>Unlocking the Power of Smart Lock A Beginners Guide for Vivo Y100i Users</u></a></li>
<li><a href="https://windows11.techidaily.com/unpacking-essential-upgrades-in-februarys-win11-patch/"><u>Unpacking Essential Upgrades in February's Win11 Patch</u></a></li>
<li><a href="https://howto.techidaily.com/why-your-honor-90-pro-screen-might-be-unresponsive-and-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Your Honor 90 Pro Screen Might be Unresponsive and How to Fix It | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-wow-steps-to-overcome-error-132/"><u>Win11 WoW: Steps to Overcome Error #132</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-health-check-up-top-13-restoration-techniques/"><u>Windows Health Check-Up: Top 13 Restoration Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-set-10-key-ms-store-games-and-tools/"><u>Winning Set: 10 Key MS Store Games & Tools</u></a></li>
</ul></div>
