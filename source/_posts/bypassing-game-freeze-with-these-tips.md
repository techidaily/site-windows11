---
title: Bypassing Game Freeze with These Tips
date: 2024-08-15T15:18:10.969Z
updated: 2024-08-16T15:18:10.969Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Bypassing Game Freeze with These Tips
excerpt: This Article Describes Bypassing Game Freeze with These Tips
keywords: Bypass Game Frost,Avoid Gaming Halt,Tricks to Prevent Pause,Stop In-Game Stoppage,Fix Freezing Games,Unfreeze Video Games,Quick Fix Gaming Pause
thumbnail: https://thmb.techidaily.com/a26060fad92020f54b317e5747fec75ccfe05e7c2700d5cb66b41afce88bdb6e.jpg
---

## Bypassing Game Freeze with These Tips

 When Minecraft fails to launch correctly, it will sometimes crash with the "exit code: 1" error. While the error message indicates issues with Java runtime configuration, there can also be other reasons. An outdated graphics driver, incorrect in-game settings, incompatible mods, buggy game files, and an invalid launcher file path can also trigger the "exit code:1" error on Windows.

 Here we show you a few quick troubleshooting steps to fix the "exit code: 1" and get back to playing Minecraft on your Windows computer.

## 1\. Delete or Disable Outdated Mods

 The "exit code: 1" error can occur due to outdated mods. To resolve the error, check the Minecraft mods folder and delete it. Removing mods can break your worlds. So make sure to create a backup before attempting to remove any mods. Here’s how to do it.

