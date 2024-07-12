---
title: Mending the Malfunction of Defrag in Windows OS
date: 2024-07-11T22:01:35.289Z
updated: 2024-07-12T22:01:35.289Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mending the Malfunction of Defrag in Windows OS
excerpt: This Article Describes Mending the Malfunction of Defrag in Windows OS
keywords: Fixing Windows Fragmentation,Defrag OS Improvement Tips,Windows File Organization,Optimizing OS Performance,Reducing Disk Lag in Windows,Enhancing System Efficiency,Streamlining Windows Filesystem
thumbnail: https://thmb.techidaily.com/ef8036d25906bf8bc672642e846b12e7bf455ea76b0df7385d290b38eb25840e.jpg
---

## Mending the Malfunction of Defrag in Windows OS

 The Disk Defragmenter tool is a Windows user's best friend. This tool fixes fragmentation issues so that your hard drive runs smoother, but it itself sometimes comes across problems of its own. If you're having trouble with your disk defragmenter, there are a few things you can do to resolve the problem.

 In this article, you will learn how to fix the Disk Defragmenter so it works properly again.

## What Is the Disk Defragmenter? Why Does It Stop Working?

 The Disk Defragmenter tool rearranges files on your hard drive so that they are stored in a contiguous manner. This helps to improve file access speed and overall system performance. Disk fragmentation can occur over time as you add, remove, and modify files on your hard drive.

 Although a disk defragmenter is an important tool for keeping your computer running smoothly, sometimes it does not work as it should. Here are a few things that can cause the disk defragmenter to stop working:

1. The tool won't work if you have a solid-state drive (SSD). SSDs don't need to be defragmented because they don't have the same type of moving parts that traditional hard drives do.
2. Another possibility is that you have a virus or malware on your computer that's interfering with the disk defragmenter. You can try running a virus scan to see if that fixes the problem.
3. Corrupt system files can also cause the service to malfunction. In such a case, it may be worthwhile running an SFC (System File Checker) scan as a way to diagnose the problem.

 Now we know what causes the Disk Defragmenter to stop working, it's time to look at some solutions that may help you fix the problem.

## 1\. Check Disk Defragmenter's Status

 If your computer is running slowly, one potential reason could be that the Disk Defragmenter service is not running properly. This service helps to optimize your hard drive by rearranging files so that they can be read more quickly and efficiently.

 To check if the Disk Defragmenter service is running properly, follow the steps:

1. Open the Services app (see [ways to open the Services app on Windows](https://www.makeuseof.com/windows-11-open-services-app/) ).
2. Scroll down to the "Optimise drives" service and double-click on it.
3. Click on the drop-down menu and set the Start type to "Manual."
4. Make sure the Service status is "Running." If it is not, then click on**Start** to run it.  
![Set Optimise drives Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Set-Optimise-drives-Properties.jpg)
5. Click**Apply > OK** to save it.

 After making the above changes, check if it solves the problem. If not, move on to the next solution.

## 2\. Run the System File Checker tool

 Another way to fix your disk defragmenter is to run the System File Checker tool. This tool will scan all of your system files and replace any that are corrupt or missing.

To run the System File Checker, follow these steps:

1. Press**Win + X** on your keyboard to open the Power User menu.
2. Select the**Run** option from the menu list.
3. In the Run command dialog box, type "cmd" and press**Ctrl + Shift + Enter** at the same time.
4. When UAC appears on the screen, select**Yes** to approve administrator access.
5. Once you're in the Command Prompt window, type "sfc /scannow", and press**Enter** .

 It may take a while for the scan to complete, so be patient. Once the scan is complete, restart your computer and try running Disk Defragmenter again. It should now work properly.

![SFC and DISM Scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/SFC-and-DISM-Scan.jpg)

 If you're still having trouble with your Disk Defragmenter tool after running an SFC scan, you may need to use the DISM utility. To do this, open the Command Prompt as an administrator and run the below command line:

`DISM /Online /Cleanup-Image /ScanHealth\nDism.exe /online /cleanup-image /restorehealth`

 Once the scan is complete, restart your computer and try defragmenting again.

## 3\. Run the CHKDSK Utility

 If your computer's Disk Defragmenter is still not working, you can try [running the CHKDSK utility](http://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) . This is a computer program designed to check the integrity of your hard drive, identify errors, and fix them.

To run the CHKDSK utility, follow the below steps:

1. Press the Windows key and search for "Command Prompt".
2. Right-click on the search result and select**Run as administrator** .
3. Click**Yes** if UAC prompts on your computer screen. This will open a Command Prompt with admin access.  
![Run chkdsk command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Run-chkdsk-command.jpg)
4. When you're in Command Prompt, type the following command and press Enter:  
`chkdsk C: /f`

 In the command above,**"C:"** represents your drive, so you should replace it with the letter that refers to your drive.

 Once the scanning process is completed, and you have been informed that your drive has been scanned, try to defragment it again.

 As it turns out, it may take several minutes for the scan to complete, depending on the size of your partition and sometimes it seems to get stuck. However, you should let it complete its task uninterrupted.

## 4\. Close All Third-Party Applications

 Some third-party applications may interfere with Disk Defragmenter if they are running. In such a case, close all third-party programs and see if that helps the defragmenter to run properly.

 If you close all active windows and find that the defragmenter is still having issues, there might be a background process interfering with it. As such, you can try ending some third-party processes and see if that fixes it.

1. Press**Ctrl + Shift + Esc** on your keyboard to open the Task Manager.
2. On the Processes tab, find a non-essential third-party service and right-click on it.
3. Then select**End task** from the context menu.  
![Close Programs Via Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Close-Programs-Via-Task-Manager.jpg)

 After closing one, check if the disk defragmenter works again. If it does, the service you just closed is the culprit. Now you can either update, re-install, or even uninstall the problematic app so it stops interfering with Disk Defragmenter.

## Fixing Windows Disk Defragmenter's Opening Issues

 Disk defragmentation can improve the situation by rearranging files so that they can be evenly distributed throughout the drive. However, sometimes the Disk Defragmenter tool doesn't work as expected. If you encounter this problem, the methods described above should help you resolve it.


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
<li><a href="https://youtube-docs.techidaily.com/arness-social-blade-for-profound-youtube-stats-analysis-for-2024/"><u>[New] Harness Social Blade for Profound YouTube Stats Analysis for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-huawei-nova-y71-drfone-by-drfone-virtual-android/"><u>In 2024, Why Your WhatsApp Live Location is Not Updating and How to Fix on your Huawei Nova Y71 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-windows-11s-compatibility-checker-usage-guide/"><u>Understanding Windows 11'S Compatibility Checker: Usage Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/access-hurdles-rejoin-your-shared-windows-zone/"><u>Access Hurdles: Rejoin Your Shared Windows Zone</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-photography-fix-overcoming-package-not-registered-issues/"><u>Win11 Photography Fix: Overcoming Package Not Registered Issues</u></a></li>
<li><a href="https://extra-information.techidaily.com/free-cutting-edge-beat-detection-for-aspiring-producers/"><u>Free, Cutting-Edge Beat Detection for Aspiring Producers</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-mastering-aspect-ratios-in-video-production/"><u>[New] Mastering Aspect Ratios in Video Production</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-about-realme-c51-frp-bypass-by-drfone-android/"><u>In 2024, About Realme C51 FRP Bypass</u></a></li>
<li><a href="https://windows11.techidaily.com/sound-struggles-winning-back-noise-from-windows-spacebar/"><u>Sound Struggles: Winning Back Noise From Windows' Spacebar</u></a></li>
<li><a href="https://windows11.techidaily.com/determining-effective-network-sharing-tools-tech-giants-face-off/"><u>Determining Effective Network Sharing Tools: Tech Giants Face-Off</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-workflow-in-windows-11-run-command-innovation-guide/"><u>Elevate Your Workflow in Windows 11: Run Command Innovation Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/starting-windows-terminal-with-quake-effects/"><u>Starting Windows Terminal with Quake Effects</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-workspace-malfunctions-essential-tips-for-office-on-winos/"><u>Resolving Workspace Malfunctions: Essential Tips for Office on WINOS</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/boosting-engagement-from-the-start-premium-paid-free-intra-creators/"><u>Boosting Engagement From the Start  Premium, Paid-Free Intra Creators</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-keep-your-music-memories-intact-top-three-storage-methods-for-2024/"><u>[Updated] Keep Your Music Memories Intact  Top Three Storage Methods for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-explorers-guide-6-steps-to-property-expertise/"><u>The Explorer's Guide: 6 Steps to Property Expertise</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-screen-glitches-in-windows-11-a-step-by-step-guide/"><u>Solving Screen Glitches in Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/circumventing-windows-policies-preventing-app-deployment/"><u>Circumventing Windows Policies Preventing App Deployment</u></a></li>
<li><a href="https://windows11.techidaily.com/banishing-0x800704b3-error-from-your-win1011-system/"><u>Banishing 0X800704B3 Error From Your Win10/11 System</u></a></li>
<li><a href="https://windows11.techidaily.com/5-essential-fixes-for-hybrid-os-hypervisor-faults/"><u>5 Essential Fixes for Hybrid OS Hypervisor Faults</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/2024-approved-discover-the-best-top-10-intro-maker-sites-for-videos/"><u>2024 Approved Discover the Best Top 10 Intro Maker Sites for Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-solve-iphone-picture-failure-in-pcs-windows/"><u>Steps to Solve iPhone Picture Failure in PCs (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/steering-onedrive-destination-on-windows-pc/"><u>Steering OneDrive Destination on Windows PC</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-a-step-by-step-guide-to-erasing-chats-on-discord-en-masse/"><u>[Updated] A Step-by-Step Guide to Erasing Chats on Discord En Masse</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-2023s-social-media-sensations-on-twitter/"><u>[New] 2024 Approved  2023'S Social Media Sensations on Twitter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-re-listing-bluetooth-on-windows-pc/"><u>Strategies for Re-Listing Bluetooth on Windows PC</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-easiest-ways-to-change-your-voice-in-pubg-for-2024/"><u>[New] Easiest Ways to Change Your Voice in PUBG for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/universal-unlock-pattern-for-vivo-y100t-by-drfone-android/"><u>Universal Unlock Pattern for Vivo Y100t</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-uncover-the-best-12-flipscreen-vlogging-cameras-on-a-budget/"><u>[Updated] Uncover the Best 12 Flipscreen Vlogging Cameras on a Budget</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-microsoft-store-issues-overcoming-0x80072f30/"><u>Unraveling Microsoft Store Issues: Overcoming 0X80072F30</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-getting-the-pokemon-go-gps-signal-not-found-11-error-in-vivo-y27-4g-drfone-by-drfone-virtual/"><u>In 2024, Getting the Pokemon Go GPS Signal Not Found 11 Error in Vivo Y27 4G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/seeking-entry-into-the-windows-11-insider-circle/"><u>Seeking Entry Into the Windows 11 Insider Circle</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-grow-your-streams-money-potential-anywhere-on-devices/"><u>[Updated] 2024 Approved  Grow Your Stream's Money Potential Anywhere on Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-absent-windows-extras-a-comprehensive-guide/"><u>Reviving Absent Windows Extras: A Comprehensive Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-searching-on-windows-techniques-beyond-ls-command/"><u>Seamless Searching on Windows: Techniques Beyond LS Command</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlined-startup-routines-in-modern-windows/"><u>Streamlined Startup Routines in Modern Windows</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/navigate-your-way-through-premiere-pros-fs-mode/"><u>Navigate Your Way Through Premiere Pro's FS Mode</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-share-location-in-messenger-on-apple-iphone-se-2020-drfone-by-drfone-virtual-ios/"><u>How to Share Location in Messenger On Apple iPhone SE (2020)? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/surface-go-3-with-latest-chip-reviewed-mixed-outcomes-noted/"><u>Surface Go 3 with Latest Chip Reviewed: Mixed Outcomes Noted</u></a></li>
<li><a href="https://change-location.techidaily.com/home-button-not-working-on-vivo-y17s-here-are-real-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Home Button Not Working on Vivo Y17s? Here Are Real Fixes | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-windows-from-notifying-you-of-updates/"><u>Stop Windows From Notifying You of Updates</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-download-dynamics-of-hd-content-on-modern-social-networks/"><u>[Updated] 2024 Approved  Download Dynamics of HD Content on Modern Social Networks</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-your-system-without-relying-on-bitlocker/"><u>Securing Your System without Relying on Bitlocker</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-correct-sound-hiccup-in-audacity-on-windows-11/"><u>Strategies to Correct Sound Hiccup in Audacity on Windows 11</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/024-approved-the-components-that-lift-you-in-youtube-viewership/"><u>[New] 2024 Approved  The Components That Lift You in YouTube Viewership</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-the-hidden-potential-in-windows-powertoys-10-applications/"><u>Discover the Hidden Potential in Windows PowerToys' 10 Applications</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-how-to-add-subtitles-to-mkv-videos-on-all-platforms-for-2024/"><u>Updated How to Add Subtitles to MKV Videos on All Platforms for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-unlocking-elite-status-the-essentials-of-joining-discords-disconitro/"><u>2024 Approved  Unlocking Elite Status  The Essentials of Joining Discord's DiscoNitro</u></a></li>
<li><a href="https://windows11.techidaily.com/combating-steams-inability-to-synch-with-windows-folders/"><u>Combating Steam's Inability to Synch with Windows Folders</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-iso-images-from-your-windows-esd-originals/"><u>Crafting ISO Images From Your Windows' ESD Originals</u></a></li>
<li><a href="https://windows11.techidaily.com/5-essential-fixes-for-hypervisor-blue-screen-on-win-os/"><u>5 Essential Fixes for Hypervisor Blue Screen on WIN OS</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-click-rate-three-methods-for-mouse-double-click-tweaking/"><u>Enhance Click Rate: Three Methods for Mouse Double-Click Tweaking</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-in-2024-innovative-pfp-suggestions-to-differentiate-your-tiktok-presence/"><u>[Updated] In 2024, Innovative PFP Suggestions to Differentiate Your TikTok Presence</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-11-camera-app-eradicating-error-a00f425d/"><u>Troubleshooting Windows 11 Camera App: Eradicating Error A00F425D</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-twitter-vids-to-mp3-easy-extraction-techniques/"><u>[New] Twitter Vids to MP3  Easy Extraction Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-stalled-netflix-app-on-windows/"><u>Troubleshooting Stalled Netflix App on Windows</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-video-marketing-mastery-for-affiliate-success/"><u>[Updated] Video Marketing Mastery for Affiliate Success</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/how-to-write-a-script-for-a-youtube-video/"><u>How to Write a Script for a YouTube Video?</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-notetaking-for-windows-professionals-win11w10/"><u>Advanced Notetaking for Windows Professionals (Win11/W10)</u></a></li>
</ul></div>
