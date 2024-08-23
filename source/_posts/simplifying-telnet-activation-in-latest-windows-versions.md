---
title: Simplifying Telnet Activation in Latest Windows Versions
date: 2024-08-22T21:38:19.956Z
updated: 2024-08-23T21:38:19.956Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Simplifying Telnet Activation in Latest Windows Versions
excerpt: This Article Describes Simplifying Telnet Activation in Latest Windows Versions
keywords: Telnet Setup Simplified,Windows Telnet Enable,Easy Telnet Windows,Windows Telnet Guide,Simple Telnet Activation,Telnet WinXP+Setup,Modern Telnet Windows
thumbnail: https://thmb.techidaily.com/8f41caf7d9b5e4f9d2e8bb7de69d52df6f6bccbd4e17b1b94150ffa9569118d6.jpg
---

## Simplifying Telnet Activation in Latest Windows Versions

 Despite the vulnerability issues, Telnet is still used as a client-server protocol by Windows users. It is primarily used for initial network hardware configuration, remote access, port testing and forwarding, and other tasks that don't involve sensitive information transfer.

 You can enable Telnet on Windows 10 and 11 computers via Command Prompt or the Graphics User Interface (GUI) tool. Here we show you the many ways to enable Telnet on your Windows computer.

## 1\. Enable Telnet on Windows Using Control Panel

 You can enable Telnet Client using the Classic Control Panel. Since it is an optional feature, you can enable it using the Windows Optional Feature dialog. You can use it[add or remove other users' optional features on Windows](https://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) .

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

## 2\. Enable Telnet Client Using Windows PowerShell

![enable telnet client powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-client-powershell.jpg)

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
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Install Telnet Client Using Command Prompt

![enable telnet command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Check the Telnet Client Status on Your PC

![telnet status enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/telnet-status-enabled.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
 You can check if the Telnet client is enabled on your PC using a Command Prompt command. When enabled, the Telnet command will open a new CMD to connect to remote servers and perform other tasks.

1. Launch Command Prompt as administrator (see[how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for in-depth steps).
2. In the Command Prompt window, type**Telnet** and press**Enter** .
3. A new CMD with Microsoft Telnet will open.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-the-definitive-steps-for-online-streaming-audio-archiving/"><u>[New] In 2024, The Definitive Steps for Online Streaming Audio Archiving</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-smart-picks-top-free-online-recorder-software-for-2024/"><u>[New] Smart Picks  Top Free Online Recorder Software for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-crafting-the-perfect-soundtrack-for-your-vimeo-content/"><u>[Updated] Crafting the Perfect Soundtrack for Your Vimeo Content</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-from-basics-to-best-achieving-superior-sound-via-zoom-for-podcasting/"><u>2024 Approved  From Basics to Best  Achieving Superior Sound via Zoom for Podcasting</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-timeless-thread-triumphs-reddits-all-time-fave-list-top-10/"><u>2024 Approved  Timeless Thread Triumphs  Reddit’s All-Time Fave List (Top 10)</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/a-working-guide-for-pachirisu-pokemon-go-map-on-nokia-c02-drfone-by-drfone-virtual-android/"><u>A Working Guide For Pachirisu Pokemon Go Map On Nokia C02 | Dr.fone</u></a></li>
<li><a href="https://article-posts.techidaily.com/advanced-tips-for-maximum-digital-storage/"><u>Advanced Tips for Maximum Digital Storage</u></a></li>
<li><a href="https://tech-hub.techidaily.com/bypassing-common-auto-gpt-barriers-with-these-six-fixes/"><u>Bypassing Common Auto-GPT Barriers with These Six Fixes</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/discord-username-update-how-to-alter-profile-images/"><u>Discord Username Update: How To Alter Profile Images</u></a></li>
<li><a href="https://hardware-help.techidaily.com/effortless-installation-latest-dell-d31n-driver-software-for-your-pc/"><u>Effortless Installation: Latest Dell D31n Driver Software for Your PC</u></a></li>
<li><a href="https://extra-information.techidaily.com/engaging-conversations-with-your-youtube-audience/"><u>Engaging Conversations with Your YouTube Audience</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-windows-compatible-art-tools-alike-procreate/"><u>Essential Windows-Compatible Art Tools Alike Procreate</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-the-significance-of-versions-in-windows-updates/"><u>Exploring the Significance of Versions in Windows Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/fixes-for-recurrent-disk-filling-on-windows-pcs/"><u>Fixes for Recurrent Disk Filling on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/flipping-the-script-revisiting-timeless-pc-games/"><u>Flipping the Script: Revisiting Timeless PC Games</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-conquering-unexplained-obs-recordings-glitches/"><u>Guide to Conquering Unexplained OBS Recordings Glitches</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-rectify-file-history-fault-in-windows/"><u>Guide to Rectify “File History Fault” In Windows</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-honor-v-purse-frp-in-3-different-ways-by-drfone-android/"><u>How To Bypass Honor V Purse FRP In 3 Different Ways</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-package-could-not-be-registered-photos-error-in-windows-11-and-11/"><u>How to Fix the “Package Could Not Be Registered” Photos Error in Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-camera-apps-0xa00f429f-error-in-windows-10-and-11/"><u>How to Fix the Camera App’s 0xA00F429F Error in Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-remedy-mbs-service-disconnection-issue-on-windows-11/"><u>How to Remedy MB's Service Disconnection Issue on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-update-windows-offline-with-portable-update/"><u>How to Update Windows Offline With Portable Update</u></a></li>
<li><a href="https://windows11.techidaily.com/implementing-end-task-action-within-windows-11/"><u>Implementing End Task Action Within Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-multitasking-running-windows-11-in-macos-with-parallels/"><u>Mastering Multitasking: Running Windows 11 in MacOS with Parallels</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-network-snags-seven-strategies-to-connect-in-obs-windows/"><u>Navigating Network Snags: Seven Strategies to Connect in OBS Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/prioritize-security-on-windows-the-leading-7-free-pass-gen-apps/"><u>Prioritize Security on Windows: The Leading 7 Free Pass Gen Apps</u></a></li>
<li><a href="https://extra-hints.techidaily.com/quickest-sharp-window-photo-enhancer/"><u>Quickest Sharp Window Photo Enhancer</u></a></li>
<li><a href="https://windows11.techidaily.com/reboot-to-regain-default-navigator-setup-in-win11/"><u>Reboot to Regain Default Navigator Setup in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstating-active-conditional-filters-in-windows-mail/"><u>Reinstating Active Conditional Filters in Windows Mail</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-the-exception-has-been-reached-on-windows-devices/"><u>Resolving “The Exception Has Been Reached” On Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/resurrect-your-invisible-wi-fi-connection-on-windows-11/"><u>Resurrect Your Invisible Wi-Fi Connection on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/shielding-operations-mastering-uac-security-measures/"><u>Shielding Operations: Mastering UAC Security Measures</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-to-combat-vanished-steam-graphics/"><u>Solutions to Combat Vanished Steam Graphics</u></a></li>
<li><a href="https://windows11.techidaily.com/start-menu-no-more-unwanted-advertisements/"><u>Start Menu, No More Unwanted Advertisements!</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-address-security-glitches-in-windows-1011/"><u>Steps to Address Security Glitches in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-razer-devices-not-detected-by-synapse-on-windows/"><u>Steps to Resolve Razer Devices Not Detected by Synapse on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-stopping-windows-11s-observer-mode/"><u>Strategies for Stopping Windows 11'S Observer Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-fix-unresponsive-usb-cases-win-xpvista7810/"><u>Strategies to Fix Unresponsive USB Cases: Win XP/Vista/7/8/10</u></a></li>
<li><a href="https://windows11.techidaily.com/tackle-windows-11-woes-your-guide-to-fixing-11-issues/"><u>Tackle Windows 11 Woes - Your Guide to Fixing 11 Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-unfreezing-the-windows-update-troubleshooter/"><u>The Art of Unfreezing the Windows Update Troubleshooter</u></a></li>
<li><a href="https://windows11.techidaily.com/the-role-and-significance-of-windows-bt-folders/"><u>The Role and Significance of Windows ~BT Folders</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-embellishing-system-tray-with-a-favorite-weather-symbol-in-windows-11/"><u>The Ultimate Guide to Embellishing System Tray With a Favorite Weather Symbol in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-windows-11-explorer-guide-pinpointing-your-machines-mac/"><u>The Windows 11 Explorer Guide: Pinpointing Your Machine's MAC</u></a></li>
<li><a href="https://windows11.techidaily.com/triumph-over-trapped-troubleshooting-of-windows-update/"><u>Triumph Over Trapped Troubleshooting of Windows Update</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-solutions-to-side-by-side-error-on-win10/"><u>Unveiling Solutions to Side-by-Side Error on Win10</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unveiling-the-full-potential-of-tablet-mode-in-windows-11-for-enhanced-productivity/"><u>Unveiling the Full Potential of Tablet Mode in Windows 11 for Enhanced Productivity</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-11s-auto-hdr-capabilities/"><u>Unveiling Windows 11'S Auto HDR Capabilities</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/updated-in-2024-how-to-make-a-flv-photo-slideshow-with-music/"><u>Updated In 2024, How to Make a FLV Photo Slideshow with Music</u></a></li>
<li><a href="https://windows11.techidaily.com/voice-recorder-efficiency-essential-keyboard-shortcuts-in-windows-11/"><u>Voice Recorder Efficiency: Essential Keyboard Shortcuts in Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-are-location-permissions-life360-on-itel-p55plus-drfone-by-drfone-virtual-android/"><u>What are Location Permissions Life360 On Itel P55+? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/whats-new-for-windows-11-excitement-from-moment-update-22h2/"><u>What's New for Windows 11? Excitement From Moment Update #22H2</u></a></li>
<li><a href="https://windows11.techidaily.com/window-menus-hidden-potential-in-windows-1011/"><u>Window Menus' Hidden Potential in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-tickout-restoring-clock-consistency/"><u>Windows Tickout: Restoring Clock Consistency</u></a></li>
</ul></div>
