---
title: Unveiling the Power of Dism in Win11 Image Management
date: 2024-07-11T21:26:11.729Z
updated: 2024-07-12T21:26:11.729Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unveiling the Power of Dism in Win11 Image Management
excerpt: This Article Describes Unveiling the Power of Dism in Win11 Image Management
keywords: Win11 Img Manage,Dism Power Unveil,Win11 System Update,Dism Windows Tooling,Image Recovery Win11,Upgrade Win11 With Dism,Effective Dism Usage
thumbnail: https://thmb.techidaily.com/4f7677089ce9d876fde36aa600317f042b44ee73a802e442be2008c2b3992f0d.jpg
---

## Unveiling the Power of Dism in Win11 Image Management

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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://android-location-track.techidaily.com/top-10-telegram-spy-tools-on-xiaomi-redmi-a2plus-for-parents-drfone-by-drfone-virtual-android/"><u>Top 10 Telegram Spy Tools On Xiaomi Redmi A2+ for Parents | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-ultimate-guide-to-effective-video-marketing-tools-8/"><u>2024 Approved  Ultimate Guide to Effective Video Marketing Tools (8)</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-a-compreranium-of-hand-tracking-systems/"><u>In 2024, A Compreranium of Hand Tracking Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/a-users-guide-to-windows-11-system-anomalies-analysis/"><u>A User’s Guide to Windows 11 System Anomalies Analysis</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-screencapture-hq-top-browsers-for-digital-footprints/"><u>[Updated] ScreenCapture HQ  Top Browsers for Digital Footprints</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-learn-the-best-green-screen-video-editors-for-mac-users-including-green-screen-final-cut-pro-for-2024/"><u>New Learn the Best Green Screen Video Editors for Mac Users, Including Green Screen Final Cut Pro for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/beat-the-blank-screen-blues-faster-input-in-windows-11/"><u>Beat the Blank Screen Blues: Faster Input in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/activatedeactivate-smartscreen-filter-on-windows-11/"><u>Activate/Deactivate SmartScreen Filter on Windows 11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-optimal-visual-performance-in-4k-titles/"><u>[New] Optimal Visual Performance in 4K Titles</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-unfold-time-how-to-watch-previous-fb-content/"><u>[Updated] Unfold Time  How To Watch Previous FB Content</u></a></li>
<li><a href="https://audio-editing.techidaily.com/2024-approved-curating-the-finest-sound-a-list-of-premium-ios-and-android-music-editors/"><u>2024 Approved Curating the Finest Sound A List of Premium iOS & Android Music Editors</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-with-location-spoofer-on-vivo-v30-drfone-by-drfone-virtual-android/"><u>How To Simulate GPS Movement With Location Spoofer On Vivo V30? | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-expert-advice-for-efficiently-creating-srt-files/"><u>In 2024, Expert Advice for Efficiently Creating SRT Files</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-all-you-need-to-know-about-mega-greninja-for-honor-play-8t-drfone-by-drfone-virtual-android/"><u>In 2024, All You Need To Know About Mega Greninja For Honor Play 8T | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-resolving-m365-error-30015-26-on-pcs/"><u>Understanding and Resolving M365 Error 30015-26 on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/the-clarity-connoisseurs-guide-top-tips-for-perfecting-pc-displays/"><u>The Clarity Connoisseur's Guide: Top Tips for Perfecting PC Displays</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-troubleshooting-silent-voice-calls-in-valorant/"><u>Windows Troubleshooting: Silent Voice Calls in Valorant</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-and-correcting-windows-security-faults-in-windows-11/"><u>Avoiding and Correcting Windows Security Faults in Windows 11</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-signs-youre-no-longer-snapchat-friend-for-2024/"><u>[New] Signs You're No Longer Snapchat Friend for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/quick-tutorial-for-top-memes-kinemaster/"><u>Quick Tutorial for Top Memes  KineMaster</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-b-roll-wisdom-enhancing-your-cinematic-quality/"><u>In 2024, B-Roll Wisdom  Enhancing Your Cinematic Quality</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-dual-monitor-setup-problems/"><u>Resolving Dual Monitor Setup Problems</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-easy-ways-to-copy-contacts-from-oppo-reno-9a-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Easy Ways to Copy Contacts from Oppo Reno 9A to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-workflow-multitask-with-windows-11-expertise/"><u>Optimizing Workflow: Multitask with Windows 11 Expertise</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-a-deep-dive-into-cutting-edge-vr-technology/"><u>2024 Approved  A Deep Dive Into Cutting-Edge VR Technology</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-solutions-to-resolve-instant-failure-in-adding-a-folder-in-onedrive/"><u>Swift Solutions to Resolve Instant Failure in Adding a Folder in OneDrive</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/youtube-outros-that-grow-your-channel-faster/"><u>YouTube Outros that Grow Your Channel Faster</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-expert-approved-3d-video-creation-software-for-professionals/"><u>New 2024 Approved Expert-Approved 3D Video Creation Software for Professionals</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-enhancing-visual-experiences-a-deep-dive-into-video-enhancer-22/"><u>[Updated] In 2024, Enhancing Visual Experiences  A Deep Dive Into Video Enhancer 2.2</u></a></li>
<li><a href="https://windows11.techidaily.com/remediation-techniques-for-resource-occupancy-errors-149-chars/"><u>Remediation Techniques for Resource Occupancy Errors (149 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-workflow-efficiency-mastering-flow-launcher/"><u>Boost Workflow Efficiency: Mastering Flow Launcher</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-how-does-the-stardust-trade-cost-in-pokemon-go-on-apple-iphone-11-pro-max-drfone-by-drfone-virtual-ios/"><u>In 2024, How does the stardust trade cost In pokemon go On Apple iPhone 11 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-from-passive-to-profitable-youtube-revenue-techniques/"><u>2024 Approved  From Passive to Profitable  YouTube Revenue Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-taskbar-tools-monitoring-cpu-ram-and-disk-use/"><u>Tailored Taskbar Tools: Monitoring CPU, RAM & Disk Use</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-your-screen-without-pin-in-windows-11/"><u>Unlock Your Screen Without PIN in Window's 11</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-how-to-reset-and-fix-obs-fullscreen-issue-for-2024/"><u>[New] How to Reset and Fix OBS Fullscreen Issue for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/speed-racers-remarkable-22-run/"><u>Speed Racers' Remarkable '22 Run</u></a></li>
<li><a href="https://extra-skills.techidaily.com/novices-guide-to-animated-videos-with-wmm-for-2024/"><u>Novice's Guide to Animated Videos with WMM for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/simplified-docx-to-pdf-workflow-in-windows-11-systems/"><u>Simplified DOCX to PDF Workflow in Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/nine-pathways-out-of-the-window-11s-0x8004def5-puzzle/"><u>Nine Pathways Out of the Window 11'S 0X8004DEF5 Puzzle</u></a></li>
<li><a href="https://windows11.techidaily.com/sudos-arrival-in-windows-os-explained/"><u>Sudo's Arrival in Windows OS Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/switching-your-windows-security-pin-quickly/"><u>Switching Your Windows Security Pin Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-wifi-wisdom-accelerating-network-speed-assessment/"><u>Windows WiFi Wisdom: Accelerating Network Speed Assessment</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-failed-capture-issue-in-win11-photoapp/"><u>Overcoming 'Failed Capture' Issue in Win11 PhotoApp</u></a></li>
<li><a href="https://windows11.techidaily.com/3-ways-to-adjust-the-mouse-double-click-speed-on-windows/"><u>3 Ways to Adjust the Mouse Double-Click Speed on Windows</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-additional-tips-about-sinnoh-stone-for-oppo-k11-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Additional Tips About Sinnoh Stone For Oppo K11 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-notebook-interface-with-themes-and-fonts/"><u>Streamline Your Notebook Interface with Themes & Fonts</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-group-policy-editor-navigation-windows-11-style/"><u>Mastering Group Policy Editor Navigation, Windows 11 Style</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-top-7-watermark-free-video-combiners-for-2024/"><u>Updated Top 7 Watermark-Free Video Combiners for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/exploring-top-ios-psp-emulation-tools-for-gamers/"><u>Exploring Top iOS PSP Emulation Tools for Gamers</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-the-ultimate-guide-to-tiktok-video-amplification/"><u>2024 Approved  The Ultimate Guide to TikTok Video Amplification</u></a></li>
<li><a href="https://windows11.techidaily.com/9-ways-to-fix-windows-hello-fingerprint-recognition-not-working/"><u>9 Ways to Fix Windows Hello Fingerprint Recognition Not Working</u></a></li>
<li><a href="https://windows11.techidaily.com/reactivating-inputs-post-sleep-on-latest-windows/"><u>Reactivating Inputs Post-Sleep on Latest Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-microsoft-teams-instability-on-ws11ws10-devices/"><u>Preventing Microsoft Teams Instability on WS11/WS10 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-folder-menu-enhancement-with-new-commands-win-11/"><u>Step-by-Step Guide: Folder Menu Enhancement with New Commands (Win 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-your-creative-potential-with-win11s-photos-app-creating-dynamic-slideshows-and-image-spot-repair/"><u>Unlock Your Creative Potential with Win11's Photos App: Creating Dynamic Slideshows & Image Spot Repair</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-first-steps-on-social-landscape-creating-a-facebook-account/"><u>[New] First Steps on Social Landscape  Creating a Facebook Account</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/2024-approved-50plus-tiktok-quotes-to-inspire-you-and-make-videos-go-viral/"><u>2024 Approved  50+ TikTok Quotes to Inspire You and Make Videos Go Viral</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/building-captivating-instagram-feed-layouts-for-2024/"><u>Building Captivating Instagram Feed Layouts for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-premier-programs-to-transform-webcam-footage/"><u>[New] 2024 Approved  Premier Programs to Transform Webcam Footage</u></a></li>
<li><a href="https://windows11.techidaily.com/the-future-of-personal-computing-transforming-window-11-widgets/"><u>The Future of Personal Computing: Transforming Window 11 Widgets</u></a></li>
<li><a href="https://windows11.techidaily.com/pro-tips-for-buying-windows-11-vcs/"><u>Pro Tips for Buying Windows 11 VCs</u></a></li>
<li><a href="https://extra-resources.techidaily.com/digital-cosmos-display-top-pick-hdr-sky-sites-list/"><u>Digital Cosmos Display  Top Pick HDR Sky Sites List</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-bring-your-photos-to-life-the-best-animation-tools/"><u>In 2024, Bring Your Photos to Life The Best Animation Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/nullify-specification-shortfalls-alerts-in-win11/"><u>Nullify Specification Shortfalls Alerts in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-potential-of-windows-11s-configurable-fn-keys/"><u>Mastering the Potential of Windows 11'S Configurable FN Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11s-software-compatibility-tool/"><u>Navigating Windows 11’S Software Compatibility Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-deleting-account-info-from-windows-logon/"><u>Steps for Deleting Account Info From Windows Logon</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-demystifying-income-flow-to-creators-within-the-short-video-model/"><u>2024 Approved  Demystifying Income Flow to Creators Within the Short Video Model</u></a></li>
<li><a href="https://windows11.techidaily.com/proactive-measures-for-sticky-notes-longevity/"><u>Proactive Measures for Sticky Notes' Longevity</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-cleanup-stripping-out-microsoft-store/"><u>Win11 Cleanup: Stripping Out Microsoft Store</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-and-resolving-outlooks-error-0x80040610/"><u>Navigating Through and Resolving Outlook's Error 0X80040610</u></a></li>
<li><a href="https://windows11.techidaily.com/learn-9-keys-to-tweaking-windows-audio-properties/"><u>Learn 9 Keys to Tweaking Windows Audio Properties</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-enhancing-filmmaking-top-choices-in-camera-lenses/"><u>[Updated] Enhancing Filmmaking  Top Choices in Camera Lenses</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-challenge-of-0x8007045d-error-on-windows-11/"><u>Overcoming the Challenge of 0X8007045d Error on Windows 11</u></a></li>
<li><a href="https://animation-videos.techidaily.com/can-i-do-animated-logo-design-without-design-skills-in-2024/"><u>Can I Do Animated Logo Design Without Design Skills, In 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-from-play-to-pro-setting-up-a-ps4-game-broadcast-hub/"><u>[Updated] In 2024, From Play to Pro  Setting up a PS4 Game Broadcast Hub</u></a></li>
</ul></div>
