---
title: "Mastering PowerShell: Clearing Blocked Files in Windows"
date: 2025-01-26T23:16:15.439Z
updated: 2025-01-30T03:08:41.677Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=M69YSY0Mk_gsdU0Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Do I Unblock Multiple Files Using PowerShell on Windows?

 You can easily unblock a file by right-clicking on it and going to**Properties** — If you're on Windows 11, you'll need to click**Show more options** first before you can see the**Properties** option in the context menu. And once you're there, select the**General** tab and tick**Unblock** at the bottom in the**Security** section.

![unblocking a file in Properties on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unblock-file-properties-windows.jpg)

 But what if you have more than one file you need to unblock? Doing this one by one can get tedious. Alternatively, you can execute a single PowerShell command to unblock multiple files in a directory. Here is the command structure you need to use:

`dir [path] | unblock-file -confirm`

 Just replace**path** in the square brackets with the file path of the directory that has the blocked files. You can grab the file path of the directory by right-clicking on it and selecting**Copy as path** .

![copying file path on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/copy-as-path-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fo4lNZ84x9Q?si=WdcYPZp-9VJnZEnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 With the file path handy, follow the instructions below to use the unblock command in PowerShell:

1. Press**Win + S** to open Windows Search.
2. Type**powershell** in the search box and when the program appears in the search results, right-click on it and select**Run as administrator** . For more ways to open it, please read our guide on[ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
3. Enter the unblock command in PowerShell and hit the**Enter** key to run it. This is what it looks like on our computer:  
![entering the unblock file command in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-command.jpg)
4. You will be asked to confirm each file you want to unblock, so type either**Y** for**Yes** or**N** for**No** and hit the**Enter** key. This confirmation step is due to the**\-confirm** portion of the command. It is completely optional, and you can omit it or type**A** to confirm all the files in the directory.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zXUt81WsQpI?si=W3DKIAsa2-qbGadJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![confirming files to unblock in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-confirm.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3C51hzX46eY?si=o5qiDSkT7mXUGm3F" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 There’s a way you can tell Windows to always trust files you download from the internet. To do that, please read our guide on[how to stop Windows 10 from blocking your downloaded files](https://www.makeuseof.com/stop-windows-10-from-blocking-your-downloaded-files/) . The instructions in the tutorial use the Registry Editor and Local Group Policy Editor, so they should also work on Windows 11.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GBWcw6rXIdg?si=Tlue44bW-bPA4tH9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-lab.techidaily.com/levate-traffic-ethical-practices-for-amplifying-content-views-for-2024/"><u>[New] Elevate Traffic Ethical Practices for Amplifying Content Views for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-healing-harmony-best-20-soothing-country-tracks-to-groove-on-tiktok-for-2024/"><u>[New] Healing Harmony Best 20 Soothing Country Tracks to Groove On TikTok for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-ultimate-guide-to-meme-design-props/"><u>[New] The Ultimate Guide to Meme Design Props</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-10-best-zero-cost-videochats-collaboration-at-your-desk/"><u>[Updated] 2024 Approved 10 Best Zero-Cost Videochats Collaboration at Your Desk</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-benq-bl2711u-a-journey-through-professional-4k-display-tech/"><u>2024 Approved BenQ BL2711U - A Journey Through Professional 4K Display Tech</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-after-switching-from-vivo-t2-5g-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data After Switching From Vivo T2 5G to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-unblock-and-install-unverified-windows-software/"><u>How to Unblock and Install Unverified Windows Software</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-honor-x50-gt-bootloader-easily-by-drfone-android/"><u>How to Unlock Honor X50 GT Bootloader Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/incorinas-technology-and-apple-maps-for-windows-users/"><u>Incorinas Technology and Apple Maps for Windows Users</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/mastering-mac-finder-tailoring-view-options-for-folders-and-subfolders/"><u>Mastering Mac Finder - Tailoring View Options for Folders & Subfolders</u></a></li>
<li><a href="https://windows11.techidaily.com/re-establishing-erased-battery-mode-on-ws-11/"><u>Re-Establishing Erased Battery Mode on WS 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-fix-for-msvcr120dll-non-existence-on-computers/"><u>The Ultimate Fix for MSVCR120.DLL Non-Existence on Computers</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/the-ultimate-ranking-of-the-best-mobile-gaming-devices-according-to-zdnet/"><u>The Ultimate Ranking of the Best Mobile Gaming Devices According to ZDNet</u></a></li>
<li><a href="https://windows11.techidaily.com/transforming-data-integrating-windows-with-qr-technology/"><u>Transforming Data: Integrating Windows with QR Technology</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-printer-dilemma-windows-error-xffffff/"><u>Unraveling the Printer Dilemma: Windows Error XFFFFFF</u></a></li>
<li><a href="https://windows11.techidaily.com/what-is-the-arp-cache-and-how-do-you-clear-it-on-windows/"><u>What Is the ARP Cache, and How Do You Clear It on Windows?</u></a></li>
</ul></div>

