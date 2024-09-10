---
title: Telnet Access in Windows 11 Made Simple
date: 2024-09-09T11:58:20.491Z
updated: 2024-09-10T11:58:20.491Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Telnet Access in Windows 11 Made Simple
excerpt: This Article Describes Telnet Access in Windows 11 Made Simple
keywords: WinTelNetAccess,SimplifiedWinLogin,TelnetWindowsXP,EasyTelnetOS,QuickTelnetEntry,WindowsTelnetGuide,SimpleWinTelNet
thumbnail: https://thmb.techidaily.com/34062c0c76761441d1daaab882479cf039a7dd266a5c393fca1f08310200c903.jpg
---

## Telnet Access in Windows 11 Made Simple

 Despite the vulnerability issues, Telnet is still used as a client-server protocol by Windows users. It is primarily used for initial network hardware configuration, remote access, port testing and forwarding, and other tasks that don't involve sensitive information transfer.

 You can enable Telnet on Windows 10 and 11 computers via Command Prompt or the Graphics User Interface (GUI) tool. Here we show you the many ways to enable Telnet on your Windows computer.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2132160/7443" target="_top" id="2132160">
  <img src="//a.impactradius-go.com/display-ad/7443-2132160" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2132160/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Enable Telnet on Windows Using Control Panel

 You can enable Telnet Client using the Classic Control Panel. Since it is an optional feature, you can enable it using the Windows Optional Feature dialog. You can use it[add or remove other users' optional features on Windows](https://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) .

To enable Telnet Client using Control Panel:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel.**
3. In Control Panel, Click on**Uninstall a Program** under**Programs and Features.**  
![turn windows features on or off control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/turn-windows-features-on-or-off-control-panel.jpg)
4. In the left pane, click on the**Turn Windows feature on or off.**  
<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2135316/14409" target="_top" id="2135316">
  <img src="//a.impactradius-go.com/display-ad/14409-2135316" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2135316/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![enable telnet client windows features dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-client-windows-features-dialog.jpg)
5. In the Windows Features dialog, scroll down and select**Telnet Client.**
6. Click**OK** and wait for the feature to install. Once installed, restart your PC to apply the changes and enable the feature.

If you need to disable Telnet:

1. Open the**Windows Features** dialog and unselect**Telnet Client.**
2. Click**OK** and wait for the feature to uninstall.
3. Click on**Restart** now to reboot your PC and apply the changes.

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014851/22899" target="_top" id="2014851">
  <img src="//a.impactradius-go.com/display-ad/22899-2014851" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014851/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<span id="1993650">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Install Telnet Client Using Command Prompt

![enable telnet command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-command-prompt.jpg)

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
<a href="https://unicoeye.pxf.io/c/5597632/2134491/18498" target="_top" id="2134491">
  <img src="//a.impactradius-go.com/display-ad/18498-2134491" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134491/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Check the Telnet Client Status on Your PC

![telnet status enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/telnet-status-enabled.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134237/18498" target="_top" id="2134237">
  <img src="//a.impactradius-go.com/display-ad/18498-2134237" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134237/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You can check if the Telnet client is enabled on your PC using a Command Prompt command. When enabled, the Telnet command will open a new CMD to connect to remote servers and perform other tasks.

1. Launch Command Prompt as administrator (see[how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for in-depth steps).
2. In the Command Prompt window, type**Telnet** and press**Enter** .
3. A new CMD with Microsoft Telnet will open.

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
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-best-budget-gaming-accessories-keyboards-and-mice-under-99/"><u>[New] 2024 Approved  Best Budget Gaming Accessories  Keyboards & Mice Under $99</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-encrypting-lives-techniques-to-mask-personal-information-for-2024/"><u>[New] Encrypting Lives  Techniques to Mask Personal Information for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-twitter-gif-mastery-on-your-desktop-for-2024/"><u>[New] Twitter Gif Mastery on Your Desktop for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-2024-approved-optimize-your-audio-content-expert-tips-for-editing-in-garageband/"><u>[Updated] 2024 Approved  Optimize Your Audio Content  Expert Tips for Editing in GarageBand</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-disabling-automated-podcast-suggestions-for-privacy/"><u>[Updated] Disabling Automated Podcast Suggestions for Privacy</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-how-to-access-facebooks-just-watched-video-list/"><u>[Updated] How To Access Facebook’s Just-Watched Video List</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-step-by-step-to-a-luminous-world-of-android-videos/"><u>[Updated] Step-by-Step to a Luminous World of Android Videos</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unleash-your-videos-potential-thriving-in-youtube-rankings/"><u>[Updated] Unleash Your Video's Potential  Thriving in YouTube Rankings</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/elegoo-saturn-4-ultra-pioneering-progress-and-breakthroughs-in-the-realm-of-high-quality-resin-printing/"><u>Elegoo Saturn 4 Ultra: Pioneering Progress and Breakthroughs in the Realm of High-Quality Resin Printing</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-to-github-desktop-usage-for-novice-windows-11-users/"><u>Essential Guide to GitHub Desktop Usage for Novice Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/exposing-6-incongruent-features-in-windows-11/"><u>Exposing 6 Incongruent Features in Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/fake-the-location-to-get-around-the-mlb-blackouts-on-oppo-reno-10-pro-5g-drfone-by-drfone-virtual-android/"><u>Fake the Location to Get Around the MLB Blackouts on Oppo Reno 10 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-permissions-hurdle-become-an-admin-instantly/"><u>Fix Permissions Hurdle - Become an Admin Instantly</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-videos-from-poco-m6-pro-4g-to-ipad-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Videos from Poco M6 Pro 4G to iPad | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-a-comprehensive-handbook-for-recording-live-hulu-on-pcmacosandroid/"><u>In 2024, A Comprehensive Handbook for Recording Live Hulu on PC/MacOS/Android</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-efficiency-prioritizing-terminal-over-others/"><u>Maximizing Efficiency: Prioritizing Terminal Over Others</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-fn-button-a-comprehensive-guidebook/"><u>Navigating the Fn Button: A Comprehensive Guidebook</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-unlock-pro-level-video-editing-on-windows-8-and-beyond/"><u>New In 2024, Unlock Pro-Level Video Editing on Windows 8 and Beyond</u></a></li>
<li><a href="https://windows11.techidaily.com/no-expense-spared-try-these-5-top-tier-driver-upgrades/"><u>No Expense Spared? Try These 5 Top-Tier Driver Upgrades</u></a></li>
<li><a href="https://windows11.techidaily.com/optimal-web-access-a-comparative-study-of-browser-ram-use/"><u>Optimal Web Access: A Comparative Study of Browser RAM Use</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-audacity-audio-error-in-windows-1111/"><u>Overcoming Audacity Audio Error in Windows 11/11</u></a></li>
<li><a href="https://windows11.techidaily.com/proactive-defense-7-steps-to-thwart-windows-hackers/"><u>Proactive Defense: 7 Steps to Thwart Windows Hackers</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-for-erroneous-0x80246007-in-win11-uptime/"><u>Quick Fix for Erroneous 0X80246007 in Win11 Uptime</u></a></li>
<li><a href="https://windows11.techidaily.com/realign-windows-clock-stop-time-discrepancy-woes/"><u>Realign Windows Clock: Stop Time Discrepancy Woes</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstating-credible-power-consumption-forecasts-on-windows-11/"><u>Reinstating Credible Power Consumption Forecasts on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-operative-bin-icon-on-windows-11/"><u>Restoring Operative Bin Icon on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/seamlessly-incorporate-gallery-view-into-file-explorer/"><u>Seamlessly Incorporate Gallery View Into File Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/show-more-pins-strategies-for-start-screen/"><u>Show More Pins: Strategies for Start Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/sidestep-w11s-onedrive-error-code-def5/"><u>Sidestep W11's OneDrive Error Code DEF5</u></a></li>
<li><a href="https://win-amazing.techidaily.com/step-by-step-guide-to-installing-hp-laserjet-5200-drivers-on-windows-11-10-and-8/"><u>Step-by-Step Guide to Installing HP LaserJet 5200 Drivers on Windows 11, 10 & 8</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-qbittorrent-transfer-from-one-windows-to-another/"><u>Steps for qBittorrent Transfer From One Windows to Another</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-overcome-game-hub-connectivity-issues/"><u>Strategies to Overcome Game Hub Connectivity Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-your-win-based-software-overcome-too-many-requests/"><u>Streamlining Your Win-Based Software: Overcome Too Many Requests</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-application-launch-in-windows-11/"><u>Swift Application Launch in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/sync-solutions-for-win1011-users-with-adobe-not-available/"><u>Sync Solutions for Win10/11 Users with Adobe Not Available</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-efficient-path-to-time-stamped-image-documentation-for-2024/"><u>The Efficient Path to Time-Stamped Image Documentation for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-essential-guide-to-downloading-and-editing-whatsapp-alerts-for-2024/"><u>The Essential Guide to Downloading & Editing WhatsApp Alerts for 2024</u></a></li>
<li><a href="https://fox-that.techidaily.com/1721472694629-troubleshoot-the-low-memory-warning-issue-in-roblox-for-your-iphone-easily/"><u>Troubleshoot the 'Low Memory Warning' Issue in Roblox for Your iPhone Easily!</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-11-for-5ghz-wi-fi-issues/"><u>Troubleshooting Windows 11 for 5GHz Wi-Fi Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-itunes-performance-issues-on-windows-pcs/"><u>Unlocking iTunes Performance Issues on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-potential-from-esd-to-iso-file-transformation/"><u>Unlocking Windows' Potential: From ESD to ISO File Transformation</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-how-to-edit-videos-with-quicktime-on-mac-step-by-step-guide-for-2024/"><u>Updated How to Edit Videos with QuickTime on Mac Step-by-Step Guide for 2024</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-free-3gp-video-editing-rotate-flip-and-more-with-these-top-tools/"><u>Updated In 2024, Free 3GP Video Editing Rotate, Flip, and More with These Top Tools</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-google-play-services-keeps-stopping-on-vivo-y27-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What to Do if Google Play Services Keeps Stopping on Vivo Y27 5G | Dr.fone</u></a></li>
</ul></div>
