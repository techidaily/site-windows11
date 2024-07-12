---
title: 10 Ways to Clean Up Your Firewall Rules
date: 2024-07-11T22:09:26.824Z
updated: 2024-07-12T22:09:26.824Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 10 Ways to Clean Up Your Firewall Rules
excerpt: This Article Describes 10 Ways to Clean Up Your Firewall Rules
keywords: Firewall Optimization Tips,Streamlining Firewall Rules,Enhancing Network Security,Firewall Management Strategies,Simplifying Firewall Configurations,Firewall Rule Cleanup Guide,Improving Firewall Efficiency
thumbnail: https://thmb.techidaily.com/4740430244a268b3ae9a4b1e15c683b234a7cf8bdf323c545591ca9aaa0e0818.jpg
---

## 10 Ways to Clean Up Your Firewall Rules

 The Windows Firewall protects your device from malicious threats. But if you don't configure its settings correctly, this tool might prevent you from accessing most of the apps on your device.

 So, what's the solution if you've configured the wrong firewall settings by mistake? It's simple—all you need to do is reset these settings to their defaults.

 Let’s dive in and explore all the solutions.

## 1\. Use the Control Panel

 The Control Panel is an incredible tool that allows you to troubleshoot system issues or tweak PC settings. Now, let’s check out how this tool can help you reset the firewall settings:

