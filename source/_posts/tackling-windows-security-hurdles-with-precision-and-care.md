---
title: Tackling Windows Security Hurdles with Precision & Care
date: 2024-08-22T21:36:00.224Z
updated: 2024-08-23T21:36:00.224Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling Windows Security Hurdles with Precision & Care
excerpt: This Article Describes Tackling Windows Security Hurdles with Precision & Care
keywords: Precision Windows Secure,Tackle Windows Safety,Security Windows Guard,Precise Windows Protect,Windows Hurdles Safeguard,Careful Window Defense,Secure Windows Strategy
thumbnail: https://thmb.techidaily.com/f60b5cb5d31f0db6c00b1faa5bbb82ce655e5c5fa0350104266b8258e603ad98.png
---

## Tackling Windows Security Hurdles with Precision & Care

 Windows Security incorporates the Microsoft Defender antivirus utility. However, some users can’t select to run Microsoft Defender scans because of an error message that says: “Unexpected error. Sorry, we ran into a problem.” That “Unexpected error” message pops up for some users when they select the**Virus & threat protection** tab in Windows Security.

 Consequently, the**Virus and threat protection tab** is inaccessible. That error means there’s an issue with the Windows antivirus tool. This is how you can resolve the “Unexpected error” issue.

## 1\. Check for New Windows Updates

 First, check for and install available Windows patch updates. Microsoft releases many patches to update Microsoft Defender. So, a patch update could feasibly resolve a Windows Security bug. Our[guide to manually updating Windows](https://www.makeuseof.com/update-windows-manually/#:~:text=Press%20the%20Win%20%2B%20I%20hotkeys,the%20Check%20for%20updates%20button.) tells you how to check for and install new updates in Settings.

![The Reset option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-option.jpg)

## 2\. Run System File and Image Scans

 System file issues might be causing the “Unexpected error” on your PC. To check if that’s the case, run a System File Checker scan within the Command Prompt. Such a scan will repair the corrupted system files detected. Our guide on[utilizing the SFC tool on Windows](https://www.makeuseof.com/system-file-checker-sfc-windows/) tells you how to scan system files with that utility.

![The SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-sfc-scannow-command.jpg)

 It’s also recommended to run a Deployment Image Servicing and Management scan, which can resolve Windows system image issues. The System File Checker tool doesn’t work when there are issues with the system image. So, try executing this command before the SFC scan as well:

`Dism /Online /Cleanup-Image /RestoreHealth`

## 3\. Remove Third-Party Antivirus Software

 Do you have an alternative third-party antivirus tool installed on your PC? If so, then there’s a possibility that antivirus software is causing the issue by conflicting with Microsoft Defender. At least try turning off the third-party AV utility by right-clicking the system tray icon for the app and selecting a disable context menu setting.

 If disabling the third-party antivirus software works, you have two options. You can re-enable that antivirus software and utilize the alternative antivirus scanner it provides. Or you can completely uninstall the third-party antivirus software if you prefer Microsoft Defender. Our guide to removing Windows software includes numerous methods for uninstalling programs.

<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Modify the Windows Defender Registry Key

 This registry tweak for modifying a**DisableAntiSpyware** DWORD is one of the most widely confirmed fixes for the “Unexpected error” issue. So, maybe this could the “Unexpected error” solution you’re looking for as well. To apply this potential fix, edit the registry as follows:

1. Open Run, input**regedit** , and click**OK** .
2. Erase the current registry path and input this registry key location inside the address box:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender`
3. You can skip through to step five if the Windows Defender key includes a**DisableAntiSpyware** DWORD. However, users who can’t see that DWORD will need to right-click the**Windows Defender** key and select**New** \>**DWORD** .  
![The New and Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-new-key-options.jpg)
4. Type**DisableAntiSpyware** in the DWORD’s text box.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
5. Double-click the**DisableAntiSpyware** DWORD to access its**Value** box.
6. Input**0** in the data box if that’s not the current value set.  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-edit-dword-window.jpg)
7. Select**OK** to confirm the value for the DWORD.
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Reset the Windows Security App

 Resetting Windows Security is worth trying whenever that app isn’t working right. In this case, something is up with the antivirus component of that app. You can reset that app within Settings or by executing a PowerShell command. Our article about[resetting Windows Security](https://www.makeuseof.com/windows-11-reset-windows-security/) tells you how to apply this potential resolution in three different ways.

![The Reset option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-option.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
## 6\. Run a Malwarebytes Scan

 The “Unexpected error” can sometimes be caused by malware targeting Windows Security. Yet, users can’t purge malware with Windows Security because of the error. So, try running a scan with the freeware Malwarebytes version. Some users have said utilizing that software helped them resolve the “Unexpected error” issue. This is how you can run a Malwarebytes scan:

1. Open the[Malwarebytes](https://www.anrdoezrs.net/links/7251228/type/dlg/sid/UUmuoUeUpU2024249/https://www.malwarebytes.com/) website.
2. Click the**Free Download** button.
3. Activate Explorer by holding the**Windows** logo key and pressing**E** .
4. Go to the folder location containing the Malwarebytes setup file.
5. Double-click the**MBSetup.exe** file.
6. Click**Install** to add Malwarebytes to a default directory path.  
![The Install button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-button-for-malwarebytes.jpg)
7. Select**Me or my family** (for personal use) at the production selection step and click**Next** .
8. Click**Skip this for now** if you prefer not to install the additional Malwarebytes Browser Guard software.  
![The Skip this for now option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/skip-this-for-now-option.jpg)
9. Select**Done** to finish.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
10. Malwarebytes will then open automatically. Select**Get started** \>**Maybe later** within the Malwarebytes window.
11. Click**Get started** again.
12. Select Malwarebytes’**Scan** option.  
![The Scan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/scan-option.jpg)
13. Press the**Quarantine** button after the scan.
<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If this potential resolution works, you can keep Malwarebytes installed for manual scanning. It’s a 14-day trial of the Premium version, and the real-time protection will only last a couple of weeks. However, you can disable the Malwarebytes protection to ensure it doesn’t conflict with Microsoft Defender by right-clicking the utility’s system tray icon and deselecting the**Malware** ,**Ransomware** ,**Exploit** , and**Web Protection** options.

 The Microsoft Safety Scanner is an alternative to Malwarebytes you can run a malware scan with as well. However, that’s only a temporary scanning utility that expires after 10 days. You can download that utility from this[Microsoft page](https://learn.microsoft.com/en-us/microsoft-365/security/intelligence/safety-scanner-download?view=o365-worldwide) . Check out[our Microsoft Safety Scanner guide](https://www.makeuseof.com/microsoft-safety-scanner-guide/) for details about to purge malware with that tool.

## 7\. Check the "Turn Off Microsoft Defender Antivirus" Group Policy Setting

 If you’re a Windows Pro or Enterprise user, check that the the**Turn Off Microsoft Defender Antivirus** policy isn’t enabled in Group Policy. You can check that policy in the following steps:

1. [Open Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) by pressing the**Windows** logo +**S** hotkey, entering**gpedit.msc** in the search box, and selecting the**gpedit.msc** result.
2. Then navigate to this policy location in Group Policy’s sidebar:  
`Computer Configuration\Administrative Templates\Windows Components\Microsoft Defender Antivirus`
3. Next, double-click**Turn Off Microsoft Defender Antivirus** to check that policy.  
![The Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/microsoft-defender-antivirus-policy-settings.jpg)
4. Click**Not Configured** if that policy is set to**Enabled** .  
![The Turn Off Microsoft Defender Antivirus policy window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/turn-off-microsoft-defender-antivirus.jpg)
5. Select the policy’s**Apply** and**OK** options.

## 8\. Reset Windows or Perform an In-Place Upgrade

 Resetting Windows is a troubleshooting method that restores the platform to a default (factory) configuration. The Reset this PC tool gives you a simple way to reinstall the platform and preserve user files, but you’ll need to reinstall apps.

[Applying a Windows reset](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) might resolve some deeper system issues causing the “Unexpected error” issue. However, it’s only advised to do so if none of the other potential solutions suggested here work.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-this-pc-tool.jpg)

 An in-place upgrade is an alternative troubleshooting method to resetting Windows. Performing an in-place upgrade will reinstall Windows by installing the latest build version. So, it’s like a reset, but the advantage is that an in-place upgrade preserves the apps you’ve installed. This guide to[performing an in-place upgrade on Windows](https://www.makeuseof.com/in-place-upgrade-windows-11/) provides full instructions for upgrading Windows 11 in such a way.

 However, you could feasibly upgrade to a new Windows version via Settings. Open**Windows Update** in the Settings app to see if there’s a version upgrade available. If so, select to upgrade to the latest Windows build from there.

## Run a Scan With Windows Security Again

 You’ll probably be able to access the antivirus-scanning options in Windows Security again after applying the potential solutions covered here. So, try applying all those potential “Unexpected error” resolutions in the order specified to find one that works on your Windows PC. You can also contact the[Microsoft Windows support service](https://support.microsoft.com/en-us/home/contact?SourceApp=smc2&ContactUsExperienceEntryPointAssetId=Google) for further assistance but give the potential fixes outlined here a try first.

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
<li><a href="https://extra-lessons.techidaily.com/new-audio-accentuation-tunes-for-visual-projects/"><u>[New] Audio Accentuation  Tunes for Visual Projects</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-mastering-pip-views-on-chrome-across-devices/"><u>[New] Mastering PIP Views on Chrome Across Devices</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-mastering-the-art-of-hash-tracking-top-apps-reviewed-fbtwitterinsta/"><u>[Updated] 2024 Approved  Mastering the Art of Hash Tracking  Top Apps Reviewed (FB/Twitter/Insta)</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-in-2024-boost-your-pc-editing-game-with-inshot-techniques/"><u>[Updated] In 2024, Boost Your PC Editing Game with Inshot Techniques</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-stream-and-save-discover-the-top-5-recorders-of-live-conferences-for-2024/"><u>[Updated] Stream and Save - Discover The Top 5 Recorders of Live Conferences for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/4-ways-to-transfer-music-from-vivo-v27-pro-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>4 Ways to Transfer Music from Vivo V27 Pro to iPhone | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/does-find-my-friends-work-on-samsung-galaxy-a15-4g-drfone-by-drfone-virtual-android/"><u>Does find my friends work on Samsung Galaxy A15 4G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-steps-for-resolving-printer-connections-in-windows/"><u>Essential Steps for Resolving Printer Connections in Windows</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/factory-reset-iphone-12-mini-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>Factory Reset iPhone 12 mini | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/file-explorer-misses-out-on-sd-card-heres-fixing-it/"><u>File Explorer Misses Out on SD Card - Here's Fixing It</u></a></li>
<li><a href="https://data-wizards.techidaily.com/fixing-avchd-file-disruptions/"><u>Fixing AVCHD File Disruptions</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-bypass-android-lock-screen-using-emergency-call-on-poco-x5-pro-by-drfone-android/"><u>How to Bypass Android Lock Screen Using Emergency Call On Poco X5 Pro?</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-bypass-icloud-by-checkra1n-even-on-apple-iphone-8-plus-if-youve-tried-everything-by-drfone-ios/"><u>How To Bypass iCloud By Checkra1n Even On Apple iPhone 8 Plus If Youve Tried Everything</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-dodge-perpetual-network-logon-errors-in-windows/"><u>How to Dodge Perpetual Network Logon Errors in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-overcome-invalid-session-from-vac-steam-alert/"><u>How To Overcome Invalid Session From VAC Steam Alert</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-6s-to-others-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 6s To Others devices? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/identifying-non-essential-windows-11-functions-to-turn-off/"><u>Identifying Non-Essential Windows 11 Functions to Turn Off</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-a-perfect-guide-to-remove-or-disable-google-smart-lock-on-oppo-reno-8t-5g-by-drfone-android/"><u>In 2024, A Perfect Guide To Remove or Disable Google Smart Lock On Oppo Reno 8T 5G</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-your-infinix-gt-10-pro-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Your Infinix GT 10 Pro Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-use-pokemon-go-joystick-on-poco-x5-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Pokemon Go Joystick on Poco X5 Pro? | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-top-notch-solutions-for-disabled-apple-id-on-apple-iphone-11-making-it-possible-by-drfone-ios/"><u>In 2024, Top-Notch Solutions for Disabled Apple ID On Apple iPhone 11 Making It Possible</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-use-of-microsoft-family-safety/"><u>Mastering the Use of Microsoft Family Safety</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/obs-studio-guide-5-key-edits-for-flawless-results/"><u>OBS Studio Guide  5 Key Edits for Flawless Results</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-cpu-performance-with-solutions-for-tiworkerexe-use/"><u>Optimize CPU Performance with Solutions for TiWorker.exe Use</u></a></li>
<li><a href="https://windows11.techidaily.com/real-time-speech-conversion-using-whisper-desktop/"><u>Real-Time Speech Conversion: Using Whisper Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/reawakening-windows-hibernate-a-practical-guide/"><u>Reawakening Windows Hibernate: A Practical Guide</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/rectified-graphical-glitch-nvidia-leads-the-way/"><u>Rectified Graphical Glitch - NVIDIA Leads the Way</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-sound-error-error-0xc00d36b4-in-win11/"><u>Rectifying Sound Error: Error 0XC00D36B4 in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/reducing-the-overwhelming-impact-of-ntoskrnlexe/"><u>Reducing the Overwhelming Impact of Ntoskrnl.exe</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstating-hidden-pane-windows-6-procedures-in-win11/"><u>Reinstating Hidden Pane Windows: 6 Procedures in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/repairing-filesystem-issues-with-ease-on-windows-11/"><u>Repairing Filesystem Issues with Ease on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-order-7-solutions-for-lost-windows-server-time/"><u>Restoring Order: 7 Solutions for Lost Windows Server Time</u></a></li>
<li><a href="https://win-answers.techidaily.com/solving-doom-eternal-crashes-effective-troubleshooting-steps/"><u>Solving DOOM Eternal Crashes: Effective Troubleshooting Steps</u></a></li>
<li><a href="https://howto.techidaily.com/spotify-keeps-crashing-a-complete-list-of-fixes-you-can-use-on-xiaomi-13t-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Spotify Keeps Crashing A Complete List of Fixes You Can Use on Xiaomi 13T Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/steering-clear-of-windows-complications-during-amd-setup/"><u>Steering Clear of Windows Complications During AMD Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/surge-speed-settings-preventing-unexpected-download-plunges/"><u>Surge Speed Settings: Preventing Unexpected Download Plunges</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-disable-discord-auto-updates-at-bootup/"><u>Techniques to Disable Discord Auto-Updates at Bootup</u></a></li>
<li><a href="https://windows11.techidaily.com/the-easy-way-out-windows-11s-silencing-methods/"><u>The Easy Way Out: Windows 11'S Silencing Methods</u></a></li>
<li><a href="https://howto.techidaily.com/top-10-fixes-for-phone-keep-disconnecting-from-wi-fi-on-lava-agni-2-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 10 Fixes for Phone Keep Disconnecting from Wi-Fi On Lava Agni 2 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-methods-for-resolving-windows-interface-dispute/"><u>Top 5 Methods for Resolving Windows Interface Dispute</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-common-errors-in-microsoft-office-windows/"><u>Troubleshooting Common Errors in Microsoft Office Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/what-makes-windows-11s-limited-functionality-beneficial/"><u>What Makes Windows 11’S Limited Functionality Beneficial?</u></a></li>
</ul></div>
