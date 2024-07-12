---
title: Cooling Down Your Windows 11 Computer
date: 2024-07-11T22:22:22.096Z
updated: 2024-07-12T22:22:22.096Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Cooling Down Your Windows 11 Computer
excerpt: This Article Describes Cooling Down Your Windows 11 Computer
keywords: Win11 Cooling Tips,Optimal PC Temp Reduction,Battery Saver Mode for Win11,Efficient Win11 Overheat Prevention,Balanced CPU Temperature Control,Quick Cool Windows 11,Enhanced System Thermal Management
thumbnail: https://thmb.techidaily.com/46f8f3c70815f152419419ddd699d5297d1d12c7e29c16f1ef4c1543e402a7a3.jpg
---

## Cooling Down Your Windows 11 Computer

 Some common reasons for an overheating computer include poor ventilation, insufficient airflow, and overclocking. But specifically on Windows 11, you may experience high temperatures after upgrading or installing a Windows update.

 The telltale sign of an overheating system is when the CPU starts to idle at 60-70° C. If you noticed a spike in CPU temperature after installing an update, it might be a case of a bad Windows update. CPU overclocking is another common reason for an overheating system.

 If your computer has been running hot, here are a few troubleshooting steps to help you fix an overheating Windows 11 computer.

## 1\. Install Pending Windows Updates

![install windows 11 feature update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/install-windows-11-feature-update.jpg)

 If you determine a recent Windows update to have caused your CPU to overheat, check if a fix is available. If it is a widespread issue, you can expect a hotfix via Windows update.

To update your Windows computer:

1. Press**Win + I** to open**Settings** .
2. Open the**Windows Update** tab in the left pane.
3. Click on**Check for updates** . Next, download and install all the pending updates. Reboot your PC and check for any improvements.

## 2\. Remove a Bad Windows Update

![uninstall windows updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/uninstall-windows-updates.jpg)

 If your system started to overheat after a recent Windows update, try to uninstall the update to fix the issue. You can check the Windows update history in the Settings app. You need to look for an update that matches the timeline when your Windows 11 computer started to overheat. If found, uninstall the update to see if that resolves the problem.

 You can [manually uninstall Windows 11 updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) using Settings and Control Panel. Once uninstalled, check if the CPU temperature is in the ideal range.

## 3\. Check Background Apps for High CPU Usage

![high cpu usage service task manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/high-cpu-usage-service-task-manager.jpg)

 Background apps with high CPU usage are often responsible for an overheating computer. Even if the app is using only 5-6% of your CPU resources, it may still be able to cause high CPU temperature.

 You can use the Windows Task Manager to monitor background services and terminate them if necessary. To do this:

1. Right-click on the**Start menu** and open**Task Manager** .
2. In Task Manager, open the**Process** tab.
3. Click the**CPU** column header to sort the list by CPU usage.
4. Check if any background services have high CPU usage. For example, an audio service that is usually not a resource hog.
5. End the process and check if the CPU temperature decreased. If yes, you'll need to disable the service, and update the associated drivers to fix the problem.

## 4\. Select the Balanced Power Plan

