---
title: "Mastering System Debugging: Locating & Resolving Error Codes via Windows Command Prompt"
date: 2024-08-27T16:06:36.736Z
updated: 2024-08-28T16:06:36.736Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering System Debugging: Locating & Resolving Error Codes via Windows Command Prompt"
excerpt: "This Article Describes Mastering System Debugging: Locating & Resolving Error Codes via Windows Command Prompt"
keywords: Debugging Skills,Error Code Findings,Resolving Software Issues,Command Prompt Tips,System Diagnostics,Debugging Techniques,Windows Troubleshooting
thumbnail: https://thmb.techidaily.com/52f669a15e335bb29d06275250544e9470586ee079bd1c12147b53606781363c.jpg
---

## Mastering System Debugging: Locating & Resolving Error Codes via Windows Command Prompt

 Encountering random errors and crashes while using the operating system without an explanation can be frustrating. It also makes it harder to find the appropriate solutions, because you have no clue what caused the problem in the first place.

 In this guide, we will show you how you can use the Command Prompt utility to identify potential culprits behind annoying Windows errors. We will also discuss how you fix the issue using CMD as well.

## How to Diagnose Windows Errors in the Command Prompt

 To solve a problem in Windows, such as an update error or a Blue Screen of Death, it's important to identify the potential causes of the issue. Windows comes with several utilities that can help you with this, one of which is Command Prompt.

 Below, we have discussed different ways of using Command Prompt to look up Windows error codes.

### 1\. Use the NET HELPMSG Command

 The NET HELPMSG command helps convert error codes into strings, which you can use to find relevant solutions for the problem. However, this command can only help you with system error codes, which are specific numerical values. This means you cannot use it for BSOD errors like the INACCESSIBLE\_BOOT\_DEVICE error.

Moreover, the numerical value of the error code must also be precise.

Here is how you can use this command:

1. Press the**Win + R** keys together to open a Run dialog.
2. Type "cmd" in Run and press the**Ctrl + Shift + Enter** keys together to open Command Prompt with administrative privileges.
3. Click**Yes** in the User Account Control prompt.
4. Once you are inside the Command Prompt window, type the command mentioned below and hit**Enter** to execute it. Replace <error code> with the numerical value of the code.  
`NET HELPMSG <error code>`
5. For instance, if the error code you want lookup is 8242, your command will be:  
`NET HELPMSG 8242​​​`  
![Execute the net helpmsg command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/net-helpmsg-error.jpg)

 Once you have the details on the error code, you can either look for solutions online or jump to the solutions listed later in this guide.

### 2\. Use the CertUtil Command

 Another easy way to look up error descriptions using the Command Prompt is by using the CertUtil command. This command is typically used for managing certificates and certificate services, but can also be a helpful tool in finding short explanations for the error codes.

Here is how you can use it:

1. Open Command Prompt using the steps we have described above.
2. In the Command Prompt window, execute the command below. Replace <error code> with the error code you are encountering:  
`CertUtil /error <error code>`
3. So for instance, if you are encountering the update error 0x80070002, your command will be:  
`CertUtil /error 0x80070002​​​​`  
![Execute the entered command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/certutil-command.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698827&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3REpage-newmainscreenshot.png" border="0">DEX 3 RE is Easy-To-Use DJ Mixing Software for MAC and Windows Designed for Today's Versatile DJ. 

 Mix from your own library of music, iTunes or use the Pulselocker subsciprtion service for in-app access to over 44 million songs. Use with over 85 supported DJ controllers or mix with a keyboard and mouse.  

 DEX 3 RE is everything you need without the clutter - the perfect 2-deck mixing software solution for mobile DJs or hard-core hobbiests.  
 PCDJ DEX 3 RE (DJ Software for Win & MAC - Product Activation For 3 Machines)</a>
<!-- affiliate ads end -->
 You should now be presented with a description of the error message. You can use this detail to identify the culprit and eliminate it.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 3\. Access the Event Viewer

 When you encounter an error on Windows, a log file for the error is created in the Event Viewer. This log file contains the details of the event, including the time and date it occurred, the error code associated with it, and the source of the event.

 You can[access the Event Viewer using the Command Prompt](https://www.makeuseof.com/windows-open-event-viewer/) to identify the culprit behind the error, and then proceed with the relevant solutions to fix the problem.

## How to Resolve the Problem Using the Command Prompt

 Once you have identified the problem, you can use the Command Prompt utility to fix it as well. Windows comes with a set of troubleshooting utilities that can you can run via this command-line interface to resolve system issues once and for all.

 Here are some common ways you can use the Command Prompt to diagnose and resolve various issues with your Windows operating system.

<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. Fix Any Corruption Errors

 There are a number of problems that may result from corruption errors and bugs within the operating system, such as frequent crashes and freezes, boot problems, data loss, and slow performance.

 The easiest way to fix such issues is by[running the built-in SFC and DISM tools](https://www.makeuseof.com/windows-built-in-repair-tools/) via Command Prompt.

![Run SFC and DISM scans](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/scannow-restorehealth-cmd-1.jpg)

 SFC or the System File Checker works by scanning the protected system files to check their integrity. It will compare the files to a stable version stored in the Windows component store or the installation media. If a problem with the file is identified, the utility will automatically replace the file with its healthier counterpart and generate a report based on it.

 DISM, on the other hand, can be used to repair a wide range of issues, including system files, problematic drivers, and a corrupt Windows image. It is considered to be more advanced and powerful than SFC.

 Once you have completed an SFC scan, you can check the log file for more detailed information as well. Simply execute this command:

`findstr /c:"[SR]" %windir%\logs\cbs\cbs.log >"%userprofile%\Desktop\sfcdetails.txt`

 Doing so will create a log file named sfcdetails.txt on your desktop, listing all the issues found during the scan.

### 2\. Uninstall Windows Updates

 There are times when an update you install on the system turns out to be buggy or corrupt, leading to different issues within the system.

 Since Windows provides you with the option to uninstall updates, you can use Command Prompt to achieve this.

 Simply open Command Prompt as an administrator and execute the command listed below to view a list of installed updates:

`wmic qfe list brief /format:table`

 To uninstall one, execute the following command. Replace <HotFixID> with the ID number of the update that you want to uninstall.

`wusa /uninstall /kb:<HotFixID>`

![Uninstall the update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-update-cmd.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
<!-- affiliate ads end -->
### 3\. Fix Boot Issues

 If you are having trouble booting into Windows, or the boot time is just painfully slow, the issue is likely to be related to the boot sector or boot configuration data (BCD).

You can use the bootrec command to repair these via Command Prompt.

Here is how you can do that:

1. [Boot into WinRE](https://www.makeuseof.com/ways-to-boot-into-the-windows-recovery-environment/) and head over to Repair your computer.
2. Navigate to**Troubleshoot** \>**Advanced options** .  
![WinRE-Advanced-Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/winre-advanced-options.jpg)
3. Choose**Command Prompt** from the list of options available.
4. Once you are in the Command Prompt window, execute the following commands:  
`bootrec /fixmbr bootrec /fixboot bootrec /rebuildbcd`
5. If you are prompted with Add installation to boot list?, type Y and hit Enter.
6. Once all the commands are executed, you can exit Command Prompt by typing exit and hitting Enter.
7. Restart your computer, and you should be able to boot into Windows successfully!

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
## The Command Prompt to the Rescue

 Having knowledge of certain Windows tools can come in handy when dealing with various computer-related issues. One such utility that can help you find solutions is Command Prompt and knowing how to use it can save you both time and frustration.

 We highly recommend backing up your essential data before making any changes to your operating system, just to be safe. With a little patience and some troubleshooting skills, you can get rid of annoying Windows errors for good.


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
<li><a href="https://fox-links.techidaily.com/new-a-fresh-take-on-samsungs-ultrablade-k850-review-for-2024/"><u>[New] A Fresh Take on Samsung’s UltraBlade K850 Review for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-how-to-check-what-youve-liked-on-facebook-lately/"><u>[New] In 2024, How To Check What You've Liked on Facebook Lately</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-smile-spawning-creativity-in-adobe-meme-making/"><u>[New] Smile Spawning  Creativity in Adobe Meme-Making</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-unleash-your-social-media-potential-with-insta-post-magic-for-2024/"><u>[New] Unleash Your Social Media Potential with Insta Post Magic for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-effortless-screen-capture-in-dota-2-matches/"><u>[Updated] In 2024, Effortless Screen Capture in Dota 2 Matches</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-network-access-error-for-google-chrome-in-windows-settings/"><u>Fix Network Access Error for Google Chrome in Windows Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-non-scrolling-issue-unlock-cells-in-excel-windows/"><u>Fix Non-Scrolling Issue: Unlock Cells in Excel (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-failed-steam-remote-links-on-pc/"><u>Fixing Failed Steam Remote Links on PC</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-do-honor-x50i-screen-sharing-drfone-by-drfone-android/"><u>How To Do Honor X50i Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-from-motorola-moto-g24-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock from Motorola Moto G24 Phones with/without a PC</u></a></li>
<li><a href="https://windows11.techidaily.com/installing-apk-files-made-convenient-win-11s-guide-to-easy-setups/"><u>Installing APK Files Made Convenient: Win 11'S Guide to Easy Setups</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-cortana-integration-vivetool-writings/"><u>Mastering Cortana Integration: ViveTool' Writings</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-windows-11-taskbar-functionality/"><u>Maximizing Windows 11 Taskbar Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/mitigating-windows-update-problem-code-0x8024800c/"><u>Mitigating Windows Update Problem: Code 0X8024800C</u></a></li>
<li><a href="https://windows11.techidaily.com/open-locked-windows-shared-files-now/"><u>Open Locked Windows Shared Files Now</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-inaccessible-erase-functionality-in-windows-11/"><u>Overcoming Inaccessible Erase Functionality in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-operational-obligations-avoiding-sudden-freezes-on-your-pc/"><u>Overcoming Operational Obligations: Avoiding Sudden Freezes on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/perfect-visuals-your-guide-to-leveraging-background-blur-on-windows-11-photos-app/"><u>Perfect Visuals: Your Guide to Leveraging Background Blur on Windows 11 Photos App</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-access-to-system-status-and-update-information-via-menu-option-in-win11/"><u>Quick Access to System Status & Update Information via Menu Option in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-unconnected-error-with-geforce-experience-on-pc/"><u>Rectifying Unconnected Error with GeForce Experience on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/reimagine-your-workspace-with-direct-desktop-drawings-in-windows-11/"><u>Reimagine Your Workspace with Direct Desktop Drawings in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/safeguard-your-desktops-background-from-changes/"><u>Safeguard Your Desktop's Background From Changes</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-non-responsive-windows-shift/"><u>Solutions for Non-Responsive Windows Shift.</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-solutions-for-overcoming-the-blue-screen-of-death-issue/"><u>Step-by-Step Solutions for Overcoming the 'Blue Screen of Death' Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-handle-and-solve-app-runtime-error-on-pc/"><u>Strategies to Handle and Solve App Runtime Error on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-productivity-mastering-windows-11s-widgets/"><u>Streamline Productivity: Mastering Windows 11'S Widgets</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-file-search-in-windows-moving-away-from-ls/"><u>Streamlining File Search in Windows: Moving Away From LS</u></a></li>
<li><a href="https://windows11.techidaily.com/supercharge-your-workday-mastery-tips-for-multitasking-windows-11/"><u>Supercharge Your Workday: Mastery Tips for Multitasking Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/supercharging-windows-11s-protected-mode-graphics/"><u>Supercharging Windows 11'S Protected Mode Graphics</u></a></li>
<li><a href="https://windows11.techidaily.com/systematic-success-guiding-through-windows-11-renewal/"><u>Systematic Success: Guiding Through Windows 11 Renewal</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-high-cpu-drain-by-tiworkerexe/"><u>Tackling High CPU Drain by TiWorker.exe</u></a></li>
<li><a href="https://hardware-help.techidaily.com/toms-tech-hub-expert-insights-on-hardware-solutions/"><u>Tom's Tech Hub: Expert Insights on Hardware Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-error-0x80072efd-on-windows-devices/"><u>Troubleshooting Error 0X80072EFD on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-steam-ui-dll-failure-on-windows/"><u>Troubleshooting Steam UI DLL Failure on Windows</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/ultimate-raspberry-pi-400-evaluation-unboxing-the-all-in-one-desktop-companion/"><u>Ultimate Raspberry Pi 400 Evaluation: Unboxing the All-in-One Desktop Companion</u></a></li>
<li><a href="https://windows11.techidaily.com/unite-cloud-storage-onedrive-meets-microsoft-live-id/"><u>Unite Cloud Storage: OneDrive Meets Microsoft Live ID</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-creativity-through-windows-photos-app-deletion/"><u>Unleashing Creativity Through Window's Photos App Deletion</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-your-print-potential-strategies-to-fix-slide-show-problems-on-windows/"><u>Unlocking Your Print Potential: Strategies to Fix Slide Show Problems on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unshackle-administrative-access-on-pcs/"><u>Unshackle Administrative Access on PCs</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-camtasia-tutorial-change-video-speed-and-pitch-for-2024/"><u>Updated Camtasia Tutorial Change Video Speed and Pitch for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-unveiling-the-triple-widget-configuration-steps/"><u>Windows 11: Unveiling the Triple Widget Configuration Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-arp-cache-explained-clears-and-management/"><u>Windows ARP Cache Explained: Clears & Management</u></a></li>
</ul></div>