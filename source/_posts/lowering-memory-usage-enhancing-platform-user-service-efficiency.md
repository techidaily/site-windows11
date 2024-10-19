---
title: "Lowering Memory Usage: Enhancing Platform User Service Efficiency"
date: 2024-10-14T16:38:30.615Z
updated: 2024-10-19T02:20:59.482Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Lowering Memory Usage: Enhancing Platform User Service Efficiency"
excerpt: "This Article Describes Lowering Memory Usage: Enhancing Platform User Service Efficiency"
keywords: LowMemoryOptimization,EfficientUserService,MemoryUsageReduction,ServiceEfficiencyBoost,EnhancedPlatformPerformance,UserExperienceImprovement,OptimalResourceManagement
thumbnail: https://thmb.techidaily.com/8984f3e954dc5418ee2dd74f85120f2ef763c0382a218a0a60fa194808ade857.jpg
---

## Lowering Memory Usage: Enhancing Platform User Service Efficiency

 On every Windows startup, the Connected Devices Platform User service uploads the necessary data that connected devices on your computer need. It also authenticates and facilitates communication between them.

 When it consumes too much RAM, it means something could be wrong with the process or your connected devices. Below, we'll show you how to stop Connected Devices Platform User Service from hogging your physical memory.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Disable Connected Devices Platform User Service

 The simplest way to stop Connected Devices Platform User Service from using too much RAM is to disable it. However, this might cause some unexpected behavior on your computer. And if that happens, you can always enable it again.

 To disable Connected Devices Platform User Service, press **Win + R** to bring up Windows Run. Enter **services.msc** in the text box and then press the **Enter** key on your keyboard.

![services msc Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/services-msc-Windows-11.jpg)

 Find the **Disable Connected Devices Platform User Service** in the list of services and double-click on it. Click on the **Startup type** dropdown and select **Disabled**. Then, under **Service status** in the same window, click on **Stop**.

![the-connected-device-platform-user-service-properties-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-connected-device-platform-user-service-properties-windows.jpg)

 Now, check Task Manager to see if the service is still consuming too much RAM.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934183/19272" target="_top" id="1934183">
  <img src="//a.impactradius-go.com/display-ad/19272-1934183" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934183/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Remove the ActivitiesCache.db file

 Some users have reported that deleting the ActivitiesCache.db file on their computer has helped solve the problem. To delete it, start by disabling the Connected Devices Platform User Service, as discussed above. Then, press **Win + R** to open Windows Run, copy and paste **%localappdata%\\ConnectedDevicesPlatform\\** in the text, and then hit the **Enter** key.

