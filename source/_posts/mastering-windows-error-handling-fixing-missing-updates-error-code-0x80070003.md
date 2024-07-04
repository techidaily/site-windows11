---
title: "Mastering Windows Error Handling: Fixing Missing Updates (Error Code: 0X80070003)"
date: 2024-06-25T11:57:38.940Z
updated: 2024-06-26T11:57:38.940Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Windows Error Handling: Fixing Missing Updates (Error Code: 0X80070003)"
excerpt: "This Article Describes Mastering Windows Error Handling: Fixing Missing Updates (Error Code: 0X80070003)"
keywords: WinErrorHandlingBasics,UpdateMissingSolution,ErrorCode0X80070003Fix,WindowsUpdatesTroubleshoot,FixError0x80070003,MissingWindowsUpdateResolve,ErrorHandlingStepByStep
thumbnail: https://thmb.techidaily.com/734ba7f5cb5c21a47d1f0b28c0f28b69fa0ec96215f4c2ee497557b9ec2807d6.jpg
---

## Mastering Windows Error Handling: Fixing Missing Updates (Error Code: 0X80070003)

 It's not unusual for Windows users to run into issues when installing updates or upgrading to the latest version of Windows. The problem with these error codes is that most of the time, they do not specify the cause of the error or what users can do to avoid it.

 A common error that users run into when trying to update their system is 0x80070003\. This error is accompanied by a message stating "Some update files are missing." Let's explore the reasons behind this issue and the solutions you can try to resolve it.

## Why Are Update Files Missing From Your PC?

 One or more of the following reasons might explain why you are experiencing the problem on your computer:

1. The Windows log file might have corrupt data files that are interfering with the update installation process in Windows. The best way to deal with corrupt files is by repairing them using the built-in Windows utilities. If that does not work, you can delete them to resolve the problem.
2. The essential system files have become corrupt. This scenario can be resolved by running the troubleshooting utilities described below. They can identify corrupt files and replace them with healthy ones.
3. The Windows update components required for the pending updates to install are not functioning properly, which is causing the system to throw the error Fortunately, repairing the corrupt components is easy and can be done within a few minutes using the Command Prompt.
4. The Windows Update service and other relevant services required by the system to install the pending updates are disabled or have become corrupt. In this case, you can simply restart the services to resolve the issue.

 Now that you know what might be causing the problem let’s see how to resolve this case of missing update files in Windows.

## 1\. Delete the Contents of the DataStore Folder

 The DataStore folder in Windows is a log file that stores information about all the updates installed in the system. This folder is located in the SoftwareDistribution folder, which is a directory of update-related information in Windows.

 In several cases, the underlying issue was caused due to the corrupt components of the DataStore folder, which were interfering with the system’s update process. An easy way to resolve this issue is by deleting the contents of this folder or removing the Data Store folder as a whole. Both methods are safe to execute.

 We have described the steps for doing this below. However, if you do not want to delete the DataStore folder or its contents, you can also repair them. For that, follow the next method below.

1. Launch File Explorer and navigate to the following location below:  
`C:\Windows\SoftwareDistribution`  
![Software distribution](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/win11-software-distribution.jpg)
2. Locate the**DataStore** folder in the SoftwareDistribution folder and right-click on it.
3. Choose**Delete** from the context menu.  
![Delete the DataStore folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/software-distribution-datastore-delete-1.jpg)
4. Click**Yes** in the confirmation prompt to proceed.

 Once the folder is deleted, open the Settings app and try installing the updates again.

## 2\. Run System Scans

 The next thing you can do is scan the system for potential issues. The best way to do this is by using built-in system utilities like the System File Checker and DISM.

 The System File Checker (SFC) will scan the protected system files for inconsistencies. If it finds a file that is corrupt, SFC will replace it with its healthier cached counterpart. DISM, on the other hand, will repair the system image.

 We will be using the Command Prompt to run these tools. Make sure you are logged into Windows as an administrator before proceeding:

Here is all that you need to do:

1. Open Command Prompt as an administrator (see[how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for instructions).
2. Click**Yes** in the User Account Control prompt.
3. In the Command Prompt window, type the command mentioned below and hit**Enter** .  
`sfc /scannow`  
![SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/sfc-scannow.jpg)
4. Wait for the command to execute, and then execute the following command:  
`Dism /Online /Cleanup-Image /ScanHealth`  
![DISM scanhealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/scanhealth.jpg)
5. Next, proceed with the following command:  
`Dism /Online /Cleanup-Image /RestoreHealth`  
![DISM restorehealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/restorehealth.jpg)
6. Once this command is executed, close the Command Prompt window and check if you can now download the targeted updates.

 While you are at it, you can also[run the Windows Update troubleshooter](https://www.makeuseof.com/tag/windows-update-troubleshooter/) . This tool also works like the utilities we just described above. It will scan the system for errors and suggest you relevant fixes that can be applied using the troubleshooter as well.

## 3\. Repair the Update Components

 As we mentioned earlier, the update components can also deal with some kind of corruption, leading to the problem under discussion.

 The good news is that repairing these components is quite simple, and we will also use the Command Prompt in this method. We recommend[creating a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed. This will help you revert to the current system state in case something goes wrong during the execution of the method.

Once the restore point is created, follow these steps:

1. Open a Run dialog box (see[how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) to learn how).
2. Type cmd in the text field of Run and press Ctrl + Shift + Enter to open Command Prompt as an administrator.
3. Click**Yes** in the User Account Control prompt.
4. Once you are inside the Command Prompt, execute the commands below one by one:  
`<code>net stop wuauserv  
net stop cryptSvc  
net stop bits  
net stop msiserver`  
``` `` ```
5. Once all the services are stopped, execute the following commands. These will clear the update cache in the system:  
`<code>ren %systemroot%\softwaredistribution softwaredistribution.bak  
ren %systemroot%\system32\catroot2 catroot2.bak`  
``` `` ```
6. Now, proceed with the following commands one by one to start the Windows update services again:  
`<code>net start wuauserv  
net start bits  
net start cryptsvc  
net start trustedinstaller  
net start appidsvc`  
![Restart the update services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/restart-the-services.jpg)
7. After the commands are executed, restart your computer. Hopefully, you will be able to install the pending updates on reboot.

## Get the Missing Update Files Back on Windows

 Hopefully, by now, you should have successfully resolved the annoying update error. In case you are still facing the issue, you can use the Microsoft update catalog to install the updates manually. It may also be a good idea to report this issue to the Microsoft support team so they can launch an official fix for the problem.


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
<li><a href="https://windows11.techidaily.com/expert-strategies-for-effortless-integration-of-directories-win-11/"><u>Expert Strategies for Effortless Integration of Directories, Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-break-the-bond-onedrive-from-ms-account-on-windows/"><u>Techniques to Break the Bond: OneDrive From MS Account on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensive-guide-to-fixing-0xc00000f-error/"><u>A Comprehensive Guide to Fixing 0xC00000F Error</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehending-the-safeguarded-state-of-windows-11/"><u>Comprehending the Safeguarded State of Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/path-to-start-driver-verifier-toolset-in-windows-11/"><u>Path to Start Driver Verifier Toolset in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerate-search-results-in-windows-11-with-these-11-fixes/"><u>Accelerate Search Results in Windows 11 with These 11 Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-discord-from-starting-with-windows-boot/"><u>Preventing Discord From Starting with Windows Boot</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-the-problem-of-unrecognized-drivers-during-windows-startup/"><u>Fixing the Problem of Unrecognized Drivers During Windows Startup</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/power-up-storage-ultimate-ps5-hard-drives-compared-for-2024/"><u>Power Up Storage  Ultimate PS5 Hard Drives Compared for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-integrate-efficiently-macos-sierra-for-desktop-enhancement/"><u>2024 Approved  Integrate Efficiently  MacOS Sierra for Desktop Enhancement</u></a></li>
<li><a href="https://extra-resources.techidaily.com/infusing-interactive-elements-incorrante-youtube-music-into-videography/"><u>Infusing Interactive Elements  Incorrante YouTube Music Into Videography</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-accelerate-your-footage-creating-time-lapses-in-final-cut-pro/"><u>New 2024 Approved Accelerate Your Footage Creating Time Lapses in Final Cut Pro</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-ultimate-10-video-editors-webcams-reimagined-for-2024/"><u>[New] Ultimate 10 Video Editors  Webcams Reimagined for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-masterful-free-fb-picture-and-film-producer/"><u>2024 Approved  Masterful Free FB Picture & Film Producer</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-5-best-route-generator-apps-you-should-try-on-honor-100-pro-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Best Route Generator Apps You Should Try On Honor 100 Pro | Dr.fone</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/personalizing-your-tiktok-presence-with-30-innovative-pfp-ideas-for-2024/"><u>Personalizing Your TikTok Presence with 30 Innovative PFP Ideas for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-the-epic-journey-through-memory-lane-advanced-methods-for-capturing-your-sims-digital-adventures-for-2024/"><u>[Updated] The Epic Journey Through Memory Lane  Advanced Methods for Capturing Your Sims' Digital Adventures for 2024</u></a></li>
</ul></div>
