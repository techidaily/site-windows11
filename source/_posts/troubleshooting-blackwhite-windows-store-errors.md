---
title: Troubleshooting Black/White Windows Store Errors
date: 2024-12-14T21:59:22.945Z
updated: 2024-12-17T01:14:07.587Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Black/White Windows Store Errors
excerpt: This Article Describes Troubleshooting Black/White Windows Store Errors
keywords: Window Store Issue Fix,B/W Store Crash Resolve,Windows App Blackout Trouble,White Windows Problem Solve,Error Handling B/W Store,Windows Store Colour Glitch,Addressing B/W Windows Fail
thumbnail: https://thmb.techidaily.com/b1b6775bf38540cce32c7cf3ae0c3f9781deea4b62c3dc654004acc69b97d819.jpg
---

## Troubleshooting Black/White Windows Store Errors

 If you’re looking for a new app to install on your Windows computer, chances are you’re using Microsoft Store.

 Microsoft Store has the advantage that every listed app is certified by Microsoft, so there’s no chance of hidden malware or virus. Also, you can download movies and TV shows.

 But if the store is displaying a white or black screen, you will not be able to get any new apps or movies. However, you can easily get back Microsoft Store functionality by going through the steps below.

## 1\. Restart the Microsoft Store

 Microsoft Store showing a black or white screen might be due to a temporary glitch. In this case, restarting the app should be enough to fix it.

 Once you close Microsoft Store, press**Ctrl + Shift + Esc** to bring up Task Manager. Then, open the**Processes** tab. Right-click**Microsoft Store** and select**End task** to close any process that might be running in the background.

