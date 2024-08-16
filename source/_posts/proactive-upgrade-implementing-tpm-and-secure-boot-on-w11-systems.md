---
title: "Proactive Upgrade: Implementing TPM and Secure Boot on W11 Systems"
date: 2024-08-15T16:11:36.060Z
updated: 2024-08-16T16:11:36.060Z
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4531356&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8fdd149fcaa7058caccc9c4ad5b0d89a/products/tss-box.JPG" border="0">The Tube Sites Submitter is a fast and efficient tool for anyone who needs to upload videos quickly, easily and automatically to hundreds of tube sites in mere minutes . </a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### How to Enable TPM in Your BIOS/UEFI

 The location of the TPM settings in your BIOS will differ depending on your motherboard manufacturer. The following images are taken from an X570 MSI motherboard, though where you find the TPM option won't necessarily be similar.

![msi motherboard enable tpm settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/msi-motherboard-enable-tpm-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->

 Be aware that the TPM might be listed under a different name on some motherboards, depending on your CPU manufacturer:

* Intel Platform Trust Technology (PTT)
* AMD fTMP

 On my motherboard, TPM options are found at **Settings > Security > Trusted Computing > TPM Device Selection**, where I'll switch on AMD fTMP.

 Once switched on, you can save the settings and return to Windows 10\. Once Windows boots, you can check your TPM status within the OS to ensure it's running properly.

 Press **Windows key + R** to open the Run dialog, then input **tpm.msc** and press Enter. The TPM management console will load, indicating if TPM is enabled—and if so, which version you're using.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
### How to Enable Secure Boot

 While you're deep in your system settings, take a moment to check if Secure Boot is enabled.

 Like the TPM options, where you find the Secure Boot option will differ depending on hardware, but it is generally located in the **Boot** tab. Find your **Boot** tab, scroll down to find the **Secure Boot** option, and ensure it's enabled.

![msi motherboard enable secure boot settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/msi-motherboard-enable-secure-boot-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Note that Secure Boot requires your drives to use GUID Partition Table (GPT) rather than the older master boot record (MBR). As the newer partition table, GPT comes with several enhancements over MBR. If Secure Boot doesn't enable, you may need to [convert your MBR drive to GPT](http://www.makeuseof.com/tag/convert-mbr-gpt-windows/).

 Alternatively, your computer or hardware may be too old to enable Secure Boot.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
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
<li><a href="https://youtube-zero.techidaily.com/irst-steps-in-filmmaking-essentials-for-new-youtube-talents/"><u>[New] First Steps in Filmmaking  Essentials for New YouTube Talents</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-photo-care-essentials-scanning-and-securing-vintage-prints/"><u>[New] Photo Care Essentials  Scanning & Securing Vintage Prints</u></a></li>
<li><a href="https://location-fake.techidaily.com/11-best-location-changers-for-nokia-105-classic-drfone-by-drfone-virtual-android/"><u>11 Best Location Changers for Nokia 105 Classic | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-decoding-facebooks-absence-of-personalized-video-content/"><u>2024 Approved  Decoding Facebook's Absence of Personalized Video Content</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-error-code-963-on-google-play-of-motorola-moto-g24-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Error Code 963 on Google Play Of Motorola Moto G24 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/8-essential-fixes-for-resistant-windows-pin-locks/"><u>8 Essential Fixes for Resistant Windows PIN Locks</u></a></li>
<li><a href="https://windows11.techidaily.com/a-compre-written-in-the-stars-mastering-your-laptops-touchscreen-precision/"><u>A Compre Written in the Stars: Mastering Your Laptop’s Touchscreen Precision</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-prints-with-microsoft-smartscreen-security-feature/"><u>Activating Prints with Microsoft SmartScreen Security Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-how-you-handle-deleted-items-on-pc/"><u>Adjusting How You Handle Deleted Items on PC</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-locked-or-disabled-from-iphone-6s-plus-7-mehtods-you-cant-miss-by-drfone-ios/"><u>Apple ID Locked or Disabled From iPhone 6s Plus? 7 Mehtods You Cant-Miss</u></a></li>
<li><a href="https://windows11.techidaily.com/asus-challenges-rog-ally-with-innovative-designs/"><u>ASUS Challenges ROG Ally with Innovative Designs</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-complications-resetting-terminal-on-win11/"><u>Avoid Complications: Resetting Terminal on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/becoming-proficient-with-windows-odbc-control-panel/"><u>Becoming Proficient with Windows' ODBC Control Panel</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-performance-with-windows-11-power-options/"><u>Boost Performance with Windows 11 Power Options</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-fps-supercharge-yuzu-for-windows/"><u>Boosting FPS: Supercharge Yuzu for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/bridging-software-generations-windows-7-key-for-11-boot/"><u>Bridging Software Generations: Windows 7 Key for 11 Boot</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-game-freeze-with-these-tips/"><u>Bypassing Game Freeze with These Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-overload-on-windows-applications-0x80860010/"><u>Bypassing Overload on Windows Applications (0X80860010)</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-tpm-in-win11-the-ultimate-rufus-technique/"><u>Bypassing TPM in Win11: The Ultimate Rufus Technique</u></a></li>
<li><a href="https://windows11.techidaily.com/cleanse-your-screen-history-3-strategies/"><u>Cleanse Your Screen History - 3 Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/coalescing-file-structures-a-windows-guide/"><u>Coalescing File Structures, A Windows Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-an-efficient-menu-choice-for-regular-system-checks-on-win11plus11/"><u>Crafting an Efficient Menu Choice for Regular System Checks on Win11+11</u></a></li>
<li><a href="https://windows11.techidaily.com/create-efficiency-in-windows-unique-snapping-layouts-with-powertoys/"><u>Create Efficiency in Windows: Unique Snapping Layouts with PowerToys</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-minimummax-cpu-in-power-preferences/"><u>Deciphering Minimum/Max CPU in Power Preferences</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-dealing-with-steam-installation-fiascos-win11-style/"><u>Decoding and Dealing with Steam Installation Fiascos, Win11-Style</u></a></li>
<li><a href="https://windows11.techidaily.com/direct-paths-opening-system-information-at-your-fingertips/"><u>Direct Paths: Opening System Information at Your Fingertips</u></a></li>
<li><a href="https://windows11.techidaily.com/disable-windows-11s-covert-surveillance/"><u>Disable Windows 11'S Covert Surveillance</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-phonelinkexe-important-for-windows-users/"><u>Disabling PhoneLink.exe: Important for Windows Users?</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/expressing-thanks-top-outro-templates-collection/"><u>Expressing Thanks  Top Outro Templates Collection</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-top-15-augmented-reality-games-like-pokemon-go-to-play-on-vivo-y100i-drfone-by-drfone-virtual-android/"><u>In 2024, Top 15 Augmented Reality Games Like Pokémon GO To Play On Vivo Y100i | Dr.fone</u></a></li>
<li><a href="https://driver-download.techidaily.com/update-your-microsoft-bluetooth-software-today-download-for-win-111087/"><u>Update Your Microsoft Bluetooth Software Today - Download for Win 11/10/8/7</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/windows-10-speaks-a-summary-of-recent-additions/"><u>Windows 10 Speaks  A Summary of Recent Additions</u></a></li>
</ul></div>
