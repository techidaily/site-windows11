---
title: Regaining Normalcy in Windows 11 User Access
date: 2024-06-25T12:39:41.725Z
updated: 2024-06-26T12:39:41.725Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Regaining Normalcy in Windows 11 User Access
excerpt: This Article Describes Regaining Normalcy in Windows 11 User Access
keywords: Windows 11 Update,Access Security,System Normalization,New OS Stability,Windows Regain,Access Control Win11,Norm-Win User Entry
thumbnail: https://thmb.techidaily.com/775033cec734e193d493811f769dcaa65d428fba2286e40a488d59f8b08228ae.png
---

## Regaining Normalcy in Windows 11 User Access

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
<li><a href="https://windows11.techidaily.com/navigating-windows-11s-software-compatibility-tool/"><u>Navigating Windows 11’S Software Compatibility Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-grayed-out-bin-status-in-win11/"><u>Rectifying Grayed Out Bin Status in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-action-to-freeze-damaged-windows-pins/"><u>Immediate Action to Freeze-Damaged Windows PINs</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-new-era-of-filesystems-windows-11s-innovations/"><u>Navigating the New Era of Filesystems: Windows 11'S Innovations</u></a></li>
<li><a href="https://windows11.techidaily.com/the-5-best-practices-for-using-wsl-2-on-windows-10-and-11/"><u>The 5 Best Practices for Using WSL 2 on Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-linguistic-landscapes-smoothly-via-keyboard-shortcuts-in-win1011/"><u>Navigate Linguistic Landscapes Smoothly via Keyboard Shortcuts in Win10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-updating-obstacles-a-compreeher-guide-to-fixes/"><u>Clearing Updating Obstacles: A Compreeher Guide to Fixes</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-elite-group-16-youtube-entries-boosting-views-for-2024/"><u>[New] Elite Group  16 YouTube Entries Boosting Views for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-after-switching-from-vivo-v29-pro-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data After Switching From Vivo V29 Pro to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-seizing-stability-eliminating-instability/"><u>2024 Approved  Seizing Stability  Eliminating Instability</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-7-best-filmmaking-software-you-should-know-low-budget/"><u>New 7 Best Filmmaking Software You Should Know (Low Budget)</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-accelerate-clan-growth-9-rapid-fire-tips-for-popularity/"><u>2024 Approved  Accelerate Clan Growth  9 Rapid-Fire Tips for Popularity</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-boost-your-projects-quality-rankings-of-the-best-free-editing-apps-top-9-for-2024/"><u>[Updated] Boost Your Projects' Quality  Rankings of the Best Free Editing Apps (Top 9) for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-talking-audio-log-audit/"><u>2024 Approved  Talking Audio Log Audit</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-insta-speedsters-playbook-power-through-video-and-likes/"><u>[New] 2024 Approved  Insta Speedster's Playbook  Power Through Video and Likes</u></a></li>
</ul></div>