![Clost Microsoft Store tasks](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/end-microsoft-store-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vPGg53vbOsk?si=CkSEN5HFPS7vDuAa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Open Microsoft Store again and check if it’s now working.

 If you're encountering a lot of glitches that go away after a restart, you might be leaving your PC on for too long. Check out these[reasons why you should turn off your PC every night](https://www.makeuseof.com/reasons-why-should-shut-down-computer/) for some inspiration.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9sk53d1bBhY?si=yaTeDogLb3D4dYu1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Check Your Internet Connection

 There might be nothing wrong with Microsoft Store, but you’re simply having an internet connectivity problem. If you’re[dealing with an unstable WiFi connection](https://www.makeuseof.com/tag/fix-slow-unstable-wi-fi-connection/) or downloading a large file, Microsoft Store might display a black or white screen.

 If possible, access the store from a different device. If everything works as usual, the problem is limited to your computer.

## 3\. Run the Microsoft Store Troubleshooter

 Every time you run into an issue on your Windows computer, try running the corresponding troubleshooter. These tools are designed to fix any generic issues that you may encounter.

 So, for any trouble regarding the Microsoft Store, you should run the Windows Store Apps troubleshooter. Here’s how to do it:

1. Right-click the**Start** button and go to**Settings** .
2. Click**System > Troubleshoot** .
3. Select**Other trouble-shooters** .
4. Click the**Run** button next to**Windows Store Apps** .

![Run Windows app troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/store-troubleshooter-1.jpg)

 Windows will search for any issues and fix them automatically. Once the process is complete, try to launch Microsoft Store again.

## 4\. Delete the Microsoft Store Cache

 Like most apps, Microsoft Store uses cache to improve performance. But if the app’s cache somehow gets corrupted, you’ll run into all sorts of issues, including Microsoft Store displaying a black or white background every time you open the app. In this case, deleting the cache should fix the problem.

 Press**Win + R** to bring up a Run dialog. Then, type**wsreset.exe** , and press**Shift + Enter** to run the command with administrative rights.

 This should open a blank Command Prompt window for several seconds. Once it deletes the cache, Windows will close Command Prompt and launch the Microsoft Store app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_SbYznUy_zY?si=ThBkP934r3mizi48" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Run the SFC Tool

 There’s a chance that Microsoft Store isn’t working as usual due to corrupt or damaged system files. To fix the issue, you should run the Windows System File Checker tool.

 First, launch Command Prompt with administrative rights. Then, type**sfc/ scannow** and press**Enter** .

 Make sure you don’t close the Command Prompt window until the scan is complete. Windows will search and automatically replace any corrupt or damaged system files.

![Run SFC scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/sfc-scan-1-3.jpg)

## 6\. Check Your System's Set Time and Region

 Microsoft Store servers must be synced with your system, so everything works properly. If your computer’s time and region, Microsoft Store will show a black, white, or even blue screen.

Go through the below steps to change the Windows region:

1. Press**Win + I** to bring up Windows Settings.
2. From the left-hand menu, click**Time & language** .
3. Select**Language & region** .
4. Set**Country or region** to your current region.
5. Restart your computer and check if Microsoft Store is working.

![Change Windows region](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-region-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/h5uImbOWmTg?si=z4kP-R0QbXbBAJTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Also, you can[manually change Windows date and time settings](https://www.makeuseof.com/windows-11-change-date-time/) .

## 7\. Re-register the Microsoft Store

 If you couldn’t get Microsoft Store to work using the above solutions, you should re-register the app through PowerShell. The process is quite easy and fast.

 First, launch PowerShell with administrative rights. If you don't know how to do this, refer to[how to open PowerShell with administrative rights](https://www.makeuseof.com/windows-11-powershell-administrator/) .

 Then, copy the **Get-AppXPackage \*WindowsStore\* -AllUsers | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($\_.InstallLocation)\\AppXManifest.xml"}** command, and press**Enter** to run it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zmXpl6irBYk?si=BXjGpQr6PXFcqhCI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 8\. Reset Your Windows PC

 If Microsoft Store showing a black or white screen isn’t the only problem you noticed, there might be some deep corruption within your system files. In this case, you could try to[factory reset your Windows PC](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) . This will revert it back to its factory settings, so make sure you back up all essential data.

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
<li><a href="https://some-skills.techidaily.com/new-the-8-step-formula-for-captivating-your-instagram-audience-with-reels/"><u>[New] The 8-Step Formula for Captivating Your Instagram Audience with Reels</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-2024-approved-top-9-iphone-tools-expertly-watermarking-your-pics/"><u>[Updated] 2024 Approved Top 9 iPhone Tools Expertly Watermarking Your Pics</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-easyvidrecorder-web-based-video-grab/"><u>[Updated] EasyVidRecorder Web-Based Video Grab</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-essential-tips-for-gameplay-screen-shotting-on-playstation-4-for-2024/"><u>[Updated] Essential Tips for Gameplay Screen Shotting on PlayStation 4 for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-spotlight-on-success-top-tiktok-tweets/"><u>[Updated] Spotlight on Success Top TikTok Tweets</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/everything-you-need-to-know-about-unlocked-apple-iphone-15-pro-by-drfone-ios/"><u>Everything You Need To Know About Unlocked Apple iPhone 15 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/file-location-artistry-in-windows-11-exploring-best-practices-6-advanced-methods/"><u>File Location Artistry in Windows 11: Exploring Best Practices (6 Advanced Methods)</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tune-your-system-control-delete-confirmations/"><u>Fine-Tune Your System: Control Delete Confirmations</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/how-luts-refine-image-details-and-contrast-in-photos-for-2024/"><u>How LUTs Refine Image Details and Contrast in Photos for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-nvidia-control-panel-not-saving-settings-in-windows-11/"><u>How to Fix the NVIDIA Control Panel Not Saving Settings in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-window-terminals-shutdown-procedures-entryexit-tactics/"><u>Mastering Window Terminal's Shutdown Procedures: Entry/Exit Tactics</u></a></li>
<li><a href="https://network-issues.techidaily.com/quick-fix-rectify-apex-legends-glitches-now/"><u>Quick Fix: Rectify Apex Legends Glitches Now!</u></a></li>
<li><a href="https://windows11.techidaily.com/rediscover-the-lost-treasures-within-windows-11s-features/"><u>Rediscover the Lost Treasures Within Windows 11'S Features</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-to-reduce-high-wmi-cpu-consumption/"><u>Solutions to Reduce High WMI CPU Consumption</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-mending-non-responsive-windows-network/"><u>Strategies for Mending Non-Responsive Windows Network</u></a></li>
<li><a href="https://windows11.techidaily.com/top-methods-to-enhance-utorrent-download-speed-win-edition/"><u>Top Methods to Enhance uTorrent Download Speed, WIN Edition</u></a></li>
<li><a href="https://win-advanced.techidaily.com/unveiling-windows-11-se-the-latest-educational-laptops-from-pc-manufacturers-zdnet/"><u>Unveiling Windows 11 SE: The Latest Educational Laptops From PC Manufacturers - ZDNet</u></a></li>
</ul></div>

