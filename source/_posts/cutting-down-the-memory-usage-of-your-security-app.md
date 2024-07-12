---
title: Cutting Down the Memory Usage of Your Security App
date: 2024-07-11T22:28:38.369Z
updated: 2024-07-12T22:28:38.369Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Cutting Down the Memory Usage of Your Security App
excerpt: This Article Describes Cutting Down the Memory Usage of Your Security App
keywords: Low Memory Security Apps,Reduce App Memory Use,Efficient Security Software,High-Performance S/W,Optimized Security Apps,Streamline Safety Programs,Minimal Memory Tools
thumbnail: https://thmb.techidaily.com/8ff514e7ae8e73f00c632257f00b6aefbc08dc01d831c81a6f2628b843ff494a.jpg
---

## Cutting Down the Memory Usage of Your Security App

 If you’ve kept a close eye on the Task Manager, then you may have noticed the Antimalware Service Executable doing its job. It is a crucial process of Windows Security (previously "Microsoft Defender") and helps keep your system safe from malware. It is pretty common to disable the Antimalware Service Executable because it consumes a large chunk of the system resources.

 On older PCs with limited system resources, the Antimalware Service Executable can severely impact the performance of your system. Read on as we discuss the importance of this service and how you can disable it.

## What Is the Antimalware Service Executable?

 You’re probably familiar with Windows Security (previously Microsoft Defender). Windows Security is a reliable antivirus that comes pre-installed on Windows 10 and 11\. The Antimalware Service Executable (you may find it listed as**MsMpEng.exe** in the**Task Manager**) is a core part of Windows Security.

 The service helps ensure your PC stays protected against any virus, worms, and other malware by continually scanning files and programs on your PC in the background. If the Antimalware Service Executable finds a malicious file or program, it will immediately delete or quarantine the affected files.

## Should You Disable the Antimalware Service Executable?

 Considering how integral the Antimalware Service Executable is to protect your PC, you must be wondering why you should even consider disabling it.

 If you do not have a third-party antivirus installed on your system, then Windows Security is your sole protection against potentially harmful malware. If your PC is left without any third-party antivirus programs installed, the Antimalware Service Executable automatically enables itself and begins safeguarding your PC as part of Windows Security.

 Ideally, you should not turn off the Antimalware Service Executable process. But if you have a reliable third-party antivirus installed, and the Antimalware Service Executable is still consuming a large chunk of your RAM or CPU, then it might make sense to disable it.

## How to Disable the Antimalware Service Executable

 There are a few different ways you can disable the Antimalware Service Executable depending on the circumstances of your system’s performance.

