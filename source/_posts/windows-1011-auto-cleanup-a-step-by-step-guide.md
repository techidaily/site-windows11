---
title: "Windows 10/11 Auto-Cleanup: A Step-by-Step Guide"
date: 2024-07-11T22:07:24.563Z
updated: 2024-07-12T22:07:24.563Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows 10/11 Auto-Cleanup: A Step-by-Step Guide"
excerpt: "This Article Describes Windows 10/11 Auto-Cleanup: A Step-by-Step Guide"
keywords: Win10AutoClean,Win11Maintenance,CleanUpWindows,SystemResetGuide,AutoRefreshWin,PCUpdateSteps,OSCleaningTips
thumbnail: https://thmb.techidaily.com/399b71f22f6a0f097f9f941327a817b697b933fa54dbaf37480f689ec0e73886.jpg
---

## Windows 10/11 Auto-Cleanup: A Step-by-Step Guide

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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://snapchat-videos.techidaily.com/new-mastering-video-storage-of-snapchat-stories/"><u>[New] Mastering Video Storage of Snapchat Stories</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-error-0x887a0006-on-windows-devices/"><u>Addressing Error 0X887A0006 on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/automate-image-display-7-clever-strategies-for-windows-11/"><u>Automate Image Display: 7 Clever Strategies for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/1719258336470-escalate-emulation-faster-yuzu-win-users/"><u>Escalate Emulation: Faster Yuzu, WIN Users!</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-maximize-your-reach-optimizing-social-media-images-with-the-right-aspect-ratios/"><u>New In 2024, Maximize Your Reach Optimizing Social Media Images with the Right Aspect Ratios</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-the-cinematographers-journey-shooting-top-notch-youtube-content/"><u>[Updated] In 2024, The Cinematographer's Journey  Shooting Top-Notch YouTube Content</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-in-2024-techniques-for-quieting-the-soundscape-in-recorded-movies/"><u>New In 2024, Techniques for Quieting the Soundscape in Recorded Movies</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-employing-google-trends-to-discover-compelling-video-themes/"><u>[New] In 2024, Employing Google Trends to Discover Compelling Video Themes</u></a></li>
<li><a href="https://windows11.techidaily.com/ultimate-7-list-cost-free-windows-media-centers/"><u>Ultimate 7 List: Cost-Free Windows Media Centers</u></a></li>
<li><a href="https://activate-lock.techidaily.com/unlock-your-device-icloud-dns-bypass-explained-and-tested-plus-easy-alternatives-on-apple-iphone-6-plus-by-drfone-ios/"><u>Unlock Your Device iCloud DNS Bypass Explained and Tested, Plus Easy Alternatives On Apple iPhone 6 Plus</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-earnings-escalate-500-subscriber-marker-achieved-for-2024/"><u>[Updated] Earnings Escalate  500-Subscriber Marker Achieved for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/zap-zaps-revitalizing-a-sluggish-windows-11-experience/"><u>Zap Zaps: Revitalizing a Sluggish Windows 11 Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/digital-transformation-for-windows-old-to-new-drivers/"><u>Digital Transformation for Windows: Old to New Drivers</u></a></li>
<li><a href="https://windows11.techidaily.com/volume-vanishing-act-top-remedies-for-muted-keys-in-windows/"><u>Volume Vanishing Act? Top Remedies for Muted Keys in Windows</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-from-ordinary-to-extraordinary-crafting-stunning-pfp-for-discord/"><u>[New] In 2024, From Ordinary to Extraordinary  Crafting Stunning Pfp for Discord</u></a></li>
<li><a href="https://windows11.techidaily.com/1719348778059-troubleshooting-wwinplusp-glitch-on-pc-solutions-included/"><u>Troubleshooting: WWin+P Glitch on PC, Solutions Included!</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-the-battle-against-windows-software-problems-7-ways/"><u>Winning the Battle Against Windows Software Problems (7 Ways)</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/best-ways-to-document-smartphone-use/"><u>Best Ways to Document Smartphone Use</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-ftdibussys-the-impact-on-windows-memory-standards-and-safety/"><u>Unraveling ftdibus.sys: The Impact on Windows' Memory Standards and Safety</u></a></li>
<li><a href="https://windows11.techidaily.com/winrars-corrected-compression-overcoming-sum-errors/"><u>WinRAR's Corrected Compression: Overcoming Sum Errors</u></a></li>
<li><a href="https://extra-resources.techidaily.com/from-silence-to-soundscape-step-by-step-in-audition/"><u>From Silence to Soundscape  Step-by-Step in Audition</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-keyboard-magic-custom-shortcuts-w11-style/"><u>Tailored Keyboard Magic: Custom Shortcuts W11 Style</u></a></li>
<li><a href="https://windows11.techidaily.com/combat-the-frustration-7-methods-for-restoring-windows-notepad/"><u>Combat the Frustration: 7 Methods for Restoring Window's Notepad</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-how-to-stop-game-proposals/"><u>Win11: How To Stop Game Proposals</u></a></li>
<li><a href="https://windows11.techidaily.com/breach-ethernet-speed-barriers-past-windows-100mbps-ceiling/"><u>Breach Ethernet Speed Barriers: Past Windows' 100Mbps Ceiling</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-facecam-videography-improving-image-quality-and-clarity/"><u>In 2024, Facecam Videography  Improving Image Quality and Clarity</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/in-2024-best-5-ai-movie-script-generators/"><u>In 2024, Best 5 AI Movie Script Generators</u></a></li>
<li><a href="https://windows11.techidaily.com/cost-effective-solutions-affordable-windows-11-key-access/"><u>Cost-Effective Solutions: Affordable Windows 11 Key Access</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-upcoming-moment-anticipated-new-features/"><u>Windows 11'S Upcoming Moment: Anticipated New Features</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-embed-presentation-asset-as-video-feature/"><u>[New] 2024 Approved  Embed Presentation Asset as Video Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooters-and-their-role-on-windows-11-systems/"><u>Troubleshooters and Their Role on Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/taskbar-chatting-feature-in-windows-11-user-implications/"><u>Taskbar Chatting Feature in Windows 11: User Implications</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-echoes-in-images-selfie-with-your-x-phone/"><u>[New] 2024 Approved  Echoes in Images  Selfie with Your X Phone</u></a></li>
<li><a href="https://windows11.techidaily.com/turn-your-windows-11-pc-into-a-self-contained-internet-station/"><u>Turn Your Windows 11 PC Into a Self-Contained Internet Station</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-your-photo-preview-heights/"><u>Customizing Your Photo Preview Heights</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-zooming-in-and-out-like-a-storytelling-pro-insta-tips/"><u>[Updated] In 2024, Zooming in and Out Like a Storytelling Pro  Insta Tips</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-best-stop-motion-software-online-creators-ranked-for-2024/"><u>Updated Best Stop Motion Software Online Creators Ranked for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-artisans-approach-to-high-dynamic-range-mastery-on-windows-11/"><u>The Artisan’s Approach to High Dynamic Range Mastery on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/timeless-upgrades-essential-time-saver-tools-for-pcs/"><u>Timeless Upgrades: Essential Time Saver Tools for PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/changing-home-screen-settings-without-start-menu/"><u>Changing Home Screen Settings Without Start Menu</u></a></li>
</ul></div>
