---
title: Reducing RAM Burden in Cross-Device Service Platforms on Windows
date: 2024-12-23T19:33:27.355Z
updated: 2024-12-25T16:47:44.546Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reducing RAM Burden in Cross-Device Service Platforms on Windows
excerpt: This Article Describes Reducing RAM Burden in Cross-Device Service Platforms on Windows
keywords: Reduce RAM Usage,Cross-Platform Optimization,Windows Memory Efficiency,Device Service RAM Management,Platform Performance Improvement,Reducing System Burden,Enhancing Windows Services
thumbnail: https://thmb.techidaily.com/0c8f696950ea736c2174f2d7e8a74906124afdbd8faac5e2796b198a9b431fdb.jpg
---

## Reducing RAM Burden in Cross-Device Service Platforms on Windows

 On every Windows startup, the Connected Devices Platform User service uploads the necessary data that connected devices on your computer need. It also authenticates and facilitates communication between them.

 When it consumes too much RAM, it means something could be wrong with the process or your connected devices. Below, we'll show you how to stop Connected Devices Platform User Service from hogging your physical memory.

## 1\. Disable Connected Devices Platform User Service

 The simplest way to stop Connected Devices Platform User Service from using too much RAM is to disable it. However, this might cause some unexpected behavior on your computer. And if that happens, you can always enable it again.

 To disable Connected Devices Platform User Service, press **Win + R** to bring up Windows Run. Enter **services.msc** in the text box and then press the **Enter** key on your keyboard.

![services msc Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/services-msc-Windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RhLjZsruC9M?si=-861oUSfrUde2Ykt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Find the **Disable Connected Devices Platform User Service** in the list of services and double-click on it. Click on the **Startup type** dropdown and select **Disabled**. Then, under **Service status** in the same window, click on **Stop**.

![the-connected-device-platform-user-service-properties-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-connected-device-platform-user-service-properties-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Wy0uYNNdMDM?si=5ir7EHlr0CkpcYOT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now, check Task Manager to see if the service is still consuming too much RAM.

## 2\. Remove the ActivitiesCache.db file

 Some users have reported that deleting the ActivitiesCache.db file on their computer has helped solve the problem. To delete it, start by disabling the Connected Devices Platform User Service, as discussed above. Then, press **Win + R** to open Windows Run, copy and paste **%localappdata%\\ConnectedDevicesPlatform\\** in the text, and then hit the **Enter** key.

![navigating-to-the-connecteddevicesplatform-folder-in-windows-run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/navigating-to-the-connecteddevicesplatform-folder-in-windows-run.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GPk8_xpN_rA?si=YbAdgsjAKsCn_UsB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 This will open the **ConnectedDevicesPlatform** folder. You'll see several files and folders in there, so open each of the folders and delete the **ActivitiesCache.db** file in all of them.

![the-activitiescab-file-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-activitiescab-file-on-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=heERQcpMi77lqToE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you do, restart your computer and see if Connected Devices Platform User Service is still causing RAM consumption issues.

## 3\. Check for Issues With Your Computer's Hardware

 Sometimes, the problem could arise due to one of your connected devices experiencing a problem. To check if your connected devices are functioning properly, open Device Manager by pressing **Win + R**, enter **devmgmt.msc** in the text box, and then hit the **Enter** key on your keyboard.

![devmgmt.msc in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/devmgmt-msc.jpg)

 In Device Manager, double-click the device you suspect is causing issues. This will open its properties window.

 In the **General** tab of the Properties window, make sure it says **This device is working properly** under **Device status**.

![the-properties-window-of-a-device-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-properties-window-of-a-device-on-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JlX-G8rBs1w?si=iIhUoWAq5x3YK9rA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-hovers.techidaily.com/updated-easy-voice-adjustment-for-ps5-and-ps4-for-2024/"><u>[Updated] Easy Voice Adjustment for PS5 & PS4 for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-secure-and-document-your-zoom-conferences/"><u>[Updated] Secure & Document Your Zoom Conferences</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-guide-on-faking-your-location-in-mozilla-firefox-on-htc-u23-drfone-by-drfone-virtual-android/"><u>A Detailed Guide on Faking Your Location in Mozilla Firefox On HTC U23 | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/complete-studio-exploration-in-depth-xvideoexamine-for-2024/"><u>Complete Studio Exploration In-Depth XVideoExamine for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-video-playback-issues-with-error-0xc10100bf/"><u>Fixing Video Playback Issues with Error 0XC10100BF</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-fix-corrupt-video-files-of-note-30-using-video-repair-utility-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>How to Fix corrupt video files of Note 30 using Video Repair Utility on Windows?</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-windows-activation-error-0x803f700f/"><u>How to Fix the Windows Activation Error 0X803F700F</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-speed-up-your-windows-10-or-11-boot-process-expert-advice-here/"><u>How to Speed Up Your Windows 10 or 11 Boot Process – Expert Advice Here</u></a></li>
<li><a href="https://windows11.techidaily.com/simplified-steps-to-alter-your-cursors-look/"><u>Simplified Steps to Alter Your Cursor's Look</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/trouble-with-apple-iphone-se-swipe-up-try-these-11-solutions-drfone-by-drfone-ios/"><u>Trouble with Apple iPhone SE Swipe-Up? Try These 11 Solutions | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-upgraded-widget-choice-interface-in-win11/"><u>Unlocking Upgraded Widget Choice Interface in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/your-guide-to-next-gen-computing-at-ifa-2023/"><u>Your Guide to Next-Gen Computing at IFA 2023</u></a></li>
</ul></div>

