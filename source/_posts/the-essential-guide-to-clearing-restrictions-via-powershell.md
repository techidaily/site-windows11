---
title: The Essential Guide to Clearing Restrictions via PowerShell
date: 2025-02-05T01:57:12.196Z
updated: 2025-02-10T23:34:40.570Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/97ydpSmzTJw?si=tFcelmtQX4u-b3u5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Do I Unblock Multiple Files Using PowerShell on Windows?

 You can easily unblock a file by right-clicking on it and going to**Properties** — If you're on Windows 11, you'll need to click**Show more options** first before you can see the**Properties** option in the context menu. And once you're there, select the**General** tab and tick**Unblock** at the bottom in the**Security** section.

![unblocking a file in Properties on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unblock-file-properties-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/it8VkxDUdAc?si=ef6VZWR7kW4P9ikh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 But what if you have more than one file you need to unblock? Doing this one by one can get tedious. Alternatively, you can execute a single PowerShell command to unblock multiple files in a directory. Here is the command structure you need to use:

`dir [path] | unblock-file -confirm`

 Just replace**path** in the square brackets with the file path of the directory that has the blocked files. You can grab the file path of the directory by right-clicking on it and selecting**Copy as path** .

![copying file path on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/copy-as-path-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-0Ww1YIIUe4?si=cQ-Gkh9UCJABuPZU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 With the file path handy, follow the instructions below to use the unblock command in PowerShell:

1. Press**Win + S** to open Windows Search.
2. Type**powershell** in the search box and when the program appears in the search results, right-click on it and select**Run as administrator** . For more ways to open it, please read our guide on[ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
3. Enter the unblock command in PowerShell and hit the**Enter** key to run it. This is what it looks like on our computer:  
![entering the unblock file command in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-command.jpg)
4. You will be asked to confirm each file you want to unblock, so type either**Y** for**Yes** or**N** for**No** and hit the**Enter** key. This confirmation step is due to the**\-confirm** portion of the command. It is completely optional, and you can omit it or type**A** to confirm all the files in the directory.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ITtcSWvS8bo?si=4M4BfMgaabrW6148" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![confirming files to unblock in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-confirm.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-crafting-content-for-specific-youtube-subsets/"><u>[New] 2024 Approved Crafting Content for Specific Youtube Subsets</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-23-budget-friendly-methods-document-webinars-with-no-cost/"><u>[Updated] In 2024, 23 Budget-Friendly Methods Document Webinars with No Cost</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-superb-culmination-for-vr-journeys/"><u>[Updated] Superb Culmination for VR Journeys</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-ultimate-guide-to-box-enthusiasm/"><u>2024 Approved The Ultimate Guide to Box Enthusiasm</u></a></li>
<li><a href="https://windows11.techidaily.com/a-guide-to-overcoming-windows-resolution-riddles/"><u>A Guide to Overcoming Windows Resolution Riddles</u></a></li>
<li><a href="https://windows11.techidaily.com/ace-your-win-11-games-with-these-best-fps-tools/"><u>Ace Your Win 11 Games with These Best FPS Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/back-to-basics-windows-11-access-re-establishment-guide/"><u>Back to Basics: Windows 11 Access Re-Establishment Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-control-mastering-local-gpo-access-on-windows-11/"><u>Boosting Control: Mastering Local GPO Access on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/bypass-bottlenecks-9-fixes-for-rapid-windows-verification/"><u>Bypass Bottlenecks: 9 Fixes for Rapid Windows Verification</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-custom-privileges-in-win11-by-default/"><u>Clearing Custom Privileges in Win11 by Default</u></a></li>
<li><a href="https://windows11.techidaily.com/command-line-to-admin-initiating-windows-11s-task-manager-with-power/"><u>Command Line to Admin: Initiating Windows 11'S Task Manager with Power</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-your-own-windows-voice-transcription-software-using-ahk-and-whisper/"><u>Crafting Your Own Windows Voice Transcription Software Using AHK and Whisper</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-the-clutter-soundcard-irq-solutions/"><u>Cutting the Clutter: Soundcard IRQ Solutions</u></a></li>
<li><a href="https://some-approaches.techidaily.com/free-conversion-from-avs-to-mp4-streamline-video-editing-with-online-tools/"><u>Free Conversion From AVS to MP4: Streamline Video Editing with Online Tools</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-10-vivo-t2x-5g-android-sim-unlock-apk-by-drfone-android/"><u>In 2024, Top 10 Vivo T2x 5G Android SIM Unlock APK</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/ring-sound-repeat-a-comprehensible-guide-to-personalization-on-android-devices/"><u>Ring, Sound, Repeat A Comprehensible Guide to Personalization on Android Devices</u></a></li>
<li><a href="https://fox-http.techidaily.com/soothing-soundscapes-recommended-voice-experts/"><u>Soothing Soundscapes Recommended Voice Experts</u></a></li>
<li><a href="https://win-solutions.techidaily.com/the-gamers-guide-to-banishing-stutters-in-your-digital-world-of-high-frame-rates/"><u>The Gamer's Guide to Banishing Stutters in Your Digital World of High Frame Rates</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/the-influence-of-thumbnail-size-on-viewership-numbers/"><u>The Influence of Thumbnail Size on Viewership Numbers</u></a></li>
</ul></div>

