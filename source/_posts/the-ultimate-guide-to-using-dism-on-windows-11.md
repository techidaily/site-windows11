---
title: The Ultimate Guide to Using DISM on Windows 11
date: 2024-08-22T21:44:24.240Z
updated: 2024-08-23T21:44:24.240Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Ultimate Guide to Using DISM on Windows 11
excerpt: This Article Describes The Ultimate Guide to Using DISM on Windows 11
keywords: Diskmastery Guide,Windows 11 Dism Tool,Dism Usage in Win11,Mastering DISM on W11,Win11 DISM Proficiency,DISM Guide for Windows 11,Essential Dism Practices in Win11
thumbnail: https://thmb.techidaily.com/cdd7fc426e2ad9d45bb7ca050714efc7a5191159c61f1ffd4157c0d0a51c0306.jpg
---

## The Ultimate Guide to Using DISM on Windows 11

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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
## Perform an Advanced System Image Scan with the ScanHealth Command

![DISM scan health command PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/dism-scan-health-command-powershell.jpg)

<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
 You can use the DISM ScanHealth command to perform an advanced scan of your Windows 11 system image. This will check your system for component store corruption and save the report to a log file.

 To run the DISM ScanHealth command:

1. Open **PowerShell** as administrator.
2. Type the following command and press Enter:  
`DISM /Online /Cleanup-Image /ScanHealth`
3. This process may take some time to complete. Once done, it will report any issues with the component store.
4. If an issue is detected, run the DISM RestoreHealth command to repair your Windows image.

<!-- affiliate ads begin -->
<a href="https://uperfect.sjv.io/c/5597632/1246754/15155" target="_top" id="1246754"><img src="//a.impactradius-go.com/display-ad/15155-1246754" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1246754/15155" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Run the DISM RestoreHealth Command to Repair the Windows System Image

