---
title: Ensuring Convergence of Windows & WSL with Win 11 Upgrade
date: 2024-08-15T16:01:02.675Z
updated: 2024-08-16T16:01:02.675Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Ensuring Convergence of Windows & WSL with Win 11 Upgrade
excerpt: This Article Describes Ensuring Convergence of Windows & WSL with Win 11 Upgrade
keywords: Windows-WSL Integration,Win 11 Upgrade Impact,Converging Operating Systems,Enhancing WSL Compatibility,Win11 & Linux Alignment,OS Update Strategies,Streamlining Windows-Linux
thumbnail: https://thmb.techidaily.com/8cc7746fe0672e4725ddd5d1492632738fafd136f8e04394f483f1432a572415.png
---

## Ensuring Convergence of Windows & WSL with Win 11 Upgrade

 There are several potential reasons why Windows Subsystem for Linux (WSL) stopped working after your PC was upgraded to Windows 11\. Thankfully, the breakdown is unlikely to be terminal, although you might have to try a few different fixes to get it working once again.

 **MUO VIDEO OF THE DAY**

 **SCROLL TO CONTINUE WITH CONTENT**

 Here are several ways to get the Windows Subsystem for Linux working again after upgrading to Windows 11.

## 1\. Check That WSL Is Enabled

 It isn't unusual that upgrading to a newer version of the OS will break some apps and features. So although it might sound obvious, checking WSL hasn't simply been disabled during the upgrade process should be your first step. Here's how to check:

![checking if WSL is enabled in Windows Features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-enabled.jpg)

