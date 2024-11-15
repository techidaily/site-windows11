---
title: Preparing Your Devices for a Win 11 App Transfer Transition
date: 2024-11-12T16:01:30.062Z
updated: 2024-11-15T17:15:48.134Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Preparing Your Devices for a Win 11 App Transfer Transition
excerpt: This Article Describes Preparing Your Devices for a Win 11 App Transfer Transition
keywords: Win 11 Update Guide,Device Win 11 Compatibility,Win 11 Migration Tools,Data Backup for Windows 11,App Transfer in Win 11,Win 11 Installation Steps,Win 11 System Prep
thumbnail: https://thmb.techidaily.com/16a9b35c6bd9fc401c0908fd1a1024fa5ae9f4d4fbf37f1eb35abe3fab424ae1.jpg
---

## Preparing Your Devices for a Win 11 App Transfer Transition

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2132162/7443" target="_top" id="2132162">
  <img src="//a.impactradius-go.com/display-ad/7443-2132162" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2132162/7443" style="position:absolute;visibility:hidden;" border="0" />
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
5. Patiently wait while winget downloads and installs all the packages in the JSON file one by one. Then, close the Command Prompt window.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975807/19272" target="_top" id="1975807">
  <img src="//a.impactradius-go.com/display-ad/19272-1975807" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975807/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997643/19272" target="_top" id="1997643">
  <img src="//a.impactradius-go.com/display-ad/19272-1997643" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997643/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## What About Any Left Out Apps?

 Even after using both methods, some apps will still be left out. It is because Microsoft Account sign-in only brings back Windows settings and Microsoft Store apps. The winget export file can restore only the apps listed in its official repository.

 As such, you still need to download the programs that aren’t included in both of these methods. But it will be a very short list compared to the effort you would have to put in if you just performed a normal installation.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151894/7443" target="_top" id="2151894">
  <img src="//a.impactradius-go.com/display-ad/7443-2151894" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151894/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-sword-and-shield-the-ultimate-10-game-collection/"><u>[New] 2024 Approved Sword and Shield The Ultimate 10-Game Collection</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/024-approved-transform-your-asmr-experience-into-proficiently-produced-videos/"><u>[New] 2024 Approved Transform Your ASMR Experience Into Proficiently Produced Videos</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-2024-approved-from-raw-footage-to-stunning-visuals-using-luts-in-obs-studio/"><u>[Updated] 2024 Approved From Raw Footage to Stunning Visuals Using LUTs in OBS Studio</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-explore-our-updated-top-10-best-fb-video-extractors-for-android-users/"><u>[Updated] Explore Our Updated Top 10 Best FB Video Extractors for Android Users</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-windows-11-file-transfers-that-halt/"><u>How to Resolve Windows 11 File Transfers That Halt</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-watch-hulu-outside-us-on-lava-blaze-2-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Watch Hulu Outside US On Lava Blaze 2 Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-art-of-remedying-voice-typing-flaws-in-windows-11/"><u>Master the Art of Remedying Voice Typing Flaws in Windows 11</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/tation-plaza-your-gateway-to-a-thousand-channels-for-2024/"><u>PlayStation Plaza Your Gateway to a Thousand Channels for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-steps-to-overcome-a-freeze-in-windows-based-itunes/"><u>Quick Steps to Overcome a Freeze in Windows-Based iTunes</u></a></li>
<li><a href="https://windows11.techidaily.com/redefining-window-11-interface-top-6-upgrades-for-the-taskbar/"><u>Redefining Window 11 Interface: Top 6 Upgrades for the Taskbar</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/resolving-the-issue-where-is-msvcr70dll/"><u>Resolving the Issue: Where Is MSVCR70.DLL?</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-your-os-without-bitlockers-assistance/"><u>Securing Your OS Without BitLocker's Assistance</u></a></li>
</ul></div>

