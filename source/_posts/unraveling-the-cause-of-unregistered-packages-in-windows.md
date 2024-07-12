---
title: Unraveling the Cause of Unregistered Packages in Windows
date: 2024-07-11T22:02:06.888Z
updated: 2024-07-12T22:02:06.888Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unraveling the Cause of Unregistered Packages in Windows
excerpt: This Article Describes Unraveling the Cause of Unregistered Packages in Windows
keywords: Window Package Delivery Issues,Unlogged Parcels in Win,Tracking Missing Shipments,Windows Mail Delayed Notices,Unexpected Mail Packages,Parcel Errors WIndows,Mailbox Registration Woes
thumbnail: https://thmb.techidaily.com/b7fdec82e5e2a50f89b07a18bb64e205705f93d7819f0fe370579d848f9daaea.jpg
---

## Unraveling the Cause of Unregistered Packages in Windows

 Microsoft Photos is the default image viewer in Windows with which many users open picture files. However, some users can’t open images in Photos because of a “Package could not be registered” error. That issue arises for some Photos users when they try to open JPG or PNG images in that app.

 This is how you can fix the “Package could not be registered” error in Windows 11 and 10.

## 1\. Run the Windows Store Apps Troubleshooter

 Start your error troubleshooting with a troubleshooter for UWP apps on Microsoft Store. Windows Store Apps is a troubleshooter that could identify and resolve an issue with the Photos app. These are the steps for running that troubleshooter in Windows 11:

1. Simultaneously press the**Win + I** keyboard keys to bring up Settings.
2. Click**Troubleshoot** within the**System** tab of Settings.
3. Next, select**Other trouble-shooters** to reach the Windows troubleshooters in Settings.
4. Press the Windows Store Apps troubleshooter’s**Run** button.  
![The troubleshooters in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/other-troubleshooters-in-settings.jpg)
5. Then select to apply fixes suggested by the Windows Store App troubleshooter.  
![The Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-store-apps-troubleshooter.jpg)

 The same troubleshooter is also available within Windows 10’s Settings app. To access it, click the**Update & Security** category and**Troubleshoot** tab. Then you can select**Additional troubleshooters** to bring up the list of troubleshooting tools.

## 2\. Update Photos

 Updating Microsoft Store apps like Photos can fix issues with them. So, try updating Microsoft Photos like this:

1. Click**Start** and select Microsoft Store on that button’s menu.
2. Select Microsoft Store’s**Library** tab.
3. Click**Get updates** to see what apps need updating. MS Store will then automatically download and install an update for Photos if available.  
![The Get updates button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/get-updates-button.jpg)
4. Wait for the Photos app update to finish before closing Microsoft Store.

