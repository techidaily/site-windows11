---
title: Overcoming Deactivated System Cooler Protocol on PCs
date: 2025-02-28T19:13:11.490Z
updated: 2025-03-02T01:33:43.355Z
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

 Now you can go ahead and set the policy. If you need a refresher on how to do that, please read our guide on [what the Windows system cooling policy is and how to set it](https://www.makeuseof.com/what-is-the-system-cooling-policy-on-windows-and-how-do-you-set-it/) .

![Power Options menu on Windows with the System cooling policy expanded](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-options-windows-system-cooling.jpg)

 If you want to hide it again after you’ve set it, you can enter the following command and then press**Enter** to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F +ATTRIB_HIDE`

 If you go back to the Power Options menu, you’ll find that it’s gone.

## How to Fix a Missing System Cooling Policy Using the Windows Registry

 Another way to fix the system cooling policy missing from Power Options is by editing the Windows Registry. Before you proceed, please make a copy of it so you have something to restore if something goes wrong. To do that please read our guide on [how to backup and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

 Next, click on an empty part of the desktop and select**New > Text document** and name it**add-system-cooling-policy.reg** . You’ve basically [created a registry file on Windows](https://www.makeuseof.com/windows-registry-file-guide/) here.

![creating a text document on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-text-doc-windows-11.jpg)

In the text document, enter the following code:

`Windows Registry Editor Version 5.00 [HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000002`

 Save the file by clicking**File > Save** . Next, double-click on the registry file and then click**Yes** on the UAC prompt. In the pop-up, click**Yes** to merge the keys and values in the registry file with the Windows Registry.

![message to continue merging a registry file with the windows registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/message-continue-merge-reg-gile.jpg)

 You should now see the system cooling policy in the Power Options menu.

 To remove the system cooling policy again after you’ve made your changes, create another registry file named**add-system-cooling-policy.reg** . Then, paste the below text into the document and save it:

`Windows Registry Editor Version 5.00 [HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000001`

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
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-side-by-side-display-logging/"><u>[New] In 2024, Side-by-Side Display Logging</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-hp-printer-driver-is-unavailable-on-windows-1110/"><u>[Solved] HP Printer Driver Is Unavailable on Windows 11/10</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-navigating-the-lands-marketplace-of-product-sponsored-youtube-content/"><u>2024 Approved Navigating the Lands Marketplace of Product-Sponsored YouTube Content</u></a></li>
<li><a href="https://facebook.techidaily.com/deletion-or-memories-managing-late-loved-ones-virtual-footprints/"><u>Deletion or Memories - Managing Late Loved Ones' Virtual Footprints</u></a></li>
<li><a href="https://win-popular.techidaily.com/extend-the-life-of-your-windows-e-pc-for-zero-or-low-cost-essential-tips-from-zdnet/"><u>Extend the Life of Your Windows E PC for Zero or Low Cost - Essential Tips From ZDNet</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-activate-and-use-life360-ghost-mode-on-nokia-g42-5g-drfone-by-drfone-virtual-android/"><u>How To Activate and Use Life360 Ghost Mode On Nokia G42 5G | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-teach-you-to-transfer-files-from-samsung-galaxy-s24-ultra-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways To Teach You To Transfer Files from Samsung Galaxy S24 Ultra to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-browser-management-in-windows/"><u>Mastering the Art of Browser Management in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-repair-of-windows-hyper-v-error-0x8009030e/"><u>Mastering the Repair of Windows Hyper-V Error 0X8009030E</u></a></li>
<li><a href="https://fox-glue.techidaily.com/mastery-over-picture-in-picture-for-improved-productivity-for-2024/"><u>Mastery over Picture In Picture for Improved Productivity for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/power-up-windows-for-video-on-demand-via-dynamic-transcoding-by-tdarr/"><u>Power Up Windows for Video-on-Demand via Dynamic Transcoding by Tdarr</u></a></li>
<li><a href="https://windows11.techidaily.com/preparing-your-devices-for-a-win-11-app-transfer-transition/"><u>Preparing Your Devices for a Win 11 App Transfer Transition</u></a></li>
<li><a href="https://windows11.techidaily.com/record-games-like-a-pro-with-windows-and-intels-command-center/"><u>Record Games Like a Pro with Windows & Intel's Command Center</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-for-color-discrepanenas-of-store-interface/"><u>Remedy for Color Discrepanenas of Store Interface</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/section-3b-five-facts-to-remember-about-systolic-dysfunction-in-hfref/"><u>Section 3B: Five Facts to Remember About Systolic Dysfunction in HFrEF</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-obs-errors-unknown-failure-recorded/"><u>Troubleshooting OBS Errors: Unknown Failure Recorded</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-microsoft-store-app-in-windows-11-os/"><u>Unlocking Microsoft Store App in Windows 11 OS</u></a></li>
</ul></div>

