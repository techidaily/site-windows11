---
title: "Hide Your Wireless Signal: Windows Techniques"
date: 2024-09-05T02:08:01.977Z
updated: 2024-09-06T02:08:01.977Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Hide Your Wireless Signal: Windows Techniques"
excerpt: "This Article Describes Hide Your Wireless Signal: Windows Techniques"
keywords: Hide Wi-Fi Signals Windows,Disable Wireless Windows,Mask Wireless Windows Pro,Stealth Wireless Windows,Conceal Windows SSID,Invisible Wi-Fi Windows,Suppress Windows Networking
thumbnail: https://thmb.techidaily.com/571b6953560c969952a7e82657ab3c73d752ed211ca4fd673ea682421459ce79.png
---

## Hide Your Wireless Signal: Windows Techniques

 By default, Windows displays all available Wi-Fi networks close to your device. Even if the networks are insecure, don't have parental controls enabled, or are just named inappropriately, Windows does not make an exception to block or hide them automatically.

 If you spot such a network and want to stop it from appearing among available Wi-Fi networks to prevent your children or yourself from viewing or accidentally connecting to it, here's how you can do that.

## How to Hide or Block a Wi-Fi Network on Windows

 Follow these steps to [use the Windows Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) to stop a Wi-Fi network from showing up among the available networks:

1. Type"Command Prompt" into Windows Search, right-click on the **Command Prompt** app and then click **Run as administrator**.
2. Note the full name of the network you intend to block or hide.
3. Enter the name of the Wi-Fi network next to the SSID field in the following command:  
`netsh wlan add filter permission=block ssid="add the name of the Wi-Fi network you want to block here" networktype=infrastructure`
4. Copy and paste the command into the Command Prompt app and press **Enter**.  
![Block the Wi-Fi Network By Running a Command in Command Prompt on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/block-the-wi-fi-network-by-running-a-command-in-command-prompt-on-windows.jpg)

 If you see the message "The filter is added on the system successfully," the Wi-Fi network has been blocked, and it'll no longer appear in your Wi-Fi list. While the above steps will indeed block the Wi-Fi network, it will reappear among the available networks if the owner decides to [rename the Wi-Fi adapter](https://www.makeuseof.com/windows-11-rename-network-adapter/).

 If you change your mind and want to unblock the network you just blocked, enter the following command into the Command Prompt after entering the blocked network name:

`netsh wlan delete filter permission=block ssid="add the of the name of the Wi-Fi network you want to unblock here" networktype=infrastructure`

![Remove the Blocked Filter to Unblock the Wi-Fi Network Using the Windows Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/remove-the-blocked-filter-to-unblock-the-wi-fi-network-using-the-windows-command-prompt.jpg)

## Block Suspicious Wi-Fi Networks on Windows

 When a network is named inappropriately or looks suspicious owing to the lack of a password or protection, blocking it becomes imperative. Hopefully, now you know how to block and unblock a Wi-Fi network in the Command Prompt by running simple commands.

 While blocking other networks is essential, securing your network from prying eyes is equally important in maintaining your security and privacy.

 If you spot such a network and want to stop it from appearing among available Wi-Fi networks to prevent your children or yourself from viewing or accidentally connecting to it, here's how you can do that.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1175223/12108" target="_top" id="1175223">
  <img src="//a.impactradius-go.com/display-ad/12108-1175223" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1175223/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->