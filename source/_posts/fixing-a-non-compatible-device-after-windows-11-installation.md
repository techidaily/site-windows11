---
title: Fixing a Non-Compatible Device After Windows 11 Installation
date: 2024-08-15T16:06:20.056Z
updated: 2024-08-16T16:06:20.056Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing a Non-Compatible Device After Windows 11 Installation
excerpt: This Article Describes Fixing a Non-Compatible Device After Windows 11 Installation
keywords: Compatibility Issues Post-Windows 11,Fixing Devices in Windows 11,Update Software for Device Compat,Resolve Non-Compatible PC Errors,Address Windows 11 Install Fails,Adjust New OS on Old Hardware,Enhance Device Functionality Post-Update
thumbnail: https://thmb.techidaily.com/95716cb061a5dae526d57500a8951c520e1cad5f6661b79a6595a67d8bfbaed5.jpg
---

## Fixing a Non-Compatible Device After Windows 11 Installation

 Microsoft Windows 11 is here, and you can use the company's PC Health Check app to check if your PC meets the minimum system requirements to install Windows 11\. Unfortunately, for many users, running the PC Health Check app returns the This PC can't Run Windows 11 error.

 You will most likely encounter this error if the app detects your system hardware incompatible with Windows 11\. Fortunately, there are workarounds to get around this annoying error that may prevent you from upgrading to Windows 11 successfully.

## What Is the Windows 11 Upgrade Error Message?

The full error message reads:

 "This PC can't run Windows 11—While this PC doesn't meet the system requirements to run Windows 11, you'll keep getting Windows 10 updates"

Additionally, you may also see the following error:

* This PC must support TMP 1.2/2.0.
* This PC must support Secure Boot.

 If you are experiencing similar errors, it is possible that your PC doesn't have the minimum system requirements to run Windows 11\. That said, the error can be a false flag as well as it will not detect a Secure Boot and TMP 2.0-supported systems if the features are disabled in BIOS.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->
