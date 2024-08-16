---
title: "Declutter Your Disk Space: Auto-Deletion Settings for Windows 11"
date: 2024-08-15T15:28:44.937Z
updated: 2024-08-16T15:28:44.937Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Declutter Your Disk Space: Auto-Deletion Settings for Windows 11"
excerpt: "This Article Describes Declutter Your Disk Space: Auto-Deletion Settings for Windows 11"
keywords: WIN11 FreeSpace,DeletesAutoSettings,DiskCleanupWin11,AutoDeletionControl,WindowsFreeUp,SpaceOptimizeWin11,AutoDeleteOptions
thumbnail: https://thmb.techidaily.com/bb00ebc3d89d1362ca9b186657d254b37c10a245e721f7dc9d791e4530e6a65b.jpeg
---

## Declutter Your Disk Space: Auto-Deletion Settings for Windows 11

 For many, a cluttered desktop and downloads folder is just a way of life—no matter how hard you try, they somehow always ends up disorganized. Need to do a bit of digital spring-cleaning? Fortunately, there are lots of ways you can keep your Windows 10 computer decluttered.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.

## 1\. Auto-Delete Old Files or Folders Using Storage Settings

 The Settings menu lets you do and manage a lot of stuff on your Windows computer. From updates to tweaking the Windows appearance—you can do almost everything. It's no surprise then that you can also use it for setting up an auto-deletion setting on your Windows. Here's how:

![storage settings on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/storage-settings-on-windows.jpg)

1. Go to **Settings > System > Storage**.
2. Toggle on the **Storage Sense** feature.
3. Then, click **Configure Storage Sense or run it now**.
4. Under **Temporary Files**, set up your desired time frames fore deleting files in the recycle bin and files in your Downloads folder.  
![storage sense in windows settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/storage-sense-in-windows-settings.jpg)

 Not all files in the Downloads folder will be deleted after the set time; just those that haven't been opened. This means if you download a file and want to open it later, it will still be deleted after the set time. If you turn this setting on, you should move anything out of the Downloads folder that you intend to keep.

 If you want, you can always turn off the setting by simply disabling the **Storage Sense** button later on.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
## 2\. Deleted Old Files or Folders With the Command Prompt

 Like most things on Windows, you can use the Command Prompt here as well. A replacement for the easy pin-and-point graphical user interface, the Command Prompt works with simple text-based commands to help you perform different admin functions and fix various troubleshooting issues on Windows.

 Here's how you can use it to fix your storage issues via the _ForFiles_ command on Windows:

1. Head to the **Start menu** search bar, type in 'cmd', and run the CMD as an administrator.
2. Now, to delete the files that you haven't modified in 30 days, type in the following command and hit **Enter**:  
`ForFiles /p "C:\path\to\folder"/s /d -30 /c "cmd /c del /q @file"`

 The "C:\\path\\to\\folder" and /d -30 here refer to the folder path from where you want to delete files and the specific time for which you'd like to delete your file. Replace them with the settings that suit you.

![command prompt on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/command-prompt-on-windows.jpg)

 Your files will be removed as quickly as soon as you hit the above commands.

<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Use Task Scheduler on Windows

 Task Scheduler is a simple Windows tool that lets you easily automate your repetitive Windows tasks. Just set up the task, and the app will handle whatever you have asked it to do. When it comes to auto-deleting your files or folders, the _ForFiles_ command is what you will need to help you delete your older files or folders.

 Here's how you can automate the deletion:

1. Head to the **Start menu** search bar, type in 'task scheduler', and select the best match.
2. Right-click on **Task Scheduler Library** and select **New Folder**.
3. Put in any name and click on **OK**.
4. Right-click on the recently created folder and select the **Create Task** option.  
![task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/task-scheduler.jpg)
5. In the **Name** box, enter a name for the task.
6. Now, in the **General** tab, under the **Security options** section, select the **Run whether the user is logged on or not** option.
7. Make sure the **Do not store password** checkbox is unselected.
8. Click on the **Triggers** tab and select the **New** button.
9. Select **On a schedule** option using the **Begin the task** setting.  
![new trigger section on task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-trigger-section-on-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
10. Under the **Settings** section, set up the timings of the tasks you'd like to run. Finally, click on **OK**.

 Now, head to the **Actions** tab and click on the **New** button. From the **Actions** drop-down menu, select the **Start a program** option.

 In the Program/script box, type in the following command:

`ForFiles`

![new action tab on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-action-tab-on-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->

 Similarly, in the **Add arguments** box, type in the following command:

`/p "C:\path\to\folder"/s /d -30 /c "cmd /c del /q @file"`

 In the above command, tweak the _"C:\\path\\to\\folder_" to the path of the folder where your files are and replace "_/d -30_" with actual number you'd like pick. So, your command will become something like this:

`/p "%userprofile%\Users\[Your Username]\Downloads" /s /d -30 /c "cmd /c del /q @file"`

 Click on **OK**. Finally, from the **Settings** tab, check the following checkboxes and then click on **OK**:

* Allow task to be run on demand.
* Run the task as soon as possible after a scheduled start is missed.
* If the task fails, restart every.

![new action setting on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-action-setting-on-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 That's it—finalize the changes by clicking **OK** once again, and you will be done in no time. From here forward, your files will be automatically deleted within the specified time. Of course, if you later change your mind you can always reverse this setting by simply deleting the new folder your created in first step (which in our case, will be **New Folder 1**).

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Auto-Deleting Old Files or Folders on a Windows Computer

 Keeping unnecessary files on your computer is seldom useful. They eat up memory space, hamper your PC's performance, and clog the file organization. Setting up auto-delete instructions, with whichever method you prefer, lets you rid your PC of this extra baggage.

 However, we'd add that auto-removing files or folders from your PC is just one part of cleaning up your Windows. There are many other important hacks such as removing unused apps, terminating pointless background processes, and tweaking settings to whatever is most relevant to your situation. So, make sure you follow all the best principles for running your Windows as smoothly as possible.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-little-wheels-whirlwind-games/"><u>[New] 2024 Approved  Little Wheels Whirlwind Games</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-tailored-gaming-experience-without-cross-play-in-apex/"><u>[New] In 2024, Tailored Gaming Experience without Cross-Play in Apex</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-top-5-non-bandicamp-capture-tools-for-mac-users/"><u>[New] In 2024, Top 5 Non-Bandicamp Capture Tools for Mac Users</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-activating-grid-view-in-google-meet-webinars-a-step-by-step-guide/"><u>[Updated] 2024 Approved  Activating Grid View in Google Meet Webinars  A Step-by-Step Guide</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-faces-of-technology-analyzing-face-detection-in-phones/"><u>2024 Approved  Faces of Technology  Analyzing Face Detection in Phones</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-unlocking-the-potential-of-harmonics-in-your-facebook-videos/"><u>2024 Approved  Unlocking the Potential of Harmonics in Your Facebook Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/an-insight-into-windows-audio-channel-separation/"><u>An Insight Into Windows' Audio Channel Separation</u></a></li>
<li><a href="https://windows11.techidaily.com/automated-file-handling-via-task-scheduler/"><u>Automated File Handling via Task Scheduler</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-operation-elevation-woes-on-windows-11-and-11/"><u>Breaking Down Operation Elevation Woes on Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-failed-application-launches-windows-11s-error-0xc000003e-explained/"><u>Correcting Failed Application Launches: Windows 11'S Error 0XC000003E Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-windows-11-editions-home-or-pro-advantage/"><u>Deciphering Windows 11 Editions: Home or Pro Advantage</u></a></li>
<li><a href="https://windows11.techidaily.com/fuse-windows-and-tdarr-for-unrivaled-scalable-video-conversion-efficiency/"><u>Fuse Windows and Tdarr for Unrivaled, Scalable Video Conversion Efficiency</u></a></li>
<li><a href="https://windows11.techidaily.com/illustrating-maximum-and-minimum-cpu-stages-on-windows/"><u>Illustrating Maximum & Minimum CPU Stages on Windows</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-building-your-brand-on-instagram-the-top-9-actions-of-industry-stars/"><u>In 2024, Building Your Brand on Instagram  The Top 9 Actions of Industry Stars</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-iphone-xr-apples-new-iphone-drfone-by-drfone-ios/"><u>In 2024, How to Unlock iPhone XR, Apples New iPhone | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/key-applications-that-bridge-the-mac-and-windows-divide/"><u>Key Applications that Bridge the Mac and Windows Divide</u></a></li>
<li><a href="https://windows11.techidaily.com/master-key-hunting-for-windows-1110-enthusiasts/"><u>Master Key Hunting for Windows 11/10 Enthusiasts</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/mastering-youtube-live-imagery-a-comprehensive-overview/"><u>Mastering YouTube Live Imagery  A Comprehensive Overview</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-storage-effortlessly-quick-pathways-into-windows-disk-manager/"><u>Optimize Storage Effortlessly: Quick Pathways Into Windows Disk Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-visual-quality-dpi-settings-guide-for-windows-11/"><u>Optimize Visual Quality: DPI Settings Guide for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-directx-update-issues-on-windows/"><u>Overcoming DirectX Update Issues on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/reinforce-internet-ties-for-your-windows-devices-amid-sluggishness/"><u>Reinforce Internet Ties for Your Windows Devices Amid Sluggishness</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-default-windows-preferences-post-restart/"><u>Reviving Default Windows Preferences Post-Restart</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/revolutionizing-photos-through-automated-hdr-techniques/"><u>Revolutionizing Photos Through Automated HDR Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/say-goodbye-to-lag-how-to-fix-warhammer-40k-delays-on-your-pc/"><u>Say Goodbye to Lag: How to Fix Warhammer 40K Delays on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-app-installations-in-windows-11-using-winstall/"><u>Simplifying App Installations in Windows 11 Using Winstall</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/step-by-step-method-to-verify-and-update-your-tiktok-age/"><u>Step-by-Step Method to Verify and Update Your TikTok Age</u></a></li>
<li><a href="https://windows11.techidaily.com/swiftly-overcoming-windows-access-denied-blunders/"><u>Swiftly Overcoming Windows Access Denied Blunders</u></a></li>
<li><a href="https://windows11.techidaily.com/the-insiders-edge-building-snaps-with-powertoys/"><u>The Insider's Edge: Building Snaps with PowerToys</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-eliminating-enter-usernamepassword-alerts-in-windows/"><u>Troubleshooting: Eliminating 'Enter Username/Password' Alerts in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unseen-windows-firewall-protection-sectors-demystified/"><u>Unseen Windows Firewall Protection Sectors Demystified</u></a></li>
</ul></div>
