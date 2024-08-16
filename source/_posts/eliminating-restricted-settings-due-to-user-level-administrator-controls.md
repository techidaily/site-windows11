---
title: Eliminating Restricted Settings Due to User-Level Administrator Controls
date: 2024-08-15T15:30:53.448Z
updated: 2024-08-16T15:30:53.448Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eliminating Restricted Settings Due to User-Level Administrator Controls
excerpt: This Article Describes Eliminating Restricted Settings Due to User-Level Administrator Controls
keywords: Admin Restriction Removal,Access Override Elimination,User Permissions Adjustment,Inhibiting Admin Limits,User Level Control Abolish,Administrative Privilege Reset,Restricted Settings Lift
thumbnail: https://thmb.techidaily.com/64dd4d70d6e0441ce0215a5b5c562664b1c9c88648a5d01b942d93707afe0dac.jpg
---

## Eliminating Restricted Settings Due to User-Level Administrator Controls

 Some users have reported they can’t set Windows Security options because of an error that says, “This setting is managed by your administrator.” Those users see that error message just above options within the**Virus & threat protection** and**App & browser tabs** of that app. Consequently, they can’t turn on important Windows Security settings there that are grayed out and disabled.

 That issue has little to do with admin rights. Many users who encounter the issue are already utilizing Windows administrator accounts. This is how you can fix the “setting is managed by your administrator” error in Windows 11.

## 1\. Check for and Install Available Windows 11 Updates

 Although not the most likely potential solution, some users have said installing available Windows 11 updates helped them resolve this error. Patchers for Windows 11 usually address Windows bugs reported by users.

 If you're not sure how to do this, visit [how to install Windows 11 updates](https://www.makeuseof.com/windows-11-install-updates/) for a step-by-step guide.

