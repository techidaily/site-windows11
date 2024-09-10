---
title: "Tackling File Overload: Utilizing Windows' Automatic Cleanup"
date: 2024-09-09T11:59:41.740Z
updated: 2024-09-10T11:59:41.740Z
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135409/19272" target="_top" id="2135409">
  <img src="//a.impactradius-go.com/display-ad/19272-2135409" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135409/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136623/26400" target="_top" id="2136623">
  <img src="//a.impactradius-go.com/display-ad/26400-2136623" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136623/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137218/26400" target="_top" id="2137218">
  <img src="//a.impactradius-go.com/display-ad/26400-2137218" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137218/26400" style="position:absolute;visibility:hidden;" border="0" />
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
6. Now, in the **General** tab, under the **Security options** section, select the **Run whether the user is logged on or not** option.
7. Make sure the **Do not store password** checkbox is unselected.
8. Click on the **Triggers** tab and select the **New** button.
9. Select **On a schedule** option using the **Begin the task** setting.  
![new trigger section on task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-trigger-section-on-windows.jpg)
10. Under the **Settings** section, set up the timings of the tasks you'd like to run. Finally, click on **OK**.
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134496/18498" target="_top" id="2134496">
  <img src="//a.impactradius-go.com/display-ad/18498-2134496" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134496/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now, head to the **Actions** tab and click on the **New** button. From the **Actions** drop-down menu, select the **Start a program** option.

 In the Program/script box, type in the following command:

`ForFiles`

![new action tab on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-action-tab-on-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135350/19272" target="_top" id="2135350">
  <img src="//a.impactradius-go.com/display-ad/19272-2135350" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135350/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2118322/7443" target="_top" id="2118322">
  <img src="//a.impactradius-go.com/display-ad/7443-2118322" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118322/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 That's it—finalize the changes by clicking **OK** once again, and you will be done in no time. From here forward, your files will be automatically deleted within the specified time. Of course, if you later change your mind you can always reverse this setting by simply deleting the new folder your created in first step (which in our case, will be **New Folder 1**).

## Auto-Deleting Old Files or Folders on a Windows Computer

 Keeping unnecessary files on your computer is seldom useful. They eat up memory space, hamper your PC's performance, and clog the file organization. Setting up auto-delete instructions, with whichever method you prefer, lets you rid your PC of this extra baggage.

 However, we'd add that auto-removing files or folders from your PC is just one part of cleaning up your Windows. There are many other important hacks such as removing unused apps, terminating pointless background processes, and tweaking settings to whatever is most relevant to your situation. So, make sure you follow all the best principles for running your Windows as smoothly as possible.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-clips.techidaily.com/new-from-novice-to-pro-your-roadmap-to-crafting-engaging-fb-stories/"><u>[New] From Novice to Pro Your Roadmap to Crafting Engaging FB Stories</u></a></li>
<li><a href="https://youtube-data.techidaily.com/n-2024-unveiling-the-top-10-youtube-makeup-maestros-to-follow/"><u>[New] In 2024, Unveiling the Top 10 YouTube Makeup Maestros to Follow</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-step-by-step-strategies-downloading-audio-on-iphones/"><u>[New] Step-by-Step Strategies Downloading Audio on iPhones</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-unlock-the-power-of-emojis-for-yt-feedback-for-2024/"><u>[Updated] Unlock the Power of Emojis for YT Feedback for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-guide-to-writing-enthralling-videography-content/"><u>2024 Approved Guide to Writing Enthralling Videography Content</u></a></li>
<li><a href="https://android-location-track.techidaily.com/9-best-phone-monitoring-apps-for-motorola-edge-2023-drfone-by-drfone-virtual-android/"><u>9 Best Phone Monitoring Apps for Motorola Edge 2023 | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/a-step-by-step-guide-to-configuring-parental-filters-on-discord/"><u>A Step-by-Step Guide to Configuring Parental Filters on Discord</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-utorrent-non-installation-on-pcs-running-windows-os/"><u>Fixing uTorrent Non-Installation on PCs Running Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-merge-folders-and-files-in-windows-11-and-11/"><u>How to Merge Folders and Files in Windows 11 and 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-merge-windows-id-with-microsoft-profile/"><u>How to Merge Windows ID with Microsoft Profile</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-modify-microsoft-admin-for-windows-11-networks/"><u>How to Modify Microsoft Admin for Windows 11 Networks</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-telegrams-wonders-for-marketers-beginning-their-journey/"><u>In 2024, Telegram’s Wonders for Marketers Beginning Their Journey</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-wondering-the-best-alternative-to-hola-on-vivo-x100-pro-here-is-the-answer-drfone-by-drfone-virtual-android/"><u>In 2024, Wondering the Best Alternative to Hola On Vivo X100 Pro? Here Is the Answer | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-fast-startup-in-windows-11-installation/"><u>Mastering Fast Startup in Windows 11 Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-mouse-gestures-on-windows-11s-microsoft-edge/"><u>Mastering Mouse Gestures on Windows 11'S Microsoft Edge</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11s-character-display-tool/"><u>Mastering Windows 11'S Character Display Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-your-network-the-windows-iscsi-initiator-explained/"><u>Mastering Your Network: The Windows iSCSI Initiator Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-back-to-default-windows-preferences/"><u>Navigating Back to Default Windows Preferences</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/obs-essentials-optimizing-your-skype-call-recording-quality/"><u>OBS Essentials Optimizing Your Skype Call Recording Quality</u></a></li>
<li><a href="https://windows11.techidaily.com/perfect-light-settings-on-windows-screens-with-best-brightools/"><u>Perfect Light Settings on Windows Screens with Best BrighTools</u></a></li>
<li><a href="https://windows11.techidaily.com/refine-your-mouses-click-speed-three-simple-adjustments/"><u>Refine Your Mouse's Click Speed: Three Simple Adjustments</u></a></li>
<li><a href="https://windows11.techidaily.com/resize-images-in-win11-a-step-by-step/"><u>Resize Images in Win11: A Step-by-Step</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/smartphonedslr-camerass-optimal-gimbals-uncovered-1-10-for-2024/"><u>Smartphone/DSLR Cameras's Optimal Gimbals Uncovered #1-#10 for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-perfect-font-theme-match-for-your-notepad/"><u>The Perfect Font, Theme Match for Your Notepad</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-printer-errors-another-computer/"><u>Troubleshooting Printer Errors: Another Computer?</u></a></li>
<li><a href="https://windows11.techidaily.com/turbo-valorant-setup-escape-the-01kbs-download-drought/"><u>Turbo Valorant Setup: Escape the 0.1KB/S Download Drought</u></a></li>
<li><a href="https://windows11.techidaily.com/tutorial-initiating-clipboard-operations-within-microsoft-edges-protected-environment-windows-11/"><u>Tutorial: Initiating Clipboard Operations Within Microsoft Edge's Protected Environment, Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-of-error-code-80080300-with-microsoft-teams/"><u>Unraveling the Mystery of Error Code 80080300 with Microsoft Teams</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-future-of-shopping-microsoft-ai-hub/"><u>Unveiling the Future of Shopping: Microsoft AI Hub</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-keyboard-graphic-helper/"><u>Windows 11'S Keyboard Graphic Helper</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-against-apexs-hurdles-in-windows-11-crashes/"><u>Winning Against Apex's Hurdles in Windows 11 Crashes</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>