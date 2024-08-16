---
title: Remedying the Reparse Point Buffer Tag Error with OneDrive
date: 2024-08-15T16:01:26.367Z
updated: 2024-08-16T16:01:26.367Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Remedying the Reparse Point Buffer Tag Error with OneDrive
excerpt: This Article Describes Remedying the Reparse Point Buffer Tag Error with OneDrive
keywords: Reparse Buffer Fix,OneDrive Tag Error,BuffTag Solution,Drive Error Remedy,OneDrive Performance,Recycle Bin Bug Fix,File System Issue Resolve
thumbnail: https://thmb.techidaily.com/d16299364ff8a12ac1730983e510ad0f5d027390038abb94b7b607447c1cc871.jpg
---

## Remedying the Reparse Point Buffer Tag Error with OneDrive

 Have you encountered the "the tag present in the reparse point buffer is invalid" error when altering a folder or deleting it on your Windows device? You may have encountered this error when accessing a folder via Command Prompt or File Explorer, mainly for files and folders synced to OneDrive. How does this error occur? OneDrive is the source of the error.

 In this article, we'll explain the causes of this error and provide you with possible solutions to resolve it.

## What Causes "The Tag Present in the Reparse Point Buffer Is Invalid" on Windows?

 As mentioned earlier, the error is caused by a problem with OneDrive sync. It could be that the folder you're trying to access is corrupt, or that there is an issue with other system files preventing OneDrive from syncing successfully.

 There are several ways in which the "the tag present in the reparse point buffer is invalid" error can appear. Here are the two most common ones:

* Error 0x80071129: The tag present in the reparse point buffer is invalid
* Location not found: The tag present in the reparse point buffer is invalid

 "Error 0x80071129" or "Location not found" appears as the title of the error window, while the main part of the error appears in the error window. Any variation of this error has nearly the same causes, regardless of its nature. In light of that, similar fixes are effective in resolving the issue. Let's see how you can fix it.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## But First, Some Preliminary Checks

 Apply the following preliminary checks before attempting the major fixes:

* Pause the OneDrive sync and try opening the folder again.
* Restart your device once.
* Log out of your OneDrive account.
* If you have made any changes to the problematic folder on OneDrive, go back and revert them for a while.

 If the above preliminary checks do not solve the problem and the issue persists, start implementing the remaining fixes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
<!-- affiliate ads end -->
## 1\. Run a CHKDSK Scan

 For Windows users, CHKDSK is a go-to utility for scanning and fixing hard drive problems. Whenever users encounter a hard drive error or an issue with the data stored on their drive, the CHKDSK scan proves to be a godsend.

 This scan may be helpful to fix the issue under discussion since "the tag present in the reparse point buffer is invalid" is also associated with an inability to access a particular file correctly. Therefore, follow the steps below to run the CHKDSK scan before you attempt any other repair or fix:

