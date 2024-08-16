---
title: "Race the Rate: Unveiling Windows Techniques for Measuring Ethernet Speed"
date: 2024-08-15T16:20:07.370Z
updated: 2024-08-16T16:20:07.370Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Race the Rate: Unveiling Windows Techniques for Measuring Ethernet Speed"
excerpt: "This Article Describes Race the Rate: Unveiling Windows Techniques for Measuring Ethernet Speed"
keywords: Ethernet Speed Test,Wi-Fi Speed Comparison,Ping Time Analysis,Network Latency Check,Data Throughput Rate,Bandwidth Measurement,Fiber Optic Speed
thumbnail: https://thmb.techidaily.com/efe03172267db8e41dde950b174798601940a22588399da557fc77a3f3ce0d36.jpeg
---

## Race the Rate: Unveiling Windows Techniques for Measuring Ethernet Speed

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
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. How to Check the Network Adapter Connection Speed Using Control Panel

 Although Microsoft is gradually moving a large number of features to the Settings app, many people still prefer to use the Control Panel to modify settings and troubleshoot issues. If you are one of them, here's how you can check the network adapter connection speed via Control Panel.

1. Press**Win + R** to open the Run dialog (see[how to open Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways).
2. Type**control** in the box and press**Enter** .
3. In the Control Panel window that opens, use the drop-down menu in the top right corner to change the view type to**Small icons** or**Large icons** .
4. Go to**Network and Sharing Center** .
5. Click the**Change adapter settings** link from the left pane.
6. Double-click on your Ethernet or Wi-Fi adapter to open its properties.
7. Check the connection speed of your network adapter in the**Speed** field.  
![Check Network Adapter Speed Using Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/check-network-adapter-speed-using-control-panel.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->

 Seeing too many network adapter entries on your Windows computer? Learn[how to get rid of old or inactive network adapters from Windows](https://www.makeuseof.com/how-to-remove-network-adapter-windows/) in a few easy steps.

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. How to Check Network Adapter Connection Speed via Command Prompt

 Not a fan of GUI? No problem. You can also use a command-line utility like Command Prompt to check the network adapter connection speed on Windows. Here are the steps for the same.

1. Right-click on the Start icon or use the**Win + X** shortcut to open the[Power User menu](https://www.makeuseof.com/windows-power-menu-guide/) .
2. Select**Terminal** from the list.
3. In the console, paste the following command and press**Enter** .  
`netsh wlan show interfaces`
4. Check the values next to**Receive rate** and**Transmit rate** to determine the speed of your network adapter.  
![Check Network Adapter Speed Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/check-network-adapter-speed-using-command-prompt.jpg)

 Like using Command Prompt? Check our guide on[how to master Command Prompt on Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
## 4\. How to Check Network Adapter Connection Speed via PowerShell

 PowerShell is yet another command-line tool you can use to interact with Windows. Although PowerShell is primarily used to automate tasks and troubleshoot errors, you can also use it to find system information such as the network adapter speed.

To check network adapter connection speed via PowerShell:

1. Press**Win + S** to open the search menu.
2. Type**Windows PowerShell** in the search box and press**Enter** .
3. Paste the following command in the console and press**Enter** .  
`Get-NetAdapter | select interfaceDescription, name, status, linkSpeed`  
![Check Network Adapter Speed Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/check-network-adapter-speed-using-powershell.jpg)
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->

 Once you run the above command, PowerShell will display a list of all the Ethernet and Wi-Fi adapters on your Windows computer, along with their link speeds.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
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
<li><a href="https://screen-sharing-recording.techidaily.com/new-obs-streamers-toolkit-for-captivating-sessions/"><u>[New] OBS Streamer’s Toolkit for Captivating Sessions</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-creating-an-iphone-photo-mosaic-a-step-by-step-guide/"><u>[Updated] Creating an iPhone Photo Mosaic  A Step-by-Step Guide</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-everyday-online-chronicles-a-handy-tip-for-digging-up-fbs-vids-for-2024/"><u>[Updated] Everyday Online Chronicles  A Handy Tip for Digging Up FB's Vids for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-proven-strategies-for-creating-superb-igtv-videos-on-smartphonesdlsrs/"><u>[Updated] In 2024, Proven Strategies for Creating Superb IGTV Videos on Smartphones/DLSRs</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-instagram-to-music-directing-videos-to-mp3-outputs/"><u>[Updated] Instagram to Music  Directing Videos to MP3 Outputs</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-premiere-video-editing-options-for-app-developers/"><u>[Updated] Premiere Video Editing Options for App Developers</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-top-10-memes-blending-hilarity-and-emotional-depth-on-insta-for-2024/"><u>[Updated] Top 10 Memes Blending Hilarity and Emotional Depth on Insta for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/2-ways-to-monitor-samsung-galaxy-a23-5g-activity-drfone-by-drfone-virtual-android/"><u>2 Ways to Monitor Samsung Galaxy A23 5G Activity | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-top-10-histology-streams-for-academics/"><u>2024 Approved  Top 10 Histology Streams for Academics</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-ultimate-7-secure-video-conferencing-systems-for-smbs/"><u>2024 Approved  Ultimate 7 Secure Video Conferencing Systems for SMBs</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/3-ways-for-android-pokemon-go-spoofing-on-tecno-pop-7-pro-drfone-by-drfone-virtual-android/"><u>3 Ways for Android Pokemon Go Spoofing On Tecno Pop 7 Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-print-service-stopped-issue-on-windows-pc/"><u>Addressing Print Service Stopped Issue on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/applications-and-their-unique-run-notations-explored/"><u>Applications & Their Unique Run Notations Explored</u></a></li>
<li><a href="https://windows11.techidaily.com/boot-up-solutions-navigating-4-pct-routes/"><u>Boot-Up Solutions: Navigating 4 PCT Routes</u></a></li>
<li><a href="https://facebook.techidaily.com/building-memorable-facebook-events-from-scratch/"><u>Building Memorable Facebook Events From Scratch</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-package-registration-errors-a-guide-to-photography-on-windows-11/"><u>Correcting Package Registration Errors: A Guide to Photography on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-edge-methods-to-convert-word-documents-to-pdf-on-windows-11/"><u>Cutting-Edge Methods to Convert Word Documents to PDF on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-for-fixing-pubg-saving-issues-win/"><u>Expert Tips for Fixing PUBG Saving Issues (Win)</u></a></li>
<li><a href="https://windows11.techidaily.com/explore-the-best-techniques-to-streamline-your-windows-folder-system/"><u>Explore the Best Techniques to Streamline Your Windows Folder System</u></a></li>
<li><a href="https://windows11.techidaily.com/finding-out-your-internets-public-ip-with-win-cli/"><u>Finding Out Your Internet's Public IP with Win CLI</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-perfecting-images-slideshow-and-fix-in-windows-11-photos-app/"><u>Guide to Perfecting Images: Slideshow & Fix in Windows 11 Photos App</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-reinstalling-favorite-apps-on-new-windows-11-devices/"><u>Guide to Reinstalling Favorite Apps on New Windows 11 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-reinstating-original-size-for-win-11-icons/"><u>Guide to Reinstating Original Size for Win 11 Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-correct-non-empty-directory-error-code-0x80070091-in-win11/"><u>How to Correct Non-Empty Directory Error (Code: 0X80070091) in Win11</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-unresponsive-touch-screen-on-xiaomi-redmi-k70-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Touch Screen on Xiaomi Redmi K70 Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-actions-for-non-displayed-windows-sign-ins/"><u>Immediate Actions for Non-Displayed Windows Sign-Ins</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-5-quick-methods-to-bypass-xiaomi-redmi-note-12-pro-4g-frp-by-drfone-android/"><u>In 2024, 5 Quick Methods to Bypass Xiaomi Redmi Note 12 Pro 4G FRP</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-cracked-the-full-screen-hurdle-in-obs/"><u>In 2024, Cracked  The Full Screen Hurdle in OBS</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-can-i-use-a-fake-gps-without-mock-location-on-tecno-spark-go-2023-drfone-by-drfone-virtual-android/"><u>In 2024, How Can I Use a Fake GPS Without Mock Location On Tecno Spark Go (2023)? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/infuse-personalized-style-in-windows-email-calendar/"><u>Infuse Personalized Style in Windows Email, Calendar</u></a></li>
<li><a href="https://windows11.techidaily.com/inspect-font-characters-windows-11-route/"><u>Inspect Font Characters: Windows 11 Route</u></a></li>
<li><a href="https://windows11.techidaily.com/integrating-your-android-into-windows-11-webstreaming/"><u>Integrating Your Android Into Windows 11 Webstreaming</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-past-share-permission-hurdles-in-win-os/"><u>Navigate Past Share Permission Hurdles in Win OS</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-rpc-failure-essential-steps-for-win-users/"><u>Overcoming RPC Failure: Essential Steps for Win Users</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-stability-issues-with-vscode-on-w11/"><u>Preventing Stability Issues with VSCode on W11</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-for-no-sound-during-system-tests/"><u>Remedy for No Sound During System Tests</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-a-muted-windows-taskbar/"><u>Remedying a Muted Windows Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/revealing-windows-11s-disguised-taskbar-investigation-tool/"><u>Revealing Windows 11'S Disguised Taskbar Investigation Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/revitalizing-vintage-directx-apps-using-modernized-dxvk-features/"><u>Revitalizing Vintage DirectX Apps Using Modernized DXVK Features</u></a></li>
<li><a href="https://windows11.techidaily.com/sharpening-performance-with-optimized-news-and-video-consumption/"><u>Sharpening Performance with Optimized News & Video Consumption</u></a></li>
<li><a href="https://windows11.techidaily.com/simplify-workflows-automate-using-to-dot-plus-ifttt/"><u>Simplify Workflows: Automate Using To-Dot + IFTTT</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-the-process-anydesk-fixes-for-windows-users/"><u>Simplifying the Process: AnyDesk Fixes for Windows Users</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/travel-gears-new-power-bank-unicharger-pro-review-a-game-changer-in-travel-batteries/"><u>Travel Gear’s New Power Bank: UniCharger Pro Review - A Game Changer in Travel Batteries</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-unverified-adobe-in-windows/"><u>Troubleshooting Unverified Adobe in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/tweaking-netconfigs-windows-11-edition/"><u>Tweaking NetConfigs: Windows 11 Edition</u></a></li>
</ul></div>
