---
title: Altering WinTerral's Visual Theme
date: 2024-07-11T21:11:39.063Z
updated: 2024-07-12T21:11:39.063Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Altering WinTerral's Visual Theme
excerpt: This Article Describes Altering WinTerral's Visual Theme
keywords: WinTerral Theme Change,Altered WinTerral Appearance,Theme Customization WinTerral,Redesigning WinTerral UI,WinTerral Visual Update,WinTerral Aesthetic Overhaul,Personalized WinTerral Look
thumbnail: https://thmb.techidaily.com/0c63aae4422094d29361ca7d174981f6a34db77ad2868353babe77ecee3079bf.jpg
---

## Altering WinTerral's Visual Theme

 Changing the background image of the Windows Terminal is an easy way to customize your command line experience. This adds a personal touch and makes your experience visually appealing.

 This tutorial will explain three methods to change the Terminal background image in Windows 11.

## How to Change Windows Terminal Background Image

 You can change the background image of Windows Terminal in three ways: using the**Default** option within the Terminal app or manually editing the settings.json file using**File Explorer** and**Run** dialog box. All three methods achieve the same result and are easy to use.

 Using the default option is the simplest way to change your background image while editing the settings.json file provides more control and customization options. Below, we will guide you through each option.

## 1\. Change Windows Terminal Background Image via Its Options

 The easiest way to change the background image of Windows Terminal is by using its option. This can be done by opening Windows Terminal and changing settings within the app. Here's how to do it:

 To get started, open the Windows Terminal application first. For this, click on the Windows icon to open the Start menu. Then type**Terminal** into the search box, and select it from the list.

 Once you open the Terminal application, click on the dropdown menu icon in the top left corner, and select the**Settings** option.

 In the settings window's left column, go to**Defaults** . Now move to the right side of the page and tap**Appearance** to expand it.

