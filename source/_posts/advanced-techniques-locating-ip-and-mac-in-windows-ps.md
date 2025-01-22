---
title: "Advanced Techniques: Locating IP & MAC in Windows PS"
date: 2025-01-19T19:41:05.125Z
updated: 2025-01-22T19:52:39.292Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UoBCgLTmznE?si=MXXiGsd2qpd_DrzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Find Your IP or MAC Address on a Windows Using the PowerShell

 Figuring out your IP address using [PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) is easy. Here's how you can get started:

1. Head to the **Start menu** search bar, type in 'powershell,' and select the best match.
2. Once the PowerShell is up, type in the following command and hit **Enter**:  
`Get-NetIPAddress <code class="language-powershell" lang="powershell">-AddressFamily IPV4`

 That's it; as soon as you type in this command, the PowerShell will give you the IPv4 addresses of all network adapters of your Windows system. As you can see below, you will get your PC's IP address, subnet mask, default gateway, etc.

![windows powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-3.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_O8m9KphYzs?si=jITthzeyX_Kmt9X2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/j5gTm5KxtQ0?si=onF1rBS2nEM5nLGg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Find the MAC Address on Your Windows

 Like your IP address, [finding out about your MAC address](https://www.makeuseof.com/how-to-find-mac-address-windows-11/) works somewhat similarly. Again, once you're inside the PowerShell, type in the following command on the shell and hit **Enter**:

`Get-NetAdapter`

 That's it; this command will give you the details about all the network adapters from your system, along with their MAC addresses. Look over at the "MacAddress" column, and you will get the address.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c1yHj02oP3w?si=mwi3FyP0p68gkBqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### An Alternate Way to Find the MAC Address on Windows

 While the "Get-NetAdapter" will work in most cases, we'd understand that if you'd want to try a different approach for any reason. In cases like that, the "ipconfig" command is your second-best bet.

 In fact, the "ipconfig" will give you all the information, which can make your screen unnecessarily complicated. So it's important that you filter out the fluff, and only get the information that you need. For that, add the "findstr "Description Physical"" section at the end of your command.

 Here's how you can do that:

`ipconfig /all | findstr "Description Physical"  
<img alt="windows powershell" height="665" src="https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-4.jpg" width="1200" />`

 Your adapter will be listed along with its MAC address, referenced by "Description" and "Physical Address".

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5EKBEujWCw4?si=PwVvvervi8OrYaEA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://some-techniques.techidaily.com/new-huawei-p10-analysis-unveiling-performance-and-design/"><u>[New] Huawei P10 Analysis Unveiling Performance & Design</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-create-a-unique-identity-personalize-your-youtube-url-today/"><u>[Updated] 2024 Approved Create a Unique Identity Personalize Your YouTube URL Today</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-highlighted-6-exceptional-tools-for-cleaning-up-images-for-2024/"><u>[Updated] Highlighted 6 Exceptional Tools for Cleaning Up Images for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/a-harmonious-symphony-taming-your-computers-audio-irqs/"><u>A Harmonious Symphony: Taming Your Computer’s Audio IRQs</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerating-file-download-rates-in-utorrent-win-os-style/"><u>Accelerating File Download Rates in uTorrent, WIN OS Style</u></a></li>
<li><a href="https://solve-latest.techidaily.com/automated-personalization-with-the-help-of-cookiebot-technology/"><u>Automated Personalization with the Help of Cookiebot Technology</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-access-issues-enabling-windows-logins-post-fail/"><u>Clearing Access Issues: Enabling Windows Logins Post-Fail</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-your-workspace-pinning-techniques-for-w11/"><u>Customize Your Workspace: Pinning Techniques for W11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-can-we-unlock-our-realme-gt-neo-5-phone-screen-by-drfone-android/"><u>How Can We Unlock Our Realme GT Neo 5 Phone Screen?</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-train-your-dragon-movies-in-order/"><u>How to Train Your Dragon Movies in Order</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-remove-flashlight-from-iphone-8-plus-lock-screen-drfone-by-drfone-ios/"><u>In 2024, How To Remove Flashlight From iPhone 8 Plus Lock Screen | Dr.fone</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/izing-your-videos-impact-with-perfect-post-times-for-2024/"><u>Maximizing Your Videos' Impact with Perfect Post Times for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/remove-the-lock-screen-fingerprint-of-your-samsung-galaxy-a25-5g-by-drfone-android/"><u>Remove the Lock Screen Fingerprint Of Your Samsung Galaxy A25 5G</u></a></li>
</ul></div>

