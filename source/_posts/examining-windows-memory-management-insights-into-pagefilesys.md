---
title: "Examining Windows' Memory Management: Insights Into Pagefile.sys"
date: 2024-09-09T11:58:17.573Z
updated: 2024-09-10T11:58:17.573Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Examining Windows' Memory Management: Insights Into Pagefile.sys"
excerpt: "This Article Describes Examining Windows' Memory Management: Insights Into Pagefile.sys"
keywords: MemManageWindows,WindowsMemoryInsight,PagefileSysAnalysis,MemoryFileSystemWin,SystemPageFileExamine,WinMemoryOptimization,SysDumpPageFileStudy
thumbnail: https://thmb.techidaily.com/4f0baa4676690f713a7c64c49fa175c4aff67762b3efda1ae17d3bfe6d387995.jpg
---

## Examining Windows' Memory Management: Insights Into Pagefile.sys

 When your Windows computer is running out of storage space, you may find yourself looking for ways to free up some of it, even if they're a bit unconventional. One of these unconventional methods you may come across is deleting the Pagefile.sys file. But before you consider deleting it, you should know what Pagefile.sys is and if you should delete it in the first place.

Here's what you need to know.

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098705/14409" target="_top" id="2098705">
  <img src="//a.impactradius-go.com/display-ad/14409-2098705" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098705/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What Is Pagefile.sys?

 Pagefile.sys is a system file in Windows set aside for your computer’s[Random Access Memory (RAM)](https://www.makeuseof.com/tag/quick-dirty-guide-ram-need-know/) , also known as physical memory. When your computer's RAM begins to run out of memory, it uses the pagefile to offload data it doesn't need, such as files and apps.

 So how does your computer’s RAM decide when to offload data? Let’s use an app as an example of how this works.

 Usually, when you minimize an app, Windows will leave it running in the background. However, it will keep its data in the RAM so it can quickly access them when needed.

 Then, when you boot up a RAM-intensive app, Windows needs to make room for it within the RAM. As such, Windows will instruct your PC’s RAM to dump the minimized app’s program files into Pagefile.sys, so it can free up memory without losing data.

 By default, Windows will store Pagefile.sys in the root folder of your local drive (C:).

 When you need to use the minimized app again, Windows will read its data from the Pagefile.sys file. And you'll be none the wiser that it's compensating for its physical memory shortcomings with the help of your local drive.

 Reading an app’s program files from Pagefile.sys is slower than reading them from RAM. The process is even slower when you're using a hard disk drive (HDD)[instead of a solid-state drive (SDD)](https://www.makeuseof.com/choose-ssd-or-hdd-storage/) . However, It’s faster than closing the app and then relaunching it.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123734/7443" target="_top" id="2123734">
  <img src="//a.impactradius-go.com/display-ad/7443-2123734" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123734/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Check the Size of Pagefile.sys

 To prevent tampering with Pagefile.sys, Windows will hide it by default. If you want to see it, here’s what you should do.

1. Press**Win + E** to open File Explorer.
2. Click on**This PC** in the navigation pane on the left and double-click your**local drive (C:)** on the right to open it.
3. Now you need to open Folder Options. On Windows 11, click the**three vertical dots** in the top menu and select**Options** . On Windows 10, click**View** in the top menu and then on**Options** .  
![selecting options in the top menu of file explorer in windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/file-explorer-options.jpg)
4. Select the**View** tab in Folder Options and uncheck**Hide protected operating system files (Recommended)** .  
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134235/18498" target="_top" id="2134235">
  <img src="//a.impactradius-go.com/display-ad/18498-2134235" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134235/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The unhide protected os files option in folder options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/folder-options-unhide-protected-os-files.jpg)
