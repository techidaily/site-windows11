---
title: Troubleshooting Windows 11 Default Application Issues
date: 2025-02-28T08:00:10.378Z
updated: 2025-03-01T18:00:52.780Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Windows 11 Default Application Issues
excerpt: This Article Describes Troubleshooting Windows 11 Default Application Issues
keywords: Win11 Apps Fix Guide,Set Windows 11 Default Program,Resolve Win11 Start Issue,Change Default Windows 11 App,Troubleshoot Win11 Default,Win11 Default Application Repair,Restore Windows 11 Default App
thumbnail: https://thmb.techidaily.com/f1c57303ea622caa2e3702d3e2a77e00493f995e737fa90087cc4940fcb0139c.jpg
---

## Troubleshooting Windows 11 Default Application Issues

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

 This should set the app as the default option for the selected file and link types. However, if you[reset Windows 11 to its default state](https://www.makeuseof.com/windows-11-factory-reset-without-admin-password/) ever, you will lose all these settings.

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
<li><a href="https://article-posts.techidaily.com/updated-2024-approved-efficiently-moving-photosvideos-between-iphones/"><u>[Updated] 2024 Approved Efficiently Moving Photos/Videos Between iPhones</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-in-2024-core-principles-for-online-storytelling-craftsmanship/"><u>[Updated] In 2024, Core Principles for Online Storytelling Craftsmanship</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-video-editors-unite-learn-image-upload-on-youtube/"><u>[Updated] In 2024, Video Editors Unite! Learn Image Upload on YouTube</u></a></li>
<li><a href="https://some-techniques.techidaily.com/expert-strategies-for-seamless-green-screening-in-kinemaster-for-2024/"><u>Expert Strategies for Seamless Green Screening in KineMaster for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tune-your-pointers-response-time-and-visibility-on-windows-11/"><u>Fine-Tune Your Pointer's Response Time and Visibility on Windows 11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/how-to-set-up-zoom-video-meeting/"><u>How to Set up Zoom Video Meeting</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-strategies-for-maximizing-your-video-footprint-in-instagram/"><u>In 2024, Strategies for Maximizing Your Video Footprint in Instagram</u></a></li>
<li><a href="https://windows11.techidaily.com/invisible-exit-command-secreting-windows-11-power-off/"><u>Invisible Exit Command: Secreting Windows 11 Power Off</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-defenders-barrier-on-third-party-av-software/"><u>Overcoming Defender's Barrier on Third-Party AV Software</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-malfunction-win1011s-ccleaner-complications/"><u>Overcoming Malfunction: Win10/11's CCleaner Complications</u></a></li>
<li><a href="https://fox-blue.techidaily.com/tactics-for-pinpointing-ideal-podcast-debut-days-for-2024/"><u>Tactics for Pinpointing Ideal Podcast Debut Days for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-finest-9-digital-places-for-harvesting-futuristic-3d-typefaces-for-2024/"><u>The Finest 9 Digital Places for Harvesting Futuristic 3D Typefaces for 2024</u></a></li>
<li><a href="https://discover-community.techidaily.com/top-12-animated-series-in-2d-art-updated-list-2vear-2024-movavi/"><u>Top 12 Animated Series in 2D Art - Updated List 2Vear 2024 | Movavi</u></a></li>
<li><a href="https://windows11.techidaily.com/transition-to-new-background-in-winterminal/"><u>Transition to New Background in WinTerminal</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-wonders-creating-and-interpreting-reports/"><u>Unveiling Windows Wonders: Creating & Interpreting Reports</u></a></li>
</ul></div>

