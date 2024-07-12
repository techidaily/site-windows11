---
title: Safeguard Files with Window's Controlled Access Feature
date: 2024-07-11T21:38:30.840Z
updated: 2024-07-12T21:38:30.840Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Safeguard Files with Window's Controlled Access Feature
excerpt: This Article Describes Safeguard Files with Window's Controlled Access Feature
keywords: File Safety Windows Access,Secure Data Controlled Access,Protecting Files,Windows-Controlled File Security,Enhanced File Shielding Windows,Safekeep Files Windows Guard,File Integrity Windows Limited
thumbnail: https://thmb.techidaily.com/1f7a28a8bb8145eaefcf7bd927fe30950467d63b1317d80297e6274f57adb5a8.jpg
---

## Safeguard Files with Window's Controlled Access Feature

 Controlled folder access is a feature of the Windows Security antivirus app on Microsoft desktop platforms. That feature forestalls ransomware by preventing modifications to files in protected folders. Enabling controlled folder access prevents untrusted apps, malware or otherwise, from changing files within protected directories.

 Controlled folder access is an extra security feature in Windows 10 and 11 that some users appreciate. Ransomware isn’t something to be taken lightly, and enabling that feature will keep system and user files extra safe. These are four ways you can enable controlled folder access in Windows.

## How to Turn On Controlled Folder Access in Windows Security

 The Controlled folder access setting is buried within ransomware protection in the Windows Security app. However, it’s easy to find and turn that option on/off when you know where it is. This is how to turn on the Windows Security’s app Controlled folder access option.

1. To view the Windows Security app, double-click its shield system tray icon.
2. Select Windows Security’s**Virus & threat protection** tab.  
![The Manage ransomware protection](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/manage-ransomware-option.jpg)
3. Click**Manage ransomware protection** to reach the**Controlled folder access** setting.  
![The Controlled folder access option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/controlled-folder-access.jpg)
4. Now turn on the**Controlled folder access** option to enable that feature.

 Controlled folder access protects your Documents, Videos, Pictures, and Music user folders when enabled. To view the list of protected user directories, click**Protected folder** . You can add more to the list by clicking the**Add protected folder** button, choosing a directory, and clicking**Select Folder** .

![The Add a protected folder button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/add-a-protected-folder-button.jpg)

## How to Turn on Controlled Folder Access With PowerShell

 Windows PowerShell gives you an alternative method to enable and disable controlled folder access by executing commands. You can turn on controlled folder access with PowerShell as follows:

1. To activate a file search tool, press**Win + S** .
2. Input**PowerShell** within the activated search utility.
3. Open PowerShell in an elevated mode by selecting**Run as administrator** .
4. To enable controlled folder access, input this command text and hit**Enter** :  
`Set-MpPreference -EnableControlledFolderAccess Enabled`  
![The enable controlled folder access command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-controlled-folder-access-command.jpg)
5. You can disable controlled folder access by executing this command:  
`Set-MpPreference -EnableControlledFolderAccess Disabled`

## How to Enable Controlled Folder Access With Group Policy Editor

 If you have Windows 11 Pro or Enterprise edition, you can enable controlled folder access with Group Policy Editor. Group Policy Editor also includes some extra configuration settings for controlled folder access, which is a bonus. This is how to turn on controlled folder access via GPE.

 If you're on Windows Home, the Group Policy Editor won't appear by default. Check out [how to access the Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) to get around this.

1. Bring up the search tool in Windows and enter**gpedit.msc** there.
2. Select**gpedit.msc** to [bring up the Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) .
3. Click**Computer Configuration** \>**Administrative Templates** inside Group Policy Editor’s left pane.  
![Administrative Templates in Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/computer-configuration-in-group-policy-editor.jpg)
4. Double-click**Windows Components** to expand it.
5. Click the arrows for expanding**Microsoft Defender Antivirus** and**Microsoft Defender Exploit Guard** .

