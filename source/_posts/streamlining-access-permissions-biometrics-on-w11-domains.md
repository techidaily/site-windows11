---
title: "Streamlining Access Permissions: Biometrics on W11, Domains"
date: 2024-08-15T16:02:36.239Z
updated: 2024-08-16T16:02:36.239Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Streamlining Access Permissions: Biometrics on W11, Domains"
excerpt: "This Article Describes Streamlining Access Permissions: Biometrics on W11, Domains"
keywords: Bio-ID on Windows 11,Win11 Biometric Login,Domain Authentication,Access Control Tech,Secure Entry Systems,Permissions Streamlining,Identity Verification W11
thumbnail: https://thmb.techidaily.com/ae96135be8b387f3dfcd58e7778aa73a8a480a5ecd8a0532a8cb17367d809b46.jpg
---

## Streamlining Access Permissions: Biometrics on W11, Domains

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

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## How to Allow or Block a Biometrics Log-On Using the Registry Editor

 Another way to configure biometrics log-on for the domain users is through the Registry Editor. Here's how:

 Editing the registry is risky, as one wrong edit can make your system unstable. Therefore, make sure to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps.

1. Open the Run tool, type **regedit** in the search bar, and press Enter.
2. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Biometrics\Credential Provider`
3. Right-click the **Credential Provider** key in the left sidebar, hover the cursor to **New,** and choose **DWORD (32-bit) Value**.  
![DWORD (32-bit) Value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/dword-32-bit-value.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->
4. Name the value **Domain Accounts.**  
![Naming the Value Domain Accounts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/domain-accounts.jpg)
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Double-click on the Domain Accounts value, type **1** in the **Value data** section to enable biometrics log on and **0** to disable biometrics log on for domain users.  
![Editing the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/value-data.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
6. Click **OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
## Control Biometrics Logins on Your Computer

 Securing sensitive information has now become more important than ever. If you want to allow or block a domain user from logging on using biometrics, you can do that using the above methods.

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-videos.techidaily.com/new-bridge-gaps-in-generations-of-viewers-6-interactive-tests-to-find-your-youtube-match/"><u>[New] Bridge Gaps in Generations of Viewers  6 Interactive Tests to Find Your YouTube Match</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-comprehensive-guide-free-and-paid-tools-for-noise-reduction-for-2024/"><u>[New] Comprehensive Guide  Free & Paid Tools for Noise Reduction for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-in-2024-the-evolution-of-video-from-sdr-to-the-era-of-high-dynamic-range/"><u>[New] In 2024, The Evolution of Video  From SDR to the Era of High Dynamic Range</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-unraveling-360-degree-vision-a-new-cinematic-experience/"><u>[New] Unraveling 360-Degree Vision  A New Cinematic Experience</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-mastering-monetization-an-instagram-income-journey/"><u>[Updated] 2024 Approved  Mastering Monetization  An Instagram Income Journey</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-2024-approved-pinnacle-portals-high-performance-laptops-for-uhd-videos/"><u>[Updated] 2024 Approved  Pinnacle Portals  High-Performance Laptops for UHD Videos</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-enhancing-social-media-visibility-with-quality-livestreams-on-wirecast-for-2024/"><u>[Updated] Enhancing Social Media Visibility with Quality Livestreams on Wirecast for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-in-2024-demystifying-the-process-of-full-degree-videography-in-adobe-premiere/"><u>[Updated] In 2024, Demystifying the Process of Full Degree Videography in Adobe Premiere</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-from-filters-to-feeds-optimizing-your-360-video-for-youtube-publishing/"><u>[Updated] In 2024, From Filters to Feeds  Optimizing Your 360 Video for YouTube Publishing</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-learn-the-best-practices-for-capturing-instagram-live-feeds/"><u>[Updated] Learn the Best Practices for Capturing Instagram Live Feeds</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-maximizing-engagement-with-instagrams-ask-emoji/"><u>[Updated] Maximizing Engagement with Instagram's Ask Emoji</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-overcoming-the-noise-barrier-twitter-vids-without-sounds-for-2024/"><u>[Updated] Overcoming the Noise Barrier  Twitter Vids Without Sounds for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-quick-and-easy-instructions-for-launching-skype-group-conversations-on-both-windows-and-macos/"><u>[Updated] Quick and Easy Instructions for Launching Skype Group Conversations on Both Windows & MacOS</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-premier-video-breakdown-fifa-analysis-graphs/"><u>2024 Approved  Premier Video Breakdown  FIFA Analysis Graphs</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-radiance-and-refine-essential-editing-secrets-revealed/"><u>2024 Approved  Radiance and Refine  Essential Editing Secrets Revealed</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-solutions-for-non-deliverable-facebook-messenger-videos-on-androidios/"><u>2024 Approved  Solutions for Non-Deliverable Facebook Messenger Videos on Android/iOS</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-techniques-for-fabulous-photo-collage-artistry/"><u>2024 Approved  Techniques for Fabulous Photo Collage Artistry</u></a></li>
<li><a href="https://windows11.techidaily.com/4-warning-signs-for-considering-pc-reset/"><u>4 Warning Signs for Considering PC Reset</u></a></li>
<li><a href="https://windows11.techidaily.com/8-ways-to-fix-the-windows-desktop-when-it-turns-pink-or-purple/"><u>8 Ways to Fix the Windows Desktop When It Turns Pink or Purple</u></a></li>
<li><a href="https://windows11.techidaily.com/a-guide-to-the-voice-recorder-keyboard-shortcuts-on-windows-11/"><u>A Guide to the Voice Recorder Keyboard Shortcuts on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerate-typing-with-personal-hotkeys-in-windows/"><u>Accelerate Typing with Personal Hotkeys in Windows</u></a></li>
<li><a href="https://tech-revival.techidaily.com/aeroco-pilots-essential-distinctions-between-models/"><u>AeroCo-Pilots: Essential Distinctions Between Models</u></a></li>
<li><a href="https://windows11.techidaily.com/bringing-business-efficiency-installing-ms-works-on-windows/"><u>Bringing Business Efficiency: Installing MS Works on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/building-a-personalized-voice-transcription-tool-on-windows-using-ahk/"><u>Building a Personalized Voice Transcription Tool on Windows Using AHK</u></a></li>
<li><a href="https://fox-glue.techidaily.com/cutting-edge-guide-to-mastering-windows-11-conferencing-via-zoom-for-2024/"><u>Cutting-Edge Guide to Mastering Windows 11 Conferencing via Zoom for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-purpose-behind-windows-11-s-mode-feature/"><u>Deciphering the Purpose Behind Windows 11 S Mode Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-error-x-on-windows-a-guide-to-email-repair/"><u>Decoding Error X on Windows: A Guide to Email Repair</u></a></li>
<li><a href="https://driver-download.techidaily.com/easy-steps-to-update-and-get-the-best-performance-from-your-wireless-adaptors-software/"><u>Easy Steps to Update and Get the Best Performance From Your Wireless Adaptor's Software</u></a></li>
<li><a href="https://program-issues.techidaily.com/effective-fixes-for-pandoras-troubled-waters-in-avatar-frontiers-of-pandora/"><u>Effective Fixes for Pandora's Troubled Waters in 'Avatar: Frontiers of Pandora'</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-productivity-enable-a-search-bar-on-win11s-taskbar/"><u>Elevate Your Productivity: Enable a Search Bar on Win11's Taskbar</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/elite-faster-imagery-screen-reader-for-2024/"><u>Elite Faster Imagery Screen Reader for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/fix-the-error-of-unfortunately-the-processcomandroidphone-has-stopped-on-oneplus-open-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix the Error of Unfortunately the Process.com.android.phone Has Stopped on OnePlus Open | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-inaccessible-files-on-windows-platform/"><u>Fixing Inaccessible Files on Windows Platform</u></a></li>
<li><a href="https://windows11.techidaily.com/from-edge-to-frontline-quick-fixes-for-lost-off-screen-windows/"><u>From Edge to Frontline: Quick Fixes for Lost Off-Screen Windows</u></a></li>
<li><a href="https://howto.techidaily.com/full-solutions-to-fix-error-code-920-in-google-play-on-oppo-reno-8t-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Solutions to Fix Error Code 920 In Google Play on Oppo Reno 8T | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/guide-to-mirror-your-honor-magic-vs-2-to-other-android-devices-drfone-by-drfone-android/"><u>Guide to Mirror Your Honor Magic Vs 2 to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-disable-update-notifications-on-windows/"><u>How to Disable Update Notifications on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-troubleshooters-not-working-in-windows-10-and-11/"><u>How to Fix the Troubleshooters Not Working in Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-rectify-steams-server-disconnection-on-windows-machines/"><u>How to Rectify Steam's Server Disconnection on Windows Machines</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-redo-on-windows-with-a-hotkey/"><u>How to Redo on Windows With a Hotkey</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-reset-your-vivo-y36-lock-screen-password-by-drfone-android/"><u>How to Reset your Vivo Y36 Lock Screen Password</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-stop-windows-from-always-entering-cmos-mode-at-start-up/"><u>How to Stop Windows From Always Entering CMOS Mode at Start-Up</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-honor-v-purse-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>How to Unlock Honor V Purse Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-vivo-s17-drfone-by-drfone-virtual-android/"><u>In 2024, Can I use iTools gpx file to catch the rare Pokemon On Vivo S17 | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-craft-a-closer-vision-5-easy-ways-to-enhance-minecraft-screens/"><u>In 2024, Craft a Closer Vision  5 Easy Ways to Enhance Minecraft Screens</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-fake-gps-location-spoofer-a-good-choice-on-samsung-galaxy-m54-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Is Fake GPS Location Spoofer a Good Choice On Samsung Galaxy M54 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/making-your-notes-pop-in-win-1011-os/"><u>Making Your Notes Pop in Win 10/11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-apex-servers-on-pc-7-ways-to-fix-no-server-errors-(156-chars/"><u>Mastering Apex Servers on PC: 7 Ways to Fix 'No Server' Errors (<156 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windowsapps-access-a-step-by-step-guide/"><u>Mastering WindowsApps Access: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/must-use-3d-paint-shortcuts-compiled/"><u>Must-Use 3D Paint Shortcuts Compiled</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-the-nuances-of-windows-maintenance-and-update-scheduling/"><u>Navigate the Nuances of Windows Maintenance & Update Scheduling</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-transition-from-ical-to-windows-calendar/"><u>Navigating the Transition: From iCal to Windows Calendar</u></a></li>
<li><a href="https://windows11.techidaily.com/new-horizons-in-customizing-win11-ui/"><u>New Horizons in Customizing Win11 UI</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-generic-sound-not-recognized-issue-in-windows-system/"><u>Overcoming Generic Sound Not Recognized Issue in Windows System</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-hurdle-of-non-responding-email-alerts-on-pcs/"><u>Overcoming the Hurdle of Non-Responding Email Alerts on PCs</u></a></li>
<li><a href="https://facebook.techidaily.com/past-vs-present-a-reevaluation-of-the-impact-of-facebook-investigations/"><u>Past vs Present: A Reevaluation of The Impact of Facebook Investigations</u></a></li>
<li><a href="https://screen-recording.techidaily.com/pioneering-techniques-in-screen-snatching-for-2024/"><u>Pioneering Techniques in Screen Snatching for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaim-your-slack-notifications-fixes-for-windows-11/"><u>Reclaim Your Slack Notifications: Fixes for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/reduce-keyboard-latency-in-win-os-with-top-7-hacks/"><u>Reduce Keyboard Latency in Win OS with Top 7 Hacks</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-cannot-create-errors-for-files-in-windows/"><u>Remedying 'Cannot Create' Errors for Files in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-disabled-windows-shadow-copies/"><u>Resolving Disabled Windows Shadow Copies</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-error-code-0x80040610-in-depth-outlook-troubleshooting-guide/"><u>Resolving Windows Error Code 0X80040610: In-Depth Outlook Troubleshooting Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-keep-windows-notepad-running-without-interruptions/"><u>Strategies to Keep Windows Notepad Running without Interruptions</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-windows-searches-using-everythingapp/"><u>Streamline Windows Searches Using EverythingApp</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-creating-sequences-of-directories-simultaneously-in-windows/"><u>The Art of Creating Sequences of Directories Simultaneously in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-reviving-the-net-framework-on-pcs-max-156/"><u>The Art of Reviving the .NET Framework on PCs (Max 156)</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-hd-strategy-for-classics-gaming-on-windows-via-scummvm/"><u>The Ultimate HD Strategy for Classics Gaming on Windows via ScummVM</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-windows-folders-tricks-for-enhanced-efficiency/"><u>Top 5 Windows Folders Tricks for Enhanced Efficiency</u></a></li>
<li><a href="https://windows11.techidaily.com/transforming-ideas-into-art-the-best-drawing-apps-ranked-in-win10/"><u>Transforming Ideas Into Art: The Best Drawing Apps Ranked in Win10</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-insight-essential-steps-for-gauging-network-bandwidth/"><u>Windows Insight: Essential Steps for Gauging Network Bandwidth</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-integration-mastery-overcoming-add-on-installation-roadblocks/"><u>Windows Integration Mastery: Overcoming Add-On Installation Roadblocks</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-the-battle-against-installer-error-messages-on-pcs/"><u>Winning the Battle Against Installer Error Messages on PCs</u></a></li>
</ul></div>
