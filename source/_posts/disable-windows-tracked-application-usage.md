---
title: Disable Windows' Tracked Application Usage
date: 2024-07-11T22:22:08.147Z
updated: 2024-07-12T22:22:08.147Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Disable Windows' Tracked Application Usage
excerpt: This Article Describes Disable Windows' Tracked Application Usage
keywords: Turn Off App Usage Tracker,Stop Windows Tracking Apps,End Windows App Data Logging,Disable Tracking in Windows,Block App Usage Monitoring,Remove Windows Application Watcher,Halt Windows Data Collection
thumbnail: https://thmb.techidaily.com/85034a62a15df819e619fec4e6d0909e5ab4845fbca98b126bdfe343d56fc596.jpg
---

## Disable Windows' Tracked Application Usage

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/concealed-compression-stashing-archives-in-windows-picture-files/"><u>Concealed Compression: Stashing Archives in Windows Picture Files</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-intercept-text-messages-on-honor-100-pro-drfone-by-drfone-virtual-android/"><u>How to Intercept Text Messages on Honor 100 Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-the-purpose-of-pagefilesys-within-os-structure/"><u>Dissecting the Purpose of Pagefile.sys Within OS Structure</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-in-2024-the-ultimate-encyclopedia-of-affordable-audio-recorder-applications/"><u>New In 2024, The Ultimate Encyclopedia of Affordable Audio Recorder Applications</u></a></li>
<li><a href="https://windows11.techidaily.com/diving-into-windows-n-types-benefits-and-downfalls/"><u>Diving Into Windows N Types: Benefits and Downfalls</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-hashtag-wisdom-uncovering-the-best-tags-to-dominate-on-instagram/"><u>In 2024, Hashtag Wisdom  Uncovering the Best Tags to Dominate on Instagram</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-daytime-delights-the-most-inspiring-anime-streaming-channels/"><u>[New] Daytime Delights  The Most Inspiring Anime Streaming Channels</u></a></li>
<li><a href="https://windows11.techidaily.com/decode-subtitle-failures-in-prime-windows-11-collaboration/"><u>Decode Subtitle Failures in Prime, Windows 11 Collaboration</u></a></li>
<li><a href="https://windows11.techidaily.com/discovering-surface-laptop-studio-2-near-flawless-for-makers/"><u>Discovering Surface Laptop Studio 2: Near-Flawless for Makers</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-explore-interaction-tips-for-uploading-videos-from-twitter-snapchat-for-2024/"><u>[Updated] Explore Interaction  Tips for Uploading Videos From Twitter (Snapchat) for 2024</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/mp3-to-minus-one-converter-online-free-your-gateway-to-karaoke-bliss-for-2024/"><u>MP3 To Minus One Converter Online Free Your Gateway To Karaoke Bliss for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-channel-growth-blueprint-selecting-between-studio-and-latest-beta-for-2024/"><u>[New] Channel Growth Blueprint  Selecting Between Studio and Latest Beta for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-and-correcting-irq-glitches/"><u>Deciphering and Correcting IRQ Glitches</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-8-best-daw-apps-for-android-to-boost-your-music-production-2023/"><u>New 8 Best DAW Apps for Android to Boost Your Music Production 2023</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-master-the-airwaves-gratis-applications-to-revolutionize-your-vocal-artistry/"><u>[New] Master the Airwaves  Gratis Applications to Revolutionize Your Vocal Artistry</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-exploring-the-world-of-viral-tiktok-video-responses-for-2024/"><u>[Updated] Exploring the World of Viral TikTok Video Responses for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensible-guide-to-counteracting-winerror-0x80071a90/"><u>Comprehensible Guide to Counteracting WinError 0X80071a90</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-classic-visuals-a-guide-to-shader-magic-in-retroarc/"><u>Crafting Classic Visuals: A Guide to Shader Magic in RetroArc</u></a></li>
<li><a href="https://windows11.techidaily.com/create-a-gratis-local-gptclone-with-gpt4all-for-windows/"><u>Create a Gratis, Local GPTClone with GPT4All for Windows</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-navigating-the-spin-a-step-by-step-instagram-video-reversal-guide/"><u>[New] In 2024, Navigating the Spin  A Step-by-Step Instagram Video Reversal Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/decode-and-dissolve-rectifying-win11-webcam-issue-error-a00f4289/"><u>Decode & Dissolve: Rectifying Win11 Webcam Issue - Error A00F4289</u></a></li>
<li><a href="https://windows11.techidaily.com/data-mastery-for-pcs-uncovering-5-top-notch-fileshare-tools/"><u>Data Mastery for PCs: Uncovering 5 Top-Notch Fileshare Tools</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/2024-approved-the-ultimate-list-top-10-free-webm-video-editors/"><u>2024 Approved The Ultimate List Top 10 Free WebM Video Editors</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-incompatible-drivers-on-windows-11/"><u>Correcting Incompatible Drivers on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-fatal-component-error-in-win10win11-system/"><u>Disabling Fatal Component Error in Win10/Win11 System</u></a></li>
<li><a href="https://windows11.techidaily.com/diagnosing-and-fixing-microsoft-windows-nearby-share-malfunction/"><u>Diagnosing and Fixing Microsoft Windows Nearby Share Malfunction</u></a></li>
<li><a href="https://windows11.techidaily.com/declutter-data-step-by-step-hdd-defrag-for-win11/"><u>Declutter Data: Step-by-Step HDD Defrag for Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-another-program-uses-device-in-windows-sound-system/"><u>Correcting 'Another Program Uses Device' In Windows Sound System</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-pc-screen-to-samsung-galaxy-s23plus-phones-drfone-by-drfone-android/"><u>In 2024, How to Mirror PC Screen to Samsung Galaxy S23+ Phones? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/creating-custom-volume-control-commands-for-windows-11-users/"><u>Creating Custom Volume Control Commands for Windows 11 Users</u></a></li>
<li><a href="https://extra-information.techidaily.com/elite-eight-polishing-pictures-through-premium-grid-makers/"><u>Elite Eight  Polishing Pictures Through Premium Grid Makers</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/financial-forecasting-in-the-world-of-youtube-snippet-creation/"><u>Financial Forecasting in the World of YouTube Snippet Creation</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-exclusive-list-of-top-mobile-editing-software-for-iphoneandroid/"><u>2024 Approved  Exclusive List of Top Mobile Editing Software for iPhone/Android</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-add-personal-touch-to-videos-with-text-labels-using-photos-app-windows-11-for-2024/"><u>[New] Add Personal Touch to Videos with Text Labels Using Photos App (Windows 11) for 2024</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-melodic-minus-one-magic-a-gratuitous-converter-bringing-downbeats-of-mp3-track-to-harmony/"><u>Updated In 2024, Melodic Minus One Magic A Gratuitous Converter Bringing Downbeats of MP3 Track to Harmony.</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensible-guide-to-revoking-custom-search-on-windows-11/"><u>Comprehensible Guide to Revoking Custom Search on Windows 11</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/tailoring-your-content-for-split-screen-audiences-via-facebook-lives-for-2024/"><u>Tailoring Your Content for Split Screen Audiences via Facebook Lives for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-preparation-to-beat-giovani-in-pokemon-go-for-samsung-galaxy-z-fold-5-drfone-by-drfone-virtual-android/"><u>In 2024, Preparation to Beat Giovani in Pokemon Go For Samsung Galaxy Z Fold 5 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/command-line-tip-disable-amdnvidia-gpu-enhancements/"><u>Command Line Tip: Disable AMD/Nvidia GPU Enhancements</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-the-path-fixing-windows-11-writable-errors/"><u>Clearing the Path: Fixing Windows 11' Writable Errors</u></a></li>
<li><a href="https://audio-editing.techidaily.com/techniques-to-silence-audio-streams-from-new-mkv-file-versions/"><u>Techniques to Silence Audio Streams From New MKV File Versions</u></a></li>
<li><a href="https://windows11.techidaily.com/clear-communication-test-your-mic-on-pc/"><u>Clear Communication: Test Your Mic on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-dism-your-ultimate-toolkit-for-fixing-win11/"><u>Decoding DISM: Your Ultimate Toolkit for Fixing Win11</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/crafting-winning-titles-and-tags-for-your-youtube-videos/"><u>Crafting Winning Titles & Tags for Your YouTube Videos</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-digital-deviants-titles-mirroring-gta-v-experience/"><u>[Updated] In 2024, Digital Deviants  Titles Mirroring GTA V Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/compreran-gaming-hurdles-enhance-gamesplay-on-windows/"><u>Compreran Gaming Hurdles: Enhance Gamesplay on Windows</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/in-2024-quicktime-video-acceleration-boost-your-productivity/"><u>In 2024, QuickTime Video Acceleration Boost Your Productivity</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-vivo-x90s-mirror-screen-to-pc-drfone-by-drfone-android/"><u>How Vivo X90S Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/digital-revolution-at-your-fingertips-master-paint-updates/"><u>Digital Revolution at Your Fingertips - Master Paint Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-windows-audio-graph-isolation/"><u>Decoding Windows Audio Graph Isolation</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/instagram-video-dimensions-explained-a-beginners-guide-for-2024/"><u>Instagram Video Dimensions Explained A Beginners Guide for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-crash-reports-for-flawless-hardware-repairs/"><u>Decoding Crash Reports for Flawless Hardware Repairs</u></a></li>
<li><a href="https://windows11.techidaily.com/controlling-clock-display-in-windows-11-taskbar/"><u>Controlling Clock Display in Windows 11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/detailed-steps-to-fully-remove-wsl/"><u>Detailed Steps to Fully Remove WSL</u></a></li>
<li><a href="https://windows11.techidaily.com/directing-biometric-access-control-for-windows-11-users/"><u>Directing Biometric Access Control for Windows 11 Users</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>