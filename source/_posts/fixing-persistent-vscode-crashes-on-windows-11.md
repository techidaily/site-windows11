---
title: Fixing Persistent VSCode Crashes on Windows 11
date: 2024-07-11T21:26:30.654Z
updated: 2024-07-12T21:26:30.654Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Persistent VSCode Crashes on Windows 11
excerpt: This Article Describes Fixing Persistent VSCode Crashes on Windows 11
keywords: Fix VSCode Crashes,Stop VSCode Freeze,Resolve Code Editor Errors,Stabilize VSCode Windows,Eliminate VSCode Crashes,Prevent VSCode Glitches,Avoid Code Editor Failures
thumbnail: https://thmb.techidaily.com/34a94943f164b90199ce5a5021ae83a50e184cfb3851095557656d94288c8df5.jpg
---

## Fixing Persistent VSCode Crashes on Windows 11

 Visual Studio Code is a popular IDE widely preferred by programming enthusiasts. Microsoft revamped its user interface and made it available on Microsoft Store as well. You can even install multiple extensions in Visual Studio Code to make your programming experience better.

 But many users face abrupt crashes in the Visual Studio Code app which impedes their workflow. If you face the same issue repeatedly, don't worry. We will list out multiple fixes so that you can try and resolve the issue on your computer. Let's dive into the post.

## 1\. Terminate Visual Studio Code and Restart

 Before moving on to more complex fixes for the app, completely close Visual Studio Code using Task Manager and restart it. Here's how to do it:

