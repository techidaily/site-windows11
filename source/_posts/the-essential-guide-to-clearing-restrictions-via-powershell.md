---
title: The Essential Guide to Clearing Restrictions via PowerShell
date: 2024-11-01T07:13:57.833Z
updated: 2024-11-05T10:35:20.056Z
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
<span id="1424527">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424527.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424527">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424527.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424527%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424527/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-record-videos.techidaily.com/new-enhance-branding-the-ultimate-guide-to-custom-urls-for-youtube-for-2024/"><u>[New] Enhance Branding The Ultimate Guide to Custom URLs for YouTube for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-strategies-for-syncing-zoom-meetings-across-devices/"><u>[New] In 2024, Strategies for Syncing Zoom Meetings Across Devices</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-master-picks-for-commercial-cloud-space/"><u>[New] Master Picks for Commercial Cloud Space</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-network-growth-strategy-share-twitch-live-links-on-fb/"><u>[New] Network Growth Strategy Share Twitch Live Links on FB</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-direct-recording-tool-for-chrome-os/"><u>[Updated] 2024 Approved Direct Recording Tool for Chrome OS</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-mastering-telegram-the-ultimate-step-by-step-guide/"><u>[Updated] Mastering Telegram The Ultimate Step-By-Step Guide</u></a></li>
<li><a href="https://discover-bytes.techidaily.com/come-connettere-la-tua-libreria-di-rete-con-google-drive-in-modo-effettivo/"><u>Come Connettere La Tua Libreria Di Rete Con Google Drive in Modo Effettivo</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-file-error-puzzle-finding-solution-for-0x80070570-on-windows-11/"><u>Decoding the File Error Puzzle - Finding Solution for 0X80070570 on Windows 11</u></a></li>
<li><a href="https://tech-haven.techidaily.com/from-simple-ai-to-sophisticated-gpt-4/"><u>From Simple AI to Sophisticated GPT-4</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-address-geforce-nows-error-code-xc0f1103f/"><u>How To Address GeForce Now's Error Code Xc0f1103f</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-an-attempt-was-made-to-reference-a-token-error-in-windows-1110/"><u>How to Fix the “An Attempt Was Made to Reference a Token” Error in Windows 11/10</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-a-perfect-guide-to-remove-or-disable-google-smart-lock-on-motorola-g54-5g-by-drfone-android/"><u>In 2024, A Perfect Guide To Remove or Disable Google Smart Lock On Motorola G54 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-camera-access-notification-controls-on-win11/"><u>Mastering Camera Access Notification Controls on Win11</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/navigating-instagrams-voice-customization-features/"><u>Navigating Instagram's Voice Customization Features</u></a></li>
<li><a href="https://windows11.techidaily.com/1719373513910-reawaken-chrome-on-win11-essential-troubleshooting-steps/"><u>Reawaken Chrome on Win11 – Essential Troubleshooting Steps.</u></a></li>
<li><a href="https://windows11.techidaily.com/reignite-your-windows-11-search-top-11-fixes-here/"><u>Reignite Your Windows 11 Search: Top 11 Fixes Here</u></a></li>
<li><a href="https://windows11.techidaily.com/1719374357320-seven-big-mistakes-new-users-could-make-in-windows-11-to-avoid/"><u>Seven Big Mistakes New Users Could Make in Windows 11 - To Avoid!</u></a></li>
<li><a href="https://windows11.techidaily.com/slashing-gpu-energy-on-desktop-window-manager/"><u>Slashing GPU Energy on Desktop Window Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-install-non-verified-windows-applications/"><u>Steps to Install Non-Verified Windows Applications</u></a></li>
</ul></div>

