---
title: "Decoding Dism: A Practical Guide to Fixing Win11 OS"
date: 2024-07-11T22:29:21.307Z
updated: 2024-07-12T22:29:21.307Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Decoding Dism: A Practical Guide to Fixing Win11 OS"
excerpt: "This Article Describes Decoding Dism: A Practical Guide to Fixing Win11 OS"
keywords: Win11 Repair Guide,Windows 11 Troubleshooting,Win11 Fixed Issues,Dism Command Usage,Win11 OS Fix Tips,System File Correction,Reinstalling Win11
thumbnail: https://thmb.techidaily.com/13a1f9ec7eefb2f2d2c19f961783b576aae3496864dc942793b7f634c661d531.jpg
---

## Decoding Dism: A Practical Guide to Fixing Win11 OS

 Windows 11, like its predecessor, features the built-in Deployment Image Servicing and Management (DISM), a command-line utility to troubleshoot critical system errors. The DISM commands can help you fix Blue Screen of Death (BSOD) errors, a slow computer due to broken system files, and even repair the Windows Recovery Environment.

 In this article, we’ll show you how you can use the DISM and System File Checker utility to repair your damaged Windows 11 image and installation.

## How to Use the DISM Command in Windows 11

 The DISM command-line utility is a multi-purpose tool. It allows the system administrator to prepare and service Windows images. In addition, you can use the DISM tool in combination with the System File Checker utility to recover your Windows computer from critical failure.

 While DISM supports multiple specified commands, to repair your Windows computer, you only need to know the DISM CheckHealth, DISM ScanHealth, and DISM RestoreHealth commands.

 If you can boot into Windows 11, you can run the DISM command from an elevated PowerShell console or Command Prompt. If not, you’ll need to [boot into the Windows Recovery Environment](boot%20into%20the%20Windows%20Recovery%20Environment) and launch Command Prompt from **Advanced Options** to run DISM.

## Check Your System Health Using the DISM CheckHealth Command

 You can check for any file corruption using the DISM CheckHealth command. It is a diagnostic tool used to detect system image corruption and report the same. However, it doesn’t perform any repair.

 To run the CheckHealth command:

1. Press the **Win** key and type **cmd**.
2. Right-click on **Command Prompt** and select **Run as administrator**.  
![DISM scan health powershell command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/dism-clean-health-powershell-command.jpg)
3. In the Command Prompt window, type the following command and press **Enter**:  
`DISM /Online /Cleanup-Image /CheckHealth`
4. In the above command, the **/Online** parameter specifies the scan must be performed on the currently running operating system. The **/Cleanup-Image** parameter specifies the operation is related to Windows image repair.
5. When executed, the command will show the report as “**The component stored has been corrupted**” or “**No component store corrupted detected.**” depending on whether a component store corruption is found.  
![DISM powershell CheckHealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/dism-powershell-checkhealth-command.jpg)
6. If you use PowerShell, use the following command instead:  
`Repair-WindowsImage -Online -CheckHealth`
7. The PowerShell command will report your image status to indicate whether it is **Healthy**, **Repairable** or **Non-repairable**. A healthy image doesn’t need any further action, and you can proceed to run the SFC tool.

 If the image is repairable, you can use the RestoreHealth command to use Windows Update to fix any corruption. However, for a non-repairable image, you may need to perform a clean install to fix your computer.

## Perform an Advanced System Image Scan with the ScanHealth Command

![DISM scan health command PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/dism-scan-health-command-powershell.jpg)

 You can use the DISM ScanHealth command to perform an advanced scan of your Windows 11 system image. This will check your system for component store corruption and save the report to a log file.

 To run the DISM ScanHealth command:

1. Open **PowerShell** as administrator.
2. Type the following command and press Enter:  
`DISM /Online /Cleanup-Image /ScanHealth`
3. This process may take some time to complete. Once done, it will report any issues with the component store.
4. If an issue is detected, run the DISM RestoreHealth command to repair your Windows image.

## Run the DISM RestoreHealth Command to Repair the Windows System Image

![DISM scan health restore health command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dism-scan-health-restore-health-command-prompt.jpg)

 The DISM RestoreHealth command uses Windows Update to provide the necessary files to fix file corruption and repair the Windows 11 system image. However, you must be connected to the internet so that the DISM tool can download and restore the files needed to perform a repair.

 To run the DISM RestoreHealth command:

1. Open **Windows PowerShell** as administrator.
2. Next, type the following command and press **Enter**:  
`DISM.exe /Online /Cleanup-image /RestoreHealth`
3. The DISM utility will perform a scan and start repairing the Windows system image. This process may take some time to complete. So, wait till the progress bar reaches 100%.

