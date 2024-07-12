---
title: "Quick Fixes: Making Winget Work Again in Windows"
date: 2024-07-11T21:44:48.451Z
updated: 2024-07-12T21:44:48.451Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Quick Fixes: Making Winget Work Again in Windows"
excerpt: "This Article Describes Quick Fixes: Making Winget Work Again in Windows"
keywords: Winget Functionality,WinWingetRepair,QuickWingetFix,RestoreWindowsWinget,FixWingetError,WindowsWingetQuick,ResetWinPackageManager
thumbnail: https://thmb.techidaily.com/238e2de8d5663845563adee13d68f244664dc4975f435870883240d8e13b1f76.jpg
---

## Quick Fixes: Making Winget Work Again in Windows

 Winget is a command-line tool that can download and install app packages from MS Store and the apps listed in its repository. It saves a lot of time that would be otherwise wasted in searching the Microsoft Store or the web for a particular app, downloading it, and then manually installing it.

 But some users report that Winget is not working on their PC. They face a "The system cannot execute the specified program" and cannot run any commands, This post will discuss multiple methods to resolve the issue and restore Winget to its working state. Let’s begin.

## Reasons Why Winget Stops Working on Windows

 Here are the following reasons why Winget is not working on your Windows PC:

1. You are running an outdated version of the App Installer.
2. Winget servers are down, or you don’t have an active internet connection.
3. The app execution alias is not configured or inactive for Winget.
4. App Installer failed to add the PATH environment variable automatically while installing.

 Now, you know the reasons behind Winget not working issue. Try out these eight methods to resolve the issue and use your favorite package manager again.

## 1\. Close and Reopen Winget in the Terminal App

 Before moving on to advanced fixes, completely close the Command Prompt or PowerShell instance you are running on the PC. You can use the Task Manager to stop an unresponsive instance of either of these command-line tools.

 After that, open Command Prompt or PowerShell with administrator privileges on your system. Type Winget and press the **Enter** key to check if Winget works now.

