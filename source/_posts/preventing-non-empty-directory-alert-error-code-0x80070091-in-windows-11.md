---
title: "Preventing Non-Empty Directory Alert (Error Code: 0X80070091) in Windows 11"
date: 2024-07-11T21:36:22.882Z
updated: 2024-07-12T21:36:22.882Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Preventing Non-Empty Directory Alert (Error Code: 0X80070091) in Windows 11"
excerpt: "This Article Describes Preventing Non-Empty Directory Alert (Error Code: 0X80070091) in Windows 11"
keywords: Win11 Directory Error Prevention,Empty Folder Fix Error 0X80070091,Stop Non-Empty Dir Alert in Windows,Error Code 0X80070091 Solutions,Avoiding Win11 Directory Failure,Correcting Empty Folder Issue,Preventing Directory Errors Windows 11
thumbnail: https://thmb.techidaily.com/38a10dded96ded9495ccb2173f240c20a69acb6b4b947c6dc175d30ce0f723b9.jpg
---

## Preventing Non-Empty Directory Alert (Error Code: 0X80070091) in Windows 11

 Error 0x80070091 is a File Explorer issue that occurs for some users when they try to delete folders in Windows 11/10\. The error message says, “The directory is not empty," and you can't delete the folder that throws the error.

 The 0x80070091 message suggests that the error occurs because a folder isn’t empty. Yet, you should be able to erase directories that contain files without any issues. Furthermore, that error can also arise for empty folders. If you’re seeing the same folder error 0x80070091 in Windows, try applying these potential fixes.

## 1\. Try Erasing the Folder With the Command Prompt

 The Command Prompt gives users another way to delete folders in Windows 11/10\. So, you might be able to erase an affected folder without issues by using the Command Prompt. Using the Command Prompt might be more of a workaround, but at least you’ll get the folder deleted if works.

 Run Command Prompt with elevated (administrative) rights. Our guide about [running Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) includes numerous methods for launching that app. Then input this command and press**Enter** to delete an affected folder:

`rmdir /s "folder path"`

 You’ll need to replace**folder path** in that command with the location of whatever directory you need to delete. The location should include a drive letter and a full path for the directory like in this example:

`rmdir /s "C:\Users\New folder"`

![The delete folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-folder-command.jpg)

## 2\. Restart Windows File Explorer

 Restarting File Explorer can resolve issues that occur with that file manager. However, closing and reopening the Explorer window doesn’t restart the file manager. You’ll need to restart the Explorer process via Task Manager like this:

1. To view Task Manager, press**Ctrl** +**Shift** +**Esc** simultaneously.
2. Select File Explorer on the**Processes** tab.  
![The Restart option for File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/restart-options-for-file-explorer.jpg)
3. Press the**Restart** button for the selected Explorer process.

## 3\. Scan System Files With an SFC Scan

 Error 0x80070091 can be caused by some corrupted system files that need repairing. Running an SFC scan might both detect and repair corrupted system files and fix error 0x80070091 in the process. You can scan with SFC as instructed in our post for [running the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) .

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/sfc-scannow-command.jpg)

## 4\. Check for Errors With a Disk Scan

 The 0x80070091 error is often due to corrupted or bad hard drive sectors. A lot of users have said they’ve resolved that issue by using the Check Disk (CHKDSK) utility for repairing bad drive sectors. This is how you can check for and repair bad sectors with Check Disk:

1. Open up the Command Prompt window with administrative rights.
2. Type in this Check Disk command and press**Enter:**  
`chkdsk /f /r C:`
3. Press**Y** to schedule the scan for a restart.  
![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/chkdsk-scan-command.jpg)
4. Click**Start** and select**Power** \>**Restart** to reboot.

 If the folder the 0x80070091 error occurs for isn’t on the C: drive, you’ll need to modify the above command. Replace**C:** with the letter of the storage drive that includes the affected folder.

## 5\. Modify the Affected Folder’s Permissions

 Error 0x80070091 can arise because of insufficient folder permission. You might need to set an affected folder to full permission to resolve error 0x80070091\. To do that, change the folder’s permission settings as follows:

1. Open Explorer and right-click the affected folder to select**Properties** .  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/properties-option.jpg)
2. Click the window’s**Security** tab.
3. Next, press the**Advanced** button.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/security-tab.jpg)
4. Click**Change** beside the owner’s name.  
![The Advanced Security Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/advanced-security-settings-window.jpg)
5. Enter your Windows user account name inside the object name text box.  
![The Select a User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/select-a-user-or-group.jpg)
6. Then select the**Check Names** option and**OK** .
7. Click**Replace owner on subcontainers and objects** to select that setting.
8. Press the Advanced Security Settings window’s**Apply** and**OK** buttons.

