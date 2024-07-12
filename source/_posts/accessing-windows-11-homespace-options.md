---
title: Accessing Windows 11 Homespace Options
date: 2024-07-11T22:06:26.792Z
updated: 2024-07-12T22:06:26.792Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Accessing Windows 11 Homespace Options
excerpt: This Article Describes Accessing Windows 11 Homespace Options
keywords: Windows 11 Setup,HomeSpace Access,Win11 Launcher,Homespace Settings,Enter Win11,Windows Desktop Space,Windows 11 Interface
thumbnail: https://thmb.techidaily.com/0608abec5e89fbdabfc438dbc05f250f26c6343ebf5ad117060d9466fac18ee3.jpg
---

## Accessing Windows 11 Homespace Options

 Microsoft introduced the Settings app in Windows 8 and has since worked to improve the overall usability of the app. Its design has undergone several changes and the new one in Windows 11 looks much better due to the better UI and feature organization.

 However, it isn't just a cosmetic change because many utilities and Control Panel items are migrated to the Settings app. Microsoft also released a different version of the Settings app which incorporates a new Home section and a layout that will help you access the most commonly used settings. Let’s learn how to enable it on your PC.

## What's Wrong With the Old Settings App?

 The old Settings app directly opens the System section when you launch it. This section contains the most common settings like Display, Sound, Storage, Troubleshooting, and more. But you will still have to use the left side menu to access common settings such as Network, Personalization, Bluetooth, One Drive, and more.

![Current Settings app-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/current-settings-app-1.jpg)

 Microsoft noticed this issue and created a new Home section in the revamped Settings app. At the time of writing, you can only find this new Settings app in the Windows Insider program.

 The new Home section brings all the common settings under one roof, so the users don't have to dive deep into the Settings app to change a network or personalization setting.

## How to Enable the Home Section in the Settings App

 Repeat the following steps to enable and use the Home section in the Settings App:

### 1\. Download the Latest Insider Build and ViveTool

 The new Settings app with a Home section is available in the Windows Insider Dev build 23493\. So, you must update your PC enrolled in the Dev channel to the build version 23493 or above. If you don't want to enroll your PC into the Windows Insider program or want to try out the build in a virtual machine, there’s an easy way.

 You can [use UPP DUMP to download Windows Insider builds without enrolling in the Windows Insider program](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/). After the download completes, you will have to perform an in-place upgrade or create a bootable USB drive to install the Dev build on your PC.

 The enhanced Settings app with the included Home section isn't directly available in build 243943\. So, you must use Vivetool to enable the experimental feature. All you need to do is [download ViveTool from GitHub](https://github.com/thebookisclosed/ViVe/releases).

 After the download completes, navigate to the download location using File Explorer and extract the contents of the archive to a folder named "**Vive**". Move the folder containing the Vivetool to the **C** drive.

### 2\. Enable the Home Section in the Settings App

 After updating your Windows PC and installing Vivetool, repeat the following steps:

1. Press **Win + R** to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **cmd** in the text box and press the **Ctrl + Shift + Enter** keys simultaneously.
2. The User Account Control window will pop up. Click on the **Yes** button.
3. First, you need to switch to the drive where you extracted the Vivetool. Type **cd c:\\** in the Command Prompt window and press the **Enter** key to execute the command.
4. Now, you need to switch to the folder where Vivetool is present. Since we extracted the tool to a folder named “**Vive**” our command becomes: **cd vive**.
5. Type **vivetool** and press the **Enter** key to check if the tool runs perfectly or not.  
![Enable the New Home Section in the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-the-new-home-section-in-the-settings-app.jpg)
6. Now, type the following commands and press the **Enter** key to execute them one by one:  
`vivetool /enable /id:42058345  
vivetool /enable /id:42058313`
7. **Close** the Command Prompt window.  
![Enable the New Home Section in the Settings App 2-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-the-new-home-section-in-the-settings-app-2-1.jpg)
8. **Restart** your PC to apply the changes made by the Vivetool in the Settings app.

