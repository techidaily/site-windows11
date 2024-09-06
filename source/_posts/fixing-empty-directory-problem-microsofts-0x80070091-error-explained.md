---
title: Fixing 'Empty Directory' Problem - Microsoft's 0X80070091 Error Explained
date: 2024-09-05T02:13:47.685Z
updated: 2024-09-06T02:13:47.685Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing 'Empty Directory' Problem - Microsoft's 0X80070091 Error Explained
excerpt: This Article Describes Fixing 'Empty Directory' Problem - Microsoft's 0X80070091 Error Explained
keywords: Windows 0X80070091 Fix,Empty Folder Issue,Directory Problem Troubleshooting,0X80070091 Error Resolution,Microsoft Error Correction,File System Anomaly Repair,Directory Access Failure Guide
thumbnail: https://thmb.techidaily.com/243178c138d6204ad2bbeb47ec4cfcdba020958c11cab04cb22d5f5327eef01b.jpg
---

## Fixing 'Empty Directory' Problem - Microsoft's 0X80070091 Error Explained

 Error 0x80070091 is a File Explorer issue that occurs for some users when they try to delete folders in Windows 11/10\. The error message says, “The directory is not empty," and you can't delete the folder that throws the error.

 The 0x80070091 message suggests that the error occurs because a folder isn’t empty. Yet, you should be able to erase directories that contain files without any issues. Furthermore, that error can also arise for empty folders. If you’re seeing the same folder error 0x80070091 in Windows, try applying these potential fixes.

## 1\. Try Erasing the Folder With the Command Prompt

 The Command Prompt gives users another way to delete folders in Windows 11/10\. So, you might be able to erase an affected folder without issues by using the Command Prompt. Using the Command Prompt might be more of a workaround, but at least you’ll get the folder deleted if works.

 Run Command Prompt with elevated (administrative) rights. Our guide about[running Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) includes numerous methods for launching that app. Then input this command and press**Enter** to delete an affected folder:

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

 Error 0x80070091 can be caused by some corrupted system files that need repairing. Running an SFC scan might both detect and repair corrupted system files and fix error 0x80070091 in the process. You can scan with SFC as instructed in our post for[running the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) .

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/sfc-scannow-command.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111982/7443" target="_top" id="2111982">
  <img src="//a.impactradius-go.com/display-ad/7443-2111982" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111982/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Check for Errors With a Disk Scan

 The 0x80070091 error is often due to corrupted or bad hard drive sectors. A lot of users have said they’ve resolved that issue by using the Check Disk (CHKDSK) utility for repairing bad drive sectors. This is how you can check for and repair bad sectors with Check Disk:

1. Open up the Command Prompt window with administrative rights.
2. Type in this Check Disk command and press**Enter:**  
`chkdsk /f /r C:`
3. Press**Y** to schedule the scan for a restart.  
![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/chkdsk-scan-command.jpg)
4. Click**Start** and select**Power** \>**Restart** to reboot.

 If the folder the 0x80070091 error occurs for isn’t on the C: drive, you’ll need to modify the above command. Replace**C:** with the letter of the storage drive that includes the affected folder.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886048/19272" target="_top" id="1886048">
  <img src="//a.impactradius-go.com/display-ad/19272-1886048" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886048/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Modify the Affected Folder’s Permissions

 Error 0x80070091 can arise because of insufficient folder permission. You might need to set an affected folder to full permission to resolve error 0x80070091\. To do that, change the folder’s permission settings as follows:

1. Open Explorer and right-click the affected folder to select**Properties** .  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/properties-option.jpg)
2. Click the window’s**Security** tab.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997680/19272" target="_top" id="1997680">
  <img src="//a.impactradius-go.com/display-ad/19272-1997680" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997680/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Next, press the**Advanced** button.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/security-tab.jpg)
4. Click**Change** beside the owner’s name.  
![The Advanced Security Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/advanced-security-settings-window.jpg)
5. Enter your Windows user account name inside the object name text box.  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2027181/19272" target="_top" id="2027181">
  <img src="//a.impactradius-go.com/display-ad/19272-2027181" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2027181/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Select a User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/select-a-user-or-group.jpg)