1. Type **Control Panel** in the Start menu search bar and select the **Best match**. Alternatively, check out [the various way to access the Control Panel](https://www.makeuseof.com/windows-open-control-panel/).
2. Click the **View by** drop-down menu and select either the **Small icons** or **Large icons** option.
3. Select **Windows Defender Firewall** from the menu items.
4. Click the **Restore defaults** option on the left-hand side and follow the on-screen instructions.

![Clicking the Restore defaults option on the Windows Defender Firewall screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/clicking-the-restore-defaults-option-on-the-windows-defender-firewall-screen.jpg)

## 2\. Use the Command Prompt

 Ever used the Command Prompt before? It’s an incredible tool that helps you configure system settings, troubleshoot PC issues, and access various apps.

 In fact, you can perform a lot of tasks with this tool as long as you [type in the correct commands](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/).

 Now, let’s check out how to reset the firewall settings using the Command Prompt:

1. Type **Command Prompt** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as administrator**.
3. Type the following command and press **Enter**:

netsh advfirewall reset

 Wait for the process to complete. From there, restart your device to save these changes.

## 3\. Use Windows PowerShell

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

 Struggling to reset the firewall settings using the Command Prompt? If so, then try [Windows PowerShell](https://www.makeuseof.com/what-is-windows-powershell/).

 Here’s how to reset the firewall settings using PowerShell:

1. Type **Windows PowerShell** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as Administrator**.
3. Copy-paste the following command into PowerShell and press **Enter**:

(New-Object -ComObject HNetCfg.FwPolicy2).RestoreLocalFirewallDefaults()

 Wait for the process to complete, and then restart your device.

## 4\. Use the Windows Security App

 The Windows Security app is a tool that helps you scan and fix system bugs. Interestingly, you can also use this tool to reset the firewall settings.

 Here are the steps you need to follow:

1. Press **Win + I** to access the system settings.
2. Select the **Update & Security** option.
3. Click the **Windows Security** option on the left-hand side.
4. Select the **Firewall & network protection** tool in the middle pane.
5. Click the **Restore firewalls to default** option on the next screen.

![Clicking the Restore firewalls to default option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/clicking-the-restore-firewalls-to-default-option.jpg)

## 5\. Use the "Firewall with Advanced Security" Tool

 Still can’t reset the firewall settings? Try one of the options in the “Windows Firewall with Advanced Security” screen.

 As the name suggests, the “Windows Firewall with Advanced Security” tool allows you to configure various advanced settings. So, you can use it later if you want to tweak various firewall settings.

 For now, let’s check out how this tool can help you reset the firewall settings:

1. Press **Win + R** to open the Run command dialog box.
2. Type **wf.msc** and press **Enter** to open the “Windows Defender Firewall with Advanced Security” screen.
3. Navigate to the top-left corner and right-click on the **Windows Defender Firewall with Advanced Security on Local Computer** option.
4. Select the **Restore Default Policy** option.

![Selecting the Restore Default Policy option on the Firewall with Advanced Security screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/selecting-the-restore-default-policy-option-on-the-firewall-with-advanced-secutiry-screen.jpg)

 Can’t access the “Windows Defender Firewall with Advanced Security” screen using the steps we’ve covered? Try these methods:

1. Press **Win + I** to access the system settings.
2. Select the **Update & Security** option.
3. Click the **Windows Security** option on the left-hand side.
4. Select the **Firewall & network protection** tool in the middle pane.
5. Click **Advanced settings** in the middle pane.

 From there, right-click on the **Windows Defender Firewall with Advanced Security on Local Computer** option and select the **Restore Default Policy** option.

## Restoring the Firewall Settings to Their Default Settings

 It’s quite frustrating when the firewall settings prevent you from accessing the apps on your PC. But the good news is that you can simply resolve such issues by resetting these settings.

 To reset the firewall settings with ease, check out any of the tips we’ve covered. And if you want to reset the Settings app instead, there are solutions for that too!


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
<li><a href="https://windows11.techidaily.com/least-ram-and-cpu-hungry-browsers-on-triple-operating-systems/"><u>Least RAM and CPU-Hungry Browsers on Triple Operating Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-overcome-mb-service-connections-problem-on-win11-pc/"><u>How to Overcome MB Service Connections Problem on Win11 PC</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-innovate-with-imagery-installing-the-windows-11-movie-maker-app/"><u>2024 Approved  Innovate with Imagery  Installing the Windows 11 Movie Maker App</u></a></li>
<li><a href="https://extra-hints.techidaily.com/unveiling-the-future-of-podcasting-the-top-10-blenders-to-choose-from/"><u>Unveiling the Future of Podcasting - The Top 10 Blenders to Choose From</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-obs-troubleshooting-techniques-for-win-11-users/"><u>Mastering OBS Troubleshooting Techniques for Win 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/muting-windows-update-notifications/"><u>Muting Windows Update Notifications</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-system-crashes-sifting-through-win-files/"><u>Deciphering System Crashes: Sifting Through Win Files</u></a></li>
<li><a href="https://windows11.techidaily.com/maintaining-calculator-prominence-in-windows-os/"><u>Maintaining Calculator Prominence in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-open-wordpad-in-windows/"><u>How to Open WordPad in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mitigating-code-xc0000142-on-windows-xp-10/"><u>Mitigating Code XC0000142 on Windows XP, 10</u></a></li>
<li><a href="https://windows11.techidaily.com/getting-a-sneak-peek-of-windows-new-features-via-vivetool/"><u>Getting a Sneak Peek of Windows' New Features via ViVeTool</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-2024-approved-achieving-sonic-clarity-managing-audio-volume-in-audacity/"><u>New 2024 Approved Achieving Sonic Clarity Managing Audio Volume in Audacity</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-bypass-ms-defenders-blockage-on-third-party-av/"><u>How to Bypass MS Defender's Blockage on Third-Party AV</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-productivity-choosing-terminal-as-primary-command-line-interface/"><u>Enhancing Productivity: Choosing Terminal as Primary Command Line Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-windows-videography-leverage-advanced-distributive-transcoding-by-tdarr/"><u>Enhance Window's Videography: Leverage Advanced Distributive Transcoding by Tdarr</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/all-about-factory-reset-what-is-it-and-what-it-does-to-your-oppo-reno-10-proplus-5g-drfone-by-drfone-reset-android-reset-android/"><u>All About Factory Reset, What Is It and What It Does to Your Oppo Reno 10 Pro+ 5G? | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-asus-proart-review-pushing-boundaries-in-color-accuracy/"><u>2024 Approved  ASUS ProArt Review  Pushing Boundaries in Color Accuracy</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-address-0x800f0845-failure/"><u>How to Address 0X800f0845 Failure</u></a></li>
<li><a href="https://windows11.techidaily.com/managing-storage-with-onedrive-rearrange-for-win-11/"><u>Managing Storage with OneDrive – Rearrange for Win 11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-budget-friendly-ultra-panoramic-video-cameras/"><u>In 2024, Budget-Friendly Ultra-Panoramic Video Cameras</u></a></li>
<li><a href="https://extra-tips.techidaily.com/innovations-for-elevating-your-gopro-filmmaking-skills/"><u>Innovations for Elevating Your GoPro Filmmaking Skills</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-top-video-invite-creators-for-mobile-devices/"><u>Updated Top Video Invite Creators for Mobile Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/curing-stale-boot-option-imagery/"><u>Curing Stale BOOT Option Imagery</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-downloading-the-latest-hits-top-youtube-playlist-savers-for-pc/"><u>[New] In 2024, Downloading the Latest Hits  Top YouTube Playlist Savers for PC</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-discover-key-methods-to-store-discord-livestream-videos-efficiently/"><u>[New] 2024 Approved  Discover Key Methods to Store Discord Livestream Videos Efficiently</u></a></li>
<li><a href="https://fix-guide.techidaily.com/poco-f5-5g-screen-unresponsive-heres-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Poco F5 5G Screen Unresponsive? Heres How to Fix It | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/curing-grayed-screen-savers-quick-fixes-for-windows-users/"><u>Curing Grayed Screen Savers: Quick Fixes for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/experience-true-tech-fusion-windows-android-via-samsung/"><u>Experience True Tech Fusion – Windows, Android via Samsung</u></a></li>
<li><a href="https://iphone-location.techidaily.com/a-full-review-for-itools-virtual-location-and-top-5-alternatives-for-apple-iphone-15-plusipad-drfone-by-drfone-virtual-ios/"><u>A Full Review for iTools Virtual Location and Top 5 Alternatives For Apple iPhone 15 Plus/iPad | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/dispatching-windows-11s-silent-search-instigator/"><u>Dispatching Windows 11'S Silent Search Instigator</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-recognizing-breakthrough-voice-actors-in-anime-s-fresh-perspectives-for-2024/"><u>New Recognizing Breakthrough Voice Actors in Anime S Fresh Perspectives for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-multi-monitor-setup-changes/"><u>Mastering Multi-Monitor Setup Changes</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-solo-sound-output-in-windows-audio-device/"><u>Mending Solo Sound Output in Windows Audio Device</u></a></li>
</ul></div>
