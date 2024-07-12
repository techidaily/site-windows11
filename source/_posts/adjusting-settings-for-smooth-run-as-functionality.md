---
title: Adjusting Settings for Smooth 'Run As' Functionality
date: 2024-07-11T22:10:57.193Z
updated: 2024-07-12T22:10:57.193Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting Settings for Smooth 'Run As' Functionality
excerpt: This Article Describes Adjusting Settings for Smooth 'Run As' Functionality
keywords: Run As Adjustments,Smooth Run Guide,Setting Optimization,Run Functionality Tweaks,Adjust Settings Tutorial,Enhance 'Run' Performance,Streamline Run Feature
thumbnail: https://thmb.techidaily.com/a4a765e99a54a380752423d8d88b32966a3339aa9293b1bce2b9a95dc690dd25.jpg
---

## Adjusting Settings for Smooth 'Run As' Functionality

 Windows offers a Run as administrator option that allows users to run applications and programs with administrator privileges. You can also use it to troubleshoot computer issues. But what if this feature malfunctions, depriving you of administrator rights?

 That’s where this guide comes into play. So, let’s look at what you can do to fix Run as administrator not working on Windows.

## What Causes Run as Administrator Not Working?

 Before you start fixing things, you must understand what causes this issue. In general, you may experience Run as administrator not working due to the following reasons:

* Group Policy or User Account Control (UAC) blocks the application or program you’re trying to run.
* The user account associated with your device isn’t an administrator account and therefore doesn’t have the necessary privileges.
* Corrupt system files or registry entries could prevent you from running administrator programs.
* Malware infection on your computer could disrupt the feature.

 Now that you know the potential causes of this issue, let’s look at ways to fix it. ​​​

