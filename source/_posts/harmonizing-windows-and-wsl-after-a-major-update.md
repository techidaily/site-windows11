---
title: Harmonizing Windows and WSL After a Major Update
date: 2024-08-08T06:02:46.607Z
updated: 2024-08-09T06:02:46.607Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Harmonizing Windows and WSL After a Major Update
excerpt: This Article Describes Harmonizing Windows and WSL After a Major Update
keywords: Windows+WSL Integration,WSL Post-Update Guide,Unifying Windows & WSL,Streamlined WSL Usage,Upgrading Windows + WSL,Major Update WSL Tips,Enhanced Windows+WSL Functionality
thumbnail: https://thmb.techidaily.com/3c096ca7006d9a28f3f7e555f29e64435eb73c0052911cf681dfac2286fbe4f4.jpg
---

## Harmonizing Windows and WSL After a Major Update

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

 Learn more about the[things you can do with WSL and Linux](https://www.makeuseof.com/pros-cons-windows-subsystem-for-linux/) on your Windows computer.

## 2\. Enable Hyper-V and Virtual Machine Platform

 If you want to use a subsystem such as WSL in Windows, you'll also need to enable the virtualization tools. These include Hyper-V and the Virtual Machine Platform.

![Error message in the command line interface](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-feature-missing.jpg)

 If a command line interface opens, telling you a required feature is not installed, when you try to run your Linux distribution, this is likely what it refers to.

1. Search for**Turn Windows features on or off** and click the search result.
2. In Windows Features, scroll down to find**Virtual Machine Platform** and**Windows Hypervisor Platform** .
3. Check the boxes next to each of these features and then click**Ok** .
4. You will need to restart your computer to complete the installation of these tools.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Repair the Linux Distribution App

 Your Linux distribution app, such as Ubuntu, Kali, or Debian, could be corrupted or require updating. This can cause WSL to appear to be broken. Repairing Windows apps is very easy.

1. Open**Settings > Apps > App & Features** .
2. Scroll down to the list of your apps to find your Linux distro app.
3. Click the**three dots** to the right of the app name, and select**Advanced options** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
![Advanced app options in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl.jpg)
4. Click the**Repair** button and follow the on-screen instructions if repairs are necessary.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->
![repairing an app in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl-app.jpg)

 Check if WSL is working. If not, try uninstalling and reinstalling the Linux distribution app.

## 4\. Force WSL to Open Using the Microsoft Store

 If WSL is enabled but still refuses to open, you can try forcing launch through the Microsoft Store app. This can sometimes fix temporary glitches when opening WSL directly doesn't work.

1. Open the Microsoft Store app and search for**WSL** .
2. On the store page for WSL, you should see an**Open** button. If the button says**Update** , click it to update the app.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![opening the WSL app in the Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/force-open-store.jpg)
3. Click the**Open** button, and the default Linux distro app should launch.
4. If a command line interface window opens instead, it will probably tell you a required feature is missing. See**Enable Hyper-V and Virtual Machine Platform** above.

 If forcing WSL to open doesn't work, try the same with the Linux distro app you are using. Open the Store, search for your distro, and click the**Open** button.

## 5\. Uninstall Recent Updates to Fix WSL

 If WSL stopped working after installing an update, the update could be the cause. You can uninstall the most recent update to see if that fixes the problem.

[Uninstalling Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) isn't a complicated process, even if you have never done it before.

 If, after uninstalling the update, WSL still does not work, it is a good idea to reinstall it. Updates can often include security and performance tweaks, so it is generally recommended to keep Windows updated.

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
## 6\. Check That Malware Isn't Blocking WSL

 The final thing to try to get WSL working is scanning for malware. The potential for malware to prevent Windows Subsystem for Linux from working is low but not unheard of.

 Run a[full scan in Microsoft Defender](https://www.makeuseof.com/easy-ways-boost-security-microsoft-defender-and-windows-10/) or whichever third-party antivirus software you use. Quarantine or remove any malware your antivirus scan finds. Then restart your computer and try using WSL to see if that was the issue.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-social-media-savvy-tips-and-tricks-for-captivating-storytelling/"><u>[New] 2024 Approved  Social Media Savvy  Tips and Tricks for Captivating Storytelling</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-ultimate-free-viewer-cam-parties/"><u>[New] 2024 Approved  Ultimate Free Viewer Cam Parties</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-evaluating-the-superiority-of-splitcams-recording-for-2024/"><u>[New] Evaluating the Superiority of SplitCam's Recording for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-bypassing-instagrams-video-roadblocks-effortlessly/"><u>[Updated] 2024 Approved  Bypassing Instagram's Video Roadblocks Effortlessly</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-editors-workshop-enhancing-your-youtube-video-visibility/"><u>[Updated] 2024 Approved  Editor's Workshop  Enhancing Your Youtube Video Visibility</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-explore-5-pro-game-record-methods-in-windows-11/"><u>[Updated] 2024 Approved  Explore 5 Pro Game Record Methods in Windows 11</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-audiovisual-elevation-leading-high-definition-hdmi-21-displays-for-2024/"><u>[Updated] Audiovisual Elevation  Leading High-Definition (HDMI 2.1) Displays for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-a-novices-roadmap-to-youtube-traffic-success/"><u>[Updated] In 2024, A Novice's Roadmap to YouTube Traffic Success</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-amazon-prime-viewers-who-to-follow-on-twitter-now/"><u>[Updated] In 2024, Amazon Prime Viewers - Who to Follow on Twitter, Now</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-maximizing-video-income-key-view-numbers-for-earning-on-youtube/"><u>[Updated] In 2024, Maximizing Video Income  Key View Numbers for Earning on YouTube</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-mastering-the-makeup-artistry-leading-youtubers-of-2024/"><u>[Updated] Mastering the Makeup Artistry  Leading YouTubers of 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-photo-story-platinum-best-photo-movie-story-maker-wondershare/"><u>[Updated] Photo Story Platinum - Best Photo Movie Story Maker | Wondershare</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-revamp-iphone-photos-effective-red-eye-removal-for-free/"><u>[Updated] Revamp iPhone Photos  Effective Red-Eye Removal for FREE</u></a></li>
<li><a href="https://windows11.techidaily.com/11-ways-to-open-the-credential-manager-on-windows-11/"><u>11 Ways to Open the Credential Manager on Windows 11</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-streamline-filming-in-water-proven-7-tips-for-vids/"><u>2024 Approved  Streamline Filming in Water  Proven 7 Tips for Vids</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-sunlit-scenes-android-brighten-tips/"><u>2024 Approved  Sunlit Scenes  Android Brighten Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/a-peek-at-your-gadgets-soul-6-methods-to-discover-its-make/"><u>A Peek at Your Gadget's Soul: 6 Methods to Discover Its Make</u></a></li>
<li><a href="https://windows11.techidaily.com/achieving-optimal-security-in-win-11-with-ms-defender-application-guard-for-edge/"><u>Achieving Optimal Security in Win 11 with MS Defender Application Guard for Edge</u></a></li>
<li><a href="https://windows11.techidaily.com/amp-up-your-vehicles-performance-with-these-top-windows-upgraders/"><u>Amp up Your Vehicle's Performance with These Top Windows Upgraders</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-data-disaster-save-and-recover-snippets/"><u>Avoiding Data Disaster: Save & Recover Snippets</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-t-view-mov-movies-content-on-samsung-galaxy-s23-fe-by-aiseesoft-video-converter-play-mov-on-android/"><u>Can’t view MOV movies content on Samsung Galaxy S23 FE</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-prints-with-microsoft-defender-smartscreen-edge/"><u>Configuring Prints with Microsoft Defender SmartScreen Edge</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-permission-restrictions-on-windows/"><u>Deciphering Permission Restrictions on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/disregard-met-not-fulfilled-emblem-on-win11/"><u>Disregard Met Not Fulfilled Emblem on Win11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/finding-the-best-free-subtitle-conversion-services/"><u>Finding the Best Free Subtitle Conversion Services</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-unable-to-open-shares-on-windows-1011s-geforce/"><u>Fixing Unable to Open Shares on Windows 10/11'S GeForce</u></a></li>
<li><a href="https://windows11.techidaily.com/from-standard-to-stylish-personalize-each-window-11-screen/"><u>From Standard to Stylish: Personalize Each Window 11 Screen</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/full-assessment-macs-screenflow-studio-experience-for-2024/"><u>Full Assessment  Mac's ScreenFlow Studio Experience for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-for-reestablishing-connection-with-steams-game-servers/"><u>Guidelines for Reestablishing Connection with Steam's Game Servers</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-frp-on-samsung-galaxy-s23-ultra-by-drfone-android/"><u>How to Bypass FRP on Samsung Galaxy S23 Ultra?</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-google-frp-lock-on-realme-12-5g-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock on Realme 12 5G Devices</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-unresponsive-touch-screen-on-motorola-edge-40-neo-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Touch Screen on Motorola Edge 40 Neo | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reactivate-muted-system-sound-output-quickly/"><u>How to Reactivate Muted System Sound Output Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-uninstall-oneself-avoiding-admin-restrictions-in-windows/"><u>How To Uninstall Oneself: Avoiding Admin Restrictions in WINDOWS</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-actions-for-windows-interface-crashing/"><u>Immediate Actions for Windows Interface Crashing</u></a></li>
<li><a href="https://windows11.techidaily.com/improve-sound-quality-top-5-free-windows-tools/"><u>Improve Sound Quality: Top 5 Free Windows Tools</u></a></li>
<li><a href="https://article-helps.techidaily.com/in-2024-adapting-to-diverse-candidate-personalities/"><u>In 2024, Adapting to Diverse Candidate Personalities</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-boosting-game-speed-optimizing-minecrafts-ram-usage/"><u>In 2024, Boosting Game Speed  Optimizing Minecraft's RAM Usage</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-fake-gps-location-spoofer-a-good-choice-on-xiaomi-civi-3-disney-100th-anniversary-edition-drfone-by-drfone-virtual-android/"><u>In 2024, Is Fake GPS Location Spoofer a Good Choice On Xiaomi Civi 3 Disney 100th Anniversary Edition? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-ispoofer-is-not-working-on-apple-iphone-6-fixed-drfone-by-drfone-virtual-ios/"><u>In 2024, iSpoofer is not working On Apple iPhone 6? Fixed | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-learn-selective-picture-clarity-reduction/"><u>In 2024, Learn Selective Picture Clarity Reduction</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-streamline-and-save-prime-tools-to-plug-into-fb-videos/"><u>In 2024, Streamline & Save  Prime Tools to Plug Into Fb Videos</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-tips-and-tricks-to-tell-if-your-apple-iphone-6s-is-unlocked-by-drfone-ios/"><u>In 2024, Tips And Tricks To Tell if Your Apple iPhone 6s Is Unlocked</u></a></li>
<li><a href="https://windows11.techidaily.com/launching-windows-file-explorer-directly-via-onedrive/"><u>Launching Windows File Explorer Directly via OneDrive</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-sluggishness-boosting-speed-of-steam-on-windows/"><u>Overcoming Sluggishness: Boosting Speed of Steam on Windows</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/preferred-choices-affordable-channels-for-newbie-monetizers-for-2024/"><u>Preferred Choices  Affordable Channels for Newbie Monetizers for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/purify-your-setup-tiny11s-no-fuss-features/"><u>Purify Your Setup: Tiny11's No-Fuss Features</u></a></li>
<li><a href="https://windows11.techidaily.com/securely-store-and-view-onedrive-data-locally/"><u>Securely Store and View OneDrive Data Locally</u></a></li>
<li><a href="https://windows11.techidaily.com/skyrocketing-vm-potential-in-windows-implement-these-top-strategies/"><u>Skyrocketing VM Potential in Windows - Implement These Top Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-lessening-high-cpu-demand-from-tiworkerexe-tasks/"><u>Strategies for Lessening High CPU Demand From TiWorker.exe Tasks</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-winmedia-error-resolution/"><u>Strategies for WinMedia Error Resolution</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-circumvent-no-more-files-alert/"><u>Strategies to Circumvent No More Files Alert</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-code-0xc0000142-on-windows-devices/"><u>Tackling Code 0XC0000142 on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-winscomrssvrdll-anomaly-during-boot-up/"><u>Tackling the Winscomrssvr.dll Anomaly During Boot-Up</u></a></li>
<li><a href="https://windows11.techidaily.com/the-blueprint-for-a-more-effective-and-reliable-windows-11/"><u>The Blueprint for a More Effective and Reliable Windows 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-insiders-guide-to-crafting-insta-tones/"><u>The Insider's Guide to Crafting Insta Tones</u></a></li>
<li><a href="https://windows11.techidaily.com/the-magic-behind-the-scenes-in-photo-app-delete/"><u>The Magic Behind the Scenes in Photo App Delete</u></a></li>
<li><a href="https://windows11.techidaily.com/top-essential-gratis-tools-for-windows-11-enthusiasts/"><u>Top Essential Gratis Tools for Windows 11 Enthusiasts</u></a></li>
<li><a href="https://windows11.techidaily.com/top-windows-techniques-for-enjoying-high-definition-adventures-with-scummvm/"><u>Top Windows Techniques for Enjoying High-Definition Adventures with ScummVM</u></a></li>
<li><a href="https://windows11.techidaily.com/uncovering-digital-shadows-sid-extraction-in-win11/"><u>Uncovering Digital Shadows: SID Extraction in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11-safe-mode-an-easy-six-step-plan/"><u>Unlocking Windows 11 Safe Mode: An Easy Six-Step Plan</u></a></li>
<li><a href="https://windows11.techidaily.com/unwrapping-the-mystery-of-monitor-miscalibration/"><u>Unwrapping the Mystery of Monitor Miscalibration</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/weaving-a-web-of-sound-youtube-music-and-video-integration-guide/"><u>Weaving a Web of Sound  YouTube Music & Video Integration Guide</u></a></li>
<li><a href="https://fox-that.techidaily.com/why-wont-my-iphone-screen-power-down-resolve-the-issue-now/"><u>Why Won't My iPhone Screen Power Down? Resolve the Issue Now</u></a></li>
<li><a href="https://windows11.techidaily.com/win11s-unnecessary-filler-heres-how-to-tackle-it/"><u>Win11's Unnecessary Filler? Here’s How To Tackle It</u></a></li>
<li><a href="https://windows11.techidaily.com/window-watchers-sticky-pad-software-reviews-8-picks/"><u>Window Watchers: Sticky Pad Software Reviews (8 Picks)</u></a></li>
<li><a href="https://extra-information.techidaily.com/year-in-review-top-5-camera-tips-filmmakers/"><u>Year in Review  Top 5 Camera Tips Filmmakers</u></a></li>
</ul></div>
