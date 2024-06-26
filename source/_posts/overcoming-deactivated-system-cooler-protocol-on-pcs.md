---
title: Overcoming Deactivated System Cooler Protocol on PCs
date: 2024-06-25T12:35:08.096Z
updated: 2024-06-26T12:35:08.096Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Deactivated System Cooler Protocol on PCs
excerpt: This Article Describes Overcoming Deactivated System Cooler Protocol on PCs
keywords: PC Overheat Recovery,Cooler Protocol Fix,System Heatsink Repair,CPU Temp Normalization,Thermal Regulation Reset,Cooling Unit Restore,Fan Speed Control
thumbnail: https://thmb.techidaily.com/b855ebe51b5189358ef7af65d06591503136d0471619c6e6540592a14f8eb424.jpg
---

## Overcoming Deactivated System Cooler Protocol on PCs

 Normally, you should be able to find and set the system cooling policy in the Power Options menu. However, if you find that it's missing, you can bring it back using PowerShell or by making a simple registry tweak.

Here’s how to do that.

## How to Fix a Missing System Cooling Policy Using PowerShell

 For this method, start by pressing**Win + S** to bring up Windows search. Type**powershell** in the search box and click on**Windows PowerShell** in the search results.

 Next, enter the below command in PowerShell and then hit the**Enter** key to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F -ATTRIB_HIDE`

 Now you can go ahead and set the policy. If you need a refresher on how to do that, please read our guide on[what the Windows system cooling policy is and how to set it](https://www.makeuseof.com/what-is-the-system-cooling-policy-on-windows-and-how-do-you-set-it/) .

![Power Options menu on Windows with the System cooling policy expanded](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-options-windows-system-cooling.jpg)

 If you want to hide it again after you’ve set it, you can enter the following command and then press**Enter** to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F +ATTRIB_HIDE`

 If you go back to the Power Options menu, you’ll find that it’s gone.

## How to Fix a Missing System Cooling Policy Using the Windows Registry

 Another way to fix the system cooling policy missing from Power Options is by editing the Windows Registry. Before you proceed, please make a copy of it so you have something to restore if something goes wrong. To do that please read our guide on[how to backup and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

 Next, click on an empty part of the desktop and select**New > Text document** and name it**add-system-cooling-policy.reg** . You’ve basically[created a registry file on Windows](https://www.makeuseof.com/windows-registry-file-guide/) here.

![creating a text document on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-text-doc-windows-11.jpg)

In the text document, enter the following code:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000002`

 Save the file by clicking**File > Save** . Next, double-click on the registry file and then click**Yes** on the UAC prompt. In the pop-up, click**Yes** to merge the keys and values in the registry file with the Windows Registry.

![message to continue merging a registry file with the windows registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/message-continue-merge-reg-gile.jpg)

 You should now see the system cooling policy in the Power Options menu.

 To remove the system cooling policy again after you’ve made your changes, create another registry file named**add-system-cooling-policy.reg** . Then, paste the below text into the document and save it:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000001`

 Once you run this file, the system cooling policy will be hidden again in the Power Options menu.

## Bringing Back the System Cooling Policy on Windows

 Now that the system cooling policy has returned you can tweak it to your liking. We have even shown you how to hide it again in case you don’t want others messing with it. If these methods don’t work, you might have another problem with your computer.


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
<li><a href="https://windows11.techidaily.com/claim-your-potential-in-windows-11-regain-missing-system-upgrades/"><u>Claim Your Potential in Windows 11: Regain Missing System Upgrades</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-microsoft-store-crash-error-0x800704cf/"><u>Tackling Microsoft Store Crash: Error 0X800704CF</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-resource-monitor-app-when-its-not-working-on-windows-11/"><u>How to Fix the Resource Monitor App When It's Not Working on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-code-0x0001-failures-for-nvidia-ge-in-w10w11/"><u>Rectifying Code 0X0001 Failures for Nvidia GE in W10/W11</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-screenscape-designing-distinctive-displays-on-each-window-of-win-1011/"><u>Tailored Screenscape: Designing Distinctive Displays on Each Window of Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-missing-sign-in-screens-in-windows-11/"><u>Bypassing Missing Sign-In Screens in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-obs-troubleshooting-techniques-for-win-11-users/"><u>Mastering OBS Troubleshooting Techniques for Win 11 Users</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-master-your-screen-time-top-10-in-depth-guide-to-excellent-offline-ios-gaming/"><u>In 2024, Master Your Screen Time - Top 10 In-Depth Guide to Excellent Offline iOS Gaming</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-the-adventurers-manual-how-to-dive-into-less-conventional-discord-communities/"><u>[Updated] 2024 Approved  The Adventurer's Manual  How to Dive Into Less Conventional Discord Communities</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-ace-windows-10-tricks-to-save-time-and-energy/"><u>2024 Approved  Ace Windows 10 Tricks to Save Time & Energy</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-best-in-class-evaluating-the-top-8-sub-to-srt-convertors/"><u>[Updated] The Best in Class  Evaluating the Top 8 Sub to SRT Convertors</u></a></li>
<li><a href="https://techidaily.com/the-way-to-recover-deleted-pictures-on-asus-rog-phone-7-ultimate-without-backup-by-fonelab-android-recover-pictures/"><u>The way to recover deleted pictures on Asus ROG Phone 7 Ultimate without backup.</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/how-to-exclude-unwanted-sounds-in-your-recordings-using-audacity/"><u>How to Exclude Unwanted Sounds in Your Recordings Using Audacity</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-evaluating-screen-recording-vsdc-reviewed-plus-competitors-spotlight-for-2024/"><u>[New] Evaluating Screen Recording  VSDC Reviewed + Competitors Spotlight for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-best-zoom-tools-for-clear-session-capture-for-2024/"><u>[Updated] Best Zoom Tools for Clear Session Capture for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-boost-focus-and-style-with-top-rated-frames-in-ig-photography-for-2024/"><u>[New] Boost Focus & Style with Top-Rated Frames in IG Photography for 2024</u></a></li>
</ul></div>
