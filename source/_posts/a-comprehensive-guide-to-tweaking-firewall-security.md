---
title: A Comprehensive Guide to Tweaking Firewall Security
date: 2024-07-11T22:14:20.709Z
updated: 2024-07-12T22:14:20.709Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Comprehensive Guide to Tweaking Firewall Security
excerpt: This Article Describes A Comprehensive Guide to Tweaking Firewall Security
keywords: Firewall Tweak Essentials,Secure Firewall Settings,Advanced Firewall Configurations,Optimizing Firewall Defense,Enhance Firewall Safety,Firewall Security Guide,Improve Firewall Controls
thumbnail: https://thmb.techidaily.com/7c4b3f31474d59dd334b247ce3128a185630128709ac4ffbfcbd9f4ba557fefe.jpg
---

## A Comprehensive Guide to Tweaking Firewall Security

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
<li><a href="https://youtube-videos.techidaily.com/key-elements-to-consider-in-asmr-video-watching/"><u>Key Elements to Consider in ASMR Video Watching</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-iphones-panoramic-videos-explained-for-fb-sharing/"><u>[New] 2024 Approved  IPhone's Panoramic Videos Explained for FB Sharing</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-resource-scheduling-for-android-on-windows-wsl/"><u>Efficient Resource Scheduling for Android on Windows WSL</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-common-issues-for-intel-unison-on-windows-11/"><u>Fixing Common Issues for Intel Unison on Windows 11</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-epiceditor-hub-innovative-pc-cutting-with-tunes/"><u>In 2024, EpicEditor Hub  Innovative PC Cutting with Tunes</u></a></li>
<li><a href="https://windows11.techidaily.com/vanishing-acts-concealing-keys-without-notice/"><u>Vanishing Acts: Concealing Keys Without Notice</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-virtual-potential-hyper-v-for-windows-11-users/"><u>Unlocking Virtual Potential: Hyper-V for Windows 11 Users</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-the-top-12-tycoon-games-where-strategies-thrive-and-profits-peak/"><u>[Updated] The Top 12 Tycoon Games - Where Strategies Thrive and Profits Peak</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-record-your-gameplay-3-simple-and-effective-ways/"><u>In 2024, Record Your Gameplay 3 Simple and Effective Ways</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-advice-overcoming-printer-error-0xfffffff/"><u>Expert Advice: Overcoming Printer Error 0xFFFFFFF</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-win11-potential-essential-commands-and-tricks-with-nircmd/"><u>Unlock Win11 Potential: Essential Commands & Tricks with NirCmd</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-leading-speech-transcription-tools-for-smartphones-android-and-iphone-edition/"><u>New 2024 Approved Leading Speech Transcription Tools for Smartphones - Android and iPhone Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/a-guide-to-direct-access-for-the-curious-explorer-in-windows-11/"><u>A Guide to Direct Access for the Curious Explorer in Windows 11</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-2024-approved-cutting-edge-drones-pairing-perfectly-with-gopros/"><u>[Updated] 2024 Approved  Cutting-Edge Drones Pairing Perfectly with GoPros</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-your-windows-onedrive-hurdles-now/"><u>Fix Your Windows OneDrive Hurdles Now</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-11-nvidia-cp-not-opening-problem/"><u>Fixing Windows 11: Nvidia CP Not Opening Problem</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/where-is-the-best-place-to-catch-dratini-on-nokia-c22-drfone-by-drfone-virtual-android/"><u>Where Is the Best Place to Catch Dratini On Nokia C22 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/ensure-seamless-fullscreen-launch-on-windows-pcs/"><u>Ensure Seamless Fullscreen Launch on Windows PCs</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-expert-level-mp4-integrator-with-fb-compatibility/"><u>[Updated] Expert-Level MP4 Integrator with FB Compatibility</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-developers-rejoice-unveiling-microsoft-copilot/"><u>Windows Developers Rejoice: Unveiling Microsoft Copilot</u></a></li>
<li><a href="https://windows11.techidaily.com/unblock-windows-task-scheduler-issues-quickly/"><u>Unblock Windows Task Scheduler Issues Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tracker-tools-the-ultimate-6-list-for-windows-users/"><u>Essential Tracker Tools: The Ultimate 6 List For Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-failed-application-launches-windows-11s-error-0xc000003e-explained/"><u>Correcting Failed Application Launches: Windows 11'S Error 0XC000003E Explained</u></a></li>
<li><a href="https://techidaily.com/how-to-install-the-latest-iosipados-beta-version-on-apple-iphone-11-pro-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Install the Latest iOS/iPadOS Beta Version on Apple iPhone 11 Pro? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/direct-linking-of-youtube-content-to-facebook-feeds-via-autoplay-settings/"><u>Direct Linking of YouTube Content to Facebook Feeds via Autoplay Settings</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/unleashing-creativity-how-to-make-dynamic-gifs-with-youtube-tracks-pcmobile-for-2024/"><u>Unleashing Creativity  How to Make Dynamic GIFs with YouTube Tracks (PC/Mobile) for 2024</u></a></li>
<li><a href="https://techidaily.com/best-fixes-for-xiaomi-redmi-13c-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Xiaomi Redmi 13C 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-the-absence-of-drive-letters-in-windows-environments/"><u>Dissecting the Absence of Drive Letters in Windows Environments</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-virtual-fraud-tips-for-discerning-true-windows-apps/"><u>Avoid Virtual Fraud: Tips for Discerning True Windows Apps</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-premium-choices-the-very-best-tripods-for-high-definition-shooting/"><u>2024 Approved  Premium Choices  The Very Best Tripods for High Definition Shooting</u></a></li>
<li><a href="https://windows11.techidaily.com/easily-identify-last-opened-files-in-windows-explorer/"><u>Easily Identify Last Opened Files in Windows Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/10-command-prompt-wonders-you-didnt-know/"><u>10 Command Prompt Wonders You Didn’t Know!</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-the-iphone-15-plus-sim-lock-4-easy-methods-by-drfone-ios/"><u>In 2024, How To Unlock The iPhone 15 Plus SIM Lock 4 Easy Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/unbroken-streams-winos-stability-verification-guide/"><u>Unbroken Streams: WinOS Stability Verification Guide</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-master-videoleap-to-capture-up-close-footage/"><u>In 2024, Master Videoleap to Capture Up-Close Footage</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-differences-how-exe-files-function-compared-to-msi/"><u>Dissecting Differences: How Exe Files Function Compared to Msi</u></a></li>
<li><a href="https://windows11.techidaily.com/when-windows-acts-up-reboot-or-reset/"><u>When Windows Acts Up, Reboot or Reset?</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/in-2024-the-cream-of-the-crop-10-exceptional-video-editing-programs/"><u>In 2024, The Cream of the Crop 10 Exceptional Video Editing Programs</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-solving-microsoft-offices-0x80041015/"><u>Understanding & Solving Microsoft Office's 0X80041015</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-ispoofer-is-not-working-on-motorola-moto-g23-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, iSpoofer is not working On Motorola Moto G23? Fixed | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-twinsoundlink-bridging-gaps-between-auditory-elements-in-premiere-pro-projects-2023-overhaul/"><u>In 2024, TwinSoundLink Bridging Gaps Between Auditory Elements in Premiere Pro Projects 2023 Overhaul</u></a></li>
</ul></div>
