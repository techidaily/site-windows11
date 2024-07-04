---
title: Curing Stale BOOT Option Imagery
date: 2024-06-25T12:23:49.534Z
updated: 2024-06-26T12:23:49.534Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Curing Stale BOOT Option Imagery
excerpt: This Article Describes Curing Stale BOOT Option Imagery
keywords: Cure Boots Image,Fresh Boot Photos,Revive Shoe Pictures,New Boots Shots,Rejuvenate Boot Art,Brighten Footwear,Renew Leather Images
thumbnail: https://thmb.techidaily.com/4af354c0c4f31e85da7815990d834961f2e7342ecb73532a36e97929bcf9934e.jpg
---

## Curing Stale BOOT Option Imagery

 Newer computers come with Unified Extensible Firmware Interface (UEFI) as the new standard. However, Legacy BIOS is still largely part of most active systems due to legacy software and hardware support. Switching from UEFI to Legacy BIOS is easy using the firmware utility. But what if the legacy boot option is grayed out in BIOS?

 This can happen for a few reasons. A common reason for the grayed-out BIOS is if you have Secure Boot or Platform Trusted Technology (TPM) enabled. Issues with Modern Standby supported system is another reason that prevents you from switching from UEFI to Legacy BIOS.

 Here is how to fix the Legacy Boot grayed-out in BIOS issue on your Windows system.

## What Causes the Legacy Boot Grayed Out Problem?

 You may find the Legacy Boot option grayed out if the UEFI settings, such as Secure Boot and TPM are enabled in the BIOS utility. In some instances, the BIOS utility can tell you why you can't switch to the Legacy boot option.

 Boot into your BIOS utility and open**Advanced Boot** **Options** . Next, check the**Enable Legacy Option ROMs** option. You may see an error prompt explaining why the Legacy option cannot be enabled. It usually hints that PPT/TPM or Secure Boot is enabled.

 If you don't have any such option, try the troubleshooting steps below to restore the Legacy boot option in BIOS.

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
![Advanced OptionspUEFI Firmware Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/advanced-optionspuefi-firmware-settings.jpg)

1. Click**Restart** to boot into the**Startup Menu.**  
![startup menu HP](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/startup-menu-hp-1.jpg)
2. In the Startup Menu, press**F10** to access the**BIOS Settings** . You may see other options depending on your computer manufacturer.
3. Use the right and left arrow keys to open the**Boot Options** tab in the BIOS Utility.
4. Next, use the up and down arrow key to highlight the**Secure Boot** option and press**Enter** to view more options.  
![disable secure boot bios](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-secure-boot-bios.jpg)
5. Select**Disabled** and make sure the changes are shown in the Boot Options tab.
6. Press**F10** to save the changes and disable Secure Boot.

## 2\. Disable Trusted Platform Technology (TPM)

![disable TPM state BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-tpm-state-bios-1.jpg)

 In addition to Secure Boot, you may also have enabled Trusted Platform Module (TPM), disabling Legacy BIOS. To fix the issue, check if TPM is enabled on your PC, which is likely a case on a Windows 11 running system, and disable the option if necessary.

 You can disable TPM from the BIOS setup utility. Here's how to do it.

1. Boot into your BIOS utility using the**Windows Recovery Menu.**
2. Next, open the**Security** tab using the right and left arrow keys.
3. Highlight the**TPM State** option and press**Enter** . If no TPM option is available, look for the**PTT** option.
4. Select**Disabled** to disable TPM on your device.
5. Press**F10** to save the change and exit.

## 3\. Disable Modern Standby

 Modern Standby (S0) is a newer power mode available on select modern computers. It is enabled by default on compatible systems but can cause issues with Legacy Boot.

 To fix the issue, try to[disable Modern Standby on your Windows computer](https://www.makeuseof.com/windows-disable-modern-standby/) . Once disabled, restart your PC to see if you can switch to Legacy Boot now.

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
<li><a href="https://windows11.techidaily.com/unlocking-memory-integrity-on-windows-11-methods-77/"><u>Unlocking Memory Integrity on Windows 11: Methods 7/7</u></a></li>
<li><a href="https://windows11.techidaily.com/nexus-controller-detection-woes-heres-how-to-win-them-back/"><u>Nexus Controller Detection Woes? Here's How to Win Them Back</u></a></li>
<li><a href="https://windows11.techidaily.com/upgrade-your-win11s-connectivity-with-these-high-priority-solutions/"><u>Upgrade Your Win11's Connectivity with These High-Priority Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-constant-calculator-positioning-on-pcs/"><u>Optimizing Constant Calculator Positioning on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-for-an-effortless-in-place-windows-11-revamp/"><u>Step-by-Step Guide for an Effortless, In-Place Windows 11 Revamp</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-photo-resizing-on-windows-11-6-steps/"><u>The Ultimate Guide to Photo Resizing on Windows 11 – 6 Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/speedy-boot-ups-in-windows-11-discover-the-best-practices/"><u>Speedy Boot-Ups in Windows 11 – Discover the Best Practices</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-default-windows-preferences-post-restart/"><u>Reviving Default Windows Preferences Post-Restart</u></a></li>
<li><a href="https://windows11.techidaily.com/revealing-the-make-of-your-windows-machine-in-six-steps/"><u>Revealing the Make of Your Windows Machine in Six Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/altering-winterrals-visual-theme/"><u>Altering WinTerral's Visual Theme</u></a></li>
<li><a href="https://techidaily.com/video-file-repair-how-to-fix-corrupted-video-files-of-infinix-hot-30-5g-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>Video File Repair - How to Fix Corrupted video files of Infinix Hot 30 5G on Mac?</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-find-your-fit-top-10-youtube-channels-for-yogic-health-for-2024/"><u>[Updated] Find Your Fit  Top 10 YouTube Channels for Yogic Health for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/fix-the-error-of-unfortunately-the-processcomandroidphone-has-stopped-on-motorola-g54-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix the Error of Unfortunately the Process.com.android.phone Has Stopped on Motorola G54 5G | Dr.fone</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-overcoming-the-challenge-of-acoustic-reflections-in-sound-engineering/"><u>2024 Approved Overcoming the Challenge of Acoustic Reflections in Sound Engineering</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/onvert-with-confidence-best-apps-to-turn-spotify-into-youtube-channels-for-2024/"><u>[New] Convert with Confidence  Best Apps to Turn Spotify Into YouTube Channels for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-laugh-riot-on-tiktok-unveiling-the-best-jokes-and-riddles/"><u>[Updated] In 2024, Laugh Riot on TikTok  Unveiling the Best Jokes and Riddles</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-make-your-moments-shine-best-highlight-video-makers-for-desktop-and-mobile/"><u>Updated In 2024, Make Your Moments Shine Best Highlight Video Makers for Desktop and Mobile</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-anime-for-every-moment-the-ultimate-list-of-youtube-sources/"><u>2024 Approved  Anime for Every Moment  The Ultimate List of YouTube Sources</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-premier-roundup-2023s-top-free-video-editing-apps/"><u>2024 Approved  Premier Roundup  2023'S Top Free Video Editing Apps</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-movavi-video-pro-review-release/"><u>[New] Movavi Video Pro Review Release</u></a></li>
</ul></div>
