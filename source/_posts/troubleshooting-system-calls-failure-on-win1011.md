---
title: Troubleshooting System Calls Failure on Win10/11
date: 2024-09-05T02:13:45.160Z
updated: 2024-09-06T02:13:45.160Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting System Calls Failure on Win10/11
excerpt: This Article Describes Troubleshooting System Calls Failure on Win10/11
keywords: Windows Call Issue Resolution,Win10 Syscall Troubleshoot,Fixing Syscalls in Win10,Win11 Syscall Failure Guide,Solving Windows Syscall Errors,Win10/Win11 Syscall Problems,Debugging System Calls on Windows 10/11
thumbnail: https://thmb.techidaily.com/3f45b4986206d046cd956542a295fe465671e73b81f9c11e8f6862999203849a.jpg
---

## Troubleshooting System Calls Failure on Win10/11

 The “system call failed” error message is a common error that usually pops up when you try to open File Explorer. However, this error message can also affect the Start menu. When this error occurs, you cannot access File Explorer or other Windows features affected by this error.

 The “system call failed” error stems from File Explorer’s explorer.exe process. This is how you can fix the “System call failed” Windows 11/10 error.

## 1\. Restart Windows File Explorer

![The Processes tab in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-restart-option2.jpg)

 Restarting the explorer.exe process can fix the “System call failed” error. It's a really easy and quick fix, so it's a good starting point for troubleshooting the “system call failed” error.

 You can restart the explorer.exe process with Task Manager, as covered in this guide on [how to restart File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/).

## 2\. Run the SFC and DISM Tools in Command Prompt