## 2\. Check if the Winget Servers Are Down

 Winget is an online tool that needs a robust internet connection to search for a package in various repositories and then download and install them. If the Winget servers are down or inactive, it won’t be able to fetch results from repositories. So, check if Winget servers are down using [DownDetector](https://redirect.viglink.com/?format=go&jsonp=vglnk%5F168667664973511&key=eac202ea7a96cf485281d6c4ffa2069e&libId=liuggg0i0103es17000ULlmtlntd&loc=https%3A%2F%2Fwww.makeuseof.com%2Fhow-to-fix-0x8004def5-onedrive-error-code-windows-11%2F&ccpaConsent=1---&v=1&opt=true&optExText=false&out=https%3A%2F%2Fdowndetector.com%2F&ref=https%3A%2F%2Fwww.makeuseof.com%2Fauthor%2Fabhishekkumar-mishra%2F&title=9%20Ways%20to%20Fix%20the%200x8004def5%20OneDrive%20Error%20Code%20on%20Windows%2011&txt=DownDetector) or a similar website.

 You can also check if your Windows PC can connect to the internet. Simply open a web browser and access a website or run a web-based app to confirm internet connectivity. If the servers are down, you will have to wait until they come up live again to use Winget.

## 3\. Perform a Complete System Shutdown

 Windows uses Fast Startup to hibernate kernel-level processes and if any of these glitch, they remain in that state after your power on the system. So, perform a complete shutdown to close and relaunch all the core services and then try to run Winget. Here’s how to do it:

1. Press **Win + R** to open the Run dialog box. Type **cmd** and press **Ctrl + Shift + Enter** keys to [open the Command Prompt with administrator privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Now, type the following command and press the Enter key: **shutdown /s /f /t 0**  
![Completely Shutdown your PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/completely-shutdown-your-pc.jpg)
3. Your system will shut down. It will take longer than a usual shutdown because Windows will close everything.
4. Power on your system and try to run Winget using the Terminal app to check if it works now.

## 4\. Update App Installer

 Winget is a part of Windows 10 and 11 now and is shipped to PCs using the App Installer application. If you haven’t updated the App Installer in a while, you can face issues in running Winget and managing packages. Winget is included only in version 1.11.11451 or higher of the App Installer. If you have a version older than that, you cannot use Winget from the terminal.

![Update App Installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/update-app-installer.jpg)

 So, open Microsoft Store and check the library section for any pending updates for the App Installer. Manually search and install the update and check if Winget works now.

## 5\. Enable the App Execution Alias

 If the App Execution Alias for Winget is disabled, it won’t work when you try accessing Winget from the terminal. So, you must enable it in the app settings. Repeat the following steps:

1. Right-click on the **Start** button to open the **Power User** menu. Click on the **Settings** app.
2. Navigate to the left-hand side menu and click on the **Apps** option.
3. Now, click on the **Advanced app settings** option. Then click on the **App execution aliases** option.
4. Locate the **Windows Package Manager Client** option. Check the toggle next to it. If it is disabled, click on it to **enable** the app execution alias for the app.  
![Enable the App Execution Alias-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/enable-the-app-execution-alias-1.jpg)
5. Close the Settings app.

## 6\. Manually Add the Path Environment Variable

 Ae wrongly configured Winget path can also produce errors. So, you must manually add the correct path in Environment Variables using the Advanced System Properties window. Repeat the following steps:

1. Press **Win + R** to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **sysdm.cpl ,3** in the text box and press the **Enter** key to open **Advanced System Properties**.
2. Click on the **Environment Variables** button. Click on the **Path** entry and then click on the **Edit** button.
3. Now, click on the New button and paste the following path: **%UserProfile%\\AppData\\Local\\Microsoft\\WindowsApps**  
![Manually Add the Path Environment Variable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/manually-add-the-path-environment-variable.jpg)
4. Click on the **OK** button. Restart your PC.
5. Open the Terminal app and check if Winget works or not.

## 7\. Re-register Winget Using PowerShell

 If Winget isn’t working on your PC, you can re-register it using PowerShell. Since it is a part of the App Installer which is a system app, it is possible to re-register it. Repeat the following steps:

1. Press **Win + R** to open the Run dialog box. Type **PowerShell** and press the **Ctrl + Shift + Enter** keys at once.
2. The PowerShell window will launch with admin rights. Paste the following code and press the **Enter** key to execute it:  
`Add-AppxPackage -DisableDevelopmentMode -Register "C:\Program Files\WindowsApps\Microsoft.Winget.Source_2021.718.1322.843_neutral__8wekyb3d8bbwe\AppXManifest.xml" -Verbose`
3. You won’t see any confirmation message after the command executes successfully. Close the PowerShell window and restart your PC.  
![Re-register Winget Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/re-register-winget-using-powershell.jpg)

## 8\. Try Some Generic Windows Fixes

 If none of the methods work for you, try our generic fixes like SFC and DISM scans that find and fix the system file corruption and service Windows Image components. You must [run the SFC scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) first and allow it to find and replace the corrupt system files, if any. After that, [run the DISM scan](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) in online mode.

 After running these scans, you can use System Restore to revert the PC to a point in time when everything worked fine. Lastly, you can perform a complete system reset. You can choose the Keep my files option to preserve all your files while [factory resetting Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/).

## Make Winget Functional Again

 Winget is a fantastic package manager that helps you control and manage app packages from the terminal. Ensure robust internet connectivity and check if the app execution alias is active for Winget. Manually reconfigure the PATH for Winget and re-register the App Installer using PowerShell. If you want a GUI version of Winget, you can try Winstall which helps you batch-install apps.

 But some users report that Winget is not working on their PC. They face a "The system cannot execute the specified program" and cannot run any commands, This post will discuss multiple methods to resolve the issue and restore Winget to its working state. Let’s begin.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/updated-stars-of-tomorrow-perfecting-reaction-videos-for-audiences-through-dual-perspectives/"><u>[Updated] Stars of Tomorrow  Perfecting Reaction Videos for Audiences Through Dual Perspectives</u></a></li>
<li><a href="https://howto.techidaily.com/app-wont-open-on-your-realme-c67-4g-here-are-all-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>App Wont Open on Your Realme C67 4G? Here Are All Fixes | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/steering-clear-of-windows-11-blunders-top-8-tips/"><u>Steering Clear of Windows 11 Blunders: Top 8 Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-fatal-error-code-0x800f0831/"><u>Resolving Windows' Fatal Error: Code 0X800F0831</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-lost-functionality-to-windows-netflix/"><u>Restoring Lost Functionality to Windows Netflix</u></a></li>
<li><a href="https://screen-recording.techidaily.com/1-3-in-ipad-voice-memos-and-recorders/"><u>1-3 in iPad Voice Memos & Recorders</u></a></li>
<li><a href="https://windows11.techidaily.com/reverse-frozen-wow-post-update-blocks/"><u>Reverse Frozen WoW Post-Update Blocks</u></a></li>
<li><a href="https://windows11.techidaily.com/keeping-notes-prominent-on-windows-10-and-11/"><u>Keeping Notes Prominent on Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/real-time-resource-management-tracking-cpu-memory-and-graphics/"><u>Real-Time Resource Management: Tracking CPU, Memory & Graphics</u></a></li>
<li><a href="https://windows11.techidaily.com/illuminating-text-adopting-notepads-dark-theme-windows/"><u>Illuminating Text: Adopting Notepad's Dark Theme (Windows)</u></a></li>
<li><a href="https://activate-lock.techidaily.com/latest-guide-on-ipad-23-and-iphone-15-pro-max-icloud-activation-lock-bypass-by-drfone-ios/"><u>Latest Guide on iPad 2/3 and iPhone 15 Pro Max iCloud Activation Lock Bypass</u></a></li>
<li><a href="https://windows11.techidaily.com/the-function-and-significance-of-vcplusplus-packages/"><u>The Function and Significance of VC++ Packages</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaim-shift-control-with-easy-fixes/"><u>Reclaim Shift Control with Easy Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-reverse-windows-enter-input-failure/"><u>Methods to Reverse Windows Enter Input Failure</u></a></li>
<li><a href="https://windows11.techidaily.com/supercharge-your-workday-top-5-win-11-productivity-tools/"><u>Supercharge Your Workday: Top 5 Win 11 Productivity Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/revealing-concealed-elements-a-guide-to-windows-11-ui/"><u>Revealing Concealed Elements: A Guide to Windows 11 UI</u></a></li>
<li><a href="https://windows11.techidaily.com/sling-verification-sluggishness-top-strategies-for-speedy-updates/"><u>Sling Verification Sluggishness: Top Strategies for Speedy Updates</u></a></li>
<li><a href="https://fake-location.techidaily.com/dose-life360-notify-me-when-someone-checks-my-location-on-vivo-v27e-drfone-by-drfone-virtual-android/"><u>Dose Life360 Notify Me When Someone Checks My Location On Vivo V27e? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-eliminating-nvidias-visual-boost/"><u>Step-by-Step: Eliminating NVIDIA's Visual Boost</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-open-the-internet-options-in-windows-11/"><u>How to Open the Internet Options in Windows 11</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-peering-into-the-past-publicly-shared-masterpieces/"><u>2024 Approved  Peering Into the Past  Publicly Shared Masterpieces</u></a></li>
<li><a href="https://windows11.techidaily.com/strategizing-windows-11-service-management-safely/"><u>Strategizing Windows 11 Service Management Safely</u></a></li>
<li><a href="https://windows11.techidaily.com/re-establishing-malwarebytes-service-connections-in-win-oses/"><u>Re-Establishing Malwarebytes' Service Connections in Win OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/initiating-windows-11s-concealed-query-engine/"><u>Initiating Windows 11'S Concealed Query Engine</u></a></li>
<li><a href="https://windows11.techidaily.com/trimming-excessive-load-reducing-the-burden-of-user-mode-services-on-pcs/"><u>Trimming Excessive Load: Reducing the Burden of User-Mode Services on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-unresponsive-downloads-in-windows-explorer/"><u>Troubleshooting Unresponsive Downloads in Windows Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-no-files-available-error-in-windows-11/"><u>Solving 'No Files Available' Error in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-recurring-edge-shortcut-installations/"><u>Preventing Recurring Edge Shortcut Installations</u></a></li>
<li><a href="https://windows11.techidaily.com/proactive-upgrade-implementing-tpm-and-secure-boot-on-w11-systems/"><u>Proactive Upgrade: Implementing TPM and Secure Boot on W11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-rejuvenate-your-windows-11-with-a-fresh-reboot/"><u>How to Rejuvenate Your Windows 11 with a Fresh Reboot</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-guide-vmware-crashes-bsod-on-win11/"><u>Troubleshooting Guide: VMware Crashes, BSOD on Win11</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-make-music-without-spending-a-dime-10-free-recording-software-options-for-2024/"><u>Updated Make Music Without Spending a Dime 10 Free Recording Software Options for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/quick-easy-shifts-adjust-imagesvideos-smartly/"><u>Quick, Easy Shifts  Adjust Images/Videos Smartly</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-solutions-to-find-your-samsung-galaxy-f34-5g-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>3 Solutions to Find Your Samsung Galaxy F34 5G Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-get-creative-with-free-sound-effects-a-beginners-guide-to-final-cut-pro/"><u>In 2024, Get Creative with Free Sound Effects A Beginners Guide to Final Cut Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/keep-your-data-and-save-space-win11s-secure-drive-management-methods-max-156-chars/"><u>Keep Your Data and Save Space: Win11's Secure Drive Management Methods (Max 156 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-and-sharing-files-building-extractable-sfxs-in-win11/"><u>Securing and Sharing Files: Building Extractable SFXs in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/removing-geforce-graphical-overlay-feature/"><u>Removing GeForce Graphical Overlay Feature</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-ultimate-guide-on-infinix-smart-8-pro-frp-bypass-by-drfone-android/"><u>In 2024, Ultimate Guide on Infinix Smart 8 Pro FRP Bypass</u></a></li>
<li><a href="https://windows11.techidaily.com/seamlessly-carry-over-your-custom-powertoys/"><u>Seamlessly Carry Over Your Custom PowerToys</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-stop-recurring-disk-full-issues-in-windows/"><u>How to Stop Recurring Disk Full Issues in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-photo-resizing-on-windows-11-6-steps/"><u>The Ultimate Guide to Photo Resizing on Windows 11 – 6 Steps</u></a></li>
</ul></div>
