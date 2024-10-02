---
title: How to Merge Folders and Files in Windows 10 and 11
date: 2024-09-25T23:35:56.256Z
updated: 2024-10-01T19:12:43.178Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Merge Folders and Files in Windows 10 and 11
excerpt: This Article Describes How to Merge Folders and Files in Windows 10 and 11
keywords: Windows File Merging,Merge Folders Windows,Combine Files Windows,Windows Folder Unite,Windows 10 File Merge,Windows 11 Folder Join,Merge Data Windows 10/11
thumbnail: https://thmb.techidaily.com/0606343d17aebae3a6ccf71123da10011994b6e06ecf6d9900f777b0d8e36c8b.jpg
---

## How to Merge Folders and Files in Windows 10 and 11

 Folder merging in Windows is an excellent file management idea to organize folders with similar files into one big folder. This helps avoid clutter and offers everything in one place, thus making it easier to find what you are looking for.

 That said, by default, Windows has no option to merge folders. Even though it is clever enough to identify multiple folders of the identical name at the same level, there are more efficient ways to merge folders and files in Windows 10 and 11.

 Here we show you the best ways to merge folders on a Windows 10 and 11 system. It includes the convenient File Explorer merge option, a PowerShell script hack and third-party tools to merge folders.

## 1\. Merge Folders Using File Explorer

![confirm folder replace merge folder file explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/confirm-folder-replace-merge-folder-file-explorer.jpg)

 File Explorer will detect and prompt you to merge the folder when you try to move a folder with a name identical to an existing folder at the same level.

 For example, if you have an**XYZ** folder in**D:\\Folders** and want to merge the**XYX** folder in the same level, all you have to do is rename the**XYX** folder as**XYZ** . When the**Confirm Folder Replace** prompt appears, click**Yes** .

 Similarly, you can cut and paste the folder with identical names and then opt for the merge option. File Explorer will merge the folders and move the contents to the destination folder. If a duplicate file exists, you can opt for the**Replace** or**Skip** option.

 Conversely, this can be a time-consuming process when you have to work with hundreds of folders at a time. A more efficient way to overcome this limitation is to use a PowerShell script hack to merge folders on Windows.

