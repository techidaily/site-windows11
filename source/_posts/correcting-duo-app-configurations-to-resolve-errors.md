---
title: Correcting Duo App Configurations to Resolve Errors
date: 2024-07-11T21:21:07.192Z
updated: 2024-07-12T21:21:07.192Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting Duo App Configurations to Resolve Errors
excerpt: This Article Describes Correcting Duo App Configurations to Resolve Errors
keywords: Fix Duo Errors,Duo Configuration Guide,Duo App Troubleshooting,Solving Duo Issues,Optimize Duo Settings,Resolve Duo Configs,Update Duo App Errors
thumbnail: https://thmb.techidaily.com/4f7878f35a5617dd30422b38a025795d7b590bfdd2ba7a274f89a9a6584223ab.jpg
---

## Correcting Duo App Configurations to Resolve Errors

 It's frustrating when you can't launch your favorite apps and programs on Windows due to the "Side-by-side configuration is incorrect" error. While determining the exact cause of this error can be difficult, it is possible to resolve it.

 In most cases, the “Side-by-side configuration is incorrect” error occurs due to a damaged Visual C++ package or a compatibility issue. However, there can be other reasons for it. So, what can you do to resolve this unforeseen error on Windows? Let's find out.

## 1\. Reinstall Microsoft Visual C++ Packages

 Problems with the current Visual C++ packages on your PC can often result in the “Side-by-side configuration is incorrect” error on Windows. If that's the case, you must reinstall the problematic Visual C++ package on your computer. To do so, you'll need to find its version number using Event Viewer. Here's how you can go about it.

