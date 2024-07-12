---
title: Directing Biometric Access Control for Windows 11 Users
date: 2024-07-11T22:21:52.777Z
updated: 2024-07-12T22:21:52.777Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Directing Biometric Access Control for Windows 11 Users
excerpt: This Article Describes Directing Biometric Access Control for Windows 11 Users
keywords: Bioaccess Control in Win11,Windows 11 Biometrics Secure,Win11 User Access Security,BIoMetric Entry for WinUsers,Windows 11 Facial Recognition,Biometric Gateway Win11,Windows 11 Fingerprint Authorize
thumbnail: https://thmb.techidaily.com/b7fdec82e5e2a50f89b07a18bb64e205705f93d7819f0fe370579d848f9daaea.jpg
---

## Directing Biometric Access Control for Windows 11 Users

 Biometric authentication allows you to quickly log in to the system using fingerprint, facial, or iris recognition. However, what if you want to prevent a domain user from logging in using biometrics?

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

## How to Allow or Block a Biometrics Log-On via the Local Group Policy Editor

 The quickest way to configure your computer to allow or block a biometrics scan for domain users is through the Local Group Policy Editor. Here are the steps you need to follow:

1. Press the **Win + R** key to open the **Run tool.**
2. Type **gpedit.msc** in the search bar and click OK.
3. In the Local Group Policy Editor, head towards the following location:  
`Computer Configuration > Administrative Templates > Windows Components > Biometrics`
4. Double-click on the **Allow domain users to log on using biometrics** policy in the right pane.  
![Allow domain users to log on using biometrics policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/allow-domain-users-to-log-on-using-biometrics-policy.jpg)
5. Choose the **Enabled** option to allow biometrics log on for the domain users. And choose the **Disabled** option to block biometrics log on for the domain users.  
![Enable option in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/enable-option.png)
6. Click **Apply** \> **OK** to save the changes.

## How to Allow or Block a Biometrics Log-On Using the Registry Editor

 Another way to configure biometrics log-on for the domain users is through the Registry Editor. Here's how:

 Editing the registry is risky, as one wrong edit can make your system unstable. Therefore, make sure to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps.

