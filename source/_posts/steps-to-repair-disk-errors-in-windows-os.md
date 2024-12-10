---
title: Steps to Repair Disk Errors in Windows OS
date: 2024-12-09T20:45:09.446Z
updated: 2024-12-10T17:40:10.750Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Repair Disk Errors in Windows OS
excerpt: This Article Describes Steps to Repair Disk Errors in Windows OS
keywords: Fix Disk Issues Windows,Solve Errors Windows Drive,Windows Error Recovery Steps,Correcting Disk Problems Windows,Mend Windows Storage Errors,Remedy Windows Hard Disk Errors,Resolve Windows Data Access Issue
thumbnail: https://thmb.techidaily.com/4708f3ad86d66e7ad10dd3b75bdecccf20aa6cf32be5cc5adbe8d57734cb7714.jpg
---

## Steps to Repair Disk Errors in Windows OS

 Errors and bugs can pop up on your Windows device, no matter how well you maintain it. One such error is related to your computer's disk, which can prevent your system from booting up properly and restrict access to your files and applications.

 Let's look at various methods to repair the disk issue on your Windows device.

## Why Does the "Repairing Disk Errors" Issue Occur?

 When the disk error occurs, your computer reboots with an error message: "**Repairing disk errors. This might take over an hour to complete.**" Most of the time, this error will just show up once and won't appear the next time you reboot, but sometimes it will show up every single time you boot your PC.

 Usually, this error is caused by:

* A sudden power failure.
* An improper system shutdown.
* Physical damage to your hard drive.
* Corrupted Windows system.

 Now let’s look at possible troubleshooting ways to fix the repairing disk error on your Windows device.

## 1\. Start With These Basic Fixes

 When your Windows computer starts showing disk errors, there are a few initial steps you can take before moving on to more advanced solutions. Here's what we recommend doing:

* **Wait for an hour to pass:** Sometimes, the easiest solution is to wait. If this is the first time you've encountered this error message in a while (if ever), give it an hour, and the error might resolve itself, allowing your computer to reboot normally.
* **Check your drive for physical damage:** If your drive has suffered physical damage, this can lead to this error constantly popping up. Inspect your disk drive for any damage.
* **Revert to a previous time with a System Restore point:** System Restore undoes recent system changes without affecting your files. If the error started appearing recently, try [using System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/) and see if that fixes things.

 If the above solutions are not working for you, it's time to get started with the advanced troubleshooting methods.

## 2\. Run the Startup Repair Utility

 The Startup Repair tool is a built-in Windows feature to fix problems preventing your computer from starting correctly. This tool can be a lifesaver if your system keeps encountering errors when booting up.

 Here's how you can use the Startup Repair tool on your computer:

