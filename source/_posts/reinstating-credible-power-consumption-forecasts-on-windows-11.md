---
title: Reinstating Credible Power Consumption Forecasts on Windows 11
date: 2024-08-31T22:09:09.133Z
updated: 2024-09-01T22:09:09.133Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reinstating Credible Power Consumption Forecasts on Windows 11
excerpt: This Article Describes Reinstating Credible Power Consumption Forecasts on Windows 11
keywords: W11 Power Prediction,Credible PC Usage,Energy Efficiency Windows,Accurate W11 Stats,Forecasting Consumption,Reputed Power Estimate,Optimal Usage Windows
thumbnail: https://thmb.techidaily.com/865ed323eb71130c7276babe580275f4674927ba17ed6f4bfafe6ec23c46bab1.jpg
---

## Reinstating Credible Power Consumption Forecasts on Windows 11

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

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
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
<li><a href="https://on-screen-recording.techidaily.com/new-vsr-video-vaulter-reviews-comprehensive-guide/"><u>[New] VSR Video Vaulter Reviews  Comprehensive Guide</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-beats-that-last-a-lifetime-top-tiktok-hits-of-2024-you-cant-forget/"><u>[Updated] Beats That Last a Lifetime  Top TikTok Hits of 2024 You Can't Forget</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-real-time-skype-monitoring-with-live-obs-integration/"><u>[Updated] Real-Time Skype Monitoring with Live OBS Integration</u></a></li>
<li><a href="https://extra-hints.techidaily.com/capture-clarity-with-leading-photo-gridding-services/"><u>Capture Clarity with Leading Photo Gridding Services</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/elevate-your-editing-skills-with-pro-color-techniques-for-2024/"><u>Elevate Your Editing Skills with Pro Color Techniques for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-fixes-for-unresponsive-windows-defender-security-shield/"><u>Essential Fixes for Unresponsive Windows Defender Security Shield</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-network-issues-with-anydesk-in-win11/"><u>Fixing Network Issues with AnyDesk in WIn11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-remedy-the-usb-attachment-failure-in-virtualbox-instantly/"><u>How to Remedy the USB Attachment Failure in VirtualBox Instantly</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-unlock-icloud-activation-lock-and-icloud-account-on-iphone-se-2022-by-drfone-ios/"><u>How to Unlock iCloud Activation Lock and iCloud Account On iPhone SE (2022)?</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-expert-tips-download-youtube-playlists-in-minutes/"><u>In 2024, Expert Tips  Download YouTube Playlists in Minutes</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-locked-out-of-apple-iphone-8-plus-5-ways-to-get-into-a-locked-apple-iphone-8-plus-drfone-by-drfone-ios/"><u>In 2024, Locked Out of Apple iPhone 8 Plus? 5 Ways to get into a Locked Apple iPhone 8 Plus | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-top-10-airplay-apps-in-samsung-galaxy-s24-for-streaming-drfone-by-drfone-android/"><u>In 2024, Top 10 AirPlay Apps in Samsung Galaxy S24 for Streaming | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-android-windows-integration-for-webcams/"><u>Mastering Android-Windows Integration for Webcams</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-visual-quality-with-w11s-auto-hdr/"><u>Maximizing Visual Quality with W11's Auto HDR</u></a></li>
<li><a href="https://data-wizards.techidaily.com/nip-video-lag-in-the-bud-with-vlc/"><u>Nip Video Lag in the Bud with VLC</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-windows-launch-directly-engage-file-explorer-through-onedrive/"><u>Optimizing Windows Launch: Directly Engage File Explorer Through OneDrive</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcoming-recognition-failures-of-usb-gadgets-win-78/"><u>Overcoming Recognition Failures of USB Gadgets Win 7/8</u></a></li>
<li><a href="https://windows11.techidaily.com/power-through-print-settings-in-win11-quick-guide-max-48-chars/"><u>Power Through Print Settings in Win11 - Quick Guide (Max 48 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-and-easy-guide-for-turning-onoff-windows-key/"><u>Quick & Easy Guide for Turning On/Off Windows Key</u></a></li>
<li><a href="https://win-answers.techidaily.com/quick-guide-correct-the-easy-anti-cheat-not-installed-error-on-your-pc/"><u>Quick Guide: Correct the Easy Anti-Cheat Not Installed Error on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/safeguard-privacy-erasing-ms-defender-logs-in-windows-1011/"><u>Safeguard Privacy: Erasing MS Defender Logs in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/set-up-a-fast-safe-login-windows-hello-basics/"><u>Set Up a Fast, Safe Login: Windows Hello Basics</u></a></li>
<li><a href="https://windows11.techidaily.com/stepwise-strategy-to-erase-wsl-from-windows-11-operating-system/"><u>Stepwise Strategy to Erase WSL From Windows 11 Operating System</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-overcoming-windows-administrative-restriction-on-installers/"><u>Strategies for Overcoming Windows' Administrative Restriction on Installers</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-solutions-to-overcome-onedrives-immediate-folder-addition-error/"><u>Swift Solutions to Overcome OneDrive's Immediate Folder Addition Error</u></a></li>
<li><a href="https://windows11.techidaily.com/the-insiders-guide-accessing-onedrive-offline-on-windows/"><u>The Insider's Guide: Accessing OneDrive Offline on WINDOWS</u></a></li>
<li><a href="https://windows11.techidaily.com/the-new-era-ai-enhancements-in-windows-platforms/"><u>The New Era: AI Enhancements in Windows Platforms</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-ultimate-srt-file-craftsmanship-manual-for-2024/"><u>The Ultimate SRT File Craftsmanship Manual for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-unsupported-app-packages-on-windows-xp/"><u>Troubleshooting Unsupported App Packages on Windows XP</u></a></li>
<li><a href="https://tech-hub.techidaily.com/uninstalling-printer-software-in-windows-a-comprehensive-tutorial/"><u>Uninstalling Printer Software in Windows: A Comprehensive Tutorial</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-smooth-gaming-on-windows-eradicate-errors/"><u>Unleash Smooth Gaming on Windows, Eradicate Errors</u></a></li>
<li><a href="https://fox-that.techidaily.com/unresponsive-tablet-screen-dilemma-8-solutions-for-smooth-operation/"><u>Unresponsive Tablet Screen Dilemma: 8 Solutions for Smooth Operation</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-terminal-the-art-of-color-selection/"><u>Windows Terminal: The Art of Color Selection</u></a></li>
<li><a href="https://windows11.techidaily.com/winrar-archive-integrity-preventing-checksum-error-messages/"><u>WinRAR Archive Integrity: Preventing Checksum Error Messages</u></a></li>
</ul></div>
