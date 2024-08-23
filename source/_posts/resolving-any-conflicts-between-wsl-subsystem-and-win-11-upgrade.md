---
title: Resolving Any Conflicts Between WSL Subsystem and Win 11 Upgrade
date: 2024-08-22T21:35:40.544Z
updated: 2024-08-23T21:35:40.544Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving Any Conflicts Between WSL Subsystem and Win 11 Upgrade
excerpt: This Article Describes Resolving Any Conflicts Between WSL Subsystem and Win 11 Upgrade
keywords: WSL-UpgradeConflict,WSLWin11Compatibility,ResolveWSLUpgrade,Win11WSLSupport,FixWSLWindows11,UpgradeWSLSupport,HarmonizeWin11WSL
thumbnail: https://thmb.techidaily.com/0553b37a2d0bfe56c6f7794ae22609d4c46a2b30d090cb5ced8396683e115022.jpg
---

## Resolving Any Conflicts Between WSL Subsystem and Win 11 Upgrade

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

## 3\. Repair the Linux Distribution App

 Your Linux distribution app, such as Ubuntu, Kali, or Debian, could be corrupted or require updating. This can cause WSL to appear to be broken. Repairing Windows apps is very easy.

1. Open**Settings > Apps > App & Features** .
2. Scroll down to the list of your apps to find your Linux distro app.
3. Click the**three dots** to the right of the app name, and select**Advanced options** .  
![Advanced app options in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl.jpg)
4. Click the**Repair** button and follow the on-screen instructions if repairs are necessary.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
![repairing an app in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl-app.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
 Check if WSL is working. If not, try uninstalling and reinstalling the Linux distribution app.

<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. Force WSL to Open Using the Microsoft Store

 If WSL is enabled but still refuses to open, you can try forcing launch through the Microsoft Store app. This can sometimes fix temporary glitches when opening WSL directly doesn't work.

1. Open the Microsoft Store app and search for**WSL** .
2. On the store page for WSL, you should see an**Open** button. If the button says**Update** , click it to update the app.  
![opening the WSL app in the Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/force-open-store.jpg)
3. Click the**Open** button, and the default Linux distro app should launch.
4. If a command line interface window opens instead, it will probably tell you a required feature is missing. See**Enable Hyper-V and Virtual Machine Platform** above.

 If forcing WSL to open doesn't work, try the same with the Linux distro app you are using. Open the Store, search for your distro, and click the**Open** button.

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Uninstall Recent Updates to Fix WSL

 If WSL stopped working after installing an update, the update could be the cause. You can uninstall the most recent update to see if that fixes the problem.

[Uninstalling Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) isn't a complicated process, even if you have never done it before.

 If, after uninstalling the update, WSL still does not work, it is a good idea to reinstall it. Updates can often include security and performance tweaks, so it is generally recommended to keep Windows updated.

<!-- affiliate ads begin -->
<a href="https://martinic.evyy.net/c/5597632/1422856/4482" target="_top" id="1422856"><img src="//a.impactradius-go.com/display-ad/4482-1422856" border="0" alt="" width="580" height="309"/></a>
<!-- affiliate ads end -->
## 6\. Check That Malware Isn't Blocking WSL

 The final thing to try to get WSL working is scanning for malware. The potential for malware to prevent Windows Subsystem for Linux from working is low but not unheard of.

 Run a[full scan in Microsoft Defender](https://www.makeuseof.com/easy-ways-boost-security-microsoft-defender-and-windows-10/) or whichever third-party antivirus software you use. Quarantine or remove any malware your antivirus scan finds. Then restart your computer and try using WSL to see if that was the issue.

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
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
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-virtual-journeys-ultimate-listing-of-10-free-mmorpg-games/"><u>[New] 2024 Approved  Virtual Journey's  Ultimate Listing of 10 Free MMORPG Games</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-hidden-gems-premium-mac-speech-to-text-tools/"><u>[New] Hidden Gems  Premium Mac Speech-to-Text Tools</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-maximizing-engagement-in-online-collaboration-with-snap-camera/"><u>[New] In 2024, Maximizing Engagement in Online Collaboration with Snap Camera</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-top-ranked-zoonotic-patterns/"><u>[New] Top-Ranked Zoonotic Patterns</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-innovative-recording-solutions-top-8-sound-techniques/"><u>[Updated] 2024 Approved  Innovative Recording Solutions  Top 8 Sound Techniques</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-developers-guide-to-top-10-android-apps-for-facebook-video-downloading-for-2024/"><u>[Updated] Developer's Guide to Top 10 Android Apps for Facebook Video Downloading for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-gear-up-for-greatness-choosing-webcams-for-youtube-excellence/"><u>[Updated] In 2024, Gear Up for Greatness  Choosing Webcams for YouTube Excellence</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-innovative-hiring-the-10-most-engaging-vids/"><u>[Updated] Innovative Hiring  The 10 Most Engaging Vids</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-orchestrating-overtures-for-optimal-movie-teasers/"><u>[Updated] Orchestrating Overtures for Optimal Movie Teasers</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-visual-snips-tool/"><u>[Updated] Visual Snips Tool</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-discover-the-overlooked-insights-on-instagram-story-watching/"><u>2024 Approved  Discover the Overlooked  Insights on Instagram Story Watching</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-free-fix-swiftly-vanish-coffee-stains-from-your-iphone-pics/"><u>2024 Approved  Free Fix  Swiftly Vanish Coffee Stains From Your iPhone Pics</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-photos-files-on-spark-10-pro-by-fonelab-android-recover-photos/"><u>Complete guide for recovering photos files on Spark 10 Pro.</u></a></li>
<li><a href="https://win-blog.techidaily.com/discord-buffering-solutions-a-step-by-step-guide-for-optimal-performance/"><u>Discord Buffering Solutions: A Step-by-Step Guide for Optimal Performance</u></a></li>
<li><a href="https://driver-download.techidaily.com/easy-steps-to-get-usb-c-driver-compatible-with-windows-10/"><u>Easy Steps to Get USB-C Driver Compatible with Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-steps-for-resolving-printer-connections-in-windows/"><u>Essential Steps for Resolving Printer Connections in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/file-explorer-misses-out-on-sd-card-heres-fixing-it/"><u>File Explorer Misses Out on SD Card - Here's Fixing It</u></a></li>
<li><a href="https://windows11.techidaily.com/getting-started-with-the-windows-11-voice-chat/"><u>Getting Started with the Windows 11 Voice Chat</u></a></li>
<li><a href="https://change-location.techidaily.com/how-and-where-to-find-a-shiny-stone-pokemon-for-xiaomi-civi-3-drfone-by-drfone-virtual-android/"><u>How and Where to Find a Shiny Stone Pokémon For Xiaomi Civi 3? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-dodge-perpetual-network-logon-errors-in-windows/"><u>How to Dodge Perpetual Network Logon Errors in Windows</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-leave-a-life360-group-on-honor-x8b-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How To Leave a Life360 Group On Honor X8b Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-mute-games-recommended-by-windows-11/"><u>How To Mute Games Recommended by Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-overcome-invalid-session-from-vac-steam-alert/"><u>How To Overcome Invalid Session From VAC Steam Alert</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-play-an-mp4-on-motorola-moto-g24-by-aiseesoft-video-converter-play-mp4-on-android/"><u>How to play an MP4 on Motorola Moto G24?</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/how-to-use-io-screen-recorder/"><u>How to Use IO Screen Recorder</u></a></li>
<li><a href="https://windows11.techidaily.com/identifying-non-essential-windows-11-functions-to-turn-off/"><u>Identifying Non-Essential Windows 11 Functions to Turn Off</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-vivo-y200e-5g-phone-password-without-factory-reset-by-drfone-android/"><u>In 2024, How to Unlock Vivo Y200e 5G Phone Password Without Factory Reset?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/kodi-troubleshooting-mastery-overcoming-errors-and-enjoying-media-again/"><u>Kodi Troubleshooting Mastery: Overcoming Errors and Enjoying Media Again</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-the-benefits-of-windows-11s-auto-hdr/"><u>Leveraging the Benefits of Windows 11'S Auto HDR</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-use-of-microsoft-family-safety/"><u>Mastering the Use of Microsoft Family Safety</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-efficiency-set-predefined-app-sizes-in-win11/"><u>Maximizing Efficiency: Set Predefined App Sizes in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-resolve-it-admin-limited-warning/"><u>Methods to Resolve 'IT Admin Limited' Warning</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-cpu-performance-with-solutions-for-tiworkerexe-use/"><u>Optimize CPU Performance with Solutions for TiWorker.exe Use</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/1721433275299-protecting-your-mac-ignore-chatgpt-apps/"><u>Protecting Your Mac? Ignore ChatGPT Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/real-time-speech-conversion-using-whisper-desktop/"><u>Real-Time Speech Conversion: Using Whisper Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/reawakening-windows-hibernate-a-practical-guide/"><u>Reawakening Windows Hibernate: A Practical Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-sound-error-error-0xc00d36b4-in-win11/"><u>Rectifying Sound Error: Error 0XC00D36B4 in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/reducing-the-overwhelming-impact-of-ntoskrnlexe/"><u>Reducing the Overwhelming Impact of Ntoskrnl.exe</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstating-hidden-pane-windows-6-procedures-in-win11/"><u>Reinstating Hidden Pane Windows: 6 Procedures in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/repairing-filesystem-issues-with-ease-on-windows-11/"><u>Repairing Filesystem Issues with Ease on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-order-7-solutions-for-lost-windows-server-time/"><u>Restoring Order: 7 Solutions for Lost Windows Server Time</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-code-0x0001-issue-geforce-software-w11/"><u>Solving Code 0X0001 Issue: GeForce Software W11</u></a></li>
<li><a href="https://windows11.techidaily.com/steering-clear-of-windows-complications-during-amd-setup/"><u>Steering Clear of Windows Complications During AMD Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-address-security-glitches-in-windows-1011/"><u>Steps to Address Security Glitches in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/suppress-windows-extra-audio-functionality/"><u>Suppress Windows Extra Audio Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/surge-speed-settings-preventing-unexpected-download-plunges/"><u>Surge Speed Settings: Preventing Unexpected Download Plunges</u></a></li>
<li><a href="https://windows11.techidaily.com/tailor-your-own-lock-pattern-in-windows-11/"><u>Tailor Your Own Lock Pattern in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-disable-discord-auto-updates-at-bootup/"><u>Techniques to Disable Discord Auto-Updates at Bootup</u></a></li>
<li><a href="https://windows11.techidaily.com/the-easy-way-out-windows-11s-silencing-methods/"><u>The Easy Way Out: Windows 11'S Silencing Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/the-enigma-of-windows-11s-invisibles-menus-and-tools/"><u>The Enigma of Windows 11'S Invisibles Menus and Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-steps-to-open-windows-media-player/"><u>The Essential Steps to Open Windows Media Player</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/top-10-emulator-selections-for-mobile-gba-players-for-2024/"><u>Top 10 Emulator Selections for Mobile GBA Players for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-methods-for-resolving-windows-interface-dispute/"><u>Top 5 Methods for Resolving Windows Interface Dispute</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-common-errors-in-microsoft-office-windows/"><u>Troubleshooting Common Errors in Microsoft Office Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/what-makes-windows-11s-limited-functionality-beneficial/"><u>What Makes Windows 11’S Limited Functionality Beneficial?</u></a></li>
</ul></div>
