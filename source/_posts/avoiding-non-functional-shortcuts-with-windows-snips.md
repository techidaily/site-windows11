---
title: Avoiding Non-Functional Shortcuts with Windows Snips
date: 2024-07-11T21:35:49.928Z
updated: 2024-07-12T21:35:49.928Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Avoiding Non-Functional Shortcuts with Windows Snips
excerpt: This Article Describes Avoiding Non-Functional Shortcuts with Windows Snips
keywords: Avoid Non-FunctSnipss,SnipsWindowsShortCut,FunctionalSnipsUse,SnipOptimizationWin,WinSnipsEfficiency,SkipNonFunctSnip,EfficientSnipTechWin
thumbnail: https://thmb.techidaily.com/10c291d26c69b79184acc714bd905fecf227774d1628ff4b17b2024d943bf02d.jpg
---

## Avoiding Non-Functional Shortcuts with Windows Snips

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
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-tiktok-to-see-more-content-on-your-lava-blaze-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Location on TikTok to See More Content On your Lava Blaze Pro 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/bypass-script-failures-windows-script-troubleshooting-guide/"><u>Bypass Script Failures: Windows Script Troubleshooting Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-opaque-windows-11-themes-via-registry-manipulation/"><u>Enabling Opaque Windows 11 Themes via Registry Manipulation</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-change-credit-card-from-your-iphone-13-apple-id-and-apple-pay-by-drfone-ios/"><u>In 2024, How to Change Credit Card from Your iPhone 13 Apple ID and Apple Pay</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-undo-unintended-changes-to-mixer-volume-levels/"><u>How to Undo Unintended Changes to Mixer Volume Levels</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-visualizer-screen-recorder-3000/"><u>[New] Visualizer Screen Recorder 3000</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/mindful-moments-elite-yoga-routines-for-serenity/"><u>Mindful Moments  Elite Yoga Routines for Serenity</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-score-selection-service-enhancing-media-pieces/"><u>[Updated] Score Selection Service  Enhancing Media Pieces</u></a></li>
<li><a href="https://windows11.techidaily.com/keeping-your-win11-devices-running-smoothly-check-list-5/"><u>Keeping Your Win11 Devices Running Smoothly - Check List #5</u></a></li>
<li><a href="https://windows11.techidaily.com/iphoneandroid-as-windows-microphones-guide/"><u>IPhone/Android as Windows Microphones Guide</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-acclaimed-creators-superior-insta-hlv-page-builders/"><u>[Updated] Acclaimed Creators  Superior Insta HLV Page Builders</u></a></li>
<li><a href="https://windows11.techidaily.com/cleanse-your-search-box-of-windows-graphics/"><u>Cleanse Your Search Box of Windows Graphics</u></a></li>
<li><a href="https://windows11.techidaily.com/bringing-lost-panes-back-top-techniques-for-windows-11/"><u>Bringing Lost Panes Back: Top Techniques for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-bsod-understanding-and-fixing-blue-screen/"><u>Win11 BSOD: Understanding & Fixing Blue Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/bypass-faulty-function-keys-windows-10-fix-guide/"><u>Bypass Faulty Function Keys: Windows 10 Fix Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-navigate-and-utilize-windows-iscsi-initiator-efficiently/"><u>How to Navigate and Utilize Windows iSCSI Initiator Efficiently</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-decision-making-with-microsofts-ai-hub/"><u>Efficient Decision-Making with Microsoft's AI Hub</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-forth-hidden-5ghz-lans-in-windows-11-fixes-outlined/"><u>Bring Forth Hidden 5GHz LANs in Windows 11 - Fixes Outlined</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-windows-crash-0x800f0831-solution/"><u>Mastery Over Windows Crash: 0X800f0831 Solution</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-premier-game-viewing-platforms/"><u>[Updated] 2024 Approved  Premier Game Viewing Platforms</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-elevate-your-old-computer-into-a-windows-11-powerhouse/"><u>How to Elevate Your Old Computer Into a Windows 11 Powerhouse</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-clutter-best-windows-apps-to-disable/"><u>Cutting Clutter: Best Windows Apps to Disable</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-unlock-the-power-of-live-broadcasting-with-tiktok-from-pc-for-2024/"><u>[New] Unlock the Power of Live Broadcasting with TikTok From PC for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-resolving-windows-service-response-errors/"><u>Guide to Resolving Windows Service Response Errors</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-mastering-video-upload-your-guide-to-igtv/"><u>[New] 2024 Approved  Mastering Video Upload  Your Guide to IGTV</u></a></li>
<li><a href="https://windows11.techidaily.com/delaying-windows-10-shutdown-during-running-programs/"><u>Delaying Windows 10 Shutdown During Running Programs</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-reset-a-locked-vivo-y100-phone-by-drfone-android/"><u>In 2024, How to Reset a Locked Vivo Y100 Phone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-the-ultimate-guide-to-selecting-frame-rate-for-hd-recording/"><u>[Updated] 2024 Approved  The Ultimate Guide to Selecting Frame Rate for HD Recording</u></a></li>
<li><a href="https://windows11.techidaily.com/best-options-to-windows-snipper-top-5-alternative-capture-apps/"><u>Best Options to Windows Snipper: Top 5 Alternative Capture Apps</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updating-facebook-video-coverage-with-ease/"><u>Updating Facebook Video Coverage with Ease</u></a></li>
<li><a href="https://apple-account.techidaily.com/turning-off-two-factor-authentication-on-iphone-15-pro-5-tips-you-must-know-by-drfone-ios/"><u>Turning Off Two Factor Authentication On iPhone 15 Pro? 5 Tips You Must Know</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-a-beginners-guide-to-youtube-seo-keywords/"><u>[New] A Beginner's Guide to YouTube SEO Keywords</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-steps-to-clean-up-steams-networking-caches/"><u>Easy Steps to Clean Up Steam's Networking Caches</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-pixels-to-perfection-design-tips-for-captivating-banners/"><u>2024 Approved  Pixels to Perfection  Design Tips for Captivating Banners</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-access-steps-for-unlocking-windows-hidden-char-personality-tracker/"><u>Mastering Access: Steps for Unlocking Windows' Hidden Char Personality Tracker</u></a></li>
<li><a href="https://fox-access.techidaily.com/dji-mavic-pro-review-a-new-era-of-aerial-photography/"><u>DJI Mavic Pro Review  A New Era of Aerial Photography</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tune-automatic-lock-settings-on-pcs/"><u>Fine-Tune Automatic Lock Settings on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/breaching-windows-denied-logins-with-smart-fixes/"><u>Breaching Windows' Denied Logins with Smart Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/winsplit-a-guide-to-overcome-display-split/"><u>WinSplit: A Guide to Overcome Display Split</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-11-restrictions-a-beginners-guide/"><u>Bypassing Windows 11 Restrictions: A Beginner's Guide</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-depth-guide-to-2023s-leading-web-capture-applications/"><u>[New] In-Depth Guide to 2023’S Leading Web Capture Applications</u></a></li>
<li><a href="https://windows11.techidaily.com/localize-onedrive-a-step-by-step-windows-approach/"><u>Localize OneDrive: A Step-by-Step Windows Approach</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-download-your-favorite-videos-without-limits/"><u>[New] Download Your Favorite Videos Without Limits</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-exclusive-webcast-winners/"><u>In 2024, Exclusive Webcast Winners</u></a></li>
<li><a href="https://windows11.techidaily.com/win-error-restoring-lost-or-absent-mfc71udll/"><u>Win Error: Restoring Lost or Absent Mfc71u.dll</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-folder-shuffle-showhide-system-directories/"><u>Windows 11 Folder Shuffle: Show/Hide System Directories</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-zte-axon-40-lite-phone-without-password-by-drfone-android/"><u>In 2024, How To Unlock ZTE Axon 40 Lite Phone Without Password?</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-pro-free-mac-screen-logger/"><u>[New] Pro-Free Mac Screen Logger</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-level-insights-into-windows-non-adjacent-partition-integration/"><u>Expert-Level Insights Into Windows Non-Adjacent Partition Integration</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-audio-issue-methods-to-enable-automatic-system-startup/"><u>Windows Audio Issue: Methods to Enable Automatic System Startup</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-2024-approved-unlock-fcp-x-pro-level-green-screen-editing-techniques/"><u>New 2024 Approved Unlock FCP X Pro-Level Green Screen Editing Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/inside-outlook-and-file-explorers-new-backup-integration-in-windows-11/"><u>Inside Outlook and File Explorer's New Backup Integration in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-cr2-to-jpg-conversion-using-windows-tools/"><u>Mastering the Art of CR2 to JPG Conversion Using Windows Tools</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-streamlinedprocess-for-youcamwebrecord/"><u>2024 Approved  StreamlinedProcess for YouCamWebRecord</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-boost-your-tiktok-footprint-top-analytics-strategies-reviewed/"><u>[New] In 2024, Boost Your TikTok Footprint  Top Analytics Strategies Reviewed</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-the-top-5-personal-information-harvesters/"><u>Win11: The Top 5 Personal Information Harvesters</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-flip-and-rotate-iphone-videos-with-ease-top-free-apps/"><u>Updated Flip and Rotate iPhone Videos with Ease Top Free Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-strategies-how-to-resolve-unison-issues-on-win11/"><u>Winning Strategies: How To Resolve Unison Issues on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/monitoring-for-failed-windows-logins-a-security-checkers-guide/"><u>Monitoring for Failed Windows Logins: A Security Checker's Guide</u></a></li>
<li><a href="https://extra-hints.techidaily.com/mastering-podcast-dialogue-tips-and-practical-script-examples/"><u>Mastering Podcast Dialogue  Tips & Practical Script Examples</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-to-windows-arp-cache-and-its-clearance-136-chars-exceeds-limit-adjusted-to-fit-better-clearing-windows-arp/"><u>Essential Guide to Windows ARP Cache and Its Clearance (136 Chars, Exceeds Limit, Adjusted to Fit Better: Clearing Windows ARP</u></a></li>
<li><a href="https://windows11.techidaily.com/apk-quickstart-guide-for-widely-adopted-windows-11/"><u>APK Quickstart Guide for Widely-Adopted Windows 11</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-complete-tiktok-termination-protocol-unveiled-for-2024/"><u>[Updated] Complete TikTok Termination Protocol Unveiled for 2024</u></a></li>
</ul></div>