![Windows System File Checker tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow.jpg)

 Corrupted system files could be causing File Explorer to crash. As such, it's worth running the System File Checker (SFC). This tool is a Windows Command-Prompt utility that checks for and repairs system files.

 On top of that, the Deployment Image Serving and Management (DISM) tool can fix errors within the Windows system image. It's worth running the DISM tool before the SFC scan to check for any errors that may affect the SFC scan's efficiency.

 You can learn how to run both the SFC and DISM commands in our guide to [repairing system files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

<!-- affiliate ads begin -->
<span id="1531882">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1531882.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1531882">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1531882.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1531882%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1531882/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Check For Disk Errors With CHKDSK

 A failing hard drive is another potential cause of the “system call failed” error. You can check for and repair disk errors with the Check Disk (CHKDSK) tool on Windows.

 Our [how to run CHKDSK](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) guide explains how you can utilize the Check Disk tool.

## 4\. Initiate a Malwarebytes Scan

 Malware can cause many kinds of crashes to occur on Windows. The “system call failed” error could be occurring because of malware on your PC.

 You can scan for malware with many antivirus apps, including Windows Security. However, Malwarebytes is one of the [best free antivirus software for Windows](https://www.makeuseof.com/tag/ten-best-antivirus-programs/). So, try running a Malwarebytes scan like this:

1. Go to the [Malwarebytes download page](https://www.anrdoezrs.net/links/7251228/type/dlg/sid/UUmuoUeUpU2028435/https://www.malwarebytes.com/mwb-download) and download the tool from there.
2. Open the **MBSetup** file from your Downloads folder and click **Install**.
3. Next, click **Skip** if you don’t want to install the additional software offered.
4. Select **Open Malwarebytes** to run the software.
5. Click **Scan** to initiate a malware scan.  
![The Scan option in Malwarebytes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-scan-option.jpg)
6. Select **Quarantine** and **Yes** if Malwarebytes detects malware.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100534/7443" target="_top" id="2100534">
  <img src="//a.impactradius-go.com/display-ad/7443-2100534" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100534/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094480/7443" target="_top" id="2094480">
  <img src="//a.impactradius-go.com/display-ad/7443-2094480" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094480/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Disable Startup Items and Services With a Clean Boot

 Another possibility is that a third-party program or service is conflicting or interfering with the File Explorer processing, causing the “System call failed” error to occur on your PC.

 You can address a software conflict by disabling all third-party startup items and services, which is otherwise the clean booting troubleshooting method. You can apply that troubleshooting method by following the instructions in this guide on [performing a clean boot in Windows](https://www.makeuseof.com/how-perform-clean-boot-windows-10/).

 Restart your PC when you’ve disabled all third-party startup items and services. Then try opening File Explorer again to check if this “System call failed” error continues.

 If the error is fixed after clean booting, it will probably reoccur if you re-enable all startup apps and services again. You can try to identify what’s causing the error by gradually re-enabling items, and then disabling the startup app or service that triggers the issue again.

![Services tab on Windows Configuration menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-services-tab5.jpg)

## 6\. Restore Windows 11/10 to an Earlier Time

 System Restore is a tool that rolls Windows 11/10 back to a backup image, otherwise called a restore point. Restoring Windows to a date that predated the “System call failed” error on your PC might fix system file issues. Doing so will also remove third-party software installed on your PC after the restoration date that could be causing the issue.

 However, this potential resolution will only be effective if you can select a restoration point that predates the issue. If you don’t have System Restore enabled, you may as well skip to the next possible solution. If you do keep restoration points, try rolling back Windows 11/10 to an earlier time as covered within our [guide to utilizing System Restore](https://www.makeuseof.com/use-system-restore-windows/).

![Restore Points in System Restore](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restore-points-in-system-restore.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2027167/19272" target="_top" id="2027167">
  <img src="//a.impactradius-go.com/display-ad/19272-2027167" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2027167/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 7\. Apply a Factory Reset

 A factory reset will restore your Windows PC to a default (out-of-the-box) system configuration. Applying a factory reset is a drastic potential resolution but one that will likely resolve the “System call failed” error. It will mean you lose user-installed software that will then have to be reinstalled.

 The standard method for applying a factory reset is to utilize the Reset this PC tool. That includes a few options you can select for the reset and one of those is to keep user files. This [how-to reset Windows guide](http://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) has instructions for applying a factory reset.

![The Keep my files option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/reset-this-pc-tool4.jpg)

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/977686/11832" target="_top" id="977686">
  <img src="//a.impactradius-go.com/display-ad/11832-977686" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/977686/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049388/7443" target="_top" id="2049388">
  <img src="//a.impactradius-go.com/display-ad/7443-2049388" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049388/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get the “System Call Failed” Error Fixed

 Those “System call failed” error solutions are confirmed to work by many users who have needed to resolve that File Explorer issue.

 So, it’s very likely one will solve that issue, so you can fully utilize File Explorer again. If none of those resolutions are enough, consider contacting the Microsoft Windows support service for further guidance.

 The “system call failed” error stems from File Explorer’s explorer.exe process. This is how you can fix the “System call failed” Windows 11/10 error.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-data.techidaily.com/hort-sensation-keywords-for-enhancing-video-shows-virality-for-2024/"><u>[New] Short Sensation  Keywords for Enhancing Video Shows' Virality for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-efficient-techniques-for-saving-online-meeting-transcripts-for-2024/"><u>[Updated] Efficient Techniques for Saving Online Meeting Transcripts for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-elite-5-video-snapshot-recorders/"><u>[Updated] In 2024, Elite 5 Video Snapshot Recorders</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-yi-in-focus-the-future-of-4k-filmmaking/"><u>2024 Approved  Yi in Focus  The Future of 4K Filmmaking</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/diagnosing-and-repairing-a-malfunctioning-samsung-audio-bar/"><u>Diagnosing and Repairing a Malfunctioning Samsung Audio Bar</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/discover-the-best-7-alarm-clock-apps-available-today/"><u>Discover the Best 7 Alarm Clock Apps Available Today</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-techniques-to-resurrect-an-unopenable-notepad-on-pc/"><u>Essential Techniques to Resurrect an Unopenable Notepad on PC</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/essential-tools-for-effective-adobe-presentation-recordings-for-2024/"><u>Essential Tools for Effective Adobe Presentation Recordings for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-keep-onedrive-available-offline-in-windows/"><u>How To Keep OneDrive Available Offline in Windows</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-deciphering-the-benefits-in-depth-look-at-bandicams-capabilities/"><u>In 2024, Deciphering the Benefits  In-Depth Look at Bandicam's Capabilities</u></a></li>
<li><a href="https://windows11.techidaily.com/innovative-design-techniques-for-customizing-windows-outlook-calendars/"><u>Innovative Design Techniques for Customizing Windows Outlook Calendars</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-adobe-reader-installation-via-microsoft-store/"><u>Mastering Adobe Reader: Installation via Microsoft Store</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-clearing-blocked-windows-files/"><u>Mastering the Art of Clearing Blocked Windows Files</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-copying-custom-powertoys-configurations/"><u>Mastering the Art of Copying Custom PowerToys Configurations</u></a></li>
<li><a href="https://win-solutions.techidaily.com/modern-warfare-trouble-shoot-fixing-the-perplexing-developer-error-6034-across-ps5-xbox-series-xs-and-computers/"><u>Modern Warfare Trouble Shoot: Fixing the Perplexing Developer Error 6034 Across PS5, Xbox Series X/S, and Computers</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-to-index-settings-on-windows/"><u>Navigate to Index Settings on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-maze-of-unacceptable-connections-on-windows/"><u>Navigating the Maze of Unacceptable Connections on Windows</u></a></li>
<li><a href="https://hardware-help.techidaily.com/navigating-the-world-of-gadgets-with-tom-expert-hardware-guidance/"><u>Navigating the World of Gadgets with Tom - Expert Hardware Guidance</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-the-digital-maze-essential-changes-in-windows-11s-file-system/"><u>Navigating Through the Digital Maze: Essential Changes in Windows 11'S File System</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-the-maze-of-0x80860010-application-overload/"><u>Navigating Through the Maze of 0X80860010 Application Overload</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-the-maze-of-windows-camera-troubles/"><u>Navigating Through the Maze of Windows Camera Troubles</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-connectivity-issues-between-nvidia-geforce-and-windows-11/"><u>Overcoming Connectivity Issues Between Nvidia GeForce and Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-typical-rainmeter-hurdles-in-the-windows-realm/"><u>Overcoming Typical Rainmeter Hurdles in the Windows Realm</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-remedy-for-screens-that-tick-in-windows-11/"><u>Quick Remedy for Screens that Tick in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/removing-borders-with-technique-and-precision-tools/"><u>Removing Borders with Technique and Precision Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/revitalizing-old-drivers-the-ultimate-window-fix-up/"><u>Revitalizing Old Drivers: The Ultimate Window Fix-Up</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-your-sanctuary-swift-fixes-for-windows-safety/"><u>Secure Your Sanctuary: Swift Fixes for Windows Safety</u></a></li>
<li><a href="https://windows11.techidaily.com/sidestepping-windows-update-error-code-0x80242016/"><u>Sidestepping Windows Update Error Code 0X80242016</u></a></li>
<li><a href="https://windows11.techidaily.com/speedy-data-retrieval-on-pc-embracing-everythingapp/"><u>Speedy Data Retrieval on PC: Embracing EverythingApp</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-boosting-network-connectivity-via-windows/"><u>Step-by-Step: Boosting Network Connectivity via Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-non-functional-google-nearby-share-window/"><u>Steps to Resolve Non-Functional Google Nearby Share Window</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-fix-error-code-0x0001-in-geforce-experience/"><u>Strategies to Fix Error Code 0X0001 in GeForce Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-overcome-windows-error-code-87-with-loadlibrary/"><u>Strategies to Overcome Windows Error Code 87 with LoadLibrary</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-linguistic-navigation-on-windows-11-and-11-pro-with-shortcuts/"><u>Swift Linguistic Navigation on Windows 11 & 11 Pro with Shortcuts</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-erasing-windows-11s-task-view/"><u>The Art of Erasing Windows 11'S Task View</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-bypassing-cannot-end-task-error-in-windows/"><u>Tips for Bypassing 'Cannot End Task Error' In Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-on-preventing-windows-notepad-hangouts/"><u>Tips on Preventing Windows Notepad Hangouts</u></a></li>
<li><a href="https://windows11.techidaily.com/top-10-tips-regain-control-with-steam-support/"><u>Top 10 Tips: Regain Control with Steam Support</u></a></li>
<li><a href="https://windows11.techidaily.com/tricks-for-efficient-memory-management-in-windows/"><u>Tricks for Efficient Memory Management in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-code-0xa00f4289-in-windows-webcam-errors/"><u>Troubleshooting Code 0xA00F4289 in Windows Webcam Errors</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-successful-steps-to-get-internet-explorer-up-and-running-again/"><u>Troubleshooting: Successful Steps to Get Internet Explorer Up and Running Again</u></a></li>
<li><a href="https://windows11.techidaily.com/unplugging-troubles-stay-aware-of-power-save-mode/"><u>Unplugging Troubles: Stay Aware of Power Save Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-over-sluggishness-speedy-printer-solutions-windows-style/"><u>Winning over Sluggishness: Speedy Printer Solutions, Windows-Style</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>