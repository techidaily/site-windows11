---
title: "Fixing Flaky Windows Apps: A Step-by-Step Guide"
date: 2024-07-11T21:38:09.825Z
updated: 2024-07-12T21:38:09.825Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Fixing Flaky Windows Apps: A Step-by-Step Guide"
excerpt: "This Article Describes Fixing Flaky Windows Apps: A Step-by-Step Guide"
keywords: Fix Flaky Windows,Solve WinApp Issues,Troubleshoot WinErrors,Steps for WinApp Fixes,Resolving WinApp Crashes,Guided WinApp Repair,WinApp Stability Guide
thumbnail: https://thmb.techidaily.com/286866a306a63ee3881a3e82bbbdfd6a5621a0735c9f349a630ef1e39c65837d.jpg
---

## Fixing Flaky Windows Apps: A Step-by-Step Guide

 While the Microsoft Store offers a great selection of apps for Windows systems, you may sometimes encounter installation errors. One such error is “this app will not work on your device” which usually occurs when installing apps from the Store app. This error message appears with a yellow circle around an exclamation mark, even if the app is compatible.

 There could be various reasons for this issue depending on the app, such as a corrupted cache file or system problems. Read this guide to learn more about this error and how to fix it.

## 1\. Restart Your Computer

 Restarting your PC is the simplest solution to many Windows issues, including this one. It refreshes the system and resets the Microsoft Store service. So, if you are experiencing the “This app will not work on your device” error, restart your computer first and see if it works.

 To restart your device, open the Start menu. Then select the Power icon and click **Restart**. You can also use the keyboard shortcut **Ctrl + Alt + Del** to open the same window. After restarting, try installing the app again and see if it works.

## 2\. Clear the Microsoft Store Cache

 If restarting your device does not help, the next step is to clear the Microsoft Store cache. This process removes any temporary files that might cause this issue. Clearing the cache removes unnecessary files and speeds up the browsing experience. Here’s how to clear the Microsoft Store cache.