1. Press**Win + S** to open the search menu.
2. Type**event viewer** in the search box and select the first result that appears.
3. Use the left pane to navigate to**Custom Views > Summary page events** .  
![Event Viewer on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Event-Viewer-on-Windows.jpg)
4. Choose the most recent side-by-side error from the middle pane and note down the version number under the**General** tab.
5. Open up your web browser and head over to the [Microsoft Visual C++ Redistributable download page](https://learn.microsoft.com/en-US/cpp/windows/latest-supported-vc-redist?view=msvc-170) .
6. Download and install the Visual C++ package corresponding to your version number.

 Restart your PC after this (see [how to restart your Windows PC](https://www.makeuseof.com/windows-restart-methods/) ) and try to launch your app or program one more time.

## 2\. Run the SFC and DISM Scans

 Corrupted or missing system files on your computer can also trigger such errors. Fortunately, Windows includes a useful command-line utility called SFC (or System File Checker) scan for such occasions. It can automatically detect any damaged system files on your PC and replace them with their cached versions.

To run the SFC scan on your computer:

1. Press**Win + X** to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. Select**Yes** when the User Account Control (UAC) prompt shows up.
4. In the console, type**sfc /scannow** and press**Enter** .  
![Run SFC Scan on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Run-SFC-Scan-on-Windows.jpg)

 Wait for the scan to complete and then run the DISM (or Deployment Image Servicing and Management) scan by entering the following command:

`DISM.exe /Online /Cleanup-image /Restorehealth`

 After the process is complete, exit the Command Prompt window and restart your PC. The error should not appear anymore after the reboot.

## 3\. Run the Program Compatibility Troubleshooter

 If the “Side-by-side configuration is incorrect” error only appears when you try to launch a specific program, you can run the program compatibility troubleshooter on Windows. It’ll try to fix any compatibility issues with your program and help you fix the error. Here’s how you can run it.

1. Right-click on your app or program that’s producing the error and select**Troubleshoot compatibility** .
2. In the Program Compatibility Troubleshooter window, select**Troubleshoot program** .
3. Mark the checkbox that reads **The program worked in earlier versions of Windows but won’t install or run now** and hit**Next** .
4. Follow the on-screen prompts to run the troubleshooter and see if the error occurs again.  
![Program Compatibility Troubleshooter Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Program-Compatibility-Troubleshooter-Windows.jpg)

## 4\. Repair the Problematic App

 If the Windows troubleshooter fails to find any problems, you can try repairing the problematic app on Windows. Here's how to do it.

1. Press**Win + I** to open the Settings app.
2. Navigate to the**Apps** tab.
3. Go to**Installed apps** .
4. Scroll down to locate the problematic app on the list. Click the**three-dot menu icon** next to it and select**Advanced options** .
5. Scroll down to the Reset section and click on**Repair** .  
![Repair App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Repair-App-on-Windows.jpg)

 You should see a right checkmark next to the Repair button once the process is complete.

 Alternatively, you can repair your apps and programs from Control Panel. To learn more about this, check our guide on [how to repair apps and programs on Windows](https://www.makeuseof.com/windows-repair-apps-programs/) and follow the steps outlined there.

## 5\. Reinstall the Problematic App

 Repairing the app may not help much if the existing app data is corrupted or missing. In that case, your only option is to uninstall the problematic app and install it again.

1. Press**Win + S** to open the search menu.
2. Type in the name of your app or program and select**Uninstall** from the right pane.
3. Select**Uninstall** again to confirm.  
![Uninstall App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Uninstall-App-on-Windows.jpg)

 Head over to Microsoft Store and install the app again. Following this, the error should not bother you.

## 6\. Scan for Malware

 If your computer is infected with malware, you may encounter such errors when launching apps and programs. To check for this possibility, you can run a full system scan of your PC with Windows Defender. You can also use one of the [best third-party antivirus programs for Windows](https://www.makeuseof.com/tag/best-antivirus-for-windows-10/) for this.

 If the scan uncovers anything suspicious, take the recommended steps to fix the issue and reboot your PC after that.

## 7\. Install Pending Windows Updates

 Microsoft regularly releases updates for the Windows operating system. Aside from new features and security patches, these updates also bring much-needed fixes for bugs and other errors. You can try updating Windows to its most recent version to see if that makes a difference.

 Press**Win + I** to open the Settings app and navigate to the**Windows Update** section. Click on**Check for updates** to download and install pending updates.

![Check for System Updates on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Check-for-System-Updates-on-Windows.jpg)

## 8\. Perform a System Restore

 Windows System Restore performs a backup of the entire system on a regular basis. You can use it to revert your system to a point before the error first started appearing.

To perform a system restore on Windows:

1. Press**Win + R** to open the Run dialog box.
2. Type**sysdm.cpl** in the box and press**Enter** .
3. In the System Properties window, switch to the**System Protection** tab.
4. Click on**System Restore** .
5. Click**Next** .
6. Select a restore point before the first appeared and hit**Next** .
7. Check all the details and hit**Finish** .  
![System Restore Dialog on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/System-Restore-Dialog-on-Windows.jpg)

 Windows will restart and revert to the specified restore point. Following that, the error should be resolved.

## Start Using Your Apps Again

 By applying the above fixes, you should be able to fix the “Side-by-side configuration is incorrect” error in no time. However, if none of the solutions work, you may have to reset your Windows computer as a last resort.


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
<li><a href="https://windows11.techidaily.com/essential-troubleshooting-for-winscombsvc-error/"><u>Essential Troubleshooting for WinScombSvc Error</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-correct-steam-ui-dll-not-loaded-error/"><u>Steps to Correct Steam UI DLL Not Loaded Error</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-knowledge-about-winservicesexe/"><u>Essential Knowledge About WinServices.exe</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-active-directory-related-printer-errors-on-w11/"><u>Steps to Resolve Active Directory-Related Printer Errors on W11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-rectify-microsoft-store-error-0x80072f30-on-pcs/"><u>Steps to Rectify Microsoft Store Error 0X80072F30 on PCs</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/moments-replay-module/"><u>Moments Replay Module</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-windows-notepad-notebook-errors/"><u>Solutions for Windows Notepad Notebook Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-techniques-for-initiatingexit-focus-in-the-windows-terminal/"><u>Essential Techniques for Initiating/Exit Focus in the Windows Terminal</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-what-legendaries-are-in-pokemon-platinum-on-nubia-red-magic-8s-proplus-drfone-by-drfone-virtual-android/"><u>In 2024, What Legendaries Are In Pokemon Platinum On Nubia Red Magic 8S Pro+? | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-a-quick-guide-to-motorola-moto-g73-5g-frp-bypass-instantly-by-drfone-android/"><u>In 2024, A Quick Guide to Motorola Moto G73 5G FRP Bypass Instantly</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-silent-mode-glitches-on-windows-word-reading-feature/"><u>Fix Silent Mode Glitches on Windows' Word Reading Feature</u></a></li>
<li><a href="https://change-location.techidaily.com/what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-vivo-y36-drfone-by-drfone-virtual-android/"><u>What is the best Pokemon for pokemon pvp ranking On Vivo Y36? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/best-anti-tracker-software-for-realme-c51-drfone-by-drfone-virtual-android/"><u>Best Anti Tracker Software For Realme C51 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/revamping-network-defenses-with-these-5-steps/"><u>Revamping Network Defenses with These 5 Steps</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-expert-picks-the-best-skype-capture-tools/"><u>In 2024, Expert Picks  The Best Skype Capture Tools</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-8-best-free-online-video-stabilizers-guide-provided/"><u>New 8 Best Free Online Video Stabilizers Guide Provided</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-the-missing-file-preview-glitch-in-outlook-360/"><u>Mending the Missing File Preview Glitch in Outlook 360</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-undead-uprising-your-guide-to-engrossing-zombie-playtime/"><u>In 2024, Undead Uprising  Your Guide to Engrossing Zombie Playtime</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-divergence-in-dungeons-classic-and-hybrid-games/"><u>[New] In 2024, Divergence in Dungeons  Classic and Hybrid Games</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-compelling-desktop-imagery-on-windows-11/"><u>Crafting Compelling Desktop Imagery on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-change-the-task-manager-start-page-in-windows-11/"><u>How to Change the Task Manager Start Page in Windows 11</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-top-7-best-gopro-video-editors-for-mac/"><u>Updated Top 7 Best GoPro Video Editors for Mac</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-navigating-virtual-boards-with-ease-a-guide-to-using-google-meet-on-diverse-devices/"><u>[New] Navigating Virtual Boards with Ease  A Guide to Using Google Meet on Diverse Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/image-integration-insights-securely-stashing-files-on-windows-11/"><u>Image Integration Insights: Securely Stashing Files on Windows 11</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-transform-your-streaming-journey-by-activating-youtubes-av1/"><u>In 2024, Transform Your Streaming Journey by Activating YouTube's AV1</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/2024-approved-step-by-step-guide-how-to-translate-tiktok-videos/"><u>2024 Approved Step-by-Step Guide How to Translate TikTok Videos</u></a></li>
<li><a href="https://fake-location.techidaily.com/which-is-the-best-fake-gps-joystick-app-on-motorola-moto-g84-5g-drfone-by-drfone-virtual-android/"><u>Which is the Best Fake GPS Joystick App On Motorola Moto G84 5G? | Dr.fone</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-the-best-free-and-paid-online-vertical-video-editors/"><u>New In 2024, The Best Free and Paid Online Vertical Video Editors</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-zip-files-seamless-compressed-archives-on-windows-pcs/"><u>Conquer ZIP Files: Seamless Compressed Archives on Windows PCs</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/how-to-make-a-super-easy-rotating-video-effect-for-2024/"><u>How to Make a Super Easy Rotating Video Effect for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-inaccessible-game-on-windows-steam/"><u>Navigating Through Inaccessible Game on Windows Steam</u></a></li>
<li><a href="https://windows11.techidaily.com/checking-for-safe-network-connections-on-windows/"><u>Checking for Safe Network Connections on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-spotting-hdd-vs-ssd-in-windows-operations/"><u>Essential Guide: Spotting HDD vs SSD in Windows Operations</u></a></li>
<li><a href="https://windows11.techidaily.com/outperforming-understanding-why-pcs-triumph-over-macs-9/"><u>Outperforming: Understanding Why PCs Triumph over Macs (#9)</u></a></li>
<li><a href="https://techidaily.com/update-drivers-with-device-manager-in-windows-11-and-10-by-drivereasy-guide/"><u>Update drivers with Device Manager in Windows 11 & 10</u></a></li>
<li><a href="https://howto.techidaily.com/8-ultimate-fixes-for-google-play-your-xiaomi-redmi-a2-isnt-compatible-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Ultimate Fixes for Google Play Your Xiaomi Redmi A2 Isnt Compatible | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-top-10-youtube-cameras-from-novices-to-experts/"><u>In 2024, Top 10 YouTube Cameras, From Novices to Experts</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/essential-igtv-picks-for-a-creative-edge/"><u>Essential IGTV Picks for a Creative Edge</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-your-pre-win11-system-efficiently/"><u>Optimize Your Pre-Win11 System Efficiently</u></a></li>
<li><a href="https://screen-capture.techidaily.com/most-reliable-no-cost-chrome-os-recorder-tools-for-2024/"><u>Most Reliable No-Cost Chrome OS Recorder Tools for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-unlocking-audible-content-from-twitter-videos/"><u>2024 Approved  Unlocking Audible Content From Twitter Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/linux-vs-windows-a-comprehensive-gamers-guide/"><u>Linux Vs. Windows: A Comprehensive Gamer's Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-ccleaner-issues-in-windows-11/"><u>Overcoming CCleaner Issues in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-chains-of-stuck-files-win11-download-guide-2/"><u>Breaking Chains of Stuck Files: WIN11 Download Guide (2)</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-impact-of-copilot-key-on-your-windows-11-pc-performance/"><u>Deciphering the Impact of Copilot Key on Your Windows 11 PC Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-blue-screen-5-tactics-for-win11-hybrid-issue-fixes/"><u>Conquer Blue Screen: 5 Tactics for Win11 Hybrid Issue Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-running-handbrake-on-widows/"><u>Mastering the Art of Running HandBrake on Widows</u></a></li>
<li><a href="https://windows11.techidaily.com/lost-and-found-how-to-find-the-disappeared-enhancements-on-windows-11/"><u>Lost and Found: How to Find the Disappeared Enhancements on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/discovering-the-power-of-wintoys-a-step-by-step-analysis-for-windows-users/"><u>Discovering the Power of WinToys: A Step-by-Step Analysis for Windows Users</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-whatsapp-messages-on-motorola-moto-g04-without-them-knowing-drfone-by-drfone-virtual-android/"><u>How to Track WhatsApp Messages on Motorola Moto G04 Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-geforce-error-xc0f1103f-in-windows-systems/"><u>Overcoming GeForce Error XC0F1103F in Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-art-of-3d-painting-with-these-tips/"><u>Master the Art of 3D Painting with These Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-non-functional-shortcuts-with-windows-snips/"><u>Avoiding Non-Functional Shortcuts with Windows Snips</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-audio-mix-mastery-the-essence-of-crossfade/"><u>2024 Approved  Audio Mix Mastery  The Essence of Crossfade</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-essential-tips-for-capturing-your-skype-conversations/"><u>[New] 2024 Approved  Essential Tips for Capturing Your Skype Conversations</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/guide-cropping-and-combining-content-in-wondershare-filmora-latest/"><u>Guide Cropping and Combining Content in Wondershare Filmora Latest</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/everyday-snaps-to-professional-videos-the-top-9-mobile-filmmaking-gadgets-for-2024/"><u>From Everyday Snaps to Professional Videos - The Top 9 Mobile Filmmaking Gadgets for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-enhancing-your-snap-with-soundtracks-without-stickers/"><u>[New] 2024 Approved  Enhancing Your Snap with Soundtracks (Without Stickers)</u></a></li>
<li><a href="https://windows11.techidaily.com/corrective-measures-for-discord-search-dysfunction/"><u>Corrective Measures for Discord Search Dysfunction</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/empowering-tiktok-sharing-on-twitter-networks-for-2024/"><u>Empowering TikTok Sharing on Twitter Networks for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-the-blueprint-for-stellar-unboxing-videos-on-tiktok/"><u>[New] The Blueprint for Stellar Unboxing Videos on TikTok</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-incorrect-parameters-leading-to-loadlibrary-failure/"><u>Fixing Incorrect Parameters Leading to LoadLibrary Failure</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-overcome-systemsettingsexe-crash-in-win11/"><u>Steps to Overcome SystemSettings.exe Crash in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-most-frequent-blue-screen-hurdles/"><u>Overcoming the Most Frequent Blue Screen Hurdles</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-windows-ram-usage-for-device-connectivity-services/"><u>Optimizing Windows RAM Usage for Device Connectivity Services</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-non-empty-directory-alert-error-code-0x80070091-in-windows-11/"><u>Preventing Non-Empty Directory Alert (Error Code: 0X80070091) in Windows 11</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/accelerate-vimeo-videos-the-guide/"><u>Accelerate Vimeo Videos  The Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/how-win11-outshines-macos-on-key-fronts/"><u>How Win11 Outshines MacOS on Key Fronts</u></a></li>
</ul></div>
