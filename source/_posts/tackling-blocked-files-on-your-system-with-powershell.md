---
title: Tackling Blocked Files on Your System with PowerShell
date: 2024-10-03T17:44:31.620Z
updated: 2024-10-07T02:26:11.761Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling Blocked Files on Your System with PowerShell
excerpt: This Article Describes Tackling Blocked Files on Your System with PowerShell
keywords: File Recovery PS,Unblock Files PS,Fix Blocked Files PS,Remove File Restrictions PS,Clear File Access Issues PS,Bypass File Blocks PowerShell,Enable System File Access PS
thumbnail: https://thmb.techidaily.com/fea6185edc685da72ba963a46eed57a3a71d461697393364ab3bd89b9977de72.jpg
---

## Tackling Blocked Files on Your System with PowerShell

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
<a href="https://appsumo.8odi.net/c/5597632/2151866/7443" target="_top" id="2151866">
  <img src="//a.impactradius-go.com/display-ad/7443-2151866" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151866/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-docs.techidaily.com/024-approved-10-youtube-music-rippers-for-android-and-ios/"><u>[New] 2024 Approved 10 YouTube Music Rippers for Android and iOS</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-2024-approved-navigating-spotifys-ad-landscape-a-beginners-guide/"><u>[New] 2024 Approved Navigating Spotify's Ad Landscape A Beginner's Guide</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-scripting-temporal-disruption-scenes/"><u>[New] Scripting Temporal Disruption Scenes</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-the-8-most-advanced-open-video-call-systems-for-the-workplace/"><u>[New] The 8 Most Advanced Open Video Call Systems for the Workplace</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-steps-to-alter-windows-msi-service-status/"><u>Essential Steps to Alter Windows MSI Service Status</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-run-an-unrestricted-chatgpt-alternative-on-windows-with-freedomgpt/"><u>How to Run an Unrestricted ChatGPT Alternative on Windows With FreedomGPT</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-sony-xperia-1-v-to-pc-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Sony Xperia 1 V to PC? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-use-pokemon-emerald-master-ball-cheat-on-motorola-edge-40-neo-drfone-by-drfone-virtual-android/"><u>In 2024, How to Use Pokémon Emerald Master Ball Cheat On Motorola Edge 40 Neo | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-circle-everything-you-need-to-know-on-poco-f5-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Circle Everything You Need to Know On Poco F5 5G | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-the-ultimate-guide-to-vivo-y36i-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Ultimate Guide to Vivo Y36i Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-surface-studio-2-almost-perfect-creators-choice/"><u>Microsoft Surface Studio 2 - Almost Perfect Creator's Choice</u></a></li>
<li><a href="https://windows11.techidaily.com/mystery-non-edge-processes-in-task-manager/"><u>Mystery: Non-Edge Processes in Task Manager?</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-for-swifter-loading-of-apps-from-microsoft-store/"><u>Navigating for Swifter Loading of Apps From Microsoft Store</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-overcoming-windows-error-code-xffffff/"><u>Quick Guide: Overcoming Windows Error Code XFFFFFF</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-stalled-grammarly-checkup-in-windows-810/"><u>Reviving Stalled Grammarly Checkup in Windows 8/10</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-speed-spectacle-hero-4-versus-ghost-s-drifting-edition/"><u>The Speed Spectacle Hero 4 Versus Ghost-S Drifting Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-stuck-chrome-on-win11-easy-methods-here/"><u>Troubleshooting Stuck Chrome on Win11 – Easy Methods Here</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-arp-caching-explained-and-tips-for-clears/"><u>Windows ARP Caching Explained & Tips for Clears</u></a></li>
<li><a href="https://windows11.techidaily.com/wsl-enabling-linux-on-windows-rise/"><u>WSL Enabling: Linux on Windows Rise</u></a></li>
</ul></div>

