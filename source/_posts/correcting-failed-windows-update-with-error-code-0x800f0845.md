---
title: Correcting Failed Windows Update with Error Code 0X800f0845
date: 2024-07-11T22:29:18.017Z
updated: 2024-07-12T22:29:18.017Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting Failed Windows Update with Error Code 0X800f0845
excerpt: This Article Describes Correcting Failed Windows Update with Error Code 0X800f0845
keywords: Windows Update Fix Code 0X800F,Errorexcode800F Windows Repair,Error 0X800F Update Correction,Fix Windows Update Error 0X800F,Resolve 0X800F Update Failure,XP800F Update Fix Strategies,Eliminating Error Code 0X800F
thumbnail: https://thmb.techidaily.com/5b8a360ae2beb8ae28dded746595b2ec0252b7304ad9ab12b451e3ff69d2619e.jpg
---

## Correcting Failed Windows Update with Error Code 0X800f0845

 Windows Update brings new features to your PC while installing important security updates and bug fixes. So it's vital to keep your system updated to work and play hassle-free on Windows.

 However, some unexpected errors occur, resulting in updates failing to install on your system. And 0x800f0845 is one such error.

 But you can get past the 0x800f0845 error and continue to install essential updates by trying the following fixes.

## What Is the Windows Update 0x800f0845 Error?

 0x800f0845 is an error that mostly occurs while installing cumulative updates on your Windows PC. You may experience this update error if Windows components and services are corrupted or if there are damaged or missing system files. Sometimes, this error happens by the interactions of third-party apps with the system apps.

 You may not come to know of the error while updating, as Windows will appear to be updating normally with messages of the updates installing—such as**Updates are underway. Please keep your computer on** .

 However, just before your PC reboots, the following message on your computer screen may appear: **Something didn't go as planned. No need to worry—undoing changes. Please keep your computer on** . This message indicates a problem with the update. When your computer restarts, the cumulative update would have failed to install.

 You can check for the same by going to**Settings > Windows Update** and then clicking**Update history** . In**Update history** , you will get the message that the cumulative update has failed to install with the error code**0x800f0845** like the screenshot below.

![0x800f0845 Error in Windows Update History](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/0x800f0845-error-update-history.jpg)

 So what can you do now? Cumulative updates are quality updates, so these must be installed. Fortunately, as there are ways to get past the 0x800f0845 error and install the failed updates.

## 1\. Run the Windows Update Troubleshooter

 It's always better to try fixing Windows update errors first by using the Windows Update Troubleshooter. It scans your PC for problems, attempts to resolve them, and then applies the fixes.

