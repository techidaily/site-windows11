---
title: How to Reprogram Windows 11'S Preferred Programs Effectively
date: 2024-07-11T21:45:44.710Z
updated: 2024-07-12T21:45:44.710Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Reprogram Windows 11'S Preferred Programs Effectively
excerpt: This Article Describes How to Reprogram Windows 11'S Preferred Programs Effectively
keywords: Win11 Preferred Program Change,Efficient Program Settings Windows,Optimize Win11 Default Apps,Reprogram Win11 Choice,Alter Win11 Favorite Apps,Update Win11 Priority Uses,Modify Win11 Preferred Software
thumbnail: https://thmb.techidaily.com/c4be10a970b234d5f6880acef4bdb2e4828d9b824f3ccac5078e8475f10ac115.jpg
---

## How to Reprogram Windows 11'S Preferred Programs Effectively

 If you are not satisfied with any of the default apps assigned by Windows, you can change them to your preferred options. This process was quite simple in Windows 10, but Microsoft has made it a bit complicated for Windows 11 users.

 In this guide, we will discuss the method of changing the default apps in Windows 11 in detail. We have also discussed several troubleshooting methods later in this guide that you can try if the default apps fail to change.

## How to Change the Default Apps in Windows 11

[Changing the default apps in Windows 10](https://www.makeuseof.com/tag/change-default-settings-windows-10/) is quite simple. You can access the**Default Apps** section of the Settings app and replace the current default app with your preferred option.

 In Windows 11, this method is slightly different. You must set a program default for all the registered file types and links relevant to it since there isn’t a**Set default for all** option available.

 Below, we have listed different ways of changing the default apps in Windows 11:

### 1\. Choose the Open With Option

 The easiest method of changing the default apps option is by using the Open with option in the context menu for files.

Here is how you can do that:

1. Right-click on the targeted file. For instance, an image file that you want to open with an app other than the default Photos app.
2. Choose**Open with** \>**Choose another app** from the context menu.  
![Choose another app to open the targeted file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/image-open-with-choose-another-app.jpg)
3. Now, in the following dialog, choose the app you want to set as the default option. If you cannot find the targeted app in the list, choose**Look for another app on this PC** and then select the app.
4. Click on**Always use this app to open files** and click**OK** . This should set the selected app as the default preference.  
![Set a default app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/set-the-default-app.jpg)

### 2\. Use the Settings App

 The next thing that you can do is access the Default Apps option and choose the preferred app from there.

Follow these steps to proceed:

1. Press the Win + I keys together to open the Windows Settings.
2. Choose**Apps** from the left pane.
3. Click on**Default apps** .  
![Click on the Default apps option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/win11-settings-apps-default-apps.jpg)
4. Next, choose the app that you want to set as default. You should now see all the file types and link types the app is registered with.
5. If you want to choose a program as the default for all its registered file types and links, you'd need to click each type and choose the desired application in the following dialog.  
![Pick a default file type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/pick-a-default-file-type.jpg)

 This should set the app as the default option for the selected file and link types. However, if you [reset Windows 11 to its default state](https://www.makeuseof.com/windows-11-factory-reset-without-admin-password/) ever, you will lose all these settings.

### 3\. Use File Properties

 You can also change the file properties of the targeted file to open it with a new default app.

To proceed, follow these steps:

1. Right-click on the targeted file and choose**Properties** from the context menu.  
![Access the properties of the file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/image-properties.jpg)
2. Head over to the General tab and click on the**Change** button associated with**Opens with** .  
![Click on the Change button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/image-properties-general-change.jpg)
3. Now, choose the desired app and click**OK** .

## What to Do If You Cannot Change the Default Apps in Windows 11?

 If you are unable to change the default apps in Windows 11 despite trying the different methods mentioned above, it could be due to the following reasons:

* The app that you are trying to set as the default option is dealing with a corruption error or is not installed correctly.
* A group policy setting in the system is preventing you from changing these configurations.
* You do not have sufficient permissions to make changes of this level in the system.
* The app is not compatible with your system.

 In this case,[ensure that your user account has administrative rights](https://www.makeuseof.com/check-windows-account-admin-rights/) and that the app you are trying to set as default is compatible with the system. Here are some more steps you can follow to resolve the problem.

### 1\. Update Windows 11

 If you're running an outdated version of Windows, you may be experiencing problems due to incompatibility issues. Windows 11 needs to be updated to the latest version in this case.

Here is how you can do that:

1. Press the Win + I keys together to open Windows Settings.
2. Choose**Windows Update** from the left pane.
3. Now, click on the**Check for updates** button on the right side.
4. Install all the pending updates one by one by clicking on the**Download & install** button and then restart your PC.  
![Click on the Download & install button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/settings-windows-update-download-and-install.jpg)

 Once this is done, follow one of the steps above to change the default app.

### 2\. Reset the Targeted App

 If the problem is within the app that you are trying to change, you can reset the program to solve the problem.

Follow these steps to proceed:

1. Press Win + S keys together to open Windows Search.
2. Type Powershell and choose**Run as administrator** .
3. Click**Yes** in the User Account Control prompt.
4. In the Powershell window, type the command mentioned below and click Enter. Replace packagename with the name package name of the app that you want to set as default.  
Get-AppxPackage packagename -AllUsers | Reset-AppxPackage
5. For instance, if you want to change the Photos app, execute the following command:  
Get-AppxPackage Microsoft.Windows.Photos -AllUsers | Reset-AppxPackage  
![Reset the app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/get-appxpackage-packagename.jpg)
6. Once the command is executed, check if you can change the default app.

### 3\. Reinstall the App

 Lastly, you can try reinstalling the app that you want to set as default. This will eliminate any corruption errors are bugs within the app that are preventing you from setting it as the default option.

Here is how you can proceed:

1. Press the Win + R keys together to open a Run dialog.
2. Type control in Run and click Enter.
3. In the following window, navigate to**Uninstall a program** .  
![Uninstall a program](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/uninstall-a-program.jpg)
4. Locate the targeted app and right-click on it.
5. Choose**Uninstall** and follow the on-screen instructions to proceed.  
![Uninstall the app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/win11-uninstall-program.jpg)

 Once the uninstallation is completed, restart the computer and reinstall the app. Hopefully, this time, you will be able to set it as the default option without any problems.

## Make Your Preferred Apps Default

 The apps set as the default options on Windows are quite user-friendly and efficient. It is possible, however, to change the default preference to a better option if you have found one that suits your system better.

 With the methods listed above, you should be able to change the default apps on your Windows 11 system in no time. Nevertheless, keep in mind that in the event that Windows is reinstalled or reset, these options will return to the default configuration.

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
<li><a href="https://windows11.techidaily.com/enhancing-windows-11-ease-of-use-with-improved-run-feature/"><u>Enhancing Windows 11 Ease of Use with Improved Run Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-instantly-generate-multiple-directories-in-modern-windows-environments/"><u>How to Instantly Generate Multiple Directories in Modern Windows Environments</u></a></li>
<li><a href="https://windows11.techidaily.com/controlling-registry-tools-access-on-windows-11/"><u>Controlling Registry Tools Access on Windows 11</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-ace-your-screens-the-premium-guide-to-androids-top-8-capture-apps-for-2024/"><u>[New] Ace Your Screens  The Premium Guide to Android’s Top 8 Capture Apps for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/an-insight-into-windows-audio-channel-separation/"><u>An Insight Into Windows' Audio Channel Separation</u></a></li>
<li><a href="https://windows11.techidaily.com/circumventing-driver-checks-in-windows-no-signatures-any-installation/"><u>Circumventing Driver Checks in Windows: No Signatures, Any Installation</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-use-ispoofer-on-oppo-k11-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to use iSpoofer on Oppo K11 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/key-applications-that-bridge-the-mac-and-windows-divide/"><u>Key Applications that Bridge the Mac and Windows Divide</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-easy-fixes-how-to-recover-forgotten-icloud-password-on-your-apple-iphone-11-pro-max-by-drfone-ios/"><u>In 2024, Easy Fixes How To Recover Forgotten iCloud Password On your Apple iPhone 11 Pro Max</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-chromes-dark-window/"><u>Clearing Up Chrome's Dark Window</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/1716464326223-awe-inspiring-allure-top-youtube-magic-editing-wonders/"><u>Awe-Inspiring Allure  Top YouTube Magic Editing Wonders!</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-windows-11-editions-home-or-pro-advantage/"><u>Deciphering Windows 11 Editions: Home or Pro Advantage</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-cultivate-a-thriving-igtv-community-5-key-increase-strategies/"><u>2024 Approved  Cultivate a Thriving IGTV Community  5 Key Increase Strategies</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/discerning-broken-optical-container-auditory-event/"><u>Discerning Broken Optical Container Auditory Event</u></a></li>
<li><a href="https://windows11.techidaily.com/master-key-hunting-for-windows-1110-enthusiasts/"><u>Master Key Hunting for Windows 11/10 Enthusiasts</u></a></li>
<li><a href="https://windows11.techidaily.com/illustrating-maximum-and-minimum-cpu-stages-on-windows/"><u>Illustrating Maximum & Minimum CPU Stages on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-operation-elevation-woes-on-windows-11-and-11/"><u>Breaking Down Operation Elevation Woes on Windows 11 & 11</u></a></li>
<li><a href="https://vp-tips.techidaily.com/ultimate-selection-of-omnidirectional-recording-devices/"><u>Ultimate Selection of Omnidirectional Recording Devices</u></a></li>
<li><a href="https://fake-location.techidaily.com/prevent-cross-site-tracking-on-oneplus-nord-n30-se-and-browser-drfone-by-drfone-virtual-android/"><u>Prevent Cross-Site Tracking on OnePlus Nord N30 SE and Browser | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-transforming-scenes-with-ease-your-gopro-time-lapse-guide/"><u>In 2024, Transforming Scenes with Ease  Your GoPro Time-Lapse Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-command-prompt-tactics-for-registry-optimization/"><u>Expert Command Prompt Tactics for Registry Optimization</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-catch-or-beat-sleeping-snorlax-on-pokemon-go-for-xiaomi-redmi-k70-drfone-by-drfone-virtual-android/"><u>In 2024, Catch or Beat Sleeping Snorlax on Pokemon Go For Xiaomi Redmi K70 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-win11-avoid-and-fix-0x0-error-instantly/"><u>Mastering Win11: Avoid and Fix 0X0 Error Instantly</u></a></li>
<li><a href="https://windows11.techidaily.com/illuminating-windows-11-tray-and-secret-icons/"><u>Illuminating Windows 11 Tray & Secret Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/automated-file-handling-via-task-scheduler/"><u>Automated File Handling via Task Scheduler</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-vivo-y77t-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Vivo Y77t to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/crystal-clear-in-minutes-mastering-fuzzy-window-fixes/"><u>Crystal Clear in Minutes: Mastering Fuzzy Window Fixes</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-pictures-from-sony-xperia-1-v-by-fonelab-android-recover-pictures/"><u>Easy steps to recover deleted pictures from Sony Xperia 1 V.</u></a></li>
<li><a href="https://techidaily.com/how-to-update-or-downgrade-apple-iphone-6s-plus-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade Apple iPhone 6s Plus? | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/proven-ways-to-fix-there-was-a-problem-parsing-the-package-on-poco-f5-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Proven Ways to Fix There Was A Problem Parsing the Package on Poco F5 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-peak-productivity-essential-windows-11-and-cmd-commands/"><u>Achieve Peak Productivity: Essential Windows 11 & Cmd Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-execution-descriptor-labels-in-software/"><u>Leveraging Execution Descriptor Labels in Software</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-sticky-note-opening-on-windows-11/"><u>Breaking Down Sticky Note Opening on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-loss-of-internet-router-webpage-in-windows/"><u>Fixing Loss of Internet Router Webpage in Windows</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-easiest-guide-how-to-clone-poco-x6-pro-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Easiest Guide How to Clone Poco X6 Pro Phone? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/jump-over-the-endless-update-hurdle-quick-fixes-now/"><u>Jump Over The Endless Update Hurdle: Quick Fixes Now</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-deciphering-the-codex-of-discords-nitro-a-guide-to-its-availability/"><u>[Updated] Deciphering the Codex of Discord's Nitro  A Guide to Its Availability</u></a></li>
<li><a href="https://windows11.techidaily.com/why-choosing-windows-11-is-a-wise-decision-over-macos/"><u>Why Choosing Windows 11 Is a Wise Decision over MacOS</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-jdk-installation-for-windows-11-users/"><u>Mastering JDK Installation for Windows 11 Users</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-streamline-your-filming-gameplay-on-fbx-for-2024/"><u>[Updated] Streamline Your Filming - Gameplay on FBX for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/fuse-windows-and-tdarr-for-unrivaled-scalable-video-conversion-efficiency/"><u>Fuse Windows and Tdarr for Unrivaled, Scalable Video Conversion Efficiency</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-8-plus-to-other-iphone-13-pro-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone 8 Plus to other iPhone 13 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-free-music-recording-software-the-ultimate-list-of-11-top-picks-for-2024/"><u>Updated Free Music Recording Software The Ultimate List of 11 Top Picks for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-performance-reducing-background-processes/"><u>Enhancing Performance: Reducing Background Processes</u></a></li>
</ul></div>
