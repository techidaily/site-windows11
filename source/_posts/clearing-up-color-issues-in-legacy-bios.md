---
title: Clearing Up Color Issues in Legacy BIOS
date: 2024-08-15T15:10:37.040Z
updated: 2024-08-16T15:10:37.040Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Clearing Up Color Issues in Legacy BIOS
excerpt: This Article Describes Clearing Up Color Issues in Legacy BIOS
keywords: BIOS Color Fix,Legacy BIOS Improvement,Clear BIOS Colors,Resolve BIOS Chromaticity,Update Legacy BIOS,Remove BIOS Hue Issues,Correct BIOS Shade Problems
thumbnail: https://thmb.techidaily.com/4bc09bf00dd16476adc7181e127ad6390edb7499dd05b4708d5bc6f8d46016ec.png
---

## Clearing Up Color Issues in Legacy BIOS

 Newer computers come with Unified Extensible Firmware Interface (UEFI) as the new standard. However, Legacy BIOS is still largely part of most active systems due to legacy software and hardware support. Switching from UEFI to Legacy BIOS is easy using the firmware utility. But what if the legacy boot option is grayed out in BIOS?

 This can happen for a few reasons. A common reason for the grayed-out BIOS is if you have Secure Boot or Platform Trusted Technology (TPM) enabled. Issues with Modern Standby supported system is another reason that prevents you from switching from UEFI to Legacy BIOS.

 Here is how to fix the Legacy Boot grayed-out in BIOS issue on your Windows system.

## What Causes the Legacy Boot Grayed Out Problem?

 You may find the Legacy Boot option grayed out if the UEFI settings, such as Secure Boot and TPM are enabled in the BIOS utility. In some instances, the BIOS utility can tell you why you can't switch to the Legacy boot option.

 Boot into your BIOS utility and open**Advanced Boot** **Options** . Next, check the**Enable Legacy Option ROMs** option. You may see an error prompt explaining why the Legacy option cannot be enabled. It usually hints that PPT/TPM or Secure Boot is enabled.

 If you don't have any such option, try the troubleshooting steps below to restore the Legacy boot option in BIOS.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->
## 1\. Disable Secure Boot to Enable Boot

 Secure Boot is a UEFI feature that protects your computer against malware by allowing only trusted system software to run on your computer. When enabled, it will perform a cryptographic check during the boot process to verify the integrity of the system image.

 However, if you have Secure Boot enabled, it will likely disable Legacy Boot as well. You'll need to [disable Secure Boot in your BIOS utility](https://www.makeuseof.com/tag/disable-secure-uefi-dual-boot/) to fix the issue.

 The below steps to disable Secure Boot are for an HP Pavilion computer. For other systems, refer to your system manual.

To disable secure boot:

1. Click on**Start** and then click on**Power** .
2. Press and hold the**Shift key** and click on**Restart** . Confirm the action if necessary.
3. Release the**Shift** key as the PC shuts down and boot into the**Recovery Menu.**
4. Go to**Troubleshoot** and click on**Advanced options** .
5. Next, click on**UEFI Firmware Settings.**  
![Advanced OptionspUEFI Firmware Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/advanced-optionspuefi-firmware-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. Click**Restart** to boot into the**Startup Menu.**  
![startup menu HP](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/startup-menu-hp-1.jpg)
2. In the Startup Menu, press**F10** to access the**BIOS Settings** . You may see other options depending on your computer manufacturer.
3. Use the right and left arrow keys to open the**Boot Options** tab in the BIOS Utility.
4. Next, use the up and down arrow key to highlight the**Secure Boot** option and press**Enter** to view more options.  
![disable secure boot bios](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-secure-boot-bios.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
5. Select**Disabled** and make sure the changes are shown in the Boot Options tab.
6. Press**F10** to save the changes and disable Secure Boot.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## 2\. Disable Trusted Platform Technology (TPM)

![disable TPM state BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-tpm-state-bios-1.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4531356&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8fdd149fcaa7058caccc9c4ad5b0d89a/products/tss-box.JPG" border="0">The Tube Sites Submitter is a fast and efficient tool for anyone who needs to upload videos quickly, easily and automatically to hundreds of tube sites in mere minutes . </a>
<!-- affiliate ads end -->

 In addition to Secure Boot, you may also have enabled Trusted Platform Module (TPM), disabling Legacy BIOS. To fix the issue, check if TPM is enabled on your PC, which is likely a case on a Windows 11 running system, and disable the option if necessary.

 You can disable TPM from the BIOS setup utility. Here's how to do it.

1. Boot into your BIOS utility using the**Windows Recovery Menu.**
2. Next, open the**Security** tab using the right and left arrow keys.
3. Highlight the**TPM State** option and press**Enter** . If no TPM option is available, look for the**PTT** option.
4. Select**Disabled** to disable TPM on your device.
5. Press**F10** to save the change and exit.

## 3\. Disable Modern Standby

 Modern Standby (S0) is a newer power mode available on select modern computers. It is enabled by default on compatible systems but can cause issues with Legacy Boot.

 To fix the issue, try to [disable Modern Standby on your Windows computer](https://www.makeuseof.com/windows-disable-modern-standby/) . Once disabled, restart your PC to see if you can switch to Legacy Boot now.

<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
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
<li><a href="https://youtube-docs.techidaily.com/024-approved-vloggers-guide-to-choosing-camera-essentials-the-top-9-accessories/"><u>[New] 2024 Approved  Vloggers' Guide to Choosing Camera Essentials - The Top 9 Accessories</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-bp550-review-latest-tech-advances/"><u>[New] BP550 Review  Latest Tech Advances</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-elevate-video-conferencing-skills-google-meet-aesthetics-guide/"><u>[New] Elevate Video Conferencing Skills  Google Meet Aesthetics Guide</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-masterful-use-of-digital-boards-in-web-meetings-across-appleandroid-and-laptops/"><u>[New] In 2024, Masterful Use of Digital Boards in Web Meetings Across Apple/Android & Laptops</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-navigating-through-premium-hdr-camera-options/"><u>[New] In 2024, Navigating Through Premium HDR Camera Options</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-addressing-missing-image-display-in-youtubes-shorts-for-2024/"><u>[Updated] Addressing Missing Image Display in YouTubes Shorts for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-adobes-toolset-perfecting-your-youtube-uploads-for-2024/"><u>[Updated] Adobe's Toolset  Perfecting Your YouTube Uploads for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/1716069835614-updated-in-2024-leveraging-huaweis-inbuilt-screen-capture-tech-on-its-phones/"><u>[Updated] In 2024, Leveraging Huawei's Inbuilt Screen Capture Tech on Its Phones.</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-capture-comprehensive-screen-shot/"><u>2024 Approved  Capture Comprehensive Screen Shot</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-expeditious-approaches-to-slide-storage/"><u>2024 Approved  Expeditious Approaches to Slide Storage</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-understanding-the-economics-youtubes-new-model-for-content-creators-and-viewers/"><u>2024 Approved  Understanding the Economics  YouTube's New Model for Content Creators and Viewers</u></a></li>
<li><a href="https://tech-haven.techidaily.com/ai-lexicon-unveiled-navigating-through-29-keywords-to-revolutionize-your-understanding-of-machine-intellect/"><u>AI Lexicon Unveiled: Navigating Through 29 Keywords to Revolutionize Your Understanding of Machine Intellect</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-compatibility-nightmares-in-windows-without-troubleshooting-tools/"><u>Fix Compatibility Nightmares in Windows without Troubleshooting Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-device-not-reset-issue-in-win-11/"><u>Fixing 'Device Not Reset' Issue in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-microsoft-store-error-0x80072efd-on-pcs/"><u>Fixing Microsoft Store Error 0X80072EFD on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-store-failure-codes/"><u>Fixing Windows Store Failure Codes</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-self-clearing-windows-recycle-bin/"><u>Guide to Self-Clearing Windows Recycle Bin</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-to-correct-err-87-on-windows-loadlib/"><u>Guidelines to Correct Err 87 on Windows LoadLib</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-no-supported-devices-problem-in-windows-update/"><u>Handling 'No Supported Devices' Problem in Windows Update</u></a></li>
<li><a href="https://windows11.techidaily.com/harness-full-potential-of-windows-11-task-manager-filters-and-themes-at-your-fingertips/"><u>Harness Full Potential of Windows 11 Task Manager: Filters & Themes at Your Fingertips</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-microsoft-store-error-0x80073d26-in-windows-10-and-11/"><u>How to Fix the Microsoft Store Error 0X80073D26 in Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-halt-windows-desktop-keys-effectively/"><u>How to Halt Windows Desktop Keys Effectively</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-remove-a-previously-synced-google-account-from-your-gionee-f3-pro-by-drfone-android/"><u>How to Remove a Previously Synced Google Account from Your Gionee F3 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-repair-unable-to-fetch-error-in-nvidia-geforce-experience/"><u>How To Repair 'Unable To Fetch' Error in NVIDIA GeForce Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-intervention-for-directdraw-fails-in-windows-1011/"><u>Immediate Intervention for DirectDraw Fails in Windows 10/11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-oppo-reno-11f-5g-by-drfone-android/"><u>In 2024, 10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On Oppo Reno 11F 5G</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-best-anti-tracker-software-for-lava-blaze-2-drfone-by-drfone-virtual-android/"><u>In 2024, Best Anti Tracker Software For Lava Blaze 2 | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-full-tutorial-to-bypass-your-zte-axon-40-lite-face-lock-by-drfone-android/"><u>In 2024, Full Tutorial to Bypass Your ZTE Axon 40 Lite Face Lock?</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-fix-oem-unlock-missing-on-oppo-a59-5g-by-drfone-android/"><u>In 2024, How To Fix OEM Unlock Missing on Oppo A59 5G?</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-mastering-youtube-monetization-a-cpm-perspective/"><u>In 2024, Mastering YouTube Monetization  A CPM Perspective</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-sierras-icloud-drive-essentials-for-seamless-workflows/"><u>In 2024, Sierra’s iCloud Drive Essentials for Seamless Workflows</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-step-by-step-to-mastering-adobes-cloud-storage-capabilities-and-options/"><u>In 2024, Step-by-Step to Mastering Adobe's Cloud Storage Capabilities & Options</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-6-appsservices-to-trace-any-realme-gt-5-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, Top 6 Apps/Services to Trace Any Realme GT 5 Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-7-phone-number-locators-to-track-oppo-reno-9a-location-drfone-by-drfone-virtual-android/"><u>In 2024, Top 7 Phone Number Locators To Track Oppo Reno 9A Location | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/is-pgsharp-legal-when-you-are-playing-pokemon-on-realme-c67-5g-drfone-by-drfone-virtual-android/"><u>Is pgsharp legal when you are playing pokemon On Realme C67 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/masterful-windows-11-app-launch-strategies/"><u>Masterful Windows 11 App Launch Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-development-navigating-dev-drive-in-windows-11/"><u>Mastering Development: Navigating Dev Drive in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-repairing-windows-email-failures-error-code-0x800713f/"><u>Mastering the Art of Repairing Windows' Email Failures (Error Code 0X800713F)</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-task-scheduler-for-file-batch-execution/"><u>Mastering Windows Task Scheduler for File Batch Execution</u></a></li>
<li><a href="https://extra-tips.techidaily.com/metaverse-masterpieces-top-ten-films-that-reimagine-realities/"><u>Metaverse Masterpieces  Top Ten Films That Reimagine Realities</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-two-users-shared-ms-login-fails/"><u>Navigating Through Two Users' Shared MS Login Fails</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-command-execution-setting-terminal-preference/"><u>Optimize Command Execution: Setting Terminal Preference</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-connectivity-issues-via-winvpn/"><u>Overcoming Windows Connectivity Issues via WinVPN</u></a></li>
<li><a href="https://fox-links.techidaily.com/pro-level-performance-a-compre-cookie-box/"><u>Pro-Level Performance  A Compre Cookie Box</u></a></li>
<li><a href="https://windows11.techidaily.com/proven-tactics-for-heic-to-jpeg-conversion-process-on-windows-11-systems/"><u>Proven Tactics for Heic to JPEG Conversion Process on Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-for-disabling-audio-playback-errors/"><u>Quick Fix for Disabling Audio Playback Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/redefining-phones-role-in-windows-11-networking/"><u>Redefining Phones' Role in Windows 11 Networking</u></a></li>
<li><a href="https://windows11.techidaily.com/reinvigorate-discolored-volume-settings-in-win/"><u>Reinvigorate Discolored Volume Settings in Win</u></a></li>
<li><a href="https://windows11.techidaily.com/safeguarding-your-os-managing-usb-device-use/"><u>Safeguarding Your OS: Managing USB Device Use</u></a></li>
<li><a href="https://windows11.techidaily.com/secrecy-startup-the-invisible-power-button-guide/"><u>Secrecy Startup: The Invisible Power Button Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-a-static-backdrop-on-modern-windows-11-pcs/"><u>Secure a Static Backdrop on Modern Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/slash-wms-high-graphics-consumption-for-efficient-windows-11/"><u>Slash WM's High Graphics Consumption for Efficient Windows 11</u></a></li>
<li><a href="https://data-wizards.techidaily.com/smooth-transitions-overcoming-interlace-video-challenges/"><u>Smooth Transitions: Overcoming Interlace Video Challenges</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-common-disk-errors-on-windows-devices/"><u>Solutions for Common Disk Errors on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-entering-windows-11-home-settings/"><u>Step-by-Step: Entering Windows 11 Home Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-restore-active-window-defense-system/"><u>Strategies to Restore Active Window Defense System</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-prevent-overheating-in-w11-pcs/"><u>Techniques to Prevent Overheating in W11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-reinstate-lost-mcuicnt-file-in-windows/"><u>Techniques to Reinstate Lost McUICnt File in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-rotation-rulebook-six-secrets-to-snap-spins-in-windows-11/"><u>The Rotation Rulebook: Six Secrets to Snap-Spins in Windows 11</u></a></li>
<li><a href="https://some-approaches.techidaily.com/top-15-masterpieces-in-stop-motion-cinema-history-for-2024/"><u>Top 15 Masterpieces in Stop-Motion Cinema History for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/turbo-steam-downloads-overcoming-frustrating-speed-halts/"><u>Turbo Steam Downloads: Overcoming Frustrating Speed Halts</u></a></li>
<li><a href="https://windows11.techidaily.com/uncovering-and-correcting-cant-access-mail-errors-in-windows-11-mail-app/"><u>Uncovering and Correcting Can't Access Mail Errors in Windows 11 Mail App</u></a></li>
<li><a href="https://technical-tips.techidaily.com/water-resistance-does-iphone-15-pro-max-hold-up-underwater/"><u>Water Resistance: Does iPhone 15 Pro Max Hold Up Underwater?</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-transition-phasing-out-old-traits/"><u>Windows Transition: Phasing Out Old Traits</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-xiaomi-13t-pro-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset Xiaomi 13T Pro | Dr.fone</u></a></li>
</ul></div>
