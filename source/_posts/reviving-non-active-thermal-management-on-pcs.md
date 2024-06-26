---
title: Reviving Non-Active Thermal Management on PCs
date: 2024-06-25T12:04:10.815Z
updated: 2024-06-26T12:04:10.815Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reviving Non-Active Thermal Management on PCs
excerpt: This Article Describes Reviving Non-Active Thermal Management on PCs
keywords: Active PC Temp Control,Revive Heat Tech,Thermal Update PC,Hotspot Restoration,PC Cooling Refresh,Non-Active Temp Fix,Rejuvenate PC Thermo
thumbnail: https://thmb.techidaily.com/3c560b5f84950935f235a17f57ab9b2b0c297df9b81f28e15578b876da96606b.jpg
---

## Reviving Non-Active Thermal Management on PCs

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
<li><a href="https://windows11.techidaily.com/eliminate-loadlibrary-error-87-misconfiguration/"><u>Eliminate LoadLibrary Error 87 Misconfiguration</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-overcome-endless-startup-in-bios-for-windows-systems/"><u>Steps to Overcome Endless Startup in BIOS for Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/circumventing-windows-security-controlled-by-domain-admins/"><u>Circumventing Windows Security Controlled by Domain Admins</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-mouse-click-agility-nine-strategies-to-tweak-speeds/"><u>Boost Mouse Click Agility: Nine Strategies to Tweak Speeds</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-vivetool-your-ticket-to-access-latest-windows-innovations/"><u>Discover ViVeTool: Your Ticket to Access Latest Windows Innovations</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-of-file-explorer-opening-tabs-in-windows-11/"><u>Mastery of File Explorer: Opening Tabs in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/newbies-in-the-windows-world-steer-clear-of-these-top-8-faux-pas/"><u>Newbies in the Windows World: Steer Clear of These Top 8 Faux Pas</u></a></li>
<li><a href="https://windows11.techidaily.com/breaching-windows-denied-logins-with-smart-fixes/"><u>Breaching Windows' Denied Logins with Smart Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-offline-errors-for-windows-11s-printer-port/"><u>Resolving Offline Errors for Windows 11'S Printer Port</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-quick-access-shortcuts-adjacent-to-power-in-win11/"><u>Unveiling Quick Access: Shortcuts Adjacent to Power in Win11</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-step-by-step-record-hulu-everywhere-windowsmaciosandroid-for-2024/"><u>[New] Step-by-Step  Record Hulu Everywhere - Windows/Mac/iOS/Android for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/upgrade-clips-adding-effects-to-videos-pcmobile/"><u>Upgrade Clips  Adding Effects to Videos (PC/Mobile)</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-expert-free-fb-image-creator-no-fee/"><u>In 2024, Expert Free FB Image Creator (No Fee)</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-premier-recommendations-the-top-10-sports-apps-for-live-tennis-games/"><u>In 2024, Premier Recommendations  The Top 10 Sports Apps for Live Tennis Games</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-commanders-crown-the-ultimate-ranking-of-7-total-war-classics/"><u>In 2024, Commanders' Crown  The Ultimate Ranking of 7 Total War Classics</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-craft-your-creative-identity-mastering-instagram-photowatermarking/"><u>In 2024, Craft Your Creative Identity  Mastering Instagram Photowatermarking</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-advanced-techniques-for-capturing-high-quality-skype-calls-for-2024/"><u>[New] Advanced Techniques for Capturing High-Quality Skype Calls for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-acethinker-screen-recorder-review/"><u>[Updated] AceThinker Screen Recorder Review</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-downloading-samfw-frp-tool-30-for-vivo-g2-by-drfone-android/"><u>In 2024, Downloading SamFw FRP Tool 3.0 for Vivo G2</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-nokia-g310-drfone-by-drfone-android/"><u>In 2024, How To Use Allshare Cast To Turn On Screen Mirroring On Nokia G310 | Dr.fone</u></a></li>
</ul></div>
