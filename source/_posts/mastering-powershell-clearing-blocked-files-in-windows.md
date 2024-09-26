---
title: "Mastering PowerShell: Clearing Blocked Files in Windows"
date: 2024-09-21T21:03:47.458Z
updated: 2024-09-26T17:03:50.091Z
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037358/7443" target="_top" id="2037358">
  <img src="//a.impactradius-go.com/display-ad/7443-2037358" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037358/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-connectivity-at-its-peak-strategies-for-broadcasting-videos-to-friends/"><u>[New] In 2024, Connectivity at Its Peak Strategies for Broadcasting Videos to Friends</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-windows-desktop-recording-techniques-no-cost-for-2024/"><u>[New] Windows Desktop Recording Techniques - No Cost for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-expert-tactics-optimizing-freefire-video-content/"><u>[Updated] Expert Tactics Optimizing FreeFire Video Content</u></a></li>
<li><a href="https://location-fake.techidaily.com/10-best-fake-gps-location-spoofers-for-poco-c51-drfone-by-drfone-virtual-android/"><u>10 Best Fake GPS Location Spoofers for Poco C51 | Dr.fone</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-tech-tips-how-to-get-fcp-without-money/"><u>2024 Approved Tech Tips How to Get FCP Without Money</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-pin-count-on-the-w11-start-screen/"><u>Boosting Pin Count on the W11 Start Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-the-barrier-of-windows-11-updates/"><u>Breaking Down the Barrier of Windows 11 Updates</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-5-best-route-generator-apps-you-should-try-on-samsung-galaxy-s23-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Best Route Generator Apps You Should Try On Samsung Galaxy S23 | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-can-life360-track-you-when-your-oneplus-ace-2-is-off-drfone-by-drfone-virtual-android/"><u>In 2024, Can Life360 Track You When Your OnePlus Ace 2 is off? | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/perfect-6-apps-for-private-android-video-capturing-for-2024/"><u>Perfect 6 Apps for Private Android Video Capturing for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/resurrect-your-pcs-absent-controllers/"><u>Resurrect Your PC's Absent Controllers</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-challenge-of-non-working-win-plus-printer-feature-in-windows/"><u>Tackling the Challenge of Non-Working Win + Printer Feature in Windows.</u></a></li>
<li><a href="https://some-skills.techidaily.com/top-audio-equipment-for-crystal-clear-4k-video-capture-for-2024/"><u>Top Audio Equipment for Crystal Clear 4K Video Capture for 2024</u></a></li>
</ul></div>

