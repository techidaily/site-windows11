---
title: Enhance PC Sounds with Windows 11'S Mixer Feature
date: 2024-07-11T21:41:19.163Z
updated: 2024-07-12T21:41:19.163Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enhance PC Sounds with Windows 11'S Mixer Feature
excerpt: This Article Describes Enhance PC Sounds with Windows 11'S Mixer Feature
keywords: WinPCSoundBoost,W11AudioMixer,EnhancedWindowsAudio,PCSoundImprovementW11,Windows11Audiomixing,AudioBoostWin11,SyncWindowsSounds
thumbnail: https://thmb.techidaily.com/d50bbc29912cb43ec93cd3720edb01228fbd6306ec3185b1604a33af30298ce1.jpg
---

## Enhance PC Sounds with Windows 11'S Mixer Feature

 Remember the old volume mixer which you could access from the system tray notifications? Windows 11 seems to be missing that ever since its release. When you click on the Volume icon in the Action Center, you only see an option to change the sound output device. There are no means to directly access the volume mixer from there. But Microsoft isn’t done with the volume settings on Windows 11.

 In a new experimental feature, Microsoft is revamping the sound settings in the Action Center. You will be able to switch output devices and adjust the volume of each of the apps listed in the Volume Mixer. Wondering how to get the feature on your system? Here's how.