## Repair System Image Using an Alternate Repair Source

 The DISM RestoreHealth command may not work if your computer is not connected to the internet or if the Windows Update component is corrupt. In this situation, you can use a Windows installation media or a mounted Windows ISO as a local source to repair the system image.

 First, [create a bootable Windows 11 USB drive](https://www.makeuseof.com/windows-11-create-bootable-usb-drive/). Once you have the installation media ready, connect it to your computer and proceed with the below steps.

 To repair your Windows 11 system image using DISM and a local repair source:

1. Press **Win + E** to open **File Explorer**.
2. Open your installation media drive, open the **Sources** folder and make sure the **install.wim** file exists. Also, note the driver letter assigned to your installation media. In this instance, our installation media is assigned the drive letter **(I:)**.  
![install wim file in Windows 11 installation media](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/install-wim-file-in-windows-11-installation-media.jpg)
3. Next, type the following command to run the **DISM RestoreHealth** command with the installation media as a repair source:  
`DISM /Online /Cleanup-Image /RestoreHealth /Source:I\Sources\install.wim /LimitAccess`
4. In the above command, replace the placeholder **:I** with your installation media drive letter. Also, the **LimitAccess** command is an optional parameter that restricts DISM access to the specified source and prevents it from using **Windows Update** as a repair source.
5. Once the process is complete, you can close Command Prompt and run the **System File Checker** utility to complete the repair process.

## Repair Your Windows Installation Using the System File Checker (SFC) Utility

![run system file checker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/run-system-file-checker.png)

 Once you have successfully repaired your Windows 11 system image using the DISM RestoreHealth command, run the System File Checker (SFC) utility. It will scan your Windows installation for system file corruption and fix them automatically.

 In almost all instances, you must run the System File Checker utility after using the DISM image repair command to complete the repair process. Here’s how to do it:

1. Press **Win + X** to open the **WindowsX** menu.
2. Click **Terminal (Admin)** to launch the **Windows** Terminal app as administrator.
3. In the **Terminal** window, type the following command to run the **System File Checker** utility:  
`sfc /scannow`
4. When you run the above command, the System File Checker utility will start verifying the integrity of system files to detect corruption. If detected, it’ll automatically try to repair by replacing the files with a cached copy located at **%WinDir%\\System32\\dllcache.**

 The SFC process may take some time to complete and often may feel stuck at some stage. If you see no progress for a long time, press the **Enter** key a few times on your keyboard to refresh the Command Prompt window to view real-time progress.

 After the process is complete, restart your computer and check for any improvements. If the issue persists, run the **sfc /scannow** command again to see if that helps fix the problem.

## Repair and Recover Your Windows System Image Using DISM and SFC

 DISM makes it easy to repair a corrupt Windows image. It works both online using Windows Update and offline with a WIM file. The steps to use DISM may look complicated at first glance; however, it only takes two commands and an elevated Command Prompt to repair your Windows 11 image and installation.

 In this article, we’ll show you how you can use the DISM and System File Checker utility to repair your damaged Windows 11 image and installation.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-screen-grab.techidaily.com/updated-the-final-verdict-on-screen-capture-obs-vs-twitch-studio/"><u>[Updated] The Final Verdict on Screen Capture  OBS vs Twitch Studio</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-the-clutter-fixing-windows-error-0x80072014/"><u>Clearing the Clutter: Fixing Windows Error 0X80072014</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-optimizing-presentations-through-skilled-use-of-aiseesoft-recorder/"><u>[New] 2024 Approved  Optimizing Presentations Through Skilled Use of Aiseesoft Recorder</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-common-errors-in-windows-onedrive/"><u>Correcting Common Errors in Windows' OneDrive</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-voiceshift-pro-elevate-your-online-conversations-with-changed-tones-for-2024/"><u>Updated VoiceShift Pro Elevate Your Online Conversations with Changed Tones for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/disable-the-app-open-tracker-in-windows-10/"><u>Disable the App Open Tracker in Windows 10</u></a></li>
<li><a href="https://article-helps.techidaily.com/cheap-sky-expeditions-under-500-drone-highlights-for-2024/"><u>Cheap Sky Expeditions  Under $500 Drone Highlights for 2024</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/2024-approved-the-top-video-animation-tools-for-creating-stunning-animations-on-the-go/"><u>2024 Approved The Top Video Animation Tools for Creating Stunning Animations On-the-Go</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-80plus-catchy-cooking-channel-names-to-attract-more-audience/"><u>[New] In 2024, 80+ Catchy Cooking Channel Names to Attract More Audience</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-minimummax-cpu-in-power-preferences/"><u>Deciphering Minimum/Max CPU in Power Preferences</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-microsoft-family-safety-functions/"><u>Demystifying Microsoft Family Safety Functions</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-content-creators-dilemrante-podcasts-vs-youtube-as-a-platform/"><u>2024 Approved  Content Creators' Dilemrante  Podcasts Vs. YouTube as a Platform</u></a></li>
<li><a href="https://windows11.techidaily.com/direct-routes-to-windows-11s-system32/"><u>Direct Routes to Windows 11'S System32</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-how-to-make-a-bigger-head-look-on-your-tiktok-video-a-comprehensive-guide-3-steps/"><u>[Updated] 2024 Approved  How to Make a Bigger Head Look on Your TikTok Video  A Comprehensive Guide (3 Steps)</u></a></li>
<li><a href="https://audio-editing.techidaily.com/in-2024-unveiling-the-secrets-a-guide-to-7-exceptional-transition-audio-files-complimentary/"><u>In 2024, Unveiling the Secrets A Guide to 7 Exceptional Transition Audio Files (Complimentary)</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-windows-startup-journey/"><u>Decoding the Windows Startup Journey</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-mastering-audio-mute-on-tiktok-quick-and-easy-techniques/"><u>New 2024 Approved Mastering Audio Mute on TikTok Quick and Easy Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-failed-windows-update-with-error-code-0x800f0845/"><u>Correcting Failed Windows Update with Error Code 0X800f0845</u></a></li>
<li><a href="https://windows11.techidaily.com/detecting-correct-credentials-vs-error-logins-on-your-winpc/"><u>Detecting Correct Credentials vs Error Logins on Your WinPC</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-and-disabling-read-only-properties-in-win11/"><u>Deciphering and Disabling Read-Only Properties in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-windows-11-notifications-to-exclude-extras/"><u>Customize Windows 11 Notifications to Exclude Extras</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-the-ultimate-screencapture-hackbook-for-techies/"><u>[New] The Ultimate ScreenCapture Hackbook for Techies</u></a></li>
<li><a href="https://windows11.techidaily.com/clean-slate-optimizing-windowed-file-space/"><u>Clean Slate: Optimizing Windowed File Space</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-oppo-find-x6-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Oppo Find X6</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-gray-out-issue-with-volume-extend-in-win/"><u>Correcting Gray Out Issue with Volume Extend in Win</u></a></li>
<li><a href="https://fake-location.techidaily.com/apply-these-techniques-to-improve-how-to-detect-fake-gps-location-on-honor-magic-v2-drfone-by-drfone-virtual-android/"><u>Apply These Techniques to Improve How to Detect Fake GPS Location On Honor Magic V2 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-windows-11-parental-restrictions-guide/"><u>Configuring Windows 11 Parental Restrictions Guide</u></a></li>
<li><a href="https://fake-location.techidaily.com/prevent-cross-site-tracking-on-motorola-moto-g14-and-browser-drfone-by-drfone-virtual-android/"><u>Prevent Cross-Site Tracking on Motorola Moto G14 and Browser | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/cure-the-save-issue-in-microsoft-oses/"><u>Cure the Save Issue in Microsoft OSes</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/10-best-vlogging-cameras-for-beginners/"><u>10 Best Vlogging Cameras for Beginners</u></a></li>
<li><a href="https://windows11.techidaily.com/curbing-high-cpu-utilization-by-tiworkerexe-programs/"><u>Curbing High CPU Utilization by TiWorker.exe Programs</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/4-ways-to-mirror-apple-iphone-8-to-laptop-via-usb-or-wi-fi-drfone-by-drfone-ios/"><u>4 Ways to Mirror Apple iPhone 8 to Laptop via USB or Wi-Fi | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-quick-conversion-at-no-expense-fb-videos-to-mp4-and-hd-now/"><u>2024 Approved  Quick Conversion at No Expense - FB Videos to MP4 & HD Now</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-integrating-audible-elements-into-your-slides-a-comprehensive-guide-for-recording-sound-in-powerpoint-on-pcmac-systems/"><u>Updated Integrating Audible Elements Into Your Slides A Comprehensive Guide for Recording Sound in PowerPoint on PC/Mac Systems</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-crafting-your-signature-voice-for-instagram-success/"><u>[New] In 2024, Crafting Your Signature Voice for Instagram Success</u></a></li>
<li><a href="https://windows11.techidaily.com/cross-language-build-system-setup/"><u>Cross-Language Build System Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/coordinating-connections-dual-net-usage-on-a-single-windows-pc/"><u>Coordinating Connections: Dual Net Usage on a Single Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-shortcuts-a-guide-for-winos-users/"><u>Crafting Shortcuts: A Guide for WinOS Users</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-correcting-installer-messages-on-pcs/"><u>Decoding and Correcting Installer Messages on PCs</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-unleash-your-inner-videographer-with-easy-mac-webcam-tips-5-ways/"><u>[New] Unleash Your Inner Videographer with Easy Mac Webcam Tips (5 Ways)</u></a></li>
<li><a href="https://windows11.techidaily.com/clear-sighted-making-your-windows-11-taskbar-glossy/"><u>Clear-Sighted: Making Your Windows 11 Taskbar Glossy</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-the-meaning-behind-windows-folders-x-marks/"><u>Demystifying: The Meaning Behind Windows' Folders X-Marks</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/in-2024-top-10-free-online-tools-for-creating-stunning-glitch-effects/"><u>In 2024, Top 10 Free Online Tools for Creating Stunning Glitch Effects</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/beginners-roadmap-for-whatsapp-group-rooms/"><u>Beginners' Roadmap for WhatsApp Group Rooms</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-elite-pixel-perfect-webcam-editor/"><u>2024 Approved  Elite Pixel-Perfect Webcam Editor</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-the-windows-device-abandonment-issue/"><u>Correcting the Windows Device Abandonment Issue</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-how-to-share-twitch-stream-on-facebook/"><u>[Updated] How to Share Twitch Stream on Facebook?</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/efficient-workflow-screen-recording-techniques-in-os-x-via-keyboard-shortcuts-for-2024/"><u>Efficient Workflow  Screen Recording Techniques in OS X via Keyboard Shortcuts for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-windows-11s-obstacle-overcoming-error-code-22/"><u>Clearing Windows 11'S Obstacle: Overcoming Error Code 22</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-windows-11-a-guide-to-a-unique-environment/"><u>Customizing Windows 11: A Guide to a Unique Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-unilateral-audio-issue-on-win-os-headphones/"><u>Correcting Unilateral Audio Issue on WIN OS Headphones</u></a></li>
<li><a href="https://windows11.techidaily.com/controlling-application-spaces-in-windows-task-mgr/"><u>Controlling Application Spaces in Windows Task Mgr</u></a></li>
<li><a href="https://windows11.techidaily.com/defeating-inadequate-pcs-fixing-game-bar-errors/"><u>Defeating Inadequate PCs: Fixing Game Bar Errors</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-simplify-your-macs-sound-recording-journey-with-audacity-for-2024/"><u>[New] Simplify Your Mac's Sound Recording Journey with Audacity for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-curate-engaging-content-with-top-igtv-editor-tools/"><u>[New] Curate Engaging Content with Top IGTV Editor Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/clear-up-windows-icon-layout-confusion/"><u>Clear Up Window's Icon Layout Confusion</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-supercharge-your-media-download-sounds-for-editing/"><u>In 2024, Supercharge Your Media  Download Sounds for Editing</u></a></li>
<li><a href="https://windows11.techidaily.com/1720600438278-windowsstellar-data-recovery/"><u>「Windowsで失われたファイルを取り戻せる無料ソフトStellar Data Recovery」</u></a></li>
<li><a href="https://windows11.techidaily.com/converting-heic-photos-to-jpeg-on-windows-1011/"><u>Converting HEIC Photos to JPEG on Windows 10/11</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ring-the-art-of-adding-youtube-playlists-to-your-website-seamlessly/"><u>Mastering the Art of Adding YouTube Playlists to Your Website Seamlessly</u></a></li>
<li><a href="https://windows11.techidaily.com/compact-pc-capacity-concealed-by-slowness/"><u>Compact PC, Capacity Concealed by Slowness</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-techniques-to-transfer-data-from-samsung-galaxy-s23-to-iphone-15141312-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Techniques to Transfer Data from Samsung Galaxy S23 to iPhone 15/14/13/12 | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-any-oneplus-nord-n30-5g-phone-password-using-emergency-call-by-drfone-android/"><u>How To Unlock Any OnePlus Nord N30 5G Phone Password Using Emergency Call</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/revolutionize-your-design-work-with-free-images-from-these-leading-sites-for-2024/"><u>Revolutionize Your Design Work with Free Images From These Leading Sites for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>