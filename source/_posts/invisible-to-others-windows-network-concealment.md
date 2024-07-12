---
title: "Invisible to Others: Windows Network Concealment"
date: 2024-07-11T22:07:57.104Z
updated: 2024-07-12T22:07:57.104Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Invisible to Others: Windows Network Concealment"
excerpt: "This Article Describes Invisible to Others: Windows Network Concealment"
keywords: Hidden Windows NET,NET Conceal Tech,InvisCon Windows,Stealthed Net Sys,Others' Vision NET,Network Anonware,Secretive NETOps
thumbnail: https://thmb.techidaily.com/865974c7bb05387b6277d30c79ecdc49aad19ee23c97d33e5069a1776373f52c.jpg
---

## Invisible to Others: Windows Network Concealment

 By default, Windows displays all available Wi-Fi networks close to your device. Even if the networks are insecure, don't have parental controls enabled, or are just named inappropriately, Windows does not make an exception to block or hide them automatically.

 If you spot such a network and want to stop it from appearing among available Wi-Fi networks to prevent your children or yourself from viewing or accidentally connecting to it, here's how you can do that.

## How to Hide or Block a Wi-Fi Network on Windows

 Follow these steps to [use the Windows Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) to stop a Wi-Fi network from showing up among the available networks:

1. Type"Command Prompt" into Windows Search, right-click on the **Command Prompt** app and then click **Run as administrator**.
2. Note the full name of the network you intend to block or hide.
3. Enter the name of the Wi-Fi network next to the SSID field in the following command:  
`netsh wlan add filter permission=block ssid="add the name of the Wi-Fi network you want to block here" networktype=infrastructure`
4. Copy and paste the command into the Command Prompt app and press **Enter**.  
![Block the Wi-Fi Network By Running a Command in Command Prompt on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/block-the-wi-fi-network-by-running-a-command-in-command-prompt-on-windows.jpg)

 If you see the message "The filter is added on the system successfully," the Wi-Fi network has been blocked, and it'll no longer appear in your Wi-Fi list. While the above steps will indeed block the Wi-Fi network, it will reappear among the available networks if the owner decides to [rename the Wi-Fi adapter](https://www.makeuseof.com/windows-11-rename-network-adapter/).

 If you change your mind and want to unblock the network you just blocked, enter the following command into the Command Prompt after entering the blocked network name:

`netsh wlan delete filter permission=block ssid="add the of the name of the Wi-Fi network you want to unblock here" networktype=infrastructure`

![Remove the Blocked Filter to Unblock the Wi-Fi Network Using the Windows Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/remove-the-blocked-filter-to-unblock-the-wi-fi-network-using-the-windows-command-prompt.jpg)

## Block Suspicious Wi-Fi Networks on Windows

 When a network is named inappropriately or looks suspicious owing to the lack of a password or protection, blocking it becomes imperative. Hopefully, now you know how to block and unblock a Wi-Fi network in the Command Prompt by running simple commands.

 While blocking other networks is essential, securing your network from prying eyes is equally important in maintaining your security and privacy.

 If you spot such a network and want to stop it from appearing among available Wi-Fi networks to prevent your children or yourself from viewing or accidentally connecting to it, here's how you can do that.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/avoid-errors-manage-deps-for-virtualbox-on-windows/"><u>Avoid Errors: Manage Deps for VirtualBox on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/bold-stealth-for-your-wi-fi-on-windows-pcs/"><u>Bold Stealth for Your Wi-Fi on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/cant-insert-new-cells-in-microsoft-excel-for-windows-try-these-fixes/"><u>Can’t Insert New Cells in Microsoft Excel for Windows? Try These Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-security-the-art-of-updating-gpo-in-windows/"><u>Boosting Security: The Art of Updating GPO in Windows</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-optimizing-visual-content-adding-black-bar-and-box-to-facebook-videos/"><u>[New] Optimizing Visual Content  Adding Black Bar & Box to Facebook Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/accessing-stealthed-elements-in-windows-11-ui/"><u>Accessing Stealthed Elements in Windows 11 UI</u></a></li>
