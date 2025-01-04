---
title: "Troubleshooting Guide: Win11/10's NVidia Access Problems"
date: 2024-12-31T16:43:49.970Z
updated: 2025-01-03T18:36:04.142Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Troubleshooting Guide: Win11/10's NVidia Access Problems"
excerpt: "This Article Describes Troubleshooting Guide: Win11/10's NVidia Access Problems"
keywords: Fix NVidia Issues,Resolve Win11 Graphics,Win10 Nvidia Troubleshoot,Nvidia Driver Fix Guide,Solve Windows GPU Problems,Enhance WinNvidia Performance,Overcome Access Errors in NVidia
thumbnail: https://thmb.techidaily.com/34ef4ca08c3dfcb784929375e3e95bcc8f2ba621080c440e931274a3c95d80cc.jpg
---

## Troubleshooting Guide: Win11/10's NVidia Access Problems

 The NVIDIA Control Panel is an app included on PCs with NVIDIA GPUs with which users can change graphical settings. However, some users can’t change NVIDIA Control Panel options because of an “Access denied” error. The message of that error says, “Failed to apply selected settings to your system.”

 The “Access denied” error is mostly reported to arise for 3D settings. As a result, NVIDIA Control Panel doesn’t apply (save) the settings users select. This is how you can resolve NVIDIA Control Panel’s “Access denied” error within Windows 11/10.

## 1\. Run the NVIDIA Control Panel as an Administrator

 Firstly, try running the NVIDIA Control Panel with elevated admin permissions, which has worked for some users. To do that, press the**Windows** logo +**S** keyboard buttons and input NVIDIA Control Panel. Right-click NVIDIA Control Panel and select**Run as administrator** .