1. Press**Win + R** and type the following in the**Run** dialog:  
`%appdata%\`
2. Click**OK** to open the**AppData\\Roaming** folder in**File Explorer** .  
![appdata run dialog windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/appdata-run-dialog-windows-11.jpg)
3. Next, open the**.minecraft** folder.  
![minecraft mods folder windows file explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/minecraft-mods-folder-windows-file-explorer.jpg)
4. Open the**mods** folder inside the**.minecraft** folder.
5. Select and right-click on all the**mods** one by one and select**Delete** .

 Once all the mods are removed, close File Explorer and relaunch Minecraft to see if the error is resolved. On the flip side, you may find some Minecraft levels (worlds) broken upon launch. You may also want to re-download mods to make further modifications.

## 2\. Repair Minecraft Launcher

 You can fix common problems with the Minecraft Launcher using the [built-in repair option on Windows](https://www.makeuseof.com/windows-repair-apps-programs/) . During repair, Windows will look for common issues and try to fix them automatically. It will also delete the app’s data.

To repair Minecraft Launcher:

1. Press**Win + I** to open**Windows** .
2. Open the**Apps** tab in the left pane.
3. Click on**Installed Apps** and search**Minecraft Launcher** .  
![minecrafft launcher advanced options windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/minecrafft-launcher-advanced-options-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Next, click the**three-dots menu** beside the app name and select**Advanced Options** .  
![repair minecraft launcher windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/repair-minecraft-launcher-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
5. Scroll down to the**Reset** section and click**Repair** . Windows will perform a quick repair and show a checkmark once the repair is complete.
6. Relaunch Minecraft Launcher and check for any improvements.

 Similarly, you can also repair your Minecraft game. Open Minecraft’s**Advanced Options** and perform a repair in the**Settings** app.

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Modify the Minecraft Launcher File Path

![modify minecraft launcher file path working directory](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/modify-minecraft-launcher-file-path-working-directory.jpg)

 Issues with the Minecraft Launcher file path can cause the "exit code: 1" on Windows. If your user name has a special character, the Minecraft Launcher file path may not respond to a user account with a special character.

 To fix the issue, you’ll need to modify the Minecraft Launcher file path to allow the launcher to access the launcher without special characters.

To change the Minecraft Launcher file path:

1. Right-click on the**Minecraft Launcher** shortcut and select**Properties** .
2. In the**Properties** dialog, open the Shortcut pat.
3. In the**Target** field, add the following line to change the working directory for Minecraft Launcher. You need to add the below lines after the existing file path:  
`&ndash;workDir %ProgramData%.minecraft`
4. After modifications, the target field will look something like this:  
`"C:\Program Files (x86)\Minecraft Launcher\MinecraftLauncher.exe" &ndash;workDir %ProgramData%.minecraft`
5. Click**Apply** and**OK** to save the changes.
6. Relaunch Minecraft and check for any improvements.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. Change the Java Executable Path

 Your Minecraft installation can run into issues if the launcher fails to detect the correct Java file. While Minecraft Launcher automatically installs the required JRE version, at times, you may need to manually change the executable to run the modified version of the game.

To change the Java executable for Minecraft:

1. Open the**Minecraft Launcher** .
2. Next, select the**Minecraft Java Edition** tab in the left pane.
3. Open the**Installations** tab in the toolbar.
4. Hover your mouse over**Latest Release** and click the**three-dots menu.**
5. Select**Edit** from the menu.  
![minecraft launcher latest release edit windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/minecraft-launcher-latest-release-edit-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35408920&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/FR-200-1.png" border="0">Glarysoft File Recovery Pro - Helps to recover your lost file/data, even permanently deleted data. </a>
<!-- affiliate ads end -->

1. Click**More Options** to view additional options.
2. Click**Browse** to add a**Java Executable** .  
![java executable browse minecraft launcher windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/java-executable-browse-minecraft-launcher-windows.jpg)
3. Navigate to your Java installation. By default, the JRE file path is:  
`C:\Program Files (x86)\Java\jre1.8.0_361\bin`
4. Select the**Java.exe** file and click**Open** .  
![select JRE java executable browse minecraft launcher windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/select-jre-java-executable-browse-minecraft-launcher-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633309&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/3_premium-icon.png" border="0"> Take advantage of PREMIUM features for 12 months. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Yearly Membership</a>
<!-- affiliate ads end -->
5. Click**Save** to apply the changes and relaunch Minecraft Launcher.
6. The caveat here is you’ll need to update the Java version number or re-add the Java executable every time you update Java.

## 5\. Reinstall Minecraft Without Deleting Saves

 You can reinstall Minecraft to fix issues with the game. Depending on how you installed the game, you can uninstall Minecraft from the Settings app or delete the .minecraft Appdata folder. If you prefer, you can also choose to keep your Minecraft saves.

To backup Minecraft saves and uninstall the game:

1. Press**Win + R** to open the**Run** dialog.
2. Paste the following in the**Run** field and click**OK** :  
`%appdata%\`
3. Open the**.minecraft** folder.  
![delete minecraft data folder uninstall windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/delete-minecraft-data-folder-uninstall-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
4. Right-click on the saves folder and select**Copy (Ctrl +C)** .
5. Paste the**saves** folder outside the**.minecraft** folder.  
![minecraft saves folder windows file explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/minecraft-savess-folder-windows-file-explorer.jpg)
<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Next, return to the**Roaming** folder and delete the**.minecraft** folder to uninstall the game.
7. Restart your computer.
8. To reinstall Minecraft, open**Minecraft Launcher** . It will start the installation process.
9. Follow the on-screen instructions to complete the process and sign in with your Minecraft account.
10. Next, move the**saves** folder back to the following location:  
C:\Users\[Username]\AppData\Roaming\.minecraft
11. Relaunch Minecraft to check if the error is resolved.

## 6\. Perform Generic Windows and Java Fixes

 If Minecraft is still plagued by the "exit code: 1" error, here are some more general fixes you can try.

### Update the Graphics Drivers

 Incompatible or outdated graphics drivers can cause games on Windows computers to malfunction. For a dedicated GPU, you can use AMD Radeon Software or Nvidia GeForce Experience to [install the latest graphics drivers updates on Windows](https://www.makeuseof.com/update-graphics-drivers-in-windows-10/) .

 Intel users can download newer updates from the Windows update page. To do this, press Win + I to open Settings. Open Windows Updates and install any update available for your Intel graphics. Alternatively, check Intel’s website for newer display drivers for Windows.

### Reinstall Java

![java runtime environment install windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/java-runtine-environment-install-windows.jpg)

 The "exit code: 1" error often hints at invalid Java runtime configuration issues. You can reinstall Java to fix configuration issues fixed in the latest release.

To reinstall Java Runtime Environment:

1. Go to the [Java download page](https://www.java.com/en/download/manual.jsp) .
2. Select the correct version for your Windows computer. You can opt for the Windows Online or Offline version. Also, download the 64-bit version if applicable.
3. Run the installer and follow the on-screen instructions to complete installations.
4. Once installed, restart your computer and check for any improvements.

## Fixing the Minecraft Exit Code: 1 Error

 Many things can go wrong and trigger the "exit Code: 1 error" in Minecraft. To resolve the issue, try to disable mods and change the Minecraft Launcher path. If the issue persists, check your graphics driver for the problem.

 If all else fails, perform a reinstall. You can reinstall Minecraft while keeping saves. If you are using the latest Microsoft Store version of the game, you can also uninstall it from the settings app.


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
<li><a href="https://instagram-video-recordings.techidaily.com/new-expand-your-igtv-reach-the-top-5-methods-to-attract-more-viewers-for-2024/"><u>[New] Expand Your IGTV Reach  The Top 5 Methods to Attract More Viewers for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-concealed-visibility-mastering-visual-obscurity-in-videos/"><u>[New] In 2024, Concealed Visibility  Mastering Visual Obscurity in Videos</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-masterful-makeovers-picarts-backdrop-banishment-guide/"><u>[New] Masterful Makeovers  PicArt’s Backdrop Banishment Guide</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-sky-storage-spectacle-unlimited-free-and-elite-premium-alternatives-for-your-pics/"><u>[New] Sky Storage Spectacle  Unlimited Free & Elite Premium Alternatives for Your Pics</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-stepwise-approach-to-resolve-facebook-story-errors/"><u>[Updated] In 2024, Stepwise Approach to Resolve Facebook Story Errors</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-inside-the-revamped-sony-bdp-s6700-for-2024/"><u>[Updated] Inside the Revamped Sony BDP-S6700 for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-master-obs-on-macos-download-setup-and-get-to-work/"><u>[Updated] Master OBS on macOS  Download, Setup & Get to Work</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-sculpting-textures-creating-realistic-3d-effects-in-illustrator-for-2024/"><u>[Updated] Sculpting Textures  Creating Realistic 3D Effects in Illustrator for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-the-ultimate-skype-recorder-guide-for-2024/"><u>[Updated] The Ultimate Skype Recorder Guide for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-oneplus-11r-by-drfone-android/"><u>10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On OnePlus 11R</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerated-cross-language-compreinasion-via-windows-keyboard-tricks/"><u>Accelerated Cross-Language Compreinasion via Windows Keyboard Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/accurate-assessment-of-system-resources-in-windows-11/"><u>Accurate Assessment of System Resources in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/adeptly-disguise-wireless-networks-with-windows/"><u>Adeptly Disguise Wireless Networks with Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/black-friday-extravaganza-save-big-612-forever-win10/"><u>Black Friday Extravaganza: Save Big - $6.12 Forever Win10</u></a></li>
<li><a href="https://howto.techidaily.com/cellular-network-not-available-for-voice-calls-on-oppo-a58-4g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Cellular Network Not Available for Voice Calls On Oppo A58 4G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/digital-drawings-redefined-top-7-windows-10-art-tools-for-you/"><u>Digital Drawings Redefined: Top 7 Windows 10 Art Tools for You</u></a></li>
<li><a href="https://windows11.techidaily.com/dodging-unsupported-issue-in-windows-5-fixes/"><u>Dodging 'Unsupported' Issue in Windows: 5 Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-desktop-experience-fixing-this-pc-spotlight/"><u>Elevate Desktop Experience: Fixing 'This PC' Spotlight</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-pubg-save-problems-on-windows-systems/"><u>Eliminating PUBG Save Problems on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/expedite-photo-corrections-ps-and-windows-strategy/"><u>Expedite Photo Corrections: PS & Windows Strategy</u></a></li>
<li><a href="https://windows11.techidaily.com/flawless-system-transition-mastering-windows-11s-in-place-update-process/"><u>Flawless System Transition: Mastering Windows 11'S In-Place Update Process</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/full-guide-to-unlock-iphone-6-with-itunes-drfone-by-drfone-ios/"><u>Full Guide to Unlock iPhone 6 with iTunes | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-change-the-windows-subsystem-for-androids-resource-usage/"><u>How to Change the Windows Subsystem for Android's Resource Usage</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-5-ways-to-track-lava-blaze-pro-5g-without-app-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Ways to Track Lava Blaze Pro 5G without App | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-a-comprehensive-guide-to-icloud-unlock-on-apple-iphone-12-pro-online-by-drfone-ios/"><u>In 2024, A Comprehensive Guide to iCloud Unlock On Apple iPhone 12 Pro Online</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-cutting-edge-tactics-for-flawless-iphones-and-podcast-downloads/"><u>In 2024, Cutting-Edge Tactics for Flawless iPhones and Podcast Downloads</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-window-icon-positions/"><u>Mastery Over Window Icon Positions</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/maximize-your-impact-top-10-insta-tools-for-post-management-for-2024/"><u>Maximize Your Impact  Top 10 Insta Tools for Post Management for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/perfected-beats-on-the-go-no-cost-just-download-and-play-for-2024/"><u>Perfected Beats on the Go - No Cost, Just Download and Play for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/reactivating-inputs-post-sleep-on-latest-windows/"><u>Reactivating Inputs Post-Sleep on Latest Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-solutions-to-resolve-instant-failure-in-adding-a-folder-in-onedrive/"><u>Swift Solutions to Resolve Instant Failure in Adding a Folder in OneDrive</u></a></li>
<li><a href="https://windows11.techidaily.com/time-tinkering-tools-top-windows-programs-for-date-adjustment/"><u>Time Tinkering Tools: Top Windows Programs for Date Adjustment</u></a></li>
<li><a href="https://tech-haven.techidaily.com/transform-how-you-search-bings-ai-ready-for-mobile-devices/"><u>Transform How You Search: Bing’s AI Ready for Mobile Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-memory-integrity-on-windows-11-methods-77/"><u>Unlocking Memory Integrity on Windows 11: Methods 7/7</u></a></li>
<li><a href="https://windows11.techidaily.com/why-sudo-is-revolutionizing-windows-systems/"><u>Why Sudo Is Revolutionizing Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-cleanup-stripping-out-microsoft-store/"><u>Win11 Cleanup: Stripping Out Microsoft Store</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-troubleshooting-silent-voice-calls-in-valorant/"><u>Windows Troubleshooting: Silent Voice Calls in Valorant</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-wifi-wisdom-accelerating-network-speed-assessment/"><u>Windows WiFi Wisdom: Accelerating Network Speed Assessment</u></a></li>
</ul></div>
