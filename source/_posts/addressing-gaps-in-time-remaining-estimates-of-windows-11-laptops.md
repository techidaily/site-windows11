---
title: Addressing Gaps in Time Remaining Estimates of Windows 11 Laptops
date: 2025-01-19T20:07:12.471Z
updated: 2025-01-22T19:56:10.140Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Gaps in Time Remaining Estimates of Windows 11 Laptops
excerpt: This Article Describes Addressing Gaps in Time Remaining Estimates of Windows 11 Laptops
keywords: Win11 RM Timing Errors,Windows 11 Time Estimate,Laptop Time Remaining Gaps,Win11 Time Accuracy,Windows 11 Usage Tracking,OS Time Predictions Errors,Laptops Time Management Windows
thumbnail: https://thmb.techidaily.com/3ee1033fc4776708d60168535df9ce0ace02b9d450e390888f83793293d3623b.jpg
---

## Addressing Gaps in Time Remaining Estimates of Windows 11 Laptops

 Keeping track of how much charge remains in your laptop battery is easy. By default, hovering over the battery icon in the System Tray displays an estimate of battery time remaining, along with a percentage. Occasionally, the time estimate goes missing, leaving you to work out how much usage time you have left by percentage alone.

 Here's how to get that useful battery time remaining estimate showing again if it has vanished from your notebook.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LBCobAYzzcc?si=J3eSTQ3AdyxWAjGo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Where Did the Time Estimate Go?

 There are a few possible reasons why the time estimate has disappeared. The change often happens after upgrading to Windows 11, but even simply updating the OS can cause it. A later update may fix the issue, but that isn't always the case.

![battery icon tooltip in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/battery-time.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=EdMRoNAFi0Q6mP7G" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 It isn't entirely obvious what the root cause is. It could be a conflict in the Registry, which can occur during the update process. It also seems to have been deliberately disabled by Microsoft in some updates. Perhaps because the company is working on power and battery settings for a future update.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JlX-G8rBs1w?si=iIhUoWAq5x3YK9rA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Enable the Battery Time Estimate in the Registry

 Whatever the cause of its disappearance, the battery time estimate is still part of the OS. And with a bit of Registry tweaking, it can be brought back into view.

 As always, it is a good idea to [back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you make any changes. This is only a minor edit and shouldn't cause problems, but it's better to be safe than sorry.

1. Click Windows Search and type**Regedit** to find the Registry Editor. You don't need to choose Run as Administrator. Just select the search result.
2. With the Registry Editor open, navigate to: **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\Power** .
3. If there is no**Power** key, right-click on**Control** in the navigation panel, and select**New > Key** . Name the new registry key**Power** .  
![power values in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-key.jpg)
4. Right-click the Power key and select**New > DWORD (32-bit) Value** . Set the name of this DWORD as**EnergyEstimationEnabled** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q-mXUpVQijU?si=f1MzflPJ8-bD2_iQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Double-click the new DWORD and set the Value data to**1** . Click**Ok** to close the window.  
![Changing value data in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-dword.jpg)
6. Repeat the previous two steps to create two more DWORD values called**EnergyEstimationDisabled** and**UserBatteryDischargeEstimator** .
7. You don't need to change the Value data for these, as they should default to a 0 value.

 Close the Registry Editor and restart your laptop. When you hover over the battery icon in the System Tray, it should show the estimated time remaining. And while you're at it, check out [how to add shortcuts to the System Tray](https://www.makeuseof.com/windows-11-add-shortcuts-menu-to-system-tray/) to make it even more useful.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/l-SCWTWpegY?si=oxTsHQkIu1v4-I6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-download-premium-quality-designs-at-no-cost-for-youtube-creators/"><u>[Updated] In 2024, Download Premium-Quality Designs at No Cost – For YouTube Creators</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-journey-to-picture-perfection-iphone-tips-for-stunning-skylines/"><u>[Updated] Journey to Picture Perfection IPhone Tips for Stunning Skylines</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-peekintobettercams-beyond-mycam-for-2024/"><u>[Updated] PeekIntoBetterCams Beyond MyCam for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-capturing-your-desktop-in-winoses-effortlessly/"><u>2024 Approved Capturing Your Desktop in WinOSes Effortlessly</u></a></li>
<li><a href="https://win-bits.techidaily.com/achieve-optimal-security-five-methods-to-reinstatereset-ntfs-rights-in-windows-11/"><u>Achieve Optimal Security: Five Methods to Reinstate/Reset NTFS Rights in Windows 11</u></a></li>
<li><a href="https://win-blog.techidaily.com/bypassing-connection-glitches-a-guide-to-successful-hitman-n-gameplay/"><u>Bypassing Connection Glitches: A Guide to Successful Hitman N Gameplay</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-5-easy-ways-to-change-location-on-youtube-tv-on-apple-iphone-11-drfone-by-drfone-virtual-ios/"><u>In 2024, 5 Easy Ways to Change Location on YouTube TV On Apple iPhone 11 | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-10-best-spy-watches-for-your-oppo-k11x-drfone-by-drfone-virtual-android/"><u>In 2024, Top 10 Best Spy Watches For your Oppo K11x | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/method-to-turn-off-geforce-graphic-overlay-on-pc/"><u>Method to Turn Off GeForce Graphic Overlay on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-to-safest-win-friendly-free-software-deals/"><u>Navigating to Safest Win-Friendly Free Software Deals</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-disabled-graphics-on-steam-os/"><u>Quick Fixes for Disabled Graphics on Steam OS</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reasons-for-tecno-spark-20-pro-stuck-on-boot-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Tecno Spark 20 Pro Stuck on Boot Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-sequence-errors-for-running-tasks-windows-guide/"><u>Resolving Sequence Errors for Running Tasks: Windows Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/screen-recording-and-audio-integration-the-ultimate-guide-to-the-snipping-tool-max-156/"><u>Screen Recording & Audio Integration: The Ultimate Guide to the Snipping Tool (Max 156)</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-revive-frozen-windows-terminal-apps/"><u>Strategies to Revive Frozen Windows Terminal Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/strategizing-onedrives-positioning-within-windows-directory-space/"><u>Strategizing OneDrive's Positioning Within Windows Directory Space</u></a></li>
<li><a href="https://some-tips.techidaily.com/the-future-of-subscription-models-are-consumers-ready-for-20-monthly-fees-for-exclusive-tech-know-how/"><u>The Future of Subscription Models: Are Consumers Ready for $20 Monthly Fees for Exclusive Tech Know-How?</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-resolving-windows-disk-management-crashes/"><u>Tips: Resolving Windows Disk Management Crashes</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-windows-0x80242016-update-issue/"><u>Unraveling Window's 0X80242016 Update Issue</u></a></li>
</ul></div>

