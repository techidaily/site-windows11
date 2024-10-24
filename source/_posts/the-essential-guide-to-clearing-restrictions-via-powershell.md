---
title: The Essential Guide to Clearing Restrictions via PowerShell
date: 2024-10-19T16:21:26.145Z
updated: 2024-10-24T20:57:53.431Z
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1972684/19272" target="_top" id="1972684">
  <img src="//a.impactradius-go.com/display-ad/19272-1972684" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1972684/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://screen-sharing-recording.techidaily.com/new-the-ultimate-list-of-the-best-video-call-recording-equipment-for-2024/"><u>[New] The Ultimate List of the Best Video Call Recording Equipment for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-fb-livestream-success-on-television-four-pathways-for-2024/"><u>[Updated] FB Livestream Success on Television Four Pathways for 2024</u></a></li>
<li><a href="https://solve-news.techidaily.com/complete-tutorial-on-setting-up-libdvdcss-for-handbrake-on-macos-and-windows-10-systems/"><u>Complete Tutorial on Setting Up Libdvdcss for Handbrake on macOS and Windows 10 Systems</u></a></li>
<li><a href="https://tech-hub.techidaily.com/excel/"><u>Excel表示範囲の記録方法：操作手順ビデオガイド</u></a></li>
<li><a href="https://windows11.techidaily.com/gain-control-of-costs-windows-11-pro-key-advantages/"><u>Gain Control of Costs: Windows 11 Pro Key Advantages</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-do-i-stop-someone-from-tracking-my-motorola-edge-2023-drfone-by-drfone-virtual-android/"><u>How Do I Stop Someone From Tracking My Motorola Edge 2023? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/improve-notepad-on-win11-via-ingenious-sage/"><u>Improve Notepad on Win11 via Ingenious Sage</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-infinix-smart-7-hd-by-drfone-android/"><u>In 2024, AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Infinix Smart 7 HD</u></a></li>
<li><a href="https://hardware-help.techidaily.com/quick-setup-for-hp-officejet-n5740-download-compatible-drivers-here/"><u>Quick Setup for HP OfficeJet N5740: Download Compatible Drivers Here</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-path-not-found-issue-in-windows-xp7/"><u>Resolving Path Not Found Issue in Windows XP/7</u></a></li>
<li><a href="https://windows11.techidaily.com/secret-menu-additions-a-step-by-step-guide-in-win-10/"><u>Secret Menu Additions: A Step-by-Step Guide in Win 10</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-security-refreshing-windows-group-policies/"><u>Streamlining Security: Refreshing Windows Group Policies</u></a></li>
</ul></div>

