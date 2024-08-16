---
title: Circumventing Error Code 0X800736CC in Windows Update
date: 2024-08-15T15:18:28.271Z
updated: 2024-08-16T15:18:28.271Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Circumventing Error Code 0X800736CC in Windows Update
excerpt: This Article Describes Circumventing Error Code 0X800736CC in Windows Update
keywords: Fix Windows Update Failure (Error 0X800736CC),Resolve Update Error X736CC,Overcome Windows Error Code 0X800736CC,Windows Update 0X800736CC Fix Guide,Stop Error X736CC in Updates,Correcting Windows Update Failure (Error 0X87),Eliminate Error Code 0X800736CC WU
thumbnail: https://thmb.techidaily.com/90c2e01727fc918de7950373ab7790d2b6bd79b92f560dcc1472e9356e8fe972.png
---

## Circumventing Error Code 0X800736CC in Windows Update

 Windows Update keeps your computer safe and secure with the latest security patches. However, you might encounter errors while installing these updates, like 0x800736cc. This error code stops you from deploying critical security updates, leaving your computer vulnerable. In this guide, we’ll show you some troubleshooting steps to fix this error.

## 1\. Restart Your PC

 The first thing you need to do is [restart your computer](https://www.makeuseof.com/windows-restart-methods/). Although it may seem too simplistic, you'd be surprised how often this resolves various issues. When your computer reboots, it clears temporary files and processes that could cause problems. This includes incomplete Windows updates that failed to install or encountered installation errors.

 A quick reboot can bypass the error and complete the update, so it should be your primary course of action before delving into more intricate troubleshooting methods.

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->
## 2\. Run the Windows Update Troubleshooter

 If restarting the PC doesn't work, you can use the Windows Update Troubleshooter. This built-in utility solves minor problems that prevent Windows from updating correctly.

 To run the Windows Update Troubleshooter, follow these steps:

1. Press **Win + S** to open the Windows Search bar.
2. Type in **Troubleshoot** and select **Troubleshoot Settings** from the results list.
3. On the right sidebar, click **Other troubleshooters**.  
![Other troubleshooters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/other-troubleshooters.jpg)
4. Under **Most frequent**, locate **Windows Update** and click **Run**.  
![Run Windows Update Troubleshooter-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/run-windows-update-troubleshooter-1.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
<!-- affiliate ads end -->

 Follow the on-screen instructions to complete the troubleshooting process. It may take a few minutes for the tool to finish its job.

## 3\. Clear the Windows Update Cache

 Windows Update Cache stores temporary files and processes related to updates. If these files become corrupted, they can interfere with the update process and cause errors like 0x800736cc. In this case, clearing the cache can fix the problem.

 To clear the Windows Update Cache, do the following:

1. Open the Start menu.
2. Type **services.msc** in the search box and hit Enter. The Services window will open.
3. Scroll down and locate the **Windows Update** service. Then, right-click on it and select **Stop**. Doing so temporarily stops Windows Update.
4. Now, [open File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and navigate to this location:  
`C:\Windows\SoftwareDistribution`
5. In the SoftwareDistribution folder, delete all files and folders. This is just temporary data, so removing it won't affect your computer.  
![Clear SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/clear-softwaredistribution-folder.jpg)
6. After deleting the files, head back to the Services window, right-click on the **Windows Update** service, and select **Start**. This step restarts the Windows Update service.

 Now restart your computer. It will allow Windows Update to recreate cache files from scratch.

<!-- affiliate ads begin -->
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Disable your Antivirus Temporarily

 Security software interferes with Windows Update and causes errors. To avoid this issue, [temporarily disable your security program](http://www.makeuseof.com/how-to-turn-off-windows-defender/) before running updates. Once you have disabled it, restart the computer and install the update again. If it works, it was your security software that caused the issue.

 Remember that disabling security software leaves your computer vulnerable to malware attacks, so enable it immediately.

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Reset Windows Update Components

 Windows Update components include files and processes crucial to the update process. If these components become corrupted or damaged, Windows Update cannot run correctly. In this case, you must reset the components to their original state.

 Fortunately, there’s an easy way to do this. Microsoft provides a batch script called Reset Windows Update Tool that resets various Windows Update components with just a few clicks.

 To reset Windows Update components, follow these steps:

1. Click on Start and type **Notepad** in the search bar.
2. Right-click on Notepad and select **Run as administrator**.
3. If the User Account Control window pops up, click **Yes** to continue.
4. In the Notepad window, copy and paste the following code:  
`<code>net stop bits  
net stop wuauserv  
net stop appidsvc  
net stop cryptsvc  
Del "%ALLUSERSPROFILE%\Application Data\Microsoft\Network\Downloader\*.*"  
rmdir %systemroot%\SoftwareDistribution /S /Q  
rmdir %systemroot%  
system32\catroot2 /S /Q  
sc.exe sdset bits D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
sc.exe sdset wuauserv D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
cd /d %windir%  
system32  
regsvr32.exe /s atl.dll  
regsvr32.exe /s urlmon.dll  
regsvr32.exe /s mshtml.dll  
regsvr32.exe /s shdocvw.dll  
regsvr32.exe /s browseui.dll  
regsvr32.exe /s jscript.dll  
regsvr32.exe /s vbscript.dll  
regsvr32.exe /s scrrun.dll  
regsvr32.exe /s msxml.dll  
regsvr32.exe /s msxml3.dll  
regsvr32.exe /s msxml6.dll  
regsvr32.exe /s actxprxy.dll  
regsvr32.exe /s softpub.dll  
regsvr32.exe /s wintrust.dll  
regsvr32.exe /s dssenh.dll  
regsvr32.exe /s rsaenh.dll  
regsvr32.exe /s gpkcsp.dll  
regsvr32.exe /s sccbase.dll  
regsvr32.exe /s slbcsp.dll  
regsvr32.exe /s cryptdlg.dll  
regsvr32.exe /s oleaut32.dll  
regsvr32.exe /s ole32.dll  
regsvr32.exe /s shell32.dll  
regsvr32.exe /s initpki.dll  
regsvr32.exe /s wuapi.dll  
regsvr32.exe /s wuaueng.dll  
regsvr32.exe /s wuaueng1.dll  
regsvr32.exe /s wucltui.dll  
regsvr32.exe /s wups.dll  
regsvr32.exe /s wups2.dll  
regsvr32.exe /s wuweb.dll  
regsvr32.exe /s qmgr.dll  
regsvr32.exe /s qmgrprxy.dll  
regsvr32.exe /s wucltux.dll  
regsvr32.exe /s muweb.dll  
regsvr32.exe /s wuwebv.dll  
netsh winsock reset  
netsh winsock reset proxy  
net start bits  
net start wuauserv  
net start appidsvc  
net start cryptsvc`
5. The above commands form part of a script to reset Windows Update components. After you paste the code into Notepad, click **File** and select **Save as**.
6. In the Save As window, select **All files** from the drop-down menu.
7. Type **ResetWindowsUpdate.bat** as the file name and save it to your desktop.  
![Reset Windows Update Components](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reset-windows-update-components.jpg)
<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. Now, you have the batch script on your desktop. Right-click on it and select **Run as administrator**.
9. When the UAC pops up, click **Yes** to grant elevated privileges.

 The script will take a few minutes to run. When it's finished, close the Command Prompt window and restart your computer. Once your computer restarts, check if the 0x800736cc error is resolved.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->
## 6\. Try Generic Windows Update Fixes

 Besides the methods listed above, you can also try some generic Windows Update fixes. These methods usually work if a temporary issue or corrupted system files cause the error.

 Here are some generic Windows Update fixes you can try:

* [Repair Corrupted System Files](https://www.makeuseof.com/windows-built-in-repair-tools/) \- Run the System File Checker tool to scan and repair corrupted system files. If you need help with this, you can find detailed instructions in our [SFC guide](https://www.makeuseof.com/system-file-checker-sfc-windows/). You can also use the Deployment Image Service and Management (DISM) tool to replace broken files with healthy ones.
* [Perform a Clean Boot](https://www.makeuseof.com/clean-boot-windows-11/) \- Clean Boot can identify software conflicts causing the error. It disables all non-essential services and programs from running in the background. That way, you can isolate the problematic process and resolve the issue.
* [Manually Install the Update](https://www.makeuseof.com/update-windows-manually/) \- If Windows Update fails to install or is stuck, you can download and install it manually

## Fixing Windows Update Error 0x800736cc

 As you can see, multiple ways exist to fix the Windows Update error. We hope one of these methods has solved your problem, and you can now successfully install Windows Update. If nothing else works, you can restore your computer to a previous state or reinstall Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://twitter-clips.techidaily.com/new-in-2024-resolve-twitter-vids-playback-issue/"><u>[New] In 2024, Resolve Twitter Vids Playback Issue</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-screenflow-for-mac-review/"><u>[Updated] In 2024, ScreenFlow for Mac Review</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-maximize-creativity-10-no-cost-tiktok-editors-for-macos-for-2024/"><u>[Updated] Maximize Creativity  10 No-Cost TikTok Editors for MacOS for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-choreographed-insta-videos-with-a-musical-backdrop/"><u>2024 Approved  Choreographed Insta-Videos with a Musical Backdrop</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-moto-z2-play-smartphone-review/"><u>2024 Approved  MOTO Z2 Play Smartphone Review</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-precision-and-performance-top-6-video-edits-on-macos-big-sur/"><u>2024 Approved  Precision and Performance  Top 6 Video Edits on macOS Big Sur</u></a></li>
<li><a href="https://windows11.techidaily.com/6-cutting-edge-windows-programs-for-media-editing/"><u>6 Cutting-Edge Windows Programs for Media Editing</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-a-functional-taskbar-for-windows-11-tablets/"><u>Activating a Functional Taskbar for Windows 11 Tablets</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-task-managers-initial-screen-on-win11/"><u>Customizing Task Manager's Initial Screen on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/decreasing-non-essential-tasks-windows-108/"><u>Decreasing Non-Essential Tasks Windows 10/8</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-your-pcs-potential-with-a-windows-11-in-place-step-by-step-guide/"><u>Elevating Your PC's Potential with a Windows 11, In-Place Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-external-monitors-without-graphics-card/"><u>Enabling External Monitors without Graphics Card</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-preparations-for-revitalizing-your-pc-with-windows/"><u>Essential Preparations for Revitalizing Your PC with Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-chromes-mistaken-malware-detection-errors-in-windows/"><u>Fixing Chrome’s Mistaken Malware Detection Errors in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-rectify-and-resolve-onedrive-errors-in-os/"><u>How to Rectify and Resolve OneDrive Errors in OS</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-turn-off-or-disable-the-microsoft-defender-firewall-in-windows-11/"><u>How to Turn Off or Disable the Microsoft Defender Firewall in Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-move-contacts-from-oppo-reno-9a-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Move Contacts From Oppo Reno 9A to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/in-2024-cross-network-laughter-whos-tops-today/"><u>In 2024, Cross-Network Laughter  Who's Tops Today?</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-full-guide-to-unlock-your-xiaomi-redmi-note-13-pro-5g-by-drfone-android/"><u>In 2024, Full Guide to Unlock Your Xiaomi Redmi Note 13 Pro 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/initiating-printer-commands-via-edge-defender-smartscreen/"><u>Initiating Printer Commands via Edge Defender SmartScreen</u></a></li>
<li><a href="https://windows11.techidaily.com/innovate-w11-notebook-using-ai-guru/"><u>Innovate W11 Notebook Using AI Guru</u></a></li>
<li><a href="https://windows11.techidaily.com/master-technique-for-silencing-firewall-in-win11/"><u>Master Technique for Silencing Firewall in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-desktop-visibility-placing-this-pc-icon-front-and-center/"><u>Maximizing Desktop Visibility: Placing 'This PC' Icon Front and Center</u></a></li>
<li><a href="https://windows11.techidaily.com/missing-dxgidll-in-win11-heres-what-to-do-now/"><u>Missing Dxgi.dll in Win11? Here's What to Do Now</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-directx-12-without-onboard-graphics/"><u>Navigating Through DirectX 12 Without Onboard Graphics</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-invalid-verification-error-by-steams-vac/"><u>Overcoming Invalid Verification Error by Steam's VAC</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-autonomous-scrolling-on-os-windows/"><u>Preventing Autonomous Scrolling on OS Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/prioritize-and-achieve-a-guide-to-top-6-win-11-task-management-tools/"><u>Prioritize & Achieve - A Guide to Top 6 Win 11 Task Management Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/reestablishing-clear-audio-conversations-on-valorant-pc/"><u>Reestablishing Clear Audio Conversations on Valorant PC</u></a></li>
<li><a href="https://windows11.techidaily.com/scrutinizing-underused-windows-features-for-system-checks/"><u>Scrutinizing Underused Windows Features for System Checks</u></a></li>
<li><a href="https://windows11.techidaily.com/silencing-the-audio-stutter-taming-winirq-errors/"><u>Silencing the Audio Stutter: Taming WinIRQ Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/snip-and-sketch-vs-prtsc-the-best-tools-for-windows-users/"><u>Snip & Sketch Vs. PrtSc: The Best Tools for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-steam-service-problems-for-a-smooth-windows-11-experience/"><u>Solving Steam Service Problems for a Smooth Windows 11 Experience</u></a></li>
<li><a href="https://buynow-help.techidaily.com/sony-walkman-nw-a35-review-a-high-quality-buy/"><u>Sony Walkman NW-A35 Review: A High-Quality Buy</u></a></li>
<li><a href="https://windows11.techidaily.com/speedy-task-execution-windows-keyboard-tips-and-tricks/"><u>Speedy Task Execution: Windows Keyboard Tips & Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-to-activate-rgb-settings-in-windows-11/"><u>Step-by-Step to Activate RGB Settings in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-steam-friendship-disconnect-on-pcs/"><u>Steps to Resolve Steam Friendship Disconnect on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-activities-gain-more-in-less-time-with-flow-launcher/"><u>Streamline Activities: Gain More in Less Time With Flow Launcher</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/the-pathway-to-perfection-a-pro-guide-to-instagram-photos/"><u>The Pathway to Perfection  A Pro Guide to Instagram Photos</u></a></li>
<li><a href="https://windows11.techidaily.com/tracing-untapped-functions-within-windows-system-health-tools/"><u>Tracing Untapped Functions Within Windows' System Health Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-absence-of-thumbnail-images-on-windows-11-screens/"><u>Troubleshooting Absence of Thumbnail Images on Windows 11 Screens</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-power-settings-for-cpu-state-insights/"><u>Unlocking Power Settings for CPU State Insights</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-control-for-apps-and-browsers/"><u>Unveiling Windows Control for Apps & Browsers</u></a></li>
<li><a href="https://tech-revival.techidaily.com/utilizing-chatgpt-to-craft-individual-workout-schedules-for-gym-enthusiasts/"><u>Utilizing ChatGPT to Craft Individual Workout Schedules for Gym Enthusiasts</u></a></li>
<li><a href="https://windows11.techidaily.com/why-is-nvidia-control-panel-inaccessible-on-win11/"><u>Why Is Nvidia Control Panel Inaccessible on Win11?</u></a></li>
</ul></div>
