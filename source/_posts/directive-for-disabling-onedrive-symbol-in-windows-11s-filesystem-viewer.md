---
title: Directive for Disabling OneDrive Symbol in Windows 11’S Filesystem Viewer
date: 2024-07-11T22:21:08.820Z
updated: 2024-07-12T22:21:08.820Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Directive for Disabling OneDrive Symbol in Windows 11’S Filesystem Viewer
excerpt: This Article Describes Directive for Disabling OneDrive Symbol in Windows 11’S Filesystem Viewer
keywords: OneDrive Disable Directive,Windows 11 FileViewer Change,Disable OneDrive Icon,Remove OneDrive Symbol,Windows Filesystem Update,OneDrive Exclusion Method,Diverting OneDrive in Win11
thumbnail: https://thmb.techidaily.com/35eb7ec70c3d68bdd6223aba9efbf03bc030e84e65b3cf939f3e4c2fcf3f5d40.jpg
---

## Directive for Disabling OneDrive Symbol in Windows 11’S Filesystem Viewer

 The OneDrive cloud storage client comes pre-installed on your Windows 11 computer. By default, you'll notice a OneDrive shortcut in the left pane of File Explorer, allowing quick access to your OneDrive files and folders.

 However, if you find the shortcut cluttering or ruining your File Explorer experience, you can remove it using a registry hack. Here's how to remove the OneDrive icon from File Explorer without uninstalling OneDrive.

