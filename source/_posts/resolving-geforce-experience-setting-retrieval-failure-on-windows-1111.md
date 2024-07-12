---
title: Resolving 'GeForce Experience' Setting Retrieval Failure on Windows 11/11
date: 2024-07-11T21:47:01.846Z
updated: 2024-07-12T21:47:01.846Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving 'GeForce Experience' Setting Retrieval Failure on Windows 11/11
excerpt: This Article Describes Resolving 'GeForce Experience' Setting Retrieval Failure on Windows 11/11
keywords: GeForceXP Windows Error,XPtFailer RetrieveSetting,FixXPSettingsWin11,Win11GeForceRetrieval,ResolveGPXOnWin11,XPErrorSolutionWin11,GeForceXPWin11Repair
thumbnail: https://thmb.techidaily.com/410b1a4d385c6e4b30f8c2bafd9b2a73f332bf6953f02a101819f0b8ffe4d954.jpg
---

## Resolving 'GeForce Experience' Setting Retrieval Failure on Windows 11/11

 GeForce Experience is software with which users can usually optimize their games. However, some GeForce Experience users can’t optimize games with that software because of an “unable to retrieve settings” error. Some users see that error message when they click games’ thumbnails in GeForce Experience.

 Consequently, users can’t select the Optimize option for games that show the “unable to retrieve settings” error. That’s a bit annoying for players seeking optimal gaming performance. This is how you can fix GeForce Experience’s “unable to retrieve settings” error within Windows.

## 1\. Run GeForce Experience With Administrative Rights

 A few players have said running GeForce Experience with admin rights resolved the “Unable to retrieve settings” error for them. So, that’s a simple resolution worth trying. To see if that works for you, bring up the Windows search tool and input GeForce Experience. Then right-click the GeForce Experience search result to select **Run as administrator**.

![The Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-as-administrator-option4.jpg)

 If that works, set GeForce Experience to always run with elevated user rights. Then you won’t need to select the **Run as administrator** option all the time. Our guide for [always running apps as an administrator on Windows](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) tells you how to set software packages to start with elevated permissions.

## 2\. Remove Scan Locations

 Some GeForce Experience users confirm that removing scan locations and rescanning fixes the “Unable to retrieve settings” error. This is how you can remove scan locations in GeForce Experience:

1. Open the GeForce Experience window.
2. Click the **Settings** button by your user account name.  
![The Settings menu button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/settings-button.jpg)
3. Select the **Games & Apps** tab.
4. Then select a scan location and click **Remove**. Repeat this step to remove all scan locations shown.  
![The Remove button for scan locations](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/remove-button.jpg)
5. Press the **Scan Now** button to rescan.

## 3\. Delete the CefCache Folder

 CefCache is a GeForce Experience folder that stores cached data. GeForce Experience optimization issues can arise when that cache includes corrupted configuration files. You might be able to resolve the “Unable to retrieve settings” error by deleting the CafCache folder like this:

1. Ensure GeForce Experience isn’t already running by closing it on the taskbar and the system tray. Right-click the NVIDIA system tray and select **Exit** to close GeForce Experience there.
2. Open File Explorer (press **Win + E**) and input this path in the folder address bar:  
`C:\Users\<user folder>\AppData\Local\NVIDIA Corporation\NVIDIA GeForce Experience`  
![The CefCache folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/cefcache-folder.jpg)
3. Right-click the **CefCache** folder to select **Delete**.  
![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/delete-button.jpg)
4. Then launch the GeForce Experience software.
5. Input your GeForce Experience account details again and click **Log In**.

## 4\. Restore Default NVIDIA 3D Settings

 Restoring the NVIDIA 3D Settings to default is another potential fix for the “Unable to retrieve settings” error that has worked for some users. Applying this resolution will reset all 3D settings you’ve changed in the NVIDIA Control panel to a default configuration. You can apply this potential resolution as follows:

1. Right-click on the NVIDIA logo inside the system tray area to select **Control Panel**.
2. Next, select **Manage 3D** settings in the NVIDIA Control Panel.
3. Click **Restore** on the **Global Settings** tab.  
![The Restore button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/restore-button.jpg)
4. Select **Yes** to reset the settings.

## 5\. Delete the Steam User Data

 The “Unable to retrieve settings” error can arise for Steam games because of a data conflict with Steam. Players have confirmed erasing data in a Steam userdata subfolder works for fixing this issue. So, that’s a possible resolution recommended for all players who’ve got Steam installed. Clear Steam’s userdata folder like this:

1. Simultaneously press **Win + X** and select the File Explorer shortcut.
2. Input this userdata folder path in Explorer’s address bar:  
`C:\Program Files\Steam\userdata`  
![Steam's userdata folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/userdata-folder.jpg)
3. Right-click a subfolder that doesn’t have any numbers in its name within the userdata folder and select **Delete**.
4. Repeat the previous step to delete all subfolders in userdata with non-numeric titles like anonymous, etc.

## 6\. Perform Some Generic Windows Fixes

 There are a few Windows-based fixes you can try to get rid of this error.

### Erase Temporary Windows Data

 The Temp folder stores temporary files. GeForce Experience users confirm deleting data in that Temp folder can fix the “Unable to retrieve settings” issue. So, try eradicating data in that folder with one of the methods in our guide to [deleting temporary files](https://www.makeuseof.com/windows-11-delete-temporary-files/)[in Windows 11](http://www.makeuseof.com/windows-11-delete-temporary-files/).

![disk-cleanup-tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disk-cleanup-tool.jpg)

### Install the Latest NVIDIA Driver for Your GPU

 Although less likely, corrupted NVIDIA GPU driver files can feasibly cause the “Unable to retrieve settings” error to arise. In this case, installing the latest NVIDIA graphics drivers could be a solution for some users. Uninstall your PC’s current NVIDIA graphics driver and install the latest one by downloading it from the NVIDIA website.

 Follow the instructions in our guide to [installing and cleanly reinstalling GPU drivers](https://www.makeuseof.com/how-to-cleanly-install-and-reinstall-gpu-drivers-on-windows/) to apply this potential fix with the DDU software.

![The NVIDIA driver downloads page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/nvidia-driver-downloads.jpg)

### Disable Third-Party Antivirus Tools

 If you’ve got third-party antivirus software installed on your Windows PC, that might be blocking GeForce Experience from accessing certain folders and optimizing settings. BitDefender Total Security is one antivirus utility widely confirmed to cause this issue. Those users who've confirmed that needed to disable BitDefender to resolve the issue.

 So, try disabling BitDefender or any other third-party antivirus software to see if that makes a difference. You can disable real-time scanning by right-clicking an antivirus tool in the Windows system tray and selecting to disable or turn it off from the context menu. Select to temporarily disable the antivirus scanning for about an hour or so and then open GeForce Experience.

### Reinstall GeForce Experience

 Reinstalling GeForce Experience might be a necessary potential fix for the “Unable to retrieve files” error if others fail. That will replace any corrupted GeForce Experience files that could be causing glitches. Remove GeForce Experience with a method in this guide to [uninstalling software in Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/).

![The Programs and Features applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/uninstall-option3.jpg)

 Restart the PC before reinstalling GeForce Experience. Then head over to this [GeForce Experience](https://www.nvidia.com/en-gb/geforce/geforce-experience/download/) webpage and click **Download Now**. Open the folder your browser usually downloads files to and double-click the GeForce Experience setup wizard. Go through the installer’s steps to reinstall the software.

## Optimize Your Games With GeForce Experience

 Many GeForce Experience users have fixed the “unable to retrieve settings” error in Windows with the resolutions above. You may have to try applying a few of them to get the issue sorted since there are quite a few potential causes for this error. Then you can quickly and fully optimize all your favorite games with GeForce Experience again.

 However, remember that there are numerous ways to optimize Windows games without GeForce Experience. You can optimize gaming by enabling or even disabling certain Windows features and closing background apps. Plus, you can manually adjust the graphical settings in the NVIDIA Control Panel or games to optimize Windows gaming.

 Consequently, users can’t select the Optimize option for games that show the “unable to retrieve settings” error. That’s a bit annoying for players seeking optimal gaming performance. This is how you can fix GeForce Experience’s “unable to retrieve settings” error within Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/how-to-reveal-hidden-sd-card-in-file-explorer/"><u>How to Reveal Hidden SD Card in File Explorer?</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-windows-for-wordpad-operability/"><u>Exploring Windows for WordPad Operability</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/the-digital-pioneer-how-jake-paul-mastered-youtube/"><u>The Digital Pioneer  How Jake Paul Mastered Youtube</u></a></li>
<li><a href="https://windows11.techidaily.com/identifying-legitimate-and-false-positive-login-attempts-on-pcs/"><u>Identifying Legitimate and False-Positive Login Attempts on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-tips-install-outlook-preview-in-w10w11/"><u>Easy Tips: Install Outlook Preview in W10/W11</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-peekcapture-review-of-low-res-screen-grabs/"><u>2024 Approved  PeekCapture Review of Low-Res Screen Grabs</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/coordinate-channel-coverage-for-maximum-viewer-impact-ytplustw/"><u>Coordinate Channel Coverage for Maximum Viewer Impact (YT+TW)</u></a></li>
<li><a href="https://windows11.techidaily.com/freeze-yourself-no-more-9-techniques-for-easing-windows-install-locks/"><u>Freeze Yourself No More: 9 Techniques for Easing Windows Install Locks</u></a></li>
<li><a href="https://windows11.techidaily.com/interpreting-launch-identifiers-for-applications/"><u>Interpreting Launch Identifiers for Applications</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-chromes-erroneous-threat-detection-a-guide/"><u>Navigating Chrome's Erroneous Threat Detection: A Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/improve-sound-quality-top-5-free-windows-tools/"><u>Improve Sound Quality: Top 5 Free Windows Tools</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-my-google-pixel-7a-location-is-wrong-drfone-by-drfone-virtual-android/"><u>How to Fix My Google Pixel 7a Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-for-reestablishing-connection-with-steams-game-servers/"><u>Guidelines for Reestablishing Connection with Steam's Game Servers</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-intersecting-experiences-dissecting-vr-augmented-and-mixed-reality/"><u>In 2024, Intersecting Experiences  Dissecting VR, Augmented & Mixed Reality</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-exploration-of-windows-narrators-legacy-keys/"><u>Comprehensive Exploration of Windows Narrator's Legacy Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-of-internet-options-tweaks-for-windows-11/"><u>Mastery of Internet Options Tweaks for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/cherishing-the-slumber-of-your-computer/"><u>Cherishing the Slumber of Your Computer</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-epic-eats-tiktoks-culinary-stars/"><u>In 2024, Epic Eats  TikTok’s Culinary Stars</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/lullaby-movies-assessment-and-overview-for-2024/"><u>Lullaby Movies Assessment & Overview for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/launching-the-driver-verifier-in-win11-os/"><u>Launching the Driver Verifier in Win11 OS</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-and-where-to-find-a-shiny-stone-pokemon-for-tecno-camon-20-premier-5g-drfone-by-drfone-virtual-android/"><u>How and Where to Find a Shiny Stone Pokémon For Tecno Camon 20 Premier 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-and-forge-a-friendly-startup-in-windows-amidst-errors/"><u>Fix and Forge a Friendly Startup in Windows Amidst Errors</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-2024-approved-thumbnail-magic-a-filmmakers-mobile-techniques-for-youtube/"><u>[Updated] 2024 Approved  Thumbnail Magic  A Filmmaker's Mobile Techniques for YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-actions-to-mend-post-windows-update-issues/"><u>Immediate Actions to Mend Post-Windows Update Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-prints-with-microsoft-defender-smartscreen-edge/"><u>Configuring Prints with Microsoft Defender SmartScreen Edge</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-resolve-unreal-device-issue-in-win-11/"><u>How to Resolve Unreal Device Issue in Win 11</u></a></li>
<li><a href="https://youtube-web.techidaily.com/n-2024-top-10-tips-for-youtube-stars-perfecting-your-music-reaction-skills/"><u>[New] In 2024, Top 10 Tips for YouTube Stars  Perfecting Your Music Reaction Skills</u></a></li>
<li><a href="https://windows11.techidaily.com/clear-and-constructive-icon-arrangement-ideas/"><u>Clear and Constructive Icon Arrangement Ideas</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-windows-errors-during-amd-195-installation/"><u>Eliminating Windows Errors During AMD 195 Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/hidden-windows-11-theme-treasures-revealed/"><u>Hidden Windows 11 Theme Treasures Revealed</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-common-windo-errors-quickly/"><u>Navigating Through Common Windo Errors, Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-reminders-in-every-window-of-your-pc/"><u>Efficient Reminders in Every Window of Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-error-handling-fixing-missing-updates-error-code-0x80070003/"><u>Mastering Windows Error Handling: Fixing Missing Updates (Error Code: 0X80070003)</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-steam-login-errors-on-windows-via-rust-coding/"><u>Eliminating Steam Login Errors on Windows via Rust Coding</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-unable-to-open-shares-on-windows-1011s-geforce/"><u>Fixing Unable to Open Shares on Windows 10/11'S GeForce</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/in-2024-asus-unboxing-special-the-mg28uq-monitor-a-high-res-journey/"><u>In 2024, ASUS Unboxing Special  The MG28UQ Monitor - A High-Res Journey</u></a></li>
<li><a href="https://windows11.techidaily.com/did-rav-antivirus-suddenly-appear-on-your-windows-pc-heres-where-it-came-from-and-how-to-uninstall-it/"><u>Did RAV Antivirus Suddenly Appear on Your Windows PC? Here's Where It Came From & How to Uninstall It</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-avi-visionary-player-compatible-with-pcmobile/"><u>[New] Avi Visionary Player  Compatible with PC/Mobile</u></a></li>
</ul></div>
