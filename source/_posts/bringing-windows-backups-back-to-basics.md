---
title: Bringing Windows Backups Back to Basics
date: 2024-08-15T15:12:46.663Z
updated: 2024-08-16T15:12:46.663Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Bringing Windows Backups Back to Basics
excerpt: This Article Describes Bringing Windows Backups Back to Basics
keywords: Basic WinBackup Tips,Essential Windows Backup Guide,Fundamentals of WinBackup,Simplifying WinBackup Process,WinBackup Recovery Basics,Easy WinBackup Techniques,Restoring with Simple WinBackup
thumbnail: https://thmb.techidaily.com/c773b247e1e0895c35ac3965c0957524900af663f812d6e184693495dab0728b.jpg
---

## Bringing Windows Backups Back to Basics

 System failure or data loss can cause huge amounts of damage and that’s why Windows offers a backup feature to protect your critical data. If your backups corrupt or otherwise function incorrectly, you can reset Windows Backup to its default settings. This guide will teach you some methods to reset Windows Backup to its default on Windows.

## How Do I Know if I Need to Reset Windows Backup?

 You may need to reset Windows Backup if your backups aren't working, taking too long to create, or you can't access the stored files. If you are experiencing these issues, resetting Windows Backup may resolve them.

 For this, either use the Command Prompt or create a batch file. The steps for both methods are outlined below and should help you get your backups running again.

<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->
## Is Resetting Window Backup Risky?

 While resetting Windows Backup is generally safe, there are some risks associated with it.

 Firstly, you may lose all existing backups if you reset Windows Backup. To ensure you don't lose data, [create a backup of the existing Windows files](https://www.makeuseof.com/tag/backup-windows-files-folders/) before resetting Windows Backup.

 Furthermore, the reset may affect some third-party apps. It's wise to check with your software vendor before resetting Windows Backup.

 If something goes wrong during the reset, you may have a corrupted backup configuration. In such cases, reinstall the operating system and start from scratch.

 Overall, resetting Windows Backup helps resolve existing issues, but take the necessary precautions to avoid potential risks.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Reset Windows Backup to Its Factory Settings

 Now you know how to proceed with caution, here's how to reset Windows Backup to its factory settings.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
### 1\. Using Command Prompt

 If your current backup configuration isn't working, reset Windows Backup to its default settings. To get started, [run the Command Prompt with admin access](https://www.makeuseof.com/windows-run-command-prompt-admin/). In the Command Prompt window, run the following command:

`reg delete HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup /f`

 This will reset to the default configuration and remove all existing backups.

 After that, copy and paste the following command into the Command Prompt window and press **Enter**:

`reg add HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup`

 This will recreate the WindowsBackup entry in the registry editor. Next, type in and run the below command to delete the Automatic Backup scheduled task on Windows:

`schtasks /delete /tn "Microsoft\Windows\WindowsBackup\AutomaticBackup" /f`

 Finally, execute the below command to delete the backup monitor scheduled task:

`schtasks /delete /tn "Microsoft\Windows\WindowsBackup\Windows Backup Monitor" /f`

 After executing the above commands, restart your computer. This will reset Windows Backup to its default settings.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
### 2\. Creating a Batch File

 If you're not comfortable with the command line interface, reset Windows Backup by creating a batch file.

 To do this, [open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) and paste the below code.

