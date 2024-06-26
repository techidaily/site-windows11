---
title: Facing Down Rounded Corners in Windows 11
date: 2024-06-25T12:23:04.510Z
updated: 2024-06-26T12:23:04.510Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Facing Down Rounded Corners in Windows 11
excerpt: This Article Describes Facing Down Rounded Corners in Windows 11
keywords: Windows Round-Edge Removal,Edge Trim in Win11,Win11 Angle Adjustment,Decorative Window Edges,Cornerless Windows 11,Eliminate Rounded Corners,Smoothed Windows Interface
thumbnail: https://thmb.techidaily.com/4d8389239c924325f747de29a6fa5fd56f085170de1cb456669c5929df51dc2a.jpg
---

## Facing Down Rounded Corners in Windows 11

 With Windows 11, Microsoft brought several visual changes to its desktop operating system, including the notable addition of rounded corners for windows, menus, and dialog boxes. While the new design update has been widely embraced by many users, there are those who prefer a more traditional look with sharp corners.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

## 1\. How to Disable Rounded Corners in Windows 11 Using a Third-Party Tool

**Win11DisableOrRestoreRoundedCorners** is an open-source tool available on GitHub that can help you disable rounded corners on your Windows 11 PC. Since this tool modifies your PC's system files to remove the rounded corners, it's a good idea to [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before using it.

1. Head over to GitHub’s website to [download the Win11DisableOrRestoreRoundedCorners tool](https://github.com/valinet/Win11DisableRoundedCorners/releases).
2. Double-click the downloaded executable file to run it.
3. If you see the Microsoft Defender SmartScreen window, click on **More info** and then select **Run anyway**.
4. Select **Yes** when the User Account Control (UAC) prompt appears.  
![Microsoft Defender SmartScreen Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/microsoft-defender-smartscreen-window.jpg)

 Once you complete the above steps, a PowerShell window should appear and disable rounded corners on your PC. Here’s a glimpse of how your windows will look once the rounded corners are disabled.

![Square Corners in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/square-corners-in-windows-11.jpg)

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

## 3\. How to Disable Rounded Corners in Windows 11 via Device Manager

 Another way to remove rounded corners in Windows 11 is by disabling the graphics driver on your PC. However, it is important to consider a few caveats. Firstly, disabling the graphics driver will result in reduced display performance, lower screen resolutions, and the deactivation of any visual effects. Secondly, this will also prevent you from running any graphics-intensive applications or games on your PC.

 If you are fine with these trade-offs, use these steps to disable rounded corners via Device Manager.

1. Press **Win + X** to open the Power User menu.
2. Select **Device Manager** from the list.
3. Double-click on **Display adapters** to expand it.
4. Right-click on your display driver and select **Disable device**.  
![Disable Graphics Driver on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-graphics-driver-on-windows-11.jpg)

 Once the graphics driver is disabled, you should see square corners on all windows and menus in Windows 11\. If you want to undo this change later, simply enable the graphics driver via Device Manager.

## Disabling Rounded Corners in Windows 11 Is Easy

 Using a third-party tool is arguably the most convenient way to remove rounded corners in Windows 11\. However, if you prefer to rely on the native methods, you can use the Registry Editor or Device Manager instead.

 Disabling rounded corners isn’t the only way to get the classic look of previous Windows versions. You can also use a third-party tool like the ExplorerPatcher to make Windows 11 look like Windows 10\.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/seeking-entry-into-the-windows-11-insider-circle/"><u>Seeking Entry Into the Windows 11 Insider Circle</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-common-errors-in-office-app-activation-on-pc/"><u>Resolving Common Errors in Office App Activation on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/bringing-business-efficiency-installing-ms-works-on-windows/"><u>Bringing Business Efficiency: Installing MS Works on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-solution-for-inaccessible-administrative-mode/"><u>Comprehensive Solution for Inaccessible Administrative Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/microsofts-helpers-quick-fixes-for-window-woes/"><u>Microsoft's Helpers: Quick Fixes for Window Woes!</u></a></li>
<li><a href="https://windows11.techidaily.com/personalize-your-desktop-space-win-os-snap-configurations/"><u>Personalize Your Desktop Space: Win OS Snap Configurations</u></a></li>
<li><a href="https://windows11.techidaily.com/neutralize-required-condition-red-flags-in-win11/"><u>Neutralize Required Condition Red Flags in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/identifying-legitimate-and-false-positive-login-attempts-on-pcs/"><u>Identifying Legitimate and False-Positive Login Attempts on PCs</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-unlocking-the-power-of-smart-lock-a-beginners-guide-for-infinix-note-30-vip-racing-edition-users-by-drfone-android/"><u>In 2024, Unlocking the Power of Smart Lock A Beginners Guide for Infinix Note 30 VIP Racing Edition Users</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-secrets-back-on-snapchat-screen/"><u>[Updated] 2024 Approved  Secrets Back on Snapchat Screen</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-youtube-free-convert-your-fb-videos-into-720p1080p-mp4-online-guide/"><u>[New] In 2024, YouTube-Free  Convert Your FB Videos Into 720P/1080p MP4 Online Guide</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/no-spend-guide-to-the-best-ae-template-hits-for-2024/"><u>No-Spend Guide to the Best AE Template Hits for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-unlocking-the-code-a-guide-to-your-own-special-tiktok-hash/"><u>[New] 2024 Approved  Unlocking the Code  A Guide to Your Own Special TikTok Hash</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-unlocking-creative-potential-with-ig-reel-slow-motion/"><u>[Updated] 2024 Approved  Unlocking Creative Potential with IG Reel Slow-Motion</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-leave-a-life360-group-on-nubia-red-magic-8s-proplus-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How To Leave a Life360 Group On Nubia Red Magic 8S Pro+ Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-convert-twitter-vids-to-customized-soundtracks/"><u>[New] Convert Twitter Vids to Customized Soundtracks</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-8-ways-to-transfer-photos-from-oneplus-nord-ce-3-5g-to-iphone-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 8 Ways to Transfer Photos from OnePlus Nord CE 3 5G to iPhone Easily | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>