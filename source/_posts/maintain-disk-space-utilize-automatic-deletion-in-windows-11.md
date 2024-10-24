---
title: "Maintain Disk Space: Utilize Automatic Deletion in Windows 11"
date: 2024-10-23T17:04:07.377Z
updated: 2024-10-24T21:04:49.876Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Maintain Disk Space: Utilize Automatic Deletion in Windows 11"
excerpt: "This Article Describes Maintain Disk Space: Utilize Automatic Deletion in Windows 11"
keywords: Save Disk Space,Delete Auto,Windows 11 Clean,Storage Management,Automatic Deletion,Free Up Space,Disk Optimize
thumbnail: https://thmb.techidaily.com/0d3d204f3859dff7eef251abf3745730eecca41037a408c561029879668d653a.jpg
---

## Maintain Disk Space: Utilize Automatic Deletion in Windows 11

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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136619/26400" target="_top" id="2136619">
  <img src="//a.impactradius-go.com/display-ad/26400-2136619" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136619/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1424529">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424529.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424529">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424529.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424529%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424529/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Now, in the **General** tab, under the **Security options** section, select the **Run whether the user is logged on or not** option.
7. Make sure the **Do not store password** checkbox is unselected.
8. Click on the **Triggers** tab and select the **New** button.
9. Select **On a schedule** option using the **Begin the task** setting.  
![new trigger section on task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-trigger-section-on-windows.jpg)
10. Under the **Settings** section, set up the timings of the tasks you'd like to run. Finally, click on **OK**.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2027167/19272" target="_top" id="2027167">
  <img src="//a.impactradius-go.com/display-ad/19272-2027167" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2027167/19272" style="position:absolute;visibility:hidden;" border="0" />
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

 That's it—finalize the changes by clicking **OK** once again, and you will be done in no time. From here forward, your files will be automatically deleted within the specified time. Of course, if you later change your mind you can always reverse this setting by simply deleting the new folder your created in first step (which in our case, will be **New Folder 1**).

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130528/26400" target="_top" id="2130528">
  <img src="//a.impactradius-go.com/display-ad/26400-2130528" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130528/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-hovers.techidaily.com/new-whimsical-video-downloader-score-for-2024/"><u>[New] Whimsical Video Downloader Score for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-capture-and-conquer-instagram-photos/"><u>[Updated] Capture and Conquer Instagram Photos</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-explore-the-top-10-fastest-growing-youtube-platforms-to-motivate-you/"><u>[Updated] Explore the Top 10 Fastest Growing YouTube Platforms to Motivate You</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-retro-to-modern-radeon-transition/"><u>2024 Approved Retro to Modern Radeon Transition</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/a-comprehensive-guide-to-discovering-dazzling-and-downloadable-images-on-pexels-for-2024/"><u>A Comprehensive Guide to Discovering Dazzling and Downloadable Images on Pexels for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/best-3-software-to-transfer-files-tofrom-your-oppo-a78-5g-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Best 3 Software to Transfer Files to/from Your Oppo A78 5G via a USB Cable | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/exclusive-insight-the-ultimate-roundup-of-windows-video-tools/"><u>Exclusive Insight: The Ultimate Roundup of Windows Video Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/gamers-guide-cooling-down-the-heat-of-laptop-games/"><u>Gamer's Guide: Cooling Down the Heat of Laptop Games</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-apply-these-techniques-to-improve-how-to-detect-fake-gps-location-on-motorola-moto-g14-drfone-by-drfone-virtual-android/"><u>In 2024, Apply These Techniques to Improve How to Detect Fake GPS Location On Motorola Moto G14 | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-top-online-sources-for-high-quality-vector-illustrations/"><u>In 2024, Top Online Sources for High-Quality Vector Illustrations</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-repair-of-file-corruption-error-code-0x80070570-in-windows-11/"><u>Mastering Repair of File Corruption (Error Code 0X80070570) in Windows 11</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/online-partnerships-crafting-brand-joint-ventures-on-youtube-for-2024/"><u>Online Partnerships Crafting Brand Joint Ventures on YouTube for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-to-unblock-your-windows-pin-entry/"><u>Quick Fixes to Unblock Your Windows Pin Entry</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-the-process-of-getting-adobe-reader-on-ms-store/"><u>Simplifying the Process of Getting Adobe Reader on MS Store</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-process-for-distro-and-catroot2-fixes-in-ws11/"><u>The Ultimate Process for Distro & Catroot2 Fixes in WS11</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-launching-csgo-in-windows-11/"><u>Tips for Launching CS:GO in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-routes-for-steam-connection-failures/"><u>Troubleshooting Routes for Steam Connection Failures</u></a></li>
<li><a href="https://tech-haven.techidaily.com/understanding-the-contrast-what-sets-natural-language-processing-apart-from-machine-learning/"><u>Understanding the Contrast: What Sets Natural Language Processing Apart From Machine Learning?</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-proxies-a-practical-guide-to-enhanced-privacy/"><u>Win 11 Proxies: A Practical Guide to Enhanced Privacy</u></a></li>
</ul></div>

