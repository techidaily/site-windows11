---
title: Essential Guide to Fixing 0X80071A90 Windows Error
date: 2024-07-11T21:31:43.315Z
updated: 2024-07-12T21:31:43.315Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Essential Guide to Fixing 0X80071A90 Windows Error
excerpt: This Article Describes Essential Guide to Fixing 0X80071A90 Windows Error
keywords: Windows 0X80071A90 Fix,WinError Guide,0X80071A90 Resolution,XAS071A90 Troubleshooting,ErrorCode 0X80071A90 Solutions,Windows 0X80071A90 Fix Guide,Erroneous Code 0X80071A90 Correction
thumbnail: https://thmb.techidaily.com/fa206782af9b714e31a62f7ae5d0a20ed9b7932652ed0826ec0104cd05df9774.jpg
---

## Essential Guide to Fixing 0X80071A90 Windows Error

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
<li><a href="https://windows11.techidaily.com/5-ways-to-fix-the-windows-family-safety-feature-not-working/"><u>5 Ways to Fix the Windows Family Safety Feature Not Working</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-distracting-notifications-messages-on-windows-11/"><u>Avoid Distracting Notifications, Messages on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-troubled-windows-registry-with-effective-solutions/"><u>Tackling Troubled Windows Registry with Effective Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/turbocharge-pc-gaming-with-high-speed-yuzu/"><u>Turbocharge PC Gaming with High-Speed Yuzu</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-net-requirement-issue-in-windows-apps/"><u>Tackling the .NET Requirement Issue in Windows Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-webcam-dark-screen-issue/"><u>Resolving Windows Webcam Dark Screen Issue</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-how-to-search-comments-on-youtube-quickly/"><u>[New] How to Search Comments on YouTube Quickly?</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-windows-update-issues-0xca00a009/"><u>Streamlining Windows Update Issues: 0XCA00A009</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unleashing-windows-11s-full-visual-potential-with-automatic-hdr-mode-for-2024/"><u>Unleashing Windows 11'S Full Visual Potential with Automatic HDR Mode for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/reverse-c-drive-data-hoarding-in-windows-systems/"><u>Reverse C: Drive Data Hoarding in Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-writing-enhancers-for-your-windows-desktop/"><u>Top 5 Writing Enhancers for Your Windows Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-the-nullzero-error-fixes-for-new-users-on-win11/"><u>Stop the Null/Zero Error: Fixes for New Users on Win11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-monetary-returns-for-one-million-youtube-watchers/"><u>In 2024, Monetary Returns for One Million YouTube Watchers</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-original-settings-post-deletion-win-11/"><u>Restoring Original Settings Post Deletion (Win 11)</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-comparative-content-crusade-analyzing-your-videos-against-others/"><u>[New] 2024 Approved  Comparative Content Crusade  Analyzing Your Videos Against Others'</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-to-mute-game-proposals-in-windows-11/"><u>Tips to Mute Game Proposals in Windows 11</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-2024-approved-ace-the-art-of-editing-say-goodbye-to-overflowing-tiktok-drafts/"><u>[New] 2024 Approved  Ace the Art of Editing  Say Goodbye to Overflowing TikTok Drafts</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-onedrives-abode-in-the-windows-11-ecosystem/"><u>Adjusting OneDrive's Abode in the Windows 11 Ecosystem</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-efficiency-folders-and-files-converge-in-win-11/"><u>Unlocking Efficiency: Folders & Files Converge in Win 11</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-premium-choices-in-video-calling-platforms-for-tech-users/"><u>2024 Approved  Premium Choices in Video Calling Platforms for Tech Users</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-11-unable-to-load-driver-errors/"><u>Addressing Windows 11: Unable to Load Driver Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-quick-access-shortcuts-adjacent-to-power-in-win11/"><u>Unveiling Quick Access: Shortcuts Adjacent to Power in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-enhancing-pen-device-performance-on-windows/"><u>Troubleshooting: Enhancing Pen Device Performance on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-allot-browser-permission-via-firewall-on-pc/"><u>Steps to Allot Browser Permission via Firewall on PC</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-2024-approved-auditory-landmarks-pinpointing-button-induced-sounds-in-software/"><u>New 2024 Approved Auditory Landmarks Pinpointing Button-Induced Sounds in Software</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-capture-striking-shots-using-leading-lines-iphone/"><u>2024 Approved  Capture Striking Shots Using Leading Lines (iPhone)</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-prime-selection-of-top-20-humorous-lockdown-memes-lifting-spirits-on-facebook/"><u>[Updated] In 2024, Prime Selection of Top 20 Humorous Lockdown Memes, Lifting Spirits on Facebook</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-top-rated-apps-for-taking-screenshots-in-windows-8/"><u>[Updated] Top-Rated Apps for Taking Screenshots in Windows 8</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-the-essential-list-of-leading-guitar-soundtrack-editing-tools/"><u>Updated In 2024, The Essential List of Leading Guitar Soundtrack Editing Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-effortlessly-switch-between-windows-terminal-focus-and-normal-states/"><u>Steps to Effortlessly Switch Between Windows Terminal Focus and Normal States</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-anarchy-how-to-heal-fractured-win11-registry-elements/"><u>Avoiding Anarchy: How to Heal Fractured Win11 Registry Elements</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-solutions-to-find-your-realme-c67-4g-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>3 Solutions to Find Your Realme C67 4G Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-for-installing-unverified-windows-drivers/"><u>Tactics for Installing Unverified Windows Drivers</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-fonts-that-make-a-difference-your-20-best-choices/"><u>[New] 2024 Approved  Fonts That Make a Difference  Your 20 Best Choices</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-2024-approved-edit-like-a-pro-a-free-online-video-editing-course-using-jaycut/"><u>Updated 2024 Approved Edit Like a Pro A Free Online Video Editing Course Using Jaycut</u></a></li>
<li><a href="https://fake-location.techidaily.com/ultimate-guide-to-free-pptp-vpn-for-beginners-on-motorola-edgeplus-2023-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Free PPTP VPN For Beginners On Motorola Edge+ (2023) | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-htc-u23-pro-get-deleted-phone-number-back-with-ease-and-safety-by-fonelab-android-recover-contacts/"><u>How to HTC U23 Pro Get Deleted Phone Number Back with Ease and Safety</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-in-2024-check-out-the-article-to-add-subtitles-to-final-cut-pro-via-the-simple-step-by-step-tutorial-also-the-steps-are-similar-for-adding-captions-in-f/"><u>New In 2024, Check Out the Article to Add Subtitles to Final Cut Pro via the Simple Step-by-Step Tutorial! Also, the Steps Are Similar for Adding Captions in FCPX</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-sharefake-location-on-whatsapp-for-asus-rog-phone-8-pro-drfone-by-drfone-virtual-android/"><u>How to Share/Fake Location on WhatsApp for Asus ROG Phone 8 Pro | Dr.fone</u></a></li>
<li><a href="https://fox-info.techidaily.com/mastering-the-art-of-stealthy-sound-extinction-in-audacity-for-2024/"><u>Mastering the Art of Stealthy Sound Extinction in Audacity for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-hidden-language-of-windows-update-identifiers/"><u>The Hidden Language of Windows Update Identifiers</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-10-telegram-spy-tools-on-realme-gt-3-for-parents-drfone-by-drfone-virtual-android/"><u>Top 10 Telegram Spy Tools On Realme GT 3 for Parents | Dr.fone</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-cut-combine-repeat-the-top-free-online-video-editing-tools-for-2024/"><u>Updated Cut, Combine, Repeat The Top Free Online Video Editing Tools for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/securely-accessing-power-user-terminal/"><u>Securely Accessing Power-User Terminal</u></a></li>
<li><a href="https://windows11.techidaily.com/6-ways-to-recover-an-off-screen-window-in-windows-10-and-11/"><u>6 Ways to Recover an Off-Screen Window in Windows 10 and 11</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-memory-integrity-with-win11-tweaks-and-tricks/"><u>Securing Memory Integrity with Win11 Tweaks & Tricks</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-enumeration-of-global-podcast-listings-aggregators/"><u>New Enumeration of Global Podcast Listings Aggregators</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-nine-superior-choices-for-live-streaming-now/"><u>2024 Approved  Nine Superior Choices for Live Streaming Now</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-apple-iphone-xr-to-windows-10-drfone-by-drfone-ios/"><u>How to Mirror Apple iPhone XR to Windows 10? | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/the-essential-list-of-leading-guitar-soundtrack-editing-tools/"><u>The Essential List of Leading Guitar Soundtrack Editing Tools</u></a></li>
</ul></div>
