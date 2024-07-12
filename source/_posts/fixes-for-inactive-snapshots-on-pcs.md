---
title: Fixes for Inactive Snapshots on PCs
date: 2024-07-11T21:37:02.450Z
updated: 2024-07-12T21:37:02.450Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixes for Inactive Snapshots on PCs
excerpt: This Article Describes Fixes for Inactive Snapshots on PCs
keywords: Fix PC Inactive Snapshots,Active Snapshots Resolution,Preventing Snapshot Failures,Troubleshoot PC Snapshots,Activating Stale PC Snaps,Enable Snapshots on PCs,Eliminate Inactive Snapshots
thumbnail: https://thmb.techidaily.com/4703b9d657812b3886216df90e44b1d9ef5fb3878b6869f4909ce7c65740d3ae.jpg
---

## Fixes for Inactive Snapshots on PCs

 If the Volume Shadow Copy service isn't working, you'll see error messages when you try to use Backup and Restore or System Restore in Windows. We'll show you how you can fix Volume Shadow Copy when it's not working on a Windows PC, so you can get your backups going once more.

## 1\. Enable and Start Volume Shadow Copy Services

 VSS errors can often arise because the Volume Shadow Copy and Microsoft Software Shadow Copy Provider services aren’t enabled or running. For example, many users have confirmed enabling those services can fix VSS error codes 0x81000202 and 0x81000203, which affect the System Restore tool. So, you may be able to resolve numerous Volume Shadow Copy errors by enabling VSS services like this:

1. First, press the **Windows** logo key + **S** and enter a Services search phrase to find that app.
2. Click **Services** inside the search results.
3. Double-click the **Volume Shadow Copy Service**.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/services-window.jpg)
4. Click the drop-down menu labeled **Startup type** and select **Automatic** if the service is set differently.  
![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-type-drop-down-menu.jpg)
5. Press **Start** in the Volume Shadow Copy Service window.
6. Click on the service window’s **Apply** and **OK** buttons to set the changed options.
7. Repeat steps three to six for the Microsoft Software Shadow Copy Provider service.
8. Also, check that the RPC Endpoint Mapper and DCOM Server Process dependency services for Volume Shadow Copy are enabled and running.

 Restart those shadow copy services if they’re already set as required. You can do that by right-clicking on those services and selecting the Restart context menu options for them.

## 2\. Repair Your System Files With the SFC and DISM Commands

 Corrupted system files can affect Windows services, such as Volume Shadow Copy. So, some users may need to repair system files to fix the Volume Shadow Copy Service when it’s not working. You can do that by running System File Checker and Deployment Image Servicing Management scans, as covered in this article about [repairing corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/).

![The sfc scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/sfc-scannow-error.jpg)

## 3\. Run the Check Disk Utility

 Drive issues can cause Windows system backup VSS errors to occur, with codes like 0x807800A1 or 0x80042315\. In this case, running the Check Disk utility to scan for and address hard drive issues, such as bad sectors, is a potential fix for the Volume Shadow Copy Service not working. Check out this [guide to running the CHKDSK utility](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) for further details about how you can apply this potential resolution.

![The CHKDSK command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/chkdsk-scan-command.jpg)

## 4\. Disable Antivirus Shields

 Sometimes third-party antivirus software can interfere with and prevent Volume Shadow Copy from functioning correctly. So, try disabling third-party antivirus shields before attempting to back up or restore Windows. The usual way to do that is to right-click on an antivirus app’s system tray icon and select a disable/turn off shield protection option from there.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 Don’t leave your antivirus shield permanently disabled. If possible, select to disable it for a few hours before attempting the backup or system restoration operation again. Or manually re-enable your antivirus if you can’t select a temporary option.

## 5\. Disable Any Active Firewalls

 It’s also recommended to disable the firewall component of a third-party antivirus utility before attempting to perform a VSS operation. Turning off an antivirus shield won’t disable a firewall component. Look for firewall settings within your antivirus software’s tabs to see if it includes one. If it does, select to turn off the firewall.

 Try turning off the Windows firewall if you haven’t installed a third-party antivirus utility or firewall software. Check out this guide to [disabling Microsoft Defender Firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) for instructions for turning off that security component.

![The Turn off Windows Defender Firewall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-firewall-settings.jpg)

## 6\. Set Windows to Perform a Clean Boot

