---
title: Determining Public IP with System Commands, Windows
date: 2024-07-11T22:29:55.945Z
updated: 2024-07-12T22:29:55.945Z
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
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-cloaked-observer-of-facebook-snapshots/"><u>[New] 2024 Approved  Cloaked Observer of Facebook Snapshots</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/optimizing-your-podcasts-the-seo-blueprint/"><u>Optimizing Your Podcasts  The SEO Blueprint</u></a></li>
<li><a href="https://windows11.techidaily.com/counteracting-the-impact-of-vac-denial-in-steam-gaming/"><u>Counteracting the Impact of VAC Denial in Steam Gaming</u></a></li>
<li><a href="https://windows11.techidaily.com/deploying-microsofts-ai-companion-via-vivetool/"><u>Deploying Microsoft's AI Companion via ViveTool</u></a></li>
<li><a href="https://windows11.techidaily.com/delving-into-the-spiritual-command-center-of-windows-11/"><u>Delving Into the Spiritual Command Center of Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/display-windows-notes-prominently-and-consistently/"><u>Display Windows Notes Prominently and Consistently</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-the-divine-interface-of-windows-11-os/"><u>Discover the Divine Interface of Windows 11 OS</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-2024-approved-elevate-your-ad-game-a-deep-dive-into-spotify-promotion/"><u>[Updated] 2024 Approved  Elevate Your Ad Game  A Deep Dive Into Spotify Promotion</u></a></li>
<li><a href="https://windows11.techidaily.com/dealing-with-the-extract-to-temp-directory-glitch-fix-for-error-1152/"><u>Dealing with the 'Extract to Temp Directory' Glitch: Fix for Error 1152</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-graphics-output-for-enhanced-clarity/"><u>Customizing Graphics Output for Enhanced Clarity</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-learn-how-everything-works-on-xiaomi-13t-drfone-by-drfone-virtual-android/"><u>Life360 Learn How Everything Works On Xiaomi 13T | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-high-definition-horizons-best-4k-smartphone-cameras-of-the-year/"><u>[New] High-Definition Horizons  Best 4K Smartphone Cameras of the Year</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-ftdibussys-a-windows-memory-security-paradox/"><u>Decoding ftdibus.sys: A Windows Memory Security Paradox</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-microsoft-family-safety-functions/"><u>Demystifying Microsoft Family Safety Functions</u></a></li>
<li><a href="https://windows11.techidaily.com/dive-into-windows-11-auditory-setup-and-use/"><u>Dive Into Windows 11 Auditory Setup and Use</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-pictures-from-k11-5g-by-fonelab-android-recover-pictures/"><u>Possible solutions to restore deleted pictures from K11 5G.</u></a></li>
<li><a href="https://windows11.techidaily.com/deploying-flask-and-socketio-for-windows-file-transfers-via-server/"><u>Deploying Flask and SocketIO for Windows File Transfers via Server</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-home-screen-preferences-on-w11-os/"><u>Customizing Home Screen Preferences on W11 OS</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/chow-down-top-tiktok-eatery-channels-for-2024/"><u>Chow Down  Top TikTok Eatery Channels for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/compulsory-uninstall-guide-for-windows-11-printers/"><u>Compulsory Uninstall Guide for Windows 11 Printers</u></a></li>
<li><a href="https://windows11.techidaily.com/disable-the-app-open-tracker-in-windows-10/"><u>Disable the App Open Tracker in Windows 10</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-frp-from-motorola-g54-5g-by-drfone-android/"><u>How to Bypass FRP from Motorola G54 5G?</u></a></li>
<li><a href="https://windows11.techidaily.com/controlling-elements-post-sleep-for-optimal-use/"><u>Controlling Elements Post-Sleep for Optimal Use</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-mastering-low-volume-settings-in-os-xwindows/"><u>2024 Approved  Mastering Low-Volume Settings in OS X/Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/diagnosing-voice-commands-malfunction-in-valorant-games/"><u>Diagnosing Voice Commands Malfunction in Valorant Games</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/cketing-view-figures-by-sustaining-youtubes-creative-commons-license-for-2024/"><u>Skyrocketing View Figures by Sustaining YouTube's Creative Commons License for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/countering-compromised-windows-defender-on-win-11/"><u>Countering Compromised Windows Defender on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-non-deletable-keys-a-windows-guide/"><u>Correcting Non-Deletable Keys: A Windows Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-to-fixing-device-path-errors/"><u>Comprehensive Guide to Fixing Device Path Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/configure-your-systems-primary-terminal-application/"><u>Configure Your System’s Primary Terminal Application</u></a></li>
<li><a href="https://windows11.techidaily.com/directx-essentials-downloading-installing-made-easy-for-pc-users/"><u>DirectX Essentials: Downloading, Installing Made Easy for PC Users</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-failed-windows-update-with-error-code-0x800f0845/"><u>Correcting Failed Windows Update with Error Code 0X800f0845</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/from-silence-to-symphony-incorporating-music-into-animated-graphics-on-macos-for-2024/"><u>From Silence to Symphony Incorporating Music Into Animated Graphics on macOS for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-common-downloads-dilemmas-on-windows-pcs/"><u>Combatting Common Downloads Dilemmas on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-the-best-4-webp-apps-on-your-windows-laptoppc/"><u>Discover the Best 4 WebP Apps on Your Windows Laptop/PC</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/comprehensive-guide-to-screen-capturing-in-windows-8/"><u>Comprehensive Guide to Screen Capturing in Windows 8</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-unlocking-desktop-recording-the-ezvide-approach/"><u>[New] Unlocking Desktop Recording - The EZvide Approach</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unveiling-optimal-sites-for-pixel-sounds/"><u>[Updated] Unveiling Optimal Sites for Pixel Sounds</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-pioneering-audio-enhancement-for-compelling-visual-stories/"><u>2024 Approved  Pioneering Audio Enhancement for Compelling Visual Stories</u></a></li>
<li><a href="https://windows11.techidaily.com/curtailing-windows-updates-and-restarts/"><u>Curtailing Windows Updates and Restarts</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-filesystem-crashes-in-win11/"><u>Combatting FileSystem Crashes in Win11</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-free-filmora-13-editor-download-create-stunning-videos/"><u>Updated Free Filmora 13 Editor Download Create Stunning Videos</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-or-see-text-messages-what-can-you-do-with-life360-on-motorola-moto-g84-5g-drfone-by-drfone-virtual-android/"><u>Can Life360 Track Or See Text Messages? What Can You Do with Life360 On Motorola Moto G84 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-disruption-in-skyrims-scripting/"><u>Deciphering the Disruption in Skyrim's Scripting</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-correcting-installer-messages-on-pcs/"><u>Decoding and Correcting Installer Messages on PCs</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-sony-xperia-10-v-drfone-by-drfone-virtual-android/"><u>In 2024, Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Sony Xperia 10 V | Dr.fone</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-reclaim-your-iphone-x-experience-with-these-tips/"><u>In 2024, Reclaim Your iPhone X Experience with These Tips</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/1713964095906-new-learn-how-to-create-inspiring-motivational-videos-using-ai-explore-tools-like-midjourney-runway-gen2-chat-gpt-and-filmora-ai-for-seamless-content-creati/"><u>New Learn How to Create Inspiring Motivational Videos Using AI. Explore Tools Like Midjourney, Runway Gen2, Chat-GPT, and Filmora AI for Seamless Content Creation. Start Your Journey for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-can-you-unlock-apple-iphone-7-plus-after-forgetting-the-passcode-by-drfone-ios/"><u>In 2024, Can You Unlock Apple iPhone 7 Plus After Forgetting the Passcode?</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/button-pressing-on-keyboards-the-uk-us-disparity/"><u>Button Pressing on Keyboards: The UK-US Disparity</u></a></li>
<li><a href="https://windows11.techidaily.com/cut-down-complications-opt-for-simplicity-in-win11/"><u>Cut Down Complications: Opt for Simplicity in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/craft-a-festive-atmosphere-with-creative-windows/"><u>Craft a Festive Atmosphere with Creative Windows</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-capture-and-store-screen-content-free-for-2024/"><u>[Updated] Capture and Store Screen Content, FREE for 2024</u></a></li>
<li><a href="https://android-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-samsung-galaxy-a05withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Samsung Galaxy A05with/without a PC</u></a></li>
<li><a href="https://windows11.techidaily.com/combating-computer-chaos-fixing-windows-non-responsive-keys/"><u>Combating Computer Chaos: Fixing Windows' Non-Responsive Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-sound-malfunction-fixing-error-code-xc00d36b4/"><u>Combatting Sound Malfunction: Fixing Error Code Xc00d36b4</u></a></li>
<li><a href="https://windows11.techidaily.com/detecting-7-critical-windows-steps-for-cyber-threats/"><u>Detecting 7 Critical Windows Steps for Cyber Threats</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-absence-of-drive-letters-problems-and-cures-for-win-users/"><u>Decoding the Absence of Drive Letters: Problems & Cures for Win Users</u></a></li>
<li><a href="https://android-location.techidaily.com/3-effective-methods-to-fake-gps-location-on-android-for-your-infinix-smart-7-drfone-by-drfone-virtual/"><u>3 Effective Methods to Fake GPS location on Android For your Infinix Smart 7 | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-honor-100-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Honor 100 | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>