---
title: Pinpoint Public IP with Commands, Windows Edition
date: 2024-08-31T22:09:40.192Z
updated: 2024-09-01T22:09:40.192Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Pinpoint Public IP with Commands, Windows Edition
excerpt: This Article Describes Pinpoint Public IP with Commands, Windows Edition
keywords: Win IP Pinpointing,Commands for IP,IP Address Commands,Find Windows IP,Windows Public IP,Command Guide to IP,Locate IP in Windows
thumbnail: https://thmb.techidaily.com/861e642d844db4b2f3d772a017498464c5809d87279c75b02518b1d6b111bfc3.jpg
---

## Pinpoint Public IP with Commands, Windows Edition

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Online Tools to Get Your Public IP Address

![whatismyip online public ip address tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/whatismyip-online-public-ip-address-tool.jpg)

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If you prefer a more intuitive experience, you can use online web services that can provide information on your network configuration. These services can also detect the ISP location and other information, including the user agent.

 Online services to view public IP addresses:

* **[WhatIsMyIP](https://www.whatismyip.com/)**: A simple and intuitive web service to view your public IPv4 and IPv6 addresses. In addition, it also shows your ISP’s location and name.
* [**My External IP**](https://myexternalip.com/): A barebone web app that can detect your public IPv4 address and Port.
* **Use a search engine**: If you don’t want to remember another website to do basic stuff, try your search engine. Type “What’s my IP” in Google or Bing search to get your public IPv4/IPv6 address quickly.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->
## Many Ways to Check Your Public IP Address on Windows

 Whether you want to perform remote access or set up a gaming server, you may need to share your public IP address to allow others to connect to your network. Fortunately, plenty of web services allow you to check your network details using Command Prompt and online tools.

 While checking your private IP address is easy, knowing your public IP address can be necessary for many tasks, including remote access, server hosting, network troubleshooting, and geolocation services. Here we show you a few ways to retrieve your public IPv4/IPv6 information on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-boxes.techidaily.com/new-optimize-your-streaming-game-incorporating-chroma-key-effects-with-ease-for-2024/"><u>[New] Optimize Your Streaming Game  Incorporating Chroma Key Effects with Ease for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-the-twitch-enthusiasts-recording-guidebook/"><u>[New] The Twitch Enthusiast's Recording Guidebook</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-top-tech-choice-screen-recording-leaders-on-the-web-for-2024/"><u>[New] Top Tech Choice  Screen Recording Leaders on the Web for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-navigating-video-sharing-from-imovie-to-the-vimeo-network/"><u>[Updated] 2024 Approved  Navigating Video Sharing  From iMovie to the Vimeo Network</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-advanced-strategies-for-enhancing-footage-with-gopro-studio/"><u>[Updated] Advanced Strategies for Enhancing Footage with GoPro Studio</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-cyber-safeguard-success-reclaiming-fb/"><u>[Updated] Cyber-Safeguard Success  Reclaiming FB</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-elite-selection-of-fbs-best-viewing-apps-for-2024/"><u>[Updated] Elite Selection of FB's Best Viewing Apps for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-intuitive-camera-roll-consolidation-step-by-step-snapchat-guide-for-2024/"><u>[Updated] Intuitive Camera Roll Consolidation  Step-by-Step Snapchat Guide for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-streamlined-methods-to-store-mov-on-your-windows-pc/"><u>2024 Approved  Streamlined Methods to Store .mov on Your Windows PC</u></a></li>
<li><a href="https://howto.techidaily.com/8-solutions-to-solve-youtube-app-crashing-on-samsung-galaxy-s24-ultra-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Solutions to Solve YouTube App Crashing on Samsung Galaxy S24 Ultra | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-xiaomi-13-ultra-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Xiaomi 13 Ultra</u></a></li>
<li><a href="https://fake-location.techidaily.com/all-must-knows-to-use-fake-gps-go-location-spoofer-on-motorola-g54-5g-drfone-by-drfone-virtual-android/"><u>All Must-Knows to Use Fake GPS GO Location Spoofer On Motorola G54 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ing-streams-switching-to-av1-in-youtubes-settings/"><u>Boosting Streams  Switching to AV1 in YouTube's Settings</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/bridging-the-gap-the-ongoing-effort-by-google-for-seamless-text-communication-between-iphones-and-android-devices/"><u>Bridging the Gap: The Ongoing Effort by Google for Seamless Text Communication Between iPhones & Android Devices</u></a></li>
<li><a href="https://fox-direct.techidaily.com/enhancing-iphone-shots-employing-leading-lines-for-2024/"><u>Enhancing iPhone Shots  Employing Leading Lines for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-taskbar-upgrades-in-windows-11/"><u>Exploring Taskbar Upgrades in Windows 11</u></a></li>
<li><a href="https://program-issues.techidaily.com/fix-your-pc-woes-solve-stuttering-and-frame-drop-glitches-in-call-of-duty-mw2/"><u>Fix Your PC Woes! Solve Stuttering and Frame Drop Glitches in Call of Duty: MW2</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-network-issues-with-anydesk-in-win11/"><u>Fixing Network Issues with AnyDesk in WIn11</u></a></li>
<li><a href="https://win-dash.techidaily.com/free-hp-audio-driver-downloads-effortless-step-by-step-install-guide/"><u>Free HP Audio Driver Downloads | Effortless, Step-by-Step Install Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/future-proofing-windows-how-to-leverage-vivetool-advantages/"><u>Future-Proofing Windows: How to Leverage ViVeTool Advantages</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-principles-to-consider-in-a-new-os-rollout/"><u>Guiding Principles to Consider in a New OS Rollout</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-modify-the-visual-cues-in-windows-11-search/"><u>How to Modify the Visual Cues in Windows 11 Search</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-resurrect-a-freeze-fixing-error-code-x-in-windows-11/"><u>How to Resurrect a Freeze: Fixing Error Code X in Windows 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-videos-from-infinix-hot-40i-by-fonelab-android-recover-video/"><u>How to retrieve erased videos from Infinix Hot 40i</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-a-lost-honor-magic5-ultimate-for-free-drfone-by-drfone-virtual-android/"><u>How to Track a Lost Honor Magic5 Ultimate for Free? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-3-ways-to-fake-gps-without-root-on-apple-iphone-15-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, 3 Ways to Fake GPS Without Root On Apple iPhone 15 Plus | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-brighten-and-sharpen-expert-tips-for-v22-video-enhancement/"><u>In 2024, Brighten and Sharpen  Expert Tips for V2.2 Video Enhancement</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-do-i-stop-someone-from-tracking-my-tecno-pova-6-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How Do I Stop Someone From Tracking My Tecno Pova 6 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-motorola-moto-g73-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Snapchat Location Spoofer to Protect Your Privacy On Motorola Moto G73 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-charging-notifications-in-modern-windows-os/"><u>Leveraging Charging Notifications in Modern Windows OS</u></a></li>
<li><a href="https://tech-haven.techidaily.com/love-engineered-ais-role-in-dating-frauds/"><u>Love Engineered: AI's Role in Dating Frauds</u></a></li>
<li><a href="https://windows11.techidaily.com/masterclass-guide-to-overcoming-opengl-glitch-3/"><u>Masterclass Guide to Overcoming OpenGL Glitch #3</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-nat-type-adjustment-in-modern-windows-oses/"><u>Mastering NAT Type Adjustment in Modern Windows OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-system-debugging-locating-and-resolving-error-codes-via-windows-command-prompt/"><u>Mastering System Debugging: Locating & Resolving Error Codes via Windows Command Prompt</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-batch-conversion-heic-to-jpeg-in-windows-11/"><u>Mastering the Art of Batch Conversion: Heic to JPEG in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-fixing-install-failed-on-windows-1011/"><u>Mastering the Art of Fixing Install Failed on Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11-keys-best-offers/"><u>Mastering Windows 11 Keys: Best Offers</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-visual-quality-with-w11s-auto-hdr/"><u>Maximizing Visual Quality with W11's Auto HDR</u></a></li>
<li><a href="https://windows11.techidaily.com/methodology-purging-onedrive-icon-in-file-explorer/"><u>Methodology: Purging OneDrive Icon in File Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-background-run-of-microsoft-edge-on-win11/"><u>Navigating the Background Run of Microsoft Edge on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-errors-fixing-the-termination-denial/"><u>Navigating Windows Errors - Fixing the Termination Denial</u></a></li>
<li><a href="https://extra-support.techidaily.com/nikons-bold-move-into-4k-with-the-innovative-j5-model-for-2024/"><u>Nikon's Bold Move Into 4K with The Innovative J5 Model for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-windows-launch-directly-engage-file-explorer-through-onedrive/"><u>Optimizing Windows Launch: Directly Engage File Explorer Through OneDrive</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-backspace-failures-in-windows-environments/"><u>Overcoming Backspace Failures in Windows Environments</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-game-pass-service-halt-in-win-os/"><u>Overcoming Game Pass Service Halt in Win OS</u></a></li>
<li><a href="https://win-blog.techidaily.com/overcoming-overwatch-2-launch-errors-ultimate-fix-guide/"><u>Overcoming Overwatch 2 Launch Errors – Ultimate Fix Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/preserving-your-preferred-windows-volume-mixer-state/"><u>Preserving Your Preferred Windows Volume Mixer State</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-and-easy-guide-for-turning-onoff-windows-key/"><u>Quick & Easy Guide for Turning On/Off Windows Key</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/quick-and-easy-way-to-record-iphone-screens-for-2024/"><u>Quick & Easy Way to Record iPhone Screens for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/re-initiate-audio-playback-on-frozen-systems/"><u>Re-Initiate Audio Playback on Frozen Systems</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-iphone-6-data-from-itunes-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>Recover iPhone 6 Data From iTunes | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/reducing-unrealcefsubprocess-power-footprint-on-windows-os/"><u>Reducing UnrealCEFSubprocess Power Footprint on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/reigniting-your-wifi-detection-capabilities-in-win11/"><u>Reigniting Your Wifi Detection Capabilities in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/safeguard-privacy-erasing-ms-defender-logs-in-windows-1011/"><u>Safeguard Privacy: Erasing MS Defender Logs in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/set-up-a-fast-safe-login-windows-hello-basics/"><u>Set Up a Fast, Safe Login: Windows Hello Basics</u></a></li>
<li><a href="https://windows11.techidaily.com/solve-your-windows-dilemma-help-strategies-revealed/"><u>Solve Your Windows Dilemma: Help Strategies Revealed!</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-keeping-calculator-visible-at-top/"><u>Strategies for Keeping Calculator Visible at Top</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-overcoming-windows-administrative-restriction-on-installers/"><u>Strategies for Overcoming Windows' Administrative Restriction on Installers</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-essential-handbook-for-instagram-reels/"><u>The Essential Handbook for Instagram Reels</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-knowledge-of-command-line-nicknames/"><u>The Essential Knowledge of Command Line Nicknames</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-evolution-of-nlp-dive-into-googles-enhanced-palm-2-large-language-system/"><u>The Evolution of NLP: Dive Into Google's Enhanced PaLM 2 Large Language System</u></a></li>
<li><a href="https://windows11.techidaily.com/the-new-era-ai-enhancements-in-windows-platforms/"><u>The New Era: AI Enhancements in Windows Platforms</u></a></li>
<li><a href="https://techidaily.com/top-iphone-se-message-recovery-software-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>Top iPhone SE Message Recovery Software | Stellar</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-unsupported-app-packages-on-windows-xp/"><u>Troubleshooting Unsupported App Packages on Windows XP</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-windows-arp-caches-deletion-guide/"><u>Understanding Windows ARP Caches: Deletion Guide</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/unlocking-apple-iphone-15-lock-screen-3-foolproof-methods-that-actually-work-by-drfone-ios/"><u>Unlocking Apple iPhone 15 Lock Screen 3 Foolproof Methods that Actually Work</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-outlook-preview-features-on-windows-11-platforms/"><u>Unveiling Outlook Preview Features on Windows 11 Platforms</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-sonic-storytelling-showcasing-sound-waves-and-engaging-animated-sequences-with-sony-vegas-pro/"><u>Updated Sonic Storytelling Showcasing Sound Waves & Engaging Animated Sequences with Sony Vegas Pro</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>