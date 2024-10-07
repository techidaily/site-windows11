---
title: "Unlocking Windows: How to Use PowerShell for File Unblocking"
date: 2024-09-30T09:57:27.025Z
updated: 2024-10-06T21:03:14.741Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unlocking Windows: How to Use PowerShell for File Unblocking"
excerpt: "This Article Describes Unlocking Windows: How to Use PowerShell for File Unblocking"
keywords: PowerShell File Unblock,Blocked Files Clearance,PowerShell Security,Windows Admin Tools,Enable Execution Policy,Script-Based Unblocking,Windows Cleanup Commands
thumbnail: https://thmb.techidaily.com/df6d6f7af97a6f2a263dcbc0519760a864ba0996ca5b9b75ea6d971b44c71c22.jpg
---

## Unlocking Windows: How to Use PowerShell for File Unblocking

 So you’ve downloaded files onto a directory on your PC, but Windows doesn’t trust them? This is understandable because some files from the internet can harm your computer, but what if you know for sure that the files are safe? Luckily there’s an easy PowerShell command you can use to unblock all of them.

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
<a href="https://bluettiit.sjv.io/c/5597632/2148129/17093" target="_top" id="2148129">
  <img src="//a.impactradius-go.com/display-ad/17093-2148129" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettiit.sjv.io/i/5597632/2148129/17093" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-aspiring-youtubers-guide-to-affiliate-allies/"><u>[New] 2024 Approved Aspiring YouTubers' Guide to Affiliate Allies</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-creative-freedom-redefined-a-review-of-screenflow-on-macbook-pro/"><u>[New] 2024 Approved Creative Freedom Redefined A Review of ScreenFlow on MacBook Pro</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-fps-feudalists-unearthing-the-top-7-war-games/"><u>[New] 2024 Approved FPS Feudalists – Unearthing the Top 7 War Games</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-steps-to-establish-a-viable-youtube-sponsor-relationship/"><u>[New] Steps to Establish a Viable YouTube Sponsor Relationship</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-key-points-to-understand-tiktok-web-macos/"><u>[Updated] Key Points to Understand TikTok Web (macOS)</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-pixel-problems-non-existent-videos-on-a6400/"><u>2024 Approved Pixel Problems Non-Existent Videos on A6400</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-empty-folder-location-and-deletion-in-windows/"><u>Mastering Empty Folder Location and Deletion in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-wi-fi-settings-seamless-action-integration-on-microsoft-devices/"><u>Mastering Wi-Fi Settings: Seamless Action Integration on Microsoft Devices</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/mechanical-keyboard-care-101-a-comprehensive-guide-to-keep-it-sparkling-clean/"><u>Mechanical Keyboard Care 101: A Comprehensive Guide to Keep It Sparkling Clean</u></a></li>
<li><a href="https://common-error.techidaily.com/simple-fixes-for-enabling-wi-fi-connectivity-issues-solved/"><u>Simple Fixes for Enabling Wi-Fi Connectivity Issues [Solved]</u></a></li>
<li><a href="https://windows11.techidaily.com/stepwise-method-to-activate-dark-mode-in-notepad-on-windows-11-pcs/"><u>Stepwise Method to Activate Dark Mode in Notepad on Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-remedying-windows-11-logins/"><u>Understanding & Remedying Windows 11 Logins</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-powered-disk-cloning-no-add-ons-needed/"><u>Windows-Powered Disk Cloning, No Add-Ons Needed</u></a></li>
</ul></div>

