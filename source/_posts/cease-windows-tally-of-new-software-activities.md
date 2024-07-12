---
title: Cease Windows' Tally of New Software Activities
date: 2024-07-11T21:16:54.874Z
updated: 2024-07-12T21:16:54.874Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Cease Windows' Tally of New Software Activities
excerpt: This Article Describes Cease Windows' Tally of New Software Activities
keywords: Stop Windows Update Tracking,End Windows Activation Logging,Prevent Windows Install Monitor,Halt Windows Deactivation Counts,Disable Windows Software Alerts,Cease Windows License Tracking,Block Windows Activation Tracker
thumbnail: https://thmb.techidaily.com/983f31d4ff46a88bf34dd06f49261024f8d7c362e39532f6eee2990ca747e49a.jpg
---

## Cease Windows' Tally of New Software Activities

 Windows records and monitors how often you use particular applications. While this may enhance productivity, it does also raise privacy concerns.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.

## 1\. How to Disable App Launch Tracking Through Windows Settings

 To disable app launch tracking, open the Start menu and type **Settings** in the search bar. Select the **Settings** option in the search results. In the left-side menu, click the **Privacy & security** tab. Then click **General** under the Windows permissions section.

 On the next page, locate **Let Windows improve Start and search results by tracking app launches** and toggle it off.

![Disable App Launch Tracking through Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-through-windows-settings.jpg)

 After making the changes, Windows will stop tracking and recording your app launches.

 If you ever need to re-enable the feature, repeat the same steps and toggle the switch back on. This will enable Windows to start tracking and recording your app launches.

## 2\. How to Disable App Launch Tracking Using the Group Policy Editor

 You can also disable app launch tracking using the Group Policy Editor. But this method is only available in the Pro and Enterprise versions.

 If you don't have these Windows versions, [turn on the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) and follow these instructions.

1. Press **Win + R** on your keyboard to open the Run dialog box.
2. Type **gpedit.msc** in the text box and click **OK**.
3. In the Group Policy Editor window, navigate to the following path:  
`User Configuration > Administrative Templates > Windows Components > Edge UI​`
4. Go to the right side of the window and double-click on **Turn off tracking of app usage**.  
![Disable App Launch Tracking using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-using-group-policy-editor.jpg)
5. On the next page, check the **Enabled** box.
6. Click **Apply** \> **OK** to save your changes.

 This way, you can disable app launch tracking using the group policy editor.

 To enable the feature again, follow the same steps and navigate to _User Configuration > Administrative Templates > Windows Components > Edge UI_. Then double-click on **Turn off tracking of app usage** and check the **Not Configured** or **Disabled** option.

