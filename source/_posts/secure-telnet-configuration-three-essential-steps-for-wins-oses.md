---
title: "Secure Telnet Configuration: Three Essential Steps for Wins OSes"
date: 2024-08-15T15:30:19.282Z
updated: 2024-08-16T15:30:19.282Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Secure Telnet Configuration: Three Essential Steps for Wins OSes"
excerpt: "This Article Describes Secure Telnet Configuration: Three Essential Steps for Wins OSes"
keywords: Secure Telnet Setup,Windows Telnet Security,Telnet Configurations,WinOS Telnet Safety,Essential Telnet Steps,OS Telnet Protection,Telnet Security Guide
thumbnail: https://thmb.techidaily.com/b0ea6d61080761dc873cfd8c694bea1246e45e087ea28aa28a47640ed6e89f83.jpg
---

## Secure Telnet Configuration: Three Essential Steps for Wins OSes

 Despite the vulnerability issues, Telnet is still used as a client-server protocol by Windows users. It is primarily used for initial network hardware configuration, remote access, port testing and forwarding, and other tasks that don't involve sensitive information transfer.

 You can enable Telnet on Windows 10 and 11 computers via Command Prompt or the Graphics User Interface (GUI) tool. Here we show you the many ways to enable Telnet on your Windows computer.

## 1\. Enable Telnet on Windows Using Control Panel

 You can enable Telnet Client using the Classic Control Panel. Since it is an optional feature, you can enable it using the Windows Optional Feature dialog. You can use it [add or remove other users' optional features on Windows](https://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) .

To enable Telnet Client using Control Panel:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel.**
3. In Control Panel, Click on**Uninstall a Program** under**Programs and Features.**  
![turn windows features on or off control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/turn-windows-features-on-or-off-control-panel.jpg)
4. In the left pane, click on the**Turn Windows feature on or off.**  
![enable telnet client windows features dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-client-windows-features-dialog.jpg)
5. In the Windows Features dialog, scroll down and select**Telnet Client.**
6. Click**OK** and wait for the feature to install. Once installed, restart your PC to apply the changes and enable the feature.

If you need to disable Telnet:

1. Open the**Windows Features** dialog and unselect**Telnet Client.**
2. Click**OK** and wait for the feature to uninstall.
3. Click on**Restart** now to reboot your PC and apply the changes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3727260&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. Enable Telnet Client Using Windows PowerShell

![enable telnet client powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-client-powershell.jpg)
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can use the Enable-WindowsOptionalFeature cmdlet to enable Telnet Client using Windows PowerShell. Useful if you are unable to turn on the feature using the Windows Features dialog and it is also faster than the GUI method.

To enable Telnet using Windows PowerShell:

1. Press**Win + X** to open the**WinX** menu.
2. Click on**Windows Terminal(Admin)** and click**Yes** to open the terminal app as administrator. If you are using Windows 10, type**PowerShell** in**Windows Search** and open**Windows PowerShell** administrator.
3. In the PowerShell window, type the following command and press**Enter** to enable Telnet:  
`Enable-WindowsOptionalFeature -Online -FeatureName TelnetClient`
4. This process may take several minutes, so wait for it to complete and return a status report. If successful, you’ll see the result as**Online:True.**
5. If you want to disable Telnet Client, use the following command instead:  
`Disable-WindowsOptionalFeature -Online -FeatureName TelnetClient`
6. Close PowerShell and restart your PC.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
## 3\. Install Telnet Client Using Command Prompt

![enable telnet command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851655&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->

 If you prefer Command Prompt over PowerShell, you can use the DISM /Online command to enable the optional features on your Windows 11 computer.

Follow these steps to install Telnet using Command Prompt:

1. Press the**Win** key and type**cmd** .
2. Right-click on**Command Prompt** and select**Run as administrator.**
3. In the Command Prompt window, type the following command and press**Enter** :  
`dism /online /Enable-Feature /FeatureName:TelnetClient`
4. Command Prompt will start enabling the feature and display the operation completed successfully message.
5. If you need to disable Telnet, type the following command and press**Enter** :  
`dism /Online /Disable-Feature /FeatureName:TelnetClient`
6. Wait for the success message.
7. Type**exit** and press**Enter** to close Command Prompt.

## How to Check the Telnet Client Status on Your PC

![telnet status enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/telnet-status-enabled.jpg)
<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->

 You can check if the Telnet client is enabled on your PC using a Command Prompt command. When enabled, the Telnet command will open a new CMD to connect to remote servers and perform other tasks.

1. Launch Command Prompt as administrator (see [how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for in-depth steps).
2. In the Command Prompt window, type**Telnet** and press**Enter** .
3. A new CMD with Microsoft Telnet will open.

<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## All the Ways to Enable Telnet On Your Windows 11 Computer

 Telnet is a built-in remote access utility that you can use to troubleshoot firewall and network issues. While it is still part of Windows, system administrators now prefer the more secure SSH protocol to access computers over an unsecured network.

 The major disadvantage of Telnet is that it is not secure and prone to a man-in-the-middle attack. If not for particular situations, switch to a more secure network protocol such as SSH and Mosh with better password and public key authentication.


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
<li><a href="https://facebook-video-share.techidaily.com/new-decision-making-in-the-workplace-a-neurological-approach-to-efficacy-and-ethics-for-2024/"><u>[New] Decision-Making in the Workplace  A Neurological Approach to Efficacy and Ethics for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-breaking-into-the-digital-realm-the-wirecast-approach-for-youtube-streamers/"><u>[New] In 2024, Breaking Into the Digital Realm  The WireCast Approach for YouTube Streamers</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-maximizing-impact-strategies-for-going-viral-on-instagram/"><u>[New] In 2024, Maximizing Impact  Strategies for Going Viral on Instagram</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-photo-perfection-on-iphones-and-androids-blurring-basics-for-2024/"><u>[New] Photo Perfection on iPhones & Androids  Blurring Basics for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-in-2024-download-free-sound-effects-for-youtubers/"><u>[Updated] In 2024, Download Free Sound Effects for YouTubers</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-in-2024-innovative-approaches-to-recording-verbal-notes/"><u>[Updated] In 2024, Innovative Approaches to Recording Verbal Notes</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-the-finishing-touch-journalisms-close-call-for-2024/"><u>[Updated] The Finishing Touch  Journalism's Close Call for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-laying-the-groundwork-for-successful-channels/"><u>2024 Approved  Laying The Groundwork For Successful Channels</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-essential-iphone-hdr-photography-skills/"><u>2024 Approved  The Essential iPhone HDR Photography Skills</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-fake-gps-without-root-on-apple-iphone-se-2020-drfone-by-drfone-virtual-ios/"><u>3 Ways to Fake GPS Without Root On Apple iPhone SE (2020) | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/bluetooth-enabling-for-lenovo-on-win11-platform/"><u>Bluetooth Enabling for Lenovo on Win11 Platform</u></a></li>
<li><a href="https://fox-access.techidaily.com/capture-and-preserve-a-detailed-look-at-7-ways-to-log-webcasts/"><u>Capture and Preserve  A Detailed Look at 7 Ways to Log Webcasts</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/discovering-artistic-expression-top-film-tips-on-youtube-for-2024/"><u>Discovering Artistic Expression  Top Film Tips on YouTube for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/dodgy-deals-understanding-the-threats-of-low-price-windows-licenses/"><u>Dodgy Deals: Understanding the Threats of Low-Price Windows Licenses</u></a></li>
<li><a href="https://windows11.techidaily.com/drive-success-top-5-windows-productivity-hacks-you-cant-miss/"><u>Drive Success: Top 5 Windows Productivity Hacks You Can't Miss</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-command-line-master-20-key-cmd-commands/"><u>Efficient Command Line: Master 20 Key CMD Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-windows-partition-integration-strategies/"><u>Efficient Windows Partition Integration Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-managing-your-c-drive-usage-on-windows/"><u>Efficiently Managing Your C: Drive Usage on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-resolving-windows-audio-glitches-error-code-9999/"><u>Efficiently Resolving Windows Audio Glitches: Error Code 9999</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-windows-method-to-determine-ram-specifications/"><u>Effortless Windows Method to Determine RAM Specifications</u></a></li>
<li><a href="https://windows11.techidaily.com/effortlessly-create-win-11-boot-drive-using-these-3-methods/"><u>Effortlessly Create Win 11 Boot Drive Using These 3 Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-internet-safety-in-windows-11-trusted-site-listing/"><u>Elevate Internet Safety in Windows 11: Trusted Site Listing</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-usability-and-style-for-windows-1011-in-8-ways/"><u>Elevate Usability and Style for Windows 10/11 in 8 Ways</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-audio-experience-with-windows-11-settings/"><u>Elevate Your Audio Experience with Windows 11 Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-game-amplifying-graphics-power-in-windows-1011/"><u>Elevate Your Game: Amplifying Graphics Power in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-workflow-master-the-taskbar-in-win-11/"><u>Elevate Your Workflow: Master the Taskbar in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-device-safety-with-custom-lock-patterns-in-windows-11/"><u>Elevating Device Safety with Custom Lock Patterns in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminate-no-errors-comprehensible-guide-to-fixing-win11-issues/"><u>Eliminate No Errors: Comprehensible Guide to Fixing Win11 Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminate-old-wallpaper-3-efficient-methods/"><u>Eliminate Old Wallpaper: 3 Efficient Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-we-encountered-an-error-oculus-w11w10-guide/"><u>Eliminating We Encountered an Error: Oculus W11/W10 Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/embarking-on-a-journey-with-ai-copilot-in-windows-11/"><u>Embarking on a Journey with AI Copilot in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/emergency-printer-deletion-in-windows-os-a-step-by-step-approach/"><u>Emergency Printer Deletion in Windows OS: A Step-by-Step Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/empowering-windows-11-android-phone-webcam-utilization/"><u>Empowering Windows 11: Android Phone Webcam Utilization</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-windows-security-today-the-best-7-free-password-creator-apps/"><u>Enhance Windows Security Today: The Best 7 Free Password Creator Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-wordsmithing-effortlessly-with-top-apps-windows/"><u>Enhance Wordsmithing Effortlessly With Top Apps (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-qbittorrent-performance-after-a-halt/"><u>Enhancing qBittorrent Performance After a Halt</u></a></li>
<li><a href="https://windows11.techidaily.com/enriching-macos-with-windows-powered-innovations/"><u>Enriching macOS with Windows-Powered Innovations</u></a></li>
<li><a href="https://windows11.techidaily.com/enriching-windows-taskmanager-with-cli-tab-feature/"><u>Enriching Windows TaskManager with CLI Tab Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-high-visibility-of-taskmanager/"><u>Ensuring High Visibility of TaskManager</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicate-black-screen-on-win11-top-easy-fixes/"><u>Eradicate Black Screen on Win11: Top Easy Fixes!</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicating-glitch-windows-edition-geforce-x0001/"><u>Eradicating Glitch: Windows Edition, GeForce X0001</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-3d-paint-keyboard-tricks/"><u>Essential 3D Paint Keyboard Tricks</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-3-effective-methods-to-fake-gps-location-on-android-for-your-poco-m6-pro-4g-drfone-by-drfone-virtual/"><u>In 2024, 3 Effective Methods to Fake GPS location on Android For your Poco M6 Pro 4G | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-3-things-you-must-know-about-fake-snapchat-location-on-asus-rog-phone-8-pro-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Things You Must Know about Fake Snapchat Location On Asus ROG Phone 8 Pro | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-a-compilation-of-must-play-virtual-realms/"><u>In 2024, A Compilation of Must-Play Virtual Realms</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-android-unlock-code-sim-unlock-your-xiaomi-redmi-k70e-phone-and-remove-locked-screen-by-drfone-android/"><u>In 2024, Android Unlock Code Sim Unlock Your Xiaomi Redmi K70E Phone and Remove Locked Screen</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-facebook-dating-for-your-apple-iphone-xs-max-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Change Location On Facebook Dating for your Apple iPhone XS Max | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-pro-tips-navigating-without-watching-edgenuity-content/"><u>In 2024, Pro Tips  Navigating Without Watching Edgenuity Content</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/professional-tips-for-using-luts-in-adobe-after-effects-for-2024/"><u>Professional Tips for Using LUTs in Adobe After Effects for 2024</u></a></li>
<li><a href="https://buynow-help.techidaily.com/sealoc-coastal-silver-55-inch-4k-outdoor-tv-review-a-slim-and-sleek-tv-for-outdoors/"><u>Sealoc Coastal Silver 55-Inch 4K Outdoor TV Review: A Slim & Sleek TV for Outdoors</u></a></li>
<li><a href="https://common-error.techidaily.com/speed-and-precision-master-windows-scrolls/"><u>Speed and Precision: Master Windows Scrolls</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/top-rated-m-mooc-1000a-portable-car-jump-starter-with-18000-mah-battery-comprehensive-review/"><u>Top-Rated M MOOC 1000A Portable Car Jump Starter with 18,000 mAh Battery - Comprehensive Review</u></a></li>
<li><a href="https://extra-hints.techidaily.com/ultimate-guide-80s-vhs-tricks-for-dynamic-edits/"><u>Ultimate Guide  80'S VHS Tricks for Dynamic Edits</u></a></li>
</ul></div>
