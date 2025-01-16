---
title: Customize PC Audio with Windows 11'S Volume Mixer Tutorial
date: 2025-01-15T04:24:26.638Z
updated: 2025-01-16T11:52:12.344Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Customize PC Audio with Windows 11'S Volume Mixer Tutorial
excerpt: This Article Describes Customize PC Audio with Windows 11'S Volume Mixer Tutorial
keywords: WinVolumeMixTutorial,CustomPCAudioWin11,AudioW11EnhanceGuide,PCSoundControlWin11,VolumeAdjustWin11,MixerSetupWindows11,EnhancePCAudioWin11
thumbnail: https://thmb.techidaily.com/1127690728774d68859773ac2967a71d9b05c7378c0abebd2da2f4a67474809a.jpg
---

## Customize PC Audio with Windows 11'S Volume Mixer Tutorial

 Remember the old volume mixer which you could access from the system tray notifications? Windows 11 seems to be missing that ever since its release. When you click on the Volume icon in the Action Center, you only see an option to change the sound output device. There are no means to directly access the volume mixer from there. But Microsoft isn’t done with the volume settings on Windows 11.

 In a new experimental feature, Microsoft is revamping the sound settings in the Action Center. You will be able to switch output devices and adjust the volume of each of the apps listed in the Volume Mixer. Wondering how to get the feature on your system? Here's how.

## Why Do You Need a Volume Mixer in Action Center?

 The present state of volume settings in Windows 11 is quite lackluster. You can only adjust the volume of the system and cycle between multiple audio devices. For opening any other settings, even something as trivial as a volume mixer: you need to dive deep into system sound settings.

 It is baffling how Microsoft missed something so crucial in Windows 11\. These missing volume settings gave rise to apps like [EarTrumpet](https://apps.microsoft.com/store/detail/9NBLGGH516XP?hl=en-us&gl=US&ranMID=24542&ranEAID=nOD%2FrLJHOac&ranSiteID=nOD%5FrLJHOac-kFXVOqcgmh%5FMcUkQutiXeg&epi=nOD%5FrLJHOac-kFXVOqcgmh%5FMcUkQutiXeg&irgwc=1&OCID=AID2200057%5Faff%5F7593%5F1243925&activetab=pivot%3Aoverviewtab&ranMID=43674&ranEAID=RIg0ReKk7DI&ranSiteID=RIg0ReKk7DI-SCKmwfBirhtH6ExPZ%5FEJzQ&epi=RIg0ReKk7DI-SCKmwfBirhtH6ExPZ%5FEJzQ&irgwc=1&OCID=AID2200057%5Faff%5F7795%5F1243925&tduid=%28ir%5F%5Fwdc06dt9wokfbgsgxdjh3vgezv2x6gcmodrafe9c00%29%287795%29%281243925%29%28RIg0ReKk7DI-SCKmwfBirhtH6ExPZ%5FEJzQ%29%28%29&irclickid=%5Fwdc06dt9wokfbgsgxdjh3vgezv2x6gcmodrafe9c00) which offered rich sound customization settings. Along with that, you can even access the old volume mixers, adjust the sound levels of each app, and map shortcuts.

![Old Volume Settings in Action Center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/old-volume-settings-in-action-center.jpg)

 However, Microsoft is slowly identifying such missing features in Windows 11 and is adding an inbuilt solution for it. Recently,[Microsoft began testing an RGB lighting feature](https://www.makeuseof.com/enable-rgb-lighting-controls-windows-11/) that will eliminate the need for third-party customization apps. So, it is pretty clear that Microsoft wants to reduce the reliance on third-party apps for vital system features and tweaks.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Hpne0zPsZwU?si=yN5QDsG_WLb_Y3u-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Enable the Volume Mixer in Windows 11's Action Center

 To enable the volume mixer in Windows 11, you will need to do the following:

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gSKkJrJ57EA?si=WDOmInPE9EgQa_tB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4DJKH1uY7P0?si=tCG66XVlbwSKoATj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

9. Log in and press**Win + A** to open Action Center. You will notice a new volume mixer icon next to the volume bar. Click on it to reveal the complete sound settings. Both the Spatial Audio and volume mixer will be present inside.  
![New Volume Settings in Action Center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/new-volume-settings-in-action-center.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/umvX4ZdWbxk?si=tPXL0-Kzf9SQaY8z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BR4gsW-J7as?si=9a56UDKZKhREZnwz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-helps.techidaily.com/new-2024-approved-key-technique-to-integrate-gopro-content-within-cohesive-spherical-videography/"><u>[New] 2024 Approved Key Technique to Integrate GoPro Content Within Cohesive Spherical Videography</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-elite-selection-free-video-streamers-that-work-onlinedesktop-for-2024/"><u>[New] Elite Selection Free Video Streamers That Work Online/Desktop for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-quick-snapshot-the-essential-skill-for-zoom-meetings/"><u>[New] In 2024, Quick Snapshot The Essential Skill for Zoom Meetings</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-easy-to-follow-guide-to-mobile-recording-snapchat-edition/"><u>2024 Approved Easy-to-Follow Guide to Mobile Recording Snapchat Edition</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/approved-elevating-engagement-strategic-use-of-youtube-titles/"><u>2024 Approved Elevating Engagement Strategic Use of Youtube Titles</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-your-bluetooth-detection-problems-with-windows-10-solutions/"><u>Fix Your Bluetooth Detection Problems with Windows 10 Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-inaccessible-folders-in-windows-outlook-a-comprerani-guide/"><u>Fixing Inaccessible Folders in Windows Outlook: A Comprerani Guide</u></a></li>
<li><a href="https://discover-hacks.techidaily.com/passaggio-veloce-dalliso-al-mp4-una-procedura-semplice-per-la-conversione-in-pochi-minuti-solo-5/"><u>Passaggio Veloce Dall'ISO Al MP4: Una Procedura Semplice per La Conversione in Pochi Minuti Solo 5</u></a></li>
<li><a href="https://windows11.techidaily.com/pinpoint-win-logins-the-differentiator-between-right-and-wrong-entries/"><u>Pinpoint Win Logins: The Differentiator Between Right & Wrong Entries</u></a></li>
<li><a href="https://windows11.techidaily.com/the-complete-process-for-adding-widgets-on-windows-11/"><u>The Complete Process for Adding Widgets on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-and-personalize-your-pc-with-alomwares-mastery/"><u>Transform and Personalize Your PC With AlomWare's Mastery</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-memory-feature-disabled-in-win11/"><u>Troubleshooting Memory Feature Disabled in Win11</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/true-or-false-unmasking-gpt-myths/"><u>True or False? Unmasking GPT Myths</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-silent-keys-troubleshooting-tactics-for-windows-pcs/"><u>Unlock Silent Keys: Troubleshooting Tactics for Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/whats-next-after-0x800f0845-error/"><u>What's Next After 0X800f0845 Error?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/will-artificial-intelligence-determine-the-fate-of-apples-next-phenomenon-the-iphone-16-explored-at-zdnet/"><u>Will Artificial Intelligence Determine the Fate of Apple's Next Phenomenon, the iPhone 16? | Explored at ZDNET</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-mastery-constructing-clutter-free-directories/"><u>Windows 11 Mastery: Constructing Clutter-Free Directories</u></a></li>
</ul></div>

