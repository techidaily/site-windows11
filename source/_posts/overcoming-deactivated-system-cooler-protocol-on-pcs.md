---
title: Overcoming Deactivated System Cooler Protocol on PCs
date: 2024-07-11T21:57:25.212Z
updated: 2024-07-12T21:57:25.212Z
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
<li><a href="https://windows11.techidaily.com/windows-audio-issue-methods-to-enable-automatic-system-startup/"><u>Windows Audio Issue: Methods to Enable Automatic System Startup</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-opaque-windows-11-themes-via-registry-manipulation/"><u>Enabling Opaque Windows 11 Themes via Registry Manipulation</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-forth-hidden-5ghz-lans-in-windows-11-fixes-outlined/"><u>Bring Forth Hidden 5GHz LANs in Windows 11 - Fixes Outlined</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-sharpen-aesthetic-focus-learning-border-techniques-for-insta-videos/"><u>[New] 2024 Approved  Sharpen Aesthetic Focus  Learning Border Techniques for Insta-Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-and-remedying-chromes-profile-anomalies/"><u>Unraveling and Remedying Chrome's Profile Anomalies</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tune-automatic-lock-settings-on-pcs/"><u>Fine-Tune Automatic Lock Settings on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/winsplit-a-guide-to-overcome-display-split/"><u>WinSplit: A Guide to Overcome Display Split</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-strategies-how-to-resolve-unison-issues-on-win11/"><u>Winning Strategies: How To Resolve Unison Issues on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/win-error-restoring-lost-or-absent-mfc71udll/"><u>Win Error: Restoring Lost or Absent Mfc71u.dll</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-frp-hijacker-by-hagard-download-and-bypass-your-motorola-moto-g04-frp-locks-by-drfone-android/"><u>In 2024, FRP Hijacker by Hagard Download and Bypass your Motorola Moto G04 FRP Locks</u></a></li>
<li><a href="https://screen-recording.techidaily.com/capturing-with-snap-zoom-guide/"><u>Capturing with Snap  Zoom Guide</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-changefake-your-oppo-a56s-5g-location-on-viber-drfone-by-drfone-virtual-android/"><u>How to Change/Fake Your Oppo A56s 5G Location on Viber | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-bushido-code-continuation-top-similar-game-experiences/"><u>[Updated] In 2024, Bushido Code Continuation - Top Similar Game Experiences</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/understanding-the-duration-required-for-language-mastery/"><u>Understanding the Duration Required for Language Mastery</u></a></li>
<li><a href="https://ai-video.techidaily.com/updated-in-2024-a-brief-review-of-capcut-translate-with-alternative/"><u>updated In 2024, A Brief Review of CapCut Translate With Alternative</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-methods-for-transcribing-audio-to-written-words/"><u>New Methods for Transcribing Audio to Written Words</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-in-2024-techniques-for-creating-animated-logo-that-few-people-know-about/"><u>Updated In 2024, Techniques for Creating Animated Logo That Few People Know About</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-complete-guide-to-adding-texts-to-tiktok/"><u>[Updated] Complete Guide to Adding Texts to TikTok</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-unexpected-security-alerts/"><u>Troubleshooting Windows' Unexpected Security Alerts</u></a></li>
<li><a href="https://windows11.techidaily.com/delaying-windows-10-shutdown-during-running-programs/"><u>Delaying Windows 10 Shutdown During Running Programs</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-steps-to-clean-up-steams-networking-caches/"><u>Easy Steps to Clean Up Steam's Networking Caches</u></a></li>
<li><a href="https://windows11.techidaily.com/bringing-lost-panes-back-top-techniques-for-windows-11/"><u>Bringing Lost Panes Back: Top Techniques for Windows 11</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-expertly-selected-asmr-tools-for-androidios/"><u>[New] 2024 Approved  Expertly Selected ASMR Tools for Android/iOS</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-nubia-z50-ultra-phone-frp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Nubia Z50 Ultra Phone FRP Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/iphoneandroid-as-windows-microphones-guide/"><u>IPhone/Android as Windows Microphones Guide</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/prime-traffic-magnet-design/"><u>Prime Traffic Magnet Design</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-reset-a-locked-vivo-y200e-5g-phone-by-drfone-android/"><u>In 2024, How to Reset a Locked Vivo Y200e 5G Phone</u></a></li>
<li><a href="https://windows11.techidaily.com/bypass-script-failures-windows-script-troubleshooting-guide/"><u>Bypass Script Failures: Windows Script Troubleshooting Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-11-restrictions-a-beginners-guide/"><u>Bypassing Windows 11 Restrictions: A Beginner's Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-elevate-your-old-computer-into-a-windows-11-powerhouse/"><u>How to Elevate Your Old Computer Into a Windows 11 Powerhouse</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-the-top-5-personal-information-harvesters/"><u>Win11: The Top 5 Personal Information Harvesters</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-decision-making-with-microsofts-ai-hub/"><u>Efficient Decision-Making with Microsoft's AI Hub</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-navigate-and-utilize-windows-iscsi-initiator-efficiently/"><u>How to Navigate and Utilize Windows iSCSI Initiator Efficiently</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-undo-unintended-changes-to-mixer-volume-levels/"><u>How to Undo Unintended Changes to Mixer Volume Levels</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-clutter-best-windows-apps-to-disable/"><u>Cutting Clutter: Best Windows Apps to Disable</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/catch-or-beat-sleeping-snorlax-on-pokemon-go-for-motorola-moto-g04-drfone-by-drfone-virtual-android/"><u>Catch or Beat Sleeping Snorlax on Pokemon Go For Motorola Moto G04 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-folder-shuffle-showhide-system-directories/"><u>Windows 11 Folder Shuffle: Show/Hide System Directories</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-bsod-understanding-and-fixing-blue-screen/"><u>Win11 BSOD: Understanding & Fixing Blue Screen</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-simple-steps-for-iphone-screen-capture/"><u>2024 Approved  Simple Steps for iPhone Screen Capture</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-can-i-catch-the-regional-pokemon-without-traveling-on-infinix-hot-40-drfone-by-drfone-virtual-android/"><u>How Can I Catch the Regional Pokémon without Traveling On Infinix Hot 40 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-resolving-windows-service-response-errors/"><u>Guide to Resolving Windows Service Response Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-level-insights-into-windows-non-adjacent-partition-integration/"><u>Expert-Level Insights Into Windows Non-Adjacent Partition Integration</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-ultimate-visual-upgrade-mastery-of-video-enhancer-version-22/"><u>In 2024, Ultimate Visual Upgrade  Mastery of Video Enhancer Version 2.2</u></a></li>
<li><a href="https://windows11.techidaily.com/inside-outlook-and-file-explorers-new-backup-integration-in-windows-11/"><u>Inside Outlook and File Explorer's New Backup Integration in Windows 11</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-free-online-convertors-6-leading-applications-turning-tiktop-to-mp3/"><u>[New] Free Online Convertors  6 Leading Applications Turning TikTop to MP3</u></a></li>
<li><a href="https://windows11.techidaily.com/cleanse-your-search-box-of-windows-graphics/"><u>Cleanse Your Search Box of Windows Graphics</u></a></li>
<li><a href="https://windows11.techidaily.com/apk-quickstart-guide-for-widely-adopted-windows-11/"><u>APK Quickstart Guide for Widely-Adopted Windows 11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-produce-personalized-internet-chuckles/"><u>In 2024, Produce Personalized Internet Chuckles</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-enhancing-your-listening-experience-the-essentials-of-recording-with-audacity-on-mac-for-2024/"><u>[New] Enhancing Your Listening Experience  The Essentials of Recording with Audacity on Mac for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-tips-for-shooting-and-sharing-videos-on-instagram-for-2024/"><u>[Updated] Tips for Shooting & Sharing Videos on Instagram for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/best-options-to-windows-snipper-top-5-alternative-capture-apps/"><u>Best Options to Windows Snipper: Top 5 Alternative Capture Apps</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-maximize-your-gopro-footage-effortless-video-editing-on-macbook-with-quik/"><u>2024 Approved Maximize Your GoPro Footage Effortless Video Editing on MacBook with Quik</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-android-techniques-old-to-new-video-format/"><u>2024 Approved  Android Techniques  Old to New Video Format</u></a></li>
<li><a href="https://windows11.techidaily.com/breaching-windows-denied-logins-with-smart-fixes/"><u>Breaching Windows' Denied Logins with Smart Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-to-windows-arp-cache-and-its-clearance-136-chars-exceeds-limit-adjusted-to-fit-better-clearing-windows-arp/"><u>Essential Guide to Windows ARP Cache and Its Clearance (136 Chars, Exceeds Limit, Adjusted to Fit Better: Clearing Windows ARP</u></a></li>
<li><a href="https://windows11.techidaily.com/bypass-faulty-function-keys-windows-10-fix-guide/"><u>Bypass Faulty Function Keys: Windows 10 Fix Guide</u></a></li>
</ul></div>
