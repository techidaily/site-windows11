---
title: Curing White Screen Problems on Store Platform
date: 2025-01-10T11:47:49.080Z
updated: 2025-01-15T22:16:49.777Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Curing White Screen Problems on Store Platform
excerpt: This Article Describes Curing White Screen Problems on Store Platform
keywords: Fix White Screens,Stop Store Display,Clearing Screen Error,Resolve Screenshare Glitch,Eliminate Blackout Bug,Stop Freeze Issue,Cure Screenspace Problem
thumbnail: https://thmb.techidaily.com/65d11e70a3e2b524202510534160699ecec295d81962cec51e81800c7f637654.jpg
---

## Curing White Screen Problems on Store Platform

 If you’re looking for a new app to install on your Windows computer, chances are you’re using Microsoft Store.

 Microsoft Store has the advantage that every listed app is certified by Microsoft, so there’s no chance of hidden malware or virus. Also, you can download movies and TV shows.

 But if the store is displaying a white or black screen, you will not be able to get any new apps or movies. However, you can easily get back Microsoft Store functionality by going through the steps below.

## 1\. Restart the Microsoft Store

 Microsoft Store showing a black or white screen might be due to a temporary glitch. In this case, restarting the app should be enough to fix it.

 Once you close Microsoft Store, press**Ctrl + Shift + Esc** to bring up Task Manager. Then, open the**Processes** tab. Right-click**Microsoft Store** and select**End task** to close any process that might be running in the background.

