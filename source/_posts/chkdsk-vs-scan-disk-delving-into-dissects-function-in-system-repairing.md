---
title: "Chkdsk Vs. Scan Disk: Delving Into Dissect's Function in System Repairing"
date: 2024-07-11T22:12:29.679Z
updated: 2024-07-12T22:12:29.679Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Chkdsk Vs. Scan Disk: Delving Into Dissect's Function in System Repairing"
excerpt: "This Article Describes Chkdsk Vs. Scan Disk: Delving Into Dissect's Function in System Repairing"
keywords: ChkDsk Analysis,ScanDisk Usage,SystemRepair Tools,DriveDiagnostics,DiskError Fixes,FileSystemCheck,RepairUtility Functions
thumbnail: https://thmb.techidaily.com/861e642d844db4b2f3d772a017498464c5809d87279c75b02518b1d6b111bfc3.jpg
---

## Chkdsk Vs. Scan Disk: Delving Into Dissect's Function in System Repairing

### Quick Links

* [What Is CHKDSK and When Should You Use It?](#what-is-chkdsk-and-when-should-you-use-it)
* [What Is SFC Scannow and When Should You Use It?](#what-is-sfc-scannow-and-when-should-you-use-it)
* [What Is DISM and When Should You Use It?](#what-is-dism-and-when-should-you-use-it)
* [What Order Should You Run CHKDSK, SFC, and DISM In?](#what-order-should-you-run-chkdsk-sfc-and-dism-in)

### Key Takeaways

* CHKDSK scans your hard drive for errors and bad sectors, and you should run it if your computer isn't booting properly.
* SFC scans and repairs Windows system files, so run it when you experience program crashes or missing DLL errors.
* DISM is the most powerful tool and fixes corrupt files in the Windows system image, use it when SFC can't repair files.

 When your PC starts reporting errors, slowing down, or misbehaving, you can use Windows's built-in diagnostic tools to try and fix the problem. CHKDSK, SFC, and DISM check the health of your hard drive and repair corrupt files, but the three tools work in different ways and target different areas of your system.

 CHKDSK, SFC, and DISM are system tools, and you can run all three. However, this can be time-consuming and unnecessary for your specific problem, so it's best to know when and how to use this trio of troubleshooting tools.

## What Is CHKDSK and When Should You Use It?

 CHKDSK (Check Disk) is the first Windows diagnostic tool you should try if your PC starts acting strangely. For example, if it hangs while shutting down or becomes frustratingly slow.

 CHKDSK scans your entire hard drive to find and fix errors in files and the file system itself. It also checks your drive for bad sectors (clusters of data that cannot be read), and either tries to repair them or tells your system not to use them.

 Windows may run CHKDSK on startup if it detects a problem with your hard drive, sometimes for innocuous reasons such as improper shutdown, but also more serious ones, including malware infection and impending drive failure. However, it won't actually fix any issues until instructed to do so.

 To prevent future errors and potential data loss, it's worth running CHKDSK manually as part of your PC maintenance routine. You can use one of the following methods:

### 1\. Run CHKDSK Through File Explorer

 You can run CHKDSK from the command prompt. If you're uncomfortable using the Command Prompt, open **File Explorer**, click **This PC**, right-click the drive you want to check and select **Properties**.

 Select the **Tools** tab and then select **Check** in the **Error-checking** section.

![Launch the Check Disk tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-error-checking.jpg)

 If Windows determines that everything is running smoothly, it will suggest that you don't need to scan the drive. To run CHKDSK anyway, select **Scan drive**.

 The scan may take anywhere from a few minutes to half an hour, depending on the size and state of your drive. Once complete, CHKDSK will either tell you that no errors were found, or if it does find any, it will suggest you fix them.

### 2\. Run CHKDSK From the Command Prompt

 For greater control over the disk-checking process, you should run CHKDSK from an elevated Command Prompt. Follow these steps to continue:

1. Press the **Win** \+ **R** keys to open the Run dialog.
2. Type "cmd" in Run and press the **Ctrl** \+ **Shift** \+ **Enter** keys together to open Command Prompt as an administrator.
3. Click **Yes** in the User Account Control prompt.
4. In the Command Prompt window, type **chkdsk,** then space, followed by the drive letter you want to check. For example, **chkdsk c:** to scan your C: drive.  
![CHKDSK scan in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/chkdsk-scan.jpg)
5. Press **Enter** to scan for errors in read-only mode, which means no changes will be made.

 To make changes, you can use parameters with the CHKDSK command. Here are two you can use to fix problems:

* To make CHKDSK fix the problems it finds, type **chkdsk /f c:** (for your C: drive).
* To scan for bad sectors and errors, type **chkdsk /r c:**

 If you cannot run these commands because "the volume is in use by another process," Command Prompt will offer to schedule the scan for when your PC restarts. This should, however, only happen once. If the tool pops up whenever you boot your PC, you can [stop CHKDSK from running at every startup](https://www.makeuseof.com/tag/stuck-chkdsk-use-fix-right-way/) manually.

## What Is SFC Scannow and When Should You Use It?

 Whereas CHKDSK finds and fixes errors in the file system of your hard drive, **SFC (System File Checker)** specifically scans and repairs Windows system files. If it detects a file has been corrupted or modified, SFC automatically replaces that file with the correct version.

 Knowing when to use SFC is usually more obvious than with CHKDSK, which depends on the hunch that your hard drive isn't behaving correctly. If Windows programs are crashing, you're getting error messages about missing DLL files, or you're experiencing the dreaded Blue Screen of Death, then it's definitely time to run SFC.

[Open an elevated Command Prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), then type the following command and press **Enter** to execute:

`sfc /scannow`

 SFC will perform a full scan of your system and repair and replace any files that are damaged or missing using versions from the Windows component store (read the next section on DISM for more information on this and how SFC and DISM work can work together). The scan can take some time, but make sure you leave the Command Prompt window open until it's complete.

 If you only want to scan but not repair corrupted system files, type:

`sfc /verifyonly command`

 Once SFC has finished scanning, you'll see one of three messages:

* **Windows Resource Protection did not find any integrity violations.** This means that whatever's causing your PC problems isn't related to a system file.
* **Windows Resource Protection found corrupt files and successfully repaired them.** This should hopefully mean that your problems have been solved.
* **Windows Resource Protection found corrupt files but was unable to fix some of them.** This means that system files are to blame, but SFC can't replace them. Try running the tool again in Safe Mode. If you still get the same result, don't despair: it's time to use DISM.

![Screenshot of complete sfc scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/screenshot-of-complete-sfc-scan.jpg)

## What Is DISM and When Should You Use It?

**DISM (Deployment Image Servicing and Management)** is the most powerful of the three Windows diagnostic tools. Although you shouldn't usually need to use the tools, it's the one to turn to when you're experiencing frequent crashes, freezes, and errors, but SFC either can't repair your system files or is unable to run at all.

 While CHKDSK scans your hard drive and SFC your system files, DISM detects and fixes corrupt files in the component store of the Windows system image so that SFC can work properly. It can also help with Windows updates, driver integration, and boot issues you might be facing.

[Create a backup of your data](https://www.makeuseof.com/tag/ultimate-windows-10-data-backup-guide/) before running DISM, just in case something goes wrong.

 As with CHKDSK and SFC, you'll need to open an elevated Command Prompt (or Administrator Terminal Window on Windows 11) to run DISM. To save you the time and risk of performing repairs unnecessarily, you can first check if the image is corrupted without making any changes. Type the following command and press Enter:

`Dism /Online /Cleanup-Image /CheckHealth`

![windows dism check in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/windows-dism-check-in-command-prompt.jpg)

 The scan should only take a few seconds. If no corruption is detected, you can run a more advanced scan to determine if the component store is healthy and repairable, again without making any changes, by typing:

`Dism /Online /Cleanup-Image /ScanHealth`

 If DISM reports that there are problems with the system image, run another advanced scan to repair these issues automatically. DISM will connect to Windows Update to download and replace damaged files as required. Note that the process may take up to 10 minutes and hang for a while at 20 seconds, but this is normal. Type this command:

`Dism /Online /Cleanup-Image /RestoreHealth  
`

![dism scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dism-scan.jpg)

 Once the scan and repairs are complete, restart your PC and run SFC again to replace your corrupt or missing system files.

## What Order Should You Run CHKDSK, SFC, and DISM In?

 Now that you understand what CHKDSK, SFC, and DISM do, running one or more of these Windows troubleshooting tools will hopefully help you fix your PC.

 However, a common question concerns the order in which you should run these system tests. Should you always run CHKDSK first? Or how about always running DISM before SFC?

 There is no specific order to CHKDSK, SFC, and DISM, as why you run each tool depends on the issue you're experiencing. However, if you run SFC and it finds corrupt files and other issues, you should then run DISM to fix the Component Store and then run SFC again to fix any broken files.

 If you're still having trouble, perform a System Restore. This will restore your system files, settings, and programs to a time when they worked properly. If your system wasn't damaged when the restore point was created, it may solve your corruption problems.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://snapchat-videos.techidaily.com/ensuring-every-snapchatter-friendly-footage-via-mac-for-2024/"><u>Ensuring Every Snapchatter-Friendly Footage via Mac for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reactivate-grammarly-on-microsoft-devices/"><u>How To Reactivate Grammarly on Microsoft Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-ea-server-connection-failure-in-windows/"><u>Resolving EA Server Connection Failure in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/freedom-in-gaming-ps3-wirelessly-on-windows/"><u>Freedom in Gaming: PS3 Wirelessly on Windows</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-techniques-to-transfer-data-from-oneplus-nord-3-5g-to-iphone-15141312-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Techniques to Transfer Data from OnePlus Nord 3 5G to iPhone 15/14/13/12 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/gain-control-of-costs-windows-11-pro-key-advantages/"><u>Gain Control of Costs: Windows 11 Pro Key Advantages</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/worldly-speech-patterns-finding-a-home-in-english/"><u>Worldly Speech Patterns Finding a Home in English</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-navigate-facebooks-video-playback-like-a-pro/"><u>[Updated] In 2024, Navigate Facebook's Video Playback Like a Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/rejuvenate-your-locked-shift-key-in-windows/"><u>Rejuvenate Your Locked Shift Key in Windows.</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-device-functionality-in-windows-11/"><u>Optimize Device Functionality in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-path-not-found-issue-in-windows-xp7/"><u>Resolving Path Not Found Issue in Windows XP/7</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/advanced-audio-editing-in-adobe-premiere-pro-effortless-track-mixing-methods-for-2024/"><u>Advanced Audio Editing in Adobe Premiere Pro Effortless Track Mixing Methods for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/-favorite-footage-charted-on-youtube-for-2024/"><u>FIFA's Favorite Footage  Charted on YouTube for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixed-top-10-windows-glitch-solvers/"><u>Quick Fixed: Top 10 Windows Glitch Solvers</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/youtube-growth-hacking-for-new-videographers-for-2024/"><u>YouTube Growth Hacking for New Videographers for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-shutdown-how-to-pause-windows-11/"><u>Quick Shutdown: How to Pause Windows 11</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-free-online-video-editing-tools-with-background-music-options/"><u>2024 Approved Free Online Video Editing Tools with Background Music Options</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-troubleshoot-windows-obs-studio-crashes/"><u>How to Troubleshoot Windows OBS Studio Crashes</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-a-step-by-step-tutorial-on-video-angles-using-vlc-for-2024/"><u>[Updated] A Step-by-Step Tutorial on Video Angles Using VLC for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/purpose-and-key-aspects-of-vcplusplus-distributions/"><u>Purpose & Key Aspects of VC++ Distributions</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-fix-wins-unhandled-exception-blue-screen-problem/"><u>Methods to Fix Win's Unhandled Exception Blue Screen Problem</u></a></li>
<li><a href="https://windows11.techidaily.com/regaining-normalcy-in-windows-11-user-access/"><u>Regaining Normalcy in Windows 11 User Access</u></a></li>
<li><a href="https://howto.techidaily.com/full-solutions-to-fix-error-code-920-in-google-play-on-oneplus-ace-2-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Solutions to Fix Error Code 920 In Google Play on OnePlus Ace 2 Pro | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-spark-interest-how-to-make-your-vids-shine-on-insta/"><u>[New] 2024 Approved  Spark Interest  How to Make Your Vids Shine on Insta</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-twitch-and-friendly-networks-efficient-crossposting/"><u>[Updated] 2024 Approved  Twitch and Friendly Networks  Efficient Crossposting</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-banishing-stickers-from-social-media-short-clips/"><u>In 2024, Banishing Stickers From Social Media Short Clips</u></a></li>
<li><a href="https://android-location.techidaily.com/9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-lava-blaze-2-pro-drfone-by-drfone-virtual/"><u>9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Lava Blaze 2 Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/improve-download-efficiency-boosting-steam-and-windows-speed/"><u>Improve Download Efficiency: Boosting Steam and Windows Speed</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-a-smooth-transfer-of-your-windows-qbittorrent-settings/"><u>Ensuring a Smooth Transfer of Your Windows qBittorrent Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/getting-started-terminal-and-quake-mode/"><u>Getting Started: Terminal & Quake Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/rebuilding-dotnet-windows-fixes-to-remember-max-156/"><u>Rebuilding DotNet: Windows Fixes to Remember (Max 156)</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-2024-approved-how-to-translate-instagram-videos-for-global-engagement/"><u>New 2024 Approved How to Translate Instagram Videos for Global Engagement</u></a></li>
<li><a href="https://windows11.techidaily.com/escape-slowness-boosting-outlook-in-windows-os/"><u>Escape Slowness: Boosting Outlook in Windows OS</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-on-oppo-reno-11-pro-5g-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location on Oppo Reno 11 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-league-of-legends-playability-on-pc/"><u>Restoring League of Legends Playability on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-halt-unwanted-file-explorer-triggers/"><u>How to Halt Unwanted File Explorer Triggers</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-apple-id-unlock-from-iphone-6-how-to-fix-it-by-drfone-ios/"><u>In 2024, Apple ID Unlock From iPhone 6? How to Fix it?</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/024-approved-crafting-compelling-thumbnails-to-captivate-youtube-viewers-and-encourage-clicks/"><u>[New] 2024 Approved  Crafting Compelling Thumbnails to Captivate YouTube Viewers and Encourage Clicks</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-iphone-13-pro-activation-lock-by-drfone-ios/"><u>In 2024, How to Remove iPhone 13 Pro Activation Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-for-windows-update-failure-at-error-0xca00a009/"><u>Remedy for Windows Update Failure at Error 0xCA00A009</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-hide-a-zip-archive-within-an-image-file-in-windows-11-and-11/"><u>How to Hide a ZIP Archive Within an Image File in Windows 11 & 11</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-the-complete-snapchat-editors-toolbox-for-photo-finesse/"><u>[Updated] The Complete Snapchat Editor's Toolbox for Photo Finesse</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-catch-or-beat-sleeping-snorlax-on-pokemon-go-for-xiaomi-redmi-note-12-4g-drfone-by-drfone-virtual-android/"><u>In 2024, Catch or Beat Sleeping Snorlax on Pokemon Go For Xiaomi Redmi Note 12 4G | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/top-10-airplay-apps-in-vivo-y100-5g-for-streaming-drfone-by-drfone-android/"><u>Top 10 AirPlay Apps in Vivo Y100 5G for Streaming | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/enrich-your-windows-setup-with-personal-menus/"><u>Enrich Your Windows Setup with Personal Menus</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-unlock-windows-from-stuck-twilight-settings/"><u>How to Unlock Windows From Stuck Twilight Settings</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-facebook-ad-dominance-through-structured-strategic-copywriting-techniques/"><u>[Updated] 2024 Approved  Facebook Ad Dominance Through Structured, Strategic Copywriting Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-onedrive-errors-efficient-steps-for-instant-folder-addition/"><u>Overcoming Windows OneDrive Errors - Efficient Steps for Instant Folder Addition</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-10-best-free-editors-to-craft-captivating-facebook-videos/"><u>[New] 10 Best Free Editors to Craft Captivating Facebook Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/manual-inspections-to-detect-malicious-programs/"><u>Manual Inspections to Detect Malicious Programs</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-expert-analysis-on-slomo-video-softwares-performance/"><u>2024 Approved  Expert Analysis on SloMo Video Software's Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/masterful-techniques-to-perfect-your-wsl-2-docker-workflow/"><u>Masterful Techniques to Perfect Your WSL 2 Docker Workflow</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-oneplus-ace-2-pro-drfone-by-drfone-virtual-android/"><u>4 solution to get rid of pokemon fail to detect location On OnePlus Ace 2 Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/harnessing-ai-for-text-whisper-transcription-guide-for-windows-users/"><u>Harnessing AI for Text: Whisper Transcription Guide for Windows Users</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-efficient-downloads-transform-vimeo-videos-into-mp4-for-2024/"><u>[Updated] Efficient Downloads  Transform Vimeo Videos Into MP4 for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/the-ultimate-guide-to-slicing-and-dicing-vimeo-videos-online/"><u>The Ultimate Guide to Slicing and Dicing Vimeo Videos Online</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/four-pillars-of-mobile-video-acquisition-igtv-edition/"><u>Four Pillars of Mobile Video Acquisition  IGTV Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/reintroduce-forgotten-bluetooth-items-devices-mgr/"><u>Reintroduce Forgotten Bluetooth Items Devices Mgr</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-efficiency-top-6-ideas-to-overhaul-windows-11s-taskbar-layout/"><u>Maximizing Efficiency: Top 6 Ideas to Overhaul Windows 11'S Taskbar Layout</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/transforming-spaces-with-channels-top-10-online-tools-revealed-for-2024/"><u>Transforming Spaces with Channels  Top 10 Online Tools Revealed for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-unreachable-issues-with-malwarebytes-on-win11/"><u>Resolving Unreachable Issues with Malwarebytes on Win11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/waveform-whispering-how-to-gradually-reduce-volume-in-adobe/"><u>Waveform Whispering  How to Gradually Reduce Volume In Adobe</u></a></li>
<li><a href="https://windows11.techidaily.com/improve-notepad-on-win11-via-ingenious-sage/"><u>Improve Notepad on Win11 via Ingenious Sage</u></a></li>
<li><a href="https://windows11.techidaily.com/master-9-techniques-to-modify-windows-audio-interface/"><u>Master 9 Techniques to Modify Windows Audio Interface</u></a></li>
</ul></div>
