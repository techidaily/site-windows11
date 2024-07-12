---
title: "The Path to Defaults: Resetting Win11 Admin Permissions"
date: 2024-07-11T21:51:28.720Z
updated: 2024-07-12T21:51:28.720Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes The Path to Defaults: Resetting Win11 Admin Permissions"
excerpt: "This Article Describes The Path to Defaults: Resetting Win11 Admin Permissions"
keywords: Win11 Admin Pause,Win11 PermReset,Win11 PermCheck,Admin Rights Reset,Default Windows Perms,Win11 Security Fixes,Restore Win11 Privileges
thumbnail: https://thmb.techidaily.com/b41dfc1747c954c2591d35270b4a20079e5707f867334ccdc51bba558ecb898b.jpg
---

## The Path to Defaults: Resetting Win11 Admin Permissions

 Having issues with apps or programs not running properly on your Windows computer? Resetting Windows Update permissions could be the solution you need. Similarly, if you're troubleshooting user profile problems, you can restore user permissions.

 This article covers three different methods to reset all user permissions – using the Icacls command, the Secedit command, and the Subinacl tool.

Let's now explore them in detail.

## 1\. Run the Icacls Command

 The Icacls command allows you to view, modify, and reset file system permissions on files and folders. To reset Windows Update permissions using this command, you will first have to [take ownership of the folders on Windows](https://www.makeuseof.com/windows-10-11-own-folder/) . Then [open an elevated Command Prompt on Windows](https://www.makeuseof.com/windows-run-command-prompt-admin/) and type in the following command:

`icacls * /t /q /c /reset`

 Now press Enter on your keyboard to execute the command. This will reset all user permissions to default for every folder, subfolder, and file within the current working directory.

In the above command, here are the parameters explained:

* \* – This is a wildcard character that includes all folders within the current directory.
* /t – It targets all the subfolders and files within the current folder.
* /q – Run command without displaying success messages.
* /c – Continues the operation even if errors occur.
* /reset – This parameter resets the permission options to their default values.

## 2\. Run the Secedit command

 Windows provides the Secedit command to configure and analyze system security. To reset all user permissions using this command, run the command prompt with admin access, then type in the following command:

![Run the Secedit command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-the-secedit-command.jpg)

`secedit /configure /cfg %windir%\inf\defltbase.inf /db defltbase.sdb /verbose`

 Now press Enter to execute the command. Wait for the process to finish and restart your computer. This will reset the user permissions to the default system settings.

## 3\. Run the Subinacl Tool

 If you're not comfortable using the command prompt, you may use the Subinacl tool. This is a command-line utility from Microsoft that can be used to reset user permissions. Here's how to do it:

1. [Download the Subinacl tool from Microsoft's webpage](https://web.archive.org/web/20190830103837/http://www.microsoft.com/en-us/download/confirmation.aspx?id=23510) . When you open the page, the download starts automatically. If not, wait 30 seconds and click the link.
2. Once downloaded, double-click on the installer package. This will open the installation wizard.  
![Open the installation wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/open-the-installation-wizard.jpg)
3. Click on**Next** and then accept the license agreement terms.  
![Install the Subinacl tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-the-subinacl-tool.jpg)
4. Next, copy and paste the following path into the Destination folder:  
`C:\Windows\System32`  
 Note: If you have installed Windows on a different drive, use that path instead.
5. Now click on**Install now** and wait for the Subinacl tool to be installed. This may take several minutes, so be patient.

1. When the installation is complete,[open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) and type in the following commands:  
`subinacl /subkeyreg HKEY_LOCAL_MACHINE /grant=administrators=f  
subinacl /subkeyreg HKEY_CURRENT_USER /grant=administrators=f  
subinacl /subkeyreg HKEY_CLASSES_ROOT /grant=administrators=f  
subinacl /subdirectories %SystemDrive% /grant=administrators=f  
subinacl /subkeyreg HKEY_LOCAL_MACHINE /grant=system=f  
subinacl /subkeyreg HKEY_CURRENT_USER /grant=system=f  
subinacl /subkeyreg HKEY_CLASSES_ROOT /grant=system=f  
subinacl /subdirectories %SystemDrive% /grant=system=f`
2. On the Save As window, set the File name to**Reset.cmd** and then select**All Files** from the drop-down menu next to it.  
![Reset Windows Update permissions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-update-permissions.jpg)
3. Next, select**Desktop** from the left pane and click on**Save** .
4. Now double-click on it to reset the user permissions to default.
5. This may take a while to complete the procedure, so wait for it to finish.

 Once done, close any running program, and then restart your computer. Your Windows Update permissions will be reset to their default settings. These are three different methods you can use to reset the user permission settings on Windows.

## Restore User Permissions to Default on Windows

 User permissions play a crucial role in computer security. If you're experiencing user permission issues, you must reset them to their default settings. This guide helps you reset all user permissions on Windows using three different methods. You can use the ICACLS command, Secedit command, or Subinacl tool, depending on your preference.


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
<li><a href="https://windows11.techidaily.com/a-guide-to-overcoming-windows-resolution-riddles/"><u>A Guide to Overcoming Windows Resolution Riddles</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-win11-boot-time-quick-tips-for-speedier-launches/"><u>Boosting Win11 Boot Time: Quick Tips for Speedier Launches</u></a></li>
<li><a href="https://techidaily.com/recover-apple-iphone-se-2022-data-from-icloud-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>Recover Apple iPhone SE (2022) Data From iCloud | Dr.fone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-navigating-the-world-of-audio-editing-in-audacity-for-mac-devices-for-2024/"><u>[New] Navigating the World of Audio Editing in Audacity for Mac Devices for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/beginners-blueprint-to-conquering-diablo/"><u>Beginner’s Blueprint to Conquering Diablo</u></a></li>
<li><a href="https://windows11.techidaily.com/8-essential-fixes-for-resistant-windows-pin-locks/"><u>8 Essential Fixes for Resistant Windows PIN Locks</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/2024-approved-evolving-sound-quality-issues-within-the-2023-adobe-rush-iteration/"><u>2024 Approved Evolving Sound Quality Issues Within the 2023 Adobe Rush Iteration</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-ios-leading-ps2-game-emulation-tools/"><u>In 2024, IOS Leading PS2 Game Emulation Tools</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-video-mastery-unlocked-the-top-5-online-techniques-to-shorten-vimeo-content/"><u>2024 Approved  Video Mastery Unlocked  The Top 5 Online Techniques to Shorten Vimeo Content</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-life-to-windows-11-desktops-with-interactive-wallpapers/"><u>Bring Life to Windows 11 Desktops with Interactive Wallpapers</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-peak-laughter-edit-suite/"><u>In 2024, Peak Laughter Edit Suite</u></a></li>
<li><a href="https://windows11.techidaily.com/8-essential-steps-to-bring-back-lost-windows-files/"><u>8 Essential Steps to Bring Back Lost Windows Files</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-2024-approved-spark-the-momentum-channels-best-inspirational-videos/"><u>[Updated] 2024 Approved  Spark the Momentum  Channel's Best Inspirational Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-blunders-fix-windows-color-management-fiascos/"><u>Bypassing Blunders: Fix Windows Color Management Fiascos</u></a></li>
<li><a href="https://windows11.techidaily.com/adapting-oculus-quest-3-for-windows-os-vr-environment/"><u>Adapting Oculus Quest 3 for Windows OS VR Environment</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-instantly-optimize-your-twitter-videos-with-aspect-ratio-data/"><u>2024 Approved Instantly Optimize Your Twitter Videos with Aspect Ratio Data</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-did-your-apple-iphone-xr-passcode-change-itself-unlock-it-now-by-drfone-ios/"><u>In 2024, Did Your Apple iPhone XR Passcode Change Itself? Unlock It Now</u></a></li>
<li><a href="https://windows11.techidaily.com/alter-ip-settings-with-confidence-windows-11/"><u>Alter IP Settings with Confidence (Windows 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/bypass-windows-11-pc-life-hacks-for-older-systems/"><u>Bypass Windows 11: PC Life Hacks for Older Systems</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-turning-pinterest-video-into-downloadable-mp3-files/"><u>[New] Turning Pinterest Video Into Downloadable MP3 Files</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-syncopating-soundtracks-with-flawless-audio-transitions/"><u>2024 Approved  Syncopating Soundtracks with Flawless Audio Transitions</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-silencing-windows-11-alerts-benefits-unveiled/"><u>Avoid Silencing Windows 11 Alerts: Benefits Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/bootable-windows-11-flashdrive-top-3-efficient-techniques/"><u>Bootable Windows 11 Flashdrive: Top 3 Efficient Techniques</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-tread-lightly-in-the-digital-jungle-vr-fitness-machines-examined/"><u>2024 Approved  Tread Lightly in the Digital Jungle  VR Fitness Machines Examined</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-formatting-youtubes-auto-subscribe-page-easily-for-2024/"><u>[New] Formatting YouTube's Auto-Subscribe Page Easily for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/accessing-the-internet-without-a-browser-post-setup/"><u>Accessing the Internet Without a Browser Post-Setup</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/yogic-path-top-10-pioneers-in-virtual-practice-for-2024/"><u>Yogic Path  Top 10 Pioneers in Virtual Practice for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-without-mishap-avoiding-errors-in-windows-11/"><u>Navigating Without Mishap: Avoiding Errors in Windows 11</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-in-2024-how-to-remove-static-noise-from-audio-in-seconds/"><u>Updated In 2024, How to Remove Static Noise From Audio in Seconds</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-craft-a-masterpiece-techniques-for-engaging-viral-tiktok-unpacks/"><u>[Updated] Craft a Masterpiece  Techniques for Engaging, Viral TikTok Unpacks</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-game-on-unlock-the-secrets-of-effective-lol-recording/"><u>[New] Game-On! - Unlock the Secrets of Effective LOL Recording</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-the-complete-roadmap-to-effective-fb-video-campaigns/"><u>In 2024, The Complete Roadmap to Effective FB Video Campaigns</u></a></li>
<li><a href="https://windows11.techidaily.com/camouflage-linguistic-separator-on-win11-status-bar/"><u>Camouflage Linguistic Separator on Win11 Status Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-efficiency-best-keys-for-auto-clicking/"><u>Boost Efficiency: Best Keys for Auto Clicking</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-why-obs-wont-start-on-your-pc/"><u>Breaking Down Why OBS Won't Start on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-failures-fixing-vagrant-boot-problems-win11/"><u>Bypassing Failures: Fixing Vagrant Boot Problems Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/8-ways-to-fix-the-windows-pin-not-working-in-windows-11-and-11/"><u>8 Ways to Fix the Windows PIN Not Working in Windows 11 & 11</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-tasty-tales-ideal-naming-for-culinary-broadcasts/"><u>2024 Approved  Tasty Tales  Ideal Naming for Culinary Broadcasts</u></a></li>
<li><a href="https://windows11.techidaily.com/altering-windows-service-for-installation-controls/"><u>Altering Windows Service for Installation Controls</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-win-1011s-xc0f1103f-with-geforce-error/"><u>Addressing Win 10/11'S XC0F1103F with GeForce Error</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-metric-monitoring-of-wifi-networks-via-win11-settings/"><u>Adjusting Metric Monitoring of Wifi Networks via Win11 Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/automation-made-simple-windows-task-scheduler-batch/"><u>Automation Made Simple: Windows Task Scheduler Batch</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ltimate-list-of-8-free-video-editing-programs-for-creatives-for-2024/"><u>The Ultimate List of 8 FREE Video Editing Programs for Creatives for 2024</u></a></li>
</ul></div>
