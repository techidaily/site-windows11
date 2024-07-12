---
title: Guide to Reinstalling Favorite Apps on New Windows 11 Devices
date: 2024-07-11T21:28:43.490Z
updated: 2024-07-12T21:28:43.490Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Reinstalling Favorite Apps on New Windows 11 Devices
excerpt: This Article Describes Guide to Reinstalling Favorite Apps on New Windows 11 Devices
keywords: Win11 App Reinstall Guide,FavApps Restore Windows 11,Windows 11 Update Procedures,NewOS App Setup Tips,Freshly Installed OS Apps,Revive Old Windows Apps,Optimize Win11 App Install
thumbnail: https://thmb.techidaily.com/829f3e424c1b3b1991d559a20a197c8257f098aee3dfffc59a2e2d3ad659a88e.jpg
---

## Guide to Reinstalling Favorite Apps on New Windows 11 Devices

 Setting up Windows 11 on your PC, or another PC is a laborious task. After installing the operating system and the OEM drivers, there is still a lot of work left. You need to reconfigure your system settings, re-download, and install all the Microsoft Store apps. Along with that, you need to individually download and install each third-party software, which makes it more challenging.

 But what if you could eliminate the hours spent in finding and installing every single app, and configuring every setting? We will discuss two methods to effortlessly migrate most of your old apps to your new PC.

