---
title: "Unzipping & Zipping Made Easy: Windows Command Line Guidebook"
date: 2024-10-06T10:27:38.184Z
updated: 2024-10-07T01:11:49.304Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unzipping & Zipping Made Easy: Windows Command Line Guidebook"
excerpt: "This Article Describes Unzipping & Zipping Made Easy: Windows Command Line Guidebook"
keywords: Command Line Zipping,Command Line Unzip,Windows Cmd Guide,Easy File Compression,Compress Files in Cmd,Zip Windows Commands,Unzipping Command Tools
thumbnail: https://thmb.techidaily.com/32e2647cfec7540fd7d33c1c66a7dde730efec2830801400ac767081505a0953.jpg
---

## Unzipping & Zipping Made Easy: Windows Command Line Guidebook

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

<!-- affiliate ads begin -->
<span id="1531879">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1531879.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1531879">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1531879.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1531879%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1531879/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://aligracehair.sjv.io/c/5597632/2006919/19272" target="_top" id="2006919">
  <img src="//a.impactradius-go.com/display-ad/19272-2006919" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006919/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Unzip Files Using Command Prompt

 There may be situations where you want to[unzip files on your Windows computer](https://www.makeuseof.com/unzip-files-windows-10/) . Fortunately, you can do that as well using Command Prompt. Here's how:

1. Launch Command Prompt with admin privileges.
2. Use the**cd** command to head toward the zip file's location.
3. Type the following command and press**Enter** . Replace '**Name** ' with the name of the zip file.  
`tar -xf Name.zip`  
![Unzipping file in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unzipping-file.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528700/16446" target="_top" id="1528700">
  <img src="//a.impactradius-go.com/display-ad/16446-1528700" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528700/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

You've successfully unzipped the file.

## How to Unzip Files Using Windows PowerShell

 Windows PowerShell lets you quickly unzip files on your computer. Here's how to do that:

1. Open Windows PowerShell with admin rights.
2. Type the following command and press**Enter** . Make sure to replace <**file** **destination** \> and <**target** **location** \> with the location of the zip file and the place where you want the file to be unzipped, respectively.  
`Expand-Archive -LiteralPath <file destination> -DestinationPath <target location>`  
![Unzipping file in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unzipping.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043618/7443" target="_top" id="2043618">
  <img src="//a.impactradius-go.com/display-ad/7443-2043618" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043618/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://program-issues.techidaily.com/fixed-wow-screen-flickering-issue/"><u>[FIXED] WOW Screen Flickering Issue</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-2024-approved-comparing-apples-with-oranges-not-when-it-comes-to-m1-pro-and-m1-max/"><u>[New] 2024 Approved Comparing Apples with Oranges? Not When It Comes to M1 Pro & M1 Max</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-how-to-change-background-on-teams-before-or-after-calling/"><u>[Updated] 2024 Approved How to Change Background on Teams Before or After Calling</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-androids-elite-mobile-multiplayer-battle-games-for-2024/"><u>[Updated] Android's Elite Mobile Multiplayer Battle Games for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-farm-management-mastery-for-stardews-ginger-isles/"><u>[Updated] In 2024, Farm Management Mastery for Stardew's Ginger Isles</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-expert-guide-to-screen-zooming-on-microsoft-teams/"><u>2024 Approved Expert Guide to Screen Zooming on Microsoft Teams</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-should-itop-top-your-list-for-screen-recorders/"><u>2024 Approved Should ITop Top Your List for Screen Recorders?</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/expanding-your-instagram-audience-step-by-step-for-2024/"><u>Expanding Your Instagram Audience Step-by-Step for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-unblock-chrome-from-firewall-settings-on-windows-1011/"><u>How to Unblock Chrome From Firewall Settings on Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/keyboard-tricks-for-immediate-translation-on-modern-windows-os/"><u>Keyboard Tricks for Immediate Translation on Modern Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/launching-linux-virtualization-effortlessly-within-hyper-v-windows/"><u>Launching Linux Virtualization Effortlessly Within Hyper-V Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/post-cortana-windows-the-next-4-interfaces/"><u>Post-Cortana Windows: The Next 4 Interfaces</u></a></li>
<li><a href="https://fox-direct.techidaily.com/the-ultimate-guide-to-lightroom-for-hdr-image-creation-for-2024/"><u>The Ultimate Guide to Lightroom for HDR Image Creation for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-generation-gauge-guide/"><u>Windows Generation Gauge Guide</u></a></li>
</ul></div>

