---
title: The Ultimate Tutorial for Managing Archive Files via CMD
date: 2024-06-25T11:59:46.419Z
updated: 2024-06-26T11:59:46.419Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Ultimate Tutorial for Managing Archive Files via CMD
excerpt: This Article Describes The Ultimate Tutorial for Managing Archive Files via CMD
keywords: CmdArchiveManagement,ArchiveFilesCmdTutorial,FileBackupCMDGuide,CMDFileOrganization,TutArchiveCmdUse,MasteringArchivesCmd,OptimizeCmdArchive
thumbnail: https://thmb.techidaily.com/359889cca1fac1d0cab50a3e170aa122469e4b901fffff3859c0a0ef7a4f048d.jpg
---

## The Ultimate Tutorial for Managing Archive Files via CMD

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

## How to Unzip Files Using Command Prompt

 There may be situations where you want to[unzip files on your Windows computer](https://www.makeuseof.com/unzip-files-windows-10/) . Fortunately, you can do that as well using Command Prompt. Here's how:

1. Launch Command Prompt with admin privileges.
2. Use the**cd** command to head toward the zip file's location.
3. Type the following command and press**Enter** . Replace '**Name** ' with the name of the zip file.  
`tar -xf Name.zip`  
![Unzipping file in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unzipping-file.jpg)

You've successfully unzipped the file.

## How to Unzip Files Using Windows PowerShell

 Windows PowerShell lets you quickly unzip files on your computer. Here's how to do that:

1. Open Windows PowerShell with admin rights.
2. Type the following command and press**Enter** . Make sure to replace <**file** **destination** \> and <**target** **location** \> with the location of the zip file and the place where you want the file to be unzipped, respectively.  
`Expand-Archive -LiteralPath <file destination> -DestinationPath <target location>`  
![Unzipping file in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unzipping.jpg)

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
<li><a href="https://windows11.techidaily.com/power-preservation-pitfalls-the-reality-of-modern-standby/"><u>Power Preservation Pitfalls: The Reality of Modern Standby</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reach-windows-11s-account-control-interface/"><u>How to Reach Windows 11'S Account Control Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reactivate-grammarly-on-microsoft-devices/"><u>How To Reactivate Grammarly on Microsoft Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-guide-vmware-crashes-bsod-on-win11/"><u>Troubleshooting Guide: VMware Crashes, BSOD on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-11-and-galaxy-ties-with-samsung-dex/"><u>Unveiling Windows 11 & Galaxy Ties with Samsung DeX</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resurrect-a-dormant-windows-tab-key/"><u>Steps to Resurrect a Dormant Windows Tab Key</u></a></li>
<li><a href="https://windows11.techidaily.com/highest-rated-windows-encryption-software-guide-150-chars/"><u>Highest Rated Window's Encryption Software Guide (150 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/transforming-ideas-into-art-the-best-drawing-apps-ranked-in-win10/"><u>Transforming Ideas Into Art: The Best Drawing Apps Ranked in Win10</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-power-saving-paradox-modern-standbys-dilemni/"><u>Windows' Power-Saving Paradox: Modern Standby's Dilemni</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-2024-approved-resizing-your-video-how-to-change-aspect-ratio-in-final-cut-pro/"><u>Updated 2024 Approved Resizing Your Video How to Change Aspect Ratio in Final Cut Pro</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-discover-top-6-short-video-download-sites-free/"><u>[New] In 2024, Discover Top 6 Short Video Download Sites (FREE)</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/mastering-the-art-of-freefire-a-gaming-youtubers-guide-for-2024/"><u>Mastering the Art of FreeFire  A Gaming Youtuber’s Guide for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/apex-thrill-racers-our-favorites-5/"><u>Apex Thrill Racers  Our Favorites (5)</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-apple-iphone-se-2020-ios-system-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair Apple iPhone SE (2020) iOS System? | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/detailed-tutorial-on-screen-capturing-in-online-meetings-google-for-2024/"><u>Detailed Tutorial on Screen Capturing in Online Meetings (Google) for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-podcast-titling-evolution-10-ai-generators-to-watch/"><u>2024 Approved  Podcast Titling Evolution  10 AI Generators to Watch</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-optimal-activities-coexisting-with-listening-podcasts/"><u>[Updated] Optimal Activities Coexisting with Listening Podcasts</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/all-about-factory-reset-what-is-it-and-what-it-does-to-your-nokia-c22-drfone-by-drfone-reset-android-reset-android/"><u>All About Factory Reset, What Is It and What It Does to Your Nokia C22? | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/6-fixes-to-unfortunately-whatsapp-has-stopped-error-popups-on-samsung-galaxy-f04-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Fixes to Unfortunately WhatsApp has stopped Error Popups On Samsung Galaxy F04 | Dr.fone</u></a></li>
</ul></div>
