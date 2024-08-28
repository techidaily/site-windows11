---
title: Mastering App Migration to Your New Windows 11 Laptop
date: 2024-08-27T16:05:20.483Z
updated: 2024-08-28T16:05:20.483Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering App Migration to Your New Windows 11 Laptop
excerpt: This Article Describes Mastering App Migration to Your New Windows 11 Laptop
keywords: Win11 Laptop Setup,Transfer Data Quickly,Optimize Windows 11,Easy App Migration,Laptop Upgrade Seo,New OS Integration,Tech Transition Guide
thumbnail: https://thmb.techidaily.com/d599dad7b998abdf06ca417d32becc28547b33f181303fc426d96b899acd4e4b.jpg
---

## Mastering App Migration to Your New Windows 11 Laptop

 Setting up Windows 11 on your PC, or another PC is a laborious task. After installing the operating system and the OEM drivers, there is still a lot of work left. You need to reconfigure your system settings, re-download, and install all the Microsoft Store apps. Along with that, you need to individually download and install each third-party software, which makes it more challenging.

 But what if you could eliminate the hours spent in finding and installing every single app, and configuring every setting? We will discuss two methods to effortlessly migrate most of your old apps to your new PC.

## 1\. Using Microsoft Account

 If you used a Microsoft account on your old PC, Windows 11 offers multiple options to back up your App list, Preferences, and use OneDrive for personal files. To do that, you must enable [OneDrive](https://www.makeuseof.com/what-is-onedrive/)and back up all your personal files and folders to it. It will only take care of the files part but the apps and preferences are still left. But you must also enable the backup of these two things on your old PC before [reinstalling Windows 11](https://www.makeuseof.com/windows-11-reinstall-without-deleting-apps/) or migrating to a new PC.

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

<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->
## What About Any Left Out Apps?

 Even after using both methods, some apps will still be left out. It is because Microsoft Account sign-in only brings back Windows settings and Microsoft Store apps. The winget export file can restore only the apps listed in its official repository.

 As such, you still need to download the programs that aren’t included in both of these methods. But it will be a very short list compared to the effort you would have to put in if you just performed a normal installation.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
## Save Time When Setting Up Windows 11

 Make sure to enable files, apps, and preferences backup on your PC and create a winget export file beforehand. After you have both these backups in place, you can begin reinstalling Windows 11 on a different PC or reinstalling on the same PC.

 But what if you could eliminate the hours spent in finding and installing every single app, and configuring every setting? We will discuss two methods to effortlessly migrate most of your old apps to your new PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-techniques.techidaily.com/new-ice-chase-top-moments-captured-s-olympic-snowboard-race-events/"><u>[New] Ice Chase  Top Moments Captured 'S Olympic Snowboard Race Events</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-cameras-that-complement-best-hats-for-capturing-motorcycle-adventures/"><u>[Updated] Cameras That Complement  Best Hats for Capturing Motorcycle Adventures</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-finding-heartfelt-connections-in-discord-chats/"><u>[Updated] In 2024, Finding Heartfelt Connections in Discord Chats</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-premium-serene-pc-games-catalog/"><u>[Updated] In 2024, Premium Serene PC Games Catalog</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-transforming-hobby-footage-into-professional-vlogs/"><u>[Updated] Transforming Hobby Footage Into Professional Vlogs</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-niche-knowledge-on-selecting-premium-fpv-drone-propellers/"><u>2024 Approved  Niche Knowledge on Selecting Premium FPV Drone Propellers</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-the-free-webinar-recorders-manual/"><u>2024 Approved  The Free Webinar Recorder's Manual</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1723862790349-dell-xps-13s-dynamic-leap-with-lgs-latest-oled-technology-now-mass-produced/"><u>Dell XPS 13'S Dynamic Leap with LG’s Latest OLED Technology – Now Mass Produced</u></a></li>
<li><a href="https://driver-download.techidaily.com/download-and-setup-essential-steelseries-arctis-5-headset-driver-instructions/"><u>Download and Setup: Essential SteelSeries Arctis 5 Headset Driver Instructions</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-how-to-activating-hyper-v-for-win11-users/"><u>Essential How-To: Activating Hyper-V for Win11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-blackouts-during-win-based-gameplay/"><u>How to Fix Blackouts During Win-Based Gameplay</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-realign-read-aloud-settings-on-word-app/"><u>How To Realign Read Aloud Settings on Word App</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-salvage-your-failed-zip-extraction-in-windows-11/"><u>How To Salvage Your Failed ZIP Extraction in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-take-a-screenshot-of-uac-prompts-on-windows/"><u>How to Take a Screenshot of UAC Prompts on Windows</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-4-ways-to-transfer-music-from-apple-iphone-se-2020-to-ipod-touch-drfone-by-drfone-transfer-from-ios/"><u>In 2024, 4 Ways to Transfer Music from Apple iPhone SE (2020) to iPod touch | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-can-i-catch-the-regional-pokemon-without-traveling-on-vivo-s17-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How Can I Catch the Regional Pokémon without Traveling On Vivo S17 Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/redesigned-navigation-top-7-updates-to-window-11s-file-explorer/"><u>Redesigned Navigation: Top 7 Updates to Window 11'S File Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/regain-access-to-hidden-5ghz-networks-on-your-windows-pc/"><u>Regain Access to Hidden 5GHz Networks on Your Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-zoom-crash-code-1132-in-windows-os/"><u>Resolving Zoom Crash Code: 1132 in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-frozen-grammarly-on-your-computer-system/"><u>Solving Frozen Grammarly on Your Computer System</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-recover-from-a-blank-login-display-window/"><u>Steps to Recover From a Blank Login Display Window</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-disk-read-failed-problem/"><u>Tackling the “Disk Read Failed” Problem</u></a></li>
<li><a href="https://windows11.techidaily.com/the-vision-enhancers-guide-top-9-remedies-for-blurry-displays/"><u>The Vision Enhancers' Guide: Top 9 Remedies for Blurry Displays</u></a></li>
<li><a href="https://windows11.techidaily.com/top-tools-that-makes-your-laptops-os-change-more-manageable/"><u>Top Tools that Makes Your Laptop's OS Change More Manageable</u></a></li>
<li><a href="https://windows11.techidaily.com/transformative-tools-in-the-studio-4-microsoft-paint-redesigns/"><u>Transformative Tools in the Studio: 4 Microsoft Paint Redesigns</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshoot-and-fix-logitech-g933-microphone-issues-solutions-that-work/"><u>Troubleshoot & Fix Logitech G933 Microphone Issues: Solutions That Work</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-code-0x0001-for-nvidia-experience-in-windows/"><u>Troubleshooting Code 0X0001 for Nvidia Experience in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-the-store-error-a-fix-for-windows-x800704cf/"><u>Unblocking the Store Error: A Fix for Windows' X800704CF</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-airpods-windows-symbiosis/"><u>Unlocking AirPods-Windows Symbiosis</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-full-potential-of-your-systems-ram-with-windows/"><u>Unlocking the Full Potential of Your System's RAM with Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-power-of-cross-platform-note-taking-in-win11/"><u>Unveiling the Power of Cross-Platform Note Taking in Win11</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-best-mkv-video-cutters-for-mac-users/"><u>Updated 2024 Approved Best MKV Video Cutters for Mac Users</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>