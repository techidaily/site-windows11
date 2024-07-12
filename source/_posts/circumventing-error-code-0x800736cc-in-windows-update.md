---
title: Circumventing Error Code 0X800736CC in Windows Update
date: 2024-07-11T22:14:33.221Z
updated: 2024-07-12T22:14:33.221Z
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

## 2\. Run the Windows Update Troubleshooter

 If restarting the PC doesn't work, you can use the Windows Update Troubleshooter. This built-in utility solves minor problems that prevent Windows from updating correctly.

 To run the Windows Update Troubleshooter, follow these steps:

1. Press **Win + S** to open the Windows Search bar.
2. Type in **Troubleshoot** and select **Troubleshoot Settings** from the results list.
3. On the right sidebar, click **Other troubleshooters**.  
![Other troubleshooters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/other-troubleshooters.jpg)
4. Under **Most frequent**, locate **Windows Update** and click **Run**.  
![Run Windows Update Troubleshooter-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/run-windows-update-troubleshooter-1.jpg)

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

## 4\. Disable your Antivirus Temporarily

 Security software interferes with Windows Update and causes errors. To avoid this issue, [temporarily disable your security program](http://www.makeuseof.com/how-to-turn-off-windows-defender/) before running updates. Once you have disabled it, restart the computer and install the update again. If it works, it was your security software that caused the issue.

 Remember that disabling security software leaves your computer vulnerable to malware attacks, so enable it immediately.

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
8. Now, you have the batch script on your desktop. Right-click on it and select **Run as administrator**.
9. When the UAC pops up, click **Yes** to grant elevated privileges.

 The script will take a few minutes to run. When it's finished, close the Command Prompt window and restart your computer. Once your computer restarts, check if the 0x800736cc error is resolved.

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
<li><a href="https://some-skills.techidaily.com/updated-unleash-creativity-discovering-the-most-acclaimed-photo-swap-apps/"><u>[Updated] Unleash Creativity  Discovering the Most Acclaimed Photo Swap Apps</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-harmonize-length-and-engagement-in-podcasting/"><u>[New] Harmonize Length & Engagement in Podcasting</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensive-guide-to-using-w11s-auto-hdr/"><u>A Comprehensive Guide to Using W11's Auto HDR</u></a></li>
<li><a href="https://windows11.techidaily.com/unnoticeable-disk-usage-for-ws1110-users/"><u>Unnoticeable Disk Usage for WS11/10 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/1719268966849-windows-users-save-your-keys-from-failure/"><u>Windows Users: Save Your Keys From Failure!</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-i-transferred-messages-from-vivo-y100t-to-iphone-12xs-max-in-seconds-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How I Transferred Messages from Vivo Y100t to iPhone 12/XS (Max) in Seconds | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-streamlining-the-acquisition-of-background-visual-content/"><u>2024 Approved  Streamlining the Acquisition of Background Visual Content</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-streamline-skype-calls-with-effective-recording-techniques/"><u>2024 Approved  Streamline Skype Calls with Effective Recording Techniques</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-motorola-moto-g04-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some Pro Tips for Pokemon Go PvP Battles On Motorola Moto G04 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/the-top-8-tips-for-a-smooth-windows-11-transition/"><u>The Top 8 Tips for a Smooth Windows 11 Transition</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-your-windows-11-reboot-cycle/"><u>Streamlining Your Windows 11 Reboot Cycle</u></a></li>
<li><a href="https://windows11.techidaily.com/biometric-betrayal-how-secure-is-your-windows-hello-lock/"><u>Biometric Betrayal: How Secure Is Your Windows Hello Lock?</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-point-guide-to-achievement-enhancement-in-vintage-titles-via-retroarch/"><u>Step-By Point Guide to Achievement Enhancement in Vintage Titles via Retroarch</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/2024-approved-rtmp-streaming-on-instagram-a-comprehensive-tutorial/"><u>2024 Approved RTMP Streaming on Instagram A Comprehensive Tutorial</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-unlock-the-lock-screen-on-my-itel-s23plus-by-drfone-android-unlock-android-unlock/"><u>How to Unlock the Lock Screen on my Itel S23+</u></a></li>
<li><a href="https://windows11.techidaily.com/zero-tolerance-to-error-e84-steam-fix-guide/"><u>Zero Tolerance to Error E84: Steam Fix Guide</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-mastering-the-art-of-quick-pacing-in-tiktok/"><u>[New] Mastering the Art of Quick Pacing in TikTok</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-smooth-sailing-in-transforming-ppt-slides-into-videos/"><u>[New] 2024 Approved  Smooth Sailing in Transforming PPT Slides Into Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/winservicesexe-what-it-is-and-fixing-errors/"><u>Winservices.exe: What It Is and Fixing Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/brighten-up-a-step-by-step-guide-to-an-eye-catching-cursor/"><u>Brighten Up: A Step-by-Step Guide to an Eye-Catching Cursor</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-the-artisans-guide-to-zen-like-zoom-backgrounds/"><u>[Updated] In 2024, The Artisan's Guide to Zen-Like Zoom Backgrounds</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-ultimate-collection-of-elite-cost-free-vfx-and-editing-websites/"><u>[New] The Ultimate Collection of Elite, Cost-Free VFX & Editing Websites</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-clinical-manifestations-of-fetal-alcohol-syndrome/"><u>[Updated] In 2024, Clinical Manifestations of Fetal Alcohol Syndrome</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/uninterrupted-adventures-top-10-best-offline-ios-titles-for-2024/"><u>Uninterrupted Adventures  Top 10 Best Offline iOS Titles for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-transform-your-twitter-usage-best-unfollower-tools-reviewed/"><u>2024 Approved  Transform Your Twitter Usage  Best Unfollower Tools Reviewed</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/tech-savvy-tips-for-recording-quality-movies-on-any-device-for-2024/"><u>Tech-Savvy Tips for Recording Quality Movies on Any Device for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-turning-onoff-windows-10s-smartscreen/"><u>Tips for Turning On/Off Windows 10'S SmartScreen</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-pen-pad-issues-on-windows-os/"><u>Troubleshooting: Pen Pad Issues on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-rectify-unresponsive-windows-key/"><u>Techniques to Rectify Unresponsive Windows Key</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-the-wild-waters-of-xbox-errors-in-win11/"><u>Taming the Wild Waters of Xbox Errors in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-system-updates-for-compatibility-with-intel-graphics/"><u>Streamlining System Updates for Compatibility with Intel Graphics</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-starting-up-mspaint-windows-11-edition/"><u>Step-by-Step Guide: Starting up MSPaint, Windows 11 Edition</u></a></li>
<li><a href="https://network-issues.techidaily.com/guiding-through-windows-7-screenshake-solutions/"><u>Guiding Through Windows 7 Screenshake Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-unexpected-wins-system-messages/"><u>Tackling Unexpected WINS System Messages</u></a></li>
<li><a href="https://windows11.techidaily.com/backtracking-your-pc-with-ease-using-system-restore/"><u>Backtracking Your PC with Ease Using System Restore</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-memory-management-understanding-and-flushing-cache/"><u>Windows Memory Management: Understanding and Flushing Cache</u></a></li>
<li><a href="https://windows11.techidaily.com/choosing-wisely-windows-terminal-as-your-primary-cli/"><u>Choosing Wisely: Windows Terminal as Your Primary CLI</u></a></li>
<li><a href="https://windows11.techidaily.com/1719327094876-top-4-solutions-for-troubleshooting-full-screen-capture-issues-in-windows-snipping-tool/"><u>Top 4 Solutions for Troubleshooting Full-Screen Capture Issues in Windows Snipping Tool.</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-grow-your-computers-storage-for-free/"><u>The Ultimate Guide to Grow Your Computer's Storage, For Free</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-guide-unique-monitors-wallpapers-tips/"><u>Windows 11 Guide: Unique Monitors Wallpapers Tips</u></a></li>
<li><a href="https://video-capture.techidaily.com/detailed-ice-cream-snapshot-analysis-report-for-2024/"><u>Detailed Ice Cream Snapshot Analysis Report for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-decoding-youtubes-operations-following-uploads/"><u>[New] 2024 Approved  Decoding YouTube’s Operations Following Uploads</u></a></li>
<li><a href="https://windows11.techidaily.com/winstorage-revival-guide-with-altwindirstat-insights/"><u>WinStorage Revival Guide with AltWinDirStat Insights</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-decrease-high-cpu-usage-from-dropbox-on-windows-pcs/"><u>Strategies to Decrease High CPU Usage From Dropbox on Windows PCs</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-videos-and-music-files-from-iphone-6-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Recover Deleted Photos, Videos & Music Files from iPhone 6 | Stellar</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-savoring-secrets-tiktok-food-trends-you-cant-miss/"><u>2024 Approved  Savoring Secrets  #Tiktok Food Trends You Can't Miss</u></a></li>
</ul></div>
