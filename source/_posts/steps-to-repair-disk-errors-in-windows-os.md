---
title: Steps to Repair Disk Errors in Windows OS
date: 2024-08-15T16:16:54.271Z
updated: 2024-08-16T16:16:54.271Z
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->

 The repair tool will then scan for any corrupted files to repair. If this doesn't work, check out [what to do if Startup Repair fails to fix your PC](https://www.makeuseof.com/what-to-do-if-startup-repair-fails-to-repair-your-pc/).

 Once the repair process begins, avoid interrupting it or turning off your computer. Doing so could corrupt Windows even further.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
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
![Windows 11 Device Manager Preview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-11-device-manager-preview.jpg)
3. Choose **Search automatically for drivers**, then **Search for updated drivers on Windows Update**. Windows will then search for the necessary updates for your disk controller driver.  
![Windows 11 Update Drivers Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-11-update-drivers-window.jpg)
4. Once it installs the driver update, restart your computer. If the error black screen doesn't appear, it means your issue is resolved.

## 5\. Try a Third-Party Disk Repair Tool

 Sometimes the in-built Windows tools for troubleshooting are of no use. So, you have to depend on third-party tools to investigate the issue. We'll use a free tool called Macrorit Partition Expert for this guide.

 Third-party disk repair tools are not a sure-shot fix. They sometimes work and sometimes create more trouble with the system. So, before using any tool, [create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) as a backup.

 Here's how to use the Macrorit Partition Expert tool on Windows:

