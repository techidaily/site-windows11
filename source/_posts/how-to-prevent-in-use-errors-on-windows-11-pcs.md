---
title: How to Prevent 'In Use' Errors on Windows 11 PCs
date: 2024-07-11T21:53:01.378Z
updated: 2024-07-12T21:53:01.378Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Prevent 'In Use' Errors on Windows 11 PCs
excerpt: This Article Describes How to Prevent 'In Use' Errors on Windows 11 PCs
keywords: Fixing InUseError in Win11,Avoiding Windows 11 Freeze,Troubleshoot In Use Error,Prevent File Access Faults,Stop 'In Use' On PC,Resolve Active Files Issue,Eliminate OS Lockup Problems
thumbnail: https://thmb.techidaily.com/8da75a920197365538cecf50a6a02f169af5b1bab79994ca4fd6fd7629b24545.jpg
---

## How to Prevent 'In Use' Errors on Windows 11 PCs

 Users have reported “the requested resource in use” error message pops up on their PCs when trying to copy or move files from mobile devices to their Windows PCs. That error message’s heading also says, “error copying file or folder.” As a result, users can’t copy the files they need to.

 Here is how you can fix the “requested resource is in use” error on a Windows 10 or 11 PC.

## 1\. Check if the File Is Already in Use

![The End task option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-end-task-option.jpg)

 The “requested resource is in use” error message hints that the file (resource) you’re trying to copy is already in use. Thus, the copy operation cannot be completed because something else is using the file or folder. So, you might need to close some background processes to address this issue.

 First, move your mouse’s cursor over the File Explorer taskbar icon to see if there are any windows for active file operations. Cancel any active file operations you see. Then try copying the file again.

 If that doesn’t work, go into Task Manager and close superfluous third-party app background processes. Our guide to [fixing too many background processes on Windows](https://www.makeuseof.com/windows-pc-too-many-background-processes/) provides further instructions for how you can do that.

## 2\. Disable File Explorer’s Preview Pane

 Many users have fixed the “requested resource is in use” error by disabling File Explorer’s preview pane. That preview pane can hinder the file copy operation. You can disable File Explorer’s preview pane in Windows 11 as follows:

1. Press the **Win + E** key combination to launch File Explorer.
2. Then click the **View** menu button.
3. Select the **Show** submenu.
4. Deselect the **Preview pane** option.  
![The Preview pane option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/preview-pane-option.jpg)
5. Then try moving or copying your files again.

 The layout in Windows 10 File Explorer is a little different. To disable preview panes in that file manager, you’ll need to click the **View** tab. Then click **Preview pane** to deselect that option.

![The View tab in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-view-tab.jpg)

 Note that just disabling the preview pane might not always be enough. If that doesn’t work, try turning off the icon file view. To do so in Windows 11 File Explorer, click **View** and select the **List** or **Details view** option. You can select the same options on the **View** tab in Windows 10 File Explorer.

## 3\. Run a Malware Scan

 If the previous two resolutions don’t work for you, it’s probably the case that malware is causing the “requested resource is in use” error on your PC. SmartService is a trojan known to cause the “required source is in use” error. So, try running an antivirus scan with third-party software or Windows Security to kill SmartService. You can run an antivirus scan with Windows Security like this:

1. Double-click Windows Security’s icon in the system tray (the shield).
2. Click **Virus & threat protection** \> **Scan options** to access the Microsoft Defender antivirus tool.  
![The Scan options navigation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-scan-options.jpg)
3. Select the **Full scan** setting.
4. Click **Scan now** to initiate the malware scanning.  
![The Scan now button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-full-scan-radio-button.jpg)
5. Wait for the scanning to finish and select **Start actions** to remove detected malware.

 If you find Microsoft Defender is disabled and cannot turn it on, that’s a surefire sign the SmartService malware has infected your PC. SmartService is a rootkit trojan that blocks users from utilizing antivirus tools. That malware can also block the installation of some antivirus apps. In this case, the “requested resource in use” error can also occur when you try to run security apps.

 To circumvent such a block, try running a Windows Security or third-party app antivirus scan in safe mode instead. Our guide to [booting into safe mode on Windows](https://www.makeuseof.com/windows-11-boot-safe-mode/) includes a few different methods for entering that troubleshooting mode. Select to enable safe mode with networking.

![windows 11 startup settings safe mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-startup-settings-safe-mode.jpg)

## 4\. Disable Any Unknown Programs in Task Manager

 You might be able to disable a SmartService trojan from starting with Windows via Task Manager’s Startup tab. Look for and disable any suspicious programs listed on the **Startup** tab as follows:

1. Right-click a space on the taskbar to select a **Task Manager** context menu shortcut.
2. Next, click **Startup** to view that tab.
3. Look for any programs you don’t recognize on the **Startup** tab.
4. If you see anything suspicious, select that item and click the **Disable** button.  
![The Disable button on Task Manager's Startup tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-button.jpg)
5. Then restart your PC to see if the issue persists.

## 5\. Uninstall Any Suspicious-Looking Programs

 The SmartService trojan might also be listed within the Programs and Features Control Panel applet for uninstalling software. If you notice suspicious-looking software in Programs and Features, you can also select to uninstall it from there.

 Try uninstalling suspicious programs like this:

1. Bring up the Windows uninstaller tool with a method in our guide to opening Programs and Features.
2. Look through the list of installed software to see if there’s any suspicious-looking program there. Look for a program you can’t recall installing with an unknown publisher title.  
![The Uninstall option in Programs and Features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-uninstall-option4.jpg)
3. Right-click on the suspected SmartService malware and select **Uninstall**.
4. If you can’t uninstall the suspicious software, restart Windows in safe mode. Then try removing the same suspicious item via Programs and Features in safe mode.

 Also, clear temporary data after uninstalling SmartService to ensure the malware can’t re-emerge. To do so, you’ll need to clear out the Temp folder. This article about [deleting temporary files](https://www.makeuseof.com/windows-11-delete-temporary-files/) includes alternative methods for clearing data in the Temp folder.

## 6\. Perform a Factory Reset

 If the “requested resource is in use” error remains unresolved after trying all the potential resolutions above, performing a factory reset is the last resort. A factory reset will remove all programs not pre-installed with Windows and restore your PC to its default configuration. Applying this potential fix will likely eradicate malware causing the “requested resource is in use” error.

 The "Reset this PC" utility lets you factory reset Windows 11 and 10\. That tool includes an option you can select to stop the reset deleting user files. Our [how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) guide provides detailed guidelines for resetting the platform.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-keep-my-files-option.jpg)

## Get the “Requested Resource Is in Use” Error Sorted on Windows

 The potential solutions covered here are widely confirmed to resolve the “requested resource is in use” error. If it’s not caused by malware, disabling Explorer’s preview pane, as covered in resolution two, will usually fix the issue. Users confirm running an antivirus scan in safe mode (solution three) can fix the “required resource is in use” error when caused by malware.

 Here is how you can fix the “requested resource is in use” error on a Windows 10 or 11 PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-unadvertised-fullscreen-recordings-limit-10/"><u>[New] In 2024, Unadvertised Fullscreen Recordings (Limit 10)</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-tips-for-syncing-two-windows-displays/"><u>Quick Tips for Syncing Two Windows Displays</u></a></li>
<li><a href="https://audio-editing.techidaily.com/in-2024-professionals-guide-to-the-top-vocal-dampening-software-for-musicians-and-producers/"><u>In 2024, Professionals Guide to the Top Vocal Dampening Software for Musicians and Producers</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-hello-fingerprint-setup-on-11/"><u>Mastering Windows Hello Fingerprint Setup on 11</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/laylist-extraction-step-by-step-from-youtubes-archive-for-2024/"><u>[New] Playlist Extraction - Step by Step From YouTube's Archive for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-turning-onoff-the-registry-editor/"><u>Techniques for Turning On/Off the Registry Editor</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-tips-for-a-pristine-image-canvas-background-technique/"><u>In 2024, Tips for a Pristine Image  Canva's Background Technique</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-repair-windows-event-viewer-in-windows-11/"><u>Steps to Repair Windows Event Viewer in Windows 11</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-jumpstart-your-journey-learning-snapseed-techniques/"><u>[Updated] Jumpstart Your Journey  Learning Snapseed Techniques</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-professional-picks-top-gimbals-for-drones/"><u>In 2024, Professional Picks  Top Gimbals for Drones</u></a></li>
<li><a href="https://windows11.techidaily.com/6-cutting-edge-windows-programs-for-media-editing/"><u>6 Cutting-Edge Windows Programs for Media Editing</u></a></li>
<li><a href="https://windows11.techidaily.com/precision-tools-for-crafting-custom-windows-filename-dates/"><u>Precision Tools for Crafting Custom Windows Filename Dates</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-top-digital-depositories-customized-alert-sounds/"><u>[Updated] In 2024, Top Digital Depositories  Customized Alert Sounds</u></a></li>
<li><a href="https://windows11.techidaily.com/rejoining-lost-astra-pilot-on-windows-11-machines/"><u>Rejoining Lost Astra Pilot on Windows 11 Machines</u></a></li>
<li><a href="https://windows11.techidaily.com/perfecting-taskbar-setup-in-windows-11/"><u>Perfecting Taskbar Setup in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-task-managers-initial-screen-on-win11/"><u>Customizing Task Manager's Initial Screen on Win11</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-enhancing-visual-aesthetics-adding-black-bar-and-box-to-videos-for-2024/"><u>[Updated] Enhancing Visual Aesthetics  Adding Black Bar & Box to Videos for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-microsofts-bluetooth-linked-application/"><u>Navigating Microsoft's Bluetooth-Linked Application</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-elevating-your-viewing-experience-with-benq-sw320-monitor-for-2024/"><u>[New] Elevating Your Viewing Experience with BenQ SW320 Monitor for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-ultimate-blueprint-for-transferring-large-videos-between-apple-devices/"><u>2024 Approved  The Ultimate Blueprint for Transferring Large Videos Between Apple Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/supercharging-download-speeds-tips-and-tricks-for-ms-marketplace/"><u>Supercharging Download Speeds: Tips & Tricks for MS Marketplace</u></a></li>
<li><a href="https://windows11.techidaily.com/path-to-start-driver-verifier-toolset-in-windows-11/"><u>Path to Start Driver Verifier Toolset in Windows 11</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-explore-online-downloads-converting-youtube-to-mp3-made-simple/"><u>[Updated] 2024 Approved  Explore Online Downloads  Converting YouTube to MP3 Made Simple</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-unlock-the-full-potential-of-your-pcgaming-with-obs/"><u>[Updated] Unlock the Full Potential of Your PC/Gaming with OBS</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11-menu-erase-show-more-options/"><u>Mastering Windows 11 Menu: Erase Show More Options</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-building-a-better-tiktok-profile-step-by-step/"><u>[Updated] Building a Better TikTok Profile Step-by-Step</u></a></li>
<li><a href="https://windows11.techidaily.com/sneak-peek-at-windows-11-writers-seven-vintage-traits/"><u>Sneak Peek at Windows 11' Writers: Seven Vintage Traits</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-navigating-snapchats-networking-tools-with-finesse-for-2024/"><u>[New] Navigating Snapchat's Networking Tools with Finesse for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/perfect-your-pc-settings-unlock-potential-using-alomware-suite/"><u>Perfect Your PC Settings: Unlock Potential Using AlomWare Suite</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-in-2024-expert-approach-to-extracting-and-erasing-drum-tracks-from-songs-digitally-hosted-online/"><u>Updated In 2024, Expert Approach to Extracting and Erasing Drum Tracks From Songs Digitally Hosted Online</u></a></li>
<li><a href="https://windows11.techidaily.com/procedures-for-upholding-true-windows-time-values/"><u>Procedures for Upholding True Windows Time Values</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-access-your-outlook-preview/"><u>Unlocking Windows: Access Your Outlook Preview</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-invisibility-of-task-view-on-bar/"><u>Techniques for Invisibility of Task View on Bar</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/mastering-vocal-depth-techniques-for-a-deepened-tone-in-filmora/"><u>Mastering Vocal Depth Techniques for a Deepened Tone in Filmora</u></a></li>
<li><a href="https://windows11.techidaily.com/biometric-betrayal-windows-hellos-security-under-fire/"><u>Biometric Betrayal: Windows Hello's Security Under Fire?</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-top-20-youtube-bards-for-unforgettable-tales/"><u>[New] Top 20 YouTube Bards for Unforgettable Tales</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-quick-insights-for-accelerating-editing-tasks-efficiently/"><u>[New] Quick Insights for Accelerating Editing Tasks Efficiently</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-a-functional-taskbar-for-windows-11-tablets/"><u>Activating a Functional Taskbar for Windows 11 Tablets</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-life360-notify-when-you-log-out-on-xiaomi-13t-pro-drfone-by-drfone-virtual-android/"><u>Does Life360 Notify When You Log Out On Xiaomi 13T Pro? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/proven-file-sync-software-the-most-trusted-windows-picks/"><u>Proven File Sync Software: The Most Trusted Windows Picks</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/crafting-engagement-with-weblink-content-in-instagram-for-2024/"><u>Crafting Engagement with Weblink Content in Instagram for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/uninstalling-epic-games-with-ease-on-your-w11-computer/"><u>Uninstalling Epic Games with Ease on Your W11 Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-to-resolving-pin-check-errors-on-windows-devices/"><u>Quick Guide to Resolving Pin Check Errors on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-package-discrepinas-in-windows-photos-with-step-by-step-tips/"><u>Overcoming Package Discrepinas in Windows Photos with Step-by-Step Tips</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/-paradise-100plus-game-havens-explored/"><u>Pixel Paradise  100+ Game Havens Explored</u></a></li>
<li><a href="https://windows11.techidaily.com/decreasing-non-essential-tasks-windows-108/"><u>Decreasing Non-Essential Tasks Windows 10/8</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-logo-magic-sprucing-up-your-podcasts-visual-appeal/"><u>2024 Approved  Logo Magic  Sprucing Up Your Podcast's Visual Appeal</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-resource-monitor-stalls-in-windows-11/"><u>Overcoming Resource Monitor Stalls in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-fast-access-to-textual-explanations/"><u>Windows 11: Fast Access to Textual Explanations</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/latest-guide-how-to-bypass-honor-magic-6-pro-frp-without-computer-by-drfone-android/"><u>Latest Guide How To Bypass Honor Magic 6 Pro FRP Without Computer</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-building-wealth-through-video-content-revenue/"><u>[Updated] In 2024, Building Wealth Through Video Content Revenue</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-microsoft-store-error-code-0x80072f30/"><u>Troubleshooting Microsoft Store: Error Code 0X80072F30</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-obstacle-fixing-windows-system-function-interruption/"><u>Overcoming the Obstacle: Fixing Windows System Function Interruption</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-credential-vault-hurdles/"><u>Overcoming Credential Vault Hurdles</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-microsoft-store-error-0x80072efd/"><u>Unblocking Microsoft Store Error 0X80072EFD</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-troubleshooting-ms-to-do-sync-failures/"><u>Tips for Troubleshooting MS To-Do Sync Failures</u></a></li>
<li><a href="https://windows11.techidaily.com/method-for-startingstopping-windows-installer/"><u>Method for Starting/Stopping Windows Installer</u></a></li>
<li><a href="https://windows11.techidaily.com/the-clarity-compass-directing-you-through-a-fuzzy-screen-fix-up/"><u>The Clarity Compass: Directing You Through a Fuzzy Screen Fix-Up</u></a></li>
<li><a href="https://windows11.techidaily.com/tutorial-enabling-or-disabling-wi-fi-cost-meter-in-windows-11/"><u>Tutorial: Enabling or Disabling Wi-Fi Cost Meter in Windows 11</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/approved-making-sense-of-creative-commons-licensing-and-usage/"><u>2024 Approved  Making Sense of Creative Commons Licensing & Usage</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/earnings-explosion-how-to-maximize-income-on-youtube-shorts/"><u>Earnings Explosion  How to Maximize Income on YouTube Shorts</u></a></li>
<li><a href="https://windows11.techidaily.com/no-more-fbm-hurdles-top-windows-troubleshooting-tips/"><u>No More FBM Hurdles: Top Windows Troubleshooting Tips</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/skypes-premier-audio-capture-solutions-for-2024/"><u>Skype's Premier Audio Capture Solutions for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/calls-on-samsung-galaxy-a14-4g-go-straight-to-voicemail-12-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Calls on Samsung Galaxy A14 4G Go Straight to Voicemail? 12 Fixes | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-unleash-the-skys-potential-with-drone-livestreaming-on-fb/"><u>[Updated] In 2024, Unleash the Sky's Potential with Drone Livestreaming on FB</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-enhancing-visual-storytelling-adding-audio-elements-in-adobe-premiere-pro/"><u>New 2024 Approved Enhancing Visual Storytelling Adding Audio Elements in Adobe Premiere Pro</u></a></li>
<li><a href="https://screen-recording.techidaily.com/harmonyhook-tracker-extracting-sound-and-insights-for-2024/"><u>HarmonyHook Tracker  Extracting Sound & Insights for 2024</u></a></li>
<li><a href="https://techidaily.com/best-fixes-for-oppo-reno-8t-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Oppo Reno 8T 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-aesthetics-for-windows-terminal/"><u>Tailoring Aesthetics for Windows Terminal</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-a-comprehensive-guide-to-instagram-edits-for-professionals/"><u>[Updated] In 2024, A Comprehensive Guide to Instagram Edits for Professionals</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-this-article-i-will-share-top-40-keyboard-shortcuts-for-final-cut-pro-and-ive-categorized-them-to-make-these-easier-to-find-for-2024/"><u>In This Article, I Will Share Top 40 Keyboard Shortcuts for Final Cut Pro and Ive Categorized Them to Make These Easier to Find for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/reconfiguring-start-menu-and-browser-by-defaults/"><u>Reconfiguring Start Menu and Browser by Defaults</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-breaking-down-whatsapps-voice-call-features/"><u>In 2024, Breaking Down WhatsApp's Voice Call Features</u></a></li>
<li><a href="https://windows11.techidaily.com/the-gateway-to-information-conquering-windows-qr-code-scan/"><u>The Gateway to Information: Conquering Windows' QR Code Scan</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-joy-journeys-a-curated-list-of-the-best-humor-vids-online/"><u>2024 Approved  Joy Journeys  A Curated List of the Best Humor Vids Online</u></a></li>
</ul></div>
