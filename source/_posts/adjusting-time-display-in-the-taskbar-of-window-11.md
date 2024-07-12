---
title: Adjusting Time Display in the Taskbar of Window 11
date: 2024-07-11T22:14:21.773Z
updated: 2024-07-12T22:14:21.773Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting Time Display in the Taskbar of Window 11
excerpt: This Article Describes Adjusting Time Display in the Taskbar of Window 11
keywords: Windows 11 Taskbar Time Adjust,Taskbar Timer Change Win11,Alter Taskbar Clock W11,Display Clock Winbar Settings,Update Windows 11 Clock,Tweak Taskbar Time Format,Modify Winbar Clock Position
thumbnail: https://thmb.techidaily.com/dd7a824e4ab8b6d6473fb0116a606a013dd12f046dfa0556ebd9b84053509fd9.png
---

## Adjusting Time Display in the Taskbar of Window 11

 The system tray clock on the right side of the Windows taskbar shows the date and time. While most users find this information useful, others might consider it a source of distraction.

 As such, if you want to hide the clock and date from the taskbar, then this is the place where you need to be. We'll share three different ways by which you can configure the taskbar to hide or show the clock and date.

## 1\. Hide or Show the Clock and Date from the Taskbar by Using Windows System Settings

 The System Settings is the central hub of a Windows PC. You can use it to update Windows, manage privacy settings,[customize the taskbar](https://www.makeuseof.com/windows-11-customize-taskbar/) , and more.

 It's also one of the places from where you can configure the taskbar to hide or show the clock and date. You can do this by following the below instructions:

 This method only works for Windows 10\. If you are using Windows 11, you can try any other method in this article.

1. Open the**Settings** menu by pressing the**Win + I** hotkeys.
2. Choose the**Personalization** option.
3. Select**Taskbar** from the left panel.
4. Scroll down and click the**Turn system icon on or off** option under the**Notification** area.  
![Turn system icons on or off option in Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-system-icons-on-or-off.png)
5. In the new window that crops up, disable the toggle next to**Clock.**  
![Disable the Clock in System Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-the-clock.png)

 That's it. You've disabled the clock and date from the taskbar.

 To enable them again, head towards the above settings again and enable the toggle.

## 2\. Hide or Show the Clock and Date from the Taskbar by Using the Local Group Policy Editor

 The next utility that will help you hide or show the clock and date from the taskbar is the Local Group Policy Editor. You can use this utility to manage Windows features, sign-in and shutdown processes, and more.

 The Local Group Policy Editor is disabled by default in the Windows Home edition. To enable it, check out our guide on how to [access the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 Nevertheless, here's how to use Local Group Policy Editor to configure the taskbar to hide the clock and date.

1. Open the Run dialog box, type**gpedit.msc,** and press Enter.
2. In the Local Group Policy Editor, select the**Administrative Templates** folder under**User configuration.**
3. Click the**Start Menu and Taskbar** folder.
4. Click the**Setting** option in the right pane.
5. Search for and right-click on the**Remove Clock from the system notification area** policy. Then, choose**Edit** from the context menu.
6. In the policy edit window, choose the**Enabled** option.  
![Disabling Clock and Date using the local group policy editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disabling-clock-and-date.jpg)
7. Click**Apply** \>**OK** to save the changes.

 Next,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) for changes to take effect.

 If you want to add the clock and date again to the taskbar, open the edit window of the Remove Clock from the system notification area policy, choose the Disabled option and save the settings.

## 3\. Hide or Show the Clock and Date from the Taskbar Using the Registry Editor

 The [Registry Editor](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is an extensive database of your Windows operating system configuration settings. You can use it to navigate the registry and edit its keys.

 Here's how to use the Registry Editor to hide the clock and date from the taskbar:

1. In the Run dialog box, type**regedit** and click**OK.** It'll [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Navigate to the following location:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies`
3. Right-click on the**Policies** key in the left panel, choose**New,** and then select**Key.**
4. Name the key**Explorer** and press Enter.  
![Creating new key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/creating-new-key.jpg)
5. In the Explorer key, right-click on the blank space, and choose**New** \>**DWORD (32-bit Value)** .
6. Name the value**HideClock** and press Enter.
7. Right-click on the HideClock value, type**1** in the**Value data** section, and click**OK.**  
![Modifying HideClock Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/modifying-hideclock-value.jpg)

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

## Remove Any Distraction from the Taskbar

 The system tray clock helps you to keep track of the date and time. But if it has become a distraction or you want to keep the taskbar clean, you can use either of the above methods to configure the taskbar to hide the clock and date.


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
<li><a href="https://audio-shaping.techidaily.com/updated-elite-sound-transformer-swiftly-convert-and-enjoy-mp3-audio-files-for-2024/"><u>Updated Elite Sound Transformer Swiftly Convert and Enjoy MP3 Audio Files for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/ace-your-valorant-soundscape-exclusive-access-to-the-top-voice-changer-at-no-cost-for-2024/"><u>Ace Your Valorant Soundscape - Exclusive Access to the Top Voice Changer at No Cost for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-start-driver-verifier-manager/"><u>Steps to Start Driver Verifier Manager</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-unveil-the-secrets-to-excellent-youtube-thumbnails/"><u>In 2024, Unveil the Secrets to Excellent YouTube Thumbnails</u></a></li>
<li><a href="https://location-fake.techidaily.com/10-best-fake-gps-location-spoofers-for-vivo-y100t-drfone-by-drfone-virtual-android/"><u>10 Best Fake GPS Location Spoofers for Vivo Y100t | Dr.fone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-innovative-approaches-for-cross-social-media-broadcasting-fbwhatsapp/"><u>[Updated] Innovative Approaches for Cross-Social Media Broadcasting (FB/WhatsApp)</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-up-oculus-rift-as-a-windows-pc-vr-setup/"><u>Setting up Oculus Rift as a Windows PC VR Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-interactions-between-devices-and-pc-slumber/"><u>Navigating Interactions Between Devices and PC Slumber</u></a></li>
<li><a href="https://fake-location.techidaily.com/ispoofer-is-not-working-on-itel-p40plus-fixed-drfone-by-drfone-virtual-android/"><u>iSpoofer is not working On Itel P40+? Fixed | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/key-steps-unveiled-navigating-disks-in-w10-and-w11-systems/"><u>Key Steps Unveiled: Navigating Disks in W10 & W11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/mindfulness-meets-the-mind-cognitive-and-emotional-responses-to-meditation/"><u>Mindfulness Meets the Mind: Cognitive & Emotional Responses to Meditation</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-leading-titles-the-top-5-android-apps-for-ps2-games-for-2024/"><u>[Updated] Leading Titles  The Top 5 Android Apps for PS2 Games for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-stream-google-meet-to-youtube-step-by-step-guide-for-2024/"><u>[Updated] How To Stream Google Meet to YouTube [Step-by-Step Guide] for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/reducing-heavy-resource-use-by-news-apps-in-windows-os/"><u>Reducing Heavy Resource Use by News Apps in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-license-validity-alert-on-windows-oses/"><u>Resolving License Validity Alert on Windows OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-windows-11-when-it-cant-connect-to-5ghz-wi-fi/"><u>How to Fix Windows 11 When It Can’t Connect to 5GHz Wi-Fi</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-2024-approved-sound-innovators-choice-the-best-free-audio-mixer-platforms-ranked/"><u>Updated 2024 Approved Sound Innovators Choice The Best FREE Audio Mixer Platforms Ranked!</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/mastering-tiktoks-economy-with-these-8-profitable-methods-for-2024/"><u>Mastering TikTok's Economy with These 8 Profitable Methods for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-effortless-access-to-videos-find-your-perfect-chromium-extension-for-fb-vids/"><u>[Updated] Effortless Access to Videos  Find Your Perfect Chromium Extension for FB Vids</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-system-limitations-intel-hd-graphics-compatibility-fixes/"><u>Rectifying System Limitations: Intel HD Graphics Compatibility Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-windows-11-search-with-custom-settings/"><u>Optimizing Windows 11 Search with Custom Settings</u></a></li>
<li><a href="https://android-unlock.techidaily.com/forgotten-the-voicemail-password-of-lava-blaze-2-pro-try-these-fixes-by-drfone-android/"><u>Forgotten The Voicemail Password Of Lava Blaze 2 Pro? Try These Fixes</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-in-2024-whats-music-video-gif-and-how-to-add-music-to-your-gif-files/"><u>Updated In 2024, Whats Music Video GIF & How to Add Music to Your GIF Files</u></a></li>
<li><a href="https://windows11.techidaily.com/resetting-grammarly-settings-in-windows/"><u>Resetting Grammarly Settings in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-default-windows-preferences-post-restart/"><u>Reviving Default Windows Preferences Post-Restart</u></a></li>
<li><a href="https://windows11.techidaily.com/power-up-your-vms-in-windows-using-these-top-6-enhancers/"><u>Power Up Your VMs in Windows Using These Top 6 Enhancers</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/monthly-income-prospects-for-youtube-creators/"><u>Monthly Income Prospects for YouTube Creators</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-not-found-errors-on-pc-windows/"><u>Overcoming 'Not Found' Errors on PC Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-troubleshooting-excel-display-issue-in-notepad/"><u>Remedy: Troubleshooting Excel Display Issue in Notepad</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-pause-life360-location-sharing-for-poco-c51-drfone-by-drfone-virtual-android/"><u>How To Pause Life360 Location Sharing For Poco C51 | Dr.fone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-enhance-engagement-mastering-template-based-video-description-writing/"><u>[New] 2024 Approved  Enhance Engagement  Mastering Template-Based Video Description Writing</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-1110-how-to-stop-double-click-folders-from-closing/"><u>Fixing Windows 11/10: How to Stop Double-Click Folders From Closing</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-completely-removing-wsl-in-win-11/"><u>Step-by-Step: Completely Removing WSL in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-taskbar-transparency-in-maxed-browser-screens/"><u>Solutions for Taskbar Transparency in Maxed Browser Screens</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-unlock-and-reset-restricted-program-status/"><u>How to Unlock and Reset Restricted Program Status</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-high-memory-consumption-in-edges-webview2/"><u>Tackling High Memory Consumption in Edge's WebView2</u></a></li>
<li><a href="https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-nokia-c22-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Troubleshooting Guide How to Fix an Unresponsive Nokia C22 Screen | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-geforce-experience-setting-retrieval-failure-on-windows-1111/"><u>Resolving 'GeForce Experience' Setting Retrieval Failure on Windows 11/11</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-how-to-advertise-on-twitter/"><u>[New] 2024 Approved  How to Advertise on Twitter</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-solutions-to-the-windows-too-many-requests-challenge/"><u>Swift Solutions to the Windows Too Many Requests Challenge</u></a></li>
<li><a href="https://windows11.techidaily.com/synchronize-the-seconds-windows-time-repair-guide/"><u>Synchronize the Seconds: Windows Time Repair Guide</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-olympic-ice-showdown-highlights-of-speed-skating-short-track-for-2024/"><u>[New] Olympic Ice Showdown  Highlights of Speed Skating Short Track for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-handle-exception-breaking-point-issues-on-pc/"><u>How to Handle Exception Breaking Point Issues on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/skyrocket-your-typing-swift-input-strategies-for-win-1011-users/"><u>Skyrocket Your Typing: Swift Input Strategies for WIN 10/11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/integrated-thermal-management-windows-edition/"><u>Integrated Thermal Management: Windows Edition</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/secure-and-simple-grab-your-desired-youtube-cover-at-no-charge-for-2024/"><u>Secure & Simple  Grab Your Desired YouTube Cover at No Charge for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/instructional-guide-for-end-task-enabling-on-windows-11/"><u>Instructional Guide for End Task Enabling on Windows 11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-the-pathway-to-lyrical-masterpieces-via-lyric-video-maker-software/"><u>[Updated] The Pathway to Lyrical Masterpieces via Lyric Video Maker Software</u></a></li>
<li><a href="https://windows11.techidaily.com/rectify-stalling-windows-guard-mechanism-in-win-11/"><u>Rectify Stalling Windows Guard Mechanism in Win 11</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/updated-in-2024-best-tool-to-translate-youtube-video-to-arabic/"><u>Updated In 2024, Best Tool to Translate YouTube Video to Arabic</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-sound-and-microphone-discrepancies-in-valorant/"><u>Resolving Sound and Microphone Discrepancies in Valorant</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-enhance-your-feed-editing-tall-videos-with-fcpx-expertise/"><u>[New] In 2024, Enhance Your Feed  Editing Tall Videos with FCPX Expertise</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-win11-pointer-adjustments-for-access/"><u>Mastering Win11 Pointer Adjustments for Access</u></a></li>
<li><a href="https://windows11.techidaily.com/redirecting-to-file-explorer-from-onedrive-menu/"><u>Redirecting to File Explorer From OneDrive Menu</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/step-by-step-looping-iphones-videos-effortlessly-for-2024/"><u>Step-by-Step  Looping iPhones Videos Effortlessly for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/prioritize-your-data-spotting-the-biggest-disk-space-eaters/"><u>Prioritize Your Data: Spotting the Biggest Disk Space Eaters</u></a></li>
<li><a href="https://windows11.techidaily.com/recover-lost-pin-following-system-breakdown-on-windows-11/"><u>Recover Lost PIN Following System Breakdown on Windows 11</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-exploring-the-sonic-qualities-of-whistle-noises/"><u>In 2024, Exploring the Sonic Qualities of Whistle Noises</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-how-to-transfer-apple-iphone-12-pro-data-to-iphone-12-a-complete-guide-drfone-by-drfone-transfer-from-ios/"><u>In 2024, How to Transfer Apple iPhone 12 Pro Data to iPhone 12 A Complete Guide | Dr.fone</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-top-8-online-free-voice-recorder/"><u>New 2024 Approved Top 8 Online Free Voice Recorder</u></a></li>
<li><a href="https://windows11.techidaily.com/system-saviors-the-10-best-windows-diagnostic-apps/"><u>System Saviors: The 10 Best Windows Diagnostic Apps</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-jumpstarting-your-marketing-the-essentials-of-telegram-advertising/"><u>[New] Jumpstarting Your Marketing  The Essentials of Telegram Advertising</u></a></li>
<li><a href="https://windows11.techidaily.com/tackle-non-selectable-text-in-windows-based-pdf-documents-easily/"><u>Tackle Non-Selectable Text in Windows-Based PDF Documents Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-surface-software-enhancement-techniques-for-maximum-performance/"><u>Mastering Surface Software Enhancement Techniques for Maximum Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-stopping-self-activating-store-app/"><u>Strategies for Stopping Self-Activating Store App</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-visual-virtuosity-mastering-motivation-on-instagram/"><u>[Updated] In 2024, Visual Virtuosity  Mastering Motivation on Instagram</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-2024-approved-ways-to-stop-animation-from-looping-in-unity/"><u>New 2024 Approved Ways to Stop Animation From Looping in Unity</u></a></li>
<li><a href="https://windows11.techidaily.com/ignite-vm-speed-and-stability-top-6-methods-to-enhance-in-windows/"><u>Ignite VM Speed and Stability: Top 6 Methods to Enhance in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-nvidia-experience-connectivity-issues-on-pcs/"><u>Remedying Nvidia Experience Connectivity Issues on PCs</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-easy-guide-unearthing-your-youtube-compliments-and-critiques/"><u>[New] Easy Guide  Unearthing Your YouTube Compliments & Critiques</u></a></li>
</ul></div>