![Clost Microsoft Store tasks](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/end-microsoft-store-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bXmwwSmYqq4?si=Bb-eJfLnlpeeClyt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Open Microsoft Store again and check if it’s now working.

 If you're encountering a lot of glitches that go away after a restart, you might be leaving your PC on for too long. Check out these [reasons why you should turn off your PC every night](https://www.makeuseof.com/reasons-why-should-shut-down-computer/) for some inspiration.

## 2\. Check Your Internet Connection

 There might be nothing wrong with Microsoft Store, but you’re simply having an internet connectivity problem. If you’re [dealing with an unstable WiFi connection](https://www.makeuseof.com/tag/fix-slow-unstable-wi-fi-connection/) or downloading a large file, Microsoft Store might display a black or white screen.

 If possible, access the store from a different device. If everything works as usual, the problem is limited to your computer.

## 3\. Run the Microsoft Store Troubleshooter

 Every time you run into an issue on your Windows computer, try running the corresponding troubleshooter. These tools are designed to fix any generic issues that you may encounter.

 So, for any trouble regarding the Microsoft Store, you should run the Windows Store Apps troubleshooter. Here’s how to do it:

1. Right-click the**Start** button and go to**Settings** .
2. Click**System > Troubleshoot** .
3. Select**Other trouble-shooters** .
4. Click the**Run** button next to**Windows Store Apps** .

![Run Windows app troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/store-troubleshooter-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/On0Jw2oMZf0?si=Pm-FJoEt8XWmtMbr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Windows will search for any issues and fix them automatically. Once the process is complete, try to launch Microsoft Store again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sXLLPY11of0?si=-3YNnpnO0wbc0K_-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Delete the Microsoft Store Cache

 Like most apps, Microsoft Store uses cache to improve performance. But if the app’s cache somehow gets corrupted, you’ll run into all sorts of issues, including Microsoft Store displaying a black or white background every time you open the app. In this case, deleting the cache should fix the problem.

 Press**Win + R** to bring up a Run dialog. Then, type**wsreset.exe** , and press**Shift + Enter** to run the command with administrative rights.

 This should open a blank Command Prompt window for several seconds. Once it deletes the cache, Windows will close Command Prompt and launch the Microsoft Store app.

## 5\. Run the SFC Tool

 There’s a chance that Microsoft Store isn’t working as usual due to corrupt or damaged system files. To fix the issue, you should run the Windows System File Checker tool.

 First, launch Command Prompt with administrative rights. Then, type**sfc/ scannow** and press**Enter** .

 Make sure you don’t close the Command Prompt window until the scan is complete. Windows will search and automatically replace any corrupt or damaged system files.

![Run SFC scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/sfc-scan-1-3.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QRaEdFMU-Xc?si=OjaiTvlogJy5wHhN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Check Your System's Set Time and Region

 Microsoft Store servers must be synced with your system, so everything works properly. If your computer’s time and region, Microsoft Store will show a black, white, or even blue screen.

Go through the below steps to change the Windows region:

1. Press**Win + I** to bring up Windows Settings.
2. From the left-hand menu, click**Time & language** .
3. Select**Language & region** .
4. Set**Country or region** to your current region.
5. Restart your computer and check if Microsoft Store is working.

![Change Windows region](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-region-1.jpg)

 Also, you can [manually change Windows date and time settings](https://www.makeuseof.com/windows-11-change-date-time/) .

## 7\. Re-register the Microsoft Store

 If you couldn’t get Microsoft Store to work using the above solutions, you should re-register the app through PowerShell. The process is quite easy and fast.

 First, launch PowerShell with administrative rights. If you don't know how to do this, refer to [how to open PowerShell with administrative rights](https://www.makeuseof.com/windows-11-powershell-administrator/) .

 Then, copy the **Get-AppXPackage \*WindowsStore\* -AllUsers | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($\_.InstallLocation)\\AppXManifest.xml"}** command, and press**Enter** to run it.

## 8\. Reset Your Windows PC

 If Microsoft Store showing a black or white screen isn’t the only problem you noticed, there might be some deep corruption within your system files. In this case, you could try to [factory reset your Windows PC](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) . This will revert it back to its factory settings, so make sure you back up all essential data.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Bov2KfWQ_Y?si=MnVczisgeJ-sGW2r" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Get the Microsoft Store Working Again

 It can be frustrating when you need to install a new app, but Microsoft Store isn’t working. Instead of looking for the same app on not-so-trustworthy websites, you can use the above solutions to fix Microsoft Store.

 But if you can’t find a specific app, there are several websites where you can download apps without compromising your system security.

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
<li><a href="https://youtube-zero.techidaily.com/el-expansion-through-smart-youtube-link-building-methods/"><u>Channel Expansion Through Smart YouTube Link-Building Methods</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722958701429-experience-gaming-like-never-before-by-updating-nvidias-gtx-1660-ti-drivers/"><u>Experience Gaming Like Never Before by Updating NVIDIA's GTX 1660 Ti Drivers</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-updated-epson-artisan-1430-drivers-optimized-for-windows-11108-secure-your-print-jobs/"><u>Get Updated Epson Artisan 1430 Drivers: Optimized for Windows 11/10/8 - Secure Your Print Jobs!</u></a></li>
<li><a href="https://youtube-data.techidaily.com/-deleting-items-from-your-youtubeumbers-list/"><u>Guide Deleting Items From Your YouTube'umbers List</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-ultimate-guide-on-iphone-15-plus-icloud-activation-lock-bypass-by-drfone-ios/"><u>In 2024, Ultimate Guide on iPhone 15 Plus iCloud Activation Lock Bypass</u></a></li>
<li><a href="https://techtrends.techidaily.com/meet-brian-unruh-the-responsible-executive-for-abbyys-chief-financial-officer-position-steering-fiscal-excellence/"><u>Meet Brian Unruh, the Responsible Executive for ABBYY's Chief Financial Officer Position: Steering Fiscal Excellence</u></a></li>
<li><a href="https://windows11.techidaily.com/optimal-settings-where-to-store-your-games-on-xbox/"><u>Optimal Settings: Where to Store Your Games on Xbox</u></a></li>
<li><a href="https://windows11.techidaily.com/reducing-memory-waste-with-microsoft-edges-webview2/"><u>Reducing Memory Waste with Microsoft Edge's WebView2</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-need-old-password-warning-on-win11win11-os/"><u>Resolving “Need Old Password” Warning on Win11/Win11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionize-desktop-top-5-clock-saver-software/"><u>Revolutionize Desktop - Top 5 Clock Saver Software</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/sending-past-moments-via-snapchat-camera-roll-guide/"><u>Sending Past Moments via Snapchat Camera Roll Guide</u></a></li>
</ul></div>