6. Then select the**Check Names** option and**OK** .
7. Click**Replace owner on subcontainers and objects** to select that setting.
8. Press the Advanced Security Settings window’s**Apply** and**OK** buttons.

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924297/11305" target="_top" id="924297">
  <img src="//a.impactradius-go.com/display-ad/11305-924297" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i110150.net/i/5597632/924297/11305" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975821/19272" target="_top" id="1975821">
  <img src="//a.impactradius-go.com/display-ad/19272-1975821" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975821/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-top-10-non-native-screen-capture-applications/"><u>[New] 2024 Approved  Top 10 Non-Native Screen Capture Applications</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-twitters-revised-video-standards-aspect-ratios-included/"><u>[New] 2024 Approved  Twitter's Revised Video Standards  Aspect Ratios Included</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/avigating-the-world-of-youtube-music-shorts/"><u>[New] Navigating the World of YouTube Music Shorts</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-ultimate-guide-to-the-best-high-res-capture-software/"><u>[New] Ultimate Guide to the Best High-Res Capture Software</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-top-6-apps-for-creating-film-captions-in-various-languages-for-2024/"><u>[Updated] Top 6 Apps for Creating Film Captions in Various Languages for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-streamlining-the-process-of-saving-ps3-gaming-moments/"><u>2024 Approved  Streamlining the Process of Saving PS3 Gaming Moments</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-unlock-the-potential-of-your-iphone-with-top-podcast-tips/"><u>2024 Approved  Unlock the Potential of Your iPhone with Top Podcast Tips</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-where-to-find-high-quality-pixel-ringers/"><u>2024 Approved  Where to Find High-Quality Pixel Ringers</u></a></li>
