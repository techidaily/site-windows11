---
title: Unraveling File System Errors on Windows
date: 2024-08-22T21:32:33.375Z
updated: 2024-08-23T21:32:33.375Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unraveling File System Errors on Windows
excerpt: This Article Describes Unraveling File System Errors on Windows
keywords: Windows Filesystem Woes,Fixing FS Failures,Resolve WinFS Issues,Debugging Windows FSEs,Windows FSE Troubleshoot,Eliminate WinFS Errors,Correcting File Errors WX
thumbnail: https://thmb.techidaily.com/6a82b15c3b5908dade20c57e5528354889aa2d43fb699583edd3d2db4662000a.jpg
---

## Unraveling File System Errors on Windows

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

 The repair tool will then scan for any corrupted files to repair. If this doesn't work, check out [what to do if Startup Repair fails to fix your PC](https://www.makeuseof.com/what-to-do-if-startup-repair-fails-to-repair-your-pc/).

 Once the repair process begins, avoid interrupting it or turning off your computer. Doing so could corrupt Windows even further.

<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Run the SFC and CHKDSK Tools

 If the startup repair tool does not work, it's time to use the Command Prompt to run the System File Checker and CHKDSK tool.

 The System File Checker (SFC) tool checks your computer for any buggy system files and then tries to fix them. Most of the time, this resolves the disk error issue and other [startup issues on Windows](https://www.makeuseof.com/windows-11-startup-issues-fix/).

 Follow the steps given below to use the System File Checker and CHKDSK:

1. Launch the [Command Prompt with administrator rights](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. On the Command Prompt window, input the **sfc /scannow** command and then **Enter**.
3. Then, type **chkdsk %SystemDrive% /scan** and again press **Enter**.  
![CHKDSK SCAN Command Preview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/chkdsk-scan-command-preview.jpg)

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
 The above-given commands initiates a thorough scan of your system. It might take a while, and once completed, you should no longer see the black screen on startup.

 If you cannot access your desktop, you can also run the Command Prompt and the given commands via Windows safe mode.

 If these commands came in handy, be sure to check out all the [built-in Windows tools that repair corrupted system files](https://www.makeuseof.com/windows-built-in-repair-tools/).

## 4\. Update the Disk Controller Driver

 The "disk controller driver" usually appears under a variety of names, like "Standard SATA AHCI" Controller. It is a Windows driver that establishes communication between your operating system and your hard drive. If the disk controller driver gets outdated, it can lead to disk-related errors.

 Follow these steps to update the disk controller driver on your PC:

1. Press **Win + X** and click on **Device Manager** from the menu.  
![Device Manager In Power Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/device-manager-in-power-menu.jpg)
2. Expand the **IDE ATA/ATAPI controllers** category. Right-click on your disk controller driver (in our case, **Standard SATA AHCI Controller**) and select **Update driver**.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
![Windows 11 Device Manager Preview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-11-device-manager-preview.jpg)
3. Choose **Search automatically for drivers**, then **Search for updated drivers on Windows Update**. Windows will then search for the necessary updates for your disk controller driver.  
![Windows 11 Update Drivers Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-11-update-drivers-window.jpg)
4. Once it installs the driver update, restart your computer. If the error black screen doesn't appear, it means your issue is resolved.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Try a Third-Party Disk Repair Tool

 Sometimes the in-built Windows tools for troubleshooting are of no use. So, you have to depend on third-party tools to investigate the issue. We'll use a free tool called Macrorit Partition Expert for this guide.

 Third-party disk repair tools are not a sure-shot fix. They sometimes work and sometimes create more trouble with the system. So, before using any tool, [create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) as a backup.

 Here's how to use the Macrorit Partition Expert tool on Windows:

1. Download the tool from [the Macrorit website](https://macrorit.com/partition-magic-manager/partition-expert-download.html) and install the application.
2. Click on **dm.exe** to run Macrorit Partition Expert.  
![Macrorit Partition Expert Files](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/macrorit-partition-expert-files.jpg)
3. On the application window, select the disk or volume where your current Windows is present. For example, in our case, it's in **Disk 0**.
4. After selecting, click on **Check Volume** from the left-hand sidebar.  
![Macrorit Partition Expert Application](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/macrorit-partition-expert-application.jpg)
5. Choose **Fix found errors**, **Try to fix found bad sectors**, and click **OK**.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
![Macrorit Partition Expert Volume Checker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/macrorit-partition-expert-volume-checker.jpg)

 Now, Macrorit Partition Expert will analyze your selected disk to check for any bad sectors and try to fix them.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
## 6\. Factory Reset Windows

 If none of the fixes were helpful, you must reinstall Windows OS as a last resort. This will wipe all the data from your computer, so ensure to back up your important data.

 Once you've backed up your files, check out [how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/). Once the reinstallation is complete, you'll have a clean slate to work with, and you can restore all the files you've backed up.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4531356&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8fdd149fcaa7058caccc9c4ad5b0d89a/products/tss-box.JPG" border="0">The Tube Sites Submitter is a fast and efficient tool for anyone who needs to upload videos quickly, easily and automatically to hundreds of tube sites in mere minutes . </a>
<!-- affiliate ads end -->
## No More Disk Errors on Windows

 As said earlier, there's no fixed reason for the repairing disk error. However, one thing that causes the error is an issue with your disks, such as bad sectors, physical damage, and viruses.

 If you fail to resolve the issue, consider resetting your computer and fresh set up everything.

 Let's look at various methods to repair the disk issue on your Windows device.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-facebooks-unique-media-the-top-ios-downloader-tools-revealed-today/"><u>[New] 2024 Approved  Facebook's Unique Media  The Top iOS Downloader Tools Revealed Today</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-audio-ambition-realized-cutting-edge-recording-methods-for-minecraft-players/"><u>[New] In 2024, Audio Ambition Realized  Cutting-Edge Recording Methods for Minecraft Players</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-top-10-text-presets-for-visual-impact/"><u>[New] Top 10 Text Presets for Visual Impact</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-identifying-the-top-10-hidden-story-admirers/"><u>[Updated] 2024 Approved  Identifying the Top 10 Hidden Story Admirers</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-setting-the-price-for-higher-youtube-engagement/"><u>[Updated] 2024 Approved  Setting the Price for Higher YouTube Engagement</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-video-streamers-essentials-ultimate-hd-camera-guide/"><u>[Updated] Video Streamers' Essentials – Ultimate HD Camera Guide</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-quick-and-easy-instructions-for-launching-skype-group-conversations-on-both-windows-and-macos/"><u>2024 Approved  Quick and Easy Instructions for Launching Skype Group Conversations on Both Windows & MacOS</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-or-see-text-messages-what-can-you-do-with-life360-on-vivo-t2-5g-drfone-by-drfone-virtual-android/"><u>Can Life360 Track Or See Text Messages? What Can You Do with Life360 On Vivo T2 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/harnessing-the-power-of-linux-inside-a-windows-os/"><u>Harnessing the Power of Linux Inside a Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/harnessing-windows-powers-for-linux-enhancement/"><u>Harnessing Windows Powers for Linux Enhancement</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-bypass-icloud-lock-from-iphone-13-pro-max-by-drfone-ios/"><u>How to Bypass iCloud Lock from iPhone 13 Pro Max</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reactivate-a-non-operational-lunar-client-in-os/"><u>How to Reactivate a Non-Operational Lunar Client in OS</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-apple-iphone-14-drfone-by-drfone-virtual-ios/"><u>In 2024, 15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Apple iPhone 14 | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-3-effective-methods-to-fake-gps-location-on-android-for-your-lava-agni-2-5g-drfone-by-drfone-virtual/"><u>In 2024, 3 Effective Methods to Fake GPS location on Android For your Lava Agni 2 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/initiate-your-adventure-joining-win-11-insiders/"><u>Initiate Your Adventure: Joining Win 11 Insiders</u></a></li>
<li><a href="https://tech-haven.techidaily.com/introducing-gpt-4-by-openai-pioneering-a-new-era-in-artificial-general-intelligence/"><u>Introducing GPT-4 by OpenAI – Pioneering a New Era in Artificial General Intelligence</u></a></li>
<li><a href="https://windows11.techidaily.com/keeping-calculator-top-displayed-in-windows/"><u>Keeping Calculator Top-Displayed in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/lightweight-window-navigators-ram-usage-tested-and-rated/"><u>Lightweight Window Navigators: Ram Usage Tested and Rated</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-world-of-remote-device-collaboration-googlewindows/"><u>Navigating the World of Remote Device Collaboration: Google/Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/power-up-your-workflow-essential-tools-for-win-11-pros/"><u>Power Up Your Workflow: Essential Tools for Win 11 Pros</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-non-terminable-tasks-on-windows-pcs/"><u>Quick Fixes for Non-Terminable Tasks on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/reactivating-frozen-discord-widgets-on-windows-desktop/"><u>Reactivating Frozen Discord Widgets on Windows Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/reestablishing-active-slack-signals-in-windows-11/"><u>Reestablishing Active Slack Signals in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-absence-of-files-alerts-in-windows-11/"><u>Remedying Absence of Files Alerts in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/repairing-rough-operations-with-ccleaner-in-win11/"><u>Repairing Rough Operations with CCleaner in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-screen-not-responsive-in-windows-11-and-11/"><u>Resolving Screen Not Responsive in Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-up-microsofts-defender-on-edge-win-11-guide/"><u>Setting Up Microsoft's Defender on Edge: Win 11 Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/smooth-transition-to-emoji-15-for-windows-11-users/"><u>Smooth Transition to Emoji 15 for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/solo-system-imaging-techniques-for-win-users/"><u>Solo System Imaging Techniques for Win Users</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-ensure-precise-cpu-usage-readings-from-task-manager/"><u>Strategies to Ensure Precise CPU Usage Readings From Task Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-browsing-with-mouse-gestures-in-microsoft-edge/"><u>Streamline Your Browsing with Mouse Gestures in Microsoft Edge</u></a></li>
<li><a href="https://windows11.techidaily.com/subtlety-shifts-concealing-win-11s-control/"><u>Subtlety Shifts: Concealing Win 11'S Control</u></a></li>
<li><a href="https://windows11.techidaily.com/tech-refresh-3000-revolutionary-windows-rebooting/"><u>Tech Refresh 3000: Revolutionary Windows Rebooting</u></a></li>
<li><a href="https://windows11.techidaily.com/tutorial-activating-and-launching-ms-paint-in-windows-11/"><u>Tutorial: Activating and Launching MS Paint in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-system-potential-mastery-of-win-registry-cli-edits/"><u>Unlocking System Potential: Mastery of Win Registry CLI Edits</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-wasd-segregating-sounds-effectively/"><u>Windows WASD: Segregating Sounds Effectively?</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>