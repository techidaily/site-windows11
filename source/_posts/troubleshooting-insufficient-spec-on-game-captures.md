---
title: Troubleshooting Insufficient Spec on Game Captures
date: 2024-07-11T21:13:35.467Z
updated: 2024-07-12T21:13:35.467Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Insufficient Spec on Game Captures
excerpt: This Article Describes Troubleshooting Insufficient Spec on Game Captures
keywords: Game Capture Issues,Spec Error Fixing,Resolve Game Frames,Correcting Capture Mistakes,Incorrect Game Screenshots,Enhancing Image Quality,Fixing Low-Quality Game Shots
thumbnail: https://thmb.techidaily.com/d20fb0a2bb9049e2210bb23aa9225c390244059cedf35b9a34d45f9a041c8543.jpg
---

## Troubleshooting Insufficient Spec on Game Captures

 Many users utilize the Xbox Game Bar app pre-installed with Windows for recording game clips. However, some users can’t record anything with the Game Bar because of an error that says, “sorry, your PC doesn't meet the hardware requirements for captures.” That error message can appear within Settings or when users select to record.

 The error message highlights a PC doesn’t meet system requirements for Game Bar recording. Yet, this error often arises for users who’ve utilized Game Bar’s recording on their PCs before. This is how you can fix the “PC doesn't meet the hardware requirements for captures” error in Windows 10 and 11\.

## Enable Game DVR With Game DVR Config

 Game DVR Config is third-party software with which some users have resolved the “PC doesn't meet the hardware requirements for captures” error. That software includes settings users can select to enable Game DVR along with audio and microphone capture.

 Here is how you can enable Game DVR with that software:

1. Open the [Game DVR Config](https://github.com/FunkyFr3sh/GameDVR%5FConfig/releases) page.
2. Click the **GameDVR\_Config.exe** download link.
3. Bring up Windows Explorer and the Downloads folder or other directory containing the Game DVR file.
4. Double-click the **GameDVR\_Config** file.
5. Select the **Enable Game DVR (Win+G)** checkbox.  
![The Game DVR Config software](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/game-dvr-config.jpg)
6. Click the **Force software MFT** checkbox to select that setting.
7. Exit Game DVR Config and [open Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/).
8. Look for the Broadcast DVR server on the **Processes** tab. Right-click Broadcast DVR Server and select **End task** if you can find that process.

## Edit the Control Registry Key

 Editing the Control registry key is a fix that’s worked for some users. Try editing that key like this:

1. To activate Run, simultaneously press **Win** \+ **R**.
2. Type **regedit** within the Run command box and press the **Enter** key.
3. Clear the text in the address bar and input this registry key location there:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control`
4. If there isn’t a **PortableOperatingSystem** DWORD already, right-click on the **Control** key and select **New** and **DWORD**. Input **PortableOperatingSystem** within the new key’s text box.  
![The New and Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/new-key-options.jpg)
5. Double-click on the **PortableOperatingSystem** DWORD in the Control key.
6. Delete the **0** number and input **1** within the **Value data** box.  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/edit-dword-window.jpg)
7. Set the value by clicking **OK** inside the Edit DWORD window.
8. Then close out of the Registry Editor app and restart Windows.

## Update Your Graphics Adapter’s Driver

 An outdated or faulty graphics driver might be causing this recording issue on your PC. Try installing the latest graphics driver for your GPU if you haven’t updated it in a while (or ever). This guide tells you [how to update a PC’s graphics driver in Windows](http://www.makeuseof.com/update-graphics-drivers-in-windows-10/).

![The NVIDIA graphics driver download page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/nvidia-driver-download.jpg)

## Enable the Windows Game Recording and Broadcasting Policy

 Group Policy Editor includes a Game Recording and Broadcasting policy that prevents recording when disabled. So, Windows Pro and Enterprise users must make sure that the Game Recording and Broadcasting policy is set to enabled. Do note that Windows Home doesn’t include the Group Policy Editor.

 Here is how you can enable that policy:

1. [Open Local Group Policy Editor](https://www.makeuseof.com/tag/open-local-group-policy-editor-windows/) and double-click **Computer Configuration** when it appears.
2. Double-click **Administrative Templates** \> **Windows Components**.
3. Select **Windows Game Recording and Broadcasting** in Group Policy’s sidebar.
4. Then double-click on the **Enables or disables Windows Game Recording and Broadcasting** policy.  
![The Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/group-policy-editor.jpg)
5. Click **Enabled** if that policy is disabled.
6. Select **Apply** to enable the recording policy and **OK** to close the window.  
![The Enables or disables Windows Game Recording and Broadcasting policy window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-game-and-recording-policy-window.jpg)
7. Close Group Policy Editor, bring up your Start menu and select **Power** \> **Restart**.

## Erase Data in the GameDVR Registry Key

 Corrupted GameDVR entries within the registry can cause the “PC doesn't meet the hardware requirements for captures” error. You can fix that by deleting DWORDs and strings in the GameDVR registry key, which will automatically regenerate. However, we still recommend users back up the registry before applying this potential solution.

 You can erase data from the GameDVR registry key as follows:

1. Open Registry Editor with Run, as covered in the first couple of steps of resolution two.
2. Go to this GameDVR registry key location:  
`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\GameDVR`
3. Select all DWORDs and strings within the GameDVR key by holding the **Ctrl** key and clicking on them.
4. Then right-click and select **Delete** \> **Yes**.  
![the-delete-option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-delete-option.jpg)
5. Click the Start menu’s Power button and select **Restart**.

## Get Recording Again With the Xbox Game Bar

 The potential solutions covered here are widely confirmed to resolve the “PC doesn't meet the hardware requirements for captures” by users who’ve needed to fix that issue. So, it’s most likely applying the potential fixes above will resolve that Game Bar recording issue on your Windows laptop or desktop. Then you can record video while gaming with the Game Bar’s recording feature again.

 The error message highlights a PC doesn’t meet system requirements for Game Bar recording. Yet, this error often arises for users who’ve utilized Game Bar’s recording on their PCs before. This is how you can fix the “PC doesn't meet the hardware requirements for captures” error in Windows 10 and 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-video-capture.techidaily.com/updated-capturing-the-heart-of-sims-4-games-for-2024/"><u>[Updated] Capturing the Heart of Sims 4 Games for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-photography-fix-overcoming-package-not-registered-issues/"><u>Win11 Photography Fix: Overcoming Package Not Registered Issues</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/snap-google-meet-sessions-on-ios-and-android-devices-for-2024/"><u>Snap Google Meet Sessions on iOS & Android Devices for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-click-rate-three-methods-for-mouse-double-click-tweaking/"><u>Enhance Click Rate: Three Methods for Mouse Double-Click Tweaking</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-notetaking-for-windows-professionals-win11w10/"><u>Advanced Notetaking for Windows Professionals (Win11/W10)</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-best-game-download-sites-top-picks/"><u>New Best Game Download Sites Top Picks</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-use-pokemon-go-joystick-on-xiaomi-13t-drfone-by-drfone-virtual-android/"><u>How to use Pokemon Go Joystick on Xiaomi 13T? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-circle-everything-you-need-to-know-on-poco-c50-drfone-by-drfone-virtual-android/"><u>Life360 Circle Everything You Need to Know On Poco C50 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-steps-for-altering-terminal-preference/"><u>Essential Steps for Altering Terminal Preference</u></a></li>
<li><a href="https://windows11.techidaily.com/fast-startup-mastery-in-windows-11-a-comprehensible-guide/"><u>Fast Startup Mastery in Windows 11 - A Comprehensible Guide</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-use-ispoofer-on-nubia-red-magic-9-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to use iSpoofer on Nubia Red Magic 9 Pro? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-the-hidden-potential-in-windows-powertoys-10-applications/"><u>Discover the Hidden Potential in Windows PowerToys' 10 Applications</u></a></li>
<li><a href="https://windows11.techidaily.com/5-essential-fixes-for-hypervisor-blue-screen-on-win-os/"><u>5 Essential Fixes for Hypervisor Blue Screen on WIN OS</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unlocking-digital-media-compreenhensive-srt-to-other-guidebook/"><u>[Updated] Unlocking Digital Media  Compreenhensive SRT-to-Other Guidebook</u></a></li>
<li><a href="https://network-issues.techidaily.com/simplified-repair-unused-gfx-card-wnvidia/"><u>Simplified Repair: Unused GFX Card W/NVIDIA</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-microsoft-store-issues-overcoming-0x80072f30/"><u>Unraveling Microsoft Store Issues: Overcoming 0X80072F30</u></a></li>
<li><a href="https://windows11.techidaily.com/5-essential-fixes-for-hybrid-os-hypervisor-faults/"><u>5 Essential Fixes for Hybrid OS Hypervisor Faults</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-detect-and-dislodge-suddenly-installed-rav-antivirus/"><u>How to Detect & Dislodge Suddenly Installed Rav Antivirus</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-garagebands-easy-way-to-dull-down-noise-levels/"><u>[Updated] Garageband's Easy Way to Dull Down Noise Levels</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-set-up-linux-and-linux-apps-on-a-windows-pc/"><u>How to Set Up Linux and Linux Apps on a Windows PC</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/which-pokemon-can-evolve-with-a-moon-stone-for-honor-play-7t-drfone-by-drfone-virtual-android/"><u>Which Pokémon can Evolve with a Moon Stone For Honor Play 7T? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/circumventing-windows-policies-preventing-app-deployment/"><u>Circumventing Windows Policies Preventing App Deployment</u></a></li>
<li><a href="https://windows11.techidaily.com/determining-effective-network-sharing-tools-tech-giants-face-off/"><u>Determining Effective Network Sharing Tools: Tech Giants Face-Off</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/ideal-choices-priority-6-fb-lite-vids-for-2024/"><u>Ideal Choices  Priority 6 FB Lite Vids for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tuning-taskbars-date-and-time-presentation/"><u>Fine-Tuning Taskbar's Date & Time Presentation</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-in-2024-get-to-know-openais-sora-and-how-to-use-it/"><u>New In 2024, Get To Know OpenAIs Sora and How To Use It</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/master-commanders-unleashed-ranking-7-total-war-champions-for-2024/"><u>Master Commanders Unleashed  Ranking 7 Total War Champions for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/access-hurdles-rejoin-your-shared-windows-zone/"><u>Access Hurdles: Rejoin Your Shared Windows Zone</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-windows-11s-compatibility-checker-usage-guide/"><u>Understanding Windows 11'S Compatibility Checker: Usage Guide</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-free-discolinking-techniques-desktop-and-smartphone-edition/"><u>2024 Approved  Free DiscoLinking Techniques  Desktop & Smartphone Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/banishing-0x800704b3-error-from-your-win1011-system/"><u>Banishing 0X800704B3 Error From Your Win10/11 System</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/maximize-your-youtube-channels-using-google-analytics/"><u>Maximize Your YouTube Channels Using Google Analytics</u></a></li>
<li><a href="https://windows11.techidaily.com/combating-steams-inability-to-synch-with-windows-folders/"><u>Combating Steam's Inability to Synch with Windows Folders</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-insiders-guide-to-creating-viral-memes-on-9gag-for-2024/"><u>The Insider's Guide to Creating Viral Memes on 9GAG for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-bring-your-vision-to-life-adobe-premiere-pro-for-mac-creators/"><u>In 2024, Bring Your Vision to Life Adobe Premiere Pro for Mac Creators</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-iso-images-from-your-windows-esd-originals/"><u>Crafting ISO Images From Your Windows' ESD Originals</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/crafting-solo-beats-methods-to-distill-music-into-single-element-projects-for-2024/"><u>Crafting Solo Beats Methods to Distill Music Into Single Element Projects for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-in-2024-unfolding-the-digital-canvas-vr-evolution/"><u>[New] In 2024, Unfolding the Digital Canvas  VR Evolution</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/2024-approved-easy-media-sharing-on-twitter-no-retweets-required/"><u>2024 Approved  Easy Media Sharing on Twitter - No Retweets Required</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-endure-no-more-teams-login-troubles-in-windows/"><u>How to Endure No More Teams Login Troubles in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-workflow-in-windows-11-run-command-innovation-guide/"><u>Elevate Your Workflow in Windows 11: Run Command Innovation Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-11-camera-app-eradicating-error-a00f425d/"><u>Troubleshooting Windows 11 Camera App: Eradicating Error A00F425D</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-stalled-netflix-app-on-windows/"><u>Troubleshooting Stalled Netflix App on Windows</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-inside-the-drone-world-detailed-look-at-dji-phantom-4/"><u>2024 Approved  Inside the Drone World  Detailed Look at DJI Phantom 4</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-apex-series-select-7-top-fps-games/"><u>In 2024, Apex Series  Select 7 Top FPS Games</u></a></li>
<li><a href="https://windows11.techidaily.com/the-explorers-guide-6-steps-to-property-expertise/"><u>The Explorer's Guide: 6 Steps to Property Expertise</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-google-frp-lock-on-motorola-moto-g04-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock on Motorola Moto G04 Devices</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-no-cost-screen-record-the-ultimate-win11-tools-1-5-listing/"><u>[New] No-Cost Screen Record  The Ultimate Win11 Tools #1-5 Listing</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/deep-dive-into-the-technological-framework-of-sound-forge/"><u>Deep Dive Into the Technological Framework of Sound Forge</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-new-submenus-to-windows-11s-desktop-context-menu/"><u>How to Add New Submenus to Windows 11’S Desktop Context Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reactivate-lost-bluetooth-listings-dmi/"><u>How to Reactivate Lost Bluetooth Listings DMI</u></a></li>
<li><a href="https://windows11.techidaily.com/fast-track-eliminate-extra-software-in-windows-11/"><u>Fast Track: Eliminate Extra Software in Windows 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-xiaomi-redmi-k70-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>In 2024, How to Cast Xiaomi Redmi K70 to Computer for iPhone and Android? | Dr.fone</u></a></li>
</ul></div>
