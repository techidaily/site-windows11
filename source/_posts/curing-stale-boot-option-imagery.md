---
title: Curing Stale BOOT Option Imagery
date: 2024-08-15T15:47:26.500Z
updated: 2024-08-16T15:47:26.500Z
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

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
<!-- affiliate ads end -->

1. Click**Restart** to boot into the**Startup Menu.**  
![startup menu HP](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/startup-menu-hp-1.jpg)
<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2. In the Startup Menu, press**F10** to access the**BIOS Settings** . You may see other options depending on your computer manufacturer.
3. Use the right and left arrow keys to open the**Boot Options** tab in the BIOS Utility.
4. Next, use the up and down arrow key to highlight the**Secure Boot** option and press**Enter** to view more options.  
![disable secure boot bios](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-secure-boot-bios.jpg)
5. Select**Disabled** and make sure the changes are shown in the Boot Options tab.
6. Press**F10** to save the changes and disable Secure Boot.

## 2\. Disable Trusted Platform Technology (TPM)

![disable TPM state BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-tpm-state-bios-1.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->

 In addition to Secure Boot, you may also have enabled Trusted Platform Module (TPM), disabling Legacy BIOS. To fix the issue, check if TPM is enabled on your PC, which is likely a case on a Windows 11 running system, and disable the option if necessary.

 You can disable TPM from the BIOS setup utility. Here's how to do it.

1. Boot into your BIOS utility using the**Windows Recovery Menu.**
2. Next, open the**Security** tab using the right and left arrow keys.
3. Highlight the**TPM State** option and press**Enter** . If no TPM option is available, look for the**PTT** option.
4. Select**Disabled** to disable TPM on your device.
5. Press**F10** to save the change and exit.

<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Disable Modern Standby

 Modern Standby (S0) is a newer power mode available on select modern computers. It is enabled by default on compatible systems but can cause issues with Legacy Boot.

 To fix the issue, try to [disable Modern Standby on your Windows computer](https://www.makeuseof.com/windows-disable-modern-standby/) . Once disabled, restart your PC to see if you can switch to Legacy Boot now.

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-behind-the-scenes-recording-your-facebook-live-stream/"><u>[New] 2024 Approved  Behind the Scenes  Recording Your Facebook Live Stream</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-exclusive-look-at-best-screencaster-for-windowsmacos/"><u>[New] 2024 Approved  Exclusive Look at Best Screencaster for Windows/macOS</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-dive-into-the-dos-and-donts-of-youtube-beauty-channels-for-2024/"><u>[New] Dive Into the Do's and Don'ts of YouTube Beauty Channels for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-expert-guide-to-applying-luts-in-professional-production-for-2024/"><u>[New] Expert Guide to Applying LUTs in Professional Production for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-silencing-sound-obs-audio-solution-for-2024/"><u>[New] Silencing Sound  OBS Audio Solution for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-the-key-to-immersive-roleplay-zooming-into-roblox-worlds/"><u>[New] The Key to Immersive Roleplay  Zooming Into Roblox Worlds</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-from-chat-room-to-screen-step-by-step-google-meet-youtube-streams/"><u>[Updated] 2024 Approved  From Chat Room to Screen  Step-by-Step Google Meet YouTube Streams</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-breaking-ground-video-capture-breakdown-for-2024/"><u>[Updated] Breaking Ground  Video Capture Breakdown for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-downloading-facebook-videos-to-mp4-no-hassle-for-2024/"><u>[Updated] Downloading Facebook Videos to MP4 - No Hassle for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-unveiling-social-screens-share-your-monitor-on-fb-live/"><u>[Updated] In 2024, Unveiling Social Screens  Share Your Monitor on FB Live</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-insiders-pick-of-advanced-audio-software-a-vtubers-guide/"><u>2024 Approved  Insider's Pick of Advanced Audio Software  A Vtuber's Guide</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-megasecond-analysis-understanding-20mb-video-time/"><u>2024 Approved  MegaSecond Analysis  Understanding 20Mb Video Time</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-precision-evaluation-a-vll-approach-to-apps/"><u>2024 Approved  Precision Evaluation  A VLL Approach to Apps</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-the-ultimate-tutorial-for-musical-harmony-in-your-facebook-feed/"><u>2024 Approved  The Ultimate Tutorial for Musical Harmony in Your Facebook Feed</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-unleash-your-creativity-drawing-faces-on-snapchat/"><u>2024 Approved  Unleash Your Creativity  Drawing Faces on Snapchat</u></a></li>
<li><a href="https://windows11.techidaily.com/5-proven-strategies-for-superior-windows-11-search-performance/"><u>5 Proven Strategies for Superior Windows 11 Search Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/7-ways-to-fix-the-application-made-too-many-requests-error-0x80860010-on-windows/"><u>7 Ways to Fix the Application Made Too Many Requests Error (0X80860010) on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/a-compre-written-in-the-stars-mastering-your-laptops-touchscreen-precision/"><u>A Compre Written in the Stars: Mastering Your Laptop’s Touchscreen Precision</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensive-guide-to-wipeout-ms-audit-reports-on-your-pc/"><u>A Comprehensive Guide to Wipeout MS Audit Reports on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/a-fresh-window-on-computers-after-windows-11/"><u>A Fresh Window on Computers: After Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/a-guide-to-uncovering-your-systems-identity-quickly/"><u>A Guide to Uncovering Your System's Identity Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-restoration-features-your-pathway-through-windows-11/"><u>Activating Restoration Features: Your Pathway Through Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-windows-11s-task-manager-launch-interface/"><u>Adjusting Windows 11'S Task Manager Launch Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-uses-of-github-desktop-for-windows-11-enthusiasts/"><u>Advanced Uses of GitHub Desktop for Windows 11 Enthusiasts</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-complications-resetting-terminal-on-win11/"><u>Avoid Complications: Resetting Terminal on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-performance-with-windows-11-power-options/"><u>Boost Performance with Windows 11 Power Options</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-productivity-with-permanent-windows-terminal-admin-entry/"><u>Boost Productivity with Permanent Windows Terminal Admin Entry</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-steam-downloads-enhancing-windows-performance/"><u>Boosting Steam Downloads: Enhancing Windows Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/cleanse-your-screen-history-3-strategies/"><u>Cleanse Your Screen History - 3 Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/compatible-drawing-tools-for-windows-not-procreate/"><u>Compatible Drawing Tools for Windows, Not Procreate</u></a></li>
<li><a href="https://windows11.techidaily.com/correct-windows-11s-no-error-zero-error-flaw-quickly/"><u>Correct Windows 11'S No Error, Zero-Error Flaw Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-gray-out-issue-with-volume-extend-in-win/"><u>Correcting Gray Out Issue with Volume Extend in Win</u></a></li>
<li><a href="https://windows11.techidaily.com/cracking-the-code-unlocking-mac-locations-in-windows-11/"><u>Cracking the Code: Unlocking MAC Locations in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/craft-a-festive-atmosphere-with-creative-windows/"><u>Craft a Festive Atmosphere with Creative Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-and-correcting-irq-glitches/"><u>Deciphering and Correcting IRQ Glitches</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-win-errors-post-bsod-on-modern-oses/"><u>Deciphering Win Errors Post-BSOD on Modern OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/determining-public-ip-with-system-commands-windows/"><u>Determining Public IP with System Commands, Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/disable-untrusted-adobe-pop-up-on-computer/"><u>Disable Untrusted Adobe Pop-Up on Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/display-windows-notes-prominently-and-consistently/"><u>Display Windows Notes Prominently and Consistently</u></a></li>
<li><a href="https://fox-glue.techidaily.com/grid-mastery-in-photos-with-our-select-apps/"><u>Grid Mastery in Photos with Our Select Apps</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-samsung-galaxy-s24-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>How to Track Samsung Galaxy S24 Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-a-guide-oneplus-ace-2-pro-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>In 2024, A Guide OnePlus Ace 2 Pro Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-embrace-the-season-ideal-winter-backgrounds-for-yt/"><u>In 2024, Embrace the Season  Ideal Winter Backgrounds for YT</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-detect-and-stop-mspy-from-spying-on-your-nubia-red-magic-9-proplus-drfone-by-drfone-virtual-android/"><u>In 2024, How to Detect and Stop mSpy from Spying on Your Nubia Red Magic 9 Pro+ | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-steps-to-permanently-delete-your-instagram-profile-the-complete-guide/"><u>In 2024, Steps to Permanently Delete Your Instagram Profile  The Complete Guide</u></a></li>
<li><a href="https://extra-resources.techidaily.com/leading-action-cameras-for-thrill-seekers/"><u>Leading Action Cameras for Thrill Seekers</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overcoming-direct3d-launch-failure/"><u>Overcoming Direct3D Launch Failure</u></a></li>
<li><a href="https://windows11.techidaily.com/1719359377017-unfreeze-shift-button-on-your-pc/"><u>Unfreeze Shift Button on Your PC</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unlocking-more-potential-with-chatgpt-desktop-a-look-at-its-enhanced-capabilities-compared-to-web-version/"><u>Unlocking More Potential with ChatGPT Desktop: A Look at Its Enhanced Capabilities Compared to Web Version</u></a></li>
</ul></div>
