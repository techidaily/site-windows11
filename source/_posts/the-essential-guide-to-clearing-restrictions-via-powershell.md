---
title: The Essential Guide to Clearing Restrictions via PowerShell
date: 2024-09-08T19:09:26.140Z
updated: 2024-09-15T16:45:41.003Z
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
<li><a href="https://facebook-video-content.techidaily.com/new-2024-trends-transforming-facebook-ad-campaigns/"><u>[New] 2024 Trends Transforming Facebook Ad Campaigns</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-aviary-creator-searching-for-affordable-filters/"><u>[New] Aviary Creator Searching for Affordable Filters</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-capturing-chats-complete-fbm-conversation-history-for-2024/"><u>[Updated] Capturing Chats Complete FBM Conversation History for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-crafting-engaging-youtube-video-layouts-for-2024/"><u>[Updated] Crafting Engaging YouTube Video Layouts for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/calculating-youtubes-adsense-gains-per-thousand-viewer-income-for-2024/"><u>Calculating Youtube's AdSense Gains Per Thousand Viewer Income for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-info-on-keygen-malware-and-effective-windows-defense-techniques/"><u>Essential Info on Keygen Malware & Effective Windows Defense Techniques</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-erratic-behavior-of-bluetooth-mice-for-windows-11-and-10-users/"><u>Fixing Erratic Behavior of Bluetooth Mice for Windows 11 and 10 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-merge-folders-and-files-in-windows-10-and-11/"><u>How to Merge Folders and Files in Windows 10 and 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-prolong-pin-length-strengthen-windows-11-security/"><u>How to Prolong Pin Length, Strengthen Windows 11 Security</u></a></li>
<li><a href="https://windows11.techidaily.com/perfecting-the-art-of-virtualizing-windows-11-in-vmware/"><u>Perfecting the Art of Virtualizing Windows 11 in VMware</u></a></li>
<li><a href="https://facebook.techidaily.com/tiktoks-user-growth-signals-a-looming-challenge-for-facebook/"><u>TikTok’s User Growth Signals a Looming Challenge for Facebook</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-null-device-error-on-win-11/"><u>Troubleshooting Null Device Error on Win 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/visualize-and-create-with-top-7-innovative-animation-suites/"><u>Visualize & Create with Top 7 Innovative Animation Suites</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/which-pokemon-can-evolve-with-a-moon-stone-for-tecno-spark-20-proplus-drfone-by-drfone-virtual-android/"><u>Which Pokémon can Evolve with a Moon Stone For Tecno Spark 20 Pro+? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/win-strategies-for-persistent-hibernate-issues/"><u>Win Strategies for Persistent Hibernate Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-hello-exposed-is-your-biometric-data-safe/"><u>Windows Hello Exposed: Is Your Biometric Data Safe?</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115910/19272" target="_top" id="2115910">
  <img src="//a.impactradius-go.com/display-ad/19272-2115910" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115910/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

