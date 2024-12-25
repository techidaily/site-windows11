---
title: "Proactive Device Management in Windows 11: Essential Uptime Verification Steps"
date: 2024-12-20T17:48:04.575Z
updated: 2024-12-25T19:52:26.720Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Proactive Device Management in Windows 11: Essential Uptime Verification Steps"
excerpt: "This Article Describes Proactive Device Management in Windows 11: Essential Uptime Verification Steps"
keywords: Win11 Proactice Devices,Uptime Verify Tech,Uptime Check Steps,Device Management Pro,Windows Uptime Controls,Verify System Health,Uptime Assurance
thumbnail: https://thmb.techidaily.com/75e496d7d03af882c809a7273c9e1eb1d9baeae9a3a5a4a6ed566b778061c9ff.png
---

## Proactive Device Management in Windows 11: Essential Uptime Verification Steps

 Checking your computer's uptime is something you might want to do to monitor its performance. This information can also come in handy when troubleshooting your system or performing regular maintenance tasks.

 Your Windows 11 PC provides several options for checking the device's uptime. Let’s go over all of them one by one.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2ipTu54inBo?si=gRegjvtVq5gm_PHo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Find System Uptime Using Task Manager

 Windows Task Manager is an advanced tool that provides useful information about your PC’s hardware and software. Here's how you can use it to find your computer’s uptime.

1. Press**Ctrl + Shift + Esc** on your keyboard or use one of the[many ways to access Task Manager](https://www.makeuseof.com/how-to-access-task-manager-on-windows-11/) .
2. In the**Performance** tab, click on**CPU** .
3. Check the system uptime under the**Up time** section.  
![Check System Uptime Using Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-system-uptime-using-task-manager.jpg)

## 2\. How to Find System Uptime via the Settings App

 Another way to check your system's uptime is through the Windows Settings app. Here are the steps for the same.

1. Press**Win + I** to open the Settings app.
2. Select the**Network & internet** tab from the left sidebar.
3. Click on**Advanced network settings** .
4. Under the**Network adapters** section, click on the active network adapter and check the uptime mentioned next to**Duration** .  
![Check System Uptime Using Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-system-uptime-using-windows-settings-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/w7c5EHp-GDw?si=UTw7lZR0wTmRjp8W" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Note that this method displays your network adapter’s uptime. So, the information displayed may not be accurate if you have reset your network connection after boot.

## 3\. How to Find System Uptime Using Control Panel

 If you prefer to do things the old-fashioned way, you can use the classic Control Panel to find your device’s uptime in Windows 11\. To do so, use the following steps:

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**control panel** in the box and select the first result that appears.
3. In the Control Panel window that appears, use the drop-down menu in the top right corner to change the view type to**Large icons** .
4. Click on**Network and Sharing Center** .
5. Click on**Change adapter settings** in the left pane.
6. Right-click on the active network adapter and select**Status** .
7. Under the**General** tab, you’ll find the uptime next to**Duration** .  
![Check System Uptime Using Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-system-uptime-using-control-panel.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jpdGEJJwMLY?si=eKgXOPpNeYvYKcel" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. How to Check System Uptime With Command Prompt

 If you're an advanced Windows user, you can also use Command Prompt to check your computer’s uptime. Here’s how:

1. Right-click on the Start icon or press**Win + X** to open the Power User menu.
2. Select**Terminal** from the list.
3. Type the following command in the console and press**Enter** .  
`systeminfo | find "System Boot Time"`  
![Check System Uptime Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-system-uptime-using-command-prompt.jpg)

 Once you run the above command, Command Prompt should display the time when your computer started operating. You can easily calculate the system uptime by subtracting the**System Boot Time** from the current time.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HaM818fFKXQ?si=ZZLA4lFSHSgCpSE0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. How to Check System Uptime With PowerShell

 PowerShell is another command-line tool available on Windows. If you prefer using that, follow these steps to find your device’s uptime.

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**Windows PowerShell** and press**Enter** .
3. Paste the following command in the PowerShell window and press**Enter** .  
`(get-date) - (gcim Win32_OperatingSystem).LastBootUpTime`  
![Check System Uptime Using Windows PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-system-uptime-using-windows-powershell.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3C51hzX46eY?si=o5qiDSkT7mXUGm3F" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 PowerShell should display the number of days, hours, minutes, seconds, and milliseconds since the device was turned on.

 Like using PowerShell on Windows? Why not familiarize yourself with these[best PowerShell commands on Windows](https://www.makeuseof.com/windows-powershell-commands-cmdlets/) ?

## Checking Your Device Uptime on Windows 11

 As we just saw, finding your Windows 11 PC’s uptime is fairly simple. You can use any of the methods listed above to find that information.

 The total uptime of your computer may not provide you with accurate information about how much time you spend in front of it. For that, you’ll need to check Power & battery usage in the Windows Settings app.

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
<li><a href="https://youtube-tips.techidaily.com/roadcast-repeat-looping-youtube-video-magic-for-your-setup-for-2024/"><u>[New] Broadcast Repeat Looping YouTube Video Magic for Your Setup for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-pioneering-color-grading-with-3d-luts/"><u>[New] Pioneering Color Grading with 3D LUTs</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-spotifys-top-10-chart-toppers-for-2024/"><u>[New] Spotify’s Top 10 Chart-Toppers for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-step-by-step-download-vimeo-to-mp4-files-for-2024/"><u>[New] Step-by-Step Download Vimeo to MP4 Files for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-instagrams-trust-tales-decoding-the-power-of-selfies/"><u>[Updated] Instagram's Trust Tales Decoding the Power of Selfies</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-audio-interface-innovations-for-optimal-podcasting/"><u>2024 Approved Audio Interface Innovations for Optimal Podcasting</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-learn-the-ins-and-outs-of-adding-gifs-on-instagram-in-4-steps/"><u>2024 Approved Learn the Ins and Outs of Adding GIFs on Instagram in 4 Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-non-initialized-disks-a-windows-guide/"><u>Fixing Non-Initialized Disks: A Windows Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reactivate-frozen-taskbar-and-menu/"><u>How to Reactivate Frozen Taskbar & Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-refresh-the-group-policy-settings-on-windows/"><u>How to Refresh the Group Policy Settings on Windows</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ideo-editing-selections-for-social-media-for-2024/"><u>Pro Video Editing Selections for Social Media for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-missed-game-content-with-steam-on-win11/"><u>Resolving Missed Game Content with Steam on Win11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/rootjunky-apk-to-bypass-google-frp-lock-for-infinix-note-30-pro-by-drfone-android/"><u>Rootjunky APK To Bypass Google FRP Lock For Infinix Note 30 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-power-of-windows-nettools/"><u>Unveiling the Power of Windows NetTools</u></a></li>
</ul></div>