![The Startup type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-tab.jpg)

 Conflicting background apps or services are another potential cause of Volume Shadow Copy errors. Third-party backup utilities with snapshot managers are the most likely software packages to conflict with the Volume Shadow Copy Service. If you know you’ve installed a third-party backup manager, uninstalling it could be the best way to ensure it doesn’t cause any conflicts.

 However, you can [perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) to stop third-party apps and services from starting with Windows to prevent conflicts from arising. This involves disabling startup items and services with Task Manager and MSConfig and restarting Windows. Then try utilizing the Windows Backup and Restore or System Restore tools after clean booting your PC to see if the VSS error persists.

 If it does, this means something you disabled during the clean boot is causing the problem. Now you can slowly re-enable each app until the problem reappears, then either uninstall or update the offending app.

## Back up and Restore Windows Again

 These solutions can potentially resolve many variable Volume Shadow Copy Service error messages and codes that pop up during system backup and restore operations. With Volume Shadow Copy fixed, you can back up and restore Windows with built-in system tools again.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-redefining-wanderlust-with-virtual-reality-tours/"><u>2024 Approved  Redefining Wanderlust with Virtual Reality Tours</u></a></li>
<li><a href="https://discord-videos.techidaily.com/everything-on-discord-stickers-a-comprehensive-guide/"><u>Everything on Discord Stickers  A Comprehensive Guide</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/unleash-your-creative-potential-top-8-digital-audio-workstations-for-studio-quality-sound-design/"><u>Unleash Your Creative Potential Top 8 Digital Audio Workstations for Studio-Quality Sound Design</u></a></li>
<li><a href="https://howto.techidaily.com/6-solutions-to-fix-error-505-in-google-play-store-on-realme-11x-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Solutions to Fix Error 505 in Google Play Store on Realme 11X 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/ace-your-win-11-games-with-these-best-fps-tools/"><u>Ace Your Win 11 Games with These Best FPS Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-disruption-fixing-windows-minecraft-errors/"><u>Avoid Disruption - Fixing Windows Minecraft Errors</u></a></li>
<li><a href="https://fix-guide.techidaily.com/realme-narzo-n53-camera-not-working-unexpected-error-fix-it-now-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Realme Narzo N53 Camera Not Working Unexpected Error? Fix It Now | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-plug-in-proweries-expert-analysis/"><u>[New] PLUG-IN PROWERIES  Expert Analysis</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-asking-too-many-hands-at-once-error/"><u>Bypassing Asking Too Many Hands at Once Error</u></a></li>
<li><a href="https://windows11.techidaily.com/beneath-radar-outstanding-windows-11-customization/"><u>Beneath Radar: Outstanding Windows 11 Customization</u></a></li>
<li><a href="https://windows11.techidaily.com/1719366391353-keyboards-on-the-ropes-reclaim-your-arrows/"><u>Keyboards on the Ropes? Reclaim Your Arrows!</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-uncomplicated-ways-to-save-vimeo-content/"><u>2024 Approved  Uncomplicated Ways to Save Vimeo Content</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-cracking-the-code-calculating-your-income-from-youtubes-cpm/"><u>[New] 2024 Approved  Cracking the Code  Calculating Your Income From YouTube's CPM</u></a></li>
<li><a href="https://unlock-android.techidaily.com/forgotten-the-voicemail-password-of-xiaomi-redmi-note-12-5g-try-these-fixes-by-drfone-android/"><u>Forgotten The Voicemail Password Of Xiaomi Redmi Note 12 5G? Try These Fixes</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-oneplus-nord-n30-5g-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my OnePlus Nord N30 5G Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/leveraging-communication-to-enhance-interview-success-for-2024/"><u>Leveraging Communication to Enhance Interview Success for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/are-the-icons-on-your-windows-desktop-overlapping-here-are-some-solutions/"><u>Are the Icons on Your Windows Desktop Overlapping? Here Are Some Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-performance-of-docker-in-wsl-2-on-windows-devices/"><u>Boosting Performance of Docker in WSL 2 on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/a-history-of-the-windows-taskbar-from-1985-to-2023/"><u>A History of the Windows Taskbar From 1985 to 2023</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-infinix-hot-40-pro-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>In 2024, How to Unlock Infinix Hot 40 Pro Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://windows11.techidaily.com/blending-digital-worlds-androidpc-connections-made-simple/"><u>Blending Digital Worlds: Android/PC Connections Made Simple</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-fps-supercharge-yuzu-for-windows/"><u>Boosting FPS: Supercharge Yuzu for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-11-system-call-failures-quickly/"><u>Addressing Windows 11 System Call Failures Quickly</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-shopback-up-specialists-judgment/"><u>2024 Approved  ShopBack Up Specialists' Judgment</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-broaden-viewership-with-simultaneous-yt-and-twitch-broadcasts/"><u>[Updated] Broaden Viewership with Simultaneous YT & Twitch Broadcasts</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-quick-guide-crafting-youtube-thumbnails-on-your-phone/"><u>[New] Quick Guide  Crafting YouTube Thumbnails on Your Phone</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-vscode-shutdown-troubles-in-new-os/"><u>Avoiding VSCode Shutdown Troubles in New OS</u></a></li>
<li><a href="https://windows11.techidaily.com/best-budget-single-board-windows-systems/"><u>Best Budget Single-Board Windows Systems</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-advanced-techniques-for-capturing-high-quality-skype-calls/"><u>[Updated] 2024 Approved  Advanced Techniques for Capturing High-Quality Skype Calls</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-4-feasible-ways-to-fake-location-on-facebook-for-your-oppo-reno-10-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Feasible Ways to Fake Location on Facebook For your Oppo Reno 10 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/avoidance-of-memory-limitations-strategies-for-windows/"><u>Avoidance of Memory Limitations: Strategies for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/5-key-adjustments-for-a-mac-look-in-windows-environment/"><u>5 Key Adjustments for a Mac Look in Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/1719351366052-breathe-new-life-into-your-win11-printer-with-these-tips/"><u>Breathe New Life Into Your Win11 Printer with These Tips!</u></a></li>
<li><a href="https://windows11.techidaily.com/6-expert-windows-programs-for-video-editors/"><u>6 Expert Windows Programs for Video Editors</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/024-approved-audiences-delighted-best-editors-to-transform-youtube-shorts/"><u>[New] 2024 Approved  Audiences Delighted  Best Editors to Transform Youtube Shorts</u></a></li>
<li><a href="https://windows11.techidaily.com/beat-nvidias-windows-scanner-errors-today/"><u>Beat Nvidia's Windows Scanner Errors Today</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-blue-screen-blues-fixing-error-740-on-winos/"><u>Avoiding Blue Screen Blues: Fixing Error 740 on WINOS</u></a></li>
<li><a href="https://windows11.techidaily.com/amplify-tray-ui-add-scrolllock-and-number-keys-iconos/"><u>Amplify Tray UI: Add ScrollLock and Number Keys Iconos</u></a></li>
<li><a href="https://windows11.techidaily.com/apexs-windows-woes-strategies-to-clear-no-server-error-(156-chars/"><u>Apex's Windows Woes: Strategies to Clear No-Server Error (<156 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/captivating-yuletide-atmosphere-in-window-artistry/"><u>Captivating Yuletide Atmosphere in Window Artistry</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-find-ispoofer-pro-activation-key-on-xiaomi-redmi-a2plus-drfone-by-drfone-virtual-android/"><u>How to Find iSpoofer Pro Activation Key On Xiaomi Redmi A2+? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/audio-prowess-on-windows-a-comprehensible-drivers-upgrade-blueprint/"><u>Audio Prowess on Windows: A Comprehensible Drivers' Upgrade Blueprint</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-restoration-features-your-pathway-through-windows-11/"><u>Activating Restoration Features: Your Pathway Through Windows 11</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-command-center-redefined-your-pathway-through-studio/"><u>[Updated] Command Center Redefined  Your Pathway Through Studio</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-services-that-dont-launch/"><u>Addressing Windows Services That Don't Launch</u></a></li>
<li><a href="https://windows11.techidaily.com/bypass-black-screen-in-win11-fast-and-straightforward/"><u>Bypass Black Screen in Win11, Fast & Straightforward</u></a></li>
<li><a href="https://windows11.techidaily.com/batch-processing-excellence-using-task-scheduler/"><u>Batch Processing Excellence Using Task Scheduler</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-the-sluggishness-of-windows-discord-features/"><u>Addressing the Sluggishness of Windows Discord Features</u></a></li>
<li><a href="https://windows11.techidaily.com/a-compreenasian-approach-to-fixing-winget-on-windows-11/"><u>A Compreenasian Approach to Fixing Winget on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/changing-default-user-directory-labels-windows-11/"><u>Changing Default User Directory Labels (Windows 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/7-solutions-when-apps-arent-working-properly-on-windows/"><u>7 Solutions When Apps Aren't Working Properly on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/beginner-friendly-steps-to-install-chrome-on-windows-11/"><u>Beginner-Friendly Steps to Install Chrome on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-limited-it-admin-power-in-security-warning/"><u>Bypassing 'Limited IT Admin Power' In Security Warning</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-security-sync-windows-11-remotely-easily/"><u>Bypassing Security, Sync Windows 11 Remotely Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/bypass-windows-folder-permission-snags-swiftly/"><u>Bypass Windows Folder Permission Snags Swiftly</u></a></li>
<li><a href="https://windows11.techidaily.com/choosing-your-win-software-downloader-choco-versus-wslm/"><u>Choosing Your Win Software Downloader: Choco Versus WSLM</u></a></li>
</ul></div>
