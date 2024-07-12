---
title: Fixing Snipping Tool Keyboard Failures on PC
date: 2024-07-11T21:51:51.844Z
updated: 2024-07-12T21:51:51.844Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Snipping Tool Keyboard Failures on PC
excerpt: This Article Describes Fixing Snipping Tool Keyboard Failures on PC
keywords: SnipTool Keyboard Fix PC,Solve PC Keyboard Snipper,Snipping Tool Input Error,Troubleshoot Snip & Paste,Fix Snipping Bug PC,Correct PC Snippet Issue,Rectify Keyboard Snipper Fail
thumbnail: https://thmb.techidaily.com/a3ff3acad952490c637c7b896fc0975ebe957935337cd7ad7a4e6125800ac957.jpg
---

## Fixing Snipping Tool Keyboard Failures on PC

 Whether you need to capture an error message or share something specific with someone, screenshots can be a lifesaver. The Win + Shift + S shortcut makes it easy to take screenshots with the Snipping Tool, but what if that shortcut stops responding?

 Is your screenshot-taking career over? Definitely not. There are still some fixes you can try to solve this issue. Read on to learn what to do when your Win + Shift + S shortcut isn't working.

## 1\. Restart the Computer

 It might sound simple, but restarting your computer often solves minor problems. This can help clear out any glitches that may prevent the shortcut from working correctly.

 To restart your computer, close any running programs. Now, open the Start menu and choose **Restart** in the list of options.

## 2\. Check Your Keyboard

 Check the keyboard for any dirt or debris that may obstruct the keys. Clean off dust, crumbs, and other particles with compressed air. Ensure that all the keys are working correctly and that none are stuck or pressed down. If the keys have been damaged or worn down, consider replacing your keyboard.

## 3\. Enable the Clipboard History

 If keyboard dirt and debris are not the issues, you may need to enable the clipboard history feature. This will help you restore any screenshots taken with Win + Shift + S that have been lost.

![Enable the Clipboard History](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/enable-the-clipboard-history.jpg)

 To enable it, open Settings and navigate to **System** \> **Clipboard**. There, you'll find the toggle for **Clipboard history** – turn it on.

 You can also use the Windows search bar to type in **Clipboard settings** and open it directly. If you prefer shortcuts, hit **Win + R** or type **ms-settings:clipboard** into Run.

## 4\. Turn on Snipping Tool Notification Toggle

 When you press Win + Shift + S on your keyboard, a notification should appear in the bottom-right corner of the screen. This notification toggle helps you quickly access screenshots taken with the shortcut.

 If you don't see a notification, that means the toggle is off, and you may need to enable it manually. Here's how to do it:

1. Right-click on Start and select **Settings**.
2. In the Settings window, navigate to **System** \> **Notifications**.
3. Under **Notifications from apps and other senders**, scroll down to the bottom and turn on the Snipping Tool notification toggle.  
![Turn on Snipping Tool Notification Toggle](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/turn-on-snipping-tool-notification-toggle.jpg)

 Once you have enabled this option, press **Win + Shift + S** to take a screenshot. If the shortcut works, you will see a notification that the screenshot is saved to the clipboard.

## 5\. Reset the Snipping Tool

 Another solution is to reset the Snipping Tool. It restores the default settings and can help if something goes wrong.

 To reset it, right-click on the **Start** menu and select **Installed apps**. Find **Snipping Tool** in the list, click three dots, and select **Advanced options**.

 You can also use **Win + R** or type **ms-settings:appsfeatures** in the Run dialog box to open Installed apps. From there, you can find the Advanced options for the Snipping Tool.

![Reset Snipping Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-snipping-tool.jpg)

 On the next page, scroll down to the **Reset** section. Select **Reset** and then click on **Reset** again in the confirmation popup. After resetting the Snipping Tool, check if the Win + Shift + S shortcut works.

## 6\. Reinstall the Snipping Tool

 If resetting doesn't solve the problem, try reinstalling the Snipping Tool. It will resolve any issues you may have with your current installation.

 To reinstall the Snipping Tool, open the System Settings. Select **Apps** \> **Installed apps**, then find and select **Snipping Tool** from the list of installed programs.

![Reset the Snipping Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-the-snipping-tool.jpg)

 Click the three dots and select **Uninstall**. Now follow the on-screen instructions to complete the process. Once done, download and install a new version of the Snipping Tool from the Microsoft Store app.

## 7\. Turn on Windows Hotkeys

 If your Windows hotkeys are disabled for some reason, the shortcut keys will not work. In such cases, you will need to enable the Windows hotkeys through the group policy editor. Here's how to do it:

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **gpedit.msc** in the dialog box and hit Enter. This will open the Group Policy Editor window.  
![Turn on Windows Hotkeys Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/turn-on-windows-hotkeys-using-group-policy.jpg)
3. Navigate to the path:  
`User Configuration > Administrative Templates > Windows Components > File Explorer`
4. In the right pane, double-click on the **Turn off Windows Key hotkeys** option.
5. Select Enabled in the settings window and click **Apply** \> **OK**.

 After making these changes, try taking a screenshot with Win + Shift + S shortcut. It should work now.

 One thing to remember is that this method will only work with Windows Pro and Enterprise editions. If you have the Home edition, you can't access the Group Policy Editor. In such a case, you'll need to [enable the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). But if that sounds complicated, skip this method and use the Registry Editor instead.

 To enable Windows Hotkeys through the Registry Editor, follow these steps:

