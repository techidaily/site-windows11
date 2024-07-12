---
title: "Configuring Terminal in Win11: Start Fresh"
date: 2024-07-11T22:27:18.090Z
updated: 2024-07-12T22:27:18.090Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Configuring Terminal in Win11: Start Fresh"
excerpt: "This Article Describes Configuring Terminal in Win11: Start Fresh"
keywords: Windows Terminal Setup Guide,Win11 Terminal Configuration,Fresh Win11 Terminal Start,Revamping Terminal in Win11,New Terminal Setup Win11,Initializing Win11 Terminal,Win11 Terminal Freshness
thumbnail: https://thmb.techidaily.com/474c5054a0eaa723712bc3725331bacf73663ebfef0031bd8bc1879804e39c8f.jpg
---

## Configuring Terminal in Win11: Start Fresh

 Windows Terminal is the next-generation command line platform in Windows 11\. It provides an improved user experience with modern command line tools that enable you to access multiple command lines in a single window. The tool is essential for developers and administrators alike, but sometimes your terminal settings need to be reset to default.

 In this article, we will explain how to reset your Windows Terminal settings back to their original state.

## Why Would You Reset Your Windows Terminal?

 Windows Terminal is an amazing tool for power users and developers. It allows you to access a variety of tools, all in one place, with custom settings and themes that make it easy to work from anywhere. But over time, your Windows Terminal may become cluttered with old settings or themes that have become redundant or are no longer relevant.

 It also helps clear out any potentially harmful malware or corrupt files that might be lurking in the background of your system, hindering your productivity. By doing so, you will ensure that your computer works as fast and as smoothly as possible - giving you the most optimal experience when using this powerful tool.

 Let's now move to the below sections and see how it can be reset.

## How to Reset Windows Terminal Settings by Clearing JSON Files

 In order to reset the settings back to the original defaults, you will need to delete the settings.json file. Here's how to do it.

1. Right click on Start and select**Terminal** from the menu list.
2. Next, click the down-arrow icon and select**Settings** .
3. From the left pane of the Settings page, click**Open JSON file** .  
![Open JSON file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-json-file.jpg)
4. If you're asked which app to use to open the file, then double-click on**Notepad** .
5. On the next page, select all the contents and**Delete** them.
6. Now press**Ctrl + S** on your keyboard to save it.

 Next time you open the app, a new configuration with all the default settings will be created automatically.