## 3\. How to Disable App Launch Tracking Through the Registry Editor

 Registry Editor is another method to disable app launch tracking. The process is tricky as you need to manually modify the registry keys and one wrong move can cause serious problems. So, we suggest you [create a backup of the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it.

 To disable app launch tracking through Registry Editor, do the following:

1. Right-click on Start and select **Run** from the menu list.
2. Type **regedit** in the text field and click **OK**. This will [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. When the UAC window appears, click **Yes** to grant privileges.
4. In the left pane, navigate to the following path:  
`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. If you don't find the Advanced folder, right-click on **Explorer** and select **New** \> **Key**.
6. Name it **Advanced** and press the Enter key.
7. Now, right-click on the **Advanced** folder and choose **New** \> **DWORD (32-bit) Value**.
8. Name it **Start\_TrackProgs** and hit Enter.  
![Disable App Launch Tracking through the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-through-the-registry-editor.jpg)
9. Double-click on the **Start\_TrackProgs** DWORD and set its value to **0**.

 Once you're done, close the Registry Editor and restart your computer. Now, Windows won't track or record app launches.

 If you ever want to turn back on app launch tracking, double-click on the **Start\_TrackProgs** DWORD in Registry Editor and set its value to **1**. After that, restart your system for the changes to take effect.

## Windows Won’t Track or Monitor the Apps You Use

 If you don't want to mess with the Registry Editor or Group Policy Editor, use the Settings option to disable app launch tracking. Choose the method you prefer and enjoy a tracking-free experience.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/mending-the-gap-enabling-smooth-steam-connection/"><u>Mending the Gap: Enabling Smooth Steam Connection</u></a></li>
<li><a href="https://windows11.techidaily.com/creative-walls-for-your-pc-windows-1011-guide/"><u>Creative Walls for Your PC: Windows 10/11 Guide</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-from-concept-to-reality-the-vr-story/"><u>2024 Approved  From Concept to Reality  The VR Story</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-navigating-the-maze-of-tiktoks-bulk-video-transfer/"><u>[Updated] 2024 Approved  Navigating the Maze of TikTok's Bulk Video Transfer</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-11-error-0x80070570-fixing-damaged-files/"><u>Overcoming Windows 11 Error 0X80070570: Fixing Damaged Files</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-pros-choices-top-4-fullscreen-recording-software-for-pcmac/"><u>[Updated] 2024 Approved  Pros' Choices  Top 4 Fullscreen Recording Software for PC/Mac</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-a-deep-dive-comparative-analysis-of-audio-editors-magix-edition/"><u>2024 Approved  A Deep Dive  Comparative Analysis of Audio Editors - Magix Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-to-address-missing-windows-1011-search-data/"><u>Guidelines to Address Missing Windows 10/11 Search Data</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-snipeater-glitches-fix-strategies-here/"><u>Navigating SnipEater Glitches: Fix Strategies Here</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-ultimate-race-realism-5-favorites/"><u>In 2024, Ultimate Race Realism  5 Favorites</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-email-management-gmail-in-outlook-windows-edition/"><u>Effortless Email Management: Gmail in Outlook, Windows Edition</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-analyzing-the-post-upload-process-in-youtubes-ecosystem/"><u>[New] 2024 Approved  Analyzing the Post-Upload Process in YouTube's Ecosystem</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-what-does-jailbreaking-iphone-11-pro-i-do-get-answers-here-by-drfone-ios/"><u>In 2024, What Does Jailbreaking iPhone 11 Pro i Do? Get Answers here</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-ride-on-windows-discover-top-5-budget-enhancers/"><u>Elevate Your Ride on Windows: Discover Top 5 Budget Enhancers</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11-for-spatial-aural-enhancement/"><u>Navigating Windows 11 for Spatial Aural Enhancement</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/cutting-edge-tips-elevating-content-with-tags/"><u>Cutting-Edge Tips  Elevating Content with Tags</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-package-control-with-winget-on-win11/"><u>Navigating Package Control with Winget on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-failed-office-activation-on-pcs-and-laptops/"><u>Conquering Failed Office Activation on PCs and Laptops</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-best-free-video-cutting-apps-your-go-to-list/"><u>[Updated] In 2024, Best Free Video Cutting Apps  Your Go-To List</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-how-to-erase-past-safety-checks-on-windows/"><u>Expert Tips: How to Erase Past Safety Checks on Windows</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-instagram-to-mp3-conversion-process-walkthrough/"><u>2024 Approved  Instagram to MP3 Conversion Process Walkthrough</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-final-cut-pro-wizardry-incorporating-lifelike-audio-waveforms-and-animation-into-your-video-edits-for-2024/"><u>New Final Cut Pro Wizardry Incorporating Lifelike Audio Waveforms and Animation Into Your Video Edits for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/need-windows-help-find-support-tips-and-solutions/"><u>Need Windows Help? Find Support Tips & Solutions</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-fine-tuning-soundtracks-with-garageband-expertise/"><u>[New] Fine-Tuning Soundtracks with GarageBand Expertise</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/izing-channel-potential-across-diverse-digital-venues-for-2024/"><u>Maximizing Channel Potential Across Diverse Digital Venues for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-crafting-professionally-recorded-audio-via-audacity/"><u>[Updated] Crafting Professionally Recorded Audio via Audacity</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-batched-taskbar-visual-elements/"><u>Correcting Batched Taskbar Visual Elements</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-change-your-username-in-windows-11/"><u>How to Change Your Username in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/decorating-windows-11-with-a-christmas-twist/"><u>Decorating Windows 11 with a Christmas Twist</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-art-of-fixing-disk-read-errors/"><u>Master the Art of Fixing Disk Read Errors</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-apple-iphone-se-2020-to-windows-10-drfone-by-drfone-ios/"><u>How to Mirror Apple iPhone SE (2020) to Windows 10? | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-analyzing-huawei-p10s-impact-on-mobile-photography-trends/"><u>[Updated] Analyzing Huawei P10's Impact on Mobile Photography Trends</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-journeying-through-yesteryears-facebook-posts-on-mobilelaptop/"><u>In 2024, Journeying Through Yesteryear's Facebook Posts on Mobile/Laptop</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-edge-windows-photo-management-software/"><u>Cutting-Edge Windows Photo Management Software</u></a></li>
<li><a href="https://windows11.techidaily.com/paramount-procedures-for-wiping-your-windows-installation/"><u>Paramount Procedures for Wiping Your Windows Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-enable-the-home-section-in-the-settings-app-in-windows-11/"><u>How to Enable the Home Section in the Settings App in Windows 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-share-on-apple-iphone-6-drfone-by-drfone-ios/"><u>In 2024, How to Screen Share on Apple iPhone 6? | Dr.fone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-techniques-for-gh-video-logging-for-2024/"><u>[New] Techniques for GH Video Logging for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/device-dialogue-diplomacy-android-plus-pc-sync-guide/"><u>Device Dialogue Diplomacy: Android + PC Sync Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/harmonious-hardware-connections-android-pc-junctions/"><u>Harmonious Hardware Connections: Android-PC Junctions</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-nvidia-control-panel-not-opening-in-windows-11/"><u>How to Fix the NVIDIA Control Panel Not Opening in Windows 11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-hololens-analysis-a-3d-interface-revolution-by-microsoft/"><u>[New] HoloLens Analysis  A 3D Interface Revolution by Microsoft</u></a></li>
<li><a href="https://windows11.techidaily.com/reinitializing-windows-spooler/"><u>Reinitializing Windows' Spooler</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-output-amplitude-for-external-windows-11-audio/"><u>Elevating Output Amplitude for External Windows 11 Audio</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-innovation-best-windows-devices-for-24/"><u>Exploring Innovation - Best Windows Devices for '24</u></a></li>
<li><a href="https://windows11.techidaily.com/erase-your-black-screen-and-clear-cursor-issues-in-win11/"><u>Erase Your Black Screen & Clear Cursor Issues in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-batch-convert-heic-images-to-jpeg-format-in-windows-10-and-11/"><u>How to Batch Convert HEIC Images to JPEG Format in Windows 10 & 11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/elevating-video-content-10-proven-methods-for-youtube-conversion/"><u>Elevating Video Content  10 Proven Methods for YouTube Conversion</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-microsoft-store-app-on-win11-pcs/"><u>Enabling Microsoft Store App on Win11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/no-more-erratic-arrows-fixes-for-the-frustrated/"><u>No More Erratic Arrows: Fixes for the Frustrated</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-catchemall-celebrate-national-pokemon-day-with-virtual-location-on-vivo-y36-drfone-by-drfone-virtual-android/"><u>In 2024, CatchEmAll Celebrate National Pokémon Day with Virtual Location On Vivo Y36 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/prioritize-and-proliferate-elevating-notifications-in-windows-11/"><u>Prioritize and Proliferate: Elevating Notifications in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-optimal-window-size-on-windows-11/"><u>Configuring Optimal Window Size on Windows 11</u></a></li>
</ul></div>
