---
title: How to Fix the “Package Could Not Be Registered” Photos Error in Windows 11 & 11
date: 2024-08-15T16:21:46.277Z
updated: 2024-08-16T16:21:46.277Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix the “Package Could Not Be Registered” Photos Error in Windows 11 & 11
excerpt: This Article Describes How to Fix the “Package Could Not Be Registered” Photos Error in Windows 11 & 11
keywords: Win11 Photo Error Fix,Register Photos in Win11,Win11 Package Registration,Solve Win11 Photo Error,Windows 11 Photo Registration,Fixing Win11 Photo Issue,Correct Photo Error Win11
thumbnail: https://thmb.techidaily.com/b2d913b57df62249e08cf6aa2213e0e218bf0ce45d452041bd7c83bf359b02fd.jpg
---

## How to Fix the “Package Could Not Be Registered” Photos Error in Windows 11 & 11

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

## 2\. Update Photos

 Updating Microsoft Store apps like Photos can fix issues with them. So, try updating Microsoft Photos like this:

1. Click**Start** and select Microsoft Store on that button’s menu.
2. Select Microsoft Store’s**Library** tab.
3. Click**Get updates** to see what apps need updating. MS Store will then automatically download and install an update for Photos if available.  
![The Get updates button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/get-updates-button.jpg)
<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Wait for the Photos app update to finish before closing Microsoft Store.

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Repair and Reset the Photos Apps

 Repairing or resetting Photos will likely fix the “Package could not be registered” if that app has corrupted files or data. You can select adjacent**Repair** and**Reset** troubleshooting options for Photos within Settings’ Apps & Features tool. To apply this solution, follow the instructions in our guide for[resetting Microsoft Store apps](https://www.makeuseof.com/windows-reset-app/) . Select the**Repair** option first and**Reset** second if necessary.

![The Repair and Reset buttons for Photos](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-repair-reset-buttons.jpg)

## 4\. Run the Deployment Image and System File Checker Tools

 The “Package could not be registered” error can also be due to Windows system file corruption. That much has been confirmed by users who’ve said that running Deployment Image Servicing Management and System File Checker scans fixed this issue on their PCs. You can apply this potential solution by[opening the Command Prompt with admin rights](https://www.makeuseof.com/windows-11-open-command-prompt/) and running these separate DISM and SFC commands:

`DISM.exe /Online /Cleanup-image /Restorehealth`

`sfc /scannow`

 Run the Deployment Image Servicing Management scan command before the System File Checker tool. Leave the Command Prompt open until it shows a Windows Resource Protection message for the SFC scan. If it says Windows Resource Protection repaired files, this resolution might have resolved the “Package could not be registered” error.

## 5\. Reinstall Photos

 If the “Package could not be registered” error persists after applying the resolutions above, you might need to reinstall Photos to fix it. This solution is the most likely one to fix a corrupted Photos app. You can uninstall and reinstall Photos with PowerShell like this:

1. Start PowerShell with a method in our guide to[opening PowerShell as an administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. Then input this command for uninstalling PowerShell and hit**Enter** :  
`Get-AppxPackage Microsoft.Windows.Photos | Remove-AppxPackage`  
![The uninstall Photos command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/remove-photos-command.jpg)
<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. To reinstall Photos, input this PowerShell command and press**Enter** :  
`Get-AppxPackage -allusers Microsoft.Windows.Photos | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reinstall Photos app command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reinstall-photos-app.jpg)
4. Restart your PC after reinstalling Photos.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Reset Windows

 If you’ve tried all other resolutions suggested here, there could be a deeper Windows issue causing the “Package could not be registered” Photos error. Then a system reset could be needed to remedy that deeper issue. Resetting Windows will refresh the platform’s components and restore it to a default state.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reset-this-pc-tool.jpg)
<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 This is suggested as a last resort because you’ll need to reinstall third-party software installed before resetting Windows. However, you can select to keep user files such as photos, documents, videos, etc. Our[guide to resetting Windows 10 and 11](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) tells you how to perform a factory reset.

<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-enhancing-follows-into-genuine-subscriptions/"><u>[New] 2024 Approved  Enhancing Follows Into Genuine Subscriptions</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-enhance-your-online-presence-with-these-50-complimentary-banners-for-2024/"><u>[New] Enhance Your Online Presence with These 50 Complimentary Banners for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-mirthful-melodies-smart-picks-for-funny-phone-tones/"><u>[New] Mirthful Melodies  Smart Picks for Funny Phone Tones</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-ios-screen-recording-the-updated-process/"><u>[Updated] 2024 Approved  IOS Screen Recording   The Updated Process</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-unrivaled-selection-of-top-10-mobile-video-calling-apps/"><u>[Updated] 2024 Approved  Unrivaled Selection of Top 10 Mobile Video Calling Apps</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-becoming-a-master-of-instagrams-video-dialogue-dynamics-for-2024/"><u>[Updated] Becoming a Master of Instagram's Video Dialogue Dynamics for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-comprehensive-overview-utilizing-googles-automatic-transcription-service/"><u>[Updated] Comprehensive Overview  Utilizing Google's Automatic Transcription Service</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-direct-from-device-to-digital-world-recording-your-apple-gadgets/"><u>[Updated] In 2024, Direct From Device to Digital World  Recording Your Apple Gadgets</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-innovative-classroom-techniques-utilizing-youtube-effectively/"><u>[Updated] Innovative Classroom Techniques  Utilizing YouTube Effectively</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-the-prime-mac-screen-capture-options-for-2024/"><u>[Updated] The Prime Mac Screen Capture Options for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-voice-over-techniques-video-production-edition/"><u>[Updated] Voice Over Techniques  Video Production Edition</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-step-by-step-enabling-screen-capture-on-macos/"><u>2024 Approved  Step-by-Step  Enabling Screen Capture on MacOS</u></a></li>
<li><a href="https://windows11.techidaily.com/4-ways-to-check-your-network-adapter-speed-on-windows/"><u>4 Ways to Check Your Network Adapter Speed on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/6-fixes-for-windows-gone-dark-and-unresponsive/"><u>6 Fixes for Windows Gone Dark and Unresponsive</u></a></li>
<li><a href="https://windows11.techidaily.com/a-detailed-guide-turning-off-windows-update-restrictions/"><u>A Detailed Guide: Turning Off Windows Update Restrictions</u></a></li>
<li><a href="https://windows11.techidaily.com/a-short-tale-on-wintoys-unveiling-a-compelling-windows-application/"><u>A Short Tale on 'WinToys': Unveiling a Compelling Windows Application</u></a></li>
<li><a href="https://windows11.techidaily.com/actions-for-correcting-windows-11-0x800f0922-error/"><u>Actions for Correcting Windows 11 0X800F0922 Error</u></a></li>
<li><a href="https://windows11.techidaily.com/add-command-to-windows-11-context-menu-for-file-moves-and-copies/"><u>Add Command to Windows 11 Context Menu for File Moves & Copies</u></a></li>
<li><a href="https://windows11.techidaily.com/adding-comprehensive-firewall-tools-to-windows-11s-menu-bar/"><u>Adding Comprehensive Firewall Tools to Windows 11’S Menu Bar</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/advantages-and-disadvantages-a-comprehensive-guide-to-using-pidgin-im/"><u>Advantages and Disadvantages: A Comprehensive Guide to Using Pidgin IM</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/anime-inspired-valkyrie-vind-sl125-a-review-of-style-vs-substance-performance/"><u>Anime-Inspired Valkyrie Vind SL125 - A Review of Style Vs. Substance Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/avoidance-of-memory-limitations-strategies-for-windows/"><u>Avoidance of Memory Limitations: Strategies for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/awaken-slumbering-screens-remedy-key-mouse-woes-on-windows/"><u>Awaken Slumbering Screens: Remedy Key, Mouse Woes on Windows</u></a></li>
<li><a href="https://extra-resources.techidaily.com/best-compact-cameras-for-1000-or-less-4k/"><u>Best Compact Cameras for $1000 or Less (4K)</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-winos-stop-autominize-apps/"><u>Boosting WinOS: Stop Autominize Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-xbox-game-pass-error-on-latest-windows-pcs/"><u>Bypassing Xbox Game Pass Error on Latest Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-windows-11s-directive-non-empty-problem-0x80070091/"><u>Clearing Up Windows 11'S Directive Non-Empty Problem #0X80070091</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-common-downloads-dilemmas-on-windows-pcs/"><u>Combatting Common Downloads Dilemmas on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/command-center-for-direct-access-to-windows-11s-appsfolders/"><u>Command Center for Direct Access to Windows 11'S AppsFolders</u></a></li>
<li><a href="https://windows11.techidaily.com/control-windows-11s-emphasis-and-search-highlight/"><u>Control Windows 11'S Emphasis and Search Highlight</u></a></li>
<li><a href="https://windows11.techidaily.com/countering-compromised-windows-defender-on-win-11/"><u>Countering Compromised Windows Defender on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-unique-room-backgrounds-with-windows-spotlight-pics/"><u>Crafting Unique Room Backgrounds with Windows Spotlight Pics</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-pc-audio-with-windows-11s-volume-mixer-tutorial/"><u>Customize PC Audio with Windows 11'S Volume Mixer Tutorial</u></a></li>
<li><a href="https://windows11.techidaily.com/decode-and-resolve-uninitialized-disk-message-on-pc/"><u>Decode and Resolve Uninitialized Disk Message on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-bsod-0x0000003b-and-resolution-steps-in-windows-os/"><u>Decoding BSOD -0X0000003B & Resolution Steps in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/delving-into-windows-tools-chkdsk-sfc-and-disms-functions/"><u>Delving Into Windows Tools: CHKDSK, SFC & DISM's Functions</u></a></li>
<li><a href="https://windows11.techidaily.com/diagnosing-and-repairing-dormant-window-control/"><u>Diagnosing and Repairing Dormant Window Control</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-fatal-component-error-in-win10win11-system/"><u>Disabling Fatal Component Error in Win10/Win11 System</u></a></li>
<li><a href="https://windows11.techidaily.com/1719271997711-enable-high-contrast-mode-go-to-ease-of-access-settings-and-enable-high-contrast-mode-if-it-improves-visibility/"><u>Enable High Contrast Mode: Go to 'Ease of Access' Settings and Enable High Contrast Mode if It Improves Visibility.</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-hdr-rating-does-aurora-deliver-quality/"><u>In 2024, HDR Rating  Does Aurora Deliver Quality?</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-your-samsung-galaxy-a24-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>In 2024, How to Mirror Your Samsung Galaxy A24 Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-music-from-vivo-v29-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Music from Vivo V29 to iPod | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-unlock-channels-success-key-equipment-insights/"><u>In 2024, Unlock Channels Success  Key Equipment Insights</u></a></li>
<li><a href="https://extra-hints.techidaily.com/installation-how-to-for-moviemaker-6-on-pcs/"><u>Installation How-To for Moviemaker 6 on PCs</u></a></li>
<li><a href="https://win-dash.techidaily.com/quick-and-easy-installation-of-amd-vega-graphics-card-drivers-gamers-guide/"><u>Quick and Easy Installation of AMD Vega Graphics Card Drivers: Gamer's Guide</u></a></li>
<li><a href="https://driver-install.techidaily.com/the-art-of-keeping-your-msi-system-at-peak-performance/"><u>The Art of Keeping Your MSI System at Peak Performance</u></a></li>
<li><a href="https://win-dash.techidaily.com/the-ultimate-solution-to-download-and-install-correctly-updated-hp-elitebook-8460p-drivers-on-windows-systems/"><u>The Ultimate Solution to Download & Install Correctly Updated HP Elitebook 8460P Drivers on Windows Systems</u></a></li>
<li><a href="https://change-location.techidaily.com/ultimate-guide-to-get-the-meltan-box-pokemon-go-for-vivo-x-flip-drfone-by-drfone-virtual-android/"><u>Ultimate guide to get the meltan box pokemon go For Vivo X Flip | Dr.fone</u></a></li>
</ul></div>
