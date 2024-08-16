---
title: Keep Your Disk Space Clear with Auto-Delete in Win11
date: 2024-08-15T15:59:06.379Z
updated: 2024-08-16T15:59:06.379Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Keep Your Disk Space Clear with Auto-Delete in Win11
excerpt: This Article Describes Keep Your Disk Space Clear with Auto-Delete in Win11
keywords: Win11 Storage Cleanup,AutoDeletion Win11,FreeDisk Win11,Win11 Space Management,DiskSpace Auto-Delete,Win11 Clearance,Optimize Win11 Disk
thumbnail: https://thmb.techidaily.com/494747ec004285de2aadee4c9fc771562b4f42ca29ed6aecefce800cf9eedde4.jpg
---

## Keep Your Disk Space Clear with Auto-Delete in Win11

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
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->

 Your files will be removed as quickly as soon as you hit the above commands.

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
10. Under the **Settings** section, set up the timings of the tasks you'd like to run. Finally, click on **OK**.

 Now, head to the **Actions** tab and click on the **New** button. From the **Actions** drop-down menu, select the **Start a program** option.

 In the Program/script box, type in the following command:

`ForFiles`

![new action tab on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-action-tab-on-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
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
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
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
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-innovative-approaches-to-monitoring-and-snapping-digital-displays/"><u>[New] 2024 Approved  Innovative Approaches to Monitoring and Snapping Digital Displays</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-mastering-360-fb-live-broadcasts/"><u>[New] 2024 Approved  Mastering 360 FB Live Broadcasts</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-behind-the-scenes-how-to-flip-your-snaps/"><u>[New] Behind-the-Scenes  How to Flip Your Snaps</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-elite-image-processor-upgrade-your-viewing-experience-for-2024/"><u>[New] Elite Image Processor  Upgrade Your Viewing Experience for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-sj6-ultimate-face-off-with-xiaomis-yi-4k-genius/"><u>[New] SJ6 Ultimate Face-Off with Xiaomi's Yi 4K Genius</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-unique-channels-generating-top-notch-video-naming/"><u>[New] Unique Channels  Generating Top-Notch Video Naming</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-cushioning-calm-top-relaxing-pc-titles/"><u>[Updated] 2024 Approved  Cushioning Calm  Top Relaxing PC Titles</u></a></li>
<li><a href="https://android-unlock.techidaily.com/10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-vivo-s17-by-drfone-android/"><u>10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On Vivo S17</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-customizing-youtube-viewing-policies-for-your-content/"><u>2024 Approved  Customizing YouTube Viewing Policies for Your Content</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-navigating-facebooks-copyright-enforcement-on-live-feeds/"><u>2024 Approved  Navigating Facebook's Copyright Enforcement on Live Feeds</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-pathways-to-identifying-outstanding-video-artists/"><u>2024 Approved  Pathways to Identifying Outstanding Video Artists</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/2024-approved-unlock-6-free-youtube-endings-for-pros/"><u>2024 Approved  Unlock 6 Free YouTube Endings for Pros!</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/2024-approved-viral-tendencies-on-twittersphere-most-viewed/"><u>2024 Approved  Viral Tendencies on Twittersphere (Most Viewed)</u></a></li>
<li><a href="https://windows11.techidaily.com/9-ways-to-fix-the-0x8004def5-onedrive-error-code-on-windows-11/"><u>9 Ways to Fix the 0X8004def5 OneDrive Error Code on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/a-stepwise-guide-to-banishing-the-onedrive-icon-from-explorer/"><u>A Stepwise Guide to Banishing the OneDrive Icon From Explorer</u></a></li>
<li><a href="https://extra-information.techidaily.com/achieve-creative-vibrancy-with-picshots-assistance/"><u>Achieve Creative Vibrancy with Picshot's Assistance</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-non-admin-privilege-levels-in-windows-os/"><u>Adjusting Non-Admin Privilege Levels in Windows OS</u></a></li>
<li><a href="https://buynow-help.techidaily.com/affordable-security-alerts-with-iseebell-top-under-50-video-doorbells-comparison/"><u>Affordable Security Alerts with ISeeBell - Top Under $50 Video Doorbells Comparison</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-windows-11-stumbling-blocks-the-most-crucial-tips/"><u>Avoiding Windows 11 Stumbling Blocks: The Most Crucial Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-windows-updates-0x80242016-hurdles/"><u>Avoiding Windows Update's 0X80242016 Hurdles</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-error-code-x80131500-at-store/"><u>Breaking Down Error Code: X80131500 at Store</u></a></li>
<li><a href="https://extra-resources.techidaily.com/complete-biomechanical-study-2023/"><u>Complete Biomechanical Study 2023</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-fn-keys-to-maximize-pc-efficiency-in-wins/"><u>Customizing FN Keys to Maximize PC Efficiency in Wins</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-down-energy-waste-without-slowing-down-games/"><u>Cutting Down Energy Waste Without Slowing Down Games</u></a></li>
<li><a href="https://windows11.techidaily.com/digital-dream-team-top-windows-apps-for-a-winning-start/"><u>Digital Dream Team: Top Windows Apps for a Winning Start</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-clutter-software-uninstallation-tricks-for-windows-11-106-chars/"><u>Eliminating Clutter: Software Uninstallation Tricks for Windows 11 (106 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-windows-11s-functionality-top-strategies-for-widget-upgrades/"><u>Enhancing Windows 11'S Functionality: Top Strategies for Widget Upgrades</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-a-non-compatible-device-after-windows-11-installation/"><u>Fixing a Non-Compatible Device After Windows 11 Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/get-ahead-in-passwords-7-best-free-generation-tools-for-windows/"><u>Get Ahead in Passwords: 7 Best Free Generation Tools for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/hidden-harmony-seamlessly-blending-image-and-zip-archives-win1011/"><u>Hidden Harmony: Seamlessly Blending Image and ZIP Archives WIN10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-removing-windows-11s-taskbar-chatter-affects-you-the-user/"><u>How Removing Windows 11'S Taskbar Chatter Affects You, The User?</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/how-to-share-tiktok-videos-to-facebook-in-2024/"><u>How to Share TikTok Videos to Facebook, In 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-full-guide-on-mirroring-your-nokia-xr21-to-your-pcmac-drfone-by-drfone-android/"><u>In 2024, Full Guide on Mirroring Your Nokia XR21 to Your PC/Mac | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-can-i-use-a-fake-gps-without-mock-location-on-honor-90-drfone-by-drfone-virtual-android/"><u>In 2024, How Can I Use a Fake GPS Without Mock Location On Honor 90? | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-remove-apple-id-from-apple-iphone-x-without-password-by-drfone-ios/"><u>In 2024, How to Remove Apple ID from Apple iPhone X without Password?</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-revolutionizing-gameplay-a-curated-list-of-stardew-valleys-top-7-mods/"><u>In 2024, Revolutionizing Gameplay  A Curated List of Stardew Valley's Top 7 Mods</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-filmmakers-toolbox-in-depth-guide-to-cinematic-techniques-in-24/"><u>In 2024, The Filmmaker’s Toolbox  In-Depth Guide to Cinematic Techniques in '24</u></a></li>
<li><a href="https://windows11.techidaily.com/master-your-timers-fixing-scheduler-errors/"><u>Master Your Timers: Fixing Scheduler Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/microsofts-helpers-quick-fixes-for-window-woes/"><u>Microsoft's Helpers: Quick Fixes for Window Woes!</u></a></li>
<li><a href="https://technical-tips.techidaily.com/night-owls-compannion-how-to-activate-dark-mode-on-your-iphone-easily/"><u>Night Owl's Compannion: How to Activate Dark Mode on Your iPhone Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-your-experience-adding-uninstall-shortcut-in-windows-10/"><u>Optimize Your Experience: Adding Uninstall Shortcut in Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/personalize-your-desktop-space-win-os-snap-configurations/"><u>Personalize Your Desktop Space: Win OS Snap Configurations</u></a></li>
<li><a href="https://windows11.techidaily.com/resurrect-corrupted-files-win-11s-zip-fix-guide/"><u>Resurrect Corrupted Files: Win 11'S ZIP Fix Guide</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/revolutionizing-audience-retention-on-youtube-with-these-top-6-techniques-for-2024/"><u>Revolutionizing Audience Retention on YouTube with These Top 6 Techniques for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/simplified-guide-to-shift-your-qbittorrent-installation/"><u>Simplified Guide to Shift Your qBittorrent Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/solve-no-errors-on-win11-quick-fix-guide/"><u>Solve No Errors on Win11 - Quick Fix Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-window-11s-missing-clickables-problem/"><u>Solving Window 11'S Missing Clickables Problem</u></a></li>
<li><a href="https://windows11.techidaily.com/success-reinstalling-microsofts-pc-manager-in-win8/"><u>Success! Reinstalling Microsoft's PC Manager in Win8</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-the-winds-of-windows-fix-for-non-openable-exes/"><u>Taming the Winds of Windows: Fix for Non-Openable EXEs</u></a></li>
<li><a href="https://windows11.techidaily.com/tech-enthusiasts-treasure-hunt-unlock-free-lifetime-windows-11-from-black-fridays-best-price/"><u>Tech Enthusiasts’ Treasure Hunt: Unlock Free Lifetime Windows 11 From Black Friday's Best Price</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-unblock-application-packages-on-windows-servers/"><u>Techniques to Unblock Application Packages on Windows Servers</u></a></li>
<li><a href="https://win11.techidaily.com/ten-simple-steps-for-fixing-def5-onedrive-woes-on-win11/"><u>Ten Simple Steps for Fixing DEF5: OneDrive Woes on Win11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-magnificent-art-of-pokemon-go-streaming-on-tecno-spark-go-2023-drfone-by-drfone-virtual-android/"><u>The Magnificent Art of Pokemon Go Streaming On Tecno Spark Go (2023)? | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/toms-tech-review-in-depth-insights-on-top-hardware/"><u>Tom's Tech Review: In-Depth Insights on Top Hardware</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-11-free-apps-to-check-imei-on-motorola-phones-by-drfone-android/"><u>Top 11 Free Apps to Check IMEI on Motorola Phones</u></a></li>
<li><a href="https://windows11.techidaily.com/triumph-over-the-quiet-shop-microsoft-writes-on-error-x00000000/"><u>Triumph over the Quiet Shop: Microsoft' Writes on Error X00000000</u></a></li>
<li><a href="https://win-amazing.techidaily.com/unlock-full-graphics-power-fresh-install-of-the-newest-amd-vega-64-drivers-for-windows-systems/"><u>Unlock Full Graphics Power: Fresh Install of the Newest AMD Vega 64 Drivers for Windows Systems!</u></a></li>
<li><a href="https://unlock-android.techidaily.com/unlocking-the-power-of-smart-lock-a-beginners-guide-for-xiaomi-14-pro-users-by-drfone-android/"><u>Unlocking the Power of Smart Lock A Beginners Guide for Xiaomi 14 Pro Users</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-power-of-dism-in-win11-image-management/"><u>Unveiling the Power of Dism in Win11 Image Management</u></a></li>
<li><a href="https://windows11.techidaily.com/why-task-managers-feature-extras-under-edge/"><u>Why Task Managers Feature Extras Under Edge?</u></a></li>
<li><a href="https://windows11.techidaily.com/zeroing-out-bloatware-windows-11-edition/"><u>Zeroing Out Bloatware: Windows 11 Edition</u></a></li>
</ul></div>
