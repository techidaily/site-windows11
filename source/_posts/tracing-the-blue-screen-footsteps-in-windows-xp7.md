---
title: Tracing the Blue Screen Footsteps in Windows XP/7
date: 2024-12-06T20:30:50.192Z
updated: 2024-12-10T17:19:19.237Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tracing the Blue Screen Footsteps in Windows XP/7
excerpt: This Article Describes Tracing the Blue Screen Footsteps in Windows XP/7
keywords: WinXP BlueScreen Fix,WinXP Crash Diagnostics,Win7 BlueScreen Troubleshoot,Debugging BlueScreen XPS,XP/Win7 Error Analysis,Windows BlueScreen Guide,System Breakpoint Solutions
thumbnail: https://thmb.techidaily.com/06e60fe3d947d58be6e231820ad1f116434db798e239b52d730db0c4a5927ced.jpg
---

## Tracing the Blue Screen Footsteps in Windows XP/7

 When your computer crashes and you face a Blue Screen of Death (BSOD), your system saves the details of the crash as a BSOD log, in a pre-defined location in Windows. This information gives you details about when the crash happened, what caused it, and sometimes even what to do to fix the problem.

 In this guide, we will first discuss where are the BSOD files located in Windows and then how to identify them. Once you have located a BSOD file, we will show you how to read it properly to understand the potential causes of the error and resolve the problem.

## Where Are the BSOD Log Files Located in Windows?

 You can find the BSOD log files in the Event Viewer, Control Panel, and Registry Editor in Windows. Below, we have listed the detailed steps for finding these files in all three of these utilities.

