---
title: Revealing the Make of Your Windows Machine in Six Steps
date: 2024-07-11T22:08:10.802Z
updated: 2024-07-12T22:08:10.802Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Revealing the Make of Your Windows Machine in Six Steps
excerpt: This Article Describes Revealing the Make of Your Windows Machine in Six Steps
keywords: Windows OS Identification,Uncovering Windows Model,Detect Windows Version,Windows Machine Type,Windows Release Decoding,Pinpoint Windows Build,Discover Windows Edition
thumbnail: https://thmb.techidaily.com/ee5c0d7e477d155cf7c4d7a41bb4baf523bd4dd370c1eec84bd95b2e762714db.png
---

## Revealing the Make of Your Windows Machine in Six Steps

 Whether you want to find the correct hardware upgrade for your computer or want to fix an issue, knowing about your computer model name can come in handy in various situations. Here are 6 quick ways to check your computer model name on Windows.

## 1\. Using the Settings App

![Checking System Name in the Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-name.jpg)

 The quickest way to check your computer model name and number is through the Settings app. Simply, launch the**Settings app** (see [how to open the Settings app on Windows](https://www.makeuseof.com/windows-ways-to-open-system-settings/) ) and choose**System** from the left sidebar. You'll see your computer model name at the top of the System window.

## 2\. Using the System Information App

 The System Information is the go-to place to [check your system information on Windows 11](https://www.makeuseof.com/windows-11-check-system-information/) . You can use it to know about your computer's hardware resources, components, and software environment.

 To see your computer model name using the System Information app, follow the below instructions:

1. Press the**Win + S** hotkeys to open**Windows Search.**
2. In the search bar, type**System Information** and choose**Open** from the right pane.  
![Typing System Information in Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-information.jpg)
3. Choose**System Summary** from the left sidebar.
4. Check the**System Model** row in the right pane to know about your computer model name.  
![Checking System Model in System Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-model.jpg)

## 3\. Using the DirectX Diagnostic Tool

 The DirectX Diagnostic Tool contains information about the DirectX components and drivers installed on your computer. You can also use this tool to get information like System model, BIOS, Processor, Memory, Page file, and more.

 Here's how to use the DirectX Diagnostic Tool to know about your system model name:

1. Use one of the [many ways to open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. In the text field, type**dxdiag** and click**OK.**
3. Click the**System** tab in the DirectX Diagnostic Tool.
4. Under the System Information section, you can check your computer model name next to the**System Model** option.  
![System Model option in the DirectX Diagnostic Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-model-option.jpg)

## 4\. Using the Command-Line Tools

 If you're an advanced Windows user, you can use the command-line tools, Windows PowerShell and Command Prompt, to know everything about your computer. Here's how to use the Command Prompt to check your computer model name:

1. Open the Windows Search, type**Command Prompt** in the search bar, and press Enter.
2. In the Command Prompt window, type**wmic csproduct get name** , and press Enter.  
![System model checking command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-model-checking-command.jpg)

You'll see the model name on the console screen.

 Now, to view the model name using Windows PowerShell, launch Windows PowerShell, type the following command, and press Enter.

`Get-CimInstance -ClassName Win32_ComputerSystem`

![Command to Check System name in Windows PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/command-to-check-system-name.jpg)

 In case you want to check your computer serial number, execute the following command in the PowerShell window.

`Get-CimInstance -ClassName Win32_bios`

![Command to Check System Serial number in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/command-to-check-system-serial-number.jpg)

## 5\. Using the Manufacturer's Assistant App

![Checking System name using HP Support Assistant](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/hp-support-assistant.jpg)

 Most manufacturers nowadays offer an assistant app using which you can check your computer model name and number. For instance, if you're using an HP laptop, you can download the [HP Support Assistant app](https://support.hp.com/us-en/help/hp-support-assistant) to know everything about your computer.

 Similarly, you can download the assistant app of your manufacturer to check your computer's name.

## 6\. By Entering the BIOS

 The Basic Input / Output System, aka BIOS, lets you configure basic computer settings like boot order, hardware components, and more. You can also use the BIOS menu to know every tiny detail about your computer.

 Here's how to [enter the BIOS menu on Windows](https://www.makeuseof.com/tag/enter-bios-computer/) and check your computer model name:

1. Open the Settings app, and choose**Windows Update** from the left sidebar.
2. Choose the**Advanced options.**
3. Under**Additional options,** select the**Recovery** option.
4. Click the**Restart now** button next to**Advanced startup.** Your computer will not boot into Recovery mode.  
![Restart now button next to Advanced startup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/restart-now-button.jpg)
5. Navigate to**Troubleshoot** \>**Advanced options** \>**UEFI Firmware Settings** \>**Restart.**
6. Usually, your computer will now boot straight into UEFI BIOS. But in some manufacturers like HP, you'll be welcomed with a**Startup** **Menu.** Choose**System Information** from the menu.  
![Choosing System Information from the Startup menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/choosing-system-information.JPG)
7. You can check your computer name in the System Information section.  
![Checking Product name in System Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/checking-product-name.JPG)

## Get to Know Your Computer's Model on Windows

 These were all the working ways using which you can know your computer model name. However there are many other methods to check the name, but the ones mentioned above are among the quickest and easiest.

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
<li><a href="https://windows11.techidaily.com/addressing-windows-photos-problem-package-not-registered/"><u>Addressing Windows Photos Problem - Package Not Registered</u></a></li>
<li><a href="https://windows11.techidaily.com/5-proven-strategies-for-superior-windows-11-search-performance/"><u>5 Proven Strategies for Superior Windows 11 Search Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-proxy-in-windows-11-for-enhanced-privacy/"><u>Adjusting Proxy in Windows 11 for Enhanced Privacy</u></a></li>
<li><a href="https://vp-tips.techidaily.com/foremost-12-gps-enabled-cctv-cameras-for-motion-recording/"><u>Foremost 12 GPS-Enabled CCTV Cameras for Motion Recording</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-windows-vram-a-step-by-step-guide/"><u>Boosting Windows VRAM: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/a-step-by-step-guide-to-modifying-windows-file-attributes/"><u>A Step-by-Step Guide to Modifying Windows File Attributes</u></a></li>
<li><a href="https://windows11.techidaily.com/boot-old-gear-into-latest-windows-11-22h2/"><u>Boot Old Gear Into Latest Windows 11 22H2</u></a></li>
<li><a href="https://windows11.techidaily.com/arp-cache-in-windows-what-and-how-to-purge/"><u>ARP Cache in Windows: What and How to Purge?</u></a></li>
<li><a href="https://windows11.techidaily.com/best-data-shields-on-windows-encryption-apps-analysis-150-chars/"><u>Best Data Shields on Windows: Encryption Apps Analysis (150 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/1719361633854-enhance-your-pcs-screen-glow-with-these-fixes/"><u>Enhance Your PC's Screen Glow with These Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/beat-the-burn-how-to-cool-down-your-gamers-windows-laptop/"><u>Beat The Burn: How to Cool Down Your Gamers’ Windows Laptop</u></a></li>
<li><a href="https://windows11.techidaily.com/a-new-look-for-you-top-methods-to-alter-windows-11-themes/"><u>A New Look for You: Top Methods to Alter Windows 11 Themes</u></a></li>
<li><a href="https://windows11.techidaily.com/access-androids-gaming-joy-on-pc-from-phone-to-window-11-via-google-linkup/"><u>Access Android's Gaming Joy on PC: From Phone to Window 11 via Google Linkup</u></a></li>
<li><a href="https://windows11.techidaily.com/a-harmonious-symphony-taming-your-computers-audio-irqs/"><u>A Harmonious Symphony: Taming Your Computer’s Audio IRQs</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-step-by-step-tips-for-green-screen-cinematography-success/"><u>[New] Step-by-Step Tips for Green Screen Cinematography Success</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/how-to-pick-a-youtube-channel-name-for-2024/"><u>How To Pick a YouTube Channel Name for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-premier-movie-sneak-peeks-ensemble/"><u>2024 Approved  Premier Movie Sneak Peeks Ensemble</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-fix-pokemon-go-route-not-working-on-infinix-hot-40-pro-drfone-by-drfone-virtual-android/"><u>How to Fix Pokemon Go Route Not Working On Infinix Hot 40 Pro? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-insufficient-access-errors-during-software-removal/"><u>Avoiding Insufficient Access Errors During Software Removal</u></a></li>
<li><a href="https://windows11.techidaily.com/antiquated-tech-awakened-atlasos-upgrade/"><u>Antiquated Tech Awakened: AtlasOS Upgrade</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-from-pixels-to-perfection-selecting-the-premier-screen-recording-software/"><u>In 2024, From Pixels to Perfection  Selecting the Premier Screen Recording Software</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-non-existent-files-message-on-windows-11/"><u>Addressing Non-Existent Files Message on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/a-step-by-step-for-placing-antique-games-into-photos-folder/"><u>A Step-by-Step for Placing Antique Games Into Photos Folder</u></a></li>
<li><a href="https://windows11.techidaily.com/a-visual-journey-to-custom-window-design-with-winbubbles-insights/"><u>A Visual Journey to Custom Window Design with WinBubble's Insights</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-transforming-silent-videos-to-audible-magic-on-tiktok/"><u>2024 Approved  Transforming Silent Videos to Audible Magic on TikTok</u></a></li>
<li><a href="https://windows11.techidaily.com/5-ways-to-close-multiple-apps-simultaneously-on-windows/"><u>5 Ways to Close Multiple Apps Simultaneously on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-customizable-rgb-in-windows-11-os/"><u>Activating Customizable RGB in Windows 11 OS</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-check-distance-and-radius-on-google-maps-for-your-oppo-a56s-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Check Distance and Radius on Google Maps For your Oppo A56s 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/amplify-your-pcs-wi-fi-with-8-effective-fixes-for-windows-11/"><u>Amplify Your PC's Wi-Fi with 8 Effective Fixes for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/9-ways-to-fix-blurry-screen-issues-on-windows-11/"><u>9 Ways to Fix Blurry Screen Issues on Windows 11</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-cutting-edge-ai-companions-discord-for-2024/"><u>[New] Cutting-Edge AI Companions Discord for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-crisp-visuals-leveraging-background-blur-in-w11s-photos-app/"><u>Achieve Crisp Visuals: Leveraging Background Blur in W11's Photos App</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/breakneck-broadcast-channel-your-youtube-list-for-2024/"><u>Breakneck Broadcast  Channel Your YouTube List for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-vimeo-to-gif-how-to-make-a-gif-from-vimeo-video/"><u>[New] In 2024, Vimeo to GIF  How to Make a GIF From Vimeo Video</u></a></li>
<li><a href="https://windows11.techidaily.com/7-solutions-for-enabling-windows-11s-memory-check/"><u>7 Solutions for Enabling Windows 11'S Memory Check</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-rgb-customization-in-win11/"><u>Activating RGB Customization in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-unresponsive-windows-11-login-screens/"><u>Bypassing Unresponsive Windows 11 Login Screens</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-10-upgrade-fault-code-0xc004f050/"><u>Bypassing Windows 10 Upgrade Fault: Code 0XC004F050</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-in-2024-the-ultimate-technique-for-voice-extraction-from-songs/"><u>Updated In 2024, The Ultimate Technique for Voice Extraction From Songs</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-changing-printer-behavior-on-windows/"><u>Avoiding Changing Printer Behavior on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-forbidden-page-in-windows-setup/"><u>Addressing Forbidden Page in Windows Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/briefly-explain-what-cultural-relativism-means-in-your-own-words/"><u>Briefly Explain What Cultural Relativism Means in Your Own Words.</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-things-you-need-to-know-about-pexelscom/"><u>2024 Approved Things You Need to Know About Pexels.com</u></a></li>
<li><a href="https://windows11.techidaily.com/best-practices-for-disabling-noncritical-windows-11-services/"><u>Best Practices for Disabling Noncritical Windows 11 Services</u></a></li>
<li><a href="https://windows11.techidaily.com/altering-start-page-in-windows-11-task-manager/"><u>Altering Start Page in Windows 11 Task Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/best-practices-choosing-the-right-win-video-codec/"><u>Best Practices: Choosing the Right Win Video Codec</u></a></li>
</ul></div>