1. Open the Run tool, type **regedit** in the search bar, and press Enter.
2. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Biometrics\Credential Provider`
3. Right-click the **Credential Provider** key in the left sidebar, hover the cursor to **New,** and choose **DWORD (32-bit) Value**.  
![DWORD (32-bit) Value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/dword-32-bit-value.jpg)
4. Name the value **Domain Accounts.**  
![Naming the Value Domain Accounts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/domain-accounts.jpg)
5. Double-click on the Domain Accounts value, type **1** in the **Value data** section to enable biometrics log on and **0** to disable biometrics log on for domain users.  
![Editing the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/value-data.jpg)
6. Click **OK** to save the changes.

## Control Biometrics Logins on Your Computer

 Securing sensitive information has now become more important than ever. If you want to allow or block a domain user from logging on using biometrics, you can do that using the above methods.

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/decode-and-dissolve-rectifying-win11-webcam-issue-error-a00f4289/"><u>Decode & Dissolve: Rectifying Win11 Webcam Issue - Error A00F4289</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-troubleshooting-error-connecting-to-the-apple-id-server-on-iphone-11-pro-max-by-drfone-ios/"><u>In 2024, Troubleshooting Error Connecting to the Apple ID Server On iPhone 11 Pro Max</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/in-2024-top-8-ar-apps-for-android-and-ios-help-you-see-the-world-of-ar/"><u>In 2024, Top 8 AR Apps for Android and iOS | Help You See the World of AR</u></a></li>
<li><a href="https://windows11.techidaily.com/digital-revolution-at-your-fingertips-master-paint-updates/"><u>Digital Revolution at Your Fingertips - Master Paint Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-windows-audio-graph-isolation/"><u>Decoding Windows Audio Graph Isolation</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-camera-access-overlap-in-windows-apps/"><u>Correcting Camera Access Overlap in Windows Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensible-guide-to-counteracting-winerror-0x80071a90/"><u>Comprehensible Guide to Counteracting WinError 0X80071a90</u></a></li>
<li><a href="https://windows11.techidaily.com/data-mastery-for-pcs-uncovering-5-top-notch-fileshare-tools/"><u>Data Mastery for PCs: Uncovering 5 Top-Notch Fileshare Tools</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-how-to-save-instagram-audio-a-step-by-step-guide/"><u>2024 Approved How to Save Instagram Audio A Step-by-Step Guide</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-instabeats-intellectual-property-overview/"><u>[Updated] InstaBeats  Intellectual Property Overview</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-cost-free-treasure-hunts-finding-gorgeous-tiktok-backdrops/"><u>[Updated] Cost-Free Treasure Hunts  Finding Gorgeous TikTok Backdrops</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/catchemall-celebrate-national-pokemon-day-with-virtual-location-on-lava-blaze-2-pro-drfone-by-drfone-virtual-android/"><u>CatchEmAll Celebrate National Pokémon Day with Virtual Location On Lava Blaze 2 Pro | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/11-ways-to-fix-it-when-my-vivo-v29-wont-charge-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Ways to Fix it When My Vivo V29 Wont Charge | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-discord-setup-woes-on-windows-11/"><u>Correcting Discord Setup Woes on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/hidden-sd-card-regain-access-with-troubleshooting-guide/"><u>Hidden SD Card: Regain Access with Troubleshooting Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/cut-through-the-frustration-swift-solutions-for-ms-teams-error-80080300-in-win11/"><u>Cut Through the Frustration: Swift Solutions for MS Teams Error 80080300 in Win11</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-mastering-the-art-of-sniping-on-mac-with-these-tools/"><u>2024 Approved  Mastering the Art of Sniping on Mac with These Tools</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-enhancing-gamers-experience-recording-console-titles-for-pc/"><u>[Updated] 2024 Approved  Enhancing Gamers' Experience  Recording Console Titles for PC</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-the-perfect-fit-adjusting-amazon-prime-video-aspect-ratio-for-any-tv/"><u>In 2024, The Perfect Fit Adjusting Amazon Prime Video Aspect Ratio for Any TV</u></a></li>
<li><a href="https://windows11.techidaily.com/dial-back-the-dread-of-an-unresponsive-esc-button-in-windows/"><u>Dial Back the Dread of an Unresponsive Esc Button in Windows</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-flash-video-insights-guide-for-2024/"><u>[New] Flash Video Insights Guide for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/mastering-the-soundtrack-the-quintessential-rock-playlist-for-2024/"><u>Mastering the Soundtrack The Quintessential Rock Playlist for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/diagnosing-and-fixing-microsoft-windows-nearby-share-malfunction/"><u>Diagnosing and Fixing Microsoft Windows Nearby Share Malfunction</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-error-code-zero-on-your-gaming-machine/"><u>Disabling Error Code Zero on Your Gaming Machine</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-dism-your-ultimate-toolkit-for-fixing-win11/"><u>Decoding DISM: Your Ultimate Toolkit for Fixing Win11</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/in-2024-navigating-the-increasedecrease-functionality-in-audacity-for-clearer-sounds/"><u>In 2024, Navigating the Increase/Decrease Functionality in Audacity for Clearer Sounds</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-in-2024-the-art-of-creating-soundtrack-enhanced-media-at-little-or-no-cost/"><u>New In 2024, The Art of Creating Soundtrack-Enhanced Media at Little or No Cost</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/decoding-chroma-techniques-from-raw-footage-to-final-cut-for-2024/"><u>Decoding Chroma Techniques  From Raw Footage to Final Cut for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/compre-written-guide-to-repair-xbox-live-glitches/"><u>Compre Written Guide To Repair Xbox Live Glitches</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-another-program-uses-device-in-windows-sound-system/"><u>Correcting 'Another Program Uses Device' In Windows Sound System</u></a></li>
<li><a href="https://howto.techidaily.com/6-fixes-to-unfortunately-whatsapp-has-stopped-error-popups-on-nubia-red-magic-9-proplus-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Fixes to Unfortunately WhatsApp has stopped Error Popups On Nubia Red Magic 9 Pro+ | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/guides-to-mastering-your-fax-interface-with-w11s-tools/"><u>Guides to Mastering Your Fax Interface with W11's Tools</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-itel-s23-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Itel S23 without Losing Data | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-expert-reviews-find-the-best-8-5k-computer-displays/"><u>2024 Approved  Expert Reviews - Find the Best 8 5K Computer Displays</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-windows-error-code-31-and-network-adapter-issues/"><u>Demystifying Windows Error Code 31 and Network Adapter Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-the-purpose-of-pagefilesys-within-os-structure/"><u>Dissecting the Purpose of Pagefile.sys Within OS Structure</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/advanced-recording-setup-gamers-guide-to-flawless-footage/"><u>Advanced Recording Setup  Gamers' Guide to Flawless Footage</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-fix-icloud-lock-from-your-apple-iphone-15-pro-and-ipad-by-drfone-ios/"><u>How to fix iCloud lock from your Apple iPhone 15 Pro and iPad</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-premium-picks-for-the-ultimate-gopro-experience/"><u>2024 Approved  Premium Picks for the Ultimate Gopro Experience</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-mastering-the-seamless-transition-from-obs-to-facebook-live-for-2024/"><u>[Updated] Mastering the Seamless Transition From OBS to Facebook Live for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/disarming-error-dism-0x800f082f-on-microsoft-os/"><u>Disarming Error: DISM 0X800F082F on Microsoft OS</u></a></li>
<li><a href="https://windows11.techidaily.com/decode-your-digital-identity-how-to-find-out-what-computer-you-have/"><u>Decode Your Digital Identity: How to Find Out What Computer You Have</u></a></li>
<li><a href="https://windows11.techidaily.com/consistent-experience-migrating-powertoys-on-new-pcs/"><u>Consistent Experience: Migrating PowerToys on New PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/diving-into-windows-n-types-benefits-and-downfalls/"><u>Diving Into Windows N Types: Benefits and Downfalls</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-sound-misstep-solving-xc00d36b4-on-windows/"><u>Decoding Sound Misstep: Solving XC00D36B4 on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/creating-custom-volume-control-commands-for-windows-11-users/"><u>Creating Custom Volume Control Commands for Windows 11 Users</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-navigate-the-world-of-tiktok-with-top-7-emoji-expertise-for-2024/"><u>[Updated] Navigate the World of TikTok with Top 7 Emoji Expertise for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-and-correcting-irq-glitches/"><u>Deciphering and Correcting IRQ Glitches</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensible-guide-to-revoking-custom-search-on-windows-11/"><u>Comprehensible Guide to Revoking Custom Search on Windows 11</u></a></li>
<li><a href="https://fox-links.techidaily.com/unveiling-the-secrets-of-video-filter-application-techniques-for-2024/"><u>Unveiling the Secrets of Video Filter Application Techniques for 2024</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/in-2024-mastering-twitter-cleanup-top-apps-for-efficient-management/"><u>In 2024, Mastering Twitter Cleanup  Top Apps for Efficient Management</u></a></li>
<li><a href="https://windows11.techidaily.com/command-prompt-mastery-the-fundamental-20-cmd-commands-to-know/"><u>Command Prompt Mastery: The Fundamental 20 CMD Commands to Know</u></a></li>
<li><a href="https://windows11.techidaily.com/dial-down-display-flicker-in-windows-11-devices/"><u>Dial Down Display Flicker in Windows 11 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-classic-visuals-a-guide-to-shader-magic-in-retroarc/"><u>Crafting Classic Visuals: A Guide to Shader Magic in RetroArc</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-pixelpranks-mememakermarket/"><u>[New] PixelPranks  MemeMakerMarket</u></a></li>
<li><a href="https://windows11.techidaily.com/controlling-clock-display-in-windows-11-taskbar/"><u>Controlling Clock Display in Windows 11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-resource-locks-in-windows-11-environments/"><u>Disabling Resource Locks in Windows 11 Environments</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-clock-divergence-chrome-vs-windows/"><u>Correcting Clock Divergence: Chrome vs Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-incompatible-drivers-on-windows-11/"><u>Correcting Incompatible Drivers on Windows 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/process-of-screen-sharing-motorola-moto-g23-to-pc-detailed-steps-drfone-by-drfone-android/"><u>Process of Screen Sharing Motorola Moto G23 to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/clear-path-to-app-removal-tackling-do-not-have-access-errors/"><u>Clear Path to App Removal: Tackling Do Not Have Access Errors</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-music-from-tecno-spark-10-4g-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Music from Tecno Spark 10 4G to iPod | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/curing-windows-security-hiccups-in-win-11-system/"><u>Curing Windows Security Hiccups in Win 11 System</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-htc-u23-pro-phone-frp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your HTC U23 Pro Phone FRP Lock</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-try-before-you-buy-final-cut-pro-90-day-free-trial/"><u>Updated Try Before You Buy Final Cut Pro 90-Day Free Trial</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/latest-guide-how-to-bypass-honor-100-pro-frp-without-computer-by-drfone-android/"><u>Latest Guide How To Bypass Honor 100 Pro FRP Without Computer</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-optimal-audio-bots-guide-unleashing-peak-performance-in-discord/"><u>2024 Approved  Optimal Audio Bots Guide  Unleashing Peak Performance in Discord</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-html-display-issues-in-windows-11-email-client/"><u>Correcting HTML Display Issues in Windows 11 Email Client</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>