## 1\. Restart Your Computer

 If you’re having trouble running applications with administrative privileges, [restarting your computer](https://www.makeuseof.com/windows-restart-methods/) will likely solve the issue. This simple solution flushes out any temporary issues and puts the system in its default state.

## 2\. Check Your Account Type

 Not all user accounts are equal. To run programs with administrative privileges, you must have an administrator account. So, [head to the Control Panel](https://www.makeuseof.com/windows-open-control-panel/) and [check your account type](https://www.makeuseof.com/check-windows-account-admin-rights/). If it’s not labeled as an administrator account, switch to a different one or create a new account.

## 3\. Check User Account Control Settings

 The Windows User Account Control (UAC) prevents malicious programs from installing on your computer. This security feature can stop you from using elevated privileges.

 To ensure the issue isn’t related to UAC, head to the Control Panel and check your User Account Settings. If it is set to the highest level, bring it down to the default. Here's how to do it:

1. Press **Win + S** simultaneously to open the search box.
2. Type **Control Panel** in the search box and press Enter. This will open the Control Panel window.
3. View items by **Large icons** in the Control Panel and click on **User Accounts**.
4. In the right pane, click on **Change User Account Control settings**. Doing this will open the User Account Control Settings window.
5. Here you’ll see a slider with four options: **Always notify**, **Default**, **Notify me only when applications try to make changes to my computer**, and **Never notify**.  
![User Account Control Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/user-account-control-settings.jpg)
6. Drag the slider to **Default**, then click **OK**. It will set your UAC to the default level and enable you to run applications with elevated privileges.

 Now, close the window and restart your PC. After that, try running the application with the Run as administrator feature and see if it works.

## 4\. Change Group Policy Settings

 Is the Run as administrator function not working despite trying the suggestions above? It's likely that group policy settings block the feature. To fix this, head to the Local Group Policy Editor and check the settings.

 Here’s what you need to do:

1. Press **Win + R** simultaneously to open the Run dialogue box.
2. Type **gpedit.msc** in the text field and press **Enter**. This will open the Local Group Policy Editor window on your computer screen.
3. From the left navigation panel, go to the following path:  
Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options
4. In the right pane, you'll see a list of different security options. Scroll to the bottom and double-click on the **User Account Control: Run all administrators in Admin Approval Mode** policy.  
![Run all administrators in admin approved](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/run-all-administrators-in-admin-approved.jpg)
5. Doing this will open another window. Here, select the **Disabled** option and click **Apply** \> **OK**.  
![Disable User Account Control in Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-user-account-control-in-group-policy.jpg)
6. Close the Local Group Policy Editor and restart your computer.

 After restarting, try running a program with elevated privileges. It should work now. Don't forget to re-enable the Admin Approval Mode setting once you're finished troubleshooting.

## 5\. Clean up the Context Menu

 When you right-click on a program or file, you often see the Run as administrator option in the context menu. If it's missing, you should look at your context menu entries for clutter.

 This solution involves editing the Windows registry. A single mistake can cause serious problems. So proceed cautiously and [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before applying any changes.

 Follow these steps to clean up the context menu:

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **regedit** in the text field and press Enter. Doing this will open the Windows Registry Editor.
3. If the UAC window pops up, click **Yes** to grant administrative privileges.
4. In the Registry Editor window, navigate to the following path:  
Computer\HKEY_CLASSES_ROOT\*\shellex\ContextMenuHandlers
5. Next, expand the **ContextMenuHandlers** folder and look for any suspicious entries. If you find any, delete them.  
![Clean the Context Menu Items](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/clean-the-context-menu-items.jpg)
6. Now exit the Registry Editor and restart your computer.

 Once your computer reboots, you will see the Run as administrator option in the context menu. Try running a program with elevated privileges and see if it works.

## 6\. Try Some Generic Fixes

 Besides the fixes mentioned above, some generic solutions work in any situation. Try these out if you’re still having issues running applications with elevated privileges:

* [Repair Corrupted System Files](https://www.makeuseof.com/windows-built-in-repair-tools/): It restores your computer’s corrupted and missing system files. Use them to repair the root cause of the issue.
* [Perform a Clean Boot](https://www.makeuseof.com/clean-boot-windows-11/): When you start Windows in a clean boot state, the operating system will only run essential services and programs. It identifies any third-party software causing the issue.
* [Create a New Administrator User Account](https://www.makeuseof.com/tag/windows-administrator-account-everything-need-know/): If all else fails, try creating a new administrator user account and logging in. This ascertains if your existing account is corrupted or not.

## Troubleshooting Run as Administrator on Windows

 We hope this guide helped you solve the Run as administrator not working on Windows issue. Despite the prevalence of this problem, it’s relatively easy to fix if you know what to do.

 If none of the troubleshooting steps worked, try running a system scan using an advanced antivirus program. Some malicious programs prevent you from running as an administrator. A complete system scan should find and remove any malicious software on your computer, so you can start using it again.

 That’s where this guide comes into play. So, let’s look at what you can do to fix Run as administrator not working on Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/effortless-windows-11-deployment-on-vmware-17-platform/"><u>Effortless Windows 11 Deployment on VMWare 17 Platform</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-pin-count-on-the-w11-start-screen/"><u>Boosting Pin Count on the W11 Start Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-spotify-link-reset-strategies/"><u>Mastering Windows Spotify Link Reset Strategies</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-beginners-roadmap-for-whatsapp-group-rooms/"><u>[New] In 2024, Beginners' Roadmap for WhatsApp Group Rooms</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-ultimate-guide-to-iphone-selfie-gear-rankings-8/"><u>In 2024, The Ultimate Guide to Iphone Selfie Gear Rankings (#8)</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-guide-deciphering-and-fixing-error-x800704cf/"><u>Expert Guide: Deciphering and Fixing Error X800704CF</u></a></li>
<li><a href="https://discord-videos.techidaily.com/premium-mobile-and-desktop-discord-recorders/"><u>Premium Mobile & Desktop Discord Recorders</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-potential-of-windows-without-using-the-compatibility-tool/"><u>Unlock Potential of Windows without Using the Compatibility Tool.</u></a></li>
<li><a href="https://windows11.techidaily.com/identify-and-solve-hidden-disk-space-problems-in-windows/"><u>Identify & Solve Hidden Disk Space Problems in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-0x80072af9-error-code-instantly/"><u>Eliminating 0X80072AF9 Error Code Instantly</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-requirement-errors-in-gaming/"><u>Bypassing Windows Requirement Errors in Gaming</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-driver-verifier-management-in-windows-11/"><u>Guide: Driver Verifier Management in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/install-and-enhance-edge-security-with-the-defender-application-guard-from-ms/"><u>Install and Enhance Edge Security with the Defender Application Guard From MS</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-rx-heritage-bundle-for-2024/"><u>[New] RX Heritage Bundle for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-full-potential-of-taskbar-in-win11/"><u>Unlock the Full Potential of Taskbar in Win11</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-how-to-make-gif-stickers-for-whatsapp-100-the-easy-way/"><u>Updated How to Make GIF Stickers for WhatsApp 100 The Easy Way</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-preventing-google-chromes-autopilot-tabs/"><u>Guide to Preventing Google Chrome's Autopilot Tabs</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-the-barrier-of-windows-11-updates/"><u>Breaking Down the Barrier of Windows 11 Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-ultimate-free-toolset-for-win11-pcs/"><u>Unveiling the Ultimate Free Toolset for Win11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/creating-personalized-themes-in-wt-terminal/"><u>Creating Personalized Themes in WT Terminal</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-new-horizons-in-personalizing-windows-11/"><u>Exploring New Horizons in Personalizing Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-microsoft-store-eliminating-code-x80072f30-errors/"><u>Mastering the Microsoft Store: Eliminating Code X80072F30 Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-error-code-0x8007251d-in-microsofts-os-activation/"><u>Demystifying Error Code 0X8007251d in Microsoft's OS Activation</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/times-illusion-crafting-engaging-slow-motion-videos-on-ig-for-2024/"><u>Time's Illusion  Crafting Engaging Slow-Motion Videos on IG for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/apex-top-youtube-videos-watch-count-heaven/"><u>Apex Top YouTube Videos  Watch Count Heaven</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-workspace-potential-discover-the-best-window-folder-methods/"><u>Unlock Workspace Potential: Discover the Best Window Folder Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/10-swift-routes-to-the-control-panel-interface/"><u>10 Swift Routes to the Control Panel Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-and-overcoming-microsoft-offices-error-code-0x80040610/"><u>Deciphering and Overcoming Microsoft Office's Error Code 0X80040610</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-windows-tray-for-numeric-lock-signifiers/"><u>Customizing Windows Tray for Numeric Lock Signifiers</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-2024-approved-iconic-public-music-pieces-for-sequential-artworks/"><u>Updated 2024 Approved Iconic Public Music Pieces for Sequential Artworks</u></a></li>
<li><a href="https://some-skills.techidaily.com/ultimate-webcam-selection-for-podcasting-for-2024/"><u>Ultimate Webcam Selection for Podcasting for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-journey-through-time-a-comprehensive-guide-on-scanning-and-storing-old-prints/"><u>2024 Approved  Journey Through Time  A Comprehensive Guide on Scanning and Storing Old Prints</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-faster-typing-the-powertoys-way/"><u>Unlock Faster Typing: The PowerToys Way</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-sound-sleuths-exceptional-music-detection-software-to-uncover-your-favorite-tunes-on-android-for-2024/"><u>New Sound Sleuths Exceptional Music Detection Software to Uncover Your Favorite Tunes on Android for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-win-1011s-geforce-notaxc0f1103f-error/"><u>Fixing Win 10/11'S GeForce NotaXC0F1103F Error</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-3-ways-to-fake-gps-without-root-on-nokia-g310-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Fake GPS Without Root On Nokia G310 | Dr.fone</u></a></li>
</ul></div>