## 6\. Run an Antivirus Scan

 Malware could also feasibly be causing error 0x80070091 on your PC. If you’re still trying to fix that issue after going through all the potential fixes above, run an antivirus scan with Windows Security or alternative third-party software. This is how to run a scan with the Windows Security app.

1. Double-click a**Windows Security** (shield) icon in the system tray part of the taskbar.
2. Click**Virus & threat protection** \>**Scan options** to view all options for scanning.  
![The Scan options navigation link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-scan-options-link.jpg)
3. Select the most thorough**Full Scan** option, which could take more than an hour to finish.  
![The Full scan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/full-scan-option.jpg)
4. Press**Scan now** to start the antivirus scanning.
5. Then wait to see if the scan detects anything, and select**Remove** if it does.
6. Click**Start actions** to apply.

## Delete Your Folders in File Explorer Again With These Fixes

 You’ll probably be able to delete the folders for which error 0x80070091 occurred after applying those potential solutions. If that error persists, the Windows registry on your PC could be corrupted. To resolve such registry issues, you might need to perform a system restore or even reset Windows 11/10.

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
<li><a href="https://windows11.techidaily.com/disabling-memory-write-failures-windows-fixes-guide/"><u>Disabling Memory Write Failures: Windows Fixes Guide</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-the-years-predictions-rendered-in-infographics/"><u>[Updated] The Year's Predictions Rendered in Infographics</u></a></li>
<li><a href="https://windows11.techidaily.com/automate-peaceful-rest-for-your-windows-11-desktop/"><u>Automate Peaceful Rest for Your Windows 11 Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/notepaddarksettingsinstructionswin1011/"><u>NotepadDarkSettingsInstructionsWin10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-multi-screen-brightness-best-tools-to-light-up-your-windows-monitors/"><u>Navigating Multi-Screen Brightness: Best Tools to Light Up Your Windows Monitors</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-the-wow-breakdown-cure-windows-error-code-132/"><u>Avoid the WoW Breakdown: Cure Windows Error Code 132</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-deactivated-sliders-for-volume-control/"><u>Troubleshooting Deactivated Sliders for Volume Control</u></a></li>
<li><a href="https://windows11.techidaily.com/approaches-to-fix-failed-launch-of-lunar-client-in-windows/"><u>Approaches to Fix Failed Launch of Lunar Client in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-of-non-existent-mmc-snaps/"><u>Unraveling the Mystery of Non-Existent MMC Snaps</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/how-android-enables-seamless-screen-capturing/"><u>How Android Enables Seamless Screen Capturing</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-flawed-setups-a-guide-to-windows-package-woes/"><u>Fixing Flawed Setups: A Guide to Windows Package Woes</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-unlocking-the-secrets-to-stellar-sims-gameplay-recording/"><u>2024 Approved  Unlocking the Secrets to Stellar Sims Gameplay Recording</u></a></li>
<li><a href="https://windows11.techidaily.com/exclusive-guide-to-forgotten-windows-11-themes/"><u>Exclusive Guide to Forgotten Windows 11 Themes</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-maximize-space-not-time-discover-the-coolest-34-phone-apps-for-slashing-size/"><u>[New] Maximize Space, Not Time  Discover the Coolest 34 Phone Apps for Slashing Size</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/full-spectrum-analysis-the-logitech-4k-pro-webcam/"><u>Full Spectrum Analysis  The Logitech 4K Pro Webcam</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-social-medias-best-video-enhancing-programs-2023/"><u>In 2024, Social Media's Best Video Enhancing Programs, 2023</u></a></li>
<li><a href="https://windows11.techidaily.com/ai-driven-evolution-in-windows-software-design/"><u>AI-Driven Evolution in Windows Software Design</u></a></li>
<li><a href="https://windows11.techidaily.com/turbocharging-windows-solid-state-drives-utilizing-fresh-tools/"><u>Turbocharging Windows' Solid State Drives - Utilizing Fresh Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-enabling-or-disabling-wi-fi-cost-tracking-in-windows-11/"><u>Guide: Enabling or Disabling Wi-Fi Cost Tracking in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/detailed-guide-turning-secure-boot-and-tpm-onoff-in-vbox/"><u>Detailed Guide: Turning Secure Boot and TPM On/Off in VBox</u></a></li>
<li><a href="https://windows11.techidaily.com/insights-on-how-to-utilize-execution-nicknames/"><u>Insights on How to Utilize Execution Nicknames</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-edge-windows-11-techniques-building-hotkeys-for-text-snapping/"><u>Cutting Edge Windows 11 Techniques: Building Hotkeys for Text Snapping</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-secrets-for-mastering-volume-control-in-windows-11/"><u>Unlock Secrets for Mastering Volume Control in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-visual-coherence-integrating-this-pc-icon/"><u>Enhance Visual Coherence: Integrating 'This PC' Icon</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-the-secret-behind-successful-igtv-uploads-from-h-videos/"><u>[New] The Secret Behind Successful IGTV Uploads From H-Videos</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-boost-creativity-and-connectivity-best-50plus-tiktok-quotes/"><u>[New] 2024 Approved  Boost Creativity & Connectivity  Best 50+ TikTok Quotes</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-mend-the-pairing-glitch-fixing-connection-issues-in-win-11/"><u>How to Mend the Pairing Glitch: Fixing Connection Issues in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/diminishing-high-cpu-impact-of-tiworkerexe-applications/"><u>Diminishing High CPU Impact of TiWorker.exe Applications</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-personalization-transforming-ordinary-into-extraordinary/"><u>Windows 11 Personalization: Transforming Ordinary Into Extraordinary</u></a></li>
<li><a href="https://windows11.techidaily.com/fixes-for-stumbling-windows-discord-search-bar/"><u>Fixes for Stumbling Windows Discord Search Bar</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/journey-through-linguistic-landscapes-discovering-squid-game/"><u>Journey Through Linguistic Landscapes: Discovering Squid Game</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-spotlight-on-benq-sw320s-eye-catching-4k-display/"><u>2024 Approved  Spotlight on BenQ SW320’s Eye-Catching 4K Display</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-oppo-a78-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>How to Track Oppo A78 Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-prime-viewer-iosandroidwindows-compatible/"><u>[Updated] Prime Viewer  IOS/Android/Windows Compatible</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-deactivated-system-cooler-protocol-on-pcs/"><u>Overcoming Deactivated System Cooler Protocol on PCs</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-solving-the-mystery-of-your-own-face-appearing-during-calls/"><u>[New] Solving the Mystery of Your Own Face Appearing During Calls</u></a></li>
<li><a href="https://windows11.techidaily.com/get-your-pcs-virtual-machine-game-strong-with-hyper-v/"><u>Get Your PC's Virtual Machine Game Strong with Hyper-V</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-disable-the-built-in-laptop-keyboard-in-windows/"><u>How to Disable the Built-In Laptop Keyboard in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-installation-issues-fixing-zero-error-on-win11/"><u>Avoid Installation Issues: Fixing Zero Error on Win11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-crafting-distinctive-video-stream-names-tips-for-filmora-users-for-2024/"><u>[New] Crafting Distinctive Video Stream Names  Tips for Filmora Users for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-through-qbittorrent-lag-a-windows-guide/"><u>Breaking Through qBittorrent Lag: A Windows Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-your-windows-11-journey-top-6-multitasking-android-apps/"><u>Enhancing Your Windows 11 Journey: Top 6 Multitasking Android Apps</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-2024-approved-leading-edge-headsets-for-drone-vr-use/"><u>[Updated] 2024 Approved  Leading Edge Headsets for Drone VR Use</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-for-lowering-tiworkerexe-process-resource-use/"><u>Methods for Lowering TiWorker.exe Process Resource Use</u></a></li>
<li><a href="https://windows11.techidaily.com/initiating-contact-accessing-windows-printer-administration-tools/"><u>Initiating Contact: Accessing Windows' Printer Administration Tools</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-crafting-professional-gamers-content-with-obs-recordings/"><u>In 2024, Crafting Professional Gamers' Content with OBS Recordings</u></a></li>
<li><a href="https://windows11.techidaily.com/discovering-distinctive-decor-for-each-monitor-in-windows-11/"><u>Discovering Distinctive Decor for Each Monitor in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-powershell-access-control-settings/"><u>Optimizing PowerShell Access Control Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-start-up-sequence-of-windows-os/"><u>Decoding the Start-Up Sequence of Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-windows-steam-streams-stopping-zero-rate-issues/"><u>Optimize Windows Steam Streams: Stopping Zero-Rate Issues</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-top-rated-4k-video-editing-tools-for-creators/"><u>Updated Top-Rated 4K Video Editing Tools for Creators</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-your-typing-speed-top-7-fixes-on-win-os/"><u>Elevating Your Typing Speed: Top 7 Fixes on WIN OS</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-boost-yt-thumbnails-flashy-neon-borders-applied/"><u>2024 Approved  Boost YT Thumbnails  Flashy Neon Borders Applied</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/mastering-twitter-videos-in-ultra-hd/"><u>Mastering Twitter Videos in Ultra HD</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-stop-life360-from-tracking-you-on-apple-iphone-14-plus-drfone-by-drfone-virtual-ios/"><u>How to Stop Life360 from Tracking You On Apple iPhone 14 Plus? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-back-chrome-color-loss/"><u>Winning Back Chrome Color Loss</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-boot-sector-problems-on-pc/"><u>Navigating Through Boot Sector Problems on PC</u></a></li>
</ul></div>
