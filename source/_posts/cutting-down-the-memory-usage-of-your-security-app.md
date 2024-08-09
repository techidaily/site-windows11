---
title: Cutting Down the Memory Usage of Your Security App
date: 2024-08-08T05:57:11.782Z
updated: 2024-08-09T05:57:11.782Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Cutting Down the Memory Usage of Your Security App
excerpt: This Article Describes Cutting Down the Memory Usage of Your Security App
keywords: Low Memory Security Apps,Reduce App Memory Use,Efficient Security Software,High-Performance S/W,Optimized Security Apps,Streamline Safety Programs,Minimal Memory Tools
thumbnail: https://thmb.techidaily.com/8ff514e7ae8e73f00c632257f00b6aefbc08dc01d831c81a6f2628b843ff494a.jpg
---

## Cutting Down the Memory Usage of Your Security App

 If you’ve kept a close eye on the Task Manager, then you may have noticed the Antimalware Service Executable doing its job. It is a crucial process of Windows Security (previously "Microsoft Defender") and helps keep your system safe from malware. It is pretty common to disable the Antimalware Service Executable because it consumes a large chunk of the system resources.

 On older PCs with limited system resources, the Antimalware Service Executable can severely impact the performance of your system. Read on as we discuss the importance of this service and how you can disable it.

## What Is the Antimalware Service Executable?

 You’re probably familiar with Windows Security (previously Microsoft Defender). Windows Security is a reliable antivirus that comes pre-installed on Windows 10 and 11\. The Antimalware Service Executable (you may find it listed as**MsMpEng.exe** in the**Task Manager**) is a core part of Windows Security.

 The service helps ensure your PC stays protected against any virus, worms, and other malware by continually scanning files and programs on your PC in the background. If the Antimalware Service Executable finds a malicious file or program, it will immediately delete or quarantine the affected files.

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Should You Disable the Antimalware Service Executable?

 Considering how integral the Antimalware Service Executable is to protect your PC, you must be wondering why you should even consider disabling it.

 If you do not have a third-party antivirus installed on your system, then Windows Security is your sole protection against potentially harmful malware. If your PC is left without any third-party antivirus programs installed, the Antimalware Service Executable automatically enables itself and begins safeguarding your PC as part of Windows Security.

 Ideally, you should not turn off the Antimalware Service Executable process. But if you have a reliable third-party antivirus installed, and the Antimalware Service Executable is still consuming a large chunk of your RAM or CPU, then it might make sense to disable it.

## How to Disable the Antimalware Service Executable

 There are a few different ways you can disable the Antimalware Service Executable depending on the circumstances of your system’s performance.

