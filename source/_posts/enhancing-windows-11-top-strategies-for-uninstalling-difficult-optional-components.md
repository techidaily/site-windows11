---
title: "Enhancing Windows 11: Top Strategies for Uninstalling Difficult Optional Components"
date: 2024-07-29T04:23:43.265Z
updated: 2024-07-30T04:23:43.265Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Enhancing Windows 11: Top Strategies for Uninstalling Difficult Optional Components"
excerpt: "This Article Describes Enhancing Windows 11: Top Strategies for Uninstalling Difficult Optional Components"
keywords: Win11 Component Removal,OptiUninstall Tips,Remove Windows Extras,Easy Win11 Cleanup,Optional Components Uninstall,Difficult Win11 Updates,Strategy for Win11 Clean
thumbnail: https://thmb.techidaily.com/b4646e6c7dd57e63be8305e5fc613622e6d7e19134ef2ba8ba5fe989f296bf0b.png
---

## Enhancing Windows 11: Top Strategies for Uninstalling Difficult Optional Components

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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
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

 While the commands may look intimidating, you don't need to worry, as all the commands mentioned above will not cause any harm to your system.​​​​

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## 4\. Run the Windows Update Troubleshooter

 If the Command Prompt method did not work for you, you can use the Windows Update Troubleshooter to reset update components. This tool can help identify and fix problems with the update process, including issues that might be preventing optional features from installing.

Follow these steps to run the update troubleshooter on Windows:

1. Press**Win + I** to launch the Settings app.
2. Scroll down and click**Troubleshoot > Other troubleshooters.**  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Troubleshooter Settings In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/troubleshooter-settings-in-windows.jpg)
3. Click**Run** next to**Windows Update** to run the troubleshooter.  
![Other Troubleshooters In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/other-troubleshooters-in-windows.jpg)
4. Follow the prompts to complete the troubleshooting process.

 If you're using Windows 10, the Windows Update Troubleshooter is in**Settings > Update & Security >** **Troubleshoot > Windows Update** .

 The troubleshooter will begin scanning your system for any issues with the update process and will offer suggestions for how to fix them. So, you just need to follow the prompts, and then try[installing the optional features](https://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) again.

## 5\. Update Windows to the Latest Version

 If the issue with optional feature installation is related to outdated system files, you may be able to fix it by updating Windows to the latest version.

 Updating Windows can help ensure that you have the latest security patches, bug fixes, and system files, which can help resolve any issues you may be experiencing.

Here's how you can update Windows to the latest version:

1. Press**Win + I** to open the Settings app.
2. Click on**Windows** **Update > Check for updates** on Windows 11\. For Windows 10, click on **Update & Security > Windows Update > Check for Updates** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->
![Windows Update In Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-update-in-windows-11.jpg)

 That's it. Now, you can install any update that is available for your computer.

 By default, Windows automatically downloads and installs updates, but you can also check for updates manually by following the steps above.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
<!-- affiliate ads end -->
## 6\. Restart the Windows Module Installer Service

 The Windows Module Installer service allows you to install, change, and remove Windows features and optional components. If it is not working properly, it can make it difficult to install optional features.

 Follow the below-given steps to restart the Windows Module Installer service:

1. Open Windows search and type**services** .
2. Select the best match to open the**Services** app.
3. Scroll down and find the**Windows Module Installer** service.
4. Right-click on the service and select**Restart** .  
<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Windows Modules Installer Service In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-modules-installer-service.jpg)

 When you reset the module installer service, Windows tries to stop it and then start it again, which can help reset the installation process of optional features and fix any issues that might be causing problems.

 Once the service restarts, try installing the optional feature again, and it should work now.