![Change Windows Terminal Background Image via Default Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-windows-terminal-background-image-via-default-option.jpg)

 Scroll down to the**Background image** section, then click the**Background image path** option. Next, click the**Browse** option and select an image you want to use as a background.

 Click**Open** to confirm your selection. Now you should be able to see the selected image as the background of the terminal.

 You can also copy and paste the file path of an image directly into the Background image path option. Finally, click the**Save** button and the background image will be set.

 To improve the appearance of your image in the Windows Terminal, you can customize it using several options. You can use**Background image stretch mode** to change how the image is resized to fill the window. Further, you can change the**Background image alignment** to adjust the image position, and**Background image opacity** to make it more or less transparent.

 Once you are satisfied with the changes, click the**Save** button in order to apply them. Your custom background image should now be visible in the Windows Terminal.

 If you want to switch to the default image,[reset the Windows Terminal to its default settings](https://www.makeuseof.com/windows-11-reset-terminal-settings/) . This will automatically restore your background to the default image.

## 2\. Change the Windows Terminal Background Image via Windows File Explorer

 Manually editing settings.json is another great way to customize your Windows Terminal background image. For this, you need to open the settings.json file in any text editor, such as Notepad. Here's how to do it:

1. Open Windows File Explorer (see our guide on [how to open File Explorer on a Windows PC](https://www.makeuseof.com/windows-open-file-explorer/) ).
2. Once you're in File Explorer, navigate to your**C:** drive and select the**Users** folder.
3. Locate your**username** in this folder, then open the**AppData** folder and the**Local** folder.
4. In the Local folder, find and open the**Packages** folder.
5. Look for the**Microsoft.WindowsTerminal\_8wekyb3d8bbwe** folder and open it.
6. Finally, in this folder, double-click on**Settings** to open settings.json in any text editor.

 In the settings.json file, you will find a section called**backgroundImage** . You can use**Ctrl + F** to find it quickly.

 This is where you can enter the path of your own image to set as the Windows Terminal background. To do this, first copy the full file path for the image you want to use, including the file name.

![How to Change Windows Terminal Background Image From Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/how-to-change-windows-terminal-background-image-from-windows-file-explorer.jpg)

 Then paste this path into the**backgroundImage** section of settings.json. Remember to include a comma (**,**) after the path, as shown in the image above.

 Once you have pasted the path of your image, save the settings file and close the text editor. To apply this new background image, simply restart your Windows Terminal. The new background image should be displayed on the terminal window.

 You can adjust the image transparency using the same method. Simply input values for the**backgroundImageOpacity** parameters to modify the settings. These additional settings allow you to personalize your Windows Terminal background image even further.

 Restart Windows Terminal for the changes to take effect. In this way, you can easily customize your Windows Terminal background image using the settings.json file.

## 3\. Change the Windows Terminal Background Image Using the Run Command

 The Run Command can also help you change your Windows Terminal background image. Instead of searching for the settings.json file in Windows File Explorer, you can directly access and modify it using this tool.

 Follow these instructions to customize your Windows Terminal background image using the Run Command tool:

1. Right-click on Start and select**Run** from the menu list. If you prefer using shortcut keys, press**Win + R** on your keyboard to open the tool directly.
2. In the text box, type the following command and press Enter:  
`%localappdata%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState`
3. This will open the Local State folder containing the settings.json file. Right-click on**Settings** and select**Open with** \>**Notepad** .  
![Change Windows Terminal Background Image From Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-windows-terminal-background-image-from-windows-file-explorer.jpg)
4. Scroll down to the**backgroundImage** section and replace the image path with your own.
5. Then press**Ctrl + S** on your keyboard to save the changes.
6. Close Notepad, then open Windows Terminal to see your new background image.

 You’re done! Now you know how to customize your Windows Terminal background image using the Run Command tool. You can further explore the settings.json file or use other tools to [customize and personalize your Windows Terminal](https://www.makeuseof.com/windows-terminal-customization/) .

## Set a New Background Image for Windows Terminal

 It's easy to customize your Windows Terminal by adding or changing the background image. All you need to do is access the settings.json file, where you can also adjust your image's transparency. Just remember to restart Windows Terminal after making changes. Read this guide to learn how to customize your Windows Terminal background image easily.

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
<li><a href="https://screen-capture.techidaily.com/new-comprerans-selection-premier-screen-recording-tools/"><u>[New] Compreran's Selection  Premier Screen Recording Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-compelling-desktop-imagery-on-windows-11/"><u>Crafting Compelling Desktop Imagery on Windows 11</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-top-7-budget-pc-screenshot-and-recording-apps/"><u>[New] Top 7 Budget PC Screenshot & Recording Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-running-handbrake-on-widows/"><u>Mastering the Art of Running HandBrake on Widows</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-audio-mastery-configuring-custom-volume-hotkeys/"><u>Win11 Audio Mastery: Configuring Custom Volume Hotkeys</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-filmora-on-a-budget-how-to-get-it-for-free-seriously/"><u>In 2024, Filmora on a Budget How to Get It for Free (Seriously!)</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-troubleshooting-for-winscombsvc-error/"><u>Essential Troubleshooting for WinScombSvc Error</u></a></li>
<li><a href="https://windows11.techidaily.com/outperforming-understanding-why-pcs-triumph-over-macs-9/"><u>Outperforming: Understanding Why PCs Triumph over Macs (#9)</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-windows-ram-usage-for-device-connectivity-services/"><u>Optimizing Windows RAM Usage for Device Connectivity Services</u></a></li>
<li><a href="https://extra-information.techidaily.com/holistic-locomotion-scrutiny-report/"><u>Holistic Locomotion Scrutiny Report</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-dominating-viewership-tips-for-your-video-to-be-a-staff-choice/"><u>[Updated] In 2024, Dominating Viewership  Tips for Your Video to Be a Staff Choice</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-pcs-duration-before-lockdown/"><u>Adjusting PC's Duration Before Lockdown</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-xiaomi-redmi-note-12-pro-5g-phone-without-any-data-loss-by-drfone-android/"><u>How to Unlock Xiaomi Redmi Note 12 Pro 5G Phone without Any Data Loss</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-guide-to-hosting-channels-with-real-time-video-streaming-for-2024/"><u>[New] Guide to Hosting Channels with Real-Time Video Streaming for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-obs-record-failure-a-comprehensive-guide-for-windows-users/"><u>Addressing OBS Record Failure: A Comprehensive Guide for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerate-search-results-in-windows-11-with-these-11-fixes/"><u>Accelerate Search Results in Windows 11 with These 11 Fixes</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/prime-video-game-editors-simplified-top-picks-for-newbies/"><u>Prime Video Game Editors Simplified  Top Picks for Newbies</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-dynamic-distortions-for-compelling-image-narratives/"><u>2024 Approved  Dynamic Distortions for Compelling Image Narratives</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-non-functional-shortcuts-with-windows-snips/"><u>Avoiding Non-Functional Shortcuts with Windows Snips</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-inaccessible-game-on-windows-steam/"><u>Navigating Through Inaccessible Game on Windows Steam</u></a></li>
<li><a href="https://windows11.techidaily.com/linux-vs-windows-a-comprehensive-gamers-guide/"><u>Linux Vs. Windows: A Comprehensive Gamer's Guide</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-android-users-the-top-6-video-downloaders-for-easy-access/"><u>[New] 2024 Approved  Android Users  The Top 6 Video Downloaders for Easy Access</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/how-to-enrich-social-media-content-with-auto-generated-speech/"><u>How to Enrich Social Media Content with Auto-Generated Speech</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-your-pre-win11-system-efficiently/"><u>Optimize Your Pre-Win11 System Efficiently</u></a></li>
<li><a href="https://windows11.techidaily.com/3-ways-to-find-a-group-policy-on-windows/"><u>3 Ways to Find a Group Policy on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-silent-mode-glitches-on-windows-word-reading-feature/"><u>Fix Silent Mode Glitches on Windows' Word Reading Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-techniques-for-initiatingexit-focus-in-the-windows-terminal/"><u>Essential Techniques for Initiating/Exit Focus in the Windows Terminal</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-zany-zoomers-unleashing-the-hottest-tiktok-games/"><u>[Updated] Zany Zoomers  Unleashing the Hottest TikTok Games</u></a></li>
<li><a href="https://windows11.techidaily.com/checking-for-safe-network-connections-on-windows/"><u>Checking for Safe Network Connections on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-incorrect-parameters-leading-to-loadlibrary-failure/"><u>Fixing Incorrect Parameters Leading to LoadLibrary Failure</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-spotting-hdd-vs-ssd-in-windows-operations/"><u>Essential Guide: Spotting HDD vs SSD in Windows Operations</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-graphics-troubleshoot-and-restart-for-clear-images/"><u>Windows 11 Graphics: Troubleshoot & Restart for Clear Images</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-the-missing-file-preview-glitch-in-outlook-360/"><u>Mending the Missing File Preview Glitch in Outlook 360</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-zip-files-seamless-compressed-archives-on-windows-pcs/"><u>Conquer ZIP Files: Seamless Compressed Archives on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-chains-of-stuck-files-win11-download-guide-2/"><u>Breaking Chains of Stuck Files: WIN11 Download Guide (2)</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-crafting-a-pro-sports-youtube-feed-on-macos/"><u>[Updated] 2024 Approved  Crafting a Pro Sports YouTube Feed on MacOS</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-change-the-task-manager-start-page-in-windows-11/"><u>How to Change the Task Manager Start Page in Windows 11</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-step-up-your-video-game-expert-endorsed-cost-free-intro-creators/"><u>[New] Step Up Your Video Game  Expert-Endorsed, Cost-Free Intro Creators</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-from-needle-to-narrative-tales-of-textiles-on-tiktok/"><u>[New] From Needle to Narrative  Tales of Textiles on TikTok</u></a></li>
<li><a href="https://extra-support.techidaily.com/quick-and-easy-the-top-ten-for-youtube-mpeg-transformation-for-2024/"><u>Quick and Easy  The Top Ten for YouTube MPEG Transformation for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-master-your-presence-the-complete-guide-to-altering-status-and-avatars/"><u>[New] 2024 Approved  Master Your Presence  The Complete Guide to Altering Status & Avatars</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-art-of-3d-painting-with-these-tips/"><u>Master the Art of 3D Painting with These Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/how-win11-outshines-macos-on-key-fronts/"><u>How Win11 Outshines MacOS on Key Fronts</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-knowledge-about-winservicesexe/"><u>Essential Knowledge About WinServices.exe</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-blue-screen-5-tactics-for-win11-hybrid-issue-fixes/"><u>Conquer Blue Screen: 5 Tactics for Win11 Hybrid Issue Fixes</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-11-free-apps-to-check-imei-on-motorola-moto-g73-5g-phones-by-drfone-android/"><u>In 2024, Top 11 Free Apps to Check IMEI on Motorola Moto G73 5G Phones</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-from-dull-to-dynamic-top-11-techniques-for-enhanced-hues/"><u>In 2024, From Dull to Dynamic  Top 11 Techniques for Enhanced Hues</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-impact-of-copilot-key-on-your-windows-11-pc-performance/"><u>Deciphering the Impact of Copilot Key on Your Windows 11 PC Performance</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-infinix-zero-5g-2023-turbo-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos from Infinix Zero 5G 2023 Turbo to New Android? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/lost-and-found-how-to-find-the-disappeared-enhancements-on-windows-11/"><u>Lost and Found: How to Find the Disappeared Enhancements on Windows 11</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-learn-how-to-make-modern-tiktok-velocity-dance-videos-in-filmora-just-like-the-ones-you-see-on-tiktok-and-instagram-reels/"><u>Updated Learn How to Make Modern TikTok Velocity Dance Videos in Filmora Just Like the Ones You See on TikTok and Instagram Reels</u></a></li>
<li><a href="https://windows11.techidaily.com/discovering-the-power-of-wintoys-a-step-by-step-analysis-for-windows-users/"><u>Discovering the Power of WinToys: A Step-by-Step Analysis for Windows Users</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/acid-pro-a-deep-dive-and-competitive-matchups-for-2024/"><u>ACID Pro  A Deep Dive & Competitive Matchups for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/mastering-the-ken-burns-technique-a-step-by-step-guide-for-2024/"><u>Mastering the Ken Burns Technique A Step-by-Step Guide for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-apps-from-xiaomi-redmi-a2plus-to-another-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Apps from Xiaomi Redmi A2+ to Another | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/5-reasons-to-steer-clear-from-inexpensive-windows-keys/"><u>5 Reasons to Steer Clear From Inexpensive Windows Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/corrective-measures-for-discord-search-dysfunction/"><u>Corrective Measures for Discord Search Dysfunction</u></a></li>
<li><a href="https://windows11.techidaily.com/image-integration-insights-securely-stashing-files-on-windows-11/"><u>Image Integration Insights: Securely Stashing Files on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-windows-media-player-in-a-swift-manner/"><u>Activating Windows Media Player in a Swift Manner</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-expert-advice-on-lighting-your-youtube-content-perfectly/"><u>[New] In 2024, Expert Advice on Lighting Your YouTube Content Perfectly</u></a></li>
</ul></div>
