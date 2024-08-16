---
title: Steps for Windows Backup Configuration Recollection
date: 2024-08-15T15:51:12.892Z
updated: 2024-08-16T15:51:12.892Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps for Windows Backup Configuration Recollection
excerpt: This Article Describes Steps for Windows Backup Configuration Recollection
keywords: Windows Backup Guide,Configuring Backups Windows,System Backup Setup Win,Windows Data Protection,Restore Windows Settings,Recovering Windows Files,Backup & Restore Win
thumbnail: https://thmb.techidaily.com/3be6004f814f322eb7c81e59f5f3e6dc5377a1a28f18fb94887b3ff8d1dce543.jpg
---

## Steps for Windows Backup Configuration Recollection

 System failure or data loss can cause huge amounts of damage and that’s why Windows offers a backup feature to protect your critical data. If your backups corrupt or otherwise function incorrectly, you can reset Windows Backup to its default settings. This guide will teach you some methods to reset Windows Backup to its default on Windows.

## How Do I Know if I Need to Reset Windows Backup?

 You may need to reset Windows Backup if your backups aren't working, taking too long to create, or you can't access the stored files. If you are experiencing these issues, resetting Windows Backup may resolve them.

 For this, either use the Command Prompt or create a batch file. The steps for both methods are outlined below and should help you get your backups running again.

<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->
## Is Resetting Window Backup Risky?

 While resetting Windows Backup is generally safe, there are some risks associated with it.

 Firstly, you may lose all existing backups if you reset Windows Backup. To ensure you don't lose data, [create a backup of the existing Windows files](https://www.makeuseof.com/tag/backup-windows-files-folders/) before resetting Windows Backup.

 Furthermore, the reset may affect some third-party apps. It's wise to check with your software vendor before resetting Windows Backup.

 If something goes wrong during the reset, you may have a corrupted backup configuration. In such cases, reinstall the operating system and start from scratch.

 Overall, resetting Windows Backup helps resolve existing issues, but take the necessary precautions to avoid potential risks.

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Reset Windows Backup to Its Factory Settings

 Now you know how to proceed with caution, here's how to reset Windows Backup to its factory settings.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633309&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/3_premium-icon.png" border="0"> Take advantage of PREMIUM features for 12 months. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Yearly Membership</a>
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
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-creating-hilarious-reactions-mastering-youtube-tricks-3-methods/"><u>[New] In 2024, Creating Hilarious Reactions  Mastering YouTube Tricks (3 Methods)</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-essential-skillset-how-to-execute-screen-recording-on-mac/"><u>[New] In 2024, Essential Skillset  How to Execute Screen Recording on Mac</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-essential-tactics-for-youtube-advertising-with-banners/"><u>[Updated] 2024 Approved  Essential Tactics for YouTube Advertising with Banners</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-mastering-wide-angle-postings-integrating-360-photos-on-mobile-apps-for-2024/"><u>[Updated] Mastering Wide Angle Postings  Integrating 360 Photos on Mobile Apps for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/everything-you-need-to-know-about-lock-screen-settings-on-your-oppo-a38-by-drfone-android/"><u>Everything You Need to Know about Lock Screen Settings on your Oppo A38</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-fatigued-performance-in-win10plusedge-browser/"><u>Fixing Fatigued Performance in Win10+Edge Browser</u></a></li>
<li><a href="https://windows11.techidaily.com/gaming-past-present-atlasos-enablement/"><u>Gaming Past, Present: AtlasOS Enablement</u></a></li>
<li><a href="https://howto.techidaily.com/google-play-services-wont-update-12-fixes-are-here-on-honor-x7b-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Google Play Services Wont Update? 12 Fixes are Here on Honor X7b | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/hidden-screens-revealed-the-most-effective-6-techniques-to-recover-off-screen-apps-in-win/"><u>Hidden Screens Revealed: The Most Effective 6 Techniques to Recover Off-Screen Apps in Win</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-disable-amdnvidia-graphics-ui-extras/"><u>How to Disable AMD/Nvidia Graphics UI Extras</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-ignore-microsofts-app-verification-warnings/"><u>How to Ignore Microsoft's App Verification Warnings</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reactivate-a-unresponsive-windows-start-button/"><u>How to Reactivate a Unresponsive Window's Start Button</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-resolve-offline-printer-problems-in-os/"><u>How To Resolve Offline Printer Problems in OS</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-revert-your-windows-backup-settings/"><u>How To Revert Your Windows Backup Settings</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-k850-ultrahd-samsung-2023-tech-review/"><u>In 2024, K850 UltraHD  Samsung 2023 Tech Review</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-6-appsservices-to-trace-any-vivo-y17s-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, Top 6 Apps/Services to Trace Any Vivo Y17s Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-unlock-your-vivo-t2-pro-5g-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>In 2024, Unlock Your Vivo T2 Pro 5G Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/isolating-and-resolving-unilateral-sound-issue-on-win-os/"><u>Isolating and Resolving Unilateral Sound Issue on WIN OS</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-calculators-dark-scheme/"><u>Mastering Windows Calculator's Dark Scheme</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-reinstate-working-utorrent-installer-in-various-windows-versions/"><u>Methods to Reinstate Working uTorrent Installer in Various Windows Versions</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-setbacks-due-to-recent-windows-installation/"><u>Overcoming Setbacks Due to Recent Windows Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-battlenet-being-inaccessible-in-windows-1011/"><u>Quick Fixes for Battle.net Being Inaccessible in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-fixing-windows-updates-error-xcode-0x80246007/"><u>Solutions for Fixing Windows Updates Error – XCode 0X80246007</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-to-file-transfer-problems-on-windows-1011/"><u>Solutions to File Transfer Problems on Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-failed-page-loading-on-ms-store/"><u>Steps to Resolve Failed Page Loading on MS Store</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-tackle-stranded-error-on-xbox-app-windows-devices/"><u>Steps to Tackle 'Stranded' Error on Xbox App Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-resolve-windows-1110s-nvidia-access-problem/"><u>Strategies to Resolve Windows 11/10'S NVidia Access Problem</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-boot-sequence-customizing-timeout-window-11/"><u>Streamlining Boot Sequence: Customizing Timeout Window 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-collection-of-task-management-tools-for-windows-11-users/"><u>The Ultimate Collection of Task Management Tools for Windows 11 Users</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/top-10plus-best-free-online-video-editors-for-video-editing-online/"><u>Top 10+ Best Free Online Video Editors for Video Editing Online</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-file-download-issues-on-windows-11-6/"><u>Troubleshooting File Download Issues on Windows 11 (6)</u></a></li>
<li><a href="https://windows11.techidaily.com/unchained-gpt-on-your-machine-using-freedomgpt/"><u>Unchained GPT on Your Machine: Using FreedomGPT</u></a></li>
<li><a href="https://windows11.techidaily.com/what-are-windows-bsod-memory-dumps-and-how-can-they-help-you/"><u>What Are Windows BSoD Memory Dumps, and How Can They Help You?</u></a></li>
</ul></div>
