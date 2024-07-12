---
title: "Navigating and Reviving Winget: A Guide for Windows 11 Users"
date: 2024-07-11T21:37:16.511Z
updated: 2024-07-12T21:37:16.511Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Navigating and Reviving Winget: A Guide for Windows 11 Users"
excerpt: "This Article Describes Navigating and Reviving Winget: A Guide for Windows 11 Users"
keywords: Win11 Winget Use,Winget Tool Tips,Revive Winget Steps,Winget Troubleshooting,Optimize Win11 Winget,Update Windows Winget,Guide to Winget Usage
thumbnail: https://thmb.techidaily.com/e9711d2ba9e06d496671fabcb5c03dc2cfd9b4b1eb26d7f5f5a9a68662ceb542.jpg
---

## Navigating and Reviving Winget: A Guide for Windows 11 Users

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
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-tagging-towards-triumph-the-best-instagram-hashtags/"><u>[Updated] In 2024, Tagging Towards Triumph  The Best Instagram Hashtags</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-users-through-fixing-nvidias-unreachable-error/"><u>Guiding Users Through Fixing NVIDIA's 'Unreachable' Error</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-notepad-abrupt-closures/"><u>Overcoming Windows Notepad Abrupt Closures</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-actions-for-windows-interface-crashing/"><u>Immediate Actions for Windows Interface Crashing</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-security-a-comprehensive-guide-to-lock-patterns-in-windows-11/"><u>Customizing Security: A Comprehensive Guide to Lock Patterns in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/pro-tip-unearthing-windows-apps-installed-locations-quickly/"><u>Pro Tip: Unearthing Windows Apps' Installed Locations Quickly</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-remove-the-lock-screen-fingerprint-of-your-samsung-galaxy-s23-fe-by-drfone-android/"><u>In 2024, Remove the Lock Screen Fingerprint Of Your Samsung Galaxy S23 FE</u></a></li>
<li><a href="https://windows11.techidaily.com/method-to-correct-windows-installation-glitch-xc004f050/"><u>Method to Correct Windows Installation Glitch Xc004f050</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-cutting-edge-concepts-for-captivating-youtube-video-thumbnails/"><u>2024 Approved  Cutting-Edge Concepts for Captivating YouTube Video Thumbnails</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/locating-your-own-playlists-on-youtube-for-2024/"><u>Locating Your Own Playlists on Youtube for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/disregard-met-not-fulfilled-emblem-on-win11/"><u>Disregard Met Not Fulfilled Emblem on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-uninstall-oneself-avoiding-admin-restrictions-in-windows/"><u>How To Uninstall Oneself: Avoiding Admin Restrictions in WINDOWS</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-android-and-ios-users-choice-top-playlist-saving-apps-for-youtube/"><u>[New] 2024 Approved  Android & iOS Users' Choice  Top Playlist Saving Apps for YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-onedrive-login-hiccup-zero-based-code-error-on-win11/"><u>Fixing OneDrive Login Hiccup: Zero-Based Code Error on Win11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-t-view-mov-movies-content-on-xiaomi-by-aiseesoft-video-converter-play-mov-on-android/"><u>Can’t view MOV movies content on Xiaomi </u></a></li>
<li><a href="https://change-location.techidaily.com/why-is-ipogo-not-working-on-vivo-v29-fixed-drfone-by-drfone-virtual-android/"><u>Why is iPogo not working On Vivo V29? Fixed | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-system-resource-usage-details-to-the-windows-system-tray/"><u>How to Add System Resource Usage Details to the Windows System Tray</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-launching-into-content-creation-account-setup-on-youtube/"><u>2024 Approved  Launching Into Content Creation  Account Setup on YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-start-the-narrator-in-windows-11/"><u>How to Start the Narrator in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/skyrocketing-vm-potential-in-windows-implement-these-top-strategies/"><u>Skyrocketing VM Potential in Windows - Implement These Top Strategies</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-can-honor-100-promirror-share-to-pc-drfone-by-drfone-android/"><u>How Can Honor 100 ProMirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-proven-mac-screen-recording-programs-beyond-bandicaps-success/"><u>In 2024, Proven Mac Screen Recording Programs Beyond Bandicap's Success</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/2024-approved-maximize-your-screen-real-estate-amazon-prime-video-aspect-ratio-hacks/"><u>2024 Approved Maximize Your Screen Real Estate Amazon Prime Video Aspect Ratio Hacks</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-going-back-with-android-video-editing/"><u>[Updated] Going Back with Android Video Editing</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-biometric-control-in-w11-for-domain-users/"><u>Secure Biometric Control in W11 for Domain Users</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-lost-thermal-management-directive-for-pcs/"><u>Restoring Lost Thermal Management Directive for PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/master-windows-performance-with-extended-display-setup/"><u>Master Window's Performance With Extended Display Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reactivate-muted-system-sound-output-quickly/"><u>How to Reactivate Muted System Sound Output Quickly</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/getting-into-the-details-a-review-of-kodak-luts-for-2024/"><u>Getting Into The Details A Review of Kodak LUTs for 2024</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/in-2024-optimizing-mobile-screen-design-a-guide-to-vertical-aspect-ratios/"><u>In 2024, Optimizing Mobile Screen Design A Guide to Vertical Aspect Ratios</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-windows-innovations-to-enrich-macos/"><u>Leveraging Windows Innovations to Enrich macOS</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-finding-your-video-complement-the-process-of-collaborative-pairing-for-2024/"><u>[Updated] Finding Your Video Complement  The Process of Collaborative Pairing for 2024</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-in-2024-beginners-guide-to-video-editing-best-software-choices/"><u>New In 2024, Beginners Guide to Video Editing Best Software Choices</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-iphone-photographic-file-import-failures-on-windows-pcs/"><u>Handling iPhone Photographic File Import Failures on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionizing-mouse-interactions-on-windows-via-clicklock-techniques/"><u>Revolutionizing Mouse Interactions on Windows via ClickLock Techniques</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-optimal-routines-to-alter-track-tempoplay-in-spotify/"><u>[Updated] Optimal Routines to Alter Track Tempoplay in Spotify</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-hastened-steps-for-clear-background-filming-success/"><u>[Updated] 2024 Approved  Hastened Steps for Clear Background Filming Success</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-the-leading-edge-in-social-media-video-capture-5-apps-reviewed/"><u>In 2024, The Leading Edge in Social Media Video Capture (5 Apps Reviewed)</u></a></li>
<li><a href="https://windows11.techidaily.com/flushing-dns-on-windows-best-practices/"><u>Flushing DNS on Windows: Best Practices</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-manage-windows-deletion-prompt-actions/"><u>Efficiently Manage Windows' Deletion Prompt Actions</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-samsung-galaxy-s8-4k-smartphone-review/"><u>2024 Approved  Samsung Galaxy S8 4K Smartphone Review</u></a></li>
<li><a href="https://windows11.techidaily.com/launching-windows-file-explorer-directly-via-onedrive/"><u>Launching Windows File Explorer Directly via OneDrive</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-batch-installs-windows-11-with-winstall/"><u>Mastering Batch Installs: Windows 11 with Winstall</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-looks-like-youre-stranded-xbox-app-error-in-windows-11-and-11/"><u>How to Fix the “Looks Like You’re Stranded” Xbox App Error in Windows 11 & 11</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-launching-an-impactful-instagram-live-session-for-2024/"><u>[New] Launching an Impactful Instagram Live Session for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/from-standard-to-stylish-personalize-each-window-11-screen/"><u>From Standard to Stylish: Personalize Each Window 11 Screen</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-leveraging-vr-to-shape-modern-business-practices/"><u>[New] Leveraging VR to Shape Modern Business Practices</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-permission-restrictions-on-windows/"><u>Deciphering Permission Restrictions on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/revising-account-lockout-count-after-multiple-login-failures-in-windows-11/"><u>Revising Account Lockout Count After Multiple Login Failures in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/purify-your-setup-tiny11s-no-fuss-features/"><u>Purify Your Setup: Tiny11's No-Fuss Features</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-system-stability-automatic-windows-and-amd-driver-shift/"><u>Elevate System Stability: Automatic Windows & AMD Driver Shift</u></a></li>
<li><a href="https://fix-guide.techidaily.com/in-2024-simple-and-effective-ways-to-change-your-country-on-youtube-app-of-your-xiaomi-redmi-note-12t-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Simple and Effective Ways to Change Your Country on YouTube App Of your Xiaomi Redmi Note 12T Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-sluggishness-boosting-speed-of-steam-on-windows/"><u>Overcoming Sluggishness: Boosting Speed of Steam on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-eliminate-windows-error-xc0f1103f-on-geforce/"><u>Steps to Eliminate Windows Error XC0F1103F on GeForce</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-looking-for-a-way-to-learn-how-to-merge-videos-in-handbrake-theres-a-better-solution-waiting-for-you-inside/"><u>2024 Approved Looking for a Way to Learn How to Merge Videos in HandBrake? Theres a Better Solution Waiting for You Inside</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/navigating-the-world-of-desktop-tiktok-a-step-by-step-guide-for-2024/"><u>Navigating the World of Desktop TikTok  A Step-by-Step Guide for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-taskmgr-with-command-line-interface-cli-feature/"><u>Enhance TaskMgr with Command Line Interface (CLI) Feature</u></a></li>
</ul></div>