## How to Remove OneDrive Shortcut From File Explorer via the Registry Editor

 You can remove the OneDrive icon from File Explorer using a registry hack. This way, you can get rid of the icon in File Explorer without uninstalling the OneDrive client. If you would rather remove the app entirely, follow our guide on [removing OneDrive on Windows 11](https://www.makeuseof.com/windows-11-disable-remove-onedrive/) .

 Note that modifying the Windows registry involves risk. We recommend you [create a system restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed with the steps below. A restore point will help you restore your computer in case something goes wrong.

 Once done, follow these steps to remove the OneDrive shortcut from File Explorer:

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open Registry Editor. Click**Yes** if prompted by**User Account Control (UAC).**
3. Next, in the Registry Editor, navigate to the following location. Copy and paste the registry path in the editor for quicker navigation:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
4. In the right pane, right-click on**System.IsPinnedToNameSpaceTree** DWORD value and select**Modify** .  
![remove onedrive icon windows 11 registry editor modify system is pinned to name space free](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-modify-system-is-pinnedtonamespace-free.jpg)
5. In the**Value data** field, type**0** and click**OK** .  
![remove onedrive icon windows 11 registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor.jpg)
6. Next, navigate to the following location in Registry Editor:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace`
7. In the left pane, right-click on**{018D5C66-4533-4307-9B53-224DE2ED1FE6}** and select**Delete** to remove the entry.  
![remove onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)
8. Once done, close the Registry Editor.
9. When you open File Explorer, the OneDrive icon will not be visible anymore.

## How to Show the OneDrive Icon Again in File Explorer

![show onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/show-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)

 To show the OneDrive icon in File Explorer, you’ll need to modify a registry entry again. Here’s how to do it.

1. Press**Win + R** to open**Registry Editor.**
2. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
3. In the right pane, double-click on**System.IsPinnedToNameSpaceTree** DWORD value.
4. Next, type**1** in the**Value data f** ield and click**OK** to save the changes.
5. Relaunch File Explorer to see the changes.

## Remove OneDrive Icon Without Uninstalling OneDrive

 This registry hack is a handy way to make the OneDrive icon disappear without deleting the app entirely from your PC. Alternatively, if you don’t use the service, you can completely remove OneDrive on Windows 11 or disable the service using Group Policy Editor.


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
<li><a href="https://windows11.techidaily.com/confronting-and-overcoming-failed-capture-issues-in-windows/"><u>Confronting and Overcoming Failed Capture Issues in Windows</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-2024-approved-the-ultimate-list-of-video-maker-apps-with-music-for-mobile-devices/"><u>Updated 2024 Approved The Ultimate List of Video Maker Apps with Music for Mobile Devices</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-open-your-apple-iphone-8-plus-without-a-home-button-drfone-by-drfone-ios/"><u>In 2024, How To Open Your Apple iPhone 8 Plus Without a Home Button | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-edge-tips-for-individualized-pattern-security-on-windows/"><u>Cutting-Edge Tips for Individualized Pattern Security on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/delving-into-individual-user-settings-on-group-policy-level/"><u>Delving Into Individual User Settings on Group Policy Level</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-pc-safety-introducing-your-unique-window-pin-design/"><u>Elevate PC Safety: Introducing Your Unique Window Pin Design</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-elevate-your-film-experience-integrating-subtitles-in-wmp/"><u>2024 Approved  Elevate Your Film Experience  Integrating Subtitles in WMP</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-conquer-common-errors-during-windows-11-rollout/"><u>How to Conquer Common Errors During Windows 11 Rollout</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-non-starting-windows-speech-to-text-feature/"><u>Fixing Non-Starting Windows Speech to Text Feature</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/in-2024-the-ultimate-guide-to-selecting-the-perfect-ogg-converter/"><u>In 2024, The Ultimate Guide to Selecting the Perfect OGG Converter</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-exploring-depth-of-field-for-giant-audio-waves/"><u>In 2024, Exploring Depth of Field for Giant Audio Waves</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/n-2024-12-premier-video-game-entrances-by-top-youtubers-free-and-paid-analysis/"><u>[New] In 2024, 12 Premier Video Game Entrances by Top Youtubers  Free & Paid Analysis</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-aerial-autonomy-groups-for-2024/"><u>[New] Aerial Autonomy Groups for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-easy-guide-how-to-bypass-vivo-y78-5g-frp-android-10111213-by-drfone-android/"><u>In 2024, Easy Guide How To Bypass Vivo Y78 5G FRP Android 10/11/12/13</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-missing-initialization-message-on-windows-pc/"><u>Fixing 'Missing Initialization' Message on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-to-fixing-0x80071a90-windows-error/"><u>Essential Guide to Fixing 0X80071A90 Windows Error</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-disparities-microsoft-and-default-windows-login-types/"><u>Dissecting Disparities: Microsoft and Default Windows Login Types</u></a></li>
<li><a href="https://windows11.techidaily.com/converting-files-a-step-by-step-windows-process/"><u>Converting Files: A Step-by-Step Windows Process</u></a></li>
<li><a href="https://windows11.techidaily.com/hide-your-contacts-delete-email-post-login-in-windows/"><u>Hide Your Contacts: Delete Email Post Login in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-steps-to-fix-error-code-0xc0000001-on-windows-pcs/"><u>Easy Steps To Fix Error Code 0XC0000001 on Windows PCs</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-2024-approved-unlocking-tiktoks-true-potential-with-apples-voice-activated-system/"><u>[New] 2024 Approved  Unlocking TikTok's True Potential with Apple's Voice-Activated System</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-frequent-anydesk-windows-complications/"><u>Conquering Frequent AnyDesk Windows Complications</u></a></li>
<li><a href="https://windows11.techidaily.com/darkeningwindowsnotepaddisplaysettings/"><u>DarkeningWindowsNotepadDisplaySettings</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-graphical-forecast-the-dominant-23-social-themes/"><u>[Updated] Graphical Forecast  The Dominant '23 Social Themes</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-debugs-top-windows-troubleshooting-apps/"><u>Deciphering Debugs: Top Windows Troubleshooting Apps</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-edit-and-send-fake-location-on-telegram-for-your-samsung-galaxy-f04-in-3-ways-drfone-by-drfone-virtual-android/"><u>In 2024, Edit and Send Fake Location on Telegram For your Samsung Galaxy F04 in 3 Ways | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/enhancing-your-iphones-screen-recording-skills-for-2024/"><u>Enhancing Your Iphone's Screen Recording Skills for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/from-play-to-watch-recording-with-a-nintendo-switch/"><u>From Play to Watch  Recording with a Nintendo Switch</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-vlc-capture-tool-assessment/"><u>[Updated] 2024 Approved  VLC Capture Tool Assessment</u></a></li>
<li><a href="https://windows11.techidaily.com/combat-unknown-obs-record-error-on-windows-11-pc/"><u>Combat Unknown OBS Record Error on Windows 11 PC</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-top-8-best-free-srt-translators-online-tips-to-choose/"><u>2024 Approved  Top 8 Best Free SRT Translators Online (Tips to Choose)</u></a></li>
<li><a href="https://windows11.techidaily.com/control-windows-11s-emphasis-and-search-highlight/"><u>Control Windows 11'S Emphasis and Search Highlight</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/024-approved-cutting-edge-pc-editing-techniques-enhancing-your-youtube-presence/"><u>[New] 2024 Approved  Cutting-Edge PC Editing Techniques  Enhancing Your YouTube Presence</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-change-from-mkv-to-mp4-format-with-windows-tools/"><u>Easy Change From MKV to MP4 Format with Windows Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-steam-data-flow-stopping-frustrating-speed-drops/"><u>Enhance Steam Data Flow: Stopping Frustrating Speed Drops</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-cyberlinks-screen-recorder-an-expert-evaluation/"><u>[Updated] Cyberlink's Screen Recorder  An Expert Evaluation</u></a></li>
<li><a href="https://windows11.techidaily.com/curbing-the-noise-quiet-explore-tab-behavior/"><u>Curbing the Noise: Quiet Explore Tab Behavior</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-code-of-high-quality-visuals-with-windows-11-hdr/"><u>Deciphering the Code of High-Quality Visuals with Windows 11 HDR</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-and-remedying-wins-error-messages/"><u>Deciphering & Remedying WINS Error Messages</u></a></li>
<li><a href="https://windows11.techidaily.com/direct-paths-opening-system-information-at-your-fingertips/"><u>Direct Paths: Opening System Information at Your Fingertips</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-contacts-from-vivo-y78plus-by-fonelab-android-recover-contacts/"><u>Undelete lost contacts from Vivo Y78+.</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-top-10-game-changing-apps-for-live-sports-and-premier-league-watching/"><u>[New] 2024 Approved  Top 10 Game-Changing Apps for Live Sports & Premier League Watching</u></a></li>
<li><a href="https://windows11.techidaily.com/disable-auto-updates-in-windows-and-office-instantly/"><u>Disable Auto-Updates in Windows & Office Instantly</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminate-loadlibrary-error-87-misconfiguration/"><u>Eliminate LoadLibrary Error 87 Misconfiguration</u></a></li>
<li><a href="https://windows11.techidaily.com/combining-kali-with-windows-os-seamlessly/"><u>Combining Kali with Windows OS Seamlessly</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-9-compelling-arguments-for-pc-dominance-over-macs/"><u>Demystifying: 9 Compelling Arguments for PC Dominance over Macs</u></a></li>
</ul></div>
