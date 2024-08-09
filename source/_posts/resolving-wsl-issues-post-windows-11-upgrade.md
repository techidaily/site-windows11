---
title: Resolving WSL Issues Post-Windows 11 Upgrade
date: 2024-08-08T06:14:32.282Z
updated: 2024-08-09T06:14:32.282Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving WSL Issues Post-Windows 11 Upgrade
excerpt: This Article Describes Resolving WSL Issues Post-Windows 11 Upgrade
keywords: Windows 11 WSL Troubleshoot,Fixing WSL After WinUpgrade,Windows 11 WSL Resolve Issues,Post-Win11 WSL Fix Guide,Upgraded OS,Address WSL Win11 Challenges,Overcoming Win11 WSL Glitches
thumbnail: https://thmb.techidaily.com/e591b5728fa84d66a3323b91b4ed2e3f5b0efaa53a757d0b8f7bbc674ee0d976.jpg
---

## Resolving WSL Issues Post-Windows 11 Upgrade

 There are several potential reasons why Windows Subsystem for Linux (WSL) stopped working after your PC was upgraded to Windows 11\. Thankfully, the breakdown is unlikely to be terminal, although you might have to try a few different fixes to get it working once again.

 **MUO VIDEO OF THE DAY**

 **SCROLL TO CONTINUE WITH CONTENT**

 Here are several ways to get the Windows Subsystem for Linux working again after upgrading to Windows 11.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Check That WSL Is Enabled

 It isn't unusual that upgrading to a newer version of the OS will break some apps and features. So although it might sound obvious, checking WSL hasn't simply been disabled during the upgrade process should be your first step. Here's how to check:

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![checking if WSL is enabled in Windows Features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-enabled.jpg)

