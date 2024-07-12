---
title: "Win11 Cleanup: Stripping Out Microsoft Store"
date: 2024-07-11T21:43:05.139Z
updated: 2024-07-12T21:43:05.139Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Win11 Cleanup: Stripping Out Microsoft Store"
excerpt: "This Article Describes Win11 Cleanup: Stripping Out Microsoft Store"
keywords: Win11 DeepClean,Remove MSStore,Win11 Optimize,Uninstall Microsoft Store,Free Win11 Space,Clean Windows 11,XPFreeupWin11
thumbnail: https://thmb.techidaily.com/fd283428cd4cb2c0907e2d15b8c7aa3306b361f3c11c9903f383663675146f0a.jpg
---

## Win11 Cleanup: Stripping Out Microsoft Store

 Microsoft Store is the go-to place for Windows users if they want to install an app. The app library is slowly expanding, and you will find all the popular apps without any difficulty. But sometimes the Microsoft Store application behaves abnormally and requires troubleshooting.

 But what if it still doesn’t work, even after repairing and resetting? There is no uninstall option in the Settings app, so it is possible to uninstall Microsoft Store? Well, it is possible to remove and reinstall the Microsoft Store app. Here’s how.

## Why Should You Uninstall the Microsoft Store App?

 Microsoft Store houses all the useful and popular applications for Windows devices. Moreover, it guarantees safe and malware-free application downloads. But if the app fails to start or doesn’t work properly, removing it makes sense.

 But don’t worry. You can remove the app and then reinstall it if you want. Reinstallation can fix persistent issues with the current version of the Microsoft Store app. It will remove the current app installation and all its related files and corrupt data. After that, you can reinstall the Microsoft app with a single command.

## How to Uninstall Microsoft Store App From Windows 11

 You can remove the Microsoft Store app from Windows 11 using the winget tool and run it using the command prompt. In addition, you can use the PowerShell cmdlet to remove the Microsoft Store application package from your system or use a batch file.

### 1\. Using Winget

 Winget is a handy Windows package manager tool available with the newer releases of Windows 10 and 11\. It makes it ridiculously easy to search and manage applications on your system. You can use it to remove any application, even the Microsoft Store app from your system. Here’s how:

1. Press the**Win + R** key to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**cmd** and press the**Ctrl + Shift + Enter** keys to launch the Command Prompt with administrator privileges.
2. Now, we need to locate the ID of the Microsoft Store app installed on the system. Type the following command in the command prompt window and press the enter key:**Winget list Store**
3. Winget will list all the installed programs on your system containing the string “store” in their name. Find the Microsoft Store app in the list and**copy** its**ID** .
4. After that, you need to run the uninstall command using winget. The syntax is**winget uninstall \[app ID\]** . So, the command will be:  
winget uninstall Microsoft.WindowsStore_8wekyb3d8bb
5. Press enter to execute the command and wait for it to execute successfully.  
![Uninstall Microsoft Store App using winget](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-winget.jpg)
6. Type**exit** in the command prompt window and press enter to close it.

### 2\. Using PowerShell

 Before winget was officially integrated into Windows 10 and 11, there was a method to [remove the Microsoft Store app using PowerShell](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) . The method still works and all you need to do is list the package name and then use the**Remove-AppxPackage** cmdlet to uninstall the Microsoft Store app from your system. Make sure to run PowerShell with elevated permissions.

### 3\. Using a Batch File

 If you want to save the hassle of typing commands every time you want to uninstall the Microsoft Store app, you can use a batch file. It will help you to remove Microsoft Store app from your system in a couple of clicks whenever the normal troubleshooting methods don’t work for you. Repeat the following steps:

1. Press**Win + D** to switch to the Desktop. Right-click on the Desktop and select the**New > Text Document** option.
2. Open the newly created text document file on the desktop. A Notepad window will pop up. Paste the following text in it:  
@echo off winget uninstall "Microsoft Store" exit
3. Now, press**Ctrl + Shift + S** to open the "Save as" window. Name the batch file as**UninstallStore.bat** and keep the**Save as** type option as**All files** .  
![Uninstall Microsoft Store App using batch file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-batch-file.jpg)
4. Click on the**Save** button. Close the Notepad window.
5. Press**Win + D** to switch to the desktop again. Right-click on the batch file and select the**Run as administrator** option from the context menu.
6. A command prompt window will open, run the Microsoft Store app uninstallation command, and close automatically. You don’t need to interact with the window.
7. Open the Start menu and search for Microsoft Store. You won’t find any matching app on your system.

## Easily Remove the Microsoft Store From Windows

 Windows 10 and 11 don’t offer an option to uninstall Microsoft Store. So, you are only left at the mercy of a system restore or reset. However, you can now uninstall the Microsoft Store app from your system using any of the three methods mentioned above. You can also reinstall it using the PowerShell cmdlet and continue using the app again.


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
<li><a href="https://windows11.techidaily.com/how-to-fix-the-page-could-not-be-loaded-error-in-the-microsoft-store-for-windows/"><u>How to Fix the Page Could Not Be Loaded Error in the Microsoft Store for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-dual-monitor-setup-problems/"><u>Resolving Dual Monitor Setup Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-workflow-multitask-with-windows-11-expertise/"><u>Optimizing Workflow: Multitask with Windows 11 Expertise</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-challenge-of-0x8007045d-error-on-windows-11/"><u>Overcoming the Challenge of 0X8007045d Error on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-future-of-personal-computing-transforming-window-11-widgets/"><u>The Future of Personal Computing: Transforming Window 11 Widgets</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-microsoft-teams-instability-on-ws11ws10-devices/"><u>Preventing Microsoft Teams Instability on WS11/WS10 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-widgets-to-the-windows-11-desktop/"><u>How to Add Widgets to the Windows 11 Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-solutions-to-resolve-instant-failure-in-adding-a-folder-in-onedrive/"><u>Swift Solutions to Resolve Instant Failure in Adding a Folder in OneDrive</u></a></li>
<li><a href="https://windows11.techidaily.com/ftdibussys-and-windows-exploring-the-memory-integrity-dilemshift/"><u>Ftdibus.sys and Windows: Exploring the Memory Integrity Dilemshift</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-taskbar-tools-monitoring-cpu-ram-and-disk-use/"><u>Tailored Taskbar Tools: Monitoring CPU, RAM & Disk Use</u></a></li>
<li><a href="https://windows11.techidaily.com/simplified-docx-to-pdf-workflow-in-windows-11-systems/"><u>Simplified DOCX to PDF Workflow in Windows 11 Systems</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-brisk-tutorial-transforming-photos-into-youtube-desktop-thumbnails/"><u>2024 Approved  Brisk Tutorial  Transforming Photos Into YouTube Desktop Thumbnails</u></a></li>
<li><a href="https://windows11.techidaily.com/nine-pathways-out-of-the-window-11s-0x8004def5-puzzle/"><u>Nine Pathways Out of the Window 11'S 0X8004DEF5 Puzzle</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-nokia-c110-location-on-skout-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Nokia C110 Location on Skout | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-apple-iphone-8-plus-with-a-mask-on-by-drfone-ios/"><u>How to Unlock Apple iPhone 8 Plus with a Mask On</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-deleting-account-info-from-windows-logon/"><u>Steps for Deleting Account Info From Windows Logon</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/2024-approved-the-visual-blueprint-understanding-social-media-aspect-ratios-for-success/"><u>2024 Approved The Visual Blueprint Understanding Social Media Aspect Ratios for Success</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-potential-of-windows-11s-configurable-fn-keys/"><u>Mastering the Potential of Windows 11'S Configurable FN Keys</u></a></li>
<li><a href="https://extra-skills.techidaily.com/live-production-pros-dilemma-pmix-vs-castpro-for-2024/"><u>Live Production Pros' Dilemma  PMix Vs. CastPro for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/apply-these-techniques-to-improve-how-to-detect-fake-gps-location-on-honor-100-pro-drfone-by-drfone-virtual-android/"><u>Apply These Techniques to Improve How to Detect Fake GPS Location On Honor 100 Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/installation-essentials-intel-network-adapters-for-windows-users/"><u>Installation Essentials: Intel Network Adapters for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/learn-9-keys-to-tweaking-windows-audio-properties/"><u>Learn 9 Keys to Tweaking Windows Audio Properties</u></a></li>
<li><a href="https://windows11.techidaily.com/nullify-specification-shortfalls-alerts-in-win11/"><u>Nullify Specification Shortfalls Alerts in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/sudos-arrival-in-windows-os-explained/"><u>Sudo's Arrival in Windows OS Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/proactive-measures-for-sticky-notes-longevity/"><u>Proactive Measures for Sticky Notes' Longevity</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-asana-not-working-on-windows/"><u>How to Fix Asana Not Working on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/flawless-system-transition-mastering-windows-11s-in-place-update-process/"><u>Flawless System Transition: Mastering Windows 11'S In-Place Update Process</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-notebook-interface-with-themes-and-fonts/"><u>Streamline Your Notebook Interface with Themes & Fonts</u></a></li>
<li><a href="https://windows11.techidaily.com/reactivating-inputs-post-sleep-on-latest-windows/"><u>Reactivating Inputs Post-Sleep on Latest Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-group-policy-editor-navigation-windows-11-style/"><u>Mastering Group Policy Editor Navigation, Windows 11 Style</u></a></li>
<li><a href="https://windows11.techidaily.com/the-clarity-connoisseurs-guide-top-tips-for-perfecting-pc-displays/"><u>The Clarity Connoisseur's Guide: Top Tips for Perfecting PC Displays</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-sim-unlock-lava-blaze-2-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>In 2024, Sim Unlock Lava Blaze 2 Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/pro-tips-for-buying-windows-11-vcs/"><u>Pro Tips for Buying Windows 11 VCs</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-ornate-asian-dwellings-for-your-next-build-off/"><u>In 2024, Ornate Asian Dwellings for Your Next Build-Off</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-an-incorrect-cpu-usage-in-the-windows-task-manager/"><u>How to Fix an Incorrect CPU Usage in the Windows Task Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/switching-your-windows-security-pin-quickly/"><u>Switching Your Windows Security Pin Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-and-resolving-outlooks-error-0x80040610/"><u>Navigating Through and Resolving Outlook's Error 0X80040610</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-strategies-to-rectify-freeze-in-obs-fullscreen-functionality/"><u>[Updated] In 2024, Strategies to Rectify Freeze in OBS Fullscreen Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-failed-capture-issue-in-win11-photoapp/"><u>Overcoming 'Failed Capture' Issue in Win11 PhotoApp</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-excellent-zooid-formats-for-creation/"><u>In 2024, Excellent Zooid Formats for Creation</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-error-xc0000142-with-windows-oses/"><u>Fixing Error XC0000142 with Windows OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-folder-menu-enhancement-with-new-commands-win-11/"><u>Step-by-Step Guide: Folder Menu Enhancement with New Commands (Win 11)</u></a></li>
<li><a href="https://games-able.techidaily.com/5-essential-steps-to-transform-the-xbox-game-bar-interface-on-your-pc/"><u>5 Essential Steps to Transform the Xbox Game Bar Interface on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/remediation-techniques-for-resource-occupancy-errors-149-chars/"><u>Remediation Techniques for Resource Occupancy Errors (149 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11s-software-compatibility-tool/"><u>Navigating Windows 11’S Software Compatibility Tool</u></a></li>
</ul></div>
