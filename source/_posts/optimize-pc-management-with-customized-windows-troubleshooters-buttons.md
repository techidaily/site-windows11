---
title: Optimize PC Management with Customized Windows Troubleshooters Buttons
date: 2024-07-11T21:55:16.247Z
updated: 2024-07-12T21:55:16.247Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Optimize PC Management with Customized Windows Troubleshooters Buttons
excerpt: This Article Describes Optimize PC Management with Customized Windows Troubleshooters Buttons
keywords: Optimal PC Tips,Windows Easy Fixes,Custom Troubleshoot Tools,Manage PC Effectively,Simplify System Glitches,Enhance PC Settings,Streamlined PC Management
thumbnail: https://thmb.techidaily.com/4344716e214d80fc0302240776bca3183fcb221b8492651a99a24a405c1e3fa0.jpg
---

## Optimize PC Management with Customized Windows Troubleshooters Buttons

 Windows 11 and 10 include various troubleshooting tools you can open via Settings and the Control Panel. There are troubleshooters for fixing Bluetooth, internet, Windows Update, audio, hardware, printer, video, and MS Store app-related errors that arise. Those troubleshooters detect issues and either automatically apply or suggest potential fixes to resolve them.

 Adding troubleshooter shortcuts to Windows 11/10 will save you from rummaging through Settings or the Control Panel whenever you need to access them. You can create troubleshooter shortcuts on the Windows 11/10 desktop, taskbar, Start menu, and even context menu with the methods below.

