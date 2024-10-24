---
title: "Lowering Memory Usage: Enhancing Platform User Service Efficiency"
date: 2024-10-22T16:44:10.661Z
updated: 2024-10-24T17:33:34.461Z
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

## 2\. Remove the ActivitiesCache.db file

 Some users have reported that deleting the ActivitiesCache.db file on their computer has helped solve the problem. To delete it, start by disabling the Connected Devices Platform User Service, as discussed above. Then, press **Win + R** to open Windows Run, copy and paste **%localappdata%\\ConnectedDevicesPlatform\\** in the text, and then hit the **Enter** key.

![navigating-to-the-connecteddevicesplatform-folder-in-windows-run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/navigating-to-the-connecteddevicesplatform-folder-in-windows-run.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528696/16446" target="_top" id="1528696">
  <img src="//a.impactradius-go.com/display-ad/16446-1528696" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528696/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 This will open the **ConnectedDevicesPlatform** folder. You'll see several files and folders in there, so open each of the folders and delete the **ActivitiesCache.db** file in all of them.

![the-activitiescab-file-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-activitiescab-file-on-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134224/18498" target="_top" id="2134224">
  <img src="//a.impactradius-go.com/display-ad/18498-2134224" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134224/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you do, restart your computer and see if Connected Devices Platform User Service is still causing RAM consumption issues.

## 3\. Check for Issues With Your Computer's Hardware

 Sometimes, the problem could arise due to one of your connected devices experiencing a problem. To check if your connected devices are functioning properly, open Device Manager by pressing **Win + R**, enter **devmgmt.msc** in the text box, and then hit the **Enter** key on your keyboard.

![devmgmt.msc in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/devmgmt-msc.jpg)

<!-- affiliate ads begin -->
<span id="1982499">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982499.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982499">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982499.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982499%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982499/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In Device Manager, double-click the device you suspect is causing issues. This will open its properties window.

 In the **General** tab of the Properties window, make sure it says **This device is working properly** under **Device status**.

![the-properties-window-of-a-device-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-properties-window-of-a-device-on-windows.jpg)

<!-- affiliate ads begin -->
<span id="1983473">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983473.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983473">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983473.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983473%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983473/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If it doesn't, you will see an error message and a code. Take note of both so you can start troubleshooting the problem. You can start by using [one of the troubleshooters on Windows](https://www.makeuseof.com/run-troubleshooter-windows-10-11/) to check for and fix the hardware problem you're seeing.

 If all the steps above don't work then you might need to [use a system restore point](https://www.makeuseof.com/use-system-restore-windows/) that you created before it started using too much RAM. And if that doesn't work as well, you might have to reset your Windows computer

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
<li><a href="https://article-tips.techidaily.com/new-2024-approved-drone-racers-manual-fundamentals-to-high-scores-and-best-drones/"><u>[New] 2024 Approved Drone Racer's Manual Fundamentals to High Scores and Best Drones</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-elitescreensnap-for-windows-xxp-for-2024/"><u>[New] EliteScreenSnap for Windows X/XP for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-inside-apoyser-detailed-comparison-with-leading-screen-recorder-apps/"><u>[Updated] 2024 Approved Inside Apoyser Detailed Comparison with Leading Screen Recorder Apps</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-freeze-the-frame-choose-the-best-9-gif-recipes-on-windows-systems-for-2024/"><u>[Updated] Freeze the Frame! Choose the Best 9 GIF Recipes on Windows Systems for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-the-confusion-of-microsoft-store-error-0x80072efd/"><u>Clearing Up the Confusion of Microsoft Store Error 0X80072EFD</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-windows-arp-caches-made-simple/"><u>Clearing Windows ARP Caches Made Simple</u></a></li>
<li><a href="https://windows11.techidaily.com/detailed-steps-for-running-sfc-in-windows-os/"><u>Detailed Steps for Running SFC in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-how-to-optimize-win11-taskbar/"><u>Discover How to Optimize Win11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/discovering-surface-laptop-studio-2-near-flawless-for-makers/"><u>Discovering Surface Laptop Studio 2: Near-Flawless for Makers</u></a></li>
<li><a href="https://windows11.techidaily.com/discreet-toolbar-tactics-concealing-items-in-windows-11/"><u>Discreet Toolbar Tactics: Concealing Items in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/display-number-and-caps-lock-status-in-taskbar-tray-win11/"><u>Display Number and Caps Lock Status in Taskbar Tray Win11</u></a></li>
<li><a href="https://driver-error.techidaily.com/easy-troubleshooting-guide-resolving-itbm-driver-errors-instantly/"><u>Easy Troubleshooting Guide: Resolving ITBM Driver Errors Instantly</u></a></li>
<li><a href="https://fox-direct.techidaily.com/in-2024-assessment-of-various-camera-types-for-videos/"><u>In 2024, Assessment of Various Camera Types for Videos</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-will-ispoofer-update-on-apple-iphone-xr-drfone-by-drfone-virtual-ios/"><u>In 2024, Will iSpoofer update On Apple iPhone XR | Dr.fone</u></a></li>
<li><a href="https://discord-videos.techidaily.com/strategic-message-management-expert-tips-for-discord-pinning/"><u>Strategic Message Management Expert Tips for Discord Pinning</u></a></li>
</ul></div>

