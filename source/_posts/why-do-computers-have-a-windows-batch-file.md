---
title: Why Do Computers Have a Windows Batch File?
date: 2024-12-08T21:39:45.048Z
updated: 2024-12-10T18:33:31.450Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Why Do Computers Have a Windows Batch File?
excerpt: This Article Describes Why Do Computers Have a Windows Batch File?
keywords: Batch Files in Computing,Windows System Scripts,Programming Command Files,Computer OS Integration,Operating Systems Tasking,Execution Batch Processes,Software Automation Windows
thumbnail: https://thmb.techidaily.com/a929b0d993c705dcd1293af7219e5e597567df393d17dd26d0130a00b3701a6a.JPG
---

## Why Do Computers Have a Windows Batch File?

 Deleting the hidden "$Windows.\~BT" folder and recovering gigabytes of space on your hard drive is tempting. But what is this cryptically named folder for, and how critical is it to your Windows installation?

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15TKQ-BOENI?si=Ri4B2AuxAdi0Bglz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Is the “$Windows.\~BT” Folder, and Should You Delete It?

 Windows creates the "$Windows.\~BT" folder when you upgrade the operating system to a newer build. This folder contains all the essential files for the upgrade process, like temporary installation files and logs from the previous Windows installation.

 Windows automatically removes the "$Windows.\~BT" folder after 10 days. As manually deleting this folder will [remove old Windows installation files](https://www.makeuseof.com/tag/delete-old-windows-update-files/), you won't be able to roll back to the previous Windows build using the **Go back** option in the Recovery menu within that time (for example, to [downgrade from Windows 11 to Windows 10](https://www.makeuseof.com/windows-11-downgrade-to-windows-10/)). Hence, you should only get rid of this folder if you are satisfied with the current Windows build on your PC. You can also safely delete the massive folder if Windows fails to do it automatically after the grace period.

 But you shouldn't just delete this hidden folder like any other folder on the desktop. Instead, you should turn to the Disk Cleanup tool or the Command Prompt.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/td3ojuzhloY?si=N_maQNiJWrJp7XZl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Find and Delete the "$Windows.\~BT" Folder

 As "$Windows.\~BT" is a hidden folder, you need to [configure Windows to show hidden files and folders](https://www.makeuseof.com/windows-11-show-hidden-files-folders/) to find it in File Explorer. Once you do, the **C:\\$Windows.\~BT** directory will become visible.

 You can’t delete the "$Windows.\~BT" folder directly, though. To do so, you need to run the Disk Cleanup tool. Here's how:

1. Press **Win + R** to open the Run dialog box.
2. Type **cleanmgr** in the box and press **Enter**.
3. Use the dropdown menu to select the system drive (usually **C:**) and click **OK**.
4. Click the **Clean up system files** button.
5. Under **Files to delete**, use the checkboxes to select these options: **Previous Windows Installations**, **Windows Update Cleanup**, **Windows upgrade log files**, **Temporary Windows installation files**, and **Temporary files**.
6. Click **OK**.
7. Choose **Delete Files** to confirm.  
![Delete the $Windows.~BT Folder Using the Disk Cleanup Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/delete-the-windows-bt-folder-using-the-disk-cleanup-tool.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jpdGEJJwMLY?si=eKgXOPpNeYvYKcel" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If the "$Windows.\~BT" folder shows up even after you run the Disk Cleanup tool, you'll need to execute a few commands in Command Prompt. For that, [open Command Prompt with administrative rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) and then run the following commands one by one.

`takeown /F C:\$Windows.~BT\* /R /A
icacls C:\$Windows.~BT\*.* /T /grant administrators:F
rmdir /S /Q C:\$Windows.~BT\`

 Once you run the above commands, the "$Windows.\~BT" folder will be deleted for good.

 Now that you understand the purpose of the "$Windows.\~BT" folder, you can decide how to handle it. Beyond the "$Windows.\~BT" folder, you may also come across folders like "Windows.old," "$WinREAgent," "$SysReset," and others which can also be deleted safely using the Disk Cleanup tool.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-top-8-best-screen-recorders-with-no-lag/"><u>[New] 2024 Approved Top 8 Best Screen Recorders with No Lag</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-ironborn-chimes-expertly-selected-spots-for-tts-downloads/"><u>[Updated] Ironborn Chimes Expertly Selected Spots for TTS Downloads</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-snapshots-of-success-recording-your-switch-gaming/"><u>2024 Approved Snapshots of Success Recording Your Switch Gaming</u></a></li>
<li><a href="https://driver-install.techidaily.com/fix-for-incompatible-hd-audio-in-new-windows-release/"><u>Fix for Incompatible HD Audio in New Windows Release</u></a></li>
<li><a href="https://windows11.techidaily.com/note-taking-evolution-embracing-obsidian-canvas/"><u>Note-Taking Evolution: Embracing Obsidian Canvas</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-unfreezing-stuck-spotify-app-in-win11-pcs/"><u>Quick Guide: Unfreezing Stuck Spotify App in Win11 PCs</u></a></li>
<li><a href="https://facebook.techidaily.com/staying-safe-from-social-engineering-snares/"><u>Staying Safe From Social Engineering Snares</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-boost-utorrent-downloads-in-windows/"><u>Strategies to Boost uTorrent Downloads in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-troubled-waters-of-outlooks-winerror-x/"><u>Tackling the Troubled Waters of Outlook's WinError X</u></a></li>
<li><a href="https://windows11.techidaily.com/tech-nostalgia-unleashed-windows-11-to-the-past/"><u>Tech Nostalgia Unleashed: Windows 11 to the Past</u></a></li>
<li><a href="https://windows11.techidaily.com/the-5-best-fixes-for-hiberatus-computers/"><u>The 5 Best Fixes for Hiberatus Computers</u></a></li>
<li><a href="https://video-capture.techidaily.com/top-picks-and-tips-for-thriving-in-valheim/"><u>Top Picks & Tips for Thriving in Valheim</u></a></li>
<li><a href="https://windows11.techidaily.com/tweaking-windows-lockscreensaver-timer/"><u>Tweaking Windows Lock/Screensaver Timer</u></a></li>
<li><a href="https://fox-info.techidaily.com/windowed-guide-windows-movie-maker-60-preparation/"><u>Windowed Guide Windows Movie Maker 6.0 Preparation</u></a></li>
<li><a href="https://solve-help.techidaily.com/winxdvd-utilisateur-ameliorer-sa-connaissance-avec-le-manuel-complet-explique/"><u>WinXDVD Utilisateur Améliorer Sa Connaissance Avec Le Manuel Complet Expliqué</u></a></li>
</ul></div>

