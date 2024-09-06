---
title: Resetting Error with Windows' Shadow Copy Service
date: 2024-09-05T02:15:05.403Z
updated: 2024-09-06T02:15:05.403Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resetting Error with Windows' Shadow Copy Service
excerpt: This Article Describes Resetting Error with Windows' Shadow Copy Service
keywords: Fix Shadow Copy Failure,Restore Windows Snapshots,Reset Shadow Copy Errors,Revert Error to Shadow Copy,Correcting Snapshot Issues,Resolve Shadow Copy Glitches,Restart Windows Backup Service
thumbnail: https://thmb.techidaily.com/9b6e560f5ae8bf8946a31c995d6c73a4779b962b2219e90738423fb3fbbee898.jpg
---

## Resetting Error with Windows' Shadow Copy Service

 If the Volume Shadow Copy service isn't working, you'll see error messages when you try to use Backup and Restore or System Restore in Windows. We'll show you how you can fix Volume Shadow Copy when it's not working on a Windows PC, so you can get your backups going once more.

## 1\. Enable and Start Volume Shadow Copy Services

 VSS errors can often arise because the Volume Shadow Copy and Microsoft Software Shadow Copy Provider services aren’t enabled or running. For example, many users have confirmed enabling those services can fix VSS error codes 0x81000202 and 0x81000203, which affect the System Restore tool. So, you may be able to resolve numerous Volume Shadow Copy errors by enabling VSS services like this:

1. First, press the **Windows** logo key + **S** and enter a Services search phrase to find that app.
2. Click **Services** inside the search results.
3. Double-click the **Volume Shadow Copy Service**.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/services-window.jpg)
4. Click the drop-down menu labeled **Startup type** and select **Automatic** if the service is set differently.  
![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-type-drop-down-menu.jpg)
5. Press **Start** in the Volume Shadow Copy Service window.
6. Click on the service window’s **Apply** and **OK** buttons to set the changed options.
7. Repeat steps three to six for the Microsoft Software Shadow Copy Provider service.
8. Also, check that the RPC Endpoint Mapper and DCOM Server Process dependency services for Volume Shadow Copy are enabled and running.

 Restart those shadow copy services if they’re already set as required. You can do that by right-clicking on those services and selecting the Restart context menu options for them.

## 2\. Repair Your System Files With the SFC and DISM Commands

 Corrupted system files can affect Windows services, such as Volume Shadow Copy. So, some users may need to repair system files to fix the Volume Shadow Copy Service when it’s not working. You can do that by running System File Checker and Deployment Image Servicing Management scans, as covered in this article about [repairing corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/).

