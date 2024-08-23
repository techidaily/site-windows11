---
title: Strategies for Uninstalling Win11's Official App
date: 2024-08-22T21:34:37.929Z
updated: 2024-08-23T21:34:37.929Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strategies for Uninstalling Win11's Official App
excerpt: This Article Describes Strategies for Uninstalling Win11's Official App
keywords: Win11 Uninstall Guide,Official Win11 Removal,Unofficial Win11 Delete,Win11 Remove Tips,Win11 Installation Stop,Eliminate Win11 App,Windows 11 Remover Tool
thumbnail: https://thmb.techidaily.com/0a18a6b406ce9f21eda937adac64825b459ee3a87d13a642256000f5335eb2cc.jpg
---

## Strategies for Uninstalling Win11's Official App

 Microsoft Store is the go-to place for Windows users if they want to install an app. The app library is slowly expanding, and you will find all the popular apps without any difficulty. But sometimes the Microsoft Store application behaves abnormally and requires troubleshooting.

 But what if it still doesn’t work, even after repairing and resetting? There is no uninstall option in the Settings app, so it is possible to uninstall Microsoft Store? Well, it is possible to remove and reinstall the Microsoft Store app. Here’s how.

## Why Should You Uninstall the Microsoft Store App?

 Microsoft Store houses all the useful and popular applications for Windows devices. Moreover, it guarantees safe and malware-free application downloads. But if the app fails to start or doesn’t work properly, removing it makes sense.

 But don’t worry. You can remove the app and then reinstall it if you want. Reinstallation can fix persistent issues with the current version of the Microsoft Store app. It will remove the current app installation and all its related files and corrupt data. After that, you can reinstall the Microsoft app with a single command.

## How to Uninstall Microsoft Store App From Windows 11

 You can remove the Microsoft Store app from Windows 11 using the winget tool and run it using the command prompt. In addition, you can use the PowerShell cmdlet to remove the Microsoft Store application package from your system or use a batch file.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->
### 1\. Using Winget

 Winget is a handy Windows package manager tool available with the newer releases of Windows 10 and 11\. It makes it ridiculously easy to search and manage applications on your system. You can use it to remove any application, even the Microsoft Store app from your system. Here’s how:

1. Press the**Win + R** key to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**cmd** and press the**Ctrl + Shift + Enter** keys to launch the Command Prompt with administrator privileges.
2. Now, we need to locate the ID of the Microsoft Store app installed on the system. Type the following command in the command prompt window and press the enter key:**Winget list Store**
3. Winget will list all the installed programs on your system containing the string “store” in their name. Find the Microsoft Store app in the list and**copy** its**ID** .
4. After that, you need to run the uninstall command using winget. The syntax is**winget uninstall \[app ID\]** . So, the command will be:  
winget uninstall Microsoft.WindowsStore_8wekyb3d8bb
5. Press enter to execute the command and wait for it to execute successfully.  
![Uninstall Microsoft Store App using winget](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-winget.jpg)
6. Type**exit** in the command prompt window and press enter to close it.
<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
### 2\. Using PowerShell

 Before winget was officially integrated into Windows 10 and 11, there was a method to[remove the Microsoft Store app using PowerShell](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) . The method still works and all you need to do is list the package name and then use the**Remove-AppxPackage** cmdlet to uninstall the Microsoft Store app from your system. Make sure to run PowerShell with elevated permissions.

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->
### 3\. Using a Batch File

 If you want to save the hassle of typing commands every time you want to uninstall the Microsoft Store app, you can use a batch file. It will help you to remove Microsoft Store app from your system in a couple of clicks whenever the normal troubleshooting methods don’t work for you. Repeat the following steps:

1. Press**Win + D** to switch to the Desktop. Right-click on the Desktop and select the**New > Text Document** option.
2. Open the newly created text document file on the desktop. A Notepad window will pop up. Paste the following text in it:  
@echo off winget uninstall "Microsoft Store" exit
3. Now, press**Ctrl + Shift + S** to open the "Save as" window. Name the batch file as**UninstallStore.bat** and keep the**Save as** type option as**All files** .  
![Uninstall Microsoft Store App using batch file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-batch-file.jpg)
4. Click on the**Save** button. Close the Notepad window.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
<!-- affiliate ads end -->
5. Press**Win + D** to switch to the desktop again. Right-click on the batch file and select the**Run as administrator** option from the context menu.
6. A command prompt window will open, run the Microsoft Store app uninstallation command, and close automatically. You don’t need to interact with the window.
7. Open the Start menu and search for Microsoft Store. You won’t find any matching app on your system.