1. Launch the Settings app and go to **System > Recovery**.
2. On the Settings window, click on **Restart now** button (located next to **Advanced startup**).  
![Advanced Startup Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/advanced-startup-option.jpg)
3. A blue-colored screen must appear now. From there, click on **Troubleshoot > Advanced options** and then **Startup Repair**.  
![Startup Repair Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/startup-repair-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlpdv0cz_k?si=HwTdnMmeVJXm4GPV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The repair tool will then scan for any corrupted files to repair. If this doesn't work, check out [what to do if Startup Repair fails to fix your PC](https://www.makeuseof.com/what-to-do-if-startup-repair-fails-to-repair-your-pc/).

 Once the repair process begins, avoid interrupting it or turning off your computer. Doing so could corrupt Windows even further.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Run the SFC and CHKDSK Tools

 If the startup repair tool does not work, it's time to use the Command Prompt to run the System File Checker and CHKDSK tool.

 The System File Checker (SFC) tool checks your computer for any buggy system files and then tries to fix them. Most of the time, this resolves the disk error issue and other [startup issues on Windows](https://www.makeuseof.com/windows-11-startup-issues-fix/).

 Follow the steps given below to use the System File Checker and CHKDSK:

1. Launch the [Command Prompt with administrator rights](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. On the Command Prompt window, input the **sfc /scannow** command and then **Enter**.
3. Then, type **chkdsk %SystemDrive% /scan** and again press **Enter**.  
![CHKDSK SCAN Command Preview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/chkdsk-scan-command-preview.jpg)

 The above-given commands initiates a thorough scan of your system. It might take a while, and once completed, you should no longer see the black screen on startup.

 If you cannot access your desktop, you can also run the Command Prompt and the given commands via Windows safe mode.

 If these commands came in handy, be sure to check out all the [built-in Windows tools that repair corrupted system files](https://www.makeuseof.com/windows-built-in-repair-tools/).

## 4\. Update the Disk Controller Driver

 The "disk controller driver" usually appears under a variety of names, like "Standard SATA AHCI" Controller. It is a Windows driver that establishes communication between your operating system and your hard drive. If the disk controller driver gets outdated, it can lead to disk-related errors.

 Follow these steps to update the disk controller driver on your PC:

1. Press **Win + X** and click on **Device Manager** from the menu.  
![Device Manager In Power Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/device-manager-in-power-menu.jpg)
2. Expand the **IDE ATA/ATAPI controllers** category. Right-click on your disk controller driver (in our case, **Standard SATA AHCI Controller**) and select **Update driver**.  
![Windows 11 Device Manager Preview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-11-device-manager-preview.jpg)
3. Choose **Search automatically for drivers**, then **Search for updated drivers on Windows Update**. Windows will then search for the necessary updates for your disk controller driver.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/szUqw4TLvWs?si=srv1OeLOe579gLwj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Windows 11 Update Drivers Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-11-update-drivers-window.jpg)
4. Once it installs the driver update, restart your computer. If the error black screen doesn't appear, it means your issue is resolved.

## 5\. Try a Third-Party Disk Repair Tool

 Sometimes the in-built Windows tools for troubleshooting are of no use. So, you have to depend on third-party tools to investigate the issue. We'll use a free tool called Macrorit Partition Expert for this guide.

 Third-party disk repair tools are not a sure-shot fix. They sometimes work and sometimes create more trouble with the system. So, before using any tool, [create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) as a backup.

 Here's how to use the Macrorit Partition Expert tool on Windows:

1. Download the tool from [the Macrorit website](https://macrorit.com/partition-magic-manager/partition-expert-download.html) and install the application.
2. Click on **dm.exe** to run Macrorit Partition Expert.  
![Macrorit Partition Expert Files](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/macrorit-partition-expert-files.jpg)
3. On the application window, select the disk or volume where your current Windows is present. For example, in our case, it's in **Disk 0**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E1ax-vnGdeo?si=bgTkOhOEwDTlRQE3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. After selecting, click on **Check Volume** from the left-hand sidebar.  
![Macrorit Partition Expert Application](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/macrorit-partition-expert-application.jpg)
5. Choose **Fix found errors**, **Try to fix found bad sectors**, and click **OK**.  
![Macrorit Partition Expert Volume Checker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/macrorit-partition-expert-volume-checker.jpg)

 Now, Macrorit Partition Expert will analyze your selected disk to check for any bad sectors and try to fix them.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0pSRlspzW-A?si=A82G3Yxwj_31cKDq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Factory Reset Windows

 If none of the fixes were helpful, you must reinstall Windows OS as a last resort. This will wipe all the data from your computer, so ensure to back up your important data.

 Once you've backed up your files, check out [how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/). Once the reinstallation is complete, you'll have a clean slate to work with, and you can restore all the files you've backed up.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qfCSLAhd4FY?si=CUBztmilaeAwl1lw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## No More Disk Errors on Windows

 As said earlier, there's no fixed reason for the repairing disk error. However, one thing that causes the error is an issue with your disks, such as bad sectors, physical damage, and viruses.

 If you fail to resolve the issue, consider resetting your computer and fresh set up everything.

 Let's look at various methods to repair the disk issue on your Windows device.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-ios-meets-classic-play-best-ps2-game-emulators-reviewed/"><u>[New] 2024 Approved IOS Meets Classic Play Best PS2 Game Emulators Reviewed</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-god-of-war-ragnarok-release-date/"><u>[Updated] 2024 Approved God of War Ragnarok Release Date</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-8-free-online-video-editors-for-youtube/"><u>[Updated] In 2024, 8 Free Online Video Editors for YouTube</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-laugh-loops-crafting-comical-content-for-brevity-based-videos/"><u>[Updated] Laugh Loops Crafting Comical Content for Brevity-Based Videos</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-fabricate-funny-faces/"><u>2024 Approved Fabricate Funny Faces</u></a></li>
<li><a href="https://blog-min.techidaily.com/effortless-transformation-convert-your-blu-ray-discs-to-high-quality-avchd-format-using-our-advanced-conversion-tool/"><u>Effortless Transformation: Convert Your Blu-Ray Discs to High-Quality AVCHD Format Using Our Advanced Conversion Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/get-a-free-self-hosted-gptclone-with-gpt4all/"><u>Get a Free, Self-Hosted GPTClone with GPT4All.</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-latest-guide-how-to-bypass-realme-12-proplus-5g-frp-without-computer-by-drfone-android/"><u>In 2024, Latest Guide How To Bypass Realme 12 Pro+ 5G FRP Without Computer</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-10-telegram-spy-tools-on-nokia-c110-for-parents-drfone-by-drfone-virtual-android/"><u>In 2024, Top 10 Telegram Spy Tools On Nokia C110 for Parents | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/master-plain-text-and-mouse-jump-methods-in-powertoys/"><u>Master Plain Text & Mouse Jump Methods in PowerToys</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-auto-delete-for-windows-11-files-a-step-by-step-guide/"><u>Mastering Auto-Delete for Windows 11 Files: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-store-faults-error-x80072f17-guidance/"><u>Navigating Windows Store Faults: Error X80072F17 Guidance</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-security-adjusting-lockout-count-after-failed-attempts/"><u>Optimizing Security: Adjusting Lockout Count After Failed Attempts</u></a></li>
<li><a href="https://windows11.techidaily.com/reactivation-roadmap-reviving-winget-in-w11-environment/"><u>Reactivation Roadmap: Reviving Winget in W11 Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-software-management-using-windows-package-manager/"><u>Simplifying Software Management Using Windows Package Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-solve-error-0x80370102-during-windows-subsystem-for-linux-installation/"><u>Steps to Solve Error 0X80370102 During Windows Subsystem for Linux Installation</u></a></li>
<li><a href="https://win-able.techidaily.com/troubleshooting-guide-fixing-wolcen-lords-of-mayhem-unavailable-issue/"><u>Troubleshooting Guide: Fixing 'Wolcen: Lords of Mayhem' Unavailable Issue</u></a></li>
<li><a href="https://win-dash.techidaily.com/universal-3gpmp4-converter-easily-transform-videos-between-popular-formats-like-avi-mkv-mpg-more/"><u>Universal 3GP/MP4 Converter: Easily Transform Videos Between Popular Formats Like AVI, MKV, MPG More!</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-windows-xp-potential-without-the-compatibility-tool/"><u>Unlock Windows XP Potential Without the Compatibility Tool</u></a></li>
</ul></div>

