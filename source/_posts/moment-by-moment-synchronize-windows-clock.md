---
title: "Moment by Moment: Synchronize Windows Clock"
date: 2024-07-11T21:26:42.485Z
updated: 2024-07-12T21:26:42.485Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Moment by Moment: Synchronize Windows Clock"
excerpt: "This Article Describes Moment by Moment: Synchronize Windows Clock"
keywords: Windows Time Sync,Clock Unify Windows,Sync Windows Clock,Timed Windows Update,Windows Synchronization,Schedule Windows Time,Coordinated Windows Date
thumbnail: https://thmb.techidaily.com/878905428de37ec37afcf7b8018e7d924bf2c1ca322a8100dfaafbd0ac4bcb97.jpg
---

## Moment by Moment: Synchronize Windows Clock

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
<li><a href="https://windows11.techidaily.com/keyboard-knots-unraveling-win10-functional-issues/"><u>Keyboard Knots: Unraveling WIN10 Functional Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-ppt-file-saving-challenges-swift-solutions-in-windows-11/"><u>Conquer PPT File Saving Challenges: Swift Solutions in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-bsod-errors-tackling-interrupt-exceptions-on-windows-11/"><u>Fixing BSOD Errors: Tackling Interrupt Exceptions on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-optimize-your-browsing-experience-use-defender-aguard-in-win-11-edge/"><u>How to Optimize Your Browsing Experience: Use Defender Aguard in Win 11 Edge</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-writing-permission-failure-in-windows-10-and-11/"><u>Fixing Writing Permission Failure in Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-digital-experience-process-control-and-thematic-aesthetics-in-w11/"><u>Elevate Your Digital Experience: Process Control & Thematic Aesthetics in W11</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/uick-captivating-content-learn-with-our-youtube-shorts-guide-for-2024/"><u>[New] Quick, Captivating Content? Learn with Our YouTube Shorts Guide for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-to-retrieve-the-missing-windows-product-patch/"><u>Expert Tips to Retrieve the Missing Windows Product Patch</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-labels-for-efficient-file-management-on-windows-11/"><u>Leveraging Labels for Efficient File Management on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-efail-error-code-0x80004005-in-virtualbox/"><u>Combatting E_FAIL (Error Code: 0X80004005) in Virtualbox</u></a></li>
<li><a href="https://windows11.techidaily.com/engagingnotabledarkthemefornotepadwin/"><u>EngagingNotableDarkThemeForNotepadWin</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-a-practical-guide-to-saving-screens-on-dell-computers/"><u>[Updated] A Practical Guide to Saving Screens on Dell Computers</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-selective-deactivation-for-better-efficiency/"><u>Windows 11: Selective Deactivation for Better Efficiency</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-security-beyond-bitlocker-top-4-choices/"><u>Windows Security Beyond BitLocker: Top 4 Choices</u></a></li>
<li><a href="https://windows11.techidaily.com/from-backup-bin-to-picture-panel-guiding-games-on-pcs-with-w11/"><u>From Backup Bin to Picture Panel: Guiding Games on PCs with W11</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-tranquil-application-management-in-window-11/"><u>Techniques for Tranquil Application Management in Window 11</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-call-logs-from-narzo-60-5g-by-fonelab-android-recover-call-logs/"><u>Undelete lost call logs from Narzo 60 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-network-error-0x800704b3-in-windows-11-and-11/"><u>How to Fix the Network Error 0X800704b3 in Windows 11 & 11</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-fix-when-apple-account-locked-on-iphone-se-by-drfone-ios/"><u>How to Fix when Apple Account Locked On iPhone SE?</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/irreversible-steps-for-a-fixed-tiktok-exit/"><u>Irreversible Steps for a Fixed TikTok Exit</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-ditch-intels-onboard-graphics-in-windows/"><u>How to Ditch Intel's Onboard Graphics in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-techniques-in-windows-photo-editing/"><u>Advanced Techniques in Windows Photo Editing</u></a></li>
<li><a href="https://unlock-android.techidaily.com/tips-and-tricks-for-setting-up-your-xiaomi-redmi-13c-phone-pattern-lock-by-drfone-android/"><u>Tips and Tricks for Setting Up your Xiaomi Redmi 13C Phone Pattern Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/ensure-office-applications-open-email-attachments-as-text-only-by-design/"><u>Ensure Office Applications Open Email Attachments as Text Only by Design</u></a></li>
<li><a href="https://windows11.techidaily.com/the-premier-selection-of-cost-free-high-efficiency-driver-utilities/"><u>The Premier Selection of Cost-Free, High-Efficiency Driver Utilities</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-virality-voyage-navigating-newsfeeds-with-noteworthy-posts/"><u>[Updated] 2024 Approved  Virality Voyage  Navigating Newsfeeds with Noteworthy Posts</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-the-ultimate-guide-to-free-filmora-no-strings-attached/"><u>New In 2024, The Ultimate Guide to Free Filmora No Strings Attached</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/uncover-earths-wonders-with-these-top-10-vids-for-2024/"><u>Uncover Earth's Wonders with These Top 10 Vids for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-lan-world-play-in-windows-mc-game/"><u>Mastering LAN World Play in Windows MC Game</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-how-to-download-gif-from-facebook-on-pc-android-and-iphone/"><u>2024 Approved  How to Download GIF From Facebook on PC, Android and iPhone</u></a></li>
<li><a href="https://windows11.techidaily.com/launching-the-system-rescue-console-easily/"><u>Launching the System Rescue Console Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-maximum-cursor-visibility-on-win-11-desktop/"><u>Unlocking Maximum Cursor Visibility on Win 11 Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-differences-of-fix-focused-tools-dism-sfc-and-chkdsk/"><u>Understanding Differences of Fix-Focused Tools: DISM, SFC & CHKDSK</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-unveiling-top-5-essential-android-photo-editing-software/"><u>In 2024, Unveiling Top 5 Essential Android Photo Editing Software</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-check-if-your-nokia-c12-is-unlocked-by-drfone-android/"><u>In 2024, How To Check if Your Nokia C12 Is Unlocked</u></a></li>
<li><a href="https://windows11.techidaily.com/flipping-a-non-working-search-bar-in-windows-11s-settings/"><u>Flipping a Non-Working Search Bar in Windows 11’S Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/analyzing-how-windows-11-fuels-microsofts-earnings/"><u>Analyzing How Windows 11 Fuels Microsoft's Earnings</u></a></li>
<li><a href="https://windows11.techidaily.com/tweaking-windows-cursor-appearance-easily/"><u>Tweaking Window's Cursor Appearance Easily</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/unleash-your-creativity-top-5-iphone-video-editing-apps-you-need-for-2024/"><u>Unleash Your Creativity Top 5 iPhone Video Editing Apps You Need for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/initiating-changes-accessing-fax-editor-in-the-newest-os/"><u>Initiating Changes: Accessing Fax Editor in the Newest OS</u></a></li>
<li><a href="https://windows11.techidaily.com/top-7-tabs-notes-that-complement-pen-tech/"><u>Top 7 Tabs: Notes That Complement Pen Tech</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-decluttering-your-w11-desktop/"><u>The Ultimate Guide to Decluttering Your W11 Desktop</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-10-oneplus-nord-n30-5g-android-sim-unlock-apk-by-drfone-android/"><u>In 2024, Top 10 OnePlus Nord N30 5G Android SIM Unlock APK</u></a></li>
<li><a href="https://apple-account.techidaily.com/turning-off-two-factor-authentication-on-apple-iphone-12-pro-5-tips-you-must-know-by-drfone-ios/"><u>Turning Off Two Factor Authentication On Apple iPhone 12 Pro? 5 Tips You Must Know</u></a></li>
<li><a href="https://windows11.techidaily.com/explore-worldwide-efficient-mouse-skills-via-powertoys/"><u>Explore Worldwide - Efficient Mouse Skills via PowerToys</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-hacks-for-identifying-windows-age/"><u>Expert Hacks for Identifying Windows Age</u></a></li>
<li><a href="https://windows11.techidaily.com/a-systematic-approach-to-fixing-the-zeroxc000003e-issue/"><u>A Systematic Approach to Fixing the ZeroXc000003e Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/whats-wrong-with-windows-modern-standby/"><u>What's Wrong with Windows Modern Standby?</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-the-ultimate-list-10-final-cut-pro-x-competitors-you-need-to-know/"><u>New The Ultimate List 10 Final Cut Pro X Competitors You Need to Know</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-from-screens-to-stories-vertical-video-mastery-with-fcpx/"><u>[New] From Screens to Stories  Vertical Video Mastery with FCPX</u></a></li>
<li><a href="https://windows11.techidaily.com/balancing-audio-dynamics-for-bluetooth-devices/"><u>Balancing Audio Dynamics for Bluetooth Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-solution-to-cease-iomap64-syscall-freezes-on-windows/"><u>Step-by-Step Solution to Cease IOMap64 Syscall Freezes on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-reinstate-normal-startup-procedure-in-outlook/"><u>Steps to Reinstate Normal Startup Procedure in Outlook</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-a-hidden-items-context-menu-option-in-windows-10-and-11/"><u>How to Add a Hidden Items Context Menu Option in Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/smart-task-management-microsofts-ai-copilot-for-windows-11-enhances-workflow/"><u>Smart Task Management: Microsoft's AI Copilot for Windows 11 Enhances Workflow</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-virtual-environments-ideal-for-windows-11-systems/"><u>Top 5 Virtual Environments Ideal for Windows 11 Systems</u></a></li>
</ul></div>
