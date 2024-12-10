---
title: How to Plain Out Windows Edges
date: 2024-12-09T17:49:35.855Z
updated: 2024-12-10T19:17:27.638Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Plain Out Windows Edges
excerpt: This Article Describes How to Plain Out Windows Edges
keywords: Edge Removal Guide,Window Cleaning Tips,Clear Windows Trim,Edging Free Windows,Remove Window Rims,Easy Window Frame,Pure Window Look
thumbnail: https://thmb.techidaily.com/db345622b66c3b6984b775950925cc8114e2a134a67c761a2d6a6d2fb5b65330.jpg
---

## How to Plain Out Windows Edges

 With Windows 11, Microsoft brought several visual changes to its desktop operating system, including the notable addition of rounded corners for windows, menus, and dialog boxes. While the new design update has been widely embraced by many users, there are those who prefer a more traditional look with sharp corners.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

## 1\. How to Disable Rounded Corners in Windows 11 Using a Third-Party Tool

**Win11DisableOrRestoreRoundedCorners** is an open-source tool available on GitHub that can help you disable rounded corners on your Windows 11 PC. Since this tool modifies your PC's system files to remove the rounded corners, it's a good idea to [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before using it.

1. Head over to GitHub’s website to [download the Win11DisableOrRestoreRoundedCorners tool](https://github.com/valinet/Win11DisableRoundedCorners/releases).
2. Double-click the downloaded executable file to run it.
3. If you see the Microsoft Defender SmartScreen window, click on **More info** and then select **Run anyway**.
4. Select **Yes** when the User Account Control (UAC) prompt appears.  
![Microsoft Defender SmartScreen Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/microsoft-defender-smartscreen-window.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X4q6gyaEojM?si=ImdFm6Zsr0azykqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you complete the above steps, a PowerShell window should appear and disable rounded corners on your PC. Here’s a glimpse of how your windows will look once the rounded corners are disabled.

![Square Corners in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/square-corners-in-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jpdGEJJwMLY?si=eKgXOPpNeYvYKcel" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Note that this tool will not disable rounded corners in the Start menu or some modern apps. If you want to revert the changes later, simply run the downloaded EXE file again.

## 2\. How to Disable Rounded Corners in Windows 11 Using the Registry Editor

 Don't want to use a third-party tool? No problem. You can also disable rounded corners in Windows 11 by making changes to the Windows Registry. However, it's crucial to exercise caution, as modifying registry files without proper knowledge can be risky.

 Before you proceed, consider [backing up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/), just in case. After that, use these steps to disable rounded corners via the Registry Editor:

1. Press **Win + S** to open the search menu.
2. Type in **registry editor** and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Navigate to **Computer > HKEY\_CURRENT\_USER > Software > Microsoft > Windows > DWM**.
5. Right-click on the **DWM** key and select **New > DWORD (32-bit) Value**. Rename it to **UseWindowFrameStagingBuffer**.
6. Double-click the newly created DWORD and enter **0** in the **Value data** field. Then, click **OK**.
7. [Restart your PC](https://www.makeuseof.com/windows-restart-methods/) to apply the changes.  
![Disable Rounded Corners in Windows 11 via Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-rounded-corners-in-windows-11-via-registry-editor.jpg)

 If you want to reverse the above change later, repeat the same steps mentioned earlier and change the value data for the **UseWindowFrameStagingBuffer** to **1**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aRMCbJxLuwE?si=E5sfJvoqkv1qCMWz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. How to Disable Rounded Corners in Windows 11 via Device Manager

 Another way to remove rounded corners in Windows 11 is by disabling the graphics driver on your PC. However, it is important to consider a few caveats. Firstly, disabling the graphics driver will result in reduced display performance, lower screen resolutions, and the deactivation of any visual effects. Secondly, this will also prevent you from running any graphics-intensive applications or games on your PC.

 If you are fine with these trade-offs, use these steps to disable rounded corners via Device Manager.

1. Press **Win + X** to open the Power User menu.
2. Select **Device Manager** from the list.
3. Double-click on **Display adapters** to expand it.
4. Right-click on your display driver and select **Disable device**.  
![Disable Graphics Driver on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-graphics-driver-on-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/P6Wfzj6YNDM?si=WRZQD9zCdQ1_tW1b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once the graphics driver is disabled, you should see square corners on all windows and menus in Windows 11\. If you want to undo this change later, simply enable the graphics driver via Device Manager.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GU08CQVsZz0?si=V-SvPfzRsQysMS0e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Disabling Rounded Corners in Windows 11 Is Easy

 Using a third-party tool is arguably the most convenient way to remove rounded corners in Windows 11\. However, if you prefer to rely on the native methods, you can use the Registry Editor or Device Manager instead.

 Disabling rounded corners isn’t the only way to get the classic look of previous Windows versions. You can also use a third-party tool like the ExplorerPatcher to make Windows 11 look like Windows 10\.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-the-1000-club-achievement-monthly-tips-for-insta-success-and-growth/"><u>[New] 2024 Approved The 1,000 Club Achievement Monthly Tips for Insta Success and Growth</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-2024-approved-ultimate-hd-encoding-devices-for-live-events/"><u>[Updated] 2024 Approved Ultimate HD Encoding Devices for Live Events</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-maximizing-conversions-with-targeted-snapad-strategies/"><u>[Updated] Maximizing Conversions with Targeted SnapAd Strategies</u></a></li>
<li><a href="https://win-able.techidaily.com/5pel5pys6kqe5a2x5bmv5luy44gn44gu5lq65rcx5lit5zu944oq44kk44kq44os44oz44k544ot44oe44oz44cc5qw944gx44gp5qw944gx44ka44gf44kb44gu44ks44kk44oj/"><u>日本語字幕付きの人気中国バイオレンスロマン〜楽しく楽しむためのガイド</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-adjusting-low-power-modes-in-windows/"><u>Essential Tips: Adjusting Low-Power Modes in Windows</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exclusive-feature-rollout-microsoft-enables-windows-compatibility-with-chromebooks-and-macs-for-eligible-users/"><u>Exclusive Feature Rollout: Microsoft Enables Windows Compatibility with Chromebooks & Macs for Eligible Users</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-changeadd-location-filters-on-snapchat-for-your-honor-90-drfone-by-drfone-virtual-android/"><u>How to Change/Add Location Filters on Snapchat For your Honor 90 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-downloads-weighing-choco-against-wm/"><u>Mastering Windows Downloads: Weighing Choco Against WM</u></a></li>
<li><a href="https://windows11.techidaily.com/reverse-webp-images-in-chrome-for-windows-users/"><u>Reverse WebP Images in Chrome for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-deadlocked-files-on-windows-11-a-guide-1/"><u>Reviving Deadlocked Files on Windows 11: A Guide (1)</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-ultimate-quick-route-from-srt-to-text-txt-files-for-2024/"><u>The Ultimate, Quick Route From SRT to Text (TXT) Files for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unclutter-your-windows-desktop-space/"><u>Unclutter Your Windows Desktop Space</u></a></li>
<li><a href="https://windows11.techidaily.com/update-mail-and-calendars-style-them-with-fav-photos/"><u>Update Mail & Calendars: Style Them with Fav Photos</u></a></li>
<li><a href="https://driver-download.techidaily.com/update-to-newest-rtx-nvidia-gaming-performance-enhancing-drivers-windows-11-ready/"><u>Update to Newest RTX Nvidia Gaming Performance Enhancing Drivers - Windows 11 Ready!</u></a></li>
<li><a href="https://tech-revival.techidaily.com/windows-11winx-dvd-mp4-dvd/"><u>Windows 11用フリーのWinX DVD からMP4への高速コンバータ -簡単なDVD変換ツール</u></a></li>
<li><a href="https://windows11.techidaily.com/your-route-to-a-maps-integrated-windows-experience/"><u>Your Route to a Maps-Integrated Windows Experience</u></a></li>
</ul></div>

