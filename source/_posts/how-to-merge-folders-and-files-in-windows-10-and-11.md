---
title: How to Merge Folders and Files in Windows 10 and 11
date: 2024-09-09T12:11:16.100Z
updated: 2024-09-10T12:11:16.100Z
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

<!-- affiliate ads begin -->
<span id="1938141">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1938141.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1938141">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1938141.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1938141%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1938141/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Merge Folders and Files in Windows 10 and 11

 Folder merging in Windows is an excellent file management idea to organize folders with similar files into one big folder. This helps avoid clutter and offers everything in one place, thus making it easier to find what you are looking for.

 That said, by default, Windows has no option to merge folders. Even though it is clever enough to identify multiple folders of the identical name at the same level, there are more efficient ways to merge folders and files in Windows 10 and 11.

 Here we show you the best ways to merge folders on a Windows 10 and 11 system. It includes the convenient File Explorer merge option, a PowerShell script hack and third-party tools to merge folders.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2129740/7443" target="_top" id="2129740">
  <img src="//a.impactradius-go.com/display-ad/7443-2129740" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2129740/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Merge Folders Using File Explorer

![confirm folder replace merge folder file explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/confirm-folder-replace-merge-folder-file-explorer.jpg)

 File Explorer will detect and prompt you to merge the folder when you try to move a folder with a name identical to an existing folder at the same level.

 For example, if you have an**XYZ** folder in**D:\\Folders** and want to merge the**XYX** folder in the same level, all you have to do is rename the**XYX** folder as**XYZ** . When the**Confirm Folder Replace** prompt appears, click**Yes** .

 Similarly, you can cut and paste the folder with identical names and then opt for the merge option. File Explorer will merge the folders and move the contents to the destination folder. If a duplicate file exists, you can opt for the**Replace** or**Skip** option.

 Conversely, this can be a time-consuming process when you have to work with hundreds of folders at a time. A more efficient way to overcome this limitation is to use a PowerShell script hack to merge folders on Windows.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115940/19272" target="_top" id="2115940">
  <img src="//a.impactradius-go.com/display-ad/19272-2115940" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115940/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Merge Folders Using a PowerShell Script

 PowerShell is a powerful automation shell utility. You can learn the[essential PowerShell cmdlets](https://www.makeuseof.com/windows-powershell-commands-cmdlets/) to automate everyday tasks with a script.

 Similarly, you can use a PowerShell script to merge folders in Windows 10 and 11\. This is a handy way to merge multiple folders without copying and pasting them one by one.

 To use the script, you must enable running scripts in Windows PowerShell. Once done, you can copy and paste the script directly onto the PowerShell window without having to run it as a .ps1 file.

 To allow the local PowerShell script to Run, you’ll need to change the execution policy in the Settings app. Here’s how to do it.

![enable powershell to run local scripts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-powershell-to-run-local-scripts.jpg)

1. Press**Win + I** to open the**Settings** app.
2. Next, open the**Privacy & security** tab in the left pane.
3. Click on**For Developer** under the**Security section** .
4. Next, scroll down and click to expand the**PowerShell** section.
5. Toggle the switch to turn on **Change execution policy to allow local PowerShell scripts to run without signing** .**Require signing for remote scripts** .

 With the script running on PowerShell enabled, follow these to execute a PowerShell script to merge folders.

![merge folders powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/merge-folders-powershell.jpg)

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

### 1\. Folder Merger

![folder merger windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/folder-merger-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135349/19272" target="_top" id="2135349">
  <img src="//a.impactradius-go.com/display-ad/19272-2135349" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135349/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Folder Merger is a free utility to merge the contents of different folders into a single folder. You can add multiple source folders to the app and then merge them to a specified destination folder.

 Using Folder Merger is easy. You can add a single folder or select a root folder to add first-level subfolders. Next, click the**Destination** folder icon to set the destination folder.

 Once all the folders are added, click**Select All** to merge all the folders or individual folders using the**Ctrl** key. Click the**Merge** button to begin the merging process. Once done, click the S**how folder** icon in the**Destination** section to view your newly merged files.

 In addition, you can also choose to copy or move the files, merge files of a specific name or extension, and resolve file conflict with the skip, replace or rename option.

**Download** :[Folder Merger](https://2xdsoft.de.tl/Folder-Merger.htm) (Free)

### 2\. WinMerge

![winmerge file difference comparison](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/winmerge-file-difference-comparison.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettiit.sjv.io/c/5597632/2114263/17093" target="_top" id="2114263">
  <img src="//a.impactradius-go.com/display-ad/17093-2114263" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluettiit.sjv.io/i/5597632/2114263/17093" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137220/26400" target="_top" id="2137220">
  <img src="//a.impactradius-go.com/display-ad/26400-2137220" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137220/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-maximize-social-status-top-8-apps-for-gaining-more-fb-fans/"><u>[New] 2024 Approved Maximize Social Status Top 8 Apps for Gaining More FB Fans</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-asmr-recommendations-for-android-users-for-2024/"><u>[New] ASMR Recommendations for Android Users for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-keeping-your-creative-content-on-ios-with-ease-for-2024/"><u>[New] Keeping Your Creative Content on iOS with Ease for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-unlocking-igtvs-potential-secrets-to-attract-more-subscribers/"><u>[Updated] In 2024, Unlocking IGTV's Potential Secrets to Attract More Subscribers</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-insightful-analysis-of-modifying-photographic-genders-on-social-platforms/"><u>2024 Approved Insightful Analysis of Modifying Photographic Genders on Social Platforms</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-top-10-best-drones-for-kids-and-beginners/"><u>2024 Approved Top 10 Best Drones for Kids and Beginners</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-web-wonders-weekly-review/"><u>2024 Approved Web Wonders Weekly Review</u></a></li>
<li><a href="https://extra-information.techidaily.com/elite-gamers-top-picks-best-4k-gaming-screens/"><u>Elite Gamers' Top Picks Best 4K Gaming Screens</u></a></li>
<li><a href="https://hardware-help.techidaily.com/enhance-your-vehicle-sound-system-top-4-diy-audio-upgrades-that-dont-require-new-speakers/"><u>Enhance Your Vehicle Sound System: Top 4 DIY Audio Upgrades That Don't Require New Speakers</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-taskbar-pin-tricks-for-w11/"><u>Essential Taskbar Pin Tricks for W11</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-adjusting-winoss-hardware-assisted-scheduler-settings/"><u>Expert Tips: Adjusting WinOS's Hardware-Assisted Scheduler Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-multiple-monitor-troubles-in-windows/"><u>Fixing Multiple-Monitor Troubles in Windows</u></a></li>
<li><a href="https://driver-download.techidaily.com/get-the-latest-free-acer-f3u-series-touchpad-driver-compatible-with-windows-10/"><u>Get the Latest [Free] Acer F3U Series Touchpad Driver Compatible with Windows 10</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-xiaomi-redmi-note-12-pro-5g-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Xiaomi Redmi Note 12 Pro 5G without Losing Data | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-halt-chromiums-automatic-creation-of-new-windows-tabs/"><u>How to Halt Chromium's Automatic Creation of New Windows Tabs</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-sync-your-android-phone-with-a-windows-pc/"><u>How to Sync Your Android Phone With a Windows PC</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-forgot-iphone-passcode-again-unlock-apple-iphone-12-pro-max-without-passcode-now-drfone-by-drfone-ios/"><u>In 2024, Forgot iPhone Passcode Again? Unlock Apple iPhone 12 Pro Max Without Passcode Now | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-art-of-creating-secure-window-11-lock-patterns/"><u>Master the Art of Creating Secure Window 11 Lock Patterns</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-startup-routine-windows-exploration-guide/"><u>Mastering the Startup Routine: Windows Exploration Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/mend-cure-your-windows-11-function-key-woes/"><u>Mend: Cure Your Windows 11 Function Key Woes</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/methods-to-transfer-from-apple-iphone-8-to-android-drfone-by-drfone-transfer-from-ios/"><u>Methods to Transfer from Apple iPhone 8 to Android | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-virtual-disk-service-failures-in-windows/"><u>Navigating Through Virtual Disk Service Failures in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/regain-control-of-inactive-usb-ports-with-easy-steps-win/"><u>Regain Control of Inactive USB Ports with Easy Steps Win</u></a></li>
<li><a href="https://windows11.techidaily.com/secrets-to-overcoming-non-installed-hard-drive-dilemranacies-win-11-edition/"><u>Secrets to Overcoming Non-Installed Hard Drive Dilemranacies, Win 11 Edition</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/seeking-peak-conversation-gpt-vs-bings-ai-power/"><u>Seeking Peak Conversation: GPT Vs. Bing's AI Power</u></a></li>
<li><a href="https://screen-recording.techidaily.com/sharexs-standards-met-by-others-for-2024/"><u>ShareX's Standards Met by Others for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-engage-windows-terminal-in-quake/"><u>Steps to Engage Windows Terminal in Quake</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-windows-error-1132-in-zoom/"><u>Steps to Resolve Windows' Error 1132 in Zoom</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-repairing-fall-guys-connection-errors-on-pc/"><u>Strategies for Repairing Fall Guys Connection Errors on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/take-your-vms-speed-to-new-heights-six-techniques-for-windows/"><u>Take Your VM's Speed to New Heights - Six Techniques for Windows</u></a></li>
<li><a href="https://fake-location.techidaily.com/the-best-8-vpn-hardware-devices-reviewed-on-vivo-v29-drfone-by-drfone-virtual-android/"><u>The Best 8 VPN Hardware Devices Reviewed On Vivo V29 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/the-definitive-guide-to-nddrive-in-windows-11/"><u>The Definitive Guide to NDDrive in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-windows-key-filter-settings/"><u>The Ultimate Guide to Windows Key Filter Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-and-tricks-enhance-gaming-experience-on-windows/"><u>Tips & Tricks: Enhance Gaming Experience on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-stuck-windows-handbrake-usage/"><u>Transform Stuck Windows HandBrake Usage</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-print-spooler-down-on-windows-pcs/"><u>Troubleshooting Print Spooler Down on Windows PCs</u></a></li>
</ul></div>
