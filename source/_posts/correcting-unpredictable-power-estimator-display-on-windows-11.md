---
title: Correcting Unpredictable Power Estimator Display on Windows 11
date: 2024-06-25T12:11:48.795Z
updated: 2024-06-26T12:11:48.795Z
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

## How to Enable the Battery Time Estimate in the Registry

 Whatever the cause of its disappearance, the battery time estimate is still part of the OS. And with a bit of Registry tweaking, it can be brought back into view.

 As always, it is a good idea to[back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you make any changes. This is only a minor edit and shouldn't cause problems, but it's better to be safe than sorry.

1. Click Windows Search and type**Regedit** to find the Registry Editor. You don't need to choose Run as Administrator. Just select the search result.
2. With the Registry Editor open, navigate to: **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\Power** .
3. If there is no**Power** key, right-click on**Control** in the navigation panel, and select**New > Key** . Name the new registry key**Power** .  
![power values in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-key.jpg)
4. Right-click the Power key and select**New > DWORD (32-bit) Value** . Set the name of this DWORD as**EnergyEstimationEnabled** .
5. Double-click the new DWORD and set the Value data to**1** . Click**Ok** to close the window.  
![Changing value data in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-dword.jpg)
6. Repeat the previous two steps to create two more DWORD values called**EnergyEstimationDisabled** and**UserBatteryDischargeEstimator** .
7. You don't need to change the Value data for these, as they should default to a 0 value.

 Close the Registry Editor and restart your laptop. When you hover over the battery icon in the System Tray, it should show the estimated time remaining. And while you're at it, check out[how to add shortcuts to the System Tray](https://www.makeuseof.com/windows-11-add-shortcuts-menu-to-system-tray/) to make it even more useful.

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
<li><a href="https://windows11.techidaily.com/unlocking-windows-11-safe-mode-an-easy-six-step-plan/"><u>Unlocking Windows 11 Safe Mode: An Easy Six-Step Plan</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-lost-thermal-management-directive-for-pcs/"><u>Restoring Lost Thermal Management Directive for PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/future-proof-computing-with-top-windows-laptop-choices/"><u>Future-Proof Computing with Top Windows Laptop Choices</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-malfunctioning-outlook-mail-signals-on-pc/"><u>Mending Malfunctioning Outlook Mail Signals on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-powershell-to-break-free-from-windows-file-blocks/"><u>Mastering PowerShell to Break Free From Windows File Blocks</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-rejuvenate-your-windows-11-with-a-fresh-reboot/"><u>How to Rejuvenate Your Windows 11 with a Fresh Reboot</u></a></li>
<li><a href="https://windows11.techidaily.com/sudos-arrival-in-windows-os-explained/"><u>Sudo's Arrival in Windows OS Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-camera-access-notification-controls-on-win11/"><u>Mastering Camera Access Notification Controls on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-silent-mode-glitches-on-windows-word-reading-feature/"><u>Fix Silent Mode Glitches on Windows' Word Reading Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/no-more-erratic-arrows-fixes-for-the-frustrated/"><u>No More Erratic Arrows: Fixes for the Frustrated</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-can-i-catch-the-regional-pokemon-without-traveling-on-vivo-y02t-drfone-by-drfone-virtual-android/"><u>In 2024, How Can I Catch the Regional Pokémon without Traveling On Vivo Y02T | Dr.fone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-decoding-app-dynamics-an-in-depth-analysis-of-tiktok-and-snaps-similarities/"><u>[Updated] 2024 Approved  Decoding App Dynamics  An In-Depth Analysis of TikTok & Snap's Similarities</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-check-if-your-oppo-k11-5g-is-unlocked-by-drfone-android/"><u>How To Check if Your Oppo K11 5G Is Unlocked</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-creative-cinema-for-kids-bring-your-imagination-to-life/"><u>Updated 2024 Approved Creative Cinema for Kids Bring Your Imagination to Life</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/2024-approved-the-ultimate-guide-to-popular-sound-capture-software/"><u>2024 Approved The Ultimate Guide to Popular Sound Capture Software</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-top-rated-online-aspect-ratio-calculators-for-easy-use/"><u>Updated Top-Rated Online Aspect Ratio Calculators for Easy Use</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-essential-8-mirrorless-cams-for-professional-videographers-for-2024/"><u>[New] Essential 8 Mirrorless Cams for Professional Videographers for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-how-to-transfer-videos-and-photos-from-a-pc-to-an-iphone/"><u>In 2024, How to Transfer Videos and Photos From a PC to an iPhone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-the-pros-playbook-mastering-the-art-of-capturing-ps4-gaming/"><u>[Updated] 2024 Approved  The Pro's Playbook  Mastering the Art of Capturing PS4 Gaming</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-crafting-impressive-big-heads-on-tiktok-a-detailed-walkthrough-3-steps-for-2024/"><u>[Updated] Crafting Impressive Big Heads on TikTok  A Detailed Walkthrough (3 Steps) for 2024</u></a></li>
</ul></div>
