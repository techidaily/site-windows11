---
title: The Essential Guide to Clearing Restrictions via PowerShell
date: 2024-10-14T04:01:09.180Z
updated: 2024-10-18T22:07:27.303Z
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118319/7443" target="_top" id="2118319">
  <img src="//a.impactradius-go.com/display-ad/7443-2118319" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118319/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-from-ordinary-to-extraordinary-transform-your-facebook-profile-with-these-tips/"><u>[New] In 2024, From Ordinary to Extraordinary Transform Your Facebook Profile with These Tips</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-optimize-your-time-pick-the-fastest-5-chrome-addons-for-facebook-vids-for-2024/"><u>[New] Optimize Your Time Pick the Fastest 5 Chrome Addons for Facebook Vids for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-agribuddy-games-celebrating-camaraderie-on-the-farm-for-2024/"><u>[Updated] AgriBuddy Games Celebrating Camaraderie on the Farm for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/1725287610336-windows-1011/"><u>破除传统：发现Windows 10/11的高效媒体中心替代品 - 详解</u></a></li>
<li><a href="https://screen-capture.techidaily.com/essential-mc-stronghold-constructions/"><u>Essential MC Stronghold Constructions</u></a></li>
<li><a href="https://windows11.techidaily.com/guaranteeing-presence-of-startup-applications/"><u>Guaranteeing Presence of Startup Applications</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-top-7-skype-hacker-to-hack-any-skype-account-on-your-xiaomi-redmi-note-13-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Top 7 Skype Hacker to Hack Any Skype Account On your Xiaomi Redmi Note 13 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/lost-thumbnail-images-on-windows-11-a-step-by-step-resolution/"><u>Lost Thumbnail Images on Windows 11: A Step-by-Step Resolution</u></a></li>
<li><a href="https://windows11.techidaily.com/personalizing-permanent-trash-settings-in-windows-1011/"><u>Personalizing Permanent Trash Settings in Windows 10/11</u></a></li>
<li><a href="https://buynow-help.techidaily.com/the-essential-guide-to-choosing-between-a-kindle-and-fire-tablet/"><u>The Essential Guide to Choosing Between a Kindle and Fire Tablet</u></a></li>
<li><a href="https://windows11.techidaily.com/the-hidden-value-in-preserving-your-windows-11-notification-alerts/"><u>The Hidden Value in Preserving Your Windows 11 Notification Alerts</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-accessing-photos-via-windows-11s-explorer/"><u>Tips for Accessing Photos via Windows 11'S Explorer</u></a></li>
<li><a href="https://fox-that.techidaily.com/1721464419600-vpn-wont-connect-to-your-iphone-learn-how-to-solve-it-with-7-tips/"><u>VPN Won't Connect to Your iPhone? Learn How to Solve It With 7 Tips!</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-arm-setup-via-iso-file-instructions-inside/"><u>Windows 11 ARM Setup Via ISO File - Instructions Inside</u></a></li>
</ul></div>

