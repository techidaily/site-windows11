---
title: "Mastering PowerShell: Clearing Blocked Files in Windows"
date: 2024-09-29T18:17:24.513Z
updated: 2024-10-01T22:26:16.502Z
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
<span id="1977032">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977032.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977032">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977032.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977032%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977032/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://eaxpv-info.techidaily.com/new-from-novice-to-vlogger-the-top-10-editing-techniques-for-2024/"><u>[New] From Novice to Vlogger The Top 10 Editing Techniques for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-unlock-the-full-potential-of-your-gadgets-to-record-youtube-live/"><u>[Updated] 2024 Approved Unlock the Full Potential of Your Gadgets to Record YouTube Live</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-boosting-income-smart-strategies-for-profit-from-youtube-mobile-content/"><u>[Updated] In 2024, Boosting Income Smart Strategies for Profit From YouTube Mobile Content</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-virtual-meetups-made-simple-setting-up-video-calls-with-whatsapp-on-your-laptop/"><u>[Updated] Virtual Meetups Made Simple Setting up Video Calls with WhatsApp on Your Laptop</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-financial-flourishing-yielding-higher-returns-with-mobile-youtube-content/"><u>2024 Approved Financial Flourishing Yielding Higher Returns with Mobile YouTube Content</u></a></li>
<li><a href="https://windows11.techidaily.com/amplify-windows-efficiency-with-innovative-layouts/"><u>Amplify Windows Efficiency with Innovative Layouts</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-up-your-pc-set-auto-update-plus-modify-amd-video/"><u>Boost Up Your PC: Set Auto Update + Modify AMD Video</u></a></li>
<li><a href="https://windows11.techidaily.com/bridging-gaps-quick-fixes-for-microsoft-to-do-discrepancies/"><u>Bridging Gaps: Quick Fixes for Microsoft To Do Discrepancies</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-scripts-not-active-top-4-fixes-to-powershell-load-issue/"><u>Bypassing 'Scripts Not Active': Top 4 Fixes to PowerShell Load Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-overview-how-to-optimize-w11s-auto-hdr/"><u>Comprehensive Overview: How to Optimize W11's Auto HDR</u></a></li>
<li><a href="https://windows11.techidaily.com/construct-ai-driven-artistry-with-win11-and-paint-tool-sai-your-ultimate-guide-to-image-creation/"><u>Construct AI-Driven Artistry with Win11 & Paint Tool SAI: Your Ultimate Guide to Image Creation</u></a></li>
<li><a href="https://windows11.techidaily.com/cybersecurity-commandments-winning-access-prevention-on-windows/"><u>Cybersecurity Commandments: Winning Access Prevention on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-high-cpu-demands-the-case-for-vanguards-ums-optimization/"><u>Deciphering High CPU Demands: The Case for Vanguard's UMS Optimization</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-windows-allocation-strategy-for-reserve-memory/"><u>Demystifying Windows' Allocation Strategy for Reserve Memory</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-netflix-location-to-get-more-country-version-on-nokia-c12-drfone-by-drfone-virtual-android/"><u>How to Change Netflix Location to Get More Country Version On Nokia C12 | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-audio-craftsmanship-weaving-voiceovers-into-visual-tapestries/"><u>In 2024, Audio Craftsmanship Weaving Voiceovers Into Visual Tapestries</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fixing-foneazy-mockgo-not-working-on-honor-magic-6-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Fixing Foneazy MockGo Not Working On Honor Magic 6 Pro | Dr.fone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-free-avi-video-rotators-compared-top-5-choices/"><u>In 2024, Free AVI Video Rotators Compared Top 5 Choices</u></a></li>
<li><a href="https://extra-resources.techidaily.com/the-ultimate-monitor-list-for-an-immersive-xbox-series-x-experience/"><u>The Ultimate Monitor List for an Immersive Xbox Series X Experience</u></a></li>
</ul></div>

