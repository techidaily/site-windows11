---
title: "Secure Your Wi-Fi: Blocking Networks on Windows PC"
date: 2024-12-15T23:49:34.244Z
updated: 2024-12-16T17:17:09.961Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Secure Your Wi-Fi: Blocking Networks on Windows PC"
excerpt: "This Article Describes Secure Your Wi-Fi: Blocking Networks on Windows PC"
keywords: Secure Wi-Fi Guard,Block Unauthorized Net,Protect PC Connectivity,Filter Windows Routers,Prevent IP Breaches,Network Safeguard Windows,Wi-Fi Security Settings
thumbnail: https://thmb.techidaily.com/7e2e77f0d86cd559dbfa986d906ed8c2ea52210199eb42f08b362eadc3328953.jpg
---

## Secure Your Wi-Fi: Blocking Networks on Windows PC

 By default, Windows displays all available Wi-Fi networks close to your device. Even if the networks are insecure, don't have parental controls enabled, or are just named inappropriately, Windows does not make an exception to block or hide them automatically.

 If you spot such a network and want to stop it from appearing among available Wi-Fi networks to prevent your children or yourself from viewing or accidentally connecting to it, here's how you can do that.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jjGL9wFdlbo?si=Vb1JgZqRXNc03UGG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Hide or Block a Wi-Fi Network on Windows

 Follow these steps to [use the Windows Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) to stop a Wi-Fi network from showing up among the available networks:

1. Type"Command Prompt" into Windows Search, right-click on the **Command Prompt** app and then click **Run as administrator**.
2. Note the full name of the network you intend to block or hide.
3. Enter the name of the Wi-Fi network next to the SSID field in the following command:  
`netsh wlan add filter permission=block ssid="add the name of the Wi-Fi network you want to block here" networktype=infrastructure`
4. Copy and paste the command into the Command Prompt app and press **Enter**.  
![Block the Wi-Fi Network By Running a Command in Command Prompt on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/block-the-wi-fi-network-by-running-a-command-in-command-prompt-on-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/l-SCWTWpegY?si=oxTsHQkIu1v4-I6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you see the message "The filter is added on the system successfully," the Wi-Fi network has been blocked, and it'll no longer appear in your Wi-Fi list. While the above steps will indeed block the Wi-Fi network, it will reappear among the available networks if the owner decides to [rename the Wi-Fi adapter](https://www.makeuseof.com/windows-11-rename-network-adapter/).

 If you change your mind and want to unblock the network you just blocked, enter the following command into the Command Prompt after entering the blocked network name:

`netsh wlan delete filter permission=block ssid="add the of the name of the Wi-Fi network you want to unblock here" networktype=infrastructure`

![Remove the Blocked Filter to Unblock the Wi-Fi Network Using the Windows Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/remove-the-blocked-filter-to-unblock-the-wi-fi-network-using-the-windows-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Jfq2Wx1Bcs?si=YQrYpTy0g4aV5QaO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/djPqRkskaBo?si=O6FEI-KVW0HwN417" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://youtube-blog.techidaily.com/n-2024-mastering-the-art-of-youtube-brand-creation-best-names-for-vloggers-and-filmmakers-limit-to-156-characters/"><u>[New] In 2024, Mastering the Art of YouTube Brand Creation Best Names for Vloggers & Filmmakers (Limit to 156 Characters)</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-2024-approved-advanced-editing-for-published-youtube-videos/"><u>[Updated] 2024 Approved Advanced Editing for Published YouTube Videos</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-top-10-engaging-vr-experiences-on-youtube/"><u>[Updated] Top 10 Engaging VR Experiences on Youtube</u></a></li>
<li><a href="https://windows11.techidaily.com/best-approaches-to-regulate-device-connections-in-windows/"><u>Best Approaches to Regulate Device Connections in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/camouflage-computing-integrating-archives-into-digital-image-win/"><u>Camouflage Computing: Integrating Archives Into Digital Image WIN</u></a></li>
<li><a href="https://tech-haven.techidaily.com/comparing-the-m1-and-m2-ipad-pro-choosing-the-perfect-tablet-for-your-needs/"><u>Comparing the M1 and M2 iPad Pro: Choosing the Perfect Tablet for Your Needs</u></a></li>
<li><a href="https://windows11.techidaily.com/downloading-woes-how-to-fix-windows-11-transfer-issues-2/"><u>Downloading Woes: How to Fix Windows 11 Transfer Issues (2)</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-steps-to-correct-windows-11-0x800f0922-error/"><u>Effective Steps to Correct Windows 11 0X800F0922 Error</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/fidelity-in-sound-security-in-earmuffs-reviewed/"><u>Fidelity in Sound, Security in Earmuffs Reviewed</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-make-the-most-of-your-apple-iphone-7-lock-screen-with-notifications-by-drfone-ios/"><u>How to Make the Most of Your Apple iPhone 7 Lock Screen with Notifications?</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-speedier-net-transfers-on-battlenet-windows/"><u>Mastering Speedier Net Transfers on Battle.net Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-black-screens-with-simple-win11-tweaks/"><u>Resolving Black Screens with Simple Win11 Tweaks</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-access-to-disabled-windows-apps/"><u>Restoring Access to Disabled Windows Apps</u></a></li>
<li><a href="https://win-news.techidaily.com/step-by-step-guide-transfer-data-from-your-ipad-mini-4-5-and-6-to-a-pc-or-icloud/"><u>Step-by-Step Guide: Transfer Data From Your iPad Mini (4, 5 & 6) to a PC or iCloud</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/the-ultimate-approach-to-preserving-your-ps4-experience/"><u>The Ultimate Approach to Preserving Your PS4 Experience</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/unlock-fb-videos-instant-mp4-format-conversion-for-2024/"><u>Unlock FB Videos Instant MP4 Format Conversion for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-and-edge-background-runs-how-to-control/"><u>Win11 and Edge Background Runs - How to Control</u></a></li>
</ul></div>

