---
title: "Secure and Slim Filesystem: Setting Up Auto Delete in Win11"
date: 2024-11-18T17:33:49.985Z
updated: 2024-11-24T17:15:55.257Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Secure and Slim Filesystem: Setting Up Auto Delete in Win11"
excerpt: "This Article Describes Secure and Slim Filesystem: Setting Up Auto Delete in Win11"
keywords: Win11 Auto-Delete,Slim Windows File,Secure WinFS Setup,Auto-Deletion Techniques,Slim File System,Secure Filesystem Win11,Deleting Old Files
thumbnail: https://thmb.techidaily.com/95c7607cc85834758f594e36f86b8274633568f32ba37267dd79e6e802f121e2.png
---

## Secure and Slim Filesystem: Setting Up Auto Delete in Win11

 For many, a cluttered desktop and downloads folder is just a way of life—no matter how hard you try, they somehow always ends up disorganized. Need to do a bit of digital spring-cleaning? Fortunately, there are lots of ways you can keep your Windows 10 computer decluttered.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.

## 1\. Auto-Delete Old Files or Folders Using Storage Settings

 The Settings menu lets you do and manage a lot of stuff on your Windows computer. From updates to tweaking the Windows appearance—you can do almost everything. It's no surprise then that you can also use it for setting up an auto-deletion setting on your Windows. Here's how:

![storage settings on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/storage-settings-on-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eu4vwlZcMvM?si=4vEczfVU4BUUFP-t&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Go to **Settings > System > Storage**.
2. Toggle on the **Storage Sense** feature.
3. Then, click **Configure Storage Sense or run it now**.
4. Under **Temporary Files**, set up your desired time frames fore deleting files in the recycle bin and files in your Downloads folder.  
![storage sense in windows settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/storage-sense-in-windows-settings.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/d-COuhPT5mk?si=wLZU6jkkAdJuAn6h&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Not all files in the Downloads folder will be deleted after the set time; just those that haven't been opened. This means if you download a file and want to open it later, it will still be deleted after the set time. If you turn this setting on, you should move anything out of the Downloads folder that you intend to keep.

 If you want, you can always turn off the setting by simply disabling the **Storage Sense** button later on.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c17xsnbinCQ?si=xHKslFgC3QbxY4qW&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Deleted Old Files or Folders With the Command Prompt

 Like most things on Windows, you can use the Command Prompt here as well. A replacement for the easy pin-and-point graphical user interface, the Command Prompt works with simple text-based commands to help you perform different admin functions and fix various troubleshooting issues on Windows.

 Here's how you can use it to fix your storage issues via the _ForFiles_ command on Windows:

1. Head to the **Start menu** search bar, type in 'cmd', and run the CMD as an administrator.
2. Now, to delete the files that you haven't modified in 30 days, type in the following command and hit **Enter**:  
`ForFiles /p "C:\path\to\folder"/s /d -30 /c "cmd /c del /q @file"`

 The "C:\\path\\to\\folder" and /d -30 here refer to the folder path from where you want to delete files and the specific time for which you'd like to delete your file. Replace them with the settings that suit you.

![command prompt on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/command-prompt-on-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/On0Jw2oMZf0?si=Pm-FJoEt8XWmtMbr&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Your files will be removed as quickly as soon as you hit the above commands.

## 3\. Use Task Scheduler on Windows

 Task Scheduler is a simple Windows tool that lets you easily automate your repetitive Windows tasks. Just set up the task, and the app will handle whatever you have asked it to do. When it comes to auto-deleting your files or folders, the _ForFiles_ command is what you will need to help you delete your older files or folders.

 Here's how you can automate the deletion:

1. Head to the **Start menu** search bar, type in 'task scheduler', and select the best match.
2. Right-click on **Task Scheduler Library** and select **New Folder**.
3. Put in any name and click on **OK**.
4. Right-click on the recently created folder and select the **Create Task** option.  
![task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/task-scheduler.jpg)
5. In the **Name** box, enter a name for the task.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/AQn0MYjIfyI?si=rIdjT-qMRpjpJXXa&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Now, in the **General** tab, under the **Security options** section, select the **Run whether the user is logged on or not** option.
7. Make sure the **Do not store password** checkbox is unselected.
8. Click on the **Triggers** tab and select the **New** button.
9. Select **On a schedule** option using the **Begin the task** setting.  
![new trigger section on task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-trigger-section-on-windows.jpg)
10. Under the **Settings** section, set up the timings of the tasks you'd like to run. Finally, click on **OK**.

 Now, head to the **Actions** tab and click on the **New** button. From the **Actions** drop-down menu, select the **Start a program** option.

 In the Program/script box, type in the following command:

`ForFiles`

![new action tab on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-action-tab-on-windows.jpg)

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
<li><a href="https://facebook-record-videos.techidaily.com/new-asmr-app-selection-guide-for-phones-for-2024/"><u>[New] ASMR App Selection Guide for Phones for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-easyrecorder-straightforward-windows-10-tool-for-2024/"><u>[New] EasyRecorder - Straightforward Windows 10 Tool for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/solved-errconnectiontimedout-in-chrome/"><u>[SOLVED] ERR_CONNECTION_TIMED_OUT in Chrome</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-from-tweeting-short-videos-to-interactive-shareable-customized-gifs/"><u>[Updated] In 2024, From Tweeting Short Videos to Interactive, Shareable Customized GIFS</u></a></li>
<li><a href="https://tech-hub.techidaily.com/effortless-creativity-with-top-ai-enhanced-pdf-tools/"><u>Effortless Creativity with Top AI-Enhanced PDF Tools</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/how-to-intercept-text-messages-on-apple-iphone-8-drfone-by-drfone-virtual-ios/"><u>How to Intercept Text Messages on Apple iPhone 8 | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-sharefake-gps-on-uber-for-oppo-reno-10-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to share/fake gps on Uber for Oppo Reno 10 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-will-ispoofer-update-on-apple-iphone-xs-max-drfone-by-drfone-virtual-ios/"><u>In 2024, Will iSpoofer update On Apple iPhone XS Max | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/masterclass-combating-the-winscomrssvc-error-in-windows/"><u>Masterclass: Combating the WinscomrsSvc Error in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-portable-internet-access-via-windows-11/"><u>Mastering the Art of Portable Internet Access via Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-disk-space-clear-temporary-windows-files-now/"><u>Optimize Disk Space: Clear Temporary Windows Files Now</u></a></li>
<li><a href="https://games-able.techidaily.com/overclocked-obsession-a-cautionary-tale/"><u>Overclocked Obsession: A Cautionary Tale</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-out-of-space-on-windows/"><u>Overcoming Out Of Space On Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/reestablishing-functionality-for-frozen-spotify-app/"><u>Reestablishing Functionality for Frozen Spotify App</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlined-system-repairing-in-windows-easy-hotkeys-for-troubleshooting/"><u>Streamlined System Repairing in Windows: Easy Hotkeys for Troubleshooting</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-fixers-handbook-for-recurring-rainmeter-glitches/"><u>The Ultimate Fixer's Handbook for Recurring Rainmeter Glitches</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-ultimate-playbook-a-guide-to-efficiently-posting-srt-files-online/"><u>The Ultimate Playbook A Guide to Efficiently Posting SRT Files Online</u></a></li>
<li><a href="https://windows11.techidaily.com/top-8-video-edits-software-the-ultimate-guide-for-win11-users/"><u>Top 8 Video Edits Software: The Ultimate Guide for Win11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-core-of-computer-configurations/"><u>Unlocking the Core of Computer Configurations</u></a></li>
</ul></div>

