---
title: Steps for Correcting Windows Backup Defaults
date: 2024-08-22T21:35:55.188Z
updated: 2024-08-23T21:35:55.188Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps for Correcting Windows Backup Defaults
excerpt: This Article Describes Steps for Correcting Windows Backup Defaults
keywords: Fix Windows Backup Issues,Change Default Windows Backup,Reset Windows Backup Settings,Customize Windows Backup,Alter Backup Schedule,Modify Backup Destination,Adjust Backup Preferences
thumbnail: https://thmb.techidaily.com/f86f99b6d8051e2301c0b59b59f0f49d547931786fc3f8df51522ef8e8e5d47b.jpg
---

## Steps for Correcting Windows Backup Defaults

 System failure or data loss can cause huge amounts of damage and that’s why Windows offers a backup feature to protect your critical data. If your backups corrupt or otherwise function incorrectly, you can reset Windows Backup to its default settings. This guide will teach you some methods to reset Windows Backup to its default on Windows.

## How Do I Know if I Need to Reset Windows Backup?

 You may need to reset Windows Backup if your backups aren't working, taking too long to create, or you can't access the stored files. If you are experiencing these issues, resetting Windows Backup may resolve them.

 For this, either use the Command Prompt or create a batch file. The steps for both methods are outlined below and should help you get your backups running again.

## Is Resetting Window Backup Risky?

 While resetting Windows Backup is generally safe, there are some risks associated with it.

 Firstly, you may lose all existing backups if you reset Windows Backup. To ensure you don't lose data, [create a backup of the existing Windows files](https://www.makeuseof.com/tag/backup-windows-files-folders/) before resetting Windows Backup.

 Furthermore, the reset may affect some third-party apps. It's wise to check with your software vendor before resetting Windows Backup.

 If something goes wrong during the reset, you may have a corrupted backup configuration. In such cases, reinstall the operating system and start from scratch.

 Overall, resetting Windows Backup helps resolve existing issues, but take the necessary precautions to avoid potential risks.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901410&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix Pro - Software based live production. vMix Pro includes everything in vMix 4K plus 8 channels of Replay and 8 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## How to Reset Windows Backup to Its Factory Settings

 Now you know how to proceed with caution, here's how to reset Windows Backup to its factory settings.

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. Using Command Prompt

 If your current backup configuration isn't working, reset Windows Backup to its default settings. To get started, [run the Command Prompt with admin access](https://www.makeuseof.com/windows-run-command-prompt-admin/). In the Command Prompt window, run the following command:

`reg delete HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup /f`

 This will reset to the default configuration and remove all existing backups.

 After that, copy and paste the following command into the Command Prompt window and press **Enter**:

`reg add HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup`

 This will recreate the WindowsBackup entry in the registry editor. Next, type in and run the below command to delete the Automatic Backup scheduled task on Windows:

`schtasks /delete /tn "Microsoft\Windows\WindowsBackup\AutomaticBackup" /f`

 Finally, execute the below command to delete the backup monitor scheduled task:

`schtasks /delete /tn "Microsoft\Windows\WindowsBackup\Windows Backup Monitor" /f`

 After executing the above commands, restart your computer. This will reset Windows Backup to its default settings.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->
### 2\. Creating a Batch File

 If you're not comfortable with the command line interface, reset Windows Backup by creating a batch file.

 To do this, [open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) and paste the below code.

`<code>reg delete HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup /f  
reg add HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup  
schtasks /delete /tn "Microsoft\Windows\WindowsBackup\AutomaticBackup" /f  
schtasks /delete /tn "Microsoft\Windows\WindowsBackup\Windows Backup Monitor" /f`

 Click the **File** menu and select **Save as**. On the Save as dialog, type **reset-backup.bat** as the file name. Then choose **All Files** from the drop-down menu next to the Save as type. From the left panel, select **Desktop** and click the **Save** button.

 Now, close the Notepad window and right-click on the batch file. From the context menu, select **Run as administrator**. This will reset Windows Backup to its default settings.

 Lastly, restart your computer and you're done. These are two methods to reset Windows Backup to its default settings.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3727260&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## Get Your Backups Working Again on Windows

 Whether you use the command line interface or create a batch file, it's easy to reset Windows Backup. Just remember to restart your computer after the process completes successfully.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-capture.techidaily.com/new-dungeons-deep-and-deeper-old-school-and-hybrid-games-for-2024/"><u>[New] Dungeons Deep & Deeper  Old School and Hybrid Games for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-facetime-audibility-capturing-clear-audio-calls/"><u>[New] In 2024, FaceTime Audibility  Capturing Clear Audio Calls</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-capture-and-save-your-desktop-free-ways-on-windows/"><u>[Updated] Capture & Save Your Desktop - Free Ways on Windows</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-eyechrome-studio-direct-os-screencap-for-2024/"><u>[Updated] EyeChrome Studio  Direct OS Screencap for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-game-enhancement-select-top-hdds-for-xbox/"><u>[Updated] Game Enhancement  Select Top HDDs for Xbox</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-maximize-your-google-meet-experience-with-effective-use-of-digital-boards-on-any-os/"><u>[Updated] Maximize Your Google Meet Experience with Effective Use of Digital Boards on Any OS</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-unique-iphone-photo-style-adding-dynamic-motion-effects/"><u>[Updated] Unique iPhone Photo Style  Adding Dynamic Motion Effects</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-achieve-social-stardom-essential-tips-for-thriving-instagram-unboxings/"><u>2024 Approved  Achieve Social Stardom  Essential Tips for Thriving Instagram Unboxings</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-az-video-logger-full-application-breakdown/"><u>2024 Approved  AZ Video Logger  Full Application Breakdown</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-flashback-flair-top-80s-video-tricks-for-a-contemporary-edge/"><u>2024 Approved  Flashback Flair  Top 80S Video Tricks for a Contemporary Edge</u></a></li>