## What Does the Enhanced Settings App Look Like?

 We compared the experimental and the old Settings app, and there are a few noticeable changes. For example, you automatically land on the Home section every time you open the enhanced Settings app.

 As a result, it is easier to access commonly uses settings. For instance, the top section shows your current internet connection, alongside a Windows Update check button.

![New and old settings app side by side-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/new-and-old-settings-app-side-by-side-1.jpg)

 Below that, there is a card that displays the recommended settings. You also get a bird’s eye view of the total available storage space in your Outlook account. There’s also a much-needed personalization card that you can use to change the themes and color mode of your Windows PC.

 If you haven’t completed a crucial security setup for your Microsoft account, you will see a reminder on the Home Page. Apart from that, Microsoft brazenly promotes its Microsoft service as a separate card. You cannot rearrange or remove tiles, so you are stuck with the layout and the promotional stuff from Microsoft.

![New home section in the settings app-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/new-home-section-in-the-settings-app-1.jpg)

 Still, it is a much-needed overhaul from the existing Settings app, which will improve the overall user experience. Microsoft is also trying out a Home section in the File Explorer app.

## A Revamped Settings App on Windows

 Microsoft’s take on the new Home section in the Settings app is a change we would definitely want to see in the stable builds in the upcoming months. But there are major changes arriving to the File Explorer and other Windows apps like the Photos app which recently got an update to support the dark mode and some zoom and usability improvements.

 However, it isn't just a cosmetic change because many utilities and Control Panel items are migrated to the Settings app. Microsoft also released a different version of the Settings app which incorporates a new Home section and a layout that will help you access the most commonly used settings. Let’s learn how to enable it on your PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/bypassing-blocked-windows-guard-functions/"><u>Bypassing Blocked Windows Guard Functions</u></a></li>
