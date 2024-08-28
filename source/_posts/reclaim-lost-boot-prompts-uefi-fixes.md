---
title: "Reclaim Lost Boot Prompts: UEFI Fixes"
date: 2024-08-27T16:02:22.538Z
updated: 2024-08-28T16:02:22.538Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Reclaim Lost Boot Prompts: UEFI Fixes"
excerpt: "This Article Describes Reclaim Lost Boot Prompts: UEFI Fixes"
keywords: Reclaiming Boot Issues,UEFI Troubleshooting,Restore Boot Prompts,Loss of Boots Prompt,Fixed UEFI Errors,Boot System Repair,Regain Boot Starts
thumbnail: https://thmb.techidaily.com/ceeb71131f67470128687850a84b0078790624844b7b52caccd45c8365ecdd85.jpg
---

## Reclaim Lost Boot Prompts: UEFI Fixes

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

<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. Disable Trusted Platform Technology (TPM)

![disable TPM state BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-tpm-state-bios-1.jpg)

<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 In addition to Secure Boot, you may also have enabled Trusted Platform Module (TPM), disabling Legacy BIOS. To fix the issue, check if TPM is enabled on your PC, which is likely a case on a Windows 11 running system, and disable the option if necessary.

 You can disable TPM from the BIOS setup utility. Here's how to do it.

1. Boot into your BIOS utility using the**Windows Recovery Menu.**
2. Next, open the**Security** tab using the right and left arrow keys.
3. Highlight the**TPM State** option and press**Enter** . If no TPM option is available, look for the**PTT** option.
4. Select**Disabled** to disable TPM on your device.
5. Press**F10** to save the change and exit.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4693127&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.videosoftdev.com/images/video_editor/screenshots/1.jpg" border="0">
VSDC Pro Video Editor is a light professional non-linear video editing suite for creating a movie of any complexity. It supports the most popular video/audio formats and codecs, including 4K, HD and GoPro videos. Preconfigured profiles make the creation of videos for various multimedia and mobile devices absolutely hassle-free.

Key features:

