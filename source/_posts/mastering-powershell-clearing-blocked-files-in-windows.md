---
title: "Mastering PowerShell: Clearing Blocked Files in Windows"
date: 2024-11-20T23:52:16.070Z
updated: 2024-11-24T23:21:05.497Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/T-ssCD10v2M?si=WVWGNayUiCAkMZzZ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 But what if you have more than one file you need to unblock? Doing this one by one can get tedious. Alternatively, you can execute a single PowerShell command to unblock multiple files in a directory. Here is the command structure you need to use:

`dir [path] | unblock-file -confirm`

 Just replace**path** in the square brackets with the file path of the directory that has the blocked files. You can grab the file path of the directory by right-clicking on it and selecting**Copy as path** .

![copying file path on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/copy-as-path-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Iz2LYWd8EqI?si=G_3CqFRAmeVPczjj&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 With the file path handy, follow the instructions below to use the unblock command in PowerShell:

1. Press**Win + S** to open Windows Search.
2. Type**powershell** in the search box and when the program appears in the search results, right-click on it and select**Run as administrator** . For more ways to open it, please read our guide on[ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
3. Enter the unblock command in PowerShell and hit the**Enter** key to run it. This is what it looks like on our computer:  
![entering the unblock file command in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-command.jpg)
4. You will be asked to confirm each file you want to unblock, so type either**Y** for**Yes** or**N** for**No** and hit the**Enter** key. This confirmation step is due to the**\-confirm** portion of the command. It is completely optional, and you can omit it or type**A** to confirm all the files in the directory.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/f3PFn06LijE?si=zHrmlTOzrKxXe-k4&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![confirming files to unblock in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-confirm.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YpnYKIrpgZQ?si=94zicAHp1CH-0oso&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 There’s a way you can tell Windows to always trust files you download from the internet. To do that, please read our guide on[how to stop Windows 10 from blocking your downloaded files](https://www.makeuseof.com/stop-windows-10-from-blocking-your-downloaded-files/) . The instructions in the tutorial use the Registry Editor and Local Group Policy Editor, so they should also work on Windows 11.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/odDOPrPjRYY?si=7QHzdUkTPNkHJiVj&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://desktop-recording.techidaily.com/updated-high-definition-excellence-leading-the-recording-race/"><u>[Updated] High Definition Excellence Leading the Recording Race</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-master-commanders-unleashed-ranking-7-total-war-champions-for-2024/"><u>[Updated] Master Commanders Unleashed Ranking 7 Total War Champions for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-racing-hearts-22-short-track-triumph-for-2024/"><u>[Updated] Racing Hearts '22 Short-Track Triumph for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-your-life-your-legacy-youtube-videos-that-matter-for-2024/"><u>[Updated] Your Life, Your Legacy YouTube Videos That Matter. For 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-ff-insider-capture-features/"><u>2024 Approved FF Insider Capture Features</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-windows-11-stumbling-blocks-the-most-crucial-tips/"><u>Avoiding Windows 11 Stumbling Blocks: The Most Crucial Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-error-code-x80131500-at-store/"><u>Breaking Down Error Code: X80131500 at Store</u></a></li>
<li><a href="https://windows11.techidaily.com/digital-dream-team-top-windows-apps-for-a-winning-start/"><u>Digital Dream Team: Top Windows Apps for a Winning Start</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-clutter-software-uninstallation-tricks-for-windows-11-106-chars/"><u>Eliminating Clutter: Software Uninstallation Tricks for Windows 11 (106 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/get-ahead-in-passwords-7-best-free-generation-tools-for-windows/"><u>Get Ahead in Passwords: 7 Best Free Generation Tools for Windows</u></a></li>
<li><a href="https://win-blog.techidaily.com/overcoming-unresponsiveness-in-your-rust-projects-key-insights-and-solutions-for-developers/"><u>Overcoming Unresponsiveness in Your Rust Projects: Key Insights & Solutions for Developers</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/simple-guide-to-converting-your-dvds-to-mkv-format-in-windows-11-and-10/"><u>Simple Guide to Converting Your DVDs to MKV Format in Windows 11 & 10</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-unblock-application-packages-on-windows-servers/"><u>Techniques to Unblock Application Packages on Windows Servers</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-5-car-locator-apps-for-nokia-c210-drfone-by-drfone-virtual-android/"><u>Top 5 Car Locator Apps for Nokia C210 | Dr.fone</u></a></li>
<li><a href="https://win-outstanding.techidaily.com/understanding-page-cannot-be-displayed-errors-and-how-to-fix-them/"><u>Understanding 'Page Cannot Be Displayed' Errors and How To Fix Them</u></a></li>
<li><a href="https://fox-helps.techidaily.com/unleash-the-power-of-engaging-headline-crafting/"><u>Unleash the Power of Engaging Headline Crafting</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-power-of-dism-in-win11-image-management/"><u>Unveiling the Power of Dism in Win11 Image Management</u></a></li>
<li><a href="https://windows11.techidaily.com/why-task-managers-feature-extras-under-edge/"><u>Why Task Managers Feature Extras Under Edge?</u></a></li>
<li><a href="https://windows11.techidaily.com/zeroing-out-bloatware-windows-11-edition/"><u>Zeroing Out Bloatware: Windows 11 Edition</u></a></li>
</ul></div>

