---
title: Redirecting and Reinstating Windows 10/11'S MS Store
date: 2024-10-11T20:28:46.951Z
updated: 2024-10-12T17:20:37.784Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Redirecting and Reinstating Windows 10/11'S MS Store
excerpt: This Article Describes Redirecting and Reinstating Windows 10/11'S MS Store
keywords: Win10MSStoreRedirect,Win11MSStoreReinstate,RedirectWinStore,ReinstallWinStore,WinOSStoreUpdate,MSStoreRedirection,OSStoreRevive
thumbnail: https://thmb.techidaily.com/ef69c6cfc05813b51fd415fbeca882846dc473b99199e876bd020898984fe0d1.png
---

## Redirecting and Reinstating Windows 10/11'S MS Store

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
<span id="1977028">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977028.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977028">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977028.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977028%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977028/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151884/7443" target="_top" id="2151884">
  <img src="//a.impactradius-go.com/display-ad/7443-2151884" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151884/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997657/19272" target="_top" id="1997657">
  <img src="//a.impactradius-go.com/display-ad/19272-1997657" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997657/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-helps.techidaily.com/new-top-camera-brands-for-future-musical-video-production/"><u>[New] Top Camera Brands for Future Musical Video Production</u></a></li>
<li><a href="https://windows11.techidaily.com/boldly-block-wi-fi-signals-in-windows/"><u>Boldly Block Wi-Fi Signals in Windows</u></a></li>
<li><a href="https://fox-that.techidaily.com/bypassing-bug-1-7-in-your-iphone-x-quick-fix-guides-revealed/"><u>Bypassing Bug #1-#7 in Your iPhone X - Quick Fix Guides Revealed!</u></a></li>
<li><a href="https://buynow-help.techidaily.com/evaluating-the-pros-and-cons-of-the-samsung-55-inch-ru7300-smart-led-a-complete-4k-television-assessment/"><u>Evaluating the Pros and Cons of the Samsung 55-Inch RU7300 Smart LED - A Complete 4K Television Assessment</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-pc-hardware-requirement-errors/"><u>Fixing Windows PC Hardware Requirement Errors</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-in-ar-games-on-tecno-pova-5-drfone-by-drfone-virtual-android/"><u>How to Simulate GPS Movement in AR games On Tecno Pova 5? | Dr.fone</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/o-spark-interest-with-unique-channel-names/"><u>How to Spark Interest With Unique Channel Names</u></a></li>
<li><a href="https://windows11.techidaily.com/maximize-output-win-based-time-management-apps-reviewed/"><u>Maximize Output: Win-Based Time Management Apps Reviewed</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-top-10-free-surveillance-software-options/"><u>New In 2024, Top 10 Free Surveillance Software Options</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolving-pc-spec-issues-for-software-deployment/"><u>Resolving PC Spec Issues for Software Deployment</u></a></li>
<li><a href="https://windows11.techidaily.com/skyrocketing-speed-for-battlenet-downloads-on-your-pc/"><u>Skyrocketing Speed for Battle.net Downloads on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-to-manipulating-fax-cover-pages-on-win11/"><u>Step-by-Step Guide to Manipulating Fax Cover Pages on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-remedy-unsupported-audio-device-in-windows-os/"><u>Steps to Remedy Unsupported Audio Device in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-address-failed-downloads-in-windows-1011/"><u>Strategies to Address Failed Downloads in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-full-potential-of-taskbar-in-win11/"><u>Unlock the Full Potential of Taskbar in Win11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/unlocking-success-optimizing-gaming-videos-via-smart-use-of-hashtags-for-2024/"><u>Unlocking Success Optimizing Gaming Videos via Smart Use of Hashtags for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/unmatched-5-ios-backdrop-change-solutions-iphone-x87/"><u>Unmatched 5 iOS Backdrop Change Solutions (iPhone X/8/7)</u></a></li>
</ul></div>

