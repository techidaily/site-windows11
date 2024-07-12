---
title: Bringing Windows Backups Back to Basics
date: 2024-07-11T22:20:21.612Z
updated: 2024-07-12T22:20:21.612Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Bringing Windows Backups Back to Basics
excerpt: This Article Describes Bringing Windows Backups Back to Basics
keywords: Basic WinBackup Tips,Essential Windows Backup Guide,Fundamentals of WinBackup,Simplifying WinBackup Process,WinBackup Recovery Basics,Easy WinBackup Techniques,Restoring with Simple WinBackup
thumbnail: https://thmb.techidaily.com/c773b247e1e0895c35ac3965c0957524900af663f812d6e184693495dab0728b.jpg
---

## Bringing Windows Backups Back to Basics

 System failure or data loss can cause huge amounts of damage and that’s why Windows offers a backup feature to protect your critical data. If your backups corrupt or otherwise function incorrectly, you can reset Windows Backup to its default settings. This guide will teach you some methods to reset Windows Backup to its default on Windows.

## How Do I Know if I Need to Reset Windows Backup?

 You may need to reset Windows Backup if your backups aren't working, taking too long to create, or you can't access the stored files. If you are experiencing these issues, resetting Windows Backup may resolve them.

 For this, either use the Command Prompt or create a batch file. The steps for both methods are outlined below and should help you get your backups running again.

## Is Resetting Window Backup Risky?

 While resetting Windows Backup is generally safe, there are some risks associated with it.

 Firstly, you may lose all existing backups if you reset Windows Backup. To ensure you don't lose data, [create a backup of the existing Windows files](https://www.makeuseof.com/tag/backup-windows-files-folders/) before resetting Windows Backup.

 Furthermore, the reset may affect some third-party apps. It's wise to check with your software vendor before resetting Windows Backup.

 If something goes wrong during the reset, you may have a corrupted backup configuration. In such cases, reinstall the operating system and start from scratch.

 Overall, resetting Windows Backup helps resolve existing issues, but take the necessary precautions to avoid potential risks.

## How to Reset Windows Backup to Its Factory Settings

 Now you know how to proceed with caution, here's how to reset Windows Backup to its factory settings.

### 1\. Using Command Prompt

 If your current backup configuration isn't working, reset Windows Backup to its default settings. To get started, [run the Command Prompt with admin access](https://www.makeuseof.com/windows-run-command-prompt-admin/). In the Command Prompt window, run the following command:

`reg delete HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup /f`

 This will reset to the default configuration and remove all existing backups.

 After that, copy and paste the following command into the Command Prompt window and press **Enter**:

`reg add HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup`

 This will recreate the WindowsBackup entry in the registry editor. Next, type in and run the below command to delete the Automatic Backup scheduled task on Windows:

`schtasks /delete /tn "Microsoft\Windows\WindowsBackup\AutomaticBackup" /f`

 Finally, execute the below command to delete the backup monitor scheduled task:

`schtasks /delete /tn "Microsoft\Windows\WindowsBackup\Windows Backup Monitor" /f`

 After executing the above commands, restart your computer. This will reset Windows Backup to its default settings.

### 2\. Creating a Batch File

 If you're not comfortable with the command line interface, reset Windows Backup by creating a batch file.

 To do this, [open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) and paste the below code.

`<code>reg delete HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup /f  
reg add HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup  
schtasks /delete /tn "Microsoft\Windows\WindowsBackup\AutomaticBackup" /f  
schtasks /delete /tn "Microsoft\Windows\WindowsBackup\Windows Backup Monitor" /f`

 Click the **File** menu and select **Save as**. On the Save as dialog, type **reset-backup.bat** as the file name. Then choose **All Files** from the drop-down menu next to the Save as type. From the left panel, select **Desktop** and click the **Save** button.

 Now, close the Notepad window and right-click on the batch file. From the context menu, select **Run as administrator**. This will reset Windows Backup to its default settings.

 Lastly, restart your computer and you're done. These are two methods to reset Windows Backup to its default settings.

## Get Your Backups Working Again on Windows

 Whether you use the command line interface or create a batch file, it's easy to reset Windows Backup. Just remember to restart your computer after the process completes successfully.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/addressing-windows-11-get-support-disruption/"><u>Addressing Windows 11 'Get Support' Disruption</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-screen-recorder-alternatives-in-depth-review-and-top-picks/"><u>[Updated] Screen Recorder Alternatives  In-Depth Review & Top Picks</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-the-ultimate-guide-to-discerning-exceptional-sound-designers-for-your-projects/"><u>New The Ultimate Guide to Discerning Exceptional Sound Designers for Your Projects</u></a></li>
