---
title: "Make File Management Simple: Using Windows' Autodelete Feature"
date: 2024-08-15T15:58:10.400Z
updated: 2024-08-16T15:58:10.400Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Make File Management Simple: Using Windows' Autodelete Feature"
excerpt: "This Article Describes Make File Management Simple: Using Windows' Autodelete Feature"
keywords: Simplify File Handling,Windows Delete Automatically,Easy File Organization,Autodelete in Windows,Streamline File Management,Simplified Deletion Feature,Auto-Deleting Files Method
thumbnail: https://thmb.techidaily.com/0a18a6b406ce9f21eda937adac64825b459ee3a87d13a642256000f5335eb2cc.jpg
---

## Make File Management Simple: Using Windows' Autodelete Feature

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
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. In the **Name** box, enter a name for the task.
6. Now, in the **General** tab, under the **Security options** section, select the **Run whether the user is logged on or not** option.
7. Make sure the **Do not store password** checkbox is unselected.
8. Click on the **Triggers** tab and select the **New** button.
9. Select **On a schedule** option using the **Begin the task** setting.  
![new trigger section on task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-trigger-section-on-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
10. Under the **Settings** section, set up the timings of the tasks you'd like to run. Finally, click on **OK**.

 Now, head to the **Actions** tab and click on the **New** button. From the **Actions** drop-down menu, select the **Start a program** option.

 In the Program/script box, type in the following command:

`ForFiles`

![new action tab on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-action-tab-on-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901410&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix Pro - Software based live production. vMix Pro includes everything in vMix 4K plus 8 channels of Replay and 8 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->

 That's it—finalize the changes by clicking **OK** once again, and you will be done in no time. From here forward, your files will be automatically deleted within the specified time. Of course, if you later change your mind you can always reverse this setting by simply deleting the new folder your created in first step (which in our case, will be **New Folder 1**).

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
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
<li><a href="https://youtube-data.techidaily.com/024-approved-discover-leading-fonts-boosting-your-youtube-thumbnails/"><u>[New] 2024 Approved  Discover Leading Fonts  Boosting Your YouTube Thumbnails</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-become-a-broadcast-pro-screen-sharing-101-for-facebookers-for-2024/"><u>[New] Become a Broadcast Pro  Screen Sharing 101 for Facebookers for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-social-sharing-simplified-uploading-immersive-mobile-photography/"><u>[New] In 2024, Social Sharing Simplified  Uploading Immersive Mobile Photography</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-a-step-by-step-guide-to-including-vimeo-on-instagram/"><u>[Updated] A Step-by-Step Guide to Including Vimeo on Instagram</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-full-financial-forecast-the-podcast-inception-price-tag/"><u>2024 Approved  Full Financial Forecast  The Podcast Inception Price Tag</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-music-files-on-realme-11-pro-by-fonelab-android-recover-music/"><u>Complete guide for recovering music files on Realme 11 Pro</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/downloading-and-updating-your-razer-driver-for-various-windows-os-versions/"><u>Downloading and Updating Your Razer Driver for Various Windows OS Versions</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/exploring-varieties-in-gesture-tech-for-2024/"><u>Exploring Varieties in Gesture Tech for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-hide-the-search-bar-from-the-taskbar-on-windows-11/"><u>How to Hide the Search Bar From the Taskbar on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reestablish-windows-steam-connections/"><u>How to Reestablish Windows-Steam Connections</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-revert-time-travelled-command-history/"><u>How to Revert Time-Travelled Command History</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-unlink-apple-id-from-iphone-7-plus-by-drfone-ios/"><u>How To Unlink Apple ID From iPhone 7 Plus</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-reset-a-locked-nokia-130-music-phone-by-drfone-android/"><u>In 2024, How to Reset a Locked Nokia 130 Music Phone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-top-obs-recording-software-unveiled-in-our-latest-study/"><u>In 2024, Top OBS Recording Software Unveiled in Our Latest Study</u></a></li>
<li><a href="https://windows11.techidaily.com/instantly-access-dark-mode-in-notepad-windows-11-edition/"><u>Instantly Access Dark Mode in Notepad, Windows 11 Edition</u></a></li>
<li><a href="https://extra-hints.techidaily.com/journeying-beyond-boundaries-jaunt-vr-analysis/"><u>Journeying Beyond Boundaries  Jaunt VR Analysis</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-apple-iphone-se-drfone-by-drfone-virtual-ios/"><u>Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Apple iPhone SE | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-component-services-accessibility-in-w11/"><u>Mastering Component Services Accessibility in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-error-0x80070570-restoring-broken-files-on-windows-11/"><u>Mastering Error 0X80070570: Restoring Broken Files on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-fixing-uninstall-glitches-on-windows-11/"><u>Mastering the Art of Fixing Uninstall Glitches on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-group-policies-a-threefold-pathway-guide/"><u>Mastering Windows Group Policies: A Threefold Pathway Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-in-managing-windows-11-tpm-issues/"><u>Mastery in Managing Windows 11 TPM Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-device-dialogue-syncing-android-and-windows/"><u>Navigating Device Dialogue: Syncing Android & Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11s-security-with-rufus-expertise/"><u>Navigating Windows 11'S Security with Rufus Expertise</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-steam-content-access-difficulty-on-windows-systems/"><u>Overcoming Steam Content Access Difficulty on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/picking-between-google-and-windows-file-sharing-technologies/"><u>Picking Between Google and Windows File Sharing Technologies</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-cure-for-flickering-screens-on-windows-11-pcs/"><u>Quick Cure for Flickering Screens on Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-to-stop-steam-from-halting-games-on-windows-11/"><u>Quick Fixes to Stop Steam From Halting Games on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/recovering-a-mute-windows-start-button-issue/"><u>Recovering a Mute Windows Start Button Issue</u></a></li>
<li><a href="https://techidaily.com/repair-corrupt-pdf-v12-file-using-pdf-repair-tool-by-stellar-guide/"><u>Repair Corrupt PDF v1.2 File using PDF Repair Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-classics-playing-oldschool-games-with-dosbox-x/"><u>Reviving Classics: Playing Oldschool Games with DOSBox-X</u></a></li>
<li><a href="https://windows11.techidaily.com/smooth-windows-11-access-with-pin-solutions/"><u>Smooth Windows 11 Access with PIN Solutions</u></a></li>
<li><a href="https://fox-that.techidaily.com/solving-iphone-notification-problems-a-guide-with-7-key-tips/"><u>Solving iPhone Notification Problems: A Guide with 7 Key Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-spotify-links-on-windows-11-pcs/"><u>Streamlining Spotify Links on Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-non-functional-windows-11-keys/"><u>Tackling Non-Functional Windows 11 Keys</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-ultimate-list-of-advice-finding-your-dream-selfie-stick-in-6-steps/"><u>The Ultimate List of Advice: Finding Your Dream Selfie Stick in 6 Steps</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-15-apps-to-hack-wifi-password-on-xiaomi-redmi-note-12-4g-by-drfone-android/"><u>Top 15 Apps To Hack WiFi Password On Xiaomi Redmi Note 12 4G</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/transform-your-trip-diary-into-haul-video-hype-for-2024/"><u>Transform Your Trip Diary Into Haul Video Hype for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-inaccurate-power-estimator-on-windows-11-desktops/"><u>Troubleshooting Inaccurate Power Estimator on Windows 11 Desktops</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/understanding-and-correcting-the-new-world-connection-mistake/"><u>Understanding and Correcting the New World Connection Mistake</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-power-of-testing-enable-sandbox-in-win-11/"><u>Unlocking the Power of Testing: Enable Sandbox in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-leaderboard-game-lol/"><u>Unlocking Windows Leaderboard Game (LOL)</u></a></li>
<li><a href="https://windows11.techidaily.com/upgrade-windows-11-notebook-using-ai-expert/"><u>Upgrade Windows 11 Notebook Using AI Expert</u></a></li>
<li><a href="https://windows11.techidaily.com/weekend-wins-lifetime-win10-starting-at-612/"><u>Weekend Wins: Lifetime Win10, Starting at $6.12</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-bluescreen-blitz-implement-these-11-essential-steps/"><u>Win11 Bluescreen Blitz: Implement These 11 Essential Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/zero-cost-hardware-recreation-in-windows/"><u>Zero-Cost Hardware Recreation in Windows</u></a></li>
</ul></div>
