---
title: "Lowering Memory Usage: Enhancing Platform User Service Efficiency"
date: 2024-11-12T16:53:30.743Z
updated: 2024-11-15T17:23:02.720Z
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
<span id="1983472">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983472.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983472">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983472.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983472%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983472/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Remove the ActivitiesCache.db file

 Some users have reported that deleting the ActivitiesCache.db file on their computer has helped solve the problem. To delete it, start by disabling the Connected Devices Platform User Service, as discussed above. Then, press **Win + R** to open Windows Run, copy and paste **%localappdata%\\ConnectedDevicesPlatform\\** in the text, and then hit the **Enter** key.

![navigating-to-the-connecteddevicesplatform-folder-in-windows-run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/navigating-to-the-connecteddevicesplatform-folder-in-windows-run.jpg)

 This will open the **ConnectedDevicesPlatform** folder. You'll see several files and folders in there, so open each of the folders and delete the **ActivitiesCache.db** file in all of them.

![the-activitiescab-file-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-activitiescab-file-on-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087234/19272" target="_top" id="2087234">
  <img src="//a.impactradius-go.com/display-ad/19272-2087234" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087234/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you do, restart your computer and see if Connected Devices Platform User Service is still causing RAM consumption issues.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135400/19272" target="_top" id="2135400">
  <img src="//a.impactradius-go.com/display-ad/19272-2135400" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135400/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Check for Issues With Your Computer's Hardware

 Sometimes, the problem could arise due to one of your connected devices experiencing a problem. To check if your connected devices are functioning properly, open Device Manager by pressing **Win + R**, enter **devmgmt.msc** in the text box, and then hit the **Enter** key on your keyboard.

![devmgmt.msc in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/devmgmt-msc.jpg)

 In Device Manager, double-click the device you suspect is causing issues. This will open its properties window.

 In the **General** tab of the Properties window, make sure it says **This device is working properly** under **Device status**.

![the-properties-window-of-a-device-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-properties-window-of-a-device-on-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135402/19272" target="_top" id="2135402">
  <img src="//a.impactradius-go.com/display-ad/19272-2135402" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135402/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-info.techidaily.com/new-2024-approved-expert-tips-mixing-visual-filters-and-melodies-in-windows-10-photos/"><u>[New] 2024 Approved Expert Tips Mixing Visual Filters & Melodies in Windows 10 Photos</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-premiere-reviews-exploring-the-best-8k-cameras/"><u>[New] Premiere Reviews Exploring the Best 8K Cameras</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/diy-filming-hacks-to-learn-and-implement-at-home/"><u>DIY Filming Hacks to Learn and Implement at Home</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/downloading-standardized-youtube-images-with-ease-and-precision/"><u>Downloading Standardized Youtube Images with Ease & Precision</u></a></li>
<li><a href="https://discover-answers.techidaily.com/effortlessly-record-your-screen-on-windows-78-with-step-by-step-guide/"><u>Effortlessly Record Your Screen on Windows 7/8 with Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-resolve-code-0x0001-issue-with-nvidia-experience/"><u>How to Resolve Code 0X0001 Issue with Nvidia Experience</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-top-10-airplay-apps-in-tecno-pop-7-pro-for-streaming-drfone-by-drfone-android/"><u>In 2024, Top 10 AirPlay Apps in Tecno Pop 7 Pro for Streaming | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/non-procreate-windows-drawers-the-top-five/"><u>Non-Procreate Windows Drawers: The Top Five</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-common-windows-key-problems-including-the-enter-key/"><u>Overcoming Common Windows Key Problems, Including the Enter Key</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-app-malfunctions-7-effective-strategies/"><u>Overcoming Windows App Malfunctions: 7 Effective Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/return-to-simplicity-using-icons-for-the-windows-11-search-bar/"><u>Return to Simplicity: Using Icons for the Windows 11 Search Bar</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-instructions-on-leveraging-windows-telnet-client/"><u>Step-by-Step Instructions on Leveraging Windows Telnet Client</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-beginners-guide-to-old-championship-manager/"><u>The Ultimate Beginner's Guide to Old Championship Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-power-of-three-column-widgets-in-win11/"><u>Unlocking the Power of Three-Column Widgets in Win11</u></a></li>
<li><a href="https://fox-that.techidaily.com/unsticking-a-halted-itunes-update-process-6-effective-tips-for-ios-devices/"><u>Unsticking a Halted iTunes Update Process: 6 Effective Tips for iOS Devices</u></a></li>
</ul></div>

