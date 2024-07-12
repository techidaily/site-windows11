---
title: "Tweaking NetConfigs: Windows 11 Edition"
date: 2024-07-11T21:29:22.642Z
updated: 2024-07-12T21:29:22.642Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Tweaking NetConfigs: Windows 11 Edition"
excerpt: "This Article Describes Tweaking NetConfigs: Windows 11 Edition"
keywords: Win11 Config Tweaks,NetConfig Windows 11,XP Tweaker Guide,W11 Network Tuning,Windows 11 NETCONFIG,NetSetup Enhancements,OS Tweaking for W11
thumbnail: https://thmb.techidaily.com/16d13254afac9149dce0a2e443b3fbb7f20249bb61b5f6680c7797d944c293aa.jpg
---

## Tweaking NetConfigs: Windows 11 Edition

 Devices in a subnetwork have IP addresses that begin with the same prefix. The length of this prefix is different for different devices—it depends on the network size, whose length is identified using the subnet mask.

 While troubleshooting network issues, you must ensure that the subnet mask is correct. So, we'll share how to find and change the subnet in Windows 11.

## How to Find the Subnet Mask in Windows 11

 The easiest way to find the subnet mask in Windows 11 is through the [Windows Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) or Windows PowerShell. To find it using the Command Prompt, follow the steps below:

1. Press the**Win** key to launch the Start Menu.
2. In the search bar, type**Command Prompt** and choose the**Run as administrator** option from the right pane.
3. In the elevated Command Prompt window, type**ipconfig /all** and press Enter. This command will display all the important details about the network your computer is connected to, including the subnet mask.
4. Scroll and look for**Subnet Mask.** It'll be under the**Wireless LAN adapter Wi-Fi** section.  
![Finding the Subnet mask in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/finding-the-subnet-mask.jpg)

 The steps to do it using Windows PowerShell are similar to the Command Prompt. To do it,[open Windows PowerShell with admin rights](https://www.makeuseof.com/windows-11-powershell-administrator/) , type the ipconfig /all command, and press Enter.

 In the result that appears, you can see the subnet mask under the Wireless LAN adapter Wi-Fi section.

## How to Change the Subnet Mask in Windows 11

 Now that you know how to find the subnet mask on your computer, let's check out how to change it.

### 1\. Change the Subnet Mask Using the Windows Settings

 The settings menu is the central hub of a Windows operating system. It's a place to configure different settings of your computer and manage the network. You can also use it to change the subnet mask.

Here's how to do it:

1. [Open the Windows Systems Settings menu](https://www.makeuseof.com/windows-ways-to-open-system-settings/) , and choose**Network & internet** from the left panel.
2. Select**Wi-Fi,** and then choose your network in the following window.
3. Click the**Edit** button next to the**IP assignment** option.  
![Edit button in the Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/edit-button.jpg)
4. In the prompt that crops up, click on the drop-down icon and choose**Manual.**
5. Enable the toggle next to the IP version you're using.
6. Enter the details, including the subnet mask, and click**Save.**  
![Entering the new Subnet Mask in the Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/entering-the-new-subnet-mask.jpg)

### 2\. Change the Subnet Mask Using the Control Panel

 The Control Panel is the go-to place to configure window settings and make changes to your device. To use it to change the subnet mask, follow the below instructions:

1. Press the Win key, type**Control Panel** in the search bar, and press Enter.
2. Click the drop-down icon next to**View by** and choose**Large icons.**
3. Choose**Network and Internet** , and then select**Network and Sharing Center** in the following window.
4. Click on your network next to**Connections.**  
![Network name in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-name.jpg)
5. Choose**Properties** from the window that appears.
6. Select the IP version you're using. For instance, if you're using IPv4, select**Internet Protocol Version 4 (TCP/IPv4)** and click the**Properties** button.  
![IPv4 properties option in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/ipv4-properties.jpg)
7. Select the**Use the following address** option and enter the details.  
![Changing the Subnet Mask in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/changing-the-subnet-mask.jpg)
8. Click**OK** to save the changes.

### 3\. Change the Subnet Mask Using Windows PowerShell

 Windows PowerShell is also one of the places from where you can change the subnet mask in Windows 11\. Here's how to do it:

1. Open Windows PowerShell with admin rights, type the following command, and press Enter. This command will display all the network adapters installed on your device.  
`Get-NetAdapter -physical`
2. To change the subnet mask, type the following command and press Enter. Make sure to replace the "**ifIndex Number** " with the number associated with the network adapter whose subnet mask you want to change. And replace "**subnet prefix length** " with the new subnet prefix length you want.  
`Set-NetIPAddress -InterfaceIndex (ifIndex Number) -PrefixLength (subnet prefix length)`

 For instance, if the ifIndex Number is 3 and the new subnet prefix length you want is 24, then the command will be:

`Set-NetIPAddress -InterfaceIndex 3 -PrefixLength 24`

![Command to change the subnet mask in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/command-to-change-the-subnet-mask.jpg)

## Changing the Subnet Mask in Windows 11

 The subnet mask helps to identify the network and the host bit of the IP address. If you want to find and change the subnet mask on your computer, you can do it using either of the above methods.

 Meanwhile, you might be interested to know more about subnets and how to calculate them.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>



<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/windows-11-defender-how-to-deactivate-it/"><u>Windows 11 Defender: How to Deactivate It</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-mastering-basic-tone-alterations-in-ps/"><u>In 2024, Mastering Basic Tone Alterations in PS</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-ultimate-guide-from-infinix-zero-30-5g-frp-bypass-by-drfone-android/"><u>In 2024, Ultimate Guide from Infinix Zero 30 5G FRP Bypass</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-shutdown-how-to-pause-windows-11/"><u>Quick Shutdown: How to Pause Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/reintroduce-forgotten-bluetooth-items-devices-mgr/"><u>Reintroduce Forgotten Bluetooth Items Devices Mgr</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-variances-microsoft-account-versus-conventional-local-login/"><u>Unveiling Variances: Microsoft Account Versus Conventional Local Login</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-10-telegram-spy-tools-on-oppo-reno-10-5g-for-parents-drfone-by-drfone-virtual-android/"><u>In 2024, Top 10 Telegram Spy Tools On Oppo Reno 10 5G for Parents | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-efficient-application-batch-deployment-via-winstall/"><u>Windows 11: Efficient Application Batch Deployment via Winstall</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-ea-server-connection-failure-in-windows/"><u>Resolving EA Server Connection Failure in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixed-top-10-windows-glitch-solvers/"><u>Quick Fixed: Top 10 Windows Glitch Solvers</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-fix-wins-unhandled-exception-blue-screen-problem/"><u>Methods to Fix Win's Unhandled Exception Blue Screen Problem</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-work-with-non-verified-windows-apps/"><u>Techniques to Work with Non-Verified Windows Apps</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/expert-roundup-the-best-editing-software-for-youtube-creators/"><u>Expert Roundup  The Best Editing Software for YouTube Creators</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-potential-the-top-7-ways-to-optimize-windows-11-use-42/"><u>Unlocking Potential: The Top 7 Ways to Optimize Windows 11 Use (42)</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-screenshotting-windows-security-alerts/"><u>Techniques for Screenshotting Windows' Security Alerts</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-creating-a-social-media-impact-the-art-of-using-hashtags-on-fb/"><u>[Updated] Creating a Social Media Impact  The Art of Using Hashtags on FB</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-telnet-configuration-three-essential-steps-for-wins-oses/"><u>Secure Telnet Configuration: Three Essential Steps for Wins OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-error-x80780119/"><u>Troubleshooting Windows' Error X80780119</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-league-of-legends-playability-on-pc/"><u>Restoring League of Legends Playability on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-path-not-found-issue-in-windows-xp7/"><u>Resolving Path Not Found Issue in Windows XP/7</u></a></li>
<li><a href="https://windows11.techidaily.com/what-is-the-windows-portable-executable-file-format/"><u>What Is the Windows Portable Executable File Format?</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-remedying-error-code-0x80300024/"><u>Understanding and Remedying Error Code: 0X80300024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-free-extension-software-leaders-in-chromebook-video-recording/"><u>2024 Approved  Free Extension Software Leaders in Chromebook Video Recording</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-for-windows-update-failure-at-error-0xca00a009/"><u>Remedy for Windows Update Failure at Error 0xCA00A009</u></a></li>
<li><a href="https://windows11.techidaily.com/transforming-ideas-to-art-the-leading-7-drawing-apps-for-win10-users/"><u>Transforming Ideas to Art: The Leading 7 Drawing Apps for Win10 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-an-old-pc-heres-why-you-might-want-to-ditch-windows/"><u>Reviving an Old PC? Here's Why You Might Want to Ditch Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-device-functionality-in-windows-11/"><u>Optimize Device Functionality in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-overcoming-printer-not-connected-problems/"><u>Win11: Overcoming Printer Not Connected Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-non-persistent-print-device-selection/"><u>Troubleshooting: Non-Persistent Print Device Selection</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-code-workflows-with-windows-11s-developer-environment/"><u>Streamlining Code Workflows with Windows 11'S Developer Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-enhancing-your-search-system/"><u>Windows 11: Enhancing Your Search System</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-onedrive-errors-efficient-steps-for-instant-folder-addition/"><u>Overcoming Windows OneDrive Errors - Efficient Steps for Instant Folder Addition</u></a></li>
<li><a href="https://windows11.techidaily.com/rejuvenate-your-locked-shift-key-in-windows/"><u>Rejuvenate Your Locked Shift Key in Windows.</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-restore-missing-watch-artwork/"><u>[Updated] In 2024, Restore Missing Watch Artwork</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-efficiency-top-6-ideas-to-overhaul-windows-11s-taskbar-layout/"><u>Maximizing Efficiency: Top 6 Ideas to Overhaul Windows 11'S Taskbar Layout</u></a></li>
<li><a href="https://windows11.techidaily.com/purpose-and-key-aspects-of-vcplusplus-distributions/"><u>Purpose & Key Aspects of VC++ Distributions</u></a></li>
<li><a href="https://howto.techidaily.com/want-to-uninstall-google-play-service-from-oppo-reno-8t-here-is-how-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Want to Uninstall Google Play Service from Oppo Reno 8T? Here is How | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-unreachable-issues-with-malwarebytes-on-win11/"><u>Resolving Unreachable Issues with Malwarebytes on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-windows-update-error-0x8024800c/"><u>Tackling Windows Update: Error 0X8024800C</u></a></li>
<li><a href="https://extra-tips.techidaily.com/crystalline-speed-highlighting-moments-from-the-coldest-games-on-earth/"><u>Crystalline Speed  Highlighting Moments From the Coldest Games on Earth</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/2024-approved-unlock-your-chromebook-how-to-run-linux/"><u>2024 Approved Unlock Your Chromebook How to Run Linux</u></a></li>
<li><a href="https://windows11.techidaily.com/rebuilding-dotnet-windows-fixes-to-remember-max-156/"><u>Rebuilding DotNet: Windows Fixes to Remember (Max 156)</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-security-refreshing-windows-group-policies/"><u>Streamlining Security: Refreshing Windows Group Policies</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/10-best-no-cost-video-calls-for-remote-collaboration/"><u>10 Best No-Cost Video Calls for Remote Collaboration</u></a></li>
<li><a href="https://windows11.techidaily.com/secret-menu-additions-a-step-by-step-guide-in-win-10/"><u>Secret Menu Additions: A Step-by-Step Guide in Win 10</u></a></li>
<li><a href="https://windows11.techidaily.com/switch-onoff-windows-filter-keys-guide/"><u>Switch On/Off: Window's Filter Keys Guide</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-final-cut-pro-x-adding-text-titles-and-lower-thirds-like-a-pro/"><u>New 2024 Approved Final Cut Pro X Adding Text, Titles, and Lower Thirds Like a Pro</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-what-is-the-best-frame-rate-for-slow-motion-video/"><u>2024 Approved  What Is The Best Frame Rate For Slow Motion Video?</u></a></li>
<li><a href="https://windows11.techidaily.com/regaining-normalcy-in-windows-11-user-access/"><u>Regaining Normalcy in Windows 11 User Access</u></a></li>
</ul></div>
