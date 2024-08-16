---
title: Quick Fixes for Non-Terminable Tasks on Windows PCs
date: 2024-08-15T16:16:21.383Z
updated: 2024-08-16T16:16:21.383Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quick Fixes for Non-Terminable Tasks on Windows PCs
excerpt: This Article Describes Quick Fixes for Non-Terminable Tasks on Windows PCs
keywords: Terminate Task Quickly,Windows Task Halt,Fix Unfinished Task,Stop Non-Ending Process,End Non-Terminating Apps,PC Task Remediation,Completing Stalled Windows Tasks
thumbnail: https://thmb.techidaily.com/c3d35b16437bab1ad5b7b686beca2df570e5510e7d66b97529a73f9cf277751a.jpg
---

## Quick Fixes for Non-Terminable Tasks on Windows PCs

 Task Manager is a handy system utility for terminating unwanted apps and processes on Windows. Although it usually works as expected, there are times when Task Manager malfunctions and displays the "unable to terminate process" error on Windows.

 If you’re unable to terminate apps or processes due to this error, here are some ways you can either fix the error message or bypass it using a different method outside of Windows' Task Manager.

## 1\. Use the Alt + F4 Keyboard Shortcut

 At times, temporary glitches with an app or program can trigger the “unable to terminate process” error on Windows. If it’s nothing major, you should be able to close the unresponsive program with the**Alt + F4** keyboard shortcut. Switch to the app or program you want to close and press**Alt + F4** together on your keyboard to close it.

 Check out[how to force close a program without the Task Manager](https://www.makeuseof.com/tag/how-to-kill-unresponsive-programs-without-the-task-manager/) for more ways to close an app without using this tool.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
## 2\. Open Task Manager as an Administrator

 Not running Task Manager as an administrator could prevent you from terminating certain system processes. If that’s the case, use the following steps to open Task Manager with elevated rights and then try to terminate the process again.

1. Click the magnifying icon on the taskbar to open the search menu.
2. Type**Task Manager** in the box and select**Run as administrator** .
3. When the[User Account Control (UAC)](https://www.makeuseof.com/tag/user-account-control-windows-10/) prompt appears, select**Yes** to continue.
4. Right-click on the process you want to terminate and select**End task** from the context menu.  
![Close Process Using Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/close-process-using-task-manager.jpg)
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->
## 3\. Use the Taskkill Command to Terminate the Process

 Using the Task Manager isn’t the only way to terminate processes on Windows. If you’re comfortable using Command Prompt, you can run the "taskkill" command to easily stop an unwanted process on Windows.

 In order to terminate a process with the taskkill command, you’ll need to know the exact name of the process. To find out, switch to the**Details** tab in the Task Manager window and locate the process you want to kill. Note down its name from the first column.

![Details Tab in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/details-tab-in-task-manager.jpg)

 Once you have the name of the process, use the following steps to terminate it.

1. Press**Win + S** to open the search menu.
2. Type**Command Prompt** in the box and select**Run as administrator** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Type the following command and press**Enter** to terminate the process. Make sure you replace**ProcessName** in the following command with the actual name of the process noted earlier.  
`taskkill /IM "ProcessName" /T /F`  
![Terminate Process With Taskkill Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/terminate-process-with-taskkill-command.jpg)

 Once you run the above command, you should see a confirmation message indicating that the process was terminated successfully.

## 4\. Terminate the Process With WMIC

 WMIC (or Windows Management Instrumentation Command-line) is another powerful tool for terminating processes on Windows. Again, you'll need to know the exact name of the process you want to kill. Once you have that, use the following steps to terminate the process with WMIC.

1. Use any of your preferred methods to[open Command Prompt with administrative privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
2. Paste the following command in the console, replace**ProcessName** with the actual name of the process you want to terminate, and press**Enter** .  
`wmic process where name='processname.exe' delete`  
![Terminate Process With WMIC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/terminate-process-with-wmic.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Use a Task Manager Alternative

 Finally, if none of the solutions help with the "unable to terminate process" error, you can consider using a[Task Manager alternative on Windows](https://www.makeuseof.com/tag/5-powerful-alternatives-windows-task-manager/) . If you're looking for something with more power, Process Explorer is a solid choice.

1. [Download Process Explorer](https://learn.microsoft.com/en-us/sysinternals/downloads/process-explorer) on your computer.
2. Double-click the**procexp64.exe** to open Process Explorer.
3. Locate the process you want to terminate. Right-click on it and select**Kill Process** from the resulting menu.  
![Kill Process Using Process Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/kill-process-using-process-explorer.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
## Your Tasks, Terminated Successfully

 By applying the fixes in the article, you should be able to fix the “unable to terminate process” error on Windows. However, be cautious when terminating processes via Task Manager, as some may cause your system to freeze or crash if terminated.


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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-unlocking-the-secrets-to-perfect-zoom-recordings/"><u>[New] 2024 Approved  Unlocking the Secrets to Perfect Zoom Recordings</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-in-2024-how-to-make-time-lapse-videos-with-gopro-studio/"><u>[New] In 2024, How to Make Time Lapse Videos With GoPro Studio</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-prowess-in-phrasing-best-tags-for-gamer-videos/"><u>[New] Prowess in Phrasing  Best Tags for Gamer Videos</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-instagram-excellence-optimizing-post-reach/"><u>[Updated] In 2024, Instagram Excellence  Optimizing Post Reach</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-navigating-current-and-future-of-drone-use/"><u>[Updated] Navigating Current and Future of Drone Use</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-slapstick-to-subtlety-a-guide-to-crafting-memes-online/"><u>2024 Approved  Slapstick to Subtlety  A Guide to Crafting Memes Online</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-locked-for-security-reasons-on-apple-iphone-8-plus-find-the-best-solution-here-by-drfone-ios/"><u>Apple ID Locked for Security Reasons On Apple iPhone 8 Plus? Find the Best Solution Here</u></a></li>
<li><a href="https://windows11.techidaily.com/beyond-boundaries-3-tools-that-elevate-pc-audio-above-100/"><u>Beyond Boundaries: 3 Tools That Elevate PC Audio Above 100%%</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-text-entry-learning-from-typingaid/"><u>Boost Text Entry: Learning From TypingAid</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/capturing-life-in-motion-a-comprehensive-review-of-camplus-cubeplus-for-2024/"><u>Capturing Life in Motion  A Comprehensive Review of Cam+ Cube+ for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-duo-app-configurations-to-resolve-errors/"><u>Correcting Duo App Configurations to Resolve Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/detailed-exploration-retrieving-the-true-nature-of-device-ids-in-windows/"><u>Detailed Exploration: Retrieving the True Nature of Device IDs in Windows</u></a></li>
<li><a href="https://article-helps.techidaily.com/digital-content-showdown-audios-answer-to-visual-media-in-2024/"><u>Digital Content Showdown  Audio's Answer to Visual Media, In 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/digital-dot-delights-top-8-desktop-note-alternatives/"><u>Digital Dot Delights: Top 8 Desktop Note Alternatives</u></a></li>
<li><a href="https://fox-http.techidaily.com/elevate-expression-with-audio-in-statuses/"><u>Elevate Expression with Audio in Statuses</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-yuzu-emulation-speed-in-windows/"><u>Elevating Yuzu Emulation Speed in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-windows-1011-unsigned-update-errors/"><u>Eliminating Windows 10/11 'Unsigned' Update Errors</u></a></li>
<li><a href="https://driver-install.techidaily.com/essential-asus-bt400-download-for-modern-pcs/"><u>Essential ASUS BT400 Download for Modern PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-steps-for-muting-windows-11-tabs/"><u>Essential Steps for Muting Windows 11 Tabs</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tuning-windows-filename-metadata/"><u>Fine-Tuning Windows Filename Metadata</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-cant-detect-camera-error-on-windows-11-pc/"><u>Fixing Can't Detect Camera Error on Windows 11 PC</u></a></li>
<li><a href="https://android-frp.techidaily.com/frp-hijacker-by-hagard-download-and-bypass-your-samsung-galaxy-f54-5g-frp-locks-by-drfone-android/"><u>FRP Hijacker by Hagard Download and Bypass your Samsung Galaxy F54 5G FRP Locks</u></a></li>
<li><a href="https://windows11.techidaily.com/get-a-free-glimpse-into-the-realm-of-ocm-football/"><u>Get a FREE Glimpse Into the Realm of OCM Football</u></a></li>
<li><a href="https://windows11.techidaily.com/getting-acquainted-with-the-windows-odbc-system/"><u>Getting Acquainted with the Windows ODBC System</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-14-pro-to-other-iphone-11-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone 14 Pro to other iPhone 11 devices? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/insightful-tips-for-timely-ping-execution-on-windows-pcs/"><u>Insightful Tips for Timely Ping Execution on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/leap-into-connectivity-unlocking-windows-remote-desktop/"><u>Leap Into Connectivity: Unlocking Windows Remote Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/master-your-computers-potential-a-wintoy-guidebook/"><u>Master Your Computer's Potential: A Wintoy Guidebook</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-and-protect-enabling-powershell-script-policy/"><u>Optimize & Protect: Enabling PowerShell Script Policy</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-workflow-key-windows-programs-for-taskmasters/"><u>Optimizing Workflow: Key Windows Programs for Taskmasters</u></a></li>
<li><a href="https://windows11.techidaily.com/resolve-compromised-windows-defender-in-windows-11/"><u>Resolve Compromised Windows Defender in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-microsoft-store-programs-on-windows-1011-systems/"><u>Restoring Microsoft Store Programs on Windows 10/11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-using-wireless-and-cable-in-harmony-on-windows/"><u>The Ultimate Guide: Using Wireless and Cable in Harmony on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-undetectable-file-hiding-technique-on-windows-systems/"><u>The Undetectable File Hiding Technique on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/transforming-text-to-art-obsidian-canvas-techniques/"><u>Transforming Text to Art: Obsidian Canvas Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-chkdsk-vs-scan-disk-dissecting-windows-tools/"><u>Understanding Chkdsk Vs. Scan Disk: Dissecting Windows Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-11-and-galaxy-ties-with-samsung-dex/"><u>Unveiling Windows 11 & Galaxy Ties with Samsung DeX</u></a></li>
<li><a href="https://windows11.techidaily.com/visual-notetaking-revolution-unlocking-with-obsidian-canvas/"><u>Visual Notetaking Revolution: Unlocking with Obsidian Canvas</u></a></li>
</ul></div>
