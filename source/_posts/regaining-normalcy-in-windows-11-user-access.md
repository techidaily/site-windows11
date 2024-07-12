---
title: Regaining Normalcy in Windows 11 User Access
date: 2024-07-11T22:02:43.571Z
updated: 2024-07-12T22:02:43.571Z
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
<li><a href="https://windows11.techidaily.com/perfect-notetaking-companions-the-7-finest-for-pen-tech/"><u>Perfect Notetaking Companions: The 7 Finest for Pen Tech</u></a></li>
<li><a href="https://fix-guide.techidaily.com/play-store-stuck-on-downloading-of-vivo-y27-4g-7-ways-to-resolve-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Stuck on Downloading Of Vivo Y27 4G? 7 Ways to Resolve | Dr.fone</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-2024-approved-improve-your-videos-audio-quality-removing-background-noise-in-fcpx/"><u>Updated 2024 Approved Improve Your Videos Audio Quality Removing Background Noise in FCPX</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-transfer-music-from-infinix-hot-40-pro-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways to Transfer Music from Infinix Hot 40 Pro to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/value-capture-affordable-cam-options/"><u>Value Capture  Affordable Cam Options</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-unresponsive-printers-in-windows-11-environment/"><u>Remedying Unresponsive Printers in Windows 11 Environment</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-exploring-digital-dimensions-understanding-metaverse-vs-multiverse/"><u>[Updated] Exploring Digital Dimensions  Understanding Metaverse V/S Multiverse</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-disable-the-built-in-laptop-keyboard-in-windows/"><u>How to Disable the Built-In Laptop Keyboard in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-to-solving-disk-errors-uninitialized-scenarios/"><u>Quick Guide to Solving Disk Errors: Uninitialized Scenarios</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-mend-the-pairing-glitch-fixing-connection-issues-in-win-11/"><u>How to Mend the Pairing Glitch: Fixing Connection Issues in Win 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/a-comprehensive-list-of-prime-tablets-for-photo-editing-lovers-for-2024/"><u>A Comprehensive List of Prime Tablets for Photo Editing Lovers for 2024</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/consider-a-lut-to-be-a-color-preset-that-a-filmmaker-can-use-to-start-working-on-a-project-quickly-sony-engineers-have-developed-luts-to-help-filmmakers-per/"><u>Consider a LUT to Be a Color Preset that a Filmmaker Can Use to Start Working on a Project Quickly. Sony Engineers Have Developed LUTs to Help Filmmakers Perform Specific Tasks. All of These Are Available for Free</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-windows-steam-streams-stopping-zero-rate-issues/"><u>Optimize Windows Steam Streams: Stopping Zero-Rate Issues</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-the-availability-of-the-slow-motion-feature-on-the-iphone-is-often-debated-this-article-will-guide-you-on-how-to-slow-down-a-video-on-iphone-for-202/"><u>Updated The Availability of the Slow-Motion Feature on the iPhone Is Often Debated. This Article Will Guide You on How to Slow Down a Video on iPhone for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-multi-screen-brightness-best-tools-to-light-up-your-windows-monitors/"><u>Navigating Multi-Screen Brightness: Best Tools to Light Up Your Windows Monitors</u></a></li>
<li><a href="https://windows11.techidaily.com/initiating-contact-accessing-windows-printer-administration-tools/"><u>Initiating Contact: Accessing Windows' Printer Administration Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-stuck-context-menus-a-quick-guide-to-solutions/"><u>Overcoming Stuck Context Menus: A Quick Guide to Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/insights-on-how-to-utilize-execution-nicknames/"><u>Insights on How to Utilize Execution Nicknames</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-enabling-or-disabling-wi-fi-cost-tracking-in-windows-11/"><u>Guide: Enabling or Disabling Wi-Fi Cost Tracking in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-deactivated-system-cooler-protocol-on-pcs/"><u>Overcoming Deactivated System Cooler Protocol on PCs</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-barkers-symphony-an-assortment-of-dog-soundscapes-for-2024/"><u>Updated Barkers Symphony An Assortment of Dog Soundscapes for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-powershell-access-control-settings/"><u>Optimizing PowerShell Access Control Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/notepaddarksettingsinstructionswin1011/"><u>NotepadDarkSettingsInstructionsWin10/11</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-in-2024-how-to-add-adjustment-layer-clip-in-davinci-resolve/"><u>New In 2024, How to Add Adjustment Layer (Clip) in DaVinci Resolve?</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-mute-movie-tracks-steps-to-strip-audio-from-mov-files-in-windows-and-mac-os-for-2024/"><u>New Mute Movie Tracks Steps to Strip Audio From MOV Files in Windows and Mac OS for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-perfecting-pace-techniques-for-shooting-captivating-slow-motion-content-for-instagram-audiences-for-2024/"><u>[Updated] Perfecting Pace  Techniques for Shooting Captivating Slow Motion Content for Instagram Audiences for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-for-lowering-tiworkerexe-process-resource-use/"><u>Methods for Lowering TiWorker.exe Process Resource Use</u></a></li>
<li><a href="https://windows11.techidaily.com/reversing-camera-apps-loss-of-recorded-images/"><u>Reversing Camera App's Loss of Recorded Images</u></a></li>
<li><a href="https://windows11.techidaily.com/redirect-to-file-explorer-using-the-onedrive-shortcut/"><u>Redirect to File Explorer Using the OneDrive Shortcut</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/top-tracks-of-the-decade-on-spotify/"><u>Top Tracks of the Decade on Spotify</u></a></li>
<li><a href="https://windows11.techidaily.com/recovering-database-connections-resolving-malwarebytes-service-issues/"><u>Recovering Database Connections: Resolving Malwarebytes Service Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-boot-sector-problems-on-pc/"><u>Navigating Through Boot Sector Problems on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-store-error-code-0x80073cf3/"><u>Overcoming Windows Store Error Code 0X80073CF3</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-optimizing-content-editing-youtube-descriptions-and-titles-for-growth/"><u>2024 Approved  Optimizing Content  Editing YouTube Descriptions & Titles for Growth</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-global-lens-local-tales-how-to-transform-your-travel-experiences-into-content/"><u>2024 Approved  Global Lens, Local Tales  How to Transform Your Travel Experiences Into Content</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-geforce-x0001-error-on-w10w11-systems/"><u>Overcoming GeForce X0001 Error on W10/W11 Systems</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-unleash-creativity-with-these-5-advanced-tiktok-captioning-techniques-for-2024/"><u>[New] Unleash Creativity with These 5 Advanced TikTok Captioning Techniques for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-thinkers-playground-top-10-mind-bending-rooms/"><u>2024 Approved  Thinkers' Playground  Top 10 Mind-Bending Rooms</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-configure-time-zones-on-windows-manually/"><u>Quick Guide: Configure Time Zones on Windows Manually</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-code-0x0001-failures-for-nvidia-ge-in-w10w11/"><u>Rectifying Code 0X0001 Failures for Nvidia GE in W10/W11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/additional-tips-about-sinnoh-stone-for-itel-s23plus-drfone-by-drfone-virtual-android/"><u>Additional Tips About Sinnoh Stone For Itel S23+ | Dr.fone</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-unveiling-the-leading-mixers-5-highest-rated-audiovideo-combiner-devices-for-2024/"><u>Updated Unveiling the Leading Mixers 5 Highest Rated Audio/Video Combiner Devices for 2024</u></a></li>
</ul></div>
