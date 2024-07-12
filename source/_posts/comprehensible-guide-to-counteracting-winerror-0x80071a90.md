---
title: Comprehensible Guide to Counteracting WinError 0X80071a90
date: 2024-07-11T22:21:35.745Z
updated: 2024-07-12T22:21:35.745Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Comprehensible Guide to Counteracting WinError 0X80071a90
excerpt: This Article Describes Comprehensible Guide to Counteracting WinError 0X80071a90
keywords: WinError Resolution Guide,Error 0X80071a90 Fix Tips,Overcome Windows Error 7190,Troubleshoot Windows Error X,XboxError 7X190 Correction,Guide to WinError 7X190,XboxError Resolution Steps
thumbnail: https://thmb.techidaily.com/19ce8481b5575ff1faf6716113cc99f8aa092b92d7c87ab230819ca4dc98d6d3.jpg
---

## Comprehensible Guide to Counteracting WinError 0X80071a90

 The Windows Features error 0x80071A90 occurs when the users try to install or enable a features component such as .NET Framework but the process fails. This typically happens when there is an issue within the Windows component store which maintains the system components.

 Below, we take a look at why this error occurs, and the solutions to try to resolve it for good.

## Factors That Might Be Contributing to the 0x80071A90 Error

 While there are several factors that might be contributing to the Windows Features error, here are the most common ones:

* **Antivirus interruption** : If you are using a third-party security program on your computer, there is a chance that it is blocking the installation or enablement of Windows features by detecting them as potentially harmful or unwanted. This is often a false security alarm.
* **Third-party software conflicts** : Sometimes, a third-party program running in the background can interfere with the installation or enablement of Windows features, leading to the error code 0x80071A90.
* **Corrupted system files** : If the system files that are critical for the installation or enablement of Windows features are missing or corrupted, you are likely to run into the error under consideration.
* **Outdated incomplete Windows updates** : Your system might be outdated, which is resulting in compatibility issues and preventing you from installing/enabling certain Windows features.
* **Other hardware or software issues** : In some cases, hardware or software issues like problems with the device drivers or registry settings can also lead to the Windows Features error.

 Regardless of what might be causing the problem in your case, the troubleshooting methods we have listed above should help you fix it in no time. Proceed with the method that fits your situation the best.

## 1\. Disable Your Antivirus

 Antivirus programs are designed to protect your computer from harmful software and viruses but in doing so, they may also prevent some legitimate Windows components and features from installing or updating properly. This typically happens when the antivirus falsely considers the feature to be harmful.

 Some programs can also interfere with the Windows component store or the update process, leading to the problem.

 This is why, we recommend getting started with disabling your antivirus program temporarily. The exact steps of doing so may differ, depending upon the security program you are using. However, typically, you can achieve this by right-clicking on the antivirus icon in the taskbar and choosing**Disable until the computer is restarted** .

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 Once the security program is disabled, try enabling the targeted Windows feature again and check if the problem is now fixed. If the antivirus program happens to be the culprit, you can consider switching to a better alternative.

