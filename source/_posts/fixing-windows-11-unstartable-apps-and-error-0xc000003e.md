---
title: "Fixing Windows 11: Unstartable Apps and Error 0xC000003E"
date: 2024-07-11T21:48:47.167Z
updated: 2024-07-12T21:48:47.167Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Fixing Windows 11: Unstartable Apps and Error 0xC000003E"
excerpt: "This Article Describes Fixing Windows 11: Unstartable Apps and Error 0xC000003E"
keywords: Win11 Crash Fix,Stop Windows App Failures,Resolve Error C000003E,Unstartable Apps Remedy,Windows 11 Stability Tips,Err0xC000003E Solution,Fixing Win11 System Errors
thumbnail: https://thmb.techidaily.com/078ec5c6b19df307c3d053f03815c7d21ecece8ed3226ebe1d118a70909568e6.jpg
---

## Fixing Windows 11: Unstartable Apps and Error 0xC000003E

 Error 0xc000003e is among the more widely reported startup issues for Windows software packages. That error displays this message when users select to run recently installed software, “The application was unable to start correctly (0xc000003e).” As a result, users can’t open and utilize programs for which that error message pops up.

 The 0xc000003e error has been mostly reported for the Zoom and Discord apps, but it can arise for other software. It’s an issue that can occur on Windows 11, 10, and 8 platforms. Here are some probable resolutions for fixing the 0xc000003e error.

## 1\. Set the Affected Software to Run With Admin Rights

 Firstly, try opening affected software with administrative rights. Some apps the 0xc000003e error occurs for might need more elevated permissions to operate. You can set the software to run as an administrator like this:

1. Open Windows Explorer and open the installation directly that includes the affected software.
2. Right-click the EXE (application) file for the software error 0xc000003e occurs and select**Properties** .
3. Then click**Compatibility** to access the settings below.  
![The Compatibility tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/compatibility-tab.jpg)
4. Select**Run this program as administrator** to set the program to run with elevated permissions.
5. Click**Apply** to save the selected options.
6. Press the**OK** button to exit the window.

## 2\. Run the Compatibility Troubleshooter

 Error 0xc000003e can sometimes occur because of software compatibility issues. Windows has a Compatibility Troubleshooter that applies recommended compatibility settings for programs, which might help some users fix the 0xc000003e error. This is how you run that compatibility troubleshooter in Windows:

1. First, open the**Compatibility** tab for an affected program as instructed in steps one to three of this guide’s first potential resolution.
2. Click the**Run compatibility troubleshooter** button.
3. Select the**Try recommended settings** option.  
![The Try recommended settings option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/try-recommended-settings-option.jpg)
4. Press the**Test the program** button to see if the software works with recommended settings.  
![The Test the program button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/test-the-program-button.jpg)
5. Select**Next** on the Program Compatibility Troubleshooter window.
6. Click**Yes, save these settings** if the**Test Program** option opened the software.  
![The Yes, save these settings option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/yes-option.jpg)
7. Close out of the troubleshooter, and restart your PC.

## 3\. Repair System Files

 System file corruption is one of the more regular causes of software startup errors in Windows. It’s recommended to run both Deployment Image Servicing and Management and System File Checker scans for repairing system files. A DISM scan can repair image component store corruption. These are the steps for running those scans in the Command Prompt:

1. Click the Windows taskbar’s search box or button (magnifying glass icon).
2. Type the search phrase**cmd** inside the text box.
3. Click**Command Prompt** with your mouse’s right button to select a**Run as administrator** option (see [how to run the Command Prompt as administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for more methods).
4. Then input this Prompt command and press**Return** :  
`DISM.exe /Online /Cleanup-image /Restorehealth`
5. Enter and execute the following SFC command:  
`sfc /scannow`  
![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-sfc-command.jpg)
6. Wait for the scan to reach a 100 percent mark and show a Windows Resource Protection outcome message.

## 4\. Run a Check Disk Scan

 You might need to fix error 0xc000003e because of a drive issue. There could be bad disk sectors on your PC’s hard drive that store data for affected software packages. Running a Check Disk (Chkdsk) scan could resolve such an issue. You can run such as scan with Windows’ Chkdsk utility as follows:

1. Bring up Command Prompt with administrative rights, as covered in resolution three.
2. Type in and execute this Chkdsk command:  
`chkdsk c: /f /r`
3. Press**Y** and**Enter** when prompted to schedule the scan for a restart.  
![A Chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/chkdsk-scan.jpg)
4. Next, select to restart Windows 11 or 10\. The Chkdsk utility will start its scanning after the restart.

## 5\. Run an Antivirus Scan

 Malware is another possible cause for the error 0xc000003e. So, it’s recommended users manually run an antivirus scan in Windows. This is how you can run an antivirus scan with the built-in Windows Security utility:

1. Open Windows Security by double-clicking the system tray (shield) icon for that app.
2. Select the**Virus & threat protection** tab.  
![The Home tab in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-virus-threat-protection-tab.jpg)
3. Click**Scan options** to view all settings for scanning.  
![The Scan options navigation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-scan-options-link.jpg)
4. Select the radio button for the**Full scan** option.  
![The Full scan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/full-scan-option.jpg)
5. Click**Scan now** to start the antivirus scanning.

## 6\. Temporarily Turn Off Antivirus Protection

 It’s not uncommon for some third-party antivirus software to sound false positive alarms for legitimate software processes. Such incorrect detection can generate all kinds of startup errors for flagged programs. If you have installed a third-party antivirus utility, turn its shield off and then try launching any software for which error 0xc000003e occurs.

 How exactly you disable third-party antivirus utilities varies between apps. However, you can usually select to turn off antivirus tools from their context menus. Right-click a system tray icon for your antivirus package to see if its context menu includes an option for disabling its shield. If it does, select to turn off the shield for an hour or so.

## 7\. Reinstall the Program Affected With Error 0xc000003e

 The 0xc000003e error can also arise because of corrupted software installations. You can fix a corrupted software installation by reinstalling the app. Reinstalling will also ensure you have the latest app version, which can address compatibility issues.

 Uninstall the affected app with one of the methods in our guide on [how to uninstall software in Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) . The Control Panel’s**Program and Features** applet or**Apps & Features** within Settings will be sufficient for uninstalling most software.

 When you’ve uninstalled the software, download its latest version from the publisher’s website. Then you can reinstall the program by opening the downloaded setup wizard.

![The Programs and Features Control Panel applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/programs-and-features-applet.jpg)

## 8\. Roll Back Windows With the System Restore Tool

 If you have System Restore enabled on your PC, that utility may provide a potential fix for 0xc000003e. System Restore enables you to roll Windows back to saved restoration points, which can fix corrupted system files. Selecting a restore point that predates the 0xc000003e error on your PC could fix the issue.

 Our guide on [how to create restore points on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) includes full instructions about how to roll back Windows with System Restore. Note that any software you installed after a selected restore point will not be available after rolling back Windows. You’ll need to reinstall the software packages removed for a chosen restoration point.

![The System Restore point tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-system-restore-point.jpg)

## Get Error 0xc000003e Sorted on Your PC

 So, that’s how you can get the 0xc000003e error sorted out in Windows 11 and 10\. We don’t promise those possible solutions will work for everybody. However, they’re some of the most likely ways to fix error 0xc000003e. Beyond those resolutions, clean booting and updating Windows might also help some users resolve error 0xc000003e.

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
<li><a href="https://youtube-stream.techidaily.com/in-2024-navigate-the-world-of-tags-for-superior-content-performance/"><u>In 2024, Navigate the World of Tags for Superior Content Performance</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-tips-and-tricks-for-setting-up-your-realme-12plus-5g-phone-pattern-lock-by-drfone-android/"><u>In 2024, Tips and Tricks for Setting Up your Realme 12+ 5G Phone Pattern Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-commands-for-keyboard-in-winos/"><u>Tailored Commands for Keyboard in WinOS</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-hourly-hitlist-the-leading-youtube-videos-by-watch-time/"><u>[Updated] 2024 Approved  Hourly Hitlist  The Leading YouTube Videos by Watch Time</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-activate-and-deactivate-window-icons-successfully/"><u>Steps to Activate and Deactivate Window Icons Successfully</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-command-prompt-gambits-for-a-laugh/"><u>Top 5 Command Prompt Gambits for a Laugh</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-offline-setting-up-on-disconnected-pcs/"><u>Win11 Offline: Setting Up on Disconnected PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-the-sleepy-slumber-of-hibernation-woes/"><u>Stop the Sleepy Slumber of Hibernation Woes</u></a></li>
<li><a href="https://extra-tips.techidaily.com/boosting-skype-engagement-best-zoom-utilization-techniques/"><u>Boosting Skype Engagement  Best Zoom Utilization Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-solutions-for-correction-of-network-security-discrepancy-in-windows-11/"><u>Top 5 Solutions for Correction of Network Security Discrepancy in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-non-signed-file-blockade-on-w10w11/"><u>Overcoming Non-Signed File Blockade on W10/W11</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-five-key-strategies-for-effective-script-narration/"><u>[New] In 2024, Five Key Strategies for Effective Script Narration</u></a></li>
<li><a href="https://windows11.techidaily.com/shine-the-light-how-to-make-your-cursor-more-noticeable-on-win1011/"><u>Shine the Light: How to Make Your Cursor More Noticeable on Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivating-frozen-wastebin-symbol-on-win11/"><u>Reactivating Frozen Wastebin Symbol on Win11</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/discover-the-best-movie-trailer-apps-for-iphone-and-ipad/"><u>Discover the Best Movie Trailer Apps for iPhone and iPad</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-internal-errors-during-remote-connections-in-windows-11/"><u>Solving Internal Errors During Remote Connections in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/triumph-over-microsoft-teams-stumbling-block-80080300-on-w11/"><u>Triumph over Microsoft Teams' Stumbling Block #80080300 on W11</u></a></li>
<li><a href="https://windows11.techidaily.com/polishing-old-videos-windows-madvr-techniques-unveiled/"><u>Polishing Old Videos: Windows MadVR Techniques Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-nvidia-driver-recommendations-entertainment-sector/"><u>Tailored Nvidia Driver Recommendations: Entertainment Sector</u></a></li>
<li><a href="https://windows11.techidaily.com/7-crucial-blunders-every-windows-11-novice-must-avoid/"><u>7 Crucial Blunders Every Windows 11 Novice Must Avoid</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-mystery-of-mouse-controls-on-windows-11/"><u>Unlock the Mystery of Mouse Controls on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-power-indicators-set-up-full-charge-notification-in-win11/"><u>Streamlining Power Indicators: Set Up Full Charge Notification in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-unseen-messages-in-windows-discord-software/"><u>Solving Unseen Messages in Windows Discord Software</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-perfecting-transition-timings-in-premiere-audio/"><u>[Updated] Perfecting Transition Timings in Premiere Audio</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-issues-with-windows-underperforming-monitor-app/"><u>Solving Issues with Windows' Underperforming Monitor App</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-top-tiktok-watermark-removal-tools-to-boost-your-videos/"><u>New Top TikTok Watermark Removal Tools to Boost Your Videos</u></a></li>
<li><a href="https://extra-tips.techidaily.com/unveil-top-8-sites-providing-free-download-of-3d-text-psdfiles/"><u>Unveil Top 8 Sites Providing Free Download of 3D Text PSDFiles</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-unforgettable-journeys-our-favorites-in-adventure-gameplay/"><u>[New] 2024 Approved  Unforgettable Journeys  Our Favorites in Adventure Gameplay</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/in-2024-the-ultimate-guide-to-avchd-video-editing-software/"><u>In 2024, The Ultimate Guide to AVCHD Video Editing Software</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-ms-sql-disconnects-malwarebytes-errors-in-1011-windows/"><u>Overcoming MS SQL Disconnects: Malwarebytes Errors in 10/11 Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/winphone-users-decide-between-unison-and-phone-link-apps/"><u>WinPhone Users: Decide Between Unison and Phone Link Apps</u></a></li>
<li><a href="https://fix-guide.techidaily.com/itel-a60s-screen-unresponsive-heres-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Itel A60s Screen Unresponsive? Heres How to Fix It | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/dissecting-purchased-engagement-assessing-its-role-in-channel-development-for-2024/"><u>Dissecting Purchased Engagement  Assessing Its Role in Channel Development for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-to-update-windows-spotlight-imagery/"><u>Step-by-Step to Update Windows Spotlight Imagery</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-essential-guide-best-screencasting-apps-at-no-cost/"><u>[Updated] 2024 Approved  Essential Guide  Best Screencasting Apps at No Cost</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-11s-hidden-error-code-0xc1900101/"><u>Unveiling Windows 11'S Hidden Error Code #0xC1900101</u></a></li>
<li><a href="https://windows11.techidaily.com/win11s-0x8007045d-an-effective-resolution-blueprint/"><u>Win11's 0X8007045D: An Effective Resolution Blueprint</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-the-ipogo-get-you-banned-and-how-to-solve-it-on-realme-gt-5-pro-drfone-by-drfone-virtual-android/"><u>Will the iPogo Get You Banned and How to Solve It On Realme GT 5 Pro | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-giggle-grove-memetic-magic-for-all-ages/"><u>[Updated] 2024 Approved  Giggle Grove  Memetic Magic for All Ages</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-non-operational-windows-defrag-tool/"><u>Troubleshooting Non-Operational Windows Defrag Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/accessing-windows-11-homespace-options/"><u>Accessing Windows 11 Homespace Options</u></a></li>
<li><a href="https://windows11.techidaily.com/triumph-over-troubled-windows-credentials/"><u>Triumph over Troubled Windows Credentials</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-the-beginners-guide-to-pioneering-minecraft-recordings-on-mac/"><u>[Updated] 2024 Approved  The Beginner's Guide to Pioneering Minecraft Recordings on Mac</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-standard-account-access-a-windows-guide/"><u>Securing Standard Account Access: A Windows Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-interruptexception-on-windows-11/"><u>Tackling the INTERRUPT_EXCEPTION on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-resolving-zero-x-error-in-windows-email-app/"><u>Steps for Resolving Zero X Error in Windows Email App</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-solo-journey-through-the-world-of-3d-printing-in-3dr/"><u>[New] Solo Journey Through the World of 3D Printing in '3DR'</u></a></li>
<li><a href="https://windows11.techidaily.com/perfecting-user-interaction-essential-modifications-for-windows-11s-taskbar/"><u>Perfecting User Interaction: Essential Modifications for Windows 11'S Taskbar</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-step-up-your-snapchat-game-with-three-simple-steps/"><u>[New] In 2024, Step Up Your Snapchat Game with Three Simple Steps</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/troubleshooting-lines-a-guide-to-resolving-warped-sound-issues-with-various-techniques/"><u>Troubleshooting Lines A Guide to Resolving Warped Sound Issues with Various Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/1719349405273-say-no-to-incompatibility-quick-solutions-for-vistawindows-7-users/"><u>Say No to Incompatibility: Quick Solutions for Vista/Windows 7 Users.</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-the-algorithm-advantage-tips-for-achieving-instagram-video-fame/"><u>2024 Approved  The Algorithm Advantage  Tips for Achieving Instagram Video Fame</u></a></li>
</ul></div>
