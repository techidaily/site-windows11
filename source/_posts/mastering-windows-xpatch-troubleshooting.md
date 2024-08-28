---
title: Mastering Windows XPatch Troubleshooting
date: 2024-08-27T16:03:34.970Z
updated: 2024-08-28T16:03:34.970Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering Windows XPatch Troubleshooting
excerpt: This Article Describes Mastering Windows XPatch Troubleshooting
keywords: XP Patch Fix Guide,Xp Update Solutions,XP Patch Problems,WinXP Patch Help,Windows XP Troubleshoot,XP Security Updates,XP Bug Resolution
thumbnail: https://thmb.techidaily.com/f755ebc6fd74e541b86783b8f288eb9ebe73ceda235653be011e1c74d43e6c3e.jpg
---

## Mastering Windows XPatch Troubleshooting

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

## 3\. Restart Windows Update services

 Windows Update uses a bunch of background services to fetch and download updates. If these services aren’t running automatically, you will encounter an error. These include**Windows Update Service** ,**Windows Installer Service** ,**Cryptographic Services** , and**Background Intelligent Transfer Service** .

Repeat the following steps to start the necessary services:

1. Press**Win + R** to[launch the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**services.msc** and press the**enter** key
2. Services utility will launch on your system. Now locate the**Background Intelligent Transfer** service in the list.
3. Double-click on the BITS service to open the**properties** window. Set the**Startup Type** as**Automatic** and click on the**Apply** button.  
![Disabling Windows Update Services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/disabling-windows-update-services.jpg)
4. Click on the**OK** button and close the Properties windows. Now, right-click on the service and select the**Start** option from the context menu.
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->
5. Similarly, set all the services as automatic and manually start them.
6. **Close** the Services window and reattempt the Windows update.

## 4\. Run the Disk Cleanup Tool

 Disk Cleanup can wipe the delivery optimization files, old Windows update files as well as the Temp folder. If files in these locations are corrupted, they can interfere with the normal update process. Here’s how to run disk cleanup on Windows:

1. Press**Win + S** to open the search utility in Windows.
2. Type**cleanmgr.exe** and press the enter key to open the Disk Cleanup tool.
3. It will select the system drive (C) by default. Click on the**OK** button to continue.
4. Select the checkboxes of files that you want the tool to clean up. Then, click on the**Clean up system files** button.  
![Disk Cleanup App in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/disk-cleanup-app-in-windows-11.jpg)
5. Disk Cleanup will close and redirect you to pick the appropriate drive. Click on the**OK** button.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Lastly, click on the**Delete files** button.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## 5\. Rename the SoftwareDistribution Folder

 Windows update stores its content in the SoftwareDistribution folder. Since it is located inside the Windows folder in the C drive, you mustn’t delete it. Instead, you can rename the folder to force the update service to recreate the folder again.

Repeat the following steps:

1. Open the Start menu and search CMD. Press Ctrl + Shift + Enter to open the command prompt with admin privileges.
2. Type the following commands to stop all the Windows update-related services:  
 net stop wuauserv net stop cryptSvc net stop bits net stop msiserver  
![Rename the SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/rename-the-softwaredistribution-folder.jpg)
3. Once these services stop running, type**cls** in the command prompt windows. Then enter the following commands:  
 ren C:\\Windows\\SoftwareDistribution SoftwareDistribution.old ren C:\\Windows\\System32\\catroot2 Catroot2.old  
![Rename the SoftwareDistribution Folder 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/rename-the-softwaredistribution-folder-2.jpg)
4. Both the above commands rename the**SoftwareDistribution** folder and**Catroot2** folder.
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
5. Now, you need to restart all the Windows services you stopped in step 3\. Enter the following commands:  
net start wuauserv net start cryptSvc net start bits net start msiserver  
![Rename the SoftwareDistribution Folder 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/rename-the-softwaredistribution-folder-3.jpg)
6. Lastly,**restart** your system and visit the following folder location:**C:\\Windows** . You will notice that there is a new SoftwareDistribution folder in that location.
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
## 8\. Reset Windows

 Resetting Windows is the last resort you have if none of the above methods work in your favor. However, before learning[how to perform a Windows system reset](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) , try out general fixes such as[SFC, CHKDSK, and DISM](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) scans on your system. Also,[disable Windows Defender](https://www.makeuseof.com/how-to-turn-off-windows-defender/) and try updating your system before hitting the reset button.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
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
<li><a href="https://tiktok-clips.techidaily.com/new-2024-approved-engaging-in-the-moment-of-a-tiktok-life/"><u>[New] 2024 Approved  Engaging in the Moment of a TikTok Life</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-the-ultimate-guide-to-rapidly-eliminating-youtube-feedback/"><u>[New] 2024 Approved  The Ultimate Guide to Rapidly Eliminating YouTube Feedback</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-scaling-up-your-income-with-instagram-mastery/"><u>[New] In 2024, Scaling Up Your Income with Instagram Mastery</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-smart-choice-selecting-the-top-5-webcams-for-clear-audio-for-2024/"><u>[New] Smart Choice  Selecting the Top 5 Webcams for Clear Audio for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-best-multiple-video-call-and-chat-tools/"><u>[Updated] Best Multiple Video Call & Chat Tools</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-expert-insights-the-best-approaches-to-live-cricket-broadcasting/"><u>[Updated] Expert Insights  The Best Approaches to Live Cricket Broadcasting</u></a></li>
<li><a href="https://blog-min.techidaily.com/2-ways-to-transfer-text-messages-from-itel-a70-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>2 Ways to Transfer Text Messages from Itel A70 to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/5-profound-impacts-of-multilingual-communication/"><u>5 Profound Impacts of Multilingual Communication</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/android-unlock-code-sim-unlock-your-zte-nubia-z60-ultra-phone-and-remove-locked-screen-by-drfone-android/"><u>Android Unlock Code Sim Unlock Your ZTE Nubia Z60 Ultra Phone and Remove Locked Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-steps-to-locate-gpo-in-windows-os/"><u>Essential Steps to Locate GPO in Windows OS</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/evaluating-the-clever-design-a-comprehensive-review-of-twelve-south-bookbook-v2-case/"><u>Evaluating the Clever Design: A Comprehensive Review of Twelve South BookBook V2 Case</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-lacking-steam-icon-issues-on-windows-pc/"><u>Fix Lacking Steam Icon Issues on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/from-novice-to-pro-setting-up-hyper-v-on-win-11-for-home-users/"><u>From Novice to Pro: Setting Up Hyper-V on Win 11 for Home Users</u></a></li>
<li><a href="https://windows11.techidaily.com/halting-windows-edge-tab-loads-properly/"><u>Halting Windows Edge Tab Loads Properly</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-reliable-is-chatgpt-when-seeking-online-medical-information/"><u>How Reliable Is ChatGPT When Seeking Online Medical Information?</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-notes-from-iphone-14-plus-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Recover Deleted Notes from iPhone 14 Plus? | Stellar</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-rectify-the-incorrect-token-call-error-on-win11/"><u>How to Rectify the “Incorrect Token Call” Error on Win11</u></a></li>
<li><a href="https://some-skills.techidaily.com/how-to-use-picture-in-picture-pip-on-microsoft-edge-for-2024/"><u>How to Use Picture in Picture (PIP) on Microsoft Edge for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-humor-harmony-optimal-websites-for-fun-ringtones/"><u>In 2024, Humor Harmony  Optimal Websites for Fun Ringtones</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-investment-insights-15-must-see-youtube-channels/"><u>In 2024, Investment Insights  15 Must-See YouTube Channels</u></a></li>
<li><a href="https://windows11.techidaily.com/increase-dynamic-display-speed-of-task-manager-win-11/"><u>Increase Dynamic Display Speed of Task Manager Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/integrate-your-windows-fileshare-seamlessly/"><u>Integrate Your Windows Fileshare Seamlessly</u></a></li>
<li><a href="https://fake-location.techidaily.com/looking-for-a-location-changer-on-samsung-galaxy-s24-look-no-further-drfone-by-drfone-virtual-android/"><u>Looking For A Location Changer On Samsung Galaxy S24? Look No Further | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/master-control-of-windows-installer-on-devices/"><u>Master Control of Windows Installer on Devices</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/master-the-fixes-resolving-bootmgr-error-messages-on-your-pc/"><u>Master the Fixes: Resolving BOOTMGR Error Messages on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/optimized-browsing-the-least-ram-and-cpu-hungry-on-all-major-operating-systems/"><u>Optimized Browsing: The Least RAM & CPU-Hungry On All Major Operating Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-errors-in-windows-memory-check-tool/"><u>Overcoming Errors in Windows Memory Check Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-stubborn-windows-key-issues/"><u>Overcoming Stubborn Windows Key Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-unverified-app-errors-in-windows/"><u>Overcoming Unverified App Errors in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/perfecting-your-powerpoint-presentations-printouts-on-windows-platforms/"><u>Perfecting Your PowerPoint Presentations' Printouts on Windows Platforms</u></a></li>
<li><a href="https://windows11.techidaily.com/reactivating-windows-11-search-tool-performance/"><u>Reactivating Windows 11 Search Tool Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/reverse-lost-rendering-device-error-in-overwatch-2/"><u>Reverse Lost Rendering Device Error in Overwatch 2</u></a></li>
<li><a href="https://windows11.techidaily.com/revive-security-settings-windows-11-admin-control-restoration/"><u>Revive Security Settings: Windows 11 Admin Control Restoration</u></a></li>
<li><a href="https://driver-download.techidaily.com/speedy-and-straightforward-how-to-get-the-newest-surface-dock-driver/"><u>Speedy & Straightforward: How to Get the Newest Surface Dock Driver</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-tackle-errortoomanyretries-in-wsl-subsystem/"><u>Strategies to Tackle ERROR_TOO_MANY_RETRIES in WSL Subsystem</u></a></li>
<li><a href="https://windows11.techidaily.com/the-intricate-world-of-user-identification-in-win11/"><u>The Intricate World of User Identification in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-top-9-benefits-of-choosing-a-pc-over-a-mac/"><u>The Top 9 Benefits of Choosing a PC Over a Mac</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-and-tricks-for-restoring-win11s-5g-link/"><u>Tips and Tricks for Restoring Win11’s 5G Link</u></a></li>
<li><a href="https://fox-that.techidaily.com/troubleshooting-why-doesnt-face-id-recognition-work-on-my-iphone/"><u>Troubleshooting: Why Doesn't Face ID Recognition Work on My iPhone?</u></a></li>
<li><a href="https://windows11.techidaily.com/unfreeze-shift-button-on-your-pc/"><u>Unfreeze Shift Button on Your PC.</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-control-panel-access-methods/"><u>Unveiling Control Panel Access Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secret-recognizing-and-resolving-non-installed-hdd-issue-win-11-style/"><u>Unveiling the Secret: Recognizing & Resolving Non-Installed HDD Issue, Win 11 Style</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secrets-activate-cortana-with-vivetool/"><u>Unveiling the Secrets: Activate Cortana with ViveTool</u></a></li>
<li><a href="https://windows11.techidaily.com/upgrade-taskbar-appearance-instructions-to-include-a-weather-icon-in-windows-11-system-tray/"><u>Upgrade Taskbar Appearance: Instructions to Include a Weather Icon in Windows 11 System Tray</u></a></li>
<li><a href="https://windows11.techidaily.com/why-windows-supercomputers-are-game-changers/"><u>Why Windows Supercomputers Are Game-Changers</u></a></li>
</ul></div>
