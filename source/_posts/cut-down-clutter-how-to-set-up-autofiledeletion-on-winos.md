---
title: "Cut Down Clutter: How to Set Up AutoFileDeletion on WINOS"
date: 2024-07-11T22:27:27.976Z
updated: 2024-07-12T22:27:27.976Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Cut Down Clutter: How to Set Up AutoFileDeletion on WINOS"
excerpt: "This Article Describes Cut Down Clutter: How to Set Up AutoFileDeletion on WINOS"
keywords: Clutter Reduction Tips,AutoFileManagement Windows,Deletion Schedule Setting,WINOS Organization Tricks,Simplify File Management,Automatic Deleted Files,Digital Decluttering Techniques
thumbnail: https://thmb.techidaily.com/e3528d506823cb6dca25eee03d51754fbb17fe96f4d59ce559e11e5be6c55331.jpg
---

## Cut Down Clutter: How to Set Up AutoFileDeletion on WINOS

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
<li><a href="https://windows11.techidaily.com/confronting-error-code-0x8007045d-a-guide-for-windows-11-users/"><u>Confronting Error Code 0X8007045d: A Guide for Windows 11 Users</u></a></li>
<li><a href="https://animation-videos.techidaily.com/how-to-reduce-gif-size-and-best-gif-resizers/"><u>How to Reduce GIF Size and Best GIF Resizers</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-catchemall-celebrate-national-pokemon-day-with-virtual-location-on-oneplus-11-5g-drfone-by-drfone-virtual-android/"><u>In 2024, CatchEmAll Celebrate National Pokémon Day with Virtual Location On OnePlus 11 5G | Dr.fone</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-heartfelt-goodbyes-free-or-subscribed-video-endings/"><u>2024 Approved  Heartfelt Goodbyes  Free or Subscribed Video Endings</u></a></li>
<li><a href="https://android-unlock.techidaily.com/unlock-your-vivo-y56-5g-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>Unlock Your Vivo Y56 5G Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/dive-into-digital-canvases-the-best-7-apps-for-win10-artists/"><u>Dive Into Digital Canvases: The Best 7 Apps for Win10 Artists</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-expedition-tools-for-storytelling-through-lenses/"><u>[Updated] Expedition Tools for Storytelling Through Lenses</u></a></li>
<li><a href="https://windows11.techidaily.com/concealing-the-taskbar-written-words-in-windows-11-ui/"><u>Concealing the Taskbar’ Written Words in Windows 11 UI</u></a></li>
<li><a href="https://extra-hints.techidaily.com/hubsan-h501s-exploration-the-ultimate-fpv-experience/"><u>Hubsan H501S Exploration  The Ultimate FPV Experience</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/navigating-the-world-of-unfollowed-instagrams/"><u>Navigating the World of Unfollowed Instagrams</u></a></li>
<li><a href="https://windows11.techidaily.com/classic-revival-atlasos-for-outdated-pcs/"><u>Classic Revival: AtlasOS for Outdated PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/craft-an-individualized-look-for-your-schedule-in-windows-outlook/"><u>Craft an Individualized Look for Your Schedule in Windows Outlook</u></a></li>
<li><a href="https://some-approaches.techidaily.com/upward-perspectives-capturing-landscapes-from-your-phone-for-2024/"><u>Upward Perspectives  Capturing Landscapes From Your Phone for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/cryptographic-concealment-stashing-zip-files-undetected-on-windows-pcs/"><u>Cryptographic Concealment: Stashing Zip Files Undetected on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-correcting-windows-error-0x8007021/"><u>Decoding and Correcting Windows Error 0X8007021</u></a></li>
<li><a href="https://windows11.techidaily.com/complete-approach-to-deleting-the-wsl-subsystem/"><u>Complete Approach to Deleting the WSL Subsystem</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-ace-your-viewing-experience-onboarding-av1-in-youtube/"><u>[New] In 2024, Ace Your Viewing Experience  Onboarding AV1 in YouTube</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-enhance-rhythm-skills-no-cost-with-these-free-beat-trackers/"><u>[Updated] 2024 Approved  Enhance Rhythm Skills - No Cost, With These Free Beat Trackers</u></a></li>
<li><a href="https://windows11.techidaily.com/ditching-windows-11-standards-top-10-app-list/"><u>Ditching Windows 11 Standards: Top 10 App List</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-top-ranked-list-of-high-quality-3ds-emulation-software/"><u>[Updated] In 2024, Top-Ranked List of High-Quality 3DS Emulation Software</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-winos-gain-control-over-applications-browsing/"><u>Decoding WinOS: Gain Control over Applications, Browsing</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-occupied-files-a-guide-for-windows-11-users/"><u>Clearing Occupied Files: A Guide for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-overcoming-0x80072af9-errors/"><u>Decoding and Overcoming 0X80072AF9 Errors</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-2024-approved-what-is-ai-voice-text-to-speech/"><u>New 2024 Approved What Is AI Voice Text to Speech?</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-picturemosaic-maker-blend-videos-and-pics-macos/"><u>2024 Approved  PictureMosaic Maker  Blend Videos & Pics macOS</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-microsoft-store-failure-codes-x800704cf/"><u>Disabling Microsoft Store Failure Codes X800704CF</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-tecno-pova-5-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Here Are Some Reliable Ways to Get Pokemon Go Friend Codes For Tecno Pova 5 Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-terminal-in-win11-start-fresh/"><u>Configuring Terminal in Win11: Start Fresh</u></a></li>
<li><a href="https://windows11.techidaily.com/compact-windows-powered-systems-unveiled/"><u>Compact Windows-Powered Systems Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-unique-room-backgrounds-with-windows-spotlight-pics/"><u>Crafting Unique Room Backgrounds with Windows Spotlight Pics</u></a></li>
<li><a href="https://windows11.techidaily.com/convenient-quick-settings-navigating-win-11-interface/"><u>Convenient Quick Settings: Navigating Win 11 Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-failed-uploads-with-onedrive-in-w11/"><u>Correcting Failed Uploads with OneDrive in W11</u></a></li>
<li><a href="https://driver-install.techidaily.com/hp-officejet-pro-8710-direct-windows-support-pack/"><u>HP OfficeJet Pro 8710 Direct Windows Support Pack</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-essential-choice-10-free-youtube-subtitle-extractors/"><u>[New] Essential Choice  10 FREE YouTube Subtitle Extractors</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-advanced-windows-index-features/"><u>Configuring Advanced Windows Index Features</u></a></li>
<li><a href="https://windows11.techidaily.com/direct-route-out-of-windows-11s-protective-barrier/"><u>Direct Route Out of Windows 11'S Protective Barrier</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/iphone-users-learn-simple-screen-recording-now/"><u>Iphone Users, Learn Simple Screen Recording Now</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-zoom-anomalies-addressing-error-1132-in-windows-11/"><u>Correcting Zoom Anomalies: Addressing Error 1132 in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/compelling-windows-applications-for-video-transformation/"><u>Compelling Windows Applications for Video Transformation</u></a></li>
<li><a href="https://extra-tips.techidaily.com/mastering-your-media-with-vlcs-secret-features/"><u>Mastering Your Media with VLC's Secret Features</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/asus-rog-phone-7-music-recovery-recover-deleted-music-from-asus-rog-phone-7-by-fonelab-android-recover-music/"><u>Asus ROG Phone 7 Music Recovery - Recover Deleted Music from Asus ROG Phone 7</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-lenovo-laptop-screen-logging-made-easy-for-2024/"><u>[Updated] Lenovo Laptop Screen Logging Made Easy for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-prime-video-cameras-of-2024-decoded/"><u>[Updated] Prime Video Cameras of 2024 Decoded</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-how-to-activate-and-use-mouseclicklock-efficiently/"><u>Decoding How to Activate and Use MouseClickLock Efficiently</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-tutorial-onedrive-plus-microsoft-login-on-pc/"><u>Comprehensive Tutorial: OneDrive + Microsoft Login on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/cross-network-stealth-securing-data-flow-in-winos/"><u>Cross-Network Stealth: Securing Data Flow in WinOS</u></a></li>
<li><a href="https://windows11.techidaily.com/contrasting-the-workflow-of-cloud-based-and-disk-installed-windows-oses/"><u>Contrasting the Workflow of Cloud-Based & Disk Installed Windows OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/direct-guide-to-reactivate-print-spool/"><u>Direct Guide to Reactivate Print Spool</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>