<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Easily Remove the Microsoft Store From Windows

 Windows 10 and 11 don’t offer an option to uninstall Microsoft Store. So, you are only left at the mercy of a system restore or reset. However, you can now uninstall the Microsoft Store app from your system using any of the three methods mentioned above. You can also reinstall it using the PowerShell cmdlet and continue using the app again.


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
<li><a href="https://video-capture.techidaily.com/new-2024-approved-correcting-mute-issue-during-obs-recording/"><u>[New] 2024 Approved  Correcting Mute Issue During OBS Recording</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-lenovos-secrets-to-effortless-screenshots/"><u>[New] 2024 Approved  Lenovo's Secrets to Effortless Screenshots</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-enhancing-video-quality-callout-techniques-for-engaging-edits/"><u>[New] Enhancing Video Quality  Callout Techniques for Engaging Edits</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-how-to-make-a-mark-as-an-hdr-photography-pro-with-lightroom/"><u>[New] How to Make a Mark as an HDR Photography Pro with Lightroom</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-cutting-edge-gaming-setup-unpacking-samsungs-ue590-panel/"><u>[New] In 2024, Cutting Edge Gaming Setup  Unpacking Samsung's UE590 Panel</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-fixed-camera-resumes-with-obs/"><u>[New] In 2024, Fixed  Camera Resumes with OBS</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-recording-lenovo-fast-and-fuss-free-tips/"><u>[New] Recording Lenovo  Fast and Fuss-Free Tips</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-ultimate-tally-unveiling-the-highest-rated-threads-on-reddit/"><u>[New] The Ultimate Tally  Unveiling the Highest-Rated Threads on Reddit</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-unravel-the-secrets-to-successful-instagram-metrics-management-with-top-tools-for-2024/"><u>[New] Unravel the Secrets to Successful Instagram Metrics Management with Top Tools for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-curated-igtv-channels-that-matter-today-for-2024/"><u>[Updated] Curated IGTV Channels That Matter Today for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-digital-filmmaking-implementing-callout-lines-in-edits-for-2024/"><u>[Updated] Digital Filmmaking  Implementing Callout Lines in Edits for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-innovative-posting-add-youtube-to-your-insta-narratives/"><u>[Updated] Innovative Posting  Add YouTube to Your Insta Narratives</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-best-free-webm-players/"><u>2024 Approved  Best Free WebM Players</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-cutting-edge-converters-the-best-6-video-editing-tools-for-macos-big-sur/"><u>2024 Approved  Cutting-Edge Converters  The Best 6 Video Editing Tools for macOS Big Sur</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-decoding-zdsofts-key-recording-features/"><u>2024 Approved  Decoding ZDSoft's Key Recording Features</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/5-ways-to-reset-vivo-y36-without-volume-buttons-drfone-by-drfone-reset-android-reset-android/"><u>5 Ways to Reset Vivo Y36 Without Volume Buttons | Dr.fone</u></a></li>
<li><a href="https://fox-direct.techidaily.com/air-lift-extraordinaire-top-industrial-drones-for-2024/"><u>Air-Lift Extraordinaire  Top Industrial Drones for 2024</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/analyzing-netgears-powerline-adapter-does-its-bulky-design-impact-on-high-speed-performance/"><u>Analyzing Netgear's Powerline Adapter: Does Its Bulky Design Impact on High-Speed Performance?</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/apple-iphone-x-screen-mirroring-you-must-know-drfone-by-drfone-ios/"><u>Apple iPhone X Screen Mirroring You Must Know | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/can-i-bypass-a-forgotten-phone-password-of-oneplus-12r-by-drfone-android/"><u>Can I Bypass a Forgotten Phone Password Of OnePlus 12R?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-rectifying-problematic-fn-keys-on-an-asus-notebook-system/"><u>Diagnosing and Rectifying Problematic Fn Keys on an ASUS Notebook System</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-video-converter-software-for-pc-users/"><u>Essential Video Converter Software for PC Users</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-guide-to-device-tweaks-in-the-latest-windows-version/"><u>Expert Guide to Device Tweaks in the Latest Windows Version</u></a></li>
<li><a href="https://driver-error.techidaily.com/find-lost-seagate-disk-steps-for-windows-10/"><u>Find Lost Seagate Disk - Steps for Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-utorrent-connectivity-problems-on-pcs/"><u>Fixing uTorrent Connectivity Problems on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-voice-typing-malfunction-error-code-0x80049dd3-on-windows-11/"><u>Fixing Voice Typing Malfunction (Error Code: 0X80049DD3) on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/from-mobile-to-desktop-utilizing-smartphone-mic/"><u>From Mobile to Desktop: Utilizing Smartphone Mic</u></a></li>
<li><a href="https://windows11.techidaily.com/harness-the-power-of-windows-11-a-guide-to-7-effective-techniques/"><u>Harness the Power of Windows 11: A Guide to 7 Effective Techniques</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-vivo-y200-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Vivo Y200 Phones with/without a PC</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-do-honor-80-pro-straight-screen-edition-screen-sharing-drfone-by-drfone-android/"><u>How To Do Honor 80 Pro Straight Screen Edition Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-missing-tabs-in-windows-11-file-explorer/"><u>How to Fix Missing Tabs in Windows 11 File Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-iphone-image-import-something-went-wrong-error-in-windows-11-and-11/"><u>How to Fix the iPhone Image Import “Something Went Wrong” Error in Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-maintain-a-single-wallpaper-in-win11/"><u>How to Maintain a Single Wallpaper in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-overcome-windows-admin-policies-preventing-setup/"><u>How to Overcome Windows Admin Policies Preventing Setup</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-data-from-broken-iphone-15-screen-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Recover Data from Broken iPhone 15 Screen | Stellar</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-tackle-unavailable-previews-on-windows-outlook-email/"><u>How to Tackle Unavailable Previews on Windows Outlook Email</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-unlock-and-edit-files-on-win-pc/"><u>How to Unlock and Edit Files on Win PC</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/ideal-websites-for-painless-jpeg-to-gif-changeover-for-2024/"><u>Ideal Websites for Painless JPEG to GIF Changeover for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-can-i-use-a-fake-gps-without-mock-location-on-apple-iphone-xr-drfone-by-drfone-virtual-ios/"><u>In 2024, How Can I Use a Fake GPS Without Mock Location On Apple iPhone XR? | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-image-trimming-techniques-apples-ios-solutions/"><u>In 2024, Image Trimming Techniques  Apple's iOS Solutions</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/in-depth-analysis-and-reviews-of-the-gigabyte-ud750gm-high-wattage-power-supply/"><u>In-Depth Analysis & Reviews of the Gigabyte UD750GM High Wattage Power Supply</u></a></li>
<li><a href="https://windows11.techidaily.com/keep-your-pc-fresh-implementing-auto-file-cleanup-in-winos/"><u>Keep Your PC Fresh: Implementing Auto-File Cleanup in WINOS</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-guide-to-inspecting-windows-11-history/"><u>Mastery Guide to Inspecting Windows 11 History</u></a></li>
<li><a href="https://windows11.techidaily.com/minimizing-distractions-with-wins-management-on-win-11/"><u>Minimizing Distractions with Wins Management on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-past-windows-terminal-lockup/"><u>Navigating Past Windows Terminal Lockup</u></a></li>
<li><a href="https://windows11.techidaily.com/old-meets-new-a-windows-11-transformation-into-98-style/"><u>Old Meets New: A Windows 11 Transformation Into 98 Style</u></a></li>
<li><a href="https://windows11.techidaily.com/purge-your-pcs-defender-footprint-with-easy-steps/"><u>Purge Your PC’s Defender Footprint with Easy Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-loading-issues-on-discord-software/"><u>Quick Fixes for Loading Issues on Discord Software</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-linguistic-leap-translating-words-via-windows-1011-hotkeys/"><u>Quick Linguistic Leap: Translating Words via Windows 10/11 Hotkeys</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-tips-reactivate-your-calendar-and-mail-on-w11/"><u>Quick Tips: Reactivate Your Calendar & Mail on W11</u></a></li>
<li><a href="https://techidaily.com/repair-video-tool-repair-all-your-damaged-video-files-of-realme-11-5g-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>Repair Video Tool - Repair all your damaged video files of Realme 11 5G on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/reshaping-record-chronology-in-win8-with-7-tools/"><u>Reshaping Record Chronology in Win8 with 7 Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-attempted-token-access-error-on-windows-systems/"><u>Resolving Attempted Token Access Error on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-screen-glitches-stabilizing-display/"><u>Resolving Windows Screen Glitches: Stabilizing Display</u></a></li>
<li><a href="https://windows11.techidaily.com/saying-goodbye-to-apps-on-windows-11-a-compact-guide-98-chars/"><u>Saying Goodbye to Apps on Windows 11 - A Compact Guide (98 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-note-taking-tips-for-windows-11-users/"><u>Seamless Note-Taking Tips for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-social-connectivity-winning-at-fbm-glitches/"><u>Seamless Social Connectivity: Winning at FBM Glitches</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-windows-7-techniques-against-uac-intrusions/"><u>Securing Windows: 7 Techniques Against UAC Intrusions</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-up-your-windows-11-pc-as-an-invisible-network-hub/"><u>Setting Up Your Windows 11 PC as an Invisible Network Hub</u></a></li>
<li><a href="https://windows11.techidaily.com/signs-of-trouble-is-factory-reset-right-for-your-pc/"><u>Signs of Trouble: Is Factory Reset Right for Your PC</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/slidecasting-simplified-a-modern-webcam-approach/"><u>Slidecasting Simplified  A Modern, Webcam Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/speeding-up-epic-games-installation-windows-wise/"><u>Speeding Up Epic Games Installation Windows-Wise</u></a></li>
<li><a href="https://some-skills.techidaily.com/superior-cameras-for-clear-smooth-podcast-sessions-for-2024/"><u>Superior Cameras for Clear, Smooth Podcast Sessions for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-rectify-non-registered-hdds/"><u>Techniques to Rectify Non-Registered HDDs</u></a></li>
<li><a href="https://vp-tips.techidaily.com/the-enhancements-in-vegaspro-with-its-2019-release/"><u>The Enhancements in VegasPro with Its 2019 Release</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-speedy-way-to-keep-your-windows-n10-drivers-current-a-step-by-step-guide/"><u>The Speedy Way to Keep Your Windows N10 Drivers Current – A Step-by-Step Guide</u></a></li>
<li><a href="https://data-wizards.techidaily.com/tricks-to-improve-video-stream-stability-and-pace/"><u>Tricks to Improve Video Stream Stability and Pace</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-sound-delays-in-your-bluetooth-connections-on-new-windows-versions/"><u>Troubleshooting Sound Delays in Your Bluetooth Connections on New Windows Versions</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-spotify-link-failures-on-pcs-windows/"><u>Troubleshooting Spotify Link Failures on PCs (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/turn-onoff-text-emphasis-and-highlight-effects-on-pc/"><u>Turn On/Off Text Emphasis and Highlight Effects on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/turn-onoff-windows-key-like-a-pro/"><u>Turn On/Off Windows Key Like a Pro</u></a></li>
<li><a href="https://activate-lock.techidaily.com/ultimate-guide-from-apple-iphone-6-icloud-activation-lock-bypass-by-drfone-ios/"><u>Ultimate Guide from Apple iPhone 6 iCloud Activation Lock Bypass</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-faster-system-restoration-via-customized-troubleshooter-keys/"><u>Unleash Faster System Restoration via Customized Troubleshooter Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-copy-and-paste-features-with-application-guard-in-edge-w11-edition/"><u>Unlocking Copy & Paste Features with Application Guard in Edge, W11 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-mystery-behind-disabled-hard-drives-on-your-win-11-system/"><u>Unveiling the Mystery Behind Disabled Hard Drives on Your Win 11 System</u></a></li>
</ul></div>
