---
title: Expanding External Devices in Explorer's Side
date: 2024-08-15T16:18:16.251Z
updated: 2024-08-16T16:18:16.251Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Expanding External Devices in Explorer's Side
excerpt: This Article Describes Expanding External Devices in Explorer's Side
keywords: Expand Device Explorer,Sidebar Extension,External Device Add-On,Explore Sidebar,Windows Explorer Enhance,Devices in Explorer,External Tools Explorer
thumbnail: https://thmb.techidaily.com/79265524b64a96a355aa9c66ef040a78b4c61cd77b813b963d28880dc313d729.jpg
---

## Expanding External Devices in Explorer's Side

 To access the D: drive, you normally have to open File Explorer, click on **This PC** in the Navigation pane, and expand the **Devices and drives** section. With a simple hack, you can add it to the Navigation pane so you can easily access it straight from there. It will require you to tweak the Windows Registry, but don’t worry; we'll show you an extremely easy way of going about it.

## Before You Proceed…

 We are going to [create a Registry file](https://www.makeuseof.com/windows-registry-file-guide/) to add the D: drive to the Navigation Pane. This file will make changes to the Windows registry, and you need to be careful [not to mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/). A slip-up could make Windows unusable.

 Furthermore, we highly recommend that you learn how to [back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). That way, you have a way of returning it to the state it was in before you made any changes that broke it.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How Do I Add the D: Drive to the Navigation Pane in File Explorer?

 Start by pressing **Win + S** to bring up Windows Search. Then, type **notepad** in the Search box, and when Notepad shows up in the search results, click on it to launch it.

![The Notepad search result](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/notepad-search-result.png)
<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then copy and paste the below text into Notepad:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}]  
@="D: Drive"  
"System.IsPinnedToNamespaceTree"=dword:00000001  
"SortOrderIndex"=dword:00000050  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\DefaultIcon]  
@=hex(2):69,00,6d,00,61,00,67,00,65,00,72,00,65,00,73,00,2e,00,64,00,6c,00,6c,\  
  00,2c,00,2d,00,33,00,32,00,00,00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\InProcServer32]  
@=hex(2):43,00,3a,00,5c,00,57,00,49,00,4e,00,44,00,4f,00,57,00,53,00,5c,00,73,\  
  00,79,00,73,00,74,00,65,00,6d,00,33,00,32,00,5c,00,73,00,68,00,65,00,6c,00,\  
  6c,00,33,00,32,00,2e,00,64,00,6c,00,6c,00,00,00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\Instance]  
"CLSID"="{0E5AAE11-A475-4c5b-AB00-C66DE400274E}"  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\Instance\InitPropertyBag]  
"Attributes"=dword:00000011  
"TargetFolderPath"=hex(2):44,00,3a,00,5c,00,00,00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\ShellFolder]  
"FolderValueFlags"=dword:00000028  
"Attributes"=dword:f080004d  
  
[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\HideDesktopIcons\NewStartPanel]  
"{0525388b-89d9-4112-bf4d-2aaccb716a7f}"=dword:00000001  
  
[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace\{0525388b-89d9-4112-bf4d-2aaccb716a7f}]  
@="D: Drive"`

 Press **Ctrl + S**, name the file **add-d-drive-file-explorer.reg**, and then click **Save**. Don’t forget to add the REG file extension to let Windows know it’s working with a Registry file.

![saving a registry file in Notepad on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/save-reg-file-add-drive-nav-pane.jpg)
<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Next, double-click the Registry file you just created and click **Yes** on the UAC prompt. You’ll then be asked if you want to continue with the merge, so click **Yes**. Afterward, press **Win + E** to open File Explorer.

![the D drive showing in the bottom section of the Navigation pane on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/d-drive-nav-pane.jpg)
<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The D: drive should now be visible in the bottom part of the Navigation pane.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->
## How Do I Remove the D: Drive From the Navigation Pane in File Explorer?

 To remove the D: drive from the navigation pane, open Notepad and then copy and paste the below text:

`Windows Registry Editor Version 5.00  
  
[-HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}][HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\HideDesktopIcons\NewStartPanel]  
"{0525388b-89d9-4112-bf4d-2aaccb716a7f}"=-  
  
