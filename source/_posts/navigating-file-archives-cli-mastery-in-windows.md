---
title: "Navigating File Archives: CLI Mastery in Windows"
date: 2024-09-09T12:02:25.960Z
updated: 2024-09-10T12:02:25.960Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Navigating File Archives: CLI Mastery in Windows"
excerpt: "This Article Describes Navigating File Archives: CLI Mastery in Windows"
keywords: CLI Windows Navigation,Windowed File Archiving,Mastering Windows Clients,CLI Command Line Guide,File Management Tools,Archive Utilities Windows,Navigate File Systems CLI
thumbnail: https://thmb.techidaily.com/70c37a7401073f1bcbf47eb7a020f3d12c21a20e9f862ecf54abef66ad7c8a53.jpg
---

## Navigating File Archives: CLI Mastery in Windows

 Are you running out of space on your Windows PC? The best thing you can do to free up some space is to compress big files through zipping. There are plenty of third-party tools that can come in handy in this situation.

 However, if you prefer to use Command Prompt or Windows PowerShell over anything else, there are commands you can use in these utilities to zip or unzip files. So, let's check out how to zip or unzip files using Command Prompt and Windows PowerShell.

## How to Zip Files Using Command Prompt

 You can zip files through Command Prompt using the tar command. It's a command line tool that helps you to extract files and create archives. However, this command only works in Windows 10 or later.

Here's how to zip files using Command Prompt:

1. Open the**Start Menu** by pressing the**Win** key.
2. In the search bar, type**Command Prompt** and**Run as administrator** from the right pane.
3. In the console, type the following command and press**Enter** . Replace**'Place'** with the location of the file.  
`cd Place`  
![Place of the file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/place.jpg)
4. Type**dir** and press**Enter** . It'll show the files inside the selected folder.  
![Dir command in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dir.jpg)
5. To zip all the files inside the selected folder, type the following command and press**Enter** . Replace '**Compressed** ' with the name you want to give your folder where the zip file will be stored. Also, replace '**FileExt** ' with the extension of the file you're zipping.  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135370/19272" target="_top" id="2135370">
  <img src="//a.impactradius-go.com/display-ad/19272-2135370" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135370/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
`tar -a -c -f Compressed.zip *.FileExt`  
![Tar command in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tar.jpg)
6. To zip a single file, execute the following command. Again, replace '**Compressed** ' with the name you want to give your folder where the zip file will be stored, '**FileExt** ' with your file's extension, and '**FileName** ' with the name of the file you want to zip.  
`tar -a -c -f Compressed.zip FileName.FileExt`  
![Compressing one file in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/compressing-one-file.jpg)

