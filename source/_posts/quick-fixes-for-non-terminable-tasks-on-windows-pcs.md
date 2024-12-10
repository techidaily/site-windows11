---
title: Quick Fixes for Non-Terminable Tasks on Windows PCs
date: 2024-12-04T20:43:43.916Z
updated: 2024-12-10T21:38:53.717Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quick Fixes for Non-Terminable Tasks on Windows PCs
excerpt: This Article Describes Quick Fixes for Non-Terminable Tasks on Windows PCs
keywords: Terminate Task Quickly,Windows Task Halt,Fix Unfinished Task,Stop Non-Ending Process,End Non-Terminating Apps,PC Task Remediation,Completing Stalled Windows Tasks
thumbnail: https://thmb.techidaily.com/c3d35b16437bab1ad5b7b686beca2df570e5510e7d66b97529a73f9cf277751a.jpg
---

## Quick Fixes for Non-Terminable Tasks on Windows PCs

 Task Manager is a handy system utility for terminating unwanted apps and processes on Windows. Although it usually works as expected, there are times when Task Manager malfunctions and displays the "unable to terminate process" error on Windows.

 If you’re unable to terminate apps or processes due to this error, here are some ways you can either fix the error message or bypass it using a different method outside of Windows' Task Manager.

## 1\. Use the Alt + F4 Keyboard Shortcut

 At times, temporary glitches with an app or program can trigger the “unable to terminate process” error on Windows. If it’s nothing major, you should be able to close the unresponsive program with the**Alt + F4** keyboard shortcut. Switch to the app or program you want to close and press**Alt + F4** together on your keyboard to close it.

 Check out[how to force close a program without the Task Manager](https://www.makeuseof.com/tag/how-to-kill-unresponsive-programs-without-the-task-manager/) for more ways to close an app without using this tool.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Jfq2Wx1Bcs?si=YQrYpTy0g4aV5QaO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Open Task Manager as an Administrator

 Not running Task Manager as an administrator could prevent you from terminating certain system processes. If that’s the case, use the following steps to open Task Manager with elevated rights and then try to terminate the process again.

1. Click the magnifying icon on the taskbar to open the search menu.
2. Type**Task Manager** in the box and select**Run as administrator** .
3. When the[User Account Control (UAC)](https://www.makeuseof.com/tag/user-account-control-windows-10/) prompt appears, select**Yes** to continue.
4. Right-click on the process you want to terminate and select**End task** from the context menu.  
![Close Process Using Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/close-process-using-task-manager.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/szUqw4TLvWs?si=srv1OeLOe579gLwj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Use the Taskkill Command to Terminate the Process

 Using the Task Manager isn’t the only way to terminate processes on Windows. If you’re comfortable using Command Prompt, you can run the "taskkill" command to easily stop an unwanted process on Windows.

 In order to terminate a process with the taskkill command, you’ll need to know the exact name of the process. To find out, switch to the**Details** tab in the Task Manager window and locate the process you want to kill. Note down its name from the first column.

![Details Tab in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/details-tab-in-task-manager.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GFHH14XlFCk?si=2HcjQbDx5eG0ZQAt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you have the name of the process, use the following steps to terminate it.

1. Press**Win + S** to open the search menu.
2. Type**Command Prompt** in the box and select**Run as administrator** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Type the following command and press**Enter** to terminate the process. Make sure you replace**ProcessName** in the following command with the actual name of the process noted earlier.  
`taskkill /IM "ProcessName" /T /F`  
![Terminate Process With Taskkill Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/terminate-process-with-taskkill-command.jpg)

 Once you run the above command, you should see a confirmation message indicating that the process was terminated successfully.

## 4\. Terminate the Process With WMIC

 WMIC (or Windows Management Instrumentation Command-line) is another powerful tool for terminating processes on Windows. Again, you'll need to know the exact name of the process you want to kill. Once you have that, use the following steps to terminate the process with WMIC.

1. Use any of your preferred methods to[open Command Prompt with administrative privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
2. Paste the following command in the console, replace**ProcessName** with the actual name of the process you want to terminate, and press**Enter** .  
`wmic process where name='processname.exe' delete`  
![Terminate Process With WMIC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/terminate-process-with-wmic.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DCARjc5g5VI?si=9OfovbKBrpoJeXTY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Use a Task Manager Alternative

 Finally, if none of the solutions help with the "unable to terminate process" error, you can consider using a[Task Manager alternative on Windows](https://www.makeuseof.com/tag/5-powerful-alternatives-windows-task-manager/) . If you're looking for something with more power, Process Explorer is a solid choice.

1. [Download Process Explorer](https://learn.microsoft.com/en-us/sysinternals/downloads/process-explorer) on your computer.
2. Double-click the**procexp64.exe** to open Process Explorer.
3. Locate the process you want to terminate. Right-click on it and select**Kill Process** from the resulting menu.  
![Kill Process Using Process Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/kill-process-using-process-explorer.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/C3cJe7Wgn6I?si=EckDFML-VJ_2sYz8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Your Tasks, Terminated Successfully

 By applying the fixes in the article, you should be able to fix the “unable to terminate process” error on Windows. However, be cautious when terminating processes via Task Manager, as some may cause your system to freeze or crash if terminated.

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
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-proven-techniques-for-obs-broadcasting-on-fb/"><u>[New] 2024 Approved Proven Techniques for OBS Broadcasting on FB</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-unlock-the-secrets-of-stellar-snaps-and-snapchat-boomers/"><u>[New] In 2024, Unlock the Secrets of Stellar Snaps and Snapchat Boomers</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-harvest-hangouts-the-most-friendly-farm-gaming-experiences/"><u>[Updated] In 2024, Harvest Hangouts The Most Friendly Farm Gaming Experiences</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-essential-steps-for-podcast-rss-feed-creation/"><u>2024 Approved Essential Steps for Podcast RSS Feed Creation</u></a></li>
<li><a href="https://win-dash.techidaily.com/behringer-usb-sound-card-software-get-the-latest-version-now/"><u>Behringer USB Sound Card Software - Get the Latest Version Now</u></a></li>
<li><a href="https://windows11.techidaily.com/from-screenless-to-seen-effective-methods-for-re-emerging-off-screen-windows-in-win-10/"><u>From Screenless To Seen: Effective Methods for Re-Emerging Off-Screen Windows in Win 10</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-razer-synapse-not-working-in-windows-1110/"><u>How to Fix Razer Synapse Not Working in Windows 11/10</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-motorola-razr-40-drfone-by-drfone-virtual-android/"><u>How to get the dragon scale and evolution-enabled pokemon On Motorola Razr 40? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-changeadd-location-filters-on-snapchat-for-your-realme-gt-3-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change/Add Location Filters on Snapchat For your Realme GT 3 | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-unlocking-an-icloud-locked-ipad-and-iphone-xs-by-drfone-ios/"><u>In 2024, Unlocking an iCloud Locked iPad and iPhone XS</u></a></li>
<li><a href="https://windows11.techidaily.com/interpreting-storage-identities-c-drive-and-d-drive-tale/"><u>Interpreting Storage Identities: C Drive & D Drive Tale</u></a></li>
<li><a href="https://windows11.techidaily.com/launch-your-windows-11-pc-into-wireless-broadcast-mode/"><u>Launch Your Windows 11 PC Into Wireless Broadcast Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-audio-device-irq-balancing/"><u>Mastering Audio Device IRQ Balancing</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/pvr-uno-customizable-media-solution-for-2024/"><u>PVR Uno Customizable Media Solution for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-the-entry-to-wordpad-on-pc/"><u>Streamlining the Entry to WordPad on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-to-disable-game-proposals-on-w11-home-system/"><u>Tips to Disable Game Proposals on W11 Home System</u></a></li>
</ul></div>