1. Right-click the**Windows icon** on the taskbar and select**Settings** . Or use the [many ways to open Settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. On the left pane in**Settings** , click**System** . On the**System** page, click**Troubleshoot** on the right pane.
3. In the**Troubleshoot** page, select**Other troubleshooters** .  
![Select Other Trouble-shooters in Troubleshoot Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/troubleshoot-other-trouble-shooters.jpg)
4. Then click**Run** on the**Windows Update** troubleshooter.  
![Run Windows Update Troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-windows-update-troubleshooter.jpg)

 The Windows Update troubleshooter will automatically run its scans to diagnose problems. After troubleshooting completes, you'll get the message that changes have been made to your system and you should try attempting the tasks you were doing earlier.

![Windows Update Troubleshooting Complete Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-update-troubleshooting-complete.jpg)

 So close the troubleshooter and restart your computer. Then try updating Windows again and check if the failed update gets installed.

## 2\. Temporarily Disable Your Antivirus Software

 Sometimes, third-party antivirus installed on your PC may cause problems when you're updating Windows. So try temporarily disabling it and then installing updates.

 Your antivirus may have options to disable it temporarily. Or right-click on the Windows icon on the taskbar and select**Task Manager** .

 In**Task Manager** , click the**Startup** tab and look for your antivirus software. Then, right-click on it and choose**Disable** .

Try updating Windows now and see if the update gets installed.

## 3\. Run the System File Checker and the DISM Tool

 Corrupted Windows system files could also be the cause of the 0x800f0845 error. To scan, repair, and replace such damaged files, run the System File Checker or SFC scan.

 And if the SFC doesn't work properly, and can’t repair your system files, you should run the DISM or Deployment Image Servicing and Management tool. DISM is a command-line tool that can be used to service and repair Windows images, including those used for Windows Recovery and Windows Setup.

 To know how to run the SFC and DSIM, you can explore our guide on [CHKSDK, SFC, and DISM, and how they work](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) .

 These scans will take a few minutes to run. If the 0x800f0845 error was caused by corrupted files, it should have been fixed. So try updating Windows again.

## 4\. Reset Windows Update Components

 Error 0x800f0845 could occur if some Windows Update components have got corrupted. You could reset Windows components to get the Windows update running fine again. Here's how:

[Open Windows Terminal](https://www.makeuseof.com/windows-11-open-windows-terminal/) using one of the many ways. Or type**Windows Terminal** in**Windows Search** . Then, right-click**Windows Terminal** under**Best match** and select**Run as administrator.**

 First, you need to stop the update services. In the Windows Terminal window, type the following four commands one by one, making sure that you press**enter** after each command:

`net stop bits  
net stop wuauserv  
net stop appidsvc  
net stop cryptsvc`

 Then to set up a new SoftwareDistribution folder, you need to rename it. So enter the following command and press**enter** :

`Ren %systemroot%\SoftwareDistribution SoftwareDistribution.old`

 Next, rename the catroot2 folder for Windows to set up a new one. Type the following command and press**enter** :

`Ren %systemroot%\System32\catroot2 catroot2.old`

 Finally, you need to restart the stopped services. Type the following four commands one after the other, while pressing**enter** after each command:

`net start bits  
net start wuauserv  
net start appidsvc  
net start cryptsvc`

 Once you have run all the commands, the update error should have got fixed. Restart your PC and try installing the updates again.

## 5\. Install the Update Manually via the Microsoft Update Catalog

 What if none of the above solutions works for you? No worries, just install the update manually from the Microsoft Update Catalog.

1. Open your browser to search for and visit the [Microsoft Update Catalog website](https://www.catalog.update.microsoft.com/Home.aspx) .
2. Copy the number of the cumulative update or any other update that failed to install from the**Windows Update history** page. Type the update number in the**Search bar** on the**Microsoft Update Catalog** page and hit the**Search** button.  
![Search For Update On Microsoft Update Catalog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/search-on-microsoft-update-catalog.jpg)
3. The matching updates will show up on the results page. Check the update that applies to your Windows PC—whether it is for Windows 10 or 11, and whether it is for an ARM64-based system or an x64-based system.  
![Microsoft Update Catalog Search Results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/microsoft-update-catalog-search-results.jpg)
4. To know the build of your PC, search for**About** in**Windows Search** and click on**About your PC** under**Best match** . In the**About** page, under**Device specifications** , check your**System type** to know whether it is x64-based or another.  
![Device Specifications in About Your PC Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/screenshot-10065.jpg)  
 Select the update that matches your system in Microsoft Update Catalog and click the**Download** button.
5. The**Download** page will open with the file download link. Click on the link to download the update.  
![Download Update From Microsoft Update Catalog Link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/download-update-from-link.jpg)
6. Double-click on the downloaded file to open the**Windows Update Standalone Installer** and click**Yes** when prompted to download the update.  
![Windows Update Standalone Installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-update-standalone-installer.jpg)  
 The update will begin installing and this could take some time.  
![Cumulative Update Installation in Progress](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/cumulative-update-installing-progress.jpg)  
 Finally, the**Installation complete** window will appear.  
![Click Restart Now to Complete Installation](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/restart-now-to-complete-installation.jpg)
7. Just click the**Restart Now** button to complete the installation.
8. After your PC restarts, go to the**Windows Update history** page.  
![Cumulative Update Successfully Installed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/cumulative-update-successfully-installed.jpg)  
 The update that failed to install would have been successfully installed—as you can see in the screenshot above, the KB5023706 update was installed.

## Stay Updated for a Secure and Smooth Windows Experience

 Update errors like 0x800fo845 can be annoying, especially when you've spent considerable time on an update that fails to install. Try the fixes discussed above to install important updates and enjoy a smooth, secure, and hassle-free Windows experience.


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
<li><a href="https://youtube-videos.techidaily.com/enhancing-user-experience-a-quick-how-to-for-youtube-cc-and-subtitles/"><u>Enhancing User Experience  A Quick How-To for YouTube CC & Subtitles</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-leading-gloves-transforming-vr-playtime/"><u>[Updated] Leading Gloves Transforming VR Playtime</u></a></li>
<li><a href="https://windows11.techidaily.com/delving-into-disparities-unveiling-the-distinctive-aspects-of-each-login-type/"><u>Delving Into Disparities: Unveiling The Distinctive Aspects of Each Login Type</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-the-meaning-behind-windows-folders-x-marks/"><u>Demystifying: The Meaning Behind Windows' Folders X-Marks</u></a></li>
<li><a href="https://windows11.techidaily.com/confirm-if-your-system-is-a-win11-recipe/"><u>Confirm if Your System Is a Win11 Recipe</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-in-2024-how-to-transcribe-speech-to-text-in-microsoft-word-learn-it-here/"><u>[Updated] In 2024, How to Transcribe Speech to Text in Microsoft Word Learn It Here</u></a></li>
<li><a href="https://windows11.techidaily.com/coordinating-connections-dual-net-usage-on-a-single-windows-pc/"><u>Coordinating Connections: Dual Net Usage on a Single Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/clear-sighted-making-your-windows-11-taskbar-glossy/"><u>Clear-Sighted: Making Your Windows 11 Taskbar Glossy</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-windows-11-parental-restrictions-guide/"><u>Configuring Windows 11 Parental Restrictions Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/clear-up-windows-icon-layout-confusion/"><u>Clear Up Window's Icon Layout Confusion</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-down-the-memory-usage-of-your-security-app/"><u>Cutting Down the Memory Usage of Your Security App</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-mastering-sleep-optimal-asmr-experiences-and-picks/"><u>2024 Approved  Mastering Sleep  Optimal ASMR Experiences & Picks</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-navigating-the-top-android-collage-app-landscape/"><u>[New] Navigating the Top Android Collage App Landscape</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-top-5-free-video-compression-apps-for-iphone-and-ipad/"><u>New 2024 Approved Top 5 Free Video Compression Apps for iPhone and iPad</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-windows-11-notifications-to-exclude-extras/"><u>Customize Windows 11 Notifications to Exclude Extras</u></a></li>
<li><a href="https://windows11.techidaily.com/dive-into-windows-powertoys-the-ultimate-guide-to-its-best-uses/"><u>Dive Into Windows PowerToys: The Ultimate Guide to Its Best Uses</u></a></li>
<li><a href="https://windows11.techidaily.com/defeating-inadequate-pcs-fixing-game-bar-errors/"><u>Defeating Inadequate PCs: Fixing Game Bar Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-windows-11s-obstacle-overcoming-error-code-22/"><u>Clearing Windows 11'S Obstacle: Overcoming Error Code 22</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-immediate-failure-effective-strategies-to-tackle-onedrive-folder-issues-on-pc/"><u>Conquering Immediate Failure: Effective Strategies to Tackle OneDrive Folder Issues on PC</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/top-10-talking-photo-online-tools-you-have-to-try/"><u>Top 10 Talking Photo Online Tools You Have To Try</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-streamlining-video-playback-with-safaris-pip/"><u>2024 Approved  Streamlining Video Playback with Safari's PIP</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-unilateral-audio-issue-on-win-os-headphones/"><u>Correcting Unilateral Audio Issue on WIN OS Headphones</u></a></li>
<li><a href="https://windows11.techidaily.com/curbing-high-cpu-utilization-by-tiworkerexe-programs/"><u>Curbing High CPU Utilization by TiWorker.exe Programs</u></a></li>
<li><a href="https://windows11.techidaily.com/converting-heic-photos-to-jpeg-on-windows-1011/"><u>Converting HEIC Photos to JPEG on Windows 10/11</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-download-premium-video-covers-free-fast-and-easy/"><u>[New] 2024 Approved  Download Premium Video Covers - Free, Fast & Easy</u></a></li>
<li><a href="https://extra-information.techidaily.com/artistic-awareness-accelerate-editing-in-the-photos-app-win10-style/"><u>Artistic Awareness  Accelerate Editing in the Photos App, WIN10 Style</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-additional-tips-about-sinnoh-stone-for-vivo-x-fold-2-drfone-by-drfone-virtual-android/"><u>In 2024, Additional Tips About Sinnoh Stone For Vivo X Fold 2 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-windows-startup-journey/"><u>Decoding the Windows Startup Journey</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-from-basic-to-breathtaking-elevate-your-tiktok-videos-today/"><u>[New] In 2024, From Basic to Breathtaking  Elevate Your TikTok Videos Today</u></a></li>
<li><a href="https://windows11.techidaily.com/detecting-correct-credentials-vs-error-logins-on-your-winpc/"><u>Detecting Correct Credentials vs Error Logins on Your WinPC</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/metaverse-laughs-crafting-funny-virtual-memes-for-2024/"><u>Metaverse Laughs  Crafting Funny Virtual Memes for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-rhythm-and-flow-explore-easy-trending-tiktok-moves/"><u>[Updated] Rhythm & Flow  Explore Easy, Trending TikTok Moves</u></a></li>
<li><a href="https://windows11.techidaily.com/1720600438278-windowsstellar-data-recovery/"><u>「Windowsで失われたファイルを取り戻せる無料ソフトStellar Data Recovery」</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-minimummax-cpu-in-power-preferences/"><u>Deciphering Minimum/Max CPU in Power Preferences</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-windows-11-a-guide-to-a-unique-environment/"><u>Customizing Windows 11: A Guide to a Unique Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/controlling-application-spaces-in-windows-task-mgr/"><u>Controlling Application Spaces in Windows Task Mgr</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-webp-image-save-in-google-chrome-windows-edition/"><u>Disabling WebP Image Save in Google Chrome, Windows Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/direct-routes-to-windows-11s-system32/"><u>Direct Routes to Windows 11'S System32</u></a></li>
<li><a href="https://windows11.techidaily.com/cross-language-build-system-setup/"><u>Cross-Language Build System Setup</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-crafting-engaging-content-with-added-vocal-dimensions-in-tiktok-videos/"><u>[Updated] 2024 Approved  Crafting Engaging Content with Added Vocal Dimensions in TikTok Videos</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-elevate-your-video-editing-a-comprehensive-guide-to-using-the-ken-burns-effect-in-final-cut-pro/"><u>New 2024 Approved Elevate Your Video Editing A Comprehensive Guide to Using the Ken Burns Effect in Final Cut Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-correcting-installer-messages-on-pcs/"><u>Decoding and Correcting Installer Messages on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-shortcuts-a-guide-for-winos-users/"><u>Crafting Shortcuts: A Guide for WinOS Users</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-top-free-video-editors-for-newbies/"><u>Updated Top Free Video Editors for Newbies</u></a></li>
<li><a href="https://windows11.techidaily.com/cure-the-save-issue-in-microsoft-oses/"><u>Cure the Save Issue in Microsoft OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/compact-pc-capacity-concealed-by-slowness/"><u>Compact PC, Capacity Concealed by Slowness</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-show-wi-fi-password-on-vivo-y56-5g-by-drfone-android/"><u>How to Show Wi-Fi Password on Vivo Y56 5G</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-premier-5-film-scraper-apps/"><u>2024 Approved  Premier 5 Film Scraper Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/control-your-machines-invisible-operations-on-window-11/"><u>Control Your Machine's Invisible Operations on Window 11</u></a></li>
<li><a href="https://windows11.techidaily.com/control-over-edges-ongoing-tasks-in-win11-environment/"><u>Control Over Edge's Ongoing Tasks in Win11 Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-the-windows-device-abandonment-issue/"><u>Correcting the Windows Device Abandonment Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/clean-slate-optimizing-windowed-file-space/"><u>Clean Slate: Optimizing Windowed File Space</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-the-clutter-fixing-windows-error-0x80072014/"><u>Clearing the Clutter: Fixing Windows Error 0X80072014</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-unveiling-the-secrets-of-instagrams-musical-emoji-usage/"><u>[New] 2024 Approved  Unveiling the Secrets of Instagram's Musical Emoji Usage</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-and-disabling-read-only-properties-in-win11/"><u>Deciphering and Disabling Read-Only Properties in Win11</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-realme-11-5g-by-drfone-android/"><u>In 2024, AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Realme 11 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-high-cpu-demands-the-case-for-vanguards-ums-optimization/"><u>Deciphering High CPU Demands: The Case for Vanguard's UMS Optimization</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-common-errors-in-windows-onedrive/"><u>Correcting Common Errors in Windows' OneDrive</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-gray-out-issue-with-volume-extend-in-win/"><u>Correcting Gray Out Issue with Volume Extend in Win</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-how-to-fake-gps-on-android-without-mock-location-for-your-realme-c53-drfone-by-drfone-virtual/"><u>In 2024, How to Fake GPS on Android without Mock Location For your Realme C53 | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-comedy-codex-choosing-your-meme-companion/"><u>The Comedy Codex  Choosing Your Meme Companion</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-the-ultimate-12-portable-camera-reviews-for-dynamic-vlogging/"><u>[New] The Ultimate 12 Portable Camera Reviews  For Dynamic Vlogging</u></a></li>
</ul></div>
