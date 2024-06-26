---
title: "Invisible to Others: Windows Network Concealment"
date: 2024-06-25T12:44:11.713Z
updated: 2024-06-26T12:44:11.713Z
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/top-solutions-for-windows-pin-access-issues-10plus11/"><u>Top Solutions for Windows PIN Access Issues (10+11)</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-second-shuffle-solved/"><u>Windows Second Shuffle Solved</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-win-ethernet-no-internet-error/"><u>Resolving Win Ethernet No Internet Error</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-compact-icons-arrangement-in-system-interface/"><u>Fixing Compact Icons Arrangement in System Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-requirement-errors-in-gaming/"><u>Bypassing Windows Requirement Errors in Gaming</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-win11-potential-essential-commands-and-tricks-with-nircmd/"><u>Unlock Win11 Potential: Essential Commands & Tricks with NirCmd</u></a></li>
<li><a href="https://windows11.techidaily.com/combat-the-frustration-7-methods-for-restoring-windows-notepad/"><u>Combat the Frustration: 7 Methods for Restoring Window's Notepad</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-the-digital-artisans-guide-mastering-screen-recordings-in-macos/"><u>In 2024, The Digital Artisan's Guide  Mastering Screen Recordings in macOS</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-in-2024-quicktime-video-speed-boost-a-step-by-step-tutorial/"><u>New In 2024, QuickTime Video Speed Boost A Step-by-Step Tutorial</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-podcasting-prowess-crafting-a-trendsetting-showcase/"><u>2024 Approved  Podcasting Prowess  Crafting a Trendsetting Showcase</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/the-ultimate-guide-to-cost-free-online-collaboration-tools-for-2024/"><u>The Ultimate Guide to Cost-Free Online Collaboration Tools for 2024</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/in-2024-tube-tallies-counting-the-top-10-watched-videos-on-twit/"><u>In 2024, Tube Tallies  Counting the Top 10 Watched Videos on Twit</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/data-recovery-recover-lost-data-from-blaze-2-5g-by-fonelab-android-recover-data/"><u>Data Recovery – recover lost data from Blaze 2 5G</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-how-to-send-a-snap-from-memoriescamera-roll-on-snapchat/"><u>In 2024, How to Send a Snap From Memories/Camera Roll on Snapchat</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ower-of-politeness-in-growing-your-audience-for-2024/"><u>The Power of Politeness in Growing Your Audience for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>