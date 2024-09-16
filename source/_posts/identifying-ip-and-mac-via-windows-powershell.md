---
title: Identifying IP & MAC via Windows PowerShell
date: 2024-09-13T19:22:43.780Z
updated: 2024-09-15T22:10:03.019Z
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135399/19272" target="_top" id="2135399">
  <img src="//a.impactradius-go.com/display-ad/19272-2135399" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135399/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-farm-family-bonding-the-ultimate-agritainment-guide/"><u>[New] In 2024, Farm Family Bonding The Ultimate Agritainment Guide</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-the-smart-way-to-store-video-meetings-on-devices/"><u>[New] The Smart Way to Store Video Meetings on Devices</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-prime-video-communication-platforms-for-modern-tech/"><u>[Updated] Prime Video Communication Platforms for Modern Tech</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unveiling-youtubes-features-adding-images-to-videos/"><u>[Updated] Unveiling YouTube's Features Adding Images to Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-use-imessage-on-windows/"><u>How to Use iMessage on Windows</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-lava-storm-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Snapchat Location Spoofer to Protect Your Privacy On Lava Storm 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-window-10s-captions-with-minimal-trouble/"><u>Mastering Window 10'S Captions with Minimal Trouble</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-for-ms-store-crash-error-code-0x0-on-win-1011/"><u>Quick Fix for MS Store Crash: Error Code 0X0 on Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-alt-codes-glitches-50-characters/"><u>Resolving Windows ALT Codes Glitches (50 Characters)</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-best-android-sim-unlock-code-generators-unlock-your-honor-phone-hassle-free-by-drfone-android/"><u>The Best Android SIM Unlock Code Generators Unlock Your Honor Phone Hassle-Free</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-oppo-a78-device-by-drfone-android/"><u>The Ultimate Guide How to Bypass Swipe Screen to Unlock on Oppo A78 Device</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-ntfs-file-size-reduction/"><u>The Ultimate Guide to NTFS File Size Reduction</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-must-have-apps-to-maximize-your-windows-workflow/"><u>Top 5 Must-Have Apps to Maximize Your Windows Workflow</u></a></li>
</ul></div>

