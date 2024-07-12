---
title: Solutions for Unstartable Windows VMs with VMware
date: 2024-07-11T21:58:39.142Z
updated: 2024-07-12T21:58:39.142Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Solutions for Unstartable Windows VMs with VMware
excerpt: This Article Describes Solutions for Unstartable Windows VMs with VMware
keywords: WinVM Issues Fix,VM Startup Problems,Virtual Machine Recovery,Troubleshoot VMware,Boot VM Failures,Resume Unstarted VMs,Windows VM Repair Guide
thumbnail: https://thmb.techidaily.com/ad7d05b0030775951042fde08b0fbde9a0ebb4cf05f0435bf5618af5d7b42ae3.jpg
---

## Solutions for Unstartable Windows VMs with VMware

 Virtual machines enable you to try out multiple operating systems without removing your main operating system. VMware is one such popular third-party hypervisor that supports multiple operating systems. However, some users face the 'Failed to start the virtual machine' error when they power on any virtual machine in VMware.

 As a result, they are unable to launch any virtual machine in VMware and are stuck at the error screen. We will discuss multiple methods to resolve this issue and help you successfully launch the virtual machine. Let’s begin.

## 1\. Close and Restart the VMWare Virtual Machine

 VMware can face a glitch and can face issues while launching the virtual machines. So, you must completely close the app and run it with administrator rights. Here’s how:

1. Right-click on the **Start** button to launch the Power User menu. Click on the **Task Manager** option.
2. Click on the search bar and type **vmware**. Press the **Enter** key to search for all the related processes.
3. Right-click on the process and select the **End Task** option.  
![Terminate and restart VMware](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/terminate-and-restart-vmware.jpg)
4. Similarly, close all the related processes and then close the Task Manager window.
5. Press the **Win** key, type **vmware**, and click on the **Run as administrator** option.
6. The User Account Control window will open. Click on the **Yes** button.
7. Try to launch a virtual machine and check if you face the error again.

## 2\. Check If Virtualization is Active

 Every virtualization program including VMware needs hardware virtualization to work on a Windows PC. So, if you have turned off virtualization from BIOS, you must re-enable it. Repeat the following steps:

1. **Restart** your Windows PC.
2. Repeatedly mash the designated **F-key** (or even **Esc** key in some cases) to enter the BIOS. You can find out the designated F-key for your PC by searching its model name.
3. Switch to the **Advanced Settings** page.
4. Locate the **Hardware Virtualization** settings. In our Asus PC, it shows up as “**SVM**” mode, but you may see other names like **VT-x**, **AMD-V**, or **Vanderpool**. Use the **arrow** key to highlight and press the **Enter** key to enable the feature.  
![Enable hardware virtualization in BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/enable-hardware-virtualization-in-bios.jpg)
5. Press the **F10** key to save the changes and exit the BIOS.
6. Boot to the desktop and launch VMware. Check if you can launch a virtual machine without any error.

## 3\. Update VMware App

 An outdated and buggy build of VMware can cause issues with certain features. So, you must update the app to install the latest build and fix issues with new Windows updates. Here’s how to do it:

1. Press the **Win** key and type **vmware**. Then press the **Enter** key to open the app.
2. Go to the top menu and click on the **Player** button.
3. Navigate to the **Help > Software updates** option.
4. Click on the **Check for updates** button.  
![Updating the VMware app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/updating-the-vmware-app.jpg)
5. Wait for the utility to search the servers for new updates if any. Download and install the updates on your PC.
6. **Restart** your PC and launch VMware. Power on a virtual machine and check if the error pops up or not.

## 4\. Disable Memory Integrity in Windows Security

 Memory Integrity is a feature listed under the Core Isolation setting in the Windows Security app. It protects high-security processes from malware and requires hardware virtualization. Since hardware virtualization can only be used by one program at a time, VMware can encounter errors when you power on a virtual machine.

 So, you must disable memory integrity on your PC. Here’s how to do it:

1. Press the **Win** key, type **Windows Security**, and press the **Enter** key.
2. Click on the **Device Security** option.
3. Locate the **Core Isolation** section and click on the **Core Isolation details** option.
4. Now, click on the **toggle** below **Memory Integrity** to disable the feature.  
![Disable Memory Integrity](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/disable-memory-integrity.jpg)
5. **Close** the Windows Security app.