5. In the warning that pops up, click**Yes** .
6. A bit further up, you see**Hidden files and folders** . Inside it, check the**Show hidden files, folders, and drives** radio button.
7. Click**OK** to close Folder Options and apply the changes.
8. Scroll down in your local drive, and you’ll be able to see Pagefile.sys.  
![the pagefile.sys file in the root folder of the local drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/pagefile-sys-file.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137216/26400" target="_top" id="2137216">
  <img src="//a.impactradius-go.com/display-ad/26400-2137216" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137216/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 As you can see, the Pagefile.sys file is quite large, which makes many people think deleting it is a good idea when they're running out of storage space.

## Should You Delete Pagefile.sys?

 One scenario where it would be reasonable to delete Pagefile.sys to save disk space is if you have a lot of RAM. That way, it can store all the data it needs to keep apps running without needing to offload them. For the average Windows user, the minimum RAM size for this would be 16GB.

 If you delete Pagefile.sys and your computer runs out of physical memory, your system will start to become sluggish. If the sluggishness gets too bad, Windows itself might even crash.

 Also, you might notice some apps becoming slower or crashing as well. That’s because they have nowhere to put the data they need to operate properly since your computer’s RAM is full and there is no Pagefile.sys to pick up the slack.

 So unless your physical memory needs aren’t greater than your installed RAM’s capacity, we recommend leaving Pagefile.sys alone.

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134503/19576" target="_top" id="2134503">
  <img src="//a.impactradius-go.com/display-ad/19576-2134503" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134503/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Delete Pagefile.sys

 Since Windows is constantly using Pagefile.sys, it will not allow you to delete it in File Explorer directly. In fact, if you selected the file and hit the**Delete** key, you will see the following message: "The action can't be completed because the file is open in another program."

![deleting-pagefile-error](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/deleting-pagefile-error.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118326/7443" target="_top" id="2118326">
  <img src="//a.impactradius-go.com/display-ad/7443-2118326" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118326/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 However, there’s another method you can use to delete the file and save some disk space. To do that, follow the steps below.

1. Press**Win + S** to open Windows Search.
2. Type**sysdm.cpl** in the search box and hit the**Enter** key to open the System Properties window.  
![searching for sysdm.cpl in windows search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/windows-search-sysdm-cpl.jpg)
3. Select the**Advanced** tab, and in the**Performance** section, click the**Settings** button.  
![the system properties dialog box in windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/system-properties-advanced.jpg)
4. In the Performance Options window, select the**Advanced** tab and click**Change** .  
![the Perfomance Options window on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/performance-options-advanced.jpg)
5. In the Virtual Memory window, uncheck the**Automatically manage paging file size for all drives** checkbox at the top.
6. Click on the radio button for**No paging file** , and click the**Set** button on the right.  
![the Virtual Memory window on Windows with the No paging radio button ticked](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/set-no-paging-windows.jpg)
7. You’ll get a warning from Windows. Click**Yes** to bypass it.
<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137976/21526" target="_top" id="2137976">
  <img src="//a.impactradius-go.com/display-ad/21526-2137976" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137976/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. Click on**OK** to close the Virtual Memory window and apply the changes.
9. Restart your Windows computer for the changes to take effect.

 When Windows boots back up, the OS will have no use for Pagefile.sys, and it will delete it from your local drive. It will also delete the Swapfile.sys along with it. If you don't know what that file is and its importance, please read our guide on[what Swapfile.sys is and if you can delete it](https://www.makeuseof.com/windows-swapfile-sys-guide/) .

## How to Restore Pagefile.sys

 If you deleted Pagefile.sys and discovered that you're experiencing problems because of it, you can easily restore it. However, if the problems are so severe that Windows is constantly freezing or can't even boot up properly, you should try entering Safe Mode first. To do that, please check out guides on[ways to boot into Safe Mode on Windows 11](https://www.makeuseof.com/windows-11-boot-safe-mode/) and[what is Safe Mode on Windows 10](https://www.makeuseof.com/windows-11-boot-safe-mode/) .

Now, to bring back Pagefile.sys, follow the steps below:

1. Press**Win + R** to open Windows Run.
2. In the text box, enter**sysdm.cpl** and then hit the**Enter** key to launch the System Properties window.  
![opening the System Properties window using Windows Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/open-system-properties-windows-run.jpg)
3. Select the**Advanced** tab, and in the**Performance** section, click the**Settings** button.
<!-- affiliate ads begin -->
<span id="1155462">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1155462.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1155462">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1155462.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1155462%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1155462/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. In the Performance Options window, select the**Advanced** tab and click**Change** .
5. In the Virtual Memory window, make sure the**Automatically manage paging file size for all drives** checkbox at the top is checked.
6. Click on**OK** to close the Virtual Memory window and apply the changes.
7. Restart your Windows computer for the changes to take effect.

 Once your computer boots up, and you go to the folder where Pagefile.sys is located, you will see that the file has returned, along with Swapfile.sys.

## How to Resize Pagefile.sys

 If deleting Pagefile.sys isn’t an option for you, consider resizing it instead. Here’s how to do that:

1. Press**Win + E** to open File Explorer.
2. In the Navigation Pane, right-click**This PC** and select**Properties** . On Windows 11, you will have to select**Show more options** first before you can see the**Properties** option.
3. Click on the**Advanced system settings** link to open the System Properties window. On Windows 11, you will find the link on the right panel, while, on Windows 10, it will be on the left side menu.  
![the About page of the System window in the Settings app on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/system-about-windows-11.jpg)
4. Select the**Advanced** tab, and in the**Performance** section, click the**Settings** button.
5. In the Performance Options window, select the**Advanced** tab and click**Change** .
6. In the Virtual Memory window, uncheck the**Automatically manage paging file size for all drives** checkbox at the top.
7. Click on the radio button for**Custom size** . Immediately, you’ll see that the two text boxes below it (**Initial size** and**Maximum size**) are no longer grayed out.
8. Enter the appropriate page file sizes in megabytes (MB) in both text boxes and then click**Set** .  
![the virtual memory dialog box on windows with the custom page file size set to 4096](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/virtual-memory-custom-size.jpg)
9. Click**OK** to close the Virtual Memory window and apply the changes.
<!-- affiliate ads begin -->
<span id="1938136">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1938136.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1938136">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1938136.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1938136%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1938136/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
10. Restart your Windows computer for the changes to take effect.

## Pagefile.sys, Demystified

 Pagefile.sys is an extremely important file when it comes to keeping your Windows computer running smoothly. It helps give your PC's RAM more breathing room when physical memory can no longer hold more data. You can delete it, but only do so when you know your computer's RAM has enough capacity to stand on its own. If not, you’re better off just resizing Pagefile.sys so it doesn’t take up too much space.

 If you’re unsure of what to do with Pagefile.sys, just leave it to Windows to handle the file and look for other ways to free up space on your storage drive.

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
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-faceless-watchers-of-fb-flashbacks/"><u>[New] 2024 Approved  Faceless Watchers of Fb Flashbacks</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-iphones-guide-to-spherical-videos-on-facebook-platform/"><u>[New] 2024 Approved  IPhone's Guide to Spherical Videos on Facebook Platform</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-fundamentals-of-copywriting-for-engaging-fb-campaigns/"><u>[New] In 2024, Fundamentals of Copywriting for Engaging FB Campaigns</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-top-picks-the-most-advanced-online-mic-recorders-of-23/"><u>[Updated] 2024 Approved  Top Picks  The Most Advanced Online Mic Recorders of '23</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-investigating-why-specific-youtube-remarks-get-prominence/"><u>[Updated] Investigating Why Specific YouTube Remarks Get Prominence</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-unlock-instagram-broadcast-potential-through-obs-tutorials/"><u>[Updated] Unlock Instagram Broadcast Potential Through OBS Tutorials</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-mastering-the-art-of-setting-up-and-evaluating-facebooks-in-stream-ads/"><u>2024 Approved  Mastering the Art of Setting Up & Evaluating Facebook's In-Stream Ads</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-locked-for-security-reasons-on-iphone-6-find-the-best-solution-here-by-drfone-ios/"><u>Apple ID Locked for Security Reasons On iPhone 6? Find the Best Solution Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/averting-common-issues-with-deskanywhere-windows-11/"><u>Averting Common Issues with DeskAnywhere Windows 11</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/best-tools-for-live-gameplay-screen-grabs/"><u>Best Tools for Live Gameplay Screen Grabs</u></a></li>
<li><a href="https://windows11.techidaily.com/getting-started-with-arm-technology-an-unboxing-and-review-of-the-dell-inspiron-14-plus-7441/"><u>Getting Started with ARM Technology: An Unboxing and Review of the Dell Inspiron 14 Plus (7441)</u></a></li>
<li><a href="https://windows11.techidaily.com/how-cybercriminals-exploit-windows-updates-to-bypass-security-fixes/"><u>How Cybercriminals Exploit Windows Updates to Bypass Security Fixes</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-the-soft-bricked-honor-play-7t-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix the Soft Bricked Honor Play 7T? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-windows-booting-issues-a-step-by-step-guide/"><u>How to Fix Windows Booting Issues: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-turn-your-android-device-into-a-windows-11-camera-a-step-by-step-guide/"><u>How to Turn Your Android Device Into a Windows 11 Camera: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/is-windows-11-update-24h2-compatible-with-your-system-detailed-insights/"><u>Is Windows 11 Update 24H2 Compatible with Your System? Detailed Insights</u></a></li>
<li><a href="https://windows11.techidaily.com/latest-security-features-in-version-127-of-google-chrome-enhanced-malware-defense/"><u>Latest Security Features in Version 127 of Google Chrome: Enhanced Malware Defense</u></a></li>
<li><a href="https://windows11.techidaily.com/local-backup-mastery-unveiling-the-charm-and-reliability-of-in-house-data-replicas/"><u>Local Backup Mastery: Unveiling the Charm and Reliability of In-House Data Replicas</u></a></li>
<li><a href="https://youtube-help.techidaily.com/loves-cinematic-journey-youtube-and-vimeos-top-premium-marriage-videos-for-2024/"><u>Love's Cinematic Journey  YouTube & Vimeo's Top Premium Marriage Videos for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-control-a-step-by-step-tutorial-for-blocking-microsoft-marketing-features-in-windows-11/"><u>Master the Control: A Step-by-Step Tutorial for Blocking Microsoft Marketing Features in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/microsoft-disk-operating-system-version-40-1988-available-for-free/"><u>Microsoft Disk Operating System, Version 4.0 (1988) Available for Free</u></a></li>
<li><a href="https://windows11.techidaily.com/microsoft-launches-advanced-ai-driven-search-tool-comprehensive-guide-and-recall-details/"><u>Microsoft Launches Advanced AI-Driven Search Tool: Comprehensive Guide and Recall Details</u></a></li>
<li><a href="https://windows11.techidaily.com/my-top-pick-the-understated-notepad-application-for-windows-users/"><u>My Top Pick: The Understated Notepad Application for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/nvidias-leap-into-the-future-my-5-anticipated-benefits-of-their-innovative-arm-chip/"><u>NVIDIA's Leap Into the Future: My 5 Anticipated Benefits of Their Innovative ARM Chip</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/prime-9-options-to-capture-high-quality-audio-remotely-23-for-2024/"><u>Prime 9 Options to Capture High-Quality Audio Remotely ('23) for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-file-explorer-from-windows-10-on-your-new-windows-11-pc/"><u>Reviving File Explorer From Windows 10 on Your New Windows 11 PC</u></a></li>
<li><a href="https://win-able.techidaily.com/solving-the-0x803f8001-issue-fixes-for-minecraft-launcher-on-windows-11-and-10/"><u>Solving the 0X803F8001 Issue: Fixes for Minecraft Launcher on Windows 11 and 10</u></a></li>
<li><a href="https://extra-information.techidaily.com/speedy-windowed-image-viewer/"><u>Speedy Windowed Image Viewer</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-correcting-your-laptopmonitor-displays-persistent-yellow-discoloration/"><u>Step-by-Step Guide: Correcting Your Laptop/Monitor Display's Persistent Yellow Discoloration</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-tutorial-for-restoring-functionality-of-a-nonworking-wireless-mouse-on-windows-11-systems/"><u>Step-by-Step Tutorial for Restoring Functionality of a Nonworking Wireless Mouse on Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-tutorial-how-to-extract-music-from-cds-using-windows-software/"><u>Step-by-Step Tutorial: How to Extract Music From CDs Using Windows Software</u></a></li>
<li><a href="https://windows11.techidaily.com/the-creative-process-behind-developing-the-famous-3d-pipes-windows-screensaver/"><u>The Creative Process Behind Developing the Famous 3D Pipes Window's Screensaver</u></a></li>
<li><a href="https://windows11.techidaily.com/the-enduring-legacy-of-windows-xp-why-theres-no-successor/"><u>The Enduring Legacy of Windows XP - Why There's No Successor</u></a></li>
<li><a href="https://windows11.techidaily.com/the-latest-addition-to-the-lineup-meet-the-online-only-microsoft-surface-laptop-alice-what-is-the-term-used-for-any-form-of-energy-that-relates-to-motion/"><u>The Latest Addition to the Lineup: Meet the Online-Only Microsoft Surface Laptop # Alice: What Is the Term Used for Any Form of Energy that Relates to Motion?</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-zte-axon-40-lite-drfone-by-drfone-virtual-android/"><u>The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On ZTE Axon 40 Lite | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-opening-the-microsoft-store-after-unexpected-crashes/"><u>Troubleshooting Tips - Opening the Microsoft Store After Unexpected Crashes</u></a></li>
</ul></div>
