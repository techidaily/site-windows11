---
title: "Mastering PowerShell: Clearing Blocked Files in Windows"
date: 2024-09-11T17:13:43.635Z
updated: 2024-09-15T22:52:05.274Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering PowerShell: Clearing Blocked Files in Windows"
excerpt: "This Article Describes Mastering PowerShell: Clearing Blocked Files in Windows"
keywords: PowerShell File Cleanup,Unblock Windows Files,Windows Script Optimization,Remove Restrictions in PS,Mastering System Admin Tools,Clear Obstructed Files PSC,Enhancing Windows File Access
thumbnail: https://thmb.techidaily.com/3bbe537e8e6d43ee38a009c5ba9253564dbe37ab479840f5e7760ebe6f9d088b.jpg
---

## Mastering PowerShell: Clearing Blocked Files in Windows

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
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-tiktok-trends-navigating-copyright-laws-for-your-videos/"><u>[New] In 2024, TikTok Trends Navigating Copyright Laws for Your Videos</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-pinnacle-microphone-selections-for-4k-camera-excellence/"><u>[New] Pinnacle Microphone Selections for 4K Camera Excellence</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/can-chatgpt-and-bard-safely-steer-your-money-moves/"><u>Can ChatGPT and Bard Safely Steer Your Money Moves?</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/get-the-best-free-pc-sound-logger-download-x-recorder-for-2024/"><u>Get the Best Free PC Sound Logger – Download X-Recorder for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-share-location-in-messenger-on-apple-iphone-13-pro-max-drfone-by-drfone-virtual-ios/"><u>How to Share Location in Messenger On Apple iPhone 13 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-fake-android-location-without-rooting-for-your-lava-yuva-3-pro-drfone-by-drfone-virtual/"><u>In 2024, Fake Android Location without Rooting For Your Lava Yuva 3 Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-storage-management-4-keyways-into-windows-11-disk-settings/"><u>Optimize Storage Management: 4 Keyways Into Windows 11 Disk Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-device-duplication-resolve-already-used-errors-in-windows/"><u>Tackling Device Duplication: Resolve Already Used Errors in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-bypassing-check-pin-error-in-windows-1110-bluetooth/"><u>Techniques for Bypassing Check Pin Error in Windows 11/10 Bluetooth</u></a></li>
<li><a href="https://windows11.techidaily.com/transformative-strategies-to-supercharge-windows-11/"><u>Transformative Strategies to Supercharge Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-enabling-immersive-sound-experience/"><u>Windows 11: Enabling Immersive Sound Experience</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2121334/18498" target="_top" id="2121334">
  <img src="//a.impactradius-go.com/display-ad/18498-2121334" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2121334/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
