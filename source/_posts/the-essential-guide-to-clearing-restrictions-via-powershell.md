---
title: The Essential Guide to Clearing Restrictions via PowerShell
date: 2024-10-01T06:30:16.515Z
updated: 2024-10-06T22:22:56.430Z
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
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1557747/17382" target="_top" id="1557747">
  <img src="//a.impactradius-go.com/display-ad/17382-1557747" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1557747/17382" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-non-gta-narratives-exploring-alternative-stories/"><u>[Updated] 2024 Approved Non-GTA Narratives Exploring Alternative Stories</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-from-broadcasts-to-bitstreams-online-recording-for-professionals/"><u>[Updated] From Broadcasts to Bitstreams Online Recording for Professionals</u></a></li>
<li><a href="https://solve-news.techidaily.com/10-solving-common-drive-and-software-problems/"><u>10 - Solving Common Drive and Software Problems</u></a></li>
<li><a href="https://some-guidance.techidaily.com/aneantissement-complet-du-convertisseur-video-freemaker-fonctionnalites-inedites-et-tarifs-competitifs/"><u>Anéantissement Complet Du Convertisseur Vidéo FreeMaker: Fonctionnalités Inédites Et Tarifs Compétitifs</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ing-collabs-that-attract-and-retain-viewers-for-2024/"><u>Crafting Collabs that Attract and Retain Viewers for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/explaining-0xc000003e-error-windows-app-failure-diagnosis/"><u>Explaining 0xC000003E Error: Windows App Failure Diagnosis</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-open-sticky-notes-at-startup-on-windows/"><u>How to Open Sticky Notes at Startup on Windows</u></a></li>
<li><a href="https://fox-that.techidaily.com/how-to-successfully-retry-and-complete-an-interrupted-ios-system-update/"><u>How to Successfully Retry and Complete an Interrupted iOS System Update</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-6-ways-to-change-spotify-location-on-your-vivo-t2-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 6 Ways to Change Spotify Location On Your Vivo T2 5G | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-infinix-hot-30-5g-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Infinix Hot 30 5G to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/incorinas-technology-and-apple-maps-for-windows-users/"><u>Incorinas Technology and Apple Maps for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-troubles-avoiding-sudden-game-stoppages/"><u>Navigating Windows Troubles: Avoiding Sudden Game Stoppages</u></a></li>
<li><a href="https://windows11.techidaily.com/re-establishing-erased-battery-mode-on-ws-11/"><u>Re-Establishing Erased Battery Mode on WS 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-fix-for-msvcr120dll-non-existence-on-computers/"><u>The Ultimate Fix for MSVCR120.DLL Non-Existence on Computers</u></a></li>
<li><a href="https://win-online.techidaily.com/top-8-techniques-for-converting-mts-files-to-mp4-on-windows-and-mac/"><u>Top 8 Techniques for Converting MTS Files to MP4 on Windows and Mac</u></a></li>
<li><a href="https://windows11.techidaily.com/transforming-data-integrating-windows-with-qr-technology/"><u>Transforming Data: Integrating Windows with QR Technology</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-printer-dilemma-windows-error-xffffff/"><u>Unraveling the Printer Dilemma: Windows Error XFFFFFF</u></a></li>
<li><a href="https://windows11.techidaily.com/what-is-the-arp-cache-and-how-do-you-clear-it-on-windows/"><u>What Is the ARP Cache, and How Do You Clear It on Windows?</u></a></li>
<li><a href="https://blog-min.techidaily.com/winxvideo-ai-revolutionnez-la-qualite-dimage-en-4k-8k-et-10k-pour-une-restauration-optimale/"><u>Winxvideo AI : Révolutionnez La Qualité D'Image en 4K, 8K Et 10K Pour Une Restauration Optimale</u></a></li>
</ul></div>

