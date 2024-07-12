---
title: Curbing Resource Conflicts on PCs Running Windows 10/11 (153 Chars)
date: 2024-07-11T22:30:27.182Z
updated: 2024-07-12T22:30:27.182Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Curbing Resource Conflicts on PCs Running Windows 10/11 (153 Chars)
excerpt: This Article Describes Curbing Resource Conflicts on PCs Running Windows 10/11 (153 Chars)
keywords: WinPC Peaceful Coexistence,Resolving Windows Resource Clashes,Minimizing Windows Conflicts,Efficient PC Resource Use,Streamlining Windows Performance,Managing Windows Resource Allocation,Reducing System Conflict in Windows 10/11
thumbnail: https://thmb.techidaily.com/ef8036d25906bf8bc672642e846b12e7bf455ea76b0df7385d290b38eb25840e.jpg
---

## Curbing Resource Conflicts on PCs Running Windows 10/11 (153 Chars)

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/decoding-bsod-0x0000003b-and-resolution-steps-in-windows-os/"><u>Decoding BSOD -0X0000003B & Resolution Steps in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/determining-public-ip-with-system-commands-windows/"><u>Determining Public IP with System Commands, Windows</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-harnessing-youtubes-power-for-personal-image-amplification/"><u>2024 Approved  Harnessing YouTube's Power for Personal Image Amplification</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-iphone-xs-passcode-without-computer-by-drfone-ios/"><u>How to Unlock iPhone XS Passcode without Computer?</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/android-users-discover-the-top-youtube-video-clips/"><u>Android Users, Discover the Top YouTube Video Clips</u></a></li>
<li><a href="https://windows11.techidaily.com/clear-the-way-to-privacy-with-simple-steps-for-ms-defender/"><u>Clear the Way to Privacy with Simple Steps for MS Defender</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-uncovering-methods-for-preserving-social-media-moments-status-videos/"><u>[Updated] 2024 Approved  Uncovering Methods for Preserving Social Media Moments - Status Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-quick-access-to-start-from-onedrive/"><u>Customizing Quick Access to Start From OneDrive</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-unleash-potential-a-comprehensive-guide-to-youtube-backlink-building/"><u>In 2024, Unleash Potential  A Comprehensive Guide to YouTube Backlink Building</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-elevating-speech-synthesis-converting-ssaxml-to-professional-srts/"><u>[New] In 2024, Elevating Speech Synthesis  Converting SSA/XML to Professional SRTs</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/do-you-want-to-use-luts-in-final-cut-pro-there-are-many-free-luts-for-fcpx-available-that-you-can-use-using-luts-you-can-create-professional-looking-content/"><u>Do You Want to Use LUTs in Final Cut Pro? There Are Many Free LUTs for FCPX Available that You Can Use. Using LUTs, You Can Create Professional-Looking Content</u></a></li>
<li><a href="https://windows11.techidaily.com/constructing-a-contextual-update-prompt-mechanism/"><u>Constructing a Contextual Update Prompt Mechanism</u></a></li>
<li><a href="https://windows11.techidaily.com/compilation-of-best-windows-11-art-software/"><u>Compilation of Best Windows 11 Art Software</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-laugh-ledger-the-premier-free-meme-repository/"><u>2024 Approved  Laugh Ledger  The Premier FREE Meme Repository</u></a></li>
<li><a href="https://audio-editing.techidaily.com/10-prime-pages-to-acquire-digital-ding-tone-files-with-hassle-free-downloads/"><u>10 Prime Pages to Acquire Digital Ding Tone Files with Hassle-Free Downloads</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-renowned-experts-exquisite-insta-highlight-creators/"><u>[New] Renowned Experts  Exquisite Insta Highlight Creators</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-from-youtube-to-mp3-how-to-find-the-best-conversion-software/"><u>In 2024, From YouTube to MP3 How to Find the Best Conversion Software</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-holographic-horizons-unveiling-new-dimensions-with-sci-fi-classics/"><u>In 2024, Holographic Horizons  Unveiling New Dimensions with Sci-Fi Classics</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-solve-avidemux-no-audio-problem-updated-guide/"><u>In 2024, Solve Avidemux No Audio Problem Updated Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/detecting-7-critical-windows-steps-for-cyber-threats/"><u>Detecting 7 Critical Windows Steps for Cyber Threats</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-account-lockout-reset-in-successive-login-attempts-windows-1011/"><u>Configuring Account Lockout Reset in Successive Login Attempts Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-windows-11s-application-could-not-be-started-error-xc000003e/"><u>Combatting Windows 11'S Application Could Not Be Started Error Xc000003e</u></a></li>
<li><a href="https://windows11.techidaily.com/curing-non-detection-of-unknown-usbs-on-windows-11/"><u>Curing Non-Detection of Unknown USBs on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/cut-down-complications-opt-for-simplicity-in-win11/"><u>Cut Down Complications: Opt for Simplicity in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/combating-computer-chaos-fixing-windows-non-responsive-keys/"><u>Combating Computer Chaos: Fixing Windows' Non-Responsive Keys</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-mastering-the-art-of-screen-recording-top-4-techniques-for-hp-users/"><u>[Updated] In 2024, Mastering the Art of Screen Recording  Top 4 Techniques for HP Users</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-edge-windows-the-ai-revolutions-new-frontier/"><u>Cutting-Edge Windows: The AI Revolution's New Frontier</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-to-resolve-error-0x8007007e-in-windows/"><u>Comprehensive Guide to Resolve Error 0X8007007E in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-to-fixing-device-path-errors/"><u>Comprehensive Guide to Fixing Device Path Errors</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-cutting-edge-techniques-to-upgrade-channel-descriptions-for-2024/"><u>[New] Cutting-Edge Techniques to Upgrade Channel Descriptions for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-access-issues-enabling-windows-logins-post-fail/"><u>Clearing Access Issues: Enabling Windows Logins Post-Fail</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-resource-unavailable-situations-on-windows-149-chars/"><u>Correcting 'Resource Unavailable' Situations on Windows (149 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/dive-into-windows-11-auditory-setup-and-use/"><u>Dive Into Windows 11 Auditory Setup and Use</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-procedure-call-failures-in-malwarebytes-for-windows-os/"><u>Combatting Procedure Call Failures in Malwarebytes for Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-taskbar-and-menu-on-windows-1011-easily/"><u>Customize Taskbar & Menu on Windows 10/11 Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-your-own-windows-voice-transcription-software-using-ahk-and-whisper/"><u>Crafting Your Own Windows Voice Transcription Software Using AHK and Whisper</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-disruption-in-skyrims-scripting/"><u>Deciphering the Disruption in Skyrim's Scripting</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-why-does-the-pokemon-go-battle-league-not-available-on-meizu-21-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Why does the pokemon go battle league not available On Meizu 21 Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/compreeable-approach-to-tackle-type-troubles-in-windows-11-error-0x80049dd3/"><u>Compreeable Approach to Tackle Type Troubles in Windows 11 (Error: 0X80049DD3)</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-no-more-youtube-thumbnails-disable-previews/"><u>In 2024, No More YouTube Thumbnails  Disable Previews</u></a></li>
<li><a href="https://windows11.techidaily.com/counteracting-dxgierrordeviceremoved-in-win-1011/"><u>Counteracting DXGI_ERROR_DEVICE_REMOVED in Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-x80070091-error-in-windows-steps-for-empty-directory-problem-solving/"><u>Deciphering X80070091 Error in Windows - Steps for 'Empty Directory' Problem Solving</u></a></li>
<li><a href="https://extra-skills.techidaily.com/insider-secrets-to-sharpen-your-photoshop-skills-for-2024/"><u>Insider Secrets to Sharpen Your Photoshop Skills for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-use-ispoofer-on-lava-yuva-2-drfone-by-drfone-virtual-android/"><u>How to use iSpoofer on Lava Yuva 2? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-xiaomi-redmi-12-drfone-by-drfone-virtual-android/"><u>How to Get and Use Pokemon Go Promo Codes On Xiaomi Redmi 12 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/dive-into-deeper-game-experience-incorporating-achievements-in-vintage-titles-through-retroarch/"><u>Dive Into Deeper Game Experience: Incorporating Achievements in Vintage Titles Through Retroarch</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-windows-11-upgrade-problem-code-0x800f0922/"><u>Correcting Windows 11 Upgrade Problem - Code 0X800f0922</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-edge-windows-11-shortcut-personalization-techniques/"><u>Cutting-Edge Windows 11 Shortcut Personalization Techniques</u></a></li>
<li><a href="https://facebook.techidaily.com/decoding-the-art-of-indirect-expression-on-social-media/"><u>Decoding the Art of Indirect Expression on Social Media</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/the-ultimate-guide-locating-the-heart-of-youtube-video-management/"><u>The Ultimate Guide  Locating the Heart of YouTube Video Management</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/audacity-alternatives-unveiled-the-best-free-nonaudacity-apps-on-your-desktop-for-2024/"><u>Audacity Alternatives Unveiled The Best Free Nonaudacity Apps on Your Desktop for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/delving-into-windows-tools-chkdsk-sfc-and-disms-functions/"><u>Delving Into Windows Tools: CHKDSK, SFC & DISM's Functions</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-iphoneipad-advanced-screen-recording-tips-new-methods-2023/"><u>[Updated] 2024 Approved  IPhone/iPad  Advanced Screen Recording Tips - New Methods 2023</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-steam-cloud-errors/"><u>Clearing Up Steam Cloud Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-windows-layout-fancywm-power-up/"><u>Customize Windows Layout: FancyWM Power Up</u></a></li>
<li><a href="https://windows11.techidaily.com/curtail-windows-system-acoustic-intensifiers/"><u>Curtail Windows System Acoustic Intensifiers</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-wintools-functions-what-makes-chkdsk-different/"><u>Decoding Wintools Functions: What Makes CHKDSK Different?</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-windows-11-editions-matching-home-to-pro-features/"><u>Decoding Windows 11 Editions: Matching Home to Pro Features</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>