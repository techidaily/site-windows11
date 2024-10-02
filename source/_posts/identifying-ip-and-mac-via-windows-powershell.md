---
title: Identifying IP & MAC via Windows PowerShell
date: 2024-09-28T02:29:30.183Z
updated: 2024-10-02T00:20:46.024Z
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

## Identifying IP & MAC via Windows PowerShell

 Have you been facing some network or troubleshooting issues on your PC? Or maybe you simply need to fix your access control or networking problems caused by your device or hardware. In cases like this, knowing your MAC or IP address will come in handy.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

## How to Find Your IP or MAC Address on a Windows Using the PowerShell

 Figuring out your IP address using [PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) is easy. Here's how you can get started:

1. Head to the **Start menu** search bar, type in 'powershell,' and select the best match.
2. Once the PowerShell is up, type in the following command and hit **Enter**:  
`Get-NetIPAddress <code class="language-powershell" lang="powershell">-AddressFamily IPV4`

 That's it; as soon as you type in this command, the PowerShell will give you the IPv4 addresses of all network adapters of your Windows system. As you can see below, you will get your PC's IP address, subnet mask, default gateway, etc.

![windows powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-3.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925570/19272" target="_top" id="1925570">
  <img src="//a.impactradius-go.com/display-ad/19272-1925570" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925570/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Find the MAC Address on Your Windows

 Like your IP address, [finding out about your MAC address](https://www.makeuseof.com/how-to-find-mac-address-windows-11/) works somewhat similarly. Again, once you're inside the PowerShell, type in the following command on the shell and hit **Enter**:

`Get-NetAdapter`

 That's it; this command will give you the details about all the network adapters from your system, along with their MAC addresses. Look over at the "MacAddress" column, and you will get the address.

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1828647/21290" target="_top" id="1828647">
  <img src="//a.impactradius-go.com/display-ad/21290-1828647" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://versadesk.pxf.io/i/5597632/1828647/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### An Alternate Way to Find the MAC Address on Windows

 While the "Get-NetAdapter" will work in most cases, we'd understand that if you'd want to try a different approach for any reason. In cases like that, the "ipconfig" command is your second-best bet.

 In fact, the "ipconfig" will give you all the information, which can make your screen unnecessarily complicated. So it's important that you filter out the fluff, and only get the information that you need. For that, add the "findstr "Description Physical"" section at the end of your command.

 Here's how you can do that:

`ipconfig /all | findstr "Description Physical"  
<img alt="windows powershell" height="665" src="https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-4.jpg" width="1200" />`

 Your adapter will be listed along with its MAC address, referenced by "Description" and "Physical Address".

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/1943647/22993" target="_top" id="1943647">
  <img src="//a.impactradius-go.com/display-ad/22993-1943647" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://homestyler.sjv.io/i/5597632/1943647/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Finding Your IP or MAC Address on Windows PC

 So that's all about your IP or MAC address on your Windows PC. Type in the above commands, and you will get your MAC or IP addresses instantly. Of course, PowerShell is just one way of doing that. For instance, you can even find out your IP address on Windows with both settings menu and Command prompt. Knowing all the different methods, then, will come in handy in places like this.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-keep-your-music-memories-intact-top-three-storage-methods/"><u>[Updated] 2024 Approved Keep Your Music Memories Intact Top Three Storage Methods</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-a-decade-of-dreamy-vacation-flicks-top-10-titles/"><u>[Updated] In 2024, A Decade of Dreamy Vacation Flicks Top 10 Titles</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-moonlight-mastery-a-photographers-guidebook-to-nighttime-imagery/"><u>[Updated] In 2024, Moonlight Mastery A Photographer's Guidebook to Nighttime Imagery</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-transforming-standard-calls-into-visual-masterpieces-with-zoom/"><u>[Updated] Transforming Standard Calls Into Visual Masterpieces with Zoom</u></a></li>
<li><a href="https://windows11.techidaily.com/9-insights-on-how-pc-outperforms-a-mac-in-essential-areas/"><u>9 Insights on How PC Outperforms a Mac in Essential Areas</u></a></li>
<li><a href="https://windows11.techidaily.com/a-closer-look-at-windows-sound-system-segregation/"><u>A Closer Look at Windows' Sound System Segregation</u></a></li>
<li><a href="https://windows11.techidaily.com/batch-folder-generation-in-windows-11-for-efficiency-boost/"><u>Batch Folder Generation in Windows 11 for Efficiency Boost</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-print-speed-on-pcs-tips-for-windows-users/"><u>Boosting Print Speed on PCs: Tips for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/booting-up-windows-sound-service-quick-fix-steps/"><u>Booting Up Windows Sound Service: Quick Fix Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-windows-java-installation-roadblocks/"><u>Clearing Windows Java Installation Roadblocks</u></a></li>
<li><a href="https://windows11.techidaily.com/comparing-ease-of-use-in-soft-installation-tools/"><u>Comparing Ease of Use in Soft Installation Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/cracking-the-code-fixing-windows-pin-failures/"><u>Cracking the Code: Fixing Windows PIN Failures</u></a></li>
<li><a href="https://windows11.techidaily.com/credential-control-in-win11-quick-ways-to-unlock-passwords/"><u>Credential Control in Win11: Quick Ways to Unlock Passwords</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/embrace-the-synergy-streaming-fb-videos-through-your-apple-device/"><u>Embrace the Synergy Streaming FB Videos Through Your Apple Device</u></a></li>
<li><a href="https://sound-issues.techidaily.com/expert-fixes-for-the-dead-microphone-on-steelseries-arctis-prime-headset/"><u>Expert Fixes for the Dead Microphone on SteelSeries Arctis Prime Headset</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/groan-inducing-humor-in-hits/"><u>Groan-Inducing Humor in Hits</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-iphone-11-pro-max-without-passcode-4-easy-methods-by-drfone-ios/"><u>How To Unlock iPhone 11 Pro Max Without Passcode? 4 Easy Methods</u></a></li>
<li><a href="https://extra-information.techidaily.com/mastering-facetune-a-thorough-app-guide/"><u>Mastering Facetune A Thorough App Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/transform-your-arw-images-into-jpgs-swiftly-across-pcs-and-macs-simple-4-step-procedure-revealed/"><u>Transform Your ARW Images Into JPGs Swiftly Across PCs and Macs – Simple 4-Step Procedure Revealed</u></a></li>
</ul></div>

