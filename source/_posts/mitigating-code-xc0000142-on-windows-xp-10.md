---
title: Mitigating Code XC0000142 on Windows XP, 10
date: 2024-07-11T21:44:40.445Z
updated: 2024-07-12T21:44:40.445Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mitigating Code XC0000142 on Windows XP, 10
excerpt: This Article Describes Mitigating Code XC0000142 on Windows XP, 10
keywords: Windows XP XC Mitigation,XP C000142 Fixes,XP C000142 Security,Code C000142 XP,XC000142 Mitigation Windows,C000142 XC Protection XP,XP Countermeasure C000142
thumbnail: https://thmb.techidaily.com/99bb08ac4320921b1ffab3e5a5166b4c117aac2cf8ab3a2d0b2277eb6b26d486.jpg
---

## Mitigating Code XC0000142 on Windows XP, 10

 Error 0xc0000142 occurs when users try launching some Windows software packages. Those who encountered this issue usually see an error message that says, "The application was unable to start correctly (0xc0000142)." When that happens, the affected program refuses to launch.

 Unfortunately, error 0xc0000142 is a generic code that could affect many Windows software packages. However, many users report that it usually comes from Microsoft Office applications and games.

 So, if you're running into this issue, this is how you can fix error 0xc0000142 in Windows 11 and 10\.

## 1\. Run Affected Software With Admin Permissions

 Start your error 0xc0000142 troubleshooting by setting the affected software to run as an administrator. That will ensure the program can access more restricted file locations. You could potentially stop this error code by [setting the affected app to always run as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/).

## 2\. Set Affected Software to Run in Compatibility Mode

 If error 0xc0000142 arises for older software, there could be a compatibility issue with your PC's Windows 11/10 platform. Setting up an app or game to run in compatibility mode for an older Windows platform could resolve such an issue.

 This is how you can set your software to run in compatibility mode:

1. Press the **Windows** logo + **E** keyboard buttons and open the installation folder for your affected software.
2. Right-click the software's EXE (application) file to select **Properties**.  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-properties-option.jpg)
3. Click on the properties window's **Compatibility** tab.
4. Select the checkbox labeled **Run this program in compatibility mode**.  
![Run this program as an administrator checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-this-program-in-compatibility-mode-checkbox.jpg)
5. Choose the Windows OS that was the latest one in your software's release year within the drop-down menu. Selecting Windows 8 or 7 there will probably be sufficient for most apps.
6. Click **Apply** to set the new compatibility mode.
7. Select **OK** to exit the properties window.

 An alternative method is to [use the Windows 11 Program Compatibility Troubleshooter](https://www.makeuseof.com/program-compatibility-troubleshooter-windows-11-guide/). That tool automatically applies recommended compatibility settings, saving you time and effort.

## 3\. Scan Your PC's System Files

 Corrupted DLL (Dynamic Link Library) system files can cause error 0xc0000142\. You can check for and remedy system file corruption by [running the Windows System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/).

![The SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-sfc-scannow-command5.jpg)

 We also recommend running a Deployment Imaging Servicing Management scan command. That utility can remedy issues with the Windows system image. To run that tool, execute this command in the Command Prompt:

`DISM.exe /Online /Cleanup-image /Restorehealth`

## 4\. Set the Right System Locale

 Setting a correct system locale is an error 0xc0000142 fix that's worked for some uses. To apply this fix, you must select a system locale setting for non-unicode software that matches the correct region for your PC. You can set the suitable system locale as follows:

1. Press **Windows** key + **R**, type **Control Panel** in Run, and select **OK**.
2. Click on **Region** inside the All Control Panel Items window.  
![The Region applet in Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/region-in-control-panel.jpg)
3. Next, click on the **Administrative** tab.
4. Press the **Change system locale** button.  
![The Change system locale button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-system-locale-button.jpg)
5. Select the correct region for your PC in the drop-down menu.
6. Press **OK** in the Region Settings window.
7. Click on the **Apply** button to save your regional settings and **OK** to exit.

## 5\. Reregister DLL Files in Windows

 Lots of users have said reregistering all DLL files works for fixing error 0xc0000142\. This highlights that error 0xc0000142 arises because some required DLL files aren't correctly registered. There are many DLL files, but you can reregister them all by executing a single command as follows:

1. Press the **Windows** logo + **S** key simultaneously and input Command Prompt.
2. [Open the Command Prompt with admin privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/) by selecting **Run as administrator** for that app's search result.
3. Input this command for reregistering DLLs and hit **Return**:  
`for %1 in (*.dll) do regsvr32 /s %1`  
![The reregister all DLLs command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/re-register-all-command.jpg)
4. Then wait until all the DLLs have been registered before closing the Command Prompt.

## 6\. Run a CHKDSK (Check Disk) Scan

 Another possible reason for the error 0xc0000142 is that your PC has bad disk sectors. You can check for and repair bad disk sectors by [running a CHKDSK (Check Disk) scan](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) in the Command Prompt.

![The CHKDSK command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/chkdsk-scan.jpg)

## 7\. Update the Driver for Your PC's GPU (Graphics Processing Unit)

 If you need to fix the error 0xc0000142 for a Windows game, [updating your PC's graphics driver](https://www.makeuseof.com/update-graphics-drivers-in-windows-10/) might help. You can do that manually, using a third-party driver updater tool or AMD or NVIDIA software like GeForce Experience.

![A Download option in GeForce Experience](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/geforce-experience.jpg)

## 8\. Enable the .NET Framework 3.5 Feature

 Some programs need older .NET Framework versions to run in Windows. So, you might need to [enable .NET Framework 3.5 on Windows](https://www.makeuseof.com/windows-10-install-net-framework-version-35/) if that feature isn't available on your computer.

![The .NET Framework option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/net-framework-3-5.jpg)

## 9\. Edit the Windows Registry Key

 Many users who've fixed error 0xc0000142 confirm editing a Windows registry worked for them. Those users modified the value of a LoadAppInit\_DLL DWORD within the Windows key. These are the exact steps for applying this potential resolution:

 It's risky to edit the Registry. Always [back up your Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before making any changes to ensure you can revert to the original if you encounter issues after applying this fix.

1. Click on your taskbar's magnifying glass icon or the Search box to activate a file finder tool.
2. Enter the search phrase **regedit** into the file finder tool.
3. Select **Registry Editor** to view the registry window.
4. Go to this key location by entering the following path within Registry Editor's address bar:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\Current Version\Windows`  
![The Windows key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-key.jpg)
5. Double-click on the **LoadAppInit\_DLLs** DWORD.
6. Then input **0** in the **Value data** box if that DWORD is set differently.  
![The EDIT DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/edit-dword-window.jpg)
7. Click **OK** to apply the new value for the LoadAppInit\_DLLs DWORD.
8. Close out of the Registry Editor and restart your PC.

## 10\. Reinstall Affected Software Packages

 The final potential solution is reinstalling software packages for which the 0xc0000142 error occurs. Doing so will refresh and repair the software's files, which might be necessary if other resolutions don't work. Reinstalling is also another way to update apps.

![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-uninstall-option.jpg)

 There are [many ways to uninstall software in Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/), and you can choose any method to remove the app. However, if the error occurs when you open a game, you may need to uninstall it with its client software, such as the Epic Games Launcher. Then, reinstall the latest version of the app or game by downloading it from its website or gaming client.

## Get Error 0xc0000142 Sorted Out in Windows 11 and Windows 10

 Fixing error 0xc0000142 isn't always simple because that's an issue with many possible causes. There are numerous confirmed ways to fix that issue, many of which are covered here. So, you'll probably have to try applying at least a few of those troubleshooting methods to find one that gets error 0xc0000142 sorted out on your PC.

 Various third-party repair tools for Windows 11 and Windows 10 might also be useful for fixing error 0xc0000142\. Windows Repair, Advanced SystemCare, and Windows Repair Toolbox are among the best freeware repair tools for software troubleshooting.

 Unfortunately, error 0xc0000142 is a generic code that could affect many Windows software packages. However, many users report that it usually comes from Microsoft Office applications and games.

 So, if you're running into this issue, this is how you can fix error 0xc0000142 in Windows 11 and 10\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-tips.techidaily.com/ed-in-2024-the-ultimate-guide-to-youtube-caption-insertion/"><u>[Updated] In 2024, The Ultimate Guide to YouTube Caption Insertion</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-game-drives-in-xbox-app/"><u>The Ultimate Guide to Game Drives in Xbox App</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-ultimate-camcorders-for-high-quality-podcasts/"><u>[Updated] Ultimate Camcorders for High-Quality Podcasts</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-step-by-step-guide-invert-playback-videos-android/"><u>2024 Approved  Step-by-Step Guide  Invert Playback Videos Android</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-content-disconnected-error-on-windows-using-steam/"><u>Solving Content Disconnected Error on Windows Using Steam</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-essential-apps-for-professional-video-editing-on-androidpc/"><u>[New] 2024 Approved  Essential Apps for Professional Video Editing on Android/PC</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-inverted-indexing-flipping-your-iphones-videos/"><u>[Updated] Inverted Indexing  Flipping Your iPhone's Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-restore-error-0x80042306-quickly/"><u>Overcoming Windows Restore Error 0X80042306 Quickly</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-gopro-quik-for-pc-and-alternatives/"><u>New 2024 Approved GoPro Quik for PC and Alternatives</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-shoot-the-worlds-hustle-and-bustle-iphone-tips-for-shutter-speed-blurs/"><u>In 2024, Shoot the World's Hustle and Bustle  IPhone Tips for Shutter Speed Blurs</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-direct-access-to-windows-11-dialer-feature/"><u>Unlocking Direct Access to Windows 11 Dialer Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-integrating-alternative-antiviruses-with-ms-defender/"><u>Tips for Integrating Alternative Antiviruses with MS Defender</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-tutorial-for-managing-archive-files-via-cmd/"><u>The Ultimate Tutorial for Managing Archive Files via CMD</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-windows-update-blockage-error-e/"><u>Mending Windows Update Blockage, Error E</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-solutions-freeing-up-stuck-windows-11-pins/"><u>Quick Solutions: Freeing Up Stuck Windows 11 PINs</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-to-user-management-settings-in-windows-11-and-10/"><u>Navigate to User Management Settings in Windows 11 & 10</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/what-does-enter-puk-code-mean-and-why-did-the-sim-get-puk-blocked-on-oppo-a58-4g-device-by-drfone-android/"><u>What Does Enter PUK Code Mean And Why Did The Sim Get PUK Blocked On Oppo A58 4G Device</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-exploring-manycams-latest-video-capture-innovations/"><u>[Updated] 2024 Approved  Exploring ManyCam's Latest Video Capture Innovations</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-permission-fixes-for-installer-problems/"><u>Streamlining Permission Fixes for Installer Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/snipping-tool-or-printscreen-best-windows-capture-strategy/"><u>Snipping Tool or Printscreen? Best Windows Capture Strategy</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-solve-mkv-lagging-problem-in-moto-g-stylus-2023-by-aiseesoft-video-converter-play-mkv-on-android/"><u>How to solve MKV lagging problem in Moto G Stylus (2023)?</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-workspace-incorrante-folders-into-context-menu/"><u>Streamline Your Workspace: Incorrante Folders Into Context Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/stepwise-guide-for-crafting-personalized-audio-cds-from-your-mp3-collection-windows/"><u>Stepwise Guide for Crafting Personalized Audio CDs From Your MP3 Collection (Windows)</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-become-a-pro-voiceovers-on-tiktok/"><u>[Updated] 2024 Approved  Become a Pro  Voiceovers on TikTok</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-failed-app-install-in-windows-store/"><u>Troubleshooting Failed App Install in Windows Store</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-picku-or-better-a-critical-look-at-androids-premier-photo-tool/"><u>[New] PickU or Better? A Critical Look at Android's Premier Photo Tool</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-why-apple-discontinued-final-cut-express-in-2024-what-are-the-major-differences-between-final-cut-express-and-final-cut-pro/"><u>Updated Why Apple Discontinued Final Cut Express, In 2024 What Are the Major Differences Between Final Cut Express and Final Cut Pro?</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-digital-cash-kings-leading-youtube-creators/"><u>[New] In 2024, Digital Cash Kings  Leading YouTube Creators</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-absent-bluetooth-devices-manager/"><u>Remedy Absent Bluetooth Devices Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-error-0x80d03801-on-microsoft-store-pcs/"><u>Resolving Error 0X80D03801 on Microsoft Store PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-your-potential-7-proven-techniques-to-master-windows-based-studying/"><u>Unlock Your Potential: 7 Proven Techniques to Master Windows-Based Studying</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-defaults-permissions-restoration-guide/"><u>Unlocking Defaults: Permissions Restoration Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/unblock-your-computers-usb-hub-windows-fix-guide/"><u>Unblock Your Computer's USB Hub: Windows Fix Guide</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-in-2024-is-it-allowable-to-distribute-videos-via-social-networks/"><u>[Updated] In 2024, Is It Allowable to Distribute Videos via Social Networks?</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-cross-os-installation-of-kali-linux/"><u>Simplifying Cross-OS Installation of Kali Linux</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-pros-selection-excellent-webcam-recorders-windows-11/"><u>2024 Approved  Pro's Selection  Excellent Webcam Recorders Windows 11</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-leading-the-pack-2023s-8-facebook-movie-downloads/"><u>In 2024, Leading the Pack  2023'S #8 Facebook Movie Downloads</u></a></li>
<li><a href="https://windows11.techidaily.com/revitalizing-the-old-guard-running-windows-11-on-pre-ultimate-pcs-via-to-go-and-rufus/"><u>Revitalizing the Old Guard: Running Windows 11 on Pre-Ultimate PCs via To Go & Rufus</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/what-does-jailbreaking-iphone-14-pro-i-do-get-answers-here-drfone-by-drfone-ios/"><u>What Does Jailbreaking iPhone 14 Pro i Do? Get Answers here | Dr.fone</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-2024-approved-digitally-chronicled-tweets-of-the-year-so-far/"><u>[Updated] 2024 Approved  Digitally Chronicled Tweets of the Year So Far</u></a></li>
<li><a href="https://windows11.techidaily.com/three-steps-to-validate-windows-11-activation/"><u>Three Steps to Validate Windows 11 Activation</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-historical-insights-at-your-fingertips-top-10-for-students/"><u>[New] 2024 Approved  Historical Insights at Your Fingertips – Top 10 for Students</u></a></li>
<li><a href="https://techidaily.com/video-fixer-software-for-all-corrupt-videos-of-samsung-galaxy-a15-4g-by-stellar-video-repair-mobile-video-repair/"><u>Video Fixer Software for all Corrupt Videos of Samsung Galaxy A15 4G</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaim-soundfulness-overcoming-muted-mouses-cry/"><u>Reclaim Soundfulness: Overcoming Muted Mouse's Cry</u></a></li>
<li><a href="https://network-issues.techidaily.com/seamless-alignment-of-display-angles/"><u>Seamless Alignment of Display Angles</u></a></li>
<li><a href="https://network-issues.techidaily.com/windows-11-resolution-too-large/"><u>Window's 11 Resolution Too Large</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-np-setting-detection-mishap/"><u>Resolving Windows NP Setting Detection Mishap</u></a></li>
</ul></div>