<li><a href="https://youtube-web.techidaily.com/approved-historical-knowledge-at-your-fingertips-best-yt-history-channels/"><u>2024 Approved  Historical Knowledge at Your Fingertips  Best YT History Channels</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/a-step-by-step-approach-add-a-linked-url-to-your-tiktok-profile-for-2024/"><u>A Step-by-Step Approach  Add a Linked URL to Your TikTok Profile for 2024</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723015949127-audio-malfunction-in-chrome-heres-the-fix-that-works/"><u>Audio Malfunction in Chrome? Here's the Fix That Works</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/audio-visual-innovators-group-for-2024/"><u>Audio-Visual Innovators Group for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/beyond-wonders-the-unseen-disadvantages-in-vr/"><u>Beyond Wonders  The Unseen Disadvantages in VR</u></a></li>
<li><a href="https://tech-revival.techidaily.com/comparing-creativity-in-3-bot-systems/"><u>Comparing Creativity in 3 Bot Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-the-performance-of-discord-searches-on-windows/"><u>Enhancing the Performance of Discord Searches on Windows</u></a></li>
<li><a href="https://fox-http.techidaily.com/explore-8-leading-free-srt-translators-online/"><u>Explore 8 Leading Free SRT Translators Online</u></a></li>
<li><a href="https://windows11.techidaily.com/file-explorer-missing-sd-card-resolution-guide/"><u>File Explorer Missing SD Card: Resolution Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-utorrent-connectivity-problems-on-pcs/"><u>Fixing uTorrent Connectivity Problems on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-voice-typing-malfunction-error-code-0x80049dd3-on-windows-11/"><u>Fixing Voice Typing Malfunction (Error Code: 0X80049DD3) on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-showhide-directories-on-modern-windows-11-pcs/"><u>Guide to Show/Hide Directories on Modern Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-error-code-0xc00000f-with-ease-on-pcs/"><u>Handling Error Code 0xC00000F with Ease on PCs</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-do-i-add-my-signature-to-excel-2016-files-by-ldigisigner-sign-a-excel-sign-a-excel/"><u>How do i add my signature to Excel 2016 files</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-get-the-right-network-drivers-for-your-hp-system-on-win10win8win7/"><u>How to Get the Right Network Drivers for Your HP System on Win10/Win8/Win7</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-plain-out-windows-edges/"><u>How to Plain Out Windows Edges</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-call-logs-from-realme-12plus-5g-by-fonelab-android-recover-call-logs/"><u>How to rescue lost call logs from Realme 12+ 5G</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-iphone-15-pro-with-an-apple-watch-and-what-to-do-if-it-doesnt-work-by-drfone-ios/"><u>How to Unlock iPhone 15 Pro With an Apple Watch & What to Do if It Doesnt Work</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-edit-and-send-fake-location-on-telegram-for-your-oppo-find-n3-in-3-ways-drfone-by-drfone-virtual-android/"><u>In 2024, Edit and Send Fake Location on Telegram For your Oppo Find N3 in 3 Ways | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-can-infinix-note-30-vip-racing-editionmirror-share-to-pc-drfone-by-drfone-android/"><u>In 2024, How Can Infinix Note 30 VIP Racing EditionMirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-remove-a-previously-synced-google-account-from-your-samsung-galaxy-f34-5g-by-drfone-android/"><u>In 2024, How to Remove a Previously Synced Google Account from Your Samsung Galaxy F34 5G</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-tap-out-of-tiktok-clutter-editing-guide-for-massive-drafts/"><u>In 2024, Tap Out of TikTok Clutter  Editing Guide for Massive Drafts</u></a></li>
<li><a href="https://windows11.techidaily.com/integrating-dns-client-service-in-windows-11-with-precision/"><u>Integrating DNS Client Service in Windows 11 with Precision</u></a></li>
<li><a href="https://windows11.techidaily.com/iphoneandroid-your-smartphone-as-a-windows-microphone/"><u>IPhone/Android: Your Smartphone as a Windows Microphone</u></a></li>
<li><a href="https://windows11.techidaily.com/key-collectors-rejoice-get-the-perfect-pair-of-keys-and-essential-windows-11-612lifetime/"><u>Key Collectors Rejoice – Get the Perfect Pair of Keys & Essential Windows 11, $6.12/Lifetime!</u></a></li>
<li><a href="https://fox-that.techidaily.com/mastering-dfu-a-guide-to-solving-5-widespread-problems-on-iphones/"><u>Mastering DFU: A Guide to Solving 5 Widespread Problems on iPhones</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-image-spin-6-tactics-for-windows-11/"><u>Mastering Image Spin: 6 Tactics for Windows 11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/mastering-the-art-of-picture-customization-for-samsung-series-9-4k-panels/"><u>Mastering the Art of Picture Customization for Samsung Series 9 4K Panels</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-quick-start-for-rdc-on-windows-11/"><u>Mastering the Art of Quick Start for RDC on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-guide-to-inspecting-windows-11-history/"><u>Mastery Guide to Inspecting Windows 11 History</u></a></li>
<li><a href="https://windows11.techidaily.com/minimizing-distractions-with-wins-management-on-win-11/"><u>Minimizing Distractions with Wins Management on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-local-gpo-on-windows-with-ease/"><u>Navigating Local GPO on Windows with Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-past-windows-terminal-lockup/"><u>Navigating Past Windows Terminal Lockup</u></a></li>
<li><a href="https://windows11.techidaily.com/old-meets-new-a-windows-11-transformation-into-98-style/"><u>Old Meets New: A Windows 11 Transformation Into 98 Style</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-error-x8019-on-windows-xp/"><u>Preventing Error X8019 on Windows XP</u></a></li>
<li><a href="https://windows11.techidaily.com/purge-your-pcs-defender-footprint-with-easy-steps/"><u>Purge Your PC’s Defender Footprint with Easy Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-loading-issues-on-discord-software/"><u>Quick Fixes for Loading Issues on Discord Software</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-linguistic-leap-translating-words-via-windows-1011-hotkeys/"><u>Quick Linguistic Leap: Translating Words via Windows 10/11 Hotkeys</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-tips-reactivate-your-calendar-and-mail-on-w11/"><u>Quick Tips: Reactivate Your Calendar & Mail on W11</u></a></li>
<li><a href="https://network-issues.techidaily.com/re-enabling-displays-on-nvidia-gpus/"><u>Re-Enabling Displays on NVIDIA GPUs</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-discords-loading-failures-in-windows/"><u>Resolving Discord's Loading Failures in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-non-functional-activation-in-os-11/"><u>Resolving Non-Functional Activation in OS 11</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-note-taking-tips-for-windows-11-users/"><u>Seamless Note-Taking Tips for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-windows-7-techniques-against-uac-intrusions/"><u>Securing Windows: 7 Techniques Against UAC Intrusions</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/sim-unlock-lava-yuva-3-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>Sim Unlock Lava Yuva 3 Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/speeding-up-epic-games-installation-windows-wise/"><u>Speeding Up Epic Games Installation Windows-Wise</u></a></li>
<li><a href="https://win-blog.techidaily.com/step-by-step-guide-to-troubleshoot-non-recording-problems-with-obs-software/"><u>Step-by-Step Guide to Troubleshoot Non-Recording Problems with OBS Software</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-rectify-non-registered-hdds/"><u>Techniques to Rectify Non-Registered HDDs</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-spotify-link-failures-on-pcs-windows/"><u>Troubleshooting Spotify Link Failures on PCs (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/turn-onoff-text-emphasis-and-highlight-effects-on-pc/"><u>Turn On/Off Text Emphasis and Highlight Effects on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/turn-onoff-windows-key-like-a-pro/"><u>Turn On/Off Windows Key Like a Pro</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/understanding-current-availability-of-chatgpt/"><u>Understanding Current Availability of ChatGPT</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-copy-and-paste-features-with-application-guard-in-edge-w11-edition/"><u>Unlocking Copy & Paste Features with Application Guard in Edge, W11 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-7-key-windows-11-widgets-for-enhanced-productivity/"><u>Unveiling 7 Key Windows 11 Widgets for Enhanced Productivity</u></a></li>
<li><a href="https://windows11.techidaily.com/visualizing-disks-wisely-the-windows-methodology/"><u>Visualizing Disks Wisely: The Windows Methodology</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>