<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Enable Optional Feature Command In PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/optional-feature-in-powershell.jpg)
5. Restart your computer for the changes to take effect.

 This will add the feature back to your system and should make it available for you to enable or disable in the features window.

 This method only allows you to restore a specific feature and, not all the features at once. So, you need to copy and paste the same command and edit the**FEATURENAME** every time.

 If these steps don't fix the problem, you may need to ask Microsoft or a technical support professional for more help.

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
<li><a href="https://youtube-sure.techidaily.com/024-approved-digital-dynamics-mastering-youtube-video-distribution-on-facebook/"><u>[New] 2024 Approved  Digital Dynamics  Mastering YouTube Video Distribution on Facebook</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-best-9-free-youtube-logo-makers-for-2024/"><u>[New] Best 9 Free YouTube Logo Makers for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-xchange-your-thoughts-on-better-alternatives/"><u>[New] In 2024, XChange Your Thoughts on Better Alternatives</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-unlocking-potential-metaverse-marketing-secrets/"><u>[New] Unlocking Potential  Metaverse Marketing Secrets</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-access-exclusive-stock-images-through-vital-4-youtube-sources/"><u>[Updated] 2024 Approved  Access Exclusive Stock Images Through Vital 4 YouTube Sources</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-a-comprehensive-guide-to-facebooks-full-screen-feature-for-2024/"><u>[Updated] A Comprehensive Guide to Facebook's Full Screen Feature for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-az-record-pro-detailed-app-analyses-and-backup-choices/"><u>[Updated] In 2024, AZ Record Pro  Detailed App Analyses & Backup Choices</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-direct-download-of-youtube-videos/"><u>[Updated] In 2024, Direct Download of YouTube Videos</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-enhancing-immersion-prepping-for-oculus/"><u>2024 Approved  Enhancing Immersion  Prepping for Oculus</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-final-cut-pros-top-10-vfx-power-players/"><u>2024 Approved  Final Cut Pro’s Top 10 VFX Power Players</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-next-level-screenrecord-a-critical-evaluation/"><u>2024 Approved  Next-Level ScreenRecord  A Critical Evaluation</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-camera-app-malfunction-in-windows-11/"><u>Addressing Camera App Malfunction in Windows 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/best-movie-scripts-so-far/"><u>Best Movie Scripts so Far</u></a></li>
<li><a href="https://windows11.techidaily.com/blueprints-to-build-secure-window-for-hardware-unhook/"><u>Blueprints to Build Secure Window for Hardware Unhook</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-chromes-erroneous-virus-warning-on-pc/"><u>Clearing Chrome's Erroneous Virus Warning on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/direct-path-to-spooler-restart/"><u>Direct Path to Spooler Restart</u></a></li>
<li><a href="https://windows11.techidaily.com/distinguishing-between-hdd-and-ssd-drives-on-pc/"><u>Distinguishing Between HDD & SSD Drives on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-elevated-privileges-for-power-users-a-guide/"><u>Enabling Elevated Privileges for Power Users: A Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-your-window-experience-mastering-the-start-menu/"><u>Enhance Your Window Experience: Mastering the Start Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-xbox-game-pass-0x800700e9-error-in-windows-11-and-11/"><u>How to Fix the Xbox Game Pass 0X800700e9 Error in Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-halt-microsoft-edge-icons-regularity/"><u>How to Halt Microsoft Edge Icons' Regularity</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-t-mobile-iphone-se-online-without-sim-card-by-drfone-ios/"><u>In 2024, How to Unlock T-Mobile iPhone SE online without SIM Card?</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-optimizing-video-quality-youtube-to-mpeg-conversion-strategies/"><u>In 2024, Optimizing Video Quality  YouTube to MPEG Conversion Strategies</u></a></li>
<li><a href="https://fake-location.techidaily.com/is-pgsharp-legal-when-you-are-playing-pokemon-on-samsung-galaxy-s21-fe-5g-2023-drfone-by-drfone-virtual-android/"><u>Is pgsharp legal when you are playing pokemon On Samsung Galaxy S21 FE 5G (2023)? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/make-file-management-simple-using-windows-autodelete-feature/"><u>Make File Management Simple: Using Windows' Autodelete Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/newbies-in-the-windows-world-steer-clear-of-these-top-8-faux-pas/"><u>Newbies in the Windows World: Steer Clear of These Top 8 Faux Pas</u></a></li>
<li><a href="https://windows11.techidaily.com/playnite-extension-virtual-games-collection/"><u>Playnite Extension: Virtual Games Collection</u></a></li>
<li><a href="https://windows11.techidaily.com/rapid-and-secure-firmware-update-guide-for-surface-systems/"><u>Rapid & Secure Firmware Update Guide for Surface Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/re-establishing-printer-linkage-in-windows-11-setup/"><u>Re-Establishing Printer Linkage in Windows 11 Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/reestablish-wi-fi-masterful-solutions-for-windows-usb-adapters/"><u>Reestablish Wi-Fi: Masterful Solutions for Windows USB Adapters</u></a></li>
<li><a href="https://windows11.techidaily.com/reversal-of-extra-privileges-win11-standardization-tutorial/"><u>Reversal of Extra Privileges: Win11 Standardization Tutorial</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-addressing-undetectable-disks/"><u>Strategies for Addressing Undetectable Disks</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-reducing-browsing-impact-on-system-performance/"><u>Tips for Reducing Browsing Impact on System Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/uniting-gmail-and-outlook-windows-setup-walkthrough/"><u>Uniting Gmail and Outlook: Windows Setup Walkthrough</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11-secrets-with-devhome-insights/"><u>Unlocking Windows 11 Secrets with DevHome Insights</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-desktop-from-chaotic-to-customized-in-minutes/"><u>Win11 Desktop: From Chaotic to Customized, in Minutes</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-update-halted-quick-solutions-for-a-perfect-installation/"><u>Windows Update Halted: Quick Solutions for a Perfect Installation</u></a></li>
</ul></div>