1. In Windows Search, type**Turn Windows features on or off** and click the search result that should appear at the top.
2. In the Windows System dialog, scroll down until you see**Windows Subsystem for Linux** .
3. If the checkbox for the feature is not selected, do so now. Then click**Ok** .
4. You might also need to restart your computer before checking to see if that fixed the problem.

 Hopefully, WSL is now working, and you can begin using the tool. If not, read on for some other possible solutions.

 Learn more about the[things you can do with WSL and Linux](https://www.makeuseof.com/pros-cons-windows-subsystem-for-linux/) on your Windows computer.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. Enable Hyper-V and Virtual Machine Platform

 If you want to use a subsystem such as WSL in Windows, you'll also need to enable the virtualization tools. These include Hyper-V and the Virtual Machine Platform.

<!-- affiliate ads begin -->
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
![repairing an app in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl-app.jpg)

 Check if WSL is working. If not, try uninstalling and reinstalling the Linux distribution app.

## 4\. Force WSL to Open Using the Microsoft Store

 If WSL is enabled but still refuses to open, you can try forcing launch through the Microsoft Store app. This can sometimes fix temporary glitches when opening WSL directly doesn't work.

1. Open the Microsoft Store app and search for**WSL** .
2. On the store page for WSL, you should see an**Open** button. If the button says**Update** , click it to update the app.  
<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
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
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
## 6\. Check That Malware Isn't Blocking WSL

 The final thing to try to get WSL working is scanning for malware. The potential for malware to prevent Windows Subsystem for Linux from working is low but not unheard of.

 Run a[full scan in Microsoft Defender](https://www.makeuseof.com/easy-ways-boost-security-microsoft-defender-and-windows-10/) or whichever third-party antivirus software you use. Quarantine or remove any malware your antivirus scan finds. Then restart your computer and try using WSL to see if that was the issue.

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
<li><a href="https://extra-guidance.techidaily.com/new-premium-quality-transformer-for-video-enthusiasts/"><u>[New] Premium Quality Transformer for Video Enthusiasts</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-value-airborne-innovations-top-5-budget-drone-selections-for-2024/"><u>[New] Value Airborne Innovations  Top 5 Budget Drone Selections for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-hacks-for-preventing-youtube-short-failures/"><u>[Updated] 2024 Approved  Hacks for Preventing YouTube Short Failures</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-how-to-create-and-schedule-a-google-meet/"><u>[Updated] In 2024, How to Create and Schedule A Google Meet?</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-innovative-house-blueprints-for-snapshot-players/"><u>2024 Approved  Innovative House Blueprints for Snapshot Players</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-transforming-skype-sessions-with-proactive-zoom-tactics/"><u>2024 Approved  Transforming Skype Sessions with Proactive Zoom Tactics</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-misconfigured-duo-apps-on-windows/"><u>Addressing Misconfigured Duo Apps on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/beyond-boundaries-3-tools-that-elevate-pc-audio-above-100/"><u>Beyond Boundaries: 3 Tools That Elevate PC Audio Above 100%%</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/clearance-checking-guidelines-for-pre-upload-to-tiktok/"><u>Clearance-Checking Guidelines for Pre-Upload to TikTok</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-dismantling-the-win10-blue-screen/"><u>Decoding and Dismantling the Win10 Blue Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/detailed-exploration-retrieving-the-true-nature-of-device-ids-in-windows/"><u>Detailed Exploration: Retrieving the True Nature of Device IDs in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/digital-dot-delights-top-8-desktop-note-alternatives/"><u>Digital Dot Delights: Top 8 Desktop Note Alternatives</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-yuzu-emulation-speed-in-windows/"><u>Elevating Yuzu Emulation Speed in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-windows-1011-unsigned-update-errors/"><u>Eliminating Windows 10/11 'Unsigned' Update Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/empowering-your-system-bypass-tpm-and-secure-boot-via-rufus/"><u>Empowering Your System: Bypass TPM & Secure Boot via Rufus</u></a></li>
<li><a href="https://fox-glue.techidaily.com/enhance-your-tweet-game-with-top-video-converters-for-2024/"><u>Enhance Your Tweet Game with Top Video Converters for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-system-diagnostics-a-guide-to-windows-ping-usage/"><u>Enhancing System Diagnostics: A Guide to Windows Ping Usage</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-steps-to-prevent-and-resolve-onedrive-errors-on-your-pc/"><u>Essential Steps to Prevent and Resolve OneDrive Errors on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/executing-policies-for-a-single-user-target-in-modern-windows-systems/"><u>Executing Policies for a Single-User Target in Modern Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-cant-detect-camera-error-on-windows-11-pc/"><u>Fixing Can't Detect Camera Error on Windows 11 PC</u></a></li>
<li><a href="https://windows11.techidaily.com/get-a-free-glimpse-into-the-realm-of-ocm-football/"><u>Get a FREE Glimpse Into the Realm of OCM Football</u></a></li>
<li><a href="https://windows11.techidaily.com/getting-acquainted-with-the-windows-odbc-system/"><u>Getting Acquainted with the Windows ODBC System</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-silencing-game-recommendations-on-w11/"><u>Guide to Silencing Game Recommendations on W11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-alleviate-windows-1011s-devastating-discord-js-failure/"><u>How to Alleviate Windows 10/11'S Devastating Discord JS Failure</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-htc-u23-by-fonelab-android-recover-photos/"><u>How to recover deleted photos from HTC U23.</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-stop-snipping-tool-activation-from-pressing-prtscn-in-11/"><u>How to Stop Snipping Tool Activation From Pressing PrtScn in 11</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-maximum-mac-gif-recorder/"><u>In 2024, Maximum Mac Gif Recorder</u></a></li>
<li><a href="https://windows11.techidaily.com/master-your-computers-potential-a-wintoy-guidebook/"><u>Master Your Computer's Potential: A Wintoy Guidebook</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-memory-management-in-new-os/"><u>Mastering Memory Management in New OS</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-window-gloss-your-guide-to-a-clearer-taskbar-in-win11/"><u>Mastering Window Gloss: Your Guide to a Clearer Taskbar in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-and-protect-enabling-powershell-script-policy/"><u>Optimize & Protect: Enabling PowerShell Script Policy</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-your-drive-enable-file-cleanup-in-win11-operating-system/"><u>Optimize Your Drive: Enable File Cleanup in Win11 Operating System</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/optimizing-recording-quality-tips-and-tricks-for-ps3-gamers-for-2024/"><u>Optimizing Recording Quality  Tips and Tricks for PS3 Gamers for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-printer-in-use-issue-on-windows-11/"><u>Overcoming Printer In Use Issue on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolve-compromised-windows-defender-in-windows-11/"><u>Resolve Compromised Windows Defender in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-microsoft-store-programs-on-windows-1011-systems/"><u>Restoring Microsoft Store Programs on Windows 10/11 Systems</u></a></li>
<li><a href="https://technical-tips.techidaily.com/roku-device-face-off-express-edition-versus-original-stick/"><u>Roku Device Face-Off: Express Edition Versus Original Stick</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-correct-wsl-error-code-4294967295-in-windows/"><u>Steps to Correct WSL Error Code 4294967295 in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-methods-for-verifying-windows-11-installation/"><u>The Essential Methods for Verifying Windows 11 Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-using-wireless-and-cable-in-harmony-on-windows/"><u>The Ultimate Guide: Using Wireless and Cable in Harmony on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-undetectable-file-hiding-technique-on-windows-systems/"><u>The Undetectable File Hiding Technique on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/transforming-text-to-art-obsidian-canvas-techniques/"><u>Transforming Text to Art: Obsidian Canvas Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-chkdsk-vs-scan-disk-dissecting-windows-tools/"><u>Understanding Chkdsk Vs. Scan Disk: Dissecting Windows Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/unfreezing-and-reviving-windows-11s-stuck-media-player/"><u>Unfreezing and Reviving Windows 11'S Stuck Media Player</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-speed-and-efficiency-windows-shortcuts-for-uwp/"><u>Unleash Speed and Efficiency: Windows Shortcuts for UWP</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/unmask-phony-followers-a-speedy-cost-free-approach-for-instagram-for-2024/"><u>Unmask Phony Followers  A Speedy, Cost-Free Approach for Instagram for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-advanced-file-navigation-skills-steering-clear-of-ls/"><u>Unraveling Advanced File Navigation Skills: Steering Clear of LS</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-11-and-galaxy-ties-with-samsung-dex/"><u>Unveiling Windows 11 & Galaxy Ties with Samsung DeX</u></a></li>
<li><a href="https://windows11.techidaily.com/visual-notetaking-revolution-unlocking-with-obsidian-canvas/"><u>Visual Notetaking Revolution: Unlocking with Obsidian Canvas</u></a></li>
<li><a href="https://windows11.techidaily.com/what-purpose-does-a-directory-like-windows-bt-serve/"><u>What Purpose Does a Directory Like Windows ~BT Serve?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win7-printer-inactivity-post-sleep-fix-guide/"><u>Win7 Printer Inactivity Post-Sleep: Fix Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-photo-wizardry-made-easy-mastering-slideshow-creation-and-spot-repair/"><u>Windows 11'S Photo Wizardry Made Easy: Mastering Slideshow Creation & Spot Repair</u></a></li>
</ul></div>
