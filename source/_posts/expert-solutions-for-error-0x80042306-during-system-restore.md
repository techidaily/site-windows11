---
title: Expert Solutions for Error 0X80042306 During System Restore
date: 2024-08-15T15:28:52.402Z
updated: 2024-08-16T15:28:52.402Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Expert Solutions for Error 0X80042306 During System Restore
excerpt: This Article Describes Expert Solutions for Error 0X80042306 During System Restore
keywords: Error Code 0X80042306 Fix,System Restore Issue Resolved,Solve Restore Error 0X80042306,Troubleshoot Windows Error 0X80042306,Correcting Restore Error Code X,Overcoming Restore Error 0X42306,Fix Error 0X80042306 System Restore
thumbnail: https://thmb.techidaily.com/de2b8c65401e9876b1b1a5fbf84a14916f9f22a18062d51200fd6852f871f665.jpg
---

## Expert Solutions for Error 0X80042306 During System Restore

 The error code 0x80042306 occurs when attempting to create a restore point in Windows. It prevents the creation of new restore points in the system and typically occurs when your system does not have sufficient free space, there is a problem with the Volume Shadow Copy service (VSS), or a background process is conflicting with the restore utility.

 Below, we talk about the different troubleshooting methods you can try to fix the system restore error 0x80042306 in Windows. We recommend booting into the administrator account before you proceed.

