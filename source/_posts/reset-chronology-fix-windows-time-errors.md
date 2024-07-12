---
title: "Reset Chronology: Fix Windows Time Errors"
date: 2024-07-11T21:22:55.766Z
updated: 2024-07-12T21:22:55.766Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Reset Chronology: Fix Windows Time Errors"
excerpt: "This Article Describes Reset Chronology: Fix Windows Time Errors"
keywords: Reset Time Windows,Windows Date Correction,Fix Windows Timestamp,Correct Time Errors PC,Set Windows Clock Right,Realign Windows Calendar,Tweak Windows DateError
thumbnail: https://thmb.techidaily.com/9304676ddebde0491fac069817e2e83439806cdb3bbe061f637b22cd4655ca5f.jpg
---

## Reset Chronology: Fix Windows Time Errors

 Is your Windows system clock out of sync? Are you receiving an error message saying “Time synchronization failed”? It may cause various issues like missing reminders or emails with the wrong timestamp. Read this guide to learn how to fix the issue and synchronize your system clock accurately.

## What Causes Time Synchronization to Fail on Windows?

 Time synchronization issues on Windows can occur for several reasons. Here are some common causes.

1. **Incorrect timezone settings:** The time set on your PC must be accurate for synchronization to work properly. If the time zone is incorrect, synchronization will fail.
2. **Firewall settings:** Firewalls block the Windows Time service from connecting to its hosts. This prevents time synchronization from occurring.
3. **System viruses and malware:** Viruses or malicious software corrupt system files related to time synchronization, causing failure.
4. **Problems with the Windows Time service:** The Windows Time (W32Time) service controls time synchronization on your system. If it's not running properly, synchronization will fail.

 Now that you know the possible causes of time synchronization failure, let’s discuss how to fix this issue.

## 1\. Restart the Windows Time Service

 The Windows Time Service keeps the computer’s time and date synchronized with other computers on the network. If this service is stopped or not functioning, it leads to time synchronization issues.

 To restart the Windows Time Service, follow these steps:

1. Press **Win + R** on your keyboard to open the Run dialog box.
2. Type **services.msc** in the search box and hit Enter. This will open the Services window.
3. Locate the **Windows Time** service and right-click on it.
4. Select **Restart** from the context menu.  
![Restart Windows Time service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restart-windows-time-service.jpg)

 Once the service is restarted, close the window and check the time synchronization.

## 2\. Configure the Windows Time Service

 If restarting the Windows Time Service doesn't resolve the time synchronization issue, configure its settings to see if that helps.

 To configure the Windows Time Service, follow these steps:

1. [Open the Services window](https://www.makeuseof.com/windows-11-open-services-app/).
2. Double-click on **Windows Time** to open its properties window.
3. On the **General** tab, set the Startup Typeto **Automatic**.  
![Windows Time Service Status](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-time-service-status.jpg)
4. Now go to Service Status and click on the **Start** button. If the service is running, click on **Stop** and then **Start**.
5. Switch to the **Log On** tab and select **Local System account**.  
![Windows Time Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-time-properties-window.jpg)
6. Check the **Allow Service** **to Interact with desktop** option.
7. Click **Apply > OK** to save the changes.

 Now that you have configured the Windows Time Service, close the window. After that, restart your computer and check if time synchronization works.

## 3\. Change the Time Server

 This method is suitable when the time synchronization service fails to sync with an internet time server. It syncs to a reliable internet clock manually.

 To modify internet time settings, follow these steps:

1. [Open the Run Command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **timedate.cpl** in the text box and press Enter. This will open the Date and Time window.
3. Switch to the **Internet Time** tab and click on **Change settings**.
4. Check the box next to **Synchronize with an Internet time server**.  
![Change the Time Server](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/change-the-time-server.jpg)
5. Select a different time server from the **Server** list.
6. Click **Update now** to sync your PC with the selected time server.

 Once you perform the above action, close all windows and restart your computer. After restarting, check if the time synchronization issue is fixed.

## 4\. Add More Time Servers

 If changing the time server doesn't work, add more servers to the list. That way, Windows try different servers to keep time in sync. To add more time servers, follow these steps:

1. Press **Win + S** on your keyboard to open the Windows Search box.
2. Type **regedit** in the search box and hit Enter.
3. If UAC (User Account Control) dialog appears, click **Yes** to continue.
4. In the registry editor, navigate the following steps.  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\DateTime\Servers`
5. Right-click on the **Servers** key and select **New** \> **String Value**.  
![Add More Time Servers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/add-more-time-servers.jpg)
6. Name the new string value **ServerX**, where X is the server number.
7. Double-click on the new **String Value** and enter a valid time server URL in the Value data box.
8. Repeat the above steps until you have added all the time servers to the list.

 Once you are done, close the registry editor. After synchronization completes, close all windows and restart your computer. Then verify if the time is accurate.

## 5\. Scan for Malicious Programs

 If other methods fail to fix the time synchronization issue on your Windows computer, scan for malicious programs. Malicious software interrupts time synchronization processes and causes errors.

 To scan for malicious programs, follow these steps:

1. Press **Win + S** on your keyboard to open the Windows Search box.
2. Type **Windows Security** in the search box and hit Enter.
3. In the Windows Security window, click on **Virus & threat protection**.  
![Scan options in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/scan-options-in-windows-security.jpg)
4. Under **Current threats**, click **Scan options** and check **Full scan** from the list.  
![Full Scan Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/full-scan-windows-security.jpg)
5. Now click **Scan now** to initiate a full scan.

 Once you perform the above action, close the Windows Security window and restart your computer. If malicious programs were responsible for the issue, it should now keep the time synchronized correctly.

## 6\. Try Some Generic Fixes

 Besides the specific solutions mentioned above, there are some general fixes that troubleshoot time synchronization problems.

 Try these suggestions to fix time synchronization failed errors:

1. [Run the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/). This tool scans system files and replaces any corrupted files that cause the time synchronization to fail.
2. [Perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) and check if that helps. It’s possible that some software or process running on your PC interferes with time synchronization. Doing a clean boot identifies the culprit and solves the issue.
3. [Temporarily disable firewall and antivirus programs](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/). Firewall or antivirus settings can sometimes block the Windows Time service from connecting to its hosts, resulting in synchronization failure. Temporarily disabling your firewall and antivirus programs can resolve this issue.
4. [Run the Windows Network Connections tool](https://www.makeuseof.com/windows-open-network-connections-tool/) to diagnose and repair network issues.

 These fixes resolve time synchronization problems on your Windows computer.

## Fixing Time Synchronization Issues on Windows

 We hope this article resolved any timing issues you encountered on your Windows computer. If the issue continues, perform a system restore. This reverses any recent modifications that could cause the issue. Meanwhile, it is advised to regularly backup your data in case of sudden system failures.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/troubleshooting-failed-app-install-in-windows-store/"><u>Troubleshooting Failed App Install in Windows Store</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-direct-access-to-windows-11-dialer-feature/"><u>Unlocking Direct Access to Windows 11 Dialer Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-integrating-alternative-antiviruses-with-ms-defender/"><u>Tips for Integrating Alternative Antiviruses with MS Defender</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-2-ways-to-monitor-meizu-21-activity-drfone-by-drfone-virtual-android/"><u>In 2024, 2 Ways to Monitor Meizu 21 Activity | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-defaults-permissions-restoration-guide/"><u>Unlocking Defaults: Permissions Restoration Guide</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-instagram-intonation-blending-audio-with-imagery/"><u>In 2024, Instagram Intonation  Blending Audio with Imagery</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-easy-ways-to-record-webcam-chat/"><u>[Updated] In 2024, Easy Ways to Record Webcam Chat</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-error-0x80d03801-on-microsoft-store-pcs/"><u>Resolving Error 0X80D03801 on Microsoft Store PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-content-disconnected-error-on-windows-using-steam/"><u>Solving Content Disconnected Error on Windows Using Steam</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-restore-error-0x80042306-quickly/"><u>Overcoming Windows Restore Error 0X80042306 Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/unblock-your-computers-usb-hub-windows-fix-guide/"><u>Unblock Your Computer's USB Hub: Windows Fix Guide</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-engineering-engaging-media-excerpts-for-2024/"><u>[New] Engineering Engaging Media Excerpts for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-workspace-incorrante-folders-into-context-menu/"><u>Streamline Your Workspace: Incorrante Folders Into Context Menu</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-building-a-successful-online-presence-wirecast-streaming-to-youtube/"><u>2024 Approved  Building a Successful Online Presence  WireCast Streaming to Youtube</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-assemble-comic-memes-with-giphy/"><u>[New] 2024 Approved  Assemble Comic Memes with Giphy</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaim-soundfulness-overcoming-muted-mouses-cry/"><u>Reclaim Soundfulness: Overcoming Muted Mouse's Cry</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-conducting-collaborative-discussions-in-a-hassle-free-manner-via-skype-across-operating-systems/"><u>[Updated] In 2024, Conducting Collaborative Discussions in a Hassle-Free Manner via Skype Across Operating Systems</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-webs-frontier-leading-browsers-for-screen-recording/"><u>[New] Web's Frontier  Leading Browsers for Screen Recording</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-permission-fixes-for-installer-problems/"><u>Streamlining Permission Fixes for Installer Problems</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-leading-8-cameras-that-make-live-streaming-shine/"><u>2024 Approved  Leading 8 Cameras That Make Live Streaming Shine</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-guide-to-fb-video-repositories-windows-and-macos/"><u>[Updated] 2024 Approved  Guide to FB Video Repositories  Windows & macOS</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-sim-unlock-lava-yuva-2-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>In 2024, Sim Unlock Lava Yuva 2 Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-tutorial-for-managing-archive-files-via-cmd/"><u>The Ultimate Tutorial for Managing Archive Files via CMD</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-audio-sanitization-made-simple-a-guide-to-voice-less-video-enhancement/"><u>Updated Audio Sanitization Made Simple A Guide to Voice-Less Video Enhancement</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-absent-bluetooth-devices-manager/"><u>Remedy Absent Bluetooth Devices Manager</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-xiaomi-redmi-k70-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Xiaomi Redmi K70 without Losing Data | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-your-potential-7-proven-techniques-to-master-windows-based-studying/"><u>Unlock Your Potential: 7 Proven Techniques to Master Windows-Based Studying</u></a></li>
<li><a href="https://windows11.techidaily.com/revitalizing-the-old-guard-running-windows-11-on-pre-ultimate-pcs-via-to-go-and-rufus/"><u>Revitalizing the Old Guard: Running Windows 11 on Pre-Ultimate PCs via To Go & Rufus</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-np-setting-detection-mishap/"><u>Resolving Windows NP Setting Detection Mishap</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-cross-os-installation-of-kali-linux/"><u>Simplifying Cross-OS Installation of Kali Linux</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-solutions-freeing-up-stuck-windows-11-pins/"><u>Quick Solutions: Freeing Up Stuck Windows 11 PINs</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-leave-a-life360-group-on-vivo-x90s-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How To Leave a Life360 Group On Vivo X90S Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/snipping-tool-or-printscreen-best-windows-capture-strategy/"><u>Snipping Tool or Printscreen? Best Windows Capture Strategy</u></a></li>
<li><a href="https://windows11.techidaily.com/three-steps-to-validate-windows-11-activation/"><u>Three Steps to Validate Windows 11 Activation</u></a></li>
<li><a href="https://windows11.techidaily.com/stepwise-guide-for-crafting-personalized-audio-cds-from-your-mp3-collection-windows/"><u>Stepwise Guide for Crafting Personalized Audio CDs From Your MP3 Collection (Windows)</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/direct-transmission-of-television-streams-via-computer-for-2024/"><u>Direct Transmission of Television Streams via Computer for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-to-user-management-settings-in-windows-11-and-10/"><u>Navigate to User Management Settings in Windows 11 & 10</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-crafting-professional-icons-with-pre-made-graphic-elements/"><u>2024 Approved  Crafting Professional Icons with Pre-Made Graphic Elements</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-game-drives-in-xbox-app/"><u>The Ultimate Guide to Game Drives in Xbox App</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/streamlining-intellgraphics-updates-on-win7/"><u>Streamlining IntellGraphics Updates on Win7</u></a></li>
</ul></div>
