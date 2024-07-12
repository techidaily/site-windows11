---
title: 3 Simple Methods for Identifying Windows RAM
date: 2024-07-11T21:14:43.486Z
updated: 2024-07-12T21:14:43.486Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 3 Simple Methods for Identifying Windows RAM
excerpt: This Article Describes 3 Simple Methods for Identifying Windows RAM
keywords: Windows Memory Test,RAM Detection Tips,RAM Quality Check,Detecting Windows RAM,RAM Performance Guide,Simple RAM Verify,Identify Windows RAM
thumbnail: https://thmb.techidaily.com/700293ffdf9a4730d9df7fa5093979f42d9fa58b0347dc31082bc6c29ca2c642.jpg
---

## 3 Simple Methods for Identifying Windows RAM

 Knowing the type of RAM installed on your Windows PC can help you make more informed decisions when upgrading or diagnosing performance issues. Thankfully, it’s possible to check the RAM type on your Windows PC without opening the computer case and getting your hands dirty.

 This guide will walk you through some easy methods for identifying the type of RAM housed within your computer.

## 1\. How to Check the RAM Type With Command Prompt

 The most straightforward to check the RAM type on your Windows PC is via Command Prompt. You can use this method even [if you're a beginner with the Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/), as it only requires you to run a single command.

 Here's how you can check the RAM type on Windows using the Command Prompt:

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the menu that appears.
2. Select **Yes** when the User Account Control (UAC) prompt appears.
3. In the console, type the command mentioned below and press **Enter**.  
`wmic memorychip get devicelocator, memorytype`
4. Note down the code number under the **MemoryType** column.  
![Check Memory Type Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-memory-type-using-command-prompt.jpg)

 Compare the numerical value from the **MemoryType** column with the following table to identify the RAM type. For instance, if the code number is **24**, it means your computer has **DDR3** RAM.

![A Table Showing RAM Type and Numeric Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/a-table-showing-ram-type-and-numeric-value.jpg)

## 2\. How to Check the RAM Type With PowerShell

 Like Command Prompt, you can use PowerShell to find out the type of RAM installed on your Windows computer. Here are the steps for the same.

1. Press **Win + S** to open the search menu.
2. Type **powershell** in the box.
3. Select **Run as administrator**.
4. When the User Account Control (UAC) prompt appears, select **Yes** to continue.
5. Type the following command in the PowerShell window and hit **Enter**.  
`Get-CimInstance -ClassName Win32_PhysicalMemory | Format-Table SMBIOSMemoryType`  
![Check RAM Type Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-ram-type-using-powershell.jpg)

 Under the **SMBIOSMemoryType** column, note down the code number and compare it with the following table to determine the RAM type.

![A Table Showing RAM Type and Numeric Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/a-table-showing-ram-type-and-numeric-value.jpg)

## 3\. How to Check the RAM Type Using the Task Manager App

 Windows Task Manager can provide you with all the necessary hardware information you need about your PC, including the type of RAM installed. However, it's important to note that Task Manager does not show the memory type if your PC has [DDR4 or DDR5 RAM](https://www.makeuseof.com/ddr4-vs-ddr5-should-you-upgrade/). So, this method will only work for PCs with DDR3 or lower-generation RAM.

 To check the RAM type using Windows Task Manager, follow these steps:

1. Press **Ctrl + Shift + Esc** to open the Task Manager.
2. Switch to the **Performance** tab.
3. Select **Memory** from the left pane. You should see the amount and type of RAM your PC has in the top right corner of the screen.  
![Check Memory Type Using Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-memory-type-using-windows-task-manager.jpg)

 The Windows Task Manager does more than show hardware information. You also use it to manage running programs, end tasks, and view resource usage. To learn more, read our guide on the best [Windows Task Manager tips that you may not know](https://www.makeuseof.com/tag/10-windows-task-manager-tricks-didnt-know/).

## 4\. How to Check the RAM Type Using CPU-Z

 If you're seeking a relatively uncomplicated method to check the RAM type along with other hardware details, you can use a third-party app like CPU-Z. It is available for free and allows you to access various sets of information about your computer, including details about both the CPU and the RAM.

 Download and open the [CPU-Z](https://www.cpuid.com/softwares/cpu-z.html) app on your PC. Click on the **Memory** tab to get a detailed breakdown of the installed RAM. Under the **General** section, look for the value in the **Type** field to know the type of RAM installed on your PC.

![Check Memory Type Using CPU-Z App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-memory-type-using-cpu-z-app.jpg)

## Know the Type of RAM Installed on Your Windows PC

 The performance of your computer is affected not only by the amount of RAM installed but also by the type of RAM. Fortunately, identifying the RAM type on your Windows PC is a quick and painless process with the methods mentioned above.

 This guide will walk you through some easy methods for identifying the type of RAM housed within your computer.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-resources.techidaily.com/turn-template-ideas-into-real-logo-artwork/"><u>Turn Template Ideas Into Real Logo Artwork</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-resolving-unresponsiveness-in-your-windows-downloads-hub/"><u>Tips for Resolving Unresponsiveness in Your Windows Downloads Hub</u></a></li>
<li><a href="https://article-tips.techidaily.com/in-2024-pioneers-of-haptic-technology-unveiled/"><u>In 2024, Pioneers of Haptic Technology Unveiled</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-step-by-step-guide-quick-vlog-content-ideas/"><u>2024 Approved  Step-by-Step Guide  Quick Vlog Content Ideas</u></a></li>
<li><a href="https://extra-information.techidaily.com/adding-apple-music-a-guide-to-enhanced-videos/"><u>Adding Apple Music  A Guide to Enhanced Videos</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-boosting-engagement-navigate-to-these-8-best-apps-for-post-timers-for-2024/"><u>[New] Boosting Engagement  Navigate to These 8 Best Apps for Post Timers for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-driving-growth-with-metaverse-marketing-excellence/"><u>[New] Driving Growth with Metaverse Marketing Excellence</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-to-tackling-error-1053-unresponsive-windows-services/"><u>Quick Guide to Tackling Error 1053: Unresponsive Windows Services</u></a></li>
<li><a href="https://windows11.techidaily.com/speeding-up-typing-typingaids-expertise/"><u>Speeding Up Typing: TypingAid's Expertise</u></a></li>
<li><a href="https://vp-tips.techidaily.com/unlock-flawless-selfies-with-these-top-iphone-free-tools/"><u>Unlock Flawless Selfies with These Top iPhone Free Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-failed-zip-file-extraction-in-windows-11/"><u>Troubleshooting Failed: Zip File Extraction in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-strategy-enhancing-hard-drive-performance/"><u>Win11 Strategy: Enhancing Hard Drive Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-unstartable-windows-vms-with-vmware/"><u>Solutions for Unstartable Windows VMs with VMware</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-techniques-boosting-your-virtual-memory-in-windows-11/"><u>The Essential Techniques: Boosting Your Virtual Memory in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-hidden-dangers-in-bot-made-win-11-codes/"><u>The Hidden Dangers in Bot-Made Win 11 Codes</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-honor-play-7t-drfone-by-drfone-virtual-android/"><u>In 2024, How to get the dragon scale and evolution-enabled pokemon On Honor Play 7T? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-7-phone-number-locators-to-track-oneplus-nord-n30-5g-location-drfone-by-drfone-virtual-android/"><u>In 2024, Top 7 Phone Number Locators To Track OnePlus Nord N30 5G Location | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-reset-a-oppo-f23-5g-phone-that-is-locked-by-drfone-android/"><u>How to Reset a Oppo F23 5G Phone that is Locked?</u></a></li>
<li><a href="https://some-techniques.techidaily.com/gopro-hero5-black-secrets-elevating-your-cinematic-craft-for-2024/"><u>GoPro Hero5 Black Secrets  Elevating Your Cinematic Craft for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-windows-activation-flaw-error-0x803f700f/"><u>Remedying Windows Activation Flaw: Error 0X803F700F</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/what-to-do-if-your-iphone-14-has-bad-esn-or-blacklisted-imei-by-drfone-ios/"><u>What to do if your iPhone 14 has bad ESN or blacklisted IMEI?</u></a></li>
<li><a href="https://windows11.techidaily.com/reboot-to-reconnect-reviving-ethernet-net-access/"><u>Reboot to Reconnect: Reviving Ethernet Net Access</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-11s-registry-a-guide-to-its-components/"><u>Unveiling Windows 11'S Registry: A Guide to Its Components</u></a></li>
<li><a href="https://windows11.techidaily.com/reactivate-quieted-slack-feedback-in-win-11-systems/"><u>Reactivate Quieted Slack Feedback in Win 11 Systems</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/crafting-impactful-youtube-channel-logo-tips-for-2024/"><u>Crafting Impactful YouTube Channel Logo Tips for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/taskbar-timeline-microsofts-ui-evolution/"><u>Taskbar Timeline: Microsoft's UI Evolution</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionizing-ui-adding-cli-functionality-to-taskmgr-in-win11/"><u>Revolutionizing UI: Adding CLI Functionality to TaskMgr in Win11</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-stability-secrets-for-dynamic-photo-shoots/"><u>In 2024, Stability Secrets for Dynamic Photo Shoots</u></a></li>
<li><a href="https://windows11.techidaily.com/unfolding-wxpxo11-dilemnas-fixes-for-non-openable-folders-after-double-clicks/"><u>Unfolding WXP/XO11 Dilemnas: Fixes for Non-Openable Folders After Double-Clicks</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-the-stalled-windows-system-insight/"><u>Troubleshooting the Stalled Windows System Insight</u></a></li>
<li><a href="https://windows11.techidaily.com/prevent-chrome-from-saving-webp-images-in-windows/"><u>Prevent Chrome From Saving WebP Images in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/verify-the-validity-three-ways-to-check-windows-11/"><u>Verify the Validity: Three Ways to Check Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcome-apex-crashes-essential-steps-for-windows-11-gamers/"><u>Overcome Apex Crashes: Essential Steps for Windows 11 Gamers</u></a></li>
<li><a href="https://windows11.techidaily.com/stepwise-strategy-for-full-removal-of-wsl-on-windows-11/"><u>Stepwise Strategy for Full Removal of WSL on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/upgrade-your-win11s-connectivity-with-these-high-priority-solutions/"><u>Upgrade Your Win11's Connectivity with These High-Priority Solutions</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-ultimate-blueprint-for-transferring-large-videos-between-apple-devices/"><u>[Updated] The Ultimate Blueprint for Transferring Large Videos Between Apple Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-disconnect-untrusted-users-from-windows-11/"><u>Techniques to Disconnect Untrusted Users From Windows 11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-10-best-youtube-keyword-tools-to-get-more-views-filmora/"><u>[New] 10 Best YouTube Keyword Tools to Get More Views - Filmora</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-detailed-tutorial-to-rotate-videos-in-cyberlink-powerdirector/"><u>New Detailed Tutorial to Rotate Videos in Cyberlink PowerDirector</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/masterfb-mp4-the-ultimate-downloader-for-vids-for-2024/"><u>MasterFB-MP4  The Ultimate Downloader for Vids for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/perfecting-the-art-shrink-or-enlarge-apps-using-shortcut-on-win11/"><u>Perfecting the Art: Shrink or Enlarge Apps Using Shortcut on Win11</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-4k-perfection-the-most-jaw-dropping-video-samples-out-there-for-2024/"><u>New 4K Perfection The Most Jaw-Dropping Video Samples Out There for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-integration-effortlessly-managing-tabs-in-windows-11/"><u>Seamless Integration: Effortlessly Managing Tabs in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-printer-busy-errors-on-pcs/"><u>Troubleshooting Printer Busy Errors on PCs</u></a></li>
<li><a href="https://location-fake.techidaily.com/6-ways-to-change-spotify-location-on-your-vivo-v30-pro-drfone-by-drfone-virtual-android/"><u>6 Ways to Change Spotify Location On Your Vivo V30 Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/reduce-clutter-increase-efficiency-one-antivirus-rule/"><u>Reduce Clutter, Increase Efficiency: One Antivirus Rule!</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-program-use-in-windows-via-right-click-options/"><u>Optimizing Program Use in Windows via Right-Click Options</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-boosting-photo-skills-speed-and-simplicity-with-windows-10-paint-app/"><u>[Updated] In 2024, Boosting Photo Skills  Speed & Simplicity with Windows 10 Paint App</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/legends-of-warfare-the-top-7-total-war-game-series-for-2024/"><u>Legends of Warfare  The Top 7 Total War Game Series for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-the-definitive-manual-for-windows-10-perfecting-your-audio-recordings/"><u>New 2024 Approved The Definitive Manual for Windows 10 Perfecting Your Audio Recordings</u></a></li>
<li><a href="https://windows11.techidaily.com/redefine-reviving-with-modern-os-alternatives/"><u>Redefine Reviving with Modern OS Alternatives</u></a></li>
<li><a href="https://windows11.techidaily.com/the-shortcut-pathways-for-windows-starters/"><u>The Shortcut Pathways for Windows Starters</u></a></li>
<li><a href="https://windows11.techidaily.com/reverting-back-to-legacy-window-explorer/"><u>Reverting Back to Legacy Window Explorer</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-premium-zero-cost-switch-gaming-experience/"><u>[New] Premium Zero Cost Switch Gaming Experience</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-first-impressions-intova-x-in-the-spotlight/"><u>[Updated] First Impressions  Intova X in the Spotlight</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-from-beginner-to-pro-final-cut-pro-tutorials-for-2024/"><u>Updated From Beginner to Pro Final Cut Pro Tutorials for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-recovery-overcoming-black-screen-issues-in-wins/"><u>Swift Recovery: Overcoming Black-Screen Issues in Wins</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/5-ways-to-track-apple-iphone-x-without-app-drfone-by-drfone-virtual-ios/"><u>5 Ways to Track Apple iPhone X without App | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-lightning-fast-instagram-videos-tips-for-mobile-users/"><u>[Updated] Lightning-Fast Instagram Videos  Tips for Mobile Users</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/elite-photo-backup-networks/"><u>Elite Photo Backup Networks</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-the-screens-sole-contender-software-or-hardware-triumph/"><u>In 2024, The Screen's Sole Contender  Software or Hardware Triumph?</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-broadcasting-with-ease-screen-sharing-techniques-for-facebook/"><u>[Updated] 2024 Approved  Broadcasting with Ease  Screen Sharing Techniques for Facebook</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-for-no-sound-when-screencasting-with-powerpoint/"><u>Troubleshooting for No Sound when Screencasting with PowerPoint</u></a></li>
</ul></div>
