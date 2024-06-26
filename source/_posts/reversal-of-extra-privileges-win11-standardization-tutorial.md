---
title: "Reversal of Extra Privileges: Win11 Standardization Tutorial"
date: 2024-06-25T12:15:10.615Z
updated: 2024-06-26T12:15:10.615Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Reversal of Extra Privileges: Win11 Standardization Tutorial"
excerpt: "This Article Describes Reversal of Extra Privileges: Win11 Standardization Tutorial"
keywords: Win11 Standardization Guide,Removing Extra Windows Privileges,Win11 Security Best Practices,Streamlining Windows Operations,Secure Win11 User Accounts,Standardizing Win11 Settings,Privilege Reduction in Win11
thumbnail: https://thmb.techidaily.com/805432a26a63c24a3ad7f94c306f1a1291a2364beb1c1710fc99d1f9d71ae26e.jpg
---

## Reversal of Extra Privileges: Win11 Standardization Tutorial

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
<li><a href="https://windows11.techidaily.com/utilizing-portable-gpus-no-internal-graphic-needed/"><u>Utilizing Portable GPUs: No Internal Graphic Needed</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-overcoming-printer-not-connected-problems/"><u>Win11: Overcoming Printer Not Connected Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-troubleshooting-guide-no-audio-output-error/"><u>Quick Troubleshooting Guide: No Audio Output Error</u></a></li>
<li><a href="https://windows11.techidaily.com/diagnosing-and-repairing-win-lsa-errors/"><u>Diagnosing and Repairing Win LSA Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-an-uninstall-shortcut-to-the-context-menu-in-windows-1110/"><u>How to Add an Uninstall Shortcut to the Context Menu in Windows 11/10</u></a></li>
<li><a href="https://windows11.techidaily.com/end-of-year-sale-windows-10-starting-at-an-insanely-low-612/"><u>End of Year Sale: Windows 10, Starting at an Insanely Low $6.12</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-icon-organization-made-simple/"><u>Windows Icon Organization Made Simple</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-caption-troubleshooting-made-simple/"><u>Win11 Caption Troubleshooting Made Simple</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-the-already-in-use-local-device-name-mistake-on-pcs/"><u>Remedy the 'Already in Use' Local Device Name Mistake on PCs</u></a></li>
<li><a href="https://extra-tips.techidaily.com/behind-the-scenes-mastering-cinematic-techniques-in-24-for-2024/"><u>Behind the Scenes  Mastering Cinematic Techniques in '24 for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-melodic-minutes-streamlined-strategies-for-viral-music-on-youtub/"><u>In 2024, Melodic Minutes  Streamlined Strategies for Viral Music on YouTub</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/the-magnificent-art-of-pokemon-go-streaming-on-poco-m6-5g-drfone-by-drfone-virtual-android/"><u>The Magnificent Art of Pokemon Go Streaming On Poco M6 5G? | Dr.fone</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-get-your-fcpx-flow-back-a-comprehensive-reset-and-troubleshooting-guide/"><u>2024 Approved Get Your FCPX Flow Back A Comprehensive Reset and Troubleshooting Guide</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-master-the-map-locating-youtube-studio-content-architects-toolbox/"><u>2024 Approved  Master the Map  Locating YouTube Studio, Content Architect’s Toolbox</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-in-2024-quietude-in-quarter-notes-advanced-methods-for-drum-ditching-in-digital-music/"><u>Updated In 2024, Quietude in Quarter Notes Advanced Methods for Drum Ditching in Digital Music</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-the-top-10-wave-capturing-cams-for-2024/"><u>[New] The Top 10 Wave-Capturing Cams for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-getting-started-in-google-meet-on-computersphone/"><u>[Updated] Getting Started in Google Meet on Computers/Phone</u></a></li>
<li><a href="https://change-location.techidaily.com/why-does-the-pokemon-go-battle-league-not-available-on-vivo-y78t-drfone-by-drfone-virtual-android/"><u>Why does the pokemon go battle league not available On Vivo Y78t | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-erase-background-noises-with-ease-using-audacity-tools/"><u>In 2024, Erase Background Noises with Ease Using Audacity Tools</u></a></li>
</ul></div>
