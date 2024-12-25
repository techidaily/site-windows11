---
title: Regaining Run Window's Past Execution
date: 2024-12-23T19:03:33.982Z
updated: 2024-12-25T16:38:22.102Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Regaining Run Window's Past Execution
excerpt: This Article Describes Regaining Run Window's Past Execution
keywords: WinRunBackup,RestoreWinExecution,RegainRunPast,RecoverWindowRun,RewindWindowsRun,ReinstateRunHistory,FixRunTimeError
thumbnail: https://thmb.techidaily.com/7463aefc3bf7373e7e8450adfdbb24d271ecbb972a6b7c25ccc1795bc56f580e.jpg
---

## Regaining Run Window's Past Execution

 The Run command dialog box in Windows makes it easy to launch apps, access system tools, and perform various other tasks. It also has an auto-complete feature that makes it easy to re-use your commands later. However, the auto-complete feature in the Run tool may not work if it fails to save your command history in the first place.

 If you're encountering a similar problem, don’t fret. Below, we share some quick and useful tips that should get the Run tool to save your history once again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aYH0B2HqcIM?si=3fkoG85L6hAeB4ok" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Check Your Privacy Settings

 A common reason why Windows may not save the Run command history is if you have previously blocked it from tracking your app launches. Here’s how you can change that.

1. Press **Win + I** to open the Settings app.
2. Select **Privacy & security** from the left sidebar.
3. Under Windows permissions, click on **General**.
4. Enable the toggle next to **Let Windows improve Start and search results by tracking app launches**.  
![Allow Windows to Track App Launches on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-windows-to-track-app-launches-on-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jpdGEJJwMLY?si=eKgXOPpNeYvYKcel" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After completing the above steps, try running a few commands via the Run dialog box. Then, check if it is saving your command history and providing auto-complete suggestions.

## 2\. Edit Registry Files

 Is the **Let Windows improve Start and search results by tracking app launches** option grayed out on your PC? If so, you can take help from the Registry Editor to get Windows to save your Run command history.

 As you may already be aware, registry files on your PC store essential settings for Windows and its services. Making incorrect modifications to these files can render your system inoperable. Hence, it’s a good idea to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

1. Click the search icon on the taskbar or press the **Win + S** keyboard shortcut to open the search menu.
2. Type **registry editor** in the search box and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_CURRENT\_USER > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer > Advanced**.
5. Locate the **Start\_TrackProgs** entry in the right pane. If you can’t find it, right-click on the **Advanced** key and select **New > DWORD (32-bit) Value**. Rename it to **Start\_TrackProgs**.
6. Double-click the newly created DWORD and enter **1** in the **Value data** field.
7. Click **OK**.  
![Edit Registry DWORD on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/edit-registry-dword-on-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/r_wWybMqZEM?si=0nPjCQDLS2MCaQbG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Restart your PC after this for the changes to take effect. Following this, the Run command should start saving your history on Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8Y-k_3N-0OI?si=1J-aFBXLJl5b3x4h" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Apply Generic Fixes

 If the problem persists even after implementing the above tips, you can try applying some basic fixes to resolve the underlying issue.

* **Restart Your PC:** This may appear rudimentary, but temporary OS-related glitches can sometimes cause such anomalies. If it’s nothing major, [restarting your PC](https://www.makeuseof.com/windows-restart-methods/) should fix any issues with the Run command.
* **Run an SFC Scan:** Such issues can also arise if some of the critical system files on your PC are corrupt. [Running a System File Checker (SFC) scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) can help detect and repair any damaged system files on your PC.
* **Scan for Malware:** It’s possible that your system is infected by malware, which is why the Run command is having trouble saving your history. To rule out this possibility, you can [scan Windows for malware using PowerShell](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/) or Windows Defender.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cKRBWf1EDZo?si=CTNd4q450biit4eM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Get the Run Tool to Save Your History on Windows

 It can be inconvenient if the Run command dialog box stops saving your history on Windows. Hopefully, one of the solutions provided above has successfully resolved the issue for you.

 If you feel that the Run utility in Windows lacks advanced features, you can always switch to alternative tools like Run-Command or PowerToys Run.

 If you're encountering a similar problem, don’t fret. Below, we share some quick and useful tips that should get the Run tool to save your history once again.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-helps.techidaily.com/new-design-memes-in-adobe/"><u>[New] Design Memes in Adobe</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722963875713-download-the-fast-track-validity-fps-driver-secure-your-systems-now/"><u>Download the Fast-Track Validity FPS Driver - Secure Your Systems Now</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-prolong-windows-10-restart-time-while-tasks-run/"><u>How to Prolong Windows 10 Restart Time While Tasks Run</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-secrets-revealed-flawless-and-straightforward-ipad-screen-recording/"><u>In 2024, Secrets Revealed Flawless and Straightforward iPad Screen Recording</u></a></li>
<li><a href="https://windows11.techidaily.com/instant-admin-access-to-command-prompt-in-windows/"><u>Instant Admin Access to Command Prompt in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/maximize-graphics-performance-with-1-6-tools-for-windows-pcs/"><u>Maximize Graphics Performance with #1-#6 Tools for Windows PCs</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-high-tech-purchases-insights-from-toms-hardware-expertise/"><u>Navigating High-Tech Purchases: Insights From Tom's Hardware Expertise</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-remote-desktop-windows-problems/"><u>Navigating Through Remote Desktop Windows Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/seamlessly-navigate-anywhere-the-art-of-cross-border-mouse-usage/"><u>Seamlessly Navigate Anywhere - The Art of Cross-Border Mouse Usage</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/tcl-32s325-roku-smart-led-tv-2019-review-brains-without-the-brawn/"><u>TCL 32S325 Roku Smart LED TV (2019) Review: Brains Without the Brawn</u></a></li>
<li><a href="https://fox-tls.techidaily.com/top-video-recording-tools-effective-substitutes-for-camtasia/"><u>Top Video Recording Tools: Effective Substitutes for Camtasia</u></a></li>
<li><a href="https://windows11.techidaily.com/turning-classic-computers-into-modern-windows-11-hubs-with-tools/"><u>Turning Classic Computers Into Modern Windows 11 Hubs with Tools</u></a></li>
<li><a href="https://win-remarkable.techidaily.com/user-management-via-windows-control-panel-tips-and-tricks-from-yl-computing/"><u>User Management via Windows Control Panel: Tips & Tricks From YL Computing</u></a></li>
</ul></div>

