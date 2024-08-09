---
title: Determining Public IP with System Commands, Windows
date: 2024-08-08T05:56:04.825Z
updated: 2024-08-09T05:56:04.825Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Determining Public IP with System Commands, Windows
excerpt: This Article Describes Determining Public IP with System Commands, Windows
keywords: Public IP Windows Find,Detecting Public IP,Windows IP Checker,Get Public IP Address,Identify Public Windows IP,Locate System IP,Access Windows Public IP
thumbnail: https://thmb.techidaily.com/e6c4e66a053f4adf51b38aa148d1e7f1b0fe37b06c40a2dc84de8d83be8e3fd3.jpg
---

## Determining Public IP with System Commands, Windows

 A computer or any device connected to the Internet has two types of IP addresses necessary to communicate. Each Internet-enabled device comes with a private IP address, whereas a public IP address, also known as the external IP address, is provided by your Internet Service Provider (ISP).

 While checking your private IP address is easy, knowing your public IP address can be necessary for many tasks, including remote access, server hosting, network troubleshooting, and geolocation services. Here we show you a few ways to retrieve your public IPv4/IPv6 information on Windows.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
## How to Check Your Private IP Address on Windows

<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![command prompt ipconfig private ip address](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/command-prompt-ipconfig-private-ip-address.jpg)

 Windows offers multiple ways to view your network information, including the IP address. For instance, you can easily [check your IP address from the Settings app](https://www.makeuseof.com/tag/find-ip-address-windows-10/). You can also use the Network and Sharing Center in Control Panel or dig a little bit in the Task Manager’s Performance tab to access your system’s network details.

 But if you would rather skip multiple clicks and are comfortable with Command Prompt, the ipconfig (Internet Protocol configuration) command is all you need. It is easy to remember and shows more information quickly than the Settings app.

 Follow these steps to get your Private IP address using Command Prompt:

1. Press the **Win** key, and type **cmd**. From the search result, click on **Command Prompt**.
2. Next, type the following command in the Command Prompt window and press Enter:  
`ipconfig`
3. The output will display a host of network information. Look for the IPv4 address for your Ethernet or Wireless LAN adapter to identify your private IP address.
4. If you need complete information, including NetBIOS over TCPIP, DHCP status, and Physical IP address, use the following command instead:  
`Ipconfig /all`
5. You’ll likely see multiple network adapter entries with unique IP addresses. This is usually due to your computer having multiple network adapters, including Ethernet, Wireless LAN, and vEthernet switches.

 If you need to share the output for troubleshooting purposes, you can export the output to a text file. In Command Prompt, run **ipconfig > NetworkInfo.txt** to save the output to a **NetworkInfo.text** file. By default, it is saved to the **C:\\Users\\Username** directory.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
## How to Get Your Public IP Address on Windows

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->
![Command Prompt running Curl command showing Public IP Address on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/command-prompt-public-ip-address-curl.jpg)

 Unlike the private IP address, the **ipconfig** command cannot retrieve the public IP address of your ISP. Instead, you’ll need to [use the curl command-line utility to make HTTP requests](https://www.makeuseof.com/curl-how-make-http-requests/) using a third-party service, like ifconfig.me, to obtain IP address mapping information.

 The newer versions of the OS, Windows 10 and 11, come with the curl utility built-in. If you are using an older version, you may need to install curl for Windows to run the utility.

 Follow these steps to get the public IP address using Command Prompt:

1. Press **Win + R**, type **cmd** and click **OK** to [open Command Prompt](https://www.makeuseof.com/windows-11-open-command-prompt/)
2. Type the following command in the Command Prompt window and press Enter:  
`curl ifconfig.me`
3. The above command sends an HTTP request to the **ifconfig.me** server, which returns your public IP address information. Similarly, you can visit the **ifconfig.me** URL using your web browser to view your public IP address.
4. That said, if the **ifconfig.me** command doesn’t return a public IPv6 address, use the following command instead:  
`nslookup myip.opendns.com resolver1.opendns.com`
5. The above command uses the **nslookup** command-line utility to retrieve your public IP address using the OpenDNS service. Your public IPv6 address will look something like this 2401:\*\*00:1c08:55f0:594b:cdbe:\*\*\*\*.\*\*\*\*.

 If you check your public IPv6 address again after a few hours or days—depending on the router's configuration—you may notice a different IPv6 address. Due to privacy concerns, your router dynamically assigns and changes the IPv6 address for all connected devices.

<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
## Online Tools to Get Your Public IP Address

![whatismyip online public ip address tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/whatismyip-online-public-ip-address-tool.jpg)

 If you prefer a more intuitive experience, you can use online web services that can provide information on your network configuration. These services can also detect the ISP location and other information, including the user agent.

 Online services to view public IP addresses:

* **[WhatIsMyIP](https://www.whatismyip.com/)**: A simple and intuitive web service to view your public IPv4 and IPv6 addresses. In addition, it also shows your ISP’s location and name.
* [**My External IP**](https://myexternalip.com/): A barebone web app that can detect your public IPv4 address and Port.
* **Use a search engine**: If you don’t want to remember another website to do basic stuff, try your search engine. Type “What’s my IP” in Google or Bing search to get your public IPv4/IPv6 address quickly.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->
## Many Ways to Check Your Public IP Address on Windows

 Whether you want to perform remote access or set up a gaming server, you may need to share your public IP address to allow others to connect to your network. Fortunately, plenty of web services allow you to check your network details using Command Prompt and online tools.

 While checking your private IP address is easy, knowing your public IP address can be necessary for many tasks, including remote access, server hosting, network troubleshooting, and geolocation services. Here we show you a few ways to retrieve your public IPv4/IPv6 information on Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-record-videos.techidaily.com/new-cutting-edge-concepts-for-captivating-youtube-video-thumbnails-for-2024/"><u>[New] Cutting-Edge Concepts for Captivating YouTube Video Thumbnails for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-smartcapture-hd-v2/"><u>[New] In 2024, SmartCapture HD V2</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-top-10-customizable-screenshot-tools-for-gamers/"><u>[New] In 2024, Top 10 Customizable Screenshot Tools for Gamers</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-strategy-envelope-market-success-inside-out/"><u>[New] Strategy Envelope  Market Success Inside Out</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-unboxing-unveiled-enhancing-customer-experiences/"><u>[New] Unboxing Unveiled  Enhancing Customer Experiences</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-2024-approved-boost-traffic-critical-youtube-seo-instruments-for-video-success/"><u>[Updated] 2024 Approved  Boost Traffic  Critical YouTube SEO Instruments for Video Success</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-premiere-smart-goggles-craftsmen/"><u>[Updated] 2024 Approved  Premiere Smart Goggles Craftsmen</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-cut-out-facebook-video-2023-edition-mobile-friendly/"><u>[Updated] Cut Out Facebook Video  2023 Edition, Mobile-Friendly</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-direct-webcam-streaming-with-vlc-for-2024/"><u>[Updated] Direct Webcam Streaming with VLC for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-achieving-virality-youtube-promotion-no-cost-involved/"><u>[Updated] In 2024, Achieving Virality  YouTube Promotion No Cost Involved</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-loudness-in-the-void-breaking-soundless-twitter-vids/"><u>[Updated] In 2024, Loudness in the Void  Breaking Soundless Twitter Vids</u></a></li>
<li><a href="https://windows11.techidaily.com/easing-out-of-the-eclipse-ending-dark-mode-anomaly/"><u>Easing Out of the Eclipse: Ending Dark Mode Anomaly</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-way-installing-google-play-on-win11/"><u>Easy Way: Installing Google Play on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiency-boost-for-winwms-excessive-graphics-use/"><u>Efficiency Boost for WinWM's Excessive Graphics Use</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-energy-use-with-windows-pcs/"><u>Efficient Energy Use with Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-drag-fixes-for-your-win11-desktop/"><u>Effortless Drag Fixes for Your Win11 Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/effortlessly-switching-files-between-formats-in-windows/"><u>Effortlessly Switching Files Between Formats in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-development-workflow-navigating-windows-11s-dev-drive/"><u>Elevate Development Workflow: Navigating Windows 11'S Dev Drive</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-windows-productivity-the-best-tech-tools-for-success/"><u>Elevate Windows Productivity: The Best Tech Tools for Success</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-blackout-phenomenon-in-windows-titles/"><u>Eliminating Blackout Phenomenon in Windows Titles</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-common-windows-installer-problems/"><u>Eliminating Common Windows Installer Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-driver-enforcement-loading-unsigned-on-windows-108/"><u>Eliminating Driver Enforcement: Loading Unsigned On Windows 10/8</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-faulty-devices-from-system-logs-windows-1011/"><u>Eliminating Faulty Devices From System Logs: Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-genuineness-errors-in-adobe-windows/"><u>Eliminating Genuineness Errors in Adobe Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-read-only-files-a-guide-for-windows-11-users/"><u>Eliminating Read-Only Files: A Guide for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-steams-content-server-unreachable-problem-in-windows/"><u>Eliminating Steam's Content Server Unreachable Problem in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-voice-typing-glitches-in-windows-11-error-code-0x80049dd3/"><u>Eliminating Voice Typing Glitches in Windows 11 (Error Code: 0X80049DD3)</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-windows-error-0x80072f8f-0x20000/"><u>Eliminating Windows Error: 0X80072f8f-0x20000</u></a></li>
<li><a href="https://windows11.techidaily.com/embellishing-windows-tray-adding-number-lock-symbols/"><u>Embellishing Windows Tray: Adding Number Lock Symbols</u></a></li>
<li><a href="https://windows11.techidaily.com/embrace-world-typography-on-windows-font-guide/"><u>Embrace World Typography on Windows - Font Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/embracing-linguistic-diversity-with-windows-fonts/"><u>Embracing Linguistic Diversity with Windows Fonts</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-your-subnet-configuration-in-win11/"><u>Enhance Your Subnet Configuration in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-graphics-memory-capability-for-hogwarts-virtual-learning-experience/"><u>Enhancing Graphics Memory Capability for Hogwarts Virtual Learning Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-system-analysis-widgets-for-hardware-monitoring/"><u>Enhancing System Analysis: Widgets for Hardware Monitoring</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-touchscreen-accuracy-windows-11-tutorial/"><u>Enhancing Touchscreen Accuracy: Windows 11 Tutorial</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-visibility-notifications-for-win11-webcam-use/"><u>Enhancing Visibility: Notifications for Win11 WebCam Use</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-windowed-discords-query-system/"><u>Enhancing Windowed Discord's Query System</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-digital-security-best-windows-cryptography-picks-148-chars/"><u>Ensuring Digital Security: Best Window's Cryptography Picks (148 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicating-screen-annoyances-in-sonic-frontiers-on-windows-11/"><u>Eradicating Screen Annoyances in Sonic Frontiers on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/erase-system-misses-message-on-windows-os/"><u>Erase System Misses Message on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/error-code-x80246007-fixing-windows-update-issues/"><u>Error Code X80246007: Fixing WIndows Update Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-app-list-for-seamless-os-transition-from-apple-to-windows/"><u>Essential App List for Seamless OS Transition From Apple to Windows</u></a></li>
<li><a href="https://tech-hub.techidaily.com/exploring-ais-potential-with-prompt-engineering-careers/"><u>Exploring AI's Potential with Prompt Engineering Careers</u></a></li>
<li><a href="https://some-techniques.techidaily.com/financial-free-editing-the-ultimate-guide-to-fcp-for-2024/"><u>Financial-Free Editing  The Ultimate Guide to FCP for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/-to-rapid-or-slowdown-youtubes-playback-adjustments-for-2024/"><u>Guide to Rapid or Slowdown  YouTube's Playback Adjustments for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-cards-of-nokia-c12-plus-without-puk-codes-by-drfone-android/"><u>How To Unlock SIM Cards Of Nokia C12 Plus Without PUK Codes</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-4-ways-to-unlock-iphone-14-plus-to-use-usb-accessories-without-passcode-by-drfone-ios/"><u>In 2024, 4 Ways to Unlock iPhone 14 Plus to Use USB Accessories Without Passcode</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-a-user-friendly-guide-to-board-integration-in-desktopiosandroid-zoom-meetings/"><u>In 2024, A User-Friendly Guide to Board Integration in Desktop/iOS/Android Zoom Meetings</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-dose-life360-notify-me-when-someone-checks-my-location-on-oppo-a38-drfone-by-drfone-virtual-android/"><u>In 2024, Dose Life360 Notify Me When Someone Checks My Location On Oppo A38? | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-immersive-experience-logging-top-tips-and-techniques-for-minecraft-recordings/"><u>In 2024, Immersive Experience Logging  Top Tips & Techniques for Minecraft Recordings</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-premium-choices-in-video-calling-platforms-for-tech-users/"><u>In 2024, Premium Choices in Video Calling Platforms for Tech Users</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-the-ultimate-checklist-for-using-firefoxs-popup-window/"><u>In 2024, The Ultimate Checklist for Using Firefox's Popup Window</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-circle-everything-you-need-to-know-on-realme-gt-3-drfone-by-drfone-virtual-android/"><u>Life360 Circle Everything You Need to Know On Realme GT 3 | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/set-your-preferred-job-location-on-linkedin-app-of-your-oneplus-nord-ce-3-lite-5g-drfone-by-drfone-virtual-android/"><u>Set Your Preferred Job Location on LinkedIn App of your OnePlus Nord CE 3 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/stepwise-protocols-for-capturing-superior-vimeo-content-for-2024/"><u>Stepwise Protocols for Capturing Superior Vimeo Content for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/the-ultimate-vision-quest-samsung-galaxy-s8s-4k-prowess/"><u>The Ultimate Vision Quest  Samsung Galaxy S8's 4K Prowess</u></a></li>
</ul></div>
