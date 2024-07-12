---
title: Addressing Memory Overuse in User Services and Connected Devices
date: 2024-07-11T21:38:55.736Z
updated: 2024-07-12T21:38:55.736Z
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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/windows-users-beware-is-yourphoneexe-safe-to-use/"><u>Windows Users Beware: Is YourPhone.exe Safe to Use?</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-support-functionality-in-windows-11-help/"><u>Restoring Support Functionality in Windows 11 Help</u></a></li>
<li><a href="https://windows11.techidaily.com/supercharge-performance-conquering-windows-lag-issues/"><u>Supercharge Performance: Conquering Windows Lag Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-to-troubleshoot-loaded-lol-screens/"><u>Tactics to Troubleshoot Loaded LOL Screens</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-do-you-want-to-loop-a-video-but-arent-sure-where-to-begin-this-is-the-article-for-you-you-may-view-videos-endlessly-without-having-to-worry-abou/"><u>New In 2024, Do You Want to Loop a Video but Arent Sure Where to Begin? This Is the Article for You. You May View Videos Endlessly without Having to Worry About the Loop Options if You Use a Third-Party Video Looper Program</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-your-windows-11-program-choices/"><u>Streamlining Your Windows 11 Program Choices</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-integration-how-to-get-and-run-msibundle-and-appxappxbundles/"><u>Seamless Integration: How to Get & Run MsiBundle & Appx/Appxbundles</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-silent-sounds-on-windows-devices/"><u>Troubleshooting Silent Sounds on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/6-methods-for-reviving-windows-command-line-interface/"><u>6 Methods for Reviving Windows' Command Line Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-login-audit-success-or-no-go-indicators/"><u>Windows Login Audit: Success or No-Go Indicators</u></a></li>
<li><a href="https://windows11.techidaily.com/5-key-fixes-to-stop-rpc-failures-in-windows/"><u>5 Key Fixes to Stop RPC Failures in Windows</u></a></li>
<li><a href="https://audio-editing.techidaily.com/nine-high-performance-audio-recorders-you-cant-overlook-for-live-events-for-2024/"><u>Nine High-Performance Audio Recorders You Cant Overlook for Live Events for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/does-find-my-friends-work-on-xiaomi-13t-drfone-by-drfone-virtual-android/"><u>Does find my friends work on Xiaomi 13T | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-oppo-a58-4g-drfone-by-drfone-virtual-android/"><u>Read This Guide to Find a Reliable Alternative to Fake GPS On Oppo A58 4G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-sleep-mode-anomalies-why-it-frustrates-users/"><u>Windows' Sleep Mode Anomalies: Why It Frustrates Users</u></a></li>
<li><a href="https://windows11.techidaily.com/the-8-different-ways-to-restart-your-windows-computer/"><u>The 8 Different Ways to Restart Your Windows Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/address-common-printer-glitches-in-windows-11/"><u>Address Common Printer Glitches in Windows 11</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-streamlining-avi-to-gif-transitions-on-pcmac-via-filmora-pro/"><u>In 2024, Streamlining AVI to GIF Transitions on PC/Mac via Filmora Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-fixing-0x8009030e-on-virt-environments/"><u>Step-by-Step Guide: Fixing 0X8009030E on Virt Environments</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-transform-your-snapchat-soundtrack-easy-changes-in-just-two-steps/"><u>[New] Transform Your Snapchat Soundtrack  Easy Changes in Just Two Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-unlock-your-computers-windows-license/"><u>Techniques to Unlock Your Computer's Windows License</u></a></li>
<li><a href="https://activate-lock.techidaily.com/unlock-your-device-icloud-dns-bypass-explained-and-tested-plus-easy-alternatives-on-iphone-14-pro-max-by-drfone-ios/"><u>Unlock Your Device iCloud DNS Bypass Explained and Tested, Plus Easy Alternatives On iPhone 14 Pro Max</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-find-wolf-howling-sound-effect-for-2024/"><u>New Find Wolf Howling Sound Effect for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-secrets-to-stable-apex-play-on-windows-11/"><u>Unlocking the Secrets to Stable Apex Play on Windows 11</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unveiling-the-basics-of-vlogging-gear-and-software/"><u>[Updated] Unveiling the Basics of Vlogging Gear & Software</u></a></li>
<li><a href="https://windows11.techidaily.com/software-selection-showdown-on-windows-choc-vs-wm/"><u>Software Selection Showdown on Windows: Choc vs WM</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-full-potential-of-the-windows-11-taskbar/"><u>Unlock the Full Potential of the Windows 11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/reset-windows-strategies-8-techniques-unveiled/"><u>Reset Windows Strategies: 8 Techniques Unveiled</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-snappy-business-ideas-for-profit/"><u>[New] In 2024, Snappy Business Ideas for Profit</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-right-click-customization-compatibility-tool-inclusion/"><u>Windows Right-Click Customization: Compatibility Tool Inclusion</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-gold-class-selection-of-unseen-video-extractors/"><u>[New] Gold-Class Selection of Unseen Video Extractors</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-the-art-of-crafting-compelling-video-covers-for-2024/"><u>[Updated] The Art of Crafting Compelling Video Covers for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/additional-updates-available-in-windows-11s-latest-release/"><u>Additional Updates Available in Windows 11'S Latest Release</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-podcast-powered-by-seo-dominating-search-engine-landscapes/"><u>[New] Podcast Powered by SEO  Dominating Search Engine Landscapes</u></a></li>
<li><a href="https://windows11.techidaily.com/speed-up-taskbar-interaction-enabledisable-ai-on-win-11/"><u>Speed Up Taskbar Interaction: Enable/Disable AI on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/revive-slow-windows-apps-ensure-robust-web-linkage/"><u>Revive Slow Windows Apps: Ensure Robust Web Linkage</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-windows-sluggish-discord-overlay-performance/"><u>Reviving Windows' Sluggish Discord Overlay Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-tasks-in-windows-11-with-a-customized-run-command-setup/"><u>Streamline Tasks in Windows 11 with a Customized Run Command Setup</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-how-to-make-better-facebook-video-ads/"><u>2024 Approved  How to Make Better Facebook Video Ads</u></a></li>
<li><a href="https://windows11.techidaily.com/slowing-down-the-high-life-excess-in-windowed-worlds/"><u>Slowing Down the High Life Excess in Windowed Worlds</u></a></li>
</ul></div>
