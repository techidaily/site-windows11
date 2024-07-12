---
title: 9 Ways to Fix the 0X8004def5 OneDrive Error Code on Windows 11
date: 2024-07-11T21:25:16.155Z
updated: 2024-07-12T21:25:16.155Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 9 Ways to Fix the 0X8004def5 OneDrive Error Code on Windows 11
excerpt: This Article Describes 9 Ways to Fix the 0X8004def5 OneDrive Error Code on Windows 11
keywords: OneDrive Error Fix,0X8004Def5 Solutions,Windows 11 File Access,Def5Error Repair,SaveOneDrive Data,Windows Error Code DF5,Office Apps Troubleshoot
thumbnail: https://thmb.techidaily.com/b291d1186c17a0e27af028a28ffb312d4304bf88d64275a707a4eb2f0cc766f8.jpg
---

## 9 Ways to Fix the 0X8004def5 OneDrive Error Code on Windows 11

 Microsoft bundles OneDrive with Windows 11 by default. Despite not being the most popular cloud storage service, it's hard to ignore its 5 GB free cloud storage offer. It's less than Google Drive but still lucrative because it's built into Windows.

 However, some users face the infuriating error code 0x8004def5 whenever they try to launch it. The error code indicates a problem in establishing a connection with OneDrive.

 If you face the same error and cannot log in and access your OneDrive account, don't worry. We will list out multiple methods to restore OneDrive to its working state. Let's begin.

## 1\. Terminate OneDrive and Restart the App

 Before trying out any complex fixes, you must terminate all the active instances of OneDrive. After that, restart it to check if it connects with the server. Here's how:

1. Press**Ctrl + Shift + Esc** to [open Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) .
2. Go to the top search bar and type**OneDrive** .
3. Switch to the**Details** tab. Right-click on the**OneDrive.exe** process and select the**End process tree** option from the context menu.
4. A popup window will launch. Click on the**End process tree** option.  
![Terminate OneDrive and Restart](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/terminate-onedrive-and-restart.jpg)
5. Open the Start menu and type OneDrive. Click on the**Open** option and check if the error pops up.

