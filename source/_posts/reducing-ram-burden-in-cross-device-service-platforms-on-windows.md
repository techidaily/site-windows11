---
title: Reducing RAM Burden in Cross-Device Service Platforms on Windows
date: 2024-08-08T06:04:31.606Z
updated: 2024-08-09T06:04:31.606Z
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

 Find the **Disable Connected Devices Platform User Service** in the list of services and double-click on it. Click on the **Startup type** dropdown and select **Disabled**. Then, under **Service status** in the same window, click on **Stop**.

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1896607/21553" target="_top" id="1896607"><img src="//a.impactradius-go.com/display-ad/21553-1896607" border="0" alt="" width="750" height="422"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1896607/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![the-connected-device-platform-user-service-properties-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-connected-device-platform-user-service-properties-windows.jpg)

 Now, check Task Manager to see if the service is still consuming too much RAM.

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->
## 2\. Remove the ActivitiesCache.db file

 Some users have reported that deleting the ActivitiesCache.db file on their computer has helped solve the problem. To delete it, start by disabling the Connected Devices Platform User Service, as discussed above. Then, press **Win + R** to open Windows Run, copy and paste **%localappdata%\\ConnectedDevicesPlatform\\** in the text, and then hit the **Enter** key.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
![navigating-to-the-connecteddevicesplatform-folder-in-windows-run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/navigating-to-the-connecteddevicesplatform-folder-in-windows-run.jpg)

 This will open the **ConnectedDevicesPlatform** folder. You'll see several files and folders in there, so open each of the folders and delete the **ActivitiesCache.db** file in all of them.

![the-activitiescab-file-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-activitiescab-file-on-windows.jpg)

 Once you do, restart your computer and see if Connected Devices Platform User Service is still causing RAM consumption issues.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->
## 3\. Check for Issues With Your Computer's Hardware

 Sometimes, the problem could arise due to one of your connected devices experiencing a problem. To check if your connected devices are functioning properly, open Device Manager by pressing **Win + R**, enter **devmgmt.msc** in the text box, and then hit the **Enter** key on your keyboard.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![devmgmt.msc in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/devmgmt-msc.jpg)

 In Device Manager, double-click the device you suspect is causing issues. This will open its properties window.

 In the **General** tab of the Properties window, make sure it says **This device is working properly** under **Device status**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
![the-properties-window-of-a-device-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-properties-window-of-a-device-on-windows.jpg)

 If it doesn't, you will see an error message and a code. Take note of both so you can start troubleshooting the problem. You can start by using [one of the troubleshooters on Windows](https://www.makeuseof.com/run-troubleshooter-windows-10-11/) to check for and fix the hardware problem you're seeing.

 If all the steps above don't work then you might need to [use a system restore point](https://www.makeuseof.com/use-system-restore-windows/) that you created before it started using too much RAM. And if that doesn't work as well, you might have to reset your Windows computer

## Free Your RAM From Connected Devices Platform User Service

 No process is entitled to consume too much RAM on your computer. And if you find that Connected Devices Platform User Service is doing just that, you can disable it, delete the ActivitiesCache.db file, or see if there's something wrong with your hardware. Hopefully, one of those things will help stop the process hogging the RAM.

 When it consumes too much RAM, it means something could be wrong with the process or your connected devices. Below, we'll show you how to stop Connected Devices Platform User Service from hogging your physical memory.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-live-streaming-and-screen-capture-a-comprehensive-obs-analysis/"><u>[New] 2024 Approved  Live Streaming & Screen Capture  A Comprehensive OBS Analysis</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-bring-imagination-to-life-self-animated-artistry-for-2024/"><u>[New] Bring Imagination to Life  Self-Animated Artistry for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-weekly-must-watch-excellence-in-igtv/"><u>[New] In 2024, Weekly Must-Watch  Excellence in IGTV</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-spectacular-sites-featuring-rich-3d-and-golden-text/"><u>[New] Spectacular Sites Featuring Rich 3D and Golden Text</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/1715859630962-new-unveiling-advantages-comprehen/"><u>[New] Unveiling Advantages  Comprehen...</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-creative-content-concepts-for-vlogs/"><u>[Updated] 2024 Approved  Creative Content Concepts for Vlogs</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-record-and-share-moments-instantly-using-vlcs-webcam-recorder/"><u>[Updated] Record & Share Moments Instantly Using VLC's Webcam Recorder</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-recordingrealm-expedition-unveiling-snapcastpro-2023/"><u>[Updated] RecordingRealm Expedition  Unveiling 'SnapCastPro' 2023</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-fake-gps-without-root-on-vivo-v30-pro-drfone-by-drfone-virtual-android/"><u>3 Ways to Fake GPS Without Root On Vivo V30 Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-absence-of-files-alert-in-windows-11/"><u>Addressing Absence of Files Alert in Windows 11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/androids-very-own-podcasters-for-2024/"><u>Android's Very Own Podcasters for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/automating-network-drives-on-win11/"><u>Automating Network Drives on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-productivity-on-windows-by-adjusting-with-alomware/"><u>Boost Productivity on Windows by Adjusting with AlomWare</u></a></li>