### 1\. Find and Read the BSOD Log Files in the Event Viewer

 The Event Viewer is a tool developed by Microsoft for users to view system and program-related events in Windows. These events can include system errors, warnings, informational messages, and more. In other words, every issue you encounter (whether a minor glitch or a major crash) will be logged in the Event Viewer for later investigation and sharing with Microsoft.

 You can check out our detailed guide on [what the Event Viewer is and how it can be useful](https://www.makeuseof.com/windows-event-viewer-guide/) if you are unfamiliar with it.

 Here is how you can find the BSOD log files in the Event Viewer:

1. Right-click on the Windows icon in the taskbar and choose **Event Viewer** from the context menu.  
![Choose Event Viewer in the context menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/event-viewer.jpg)
2. Head over to the **Action** menu located at the top, and choose **Create Custom View** from the context menu.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jnITUsxMz5s?si=ohwRVH6eWhVnC6Xf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Create a custom view in the Event viewer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/create-custom-view.jpg)
3. In the following dialog, expand the dropdown for **Logged** and choose the time when you encountered the issue.  
![Check the logged section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/custom-time.jpg)
4. Now, move to the Event Level section and choose **Error**.  
![Event level of the error](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/error-event-level.jpg)
5. Expand the dropdown for **Event Logs** and checkmark the box for **Windows Logs**.  
![Choose Windows logs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/windows-logs.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nlwr9LjJ-ng?si=I6UNAtfBkY2FTceu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Click **OK** to proceed.
2. You will now be prompted to enter a name and description for the custom view you just created. Enter these details and click **OK**.  
![Create a filter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/name-event-viewer.jpg)
3. Once the view is created, you will be presented with a list of errors that occurred during the time frame you selected earlier. You can sort this information further in the Date and time section.  
![Check the Event Viewer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/event-viewer-11.jpg)
4. Next, locate the BSOD using details like the date and time again.
5. Once you find the targeted log, click on it.
6. Check both the General and Details tabs to get information about this error.

 Once you find the error code associated with the crash and the cause, you can look for solutions online, or head over to our guide that discusses [how to fix blue screen errors in Windows](https://www.makeuseof.com/tag/4-tips-fix-blue-screen-error/) if it's a bsod.

### 2\. Find and Read the BSOD Log Files in the Registry Editor

 In case using the Event Viewer does not work for you for some reason, you can use another Windows utility to locate and study the BSOD log files—the Registry Editor.

 Windows Registry Editor is an administrative-level utility that lets you control how Windows operates and interacts with hardware and software. The Registry stores information related to the hardware and software components of your system. This information in the Registry is stored in the form of keys and values, and by modifying these with the dedicated Registry Editor, you can customize the operations of your system.

 Listed below are the steps for finding the BSOD log files in the Registry Editor. Make sure you are logged into your system as an administrator before you proceed.

1. Press the **Win + R** keys to open Run.
2. Type "regedit" in Run and press **Ctrl + Shift + Enter** to launch the Registry Editor as an administrator.
3. Now, select **Yes** in the User Account Prompt.
4. Once you are inside the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\System\CurrentControlSet\Control\CrashControl`
5. Next, move to the right pane and right-click on an empty space anywhere.
6. Choose **New** \> **DWORD (32-bit) Value**.  
![Create a new DWORD value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/dword-policies.jpg)
7. Name this value as **DisplayParameters** and double-click on it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4DJKH1uY7P0?si=tCG66XVlbwSKoATj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

8. Under Value data, type 1 and click **OK**.  
![Change the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/value-data-1.jpg)
9. Once done, restart your PC.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SyMZxS9479s?si=0T6zZpyN2LBftFTM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Upon reboot, you should be able to view the log files without any problems.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UoBCgLTmznE?si=MXXiGsd2qpd_DrzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 3\. Find and Read the BSOD Log Files in the Control Panel

 The third way of finding and reading the BSOD log files is via the Control Panel. This approach offers a graphical representation of the log files using the Windows Reliability Monitor, unlike the methods we have explored previously.

 The Reliability Monitor, which is different than the Performance Monitor (see [Reliability Monitor vs. Performance Monitor](https://www.makeuseof.com/reliability-monitor-vs-performance-monitor/)) will show you a timeline of important system events that occurred on your computer including BSOD occurrences, software installations, application crashes, and other relevant events.

 Here is how you can use it to identify and fix problems that may affect your system:

1. Type Control Panel in the search area of the taskbar and click **Open**.
2. In the following window, choose **System and Security** \> **Security and Maintenance**.  
![Security and maintenance settings in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/security-maintenance.jpg)
3. Click on **Maintenance** and then select **View reliability history**.  
![Check the reliability history of the system](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/view-realability-history.jpg)
4. You should now see a graph showing the reliability data. Look for red cross icons and blue (i) icons in the graph, as they show problematic events.  
![Reliability graph](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/realability-graph.jpg)
5. Click on each of the icons to view its details. Keep repeating the process to locate the event you are looking for.

 You will be presented with information like the faulting application path, its name, fault module timestamp, exception code, etc. If this app caused a BSOD crash, then you can try ending its process via the Task Manager or uninstalling the app if it is not necessary.

 It is also a good idea to copy this information and send it to Microsoft for review if you cannot find a solution online.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LI9nKlbhnw8?si=uUXFVbuEqXtFHHv0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Learn How to Read Your BSOD Log Files and Resolve Your Crashes

 ​​​​​​Windows blue screen errors are nothing new, but since they only display messages like "Your PC encountered a problem" without describing the cause, it can be difficult to find a fix. Understanding how to read BSOD log files can not only help you identify the exact cause of the problem but also help you find the right solution.

 Whenever a component causes your system to crash, you can disable it and switch to a better alternative to avoid the problem.

 In this guide, we will first discuss where are the BSOD files located in Windows and then how to identify them. Once you have located a BSOD file, we will show you how to read it properly to understand the potential causes of the error and resolve the problem.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://eaxpv-info.techidaily.com/new-harnessing-youtubes-true-potential-in-studio-for-2024/"><u>[New] Harnessing YouTube's True Potential in Studio for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-in-2024-the-50-must-try-virtual-bikes-for-riders/"><u>[New] In 2024, The 50 Must-Try Virtual Bikes for Riders</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-discovering-and-developing-your-personalized-mukbang-style-for-2024/"><u>[Updated] Discovering and Developing Your Personalized Mukbang Style for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-from-ground-up-a-complete-evaluation-of-dji-phantom-4/"><u>2024 Approved From Ground Up A Complete Evaluation of DJI Phantom 4</u></a></li>
<li><a href="https://win-able.techidaily.com/addressing-dota-2s-latest-vac-error-effective-strategies-for-account-revival/"><u>Addressing Dota 2'S Latest VAC Error: Effective Strategies for Account Revival</u></a></li>
<li><a href="https://tech-haven.techidaily.com/ballads-battlefield-poetic-giants-versus-gpt-shepherds-wooly-kinfolk/"><u>Ballads' Battlefield - Poetic Giants Versus GPT Shepherds, Wooly Kinfolk</u></a></li>
<li><a href="https://techidaily.com/beginners-guide-to-wiping-clean-and-refreshing-your-hp-laptop-the-complete-factory-reset-method/"><u>Beginner's Guide to Wiping Clean and Refreshing Your HP Laptop - The Complete Factory Reset Method</u></a></li>
<li><a href="https://fake-location.techidaily.com/dose-life360-notify-me-when-someone-checks-my-location-on-realme-gt-5-drfone-by-drfone-virtual-android/"><u>Dose Life360 Notify Me When Someone Checks My Location On Realme GT 5? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/hidden-impact-unassuming-apps-draining-windows-11-power/"><u>Hidden Impact: Unassuming Apps Draining Windows 11 Power</u></a></li>
<li><a href="https://windows11.techidaily.com/managing-alerts-when-your-pcs-webcam-activates/"><u>Managing Alerts When Your PC's WebCam Activates</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-fixing-xbox-game-pass-issue-0x00000001-on-windows-11/"><u>Mastering the Art of Fixing Xbox Game Pass Issue 0X00000001 on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-top-complaints-in-windows-11-review/"><u>Navigating Through Top Complaints in Windows 11 Review</u></a></li>
<li><a href="https://blog-min.techidaily.com/official-winx-hd-media-transcoder-for-macos-seamlessly-convert-avchdmkvmov-to-mp4-videos/"><u>Official WinX HD Media Transcoder for macOS - Seamlessly Convert AVCHD/MKV/MOV to MP4 Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/optimal-performance-with-new-amd-drivers-windows-11-edition/"><u>Optimal Performance with New AMD Drivers: Windows 11 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-ownership-challenges-with-managed-windows-11-features/"><u>Solving Ownership Challenges with Managed Windows 11 Features</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-too-many-requests-in-win-based-software/"><u>Troubleshooting Too Many Requests in Win-Based Software</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-win11-the-google-play-setup/"><u>Unveiling Win11: The Google Play Setup</u></a></li>
</ul></div>

