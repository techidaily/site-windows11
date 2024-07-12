---
title: Optimizing Windows RAM Usage for Device Connectivity Services
date: 2024-07-11T21:36:17.043Z
updated: 2024-07-12T21:36:17.043Z
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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-intuitive-video-collaboration-through-mstream/"><u>[New] 2024 Approved  Intuitive Video Collaboration Through MStream</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-system-crash-code-0xc0000001/"><u>Remedying System Crash Code 0xC0000001</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-chuckle-chronicles-top-10-humoristic-youtube-video-plans/"><u>[Updated] 2024 Approved  Chuckle Chronicles  Top 10 Humoristic YouTube Video Plans</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-batch-convert-heic-images-to-jpeg-format-in-windows-10-and-11/"><u>How to Batch Convert HEIC Images to JPEG Format in Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-your-pcs-protection-the-firewall-guide/"><u>Tailoring Your PC's Protection: The Firewall Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/reversing-error-0x800704cf-in-winstore/"><u>Reversing Error 0X800704CF in WinStore</u></a></li>
<li><a href="https://windows11.techidaily.com/no-more-erratic-arrows-fixes-for-the-frustrated/"><u>No More Erratic Arrows: Fixes for the Frustrated</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-achieve-perfect-youtube-broadcasts-with-superior-webcams/"><u>[Updated] In 2024, Achieve Perfect YouTube Broadcasts with Superior Webcams</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/clinical-manifestations-of-fetal-alcohol-syndrome-for-2024/"><u>Clinical Manifestations of Fetal Alcohol Syndrome for 2024</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/10-iconic-italian-signals-you-must-know/"><u>10 Iconic Italian Signals You Must Know</u></a></li>
<li><a href="https://windows11.techidaily.com/the-comprehensive-manual-for-component-settings-in-w11/"><u>The Comprehensive Manual for Component Settings in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-unmasking-user-ids-a-guide-to-sids-in-windows-11/"><u>The Art of Unmasking User IDs: A Guide to SIDs in Windows 11</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/navigating-instagrams-self-verification-maze-for-2024/"><u>Navigating Instagram's Self-Verification Maze for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/prioritize-and-proliferate-elevating-notifications-in-windows-11/"><u>Prioritize and Proliferate: Elevating Notifications in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-11-error-0x80070570-fixing-damaged-files/"><u>Overcoming Windows 11 Error 0X80070570: Fixing Damaged Files</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-ultimate-guide-to-windows-10-picture-and-media-importer/"><u>[Updated] The Ultimate Guide to Windows 10 Picture & Media Importer</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11-for-spatial-aural-enhancement/"><u>Navigating Windows 11 for Spatial Aural Enhancement</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-remarkable-effects-of-asmr-on-you-for-2024/"><u>The Remarkable Effects of ASMR on You for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-most-popular-tweets-of-2023-viewership-ranked/"><u>[New] Most Popular Tweets of 2023 - Viewership Ranked</u></a></li>
<li><a href="https://location-social.techidaily.com/4-feasible-ways-to-fake-location-on-facebook-for-your-honor-magic-5-lite-drfone-by-drfone-virtual-android/"><u>4 Feasible Ways to Fake Location on Facebook For your Honor Magic 5 Lite | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-art-of-fixing-disk-read-errors/"><u>Master the Art of Fixing Disk Read Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/reinitializing-windows-spooler/"><u>Reinitializing Windows' Spooler</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-comparing-streams-vimeo-versus-youtube/"><u>In 2024, Comparing Streams  Vimeo Versus YouTube</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-apps-and-online-tools-to-track-vivo-y27-4g-phone-withwithout-imei-number-by-drfone-android/"><u>In 2024, Top Apps and Online Tools To Track Vivo Y27 4G Phone With/Without IMEI Number</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-simple-and-effective-ways-to-change-your-country-on-youtube-app-of-your-realme-c53-drfone-by-drfone-virtual-android/"><u>In 2024, Simple and Effective Ways to Change Your Country on YouTube App Of your Realme C53 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/paramount-procedures-for-wiping-your-windows-installation/"><u>Paramount Procedures for Wiping Your Windows Installation</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-pokemon-go-error-12-failed-to-detect-location-on-vivo-v27e-drfone-by-drfone-virtual-android/"><u>In 2024, Pokemon Go Error 12 Failed to Detect Location On Vivo V27e? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-change-your-username-in-windows-11/"><u>How to Change Your Username in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-package-control-with-winget-on-win11/"><u>Navigating Package Control with Winget on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-the-gap-enabling-smooth-steam-connection/"><u>Mending the Gap: Enabling Smooth Steam Connection</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-crafting-captivating-thumbnails-a-comprehensive-guide-for-youtube-creators/"><u>[New] Crafting Captivating Thumbnails  A Comprehensive Guide for YouTube Creators</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-enable-the-home-section-in-the-settings-app-in-windows-11/"><u>How to Enable the Home Section in the Settings App in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-snipeater-glitches-fix-strategies-here/"><u>Navigating SnipEater Glitches: Fix Strategies Here</u></a></li>
<li><a href="https://windows11.techidaily.com/the-comprehensive-guide-to-getting-most-out-of-windows-11s-startup-screen/"><u>The Comprehensive Guide to Getting Most Out of Windows 11'S Startup Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/reset-your-screen-quickly-when-black-hits/"><u>Reset Your Screen Quickly When Black Hits</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-and-streamline-with-win11s-hard-drive-defrag/"><u>Secure & Streamline with Win11's Hard Drive Defrag</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-premier-iphone-x8-series-gif-apps-reviewed/"><u>In 2024, Premier iPhone X/8 Series GIF Apps Reviewed</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-nvidia-control-panel-not-opening-in-windows-11/"><u>How to Fix the NVIDIA Control Panel Not Opening in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/reinvigorating-a-non-functional-windows-taskbar/"><u>Reinvigorating a Non-Functional Windows Taskbar</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-upgrade-or-downgrade-iphone-11-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Upgrade or Downgrade iPhone 11 Without iTunes? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/need-windows-help-find-support-tips-and-solutions/"><u>Need Windows Help? Find Support Tips & Solutions</u></a></li>
</ul></div>
