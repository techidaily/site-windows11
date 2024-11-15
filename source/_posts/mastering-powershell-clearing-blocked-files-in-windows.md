---
title: "Mastering PowerShell: Clearing Blocked Files in Windows"
date: 2024-11-11T17:11:48.531Z
updated: 2024-11-15T16:20:20.301Z
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
<a href="https://appsumo.8odi.net/c/5597632/2075483/7443" target="_top" id="2075483">
  <img src="//a.impactradius-go.com/display-ad/7443-2075483" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075483/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-glue.techidaily.com/new-global-industrys-biggest-uav-lifters-the-ultimate-list/"><u>[New] Global Industry's Biggest UAV Lifters The Ultimate List</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-cutting-down-video-lengths-the-ultimate-mac-guide-for-insta/"><u>2024 Approved Cutting Down Video Lengths The Ultimate Mac Guide for Insta</u></a></li>
<li><a href="https://os-tips.techidaily.com/complete-guide-sharing-your-creations-with-ease-a-step-by-step-instagram-posting-tutorial/"><u>Complete Guide: Sharing Your Creations with Ease - A Step-by-Step Instagram Posting Tutorial</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/in-2024-googles-ar-sticker-innovation-an-inside-look-and-alternatives/"><u>In 2024, Google's AR Sticker Innovation An Inside Look & Alternatives</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-streamlabs-competitors-in-the-livestream-arena/"><u>In 2024, Streamlabs' Competitors in the Livestream Arena</u></a></li>
<li><a href="https://windows11.techidaily.com/lost-features-a-step-by-step-guide-to-find-windows-11s-enhancement/"><u>Lost Features? A Step-by-Step Guide to Find Windows 11'S Enhancement</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-elevate-your-storytelling-a-guide-to-making-videos-with-photos-and-music/"><u>New Elevate Your Storytelling A Guide to Making Videos with Photos and Music</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-failed-task-runner-in-windows/"><u>Overcoming Failed Task Runner in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-microsofts-dism-hurdle-code-0x800f082f/"><u>Overcoming Microsoft's DISM Hurdle: Code 0X800F082F</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-solution-fixing-try-connecting-your-device-on-win-11/"><u>Quick Solution: Fixing 'Try Connecting Your Device' On Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstating-default-organization-of-windows-files/"><u>Reinstating Default Organization of Windows Files</u></a></li>
<li><a href="https://some-approaches.techidaily.com/synergizing-brands-on-video-platforms-for-2024/"><u>Synergizing Brands on Video Platforms for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-opening-windows-stubborn-folders-on-double-click/"><u>The Ultimate Guide: Opening Windows' Stubborn Folders on Double-Click</u></a></li>
<li><a href="https://windows11.techidaily.com/turning-offlight-on-notepadwindows/"><u>Turning Offlight On NotepadWindows</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/uniting-the-world-of-learning-betts-mission/"><u>Uniting the World of Learning - BETT's Mission</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/unlock-the-secrets-to-building-utopian-metropolises-with-cities-skylines-reviewed/"><u>Unlock the Secrets to Building Utopian Metropolises with Cities: Skylines Reviewed!</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-puzzle-of-windows-subsystem-for-linux-error-4294967295/"><u>Unraveling the Puzzle of Windows Subsystem for Linux Error 4294967295</u></a></li>
</ul></div>

