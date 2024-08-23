---
title: "Harnessing File Operations: Techniques to Archive and Extract"
date: 2024-08-22T21:33:05.358Z
updated: 2024-08-23T21:33:05.358Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Harnessing File Operations: Techniques to Archive and Extract"
excerpt: "This Article Describes Harnessing File Operations: Techniques to Archive and Extract"
keywords: Archive & Retrieve Files,Data Archiving Methods,File Extraction Techniques,Efficient File Handling,Digital Document Preservation,Optimize File Operations,Streamline File Access
thumbnail: https://thmb.techidaily.com/b46dbabb50d5277c1ad28a5993cc958234753eefedba62d12174cf3ff84234d4.jpg
---

## Harnessing File Operations: Techniques to Archive and Extract

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

 If you want to zip multiple files, execute the following command. Replace**file destination** and**file destination 1** with the location of the first and second files, respectively. And replace**file name** and**file name 2** with the first and second file names.

`Compress-Archive -LiteralPath 'file destination\file name', 'file destination 1\file name 2 -DestinationPath 'target location\destination name'  
`

![Zipping 2 files at once](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/zipping-2.jpg)

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35408920&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/FR-200-1.png" border="0">Glarysoft File Recovery Pro - Helps to recover your lost file/data, even permanently deleted data. </a>
<!-- affiliate ads end -->
## How to Unzip Files Using Command Prompt

 There may be situations where you want to[unzip files on your Windows computer](https://www.makeuseof.com/unzip-files-windows-10/) . Fortunately, you can do that as well using Command Prompt. Here's how:

1. Launch Command Prompt with admin privileges.
2. Use the**cd** command to head toward the zip file's location.
3. Type the following command and press**Enter** . Replace '**Name** ' with the name of the zip file.  
`tar -xf Name.zip`  
![Unzipping file in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unzipping-file.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->
You've successfully unzipped the file.

<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Unzip Files Using Windows PowerShell

 Windows PowerShell lets you quickly unzip files on your computer. Here's how to do that:

1. Open Windows PowerShell with admin rights.
2. Type the following command and press**Enter** . Make sure to replace <**file** **destination** \> and <**target** **location** \> with the location of the zip file and the place where you want the file to be unzipped, respectively.  
`Expand-Archive -LiteralPath <file destination> -DestinationPath <target location>`  
![Unzipping file in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unzipping.jpg)

<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
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
<li><a href="https://extra-lessons.techidaily.com/new-cartooncanvas-comprehensive-review-and-guidebook-24/"><u>[New] CartoonCanvas Comprehensive Review & Guidebook '24</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-correcting-audio-absence-in-obs-recordings-quickly/"><u>[New] Correcting Audio Absence in OBS Recordings Quickly</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-gaming-insiders-youtube-channels-you-should-see/"><u>[New] In 2024, Gaming Insiders' YouTube Channels You Should See</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-the-overlooked-elements-of-success-with-instagram-reels/"><u>[Updated] 2024 Approved  The Overlooked Elements of Success with Instagram Reels</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-navigating-the-download-of-fb-storied-videos/"><u>[Updated] In 2024, Navigating the Download of FB Storied Videos</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-navigating-social-surveys-instagram-stories-edition-for-2024/"><u>[Updated] Navigating Social Surveys  Instagram Stories Edition for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-prime-interactive-face-time-festivals/"><u>2024 Approved  Prime Interactive Face Time Festivals</u></a></li>
<li><a href="https://android-location-track.techidaily.com/best-anti-tracker-software-for-honor-v-purse-drfone-by-drfone-virtual-android/"><u>Best Anti Tracker Software For Honor V Purse | Dr.fone</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/cutting-clutter-effective-usage-of-photoshops-eraser-tool-for-2024/"><u>Cutting Clutter  Effective Usage of Photoshop’s Eraser Tool for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/dissecting-dji-inspire-2s-capabilities/"><u>Dissecting DJI Inspire 2'S Capabilities</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-steps-for-resolving-printer-connections-in-windows/"><u>Essential Steps for Resolving Printer Connections in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/file-explorer-misses-out-on-sd-card-heres-fixing-it/"><u>File Explorer Misses Out on SD Card - Here's Fixing It</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-call-logs-from-infinix-smart-8-hd-by-fonelab-android-recover-call-logs/"><u>How To  Restore Missing Call Logs from Infinix Smart 8 HD</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-dodge-perpetual-network-logon-errors-in-windows/"><u>How to Dodge Perpetual Network Logon Errors in Windows</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-exit-android-factory-mode-on-vivo-t2-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Exit Android Factory Mode On Vivo T2 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-mute-games-recommended-by-windows-11/"><u>How To Mute Games Recommended by Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-overcome-invalid-session-from-vac-steam-alert/"><u>How To Overcome Invalid Session From VAC Steam Alert</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-system-of-iphone-13-pro-max-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair System of iPhone 13 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/identifying-non-essential-windows-11-functions-to-turn-off/"><u>Identifying Non-Essential Windows 11 Functions to Turn Off</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-crafting-clear-and-consistent-slug-lines/"><u>In 2024, Crafting Clear and Consistent Slug Lines</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-sim-unlock-code-generators-unlock-your-motorola-moto-e13-phone-hassle-free-by-drfone-android/"><u>In 2024, The Best Android SIM Unlock Code Generators Unlock Your Motorola Moto E13 Phone Hassle-Free</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-your-step-by-step-pathway-to-recording-exceptional-tiktok-videos/"><u>In 2024, Your Step-by-Step Pathway to Recording Exceptional TikTok Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-use-of-microsoft-family-safety/"><u>Mastering the Use of Microsoft Family Safety</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-efficiency-set-predefined-app-sizes-in-win11/"><u>Maximizing Efficiency: Set Predefined App Sizes in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-cpu-performance-with-solutions-for-tiworkerexe-use/"><u>Optimize CPU Performance with Solutions for TiWorker.exe Use</u></a></li>
<li><a href="https://windows11.techidaily.com/real-time-speech-conversion-using-whisper-desktop/"><u>Real-Time Speech Conversion: Using Whisper Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/reawakening-windows-hibernate-a-practical-guide/"><u>Reawakening Windows Hibernate: A Practical Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-sound-error-error-0xc00d36b4-in-win11/"><u>Rectifying Sound Error: Error 0XC00D36B4 in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/reducing-the-overwhelming-impact-of-ntoskrnlexe/"><u>Reducing the Overwhelming Impact of Ntoskrnl.exe</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstating-hidden-pane-windows-6-procedures-in-win11/"><u>Reinstating Hidden Pane Windows: 6 Procedures in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/repairing-filesystem-issues-with-ease-on-windows-11/"><u>Repairing Filesystem Issues with Ease on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-order-7-solutions-for-lost-windows-server-time/"><u>Restoring Order: 7 Solutions for Lost Windows Server Time</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-code-0x0001-issue-geforce-software-w11/"><u>Solving Code 0X0001 Issue: GeForce Software W11</u></a></li>
<li><a href="https://windows11.techidaily.com/steering-clear-of-windows-complications-during-amd-setup/"><u>Steering Clear of Windows Complications During AMD Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/suppress-windows-extra-audio-functionality/"><u>Suppress Windows Extra Audio Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/surge-speed-settings-preventing-unexpected-download-plunges/"><u>Surge Speed Settings: Preventing Unexpected Download Plunges</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-disable-discord-auto-updates-at-bootup/"><u>Techniques to Disable Discord Auto-Updates at Bootup</u></a></li>
<li><a href="https://windows11.techidaily.com/the-easy-way-out-windows-11s-silencing-methods/"><u>The Easy Way Out: Windows 11'S Silencing Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/the-enigma-of-windows-11s-invisibles-menus-and-tools/"><u>The Enigma of Windows 11'S Invisibles Menus and Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-steps-to-open-windows-media-player/"><u>The Essential Steps to Open Windows Media Player</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-methods-for-resolving-windows-interface-dispute/"><u>Top 5 Methods for Resolving Windows Interface Dispute</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/treacle-tracking-step-by-step-tutorial-on-summer-snack-monitoring-for-2024/"><u>Treacle Tracking  Step-by-Step Tutorial on Summer Snack Monitoring for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-common-errors-in-microsoft-office-windows/"><u>Troubleshooting Common Errors in Microsoft Office Windows</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-cutting-edge-video-editing-top-3-4k8k-software-solutions/"><u>Updated Cutting-Edge Video Editing Top 3 4K/8K Software Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/what-makes-windows-11s-limited-functionality-beneficial/"><u>What Makes Windows 11’S Limited Functionality Beneficial?</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-ispoofer-update-on-samsung-galaxy-a05-drfone-by-drfone-virtual-android/"><u>Will iSpoofer update On Samsung Galaxy A05 | Dr.fone</u></a></li>
</ul></div>
