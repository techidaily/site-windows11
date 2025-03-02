---
title: Regaining Normalcy in Windows 11 User Access
date: 2025-02-23T11:51:59.509Z
updated: 2025-03-01T22:14:48.536Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Regaining Normalcy in Windows 11 User Access
excerpt: This Article Describes Regaining Normalcy in Windows 11 User Access
keywords: Windows 11 Update,Access Security,System Normalization,New OS Stability,Windows Regain,Access Control Win11,Norm-Win User Entry
thumbnail: https://thmb.techidaily.com/775033cec734e193d493811f769dcaa65d428fba2286e40a488d59f8b08228ae.png
---

## Regaining Normalcy in Windows 11 User Access

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

## 2\. Run the Secedit command

 Windows provides the Secedit command to configure and analyze system security. To reset all user permissions using this command, run the command prompt with admin access, then type in the following command:

![Run the Secedit command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-the-secedit-command.jpg)

`secedit /configure /cfg %windir%\inf\defltbase.inf /db defltbase.sdb /verbose`

 Now press Enter to execute the command. Wait for the process to finish and restart your computer. This will reset the user permissions to the default system settings.

## 3\. Run the Subinacl Tool

 If you're not comfortable using the command prompt, you may use the Subinacl tool. This is a command-line utility from Microsoft that can be used to reset user permissions. Here's how to do it:

1. [Download the Subinacl tool from Microsoft's webpage](https://web.archive.org/web/20190830103837/http://www.microsoft.com/en-us/download/confirmation.aspx?id=23510) . When you open the page, the download starts automatically. If not, wait 30 seconds and click the link.
2. Once downloaded, double-click on the installer package. This will open the installation wizard.  
![Open the installation wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/open-the-installation-wizard.jpg)
3. Click on**Next** and then accept the license agreement terms.  
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
<li><a href="https://youtube-docs.techidaily.com/n-2024-clip-description-creator/"><u>[New] In 2024, Clip Description Creator</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-precise-voice-adjustments-for-pubg-success/"><u>[New] Precise Voice Adjustments for PUBG Success</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-rotate-for-results-instagram-video-alchemy/"><u>[Updated] 2024 Approved Rotate for Results Instagram Video Alchemy</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-navigating-azure-speech-recognition-efficiently/"><u>[Updated] Navigating Azure Speech Recognition Efficiently</u></a></li>
<li><a href="https://hardware-help.techidaily.com/discover-enhanced-productivity-microsofts-all-new-surface-pro-10-and-laptop-with-cutting-edge-ai-capabilities-insights/"><u>Discover Enhanced Productivity: Microsoft's All-New Surface Pro 10 and Laptop with Cutting-Edge AI Capabilities Insights</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-explorer-exploration-shun-common-pitfalls/"><u>Efficient Explorer Exploration: Shun Common Pitfalls</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-connectivity-expert-instructions-for-dns-configuration/"><u>Elevate Connectivity: Expert Instructions for DNS Configuration</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-language-input-with-customized-keyboard-options-in-win-11/"><u>Elevate Your Language Input with Customized Keyboard Options in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-poorly-performing-ccleaner-in-win11/"><u>Elevating Poorly Performing CCleaner in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/empowering-windows-users-with-access-to-apples-imessage/"><u>Empowering Windows Users with Access to Apple's iMessage</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-creativity-ranking-the-best-drawers-for-win-11/"><u>Enhance Creativity: Ranking the Best Drawers for Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-windows-experience-selecting-top-free-car-upgraders/"><u>Enhance Windows Experience: Selecting Top Free Car Upgraders</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-why-apple-account-disabled-from-your-apple-iphone-13-how-to-fix-by-drfone-ios/"><u>In 2024, Why Apple Account Disabled From your Apple iPhone 13? How to Fix</u></a></li>
<li><a href="https://sound-issues.techidaily.com/logitech-g933-mic-not-working-fixed/"><u>Logitech G933 Mic Not Working [FIXED]</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/outperforming-vimeo-with-these-superior-alternatives/"><u>Outperforming Vimeo with These Superior Alternatives</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/step-by-step-guide-to-dynamic-sports-filmmaking/"><u>Step-by-Step Guide to Dynamic Sports Filmmaking</u></a></li>
</ul></div>