<li><a href="https://windows11.techidaily.com/establishing-controls-over-insider-build-exposure/"><u>Establishing Controls Over Insider Build Exposure</u></a></li>
<li><a href="https://windows11.techidaily.com/gateway-to-gaming-glory-using-dosbox-x-for-pc-classics/"><u>Gateway to Gaming Glory: Using DOSBox-X for PC Classics</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-0x0000004e-error-in-windows-10-and-11/"><u>How to Fix the 0X0000004E Error in Windows 10 and 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reactivate-sound-capture-in-obs-studio-on-windows-11-pcs/"><u>How to Reactivate Sound Capture in OBS Studio on Windows 11 PCs</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-i-transferred-messages-from-samsung-galaxy-xcover-6-pro-tactical-edition-to-iphone-12xs-max-in-seconds-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How I Transferred Messages from Samsung Galaxy XCover 6 Pro Tactical Edition to iPhone 12/XS (Max) in Seconds | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/is-sleep-hibernate-or-shutdown-best-for-your-windows-computer/"><u>Is Sleep, Hibernate, or Shutdown Best for Your Windows Computer?</u></a></li>
<li><a href="https://buynow-info.techidaily.com/kittys-eye-view-engaging-pet-watching-for-all/"><u>Kitty's Eye View: Engaging Pet Watching for All</u></a></li>
<li><a href="https://windows11.techidaily.com/master-linux-without-wsl/"><u>Master Linux without WSL</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-power-indicators-full-charge-alerts-for-windows-11/"><u>Mastering Power Indicators: Full Charge Alerts for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-secure-boot-settings-for-enhanced-vm-security/"><u>Mastering Secure Boot Settings for Enhanced VM Security</u></a></li>
<li><a href="https://windows11.techidaily.com/mobile-device-interaction-with-server-storage/"><u>Mobile Device Interaction with Server Storage</u></a></li>
<li><a href="https://windows11.techidaily.com/never-delay-in-decision-making-terminal-as-admin-instantly/"><u>Never Delay in Decision Making: Terminal as Admin, Instantly</u></a></li>
<li><a href="https://windows11.techidaily.com/note-taking-evolution-embracing-obsidian-canvas/"><u>Note-Taking Evolution: Embracing Obsidian Canvas</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-errors-in-windows-performance-dashboard/"><u>Overcoming Errors in Windows Performance Dashboard</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-errors-for-smooth-navigation/"><u>Overcoming Windows Errors for Smooth Navigation</u></a></li>
<li><a href="https://fox-helps.techidaily.com/prime-locations-for-obtaining-got-mobile-melodies-for-2024/"><u>Prime Locations for Obtaining GoT Mobile Melodies for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-unfreezing-stuck-spotify-app-in-win11-pcs/"><u>Quick Guide: Unfreezing Stuck Spotify App in Win11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaiming-control-from-a-wildly-wandering-mouse/"><u>Reclaiming Control From a Wildly Wandering Mouse</u></a></li>
<li><a href="https://windows11.techidaily.com/reconfiguring-saving-preferences-for-pubg-on-pc/"><u>Reconfiguring Saving Preferences for PUBG on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-spontaneous-command-triggers-in-os/"><u>Remedying Spontaneous Command Triggers in OS</u></a></li>
<li><a href="https://windows11.techidaily.com/removing-windows-forbidden-permission-block/"><u>Removing Windows Forbidden Permission Block</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-disappearing-windows-during-bootup/"><u>Resolving Disappearing Windows During Bootup</u></a></li>
<li><a href="https://windows11.techidaily.com/sayonara-to-sluggish-keys-top-tricks-for-win-11s-faster-typing/"><u>Sayonara to Sluggish Keys: Top Tricks for Win 11'S Faster Typing</u></a></li>
<li><a href="https://windows11.techidaily.com/seamlessly-switch-windows-11-walls-to-reflect-each-screens-style/"><u>Seamlessly Switch Windows 11 Walls to Reflect Each Screen's Style</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-a-blissful-experience-with-no-bluescreens-on-win11/"><u>Secure a Blissful Experience with No Bluescreens on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-your-windows-interface-personalized-pin-design-process/"><u>Secure Your Windows Interface: Personalized Pin Design Process</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-your-virtual-world-steps-for-epic-save-safety/"><u>Securing Your Virtual World: Steps for Epic Save Safety</u></a></li>
<li><a href="https://windows11.techidaily.com/shelve-the-start-of-edge-windows-11s-solution/"><u>Shelve the Start of Edge: Windows 11'S Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/simplified-gpo-analysis-via-gpresult-command/"><u>Simplified GPO Analysis via GPResult Command</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-resurrecting-non-responsive-windows-batch-jobs/"><u>Strategies for Resurrecting Non-Responsive Windows Batch Jobs</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-boost-utorrent-downloads-in-windows/"><u>Strategies to Boost uTorrent Downloads in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-troubled-waters-of-outlooks-winerror-x/"><u>Tackling the Troubled Waters of Outlook's WinError X</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-strategies-for-enhancing-virtual-memory-on-windows-11-systems/"><u>Tailored Strategies for Enhancing Virtual Memory on Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/tech-nostalgia-unleashed-windows-11-to-the-past/"><u>Tech Nostalgia Unleashed: Windows 11 to the Past</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-overcoming-admin-restrictions-on-setup-errors/"><u>Techniques for Overcoming Admin Restrictions on Setup Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/the-5-best-apps-to-skyrocket-your-productivity-on-windows-10-or-11/"><u>The 5 Best Apps to Skyrocket Your Productivity on Windows 10 or 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-5-best-fixes-for-hiberatus-computers/"><u>The 5 Best Fixes for Hiberatus Computers</u></a></li>
<li><a href="https://fake-location.techidaily.com/the-best-8-vpn-hardware-devices-reviewed-on-realme-12plus-5g-drfone-by-drfone-virtual-android/"><u>The Best 8 VPN Hardware Devices Reviewed On Realme 12+ 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/top-writing-helpers-to-transform-your-windows-experience/"><u>Top Writing Helpers to Transform Your Windows Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/triumphant-tech-reboot-triple-effect-windows-fixes/"><u>Triumphant Tech Reboot: Triple-Effect Windows Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-non-functioning-windows-event-log/"><u>Troubleshooting Non-Functioning Windows Event Log</u></a></li>
<li><a href="https://windows11.techidaily.com/tutorial-switching-to-quake-with-terminal/"><u>Tutorial: Switching to Quake with Terminal</u></a></li>
<li><a href="https://windows11.techidaily.com/tweaking-windows-lockscreensaver-timer/"><u>Tweaking Windows Lock/Screensaver Timer</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-full-potential-of-text-with-snipping-tool-on-win-11/"><u>Unlock Full Potential of Text with Snipping Tool on Win 11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/visionsonic-vsdc-review-ideal-substitutes/"><u>VisionSonic VSDC Review - Ideal Substitutes</u></a></li>
</ul></div>