## 2\. Check if OneDrive Servers Are Down

 OneDrive stores all your data in a dedicated cloud server maintained by Microsoft. Despite promising 99% uptime, it is common for cloud services like OneDrive to encounter outages. Or the service could be down due to scheduled maintenance.

 You can visit the [Microsoft Service Health page](https://portal.office.com/servicestatus) to check which services are down. Alternatively, you can use third-party websites like [DownDetector](https://downdetector.com/) . That way, you can know if other users also face the same server outage issue. If that's the case, you have to wait until Microsoft resolves the problem and brings up the OneDrive servers again.

## 3\. Completely Shut Down and Reboot Your Computer

 Background services are susceptible to glitches and crashes. If one or more such essential services encounter a glitch, it can impede apps that rely on them. However, Windows 11 enables Fast Startup by default which preserves the state of all system and kernel processes for speeding up boot time.

 Even if you shut down the system, it will not close and restart all processes and services. So, you must perform a complete shutdown. Repeat the following steps to do so:

1. Press**Win + R** to open the Run command box. Type**cmd** and press**Ctrl + Shift + Enter** keys to open the command prompt with administrator privileges.
2. Now, type the following command and press the enter key:**shutdown /s /f /t 0**  
![Perform a complete system shutdown](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/perform-a-complete-system-shutdown.jpg)
3. A complete shutdown will take longer than usual. Wait for the system to Restart and boot to the desktop.
4. Now, launch OneDrive and check if you can access your files.

## 4\. Switch Network Connections

 It is possible that your current ISP, or the network you are connected to, blocks Microsoft's servers. Many users shared they were able to fix the issue when they switched to another network. You can simply create a wireless hotspot from your phone or use USB tethering to share the internet with your Windows computer.

 After that, relaunch the OneDrive app and check if you can access your files on the network. You can also request your ISP to remove the block on your connection to access the OneDrive servers seamlessly in the future.

## 5\. Clear OneDrive Logs

 You can try clearing OneDrive telemetry log files in the app data folder. Here's how to do it:

1. Press**Win + E** to [open the File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) .
2. Go to the address bar, type the following path, and replace the "**UserName** " with your PC's username:  
C:\Users\UserName\AppData\Local\Microsoft\OneDrive\setup\logs
3. Press the enter key to navigate to the OneDrive logs folder.
4. Locate the**userTelemetryCache.otc** file and copy it.**Paste** it to any other disk drive on your system.
5. Return to the logs folder and**delete** the**userTelemetryCache.otc** file.  
![Clear OneDrive Logs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/clear-onedrive-logs.jpg)
6. Close the File Explorer and restart your system.
7. Launch OneDrive and then check if it encounters the same error code.

## 6\. Reset OneDrive

 You can reset some Windows apps by accessing their advanced settings. But OneDrive doesn't have an advanced settings option in the Settings app. So, you need to reset it manually using the command prompt. Here's how:

1. Press**Win + R** to open the Run command box. Type**cmd** and press the Enter key to open a new Terminal window.
2. Type the following command and press the enter key:  
%localappdata%\Microsoft\OneDrive\onedrive.exe /reset
3. Wait for the command to reset OneDrive. You will see the OneDrive window popup informing you that the reset is underway.  
![Reset OneDrive 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-onedrive-1.jpg)
4. Close the app after you see the "Reset completed" message. Restart your system.

## 7\. Reinstall OneDrive Using Winget

 If resetting the app didn't work, consider a complete reinstall. It will fix any underlying corruption with the app files and install the latest version on your system. Here's how to do it with the Winget tool:

1. Press**Win + R** to open the Run command box. Type**cmd** in the text box and press**Ctrl + Shift + Enter** keys to open the command prompt with administrator privileges.
2. Type the**winget list onedrive** command and press the enter key.**Copy** the**ID** of the OneDrive app.
3. Now, run the**winget uninstall** command with the OneDrive app ID. This is what it will look like:**Winget uninstall Microsoft.OneDrive**
4. Wait for winget to remove OneDrive from your system. To confirm the uninstallation, type the following command:**winget list onedrive**
5. You will see that no package named OneDrive is not present on your system.  
![Reinstall OneDrive 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reinstall-onedrive-1.jpg)

1. Type**cls** to clear the command prompt window.
2. Now, input the following command and press the enter key:**winget install Microsoft.OneDrive**  
![Reinstall OneDrive 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reinstall-onedrive-2.jpg)
3. Wait for the tool to download and install OneDrive on your system. You don't need to interact with the installer.
4. **Close** the command prompt window after seeing the "**Successfully installed** " message.
5. Launch OneDrive. You will have to**sign in** with your account.
6. Check if you can connect and browse your files.

## 8\. Rollback Windows Updates

 New Windows updates can sometimes wreck your system and break app compatibility. If OneDrive runs fine before installing a new update,[roll back the Windows update](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) . It could take longer if the update file is too big and not all Windows updates can be undone. After that, restart your system and try running the OneDrive app.

## 9\. Restore or Reset the PC

 If you still face the OneDrive error code, it's time to [perform a System Restore or a Windows Reset](https://www.makeuseof.com/windows-reset-system-restore-difference/) . It will help you revert to an old but working system configuration when OneDrive was working fine. Look for the most recent restore point in the wizard and use that.[Perform a factory reset](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) only if you don't have any Windows Restore points available.

## Make OneDrive Functional Again

 OneDrive can fail to connect with the server for a variety of reasons. Start with basic troubleshooting and check if the OneDrive servers are active. After that, delete the telemetry log files and reset the app. If that has no impact, reinstall the OneDrive app and log in again.

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
<li><a href="https://windows11.techidaily.com/win-1011-printer-uninstallation-a-quick-and-direct-guide/"><u>Win 10/11 Printer Uninstallation: A Quick & Direct Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-removing-onedrive-linkage-on-windows-os/"><u>Steps for Removing OneDrive Linkage on Windows OS</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-rhythmic-revelations-top-15-vlogs-celebrating-music-creators-stories/"><u>[Updated] Rhythmic Revelations  Top 15 Vlogs Celebrating Music Creators' Stories</u></a></li>
<li><a href="https://video-capture.techidaily.com/superior-hd-gameplay-through-top-captures-for-2024/"><u>Superior HD Gameplay Through Top Captures for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-fixing-skewed-views-in-internet-based-videos/"><u>In 2024, Fixing Skewed Views in Internet-Based Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-windows-pc-boosters-for-speed-and-efficiency/"><u>Top 5 Windows PC Boosters for Speed and Efficiency</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-from-noisy-to-silent-a-filmmakers-guide-to-perfecting-audio-quality-with-filmora-software/"><u>New 2024 Approved From Noisy to Silent A Filmmakers Guide to Perfecting Audio Quality with Filmora Software</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-icon-organization-made-simple/"><u>Windows Icon Organization Made Simple</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-unseen-wi-fi-in-windows/"><u>The Art of Unseen Wi-Fi in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-student-laptop-asus-s15-oled-in-focus/"><u>The Ultimate Student Laptop: ASUS S15 OLED in Focus</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-endless-screen-saving-software/"><u>[Updated] In 2024, Endless Screen Saving Software</u></a></li>
<li><a href="https://windows11.techidaily.com/time-travel-tech-windows-7-product-key-for-11-activation/"><u>Time-Travel Tech: Windows 7 Product Key for 11 Activation</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-desk-icons-clashing-find-harmony/"><u>Windows Desk Icons Clashing - Find Harmony!</u></a></li>
<li><a href="https://fix-guide.techidaily.com/realme-narzo-60-pro-5g-screen-unresponsive-heres-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Realme Narzo 60 Pro 5G Screen Unresponsive? Heres How to Fix It | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/the-9-best-features-in-the-windows-11-february-2023-update/"><u>The 9 Best Features in the Windows 11 February 2023 Update</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-reimagined-analyzing-the-core-upgrades-of-windows-11/"><u>Windows Reimagined: Analyzing the Core Upgrades of Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-instructions-for-software-icons-on-desktop-menu/"><u>Tailored Instructions for Software Icons on Desktop Menu</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-the-ultimate-guide-to-selecting-a-premier-fb-cover-photo-designer/"><u>In 2024, The Ultimate Guide to Selecting a Premier FB Cover Photo Designer</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-unleash-the-power-of-online-livestreams-with-us-today/"><u>[Updated] Unleash the Power of Online Livestreams with Us Today</u></a></li>
<li><a href="https://extra-resources.techidaily.com/affordable-4k-cameras-guide-(1k-top-picks-for-2024/"><u>Affordable 4K Cameras Guide (<$1K) - Top Picks for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-the-hover-over-sensitivity-and-visibility-in-windows-11/"><u>Tailoring the Hover Over Sensitivity and Visibility in Windows 11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-fundamentals-of-creating-dynamic-podcast-feeds/"><u>In 2024, The Fundamentals of Creating Dynamic Podcast Feeds</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-remove-screen-lock-pin-on-xiaomi-mix-fold-3-like-a-pro-5-easy-ways-by-drfone-android/"><u>In 2024, How To Remove Screen Lock PIN On Xiaomi Mix Fold 3 Like A Pro 5 Easy Ways</u></a></li>
<li><a href="https://windows11.techidaily.com/three-steps-for-ditching-microsofts-store/"><u>Three Steps for Ditching Microsoft's Store</u></a></li>
<li><a href="https://windows11.techidaily.com/1719290153300-quick-fix-guide-resurrect-your-chrome-browser-in-w11/"><u>Quick Fix Guide: Resurrect Your Chrome Browser in W11.</u></a></li>
<li><a href="https://windows11.techidaily.com/10-tips-to-restore-bluetooth-functionality-on-windows-11/"><u>10 Tips to Restore Bluetooth Functionality on Windows 11</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-jumpstart-your-recording-with-this-obs-mac-setup-guide/"><u>2024 Approved  Jumpstart Your Recording with This OBS Mac Setup Guide</u></a></li>
<li><a href="https://some-techniques.techidaily.com/game-changing-growl-techniques-in-free-fire-for-2024/"><u>Game-Changing Growl Techniques in Free Fire for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-infusing-watermarks-in-youtube-content-for-trademarks/"><u>In 2024, Infusing Watermarks in YouTube Content for Trademarks</u></a></li>
<li><a href="https://windows11.techidaily.com/unfreezing-windows-updates-top-6-strategies-to-resolve-sticking-issues/"><u>Unfreezing Windows Updates: Top 6 Strategies to Resolve Sticking Issues</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-monetary-milestones-a-look-at-pewdiepies-yearly-income/"><u>In 2024, Monetary Milestones  A Look at PewDiePie's Yearly Income</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-network-overview-understanding-arp-caches/"><u>Windows Network Overview: Understanding ARP Caches</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-avoiding-common-nocturnal-photography-errors/"><u>In 2024, Avoiding Common Nocturnal Photography Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-full-gpu-potential-in-windows-10-and-11-via-vram/"><u>Unleashing Full GPU Potential in Windows 10 & 11 via VRAM</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-mastering-twitch-instant-replay-techniques/"><u>[New] Mastering Twitch  Instant Replay Techniques</u></a></li>
<li><a href="https://fake-location.techidaily.com/looking-for-a-location-changer-on-oppo-reno-11f-5g-look-no-further-drfone-by-drfone-virtual-android/"><u>Looking For A Location Changer On Oppo Reno 11F 5G? Look No Further | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-of-windows-law-filter-mechanics-and-output/"><u>Unraveling the Mystery of Window's LAW Filter Mechanics and Output</u></a></li>
<li><a href="https://android-unlock.techidaily.com/the-ultimate-guide-to-vivo-t2x-5g-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>The Ultimate Guide to Vivo T2x 5G Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-fbm-issues-on-your-pc-screen/"><u>Unblocking FBM Issues on Your PC Screen</u></a></li>
</ul></div>
