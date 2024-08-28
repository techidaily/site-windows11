---
title: Stepwise Strategy to Erase WSL From Windows 11 Operating System
date: 2024-08-27T16:05:59.371Z
updated: 2024-08-28T16:05:59.371Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Stepwise Strategy to Erase WSL From Windows 11 Operating System
excerpt: This Article Describes Stepwise Strategy to Erase WSL From Windows 11 Operating System
keywords: Removing WSL (Windows Subsystem for Linux),Win11 WSL Deactivation Steps,Uninstall Linux on Windows 11,Disable WSL in Windows 11,How to Remove Linux Subsystem,Turn Off Windows Subsystem,Stop Linux Support in Windows OS
thumbnail: https://thmb.techidaily.com/c8cc0b50d6a862024b28911d2e2409173d05c3a9fcb60009ede2fce73e839885.jpg
---

## Stepwise Strategy to Erase WSL From Windows 11 Operating System

 If you don't want or need Windows Subsystem for Linux on your computer, you can remove it. However, that process can include more than just clicking the uninstall button in Windows Settings. It isn't difficult, but it's important to remove files in the correct order.

 Here are the steps you need to follow to completely remove WSL from your Windows PC.

## Why Uninstall Windows Subsystem for Linux?

 WSL is a very handy tool that allows you to easily run Linux distros in a virtual environment on your Windows computer. Although it doesn't have much impact on storage space, if you have no interest in using Linux, there's no need to have it installed.

 There are also [good alternatives to WSL](https://www.makeuseof.com/dont-need-microsoft-windows-subsystem-for-linux/) for running Linux available, and you might decide to use one of those instead of the Microsoft solution. Not only would you not need WSL, but there is also a slight risk of conflict between the Windows Subsystem and your alternative choice.

## Remove All Installed Linux Distros on Windows

 This step won't be relevant to everyone, but if you have installed any Linux distros, you should remove them first. This helps to ensure that no files associated with the Linux installations remain on your computer when you uninstall WSL.

1. You can find your installed Linux distros listed with your other installed apps in **Settings > Apps > Installed Apps**.
2. Uninstall each of the Linux Distros, such as Ubuntu, in exactly the same way you would [uninstall any other Windows app](https://www.makeuseof.com/ways-to-uninstall-apps-windows-11/).

![Ubuntu in the Windows 11 apps list](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-remove.jpg)

 If the computer came to you with the apps already installed, you might not know what is or isn't a Linux distribution. Here are some of the [most common Linux distros](https://www.makeuseof.com/linux-distros-for-beginners-intermediate-and-advanced-users/), but you can also simply do a Google search for the name of the app you are unsure about.

 When all versions of Linux have been uninstalled, you can move on to the next step in the process.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
## Uninstall the WSL Components

 With all versions of Linux removed, you can remove the WSL app and its related components. As with the previous step, you can remove WSL in the same way you would remove any other app.

 Go to **Settings > Apps > Apps & Features**. Scroll down to the bottom of your apps list to find Windows Subsystem for Linux. Click the **More** button and select **Uninstall**. On Windows 10, click on the app name and then click **Uninstall**.

![Uninstalling WSL components in Windows settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-components.jpg)

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
 If you see any additional WSL components, such as the WSL update or WSLg Preview, uninstall these in the same way.

<!-- affiliate ads begin -->
<span id="1993652">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Uninstall WSL and Virtual Machine Platform

 The final part of the process is to uninstall the WSL core files and disable the option in the Windows Optional Features panel.

1. Open the Windows Features panel by going to **Settings > Apps > Optional Features > More Windows Features**. You can also search for **Windows Features** and click **Turn Windows features on or off**.
2. Scroll down the list of features to find and deselect the **Windows Subsystem for Linux** option.
3. If you don't need to run any other virtual environments, you can also deselect the **Virtual Machine Platform** option.
4. Click **Ok**, and then restart your computer.

![Removing WSL in the Windows Features panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-core-files.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
 WSL should now be completely removed from your computer. It will receive no automatic updates, and you won't be able to interact with it in any way. If you need it in the future, here's how to [install WSL through the Microsoft Store](https://www.makeuseof.com/install-windows-subsystem-for-windows-microsoft-store/) on a Windows PC.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
## Removing WSL From Your Windows PC

 You can install WSL on your Windows computer with a single command. Uninstalling it, if you no longer need or want it on your PC, is not quite as simple. By following the three simple steps detailed here, you can ensure that all WSL files and components are removed.

 If you don't want or need Windows Subsystem for Linux on your computer, you can remove it. However, that process can include more than just clicking the uninstall button in Windows Settings. It isn't difficult, but it's important to remove files in the correct order.

 Here are the steps you need to follow to completely remove WSL from your Windows PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-record-videos.techidaily.com/new-design-channels-get-free-visuals-now-for-2024/"><u>[New] Design Channels - Get Free Visuals Now for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-ultimate-checklist-to-increase-likes-on-your-tiktok-videos/"><u>[New] The Ultimate Checklist to Increase Likes on Your TikTok Videos</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-unmatched-visuals-leading-ps5-compatible-hdmi-21-monitors-for-2024/"><u>[New] Unmatched Visuals  Leading PS5 Compatible HDMI 2.1 Monitors for 2024</u></a></li>
<li><a href="https://win-able.techidaily.com/solved-yakuza-like-a-dragon-crashing-on-pc/"><u>[SOLVED] Yakuza: Like a Dragon Crashing on PC</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-2024-approved-how-to-free-rotate-and-merge-videos-on-android/"><u>[Updated] 2024 Approved  How to Free Rotate and Merge Videos on Android</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-mastering-video-capturing-made-simple-a-complete-guide-using-zd-software/"><u>[Updated] 2024 Approved  Mastering Video Capturing Made Simple  A Complete Guide Using ZD Software</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/1716068947498-updated-2024-approved-seeking-the-best-ps2-games-try-these-5-android-emulators/"><u>[Updated] 2024 Approved  Seeking the Best PS2 Games? Try These 5 Android Emulators!</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-comprehensive-app-audit-by-az-recorder/"><u>[Updated] Comprehensive App Audit by AZ Recorder</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-comprehensive-list-of-ios-compatible-ps2-games/"><u>[Updated] Comprehensive List of iOS-Compatible PS2 Games</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-free-editing-powerhouses-top-9-simplified-video-tools/"><u>[Updated] In 2024, Free Editing Powerhouses  Top 9 Simplified Video Tools</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-the-complete-zoomers-guide-achieving-exceptional-video-and-audio-recordings-on-zoom/"><u>[Updated] In 2024, The Complete Zoomer's Guide  Achieving Exceptional Video & Audio Recordings on Zoom</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-ai-naming-power-the-top-ten-podcast-renamers/"><u>2024 Approved  AI Naming Power  The Top Ten Podcast Renamers</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-explore-top-5-ps2-games-simulators-for-ios/"><u>2024 Approved  Explore Top 5 PS2 Games Simulators for iOS</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-in-depth-comparison-the-finest-streaming-tv-platforms/"><u>2024 Approved  In-Depth Comparison  The Finest Streaming TV Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/7-pivotal-points-for-reconnecting-your-obs-studio-link-win-compatible/"><u>7 Pivotal Points for Reconnecting Your OBS Studio Link (Win-Compatible)</u></a></li>
<li><a href="https://howto.techidaily.com/android-screen-stuck-general-honor-magic-6-pro-partly-screen-unresponsive-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Android Screen Stuck General Honor Magic 6 Pro Partly Screen Unresponsive | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/bypassing-google-account-with-vnrom-bypass-for-infinix-note-30-vip-by-drfone-android/"><u>Bypassing Google Account With vnROM Bypass For Infinix Note 30 VIP</u></a></li>
<li><a href="https://hardware-help.techidaily.com/discover-the-world-of-computing-with-toms-gear-expertise/"><u>Discover the World of Computing with Tom's Gear Expertise</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-steps-for-powertoys-on-win11/"><u>Essential Steps for PowerToys on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-effortlessly-engage-with-windows-11-service-tools/"><u>How to Effortlessly Engage with Windows 11 Service Tools</u></a></li>
<li><a href="https://program-issues.techidaily.com/immortals-fenyx-rising-not-launching-solved/"><u>Immortals Fenyx Rising Not Launching [SOLVED]</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-motorola-moto-g04-drfone-by-drfone-virtual/"><u>In 2024, 9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Motorola Moto G04 | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-text-messages-from-oneplus-nord-n30-5g-to-new-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Text Messages from OnePlus Nord N30 5G to New Phone | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-infinite-recorders-without-bounds/"><u>In 2024, Infinite Recorders Without Bounds</u></a></li>
<li><a href="https://windows11.techidaily.com/initiating-playback-with-windows-media-player-guide/"><u>Initiating Playback with Windows Media Player Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/learn-how-to-resurrect-the-non-functional-win-plus-p-feature-in-windows/"><u>Learn How to Resurrect the Non-Functional Win + P Feature in Windows.</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-bluescreenview-an-in-depth-analysis/"><u>Leveraging BlueScreenView - An In-Depth Analysis</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-fixes-reconciling-obs-server-disconnections-on-windows/"><u>Mastering the Fixes: Reconciling OBS Server Disconnections on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11-a-guide-to-overcoming-stubborn-gif-size-errors-discord/"><u>Mastering Windows 11: A Guide to Overcoming Stubborn GIF Size Errors (Discord)</u></a></li>
<li><a href="https://windows11.techidaily.com/modifying-metadata-in-windows-files-timestamp-tweaks-guide/"><u>Modifying Metadata in Windows Files: Timestamp Tweaks Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-error-code-0xc00ce556-in-windows/"><u>Navigating the Error Code 0xC00CE556 in WINDOWS</u></a></li>
<li><a href="https://youtube-help.techidaily.com/navigating-through-common-youtube-short-difficulties-for-2024/"><u>Navigating Through Common YouTube Short Difficulties for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/preparing-for-a-mobile-cinematic-experience-for-2024/"><u>Preparing for a Mobile Cinematic Experience for 2024</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/quickclip-editor-for-2024/"><u>QuickClip Editor for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/reimagining-windows-ui-adding-menus-and-subitems/"><u>Reimagining Windows UI: Adding Menus and Subitems</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-checksum-accuracy-in-winrar-archives-with-6-tips/"><u>Restoring Checksum Accuracy in WinRAR Archives with 6 Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-and-protect-win-11-edge-instalment-of-microsofts-aguard-feature/"><u>Secure and Protect Win 11 Edge: Instalment of Microsoft's Aguard Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-and-slim-filesystem-setting-up-auto-delete-in-win11/"><u>Secure and Slim Filesystem: Setting Up Auto Delete in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-your-deal-black-friday-612-for-full-life-win10/"><u>Secure Your Deal: Black Friday - $6.12 for Full-Life Win10</u></a></li>
<li><a href="https://windows11.techidaily.com/simplified-approach-to-batch-convert-heic-files-to-jpeg-in-windows-11/"><u>Simplified Approach to Batch Convert HEIC Files to JPEG in Windows 11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/simplify-information-storage-via-mematic-for-2024/"><u>Simplify Information Storage via Mematic for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/strategic-tips-to-optimize-amd-radeon-gaming/"><u>Strategic Tips to Optimize AMD Radeon Gaming</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-tackling-windows-disk-errors/"><u>The Ultimate Guide to Tackling Windows Disk Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-seamless-slideshow-creation-and-image-spot-repair-in-win11-photos/"><u>Tips for Seamless Slideshow Creation and Image Spot Repair in Win11 Photos</u></a></li>
<li><a href="https://windows11.techidaily.com/title-perfecting-space-between-windows-widgets/"><u>Title: Perfecting Space Between Windows Widgets</u></a></li>
<li><a href="https://extra-hints.techidaily.com/top-free-video-template-resources/"><u>Top Free Video Template Resources</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshoot-unresponsive-inputs-when-waking-up-win11/"><u>Troubleshoot Unresponsive Inputs When Waking up Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-non-responsive-windows-enter-key/"><u>Troubleshooting Non-Responsive Windows Enter Key</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-steam-friendship-disconnect-on-pc/"><u>Troubleshooting Steam Friendship Disconnect on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-potential-top-winning-apps-from-ms-store-2023/"><u>Unleash Potential: Top Winning Apps From MS Store, 2023</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-your-pc-easily-windows-hello-fingerprint-guide/"><u>Unlock Your PC Easily: Windows Hello Fingerprint Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-new-horizons-rethinking-user-rights-on-windows/"><u>Unlocking New Horizons: Rethinking User Rights on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-diagnostic-info-a-quick-guide/"><u>Unlocking Windows' Diagnostic Info: A Quick Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-blue-screen-mystery-0xc0000001/"><u>Unraveling Blue Screen Mystery - 0xC0000001</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-gif-size-limits-a-guide-to-fixed-errors-in-discord-win11/"><u>Unraveling GIF Size Limits: A Guide to Fixed Errors in Discord (Win11)</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-mastering-gopro-video-editing-on-mac-a-2023-guide-for-2024/"><u>Updated Mastering GoPro Video Editing on Mac A 2023 Guide for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/uptime-expertise-for-win11-devices-discover-the-top-5-methods/"><u>Uptime Expertise for Win11 Devices - Discover the Top 5 Methods</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/watching-taylor-swifts-cinematic-journey-step-by-step/"><u>Watching Taylor Swift's Cinematic Journey Step-by-Step</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-drop-issue-effective-solutions-needed/"><u>Win11 Drop Issue: Effective Solutions Needed</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>