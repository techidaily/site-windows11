---
title: Demystifying Your Global IP on WIN OS via CLI
date: 2024-06-25T12:21:07.286Z
updated: 2024-06-26T12:21:07.286Z
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/strategies-to-decrease-high-cpu-usage-from-dropbox-on-windows-pcs/"><u>Strategies to Decrease High CPU Usage From Dropbox on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-windows-default-no-spotify-autoplay/"><u>Avoid Windows Default: No Spotify Autoplay</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-desk-icons-clashing-find-harmony/"><u>Windows Desk Icons Clashing - Find Harmony!</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-mspcm-bar-with-finesse-in-windows-11-environment/"><u>Navigating MSPCM Bar with Finesse in Windows 11 Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/uncomplicated-superiority-persistent-high-privilege-terminal/"><u>Uncomplicated Superiority: Persistent High-Privilege Terminal</u></a></li>
<li><a href="https://windows11.techidaily.com/initiate-your-narrative-with-a-click-on-windows-11/"><u>Initiate Your Narrative with a Click on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-cutting-back-cpu-overuse-in-windows-systems/"><u>Strategies for Cutting Back CPU Overuse in Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-common-issues-with-windows-shared-printers/"><u>Solving Common Issues with Windows Shared Printers</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-windows-crash-0x800f0831-solution/"><u>Mastery Over Windows Crash: 0X800f0831 Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-performance-monitoring-pcs-ram-gpu-and-cpu/"><u>Maximizing Performance: Monitoring PC's RAM, GPU & CPU</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-whatsapp-messages-on-lava-yuva-3-without-them-knowing-drfone-by-drfone-virtual-android/"><u>How to Track WhatsApp Messages on Lava Yuva 3 Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-social-media-music-grabber/"><u>[Updated] 2024 Approved  Social Media Music Grabber</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-fake-gps-without-root-on-samsung-galaxy-a05-drfone-by-drfone-virtual-android/"><u>3 Ways to Fake GPS Without Root On Samsung Galaxy A05 | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-dissecting-and-defeating-dreadful-greenscreen-a-mac-editors-directive/"><u>[Updated] 2024 Approved  Dissecting & Defeating Dreadful Greenscreen  A Mac Editor's Directive</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-frp-on-12-by-drfone-android-unlock-remove-google-frp/"><u>How To Bypass FRP on 12</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/remedy-for-audio-pause-in-obs-streams-for-2024/"><u>Remedy for Audio Pause in OBS Streams for 2024</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-elevate-your-video-editing-game-top-5-final-cut-pro-tips-and-tricks/"><u>In 2024, Elevate Your Video Editing Game Top 5 Final Cut Pro Tips and Tricks</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-detect-and-remove-spyware-on-oppo-a58-4g-drfone-by-drfone-virtual-android/"><u>How to Detect and Remove Spyware on Oppo A58 4G? | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-cutting-edge-camera-and-recording-apps-for-smartphones-most-reliable-sources/"><u>2024 Approved  Cutting-Edge Camera & Recording Apps for Smartphones' Most Reliable Sources</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-2024-approved-the-compre-habits-of-top-reddit-posters-explained/"><u>[Updated] 2024 Approved  The Compre Habits of Top Reddit Posters Explained</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>