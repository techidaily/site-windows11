---
title: Tackling the Busy Resource Issue in Windows Environments (153 Chars)
date: 2025-01-28T00:24:35.223Z
updated: 2025-01-29T17:10:41.172Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling the Busy Resource Issue in Windows Environments (153 Chars)
excerpt: This Article Describes Tackling the Busy Resource Issue in Windows Environments (153 Chars)
keywords: WinResourceBusySolution,WindowsEfficiencyBoost,FastWindowsResources,EfficientWinResourceUse,ReduceWindowLatency,OptimizeWinPerformance,MinimizeWindowsIdleTime
thumbnail: https://thmb.techidaily.com/97bffd7aabaab6ce88cfb81baf09f210aa957590abbc17524d40c38c29898fc2.jpg
---

## Tackling the Busy Resource Issue in Windows Environments (153 Chars)

 Users have reported “the requested resource in use” error message pops up on their PCs when trying to copy or move files from mobile devices to their Windows PCs. That error message’s heading also says, “error copying file or folder.” As a result, users can’t copy the files they need to.

 Here is how you can fix the “requested resource is in use” error on a Windows 10 or 11 PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Check if the File Is Already in Use

![The End task option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-end-task-option.jpg)

 The “requested resource is in use” error message hints that the file (resource) you’re trying to copy is already in use. Thus, the copy operation cannot be completed because something else is using the file or folder. So, you might need to close some background processes to address this issue.

 First, move your mouse’s cursor over the File Explorer taskbar icon to see if there are any windows for active file operations. Cancel any active file operations you see. Then try copying the file again.

 If that doesn’t work, go into Task Manager and close superfluous third-party app background processes. Our guide to [fixing too many background processes on Windows](https://www.makeuseof.com/windows-pc-too-many-background-processes/) provides further instructions for how you can do that.

## 2\. Disable File Explorer’s Preview Pane

 Many users have fixed the “requested resource is in use” error by disabling File Explorer’s preview pane. That preview pane can hinder the file copy operation. You can disable File Explorer’s preview pane in Windows 11 as follows:

1. Press the **Win + E** key combination to launch File Explorer.
2. Then click the **View** menu button.
3. Select the **Show** submenu.
4. Deselect the **Preview pane** option.  
![The Preview pane option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/preview-pane-option.jpg)
5. Then try moving or copying your files again.

 The layout in Windows 10 File Explorer is a little different. To disable preview panes in that file manager, you’ll need to click the **View** tab. Then click **Preview pane** to deselect that option.

![The View tab in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-view-tab.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8Y-k_3N-0OI?si=1J-aFBXLJl5b3x4h" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Note that just disabling the preview pane might not always be enough. If that doesn’t work, try turning off the icon file view. To do so in Windows 11 File Explorer, click **View** and select the **List** or **Details view** option. You can select the same options on the **View** tab in Windows 10 File Explorer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6kzbT13ds3M?si=hBInu0Or-cX2ANJF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Run a Malware Scan

 If the previous two resolutions don’t work for you, it’s probably the case that malware is causing the “requested resource is in use” error on your PC. SmartService is a trojan known to cause the “required source is in use” error. So, try running an antivirus scan with third-party software or Windows Security to kill SmartService. You can run an antivirus scan with Windows Security like this:

1. Double-click Windows Security’s icon in the system tray (the shield).
2. Click **Virus & threat protection** \> **Scan options** to access the Microsoft Defender antivirus tool.  
![The Scan options navigation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-scan-options.jpg)
3. Select the **Full scan** setting.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Lp78eFEGwVU?si=-4orJBLvJJrggCJ2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/odDOPrPjRYY?si=7QHzdUkTPNkHJiVj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Uninstall Any Suspicious-Looking Programs

 The SmartService trojan might also be listed within the Programs and Features Control Panel applet for uninstalling software. If you notice suspicious-looking software in Programs and Features, you can also select to uninstall it from there.

 Try uninstalling suspicious programs like this:

1. Bring up the Windows uninstaller tool with a method in our guide to opening Programs and Features.
2. Look through the list of installed software to see if there’s any suspicious-looking program there. Look for a program you can’t recall installing with an unknown publisher title.  
![The Uninstall option in Programs and Features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-uninstall-option4.jpg)
3. Right-click on the suspected SmartService malware and select **Uninstall**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LT4sdZgUvRQ?si=SvQD5FouEzu4UHpJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. If you can’t uninstall the suspicious software, restart Windows in safe mode. Then try removing the same suspicious item via Programs and Features in safe mode.

 Also, clear temporary data after uninstalling SmartService to ensure the malware can’t re-emerge. To do so, you’ll need to clear out the Temp folder. This article about [deleting temporary files](https://www.makeuseof.com/windows-11-delete-temporary-files/) includes alternative methods for clearing data in the Temp folder.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6X24fPKs6AE?si=YtQy-8zy7GifgfA7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Perform a Factory Reset

 If the “requested resource is in use” error remains unresolved after trying all the potential resolutions above, performing a factory reset is the last resort. A factory reset will remove all programs not pre-installed with Windows and restore your PC to its default configuration. Applying this potential fix will likely eradicate malware causing the “requested resource is in use” error.

 The "Reset this PC" utility lets you factory reset Windows 11 and 10\. That tool includes an option you can select to stop the reset deleting user files. Our [how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) guide provides detailed guidelines for resetting the platform.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-keep-my-files-option.jpg)

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
<li><a href="https://fox-info.techidaily.com/new-deconstructing-magix-photo-and-video-tools/"><u>[New] Deconstructing MAGIX Photo & Video Tools</u></a></li>
<li><a href="https://article-files.techidaily.com/new-the-ultimate-roadmap-to-crafting-high-quality-srt-files/"><u>[New] The Ultimate Roadmap to Crafting High-Quality SRT Files</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-peak-level-hd-mastery-in-the-markets-top-recorders/"><u>[Updated] In 2024, Peak-Level HD Mastery in the Market's Top Recorders</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-streamline-video-shoot-excellent-camera-tripods-reviewed-for-2024/"><u>[Updated] Streamline Video Shoot Excellent Camera Tripods Reviewed for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-ultra-30-action-camera-by-garmin-detailed-reviews-and-features/"><u>[Updated] Ultra 30 Action Camera by Garmin – Detailed Reviews & Features</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/approved-captivating-crafting-writing-intriguing-youtube-descriptions-with-templates/"><u>2024 Approved Captivating Crafting Writing Intriguing Youtube Descriptions with Templates</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-cinema-in-editing-10-snippet-selections/"><u>2024 Approved Cinema in Editing 10 Snippet Selections</u></a></li>
<li><a href="https://win-top.techidaily.com/destination-of-deleted-data-understanding-what-occurs-when-you-clear-your-recycle-bin/"><u>Destination of Deleted Data: Understanding What Occurs When You Clear Your Recycle Bin</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-defrag-a-hard-disk-drive-in-windows-11/"><u>How to Defrag a Hard Disk Drive in Windows 11</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-watch-fubotv-channels-using-an-amazon-fire-stick-ultimate-tutorial/"><u>How to Watch FuboTV Channels Using an Amazon Fire Stick - Ultimate Tutorial</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-reset-a-lava-blaze-pro-5g-phone-that-is-locked-by-drfone-android/"><u>In 2024, How to Reset a Lava Blaze Pro 5G Phone that is Locked?</u></a></li>
<li><a href="https://windows11.techidaily.com/master-organization-to-do-and-ifttt-alliance/"><u>Master Organization: To-Do & IFTTT Alliance</u></a></li>
<li><a href="https://windows11.techidaily.com/master-time-management-pick-from-these-5-best-windows-clock-screen-saver-apps/"><u>Master Time Management: Pick From These 5 Best Windows Clock Screen Saver Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-resolving-windows-errors-in-windows-11/"><u>Mastering the Art of Resolving Windows Errors in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/personalize-your-keyboard-use-with-winos-commands/"><u>Personalize Your Keyboard Use with WinOS Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/preserving-default-time-on-windows-pcs/"><u>Preserving Default Time on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-break-windows-stealthy-cam-policy/"><u>Techniques to Break Window's Stealthy Cam Policy</u></a></li>
<li><a href="https://windows11.techidaily.com/transforming-black-desktop-backgrounds-on-pcs/"><u>Transforming Black Desktop Backgrounds on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/win-rpc-problems-here-are-5-fixes-you-need/"><u>Win RPC Problems? Here Are 5 Fixes You Need!</u></a></li>
</ul></div>

