---
title: Deciphering & Remedying WINS Error Messages
date: 2024-08-15T15:12:11.352Z
updated: 2024-08-16T15:12:11.352Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Deciphering & Remedying WINS Error Messages
excerpt: This Article Describes Deciphering & Remedying WINS Error Messages
keywords: Fixing WINS Issues,Solving WINS Errors,Understanding WINS Errors,Resolve WINS Failures,Tackling WINS Problems,Explaining WINS Messages,Mitigating WINS Fails
thumbnail: https://thmb.techidaily.com/1285640821abadae64475db5187a42bfa0d643a297eba82ebbb288218a3b2d87.jpg
---

## Deciphering & Remedying WINS Error Messages

 Windows Security incorporates the Microsoft Defender antivirus utility. However, some users can’t select to run Microsoft Defender scans because of an error message that says: “Unexpected error. Sorry, we ran into a problem.” That “Unexpected error” message pops up for some users when they select the**Virus & threat protection** tab in Windows Security.

 Consequently, the**Virus and threat protection tab** is inaccessible. That error means there’s an issue with the Windows antivirus tool. This is how you can resolve the “Unexpected error” issue.

## 1\. Check for New Windows Updates

 First, check for and install available Windows patch updates. Microsoft releases many patches to update Microsoft Defender. So, a patch update could feasibly resolve a Windows Security bug. Our [guide to manually updating Windows](https://www.makeuseof.com/update-windows-manually/#:~:text=Press%20the%20Win%20%2B%20I%20hotkeys,the%20Check%20for%20updates%20button.) tells you how to check for and install new updates in Settings.

![The Reset option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-option.jpg)

## 2\. Run System File and Image Scans

 System file issues might be causing the “Unexpected error” on your PC. To check if that’s the case, run a System File Checker scan within the Command Prompt. Such a scan will repair the corrupted system files detected. Our guide on [utilizing the SFC tool on Windows](https://www.makeuseof.com/system-file-checker-sfc-windows/) tells you how to scan system files with that utility.

![The SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-sfc-scannow-command.jpg)
<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->

 It’s also recommended to run a Deployment Image Servicing and Management scan, which can resolve Windows system image issues. The System File Checker tool doesn’t work when there are issues with the system image. So, try executing this command before the SFC scan as well:

`Dism /Online /Cleanup-Image /RestoreHealth`

## 3\. Remove Third-Party Antivirus Software

 Do you have an alternative third-party antivirus tool installed on your PC? If so, then there’s a possibility that antivirus software is causing the issue by conflicting with Microsoft Defender. At least try turning off the third-party AV utility by right-clicking the system tray icon for the app and selecting a disable context menu setting.

 If disabling the third-party antivirus software works, you have two options. You can re-enable that antivirus software and utilize the alternative antivirus scanner it provides. Or you can completely uninstall the third-party antivirus software if you prefer Microsoft Defender. Our guide to removing Windows software includes numerous methods for uninstalling programs.

## 4\. Modify the Windows Defender Registry Key

 This registry tweak for modifying a**DisableAntiSpyware** DWORD is one of the most widely confirmed fixes for the “Unexpected error” issue. So, maybe this could the “Unexpected error” solution you’re looking for as well. To apply this potential fix, edit the registry as follows:

1. Open Run, input**regedit** , and click**OK** .
2. Erase the current registry path and input this registry key location inside the address box:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender`
3. You can skip through to step five if the Windows Defender key includes a**DisableAntiSpyware** DWORD. However, users who can’t see that DWORD will need to right-click the**Windows Defender** key and select**New** \>**DWORD** .  
![The New and Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-new-key-options.jpg)
<!-- affiliate ads begin -->
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Type**DisableAntiSpyware** in the DWORD’s text box.
5. Double-click the**DisableAntiSpyware** DWORD to access its**Value** box.
6. Input**0** in the data box if that’s not the current value set.  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-edit-dword-window.jpg)
7. Select**OK** to confirm the value for the DWORD.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Reset the Windows Security App

 Resetting Windows Security is worth trying whenever that app isn’t working right. In this case, something is up with the antivirus component of that app. You can reset that app within Settings or by executing a PowerShell command. Our article about [resetting Windows Security](https://www.makeuseof.com/windows-11-reset-windows-security/) tells you how to apply this potential resolution in three different ways.

![The Reset option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-option.jpg)
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Run a Malwarebytes Scan

 The “Unexpected error” can sometimes be caused by malware targeting Windows Security. Yet, users can’t purge malware with Windows Security because of the error. So, try running a scan with the freeware Malwarebytes version. Some users have said utilizing that software helped them resolve the “Unexpected error” issue. This is how you can run a Malwarebytes scan:

1. Open the [Malwarebytes](https://www.anrdoezrs.net/links/7251228/type/dlg/sid/UUmuoUeUpU2024249/https://www.malwarebytes.com/) website.
2. Click the**Free Download** button.
3. Activate Explorer by holding the**Windows** logo key and pressing**E** .
4. Go to the folder location containing the Malwarebytes setup file.
5. Double-click the**MBSetup.exe** file.
6. Click**Install** to add Malwarebytes to a default directory path.  
![The Install button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-button-for-malwarebytes.jpg)
7. Select**Me or my family** (for personal use) at the production selection step and click**Next** .
8. Click**Skip this for now** if you prefer not to install the additional Malwarebytes Browser Guard software.  
![The Skip this for now option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/skip-this-for-now-option.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
9. Select**Done** to finish.
10. Malwarebytes will then open automatically. Select**Get started** \>**Maybe later** within the Malwarebytes window.
11. Click**Get started** again.
12. Select Malwarebytes’**Scan** option.  
![The Scan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/scan-option.jpg)
13. Press the**Quarantine** button after the scan.

 If this potential resolution works, you can keep Malwarebytes installed for manual scanning. It’s a 14-day trial of the Premium version, and the real-time protection will only last a couple of weeks. However, you can disable the Malwarebytes protection to ensure it doesn’t conflict with Microsoft Defender by right-clicking the utility’s system tray icon and deselecting the**Malware** ,**Ransomware** ,**Exploit** , and**Web Protection** options.

 The Microsoft Safety Scanner is an alternative to Malwarebytes you can run a malware scan with as well. However, that’s only a temporary scanning utility that expires after 10 days. You can download that utility from this [Microsoft page](https://learn.microsoft.com/en-us/microsoft-365/security/intelligence/safety-scanner-download?view=o365-worldwide) . Check out [our Microsoft Safety Scanner guide](https://www.makeuseof.com/microsoft-safety-scanner-guide/) for details about to purge malware with that tool.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->
## 7\. Check the "Turn Off Microsoft Defender Antivirus" Group Policy Setting

 If you’re a Windows Pro or Enterprise user, check that the the**Turn Off Microsoft Defender Antivirus** policy isn’t enabled in Group Policy. You can check that policy in the following steps:

1. [Open Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) by pressing the**Windows** logo +**S** hotkey, entering**gpedit.msc** in the search box, and selecting the**gpedit.msc** result.
2. Then navigate to this policy location in Group Policy’s sidebar:  
`Computer Configuration\Administrative Templates\Windows Components\Microsoft Defender Antivirus`
3. Next, double-click**Turn Off Microsoft Defender Antivirus** to check that policy.  
![The Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/microsoft-defender-antivirus-policy-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4708689&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Win： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
4. Click**Not Configured** if that policy is set to**Enabled** .  
![The Turn Off Microsoft Defender Antivirus policy window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/turn-off-microsoft-defender-antivirus.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Select the policy’s**Apply** and**OK** options.

## 8\. Reset Windows or Perform an In-Place Upgrade

 Resetting Windows is a troubleshooting method that restores the platform to a default (factory) configuration. The Reset this PC tool gives you a simple way to reinstall the platform and preserve user files, but you’ll need to reinstall apps.

[Applying a Windows reset](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) might resolve some deeper system issues causing the “Unexpected error” issue. However, it’s only advised to do so if none of the other potential solutions suggested here work.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-this-pc-tool.jpg)

 An in-place upgrade is an alternative troubleshooting method to resetting Windows. Performing an in-place upgrade will reinstall Windows by installing the latest build version. So, it’s like a reset, but the advantage is that an in-place upgrade preserves the apps you’ve installed. This guide to [performing an in-place upgrade on Windows](https://www.makeuseof.com/in-place-upgrade-windows-11/) provides full instructions for upgrading Windows 11 in such a way.

 However, you could feasibly upgrade to a new Windows version via Settings. Open**Windows Update** in the Settings app to see if there’s a version upgrade available. If so, select to upgrade to the latest Windows build from there.

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Run a Scan With Windows Security Again

 You’ll probably be able to access the antivirus-scanning options in Windows Security again after applying the potential solutions covered here. So, try applying all those potential “Unexpected error” resolutions in the order specified to find one that works on your Windows PC. You can also contact the [Microsoft Windows support service](https://support.microsoft.com/en-us/home/contact?SourceApp=smc2&ContactUsExperienceEntryPointAssetId=Google) for further assistance but give the potential fixes outlined here a try first.

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
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-learn-to-download-discord-videos-without-cost-on-all-devices/"><u>[New] 2024 Approved  Learn to Download Discord Videos Without Cost on All Devices</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-find-your-fit-understanding-basic-to-pro-plans-at-vimeo-for-2024/"><u>[New] Find Your Fit  Understanding Basic to Pro Plans at Vimeo for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-ensuring-your-shorts-videos-thumbnail-shows-up/"><u>[New] In 2024, Ensuring Your Shorts Video's Thumbnail Shows Up</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-navigating-instagram-marketing-ultimate-guide-to-video-success-for-2024/"><u>[New] Navigating Instagram Marketing  Ultimate Guide to Video Success for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-seamlessly-sharing-your-style-macootd-tiktoks/"><u>[Updated] In 2024, Seamlessly Sharing Your Style  MacOOTD TikToks</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-instant-insight-into-colour-difference-filming-methods/"><u>[Updated] Instant Insight Into Colour Difference Filming Methods</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-unveiling-the-secrets-of-auto-played-youtube-content-on-facebook-platform/"><u>[Updated] Unveiling the Secrets of Auto-Played YouTube Content on Facebook Platform</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-infographic-insights-small-business-video-mastery/"><u>2024 Approved  Infographic Insights  Small Business Video Mastery</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-top-10-shopping-sites-for-customized-gift-boxes-find-the-perfect-personalized-present/"><u>2024 Approved  Top 10 Shopping Sites for Customized Gift Boxes - Find the Perfect Personalized Present</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-you-when-your-realme-11-proplus-is-off-drfone-by-drfone-virtual-android/"><u>Can Life360 Track You When Your Realme 11 Pro+ is off? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-access-denied-and-restricted-access-issues-windows-office-solution/"><u>Fixing 'Access Denied' And Restricted Access Issues: Windows Office Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-color-discrepancies-on-microsoft-windows/"><u>Fixing Color Discrepancies on Microsoft Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/get-your-data-fast-onedrive-without-web-connection/"><u>Get Your Data Fast: OneDrive, Without Web Connection</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-through-setting-up-and-adjusting-net-settings/"><u>Guide Through Setting Up and Adjusting Net Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-fix-invalid-label-alert-in-win11/"><u>Guide to Fix Invalid Label Alert in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-silencing-folder-views-in-windows-11/"><u>Guide to Silencing Folder Views in Windows 11</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-without-jailbreak-on-motorola-g24-power-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location without Jailbreak On Motorola G24 Power | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-get-excel-data-displayed-in-notepad/"><u>How To Get Excel Data Displayed in Notepad</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-mend-the-dxgi-error-in-win-11-os/"><u>How to Mend the DXGI Error in Win 11 OS</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-update-iphone-15-to-the-latest-ios-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update iPhone 15 to the Latest iOS Version? | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-instagram-desktop-tips-for-effortless-video-posts/"><u>In 2024, Instagram Desktop Tips for Effortless Video Posts</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-picture-perfect-creating-screenshots-in-windows/"><u>In 2024, Picture Perfect  Creating Screenshots in Windows</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-swinging-sparrow-suites/"><u>In 2024, Swinging Sparrow Suites</u></a></li>
<li><a href="https://windows11.techidaily.com/insight-into-windows-canary-vulnerability-monitoring/"><u>Insight Into Windows' Canary Vulnerability Monitoring</u></a></li>
<li><a href="https://windows11.techidaily.com/manipulating-image-summary-dimensions-w11/"><u>Manipulating Image Summary Dimensions W11</u></a></li>
<li><a href="https://windows11.techidaily.com/minimizing-resource-waste-during-device-integration-on-windows/"><u>Minimizing Resource Waste During Device Integration on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-win11-with-ease-mastering-package-control-using-wingetui/"><u>Navigate Win11 with Ease: Mastering Package Control Using WingetUI</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-cropping-and-resizing-images-in-final-cut-pro-x-made-easy-for-2024/"><u>New Cropping and Resizing Images in Final Cut Pro X Made Easy for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/outsmart-your-pcs-bluescreen-adopting-win11s-best-practices/"><u>Outsmart Your PC's Bluescreen: Adopting Win11's Best Practices</u></a></li>
<li><a href="https://windows11.techidaily.com/perfect-speech-capture-on-a-windows-device/"><u>Perfect Speech Capture on a Windows Device</u></a></li>
<li><a href="https://windows11.techidaily.com/precision-tools-for-program-harmony-on-pc/"><u>Precision Tools for Program Harmony on PC</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-tutorial-on-creating-homemade-projector-screens/"><u>Step-by-Step Tutorial on Creating Homemade Projector Screens</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-solve-chrome-not-saving-or-uploading-issues-on-windows/"><u>Steps to Solve Chrome Not Saving or Uploading Issues on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-rescuing-non-transferring-usbs-in-windows/"><u>Strategies for Rescuing Non-Transferring USBs in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-shifting-windows-taskbar-a-historical-view/"><u>The Shifting Windows Taskbar: A Historical View</u></a></li>
<li><a href="https://vp-tips.techidaily.com/transcribe-speaking-to-writing-free-of-charge-for-2024/"><u>Transcribe Speaking to Writing  Free of Charge for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-unseen-hdd-in-windows/"><u>Troubleshooting Unseen HDD in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-full-potential-of-win11-with-command-shortcuts/"><u>Unlock the Full Potential of Win11 with Command Shortcuts</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-typing-potential-essentials-for-crafting-shortcuts-in-the-latest-windows-version/"><u>Unlock Typing Potential: Essentials for Crafting Shortcuts in the Latest Windows Version</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-efficiency-9-gains-from-the-newest-outlook-update/"><u>Unlocking Efficiency: 9 Gains From the Newest Outlook Update</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unlocking-secrets-to-triumph-over-the-beastly-lynels-in-links-epic-quest/"><u>Unlocking Secrets to Triumph over The Beastly Lynels in Link's Epic Quest</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-invisible-windows-methods-to-bring-them-back-in-win10win11/"><u>Unveiling Invisible Windows: Methods to Bring Them Back in Win10/Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-steps-to-fix-rockalldlldll-not-found-error/"><u>Unveiling Steps to Fix 'Rockalldll.dll Not Found Error'</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-top-7-pencil-powerhouses-for-windows-creators/"><u>Unveiling the Top 7 Pencil Powerhouses for Windows Creators</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-with-virtualbox-deps-before-the-big-setup/"><u>Winning with VirtualBox: Deps Before the Big Setup</u></a></li>
</ul></div>
