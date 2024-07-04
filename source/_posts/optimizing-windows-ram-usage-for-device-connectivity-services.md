---
title: Optimizing Windows RAM Usage for Device Connectivity Services
date: 2024-06-25T12:16:50.639Z
updated: 2024-06-26T12:16:50.639Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Optimizing Windows RAM Usage for Device Connectivity Services
excerpt: This Article Describes Optimizing Windows RAM Usage for Device Connectivity Services
keywords: Optimal RAM Use,Windows Connectivity,RAM Efficiency,System Performance,Device Linking,RAM Management,Service Speedup
thumbnail: https://thmb.techidaily.com/729729197b22ccebe2bbfe977aa7bc85dbf69a72f989ad7aa422cd7f1d76fb4a.jpg
---

## Optimizing Windows RAM Usage for Device Connectivity Services

 On every Windows startup, the Connected Devices Platform User service uploads the necessary data that connected devices on your computer need. It also authenticates and facilitates communication between them.

 When it consumes too much RAM, it means something could be wrong with the process or your connected devices. Below, we'll show you how to stop Connected Devices Platform User Service from hogging your physical memory.

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

 This will open the **ConnectedDevicesPlatform** folder. You'll see several files and folders in there, so open each of the folders and delete the **ActivitiesCache.db** file in all of them.

![the-activitiescab-file-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-activitiescab-file-on-windows.jpg)

 Once you do, restart your computer and see if Connected Devices Platform User Service is still causing RAM consumption issues.

## 3\. Check for Issues With Your Computer's Hardware

 Sometimes, the problem could arise due to one of your connected devices experiencing a problem. To check if your connected devices are functioning properly, open Device Manager by pressing **Win + R**, enter **devmgmt.msc** in the text box, and then hit the **Enter** key on your keyboard.

![devmgmt.msc in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/devmgmt-msc.jpg)

 In Device Manager, double-click the device you suspect is causing issues. This will open its properties window.

 In the **General** tab of the Properties window, make sure it says **This device is working properly** under **Device status**.

![the-properties-window-of-a-device-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-properties-window-of-a-device-on-windows.jpg)

 If it doesn't, you will see an error message and a code. Take note of both so you can start troubleshooting the problem. You can start by using [one of the troubleshooters on Windows](https://www.makeuseof.com/run-troubleshooter-windows-10-11/) to check for and fix the hardware problem you're seeing.

 If all the steps above don't work then you might need to [use a system restore point](https://www.makeuseof.com/use-system-restore-windows/) that you created before it started using too much RAM. And if that doesn't work as well, you might have to reset your Windows computer

## Free Your RAM From Connected Devices Platform User Service

 No process is entitled to consume too much RAM on your computer. And if you find that Connected Devices Platform User Service is doing just that, you can disable it, delete the ActivitiesCache.db file, or see if there's something wrong with your hardware. Hopefully, one of those things will help stop the process hogging the RAM.

 When it consumes too much RAM, it means something could be wrong with the process or your connected devices. Below, we'll show you how to stop Connected Devices Platform User Service from hogging your physical memory.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/unlock-workspace-potential-discover-the-best-window-folder-methods/"><u>Unlock Workspace Potential: Discover the Best Window Folder Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/learn-9-keys-to-tweaking-windows-audio-properties/"><u>Learn 9 Keys to Tweaking Windows Audio Properties</u></a></li>
<li><a href="https://windows11.techidaily.com/tackle-interruptexception-in-win11-blue-screen/"><u>Tackle INTERRUPT_EXCEPTION in Win11 Blue Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/classic-interface-reclamation-tips/"><u>Classic Interface Reclamation Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/synchronize-the-seconds-windows-time-repair-guide/"><u>Synchronize the Seconds: Windows Time Repair Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-windows-11-audio-adjustment-tools/"><u>Unveiling the Windows 11 Audio Adjustment Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/curing-stale-boot-option-imagery/"><u>Curing Stale BOOT Option Imagery</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-guide-forcibly-disabledelete-printer-on-pc/"><u>Immediate Guide: Forcibly Disable/Delete Printer on PC</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-the-insiders-manual-posting-youtube-videos-on-yourfb-page/"><u>2024 Approved  The Insider's Manual  Posting YouTube Videos on YourFB Page</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-mp3-to-mp4-conversion-checklist-dont-forget-these-crucial-steps/"><u>New 2024 Approved MP3 to MP4 Conversion Checklist Dont Forget These Crucial Steps</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-navigating-social-surveys-instagram-stories-edition/"><u>[New] In 2024, Navigating Social Surveys  Instagram Stories Edition</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-8-plus-apples-new-iphone-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone 8 Plus, Apples New iPhone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-transformative-techniques-applying-luts-for-dynamic-effects-in-after-effects/"><u>[New] Transformative Techniques  Applying LUTs for Dynamic Effects in After Effects</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-forgotten-the-voicemail-password-of-realme-12-proplus-5g-try-these-fixes-by-drfone-android/"><u>In 2024, Forgotten The Voicemail Password Of Realme 12 Pro+ 5G? Try These Fixes</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/updated-how-to-auto-translate-youtube-videos-into-different-languages-for-2024/"><u>Updated How To Auto Translate YouTube Videos Into Different Languages for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-best-websites-to-access-text-styling-resources/"><u>2024 Approved  Best Websites to Access Text Styling Resources</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unlock-the-potential-of-your-podcast-covers-now/"><u>[Updated] Unlock the Potential of Your Podcast Covers Now</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>