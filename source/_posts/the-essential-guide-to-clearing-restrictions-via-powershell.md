---
title: The Essential Guide to Clearing Restrictions via PowerShell
date: 2025-02-24T11:45:13.505Z
updated: 2025-03-02T03:36:53.982Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Essential Guide to Clearing Restrictions via PowerShell
excerpt: This Article Describes The Essential Guide to Clearing Restrictions via PowerShell
keywords: PS Restriction Removal,PowerShell Command Guide,Admin Script for Restrictions,Bypassing Access Controls,Secure PowerShell Commands,Clear Permissions PS,Advanced User Rights
thumbnail: https://thmb.techidaily.com/029b0eb85077c27446243e8d1c815878a76764b760390b18a7b33382115f2d0b.jpg
---

## The Essential Guide to Clearing Restrictions via PowerShell

 So you’ve downloaded files onto a directory on your PC, but Windows doesn’t trust them? This is understandable because some files from the internet can harm your computer, but what if you know for sure that the files are safe? Luckily there’s an easy PowerShell command you can use to unblock all of them.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How Do I Unblock Multiple Files Using PowerShell on Windows?

 You can easily unblock a file by right-clicking on it and going to**Properties** — If you're on Windows 11, you'll need to click**Show more options** first before you can see the**Properties** option in the context menu. And once you're there, select the**General** tab and tick**Unblock** at the bottom in the**Security** section.

![unblocking a file in Properties on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unblock-file-properties-windows.jpg)

 But what if you have more than one file you need to unblock? Doing this one by one can get tedious. Alternatively, you can execute a single PowerShell command to unblock multiple files in a directory. Here is the command structure you need to use:

`dir [path] | unblock-file -confirm`

 Just replace**path** in the square brackets with the file path of the directory that has the blocked files. You can grab the file path of the directory by right-clicking on it and selecting**Copy as path** .

![copying file path on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/copy-as-path-windows-11.jpg)

 With the file path handy, follow the instructions below to use the unblock command in PowerShell:

1. Press**Win + S** to open Windows Search.
2. Type**powershell** in the search box and when the program appears in the search results, right-click on it and select**Run as administrator** . For more ways to open it, please read our guide on[ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
3. Enter the unblock command in PowerShell and hit the**Enter** key to run it. This is what it looks like on our computer:  
![entering the unblock file command in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-command.jpg)
4. You will be asked to confirm each file you want to unblock, so type either**Y** for**Yes** or**N** for**No** and hit the**Enter** key. This confirmation step is due to the**\-confirm** portion of the command. It is completely optional, and you can omit it or type**A** to confirm all the files in the directory.  

![confirming files to unblock in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-confirm.jpg)

 There’s a way you can tell Windows to always trust files you download from the internet. To do that, please read our guide on[how to stop Windows 10 from blocking your downloaded files](https://www.makeuseof.com/stop-windows-10-from-blocking-your-downloaded-files/) . The instructions in the tutorial use the Registry Editor and Local Group Policy Editor, so they should also work on Windows 11.

## Now You Know How to Unblock Files You Know Are Safe

 With the instruction above unlocking a bunch of downloaded files in a directory should be easier. Keep in mind that you shouldn’t do this on files you don’t trust. The last thing you want to do is put your Windows PC at risk unnecessarily

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
<li><a href="https://youtube-sure.techidaily.com/024-approved-launching-a-lucrative-channel-youtubes-most-accessible-biz-setups/"><u>[New] 2024 Approved Launching a Lucrative Channel YouTube's Most Accessible Biz Setups</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-copyright-free-game-audio-repositories/"><u>[Updated] 2024 Approved Copyright-Free Game Audio Repositories</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-masterful-screencasting-insights-into-advanced-techniques-and-tools/"><u>[Updated] Masterful Screencasting Insights Into Advanced Techniques & Tools</u></a></li>
<li><a href="https://win-answers.techidaily.com/advanced-dvd-unpacking-tool-transform-low-res-dvds-into-high-definition-format/"><u>Advanced DVD Unpacking Tool: Transform Low-Res DVDs Into High-Definition Format</u></a></li>
<li><a href="https://fox-zero.techidaily.com/download-your-favorite-cartoons-in-high-quality-how-to-convert-and-save-from-kimcartoon-as-mp4-or-avi/"><u>Download Your Favorite Cartoons in High Quality: How to Convert & Save From KIMCartoon as MP4 or AVI</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-music-from-redmi-k70-by-fonelab-android-recover-music/"><u>Easy steps to recover deleted music from Redmi K70</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/essential-shortcut-strategies-exploring-the-best-techniques-on-ios-platform/"><u>Essential Shortcut Strategies: Exploring the Best Techniques on iOS Platform</u></a></li>
<li><a href="https://windows11.techidaily.com/extending-windows-11-shutdown-for-active-tasks-tips-and-tricks/"><u>Extending Windows 11 Shutdown for Active Tasks: Tips & Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/fixes-for-application-flood-conquering-0x80860010/"><u>Fixes for Application Flood: Conquering 0X80860010</u></a></li>
<li><a href="https://windows11.techidaily.com/google-chrome-unresponsiveness-solved-expert-troubleshooting-tips/"><u>Google Chrome Unresponsiveness Solved: Expert Troubleshooting Tips</u></a></li>
<li><a href="https://some-approaches.techidaily.com/macwindows-1011m4awav/"><u>MacおよびWindows 10・11用のM4AファイルをWAVに自由に変換する手順集!</u></a></li>
<li><a href="https://facebook.techidaily.com/modifying-facebook-group-regulations-efficiently/"><u>Modifying Facebook Group Regulations Efficiently</u></a></li>
<li><a href="https://windows11.techidaily.com/quieting-chrome-bugs-on-windows-systems/"><u>Quieting Chrome Bugs on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-insert-isp-info-on-taskbar/"><u>Step-by-Step Guide: Insert ISP Info on Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-disabling-discordutation-at-windows-boot-up/"><u>Techniques for Disabling Discord'utation at Windows Boot-Up</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-fixing-non-responsive-pc-gamepad-issues/"><u>Tips for Fixing Non-Responsive PC Gamepad Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/tutorial-reverting-the-search-bar-design-of-windows-11/"><u>Tutorial: Reverting the Search Bar Design of Windows 11</u></a></li>
</ul></div>

