---
title: Overcoming Package Discrepinas in Windows Photos with Step-by-Step Tips
date: 2024-08-15T15:43:40.526Z
updated: 2024-08-16T15:43:40.526Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Package Discrepinas in Windows Photos with Step-by-Step Tips
excerpt: This Article Describes Overcoming Package Discrepinas in Windows Photos with Step-by-Step Tips
keywords: Fixing Photo Errors,Windows Photo Correction,Correct Package Discrepancies,Error Fixing Steps,Steps for Photo Alignment,Window's Photos Error Guide,Tips for Photo Issue Resolution
thumbnail: https://thmb.techidaily.com/6b74a794374950c8c7d33f01e283b8595a0e02efb75345cb412052a7193f6b01.jpg
---

## Overcoming Package Discrepinas in Windows Photos with Step-by-Step Tips

 Microsoft Photos is the default image viewer in Windows with which many users open picture files. However, some users can’t open images in Photos because of a “Package could not be registered” error. That issue arises for some Photos users when they try to open JPG or PNG images in that app.

 This is how you can fix the “Package could not be registered” error in Windows 11 and 10.

## 1\. Run the Windows Store Apps Troubleshooter

 Start your error troubleshooting with a troubleshooter for UWP apps on Microsoft Store. Windows Store Apps is a troubleshooter that could identify and resolve an issue with the Photos app. These are the steps for running that troubleshooter in Windows 11:

1. Simultaneously press the**Win + I** keyboard keys to bring up Settings.
2. Click**Troubleshoot** within the**System** tab of Settings.
3. Next, select**Other trouble-shooters** to reach the Windows troubleshooters in Settings.
4. Press the Windows Store Apps troubleshooter’s**Run** button.  
![The troubleshooters in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/other-troubleshooters-in-settings.jpg)
5. Then select to apply fixes suggested by the Windows Store App troubleshooter.  
![The Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-store-apps-troubleshooter.jpg)

 The same troubleshooter is also available within Windows 10’s Settings app. To access it, click the**Update & Security** category and**Troubleshoot** tab. Then you can select**Additional troubleshooters** to bring up the list of troubleshooting tools.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851655&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. Update Photos

 Updating Microsoft Store apps like Photos can fix issues with them. So, try updating Microsoft Photos like this:

1. Click**Start** and select Microsoft Store on that button’s menu.
2. Select Microsoft Store’s**Library** tab.
3. Click**Get updates** to see what apps need updating. MS Store will then automatically download and install an update for Photos if available.  
![The Get updates button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/get-updates-button.jpg)
4. Wait for the Photos app update to finish before closing Microsoft Store.

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Repair and Reset the Photos Apps

 Repairing or resetting Photos will likely fix the “Package could not be registered” if that app has corrupted files or data. You can select adjacent**Repair** and**Reset** troubleshooting options for Photos within Settings’ Apps & Features tool. To apply this solution, follow the instructions in our guide for [resetting Microsoft Store apps](https://www.makeuseof.com/windows-reset-app/) . Select the**Repair** option first and**Reset** second if necessary.

![The Repair and Reset buttons for Photos](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-repair-reset-buttons.jpg)
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Run the Deployment Image and System File Checker Tools

 The “Package could not be registered” error can also be due to Windows system file corruption. That much has been confirmed by users who’ve said that running Deployment Image Servicing Management and System File Checker scans fixed this issue on their PCs. You can apply this potential solution by [opening the Command Prompt with admin rights](https://www.makeuseof.com/windows-11-open-command-prompt/) and running these separate DISM and SFC commands:

`DISM.exe /Online /Cleanup-image /Restorehealth`

`sfc /scannow`

 Run the Deployment Image Servicing Management scan command before the System File Checker tool. Leave the Command Prompt open until it shows a Windows Resource Protection message for the SFC scan. If it says Windows Resource Protection repaired files, this resolution might have resolved the “Package could not be registered” error.

## 5\. Reinstall Photos

 If the “Package could not be registered” error persists after applying the resolutions above, you might need to reinstall Photos to fix it. This solution is the most likely one to fix a corrupted Photos app. You can uninstall and reinstall Photos with PowerShell like this:

1. Start PowerShell with a method in our guide to [opening PowerShell as an administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. Then input this command for uninstalling PowerShell and hit**Enter** :  
`Get-AppxPackage Microsoft.Windows.Photos | Remove-AppxPackage`  
![The uninstall Photos command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/remove-photos-command.jpg)
3. To reinstall Photos, input this PowerShell command and press**Enter** :  
`Get-AppxPackage -allusers Microsoft.Windows.Photos | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reinstall Photos app command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reinstall-photos-app.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075475/7443" target="_top" id="2075475"><img src="//a.impactradius-go.com/display-ad/7443-2075475" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Restart your PC after reinstalling Photos.

## 6\. Reset Windows

 If you’ve tried all other resolutions suggested here, there could be a deeper Windows issue causing the “Package could not be registered” Photos error. Then a system reset could be needed to remedy that deeper issue. Resetting Windows will refresh the platform’s components and restore it to a default state.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reset-this-pc-tool.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->

 This is suggested as a last resort because you’ll need to reinstall third-party software installed before resetting Windows. However, you can select to keep user files such as photos, documents, videos, etc. Our [guide to resetting Windows 10 and 11](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) tells you how to perform a factory reset.

## Open Your Images in Photos Again

 One of the above resolutions will likely resolve the “Package Could not be Registered” error on your Windows 11/10 PC. However, remember there are plenty of third-party app alternatives you can open your images with if that Photos error persists. IrfanView, XnView, and FastStone Image Viewer are among the best Photos alternatives that are freely available.

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
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-tips-for-incorporating-songs-in-your-fb-story/"><u>[New] In 2024, Tips for Incorporating Songs in Your FB Story</u></a></li>
<li><a href="https://windows11.techidaily.com/10-essential-windows-methods-for-controller-recognition/"><u>10 Essential Windows Methods for Controller Recognition</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-exploring-the-leading-10-macwindows-srt-enhancers/"><u>2024 Approved  Exploring the Leading 10 Mac/Windows SRT Enhancers</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-ultimate-tally-unveiling-the-highest-rated-threads-on-reddit/"><u>2024 Approved  The Ultimate Tally  Unveiling the Highest-Rated Threads on Reddit</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-youtubes-earnings-explained-making-money-from-ads/"><u>2024 Approved  YouTube’s Earnings Explained  Making Money From Ads</u></a></li>
<li><a href="https://windows11.techidaily.com/adapting-windows-11-multifaceted-monitor-wallpaper-strategy/"><u>Adapting Windows 11: Multifaceted Monitor Wallpaper Strategy</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-lost-extra-screen-in-w11/"><u>Addressing Lost Extra Screen in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/alomware-essentials-for-customizing-windows-experience/"><u>AlomWare Essentials for Customizing Windows Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/augmenting-windows-functionality-with-these-top-6-android-apps/"><u>Augmenting Windows Functionality with These Top 6 Android Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/avoidance-of-soon-to-end-windows-license-issues/"><u>Avoidance of Soon-to-End Windows License Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/begin-your-media-adventure-windows-media-player/"><u>Begin Your Media Adventure: Windows Media Player</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-your-vbox-windows-install-with-dependencies/"><u>Boost Your VBox Windows Install with Dependencies</u></a></li>
<li><a href="https://windows11.techidaily.com/combating-writing-denials-in-windows-11-environment/"><u>Combating Writing Denials in Windows 11 Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-windows-steam-blackout-immediate-solutions/"><u>Combatting Windows Steam Blackout: Immediate Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/comparative-overview-of-installation-methods-exe-and-msi-files/"><u>Comparative Overview of Installation Methods: Exe & Msi Files</u></a></li>
<li><a href="https://windows11.techidaily.com/configure-windows-11-to-optimize-system-audio-performance/"><u>Configure Windows 11 to Optimize System Audio Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-clock-divergence-chrome-vs-windows/"><u>Correcting Clock Divergence: Chrome vs Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/counteracting-the-impact-of-vac-denial-in-steam-gaming/"><u>Counteracting the Impact of VAC Denial in Steam Gaming</u></a></li>
<li><a href="https://windows11.techidaily.com/creating-custom-volume-control-commands-for-windows-11-users/"><u>Creating Custom Volume Control Commands for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/darkeningwindowsnotepaddisplaysettings/"><u>DarkeningWindowsNotepadDisplaySettings</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-complexity-of-wintoys-your-guide-to-a-versatile-tool/"><u>Decoding the Complexity of 'WinToys': Your Guide to a Versatile Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/defensive-operations-mastering-windows-unauthorized-prevention/"><u>Defensive Operations: Mastering Windows Unauthorized Prevention</u></a></li>
<li><a href="https://windows11.techidaily.com/direct-guide-to-reactivate-print-spool/"><u>Direct Guide to Reactivate Print Spool</u></a></li>
<li><a href="https://windows11.techidaily.com/discerning-the-divergences-between-terminal-and-powershell/"><u>Discerning the Divergences Between Terminal & PowerShell</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-distinctions-between-microsoft-and-standard-windows-accounts/"><u>Dissecting: Distinctions Between Microsoft & Standard Windows Accounts</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-netflix-location-to-get-more-country-version-on-itel-s23-drfone-by-drfone-virtual-android/"><u>How to Change Netflix Location to Get More Country Version On Itel S23 | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/innocn-39g1r-massive-sub-500-high-refresh-gaming-monitor/"><u>InnoCN 39G1R: Massive, Sub-$500 High Refresh Gaming Monitor</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/navigating-the-basics-of-setting-up-and-timing-google-meet-for-2024/"><u>Navigating the Basics of Setting Up and Timing Google Meet for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/sculpt-personalized-digital-laughs-now/"><u>Sculpt Personalized Digital Laughs Now</u></a></li>
<li><a href="https://windows11.techidaily.com/1719309112975-stuck-in-chrome-unfreeze-windows-11-with-simple-fixes/"><u>Stuck in Chrome? Unfreeze Windows 11 with Simple Fixes!</u></a></li>
<li><a href="https://screen-capture.techidaily.com/take-screenshots-with-precision-on-a-mac-for-2024/"><u>Take Screenshots with Precision on a Mac for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/the-future-awaits-elevate-your-fb-chronicles-for-free/"><u>The Future Awaits  Elevate Your FB Chronicles for FREE</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-ultimate-tiktok-unboxers-playbook-for-likes/"><u>The Ultimate TikTok Unboxer's Playbook for Likes</u></a></li>
<li><a href="https://games-able.techidaily.com/1719168475628-top-titles-towns-winners-worlds/"><u>Top Titles Towns: Winners' Worlds</u></a></li>
</ul></div>
