---
title: Restoring Microsoft Store Programs on Windows 10/11 Systems
date: 2024-08-15T16:10:38.111Z
updated: 2024-08-16T16:10:38.111Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Microsoft Store Programs on Windows 10/11 Systems
excerpt: This Article Describes Restoring Microsoft Store Programs on Windows 10/11 Systems
keywords: Win10 Restore MS Store,Reinstalling MS Store,Fix MS Store Error,Repair MS Store Access,Regain Windows Store Functionality,Update Microsoft Apps,Maintain Microsoft Store Compatibility
thumbnail: https://thmb.techidaily.com/605743c45d46920946cf620896ea214cdef6126e457144d63179eeaf5994b016.jpg
---

## Restoring Microsoft Store Programs on Windows 10/11 Systems

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

## How to Re-Register Microsoft Store Apps for Current Users

![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

 If the [Microsoft Store app issue](https://www.makeuseof.com/tag/5-tips-fix-windows-store-app-issues-windows-10/) exists with a specific user account, you don’t need to re-register the app for all the user accounts on your computer. Instead, you can re-register the app only for the current user account.

To re-register Microsoft Store apps for the current user:

1. Press the**Win** key and type "powershell" into the Search bar.
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell console, type the following command and press**Enter** :  
`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
4. Wait for the command to execute and complete. You may see a blue loading graphic.
5. Once done, type**exit** and press**Enter** to close PowerShell.

 During the process, you may see some errors highlighted in red. It is due to PowerShell trying to reinstall existing apps on Windows. So, ignore the error and wait for the process to complete.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600114&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Mac： Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
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
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-tutorial-for-downloading-movie-maker-6-on-windows/"><u>[New] 2024 Approved  Tutorial for Downloading Movie Maker 6 on Windows</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-video-format-mastery-best-practices-for-instagram/"><u>[New] In 2024, Video Format Mastery  Best Practices for Instagram</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-key-elements-impacting-youtube-content-visibility/"><u>[New] Key Elements Impacting YouTube Content Visibility</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ecuring-your-digital-dividends-a-no-ads-youtube-money-manual/"><u>[New] Securing Your Digital Dividends  A No Ads YouTube Money Manual</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-the-essential-guide-adding-and-editing-discord-roles/"><u>[Updated] 2024 Approved  The Essential Guide  Adding and Editing Discord Roles</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-audio-anomalies-essential-rhythm-altering-tools-for-2024/"><u>[Updated] Audio Anomalies  Essential Rhythm Altering Tools for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-complete-critique-unmasking-the-bublcam-360-experience/"><u>[Updated] Complete Critique  Unmasking the Bublcam 360 Experience</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-navigating-account-creation-on-youtube-for-2024/"><u>[Updated] Navigating Account Creation on YouTube for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-error-0x00000709-in-windows/"><u>Addressing Error 0X00000709 in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-techniques-in-windows-photo-editing/"><u>Advanced Techniques in Windows Photo Editing</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-update-issue-the-0x800736cc-method/"><u>Bypassing Windows Update Issue: The 0X800736CC Method</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-ppt-file-saving-challenges-swift-solutions-in-windows-11/"><u>Conquer PPT File Saving Challenges: Swift Solutions in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-bluescreenviews-purpose/"><u>Decoding BlueScreenView's Purpose</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-forgotten-windows-add-ons-and-utilities-in-7-ways/"><u>Enabling Forgotten Windows Add-Ons and Utilities in 7 Ways</u></a></li>
<li><a href="https://windows11.techidaily.com/engagingnotabledarkthemefornotepadwin/"><u>EngagingNotableDarkThemeForNotepadWin</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-system-appearance-with-custom-pointer-design/"><u>Enhancing System Appearance with Custom Pointer Design</u></a></li>
<li><a href="https://windows11.techidaily.com/harnessing-power-using-lav-filters-on-microsoft-windows/"><u>Harnessing Power: Using LAV Filters on Microsoft Windows</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-enable-usb-debugging-on-a-locked-realme-note-50-phone-by-drfone-android/"><u>How To Enable USB Debugging on a Locked Realme Note 50 Phone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-pokemon-go-no-gps-signal-heres-every-possible-solution-on-apple-iphone-13-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, Pokemon Go No GPS Signal? Heres Every Possible Solution On Apple iPhone 13 Pro | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-top-15-augmented-reality-games-like-pokemon-go-to-play-on-honor-magic-6-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Top 15 Augmented Reality Games Like Pokémon GO To Play On Honor Magic 6 Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/journey-to-mastery-original-diablo-basics-explained/"><u>Journey to Mastery: Original Diablo Basics Explained</u></a></li>
<li><a href="https://buynow-info.techidaily.com/navigating-cities-swiftly-on-a-gotrax-gxl-v2-a-thorough-performance-assessment/"><u>Navigating Cities Swiftly on a Gotrax GXL V2 - A Thorough Performance Assessment</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-installation-of-intel-wi-fi-drivers/"><u>Navigating the Installation of Intel Wi-Fi Drivers</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-1011s-auto-restart-settings/"><u>Navigating Windows 10/11'S Auto-Restart Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/overcome-apex-crashes-essential-steps-for-windows-11-gamers/"><u>Overcome Apex Crashes: Essential Steps for Windows 11 Gamers</u></a></li>
<li><a href="https://windows11.techidaily.com/prevent-chrome-from-saving-webp-images-in-windows/"><u>Prevent Chrome From Saving WebP Images in Windows</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/recorders-unite-compete-in-2024/"><u>Recorders Unite, Compete, In 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/securely-accessing-power-user-terminal/"><u>Securely Accessing Power-User Terminal</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-the-nullzero-error-fixes-for-new-users-on-win11/"><u>Stop the Null/Zero Error: Fixes for New Users on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-for-installing-unverified-windows-drivers/"><u>Tactics for Installing Unverified Windows Drivers</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/the-essential-guide-to-advanced-youtube-studio-editing/"><u>The Essential Guide to Advanced YouTube Studio Editing</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-techniques-boosting-your-virtual-memory-in-windows-11/"><u>The Essential Techniques: Boosting Your Virtual Memory in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-shortcut-pathways-for-windows-starters/"><u>The Shortcut Pathways for Windows Starters</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-writing-enhancers-for-your-windows-desktop/"><u>Top 5 Writing Enhancers for Your Windows Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-failed-zip-file-extraction-in-windows-11/"><u>Troubleshooting Failed: Zip File Extraction in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-enhancing-pen-device-performance-on-windows/"><u>Troubleshooting: Enhancing Pen Device Performance on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-efficiency-folders-and-files-converge-in-win-11/"><u>Unlocking Efficiency: Folders & Files Converge in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-quick-access-shortcuts-adjacent-to-power-in-win11/"><u>Unveiling Quick Access: Shortcuts Adjacent to Power in Win11</u></a></li>
</ul></div>
