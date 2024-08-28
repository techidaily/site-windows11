---
title: "Tackling Windows Update Failures: Error X712"
date: 2024-08-27T16:13:21.179Z
updated: 2024-08-28T16:13:21.179Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Tackling Windows Update Failures: Error X712"
excerpt: "This Article Describes Tackling Windows Update Failures: Error X712"
keywords: Fixing Windows Updates,Windows X712 Issue Guide,Troubleshooting Windows ErrX712,Resolve Windows Update Error,X712 Windows Failure Tips,Overcoming Windows XP712 Problems,X712 Fix for Windows Updates
thumbnail: https://thmb.techidaily.com/9fa9e4346708270d82530e01172580b66a8c63e17b3edbe0866986af1acde6f2.jpg
---

## Tackling Windows Update Failures: Error X712

 Microsoft frequently releases updates to fix security issues, and introduce new features and stability to the Windows OS. But not all updates install smoothly on your system and trigger an error code while doing so. Many users share their woes with the 0x80073712 update error code with the error message that some files are missing from the system.

 If you experience the same update error code and are unable to install the latest Windows update, don’t worry. We will list out all the possible fixes that you can try to resolve the 0x80073712 error code.

## 1\. Use the Windows Troubleshooter

 Before jumping onto major fixes, leverage the in-built troubleshooter on Windows 10 and 11\. It tries to find out existing problems with Windows Update and try to fix them. Repeat the following steps:

1. Press**Win + I** to launch the settings app.
2. Navigate to the**System > Troubleshoot** section.
3. Click on the**Other Troubleshooter** option.
4. Locate the**Windows Update troubleshooter** option from the list.
5. Then, click on the**Run** button to start the troubleshooter.  
![Windows Update Troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-update-troubleshooter.jpg)
6. Wait for the Windows Update troubleshooter to identify problems. Click on the**Next** button.
7. Close the troubleshooter window and reattempt the Windows update installation.

## 2\. Perform a Complete system shutdown

 Windows OS enables the fast startup option by default. Even if you restart your system, or shut it down, it preserves the system state using hibernate. So, you need to perform a complete system shutdown and then power it back on to close and restart all background services.

Here’s how to perform a complete system shutdown:

1. Press**Win + X** to launch the Power user menu. Scroll down and select the**Terminal (Admin)** option from the list.
2. The Terminal app will open with an instance of a command prompt with admin privileges.
3. Type the**shutdown /s /f /t 0** command and press the**enter** key.
4. Your system will power off. It will take a tad bit longer that a normal shutdown procedure.
5. Now, restart your Windows PC and try to install the Windows update.

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1896607/21553" target="_top" id="1896607"><img src="//a.impactradius-go.com/display-ad/21553-1896607" border="0" alt="" width="750" height="422"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1896607/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Restart Windows Update services

 Windows Update uses a bunch of background services to fetch and download updates. If these services aren’t running automatically, you will encounter an error. These include**Windows Update Service** ,**Windows Installer Service** ,**Cryptographic Services** , and**Background Intelligent Transfer Service** .

Repeat the following steps to start the necessary services:

1. Press**Win + R** to[launch the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**services.msc** and press the**enter** key
2. Services utility will launch on your system. Now locate the**Background Intelligent Transfer** service in the list.
3. Double-click on the BITS service to open the**properties** window. Set the**Startup Type** as**Automatic** and click on the**Apply** button.  
![Disabling Windows Update Services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/disabling-windows-update-services.jpg)
4. Click on the**OK** button and close the Properties windows. Now, right-click on the service and select the**Start** option from the context menu.
5. Similarly, set all the services as automatic and manually start them.
6. **Close** the Services window and reattempt the Windows update.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
<!-- affiliate ads end -->
## 4\. Run the Disk Cleanup Tool

 Disk Cleanup can wipe the delivery optimization files, old Windows update files as well as the Temp folder. If files in these locations are corrupted, they can interfere with the normal update process. Here’s how to run disk cleanup on Windows:

1. Press**Win + S** to open the search utility in Windows.
2. Type**cleanmgr.exe** and press the enter key to open the Disk Cleanup tool.
3. It will select the system drive (C) by default. Click on the**OK** button to continue.
4. Select the checkboxes of files that you want the tool to clean up. Then, click on the**Clean up system files** button.  
![Disk Cleanup App in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/disk-cleanup-app-in-windows-11.jpg)
5. Disk Cleanup will close and redirect you to pick the appropriate drive. Click on the**OK** button.
6. Lastly, click on the**Delete files** button.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->
## 5\. Rename the SoftwareDistribution Folder

 Windows update stores its content in the SoftwareDistribution folder. Since it is located inside the Windows folder in the C drive, you mustn’t delete it. Instead, you can rename the folder to force the update service to recreate the folder again.

Repeat the following steps:

1. Open the Start menu and search CMD. Press Ctrl + Shift + Enter to open the command prompt with admin privileges.
2. Type the following commands to stop all the Windows update-related services:  
 net stop wuauserv net stop cryptSvc net stop bits net stop msiserver  
![Rename the SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/rename-the-softwaredistribution-folder.jpg)
3. Once these services stop running, type**cls** in the command prompt windows. Then enter the following commands:  
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
 ren C:\\Windows\\SoftwareDistribution SoftwareDistribution.old ren C:\\Windows\\System32\\catroot2 Catroot2.old  
![Rename the SoftwareDistribution Folder 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/rename-the-softwaredistribution-folder-2.jpg)
4. Both the above commands rename the**SoftwareDistribution** folder and**Catroot2** folder.
5. Now, you need to restart all the Windows services you stopped in step 3\. Enter the following commands:  
net start wuauserv net start cryptSvc net start bits net start msiserver  
![Rename the SoftwareDistribution Folder 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/rename-the-softwaredistribution-folder-3.jpg)
6. Lastly,**restart** your system and visit the following folder location:**C:\\Windows** . You will notice that there is a new SoftwareDistribution folder in that location.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
7. Open the Windows update in Settings and try to download and install updates.

## 6\. Delete the Pending.xml file

 The pending.xml file contains all the pending Windows update tasks. Oftentimes, it can interfere with installing new updates because there are already multiple incomplete old update tasks. So, you must delete this file and proceed with the Windows update.

Retrace the following steps to delete the pending.xml file:

1. Log in with an administrator account. Then, press**Win + E** to launch the file explorer.
2. Navigate to the**C:\\Windows\\WinSxS** folder.
3. Locate the**pending.xml** in the**WinSxS** folder and right-click on it.
4. Press the**Shift** key and click on the**Delete** option.
5. Restart your computer.

## 7\. Manually Download Windows Updates

 If you are unable to download a specific Windows update using the Settings page, consider a direct download and install approach. Visit the Microsoft Update Catalog website and search for the KB update you want to download. However, you first have to check the corresponding update number which is failing to download and install on your system.

![Manually Download Windows Updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/manually-download-windows-updates.jpg)

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 8\. Reset Windows

 Resetting Windows is the last resort you have if none of the above methods work in your favor. However, before learning[how to perform a Windows system reset](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) , try out general fixes such as[SFC, CHKDSK, and DISM](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) scans on your system. Also,[disable Windows Defender](https://www.makeuseof.com/how-to-turn-off-windows-defender/) and try updating your system before hitting the reset button.

## Update Windows Without Hiccups

 Windows updates can be tricky to install sometimes. Use the inbuilt troubleshooter to identify and fix problems. After that restart, all the crucial Windows update services and run the Disk Cleanup tool. If everything else fails, try doing a manual update or performing a Windows Reset.


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
<li><a href="https://youtube-docs.techidaily.com/024-approved-flash-fixing-fame-is-it-youtubes-shorts-or-tiktok-for-quick-content-conquest/"><u>[New] 2024 Approved  Flash-Fixing Fame  Is It YouTubes Shorts or TikTok for Quick Content Conquest?</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-essential-tutorial-navigating-mobizen-recording-features/"><u>[New] Essential Tutorial  Navigating Mobizen Recording Features</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-facebook-security-breach-regain-account-with-ease/"><u>[New] Facebook Security Breach? Regain Account with Ease</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-sharexs-standards-met-by-others-for-2024/"><u>[New] ShareX's Standards Met by Others for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-bring-back-faded-watch-icon-artwork-for-2024/"><u>[Updated] Bring Back Faded Watch Icon Artwork for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-incremental-introduction-for-2024/"><u>[Updated] Incremental Introduction for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/change-location-on-yik-yak-for-your-nokia-c32-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>Change Location on Yik Yak For your Nokia C32 to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/explaining-and-fixing-blue-screen-errors-in-win1011/"><u>Explaining and Fixing Blue Screen Errors in Win10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-turn-off-windows-from-starting-spotify/"><u>Guide to Turn Off Windows From Starting Spotify</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-from-vivo-v27-pro-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock from Vivo V27 Pro Phones with/without a PC</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-samsung-galaxy-a23-5g-drfone-by-drfone-virtual-android/"><u>Here Are Some Reliable Ways to Get Pokemon Go Friend Codes For Samsung Galaxy A23 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-zoom-error-code-1132-in-windows-11-and-11/"><u>How to Fix Zoom Error Code 1132 in Windows 11 & 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-remove-a-previously-synced-google-account-from-your-vivo-s17e-by-drfone-android/"><u>How to Remove a Previously Synced Google Account from Your Vivo S17e</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-remove-flashlight-from-iphone-13-mini-lock-screen-by-drfone-ios/"><u>How To Remove Flashlight From iPhone 13 mini Lock Screen</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-brief-beatcasts-role-of-the-melody/"><u>In 2024, Brief Beatcasts  Role of the Melody</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-cinematic-blackout-premiere-pro-guide/"><u>In 2024, Cinematic Blackout - Premiere Pro Guide</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-top-6-premium-video-translation-tools/"><u>In 2024, Top 6 Premium Video Translation Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/key-steps-for-entering-windows-11s-system32/"><u>Key Steps for Entering Windows 11'S System32</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-in-solving-the-mystery-fixing-obs-studios-hidden-error/"><u>Mastery in Solving the Mystery: Fixing OBS Studio's Hidden Error</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-monitors-choosing-personalized-themes-in-win-1011/"><u>Maximizing Monitors: Choosing Personalized Themes in Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-disconnected-spotify-sessions-in-w10w11/"><u>Mending Disconnected Spotify Sessions in W10/W11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-service-did-not-respond-error-in-windows/"><u>Overcoming The Service Did Not Respond Error in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/peering-into-major-complaints-about-windows-11-launch/"><u>Peering Into Major Complaints About Windows 11 Launch</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-file-naming-powertoys-batch-renamer-tool/"><u>Quick File Naming: PowerToys Batch Renamer Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-recovery-reviving-a-vanished-windows-update/"><u>Quick Recovery: Reviving a Vanished Windows Update</u></a></li>
<li><a href="https://windows11.techidaily.com/recover-missing-bluetooth-entries-on-windows-system/"><u>Recover Missing Bluetooth Entries on Windows System</u></a></li>
<li><a href="https://windows11.techidaily.com/redefining-where-you-keep-your-files-onedrive-move-in-windows-10/"><u>Redefining Where You Keep Your Files: OneDrive Move in Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/reversing-game-launch-hurdles-with-epic-logins/"><u>Reversing Game Launch Hurdles with Epic Logins</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-windows-11-sign-ins-with-blank-screen-fixes/"><u>Reviving Windows 11 Sign-Ins with Blank Screen Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/sd-card-vanishing-act-solutions-for-windows-explore/"><u>SD Card Vanishing Act: Solutions for Windows Explore</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-videos-back-from-realme-gt-5-pro-by-fonelab-android-recover-video/"><u>Simple ways to get lost videos back from Realme GT 5 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-non-functional-utorrent-installer-on-pcs-with-winos/"><u>Solutions for Non-Functional uTorrent Installer on PCs with WinOS</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-the-mystery-of-error-0x0000004e-on-windows/"><u>Solving the Mystery of Error 0X0000004E on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/stealthy-shutdown-auto-restart-guide-for-windows-pcs/"><u>Stealthy Shutdown: Auto-Restart Guide for Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-uninstalling-win11s-official-app/"><u>Strategies for Uninstalling Win11's Official App</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-curtail-chromes-unintended-tab-creation/"><u>Strategies to Curtail Chrome's Unintended Tab Creation</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-your-workspace-integrating-directories-into-taskbar-menu/"><u>Streamlining Your Workspace: Integrating Directories Into Taskbar Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-your-file-management-with-powerrename/"><u>Transform Your File Management with PowerRename</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secrets-to-using-netstat-within-windows-11/"><u>Unveiling the Secrets to Using Netstat Within Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/virtual-vigilance-effective-methods-to-secure-your-os/"><u>Virtual Vigilance: Effective Methods to Secure Your OS</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-files-a-deep-dive-into-date-customization/"><u>Windows Files: A Deep Dive Into Date Customization</u></a></li>
</ul></div>