## How to Reset Windows Terminal Settings Using Command Prompt

 The Command Prompt is a command line tool that can help you accomplish a number of tasks on your computer. It lets you run programs, manage files, and even troubleshoot problems with the operating system. We covered a lot of its functionality in our [beginner's guide to the Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) , but for now, we'll just explore resetting the Windows Terminal settings.

 To reset Windows Terminal Settings back to their defaults, follow these steps:

1. Open the Command Prompt. For this, use the Taskbar search or type "cmd" in the Run dialog.
2. In the Command Prompt window, copy and paste the following command:  
![Reset Windows Terminal Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-command-prompt.jpg)  
del /f /s /q /a "%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json"
3. Now press the**Enter** key to delete the settings.json file.
4. You can now exit the command prompt.

## How to Reset Windows Terminal Settings Using Windows PowerShell

 Windows PowerShell is another command line application that you can use to restore Windows Terminal Settings to their default state. To figure out how, follow these steps:

1. Open Windows PowerShell. You can do this by pressing**Win + R** , typing "PowerShell", and then pressing**Enter** . You can also one of the other [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
2. In the PowerShell window, copy and paste the following command:  
![Reset Windows Terminal Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-powershell.jpg)  
Remove-Item -Path "$env:LOCALAPPDATA\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json" -Force
3. Press**Enter** to execute the command.

## How to Reset Windows Terminal Settings From File Explorer

 If you don't prefer the command line process, you can use Windows File Explorer to reset the settings. In this way, the Terminal will be reset to its default settings, and you can continue using it. Here's how to do it:

1. Open Windows File Explorer. For this, right-click Start and choose**File Explorer** , or press**Win + E** on your keyboard.
2. Copy and paste the following path into the address bar:  
![Reset Windows Terminal Using File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-file-explorer.jpg)  
%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState
3. On the next page, right-click on**settings.json** and select**Delete** from the context menu.

 Once you perform the above steps, Settings.json will automatically be created with the default settings.

## Resetting the Windows Terminal, Made Easy

 After reading this post, you now know some useful tips that will help you reset the terminal to default settings in Windows 11\. Try them out and find out which one works best for you.


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
<li><a href="https://windows11.techidaily.com/cryptographic-concealment-stashing-zip-files-undetected-on-windows-pcs/"><u>Cryptographic Concealment: Stashing Zip Files Undetected on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-windows-java-installation-roadblocks/"><u>Clearing Windows Java Installation Roadblocks</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-for-people-wanting-to-mock-gps-on-motorola-moto-g-stylus-2023-devices-drfone-by-drfone-virtual/"><u>In 2024, For People Wanting to Mock GPS on Motorola Moto G Stylus (2023) Devices | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/concealing-the-taskbar-written-words-in-windows-11-ui/"><u>Concealing the Taskbar’ Written Words in Windows 11 UI</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-tutorial-onedrive-plus-microsoft-login-on-pc/"><u>Comprehensive Tutorial: OneDrive + Microsoft Login on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-unique-room-backgrounds-with-windows-spotlight-pics/"><u>Crafting Unique Room Backgrounds with Windows Spotlight Pics</u></a></li>
<li><a href="https://windows11.techidaily.com/classic-revival-atlasos-for-outdated-pcs/"><u>Classic Revival: AtlasOS for Outdated PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-internal-audio-issues-with-audacity-windows-11/"><u>Correcting Internal Audio Issues with Audacity (Windows 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/conveniently-embedding-passwords-into-windows-text-archives/"><u>Conveniently Embedding Passwords Into Windows Text Archives</u></a></li>
<li><a href="https://windows11.techidaily.com/contrasting-the-workflow-of-cloud-based-and-disk-installed-windows-oses/"><u>Contrasting the Workflow of Cloud-Based & Disk Installed Windows OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/complete-approach-to-deleting-the-wsl-subsystem/"><u>Complete Approach to Deleting the WSL Subsystem</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-snapchat-to-smiles-phones-for-2024/"><u>[New] Snapchat to Smiles  Phones for 2024</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/2024-approved-cutting-edge-window-sound-solutions-top-picks-for-background-noise-eviction-from-recordings/"><u>2024 Approved Cutting Edge Window Sound Solutions Top Picks for Background Noise Eviction From Recordings</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-success-in-playing-ps1-games-on-win-with-duckstations-tips/"><u>Deciphering Success in Playing PS1 Games on WIN with Duckstation’s Tips</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-use-google-assistant-on-your-lock-screen-of-nokia-c210-phone-by-drfone-android/"><u>How to Use Google Assistant on Your Lock Screen Of Nokia C210 Phone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-in-depth-guide-obs-for-gamers/"><u>[New] 2024 Approved  In-Depth Guide  OBS for Gamers</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-reset-gmail-password-on-realme-note-50-devices-by-drfone-android/"><u>How to Reset Gmail Password on Realme Note 50 Devices</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-hunting-for-genuine-creature-roar-ambience-for-2024/"><u>New Hunting for Genuine Creature Roar Ambience for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-microsoft-store-failure-codes-x800704cf/"><u>Disabling Microsoft Store Failure Codes X800704CF</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/in-2024-transform-your-audio-into-visually-stunning-videos-online/"><u>In 2024, Transform Your Audio Into Visually Stunning Videos Online</u></a></li>
<li><a href="https://windows11.techidaily.com/direct-guide-to-reactivate-print-spool/"><u>Direct Guide to Reactivate Print Spool</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-best-biz-youtubes-top-10-for-quick-channel-setup/"><u>[New] Best Biz YouTubes  Top 10 for Quick Channel Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/compact-windows-powered-systems-unveiled/"><u>Compact Windows-Powered Systems Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/convenient-quick-settings-navigating-win-11-interface/"><u>Convenient Quick Settings: Navigating Win 11 Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-unique-applications-the-best-10-uses-for-powertoys/"><u>Discover Unique Applications: The Best 10 Uses for PowerToys</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-quest-for-immersion-reviewing-benqs-ultra-hd-sw320/"><u>In 2024, The Quest for Immersion  Reviewing BenQ's Ultra HD SW320</u></a></li>
<li><a href="https://windows11.techidaily.com/distinguishing-key-features-of-exe-and-msi-formats/"><u>Distinguishing Key Features of EXE and MSI Formats</u></a></li>
<li><a href="https://windows11.techidaily.com/craft-an-individualized-look-for-your-schedule-in-windows-outlook/"><u>Craft an Individualized Look for Your Schedule in Windows Outlook</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/reasons-why-pokemon-gps-does-not-work-on-tecno-spark-go-2023-drfone-by-drfone-virtual-android/"><u>Reasons why Pokémon GPS does not Work On Tecno Spark Go (2023)? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/direct-route-out-of-windows-11s-protective-barrier/"><u>Direct Route Out of Windows 11'S Protective Barrier</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/in-2024-best-ways-to-blur-zoom-background-for-free/"><u>In 2024, Best Ways to Blur Zoom Background for Free</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-virtual-vigilance-securing-your-cyber-space-while-connecting-online/"><u>New 2024 Approved Virtual Vigilance Securing Your Cyber Space While Connecting Online</u></a></li>
<li><a href="https://windows11.techidaily.com/dive-into-digital-canvases-the-best-7-apps-for-win10-artists/"><u>Dive Into Digital Canvases: The Best 7 Apps for Win10 Artists</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-winos-gain-control-over-applications-browsing/"><u>Decoding WinOS: Gain Control over Applications, Browsing</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-stepwise-voice-transformation-techniques-for-tiktokers-for-2024/"><u>[Updated] Stepwise Voice Transformation Techniques for TikTokers for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-correcting-windows-error-0x8007021/"><u>Decoding and Correcting Windows Error 0X8007021</u></a></li>
<li><a href="https://windows11.techidaily.com/crucial-cross-platform-tools-for-windowsandroid-users/"><u>Crucial Cross-Platform Tools For Windows/Android Users</u></a></li>
<li><a href="https://windows11.techidaily.com/cracking-the-code-unlocking-mac-locations-in-windows-11/"><u>Cracking the Code: Unlocking MAC Locations in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-failed-uploads-with-onedrive-in-w11/"><u>Correcting Failed Uploads with OneDrive in W11</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/2024-approved-professional-grade-animation-top-software-for-macwindows-creatives/"><u>2024 Approved Professional-Grade Animation Top Software for Mac/Windows Creatives</u></a></li>
<li><a href="https://windows11.techidaily.com/compelling-windows-applications-for-video-transformation/"><u>Compelling Windows Applications for Video Transformation</u></a></li>
<li><a href="https://windows11.techidaily.com/display-number-and-caps-lock-status-in-taskbar-tray-win11/"><u>Display Number and Caps Lock Status in Taskbar Tray Win11</u></a></li>
</ul></div>