## 1\. Using Microsoft Account

 If you used a Microsoft account on your old PC, Windows 11 offers multiple options to back up your App list, Preferences, and use OneDrive for personal files. To do that, you must enable [OneDrive](https://www.makeuseof.com/what-is-onedrive/) and back up all your personal files and folders to it. It will only take care of the files part but the apps and preferences are still left. But you must also enable the backup of these two things on your old PC before [reinstalling Windows 11](https://www.makeuseof.com/windows-11-reinstall-without-deleting-apps/) or migrating to a new PC.

 Repeat the following steps to enable apps and settings backup:

1. Press **Win + I** to launch the Settings app. Navigate to **Accounts > Windows backup** section.
2. Go to the **Remember my apps** option and click on the toggle next to it to enable the settings.
3. Next, click on the toggle next to **Remember my preferences** option to back up your settings as well.  
![Backup Apps and Preferences to Microsoft Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/backup-apps-and-preferences-to-microsoft-account.jpg)
4. You will notice that the top section of the Windows backup page will mark each of these features as “**backed up**”.

 After you reinstall Windows 11, the OOBE page will ask you to [sign in with a Microsoft account](https://www.makeuseof.com/windows-switch-local-account-to-microsoft-account/). Enter your credentials, and you will see a “Welcome back, User!” message with an option to restore all apps, settings, and files present on your previous machine. Click on the **Next** button and proceed setup up your new PC

![Install Old Apps Using Microsoft Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-old-apps-using-microsoft-account.jpg)

 As soon as you boot to the desktop, you will see a popup that Windows is trying to restore the most used apps from before. It will ask you to open Microsoft Store to restore additional apps from your old PC. Click on the **Restore my apps** button.

![Install Old Apps Using Microsoft Account 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-old-apps-using-microsoft-account-2.jpg)

 Microsoft Store will display all the remaining apps available for restoration. Click on the **Restore All** button if you want to bring back every app. Wait for the apps to install and then close Microsoft Store.

![Install Old Apps Using Microsoft Account 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-old-apps-using-microsoft-account-3.jpg)

## 2\. Using a Winget JSON File

 The first method of using Microsoft Account has its limitations. It only includes Windows apps and settings but leaves many other third-party apps that you installed from the Winget repository or from the web. So you can use Winget to export the app list into a JSON file and then import it to your new Windows 11 PC. You must execute this method after Windows 11 brings back all the settings and Microsoft apps, and you boot to the desktop.

 Repeat the following steps to import a Winget JSON file:

1. Download or copy the Winget export file on your system.
2. Press **Win + R** to open the **Run dialog box**. Type **cmd** and press **Ctrl + Shift + Enter** to [open Command Prompt with administrator privileges](https://www.makeuseof.com/how-to-always-open-command-prompt-as-administrator-windows/).
3. Now, use the **winget import -i** command to import the JSON file. Type the following command and press the **Enter** key:  
`winget import -i C:\apps.json --accept-source-agreements --accept-package-agreements`
4. Replace the folder location and name with the storage location and name of the winget export file on your system.  
![Import Apps Using Winget in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/import-apps-using-winget-in-windows-11.jpg)
5. Patiently wait while winget downloads and installs all the packages in the JSON file one by one. Then, close the Command Prompt window.

## What About Any Left Out Apps?

 Even after using both methods, some apps will still be left out. It is because Microsoft Account sign-in only brings back Windows settings and Microsoft Store apps. The winget export file can restore only the apps listed in its official repository.

 As such, you still need to download the programs that aren’t included in both of these methods. But it will be a very short list compared to the effort you would have to put in if you just performed a normal installation.

## Save Time When Setting Up Windows 11

 Make sure to enable files, apps, and preferences backup on your PC and create a winget export file beforehand. After you have both these backups in place, you can begin reinstalling Windows 11 on a different PC or reinstalling on the same PC.

 But what if you could eliminate the hours spent in finding and installing every single app, and configuring every setting? We will discuss two methods to effortlessly migrate most of your old apps to your new PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-lab.techidaily.com/ed-building-awesome-channel-art-for-your-youtube-presence/"><u>[Updated] Building Awesome Channel Art for Your YouTube Presence</u></a></li>
<li><a href="https://windows11.techidaily.com/quash-insufficient-requirement-notice-windows-11/"><u>Quash Insufficient Requirement Notice Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tech-enthusiasts-rejoice-black-friday-offer-for-lifetime-612-windows-11-savings/"><u>Tech Enthusiasts Rejoice - Black Friday Offer for Lifetime $6.12 Windows 11 Savings</u></a></li>
<li><a href="https://youtube-web.techidaily.com/024-approved-from-eyeballs-to-earnings-the-price-of-popular-videos/"><u>[New] 2024 Approved  From Eyeballs to Earnings  The Price of Popular Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/curing-stale-boot-option-imagery/"><u>Curing Stale BOOT Option Imagery</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-redesign-instant-twitter-video-view/"><u>2024 Approved  Redesign Instant Twitter Video View</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-solution-for-inaccessible-administrative-mode/"><u>Comprehensive Solution for Inaccessible Administrative Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-windows-videography-leverage-advanced-distributive-transcoding-by-tdarr/"><u>Enhance Window's Videography: Leverage Advanced Distributive Transcoding by Tdarr</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-unleash-creative-potential-for-video-editing-in-windows-photos/"><u>2024 Approved  Unleash Creative Potential for Video Editing in Windows Photos</u></a></li>
<li><a href="https://windows11.techidaily.com/dispatching-windows-11s-silent-search-instigator/"><u>Dispatching Windows 11'S Silent Search Instigator</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-restore-fn-key-brighness-in-windows-11/"><u>Steps to Restore Fn Key Brighness in Windows 11</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/he-complete-guide-to-assembling-youtube-music-collections-onlineapp-wise/"><u>[New] The Complete Guide to Assembling YouTube Music Collections Online/App-Wise</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-the-ultimate-guide-to-youtubes-best-music-responses/"><u>2024 Approved  The Ultimate Guide to YouTube's Best Music Responses</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-4-ways-to-trace-realme-12-5g-location-drfone-by-drfone-virtual-android/"><u>In 2024, Top 4 Ways to Trace Realme 12 5G Location | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-network-path-with-fixed-ea-server-error-in-os/"><u>Restoring Network Path with Fixed EA Server Error in OS</u></a></li>
<li><a href="https://windows11.techidaily.com/voice-your-ideas-type-them-out-with-openais-whisper/"><u>Voice Your Ideas, Type Them Out With OpenAI’s Whisper</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-streamlining-your-workflow-our-selection-of-the-6-best-automatic-transcription-programs-for-2024/"><u>New Streamlining Your Workflow Our Selection of the 6 Best Automatic Transcription Programs for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-fixing-steam-file-connections-issue/"><u>Strategies for Fixing Steam File Connections Issue</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-inside-look-tunefabs-best-screen-recorder/"><u>In 2024, Inside Look  Tunefab's Best Screen Recorder</u></a></li>
<li><a href="https://windows11.techidaily.com/the-best-way-to-setup-games-on-the-windows-xbox-app/"><u>The Best Way to Setup Games on the Windows Xbox App</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-system-crashes-sifting-through-win-files/"><u>Deciphering System Crashes: Sifting Through Win Files</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-productivity-choosing-terminal-as-primary-command-line-interface/"><u>Enhancing Productivity: Choosing Terminal as Primary Command Line Interface</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/grasping-the-intricacies-of-russian-sounds/"><u>Grasping the Intricacies of Russian Sounds</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-to-github-desktop-with-windows-11-os/"><u>Step-by-Step Guide to GitHub Desktop with Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-win11-taskbar-icon-dimensions/"><u>Adjusting Win11 Taskbar Icon Dimensions</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-steps-delete-email-after-signing-in/"><u>Troubleshooting Steps: Delete Email After Signing In</u></a></li>
<li><a href="https://windows11.techidaily.com/quickly-fixing-microsoft-store-problems-on-win-11/"><u>Quickly Fixing Microsoft Store Problems on Win 11</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-ice-cream-capture-gadget-detailed-examination/"><u>[Updated] Ice Cream Capture Gadget Detailed Examination</u></a></li>
<li><a href="https://windows11.techidaily.com/taking-flight-with-windows-accessibility-novice-style/"><u>Taking Flight with Windows Accessibility, Novice Style</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/2024-approved-the-top-english-voice-generator-to-convert-text-into-desired-accent/"><u>2024 Approved The Top English Voice Generator To Convert Text Into Desired Accent</u></a></li>
<li><a href="https://windows11.techidaily.com/battle-of-the-packagers-chocolatey-or-wm-on-windows-pcs/"><u>Battle of the Packagers: Chocolatey or WM on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-counteract-d3d11-hardware-failures-in-w11w10/"><u>Strategies to Counteract D3D11 Hardware Failures in W11/W10</u></a></li>
<li><a href="https://windows11.techidaily.com/correction-of-microsoft-store-error-0x80073cf3-on-windows-11/"><u>Correction of Microsoft Store Error 0X80073cf3 on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-error-windows-welcome-cant-read-fingers/"><u>Tackling Error: Windows Welcome Can't Read Fingers</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-screen-disruptions-secure-smooth-play-on-w11-with-sonic-frontiers/"><u>Overcoming Screen Disruptions: Secure Smooth Play on W11 with Sonic Frontiers</u></a></li>
<li><a href="https://windows11.techidaily.com/the-top-9-truths-about-why-pc-computers-win-over-macos-9/"><u>The Top 9 Truths About Why PC Computers Win over MacOS (#9)</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-windows-11-screens-with-custom-wallpaper-panes/"><u>Transform Windows 11 Screens with Custom Wallpaper Panes</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-the-endless-void-fixing-xbox-app-errors-in-win11/"><u>Avoiding the Endless Void: Fixing Xbox App Errors in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-your-smartphone-writescreen-functionality-for-windows-11/"><u>Unlocking Your Smartphone' Writescreen Functionality for Windows 11</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/the-ultimate-list-of-global-tiktok-titans/"><u>The Ultimate List of Global TikTok Titans</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-excessive-ram-allocation-in-connected-devices-interface/"><u>Resolving Excessive RAM Allocation in Connected Devices Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-reclaiming-standard-windows-11-search-preferences/"><u>Step-by-Step: Reclaiming Standard Windows 11 Search Preferences</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-transition-tips-seamlessly-moving-to-macos-sierra/"><u>[New] Transition Tips  Seamlessly Moving to MacOS Sierra</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-optimal-sleep-cycles-for-windows-devices/"><u>Unlocking Optimal Sleep Cycles for Windows Devices</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-guide-to-quick-video-recording-on-youtube/"><u>2024 Approved  Guide to Quick Video Recording on YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/personalize-your-windows-dashboard-incorporate-portable-apps/"><u>Personalize Your Windows Dashboard: Incorporate Portable Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-the-walls-of-windows-icons/"><u>Taming the Walls of Windows Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11-internet-options/"><u>Unlocking Windows 11 Internet Options</u></a></li>
<li><a href="https://windows11.techidaily.com/curb-intrusive-windows-scrolling-for-smooth-screens/"><u>Curb Intrusive Windows Scrolling for Smooth Screens</u></a></li>
<li><a href="https://windows11.techidaily.com/curing-grayed-screen-savers-quick-fixes-for-windows-users/"><u>Curing Grayed Screen Savers: Quick Fixes for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-techniques-finding-out-charge-status-win-1011/"><u>Advanced Techniques: Finding Out Charge Status (Win 10/11)</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/ultimate-guide-on-xiaomi-redmi-12-5g-frp-bypass-by-drfone-android/"><u>Ultimate Guide on Xiaomi Redmi 12 5G FRP Bypass</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-the-impact-of-ntfs-compression-on-data-saving/"><u>Understanding the Impact of NTFS Compression on Data Saving</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-streamlined-strategies-mastering-screen-record-on-an-hp-notebook/"><u>[Updated] In 2024, Streamlined Strategies  Mastering Screen Record on an HP Notebook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-power-settings-fully-charged-notifications-for-win11/"><u>Navigating Power Settings: Fully Charged Notifications for Win11</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-in-2024-the-complete-checklist-for-youtube-production-gear/"><u>[Updated] In 2024, The Complete Checklist for YouTube Production Gear</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-application-startup-hexadecimal-issue-error/"><u>Unraveling The Application Startup Hexadecimal Issue (Error)</u></a></li>
</ul></div>