![DISM scan health restore health command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dism-scan-health-restore-health-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The DISM RestoreHealth command uses Windows Update to provide the necessary files to fix file corruption and repair the Windows 11 system image. However, you must be connected to the internet so that the DISM tool can download and restore the files needed to perform a repair.

 To run the DISM RestoreHealth command:

1. Open **Windows PowerShell** as administrator.
2. Next, type the following command and press **Enter**:  
`DISM.exe /Online /Cleanup-image /RestoreHealth`
3. The DISM utility will perform a scan and start repairing the Windows system image. This process may take some time to complete. So, wait till the progress bar reaches 100%.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599952&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>Epubor Ultimate for Mac:Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
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
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-audio-matters-ensuring-excellent-sound-in-your-youtube-shots/"><u>[Updated] 2024 Approved  Audio Matters  Ensuring Excellent Sound in Your YouTube Shots</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-vimeo-revenue-a-step-by-step-money-making-blueprint/"><u>[Updated] 2024 Approved  Vimeo Revenue  A Step-by-Step Money-Making Blueprint</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-how-to-record-skype-meeting-on-windows-and-mac-skype-for-business/"><u>[Updated] How to Record Skype Meeting on Windows and Mac | Skype for Business</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-a-step-by-step-approach-to-incorporating-luts-in-obs-studio-projects/"><u>2024 Approved  A Step-by-Step Approach to Incorporating LUTs in OBS Studio Projects</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-nature-of-the-cosmos-select-sky-photography-websites/"><u>2024 Approved  Nature of the Cosmos  Select Sky Photography Websites</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-vivo-y27-4g-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Vivo Y27 4G</u></a></li>
<li><a href="https://windows11.techidaily.com/a-users-guide-to-windows-11-system-anomalies-analysis/"><u>A User’s Guide to Windows 11 System Anomalies Analysis</u></a></li>
<li><a href="https://windows11.techidaily.com/beat-the-blank-screen-blues-faster-input-in-windows-11/"><u>Beat the Blank Screen Blues: Faster Input in Windows 11</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/best-android-options-10-gb-emulation-tools/"><u>Best Android Options  10 GB Emulation Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-barriers-to-maximize-windows-ram/"><u>Breaking Down Barriers to Maximize Windows' RAM</u></a></li>
<li><a href="https://windows11.techidaily.com/brighten-control-navigating-windows-11-display-settings/"><u>Brighten Control: Navigating Windows 11 Display Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/classic-interface-reclamation-tips/"><u>Classic Interface Reclamation Tips</u></a></li>
<li><a href="https://tech-hub.techidaily.com/counter-cold-war-pc-lag-and-frame-drops-with-these-proven-techniques-2024-game-optimization-guide/"><u>Counter Cold War PC Lag and Frame Drops with These Proven Techniques - 2024 Game Optimization Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-windows-modern-standbys-drawbacks/"><u>Decoding Windows Modern Standby's Drawbacks</u></a></li>
<li><a href="https://windows11.techidaily.com/easing-wow-start-up-issues-after-updates/"><u>Easing WoW Start-Up Issues After Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-editing-skills-mastering-jumps-and-pastes/"><u>Elevate Editing Skills: Mastering Jumps & Pastes</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/elevate-your-fb-campaigns-the-20-premier-video-tactics-for-2024/"><u>Elevate Your FB Campaigns  The 20 Premier Video Tactics for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-chromiums-firewall-connection-within-windows-safeguards/"><u>Enabling Chromium's Firewall Connection Within Windows Safeguards</u></a></li>
<li><a href="https://windows11.techidaily.com/enhanced-windows-file-navigation-a-guide-excluding-ls/"><u>Enhanced Windows File Navigation: A Guide Excluding LS</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/expert-advice-on-computing-from-tomntech-space/"><u>Expert Advice on Computing From Tom'nTech Space</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/from-mundane-to-memorable-transform-your-social-media-identity-with-these-tips/"><u>From Mundane to Memorable  Transform Your Social Media Identity with These Tips</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/hacks-to-do-pokemon-go-trainer-battles-for-motorola-g54-5g-drfone-by-drfone-virtual-android/"><u>Hacks to do pokemon go trainer battles For Motorola G54 5G | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-vivo-t2x-5g-phone-with-broken-screen-by-drfone-android/"><u>How to Unlock Vivo T2x 5G Phone with Broken Screen</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-8-premier-online-photo-frame-creators-revealed/"><u>In 2024, 8 Premier Online Photo Frame Creators Revealed</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-clearer-sound-with-these-ipad-tips/"><u>In 2024, Clearer Sound with These iPad Tips</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-dive-into-digital-green-magic-top-4-youtube-sources-for-no-cost-background-workshops/"><u>In 2024, Dive Into Digital Green Magic  Top 4 YouTube Sources for No-Cost Background Workshops</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-launch-xp-movie-editor-for-seamless-editing/"><u>In 2024, Launch XP Movie Editor for Seamless Editing</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-perfecting-your-presentations-youtube-and-google-slides/"><u>In 2024, Perfecting Your Presentations  YouTube and Google Slides</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-premier-virtual-microphones/"><u>In 2024, Premier Virtual Microphones</u></a></li>
<li><a href="https://windows11.techidaily.com/lowering-gameplay-stress-reducing-cpu-load-while-playing/"><u>Lowering Gameplay Stress: Reducing CPU Load While Playing</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-landscape-of-android-and-windows-file-sharing/"><u>Navigating the Landscape of Android & Windows File Sharing</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-powershell-script-execution-policy-landscape/"><u>Navigating the PowerShell Script Execution Policy Landscape</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-how-to-make-animation-talk-explained-with-easy-steps/"><u>New How To Make Animation Talk? Explained with Easy Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/no-more-frustration-quick-fixes-for-windows-11-woes/"><u>No More Frustration! Quick Fixes for Windows 11 Woes</u></a></li>
<li><a href="https://extra-information.techidaily.com/one-airpod-not-working-how-to-fix-it/"><u>One Airpod Not Working  How to Fix It</u></a></li>
<li><a href="https://windows11.techidaily.com/quash-insufficient-requirement-notice-windows-11/"><u>Quash Insufficient Requirement Notice Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/quickly-fixing-microsoft-store-problems-on-win-11/"><u>Quickly Fixing Microsoft Store Problems on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-excessive-ram-allocation-in-connected-devices-interface/"><u>Resolving Excessive RAM Allocation in Connected Devices Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-to-github-desktop-with-windows-11-os/"><u>Step-by-Step Guide to GitHub Desktop with Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-reclaiming-standard-windows-11-search-preferences/"><u>Step-by-Step: Reclaiming Standard Windows 11 Search Preferences</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-restore-fn-key-brighness-in-windows-11/"><u>Steps to Restore Fn Key Brighness in Windows 11</u></a></li>
<li><a href="https://driver-install.techidaily.com/swift-software-refreshes-on-lenovo-z50-70/"><u>Swift Software Refreshes on Lenovo Z50-70</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-the-walls-of-windows-icons/"><u>Taming the Walls of Windows Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/the-top-9-truths-about-why-pc-computers-win-over-macos-9/"><u>The Top 9 Truths About Why PC Computers Win over MacOS (#9)</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-5-car-locator-apps-for-oppo-reno-10-pro-5g-drfone-by-drfone-virtual-android/"><u>Top 5 Car Locator Apps for Oppo Reno 10 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-imei-unlokers-for-your-lenovo-phone-by-drfone-android/"><u>Top IMEI Unlokers for Your Lenovo Phone</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-windows-11-screens-with-custom-wallpaper-panes/"><u>Transform Windows 11 Screens with Custom Wallpaper Panes</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-steps-delete-email-after-signing-in/"><u>Troubleshooting Steps: Delete Email After Signing In</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-optimal-sleep-cycles-for-windows-devices/"><u>Unlocking Optimal Sleep Cycles for Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/voice-your-ideas-type-them-out-with-openais-whisper/"><u>Voice Your Ideas, Type Them Out With OpenAI’s Whisper</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>