---
title: "Tackling File Overload: Utilizing Windows' Automatic Cleanup"
date: 2024-10-01T03:37:03.443Z
updated: 2024-10-06T17:09:57.911Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Tackling File Overload: Utilizing Windows' Automatic Cleanup"
excerpt: "This Article Describes Tackling File Overload: Utilizing Windows' Automatic Cleanup"
keywords: File Overload Cleanup,Windows Auto-Cleanup,Disk Space Management,Removing Unnecessary Files,Optimize System Performance,Automatic File Deletion,Manage Storage Efficiently
thumbnail: https://thmb.techidaily.com/fed19fb5539928ceb1f098e4df501aac24d80c5bb6000047d745afbd7491bdcb.jpg
---

## Tackling File Overload: Utilizing Windows' Automatic Cleanup

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
<a href="https://laganoo.pxf.io/c/5597632/1528688/16446" target="_top" id="1528688">
  <img src="//a.impactradius-go.com/display-ad/16446-1528688" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528688/16446" style="position:absolute;visibility:hidden;" border="0" />
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
10. Under the **Settings** section, set up the timings of the tasks you'd like to run. Finally, click on **OK**.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139114/17108" target="_top" id="2139114">
  <img src="//a.impactradius-go.com/display-ad/17108-2139114" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139114/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now, head to the **Actions** tab and click on the **New** button. From the **Actions** drop-down menu, select the **Start a program** option.

 In the Program/script box, type in the following command:

`ForFiles`

![new action tab on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-action-tab-on-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925473/19272" target="_top" id="1925473">
  <img src="//a.impactradius-go.com/display-ad/19272-1925473" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925473/19272" style="position:absolute;visibility:hidden;" border="0" />
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

 That's it—finalize the changes by clicking **OK** once again, and you will be done in no time. From here forward, your files will be automatically deleted within the specified time. Of course, if you later change your mind you can always reverse this setting by simply deleting the new folder your created in first step (which in our case, will be **New Folder 1**).

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1868499/19272" target="_top" id="1868499">
  <img src="//a.impactradius-go.com/display-ad/19272-1868499" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868499/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-streamlining-role-assignment-in-discord-channels/"><u>[New] 2024 Approved Streamlining Role Assignment in Discord Channels</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/inding-the-highlighted-online-discourse-for-2024/"><u>[New] Finding the Highlighted Online Discourse for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-sleek-line-up-best-7-fps-arenas/"><u>[Updated] 2024 Approved Sleek Line-Up Best 7 FPS Arenas</u></a></li>
<li><a href="https://games-able.techidaily.com/a-comprehensive-guide-to-selecting-superior-discords/"><u>A Comprehensive Guide to Selecting Superior Discords</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-error-c0000022-a-path-to-windows-stability/"><u>Demystifying Error C0000022: A Path to Windows Stability</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-for-instantly-generating-numerous-subfolders-on-modern-windows-systems/"><u>Expert Tips for Instantly Generating Numerous Subfolders on Modern Windows Systems</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-remove-screen-lock-pin-on-xiaomi-like-a-pro-5-easy-ways-by-drfone-android/"><u>In 2024, How To Remove Screen Lock PIN On Xiaomi Like A Pro 5 Easy Ways</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-text-messages-from-vivo-y28-5g-to-new-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Text Messages from Vivo Y28 5G to New Phone | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-obs-streaming-windows-and-mac-guide/"><u>In 2024, OBS Streaming [Windows and Mac Guide]</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-system-restore-your-key-to-past-windows-configurations/"><u>Leveraging System Restore: Your Key to Past Windows Configurations</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-files-with-powertoys-a-comprehensive-tutorial/"><u>Optimizing Files with PowerToys: A Comprehensive Tutorial</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-your-workflow-embracing-the-shift-in-ram-standards/"><u>Optimizing Your Workflow: Embracing the Shift in RAM Standards</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-prevent-windows-dwarf-fortress-crashes/"><u>Strategies to Prevent Windows-Dwarf Fortress Crashes</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-for-fixing-no-available-on-nvidia-display-error/"><u>Tactics for Fixing 'No Available' On Nvidia Display Error</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-over-windows-11-22h2-fix-strategies/"><u>Winning Over Windows 11: 22H2 Fix Strategies</u></a></li>
</ul></div>

