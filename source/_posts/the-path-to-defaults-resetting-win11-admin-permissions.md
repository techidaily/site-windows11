---
title: "The Path to Defaults: Resetting Win11 Admin Permissions"
date: 2024-06-25T12:30:00.376Z
updated: 2024-06-26T12:30:00.376Z
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
<li><a href="https://windows11.techidaily.com/winrars-corrected-compression-overcoming-sum-errors/"><u>WinRAR's Corrected Compression: Overcoming Sum Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-adding-speed-meter-to-taskbar/"><u>Quick Guide: Adding Speed Meter to Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/best-approaches-to-regulate-device-connections-in-windows/"><u>Best Approaches to Regulate Device Connections in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-setup-of-microsofts-powertoys-win11/"><u>Effortless Setup of Microsoft's PowerToys (Win11)</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-screen-resolution-problems-in-windows-os/"><u>Rectifying Screen Resolution Problems in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-overhaul-pretend-its-windows-98-edition/"><u>Windows Overhaul: Pretend It's Windows 98 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/biometric-betrayal-how-secure-is-your-windows-hello-lock/"><u>Biometric Betrayal: How Secure Is Your Windows Hello Lock?</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-desktop-experience-fixing-this-pc-spotlight/"><u>Elevate Desktop Experience: Fixing 'This PC' Spotlight</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-art-of-elevating-notetaking-on-windows/"><u>Master the Art of Elevating Notetaking on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-your-gameplay-overcoming-lags-in-warfare/"><u>Elevating Your Gameplay: Overcoming Lags in Warfare</u></a></li>
<li><a href="https://audio-editing.techidaily.com/in-2024-transforming-your-speech-into-powerful-bass-with-filmora-filmmaking/"><u>In 2024, Transforming Your Speech Into Powerful Bass with Filmora Filmmaking</u></a></li>
<li><a href="https://extra-information.techidaily.com/achieving-studio-quality-with-audacity-for-2024/"><u>Achieving Studio Quality with Audacity for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-infinix-hot-40i-to-samsung-galaxy-s21-ultra-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos From Infinix Hot 40i to Samsung Galaxy S21 Ultra | Dr.fone</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-create-hollywood-style-videos-with-these-8-mac-apps/"><u>New 2024 Approved Create Hollywood-Style Videos with These 8 Mac Apps</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-lumafusion-on-mac-installation-guide-and-best-replacements/"><u>New In 2024, Lumafusion on Mac Installation Guide and Best Replacements</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-xiaomi-redmi-a2-phone-without-pin-by-drfone-android/"><u>In 2024, How to Unlock Xiaomi Redmi A2 Phone without PIN</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-maximizing-ram-for-enhanced-minecraft-experience/"><u>[Updated] Maximizing RAM for Enhanced Minecraft Experience</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/how-much-footage-does-instagram-allow/"><u>How Much Footage Does Instagram Allow?</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-post-mortem-punchlines-pro/"><u>In 2024, Post-Mortem Punchlines Pro</u></a></li>
<li><a href="https://ai-video.techidaily.com/new-how-to-convert-video-voice-to-text-online-for-freein-2024/"><u>new How To Convert Video Voice to Text Online for Free,In 2024</u></a></li>
</ul></div>
