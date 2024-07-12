---
title: Steps for Windows Backup Configuration Recollection
date: 2024-07-11T21:41:48.501Z
updated: 2024-07-12T21:41:48.501Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps for Windows Backup Configuration Recollection
excerpt: This Article Describes Steps for Windows Backup Configuration Recollection
keywords: Windows Backup Guide,Configuring Backups Windows,System Backup Setup Win,Windows Data Protection,Restore Windows Settings,Recovering Windows Files,Backup & Restore Win
thumbnail: https://thmb.techidaily.com/3be6004f814f322eb7c81e59f5f3e6dc5377a1a28f18fb94887b3ff8d1dce543.jpg
---

## Steps for Windows Backup Configuration Recollection

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
<li><a href="https://windows11.techidaily.com/breaking-down-steam-auth-blocks-in-rust-on-windows-devices/"><u>Breaking Down Steam Auth Blocks in Rust on Windows Devices</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-harnessing-hours-of-light-long-exposure-iphone-tips/"><u>In 2024, Harnessing Hours of Light  Long-Exposure iPhone Tips</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-the-instagram-editors-handbook-maximizing-video-impact/"><u>2024 Approved  The Instagram Editor's Handbook  Maximizing Video Impact</u></a></li>
<li><a href="https://windows11.techidaily.com/boosted-windows-11-app-launch-strategies/"><u>Boosted Windows 11 App Launch Strategies</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/swift-fixes-to-rectify-non-sending-videos-on-the-social-networking-platform-iphoneandroid-for-2024/"><u>Swift Fixes to Rectify Non-Sending Videos on the Social Networking Platform iPhone/Android for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/become-a-windows-wizard-learn-essential-shortcut-commands/"><u>Become a Windows Wizard: Learn Essential Shortcut Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/bouncing-back-deleted-folders-on-your-pc/"><u>Bouncing Back Deleted Folders on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/6-ways-to-fix-network-adapter-not-working-in-windows/"><u>6 Ways to Fix Network Adapter Not Working in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/cant-choose-a-drive-to-install-games-on-the-xbox-app-for-windows-try-these-fixes/"><u>Can't Choose a Drive to Install Games on the Xbox App for Windows? Try These Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/activate-dialer-in-microsoft-windows-11/"><u>Activate Dialer in Microsoft Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/avoidance-tactics-against-flaky-saving-mechanism-in-nvidia-gui/"><u>Avoidance Tactics Against Flaky Saving Mechanism in Nvidia GUI</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-a-clean-desktop-with-automatic-trash-emptying-in-windows/"><u>Achieve a Clean Desktop with Automatic Trash Emptying in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-windows-11-notepad-using-ai-mentor/"><u>Boost Windows 11 Notepad Using AI Mentor</u></a></li>
<li><a href="https://windows11.techidaily.com/best-slate-companions-selecting-top-7-windows-tabs/"><u>Best Slate Companions: Selecting Top 7 Windows Tabs</u></a></li>
<li><a href="https://windows11.techidaily.com/bridging-no-network-access-on-winethernet/"><u>Bridging No Network Access on WinEthernet</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/mastering-lock-screen-settings-how-to-enable-and-disable-on-nokia-c22-by-drfone-android/"><u>Mastering Lock Screen Settings How to Enable and Disable on Nokia C22</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-time-display-in-the-taskbar-of-window-11/"><u>Adjusting Time Display in the Taskbar of Window 11</u></a></li>
<li><a href="https://data-recovery.techidaily.com/easydata-revival-software-multiplatform-compatibility/"><u>EasyData Revival Software - Multiplatform Compatibility</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-license-validity-time-out-alerts-on-win10w11/"><u>Bypassing License Validity Time-Out Alerts on Win10/W11</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-real-time-music-videos-on-douyin-for-2024/"><u>[New] Real-Time Music Videos on Douyin for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-highlight-harmony-the-top-business-tactics-for-insta/"><u>In 2024, Highlight Harmony  The Top Business Tactics for Insta</u></a></li>
<li><a href="https://windows11.techidaily.com/ace-your-assault-win-against-mouse-lags-on-sw/"><u>Ace Your Assault: Win Against Mouse Lags on SW</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-2024-approved-how-to-make-a-do-it-yourself-video/"><u>Updated 2024 Approved How To Make A Do-It-Yourself Video</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-unnoticed-use-of-your-pcs-cam-on-windows-11/"><u>Avoiding Unnoticed Use of Your PC's Cam on Windows 11</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-mastering-the-art-of-profiling-a-complete-guide-to-pfps-in-discord/"><u>[New] In 2024, Mastering the Art of Profiling  A Complete Guide to Pfps in Discord</u></a></li>
<li><a href="https://windows11.techidaily.com/circumventing-error-code-0x800736cc-in-windows-update/"><u>Circumventing Error Code 0X800736CC in Windows Update</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-reactivating-windows-photo-viewer-in-windows-10-methods-unveiled/"><u>[Updated] Reactivating Windows Photo Viewer in Windows 10 - Methods Unveiled</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-realme-c51-frp-by-drfone-android/"><u>In 2024, Step-by-Step Tutorial How To Bypass Realme C51 FRP</u></a></li>
<li><a href="https://some-techniques.techidaily.com/explore-the-finest-free-luts-of-the-year-for-2024/"><u>Explore the Finest FREE LUTs of the Year for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-decades-old-password-request-on-modern-windows/"><u>Bypassing Decades-Old Password Request on Modern Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-duplicate-local-device-names-in-windows-systems/"><u>Avoiding Duplicate Local Device Names in Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/banishing-blue-screens-a-windows-fixers-manual/"><u>Banishing Blue Screens: A Windows Fixer’s Manual</u></a></li>
<li><a href="https://fake-location.techidaily.com/looking-for-a-location-changer-on-itel-s23-look-no-further-drfone-by-drfone-virtual-android/"><u>Looking For A Location Changer On Itel S23? Look No Further | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/clarity-masterclass-fixes-that-bring-life-to-fuzzy-screens/"><u>Clarity Masterclass: Fixes That Bring Life to Fuzzy Screens</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-thriving-livestreams-strategies-for-beginners-with-low-followers/"><u>[New] Thriving Livestreams  Strategies for Beginners with Low Followers</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-reel-in-riches-a-guide-to-earning-on-youtube-shorts/"><u>[New] Reel In Riches  A Guide to Earning on YouTube Shorts</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-socialvideocutter-download-feature-for-2024/"><u>[Updated] SocialVideoCutter  Download Feature for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-optimal-video-chat-on-windows-1-8-for-2024/"><u>[Updated] Optimal Video Chat on Windows  #1-8 for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-system-maintenance-locating-and-resolving-win-os-error-codes-via-command-prompt-expertise/"><u>Advanced System Maintenance: Locating and Resolving Win-OS Error Codes via Command Prompt Expertise</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-elite-listing-top-10-windows-11-cam-capture-devices/"><u>[Updated] Elite Listing  Top 10 Windows 11 Cam Capture Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/choosing-a-fresh-termbackground-pic/"><u>Choosing a Fresh TermBackground Pic</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-instagram-spotlight-tactics-a-3-step-guide/"><u>[Updated] In 2024, Instagram Spotlight Tactics  A 3-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensive-guide-to-tweaking-firewall-security/"><u>A Comprehensive Guide to Tweaking Firewall Security</u></a></li>
<li><a href="https://windows11.techidaily.com/audio-system-refreshment-navigating-the-windows-driver-update-process/"><u>Audio System Refreshment: Navigating the Windows Driver Update Process</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-discover-essential-youtube-music-channels/"><u>[Updated] In 2024, Discover Essential YouTube Music Channels</u></a></li>
<li><a href="https://windows11.techidaily.com/browser-blackouts-unveiled-7-fixes-to-restore-access-on-your-os/"><u>Browser Blackouts Unveiled: 7 Fixes to Restore Access on Your OS</u></a></li>
<li><a href="https://windows11.techidaily.com/6-fixes-for-windows-gone-dark-and-unresponsive/"><u>6 Fixes for Windows Gone Dark and Unresponsive</u></a></li>
<li><a href="https://fake-location.techidaily.com/wondering-the-best-alternative-to-hola-on-oppo-a1-5g-here-is-the-answer-drfone-by-drfone-virtual-android/"><u>Wondering the Best Alternative to Hola On Oppo A1 5G? Here Is the Answer | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-switch-to-the-future-capture-cards-guide/"><u>[Updated] In 2024, Switch to the Future  Capture Cards Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/1719354556221-eliminate-troubleshooting-roadblocks-for-compatibility-issues/"><u>Eliminate Troubleshooting Roadblocks for Compatibility Issues.</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/innovating-in-the-snapchat-space-trendsetting-ad-design-principles/"><u>Innovating in the Snapchat Space  Trendsetting Ad Design Principles</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-top-10-steps-youtube-to-mp3mpeg-conversion-process/"><u>[Updated] Top 10 Steps  YouTube to MP3/MPEG Conversion Process</u></a></li>
<li><a href="https://windows11.techidaily.com/6-different-ways-to-open-programs-on-windows/"><u>6 Different Ways to Open Programs on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/1719316143750-avoid-panic-recover-lost-data-with-these-steps/"><u>Avoid Panic, Recover Lost Data with These Steps!</u></a></li>
<li><a href="https://windows11.techidaily.com/5-great-free-podcast-editing-programs-for-windows/"><u>5 Great Free Podcast Editing Programs for Windows</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-stream-anything-from-realme-c51-to-apple-tv-drfone-by-drfone-android/"><u>How To Stream Anything From Realme C51 to Apple TV | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-the-best-free-screen-recorder-tool-bandicam-or-camtasia/"><u>[Updated] The Best Free Screen Recorder Tool  Bandicam or Camtasia?</u></a></li>
<li><a href="https://windows11.techidaily.com/becoming-proficient-with-windows-odbc-control-panel/"><u>Becoming Proficient with Windows' ODBC Control Panel</u></a></li>
<li><a href="https://howto.techidaily.com/7-fixes-for-unfortunately-phone-has-stopped-on-vivo-x-fold-2-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Fixes for Unfortunately, Phone Has Stopped on Vivo X Fold 2 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-win-based-office-glitches-effectively/"><u>Addressing Win-Based Office Glitches Effectively</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-back-disappearing-desktop-elements-on-windows/"><u>Bring Back Disappearing Desktop Elements on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/awakening-windows-11s-digital-storyteller/"><u>Awakening Windows 11'S Digital Storyteller</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-frozen-savers-4-tips-to-fix-windows-issues/"><u>Avoid Frozen Savers: 4 Tips to Fix Windows Issues</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/the-art-of-hiding-hashtags-on-social-media-platforms-for-2024/"><u>The Art of Hiding Hashtags on Social Media Platforms for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-oppo-a78-drfone-by-drfone-android/"><u>How To Use Allshare Cast To Turn On Screen Mirroring On Oppo A78 | Dr.fone</u></a></li>
</ul></div>
