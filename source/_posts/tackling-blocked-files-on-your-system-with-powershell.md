---
title: Tackling Blocked Files on Your System with PowerShell
date: 2024-09-09T11:59:30.925Z
updated: 2024-09-10T11:59:30.925Z
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

<!-- affiliate ads begin -->
<span id="1976998">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1976998.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1976998">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1976998.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1976998%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1976998/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Tackling Blocked Files on Your System with PowerShell

 So you’ve downloaded files onto a directory on your PC, but Windows doesn’t trust them? This is understandable because some files from the internet can harm your computer, but what if you know for sure that the files are safe? Luckily there’s an easy PowerShell command you can use to unblock all of them.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135366/19272" target="_top" id="2135366">
  <img src="//a.impactradius-go.com/display-ad/19272-2135366" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135366/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How Do I Unblock Multiple Files Using PowerShell on Windows?

 You can easily unblock a file by right-clicking on it and going to**Properties** — If you're on Windows 11, you'll need to click**Show more options** first before you can see the**Properties** option in the context menu. And once you're there, select the**General** tab and tick**Unblock** at the bottom in the**Security** section.

![unblocking a file in Properties on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unblock-file-properties-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2132161/7443" target="_top" id="2132161">
  <img src="//a.impactradius-go.com/display-ad/7443-2132161" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2132161/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136615/26400" target="_top" id="2136615">
  <img src="//a.impactradius-go.com/display-ad/26400-2136615" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136615/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![confirming files to unblock in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-confirm.jpg)

<!-- affiliate ads begin -->
<span id="701707">
					<video width="1536" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/701707.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/7443-701707">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/701707.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:960px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fappsumo.8odi.net%2Fc%2F5597632%2F701707%2F7443'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/701707/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 There’s a way you can tell Windows to always trust files you download from the internet. To do that, please read our guide on[how to stop Windows 10 from blocking your downloaded files](https://www.makeuseof.com/stop-windows-10-from-blocking-your-downloaded-files/) . The instructions in the tutorial use the Registry Editor and Local Group Policy Editor, so they should also work on Windows 11.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135394/19272" target="_top" id="2135394">
  <img src="//a.impactradius-go.com/display-ad/19272-2135394" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135394/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://article-helps.techidaily.com/new-2024-approved-cloud-keepers-value-deal-economical-mass-storage/"><u>[New] 2024 Approved Cloud Keepers' Value Deal Economical Mass Storage</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-from-snippets-to-stars-the-essence-of-video-musical-success/"><u>[New] 2024 Approved From Snippets to Stars The Essence of Video Musical Success</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-exploring-photo-deformation-software/"><u>[New] Exploring Photo Deformation Software</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-inventory-a-multitude-of-video-recorders/"><u>[New] Inventory A Multitude of Video Recorders</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-demystifying-the-purpose-what-is-a-blue-image-on-facebook/"><u>[Updated] Demystifying the Purpose What Is a Blue Image on Facebook?</u></a></li>
<li><a href="https://program-issues.techidaily.com/beat-the-bug-blues-fix-alan-wake-2-stability-problems/"><u>Beat the Bug Blues: Fix Alan Wake 2 Stability Problems</u></a></li>
<li><a href="https://howto.techidaily.com/best-methods-for-honor-x50-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Best Methods for Honor X50 Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/build-an-advanced-computing-device-with-asrocks-deskmate-x600-and-nvidia-gpu-a-china-exclusive-opportunity-at-roughly-193-usd/"><u>Build an Advanced Computing Device with ASRock's DeskMate X600 and NVIDIA GPU – A China-Exclusive Opportunity at Roughly $193 USD</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/cleanest-recording-app-ad-aware-edition-for-2024/"><u>Cleanest Recording App - Ad-Aware Edition for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/does-tecno-spark-10-5g-have-find-my-friends-drfone-by-drfone-virtual-android/"><u>Does Tecno Spark 10 5G Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://win-answers.techidaily.com/expert-tips-for-solving-launch-issues-in-armored-core-vi-the-fires-of-rubicon-not-opening-dilemma/"><u>Expert Tips for Solving Launch Issues in Armored Core VI - The 'Fires of Rubicon Not Opening' Dilemma</u></a></li>
<li><a href="https://windows11.techidaily.com/explaining-the-essence-of-windows-reserved-ram/"><u>Explaining the Essence of Windows Reserved RAM</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-windows-iscsi-initiator-functionality/"><u>Exploring Windows iSCSI Initiator Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-common-photo-errors-on-windows-1011/"><u>Fixing Common Photo Errors on Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/get-rid-of-bloatware-in-a-flash-with-windows-11/"><u>Get Rid of Bloatware in a Flash with Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-address-windows-memory-write-faults/"><u>How to Address Windows Memory Write Faults</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-iphone-se-2022-data-from-ios-itunes-backup-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How to Recover iPhone SE (2022) Data From iOS iTunes Backup? | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-instagram-filter-application-guide-tips-and-tricks/"><u>In 2024, Instagram Filter Application Guide - Tips & Tricks</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-spectra-adjustment-suite/"><u>In 2024, Spectra Adjustment Suite</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-ultra-rich-viewable-ventures/"><u>In 2024, Ultra-Rich Viewable Ventures</u></a></li>
<li><a href="https://program-issues.techidaily.com/intersectionality-and-health-an-analysis-of-socioeconomic-status-raceethnicity-and-gender/"><u>Intersectionality and Health: An Analysis of Socioeconomic Status, Race/Ethnicity, and Gender</u></a></li>
<li><a href="https://windows11.techidaily.com/jolly-windows-11-makeover-7-tips-and-tricks/"><u>Jolly Windows 11 Makeover: 7 Tips and Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/recover-missing-audio-configuration-post-windows-updates/"><u>Recover Missing Audio Configuration Post-Windows Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-reversed-alphabet-input-on-windows/"><u>Rectifying Reversed Alphabet Input on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/resurrecting-old-machines-skip-the-windows-path/"><u>Resurrecting Old Machines, Skip the Windows Path</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-dormant-workflow-rules-in-microsoft-outlook/"><u>Reviving Dormant Workflow Rules in Microsoft Outlook</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-missing-windows-update-a-step-by-step-guide/"><u>Reviving Missing Windows Update: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/skillful-art-of-masking-the-search-on-11-taskbar/"><u>Skillful Art of Masking the Search on 11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/snipview-missteps-corrective-strategies-within-reach/"><u>SnipView Missteps? Corrective Strategies Within Reach</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-recurrent-login-issues-with-microsoft-teams/"><u>Solving Recurrent Login Issues with Microsoft Teams</u></a></li>
<li><a href="https://windows11.techidaily.com/stealthy-start-concealing-win11s-power-button-in-start-menu/"><u>Stealthy Start: Concealing Win11's Power Button in Start Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-securely-storing-credentials-in-windows-files/"><u>Step-by-Step: Securely Storing Credentials in Windows Files</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-rectifying-audacitys-audio-access-issue/"><u>Steps for Rectifying Audacity’s Audio Access Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-rectify-windows-activation-error-0x803f700f/"><u>Steps to Rectify Windows Activation Error 0X803f700f</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-windows-configuration-crashes-with-ease/"><u>Stop Windows Configuration Crashes with Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/stopping-unwanted-search-menu-opens-in-win11/"><u>Stopping Unwanted Search Menu Opens in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlined-methods-deleting-saved-wi-fi-in-win-11/"><u>Streamlined Methods: Deleting Saved Wi-Fi in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/strengthening-net-framework-in-windows-max-156/"><u>Strengthening .NET Framework in Windows (Max 156)</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-unresponsive-volume-sliders-on-desktops/"><u>Taming Unresponsive Volume Sliders on Desktops</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-severing-windows-11-connections/"><u>Techniques for Severing Windows 11 Connections</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-conquer-windowsstore-folder-lockdown/"><u>Techniques to Conquer WindowsStore Folder Lockdown</u></a></li>
<li><a href="https://windows11.techidaily.com/the-beginners-walkthrough-to-quick-menu-in-w11/"><u>The Beginner’s Walkthrough to Quick Menu in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-guide-to-systematic-surface-software-updates/"><u>The Essential Guide to Systematic Surface Software Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/the-lost-and-found-getting-windows-10-and-11-back-onscreen/"><u>The Lost and Found: Getting Windows 10 & 11 Back Onscreen</u></a></li>
<li><a href="https://hardware-help.techidaily.com/the-simplest-way-to-get-your-asus-maximus-x-hero-graphics-card-up-to-date-with-driver-upgrades/"><u>The Simplest Way to Get Your ASUS Maximus X Hero Graphics Card Up to Date with Driver Upgrades</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-authentication-issues-in-windows-os/"><u>Troubleshooting Authentication Issues in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-manipulating-windows-files-creation-timestamps/"><u>Understanding & Manipulating Windows Files' Creation Timestamps</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-microsofts-family-safety-features/"><u>Understanding Microsoft's Family Safety Features</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-a-frozen-media-player-in-microsoft-windows-11/"><u>Unlocking a Frozen Media Player in Microsoft Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-your-computers-control-center/"><u>Unlocking Your Computer's Control Center</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-secrets-optimizing-rdc-in-w11/"><u>Unveiling Secrets: Optimizing RDC in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/visual-cplusplus-redistributables-an-overview/"><u>Visual C++ Redistributables: An Overview</u></a></li>
<li><a href="https://windows11.techidaily.com/what-is-the-wacatacbml-trojan-how-to-remove-it-from-windows/"><u>What Is the Wacatac.B!ml Trojan? How to Remove It From Windows</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-google-pixel-8-drfone-by-drfone-virtual-android/"><u>Will Pokémon Go Ban the Account if You Use PGSharp On Google Pixel 8 | Dr.fone</u></a></li>
</ul></div>
