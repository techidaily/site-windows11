---
title: "Conquering the Not an Empty Directory Alert (Error Code: 0X80070091) in Win11"
date: 2024-07-11T21:33:44.013Z
updated: 2024-07-12T21:33:44.013Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Conquering the Not an Empty Directory Alert (Error Code: 0X80070091) in Win11"
excerpt: "This Article Describes Conquering the Not an Empty Directory Alert (Error Code: 0X80070091) in Win11"
keywords: Win11 Error Fixing,Windows XP Error Resolution,DirNotFound Error Win11,Empty Folder Alert Win11,Directory Not Found Fix,0X80070091 Error Solution,Win11 File Error Correction
thumbnail: https://thmb.techidaily.com/8c3b13a3ac83a5d3d00093c2a17a7909556b01cc18d6b9abd17e301fcbcbc6e6.jpg
---

## Conquering the Not an Empty Directory Alert (Error Code: 0X80070091) in Win11

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
<li><a href="https://windows11.techidaily.com/say-goodbye-to-lag-how-to-fix-warhammer-40k-delays-on-your-pc/"><u>Say Goodbye to Lag: How to Fix Warhammer 40K Delays on Your PC</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-key-to-attracting-views-youtube-image-marketing/"><u>2024 Approved  The Key to Attracting Views  YouTube Image Marketing</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-delete-gmail-account-withwithout-password-on-infinix-by-drfone-android/"><u>In 2024, Delete Gmail Account With/Without Password On Infinix</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-best-apps-for-tracking-movement-on-your-smartphone-or-tablet/"><u>New 2024 Approved Best Apps for Tracking Movement on Your Smartphone or Tablet</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-fine-tuning-windows-11-alerts/"><u>The Art of Fine-Tuning Windows 11 Alerts</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-screenscape-designing-distinctive-displays-on-each-window-of-win-1011/"><u>Tailored Screenscape: Designing Distinctive Displays on Each Window of Win 10/11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-from-novice-to-pro-expert-tips-for-spotifys-advertisers/"><u>[Updated] From Novice to Pro  Expert Tips for Spotify's Advertisers</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-elevate-video-decks-smart-description-templates/"><u>[New] In 2024, Elevate Video Decks  Smart Description Templates</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-break-the-bond-onedrive-from-ms-account-on-windows/"><u>Techniques to Break the Bond: OneDrive From MS Account on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/chronological-corrections-6-utilities-to-edit-file-timestamps/"><u>Chronological Corrections: 6 Utilities to Edit File Timestamps</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-in-2024-how-to-forge-memes-that-captivate-audiences/"><u>[New] In 2024, How to Forge Memes that Captivate Audiences</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-eliminating-enter-usernamepassword-alerts-in-windows/"><u>Troubleshooting: Eliminating 'Enter Username/Password' Alerts in Windows</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-digital-bridge-integrating-youtube-into-tiktoks-ecosystem/"><u>In 2024, The Digital Bridge  Integrating YouTube Into TikTok's Ecosystem</u></a></li>
<li><a href="https://windows11.techidaily.com/swiftly-overcoming-windows-access-denied-blunders/"><u>Swiftly Overcoming Windows Access Denied Blunders</u></a></li>
<li><a href="https://windows11.techidaily.com/steady-your-pc-controlling-high-cpu-load-with-windows-resource-tool/"><u>Steady Your PC: Controlling High CPU Load With Window's Resource Tool</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-advanced-focus-modifier-app/"><u>[New] Advanced Focus Modifier App</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-transitioning-instagram-video-to-mp3-format/"><u>In 2024, Transitioning Instagram Video to Mp3 Format</u></a></li>
<li><a href="https://windows11.techidaily.com/cease-windows-system-notification-for-upgrades/"><u>Cease Windows System Notification for Upgrades</u></a></li>
<li><a href="https://windows11.techidaily.com/unseen-windows-firewall-protection-sectors-demystified/"><u>Unseen Windows Firewall Protection Sectors Demystified</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-the-essential-guide-to-expanding-your-tiktok-reach-and-interactions-for-2024/"><u>[New] The Essential Guide to Expanding Your TikTok Reach & Interactions for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-insiders-guide-to-bluescreenview-execution/"><u>The Insider’s Guide to BlueScreenView Execution</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-the-comprehensive-guide-to-effective-screen-recording/"><u>[New] 2024 Approved  The Comprehensive Guide to Effective Screen Recording</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-3-easy-ways-to-factory-reset-a-locked-apple-iphone-13-pro-without-itunes-by-drfone-ios/"><u>In 2024, 3 Easy Ways to Factory Reset a Locked Apple iPhone 13 Pro Without iTunes</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-speed-with-wordpad-embedding-keyboard-macros-into-windows-menu/"><u>Boosting Speed with WordPad: Embedding Keyboard Macros Into Windows Menu</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-unlock-new-horizons-best-6-instagram-reel-apps/"><u>2024 Approved  Unlock New Horizons  Best 6 Instagram Reel Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-the-best-encoding-methods-on-pc/"><u>Understanding the Best Encoding Methods on PC</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-perfect-playback-5-innovative-techniques-for-gamers/"><u>[New] 2024 Approved  Perfect Playback  5 Innovative Techniques for Gamers</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-long-term-snap-storage-on-androidmac-systems/"><u>2024 Approved  Long-Term Snap Storage on Android/Mac Systems</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/1714308739974-updated-2024-approved-the-ultimate-list-of-vignette-apps-for-mobile-free-paid-and-everything-in-between/"><u>Updated 2024 Approved The Ultimate List of Vignette Apps for Mobile Free, Paid, and Everything in Between</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-can-you-transfer-files-from-tecno-spark-20-to-iphone-151413-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How Can You Transfer Files From Tecno Spark 20 To iPhone 15/14/13? | Dr.fone</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/mp4-from-tiktok-best-free-extractors-available/"><u>MP4 From TikTok  Best Free Extractors Available</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-solutions-for-dotnet-health-in-pcs-max-156/"><u>Swift Solutions for DotNet Health in PCs (Max 156)</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-customizing-your-windows-11-notepad-appearance/"><u>Step-by-Step: Customizing Your Windows 11 Notepad Appearance</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-the-angle-game-rotate-images-in-6-steps-w11/"><u>Winning the Angle Game: Rotate Images in 6 Steps W11</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-low-end-system-failures-due-to-intel-graphics-requirements/"><u>Tackling Low-End System Failures Due to Intel Graphics Requirements</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-frustration-with-non-responsive-photoshop/"><u>Tackling Frustration with Non-Responsive Photoshop</u></a></li>
<li><a href="https://windows11.techidaily.com/automate-your-photo-display-craft-the-ultimate-win11-slideshow/"><u>Automate Your Photo Display - Craft the Ultimate Win11 Slideshow</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-syncing-twitter-to-snapchat-video-uploading-techniques/"><u>In 2024, Syncing Twitter to Snapchat  Video Uploading Techniques</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-decades-leading-guide-to-budget-friendly-recorders-for-2024/"><u>[Updated] Decade's Leading Guide to Budget-Friendly Recorders for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-app-installations-in-windows-11-using-winstall/"><u>Simplifying App Installations in Windows 11 Using Winstall</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/mastering-android-device-manager-the-ultimate-guide-to-unlocking-your-realme-gt-neo-5-se-device-by-drfone-android/"><u>Mastering Android Device Manager The Ultimate Guide to Unlocking Your Realme GT Neo 5 SE Device</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-download-velocity-in-steam-fending-off-drops/"><u>Boosting Download Velocity in Steam: Fending Off Drops</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-guerrilla-mic-guide-top-chip-selection-on-a-shoestring/"><u>[New] In 2024, Guerrilla Mic Guide  Top Chip Selection on a Shoestring</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-discords-auto-activation-at-pc-boot-sequence/"><u>Stop Discord's Auto-Activation at PC Boot Sequence</u></a></li>
</ul></div>
