---
title: Simplifying App Installations in Windows 11 Using Winstall
date: 2024-07-11T21:48:10.159Z
updated: 2024-07-12T21:48:10.159Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Simplifying App Installations in Windows 11 Using Winstall
excerpt: This Article Describes Simplifying App Installations in Windows 11 Using Winstall
keywords: Win11AppInstalls,EasyWinstallWindows,SimplifyWinInstall,QuickWinSetup,NoFussWinInstall,WinstallGuideWin,Windows11EasyInstall
thumbnail: https://thmb.techidaily.com/571b6953560c969952a7e82657ab3c73d752ed211ca4fd673ea682421459ce79.png
---

## Simplifying App Installations in Windows 11 Using Winstall

 The latest builds of Windows 10 and 11 now get the Windows Package Manager (Winget) from Microsoft. Before Microsoft included it in the latest versions of its operating systems, Winget was just an experimental project only enthusiasts used. Or you had to use third-party apps, like Chocolatey, to install apps automatically on your PC.

 Still, Winget is a command-line tool, meaning users can find it challenging to execute commands for app installation. Winstall solves this problem by introducing a web UI interface you can use to find and install apps.

 With Winstall, you can now easily use Winget to batch-install Windows 10 and 11 apps. Best of all, both tools are free! So, are you wondering how to use this? Let's begin.

## What Is Winstall?

