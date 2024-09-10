---
title: Steps to Reinstall Non-Loading Drivers in Windows 11
date: 2024-09-09T12:15:51.356Z
updated: 2024-09-10T12:15:51.356Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Reinstall Non-Loading Drivers in Windows 11
excerpt: This Article Describes Steps to Reinstall Non-Loading Drivers in Windows 11
keywords: Reinstall Driver,Windows 11 Driver Fix,Non-Loading Drivers Remedy,Load Non-Driver Issue,Windows 11 Update Drivers,Drivers Install Procedure,Windows Driver Reinstall Guide
thumbnail: https://thmb.techidaily.com/b1aabf9182a40f39eacfea832a56e2883c1058666aaa24cc7d5f400170f744e3.jpeg
---

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123479/16836" target="_top" id="2123479">
  <img src="//a.impactradius-go.com/display-ad/16836-2123479" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123479/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Steps to Reinstall Non-Loading Drivers in Windows 11

 Windows loads drivers every time you power on your PC. However, some users face the "A driver can't load on this device" error after they boot to the desktop. This error can arise while installing an unsigned driver or due to a meddlesome application.

 In this guide, we will discuss some methods to resolve this issue and restore your PC drivers to a normal working state.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130869/7443" target="_top" id="2130869">
  <img src="//a.impactradius-go.com/display-ad/7443-2130869" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130869/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Check for Optional Windows Updates

 Optional updates can contain driver updates for your device components. So, you must check for available driver updates in the Windows Update Settings. Repeat the following steps:

1. Press **Win + I** to launch the Settings app.
2. Click on the **Windows Update** icon.
3. Now click on the **Advanced options**.
4. Scroll down to the **Additional Options** section. Click on the **Optional Updates** option.
5. Check if any optional updates related to the device you are facing issues with are available. Download and install it.  
![Install optional updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/install-optional-updates.jpg)
6. **Close** the Settings app.
<!-- affiliate ads begin -->
<a href="https://bluettiit.sjv.io/c/5597632/2114263/17093" target="_top" id="2114263">
  <img src="//a.impactradius-go.com/display-ad/17093-2114263" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluettiit.sjv.io/i/5597632/2114263/17093" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can also visit the device manufacturer’s website to download the latest updated drivers, which will be digitally signed. These should pose no issues during installation.

## 2\. Disable the Memory Integrity Feature

 Memory Integrity is a security feature that leverages virtualization to protect unauthorized programs from making changes to important security processes. But this security setting can prevent a driver from loading old or unsigned drivers from running on your PC.

 So, you must disable Memory Integrity. Repeat the following steps:

1. Press **Win + I** to open the Settings app.
2. Click on the **Privacy & security** option in the left-hand side menu.
3. Now, click on the **Windows Security** option.
4. Scroll down and click on the **Device Security** option.
5. Navigate to the Core Isolation section. Click on the **Core isolation details** option.
6. Disable the **toggle** present below the **Memory Integrity** option.  
![Disable Memory Integrity](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/disable-memory-integrity.jpg)
7. **Restart** your PC to apply the changes.

 Now, check if the “a driver cannot load on this device” still pops up.

## 3\. Uninstall Any Recent System Updates

 If you are encountering an issue with a driver after installing a recent Windows update, you should consider removing that from your PC. Rolling back the update won’t remove any of your personal files.

 Check our guide on [ways to manually uninstall Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) for more information. But remember that it is not possible to remove all installed updates.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135411/19272" target="_top" id="2135411">
  <img src="//a.impactradius-go.com/display-ad/19272-2135411" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135411/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Modify the System Registry

 Corrupt registry entries for the device can also be a reason for the hardware device encountering the driver issue. So, you must modify the system registry and remove those corrupt entries for the device.

 Make sure to manually export a [backup of your PC registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) onto a removable drive, so you always have the option to revert to the last working configuration.

 Repeat the following steps:

1. Right-click on the **Start** button to open the **Power User menu**. Click on the **Device Manager** option.
2. Locate the device facing driver issues and double-click on it to open its **Properties**.
3. Switch to the **Details** tab.
4. Click on the drop-down tab and click on the **Class GUID** option. It will display the GUID. **Copy** it to the clipboard.  
![Checking GUID in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/checking-guid-in-device-manager.jpg)
5. Press **Win + R** to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **Regedit** and press the **Ctrl + Shift + Enter** keys to open the Registry editor.
6. Paste the following path into the address bar and press the **Enter** key:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Class\`
7. Press **Ctrl + F** to open the **Find** window. **Paste** the copied GUID and click on the **Find Next** option.
8. Go to the right-hand side pane of the found GUID key. Find the **UpperFilters** value.
9. Right-click on it and select the **Delete** option.  
![Modify the System Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/modify-the-system-registry.jpg)
10. Similarly, find the **LowerFilters** value and then delete it as well. Some devices may not have this value.
11. **Restart** your PC for the changes to take effect.

## 5\. Reinstall or Remove the Concerned Application

 Some users face an eny.sys driver issue which controls RGB lighting on PCs. This is a problem for many MSI and ASUS PC users. It is not a system utility and if it encounters an error every time, you must reinstall the concerned RGB-lighting-controlled application.

 Reinstalling the latest version will ensure that the application comes with signed drivers and fixes the driver issues with Windows 11 PCs. Here’s how to do it:

1. Right-click on the **Start** button to open the **Power User menu**.
2. Click on the **Installed apps** option.
3. Find the concerned RGB-controlling application and click on the **ellipsis** icon. Select the **Uninstall** option.
4. Click on the **Uninstall** button.  
![Remove a meddlesome application](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/remove-a-meddlesome-application.jpg)

 After removing the app, restart your PC and check if the error pops up now. Now, visit the app manufacturer's website and download the recent version of the RGB-control app. Install it and check if it causes the driver error. If that is the case, then you must remove the application.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123476/16836" target="_top" id="2123476">
  <img src="//a.impactradius-go.com/display-ad/16836-2123476" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123476/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Use System Restore

 System Restore is an excellent utility baked into Windows that helps you fix issues in one go. It will roll back your PC to an earlier state when there were no abrupt issues with your PC.

 Check our guide on [how to use System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/) and revert to an earlier PC state without losing your personal files. However, all the installed apps and updates after the restore point will be removed, if you adopt this route.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135368/19272" target="_top" id="2135368">
  <img src="//a.impactradius-go.com/display-ad/19272-2135368" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135368/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Your Driver Issues on Windows 11, Fixed

 These are the best methods you can use to fix the "A driver can't load on this device" error on your Windows 11 PC. Update all the device drivers, install optional updates, and disable memory integrity. After that, modify the system registry and remove the meddlesome RGB application to get rid of this problem.

 In this guide, we will discuss some methods to resolve this issue and restore your PC drivers to a normal working state.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-glue.techidaily.com/new-2024-approved-deep-dive-into-theta-s-a-full-camera-examination/"><u>[New] 2024 Approved Deep Dive Into Theta S A Full Camera Examination</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-gofundme-campaign-imagery-tips/"><u>[New] In 2024, GoFundMe Campaign Imagery Tips</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-managing-bitrate-in-obs-broadcasts/"><u>[New] In 2024, Managing Bitrate in OBS Broadcasts</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/rreversible-termination-of-youtubes-brevity-mode/"><u>[New] Irreversible Termination of YouTube’s Brevity Mode</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-optimal-mp4-senders-for-fb-networks-for-2024/"><u>[New] Optimal MP4 Senders for FB Networks for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-prodigious-cameras-for-slow-motion-delight/"><u>[New] Prodigious Cameras for Slow-Motion Delight</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-the-best-laptops-for-video-editing-you-should-know-for-2024/"><u>[New] The Best Laptops For Video Editing You Should Know for 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/new-unveiling-iphone-xs-advanced-photography-tools-for-2024/"><u>[New] Unveiling iPhone X's Advanced Photography Tools for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-capturing-timeless-moments-iphones-prolonged-shots-guide/"><u>[Updated] Capturing Timeless Moments IPhone’s Prolonged Shots Guide</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-crafting-sequences-a-movie-maker-approach-to-animation-for-2024/"><u>[Updated] Crafting Sequences A Movie Maker Approach to Animation for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-instagram-tutorial-implementing-a-clean-color-separation/"><u>[Updated] In 2024, Instagram Tutorial Implementing a Clean Color Separation</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-unveiling-5-strategies-for-fb-story-access-on-pctablet-and-phone/"><u>[Updated] Unveiling 5 Strategies for FB Story Access on PC/Tablet and Phone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-win-11-mov-file-recording-guide-for-2024/"><u>[Updated] Win 11 MOV File Recording Guide for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/a-journey-to-vivid-visuals-top-11-hue-enhancement-guides-for-2024/"><u>A Journey to Vivid Visuals Top 11 Hue Enhancement Guides for 2024</u></a></li>
<li><a href="https://data-wizards.techidaily.com/android-media-playback-assistance/"><u>Android Media Playback Assistance</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/cannot-play-mkv-files-on-xiaomi-redmi-k70-by-aiseesoft-video-converter-play-mkv-on-android/"><u>Cannot play MKV files on Xiaomi Redmi K70</u></a></li>
<li><a href="https://fox-http.techidaily.com/closer-look-techniques-for-effective-collaboration-on-ms-teams-for-2024/"><u>Closer Look Techniques for Effective Collaboration on MS Teams for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/decision-time-should-i-embrace-the-latest-ios-update/"><u>Decision Time: Should I Embrace the Latest iOS Update?</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/explore-androids-leading-music-video-watching-tools/"><u>Explore Android's Leading Music Video Watching Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-access-denied-roblox-game-due-to-pc-settings/"><u>Fixing Access Denied Roblox Game Due To PC Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-error-2e-to-enable-windows-update/"><u>Fixing Error 2E to Enable Windows Update</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-mute-microphones-reclaim-your-systems-voice/"><u>Fixing Mute Microphones: Reclaim Your System's Voice</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-requested-operation-requires-elevation-error-740-on-windows-11-and-11/"><u>How to Fix the “Requested Operation Requires Elevation” Error 740 on Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-hardware-problems-were-detected-error-in-the-windows-memory-diagnostic-tool/"><u>How to Fix the Hardware Problems Were Detected Error in the Windows Memory Diagnostic Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-locate-missing-gateway-ubisofts-launcher/"><u>How To Locate Missing Gateway: Ubisoft's Launcher</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-open-windows-media-player-simple-instructions/"><u>How to Open Windows Media Player: Simple Instructions</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-7-plus-to-other-iphone-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 7 Plus To Other iPhone devices? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-fix-oppo-reno-8t-5g-find-my-friends-no-location-found-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix Oppo Reno 8T 5G Find My Friends No Location Found? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/instant-relief-guaranteed-solution-to-boot-time-sound-service-fix/"><u>Instant Relief: Guaranteed Solution to Boot-Time Sound Service Fix</u></a></li>
<li><a href="https://windows11.techidaily.com/maximize-storage-calculating-app-usage-in-windows/"><u>Maximize Storage: Calculating App Usage in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/minimizing-delays-boosting-speed-of-windows-discord-app/"><u>Minimizing Delays: Boosting Speed of Windows Discord App</u></a></li>
<li><a href="https://windows11.techidaily.com/missing-screen-saviors-how-to-reclaim-windows-10-and-11-panels/"><u>Missing Screen Saviors: How to Reclaim Windows 10 & 11 Panels</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-frequent-rainmeter-quirks-on-your-system/"><u>Navigating Through Frequent Rainmeter Quirks on Your System</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-to-file-explorer-bypassing-quick-access-with-onedrive/"><u>Navigating to File Explorer Bypassing Quick Access with OneDrive</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-system-crashes-fixing-c0000022-fatalities/"><u>Navigating Windows System Crashes: Fixing C0000022 Fatalities</u></a></li>
<li><a href="https://windows11.techidaily.com/no-apps-needed-windows-11-note-hacks/"><u>No Apps Needed: Windows 11 Note Hacks</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/nvidia-geforce-rtx-2070-drivers-latest-version-download-compatible-with-win-1087/"><u>NVIDIA Geforce RTX 2070 Drivers - Latest Version Download Compatible with Win 10/8/7</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-your-window-experience-essential-product-key-insights/"><u>Optimize Your Window Experience: Essential Product Key Insights</u></a></li>
<li><a href="https://windows11.techidaily.com/overhauling-deactivated-windows-11-keys/"><u>Overhauling Deactivated Windows 11 Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/priority-toolkit-best-free-resources-for-win11-power/"><u>Priority Toolkit: Best Free Resources for Win11 Power</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-overcoming-fullscreen-obstacles-on-windows/"><u>Quick Guide: Overcoming Fullscreen Obstacles on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivate-your-windows-11-explore-with-ease/"><u>Reactivate Your Windows 11 Explore with Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/redefining-initial-web-portal-for-new-windows-user/"><u>Redefining Initial Web Portal for New Windows User</u></a></li>
<li><a href="https://windows11.techidaily.com/reimagining-windows-focusing-on-essential-upgrades/"><u>Reimagining Windows: Focusing on Essential Upgrades</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-directx-install-failures-on-pcs/"><u>Resolving DirectX Install Failures on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-needs-old-pass-troubleshooting-tips/"><u>Resolving Windows Needs Old Pass: Troubleshooting Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-accuracy-fixed-discord-games-status-errors-windows/"><u>Restoring Accuracy: Fixed Discord Games Status Errors (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-windows-defenders-threat-barrier-a-top-5-approach-to-restoration/"><u>Reviving Windows Defender’s Threat Barrier: A Top 5 Approach to Restoration</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-system-security-top-5-techniques-to-resolve-keys-mismatches-in-win11/"><u>Seamless System Security: Top 5 Techniques to Resolve Keys Mismatches in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/sneak-peek-into-windows-11s-undercover-menus/"><u>Sneak Peek Into Windows 11'S Undercover Menus</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-invisible-additional-screen/"><u>Tackling Invisible Additional Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-command-setup-easy-access-shortcuts-next-to-win11-writes/"><u>Tailored Command Setup: Easy Access Shortcuts Next to Win11' Writes</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-image-rotation-on-your-windows-11-pc/"><u>The Art of Image Rotation on Your Windows 11 PC</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/transform-your-social-media-status-with-these-best-30-tiktok-handles/"><u>Transform Your Social Media Status with These Best 30 TikTok Handles</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-resolving-a-non-responsive-mouse-on-your-pc/"><u>Ultimate Guide: Resolving a Non-Responsive Mouse on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-the-pathway-for-fixing-virtualboxs-efail-error/"><u>Unblocking the Pathway for Fixing Virtualbox's E_FAIL Error</u></a></li>
<li><a href="https://windows11.techidaily.com/uninstalling-epic-launcher-on-w11-solutions-present/"><u>Uninstalling Epic Launcher on W11 - Solutions Present</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-power-restarting-file-explorer-on-win-11/"><u>Unlock the Power: Restarting File Explorer on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-rdp-access-on-windows-11-no-password/"><u>Unlocking RDP Access on Windows 11 No Password</u></a></li>
<li><a href="https://windows11.techidaily.com/why-does-task-manager-list-unrelated-processes-under-microsoft-edge/"><u>Why Does Task Manager List Unrelated Processes Under Microsoft Edge?</u></a></li>
<li><a href="https://windows11.techidaily.com/win-based-problem-solving-tackling-error-9999-in-audacity/"><u>Win-Based Problem Solving: Tackling Error 9999 in Audacity</u></a></li>
<li><a href="https://windows11.techidaily.com/win10win11-fixing-unidentified-device-errors/"><u>Win10/Win11: Fixing Unidentified Device Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-recover-unseen-additional-monitor/"><u>Windows 11: Recover Unseen Additional Monitor</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>