---
title: The Essential Guide to Clearing Restrictions via PowerShell
date: 2024-12-02T22:30:40.948Z
updated: 2024-12-03T22:17:09.234Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YwOwUI47FuU?si=NK7IEELjx7_SJSl2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Do I Unblock Multiple Files Using PowerShell on Windows?

 You can easily unblock a file by right-clicking on it and going to**Properties** — If you're on Windows 11, you'll need to click**Show more options** first before you can see the**Properties** option in the context menu. And once you're there, select the**General** tab and tick**Unblock** at the bottom in the**Security** section.

![unblocking a file in Properties on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unblock-file-properties-windows.jpg)

 But what if you have more than one file you need to unblock? Doing this one by one can get tedious. Alternatively, you can execute a single PowerShell command to unblock multiple files in a directory. Here is the command structure you need to use:

`dir [path] | unblock-file -confirm`

 Just replace**path** in the square brackets with the file path of the directory that has the blocked files. You can grab the file path of the directory by right-clicking on it and selecting**Copy as path** .

![copying file path on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/copy-as-path-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JAkb8Bv3AU4?si=2rHwnZYTzTLieKgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 With the file path handy, follow the instructions below to use the unblock command in PowerShell:

1. Press**Win + S** to open Windows Search.
2. Type**powershell** in the search box and when the program appears in the search results, right-click on it and select**Run as administrator** . For more ways to open it, please read our guide on[ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
3. Enter the unblock command in PowerShell and hit the**Enter** key to run it. This is what it looks like on our computer:  
![entering the unblock file command in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-command.jpg)
4. You will be asked to confirm each file you want to unblock, so type either**Y** for**Yes** or**N** for**No** and hit the**Enter** key. This confirmation step is due to the**\-confirm** portion of the command. It is completely optional, and you can omit it or type**A** to confirm all the files in the directory.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/szUqw4TLvWs?si=srv1OeLOe579gLwj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![confirming files to unblock in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-confirm.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cBCyRXC1-Tw?si=lN9P2xo0hsfyD8K6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 There’s a way you can tell Windows to always trust files you download from the internet. To do that, please read our guide on[how to stop Windows 10 from blocking your downloaded files](https://www.makeuseof.com/stop-windows-10-from-blocking-your-downloaded-files/) . The instructions in the tutorial use the Registry Editor and Local Group Policy Editor, so they should also work on Windows 11.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/O7ChChlyX2o?si=7pMKdN1NZig1kYek" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-files.techidaily.com/new-facebooks-shift-to-short-videos-a-look-into-2023-trends-for-2024/"><u>[New] Facebook's Shift to Short Videos A Look Into 2023 Trends for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-in-2024-engaging-audiences-youtube-shorts-vs-tiktok-trends/"><u>[Updated] In 2024, Engaging Audiences Youtube Shorts Vs. TikTok Trends</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-top-20-unrestricted-zero-cost-pubg-snapshits/"><u>2024 Approved Top 20 Unrestricted, Zero-Cost PUBG Snapshits</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/craft-cartoony-snaps-master-snapchats-anime-filters-guide/"><u>Craft Cartoony Snaps Master Snapchat’s Anime Filters Guide</u></a></li>
<li><a href="https://tech-hub.techidaily.com/expert-tips-for-deleting-every-interaction-youve-had-with-chatgpt/"><u>Expert Tips for Deleting Every Interaction You've Had with ChatGPT</u></a></li>
<li><a href="https://windows11.techidaily.com/implementing-end-task-action-within-windows-11/"><u>Implementing End Task Action Within Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstating-active-conditional-filters-in-windows-mail/"><u>Reinstating Active Conditional Filters in Windows Mail</u></a></li>
<li><a href="https://win-deluxe.techidaily.com/revolutionize-your-outreach-the-top-25-motivations-for-kicking-off-a-newspaper-via-email-using-massmail-technology-201e/"><u>Revolutionize Your Outreach: The Top 25 Motivations for Kicking Off a Newspaper via Email Using Massmail Technology (201E)</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-to-combat-vanished-steam-graphics/"><u>Solutions to Combat Vanished Steam Graphics</u></a></li>
<li><a href="https://windows11.techidaily.com/whats-new-for-windows-11-excitement-from-moment-update-22h2/"><u>What's New for Windows 11? Excitement From Moment Update #22H2</u></a></li>
<li><a href="https://windows11.techidaily.com/window-menus-hidden-potential-in-windows-1011/"><u>Window Menus' Hidden Potential in Windows 10/11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/windows-10-treasures-exciting-new-apps-and-games-await/"><u>Windows 10 Treasures Exciting New Apps & Games Await</u></a></li>
</ul></div>

