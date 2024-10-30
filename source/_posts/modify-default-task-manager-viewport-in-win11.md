---
title: Modify Default Task Manager Viewport in Win11
date: 2024-10-28T16:07:47.025Z
updated: 2024-10-30T16:11:07.111Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Modify Default Task Manager Viewport in Win11
excerpt: This Article Describes Modify Default Task Manager Viewport in Win11
keywords: Win11 Task View Modification,Windows 11 User Interface Tweaks,Altering Task Manager Layout,Win11 Display Adjustments,Customizing Windows Taskbar,Change Windows Settings,Task Manager UI Enhancement
thumbnail: https://thmb.techidaily.com/5bfb2b2f01975a3eebb8a0b131dcc5bf0873594ba112a1d8a6d8b08b27b2cbba.jpg
---

## Modify Default Task Manager Viewport in Win11

 The Task Manager provides a quick overview of your system's current status and shows essential information. Its Start page displays useful details such as currently running background processes, applications, CPU, and memory utilization. If you'd like to customize its appearance, change the Start page. In this article, we’ll look at how to change the Task Manager Start page in Windows 11\.

## 1\. Use Task Manager Settings

 If you want to quickly change the Task Manager Start page, you can use its Settings tab. This option requires no modification to the registry editor or additional scripts to run.

 To change the Task Manager Start page using Task Manager settings, do the following.

1. Press **Win + R** to open the Run dialog box.
2. Type **taskmgr** and press **Enter** to launch Task Manager.
3. Once in Task Manager, click on **Settings** (the gear icon).
4. You'll see a **Default Start Page** drop-down menu at the top. This is where you can select the page to display when Task Manager opens.  
![Use Settings to Change Task Manager Start Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/use-settings-to-change-task-manager-start-page.jpg)

 The options available are the following:

1. Processes
2. Performance
3. App history
4. Startup apps
5. Users
6. Details
7. Services ​​​​

 Once you make a selection, Task Manager will remember the setting and open the page you chose from now on.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036486/19272" target="_top" id="2036486">
  <img src="//a.impactradius-go.com/display-ad/19272-2036486" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036486/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Tweak the Registry Editor

 The Registry Editor is another way to change the default Start page for Task Manager. The procedure is slightly more complex than using Task Manager Settings, but it offers more customization options. Be careful when modifying entries in the Registry Editor, as incorrect changes can cause errors or system instability. To avoid losing data, [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it.

 To change the Task Manager Start page using the Registry Editor, follow these steps.

1. [Open the Registry Editor window](https://www.makeuseof.com/windows-11-open-registry-editor/).
2. If the UAC prompt pops up, click **Yes** to grant administrative rights.
3. In the left pane, navigate to the following key.  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\TaskManager`
4. Double-click **StartUpTab** in the right pane. If there is no such entry, then right-click on the Task Manager key.
5. From the context menu, select **New > DWORD (32-bit) Value**.
6. Now name the value **StartUpTab** and double-click on it.  
![Modify Registry to Change Task Manager Start Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modify-registry-to-change-task-manager-start-page.jpg)
7. Set its **Value data** to one of the following numbers to change the default start page:  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2016143/19272" target="_top" id="2016143">
  <img src="//a.impactradius-go.com/display-ad/19272-2016143" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016143/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

`0 = Processes  

1 = Performance  

2 = App history  

3 = Startup apps  

4 = Users  

5 = Details  

6 = Services`
8. Click **OK** to save the changes and close the Registry Editor window.

 Next time you open Task Manager, it will display a page according to your preferences.

<!-- affiliate ads begin -->
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1557742/17382" target="_top" id="1557742">
  <img src="//a.impactradius-go.com/display-ad/17382-1557742" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1557742/17382" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Use a REG File

 If the registry editor isn't your thing, you can use a REG file to modify the Task Manager start page. The process does not require registry tweaking and is straightforward.

 To create a .reg file, [open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) and type the following:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\TaskManager]  
  
"StartUpTab"=dword:00000000`

 Here, the last digit reflects the type of Start page.

 For example, if you want to set **Processes** as your default start page, use **0** (**00000000**). Similarly, if you want the **Details** page to display as default, set it to **5** (**00000005**).

 The other options are:

`00000001 - Performance  
  
00000002 - App history  
  
00000003 - Startup apps  
  
00000004 - Users  
  
00000006 - Services`

 Now, click **File** and select **Save as**. In the Save as dialog box, click the Save as type drop-down menu and select **All files**. Name the file with the **.reg** extension. For example, **TaskManagerStartPage.reg**.

![Use a REG File to Change Task Manager Start Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/use-a-reg-file-to-change-task-manager-start-page.jpg)

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1001453/11832" target="_top" id="1001453">
  <img src="//a.impactradius-go.com/display-ad/11832-1001453" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1001453/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Next, select **Desktop** from the left pane and click **Save**. Once saved, double-click on this newly created REG file. This adds the required details to the Registry Editor and changes the Task Manager start page.

 If you ever want to revert the changes, delete the REG file and restart your computer.

## Changing the Task Manager Start Page on Windows

 It’s easy to customize Task Manager and change its Start page according to your preference. You can use Task Manager Settings, the Registry Editor, or a REG file to set the desired page. Once you have set the Start page, Task Manager will remember it and open that page when you launch it.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-helps.techidaily.com/new-2024-approved-warping-letters-in-photographyvideo/"><u>[New] 2024 Approved Warping Letters in Photography/Video</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-2024-approved-innovative-approaches-to-modify-user-numbers-in-tiktok/"><u>[Updated] 2024 Approved Innovative Approaches to Modify User Numbers in TikTok</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-capture-coastlines-best-surfer-cams/"><u>2024 Approved Capture Coastlines Best Surfer Cams</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-which-is-better-video-editor-for-iphone-cameo-or-filmorago/"><u>2024 Approved Which Is Better Video Editor for iPhone? Cameo or FilmoraGo?</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/a-guide-vivo-y100t-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>A Guide Vivo Y100t Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://fox-access.techidaily.com/best-unboxing-video-series-the-ultimate-2024-watchlist/"><u>Best Unboxing Video Series - The Ultimate 2024 Watchlist</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-in-solving-the-mystery-fixing-obs-studios-hidden-error/"><u>Mastery in Solving the Mystery: Fixing OBS Studio's Hidden Error</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-monitors-choosing-personalized-themes-in-win-1011/"><u>Maximizing Monitors: Choosing Personalized Themes in Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-disconnected-spotify-sessions-in-w10w11/"><u>Mending Disconnected Spotify Sessions in W10/W11</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-top-9-online-movie-makers-to-make-movie-online-for-free/"><u>New 2024 Approved Top 9 Online Movie Makers to Make Movie Online for Free</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-file-naming-powertoys-batch-renamer-tool/"><u>Quick File Naming: PowerToys Batch Renamer Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/stealthy-shutdown-auto-restart-guide-for-windows-pcs/"><u>Stealthy Shutdown: Auto-Restart Guide for Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-your-workspace-integrating-directories-into-taskbar-menu/"><u>Streamlining Your Workspace: Integrating Directories Into Taskbar Menu</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/transform-your-gaming-experience-with-the-alienware-curved-34-inch-oled-available-for-749-at-best-buy/"><u>Transform Your Gaming Experience with the Alienware Curved 34 Inch OLED - Available for $749 at Best Buy</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-top-rated-free-video-editors-for-mp4-files/"><u>Updated In 2024, Top-Rated Free Video Editors for MP4 Files</u></a></li>
<li><a href="https://windows11.techidaily.com/virtual-vigilance-effective-methods-to-secure-your-os/"><u>Virtual Vigilance: Effective Methods to Secure Your OS</u></a></li>
</ul></div>

