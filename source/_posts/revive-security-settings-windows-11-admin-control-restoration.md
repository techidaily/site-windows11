---
title: "Revive Security Settings: Windows 11 Admin Control Restoration"
date: 2024-11-21T01:22:41.352Z
updated: 2024-11-25T01:50:49.947Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Revive Security Settings: Windows 11 Admin Control Restoration"
excerpt: "This Article Describes Revive Security Settings: Windows 11 Admin Control Restoration"
keywords: Win11 Security Revival,Admin Control Recovery,Windows Setup Reset,Security Restore Proc,Admin Settings Fix,System Guard Reinstate,Windows Safeguard Refresh
thumbnail: https://thmb.techidaily.com/1734faea8dc6fb99b0356fb7510aa58c46806122f440ead1dafd4f608890d169.png
---

## Revive Security Settings: Windows 11 Admin Control Restoration

 Having issues with apps or programs not running properly on your Windows computer? Resetting Windows Update permissions could be the solution you need. Similarly, if you're troubleshooting user profile problems, you can restore user permissions.

 This article covers three different methods to reset all user permissions – using the Icacls command, the Secedit command, and the Subinacl tool.

Let's now explore them in detail.

## 1\. Run the Icacls Command

 The Icacls command allows you to view, modify, and reset file system permissions on files and folders. To reset Windows Update permissions using this command, you will first have to[take ownership of the folders on Windows](https://www.makeuseof.com/windows-10-11-own-folder/) . Then[open an elevated Command Prompt on Windows](https://www.makeuseof.com/windows-run-command-prompt-admin/) and type in the following command:

`icacls * /t /q /c /reset`

 Now press Enter on your keyboard to execute the command. This will reset all user permissions to default for every folder, subfolder, and file within the current working directory.

In the above command, here are the parameters explained:

* \* – This is a wildcard character that includes all folders within the current directory.
* /t – It targets all the subfolders and files within the current folder.
* /q – Run command without displaying success messages.
* /c – Continues the operation even if errors occur.
* /reset – This parameter resets the permission options to their default values.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qv4Qm7kpeMs?si=9fv5SOS5a2DvixTK&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Run the Secedit command

 Windows provides the Secedit command to configure and analyze system security. To reset all user permissions using this command, run the command prompt with admin access, then type in the following command:

![Run the Secedit command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-the-secedit-command.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fZTlPdOFNmo?si=Ym8p7ayV1gtNzzXj&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`secedit /configure /cfg %windir%\inf\defltbase.inf /db defltbase.sdb /verbose`

 Now press Enter to execute the command. Wait for the process to finish and restart your computer. This will reset the user permissions to the default system settings.

## 3\. Run the Subinacl Tool

 If you're not comfortable using the command prompt, you may use the Subinacl tool. This is a command-line utility from Microsoft that can be used to reset user permissions. Here's how to do it:

1. [Download the Subinacl tool from Microsoft's webpage](https://web.archive.org/web/20190830103837/http://www.microsoft.com/en-us/download/confirmation.aspx?id=23510) . When you open the page, the download starts automatically. If not, wait 30 seconds and click the link.
2. Once downloaded, double-click on the installer package. This will open the installation wizard.  
![Open the installation wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/open-the-installation-wizard.jpg)
3. Click on**Next** and then accept the license agreement terms.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aqeO4ed766s?si=AWtKHxP4hvQRd_lk&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Install the Subinacl tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-the-subinacl-tool.jpg)
4. Next, copy and paste the following path into the Destination folder:  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LI9nKlbhnw8?si=uUXFVbuEqXtFHHv0&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DBMTAJBx-X4?si=sje5pFJXiHzJJGbP&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://youtube-blog.techidaily.com/ed-unlock-content-insights-7-premier-free-tag-extraction-tools/"><u>[Updated] Unlock Content Insights 7 Premier Free Tag Extraction Tools</u></a></li>
<li><a href="https://win-news.techidaily.com/building-captivating-audiobooks-for-kids-a-step-by-step-guide-with-flipbuilder/"><u>Building Captivating Audiobooks for Kids: A Step-by-Step Guide with FlipBuilder</u></a></li>
<li><a href="https://some-approaches.techidaily.com/cambiar-formatos-de-fotos-eficientemente-convertir-dpx-en-jpg-gratis-usando-movavi/"><u>Cambiar Formatos De Fotos Eficientemente - Convertir DPX en JPG Gratis Usando Movavi</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/comprehensive-compilation-of-20-best-github-chatgpt-sessions/"><u>Comprehensive Compilation of 20 Best Github ChatGPT Sessions</u></a></li>
<li><a href="https://win-answers.techidaily.com/1723004543196-fifa-19-troubleshooting-no-more-pc-freezes-or-crashes/"><u>FIFA 19 Troubleshooting: No More PC Freezes or Crashes</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-updater-faulty-error-0xca00a009/"><u>Fixing Windows Updater Faulty Error 0xCA00A009</u></a></li>
<li><a href="https://windows11.techidaily.com/get-started-with-hyper-v-windows-11-homes-edition-setup-guide/"><u>Get Started with Hyper-V: Windows 11 Homes Edition Setup Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-resolve-the-no-hardware-detected-error-in-windows/"><u>How to Resolve the ‘No Hardware Detected’ Error in Windows</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-honor-magic-6-pro-to-other-android-devices-using-bluetooth-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from Honor Magic 6 Pro to Other Android Devices Using Bluetooth? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-through-the-maze-of-windows-temporary-folder-issues/"><u>Navigate Through the Maze of Windows Temporary Folder Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-directly-modifying-windows-installer-controls/"><u>Steps for Directly Modifying Windows Installer Controls</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/the-ultimate-guide-to-quicktime-video-editing-on-mac-for-2024/"><u>The Ultimate Guide to QuickTime Video Editing on Mac for 2024</u></a></li>
</ul></div>

