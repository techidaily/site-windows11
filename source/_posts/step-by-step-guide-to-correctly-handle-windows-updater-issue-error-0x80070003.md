---
title: Step-by-Step Guide to Correctly Handle Windows' Updater Issue (Error 0X80070003)
date: 2024-08-08T06:12:57.640Z
updated: 2024-08-09T06:12:57.640Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Step-by-Step Guide to Correctly Handle Windows' Updater Issue (Error 0X80070003)
excerpt: This Article Describes Step-by-Step Guide to Correctly Handle Windows' Updater Issue (Error 0X80070003)
keywords: Windows Updater Fix Tips,Handling Error 0X80070003,Windows Update Troubleshooting,Solve Updater Issue Quickly,Stop Error 0X80070003 in Windows,Guide to Windows Update Success,Fixing Updater Errors Effectively
thumbnail: https://thmb.techidaily.com/526587f9f9083224ba90b469fae9f684a8ef66dad7a99594a73a26d6b57f4450.jpg
---

## Step-by-Step Guide to Correctly Handle Windows' Updater Issue (Error 0X80070003)

 It's not unusual for Windows users to run into issues when installing updates or upgrading to the latest version of Windows. The problem with these error codes is that most of the time, they do not specify the cause of the error or what users can do to avoid it.

 A common error that users run into when trying to update their system is 0x80070003\. This error is accompanied by a message stating "Some update files are missing." Let's explore the reasons behind this issue and the solutions you can try to resolve it.

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1896607/21553" target="_top" id="1896607"><img src="//a.impactradius-go.com/display-ad/21553-1896607" border="0" alt="" width="750" height="422"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1896607/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->
![Software distribution](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/win11-software-distribution.jpg)
2. Locate the**DataStore** folder in the SoftwareDistribution folder and right-click on it.
3. Choose**Delete** from the context menu.  
<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Delete the DataStore folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/software-distribution-datastore-delete-1.jpg)
4. Click**Yes** in the confirmation prompt to proceed.

 Once the folder is deleted, open the Settings app and try installing the updates again.

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
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
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
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


