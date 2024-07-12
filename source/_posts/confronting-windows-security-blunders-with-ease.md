---
title: Confronting Windows Security Blunders with Ease
date: 2024-07-11T22:27:40.341Z
updated: 2024-07-12T22:27:40.341Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Confronting Windows Security Blunders with Ease
excerpt: This Article Describes Confronting Windows Security Blunders with Ease
keywords: Window Secure Fixes,Easy Security Solutions,Safe Windows Protection,Cybersecurity for Windows,Bypassing Window Hacks,Simplified OS Safety,Windows Security Tips
thumbnail: https://thmb.techidaily.com/da9934bcfc52017f09c9dd8ece522ceaa1a0b25522700613f88aea37d088bc1d.jpg
---

## Confronting Windows Security Blunders with Ease

 Windows Security incorporates the Microsoft Defender antivirus utility. However, some users can’t select to run Microsoft Defender scans because of an error message that says: “Unexpected error. Sorry, we ran into a problem.” That “Unexpected error” message pops up for some users when they select the**Virus & threat protection** tab in Windows Security.

 Consequently, the**Virus and threat protection tab** is inaccessible. That error means there’s an issue with the Windows antivirus tool. This is how you can resolve the “Unexpected error” issue.

## 1\. Check for New Windows Updates

 First, check for and install available Windows patch updates. Microsoft releases many patches to update Microsoft Defender. So, a patch update could feasibly resolve a Windows Security bug. Our [guide to manually updating Windows](https://www.makeuseof.com/update-windows-manually/#:~:text=Press%20the%20Win%20%2B%20I%20hotkeys,the%20Check%20for%20updates%20button.) tells you how to check for and install new updates in Settings.

![The Reset option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-option.jpg)

## 2\. Run System File and Image Scans

 System file issues might be causing the “Unexpected error” on your PC. To check if that’s the case, run a System File Checker scan within the Command Prompt. Such a scan will repair the corrupted system files detected. Our guide on [utilizing the SFC tool on Windows](https://www.makeuseof.com/system-file-checker-sfc-windows/) tells you how to scan system files with that utility.

![The SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-sfc-scannow-command.jpg)

 It’s also recommended to run a Deployment Image Servicing and Management scan, which can resolve Windows system image issues. The System File Checker tool doesn’t work when there are issues with the system image. So, try executing this command before the SFC scan as well:

`Dism /Online /Cleanup-Image /RestoreHealth`

## 3\. Remove Third-Party Antivirus Software

 Do you have an alternative third-party antivirus tool installed on your PC? If so, then there’s a possibility that antivirus software is causing the issue by conflicting with Microsoft Defender. At least try turning off the third-party AV utility by right-clicking the system tray icon for the app and selecting a disable context menu setting.

 If disabling the third-party antivirus software works, you have two options. You can re-enable that antivirus software and utilize the alternative antivirus scanner it provides. Or you can completely uninstall the third-party antivirus software if you prefer Microsoft Defender. Our guide to removing Windows software includes numerous methods for uninstalling programs.

## 4\. Modify the Windows Defender Registry Key

 This registry tweak for modifying a**DisableAntiSpyware** DWORD is one of the most widely confirmed fixes for the “Unexpected error” issue. So, maybe this could the “Unexpected error” solution you’re looking for as well. To apply this potential fix, edit the registry as follows:

1. Open Run, input**regedit** , and click**OK** .
2. Erase the current registry path and input this registry key location inside the address box:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender`
3. You can skip through to step five if the Windows Defender key includes a**DisableAntiSpyware** DWORD. However, users who can’t see that DWORD will need to right-click the**Windows Defender** key and select**New** \>**DWORD** .  
![The New and Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-new-key-options.jpg)
4. Type**DisableAntiSpyware** in the DWORD’s text box.
5. Double-click the**DisableAntiSpyware** DWORD to access its**Value** box.
6. Input**0** in the data box if that’s not the current value set.  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-edit-dword-window.jpg)
7. Select**OK** to confirm the value for the DWORD.

## 5\. Reset the Windows Security App

 Resetting Windows Security is worth trying whenever that app isn’t working right. In this case, something is up with the antivirus component of that app. You can reset that app within Settings or by executing a PowerShell command. Our article about [resetting Windows Security](https://www.makeuseof.com/windows-11-reset-windows-security/) tells you how to apply this potential resolution in three different ways.

![The Reset option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-option.jpg)

## 6\. Run a Malwarebytes Scan

 The “Unexpected error” can sometimes be caused by malware targeting Windows Security. Yet, users can’t purge malware with Windows Security because of the error. So, try running a scan with the freeware Malwarebytes version. Some users have said utilizing that software helped them resolve the “Unexpected error” issue. This is how you can run a Malwarebytes scan:

1. Open the [Malwarebytes](https://www.anrdoezrs.net/links/7251228/type/dlg/sid/UUmuoUeUpU2024249/https://www.malwarebytes.com/) website.
2. Click the**Free Download** button.
3. Activate Explorer by holding the**Windows** logo key and pressing**E** .
4. Go to the folder location containing the Malwarebytes setup file.
5. Double-click the**MBSetup.exe** file.
6. Click**Install** to add Malwarebytes to a default directory path.  
![The Install button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-button-for-malwarebytes.jpg)
7. Select**Me or my family** (for personal use) at the production selection step and click**Next** .
8. Click**Skip this for now** if you prefer not to install the additional Malwarebytes Browser Guard software.  
![The Skip this for now option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/skip-this-for-now-option.jpg)
9. Select**Done** to finish.
10. Malwarebytes will then open automatically. Select**Get started** \>**Maybe later** within the Malwarebytes window.
11. Click**Get started** again.
12. Select Malwarebytes’**Scan** option.  
![The Scan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/scan-option.jpg)
13. Press the**Quarantine** button after the scan.

 If this potential resolution works, you can keep Malwarebytes installed for manual scanning. It’s a 14-day trial of the Premium version, and the real-time protection will only last a couple of weeks. However, you can disable the Malwarebytes protection to ensure it doesn’t conflict with Microsoft Defender by right-clicking the utility’s system tray icon and deselecting the**Malware** ,**Ransomware** ,**Exploit** , and**Web Protection** options.

 The Microsoft Safety Scanner is an alternative to Malwarebytes you can run a malware scan with as well. However, that’s only a temporary scanning utility that expires after 10 days. You can download that utility from this [Microsoft page](https://learn.microsoft.com/en-us/microsoft-365/security/intelligence/safety-scanner-download?view=o365-worldwide) . Check out [our Microsoft Safety Scanner guide](https://www.makeuseof.com/microsoft-safety-scanner-guide/) for details about to purge malware with that tool.

## 7\. Check the "Turn Off Microsoft Defender Antivirus" Group Policy Setting

 If you’re a Windows Pro or Enterprise user, check that the the**Turn Off Microsoft Defender Antivirus** policy isn’t enabled in Group Policy. You can check that policy in the following steps:

1. [Open Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) by pressing the**Windows** logo +**S** hotkey, entering**gpedit.msc** in the search box, and selecting the**gpedit.msc** result.
2. Then navigate to this policy location in Group Policy’s sidebar:  
`Computer Configuration\Administrative Templates\Windows Components\Microsoft Defender Antivirus`
3. Next, double-click**Turn Off Microsoft Defender Antivirus** to check that policy.  
![The Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/microsoft-defender-antivirus-policy-settings.jpg)
4. Click**Not Configured** if that policy is set to**Enabled** .  
![The Turn Off Microsoft Defender Antivirus policy window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/turn-off-microsoft-defender-antivirus.jpg)
5. Select the policy’s**Apply** and**OK** options.

## 8\. Reset Windows or Perform an In-Place Upgrade

 Resetting Windows is a troubleshooting method that restores the platform to a default (factory) configuration. The Reset this PC tool gives you a simple way to reinstall the platform and preserve user files, but you’ll need to reinstall apps.

[Applying a Windows reset](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) might resolve some deeper system issues causing the “Unexpected error” issue. However, it’s only advised to do so if none of the other potential solutions suggested here work.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-this-pc-tool.jpg)

 An in-place upgrade is an alternative troubleshooting method to resetting Windows. Performing an in-place upgrade will reinstall Windows by installing the latest build version. So, it’s like a reset, but the advantage is that an in-place upgrade preserves the apps you’ve installed. This guide to [performing an in-place upgrade on Windows](https://www.makeuseof.com/in-place-upgrade-windows-11/) provides full instructions for upgrading Windows 11 in such a way.

 However, you could feasibly upgrade to a new Windows version via Settings. Open**Windows Update** in the Settings app to see if there’s a version upgrade available. If so, select to upgrade to the latest Windows build from there.

## Run a Scan With Windows Security Again

 You’ll probably be able to access the antivirus-scanning options in Windows Security again after applying the potential solutions covered here. So, try applying all those potential “Unexpected error” resolutions in the order specified to find one that works on your Windows PC. You can also contact the [Microsoft Windows support service](https://support.microsoft.com/en-us/home/contact?SourceApp=smc2&ContactUsExperienceEntryPointAssetId=Google) for further assistance but give the potential fixes outlined here a try first.

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
<li><a href="https://windows11.techidaily.com/craft-an-individualized-look-for-your-schedule-in-windows-outlook/"><u>Craft an Individualized Look for Your Schedule in Windows Outlook</u></a></li>
<li><a href="https://windows11.techidaily.com/direct-guide-to-reactivate-print-spool/"><u>Direct Guide to Reactivate Print Spool</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-innovative-home-designs-for-modern-minecraft-world/"><u>In 2024, Innovative Home Designs for Modern Minecraft World</u></a></li>
<li><a href="https://windows11.techidaily.com/concealing-the-taskbar-written-words-in-windows-11-ui/"><u>Concealing the Taskbar’ Written Words in Windows 11 UI</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-the-art-of-tracking-network-activity-via-netstat-in-win11/"><u>Discover the Art of Tracking Network Activity via Netstat in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-the-unseen-scroll-phenomenon-in-windows/"><u>Conquer the Unseen Scroll Phenomenon in Windows</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-innovative-iphone-close-up-tips-for-astounding-photos/"><u>2024 Approved  Innovative iPhone Close-Up Tips for Astounding Photos</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/collect-premium-audio-for-video-editors-for-2024/"><u>Collect Premium Audio for Video Editors for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/cross-network-stealth-securing-data-flow-in-winos/"><u>Cross-Network Stealth: Securing Data Flow in WinOS</u></a></li>
<li><a href="https://windows11.techidaily.com/ditching-windows-11-standards-top-10-app-list/"><u>Ditching Windows 11 Standards: Top 10 App List</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-occupied-files-a-guide-for-windows-11-users/"><u>Clearing Occupied Files: A Guide for Windows 11 Users</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-decoding-high-impact-tiktok-campaign-techniques/"><u>2024 Approved  Decoding High-Impact TikTok Campaign Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/convenient-telnet-setup-for-modern-windows-systems-wins/"><u>Convenient Telnet Setup for Modern Windows Systems (Wins)</u></a></li>
<li><a href="https://windows11.techidaily.com/command-center-changing-your-onedrive-storage-territory-on-windows-10/"><u>Command Center: Changing Your OneDrive Storage Territory on Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-terminal-in-win11-start-fresh/"><u>Configuring Terminal in Win11: Start Fresh</u></a></li>
<li><a href="https://windows11.techidaily.com/compact-windows-powered-systems-unveiled/"><u>Compact Windows-Powered Systems Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/convenient-quick-settings-navigating-win-11-interface/"><u>Convenient Quick Settings: Navigating Win 11 Interface</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/in-2024-10-top-rated-vegas-pro-alternatives-for-mac-a-comprehensive-review/"><u>In 2024, 10 Top-Rated Vegas Pro Alternatives for Mac A Comprehensive Review</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-the-ultimate-guide-to-selecting-facebook-live-capturers/"><u>[Updated] 2024 Approved  The Ultimate Guide to Selecting Facebook Live Capturers</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-2024-approved-how-to-crop-videos-in-windows-media-player/"><u>New 2024 Approved How to Crop Videos in Windows Media Player</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-enhancing-your-podcast-experience-the-art-of-editing-in-garageband-for-2024/"><u>[Updated] Enhancing Your Podcast Experience  The Art of Editing in GarageBand for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/discovering-surface-laptop-studio-2-the-near-perfect-companion/"><u>Discovering Surface Laptop Studio 2 - The Near-Perfect Companion</u></a></li>
<li><a href="https://windows11.techidaily.com/confronting-error-code-0x8007045d-a-guide-for-windows-11-users/"><u>Confronting Error Code 0X8007045d: A Guide for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/converting-oculus-quest-2-to-windows-vr-compatibility-level/"><u>Converting Oculus Quest 2 to Windows VR Compatibility Level</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/guide-to-mirror-your-oppo-a58-4g-to-other-android-devices-drfone-by-drfone-android/"><u>Guide to Mirror Your Oppo A58 4G to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-microsoft-store-failure-codes-x800704cf/"><u>Disabling Microsoft Store Failure Codes X800704CF</u></a></li>
<li><a href="https://windows11.techidaily.com/cut-down-clutter-how-to-set-up-autofiledeletion-on-winos/"><u>Cut Down Clutter: How to Set Up AutoFileDeletion on WINOS</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-breaking-into-the-top-1m-youtube-view-hacks-revealed/"><u>In 2024, Breaking Into the Top 1M  YouTube View Hacks Revealed</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-high-dpi-display-issues-in-windows/"><u>Clearing Up High DPI Display Issues in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-overcoming-0x80072af9-errors/"><u>Decoding and Overcoming 0X80072AF9 Errors</u></a></li>
<li><a href="https://win11.techidaily.com/refinement-of-visuals-windows-11-dpi-tweaks/"><u>Refinement of Visuals: Windows 11 DPI Tweaks</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-advanced-windows-index-features/"><u>Configuring Advanced Windows Index Features</u></a></li>
<li><a href="https://windows11.techidaily.com/contrasting-the-workflow-of-cloud-based-and-disk-installed-windows-oses/"><u>Contrasting the Workflow of Cloud-Based & Disk Installed Windows OSes</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-unlocking-your-youtube-success-story-a-comprehensive-guide-to-creative-studio/"><u>2024 Approved  Unlocking Your Youtube Success Story  A Comprehensive Guide to Creative Studio</u></a></li>
<li><a href="https://windows11.techidaily.com/discerning-the-divergences-between-terminal-and-powershell/"><u>Discerning the Divergences Between Terminal & PowerShell</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-factory-seal-on-windows-11/"><u>Disabling Factory Seal on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-how-to-activate-and-use-mouseclicklock-efficiently/"><u>Decoding How to Activate and Use MouseClickLock Efficiently</u></a></li>
<li><a href="https://windows11.techidaily.com/digital-illusions-sketching-secrets-for-windows-users/"><u>Digital Illusions: Sketching Secrets for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-zoom-anomalies-addressing-error-1132-in-windows-11/"><u>Correcting Zoom Anomalies: Addressing Error 1132 in Windows 11</u></a></li>
</ul></div>