## 2\. Perform the Action in Safe Mode

 As we mentioned earlier, certain applications and processes running in the background can also interfere with the installation or enablement of Windows features. To prevent any potential third-party software conflicts, you can try performing the action in Safe Mode.

 This mode launches Windows with only the necessary drivers and services, allowing you to finish tasks without interference from third-party software.

 Once you [boot into Safe Mode on Windows](https://www.makeuseof.com/windows-11-boot-safe-mode/) , launch the Windows Features utility and try performing the action that was initially triggering the error. If a background process was leading to it, you should be able to enable the targeted feature without any problems now.

## 3\. Rebuild the WMI Repository

 You might also be facing the problem due to a corrupted WMI Repository.

 This repository is like a database where your system stores information about hardware, software, and other related settings. This information can be used by software programs and administrative scripts to manage the system settings and if the repository has corrupt or missing files, it can lead to issues like Windows Features error.

 To fix issues with the WMI repository, you can rebuild it, which will essentially check the repository for any inconsistencies and reset it to its default state. This can help fix any issues that were preventing the installation or enablement of Windows features.

Follow these steps to proceed:

1. Press the**Win** +**R** keys together to open Run.
2. Type "cmd" in Run and press**Ctrl** +**Shift** +**Enter** keys together. This will launch Command Prompt as an administrator.
3. Click**Yes** in the User Account Control prompt.
4. Once you are inside the Command Prompt, execute the following commands one by one:  
`winmgmt /salvagerepositorywinmgmt /verifyrepositorywinmgmt /resetrepository`
5. Wait for the commands to execute and then exit Command Prompt. You can now check if the issue is resolved.

## 4\. Try Some Generic Windows-Based Fixes for Errors

 If nothing else works, these general WIndows fixes can help you fix the issue:

### Update Windows

![install windows 11 feature update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/install-windows-11-feature-update.jpg)

 If you haven’t installed the latest Windows updates in a while, then you might be facing the problem due to an outdated system. This can be due to a compatibility issue or because your system lacks updates/hotfixes that were released by Microsoft to address specific issues related to Windows features.

 In this case, we recommend taking your time to [install any pending Windows updates](https://www.makeuseof.com/windows-11-install-updates/) available. This will ensure that the drivers and software are compatible with the latest version of Windows.

### Check the System for Corruption Errors

![Run SFC scan in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/sfc-scan-1-1.jpg)

 In order to install or enable Windows features, the system relies on critical files and the Windows component store. If any of these files or the store becomes corrupted, it can impede the system's access to the necessary components for feature installation or enablement, leading to errors like the one at hand.

 To fix such corruption errors, you can use a tool like the System File Checker (SFC) to scan and repair system files or the Deployment Image Servicing and Management (DISM) tool to repair the Windows component store. You can run both these utilities via Command Prompt.

 Follow the correct steps for running SFC and DISM in Windows in our guide on [how to fix file system errors on Windows](https://www.makeuseof.com/fix-file-system-errors-windows/) .

## Enable Your Windows Features Again

 The Windows Features error 0x80071A90 is a frustrating problem that can prevent you from installing/enabling certain Windows features. Fortunately, there are several troubleshooting methods that can help you fix it for good.

 To prevent any such issues from occurring in the future, we highly recommend keeping your Windows up-to-date at all times. Additionally, make sure you use a reputable antivirus and avoid unsafe third-party programs that can interfere with the system processes.


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
<li><a href="https://techidaily.com/different-methods-for-resetting-motorola-moto-g73-5g-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Motorola Moto G73 5G Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-code-of-high-quality-visuals-with-windows-11-hdr/"><u>Deciphering the Code of High-Quality Visuals with Windows 11 HDR</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-the-ultimate-deck-to-deck-users-manual-for-durecorder/"><u>[Updated] In 2024, The Ultimate Deck-to-Deck User's Manual for DuRecorder</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-disparities-microsoft-and-default-windows-login-types/"><u>Dissecting Disparities: Microsoft and Default Windows Login Types</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-best-sound-extractor-how-to-extract-sound-from-video-for-2024/"><u>New Best Sound Extractor How to Extract Sound From Video for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-android-apps-that-youd-actually-want-to-install-on-windows-11/"><u>6 Android Apps That You’d Actually Want to Install on Windows 11</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-strategies-for-discerning-professional-film-making-talents/"><u>In 2024, Strategies for Discerning Professional Film Making Talents</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-perfect-your-pictures-the-ultimate-guide-to-photo-text-editing/"><u>2024 Approved  Perfect Your Pictures  The Ultimate Guide to Photo Text Editing</u></a></li>
<li><a href="https://windows11.techidaily.com/cut-through-the-frustration-swift-solutions-for-ms-teams-error-80080300-in-win11/"><u>Cut Through the Frustration: Swift Solutions for MS Teams Error 80080300 in Win11</u></a></li>
<li><a href="https://extra-information.techidaily.com/relish-free-movie-playback-pc-and-mac-style/"><u>Relish Free Movie Playback, PC & Mac Style</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-resource-locks-in-windows-11-environments/"><u>Disabling Resource Locks in Windows 11 Environments</u></a></li>
<li><a href="https://windows11.techidaily.com/clear-the-hurdle-of-ms-teams-error-80080300-with-actionable-steps/"><u>Clear the Hurdle of MS Teams Error 80080300 with Actionable Steps</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/2024-approved-using-compressor-in-fcpx-tips-tricks-and-best-practices/"><u>2024 Approved Using Compressor in FCPX Tips, Tricks, and Best Practices</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-color-harmony-in-powerdirector-tips-and-tricks-for-a-polished-look/"><u>New 2024 Approved Color Harmony in PowerDirector Tips and Tricks for a Polished Look</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-windows-xc0f1103f-geforce-not-working/"><u>Correcting Windows' XC0F1103F GeForce Not Working</u></a></li>
<li><a href="https://windows11.techidaily.com/curing-windows-security-hiccups-in-win-11-system/"><u>Curing Windows Security Hiccups in Win 11 System</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-the-leaderboard-of-the-best-web-capture-apps/"><u>[Updated] 2024 Approved  The Leaderboard of the Best Web Capture Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/control-windows-11s-emphasis-and-search-highlight/"><u>Control Windows 11'S Emphasis and Search Highlight</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-tiktok-treasures-turned-into-trendy-graphics-with-top-apps/"><u>[Updated] TikTok Treasures Turned Into Trendy Graphics with Top Apps</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-easy-guide-to-itel-a60-frp-bypass-with-best-methods-by-drfone-android/"><u>In 2024, Easy Guide to Itel A60 FRP Bypass With Best Methods</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/7-ways-to-lock-apps-on-apple-iphone-12-pro-and-ipad-securely-by-drfone-ios/"><u>7 Ways to Lock Apps on Apple iPhone 12 Pro and iPad Securely</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-unleashing-potential-mastering-advertising-partnerships-with-famebit/"><u>[Updated] Unleashing Potential  Mastering Advertising Partnerships with FameBit</u></a></li>
<li><a href="https://windows11.techidaily.com/controlling-clock-display-in-windows-11-taskbar/"><u>Controlling Clock Display in Windows 11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/consistent-experience-migrating-powertoys-on-new-pcs/"><u>Consistent Experience: Migrating PowerToys on New PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/command-prompt-mastery-the-fundamental-20-cmd-commands-to-know/"><u>Command Prompt Mastery: The Fundamental 20 CMD Commands to Know</u></a></li>
<li><a href="https://windows11.techidaily.com/defeating-defunct-windows-security-hurdles-in-win-11/"><u>Defeating Defunct Windows Security Hurdles in Win 11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-superior-5-camera-background-modification-utilities/"><u>2024 Approved  Superior 5 Camera Background Modification Utilities</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/mastering-digital-image-cropping-techniques/"><u>Mastering Digital Image Cropping Techniques</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-can-i-use-a-fake-gps-without-mock-location-on-zte-nubia-flip-5g-drfone-by-drfone-virtual-android/"><u>How Can I Use a Fake GPS Without Mock Location On ZTE Nubia Flip 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-html-display-issues-in-windows-11-email-client/"><u>Correcting HTML Display Issues in Windows 11 Email Client</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-to-unfreezing-window-taskbar/"><u>Comprehensive Guide to Unfreezing Window TaskBar</u></a></li>
<li><a href="https://howto.techidaily.com/fix-cant-take-screenshot-due-to-security-policy-on-infinix-smart-7-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Cant Take Screenshot Due to Security Policy on Infinix Smart 7 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/dial-back-the-dread-of-an-unresponsive-esc-button-in-windows/"><u>Dial Back the Dread of an Unresponsive Esc Button in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/clear-path-to-app-removal-tackling-do-not-have-access-errors/"><u>Clear Path to App Removal: Tackling Do Not Have Access Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-sound-misstep-solving-xc00d36b4-on-windows/"><u>Decoding Sound Misstep: Solving XC00D36B4 on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/disarming-error-dism-0x800f082f-on-microsoft-os/"><u>Disarming Error: DISM 0X800F082F on Microsoft OS</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-2024-approved-beginner-tutorial-on-making-unity-2d-animation/"><u>New 2024 Approved Beginner Tutorial on Making Unity 2D Animation</u></a></li>
<li><a href="https://windows11.techidaily.com/disable-auto-updates-in-windows-and-office-instantly/"><u>Disable Auto-Updates in Windows & Office Instantly</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-windows-error-code-31-and-network-adapter-issues/"><u>Demystifying Windows Error Code 31 and Network Adapter Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-camera-access-overlap-in-windows-apps/"><u>Correcting Camera Access Overlap in Windows Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-error-code-zero-on-your-gaming-machine/"><u>Disabling Error Code Zero on Your Gaming Machine</u></a></li>
<li><a href="https://windows11.techidaily.com/darkeningwindowsnotepaddisplaysettings/"><u>DarkeningWindowsNotepadDisplaySettings</u></a></li>
<li><a href="https://windows11.techidaily.com/curbing-the-noise-quiet-explore-tab-behavior/"><u>Curbing the Noise: Quiet Explore Tab Behavior</u></a></li>
<li><a href="https://windows11.techidaily.com/directive-for-disabling-onedrive-symbol-in-windows-11s-filesystem-viewer/"><u>Directive for Disabling OneDrive Symbol in Windows 11’S Filesystem Viewer</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-edge-tips-for-individualized-pattern-security-on-windows/"><u>Cutting-Edge Tips for Individualized Pattern Security on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/decode-your-digital-identity-how-to-find-out-what-computer-you-have/"><u>Decode Your Digital Identity: How to Find Out What Computer You Have</u></a></li>
<li><a href="https://windows11.techidaily.com/dial-down-display-flicker-in-windows-11-devices/"><u>Dial Down Display Flicker in Windows 11 Devices</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-error-code-963-on-google-play-of-oppo-k11x-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Error Code 963 on Google Play Of Oppo K11x | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-discord-setup-woes-on-windows-11/"><u>Correcting Discord Setup Woes on Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-oppo-a79-5g-location-by-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Oppo A79 5G Location by Number | Dr.fone</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/approved-harmonize-your-listens-the-complete-path-to-youtube-playlist-making-webmobile/"><u>2024 Approved  Harmonize Your Listens  The Complete Path to YouTube Playlist Making (Web/Mobile)</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-clock-divergence-chrome-vs-windows/"><u>Correcting Clock Divergence: Chrome vs Windows</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-perfect-snapchat-video-maximizing-mac-capabilities/"><u>In 2024, Perfect Snapchat Video  Maximizing Mac Capabilities</u></a></li>
<li><a href="https://windows11.techidaily.com/compre-written-guide-to-repair-xbox-live-glitches/"><u>Compre Written Guide To Repair Xbox Live Glitches</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-control-over-your-spotify-default-podcast-recommendations/"><u>2024 Approved  Control Over Your Spotify Default Podcast Recommendations</u></a></li>
</ul></div>
