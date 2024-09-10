---
title: Identifying IP & MAC via Windows PowerShell
date: 2024-09-09T12:11:25.475Z
updated: 2024-09-10T12:11:25.475Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Identifying IP & MAC via Windows PowerShell
excerpt: This Article Describes Identifying IP & MAC via Windows PowerShell
keywords: Find IP Address,Locate Mac Address,Windows PowerShell Scripts,IP Identification Tool,MAC Address Extraction,Powershell Network Tools,Detecting Devices in PC,Windows IP Locator,Mac Finder Script,PowerShell Dev Tools
thumbnail: https://thmb.techidaily.com/51c7e118bec96598bc9d2d2c18cf903e1dca3cd5201c33fd6a45fd74bf88fe0d.jpg
---

<!-- affiliate ads begin -->
<span id="1743243">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1743243.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19272-1743243">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1743243.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Faligracehair.sjv.io%2Fc%2F5597632%2F1743243%2F19272'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1743243/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Identifying IP & MAC via Windows PowerShell

 Have you been facing some network or troubleshooting issues on your PC? Or maybe you simply need to fix your access control or networking problems caused by your device or hardware. In cases like this, knowing your MAC or IP address will come in handy.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

<!-- affiliate ads begin -->
<span id="1160850">
					<video width="576" height="324" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1160850.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1160850">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1160850.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1160850%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1160850/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Find Your IP or MAC Address on a Windows Using the PowerShell

 Figuring out your IP address using [PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) is easy. Here's how you can get started:

1. Head to the **Start menu** search bar, type in 'powershell,' and select the best match.
2. Once the PowerShell is up, type in the following command and hit **Enter**:  
`Get-NetIPAddress <code class="language-powershell" lang="powershell">-AddressFamily IPV4`

 That's it; as soon as you type in this command, the PowerShell will give you the IPv4 addresses of all network adapters of your Windows system. As you can see below, you will get your PC's IP address, subnet mask, default gateway, etc.

