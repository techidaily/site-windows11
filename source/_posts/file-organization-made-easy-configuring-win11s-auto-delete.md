---
title: "File Organization Made Easy: Configuring Win11's Auto Delete"
date: 2024-10-08T01:57:40.896Z
updated: 2024-10-13T03:22:08.484Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes File Organization Made Easy: Configuring Win11's Auto Delete"
excerpt: "This Article Describes File Organization Made Easy: Configuring Win11's Auto Delete"
keywords: Win11 Auto Deletion,File Management Win11,Easy Win11 Sync,Organize Files Win11,Configuring Auto-Delete,Efficient File Ordering Win11,Digital Cleanup in Windows 11
thumbnail: https://thmb.techidaily.com/7893aa47861abae86c2201349f48204a58f66be5a4db0cfc4bb799b623cb07e4.jpg
---

## File Organization Made Easy: Configuring Win11's Auto Delete

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
<a href="https://sentrypc.7eer.net/c/5597632/398449/3022" target="_top" id="398449">
  <img src="//a.impactradius-go.com/display-ad/3022-398449" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398449/3022" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://wigfever.sjv.io/c/5597632/2014859/22899" target="_top" id="2014859">
  <img src="//a.impactradius-go.com/display-ad/22899-2014859" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014859/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Now, in the **General** tab, under the **Security options** section, select the **Run whether the user is logged on or not** option.
7. Make sure the **Do not store password** checkbox is unselected.
8. Click on the **Triggers** tab and select the **New** button.
9. Select **On a schedule** option using the **Begin the task** setting.  
![new trigger section on task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-trigger-section-on-windows.jpg)
10. Under the **Settings** section, set up the timings of the tasks you'd like to run. Finally, click on **OK**.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139108/17108" target="_top" id="2139108">
  <img src="//a.impactradius-go.com/display-ad/17108-2139108" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139108/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043661/7443" target="_top" id="2043661">
  <img src="//a.impactradius-go.com/display-ad/7443-2043661" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043661/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-essential-tips-sharing-your-apple-devices-screen-with-youtube/"><u>[New] 2024 Approved Essential Tips Sharing Your Apple Devices Screen with YouTube</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-in-2024-strategies-for-effortless-insertion-of-videos-into-youtube-compilations/"><u>[New] In 2024, Strategies for Effortless Insertion of Videos Into YouTube Compilations</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-safaris-picture-in-picture-feature-usage-guide/"><u>[New] Safari's Picture-in-Picture Feature Usage Guide</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-from-raw-files-to-artwork-beginners-guide-to-lunapic/"><u>[Updated] From Raw Files to Artwork Beginner’s Guide to LunaPic</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-non-gaming-screen-capture-apps-worth-your-time-for-2024/"><u>[Updated] Non-Gaming Screen Capture Apps Worth Your Time for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-exploring-the-unexpected-sideway-effects-in-ig-videos/"><u>2024 Approved Exploring the Unexpected Sideway Effects in IG Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-causes-of-pc-disk-issues/"><u>Addressing Causes of PC Disk Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-user-interface-integrating-emoji-15-into-win11/"><u>Boosting User Interface: Integrating Emoji 15 Into Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/hidden-sd-card-regain-access-with-troubleshooting-guide/"><u>Hidden SD Card: Regain Access with Troubleshooting Guide</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/high-fidelity-avi-player-for-portable-and-stationary-use-for-2024/"><u>High-Fidelity AVI Player for Portable & Stationary Use for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-utilize-windows-for-handwritten-input/"><u>How to Utilize Windows for Handwritten Input</u></a></li>
<li><a href="https://facebook.techidaily.com/insta-collage-creation-tips-for-engaging-online-portfolits/"><u>Insta-Collage Creation: Tips for Engaging Online Portfolits</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/master-language-barriers-with-these-ebest-offline-translator-programs/"><u>Master Language Barriers with These Ebest Offline Translator Programs</u></a></li>
<li><a href="https://windows11.techidaily.com/merge-your-world-connecting-android-and-windows-11-tablets/"><u>Merge Your World: Connecting Android and Windows 11 Tablets</u></a></li>
<li><a href="https://windows11.techidaily.com/overhauling-write-operations-failure-fixes-on-windows/"><u>Overhauling Write Operations Failure Fixes on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-manual-reverting-windows-to-a-previous-state/"><u>Step-by-Step Manual: Reverting Windows to a Previous State</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/still-using-pattern-locks-with-nokia-xr21-tips-tricks-and-helpful-advice-by-drfone-android/"><u>Still Using Pattern Locks with Nokia XR21? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-correcting-incompatible-software-with-windows-operations/"><u>Strategies for Correcting Incompatible Software with Windows Operations</u></a></li>
<li><a href="https://windows11.techidaily.com/the-uncharted-territory-windows-11-and-the-future-of-ai/"><u>The Uncharted Territory: Windows 11 and the Future of AI</u></a></li>
</ul></div>

