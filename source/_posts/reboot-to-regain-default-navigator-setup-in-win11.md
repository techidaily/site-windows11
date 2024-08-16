---
title: Reboot to Regain Default Navigator Setup in Win11
date: 2024-08-15T16:21:55.154Z
updated: 2024-08-16T16:21:55.154Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reboot to Regain Default Navigator Setup in Win11
excerpt: This Article Describes Reboot to Regain Default Navigator Setup in Win11
keywords: Win11 Nav Default,Win11 ReBoot Guide,Win11 Restore Navigator,Win11 Setup Help,Win11 Regain Nav,Win11 Navigate Default,Win11 Navigator Revive
thumbnail: https://thmb.techidaily.com/4e339c0438a311f0739fe8dd767b8fe136567e49f78cba1047e1590ff1927d2b.png
---

## Reboot to Regain Default Navigator Setup in Win11

 Folder View Settings in Windows help you control how the contents of a particular folder are displayed and organized. If you’ve changed these settings, but now want to reset them to the default view, it’s easy. Read this guide to learn how to reset Folder View settings on your Windows 11 PC.

## How to Reset Folder View Settings to Default on Windows

 There are three ways to reset your Folder View Settings to the default view. The first method is to run a batch file, the second using File Explorer, whereas the third and final method involves tweaking the registry editor. This post explains each method in detail. Let's dive into it.

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
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->
7. From the left pane, select**Desktop** as the location.
8. Then click**Save** and close the text editor window.
9. Finally, double-click the batch file you created, and it will reset your Folder View Settings to the default view.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. Reset Folder View Settings to Default via File Explorer

 If you only need to reset the View Settings of all folders of the same type, this method is for you. Here's what you have to do:

1. Click on Start and search for**File Explorer Options** . To learn more about it, see our guide on[how to open the Folder Options on Windows](https://www.makeuseof.com/windows-10-open-folder-options/) .
2. Now, select the**View** tab in the top bar and tap on**Reset Folders** .  
![Reset Folder View Settings to Default Via File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-via-file-explorer.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4742929&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/boxshot(2).png" border="0">Kanto Player Professional</a>
<!-- affiliate ads end -->
3. Click**Yes** when prompted to confirm your action.
4. Finally, hit**OK** and the window will close.

 This will reset your Folder View Settings to Windows' default settings.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698998&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/MacBook_Pro_lyrx-withsinger-tv.png" border="0">LYRX is an easy-to-use karaoke software with the professional features karaoke hosts need to perform with precision. LYRX is karaoke show hosting software that supports all standard karaoke file types as well as HD video formats, and it’s truly fun to use. 
LYRX Karaoke Software MAC/WINDOWS (Includes Activation For 3 Machines)</a>
<!-- affiliate ads end -->
### 3\. Reset Folder View Settings to Default Using Registry Editor

 The last method to reset Folder View settings involves using the Windows Registry Editor. You should only use this method if you are an experienced user and know how it works, since messing with its keys could cause serious problems. To avoid data loss, you must[create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before continuing.

 To reset folder view settings using the registry editor, do the following:

1. Press**Win + R** on your keyboard to[open the Run command](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**regedit** in the text box and press Enter. This will[open the Registry Editor window](https://www.makeuseof.com/windows-11-open-registry-editor/) .
3. Navigate to the following location:  
HKEY_CURRENT_USER\Software\Classes\Local Settings\Software\Microsoft\Windows\Shell
4. In the left sidebar, right-click on the**BagMRU** folder and select**Delete.**  
![Reset Folder View Settings to Default Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-using-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
5. Click**Yes** when asked to confirm your action.
6. Similarly, delete the**Bags** folder and close the Registry window.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-videos.techidaily.com/new-crafting-the-perfect-facebook-video-post-pcandroid-techniques-for-2024/"><u>[New] Crafting the Perfect Facebook Video Post, PC/Android Techniques for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-how-to-organize-photo-album-on-iphone-and-icloud-for-2024/"><u>[New] How To Organize Photo Album On iPhone And iCloud for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-quick-methods-for-scavenging-free-frame-videos/"><u>[New] Quick Methods for Scavenging Free Frame Videos</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-snatching-your-secret-snaps-again/"><u>[New] Snatching Your Secret Snaps Again</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-transforming-in-game-audio-identity-for-a-unique-competitive-advantage-no-charge/"><u>[New] Transforming In-Game Audio Identity for a Unique Competitive Advantage (No Charge!)</u></a></li>
<li><a href="https://windows11.techidaily.com/10-essential-windows-methods-for-controller-recognition/"><u>10 Essential Windows Methods for Controller Recognition</u></a></li>
<li><a href="https://windows11.techidaily.com/10-overlooked-windows-11-aesthetic-themes/"><u>10 Overlooked Windows 11 Aesthetic Themes</u></a></li>
<li><a href="https://windows11.techidaily.com/10-solutions-for-windows-uncovering-lost-nexus-controllers/"><u>10 Solutions for Windows: Uncovering Lost Nexus Controllers</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-altvmix-cross-platform-virtual-mixer/"><u>2024 Approved  AltVMix  Cross-Platform Virtual Mixer</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-revenue-rundown-the-profit-of-youtube-star-pewdopeep/"><u>2024 Approved  Revenue Rundown  The Profit of YouTube Star PewDoPeep</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-windows-and-mac-call-recordings-explained-20plus-ways-to-go/"><u>2024 Approved  Windows & Mac Call Recordings Explained - 20+ Ways to Go</u></a></li>
<li><a href="https://windows11.techidaily.com/5-ways-to-fix-the-remote-procedure-call-failed-error-in-windows/"><u>5 Ways to Fix the Remote Procedure Call Failed Error in Windows</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/7-groundbreaking-tools-excluding-chatgpt-for-code-writing/"><u>7 Groundbreaking Tools Excluding ChatGPT for Code Writing</u></a></li>
<li><a href="https://windows11.techidaily.com/a-deep-dive-into-winning-windows-captures-with-printscreen-or-snip-tool/"><u>A Deep Dive Into Winning Windows Captures with Printscreen or Snip Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/a-practical-approach-to-windows-network-file-transfer-via-python/"><u>A Practical Approach to Windows Network File Transfer via Python</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerating-epic-launcher-on-pcs-a-quick-guide/"><u>Accelerating Epic Launcher on PCs: A Quick Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/accessing-windows-11s-screen-capture-shortcut/"><u>Accessing Windows 11'S Screen Capture Shortcut</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-portable-network-capabilities-via-windows-11-pc/"><u>Activating Portable Network Capabilities via Windows 11 PC</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-11-get-support-disruption/"><u>Addressing Windows 11 'Get Support' Disruption</u></a></li>
<li><a href="https://windows11.techidaily.com/adjust-brightness-slider-look-for-the-brightness-slider-under-system-or-personalization-tabs-in-settings/"><u>Adjust Brightness Slider: Look for the Brightness Slider Under 'System' Or 'Personalization' Tabs in Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/alomware-essentials-for-customizing-windows-experience/"><u>AlomWare Essentials for Customizing Windows Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/avoidance-tactics-against-flaky-saving-mechanism-in-nvidia-gui/"><u>Avoidance Tactics Against Flaky Saving Mechanism in Nvidia GUI</u></a></li>
<li><a href="https://windows11.techidaily.com/banish-os-requirement-warning-labels-in-windows-11/"><u>Banish OS Requirement Warning Labels in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-your-vbox-windows-install-with-dependencies/"><u>Boost Your VBox Windows Install with Dependencies</u></a></li>
<li><a href="https://windows11.techidaily.com/bridge-the-mc-lan-chasm-7-key-fixes-for-windows-users/"><u>Bridge the MC LAN Chasm: 7 Key Fixes for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/browser-breakdowns-heres-how-to-get-past-the-roadblocks-in-win-os/"><u>Browser Breakdowns? Here's How to Get Past the Roadblocks in WIN OS</u></a></li>
<li><a href="https://windows11.techidaily.com/bypass-license-validity-warning-on-w10-and-w11-systems/"><u>Bypass License Validity Warning on W10 & W11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/bypass-the-troubleshooter-effective-fixes-in-vista-and-7/"><u>Bypass the Troubleshooter: Effective Fixes in Vista & 7</u></a></li>
<li><a href="https://extra-information.techidaily.com/capture-the-world-with-these-leading-4k-cams-for-2024/"><u>Capture the World with These Leading 4K Cams for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/christmas-tech-surprises-through-microsofts-marketplace/"><u>Christmas Tech Surprises Through Microsoft's Marketplace</u></a></li>
<li><a href="https://windows11.techidaily.com/combating-writing-denials-in-windows-11-environment/"><u>Combating Writing Denials in Windows 11 Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-windows-steam-blackout-immediate-solutions/"><u>Combatting Windows Steam Blackout: Immediate Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/command-your-computer-mastery-of-windows-through-alomware/"><u>Command Your Computer: Mastery of Windows Through AlomWare</u></a></li>
<li><a href="https://windows11.techidaily.com/comparative-overview-of-installation-methods-exe-and-msi-files/"><u>Comparative Overview of Installation Methods: Exe & Msi Files</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-tutorial-for-extracting-dual-and-multi-archive-files/"><u>Comprehensive Tutorial for Extracting Dual and Multi-Archive Files</u></a></li>
<li><a href="https://windows11.techidaily.com/converting-oculus-quest-2-to-windows-vr-compatibility-level/"><u>Converting Oculus Quest 2 to Windows VR Compatibility Level</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-systemsettings-executable-errors-on-windows-11/"><u>Correcting SystemSettings Executable Errors on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/corrective-measures-for-xc0351000-hyprocvisor-not-found/"><u>Corrective Measures for XC0351000: Hyprocvisor Not Found</u></a></li>
<li><a href="https://windows11.techidaily.com/creating-custom-volume-control-commands-for-windows-11-users/"><u>Creating Custom Volume Control Commands for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/creating-personalized-music-cds-with-mp3s-a-compreenasive-guide-for-windows-users-imgburn/"><u>Creating Personalized Music CDs with Mp3s: A Compreenasive Guide for Windows Users (ImgBurn)</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-graphics-output-dpi-adjustment-guide/"><u>Customizing Graphics Output: DPI Adjustment Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-complexity-of-wintoys-your-guide-to-a-versatile-tool/"><u>Decoding the Complexity of 'WinToys': Your Guide to a Versatile Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-microsofts-code-companion-for-enhanced-programming/"><u>Demystifying Microsoft's Code Companion for Enhanced Programming</u></a></li>
<li><a href="https://windows11.techidaily.com/deterring-windows-auto-update-alerts/"><u>Deterring Windows Auto-Update Alerts</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-factory-seal-on-windows-11/"><u>Disabling Factory Seal on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-ways-to-free-disk-space-without-deleting-windows-11-files-max-156-chars/"><u>Discover Ways to Free Disk Space Without Deleting Windows 11 Files (Max 156 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-your-ideal-nvidia-driver-entertainment-driven-selection/"><u>Discover Your Ideal Nvidia Driver: Entertainment-Driven Selection</u></a></li>
<li><a href="https://windows11.techidaily.com/discovery-of-four-cortana-succession-steps/"><u>Discovery of Four Cortana Succession Steps</u></a></li>
<li><a href="https://extra-tips.techidaily.com/extended-review-for-uncomplicated-hdr-techniques/"><u>Extended Review for Uncomplicated HDR Techniques</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/frequency-logging-computer-sounds-and-dialogue-for-2024/"><u>Frequency Logging  Computer Sounds & Dialogue for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-10-best-video-editors-for-webcam-videos/"><u>In 2024, 10 Best Video Editors for Webcam Videos</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-vivo-t2-pro-5g-by-drfone-android/"><u>In 2024, 10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On Vivo T2 Pro 5G</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-everything-you-need-to-know-about-unlocked-iphone-13-by-drfone-ios/"><u>In 2024, Everything You Need To Know About Unlocked iPhone 13</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-lava-yuva-3-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How PGSharp Save You from Ban While Spoofing Pokemon Go On Lava Yuva 3 Pro? | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-how-to-add-border-to-instagram-photos/"><u>In 2024, How to Add Border to Instagram Photos?</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-delete-icloud-account-with-or-without-password-from-your-apple-iphone-7windowsmac-by-drfone-ios/"><u>In 2024, How to Delete iCloud Account with or without Password from your Apple iPhone 7/Windows/Mac</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-oppo-a58-4g-phone-frp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Oppo A58 4G Phone FRP Lock</u></a></li>
<li><a href="https://hardware-help.techidaily.com/keep-your-brother-mfc-7860dw-running-smoothly-download-and-update-drivers-on-windows/"><u>Keep Your Brother MFC-7860DW Running Smoothly: Download & Update Drivers on Windows</u></a></li>
<li><a href="https://article-tips.techidaily.com/master-the-art-of-conducting-virtual-meetings-with-zoom-win10/"><u>Master the Art of Conducting Virtual Meetings with Zoom (Win10)</u></a></li>
<li><a href="https://windows11.techidaily.com/1719319278608-microsoft-woes-solutions-to-ease-your-way/"><u>Microsoft Woes? Solutions to Ease Your Way</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-digital-era-with-facebook-twitter-instagram-and-youtube/"><u>Navigating the Digital Era with Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://fox-links.techidaily.com/professional-ios-podcast-setup-boost-your-audio-quality-game-for-2024/"><u>Professional iOS Podcast Setup  Boost Your Audio Quality Game for 2024</u></a></li>
<li><a href="https://data-wizards.techidaily.com/recovering-flawed-avi-mov-and-mp4-through-quickplay-action/"><u>Recovering Flawed AVI, MOV & MP4 Through QuickPlay Action</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-10-infinix-smart-8-android-sim-unlock-apk-by-drfone-android/"><u>Top 10 Infinix Smart 8 Android SIM Unlock APK</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/unlock-the-power-of-your-fb-lives-with-these-picks-for-2024/"><u>Unlock the Power of Your Fb Lives with These Picks for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/vivacut-video-editor-complete-review-and-guide-2024/"><u>VivaCut Video Editor – Complete Review and Guide 2024</u></a></li>
<li><a href="https://program-issues.techidaily.com/warzone-and-your-hardware-optimizing-gpu-performance-on-windows-11-devices/"><u>Warzone and Your Hardware: Optimizing GPU Performance on Windows 11 Devices</u></a></li>
</ul></div>