1. Press **Win + R** on your keyboard to [launch the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **WSReset.exe** in the dialog box and press Enter.  
![Clear Microsoft Store Cache File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/clear-microsoft-store-cache-file.jpg)

 A command prompt appears on the screen confirming that the Windows Store cache is cleared. Once you've completed these steps, check if it solves the error.

## 3\. Check for Microsoft Store Updates

 Another potential reason for this error is the outdated Windows Store version. Microsoft regularly releases updates to fix bugs and improve Store performance. So, make sure that you are using the latest version. To check for Windows Store updates, follow these steps.

1. Go to Start, search for Microsoft Store, and click on it.
2. Click the **Library** icon. This will be on the left side of the Store app.  
![Check for Microsoft Store Updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/check-for-microsoft-store-updates.jpg)
3. Next, click the **Get updates** button to check for available updates.
4. If updates are available, click **Update all** to download and install them.

 After following the steps above, restart your computer and see if it resolves the issue.

## 4\. Run the Windows Store Apps Troubleshooter

 Windows comes with a built-in troubleshooter that diagnoses and resolves various problems. You can use it to fix the “This app will not work on your device” error as well. To run the troubleshooter, follow these steps:

1. Right-click on Start and select **Settings** from the menu list.
2. From the left pane, click **System > Troubleshoot > Other troubleshooters**.  
![Other troubleshooters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/other-troubleshooters.jpg)
3. Scroll down to **Windows Store Apps** and click the **Run** button.  
![Run Windows Store Apps Troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-windows-store-apps-troubleshooter.jpg)
4. Wait for the troubleshooter to detect any problem and fix it if necessary.

 After performing the instructions, try launching the app again and see if it works. If not, you can try the next solution below.

## 5\. Restart the Application Identity Service

 Application Identity service determines and verifies the identity of Windows Store apps. So, if it’s not running correctly, you may run into this error. To restart this service, do the following:

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **services.msc** in the dialog box and press Enter. This will open the Services window.
3. Scroll down to find the **Application Identity** service and double-click on it.  
![Restart the Application Identity Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/restart-the-application-identity-service.jpg)
4. In the Properties window, set the **Startup type** to **Automatic**.
5. Also, click on the **Start** button under Service status.
6. Finally, click **Apply > OK** to save the changes.

 Now, restart your computer and check if the error has been resolved. If not, proceed to the next solution.

## 6\. Temporarily Disable Your Antivirus Program

 If you have an antivirus program installed on your computer, it could block the app from running. To check if this is the case, temporarily disable your antivirus and see if it works. Here's how to do it:

1. Press **Win + I** on your keyboard to [open the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/).
2. Select **Privacy & security** in the left sidebar.
3. Go to the right pane and click **Open Windows Security**.
4. Once you're in Windows Security, select **Virus & threat protection** from the left pane.
5. Next, scroll down to **Virus & threat protection settings** and click **Manage settings**.  
![Manage settings in Windows security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/manage-settings-in-windows-security.jpg)
6. Turn off the **Real-time protection** toggle.  
![Turn off the Real-time protection toggle](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/turn-off-the-real-time-protection-toggle.jpg)

 Now restart your computer and try launching the app again. If the error still persists, turn on Real-time protection and try the next one.

## 7\. Enable Hyper-V in Windows Features

 Hyper-V is a Microsoft virtualization technology that lets some Microsoft Store apps run. If it isn't enabled on your device, you may encounter the “This app will not work on your device” error when installing certain programs.

1. [Open the Control Panel](https://www.makeuseof.com/windows-11-open-control-panel/) and view it in **Category** mode.
2. Go to **Programs > Programs and Features > Turn Windows features on or off**.
3. In the Windows Features dialog, scroll down to **Hyper-V** and check the box next to it.  
![Enable Hyper-V in Windows Features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/enable-hyper-v-in-windows-features.jpg)
4. Similarly, search for **Virtual Machine Platform** and **Windows Hypervisor Platform** and enable them as well.
5. Once done, click **OK > Apply** to save the changes.

 Finally, restart your computer and check if the problem is resolved.

## 8\. Perform Several Generic Windows Fixes

 If none of the above solutions managed to fix the error, you can try performing several generic fixes. This includes [running the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) to scan for missing or corrupted files and the Deployment Image Servicing and Management tool to repair any corrupt system image.

 You can also [reset the Microsoft Store](https://www.makeuseof.com/windows-10-11-reset-microsoft-store/) app to its default settings. This will reset the Store to its original configuration and potentially fix the error you're experiencing.

 If there are still problems, you can try [performing a clean boot](https://www.makeuseof.com/clean-boot-windows-11/). It will launch the device with a minimal set of drivers and programs, allowing you to identify any 3rd-party applications that may be causing the error. Once done, restart your computer normally and check if the error has been fixed.

## Keep Your Apps Up and Running on Windows

 It's okay if you receive a "this app will not work on your device" message; it just means that your system doesn't meet an app's requirements or there is a corrupted Microsoft Store cache. Thankfully, our guide offers solutions to resolve this issue quickly.

 There could be various reasons for this issue depending on the app, such as a corrupted cache file or system problems. Read this guide to learn more about this error and how to fix it.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/overcoming-restrictions-to-write-files-in-windows-11-os/"><u>Overcoming Restrictions to Write Files in Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/evaluating-hidden-gems-in-windows-system-monitors/"><u>Evaluating Hidden Gems in Windows' System Monitors</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-flush-for-your-win11-dns-cache/"><u>The Ultimate Flush for Your Win11 DNS Cache</u></a></li>
<li><a href="https://windows11.techidaily.com/improving-memory-footprint-in-ms-teams/"><u>Improving Memory Footprint in MS Teams</u></a></li>
<li><a href="https://windows11.techidaily.com/innovative-interfaces-windows-following-11/"><u>Innovative Interfaces: Windows Following 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-full-guide-on-mirroring-your-xiaomi-redmi-note-12r-to-your-pcmac-drfone-by-drfone-android/"><u>In 2024, Full Guide on Mirroring Your Xiaomi Redmi Note 12R to Your PC/Mac | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-how-to-schedule-and-dive-into-virtual-gatherings-with-zoom-on-an-android-platform/"><u>2024 Approved  How to Schedule and Dive Into Virtual Gatherings with Zoom on an Android Platform</u></a></li>
<li><a href="https://windows11.techidaily.com/reduce-precision-jumps-turn-off-mouse-speed-on-your-pc/"><u>Reduce Precision Jumps: Turn Off Mouse Speed on Your PC</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-your-infinix-note-30-vip-racing-edition-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>In 2024, How to Mirror Your Infinix Note 30 VIP Racing Edition Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-securely-enabling-controlled-folder-access-in-windows-11/"><u>Navigate Securely: Enabling Controlled Folder Access in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reactivate-nonfunctional-wsreset-service-in-windows/"><u>How to Reactivate Nonfunctional WSReset Service in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-files-in-win-11-with-context-menu-enhancements/"><u>Streamline Your Files in Win 11 with Context Menu Enhancements</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-guidelines-to-affirm-your-youtube-status/"><u>[New] Guidelines to Affirm Your YouTube Status</u></a></li>
<li><a href="https://windows11.techidaily.com/steering-clear-of-disconnect-issues-in-nvidia-software/"><u>Steering Clear of Disconnect Issues in Nvidia Software</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-capture-the-essence-two-effective-ways-to-create-time-lapse-videos-that-impress/"><u>Updated In 2024, Capture the Essence Two Effective Ways to Create Time Lapse Videos That Impress</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaim-default-speaker-levels-post-windows-update/"><u>Reclaim Default Speaker Levels Post-Windows Update</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-recover-and-reset-itunes-when-its-not-working/"><u>How to Recover and Reset iTunes When It's Not Working</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-gaming-experience-installing-windows-on-steam-deck/"><u>Streamline Your Gaming Experience: Installing Windows on Steam Deck</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/2024-approved-take-your-videos-to-the-next-level-top-1080p-editing-tools-and-software/"><u>2024 Approved Take Your Videos to the Next Level Top 1080P Editing Tools and Software</u></a></li>
<li><a href="https://extra-tips.techidaily.com/buying-smart-key-accessories-for-dynamic-cinematography/"><u>Buying Smart  Key Accessories for Dynamic Cinematography</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-develop-windows-custom-text-to-voice-software-using-whisper-and-ahk/"><u>How to Develop Window's Custom Text-To-Voice Software Using Whisper & AHK</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-best-ways-to-record-and-save-itunes-videos/"><u>2024 Approved  Best Ways to Record and Save iTunes Videos</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-uncovering-top-6-free-internet-based-tools-for-tiktok-to-mp3-conversion/"><u>[Updated] 2024 Approved  Uncovering Top 6 FREE, Internet-Based Tools for TikTok to MP3 Conversion</u></a></li>
<li><a href="https://windows11.techidaily.com/harness-the-power-of-windows-11-a-guide-to-7-effective-techniques-36/"><u>Harness the Power of Windows 11: A Guide to 7 Effective Techniques (36)</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-mac-audio-enthusiasts-guide-to-selecting-the-optimal-mp3-trimmer-software/"><u>New Mac Audio Enthusiasts Guide to Selecting the Optimal Mp3 Trimmer Software</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-deciphering-the-innovative-world-of-youtube-studio/"><u>In 2024, Deciphering the Innovative World of YouTube Studio</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-steps-to-launch-wordpad-on-windows/"><u>Seamless Steps to Launch WordPad on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-customize-sound-levels-with-dedicated-win11-keys/"><u>How to Customize Sound Levels with Dedicated Win11 Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-disabled-programs-in-windows/"><u>Unblocking Disabled Programs in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-rectify-faulty-cpu-usage-in-windows-management-console/"><u>Steps to Rectify Faulty CPU Usage in Windows Management Console</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/a-guide-xiaomi-redmi-note-12t-pro-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>A Guide Xiaomi Redmi Note 12T Pro Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-best-free-desktop-pass-gen-software/"><u>The Ultimate Guide to Best Free Desktop Pass Gen Software</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-regain-control-over-non-responsive-overlays/"><u>Strategies to Regain Control over Non-Responsive Overlays</u></a></li>
<li><a href="https://windows11.techidaily.com/safeguard-files-with-windows-controlled-access-feature/"><u>Safeguard Files with Window's Controlled Access Feature</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-lost-data-from-camon-20-by-fonelab-android-recover-data/"><u>How to recover lost data from Camon 20?</u></a></li>
<li><a href="https://windows11.techidaily.com/uncovering-the-oddities-in-windows-11-visual-language/"><u>Uncovering the Oddities in Windows 11 Visual Language</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-setting-up-a-trio-of-widget-boards-in-windows-11/"><u>Step by Step: Setting Up a Trio of Widget Boards in Windows 11</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-break-through-boundaries-15plus-best-free-video-starters/"><u>In 2024, Break Through Boundaries  15+ Best Free Video Starters</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-techniques-for-an-opening-windows-terminal/"><u>Mastering Techniques for an Opening Windows Terminal</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-inactive-mail-signals-on-desktop-os/"><u>Tackling Inactive Mail Signals on Desktop OS</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-seamless-broadcasting-gamers-secrets-from-obs/"><u>[New] 2024 Approved  Seamless Broadcasting  Gamers' Secrets From OBS</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-reliable-remote-connections-in-windows-environment/"><u>Securing Reliable Remote Connections in Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/method-for-handling-device-access-issues-with-audacity-win/"><u>Method for Handling Device Access Issues with Audacity (Win)</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-explore-8-leading-youtube-growth-strategies-for-2024/"><u>[New] Explore 8 Leading Youtube Growth Strategies for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-google-play-services-keeps-stopping-on-nokia-g22-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What to Do if Google Play Services Keeps Stopping on Nokia G22 | Dr.fone</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/updated-2024-approved-a-complete-guide-to-translate-video-with-google/"><u>Updated 2024 Approved A Complete Guide To Translate Video With Google</u></a></li>
<li><a href="https://windows11.techidaily.com/remedies-for-sudden-stoppages-of-windows-notepad-app/"><u>Remedies for Sudden Stoppages of Windows Notepad App</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-high-end-displays-ranked-1-to-5-ps5/"><u>2024 Approved  High-End Displays Ranked #1 to #5 (PS5)</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-bypass-iphone-14-plus-passcode-easily-video-inside-drfone-by-drfone-ios/"><u>How to Bypass iPhone 14 Plus Passcode Easily Video Inside | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-touchpad-sensitivity-in-windows-11-devices/"><u>Mastering Touchpad Sensitivity in Windows 11 Devices</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-methods-to-change-gps-location-on-nubia-z50-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, Methods to Change GPS Location On Nubia Z50 Ultra | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-quick-screen-cut-and-paste-in-winoses/"><u>[New] 2024 Approved  Quick Screen Cut & Paste in WinOSes</u></a></li>
<li><a href="https://windows11.techidaily.com/integrating-nas-into-mobile-device-setups/"><u>Integrating NAS Into Mobile Device Setups</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-rectify-preview-failures-in-outlook-for-pcs/"><u>Steps to Rectify Preview Failures in Outlook for PCs</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-swift-and-efficient-turning-youtube-vids-into-mp4-high-definition-via-online-service-for-2024/"><u>[New] Swift & Efficient  Turning YouTube Vids Into MP4, High-Definition via Online Service for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-resolving-windows-11s-isdonedll-problems/"><u>Strategies for Resolving Windows 11'S ISDone.dll Problems</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-videos-from-nokia-150-2023-by-fonelab-android-recover-video/"><u>The way to get back lost videos from Nokia 150 (2023)</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/from-basic-to-brilliant-mastering-video-editing-effects-for-beginners-for-2024/"><u>From Basic to Brilliant Mastering Video Editing Effects for Beginners for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-apex-stream-recorders-compendium/"><u>[New] Apex Stream Recorders Compendium</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-white-or-gray-microsoft-store-display/"><u>Fixing White or Gray Microsoft Store Display</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-androids-best-top-8-gratuitous-capture-tools/"><u>[New] In 2024, Android's Best  Top 8 Gratuitous Capture Tools</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-swiftrecorder-plus-soundtrack-guided-screen-recording/"><u>[Updated] SwiftRecorder Plus - Soundtrack Guided Screen Recording</u></a></li>
<li><a href="https://windows11.techidaily.com/getting-acquainted-with-apple-maps-on-windows-desktops/"><u>Getting Acquainted with Apple Maps on Windows Desktops</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-social-media-savvy-instagrams-best-tips-for-gif-uploads-and-posting/"><u>2024 Approved  Social Media Savvy  Instagram's Best Tips for GIF Uploads and Posting</u></a></li>
<li><a href="https://windows11.techidaily.com/tricks-to-extend-the-wait-window-in-windows-10-before-restarting/"><u>Tricks to Extend the Wait Window in Windows 10 Before Restarting</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-detailed-guide-of-ispoofer-for-pogo-installation-on-nokia-xr21-drfone-by-drfone-virtual-android/"><u>In 2024, Detailed guide of ispoofer for pogo installation On Nokia XR21 | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/silent-void-after-graphic-installation/"><u>Silent Void After Graphic Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-power-of-local-gpo-control-on-windows-11/"><u>Unlock the Power of Local GPO Control on Windows 11</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-streamlining-video-sharing-across-youtube-and-tiktok/"><u>2024 Approved  Streamlining Video Sharing Across YouTube and TikTok</u></a></li>
</ul></div>
