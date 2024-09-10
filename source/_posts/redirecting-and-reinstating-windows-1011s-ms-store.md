---
title: Redirecting and Reinstating Windows 10/11'S MS Store
date: 2024-09-09T11:58:16.501Z
updated: 2024-09-10T11:58:16.501Z
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115925/19272" target="_top" id="2115925">
  <img src="//a.impactradius-go.com/display-ad/19272-2115925" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115925/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Redirecting and Reinstating Windows 10/11'S MS Store

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

<!-- affiliate ads begin -->
<a href="https://bluettiit.sjv.io/c/5597632/2114264/17093" target="_top" id="2114264">
  <img src="//a.impactradius-go.com/display-ad/17093-2114264" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettiit.sjv.io/i/5597632/2114264/17093" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Re-Register Microsoft Store Apps for Current Users

![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123475/16836" target="_top" id="2123475">
  <img src="//a.impactradius-go.com/display-ad/16836-2123475" border="0" alt="https://techidaily.com" width="300" height="75"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123475/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<span id="1983588">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983588.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983588">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983588.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983588%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983588/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

<!-- affiliate ads begin -->
<span id="1993645">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993645.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993645">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993645.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993645%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993645/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115917/19272" target="_top" id="2115917">
  <img src="//a.impactradius-go.com/display-ad/19272-2115917" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115917/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://on-screen-recording.techidaily.com/new-simple-strategies-upside-down-video-rotation-via-vlc/"><u>[New] Simple Strategies  Upside-Down Video Rotation via VLC</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-perfect-game-video-edits-made-easy-for-newcomers/"><u>[Updated] 2024 Approved  Perfect Game Video Edits Made Easy for Newcomers</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-2024-approved-swift-shadow-magic-one-minute/"><u>[Updated] 2024 Approved  Swift Shadow Magic, One Minute</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-essential-android-ad-blocking-the-top-7-app-list/"><u>[Updated] Essential Android Ad Blocking  The Top 7 App List</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-premier-vr-manipulators-to-try-now/"><u>[Updated] Premier VR Manipulators to Try Now</u></a></li>
<li><a href="https://windows11.techidaily.com/1-intelligent-workspace-companion-how-stardock-desktopgpt-surges-past-traditional-copilots/"><u>1. Intelligent Workspace Companion: How Stardock DesktopGPT Surges Past Traditional Copilots</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerating-your-browsing-how-microsoft-edges-speed-is-leaping-forward/"><u>Accelerating Your Browsing: How Microsoft Edge's Speed Is Leaping Forward</u></a></li>
<li><a href="https://windows11.techidaily.com/activate-graphics-card-fast-tracking-on-windows-1011-step-by-step-guide/"><u>Activate Graphics Card Fast Tracking on Windows 10/11: Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/affordable-and-durable-storage-solutions-below-100/"><u>Affordable and Durable Storage Solutions Below $100</u></a></li>
<li><a href="https://windows11.techidaily.com/ai-enhanced-microsoft-teams-transforming-your-virtual-background-easily/"><u>AI-Enhanced Microsoft Teams: Transforming Your Virtual Background Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/create-an-eye-catching-custom-windows-desktop-with-rainmeter-tips/"><u>Create an Eye-Catching Custom Windows Desktop with Rainmeter Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-improved-voice-modulation-in-the-latest-version-of-microsoft-clipchamp/"><u>Discover Improved Voice Modulation in the Latest Version of Microsoft Clipchamp</u></a></li>
<li><a href="https://windows11.techidaily.com/ease-system-overload-in-your-linux-vmware-by-regaining-lost-storage-capacity-quickly/"><u>Ease System Overload in Your Linux Vmware by Regaining Lost Storage Capacity Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-strategies-to-address-and-correct-dpc-watchdog-errors-in-windows-10-systems/"><u>Effective Strategies to Address and Correct DPC Watchdog Errors in Windows 10 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-techniques-for-forcing-shut-down-non-responsive-programs-in-windows-11/"><u>Effective Techniques for Forcing Shut Down Non-Responsive Programs in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-file-management-game-top-4-advanced-techniques-for-windows-11-tab-users/"><u>Elevate Your File Management Game: Top 4 Advanced Techniques for Windows 11 Tab Users</u></a></li>
<li><a href="https://windows11.techidaily.com/elgato-stream-deck-neo-review-initial-thoughts-and-unboxing-experience/"><u>Elgato Stream Deck Neo Review - Initial Thoughts and Unboxing Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/embracing-the-elegance-of-onsite-data-duplication-a-guide-to-local-backups/"><u>Embracing the Elegance of Onsite Data Duplication: A Guide to Local Backups</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-windows-network-protection-with-microsofts-newly-integrated-zero-trust-dns-technology/"><u>Enhancing Windows Network Protection with Microsoft's Newly Integrated Zero Trust DNS Technology</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-your-windows-navigation-with-superior-file-management/"><u>Enhancing Your Windows Navigation with Superior File Management</u></a></li>
<li><a href="https://windows11.techidaily.com/expanded-access-microsoft-now-supports-more-devices-with-windows-11-upgrade/"><u>Expanded Access: Microsoft Now Supports More Devices with Windows 11 Upgrade</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-windows-11-on-arm-a-comprehensive-guide-and-its-differences-from-traditional-windows-systems/"><u>Exploring Windows 11 on ARM: A Comprehensive Guide & Its Differences From Traditional Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/financial-support-for-individuals-and-businesses/"><u>Financial Support for Individuals and Businesses</u></a></li>
<li><a href="https://windows11.techidaily.com/from-doubts-to-discovery-why-the-old-concerns-of-switching-from-windows-to-linux-have-been-disproven/"><u>From Doubts to Discovery: Why the Old Concerns of Switching From Windows to Linux Have Been Disproven</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-your-system-up-to-date-with-new-nvidia-drivers-for-windows-platforms/"><u>Get Your System Up to Date with New Nvidia Drivers for Windows Platforms</u></a></li>
<li><a href="https://windows11.techidaily.com/getting-started-with-arm-technology-an-unboxing-and-review-of-the-dell-inspiron-14-plus-7441/"><u>Getting Started with ARM Technology: An Unboxing and Review of the Dell Inspiron 14 Plus (7441)</u></a></li>
<li><a href="https://windows11.techidaily.com/how-cybercriminals-exploit-windows-updates-to-bypass-security-fixes/"><u>How Cybercriminals Exploit Windows Updates to Bypass Security Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-windows-booting-issues-a-step-by-step-guide/"><u>How to Fix Windows Booting Issues: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-turn-your-android-device-into-a-windows-11-camera-a-step-by-step-guide/"><u>How to Turn Your Android Device Into a Windows 11 Camera: A Step-by-Step Guide</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-everything-you-need-to-know-about-lock-screen-settings-on-your-google-pixel-7a-by-drfone-android/"><u>In 2024, Everything You Need to Know about Lock Screen Settings on your Google Pixel 7a</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-ultimate-guide-to-get-the-meltan-box-pokemon-go-for-samsung-galaxy-z-flip-5-drfone-by-drfone-virtual-android/"><u>In 2024, Ultimate guide to get the meltan box pokemon go For Samsung Galaxy Z Flip 5 | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/master-your-gameplay-essential-steps-5-tips-for-mac-users/"><u>Master Your Gameplay: Essential Steps (5 Tips) for Mac Users</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/tutorial-to-change-vivo-y27-5g-imei-without-root-a-comprehensive-guide-by-drfone-android/"><u>Tutorial to Change Vivo Y27 5G IMEI without Root A Comprehensive Guide</u></a></li>
</ul></div>
