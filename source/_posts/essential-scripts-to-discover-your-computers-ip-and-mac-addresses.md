---
title: Essential Scripts to Discover Your Computer's IP & MAC Addresses
date: 2024-08-08T06:11:01.623Z
updated: 2024-08-09T06:11:01.623Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Essential Scripts to Discover Your Computer's IP & MAC Addresses
excerpt: This Article Describes Essential Scripts to Discover Your Computer's IP & MAC Addresses
keywords: Find IP Address,Mac Address Locator,Uncover MAC ID,Detect Network IP,Reveal System MAC,Identify Computer IP,Discover Device MAC
thumbnail: https://thmb.techidaily.com/1a08c8dedd48664d90b507bda304483e40c9a1d2dac0696255a8394fc453f16e.jpg
---

## Essential Scripts to Discover Your Computer's IP & MAC Addresses

 Have you been facing some network or troubleshooting issues on your PC? Or maybe you simply need to fix your access control or networking problems caused by your device or hardware. In cases like this, knowing your MAC or IP address will come in handy.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->
## How to Find Your IP or MAC Address on a Windows Using the PowerShell

 Figuring out your IP address using [PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) is easy. Here's how you can get started:

1. Head to the **Start menu** search bar, type in 'powershell,' and select the best match.
2. Once the PowerShell is up, type in the following command and hit **Enter**:  
`Get-NetIPAddress <code class="language-powershell" lang="powershell">-AddressFamily IPV4`

 That's it; as soon as you type in this command, the PowerShell will give you the IPv4 addresses of all network adapters of your Windows system. As you can see below, you will get your PC's IP address, subnet mask, default gateway, etc.

