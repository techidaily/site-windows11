---
title: Correcting Unpredictable Power Estimator Display on Windows 11
date: 2024-08-15T16:00:52.034Z
updated: 2024-08-16T16:00:52.034Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting Unpredictable Power Estimator Display on Windows 11
excerpt: This Article Describes Correcting Unpredictable Power Estimator Display on Windows 11
keywords: Power Usage Monitoring,Windows 11 Performance Fix,Predictability in Energy Display,Unpredictable Energy Estimator,Optimize Windows Power Display,Improve Windows 11 Battery Life,Correcting Power Display Issues
thumbnail: https://thmb.techidaily.com/3fbb28fdd30ab5cd77a4baca2551c9d92b27e18215ac7c02404eb389cacb68b2.jpg
---

## Correcting Unpredictable Power Estimator Display on Windows 11

 Keeping track of how much charge remains in your laptop battery is easy. By default, hovering over the battery icon in the System Tray displays an estimate of battery time remaining, along with a percentage. Occasionally, the time estimate goes missing, leaving you to work out how much usage time you have left by percentage alone.

 Here's how to get that useful battery time remaining estimate showing again if it has vanished from your notebook.

## Where Did the Time Estimate Go?

 There are a few possible reasons why the time estimate has disappeared. The change often happens after upgrading to Windows 11, but even simply updating the OS can cause it. A later update may fix the issue, but that isn't always the case.

![battery icon tooltip in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/battery-time.jpg)

 It isn't entirely obvious what the root cause is. It could be a conflict in the Registry, which can occur during the update process. It also seems to have been deliberately disabled by Microsoft in some updates. Perhaps because the company is working on power and battery settings for a future update.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
