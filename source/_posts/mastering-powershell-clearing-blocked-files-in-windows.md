---
title: "Mastering PowerShell: Clearing Blocked Files in Windows"
date: 2025-01-03T21:54:58.973Z
updated: 2025-01-10T17:36:11.361Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aqeO4ed766s?si=AWtKHxP4hvQRd_lk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 But what if you have more than one file you need to unblock? Doing this one by one can get tedious. Alternatively, you can execute a single PowerShell command to unblock multiple files in a directory. Here is the command structure you need to use:

`dir [path] | unblock-file -confirm`

 Just replace**path** in the square brackets with the file path of the directory that has the blocked files. You can grab the file path of the directory by right-clicking on it and selecting**Copy as path** .

![copying file path on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/copy-as-path-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlVkEwpjKKo?si=hXi-mchMaJvbnIzM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 With the file path handy, follow the instructions below to use the unblock command in PowerShell:

1. Press**Win + S** to open Windows Search.
2. Type**powershell** in the search box and when the program appears in the search results, right-click on it and select**Run as administrator** . For more ways to open it, please read our guide on[ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
3. Enter the unblock command in PowerShell and hit the**Enter** key to run it. This is what it looks like on our computer:  
![entering the unblock file command in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-command.jpg)
4. You will be asked to confirm each file you want to unblock, so type either**Y** for**Yes** or**N** for**No** and hit the**Enter** key. This confirmation step is due to the**\-confirm** portion of the command. It is completely optional, and you can omit it or type**A** to confirm all the files in the directory.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S3Th6oa_isA?si=TTQ013BB9beUM4x6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![confirming files to unblock in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-confirm.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JlX-G8rBs1w?si=iIhUoWAq5x3YK9rA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 There’s a way you can tell Windows to always trust files you download from the internet. To do that, please read our guide on[how to stop Windows 10 from blocking your downloaded files](https://www.makeuseof.com/stop-windows-10-from-blocking-your-downloaded-files/) . The instructions in the tutorial use the Registry Editor and Local Group Policy Editor, so they should also work on Windows 11.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/AcAYRX0cwwA?si=DxqWU39vqksZbe1s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-blue.techidaily.com/updated-2024-approved-understanding-cloud-pricing-models-and-savings-strategies/"><u>[Updated] 2024 Approved Understanding Cloud Pricing Models & Savings Strategies</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-enhance-your-presence-best-free-tools-for-intriguing-openings/"><u>[Updated] Enhance Your Presence Best Free Tools for Intriguing Openings</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-a-filmmakers-dream-the-8-best-no-fee-video-editors-on-the-market/"><u>[Updated] In 2024, A Filmmaker's Dream The 8 Best No-Fee Video Editors on the Market</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-instantaneous-infiltration-of-lost-reddit-threads-for-2024/"><u>[Updated] Instantaneous Infiltration of Lost Reddit Threads for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-legal-means-to-elevate-your-youtube-popularity-by-one-million/"><u>[Updated] Legal Means to Elevate Your YouTube Popularity by One Million</u></a></li>
<li><a href="https://change-location.techidaily.com/here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-xiaomi-redmi-a2plus-drfone-by-drfone-virtual-android/"><u>Here Are Some Reliable Ways to Get Pokemon Go Friend Codes For Xiaomi Redmi A2+ | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-lava-yuva-3-pro-get-deleted-photos-back-with-ease-and-safety-by-fonelab-android-recover-photos/"><u>How to Lava Yuva 3 Pro Get Deleted photos Back with Ease and Safety?</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-innovative-tiktok-pfp-ideas-to-enhance-your-profile-visibility/"><u>In 2024, Innovative TikTok PFP Ideas to Enhance Your Profile Visibility</u></a></li>
<li><a href="https://windows11.techidaily.com/installing-apk-files-made-convenient-win-11s-guide-to-easy-setups/"><u>Installing APK Files Made Convenient: Win 11'S Guide to Easy Setups</u></a></li>
<li><a href="https://hardware-help.techidaily.com/logitech-k350-universal-wired-mouse-setup-and-driver-downloads/"><u>Logitech K350 Universal Wired Mouse Setup & Driver Downloads</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-windows-11-taskbar-functionality/"><u>Maximizing Windows 11 Taskbar Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/reimagine-your-workspace-with-direct-desktop-drawings-in-windows-11/"><u>Reimagine Your Workspace with Direct Desktop Drawings in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/safeguard-your-desktops-background-from-changes/"><u>Safeguard Your Desktop's Background From Changes</u></a></li>
<li><a href="https://windows11.techidaily.com/supercharge-your-workday-mastery-tips-for-multitasking-windows-11/"><u>Supercharge Your Workday: Mastery Tips for Multitasking Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/supercharging-windows-11s-protected-mode-graphics/"><u>Supercharging Windows 11'S Protected Mode Graphics</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/superior-hd-recording-systems-for-2024/"><u>Superior HD Recording Systems for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-high-cpu-drain-by-tiworkerexe/"><u>Tackling High CPU Drain by TiWorker.exe</u></a></li>
<li><a href="https://windows11.techidaily.com/unite-cloud-storage-onedrive-meets-microsoft-live-id/"><u>Unite Cloud Storage: OneDrive Meets Microsoft Live ID</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-your-print-potential-strategies-to-fix-slide-show-problems-on-windows/"><u>Unlocking Your Print Potential: Strategies to Fix Slide Show Problems on Windows</u></a></li>
</ul></div>

