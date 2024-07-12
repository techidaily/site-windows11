---
title: "How to Correct Non-Empty Directory Error (Code: 0X80070091) in Win11"
date: 2024-07-11T21:28:45.697Z
updated: 2024-07-12T21:28:45.697Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes How to Correct Non-Empty Directory Error (Code: 0X80070091) in Win11"
excerpt: "This Article Describes How to Correct Non-Empty Directory Error (Code: 0X80070091) in Win11"
keywords: Win11 Fix,Non-Empty Directory Win11,Win11 Empty Folder Issue,Directory Error Code 0X80070091,Resolving Win11 Folder Error,Win11,Fixing 0X80070091 in Windows 11
thumbnail: https://thmb.techidaily.com/d77d95aa486b91c6469c5ee9cc4e937e8d3af5aa50ced6b44ad4148b7b19bd91.jpg
---

## How to Correct Non-Empty Directory Error (Code: 0X80070091) in Win11

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
<li><a href="https://windows11.techidaily.com/clearing-up-old-user-credentials-issue-on-win-11-os/"><u>Clearing Up 'Old User Credentials' Issue on Win 11 OS</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-nokia-xr21-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Nokia XR21 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-breakdown-using-toolbar-in-mspcm-on-windows-11/"><u>Comprehensive Breakdown: Using Toolbar in MSPCM on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-versatility-top-10-innovative-ways-to-use-powertoys-tools/"><u>Discover Versatility: Top 10 Innovative Ways to Use PowerToys Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-shortcut-for-character-viewing/"><u>Windows 11 Shortcut for Character Viewing</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/mastery-of-instagram-videography-blueprint-for-robust-marketing-plans-for-2024/"><u>Mastery of Instagram Videography  Blueprint for Robust Marketing Plans for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/7-festive-tweaks-to-personalize-your-windows-11/"><u>7 Festive Tweaks to Personalize Your Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-powertoys-worldwide-mouse-capabilities/"><u>Unlock PowerToy's Worldwide Mouse Capabilities</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-audio-error-devices-being-used-by-non-targeted-apps/"><u>Clearing Up Audio Error: Devices Being Used by Non-Targeted Apps</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/what-is-a-sim-network-unlock-pin-get-your-lenovo-thinkphone-phone-network-ready-by-drfone-android/"><u>What Is a SIM Network Unlock PIN? Get Your Lenovo ThinkPhone Phone Network-Ready</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-up-controlled-temperature-policy-on-windows-pcs/"><u>Setting up Controlled Temperature Policy on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-abrupt-game-closure-in-roblox-fix-tips-for-pc-users/"><u>Avoiding Abrupt Game Closure in Roblox: Fix Tips for PC Users</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-alternate-pdf-reader-on-windows/"><u>Configuring Alternate PDF Reader on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-simple-trick-to-finding-your-installed-application-home/"><u>The Simple Trick to Finding Your Installed Application Home</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-productivity-expert-guide-to-using-toolbar-on-w11-winpcm/"><u>Elevate Your Productivity: Expert Guide to Using Toolbar on W11 WinPCM</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-fix-absent-app-in-windows-filesystem/"><u>Strategies to Fix Absent App in Windows Filesystem</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-list-of-pokemon-go-joysticks-on-nubia-z50s-pro-drfone-by-drfone-virtual-android/"><u>In 2024, List of Pokémon Go Joysticks On Nubia Z50S Pro | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-laughs-at-your-service-web/"><u>[New] Laughs at Your Service (Web)</u></a></li>
<li><a href="https://windows11.techidaily.com/tactical-aid-for-windows-issues-in-googles-nearby-share-app/"><u>Tactical Aid for Windows Issues in Google's Nearby Share App</u></a></li>
<li><a href="https://howto.techidaily.com/11-ways-to-fix-it-when-my-xiaomi-redmi-k70e-wont-charge-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Ways to Fix it When My Xiaomi Redmi K70E Wont Charge | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-google-play-location-on-oneplus-nord-ce-3-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Google Play Location On OnePlus Nord CE 3 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-the-setup-of-new-non-operational-store-programs/"><u>Streamlining the Setup of New, Non-Operational Store Programs</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-correcting-malwarebytes-call-failure-in-win11win10/"><u>Steps for Correcting Malwarebytes Call Failure in Win11/Win10</u></a></li>
<li><a href="https://windows11.techidaily.com/decreasing-the-impact-of-high-cpu-tiworkerexe-applications/"><u>Decreasing the Impact of High-CPU TiWorker.exe Applications</u></a></li>
<li><a href="https://windows11.techidaily.com/syncing-sound-levels-across-windows-and-bt-audio-gear/"><u>Syncing Sound Levels Across Windows and BT Audio Gear</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerating-wired-internet-beyond-100mbps-in-windows/"><u>Accelerating Wired Internet Beyond 100Mbps in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-prevent-and-fix-windows-error-code-0xc00000f/"><u>Strategies to Prevent & Fix Windows Error Code 0Xc00000f</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-nearby-share-for-file-transfers/"><u>Understanding Nearby Share for File Transfers</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-wows-abrupt-server-quit-error-132-in-win11/"><u>Solutions for WoW's Abrupt Server Quit (Error 132) in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/stealth-mode-disabling-windows-wi-fi-broadcast/"><u>Stealth Mode: Disabling Windows Wi-Fi Broadcast</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-top-mac-screen-recorders-ranked-a-comprehensive-analysis/"><u>[New] 2024 Approved  Top Mac Screen Recorders Ranked  A Comprehensive Analysis</u></a></li>
<li><a href="https://extra-resources.techidaily.com/curated-list-of-premium-iphone-x7-camera-improvers/"><u>Curated List of Premium iPhone X/7 Camera Improvers</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11-for-optimal-clipchamp-functionality/"><u>Unlocking Windows 11 for Optimal ClipChamp Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/unmasking-windows-hidden-chronicle-view-clean-up/"><u>Unmasking Windows' Hidden Chronicle - View, Clean Up!</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-your-workflow-with-windows-11s-widget-toolbar/"><u>Boost Your Workflow with Windows 11'S Widget Toolbar</u></a></li>
<li><a href="https://windows11.techidaily.com/detailed-guide-extracting-device-ids-on-windows-pcs/"><u>Detailed Guide: Extracting Device IDs on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/dismantling-tpm-in-win11-using-the-power-of-rufus/"><u>Dismantling TPM in Win11 Using the Power of Rufus</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-tab-issue-solutions-for-non-responsive-keys/"><u>Windows Tab Issue: Solutions for Non-Responsive Keys</u></a></li>
<li><a href="https://android-unlock.techidaily.com/still-using-pattern-locks-with-oppo-a38-tips-tricks-and-helpful-advice-by-drfone-android/"><u>Still Using Pattern Locks with Oppo A38? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-the-top-5-android-apps-that-use-fingerprint-sensor-to-lock-your-apps-on-infinix-hot-40i-by-drfone-android/"><u>In 2024, The Top 5 Android Apps That Use Fingerprint Sensor to Lock Your Apps On Infinix Hot 40i</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-create-engaging-videos-with-the-ken-burns-effect-a-step-by-step-tutorial/"><u>New 2024 Approved Create Engaging Videos with the Ken Burns Effect A Step-by-Step Tutorial</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-essential-asmr-channel-discoveries/"><u>[Updated] 2024 Approved  Essential ASMR Channel Discoveries</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-14-pro-max-to-android-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 14 Pro Max To Android devices? | Dr.fone</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-a-comprehensive-guide-to-video-and-subtitle-translation-with-veedio-for-2024/"><u>New A Comprehensive Guide to Video and Subtitle Translation with Veed.io for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-policy-settings-with-proven-gpo-update-methods/"><u>Streamlining Policy Settings with Proven GPO Update Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-restoring-icon-clarity-on-your-pcs-desktop/"><u>Tips for Restoring Icon Clarity on Your PC's Desktop</u></a></li>
<li><a href="https://network-issues.techidaily.com/how-to-toggle-to-safe-mode-and-delete-graphics-drivers-on-windows-8/"><u>How to Toggle to Safe Mode & Delete Graphics Drivers on Windows 8</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/nurturing-discussions-strategies-to-connect-with-followers-for-2024/"><u>Nurturing Discussions  Strategies to Connect With Followers for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-common-issues-with-windows-shared-printers/"><u>Solving Common Issues with Windows Shared Printers</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/mastering-metaverse-marketing-techniques-for-2024/"><u>Mastering Metaverse Marketing Techniques for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/selecting-ideal-fpv-propellers-a-comprehensive-guide/"><u>Selecting Ideal FPV Propellers  A Comprehensive Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/your-missing-flight-tech-copilot-in-new-os/"><u>Your Missing Flight Tech (Copilot) in New OS?</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-does-find-my-friends-work-on-vivo-v27e-drfone-by-drfone-virtual-android/"><u>In 2024, Does find my friends work on Vivo V27e | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-create-a-digital-signature-online-for-word-document-by-ldigisigner-sign-a-word-sign-a-word/"><u>How to Create a Digital Signature Online for Word document</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/editing-to-sharing-youtube-mastery-with-adobe-premiere/"><u>From Editing to Sharing  YouTube Mastery with Adobe Premiere</u></a></li>
<li><a href="https://windows11.techidaily.com/breathing-life-into-winget-a-windows-11-solution/"><u>Breathing Life Into Winget: A Windows 11 Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-tackle-icons-not-aligned/"><u>Win 11: Tackle Icons Not Aligned</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-tecno-spark-go-2023-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Tecno Spark Go (2023)</u></a></li>
<li><a href="https://youtube-help.techidaily.com/identifying-and-accessing-your-music-picks-on-youtube-for-2024/"><u>Identifying and Accessing Your Music Picks on Youtube for 2024</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-the-fastest-way-to-convert-4k-videos-to-mp4-no-technical-expertise-needed-for-2024/"><u>New The Fastest Way to Convert 4K Videos to MP4 No Technical Expertise Needed for 2024</u></a></li>
</ul></div>
