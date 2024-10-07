---
title: Fixing Drive Unformatted Notice in Windows OS
date: 2024-10-05T21:02:35.013Z
updated: 2024-10-06T22:19:38.224Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Drive Unformatted Notice in Windows OS
excerpt: This Article Describes Fixing Drive Unformatted Notice in Windows OS
keywords: Fix Windows Drive Error,Resolve Unreadable Disk,Remove File System Warning,Clear Drive Notation Issue,Fix Read-Only Windows Drive,Eradicate Unformat Message,Eliminate Bad Sectors Alert
thumbnail: https://thmb.techidaily.com/4e8fed255189bd9ee7a706026d30ffe02100ebaeeb2d7b69ad5a8426d3a0541d.jpg
---

## Fixing Drive Unformatted Notice in Windows OS

 We use external flash drives and hard disks on a regular basis for file transfer and sharing. While cloud sharing is gaining popularity, physical disk sharing is still best suited for large or personal files. You can connect multiple USB devices on your system at the same time and move data from one drive to others.

 But some users encounter the "You Need To Format The Disk In Drive before you can use it" error. It forces you to format the disk before you can use it. However, it isn’t a sensible option if you have important files on the disk. We will list multiple methods using which you can reassess your disk drive. Let’s begin.

## What Are the Reasons Behind the Error Message?

 You can see the “Format Disk in drive” message due to one or more of the following reasons:

1. The USB drive or the port is malfunctioning.
2. The device drivers of the disk are corrupt or outdated.
3. Malware is preventing access to the disk.
4. Core system files have gone missing or corrupt.
5. A third-party app is conflicting with system apps and services.

## Methods to Fix the “You Need to Format the Disk in Drive Before You Can Use It” Error

 Try out the following methods to fix the disk error message and save your data stored on it:

###

### 1\. Check the USB Drive

 If connecting the USB drive to any USB port on your system produces the same error, then unplug it. Connect it to another computer and check if it shows up in Device Manager and you can access the file contents without any issues. If it works, create a copy of all your data on that system for backup purposes.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105859/7443" target="_top" id="2105859">
  <img src="//a.impactradius-go.com/display-ad/7443-2105859" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105859/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2\. Perform a Complete Shutdown

