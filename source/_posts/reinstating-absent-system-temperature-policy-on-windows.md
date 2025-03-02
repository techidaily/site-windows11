---
title: Reinstating Absent System Temperature Policy on Windows
date: 2025-02-23T09:50:01.945Z
updated: 2025-03-02T11:17:57.661Z
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
<li><a href="https://facebook-record-videos.techidaily.com/new-mastering-subscriber-identification-on-youtube/"><u>[New] Mastering Subscriber Identification on YouTube</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/antheon-of-youtubes-all-time-highest-views/"><u>[New] Pantheon of YouTube's All-Time Highest Views</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-lg-ultrafine-4k-monitor-complete-review/"><u>[Updated] In 2024, LG UltraFine 4K Monitor Complete Review</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-mastering-luts-unlocking-color-grading-in-ar-and-vfx/"><u>2024 Approved Mastering LUTs Unlocking Color Grading in AR & VFX</u></a></li>
<li><a href="https://hardware-help.techidaily.com/canon-mx49eb-printer-driver-updates-available-seamless-compatibility-with-windows-operating-systems/"><u>Canon MX49eb Printer Driver Updates Available - Seamless Compatibility with Windows Operating Systems</u></a></li>
<li><a href="https://fox-search.techidaily.com/free-aspnet-design-assets-and-starter-kits-from-creative-tim-get-inspired/"><u>Free ASP.NET Design Assets & Starter Kits From Creative Tim - Get Inspired!</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-achieving-maximum-comfort-in-vr-landscape/"><u>In 2024, Achieving Maximum Comfort in VR Landscape</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-art-of-cross-border-mouse-glance-using-powertoys-features/"><u>Master the Art of Cross-Border Mouse Glance Using PowerToys' Features</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-subsystem-top-practices-in-wsl-2-environments/"><u>Master the Subsystem: Top Practices in WSL 2 Environments</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-nvidia-connections-problems-on-win-11-os/"><u>Navigating Through NVIDIA Connections Problems on Win 11 OS</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-make-unforgettable-highlights-top-picks-for-desktop-and-mobile/"><u>New Make Unforgettable Highlights Top Picks for Desktop and Mobile</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-hardware-limitations-in-windows-capture-errors/"><u>Overcoming Hardware Limitations in Windows Capture Errors</u></a></li>
<li><a href="https://howto.techidaily.com/realme-12-proplus-5g-bootloop-problem-how-to-fix-it-without-data-loss-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Realme 12 Pro+ 5G Bootloop Problem, How to Fix it Without Data Loss | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstallation-strategies-for-lost-render-device-in-ow2/"><u>Reinstallation Strategies for Lost Render Device in OW2</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-xc0f1103f-error-with-nvidias-software/"><u>Remedying XC0F1103F Error with NVIDIA's Software</u></a></li>
<li><a href="https://windows11.techidaily.com/reveling-in-windows-11s-covert-bar-locator/"><u>Reveling in Windows 11'S Covert Bar Locator</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-app-overload-understanding-and-resolving-windows-0x80860010/"><u>Tackling App Overload: Understanding and Resolving Windows 0X80860010</u></a></li>
<li><a href="https://windows11.techidaily.com/the-8-best-video-cutting-apps-for-windows-11-and-11/"><u>The 8 Best Video Cutting Apps for Windows 11 & 11</u></a></li>
<li><a href="https://win-premium.techidaily.com/verstanden-was-bedeutet-die-fehler-404-meldung-in-der-aomei-backupper-software/"><u>Verstanden? Was Bedeutet Die 'Fehler 404' Meldung in Der AOMEI Backupper-Software?</u></a></li>
</ul></div>

