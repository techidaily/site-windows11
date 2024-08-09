---
title: Minimizing Resource Waste During Device Integration on Windows
date: 2024-08-08T06:04:04.490Z
updated: 2024-08-09T06:04:04.490Z
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
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Disable Connected Devices Platform User Service

 The simplest way to stop Connected Devices Platform User Service from using too much RAM is to disable it. However, this might cause some unexpected behavior on your computer. And if that happens, you can always enable it again.

 To disable Connected Devices Platform User Service, press **Win + R** to bring up Windows Run. Enter **services.msc** in the text box and then press the **Enter** key on your keyboard.

![services msc Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/services-msc-Windows-11.jpg)

 Find the **Disable Connected Devices Platform User Service** in the list of services and double-click on it. Click on the **Startup type** dropdown and select **Disabled**. Then, under **Service status** in the same window, click on **Stop**.

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![the-connected-device-platform-user-service-properties-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-connected-device-platform-user-service-properties-windows.jpg)

 Now, check Task Manager to see if the service is still consuming too much RAM.

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Remove the ActivitiesCache.db file

 Some users have reported that deleting the ActivitiesCache.db file on their computer has helped solve the problem. To delete it, start by disabling the Connected Devices Platform User Service, as discussed above. Then, press **Win + R** to open Windows Run, copy and paste **%localappdata%\\ConnectedDevicesPlatform\\** in the text, and then hit the **Enter** key.

![navigating-to-the-connecteddevicesplatform-folder-in-windows-run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/navigating-to-the-connecteddevicesplatform-folder-in-windows-run.jpg)

 This will open the **ConnectedDevicesPlatform** folder. You'll see several files and folders in there, so open each of the folders and delete the **ActivitiesCache.db** file in all of them.

<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![the-activitiescab-file-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-activitiescab-file-on-windows.jpg)

 Once you do, restart your computer and see if Connected Devices Platform User Service is still causing RAM consumption issues.

<!-- affiliate ads begin -->
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Check for Issues With Your Computer's Hardware

 Sometimes, the problem could arise due to one of your connected devices experiencing a problem. To check if your connected devices are functioning properly, open Device Manager by pressing **Win + R**, enter **devmgmt.msc** in the text box, and then hit the **Enter** key on your keyboard.

![devmgmt.msc in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/devmgmt-msc.jpg)

 In Device Manager, double-click the device you suspect is causing issues. This will open its properties window.

 In the **General** tab of the Properties window, make sure it says **This device is working properly** under **Device status**.

![the-properties-window-of-a-device-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-properties-window-of-a-device-on-windows.jpg)

 If it doesn't, you will see an error message and a code. Take note of both so you can start troubleshooting the problem. You can start by using [one of the troubleshooters on Windows](https://www.makeuseof.com/run-troubleshooter-windows-10-11/) to check for and fix the hardware problem you're seeing.

 If all the steps above don't work then you might need to [use a system restore point](https://www.makeuseof.com/use-system-restore-windows/) that you created before it started using too much RAM. And if that doesn't work as well, you might have to reset your Windows computer

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Free Your RAM From Connected Devices Platform User Service

 No process is entitled to consume too much RAM on your computer. And if you find that Connected Devices Platform User Service is doing just that, you can disable it, delete the ActivitiesCache.db file, or see if there's something wrong with your hardware. Hopefully, one of those things will help stop the process hogging the RAM.

 When it consumes too much RAM, it means something could be wrong with the process or your connected devices. Below, we'll show you how to stop Connected Devices Platform User Service from hogging your physical memory.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-expert-guide-to-skype-recordings-the-most-effective-free-and-paid-ways-for-2024/"><u>[New] Expert Guide to Skype Recordings - The Most Effective Free & Paid Ways for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-is-inshot-the-best-video-editing-app-our-in-depth-review/"><u>[New] Is InShot the Best Video Editing App? Our In-Depth Review</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-mobile-focus-top-gimbal-systems-for-dynamic-shooting/"><u>[New] Mobile Focus  Top Gimbal Systems for Dynamic Shooting</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-rhythmic-respite-top-20-easygoing-country-hits-for-stress-relief-dance-on-tiktok-for-2024/"><u>[Updated] Rhythmic Respite  Top 20 Easygoing Country Hits for Stress-Relief Dance on TikTok for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-shrink-it-down-youtubes-video-trimming-process/"><u>[Updated] Shrink It Down  YouTube's Video Trimming Process</u></a></li>
