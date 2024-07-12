---
title: Clearing Custom Privileges in Win11 by Default
date: 2024-07-11T22:28:13.925Z
updated: 2024-07-12T22:28:13.925Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Clearing Custom Privileges in Win11 by Default
excerpt: This Article Describes Clearing Custom Privileges in Win11 by Default
keywords: Win11 Privilege Management,Clearance Windows 11,Disable Default Permissions,Win11 User Settings,Privilege Reset Win11,Access Control in Win11,Secure Win11 Configurations
thumbnail: https://thmb.techidaily.com/09fee241173a4d75afd314bc2889ac10d1158fd98dc41bc3885e34ece3467540.jpg
---

## Clearing Custom Privileges in Win11 by Default

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
<li><a href="https://windows11.techidaily.com/correcting-audacitys-internal-portaudio-error-on-w10w11-pcs/"><u>Correcting Audacity's Internal PortAudio Error on W10/W11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/creative-windows-users-heres-the-best-drawing-list/"><u>Creative Windows Users, Here’s the Best Drawing List</u></a></li>
<li><a href="https://extra-skills.techidaily.com/speedy-steps-for-assembling-image-collections-on-mac-for-2024/"><u>Speedy Steps for Assembling Image Collections on Mac for 2024</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-next-gen-sound-the-most-impressive-dj-audio-editing-solutions-reviewed/"><u>New 2024 Approved Next-Gen Sound The Most Impressive DJ Audio Editing Solutions Reviewed</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-music-from-realme-c33-2023-by-fonelab-android-recover-music/"><u>How to retrieve erased music from Realme C33 2023</u></a></li>
<li><a href="https://extra-resources.techidaily.com/5-best-slow-motion-cameras/"><u>5 Best Slow Motion Cameras</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-differences-windows-10-meets-windows-11/"><u>Deciphering the Differences: Windows 10 Meets Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/discovering-surface-laptop-studio-2-the-near-perfect-companion/"><u>Discovering Surface Laptop Studio 2 - The Near-Perfect Companion</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-efficient-automation-to-dot-and-ifttt/"><u>Crafting Efficient Automation: To-Dot & IFTTT</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/top-5-vivo-x100-pro-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 Vivo X100 Pro Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://windows11.techidaily.com/diminishing-drain-techniques-to-limit-vanguards-user-mode-cpu-use/"><u>Diminishing Drain: Techniques to Limit Vanguard's User-Mode CPU Use</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-samsung-galaxy-s23-tactical-edition-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>How to Unlock Samsung Galaxy S23 Tactical Edition Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-tutorial-downloading-and-setting-up-msixbundle-and-msix-file-types/"><u>Comprehensive Tutorial: Downloading & Setting Up Msixbundle & MSIX File Types</u></a></li>
<li><a href="https://network-issues.techidaily.com/windows-10-display-glitch-resolved/"><u>Windows 10 Display Glitch: Resolved</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-overview-how-to-optimize-w11s-auto-hdr/"><u>Comprehensive Overview: How to Optimize W11's Auto HDR</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-the-ultimate-guide-to-tiktok-captioning-mastery/"><u>2024 Approved  The Ultimate Guide to TikTok Captioning Mastery</u></a></li>
<li><a href="https://windows11.techidaily.com/discreet-toolbar-tactics-concealing-items-in-windows-11/"><u>Discreet Toolbar Tactics: Concealing Items in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-setting-up-outlook-preview-for-w10w11/"><u>Comprehensive Guide: Setting up Outlook Preview for W10/W11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-freenoweb-cam-app-assessment-and-comparison-guide-for-2024/"><u>[New] FreenoWeb Cam App Assessment & Comparison Guide for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/command-line-to-admin-initiating-windows-11s-task-manager-with-power/"><u>Command Line to Admin: Initiating Windows 11'S Task Manager with Power</u></a></li>
<li><a href="https://windows11.techidaily.com/convenient-telnet-setup-for-modern-windows-systems-wins/"><u>Convenient Telnet Setup for Modern Windows Systems (Wins)</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-pioneering-cinematic-language/"><u>2024 Approved  Pioneering Cinematic Language</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/gain-ground-on-social-media-leaders-with-insta-growth-tips/"><u>Gain Ground on Social Media Leaders with Insta-Growth Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/defeating-disk-defenders-sync-soundcard-irq-in-windows/"><u>Defeating Disk Defenders: Sync Soundcard IRQ in Windows</u></a></li>
<li><a href="https://screen-recording.techidaily.com/capturing-facetime-best-practices-unveiled-for-2024/"><u>Capturing FaceTime  Best Practices Unveiled for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-windows-11-security-filters-in-context-menu/"><u>Configuring Windows 11 Security Filters in Context Menu</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-disabled-iphone-15-plusipad-without-computer-by-drfone-ios/"><u>In 2024, How to Unlock Disabled iPhone 15 Plus/iPad Without Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/discovering-new-horizons-for-galaxy-users-on-pc/"><u>Discovering New Horizons for Galaxy Users on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-chrome-display-glitches-on-pc/"><u>Clearing Chrome Display Glitches on PC</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-2024-approved-master-photo-framing-techniques-via-digital-platforms-2-written-by-user-johndoe/"><u>[New] 2024 Approved  Master Photo Framing Techniques via Digital Platforms (2 Written by User JohnDoe</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-cutting-edge-free-premiere-pro-templates-2023/"><u>2024 Approved  Cutting-Edge, FREE Premiere Pro Templates 2023</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-income-journey-on-youtube-start-here-with-8-tips/"><u>[Updated] Income Journey on YouTube - Start Here with 8 Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-windows-process-aggregatorhostexe-use-and-risks/"><u>Deciphering Windows Process AggregatorHost.exe: Use and Risks</u></a></li>
<li><a href="https://windows11.techidaily.com/de-cluttering-notifications-tips-for-windows-11-users/"><u>De-Cluttering Notifications: Tips for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/design-dilemma-overcoming-unexpected-screen-shades/"><u>Design Dilemma: Overcoming Unexpected Screen Shades</u></a></li>
<li><a href="https://windows11.techidaily.com/delving-into-windows-11s-data-preservation-capabilities/"><u>Delving Into Windows 11'S Data Preservation Capabilities</u></a></li>
<li><a href="https://windows11.techidaily.com/command-the-control-of-windows-accessibility-options/"><u>Command the Control of Windows' Accessibility Options</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/global-viewer-count-triumphs-play-button-honors/"><u>Global Viewer Count Triumphs  Play Button Honors</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-avoid-hassles-simple-iphone-screen-sharing/"><u>[Updated] 2024 Approved  Avoid Hassles  Simple Iphone Screen Sharing</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-why-many-dismiss-windows-11-now/"><u>Decoding Why Many Dismiss Windows 11 Now</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/reasons-why-pokemon-gps-does-not-work-on-nokia-c22-drfone-by-drfone-virtual-android/"><u>Reasons why Pokémon GPS does not Work On Nokia C22? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-high-dpi-display-issues-in-windows/"><u>Clearing Up High DPI Display Issues in Windows</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-unlock-pro-quality-edits-top-1080p-video-editing-tools/"><u>New Unlock Pro-Quality Edits Top 1080P Video Editing Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/classic-game-storage-integrating-into-the-windows-photos-space/"><u>Classic Game Storage: Integrating Into the Windows Photos Space</u></a></li>
<li><a href="https://windows11.techidaily.com/corrective-measures-for-xc0351000-hyprocvisor-not-found/"><u>Corrective Measures for XC0351000: Hyprocvisor Not Found</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-rectifying-delayed-folder-upload-in-onedrive-without-hitches/"><u>Comprehensive Guide: Rectifying Delayed Folder Upload in OneDrive without Hitches</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-2024-approved-free-audio-transmutation-exploring-six-efficient-ways-to-convert-video-to-sound/"><u>New 2024 Approved Free Audio Transmutation Exploring Six Efficient Ways to Convert Video to Sound</u></a></li>
<li><a href="https://windows11.techidaily.com/dealing-with-active-directory-printer-problems-a-guide-for-win-10-users/"><u>Dealing with Active Directory Printer Problems: A Guide For WIN 10 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/decode-and-resolve-uninitialized-disk-message-on-pc/"><u>Decode and Resolve Uninitialized Disk Message on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-old-wallpaper-a-simple-three-step-plan/"><u>Clearing Old Wallpaper - A Simple Three-Step Plan</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/2024-approved-the-ultimate-list-of-16-free-avi-video-rotation-tools-for-any-platform/"><u>2024 Approved The Ultimate List of 16 Free AVI Video Rotation Tools for Any Platform</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-resolving-directdraw-errors-on-win1011/"><u>Decoding and Resolving DirectDraw Errors on WIN10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/combating-writing-denials-in-windows-11-environment/"><u>Combating Writing Denials in Windows 11 Environment</u></a></li>
<li><a href="https://location-fake.techidaily.com/3utools-virtual-location-not-working-on-samsung-galaxy-s24-ultra-fix-now-drfone-by-drfone-virtual-android/"><u>3uTools Virtual Location Not Working On Samsung Galaxy S24 Ultra? Fix Now | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-and-rectifying-windows-steams-error-e84/"><u>Demystifying and Rectifying Windows Steam's Error E84</u></a></li>
</ul></div>