<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
![windows powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-3.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->
## Find the MAC Address on Your Windows

 Like your IP address, [finding out about your MAC address](https://www.makeuseof.com/how-to-find-mac-address-windows-11/) works somewhat similarly. Again, once you're inside the PowerShell, type in the following command on the shell and hit **Enter**:

`Get-NetAdapter`

 That's it; this command will give you the details about all the network adapters from your system, along with their MAC addresses. Look over at the "MacAddress" column, and you will get the address.

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### An Alternate Way to Find the MAC Address on Windows

 While the "Get-NetAdapter" will work in most cases, we'd understand that if you'd want to try a different approach for any reason. In cases like that, the "ipconfig" command is your second-best bet.

 In fact, the "ipconfig" will give you all the information, which can make your screen unnecessarily complicated. So it's important that you filter out the fluff, and only get the information that you need. For that, add the "findstr "Description Physical"" section at the end of your command.

 Here's how you can do that:

`ipconfig /all | findstr "Description Physical"  
<img alt="windows powershell" height="665" src="https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-4.jpg" width="1200" />`

 Your adapter will be listed along with its MAC address, referenced by "Description" and "Physical Address".

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
## Finding Your IP or MAC Address on Windows PC

 So that's all about your IP or MAC address on your Windows PC. Type in the above commands, and you will get your MAC or IP addresses instantly. Of course, PowerShell is just one way of doing that. For instance, you can even find out your IP address on Windows with both settings menu and Command prompt. Knowing all the different methods, then, will come in handy in places like this.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-hovers.techidaily.com/new-diving-into-the-depths-of-hdr-with-asus-pa32u/"><u>[New] Diving Into the Depths of HDR with ASUS PA32U</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-snap-and-save-securely-downloading-vids-from-twitter-for-2024/"><u>[New] Snap & Save  Securely Downloading Vids From Twitter for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-triller-demystified-a-comparative-look-at-unique-online-platforms/"><u>[New] Triller Demystified  A Comparative Look at Unique Online Platforms</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-in-2024-premium-steadicam-models-to-transform-your-dslr-filmmaking-experience/"><u>[Updated] In 2024, Premium Steadicam Models to Transform Your DSLR Filmmaking Experience</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-pro-video-setup-utilizing-your-logitech-webcam/"><u>[Updated] Pro Video Setup  Utilizing Your Logitech Webcam</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-unrestricted-display-save-tool-for-2024/"><u>[Updated] Unrestricted Display Save Tool for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-user-insights-on-vllo/"><u>[Updated] User Insights on VLLO</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-beyond-boundaries-channel-youtube-for-exciting-green-screens/"><u>2024 Approved  Beyond Boundaries  Channel Youtube for Exciting Green Screens</u></a></li>
<li><a href="https://tech-haven.techidaily.com/demystifying-codegpt-could-it-redefine-coding-standards/"><u>Demystifying CodeGPT: Could It Redefine Coding Standards?</u></a></li>
<li><a href="https://windows11.techidaily.com/easily-adjust-picture-resolution-in-windows-11-the-top-6-methods/"><u>Easily Adjust Picture Resolution in Windows 11: The Top 6 Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-word-lookups-for-newbies-to-win11/"><u>Efficient Word Lookups for Newbies to Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/effortlessly-access-the-microsoft-store/"><u>Effortlessly Access the Microsoft Store</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-desktop-8-winbubble-methods-for-window-tailoring/"><u>Elevate Your Desktop: 8 WinBubble Methods for Window Tailoring</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-low-sound-levels-for-external-speakers/"><u>Elevating Low Sound Levels for External Speakers</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminate-error-rebuild-failed-java-virtual-machine/"><u>Eliminate Error: Rebuild Failed Java Virtual Machine</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-boltguns-lags-winning-techniques-for-windows-users/"><u>Eliminating Boltgun's Lags: Winning Techniques for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-team-error-80080300-in-windows-11/"><u>Eliminating Team Error 80080300 in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-win1011-error-0xc0000001/"><u>Eliminating Win10/11 Error 0xC0000001</u></a></li>
<li><a href="https://windows11.techidaily.com/embarking-on-wintoys-journey-your-comprehensive-guide-to-windows-mastery/"><u>Embarking on WinToys Journey: Your Comprehensive Guide to Windows Mastery</u></a></li>
<li><a href="https://windows11.techidaily.com/enablingdisabling-wi-fi-cost-monitor-in-win11/"><u>Enabling/Disabling Wi-Fi Cost Monitor in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-night-vision-with-dark-mode-for-notepad-on-win-11/"><u>Enhance Night Vision with Dark Mode for Notepad on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-pc-master-distributed-transcoding-with-tdarr/"><u>Enhance PC: Master Distributed Transcoding with Tdarr</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-performance-with-customized-windows-11-configurations/"><u>Enhance Performance with Customized Windows 11 Configurations</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-productivity-unleash-potential-via-flow-launcher/"><u>Enhance Productivity: Unleash Potential via Flow Launcher</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-touchpad-navigation-efficiency-in-windows-os/"><u>Enhancing Touchpad Navigation Efficiency in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-user-identity-management-in-win11-pro/"><u>Enhancing User Identity Management in Win11 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-clear-voice-commands-with-xbox-and-windows/"><u>Ensuring Clear Voice Commands with Xbox & Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-clickable-window-previews-return/"><u>Ensuring Clickable Window Previews Return</u></a></li>
<li><a href="https://windows11.techidaily.com/escalate-typing-pace-via-windows-powertoys/"><u>Escalate Typing Pace via Windows' PowerToys</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-creators-uniting-for-marvels-digital-future/"><u>In 2024, Creators Uniting for Marvel's Digital Future</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-full-guide-on-mirroring-your-poco-x5-to-your-pcmac-drfone-by-drfone-android/"><u>In 2024, Full Guide on Mirroring Your Poco X5 to Your PC/Mac | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/non-rivalry-indicates-that-one-persons-consumption-doesnt-reduce-the-availability-for-others/"><u>Non-Rivalry Indicates that One Person’s Consumption Doesn’t Reduce the Availability for Others.</u></a></li>
<li><a href="https://review-topics.techidaily.com/play-mov-movies-on-galaxy-s23-tactical-edition-is-it-possible-by-aiseesoft-video-converter-play-mov-on-android/"><u>Play MOV movies on Galaxy S23 Tactical Edition, is it possible?</u></a></li>
<li><a href="https://facebook.techidaily.com/secure-a-unique-space-in-the-webs-sphere-fb-url-change/"><u>Secure a Unique Space in the Web's Sphere: FB URL Change</u></a></li>
<li><a href="https://win-blog.techidaily.com/stop-sims-3-from-crashing-on-your-computer-fast-and-simple-fixes/"><u>Stop Sims 3 From Crashing On Your Computer - Fast & Simple Fixes</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>