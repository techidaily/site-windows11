---
title: Resetting the Explorer View for Better Management
date: 2024-08-15T15:25:09.153Z
updated: 2024-08-16T15:25:09.153Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resetting the Explorer View for Better Management
excerpt: This Article Describes Resetting the Explorer View for Better Management
keywords: ExploreViewReset,ManageExplorer,ResetExpVIEW,ViewManagement,ExplorerRefresh,BetterManageEXP,OptimizeEXPVIEW
thumbnail: https://thmb.techidaily.com/ecc3916e90aab64f99ff84f9c45d036bcf1e08682351feaa92b6a0ff146b14b9.jpg
---

## Resetting the Explorer View for Better Management

 Folder View Settings in Windows help you control how the contents of a particular folder are displayed and organized. If you’ve changed these settings, but now want to reset them to the default view, it’s easy. Read this guide to learn how to reset Folder View settings on your Windows 11 PC.

## How to Reset Folder View Settings to Default on Windows

 There are three ways to reset your Folder View Settings to the default view. The first method is to run a batch file, the second using File Explorer, whereas the third and final method involves tweaking the registry editor. This post explains each method in detail. Let's dive into it.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
### 1\. Run a Batch File to Reset Folder View Settings to Default

 Resetting the Folder View Settings with this method requires creating and running a batch file. This will reset the settings for all folders across your computer. Here's how to do it:

1. Right-click on your desktop and select**New > Text Document** .
2. Name it**ResetFolderViewSettings** and press Enter to save it.
3. Open the newly created text file in Notepad or any other text editor of your choice.
4. Now copy and paste the following code into the file:  
`@echo off  

:: Resets folder view settings, window size and position of all folders  
Reg Delete "HKCU\SOFTWARE\Classes\Local Settings\Software\Microsoft\Windows\Shell\BagMRU" /F  
Reg Delete "HKCU\SOFTWARE\Classes\Local Settings\Software\Microsoft\Windows\Shell\Bags" /F  

:: To reset "Apply to Folders" views to default for all folder types  
REG Delete "HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\Streams\Defaults" /F  

:: To reset size of details, navigation, preview panes to default for all folders  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Modules\GlobalSettings\Sizer" /F  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Modules\NavPane" /F  

:: To reset size of Save as amd Open dialogs to default for all folders  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\CIDOpen" /F  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\CIDSave" /F  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\ComDlg32" /F  

:: To kill and restart explorer process  
taskkill /f /im explorer.exe  
start explorer.exe`
5. After adding the code, click**File** in the top menu, then select**Save As** .
6. Now select**All Files** in the Save as type menu, and add**.bat** to the end of the file’s name.  
![Run a Batch File to Reset Folder View Settings to Default](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-a-batch-file-to-reset-folder-view-settings-to-default.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
7. From the left pane, select**Desktop** as the location.
8. Then click**Save** and close the text editor window.
9. Finally, double-click the batch file you created, and it will reset your Folder View Settings to the default view.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. Reset Folder View Settings to Default via File Explorer

 If you only need to reset the View Settings of all folders of the same type, this method is for you. Here's what you have to do:

1. Click on Start and search for**File Explorer Options** . To learn more about it, see our guide on [how to open the Folder Options on Windows](https://www.makeuseof.com/windows-10-open-folder-options/) .
2. Now, select the**View** tab in the top bar and tap on**Reset Folders** .  
![Reset Folder View Settings to Default Via File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-via-file-explorer.jpg)
3. Click**Yes** when prompted to confirm your action.
4. Finally, hit**OK** and the window will close.

 This will reset your Folder View Settings to Windows' default settings.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->
### 3\. Reset Folder View Settings to Default Using Registry Editor

 The last method to reset Folder View settings involves using the Windows Registry Editor. You should only use this method if you are an experienced user and know how it works, since messing with its keys could cause serious problems. To avoid data loss, you must [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before continuing.

 To reset folder view settings using the registry editor, do the following:

1. Press**Win + R** on your keyboard to [open the Run command](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**regedit** in the text box and press Enter. This will [open the Registry Editor window](https://www.makeuseof.com/windows-11-open-registry-editor/) .
3. Navigate to the following location:  
HKEY_CURRENT_USER\Software\Classes\Local Settings\Software\Microsoft\Windows\Shell
4. In the left sidebar, right-click on the**BagMRU** folder and select**Delete.**  
![Reset Folder View Settings to Default Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-using-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
5. Click**Yes** when asked to confirm your action.
6. Similarly, delete the**Bags** folder and close the Registry window.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
## Reset Folder View Settings to Default

 Folder View on Windows allows users to customize their view of files and folders. This includes settings such as the file size information, restoring the previous folder when logging in, and automatically entering words when searching.

 However, if you have changed the View settings, this guide will help you reset Folder Options to its default.


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
<li><a href="https://vp-tips.techidaily.com/new-freely-accessing-pinterest-vids-top-5-free-downloader-rankings/"><u>[New] Freely Accessing Pinterest Vids  Top 5 Free Downloader Rankings</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-streamlining-video-features-youtube-annotations-guide/"><u>[New] Streamlining Video Features  YouTube Annotations Guide</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-enhancing-youtube-videos-with-professional-techniques-using-wmm/"><u>[Updated] 2024 Approved  Enhancing YouTube Videos with Professional Techniques Using WMM</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-easeus-assessment-for-all-for-2024/"><u>[Updated] EaseUS Assessment for All for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-fast-funny-build-memes-with-kapwing/"><u>[Updated] Fast, Funny  Build Memes with Kapwing</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-recording-real-time-action-in-overwatch/"><u>[Updated] In 2024, Recording Real-Time Action in Overwatch</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-top-gamers-tools-premium-gear-lists-on-youtube/"><u>[Updated] In 2024, Top Gamers' Tools  Premium Gear Lists on YouTube</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-troubleshooting-companion-restoring-srt-functionality-in-premiere/"><u>[Updated] The Troubleshooting Companion  Restoring SRT Functionality in Premiere</u></a></li>
<li><a href="https://windows11.techidaily.com/1720600438278-windowsstellar-data-recovery/"><u>「Windowsで失われたファイルを取り戻せる無料ソフトStellar Data Recovery」</u></a></li>
<li><a href="https://fox-that.techidaily.com/12-effective-tips-to-restore-iphones-flashlight-functionality/"><u>12 Effective Tips to Restore iPhone's Flashlight Functionality</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-how-to-shoot-vertical-panorama-photos-with-your-smartphone-androidios/"><u>2024 Approved  How to Shoot Vertical Panorama Photos with Your Smartphone Android/iOS</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-unveiling-secrets-for-converting-instagram-vids-into-high-quality-mp4/"><u>2024 Approved  Unveiling Secrets for Converting Instagram Vids Into High-Quality MP4</u></a></li>
<li><a href="https://windows11.techidaily.com/9-ways-to-fix-windows-hello-fingerprint-recognition-not-working/"><u>9 Ways to Fix Windows Hello Fingerprint Recognition Not Working</u></a></li>
<li><a href="https://win-blog.techidaily.com/a-complete-guide-to-fixing-slow-loading-times-in-rainbow-six-siege/"><u>A Complete Guide to Fixing Slow Loading Times in Rainbow Six Siege</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-razer-device-absence-in-win-1011-via-synapse/"><u>Addressing Razer Device Absence in Win 10/11 via Synapse</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-service-disruptions-with-steam-windows-11-style/"><u>Addressing Service Disruptions with Steam, Windows 11 Style</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-reset-account-lockout-counter-post-failed-sign-in-attempts/"><u>Adjusting Reset Account Lockout Counter Post-Failed Sign-In Attempts</u></a></li>
<li><a href="https://windows11.techidaily.com/deleting-persistent-epic-launcher-without-hurdles-in-w11/"><u>Deleting Persistent Epic Launcher Without Hurdles in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-window-11-safety-with-best-in-class-password-protectors/"><u>Elevating Window 11 Safety with Best-in-Class Password Protectors</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/elite-video-services-for-performing-artists/"><u>Elite Video Services for Performing Artists</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-speed-of-microsoft-edge-on-win10plus11/"><u>Enhancing Speed of Microsoft Edge on Win10+11</u></a></li>
<li><a href="https://windows11.techidaily.com/find-your-windows-11-backdrops-saving-spot/"><u>Find Your Windows 11 Backdrop's Saving Spot</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-for-rockalldlldll-not-found-on-windows-devices/"><u>Fix for 'Rockalldll.dll' Not Found on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-error-xc0000142-with-windows-oses/"><u>Fixing Error XC0000142 with Windows OSes</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-motorola-moto-g23-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Motorola Moto G23 | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-tiktok-to-see-more-content-on-your-samsung-galaxy-f15-5g-drfone-by-drfone-virtual-android/"><u>How to Change Location on TikTok to See More Content On your Samsung Galaxy F15 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-an-incorrect-cpu-usage-in-the-windows-task-manager/"><u>How to Fix an Incorrect CPU Usage in the Windows Task Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-page-could-not-be-loaded-error-in-the-microsoft-store-for-windows/"><u>How to Fix the Page Could Not Be Loaded Error in the Microsoft Store for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-keep-windows-full-screen-without-mobility-features/"><u>How To Keep Windows Full Screen without Mobility Features</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-motorola-g54-5g-device-by-drfone-android/"><u>In 2024, The Ultimate Guide How to Bypass Swipe Screen to Unlock on Motorola G54 5G Device</u></a></li>
<li><a href="https://windows11.techidaily.com/installation-essentials-intel-network-adapters-for-windows-users/"><u>Installation Essentials: Intel Network Adapters for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/learn-9-keys-to-tweaking-windows-audio-properties/"><u>Learn 9 Keys to Tweaking Windows Audio Properties</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/mastering-easy-hdr-a-step-by-step-guide-for-2024/"><u>Mastering Easy HDR  A Step-by-Step Guide for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-group-policy-editor-navigation-windows-11-style/"><u>Mastering Group Policy Editor Navigation, Windows 11 Style</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11s-software-compatibility-tool/"><u>Navigating Windows 11’S Software Compatibility Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/nine-pathways-out-of-the-window-11s-0x8004def5-puzzle/"><u>Nine Pathways Out of the Window 11'S 0X8004DEF5 Puzzle</u></a></li>
<li><a href="https://windows11.techidaily.com/nullify-specification-shortfalls-alerts-in-win11/"><u>Nullify Specification Shortfalls Alerts in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/pro-tips-for-buying-windows-11-vcs/"><u>Pro Tips for Buying Windows 11 VCs</u></a></li>
<li><a href="https://windows11.techidaily.com/proactive-measures-for-sticky-notes-longevity/"><u>Proactive Measures for Sticky Notes' Longevity</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-dual-monitor-setup-problems/"><u>Resolving Dual Monitor Setup Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/simplified-docx-to-pdf-workflow-in-windows-11-systems/"><u>Simplified DOCX to PDF Workflow in Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-deleting-account-info-from-windows-logon/"><u>Steps for Deleting Account Info From Windows Logon</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-taskbar-tools-monitoring-cpu-ram-and-disk-use/"><u>Tailored Taskbar Tools: Monitoring CPU, RAM & Disk Use</u></a></li>
<li><a href="https://windows11.techidaily.com/tech-enthusiasts-rejoice-black-friday-offer-for-lifetime-612-windows-11-savings/"><u>Tech Enthusiasts Rejoice - Black Friday Offer for Lifetime $6.12 Windows 11 Savings</u></a></li>
<li><a href="https://windows11.techidaily.com/the-future-of-personal-computing-transforming-window-11-widgets/"><u>The Future of Personal Computing: Transforming Window 11 Widgets</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-your-creative-potential-with-win11s-photos-app-creating-dynamic-slideshows-and-image-spot-repair/"><u>Unlock Your Creative Potential with Win11's Photos App: Creating Dynamic Slideshows & Image Spot Repair</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-application-startup-hexadecimal-issue-error/"><u>Unraveling The Application Startup Hexadecimal Issue (Error)</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-fcpx-skin-retouching-a-plugin-free-guide-to-flawless-skin/"><u>Updated 2024 Approved FCPX Skin Retouching A Plugin-Free Guide to Flawless Skin</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/updated-in-2024-how-to-use-emojis-on-windows/"><u>Updated In 2024, How to Use Emojis on Windows</u></a></li>
<li><a href="https://techidaily.com/useful-ways-that-can-help-to-effectively-recover-deleted-files-from-vivo-x100-pro-by-fonelab-android-recover-data/"><u>Useful ways that can help to effectively recover deleted files from Vivo X100 Pro</u></a></li>
<li><a href="https://win-howtos.techidaily.com/winning-the-battle-against-windows-10s-persistent-0x800705b4-update-issue-a-step-by-step-fix/"><u>Winning the Battle Against Windows 10'S Persistent 0X800705b4 Update Issue – A Step-by-Step Fix</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-the-battle-with-unshuttable-windows-10-systems-fixed/"><u>Winning the Battle with Unshuttable Windows 10 Systems [FIXED]</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/yahoo-messenger-the-complete-story-of-its-creation-and-closure/"><u>Yahoo! Messenger: The Complete Story of Its Creation and Closure</u></a></li>
</ul></div>