1. Select**Controlled Folder Access** to view policy settings for that feature.
2. Then double-click**Configure Controlled folder access** to view that setting’s window.  
![The Controlled Folder Access policy in Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/controlled-folder-access-in-group-policy-editor.jpg)
3. Select the Configure Controlled folder access window’s**Enabled** radio button.
4. Click**Block** on the drop-down menu to select the strictest CFA mode. However, you can also select alternative**Audit Mode** ,**Block disk notification only** , and**Audit disk notification only** options for enabling controlled folder access.  
![The Configure the guard my folders feature drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/configure-controlled-folder-access.jpg)
5. Select**Apply** in the Configure Controlled folder access window.
6. Click the Configure Controlled folder access window’s**OK** button.

## How to Turn on Controlled Folder Access From the Windows Context Menu

 Alternatively, you can create a context menu shortcut for enabling/disabling controlled folder access. Then you’ll be able to access a Turn on Control folder access setting directly from the desktop area of Windows. You can add such a CFA option to the right-click menu by setting up and running a registry script like this:

1. Open Notepad.
2. Then select this script text, and press the**Ctrl** +**C** key combination:  
`Windows Registry Editor Version 5.00  

 ; Created by: Shawn Brink  

 ; Created on: July 19th 2018  

 ; Tutorial: <https://www.tenforums.com/tutorials/114389-add-turn-off-controlled-folder-access-context-menu-windows-10-a.html>  

 [HKEY_CLASSES_ROOT\DesktopBackground\Shell\ControlledFolderAccess]  

 "HasLUAShield"=""  

 "Icon"="%ProgramFiles%\\Windows Defender\\EppManifest.dll,-101"  

 "MUIVerb"="Turn On or Off Control folder access"  

 "Position"="Bottom"  

 "SubCommands"=""  

 [HKEY_CLASSES_ROOT\DesktopBackground\Shell\ControlledFolderAccess\shell\001flyout]  

 "MUIVerb"="Turn on Control folder access"  

 "HasLUAShield"=""  

 "Icon"="%ProgramFiles%\\Windows Defender\\EppManifest.dll,-101"  

 [HKEY_CLASSES_ROOT\DesktopBackground\Shell\ControlledFolderAccess\shell\001flyout\command]  

 @="PowerShell -windowstyle hidden -Command \"Start-Process cmd -ArgumentList '/s,/c,start PowerShell.exe Set-MpPreference -EnableControlledFolderAccess Enabled' -Verb RunAs\""  

 [HKEY_CLASSES_ROOT\DesktopBackground\Shell\ControlledFolderAccess\shell\002flyout]  

 "MUIVerb"="Turn off Control folder access"  

 "HasLUAShield"=""  

 "Icon"="%ProgramFiles%\\Windows Defender\\EppManifest.dll,-101"  

 [HKEY_CLASSES_ROOT\DesktopBackground\Shell\ControlledFolderAccess\shell\002flyout\command]  

 @="PowerShell -windowstyle hidden -Command \"Start-Process cmd -ArgumentList '/s,/c,start PowerShell.exe Set-MpPreference -EnableControlledFolderAccess Disabled' -Verb RunAs\""`
3. Paste that script into Notepad by clicking in that app’s window and pressing**Ctrl** +**V** .  
![The controlled folder access registry script](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/controlled-folder-access-registry-script.jpg)
4. Next, press**Ctrl** +**Shift** +**S** to view Notepad’s "Save as" window.
5. Set the**Save as type** option to**All files** .  
![The All files option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/all-files-option.jpg)