## 3\. Repair and Reset the Photos Apps

 Repairing or resetting Photos will likely fix the “Package could not be registered” if that app has corrupted files or data. You can select adjacent**Repair** and**Reset** troubleshooting options for Photos within Settings’ Apps & Features tool. To apply this solution, follow the instructions in our guide for [resetting Microsoft Store apps](https://www.makeuseof.com/windows-reset-app/) . Select the**Repair** option first and**Reset** second if necessary.

![The Repair and Reset buttons for Photos](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-repair-reset-buttons.jpg)

## 4\. Run the Deployment Image and System File Checker Tools

 The “Package could not be registered” error can also be due to Windows system file corruption. That much has been confirmed by users who’ve said that running Deployment Image Servicing Management and System File Checker scans fixed this issue on their PCs. You can apply this potential solution by [opening the Command Prompt with admin rights](https://www.makeuseof.com/windows-11-open-command-prompt/) and running these separate DISM and SFC commands:

`DISM.exe /Online /Cleanup-image /Restorehealth`

`sfc /scannow`

 Run the Deployment Image Servicing Management scan command before the System File Checker tool. Leave the Command Prompt open until it shows a Windows Resource Protection message for the SFC scan. If it says Windows Resource Protection repaired files, this resolution might have resolved the “Package could not be registered” error.

## 5\. Reinstall Photos

 If the “Package could not be registered” error persists after applying the resolutions above, you might need to reinstall Photos to fix it. This solution is the most likely one to fix a corrupted Photos app. You can uninstall and reinstall Photos with PowerShell like this:

1. Start PowerShell with a method in our guide to [opening PowerShell as an administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. Then input this command for uninstalling PowerShell and hit**Enter** :  
`Get-AppxPackage Microsoft.Windows.Photos | Remove-AppxPackage`  
![The uninstall Photos command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/remove-photos-command.jpg)
3. To reinstall Photos, input this PowerShell command and press**Enter** :  
`Get-AppxPackage -allusers Microsoft.Windows.Photos | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reinstall Photos app command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reinstall-photos-app.jpg)
4. Restart your PC after reinstalling Photos.

## 6\. Reset Windows

 If you’ve tried all other resolutions suggested here, there could be a deeper Windows issue causing the “Package could not be registered” Photos error. Then a system reset could be needed to remedy that deeper issue. Resetting Windows will refresh the platform’s components and restore it to a default state.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reset-this-pc-tool.jpg)

 This is suggested as a last resort because you’ll need to reinstall third-party software installed before resetting Windows. However, you can select to keep user files such as photos, documents, videos, etc. Our [guide to resetting Windows 10 and 11](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) tells you how to perform a factory reset.

## Open Your Images in Photos Again

 One of the above resolutions will likely resolve the “Package Could not be Registered” error on your Windows 11/10 PC. However, remember there are plenty of third-party app alternatives you can open your images with if that Photos error persists. IrfanView, XnView, and FastStone Image Viewer are among the best Photos alternatives that are freely available.

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
<li><a href="https://windows11.techidaily.com/bypass-script-failures-windows-script-troubleshooting-guide/"><u>Bypass Script Failures: Windows Script Troubleshooting Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/apk-quickstart-guide-for-widely-adopted-windows-11/"><u>APK Quickstart Guide for Widely-Adopted Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-folder-shuffle-showhide-system-directories/"><u>Windows 11 Folder Shuffle: Show/Hide System Directories</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/step-by-step-instructions-for-incorporating-custom-gifs-and-icons-into-your-story-posts-on-instagram-for-2024/"><u>Step-by-Step Instructions for Incorporating Custom GIFS & Icons Into Your Story Posts on Instagram for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/breaching-windows-denied-logins-with-smart-fixes/"><u>Breaching Windows' Denied Logins with Smart Fixes</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/leading-photo-and-tune-recorders-for-immersive-experience-for-2024/"><u>Leading Photo & Tune Recorders for Immersive Experience for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-excellent-mac-bandicam-substitutes-5-for-2024/"><u>[Updated] Excellent Mac Bandicam Substitutes [#5] for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-bsod-understanding-and-fixing-blue-screen/"><u>Win11 BSOD: Understanding & Fixing Blue Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/inside-outlook-and-file-explorers-new-backup-integration-in-windows-11/"><u>Inside Outlook and File Explorer's New Backup Integration in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-level-insights-into-windows-non-adjacent-partition-integration/"><u>Expert-Level Insights Into Windows Non-Adjacent Partition Integration</u></a></li>
<li><a href="https://windows11.techidaily.com/best-options-to-windows-snipper-top-5-alternative-capture-apps/"><u>Best Options to Windows Snipper: Top 5 Alternative Capture Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/delaying-windows-10-shutdown-during-running-programs/"><u>Delaying Windows 10 Shutdown During Running Programs</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/aiming-high-selecting-the-best-webcams-for-live-gameplay-streams/"><u>Aiming High  Selecting the Best Webcams for Live Gameplay Streams</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-mastering-podcast-title-craft-the-essential-handbook/"><u>2024 Approved  Mastering Podcast Title Craft  The Essential Handbook</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-navigate-and-utilize-windows-iscsi-initiator-efficiently/"><u>How to Navigate and Utilize Windows iSCSI Initiator Efficiently</u></a></li>
<li><a href="https://windows11.techidaily.com/cleanse-your-search-box-of-windows-graphics/"><u>Cleanse Your Search Box of Windows Graphics</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-how-to-flip-a-video-online-top-tools-and-tricks/"><u>Updated In 2024, How to Flip a Video Online Top Tools and Tricks</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-history-streams-that-will-transform-your-study-habits/"><u>[Updated] 2024 Approved  History Streams That Will Transform Your Study Habits</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-decision-making-with-microsofts-ai-hub/"><u>Efficient Decision-Making with Microsoft's AI Hub</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-audio-issue-methods-to-enable-automatic-system-startup/"><u>Windows Audio Issue: Methods to Enable Automatic System Startup</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/for-efficient-workflow-the-keyboard-shortcuts-cannot-be-beaten-so-here-i-list-top-20-adobe-premiere-shortcuts-you-will-use-when-editing-video/"><u>For Efficient Workflow, the Keyboard Shortcuts Cannot Be Beaten. So Here I List Top 20 Adobe Premiere Shortcuts You Will Use when Editing Video</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-resolving-windows-service-response-errors/"><u>Guide to Resolving Windows Service Response Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/bringing-lost-panes-back-top-techniques-for-windows-11/"><u>Bringing Lost Panes Back: Top Techniques for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/win-error-restoring-lost-or-absent-mfc71udll/"><u>Win Error: Restoring Lost or Absent Mfc71u.dll</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-unexpected-security-alerts/"><u>Troubleshooting Windows' Unexpected Security Alerts</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-to-windows-arp-cache-and-its-clearance-136-chars-exceeds-limit-adjusted-to-fit-better-clearing-windows-arp/"><u>Essential Guide to Windows ARP Cache and Its Clearance (136 Chars, Exceeds Limit, Adjusted to Fit Better: Clearing Windows ARP</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-and-remedying-chromes-profile-anomalies/"><u>Unraveling and Remedying Chrome's Profile Anomalies</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-methods-to-mirror-nubia-z50-ultra-to-roku-drfone-by-drfone-android/"><u>In 2024, 3 Methods to Mirror Nubia Z50 Ultra to Roku | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-forth-hidden-5ghz-lans-in-windows-11-fixes-outlined/"><u>Bring Forth Hidden 5GHz LANs in Windows 11 - Fixes Outlined</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tune-automatic-lock-settings-on-pcs/"><u>Fine-Tune Automatic Lock Settings on PCs</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-2024-approved-the-ultimate-guide-to-student-centric-historical-yt-channels/"><u>[Updated] 2024 Approved  The Ultimate Guide to Student-Centric Historical YT Channels</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-steps-restoring-light-from-dark-mode/"><u>Troubleshooting Steps: Restoring Light From Dark Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-elevate-your-old-computer-into-a-windows-11-powerhouse/"><u>How to Elevate Your Old Computer Into a Windows 11 Powerhouse</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-strategies-how-to-resolve-unison-issues-on-win11/"><u>Winning Strategies: How To Resolve Unison Issues on Win11</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-apple-iphone-15-pro-location-on-skout-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Change Apple iPhone 15 Pro Location on Skout | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/bypass-faulty-function-keys-windows-10-fix-guide/"><u>Bypass Faulty Function Keys: Windows 10 Fix Guide</u></a></li>
<li><a href="https://change-location.techidaily.com/how-can-i-catch-the-regional-pokemon-without-traveling-on-samsung-galaxy-f15-5g-drfone-by-drfone-virtual-android/"><u>How Can I Catch the Regional Pokémon without Traveling On Samsung Galaxy F15 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-the-top-5-personal-information-harvesters/"><u>Win11: The Top 5 Personal Information Harvesters</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-steps-to-clean-up-steams-networking-caches/"><u>Easy Steps to Clean Up Steam's Networking Caches</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-unleash-your-creativity-top-apple-video-editing-tools/"><u>Updated Unleash Your Creativity Top Apple Video Editing Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/winsplit-a-guide-to-overcome-display-split/"><u>WinSplit: A Guide to Overcome Display Split</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-top-tier-talk-transcribers-in-schools/"><u>[New] In 2024, Top-Tier Talk Transcribers in Schools</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-how-to-split-a-clip-in-after-effects/"><u>New How to Split a Clip in After Effects</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-opaque-windows-11-themes-via-registry-manipulation/"><u>Enabling Opaque Windows 11 Themes via Registry Manipulation</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-clutter-best-windows-apps-to-disable/"><u>Cutting Clutter: Best Windows Apps to Disable</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-11-restrictions-a-beginners-guide/"><u>Bypassing Windows 11 Restrictions: A Beginner's Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-undo-unintended-changes-to-mixer-volume-levels/"><u>How to Undo Unintended Changes to Mixer Volume Levels</u></a></li>
</ul></div>
