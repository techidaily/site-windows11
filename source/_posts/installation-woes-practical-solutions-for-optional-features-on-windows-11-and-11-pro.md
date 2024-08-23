---
title: "Installation Woes: Practical Solutions for Optional Features on Windows 11 & 11 Pro"
date: 2024-08-22T21:44:07.859Z
updated: 2024-08-23T21:44:07.859Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Installation Woes: Practical Solutions for Optional Features on Windows 11 & 11 Pro"
excerpt: "This Article Describes Installation Woes: Practical Solutions for Optional Features on Windows 11 & 11 Pro"
keywords: Win11 Install Troubleshooting,ProGadget Optimization Tips,Unlock Windows 11 Features,Easy Optional Upgrade Paths,Bypassing Pro Plugin Issues,Enhance Win11 OS Performance,Simplified Software Integration
thumbnail: https://thmb.techidaily.com/731e7d95cb104fd0f2b4a441263b2d39fb916acbe1dcf99883081e6f54b5961f.jpg
---

## Installation Woes: Practical Solutions for Optional Features on Windows 11 & 11 Pro

 Optional features are those that you can add to get more functionality or support for certain file formats. For example, you can install different font packs or old Windows utilities like Paint and WordPad.

 If you're having trouble installing optional features, you're not alone. Sometimes optional features may fail to install due to corrupt system files, an outdated Windows version, or incorrect configuration settings.

 Fortunately, there are several ways to fix this problem and get the optional features running again. So, how can you fix the optional features not installing issue?

## 1\. Use the DISM Tool

 One of the first things you can try is using the Deployment Image Servicing and Management (DISM) tool. This tool is part of Windows, and you can use it to fix corrupt system files, including ones that could be causing problems when installing optional features.

To use the DISM tool, follow these steps:

1. Press**Win + Q** to bring up the Windows search dialogue box.
2. Type**cmd** and click**Run as administrator** to open the Command Prompt.
3. Type**dism /online /cleanup-image /restorehealth** and press**Enter** .  
![DISM Windows Utility Overview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/dism-windows-utility.jpg)

 This will start the DISM tool and begin scanning your system for any corrupt or missing files. If it finds any issues with your computer, it will automatically repair them.

 Once the process is complete, you can restart your computer and try installing the optional feature again. If DISM does not work or throws an error code, make sure to go through the[DISM not working fixes](https://www.makeuseof.com/windows-11-dism-error-2-fix/) .

## 2\. Run the System File Checker or SFC Utility

 Another tool you can use to fix issues with optional feature installation is the System File Checker (SFC) utility.

 SFC is a command-line utility on Windows, which means you can use it from the Command Prompt itself. It is a useful tool for troubleshooting and repairing problems with the system files on your computer, similar to the DISM tool.

To check your system using SFC, follow these steps:

1. Open the Command Prompt with administrative rights using any of the[ways to open CMD as an admin on Windows](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
2. Type**sfc /scannow** and press**Enter** .  
![SFC Utility In Windows Overview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-utility-in-windows.jpg)
3. Once SFC scans for errors, make sure to restart your computer.

Want to know the best part?

 The best part is that the System File Checker not only helps you fix the optional features problem but also any other Windows issues. In fact, it's one of the best[ways to repair corrupted Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) .

## 3\. Reset the Windows Update Components

 Windows Update Components include all the services, tasks, and programs that work together to make sure your Windows system is up-to-date and secure.

 Resetting the Windows Update components might help solve the issue with optional feature installation. Here's how you can reset the Windows Update components easily:

1. Open the Command Prompt utility as an administrator.
2. Type the following commands one after the other, pressing**Enter** after each one:

`net stop wuauserv  
net stop cryptSvc  
net stop bits  
net stop msiserver  
ren C:\Windows\SoftwareDistribution SoftwareDistribution.old  
ren C:\Windows\System32\catroot2 catroot2.old  
net start wuauserv  
net start cryptSvc  
net start bits  
net start msiserver`

 This command will stop the Windows Update services, rename the**SoftwareDistribution** and**catroot2** folders, and then restart the services. This can help reset the update process and fix any issues that might be causing problems with optional feature installation.

![Update Components Reset In CMD Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/update-components-reset-in-cmd.jpg)

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
 While the commands may look intimidating, you don't need to worry, as all the commands mentioned above will not cause any harm to your system.​​​​

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->
## 4\. Run the Windows Update Troubleshooter

 If the Command Prompt method did not work for you, you can use the Windows Update Troubleshooter to reset update components. This tool can help identify and fix problems with the update process, including issues that might be preventing optional features from installing.

Follow these steps to run the update troubleshooter on Windows:

1. Press**Win + I** to launch the Settings app.
2. Scroll down and click**Troubleshoot > Other troubleshooters.**  
![Troubleshooter Settings In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/troubleshooter-settings-in-windows.jpg)
3. Click**Run** next to**Windows Update** to run the troubleshooter.  
![Other Troubleshooters In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/other-troubleshooters-in-windows.jpg)
4. Follow the prompts to complete the troubleshooting process.
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
<!-- affiliate ads end -->

 If you're using Windows 10, the Windows Update Troubleshooter is in**Settings > Update & Security >** **Troubleshoot > Windows Update** .

 The troubleshooter will begin scanning your system for any issues with the update process and will offer suggestions for how to fix them. So, you just need to follow the prompts, and then try[installing the optional features](https://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) again.

<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
## 5\. Update Windows to the Latest Version

 If the issue with optional feature installation is related to outdated system files, you may be able to fix it by updating Windows to the latest version.

 Updating Windows can help ensure that you have the latest security patches, bug fixes, and system files, which can help resolve any issues you may be experiencing.

Here's how you can update Windows to the latest version:

1. Press**Win + I** to open the Settings app.
2. Click on**Windows** **Update > Check for updates** on Windows 11\. For Windows 10, click on **Update & Security > Windows Update > Check for Updates** .  
![Windows Update In Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-update-in-windows-11.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-platform-ui-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
 That's it. Now, you can install any update that is available for your computer.

 By default, Windows automatically downloads and installs updates, but you can also check for updates manually by following the steps above.

## 6\. Restart the Windows Module Installer Service

 The Windows Module Installer service allows you to install, change, and remove Windows features and optional components. If it is not working properly, it can make it difficult to install optional features.

 Follow the below-given steps to restart the Windows Module Installer service:

1. Open Windows search and type**services** .
2. Select the best match to open the**Services** app.
3. Scroll down and find the**Windows Module Installer** service.
4. Right-click on the service and select**Restart** .  
![Windows Modules Installer Service In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-modules-installer-service.jpg)

 When you reset the module installer service, Windows tries to stop it and then start it again, which can help reset the installation process of optional features and fix any issues that might be causing problems.

 Once the service restarts, try installing the optional feature again, and it should work now.

## 7\. Restore Windows Features Using PowerShell

 If all the above methods fail to work, restoring Windows features is your last resort. So, if you are unable to use or install an optional Windows feature, you might be able to fix the problem by using PowerShell to restore a particular feature.

 Here are the steps for restoring Windows features using the PowerShell:

1. Press**Win + X** to open the Power User menu.
2. Click on**Windows PowerShell (Admin)** or**Terminal (Admin)** .
3. Type the following command and press**Enter** :  
Get-WindowsOptionalFeature -Online  
![Get Optional Feature Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/get-optional-feature-command.jpg)  
 This command will show you the**FeatureName** and**State** of every optional Windows feature that you can use. Make sure to copy the "**FeatureName** " of the feature that you want to enable on Windows.
4. To turn on a certain feature, use the following command and replace "**FEATURENAME** " with the feature's name that you copied earlier:  
Enable-WindowsOptionalFeature -Online -FeatureName FEATURENAME  
![Enable Optional Feature Command In PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/optional-feature-in-powershell.jpg)
5. Restart your computer for the changes to take effect.

 This will add the feature back to your system and should make it available for you to enable or disable in the features window.

 This method only allows you to restore a specific feature and, not all the features at once. So, you need to copy and paste the same command and edit the**FEATURENAME** every time.

 If these steps don't fix the problem, you may need to ask Microsoft or a technical support professional for more help.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
## Get Back the Windows Optional Features

 Hopefully, the issue with optional features not installing on your system should be fixed now. In any case, it is important to keep your system up-to-date and to follow best practices for maintaining your computer properly to help prevent issues like this from occurring.


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
<li><a href="https://video-screen-grab.techidaily.com/new-dominance-digest-the-ultimate-battle-royale-list/"><u>[New] Dominance Digest  The Ultimate Battle Royale List</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-peak-level-illustration-tweaks/"><u>[New] Peak Level Illustration Tweaks</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-unparalleled-asmr-channel-selection/"><u>[New] Unparalleled ASMR Channel Selection</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-best-12-screensavers-with-no-time-caps/"><u>[Updated] Best 12 Screensavers with No Time Caps</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-aesthetic-all-stars-popular-instagram-filters/"><u>[Updated] In 2024, Aesthetic All-Stars  Popular Instagram Filters</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-lullaby-vids-a-critical-look-at-bedtime-narrative-videos/"><u>[Updated] Lullaby Vids  A Critical Look at Bedtime Narrative Videos</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-pro-video-enhancements-grasping-green-screen-artistry-through-4-youtube-demos/"><u>[Updated] Pro Video Enhancements  Grasping Green Screen Artistry Through 4 YouTube Demos</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-capture-engaging-shots-using-strategic-leading-lines-iphone/"><u>2024 Approved  Capture Engaging Shots Using Strategic Leading Lines (iPhone)</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-premier-guide-to-filmed-action-preservation/"><u>2024 Approved  Premier Guide to Filmed Action Preservation</u></a></li>
<li><a href="https://windows11.techidaily.com/3-ways-to-find-a-group-policy-on-windows/"><u>3 Ways to Find a Group Policy on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/4-ways-to-find-a-programs-install-location-on-windows/"><u>4 Ways to Find a Program's Install Location on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-windows-media-player-in-a-swift-manner/"><u>Activating Windows Media Player in a Swift Manner</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-obs-record-failure-a-comprehensive-guide-for-windows-users/"><u>Addressing OBS Record Failure: A Comprehensive Guide for Windows Users</u></a></li>
<li><a href="https://fox-direct.techidaily.com/beginners-aerial-adventure-top-10-best-kids-drones-for-2024/"><u>Beginner's Aerial Adventure  Top 10 Best Kids' Drones for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/beijings-ice-arena-olympic-moments-2022-for-2024/"><u>Beijing's Ice Arena  Olympic Moments, 2022 for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/bypassed-direct3d-delays-unleash-full-gpu-capabilities-now/"><u>Bypassed Direct3D Delays - Unleash Full GPU Capabilities Now</u></a></li>
<li><a href="https://extra-tips.techidaily.com/capturing-awe-the-power-of-creative-distortion-in-photoshop-for-2024/"><u>Capturing Awe  The Power of Creative Distortion in Photoshop for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/checking-for-safe-network-connections-on-windows/"><u>Checking for Safe Network Connections on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-zip-files-seamless-compressed-archives-on-windows-pcs/"><u>Conquer ZIP Files: Seamless Compressed Archives on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-impact-of-copilot-key-on-your-windows-11-pc-performance/"><u>Deciphering the Impact of Copilot Key on Your Windows 11 PC Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-accidental-windows-11-search-menu-trigger/"><u>Disabling Accidental Windows 11 Search Menu Trigger</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-spotting-hdd-vs-ssd-in-windows-operations/"><u>Essential Guide: Spotting HDD vs SSD in Windows Operations</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-knowledge-about-winservicesexe/"><u>Essential Knowledge About WinServices.exe</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-techniques-for-initiatingexit-focus-in-the-windows-terminal/"><u>Essential Techniques for Initiating/Exit Focus in the Windows Terminal</u></a></li>
<li><a href="https://windows11.techidaily.com/faster-apps-better-internet-fixes-for-windows-devices/"><u>Faster Apps, Better Internet: Fixes for Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-incorrect-parameters-leading-to-loadlibrary-failure/"><u>Fixing Incorrect Parameters Leading to LoadLibrary Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-unreachable-status-for-malwarebytes-services-in-win11/"><u>How to Fix Unreachable Status for Malwarebytes' Services in Win11</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-4-most-known-ways-to-find-someone-on-tinder-for-asus-rog-phone-8-by-name-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Most-Known Ways to Find Someone on Tinder For Asus ROG Phone 8 by Name | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-4-ways-to-unlock-apple-iphone-12-pro-max-to-use-usb-accessories-without-passcode-by-drfone-ios/"><u>In 2024, 4 Ways to Unlock Apple iPhone 12 Pro Max to Use USB Accessories Without Passcode</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-gps-joystick-to-fake-gps-location-on-honor-70-lite-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Complete Tutorial to Use GPS Joystick to Fake GPS Location On Honor 70 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-ispoofer-is-not-working-on-apple-iphone-8-plus-fixed-drfone-by-drfone-virtual-ios/"><u>In 2024, iSpoofer is not working On Apple iPhone 8 Plus? Fixed | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-running-handbrake-on-widows/"><u>Mastering the Art of Running HandBrake on Widows</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-the-missing-file-preview-glitch-in-outlook-360/"><u>Mending the Missing File Preview Glitch in Outlook 360</u></a></li>
<li><a href="https://sound-issues.techidaily.com/modern-warfare-voice-communication-issues-solved/"><u>Modern Warfare Voice Communication Issues - Solved!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-shared-device-conflicts-in-win11/"><u>Navigating Shared Device Conflicts in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-windows-ram-usage-for-device-connectivity-services/"><u>Optimizing Windows RAM Usage for Device Connectivity Services</u></a></li>
<li><a href="https://windows11.techidaily.com/outperforming-understanding-why-pcs-triumph-over-macs-9/"><u>Outperforming: Understanding Why PCs Triumph over Macs (#9)</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-ccleaner-issues-in-windows-11/"><u>Overcoming CCleaner Issues in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-most-frequent-blue-screen-hurdles/"><u>Overcoming the Most Frequent Blue Screen Hurdles</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/perfect-your-instagram-video-upload/"><u>Perfect Your Instagram Video Upload</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-non-empty-directory-alert-error-code-0x80070091-in-windows-11/"><u>Preventing Non-Empty Directory Alert (Error Code: 0X80070091) in Windows 11</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/securely-transferring-camera-photos-to-snapchat-correctly/"><u>Securely Transferring Camera Photos to Snapchat Correctly</u></a></li>
<li><a href="https://location-social.techidaily.com/simple-and-effective-ways-to-change-your-country-on-youtube-app-of-your-realme-gt-neo-5-se-drfone-by-drfone-virtual-android/"><u>Simple and Effective Ways to Change Your Country on YouTube App Of your Realme GT Neo 5 SE | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-windows-notepad-notebook-errors/"><u>Solutions for Windows Notepad Notebook Errors</u></a></li>
<li><a href="https://data-wizards.techidaily.com/some-files-uncorrected-by-video-software/"><u>Some Files Uncorrected by Video Software.</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-correct-steam-ui-dll-not-loaded-error/"><u>Steps to Correct Steam UI DLL Not Loaded Error</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-overcome-systemsettingsexe-crash-in-win11/"><u>Steps to Overcome SystemSettings.exe Crash in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-rectify-microsoft-store-error-0x80072f30-on-pcs/"><u>Steps to Rectify Microsoft Store Error 0X80072F30 on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-port-reset-failed-issue-in-windows-11/"><u>Tackling 'Port Reset Failed' Issue in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tech-triumph-expert-tips-for-reinitializing-windows-11-apps/"><u>Tech Triumph: Expert Tips for Reinitializing Windows 11 Apps</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/the-pinnacle-selector-your-personal-video-vault-for-2024/"><u>The Pinnacle Selector  Your Personal Video Vault for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-notepad-on-win11-through-ai-wisdom/"><u>Transform Notepad on Win11 Through AI Wisdom</u></a></li>
<li><a href="https://windows11.techidaily.com/tricks-for-easily-opening-and-modifying-faxes-on-windows-11/"><u>Tricks for Easily Opening and Modifying Faxes on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-errors-when-opening-sound-devices-on-audacity/"><u>Troubleshooting Errors When Opening Sound Devices on Audacity</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/universal-strategy-to-preserve-your-favorite-youtube-broadcasts-on-all-devices-for-2024/"><u>Universal Strategy to Preserve Your Favorite YouTube Broadcasts on All Devices for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-evolution-a-portable-offline-approach/"><u>Windows Evolution: A Portable Offline Approach</u></a></li>
</ul></div>
