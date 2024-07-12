---
title: Confronting and Overcoming MMC Snaps Not Found Errors
date: 2024-07-11T22:07:38.387Z
updated: 2024-07-12T22:07:38.387Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Confronting and Overcoming MMC Snaps Not Found Errors
excerpt: This Article Describes Confronting and Overcoming MMC Snaps Not Found Errors
keywords: MMC Snap Fix Error,MMC Tools Troubleshoot,NTFS Filesystem Glitch,Windows MMC Snapping,SnapNotFound MMC,Repair MMC Shortcuts,Overcoming MMC Crashes
thumbnail: https://thmb.techidaily.com/03226297e1d4f4326afb184b72adefb3e6177057903e76b2e2845e825a7f6538.jpg
---

## Confronting and Overcoming MMC Snaps Not Found Errors

 The "MMC could not create the snap-in" error has been around for some time and still seem to bug some users now and then. The error occurs when you try to open an administrative tool such as an Event Viewer, Task Scheduler, and so forth.

 Sometimes, the error may also pop up after a Blue Screen of Death (BSOD), causing one or more apps to crash. This error often occurs if the registry configuration of the snap-in is malfunctioning. Here we show a few ways to fix to help you resolve the "MMC could not create the snap-in" error and restore administrative tools access in Windows.

## 1\. Fix the Broken Registry Configuration for the Snap-In