## How to a Set Up a Desktop Shortcut for Opening the Troubleshooting Applet

 Most users probably go through Settings to bring up troubleshooters. However, Control Panel’s Troubleshooting applet includes more troubleshooters than the Settings app. Adding a [desktop shortcut](https://www.makeuseof.com/what-is-desktop-shortcut-how-work/) for opening the applet will enable you to access all troubleshooters included within it more quickly.

 You can create a Troubleshooting shortcut on the Windows desktop in the following steps:

1. Right-click any part of the desktop area and select**New** .
2. Click the**Shortcut** option on the**New** submenu.  
![The Shortcut option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/shortcut-option.jpg)
3. Input**explorer shell:::{C58C4893-3BE0-4B45-ABB5-A63E4B8C8651}** inside the location box, and select the Create Shortcut wizard’s**Next** option.  
![The Create Shortcut window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/create-shortcut-window.jpg)
4. Erase the default shortcut title, and type**Troubleshooting Applet** in the text box.
5. Select**Finish** to add the Troubleshooting Applet desktop shortcut.  
![The Troubleshooting Applet desktop shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/troubleshooting-applet-shortcut.jpg)

 Double-click the new desktop shortcut you just added to open the Troubleshooting applet. There you can click**Programs** ,**Hardware and Sound** ,**Network and Internet** , or**System and Security** to view and access different categories of troubleshooters. Alternatively, select**View all** open to bring up a full list of troubleshooters. You can click any troubleshooter there to open it.

![The Troubleshooting applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-troubleshooting-applet.jpg)

 The Troubleshooting shortcut will have the same folder library icon as Explorer’s taskbar button. If you would prefer something else, you can change the icon via the shortcut’s properties window. Check out our guide about [how to customize icons on Windows](https://www.makeuseof.com/tag/customize-icon-windows/) for details.

## How to Set Up Taskbar and Start Menu Troubleshooting Shortcuts

 You can easily convert the Troubleshooting Applet desktop shortcut into a taskbar or Start menu one. To do so in Windows 11, click the Troubleshooting Applet shortcut with the right mouse button and select**Show more options** . Select**Pin to taskbar** on the classic menu to stick the same shortcut on the taskbar. Or click**Pin to Start** to have one for opening the Troubleshooting applet from the pinned area of the Start menu.

![The Pin to taskbar option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/pin-to-taskbar-option.jpg)

 Then you may as well remove the desktop shortcut if a taskbar or Start menu one is preferred. Right-click Troubleshooting Applet to select**Delete** (the trash bin icon in Windows 11).

## How to Set Up a Troubleshooting Hotkey

 A Troubleshooting desktop shortcut can also become a convenient hotkey in a few quick steps. All you have to do is set a key combination for activating the desktop shortcut. Then you can open the Troubleshooting applet by pressing a**Ctrl** +**Alt** key combo. These are the steps for setting up a hotkey that opens the Troubleshooting applet:

1. Create a desktop shortcut for opening the Troubleshooting applet as outlined in the first method.
2. Right-click the Troubleshooting shortcut and select**Properties** .
3. Click inside the box labeled**Shortcut key** .
4. Press**T** (for troubleshooting) to establish a**Ctrl** +**Alt** +**T** key combination.  
![The Shortcut key box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/shortcut-key-option.jpg)
5. Select**Apply** to save your new troubleshooting hotkey.
6. Click**OK** or**X** to close the Shortcut tab and window.

 Now you can access the Troubleshooting applet with a key combo. Press**Ctrl** +**Alt** +**T** to open that applet and access its troubleshooters. That hotkey depends on the desktop shortcut you set it for. So, you’ve got to leave the shortcut on the desktop.

## How to Set Up Shortcuts for Opening Specific Troubleshooters

 You can also set up shortcuts for opening any specific troubleshooters included within the Troubleshooting Control Panel applet. Each troubleshooter there has a pack ID with which you can set up a desktop shortcut for opening it. You can set up a troubleshooter shortcut in such a way via the Create Shortcut wizard with the following command:

`msdt.exe /id <diagnostic_id>`

 The above command must include an actual diagnostic\_id for the troubleshooter. This [MSDT page](https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2008-R2-and-2008/ee424379%28v=ws.10%29?redirectedfrom=MSDN) has a list of troubleshooting pack IDs you can include in that command. These are the diagnostic ID commands for some of the more useful troubleshooters:

`msdt.exe /id WindowsUpdateDiagnostic  
  
msdt.exe /id SearchDiagnostic  
  
msdt.exe /id DeviceDiagnostic  
  
msdt.exe /id PrinterDiagnostic  
  
msdt.exe /id NetworkDiagnosticsWeb  
  
msdt.exe /id AudioPlaybackDiagnostic`

 You can set up a desktop shortcut for a specific troubleshooter much the same as the Troubleshooting applet. Go through the same steps in this guide’s instructions for setting up a desktop shortcut, but input a troubleshooter diagnostic ID command at step three instead. Enter a different name for the shortcut in step four, and select the**Finish** option.

![The Windows Update troubleshooter command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-update-troubleshooter-command.jpg)

 Double-clicking that desktop shortcut will open whatever troubleshooter you set it to with the diagnostic ID command. Then you can also pin that desktop shortcut to the taskbar or Start menu just the same as the Troubleshooting applet one. Or set up a hotkey for opening the troubleshooting tool as outlined in this guide’s keyboard shortcut instructions.

![The Windows Update troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-update-troubleshooter-and-shortcut.jpg)

## How to Add a Troubleshooters Submenu to the Context Menu

 The right-click context menu is another place you can add Troubleshooting shortcuts in Windows 11/10\. You can set up a**Troubleshooters** submenu on the Windows 11/10 context menu that includes shortcuts for opening different parts of the Troubleshooting applet. To do that, you only need to download and run a premade registry script like this:

1. Open the [Add Troubleshooters Context Menu Softpedia page](https://www.softpedia.com/get/Tweak/System-Tweak/Add-Troubleshooters-Context-Menu-in-Windows-10.shtml) .
2. Select that registry script’s**Download Now** option.
3. Click the**Secure Download (US)** option.
4. Go into File Explorer (press**Win** +**E** to open), and bring up the directory containing the registry script’s ZIP archive.  
![The Extract Compressed Folders tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/extract-compressed-folder-tool.jpg)
5. Select to extract the troubleshooters-context-menu.zip archive. Our guide to [unzipping ZIP files on Windows](https://www.makeuseof.com/unzip-files-windows-10/) includes instructions for extracting these archives.
6. Open the extracted troubleshooters-context-menu folder.
7. Double-click the**Add Troubleshooters To Desktop Context Menu.reg** file.  
![The troubleshooters-context-menu folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/troubleshooters-context-menu-folder.jpg)
8. Click**Yes** on the prompt that asks for user confirmation to apply the script.

 You will now see a new**Troubleshooters** submenu on your desktop’s context menu. Right-click any space within the desktop wallpaper area and select**Show more options** on Windows 11’s context menu. Move the cursor over the**Troubleshooters** submenu to view its shortcuts.

![The Troubleshooters submenu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/troubleshooters-option.jpg)

 There you can select**Classic Troubleshooting applet** to bring up the Troubleshooting home screen in the Control Panel. Select**All Categories** to open the full list of troubleshooters. Or click**Programs** ,**Hardware and Sound** ,**Network and Internet** , and**System Security** to view category pages for opening troubleshooters.

 The troubleshooters-context-menu folder also includes a script for removing the Troubleshooters submenu. Double-click**Remove Troubleshooters From Desktop Context Menu.reg** in that folder to run that script. Then select**Yes** to erase the submenu from the context menu.

## Make Some Shortcuts for Accessing Troubleshooters in Windows

 So, now you can create Windows shortcuts for opening the Troubleshooting applet and more specific troubleshooters in various ways. You can create a general Troubleshooting Control Panel desktop, taskbar, keyboard, or context menu shortcut for accessing all troubleshooting tools. Or set up shortcuts that give you more direct access to the specific troubleshooting tools you utilize more regularly.

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
<li><a href="https://windows11.techidaily.com/quicker-quests-9-strategies-to-prevent-wwe-2k23-crashes/"><u>Quicker Quests: 9 Strategies to Prevent WWE 2K23 Crashes</u></a></li>
<li><a href="https://windows11.techidaily.com/unblock-windows-task-scheduler-issues-quickly/"><u>Unblock Windows Task Scheduler Issues Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshoot-non-functional-windows-security-on-win-11/"><u>Troubleshoot Non-Functional Windows Security on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-common-errors-in-office-app-activation-on-pc/"><u>Resolving Common Errors in Office App Activation on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-overcome-win-11s-store-error-x00000000/"><u>Steps to Overcome Win 11'S Store Error X00000000</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-skyline-of-success-stardews-top-7-upgrades-review-for-2024/"><u>[Updated] Skyline of Success  Stardew's Top 7 Upgrades Review for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-quieting-geforces-visual-flourishes/"><u>Step-By-Step: Quieting GeForce's Visual Flourishes</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/nhancing-engagement-imovie-techniques-for-youtube-intros-for-2024/"><u>[New] Enhancing Engagement  IMovie Techniques for YouTube Intros for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-expert-approved-video-editing-software-for-2024/"><u>New Expert-Approved Video Editing Software for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-windows-11s-frustrating-5ghz-link-failures/"><u>Solving Windows 11'S Frustrating 5GHz Link Failures</u></a></li>
<li><a href="https://windows11.techidaily.com/unbroken-streams-winos-stability-verification-guide/"><u>Unbroken Streams: WinOS Stability Verification Guide</u></a></li>
<li><a href="https://howto.techidaily.com/8-workable-fixes-to-the-sim-not-provisioned-mm2-error-on-motorola-moto-g23-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Workable Fixes to the SIM not provisioned MM#2 Error on Motorola Moto G23 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-address-game-pass-connection-errors-in-windows/"><u>Techniques to Address Game Pass Connection Errors in Windows</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/cutting-the-cord-on-costs-select-best-free-yt-title-makers/"><u>Cutting the Cord on Costs - Select Best-Free YT Title Makers</u></a></li>
<li><a href="https://windows11.techidaily.com/vanishing-acts-concealing-keys-without-notice/"><u>Vanishing Acts: Concealing Keys Without Notice</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/superior-streams-with-av1-activate-on-youtube-for-2024/"><u>Superior Streams with AV1  Activate on YouTube for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-solving-microsoft-offices-0x80041015/"><u>Understanding & Solving Microsoft Office's 0X80041015</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/3-ways-for-android-pokemon-go-spoofing-on-oneplus-11-5g-drfone-by-drfone-virtual-android/"><u>3 Ways for Android Pokemon Go Spoofing On OnePlus 11 5G | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-how-to-add-captions-to-instagram-videos/"><u>[New] In 2024, How to Add Captions to Instagram Videos</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-vn-video-editor-app-review-is-it-worth-the-download/"><u>New VN Video Editor App Review Is It Worth the Download?</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-win11-potential-essential-commands-and-tricks-with-nircmd/"><u>Unlock Win11 Potential: Essential Commands & Tricks with NirCmd</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-and-personalize-the-ultimate-desktop-guide-for-win11-users/"><u>Streamline & Personalize: The Ultimate Desktop Guide for Win11 Users</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-sim-unlock-huawei-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>In 2024, Sim Unlock Huawei Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/the-authoritative-tiktok-symbol-compendium/"><u>The Authoritative TikTok Symbol Compendium</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-2024-approved-full-mastery-guide-adobe-cloud-and-its-rival-services/"><u>[New] 2024 Approved  Full Mastery Guide  Adobe Cloud and Its Rival Services</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-advanced-steps-in-monitoring-and-archiving-system-sounds/"><u>2024 Approved  Advanced Steps in Monitoring & Archiving System Sounds</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-adding-speed-meter-to-taskbar/"><u>Quick Guide: Adding Speed Meter to Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/trimming-down-linux-overheads-in-android-wsl-setup/"><u>Trimming Down Linux Overheads in Android WSL Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/revisiting-exe-execution-hurdles-in-windows/"><u>Revisiting EXE Execution Hurdles in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-windows-experience-by-fixing-prerequisites-first/"><u>Streamline Windows Experience by Fixing Prerequisites First</u></a></li>
<li><a href="https://extra-information.techidaily.com/begin-your-journey-into-xps-video-editing-world-for-2024/"><u>Begin Your Journey Into Xp's Video Editing World for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-prime-selections-the-best-free-screencasting-apps/"><u>[New] In 2024, Prime Selections  The Best Free Screencasting Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/resolve-credential-manager-login-issues/"><u>Resolve Credential Manager Login Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/when-windows-acts-up-reboot-or-reset/"><u>When Windows Acts Up, Reboot or Reset?</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-virtual-potential-hyper-v-for-windows-11-users/"><u>Unlocking Virtual Potential: Hyper-V for Windows 11 Users</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-metaverse-vs-multimetaverse-elucidating-the-variances-ultimate-guide/"><u>[Updated] Metaverse Vs. MultiMetaverse  Elucidating the Variances (Ultimate Guide)</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-global-sensations-surpassing-100-million-views-on-youtube-the-yearly-countdown/"><u>[New] Global Sensations  Surpassing 100 Million Views on YouTube (The Yearly Countdown)</u></a></li>
</ul></div>
