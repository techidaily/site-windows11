---
title: "Reinstating Microsoft Store Apps: Windows 11'S Guide to Fixes"
date: 2024-10-18T01:53:59.869Z
updated: 2024-10-19T01:29:30.998Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Reinstating Microsoft Store Apps: Windows 11'S Guide to Fixes"
excerpt: "This Article Describes Reinstating Microsoft Store Apps: Windows 11'S Guide to Fixes"
keywords: Windows 11 App Restore,Microsoft Store Update Guide,Windows 11 Fixes Steps,Reinstate MS Store Apps,Windows 11 Troubleshooting,MS Store Reinstallation,Fixing Win11 Store Issues
thumbnail: https://thmb.techidaily.com/f3b5fbbb41ff3e0e15766362f9082ba5609c00b8437978e5e3317dc5d76ea72c.jpg
---

## Reinstating Microsoft Store Apps: Windows 11'S Guide to Fixes

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

## How to Re-Register Microsoft Store Apps for Current Users

![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

 If the[Microsoft Store app issue](https://www.makeuseof.com/tag/5-tips-fix-windows-store-app-issues-windows-10/) exists with a specific user account, you don’t need to re-register the app for all the user accounts on your computer. Instead, you can re-register the app only for the current user account.

To re-register Microsoft Store apps for the current user:

1. Press the**Win** key and type "powershell" into the Search bar.
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell console, type the following command and press**Enter** :  
`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
4. Wait for the command to execute and complete. You may see a blue loading graphic.
5. Once done, type**exit** and press**Enter** to close PowerShell.

 During the process, you may see some errors highlighted in red. It is due to PowerShell trying to reinstall existing apps on Windows. So, ignore the error and wait for the process to complete.

<!-- affiliate ads begin -->
<span id="1793213">
					<video width="864" height="1296" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1793213.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19135-1793213">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1793213.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftinyland.pxf.io%2Fc%2F5597632%2F1793213%2F19135'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793213/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137224/26400" target="_top" id="2137224">
  <img src="//a.impactradius-go.com/display-ad/26400-2137224" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137224/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1959778/19272" target="_top" id="1959778">
  <img src="//a.impactradius-go.com/display-ad/19272-1959778" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959778/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Install and Re-Register All Microsoft Store Apps on Windows 11

 Re-registering Windows apps is often necessary when Microsoft Store is not working. It can also help deal with other Windows settings and apps. If the issue persists, try the built-in Windows Store Apps troubleshooter to fix common Microsoft Store app issues.

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
<li><a href="https://extra-approaches.techidaily.com/new-step-by-step-audacity-crossfading-process/"><u>[New] Step-by-Step Audacity Crossfading Process</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-2024-approved-discover-the-ultimate-display-selection-boost-your-xbox-experience/"><u>[Updated] 2024 Approved Discover the Ultimate Display Selection Boost Your Xbox Experience</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-harnessing-your-creative-power-with-ipad-for-time-lapses-for-2024/"><u>[Updated] Harnessing Your Creative Power with iPad for Time-Lapses for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/5-ways-to-reset-vivo-v30-lite-5g-without-volume-buttons-drfone-by-drfone-reset-android-reset-android/"><u>5 Ways to Reset Vivo V30 Lite 5G Without Volume Buttons | Dr.fone</u></a></li>
<li><a href="https://win-answers.techidaily.com/cyberpunk-2077-hurdles-heres-how-to-successfully-download-your-game-on-steam/"><u>Cyberpunk 2077 Hurdles? Here’s How to Successfully Download Your Game on Steam</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-for-win11-defender-firewall-control/"><u>Essential Tips for Win11 Defender Firewall Control</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tactics-to-unite-windows-directories/"><u>Expert Tactics to Unite Windows Directories</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-abnormal-character-output-windows-wise/"><u>Handling Abnormal Character Output Windows-Wise</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-google-frp-lock-from-poco-x5-pro-devices-by-drfone-android/"><u>In 2024, How to Bypass Google FRP Lock from Poco X5 Pro Devices</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-essence-of-dji-inspire-2-distilled/"><u>In 2024, The Essence of DJI Inspire 2 Distilled</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-ultimate-guide-on-iphone-14-icloud-activation-lock-bypass-by-drfone-ios/"><u>In 2024, Ultimate Guide on iPhone 14 iCloud Activation Lock Bypass</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-hardware-space-exploring-disks-in-w10-and-w11/"><u>Mastering Hardware Space: Exploring Disks in W10 & W11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-non-detected-proxy-setup/"><u>Navigating Windows Non-Detected Proxy Setup</u></a></li>
<li><a href="https://driver-install.techidaily.com/powering-up-nvidias-3090-driver-release/"><u>Powering Up: NVIDIA's 3090 Driver Release</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-tip-erasing-microsoft-edge-on-windows-11/"><u>Quick Tip: Erasing Microsoft Edge on Windows 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/remove-frp-lock-on-note-30-pro-by-drfone-android-unlock-remove-google-frp/"><u>Remove FRP Lock on Note 30 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/the-hidden-the-forgotten-now-revealed-restoring-your-windows-on-win10win11/"><u>The Hidden, The Forgotten, Now Revealed: Restoring Your Windows on Win10/Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-vlc-lag-on-windows-devices/"><u>Troubleshooting VLC Lag on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-quick-deletion-windows-customization-for-instant-removal/"><u>Unleashing Quick Deletion: Windows Customization for Instant Removal</u></a></li>
</ul></div>

