---
title: Uninstalling the Default Software on Win11 PCs
date: 2024-07-11T21:47:23.985Z
updated: 2024-07-12T21:47:23.985Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Uninstalling the Default Software on Win11 PCs
excerpt: This Article Describes Uninstalling the Default Software on Win11 PCs
keywords: Win11 Uninstall Guide,Default App Removal,Windows 11 Cleanup,System Default Deletion,Built-In Software Removal,Win11 Exclusive Tools,PC Customization Tips
thumbnail: https://thmb.techidaily.com/13632811731c559bc127701456401507af159186a9de22e1aa59a5e7f9127b24.jpg
---

## Uninstalling the Default Software on Win11 PCs

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
<li><a href="https://windows11.techidaily.com/overcome-windows-obstacles-expert-advice-awaits/"><u>Overcome Windows Obstacles: Expert Advice Awaits!</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reactivate-lost-bluetooth-listings-dmi/"><u>How to Reactivate Lost Bluetooth Listings DMI</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-4-ways-to-sync-audio-to-video-automatically-in-for-2024/"><u>New 4 Ways to Sync Audio to Video Automatically In for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/liberating-windows-past-a-set-of-three-tactics/"><u>Liberating Windows Past - A Set of Three Tactics</u></a></li>
<li><a href="https://windows11.techidaily.com/perfectly-presented-photos-mastering-the-art-of-crafting-captivating-slideshows-in-win11-photos-app/"><u>Perfectly Presented Photos: Mastering the Art of Crafting Captivating Slideshows in Win11 Photos App</u></a></li>
<li><a href="https://windows11.techidaily.com/n-series-window-enigma-deciding-factors/"><u>N-Series Window Enigma: Deciding Factors</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-new-submenus-to-windows-11s-desktop-context-menu/"><u>How to Add New Submenus to Windows 11’S Desktop Context Menu</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-best-alternatives-to-virtualdub-video-processing-software-compared/"><u>In 2024, Best Alternatives to VirtualDub Video Processing Software Compared</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-social-sanctuary-secure-access-restored/"><u>[New] Social Sanctuary  Secure Access Restored</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-endure-no-more-teams-login-troubles-in-windows/"><u>How to Endure No More Teams Login Troubles in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/strike-balance-not-conflict-choose-one-antivirus-on-your-windows-pc/"><u>Strike Balance, Not Conflict: Choose One Antivirus on Your Windows PC</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-in-2024-seamless-speed-control-the-editors-essential-handbook/"><u>[Updated] In 2024, Seamless Speed Control  The Editor's Essential Handbook</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-no-supported-devices-found-in-windows-11/"><u>Overcoming No Supported Devices Found in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/personalizing-windows-space-adding-this-pc-iconography/"><u>Personalizing Windows Space: Adding 'This PC' Iconography</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-productivity-with-windows-11-calendar/"><u>Maximizing Productivity with Windows 11 Calendar</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-best-realme-frp-bypass-guide-by-drfone-android/"><u>In 2024, Best Realme FRP Bypass Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-system-limit-fixing-gpt-windows-problems/"><u>Overcoming System Limit: Fixing GPT Windows Problems</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-time-travel-photos-on-snapchat-step-by-step-guide/"><u>[Updated] Time-Travel Photos on Snapchat  Step by Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/the-savvy-buyers-guide-to-finding-windows-11-deals/"><u>The Savvy Buyer's Guide to Finding Windows 11 Deals</u></a></li>
<li><a href="https://windows11.techidaily.com/top-10-uses-for-windows-powertoys-tools/"><u>Top 10 Uses for Windows PowerToys Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-startup-opening-sticky-notes-seamlessly-on-pc/"><u>Streamlining Startup: Opening Sticky Notes Seamlessly on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/pushing-boundaries-my-quest-to-overcome-app-guard-censorship/"><u>Pushing Boundaries: My Quest to Overcome App Guard Censorship</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-windows-cars-keyboard-magic-boosts-speed/"><u>Top 5 Windows Cars: Keyboard Magic Boosts Speed</u></a></li>
<li><a href="https://windows11.techidaily.com/leveling-web-speeds-for-seamless-experience/"><u>Leveling Web Speeds for Seamless Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/tackle-interruptexception-in-win11-blue-screen/"><u>Tackle INTERRUPT_EXCEPTION in Win11 Blue Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-access-to-any-language-hotkeys-for-efficient-translation-in-windows-os/"><u>Quick Access to Any Language: Hotkeys for Efficient Translation in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-error-code-3-nvidias-win10-and-11-woes/"><u>Tackling Error Code 3: NVIDIA's Win10 & 11 Woes</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-a-polished-w11-workspace/"><u>Quick Fixes for a Polished W11 Workspace</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-2024-approved-voice-customization-leaders-beyond-echo-magic/"><u>[New] 2024 Approved  Voice Customization Leaders  Beyond Echo Magic</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-detect-and-dislodge-suddenly-installed-rav-antivirus/"><u>How to Detect & Dislodge Suddenly Installed Rav Antivirus</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-fixing-windows-office-error-0x80041015/"><u>Solutions for Fixing Windows Office Error 0X80041015</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-your-view-simple-fixes-for-windows-11-screen-haze/"><u>Transform Your View: Simple Fixes for Windows 11 Screen Haze</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tuning-taskbars-date-and-time-presentation/"><u>Fine-Tuning Taskbar's Date & Time Presentation</u></a></li>
<li><a href="https://windows11.techidaily.com/modifying-failed-login-lockout-timer-in-windows-1011/"><u>Modifying Failed Login Lockout Timer in Windows 10/11</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-vertical-video-mastery-the-best-editing-apps-for-iphone-and-android/"><u>Updated Vertical Video Mastery The Best Editing Apps for iPhone and Android</u></a></li>
<li><a href="https://windows11.techidaily.com/fast-track-eliminate-extra-software-in-windows-11/"><u>Fast Track: Eliminate Extra Software in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/speedy-boot-ups-in-windows-11-discover-the-best-practices/"><u>Speedy Boot-Ups in Windows 11 – Discover the Best Practices</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-process-for-ram-recalibration-on-win-11/"><u>Step-by-Step Process for RAM Recalibration on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-through-samsung-flow-connected-life-for-devices/"><u>Navigate Through Samsung Flow - Connected Life for Devices</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-the-easy-route-to-capturing-every-gameplay-moment-for-2024/"><u>[Updated] The Easy Route to Capturing Every Gameplay Moment for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-0x80072efd-in-win1110s-microsoft-store/"><u>Solving 0X80072EFD in Win11/10's Microsoft Store</u></a></li>
<li><a href="https://windows11.techidaily.com/swipe-to-learn-comparing-windows-10-ui-with-windows-11/"><u>Swipe to Learn: Comparing Windows 10 UI with Windows 11</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-seamless-stories-from-the-past-accessing-older-fb-content-on-pcmobile-for-2024/"><u>[New] Seamless Stories From The Past  Accessing Older FB Content on PC/Mobile for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-unleash-creativity-the-best-9-camera-accessories-for-vloggers-and-more/"><u>[Updated] Unleash Creativity  The Best 9 Camera Accessories for Vloggers and More</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-app-management-in-windows-the-power-of-winget/"><u>Mastering App Management in Windows: The Power of Winget</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-synthesis-how-meditation-transforms-cognition-and-emotion/"><u>Seamless Synthesis: How Meditation Transforms Cognition & Emotion</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-set-up-linux-and-linux-apps-on-a-windows-pc/"><u>How to Set Up Linux and Linux Apps on a Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-file-write-permissions-correction-on-win/"><u>Mastering File Write Permissions Correction on Win</u></a></li>
</ul></div>
