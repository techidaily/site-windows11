---
title: Addressing Inaccuracy of Power Usage Predictor on Win 11 Devices
date: 2025-01-18T20:42:11.832Z
updated: 2025-01-22T16:22:58.876Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Inaccuracy of Power Usage Predictor on Win 11 Devices
excerpt: This Article Describes Addressing Inaccuracy of Power Usage Predictor on Win 11 Devices
keywords: Power Usage Prediction Errors,Win 11 Energy Consumption Mistakes,Accurate Power Estimation Software,Windows 11 Power Metering,Efficient PC Power Tracking,Power Miscalculation in Windows,Correcting Win Devices' Power Readings
thumbnail: https://thmb.techidaily.com/33c48593ec0173b68a8667f248e53142d39bc8c3611fadd3a7f85564f8ade76e.jpg
---

## Addressing Inaccuracy of Power Usage Predictor on Win 11 Devices

 Keeping track of how much charge remains in your laptop battery is easy. By default, hovering over the battery icon in the System Tray displays an estimate of battery time remaining, along with a percentage. Occasionally, the time estimate goes missing, leaving you to work out how much usage time you have left by percentage alone.

 Here's how to get that useful battery time remaining estimate showing again if it has vanished from your notebook.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlVkEwpjKKo?si=hXi-mchMaJvbnIzM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Where Did the Time Estimate Go?

 There are a few possible reasons why the time estimate has disappeared. The change often happens after upgrading to Windows 11, but even simply updating the OS can cause it. A later update may fix the issue, but that isn't always the case.

![battery icon tooltip in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/battery-time.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c17xsnbinCQ?si=xHKslFgC3QbxY4qW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 It isn't entirely obvious what the root cause is. It could be a conflict in the Registry, which can occur during the update process. It also seems to have been deliberately disabled by Microsoft in some updates. Perhaps because the company is working on power and battery settings for a future update.

## How to Enable the Battery Time Estimate in the Registry

 Whatever the cause of its disappearance, the battery time estimate is still part of the OS. And with a bit of Registry tweaking, it can be brought back into view.

 As always, it is a good idea to [back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you make any changes. This is only a minor edit and shouldn't cause problems, but it's better to be safe than sorry.

1. Click Windows Search and type**Regedit** to find the Registry Editor. You don't need to choose Run as Administrator. Just select the search result.
2. With the Registry Editor open, navigate to: **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\Power** .
3. If there is no**Power** key, right-click on**Control** in the navigation panel, and select**New > Key** . Name the new registry key**Power** .  
![power values in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-key.jpg)
4. Right-click the Power key and select**New > DWORD (32-bit) Value** . Set the name of this DWORD as**EnergyEstimationEnabled** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tPgf_wSdhS8?si=BHoH1ryaxmwk-8FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Double-click the new DWORD and set the Value data to**1** . Click**Ok** to close the window.  
![Changing value data in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-dword.jpg)
6. Repeat the previous two steps to create two more DWORD values called**EnergyEstimationDisabled** and**UserBatteryDischargeEstimator** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2NU63YqpVqw?si=uoJs0-nZYAkILqXx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. You don't need to change the Value data for these, as they should default to a 0 value.

 Close the Registry Editor and restart your laptop. When you hover over the battery icon in the System Tray, it should show the estimated time remaining. And while you're at it, check out [how to add shortcuts to the System Tray](https://www.makeuseof.com/windows-11-add-shortcuts-menu-to-system-tray/) to make it even more useful.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XoC2TGp1PLY?si=iH9xs76NhWn4pP-E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-info.techidaily.com/updated-hero5-black-meets-hero5-session-a-visual-verdict/"><u>[Updated] Hero5 Black Meets Hero5 Session – A Visual Verdict</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/approved-ace-your-edits-youtube-studios-time-saving-secrets-revealed/"><u>2024 Approved Ace Your Edits YouTube Studio's Time-Saving Secrets Revealed</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-balance-of-serene-visuals/"><u>2024 Approved The Balance of Serene Visuals</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-for-secure-nddrive-configuration-win11/"><u>Expert Tips for Secure NDDrive Configuration (Win11)</u></a></li>
<li><a href="https://windows11.techidaily.com/get-to-the-essentials-6-methods-of-boot-safe-mode-in-windows-11/"><u>Get to the Essentials: 6 Methods of Boot Safe Mode in Windows 11</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/immediate-imaging-swift-solution-to-no-signal-dilemma/"><u>Immediate Imaging: Swift Solution to No Signal Dilemma</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-craft-your-visual-narrative-top-10-iphoneandroid-screenshot-sticker-apps/"><u>In 2024, Craft Your Visual Narrative – Top 10 iPhone/Android Screenshot Sticker Apps</u></a></li>
<li><a href="https://article-helps.techidaily.com/mastering-numeric-adjustments-in-tiktok-videos/"><u>Mastering Numeric Adjustments in TikTok Videos</u></a></li>
<li><a href="https://some-tips.techidaily.com/no-more-fuss-effortlessly-sync-your-airpods-to-quest-audio-gear-in-peace/"><u>No More Fuss: Effortlessly Sync Your AirPods to Quest Audio Gear in Peace</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-unwanted-audio-app-utilization-issue-on-windows/"><u>Overcoming Unwanted Audio App Utilization Issue on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/personalize-windows-appearance-with-popular-photographs/"><u>Personalize Windows' Appearance with Popular Photographs</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-avoid-demanded-assets-alerts-on-windows-10and11/"><u>Troubleshooting: Avoid Demanded Assets Alerts on Windows 10&11</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-gpu-driver-issues-in-win1011/"><u>Unraveling GPU Driver Issues in WIN10/11</u></a></li>
<li><a href="https://ai-topics.techidaily.com/updated-what-is-an-ai-presentation-maker-for-2024/"><u>Updated What Is an AI Presentation Maker for 2024</u></a></li>
<li><a href="https://win-amazing.techidaily.com/whats-new-update-on-your-logitech-extreme-3d-driver/"><u>What’s New: Update on Your Logitech Extreme 지역 3D 프로 마우스 Driver</u></a></li>
<li><a href="https://windows11.techidaily.com/win-10w11-mastery-quick-paste-snippet-techniques/"><u>Win 10/W11 Mastery: Quick Paste Snippet Techniques</u></a></li>
</ul></div>

