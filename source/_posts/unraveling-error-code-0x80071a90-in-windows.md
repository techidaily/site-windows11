---
title: Unraveling Error Code 0X80071A90 in Windows
date: 2024-07-11T21:30:20.347Z
updated: 2024-07-12T21:30:20.347Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unraveling Error Code 0X80071A90 in Windows
excerpt: This Article Describes Unraveling Error Code 0X80071A90 in Windows
keywords: Fix Windows Error X71A90,Resolve WinError X71A90,Overcome Windows 0X71A90 Fault,Eradicate Windows X71A90 Issue,Solve WinError Code 0X71A90,Unlock WinError 0X80071A90,Correct Error 0X80071A90 in Windows
thumbnail: https://thmb.techidaily.com/ea600fcdcc2d5739582790f8ecc24848128b14c3ba69f4885da8723ba49d2002.jpg
---

## Unraveling Error Code 0X80071A90 in Windows

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
<li><a href="https://windows11.techidaily.com/dissecting-the-8-anomalies-in-windows-11s-ui/"><u>Dissecting the 8 Anomalies in Windows 11'S UI</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-vigilance-understanding-and-monitoring-device-uptime/"><u>Windows 11 Vigilance: Understanding and Monitoring Device Uptime</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-ensure-your-insta-pics-are-real-a-comprehensible-guide/"><u>In 2024, Ensure Your Insta Pics Are Real - A Comprehensible Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-limitations-for-power-use-in-winos/"><u>Bypassing Limitations for Power Use in WinOS</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/beginners-journey-into-hosting-successful-zoom-sessions/"><u>Beginner's Journey Into Hosting Successful Zoom Sessions</u></a></li>
<li><a href="https://some-skills.techidaily.com/trending-memes-galore-unique-themes-for-any-event-for-2024/"><u>Trending Memes Galore  Unique Themes for Any Event for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-obs-guide-seamless-youtube-and-twitch-streaming/"><u>[New] OBS Guide  Seamless YouTube and Twitch Streaming</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-7-ways-to-unlock-a-locked-oppo-find-x7-ultra-phone-by-drfone-android/"><u>In 2024, 7 Ways to Unlock a Locked Oppo Find X7 Ultra Phone</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-the-perfect-keys-list-for-win11s-narrator-control/"><u>Crafting the Perfect Keys List for Win11's Narrator Control</u></a></li>
<li><a href="https://windows11.techidaily.com/audio-visual-verification-a-windows-users-pre-meet-checklist/"><u>Audio Visual Verification: A Windows User’s Pre-Meet Checklist</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-2024-approved-best-avi-video-trimmers-cut-and-edit-avi-files-on-any-device/"><u>Updated 2024 Approved Best AVI Video Trimmers Cut and Edit AVI Files on Any Device</u></a></li>
<li><a href="https://windows11.techidaily.com/the-pathway-for-effortless-changes-of-file-extensions/"><u>The Pathway for Effortless Changes of File Extensions</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-eliminate-clutter-on-tweet-feed-with-top-20-apps-for-2024/"><u>[New] Eliminate Clutter on Tweet Feed with Top 20 Apps for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/window-wonderland-crafting-distinctive-displays-in-win-1011/"><u>Window Wonderland: Crafting Distinctive Displays in Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-update-codes-and-version-names-in-windows/"><u>Understanding Update Codes and Version Names in WINDOWS</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-prevalent-anydesk-errors-in-windows/"><u>Decoding Prevalent AnyDesk Errors in Windows</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/fb-quick-views-snap-and-share-for-2024/"><u>FB Quick Views  Snap & Share for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/voice-activated-mastery-in-windows-11s-accessibility-features/"><u>Voice-Activated Mastery in Windows 11'S Accessibility Features</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-elevate-mobile-streaming-with-obs-studio-android-edition/"><u>[New] In 2024, Elevate Mobile Streaming with OBS Studio Android Edition</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-oppo-a59-5g-without-the-home-button-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Oppo A59 5G Without the Home Button | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-xiaomi-redmi-note-13-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Can I use iTools gpx file to catch the rare Pokemon On Xiaomi Redmi Note 13 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-user-accounts-to-local-groups-policy-in-windows-11-and-11/"><u>Tailoring User Accounts to Local Groups Policy in Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-solve-no-device-camera-error-in-win11/"><u>Steps to Solve No Device: Camera Error in Win11</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-maximizing-impact-instagram-and-twitter-video-collaboration-for-2024/"><u>[New] Maximizing Impact  Instagram & Twitter Video Collaboration for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-fixing-the-application-was-unable-error/"><u>Understanding and Fixing The Application Was Unable Error</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-preserving-periscope-content-tips-from-the-pros/"><u>2024 Approved  Preserving Periscope Content  Tips From the Pros</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-unresponsive-spotify-on-windows-11/"><u>Troubleshooting Unresponsive Spotify on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/discovering-devhome-the-essential-guide-to-win11/"><u>Discovering DevHome: The Essential Guide to Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resurrect-a-dormant-windows-tab-key/"><u>Steps to Resurrect a Dormant Windows Tab Key</u></a></li>
<li><a href="https://windows11.techidaily.com/chronicle-of-windows-seven-enduring-traits-in-the-new-era-of-11/"><u>Chronicle of Windows: Seven Enduring Traits in the New Era of 11</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-windows-aggregatorhostexe-functions-risks-and-safety-concerns/"><u>Decoding Windows' AggregatorHost.exe: Functions, Risks, and Safety Concerns</u></a></li>
<li><a href="https://windows11.techidaily.com/the-special-features-that-define-artificited-computers/"><u>The Special Features that Define Artificited Computers</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-tweaking-mouse-speeds-in-win-1011/"><u>The Ultimate Guide to Tweaking Mouse Speeds in Win 10/11</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-streamlining-windows-photos-with-customized-audio-and-visual-settings/"><u>[Updated] Streamlining Windows Photos with Customized Audio & Visual Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/1719217852527-solve-low-brightness-woes-in-windows-11-easily/"><u>Solve Low-Brightness Woes in Windows 11 Easily!</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-fake-snapchat-location-without-jailbreak-on-itel-a60-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location without Jailbreak On Itel A60 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/swiftly-overcoming-disruptions-after-a-windows-update/"><u>Swiftly Overcoming Disruptions After a Windows Update</u></a></li>
<li><a href="https://windows11.techidaily.com/top-screen-notebook-techniques-for-win-1011/"><u>Top-Screen Notebook Techniques for Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/a-step-by-step-for-erasing-sign-in-email-in-win/"><u>A Step-By-Step for Erasing Sign-In Email in Win</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/step-by-step-photo-addition-to-instagram-for-2024/"><u>Step-by-Step Photo Addition to Instagram for 2024</u></a></li>
<li><a href="https://techidaily.com/hard-resetting-an-poco-x6-device-made-easy-drfone-by-drfone-reset-android-reset-android/"><u>Hard Resetting an Poco X6 Device Made Easy | Dr.fone</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-get-noticed-20-stunning-adobe-premiere-intro-templates-free-to-download/"><u>New Get Noticed 20 Stunning Adobe Premiere Intro Templates Free to Download</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/crafting-charts-with-a-click-youtube-short-tunes-made-easy-for-2024/"><u>Crafting Charts with a Click  YouTube Short Tunes Made Easy for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-windows-index-settings/"><u>Configuring Windows Index Settings</u></a></li>
<li><a href="https://extra-tips.techidaily.com/decoding-the-secrets-of-successful-haul-video-edits/"><u>Decoding the Secrets of Successful Haul Video Edits</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-in-2024-step-by-step-soundtracking-tips-for-premiere-pro-editors/"><u>[New] In 2024, Step-by-Step Soundtracking Tips for Premiere Pro Editors</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-understanding-your-needs-for-a-precise-vimeo-subscription-level/"><u>[New] In 2024, Understanding Your Needs for a Precise Vimeo Subscription Level</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-capture-your-screen-on-chromebook-methods-4-you-in-2024/"><u>[New] Capture Your Screen on Chromebook  Methods 4 You, In 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-for-curtailing-windows-eyes-on-you/"><u>Tactics for Curtailing Windows' Eyes on You</u></a></li>
<li><a href="https://windows11.techidaily.com/bringing-print-functionality-to-microsofts-secure-edge/"><u>Bringing Print Functionality to Microsoft's Secure Edge</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-your-experience-altering-device-settings-in-windows-11/"><u>Customize Your Experience: Altering Device Settings in Windows 11</u></a></li>
</ul></div>
