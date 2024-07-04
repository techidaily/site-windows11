---
title: Addressing Gaps in Time Remaining Estimates of Windows 11 Laptops
date: 2024-07-03T11:13:25.505Z
updated: 2024-07-04T11:13:25.505Z
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

## Where Did the Time Estimate Go?

 There are a few possible reasons why the time estimate has disappeared. The change often happens after upgrading to Windows 11, but even simply updating the OS can cause it. A later update may fix the issue, but that isn't always the case.

![battery icon tooltip in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/battery-time.jpg)

 It isn't entirely obvious what the root cause is. It could be a conflict in the Registry, which can occur during the update process. It also seems to have been deliberately disabled by Microsoft in some updates. Perhaps because the company is working on power and battery settings for a future update.

## How to Enable the Battery Time Estimate in the Registry

 Whatever the cause of its disappearance, the battery time estimate is still part of the OS. And with a bit of Registry tweaking, it can be brought back into view.

 As always, it is a good idea to [back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you make any changes. This is only a minor edit and shouldn't cause problems, but it's better to be safe than sorry.

1. Click Windows Search and type**Regedit** to find the Registry Editor. You don't need to choose Run as Administrator. Just select the search result.
2. With the Registry Editor open, navigate to: **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\Power** .
3. If there is no**Power** key, right-click on**Control** in the navigation panel, and select**New > Key** . Name the new registry key**Power** .  
![power values in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-key.jpg)
4. Right-click the Power key and select**New > DWORD (32-bit) Value** . Set the name of this DWORD as**EnergyEstimationEnabled** .
5. Double-click the new DWORD and set the Value data to**1** . Click**Ok** to close the window.  
![Changing value data in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-dword.jpg)
6. Repeat the previous two steps to create two more DWORD values called**EnergyEstimationDisabled** and**UserBatteryDischargeEstimator** .
7. You don't need to change the Value data for these, as they should default to a 0 value.

 Close the Registry Editor and restart your laptop. When you hover over the battery icon in the System Tray, it should show the estimated time remaining. And while you're at it, check out [how to add shortcuts to the System Tray](https://www.makeuseof.com/windows-11-add-shortcuts-menu-to-system-tray/) to make it even more useful.

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
<li><a href="https://windows11.techidaily.com/essential-free-drivers-windows-best-five-boosters/"><u>Essential Free Drivers: Windows' Best Five Boosters</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-roadblocks-activating-non-functional-scripts-in-windows/"><u>Overcoming Roadblocks: Activating Non-Functional Scripts in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/clarifying-the-concept-of-windows-ram-caching/"><u>Clarifying the Concept of Window's RAM Caching</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-a-non-responsive-resource-monitor-steps-for-windows-11-users/"><u>Navigating a Non-Responsive Resource Monitor: Steps for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-desktop-visibility-placing-this-pc-icon-front-and-center/"><u>Maximizing Desktop Visibility: Placing 'This PC' Icon Front and Center</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-non-operational-windows-defrag-tool/"><u>Troubleshooting Non-Operational Windows Defrag Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/time-to-get-back-on-track-recovering-windows-time-service/"><u>Time to Get Back on Track: Recovering Windows Time Service</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-stopping-auto-recommended-game-suggestion/"><u>Steps for Stopping Auto-Recommended Game Suggestion</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-the-barrier-of-windows-11-updates/"><u>Breaking Down the Barrier of Windows 11 Updates</u></a></li>
<li><a href="https://unlock-android.techidaily.com/a-complete-guide-to-oem-unlocking-on-honor-magic-6-by-drfone-android/"><u>A Complete Guide To OEM Unlocking on Honor Magic 6</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-elevating-your-webinar-footage-with-best-practices/"><u>[Updated] 2024 Approved  Elevating Your Webinar Footage with Best Practices</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-ps-color-enhancement-simplified-approaches/"><u>[Updated] PS Color Enhancement  Simplified Approaches</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-screen-sleeves-on-sony-a6400-block-video-playback/"><u>[New] Screen Sleeves on Sony A6400 Block Video Playback</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-essential-tactics-for-elevating-your-facebook-profile-ranks/"><u>[New] In 2024, Essential Tactics for Elevating Your Facebook Profile Ranks</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-guide-to-superior-youtube-commercials/"><u>2024 Approved  Guide to Superior YouTube Commercials</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-securing-smooth-iphone-video-playback-top-three-strategies/"><u>In 2024, Securing Smooth iPhone Video Playback  Top Three Strategies</u></a></li>
<li><a href="https://change-location.techidaily.com/latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-vivo-y28-5g-drfone-by-drfone-virtual-android/"><u>Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Vivo Y28 5G | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/why-your-honor-play-7t-screen-might-be-unresponsive-and-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Your Honor Play 7T Screen Might be Unresponsive and How to Fix It | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-top-4-sim-location-trackers-to-easily-find-your-lost-vivo-s18e-device-by-drfone-android/"><u>In 2024, Top 4 SIM Location Trackers To Easily Find Your Lost Vivo S18e Device</u></a></li>
</ul></div>