## What Are the System Requirements to Install Windows 11?

 Interestingly, the official [Windows 11 system requirements](https://www.makeuseof.com/can-your-pc-run-windows-11/) aren't the most intensive, and most modern systems should support it out of the box. However, there are some upgrades from Windows 10.

 The following are the system requirements to install and run Windows 11:

* 1GHz 64-bit processor
* 4GB of RAM
* 64 GB of storage space
* System firmware that supports UEFI, Secure Boot capable
* Trusted Platform Module (TPM) 1.2/2.0.

 Now, if you meet the hardware specifications and still encounter this PC can't run Windows 11 error when using the [PC Health Checkup](https://www.microsoft.com/en-us/windows/windows-11) app, you can fix it by tweaking a few settings in your BIOS/UEFI setup.

![pc health check upgrade windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/06/pc-health-check-upgrade-windows-11.png)

 You may also encounter said error when installing Windows 11 through a bootable drive or setup file from the mounted ISO.

### What Is UEFI Boot Mode?

 UEFI (Unified Extensible Firmware Interface) is a booting method designed to replace BIOS (Basic Input Output System). In the legacy boot, the system uses BIOS firmware for booting.

 In general, installing Windows using the newer UEFI mode is recommended as it comes with more security features such as Secure Boot than the legacy BIOS mode. You can [learn more about BIOS](https://www.makeuseof.com/tag/the-bios-explained-boot-order-video-memory-saving-resets-and-optimum-defaults-si/) here.

## What Causes the "PC Can't Run Windows 11 Error?"

 This error occurs when you run the PC Health Check app to check if your PC supports Windows 11\. It may also occur when you try to install Windows 11 from the bootable flash drive or using the setup file from the mounted ISO.

 For Windows 11 to be compatible with your computer, it must support UEFI with Secure Boot, and TPM 1.2 or 2.0 must be enabled. Since Windows 11 requires a UEFI Secure Boot compatible system, the setup will fail to detect required features if you have installed Windows 10 via the legacy boot mode.

 This will trigger the This PC can't install Windows 11 error as the system requirements are unmet. Even if your PC support both Secure Boot and TMP 2.0, you may still have to enable them to resolve the error manually.

 If you use legacy boot mode, you need to set the Boot Mode to UEFI in your BIOS setup to enable the Secure Boot feature (and potentially switch TMP 1.2/2.0 on, too).

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Fix the "This PC Can't Run Windows 11 Error?"

 To fix this error, you should set the Boot Mode to UEFI and enable Secure Boot, and then make sure TPM 1.2/2.0 is enabled on your computer. Please note that the tab names may vary between manufacturers, but the instructions should translate roughly across hardware.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->
## 1\. Enable Secure Boot in Windows 10

![Enable Secure Boot UEFI Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/06/Secure-Boot-enabled.png)
<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->

Follow these steps to enable Secure Boot compatibility in Windows 10.

1. Close all the open Windows and save your work. Then shut down your PC.
2. Restart your system and start pressing**F2** to enter BIOS setup. Different laptop and PC manufacturers may use other function keys such as F12, F10, F8, or Esc key to enter BIOS. If you need help, refer to our guide on [how to enter BIOS](https://www.makeuseof.com/tag/enter-bios-computer/) for more tips.
3. In the BIOS setup utility, use the arrow keys to open the**Boot** tab. Highlight**Boot Mode** and check if it is set to**Legacy** .
4. To change the Boot Mode, press Enter while the**Boot Mode** is highlighted.
5. Choose**UEFI** from the options. Use the Up and Down arrow keys to select UEFI, and hit Enter to select the option.
6. Next, open the**Security** tab.
7. Highlight the**Secure Boot** option using the arrow keys and hit Enter.
8. Choose**Enabled** to enable Secure Boot on your PC.

 Once you have enabled Secure Boot and UEFI in Boot Mode, make sure TPM 1.2/2.0 is also enabled for your PC. So, don't close the BIOS setup menu yet.

<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Enable TMP 1.2/2.0 to fix the "This PC Can't Install Windows 11 Error"

![Enable Trusted Platform Module](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/06/Enable-TPM-2-0-BIOS.png)

 TMP 1.2/2.0 feature is accessible from the BIOS setup as well. Here's how to do it.

1. In BIOS/UEFI, open the**Security** tab.
2. Scroll down and highlight the**Trusted Platform Technology** option, and hit Enter. On Intel laptops, you may see the**Intel Platform Trust Technology** option instead.
3. Choose**Enabled** and press Enter to apply your selection.
4. Save the changes and exit.

 That's it. You have successfully enabled Secure Boot compatibility and TMP 2.0 on Windows 10\. Restart your PC, run the PC Health Checkup tool, or install Windows 11 to see if the error is resolved.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Bypass TPM 2.0 and Secure Boot Requirement Using Registry Editor

 If your PC doesn't support Secure Boot and TPM 2.0, you can bypass the restriction using a workaround. To do this, we will modify the registry entry, allowing you to upgrade without Secure Boot and TPM 2.0 requirements.

 Note that your system must support at least TPM 1.2 for this workaround to work.

 Note that editing your Windows Registry involves risk. Make sure to [create a system restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and then proceed with the step below.

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open**Registry Editor.**
3. In Registry Editor, navigate to the following location. You can copy and paste the registry path for quick navigation:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\Setup\MoSetup`
4. Right-click on the**MoSetup** key and selec**t New > DWORD** (32-bit) value.  
![registry editor mosetup new value bypass windows 11 restriction](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/registry-editor-mosetup-new-value-bypass-windows-11-restriction.jpg)
5. Rename the value as**AllowUpgradeWithUnsupportedTPMorCPU.**
6. Right-click on the newly created value and select**Modify** .  
![registry editor mosetup new value 1 bypass windows 11 restriction](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/registry-editor-mosetup-new-value-1-bypass-windows-11-restriction.jpg)
7. In the Value data field, type**1** and click**OK** to save the changes.
8. Close the Registry Editor and try to install Windows 11 using the media creation tool or ISO. The upgrade should complete without the error.

 If the issue persists, read our guide to [bypass Windows 11 minimum installation requirements](https://www.makeuseof.com/bypass-windows-11-minimum-installation-requirements/) to learn more ways to bypass the restrictions and upgrade your PC.

## No Boot Device Found Error After Changing Boot Mode from Legacy to UEFI

 You may encounter the**No Boot Device Found** error if you change the Boot Mode for an existing Windows 10 installation from Legacy to UEFI. However, there's nothing to worry about.

 You can easily boot into your existing Windows 10 installation by changing the Boot Mode to Legacy from UEFI again in the BIOS setup. Next, use the MBR2GTP tool to convert your installation drive/disk from Master Boot Record (MBR) to the GUID Partition Table (GPT) without modifying or deleting data on the disk. You can learn more about using MBR2GRP here .

 Once you have converted the drive, you can change the Boot Mode from Legacy to UEFI without the No Boot Device Found error. Alternatively, if you are going to clean install Windows 11, make sure to install Windows 11 (or Windows 10) in the UEFI mode to prevent any issues in the future.

 If the bootable drive does not show up in the Boot Manager after enabling Secure Boot, ensure it is formatted with the UEFI system in Rufus. If not, create a bootable drive again with the target system set to UEFI (CMS).

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fixing the This PC Can't Run Windows 11 Error

 Windows computers with the BIOS legacy firmware enabled won't be able to install Windows 11\. Fortunately, you can easily fix the error by tweaking your BIOS setup utility to enable UEFI firmware mode to enable Secure Boot and TPM 2.0.


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
<li><a href="https://some-approaches.techidaily.com/updated-hero-vs-hero-a-technological-comparison/"><u>[Updated] Hero Vs Hero  A Technological Comparison</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-tuning-into-iphones-sound-scenarios/"><u>[Updated] Tuning Into iPhone's Sound Scenarios</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-unveiling-the-secrets-of-movie-maker-on-windows-8/"><u>[Updated] Unveiling the Secrets of Movie Maker on Windows 8</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-veiled-viewer-in-the-social-sphere/"><u>[Updated] Veiled Viewer in the Social Sphere</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-20-top-free-cloud-storage-options-maximize-your-upload-limit-1tbplus/"><u>2024 Approved  20 Top Free Cloud Storage Options, Maximize Your Upload Limit (1TB+)</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-optimal-8-windows-podcast-solutions/"><u>2024 Approved  Optimal 8-Windows Podcast Solutions</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-webcam-setup-for-quick-recordings-on-chromebooks/"><u>2024 Approved  Webcam Setup for Quick Recordings on Chromebooks</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/2024-approved-what-is-ai-influencer-wondershare-virbo-glossary/"><u>2024 Approved What Is AI Influencer? | Wondershare Virbo Glossary</u></a></li>
<li><a href="https://windows11.techidaily.com/7-unique-windows-methods-for-launching-applications/"><u>7 Unique Windows Methods for Launching Applications</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-common-fails-on-your-first-day-with-windows-11/"><u>Avoiding Common Fails on Your First Day with Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/ceasing-autonomous-openings-in-microsoft-shop-app/"><u>Ceasing Autonomous Openings in Microsoft Shop App</u></a></li>
<li><a href="https://windows11.techidaily.com/changing-terminals-default-backdrop/"><u>Changing Terminal's Default Backdrop</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-memory-test-failed-in-windows/"><u>Combatting 'Memory Test Failed' In Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-the-essence-of-windows-11s-registry-structure/"><u>Dissecting the Essence of Windows 11'S Registry Structure</u></a></li>
<li><a href="https://windows11.techidaily.com/easing-the-load-streamlining-windows-11-mails-email-display/"><u>Easing the Load: Streamlining Windows 11 Mail's Email Display</u></a></li>
<li><a href="https://fox-access.techidaily.com/easy-editing-unlimited-canon-lut-choices/"><u>Easy Editing - Unlimited Canon LUT Choices</u></a></li>
<li><a href="https://windows11.techidaily.com/evaluating-hidden-gems-in-windows-system-monitors/"><u>Evaluating Hidden Gems in Windows' System Monitors</u></a></li>
<li><a href="https://buynow-help.techidaily.com/explore-the-enhanced-capabilities-of-the-newly-launched-cycwagen-cargo-electric-bike/"><u>Explore the Enhanced Capabilities of the Newly Launched CycWagen Cargo Electric Bike</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-recover-and-reset-itunes-when-its-not-working/"><u>How to Recover and Reset iTunes When It's Not Working</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-use-pokemon-go-joystick-on-itel-p55plus-drfone-by-drfone-virtual-android/"><u>How to use Pokemon Go Joystick on Itel P55+? | Dr.fone</u></a></li>
<li><a href="https://data-wizards.techidaily.com/immediate-exchange-outer-space-film-restore/"><u>Immediate Exchange: Outer Space Film Restore</u></a></li>
<li><a href="https://windows11.techidaily.com/implementing-effective-policies-for-external-drive-use-in-windows/"><u>Implementing Effective Policies for External Drive Use in Windows</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-disabled-iphone-14-how-to-unlock-a-disabled-iphone-14-drfone-by-drfone-ios/"><u>In 2024, Disabled iPhone 14 How to Unlock a Disabled iPhone 14? | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-navigating-googles-podcast-uploading-guide/"><u>In 2024, Navigating Google's Podcast Uploading Guide</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-nighttime-storyscapes-in-moving-pictures/"><u>In 2024, Nighttime Storyscapes in Moving Pictures</u></a></li>
<li><a href="https://youtube-web.techidaily.com/encer-tip-crafting-irresistible-templated-content-in-youtube-descriptions-for-2024/"><u>Influencer Tip  Crafting Irresistible Templated Content in YouTube Descriptions for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/innovative-interfaces-windows-following-11/"><u>Innovative Interfaces: Windows Following 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719255310971-jump-over-compatibility-obstacles-with-these-simple-fixes/"><u>Jump Over Compatibility Obstacles with These Simple Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-ai-to-enhance-shopping-on-the-ms-store/"><u>Leveraging AI to Enhance Shopping on the MS Store</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-techniques-for-an-opening-windows-terminal/"><u>Mastering Techniques for an Opening Windows Terminal</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-touchpad-sensitivity-in-windows-11-devices/"><u>Mastering Touchpad Sensitivity in Windows 11 Devices</u></a></li>
<li><a href="https://win-solutions.techidaily.com/no-more-lags-resolving-fps-drops-eradicating-gameplay-hiccups-and-boosting-performance/"><u>No More Lags: Resolving FPS Drops, Eradicating Gameplay Hiccups & Boosting Performance</u></a></li>
<li><a href="https://win-solutions.techidaily.com/oculus-link-not-working-here-are-6-rapid-remedies-for-the-black-screen-glitch/"><u>Oculus Link Not Working? Here Are 6 Rapid Remedies for the Black Screen Glitch</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-restrictions-to-write-files-in-windows-11-os/"><u>Overcoming Restrictions to Write Files in Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/proactive-protection-with-powertoys-locksmith-toolkit/"><u>Proactive Protection with PowerToys' Locksmith Toolkit</u></a></li>
<li><a href="https://windows11.techidaily.com/reduce-precision-jumps-turn-off-mouse-speed-on-your-pc/"><u>Reduce Precision Jumps: Turn Off Mouse Speed on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/remedies-for-sudden-stoppages-of-windows-notepad-app/"><u>Remedies for Sudden Stoppages of Windows Notepad App</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-your-excel-layout-fixing-failed-new-cell-insertions-on-pc/"><u>Reviving Your Excel Layout: Fixing Failed New Cell Insertions on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-steps-to-launch-wordpad-on-windows/"><u>Seamless Steps to Launch WordPad on Windows</u></a></li>
<li><a href="https://technical-tips.techidaily.com/1722903190821-step-by-step-guide-flushing-your-android-devices-cache/"><u>Step-by-Step Guide: Flushing Your Android Device's Cache</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-resolving-windows-11s-isdonedll-problems/"><u>Strategies for Resolving Windows 11'S ISDone.dll Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-regain-control-over-non-responsive-overlays/"><u>Strategies to Regain Control over Non-Responsive Overlays</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-files-in-win-11-with-context-menu-enhancements/"><u>Streamline Your Files in Win 11 with Context Menu Enhancements</u></a></li>
<li><a href="https://windows11.techidaily.com/supercharge-win11s-notes-via-wise-mentor/"><u>Supercharge Win11's Notes via Wise Mentor</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-inactive-mail-signals-on-desktop-os/"><u>Tackling Inactive Mail Signals on Desktop OS</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/the-best-ispoofer-alternative-to-try-on-apple-iphone-6-plus-drfone-by-drfone-virtual-ios/"><u>The Best iSpoofer Alternative to Try On Apple iPhone 6 Plus | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-best-free-desktop-pass-gen-software/"><u>The Ultimate Guide to Best Free Desktop Pass Gen Software</u></a></li>
<li><a href="https://some-guidance.techidaily.com/time-honored-tricks-top-1980s-visual-effects-to-elevate-your-edits-for-2024/"><u>Time-Honored Tricks  Top 1980S Visual Effects to Elevate Your Edits for 2024</u></a></li>
<li><a href="https://fox-that.techidaily.com/1721460535558-troubleshooting-tips-resolving-iphone-email-sync-problems-today/"><u>Troubleshooting Tips: Resolving iPhone Email Sync Problems Today</u></a></li>
<li><a href="https://windows11.techidaily.com/uncovering-the-oddities-in-windows-11-visual-language/"><u>Uncovering the Oddities in Windows 11 Visual Language</u></a></li>
<li><a href="https://common-error.techidaily.com/understanding-and-managing-company-wide-windows-setup-preferences/"><u>Understanding and Managing Company-Wide Windows Setup Preferences</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/unveiling-advanced-game-recording-techniques-in-windows-11/"><u>Unveiling Advanced Game Recording Techniques in Windows 11</u></a></li>
<li><a href="https://apple-account.techidaily.com/why-apple-account-disabled-from-your-apple-iphone-15-how-to-fix-by-drfone-ios/"><u>Why Apple Account Disabled From your Apple iPhone 15? How to Fix</u></a></li>
<li><a href="https://windows11.techidaily.com/win10-troubleshooting-make-functions-work-again/"><u>WIN10 Troubleshooting: Make Functions Work Again</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-dynamic-ui-embracing-the-new-widget-era/"><u>Windows 11'S Dynamic UI: Embracing the New Widget Era</u></a></li>
</ul></div>