1. In Windows Search, type**Turn Windows features on or off** and click the search result that should appear at the top.
2. In the Windows System dialog, scroll down until you see**Windows Subsystem for Linux** .
3. If the checkbox for the feature is not selected, do so now. Then click**Ok** .
4. You might also need to restart your computer before checking to see if that fixed the problem.

 Hopefully, WSL is now working, and you can begin using the tool. If not, read on for some other possible solutions.

 Learn more about the [things you can do with WSL and Linux](https://www.makeuseof.com/pros-cons-windows-subsystem-for-linux/) on your Windows computer.

<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
## 2\. Enable Hyper-V and Virtual Machine Platform

 If you want to use a subsystem such as WSL in Windows, you'll also need to enable the virtualization tools. These include Hyper-V and the Virtual Machine Platform.

![Error message in the command line interface](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-feature-missing.jpg)
<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If a command line interface opens, telling you a required feature is not installed, when you try to run your Linux distribution, this is likely what it refers to.

1. Search for**Turn Windows features on or off** and click the search result.
2. In Windows Features, scroll down to find**Virtual Machine Platform** and**Windows Hypervisor Platform** .
3. Check the boxes next to each of these features and then click**Ok** .
4. You will need to restart your computer to complete the installation of these tools.

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Repair the Linux Distribution App

 Your Linux distribution app, such as Ubuntu, Kali, or Debian, could be corrupted or require updating. This can cause WSL to appear to be broken. Repairing Windows apps is very easy.

1. Open**Settings > Apps > App & Features** .
2. Scroll down to the list of your apps to find your Linux distro app.
3. Click the**three dots** to the right of the app name, and select**Advanced options** .  
![Advanced app options in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Click the**Repair** button and follow the on-screen instructions if repairs are necessary.  
![repairing an app in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl-app.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->

 Check if WSL is working. If not, try uninstalling and reinstalling the Linux distribution app.

## 4\. Force WSL to Open Using the Microsoft Store

 If WSL is enabled but still refuses to open, you can try forcing launch through the Microsoft Store app. This can sometimes fix temporary glitches when opening WSL directly doesn't work.

1. Open the Microsoft Store app and search for**WSL** .
2. On the store page for WSL, you should see an**Open** button. If the button says**Update** , click it to update the app.  
![opening the WSL app in the Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/force-open-store.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
3. Click the**Open** button, and the default Linux distro app should launch.
4. If a command line interface window opens instead, it will probably tell you a required feature is missing. See**Enable Hyper-V and Virtual Machine Platform** above.

 If forcing WSL to open doesn't work, try the same with the Linux distro app you are using. Open the Store, search for your distro, and click the**Open** button.

## 5\. Uninstall Recent Updates to Fix WSL

 If WSL stopped working after installing an update, the update could be the cause. You can uninstall the most recent update to see if that fixes the problem.

[Uninstalling Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) isn't a complicated process, even if you have never done it before.

 If, after uninstalling the update, WSL still does not work, it is a good idea to reinstall it. Updates can often include security and performance tweaks, so it is generally recommended to keep Windows updated.

## 6\. Check That Malware Isn't Blocking WSL

 The final thing to try to get WSL working is scanning for malware. The potential for malware to prevent Windows Subsystem for Linux from working is low but not unheard of.

 Run a [full scan in Microsoft Defender](https://www.makeuseof.com/easy-ways-boost-security-microsoft-defender-and-windows-10/) or whichever third-party antivirus software you use. Quarantine or remove any malware your antivirus scan finds. Then restart your computer and try using WSL to see if that was the issue.

## Fixing WSL After Upgrading to Windows 11

 Upgrading to Windows 11 usually goes smoothly, but apps and features can occasionally break. If you find that WSL is no longer working after upgrading to the newest Windows OS, don't worry, there is usually an easy fix. You might only need to re-enable the feature in the Windows system settings, but if not, running through the other fixes here will usually solve the problem.


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
<li><a href="https://twitter-clips.techidaily.com/new-a-tweet-a-day-your-2023-video-journey-begins-here/"><u>[New] A Tweet a Day - Your 2023 Video Journey Begins Here</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-8-best-video-conferencing-software-for-small-business-safe-and-stable/"><u>[New] In 2024, 8 Best Video Conferencing Software for Small Business (Safe and Stable)</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-instantaneous-screen-logging-chromebooks/"><u>[New] In 2024, Instantaneous Screen Logging (Chromebooks)</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-the-essentials-2023s-highest-ranked-twitter-content/"><u>[New] In 2024, The Essentials  2023'S Highest-Ranked Twitter Content</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-premier-zombie-apocalypse-battles-ranking-top-titles/"><u>[New] Premier Zombie Apocalypse Battles  Ranking Top Titles</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-seamless-video-recording-on-facebook-with-top-5-tools/"><u>[New] Seamless Video Recording on Facebook with Top 5 Tools</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-the-music-law-guide-for-instagram-users/"><u>[New] The Music Law Guide for Instagram Users</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-how-to-gauge-if-an-mcn-is-right-for-your-youtube-journey/"><u>[Updated] 2024 Approved  How to Gauge if an MCN Is Right for Your YouTube Journey</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-beyond-headsets-ultimate-vr-gear-guide/"><u>[Updated] Beyond Headsets  Ultimate VR Gear Guide</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-revolutionize-your-teams-productivity-with-these-tools-for-2024/"><u>[Updated] Revolutionize Your Team's Productivity with These Tools for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-beyond-wirecast-a-guide-to-alternative-software/"><u>2024 Approved  Beyond WireCast  A Guide to Alternative Software</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-elevate-your-videos-with-these-proven-seo-tools-for-more-clicks/"><u>2024 Approved  Elevate Your Videos with These Proven SEO Tools for More Clicks</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-from-snapshots-to-delights-viral-eats-you-need-in-your-life/"><u>2024 Approved  From Snapshots to Delights  Viral Eats You Need in Your Life</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-in-depth-review-the-full-picture-of-facetunes-new-features/"><u>2024 Approved  In-Depth Review  The Full Picture of Facetune's New Features</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-maximizing-spotifys-playback-rate-without-sacrificing-sound/"><u>2024 Approved  Maximizing Spotify's Playback Rate Without Sacrificing Sound</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-navigate-a-sea-of-tiktok-saves-with-proper-editing-know-how/"><u>2024 Approved  Navigate a Sea of TikTok Saves with Proper Editing Know-How</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-uncharted-territories-discovering-hidden-vlc-capabilities/"><u>2024 Approved  Uncharted Territories  Discovering Hidden VLC Capabilities</u></a></li>
<li><a href="https://windows11.techidaily.com/5-methods-how-win11-harvests-personal-info/"><u>5 Methods: How Win11 Harvests Personal Info</u></a></li>
<li><a href="https://windows11.techidaily.com/a-closer-look-at-devhome-enhancing-windows-11-performance/"><u>A Closer Look at DevHome: Enhancing Windows 11 Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensive-walkthrough-for-clean-booting-windows-11/"><u>A Comprehensive Walkthrough for Clean Booting Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/a-history-of-the-windows-taskbar-from-1985-to-2023/"><u>A History of the Windows Taskbar From 1985 to 2023</u></a></li>
<li><a href="https://windows11.techidaily.com/ace-your-development-setup-with-top-wsl-2-tricks/"><u>Ace Your Development Setup with Top WSL 2 Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/adding-faithful-functions-to-windows-ui-tools/"><u>Adding Faithful Functions to Windows' UI Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-mcuicnt-file-execution-failure-on-windows/"><u>Addressing McUICnt File Execution Failure on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-1110-malwarebytes-functional-flaws/"><u>Addressing Windows 11/10 Malwarebytes Functional Flaws</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-cpu-utilization-checkers/"><u>Advanced CPU Utilization Checkers</u></a></li>
<li><a href="https://technical-tips.techidaily.com/an-insightful-overview-of-verizons-advancements-with-5g-technology/"><u>An Insightful Overview of Verizon's Advancements with 5G Technology</u></a></li>
<li><a href="https://windows11.techidaily.com/beat-the-burn-how-to-cool-down-your-gamers-windows-laptop/"><u>Beat The Burn: How to Cool Down Your Gamers’ Windows Laptop</u></a></li>
<li><a href="https://windows11.techidaily.com/blackview-minipc-expansive-but-sluggish-storage/"><u>Blackview MiniPC: Expansive but Sluggish Storage</u></a></li>
<li><a href="https://windows11.techidaily.com/break-the-cycle-of-a-non-opening-notepad-on-your-windows-device/"><u>Break the Cycle of a Non-Opening Notepad on Your Windows Device</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-through-disabled-script-barrier-4-key-techniques-to-load-ps-successfully/"><u>Breaking Through Disabled Script Barrier: 4 Key Techniques to Load PS Successfully</u></a></li>
<li><a href="https://windows11.techidaily.com/building-your-signature-input-scheme-on-win11/"><u>Building Your Signature Input Scheme on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-decades-old-password-request-on-modern-windows/"><u>Bypassing Decades-Old Password Request on Modern Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-the-add-folder-now-obstacle-in-windows-onedrive-for-a-smooth-experience/"><u>Bypassing the 'Add Folder Now' Obstacle in Windows OneDrive for a Smooth Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/classic-revival-atlasos-for-outdated-pcs/"><u>Classic Revival: AtlasOS for Outdated PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-old-wallpaper-a-simple-three-step-plan/"><u>Clearing Old Wallpaper - A Simple Three-Step Plan</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-the-confusing-blue-screen-error-0x8007007e/"><u>Clearing Up the Confusing Blue Screen Error: 0X8007007E</u></a></li>
<li><a href="https://windows11.techidaily.com/combat-unknown-obs-record-error-on-windows-11-pc/"><u>Combat Unknown OBS Record Error on Windows 11 PC</u></a></li>
<li><a href="https://driver-download.techidaily.com/comprehensive-razer-driver-downloads-and-updates-for-windows-users-across-multiple-versions/"><u>Comprehensive Razer Driver Downloads & Updates for Windows Users Across Multiple Versions</u></a></li>
<li><a href="https://windows11.techidaily.com/configure-your-systems-primary-terminal-application/"><u>Configure Your System’s Primary Terminal Application</u></a></li>
<li><a href="https://windows11.techidaily.com/confirm-if-your-system-is-a-win11-recipe/"><u>Confirm if Your System Is a Win11 Recipe</u></a></li>
<li><a href="https://windows11.techidaily.com/controlling-clock-display-in-windows-11-taskbar/"><u>Controlling Clock Display in Windows 11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/converting-heic-photos-to-jpeg-on-windows-1011/"><u>Converting HEIC Photos to JPEG on Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/cooling-down-your-windows-11-computer/"><u>Cooling Down Your Windows 11 Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-failed-uploads-with-onedrive-in-w11/"><u>Correcting Failed Uploads with OneDrive in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/corrective-actions-to-tackle-absence-of-windows-logins/"><u>Corrective Actions to Tackle Absence of Windows Logins</u></a></li>
<li><a href="https://windows11.techidaily.com/cracked-codekeepers-stay-secure-in-the-now/"><u>Cracked Codekeepers: Stay Secure in the Now</u></a></li>
<li><a href="https://windows11.techidaily.com/cross-language-build-system-setup/"><u>Cross-Language Build System Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/curing-windows-security-hiccups-in-win-11-system/"><u>Curing Windows Security Hiccups in Win 11 System</u></a></li>
<li><a href="https://windows11.techidaily.com/curtail-windows-system-acoustic-intensifiers/"><u>Curtail Windows System Acoustic Intensifiers</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-correcting-unspecified-obs-recording-glitches/"><u>Decoding and Correcting Unspecified OBS Recording Glitches</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-rectifying-the-pink-screen-dilemma/"><u>Decoding and Rectifying the Pink Screen Dilemma</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-ten-step-window-repair-journey/"><u>Decoding the Ten-Step Window Repair Journey</u></a></li>
<li><a href="https://windows11.techidaily.com/deletion-directive-for-drives-partitioned-areas-in-windows/"><u>Deletion Directive for Drives' Partitioned Areas in Windows</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-13-pro-max-to-other-iphone-11-pro-max-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 13 Pro Max to other iPhone 11 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-unlock-the-lock-screen-on-my-honor-x7b-by-drfone-android-unlock-android-unlock/"><u>How to Unlock the Lock Screen on my Honor X7b</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-watch-hulu-outside-us-on-poco-x6-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Watch Hulu Outside US On Poco X6 Pro | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-ultimate-zoom-tricks-for-chromebook-users/"><u>In 2024, Ultimate Zoom Tricks for Chromebook Users</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-unveiling-the-best-vr-applications-for-phones/"><u>In 2024, Unveiling the Best VR Applications for Phones</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/leveraging-metas-artificial-intelligence-for-enhanced-instagram-strategies/"><u>Leveraging Meta's Artificial Intelligence for Enhanced Instagram Strategies</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/loom-downloader-how-to-loom-screen-record-for-2024/"><u>Loom Downloader - How to Loom Screen Record for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/1719267835321-reactivating-silenced-pc-speakers-easy-fixes-ahead/"><u>Reactivating Silenced PC Speakers – Easy Fixes Ahead!</u></a></li>
<li><a href="https://windows11.techidaily.com/1719373142604-sidestep-common-snip-and-sketch-screenshot-hurdles-4-fixes/"><u>Sidestep Common Snip & Sketch Screenshot Hurdles: 4 Fixes.</u></a></li>
<li><a href="https://screen-recording.techidaily.com/splitcam-verdict-unrivaled-camera-quality-or-not-for-2024/"><u>SplitCam Verdict  Unrivaled Camera Quality or Not for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/spy-on-fb-chronicles-discreetly-for-2024/"><u>Spy on FB Chronicles Discreetly for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-11-free-apps-to-check-imei-on-oppo-a79-5g-phones-by-drfone-android/"><u>Top 11 Free Apps to Check IMEI on Oppo A79 5G Phones</u></a></li>
<li><a href="https://extra-tips.techidaily.com/top-picks-premium-iphone-tune-selectors/"><u>Top Picks  Premium iPhone Tune Selectors</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/transform-your-instagram-vocal-identity-today-for-2024/"><u>Transform Your Instagram Vocal Identity Today for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/trendsetters-on-twitternet-top-10-threads-ranking/"><u>Trendsetters on Twitternet  Top 10 Threads Ranking</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-data-from-infinix-hot-30-5g-by-fonelab-android-recover-data/"><u>Undelete lost data from Infinix Hot 30 5G</u></a></li>
<li><a href="https://games-able.techidaily.com/unlock-your-potential-essential-fps-configurations/"><u>Unlock Your Potential: Essential FPS Configurations</u></a></li>
<li><a href="https://windows11.techidaily.com/1719208597283-unravel-complex-windows-issues-help-at-hand/"><u>Unravel Complex Windows Issues: Help at Hand</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/wallet-friendly-cameras-2024-roundup/"><u>Wallet-Friendly Cameras: 2024 Roundup</u></a></li>
</ul></div>
