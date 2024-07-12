---
title: How to Transfer Apps to a New Windows 11 PC
date: 2024-07-11T22:07:54.904Z
updated: 2024-07-12T22:07:54.904Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Transfer Apps to a New Windows 11 PC
excerpt: This Article Describes How to Transfer Apps to a New Windows 11 PC
keywords: Windows 11 App Transfer Guide,Moving Apps in Windows 11,Install Apps on Windows 11,Apps Migration to Windows 11 PC,Transferring Apps New Windows Laptop,Setting up Windows 11 with Apps,New PC App Setup Windows 11
thumbnail: https://thmb.techidaily.com/3a3db1628b8f2814d2040ecfe00634d164ea4b5f3058a85b825026993cb96502.jpg
---

## How to Transfer Apps to a New Windows 11 PC

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
<li><a href="https://windows11.techidaily.com/accessing-and-running-verifier-manager-in-windows-11/"><u>Accessing and Running Verifier Manager in Windows 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-overview-of-the-best-vivo-v29-screen-mirroring-app-drfone-by-drfone-android/"><u>In 2024, Overview of the Best Vivo V29 Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-print-speed-on-pcs-tips-for-windows-users/"><u>Boosting Print Speed on PCs: Tips for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-low-end-specs-for-effective-game-capture/"><u>Bypassing Low-End Specs for Effective Game Capture</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-back-sound-on-systems-running-low-volume-errors/"><u>Bring Back Sound on Systems Running Low Volume Errors</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-apple-id-unlock-from-apple-iphone-11-pro-max-how-to-fix-it-by-drfone-ios/"><u>In 2024, Apple ID Unlock From Apple iPhone 11 Pro Max? How to Fix it?</u></a></li>
<li><a href="https://windows11.techidaily.com/browser-breakdowns-heres-how-to-get-past-the-roadblocks-in-win-os/"><u>Browser Breakdowns? Here's How to Get Past the Roadblocks in WIN OS</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-lag-pro-level-valorant-fps-strategies/"><u>Avoiding Lag: Pro-Level Valorant FPS Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/7-reasons-to-choose-windows-10-over-windows-11/"><u>7 Reasons to Choose Windows 10 Over Windows 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/beatboxing-basics-add-audio-to-windows-11-projects-with-ease/"><u>Beatboxing Basics  Add Audio to Windows 11 Projects with Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/5-ways-to-fix-the-remote-procedure-call-failed-error-in-windows/"><u>5 Ways to Fix the Remote Procedure Call Failed Error in Windows</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-2024-approved-premier-general-knowledge-trivia-hubs/"><u>[New] 2024 Approved  Premier General Knowledge Trivia Hubs</u></a></li>
<li><a href="https://windows11.techidaily.com/bridging-gaps-quick-fixes-for-microsoft-to-do-discrepancies/"><u>Bridging Gaps: Quick Fixes for Microsoft To Do Discrepancies</u></a></li>
<li><a href="https://windows11.techidaily.com/a-practical-guide-to-creating-and-managing-a-win-11-hotspot/"><u>A Practical Guide to Creating and Managing a Win 11 Hotspot</u></a></li>
<li><a href="https://windows11.techidaily.com/brighten-up-windows-11-screens-with-easy-adjustments/"><u>Brighten Up Windows 11 Screens with Easy Adjustments!</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-original-design-potential-utilize-free-logo-templates-and-customization-tools/"><u>2024 Approved  Original Design Potential  Utilize FREE Logo Templates & Customization Tools</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-streamline-sharing-process-youtube-to-facebook-tips-for-2024/"><u>[Updated] Streamline Sharing Process  YouTube to Facebook Tips for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-xbox-game-pass-failure-the-0x800700e9-factor/"><u>Addressing Xbox Game Pass Failure: The 0X800700E9 Factor</u></a></li>
<li><a href="https://windows11.techidaily.com/biggest-discounts-black-friday-612-windows-10-forever/"><u>Biggest Discounts: Black Friday - $6.12, Windows 10 Forever</u></a></li>
<li><a href="https://windows11.techidaily.com/breached-byte-bastion-maintain-reflect-then-switch/"><u>Breached Byte Bastion: Maintain, Reflect, Then Switch</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-photo-snapshots-in-windows-11/"><u>Adjusting Photo Snapshots in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-update-four-techniques/"><u>Bypassing Windows Update: Four Techniques</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-exploring-the-best-audio-blending-software-top-picks-free-of-charge-in-2024/"><u>New Exploring the Best Audio Blending Software - Top Picks , Free of Charge, In 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/cant-open-the-credential-manager-on-windows-try-these-fixes/"><u>Can’t Open the Credential Manager on Windows? Try These Fixes</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-perfect-your-recordings-the-ultimate-guide-to-adobe-presenter/"><u>[Updated] In 2024, Perfect Your Recordings  The Ultimate Guide to Adobe Presenter</u></a></li>
<li><a href="https://windows11.techidaily.com/bluescreenview-explained-for-everyday-users/"><u>BlueScreenView Explained for Everyday Users</u></a></li>
<li><a href="https://windows11.techidaily.com/a-simple-way-to-inspect-and-erase-window-logs/"><u>A Simple Way to Inspect & Erase Window Logs</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-understanding-your-absence-on-snapchat/"><u>2024 Approved  Understanding Your Absence on Snapchat</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-loss-the-top-8-windows-recovery-tips/"><u>Avoiding Loss: The Top 8 Windows Recovery Tips</u></a></li>
<li><a href="https://howto.techidaily.com/play-store-not-working-on-oneplus-nord-ce-3-5g-8-solutions-inside-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Not Working On OnePlus Nord CE 3 5G? 8 Solutions Inside | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-black-backgrounds-on-your-windows-pc/"><u>Bypassing Black Backgrounds on Your Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-peak-performance-self-update-system-with-new-amd-drivers/"><u>Achieve Peak Performance: Self-Update System with New AMD Drivers</u></a></li>
<li><a href="https://windows11.techidaily.com/clarifying-the-concept-of-windows-ram-caching/"><u>Clarifying the Concept of Window's RAM Caching</u></a></li>
<li><a href="https://windows11.techidaily.com/arrow-keys-in-distress-heres-what-you-can-do/"><u>Arrow Keys in Distress? Here's What You Can Do</u></a></li>
<li><a href="https://windows11.techidaily.com/advance-windows-11-task-manager-refresh-speeds/"><u>Advance Windows 11 Task Manager Refresh Speeds</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-settings-for-smooth-run-as-functionality/"><u>Adjusting Settings for Smooth 'Run As' Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-productivity-with-these-5-essential-windows-folder-practices/"><u>Boost Productivity with These 5 Essential Windows Folder Practices</u></a></li>
</ul></div>