<li><a href="https://windows11.techidaily.com/clandestine-control-center-hidepower-command-of-windows-11/"><u>Clandestine Control Center: Hidepower Command of Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/best-windows-laptops-a-forward-looking-2024-review/"><u>Best Windows Laptops: A Forward-Looking 2024 Review</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-sign-jpeg-by-digital-signature-by-ldigisigner-sign-a-jpg-sign-a-jpg/"><u>How to sign .jpeg by digital signature</u></a></li>
<li><a href="https://howto.techidaily.com/android-safe-mode-how-to-turn-off-safe-mode-on-oppo-reno-10-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Android Safe Mode - How to Turn off Safe Mode on Oppo Reno 10 5G? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-messages-from-nokia-by-fonelab-android-recover-messages/"><u>How to retrieve erased messages from Nokia</u></a></li>
<li><a href="https://extra-information.techidaily.com/step-by-step-ios-download-episodes-like-a-pro/"><u>Step-by-Step iOS  Download Episodes Like a Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-windows-notepad-malfunctions/"><u>Taming Windows Notepad Malfunctions</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-science-and-magic-behind-perfecting-luts-for-2024/"><u>The Science and Magic Behind Perfecting LUTs for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/chroma-mastery-made-easy-a-complete-guide-to-green-screen-filmmaking/"><u>Chroma Mastery Made Easy  A Complete Guide to Green Screen Filmmaking</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/capture-the-moment-premium-snapchat-lenses-on-display/"><u>Capture the Moment  Premium Snapchat Lenses on Display</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-complete-breakdown-the-android-adaptation-of-lightroom-app/"><u>[New] Complete Breakdown  The Android Adaptation of Lightroom App</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-celestial-composition-the-art-of-nighttime-photography-mastery/"><u>In 2024, Celestial Composition  The Art of Nighttime Photography Mastery</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-earn-extra-your-guide-to-joining-the-youtube-premium-club/"><u>[New] Earn Extra  Your Guide to Joining the YouTube Premium Club</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-craft-cinematic-edits-with-ease-and-precision-in-camtasia-9/"><u>[New] In 2024, Craft Cinematic Edits with Ease and Precision in Camtasia 9</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-webp-images-top-4-viewer-tools-on-windows-os/"><u>Elevate WebP Images: Top 4 Viewer Tools on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/take-control-of-your-workflow-learn-these-essential-cmd-commands/"><u>Take Control of Your Workflow: Learn These Essential CMD Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-computer-recovery-top-10-tactics/"><u>Conquering Computer Recovery: Top 10 Tactics</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-samsung-galaxy-xcover-6-pro-tactical-edition-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Samsung Galaxy XCover 6 Pro Tactical Edition Reset Code | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-silent-reading-mode-on-ms-word-for-win-users/"><u>Troubleshooting Silent Reading Mode on MS Word for Win Users</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-performance-gauges-for-pcs/"><u>Efficient Performance Gauges for PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/triggering-the-verification-toolset-for-win11-systems/"><u>Triggering the Verification Toolset for Win11 Systems</u></a></li>
<li><a href="https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-oneplus-nord-ce-3-lite-5g-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Troubleshooting Guide How to Fix an Unresponsive OnePlus Nord CE 3 Lite 5G Screen | Dr.fone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/visualize-your-story-with-top-snapchat-augments/"><u>Visualize Your Story with Top Snapchat Augments</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-intrinsic-insights-for-instant-identification-in-fb/"><u>In 2024, Intrinsic Insights for Instant Identification in FB</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-code-0x800700e1-problems-in-windows-11/"><u>Fixing Code 0X800700E1 Problems in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/confronting-windows-search-failure-a-fixers-manual/"><u>Confronting Windows Search Failure: A Fixer's Manual</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-spotify-connection-errors-in-win11/"><u>Tackling Spotify Connection Errors in Win11</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-identify-missing-drivers-with-windows-device-manager-on-windows-11-and-10-and-7-by-drivereasy-guide/"><u>Use Device Manager to identify missing drivers with Windows Device Manager on Windows 11 & 10 & 7</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-change-video-speed-with-ffmpeg/"><u>Updated Change Video Speed with FFmpeg</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-image-precision-with-windows-11s-blurring-feature-in-photos-app/"><u>Unlocking Image Precision with Windows 11'S Blurring Feature in Photos App</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-a-closer-look-at-avs-video-editor-2023-review-and-ratings-for-2024/"><u>Updated A Closer Look at AVS Video Editor 2023 Review and Ratings for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/creating-cost-effective-youtube-closure-elements-for-2024/"><u>Creating Cost-Effective YouTube Closure Elements for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-master-your-setlist-top-dj-audio-repositories/"><u>In 2024, Master Your Setlist Top DJ Audio Repositories</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-mastering-airtunes-on-your-apple-devices-quick-guide-to-repairs/"><u>[New] Mastering Airtunes on Your Apple Devices - Quick Guide to Repairs</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-insider-clandestine-context-creation-techniques/"><u>Windows 11 Insider: Clandestine Context Creation Techniques</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-winning-at-tiktok-actions-for-more-views-and-favorites-for-2024/"><u>[Updated] Winning at TikTok  Actions for More Views & Favorites for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-productivity-hotkey-tricks-to-reconfigure-windows/"><u>Enhance Productivity: Hotkey Tricks to Reconfigure Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-and-fixing-windows-11s-error-1132-in-zoom-app/"><u>Unraveling and Fixing Windows 11'S Error 1132 in Zoom App</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-navigate-the-best-tiktok-analytics-tools-for-improved-growth/"><u>[New] 2024 Approved  Navigate the Best TikTok Analytics Tools for Improved Growth</u></a></li>
<li><a href="https://win11.techidaily.com/dxgidll-lost-files-restore-with-smart-windows-11-fixes/"><u>Dxgi.dll Lost Files? Restore with Smart Windows 11 Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/win10s-method-for-onedrive-placement-shift/"><u>Win10's Method for OneDrive Placement Shift</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-top-rated-iphone-apps-expert-reviews-and-rankings/"><u>In 2024, Top-Rated iPhone Apps Expert Reviews and Rankings</u></a></li>
<li><a href="https://activate-lock.techidaily.com/a-how-to-guide-on-bypassing-the-iphone-15-plus-icloud-lock-by-drfone-ios/"><u>A How-To Guide on Bypassing the iPhone 15 Plus iCloud Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicate-error-e1-in-windows-10-11-editions/"><u>Eradicate Error E1 in Windows 10, 11 Editions</u></a></li>
<li><a href="https://windows11.techidaily.com/briskly-boost-printer-functionality/"><u>Briskly Boost Printer Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/the-path-to-professional-print-perfection-nine-key-techniques-for-powerpoint-on-pcs/"><u>The Path to Professional Print Perfection: Nine Key Techniques for PowerPoint on PCs</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-seamless-soundwave-capture-essential-techniques-for-podcast-storage-on-computers/"><u>New Seamless Soundwave Capture Essential Techniques for Podcast Storage on Computers</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-masterful-zoom-techniques-simple-iphone-solutions/"><u>2024 Approved  Masterful Zoom Techniques  Simple iPhone Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/augmenting-mac-operations-with-windows-tech/"><u>Augmenting Mac Operations with Windows Tech</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-device-guide-for-google-meet-access/"><u>[Updated] Device Guide for Google Meet Access</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-tab-navigation-windows-11-enhanced-guide/"><u>The Art of Tab Navigation: Windows 11 Enhanced Guide</u></a></li>
<li><a href="https://android-frp.techidaily.com/latest-guide-how-to-bypass-lava-blaze-curve-5g-frp-without-computer-by-drfone-android/"><u>Latest Guide How To Bypass Lava Blaze Curve 5G FRP Without Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/dive-into-ms-store-app-selection-2023-edition/"><u>Dive Into MS Store App Selection: 2023 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-conversion-technique-windows-11-heic-to-jpeg/"><u>Effortless Conversion Technique: Windows 11 HEIC to JPEG</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-for-correcting-windows-update-problems-0x30017/"><u>Expert Tips for Correcting Windows Update Problems (0X30017)</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-missing-sign-in-screens-in-windows-11/"><u>Bypassing Missing Sign-In Screens in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/1719278005537-mastery-of-solutions-for-non-operational-wwinplusp-in-pc/"><u>Mastery of Solutions for Non-Operational WWin+P in PC.</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-ineffectual-window-11-desktop-options/"><u>Fixing Ineffectual Window 11 Desktop Options</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-your-digital-contents-full-value-winning-at-powerpoint-prints-in-windows/"><u>Unlocking Your Digital Content's Full Value: Winning at PowerPoint Prints in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-the-disconnection-problem-for-malwarebytes-in-windows-11/"><u>Fixing the Disconnection Problem for Malwarebytes in Windows 11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-check-if-your-itel-a05s-is-unlocked-by-drfone-android/"><u>In 2024, How To Check if Your Itel A05s Is Unlocked</u></a></li>
<li><a href="https://windows11.techidaily.com/breath-of-fresh-air-for-windows-13-revival-techniques/"><u>Breath of Fresh Air for Windows: 13 Revival Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/5-strategies-for-resolving-the-no-support-windows-error/"><u>5 Strategies for Resolving the No-Support Windows Error</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-you-when-your-samsung-galaxy-s24-is-off-drfone-by-drfone-virtual-android/"><u>Can Life360 Track You When Your Samsung Galaxy S24 is off? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-shared-printer-issues-on-windows-11/"><u>Addressing Shared Printer Issues on Windows 11</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-yearly-viewer-ranking-twitters-hottest-topics/"><u>[New] In 2024, Yearly Viewer Ranking  Twitters' Hottest Topics</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-androids-best-face-to-face-apps-the-ultimate-list/"><u>Updated Androids Best Face-to-Face Apps The Ultimate List</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-ftdibussys-understanding-its-role-in-windows-memory-controls/"><u>Decoding ftdibus.sys: Understanding Its Role in Windows Memory Controls</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-task-monitor-in-win-11-accelerating-real-time-updates/"><u>Boosting Task Monitor in Win 11: Accelerating Real-Time Updates</u></a></li>
</ul></div>
