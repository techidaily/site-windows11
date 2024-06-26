---
title: Restoring Lost Thermal Management Directive for PCs
date: 2024-06-25T11:56:54.911Z
updated: 2024-06-26T11:56:54.911Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Lost Thermal Management Directive for PCs
excerpt: This Article Describes Restoring Lost Thermal Management Directive for PCs
keywords: PC ThermoDirect Revise,PC Temp Regulation Fix,Thermal Control Directive,Heat Management Guide,PC Cooling Revision,ThermoSolution PC,PC Temp Directive Update
thumbnail: https://thmb.techidaily.com/0f7cc598462e00e671398d3de2bdb7c71a59af5f2607e912d55b8b85ab2b5c83.jpg
---

## Restoring Lost Thermal Management Directive for PCs

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
<li><a href="https://windows11.techidaily.com/revitalizing-your-stalled-windows-11-mobile-network-connection/"><u>Revitalizing Your Stalled Windows 11 Mobile Network Connection</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-recovery-restoring-the-lost-enhancement-tab-in-windows-11/"><u>Quick Recovery: Restoring the Lost Enhancement Tab in Window's 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-restoring-icon-clarity-on-your-pcs-desktop/"><u>Tips for Restoring Icon Clarity on Your PC's Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/prioritize-and-proliferate-elevating-notifications-in-windows-11/"><u>Prioritize and Proliferate: Elevating Notifications in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-missing-initialization-message-on-windows-pc/"><u>Fixing 'Missing Initialization' Message on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/custom-windows-11-taskbar-placement-hacks/"><u>Custom Windows 11 Taskbar Placement Hacks</u></a></li>
<li><a href="https://windows11.techidaily.com/automate-image-display-7-clever-strategies-for-windows-11/"><u>Automate Image Display: 7 Clever Strategies for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-error-0x887a0006-on-windows-devices/"><u>Addressing Error 0X887A0006 on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-nvidia-control-panel-not-saving-settings-in-windows-11/"><u>How to Fix the NVIDIA Control Panel Not Saving Settings in Windows 11</u></a></li>
<li><a href="https://video-capture.techidaily.com/detailed-ice-cream-snapshot-analysis-report-for-2024/"><u>Detailed Ice Cream Snapshot Analysis Report for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/enhance-visual-harmony-editing-for-instagram-standards-for-2024/"><u>Enhance Visual Harmony  Editing for Instagram Standards for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-online-persona-transformation-rendering-your-cartoon-self/"><u>2024 Approved  Online Persona Transformation  Rendering Your Cartoon Self</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-budget-friendly-top-7-tiktok-edits-for-macos/"><u>[Updated] Budget-Friendly Top 7 TikTok Edits for MacOS</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-experience-beyond-reality-with-these-immersive-titles/"><u>2024 Approved  Experience Beyond Reality with These Immersive Titles</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-shortcuts-to-turn-off-instagrams-igtv/"><u>[Updated] In 2024, Shortcuts to Turn Off Instagram's IGTV</u></a></li>
<li><a href="https://some-tips.techidaily.com/the-definitive-guide-to-googles-podcast-submission-for-2024/"><u>The Definitive Guide to Google’s Podcast Submission for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-a-damaged-video-file-of-realme-narzo-n53-using-video-repair-utility-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair a Damaged video file of Realme Narzo N53 using Video Repair Utility on Mac?</u></a></li>
<li><a href="https://audio-editing.techidaily.com/achieving-pristine-audio-quality-background-noise-elimination-in-imovie-macos-edition-for-2024/"><u>Achieving Pristine Audio Quality Background Noise Elimination in iMovie, macOS Edition for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-the-safe-and-legal-route-to-free-filmora-software/"><u>2024 Approved The Safe and Legal Route to Free Filmora Software</u></a></li>
</ul></div>