## 2\. Reset the Windows Security and Settings Apps

 Users who’ve fixed the “setting is managed by your administrator” error have confirmed resetting the Windows Security and Settings apps can work. Resetting those apps will clear their data. You can reset Windows Security via Settings, as outlined in our [how to reset apps on Windows](https://www.makeuseof.com/windows-reset-app/) guide.

![The Reset button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reset-option.jpg)

 To reset Settings, you must open the Start menu and right-click the app’s shortcut. Select**App settings** to bring up some troubleshooting options for it. Then select the**Reset** troubleshooting option for the app.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
## 3\. Uninstall Third-Party Antivirus Software

 Some third-party antivirus utilities can disable Windows Security features they effectively replace. If you’ve installed an overlapping third-party antivirus product, uninstalling it may resolve Windows Security’s administrator error. Uninstall antivirus software with a method within our guide on [how to remove Windows programs](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) to see if that resolves the issue.

![The uninstaller tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-uninstaller-tool.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->

 Should this solution work, the issue will likely reoccur if you reinstall the same third-party antivirus virus software. Then you would have to choose between using the third-party antivirus utility or Windows Security.

## 4\. Edit the Registry

 Many users have been able to fix the Windows Security administrator error by applying this confirmed registry solution. This registry tweak involves modifying a DWORD value, but you don’t need to delete any key. To apply this potential resolution, edit the registry like this:

1. Run the Windows Registry Editor app, which you can open with any method included in our [how to open Regedit](https://www.makeuseof.com/windows-11-open-registry-editor/) [g](https://www.makeuseof.com/windows-11-open-registry-editor/) uide.
2. Click inside the address box at the top of Registry Editor and erase the text in it.
3. Input this key path in the registry address bar and press**Return** :  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\DeviceGuard\Scenarios\HypervisorEnforcedCodeIntegrity`
4. Then double-click the**Enabled** DWORD within the**HypervisorEnforcedCodeIntegrity** key.  
![The HypervisorEnforced registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-hypervisor-key.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
5. Clear the**Data value** box, and then input**0** there.
6. Select**OK** to set the**Enabled** DWORD’s value.  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/edit-dword-window.jpg)
7. Exit Registry Editor and click the**Power** \>**Restart** Start menu options.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
<!-- affiliate ads end -->
## 5\. Set Group Policy’s Real-time Protection Settings to "Not Configured"

 A possibility for Windows 11 Pro and Enterprise users to consider is that Group Policy Editor could be blocking changes to Windows Security settings. If you can open Group Policy Editor on your PC, check real-time protection policy settings aren’t enabled there. This is how you can set real-time protection settings to not configured in Group Policy Editor:

1. Find Group Policy Editor by clicking the search magnifying glass icon and inputting**gpedit.msc** .
2. Select**gpedit.msc** to open the Group Policy Editor window.
3. Then select**Computer Configuration** to extend that category.
4. Double-click**Administrative Template** to access several setting categories.
5. Next, double-click**Windows Components** \>**Microsoft Defender Antivirus** \>**Real-time Protection** in the navigation sidebar.  
![The Real-time Protection policy settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-real-time-protection-policy-settings.jpg)
6. Double-click any policy setting that’s with an enabled state.
7. Then select the**Not configured radio** button.  
![The Not Configured radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/not-configured-option.jpg)
8. Click**Apply** \>**OK** in the window to set the change.
9. Repeat the previous three steps for all real-time protection policies set to enabled.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
## 6\. Reinstall Windows Security

 You can’t reinstall Windows Security by uninstalling that app via Settings and downloading it from Microsoft Store. However, you can run a more general PowerShell command that reinstalls all apps pre-installed with Windows 11\. Try reinstalling Windows Security with that command as follows:

1. Open PowerShell with administrative rights. Our guide on [how to open PowerShell](https://www.makeuseof.com/windows-11-powershell-administrator/) includes various methods for opening that app.
2. Then input the following PowerShell command for reinstalling apps:  
`Get-AppXPackage -AllUsers | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reinstall app PowerShell command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reinstall-app-command.jpg)
3. Press**Enter** and wait for the command to finish.
4. Restart your laptop or desktop from the Start menu.

## 7\. Reinstall Windows 11 With the Media Creation Tool

 Reinstalling Windows 11 by downloading an ISO with Media Creation Tool is a drastic potential solution. However, users have confirmed updating Windows 11 in such a way works for fixing this error. Furthermore, you can select to preserve apps and files when reinstalling. This is how to reinstall Windows 11:

1. Download the latest Windows 11 ISO with the Media Creation Tool. Our guide on [how to download a Windows 11 ISO](https://www.makeuseof.com/windows-11-download-iso/) includes step-by-step instructions for how to do so.
2. Then double-click your downloaded Windows 11 ISO file.
3. Click**setup.exe** to open the Windows 11 installer.  
![The Windows 11 Setup window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-setup-window.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
4. Select**Next** to initiate a system check.
5. Press the**Accept** button for the license terms.
6. The**Keep personal files and apps** option will probably be set by default at the ready-to-install stage. However, you click**Change what to keep** to make sure the**Keep personal files and apps** option is selected.  
![The Keep personal files and apps radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/keep-personal-files-option.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->
7. Then select**Next** to proceed to the last step.
8. Click**Install** to reinstall Windows 11.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Change Windows Security’s Settings Again

 Those are the most widely cited ways to fix the “setting is managed by your administrator” error in Windows 11\. So, applying those potential resolutions will probably resolve the “setting is managed by your administrator” issue on your PC. Then you’ll be able to set all the options within Windows Security as required.

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
<li><a href="https://snapchat-videos.techidaily.com/updated-android-plus-mac-save-and-secure-snapchat-videos-for-2024/"><u>[Updated] Android + Mac  Save and Secure Snapchat Videos for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-captivating-content-the-essential-six-video-formats/"><u>[Updated] Captivating Content  The Essential Six Video Formats</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-the-great-screen-capture-debate-obs-studio-versus-fraps/"><u>[Updated] In 2024, The Great Screen Capture Debate  OBS Studio Versus Fraps</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-skype-voice-to-mp3-the-economical-choice/"><u>[Updated] Skype Voice to MP3  The Economical Choice</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-soft-soundscapes-low-profile-alterations-in-garageband/"><u>[Updated] Soft Soundscapes  Low-Profile Alterations in Garageband</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-starting-strong-in-screen-sharpness-your-first-tutorial-on-hd-video-for-2024/"><u>[Updated] Starting Strong in Screen Sharpness  Your First Tutorial on HD Video for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-boosting-speed-for-periscope-live-video/"><u>2024 Approved  Boosting Speed for Periscope Live Video</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-close-out-discord-on-all-devices/"><u>2024 Approved  Close Out Discord on All Devices</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/1721268119691-stellar/"><u>今日中にStellarレーザー治療を始めよう!ステップバイステップガイド</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-stream-anything-from-tecno-spark-20-pro-to-apple-tv-drfone-by-drfone-android/"><u>In 2024, How To Stream Anything From Tecno Spark 20 Pro to Apple TV | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-maximizing-auditory-experience-on-windows-10/"><u>In 2024, Maximizing Auditory Experience on Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/locating-open-tcp-ports-in-windows-os/"><u>Locating Open TCP Ports in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/lockdown-the-background-on-your-modern-windows-11/"><u>Lockdown the Background on Your Modern Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-one-way-outlook-on-safe-windows-mode/"><u>Overcoming One-Way Outlook on Safe Windows Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-challenge-interrupt-exception-in-windows-os/"><u>Overcoming the Challenge: Interrupt Exception in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/peering-inside-windows-11-understanding-its-registry-essence/"><u>Peering Inside Windows 11: Understanding Its Registry Essence</u></a></li>
<li><a href="https://windows11.techidaily.com/personalizing-the-windows-11-task-manager-homepage/"><u>Personalizing the Windows 11 Task Manager Homepage</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-how-to-correct-windows-11s-keyboard-type-trouble-code-0x80049dd3/"><u>Quick Guide: How to Correct Windows 11'S Keyboard Type Trouble (Code: 0X80049DD3)</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-link-loss-in-winvpn-a-step-by-step-solution/"><u>Restoring Link Loss in WinVPN: A Step-By Step Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-heic-files-into-desired-jpegs-on-pc/"><u>Simplifying Heic Files Into Desired JPEGs on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/skyrocket-above-the-100mbps-ethernet-threshold-in-windows/"><u>Skyrocket Above the 100Mbps Ethernet Threshold in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/smooth-save-experience-top-6-strategies-to-tackle-ppt-errors/"><u>Smooth Save Experience: Top 6 Strategies to Tackle PPT Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-to-correcting-winrars-incorrect-file-hashes/"><u>Solutions to Correcting WinRAR's Incorrect File Hashes</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-to-erase-office-365-error-30015-26-on-pcs/"><u>Solutions to Erase Office 365 Error 30015-26 on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resurrect-your-disconnected-controller/"><u>Steps to Resurrect Your Disconnected Controller</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-troublesome-windows-programming-issues-7-ways/"><u>Tackling Troublesome Windows Programming Issues (7 Ways)</u></a></li>
<li><a href="https://techidaily.com/the-easiest-methods-to-hard-reset-oppo-reno-8t-drfone-by-drfone-reset-android-reset-android/"><u>The Easiest Methods to Hard Reset Oppo Reno 8T | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/time-capsule-trick-the-use-of-windows-7-key-for-activating-11/"><u>Time Capsule Trick: The Use of Windows 7 Key for Activating 11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-overcoming-windows-terminal-access-issues/"><u>Troubleshooting: Overcoming Windows Terminal Access Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/tutorial-navigating-to-windows-11-phone-dialer/"><u>Tutorial: Navigating to Windows 11 Phone Dialer</u></a></li>
<li><a href="https://windows11.techidaily.com/uncover-the-magic-of-reading-comics-on-windows-11/"><u>Uncover the Magic of Reading Comics on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-fixing-windows-roblox-code-403-issue/"><u>Understanding & Fixing Windows Roblox Code 403 Issue</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/unlocking-the-power-of-smart-lock-a-beginners-guide-for-realme-narzo-60-pro-5g-users-by-drfone-android/"><u>Unlocking the Power of Smart Lock A Beginners Guide for Realme Narzo 60 Pro 5G Users</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-advanced-techniques-for-blurry-backgrounds-in-w11-photo-feature/"><u>Unveiling Advanced Techniques for Blurry Backgrounds in W11 Photo Feature</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-how-to-reverse-a-tiktok-video-with-ease-an-ultimate-guide-for-2024/"><u>Updated How to Reverse A TikTok Video with Ease An Ultimate Guide for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/visual-illusion-blending-image-and-archive-data-without-notice-win1011/"><u>Visual Illusion: Blending Image and Archive Data without Notice WIN10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-offline-the-essential-manual/"><u>Win11 Offline: The Essential Manual</u></a></li>
</ul></div>