![balanced power pan windows 11 control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/balanced-power-pan-windows-11-control-panel.jpg)

 On Windows 11, you can choose from multiple power plans. By default, the system uses the Balanced power plan to offer sufficient performance and good battery life. If your laptop is set to use the high-performance power plan, it may cause your system to overheat.

 Ideally, the CPU temperature should hover around the 70-80॰ mark under load with the high-performance power plan selected. But as a quick workaround, you can switch to the Balanced power plan to stop your laptop from overheating.

 You can [change the Windows Power Plan using Control Panel](https://www.makeuseof.com/windows-11-change-power-plan/) . Under**Power Options** , review your current plan and select**Balanced (Recommended)** .

## 5\. Change the Maximum Processor State

 You can fix the Windows 11 overheating problem by changing the maximum processor state in processor power management. By default, the maximum processor state is set to 100%. This means, if required, the processor can run at its factory potential and underclock when necessary.

 If you don’t use your processor at 100% all the time, you can throttle the maximum processor state to 99% to fix the overheating issue.

To change the maximum processor state on Windows:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open Control Panel.
3. Go to**System and Security** and click on**Power Options** .  
![power options control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/power-options-control-panel-1.jpg)
4. Next, click the**Change plan settings** option for your currently active power plan.  
![change plan settings power options control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/change-plan-settings-power-options-control-panel.jpg)
5. Click on**Change advanced power settings** .  
![change advanced power settings control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/change-advanced-power-settings-control-panel.jpg)

1. Scroll down and expand the**Processor power management** section.
2. Next, expand the**Maximum processor state** option.  
![change maximum processor state 99 precent](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/change-maximum-processor-state-99-precent.jpg)
3. Select**On Battery** and change the value to**99%** .
4. Select**Plugged in** and change the value to**99%** .
5. Click**Apply** and**OK** to save the changes.

 If the maximum processor state is missing, you can [show the hidden minimum and maximum processor state](https://www.makeuseof.com/windows-minimum-maximum-processor-state-power-options/) using Command Prompt.

 As the new configuration is applied, your CPU temperature should drop immediately. But this comes at a price. Changing the maximum processor state reduces your CPU speed. As a result, you may notice decrease in system performance during gaming sessions and other CPU-intensive tasks.

 Again, this is not a solution, as you shouldn’t have to manually tweak these settings to get optimal thermal performance for your computer. But this is a known workaround and should work for most people who don’t need to use the maximum potential of their CPU all the time.

 If the issue persists, your computer is likely [overheating due to insufficient airflow, fan problems, and driver issues](https://www.makeuseof.com/how-to-fix-overheating-computer/) .

## 6\. Disable Windows Search Indexing

 Searchindexer is a Windows service that facilitates faster Windows search. While it works in the background, this service can cause high CPU usage, thus resulting in high temperatures.

 You can manage search indexing to exclude specific folders from indexing. You can also [completely turn off Windows Search Indexer](https://www.makeuseof.com/windows-search-indexer-guide/) to see if that helps resolve the overheating problem on your computer.

## 7\. Adjust the Performance Option to "Best Performance"

![The Adjust for best performance option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/adjust-for-best-performance-option.jpg)

 If your computer is overheating under heavy use like gaming, you can adjust your system to offer the best performance. Adjusting for best performance comes at the cost of reduced visual effects.

To adjust your computer for best performance:

1. Press the**Win** key and type**Adjust performance** .
2. Click on**Adjust the appearance and performance of Windows** option from the search result.
3. Next, select**Adjust for best performance** in the**Performance Options** dialog.
4. Click**Apply** and**OK** to save the changes.

## 8\. Go Back to the Previous Version

![go back to previous version windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/go-back-to-previous-version-windows-11.jpg)

 If you are unable to uninstall a Windows update, you can use the**Go back** recovery option to reinstall the previous version of Windows. This option is only available for 10 days after a major Windows update is installed

To use the Go back option:

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, scroll down and click on**Recovery** .
3. Under the**Recovery options** section, click on**Go back** . Follow on-screen instructions to go back to the previous version of Windows.

 If the option is greyed out, the option is no longer available on your PC. Windows disables the Go back recovery option 10 days after the upgrade. You can, however, extend the [10 days go-back period to 60 days on Windows 11](https://www.makeuseof.com/windows-11-extend-rollback-period/) using Command Prompt.

## 9\. Perform a System Restore

![system restore select restore point](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/system-restore-select-restore-point.jpg)

 Windows 11 automatically creates a snapshot of your system’s current state, known as restore points. A new restore point is created before installing an update. You can use an existing restore point to undo the changes and fix any issues that may have occurred due to a bad Windows update or recent changes made to your system.

To perform a system restore:

1. Press**Win + R** to open**Run** .
2. Type**rstrui.exe** and click**OK** to open the**System Restore** dialog.
3. Click**Next** .
4. Select the most recent restore point. Make sure the restore point is dated before you noticed the overheating issue.
5. Click**Next** and then click**Finish** .

 A restore point won’t remove your files and folders. However, it will remove apps and games installed after the restore point was created.

## 10\. Check for Hardware Issues

 A clean install should fix any issues occurring due to a software conflict. But, before performing a clean install, look into other issues to [fix your overheating laptop](https://www.makeuseof.com/tag/fix-overheating-laptop/) .

 First and foremost, check your laptop vents and clean them if necessary. Next, make sure to keep your laptop on a hard surface that allows the vents to displace hot air. A good laptop cooler can offer external cooling support and keep the temperature low.

## 11\. Clean Install Windows 11

 A Windows clean install may seem extreme, but it can be necessary to purge the remanent system files and drivers after the upgrade. Some of these drivers and files can cause your system to malfunction and overheat. If you have upgraded to Windows 11 from Windows 10, a clean install may be due.

 To clean install Windows 11, all you need is a [Windows 11 bootable USB drive](https://www.makeuseof.com/windows-11-create-bootable-usb-drive/) . Next, back up your personal files and folders to an external drive. Once done, boot from the USB drive and reinstall the OS.

## Fixing an Overheating Windows 11 Computer

 To fix an overheating Windows 11 computer, troubleshoot it for background services and bad Windows updates. Additionally, unblock the vents, clean the internals, and use a laptop on a hard surface to allow sufficient airflow.

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
<li><a href="https://windows11.techidaily.com/decode-subtitle-failures-in-prime-windows-11-collaboration/"><u>Decode Subtitle Failures in Prime, Windows 11 Collaboration</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-network-analysis-on-windows-11-the-netstat-command-guide/"><u>Conquer Network Analysis on Windows 11: The Netstat Command Guide</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/the-leading-selection-of-tools-to-download-facebook-lite-videos/"><u>The Leading Selection of Tools to Download Facebook Lite Videos</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-oppo-reno-8t-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Oppo Reno 8T Phones with/without a PC</u></a></li>
<li><a href="https://windows11.techidaily.com/declutter-data-step-by-step-hdd-defrag-for-win11/"><u>Declutter Data: Step-by-Step HDD Defrag for Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-interval-for-automatic-logoff/"><u>Customizing Interval for Automatic Logoff</u></a></li>
<li><a href="https://windows11.techidaily.com/create-a-gratis-local-gptclone-with-gpt4all-for-windows/"><u>Create a Gratis, Local GPTClone with GPT4All for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-the-path-fixing-windows-11-writable-errors/"><u>Clearing the Path: Fixing Windows 11' Writable Errors</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-motorola-moto-g73-5g-to-iphone-xs11-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Motorola Moto G73 5G to iPhone XS/11 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/concealed-compression-stashing-archives-in-windows-picture-files/"><u>Concealed Compression: Stashing Archives in Windows Picture Files</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-camera-glitch-solve-error-a00f4289-on-pcs/"><u>Disabling Camera Glitch: Solve Error A00F4289 on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/curing-white-screen-problems-on-store-platform/"><u>Curing White Screen Problems on Store Platform</u></a></li>
<li><a href="https://youtube-web.techidaily.com/n-2024-customize-video-speed-to-match-your-desired-watch-time/"><u>[New] In 2024, Customize Video Speed to Match Your Desired Watch Time</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-maximizing-online-exposure-on-youtube-by-keeping-up-creative-commons-usage/"><u>[Updated] In 2024, Maximizing Online Exposure on YouTube by Keeping Up Creative Commons Usage</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-oculus-install-error-on-wincx-a-helpful-guide/"><u>Conquering Oculus Install Error on WinCX: A Helpful Guide</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-15-to-other-iphone-13-pro-max-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 15 to other iPhone 13 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-a-lost-vivo-s17t-for-free-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track a Lost Vivo S17t for Free? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/creating-personalized-music-cds-with-mp3s-a-compreenasive-guide-for-windows-users-imgburn/"><u>Creating Personalized Music CDs with Mp3s: A Compreenasive Guide for Windows Users (ImgBurn)</u></a></li>
<li><a href="https://techidaily.com/unlock-a-disable-iphone-se-using-find-my-iphone-by-drfone-ios-unlock-ios-unlock/"><u>Unlock a disable iPhone SE using find my iphone</u></a></li>
<li><a href="https://windows11.techidaily.com/disable-windows-tracked-application-usage/"><u>Disable Windows' Tracked Application Usage</u></a></li>
<li><a href="https://android-unlock.techidaily.com/a-perfect-guide-to-remove-or-disable-google-smart-lock-on-samsung-galaxy-m34-5g-by-drfone-android/"><u>A Perfect Guide To Remove or Disable Google Smart Lock On Samsung Galaxy M34 5G</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-becoming-a-facetime-videographer-extraordinaire/"><u>[Updated] Becoming a Facetime Videographer Extraordinaire</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/overview-of-the-best-zte-nubia-z60-ultra-screen-mirroring-app-drfone-by-drfone-android/"><u>Overview of the Best ZTE Nubia Z60 Ultra Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/command-line-tip-disable-amdnvidia-gpu-enhancements/"><u>Command Line Tip: Disable AMD/Nvidia GPU Enhancements</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-transform-your-footage-sony-digital-camcorder-video-editing-essentials-for-2024/"><u>New Transform Your Footage Sony Digital Camcorder Video Editing Essentials for 2024</u></a></li>
<li><a href="https://techidaily.com/how-to-perform-hard-reset-on-honor-x50-drfone-by-drfone-reset-android-reset-android/"><u>How to Perform Hard Reset on Honor X50? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/detailed-steps-to-fully-remove-wsl/"><u>Detailed Steps to Fully Remove WSL</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-master-the-art-of-tiktok-video-making-with-ease-and-flair/"><u>[New] 2024 Approved  Master the Art of TikTok Video Making with Ease & Flair</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-phonelinkexe-important-for-windows-users/"><u>Disabling PhoneLink.exe: Important for Windows Users?</u></a></li>
<li><a href="https://android-unlock.techidaily.com/top-4-sim-location-trackers-to-easily-find-your-lost-samsung-galaxy-z-flip-5-device-by-drfone-android/"><u>Top 4 SIM Location Trackers To Easily Find Your Lost Samsung Galaxy Z Flip 5 Device</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-unlock-the-secrets-of-webinar-recording-a-users-manual-macos-windows/"><u>In 2024, Unlock the Secrets of Webinar Recording  A User's Manual (macOS, Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-admin-settings-causing-windows-security-failsafe/"><u>Disabling Admin Settings Causing Windows Security Failsafe</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-fatal-component-error-in-win10win11-system/"><u>Disabling Fatal Component Error in Win10/Win11 System</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-archivists-arsenal-pivotal-80s-vhs-tricks-for-editors/"><u>2024 Approved  The Archivist’s Arsenal  Pivotal 80S VHS Tricks for Editors</u></a></li>
<li><a href="https://howto.techidaily.com/app-wont-open-on-your-vivo-y100a-here-are-all-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>App Wont Open on Your Vivo Y100A? Here Are All Fixes | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-windows-servers-resolving-no-servers-found-in-apex-legends-(156-chars/"><u>Conquer Windows Servers: Resolving No Servers Found in Apex Legends (<156 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-a-driverirqlnotlessorequal-in-windows/"><u>Clearing Up A DRIVER_IRQL_NOT_LESS_OR_EQUAL in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/deletion-directives-for-software-in-windows-11-the-quick-way-116-chars/"><u>Deletion Directives for Software in Windows 11: The Quick Way (116 Chars)</u></a></li>
</ul></div>
