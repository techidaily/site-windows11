---
title: Demystifying Your Global IP on WIN OS via CLI
date: 2024-07-11T21:41:13.760Z
updated: 2024-07-12T21:41:13.760Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Demystifying Your Global IP on WIN OS via CLI
excerpt: This Article Describes Demystifying Your Global IP on WIN OS via CLI
keywords: Win OS IP Guide,CLI for IP Insight,Windows IP Command,Globally Accessed IPs,CLI-Based IP Viewing,WINOS IP Clarity,CLI IP Demystification
thumbnail: https://thmb.techidaily.com/ff8e499dfacbb3f8c53c52b2127d34f19a999ba4d08ba1beb7fd17db0047dd1a.jpg
---

## Demystifying Your Global IP on WIN OS via CLI

 A computer or any device connected to the Internet has two types of IP addresses necessary to communicate. Each Internet-enabled device comes with a private IP address, whereas a public IP address, also known as the external IP address, is provided by your Internet Service Provider (ISP).

 While checking your private IP address is easy, knowing your public IP address can be necessary for many tasks, including remote access, server hosting, network troubleshooting, and geolocation services. Here we show you a few ways to retrieve your public IPv4/IPv6 information on Windows.

## How to Check Your Private IP Address on Windows

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

## How to Get Your Public IP Address on Windows

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

## Online Tools to Get Your Public IP Address

![whatismyip online public ip address tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/whatismyip-online-public-ip-address-tool.jpg)

 If you prefer a more intuitive experience, you can use online web services that can provide information on your network configuration. These services can also detect the ISP location and other information, including the user agent.

 Online services to view public IP addresses:

* **[WhatIsMyIP](https://www.whatismyip.com/)**: A simple and intuitive web service to view your public IPv4 and IPv6 addresses. In addition, it also shows your ISP’s location and name.
* [**My External IP**](https://myexternalip.com/): A barebone web app that can detect your public IPv4 address and Port.
* **Use a search engine**: If you don’t want to remember another website to do basic stuff, try your search engine. Type “What’s my IP” in Google or Bing search to get your public IPv4/IPv6 address quickly.

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
<li><a href="https://windows11.techidaily.com/how-to-mend-the-pairing-glitch-fixing-connection-issues-in-win-11/"><u>How to Mend the Pairing Glitch: Fixing Connection Issues in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixes-for-stumbling-windows-discord-search-bar/"><u>Fixes for Stumbling Windows Discord Search Bar</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-top-ios-psp-games-and-emulators-revealed/"><u>In 2024, Top iOS PSP Games & Emulators Revealed</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-installation-issues-fixing-zero-error-on-win11/"><u>Avoid Installation Issues: Fixing Zero Error on Win11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/20plus-artistic-assembly-ideas-for-a-brighter-yard/"><u>20+ Artistic Assembly Ideas for a Brighter Yard</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-fb-video-marketing-made-simple-free-toolkit-unlocks-potential/"><u>[Updated] FB Video Marketing Made Simple  Free Toolkit Unlocks Potential</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-visual-coherence-integrating-this-pc-icon/"><u>Enhance Visual Coherence: Integrating 'This PC' Icon</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-how-to-transfer-from-apple-iphone-x-to-samsung-galaxy-s20-drfone-by-drfone-transfer-from-ios/"><u>In 2024, How to Transfer from Apple iPhone X to Samsung Galaxy S20? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/diminishing-high-cpu-impact-of-tiworkerexe-applications/"><u>Diminishing High CPU Impact of TiWorker.exe Applications</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-best-bokeh-effects-apps-for-ios-and-android-for-2024/"><u>New Best Bokeh Effects Apps for iOS and Android for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-flawed-setups-a-guide-to-windows-package-woes/"><u>Fixing Flawed Setups: A Guide to Windows Package Woes</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-enthralling-audiences-a-compilation-of-top-video-ideas/"><u>2024 Approved  Enthralling Audiences  A Compilation of Top Video Ideas</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-through-qbittorrent-lag-a-windows-guide/"><u>Breaking Through qBittorrent Lag: A Windows Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-edge-windows-11-techniques-building-hotkeys-for-text-snapping/"><u>Cutting Edge Windows 11 Techniques: Building Hotkeys for Text Snapping</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/honor-70-lite-5g-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>Honor 70 Lite 5G ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-disable-the-built-in-laptop-keyboard-in-windows/"><u>How to Disable the Built-In Laptop Keyboard in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-personalization-transforming-ordinary-into-extraordinary/"><u>Windows 11 Personalization: Transforming Ordinary Into Extraordinary</u></a></li>
<li><a href="https://windows11.techidaily.com/exclusive-guide-to-forgotten-windows-11-themes/"><u>Exclusive Guide to Forgotten Windows 11 Themes</u></a></li>
<li><a href="https://windows11.techidaily.com/detailed-guide-turning-secure-boot-and-tpm-onoff-in-vbox/"><u>Detailed Guide: Turning Secure Boot and TPM On/Off in VBox</u></a></li>
<li><a href="https://windows11.techidaily.com/ai-driven-evolution-in-windows-software-design/"><u>AI-Driven Evolution in Windows Software Design</u></a></li>
<li><a href="https://windows11.techidaily.com/insights-on-how-to-utilize-execution-nicknames/"><u>Insights on How to Utilize Execution Nicknames</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-haunting-harmonics-procuring-disturbing-sound-effects-for-creatives-for-2024/"><u>Updated Haunting Harmonics Procuring Disturbing Sound Effects for Creatives for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-comparing-igs-new-features-reels-vs-stories/"><u>[Updated] In 2024, Comparing IG's New Features  Reels Vs Stories</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-best-tools-to-hard-reset-itel-p55t-drfone-by-drfone-reset-android-reset-android/"><u>3 Best Tools to Hard Reset Itel P55T | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-of-non-existent-mmc-snaps/"><u>Unraveling the Mystery of Non-Existent MMC Snaps</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-your-windows-11-journey-top-6-multitasking-android-apps/"><u>Enhancing Your Windows 11 Journey: Top 6 Multitasking Android Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/initiating-contact-accessing-windows-printer-administration-tools/"><u>Initiating Contact: Accessing Windows' Printer Administration Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-for-lowering-tiworkerexe-process-resource-use/"><u>Methods for Lowering TiWorker.exe Process Resource Use</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/024-approved-virtual-masterclass-for-aspiring-filmmakers-on-youtube/"><u>[New] 2024 Approved  Virtual Masterclass for Aspiring Filmmakers on YouTube</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-capture-and-save-with-ease-top-5-pc-snipers-reviewed/"><u>[Updated] Capture & Save with Ease  Top 5 PC Snipers Reviewed</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-in-2024-pro-level-stabilization-systems-for-streaming-content/"><u>[New] In 2024, Pro-Level Stabilization Systems for Streaming Content</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-converting-ephemeral-content-fb-messenger-video-secrets-revealed-for-2024/"><u>[Updated] Converting Ephemeral Content  FB Messenger Video Secrets Revealed for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-the-wow-breakdown-cure-windows-error-code-132/"><u>Avoid the WoW Breakdown: Cure Windows Error Code 132</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-enabling-or-disabling-wi-fi-cost-tracking-in-windows-11/"><u>Guide: Enabling or Disabling Wi-Fi Cost Tracking in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-start-up-sequence-of-windows-os/"><u>Decoding the Start-Up Sequence of Windows OS</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-enhance-audio-quality-get-high-quality-fx/"><u>In 2024, Enhance Audio Quality, Get High-Quality FX</u></a></li>
<li><a href="https://windows11.techidaily.com/approaches-to-fix-failed-launch-of-lunar-client-in-windows/"><u>Approaches to Fix Failed Launch of Lunar Client in Windows</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-a-step-by-step-guide-to-memetic-marvels-essential-strategies-for-gif-makers/"><u>[New] A Step-by-Step Guide to Memetic Marvels  Essential Strategies for GIF Makers</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-your-typing-speed-top-7-fixes-on-win-os/"><u>Elevating Your Typing Speed: Top 7 Fixes on WIN OS</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-back-chrome-color-loss/"><u>Winning Back Chrome Color Loss</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-driving-view-counts-upward-on-youtube-6-proven-techniques/"><u>In 2024, Driving View Counts Upward on YouTube  6 Proven Techniques</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-in-2024-top-20-best-text-to-speech-software-windows-mac-android-iphone-and-online/"><u>Updated In 2024, Top 20 Best Text To Speech Software Windows, Mac, Android, iPhone & Online</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-dissolve-link-to-discord-on-devices/"><u>[Updated] In 2024, Dissolve Link to Discord on Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/get-your-pcs-virtual-machine-game-strong-with-hyper-v/"><u>Get Your PC's Virtual Machine Game Strong with Hyper-V</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-ultimate-guide-to-iphone-composition-choosing-right-angles-for-2024/"><u>The Ultimate Guide to iPhone Composition  Choosing Right Angles for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-professionals-choice-ranking-the-top-9-microphone-apps/"><u>[New] 2024 Approved  Professional's Choice  Ranking the Top 9 Microphone Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/discovering-distinctive-decor-for-each-monitor-in-windows-11/"><u>Discovering Distinctive Decor for Each Monitor in Windows 11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-crafting-the-perfect-visual-identity-podcast-covers-unveiled/"><u>2024 Approved  Crafting the Perfect Visual Identity  Podcast Covers Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-memory-write-failures-windows-fixes-guide/"><u>Disabling Memory Write Failures: Windows Fixes Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/automate-peaceful-rest-for-your-windows-11-desktop/"><u>Automate Peaceful Rest for Your Windows 11 Desktop</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-purr-fect-tone-simulation/"><u>New 2024 Approved Purr-Fect Tone Simulation</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-15-top-rated-youtube-downloaders-your-offline-viewing-solution/"><u>[New] 2024 Approved  15 Top-Rated YouTube Downloaders - Your Offline Viewing Solution</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-enhancing-communication-on-google-meet-step-by-step/"><u>[New] In 2024, Enhancing Communication on Google Meet [Step-by-Step]</u></a></li>
</ul></div>
