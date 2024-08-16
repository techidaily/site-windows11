---
title: "Optimize & Protect: Enabling PowerShell Script Policy"
date: 2024-08-15T16:10:27.520Z
updated: 2024-08-16T16:10:27.520Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Optimize & Protect: Enabling PowerShell Script Policy"
excerpt: "This Article Describes Optimize & Protect: Enabling PowerShell Script Policy"
keywords: PowerShell Security,Policy-Based Scripting,Secure Scripts,Inline Policies,Script Execution Control,PowerShell Compliance,Enhanced Script Governance
thumbnail: https://thmb.techidaily.com/71f657792ad13f84286b1544671aaf8455260b87c02f1f22e6d755ac15543040.jpg
---

## Optimize & Protect: Enabling PowerShell Script Policy

 iPowerShell, by default, lets you run commands (cmdlets) via its console. To execute a script, you can create a notepad file with the script code, save it with a .ps1 file extension, and execute it via the PowerShell console. You can also directly paste the script onto the console for execution.

 However, if it’s your first time executing a script via PowerShell, you’ll encounter the "running script is disabled" error. By default, script execution on PowerShell is disabled as a security measure to prevent malicious scripts from running on your system. Here we show you the two ways to enable the scrip execution policy on Windows PowerShell.

## How to Check Your Existing Execution Policy

![Powershell set execution policy undefined](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/powershell-set-execcution-policy-undefined.jpg)

 You can use a PowerShell cmdlet to get your current execution policy. Knowing your current execution policy is necessary to know if you need a policy change or not.

To get your current execution policy for the current user:

1. [Open Windows PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. Type the following command in the PowerShell console and hit Enter:  
`get-executionpolicy`
3. Since you have encountered an error when executing the script, the return will likely show**Restricted** as your current execution policy.
4. If you need to view the execution policy for all the supported scopes:  
`get-executionpolicy -list`

 You’ll need to change the execution policy to RemoteSigned to run local scripts without the error. You can change the execution policy from the Settings app and PowerShell.

## How to Enable PowerShell Execution Policy Using the Settings App

 You can change and set the PowerShell execution policy to RemoteSigned using the Settings app. All you have to do is tweak the PowerShell settings in the developers' section to change the execution policy to enable PowerShell script execution.

To change execution policy using Settings:

1. Press**Win + I** to open Se**t** tings.
2. Open the**Privacy & Security** tab in the left pane.
3. Next, click on**For developers.**  
![windows 11 for developers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-for-developers.jpg)
4. Click to expand the**PowerShell** section.
5. Toggle the switch to **change the execution policy to allow local PowerShell scripts to run without signing - Require signing for remote scripts** .  
![enable powershell script execution windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-powershell-script-execution-windows-11-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
6. Once done, open PowerShell, type get**executionpolicy,** and press**Enter** . The execution policy for the current user is now set to**RemoteSigned.**
7. If you need to disable the execution policy, toggle the PowerShell switch and set it to**Off** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
<!-- affiliate ads end -->
## How to Allow Scripts to Run in PowerShell using PowerShell

![Powershell set execcution policy remotesigned](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/powershell-set-execcution-policy-remotesigned.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->

 You can use a [PowerShell cmdlet](https://www.makeuseof.com/windows-powershell-commands-cmdlets/) to set the execution policy to RemoteSigned. The command-line interface makes it easy to change execution policy quickly without using the Settings app.

 Also, the Settings app can only enable or disable the RemoteSigned execution policy. Whereas PowerShell lets you set other policies and scopes as well.

To change the execution policy using PowerShell:

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Set-ExecutionPolicy RemoteSigned`
3. If prompted, press**A** to confirm the action. This will set the**RemoteSigned** execution policy for all users. If you want to set the execution policy for the**Current User** only, use the Scope parameter followed by the username.
4. For example, to set the**RemoteSigned** execution policy for**CurrentUser** , use the following command:  
`Set-ExecutionPolicy RemoteSgined -Scope CurrentUser`
5. Replace**CurrentUser** in the above command with other users (Scope) as per your requirement.

## How to Remove Script Execution Policy Using PowerShell

![set-execution-policy-undefined](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/set-execution-polify-undefined.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->

 If you want to disable script execution, set the execution policy to**Undefined** using th**e Set\_ExecutionPolicy** cmdlet. This is a default state and prevents PowerShell from executing any scripts.

To disable script execution using PowerShell:

1. Open PowerShell with elevated permission.
2. Next, type the following command and press enter to disable script execution for all users:  
`Set-ExecutionPolicy undefined`
3. The above command will set the execution policy default (undefined) for all the users. If you want to disable script execution for a specific scope, use the following command:  
`Set-ExecutionPolicy undefined -Scope CurrentUser`
4. The above command will disable script execution for**CurrentUser** .

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Understanding Execution Policies and Scopes

 Simply put, PowerShell’s execution policy is a policy that controls how PowerShell executes config files and scripts. The intended purpose is to prevent users from accidentally running malicious scripts. The seven PowerShell execution policies are **Default, Restricted, RemoteSigned, AllSigned, Unrestricted, Bypass, and Undefined** .

 The below table briefly explains all the PowerShell execution policies:

| Execution Policy | Enforcement                                                                                                    |
| ---------------- | -------------------------------------------------------------------------------------------------------------- |
| Default          | Sets the default execution policy as Restricted on Windows Client and RemoteSigned on Windows Server.          |
| AllSigned        | Allows execution of publisher signed scripts.                                                                  |
| Bypass           | Unrestricted execution of scripts for larger applications.                                                     |
| RemoteSigned     | Allows locally written script execution. Requires digital signatures for scripts downloaded from the internet. |
| Restricted       | Doesn’t allow script execution, but only individual PowerShell commands.                                       |
| Undefined        | Sets execution policy to Restricted for Windows clients and RemoteSigned for Windows Server.                   |
| Unrestricted     | Allow unsigned script execution with a warning for the scripts downloaded from the internet.                   |

### Execution Policy Scope

 You can set execution policy for a particular scope in PowerShell. The five execution policy scopes are**MachinePolicy, UserPolicy, Process, CurrentUser,** and**LocalMachine** .

The below table briefly explains all the execution policy scopes:

| Execution Policy Scope | Enforcement                                                                              |
| ---------------------- | ---------------------------------------------------------------------------------------- |
| UserPolicy             | Configured by a Group Policy for the current user.                                       |
| Machine Policy         | Configured by a Group Policy for all the users.                                          |
| CurrenUser             | Configured for the current user and stored in HKEY\_CURRENT\_MACHINE registry subkey.    |
| LocalMachine           | Configured for all users and stored in HKEY\_CURRENT\_MACHINE registry subkey.           |
| Process                | Affects current PowerShell session and automatically deleted when the session is closed. |

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->
## Add or Remove PowerShell Script Execution Policy on Windows

 Script execution on PowerShell is disabled by default for Windows clients and set to RemoteSigned for Windows server. Power users, however, can change execution policies to run local, signed, and unsigned PowerShell scripts.

 Alternatively, you can bypass the PowerShell execution policy by pasting the script into a PowerShell console or ECHO your script into PowerShell standard input. This is useful if you want to execute scripts without changing the execution policy.


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
<li><a href="https://youtube-sure.techidaily.com/024-approved-how-to-be-a-youtube-gamer/"><u>[New] 2024 Approved  How To Be a YouTube Gamer</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-a-compilation-of-best-video-chatting-applications-mobilepluspc/"><u>[New] A Compilation of Best Video Chatting Applications (Mobile+PC)</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-building-dynamic-youtube-music-chains/"><u>[New] In 2024, Building Dynamic YouTube Music Chains</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-youtubers-unleashed-a-guide-to-creating-memorable-music-reaction-vids/"><u>[New] In 2024, Youtubers Unleashed  A Guide to Creating Memorable Music Reaction Vids</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-innovative-angles-shooting-vertical-smartphone-panos/"><u>[New] Innovative Angles  Shooting Vertical Smartphone Panos</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-simplified-guide-to-mobile-video-capture/"><u>[New] Simplified Guide to Mobile Video Capture</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-eye-catching-graphic-principles-for-podcast-titles/"><u>[Updated] Eye-Catching Graphic Principles for Podcast Titles</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-toggle-your-youtube-video-with-picture-in-picture-on-ios-for-2024/"><u>[Updated] Toggle Your YouTube Video with Picture-in-Picture on iOS for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-action-spectacular-the-full-t5-camera-review/"><u>2024 Approved  Action Spectacular  The Full T5 Camera Review</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensive-guide-to-using-w11s-auto-hdr/"><u>A Comprehensive Guide to Using W11's Auto HDR</u></a></li>
<li><a href="https://windows11.techidaily.com/biometric-betrayal-how-secure-is-your-windows-hello-lock/"><u>Biometric Betrayal: How Secure Is Your Windows Hello Lock?</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-access-denial-during-system-installation/"><u>Conquering Access Denial During System Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/dont-relininas-chatbots-for-secure-authenticated-win-11-keys/"><u>Don't Relininas Chatbots for Secure, Authenticated Win 11 Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-tasks-initiating-administrative-powershell-on-win11/"><u>Elevate Your Tasks: Initiating Administrative PowerShell on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-email-management-stick-a-new-icon-in-taskbar-border/"><u>Enhance Email Management: Stick a New Icon in Taskbar Border</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-the-glitch-windows-steam-play-links/"><u>Fixing the Glitch: Windows Steam Play Links</u></a></li>
<li><a href="https://windows11.techidaily.com/global-mouse-mastery-using-powertoys-innovative-features/"><u>Global Mouse Mastery Using PowerToys' Innovative Features</u></a></li>
<li><a href="https://howto.techidaily.com/google-play-services-wont-update-12-fixes-are-here-on-oppo-f23-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Google Play Services Wont Update? 12 Fixes are Here on Oppo F23 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/graphics-driver-restart-procedure-in-windows-11/"><u>Graphics Driver Restart Procedure in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-address-not-starting-speech-recognition-in-windows/"><u>How To Address Not Starting Speech Recognition in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-dampen-explore-tabs-in-windows-11-os/"><u>How to Dampen Explore Tabs in Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-stop-the-mouse-from-freezing-in-excel/"><u>How to Stop the Mouse From Freezing in Excel</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-melodic-mosaic-sites-for-classic-phone-chimes/"><u>In 2024, Melodic Mosaic  Sites for Classic Phone Chimes</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-new-multiple-ways-how-to-remove-icloud-activation-lock-from-your-apple-iphone-14-pro-max-by-drfone-ios/"><u>In 2024, New Multiple Ways How To Remove iCloud Activation Lock From your Apple iPhone 14 Pro Max</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/overcoming-common-gs-pitfalls-in-kinemaster-for-2024/"><u>Overcoming Common GS Pitfalls in KineMaster for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-no-audio-capture-in-obs-on-windows-11-pcs/"><u>Overcoming No Audio Capture in OBS on Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/personalized-pixel-panorama-themed-displays-for-each-window-of-win-1011/"><u>Personalized Pixel Panorama: Themed Displays for Each Window of WIN 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/saving-screen-time-by-hushing-file-explorer-tabs/"><u>Saving Screen Time by Hushing File Explorer Tabs</u></a></li>
<li><a href="https://extra-skills.techidaily.com/scrutinizing-the-performance-of-dji-solo-vision-goggles-for-2024/"><u>Scrutinizing the Performance of DJi Solo Vision Goggles for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/shining-spotlight-on-cursors-with-windows-1011/"><u>Shining Spotlight on Cursors with Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-the-typhoon-of-erratic-windows-mouse-wheel/"><u>Taming the Typhoon of Erratic Windows Mouse Wheel</u></a></li>
<li><a href="https://windows11.techidaily.com/taskbar-transformation-minimizing-apps-with-ease-and-speed/"><u>Taskbar Transformation: Minimizing Apps with Ease and Speed</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-10-fingerprint-lock-apps-to-lock-your-tecno-pop-7-pro-phone-by-drfone-android/"><u>Top 10 Fingerprint Lock Apps to Lock Your Tecno Pop 7 Pro Phone</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshoot-asking-too-many-hands-at-once-errors/"><u>Troubleshoot Asking Too Many Hands at Once Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooters-guide-unlocking-photoshop-on-windows-1011/"><u>Troubleshooters' Guide: Unlocking Photoshop on Windows 10/11</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unveiling-truthgpt-the-ai-revolution-elon-musk-is-developing/"><u>Unveiling TruthGPT: The AI Revolution Elon Musk Is Developing</u></a></li>
</ul></div>
