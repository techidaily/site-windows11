---
title: Restoring Microsoft Store Programs on Windows 10/11 Systems
date: 2024-07-11T21:21:40.746Z
updated: 2024-07-12T21:21:40.746Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Microsoft Store Programs on Windows 10/11 Systems
excerpt: This Article Describes Restoring Microsoft Store Programs on Windows 10/11 Systems
keywords: Win10 Restore MS Store,Reinstalling MS Store,Fix MS Store Error,Repair MS Store Access,Regain Windows Store Functionality,Update Microsoft Apps,Maintain Microsoft Store Compatibility
thumbnail: https://thmb.techidaily.com/605743c45d46920946cf620896ea214cdef6126e457144d63179eeaf5994b016.jpg
---

## Restoring Microsoft Store Programs on Windows 10/11 Systems

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

## How to Re-Register Microsoft Store Apps for Current Users

![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

 If the [Microsoft Store app issue](https://www.makeuseof.com/tag/5-tips-fix-windows-store-app-issues-windows-10/) exists with a specific user account, you don’t need to re-register the app for all the user accounts on your computer. Instead, you can re-register the app only for the current user account.

To re-register Microsoft Store apps for the current user:

1. Press the**Win** key and type "powershell" into the Search bar.
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell console, type the following command and press**Enter** :  
`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
4. Wait for the command to execute and complete. You may see a blue loading graphic.
5. Once done, type**exit** and press**Enter** to close PowerShell.

 During the process, you may see some errors highlighted in red. It is due to PowerShell trying to reinstall existing apps on Windows. So, ignore the error and wait for the process to complete.

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

## Install and Re-Register All Microsoft Store Apps on Windows 11

 Re-registering Windows apps is often necessary when Microsoft Store is not working. It can also help deal with other Windows settings and apps. If the issue persists, try the built-in Windows Store Apps troubleshooter to fix common Microsoft Store app issues.


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
<li><a href="https://windows11.techidaily.com/windows-reimagined-make-it-mirror-macos-style-in-5-easy-ways/"><u>Windows Reimagined: Make It Mirror macOS Style in 5 Easy Ways</u></a></li>
<li><a href="https://windows11.techidaily.com/browser-bugs-and-breakages-fixing-website-issues-on-your-windows-pc/"><u>Browser Bugs & Breakages: Fixing Website Issues on Your Window's PC</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-failed-auto-detection-of-windows-proxy/"><u>Troubleshooting Failed Auto-Detection of Windows Proxy</u></a></li>
<li><a href="https://windows11.techidaily.com/the-path-to-defaults-resetting-win11-admin-permissions/"><u>The Path to Defaults: Resetting Win11 Admin Permissions</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-productivity-best-apps-to-turn-your-pcs-clock-into-an-animated-screensaver/"><u>Streamline Productivity: Best Apps to Turn Your PC’s Clock Into an Animated Screensaver</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-file-scooping-6-routes-to-data-secrets/"><u>Swift File Scooping: 6 Routes to Data Secrets</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-unearthing-the-best-free-mac-apps-for-speech-to-text-for-2024/"><u>[New] Unearthing the Best Free Mac Apps for Speech to Text for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-guide-to-generating-gpo-data-with-gpresult/"><u>The Essential Guide to Generating GPO Data with GPResult</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-automatic-screenshore-changes-in-win11/"><u>Preventing Automatic Screenshore Changes in Win11</u></a></li>
<li><a href="https://android-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-oppo-find-n3-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Oppo Find N3</u></a></li>
<li><a href="https://windows11.techidaily.com/smoothening-playback-speed-in-vlc-for-windows/"><u>Smoothening Playback Speed in VLC for Windows</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-essential-steps-for-elevating-wmm-content-on-vimeo-platform/"><u>[Updated] 2024 Approved  Essential Steps for Elevating WMM Content on Vimeo Platform</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-iphone-12-mini-3-ways-to-unlock-by-drfone-ios/"><u>How To Unlock iPhone 12 mini 3 Ways To Unlock</u></a></li>
<li><a href="https://windows11.techidaily.com/secrets-to-savings-on-windows-10-key-focused-strategies/"><u>Secrets to Savings on Windows 10: Key-Focused Strategies</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-ultimate-strategies-for-instagram-stories-mastery/"><u>[New] In 2024, Ultimate Strategies for Instagram Stories Mastery</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-do-you-need-to-make-your-video-more-immersive-you-can-make-it-60-fps-to-achieve-that-and-here-are-the-5-best-tools-that-you-can-use/"><u>New 2024 Approved Do You Need to Make Your Video More Immersive? You Can Make It 60 FPS to Achieve That. And Here Are the 5 Best Tools that You Can Use</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-aspect-ratio-made-easy-top-calculators-for-designers/"><u>Updated In 2024, Aspect Ratio Made Easy Top Calculators for Designers</u></a></li>
<li><a href="https://windows11.techidaily.com/banishing-desktop-colors-8-fixes-when-windows-turns-rare-hues/"><u>Banishing Desktop Colors: 8 Fixes When Windows Turns Rare Hues</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-resolve-high-dpi-screen-problems-on-pc/"><u>Strategies to Resolve High DPI Screen Problems on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-edge-solutions-exclusive-windows-systems-for-dsswitch-players/"><u>Cutting-Edge Solutions: Exclusive Windows Systems for DS/Switch Players</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-11-free-apps-to-check-imei-on-asus-phones-by-drfone-android/"><u>Top 11 Free Apps to Check IMEI on Asus Phones</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-from-noise-to-masterpiece-10-glitch-art-video-editing-apps-for-mobile-devices-for-2024/"><u>New From Noise to Masterpiece 10 Glitch Art Video Editing Apps for Mobile Devices for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-in-2024-giggles-in-a-box-iphone-fun/"><u>[New] In 2024, Giggles in a Box (iPhone Fun)</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-combine-wmv-videos-for-free-top-5-tools-for-2024/"><u>Updated Combine WMV Videos for Free Top 5 Tools for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/make-a-boomerang-on-snapchat-a-comprehensive-guide-for-2024/"><u>Make a Boomerang on Snapchat – A Comprehensive Guide for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-bridge-gaps-in-generations-of-viewers-6-interactive-tests-to-find-your-youtube-match/"><u>[Updated] 2024 Approved  Bridge Gaps in Generations of Viewers  6 Interactive Tests to Find Your YouTube Match</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-swift-solutions-moving-iphone-pictures-and-videos/"><u>In 2024, Swift Solutions  Moving iPhone Pictures & Videos</u></a></li>
<li><a href="https://techidaily.com/solutions-to-restore-deleted-files-from-oppo-reno-10-pro-5g-by-fonelab-android-recover-data/"><u>Solutions to restore deleted files from Oppo Reno 10 Pro 5G</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-remove-reno-9a-pin-by-drfone-android-unlock-android-unlock/"><u>How to remove Reno 9A PIN</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-from-silence-to-sound-a-guide-to-tiktok-voiceover/"><u>[Updated] From Silence to Sound  A Guide to TikTok Voiceover</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-review-for-parrot-ar-drone-20-elite-edition/"><u>[New] Review for Parrot AR Drone 2.0 Elite Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-screen-resets-for-windows-users/"><u>Streamlining Screen Resets for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-inaccessible-page-errors-for-windows-store-apps/"><u>Addressing Inaccessible Page Errors for Windows Store Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-the-windows-application-net-demand-error/"><u>Resolving the Windows Application .NET Demand Error</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-echoes-of-collaboration-tiktok-duet-hits-for-2024/"><u>[New] Echoes of Collaboration  TikTok Duet Hits for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-unleashing-creativity-advanced-obs-techniques-explained/"><u>[Updated] Unleashing Creativity  Advanced OBS Techniques Explained</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/top-10-fingerprint-lock-apps-to-lock-your-nubia-z50s-pro-phone-by-drfone-android/"><u>Top 10 Fingerprint Lock Apps to Lock Your Nubia Z50S Pro Phone</u></a></li>
<li><a href="https://windows11.techidaily.com/curb-high-gpu-demand-with-proven-fixes-for-wm-on-windows/"><u>Curb High GPU Demand with Proven Fixes for WM on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/banishing-0x800700e9-glitches-in-xbox-game-pass-on-windows-11-devices/"><u>Banishing 0X800700E9 Glitches in Xbox Game Pass on Windows 11 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/pc-files-on-ios-via-smb-share-connection/"><u>PC Files on iOS via SMB Share Connection</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-pc-performance-hiccups-in-warhammer-40k-boltgun/"><u>Tackling PC Performance Hiccups in Warhammer 40K Boltgun</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-no-sync-option-on-steam-library-error/"><u>Tackling the No Sync Option on Steam Library Error</u></a></li>
<li><a href="https://fake-location.techidaily.com/spoofing-life360-how-to-do-it-on-honor-x50-gt-drfone-by-drfone-virtual-android/"><u>Spoofing Life360 How to Do it on Honor X50 GT? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-vivo-x-flip-phone-without-password-by-drfone-android/"><u>In 2024, How To Unlock Vivo X Flip Phone Without Password?</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-in-2024-best-no-cost-video-editors-for-side-by-side-videos-online-and-offline/"><u>Updated In 2024, Best No-Cost Video Editors for Side-by-Side Videos Online & Offline</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-start-adding-windows-hello-to-your-pc/"><u>Quick Start: Adding Windows Hello to Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/win-back-missing-5ghz-connection-on-your-windows-pc/"><u>Win Back Missing 5GHz Connection on Your Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-discord-from-starting-with-windows-boot/"><u>Preventing Discord From Starting with Windows Boot</u></a></li>
<li><a href="https://windows11.techidaily.com/what-is-bluescreenview-and-how-do-you-use-it/"><u>What Is BlueScreenView and How Do You Use It?</u></a></li>
<li><a href="https://windows11.techidaily.com/redefining-virtual-meetings-a-lightweight-approach/"><u>Redefining Virtual Meetings: A Lightweight Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/reestablishing-copy-pasting-efficiency-across-browsers/"><u>Reestablishing Copy-Pasting Efficiency Across Browsers</u></a></li>
<li><a href="https://windows11.techidaily.com/an-intuitive-guide-to-performing-a-windows-rollback-via-system-restore/"><u>An Intuitive Guide to Performing a Windows Rollback via System Restore</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-homes-unlocked-your-guide-to-installing-hyper-v/"><u>Win 11 Homes Unlocked: Your Guide to Installing Hyper-V</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-steps-for-online-printer-on-windows/"><u>Quick Steps for Online Printer on Windows</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-cast-tecno-spark-10-pro-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>How to Cast Tecno Spark 10 Pro Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/on-demand-content-examination-summary-for-2024/"><u>On-Demand Content Examination Summary for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-2024-approved-get-creative-with-slow-mo-top-video-editing-software-for-filmmakers/"><u>New 2024 Approved Get Creative with Slow Mo Top Video Editing Software for Filmmakers</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-mastering-virtual-worlds-choosing-metavisors-wisely/"><u>In 2024, Mastering Virtual Worlds  Choosing Metavisors Wisely</u></a></li>
<li><a href="https://windows11.techidaily.com/triumph-over-outdated-updates-winning-strategies-revealed/"><u>Triumph Over Outdated Updates: Winning Strategies Revealed</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-lava-yuva-3-to-other-android-devices-using-bluetooth-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Lava Yuva 3 to Other Android Devices Using Bluetooth? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-reversion-of-graphics-settings-for-optimal-viewing/"><u>Quick Reversion of Graphics Settings for Optimal Viewing</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-win11-with-powertoys-installation/"><u>Streamlining Win11 with PowerToys Installation</u></a></li>
<li><a href="https://extra-information.techidaily.com/premier-tools-for-image-transformation-framecraft-pro/"><u>Premier Tools for Image Transformation  FrameCraft Pro</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-simplified-method-for-youtubers-to-dailymotion/"><u>2024 Approved  Simplified Method for YouTubers to Dailymotion</u></a></li>
</ul></div>