`<code>reg delete HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup /f  
reg add HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup  
schtasks /delete /tn "Microsoft\Windows\WindowsBackup\AutomaticBackup" /f  
schtasks /delete /tn "Microsoft\Windows\WindowsBackup\Windows Backup Monitor" /f`

 Click the **File** menu and select **Save as**. On the Save as dialog, type **reset-backup.bat** as the file name. Then choose **All Files** from the drop-down menu next to the Save as type. From the left panel, select **Desktop** and click the **Save** button.

 Now, close the Notepad window and right-click on the batch file. From the context menu, select **Run as administrator**. This will reset Windows Backup to its default settings.

 Lastly, restart your computer and you're done. These are two methods to reset Windows Backup to its default settings.

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get Your Backups Working Again on Windows

 Whether you use the command line interface or create a batch file, it's easy to reset Windows Backup. Just remember to restart your computer after the process completes successfully.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-crafting-an-ideal-speech-translation-experience-in-google/"><u>[New] 2024 Approved  Crafting an Ideal Speech Translation Experience in Google</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-worlds-finest-screen-recording-software-no-deadline/"><u>[New] In 2024, World's Finest Screen Recording Software (No Deadline)</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-command-and-conquer-triumphant-tales-of-the-best-7-total-wars-for-2024/"><u>[Updated] Command & Conquer  Triumphant Tales of the Best 7 Total Wars for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-how-to-add-custom-youtube-shorts-thumbnails-effortlessly/"><u>[Updated] How to Add Custom YouTube Shorts Thumbnails Effortlessly</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-infinite-snaps-ensuring-a-lasting-snapchat-connection/"><u>[Updated] In 2024, Infinite Snaps  Ensuring a Lasting Snapchat Connection</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-in-2024-irreversible-steps-for-a-fixed-tiktok-exit/"><u>[Updated] In 2024, Irreversible Steps for a Fixed TikTok Exit</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-the-gastronomes-blueprint-filming-feasts-for-2024/"><u>[Updated] The Gastronome’s Blueprint  Filming Feasts for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-transitioning-from-srt-to-subtitles/"><u>[Updated] Transitioning From SRT to Subtitles</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-5-best-no-cost-video-enhancement-platforms/"><u>2024 Approved  5 Best No-Cost Video Enhancement Platforms</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-achieving-clear-focus-blurring-videos-on-teams/"><u>2024 Approved  Achieving Clear Focus  Blurring Videos on Teams</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-starry-nights-in-focus-advice-on-night-portraiture/"><u>2024 Approved  Starry Nights in Focus  Advice on Night Portraiture</u></a></li>