![windows powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-3.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115943/19272" target="_top" id="2115943">
  <img src="//a.impactradius-go.com/display-ad/19272-2115943" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115943/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135417/19272" target="_top" id="2135417">
  <img src="//a.impactradius-go.com/display-ad/19272-2135417" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135417/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Find the MAC Address on Your Windows

 Like your IP address, [finding out about your MAC address](https://www.makeuseof.com/how-to-find-mac-address-windows-11/) works somewhat similarly. Again, once you're inside the PowerShell, type in the following command on the shell and hit **Enter**:

`Get-NetAdapter`

 That's it; this command will give you the details about all the network adapters from your system, along with their MAC addresses. Look over at the "MacAddress" column, and you will get the address.

<!-- affiliate ads begin -->
<span id="1938141">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1938141.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1938141">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1938141.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1938141%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1938141/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### An Alternate Way to Find the MAC Address on Windows

 While the "Get-NetAdapter" will work in most cases, we'd understand that if you'd want to try a different approach for any reason. In cases like that, the "ipconfig" command is your second-best bet.

 In fact, the "ipconfig" will give you all the information, which can make your screen unnecessarily complicated. So it's important that you filter out the fluff, and only get the information that you need. For that, add the "findstr "Description Physical"" section at the end of your command.

 Here's how you can do that:

`ipconfig /all | findstr "Description Physical"  
<img alt="windows powershell" height="665" src="https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-4.jpg" width="1200" />`

 Your adapter will be listed along with its MAC address, referenced by "Description" and "Physical Address".

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115927/19272" target="_top" id="2115927">
  <img src="//a.impactradius-go.com/display-ad/19272-2115927" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115927/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Finding Your IP or MAC Address on Windows PC

 So that's all about your IP or MAC address on your Windows PC. Type in the above commands, and you will get your MAC or IP addresses instantly. Of course, PowerShell is just one way of doing that. For instance, you can even find out your IP address on Windows with both settings menu and Command prompt. Knowing all the different methods, then, will come in handy in places like this.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-easy-storage-solutions-for-androidmac-snaps-on-devices/"><u>[New] 2024 Approved Easy Storage Solutions for Android/Mac Snaps on Devices</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-instaboomtown-building-community-with-loop-videos/"><u>[New] 2024 Approved InstaBoomtown Building Community with Loop Videos</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-fixing-blurred-footage-in-social-media-streaming-for-2024/"><u>[New] Fixing Blurred Footage in Social Media Streaming for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-easy-recording-tips-for-your-hp-laptops-camera/"><u>[New] In 2024, Easy Recording Tips for Your HP Laptop's Camera</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-mastering-multi-platform-skype-group-formation/"><u>[New] In 2024, Mastering Multi-Platform Skype Group Formation</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-revealing-the-best-free-screen-capture-tools-for-your-camera/"><u>[New] In 2024, Revealing the Best Free Screen Capture Tools for Your Camera</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-troubleshooting-messengers-failure-send-videos-without-issues-androidiphone/"><u>[New] In 2024, Troubleshooting Messenger's Failure Send Videos without Issues (Android/iPhone)</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-decoding-veiled-content-on-youtube/"><u>[Updated] 2024 Approved Decoding Veiled Content on YouTube</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-mastering-obs-and-zoom-integration-tips/"><u>[Updated] 2024 Approved Mastering OBS & Zoom Integration Tips</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-best-mac-screen-capture-tools-for-2024/"><u>[Updated] Best Mac Screen Capture Tools for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-pioneering-quests-and-thrills-top-10-game-wonders-top-10/"><u>2024 Approved Pioneering Quests & Thrills – Top 10 Game Wonders (Top 10)</u></a></li>
<li><a href="https://win-dash.techidaily.com/best-behringer-sound-enhancers-available-for-immediate-download/"><u>Best Behringer Sound Enhancers Available for Immediate Download</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-call-history-from-itel-p55-5g-by-fonelab-android-recover-call-logs/"><u>Easy steps to recover deleted call history from Itel P55 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/explore-the-full-potential-of-windows-powertoys-with-these-10-tips/"><u>Explore the Full Potential of Windows PowerToys with These 10 Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/exposing-the-wacatacbml-trojan-your-ultimate-windows-protection-plan/"><u>Exposing the Wacatac.B!ml Trojan - Your Ultimate Windows Protection Plan</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/hacks-to-do-pokemon-go-trainer-battles-for-oppo-find-x7-drfone-by-drfone-virtual-android/"><u>Hacks to do pokemon go trainer battles For Oppo Find X7 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-correct-gl-error-3-with-nvidia-on-windows-oses/"><u>How to Correct GL Error 3 with Nvidia on WIndows OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-prevent-auto-restart-events-on-win11/"><u>How to Prevent Auto-Restart Events on Win11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-corrupt-excel-2019-files-by-stellar-guide/"><u>How to Repair Corrupt Excel 2019 Files</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-troubleshoot-high-cpu-usage-with-the-windows-resource-monitor/"><u>How to Troubleshoot High CPU Usage With the Windows Resource Monitor</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-cards-of-xiaomi-redmi-13c-5g-without-puk-codes-by-drfone-android/"><u>How To Unlock SIM Cards Of Xiaomi Redmi 13C 5G Without PUK Codes</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-wash-away-your-computers-defender-past/"><u>How to Wash Away Your Computer's Defender Past</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-your-realme-narzo-60x-5g-location-on-twitter-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change your Realme Narzo 60x 5G Location on Twitter | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/keyboard-commands-for-optimal-windows-photo-editing/"><u>Keyboard Commands for Optimal Windows Photo Editing</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-law-filters-in-windows-an-experts-perspective/"><u>Leveraging LAW Filters in Windows – An Expert's Perspective</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-network-configurations-in-windows-os/"><u>Mastering Network Configurations in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-win11s-accessibility-keys/"><u>Mastering Win11's Accessibility Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-non-working-escape-keys-on-your-windows-system/"><u>Navigating Non-Working Escape Keys on Your Windows System</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-maze-of-chrome-profile-disruptions-on-desktop/"><u>Navigating the Maze of Chrome Profile Disruptions on Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-disconnection-issues-of-razer-hardware-in-win-1011/"><u>Overcoming Disconnection Issues of Razer Hardware in Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/precise-control-setup-adjusting-shortcut-locations-on-windows-11s-power-icon/"><u>Precise Control Setup: Adjusting Shortcut Locations on Windows 11'S Power Icon</u></a></li>
<li><a href="https://article-helps.techidaily.com/professional-shutter-sense-the-prime-6-4k-dslr-selections/"><u>Professional Shutter Sense The Prime 6 4K DSLR Selections</u></a></li>
<li><a href="https://windows11.techidaily.com/regaining-access-post-failed-windows-login-attempt/"><u>Regaining Access Post Failed Windows Login Attempt</u></a></li>
<li><a href="https://windows11.techidaily.com/regaining-access-fixing-malwarebytes-service-errors-in-windows-1011/"><u>Regaining Access: Fixing Malwarebytes' Service Errors in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-empty-directory-issue-windows-1011-error-x80070091/"><u>Resolving Empty Directory Issue - Windows 10/11 Error X80070091</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-lost-connection-re-list-bluetooth-in-dmi/"><u>Reviving Lost Connection: Re-List Bluetooth in DMI</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-connection-lost-5-easy-steps-for-a-fixed-usb-wi-fi-adapter/"><u>Seamless Connection Lost? 5 Easy Steps for a Fixed USB Wi-Fi Adapter</u></a></li>
<li><a href="https://windows11.techidaily.com/stay-ahead-postpone-windows-edge-tabs-on-w11/"><u>Stay Ahead: Postpone Windows Edge Tabs on W11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-tackle-missing-device-driver-issue-on-windows-startup/"><u>Steps to Tackle Missing Device Driver Issue on Windows Startup</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-cut-down-energy-use-of-wlanextexe/"><u>Strategies to Cut Down Energy Use of Wlanext.EXE</u></a></li>
<li><a href="https://windows11.techidaily.com/top-techniques-for-disabling-windows-11-tpm/"><u>Top Techniques for Disabling Windows 11 TPM</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-non-loading-drivers-in-windows-11/"><u>Troubleshooting Non-Loading Drivers in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-ignoring-local-lsa-warning/"><u>Troubleshooting Windows: Ignoring Local LSA Warning</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-remote-problem-invisible-screen/"><u>Unveiling Windows Remote Problem: Invisible Screen</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>