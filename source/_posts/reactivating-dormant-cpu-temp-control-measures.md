---
title: Reactivating Dormant CPU Temp Control Measures
date: 2024-12-29T17:22:04.167Z
updated: 2025-01-03T16:01:45.821Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reactivating Dormant CPU Temp Control Measures
excerpt: This Article Describes Reactivating Dormant CPU Temp Control Measures
keywords: CPU Temp Management,Reactivate Temp Controls,Dormant Temp Fixes,CPU Cooling Strategies,Enhance CPU Temp Regulation,Restore CPU Thermal Limits,Resume CPU Temperature Control
thumbnail: https://thmb.techidaily.com/20c1b79c602928e68eb827f2805a2d6c02102230fc6f02657f8a03a2a51b45e9.jpg
---

## Reactivating Dormant CPU Temp Control Measures

 Normally, you should be able to find and set the system cooling policy in the Power Options menu. However, if you find that it's missing, you can bring it back using PowerShell or by making a simple registry tweak.

Here’s how to do that.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/O7ChChlyX2o?si=7pMKdN1NZig1kYek" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Fix a Missing System Cooling Policy Using PowerShell

 For this method, start by pressing**Win + S** to bring up Windows search. Type**powershell** in the search box and click on**Windows PowerShell** in the search results.

 Next, enter the below command in PowerShell and then hit the**Enter** key to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F -ATTRIB_HIDE`

 Now you can go ahead and set the policy. If you need a refresher on how to do that, please read our guide on[what the Windows system cooling policy is and how to set it](https://www.makeuseof.com/what-is-the-system-cooling-policy-on-windows-and-how-do-you-set-it/) .

![Power Options menu on Windows with the System cooling policy expanded](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-options-windows-system-cooling.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pGHmqD53gc8?si=ymgHIB6Aa7_MoUUf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to hide it again after you’ve set it, you can enter the following command and then press**Enter** to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F +ATTRIB_HIDE`

 If you go back to the Power Options menu, you’ll find that it’s gone.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/slm2NjVPNtk?si=9ow6g1ucmf0TnT4T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Fix a Missing System Cooling Policy Using the Windows Registry

 Another way to fix the system cooling policy missing from Power Options is by editing the Windows Registry. Before you proceed, please make a copy of it so you have something to restore if something goes wrong. To do that please read our guide on[how to backup and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

 Next, click on an empty part of the desktop and select**New > Text document** and name it**add-system-cooling-policy.reg** . You’ve basically[created a registry file on Windows](https://www.makeuseof.com/windows-registry-file-guide/) here.

![creating a text document on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-text-doc-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0nGlyEL5K6Y?si=3KZhTTBvKcPmyS68" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

In the text document, enter the following code:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000002`

 Save the file by clicking**File > Save** . Next, double-click on the registry file and then click**Yes** on the UAC prompt. In the pop-up, click**Yes** to merge the keys and values in the registry file with the Windows Registry.

![message to continue merging a registry file with the windows registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/message-continue-merge-reg-gile.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KF793jv1LIc?si=fJOogQJ2f8JUfTzZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://youtube-webster.techidaily.com/n-2024-skyrocket-views-mastery-of-title-and-tag-optimization/"><u>[New] In 2024, Skyrocket Views Mastery of Title and Tag Optimization</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-twitch-writers-picks-5-ultimate-cams-for-gameplay-broadcasting/"><u>[Updated] 2024 Approved Twitch' Writers’ Picks 5 Ultimate Cams for Gameplay Broadcasting</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-capture-the-essence-of-xiaomis-latest-smartphones-for-2024/"><u>[Updated] Capture the Essence of Xiaomi's Latest Smartphones for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-convert-and-store-webcam-footage-in-vlc-media-for-2024/"><u>[Updated] Convert & Store Webcam Footage in VLC Media for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-the-standard-edition-review-of-djis-drone-model-3-for-2024/"><u>[Updated] The Standard Edition Review of DJI's Drone Model 3 for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/confronting-the-something-went-awry-message-comprehensive-solutions-for-windows-eon-users/"><u>Confronting the Something Went Awry Message: Comprehensive Solutions for Windows Eon Users</u></a></li>
<li><a href="https://windows11.techidaily.com/hdd-or-ssd-windows-methods-to-identify-storage-disks/"><u>HDD or SSD? Windows Methods to Identify Storage Disks</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-xiaomi-redmi-a2-to-samsung-galaxy-s21-ultra-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos From Xiaomi Redmi A2 to Samsung Galaxy S21 Ultra | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/innovative-finger-movements-win11-keybindings-unveiled/"><u>Innovative Finger Movements: Win11 Keybindings Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/keyboardmouse-wake-issues-in-windows-11/"><u>Keyboard/Mouse Wake Issues in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/master-nddrive-mapping-in-win11-effortlessly/"><u>Master NDDrive Mapping in Win11 Effortlessly</u></a></li>
<li><a href="https://windows11.techidaily.com/master-your-words-real-time-speech-to-text-with-whisper/"><u>Master Your Words: Real-Time Speech-to-Text with Whisper</u></a></li>
<li><a href="https://windows11.techidaily.com/regaining-lost-plans-windows-11-power-reset/"><u>Regaining Lost Plans: Windows 11 Power Reset</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/138624609-9781722520304-the-master-mind-condensed-classics/"><u>The Master Mind (Condensed Classics) | Free Book</u></a></li>
</ul></div>

