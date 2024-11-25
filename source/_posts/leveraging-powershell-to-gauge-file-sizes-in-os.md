---
title: Leveraging PowerShell to Gauge File Sizes in OS
date: 2024-11-18T19:28:24.047Z
updated: 2024-11-25T02:30:24.968Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Leveraging PowerShell to Gauge File Sizes in OS
excerpt: This Article Describes Leveraging PowerShell to Gauge File Sizes in OS
keywords: PowerShell File Analysis,Checking File Size with PS,File Size Monitoring Using PowerShell,PowerShell for File Sizing Data,Extract File Sizes via PowerShell,Measuring Files in OS with PowerShell,PowerShell Script for File Size Evaluation
thumbnail: https://thmb.techidaily.com/517296fb76b2495d3ca7ac9af3e02d36cfd22dc3a1d76f74a4f77913c7df7881.jpg
---

## Leveraging PowerShell to Gauge File Sizes in OS

 If you want to investigate which folders are taking up your storage space, you can check the folder's size to determine what's hogging your drive. Checking folder size is also helpful if you need to move a large folder to a USB drive or cloud storage. An easy way to do this on Windows is to use File Explorer and open the folder Properties dialog.

 File Explorer, however, can be slow to determine the size of a large folder. And not ideal if you want to manage files and folders on multiple computers in an organization. To remedy this, you can use PowerShell to quickly calculate folder sizes on Windows.

## How to Calculate a Folder's Size Using PowerShell on Windows

