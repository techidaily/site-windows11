---
title: "6 Ways to Fix Minecraft's Exit Code: 1 on Windows"
date: 2024-08-15T15:13:35.996Z
updated: 2024-08-16T15:13:35.996Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes 6 Ways to Fix Minecraft's Exit Code: 1 on Windows"
excerpt: "This Article Describes 6 Ways to Fix Minecraft's Exit Code: 1 on Windows"
keywords: Minecraft Exit Code Fix,Win Fix 1 Error in MC,Solve MC Exit 1 Error,MC Win Error Resolution,Remedies for MC Exit 1,MC Windows Exit Troubleshoot,Bypassing MC Exit Fail
thumbnail: https://thmb.techidaily.com/0c878b30db98d758dc708e36a3a1a79c906ed9e88e0726b5c47115417927372d.jpg
---

## 6 Ways to Fix Minecraft's Exit Code: 1 on Windows

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
4. Next, click the**three-dots menu** beside the app name and select**Advanced Options** .  
![repair minecraft launcher windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/repair-minecraft-launcher-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Scroll down to the**Reset** section and click**Repair** . Windows will perform a quick repair and show a checkmark once the repair is complete.
6. Relaunch Minecraft Launcher and check for any improvements.

 Similarly, you can also repair your Minecraft game. Open Minecraft’s**Advanced Options** and perform a repair in the**Settings** app.

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

## 4\. Change the Java Executable Path

 Your Minecraft installation can run into issues if the launcher fails to detect the correct Java file. While Minecraft Launcher automatically installs the required JRE version, at times, you may need to manually change the executable to run the modified version of the game.

To change the Java executable for Minecraft:

1. Open the**Minecraft Launcher** .
2. Next, select the**Minecraft Java Edition** tab in the left pane.
3. Open the**Installations** tab in the toolbar.
4. Hover your mouse over**Latest Release** and click the**three-dots menu.**
5. Select**Edit** from the menu.  
![minecraft launcher latest release edit windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/minecraft-launcher-latest-release-edit-windows.jpg)

1. Click**More Options** to view additional options.
2. Click**Browse** to add a**Java Executable** .  
![java executable browse minecraft launcher windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/java-executable-browse-minecraft-launcher-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
3. Navigate to your Java installation. By default, the JRE file path is:  
`C:\Program Files (x86)\Java\jre1.8.0_361\bin`
4. Select the**Java.exe** file and click**Open** .  
![select JRE java executable browse minecraft launcher windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/select-jre-java-executable-browse-minecraft-launcher-windows.jpg)
5. Click**Save** to apply the changes and relaunch Minecraft Launcher.
6. The caveat here is you’ll need to update the Java version number or re-add the Java executable every time you update Java.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Reinstall Minecraft Without Deleting Saves

 You can reinstall Minecraft to fix issues with the game. Depending on how you installed the game, you can uninstall Minecraft from the Settings app or delete the .minecraft Appdata folder. If you prefer, you can also choose to keep your Minecraft saves.

To backup Minecraft saves and uninstall the game:

1. Press**Win + R** to open the**Run** dialog.
2. Paste the following in the**Run** field and click**OK** :  
`%appdata%\`
3. Open the**.minecraft** folder.  
![delete minecraft data folder uninstall windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/delete-minecraft-data-folder-uninstall-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
<!-- affiliate ads end -->
4. Right-click on the saves folder and select**Copy (Ctrl +C)** .
5. Paste the**saves** folder outside the**.minecraft** folder.  
![minecraft saves folder windows file explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/minecraft-savess-folder-windows-file-explorer.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600114&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Mac： Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
6. Next, return to the**Roaming** folder and delete the**.minecraft** folder to uninstall the game.
7. Restart your computer.
8. To reinstall Minecraft, open**Minecraft Launcher** . It will start the installation process.
9. Follow the on-screen instructions to complete the process and sign in with your Minecraft account.
10. Next, move the**saves** folder back to the following location:  
C:\Users\[Username]\AppData\Roaming\.minecraft
11. Relaunch Minecraft to check if the error is resolved.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Perform Generic Windows and Java Fixes

 If Minecraft is still plagued by the "exit code: 1" error, here are some more general fixes you can try.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Update the Graphics Drivers

 Incompatible or outdated graphics drivers can cause games on Windows computers to malfunction. For a dedicated GPU, you can use AMD Radeon Software or Nvidia GeForce Experience to [install the latest graphics drivers updates on Windows](https://www.makeuseof.com/update-graphics-drivers-in-windows-10/) .

 Intel users can download newer updates from the Windows update page. To do this, press Win + I to open Settings. Open Windows Updates and install any update available for your Intel graphics. Alternatively, check Intel’s website for newer display drivers for Windows.

### Reinstall Java

![java runtime environment install windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/java-runtine-environment-install-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->

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
<li><a href="https://fox-glue.techidaily.com/new-2024-approved-recommendation-best-websites-to-download-game-of-thrones-ringtones/"><u>[New] 2024 Approved  Recommendation  Best Websites to Download Game of Thrones Ringtones</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-best-of-the-best-photo-overlays-and-text-editors-review/"><u>[New] Best of the Best  Photo Overlays & Text Editors Review</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-mastering-media-subtitles-transformation/"><u>[New] Mastering Media Subtitles Transformation</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-how-to-harness-youtubes-creative-commons-in-video-making/"><u>[Updated] How to Harness YouTube's Creative Commons in Video Making</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/3-ways-for-android-pokemon-go-spoofing-on-motorola-edge-2023-drfone-by-drfone-virtual-android/"><u>3 Ways for Android Pokemon Go Spoofing On Motorola Edge 2023 | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-undelete-lost-call-logs-from-galaxy-m54-5g-by-fonelab-android-recover-call-logs/"><u>Best Android Data Recovery - undelete lost call logs from Galaxy M54 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-steps-for-recognizing-and-fixing-disabled-hard-drives-in-windows-11/"><u>Essential Steps for Recognizing and Fixing Disabled Hard Drives in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-for-windows-11-drive-connection/"><u>Essential Tips for Windows 11 Drive Connection</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-change-itel-p55plus-lock-screen-password-by-drfone-android/"><u>How To Change Itel P55+ Lock Screen Password?</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-immediately-stop-windows-iomap64-bsod/"><u>How To Immediately Stop Windows IOMap64 BSOD</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-turn-on-quick-startup-your-complete-windows-11-guidebook/"><u>How to Turn On Quick Startup: Your Complete Windows 11 Guidebook</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-finding-and-accessing-your-personalized-musical-selection-zone-on-youtube/"><u>In 2024, Finding and Accessing Your Personalized Musical Selection Zone on Youtube</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-startup-routine-creating-shortcuts-near-power-button-for-win11/"><u>Optimizing Startup Routine: Creating Shortcuts Near Power Button for Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-windows-performance-cutting-down-vanguards-cpu-use/"><u>Optimizing Windows Performance: Cutting Down Vanguard's CPU Use</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-soon-to-end-license-alert-in-winoses/"><u>Overcoming the Soon-to-End License Alert in WinOSes</u></a></li>
<li><a href="https://win-answers.techidaily.com/quick-fixes-for-overcoming-directx-problems-in-call-of-duty-mw2/"><u>Quick Fixes for Overcoming DirectX Problems in Call of Duty MW2</u></a></li>
<li><a href="https://windows11.techidaily.com/reactivate-windows-audio-despite-disabled-settings/"><u>Reactivate Windows Audio Despite Disabled Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-winrar-summation-errors-a-sixfold-approach/"><u>Rectifying WinRAR Summation Errors: A Sixfold Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/reversing-webp-formats-in-google-chrome-for-pc-folks/"><u>Reversing WebP Formats in Google Chrome, for PC Folks</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-your-gaming-experience-by-eliminating-e84-issues/"><u>Streamlining Your Gaming Experience by Eliminating E84 Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/swiftly-tackling-windows-application-issues-with-7-solutions/"><u>Swiftly Tackling Windows Application Issues with 7 Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/syncing-apples-calendars-to-your-windoze-1011-pc/"><u>Syncing Apple’s Calendars to Your Windoze 10/11 PC</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-guide-to-playing-ps1-on-windows-duckstation/"><u>The Essential Guide to Playing PS1 on Windows - Duckstation</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-10-telegram-spy-tools-on-oneplus-nord-3-5g-for-parents-drfone-by-drfone-virtual-android/"><u>Top 10 Telegram Spy Tools On OnePlus Nord 3 5G for Parents | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-connect-now-message-in-windows-bluetooth/"><u>Troubleshooting Connect Now Message in Windows Bluetooth</u></a></li>
<li><a href="https://windows11.techidaily.com/trusting-websites-in-windows-11-a-quick-guide/"><u>Trusting Websites in Windows 11: A Quick Guide</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/ultimate-guide-choosing-optimal-sony-playstation-4-webcam-positioning/"><u>Ultimate Guide: Choosing Optimal Sony PlayStation 4 Webcam Positioning</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-9-secrets-to-control-sound-settings-in-windows-11/"><u>Unlock the 9 Secrets to Control Sound Settings in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11s-swift-access-shortcuts/"><u>Unlocking Windows 11'S Swift Access Shortcuts</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-behind-windows-memory-snapshot/"><u>Unraveling the Mystery Behind Windows' Memory Snapshot</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-full-potential-of-windows-snip-and-sketch-capabilities/"><u>Unveiling the Full Potential of Windows' Snip and Sketch Capabilities.</u></a></li>
<li><a href="https://windows11.techidaily.com/virtual-readiness-confirm-your-webcammic-functionality-windows/"><u>Virtual Readiness: Confirm Your Webcam/Mic Functionality (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/w11-pro-discounts-await-secure-your-best-price/"><u>W11 Pro Discounts Await: Secure Your Best Price</u></a></li>
<li><a href="https://facebook.techidaily.com/who-holds-copyright-to-my-shared-snapshots/"><u>Who Holds Copyright to My Shared Snapshots</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-evolution-the-remarkable-journey-of-7-ancient-traits-into-11/"><u>Windows Evolution: The Remarkable Journey of 7 Ancient Traits Into 11</u></a></li>
</ul></div>
