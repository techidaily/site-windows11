---
title: "Redeeming Windows: Reviving MS Store Programs"
date: 2024-11-08T16:46:48.436Z
updated: 2024-11-15T16:39:09.229Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Redeeming Windows: Reviving MS Store Programs"
excerpt: "This Article Describes Redeeming Windows: Reviving MS Store Programs"
keywords: Windows Reimagined,MS Store Restore,Retrieve Windows Apps,Revive MS Programs,Purchase Windows Titles,Accessing MS Marketplace,Renew MS Software Use
thumbnail: https://thmb.techidaily.com/bb9708a331c4c3dd31e799c079bb73652a9e75d1a08dd178d051b1af275cc7e6.jpg
---

## Redeeming Windows: Reviving MS Store Programs

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
<a href="https://appsumo.8odi.net/c/5597632/2151882/7443" target="_top" id="2151882">
  <img src="//a.impactradius-go.com/display-ad/7443-2151882" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151882/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136617/26400" target="_top" id="2136617">
  <img src="//a.impactradius-go.com/display-ad/26400-2136617" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136617/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012434/19272" target="_top" id="2012434">
  <img src="//a.impactradius-go.com/display-ad/19272-2012434" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012434/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-expert-insights-bridging-obs-and-facebook-live-streaming/"><u>[New] 2024 Approved Expert Insights Bridging OBS and Facebook Live Streaming</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-compre-omprehensive-razer-video-cam-test/"><u>[New] Compre Omprehensive Razer Video Cam Test</u></a></li>
<li><a href="https://windows11.techidaily.com/advance-work-efficiency-with-windows-smart-launcher-tool/"><u>Advance Work Efficiency with Windows' Smart Launcher Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-decibels-on-windows-integrated-bt-audio/"><u>Boosting Decibels on Windows-Integrated BT Audio</u></a></li>
<li><a href="https://windows11.techidaily.com/capitalizing-on-windows-capabilities-for-macos/"><u>Capitalizing on Windows Capabilities for macOS</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-discord-setup-woes-on-windows-11/"><u>Correcting Discord Setup Woes on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/1719293277231-get-personalized-chatbot-experience-local-clone-for-windows-at-no-cost/"><u>Get Personalized ChatBot Experience: Local Clone for Windows at No Cost</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-vivo-y78-5g-phone-password-without-factory-reset-by-drfone-android/"><u>In 2024, How to Unlock Vivo Y78 5G Phone Password Without Factory Reset?</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-meizu-21-drfone-by-drfone-virtual-android/"><u>In 2024, What is the best Pokemon for pokemon pvp ranking On Meizu 21? | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/premier-networks-for-your-personalized-watchlist/"><u>Premier Networks for Your Personalized Watchlist</u></a></li>
<li><a href="https://tech-haven.techidaily.com/1723808337934-windows-10-settings-wont-open-solved/"><u>Windows 10 Settings Won't Open ? [Solved]</u></a></li>
<li><a href="https://discover-guides.techidaily.com/4/"><u>オススメのビリビリ動画ダウンローダートップ4サイトを紹介します</u></a></li>
</ul></div>

