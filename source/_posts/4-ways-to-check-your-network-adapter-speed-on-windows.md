---
title: 4 Ways to Check Your Network Adapter Speed on Windows
date: 2024-08-15T15:19:24.113Z
updated: 2024-08-16T15:19:24.113Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 4 Ways to Check Your Network Adapter Speed on Windows
excerpt: This Article Describes 4 Ways to Check Your Network Adapter Speed on Windows
keywords: Win Adapter Speed Test,Network Speeds Checker,PC Speed Limit,Fast Connection Check,Optimize Net Speed,Adapter Performance,Windows Net Speed Diagnosis
thumbnail: https://thmb.techidaily.com/5c068034f0080166994d164493cb808318b6f6a0f4d45de0f56404a9b7904a53.jpg
---

## 4 Ways to Check Your Network Adapter Speed on Windows

 The network adapter is a critical piece of hardware that connects your Windows computer to the internet via a wired or wireless connection. In order to achieve the maximum speeds offered by your Internet Service Provider, it is important to know what network speed your card is capable of.

 Whether you want to upgrade your internet plan or diagnose your network for performance issues, there are several ways to determine the network adapter speed on Windows. Let’s go over all of them one by one.

## 1\. How to Check the Network Adapter Connection Speed Using the Settings App

 The quickest way to check the connection speed for a Wi-Fi or Ethernet adapter is through the Windows Settings app. Aside from network speed, the Settings app also provides important information like network band, local IP address, MAC address, and more.

To check the network adapter speed via the Settings app:

1. Press**Win + I** to open the Settings app.
2. Select**Network & internet** from the left sidebar.
3. Click on**Properties** at the top.
4. Scroll down to the**Link speed (Receive/Transmit)** field to check the connection speed.  
![Check Network Adapter Speed Using the Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/check-network-adapter-speed-using-the-windows-settings-app.jpg)

<!-- affiliate ads begin -->
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. How to Check the Network Adapter Connection Speed Using Control Panel

 Although Microsoft is gradually moving a large number of features to the Settings app, many people still prefer to use the Control Panel to modify settings and troubleshoot issues. If you are one of them, here's how you can check the network adapter connection speed via Control Panel.

