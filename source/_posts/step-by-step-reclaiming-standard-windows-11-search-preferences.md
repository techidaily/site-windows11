---
title: "Step-by-Step: Reclaiming Standard Windows 11 Search Preferences"
date: 2024-07-11T21:43:53.417Z
updated: 2024-07-12T21:43:53.417Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Step-by-Step: Reclaiming Standard Windows 11 Search Preferences"
excerpt: "This Article Describes Step-by-Step: Reclaiming Standard Windows 11 Search Preferences"
keywords: Win11 Search Guide,Customize Windows 11,Set Win11 Search,Default Win11 Search,Modify Windows 11 Search,Windows 11 Preferences,Restore Win11 Settings
thumbnail: https://thmb.techidaily.com/2e81f992123e17db59f89c6842ca48bb426d509215d95604071818ec4e7dc281.jpg
---

## Step-by-Step: Reclaiming Standard Windows 11 Search Preferences

 Like any other computer program, Windows Search can sometimes develop issues that require you to reset its settings to work properly. This article explains two simple ways to reset Windows Search settings back to default. Let's look at each one in detail.

## Why Should You Reset Windows Search Settings?

 Windows Search tracks files and folders on your hard drive, so you can find them more quickly. However, over time search settings and preferences can become corrupted, leading to incorrect search results or slow performance. To get the most effective results from Windows Search, you should periodically reset your search settings.

 Resetting search settings on Windows can improve search speed and accuracy. It gets rid of useless data and resolves errors or conflicts due to stored information. This can ultimately enhance your computer’s performance and provide a more efficient search experience.

 Let's now explore how to reset Windows Search settings.

