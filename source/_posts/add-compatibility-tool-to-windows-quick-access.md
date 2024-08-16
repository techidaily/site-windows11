---
title: Add Compatibility Tool to Windows' Quick Access
date: 2024-08-15T15:15:47.691Z
updated: 2024-08-16T15:15:47.691Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Add Compatibility Tool to Windows' Quick Access
excerpt: This Article Describes Add Compatibility Tool to Windows' Quick Access
keywords: Quick Access Tool Addon,Compatibility Enhancer,Windows QuickTool,Compatibility Update,QuikAccess Accessory,Windows EasyTool,Compatibility Windows Fix
thumbnail: https://thmb.techidaily.com/8bb1efcd08c2d3c3707b37b1d9ac64c15c4d68acde1a08c23a7f1acea10d7dc6.jpg
---

## Add Compatibility Tool to Windows' Quick Access

 There are many ways to run the Compatibility Troubleshooter, but the easiest way is to do it from the context menu by right-clicking on a program and selecting**Troubleshoot Compatibility** . However, sometimes, this option can go missing, and the good news is that you can add it back with a couple of registry tweaks. Keep on reading to find out how.

## What to Do Before Tweaking the Registry Editor

 Before you go about making big changes to your Windows PC, it’s always a good idea to have some sort of backup in case things go wrong. To do that, we highly recommend reading our guide on [creating a system restore with Command Prompt](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) . If you want, you can also read our other guide on [how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) if you want to have a copy of it somewhere.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->
## How to Add a "Troubleshoot Compatibility" Option to the Context Menu With the Registry Editor

 Now that you know how to keep the Windows registry safe, it's time to change it with the Registry Editor. We are going to start by adding the**Troubleshoot Compatibility** option to the context menu for EXE files. Afterward, the steps for adding it to other programs are going to be similar. To do that, follow the steps below:

1. Press**Win + R** to open the Run dialog box, enter**regedit** in the text box, and hit the**Enter** key to open the Registry Editor.
2. First, we are going to add the Troubleshoot Compatibility option for the EXE files. Start by copying and pasting the below key path in the address of the Registry Editor and hit the**Enter** key:  
HKEY_CLASSES_ROOT\cmdfile\shellEx\ContextMenuHandlers
3. Right-click the**ContextMenuHandlers** key and then select**New > Key** and name it**Compatibility** . If it is already there, move on to the next step.  
![Adding a new key to the ContextMenuHandler key for the EXE files](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/new-key-compatibility-troubleshooter-context-menu.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
4. Select the**Compatibility** key, double-click**Default** on the right, and set**Value data** to**{1d27f844-3a1f-4410-85ac-14651078412d}** .  
![Entering value data for a string value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enter-value-data.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->

 Next, you’re going to repeat the steps above to add the**Troubleshoot Compatibility** to the context menu of other BAT and CMD files. Just replace the key path in step two with**HKEY\_CLASSES\_ROOT\\batfile\\shellEx\\ContextMenuHandlers\\** for BAT files and**HKEY\_CLASSES\_ROOT\\cmdfile\\shellEx\\ContextMenuHandlers\\** for CMD files.

 Now when you right-click an EXE, BAT, or CMD file, you should see the**Troubleshoot Compatibility** option in the context menu.

![The Troubleshoot compatibility option in the context menu on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/troubleshoot-compatibility-context-menu.jpg)
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now you have one more way to [run the Program Compatibility Troubleshooter](https://www.makeuseof.com/run-program-compatibility-troubleshooter-windows/) .

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
## Run the Program Compatibility Troubleshooter Easily

 The Program Compatibility Troubleshooter is one of the best ways to fix compatibility issues on Windows. If you use it often, it helps to have the tool close. With the instructions above, you can add it to and run it from the context menu, which is extremely convenient.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>





<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-hovers.techidaily.com/new-all-encompassing-review-djis-inspire-1-drone-for-2024/"><u>[New] All-Encompassing Review  DJI's Inspire 1 Drone for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-controlling-video-flow-on-your-screens-window-netflix/"><u>[New] Controlling Video Flow on Your Screen's Window (Netflix)</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-experts-picks-the-best-10-photography-lenses/"><u>[New] Expert's Picks  The Best 10 Photography Lenses</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-in-2024-how-to-edit-podcasts-in-garageband/"><u>[New] In 2024, How To Edit Podcasts in GarageBand</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-instant-audience-expansion-with-these-channel-upgrades/"><u>[New] Instant Audience Expansion with These Channel Upgrades</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-making-youtube-based-twitter-videos-hearable/"><u>[New] Making YouTube-Based Twitter Videos Hearable</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-overcoming-inaudibility-in-obs-captured-audio/"><u>[New] Overcoming Inaudibility in OBS Captured Audio</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/he-ultimate-guide-to-youtube-short-video-insights-for-2024/"><u>[New] The Ultimate Guide to YouTube Short Video Insights for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-choosing-a-professional-video-editor-filmora-against-democreator/"><u>[Updated] Choosing a Professional Video Editor  Filmora Against Democreator</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-guidelines-for-renaming-yourself-in-online-meetings/"><u>[Updated] Guidelines for Renaming Yourself in Online Meetings</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-10-best-youtube-to-gif-makers-how-to-create-gif-from-youtube-video/"><u>[Updated] In 2024, 10 Best YouTube To GIF Makers  How to Create GIF From YouTube Video?</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-maximizing-your-youtube-videos-viewer-count/"><u>[Updated] Maximizing Your YouTube Video's Viewer Count</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-charting-uncharted-territories-with-jaunt-vr/"><u>2024 Approved  Charting Uncharted Territories with Jaunt VR</u></a></li>
<li><a href="https://windows11.techidaily.com/a-step-by-step-guide-to-fixing-windows-rare-errors/"><u>A Step-by-Step Guide to Fixing Windows’ Rare Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-peak-speed-for-your-windows-ssd-using-fresh-methods/"><u>Achieve Peak Speed for Your Windows' SSD Using Fresh Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-java-not-installing-a-windows-fixers-manual/"><u>Addressing Java Not Installing: A Windows Fixer's Manual</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-non-existent-files-message-on-windows-11/"><u>Addressing Non-Existent Files Message on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/altering-monitors-sequence-on-laptops/"><u>Altering Monitors' Sequence on Laptops</u></a></li>
<li><a href="https://windows11.techidaily.com/altering-windows-files-date-creation-and-modification-adjustments/"><u>Altering Windows Files: Date Creation & Modification Adjustments</u></a></li>
<li><a href="https://windows11.techidaily.com/antiquated-tech-awakened-atlasos-upgrade/"><u>Antiquated Tech Awakened: AtlasOS Upgrade</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-spontaneous-windows-11-lockups-and-shuts/"><u>Avoid Spontaneous Windows 11 Lockups & Shuts</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-failure-of-services-on-windows-with-error-1053-fixes/"><u>Avoiding Failure of Services on Windows with Error 1053 Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-productivity-with-these-5-advanced-windows-folder-hacks/"><u>Boost Productivity with These 5 Advanced Windows Folder Hacks</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-free-from-the-frozen-windows-terminal/"><u>Breaking Free From the Frozen Windows Terminal</u></a></li>
<li><a href="https://windows11.techidaily.com/bridging-linux-and-windows-gap-with-shared-tools/"><u>Bridging Linux & Windows Gap with Shared Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-frozen-wow-post-update-phases/"><u>Bypassing Frozen WoW Post-Update Phases</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-microsofts-restrictive-security-measures/"><u>Bypassing Microsoft’s Restrictive Security Measures</u></a></li>
<li><a href="https://windows11.techidaily.com/changing-default-user-directory-labels-windows-11/"><u>Changing Default User Directory Labels (Windows 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/command-line-carnival-exciting-stunts-for-your-terminal/"><u>Command Line Carnival: Exciting Stunts for Your Terminal</u></a></li>
<li><a href="https://windows11.techidaily.com/consistent-experience-migrating-powertoys-on-new-pcs/"><u>Consistent Experience: Migrating PowerToys on New PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-cannot-calculate-issues-on-windows-platform/"><u>Correcting 'Cannot Calculate' Issues on Windows Platform</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-audacitys-internal-portaudio-error-on-w10w11-pcs/"><u>Correcting Audacity's Internal PortAudio Error on W10/W11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/crucial-factors-to-evaluate-before-buying-a-windows-laptop/"><u>Crucial Factors to Evaluate Before Buying a WIndows Laptop</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-windows-layout-fancywm-power-up/"><u>Customize Windows Layout: FancyWM Power Up</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-your-window-11-experience-dynamic-wallpapers-guide/"><u>Customize Your Window 11 Experience: Dynamic Wallpapers Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-down-unnecessary-memory-use-by-webview2-on-edge/"><u>Cutting Down Unnecessary Memory Use by WebView2 on Edge</u></a></li>
<li><a href="https://windows11.techidaily.com/dealing-with-the-extract-to-temp-directory-glitch-fix-for-error-1152/"><u>Dealing with the 'Extract to Temp Directory' Glitch: Fix for Error 1152</u></a></li>
<li><a href="https://windows11.techidaily.com/deploying-microsofts-ai-companion-via-vivetool/"><u>Deploying Microsoft's AI Companion via ViveTool</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-unique-applications-the-best-10-uses-for-powertoys/"><u>Discover Unique Applications: The Best 10 Uses for PowerToys</u></a></li>
<li><a href="https://windows11.techidaily.com/dispatching-speed-limits-defeat-windows-100mbps-boundary/"><u>Dispatching Speed Limits: Defeat Windows' 100Mbps Boundary</u></a></li>
<li><a href="https://unlock-android.techidaily.com/downloading-samfw-frp-tool-30-for-tecno-spark-10-4g-by-drfone-android/"><u>Downloading SamFw FRP Tool 3.0 for Tecno Spark 10 4G</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/failed-to-play-hevc-files-on-14-pro-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>Failed to play HEVC files on 14 Pro</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-can-i-use-a-fake-gps-without-mock-location-on-honor-play-7t-drfone-by-drfone-virtual-android/"><u>How Can I Use a Fake GPS Without Mock Location On Honor Play 7T? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-6-ways-to-transfer-contacts-from-vivo-t2x-5g-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 6 Ways To Transfer Contacts From Vivo T2x 5G to iPhone | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-channeling-success-the-personal-brand-strategy-for-youtubers/"><u>In 2024, Channeling Success  The Personal Brand Strategy for YouTubers</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-motorola-moto-g73-5gwithwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Motorola Moto G73 5Gwith/without a PC</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/in-2024-mealtime-magnates-on-tiktok-platform/"><u>In 2024, Mealtime Magnates on TikTok Platform</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-unparalleled-pc-sound-control/"><u>In 2024, Unparalleled PC Sound Control</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/instagram-photo-edits-made-simple-pro-techniques-for-2024/"><u>Instagram Photo Edits Made Simple  Pro Techniques for 2024</u></a></li>
</ul></div>
