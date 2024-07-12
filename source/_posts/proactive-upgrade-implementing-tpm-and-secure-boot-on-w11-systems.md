---
title: "Proactive Upgrade: Implementing TPM and Secure Boot on W11 Systems"
date: 2024-07-11T21:20:31.983Z
updated: 2024-07-12T21:20:31.983Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Proactive Upgrade: Implementing TPM and Secure Boot on W11 Systems"
excerpt: "This Article Describes Proactive Upgrade: Implementing TPM and Secure Boot on W11 Systems"
keywords: Proactive Security Update,Windows 11 Hardware Safeguard,TPM Integration for Win11,Implement Secure Boot on W11,Enhanced System Defense,Win11 Threat Prevention,Securing W11 Systems Better
thumbnail: https://thmb.techidaily.com/053654aac9195ea45d1f77852c408a3b2770cc6c802ff6728e9e3d8c452deddb.jpg
---

## Proactive Upgrade: Implementing TPM and Secure Boot on W11 Systems

### Quick Links

* [What Are Secure Boot and TPM?](#what-are-secure-boot-and-tpm)
* [How to Enable TPM and Secure Boot](#how-to-enable-tpm-and-secure-boot)
* [Use Microsoft's PC Health Check App to Check If Your Hardware Is Compatible](#use-microsoft-39-s-pc-health-check-app-to-check-if-your-hardware-is-compatible)

### Key Takeaways

* Windows 11 requires specific hardware, including AMD Ryzen 3000 series or Intel 7th Gen CPU or better, TPM, and Secure Boot.
* TPM is a hardware-level security solution that protects data from hacking, while Secure Boot prevents unauthorized operating systems from booting up.
* You can enable TPM and Secure Boot in your BIOS/UEFI settings, but be aware that Secure Boot may prevent dual-booting and updates on unsupported hardware.

 Considering upgrading to Windows 11? There are a couple of requirements that might stop you in your tracks. We'll explain how to know if your hardware will pass Windows 11's checks.

 First up is your physical hardware. If you're not using an AMD Ryzen 3000 series or Intel 7th Gen CPU or better, neither a clean Windows 11 installation nor the Windows 10 upgrade path will work. Second, if your computer doesn't support Secure Boot and TPM, you'll also fall at the initial hurdle. However, all is not lost because you can switch on Secure Boot and TPM from your BIOS/UEFI menu.

## What Are Secure Boot and TPM?

 The [Trusted Module Platform (TPM) is a hardware-level security solution](http://www.makeuseof.com/what-is-a-trusted-platform-module-tpm/) that protects your data from hacking and other data breaches. The TPM holds unique encryption keys stored in such a way that it is nearly impossible for a hacker to access. If someone breaches your computer and your data is encrypted, it will remain secure.

 Microsoft's recommended requirements for Windows 11 list TMP 2.0\. However, you can still upgrade using a previous version, TPM 1.2, which is the minimum requirement.

 Along with TPM 2.0, Microsoft also requires you to activate Secure Boot, a UEFI-level security setting that stops any unauthorized operating system from booting up. Secure Boot is effectively a gatekeeper, stopping malicious code from booting up before your system, and its primary goal is to protect against rootkits, bootkits, and other malicious code.

![windows bios secure boot warning](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/windows-bios-secure-boot-warning.jpg)

 But it also has some side effects. For example, Secure Boot will stop you from dual-booting Linux distributions, which has led many [users to disable Secure Boot.](https://www.makeuseof.com/tag/disable-secure-uefi-dual-boot/)

 On top of those two vital features, [Windows 11 has specific hardware requirements](https://www.makeuseof.com/can-your-pc-run-windows-11/), with Microsoft opting to block the automatic upgrade path for millions of users. If you're using Windows 10 on an AMD Ryzen 3000 series or later or an Intel 7th Gen CPU or later, you can upgrade to Windows 11 directly.

 However, if not, you'll have to opt for a [Windows 11 clean install](https://www.makeuseof.com/how-to-clean-install-windows-11/) or to [bypass Windows 11's minimum requirements](https://www.makeuseof.com/bypass-windows-11-minimum-installation-requirements/). A clean installation of Windows 11 will work on most hardware, but it does come with caveats. Notably, Microsoft has repeatedly stated that it will not provide updates to Windows 11 installations on "unsupported" hardware, so you install at your own risk.

## How to Enable TPM and Secure Boot

 Trusted Module Platform and Secure Boot are found in your UEFI settings. You'll have to enter system UEFI to enable them before attempting to upgrade to Windows 11\. Both settings are found in similar areas, but we'll break the steps down into three parts for ease of reading.

### How to Enter Your BIOS/UEFI

 There are a couple of ways to enter your system BIOS/UEFI. The old tried and tested method of [tapping a keyboard key during bootup](https://www.makeuseof.com/tag/enter-bios-computer/) still works, but you might not get the chance if you have fast boot enabled. If the boot screens whizz past and you end up in Windows 10, there is another way you can access the BIOS:

1. Head to **Settings > Update & Security > Recovery > Restart now**.
2. When your computer restarts, you'll see a big blue screen with several options. Select **Troubleshoot > Advanced Options > UEFI Firmware Settings > Restart**.

 You should be in your BIOS/UEFI settings menu when the computer restarts again.

### How to Enable TPM in Your BIOS/UEFI

 The location of the TPM settings in your BIOS will differ depending on your motherboard manufacturer. The following images are taken from an X570 MSI motherboard, though where you find the TPM option won't necessarily be similar.

![msi motherboard enable tpm settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/msi-motherboard-enable-tpm-settings.jpg)

 Be aware that the TPM might be listed under a different name on some motherboards, depending on your CPU manufacturer:

* Intel Platform Trust Technology (PTT)
* AMD fTMP

 On my motherboard, TPM options are found at **Settings > Security > Trusted Computing > TPM Device Selection**, where I'll switch on AMD fTMP.

 Once switched on, you can save the settings and return to Windows 10\. Once Windows boots, you can check your TPM status within the OS to ensure it's running properly.

 Press **Windows key + R** to open the Run dialog, then input **tpm.msc** and press Enter. The TPM management console will load, indicating if TPM is enabled—and if so, which version you're using.

### How to Enable Secure Boot

 While you're deep in your system settings, take a moment to check if Secure Boot is enabled.

 Like the TPM options, where you find the Secure Boot option will differ depending on hardware, but it is generally located in the **Boot** tab. Find your **Boot** tab, scroll down to find the **Secure Boot** option, and ensure it's enabled.

![msi motherboard enable secure boot settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/msi-motherboard-enable-secure-boot-settings.jpg)

 Note that Secure Boot requires your drives to use GUID Partition Table (GPT) rather than the older master boot record (MBR). As the newer partition table, GPT comes with several enhancements over MBR. If Secure Boot doesn't enable, you may need to [convert your MBR drive to GPT](http://www.makeuseof.com/tag/convert-mbr-gpt-windows/).

 Alternatively, your computer or hardware may be too old to enable Secure Boot.

## Use Microsoft's PC Health Check App to Check If Your Hardware Is Compatible

 Microsoft recommends using its [PC Health Check App](https://www.microsoft.com/en-us/windows/windows-11?r=1), which you'll find at the bottom of the linked page, to check for hardware compatibility. Download and fire it up to check your system's compatibility with Windows 11\.

 Alternatively, you could check out [WhyNotWin11](https://github.com/rcmaehl/WhyNotWin11/releases/), an open-source alternative that may provide more detailed insight into your Windows 11 compatibility.

 So there you have it. You've enabled two of the most important settings that will block your Windows 11 upgrade path. Once enabled, and presuming you're running compatible hardware, Microsoft will offer you the Windows 11 upgrade. To check if your Windows 11 upgrade is ready, head to **Settings > Update & Security > Windows Update**, where you'll find the big update button.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/optimizing-task-execution-on-windows-adding-an-improved-run-utility/"><u>Optimizing Task Execution on Windows: Adding an Improved Run Utility</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/the-art-of-hashtagging-strategies-for-maximum-impact-on-facebook/"><u>The Art of Hashtagging  Strategies for Maximum Impact on Facebook</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/selfies-on-snap-verifying-authenticity/"><u>Selfies on Snap  Verifying Authenticity</u></a></li>
<li><a href="https://windows11.techidaily.com/defining-new-default-for-reading-pdfs-on-pc/"><u>Defining New Default for Reading PDFs on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-sluggish-excel-experience/"><u>Fixing Windows' Sluggish Excel Experience</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-from-concept-to-reality-the-artisans-guide-to-lut-crafting/"><u>2024 Approved  From Concept to Reality  The Artisan's Guide to LUT Crafting</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/best-3-motorola-moto-g24-emulator-for-mac-to-run-your-wanted-android-apps-drfone-by-drfone-android/"><u>Best 3 Motorola Moto G24 Emulator for Mac to Run Your Wanted Android Apps | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-freeplayvid-seamless-recording-for-the-avid-player-for-2024/"><u>[Updated] FreePlayVid  Seamless Recording for the Avid Player for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-professional-drone-use-in-visual-storytelling/"><u>[New] Professional Drone Use in Visual Storytelling</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-managing-applications-with-wpm-in-windows-11/"><u>Efficiently Managing Applications with WPM in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-clear-pin-lockouts-with-ease/"><u>Windows 11: Clear PIN Lockouts with Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-troubleshooting-overcoming-error-e84-on-steam/"><u>Mastering the Art of Troubleshooting: Overcoming Error E84 on Steam</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-sim-unlock-xiaomi-redmi-note-12t-pro-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>In 2024, Sim Unlock Xiaomi Redmi Note 12T Pro Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-the-path-to-perfect-sims-video-sessions-for-2024/"><u>[New] The Path to Perfect Sims Video Sessions for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-remove-apple-iphone-14-pro-max-sim-lock-by-drfone-ios/"><u>How to Remove Apple iPhone 14 Pro Max SIM Lock?</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-wiped-messages-on-honor-magic-v2-by-fonelab-android-recover-messages/"><u>How to restore wiped messages on Honor Magic V2</u></a></li>
<li><a href="https://windows11.techidaily.com/the-easy-way-opening-sticky-notes-on-win11/"><u>The Easy Way: Opening Sticky Notes on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-windows-errors-top-10-diagnostic-aids/"><u>Decoding Windows Errors: Top 10 Diagnostic Aids</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-harness-the-power-of-imagery-top-7-free-thumbnail-makers/"><u>[Updated] Harness the Power of Imagery  Top 7 Free Thumbnail Makers</u></a></li>
<li><a href="https://windows11.techidaily.com/what-to-do-if-you-cant-access-your-router-page-or-web-interfaces-on-windows/"><u>What to Do if You Can't Access Your Router Page or Web Interfaces on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-usage-settings-on-windows-11-your-how-to-guide/"><u>Navigating Usage Settings on Windows 11: Your How-To Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/cure-for-hidden-second-display-on-w11/"><u>Cure for Hidden Second Display on W11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-efficiency-advanced-tips-for-task-juggling-in-windows-11/"><u>Unlock Efficiency: Advanced Tips for Task Juggling in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-swiftly-handle-stalled-gpsvc-process/"><u>How to Swiftly Handle Stalled GPSVC Process</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-mp3s-into-listenable-audio-cds-using-windows-and-imgburn-techniques/"><u>Optimizing MP3s Into Listenable Audio Cds Using Windows and ImgBurn Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-taskbar-history-from-start-to-now/"><u>Windows Taskbar History: From Start to Now</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-mend-the-destructive-js-error-in-discord-on-win-11-pcs/"><u>How to Mend the Destructive JS Error in Discord on Win 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-common-errors-in-microsoft-office-activation/"><u>Overcoming Common Errors in Microsoft Office Activation</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-organization-controlled-errors-in-windows-11-systems/"><u>Addressing Organization-Controlled Errors in Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/zeroing-in-on-error-0x800f0831-for-windows-repair/"><u>Zeroing in on Error 0X800F0831 for Windows Repair</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-transform-your-videos-a-beginners-guide-to-editing-with-windows-movie-maker/"><u>Updated 2024 Approved Transform Your Videos A Beginners Guide to Editing with Windows Movie Maker</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/palette-perfection-in-photoshop-top-3-efficient-techniques-for-2024/"><u>Palette Perfection in Photoshop  Top 3 Efficient Techniques for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/from-novice-to-pro-a-guide-to-github-desktop-and-windows-integration/"><u>From Novice to Pro: A Guide to GitHub Desktop & Windows Integration</u></a></li>
<li><a href="https://windows11.techidaily.com/1719346558796-why-your-pc-needs-only-one-guardian-antivirus-software/"><u>Why Your PC Needs Only One Guardian - Antivirus Software!</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-the-insiders-guide-to-youtube-success/"><u>[New] The Insider's Guide to YouTube Success</u></a></li>
<li><a href="https://windows11.techidaily.com/using-ports-without-built-in-pc-graphics-hardware/"><u>Using Ports Without Built-In PC Graphics Hardware</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-error-0x80070570-a-guide-for-fixed-damaged-files/"><u>Bypassing Error 0X80070570: A Guide for Fixed Damaged Files</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-tasks-effortlessly-top-8-pomodoro-timer-reviews-on-pc/"><u>Mastering Tasks Effortlessly - Top 8 Pomodoro Timer Reviews on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-ad-ds-printing-issues-in-windows-11-pro/"><u>Overcoming AD DS Printing Issues in Windows 11 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-for-fixing-nvidia-gui-sharing-glitches/"><u>Guide for Fixing NVIDIA GUI Sharing Glitches</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-steam-library-folder-editability-in-win-11/"><u>Enabling Steam Library Folder Editability in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/combat-apex-crashes-effective-solutions-for-windows-11-users/"><u>Combat Apex Crashes: Effective Solutions for Windows 11 Users</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/top-10-airplay-apps-in-tecno-spark-20-pro-for-streaming-drfone-by-drfone-android/"><u>Top 10 AirPlay Apps in Tecno Spark 20 Pro for Streaming | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-game-on-top-10-gaming-personalities-on-tiktok/"><u>[Updated] In 2024, Game On  Top 10 Gaming Personalities on TikTok</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-revive-non-starting-adobe-photoshop-on-ws11-and-11/"><u>How to Revive Non-Starting Adobe Photoshop on WS11 & 11</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-navigating-the-financial-landscape-for-podcasters/"><u>[New] Navigating the Financial Landscape for Podcasters</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-a-full-battery-charge-notification-to-windows-11-and-11/"><u>How to Add a Full Battery Charge Notification to Windows 11 & 11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/guide-to-uploading-videos-into-youtube-lists-for-2024/"><u>Guide to Uploading Videos Into YouTube Lists for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/controlling-winoss-priority-setting-for-hardware-acceleration/"><u>Controlling WinOS's Priority Setting for Hardware Acceleration</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-11-free-apps-to-check-imei-on-iphone-13-by-drfone-ios/"><u>Top 11 Free Apps to Check IMEI on iPhone 13</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-2024-approved-the-ultimate-guide-to-8-invaluable-sound-effects-from-the-gaming-realm/"><u>Updated 2024 Approved The Ultimate Guide to 8 Invaluable Sound Effects From the Gaming Realm</u></a></li>
<li><a href="https://windows11.techidaily.com/4-ways-to-flush-the-dns-cache-on-windows-11/"><u>4 Ways to Flush the DNS Cache on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-audio-recorder-snag-with-error-9999-solution/"><u>Navigating Windows' Audio Recorder Snag with Error 9999 Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-windows-11-programs-for-faster-startups/"><u>Optimizing Windows 11 Programs for Faster Startups</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-passfab-apple-iphone-xs-max-backup-unlocker-top-4-alternatives-by-drfone-ios/"><u>In 2024, PassFab Apple iPhone XS Max Backup Unlocker Top 4 Alternatives</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-stifling-random-cmd-entrance/"><u>Techniques for Stifling Random CMD Entrance</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/24-your-pathway-to-profit-the-most-straightforward-top-10-business-channels-on-youtube/"><u>In 2024, Your Pathway to Profit  The Most Straightforward Top 10 Business Channels on YouTube</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-7-phone-number-locators-to-track-vivo-y17s-location-drfone-by-drfone-virtual-android/"><u>Top 7 Phone Number Locators To Track Vivo Y17s Location | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-chromes-non-downloading-problems-on-windows/"><u>Addressing Chrome's Non-Downloading Problems on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-in-use-device-naming-5-fixes-for-windows-errors/"><u>Avoiding In-Use Device Naming: 5 Fixes for Windows Errors</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-the-ultimate-guide-to-free-mod-video-editing-software/"><u>In 2024, The Ultimate Guide to Free MOD Video Editing Software</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-virtualbox-0x80004005-failure-on-windows-pcs/"><u>Addressing VirtualBox 0X80004005 Failure on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-inoperative-drive-not-detected-by-os/"><u>Fixing Inoperative Drive Not Detected by OS</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-2024-approved-adding-a-spooky-shadow-effect-with-filmora/"><u>Updated 2024 Approved Adding a Spooky Shadow Effect with Filmora</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-your-honor-play-7t-location-on-twitter-drfone-by-drfone-virtual-android/"><u>How to Change your Honor Play 7T Location on Twitter | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/curated-list-premium-android-collage-apps/"><u>Curated List  Premium Android Collage Apps</u></a></li>
</ul></div>