![powershell cmdlet to view folder size bytes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/powershell-cmdlet-to-view-folder-size-bytes.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-0Ww1YIIUe4?si=cQ-Gkh9UCJABuPZU&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To calculate a folder's size, you'll need to use the two PowerShell cmdlets, Get-ChildItem and Measure-Object, followed by the Length property and Sum parameter.

 The cmdlet Get-ChildItem lets you retrieve information from a specified directory and its sub-directories. The Measure-Object cmdlet and the associated properties and parameters calculate the sum of the length property for the items returned by the Get-ChildItem (alias 'cgi') cmdlet.

 If you are new to PowerShell, you may want to read our explainer on [essential PowerShell cmdlets](https://www.makeuseof.com/windows-powershell-commands-cmdlets/) to understand the basics of PowerShell.

 Now that you are familiar with the PowerShell commands, here is how to use them to get any folder size.

1. Press the **Win** key and type **powershell**.
2. Next, right-click on **Windows PowerShell** and select **Run as administrator**. Click **Yes** if prompted by **User Account Control**.
3. In the PowerShell window, type the following command:  
`Get-ChildItem FolderPath | Measure-Object -Property Length -sum`
4. In the above command, replace **FolderPath** with the directory path where your folder is saved. For example, if you want to calculate the size of the Download folder located in the **E:\\** drive, then the full command will look like this:  
`Get-ChildItem E:\Download | Measure-Object -Property Length -sum`
5. The return will show the item count in the folder and its size in bytes. You'll need to divide the total sum by **1024** to get the size in **KBs** (Kilobytes). Divide it by **1024** again to get the size in **MBs** (Megabytes) and so on.

 Alternatively, you can use the .sum property to retrieve the total size and divide it by 1 million or billion to convert it into megabytes or gigabytes.

![powershell cmdlet to view folder size megabytes gigabytes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/powershell-cmdlet-to-view-folder-size-megabytes-gigabytes.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8U3ooyFiAB4?si=yXPQrDhMBEJwN2EZ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 For example, if you want to know the value in gigabytes (MBs), type the following command and press **Enter**:

`(gci E:\Download | measure Length -s).sum / 1Mb`

 Similarly, replace **1Mb** with **1Gb** to retrieve the folder size in gigabytes.

`(gci E:\Download | measure Length -s).sum / 1Gb`

 If you want to identify the size of specific types of files in a directory, you can use the wildcard character **\*** followed by the file extension type. It will only show the file size for the specified file type.

 For example, to find how much space is taken by the images in a folder, use the following command:

![powershell cmdlet to view folder by file type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/powershell-cmdlet-to-view-folder-by-file-type.jpg)

`(gci E:\download *.jpg | measure Length -s).sum / 1Mb`

 Adding a wildcard character lets you determine if a specific file type takes the most space in the folder. You can then filter the contents based on the file extension and delete or move them if necessary.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qmQjRcnaq9g?si=jadcGtXemUAlKOTa&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Get the Subfolder Size Using PowerShell

![powershell cmdlet to view folder subfolder size](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/powershell-cmdlet-to-view-folder-subfolder-size.jpg)

 The above command will only calculate the size of your primary directory or folder. To calculate the total size of files in the specified directory and its subdirectories, you'll need to add the **\-Recurse** parameter to the above command. In addition, we'll use the -force parameter to access hidden and system files.

 For example, to get the total size of your C:\\Users directory and its subdirectories, including the hidden files, the PowerShell command will look something like this:

`((gci -force c:\Users -Recurse -ErrorAction SilentlyContinue| measure Length -s).sum / 1Gb)`

 The output in this instance shows 54 GB approx. as the total size of the c:\\users folder. In the above command, the -ErrorAction SilentlyContinue parameter is used to suppress any error messages that may occur during the process.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0pSRlspzW-A?si=A82G3Yxwj_31cKDq&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Get the Subfolder Size in a Table Format Using PowerShell

![windows powershell ISE script folder size view](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-powershell-ise-script-folder-size-view.jpg)

 If you want to know the size of all the subfolders individually, you can run a PowerShell script to get a graphical view of all the subfolders and their sizes. A script is usually helpful if you have a large directory with multiple subfolders and need to work on them frequently.

 To run this script, you can use PowerShell ISE. Here's how to do it:

1. Press the **Win key** and type **PowerShell ISE**. Click on **Windows PowerShell ISE** from the search result.  
![powershell ise start menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/powershell-ise-start-menu.jpg)
2. Next, copy and paste the following command into the PowerShell ISE console. Make sure to change the directory from c:\\ to your preferred directory.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aknYnDfODro?si=zONIVzA9FFq0rLOD&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`$targetfolder = 'C:\'  
$dataColl = Get-ChildItem -Force $targetfolder -Directory -ErrorAction SilentlyContinue | ForEach-Object {  
   $len = Get-ChildItem -Recurse -Force $_.FullName -File -ErrorAction SilentlyContinue | Measure-Object -Property Length -Sum | Select-Object -ExpandProperty Sum  
   $foldername = $_.FullName  
   $foldersize = '{0:N2} GB' -f ($len / 1Gb)  
   [PSCustomObject]@{  
       foldername = $foldername  
       foldersizeGb = $foldersize  
   }  
}  
$dataColl | Out-GridView -Title "Size of Subdirectories in $targetfolder"`
3. Next, click **Run Script** or press **F5** and wait for the script to execute. Depending on the folder size, you'll see a "**Size Of Subdirectories**" dialog listing all the subdirectories with their size.

 In addition to this, you can make use of the PowerShell comparison operators to filter results. For example, to get file size for folders created between June 2023 and July 2023, you can use the following command:

`(gci -force E:\Download &ndash;Recurse -ErrorAction SilentlyContinue | ? {$_.CreationTime -gt '01/23/23' -AND $_.CreationTime -lt '02/23/23'}| measure Length -s).sum / 1Gb`

 In the above command, **"?"** is an alias for the **Where-Object** cmdlet, **\-gt, -AND, -It** are comparison operators, and **CreationTime** is a condition. The command checks if the CreationTime of files in the subdirectory falls within the specified date range and shows output only if the condition is satisfied. If you get an error, ensure your date and time format in the command matches the system's format and try again.

## Get the Folder and Subfolder Size Using PowerShell

 File Explorer on Windows can help you calculate the size of any folder and file. However, if you work with multiple large folders or in an organization with hundreds of computers to manage, using PowerShell can help you get things done faster.

 That said, if you prefer a more GUI-based solution, consider using a disk analyzer tool. These tools can help you visualize the system's file structure and show a report detailing the contents taking up most space on your system.

 File Explorer, however, can be slow to determine the size of a large folder. And not ideal if you want to manage files and folders on multiple computers in an organization. To remedy this, you can use PowerShell to quickly calculate folder sizes on Windows.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-clips.techidaily.com/new-diverging-paths-youtube-licensing-and-creative-commons/"><u>[New] Diverging Paths YouTube Licensing & Creative Commons</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-in-2024-boost-your-visuals-video-enhance-pro-22-guide/"><u>[New] In 2024, Boost Your Visuals - Video Enhance Pro 2.2 Guide</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-in-2024-decoding-the-principles-of-mixed-reality/"><u>[New] In 2024, Decoding the Principles of Mixed Reality</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-elevate-your-channels-youtubes-partner-program/"><u>[Updated] Elevate Your Channels - YouTube's Partner Program</u></a></li>
<li><a href="https://some-guidance.techidaily.com/5yid5bplusd6icf44gn44kc55cg6kej44gx44ke44gz44ge6kej6kqs77yb44ot44oh44kq55s75yop5zob6loq44gu5asj5pu044go5yuv55s744oq44k144kk44k444oz44kw5oml6acg/"><u>初心者でも理解しやすい解説！ビデオ画像品質の変更と動画リサイジング手順</u></a></li>
<li><a href="https://windows11.techidaily.com/exclusive-insight-the-ultimate-roundup-of-windows-video-tools/"><u>Exclusive Insight: The Ultimate Roundup of Windows Video Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/gamers-guide-cooling-down-the-heat-of-laptop-games/"><u>Gamer's Guide: Cooling Down the Heat of Laptop Games</u></a></li>
<li><a href="https://windows11.techidaily.com/how-microsoft-copilot-transforms-modern-software-creation/"><u>How Microsoft Copilot Transforms Modern Software Creation</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-remove-a-previously-synced-google-account-from-your-honor-x9a-by-drfone-android/"><u>How to Remove a Previously Synced Google Account from Your Honor X9a</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-resolve-microsoft-written-install-net-message/"><u>How to Resolve Microsoft' Written: Install .NET Message</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-a-quick-guide-to-oppo-a58-4g-frp-bypass-instantly-by-drfone-android/"><u>In 2024, A Quick Guide to Oppo A58 4G FRP Bypass Instantly</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-expert-tips-save-skype-call-as-mp3-free/"><u>In 2024, Expert Tips Save Skype Call as Mp3 (Free)</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-learn-to-flip-videos-a-guide-for-instagram-users/"><u>In 2024, Learn to Flip Videos A Guide for Instagram Users</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-repair-of-file-corruption-error-code-0x80070570-in-windows-11/"><u>Mastering Repair of File Corruption (Error Code 0X80070570) in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/no-more-obsolete-windows-attributes/"><u>No More: Obsolete Windows Attributes</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-to-unblock-your-windows-pin-entry/"><u>Quick Fixes to Unblock Your Windows Pin Entry</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-launching-csgo-in-windows-11/"><u>Tips for Launching CS:GO in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-11s-taskbar-features-for-tablet-users/"><u>Unveiling Windows 11'S Taskbar Features for Tablet Users</u></a></li>
<li><a href="https://common-error.techidaily.com/why-isnt-my-corsair-keyboard-lights-up-common-issues-and-repairs/"><u>Why Isn’t My Corsair Keyboard Lights Up? Common Issues and Repairs</u></a></li>
</ul></div>

