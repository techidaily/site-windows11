---
title: "Lowering Memory Usage: Enhancing Platform User Service Efficiency"
date: 2024-11-21T22:44:45.119Z
updated: 2024-11-24T23:51:24.763Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kiW7sLvL65k?si=IHSeRFsYCrfqpn2o&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now, check Task Manager to see if the service is still consuming too much RAM.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oP8grXxuy2o?si=uIRNhTYbecTcaC7J&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Remove the ActivitiesCache.db file

 Some users have reported that deleting the ActivitiesCache.db file on their computer has helped solve the problem. To delete it, start by disabling the Connected Devices Platform User Service, as discussed above. Then, press **Win + R** to open Windows Run, copy and paste **%localappdata%\\ConnectedDevicesPlatform\\** in the text, and then hit the **Enter** key.

![navigating-to-the-connecteddevicesplatform-folder-in-windows-run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/navigating-to-the-connecteddevicesplatform-folder-in-windows-run.jpg)

 This will open the **ConnectedDevicesPlatform** folder. You'll see several files and folders in there, so open each of the folders and delete the **ActivitiesCache.db** file in all of them.

![the-activitiescab-file-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-activitiescab-file-on-windows.jpg)

 Once you do, restart your computer and see if Connected Devices Platform User Service is still causing RAM consumption issues.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=lhdUUVYMVQjzHXBh&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Check for Issues With Your Computer's Hardware

 Sometimes, the problem could arise due to one of your connected devices experiencing a problem. To check if your connected devices are functioning properly, open Device Manager by pressing **Win + R**, enter **devmgmt.msc** in the text box, and then hit the **Enter** key on your keyboard.

![devmgmt.msc in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/devmgmt-msc.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/43goO8X0iX0?si=48Cqf6td2q_6T6h3&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In Device Manager, double-click the device you suspect is causing issues. This will open its properties window.

 In the **General** tab of the Properties window, make sure it says **This device is working properly** under **Device status**.

![the-properties-window-of-a-device-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-properties-window-of-a-device-on-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DBMTAJBx-X4?si=sje5pFJXiHzJJGbP&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-syncing-songs-to-social-networks-iphonesandroid-approach/"><u>[New] 2024 Approved Syncing Songs to Social Networks IPhones/Android Approach</u></a></li>
<li><a href="https://youtube-data.techidaily.com/n-2024-streamlining-video-production-with-top-mac-mp4-tools/"><u>[New] In 2024, Streamlining Video Production with Top Mac MP4 Tools</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-navigating-windows-for-an-exceptional-listening-experience-top-8/"><u>[New] Navigating Windows for an Exceptional Listening Experience (Top 8)</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-perfect-your-visual-storytelling-inserting-titles-into-photo-videos-on-windows/"><u>[New] Perfect Your Visual Storytelling Inserting Titles Into Photo Videos on Windows</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-creative-vanguard-top-6-redefining-digital-arts/"><u>[Updated] The Creative Vanguard Top 6 Redefining Digital Arts</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-win11-taskbar-icon-dimensions/"><u>Adjusting Win11 Taskbar Icon Dimensions</u></a></li>
<li><a href="https://article-helps.techidaily.com/in-2024-elite-e-learning-leader-labeler/"><u>In 2024, Elite E-Learning Leader Labeler</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/is-the-samsung-55-inch-ru7300-a-cut-above-with-its-4k-and-smart-features-in-depth-review/"><u>Is the Samsung 55-Inch RU7300 a Cut Above with Its 4K and Smart Features? In-Depth Review!</u></a></li>
<li><a href="https://windows11.techidaily.com/muting-windows-update-notifications/"><u>Muting Windows Update Notifications</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-your-computer-no-need-for-windows-11-upgrades/"><u>Optimize Your Computer: No Need for Windows 11 Upgrades</u></a></li>
<li><a href="https://extra-tips.techidaily.com/quick-start-guide-making-your-gifs-count-as-emoji-stickers-in-telegram/"><u>Quick-Start Guide Making Your GIFS Count as Emoji Stickers in Telegram</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-correcting-malwarebytes-call-failure-in-win11win10/"><u>Steps for Correcting Malwarebytes Call Failure in Win11/Win10</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-the-setup-of-new-non-operational-store-programs/"><u>Streamlining the Setup of New, Non-Operational Store Programs</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-nearby-share-for-file-transfers/"><u>Understanding Nearby Share for File Transfers</u></a></li>
</ul></div>