## 1\. Make Sure You Have Sufficient Space

 Restore points require free space on the disk they are stored. This amount of space required by a restore point typically depends on on the size and complexity of your system configuration.

 If you do not have sufficient space on the disk, the restore utility is likely to return a 0x80042306 error. This is why, we recommend getting started by making sure that enough free space for the System Restore to function correctly. You can delete unnecessary items to increase the space manually, or [use the Disk Cleanup](https://www.makeuseof.com/tag/best-way-clean-windows-10-step-step-guide/) utility that is offered by Microsoft by default.

 Alternatively, you can also increase the amount of disk space allocated for System Restore in the System Protection settings. Here is how you can do that:

1. Type "Create a restore point" in the Windows search utility and click**Open** .
2. In the following dialog, head over to the**System Protection** tab.
3. Click on the**Configure** button and use the Max usage to slider to adjust the disk percentage according to your preference.  
![Adjust the Max usage slider](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/restore-point-usage.jpg)
4. Click**Apply** \>**OK** to save the changes.

 Once the changes are made, check if you can now create a restore point without any issues.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
## 2\. Restart the Volume Shadow Copy Service

 You might also be facing the problem if the Volume Shadow Copy service is disabled or simply not functioning properly.

 This service allows the creation of backup copies for files and volumes in Windows. It is used to by the restore utility to create snapshots of the items that are being backed up and if it fails to work due to any reason, you might encounter the problem at hand.

 To ensure this service is working properly, you can restart it using the Services utility. Follow the steps below to proceed:

1. Press the**Win** +**R** keys together to open Run.
2. Type "services.msc" in Run and click**Enter** .
3. In the services window, scroll down to locate the**Volume Shadow Copy** service and right-click on it.  
![Volume Shadow Copy service in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/volume-shadow-copy.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
4. Choose**Properties** from the context menu.
5. Now, click on the**Stop** button, wait for a few seconds, and hit**Start** again.
6. Make sure the Startup type is set to**Automatic** .  
![Start the VSS service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/start-vss-service.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
7. Finally, click**Apply** \>**OK** to save the changes.

 Do the same for the Windows Backup service and check if the issue is resolved.

## 3\. Re-Register VSS Components

 If restarting the Volume Shadow Copy service did not work, then you can also try re-registering the VSS components via Command Prompt.

Here is how to proceed:

1. Press the**Win** +**R** keys together to open Run.
2. Type "cmd" in Run and press the**Ctrl** +**Shift** +**Enter** keys together to open Command Prompt as an administrator.
3. Click**Yes** in the User Account Control prompt.
4. Now, execute the following commands one by one:  
`cd /d %windir%\system32net stop vssnet stop swprvregsvr32 /s ole32.dllregsvr32 /s oleaut32.dllregsvr32 /s vss_ps.dllvssvc /registerregsvr32 /s /i  

swprv.dllregsvr32 /s /i eventcls.dllregsvr32 /s es.dllregsvr32 /s stdprov.dllregsvr32 /s vssui.dllregsvr32 /s msxml.dllregsvr32 /s  

msxml3.dllregsvr32 /s msxml4.dllvssvc /registernet start swprvnet start vss`
5. Once you have re-registered VSS components, close Command Prompt and try creating a restore point again.

 If an issue within the VSS components was causing the problem, restarting the components should fix it.

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Create a Restore Point in Safe Mode

 In some cases, a conflicting background process can also prevent the System Restore utility from creating a restore point successfully. The best way to ensure there are no applications or programs in the background interrupting the functionality of System Restore, try creating a restore point in Safe Mode.

 This mode launches Windows with a minimal set of drivers and services, which can help isolate the issue and prevent any conflicts that may be occurring in normal mode.

Here is how you can boot in Safe Mode:

1. Type "System Configuration" in Windows search and click**Open** .
2. Head over to the**Boot** tab and under Boot Options, checkmark the Safe Boot option.
3. Choose**Minimal** and click on**Apply** \>**OK** to save the changes.  
![Minimal mode of Safe Boot](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/msconfig-boot-safe-mode-minimal.jpg)

 You can now restart your computer and upon reboot, you should enter the Safe Mode automatically. Try recreating a restore point and check if the problem is resolved.

## 5\. Scan the System For Corruption Errors

![Running Sfc scan in CMD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/running-sfc-scan.jpg)
<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The System Restore utility itself might be dealing with a corruption error, which is preventing it from functioning properly.

 To fix any corrupt system files, we suggest using the System File Checker (SFC) and Deployment Image Servicing and Management (DISM) tools. SFC works by scanning the protected system files for underlying problems. If an issue is discovered, it will replace the faulty file with its healthier cached counterpart.

 DISM, on the other hand, works by repairing corrupt system images. We have a guide on [how to use SFC and DISM in Windows](https://www.makeuseof.com/windows-built-in-repair-tools/) which you can refer to, to perform the steps correctly.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
## System Restore Back On Track

 The System Restore utility in Windows is a powerful tool that can save you from losing important data in case of unexpected system issues. That said, it can be annoying if you cannot create a restore point easily, especially when you are trying to do it before performing a critical action.

 By following the methods outlined in this guideline, you can diagnose the error and take necessary steps to resolve it. We recommend making sure all the relevant services stay enabled, and your system is up-to-date to avoid any such issues in the future.


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
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-perfecting-your-presence-share-screen-mastery-in-meet/"><u>[New] 2024 Approved  Perfecting Your Presence  Share Screen Mastery in Meet</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-demystifying-the-process-of-checking-subs/"><u>[New] Demystifying The Process of Checking Subs</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-a-step-by-step-approach-to-enhancing-your-instagram-video-sizes/"><u>[New] In 2024, A Step-by-Step Approach to Enhancing Your Instagram Video Sizes</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-inexpensive-pcs-mastering-best-obs-arrangements/"><u>[New] In 2024, Inexpensive PCs  Mastering Best OBS Arrangements</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-top-5-ios-friendly-apps-unlocking-facebooks-richest-media-library/"><u>[New] In 2024, Top 5 iOS-Friendly Apps Unlocking Facebook's Richest Media Library</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-mirth-mechanics-gratis-tools-to-amuse-and-entertain-for-2024/"><u>[New] Mirth Mechanics  Gratis Tools to Amuse and Entertain for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-saving-mov-videos-on-windows-11-a-guide-with-six-steps/"><u>[New] Saving .MOV Videos on Windows 11 - A Guide with Six Steps</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-in-2024-mediameld-mixer/"><u>[Updated] In 2024, MediaMeld Mixer</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-in-2024-the-art-of-advertising-making-money-on-the-worlds-social-network/"><u>[Updated] In 2024, The Art of Advertising  Making Money on the World's Social Network</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-constructing-captivating-podcast-vignettes/"><u>2024 Approved  Constructing Captivating Podcast Vignettes</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-cutting-edge-tutorial-for-enabling-automatic-voice-conversion-in-slides/"><u>2024 Approved  Cutting Edge Tutorial for Enabling Automatic Voice Conversion in Slides</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-maximizing-video-impact-a-comprehensive-guide-to-youtube-popularity/"><u>2024 Approved  Maximizing Video Impact  A Comprehensive Guide to YouTube Popularity</u></a></li>
<li><a href="https://games-able.techidaily.com/2024s-best-portable-power-nintendo-switch-docks-guide/"><u>2024'S Best Portable Power: Nintendo Switch Docks Guide</u></a></li>
<li><a href="https://howto.techidaily.com/8-workable-fixes-to-the-sim-not-provisioned-mm2-error-on-oppo-a56s-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Workable Fixes to the SIM not provisioned MM#2 Error on Oppo A56s 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/automatic-windows-tweak-transition-to-latest-amd-driver/"><u>Automatic Windows Tweak: Transition to Latest AMD Driver</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-desktop-aesthetics-best-pc-time-saver-apps-listed/"><u>Boost Desktop Aesthetics – Best PC Time Saver Apps Listed</u></a></li>
<li><a href="https://windows11.techidaily.com/curate-your-own-win11-screen-saver/"><u>Curate Your Own Win11 Screen Saver</u></a></li>
<li><a href="https://win-amazing.techidaily.com/easy-guide-obtain-new-hp-network-driver-software-for-windows-systems/"><u>Easy Guide: Obtain New HP Network Driver Software for Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-user-interface-fastest-uninstall-actions-with-context/"><u>Elevate User Interface: Fastest Uninstall Actions with Context</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-file-selection-adding-directories-to-context-menu/"><u>Enhancing File Selection: Adding Directories to Context Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/future-screens-innovating-beyond-windows-11/"><u>Future Screens: Innovating Beyond Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-solving-win-1011-ad-ds-printer-problems-efficiently/"><u>Guide to Solving Win 10/11 AD DS Printer Problems Efficiently</u></a></li>
<li><a href="https://windows11.techidaily.com/hidden-behind-pretense-apps-slowdown-your-modern-windows/"><u>Hidden Behind Pretense: Apps Slowdown Your Modern Windows</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-can-we-unlock-our-poco-m6-pro-4g-phone-screen-by-drfone-android/"><u>How Can We Unlock Our Poco M6 Pro 4G Phone Screen?</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-overcome-media-error-input-not-recognized-by-vlc/"><u>How to Overcome Media Error: Input Not Recognized by VLC</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/in-2024-create-magic-download-premium-soundscapes-now/"><u>In 2024, Create Magic  Download Premium Soundscapes Now!</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-reset-a-locked-oppo-a18-phone-by-drfone-android/"><u>In 2024, How to Reset a Locked Oppo A18 Phone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-the-rotation-revelation-manual-transform-your-visual-content-on-social-media-sites/"><u>In 2024, The Rotation Revelation Manual  Transform Your Visual Content on Social Media Sites</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-universal-unlock-pattern-for-xiaomi-redmi-note-12-5g-by-drfone-android/"><u>In 2024, Universal Unlock Pattern for Xiaomi Redmi Note 12 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/installing-icloud-is-easy-troubleshoot-issues-on-windows/"><u>Installing iCloud Is Easy: Troubleshoot Issues on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/is-windows-11-running-slow-or-lagging-on-your-computer-7-ways-to-fix-it/"><u>Is Windows 11 Running Slow or Lagging on Your Computer? 7 Ways to Fix It</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-of-file-explorer-opening-tabs-in-windows-11/"><u>Mastery of File Explorer: Opening Tabs in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-the-future-ui-design-with-new-folder-integration-in-windows-11/"><u>Navigate the Future UI Design with New Folder Integration in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-past-the-activation-hurdle-in-microsoft-office/"><u>Navigating Past the Activation Hurdle in Microsoft Office</u></a></li>
<li><a href="https://windows11.techidaily.com/pc-files-on-ios-via-smb-share-connection/"><u>PC Files on iOS via SMB Share Connection</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-steps-for-online-printer-on-windows/"><u>Quick Steps for Online Printer on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-the-windows-application-net-demand-error/"><u>Resolving the Windows Application .NET Demand Error</u></a></li>
<li><a href="https://windows11.techidaily.com/secrets-to-savings-on-windows-10-key-focused-strategies/"><u>Secrets to Savings on Windows 10: Key-Focused Strategies</u></a></li>
<li><a href="https://some-skills.techidaily.com/strategies-for-eye-catching-podcast-previews-for-2024/"><u>Strategies for Eye-Catching Podcast Previews for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-resolve-high-dpi-screen-problems-on-pc/"><u>Strategies to Resolve High DPI Screen Problems on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-file-scooping-6-routes-to-data-secrets/"><u>Swift File Scooping: 6 Routes to Data Secrets</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-no-sync-option-on-steam-library-error/"><u>Tackling the No Sync Option on Steam Library Error</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/unveiling-top-5-mac-snippet-applications/"><u>Unveiling Top 5 Mac Snippet Applications</u></a></li>
<li><a href="https://windows11.techidaily.com/what-is-bluescreenview-and-how-do-you-use-it/"><u>What Is BlueScreenView and How Do You Use It?</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-homes-unlocked-your-guide-to-installing-hyper-v/"><u>Win 11 Homes Unlocked: Your Guide to Installing Hyper-V</u></a></li>
<li><a href="https://windows11.techidaily.com/win-back-missing-5ghz-connection-on-your-windows-pc/"><u>Win Back Missing 5GHz Connection on Your Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-reimagined-make-it-mirror-macos-style-in-5-easy-ways/"><u>Windows Reimagined: Make It Mirror macOS Style in 5 Easy Ways</u></a></li>
</ul></div>