## 5\. Remove Other Windows Virtualization Features

 VMware relies on the Windows Hypervisor Platform feature which offers support for third-party hypervisors. But if you have other Windows virtualization features also installed on your PC, it can conflict with VMware’s virtual machine. So, you must remove these features. Repeat the following steps:

1. Press **Win + R** to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **appwiz.cpl** and press the **Enter** key.
2. The Programs and Features window will open. Click on the **Turn Windows features on or off** option.
3. Scroll down and uncheck **Hyper-V**, **Virtual Machine Platform**, and **Windows Subsystem for Linux** features in the list.
4. Click on the **OK** button.  
![Remove other virtualization features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/remove-other-virtualization-features.jpg)
5. Now, click on the **Restart now** button to apply the changes and remove all these features from your PC.

## 6\. Disable VBS

 Virtualization-based security can interfere with third-party hypervisors, so you must disable it. Check out [how to disable VBS to increase performance in Windows 11](https://www.makeuseof.com/windows-11-disable-vbs/) for more information. After disabling VBS, launch VMware and run a virtual machine to check if the 'Failed to Start the Virtual Machine' error persists.

## 7\. Remove Any Other Virtualization-Based Program

 If you use other third-party hypervisors like VirtualBox on your PC, you must uninstall them for some time and then run VMware. You won’t lose any virtual machines because you are only removing the hypervisor program. The virtual machine files will remain intact.

 Repeat the following steps to remove other hypervisors:

1. Press **Win + R** to open the Run dialog box. Type **appwiz.cpl** in the text box and press the **Enter** key.
2. The Programs and Features window will launch. Scroll down and locate the other third-party hypervisors in the list.
3. **Right-click** on the program and click on the **Uninstall** option.
4. Follow the on-screen instructions to remove the program from your computer.

## 8\. Reinstall the VMware App

 If the existing installation of VMware is corrupt or crucial files are missing from the installation folder, you must reinstall the app. It will remove all the installation files and install a new copy of the app on your PC.

 Repeat the following steps to install VMware using Winget:

1. Right-click on the **Start** button to open the **Power User** menu. Click on the **Terminal (Admin)** option.
2. The User Account Control window will pop up. Click on the **Yes** button.
3. Type the following command and press the **Enter** key to uninstall VMware:  
`Winget uninstall VMware.WorkstationPlayer`
4. Wait for Winget to remove the app package from your PC.
5. Now, execute the following command to install VMware from the Winget repository:  
`Winget install VMware.WorkstationPlayer`
6. It will take a while to download and install the app on your PC.  
![Reinstalling VMware](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/reinstalling-vmware.jpg)
7. **Close** the Terminal app window.
8. Launch VMware and power on a virtual machine to check if it runs without any issues now.

## 9\. Use System Restore

 If VMware was running fine on your PC before installing a new update or making changes to your PC, you can [use System Restore](https://www.makeuseof.com/use-system-restore-windows/) to revert to an earlier state. All your personal files will stay unaffected, and you won’t have to reset your PC for an app.

## Get VMware Working Again

 These were the nine methods to fix VMware’s 'Failed to Start the Virtual Machine' error on Windows 11\. Check virtualization settings in BIOS, update the app, and disable memory integrity. After that, disable VBS, uninstall optional virtualization features, and reinstall the app to fix the issue.

 As a result, they are unable to launch any virtual machine in VMware and are stuck at the error screen. We will discuss multiple methods to resolve this issue and help you successfully launch the virtual machine. Let’s begin.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/bypass-windows-folder-permission-snags-swiftly/"><u>Bypass Windows Folder Permission Snags Swiftly</u></a></li>
<li><a href="https://windows11.techidaily.com/ace-your-win-11-games-with-these-best-fps-tools/"><u>Ace Your Win 11 Games with These Best FPS Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-services-that-dont-launch/"><u>Addressing Windows Services That Don't Launch</u></a></li>
<li><a href="https://windows11.techidaily.com/a-history-of-the-windows-taskbar-from-1985-to-2023/"><u>A History of the Windows Taskbar From 1985 to 2023</u></a></li>
<li><a href="https://windows11.techidaily.com/amplify-tray-ui-add-scrolllock-and-number-keys-iconos/"><u>Amplify Tray UI: Add ScrollLock and Number Keys Iconos</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-oppo-a1x-5g-to-outlook-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Oppo A1x 5G to Outlook | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/choosing-your-win-software-downloader-choco-versus-wslm/"><u>Choosing Your Win Software Downloader: Choco Versus WSLM</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/ultimate-guide-on-xiaomi-redmi-note-12r-frp-bypass-by-drfone-android/"><u>Ultimate Guide on Xiaomi Redmi Note 12R FRP Bypass</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-limited-it-admin-power-in-security-warning/"><u>Bypassing 'Limited IT Admin Power' In Security Warning</u></a></li>
<li><a href="https://windows11.techidaily.com/batch-processing-excellence-using-task-scheduler/"><u>Batch Processing Excellence Using Task Scheduler</u></a></li>
<li><a href="https://windows11.techidaily.com/changing-default-user-directory-labels-windows-11/"><u>Changing Default User Directory Labels (Windows 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-vscode-shutdown-troubles-in-new-os/"><u>Avoiding VSCode Shutdown Troubles in New OS</u></a></li>
<li><a href="https://windows11.techidaily.com/apexs-windows-woes-strategies-to-clear-no-server-error-(156-chars/"><u>Apex's Windows Woes: Strategies to Clear No-Server Error (<156 Chars)</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-10-best-free-luts-roundup-download-links-galore/"><u>[New] 10 Best Free LUTs Roundup - Download Links Galore</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/voice-recognition-to-written-language-a-guide/"><u>Voice Recognition to Written Language A Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/beginner-friendly-steps-to-install-chrome-on-windows-11/"><u>Beginner-Friendly Steps to Install Chrome on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-restoration-features-your-pathway-through-windows-11/"><u>Activating Restoration Features: Your Pathway Through Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/1719351366052-breathe-new-life-into-your-win11-printer-with-these-tips/"><u>Breathe New Life Into Your Win11 Printer with These Tips!</u></a></li>
<li><a href="https://windows11.techidaily.com/beneath-radar-outstanding-windows-11-customization/"><u>Beneath Radar: Outstanding Windows 11 Customization</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-what-is-daw-digital-audio-workstation-myth-solved/"><u>In 2024, What Is DAW (Digital Audio Workstation) -Myth Solved</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-practices-for-detaching-soundtracks-in-film-clips/"><u>New Practices for Detaching Soundtracks in Film Clips</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-creating-a-safe-mc-habitat-plan-6/"><u>2024 Approved  Creating a Safe MC Habitat  Plan #6</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-the-sluggishness-of-windows-discord-features/"><u>Addressing the Sluggishness of Windows Discord Features</u></a></li>
<li><a href="https://windows11.techidaily.com/5-key-adjustments-for-a-mac-look-in-windows-environment/"><u>5 Key Adjustments for a Mac Look in Windows Environment</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-fb-ad-videos-made-easy-utilize-free-video-making-kit/"><u>[Updated] In 2024, FB Ad Videos Made Easy  Utilize Free Video-Making Kit</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-blue-screen-blues-fixing-error-740-on-winos/"><u>Avoiding Blue Screen Blues: Fixing Error 740 on WINOS</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-full-facebook-call-archive-feature-guide/"><u>2024 Approved  Full-Facebook Call Archive Feature Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/captivating-yuletide-atmosphere-in-window-artistry/"><u>Captivating Yuletide Atmosphere in Window Artistry</u></a></li>
<li><a href="https://windows11.techidaily.com/6-expert-windows-programs-for-video-editors/"><u>6 Expert Windows Programs for Video Editors</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-shooting-in-the-dark-elevating-iphone-photos-with-shadows/"><u>2024 Approved  Shooting in the Dark  Elevating iPhone Photos with Shadows</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-performance-of-docker-in-wsl-2-on-windows-devices/"><u>Boosting Performance of Docker in WSL 2 on Windows Devices</u></a></li>
</ul></div>
