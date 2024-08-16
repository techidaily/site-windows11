---
title: "Windows 10/11 Auto-Cleanup: A Step-by-Step Guide"
date: 2024-08-15T15:26:25.332Z
updated: 2024-08-16T15:26:25.332Z
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
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
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Your files will be removed as quickly as soon as you hit the above commands.

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Use Task Scheduler on Windows

 Task Scheduler is a simple Windows tool that lets you easily automate your repetitive Windows tasks. Just set up the task, and the app will handle whatever you have asked it to do. When it comes to auto-deleting your files or folders, the _ForFiles_ command is what you will need to help you delete your older files or folders.

 Here's how you can automate the deletion:

1. Head to the **Start menu** search bar, type in 'task scheduler', and select the best match.
2. Right-click on **Task Scheduler Library** and select **New Folder**.
3. Put in any name and click on **OK**.
4. Right-click on the recently created folder and select the **Create Task** option.  
![task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/task-scheduler.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
<!-- affiliate ads end -->
5. In the **Name** box, enter a name for the task.
6. Now, in the **General** tab, under the **Security options** section, select the **Run whether the user is logged on or not** option.
7. Make sure the **Do not store password** checkbox is unselected.
8. Click on the **Triggers** tab and select the **New** button.
9. Select **On a schedule** option using the **Begin the task** setting.  
![new trigger section on task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-trigger-section-on-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-android-users-ultimate-selection-top-10-fb-video-extractor-tools/"><u>[Updated] 2024 Approved  Android Users' Ultimate Selection  Top 10 FB Video Extractor Tools</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-crafting-your-first-twitter-profile-for-2024/"><u>[Updated] Crafting Your First Twitter Profile for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-precision-and-perfection-a-guide-to-youtube-studio-video-edits/"><u>[Updated] Precision and Perfection  A Guide to YouTube Studio Video Edits</u></a></li>
<li><a href="https://windows11.techidaily.com/10-overlooked-windows-11-aesthetic-themes/"><u>10 Overlooked Windows 11 Aesthetic Themes</u></a></li>
<li><a href="https://windows11.techidaily.com/10-solutions-for-windows-uncovering-lost-nexus-controllers/"><u>10 Solutions for Windows: Uncovering Lost Nexus Controllers</u></a></li>
<li><a href="https://howto.techidaily.com/11-proven-solutions-to-fix-google-play-store-not-working-issue-on-nokia-c110-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Proven Solutions to Fix Google Play Store Not Working Issue on Nokia C110 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/5-ways-to-fix-the-remote-procedure-call-failed-error-in-windows/"><u>5 Ways to Fix the Remote Procedure Call Failed Error in Windows</u></a></li>
<li><a href="https://extra-information.techidaily.com/a-detailed-guide-youtubes-most-engaging-storytellers-in-23-for-2024/"><u>A Detailed Guide  YouTube's Most Engaging Storytellers in '23 for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/a-practical-approach-to-windows-network-file-transfer-via-python/"><u>A Practical Approach to Windows Network File Transfer via Python</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerating-epic-launcher-on-pcs-a-quick-guide/"><u>Accelerating Epic Launcher on PCs: A Quick Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/accessing-windows-11s-screen-capture-shortcut/"><u>Accessing Windows 11'S Screen Capture Shortcut</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-portable-network-capabilities-via-windows-11-pc/"><u>Activating Portable Network Capabilities via Windows 11 PC</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-11-get-support-disruption/"><u>Addressing Windows 11 'Get Support' Disruption</u></a></li>
<li><a href="https://windows11.techidaily.com/adjust-brightness-slider-look-for-the-brightness-slider-under-system-or-personalization-tabs-in-settings/"><u>Adjust Brightness Slider: Look for the Brightness Slider Under 'System' Or 'Personalization' Tabs in Settings</u></a></li>
<li><a href="https://extra-tips.techidaily.com/animated-artistry-on-instagram-caption-creativity/"><u>Animated Artistry on Instagram  Caption Creativity</u></a></li>
<li><a href="https://windows11.techidaily.com/banish-os-requirement-warning-labels-in-windows-11/"><u>Banish OS Requirement Warning Labels in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/bridge-the-mc-lan-chasm-7-key-fixes-for-windows-users/"><u>Bridge the MC LAN Chasm: 7 Key Fixes for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/browser-breakdowns-heres-how-to-get-past-the-roadblocks-in-win-os/"><u>Browser Breakdowns? Here's How to Get Past the Roadblocks in WIN OS</u></a></li>
<li><a href="https://windows11.techidaily.com/bypass-license-validity-warning-on-w10-and-w11-systems/"><u>Bypass License Validity Warning on W10 & W11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/christmas-tech-surprises-through-microsofts-marketplace/"><u>Christmas Tech Surprises Through Microsoft's Marketplace</u></a></li>
<li><a href="https://windows11.techidaily.com/command-your-computer-mastery-of-windows-through-alomware/"><u>Command Your Computer: Mastery of Windows Through AlomWare</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-tutorial-for-extracting-dual-and-multi-archive-files/"><u>Comprehensive Tutorial for Extracting Dual and Multi-Archive Files</u></a></li>
<li><a href="https://windows11.techidaily.com/converting-oculus-quest-2-to-windows-vr-compatibility-level/"><u>Converting Oculus Quest 2 to Windows VR Compatibility Level</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-systemsettings-executable-errors-on-windows-11/"><u>Correcting SystemSettings Executable Errors on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/deterring-windows-auto-update-alerts/"><u>Deterring Windows Auto-Update Alerts</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-factory-seal-on-windows-11/"><u>Disabling Factory Seal on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-your-ideal-nvidia-driver-entertainment-driven-selection/"><u>Discover Your Ideal Nvidia Driver: Entertainment-Driven Selection</u></a></li>
<li><a href="https://windows11.techidaily.com/discovery-of-four-cortana-succession-steps/"><u>Discovery of Four Cortana Succession Steps</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-change-lock-screen-wallpaper-on-infinix-smart-8-plus-by-drfone-android/"><u>How to Change Lock Screen Wallpaper on Infinix Smart 8 Plus</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-your-oneplus-ace-2-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>How to Mirror Your OnePlus Ace 2 Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-full-guide-on-mirroring-your-tecno-spark-10-pro-to-your-pcmac-drfone-by-drfone-android/"><u>In 2024, Full Guide on Mirroring Your Tecno Spark 10 Pro to Your PC/Mac | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-premier-vr-manipulators-to-try-now/"><u>In 2024, Premier VR Manipulators to Try Now</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-remove-device-supervision-from-your-apple-iphone-8-drfone-by-drfone-ios/"><u>In 2024, Remove Device Supervision From your Apple iPhone 8 | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/mastering-pip-google-chrome-across-devices-for-2024/"><u>Mastering PIP  Google Chrome Across Devices for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/1719319278608-microsoft-woes-solutions-to-ease-your-way/"><u>Microsoft Woes? Solutions to Ease Your Way</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/network-locked-sim-card-inserted-on-your-oppo-f25-pro-5g-phone-unlock-it-now-by-drfone-android/"><u>Network Locked SIM Card Inserted On Your Oppo F25 Pro 5G Phone? Unlock It Now</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/pro-3-camera-insight-mastering-video-on-the-go-with-ion/"><u>Pro 3 Camera Insight  Mastering Video on the Go with ION</u></a></li>
<li><a href="https://buynow-info.techidaily.com/the-future-is-here-an-expert-analysis-on-the-groundbreaking-imac-featuring-the-game-changing-m1-chip/"><u>The Future Is Here: An Expert Analysis on the Groundbreaking iMac Featuring the Game-Changing M1 Chip</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/top-5-solutions-to-obs-studio-video-editing-for-2024/"><u>Top 5 Solutions to OBS Studio Video Editing for 2024</u></a></li>
</ul></div>
