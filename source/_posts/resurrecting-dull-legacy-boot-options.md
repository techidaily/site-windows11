---
title: Resurrecting Dull Legacy Boot Options
date: 2024-08-08T06:07:50.792Z
updated: 2024-08-09T06:07:50.792Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resurrecting Dull Legacy Boot Options
excerpt: This Article Describes Resurrecting Dull Legacy Boot Options
keywords: Boots Resurgence,Legacy Boots Revive,Legacy Boot Choices,Dull Boot Restoration,Old Boots Selection,Reviving Classic Boots,Upgrading Outdated Footwear
thumbnail: https://thmb.techidaily.com/a5bc9c78cbf7ddebb3c4b881340c3ed8f01e0b70f6fee4b10bf3f28b3b2740fa.jpg
---

## Resurrecting Dull Legacy Boot Options

 Newer computers come with Unified Extensible Firmware Interface (UEFI) as the new standard. However, Legacy BIOS is still largely part of most active systems due to legacy software and hardware support. Switching from UEFI to Legacy BIOS is easy using the firmware utility. But what if the legacy boot option is grayed out in BIOS?

 This can happen for a few reasons. A common reason for the grayed-out BIOS is if you have Secure Boot or Platform Trusted Technology (TPM) enabled. Issues with Modern Standby supported system is another reason that prevents you from switching from UEFI to Legacy BIOS.

 Here is how to fix the Legacy Boot grayed-out in BIOS issue on your Windows system.

## What Causes the Legacy Boot Grayed Out Problem?

 You may find the Legacy Boot option grayed out if the UEFI settings, such as Secure Boot and TPM are enabled in the BIOS utility. In some instances, the BIOS utility can tell you why you can't switch to the Legacy boot option.

 Boot into your BIOS utility and open**Advanced Boot** **Options** . Next, check the**Enable Legacy Option ROMs** option. You may see an error prompt explaining why the Legacy option cannot be enabled. It usually hints that PPT/TPM or Secure Boot is enabled.

 If you don't have any such option, try the troubleshooting steps below to restore the Legacy boot option in BIOS.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
<!-- affiliate ads end -->
## 1\. Disable Secure Boot to Enable Boot

 Secure Boot is a UEFI feature that protects your computer against malware by allowing only trusted system software to run on your computer. When enabled, it will perform a cryptographic check during the boot process to verify the integrity of the system image.

 However, if you have Secure Boot enabled, it will likely disable Legacy Boot as well. You'll need to[disable Secure Boot in your BIOS utility](https://www.makeuseof.com/tag/disable-secure-uefi-dual-boot/) to fix the issue.

 The below steps to disable Secure Boot are for an HP Pavilion computer. For other systems, refer to your system manual.

To disable secure boot:

1. Click on**Start** and then click on**Power** .
2. Press and hold the**Shift key** and click on**Restart** . Confirm the action if necessary.
3. Release the**Shift** key as the PC shuts down and boot into the**Recovery Menu.**
4. Go to**Troubleshoot** and click on**Advanced options** .
5. Next, click on**UEFI Firmware Settings.**  
<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
![Advanced OptionspUEFI Firmware Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/advanced-optionspuefi-firmware-settings.jpg)

1. Click**Restart** to boot into the**Startup Menu.**  
![startup menu HP](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/startup-menu-hp-1.jpg)
2. In the Startup Menu, press**F10** to access the**BIOS Settings** . You may see other options depending on your computer manufacturer.
3. Use the right and left arrow keys to open the**Boot Options** tab in the BIOS Utility.
4. Next, use the up and down arrow key to highlight the**Secure Boot** option and press**Enter** to view more options.  
![disable secure boot bios](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-secure-boot-bios.jpg)
5. Select**Disabled** and make sure the changes are shown in the Boot Options tab.
6. Press**F10** to save the changes and disable Secure Boot.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## 2\. Disable Trusted Platform Technology (TPM)

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
![disable TPM state BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-tpm-state-bios-1.jpg)

 In addition to Secure Boot, you may also have enabled Trusted Platform Module (TPM), disabling Legacy BIOS. To fix the issue, check if TPM is enabled on your PC, which is likely a case on a Windows 11 running system, and disable the option if necessary.

 You can disable TPM from the BIOS setup utility. Here's how to do it.

