---
title: "Back to Basics: Windows 11 Access Re-Establishment Guide"
date: 2024-08-15T15:12:48.767Z
updated: 2024-08-16T15:12:48.767Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Back to Basics: Windows 11 Access Re-Establishment Guide"
excerpt: "This Article Describes Back to Basics: Windows 11 Access Re-Establishment Guide"
keywords: Win11 Basics Guide,Windows Access Setup,Win11 Reboot Instructions,Windows 11 Login Restore,Basic Win11 Use Tips,Re-Establish Win11 Access,Win11 Reset Guide
thumbnail: https://thmb.techidaily.com/76bc2de184e61e693dbac8bc5f62288cf6610a7d170abd91534f7a21873e1f18.png
---

## Back to Basics: Windows 11 Access Re-Establishment Guide

 Having issues with apps or programs not running properly on your Windows computer? Resetting Windows Update permissions could be the solution you need. Similarly, if you're troubleshooting user profile problems, you can restore user permissions.

 This article covers three different methods to reset all user permissions – using the Icacls command, the Secedit command, and the Subinacl tool.

Let's now explore them in detail.

## 1\. Run the Icacls Command

 The Icacls command allows you to view, modify, and reset file system permissions on files and folders. To reset Windows Update permissions using this command, you will first have to [take ownership of the folders on Windows](https://www.makeuseof.com/windows-10-11-own-folder/) . Then [open an elevated Command Prompt on Windows](https://www.makeuseof.com/windows-run-command-prompt-admin/) and type in the following command:

`icacls * /t /q /c /reset`

 Now press Enter on your keyboard to execute the command. This will reset all user permissions to default for every folder, subfolder, and file within the current working directory.

In the above command, here are the parameters explained:

* \* – This is a wildcard character that includes all folders within the current directory.
* /t – It targets all the subfolders and files within the current folder.
* /q – Run command without displaying success messages.
* /c – Continues the operation even if errors occur.
* /reset – This parameter resets the permission options to their default values.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Run the Secedit command

 Windows provides the Secedit command to configure and analyze system security. To reset all user permissions using this command, run the command prompt with admin access, then type in the following command:

![Run the Secedit command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-the-secedit-command.jpg)
<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->

`secedit /configure /cfg %windir%\inf\defltbase.inf /db defltbase.sdb /verbose`

 Now press Enter to execute the command. Wait for the process to finish and restart your computer. This will reset the user permissions to the default system settings.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
## 3\. Run the Subinacl Tool

 If you're not comfortable using the command prompt, you may use the Subinacl tool. This is a command-line utility from Microsoft that can be used to reset user permissions. Here's how to do it:

1. [Download the Subinacl tool from Microsoft's webpage](https://web.archive.org/web/20190830103837/http://www.microsoft.com/en-us/download/confirmation.aspx?id=23510) . When you open the page, the download starts automatically. If not, wait 30 seconds and click the link.
2. Once downloaded, double-click on the installer package. This will open the installation wizard.  
![Open the installation wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/open-the-installation-wizard.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
3. Click on**Next** and then accept the license agreement terms.  
![Install the Subinacl tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-the-subinacl-tool.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
4. Next, copy and paste the following path into the Destination folder:  
`C:\Windows\System32`  
 Note: If you have installed Windows on a different drive, use that path instead.
5. Now click on**Install now** and wait for the Subinacl tool to be installed. This may take several minutes, so be patient.

1. When the installation is complete,[open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) and type in the following commands:  
`subinacl /subkeyreg HKEY_LOCAL_MACHINE /grant=administrators=f  
subinacl /subkeyreg HKEY_CURRENT_USER /grant=administrators=f  
subinacl /subkeyreg HKEY_CLASSES_ROOT /grant=administrators=f  
subinacl /subdirectories %SystemDrive% /grant=administrators=f  
subinacl /subkeyreg HKEY_LOCAL_MACHINE /grant=system=f  
subinacl /subkeyreg HKEY_CURRENT_USER /grant=system=f  
subinacl /subkeyreg HKEY_CLASSES_ROOT /grant=system=f  
subinacl /subdirectories %SystemDrive% /grant=system=f`
2. On the Save As window, set the File name to**Reset.cmd** and then select**All Files** from the drop-down menu next to it.  
![Reset Windows Update permissions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-update-permissions.jpg)
3. Next, select**Desktop** from the left pane and click on**Save** .
4. Now double-click on it to reset the user permissions to default.
5. This may take a while to complete the procedure, so wait for it to finish.

 Once done, close any running program, and then restart your computer. Your Windows Update permissions will be reset to their default settings. These are three different methods you can use to reset the user permission settings on Windows.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
## Restore User Permissions to Default on Windows

 User permissions play a crucial role in computer security. If you're experiencing user permission issues, you must reset them to their default settings. This guide helps you reset all user permissions on Windows using three different methods. You can use the ICACLS command, Secedit command, or Subinacl tool, depending on your preference.


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
<li><a href="https://facebook-video-files.techidaily.com/updated-in-2024-facebook-media-extractor-music-mode/"><u>[Updated] In 2024, Facebook Media Extractor – Music Mode</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-navigating-the-zoom-interface-like-a-pro-in-win11/"><u>[Updated] Navigating the Zoom Interface Like a Pro in Win11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-adding-visuals-on-instagram-quickly/"><u>2024 Approved  Adding Visuals on Instagram Quickly</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-step-by-step-guide-to-pc-based-live-broadcasts-on-tiktok/"><u>2024 Approved  Step-by-Step Guide to PC-Based Live Broadcasts on TikTok</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/all-about-factory-reset-what-is-it-and-what-it-does-to-your-oneplus-12r-drfone-by-drfone-reset-android-reset-android/"><u>All About Factory Reset, What Is It and What It Does to Your OnePlus 12R? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-non-terminatable-processes-on-windows-systems/"><u>Fixing Non-Terminatable Processes on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-more-value-black-friday-offers-at-612-win10/"><u>Get More Value: Black Friday Offers at $6.12 Win10</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-stop-hyper-v-service-in-windows-11/"><u>Guide: Stop Hyper-V Service in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-for-rectifying-error-code-0x8007045d-on-windows-11/"><u>Guidelines for Rectifying Error Code 0X8007045d on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-a-move-and-copy-to-folder-context-menu-options-in-windows-10-and-11/"><u>How to Add a Move and Copy to Folder Context Menu Options in Windows 10 & 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-after-switching-from-infinix-note-30-pro-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data After Switching From Infinix Note 30 Pro to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-nokia-130-music-frp-in-3-different-ways-by-drfone-android/"><u>In 2024, How To Bypass Nokia 130 Music FRP In 3 Different Ways</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-a-lost-oppo-reno-11-pro-5g-for-free-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track a Lost Oppo Reno 11 Pro 5G for Free? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-tutorial-to-change-samsung-galaxy-s23-tactical-edition-imei-without-root-a-comprehensive-guide-by-drfone-android/"><u>In 2024, Tutorial to Change Samsung Galaxy S23 Tactical Edition IMEI without Root A Comprehensive Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/inside-out-mastering-windows-error-resolution-version-22h2/"><u>Inside Out: Mastering Windows Error Resolution, Version 22H2</u></a></li>
<li><a href="https://windows11.techidaily.com/interactive-guide-to-utilizing-windows-component-services/"><u>Interactive Guide to Utilizing Windows Component Services</u></a></li>
<li><a href="https://windows11.techidaily.com/linking-win-pink-keys-with-ms-account/"><u>Linking WIN PINK KEYS with MS ACCOUNT</u></a></li>
<li><a href="https://windows11.techidaily.com/photoshop-quick-keys-a-windows-guide/"><u>Photoshop Quick Keys: A Windows Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-pasting-made-easy-personalized-shortcuts-in-the-latest-windows-version/"><u>Quick-Pasting Made Easy: Personalized Shortcuts in the Latest Windows Version</u></a></li>
<li><a href="https://windows11.techidaily.com/revealing-a-hidden-shortcoming-an-insightful-review-of-samsung-galaxy-tab-a-2020/"><u>Revealing a Hidden Shortcoming: An Insightful Review of Samsung Galaxy Tab A (2020)</u></a></li>
<li><a href="https://windows11.techidaily.com/solve-mystery-of-disappearing-hardware-in-winos/"><u>Solve Mystery of Disappearing Hardware in WinOS</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-windows-camera-app-0xa00f429f-glitches/"><u>Solving Windows' Camera App 0xA00F429F Glitches</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-rectify-failed-utorrent-installations-in-windows/"><u>Strategies to Rectify Failed uTorrent Installations in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-your-files-overcoming-common-onedrive-glitches-in-windows-11/"><u>Streamlining Your Files: Overcoming Common OneDrive Glitches in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/successful-steps-to-fix-silent-audio-in-obs-w11-system/"><u>Successful Steps to Fix Silent Audio in OBS, W11 System</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-and-tricks-to-effectively-use-the-windows-key/"><u>Tips & Tricks to Effectively Use the Windows Key</u></a></li>
<li><a href="https://howto.techidaily.com/top-4-android-system-repair-software-for-itel-p55plus-bricked-devices-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 4 Android System Repair Software for Itel P55+ Bricked Devices | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/top-5-samsung-galaxy-a05s-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 Samsung Galaxy A05s Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://windows11.techidaily.com/total-extraction-guide-how-to-remove-wsl-on-windows-11/"><u>Total Extraction Guide: How to Remove WSL on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-your-workspace-sketches-for-win-1011-users/"><u>Transform Your Workspace: Sketches for Win 10/11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/tutorial-enabling-the-revamped-toolset-for-selecting-widgets/"><u>Tutorial: Enabling the Revamped Toolset for Selecting Widgets</u></a></li>
<li><a href="https://windows11.techidaily.com/unrelated-processes-under-microsoft-edge-in-tasks/"><u>Unrelated Processes Under Microsoft Edge in Tasks</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-screen-reset-3-straightforward-solutions/"><u>Win11 Screen Reset: 3 Straightforward Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-whimsy-fixing-fuchsia-and-fern-like-colors-on-your-screen/"><u>Windows Whimsy? Fixing Fuchsia & Fern-Like Colors on Your Screen</u></a></li>
</ul></div>
