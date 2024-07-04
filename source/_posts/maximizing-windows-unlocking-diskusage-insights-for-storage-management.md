---
title: "Maximizing Windows: Unlocking DiskUsage Insights for Storage Management"
date: 2024-06-25T12:01:08.350Z
updated: 2024-06-26T12:01:08.350Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Maximizing Windows: Unlocking DiskUsage Insights for Storage Management"
excerpt: "This Article Describes Maximizing Windows: Unlocking DiskUsage Insights for Storage Management"
keywords: Disk Usage Analysis,Storage Optimization,Data Management Tips,Increase PC Performance,Reduce System Clutter,Windows Storage Insights,Maximize Hard Drive Space
thumbnail: https://thmb.techidaily.com/d3a69700e0cb55adae67e72e210fb2f2a9d54f1a94f5e0b261b4ccf5f3207b46.jpg
---

## Maximizing Windows: Unlocking DiskUsage Insights for Storage Management

 The DiskUsage.exe tool can be used to analyze the contents of any drive or folder on Windows 11\. DiskUsage is accessed from the command line and includes many options for filtering and refining the file data that can be output. In certain situations, this can make it far more useful than GUI tools like Storage Sense.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

## View Disk Usage of Any Drive or Folder

 The simplest way to use the DiskUsage command line tool is to get an overview of how space is currently used in almost a drive or folder. We have used the tool on Windows 11, but it is also available on Windows 10\.

1. Run the Command Prompt as an admin. If you need help, check out [how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. In Command Prompt type **DiskUsage** followed by the path to the drive or folder you want to analyze.
3. For example, to view the disk usage of the Pictures folder, type: **DiskUsage C:\\Users\\UserName\\Pictures**, and press **Enter**.  
![The disk usage command in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-cmd.jpg)
4. To see the SizeOnDisk number in a human-readable format, e.g. KB, MB, or GB, add **/h** to the end of the command.
5. In our example, this looks like **DiskUsage C:\\Users\\UserName\\Pictures /h**.  
![Disk usage date displayed in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-data.jpg)

 You can use DiskUsage to analyze any folder in the same way. You can even check internal and external drives, including the C: drive. Bear in mind that analyzing a drive such as C: will spew out a huge list of files and folders in DiskUsage.

 If using DiskUsage.exe seems too complicated, you can easily view how disk space is being used with [Storage Sense](https://www.makeuseof.com/windows-11-storage-sense-guide/).

## List All Files Larger Than a Specified Size

 You can refine the data displayed in DiskUsage based on file size. So if, for example, you only want to include files over 500MB, you can set it to ignore smaller files.

1. To only include files above a specific size, you need to add the minFileSize option to the command.
2. As an example: **DiskUsage /minFileSize=6553600 C:\\Users\\UseName\\Downloads /h**.
3. This will only look for files in Downloads larger than 50MB and then display the disk space those files occupy in that location.
4. The file size number must be entered in bytes, so you might have to convert MB to Byte using an online conversion tool.

 For a more detailed view of large files, including file name as well as size, you can use the **/u** command modifier. This allows you to list a defined number of the largest files in the drive or folder.

1. To do this type: **DiskUsage C:\\Users\\UserName\\Downloads /h /u=15**.
2. The 15 largest files in the Downloads folder will now be listed in Command Prompt.  
![file data listed in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-list.jpg)
3. You can replace the number with any other you want to use. For example, to see the top 5 files taking up space, use **/u=5**.
4. Make sure to include the **/h** option so that the output is in a format that's easy to read.

 After identifying what is taking up the most space, you can use any one of these [methods to delete large files](https://www.makeuseof.com/windows-11-delete-select-files/).

## Additional DiskUsage Command Options

 The DiskUsage tool contains several other useful options that you can use to filter the output. You can filter by filename, display reserved space, or the largest directories within the folder.

 For example, to filter by filename add **/n=installer** to the end of the command to display only files that contain the word installer.

 You can see a complete list of the options by typing **DiskUsage /?** and pressing **Enter**.

![A list of DiskUsage options in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-options.jpg)

## Analyze Drive Space With DiskUsage

 Many of the available command line tools are extremely useful for maintaining and managing your Windows PC. And as this guide shows, DiskUsage.exe is a powerful alternative to graphical UI tools such as Storage Sense if you want to really dig down into how your drive space is being used.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/quick-fixed-top-10-windows-glitch-solvers/"><u>Quick Fixed: Top 10 Windows Glitch Solvers</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-command-line-capabilities-in-latest-windows-releases/"><u>Boost Command-Line Capabilities in Latest Windows Releases</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-window-11s-missing-clickables-problem/"><u>Solving Window 11'S Missing Clickables Problem</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-for-fixing-unopenable-windows-folders-on-double-click/"><u>Tactics for Fixing Unopenable Windows Folders on Double-Click</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-troubleshooting-excel-display-issue-in-notepad/"><u>Remedy: Troubleshooting Excel Display Issue in Notepad</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-net-requirement-issue-in-windows-apps/"><u>Tackling the .NET Requirement Issue in Windows Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/configure-ideal-window-space-for-your-apps-in-win11/"><u>Configure Ideal Window Space for Your Apps in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-workflow-efficiency-mastering-flow-launcher/"><u>Boost Workflow Efficiency: Mastering Flow Launcher</u></a></li>
<li><a href="https://windows11.techidaily.com/briskly-boost-printer-functionality/"><u>Briskly Boost Printer Functionality</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/motivational-moments-the-ultimate-list-for-insta/"><u>Motivational Moments  The Ultimate List for Insta</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-in-2024-here-are-8-best-video-animation-app-on-different-devices-android-iphone-and-ipad/"><u>Updated In 2024, Here Are 8 Best Video Animation App on Different Devices, Android, iPhone and iPad</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-7-phone-number-locators-to-track-samsung-galaxy-m14-4g-location-drfone-by-drfone-virtual-android/"><u>Top 7 Phone Number Locators To Track Samsung Galaxy M14 4G Location | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-reel-ready-content-best-insta-downloaders-explored/"><u>[New] Reel-Ready Content  Best Insta Downloaders Explored</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/in-2024-reverse-engineering-how-to-reverse-video-clips-in-final-cut-pro/"><u>In 2024, Reverse Engineering How to Reverse Video Clips in Final Cut Pro</u></a></li>
<li><a href="https://android-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-samsung-galaxy-xcover-6-pro-tactical-edition-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Samsung Galaxy XCover 6 Pro Tactical Edition Phones with/without a PC</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reasons-for-tecno-spark-10c-stuck-on-startup-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Tecno Spark 10C Stuck on Startup Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-maximizing-your-tiktok-content-with-advanced-voice-controls-via-siri-for-2024/"><u>[New] Maximizing Your TikTok Content with Advanced Voice Controls via Siri for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-detect-and-stop-mspy-from-spying-on-your-vivo-v30-lite-5g-drfone-by-drfone-virtual-android/"><u>How to Detect and Stop mSpy from Spying on Your Vivo V30 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/the-pros-and-cons-of-using-vidma-as-a-screen-grabber/"><u>The Pros & Cons of Using Vidma as a Screen Grabber</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>