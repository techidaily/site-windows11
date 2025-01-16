---
title: Deciphering Win Errors Post-BSOD on Modern OSes
date: 2025-01-14T12:34:06.948Z
updated: 2025-01-16T07:30:30.386Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Deciphering Win Errors Post-BSOD on Modern OSes
excerpt: This Article Describes Deciphering Win Errors Post-BSOD on Modern OSes
keywords: BSOD Fix Guide,Win Error Solutions,OS Crash Recovery,Windows Diagnostic Tricks,Post-Error Boot Help,System Crash Analysis,Modern OS Blue Screen
thumbnail: https://thmb.techidaily.com/8dc1e121faf37e853cf5b4a2c9e429100f4acf86a44ca231431cd5b1e8fdd239.jpg
---

## Deciphering Win Errors Post-BSOD on Modern OSes

 When your computer crashes and you face a Blue Screen of Death (BSOD), your system saves the details of the crash as a BSOD log, in a pre-defined location in Windows. This information gives you details about when the crash happened, what caused it, and sometimes even what to do to fix the problem.

 In this guide, we will first discuss where are the BSOD files located in Windows and then how to identify them. Once you have located a BSOD file, we will show you how to read it properly to understand the potential causes of the error and resolve the problem.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9sk53d1bBhY?si=yaTeDogLb3D4dYu1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/uSfA74aeYeA?si=HdJSMdeS7HVtS6-j" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Create a custom view in the Event viewer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/create-custom-view.jpg)
3. In the following dialog, expand the dropdown for **Logged** and choose the time when you encountered the issue.  
![Check the logged section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/custom-time.jpg)
4. Now, move to the Event Level section and choose **Error**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3UyJuZYzjt0?si=W87GeyzVKVORAk7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Event level of the error](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/error-event-level.jpg)
5. Expand the dropdown for **Event Logs** and checkmark the box for **Windows Logs**.  
![Choose Windows logs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/windows-logs.jpg)

1. Click **OK** to proceed.
2. You will now be prompted to enter a name and description for the custom view you just created. Enter these details and click **OK**.  
![Create a filter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/name-event-viewer.jpg)
3. Once the view is created, you will be presented with a list of errors that occurred during the time frame you selected earlier. You can sort this information further in the Date and time section.  
![Check the Event Viewer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/event-viewer-11.jpg)
4. Next, locate the BSOD using details like the date and time again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YpnYKIrpgZQ?si=94zicAHp1CH-0oso" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
8. Under Value data, type 1 and click **OK**.  
![Change the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/value-data-1.jpg)
9. Once done, restart your PC.

 Upon reboot, you should be able to view the log files without any problems.

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fZTlPdOFNmo?si=Ym8p7ayV1gtNzzXj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Reliability graph](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/realability-graph.jpg)
5. Click on each of the icons to view its details. Keep repeating the process to locate the event you are looking for.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bXmwwSmYqq4?si=Bb-eJfLnlpeeClyt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You will be presented with information like the faulting application path, its name, fault module timestamp, exception code, etc. If this app caused a BSOD crash, then you can try ending its process via the Task Manager or uninstalling the app if it is not necessary.

 It is also a good idea to copy this information and send it to Microsoft for review if you cannot find a solution online.

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
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-best-in-class-top-drone-gimbals-compared/"><u>[New] 2024 Approved Best in Class Top Drone Gimbals Compared</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-simplified-guide-to-google-meet-on-youtube-broadcasting/"><u>2024 Approved Simplified Guide to Google Meet on YouTube Broadcasting</u></a></li>
<li><a href="https://blog-min.techidaily.com/acces-illimite-a-votre-collection-dvd-sans-frais-avec-notre-plus-puissant-logiciel-decodeur/"><u>Accès Illimité À Votre Collection DVD Sans Frais Avec Notre Plus Puissant Logiciel Décodeur</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/decoding-toolwizs-capabilities-in-mobile-photo-editing/"><u>Decoding Toolwiz's Capabilities in Mobile Photo Editing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expand-your-windows-11-pinned-apps-area/"><u>Expand Your Windows 11 Pinned Apps Area</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-overwatch-error-the-mystery-of-the-disappearing-rendering-device-explained/"><u>Fix Overwatch Error: The Mystery of the Disappearing Rendering Device Explained</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-reset-gmail-password-on-tecno-spark-10-5g-devices-by-drfone-android/"><u>How to Reset Gmail Password on Tecno Spark 10 5G Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-start-w11s-on-demand-repair-service/"><u>How to Start W11’s On-Demand Repair Service</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-erased-typing-on-windows-systems/"><u>Mending Erased Typing on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-0x80072af9-error-in-windows-os/"><u>Overcoming 0X80072AF9 Error in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-reduce-cpu-and-ram-overuse-from-unrealcefsubprocess-on-pcs/"><u>Strategies to Reduce CPU and RAM Overuse From UnrealCEFSubprocess on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-fixes-for-eliminating-windows-error-code-0xc00000f/"><u>Swift Fixes for Eliminating Windows Error Code: 0Xc00000f</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-winstore-problems-effective-fix-for-0x80072f17/"><u>Tackling WinStore Problems: Effective Fix for 0X80072f17</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/top-rated-halo-bolt-jump-starter-and-portable-charger-expert-review/"><u>Top Rated Halo Bolt Jump Starter & Portable Charger - Expert Review</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-of-edges-additional-taskers/"><u>Unraveling the Mystery of Edge's Additional Taskers</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-windows-10-and-11s-isdonedll-dilemmrances/"><u>Unraveling Windows 10 & 11'S ISDone.dll Dilemmrances</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/updated-maximizing-yandex-translate-in-video-translation-and-beyond-for-2024/"><u>Updated Maximizing Yandex Translate in Video Translation and Beyond for 2024</u></a></li>
</ul></div>

