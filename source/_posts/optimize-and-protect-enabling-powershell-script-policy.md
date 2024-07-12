---
title: "Optimize & Protect: Enabling PowerShell Script Policy"
date: 2024-07-11T21:21:30.066Z
updated: 2024-07-12T21:21:30.066Z
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
6. Once done, open PowerShell, type get**executionpolicy,** and press**Enter** . The execution policy for the current user is now set to**RemoteSigned.**
7. If you need to disable the execution policy, toggle the PowerShell switch and set it to**Off** .

## How to Allow Scripts to Run in PowerShell using PowerShell

![Powershell set execcution policy remotesigned](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/powershell-set-execcution-policy-remotesigned.jpg)

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

 If you want to disable script execution, set the execution policy to**Undefined** using th**e Set\_ExecutionPolicy** cmdlet. This is a default state and prevents PowerShell from executing any scripts.

To disable script execution using PowerShell:

1. Open PowerShell with elevated permission.
2. Next, type the following command and press enter to disable script execution for all users:  
`Set-ExecutionPolicy undefined`
3. The above command will set the execution policy default (undefined) for all the users. If you want to disable script execution for a specific scope, use the following command:  
`Set-ExecutionPolicy undefined -Scope CurrentUser`
4. The above command will disable script execution for**CurrentUser** .

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
<li><a href="https://windows11.techidaily.com/reducing-heavy-resource-use-by-news-apps-in-windows-os/"><u>Reducing Heavy Resource Use by News Apps in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/key-steps-unveiled-navigating-disks-in-w10-and-w11-systems/"><u>Key Steps Unveiled: Navigating Disks in W10 & W11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/ignite-vm-speed-and-stability-top-6-methods-to-enhance-in-windows/"><u>Ignite VM Speed and Stability: Top 6 Methods to Enhance in Windows</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-unveiling-the-leading-online-stores-for-customized-gift-boxes/"><u>2024 Approved  Unveiling the Leading Online Stores for Customized Gift Boxes</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-best-xiaomi-redmi-13c-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>In 2024, Best Xiaomi Redmi 13C Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://extra-skills.techidaily.com/spotify-how-to-halt-default-podcast-additions-for-2024/"><u>Spotify  How to Halt Default Podcast Additions for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/integrated-thermal-management-windows-edition/"><u>Integrated Thermal Management: Windows Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-handle-exception-breaking-point-issues-on-pc/"><u>How to Handle Exception Breaking Point Issues on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-1110-how-to-stop-double-click-folders-from-closing/"><u>Fixing Windows 11/10: How to Stop Double-Click Folders From Closing</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-frp-hijacker-by-hagard-download-and-bypass-your-honor-magic-v2-frp-locks-by-drfone-android/"><u>In 2024, FRP Hijacker by Hagard Download and Bypass your Honor Magic V2 FRP Locks</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-use-face-id-to-pay-for-apple-tvplus-on-iphone-6s-plus-by-drfone-ios-unlock-ios-unlock/"><u>How to Use Face ID to Pay for Apple TV+ on iPhone 6s Plus</u></a></li>
<li><a href="https://windows11.techidaily.com/prioritize-your-data-spotting-the-biggest-disk-space-eaters/"><u>Prioritize Your Data: Spotting the Biggest Disk Space Eaters</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-diy-tips-for-instant-custom-youtube-shorts-coverage/"><u>[Updated] 2024 Approved  DIY Tips for Instant Custom YouTube Shorts Coverage</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-progopro-session-series-evolution-for-2024/"><u>[New] ProGoPro Session Series Evolution for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/stay-ahead-of-the-game-top-task-filled-ideas-for-maximizing-your-podcast-experience-for-2024/"><u>Stay Ahead of the Game  Top Task-Filled Ideas for Maximizing Your Podcast Experience for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-alternatives-to-windows-traditional-video-editing/"><u>2024 Approved  Alternatives to WIndows' Traditional Video Editing</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-win11-pointer-adjustments-for-access/"><u>Mastering Win11 Pointer Adjustments for Access</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-unlock-and-reset-restricted-program-status/"><u>How to Unlock and Reset Restricted Program Status</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-troubleshooting-excel-display-issue-in-notepad/"><u>Remedy: Troubleshooting Excel Display Issue in Notepad</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-exploring-costless-alternatives-including-songs-in-video-content-creation/"><u>New 2024 Approved Exploring Costless Alternatives Including Songs in Video Content Creation</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/gopro-vs-polaroid-which-video-editor-prevails-in-2024/"><u>GoPro Vs. Polaroid  Which Video Editor Prevails, In 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-not-found-errors-on-pc-windows/"><u>Overcoming 'Not Found' Errors on PC Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-nvidia-experience-connectivity-issues-on-pcs/"><u>Remedying Nvidia Experience Connectivity Issues on PCs</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-simplifying-vocal-alterations-the-audacity-technique/"><u>New Simplifying Vocal Alterations The Audacity Technique</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-windows-11-search-with-custom-settings/"><u>Optimizing Windows 11 Search with Custom Settings</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-cutting-edge-editors-to-craft-engaging-facebook-ad-videos/"><u>[New] In 2024, Cutting-Edge Editors to Craft Engaging Facebook Ad Videos</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-step-by-step-converting-pinterest-vids-to-mp3-audio/"><u>[Updated] Step-by-Step  Converting Pinterest Vids to MP3 Audio</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-system-limitations-intel-hd-graphics-compatibility-fixes/"><u>Rectifying System Limitations: Intel HD Graphics Compatibility Fixes</u></a></li>
<li><a href="https://facebook.techidaily.com/beyond-augmented-reality-the-true-metaverse-story/"><u>Beyond Augmented Reality: The True Metaverse Story</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-license-validity-alert-on-windows-oses/"><u>Resolving License Validity Alert on Windows OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-interactions-between-devices-and-pc-slumber/"><u>Navigating Interactions Between Devices and PC Slumber</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-surface-software-enhancement-techniques-for-maximum-performance/"><u>Mastering Surface Software Enhancement Techniques for Maximum Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/redirecting-to-file-explorer-from-onedrive-menu/"><u>Redirecting to File Explorer From OneDrive Menu</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-expert-strategies-for-choosing-valheim-crops/"><u>[New] 2024 Approved  Expert Strategies for Choosing Valheim Crops</u></a></li>
<li><a href="https://windows11.techidaily.com/recover-lost-pin-following-system-breakdown-on-windows-11/"><u>Recover Lost PIN Following System Breakdown on Windows 11</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-discovering-the-quintessential-25-influence-kings-and-queens/"><u>[Updated] 2024 Approved  Discovering The Quintessential 25 Influence Kings and Queens</u></a></li>
<li><a href="https://windows11.techidaily.com/mindfulness-meets-the-mind-cognitive-and-emotional-responses-to-meditation/"><u>Mindfulness Meets the Mind: Cognitive & Emotional Responses to Meditation</u></a></li>
<li><a href="https://windows11.techidaily.com/instructional-guide-for-end-task-enabling-on-windows-11/"><u>Instructional Guide for End Task Enabling on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resetting-grammarly-settings-in-windows/"><u>Resetting Grammarly Settings in Windows</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/unveiled-list-leading-top-10-facebook-video-downloaders-for-android-for-2024/"><u>Unveiled List  Leading Top 10 Facebook Video Downloaders for Android for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-fives-finest-tools-for-rapid-video-frame-capturing/"><u>[Updated] Five's Finest Tools for Rapid Video Frame Capturing</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-windows-11-when-it-cant-connect-to-5ghz-wi-fi/"><u>How to Fix Windows 11 When It Can’t Connect to 5GHz Wi-Fi</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-bring-back-the-memories-top-5-ps1-emulation-apps-for-pc/"><u>2024 Approved  Bring Back the Memories - Top 5 PS1 Emulation Apps for PC</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-mastering-the-conversion-of-vids-to-mp3-on-insta-for-2024/"><u>[Updated] Mastering the Conversion of Vids to MP3 on Insta for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-fix-pokemon-go-route-not-working-on-oppo-f23-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix Pokemon Go Route Not Working On Oppo F23 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-geforce-experience-setting-retrieval-failure-on-windows-1111/"><u>Resolving 'GeForce Experience' Setting Retrieval Failure on Windows 11/11</u></a></li>
<li><a href="https://windows11.techidaily.com/power-up-your-vms-in-windows-using-these-top-6-enhancers/"><u>Power Up Your VMs in Windows Using These Top 6 Enhancers</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/mastering-mind-games-top-trivia-channels-for-24-for-2024/"><u>Mastering Mind Games – Top Trivia Channels for '24 for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-remove-screen-lock-pin-on-oneplus-nord-n30-se-like-a-pro-5-easy-ways-by-drfone-android/"><u>How To Remove Screen Lock PIN On OnePlus Nord N30 SE Like A Pro 5 Easy Ways</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-in-2024-samsung-image-maker-insights-and-overview-2023/"><u>[New] In 2024, Samsung Image Maker  Insights & Overview 2023</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/024-approved-elevate-your-shots-vloggers-guide-to-the-9-finest-camera-gadgets/"><u>[New] 2024 Approved  Elevate Your Shots  Vlogger's Guide to the 9 Finest Camera Gadgets</u></a></li>
<li><a href="https://windows11.techidaily.com/rectify-stalling-windows-guard-mechanism-in-win-11/"><u>Rectify Stalling Windows Guard Mechanism in Win 11</u></a></li>
</ul></div>
