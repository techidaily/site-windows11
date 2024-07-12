---
title: "Navigating New Territory: Altering Default App Choices in Windows 11"
date: 2024-07-11T22:04:47.651Z
updated: 2024-07-12T22:04:47.651Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Navigating New Territory: Altering Default App Choices in Windows 11"
excerpt: "This Article Describes Navigating New Territory: Altering Default App Choices in Windows 11"
keywords: Win11 App Selection,Changing OS Defaults,Customize Windows 11,Shift Windows Interface,Modify UI Settings,New Territory Tips,Personalize Win11
thumbnail: https://thmb.techidaily.com/6bf5f8c3a7d4525074ba1b28f14c511bc7c37f5e8a7742b128774ee55042b67a.jpg
---

## Navigating New Territory: Altering Default App Choices in Windows 11

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
<li><a href="https://windows11.techidaily.com/techniques-for-turning-onoff-the-registry-editor/"><u>Techniques for Turning On/Off the Registry Editor</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-hyper-v-in-windows-11-steps-to-follow/"><u>Enabling Hyper-V in Windows 11: Steps to Follow</u></a></li>
<li><a href="https://windows11.techidaily.com/the-gateway-to-information-conquering-windows-qr-code-scan/"><u>The Gateway to Information: Conquering Windows' QR Code Scan</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-fast-access-to-textual-explanations/"><u>Windows 11: Fast Access to Textual Explanations</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-microsoft-store-error-code-0x80072f30/"><u>Troubleshooting Microsoft Store: Error Code 0X80072F30</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-you-when-your-apple-iphone-se-2022-is-off-drfone-by-drfone-virtual-ios/"><u>Can Life360 Track You When Your Apple iPhone SE (2022) is off? | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/educations-new-era-vr-integration/"><u>Education's New Era  VR Integration</u></a></li>
<li><a href="https://windows11.techidaily.com/6-cutting-edge-windows-programs-for-media-editing/"><u>6 Cutting-Edge Windows Programs for Media Editing</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-windows-extract-error-1152-quickly/"><u>Eliminating Windows Extract Error 1152 Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/the-clarity-compass-directing-you-through-a-fuzzy-screen-fix-up/"><u>The Clarity Compass: Directing You Through a Fuzzy Screen Fix-Up</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-how-to-take-screenshots-on-xbox-one/"><u>[New] In 2024, How to Take Screenshots on Xbox One</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-how-to-add-selective-color-effect-to-your-videos/"><u>2024 Approved How to Add Selective Color Effect to Your Videos</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-mastering-the-art-of-podcast-name-creation-and-50plus-dynamic-example-titles/"><u>2024 Approved  Mastering the Art of Podcast Name Creation & 50+ Dynamic Example Titles</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-the-ultimate-guide-to-calculating-screen-aspect-ratios/"><u>New The Ultimate Guide to Calculating Screen Aspect Ratios</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-troubleshooting-ms-to-do-sync-failures/"><u>Tips for Troubleshooting MS To-Do Sync Failures</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-external-monitors-without-graphics-card/"><u>Enabling External Monitors without Graphics Card</u></a></li>
<li><a href="https://windows11.techidaily.com/biometric-betrayal-windows-hellos-security-under-fire/"><u>Biometric Betrayal: Windows Hello's Security Under Fire?</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-task-managers-initial-screen-on-win11/"><u>Customizing Task Manager's Initial Screen on Win11</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/enhance-your-vision-a-compreeved-guide-to-tiktok-video-captioning-for-2024/"><u>Enhance Your Vision  A Compreeved Guide to TikTok Video Captioning for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/decreasing-non-essential-tasks-windows-108/"><u>Decreasing Non-Essential Tasks Windows 10/8</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-access-your-outlook-preview/"><u>Unlocking Windows: Access Your Outlook Preview</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-a-functional-taskbar-for-windows-11-tablets/"><u>Activating a Functional Taskbar for Windows 11 Tablets</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-your-pcs-potential-with-a-windows-11-in-place-step-by-step-guide/"><u>Elevating Your PC's Potential with a Windows 11, In-Place Step-by-Step Guide</u></a></li>
<li><a href="https://android-location.techidaily.com/3-effective-methods-to-fake-gps-location-on-android-for-your-oppo-f23-5g-drfone-by-drfone-virtual/"><u>3 Effective Methods to Fake GPS location on Android For your Oppo F23 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-invisibility-of-task-view-on-bar/"><u>Techniques for Invisibility of Task View on Bar</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-earning-on-youtube-a-step-by-step-guide-for-newbies/"><u>[Updated] In 2024, Earning on YouTube  A Step-by-Step Guide for Newbies</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-instagram-videos-wandering-why-angles-change/"><u>[Updated] Instagram  Videos Wandering - Why Angles Change?</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-microsoft-store-error-0x80072efd/"><u>Unblocking Microsoft Store Error 0X80072EFD</u></a></li>
<li><a href="https://windows11.techidaily.com/tutorial-enabling-or-disabling-wi-fi-cost-meter-in-windows-11/"><u>Tutorial: Enabling or Disabling Wi-Fi Cost Meter in Windows 11</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-how-to-merge-flv-files-windows-macandroid-iphone-and-online/"><u>Updated How to Merge FLV Files Windows, Mac，Android, iPhone & Online</u></a></li>
<li><a href="https://windows11.techidaily.com/uninstalling-epic-games-with-ease-on-your-w11-computer/"><u>Uninstalling Epic Games with Ease on Your W11 Computer</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-best-in-class-memetics-engine/"><u>[Updated] Best-in-Class Memetics Engine</u></a></li>
</ul></div>
