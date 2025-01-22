---
title: "Back to Basics: Windows 11 Access Re-Establishment Guide"
date: 2025-01-19T16:44:18.079Z
updated: 2025-01-22T19:59:41.982Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eu4vwlZcMvM?si=4vEczfVU4BUUFP-t" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

## 2\. Run the Secedit command

 Windows provides the Secedit command to configure and analyze system security. To reset all user permissions using this command, run the command prompt with admin access, then type in the following command:

![Run the Secedit command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-the-secedit-command.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2Iv3DjT2Fyw?si=pR_z8ZDDVGF2MvKJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`secedit /configure /cfg %windir%\inf\defltbase.inf /db defltbase.sdb /verbose`

 Now press Enter to execute the command. Wait for the process to finish and restart your computer. This will reset the user permissions to the default system settings.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Run the Subinacl Tool

 If you're not comfortable using the command prompt, you may use the Subinacl tool. This is a command-line utility from Microsoft that can be used to reset user permissions. Here's how to do it:

1. [Download the Subinacl tool from Microsoft's webpage](https://web.archive.org/web/20190830103837/http://www.microsoft.com/en-us/download/confirmation.aspx?id=23510) . When you open the page, the download starts automatically. If not, wait 30 seconds and click the link.
2. Once downloaded, double-click on the installer package. This will open the installation wizard.  
![Open the installation wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/open-the-installation-wizard.jpg)
3. Click on**Next** and then accept the license agreement terms.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaGNHfAT92w?si=bvHo1iYK2JBIPtRo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Install the Subinacl tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-the-subinacl-tool.jpg)
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/hHPljBHrvkA?si=HwdfDM9rlbABSIrx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://article-tips.techidaily.com/new-elevate-meeting-aesthetics-how-to-add-filters-on-zoom/"><u>[New] Elevate Meeting Aesthetics How to Add Filters on Zoom</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-ultimate-screen-capture-guide-tunefab-pro/"><u>[New] In 2024, Ultimate Screen Capture Guide - Tunefab Pro</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-in-2024-writing-that-grabs-and-grips-podcast-description-tactics/"><u>[Updated] In 2024, Writing That Grabs and Grips Podcast Description Tactics</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-prime-10-image-repositories-without-costs-for-2024/"><u>[Updated] Prime 10 Image Repositories Without Costs for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/changing-home-screen-settings-without-start-menu/"><u>Changing Home Screen Settings Without Start Menu</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/comprehensive-guide-to-the-dependable-kensun-portable-tire-inflator-travel-companion/"><u>Comprehensive Guide to the Dependable Kensun Portable Tire Inflator - Travel Companion</u></a></li>
<li><a href="https://windows11.techidaily.com/dive-into-the-depth-of-windows-pre-boots/"><u>Dive Into the Depth of Windows Pre-Boots</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-move-contacts-from-xiaomi-redmi-note-12-proplus-5g-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Move Contacts From Xiaomi Redmi Note 12 Pro+ 5G to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-compose-your-story-best-mobile-annotation-tools/"><u>In 2024, Compose Your Story Best Mobile Annotation Tools</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/mastering-home-surveillance-a-step-by-step-review-of-the-blink-outdoor-4-wi-fi-lighted-security-camera/"><u>Mastering Home Surveillance: A Step-by-Step Review of the Blink Outdoor 4 Wi-Fi Lighted Security Camera</u></a></li>
<li><a href="https://windows11.techidaily.com/redefining-user-experience-the-changing-landsinas-of-w10-and-w11/"><u>Redefining User Experience: The Changing Landsinas of W10 & W11</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-guide-repairing-the-failed-connected-usb-hardware-in-windows/"><u>Step-by-Step Guide: Repairing the Failed Connected USB Hardware in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-overcome-windows-memory-errors/"><u>Steps to Overcome Windows Memory Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-eliminate-windows-unknown-value-warning/"><u>Strategies to Eliminate Windows Unknown Value Warning</u></a></li>
<li><a href="https://windows11.techidaily.com/swiftly-solve-drop-problems-in-win11/"><u>Swiftly Solve Drop Problems in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-unreachable-error-with-spotify-in-windows-1011/"><u>Tackling the Unreachable Error with Spotify in Windows 10/11</u></a></li>
</ul></div>