## 2\. Merge Folders Using a PowerShell Script

 PowerShell is a powerful automation shell utility. You can learn the[essential PowerShell cmdlets](https://www.makeuseof.com/windows-powershell-commands-cmdlets/) to automate everyday tasks with a script.

 Similarly, you can use a PowerShell script to merge folders in Windows 10 and 11\. This is a handy way to merge multiple folders without copying and pasting them one by one.

 To use the script, you must enable running scripts in Windows PowerShell. Once done, you can copy and paste the script directly onto the PowerShell window without having to run it as a .ps1 file.

 To allow the local PowerShell script to Run, you’ll need to change the execution policy in the Settings app. Here’s how to do it.

![enable powershell to run local scripts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-powershell-to-run-local-scripts.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105870/7443" target="_top" id="2105870">
  <img src="//a.impactradius-go.com/display-ad/7443-2105870" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105870/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. Press**Win + I** to open the**Settings** app.
2. Next, open the**Privacy & security** tab in the left pane.
3. Click on**For Developer** under the**Security section** .
4. Next, scroll down and click to expand the**PowerShell** section.
5. Toggle the switch to turn on **Change execution policy to allow local PowerShell scripts to run without signing** .**Require signing for remote scripts** .

 With the script running on PowerShell enabled, follow these to execute a PowerShell script to merge folders.

![merge folders powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/merge-folders-powershell.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934142/19272" target="_top" id="1934142">
  <img src="//a.impactradius-go.com/display-ad/19272-1934142" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934142/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. Press the**Win** key and type**powershell** .
2. Click on**Windows PowerShell** from the search results.
3. Copy and paste the following script in the PowerShell window:  
`$sourcePath = "F:\New folder"  
$destinationPath = "E:\New folder"  
$files = Get-ChildItem -Path $sourcePath -Recurse -Filter "*.*"  
foreach($file in $files){  
    $sourcePathFile = $file.FullName  
    $destinationPathFile = $file.FullName.Replace($sourcePath, $destinationPath)  
    $exists = Test-Path $destinationPathFile  
    if(!$exists){  
        $dir = Split-Path -parent $destinationPathFile  
        if (!(Test-Path($dir))) { New-Item -ItemType directory -Path $dir }  
        Copy-Item -Path $sourcePathFile -Destination $destinationPathFile -Recurse -Force  
    }  
    else{  
        $isFile = Test-Path -Path $destinationPathFile -PathType Leaf  
        if(!$isFile){  
            Copy-Item -Path $sourcePathFile -Destination $destinationPathFile -Recurse -Force  
        }  
    }  
} `
4. In the above command, replace “**E:\\New folder** ” and “**F:\\New folder** ” with the source and destination file paths, respectively. To find the file path, right-click on the folder name you want to merge and select**Copy as the path.**
5. The above command will merge the contents of the**E:\\New folder** with the**F:\\New folder** . It will skip any duplicate file conflict to leave the original files in the destination folder unaffected.

 You can repeat the script with different file paths to merge more folders. If you encounter any error, check if the file path for the destination and source is correct.

## 2\. Merge Folders Using Third-Party Software

 If you prefer a GUI-based utility over a PowerShell script to merge files, you have a few options to choose from. Third-party merge tools for Windows offer basic merging capabilities and premium offerings catered to software and creative design professionals.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082520/7443" target="_top" id="2082520">
  <img src="//a.impactradius-go.com/display-ad/7443-2082520" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082520/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 1\. Folder Merger

![folder merger windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/folder-merger-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151890/7443" target="_top" id="2151890">
  <img src="//a.impactradius-go.com/display-ad/7443-2151890" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151890/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Folder Merger is a free utility to merge the contents of different folders into a single folder. You can add multiple source folders to the app and then merge them to a specified destination folder.

 Using Folder Merger is easy. You can add a single folder or select a root folder to add first-level subfolders. Next, click the**Destination** folder icon to set the destination folder.

 Once all the folders are added, click**Select All** to merge all the folders or individual folders using the**Ctrl** key. Click the**Merge** button to begin the merging process. Once done, click the S**how folder** icon in the**Destination** section to view your newly merged files.

 In addition, you can also choose to copy or move the files, merge files of a specific name or extension, and resolve file conflict with the skip, replace or rename option.

**Download** :[Folder Merger](https://2xdsoft.de.tl/Folder-Merger.htm) (Free)

### 2\. WinMerge

![winmerge file difference comparison](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/winmerge-file-difference-comparison.jpg)

 WinMerge serves a different purpose than Folder Merger with a clean user interface. It is an open-source differencing and merger utility for Windows. A handy tool if you want to compare multiple text documents to find the differences. It can compare text-based documents, images, web pages, and more from a folder for differences and then perform a merge.

To compare and merge documents using WinMerge:

1. Click on**File** and select**Open** .
2. Select the first file or folder and then the second file or folder. You can select up to three files or folders to cross-compare.
3. Click**Compare** to load and compare the files.
4. If it is a text file, WinMerge will highlight the difference within lines between the selected documents.
5. To merge individual changes in the document, click on the highlighted text and select**Copy from right** or**Copy to right** , depending on which version you want to merge.
6. To merge all the changes, press**Ctrl + A** to select all the text and then use the copy option. It also supports difference comparison for images, web pages, binary files and tables.

 In addition, it features support for shell integration, good plugin and archive file support with 7-Zip.

**Download** :[WinMerge](https://winmerge.org/) (Free)

## The Best Apps to Merge Files and Folders on Windows

 Windows 11 can detect and prompt copied folders in the same level to be merged. However, if you need to work with multiple folders frequently, a PowerShell script or a GUI-based tool like Folder Merger makes the task much easier.

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
<li><a href="https://instagram-videos.techidaily.com/new-step-by-step-save-instagram-videos-on-desktop-devices/"><u>[New] Step-by-Step Save Instagram Videos on Desktop Devices</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-2024-approved-break-the-ice-how-to-make-a-hit-youtube-reaction-in-just-15-minutes-or-less/"><u>[Updated] 2024 Approved Break the Ice - How to Make a Hit YouTube Reaction in Just 15 Minutes or Less</u></a></li>
<li><a href="https://windows11.techidaily.com/15-paths-to-recover-missing-windows-system-time-functionality/"><u>15 Paths to Recover Missing Windows System Time Functionality</u></a></li>
<li><a href="https://youtube-data.techidaily.com/approved-the-future-of-youtube-naming-trendsetting-tips-for-video-blogging-and-filmmaking-max-156-characters/"><u>2024 Approved The Future of YouTube Naming Trendsetting Tips for Video Blogging & Filmmaking (Max 156 Characters)</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-peak-performance-with-multi-task-proficiency-on-windows-11-pcs/"><u>Achieve Peak Performance with Multi-Task Proficiency on Windows 11 PCs</u></a></li>
<li><a href="https://technical-tips.techidaily.com/bypassing-android-wi-fi-login-challenges-effortlessly/"><u>Bypassing Android Wi-Fi Login Challenges Effortlessly</u></a></li>
<li><a href="https://windows11.techidaily.com/clarity-masterclass-fixes-that-bring-life-to-fuzzy-screens/"><u>Clarity Masterclass: Fixes That Bring Life to Fuzzy Screens</u></a></li>
<li><a href="https://windows11.techidaily.com/command-line-enhancement-for-taskmanager-windows-11/"><u>Command Line Enhancement for TaskManager (Windows 11)</u></a></li>
<li><a href="https://buynow-info.techidaily.com/comprehensive-guide-and-user-reviews-eero-pro-mesh-system-full-home-coverage/"><u>Comprehensive Guide & User Reviews: Eero Pro Mesh System - Full Home Coverage</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-c0000005-on-windows-operating-systems/"><u>Conquering C0000005 on Windows Operating Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-dual-monitor-mishaps-on-your-pc/"><u>Correcting Dual Monitor Mishaps on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-internal-audio-issues-with-audacity-windows-11/"><u>Correcting Internal Audio Issues with Audacity (Windows 11)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/critical-hardware-specification-change-only-d3d11-gpus-will-support-this-updated-engine-version/"><u>Critical Hardware Specification Change: Only D3D11 GPUs Will Support This Updated Engine Version</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722969420813-install-the-improved-killer-wireless-1535-drivers-download-today/"><u>Install the Improved Killer Wireless 1535 Drivers – Download Today!</u></a></li>
<li><a href="https://blog-min.techidaily.com/top-videobearbeitungstools-fur-pcs-mit-windows-11-8-oder-7-umfassende-bildschirmaufnahmeoptionen/"><u>Top Videobearbeitungstools Für PCs Mit Windows 11, 8 Oder 7: Umfassende Bildschirmaufnahmeoptionen</u></a></li>
<li><a href="https://win-amazing.techidaily.com/update-your-targus-displaylink-drivers-now-compatible-with-windows-1187/"><u>Update Your Targus DisplayLink Drivers Now: Compatible with Windows 11/8/7</u></a></li>
<li><a href="https://windows11.techidaily.com/1719293003975-winning-over-window-devices-no-more-naming-clashes/"><u>Winning Over Window Devices: No More Naming Clashes</u></a></li>
</ul></div>