•	Import from any devices and cams, including GoPro and drones. All formats supported. Сurrently the only free video editor that allows users to export in a new H265/HEVC codec, something essential for those working with 4K and HD.
•	Everything for hassle-free basic editing: cut, crop and merge files, add titles and favorite music
•	Visual effects, advanced color correction and trendy Instagram-like filters   
•	All multimedia processing done from one app: video editing capabilities reinforced by  a video converter, a screen capture, a video capture, a disc burner and a YouTube uploader
•	Non-linear editing: edit several files with simultaneously 
•	Easy export to social networks: special profiles for YouTube, Facebook, Vimeo, Twitter and Instagram
•	High quality export – no conversion quality loss, double export speed even of HD files due to hardware acceleration
•	Stabilization tool will turn shaky or jittery footage into a more stable video automatically. 
•	Essential toolset for professional video editing: blending modes, Mask tool, advanced multiple-color Chroma Key  
</a>
<!-- affiliate ads end -->
## 3\. Disable Modern Standby

 Modern Standby (S0) is a newer power mode available on select modern computers. It is enabled by default on compatible systems but can cause issues with Legacy Boot.

 To fix the issue, try to[disable Modern Standby on your Windows computer](https://www.makeuseof.com/windows-disable-modern-standby/) . Once disabled, restart your PC to see if you can switch to Legacy Boot now.

<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
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
<li><a href="https://instagram-video-recordings.techidaily.com/new-mastering-video-editing-for-social-media-standout/"><u>[New] Mastering Video Editing for Social Media Standout</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-achieving-flawless-gameplay-optimizing-your-switch-pro-experience-on-steam-for-2024/"><u>[Updated] Achieving Flawless Gameplay  Optimizing Your Switch Pro Experience on Steam for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-mastering-close-up-views-on-ms-teams/"><u>[Updated] Mastering Close-Up Views on MS Teams</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-shadows-and-highlights-for-text-depth-in-illustrator/"><u>[Updated] Shadows & Highlights for Text Depth in Illustrator</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-anonymity-in-action-insta-stories-guide/"><u>2024 Approved  Anonymity in Action  Insta Stories Guide</u></a></li>
<li><a href="https://location-fake.techidaily.com/6-ways-to-change-spotify-location-on-your-infinix-note-30i-drfone-by-drfone-virtual-android/"><u>6 Ways to Change Spotify Location On Your Infinix Note 30i | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/a-peek-behind-windows-curtain-top-30-undisclosed-tips-for-windows-11/"><u>A Peek Behind Window's Curtain  Top 30 Undisclosed Tips for Windows 11</u></a></li>
<li><a href="https://android-frp.techidaily.com/addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-realme-narzo-60-pro-5g-by-drfone-android/"><u>AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Realme Narzo 60 Pro 5G</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/easy-installation-guide-for-updated-drivers-of-hp-officejet-5255/"><u>Easy Installation Guide for Updated Drivers of HP OfficeJet 5255</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-how-to-activating-hyper-v-for-win11-users/"><u>Essential How-To: Activating Hyper-V for Win11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/fast-track-to-enabling-telnet-in-win11-pcs/"><u>Fast Track to Enabling Telnet in Win11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-roblox-on-screen-stop-issues-on-windows-systems/"><u>Fixing Roblox On-Screen Stop Issues on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-a-portable-software-menu-to-windows-10-and-11/"><u>How to Add a Portable Software Menu to Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-blackouts-during-win-based-gameplay/"><u>How to Fix Blackouts During Win-Based Gameplay</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-irq-problems-with-your-soundcard-on-windows/"><u>How to Fix IRQ Problems With Your Soundcard on Windows</u></a></li>
<li><a href="https://win-able.techidaily.com/how-to-prevent-dead-by-daylight-from-crashing-expert-tips/"><u>How To Prevent Dead By Daylight From Crashing : Expert Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-rectify-unmovable-scrolling-in-excel-windows/"><u>How to Rectify Unmovable Scrolling in Excel (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-salvage-your-failed-zip-extraction-in-windows-11/"><u>How To Salvage Your Failed ZIP Extraction in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/muting-mayhem-reverse-sound-suppression-in-windows/"><u>Muting Mayhem? Reverse Sound Suppression in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-and-understanding-how-to-use-imessage-on-your-computer/"><u>Navigating and Understanding How to Use iMessage on Your Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-windows-11-registry-for-obscured-themes/"><u>Navigating the Windows 11 Registry for Obscured Themes</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-unlock-efficient-video-editing-6-essential-adobe-premiere-pro-tips/"><u>New Unlock Efficient Video Editing 6 Essential Adobe Premiere Pro Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/recover-lost-audio-output-in-non-responsive-os/"><u>Recover Lost Audio Output in Non-Responsive OS</u></a></li>
<li><a href="https://windows11.techidaily.com/redesigned-navigation-top-7-updates-to-window-11s-file-explorer/"><u>Redesigned Navigation: Top 7 Updates to Window 11'S File Explorer</u></a></li>
<li><a href="https://win-blog.techidaily.com/resolving-the-issue-internet-explorer-is-not-responding/"><u>Resolving the Issue: 'Internet Explorer Is Not Responding'</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-browsing-at-fingertips-activating-gestures-in-microsoft-edge-win-11-edition/"><u>Seamless Browsing at Fingertips: Activating Gestures in Microsoft Edge, Win 11 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/spotting-the-green-light-and-red-alert-windows-login-status/"><u>Spotting the Green Light & Red Alert: Windows Login Status</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/step-by-step-guide-private-yt-content-with-google-login/"><u>Step-by-Step Guide  Private YT Content with Google Login</u></a></li>
<li><a href="https://some-guidance.techidaily.com/subtle-sound-shifts-in-garageband-productions-for-2024/"><u>Subtle Sound Shifts in Garageband Productions for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/the-ultimate-playbook-youtube-gaming-success-for-2024/"><u>The Ultimate Playbook  YouTube Gaming Success for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-vision-enhancers-guide-top-9-remedies-for-blurry-displays/"><u>The Vision Enhancers' Guide: Top 9 Remedies for Blurry Displays</u></a></li>
<li><a href="https://windows11.techidaily.com/the-winning-package-tool-for-you-a-choco-vs-wm-quest/"><u>The Winning Package Tool for You: A Choco VS. WM Quest</u></a></li>
<li><a href="https://windows11.techidaily.com/top-tools-that-makes-your-laptops-os-change-more-manageable/"><u>Top Tools that Makes Your Laptop's OS Change More Manageable</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-airpods-windows-symbiosis/"><u>Unlocking AirPods-Windows Symbiosis</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-full-potential-of-your-systems-ram-with-windows/"><u>Unlocking the Full Potential of Your System's RAM with Windows</u></a></li>
</ul></div>
