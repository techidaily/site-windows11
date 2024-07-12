---
title: Reviving Non-Active Thermal Management on PCs
date: 2024-07-11T21:21:41.787Z
updated: 2024-07-12T21:21:41.787Z
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
<li><a href="https://windows11.techidaily.com/navigating-windows-11-calendar-easily/"><u>Navigating Windows 11 Calendar Easily</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-app-on-xiaomi-civi-3-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to Recover Deleted Photos from Android Gallery App on Xiaomi Civi 3</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-precision-best-keyboard-cars-for-windows/"><u>Quick Precision: Best Keyboard Cars for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-unauthorized-geforce-setting-error-on-modern-windows-versions/"><u>Fixing Unauthorized GeForce Setting Error on Modern Windows Versions</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-the-incompatible-gpu-mystery-wins11-and-win10-edition/"><u>Demystifying the Incompatible GPU Mystery: Wins11 & Win10 Edition</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-can-we-unlock-our-oneplus-nord-ce-3-lite-5g-phone-screen-by-drfone-android/"><u>How Can We Unlock Our OnePlus Nord CE 3 Lite 5G Phone Screen?</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-complete-insight-a-detailed-walkthrough-of-facetune-app/"><u>[Updated] Complete Insight  A Detailed Walkthrough of Facetune App</u></a></li>
<li><a href="https://windows11.techidaily.com/reigniting-your-calendars-and-mailboxes-w11-edition/"><u>Reigniting Your Calendars and Mailboxes: W11 Edition</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-with-many-available-video-editing-solutions-in-the-market-today-it-is-a-bit-hard-to-choose-the-best-video-editing-software-for-your-unique-needs/"><u>Updated With Many Available Video Editing Solutions in the Market Today, It Is a Bit Hard to Choose the Best Video Editing Software for Your Unique Needs</u></a></li>
<li><a href="https://discord-videos.techidaily.com/in-2024-evaluating-team-communication-tools-does-slack-outshine-discords-benefits/"><u>In 2024, Evaluating Team Communication Tools  Does Slack Outshine Discord's Benefits?</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-starting-up-mspaint-windows-11-edition/"><u>Step-by-Step Guide: Starting up MSPaint, Windows 11 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/disentangling-compact-icons-on-desktop-shelf/"><u>Disentangling Compact Icons on Desktop Shelf</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-rectify-winscomrssvdll-errors-in-windows-os/"><u>How to Rectify WinscomrssvDLL Errors in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-snipkey-issues-resetting-windows-keys/"><u>Solving SnipKey Issues: Resetting Windows Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/personalize-your-pc-a-guide-to-alomwares-control-options/"><u>Personalize Your PC: A Guide to AlomWare's Control Options</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-sound-for-windows-screencasts-with-powerpoint/"><u>Enabling Sound for Windows Screencasts with PowerPoint</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-file-explorer-crashes-in-newest-windows-11/"><u>Quick Fixes for File Explorer Crashes in Newest Windows 11</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-bring-back-the-memories-top-5-ps1-emulation-apps-for-pc/"><u>[New] In 2024, Bring Back the Memories - Top 5 PS1 Emulation Apps for PC</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-the-essential-camera-toolkit-for-yt-enthusiasts/"><u>In 2024, The Essential Camera Toolkit for YT Enthusiasts</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/fiery-friendship-keeping-your-snapstreak-hot-and-steady-for-2024/"><u>Fiery Friendship  Keeping Your Snapstreak Hot and Steady for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/premier-windows-tools-through-vivetools-advanced-features/"><u>Premier Windows Tools Through ViVeTool's Advanced Features</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-install-android-apks-with-a-double-click-in-windows-11/"><u>How to Install Android APKs With a Double-Click in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-preventing-latency-when-linking-two-monitors/"><u>Guide to Preventing Latency When Linking Two Monitors</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-memory-write-error-windows-fixes/"><u>Disabling 'Memory Write' Error: Windows Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-issues-with-the-epic-games-launcher-for-win-users/"><u>Preventing Issues with the Epic Games Launcher for Win Users</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-harmonize-hues-learning-to-edit-tamil-tracks-for-ringtones/"><u>In 2024, Harmonize Hues  Learning to Edit Tamil Tracks for Ringtones</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/from-raw-footage-to-final-cut-youtube-studio-edition-for-2024/"><u>From Raw Footage to Final Cut  YouTube Studio Edition for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-point-guide-to-achievement-enhancement-in-vintage-titles-via-retroarch/"><u>Step-By Point Guide to Achievement Enhancement in Vintage Titles via Retroarch</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-creating-compelling-instagram-story-collections-for-2024/"><u>[New] Creating Compelling Instagram Story Collections for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-overcome-java-vm-not-found-on-pc/"><u>How to Overcome Java VM Not Found On PC</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/in-2024-the-best-free-online-video-flip-and-rotate-tools/"><u>In 2024, The Best Free Online Video Flip and Rotate Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-winxps-notorious-error-0x80300024/"><u>Fixing WinXP's Notorious Error 0X80300024</u></a></li>
<li><a href="https://windows11.techidaily.com/easing-through-policy-restrictions-in-admin-blocked-installations/"><u>Easing Through Policy Restrictions in Admin-Blocked Installations</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-activate-hyper-v-in-the-latest-windows-os/"><u>How To Activate Hyper-V in the Latest Windows OS</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-undelete-lost-messages-from-motorola-moto-g-5g-2023-by-fonelab-android-recover-messages/"><u>Best Android Data Recovery - Undelete Lost Messages from Motorola Moto G 5G (2023)</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-snipping-tool-keyboard-failures-on-pc/"><u>Fixing Snipping Tool Keyboard Failures on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-your-experience-best-practices-for-reading-qr-codes-in-windows/"><u>Optimizing Your Experience: Best Practices for Reading QR Codes in Windows</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/mastery-of-live-sharing-youtube-edition-for-2024/"><u>Mastery of Live Sharing  YouTube Edition for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/get-immediate-access-to-assistive-features-in-windows/"><u>Get Immediate Access to Assistive Features in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-to-address-windows-network-not-found/"><u>Solutions to Address Windows Network Not Found</u></a></li>
<li><a href="https://windows11.techidaily.com/overcome-stubborn-windows-terminals-a-step-by-step-guide/"><u>Overcome Stubborn Windows Terminals: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-app-instance-identifiers-and-practices/"><u>Exploring App Instance Identifiers and Practices</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-0x80072efd-microsoft-store-error-in-windows-11-and-windows-10/"><u>How to Fix the 0X80072EFD Microsoft Store Error in Windows 11 and Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/precision-installation-microsoft-works-for-modern-windows/"><u>Precision Installation: Microsoft Works for Modern Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/decluttering-your-win11-desktop-wallpaper-symbol/"><u>Decluttering Your Win11 Desktop Wallpaper Symbol</u></a></li>
<li><a href="https://windows11.techidaily.com/from-separate-to-shared-android-pc-harmony-guide/"><u>From Separate to Shared: Android-PC Harmony Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-speed-up-and-conclude-your-puzzled-updates/"><u>How to Speed Up and Conclude Your Puzzled Updates</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/the-guide-to-smart-video-money-making-on-platforms/"><u>The Guide to Smart Video Money-Making on Platforms</u></a></li>
<li><a href="https://windows11.techidaily.com/secretive-startup-strategies-conceal-the-shutdown-command/"><u>Secretive Startup Strategies: Conceal the Shutdown Command</u></a></li>
</ul></div>
