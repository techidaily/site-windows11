---
title: Clearing Up Color Issues in Legacy BIOS
date: 2024-07-11T22:22:38.604Z
updated: 2024-07-12T22:22:38.604Z
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

 To fix the issue, try to [disable Modern Standby on your Windows computer](https://www.makeuseof.com/windows-disable-modern-standby/) . Once disabled, restart your PC to see if you can switch to Legacy Boot now.

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
<li><a href="https://windows11.techidaily.com/conquering-oculus-install-error-on-wincx-a-helpful-guide/"><u>Conquering Oculus Install Error on WinCX: A Helpful Guide</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-mapping-out-the-next-wave-of-social-media-graphs/"><u>[Updated] Mapping Out the Next Wave of Social Media Graphs</u></a></li>
<li><a href="https://windows11.techidaily.com/cooling-down-your-windows-11-computer/"><u>Cooling Down Your Windows 11 Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/converting-batch-files-into-executable-formats-on-pcs/"><u>Converting Batch Files Into Executable Formats on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-a-driverirqlnotlessorequal-in-windows/"><u>Clearing Up A DRIVER_IRQL_NOT_LESS_OR_EQUAL in Windows</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-spotting-blocked-contacts-in-snapchat-for-2024/"><u>[Updated] Spotting Blocked Contacts in Snapchat for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/creating-personalized-music-cds-with-mp3s-a-compreenasive-guide-for-windows-users-imgburn/"><u>Creating Personalized Music CDs with Mp3s: A Compreenasive Guide for Windows Users (ImgBurn)</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-integrating-dialogue-and-effects-advanced-audio-editing-with-premiere-pro-for-2024/"><u>Updated Integrating Dialogue & Effects Advanced Audio Editing with Premiere Pro for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-phonelinkexe-important-for-windows-users/"><u>Disabling PhoneLink.exe: Important for Windows Users?</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-windows-steam-blackout-immediate-solutions/"><u>Combatting Windows Steam Blackout: Immediate Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/dealing-with-windows-update-error-code-0x8024800c/"><u>Dealing with Windows Update: Error Code 0X8024800C</u></a></li>
<li><a href="https://windows11.techidaily.com/debunking-top-reasons-win11-beats-macos/"><u>Debunking: Top Reasons Win11 Beats macOS</u></a></li>
<li><a href="https://windows11.techidaily.com/diving-deep-using-the-netstat-command-in-windows-11-os/"><u>Diving Deep: Using the Netstat Command in Windows 11 OS</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-unlimited-video-editing-top-10-free-online-editors-with-no-watermark/"><u>Updated Unlimited Video Editing Top 10 Free Online Editors with No Watermark</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-compare-and-contrast-the-creme-de-la-creme-of-free-edits/"><u>In 2024, Compare and Contrast  The Crème De La Crème of Free Edits</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/engage-audiences-with-these-top-20-tiktok-caption-strategies-for-2024/"><u>Engage Audiences with These Top 20 TikTok Caption Strategies for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/discovering-windows-11-browser-configuration/"><u>Discovering Windows 11 Browser Configuration</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-auditory-decline-trends-in-adobe-rush-update-2023/"><u>New Auditory Decline Trends in Adobe Rush Update 2023</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-your-command-prompt-palette/"><u>Customizing Your Command Prompt Palette</u></a></li>
<li><a href="https://techidaily.com/is-your-nubia-z50-ultra-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Nubia Z50 Ultra working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-unveiling-new-era-youtube-hits-past-vidcon/"><u>In 2024, Unveiling New Era  YouTube Hits Past VidCon</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-cutting-edge-tools-the-best-9-gif-recorders-for-animated-windows-content/"><u>2024 Approved  Cutting-Edge Tools  The Best 9 GIF Recorders for Animated Windows Content</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-mastering-pcmobile-video-filter-techniques/"><u>[New] Mastering PC/Mobile Video Filter Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-interval-for-automatic-logoff/"><u>Customizing Interval for Automatic Logoff</u></a></li>
<li><a href="https://windows11.techidaily.com/defeating-wows-catastrophic-crashes-eradicate-error-132/"><u>Defeating WOW's Catastrophic Crashes: Eradicate Error 132</u></a></li>
<li><a href="https://location-fake.techidaily.com/8-solutions-to-fix-find-my-friends-location-not-available-on-vivo-v30-lite-5g-drfone-by-drfone-virtual-android/"><u>8 Solutions to Fix Find My Friends Location Not Available On Vivo V30 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/attracting-eyes-with-these-6-video-genres-for-2024/"><u>Attracting Eyes with These 6 Video Genres for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/decreasing-high-cpu-drain-tips-for-vanguards-user-mode-service/"><u>Decreasing High CPU Drain: Tips for Vanguard's User-Mode Service</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-icloud-unlocker-download-unlock-icloud-lock-for-your-iphone-13-by-drfone-ios/"><u>In 2024, iCloud Unlocker Download Unlock iCloud Lock for your iPhone 13</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-arcadearchive-annotator-for-2024/"><u>[Updated] ArcadeArchive Annotator for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-vintage-of-a-windows-pc/"><u>Deciphering Vintage of a Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-microsofts-code-companion-for-enhanced-programming/"><u>Demystifying Microsoft's Code Companion for Enhanced Programming</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-windows-servers-resolving-no-servers-found-in-apex-legends-(156-chars/"><u>Conquer Windows Servers: Resolving No Servers Found in Apex Legends (<156 Chars)</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-essential-gear-picking-the-very-best-among-top-9-free-logomakers/"><u>[Updated] Essential Gear  Picking the Very Best Among Top 9 Free Logomakers</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-camera-glitch-solve-error-a00f4289-on-pcs/"><u>Disabling Camera Glitch: Solve Error A00F4289 on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-secondary-apps-camera-usage-error-0xa00f4243/"><u>Disabling Secondary App's Camera Usage (Error 0xA00F4243)</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/by-accident-tiktok-rewind-restore-lost-content/"><u>By Accident, TikTok Rewind  Restore Lost Content?</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-premiered-5-screen-options-for-ps5-gamers/"><u>2024 Approved  Premiered 5 Screen Options for PS5 Gamers</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-admin-settings-causing-windows-security-failsafe/"><u>Disabling Admin Settings Causing Windows Security Failsafe</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-storage-alerts-and-errors-on-windows/"><u>Clearing Up Storage Alerts & Errors on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehending-cab-files-within-the-windows-ecosystem/"><u>Comprehending CAB Files Within the Windows Ecosystem</u></a></li>
</ul></div>