1. Type**Turn on Control folder access.reg** inside the file name box.
2. Select to save the script to the desktop location.
3. Click**Save** to add the**Turn on Control folder access** registry file to the desktop.
4. Close the Notepad editor, and double-click the**Turn on Control folder access.reg** file on the desktop.  
![The registry script confirmation dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-script-confirmation-dialog.jpg)
5. Select**Yes** to confirm you trust the script.

 Now you can enable controlled folder access from the Windows context menu.

 Right-click any clear area of the desktop and select**Show more options** on Windows' context menu. Move the cursor over the**Turn On or Off Control** **folder access** submenu. Click**Turn on Control folder access** to enable that Windows Security feature.

 If you ever want to remove the controlled folder access context menu option, you can do so by deleting the registry key for it. This is how to delete the key for the**Turn On or Off Control folder access** submenu:

1. Launch the Registry Editor (our guide for [opening the Regedit registry app](https://www.makeuseof.com/windows-11-open-registry-editor/) includes various methods).
2. Go to this registry key location:  
`HKEY_CLASSES_ROOT\DesktopBackground\Shell\ControlledFolderAccess`
3. Right-click the Controlled Folder Access key to select**Delete** .  
![The Delete key option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-option-for-registry-key.jpg)
4. Click**Yes** to erase that key.

## How to Set Controlled Folder Access Exceptions

 The problem with controlled folder access is that it can stop legitimate apps from accessing required files when they need to. That can be an especially big issue for Windows gaming since untrusted games often can’t save progress with controlled folder access enabled. In-game settings can also reset when that feature is turned on.

 Fortunately, controlled folder access has an exclusion (exception) list for adding trusted apps. It won’t block any trusted apps on that list from modifying files within protected folders. You can add software to the CFA exclusion list as follows:

1. Bring up the**Controlled folder access** setting in Windows Security as covered in steps one to three of the first method above.
2. Click the **Allow an app through Controlled folder access navigation** link.
3. Press the**\+ Add an allowed app** button.  
![The Add an allowed app button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/add-an-allowed-app.jpg)
4. Click**Browse all** **apps** on the menu that appears.  
![The Browse all apps option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/browse-all-apps-option.jpg)
5. Select the EXE (application) file for a game or other software you want to exclude from controlled folder access.
6. Click**Open** to add the selected game or software.

## Enable Controlled Folder Access for Greater Ransomware Protection

 Turning on controlled folder access in Windows 10 and 11 with the above methods will give files on your PC an extra layer of protection from malware. It makes little difference how you enable that feature, but you can select more configuration options by using Group Policy Editor. Adding controlled folder access context menu settings also gives you a more direct way to toggle that feature on/off as required.

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
<li><a href="https://windows11.techidaily.com/sneak-peek-at-windows-11-writers-seven-vintage-traits/"><u>Sneak Peek at Windows 11' Writers: Seven Vintage Traits</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-creating-an-efficient-framework-for-ps3-game-screencasts-for-2024/"><u>[Updated] Creating an Efficient Framework for PS3 Game Screencasts for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-obstacle-fixing-windows-system-function-interruption/"><u>Overcoming the Obstacle: Fixing Windows System Function Interruption</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-how-to-upgrade-your-mac-with-macos-sierra-simplified/"><u>[New] How to Upgrade Your Mac with macOS Sierra Simplified</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11-menu-erase-show-more-options/"><u>Mastering Windows 11 Menu: Erase Show More Options</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-mfc71udll-not-found-or-missing-on-windows/"><u>How to Fix Mfc71u.dll Not Found or Missing on Windows</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-efficient-iphoneandroid-guide-for-tweets-as-visuals/"><u>[New] Efficient iPhone/Android Guide for Tweets as Visuals</u></a></li>
<li><a href="https://windows11.techidaily.com/path-to-start-driver-verifier-toolset-in-windows-11/"><u>Path to Start Driver Verifier Toolset in Windows 11</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-epic-game-viewing-spots-1-9/"><u>2024 Approved  Epic Game Viewing Spots #1-#9</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-exploring-the-best-a-ranked-list-of-6-top-transcription-automation-tools/"><u>New 2024 Approved Exploring the Best A Ranked List of 6 Top Transcription Automation Tools</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/enhancing-tweets-adding-media-files/"><u>Enhancing Tweets  Adding Media Files</u></a></li>
<li><a href="https://extra-information.techidaily.com/androids-superior-hd-vids-discover-the-best-apps/"><u>Android's Superior HD Vids  Discover the Best Apps</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-innovative-approaches-to-tiktok-video-construction/"><u>[New] In 2024, Innovative Approaches to TikTok Video Construction</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-resource-monitor-stalls-in-windows-11/"><u>Overcoming Resource Monitor Stalls in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-repair-windows-event-viewer-in-windows-11/"><u>Steps to Repair Windows Event Viewer in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/perfect-your-pc-settings-unlock-potential-using-alomware-suite/"><u>Perfect Your PC Settings: Unlock Potential Using AlomWare Suite</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-package-discrepinas-in-windows-photos-with-step-by-step-tips/"><u>Overcoming Package Discrepinas in Windows Photos with Step-by-Step Tips</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-from-setup-to-streaming-the-definitive-guide-for-live-tv-screen-sharing-on-windows/"><u>[New] 2024 Approved  From Setup to Streaming  The Definitive Guide for Live TV Screen-Sharing on Windows</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/undead-uprising-your-guide-to-engrossing-zombie-playtime-for-2024/"><u>Undead Uprising  Your Guide to Engrossing Zombie Playtime for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-gateway-to-information-conquering-windows-qr-code-scan/"><u>The Gateway to Information: Conquering Windows' QR Code Scan</u></a></li>
<li><a href="https://windows11.techidaily.com/precision-tools-for-crafting-custom-windows-filename-dates/"><u>Precision Tools for Crafting Custom Windows Filename Dates</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-how-to-produce-compelling-haul-content-on-a-budget/"><u>In 2024, How to Produce Compelling Haul Content on a Budget</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-no-budget-no-problem-the-finest-free-voice-alterer-for-valorant-players/"><u>2024 Approved  No Budget? No Problem! The Finest Free Voice Alterer for Valorant Players</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-turning-onoff-the-registry-editor/"><u>Techniques for Turning On/Off the Registry Editor</u></a></li>
<li><a href="https://windows11.techidaily.com/method-for-startingstopping-windows-installer/"><u>Method for Starting/Stopping Windows Installer</u></a></li>
<li><a href="https://windows11.techidaily.com/proven-file-sync-software-the-most-trusted-windows-picks/"><u>Proven File Sync Software: The Most Trusted Windows Picks</u></a></li>
<li><a href="https://extra-hints.techidaily.com/proven-steps-to-conquer-hdr-images-in-ps/"><u>Proven Steps to Conquer HDR Images in PS</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-tips-for-syncing-two-windows-displays/"><u>Quick Tips for Syncing Two Windows Displays</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-troubleshooting-ms-to-do-sync-failures/"><u>Tips for Troubleshooting MS To-Do Sync Failures</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-essential-skills-editing-blurring-and-background-removal/"><u>[New] The Essential Skills  Editing, Blurring, and Background Removal</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-microsofts-bluetooth-linked-application/"><u>Navigating Microsoft's Bluetooth-Linked Application</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/exploring-the-future-of-sound-alteration-10-leading-apps-for-changing-your-voice-for-2024/"><u>Exploring the Future of Sound Alteration 10 Leading Apps for Changing Your Voice for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-clarity-compass-directing-you-through-a-fuzzy-screen-fix-up/"><u>The Clarity Compass: Directing You Through a Fuzzy Screen Fix-Up</u></a></li>
<li><a href="https://windows11.techidaily.com/procedures-for-upholding-true-windows-time-values/"><u>Procedures for Upholding True Windows Time Values</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-premier-external-hard-drive-choices-for-xbox/"><u>[New] In 2024, Premier External Hard Drive Choices for Xbox</u></a></li>
<li><a href="https://windows11.techidaily.com/reconfiguring-start-menu-and-browser-by-defaults/"><u>Reconfiguring Start Menu and Browser by Defaults</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-messages-back-from-lava-by-fonelab-android-recover-messages/"><u>Simple ways to get lost messages back from Lava</u></a></li>
<li><a href="https://audio-editing.techidaily.com/unveiling-the-hidden-capabilities-of-twistedwaves-audio-manipulation-toolkit/"><u>Unveiling the Hidden Capabilities of TwistedWaves Audio Manipulation Toolkit</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-use-ispoofer-on-realme-narzo-n53-drfone-by-drfone-virtual-android/"><u>How to use iSpoofer on Realme Narzo N53? | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-in-2024-revolutionizing-your-sound-ioss-leading-audio-editing-applications/"><u>New In 2024, Revolutionizing Your Sound IOSs Leading Audio Editing Applications</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/venture-outside-of-tiktok-with-these-top-video-app-picks/"><u>Venture Outside of TikTok with These Top Video App Picks</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-from-footage-to-frames-screen-and-webcam-capturing-with-vimeo/"><u>[New] 2024 Approved  From Footage to Frames  Screen & Webcam Capturing with Vimeo</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/where-is-the-best-place-to-catch-dratini-on-apple-iphone-12-drfone-by-drfone-virtual-ios/"><u>Where Is the Best Place to Catch Dratini On Apple iPhone 12 | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-breaking-into-livestreaming-your-pathway-to-youtube-and-twitch-via-obs/"><u>[New] In 2024, Breaking Into Livestreaming  Your Pathway to YouTube & Twitch via OBS</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-credential-vault-hurdles/"><u>Overcoming Credential Vault Hurdles</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-to-resolving-pin-check-errors-on-windows-devices/"><u>Quick Guide to Resolving Pin Check Errors on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/perfecting-taskbar-setup-in-windows-11/"><u>Perfecting Taskbar Setup in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/no-more-fbm-hurdles-top-windows-troubleshooting-tips/"><u>No More FBM Hurdles: Top Windows Troubleshooting Tips</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-download-4k-videos-in-mp4-the-best-conversion-methods-explained/"><u>New 2024 Approved Download 4K Videos in MP4 The Best Conversion Methods Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-hello-fingerprint-setup-on-11/"><u>Mastering Windows Hello Fingerprint Setup on 11</u></a></li>
<li><a href="https://windows11.techidaily.com/rejoining-lost-astra-pilot-on-windows-11-machines/"><u>Rejoining Lost Astra Pilot on Windows 11 Machines</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-the-comprehensible-guide-to-mac-based-ootd-videography/"><u>[Updated] 2024 Approved  The Comprehensible Guide to Mac-Based OOTD Videography</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-the-best-of-the-best-essential-tablet-sketching-tools/"><u>[New] The Best of the Best  Essential Tablet Sketching Tools</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-unlocking-perfect-presentation-youtubes-video-ratio-insights/"><u>[New] Unlocking Perfect Presentation  YouTube's Video Ratio Insights</u></a></li>
<li><a href="https://windows11.techidaily.com/harnessing-the-power-of-microsofts-ai-code-helper/"><u>Harnessing the Power of Microsoft's AI Code Helper</u></a></li>
<li><a href="https://windows11.techidaily.com/supercharging-download-speeds-tips-and-tricks-for-ms-marketplace/"><u>Supercharging Download Speeds: Tips & Tricks for MS Marketplace</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-invisibility-of-task-view-on-bar/"><u>Techniques for Invisibility of Task View on Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-aesthetics-for-windows-terminal/"><u>Tailoring Aesthetics for Windows Terminal</u></a></li>
<li><a href="https://windows11.techidaily.com/low-ram-footprint-webbrowsers-an-intensive-benchmark-analysis/"><u>Low RAM Footprint Webbrowsers: An Intensive Benchmark Analysis</u></a></li>
</ul></div>
