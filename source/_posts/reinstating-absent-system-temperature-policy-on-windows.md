---
title: Reinstating Absent System Temperature Policy on Windows
date: 2024-12-01T20:24:46.219Z
updated: 2024-12-03T20:45:41.724Z
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

## How to Fix a Missing System Cooling Policy Using PowerShell

 For this method, start by pressing**Win + S** to bring up Windows search. Type**powershell** in the search box and click on**Windows PowerShell** in the search results.

 Next, enter the below command in PowerShell and then hit the**Enter** key to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F -ATTRIB_HIDE`

 Now you can go ahead and set the policy. If you need a refresher on how to do that, please read our guide on[what the Windows system cooling policy is and how to set it](https://www.makeuseof.com/what-is-the-system-cooling-policy-on-windows-and-how-do-you-set-it/) .

![Power Options menu on Windows with the System cooling policy expanded](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-options-windows-system-cooling.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K4lRBnNnd9k?si=5e0MbdOz-fF6Ry_k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to hide it again after you’ve set it, you can enter the following command and then press**Enter** to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F +ATTRIB_HIDE`

 If you go back to the Power Options menu, you’ll find that it’s gone.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Un9G2_OdSRI?si=vAcGbco8DuWt4ypP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Fix a Missing System Cooling Policy Using the Windows Registry

 Another way to fix the system cooling policy missing from Power Options is by editing the Windows Registry. Before you proceed, please make a copy of it so you have something to restore if something goes wrong. To do that please read our guide on[how to backup and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

 Next, click on an empty part of the desktop and select**New > Text document** and name it**add-system-cooling-policy.reg** . You’ve basically[created a registry file on Windows](https://www.makeuseof.com/windows-registry-file-guide/) here.

![creating a text document on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-text-doc-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ASUEYpqSP5E?si=0KOZxrTVexTuUkRn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

In the text document, enter the following code:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000002`

 Save the file by clicking**File > Save** . Next, double-click on the registry file and then click**Yes** on the UAC prompt. In the pop-up, click**Yes** to merge the keys and values in the registry file with the Windows Registry.

![message to continue merging a registry file with the windows registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/message-continue-merge-reg-gile.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fZTlPdOFNmo?si=Ym8p7ayV1gtNzzXj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You should now see the system cooling policy in the Power Options menu.

 To remove the system cooling policy again after you’ve made your changes, create another registry file named**add-system-cooling-policy.reg** . Then, paste the below text into the document and save it:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000001`

 Once you run this file, the system cooling policy will be hidden again in the Power Options menu.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HtM7d4dpN1I?si=2vN_xgVGD4eYGORu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-helps.techidaily.com/new-in-2024-the-ultimate-guide-for-ios-album-arrangement-and-icloud-cloud-syncing-mastery/"><u>[New] In 2024, The Ultimate Guide for iOS Album Arrangement & iCloud Cloud Syncing Mastery</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-the-beginners-checklist-8-key-slip-ups-in-youtube-creation/"><u>[New] The Beginner's Checklist 8 Key Slip-Ups in YouTube Creation</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-leading-the-field-in-remotely-recorded-content-creation/"><u>[Updated] 2024 Approved Leading the Field in Remotely Recorded Content Creation</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-elevate-the-visual-appeal-of-your-video-credits-for-2024/"><u>[Updated] Elevate the Visual Appeal of Your Video Credits for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-in-2024-perfecting-playback-apply-filters-to-video-content/"><u>[Updated] In 2024, Perfecting Playback Apply Filters to Video Content</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-enable-quake-mode-in-windows-terminal/"><u>How to Enable Quake Mode in Windows Terminal</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-file-history-setting-glitch-in-windows-os/"><u>Mending File History Setting Glitch in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/precision-in-diagnosis-navigating-through-windows-error-messages-with-command-line-skills/"><u>Precision in Diagnosis: Navigating Through Windows Error Messages with Command Line Skills</u></a></li>
<li><a href="https://windows11.techidaily.com/rewind-and-restore-key-applications-for-changing-createdmodified-dates/"><u>Rewind and Restore: Key Applications for Changing Created/Modified Dates</u></a></li>
<li><a href="https://windows11.techidaily.com/tailor-made-window-ordering-powertoy-guide-to-win-os-snaps/"><u>Tailor-Made Window Ordering: PowerToy Guide to Win OS Snaps</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-shortcut-compendium-windows-narrators-command-guide/"><u>The Ultimate Shortcut Compendium: Windows Narrator's Command Guide</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/unraveling-youtubes-monetization-policy-overhaul-for-2024/"><u>Unraveling YouTube’s Monetization Policy Overhaul for 2024</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/z-edges-value-proposition-unveiling-the-z3-plus-camera-review/"><u>Z-Edge's Value Proposition: Unveiling the Z3 Plus Camera Review</u></a></li>
</ul></div>