1. Download the tool from [the Macrorit website](https://macrorit.com/partition-magic-manager/partition-expert-download.html) and install the application.
2. Click on **dm.exe** to run Macrorit Partition Expert.  
![Macrorit Partition Expert Files](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/macrorit-partition-expert-files.jpg)
<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. On the application window, select the disk or volume where your current Windows is present. For example, in our case, it's in **Disk 0**.
4. After selecting, click on **Check Volume** from the left-hand sidebar.  
![Macrorit Partition Expert Application](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/macrorit-partition-expert-application.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Choose **Fix found errors**, **Try to fix found bad sectors**, and click **OK**.  
![Macrorit Partition Expert Volume Checker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/macrorit-partition-expert-volume-checker.jpg)
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now, Macrorit Partition Expert will analyze your selected disk to check for any bad sectors and try to fix them.

<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
## 6\. Factory Reset Windows

 If none of the fixes were helpful, you must reinstall Windows OS as a last resort. This will wipe all the data from your computer, so ensure to back up your important data.

 Once you've backed up your files, check out [how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/). Once the reinstallation is complete, you'll have a clean slate to work with, and you can restore all the files you've backed up.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
## No More Disk Errors on Windows

 As said earlier, there's no fixed reason for the repairing disk error. However, one thing that causes the error is an issue with your disks, such as bad sectors, physical damage, and viruses.

 If you fail to resolve the issue, consider resetting your computer and fresh set up everything.

 Let's look at various methods to repair the disk issue on your Windows device.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-chaptered-cinema-the-essential-guide-to-vimeo-editing/"><u>[New] In 2024, Chaptered Cinema  The Essential Guide to Vimeo Editing</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-navigating-the-landscape-post-vlc-dominance-for-2024/"><u>[New] Navigating the Landscape Post-VLC Dominance for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-authoritative-insights-on-premium-auto-cam-tech/"><u>[Updated] Authoritative Insights on Premium Auto Cam Tech</u></a></li>
<li><a href="https://win11.techidaily.com/10-quick-tips-recognizing-your-xbox-controller-in-windows/"><u>10 Quick Tips: Recognizing Your Xbox Controller in Windows</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-conclusion/"><u>2024 Approved  Conclusion</u></a></li>
<li><a href="https://unlock-android.techidaily.com/a-perfect-guide-to-remove-or-disable-google-smart-lock-on-xiaomi-14-ultra-by-drfone-android/"><u>A Perfect Guide To Remove or Disable Google Smart Lock On Xiaomi 14 Ultra</u></a></li>
<li><a href="https://windows11.techidaily.com/claim-your-potential-in-windows-11-regain-missing-system-upgrades/"><u>Claim Your Potential in Windows 11: Regain Missing System Upgrades</u></a></li>
<li><a href="https://windows11.techidaily.com/climate-control-experts-the-finest-windows-11-apps/"><u>Climate Control Experts: The Finest Windows 11 Apps</u></a></li>
<li><a href="https://driver-install.techidaily.com/easy-driver-installation-making-3dconnexion-work/"><u>Easy Driver Installation: Making 3Dconnexion Work</u></a></li>
<li><a href="https://windows11.techidaily.com/embracing-ai-with-microsoft-copilot-writes-and-debugging/"><u>Embracing AI with Microsoft Copilot' Writes and Debugging</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-elevation-problem-with-error-code-740-on-windows-11/"><u>Fixing Elevation Problem with Error Code 740 on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-display-more-pinned-items-on-the-windows-11-start-menu/"><u>How to Display More Pinned Items on the Windows 11 Start Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-mute-cortana-in-windows-11-os/"><u>How to Mute Cortana in Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reach-windows-11s-account-control-interface/"><u>How to Reach Windows 11'S Account Control Interface</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-unlock-a-disable-iphone-14-pro-by-drfone-ios-unlock-ios-unlock/"><u>How to unlock a disable iPhone 14 Pro</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-exclusive-list-skypes-top-audio-recorders/"><u>In 2024, Exclusive List  Skype's Top Audio Recorders</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-unlock-itel-a70-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>In 2024, Unlock Itel A70 Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/intuitive-action-capture-in-depth-analysis-of-the-budget-friendly-z-edge-z3-plus/"><u>Intuitive Action Capture: In-Depth Analysis of the Budget-Friendly Z-Edge Z3 Plus</u></a></li>
<li><a href="https://extra-skills.techidaily.com/master-guide-to-choosing-your-mp4-player-for-2024/"><u>Master Guide to Choosing Your MP4 Player for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-mspcm-bar-with-finesse-in-windows-11-environment/"><u>Navigating MSPCM Bar with Finesse in Windows 11 Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-22h2-windows-woes/"><u>Navigating Through 22H2 Windows Woes</u></a></li>
<li><a href="https://ai-topics.techidaily.com/new-the-recommended-natural-ai-hindi-voice-generator-for-2024/"><u>New The Recommended Natural AI Hindi Voice Generator for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/optimal-start-menu-no-commercials-here/"><u>Optimal Start Menu: No Commercials Here!</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-clouds-hurdle-7-ways-to-reconnect-google-drive/"><u>Overcoming the Cloud's Hurdle: 7 Ways to Reconnect Google Drive</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-discord-from-launching-with-every-system-boots/"><u>Preventing Discord From Launching with Every System Boots</u></a></li>
<li><a href="https://windows11.techidaily.com/prove-your-prowess-top-7-zero-cost-pc-password-apps/"><u>Prove Your Prowess: Top 7 Zero-Cost PC Password Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-package-registration-failures-on-windows-devices/"><u>Resolving Package Registration Failures on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-ethernet-signal-in-windows-os/"><u>Securing Ethernet Signal in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-windows-pre-format-drive-errors/"><u>Solving Windows' Pre-Format Drive Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-xp709-system-failure/"><u>Strategies for XP709 System Failure</u></a></li>
<li><a href="https://some-guidance.techidaily.com/tech-talk-optimizing-for-the-apple-store-for-2024/"><u>Tech Talk  Optimizing for the Apple Store for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/top-10-tiktok-strategies-for-winning-campaigns-for-2024/"><u>Top 10 TikTok Strategies for Winning Campaigns for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-windows-from-s-mode-shackles/"><u>Unraveling Windows: From S Mode Shackles</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-and-linux-how-wsl-changes-the-game/"><u>Windows and Linux: How WSL Changes the Game?</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>