1. Right-click on the**Start** button to open the [Power User menu](https://www.makeuseof.com/windows-power-menu-guide/) . Click on the**Task Manager** option.
2. Locate the Visual Studio Code process in the list of active processes.
3. Right-click on it and click on the**End Task** option from the context menu. It will close Visual Studio Code app and all its associated processes.  
![Terminate Visual Studio Code and Restart](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/terminate-visual-studio-code-and-restart.jpg)
4. Close the Task Manager window and open the Start menu.
5. Type Visual Studio Code and run the app with administrator privileges. Check if it encounters a crash now.

## 2\. Reboot your System

 Restarting the system is the oldest trick in the book. It might not sound effective but resolves most of the system issues. Restarting a system helps in closing all the active processes and services, clearing the system memory, and relaunching them. Due to this, any services or apps that aren't working will also restart afresh.

**Right-click** on the Start button and select the**Restart** option from the Power user menu. After the system restarts, run the Visual Studio Code with administrator permissions and check if it crashes.

## 3\. Disable Hardware Acceleration

 Hardware acceleration can cause problems on the low-spec system running the Visual Studio app. There isn’t an option for this feature in the app settings. So, you must modify the argv.json file to disable it. Here's how:

1. Launch Visual Studio Code and click on the**Settings** icon in the bottom left corner.
2. Select the**Command Palette** option from the settings menu and click on the**Preferences: Configure Runtime Arguments** option.
3. Now, enter the following command in the argv.json file:**"disable-hardware-acceleration": true**  
![Disable Hardware Acceleration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-hardware-acceleration.jpg)
4. Press**Ctrl+ S** to save the changes to the file.
5. Restart the app and check if it crashes now.

## 4\. Perform a Clean Boot

 Often, third-party apps and services can interfere with other apps and cause app freezes and crashes. So, to rule out this possibility, do a [clean boot of your Window system](https://www.makeuseof.com/clean-boot-windows-11/) with only Microsoft-related services enabled on startup.

 If Visual Studio Code works fine after a clean boot, retry the clean boot while enabling some third-party service. Repeat this process until you find the problematic service or app.

## 5\. Disable Visual Studio Code Extensions

 Visual Studio Code needs extensions to extend language and debugger support for various programming languages. If you use extensions, you must find and remove the troublesome ones. Here's how to do it:

1. Launch Visual Studio Code and press**Ctrl+ Shift + X** to open the extensions settings.
2. Click on the**Installed** option to display all the extensions installed in the Visual Studio Code app.
3. Right-click on any extension and select the**Disable** option from the context menu.  
![Disable Visual Studio Code Extensions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-visual-studio-code-extensions.jpg)
4. Repeat this process for all extensions to disable them.
5. Now restart the Visual Studio Code app and run it for some time without any extensions. If it doesn't crash, an extension is probably the reason behind the crash.
6. To identify the extension, revisit the Extension settings in the app and right-click on a disabled extension. Select the**Enable** option.
7. Check if Visual Studio Code encounters a crash when this extension is active. Repeat the process to find the culprit extension and remove it from the app.

## 6\. Exclude Visual Studio Code in Windows Defender

 Antivirus programs do not play nicely with apps and programs and often wrongly flag them. So, add an exclusion for the Visual Studio Code app. If you use a third-party antivirus on your system, add an exclusion for the Visual Studio Code app directory by accessing its settings. You can even [temporarily disable Windows Security](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) and run the app to check if it crashes now.

## 7\. Update Visual Studio Code

 If you are using a very old version of Visual Studio Code and are facing abrupt crashes, then you must update the app. A new app update brings security improvements and bug fixes which could exist in the old version of the app. Here’s how to update the app:

1. Open Visual Studio Code and click on the**Settings** icon.
2. Select the**Check for updates** option from the context menu.  
![Update the Visual Studio Code](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/update-the-visual-studio-code.jpg)
3. If there is an update available, download and install it and restart your computer.
4. Launch the app again and use it for some time while keeping an eye out for crashes.

## 8\. Roll Back the Last Windows Update

 Windows updates can break system features or not sit well with third-party apps. If you encounter the app crash issue after a recent update,[manually uninstall the most recent Windows update](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) on your computer. It will revert all the new changes made to your system.

## 9\. Reinstall Visual Studio Code

 If the app installation is severely corrupt and unfixable, then a simple app reset won’t be effective. Instead, you must completely remove Visual Studio Code from your system and then reinstall it.

 Repeat the following steps to reinstall Visual Studio Code using Winget:

1. Press**Win + R** to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**cmd** in the text input box and press**Ctrl + Shift + Enter** to launch the command prompt with administrator rights.
3. Accept the UAC prompt and click on the**Yes** button.
4. Type the following command and press enter key:**Winget list**
5. Copy the ID of the Visual Studio Code app and paste it after the following command:**winget uninstall \[App ID\]**  
winget uninstall Microsoft.VisualStudioCode
6. Wait for the uninstallation to complete. Restart your system.  
![Reinstall Visual Studio Code 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reinstall-visual-studio-code-1.jpg)
7. Launch the Command Prompt with admin privileges again.
8. Then type the following command and press the enter key:**winget install Microsoft.VisualStudioCode**  
![Reinstall Visual Studio Code 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reinstall-visual-studio-code-2.jpg)
9. It will take a while to download and install the app on your system. You won’t need to interact with the installer window or grant any permissions.
10. Run Visual Studio Code now and check if the app encounters any crashes now.

## 10\. Use the Web Version

 Microsoft even offers a [web version of Visual Studio Code](https://vscode.dev/) which you can use as a temporary solution. You can sign in to the web version and sync your files and settings. Moreover, you can install a PWA from the browser of Visual Studio Code and launch it directly from your desktop.

## Visual Studio Code Won’t Crash Anymore on Windows 11

 Microsoft’s popular IDE is the go-to tool of programmers. If its crashes abruptly, the projects can get delayed by quite a bit. Start with basic troubleshooting and then disable hardware acceleration on your system. After that, disable extensions and perform a clean boot. Add an exclusion for the app in the antivirus program. Lastly, if nothing works, reinstall the Visual Studio Code app on your system.


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
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-lock-your-poco-f5-5g-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>In 2024, Lock Your Poco F5 5G Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-speed-up-and-conclude-your-puzzled-updates/"><u>How to Speed Up and Conclude Your Puzzled Updates</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-ultimate-guide-cost-effective-pc-screen-recording-apps/"><u>[New] Ultimate Guide  Cost-Effective PC Screen Recording Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-activate-hyper-v-in-the-latest-windows-os/"><u>How To Activate Hyper-V in the Latest Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-winxps-notorious-error-0x80300024/"><u>Fixing WinXP's Notorious Error 0X80300024</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-snipping-tool-keyboard-failures-on-pc/"><u>Fixing Snipping Tool Keyboard Failures on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-to-address-windows-network-not-found/"><u>Solutions to Address Windows Network Not Found</u></a></li>
<li><a href="https://windows11.techidaily.com/premier-windows-tools-through-vivetools-advanced-features/"><u>Premier Windows Tools Through ViVeTool's Advanced Features</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11-calendar-easily/"><u>Navigating Windows 11 Calendar Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/secretive-startup-strategies-conceal-the-shutdown-command/"><u>Secretive Startup Strategies: Conceal the Shutdown Command</u></a></li>
<li><a href="https://windows11.techidaily.com/personalize-your-pc-a-guide-to-alomwares-control-options/"><u>Personalize Your PC: A Guide to AlomWare's Control Options</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-file-explorer-crashes-in-newest-windows-11/"><u>Quick Fixes for File Explorer Crashes in Newest Windows 11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-syncing-your-soundtrack-import-music-into-inshot/"><u>2024 Approved  Syncing Your Soundtrack  Import Music Into InShot</u></a></li>
<li><a href="https://windows11.techidaily.com/reigniting-your-calendars-and-mailboxes-w11-edition/"><u>Reigniting Your Calendars and Mailboxes: W11 Edition</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-2024-approved-overcoming-saturation-marketing-yourself-above-top-tiktoks/"><u>[New] 2024 Approved  Overcoming Saturation  Marketing Yourself Above Top TikToks</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-precision-best-keyboard-cars-for-windows/"><u>Quick Precision: Best Keyboard Cars for Windows</u></a></li>
<li><a href="https://techidaily.com/is-your-motorola-moto-g34-5g-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Motorola Moto G34 5G working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/disentangling-compact-icons-on-desktop-shelf/"><u>Disentangling Compact Icons on Desktop Shelf</u></a></li>
<li><a href="https://windows11.techidaily.com/precision-installation-microsoft-works-for-modern-windows/"><u>Precision Installation: Microsoft Works for Modern Windows</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-tech-titans-triumph-best-online-tools-to-record-your-screen-for-2024/"><u>[Updated] Tech Titans Triumph  Best Online Tools to Record Your Screen for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/all-about-factory-reset-what-is-it-and-what-it-does-to-your-realme-narzo-n55-drfone-by-drfone-reset-android-reset-android/"><u>All About Factory Reset, What Is It and What It Does to Your Realme Narzo N55? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-app-instance-identifiers-and-practices/"><u>Exploring App Instance Identifiers and Practices</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-image-proportion-perfection-a-detailed-tutorial-on-calculating-ratios-for-2024/"><u>Updated Image Proportion Perfection A Detailed Tutorial on Calculating Ratios for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-graceful-gallops-on-frozen-ground/"><u>In 2024, Graceful Gallops on Frozen Ground</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-advanced-scripts-engineering-countdown-timers-in-broadcast-tools/"><u>[Updated] 2024 Approved  Advanced Scripts  Engineering Countdown Timers in Broadcast Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/browser-bugs-and-breakages-fixing-website-issues-on-your-windows-pc/"><u>Browser Bugs & Breakages: Fixing Website Issues on Your Window's PC</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-bring-your-text-to-life-techniques-for-3d-design-in-ps/"><u>[New] 2024 Approved  Bring Your Text to Life  Techniques for 3D Design in PS</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-rectify-winscomrssvdll-errors-in-windows-os/"><u>How to Rectify WinscomrssvDLL Errors in Windows OS</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-access-tons-of-free-vocal-textures/"><u>2024 Approved  Access Tons of Free Vocal Textures</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-unauthorized-geforce-setting-error-on-modern-windows-versions/"><u>Fixing Unauthorized GeForce Setting Error on Modern Windows Versions</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-overcome-java-vm-not-found-on-pc/"><u>How to Overcome Java VM Not Found On PC</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-engaging-creativity-crafting-compelling-facebook-ads-for-2024/"><u>[Updated] Engaging Creativity  Crafting Compelling Facebook Ads for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-preventing-latency-when-linking-two-monitors/"><u>Guide to Preventing Latency When Linking Two Monitors</u></a></li>
<li><a href="https://windows11.techidaily.com/get-immediate-access-to-assistive-features-in-windows/"><u>Get Immediate Access to Assistive Features in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/easing-through-policy-restrictions-in-admin-blocked-installations/"><u>Easing Through Policy Restrictions in Admin-Blocked Installations</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-issues-with-the-epic-games-launcher-for-win-users/"><u>Preventing Issues with the Epic Games Launcher for Win Users</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-memory-write-error-windows-fixes/"><u>Disabling 'Memory Write' Error: Windows Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-edge-solutions-exclusive-windows-systems-for-dsswitch-players/"><u>Cutting-Edge Solutions: Exclusive Windows Systems for DS/Switch Players</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-guffaw-guild-robotic-raiders/"><u>[Updated] Guffaw Guild  Robotic Raiders</u></a></li>
<li><a href="https://windows11.techidaily.com/overcome-stubborn-windows-terminals-a-step-by-step-guide/"><u>Overcome Stubborn Windows Terminals: A Step-by-Step Guide</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/the-art-of-story-lensing-smart-zooms-on-instagram/"><u>The Art of Story Lensing  Smart Zooms on Instagram</u></a></li>
<li><a href="https://windows11.techidaily.com/decluttering-your-win11-desktop-wallpaper-symbol/"><u>Decluttering Your Win11 Desktop Wallpaper Symbol</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-elevate-your-content-with-these-20-pro-video-shortcuts/"><u>[Updated] 2024 Approved  Elevate Your Content With These 20 Pro Video Shortcuts</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-0x80072efd-microsoft-store-error-in-windows-11-and-windows-10/"><u>How to Fix the 0X80072EFD Microsoft Store Error in Windows 11 and Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-sound-for-windows-screencasts-with-powerpoint/"><u>Enabling Sound for Windows Screencasts with PowerPoint</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-from-infinix-note-30-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock from Infinix Note 30 Phones with/without a PC</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/eco-conscious-screen-tech-guide/"><u>Eco-Conscious Screen Tech Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/from-separate-to-shared-android-pc-harmony-guide/"><u>From Separate to Shared: Android-PC Harmony Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-install-android-apks-with-a-double-click-in-windows-11/"><u>How to Install Android APKs With a Double-Click in Windows 11</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-free-adobe-premiere-pro-cs6-for-mac-download-latest-2023-release-for-2024/"><u>Updated Free Adobe Premiere Pro CS6 for Mac Download Latest 2023 Release for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-the-incompatible-gpu-mystery-wins11-and-win10-edition/"><u>Demystifying the Incompatible GPU Mystery: Wins11 & Win10 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-snipkey-issues-resetting-windows-keys/"><u>Solving SnipKey Issues: Resetting Windows Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/curb-high-gpu-demand-with-proven-fixes-for-wm-on-windows/"><u>Curb High GPU Demand with Proven Fixes for WM on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-your-experience-best-practices-for-reading-qr-codes-in-windows/"><u>Optimizing Your Experience: Best Practices for Reading QR Codes in Windows</u></a></li>
</ul></div>
