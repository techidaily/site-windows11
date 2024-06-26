---
title: Addressing Memory Overuse in User Services and Connected Devices
date: 2024-06-25T12:19:07.311Z
updated: 2024-06-26T12:19:07.311Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Memory Overuse in User Services and Connected Devices
excerpt: This Article Describes Addressing Memory Overuse in User Services and Connected Devices
keywords: Mem+Overuse Soln,User Service Limits,Device Connectivity,Data Usage Controls,Safe Memory Use,Resource Management,Device Efficiency
thumbnail: https://thmb.techidaily.com/298f3a51b5ad96cf99ca78528e1cf7576a8f7bf919402e8696c70895bc723b47.jpg
---

## Addressing Memory Overuse in User Services and Connected Devices

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
<li><a href="https://windows11.techidaily.com/how-to-instantly-generate-multiple-directories-in-modern-windows-environments/"><u>How to Instantly Generate Multiple Directories in Modern Windows Environments</u></a></li>
<li><a href="https://windows11.techidaily.com/speeding-up-typing-typingaids-expertise/"><u>Speeding Up Typing: TypingAid's Expertise</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-utorrent-client-not-downloading-files-or-stuck-on-connecting-to-peers-on-windows/"><u>How to Fix the uTorrent Client Not Downloading Files or Stuck on Connecting to Peers on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/new-horizons-in-customizing-win11-ui/"><u>New Horizons in Customizing Win11 UI</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-errors-in-google-nearby-share-app/"><u>Navigating Windows Errors in Google Nearby Share App</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-photography-fix-overcoming-package-not-registered-issues/"><u>Win11 Photography Fix: Overcoming Package Not Registered Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-quickly-fix-keyboard-issues-in-windows-snipper/"><u>How to Quickly Fix Keyboard Issues in Window's Snipper</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-addressing-undetectable-disks/"><u>Strategies for Addressing Undetectable Disks</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-and-correcting-windows-security-faults-in-windows-11/"><u>Avoiding and Correcting Windows Security Faults in Windows 11</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-the-ultimate-playbook-of-igtv-mastery-top-10-branding-techniques/"><u>[New] The Ultimate Playbook of IGTV Mastery  Top 10 Branding Techniques</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-unleash-your-devices-full-potential-capture-and-store-youtube-streams-flawlessly/"><u>[Updated] In 2024, Unleash Your Device's Full Potential  Capture and Store YouTube Streams Flawlessly</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-find-scream-sound-effect/"><u>2024 Approved Find Scream Sound Effect</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-top-5-gaming-chairs-on-a-shoestring-budget/"><u>2024 Approved  Top 5 Gaming Chairs on a Shoestring Budget</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-anime-inspired-shorts-top-20-trends-on-tiktok/"><u>In 2024, Anime-Inspired Shorts  Top 20 Trends on TikTok</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/echo-elimination-refining-recordings-with-audacity-for-2024/"><u>Echo Elimination  Refining Recordings with Audacity for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-tiktok-to-see-more-content-on-your-htc-u23-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Location on TikTok to See More Content On your HTC U23 Pro | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/capturing-moments-in-time-creating-dynamic-photo-videos-with-pixiz/"><u>Capturing Moments in Time  Creating Dynamic Photo Videos with Pixiz</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-reddits-hidden-gems-6-tactics-that-transform-beginners-into-titans/"><u>In 2024, Reddit's Hidden Gems  6 Tactics That Transform Beginners Into Titans</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-2024-approved-save-big-on-final-cut-pro-education-bundle-deals-inside/"><u>New 2024 Approved Save Big on Final Cut Pro Education Bundle Deals Inside</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>