## How to Zip Files Using Windows PowerShell

 There are several viable ways to[create zip files on Windows](https://www.makeuseof.com/easy-ways-create-zip-file-windows-10/) . One of these is through Windows PowerShell. However, the**tar** command doesn't work in Windows PowerShell; we'll use another command to get the work done.

Here's how to zip files using Windows PowerShell:

1. Open the Start Menu, type**Windows PowerShell,** and choose Run as administrator from the right pane.
2. In the console, type the following command and press**Enter** . Ensure to replace**file destination** and**target location** with the location of the file and the place where you want the file to be zipped, respectively. Also, replace**file name** with the name of the file you want to zip and**destination name** with the destination folder name.  
`Compress-Archive -LiteralPath 'file destination\file name' -DestinationPath 'target location\destination name'`  
![Zipping command in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/zipping.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123480/16836" target="_top" id="2123480">
  <img src="//a.impactradius-go.com/display-ad/16836-2123480" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123480/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If you want to zip multiple files, execute the following command. Replace**file destination** and**file destination 1** with the location of the first and second files, respectively. And replace**file name** and**file name 2** with the first and second file names.

`Compress-Archive -LiteralPath 'file destination\file name', 'file destination 1\file name 2 -DestinationPath 'target location\destination name'  
`

![Zipping 2 files at once](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/zipping-2.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134248/18498" target="_top" id="2134248">
  <img src="//a.impactradius-go.com/display-ad/18498-2134248" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134248/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Unzip Files Using Command Prompt

 There may be situations where you want to[unzip files on your Windows computer](https://www.makeuseof.com/unzip-files-windows-10/) . Fortunately, you can do that as well using Command Prompt. Here's how:

1. Launch Command Prompt with admin privileges.
2. Use the**cd** command to head toward the zip file's location.
3. Type the following command and press**Enter** . Replace '**Name** ' with the name of the zip file.  
`tar -xf Name.zip`  
![Unzipping file in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unzipping-file.jpg)

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014853/22899" target="_top" id="2014853">
  <img src="//a.impactradius-go.com/display-ad/22899-2014853" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014853/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
You've successfully unzipped the file.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130887/7443" target="_top" id="2130887">
  <img src="//a.impactradius-go.com/display-ad/7443-2130887" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130887/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Unzip Files Using Windows PowerShell

 Windows PowerShell lets you quickly unzip files on your computer. Here's how to do that:

1. Open Windows PowerShell with admin rights.
2. Type the following command and press**Enter** . Make sure to replace <**file** **destination** \> and <**target** **location** \> with the location of the zip file and the place where you want the file to be unzipped, respectively.  
`Expand-Archive -LiteralPath <file destination> -DestinationPath <target location>`  
![Unzipping file in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unzipping.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134218/18498" target="_top" id="2134218">
  <img src="//a.impactradius-go.com/display-ad/18498-2134218" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134218/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135405/19272" target="_top" id="2135405">
  <img src="//a.impactradius-go.com/display-ad/19272-2135405" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135405/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Save Up Space on Windows 11 by Zipping Your Files

 As a Windows user, you will always come across situations where you want to zip or unzip files. However, if you don't want to use a third-party tool, you can use Command Prompt and Windows PowerShell to quickly zip and unzip files on Windows using the above methods.

 Meanwhile, you might be interested in learning a few important Command Prompt commands.


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
<li><a href="https://facebook-clips.techidaily.com/new-from-strangers-to-community-your-facebook-onboarding-journey-for-2024/"><u>[New] From Strangers to Community Your Facebook Onboarding Journey for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-facetimes-role-in-modern-communication-best-practices-for-recording-calls/"><u>[New] In 2024, FaceTime's Role in Modern Communication Best Practices for Recording Calls</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-mastering-zoom-segregation-techniques-quickstart/"><u>[New] In 2024, Mastering Zoom Segregation Techniques Quickstart</u></a></li>
<li><a href="https://article-files.techidaily.com/new-infusing-impact-best-practices-for-podcast-graphics-for-2024/"><u>[New] Infusing Impact Best Practices for Podcast Graphics for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-2024-approved-expert-tips-for-youtube-channel-aesthetics-finding-optimal-sizes/"><u>[Updated] 2024 Approved Expert Tips for YouTube Channel Aesthetics Finding Optimal Sizes</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-2024-approved-professionalizing-slides-with-youtube-videos/"><u>[Updated] 2024 Approved Professionalizing Slides with YouTube Videos</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-facebooks-premier-playlist-best-of-the-music-videos/"><u>[Updated] Facebook's Premier Playlist Best of the Music Videos</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-empowering-education-guide-for-film-infused-curricula/"><u>[Updated] In 2024, Empowering Education Guide for Film-Infused Curricula</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-in-2024-lens-legends-library-your-query-guide/"><u>[Updated] In 2024, Lens Legends' Library Your Query Guide</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-ultimate-zoom-strategy-for-videoleap-videos/"><u>[Updated] The Ultimate Zoom Strategy for Videoleap Videos</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-full-examination-of-razer-kiyo-cam/"><u>2024 Approved Full Examination of Razer Kiyo Cam</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-masters-list-best-sierra-dvd-software/"><u>2024 Approved Master's List Best Sierra DVD Software</u></a></li>
<li><a href="https://extra-information.techidaily.com/a-deeper-look-at-vivas-video-capabilities-for-2024/"><u>A Deeper Look at Viva's Video Capabilities for 2024</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/breeze-into-adventures-compiling-top-7-free-chatgpt-itinerary-apps/"><u>Breeze Into Adventures: Compiling Top 7 Free ChatGPT Itinerary Apps</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/comprehensive-tutorial-on-stellar-repair-software-version-8-for-windows-user-guide/"><u>Comprehensive Tutorial on Stellar Repair Software Version 8 for Windows - User Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-level-strategies-for-mastering-windows-voice-access/"><u>Expert-Level Strategies for Mastering Windows Voice Access</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-offline-issues-a-solution-for-steam-and-windows/"><u>Fixing Offline Issues: A Solution for Steam and Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-locate-missing-gateway-ubisofts-launcher/"><u>How To Locate Missing Gateway: Ubisoft's Launcher</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-recover-from-network-not-found-error-windows/"><u>How to Recover From 'Network Not Found' Error Windows</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-vpna-to-fake-gps-location-on-oppo-find-x7-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, Complete Tutorial to Use VPNa to Fake GPS Location On Oppo Find X7 Ultra | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-asus-rog-phone-8-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Asus ROG Phone 8 to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-mastering-xml-files-in-final-cut-pro-x-the-ultimate-guide/"><u>In 2024, Mastering XML Files in Final Cut Pro X The Ultimate Guide</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-precision-and-performance-gamers-equipment-showcase/"><u>In 2024, Precision & Performance Gamer's Equipment Showcase</u></a></li>
<li><a href="https://windows11.techidaily.com/inside-look-windows-executable-and-linker-format-pe/"><u>Inside Look: Windows' Executable & Linker Format (PE)</u></a></li>
<li><a href="https://windows11.techidaily.com/instant-relief-guaranteed-solution-to-boot-time-sound-service-fix/"><u>Instant Relief: Guaranteed Solution to Boot-Time Sound Service Fix</u></a></li>
<li><a href="https://extra-skills.techidaily.com/integrating-music-into-unboxing-videos-a-comprehensible-manual-for-2024/"><u>Integrating Music Into Unboxing Videos A Comprehensible Manual for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/leap-from-voice-to-phrase-transcribing-with-whisper-for-windows/"><u>Leap From Voice to Phrase: Transcribing with Whisper for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/minimizing-windows-extender-lowering-cpu-demand/"><u>Minimizing Windows Extender: Lowering CPU Demand</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/modern-and-chic-mobility-detailed-insights-on-swagtron-swagger-electric-scooter/"><u>Modern & Chic Mobility: Detailed Insights on Swagtron Swagger Electric Scooter</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-art-of-ping-utilization-windows-style/"><u>Navigating the Art of Ping Utilization Windows-Style</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-your-window-experience-essential-product-key-insights/"><u>Optimize Your Window Experience: Essential Product Key Insights</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-common-connectivity-hurdles-with-7-obs-fixes/"><u>Overcoming Common Connectivity Hurdles with 7 OBS Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/perfectly-setup-your-external-drives-in-newest-os-win11/"><u>Perfectly Setup Your External Drives in Newest OS, Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/priority-toolkit-best-free-resources-for-win11-power/"><u>Priority Toolkit: Best Free Resources for Win11 Power</u></a></li>
<li><a href="https://extra-resources.techidaily.com/pros-best-top-8-tripods-excelling-at-4k-video-capture/"><u>Pro's Best Top 8 Tripods Excelling at 4K Video Capture</u></a></li>
<li><a href="https://windows11.techidaily.com/rapid-rendezvous-initiating-startup-unlocking-notepad/"><u>Rapid Rendezvous: Initiating Startup, Unlocking Notepad</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstating-lost-gesture-control-on-pcs-running-windows/"><u>Reinstating Lost Gesture Control on PCs Running Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/resetting-dns-cache-a-quick-tutorial-for-windows-users/"><u>Resetting DNS Cache: A Quick Tutorial for Windows Users</u></a></li>
<li><a href="https://tech-revival.techidaily.com/resolving-the-chatgpt-is-currently-unavailable-message-in-windows-a-step-by-step-guide/"><u>Resolving the 'ChatGPT Is Currently Unavailable' Message in Windows: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-dormant-wsreset-utility-on-computers/"><u>Restoring Dormant WSReset Utility on Computers</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-way-to-refresh-your-windows-update-system/"><u>Seamless Way to Refresh Your Windows Update System</u></a></li>
<li><a href="https://windows11.techidaily.com/sneak-peek-into-windows-11s-undercover-menus/"><u>Sneak Peek Into Windows 11'S Undercover Menus</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-to-microsoft-error-code-x00000000/"><u>Solutions to Microsoft Error Code X00000000</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-monitorscape-crafting-individual-themes-for-each-window-of-win-1011/"><u>Tailored Monitorscape: Crafting Individual Themes for Each Window of Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-how-to-for-creating-a-mobile-hotspot-with-win-11/"><u>The Ultimate How-To for Creating a Mobile Hotspot with Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-discrepancies-in-discords-windows-game-detection/"><u>Troubleshooting Discrepancies in Discord's Windows Game Detection</u></a></li>
<li><a href="https://windows11.techidaily.com/unblock-file-uploads-mastering-chromes-sync-on-a-win-os/"><u>Unblock File Uploads: Mastering Chrome's Sync on a Win OS</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-the-pathway-for-fixing-virtualboxs-efail-error/"><u>Unblocking the Pathway for Fixing Virtualbox's E_FAIL Error</u></a></li>
<li><a href="https://windows11.techidaily.com/uninstalling-epic-launcher-on-w11-solutions-present/"><u>Uninstalling Epic Launcher on W11 - Solutions Present</u></a></li>
<li><a href="https://win-able.techidaily.com/unlock-the-secrets-of-detroit-the-game-where-consciousness-awakens-smoothly-on-your-computer/"><u>Unlock the Secrets of Detroit: The Game Where Consciousness Awakens Smoothly on Your Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-efficiency-the-guide-to-windows-print-tools/"><u>Unlocking Efficiency: The Guide to Windows Print Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/updating-old-pcs-think-beyond-windows/"><u>Updating Old PCs? Think Beyond Windows</u></a></li>
</ul></div>