## Why Do You Need a Volume Mixer in Action Center?

 The present state of volume settings in Windows 11 is quite lackluster. You can only adjust the volume of the system and cycle between multiple audio devices. For opening any other settings, even something as trivial as a volume mixer: you need to dive deep into system sound settings.

 It is baffling how Microsoft missed something so crucial in Windows 11\. These missing volume settings gave rise to apps like [EarTrumpet](https://apps.microsoft.com/store/detail/9NBLGGH516XP?hl=en-us&gl=US&ranMID=24542&ranEAID=nOD%2FrLJHOac&ranSiteID=nOD%5FrLJHOac-kFXVOqcgmh%5FMcUkQutiXeg&epi=nOD%5FrLJHOac-kFXVOqcgmh%5FMcUkQutiXeg&irgwc=1&OCID=AID2200057%5Faff%5F7593%5F1243925&activetab=pivot%3Aoverviewtab&ranMID=43674&ranEAID=RIg0ReKk7DI&ranSiteID=RIg0ReKk7DI-SCKmwfBirhtH6ExPZ%5FEJzQ&epi=RIg0ReKk7DI-SCKmwfBirhtH6ExPZ%5FEJzQ&irgwc=1&OCID=AID2200057%5Faff%5F7795%5F1243925&tduid=%28ir%5F%5Fwdc06dt9wokfbgsgxdjh3vgezv2x6gcmodrafe9c00%29%287795%29%281243925%29%28RIg0ReKk7DI-SCKmwfBirhtH6ExPZ%5FEJzQ%29%28%29&irclickid=%5Fwdc06dt9wokfbgsgxdjh3vgezv2x6gcmodrafe9c00) which offered rich sound customization settings. Along with that, you can even access the old volume mixers, adjust the sound levels of each app, and map shortcuts.

![Old Volume Settings in Action Center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/old-volume-settings-in-action-center.jpg)

 However, Microsoft is slowly identifying such missing features in Windows 11 and is adding an inbuilt solution for it. Recently,[Microsoft began testing an RGB lighting feature](https://www.makeuseof.com/enable-rgb-lighting-controls-windows-11/) that will eliminate the need for third-party customization apps. So, it is pretty clear that Microsoft wants to reduce the reliance on third-party apps for vital system features and tweaks.

## How to Enable the Volume Mixer in Windows 11's Action Center

 To enable the volume mixer in Windows 11, you will need to do the following:

### 1\. Download the Latest Windows Insider Build and ViVeTool

 Currently, the volume mixer feature is an experimental feature hidden in Windows Insider build 25295\. So, you must install this Windows Insider build or a higher version to enable this feature. We recommend [using UUP Dump to download Windows Insider builds without subscribing to Windows Insider](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/) .

 Microsoft recently expanded the Insider program with a new Canary channel, and it makes it difficult to downgrade to another channel. So, you can use UPP Dump to avoid this program and get builds directly.

 You will also need to download [ViVeTool from GitHub](https://github.com/thebookisclosed/ViVe/releases) to enable the experimental volume mixer feature. It is a command-line tool that can both activate and deactivate experimental Windows features. However, extract the tool to an easily accessible location in the C drive.

### 2\. Enable Volume Mixer in Windows Using ViVeTool

After you have the ViVeTool ready, repeat the following steps:

1. Press the**Win** key to open the Start menu. Type**cmd** and press the**Ctrl + Shift + Enter** key.
2. UAC will pop up. Click on the**Yes** button to [open the Command Prompt with administrator privileges](https://www.makeuseof.com/how-to-always-open-command-prompt-as-administrator-windows/) .
3. Now, you need to navigate to the location where the ViVeTool folder exists. We extracted the tool to a folder named ViVeTool in**C** drive for easy access, and suggest you do the same. Otherwise, you have to change the directory multiple time to get to the tool’s folder.
4. Type the**cd C:\\** command and press the enter key to go to the main C drive directory.
5. After that, type**cd ViVeTool** command and press the enter key. Now, you are in the directory where ViVeTool executable file is present.
6. Type the following command and press the enter key to enable the hidden volume mixer:  
vivetool /enable /id:42106010
7. You will see a “**Successfully set feature configuration(s)** ” message. Type the**exit** command and press the enter key to close the command prompt window.  
![Enabling New Volume Settings in Action Center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enabling-new-volume-settings-in-action-center.jpg)
8. Restart your system to allow the changes to take effect.
9. Log in and press**Win + A** to open Action Center. You will notice a new volume mixer icon next to the volume bar. Click on it to reveal the complete sound settings. Both the Spatial Audio and volume mixer will be present inside.  
![New Volume Settings in Action Center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/new-volume-settings-in-action-center.jpg)

## Adjust Your Volume Like A Pro on Windows 11

 Windows 11 uprooted a lot of useful settings and features. Users resorted to registry hacks and third-party programs to fix this issue. However, the new volume mixer attempts to fix that to some extent. Microsoft might improve the volume mixer further to overshadow apps like EarTrumpet, but that’s a very slim possibility.


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
<li><a href="https://windows11.techidaily.com/avoiding-anarchy-how-to-heal-fractured-win11-registry-elements/"><u>Avoiding Anarchy: How to Heal Fractured Win11 Registry Elements</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-distracting-notifications-messages-on-windows-11/"><u>Avoid Distracting Notifications, Messages on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-windows-update-issues-0xca00a009/"><u>Streamlining Windows Update Issues: 0XCA00A009</u></a></li>
<li><a href="https://youtube-help.techidaily.com/mastery-in-making-compelling-youtube-videos-for-brands-for-2024/"><u>Mastery in Making Compelling YouTube Videos for Brands for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-webcam-dark-screen-issue/"><u>Resolving Windows Webcam Dark Screen Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-original-settings-post-deletion-win-11/"><u>Restoring Original Settings Post Deletion (Win 11)</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/the-art-of-sharing-on-social-making-instagram-stories-explode-for-2024/"><u>The Art of Sharing on Social  Making Instagram Stories Explode for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/reshaping-administration-workflow-in-the-windows-ecosystem/"><u>Reshaping Administration Workflow in the Windows Ecosystem</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-the-error-disabled-device-code-22-in-windows-11/"><u>Remedying the Error: Disabled Device, Code 22 in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-memory-integrity-with-win11-tweaks-and-tricks/"><u>Securing Memory Integrity with Win11 Tweaks & Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/best-non-procreate-sketch-tools-for-windows-pc/"><u>Best Non-Procreate Sketch Tools for Windows PC</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/discontinuing-instant-recording-on-quicktime-for-2024/"><u>Discontinuing Instant Recording on QuickTime for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-for-installing-unverified-windows-drivers/"><u>Tactics for Installing Unverified Windows Drivers</u></a></li>
<li><a href="https://windows11.techidaily.com/dive-into-dark-display-settings-for-calc-app/"><u>Dive Into Dark Display Settings for Calc App</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-2024s-premier-iphone-selfie-enhancing-gadgets/"><u>[New] 2024'S Premier iPhone Selfie-Enhancing Gadgets</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-mobile-magnification-premium-highlights-for-iphonesandroids/"><u>[Updated] In 2024, Mobile Magnification  Premium Highlights for IPhones/Androids</u></a></li>
<li><a href="https://windows11.techidaily.com/reverse-c-drive-data-hoarding-in-windows-systems/"><u>Reverse C: Drive Data Hoarding in Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-to-mute-game-proposals-in-windows-11/"><u>Tips to Mute Game Proposals in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-allot-browser-permission-via-firewall-on-pc/"><u>Steps to Allot Browser Permission via Firewall on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-taskbar-windows-11-edition/"><u>Elevate Your Taskbar: Windows 11 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-the-nullzero-error-fixes-for-new-users-on-win11/"><u>Stop the Null/Zero Error: Fixes for New Users on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/turbocharge-pc-gaming-with-high-speed-yuzu/"><u>Turbocharge PC Gaming with High-Speed Yuzu</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-find-my-friends-work-on-tecno-spark-20-proplus-drfone-by-drfone-virtual-android/"><u>In 2024, Does find my friends work on Tecno Spark 20 Pro+ | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/5-ways-to-fix-the-windows-family-safety-feature-not-working/"><u>5 Ways to Fix the Windows Family Safety Feature Not Working</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-enhancing-pen-device-performance-on-windows/"><u>Troubleshooting: Enhancing Pen Device Performance on Windows</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/fb-snapcast-converter-for-2024/"><u>FB Snapcast Converter for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-net-requirement-issue-in-windows-apps/"><u>Tackling the .NET Requirement Issue in Windows Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/6-ways-to-recover-an-off-screen-window-in-windows-10-and-11/"><u>6 Ways to Recover an Off-Screen Window in Windows 10 and 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/list-of-pokemon-go-joysticks-on-asus-rog-phone-7-drfone-by-drfone-virtual-android/"><u>List of Pokémon Go Joysticks On Asus ROG Phone 7 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-writing-enhancers-for-your-windows-desktop/"><u>Top 5 Writing Enhancers for Your Windows Desktop</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-2024-approved-tunetrimmer-pro-the-essential-tool-for-distraction-free-listening/"><u>Updated 2024 Approved TuneTrimmer Pro The Essential Tool for Distraction-Free Listening</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-ultimate-how-to-for-your-youtube-music-collection/"><u>In 2024, The Ultimate How-To for Your YouTube Music Collection</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/24-visionaries-shaping-marvel-online-experience/"><u>In 2024, Visionaries Shaping Marvel Online Experience</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-tecno-camon-20-pro-5g-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Tecno Camon 20 Pro 5G to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/download-adobe-reader-seamlessly-with-microsoft-store/"><u>Download Adobe Reader Seamlessly with Microsoft Store</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-quick-access-shortcuts-adjacent-to-power-in-win11/"><u>Unveiling Quick Access: Shortcuts Adjacent to Power in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-11-unable-to-load-driver-errors/"><u>Addressing Windows 11: Unable to Load Driver Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-effortlessly-switch-between-windows-terminal-focus-and-normal-states/"><u>Steps to Effortlessly Switch Between Windows Terminal Focus and Normal States</u></a></li>
<li><a href="https://windows11.techidaily.com/the-hidden-language-of-windows-update-identifiers/"><u>The Hidden Language of Windows Update Identifiers</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-troubled-windows-registry-with-effective-solutions/"><u>Tackling Troubled Windows Registry with Effective Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-efficiency-folders-and-files-converge-in-win-11/"><u>Unlocking Efficiency: Folders & Files Converge in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/cease-windows-logging-each-app-opener/"><u>Cease Windows Logging Each App Opener</u></a></li>
<li><a href="https://windows11.techidaily.com/securely-accessing-power-user-terminal/"><u>Securely Accessing Power-User Terminal</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-effortlessly-download-every-tiktok-video-for-2024/"><u>[New] Effortlessly Download Every TikTok Video for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-onedrives-abode-in-the-windows-11-ecosystem/"><u>Adjusting OneDrive's Abode in the Windows 11 Ecosystem</u></a></li>
</ul></div>