![Winstall home page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/winstall-home-page.jpg)

 Winstall is a website that outputs the exact Winget commands you need to run in the Terminal app to install various apps. What's groundbreaking about this service is that it provides the exact package name, ID, and commands for everything you need—you no longer have to scrounge up what you need from all over the internet.

 With that, you can easily use Winget [from Windows Terminal or PowerShell](https://www.makeuseof.com/windows-terminal-vs-powershell/) by copying and pasting the commands.

 The exact purpose of Winstall is to help you install not one but multiple apps at once. So, you don't have to wait for one installation to finish and then execute the next command. In addition, using a Graphic User Interface (GUI—[what is a GUI?](https://www.makeuseof.com/what-is-gui/)) to find apps and create packages is easy for the average Joe. You can find the available packages of popular apps you need or create your own packages.

 Currently, the Winstall app library has over 4,600+ app listings, all thanks to the efforts of Mehdi Hassan and other contributors who continue to find, list, and update package details of apps. It isn't as big as the Microsoft Store or Winget repository but still tries to include all the popular and requested apps on the portal.

## How to Batch Install Apps in Windows 11 with Winstall

 Before batch-installing apps on your Windows 11 PC, remember that Winstall is a web portal that provides the complete Winget command to install one or many apps. It cannot directly install apps on your PC. For that, you need to run the generated commands in Command Prompt, PowerShell, as a batch file, or import as a .json file.

### 1\. How to Install Multiple Apps Using a Winstall App Pack

 Winstall app packs are pre-curated collections of apps you need on Windows 11\. There are essential packs, entertainment packs, browser packs, and more. Here's how to install a Winstall pack on your system:

1. Visit the [official Winstall website](https://winstall.app/) and scroll down to the **Featured Packs** section. You don't have to sign up to use the site.
2. Click on the app pack label. Alternatively, you can click on the **View Pack** option.  
![Install Multiple Apps Using a Winstall App Pack](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-multiple-apps-using-a-winstall-app-pack.jpg)
3. Now, click on the **Get Pack** button. This will scroll the page to the **Get the Pack** section at the bottom.  
![Install Multiple Apps Using a Winstall App Pack 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-multiple-apps-using-a-winstall-app-pack-2.jpg)

 Now, you can install the app pack in three ways: Batch, PowerShell, and Winget Import. You can [download and run the batch file](https://www.makeuseof.com/tag/use-windows-batch-file-commands-automate-repetitive-tasks/) with administrator privileges on your system. Or, you can copy the batch file commands and run them in an elevated Command Prompt window.

 Similarly, you can run the PowerShell commands in an elevated PowerShell window. The command prompt code uses the "**&&**" operator to sequentially install multiple apps in one attempt, while the PowerShell code uses the "**;**" operator to achieve the same thing. Lastly, you can download the .json file containing the commands and import it using Winget to download all the packages on your PC.

 Here's how to use the Winstall commands to install multiple apps on your PC using the Command Prompt:

1. Select the **Batch** option and click on the **Advanced** options. Keep the **installation scope** unchecked.
2. Then select the **Silent installation** checkbox. It will hold back all the installer popups and automatically complete the installation with default options.
3. Click on the **Copy to clipboard** button to copy the generated code.  
![Install Multiple Apps Using a Winstall App Pack 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-multiple-apps-using-a-winstall-app-pack-3.jpg)
4. Now, press **Win + R** to [launch the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **cmd** and press **Ctrl + Shift + Enter** keys to open the tool with administrator privileges.
5. Paste the copied code into the Command Prompt window and press the enter key to execute the code.  
![Install Multiple Apps Using a Winstall App Pack 4](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-multiple-apps-using-a-winstall-app-pack-4.jpg)
6. The commands will execute linearly and download and install the respective apps on your system. You won't have to click a button or interact with an installer window. After all the apps finish installation, close the Command Prompt window.

### 2\. How to Install Multiple Apps Using a Custom App List in Winstall

 If you don't like the packs available on the Winstall packs section, you can create your custom collection or pack and then download and batch-install those apps. But you must pick at least five apps to create a pack and have to log in. Or you can use the Generate Script option to view the code to batch install the selected apps. Repeat the following steps:

1. Click on the **search bar** on the Winstall home page and type the app's name. Then click on the **+** icon to add the app to a pack.
2. Similarly, search and add more apps to the pack. There's no upper limit, but we will suggest batch-installing five apps in one session. If you encounter any error, finding and reattempting failed app installs will be easy.
3. Click on the **Generate Script** button. Like before, you will be redirected to a page with multiple options to install the app packages on your system.  
![Install Multiple Apps Using a Custom App List in Winstall](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-multiple-apps-using-a-custom-app-list-in-winstall.jpg)
4. You can use the **Advanced options** section to enable the **silent installation** command while adding the selected packages. Then, click on the **Copy to Clipboard** button.  
![Install Multiple Apps Using a Custom App List in Winstall 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-multiple-apps-using-a-custom-app-list-in-winstall-2.jpg)
5. [Open Command Prompt with administrator privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/) on your system. Paste the copied code into it and press Enter to execute the code.  
![Install Multiple Apps Using a Custom App List in Winstall 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-multiple-apps-using-a-custom-app-list-in-winstall-3.jpg)
6. Wait for Winget to download and install each app and then close the Command Prompt window.

## Things to Remember While Using Winstall

 Using Winstall is pretty straightforward: you don't need to figure out the commands because it does that for you. It is also free, but you can donate to support the developers. However, the installation doesn't go smoothly as always, and it can be difficult to troubleshoot and reattempt the installation for an average user.

 However, you can avoid most of these issues by ensuring a few things:

* Ensure an uninterrupted internet connection while installing the apps using Winget.
* Update the Winget source if the utility fails to find the source file. Just run the Winget source update command, and it will update both the msstore and Winget source in one go.
* Always run the Command Prompt, PowerShell, or batch file with administrator privileges, or you could face issues while installing certain apps. Moreover, use the silent installation option (-h) with all Winget batch installs. It will save you the effort of interacting with the installer window.

 If you want to know more about Winget, you should check out [our Widows Package Manager guide](https://www.makeuseof.com/how-to-download-install-and-use-the-windows-package-manager-winget/).

## Batch Installing Apps Is a Piece of Cake

 Opening Microsoft Store or your browser and manually searching for each app or program is exhausting. You can use Winstall to generate code to download and install multiple apps using Winget. Moreover, you can even sign in and create a pack on the website, so other users don't have to search for a specific collection of useful Windows 11 apps.

 Still, Winget is a command-line tool, meaning users can find it challenging to execute commands for app installation. Winstall solves this problem by introducing a web UI interface you can use to find and install apps.

 With Winstall, you can now easily use Winget to batch-install Windows 10 and 11 apps. Best of all, both tools are free! So, are you wondering how to use this? Let's begin.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/fuse-windows-and-tdarr-for-unrivaled-scalable-video-conversion-efficiency/"><u>Fuse Windows and Tdarr for Unrivaled, Scalable Video Conversion Efficiency</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-cutting-edge-audio-display-and-animation-in-final-cut-pro-a-comprehensive-tutorial-for-professional-editors/"><u>2024 Approved Cutting-Edge Audio Display & Animation in Final Cut Pro A Comprehensive Tutorial for Professional Editors</u></a></li>
<li><a href="https://windows11.techidaily.com/uninstalling-the-default-software-on-win11-pcs/"><u>Uninstalling the Default Software on Win11 PCs</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/6-methods-for-switching-from-apple-iphone-15-to-samsung-drfone-by-drfone-transfer-from-ios/"><u>6 Methods for Switching from Apple iPhone 15 to Samsung | Dr.fone</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-mastering-xml-files-in-final-cut-pro-x-the-ultimate-guide/"><u>Updated 2024 Approved Mastering XML Files in Final Cut Pro X The Ultimate Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/illustrating-maximum-and-minimum-cpu-stages-on-windows/"><u>Illustrating Maximum & Minimum CPU Stages on Windows</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-the-ultimate-guide-to-state-of-the-art-dj-equipment/"><u>New The Ultimate Guide to State-of-the-Art DJ Equipment</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-performance-reducing-background-processes/"><u>Enhancing Performance: Reducing Background Processes</u></a></li>
<li><a href="https://windows11.techidaily.com/crystal-clear-in-minutes-mastering-fuzzy-window-fixes/"><u>Crystal Clear in Minutes: Mastering Fuzzy Window Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/why-choosing-windows-11-is-a-wise-decision-over-macos/"><u>Why Choosing Windows 11 Is a Wise Decision over MacOS</u></a></li>
<li><a href="https://windows11.techidaily.com/illuminating-windows-11-tray-and-secret-icons/"><u>Illuminating Windows 11 Tray & Secret Icons</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-exclusive-open-source-logo-generators-for-discord-servers/"><u>[Updated] 2024 Approved  Exclusive Open Source Logo Generators for Discord Servers</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-shutter-wisdom-tips-for-astounding-image-finishes/"><u>[Updated] Shutter Wisdom  Tips for Astounding Image Finishes</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-chromes-dark-window/"><u>Clearing Up Chrome's Dark Window</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-sticky-note-opening-on-windows-11/"><u>Breaking Down Sticky Note Opening on Windows 11</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-gps-location-on-huawei-p60-easily-and-safely-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change GPS Location on Huawei P60 Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-do-you-remove-restricted-mode-on-iphone-6-drfone-by-drfone-ios/"><u>How Do You Remove Restricted Mode on iPhone 6 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-instantly-generate-multiple-directories-in-modern-windows-environments/"><u>How to Instantly Generate Multiple Directories in Modern Windows Environments</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-command-prompt-tactics-for-registry-optimization/"><u>Expert Command Prompt Tactics for Registry Optimization</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-all-encompassing-review-djis-inspire-1-drone/"><u>2024 Approved  All-Encompassing Review  DJI's Inspire 1 Drone</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-windows-11-ease-of-use-with-improved-run-feature/"><u>Enhancing Windows 11 Ease of Use with Improved Run Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-windows-11-editions-home-or-pro-advantage/"><u>Deciphering Windows 11 Editions: Home or Pro Advantage</u></a></li>
<li><a href="https://windows11.techidaily.com/controlling-registry-tools-access-on-windows-11/"><u>Controlling Registry Tools Access on Windows 11</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/024-approved-global-giga-viewers-worlds-favorite-youtube-stars/"><u>[New] 2024 Approved  Global Giga-Viewers  World's Favorite YouTube Stars</u></a></li>
<li><a href="https://windows11.techidaily.com/an-insight-into-windows-audio-channel-separation/"><u>An Insight Into Windows' Audio Channel Separation</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-3-strategies-for-tiktok-livestreaming-from-desktop/"><u>In 2024, 3 Strategies for TikTok Livestreaming From Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/jump-over-the-endless-update-hurdle-quick-fixes-now/"><u>Jump Over The Endless Update Hurdle: Quick Fixes Now</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-operation-elevation-woes-on-windows-11-and-11/"><u>Breaking Down Operation Elevation Woes on Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/circumventing-driver-checks-in-windows-no-signatures-any-installation/"><u>Circumventing Driver Checks in Windows: No Signatures, Any Installation</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-audiovisual-harmony-music-integration-in-social-media/"><u>2024 Approved  Audiovisual Harmony  Music Integration in Social Media</u></a></li>
<li><a href="https://windows11.techidaily.com/automated-file-handling-via-task-scheduler/"><u>Automated File Handling via Task Scheduler</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-selection-of-cost-free-storage-solutions-for-windows-users/"><u>The Ultimate Selection of Cost-Free Storage Solutions for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-loss-of-internet-router-webpage-in-windows/"><u>Fixing Loss of Internet Router Webpage in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-peak-productivity-essential-windows-11-and-cmd-commands/"><u>Achieve Peak Productivity: Essential Windows 11 & Cmd Commands</u></a></li>
<li><a href="https://fake-location.techidaily.com/methods-to-change-gps-location-on-xiaomi-redmi-a2plus-drfone-by-drfone-virtual-android/"><u>Methods to Change GPS Location On Xiaomi Redmi A2+ | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-bypass-android-lock-screen-using-emergency-call-on-infinix-smart-8-plus-by-drfone-android/"><u>How to Bypass Android Lock Screen Using Emergency Call On Infinix Smart 8 Plus?</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-how-to-create-a-facebook-account/"><u>[New] In 2024, How to Create a Facebook Account</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-the-ultimate-list-of-free-whiteboard-animation-software-for-windows-mac-and-beyond/"><u>Updated The Ultimate List of Free Whiteboard Animation Software for Windows, Mac, and Beyond</u></a></li>
<li><a href="https://windows11.techidaily.com/key-applications-that-bridge-the-mac-and-windows-divide/"><u>Key Applications that Bridge the Mac and Windows Divide</u></a></li>
</ul></div>
