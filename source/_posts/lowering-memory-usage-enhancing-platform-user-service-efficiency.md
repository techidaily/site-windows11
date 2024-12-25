---
title: "Lowering Memory Usage: Enhancing Platform User Service Efficiency"
date: 2024-12-24T16:26:57.728Z
updated: 2024-12-25T20:03:10.210Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5FWCFI3f_cs?si=Kt2Onr_E4c616tbH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Disable Connected Devices Platform User Service

 The simplest way to stop Connected Devices Platform User Service from using too much RAM is to disable it. However, this might cause some unexpected behavior on your computer. And if that happens, you can always enable it again.

 To disable Connected Devices Platform User Service, press **Win + R** to bring up Windows Run. Enter **services.msc** in the text box and then press the **Enter** key on your keyboard.

![services msc Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/services-msc-Windows-11.jpg)

 Find the **Disable Connected Devices Platform User Service** in the list of services and double-click on it. Click on the **Startup type** dropdown and select **Disabled**. Then, under **Service status** in the same window, click on **Stop**.

![the-connected-device-platform-user-service-properties-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-connected-device-platform-user-service-properties-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q-mXUpVQijU?si=f1MzflPJ8-bD2_iQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now, check Task Manager to see if the service is still consuming too much RAM.

## 2\. Remove the ActivitiesCache.db file

 Some users have reported that deleting the ActivitiesCache.db file on their computer has helped solve the problem. To delete it, start by disabling the Connected Devices Platform User Service, as discussed above. Then, press **Win + R** to open Windows Run, copy and paste **%localappdata%\\ConnectedDevicesPlatform\\** in the text, and then hit the **Enter** key.

![navigating-to-the-connecteddevicesplatform-folder-in-windows-run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/navigating-to-the-connecteddevicesplatform-folder-in-windows-run.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DxUX4R6Cf7c?si=prHevNQJivSkIfUt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/f3PFn06LijE?si=zHrmlTOzrKxXe-k4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If it doesn't, you will see an error message and a code. Take note of both so you can start troubleshooting the problem. You can start by using [one of the troubleshooters on Windows](https://www.makeuseof.com/run-troubleshooter-windows-10-11/) to check for and fix the hardware problem you're seeing.

 If all the steps above don't work then you might need to [use a system restore point](https://www.makeuseof.com/use-system-restore-windows/) that you created before it started using too much RAM. And if that doesn't work as well, you might have to reset your Windows computer

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HaM818fFKXQ?si=ZZLA4lFSHSgCpSE0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://some-skills.techidaily.com/new-understanding-cloud-pricing-models-and-savings-strategies/"><u>[New] Understanding Cloud Pricing Models & Savings Strategies</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-cutting-edge-video-editing-in-youtube-studio-explained-for-2024/"><u>[Updated] Cutting-Edge Video Editing in YouTube Studio Explained for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-elevate-your-online-presence-advanced-techniques-in-zoom-video-sharing/"><u>[Updated] Elevate Your Online Presence Advanced Techniques in Zoom Video Sharing</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-navigating-the-world-of-youtube-live-visual-representations/"><u>[Updated] Navigating the World of YouTube Live Visual Representations</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-sony-s6700-latest-features-reviewed/"><u>In 2024, Sony S6700 Latest Features Reviewed</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-the-cutting-edge-gaming-earpieces-for-youtubers/"><u>In 2024, The Cutting-Edge Gaming Earpieces for YouTubers</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-will-ispoofer-update-on-gionee-f3-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Will iSpoofer update On Gionee F3 Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/inside-look-windows-executable-and-linker-format-pe/"><u>Inside Look: Windows' Executable & Linker Format (PE)</u></a></li>
<li><a href="https://win-solutions.techidaily.com/marvel-gamers-rejoice-fix-these-crashes-in-guardians-of-the-galaxy-for-pc/"><u>Marvel Gamers Rejoice! - Fix These Crashes in Guardians of the Galaxy for PC</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-art-of-ping-utilization-windows-style/"><u>Navigating the Art of Ping Utilization Windows-Style</u></a></li>
<li><a href="https://windows11.techidaily.com/rapid-rendezvous-initiating-startup-unlocking-notepad/"><u>Rapid Rendezvous: Initiating Startup, Unlocking Notepad</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-disabled-pin-removal-tool-on-windows-11-pc/"><u>Reviving Disabled PIN Removal Tool on Windows 11 PC</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-way-to-refresh-your-windows-update-system/"><u>Seamless Way to Refresh Your Windows Update System</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-to-microsoft-error-code-x00000000/"><u>Solutions to Microsoft Error Code X00000000</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-discrepancies-in-discords-windows-game-detection/"><u>Troubleshooting Discrepancies in Discord's Windows Game Detection</u></a></li>
<li><a href="https://windows11.techidaily.com/unblock-file-uploads-mastering-chromes-sync-on-a-win-os/"><u>Unblock File Uploads: Mastering Chrome's Sync on a Win OS</u></a></li>
<li><a href="https://sound-issues.techidaily.com/windows-biometrics-not-functioning/"><u>Windows Biometrics Not Functioning</u></a></li>
</ul></div>