<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Method 1: Disable Real-time Protection

 Suppose you find the Antimalware Service Executable process consuming a lot of system resources in certain instances; in that case, you can temporarily disable [real-time](https://www.makeuseof.com/real-time-protection/) malware protection through Windows Security:

1. Head to the**Start** menu, search for**Windows Security** and select the Best match.
2. Navigate to**Virus & threat protection** from the sidebar.
3. Look for**Virus & threat protection settings** , and then click on**Manage settings** option underneath.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
![real time protection windows security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/real-time-protection.jpg)
4. Disable the**Real-time protection** toggle button by bringing it to the**Off** position.

 Real-time protection will be turned back on automatically by Windows Security.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
### Method 2: Turn Off Antimalware Service Executable Through Windows Security in the Registry Editor

 For users looking for a more permanent solution to disabling the Antimalware Service Executable, you will have to [disable Windows Security](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) from the Registry Editor.

 If you do not have a third-party antivirus installed, disabling Windows Security will leave your system at risk of malicious malware that can damage it.

To disable Antimalware Service Executable from the Registry Editor:

1. Search for**Registry Editor** from the**Start** menu, and launch it.
2. Navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows Defender** from the sidebar.
3. Right-click on the**Windows Defender** folder and select**New > DWORD (32-bit) Value** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
![regedit windows defender](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/regedit-windows-defender.jpg)
4. Enter**DisableAntiSpyware** in the**Value name** field and**1** in the**Value data** field.
5. Press**OK** to save your changes and restart your system for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
## Should You Rely on Windows Security for Windows 10 and 11?

 Many users opt for a dedicated third-party antivirus on Windows 10 or 11, but Windows Security has made significant improvements in the past few years. Not only is Windows Security a complete antivirus package, but it's also free and comes pre-installed on Windows.

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
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-beat-the-curve-top-facebook-ad-strategies/"><u>[New] 2024 Approved  Beat the Curve  Top Facebook Ad Strategies</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-how-to-make-money-on-youtube-without-ads/"><u>[New] 2024 Approved  How to Make Money on YouTube Without Ads</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-the-key-to-authenticity-on-discord-a-verification-roadmap/"><u>[New] 2024 Approved  The Key to Authenticity on Discord  A Verification Roadmap</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-elevate-your-gaming-by-recording-ps3-games/"><u>[New] In 2024, Elevate Your Gaming by Recording PS3 Games</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-maximizing-instagram-video-exposure-for-2024/"><u>[New] Maximizing Instagram Video Exposure for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-vlc-player-insider-top-10-underrated-functions-for-2024/"><u>[New] VLC Player Insider  Top 10 Underrated Functions for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-divide-and-conquer-easy-chapter-addition-for-vimeo-videos/"><u>[Updated] 2024 Approved  Divide and Conquer  Easy Chapter Addition for Vimeo Videos</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-harness-the-power-of-hashtags-in-instagram-marketing-strategies/"><u>[Updated] 2024 Approved  Harness the Power of Hashtags in Instagram Marketing Strategies</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-amplify-your-influence-on-ig-how-to-gain-1k-followers-monthly/"><u>[Updated] Amplify Your Influence on IG  How to Gain 1K Followers Monthly</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-honored-proposals-leading-ringtone-creators-iphone/"><u>2024 Approved  Honored Proposals  Leading Ringtone Creators iPhone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-quick-guide-to-honor-90-frp-bypass-instantly-by-drfone-android/"><u>A Quick Guide to Honor 90 FRP Bypass Instantly</u></a></li>
<li><a href="https://windows11.techidaily.com/easing-excessive-load-alert-for-gpt-window-use/"><u>Easing Excessive Load Alert for GPT Window Use</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-steps-for-activating-outlook-preview-in-windows-11-os/"><u>Easy Steps for Activating Outlook Preview in Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-playback-of-laggard-videos/"><u>Efficient Playback of Laggard Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-altering-windows-account-pin-code/"><u>Efficiently Altering Windows Account Pin Code</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-run-windows-11-news-and-video-sites-without-strain/"><u>Efficiently Run Windows 11 News & Video Sites without Strain</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-telnet-configuration-for-win11-users/"><u>Effortless Telnet Configuration for Win11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-performance-top-tools-to-tune-up-windows-pcs/"><u>Elevate Performance: Top Tools to Tune Up Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-workflow-select-7-most-powerful-w11-widgets/"><u>Elevate Workflow: Select 7 Most Powerful W11 Widgets</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-application-display-enable-windows-11s-autocolor/"><u>Elevate Your Application Display - Enable Windows 11'S AutoColor</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-workflow-with-god-mode-add-on/"><u>Elevate Your Workflow with God Mode Add-On</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-workflow-on-windows-11-for-professionals/"><u>Elevating Workflow on Windows 11 for Professionals</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-your-app-setup-game-with-winstall-on-windows-11/"><u>Elevating Your App Setup Game with Winstall on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-the-error-unable-to-terminate-process-phenomenon/"><u>Eliminating the 'Error: Unable to Terminate Process' Phenomenon</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-unexpected-closure-notifications-from-roblox-games/"><u>Eliminating Unexpected Closure Notifications From Roblox Games</u></a></li>
<li><a href="https://windows11.techidaily.com/emulate-macos-style-5-methods-to-revamp-windows/"><u>Emulate macOS Style: 5 Methods to Revamp Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/enable-sd-card-view-in-file-explorer-puzzle-solved/"><u>Enable SD Card View in File Explorer Puzzle Solved</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-application-guard-printing-for-windows-11-users/"><u>Enabling Application Guard Printing for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-epic-launcher-performance-a-how-to/"><u>Enhancing Epic Launcher Performance: A How-To</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-mouse-cursor-prominence-in-windows-os/"><u>Enhancing Mouse Cursor Prominence in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-single-user-printer-operation-on-windows-11/"><u>Ensuring Single-User Printer Operation on Windows 11</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-can-we-bypass-lava-yuva-2-pro-frp-by-drfone-android/"><u>How Can We Bypass Lava Yuva 2 Pro FRP?</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-call-logs-from-infinix-hot-40i-by-fonelab-android-recover-call-logs/"><u>How To  Restore Missing Call Logs from Infinix Hot 40i</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-change-motorola-moto-g-5g-2023-lock-screen-password-by-drfone-android/"><u>How To Change Motorola Moto G 5G (2023) Lock Screen Password?</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-oppo-find-x6-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>In 2024, How to Cast Oppo Find X6 Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-key-principles-to-write-captivating-vlog-dialogues/"><u>In 2024, Key Principles to Write Captivating Vlog Dialogues</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-optimizing-colors-in-films-via-luts/"><u>In 2024, Optimizing Colors in Films via Luts</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-set-your-preferred-job-location-on-linkedin-app-of-your-apple-iphone-6-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, Set Your Preferred Job Location on LinkedIn App of your Apple iPhone 6 Plus | Dr.fone</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-guide-eliminating-resident-evil-villages-pc-performance-hiccups/"><u>Troubleshooting Guide: Eliminating Resident Evil Village's PC Performance Hiccups</u></a></li>
<li><a href="https://fake-location.techidaily.com/ultimate-guide-to-free-pptp-vpn-for-beginners-on-lava-blaze-2-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Free PPTP VPN For Beginners On Lava Blaze 2 | Dr.fone</u></a></li>
</ul></div>
