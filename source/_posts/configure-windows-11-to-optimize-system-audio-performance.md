---
title: Configure Windows 11 to Optimize System Audio Performance
date: 2024-07-11T22:25:40.779Z
updated: 2024-07-12T22:25:40.779Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Configure Windows 11 to Optimize System Audio Performance
excerpt: This Article Describes Configure Windows 11 to Optimize System Audio Performance
keywords: Win11 Audio Optimization,Audio Settings Windows,Enhance Windows Sound,Audio Boost in Windows,Improve Windows Audios,Windows Audio Tweaks,Tune Windows Audio
thumbnail: https://thmb.techidaily.com/21f134ff6252e8b65e4072cbcc9d1f7716bea3abeb6dec26820e9ae291c1ae1c.jpg
---

## Configure Windows 11 to Optimize System Audio Performance

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
<li><a href="https://sound-tweaking.techidaily.com/updated-best-10-voice-recorder-apps-for-android-phone/"><u>Updated Best 10 Voice Recorder Apps for Android Phone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-realme-gt-5-location-on-skout-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Realme GT 5 Location on Skout | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/clear-vision-in-gaming-captures-overcoming-obs-black-screens/"><u>Clear Vision in Gaming Captures  Overcoming OBS Black Screens</u></a></li>
<li><a href="https://howto.techidaily.com/super-easy-ways-to-deal-with-samsung-galaxy-a34-5g-unresponsive-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Super Easy Ways To Deal with Samsung Galaxy A34 5G Unresponsive Screen | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/complete-body-movement-report-2023-for-2024/"><u>Complete Body Movement Report 2023 for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-unlock-software-for-nokia-device-top-5-picks-to-remove-android-locks-by-drfone-android/"><u>In 2024, The Best Android Unlock Software For Nokia Device Top 5 Picks to Remove Android Locks</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-a-user-friendly-guide-for-shortcut-placement-on-desktop/"><u>Crafting a User-Friendly Guide for Shortcut Placement on Desktop</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-simplifying-cross-platform-sharing-instagram-and-facebook-integration/"><u>[Updated] Simplifying Cross-Platform Sharing  Instagram & Facebook Integration</u></a></li>
<li><a href="https://windows11.techidaily.com/comparative-overview-of-installation-methods-exe-and-msi-files/"><u>Comparative Overview of Installation Methods: Exe & Msi Files</u></a></li>
<li><a href="https://windows11.techidaily.com/defunct-windows-characteristics-youll-miss/"><u>Defunct Windows Characteristics You'll Miss</u></a></li>
<li><a href="https://windows11.techidaily.com/deletion-directive-for-drives-partitioned-areas-in-windows/"><u>Deletion Directive for Drives' Partitioned Areas in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/dispatching-speed-limits-defeat-windows-100mbps-boundary/"><u>Dispatching Speed Limits: Defeat Windows' 100Mbps Boundary</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-and-rectifying-non-functional-batches-in-windows/"><u>Deciphering and Rectifying Non-Functional Batches in Windows</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-fresh-ideas-for-every-feed-top-20-original-and-viral-tiktok-caption-strategies/"><u>2024 Approved  Fresh Ideas for Every Feed  Top 20 Original and Viral TikTok Caption Strategies</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-best-music-players-software-for-windows/"><u>[Updated] Best Music Players Software for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-chrome-time-lag-on-windows-devices/"><u>Correcting Chrome Time Lag on Windows Devices</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-optimal-no-cost-android-video-maker-for-2024/"><u>[New] Optimal No-Cost Android Video Maker for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-automatic-shutdown-timer-on-windows/"><u>Disabling Automatic Shutdown Timer on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-system-errors-win-os-and-df-conundrums-solved/"><u>Deciphering System Errors: Win OS and DF Conundrums Solved</u></a></li>
<li><a href="https://windows11.techidaily.com/direct-console-connection-joining-win-to-ps3-controller/"><u>Direct Console Connection: Joining Win to PS3 Controller</u></a></li>
<li><a href="https://windows11.techidaily.com/construct-ai-driven-artistry-with-win11-and-paint-tool-sai-your-ultimate-guide-to-image-creation/"><u>Construct AI-Driven Artistry with Win11 & Paint Tool SAI: Your Ultimate Guide to Image Creation</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-c0000005-on-windows-operating-systems/"><u>Conquering C0000005 on Windows Operating Systems</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-centralized-content-management-and-broadcasting/"><u>[New] 2024 Approved  Centralized Content Management and Broadcasting</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/hortcuts-every-youtuber-needs-the-top-20-list-for-2024/"><u>Pro Shortcuts Every YouTuber Needs - The Top 20 List for 2024</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-2024-approved-journey-into-jazz-mysteries-beyond-commonplace-knowledge/"><u>Updated 2024 Approved Journey Into Jazz Mysteries Beyond Commonplace Knowledge</u></a></li>
<li><a href="https://windows11.techidaily.com/credential-control-in-win11-quick-ways-to-unlock-passwords/"><u>Credential Control in Win11: Quick Ways to Unlock Passwords</u></a></li>
<li><a href="https://windows11.techidaily.com/decreasing-cpu-load-in-setup-hosts/"><u>Decreasing CPU Load in Setup Hosts</u></a></li>
<li><a href="https://extra-skills.techidaily.com/peek-inside-how-do-vr-headsets-connect-in-2024/"><u>Peek Inside  How Do VR Headsets Connect, In 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-expeditious-windows-file-audit-tactics/"><u>[Updated] Expeditious Windows File Audit Tactics</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-crafting-timeless-videos-with-historical-flair/"><u>2024 Approved  Crafting Timeless Videos with Historical Flair</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-the-oculus-quest-for-windows-vr-use/"><u>Customizing the Oculus Quest for Windows VR Use</u></a></li>
<li><a href="https://howto.techidaily.com/super-easy-ways-to-deal-with-xiaomi-civi-3-unresponsive-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Super Easy Ways To Deal with Xiaomi Civi 3 Unresponsive Screen | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/diagnosing-and-fixing-printmanagement-error-on-windows-os/"><u>Diagnosing and Fixing 'PrintManagement' Error on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-your-pcs-idle-lock-time/"><u>Customize Your PC's Idle Lock Time</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-dissecting-wirecast-a-comprehensive-breakdown-and-comparisons/"><u>[New] Dissecting WireCast  A Comprehensive Breakdown & Comparisons</u></a></li>
<li><a href="https://windows11.techidaily.com/coherent-organization-of-windows-files-max-156/"><u>Coherent Organization of Windows Files (Max 156)</u></a></li>
<li><a href="https://windows11.techidaily.com/cool-off-cycles-in-the-world-of-computers/"><u>Cool-Off Cycles in the World of Computers</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-win11s-startup-configuration-for-unmatched-performance/"><u>Conquer Win11's Startup Configuration for Unmatched Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/command-line-convenience-with-windows-task-scheduler/"><u>Command Line Convenience with Windows Task Scheduler</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-windows-build-numbers-and-updates/"><u>Dissecting Windows Build Numbers & Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/decades-of-taskbars-windows-journey-19852023/"><u>Decades of Taskbars: Windows' Journey (1985–2023)</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-deal-with-the-nokia-xr21-screen-black-but-still-works-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Deal With the Nokia XR21 Screen Black But Still Works? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/differentiating-windows-terminal-from-powershell-a-compreayer-study/"><u>Differentiating Windows Terminal From PowerShell: A Compreayer Study</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-pinterest-vid-extraction-made-easy-the-best-tools-ranked/"><u>[Updated] Pinterest Vid Extraction Made Easy  The Best Tools Ranked</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-create-ai-avatar-video-with-avatar-online/"><u>Updated Create AI Avatar Video with Avatar | Online</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-another-users-microsoft-account-on-shared-device/"><u>Disabling Another User's Microsoft Account on Shared Device</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-for-clarity-windows-terminal-as-main-app/"><u>Customize for Clarity: Windows Terminal As Main App</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-your-complete-analysis-of-tiktoks-pfp-code/"><u>In 2024, Your Complete Analysis of TikTok’s PFP Code</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-thumbnail-heights-in-windows-11-ui/"><u>Customize Thumbnail Heights in Windows 11 UI</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-exploring-the-coloredge-4k-capabilities-with-eizo/"><u>2024 Approved  Exploring the ColorEdge 4K Capabilities with EIZO</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/complete-assessment-gecatas-real-time-logger-for-2024/"><u>Complete Assessment  Gecata's Real-Time Logger for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/connectivity-problems-windows-solutions/"><u>Connectivity Problems: Windows Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-discrepancy-c-drive-vs-d-drive/"><u>Decoding the Discrepancy: C: Drive Vs. D: Drive</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-win11s-cursor-blackout-quickly/"><u>Clearing Up Win11's Cursor Blackout Quickly</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-beyond-indexation-decoding-the-purpose-of-unlisted-videos/"><u>[New] In 2024, Beyond Indexation  Decoding the Purpose of 'Unlisted' Videos</u></a></li>
</ul></div>