![The Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-as-administrator-option2.jpg)

 Should this potential fix work, then it would be better to set the NVIDIA Control Panel to always run with administrative rights. However, that UWP app is located within a protected folder. You’ll need to[take ownership of the WindowsApps folder](https://www.makeuseof.com/windows-10-11-own-folder/) to set permanent admin rights for the NVIDIA Control Panel.

 If you take ownership of the WindowsApps folder, open the NVIDIACorp subfolder to reach the NVIDIA Control Panel file. Then you’ll need to set the nvcplui.exe file to run with admin rights. Follow the steps in this how to[set an app to always run as an administrator guide](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) to set elevated permissions for the nvcplui.exe file. The path for the NVIDIA Control Panel folder is:

`C:\Program Files\WindowsApps\NVIDIACorp.NVIDIAControlPanel_8.1.964.0_x64__56jybvy8sckqj`

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mHFtYJppXFk?si=ylFaAT4nXqCmlV8F" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Select the Repair and Reset Options for the NVIDIA Control Panel

 The NVIDIA Control Panel app has**Repair** and**Reset** troubleshooting options you can select in Settings. Both options can be useful for fixing apps when they’re not working right. So, try selecting the**Repair** option first and then**Reset** to clear the app’s data if repairing isn’t enough. Check out this[article about resetting apps in Windows](https://www.makeuseof.com/windows-reset-app/) for details about how to apply this potential fix.

![The Repair and Reset option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/repair-reset-options.jpg)

## 3\. Start or Restart the NVIDIA Display Container Service

 The NVIDIA Display Container is an important GPU service that runs numerous other NVIDIA background tasks. Make sure that service is running or restart it if it is. You can start or restart NVIDIA Display Container like this:

1. Click the**Type here to search** button or the Search box on the taskbar to access the Windows file finder tool.
2. Input**services** inside the file search utility.
3. Select**Services** to launch that app.
4. Then double-click**NVIDIA Display Container** to view the settings for that service.  
![The Services app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-services-app.jpg)  
 Screenshot captured by Jack Slater - No attribution required

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6X24fPKs6AE?si=YtQy-8zy7GifgfA7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Click on the**Startup type** menu and select**Automatic** from there.
6. Next, select**Start** if the NVIDIA Display Container service is stopped. Or select**Stop** \>**Start** to restart that service.  
![The NVIDIA Display Container service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/nvidia-display-container-service.jpg)
7. Click**Apply** to set the NVIDIA Display Container service’s settings.
8. Close the NVIDIA Display Container Properties window by clicking**OK** .

## 4\. Update Your NVIDIA Graphics Card Driver

 The most widely confirmed fix for the “Access denied” error is to manually update the NVIDIA graphics driver. Thus, this is often an issue caused by outdated or faulty NVIDIA drivers. This[guide to updating NVIDIA drivers](https://www.makeuseof.com/how-update-nvidia-graphics-card-drivers-windows/) provides further details about how to apply this potential solution by manually downloading the latest GPU driver available from the NVIDIA site.

 When you’ve downloaded the latest NVIDIA driver package for your GPU, bring up the directory that includes its setup file. Double-click the NVIDIA driver package file to view its setup wizard and select the**Custom** option. Then select the**Perform a clean installation** checkbox and click**Next** to install.

![The Perform a clean installation checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/perform-a-clean-installation.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MHafwnWSEQk?si=rejNVNpJZH2SqNLy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Roll Back the NVIDIA Driver

 If the “Access denied” error arises after installing a new NVIDIA driver, rolling back that driver to a previous one could be a viable potential solution. You’ll only be able to do that if the previous NVIDIA GPU driver file is still available. Our[article about rolling back drivers](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) includes guidelines for how to apply this potential fix.

 If the**Roll Back** option is grayed out, you might still be able to roll back to a previous NVIDIA graphics driver with the System Restore utility. Rolling Windows back to a restoration point restores drivers installed before the selected date. However, that will only work if your PC has a restore point that predates the driver update.

![The Roll Back Driver button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/roll-back-driver-option.jpg)

 This[post about creating and utilizing restore points](https://www.makeuseof.com/windows-11-create-restore-point/) tells you how to roll back Windows. Select a restore point that will restore the previous NVIDIA graphics driver. You can click**Scan for affected** programs in System Restore to check if a chosen restoration point will restore an NVIDIA graphics driver.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZblaBc-v2vs?si=CKW1gJwXQT2vZJYo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Restore a Previous Version of the DRS Folder

 Some NVIDIA Control Panel users have said they fixed the “Access denied” error by restoring a DRS folder version backup. Note that you’ll only be able to apply this potential fix if you’ve got File History enabled or restore points saved on your PC. This is how you can restore a previous DRS folder version in Windows 11/10:

1. First, bring up File Explorer by clicking the taskbar button with the folder library icon.
2. Then click the**View** button to select a**Show** option.
3. Select the**Hidden Items** option.  
![The Hidden items checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/hidden-items-option.jpg)
4. Clear Explorer’s address bar to input the following path:  
`C:\ProgramData\NVIDIA Corporation`
5. Then right-click the DRS folder and select**Properties** .
6. Click the**Previous Versions** tab.  
![The Previous Versions tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/previous-version-tab.jpg)
7. Select the most recent folder version shown in that tab.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zmXpl6irBYk?si=BXjGpQr6PXFcqhCI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

8. Click the**Restore** button.

 To select the same**Hidden Items** option in Windows 10, you’ll need to open the**View** tab in Explorer. Then select the checkbox labeled**Hidden Items** on that tab.

## 7\. Turn Off the Game Bar

 It’s also recommended to turn off the Game Bar in case that’s causing any issues with the NVIDIA Control Panel. This potential resolution applies more to Windows 10 since Windows 11’s Settings app doesn’t include a specific option for disabling the Game Bar. You can turn off the Game Bar in Windows 10 like this:

1. Open Settings by clicking the cog icon on the Start menu.
2. Click the**Gaming** category.
3. Then turn off the**Enable Xbox Game Bar** option.  
![The Xbox Game Bar setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-xbox-game-bar-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X4q6gyaEojM?si=ImdFm6Zsr0azykqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Change Your Settings in the NVIDIA Control Panel Again

 Many users have resolved NVIDIA Control Panel’s “Access denied” error with the potential fixes covered above. So, the probability one of them will also fix that issue on your PC is good. With that issue sorted, you can change all settings in the NVIDIA Control Panel as required.

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
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-borrow-premium-image-footage-via-top-rated-4-youtube-channels/"><u>[Updated] In 2024, Borrow Premium Image Footage via Top-Rated 4 YouTube Channels</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-leveraging-youtube-for-affiliate-earnings/"><u>[Updated] Leveraging YouTube for Affiliate Earnings</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-tackling-massed-up-tiktoks-expert-edits-for-less-chaos/"><u>[Updated] Tackling Massed-Up TikToks Expert Edits for Less Chaos</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-ultimate-steps-to-document-lol-encounters/"><u>[Updated] Ultimate Steps to Document LOL Encounters</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-unveiling-the-power-of-photos-a-comprehensive-polarr-guide/"><u>2024 Approved Unveiling the Power of Photos A Comprehensive Polarr Guide</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-gps-joystick-to-fake-gps-location-on-tecno-camon-20-pro-5g-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use GPS Joystick to Fake GPS Location On Tecno Camon 20 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-guide-fixing-the-critical-halo-t-4-ue4-fatal-error-and-avoiding-system-crashes/"><u>Comprehensive Guide: Fixing the Critical Halo T 4 UE4 'Fatal Error' & Avoiding System Crashes</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-11-taskbar-malfunction/"><u>Fixing Windows 11 Taskbar Malfunction</u></a></li>
<li><a href="https://windows11.techidaily.com/getting-acquainted-with-windows-11-controls/"><u>Getting Acquainted with Windows 11 Controls</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-motorola-moto-g73-5g-to-laptop-without-usb-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos from Motorola Moto G73 5G to Laptop Without USB | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/mp4-video-repair-tool-repair-corrupt-damaged-unplayable-video-files-of-google-pixel-8-pro-by-stellar-video-repair-mobile-video-repair/"><u>MP4 Video Repair Tool - Repair corrupt, damaged, unplayable video files of Google Pixel 8 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/pinpointing-where-windows-stores-new-software/"><u>Pinpointing Where Windows Stores New Software</u></a></li>
<li><a href="https://windows11.techidaily.com/prioritize-prerequisites-to-boost-virtualbox-integration/"><u>Prioritize Prerequisites to Boost VirtualBox Integration</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-backward-typing-glitches-on-windows/"><u>Resolving Backward Typing Glitches on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-uninstall-routine-for-wsl-in-windows-11/"><u>The Ultimate Uninstall Routine for WSL in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-intel-unison-non-operational-status-in-windows-11/"><u>Troubleshooting Intel Unison Non-Operational Status in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-driver-reset-guide-for-clear-images/"><u>Windows 11 Driver Reset Guide for Clear Images</u></a></li>
</ul></div>

