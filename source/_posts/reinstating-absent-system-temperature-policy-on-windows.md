---
title: Reinstating Absent System Temperature Policy on Windows
date: 2025-01-25T18:51:47.435Z
updated: 2025-01-30T00:38:42.692Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reinstating Absent System Temperature Policy on Windows
excerpt: This Article Describes Reinstating Absent System Temperature Policy on Windows
keywords: Windows Temp Policy,Reinstate Temp Rule,WIN_TempPolicy,System Temp Update,Restore WIN Temp,Absent Sys Temp,Temp Rule Enforcement
thumbnail: https://thmb.techidaily.com/46162ff1d50cb6f1b35f044048a0b2464ebecd738e59505ca40bf7c4a2c48673.png
---

## Reinstating Absent System Temperature Policy on Windows

 Normally, you should be able to find and set the system cooling policy in the Power Options menu. However, if you find that it's missing, you can bring it back using PowerShell or by making a simple registry tweak.

Here’s how to do that.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E3yY7lZ-FKA?si=g8VEuExP8GH59B69" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Fix a Missing System Cooling Policy Using PowerShell

 For this method, start by pressing**Win + S** to bring up Windows search. Type**powershell** in the search box and click on**Windows PowerShell** in the search results.

 Next, enter the below command in PowerShell and then hit the**Enter** key to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F -ATTRIB_HIDE`

 Now you can go ahead and set the policy. If you need a refresher on how to do that, please read our guide on[what the Windows system cooling policy is and how to set it](https://www.makeuseof.com/what-is-the-system-cooling-policy-on-windows-and-how-do-you-set-it/) .

![Power Options menu on Windows with the System cooling policy expanded](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-options-windows-system-cooling.jpg)

 If you want to hide it again after you’ve set it, you can enter the following command and then press**Enter** to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F +ATTRIB_HIDE`

 If you go back to the Power Options menu, you’ll find that it’s gone.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/td3ojuzhloY?si=N_maQNiJWrJp7XZl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Fix a Missing System Cooling Policy Using the Windows Registry

 Another way to fix the system cooling policy missing from Power Options is by editing the Windows Registry. Before you proceed, please make a copy of it so you have something to restore if something goes wrong. To do that please read our guide on[how to backup and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

 Next, click on an empty part of the desktop and select**New > Text document** and name it**add-system-cooling-policy.reg** . You’ve basically[created a registry file on Windows](https://www.makeuseof.com/windows-registry-file-guide/) here.

![creating a text document on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-text-doc-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLO5dwmJAVs?si=1OYH8rv8aPaMsCiU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

In the text document, enter the following code:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000002`

 Save the file by clicking**File > Save** . Next, double-click on the registry file and then click**Yes** on the UAC prompt. In the pop-up, click**Yes** to merge the keys and values in the registry file with the Windows Registry.

![message to continue merging a registry file with the windows registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/message-continue-merge-reg-gile.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qObsqoJB9LI?si=ppqxfXzP0UL4J6Tp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You should now see the system cooling policy in the Power Options menu.

 To remove the system cooling policy again after you’ve made your changes, create another registry file named**add-system-cooling-policy.reg** . Then, paste the below text into the document and save it:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000001`

 Once you run this file, the system cooling policy will be hidden again in the Power Options menu.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GPk8_xpN_rA?si=YbAdgsjAKsCn_UsB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://article-knowledge.techidaily.com/new-dial-up-your-digital-influence-nine-simple-steps-on-instagram-for-2024/"><u>[New] Dial Up Your Digital Influence Nine Simple Steps on Instagram for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-fbx-recorder-essentials-for-players/"><u>[New] FBX Recorder Essentials For Players</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-2024-approved-macs-premier-video-to-mp4-converters-guide/"><u>[Updated] 2024 Approved Mac's Premier Video to MP4 Converters Guide</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-vividscreen-record-pro-win-10/"><u>[Updated] In 2024, VividScreen Record Pro (Win 10)</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-analyzing-the-precision-of-yis-4k-actioncam/"><u>In 2024, Analyzing the Precision of Yi's 4K ActionCam</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-windows-with-ease-using-these-5-folder-tips/"><u>Navigate Windows with Ease Using These 5 Folder Tips</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-in-2024-upgrade-your-visuals-the-best-free-online-video-quality-improvers/"><u>New In 2024, Upgrade Your Visuals The Best Free Online Video Quality Improvers</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-iomap64-blue-screen-of-death-in-windows-78/"><u>Overcoming the IOMap64 Blue Screen of Death in Windows 7/8</u></a></li>
<li><a href="https://windows11.techidaily.com/retrospective-on-classic-ratchet-and-clank-reenvisioned-and-revitalized/"><u>Retrospective on Classic Ratchet & Clank Reenvisioned and Revitalized</u></a></li>
<li><a href="https://win11.techidaily.com/slip-through-system-demands-barrier-in-win11/"><u>Slip Through System Demands Barrier in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/stealth-mode-for-windows-11-search-bar-on-taskbar/"><u>Stealth Mode for Windows 11 Search Bar on Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/tactical-approach-to-beat-wows-fatal-132-hurdle/"><u>Tactical Approach to Beat WOW's Fatal #132 Hurdle</u></a></li>
<li><a href="https://windows11.techidaily.com/the-8-best-video-cutting-apps-for-windows-10-and-11/"><u>The 8 Best Video Cutting Apps for Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-artisans-guide-to-win-1011-wall-decorations/"><u>The Artisan's Guide to Win 10/11 Wall Decorations</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/unleashing-productivity-ai-integration-into-docs-and-spreadsheets/"><u>Unleashing Productivity: AI Integration Into Docs & Spreadsheets</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-oneplus-12r-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset OnePlus 12R | Dr.fone</u></a></li>
</ul></div>

