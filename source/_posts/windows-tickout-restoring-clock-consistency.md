---
title: "Windows Tickout: Restoring Clock Consistency"
date: 2024-12-08T19:20:13.592Z
updated: 2024-12-10T18:07:50.290Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows Tickout: Restoring Clock Consistency"
excerpt: "This Article Describes Windows Tickout: Restoring Clock Consistency"
keywords: Windows Time Fix,Clock Sync Windows,Set Windows Clock,Unify Windows Timer,Adjust Window's Clock,Correct Tickout Windows,Align Windows Time Display
thumbnail: https://thmb.techidaily.com/309cf08df9ca66a5508e9f2e2ecebe14a1b42826a0f2e3102f8c44796a0894ed.jpg
---

## Windows Tickout: Restoring Clock Consistency

 Is your Windows system clock out of sync? Are you receiving an error message saying “Time synchronization failed”? It may cause various issues like missing reminders or emails with the wrong timestamp. Read this guide to learn how to fix the issue and synchronize your system clock accurately.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YB7Ou4-iKVM?si=7Fq8iUwI8voccMLx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VlwHTQQMs?si=BXYwD1pKiaTuev4y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LBCobAYzzcc?si=J3eSTQ3AdyxWAjGo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Double-click on the new **String Value** and enter a valid time server URL in the Value data box.
8. Repeat the above steps until you have added all the time servers to the list.

 Once you are done, close the registry editor. After synchronization completes, close all windows and restart your computer. Then verify if the time is accurate.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LT4sdZgUvRQ?si=SvQD5FouEzu4UHpJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fqBKCGAKHmA?si=OkoaI17nE5qNqTHj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-cloud.techidaily.com/new-av1-decoded-for-starters/"><u>[New] AV1 Decoded for Starters</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-innovative-approaches-to-online-collaboration-4/"><u>[New] In 2024, Innovative Approaches to Online Collaboration (#4)</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-sun-salutations-and-beyond-youtubes-premier-yoga-pages/"><u>[Updated] In 2024, Sun Salutations & Beyond – YouTube's Premier Yoga Pages</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-for-rectifying-display-driver-crashes/"><u>Essential Tips for Rectifying Display Driver Crashes</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-disable-hyper-v-in-windows-11/"><u>Guide to Disable Hyper-V in Windows 11</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-does-crypto-work-your-starter-resource-based-on-zdnet-expertise/"><u>How Does Crypto Work? Your Starter Resource Based on ZDNet Expertise</u></a></li>
<li><a href="https://win-solutions.techidaily.com/how-to-fix-black-ops-cold-war-e887a0005-error-a-step-by-step-guide/"><u>How to Fix Black Ops Cold War E887A0005 Error – A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-repair-auto-detection-failure-in-windows-proxies/"><u>How to Repair Auto-Detection Failure in Windows Proxies</u></a></li>
<li><a href="https://windows11.techidaily.com/improve-efficiency-with-top-5-clock-screensaver-apps/"><u>Improve Efficiency with Top 5 Clock Screensaver Apps</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-prime-time-action-film-transcription/"><u>In 2024, Prime Time Action Film Transcription</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-setting-the-standard-for-online-video-presentations-yt-thumbnail-sizing/"><u>In 2024, Setting the Standard for Online Video Presentations – YT Thumbnail Sizing</u></a></li>
<li><a href="https://fox-access.techidaily.com/in-2024-unveil-the-power-leveraging-windows-11-and-zoom-maximum/"><u>In 2024, Unveil the Power Leveraging Windows 11 and Zoom Maximum</u></a></li>
<li><a href="https://win11.techidaily.com/leading-windows-simulators-unmatched-nintendo-switch-games/"><u>Leading Windows Simulators: Unmatched Nintendo Switch Games</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-auto-shutdown-for-idle-windows-1011-machines/"><u>Mastering Auto-Shutdown for Idle Windows 10/11 Machines</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-normal-operations-for-deleted-characters/"><u>Restoring Normal Operations for Deleted Characters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-tackle-reversal-in-keyboard-input/"><u>Strategies to Tackle Reversal in Keyboard Input</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-to-conceal-windows-11s-task-control-icon/"><u>Tactics to Conceal Windows 11'S Task Control Icon</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-to-overcome-disappearing-ubisoft-game-launcher/"><u>Tactics to Overcome Disappearing Ubisoft Game Launcher</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-repairing-disp-settings-missing-error/"><u>Tips for Repairing Disp Settings Missing Error</u></a></li>
</ul></div>