![The sfc scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/sfc-scannow-error.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123731/7443" target="_top" id="2123731">
  <img src="//a.impactradius-go.com/display-ad/7443-2123731" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123731/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Run the Check Disk Utility

 Drive issues can cause Windows system backup VSS errors to occur, with codes like 0x807800A1 or 0x80042315\. In this case, running the Check Disk utility to scan for and address hard drive issues, such as bad sectors, is a potential fix for the Volume Shadow Copy Service not working. Check out this [guide to running the CHKDSK utility](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) for further details about how you can apply this potential resolution.

![The CHKDSK command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/chkdsk-scan-command.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043594/7443" target="_top" id="2043594">
  <img src="//a.impactradius-go.com/display-ad/7443-2043594" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043594/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<span id="1983473">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983473.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983473">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983473.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983473%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983473/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Disable Antivirus Shields

 Sometimes third-party antivirus software can interfere with and prevent Volume Shadow Copy from functioning correctly. So, try disabling third-party antivirus shields before attempting to back up or restore Windows. The usual way to do that is to right-click on an antivirus app’s system tray icon and select a disable/turn off shield protection option from there.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 Don’t leave your antivirus shield permanently disabled. If possible, select to disable it for a few hours before attempting the backup or system restoration operation again. Or manually re-enable your antivirus if you can’t select a temporary option.

<!-- affiliate ads begin -->
<span id="1975562">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975562.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975562">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975562.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975562%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975562/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Disable Any Active Firewalls

 It’s also recommended to disable the firewall component of a third-party antivirus utility before attempting to perform a VSS operation. Turning off an antivirus shield won’t disable a firewall component. Look for firewall settings within your antivirus software’s tabs to see if it includes one. If it does, select to turn off the firewall.

 Try turning off the Windows firewall if you haven’t installed a third-party antivirus utility or firewall software. Check out this guide to [disabling Microsoft Defender Firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) for instructions for turning off that security component.

![The Turn off Windows Defender Firewall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-firewall-settings.jpg)

<!-- affiliate ads begin -->
<span id="1542129">
					<video width="864" height="1152" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1542129.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16836-1542129">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1542129.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2F25home.pxf.io%2Fc%2F5597632%2F1542129%2F16836'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1542129/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Set Windows to Perform a Clean Boot

![The Startup type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-tab.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2112008/7443" target="_top" id="2112008">
  <img src="//a.impactradius-go.com/display-ad/7443-2112008" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2112008/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Conflicting background apps or services are another potential cause of Volume Shadow Copy errors. Third-party backup utilities with snapshot managers are the most likely software packages to conflict with the Volume Shadow Copy Service. If you know you’ve installed a third-party backup manager, uninstalling it could be the best way to ensure it doesn’t cause any conflicts.

 However, you can [perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) to stop third-party apps and services from starting with Windows to prevent conflicts from arising. This involves disabling startup items and services with Task Manager and MSConfig and restarting Windows. Then try utilizing the Windows Backup and Restore or System Restore tools after clean booting your PC to see if the VSS error persists.

 If it does, this means something you disabled during the clean boot is causing the problem. Now you can slowly re-enable each app until the problem reappears, then either uninstall or update the offending app.

## Back up and Restore Windows Again

 These solutions can potentially resolve many variable Volume Shadow Copy Service error messages and codes that pop up during system backup and restore operations. With Volume Shadow Copy fixed, you can back up and restore Windows with built-in system tools again.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-recordings.techidaily.com/new-beginning-the-live-journey-on-instagram-for-2024/"><u>[New] Beginning the Live Journey on Instagram for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-digital-deviation-expert-strategies-to-rotate-videos-on-youtube-for-2024/"><u>[New] Digital Deviation  Expert Strategies to Rotate Videos on YouTube for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-in-2024-the-ultimate-guide-to-stock-photo-memes-and-realities/"><u>[New] In 2024, The Ultimate Guide to Stock Photo Memes & Realities</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-exclusive-movies-behind-the-best-chart/"><u>[Updated] 2024 Approved  Exclusive Movies Behind the Best Chart</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-from-joke-to-jest-constructing-impactful-social-media-memes/"><u>[Updated] In 2024, From Joke to Jest  Constructing Impactful Social Media Memes</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-unraveling-the-mysteries-of-instagrams-video-timeframe/"><u>[Updated] Unraveling the Mysteries of Instagram's Video Timeframe</u></a></li>
<li><a href="https://extra-resources.techidaily.com/a-comprehensible-approach-to-adding-dates-on-youtube-videos/"><u>A Comprehensible Approach to Adding Dates on YouTube Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/establishing-controls-over-insider-build-exposure/"><u>Establishing Controls Over Insider Build Exposure</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-updater-faulty-error-0xca00a009/"><u>Fixing Windows Updater Faulty Error 0xCA00A009</u></a></li>
<li><a href="https://windows11.techidaily.com/get-started-with-hyper-v-windows-11-homes-edition-setup-guide/"><u>Get Started with Hyper-V: Windows 11 Homes Edition Setup Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-halt-default-search-menu-opens-in-win11/"><u>Guide to Halt Default Search Menu Opens in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-0x0000004e-error-in-windows-10-and-11/"><u>How to Fix the 0X0000004E Error in Windows 10 and 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-resolve-the-no-hardware-detected-error-in-windows/"><u>How to Resolve the ‘No Hardware Detected’ Error in Windows</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-easiest-guide-how-to-clone-vivo-y78plus-t1-edition-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Easiest Guide How to Clone Vivo Y78+ (T1) Edition Phone? | Dr.fone</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-exploring-media-top-ranking-camera-apps-for-iphonesandroid-devices/"><u>In 2024, Exploring Media  Top-Ranking Camera Apps for iPhones/Android Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/is-sleep-hibernate-or-shutdown-best-for-your-windows-computer/"><u>Is Sleep, Hibernate, or Shutdown Best for Your Windows Computer?</u></a></li>
<li><a href="https://windows11.techidaily.com/making-store-downloads-functional-again-a-step-by-step-approach/"><u>Making Store Downloads Functional Again: A Step-by-Step Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/managing-overuse-of-system-resources-by-unrealcefsubprocess-on-windows/"><u>Managing Overuse of System Resources by UnrealCEFSubprocess on Windows</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/mastering-webinar-recording-on-a-budget-for-2024/"><u>Mastering Webinar Recording on a Budget for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11-top-7-techniques-to-improve-daily-use/"><u>Mastering Windows 11: Top 7 Techniques to Improve Daily Use</u></a></li>
<li><a href="https://windows11.techidaily.com/mind-body-harmony-meditations-impact-on-brain-and-mood/"><u>Mind-Body Harmony: Meditation's Impact on Brain & Mood</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-through-the-maze-of-windows-temporary-folder-issues/"><u>Navigate Through the Maze of Windows Temporary Folder Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-errors-in-windows-performance-dashboard/"><u>Overcoming Errors in Windows Performance Dashboard</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-failed-disk-readwrites-on-windows/"><u>Overcoming Failed Disk Read/Writes on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/precision-in-file-ordering-with-these-tools/"><u>Precision in File Ordering with These Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-wows-unexpected-shutdown-error-132-on-win11/"><u>Quick Fixes for WoW’s Unexpected Shutdown (Error 132) on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-to-downloading-adobe-reader/"><u>Quick Guide to Downloading Adobe Reader</u></a></li>
<li><a href="https://windows11.techidaily.com/reconfiguring-saving-preferences-for-pubg-on-pc/"><u>Reconfiguring Saving Preferences for PUBG on PC</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-your-pictures-after-edge-2023-has-been-deleted-by-fonelab-android-recover-pictures/"><u>Recover your pictures after Edge 2023 has been deleted.</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-disappearing-windows-during-bootup/"><u>Resolving Disappearing Windows During Bootup</u></a></li>
<li><a href="https://windows11.techidaily.com/restore-control-over-highlighted-text-in-windows-pdf-files/"><u>Restore Control Over Highlighted Text in Windows PDF Files</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-functionality-to-a-malfunctioning-win11-media-player/"><u>Restoring Functionality to a Malfunctioning Win11 Media Player</u></a></li>
<li><a href="https://windows11.techidaily.com/seamlessly-switch-windows-11-walls-to-reflect-each-screens-style/"><u>Seamlessly Switch Windows 11 Walls to Reflect Each Screen's Style</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-a-blissful-experience-with-no-bluescreens-on-win11/"><u>Secure a Blissful Experience with No Bluescreens on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/shelve-the-start-of-edge-windows-11s-solution/"><u>Shelve the Start of Edge: Windows 11'S Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/shop-smoothly-and-swiftly-resolve-windows-store-error-x80072f30/"><u>Shop Smoothly & Swiftly: Resolve Windows Store Error X80072F30</u></a></li>
<li><a href="https://windows11.techidaily.com/simplified-gpo-analysis-via-gpresult-command/"><u>Simplified GPO Analysis via GPResult Command</u></a></li>
<li><a href="https://win-answers.techidaily.com/solving-the-graphics-error-d3d-initialization-flaw-in-grand-theft-auto-v/"><u>Solving the Graphics Error D3D Initialization Flaw in Grand Theft Auto V</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-directly-modifying-windows-installer-controls/"><u>Steps for Directly Modifying Windows Installer Controls</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-fix-failed-display-driver-startup-in-windows-11/"><u>Steps to Fix Failed Display Driver Startup in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-inadequate-access-rights-in-win-1110-errors/"><u>Steps to Resolve Inadequate Access Rights in Win 11/10 Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-strategies-for-enhancing-virtual-memory-on-windows-11-systems/"><u>Tailored Strategies for Enhancing Virtual Memory on Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-overcoming-admin-restrictions-on-setup-errors/"><u>Techniques for Overcoming Admin Restrictions on Setup Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/top-techniques-converting-heic-images-to-jpeg-using-windows-11-capabilities/"><u>Top Techniques: Converting Heic Images to JPEG Using Windows 11 Capabilities</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-your-browser-skills-with-gesture-controls-in-microsoft-edge-windows-11/"><u>Transform Your Browser Skills with Gesture Controls in Microsoft Edge (Windows 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-your-workspace-unveiling-5-advanced-window-folder-methods/"><u>Transform Your Workspace: Unveiling 5 Advanced Window Folder Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/turn-back-time-transforming-windows-11s-search-icon-style/"><u>Turn Back Time: Transforming Windows 11'S Search Icon Style</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-and-fixing-windows-11-search-errors/"><u>Unblocking and Fixing Windows 11 Search Errors</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/understanding-the-concept-of-tagging-a-comprehensive-guide/"><u>Understanding the Concept of Tagging: A Comprehensive Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-powerful-techniques-for-managing-packages-on-windows-11/"><u>Unveiling Powerful Techniques for Managing Packages on Windows 11</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-in-2024-s-best-zero-cost-movie-creation-tools-for-all-skill-levels/"><u>Updated In 2024, S Best Zero-Cost Movie Creation Tools for All Skill Levels</u></a></li>
<li><a href="https://extra-tips.techidaily.com/video-editing-mystery-imovies-automatic-cropping-puzzle/"><u>Video Editing Mystery  IMovie's Automatic Cropping Puzzle</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-users-guide-to-transcribing-with-ais-whisper/"><u>Windows Users Guide to Transcribing with AI's Whisper</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>