<li><a href="https://windows11.techidaily.com/6-common-windows-screen-resolution-issues-and-fixes/"><u>6 Common Windows Screen Resolution Issues and Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerating-epic-launcher-on-pcs-a-quick-guide/"><u>Accelerating Epic Launcher on PCs: A Quick Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/check-if-your-computer-meets-new-win11-criteria/"><u>Check if Your Computer Meets New Win11 Criteria</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-innovating-color-grading-with-new-lut-techniques/"><u>2024 Approved  Innovating Color Grading with New LUT Techniques</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-downgrade-iphone-8-plus-to-the-previous-iosipados-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade iPhone 8 Plus to the Previous iOS/iPadOS Version? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-unintended-snipping-tool-launch-via-prtsc-on-win-11/"><u>Avoid Unintended Snipping Tool Launch via PrtSc on Win 11</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-google-frp-lock-on-asus-rog-phone-7-ultimate-devices-by-drfone-android/"><u>In 2024, How to Bypass Google FRP Lock on Asus ROG Phone 7 Ultimate Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-personalized-settings-alomwares-pathway-to-customization/"><u>Achieve Personalized Settings - AlomWare's Pathway to Customization</u></a></li>
<li><a href="https://windows11.techidaily.com/christmas-theme-makeovers-for-windows-11/"><u>Christmas Theme Makeovers for Windows 11</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-2024-approved-comprehensive-guide-to-effective-multiframe-use-in-edge/"><u>[Updated] 2024 Approved  Comprehensive Guide to Effective Multiframe Use in Edge</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/reassert-true-look-corrected-video-error-for-2024/"><u>Reassert True Look  Corrected Video Error for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensive-overview-using-bluescreenview/"><u>A Comprehensive Overview: Using BlueScreenView</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-cpu-utilization-checkers/"><u>Advanced CPU Utilization Checkers</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-failure-of-services-on-windows-with-error-1053-fixes/"><u>Avoiding Failure of Services on Windows with Error 1053 Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-boot-speed-with-simple-steps-in-windows-11-setup/"><u>Boosting Boot Speed with Simple Steps in Windows 11 Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/achieving-a-crystal-clarity-on-your-windows-taskbar/"><u>Achieving a Crystal Clarity on Your Windows Taskbar</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-creative-reactors-the-10-premier-video-responses-for-2024/"><u>[New] Creative Reactors  The 10 Premier Video Responses for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-the-cycle-how-to-fix-your-disconnected-ps4-remote-control-on-windows/"><u>Breaking the Cycle: How to Fix Your Disconnected PS4 Remote Control on Windows</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-innovative-10-ideas-thatll-boost-your-brand-on-igtv/"><u>[New] In 2024, Innovative 10 Ideas That'll Boost Your Brand on IGTV</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/mac-voice-recording-made-simple-essential-steps-for-crystal-clear-recordings-for-2024/"><u>Mac Voice Recording Made Simple Essential Steps for Crystal Clear Recordings for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-streamlining-vimeo-uploads-from-moviemaker-projects/"><u>[Updated] In 2024, Streamlining Vimeo Uploads From Moviemaker Projects</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-pixelmaster-elite-os-xwin-edition/"><u>[Updated] In 2024, PixelMaster Elite  OS X/Win Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-error-the-msvcr120dll-is-missing/"><u>Addressing Windows Error: The 'Msvcr120_dll' Is Missing</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-the-ultimate-shortcut-to-instagram-video-connectivity/"><u>[Updated] 2024 Approved  The Ultimate Shortcut to Instagram Video Connectivity</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-windows-11-heres-how-to-verify/"><u>Activating Windows 11? Here's How to Verify</u></a></li>
<li><a href="https://windows11.techidaily.com/a-compre-written-in-the-stars-mastering-your-laptops-touchscreen-precision/"><u>A Compre Written in the Stars: Mastering Your Laptop’s Touchscreen Precision</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/mastery-manual-downloading-hd-videos-on-todays-digital-landscapes-for-2024/"><u>Mastery Manual  Downloading HD Videos on Today's Digital Landscapes for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/1719374504396-dive-into-the-depth-of-complete-screenshots-via-windows-snipping-tool/"><u>Dive Into the Depth of Complete Screenshots via Windows' Snipping Tool.</u></a></li>
<li><a href="https://windows11.techidaily.com/calibrating-your-laptops-touch-response-for-maximum-comfort/"><u>Calibrating Your Laptop's Touch Response for Maximum Comfort</u></a></li>
<li><a href="https://windows11.techidaily.com/a-simple-guide-for-correcting-lsassexe-issue/"><u>A Simple Guide for Correcting 'lsass.exe' Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/adding-faithful-functions-to-windows-ui-tools/"><u>Adding Faithful Functions to Windows' UI Tools</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-launchpad-for-newcomers-creating-a-successful-product-evaluation-vlog/"><u>2024 Approved  Launchpad for Newcomers  Creating a Successful Product Evaluation Vlog</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-mcuicnt-file-execution-failure-on-windows/"><u>Addressing McUICnt File Execution Failure on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-panic-recover-lost-data-with-these-steps/"><u>Avoid Panic, Recover Lost Data with These Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/best-wsl-2-methods-for-efficient-windows-coding/"><u>Best WSL 2 Methods for Efficient Windows Coding</u></a></li>
</ul></div>