## How to Enable the Battery Time Estimate in the Registry

 Whatever the cause of its disappearance, the battery time estimate is still part of the OS. And with a bit of Registry tweaking, it can be brought back into view.

 As always, it is a good idea to [back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you make any changes. This is only a minor edit and shouldn't cause problems, but it's better to be safe than sorry.

1. Click Windows Search and type**Regedit** to find the Registry Editor. You don't need to choose Run as Administrator. Just select the search result.
2. With the Registry Editor open, navigate to: **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\Power** .
3. If there is no**Power** key, right-click on**Control** in the navigation panel, and select**New > Key** . Name the new registry key**Power** .  
![power values in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-key.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->
4. Right-click the Power key and select**New > DWORD (32-bit) Value** . Set the name of this DWORD as**EnergyEstimationEnabled** .
5. Double-click the new DWORD and set the Value data to**1** . Click**Ok** to close the window.  
![Changing value data in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-dword.jpg)
<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
6. Repeat the previous two steps to create two more DWORD values called**EnergyEstimationDisabled** and**UserBatteryDischargeEstimator** .
7. You don't need to change the Value data for these, as they should default to a 0 value.

 Close the Registry Editor and restart your laptop. When you hover over the battery icon in the System Tray, it should show the estimated time remaining. And while you're at it, check out [how to add shortcuts to the System Tray](https://www.makeuseof.com/windows-11-add-shortcuts-menu-to-system-tray/) to make it even more useful.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537546&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/7_copy_2_2_hdpro.png" border="0">HD Video Converter Factory Pro</a>
<!-- affiliate ads end -->
## Fix a Missing Battery Time Estimate on Windows

 Not being able to easily see the estimate of battery time remaining probably isn't going to keep you up at night. But it is a handy feature if using your laptop away from a power source. Luckily, a few minutes spent editing the Registry will fix the problem, so you always know how long it will be before your battery dies.


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
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-playlists-that-rule-spotifys-top-10/"><u>[New] 2024 Approved  Playlists that Rule  Spotify's Top 10</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-resolving-srt-export-woes-in-adobe-premiere-for-2024/"><u>[New] Resolving SRT Export Woes in Adobe Premiere for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-the-ultimate-list-of-mac-screen-capture-software/"><u>[New] The Ultimate List of Mac Screen Capture Software</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-top-5-pc-clipping-apps-essential-shortcuts/"><u>[New] Top 5 PC Clipping Apps  Essential Shortcuts</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-understanding-igs-evolution-reels-and-stories-for-2024/"><u>[New] Understanding IG's Evolution  Reels and Stories for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-advanced-cards-for-crystal-clear-output/"><u>2024 Approved  Advanced Cards for Crystal Clear Output</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-discovering-the-stars-that-sparkle-in-your-domains-social-space/"><u>2024 Approved  Discovering the Stars that Sparkle in Your Domain's Social Space</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-dji-aerial-lineup-standard-drone-professional-edition-4k-quality/"><u>2024 Approved  DJI Aerial Lineup  Standard Drone, Professional Edition, 4K Quality</u></a></li>
<li><a href="https://windows11.techidaily.com/6-essential-rotation-tips-for-windows-11-photos/"><u>6 Essential Rotation Tips for Windows 11 Photos</u></a></li>
<li><a href="https://windows11.techidaily.com/6-ways-to-fix-minecrafts-exit-code-1-on-windows/"><u>6 Ways to Fix Minecraft's Exit Code: 1 on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/a-journey-into-innovation-windows-11-writes-the-next-chapter/"><u>A Journey Into Innovation - Windows 11’ Writes the Next Chapter</u></a></li>
<li><a href="https://windows11.techidaily.com/a-simple-guide-to-resolving-windows-error-0xc0000001/"><u>A Simple Guide to Resolving Windows Error 0xC0000001</u></a></li>
<li><a href="https://windows11.techidaily.com/accessing-control-panel-with-ease-on-pcs/"><u>Accessing Control Panel with Ease on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-graphics-problem-3-for-windows-11-users/"><u>Addressing Graphics Problem #3 for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-vagrant-boot-failures-on-win11plusvmware/"><u>Addressing Vagrant Boot Failures on Win11+VMware</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-store-failure-code-0x800704cf/"><u>Addressing Windows Store Failure Code 0X800704CF</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-strategies-for-overcoming-win11-installer-challenges/"><u>Advanced Strategies for Overcoming Win11 Installer Challenges</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/an-in-depth-exploration-of-discord-features/"><u>An In-Depth Exploration of Discord Features</u></a></li>
<li><a href="https://windows11.techidaily.com/balancing-cpu-and-memory-use-after-news-downloads/"><u>Balancing CPU & Memory Use After News Downloads</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-license-validity-time-out-alerts-on-win10w11/"><u>Bypassing License Validity Time-Out Alerts on Win10/W11</u></a></li>
<li><a href="https://windows11.techidaily.com/cease-windows-logging-for-app-execution-dates/"><u>Cease Windows' Logging for App Execution Dates</u></a></li>
<li><a href="https://windows11.techidaily.com/clear-the-hurdle-of-ms-teams-error-80080300-with-actionable-steps/"><u>Clear the Hurdle of MS Teams Error 80080300 with Actionable Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/1719314513697-combat-snip-and-sketch-failures-a-guide-to-capturing-entire-display/"><u>Combat Snip & Sketch Failures: A Guide to Capturing Entire Display.</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-edge-computing-10-non-windows-app-favorites/"><u>Cutting-Edge Computing: 10 Non-Windows App Favorites</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-and-remedying-wins-error-messages/"><u>Deciphering & Remedying WINS Error Messages</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-vintage-of-a-windows-pc/"><u>Deciphering Vintage of a Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphring-and-diagnosing-predominant-windows-anydesk-problems/"><u>Deciphring and Diagnosing Predominant Windows AnyDesk Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-overcoming-0x80072af9-errors/"><u>Decoding and Overcoming 0X80072AF9 Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-resolving-directdraw-errors-on-win1011/"><u>Decoding and Resolving DirectDraw Errors on WIN10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/discovering-windows-11-browser-configuration/"><u>Discovering Windows 11 Browser Configuration</u></a></li>
<li><a href="https://extra-resources.techidaily.com/enhancing-tiktok-visuals-through-zoom-mastery/"><u>Enhancing TikTok Visuals Through Zoom Mastery</u></a></li>
<li><a href="https://fake-location.techidaily.com/fake-the-location-to-get-around-the-mlb-blackouts-on-nokia-c12-drfone-by-drfone-virtual-android/"><u>Fake the Location to Get Around the MLB Blackouts on Nokia C12 | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/flying-high-a-compreenasol-guide-to-cutting-edge-drone-editing-for-2024/"><u>Flying High  A Compreenasol Guide to Cutting-Edge Drone Editing for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-premium-steadicams-tailored-for-uav-filmmaking-scenarios/"><u>In 2024, Premium Steadicams Tailored for UAV Filmmaking Scenarios</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-ultimate-guide-to-catch-the-regional-located-pokemon-for-vivo-v29-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Ultimate Guide to Catch the Regional-Located Pokemon For Vivo V29 Pro | Dr.fone</u></a></li>
<li><a href="https://win-answers.techidaily.com/quick-solutions-repairing-your-madden-nfl-22-game-when-it-stops-responding/"><u>Quick Solutions: Repairing Your Madden NFL 22 Game When It Stops Responding</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/top-12-prominent-motorola-g24-power-fingerprint-not-working-solutions-by-drfone-android/"><u>Top 12 Prominent Motorola G24 Power Fingerprint Not Working Solutions</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-guide-restoring-audio-on-your-google-hangouts-device/"><u>Troubleshooting Guide: Restoring Audio on Your Google Hangouts Device</u></a></li>
<li><a href="https://techidaily.com/useful-ways-that-can-help-to-effectively-recover-deleted-files-from-tecno-spark-20c-by-fonelab-android-recover-data/"><u>Useful ways that can help to effectively recover deleted files from Tecno Spark 20C</u></a></li>
</ul></div>
