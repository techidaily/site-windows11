---
title: Curing Stale BOOT Option Imagery
date: 2024-07-11T21:44:22.091Z
updated: 2024-07-12T21:44:22.091Z
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
<li><a href="https://some-techniques.techidaily.com/guides-to-unearthing-elite-cinematography-for-2024/"><u>Guides to Unearthing Elite Cinematography for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/unlocking-the-code-to-content-creator-commerce-with-carminati-ajay/"><u>Unlocking the Code to Content Creator Commerce with Carminati (AJay)</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerate-filenames-processing-with-powertoys/"><u>Accelerate Filenames Processing with PowerToys</u></a></li>
<li><a href="https://windows11.techidaily.com/breathing-life-into-your-dormant-windows-mouse/"><u>Breathing Life Into Your Dormant Windows Mouse</u></a></li>
<li><a href="https://windows11.techidaily.com/5-key-steps-to-resolve-hypervisor-error-bsod-in-winos/"><u>5 Key Steps to Resolve Hypervisor Error BSOD in WINOS</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-absence-of-ubisoft-launcher-in-windows/"><u>Addressing Absence of Ubisoft Launcher in Windows</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-producing-dynamic-content-for-discord-channels/"><u>[New] 2024 Approved  Producing Dynamic Content for Discord Channels</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-channel-upgrade-plans-standard-studio-or-beta-revolution-for-2024/"><u>[New] Channel Upgrade Plans  Standard Studio or Beta Revolution for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-elderly-friendly-window-pc-usability/"><u>Boosting Elderly-Friendly Window PC Usability</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-without-jailbreak-on-apple-iphone-xs-drfone-by-drfone-virtual-ios/"><u>How to Fake Snapchat Location without Jailbreak On Apple iPhone XS | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-insufficient-access-errors-during-software-removal/"><u>Avoiding Insufficient Access Errors During Software Removal</u></a></li>
<li><a href="https://fake-location.techidaily.com/prevent-cross-site-tracking-on-nokia-g310-and-browser-drfone-by-drfone-virtual-android/"><u>Prevent Cross-Site Tracking on Nokia G310 and Browser | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/a-leap-forward-for-windows-11-innovative-widget-features-proposal/"><u>A Leap Forward for Windows 11: Innovative Widget Features Proposal</u></a></li>
<li><a href="https://windows11.techidaily.com/a-guide-to-uncovering-your-systems-identity-quickly/"><u>A Guide to Uncovering Your System's Identity Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-complications-resetting-terminal-on-win11/"><u>Avoid Complications: Resetting Terminal on Win11</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-navigating-social-feeds-with-panoramic-content-a-guide-for-iosandroid-users/"><u>[Updated] In 2024, Navigating Social Feeds with Panoramic Content  A Guide for iOS/Android Users</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-rotating-the-audio-and-video-files-is-quite-a-challenging-task-though-but-the-arrival-of-some-of-the-well-known-video-rotators-has-solved-this-probl/"><u>Updated Rotating the Audio and Video Files Is Quite a Challenging Task Though, but the Arrival of some of the Well Known Video Rotators Has Solved This Problem</u></a></li>
<li><a href="https://windows11.techidaily.com/arp-cache-in-windows-what-and-how-to-purge/"><u>ARP Cache in Windows: What and How to Purge?</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/magnifying-youtube-visual-experience-for-2024/"><u>Magnifying YouTube Visual Experience for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-low-vram-issues-for-hogwarts-educational-virtual-adventure/"><u>Addressing Low VRAM Issues for Hogwarts Educational Virtual Adventure</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-photos-problem-package-not-registered/"><u>Addressing Windows Photos Problem - Package Not Registered</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/0-steps-to-perfect-youtube-reactions-a-trio-guide-for-2024/"><u>[New] 10 Steps to Perfect YouTube Reactions – A Trio Guide for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-the-no-connection-error-with-malwarebytes-in-win-1011/"><u>Addressing the “No Connection” Error with Malwarebytes in Win 10/11</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-the-playlist-pivot-new-order-strategies-for-youtube/"><u>[New] 2024 Approved  The Playlist Pivot  New Order Strategies for YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/add-command-to-windows-11-context-menu-for-file-moves-and-copies/"><u>Add Command to Windows 11 Context Menu for File Moves & Copies</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-proxy-in-windows-11-for-enhanced-privacy/"><u>Adjusting Proxy in Windows 11 for Enhanced Privacy</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-burnout-keeping-your-game-windows-laptop-cool/"><u>Avoiding Burnout: Keeping Your Game Windows Laptop Cool</u></a></li>
<li><a href="https://windows11.techidaily.com/beat-the-burn-how-to-cool-down-your-gamers-windows-laptop/"><u>Beat The Burn: How to Cool Down Your Gamers’ Windows Laptop</u></a></li>
<li><a href="https://windows11.techidaily.com/a-visual-journey-to-custom-window-design-with-winbubbles-insights/"><u>A Visual Journey to Custom Window Design with WinBubble's Insights</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-expressive-poetry-in-images-and-text-top-100-instagramcaptions/"><u>[Updated] 2024 Approved  Expressive Poetry in Images and Text - Top 100 #InstagramCaptions</u></a></li>
<li><a href="https://windows11.techidaily.com/awakening-hidden-pane-windows-effective-steps-for-win11/"><u>Awakening Hidden Pane Windows: Effective Steps for Win11</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-enhance-visibility-on-tiktok-a-list-of-powerful-username-concepts/"><u>[New] 2024 Approved  Enhance Visibility on TikTok - A List of Powerful Username Concepts</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-a-listeners-compendium-where-to-find-realistic-handclap-effects/"><u>New 2024 Approved A Listeners Compendium Where to Find Realistic Handclap Effects</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-enhancing-live-broadcasts-with-premium-webcams/"><u>[Updated] In 2024, Enhancing Live Broadcasts with Premium WebCams</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-10-best-spy-watches-for-your-vivo-t2-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Top 10 Best Spy Watches For your Vivo T2 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-flip-the-like-ratio-with-squared-up-social-media-content-for-2024/"><u>[New] Flip the Like Ratio with Squared-Up Social Media Content for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/a-detailed-approach-to-fixing-windows-error-code-30005/"><u>A Detailed Approach to Fixing Windows Error Code: 30005</u></a></li>
</ul></div>