1. Press**Win + R** to open the Run dialog (see [how to open Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways).
2. Type**control** in the box and press**Enter** .
3. In the Control Panel window that opens, use the drop-down menu in the top right corner to change the view type to**Small icons** or**Large icons** .
4. Go to**Network and Sharing Center** .
5. Click the**Change adapter settings** link from the left pane.
6. Double-click on your Ethernet or Wi-Fi adapter to open its properties.
7. Check the connection speed of your network adapter in the**Speed** field.  
![Check Network Adapter Speed Using Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/check-network-adapter-speed-using-control-panel.jpg)
<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->

 Seeing too many network adapter entries on your Windows computer? Learn [how to get rid of old or inactive network adapters from Windows](https://www.makeuseof.com/how-to-remove-network-adapter-windows/) in a few easy steps.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. How to Check Network Adapter Connection Speed via Command Prompt

 Not a fan of GUI? No problem. You can also use a command-line utility like Command Prompt to check the network adapter connection speed on Windows. Here are the steps for the same.

1. Right-click on the Start icon or use the**Win + X** shortcut to open the [Power User menu](https://www.makeuseof.com/windows-power-menu-guide/) .
2. Select**Terminal** from the list.
3. In the console, paste the following command and press**Enter** .  
`netsh wlan show interfaces`
4. Check the values next to**Receive rate** and**Transmit rate** to determine the speed of your network adapter.  
![Check Network Adapter Speed Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/check-network-adapter-speed-using-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->

 Like using Command Prompt? Check our guide on [how to master Command Prompt on Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) .

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. How to Check Network Adapter Connection Speed via PowerShell

 PowerShell is yet another command-line tool you can use to interact with Windows. Although PowerShell is primarily used to automate tasks and troubleshoot errors, you can also use it to find system information such as the network adapter speed.

To check network adapter connection speed via PowerShell:

1. Press**Win + S** to open the search menu.
2. Type**Windows PowerShell** in the search box and press**Enter** .
3. Paste the following command in the console and press**Enter** .  
`Get-NetAdapter | select interfaceDescription, name, status, linkSpeed`  
![Check Network Adapter Speed Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/check-network-adapter-speed-using-powershell.jpg)

 Once you run the above command, PowerShell will display a list of all the Ethernet and Wi-Fi adapters on your Windows computer, along with their link speeds.

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
## Checking Network Adapter Connection Speed on Windows

 As we just learned, determining the network adapter connection speed on Windows is relatively simple. Do you know what else is easy? Speeding up the internet connection speed on your Windows computer.


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
<li><a href="https://youtube-zero.techidaily.com/024-approved-start-with-strategy-launching-an-online-dominant-gaming-channel/"><u>[New] 2024 Approved  Start with Strategy  Launching an Online Dominant Gaming Channel</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-unleashing-power-plays-exclusive-insights-into-best-7-total-war-battles/"><u>[New] 2024 Approved  Unleashing Power Plays  Exclusive Insights Into Best 7 Total War Battles</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-hustle-smart-listen-hard-top-tasks-for-podcast-enthusiasts/"><u>[New] Hustle Smart, Listen Hard  Top Tasks for Podcast Enthusiasts</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-climb-the-popularity-ladder-essential-youtube-seo-practices-uncovered/"><u>[New] In 2024, Climb the Popularity Ladder  Essential YouTube SEO Practices Uncovered</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-macbook-cam-tutorial-for-smooth-video-capture-for-2024/"><u>[New] MacBook Cam Tutorial for Smooth Video Capture for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-precision-leaders-best-7-shooting-adventures-for-2024/"><u>[New] Precision Leaders  Best 7 Shooting Adventures for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-how-to-speed-up-windows-file-inspection/"><u>[Updated] How To Speed Up Windows File Inspection</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-instant-screen-capture-pro-chrome/"><u>[Updated] In 2024, Instant Screen Capture Pro (Chrome)</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-making-impeccable-square-videos-in-imovie-for-instagram/"><u>[Updated] In 2024, Making Impeccable Square Videos in iMovie for Instagram</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-step-by-step-guide-to-painless-iphone-screen-sharing/"><u>[Updated] In 2024, Step-by-Step Guide to Painless iPhone Screen Sharing</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-optimizing-audio-and-visuals-in-mobile-broadcasting-via-obs-for-2024/"><u>[Updated] Optimizing Audio & Visuals in Mobile Broadcasting via OBS for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-top-tips-for-creating-instagrammable-unboxing-highlights/"><u>[Updated] Top Tips for Creating Instagrammable Unboxing Highlights</u></a></li>
<li><a href="https://windows11.techidaily.com/11-fixes-if-windows-10-cant-detect-a-wi-fi-network/"><u>11 Fixes if Windows 10 Can’t Detect a Wi-Fi Network</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-basic-techniques-for-effective-color-grading-in-ps/"><u>2024 Approved  Basic Techniques for Effective Color Grading in PS</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-image-innovation-at-its-peak-8-leaders-in-photogridding/"><u>2024 Approved  Image Innovation at Its Peak  8 Leaders in Photogridding</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-the-art-of-playback-anarchy-youtube-playlists-unordered-again/"><u>2024 Approved  The Art of Playback Anarchy  YouTube Playlists Unordered Again</u></a></li>
<li><a href="https://windows11.techidaily.com/3-ways-to-check-if-windows-11-is-activated/"><u>3 Ways to Check If Windows 11 Is Activated</u></a></li>
<li><a href="https://windows11.techidaily.com/4-ways-to-check-the-hardware-ids-of-your-devices-on-windows/"><u>4 Ways to Check the Hardware IDs of Your Devices on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/7-reasons-to-choose-windows-10-over-windows-11/"><u>7 Reasons to Choose Windows 10 Over Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensive-overview-using-bluescreenview/"><u>A Comprehensive Overview: Using BlueScreenView</u></a></li>
<li><a href="https://windows11.techidaily.com/a-guide-to-overhauling-the-settings-app-in-win11/"><u>A Guide to Overhauling the Settings App in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/a-step-by-step-approach-for-cleaning-up-ms-audit-records/"><u>A Step-by-Step Approach for Cleaning Up MS Audit Records</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerating-windows-11-app-launches/"><u>Accelerating Windows 11 App Launches</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-telnet-on-windows-3-key-methods/"><u>Activating Telnet on Windows: 3 Key Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-non-operational-state-of-ccleaner-on-win1011-systems/"><u>Addressing Non-Operational State of CCleaner on Win10/11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-unavailable-display-settings-in-nvidia-software/"><u>Addressing Unavailable Display Settings in Nvidia Software</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-services-that-dont-launch/"><u>Addressing Windows Services That Don't Launch</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-tips-for-adding-sound-in-snipping-tool-recordings-max-156/"><u>Advanced Tips for Adding Sound in Snipping Tool Recordings (Max 156)</u></a></li>
<li><a href="https://windows11.techidaily.com/alter-ip-settings-with-confidence-windows-11/"><u>Alter IP Settings with Confidence (Windows 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/analyzing-space-efficiency-of-windows-software/"><u>Analyzing Space Efficiency of Windows Software</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-decreased-size-of-your-windows-11-icons/"><u>Avoid Decreased Size of Your Windows 11 Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/beneath-the-surface-innocent-looking-apps-steal-speed-from-pcs/"><u>Beneath the Surface, Innocent-Looking Apps Steal Speed From PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/bootstrapping-your-windows-version-patch-edition/"><u>Bootstrapping Your Windows Version: Patch Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/breached-byte-bastion-maintain-reflect-then-switch/"><u>Breached Byte Bastion: Maintain, Reflect, Then Switch</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-the-workflow-of-windows-11s-recovery-features/"><u>Breaking Down the Workflow of Windows 11'S Recovery Features</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-back-sound-on-systems-running-low-volume-errors/"><u>Bring Back Sound on Systems Running Low Volume Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-the-blockade-fixing-obs-studios-server-error-window/"><u>Bypassing the Blockade: Fixing OBS Studio's Server Error Window</u></a></li>
<li><a href="https://windows11.techidaily.com/circumventing-unyielding-power-switches-on-windows-11/"><u>Circumventing Unyielding Power Switches on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-the-obscure-fixing-white-out-screens-in-win1011/"><u>Clearing the Obscure: Fixing White Out Screens in WIN10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-steam-cloud-errors/"><u>Clearing Up Steam Cloud Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/concealing-windows-11s-taskbar-search-function/"><u>Concealing Windows 11'S Taskbar Search Function</u></a></li>
<li><a href="https://windows11.techidaily.com/create-your-own-windows-speech-recognition-app-with-autohotkey-and-whisper/"><u>Create Your Own Window's Speech Recognition App with AutoHotkey and Whisper</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-home-screen-preferences-on-w11-os/"><u>Customizing Home Screen Preferences on W11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/cut-costs-not-compromise-top-5-free-media-software/"><u>Cut Costs, Not Compromise: Top 5 Free Media Software</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-edge-windows-11-shortcut-personalization-techniques/"><u>Cutting-Edge Windows 11 Shortcut Personalization Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/design-dilemma-overcoming-unexpected-screen-shades/"><u>Design Dilemma: Overcoming Unexpected Screen Shades</u></a></li>
<li><a href="https://games-able.techidaily.com/design-precision-for-performance-in-games/"><u>Design Precision for Performance in Games</u></a></li>
<li><a href="https://windows11.techidaily.com/detailed-steps-to-fully-remove-wsl/"><u>Detailed Steps to Fully Remove WSL</u></a></li>
<li><a href="https://windows11.techidaily.com/ditch-default-home-port-on-w11-settings-interface/"><u>Ditch Default Home Port on W11 Settings Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/diving-deep-using-the-netstat-command-in-windows-11-os/"><u>Diving Deep: Using the Netstat Command in Windows 11 OS</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-cast-tecno-pova-5-pro-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>How to Cast Tecno Pova 5 Pro to Computer for iPhone and Android? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-7-to-other-iphone-12-pro-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 7 To Other iPhone 12 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/how-to-use-zoom-in-your-daily-gmail-routine-for-2024/"><u>How to Use Zoom in Your Daily Gmail Routine for 2024</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-do-you-get-sun-stone-evolutions-in-pokemon-for-realme-10t-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How Do You Get Sun Stone Evolutions in Pokémon For Realme 10T 5G? | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-tiktok-versus-youtube-shorts-assessing-personal-usage-value/"><u>In 2024, TikTok versus YouTube Shorts  Assessing Personal Usage Value</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-which-recording-tool-excels-more-bandicam-vs-camtasia/"><u>In 2024, Which Recording Tool Excels More? - Bandicam Vs. Camtasia</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/revel-in-these-14-enthralling-text-based-movements-for-2024/"><u>Revel in These 14 Enthralling Text-Based Movements for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/1719270325227-seeking-help-navigate-through-windows-troubles-easily/"><u>Seeking Help? Navigate Through Windows Troubles Easily</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-oppo-reno-11f-5g-drfone-by-drfone-virtual-android/"><u>The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Oppo Reno 11F 5G | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-music-from-itel-a60s-by-fonelab-android-recover-music/"><u>The way to get back lost music from Itel A60s</u></a></li>
</ul></div>