1. Boot into your BIOS utility using the**Windows Recovery Menu.**
2. Next, open the**Security** tab using the right and left arrow keys.
3. Highlight the**TPM State** option and press**Enter** . If no TPM option is available, look for the**PTT** option.
4. Select**Disabled** to disable TPM on your device.
5. Press**F10** to save the change and exit.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->
## 3\. Disable Modern Standby

 Modern Standby (S0) is a newer power mode available on select modern computers. It is enabled by default on compatible systems but can cause issues with Legacy Boot.

 To fix the issue, try to[disable Modern Standby on your Windows computer](https://www.makeuseof.com/windows-disable-modern-standby/) . Once disabled, restart your PC to see if you can switch to Legacy Boot now.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Restore a Grayed Out Legacy Boot Option in Your BIOS

 You can fix the grayed-out Legacy boot option in BIOS by disabling Secure Boot and Trusted Platform Technology. In addition, disable Standard Standby (S0) to fix the problem.

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
<li><a href="https://youtube-zero.techidaily.com/024-approved-11-free-youtube-playlist-downloadersonlinepcandroidios/"><u>[New] 2024 Approved  11 FREE YouTube Playlist Downloaders[Online/PC/Android/iOS)</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-blending-beats-posting-tunes-on-digital-diaries/"><u>[New] 2024 Approved  Blending Beats  Posting Tunes on Digital Diaries</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-shortcuts-to-turn-off-instagrams-igtv/"><u>[New] In 2024, Shortcuts to Turn Off Instagram's IGTV</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-the-ultimate-free-guide-to-youtube-ad-videos/"><u>[Updated] In 2024, The Ultimate Free Guide to YouTube Ad Videos</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-ultimate-vivocut-guide-for-enhanced-video-creation/"><u>[Updated] Ultimate VivoCut Guide for Enhanced Video Creation</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-ditching-the-undesired-backdrop-the-path-less-cluttered/"><u>2024 Approved  Ditching the Undesired Backdrop  The Path Less Cluttered</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-ultimate-list-of-youtube-entrance-software/"><u>2024 Approved  Ultimate List of YouTube Entrance Software</u></a></li>
<li><a href="https://windows11.techidaily.com/4-ways-to-fix-the-mail-apps-cant-get-mail-error-on-windows-11/"><u>4 Ways to Fix the Mail App's Can’t Get Mail Error on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/adapting-windows-11-multifaceted-monitor-wallpaper-strategy/"><u>Adapting Windows 11: Multifaceted Monitor Wallpaper Strategy</u></a></li>
<li><a href="https://windows11.techidaily.com/add-compatibility-tool-to-windows-quick-access/"><u>Add Compatibility Tool to Windows' Quick Access</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-lost-extra-screen-in-w11/"><u>Addressing Lost Extra Screen in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/augmenting-windows-functionality-with-these-top-6-android-apps/"><u>Augmenting Windows Functionality with These Top 6 Android Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-unintended-snipping-tool-launch-via-prtsc-on-win-11/"><u>Avoid Unintended Snipping Tool Launch via PrtSc on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/avoidance-of-soon-to-end-windows-license-issues/"><u>Avoidance of Soon-to-End Windows License Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-and-remedying-windows-error-code-0x0000004e/"><u>Avoiding and Remedying Windows' Error Code: 0X0000004E</u></a></li>
<li><a href="https://windows11.techidaily.com/begin-your-media-adventure-windows-media-player/"><u>Begin Your Media Adventure: Windows Media Player</u></a></li>
<li><a href="https://windows11.techidaily.com/bridging-gap-restore-invisible-bluetooth-items-mgr/"><u>Bridging Gap: Restore Invisible Bluetooth Items Mgr</u></a></li>
<li><a href="https://windows11.techidaily.com/bridging-no-network-access-on-winethernet/"><u>Bridging No Network Access on WinEthernet</u></a></li>
<li><a href="https://windows11.techidaily.com/comparing-windows-terminal-with-powershells-different-utilities/"><u>Comparing Windows Terminal with PowerShell's Different Utilities</u></a></li>
<li><a href="https://windows11.techidaily.com/configure-windows-11-to-optimize-system-audio-performance/"><u>Configure Windows 11 to Optimize System Audio Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-clock-divergence-chrome-vs-windows/"><u>Correcting Clock Divergence: Chrome vs Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-loss-of-hard-drive-visibility/"><u>Correcting Loss of Hard Drive Visibility</u></a></li>
<li><a href="https://windows11.techidaily.com/counteracting-the-impact-of-vac-denial-in-steam-gaming/"><u>Counteracting the Impact of VAC Denial in Steam Gaming</u></a></li>
<li><a href="https://windows11.techidaily.com/darkeningwindowsnotepaddisplaysettings/"><u>DarkeningWindowsNotepadDisplaySettings</u></a></li>
<li><a href="https://windows11.techidaily.com/dealing-with-ios-photos-import-errors-on-windows-devices/"><u>Dealing with iOS Photos Import Errors on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-how-to-activate-and-use-mouseclicklock-efficiently/"><u>Decoding How to Activate and Use MouseClickLock Efficiently</u></a></li>
<li><a href="https://windows11.techidaily.com/defensive-operations-mastering-windows-unauthorized-prevention/"><u>Defensive Operations: Mastering Windows Unauthorized Prevention</u></a></li>
<li><a href="https://windows11.techidaily.com/direct-guide-to-reactivate-print-spool/"><u>Direct Guide to Reactivate Print Spool</u></a></li>
<li><a href="https://windows11.techidaily.com/discerning-the-divergences-between-terminal-and-powershell/"><u>Discerning the Divergences Between Terminal & PowerShell</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-distinctions-between-microsoft-and-standard-windows-accounts/"><u>Dissecting: Distinctions Between Microsoft & Standard Windows Accounts</u></a></li>
<li><a href="https://windows11.techidaily.com/dive-into-customization-windows-11s-potential-unlocked/"><u>Dive Into Customization: Windows 11'S Potential Unlocked</u></a></li>
<li><a href="https://driver-download.techidaily.com/download-and-update-guide-hp-laserjet-p1606dn-printer-drivers-on-windows/"><u>Download & Update Guide: HP LaserJet P1606dn Printer Drivers on Windows</u></a></li>
<li><a href="https://howto.techidaily.com/fixing-persistent-pandora-crashes-on-xiaomi-redmi-note-12-pro-4g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixing Persistent Pandora Crashes on Xiaomi Redmi Note 12 Pro 4G | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-identify-malfunctioning-your-drivers-with-windows-device-manager-in-windows-10-and-7-by-drivereasy-guide/"><u>How to identify malfunctioning your drivers with Windows Device Manager in Windows 10 & 7</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-sony-xperia-1-v-by-phone-number-drfone-by-drfone-virtual-android/"><u>How to Track Sony Xperia 1 V by Phone Number | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-asus-rog-phone-8-drfone-by-drfone-virtual/"><u>In 2024, 9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Asus ROG Phone 8 | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-15-pro-max-with-a-mask-on-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone 15 Pro Max with a Mask On</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-card-on-nokia-150-2023-online-without-jailbreak-by-drfone-android/"><u>In 2024, How to Unlock SIM Card on Nokia 150 (2023) online without jailbreak</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-special-features-virtual-location-on-vivo-x-fold-2-drfone-by-drfone-virtual-android/"><u>In 2024, How To Use Special Features - Virtual Location On Vivo X Fold 2? | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-new-guide-how-to-check-icloud-activation-lock-status-from-your-iphone-se-by-drfone-ios/"><u>In 2024, New Guide How To Check iCloud Activation Lock Status From Your iPhone SE</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-pioneering-sites-for-downloading-text-aesthetics/"><u>In 2024, Pioneering Sites for Downloading Text Aesthetics</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-the-comprehensive-guide-to-effective-screen-recording/"><u>In 2024, The Comprehensive Guide to Effective Screen Recording</u></a></li>
<li><a href="https://technical-tips.techidaily.com/mastering-the-setup-effective-ways-to-link-your-logitech-mouse/"><u>Mastering the Setup: Effective Ways to Link Your Logitech Mouse</u></a></li>
<li><a href="https://windows11.techidaily.com/1719329062784-overcoming-full-screen-capture-annoyances-with-these-4-strategies/"><u>Overcoming Full-Screen Capture Annoyances with These 4 Strategies</u></a></li>
<li><a href="https://extra-resources.techidaily.com/reducing-decibels-gradually-in-fl/"><u>Reducing Decibels Gradually in FL</u></a></li>
</ul></div>
