---
title: Optimizing Windows RAM Usage for Device Connectivity Services
date: 2024-08-15T15:56:09.803Z
updated: 2024-08-16T15:56:09.803Z
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## 2\. Remove the ActivitiesCache.db file

 Some users have reported that deleting the ActivitiesCache.db file on their computer has helped solve the problem. To delete it, start by disabling the Connected Devices Platform User Service, as discussed above. Then, press **Win + R** to open Windows Run, copy and paste **%localappdata%\\ConnectedDevicesPlatform\\** in the text, and then hit the **Enter** key.

![navigating-to-the-connecteddevicesplatform-folder-in-windows-run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/navigating-to-the-connecteddevicesplatform-folder-in-windows-run.jpg)
<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 This will open the **ConnectedDevicesPlatform** folder. You'll see several files and folders in there, so open each of the folders and delete the **ActivitiesCache.db** file in all of them.

![the-activitiescab-file-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-activitiescab-file-on-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you do, restart your computer and see if Connected Devices Platform User Service is still causing RAM consumption issues.

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Check for Issues With Your Computer's Hardware

 Sometimes, the problem could arise due to one of your connected devices experiencing a problem. To check if your connected devices are functioning properly, open Device Manager by pressing **Win + R**, enter **devmgmt.msc** in the text box, and then hit the **Enter** key on your keyboard.

![devmgmt.msc in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/devmgmt-msc.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->

 In Device Manager, double-click the device you suspect is causing issues. This will open its properties window.

 In the **General** tab of the Properties window, make sure it says **This device is working properly** under **Device status**.

![the-properties-window-of-a-device-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-properties-window-of-a-device-on-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
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
<li><a href="https://youtube-sure.techidaily.com/024-approved-tap-into-tagging-techniques-for-6kplus-youtube-vistas/"><u>[New] 2024 Approved  Tap Into #Tagging Techniques for $6K+ YouTube Vistas</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-best-10-creative-tiktok-filters-transforming-feeds/"><u>[New] Best 10 Creative TikTok Filters Transforming Feeds</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ilmmakers-lounge-app/"><u>[New] Filmmaker's Lounge App</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-instagram-stories-screen-capture-made-simple/"><u>[New] In 2024, Instagram Stories Screen Capture Made Simple</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-webcam-innovation-for-everyday-life-for-2024/"><u>[New] Webcam Innovation for Everyday Life for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-echoes-of-entertainment-discovering-6-free-android-apps-for-your-youtube-playlists-for-2024/"><u>[Updated] Echoes of Entertainment  Discovering 6 Free Android Apps for Your YouTube Playlists for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerated-cross-language-compreinasion-via-windows-keyboard-tricks/"><u>Accelerated Cross-Language Compreinasion via Windows Keyboard Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/accurate-assessment-of-system-resources-in-windows-11/"><u>Accurate Assessment of System Resources in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/adeptly-disguise-wireless-networks-with-windows/"><u>Adeptly Disguise Wireless Networks with Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/beat-the-annoying-keeps-showing-up-a-comprehveiw-on-solving-usb-recognition-problems/"><u>Beat the Annoying Keeps Showing Up: A Comprehveiw on Solving USB Recognition Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/black-friday-extravaganza-save-big-612-forever-win10/"><u>Black Friday Extravaganza: Save Big - $6.12 Forever Win10</u></a></li>
<li><a href="https://windows11.techidaily.com/dealing-with-misentered-characters-in-windows-os/"><u>Dealing with Misentered Characters in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/digital-drawings-redefined-top-7-windows-10-art-tools-for-you/"><u>Digital Drawings Redefined: Top 7 Windows 10 Art Tools for You</u></a></li>
<li><a href="https://windows11.techidaily.com/dodging-unsupported-issue-in-windows-5-fixes/"><u>Dodging 'Unsupported' Issue in Windows: 5 Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-desktop-experience-fixing-this-pc-spotlight/"><u>Elevate Desktop Experience: Fixing 'This PC' Spotlight</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-pubg-save-problems-on-windows-systems/"><u>Eliminating PUBG Save Problems on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-reliability-of-your-windows-interface/"><u>Enhancing Reliability of Your Windows Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/expedite-photo-corrections-ps-and-windows-strategy/"><u>Expedite Photo Corrections: PS & Windows Strategy</u></a></li>
<li><a href="https://howto.techidaily.com/fix-the-error-of-unfortunately-the-processcomandroidphone-has-stopped-on-oneplus-12-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix the Error of Unfortunately the Process.com.android.phone Has Stopped on OnePlus 12 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/flawless-system-transition-mastering-windows-11s-in-place-update-process/"><u>Flawless System Transition: Mastering Windows 11'S In-Place Update Process</u></a></li>
<li><a href="https://android-unlock.techidaily.com/forgotten-the-voicemail-password-of-samsung-galaxy-s23-tactical-edition-try-these-fixes-by-drfone-android/"><u>Forgotten The Voicemail Password Of Samsung Galaxy S23 Tactical Edition? Try These Fixes</u></a></li>
<li><a href="https://extra-tips.techidaily.com/graphic-geniuses-discover-the-best-10-free-sketch-for-mac/"><u>Graphic Geniuses  Discover the Best 10 Free Sketch for Mac</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-can-i-catch-the-regional-pokemon-without-traveling-on-xiaomi-redmi-13c-5g-drfone-by-drfone-virtual-android/"><u>How Can I Catch the Regional Pokémon without Traveling On Xiaomi Redmi 13C 5G | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-gps-location-on-apple-iphone-xs-max-easily-and-safely-drfone-by-drfone-virtual-ios/"><u>How to Change GPS Location on Apple iPhone XS Max Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-change-the-windows-subsystem-for-androids-resource-usage/"><u>How to Change the Windows Subsystem for Android's Resource Usage</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-obtain-and-update-hp-laserjet-1320-drivers-on-a-windows-machine/"><u>How to Obtain & Update HP LaserJet 1320 Drivers on a Windows Machine</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-apple-iphone-14-pro-ios-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair Apple iPhone 14 Pro iOS? | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-complete-guide-for-iphone-11-lock-screen-by-drfone-ios/"><u>In 2024, Complete Guide For iPhone 11 Lock Screen</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/in-2024-construct-memetic-mirth/"><u>In 2024, Construct Memetic Mirth</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-fix-vivo-y27s-find-my-friends-no-location-found-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix Vivo Y27s Find My Friends No Location Found? | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-open-your-iphone-se-2022-without-a-home-button-drfone-by-drfone-ios/"><u>In 2024, How To Open Your iPhone SE (2022) Without a Home Button | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-reset-apple-id-and-apple-password-from-apple-iphone-x-by-drfone-ios/"><u>In 2024, How to Reset Apple ID and Apple Password From Apple iPhone X</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-unlocking-the-power-of-smart-lock-a-beginners-guide-for-realme-users-by-drfone-android/"><u>In 2024, Unlocking the Power of Smart Lock A Beginners Guide for Realme Users</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-unveiling-the-secrets-of-effective-screencasts/"><u>In 2024, Unveiling the Secrets of Effective Screencasts</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-files-6-methods-to-retrieve-windows-11-paths/"><u>Mastering Files: 6 Methods to Retrieve Windows 11 Paths</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-window-icon-positions/"><u>Mastery Over Window Icon Positions</u></a></li>
<li><a href="https://windows11.techidaily.com/microsofts-surface-studio-2-a-step-towards-perfection/"><u>Microsoft's Surface Studio 2 - A Step Towards Perfection?</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11s-s-mode-is-it-worth-considering/"><u>Navigating Windows 11'S 'S Mode': Is It Worth Considering?</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-fcpx-2024-tutorial-synchronizing-audio-and-video-for-perfect-edits/"><u>New FCPX 2024 Tutorial Synchronizing Audio and Video for Perfect Edits</u></a></li>
<li><a href="https://driver-install.techidaily.com/1720062733587-nvidia-quadro-rtx-6000-drivers-download-and-update/"><u>NVIDIA Quadro RTX 6000 Drivers – Download & Update</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-pen-pad-glitches/"><u>Overcoming Windows Pen-Pad Glitches</u></a></li>
<li><a href="https://windows11.techidaily.com/prtscn-and-snipping-tool-link-in-windows-11-prevent-connection/"><u>PrtScn & Snipping Tool Link in Windows 11: Prevent Connection</u></a></li>
<li><a href="https://windows11.techidaily.com/reactivating-inputs-post-sleep-on-latest-windows/"><u>Reactivating Inputs Post-Sleep on Latest Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-screen-resolution-problems-in-windows-os/"><u>Rectifying Screen Resolution Problems in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-could-not-create-vm-problems-in-microsoft-os/"><u>Remedying 'Could Not Create VM' Problems in Microsoft OS</u></a></li>
<li><a href="https://windows11.techidaily.com/resuscitate-stalled-excel-performance-in-windows-environment/"><u>Resuscitate Stalled Excel Performance in Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-to-extending-windows-1011-contextual-commands/"><u>Step-by-Step Guide to Extending Windows 10/11 Contextual Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-solutions-to-resolve-instant-failure-in-adding-a-folder-in-onedrive/"><u>Swift Solutions to Resolve Instant Failure in Adding a Folder in OneDrive</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-print-guide-to-making-your-powerpoint-shine-on-a-windows-system/"><u>The Ultimate Print Guide to Making Your PowerPoint Shine on a Windows System</u></a></li>
<li><a href="https://windows11.techidaily.com/time-tinkering-tools-top-windows-programs-for-date-adjustment/"><u>Time Tinkering Tools: Top Windows Programs for Date Adjustment</u></a></li>
<li><a href="https://win-amazing.techidaily.com/ultimate-guide-installing-and-updating-rtx-2070-graphics-card-drivers-in-windows-11/"><u>Ultimate Guide: Installing & Updating RTX 2070 Graphics Card Drivers in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-battlenet-accessibility-on-1011-systems/"><u>Unlocking Battle.net Accessibility on 10/11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-memory-integrity-on-windows-11-methods-77/"><u>Unlocking Memory Integrity on Windows 11: Methods 7/7</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unlocking-missing-chatgpt-records/"><u>Unlocking Missing ChatGPT Records</u></a></li>
<li><a href="https://common-error.techidaily.com/why-isnt-my-hdmi-working-through-usb-common-issues-and-fixes/"><u>Why Isn't My HDMI Working Through USB? Common Issues and Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/why-sudo-is-revolutionizing-windows-systems/"><u>Why Sudo Is Revolutionizing Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-and-discord-fixing-the-deadly-js-error-quickly/"><u>Win 11 and Discord: Fixing The Deadly JS Error Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-cleanup-stripping-out-microsoft-store/"><u>Win11 Cleanup: Stripping Out Microsoft Store</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-troubleshooting-silent-voice-calls-in-valorant/"><u>Windows Troubleshooting: Silent Voice Calls in Valorant</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-wifi-wisdom-accelerating-network-speed-assessment/"><u>Windows WiFi Wisdom: Accelerating Network Speed Assessment</u></a></li>
</ul></div>
