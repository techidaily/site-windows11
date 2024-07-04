---
title: Mastering PowerShell to Break Free From Windows File Blocks
date: 2024-06-25T12:13:59.254Z
updated: 2024-06-26T12:13:59.254Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering PowerShell to Break Free From Windows File Blocks
excerpt: This Article Describes Mastering PowerShell to Break Free From Windows File Blocks
keywords: PowerShell Mastery,File Access Control,Bypass Windows Limits,Advanced Scripting Skills,Enhanced File Management,Automated Task Execution,Secure Administration Techniques
thumbnail: https://thmb.techidaily.com/d3f8a164ff7cec81bd719ff1860ad4b428bdab1ff70424914ce34922d708e742.jpg
---

## Mastering PowerShell to Break Free From Windows File Blocks

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
<li><a href="https://windows11.techidaily.com/securely-store-and-view-onedrive-data-locally/"><u>Securely Store and View OneDrive Data Locally</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-speed-up-and-conclude-your-puzzled-updates/"><u>How to Speed Up and Conclude Your Puzzled Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-w11-printer-error-fixes-related-to-ad-ds/"><u>Mastering W11 Printer Error Fixes Related to AD DS</u></a></li>
<li><a href="https://windows11.techidaily.com/reshaping-administration-workflow-in-the-windows-ecosystem/"><u>Reshaping Administration Workflow in the Windows Ecosystem</u></a></li>
<li><a href="https://windows11.techidaily.com/switch-onoff-windows-filter-keys-guide/"><u>Switch On/Off: Window's Filter Keys Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/change-to-dark-theme-in-the-windows-calculator/"><u>Change to Dark Theme in the Windows Calculator</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-system-8-routes-for-windows-restart/"><u>Reviving System: 8 Routes for Windows Restart</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11-secrets-with-devhome-insights/"><u>Unlocking Windows 11 Secrets with DevHome Insights</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-reimagined-analyzing-the-core-upgrades-of-windows-11/"><u>Windows Reimagined: Analyzing the Core Upgrades of Windows 11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/forgot-pattern-lock-heres-how-you-can-unlock-realme-gt-neo-5-pattern-lock-screen-by-drfone-android/"><u>Forgot Pattern Lock? Heres How You Can Unlock Realme GT Neo 5 Pattern Lock Screen</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/in-2024-quick-fix-valorant-thumbnails-professionally-done-now/"><u>In 2024, Quick-Fix Valorant Thumbnails  Professionally Done Now!</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-2024-approved-create-a-stunning-video-montage-a-step-by-step-guide/"><u>Updated 2024 Approved Create a Stunning Video Montage A Step-by-Step Guide</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/enhance-your-audio-experience-a-critical-look-at-the-5-premium-voice-recorders-for-mp3s/"><u>Enhance Your Audio Experience A Critical Look at the 5 Premium Voice Recorders for MP3s</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-apple-id-is-greyed-out-from-iphone-8-how-to-bypass-by-drfone-ios/"><u>In 2024, Apple ID is Greyed Out From iPhone 8 How to Bypass?</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-your-samsung-galaxy-z-flip-5-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Your Samsung Galaxy Z Flip 5 Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-what-is-discord-pfp-and-how-to-make-an-attractive-pfp-for-discord/"><u>[Updated] What Is Discord PFP and How to Make an Attractive PFP for Discord</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-quicktime-mov-editor-roundup-top-10-free-options/"><u>New QuickTime MOV Editor Roundup Top 10 Free Options</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-peak-level-illustration-tweaks/"><u>In 2024, Peak Level Illustration Tweaks</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-invisible-spectator-of-fb-tales/"><u>[New] In 2024, Invisible Spectator of FB Tales</u></a></li>
</ul></div>