* Click on Start, type **regedit**, and hit **Enter**.
* If the UAC window pops up, click Yes to open the registry editor.  
`Navigate to HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer`
* If you don't see the Explorer folder, right-click on **Policies** and select **New > Key**. Name the newly created key **Explorer**.
* Now right-click on **Explorer** and select **New** \> **DWORD 32-bit**.
* Name the DWORD **NoWinKeys**.
* Double-click on **NoWinKeys** and set the value data to **0**.  
![Turn on Windows Hotkeys Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/turn-on-windows-hotkeys-using-registry.jpg)
* Select Base as **Hexadecimal** and click **OK** to save the changes.

 After that, exit the registry editor and restart your computer. Once the system reboots, check if the issue has been resolved.

## 8\. Perform Some Generic Fixes

 There are a few general fixes that might help you get the Win + Shift + S keyboard shortcut working. Here's what you need to do:

1. Check the keyboard driver status and update it if needed.
2. Try [running the SFC utility](https://www.makeuseof.com/windows-built-in-repair-tools/) to fix corrupted system files.
3. Make sure you are [running the latest version of Windows](https://www.makeuseof.com/update-windows-manually/).
4. [Run a full scan with your antivirus program](https://www.makeuseof.com/scan-for-viruses-without-buying-antivirus-software/) and see if it solves the issue.
5. If the issue still persists, there's a chance that third-party applications are interfering with the Snipping Tool shortcut. In such a case, [try performing a clean boot](https://www.makeuseof.com/clean-boot-windows-11/). This will temporarily disable all the third-party applications and allow you to check if they were causing the issue.

## Taking Screenshots Is Easy With Shortcut Keys

 Keyboard shortcuts provide quick and easy access to different functions on your PC. It allows you to easily switch between applications and perform tasks. There are times, though, when the Win + Shift + S hotkey does not work properly. Hopefully, one of the above methods fixed this issue for you.

 Is your screenshot-taking career over? Definitely not. There are still some fixes you can try to solve this issue. Read on to learn what to do when your Win + Shift + S shortcut isn't working.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/command-guide-win11-starting-high-privilege-powershell/"><u>Command Guide: Win11 - Starting High-Privilege PowerShell</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-network-overview-understanding-arp-caches/"><u>Windows Network Overview: Understanding ARP Caches</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-in-2024-how-to-create-the-best-video-collages/"><u>New In 2024, How to Create The Best Video Collages ?</u></a></li>
<li><a href="https://windows11.techidaily.com/1719290153300-quick-fix-guide-resurrect-your-chrome-browser-in-w11/"><u>Quick Fix Guide: Resurrect Your Chrome Browser in W11.</u></a></li>
<li><a href="https://windows11.techidaily.com/best-practices-for-avoidable-file-explorer-foibles/"><u>Best Practices for Avoidable File Explorer Foibles</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-desk-icons-clashing-find-harmony/"><u>Windows Desk Icons Clashing - Find Harmony!</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-asymmetric-windows-headphone-output/"><u>Adjusting Asymmetric Windows Headphone Output</u></a></li>
<li><a href="https://windows11.techidaily.com/10-tips-to-restore-bluetooth-functionality-on-windows-11/"><u>10 Tips to Restore Bluetooth Functionality on Windows 11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-professional-edge-with-free-best-premiere-pro-resources/"><u>2024 Approved  Professional Edge with FREE, Best Premiere Pro Resources</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-windows-11-performance-tweak-ntfs-file-compression/"><u>Enhance Windows 11 Performance: Tweak NTFS File Compression</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-silencing-the-singers-10-high-quality-audio-programs-to-minimize-vocal-interference-in-studio-setups/"><u>New Silencing the Singers 10 High-Quality Audio Programs to Minimize Vocal Interference in Studio Setups</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-fbm-issues-on-your-pc-screen/"><u>Unblocking FBM Issues on Your PC Screen</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/ethical-implications-recording-whatsapp-calls-responsibly/"><u>Ethical Implications  Recording WhatsApp Calls Responsibly</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-reimagined-analyzing-the-core-upgrades-of-windows-11/"><u>Windows Reimagined: Analyzing the Core Upgrades of Windows 11</u></a></li>
<li><a href="https://screen-capture.techidaily.com/live-action-sims-perfecting-your-videos/"><u>Live-Action Sims  Perfecting Your Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/unfreezing-windows-updates-top-6-strategies-to-resolve-sticking-issues/"><u>Unfreezing Windows Updates: Top 6 Strategies to Resolve Sticking Issues</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-t-open-mov-files-on-samsung-galaxy-a14-4g-by-aiseesoft-video-converter-play-mov-on-android/"><u>Can't open MOV files on Samsung Galaxy A14 4G</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fake-the-location-to-get-around-the-mlb-blackouts-on-poco-c65-drfone-by-drfone-virtual-android/"><u>In 2024, Fake the Location to Get Around the MLB Blackouts on Poco C65 | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-power-players-list-top-trending-gadgets-and-tools-every-profession-should-have/"><u>2024 Approved  Power Players List  Top Trending Gadgets & Tools Every Profession Should Have</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-full-gpu-potential-in-windows-10-and-11-via-vram/"><u>Unleashing Full GPU Potential in Windows 10 & 11 via VRAM</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-access-to-windows-print-services-dashboard/"><u>Demystifying Access to Windows Print Services Dashboard</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-admin-error-for-apps/"><u>Bypassing Windows Admin Error for Apps</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-ios-of-apple-iphone-15-plus-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair iOS of Apple iPhone 15 Plus? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-turn-off-google-location-to-stop-tracking-you-on-oneplus-ace-2-drfone-by-drfone-virtual-android/"><u>How to Turn Off Google Location to Stop Tracking You on OnePlus Ace 2 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-edge-how-pcs-beat-macs-in-9-aspects/"><u>Decoding the Edge: How PCs Beat Macs in 9 Aspects</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-sony-s6500-blu-ray-reader-an-updated-analysis/"><u>[New] Sony S6500 Blu-Ray Reader  An Updated Analysis</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-how-to-archive-video-team-hangouts-effectively/"><u>2024 Approved  How to Archive Video Team Hangouts Effectively</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-in-2024-50plus-tiktok-quotes-to-inspire-you-and-make-videos-go-viral/"><u>[Updated] In 2024, 50+ TikTok Quotes to Inspire You and Make Videos Go Viral</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-the-ultimate-playbook-techniques-to-archive-your-unique-vr-adventures/"><u>[Updated] In 2024, The Ultimate Playbook  Techniques to Archive Your Unique VR Adventures</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-unlocking-windows-11-your-ultimate-cheat-sheet/"><u>In 2024, Unlocking Windows 11  Your Ultimate Cheat Sheet</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-your-window-preferences-on-win11/"><u>Customize Your Window Preferences on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/choosing-a-fresh-pdf-file-reader-for-os-use/"><u>Choosing a Fresh PDF File Reader for OS Use</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-icon-organization-made-simple/"><u>Windows Icon Organization Made Simple</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-boosted-audio-visual-experience-choose-av1-on-youtube/"><u>[New] In 2024, Boosted Audio-Visual Experience  Choose AV1 on YouTube</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-5-winter-youtube-background-ideas-to-warm-up-your-videos/"><u>[New] 5 Winter YouTube Background Ideas to Warm Up Your Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/win-1011-printer-uninstallation-a-quick-and-direct-guide/"><u>Win 10/11 Printer Uninstallation: A Quick & Direct Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-of-windows-law-filter-mechanics-and-output/"><u>Unraveling the Mystery of Window's LAW Filter Mechanics and Output</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-content-creation-hacks-for-rapid-youtubers-growth/"><u>2024 Approved  Content Creation Hacks for Rapid Youtubers' Growth</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-15-diy-music-production-tutorial-videos-for-home-studios/"><u>[New] In 2024, 15 DIY Music Production Tutorial Videos for Home Studios</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-changefake-your-tecno-spark-10-pro-location-on-viber-drfone-by-drfone-virtual-android/"><u>How to Change/Fake Your Tecno Spark 10 Pro Location on Viber | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/samsung-galaxy-s24-ultra-not-receiving-texts-10-hassle-free-solutions-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Samsung Galaxy S24 Ultra Not Receiving Texts? 10 Hassle-Free Solutions Here | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/automate-email-attachment-openness-ms-word-read-mode-only/"><u>Automate Email Attachment Openness: MS Word Read Mode Only</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-elevate-your-online-communication-the-best-skype-voice-changing-technologies/"><u>In 2024, Elevate Your Online Communication The Best Skype Voice Changing Technologies</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-failed-speech-recognition-startup-error-windows/"><u>Addressing 'Failed' Speech Recognition Startup Error Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/a-curated-list-of-6-essential-android-apps-for-windows-11-users/"><u>A Curated List of 6 Essential Android Apps for Windows 11 Users</u></a></li>
<li><a href="https://change-location.techidaily.com/hacks-to-do-pokemon-go-trainer-battles-for-vivo-y200e-5g-drfone-by-drfone-virtual-android/"><u>Hacks to do pokemon go trainer battles For Vivo Y200e 5G | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-mastering-the-art-of-video-discovery-on-facebook/"><u>2024 Approved  Mastering the Art of Video Discovery on Facebook</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-windows-activate-derailed-handbrake/"><u>Conquer Windows: Activate Derailed HandBrake</u></a></li>
</ul></div>