[Microsoft enables Fast Start-up](https://www.makeuseof.com/what-is-windows-fast-startup-why-disable-it/) in newer versions of the Windows operating system by default. It hibernates the system and kernel-level processes so your system boots up faster after a shutdown.

 But if the core system services encounter a glitch and stop working properly, you will see the error message every time. So, performing a complete shutdown can help in restarting all core services.

Repeat the following steps:

1. Press**Win + R** to launch the Run command box.
2. Type**cmd** in the text input box and press**Ctrl + Shift + Enter** to open Command Prompt with administrator privileges.
3. Input the following command and press the enter key:**shutdown /s /f /t 0**  
![Perform a Complete Shutdown](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/perform-a-complete-shutdown.jpg)
4. It will take longer than usual for your system to shut down. Power it on again and open File Explorer.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2139322/26400" target="_top" id="2139322">
  <img src="//a.impactradius-go.com/display-ad/26400-2139322" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2139322/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Click on the USB disk and check if you are able to access the files on it.

### 3\. Do a Clean Boot

 Third-party applications and services can interfere with system apps and impede their normal functioning. So,[perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) of your system. It will disable all the third-party services and programs from running at startup. If you are able to access the disk now, repeat the clean boot process while enabling third-party services one by one to isolate the culprit program.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068408/7443" target="_top" id="2068408">
  <img src="//a.impactradius-go.com/display-ad/7443-2068408" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068408/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 4\. Change the USB Drive Letter Using Disk Management

 Changing the drive letter could help in resolving the USB drive error on your system and make it accessible. Repeat the following steps to change the drive letter:

1. Press**Win + R** to open the Run dialog box. Type**diskmgmt.msc** and press the enter key.
2. In the Disk Management window, find your USB disk drive and right-click on it.
3. Select the**Change Drive Letter and Paths** option from the context menu.
4. Click on the**Change** button. Then, click on the**arrow** button to expand the drop-down list and select a drive letter from it.  
![Change the USB Drive Letter Using Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/change-the-usb-drive-letter-using-disk-management.jpg)
5. Lastly, click on the**OK** button. Reconfirm your decision and click on the**Yes** button to change the Drive letter.
6. You will see a system notification informing you about the Drive letter change and mounting the drive.
7. Press**Win + E** to open the File Explorer and check whether the USB drive is accessible or not.

### 5\. Scan the Hard Disk Using CHKDSK

 It is possible for the USB disk to contain bad files and sectors; due to which Windows asks you to format it before usage. But you can leverage the inbuilt CHKDSK utility to scan the USB disk for errors and fix them for you. It will scan all the files on the disk and repair the drive. You can either use the[command prompt method or Run CheckDisk](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) using the Properties window in File Explorer.

### 6\. Run an SFC and DISM Scan

 If the check disk doesn’t do any good, and you still have the error, it is possible that your system files are missing or corrupt.[Start with an SFC scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) to check and replace any corrupt system files. Follow that up with a[DISM scan to fix the Windows installation image](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) . Make sure you have an active internet connection to run the DISM scan without any issues.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1030380/11832" target="_top" id="1030380">
  <img src="//a.impactradius-go.com/display-ad/11832-1030380" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1030380/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 7\. Use a Linux Installation Media to Access the USB Disk Drive

 This method is more of a workaround to not lose your data. If you don’t have a second system nearby, you can[create a Linux installation media](https://www.makeuseof.com/tag/install-ubuntu-computer-using-usb-flash-drive/) and use the Try Ubuntu mode to mount and access the contents of the USB disk. It will save the effort of searching for another computer, and you can successfully create a backup of the USB disk.

 To access the USB disk using Linux installation media repeat the following steps:

1. Plug the Linux installation media into your system.
2. Press the**Esc** key and power on your system to enter the boot devices menu. Select the Linux installation media and boot it up.
3. In the Grub menu, select the**Try or install Ubuntu** option. Wait for the setup Window to launch and then click on the**Try Ubuntu** option.
4. Go to the left-hand side menu and click on the**Files** app.  
![Use a Linux Installation Media to Access the USB Disk Drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/use-a-linux-installation-media-to-access-the-usb-disk-drive.jpg)
5. Click on the USB disk name in the navigation pane to open it. Now, you can copy these files to another location on your hard drive or an external hard disk.
6. After you finish copying the contents of the USB disk, click on the power icon and choose the Power off option to close the Try Ubuntu mode.

### 8\. Try Generic Fixes for Drive Formatting Issues

 If none of those worked, it's time to apply more general fixes before diving into more drastic measures. There are a few different error messages related to storage drive formatting issues that Windows can throw, and all of them share some common fixes.

 As such, check out[how to fix format disk errors on Windows without formatting your drive](<http://How> to Fix Format Disk Errors Without Formatting Your Hard Drive on Windows) for more tips.

### 9\. Reset Windows

 If nothing seems to work, and you see the error with every USB disk you try to connect to the system, consider a complete Windows reset. It will remove all your system files and installed apps (though you can choose to keep personal files on the system drive).

 However, before[performing a System Reset](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) , try[System Restore](https://www.makeuseof.com/windows-reset-system-restore-difference/) using any available System Restore points. If that fails, and a reset doesn't seem to work, you can[factory reset your Windows computer](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) .

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1001446/11832" target="_top" id="1001446">
  <img src="//a.impactradius-go.com/display-ad/11832-1001446" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1001446/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Access USB Disk Contents Without Formatting

 It is a bad idea to click on the Format button when File Explorer prompts you to do it to access the USB disk. Firstly, try to check the hardware malfunctions and salvage the data on the USB disk. You can use another system or create a Linux installation media to access files on the USB disk.

 If SFC and DISM fail to repair the system, and you still see the error with every USB disk you connect to your system, reset your Windows computer.

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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-elevate-your-visual-narratives-with-mastered-stories-bokeh/"><u>[New] 2024 Approved Elevate Your Visual Narratives with Mastered Stories Bokeh</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-unlocking-youtubes-full-potential-advanced-banner-strategies-for-2024/"><u>[Updated] Unlocking YouTube's Full Potential Advanced Banner Strategies for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/anthropics-toolkit-the-complete-guide-to-claude-3/"><u>Anthropic's Toolkit: The Complete Guide to Claude 3</u></a></li>
<li><a href="https://fox-access.techidaily.com/craft-stunning-photos-with-color-correction/"><u>Craft Stunning Photos with Color Correction</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-commands-in-action-uncovering-windows-error-messages-using-command-line-knowledge/"><u>Expert Commands in Action: Uncovering Windows Error Messages Using Command Line Knowledge</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-revert-the-search-bar-lookup-of-windows-11/"><u>How to Revert the Search Bar Lookup of Windows 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-unlock-a-disable-iphone-11-without-itunes-by-drfone-ios-unlock-ios-unlock/"><u>How to unlock a disable iPhone 11 without itunes</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-vivo-y36-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Vivo Y36 to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://fox-links.techidaily.com/in-2024-professional-radial-effects-step-by-step-guide-for-photoshop-experts/"><u>In 2024, Professional Radial Effects Step-by-Step Guide for Photoshop Experts</u></a></li>
<li><a href="https://windows11.techidaily.com/leading-alternatives-to-procreate-on-windows-platform/"><u>Leading Alternatives to Procreate on Windows Platform</u></a></li>
<li><a href="https://windows11.techidaily.com/rebooting-to-default-power-management-configurations/"><u>Rebooting to Default Power Management Configurations</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-search-master-these-top-5-tricks-for-windows-11/"><u>Streamline Your Search: Master These Top 5 Tricks for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-windows-to-unlock-after-hours/"><u>Tailoring Windows To Unlock After Hours</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-walkthrough-how-to-erase-your-yahoo-mail-presence-forever/"><u>The Ultimate Walkthrough: How To Erase Your Yahoo Mail Presence Forever</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-data-from-realme-narzo-60-5g-by-fonelab-android-recover-data/"><u>Undelete lost data from Realme Narzo 60 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-virtual-capabilities-with-win-11-hypertuned-for-hyper-v/"><u>Unleash Virtual Capabilities with Win 11 Hypertuned for Hyper-V</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-mastering-sound-essential-imovie-audio-enhancement-techniques/"><u>Updated Mastering Sound Essential iMovie Audio Enhancement Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/which-browser-saves-system-resources-winmaccros-edition/"><u>Which Browser Saves System Resources? Win/Mac/CrOS Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/win-against-interfaces-not-supported-by-windows/"><u>Win Against Interfaces Not Supported by Windows</u></a></li>
</ul></div>