![delete-registry-key-mmc-snap-in-windows-registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/delete-registry-key-mmc-snap-in-windows-registry.jpg)

 If the registry configuration for the affected snap-in is broken, it may trigger the "MMC could not create the snap-in" error. To fix the issue, you’ll need to delete the corrupt registry entry associated with the snap-in. Here’s how to do it.

 Making incorrect modifications to the Windows Registry involves risk and may cause your system to malfunction. We recommend you [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and [make a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) to be on the safe side.

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK**.
3. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\MMC\SnapIns`
4. The **SnapIns** key consists of multiple sub-keys. You need to locate the sub-key identical to the **CLSID** shown in the error message.
5. For example, if the error occurs when opening Event Viewer, you’ll likely see **CLSID: c7b8fb06-bfe1-4c2e-9217-7a69a95bbac4**, and so on. So, note down the **CLSID** shown in the error screen.

1. In the **Registry Editor**, select the sub-key folder with the same name as the error **CLSID**.
2. Next, right-click on the same sub-key folder and select **Delete**.
3. Click **Yes** to confirm the action.
4. Close the **Registry Editor** and restart your computer.
5. After the restart, open the administrative tool snap-in to see if the error is resolved.

## 2\. Enable .NET Framework

![enable net framework 3 5 windows features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-net-framework-3-5-windows-features.jpg)

 You can also fix this error by enabling .NET Framework 3.5\. The idea is that one of the snap-ins on your PC may need .NET Framework 3.5 to work. So, if the feature is disabled, you may encounter an error.

 Fortunately, you can easily enable the .NET Framework feature using the Turn Windows features on or off dialog. Here’s how to do it.

 To enable .NET Framework 3.5:

1. Press the **Win** key and type **Windows features** and click on **Turn Windows features on or off** from the search results.
2. In the **Windows Features** dialog, select the **.NET Framework 3.5 (include .NET 2.0 and 3.0)**.
3. Next, click the **Plus** icon to expand the section and select the options ‘**Windows Communications Foundation HTTP Activation**’ and **‘Windows Communications Foundation Non-HTTP Activation**’.
4. Next, click to **Apply** the changes and install the feature.
5. Once installed, you’ll be prompted to restart the computer. Restart your system, and the MMC snap-in should work now.

## 3\. Check for and Repair Corrupt System Files

![DISM scan health restore health command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dism-scan-health-restore-health-command-prompt.jpg)

 If you have one or more corrupt system files, it may cause issues with the system apps. You can run the System File Checker tool to determine if the problem is due to system file issues. It will scan and check the integrity of systems files and automatically repair them to fix the problem.

 Microsoft recommends running its built-in Windows image check and repair utility, Deployment Image Servicing and Management (DISM), before running the System File Checker utility.

 If you're not sure how to run either of these tools, we cover both in our guide on [how to repair corrupt Windows files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

## 4\. Remove and Reinstall the Microsoft Visual C++ Redistributable

![repair microsoft visual c plus plus distributable package](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/repair-microsoft-visual-c-plus-plus-distributable-package.jpg)

 If the issue persists, try to fix and repair issues with the Visual C++ Redistributable package. If there are any issues with the package, it can cause the MMC snap-ins to stop working.

 To repair the Visual C++ Redistributable package:

1. Press **Win + R** to open Run.
2. Type "control" and click **OK** to open Control Panel.
3. In Control Panel, click on **Uninstall a program** under **Programs**.
4. Locate and select the **Microsoft Visual C++ Redistributable** entry and click **Uninstall**.
5. In the **Modify Setup** dialog, click **Repair**. The repair process may take a few minutes to complete.
6. Once done, restart your computer and check for any improvements.

 If the issue persists, reinstalling the Visual C++ Redistributable package may be required. To reinstall the package:

![uninstall microsoft visual c plus plus distributable package](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/uninstall-microsoft-visual-c-plus-plus-distributable-package.jpg)

1. Select the **Microsoft Visual C++ package** in Control Panel and click on **Uninstall**.
2. Click **Uninstall** in the **Modify Setup** dialog.
3. Click **Finish** to complete uninstallation. Repeat the process for all the Visual C++ Redistributable packages.
4. Once done, head over to the [Microsoft Visual C++ Redistributable package page](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170).
5. Download the latest version of the package available on your computer. Depending on your system compatibility, you can select from ARM64, X86, and X64 architecture versions.
6. Run the executable file to install the package and follow the on-screen instructions.
7. Once installed, restart your computer and check if MMC snap-ins are now working.

## Fix the MMC Snap-In and Restore Your Administrative Tools on Windows

 This error is triggered when a snap-in malfunctions, which is often a case of broken registry configuration. To fix the issue, you can delete the broken registry sub-key for the affected snap-in. Additionally, enable/re-enable the .NET Framework 3.5\. If not, scan the system for file integrity issues with the DISM and System File Checker utility.

 Alternatively, you can use the Remote Server Administration Tools (RSAT), which has additional features. RSAT is only available on the Pro and Enterprise edition of the Windows OS. However, you can run a PowerShell script to install it on the Windows Home version easily.

 Sometimes, the error may also pop up after a Blue Screen of Death (BSOD), causing one or more apps to crash. This error often occurs if the registry configuration of the snap-in is malfunctioning. Here we show a few ways to fix to help you resolve the "MMC could not create the snap-in" error and restore administrative tools access in Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://blog-min.techidaily.com/how-to-restore-deleted-infinix-zero-30-5g-photos-an-easy-method-explained-by-fonelab-android-recover-photos/"><u>How to Restore Deleted Infinix Zero 30 5G Photos  An Easy Method Explained.</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-halt-unwanted-file-explorer-triggers/"><u>How to Halt Unwanted File Explorer Triggers</u></a></li>
<li><a href="https://windows11.techidaily.com/improve-notepad-on-win11-via-ingenious-sage/"><u>Improve Notepad on Win11 via Ingenious Sage</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-ig-spotlight-superheroes-top-tier-covers-on-the-go/"><u>[Updated] 2024 Approved  IG Spotlight Superheroes  Top-Tier Covers on the Go</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-unlock-windows-from-stuck-twilight-settings/"><u>How to Unlock Windows From Stuck Twilight Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/freedom-in-gaming-ps3-wirelessly-on-windows/"><u>Freedom in Gaming: PS3 Wirelessly on Windows</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/from-chorus-to-silence-proven-tactics-for-singularizing-lyrics-within-harmonized-audios/"><u>From Chorus to Silence Proven Tactics for Singularizing Lyrics Within Harmonized Audios</u></a></li>
<li><a href="https://windows11.techidaily.com/gain-control-of-costs-windows-11-pro-key-advantages/"><u>Gain Control of Costs: Windows 11 Pro Key Advantages</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-device-functionality-in-windows-11/"><u>Optimize Device Functionality in Windows 11</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-remove-icloud-from-apple-iphone-6s-plus-smoothly-by-drfone-ios/"><u>How To Remove iCloud From Apple iPhone 6s Plus Smoothly</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-hide-a-zip-archive-within-an-image-file-in-windows-11-and-11/"><u>How to Hide a ZIP Archive Within an Image File in Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/a-beginners-guide-to-the-windows-10-activity-log/"><u>A Beginner's Guide to the Windows 10 Activity Log</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reactivate-grammarly-on-microsoft-devices/"><u>How To Reactivate Grammarly on Microsoft Devices</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-ditch-imovie-top-10-android-video-editors-you-should-try-for-2024/"><u>Updated Ditch iMovie Top 10 Android Video Editors You Should Try for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-high-quality-audio-collections-a-youtube-creators-guidebook/"><u>[Updated] In 2024, High-Quality Audio Collections  A YouTube Creator's Guidebook</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/elevating-your-marketing-game-making-impactful-fb-videos-for-2024/"><u>Elevating Your Marketing Game  Making Impactful FB Videos for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/digital-broadcasting-made-simple-your-essential-guide-to-4-recording-tips/"><u>Digital Broadcasting Made Simple  Your Essential Guide to 4 Recording Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/getting-started-terminal-and-quake-mode/"><u>Getting Started: Terminal & Quake Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/enrich-your-windows-setup-with-personal-menus/"><u>Enrich Your Windows Setup with Personal Menus</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-a-smooth-transfer-of-your-windows-qbittorrent-settings/"><u>Ensuring a Smooth Transfer of Your Windows qBittorrent Settings</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-ultimate-set-of-free-photo-screen-shifts/"><u>[Updated] Ultimate Set of Free Photo Screen Shifts</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-instant-mp3-from-your-fb-videos-online-converter/"><u>[Updated] Instant MP3 From Your FB Videos - Online Converter</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/graphics-enhancement-new-amd-hd-6950-update-on-windows-11-os/"><u>Graphics Enhancement - New AMD HD 6950 Update on Windows 11 OS</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-photojester-snapyour-chuckles/"><u>[Updated] PhotoJester  SnapYour Chuckles</u></a></li>
<li><a href="https://windows11.techidaily.com/masterful-techniques-to-perfect-your-wsl-2-docker-workflow/"><u>Masterful Techniques to Perfect Your WSL 2 Docker Workflow</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-come-up-with-the-best-pokemon-team-on-vivo-t2-pro-5g-drfone-by-drfone-virtual-android/"><u>How to Come up With the Best Pokemon Team On Vivo T2 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-role-of-copilot-key-in-your-windows-11-pc/"><u>Deciphering the Role of Copilot Key in Your Windows 11 PC</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-a-review-of-youtubes-integration-with-iphone-and-android-devices-for-2024/"><u>[New] A Review of YouTube's Integration with iPhone & Android Devices for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerate-task-management-view-in-windows-11/"><u>Accelerate Task Management View in Windows 11</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-how-to-make-your-gif-on-whatsapp-in-simple-ways/"><u>New How to Make Your GIF on WhatsApp in Simple Ways</u></a></li>
<li><a href="https://windows11.techidaily.com/manual-inspections-to-detect-malicious-programs/"><u>Manual Inspections to Detect Malicious Programs</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-mastering-nvidia-screenshot-capture-for-2024/"><u>[New] Mastering NVIDIA Screenshot Capture for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-smart-unlock-hacked-is-it-safe-to-use/"><u>Windows Smart Unlock Hacked – Is It Safe to Use?</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-from-stills-to-motion-creating-engaging-timelapse-videos-on-ipad-for-2024/"><u>[New] From Stills to Motion  Creating Engaging Timelapse Videos on iPad for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-detecting-instagram-disconnections-fast/"><u>[New] 2024 Approved  Detecting Instagram Disconnections Fast</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-insta-angle-alchemy-crafting-content-with-a-twist-for-maximum-impact/"><u>[New] In 2024, Insta-Angle Alchemy  Crafting Content with a Twist for Maximum Impact</u></a></li>
<li><a href="https://windows11.techidaily.com/harnessing-ai-for-text-whisper-transcription-guide-for-windows-users/"><u>Harnessing AI for Text: Whisper Transcription Guide for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-fix-wins-unhandled-exception-blue-screen-problem/"><u>Methods to Fix Win's Unhandled Exception Blue Screen Problem</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-onedrive-errors-efficient-steps-for-instant-folder-addition/"><u>Overcoming Windows OneDrive Errors - Efficient Steps for Instant Folder Addition</u></a></li>
<li><a href="https://windows11.techidaily.com/escape-slowness-boosting-outlook-in-windows-os/"><u>Escape Slowness: Boosting Outlook in Windows OS</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-stealth-instagram-story-viewing-guide-for-desktops-android-and-ios/"><u>[New] In 2024, Stealth Instagram Story Viewing Guide for Desktops, Android & iOS</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-navigating-costs-in-youtube-promotional-efforts/"><u>[Updated] Navigating Costs in YouTube Promotional Efforts</u></a></li>
<li><a href="https://windows11.techidaily.com/master-9-techniques-to-modify-windows-audio-interface/"><u>Master 9 Techniques to Modify Windows Audio Interface</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-enlightenment-streams-foremost-ed-resources-online/"><u>[Updated] 2024 Approved  Enlightenment Streams  Foremost Ed Resources Online</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-troubleshoot-windows-obs-studio-crashes/"><u>How to Troubleshoot Windows OBS Studio Crashes</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-screen-recordings-add-audio-to-snipping-tool-features-max-156/"><u>Enhancing Screen Recordings: Add Audio to Snipping Tool Features (Max 156)</u></a></li>
<li><a href="https://windows11.techidaily.com/declutter-your-pc-a-list-of-12-unnecessary-windows-tools/"><u>Declutter Your PC: A List of 12 Unnecessary Windows Tools</u></a></li>
<li><a href="https://extra-tips.techidaily.com/storytelling-with-style-making-instagram-text-dance/"><u>Storytelling with Style  Making Instagram Text Dance</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-efficiency-top-6-ideas-to-overhaul-windows-11s-taskbar-layout/"><u>Maximizing Efficiency: Top 6 Ideas to Overhaul Windows 11'S Taskbar Layout</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/2024-approved-facebooks-quintessential-changes-for-enthusiasts/"><u>2024 Approved  Facebook's Quintessential Changes for Enthusiasts</u></a></li>
<li><a href="https://windows11.techidaily.com/improve-download-efficiency-boosting-steam-and-windows-speed/"><u>Improve Download Efficiency: Boosting Steam and Windows Speed</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-this-article-talks-in-detail-about-how-to-convert-time-lapse-to-normal-video-using-certain-methods-on-iphone-online-tools-and-so-on-it-further-discusses/"><u>New This Article Talks in Detail About How to Convert Time-Lapse to Normal Video Using Certain Methods on iPhone, Online Tools, and so On. It Further Discusses Converting Time-Lapse Video to Normal on the Computer. Check Out</u></a></li>
</ul></div>