<li><a href="https://location-social.techidaily.com/3-things-you-must-know-about-fake-snapchat-location-on-samsung-galaxy-f04-drfone-by-drfone-virtual-android/"><u>3 Things You Must Know about Fake Snapchat Location On Samsung Galaxy F04 | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-oppo-reno-11-pro-5g-by-drfone-android/"><u>AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Oppo Reno 11 Pro 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-turn-off-hardware-assisted-gpgpus-on-widno/"><u>Essential Guide: Turn Off Hardware-Assisted GPGPUs on WIDNO</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-for-win11-defender-firewall-control/"><u>Essential Tips for Win11 Defender Firewall Control</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tactics-to-unite-windows-directories/"><u>Expert Tactics to Unite Windows Directories</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-print-server-not-responding-issue/"><u>Fixing Print Server Not Responding Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/gauge-your-windows-workhorse-power-efficiency-explored/"><u>Gauge Your Window's Workhorse - Power Efficiency Explored</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-abnormal-character-output-windows-wise/"><u>Handling Abnormal Character Output Windows-Wise</u></a></li>
<li><a href="https://windows11.techidaily.com/harmonizing-operations-combining-windows-11-and-tablet-for-peak-efficiency/"><u>Harmonizing Operations: Combining Windows 11 & Tablet for Peak Efficiency</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-preparation-to-beat-giovani-in-pokemon-go-for-asus-rog-phone-7-ultimate-drfone-by-drfone-virtual-android/"><u>In 2024, Preparation to Beat Giovani in Pokemon Go For Asus ROG Phone 7 Ultimate | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/keeping-windows-time-set-unaltered-by-users/"><u>Keeping Windows' Time Set Unaltered by Users</u></a></li>
<li><a href="https://windows11.techidaily.com/launching-home-screen-in-windows-11-easily/"><u>Launching Home Screen in Windows 11 Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-hardware-space-exploring-disks-in-w10-and-w11/"><u>Mastering Hardware Space: Exploring Disks in W10 & W11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11-showhide-system-directories/"><u>Mastering Windows 11: Show/Hide System Directories</u></a></li>
<li><a href="https://windows11.techidaily.com/method-to-turn-off-geforce-graphic-overlay-on-pc/"><u>Method to Turn Off GeForce Graphic Overlay on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-to-safest-win-friendly-free-software-deals/"><u>Navigating to Safest Win-Friendly Free Software Deals</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-non-detected-proxy-setup/"><u>Navigating Windows Non-Detected Proxy Setup</u></a></li>
<li><a href="https://howto.techidaily.com/play-store-stuck-on-downloading-of-zte-nubia-flip-5g-7-ways-to-resolve-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Stuck on Downloading Of ZTE Nubia Flip 5G? 7 Ways to Resolve | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-disabled-graphics-on-steam-os/"><u>Quick Fixes for Disabled Graphics on Steam OS</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-tip-erasing-microsoft-edge-on-windows-11/"><u>Quick Tip: Erasing Microsoft Edge on Windows 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-lost-data-from-oppo-reno-9a-by-fonelab-android-recover-data/"><u>Recover lost data from Oppo Reno 9A</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-sequence-errors-for-running-tasks-windows-guide/"><u>Resolving Sequence Errors for Running Tasks: Windows Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/revitalize-your-search-on-windows-11-11-key-fixes-included/"><u>Revitalize Your Search on Windows 11: 11 Key Fixes Included</u></a></li>
<li><a href="https://windows11.techidaily.com/screen-recording-and-audio-integration-the-ultimate-guide-to-the-snipping-tool-max-156/"><u>Screen Recording & Audio Integration: The Ultimate Guide to the Snipping Tool (Max 156)</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-address-non-successful-disco-update-windows-errors/"><u>Steps to Address Non-Successful Disco Update Windows Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-revive-frozen-windows-terminal-apps/"><u>Strategies to Revive Frozen Windows Terminal Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/strategizing-onedrives-positioning-within-windows-directory-space/"><u>Strategizing OneDrive's Positioning Within Windows Directory Space</u></a></li>
<li><a href="https://fox-access.techidaily.com/the-complete-guide-to-help-you-convert-srt-to-xml-ssa-ttml-and-othe/"><u>The Complete Guide to Help You Convert SRT to XML, SSA, TTML, and Othe</u></a></li>
<li><a href="https://windows11.techidaily.com/the-hidden-the-forgotten-now-revealed-restoring-your-windows-on-win10win11/"><u>The Hidden, The Forgotten, Now Revealed: Restoring Your Windows on Win10/Win11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/the-newcomers-guide-to-youtube-channel-setup-and-money-making-tips-for-2024/"><u>The Newcomer’s Guide to YouTube  Channel Setup & Money-Making Tips for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-resolving-windows-disk-management-crashes/"><u>Tips: Resolving Windows Disk Management Crashes</u></a></li>
<li><a href="https://windows11.techidaily.com/title-personalize-your-winos-desktop-space-configuration/"><u>Title: Personalize Your WINOS Desktop Space Configuration</u></a></li>
<li><a href="https://tech-revival.techidaily.com/top-innovative-open-source-ai-art-makers/"><u>Top Innovative Open Source AI Art Makers</u></a></li>
<li><a href="https://windows11.techidaily.com/transforming-chaos-organizing-with-windows-11-calendar/"><u>Transforming Chaos: Organizing with Windows 11 Calendar</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-vlc-lag-on-windows-devices/"><u>Troubleshooting VLC Lag on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-unraveling-color-management-issues/"><u>Troubleshooting Windows: Unraveling Color Management Issues</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ultimate-guide-to-get-the-meltan-box-pokemon-go-for-oppo-k11x-drfone-by-drfone-virtual-android/"><u>Ultimate guide to get the meltan box pokemon go For Oppo K11x | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/ultimate-tutorial-adding-straight-lines-in-microsoft-word-efficiently/"><u>Ultimate Tutorial: Adding Straight Lines in Microsoft Word Efficiently</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-quick-deletion-windows-customization-for-instant-removal/"><u>Unleashing Quick Deletion: Windows Customization for Instant Removal</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-windows-0x80242016-update-issue/"><u>Unraveling Window's 0X80242016 Update Issue</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/what-is-an-ai-script-generator-wondershare-virbo-glossary/"><u>What Is an AI Script Generator? | Wondershare Virbo Glossary</u></a></li>
</ul></div>
