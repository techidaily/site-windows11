---
title: How to Correctly Manage the 0X80070003 Updater Error on Windows
date: 2024-12-30T17:19:42.498Z
updated: 2025-01-04T00:28:10.335Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Correctly Manage the 0X80070003 Updater Error on Windows
excerpt: This Article Describes How to Correctly Manage the 0X80070003 Updater Error on Windows
keywords: 0X80070003 Fix,Updater Error Resolution,Windows Update Troubleshoot,Error Code 0X80070003 Solve,Windows Updater Error Fix,0X80070003 Error Handle,Updater Malfunction Resolve
thumbnail: https://thmb.techidaily.com/f07aba0aa676c9e76b44feb60efd0a45624266536fcc9c86e32c630adb095a41.jpg
---

## How to Correctly Manage the 0X80070003 Updater Error on Windows

 It's not unusual for Windows users to run into issues when installing updates or upgrading to the latest version of Windows. The problem with these error codes is that most of the time, they do not specify the cause of the error or what users can do to avoid it.

 A common error that users run into when trying to update their system is 0x80070003\. This error is accompanied by a message stating "Some update files are missing." Let's explore the reasons behind this issue and the solutions you can try to resolve it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MmTJlcwgyrQ?si=x3hba82M0tT57fj7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Are Update Files Missing From Your PC?

 One or more of the following reasons might explain why you are experiencing the problem on your computer:

1. The Windows log file might have corrupt data files that are interfering with the update installation process in Windows. The best way to deal with corrupt files is by repairing them using the built-in Windows utilities. If that does not work, you can delete them to resolve the problem.
2. The essential system files have become corrupt. This scenario can be resolved by running the troubleshooting utilities described below. They can identify corrupt files and replace them with healthy ones.
3. The Windows update components required for the pending updates to install are not functioning properly, which is causing the system to throw the error Fortunately, repairing the corrupt components is easy and can be done within a few minutes using the Command Prompt.
4. The Windows Update service and other relevant services required by the system to install the pending updates are disabled or have become corrupt. In this case, you can simply restart the services to resolve the issue.

 Now that you know what might be causing the problem let’s see how to resolve this case of missing update files in Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_dOmuXhsV6Y?si=aT6vgPbDx4ajjvdr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3AGmFrtBLHw?si=VhvpUaXHPBHl6OT6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aa6vSdt1elM?si=qPhmO-hoWVIPBnnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SgRVYjqB70s?si=My_2cDvJVdincQRu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://article-files.techidaily.com/new-boost-call-quality-and-creativity-learn-to-apply-filters-in-zoom/"><u>[New] Boost Call Quality & Creativity Learn to Apply Filters in Zoom</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ow-to-securely-extract-and-convert-youtube-audios-as-mp3/"><u>[New] How To Securely Extract and Convert YouTube Audios as MP3</u></a></li>
<li><a href="https://win-bytes.techidaily.com/1-solving-common-screen-issues-expert-fixes-for-incorrectly-displayed-content-on-your-monitor-guided-by-yl-computing/"><u>1. Solving Common Screen Issues: Expert Fixes for Incorrectly Displayed Content on Your Monitor - Guided by YL Computing</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/approved-diy-audio-excellence-no-mic-necessary/"><u>2024 Approved DIY Audio Excellence No Mic Necessary</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-spectaculum-of-sight-top-picks-for-professional-8k/"><u>2024 Approved Spectaculum of Sight Top Picks for Professional 8K</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/tial-tips-for-youtube-thumbnail-design/"><u>Essential Tips for YouTube Thumbnail Design</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-tecno-spark-10-pro-by-phone-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Tecno Spark 10 Pro by Phone Number | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-optimal-mobile-tools-for-post-processing-dji-media/"><u>In 2024, Optimal Mobile Tools for Post-Processing DJi Media</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-without-powershell-on-windows-system/"><u>Navigating Without PowerShell on Windows System</u></a></li>
<li><a href="https://windows11.techidaily.com/reformatting-esd-files-as-linux-and-windows-isos-with-precision/"><u>Reformatting ESD Files as Linux and Windows ISOs with Precision</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-unresponsive-pc-mouse-connections/"><u>Resolving Unresponsive PC Mouse Connections</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-up-an-everlasting-file-eraser-a-user-guide-to-customizing-windows-11s-trash/"><u>Setting up an Everlasting File Eraser: A User Guide to Customizing Windows 11'S Trash</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-display-error-nvidias-x0001-on-windows-11/"><u>Tackling Display Error: Nvidia's X0001 on Windows 11</u></a></li>
</ul></div>

