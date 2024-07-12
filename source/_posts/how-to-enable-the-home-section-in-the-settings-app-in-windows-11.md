---
title: How to Enable the Home Section in the Settings App in Windows 11
date: 2024-07-11T21:54:10.780Z
updated: 2024-07-12T21:54:10.780Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Enable the Home Section in the Settings App in Windows 11
excerpt: This Article Describes How to Enable the Home Section in the Settings App in Windows 11
keywords: Windows 11 Home Setup,Enabling Windows Sections,Windows Settings Access,Home Area Activation Win11,Windows 11 Interface Section,Windows 11 Home Config,Windows 11 Navigation Menu
thumbnail: https://thmb.techidaily.com/53ddbe6924d2ddfb268e4678d76937abc181d4038a95a53ae70246e54e37c443.jpg
---

## How to Enable the Home Section in the Settings App in Windows 11

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
<li><a href="https://windows11.techidaily.com/the-blueprint-for-a-more-effective-and-reliable-windows-11/"><u>The Blueprint for a More Effective and Reliable Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/clear-and-constructive-icon-arrangement-ideas/"><u>Clear and Constructive Icon Arrangement Ideas</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-insufficient-spec-on-game-captures/"><u>Troubleshooting Insufficient Spec on Game Captures</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-9-oppo-reno-11-pro-5g-monitoring-apps-for-parental-controls-drfone-by-drfone-virtual-android/"><u>In 2024, Top 9 Oppo Reno 11 Pro 5G Monitoring Apps for Parental Controls | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-no-audio-devices-in-windows/"><u>Addressing 'No Audio Devices' In Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/top-essential-gratis-tools-for-windows-11-enthusiasts/"><u>Top Essential Gratis Tools for Windows 11 Enthusiasts</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-on-apple-iphone-6-drfone-by-drfone-virtual-ios/"><u>How to Fake Snapchat Location on Apple iPhone 6 | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-discovering-the-top-10-invisible-story-lovers-for-2024/"><u>[Updated] Discovering the Top 10 Invisible Story Lovers for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-circumvent-no-more-files-alert/"><u>Strategies to Circumvent No More Files Alert</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-tips-install-outlook-preview-in-w10w11/"><u>Easy Tips: Install Outlook Preview in W10/W11</u></a></li>
<li><a href="https://android-location.techidaily.com/fake-android-location-without-rooting-for-your-infinix-zero-30-5g-drfone-by-drfone-virtual/"><u>Fake Android Location without Rooting For Your Infinix Zero 30 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-0xa00f4243-overlapping-camera-usage-in-apps/"><u>Troubleshooting 0xA00F4243: Overlapping Camera Usage in Apps</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-hidefake-snapchat-location-on-your-honor-100-drfone-by-drfone-virtual-android/"><u>How to Hide/Fake Snapchat Location on Your Honor 100 | Dr.fone</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-in-2024-cutting-through-the-differences-final-cut-pro-vs-express/"><u>Updated In 2024, Cutting Through the Differences Final Cut Pro vs Express</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-prints-with-microsoft-defender-smartscreen-edge/"><u>Configuring Prints with Microsoft Defender SmartScreen Edge</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-exploration-of-windows-narrators-legacy-keys/"><u>Comprehensive Exploration of Windows Narrator's Legacy Keys</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/2024-approved-rock-solid-videos-best-free-video-stabilization-tools-for-pc-and-mac/"><u>2024 Approved Rock-Solid Videos Best Free Video Stabilization Tools for PC and Mac</u></a></li>
<li><a href="https://extra-tips.techidaily.com/essential-tips-for-youtube-video-to-mpeg/"><u>Essential Tips for YouTube Video to MPEG</u></a></li>
<li><a href="https://android-location-track.techidaily.com/ways-to-stop-parent-tracking-your-realme-v30-drfone-by-drfone-virtual-android/"><u>Ways to stop parent tracking your Realme V30 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-windows-taskbar-recovery/"><u>Strategies for Windows Taskbar Recovery</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-guide-on-how-to-change-your-apple-id-email-address-on-iphone-12-mini-by-drfone-ios/"><u>In 2024, Guide on How To Change Your Apple ID Email Address On iPhone 12 mini</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/in-2024-exclusive-list-affordable-mac-video-editing-on-tiktok/"><u>In 2024, Exclusive List  Affordable Mac Video Editing on TikTok</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-steam-login-errors-on-windows-via-rust-coding/"><u>Eliminating Steam Login Errors on Windows via Rust Coding</u></a></li>
<li><a href="https://windows11.techidaily.com/systematic-approach-to-eliminate-flashing-on-windows/"><u>Systematic Approach to Eliminate Flashing on Windows</u></a></li>
<li><a href="https://extra-hints.techidaily.com/best-mobile-gif-apps-roundup-for-latest-phones/"><u>Best Mobile GIF Apps Roundup for Latest Phones</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-reminders-in-every-window-of-your-pc/"><u>Efficient Reminders in Every Window of Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionizing-mouse-interactions-on-windows-via-clicklock-techniques/"><u>Revolutionizing Mouse Interactions on Windows via ClickLock Techniques</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-how-to-change-your-tiktok-username/"><u>[New] In 2024, How to Change Your TikTok Username</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-and-forge-a-friendly-startup-in-windows-amidst-errors/"><u>Fix and Forge a Friendly Startup in Windows Amidst Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-guide-to-brightening-the-windows-11-pointer/"><u>The Essential Guide to Brightening the Windows 11 Pointer</u></a></li>
<li><a href="https://techidaily.com/complete-guide-to-hard-reset-your-oppo-a1-5g-drfone-by-drfone-reset-android-reset-android/"><u>Complete Guide to Hard Reset Your Oppo A1 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/did-rav-antivirus-suddenly-appear-on-your-windows-pc-heres-where-it-came-from-and-how-to-uninstall-it/"><u>Did RAV Antivirus Suddenly Appear on Your Windows PC? Here's Where It Came From & How to Uninstall It</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-the-full-capabilities-of-docker-in-wsl-2-windows/"><u>Unleashing the Full Capabilities of Docker in WSL 2 Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11-safe-mode-an-easy-six-step-plan/"><u>Unlocking Windows 11 Safe Mode: An Easy Six-Step Plan</u></a></li>
<li><a href="https://windows11.techidaily.com/cherishing-the-slumber-of-your-computer/"><u>Cherishing the Slumber of Your Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/tactile-hover-over-customizing-your-click-experience-in-win11/"><u>Tactile Hover Over: Customizing Your Click Experience in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/blocking-windows-update-prompts/"><u>Blocking Windows Update Prompts</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-biometric-control-in-w11-for-domain-users/"><u>Secure Biometric Control in W11 for Domain Users</u></a></li>
<li><a href="https://activate-lock.techidaily.com/ultimate-guide-from-iphone-15-icloud-activation-lock-bypass-by-drfone-ios/"><u>Ultimate Guide from iPhone 15 iCloud Activation Lock Bypass</u></a></li>
<li><a href="https://windows11.techidaily.com/skyrocketing-vm-potential-in-windows-implement-these-top-strategies/"><u>Skyrocketing VM Potential in Windows - Implement These Top Strategies</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-streamlining-board-collaboration-a-compreenasion-of-using-whiteboards-on-all-zoom-platforms/"><u>In 2024, Streamlining Board Collaboration - A Compreenasion of Using Whiteboards on All Zoom Platforms</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-revamp-your-google-group-chats-with-4-tips/"><u>[Updated] Revamp Your Google Group Chats with 4 Tips</u></a></li>
<li><a href="https://extra-skills.techidaily.com/ringsong-blueprint-guide-for-turning-tamil-tracks-into-notifications-for-2024/"><u>RingSong Blueprint  Guide for Turning Tamil Tracks Into Notifications for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-windows-errors-during-amd-195-installation/"><u>Eliminating Windows Errors During AMD 195 Installation</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-60-quick-witty-tiktok-one-liners/"><u>[Updated] 60 Quick Witty TikTok One-Liners</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-is-there-a-science-to-youtubes-quick-subscribe-tactic/"><u>[Updated] Is There a Science to YouTube's Quick Subscribe Tactic?</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-2024-approved-did-you-know-cameras-have-a-built-in-feature-to-shoot-slow-motion-clips-this-article-is-about-using-sony-sandq-to-capture-slow-motion-/"><u>Updated 2024 Approved Did You Know Cameras Have a Built-In Feature to Shoot Slow-Motion Clips? This Article Is About Using Sony S&Q to Capture Slow-Motion Scenes</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-winscomrssvrdll-anomaly-during-boot-up/"><u>Tackling the Winscomrssvr.dll Anomaly During Boot-Up</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-2024-approved-how-to-use-picture-in-picture-pip-on-microsoft-edge/"><u>[New] 2024 Approved  How to Use Picture in Picture (PIP) on Microsoft Edge</u></a></li>
<li><a href="https://windows11.techidaily.com/unwrapping-the-mystery-of-monitor-miscalibration/"><u>Unwrapping the Mystery of Monitor Miscalibration</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-unraveling-zdsofts-screen-monitor-magic/"><u>[New] In 2024, Unraveling ZDSoft's Screen Monitor Magic</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-eliminate-windows-error-xc0f1103f-on-geforce/"><u>Steps to Eliminate Windows Error XC0F1103F on GeForce</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-premium-macpc-video-recording-software/"><u>[Updated] Premium Mac/PC Video Recording Software</u></a></li>
<li><a href="https://windows11.techidaily.com/the-magic-behind-the-scenes-in-photo-app-delete/"><u>The Magic Behind the Scenes in Photo App Delete</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/selecting-fps-for-videos-why-not-both-30-or-60-in-2024/"><u>Selecting FPS for Videos  Why Not Both, 30 or 60, In 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-premier-visionaries-in-multimedia-creation/"><u>[New] Premier Visionaries in Multimedia Creation</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-windows-for-wordpad-operability/"><u>Exploring Windows for WordPad Operability</u></a></li>
<li><a href="https://windows11.techidaily.com/win11s-unnecessary-filler-heres-how-to-tackle-it/"><u>Win11's Unnecessary Filler? Here’s How To Tackle It</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-lessening-high-cpu-demand-from-tiworkerexe-tasks/"><u>Strategies for Lessening High CPU Demand From TiWorker.exe Tasks</u></a></li>
<li><a href="https://windows11.techidaily.com/the-complete-surface-computing-firmware-upgrade-manual/"><u>The Complete Surface Computing Firmware Upgrade Manual</u></a></li>
</ul></div>