## 1\. Tweak the Registry Editor

 If you want to reset Windows Search settings back to default, you can modify the registry editor. It involves directly changing certain keys in the Windows Registry, which can sometimes become risky if done incorrectly.

 To avoid this issue, be sure to [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before proceeding. Once done, follow these steps.

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **regedit** in the dialog box and hit the Enter key.
3. When the UAC prompt appears on the screen, click **Yes** to continue.
4. In the Registry Editor window, navigate to the following path:  
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows Search  
 You can also copy and paste the path into the address bar at the top of the window and hit the Enter key. This will take you to the Windows Search section.
5. Now move to the right pane and search for the key named **SetupCompletedSuccessfully**.  
![Reset Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-search.jpg)
6. Select this key, right-click on it, and choose **Modify**.
7. Set the value to **0** and click **OK** to save the changes.

 If the SetupCompletedSuccessfully key is missing, you will have to manually create it. To do this, right-click on the Windows Search key and select **New > DWORD (32-bit) Value**. Name this newly created key as **SetupCompletedSuccessfully** and set its value to **0**.

 After performing the steps above, close the Registry Editor and restart your computer for the changes to take effect.

## 2\. Use Windows PowerShell

 If you prefer command-line solutions, you can use PowerShell to reset Windows Search settings. It involves running a few simple commands to restore search settings. Here's how to do it.

[Open the Microsoft Download Page](https://www.microsoft.com/en-us/download/100295) and download the ResetWindowsSearchBox.ps1 PowerShell script. Once downloaded, right-click on the file and select **Run with PowerShell**.

 If you see an error message _"Cannot be loaded because the running script is disabled on this system"_ you need to enable script execution first. To do that, [open PowerShell as a system administrator](http://www.makeuseof.com/windows-11-powershell-administrator/). Then type **Get-ExecutionPolicy** and press Enter.

![Restrict or Unrestrict the Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/restrict-or-unrestrict-the-command.png)

 If the output is **Restricted**, execute the following command to allow PowerShell scripts:

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Unrestricted

 After setting the execution policy, try running the ResetWindowsSearchBox.ps1 file again. Once the script is executed successfully, it resets Windows search settings.

![Reset Windows Search Via PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-search-via-powershell.png)

 After resetting the Windows Search settings, you can restore the execution policy to its original settings. To do that, open PowerShell as an administrator again and execute the following command:

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Restricted

 Once the execution policy is set back to its original value, restart your computer. The Windows Search settings should now be restored to their default state.

## Easy Ways to Reset Windows Search

 Resetting Windows search settings can fix any issues you may have with your search experience. This guide will teach you how to reset Windows Search settings to their original values.


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
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-mc-homes-that-define-virtual-villages/"><u>[New] In 2024, MC Homes that Define Virtual Villages</u></a></li>
<li><a href="https://windows11.techidaily.com/masking-task-view-button-on-win-11-bar/"><u>Masking Task View Button on Win 11 Bar</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-full-course-on-morphvox-converting-your-voice-professionally/"><u>2024 Approved  Full Course on MorphVOX  Converting Your Voice Professionally</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-from-everyday-snaps-to-professional-videos-the-top-9-mobile-filmmaking-gadgets/"><u>[Updated] 2024 Approved  From Everyday Snaps to Professional Videos - The Top 9 Mobile Filmmaking Gadgets</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-camera-access-notification-controls-on-win11/"><u>Mastering Camera Access Notification Controls on Win11</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-unlocking-the-potential-of-mobile-platforms-for-personalbusiness-yt/"><u>[New] Unlocking the Potential of Mobile Platforms for Personal/Business YT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-guide-airpods-and-windows-compatibility/"><u>Simplified Guide: AirPods & Windows Compatibility</u></a></li>
<li><a href="https://network-issues.techidaily.com/quick-solution-smooth-video-screenshots/"><u>Quick Solution: Smooth Video Screenshots</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-in-2024-beginners-guide-to-premium-gopro-accessories/"><u>[New] In 2024, Beginner’s Guide to Premium GoPro Accessories</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-memory-management-for-edges-webview2/"><u>Mastering Memory Management for Edge's WebView2</u></a></li>
<li><a href="https://windows11.techidaily.com/master-syncing-how-to-rectify-non-syncing-in-ms-to-do/"><u>Master Syncing: How to Rectify Non-Syncing In MS To Do</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-window-terminals-shutdown-procedures-entryexit-tactics/"><u>Mastering Window Terminal's Shutdown Procedures: Entry/Exit Tactics</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-discovering-your-youtube-comments-on-various-devices/"><u>[New] In 2024, Discovering Your YouTube Comments on Various Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-0x800700e9-error-within-xbox-game-pass-and-windows-11/"><u>Rectifying 0X800700E9 Error Within Xbox Game Pass & Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-dive-into-and-remove-windows-usage-logs/"><u>How to Dive Into and Remove Windows Usage Logs</u></a></li>
<li><a href="https://windows11.techidaily.com/preserving-windows-default-time-configuration/"><u>Preserving Windows' Default Time Configuration</u></a></li>
<li><a href="https://windows11.techidaily.com/rediscover-the-lost-treasures-within-windows-11s-features/"><u>Rediscover the Lost Treasures Within Windows 11'S Features</u></a></li>
<li><a href="https://windows11.techidaily.com/preserving-torrent-performance-post-transfer-to-a-new-machine/"><u>Preserving Torrent Performance Post-Transfer to a New Machine</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-based-itunes-freeze-problems/"><u>Overcoming Windows-Based iTunes Freeze Problems</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-a-step-by-step-guide-to-crafting-immersive-fb-video-experienenas/"><u>[Updated] In 2024, A Step-by-Step Guide to Crafting Immersive FB Video Experienenas</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-new-territory-altering-default-app-choices-in-windows-11/"><u>Navigating New Territory: Altering Default App Choices in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-fixing-non-working-display-driver-on-windows-11/"><u>Guide to Fixing Non-Working Display Driver on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-speedier-net-transfers-on-battlenet-windows/"><u>Mastering Speedier Net Transfers on Battle.net Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-enable-driver-verification-on-windows-11-pcs/"><u>How to Enable Driver Verification on Windows 11 PCs</u></a></li>
<li><a href="https://fox-helps.techidaily.com/the-hook-up-guide-scripts-to-seduce-listeners-for-2024/"><u>The Hook-Up Guide  Scripts to Seduce Listeners for 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-the-soft-bricked-motorola-defy-2-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix the Soft Bricked Motorola Defy 2? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-rectifying-memory-issues-on-pcs/"><u>Guide to Rectifying Memory Issues on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-start-guide-to-windows-11-apps/"><u>Quick Start Guide to Windows 11 Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-nvidia-control-panel-not-saving-settings-in-windows-11/"><u>How to Fix the NVIDIA Control Panel Not Saving Settings in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/instant-change-of-windows-dashboard-background/"><u>Instant Change of Windows Dashboard Background</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-a-network-locked-oppo-a2-phone-by-drfone-android/"><u>How to Unlock a Network Locked Oppo A2 Phone?</u></a></li>
<li><a href="https://windows11.techidaily.com/innovative-windows-search-techniques-that-dont-use-ls/"><u>Innovative Windows Search Techniques That Don't Use LS</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-the-ipogo-get-you-banned-and-how-to-solve-it-on-honor-play-7t-drfone-by-drfone-virtual-android/"><u>Will the iPogo Get You Banned and How to Solve It On Honor Play 7T | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-your-way-installing-google-maps-on-pc/"><u>Navigating Your Way: Installing Google Maps on PC</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-realme-narzo-60-pro-5g-phone-frp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Realme Narzo 60 Pro 5G Phone FRP Lock</u></a></li>
</ul></div>