<li><a href="https://windows11.techidaily.com/back-to-basics-windows-11-access-re-establishment-guide/"><u>Back to Basics: Windows 11 Access Re-Establishment Guide</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-13-to-other-iphone-12-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone 13 to other iPhone 12 devices? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/bypass-bottlenecks-9-fixes-for-rapid-windows-verification/"><u>Bypass Bottlenecks: 9 Fixes for Rapid Windows Verification</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-from-ordinary-to-extraordinary-creating-hdr-in-lightroom/"><u>2024 Approved  From Ordinary to Extraordinary  Creating HDR in Lightroom</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-scripts-not-active-top-4-fixes-to-powershell-load-issue/"><u>Bypassing 'Scripts Not Active': Top 4 Fixes to PowerShell Load Issue</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-professional-tips-for-high-quality-video-disc-production-on-mac/"><u>In 2024, Professional Tips for High-Quality Video Disc Production on Mac</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-unleash-your-creativity-simple-video-editing-with-microsoft-on-windows/"><u>New 2024 Approved Unleash Your Creativity Simple Video Editing with Microsoft on Windows</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/-quick-method-for-posting-youtube-shorts-from-pctablet/"><u>Learn Quick Method for Posting YouTube Shorts From PC/Tablet</u></a></li>
<li><a href="https://windows11.techidaily.com/a-step-by-step-approach-for-cleaning-up-ms-audit-records/"><u>A Step-by-Step Approach for Cleaning Up MS Audit Records</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-productivity-and-grades-essential-study-methods-on-a-windows-pc/"><u>Boost Productivity and Grades: Essential Study Methods on a Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerating-media-playback-in-vlc-for-pc-users/"><u>Accelerating Media Playback in VLC for PC Users</u></a></li>
<li><a href="https://windows11.techidaily.com/5-methods-how-win11-harvests-personal-info/"><u>5 Methods: How Win11 Harvests Personal Info</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/unleash-potential-strategies-for-skyrocketing-your-fb-profile-status-for-2024/"><u>Unleash Potential  Strategies for Skyrocketing Your FB Profile Status for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-spotlight-on-popular-tiktok-cover-art/"><u>[Updated] Spotlight on Popular TikTok Cover Art</u></a></li>
<li><a href="https://windows11.techidaily.com/break-the-cycle-of-a-non-opening-notepad-on-your-windows-device/"><u>Break the Cycle of a Non-Opening Notepad on Your Windows Device</u></a></li>
<li><a href="https://windows11.techidaily.com/bless-your-pc-god-mode-enhancements/"><u>Bless Your PC: God Mode Enhancements</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-apple-iphone-13-pro-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Upgrade Apple iPhone 13 Pro without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-step-by-step-guide-to-dynamic-gif-making/"><u>In 2024, Step-by-Step Guide to Dynamic GIF Making</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-scanning-issues-with-your-geforce-experience-on-windows/"><u>Avoid Scanning Issues with Your GeForce Experience on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-control-mastering-local-gpo-access-on-windows-11/"><u>Boosting Control: Mastering Local GPO Access on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-java-not-installing-a-windows-fixers-manual/"><u>Addressing Java Not Installing: A Windows Fixer's Manual</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-quick-fix-for-turning-yt-lists-backwards/"><u>2024 Approved  The Quick Fix for Turning YT Lists Backwards</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-windows-file-concordance-with-aoemi-tutorial/"><u>Achieve Windows File Concordance with AOEMi Tutorial</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-from-classic-to-curvy-embracing-distorted-photography-styles/"><u>2024 Approved  From Classic to Curvy  Embracing Distorted Photography Styles</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-activate-funimate-pro-with-a-simple-apk-click/"><u>In 2024, Activate Funimate Pro with a Simple APK Click</u></a></li>
<li><a href="https://windows11.techidaily.com/3-key-fixes-for-sudden-disk-full-situations/"><u>3 Key Fixes for Sudden Disk Full Situations</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-10-exemplary-websites-for-vector-quality-graphics/"><u>2024 Approved  10 Exemplary Websites for Vector-Quality Graphics</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-learn-how-everything-works-on-realme-c51-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Learn How Everything Works On Realme C51 | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-instagrams-hidden-gems-designing-stunning-engaging-puzzle-posts/"><u>[New] In 2024, Instagram's Hidden Gems  Designing Stunning, Engaging Puzzle Posts</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-critical-analysis-of-the-best-free-video-chat-software-suitable-for-businesses-and-educators/"><u>[Updated] 2024 Approved  Critical Analysis of the Best Free Video Chat Software Suitable for Businesses & Educators</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-unveiling-the-magic-of-clear-audio-eliminating-ambient-noises-using-audacity-for-2024/"><u>[New] Unveiling the Magic of Clear Audio  Eliminating Ambient Noises Using Audacity for 2024</u></a></li>
<li><a href="https://facebook.techidaily.com/facebook-judges-announce-date-for-ruling-on-trump-ban/"><u>Facebook Judges Announce Date for Ruling on Trump Ban</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-unstartable-lunar-client-in-windows-issues/"><u>Avoiding Unstartable: Lunar Client in Windows Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-your-vbox-windows-install-with-dependencies/"><u>Boost Your VBox Windows Install with Dependencies</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-automatic-color-tuning-on-win11-devices/"><u>Activating Automatic Color Tuning on Win11 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/amplify-pc-utorrent-transfer-rate-windows-edition-guide/"><u>Amplify PC uTorrent Transfer Rate - Windows Edition Guide</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-key-sites-for-innovative-font-design/"><u>In 2024, Key Sites for Innovative Font Design</u></a></li>
<li><a href="https://windows11.techidaily.com/adaptive-keystroke-configurations-for-windows-11-users/"><u>Adaptive Keystroke Configurations for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/assuring-proper-operation-of-windows-monitor-app/"><u>Assuring Proper Operation of Windows Monitor App</u></a></li>
<li><a href="https://screen-capture.techidaily.com/top-10-online-screen-video-recorders/"><u>Top 10 Online Screen Video Recorders</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-budget-friendly-choices-must-have-gopro-add-ons/"><u>[New] Budget-Friendly Choices  Must-Have GoPro Add-Ons</u></a></li>
<li><a href="https://windows11.techidaily.com/best-practices-for-turning-off-your-pc-safely/"><u>Best Practices for Turning Off Your PC Safely</u></a></li>
<li><a href="https://howto.techidaily.com/google-play-services-wont-update-12-fixes-are-here-on-poco-x5-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Google Play Services Wont Update? 12 Fixes are Here on Poco X5 | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unresponsive-phone-touchscreen-of-tecno-pova-5-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Phone Touchscreen Of Tecno Pova 5 | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-earn-wisely-the-simple-triad-method-for-scrutinizing-youtube-profits/"><u>In 2024, Earn Wisely  The Simple Triad Method for Scrutinizing YouTube Profits</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-efficient-use-of-obs-with-zoom-video-platform-for-2024/"><u>[Updated] Efficient Use of OBS with Zoom Video Platform for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-the-unsuccessful-capture-problem-in-win11/"><u>Addressing the 'Unsuccessful Capture' Problem in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-the-hotspot-offline-error-in-windows-11/"><u>Addressing the Hotspot Offline Error in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/bridging-the-gap-top-6-ways-to-solve-network-hardware-issues-in-windows-systems/"><u>Bridging the Gap - Top 6 Ways to Solve Network Hardware Issues in Windows Systems</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2023s-viral-tweets-ranking-by-number-of-viewers-for-2024/"><u>2023’S Viral Tweets  Ranking by Number of Viewers for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-unhackable-blueprint-for-inserting-your-tiktok-links/"><u>[Updated] Unhackable Blueprint for Inserting Your TikTok Links</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-scaling-up-your-income-with-instagram-mastery/"><u>[Updated] 2024 Approved  Scaling Up Your Income with Instagram Mastery</u></a></li>
<li><a href="https://windows11.techidaily.com/clarifying-windows-approach-to-isolated-audiosystems/"><u>Clarifying Windows' Approach to Isolated Audiosystems</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-alerts-instant-battery-charged-notifications-in-win11/"><u>Boosting Alerts: Instant Battery Charged Notifications in Win11</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/the-updated-method-to-bypass-vivo-x90s-frp-by-drfone-android/"><u>The Updated Method to Bypass Vivo X90S FRP</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-delayed-auditory-feedback-on-pcs/"><u>Addressing Delayed Auditory Feedback on PCs</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/8-best-apps-for-screen-mirroring-vivo-y56-5g-pc-drfone-by-drfone-android/"><u>8 Best Apps for Screen Mirroring Vivo Y56 5G PC | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-service-failed-message-on-windows-disk-management/"><u>Addressing 'Service Failed' Message on Windows Disk Management</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-code-0x887a0006-for-gpu-stalls-windows/"><u>Addressing Code 0X887A0006 for GPU Stalls Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-display-adjustment-overcoming-overscan/"><u>Mastering Windows Display Adjustment: Overcoming Overscan</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-crafting-a-youtube-video-essential-writing-guide/"><u>[Updated] 2024 Approved  Crafting a YouTube Video  Essential Writing Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-clipboard-operations-in-application-guard-edge-win11-guide/"><u>Activating Clipboard Operations in Application Guard (Edge) - Win11 Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/bypass-license-validity-warning-on-w10-and-w11-systems/"><u>Bypass License Validity Warning on W10 & W11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-spec-deficit-errors-from-windows-game-bar/"><u>Addressing Spec Deficit Errors From Window's Game Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/6-essential-rotation-tips-for-windows-11-photos/"><u>6 Essential Rotation Tips for Windows 11 Photos</u></a></li>
<li><a href="https://windows11.techidaily.com/a-guide-to-all-the-windows-photos-keyboard-shortcuts/"><u>A Guide to All the Windows Photos Keyboard Shortcuts</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-expert-picks-ideal-software-for-screenshots-and-recordings/"><u>[Updated] Expert Picks  Ideal Software for Screenshots & Recordings</u></a></li>
<li><a href="https://windows11.techidaily.com/achieving-a-peaceful-state-disable-background-tasks/"><u>Achieving a Peaceful State: Disable Background Tasks</u></a></li>
</ul></div>
