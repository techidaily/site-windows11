---
title: "Maximizing Security: Activating TPM & Secure Boot for Windows 11 Upgrades"
date: 2024-09-09T11:58:18.524Z
updated: 2024-09-10T11:58:18.524Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Maximizing Security: Activating TPM & Secure Boot for Windows 11 Upgrades"
excerpt: "This Article Describes Maximizing Security: Activating TPM & Secure Boot for Windows 11 Upgrades"
keywords: Windows 11 Security Boost,Enhance PC Safety,TPM in Windows Upgrade,Secure Boot Activation,Win11 TPM Compliance,Steady System Protection,Secure Windows 11 Update
thumbnail: https://thmb.techidaily.com/69a1f779573ffb1d9703aa1f0c2a82407b77bc35052e19faef90f3eeabcd3dc4.jpg
---

## Maximizing Security: Activating TPM & Secure Boot for Windows 11 Upgrades

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115915/19272" target="_top" id="2115915">
  <img src="//a.impactradius-go.com/display-ad/19272-2115915" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115915/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Quick Links

* [What Are Secure Boot and TPM?](#what-are-secure-boot-and-tpm)
* [How to Enable TPM and Secure Boot](#how-to-enable-tpm-and-secure-boot)
* [Use Microsoft's PC Health Check App to Check If Your Hardware Is Compatible](#use-microsoft-39-s-pc-health-check-app-to-check-if-your-hardware-is-compatible)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135395/19272" target="_top" id="2135395">
  <img src="//a.impactradius-go.com/display-ad/19272-2135395" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135395/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Key Takeaways

* Windows 11 requires specific hardware, including AMD Ryzen 3000 series or Intel 7th Gen CPU or better, TPM, and Secure Boot.
* TPM is a hardware-level security solution that protects data from hacking, while Secure Boot prevents unauthorized operating systems from booting up.
* You can enable TPM and Secure Boot in your BIOS/UEFI settings, but be aware that Secure Boot may prevent dual-booting and updates on unsupported hardware.

 Considering upgrading to Windows 11? There are a couple of requirements that might stop you in your tracks. We'll explain how to know if your hardware will pass Windows 11's checks.

 First up is your physical hardware. If you're not using an AMD Ryzen 3000 series or Intel 7th Gen CPU or better, neither a clean Windows 11 installation nor the Windows 10 upgrade path will work. Second, if your computer doesn't support Secure Boot and TPM, you'll also fall at the initial hurdle. However, all is not lost because you can switch on Secure Boot and TPM from your BIOS/UEFI menu.

<!-- affiliate ads begin -->
<a href="https://smilemakers.pxf.io/c/5597632/2123899/26106" target="_top" id="2123899">
  <img src="//a.impactradius-go.com/display-ad/26106-2123899" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://smilemakers.pxf.io/i/5597632/2123899/26106" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123509/26400" target="_top" id="2123509">
  <img src="//a.impactradius-go.com/display-ad/26400-2123509" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123509/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### How to Enter Your BIOS/UEFI

 There are a couple of ways to enter your system BIOS/UEFI. The old tried and tested method of [tapping a keyboard key during bootup](https://www.makeuseof.com/tag/enter-bios-computer/) still works, but you might not get the chance if you have fast boot enabled. If the boot screens whizz past and you end up in Windows 10, there is another way you can access the BIOS:

1. Head to **Settings > Update & Security > Recovery > Restart now**.
2. When your computer restarts, you'll see a big blue screen with several options. Select **Troubleshoot > Advanced Options > UEFI Firmware Settings > Restart**.

 You should be in your BIOS/UEFI settings menu when the computer restarts again.

### How to Enable TPM in Your BIOS/UEFI

 The location of the TPM settings in your BIOS will differ depending on your motherboard manufacturer. The following images are taken from an X570 MSI motherboard, though where you find the TPM option won't necessarily be similar.

![msi motherboard enable tpm settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/msi-motherboard-enable-tpm-settings.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123470/16836" target="_top" id="2123470">
  <img src="//a.impactradius-go.com/display-ad/16836-2123470" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123470/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123740/7443" target="_top" id="2123740">
  <img src="//a.impactradius-go.com/display-ad/7443-2123740" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123740/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Note that Secure Boot requires your drives to use GUID Partition Table (GPT) rather than the older master boot record (MBR). As the newer partition table, GPT comes with several enhancements over MBR. If Secure Boot doesn't enable, you may need to [convert your MBR drive to GPT](http://www.makeuseof.com/tag/convert-mbr-gpt-windows/).

 Alternatively, your computer or hardware may be too old to enable Secure Boot.

## Use Microsoft's PC Health Check App to Check If Your Hardware Is Compatible

 Microsoft recommends using its [PC Health Check App](https://www.microsoft.com/en-us/windows/windows-11?r=1), which you'll find at the bottom of the linked page, to check for hardware compatibility. Download and fire it up to check your system's compatibility with Windows 11\.

 Alternatively, you could check out [WhyNotWin11](https://github.com/rcmaehl/WhyNotWin11/releases/), an open-source alternative that may provide more detailed insight into your Windows 11 compatibility.

 So there you have it. You've enabled two of the most important settings that will block your Windows 11 upgrade path. Once enabled, and presuming you're running compatible hardware, Microsoft will offer you the Windows 11 upgrade. To check if your Windows 11 upgrade is ready, head to **Settings > Update & Security > Windows Update**, where you'll find the big update button.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-web.techidaily.com/asy-access-luxury-free-access-to-your-dreamset-of-50-banners-in-2024/"><u>[New] Easy-Access Luxury - Free Access to Your Dreamset of 50 Banners, In 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-top-picks-of-engaging-click-based-pc-gaming-for-2024/"><u>[New] Top Picks of Engaging Click-Based PC Gaming for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-creative-anime-characters-and-scenes-for-viral-tiktoks-for-2024/"><u>[Updated] Creative Anime Characters & Scenes for Viral TikToks for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-perfect-your-virtual-meeting-vibes-google-meet-background-tips/"><u>2024 Approved  Perfect Your Virtual Meeting Vibes  Google Meet Background Tips</u></a></li>
<li><a href="https://tech-haven.techidaily.com/battling-bots-a-comparison-of-googles-bard-and-microsofts-bing-chat/"><u>Battling Bots: A Comparison of Google's Bard and Microsoft's Bing Chat</u></a></li>
<li><a href="https://windows11.techidaily.com/find-and-fix-your-missing-camera-on-device-screen/"><u>Find & Fix Your Missing Camera on Device Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-fixing-inaccessible-click-areas-in-windows-11/"><u>Guide to Fixing Inaccessible Click Areas in Windows 11</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/hangul-basics-effortlessly-embrace-the-korean-language/"><u>Hangul Basics: Effortlessly Embrace the Korean Language</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-webcam-camera-error-code-0xa00f4289-in-windows-11-and-11/"><u>How to Fix the Webcam Camera Error Code 0xA00F4289 in Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-maximize-your-windows-11-understanding-copilot-key-benefits/"><u>How to Maximize Your Windows 11: Understanding Copilot Key Benefits</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-easy-ways-to-manage-your-motorola-moto-g14-location-settings-drfone-by-drfone-virtual/"><u>In 2024, Easy Ways to Manage Your Motorola Moto G14 Location Settings | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-the-updated-method-to-bypass-poco-f5-pro-5g-frp-by-drfone-android/"><u>In 2024, The Updated Method to Bypass Poco F5 Pro 5G FRP</u></a></li>
<li><a href="https://windows11.techidaily.com/integrating-oracles-jvm-in-windows-11-pro-edition/"><u>Integrating Oracle's JVM in Windows 11 Pro Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/interpreting-complex-group-policies-on-windows-in-three-phases/"><u>Interpreting Complex Group Policies on Windows in Three Phases</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-configuration-your-journey-with-w11-and-pc-manager/"><u>Mastering Configuration: Your Journey With W11 & PC Manager</u></a></li>
<li><a href="https://program-issues.techidaily.com/mastering-discord-display-issues-eliminate-the-black-screen-error-when-sharing-your-screen/"><u>Mastering Discord Display Issues: Eliminate the Black Screen Error When Sharing Your Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/non-edge-processes-and-their-role-in-tasking/"><u>Non-Edge Processes and Their Role in Tasking</u></a></li>
<li><a href="https://windows11.techidaily.com/non-procreate-windows-drawers-the-top-five/"><u>Non-Procreate Windows Drawers: The Top Five</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-steam-stream-disconnects-on-pc/"><u>Overcoming Steam Stream Disconnects on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/overriding-read-only-protection-for-windows-files/"><u>Overriding Read-Only Protection for Windows Files</u></a></li>
<li><a href="https://windows11.techidaily.com/overturning-modern-windows-11-search-for-classic-icons/"><u>Overturning Modern Windows 11 Search for Classic Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-the-error-roblox-inaccessible-due-to-user-configuration/"><u>Resolving the Error: Roblox Inaccessible Due to User Configuration</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-unopened-shares-in-geforce-for-w10w11-users/"><u>Resolving Unopened Shares in GeForce for W10/W11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-setup-of-microsoft-works-on-windows-10-and-11/"><u>Seamless Setup of Microsoft Works on WIndows 10 and 11</u></a></li>
<li><a href="https://location-social.techidaily.com/set-your-preferred-job-location-on-linkedin-app-of-your-oneplus-ace-3-drfone-by-drfone-virtual-android/"><u>Set Your Preferred Job Location on LinkedIn App of your OnePlus Ace 3 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/simplified-systems-choose-windows-11-tiny/"><u>Simplified Systems: Choose Windows 11 Tiny</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/by-step-guide-to-youtube-video-editing-mastery/"><u>Step by Step Guide to YouTube Video Editing Mastery</u></a></li>
<li><a href="https://windows11.techidaily.com/subtle-enhancements-stealthy-menu-edits-windows-edition/"><u>Subtle Enhancements: Stealthy Menu Edits, Windows Edition</u></a></li>
<li><a href="https://win-solutions.techidaily.com/successfully-installing-and-playing-tiny-tinas-wonderlands-on-your-pc-troubleshooting-guide/"><u>Successfully Installing and Playing Tiny Tina's Wonderlands on Your PC - Troubleshooting Guide</u></a></li>
<li><a href="https://facebook.techidaily.com/tailoring-your-facebook-memories-selective-visibility/"><u>Tailoring Your Facebook Memories: Selective Visibility</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-guide-not-detected-headphones-in-windows-11-media-control-panel/"><u>Troubleshooting Guide: Not Detected Headphones in Windows 11 Media Control Panel</u></a></li>
<li><a href="https://windows11.techidaily.com/turbo-charging-steam-downloads-a-windows-guide/"><u>Turbo-Charging Steam Downloads: A Windows Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/unexpected-guests-unrelated-processes-with-edge/"><u>Unexpected Guests: Unrelated Processes with Edge</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-power-of-three-column-widgets-in-win11/"><u>Unlocking the Power of Three-Column Widgets in Win11</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>