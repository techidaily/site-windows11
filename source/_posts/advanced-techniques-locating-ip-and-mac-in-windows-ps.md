---
title: "Advanced Techniques: Locating IP & MAC in Windows PS"
date: 2024-07-03T11:17:41.273Z
updated: 2024-07-04T11:17:41.273Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Advanced Techniques: Locating IP & MAC in Windows PS"
excerpt: "This Article Describes Advanced Techniques: Locating IP & MAC in Windows PS"
keywords: PS IP Address Find,Windows PS MAC Location,Advanced PS IP Search,PS Mac Address Extraction,Windows PS Networking Tools,Techniques for PS IP/MAC,Identifying PS IP & MAC
thumbnail: https://thmb.techidaily.com/534bcc01d626eec0183aff232f0c9e211e75d3b58d6731fdc6da8a1b96d39a6c.jpg
---

## Advanced Techniques: Locating IP & MAC in Windows PS

 Have you been facing some network or troubleshooting issues on your PC? Or maybe you simply need to fix your access control or networking problems caused by your device or hardware. In cases like this, knowing your MAC or IP address will come in handy.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

## How to Find Your IP or MAC Address on a Windows Using the PowerShell

 Figuring out your IP address using [PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) is easy. Here's how you can get started:

1. Head to the **Start menu** search bar, type in 'powershell,' and select the best match.
2. Once the PowerShell is up, type in the following command and hit **Enter**:  
`Get-NetIPAddress <code class="language-powershell" lang="powershell">-AddressFamily IPV4`

 That's it; as soon as you type in this command, the PowerShell will give you the IPv4 addresses of all network adapters of your Windows system. As you can see below, you will get your PC's IP address, subnet mask, default gateway, etc.

![windows powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-3.jpg)

## Find the MAC Address on Your Windows

 Like your IP address, [finding out about your MAC address](https://www.makeuseof.com/how-to-find-mac-address-windows-11/) works somewhat similarly. Again, once you're inside the PowerShell, type in the following command on the shell and hit **Enter**:

`Get-NetAdapter`

 That's it; this command will give you the details about all the network adapters from your system, along with their MAC addresses. Look over at the "MacAddress" column, and you will get the address.

### An Alternate Way to Find the MAC Address on Windows

 While the "Get-NetAdapter" will work in most cases, we'd understand that if you'd want to try a different approach for any reason. In cases like that, the "ipconfig" command is your second-best bet.

 In fact, the "ipconfig" will give you all the information, which can make your screen unnecessarily complicated. So it's important that you filter out the fluff, and only get the information that you need. For that, add the "findstr "Description Physical"" section at the end of your command.

 Here's how you can do that:

`ipconfig /all | findstr "Description Physical"  
<img alt="windows powershell" height="665" src="https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-4.jpg" width="1200" />`

 Your adapter will be listed along with its MAC address, referenced by "Description" and "Physical Address".

## Finding Your IP or MAC Address on Windows PC

 So that's all about your IP or MAC address on your Windows PC. Type in the above commands, and you will get your MAC or IP addresses instantly. Of course, PowerShell is just one way of doing that. For instance, you can even find out your IP address on Windows with both settings menu and Command prompt. Knowing all the different methods, then, will come in handy in places like this.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/mending-solo-sound-output-in-windows-audio-device/"><u>Mending Solo Sound Output in Windows Audio Device</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secrets-to-overcome-directdraw-challenges-in-11-series-windows/"><u>Unveiling the Secrets to Overcome DirectDraw Challenges in 11-Series Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-to-quicken-windows-edge-on-w10-and-w11/"><u>Tips to Quicken Windows Edge on W10 & W11</u></a></li>
<li><a href="https://windows11.techidaily.com/make-your-windows-life-easier-with-proper-installation-steps/"><u>Make Your Windows Life Easier with Proper Installation Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-automatic-screenshore-changes-in-win11/"><u>Preventing Automatic Screenshore Changes in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-fixing-the-windows-error-0x800704b3/"><u>Understanding and Fixing the Windows Error: 0X800704B3</u></a></li>
<li><a href="https://windows11.techidaily.com/syncing-sound-levels-across-windows-and-bt-audio-gear/"><u>Syncing Sound Levels Across Windows and BT Audio Gear</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerate-search-results-in-windows-11-with-these-11-fixes/"><u>Accelerate Search Results in Windows 11 with These 11 Fixes</u></a></li>
<li><a href="https://printer-issues.techidaily.com/steps-to-troubleshoot-unresponsive-hp-print-subsystems/"><u>Steps to Troubleshoot Unresponsive HP Print Subsystems</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-easy-ways-to-change-location-on-youtube-tv-on-infinix-hot-30-5g-drfone-by-drfone-virtual-android/"><u>5 Easy Ways to Change Location on YouTube TV On Infinix Hot 30 5G | Dr.fone</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-unlock-the-power-of-voice-in-discord-a-tts-guide/"><u>[Updated] 2024 Approved  Unlock the Power of Voice in Discord  A TTS Guide</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-capture-every-moment-to-perfection-with-sj7s-new-4k-star-camera-review/"><u>In 2024, Capture Every Moment to Perfection with SJ7’s New 4K Star Camera Review</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/in-2024-top-5-tiktok-voice-generators-you-should-try/"><u>In 2024, Top 5 TikTok Voice Generators You Should Try</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-create-stunning-animations-the-top-tools-for-professionals-and-newbies-alike-for-2024/"><u>Updated Create Stunning Animations The Top Tools for Professionals and Newbies Alike for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/2024-approved-top-rated-free-flv-video-editing-tools/"><u>2024 Approved Top-Rated Free FLV Video Editing Tools</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-stream-anything-from-zte-blade-a73-5g-to-apple-tv-drfone-by-drfone-android/"><u>How To Stream Anything From ZTE Blade A73 5G to Apple TV | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/3-effective-ways-to-unlock-icloud-account-without-password-on-apple-iphone-13-pro-max-by-drfone-ios/"><u>3 Effective Ways to Unlock iCloud Account Without Password On Apple iPhone 13 Pro Max</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>