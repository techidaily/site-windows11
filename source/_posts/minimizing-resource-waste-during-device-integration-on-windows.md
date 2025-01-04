---
title: Minimizing Resource Waste During Device Integration on Windows
date: 2024-12-27T17:00:41.849Z
updated: 2025-01-03T18:01:01.225Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Minimizing Resource Waste During Device Integration on Windows
excerpt: This Article Describes Minimizing Resource Waste During Device Integration on Windows
keywords: Dev_Waste_Reduction,Win_Resource_Integration,Device_Eco-Efficiency,Resource_Save_Windows,Integration_Less_Trash,Efficient_Dev_Use,Waste_Minimization
thumbnail: https://thmb.techidaily.com/6e2f3010b64553c858c441b2aa0463f3e8a124b61c9d02d5a4f78ba177103c47.png
---

## Minimizing Resource Waste During Device Integration on Windows

 On every Windows startup, the Connected Devices Platform User service uploads the necessary data that connected devices on your computer need. It also authenticates and facilitates communication between them.

 When it consumes too much RAM, it means something could be wrong with the process or your connected devices. Below, we'll show you how to stop Connected Devices Platform User Service from hogging your physical memory.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1CdWd06fCwc?si=wzg-68q0jAksPRXp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Disable Connected Devices Platform User Service

 The simplest way to stop Connected Devices Platform User Service from using too much RAM is to disable it. However, this might cause some unexpected behavior on your computer. And if that happens, you can always enable it again.

 To disable Connected Devices Platform User Service, press **Win + R** to bring up Windows Run. Enter **services.msc** in the text box and then press the **Enter** key on your keyboard.

![services msc Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/services-msc-Windows-11.jpg)

 Find the **Disable Connected Devices Platform User Service** in the list of services and double-click on it. Click on the **Startup type** dropdown and select **Disabled**. Then, under **Service status** in the same window, click on **Stop**.

![the-connected-device-platform-user-service-properties-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-connected-device-platform-user-service-properties-windows.jpg)

 Now, check Task Manager to see if the service is still consuming too much RAM.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SgRVYjqB70s?si=My_2cDvJVdincQRu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Remove the ActivitiesCache.db file

 Some users have reported that deleting the ActivitiesCache.db file on their computer has helped solve the problem. To delete it, start by disabling the Connected Devices Platform User Service, as discussed above. Then, press **Win + R** to open Windows Run, copy and paste **%localappdata%\\ConnectedDevicesPlatform\\** in the text, and then hit the **Enter** key.

![navigating-to-the-connecteddevicesplatform-folder-in-windows-run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/navigating-to-the-connecteddevicesplatform-folder-in-windows-run.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/djPqRkskaBo?si=O6FEI-KVW0HwN417" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 This will open the **ConnectedDevicesPlatform** folder. You'll see several files and folders in there, so open each of the folders and delete the **ActivitiesCache.db** file in all of them.

![the-activitiescab-file-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-activitiescab-file-on-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UJJbj1vbzs8?si=X3zd8thLJKprfuEa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you do, restart your computer and see if Connected Devices Platform User Service is still causing RAM consumption issues.

## 3\. Check for Issues With Your Computer's Hardware

 Sometimes, the problem could arise due to one of your connected devices experiencing a problem. To check if your connected devices are functioning properly, open Device Manager by pressing **Win + R**, enter **devmgmt.msc** in the text box, and then hit the **Enter** key on your keyboard.

![devmgmt.msc in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/devmgmt-msc.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aqeO4ed766s?si=AWtKHxP4hvQRd_lk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In Device Manager, double-click the device you suspect is causing issues. This will open its properties window.

 In the **General** tab of the Properties window, make sure it says **This device is working properly** under **Device status**.

![the-properties-window-of-a-device-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-properties-window-of-a-device-on-windows.jpg)

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
<li><a href="https://instagram-clips.techidaily.com/new-snap-edit-and-share-with-ease-your-4-step-blueprint-for-instagram-gifs-for-2024/"><u>[New] Snap, Edit, and Share with Ease Your 4-Step Blueprint for Instagram GIFs for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-discover-top-6-short-video-download-sites-free/"><u>[Updated] In 2024, Discover Top 6 Short Video Download Sites (FREE)</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-unleash-potential-with-strategic-use-of-snapkit-features/"><u>[Updated] Unleash Potential with Strategic Use of SnapKit Features</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-come-up-with-the-best-pokemon-team-on-realme-gt-neo-5-se-drfone-by-drfone-virtual-android/"><u>How to Come up With the Best Pokemon Team On Realme GT Neo 5 SE? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/making-your-windows-11-pointer-more-visible-and-tactile/"><u>Making Your Windows 11 Pointer More Visible and Tactile</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-with-precision-enriching-windows-explorer-commentary/"><u>Navigate with Precision: Enriching Windows Explorer Commentary</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/order-matters-how-to-experience-the-complete-storyline-of-superman-movies/"><u>Order Matters! How to Experience the Complete Storyline of Superman Movies</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-remedy-for-server-stopped-errors-plaguing-microsoft-store-on-windows-11-and-11/"><u>Quick Remedy for 'Server Stopped' Errors Plaguing Microsoft Store on Windows 11 & 11</u></a></li>
<li><a href="https://buynow-info.techidaily.com/the-ultimate-selection-of-professional-dslrs/"><u>The Ultimate Selection of Professional DSLRs</u></a></li>
<li><a href="https://windows11.techidaily.com/trim-your-pcs-warm-up-3-keys-for-a-speedy-win11-launch/"><u>Trim Your PC's Warm-Up: 3 Keys for a Speedy Win11 Launch</u></a></li>
<li><a href="https://windows11.techidaily.com/yuletide-yields-gifting-windows-software-through-ms-store/"><u>Yuletide Yields: Gifting Windows Software Through MS Store</u></a></li>
</ul></div>