<li><a href="https://extra-resources.techidaily.com/12-live-video-streaming-app-for-watching-and-streaming-videos/"><u>12 Live Video Streaming App for Watching and Streaming Videos</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-advanced-techniques-for-perfecting-your-voice-with-morphvox/"><u>2024 Approved  Advanced Techniques for Perfecting Your Voice with MorphVOX</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-disqus-poster-pixel-arrangement/"><u>2024 Approved  Disqus Poster Pixel Arrangement</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-exploring-high-frame-rate-filming-with-yi/"><u>2024 Approved  Exploring High Frame Rate Filming with YI</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-instagram-silent-spots-how-to-make-every-frame-loud-and-clear/"><u>2024 Approved  Instagram Silent Spots - How to Make Every Frame Loud and Clear</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprerant-users-resourceful-approach-to-processes-and-themes-in-windows-11/"><u>A Compreran't User's Resourceful Approach to Processes and Themes in Windows 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/adding-pictures-to-instagram-with-ease-for-2024/"><u>Adding Pictures to Instagram with Ease for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-the-mold-unleashing-dormant-windows-11-powers/"><u>Breaking the Mold: Unleashing Dormant Windows 11 Powers</u></a></li>
<li><a href="https://article-posts.techidaily.com/comprehensive-guide-to-photo-to-video-conversion-via-pixiz-for-2024/"><u>Comprehensive Guide to Photo-to-Video Conversion via Pixiz for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/configure-ideal-window-space-for-your-apps-in-win11/"><u>Configure Ideal Window Space for Your Apps in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/creative-walls-for-your-pc-windows-1011-guide/"><u>Creative Walls for Your PC: Windows 10/11 Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/device-dialogue-diplomacy-android-plus-pc-sync-guide/"><u>Device Dialogue Diplomacy: Android + PC Sync Guide</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-vivo-g2-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Vivo G2 Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/efficiently-edit-your-youtube-videos-using-sony-vegas-for-2024/"><u>Efficiently Edit Your YouTube Videos Using Sony Vegas for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-email-management-gmail-in-outlook-windows-edition/"><u>Effortless Email Management: Gmail in Outlook, Windows Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-ride-on-windows-discover-top-5-budget-enhancers/"><u>Elevate Your Ride on Windows: Discover Top 5 Budget Enhancers</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-output-amplitude-for-external-windows-11-audio/"><u>Elevating Output Amplitude for External Windows 11 Audio</u></a></li>
<li><a href="https://windows11.techidaily.com/end-the-ebb-and-flow-top-strategies-for-smooth-windows-streaming/"><u>End the Ebb and Flow: Top Strategies for Smooth Windows Streaming</u></a></li>
<li><a href="https://windows11.techidaily.com/erase-your-black-screen-and-clear-cursor-issues-in-win11/"><u>Erase Your Black Screen & Clear Cursor Issues in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-how-to-erase-past-safety-checks-on-windows/"><u>Expert Tips: How to Erase Past Safety Checks on Windows</u></a></li>
<li><a href="https://howto.techidaily.com/full-guide-how-to-fix-connection-is-not-private-on-vivo-y100i-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Guide How To Fix Connection Is Not Private on Vivo Y100i | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/gpresult-command-guide-for-policy-reporting/"><u>GPResult Command Guide for Policy Reporting</u></a></li>
<li><a href="https://windows11.techidaily.com/harmonious-hardware-connections-android-pc-junctions/"><u>Harmonious Hardware Connections: Android-PC Junctions</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-batch-convert-heic-images-to-jpeg-format-in-windows-10-and-11/"><u>How to Batch Convert HEIC Images to JPEG Format in Windows 10 & 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-downgrade-iphone-8-to-the-previous-ios-system-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade iPhone 8 to the Previous iOS System Version? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-nvidia-control-panel-not-opening-in-windows-11/"><u>How to Fix the NVIDIA Control Panel Not Opening in Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-intercept-text-messages-on-realme-narzo-60x-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Intercept Text Messages on Realme Narzo 60x 5G | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-instant-impression-audiovisual-capture/"><u>In 2024, Instant Impression  Audiovisual Capture</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-planning-to-use-a-pokemon-go-joystick-on-nokia-150-2023-drfone-by-drfone-virtual-android/"><u>In 2024, Planning to Use a Pokemon Go Joystick on Nokia 150 (2023)? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-preparation-to-beat-giovani-in-pokemon-go-for-tecno-pova-5-drfone-by-drfone-virtual-android/"><u>In 2024, Preparation to Beat Giovani in Pokemon Go For Tecno Pova 5 | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-top-10-naming-algorithms-for-podcast-mastery/"><u>In 2024, Top 10 Naming Algorithms for Podcast Mastery</u></a></li>
<li><a href="https://extra-skills.techidaily.com/max-360-vs-hero-11-choosing-the-best-gopro-cam-for-2024/"><u>Max 360 Vs. Hero 11 - Choosing the Best GoPro Cam for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-the-gap-enabling-smooth-steam-connection/"><u>Mending the Gap: Enabling Smooth Steam Connection</u></a></li>
<li><a href="https://tech-revival.techidaily.com/navigating-the-future-understanding-artificial-intelligence-and-its-oversight/"><u>Navigating the Future: Understanding Artificial Intelligence and Its Oversight</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/new-2024-approved-top-7-online-auto-subtitle-translators-for-content-creators/"><u>New 2024 Approved Top 7 Online Auto Subtitle Translators for Content Creators</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-the-art-of-sound-visuals-illustrating-audio-signals-as-waveforms-and-enriching-footage-with-animation-in-adobe-premiere-pro-for-2024/"><u>New The Art of Sound Visuals Illustrating Audio Signals as Waveforms & Enriching Footage with Animation in Adobe Premiere Pro for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/no-more-erratic-arrows-fixes-for-the-frustrated/"><u>No More Erratic Arrows: Fixes for the Frustrated</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-11-error-0x80070570-fixing-damaged-files/"><u>Overcoming Windows 11 Error 0X80070570: Fixing Damaged Files</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-11-zoom-malfunction-1132/"><u>Overcoming Windows 11 Zoom Malfunction #1132</u></a></li>
<li><a href="https://fake-location.techidaily.com/read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-xiaomi-redmi-note-13-5g-drfone-by-drfone-virtual-android/"><u>Read This Guide to Find a Reliable Alternative to Fake GPS On Xiaomi Redmi Note 13 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-pc-performance-hurdles-with-intel-graphics-updates/"><u>Remedying PC Performance Hurdles with Intel Graphics Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-system-crash-code-0xc0000001/"><u>Remedying System Crash Code 0xC0000001</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-and-streamline-with-win11s-hard-drive-defrag/"><u>Secure & Streamline with Win11's Hard Drive Defrag</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-storing-error-during-new-app-installation/"><u>Solutions for Storing Error During New App Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-separate-bunched-system-icons/"><u>Strategies to Separate Bunched System Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-unmasking-user-ids-a-guide-to-sids-in-windows-11/"><u>The Art of Unmasking User IDs: A Guide to SIDs in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-comprehensive-manual-for-component-settings-in-w11/"><u>The Comprehensive Manual for Component Settings in W11</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/the-ultimate-list-of-most-watched-videos-on-fb/"><u>The Ultimate List of Most-Watched Videos on FB</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-to-quicken-windows-edge-on-w10-and-w11/"><u>Tips to Quicken Windows Edge on W10 & W11</u></a></li>
<li><a href="https://windows11.techidaily.com/turn-your-windows-11-pc-into-a-self-contained-internet-station/"><u>Turn Your Windows 11 PC Into a Self-Contained Internet Station</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/unleashing-the-full-potential-of-your-channel-in-studio-for-2024/"><u>Unleashing the Full Potential of Your Channel in Studio for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-full-potential-adding-portable-apps-to-w11/"><u>Unlock Full Potential: Adding Portable Apps to W11</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secrets-of-a-smoother-click-lock-in-windows/"><u>Unveiling the Secrets of a Smoother Click Lock in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-layers-impact-on-linux-dominance/"><u>Windows Layer's Impact on Linux Dominance</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>