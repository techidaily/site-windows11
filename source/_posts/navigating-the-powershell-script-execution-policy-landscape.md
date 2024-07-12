---
title: Navigating the PowerShell Script Execution Policy Landscape
date: 2024-07-11T21:43:42.775Z
updated: 2024-07-12T21:43:42.775Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating the PowerShell Script Execution Policy Landscape
excerpt: This Article Describes Navigating the PowerShell Script Execution Policy Landscape
keywords: PowerShell Policy Guide,PSExecutionPolicy Handling,Script Security Policies,Execute PowerShell Safely,Modify Script Policy,PowerShell Policy Enforcement,Secure Script Execution
thumbnail: https://thmb.techidaily.com/5137476410d550ff3157a9e8b8c303fc95e61e87d44f30246bb809e8ce4eedda.jpg
---

## Navigating the PowerShell Script Execution Policy Landscape

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
<li><a href="https://windows11.techidaily.com/from-handheneld-to-hardware-android-titles-on-windows-via-google-service/"><u>From Handheneld to Hardware: Android Titles on Windows via Google Service</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-repeatedly-spotted-edge-buttons/"><u>Fixing Repeatedly Spotted Edge Buttons</u></a></li>
<li><a href="https://windows11.techidaily.com/minimize-high-usage-windows-11-news-and-media-feats/"><u>Minimize High Usage Windows 11 News & Media Feats</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-troubled-windows-registry-with-effective-solutions/"><u>Tackling Troubled Windows Registry with Effective Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/best-non-procreate-sketch-tools-for-windows-pc/"><u>Best Non-Procreate Sketch Tools for Windows PC</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unlocking-the-secrets-of-professional-srt-file-making/"><u>In 2024, Unlocking the Secrets of Professional SRT File Making</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-in-2024-this-article-will-help-you-understand-how-to-create-video-contents-that-convert-sales/"><u>New In 2024, This Article Will Help You Understand How to Create Video Contents that Convert Sales</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-reset-itunes-backup-password-of-iphone-xs-prevention-and-solution-by-drfone-ios/"><u>In 2024, Reset iTunes Backup Password Of iPhone XS Prevention & Solution</u></a></li>
<li><a href="https://youtube-data.techidaily.com/nsuring-thumbnails-show-shorts-video-troubleshooting-for-2024/"><u>[New] Ensuring Thumbnails Show  Shorts Video Troubleshooting for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-5-car-locator-apps-for-oppo-f23-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Top 5 Car Locator Apps for Oppo F23 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-enhancing-pen-device-performance-on-windows/"><u>Troubleshooting: Enhancing Pen Device Performance on Windows</u></a></li>
<li><a href="https://techidaily.com/complete-guide-to-hard-reset-your-realme-note-50-drfone-by-drfone-reset-android-reset-android/"><u>Complete Guide to Hard Reset Your Realme Note 50 | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-capturing-youtube-icons-browser-extension-command-line-and-software-trio-for-2024/"><u>[New] Capturing Youtube Icons  Browser Extension, Command Line & Software Trio for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-channeling-cashflow-a-beginners-guide-to-youtube-earning/"><u>2024 Approved  Channeling Cashflow  A Beginner’s Guide to YouTube Earning</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-ultimate-2023-tweet-video-roundup/"><u>[New] In 2024, Ultimate 2023 Tweet Video Roundup</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-securing-snapshots-across-android-and-mac-platforms/"><u>[Updated] Securing Snapshots Across Android and Mac Platforms</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-resource-assignment-in-wsl-android-setup/"><u>Mastering Resource Assignment in WSL-Android Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windowed-play-top-6-windows-11-fps-counters/"><u>Mastering Windowed Play: Top 6 Windows 11 FPS Counters</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-i-transferred-messages-from-itel-a70-to-iphone-12xs-max-in-seconds-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How I Transferred Messages from Itel A70 to iPhone 12/XS (Max) in Seconds | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-lav-filters-a-comprehensive-guide-to-effective-use-in-windows/"><u>Mastery Over LAV Filters: A Comprehensive Guide to Effective Use in Windows</u></a></li>
<li><a href="https://screen-recording.techidaily.com/precision-in-pacing-time-lapse-on-ipad/"><u>Precision in Pacing  Time-Lapse on iPad</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-top-5-websites-and-software-to-convert-powerpoint-to-mp4/"><u>2024 Approved Top 5 Websites and Software to Convert Powerpoint to Mp4</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-quickly-fix-keyboard-issues-in-windows-snipper/"><u>How to Quickly Fix Keyboard Issues in Window's Snipper</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-anarchy-how-to-heal-fractured-win11-registry-elements/"><u>Avoiding Anarchy: How to Heal Fractured Win11 Registry Elements</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-captivating-sounds-without-breaking-your-piggy-bank-the-top-six-no-cost-video-conversion-approaches-for-2024/"><u>Updated Captivating Sounds Without Breaking Your Piggy Bank The Top Six No-Cost Video Conversion Approaches for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-5-popular-guitar-recording-software-for-guitarists/"><u>In 2024, 5 Popular Guitar Recording Software for Guitarists</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-efficiency-folders-and-files-converge-in-win-11/"><u>Unlocking Efficiency: Folders & Files Converge in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-to-mute-game-proposals-in-windows-11/"><u>Tips to Mute Game Proposals in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-onedrives-abode-in-the-windows-11-ecosystem/"><u>Adjusting OneDrive's Abode in the Windows 11 Ecosystem</u></a></li>
<li><a href="https://windows11.techidaily.com/turbocharge-pc-gaming-with-high-speed-yuzu/"><u>Turbocharge PC Gaming with High-Speed Yuzu</u></a></li>
<li><a href="https://windows11.techidaily.com/the-hidden-language-of-windows-update-identifiers/"><u>The Hidden Language of Windows Update Identifiers</u></a></li>
<li><a href="https://windows11.techidaily.com/6-ways-to-recover-an-off-screen-window-in-windows-10-and-11/"><u>6 Ways to Recover an Off-Screen Window in Windows 10 and 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-net-requirement-issue-in-windows-apps/"><u>Tackling the .NET Requirement Issue in Windows Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-11-unable-to-load-driver-errors/"><u>Addressing Windows 11: Unable to Load Driver Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-display-glitch-geforce-experience-x0001/"><u>Fixing Display Glitch: GeForce Experience X0001</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-offline-microsoft-onedrive-file-management/"><u>Guide to Offline Microsoft OneDrive File Management</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/full-guide-to-catch-100-iv-pokemon-using-a-map-on-realme-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>Full Guide to Catch 100 IV Pokémon Using a Map On Realme 12 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-unlocking-tiktok-perfecting-siri-voice-interaction/"><u>[Updated] In 2024, Unlocking TikTok  Perfecting Siri Voice Interaction</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-elevate-your-tiktok-footage-with-stunning-template-techniques/"><u>[Updated] 2024 Approved  Elevate Your TikTok Footage with Stunning Template Techniques</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-expert-selection-of-win-11-camcorders-and-webcam-devices-for-2024/"><u>[New] Expert Selection of Win 11 Camcorders & Webcam Devices for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/cease-windows-logging-each-app-opener/"><u>Cease Windows Logging Each App Opener</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-for-installing-unverified-windows-drivers/"><u>Tactics for Installing Unverified Windows Drivers</u></a></li>
<li><a href="https://windows11.techidaily.com/download-adobe-reader-seamlessly-with-microsoft-store/"><u>Download Adobe Reader Seamlessly with Microsoft Store</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-quick-access-shortcuts-adjacent-to-power-in-win11/"><u>Unveiling Quick Access: Shortcuts Adjacent to Power in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-batch-file-transformation-executable-edition/"><u>Mastering Batch File Transformation: Executable Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/5-ways-to-fix-the-windows-family-safety-feature-not-working/"><u>5 Ways to Fix the Windows Family Safety Feature Not Working</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/non-twitter-video-tweeting-hacks-for-the-modern-user-for-2024/"><u>Non-Twitter Video Tweeting Hacks for the Modern User for 2024</u></a></li>
<li><a href="https://ai-video.techidaily.com/new-in-2024-how-to-translate-tiktok-videos-top-5-auto-translate-tools/"><u>new In 2024, How to Translate TikTok Videos Top 5 Auto Translate Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-writing-enhancers-for-your-windows-desktop/"><u>Top 5 Writing Enhancers for Your Windows Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-distracting-notifications-messages-on-windows-11/"><u>Avoid Distracting Notifications, Messages on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/innovative-ways-to-initiate-windows-based-software/"><u>Innovative Ways to Initiate Windows-Based Software</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-manual-methods-for-malware-detection-on-desktops/"><u>Mastering Manual Methods for Malware Detection on Desktops</u></a></li>
<li><a href="https://some-skills.techidaily.com/vertex-productions-summary-pinnacle-studio-assessment-2023-for-2024/"><u>Vertex Productions Summary  Pinnacle Studio Assessment, 2023 for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-taskbar-windows-11-edition/"><u>Elevate Your Taskbar: Windows 11 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/dive-into-dark-display-settings-for-calc-app/"><u>Dive Into Dark Display Settings for Calc App</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-esd-file-conversion-to-iso-on-windows-systems/"><u>Mastering ESD File Conversion to ISO on Windows Systems</u></a></li>
</ul></div>
