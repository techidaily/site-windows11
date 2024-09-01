---
title: Resolving Missing Update Files Issue (Error Code 0X80070003) in Windows
date: 2024-08-31T22:09:31.403Z
updated: 2024-09-01T22:09:31.403Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving Missing Update Files Issue (Error Code 0X80070003) in Windows
excerpt: This Article Describes Resolving Missing Update Files Issue (Error Code 0X80070003) in Windows
keywords: File Update Error Fix,Windows Error 0X80070003 Solution,Missing Updates Troubleshoot,Resolve Win Error Code 0X80070003,Windows Updater Issue Remedy,Error 0X80070003 File Update,Fix Windows Update Failure
thumbnail: https://thmb.techidaily.com/6cebc56dc292975b98a5a871193af627ed43dff4753b2894db168c37d5d2f38f.png
---

## Resolving Missing Update Files Issue (Error Code 0X80070003) in Windows

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

<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
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
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
`Dism /Online /Cleanup-Image /ScanHealth`  
![DISM scanhealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/scanhealth.jpg)
5. Next, proceed with the following command:  
<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
`Dism /Online /Cleanup-Image /RestoreHealth`  
![DISM restorehealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/restorehealth.jpg)
6. Once this command is executed, close the Command Prompt window and check if you can now download the targeted updates.
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->

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
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
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
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-designing-the-ideal-youtube-playlist-for-you/"><u>[New] In 2024, Designing the Ideal YouTube Playlist for You</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-streamlining-the-process-of-webinars-to-video/"><u>[New] Streamlining the Process of Webinars to Video</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-navigating-the-world-of-time-stamps-in-youtube-links-desktopmobile/"><u>[Updated] Navigating the World of Time Stamps in YouTube Links (Desktop/Mobile)</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-streamline-your-youtube-experience-manage-video-comments/"><u>[Updated] Streamline Your YouTube Experience  Manage Video Comments</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/p-rated-digital-video-cutting-tools/"><u>10 Top-Rated Digital Video Cutting Tools</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-simplifying-windows-11-sound-logging/"><u>2024 Approved  Simplifying Windows 11 Sound Logging</u></a></li>
<li><a href="https://win-answers.techidaily.com/effective-solutions-for-resolving-the-blue-screen-of-death-in-hell-divers-2/"><u>Effective Solutions for Resolving the Blue Screen of Death in Hell Divers 2</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-to-using-microsoft-copilot-in-development/"><u>Essential Guide to Using Microsoft Copilot in Development</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-troubleshooting-missing-steam-controllers/"><u>Essential Tips: Troubleshooting Missing Steam Controllers</u></a></li>
<li><a href="https://article-helps.techidaily.com/explore-the-best-free-after-effects-resources/"><u>Explore the Best FREE After Effects Resources</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-your-slow-internet-matching-mobile-and-desktop-speeds/"><u>Fix Your Slow Internet: Matching Mobile and Desktop Speeds</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-your-unresponsive-xbox-controllers-on-pc/"><u>Fixing Your Unresponsive Xbox Controllers on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-unlock-pin-related-bluetooth-disconnects-in-win11win10/"><u>How To Unlock PIN-Related Bluetooth Disconnects in Win11/Win10</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-curbing-inertia-in-high-altitude-cinematography/"><u>In 2024, Curbing Inertia in High Altitude Cinematography</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-vivo-x100-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Vivo X100 to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-transforming-footage-a-step-by-step-guide-to-gopros-timelapse/"><u>In 2024, Transforming Footage  A Step-by-Step Guide to GoPro's Timelapse</u></a></li>
<li><a href="https://win-dash.techidaily.com/level-up-performance-tuning-the-asus-rx-970-for-gamers/"><u>Level Up Performance: Tuning the ASUS RX 970 for Gamers</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-learn-how-everything-works-on-nubia-z50s-pro-drfone-by-drfone-virtual-android/"><u>Life360 Learn How Everything Works On Nubia Z50S Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-meaning-of-windows-mbr-error-messages/"><u>Mastering the Meaning of Windows MBR Error Messages</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-easily-getting-outlook-preview-on-winoss/"><u>Navigate Easily: Getting Outlook Preview on WinOSs</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-zero-error-in-windows-11-with-procedures/"><u>Overcoming Zero-Error in Windows 11 with Procedures</u></a></li>
<li><a href="https://windows11.techidaily.com/resetting-forgotten-power-schemes-on-ws-11/"><u>Resetting Forgotten Power Schemes on WS 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-lockout-due-to-failed-sign-in-attempts/"><u>Resolving Windows Lockout Due to Failed Sign-In Attempts</u></a></li>
<li><a href="https://windows11.techidaily.com/revamping-robustness-of-win11s-cleanup-companion-ccleaner/"><u>Revamping Robustness of Win11's Cleanup Companion, CCleaner</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-hypervisorbsod-in-windows-a-top-ten-approach/"><u>Stop HYPERVISOR_BSOD in Windows: A Top-Ten Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-tasks-top-9-reasons-to-adopt-modernized-outlook/"><u>Streamline Your Tasks: Top 9 Reasons to Adopt Modernized Outlook</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-nvidia-connection-failures-in-10-and-11-editions/"><u>Streamlining Nvidia Connection Failures in 10 & 11 Editions</u></a></li>
<li><a href="https://windows11.techidaily.com/the-7-best-photo-organizer-apps-for-windows/"><u>The 7 Best Photo Organizer Apps For Windows</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/the-authors-secret-weapon-discover-how-chatgpt-revolutionizes-writing/"><u>The Author's Secret Weapon? Discover How ChatGPT Revolutionizes Writing</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-digital-safeguard-guide-spotlight-on-3-chatbot-risks/"><u>The Digital Safeguard Guide: Spotlight on 3 Chatbot Risks</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-fix-guide-stabilizing-ps4-input-link-on-pc/"><u>The Ultimate Fix Guide: Stabilizing PS4 Input Link on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-how-to-fix-older-user-credential-message/"><u>Unlocking: How to Fix Older User Credential Message</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-directdraw-complexities-in-the-latest-microsoft-oses/"><u>Unraveling DirectDraw Complexities in the Latest Microsoft OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/win-specific-error-recovery-reinstating-non-functional-software/"><u>Win-Specific Error Recovery: Reinstating Non-Functional Software</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-cs-go-launch-guide/"><u>Windows 11 CS GO Launch Guide</u></a></li>
</ul></div>