1. In the Windows Search box, type**"Command Prompt** .**"**
2. Right-click the**Command Prompt** app and click**Run as administrator** .
3. Enter the following command in the Command Prompt app:  
`Chkdsk C: /f /r`
4. Then press**Enter** .  
![Running Check Disk Scan in Windows Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/running-check-disk-scan-in-windows-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Here,**C:** refers to the drive where your operating system is installed. If your operating system resides on a different drive, change the command accordingly. Also, don't forget to enter the**"/f"** and**"/r"** parameters since these are needed to fix errors, locate bad sectors, and recover corrupted information.

 The CHKDSK scan has the greatest chance of adequately fixing the error under discussion. However, if it doesn't resolve the problem, you can move on to the next solution.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
## 2\. Run the DISM and SFC Scan

 Like CHKDSK, SFC and DISM scans can be used when your system behaves strangely. Initially, you should run the SFC scan because it usually resolves the issue. However, if it fails to diagnose the problem or run, you should run a DISM scan.

 Performing both scans ensures that your device does not have corrupted system files causing the trouble. To run both scans, follow these steps:

1. Open Command Prompt as an administrator.
2. To run the SFC scan, type the following command and press**Enter** :  
`SFC /scannow`
3. To run the DISM scan, type the following command and press**Enter** :  
`DISM /Online /Cleanup-Image /RestoreHealth`

![Run SFC and DISM scans](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/scannow-restorehealth-cmd-1.jpg)
<!-- affiliate ads begin -->
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To better understand the results of these scans, see our [article about the differences between CHKDSK, DISM, and SFC](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) . If the error persists after running the above scans, move on to the next fix.

## 3\. Check for File-Specific Issues

 Next, you should check whether the error occurs for a particular file or all files synced on OneDrive. Attempt to make the exact change that caused the error in a different folder and see if the problem repeats. If the issue is file-specific, it is recommended that you restore the file to its previous version, if possible. Here are the steps you need to follow:

1. Right-click on the file you're experiencing the error with and open**Properties** .
2. Click on the**Previous Versions** tab.
3. Select the previous version, if available.
4. Click the**Restore** button, then click**Apply** and**OK** .  
![Restoring Previous Version of a File in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/windows-restore-previous-file-version.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4708689&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Win： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
## 4\. Remove the Passwords From the Problematic Files

 Has this error occurred after password-protecting a synced file on OneDrive? In this case, you should go to OneDrive, check the history of modified files, and restore the problematic file to a previous version. Our article on [recovering OneDrive files from version history](https://www.makeuseof.com/tag/restore-onedrive-files-version-history/#rolling-back-a-file) explains how to roll back a file. Reset OneDrive if this fix does not solve the problem.

## 5\. Reset OneDrive

 Resetting the app or service is a good troubleshooting step for problems that don't resolve with general fixes. Therefore, if none of the fixes have worked so far, you should reset OneDrive. Remember that resetting OneDrive will not delete your data, but you'll have to set up the sync connection again.

 In our article on [how to fix OneDrive when you can't open the files](https://www.makeuseof.com/ways-fix-onedrive-when-you-cannot-open-your-files/#reset-onedrive) , we have explained how to reset OneDrive. Follow the instructions in the article to reset OneDrive, and hopefully, you will be able to fix the issue. However, if that also fails to work and the error appears periodically, you can delete or relocate the problematic file or folder.

## 6\. Delete or Relocate the Problematic File

 If all else fails, delete or relocate the problematic file. However, before you do that, you need to pause the OneDrive sync and leave it for an hour. Then, access your OneDrive online and remove the synced file from there.

 Once done, you should turn off your device's internet connection and [start Windows 11 in Safe Mode](https://www.makeuseof.com/windows-11-boot-safe-mode/) (or [Windows 10](https://www.makeuseof.com/tag/boot-windows-10-safe-mode/) if you're using an older version). Afterward, navigate to your local drive, where the problematic file is located. Delete it from there and restart your device normally.

 If the file you are experiencing the error with has value to you and you cannot delete it, move it to another computer and delete it from your primary device. Hopefully, relocating or deleting the file will prevent the error from occurring again.

## Keep Annoying OneDrive Errors at Bay

 It can be very frustrating to encounter the "The tag present in the reparse point buffer is invalid" error when making changes to our files. If you apply the fixes in the article, hopefully, you'll be able to fix the error and reaccess your files. If nothing works, you can move it elsewhere and delete it from your primary drive.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>





<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-knowledge.techidaily.com/new-how-to-see-youtube-liked-comments/"><u>[New] How to See YouTube Liked Comments</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-captivating-audience-with-these-innovative-videos-for-2024/"><u>[Updated] Captivating Audience with These Innovative Videos for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-6-ingenious-sites-brimming-with-customizable-youtube-themes/"><u>[Updated] In 2024, 6 Ingenious Sites Brimming With Customizable YouTube Themes</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-insiders-guide-to-captivating-youtube-headlines/"><u>[Updated] The Insider's Guide to Captivating YouTube Headlines</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-unlocking-the-power-of-cross-platform-social-media-with-youtube-and-instagram-stories-for-2024/"><u>[Updated] Unlocking the Power of Cross-Platform Social Media with YouTube & Instagram Stories for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-visionvoice-tips-for-perfectly-sized-insta-posts/"><u>[Updated] VisionVoice  Tips for Perfectly Sized Insta Posts</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-beginners-guide-to-motion-artistry/"><u>2024 Approved  Beginner's Guide to Motion Artistry</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/2024-approved-virtual-masterclass-for-aspiring-filmmakers-on-youtube/"><u>2024 Approved  Virtual Masterclass for Aspiring Filmmakers on YouTube</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-realme-10t-5g-drfone-by-drfone-virtual-android/"><u>9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Realme 10T 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/best-12-youtube-game-openers-a-comparative-guide-no-expense-for-2024/"><u>Best 12 YouTube Game Openers  A Comparative Guide (No Expense) for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-support-issue-in-windows-the-essential-fixes-list/"><u>Bypassing Support Issue in Windows: The Essential Fixes List</u></a></li>
<li><a href="https://windows11.techidaily.com/dynamic-tray-display-live-system-usage-statistics-on-desktop/"><u>Dynamic Tray Display: Live System Usage Statistics on Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-steps-to-disable-amdnvidia-graphics-extras/"><u>Easy Steps to Disable AMD/Nvidia Graphics Extras</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-tips-for-steam-streaming-woes/"><u>Effective Tips for Steam Streaming Woes</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-file-handling-in-windows-powertoys/"><u>Efficient File Handling in Windows PowerToys</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-techniques-for-purging-steams-dns-cache/"><u>Efficient Techniques for Purging Steam's DNS Cache</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-accessing-windows-emergency-tools/"><u>Efficiently Accessing Windows Emergency Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-win-based-open-ai-discussions/"><u>Effortless WIN-Based Open AI Discussions</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-cortana-experience-use-of-vivetool/"><u>Elevate Cortana Experience: Use of ViveTool</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-vm-game-six-key-tips-for-windows-optimization/"><u>Elevate Your VM Game: Six Key Tips for Windows Optimization</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-ui-customization-adding-shortcut-keys-for-wordpad-to-menu-bar/"><u>Elevating UI Customization: Adding Shortcut Keys for Wordpad to Menu Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-blue-screen-due-to-unhandled-win-errors/"><u>Eliminating Blue Screen Due to Unhandled Win Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-non-appearing-screens-on-pc-startup/"><u>Eliminating Non-Appearing Screens on PC Startup</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-the-windows-error-code-0x8007251d-for-activation/"><u>Eliminating the Windows Error Code 0X8007251D for Activation</u></a></li>
<li><a href="https://windows11.techidaily.com/embracing-evenings-learning-paints-dark-mode-features/"><u>Embracing Evenings: Learning Paint's Dark Mode Features</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-live-performance-on-task-monitor-win-11/"><u>Enhance Live Performance on Task Monitor Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-the-real-time-update-speed-of-task-manager/"><u>Enhance the Real-Time Update Speed of Task Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-user-experience-add-portable-software-to-windows/"><u>Enhance User Experience: Add Portable Software to Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-your-workflow-top-5-windows-folder-techniques/"><u>Enhance Your Workflow: Top 5 Windows Folder Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-file-management-on-windows-11-with-new-actions/"><u>Enhancing File Management on Windows 11 with New Actions</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-performance-lowering-edges-resource-load/"><u>Enhancing Performance: Lowering Edge's Resource Load</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-productivity-grouped-software-installs-on-windows-11-using-winstall/"><u>Enhancing Productivity: Grouped Software Installs on Windows 11 Using Winstall</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-storage-management-on-win-1011/"><u>Enhancing Storage Management on Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-cortana-records-are-saved-windows-method/"><u>Ensuring Cortana Records Are Saved: Windows Method</u></a></li>
<li><a href="https://unlock-android.techidaily.com/forgot-pattern-lock-heres-how-you-can-unlock-honor-x50i-pattern-lock-screen-by-drfone-android/"><u>Forgot Pattern Lock? Heres How You Can Unlock Honor X50i Pattern Lock Screen</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/how-to-achieve-slick-sound-segmentation-in-premiere-for-2024/"><u>How to Achieve Slick Sound Segmentation in Premiere for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-send-and-fake-live-location-on-facebook-messenger-of-your-tecno-pova-5-pro-drfone-by-drfone-virtual-android/"><u>How to Send and Fake Live Location on Facebook Messenger Of your Tecno Pova 5 Pro | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-nokia-g22-drfone-by-drfone-virtual/"><u>In 2024, 9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Nokia G22 | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-two-ways-to-track-my-boyfriends-xiaomi-redmi-13c-5g-without-him-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, Two Ways to Track My Boyfriends Xiaomi Redmi 13C 5G without Him Knowing | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-ultimate-top-5-list-ps3-games-on-windows-platforms/"><u>In 2024, Ultimate Top 5 List  PS3 Games on Windows Platforms</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-videos-back-from-honor-x50-by-fonelab-android-recover-video/"><u>Simple ways to get lost videos back from Honor X50</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/sony-s6500-review-latest-improvements/"><u>Sony S6500 Review  Latest Improvements</u></a></li>
<li><a href="https://tech-haven.techidaily.com/talking-bots-face-off-which-one-triumphs-more/"><u>Talking Bots Face-Off: Which One Triumphs More?</u></a></li>
<li><a href="https://techidaily.com/today-i-will-share-your-winning-forex-trades-with-friends-and-family-on-local-trade-copier-tm-together-by-mt4copier-guide/"><u>Today I will Share Your Winning Forex Trades With Friends and Family on Local Trade Copier™ Together</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/top-5-xiaomi-14-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 Xiaomi 14 Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/unblocking-video-sharing-how-to-solve-fb-chat-issues-for-iphonesandroid-for-2024/"><u>Unblocking Video Sharing  How to Solve FB Chat Issues for iPhones/Android for 2024</u></a></li>
</ul></div>