![navigating-to-the-connecteddevicesplatform-folder-in-windows-run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/navigating-to-the-connecteddevicesplatform-folder-in-windows-run.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137220/26400" target="_top" id="2137220">
  <img src="//a.impactradius-go.com/display-ad/26400-2137220" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137220/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 This will open the **ConnectedDevicesPlatform** folder. You'll see several files and folders in there, so open each of the folders and delete the **ActivitiesCache.db** file in all of them.

![the-activitiescab-file-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-activitiescab-file-on-windows.jpg)

 Once you do, restart your computer and see if Connected Devices Platform User Service is still causing RAM consumption issues.

## 3\. Check for Issues With Your Computer's Hardware

 Sometimes, the problem could arise due to one of your connected devices experiencing a problem. To check if your connected devices are functioning properly, open Device Manager by pressing **Win + R**, enter **devmgmt.msc** in the text box, and then hit the **Enter** key on your keyboard.

![devmgmt.msc in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/devmgmt-msc.jpg)

 In Device Manager, double-click the device you suspect is causing issues. This will open its properties window.

 In the **General** tab of the Properties window, make sure it says **This device is working properly** under **Device status**.

![the-properties-window-of-a-device-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-properties-window-of-a-device-on-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1576474/17382" target="_top" id="1576474">
  <img src="//a.impactradius-go.com/display-ad/17382-1576474" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1576474/17382" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If it doesn't, you will see an error message and a code. Take note of both so you can start troubleshooting the problem. You can start by using [one of the troubleshooters on Windows](https://www.makeuseof.com/run-troubleshooter-windows-10-11/) to check for and fix the hardware problem you're seeing.

 If all the steps above don't work then you might need to [use a system restore point](https://www.makeuseof.com/use-system-restore-windows/) that you created before it started using too much RAM. And if that doesn't work as well, you might have to reset your Windows computer

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135351/19272" target="_top" id="2135351">
  <img src="//a.impactradius-go.com/display-ad/19272-2135351" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135351/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Free Your RAM From Connected Devices Platform User Service

 No process is entitled to consume too much RAM on your computer. And if you find that Connected Devices Platform User Service is doing just that, you can disable it, delete the ActivitiesCache.db file, or see if there's something wrong with your hardware. Hopefully, one of those things will help stop the process hogging the RAM.

 When it consumes too much RAM, it means something could be wrong with the process or your connected devices. Below, we'll show you how to stop Connected Devices Platform User Service from hogging your physical memory.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-resources.techidaily.com/new-audio-adventures-begin-top-10-melodies-for-podcast-intros/"><u>[New] Audio Adventures Begin Top 10 Melodies for Podcast Intros</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-eizos-masterpiece-delving-into-the-world-of-4k-cg318-4k/"><u>[New] EIZO's Masterpiece Delving Into the World of 4K CG318-4K</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-unveiling-elite-choices-a-guide-to-hdr-cameras/"><u>[New] Unveiling Elite Choices A Guide to HDR Cameras</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-mastering-zoom-for-effective-fb-live-broadcasts/"><u>[Updated] In 2024, Mastering Zoom for Effective FB Live Broadcasts</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-retrieve-lost-contacts-from-oppo-find-x6-pro-by-fonelab-android-recover-contacts/"><u>Best Android Data Recovery - Retrieve Lost Contacts from Oppo Find X6 Pro.</u></a></li>
<li><a href="https://win-guides.techidaily.com/boost-your-text-editing-experience-the-latest-update-for-emeditors-search-toolbar-feature/"><u>Boost Your Text Editing Experience - The Latest Update for EmEditor's Search Toolbar Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/financial-success-in-w11-microsofts-blueprint/"><u>Financial Success in W11: Microsoft's Blueprint</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-jump-start-your-pc-beyond-s-mode-limits/"><u>How to Jump-Start Your PC Beyond S Mode Limits</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-mastering-lock-screen-settings-how-to-enable-and-disable-on-google-pixel-8-pro-by-drfone-android/"><u>In 2024, Mastering Lock Screen Settings How to Enable and Disable on Google Pixel 8 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/master-cortana-archive-windows-based-steps/"><u>Master Cortana Archive: Windows-Based Steps</u></a></li>
<li><a href="https://win-webster.techidaily.com/mastering-solutions-for-inaccessible-sd-media-how-to-fix-non-reading-memory-cards-on-computers/"><u>Mastering Solutions for Inaccessible SD Media: How to Fix Non-Reading Memory Cards on Computers</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11-folder-access-top-techniques-explored/"><u>Mastering Windows 11 Folder Access: Top Techniques Explored</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-wpm-in-windows-11-a-step-by-step-guide/"><u>Mastering WPM in Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-of-common-obs-error-fixes-on-windows-11/"><u>Mastery of Common OBS Error Fixes on Windows 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/oppo-find-x6-pro-support-turn-off-screen-lock-by-drfone-android-unlock-android-unlock/"><u>Oppo Find X6 Pro support - Turn Off Screen Lock.</u></a></li>
<li><a href="https://windows11.techidaily.com/stepwise-method-to-activate-dark-mode-in-notepad-on-windows-11-pcs/"><u>Stepwise Method to Activate Dark Mode in Notepad on Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-remedying-windows-11-logins/"><u>Understanding & Remedying Windows 11 Logins</u></a></li>
</ul></div>