<li><a href="https://windows11.techidaily.com/confronting-and-overcoming-mmc-snaps-not-found-errors/"><u>Confronting and Overcoming MMC Snaps Not Found Errors</u></a></li>
<li><a href="https://extra-information.techidaily.com/discovering-the-prime-6-headgear-choices-for-capturing-life-with-gopro/"><u>Discovering the Prime 6 Headgear Choices for Capturing Life with GoPro</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-the-deadly-c0000022-breakdown-in-windows-10/"><u>Fixing the Deadly C0000022 Breakdown in Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-error-0x80071a90-explained-simply/"><u>Fixing Windows Error 0X80071A90 Explained Simply</u></a></li>
<li><a href="https://youtube-web.techidaily.com/lating-impressive-online-media-introductions-for-2024/"><u>Formulating Impressive Online Media Introductions for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-the-application-encountered-an-unrecoverable-error-in-roblox-on-windows/"><u>How to Fix the “The Application Encountered an Unrecoverable Error in Roblox on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-resolve-windows-11s-update-error-0x800f0922/"><u>How to Resolve Windows 11'S Update Error 0X800f0922</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-restore-absentee-application-association-windows/"><u>How To Restore Absentee Application Association (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-successfully-upgrade-to-virtualbox-70-on-windows-11-pcs/"><u>How to Successfully Upgrade to VirtualBox 7.0 on Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-transfer-apps-to-a-new-windows-11-pc/"><u>How to Transfer Apps to a New Windows 11 PC</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-turn-off-desktop-input-on-your-win-device/"><u>How to Turn Off Desktop Input on Your Win Device</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-iphone-13-with-a-mask-on-by-drfone-ios/"><u>How to Unlock iPhone 13 with a Mask On</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-can-you-unlock-apple-iphone-x-after-forgetting-the-passcode-drfone-by-drfone-ios/"><u>In 2024, Can You Unlock Apple iPhone X After Forgetting the Passcode? | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-enhancing-media-top-5-streamlining-gadgets/"><u>In 2024, Enhancing Media  Top 5 Streamlining Gadgets</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-can-we-bypass-huawei-frp-by-drfone-android/"><u>In 2024, How Can We Bypass Huawei FRP?</u></a></li>
<li><a href="https://fix-guide.techidaily.com/in-2024-how-to-sharefake-location-on-whatsapp-for-itel-p55t-drfone-by-drfone-virtual-android/"><u>In 2024, How to Share/Fake Location on WhatsApp for Itel P55T | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-12-mini-official-method-to-unlock-your-apple-iphone-12-mini-by-drfone-ios/"><u>In 2024, How To Unlock Apple iPhone 12 mini Official Method to Unlock Your Apple iPhone 12 mini</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-mastering-lock-screen-settings-how-to-enable-and-disable-on-nubia-red-magic-8s-proplus-by-drfone-android/"><u>In 2024, Mastering Lock Screen Settings How to Enable and Disable on Nubia Red Magic 8S Pro+</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-screen-saver-saviors-how-to-download-and-save-your-favorite-tweets/"><u>In 2024, Screen Saver Saviors  How to Download and Save Your Favorite Tweets</u></a></li>
<li><a href="https://windows11.techidaily.com/invisible-to-others-windows-network-concealment/"><u>Invisible to Others: Windows Network Concealment</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-fixing-exit-code-errors/"><u>Mastering Windows: Fixing Exit Code Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-microphone-errors-in-xbox-app-on-windows-11-systems/"><u>Navigating Microphone Errors in Xbox App on Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-network-nuances-7-fixes-for-connectivity-in-obs-studio/"><u>Navigating Network Nuances: 7 Fixes for Connectivity in OBS Studio</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-detect-clapping-impact-soundscape-for-2024/"><u>New Detect Clapping Impact Soundscape for 2024</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-finding-authentic-clap-sound-implementations-for-projects/"><u>New Finding Authentic Clap Sound Implementations for Projects</u></a></li>
<li><a href="https://activate-lock.techidaily.com/new-multiple-ways-how-to-remove-icloud-activation-lock-from-your-apple-iphone-8-plus-by-drfone-ios/"><u>New Multiple Ways How To Remove iCloud Activation Lock From your Apple iPhone 8 Plus</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-android-usage-a-windows-11-webcam-setup/"><u>Optimizing Android Usage: A Windows 11 Webcam Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-openers-dive-into-windows-performance-data/"><u>Quick Openers: Dive Into Windows Performance Data</u></a></li>
<li><a href="https://windows11.techidaily.com/realign-your-windows-clock-through-chrome-settings/"><u>Realign Your Windows Clock Through Chrome Settings</u></a></li>
<li><a href="https://fox-that.techidaily.com/recognizing-the-signs-top-9-indicators-of-an-iphone-suffering-from-liquid-intrusion/"><u>Recognizing the Signs: Top 9 Indicators of an iPhone Suffering From Liquid Intrusion</u></a></li>
<li><a href="https://windows11.techidaily.com/resetting-the-explorer-view-for-better-management/"><u>Resetting the Explorer View for Better Management</u></a></li>
<li><a href="https://windows11.techidaily.com/revealing-the-make-of-your-windows-machine-in-six-steps/"><u>Revealing the Make of Your Windows Machine in Six Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-new-reset-limit-on-account-lockouts-in-windows-1011/"><u>Setting New Reset Limit on Account Lockouts in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/simplify-your-workflow-adding-context-menu-assistance/"><u>Simplify Your Workflow: Adding Context Menu Assistance</u></a></li>
<li><a href="https://windows11.techidaily.com/smart-scheduling-for-improved-resource-allocation-on-android-wsl/"><u>Smart Scheduling for Improved Resource Allocation on Android WSL</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-windows-update-failures-0x800736cc-issue/"><u>Solving Windows Update Failures: 0X800736CC Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-overcome-audio-glitch-in-win1011/"><u>Strategies to Overcome Audio Glitch in Win10/11</u></a></li>
<li><a href="https://some-skills.techidaily.com/thorough-examination-of-dji-inspire-1-for-2024/"><u>Thorough Examination of DJI Inspire 1 for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/uncharted-territory-innovations-to-windows-11s-explorer-interface/"><u>Uncharted Territory: Innovations to Windows 11'S Explorer Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-two-less-known-yet-crucial-windows-tools/"><u>Unveiling Two Less-Known, Yet Crucial Windows Tools</u></a></li>
<li><a href="https://facebook.techidaily.com/unveiling-vk-the-russian-social-networks-essentials/"><u>Unveiling VK: The Russian Social Network's Essentials</u></a></li>
<li><a href="https://techidaily.com/will-14-pro-play-avchd-mts-files-by-aiseesoft-video-converter-play-mts-on-android/"><u>Will 14 Pro play AVCHD mts files?</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-uncontrollable-scroll-troubleshooting-steps/"><u>Windows Uncontrollable Scroll: Troubleshooting Steps</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>