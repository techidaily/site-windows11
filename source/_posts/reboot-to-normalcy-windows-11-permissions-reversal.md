---
title: "Reboot to Normalcy: Windows 11 Permissions Reversal"
date: 2024-06-25T12:01:15.702Z
updated: 2024-06-26T12:01:15.702Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Reboot to Normalcy: Windows 11 Permissions Reversal"
excerpt: "This Article Describes Reboot to Normalcy: Windows 11 Permissions Reversal"
keywords: Win11 Permission Fix,Normalcy Boot Windows,Windows 11 Control Panel,Revise Windows Perms,Access Restore Windows,Unlocking Windows Security,Modify Windows Ownership
thumbnail: https://thmb.techidaily.com/c8cc0b50d6a862024b28911d2e2409173d05c3a9fcb60009ede2fce73e839885.jpg
---

## Reboot to Normalcy: Windows 11 Permissions Reversal

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
<li><a href="https://windows11.techidaily.com/swift-solutions-to-resolve-instant-failure-in-adding-a-folder-in-onedrive/"><u>Swift Solutions to Resolve Instant Failure in Adding a Folder in OneDrive</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-camera-access-notification-controls-on-win11/"><u>Mastering Camera Access Notification Controls on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/fasten-outlook-pace-on-pc-essential-tips/"><u>Fasten Outlook Pace on PC - Essential Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-high-cpu-in-your-host-system/"><u>Taming High CPU in Your Host System</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-directx-downloading-and-updating-steps/"><u>Mastering DirectX: Downloading & Updating Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-interruptexception-on-windows-11/"><u>Tackling the INTERRUPT_EXCEPTION on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-task-manager-not-working-in-windows/"><u>How to Fix the Task Manager Not Working in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/realign-your-windows-clock-through-chrome-settings/"><u>Realign Your Windows Clock Through Chrome Settings</u></a></li>
<li><a href="https://android-location-track.techidaily.com/best-anti-tracker-software-for-xiaomi-14-pro-drfone-by-drfone-virtual-android/"><u>Best Anti Tracker Software For Xiaomi 14 Pro | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/here-are-some-of-the-best-pokemon-discord-servers-to-join-on-xiaomi-14-drfone-by-drfone-virtual-android/"><u>Here are Some of the Best Pokemon Discord Servers to Join On Xiaomi 14 | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-a-comprehensive-guide-to-icloud-unlock-from-iphone-7-plus-online-by-drfone-ios/"><u>In 2024, A Comprehensive Guide to iCloud Unlock From iPhone 7 Plus Online</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/enhancing-your-syma-x8c-experience/"><u>Enhancing Your Syma X8C Experience</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-2024-approved-videopad-video-editor-2023-a-comprehensive-review-and-recommendation/"><u>Updated 2024 Approved Videopad Video Editor 2023 A Comprehensive Review and Recommendation</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fixing-foneazy-mockgo-not-working-on-xiaomi-redmi-note-12t-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Fixing Foneazy MockGo Not Working On Xiaomi Redmi Note 12T Pro | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-webcam-selection-guide-the-10-best-picks-unveiled/"><u>[Updated] 2024 Approved  Webcam Selection Guide  The 10 Best Picks Unveiled</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-fcp-mastery-expert-led-tutorials-and-training/"><u>New FCP Mastery Expert-Led Tutorials and Training</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-step-by-step-iphone-ringer-update-guide/"><u>[New] Step-by-Step  IPhone Ringer Update Guide</u></a></li>
</ul></div>