### Method 1: Disable Real-time Protection

 Suppose you find the Antimalware Service Executable process consuming a lot of system resources in certain instances; in that case, you can temporarily disable [real-time](https://www.makeuseof.com/real-time-protection/) malware protection through Windows Security:

1. Head to the**Start** menu, search for**Windows Security** and select the Best match.
2. Navigate to**Virus & threat protection** from the sidebar.
3. Look for**Virus & threat protection settings** , and then click on**Manage settings** option underneath.  
![real time protection windows security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/real-time-protection.jpg)
4. Disable the**Real-time protection** toggle button by bringing it to the**Off** position.

 Real-time protection will be turned back on automatically by Windows Security.

### Method 2: Turn Off Antimalware Service Executable Through Windows Security in the Registry Editor

 For users looking for a more permanent solution to disabling the Antimalware Service Executable, you will have to [disable Windows Security](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) from the Registry Editor.

 If you do not have a third-party antivirus installed, disabling Windows Security will leave your system at risk of malicious malware that can damage it.

To disable Antimalware Service Executable from the Registry Editor:

1. Search for**Registry Editor** from the**Start** menu, and launch it.
2. Navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows Defender** from the sidebar.
3. Right-click on the**Windows Defender** folder and select**New > DWORD (32-bit) Value** .  
![regedit windows defender](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/regedit-windows-defender.jpg)
4. Enter**DisableAntiSpyware** in the**Value name** field and**1** in the**Value data** field.
5. Press**OK** to save your changes and restart your system for the changes to take effect.

## Should You Rely on Windows Security for Windows 10 and 11?

 Many users opt for a dedicated third-party antivirus on Windows 10 or 11, but Windows Security has made significant improvements in the past few years. Not only is Windows Security a complete antivirus package, but it's also free and comes pre-installed on Windows.

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
<li><a href="https://instagram-clips.techidaily.com/in-2024-perfect-posts-enhance-videos-before-sharing-on-instagram/"><u>In 2024, Perfect Posts  Enhance Videos Before Sharing on Instagram</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-differences-windows-10-meets-windows-11/"><u>Deciphering the Differences: Windows 10 Meets Windows 11</u></a></li>
<li><a href="https://audio-editing.techidaily.com/step-by-step-tutorial-for-capturing-calls-using-google-voice-for-2024/"><u>Step-by-Step Tutorial for Capturing Calls Using Google Voice for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-upgrade-your-content-creation-process-via-youtube-studio/"><u>In 2024, Upgrade Your Content Creation Process via YouTube Studio</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/instagram-hidden-gems-top-tips-for-savvy-users-for-2024/"><u>Instagram Hidden Gems  Top Tips for Savvy Users for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-webp-image-save-in-google-chrome-windows-edition/"><u>Disabling WebP Image Save in Google Chrome, Windows Edition</u></a></li>
<li><a href="https://unlock-android.techidaily.com/pattern-locks-are-unsafe-secure-your-itel-phone-now-with-these-tips-by-drfone-android/"><u>Pattern Locks Are Unsafe Secure Your Itel Phone Now with These Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/dive-into-the-world-of-dxvk-essential-knowledge-for-windows-gamers/"><u>Dive Into the World of DXVK: Essential Knowledge for Windows Gamers</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-custom-privileges-in-win11-by-default/"><u>Clearing Custom Privileges in Win11 by Default</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-frequent-rainmeter-anomalies-in-windows-environment/"><u>Decoding Frequent Rainmeter Anomalies in Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-overview-how-to-optimize-w11s-auto-hdr/"><u>Comprehensive Overview: How to Optimize W11's Auto HDR</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-4-most-known-ways-to-find-someone-on-tinder-for-apple-iphone-11-by-name-drfone-by-drfone-virtual-ios/"><u>In 2024, 4 Most-Known Ways to Find Someone on Tinder For Apple iPhone 11 by Name | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-your-workspace-pinning-techniques-for-w11/"><u>Customize Your Workspace: Pinning Techniques for W11</u></a></li>
<li><a href="https://windows11.techidaily.com/contrasting-the-workflow-of-cloud-based-and-disk-installed-windows-oses/"><u>Contrasting the Workflow of Cloud-Based & Disk Installed Windows OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-efficient-automation-to-dot-and-ifttt/"><u>Crafting Efficient Automation: To-Dot & IFTTT</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-rise-and-shine-on-these-overlooked-meme-platforms/"><u>[New] Rise and Shine on These Overlooked Meme Platforms</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-navigating-tweeted-content-across-facebook/"><u>In 2024, Navigating Tweeted Content Across Facebook</u></a></li>
<li><a href="https://windows11.techidaily.com/design-dilemma-overcoming-unexpected-screen-shades/"><u>Design Dilemma: Overcoming Unexpected Screen Shades</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/in-2024-from-jittery-to-smooth-video-stabilization-techniques-in-premiere-pro/"><u>In 2024, From Jittery to Smooth Video Stabilization Techniques in Premiere Pro</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-a-practical-guide-to-managing-twitter-archives/"><u>[Updated] 2024 Approved  A Practical Guide to Managing Twitter Archives</u></a></li>
<li><a href="https://windows11.techidaily.com/delving-into-windows-11s-data-preservation-capabilities/"><u>Delving Into Windows 11'S Data Preservation Capabilities</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-optimized-obs-options-for-low-end-systems/"><u>[New] In 2024, Optimized OBS Options for Low-End Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/compact-windows-powered-systems-unveiled/"><u>Compact Windows-Powered Systems Unveiled</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-eliminate-watermarks-while-downloading-tiktok-videos-for-2024/"><u>[Updated] Eliminate Watermarks While Downloading TikTok Videos for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-rectifying-delayed-folder-upload-in-onedrive-without-hitches/"><u>Comprehensive Guide: Rectifying Delayed Folder Upload in OneDrive without Hitches</u></a></li>
<li><a href="https://windows11.techidaily.com/decode-and-resolve-uninitialized-disk-message-on-pc/"><u>Decode and Resolve Uninitialized Disk Message on PC</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-unleash-your-creativity-advanced-video-editing-techniques-and-effects/"><u>Updated Unleash Your Creativity Advanced Video Editing Techniques and Effects</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-resolving-directdraw-errors-on-win1011/"><u>Decoding and Resolving DirectDraw Errors on WIN10/11</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-beatbox-recorder-a-compreeved-guide/"><u>[Updated] 2024 Approved  BeatBox Recorder  A Compreeved Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-xbox-mic-connectivity-issues-in-windows-11-devices/"><u>Correcting Xbox Mic Connectivity Issues in Windows 11 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-old-wallpaper-a-simple-three-step-plan/"><u>Clearing Old Wallpaper - A Simple Three-Step Plan</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-boosting-your-content-a-guide-to-instagram-video-fame/"><u>[New] Boosting Your Content  A Guide to Instagram Video Fame</u></a></li>
<li><a href="https://windows11.techidaily.com/classic-game-storage-integrating-into-the-windows-photos-space/"><u>Classic Game Storage: Integrating Into the Windows Photos Space</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-s-best-free-mkv-editors-for-cutting-and-trimming/"><u>Updated 2024 Approved S Best Free MKV Editors for Cutting and Trimming</u></a></li>
<li><a href="https://windows11.techidaily.com/control-over-edges-ongoing-tasks-in-win11-environment/"><u>Control Over Edge's Ongoing Tasks in Win11 Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-taskbar-time-in-windows-11/"><u>Disabling Taskbar Time in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-os-issues-mastering-the-art-of-finding-and-fixing-error-messages-using-commands/"><u>Decoding OS Issues: Mastering the Art of Finding & Fixing Error Messages Using Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/delve-into-multi-display-setup-in-windows-11/"><u>Delve Into Multi-Display Setup in Windows 11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-mastering-video-thumbnail-creation-for-maximum-clicks/"><u>[New] Mastering Video Thumbnail Creation for Maximum Clicks</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-distinctions-between-microsoft-and-standard-windows-accounts/"><u>Dissecting: Distinctions Between Microsoft & Standard Windows Accounts</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-pokemon-go-cooldown-chart-on-nokia-c32-drfone-by-drfone-virtual-android/"><u>In 2024, Pokémon Go Cooldown Chart On Nokia C32 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-your-internet-gateway-in-win-11/"><u>Configuring Your Internet Gateway in Win 11</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/2024-approved-you-cannot-just-copy-and-paste-the-data-from-a-dvd-or-blu-ray-to-a-computer-since-you-need-a-file-conversion-software-in-order-to-change-the-f/"><u>2024 Approved You Cannot Just Copy and Paste the Data From a DVD or Blu-Ray to a Computer Since You Need a File Conversion Software in Order to Change the Format of a Video File. In This Article, We Are Going to Ta</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-unveiling-the-hidden-potential-of-earnings-on-vimeo-platforms-for-2024/"><u>[New] Unveiling the Hidden Potential of Earnings on Vimeo Platforms for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehending-windows-role-in-memory-reservation/"><u>Comprehending Windows' Role in Memory Reservation</u></a></li>
<li><a href="https://windows11.techidaily.com/cracking-code-repaired-windows-family-security-glitches/"><u>Cracking Code: Repaired Windows Family Security Glitches</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-error-mcuicntexe-not-found-in-win-8xp/"><u>Correcting Error: McUICnt.exe Not Found in Win 8/XP</u></a></li>
<li><a href="https://android-location.techidaily.com/for-people-wanting-to-mock-gps-on-motorola-edge-2023-devices-drfone-by-drfone-virtual/"><u>For People Wanting to Mock GPS on Motorola Edge 2023 Devices | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-transform-photos-and-videos-with-these-androidiphone-montage-apps/"><u>[New] Transform Photos & Videos with These Android/iPhone Montage Apps</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-stream-anything-from-oppo-k11x-to-apple-tv-drfone-by-drfone-android/"><u>In 2024, How To Stream Anything From Oppo K11x to Apple TV | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/cursor-on-display-redeeming-darkened-win1011-screens/"><u>Cursor on Display: Redeeming Darkened Win10/11 Screens</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/2024-approved-optimizing-facebook-video-covers-a-step-by-step-guide/"><u>2024 Approved Optimizing Facebook Video Covers A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/command-line-carnival-exciting-stunts-for-your-terminal/"><u>Command Line Carnival: Exciting Stunts for Your Terminal</u></a></li>
<li><a href="https://windows11.techidaily.com/classify-your-hdd-or-ssd-with-ease/"><u>Classify Your HDD or SSD with Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/classic-revival-atlasos-for-outdated-pcs/"><u>Classic Revival: AtlasOS for Outdated PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/command-line-to-admin-initiating-windows-11s-task-manager-with-power/"><u>Command Line to Admin: Initiating Windows 11'S Task Manager with Power</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-12-pro-without-passcode-or-face-id-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone 12 Pro without Passcode or Face ID</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-create-stunning-videos-on-windows-imovie-inspired-video-editing-tools/"><u>Updated 2024 Approved Create Stunning Videos on Windows IMovie-Inspired Video Editing Tools</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-unpublished-photography-scrutiny-and-complementary-selections/"><u>[Updated] Unpublished Photography Scrutiny & Complementary Selections</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-erratic-movement-7-windows-mouse-solutions/"><u>Conquer Erratic Movement: 7 Windows Mouse Solutions</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-mastery-in-maintaining-a-clean-feed-best-twitter-tools/"><u>In 2024, Mastery in Maintaining a Clean Feed  Best Twitter Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-and-rectifying-windows-steams-error-e84/"><u>Demystifying and Rectifying Windows Steam's Error E84</u></a></li>
<li><a href="https://windows11.techidaily.com/confirm-if-your-system-is-a-win11-recipe/"><u>Confirm if Your System Is a Win11 Recipe</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-quick-repair-pathways-creating-custom-win-shortcuts/"><u>Crafting Quick Repair Pathways: Creating Custom Win Shortcuts</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-the-path-restarting-issues-in-windows-photoshop/"><u>Clearing the Path: Restarting Issues in Windows PhotoShop</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-high-performance-gpus-for-4k-vision/"><u>2024 Approved  High-Performance GPUs for 4K Vision</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-tutorial-downloading-and-setting-up-msixbundle-and-msix-file-types/"><u>Comprehensive Tutorial: Downloading & Setting Up Msixbundle & MSIX File Types</u></a></li>
</ul></div>
