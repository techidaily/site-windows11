---
title: Tackling 'In-Use' Status on Network Resources in Windows 11
date: 2024-11-28T20:39:29.286Z
updated: 2024-12-04T04:44:03.133Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling 'In-Use' Status on Network Resources in Windows 11
excerpt: This Article Describes Tackling 'In-Use' Status on Network Resources in Windows 11
keywords: Win11 Resource Management,In-Use Monitoring (Windows),Windows 11 Usage Tracking,Network Resource Auditing,Active Resources in Win11,Usage Status Determination,Dynamic Resource Control Windows
thumbnail: https://thmb.techidaily.com/b344d8db48d6d42211b0b57079da5753b23f49ded262febe57a071aa1b9c893a.jpg
---

## Tackling 'In-Use' Status on Network Resources in Windows 11

 Users have reported “the requested resource in use” error message pops up on their PCs when trying to copy or move files from mobile devices to their Windows PCs. That error message’s heading also says, “error copying file or folder.” As a result, users can’t copy the files they need to.

 Here is how you can fix the “requested resource is in use” error on a Windows 10 or 11 PC.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uV3vm805eX0?si=YSPcsFxBcJmoxLsU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Check if the File Is Already in Use

![The End task option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-end-task-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Bov2KfWQ_Y?si=MnVczisgeJ-sGW2r" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The “requested resource is in use” error message hints that the file (resource) you’re trying to copy is already in use. Thus, the copy operation cannot be completed because something else is using the file or folder. So, you might need to close some background processes to address this issue.

 First, move your mouse’s cursor over the File Explorer taskbar icon to see if there are any windows for active file operations. Cancel any active file operations you see. Then try copying the file again.

 If that doesn’t work, go into Task Manager and close superfluous third-party app background processes. Our guide to [fixing too many background processes on Windows](https://www.makeuseof.com/windows-pc-too-many-background-processes/) provides further instructions for how you can do that.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gyGoQi7hsZk?si=8OcKcPUj2wSBmVZ1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Disable File Explorer’s Preview Pane

 Many users have fixed the “requested resource is in use” error by disabling File Explorer’s preview pane. That preview pane can hinder the file copy operation. You can disable File Explorer’s preview pane in Windows 11 as follows:

1. Press the **Win + E** key combination to launch File Explorer.
2. Then click the **View** menu button.
3. Select the **Show** submenu.
4. Deselect the **Preview pane** option.  
![The Preview pane option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/preview-pane-option.jpg)
5. Then try moving or copying your files again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jvwX82j3ci0?si=gAWoovjXgs3m1d7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The layout in Windows 10 File Explorer is a little different. To disable preview panes in that file manager, you’ll need to click the **View** tab. Then click **Preview pane** to deselect that option.

![The View tab in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-view-tab.jpg)

 Note that just disabling the preview pane might not always be enough. If that doesn’t work, try turning off the icon file view. To do so in Windows 11 File Explorer, click **View** and select the **List** or **Details view** option. You can select the same options on the **View** tab in Windows 10 File Explorer.

## 3\. Run a Malware Scan

 If the previous two resolutions don’t work for you, it’s probably the case that malware is causing the “requested resource is in use” error on your PC. SmartService is a trojan known to cause the “required source is in use” error. So, try running an antivirus scan with third-party software or Windows Security to kill SmartService. You can run an antivirus scan with Windows Security like this:

1. Double-click Windows Security’s icon in the system tray (the shield).
2. Click **Virus & threat protection** \> **Scan options** to access the Microsoft Defender antivirus tool.  
![The Scan options navigation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-scan-options.jpg)
3. Select the **Full scan** setting.
4. Click **Scan now** to initiate the malware scanning.  
![The Scan now button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-full-scan-radio-button.jpg)
5. Wait for the scanning to finish and select **Start actions** to remove detected malware.

 If you find Microsoft Defender is disabled and cannot turn it on, that’s a surefire sign the SmartService malware has infected your PC. SmartService is a rootkit trojan that blocks users from utilizing antivirus tools. That malware can also block the installation of some antivirus apps. In this case, the “requested resource in use” error can also occur when you try to run security apps.

 To circumvent such a block, try running a Windows Security or third-party app antivirus scan in safe mode instead. Our guide to [booting into safe mode on Windows](https://www.makeuseof.com/windows-11-boot-safe-mode/) includes a few different methods for entering that troubleshooting mode. Select to enable safe mode with networking.

![windows 11 startup settings safe mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-startup-settings-safe-mode.jpg)

## 4\. Disable Any Unknown Programs in Task Manager

 You might be able to disable a SmartService trojan from starting with Windows via Task Manager’s Startup tab. Look for and disable any suspicious programs listed on the **Startup** tab as follows:

1. Right-click a space on the taskbar to select a **Task Manager** context menu shortcut.
2. Next, click **Startup** to view that tab.
3. Look for any programs you don’t recognize on the **Startup** tab.
4. If you see anything suspicious, select that item and click the **Disable** button.  
![The Disable button on Task Manager's Startup tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-button.jpg)
5. Then restart your PC to see if the issue persists.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aa6vSdt1elM?si=qPhmO-hoWVIPBnnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Uninstall Any Suspicious-Looking Programs

 The SmartService trojan might also be listed within the Programs and Features Control Panel applet for uninstalling software. If you notice suspicious-looking software in Programs and Features, you can also select to uninstall it from there.

 Try uninstalling suspicious programs like this:

1. Bring up the Windows uninstaller tool with a method in our guide to opening Programs and Features.
2. Look through the list of installed software to see if there’s any suspicious-looking program there. Look for a program you can’t recall installing with an unknown publisher title.  
![The Uninstall option in Programs and Features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-uninstall-option4.jpg)
3. Right-click on the suspected SmartService malware and select **Uninstall**.
4. If you can’t uninstall the suspicious software, restart Windows in safe mode. Then try removing the same suspicious item via Programs and Features in safe mode.

 Also, clear temporary data after uninstalling SmartService to ensure the malware can’t re-emerge. To do so, you’ll need to clear out the Temp folder. This article about [deleting temporary files](https://www.makeuseof.com/windows-11-delete-temporary-files/) includes alternative methods for clearing data in the Temp folder.

## 6\. Perform a Factory Reset

 If the “requested resource is in use” error remains unresolved after trying all the potential resolutions above, performing a factory reset is the last resort. A factory reset will remove all programs not pre-installed with Windows and restore your PC to its default configuration. Applying this potential fix will likely eradicate malware causing the “requested resource is in use” error.

 The "Reset this PC" utility lets you factory reset Windows 11 and 10\. That tool includes an option you can select to stop the reset deleting user files. Our [how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) guide provides detailed guidelines for resetting the platform.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-keep-my-files-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zAzTErKy6h8?si=vi5z3M9_7fW6qiAJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Get the “Requested Resource Is in Use” Error Sorted on Windows

 The potential solutions covered here are widely confirmed to resolve the “requested resource is in use” error. If it’s not caused by malware, disabling Explorer’s preview pane, as covered in resolution two, will usually fix the issue. Users confirm running an antivirus scan in safe mode (solution three) can fix the “required resource is in use” error when caused by malware.

 Here is how you can fix the “requested resource is in use” error on a Windows 10 or 11 PC.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-helps.techidaily.com/new-2024-approved-crescendo-to-calmness-premier-asmr-artists/"><u>[New] 2024 Approved Crescendo to Calmness Premier ASMR Artists</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-step-by-step-guide-to-custom-youtube-thumbnail-sizes/"><u>2024 Approved Step-by-Step Guide to Custom YouTube Thumbnail Sizes</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-best-tools-to-hard-reset-oneplus-nord-ce-3-lite-5g-drfone-by-drfone-reset-android-reset-android/"><u>3 Best Tools to Hard Reset OnePlus Nord CE 3 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/4-ways-microsoft-is-replacing-cortana-in-windows/"><u>4 Ways Microsoft Is Replacing Cortana in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/a-peek-into-the-soulful-machine-activating-windows-private-character-analysis-platform/"><u>A Peek Into the Soulful Machine: Activating Windows’ Private Character Analysis Platform</u></a></li>
<li><a href="https://windows11.techidaily.com/a-simple-way-to-inspect-and-erase-window-logs/"><u>A Simple Way to Inspect & Erase Window Logs</u></a></li>
<li><a href="https://windows11.techidaily.com/accessible-windows-for-new-users-and-learners/"><u>Accessible Windows for New Users & Learners</u></a></li>
<li><a href="https://windows11.techidaily.com/apexs-windows-woes-strategies-to-clear-no-server-error-(156-chars/"><u>Apex's Windows Woes: Strategies to Clear No-Server Error (<156 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/cant-insert-new-cells-in-microsoft-excel-for-windows-try-these-fixes/"><u>Can’t Insert New Cells in Microsoft Excel for Windows? Try These Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/curbing-resource-conflicts-on-pcs-running-windows-1011-153-chars/"><u>Curbing Resource Conflicts on PCs Running Windows 10/11 (153 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/diagnosing-and-fixing-microsoft-windows-nearby-share-malfunction/"><u>Diagnosing and Fixing Microsoft Windows Nearby Share Malfunction</u></a></li>
<li><a href="https://windows11.techidaily.com/discovering-new-horizons-for-galaxy-users-on-pc/"><u>Discovering New Horizons for Galaxy Users on PC</u></a></li>
<li><a href="https://win-blog.techidaily.com/experience-seamless-gameplay-permanent-fixes-for-dark-souls-iii-crashing-problems/"><u>Experience Seamless Gameplay - Permanent Fixes for Dark Souls III Crashing Problems</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/fix-broken-jpegs-easily-with-our-expert-recommended-image-repair-software/"><u>Fix Broken JPEGs Easily with Our Expert-Recommended Image Repair Software</u></a></li>
<li><a href="https://vp-tips.techidaily.com/how-abbyy-works-in-harmony-with-automation-anywhere-to-streamline-your-workflow-processes-for-superior-productivity/"><u>How ABBYY Works in Harmony with Automation Anywhere to Streamline Your Workflow Processes for Superior Productivity</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-process-of-screen-sharing-infinix-smart-8-pro-to-pc-detailed-steps-drfone-by-drfone-android/"><u>In 2024, Process of Screen Sharing Infinix Smart 8 Pro to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/samsungs-latest-smartphone-debut-a-comprehensive-overview/"><u>Samsung's Latest Smartphone Debut: A Comprehensive Overview</u></a></li>
<li><a href="https://win-luxury.techidaily.com/step-by-step-tutorial-on-saving-martial-arts-movies-as-mp4-avi-and-mov-files-for-offline-viewing/"><u>Step-by-Step Tutorial on Saving Martial Arts Movies as MP4, AVI & MOV Files for Offline Viewing</u></a></li>
<li><a href="https://fox-that.techidaily.com/struggling-with-wireless-charging-on-your-iphone-find-relief-in-these-7-remedies/"><u>Struggling with Wireless Charging on Your iPhone? Find Relief in These 7 Remedies!</u></a></li>
</ul></div>

