---
title: "Unlocking Defaults: Permissions Restoration Guide"
date: 2024-06-25T11:59:51.937Z
updated: 2024-06-26T11:59:51.937Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unlocking Defaults: Permissions Restoration Guide"
excerpt: "This Article Describes Unlocking Defaults: Permissions Restoration Guide"
keywords: Unlock Permissions,Restore Access,Default Privileges,Permission Guide,Reclaim Rights,Standard Authorization,Regain Control
thumbnail: https://thmb.techidaily.com/1505d6f4180ef3234fcf66cf60e394c6b774b52749b9718fd3308deebd93e5f0.jpg
---

## Unlocking Defaults: Permissions Restoration Guide

 Having issues with apps or programs not running properly on your Windows computer? Resetting Windows Update permissions could be the solution you need. Similarly, if you're troubleshooting user profile problems, you can restore user permissions.

 This article covers three different methods to reset all user permissions – using the Icacls command, the Secedit command, and the Subinacl tool.

Let's now explore them in detail.

## 1\. Run the Icacls Command

 The Icacls command allows you to view, modify, and reset file system permissions on files and folders. To reset Windows Update permissions using this command, you will first have to[take ownership of the folders on Windows](https://www.makeuseof.com/windows-10-11-own-folder/) . Then[open an elevated Command Prompt on Windows](https://www.makeuseof.com/windows-run-command-prompt-admin/) and type in the following command:

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
<li><a href="https://windows11.techidaily.com/nullify-specification-shortfalls-alerts-in-win11/"><u>Nullify Specification Shortfalls Alerts in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windowed-play-top-6-windows-11-fps-counters/"><u>Mastering Windowed Play: Top 6 Windows 11 FPS Counters</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-cyber-safety-trustable-domains-on-windows-11/"><u>Enhance Cyber Safety: Trustable Domains on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/rectify-stalling-windows-guard-mechanism-in-win-11/"><u>Rectify Stalling Windows Guard Mechanism in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-combatting-windows-not-found-problem/"><u>Essential Tips: Combatting Windows Not Found Problem</u></a></li>
<li><a href="https://windows11.techidaily.com/proven-strategies-to-enhance-wireless-and-cable-networks-on-windows/"><u>Proven Strategies to Enhance Wireless and Cable Networks on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/thawing-the-frozen-menus-6-windows-remedies-explored/"><u>Thawing the Frozen Menus: 6 Windows Remedies Explored</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-complex-windows-partition-unification/"><u>The Ultimate Guide to Complex Windows Partition Unification</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-code-0x0001-complication-in-windows-11/"><u>Unraveling Code 0X0001 Complication in Windows 11</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-how-to-seamlessly-integrate-soft-audio-into-your-space/"><u>Updated 2024 Approved How to Seamlessly Integrate Soft Audio Into Your Space</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-from-raw-footage-to-hit-vids-a-step-by-step-guide-for-editors-for-2024/"><u>New From Raw Footage to Hit Vids A Step-by-Step Guide for Editors for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-unveiling-the-best-apps-to-master-sound-transformation/"><u>2024 Approved  Unveiling the Best Apps to Master Sound Transformation</u></a></li>
<li><a href="https://extra-skills.techidaily.com/navigating-windows-10-features-for-seamless-video-editing-for-2024/"><u>Navigating Windows 10 Features for Seamless Video Editing for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/navigating-pip-in-chrome-for-every-os/"><u>Navigating PIP in Chrome for Every OS</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-turning-clutter-into-clarity-managing-massive-tiktok-drafters/"><u>2024 Approved  Turning Clutter Into Clarity  Managing Massive TikTok Drafters</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-effective-measures-to-block-pesky-video-ads-online/"><u>2024 Approved  Effective Measures to Block Pesky Video Ads Online</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-unleash-creativity-the-newcomers-snapseed-tutorial/"><u>2024 Approved  Unleash Creativity  The Newcomer's Snapseed Tutorial</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-do-you-get-sun-stone-evolutions-in-pokemon-for-vivo-s17t-drfone-by-drfone-virtual-android/"><u>In 2024, How Do You Get Sun Stone Evolutions in Pokémon For Vivo S17t? | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-unite-video-files-into-playlist-assembly/"><u>[New] Unite Video Files Into Playlist Assembly</u></a></li>
</ul></div>
