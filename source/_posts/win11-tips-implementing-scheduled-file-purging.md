---
title: "Win11 Tips: Implementing Scheduled File Purging"
date: 2024-06-25T12:39:11.786Z
updated: 2024-06-26T12:39:11.786Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Win11 Tips: Implementing Scheduled File Purging"
excerpt: "This Article Describes Win11 Tips: Implementing Scheduled File Purging"
keywords: Win11 File Cleanup Guide,Weekly PC Maintenance,Windows Scheduled Purge,Disk Space Optimization,Frequent File Deletion Tips,Regular System Updates,Efficient File Management
thumbnail: https://thmb.techidaily.com/97b5d85adaa70d7cf066a732f43c0486f51d36a4ba60d02434a07b91f944e872.jpg
---

## Win11 Tips: Implementing Scheduled File Purging

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/win11s-0x8007045d-an-effective-resolution-blueprint/"><u>Win11's 0X8007045D: An Effective Resolution Blueprint</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-and-reviving-winget-a-guide-for-windows-11-users/"><u>Navigating and Reviving Winget: A Guide for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-steps-for-muting-windows-11-tabs/"><u>Essential Steps for Muting Windows 11 Tabs</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-mend-windows-network-proxy-errors/"><u>Steps to Mend Windows Network Proxy Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-internet-connection-league-of-legends-on-windows/"><u>Mastering Internet Connection: League of Legends on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-app-non-installation-microsoft-tips/"><u>Troubleshooting App Non-Installation: Microsoft Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-steps-for-accessing-windows-11s-policy-editor/"><u>Easy Steps for Accessing Windows 11'S Policy Editor</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-routes-to-examine-and-clean-up-windows-10s-past-actions/"><u>Easy Routes to Examine & Clean Up Windows 10'S Past Actions</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/innovative-pop-music-harmonies-a-2024-guidebook-to-perfecting-visual-media-soundscapes/"><u>Innovative Pop Music Harmonies A 2024 Guidebook to Perfecting Visual Media Soundscapes</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-get-your-favorite-soundcloud-tracks-in-mp3-format-a-simple-guide-for-2024/"><u>New Get Your Favorite Soundcloud Tracks in MP3 Format A Simple Guide for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-phantom-3-confrontation-illusionist-4-enters/"><u>[New] Phantom 3 Confrontation  Illusionist 4 Enters</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-live-link-lore-when-does-gear-give-way-to-grids/"><u>In 2024, Live Link Lore  When Does Gear Give Way to Grids?</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-4-ways-to-unlock-iphone-15-to-use-usb-accessories-without-passcode-drfone-by-drfone-ios/"><u>In 2024, 4 Ways to Unlock iPhone 15 to Use USB Accessories Without Passcode | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-mastering-iphone-collages-essential-handy-guide/"><u>2024 Approved  Mastering iPhone Collages  Essential Handy Guide</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/1714929139254-new-8-best-voice-recognition-software-for-windows-mac-and-online-for-2024/"><u>New 8 Best Voice Recognition Software for Windows, Mac and Online for 2024</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-mac-video-editing-software-by-avs-easy-and-powerful-for-2024/"><u>New Mac Video Editing Software by AVS Easy and Powerful for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/unleash-your-creativity-best-free-and-paid-glitch-video-editing-tools/"><u>Unleash Your Creativity Best Free and Paid Glitch Video Editing Tools</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>