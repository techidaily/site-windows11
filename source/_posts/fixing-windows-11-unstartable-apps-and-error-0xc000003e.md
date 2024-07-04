---
title: "Fixing Windows 11: Unstartable Apps and Error 0xC000003E"
date: 2024-06-25T12:27:40.334Z
updated: 2024-06-26T12:27:40.334Z
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
3. Click**Command Prompt** with your mouse’s right button to select a**Run as administrator** option (see[how to run the Command Prompt as administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for more methods).
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

 Uninstall the affected app with one of the methods in our guide on[how to uninstall software in Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) . The Control Panel’s**Program and Features** applet or**Apps & Features** within Settings will be sufficient for uninstalling most software.

 When you’ve uninstalled the software, download its latest version from the publisher’s website. Then you can reinstall the program by opening the downloaded setup wizard.

![The Programs and Features Control Panel applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/programs-and-features-applet.jpg)

## 8\. Roll Back Windows With the System Restore Tool

 If you have System Restore enabled on your PC, that utility may provide a potential fix for 0xc000003e. System Restore enables you to roll Windows back to saved restoration points, which can fix corrupted system files. Selecting a restore point that predates the 0xc000003e error on your PC could fix the issue.

 Our guide on[how to create restore points on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) includes full instructions about how to roll back Windows with System Restore. Note that any software you installed after a selected restore point will not be available after rolling back Windows. You’ll need to reinstall the software packages removed for a chosen restoration point.

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
<li><a href="https://windows11.techidaily.com/sound-struggles-winning-back-noise-from-windows-spacebar/"><u>Sound Struggles: Winning Back Noise From Windows' Spacebar</u></a></li>
<li><a href="https://windows11.techidaily.com/overcome-chromes-file-uploading-frustrations-on-a-pc/"><u>Overcome Chrome's File Uploading Frustrations on a PC</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-windows-security-entry-error/"><u>Navigating Through Windows 'Security Entry Error'</u></a></li>
<li><a href="https://windows11.techidaily.com/a-guide-to-direct-access-for-the-curious-explorer-in-windows-11/"><u>A Guide to Direct Access for the Curious Explorer in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-of-non-existent-mmc-snaps/"><u>Unraveling the Mystery of Non-Existent MMC Snaps</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-the-glitch-windows-steam-play-links/"><u>Fixing the Glitch: Windows Steam Play Links</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-error-code-0x8007251d-in-microsofts-os-activation/"><u>Demystifying Error Code 0X8007251d in Microsoft's OS Activation</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-new-territory-altering-default-app-choices-in-windows-11/"><u>Navigating New Territory: Altering Default App Choices in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-stopping-self-activating-store-app/"><u>Strategies for Stopping Self-Activating Store App</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-microsoft-teams-instability-on-ws11ws10-devices/"><u>Preventing Microsoft Teams Instability on WS11/WS10 Devices</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/avoiding-frustrations-with-tiktok-glitches-for-2024/"><u>Avoiding Frustrations with TikTok Glitches for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-optimized-protocols-snapshots-of-gotomeetings-made-simple-for-2024/"><u>[Updated] Optimized Protocols  Snapshots of GoToMeetings Made Simple for 2024</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/2024-approved-mastering-silence-enhancing-audio-focus-in-adobe-premiere-pro-projects/"><u>2024 Approved Mastering Silence Enhancing Audio Focus in Adobe Premiere Pro Projects</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-in-2024-you-can-turn-a-tiktok-into-a-gif-now-heres-how/"><u>Updated In 2024, You Can Turn a TikTok Into a GIF Now. Heres How</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/the-hdr-sky-experience-online-resource-listing/"><u>The HDR Sky Experience  Online Resource Listing</u></a></li>
<li><a href="https://fake-location.techidaily.com/thinking-about-changing-your-netflix-region-without-a-vpn-on-nokia-g22-drfone-by-drfone-virtual-android/"><u>Thinking About Changing Your Netflix Region Without a VPN On Nokia G22? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-channel-your-earnings-effective-youtube-money-methods-for-2024/"><u>[Updated] Channel Your Earnings  Effective YouTube Money Methods for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-the-crazy-crews-top-10-unique-tiktok-games/"><u>[New] The Crazy Crew's Top 10 Unique TikTok Games</u></a></li>
<li><a href="https://android-unlock.techidaily.com/bypassing-google-account-with-vnrom-bypass-for-motorola-by-drfone-android/"><u>Bypassing Google Account With vnROM Bypass For Motorola</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-2024-approved-optimize-video-quality-with-expertise-in-studio-editor-use/"><u>[Updated] 2024 Approved  Optimize Video Quality with Expertise in Studio Editor Use</u></a></li>
</ul></div>