[-HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace\{0525388b-89d9-4112-bf4d-2aaccb716a7f}]`

 Save the file as **remove-d-drive-file-explorer.reg**. Afterward, double-click the registry file and click **Yes** on the UAC prompt. When asked if you want to continue with the merge, click **Yes** again.

 Now the D: drive should be gone from the navigation pane in File Explorer.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->
## Create an Easier Way to Access the D: Drive on Your Windows Computer

 With this guide, you will remove an extra step when accessing the D: drive on your Windows computer. Once you have created the registry files, adding and removing the D: drive from the Navigation pane will be easy. While the registry files are safe, don’t forget to create a backup of your Registry or a system restore point for good measure.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-blue.techidaily.com/new-curated-interview-insights-engaging-podcast-audience-for-2024/"><u>[New] Curated Interview Insights  Engaging Podcast Audience for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-decrypting-the-mystery-understanding-unlisted-content-on-youtube/"><u>[New] In 2024, Decrypting the Mystery  Understanding 'Unlisted' Content on YouTube</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-cut-to-perfection-producing-captivating-loop-content-for-instagram/"><u>[Updated] 2024 Approved  Cut to Perfection  Producing Captivating Loop Content for Instagram</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-a-nostalgic-journey-through-time-with-stop-motion-classics/"><u>[Updated] A Nostalgic Journey Through Time with Stop-Motion Classics</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-beautys-buzz-youtube-gurus-predicted-for-2024/"><u>[Updated] Beauty's Buzz  YouTube Gurus Predicted for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-beyond-borders-blurring-techniques-for-global-audienes/"><u>[Updated] Beyond Borders  Blurring Techniques for Global Audienes</u></a></li>
<li><a href="https://windows11.techidaily.com/11-fixes-if-windows-10-cant-detect-a-wi-fi-network/"><u>11 Fixes if Windows 10 Can’t Detect a Wi-Fi Network</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-leap-into-action-how-to-craft-slow-motion-videos-using-gopro-hero-10/"><u>2024 Approved  Leap Into Action  How to Craft Slow-Motion Videos Using GoPro Hero 10</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-mastering-instagram-picture-perfection-expert-tips-unveiled/"><u>2024 Approved  Mastering Instagram Picture Perfection  Expert Tips Unveiled</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-ultimate-guide-using-old-school-film-tricks-today/"><u>2024 Approved  Ultimate Guide  Using Old-School Film Tricks Today</u></a></li>
<li><a href="https://windows11.techidaily.com/7-ways-to-get-the-most-out-of-windows-11/"><u>7 Ways to Get the Most Out of Windows 11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/a-showcase-of-excellence-the-best-9-platforms-for-accessing-3d-font-innovations/"><u>A Showcase of Excellence  The Best 9 Platforms for Accessing 3D Font Innovations</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerating-windows-11-app-launches/"><u>Accelerating Windows 11 App Launches</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-services-that-dont-launch/"><u>Addressing Windows Services That Don't Launch</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-tips-for-adding-sound-in-snipping-tool-recordings-max-156/"><u>Advanced Tips for Adding Sound in Snipping Tool Recordings (Max 156)</u></a></li>
<li><a href="https://windows11.techidaily.com/analyzing-space-efficiency-of-windows-software/"><u>Analyzing Space Efficiency of Windows Software</u></a></li>
<li><a href="https://windows11.techidaily.com/arp-cache-in-windows-what-and-how-to-purge/"><u>ARP Cache in Windows: What and How to Purge?</u></a></li>
<li><a href="https://windows11.techidaily.com/beneath-the-surface-innocent-looking-apps-steal-speed-from-pcs/"><u>Beneath the Surface, Innocent-Looking Apps Steal Speed From PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/breached-byte-bastion-maintain-reflect-then-switch/"><u>Breached Byte Bastion: Maintain, Reflect, Then Switch</u></a></li>
<li><a href="https://windows11.techidaily.com/cep-library-integration/"><u>CEP Library Integration</u></a></li>
<li><a href="https://windows11.techidaily.com/circumventing-unyielding-power-switches-on-windows-11/"><u>Circumventing Unyielding Power Switches on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/clear-sighted-making-your-windows-11-taskbar-glossy/"><u>Clear-Sighted: Making Your Windows 11 Taskbar Glossy</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-the-obscure-fixing-white-out-screens-in-win1011/"><u>Clearing the Obscure: Fixing White Out Screens in WIN10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-the-confusion-of-microsoft-store-error-0x80072efd/"><u>Clearing Up the Confusion of Microsoft Store Error 0X80072EFD</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-windows-arp-caches-made-simple/"><u>Clearing Windows ARP Caches Made Simple</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/comprehensive-overview-of-what-ray-tracing-entails/"><u>Comprehensive Overview of What Ray Tracing Entails</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-windows-11-parental-restrictions-guide/"><u>Configuring Windows 11 Parental Restrictions Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-incompatible-drivers-on-windows-11/"><u>Correcting Incompatible Drivers on Windows 11</u></a></li>
<li><a href="https://fox-info.techidaily.com/cross-service-song-matching-sharing-your-musical-journey/"><u>Cross-Service Song Matching  Sharing Your Musical Journey</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-home-screen-preferences-on-w11-os/"><u>Customizing Home Screen Preferences on W11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/design-dilemma-overcoming-unexpected-screen-shades/"><u>Design Dilemma: Overcoming Unexpected Screen Shades</u></a></li>
<li><a href="https://windows11.techidaily.com/detailed-steps-for-running-sfc-in-windows-os/"><u>Detailed Steps for Running SFC in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-how-to-optimize-win11-taskbar/"><u>Discover How to Optimize Win11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/discovering-surface-laptop-studio-2-near-flawless-for-makers/"><u>Discovering Surface Laptop Studio 2: Near-Flawless for Makers</u></a></li>
<li><a href="https://windows11.techidaily.com/discreet-toolbar-tactics-concealing-items-in-windows-11/"><u>Discreet Toolbar Tactics: Concealing Items in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/display-number-and-caps-lock-status-in-taskbar-tray-win11/"><u>Display Number and Caps Lock Status in Taskbar Tray Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/distinguishing-key-features-of-exe-and-msi-formats/"><u>Distinguishing Key Features of EXE and MSI Formats</u></a></li>
<li><a href="https://windows11.techidaily.com/diving-deep-using-the-netstat-command-in-windows-11-os/"><u>Diving Deep: Using the Netstat Command in Windows 11 OS</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/enhance-watchability-with-full-screen-on-fb-videos/"><u>Enhance Watchability with Full-Screen on FB Videos</u></a></li>
<li><a href="https://win-solutions.techidaily.com/expert-solutions-for-smoother-league-of-legends-gaming-experience/"><u>Expert Solutions for Smoother League of Legends Gaming Experience</u></a></li>
<li><a href="https://win-answers.techidaily.com/expert-tips-ensuring-proper-functionality-of-radeon-software-formerly-ryzen-master/"><u>Expert Tips: Ensuring Proper Functionality of Radeon Software (Formerly Ryzen Master)</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-can-we-unlock-our-vivo-y56-5g-phone-screen-by-drfone-android/"><u>How Can We Unlock Our Vivo Y56 5G Phone Screen?</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-videos-from-lava-storm-5g-to-ipad-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Videos from Lava Storm 5G to iPad | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-guide-to-mirror-your-zte-blade-a73-5g-to-other-android-devices-drfone-by-drfone-android/"><u>In 2024, Guide to Mirror Your ZTE Blade A73 5G to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-show-wi-fi-password-on-xiaomi-redmi-note-12-4g-by-drfone-android/"><u>In 2024, How to Show Wi-Fi Password on Xiaomi Redmi Note 12 4G</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-swift-solution-for-clownfish-vocal-alteration-on-pc-systems/"><u>In 2024, Swift Solution for Clownfish Vocal Alteration on PC Systems</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-transforming-chat-frustrations-into-effective-google-meet-conversations/"><u>In 2024, Transforming Chat Frustrations Into Effective Google Meet Conversations</u></a></li>
<li><a href="https://win-blog.techidaily.com/master-fixes-the-five-best-methods-to-resolve-starting-video-on-zoom-issues/"><u>Master Fixes: The Five Best Methods To Resolve 'Starting Video on Zoom Issues'</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/poll-power-players-guide-quintessential-voting-simulations/"><u>Poll Power Players' Guide  Quintessential Voting Simulations</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/process-of-screen-sharing-vivo-y02t-to-pc-detailed-steps-drfone-by-drfone-android/"><u>Process of Screen Sharing Vivo Y02T to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/1719270325227-seeking-help-navigate-through-windows-troubles-easily/"><u>Seeking Help? Navigate Through Windows Troubles Easily</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/the-five-leading-pc-tools-for-sonys-ps1-experience/"><u>The Five Leading PC Tools for Sony's PS1 Experience</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/-streamlined-techniques-for-extracting-youtubes-image-files/"><u>Three Streamlined Techniques for Extracting Youtube’s Image Files</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>