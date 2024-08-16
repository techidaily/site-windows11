---
title: Guide to Reinstalling Favorite Apps on New Windows 11 Devices
date: 2024-08-15T16:03:11.691Z
updated: 2024-08-16T16:03:11.691Z
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

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Using a Winget JSON File

 The first method of using Microsoft Account has its limitations. It only includes Windows apps and settings but leaves many other third-party apps that you installed from the Winget repository or from the web. So you can use Winget to export the app list into a JSON file and then import it to your new Windows 11 PC. You must execute this method after Windows 11 brings back all the settings and Microsoft apps, and you boot to the desktop.

 Repeat the following steps to import a Winget JSON file:

1. Download or copy the Winget export file on your system.
2. Press **Win + R** to open the **Run dialog box**. Type **cmd** and press **Ctrl + Shift + Enter** to [open Command Prompt with administrator privileges](https://www.makeuseof.com/how-to-always-open-command-prompt-as-administrator-windows/).
3. Now, use the **winget import -i** command to import the JSON file. Type the following command and press the **Enter** key:  
`winget import -i C:\apps.json --accept-source-agreements --accept-package-agreements`
4. Replace the folder location and name with the storage location and name of the winget export file on your system.  
![Import Apps Using Winget in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/import-apps-using-winget-in-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
5. Patiently wait while winget downloads and installs all the packages in the JSON file one by one. Then, close the Command Prompt window.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->
## What About Any Left Out Apps?

 Even after using both methods, some apps will still be left out. It is because Microsoft Account sign-in only brings back Windows settings and Microsoft Store apps. The winget export file can restore only the apps listed in its official repository.

 As such, you still need to download the programs that aren’t included in both of these methods. But it will be a very short list compared to the effort you would have to put in if you just performed a normal installation.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->
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
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-secrets-to-high-quality-roblox-game-footage-on-macos/"><u>[New] 2024 Approved  Secrets to High-Quality Roblox Game Footage on macOS</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-best-screenshots-software-series/"><u>[New] Best Screenshots Software Series</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-snapchat-emojis-the-real-meaning-you-may-not-know-for-2024/"><u>[New] Snapchat Emojis  The Real Meaning You May Not Know for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-step-by-step-guide-activate-or-deactivate-picture-in-picture-on-apples-youtube-app/"><u>[New] Step-by-Step Guide  Activate or Deactivate Picture-in-Picture on Apple's YouTube App</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/he-art-of-saving-just-a-bit-from-youtube-videos/"><u>[New] The Art of Saving Just a Bit From YouTube Videos</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-the-ultimate-guide-to-drawing-characters-with-snaps/"><u>[New] The Ultimate Guide to Drawing Characters with Snaps</u></a></li>
<li><a href="https://windows11.techidaily.com/10-command-prompt-wonders-you-didnt-know/"><u>10 Command Prompt Wonders You Didn’t Know!</u></a></li>
<li><a href="https://unlock-android.techidaily.com/10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-tecno-pova-6-pro-5g-by-drfone-android/"><u>10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On Tecno Pova 6 Pro 5G</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-a-showcase-of-excellence-the-best-9-platforms-for-accessing-3d-font-innovations/"><u>2024 Approved  A Showcase of Excellence  The Best 9 Platforms for Accessing 3D Font Innovations</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-best-music-players-software-for-windows/"><u>2024 Approved  Best Music Players Software for Windows</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-navigating-to-facebooks-story-archives-quickly/"><u>2024 Approved  Navigating to Facebook's Story Archives Quickly</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-easy-solutions-to-hard-reset-infinix-note-30-vip-drfone-by-drfone-reset-android-reset-android/"><u>3 Easy Solutions to Hard Reset Infinix Note 30 VIP | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/automated-file-handling-via-task-scheduler/"><u>Automated File Handling via Task Scheduler</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-virtual-fraud-tips-for-discerning-true-windows-apps/"><u>Avoid Virtual Fraud: Tips for Discerning True Windows Apps</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/best-photo-boosts-for-perfecting-your-feed-for-2024/"><u>Best Photo Boosts for Perfecting Your Feed for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-operation-elevation-woes-on-windows-11-and-11/"><u>Breaking Down Operation Elevation Woes on Windows 11 & 11</u></a></li>
<li><a href="https://fox-http.techidaily.com/canva-skills-purging-images-of-their-surroundings-for-2024/"><u>Canva Skills  Purging Images of Their Surroundings for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-failed-application-launches-windows-11s-error-0xc000003e-explained/"><u>Correcting Failed Application Launches: Windows 11'S Error 0XC000003E Explained</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/cropping-videos-in-avidemux-a-comprehensive-guide-for-beginners-and-pros/"><u>Cropping Videos in Avidemux A Comprehensive Guide for Beginners and Pros</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-the-absence-of-drive-letters-in-windows-environments/"><u>Dissecting the Absence of Drive Letters in Windows Environments</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tracker-tools-the-ultimate-6-list-for-windows-users/"><u>Essential Tracker Tools: The Ultimate 6 List For Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-advice-overcoming-printer-error-0xfffffff/"><u>Expert Advice: Overcoming Printer Error 0xFFFFFFF</u></a></li>
<li><a href="https://windows11.techidaily.com/fuse-windows-and-tdarr-for-unrivaled-scalable-video-conversion-efficiency/"><u>Fuse Windows and Tdarr for Unrivaled, Scalable Video Conversion Efficiency</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-restore-a-bricked-poco-c51-back-to-operation-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Restore a Bricked Poco C51 Back to Operation | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-music-from-realme-12-pro-5g-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Music from Realme 12 Pro 5G to iPod | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-oppo-reno-9a-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Oppo Reno 9A to New Android? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-unlock-and-reset-restricted-program-status/"><u>How to Unlock and Reset Restricted Program Status</u></a></li>
<li><a href="https://windows11.techidaily.com/illustrating-maximum-and-minimum-cpu-stages-on-windows/"><u>Illustrating Maximum & Minimum CPU Stages on Windows</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-capturing-stunning-webcam-content-quick-steps-to-success/"><u>In 2024, Capturing Stunning WebCam Content  Quick Steps to Success</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-vivo-y78plus-t1-edition-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>In 2024, Vivo Y78+ (T1) Edition ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/infusing-youtube-soundtracks-within-multimedia/"><u>Infusing YouTube Soundtracks Within Multimedia</u></a></li>
<li><a href="https://windows11.techidaily.com/key-applications-that-bridge-the-mac-and-windows-divide/"><u>Key Applications that Bridge the Mac and Windows Divide</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/laughlens-quickly-create-social-memes-and-gifs/"><u>LaughLens  Quickly Create Social Memes & Gifs</u></a></li>
<li><a href="https://windows11.techidaily.com/master-key-hunting-for-windows-1110-enthusiasts/"><u>Master Key Hunting for Windows 11/10 Enthusiasts</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-win11-pointer-adjustments-for-access/"><u>Mastering Win11 Pointer Adjustments for Access</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-storage-effortlessly-quick-pathways-into-windows-disk-manager/"><u>Optimize Storage Effortlessly: Quick Pathways Into Windows Disk Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-visual-quality-dpi-settings-guide-for-windows-11/"><u>Optimize Visual Quality: DPI Settings Guide for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-directx-update-issues-on-windows/"><u>Overcoming DirectX Update Issues on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/recover-lost-pin-following-system-breakdown-on-windows-11/"><u>Recover Lost PIN Following System Breakdown on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/redirecting-to-file-explorer-from-onedrive-menu/"><u>Redirecting to File Explorer From OneDrive Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/reinforce-internet-ties-for-your-windows-devices-amid-sluggishness/"><u>Reinforce Internet Ties for Your Windows Devices Amid Sluggishness</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-troubleshooting-excel-display-issue-in-notepad/"><u>Remedy: Troubleshooting Excel Display Issue in Notepad</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-default-windows-preferences-post-restart/"><u>Reviving Default Windows Preferences Post-Restart</u></a></li>
<li><a href="https://windows11.techidaily.com/say-goodbye-to-lag-how-to-fix-warhammer-40k-delays-on-your-pc/"><u>Say Goodbye to Lag: How to Fix Warhammer 40K Delays on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-app-installations-in-windows-11-using-winstall/"><u>Simplifying App Installations in Windows 11 Using Winstall</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-taskbar-transparency-in-maxed-browser-screens/"><u>Solutions for Taskbar Transparency in Maxed Browser Screens</u></a></li>
<li><a href="https://os-tips.techidaily.com/step-by-step-guide-how-to-effectively-reboot-your-ipod-touchnanoshuffle-issues-resolved/"><u>Step-by-Step Guide: How to Effectively Reboot Your iPod Touch/Nano/Shuffle (Issues Resolved)</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-completely-removing-wsl-in-win-11/"><u>Step-by-Step: Completely Removing WSL in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-stopping-self-activating-store-app/"><u>Strategies for Stopping Self-Activating Store App</u></a></li>
<li><a href="https://windows11.techidaily.com/swiftly-overcoming-windows-access-denied-blunders/"><u>Swiftly Overcoming Windows Access Denied Blunders</u></a></li>
<li><a href="https://windows11.techidaily.com/the-insiders-edge-building-snaps-with-powertoys/"><u>The Insider's Edge: Building Snaps with PowerToys</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-eliminating-enter-usernamepassword-alerts-in-windows/"><u>Troubleshooting: Eliminating 'Enter Username/Password' Alerts in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unseen-windows-firewall-protection-sectors-demystified/"><u>Unseen Windows Firewall Protection Sectors Demystified</u></a></li>
</ul></div>
