---
title: Boldly Block Wi-Fi Signals in Windows
date: 2024-06-25T12:00:02.045Z
updated: 2024-06-26T12:00:02.045Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Boldly Block Wi-Fi Signals in Windows
excerpt: This Article Describes Boldly Block Wi-Fi Signals in Windows
keywords: BLOCK Wi-Fi Signal,Wi-Fi Security Window,Wi-Fi Interference Stop,Windows Wi-Fi Hide,Block Wi-Fi Windows Pro,Disable Wifi Windows,Wi-Fi Leak Prevention
thumbnail: https://thmb.techidaily.com/4fad5dfb068fa17bd11d3278f05324268f19f0e4e3fba2cd6b2af2a6f5ad615e.jpg
---

## Boldly Block Wi-Fi Signals in Windows

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/approaches-to-fix-failed-launch-of-lunar-client-in-windows/"><u>Approaches to Fix Failed Launch of Lunar Client in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/swipe-to-learn-comparing-windows-10-ui-with-windows-11/"><u>Swipe to Learn: Comparing Windows 10 UI with Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-to-windows-ease-of-access-in-5-steps/"><u>Navigating to Windows Ease of Access in 5 Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/invisible-disk-hiding-tricks-in-win11w10/"><u>Invisible Disk Hiding Tricks in Win11/W10</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-best-free-desktop-pass-gen-software/"><u>The Ultimate Guide to Best Free Desktop Pass Gen Software</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-performance-monitor-not-working-on-windows/"><u>How to Fix the Performance Monitor Not Working on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/nullify-specification-shortfalls-alerts-in-win11/"><u>Nullify Specification Shortfalls Alerts in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminate-loadlibrary-error-87-misconfiguration/"><u>Eliminate LoadLibrary Error 87 Misconfiguration</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-the-art-of-eating-10-social-media-staples/"><u>[Updated] 2024 Approved  The Art of Eating  10 Social Media Staples</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-high-quality-win11-screen-capture-pro/"><u>2024 Approved  High-Quality Win11 Screen Capture Pro</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-instagram-masterclass-top-5-suggestions-and-real-life-outcomes/"><u>[New] Instagram Masterclass  Top 5 Suggestions & Real-Life Outcomes</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-direct-approaches-to-storing-google-voice-communications/"><u>In 2024, Direct Approaches to Storing Google Voice Communications</u></a></li>
<li><a href="https://android-location.techidaily.com/3-effective-methods-to-fake-gps-location-on-android-for-your-tecno-spark-20-drfone-by-drfone-virtual/"><u>3 Effective Methods to Fake GPS location on Android For your Tecno Spark 20 | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-lost-data-of-apple-iphone-11-pro-max-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Lost Data of Apple iPhone 11 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-in-2024-step-by-step-volume-regulation-in-vlc-ensuring-consistent-sound-quality/"><u>New In 2024, Step-by-Step Volume Regulation in VLC Ensuring Consistent Sound Quality</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-and-where-to-find-a-shiny-stone-pokemon-for-vivo-v27e-drfone-by-drfone-virtual-android/"><u>In 2024, How and Where to Find a Shiny Stone Pokémon For Vivo V27e? | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unleashing-the-iphones-full-potential-with-10-composition-principles/"><u>[Updated] Unleashing the iPhone's Full Potential with 10 Composition Principles</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>