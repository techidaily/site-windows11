---
title: Finding Out Your Internet's Public IP with Win CLI
date: 2024-07-11T21:29:35.929Z
updated: 2024-07-12T21:29:35.929Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Finding Out Your Internet's Public IP with Win CLI
excerpt: This Article Describes Finding Out Your Internet's Public IP with Win CLI
keywords: Find Public IP Windows,IP Address Retrieval CLI,Locate Win IP Address,Determine Windows IP,Get Win IP Address,Access Public Win IP,Uncover Win OS IP
thumbnail: https://thmb.techidaily.com/4cbebb13391bd3ac3f3b9ef43b45b771ba69f0146a8bbd42e4f0e8dd5abd0510.jpg
---

## Finding Out Your Internet's Public IP with Win CLI

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
<li><a href="https://howto.techidaily.com/full-solutions-to-fix-error-code-920-in-google-play-on-infinix-note-30-vip-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Solutions to Fix Error Code 920 In Google Play on Infinix Note 30 VIP | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/the-phasing-out-of-microsofts-windows-xp-7-and-81-lifeline/"><u>The Phasing Out of Microsoft's Windows XP, 7 & 8.1 Lifeline</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/navigating-the-world-of-youtube-titling-and-tagging/"><u>Navigating the World of YouTube Titling and Tagging</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-win-strategies-boosting-frames-in-cs-go/"><u>Quick Win Strategies - Boosting Frames in CS GO</u></a></li>
<li><a href="https://windows11.techidaily.com/1719207064707-ifas-hottest-laptops-unveiled/"><u>IFA's Hottest Laptops Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/1719270325227-seeking-help-navigate-through-windows-troubles-easily/"><u>Seeking Help? Navigate Through Windows Troubles Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/slowing-down-windows-11-shutdown-tips-for-live-tasks/"><u>Slowing Down Windows 11 Shutdown: Tips for Live Tasks</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-a-step-by-step-approach-to-zooming-success/"><u>[New] A Step-by-Step Approach to Zooming Success</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-the-quest-for-your-own-specialized-tiktok-hash-code/"><u>[New] In 2024, The Quest for Your Own Specialized TikTok Hash Code</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-windows-repeatedly-entering-cmos-settings/"><u>Solutions for Windows Repeatedly Entering CMOS Settings</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/does-samsung-galaxy-xcover-7-support-avchd-video-by-aiseesoft-video-converter-play-mts-on-android/"><u>Does Samsung Galaxy XCover 7 support AVCHD video?</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-life360-on-windows-pc-for-itel-s23-drfone-by-drfone-virtual-android/"><u>How to Use Life360 on Windows PC For Itel S23? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/1719211883980-tackling-the-challenge-of-non-working-win-plus-printer-feature-in-windows/"><u>Tackling the Challenge of Non-Working Win + Printer Feature in Windows</u></a></li>
<li><a href="https://youtube-web.techidaily.com/approved-best-youtube-shorts-video-editing-apps-for-ios-and-android/"><u>2024 Approved  Best YouTube Shorts Video Editing Apps for iOS and Android</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-controlling-file-compression-in-windows-11/"><u>Strategies for Controlling File Compression in Windows 11</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-best-free-video-watermarking-tools-top-picks/"><u>New In 2024, Best Free Video Watermarking Tools Top Picks</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-strategy-become-system-admin-now/"><u>Swift Strategy: Become System Admin Now</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-streaming-showdown-obs-vs-twitch-studio/"><u>[Updated] In 2024, Streaming Showdown  OBS vs Twitch Studio</u></a></li>
<li><a href="https://windows11.techidaily.com/13-ways-to-open-the-windows-system-settings/"><u>13 Ways to Open the Windows System Settings</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/make-a-fake-face-online-for-free-top-rated-tools-for-2024/"><u>Make a Fake Face Online for Free Top Rated Tools for 2024</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-insights-from-the-best-ogg-conversion-tools/"><u>Updated Insights From the Best OGG Conversion Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/1719267835321-reactivating-silenced-pc-speakers-easy-fixes-ahead/"><u>Reactivating Silenced PC Speakers – Easy Fixes Ahead!</u></a></li>
<li><a href="https://windows11.techidaily.com/remedial-tactics-for-loading-errors-in-discord-software/"><u>Remedial Tactics for Loading Errors in Discord Software</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/2024-approved-whatsapp-video-status-creator-tools-free-and-paid-reviews/"><u>2024 Approved WhatsApp Video Status Creator Tools Free and Paid Reviews</u></a></li>
<li><a href="https://windows11.techidaily.com/stopping-google-chrome-alerts-tips-for-windows/"><u>Stopping Google Chrome Alerts: Tips for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-your-computers-clock-display-with-animated-screensaver-apps/"><u>Transform Your Computer's Clock Display with Animated Screensaver Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/1719265109241-master-google-chromes-filesync-on-your-windows-device-now/"><u>Master Google Chrome's Filesync on Your Windows Device Now</u></a></li>
<li><a href="https://windows11.techidaily.com/10-solutions-for-windows-uncovering-lost-nexus-controllers/"><u>10 Solutions for Windows: Uncovering Lost Nexus Controllers</u></a></li>
<li><a href="https://windows11.techidaily.com/1719293277231-get-personalized-chatbot-experience-local-clone-for-windows-at-no-cost/"><u>Get Personalized ChatBot Experience: Local Clone for Windows at No Cost</u></a></li>
<li><a href="https://windows11.techidaily.com/1719208597283-unravel-complex-windows-issues-help-at-hand/"><u>Unravel Complex Windows Issues: Help at Hand</u></a></li>
<li><a href="https://windows11.techidaily.com/1719241276591-team-chat-freezing-heres-a-fix/"><u>Team Chat Freezing? Here’s a Fix!</u></a></li>
<li><a href="https://windows11.techidaily.com/10-ways-to-clean-up-your-firewall-rules/"><u>10 Ways to Clean Up Your Firewall Rules</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-essential-insights-on-recording-google-video-conferences/"><u>[Updated] Essential Insights on Recording Google Video Conferences</u></a></li>
<li><a href="https://windows11.techidaily.com/10-essential-windows-methods-for-controller-recognition/"><u>10 Essential Windows Methods for Controller Recognition</u></a></li>
<li><a href="https://windows11.techidaily.com/11-fixes-if-windows-10-cant-detect-a-wi-fi-network/"><u>11 Fixes if Windows 10 Can’t Detect a Wi-Fi Network</u></a></li>
<li><a href="https://windows11.techidaily.com/1719298315535-solving-your-full-screen-capture-predicament-with-snip-and-sketch/"><u>Solving Your Full-Screen Capture Predicament with Snip & Sketch.</u></a></li>
<li><a href="https://windows11.techidaily.com/1719205436965-open-that-locked-handbrake-on-windows-now/"><u>Open That Locked HandBrake on Windows Now!</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/complete-fixes-to-solve-iphone-13-randomly-asking-for-apple-id-password-by-drfone-ios/"><u>Complete Fixes To Solve iPhone 13 Randomly Asking for Apple ID Password</u></a></li>
<li><a href="https://windows11.techidaily.com/the-6-best-to-do-list-apps-for-windows-10-and-11/"><u>The 6 Best To-Do List Apps for Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/1719228177134-functions-not-working-on-win10-heres-what-to-do/"><u>Functions Not Working on Win10? Here's What to Do!</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-capture-natural-motion-blur-for-pics/"><u>[Updated] Capture Natural Motion Blur for Pics</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-elevate-your-content-top-5-reaction-video-makers/"><u>Updated Elevate Your Content Top 5 Reaction Video Makers</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-proven-ways-in-how-to-hide-location-on-life360-for-samsung-galaxy-s23-fe-drfone-by-drfone-virtual-android/"><u>In 2024, Proven Ways in How To Hide Location on Life360 For Samsung Galaxy S23 FE | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-to-bypass-admin-access-denied-message-on-pc/"><u>Tactics to Bypass 'Admin Access Denied' Message on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/1719252317464-understanding-and-fixing-the-common-problem-of-wwinplusp-not-working/"><u>Understanding and Fixing the Common Problem of WWin+P Not Working</u></a></li>
<li><a href="https://windows11.techidaily.com/1719235299454-overcome-the-stumbling-block-fixing-the-missing-wwinplusprint-on-pc/"><u>Overcome The Stumbling Block: Fixing the Missing WWin+Print on PC</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-unlocking-instagram-potential-with-video-descriptions/"><u>[New] In 2024, Unlocking Instagram Potential with Video Descriptions</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/free-top-12-best-idle-games-you-can-try-on-pc-for-2024/"><u>FREE Top 12 Best Idle Games You Can Try on PC for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-power-of-shortcuts-for-app-size-adjustment-on-windows-11/"><u>Unlocking the Power of Shortcuts for App Size Adjustment on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/11-ways-to-fix-the-windows-search-bar-not-showing-or-working-on-windows-11/"><u>11 Ways to Fix the Windows Search Bar Not Showing or Working on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/1719293003975-winning-over-window-devices-no-more-naming-clashes/"><u>Winning Over Window Devices: No More Naming Clashes</u></a></li>
<li><a href="https://windows11.techidaily.com/the-complete-list-of-windows-11s-narrator-keyboard-shortcuts/"><u>The Complete List of Windows 11'S Narrator Keyboard Shortcuts</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-best-luts-ranked-top-10-in-photoshop-and-lightroom/"><u>[New] Best LUTs Ranked  Top 10 in Photoshop & Lightroom</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-the-ultimate-guide-to-navigating-stardews-ginger-island/"><u>[Updated] 2024 Approved  The Ultimate Guide to Navigating Stardew’s Ginger Island</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-for-overcoming-license-expiration-notice-in-win11/"><u>Tactics for Overcoming License Expiration Notice in Win11</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-iphone-13-pro-max-passcode-screen-by-drfone-ios/"><u>How to Unlock iPhone 13 Pro Max Passcode Screen?</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/approved-stop-unsolicited-youtube-suggestion-rollouts/"><u>2024 Approved  Stop Unsolicited YouTube Suggestion Rollouts</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-accessing-and-making-sense-of-twitter-archives/"><u>[Updated] 2024 Approved  Accessing and Making Sense of Twitter Archives</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-understanding-facebooks-real-time-content-restrictions/"><u>[Updated] 2024 Approved  Understanding Facebook's Real-Time Content Restrictions</u></a></li>
<li><a href="https://windows11.techidaily.com/significance-of-redistributing-visual-cplusplus/"><u>Significance of Redistributing Visual C++</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-essential-techniques-for-crafting-efficient-thumbnails/"><u>[New] Essential Techniques for Crafting Efficient Thumbnails</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-ideal-history-streams-the-10-premier-channels-for-students-study/"><u>In 2024, Ideal History Streams  The 10 Premier Channels for Students' Study</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-device-disconnection-problems-for-windows-users-with-virtualbox/"><u>Resolving Device Disconnection Problems for Windows Users with VirtualBox</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-your-windows-11-9-solutions-for-lost-bluetooth/"><u>Reviving Your Windows 11: 9 Solutions for Lost Bluetooth</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-audiotest-review/"><u>[Updated] In 2024, AudioTest Review</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-easily-connect-to-the-cloud-and-post-from-your-camera-roll-for-2024/"><u>[New] Easily Connect to the Cloud and Post From Your Camera Roll for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-guide-to-pocket-friendly-discord-video-downloads-on-tech-devices/"><u>2024 Approved  Guide to Pocket-Friendly Discord Video Downloads on Tech Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-for-frozen-downloads-restart-tracker-resume-progress/"><u>Quick-Fix for Frozen Downloads: Restart Tracker, Resume Progress</u></a></li>
</ul></div>
