---
title: Restoring Windows Backup to Original Settings
date: 2024-08-15T16:13:40.727Z
updated: 2024-08-16T16:13:40.727Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Windows Backup to Original Settings
excerpt: This Article Describes Restoring Windows Backup to Original Settings
keywords: Windows Restore Options,System Recovery Tool,Data Backup Reinstall,Default Settings Restore,PC Factory Reset,OS Configuration Overhaul,Backup to Original Setup
thumbnail: https://thmb.techidaily.com/d8f2922d20e310fe909f77a8d8b81c6fbacf60f301e5bf6586c75f1b0b08c5ac.jpeg
---

## Restoring Windows Backup to Original Settings

 System failure or data loss can cause huge amounts of damage and that’s why Windows offers a backup feature to protect your critical data. If your backups corrupt or otherwise function incorrectly, you can reset Windows Backup to its default settings. This guide will teach you some methods to reset Windows Backup to its default on Windows.

## How Do I Know if I Need to Reset Windows Backup?

 You may need to reset Windows Backup if your backups aren't working, taking too long to create, or you can't access the stored files. If you are experiencing these issues, resetting Windows Backup may resolve them.

 For this, either use the Command Prompt or create a batch file. The steps for both methods are outlined below and should help you get your backups running again.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Is Resetting Window Backup Risky?

 While resetting Windows Backup is generally safe, there are some risks associated with it.

 Firstly, you may lose all existing backups if you reset Windows Backup. To ensure you don't lose data, [create a backup of the existing Windows files](https://www.makeuseof.com/tag/backup-windows-files-folders/) before resetting Windows Backup.

 Furthermore, the reset may affect some third-party apps. It's wise to check with your software vendor before resetting Windows Backup.

 If something goes wrong during the reset, you may have a corrupted backup configuration. In such cases, reinstall the operating system and start from scratch.

 Overall, resetting Windows Backup helps resolve existing issues, but take the necessary precautions to avoid potential risks.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->
## How to Reset Windows Backup to Its Factory Settings

 Now you know how to proceed with caution, here's how to reset Windows Backup to its factory settings.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
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
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-cut-the-clutter-advanced-techniques-for-cam-recordings/"><u>[New] 2024 Approved  Cut the Clutter  Advanced Techniques for Cam Recordings</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/024-approved-open-source-banner-resources-a-gift-to-youtubers/"><u>[New] 2024 Approved  Open Source Banner Resources  A Gift to YouTubers</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-swipe-up-for-a-dose-of-self-reflection-curated-instagramcaptions/"><u>[New] 2024 Approved  Swipe up for a Dose of Self-Reflection - Curated #InstagramCaptions</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-explore-unexpectedly-great-meme-pages-on-facebook/"><u>[New] Explore  Unexpectedly Great Meme Pages on Facebook</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-free-music-unlocked-the-ultimate-library-for-videographers-for-2024/"><u>[New] Free Music Unlocked  The Ultimate Library for Videographers for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-how-marketers-should-use-hashtags-on-facebook-properly-for-2024/"><u>[New] How Marketers Should Use Hashtags on Facebook Properly for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-in-2024-creating-immersive-experiences-best-practices-for-vr-filming-top-9/"><u>[New] In 2024, Creating Immersive Experiences  Best Practices for VR Filming (Top 9)</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-unveiling-8-best-tools-for-youtube-to-avi-conversion/"><u>[New] Unveiling 8 Best Tools for YouTube to AVI Conversion</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-saving-scenes-a-rundown-of-the-best-facebook-extensions/"><u>[Updated] 2024 Approved  Saving Scenes  A Rundown of the Best Facebook Extensions</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-tailoring-your-videography-with-personalized-instagram-captions/"><u>[Updated] 2024 Approved  Tailoring Your Videography with Personalized Instagram Captions</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-audio-capture-made-easy-in-windows-10/"><u>[Updated] Audio Capture Made Easy in Windows 10</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-crafting-impact-best-9-video-thumbnail-makers-reviewed/"><u>[Updated] In 2024, Crafting Impact  Best 9 Video Thumbnail Makers Reviewed</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-mastery-of-playback-essential-skills-in-ps3-recording/"><u>[Updated] Mastery of Playback  Essential Skills in PS3 Recording</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-navigating-the-world-of-pixiz-turning-stills-into-storytelling-video/"><u>[Updated] Navigating the World of Pixiz  Turning Stills Into Storytelling Video</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-the-ultimate-guide-to-preserving-itunes-content/"><u>2024 Approved  The Ultimate Guide to Preserving iTunes Content</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-peak-productivity-essential-windows-11-and-cmd-commands/"><u>Achieve Peak Productivity: Essential Windows 11 & Cmd Commands</u></a></li>
<li><a href="https://extra-information.techidaily.com/best-picture-preview-compilation-for-2024/"><u>Best Picture Preview Compilation for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/circumventing-driver-checks-in-windows-no-signatures-any-installation/"><u>Circumventing Driver Checks in Windows: No Signatures, Any Installation</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-fix-resolving-the-troublesome-windows-10-update-error-0x80240034/"><u>Comprehensive Fix: Resolving the Troublesome Windows 10 Update Error 0X80240034</u></a></li>
<li><a href="https://windows11.techidaily.com/controlling-registry-tools-access-on-windows-11/"><u>Controlling Registry Tools Access on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/crystal-clear-in-minutes-mastering-fuzzy-window-fixes/"><u>Crystal Clear in Minutes: Mastering Fuzzy Window Fixes</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/display-chip-functionality-restored-after-interruption/"><u>Display Chip Functionality Restored After Interruption</u></a></li>
<li><a href="https://driver-download.techidaily.com/download-drivers-for-canon-pixus-mf8500c-printer-on-windows-7-81-and-10-step-by-step-guide/"><u>Download Drivers for Canon PIXUS MF8500C Printer on Windows 7, 8.1 & 10: Step-by-Step Guide</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/enhance-your-content-creating-engaging-loop-videos-for-ig/"><u>Enhance Your Content  Creating Engaging Loop Videos for IG</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-performance-reducing-background-processes/"><u>Enhancing Performance: Reducing Background Processes</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-windows-11-ease-of-use-with-improved-run-feature/"><u>Enhancing Windows 11 Ease of Use with Improved Run Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-command-prompt-tactics-for-registry-optimization/"><u>Expert Command Prompt Tactics for Registry Optimization</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-loss-of-internet-router-webpage-in-windows/"><u>Fixing Loss of Internet Router Webpage in Windows</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/full-guide-on-mirroring-your-oppo-reno-10-proplus-5g-to-your-pcmac-drfone-by-drfone-android/"><u>Full Guide on Mirroring Your Oppo Reno 10 Pro+ 5G to Your PC/Mac | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-cast-infinix-zero-30-5g-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>How to Cast Infinix Zero 30 5G Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-instantly-generate-multiple-directories-in-modern-windows-environments/"><u>How to Instantly Generate Multiple Directories in Modern Windows Environments</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-remove-google-frp-lock-on-honor-x50iplus-by-drfone-android-unlock-remove-google-frp/"><u>How to remove Google FRP Lock on Honor X50i+</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-seamlessly-update-the-epson-wf/"><u>How to Seamlessly Update the Epson WF-</u></a></li>
<li><a href="https://techidaily.com/how-to-update-or-downgrade-apple-iphone-13-mini-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade Apple iPhone 13 mini Without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/illuminating-windows-11-tray-and-secret-icons/"><u>Illuminating Windows 11 Tray & Secret Icons</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-methods-to-mirror-itel-p55-5g-to-roku-drfone-by-drfone-android/"><u>In 2024, 3 Methods to Mirror Itel P55 5G to Roku | Dr.fone</u></a></li>
<li><a href="https://fox-glue.techidaily.com/in-2024-5-best-live-streaming-software-for-mac-you-must-know/"><u>In 2024, 5 Best Live Streaming Software for Mac You Must Know</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-all-you-need-to-know-about-mega-greninja-for-nubia-red-magic-8s-pro-drfone-by-drfone-virtual-android/"><u>In 2024, All You Need To Know About Mega Greninja For Nubia Red Magic 8S Pro | Dr.fone</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-digital-picture-perfect-with-audio-touches/"><u>In 2024, Digital Picture Perfect with Audio Touches</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-minuscule-cinematic-design/"><u>In 2024, Minuscule Cinematic Design</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-navigating-the-maze-of-youtube-short-mistakes/"><u>In 2024, Navigating the Maze of YouTube Short Mistakes</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-pro-level-playback-advanced-techniques-for-capturing-minecraft-games-on-mac/"><u>In 2024, Pro-Level Playback  Advanced Techniques for Capturing Minecraft Games on Mac</u></a></li>
<li><a href="https://windows11.techidaily.com/jump-over-the-endless-update-hurdle-quick-fixes-now/"><u>Jump Over The Endless Update Hurdle: Quick Fixes Now</u></a></li>
<li><a href="https://win-howtos.techidaily.com/keyboard-navigation-downfall-restore-function-to-up-down-left-and-right-arrows-now/"><u>Keyboard Navigation Downfall: Restore Function to Up, Down, Left & Right Arrows Now!</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-execution-descriptor-labels-in-software/"><u>Leveraging Execution Descriptor Labels in Software</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-jdk-installation-for-windows-11-users/"><u>Mastering JDK Installation for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-win11-avoid-and-fix-0x0-error-instantly/"><u>Mastering Win11: Avoid and Fix 0X0 Error Instantly</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-on-the-horizon-learning-classic-diablo/"><u>Mastery on the Horizon: Learning Classic Diablo</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/merging-made-easy-the-top-5-free-online-video-combination-tools-for-2024/"><u>Merging Made Easy The Top 5 Free Online Video Combination Tools for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/method-rectifying-disks-not-available-on-windows-pcs/"><u>Method: Rectifying Disks Not Available on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/mitigating-critical-programming-issues-in-roblox/"><u>Mitigating Critical Programming Issues in Roblox</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-repeated-sign-in-requests-for-team-collaboration-software/"><u>Overcoming Repeated Sign-In Requests for Team Collaboration Software</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-sluggishness-in-windows-discord-app/"><u>Overcoming Sluggishness in Windows Discord App</u></a></li>
<li><a href="https://windows11.techidaily.com/perfectly-pivoting-to-windows-11-in-place-strategies/"><u>Perfectly Pivoting to Windows 11: In-Place Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/procedures-to-disregard-the-your-license-will-end-alert/"><u>Procedures to Disregard the Your License Will End Alert</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-troubleshooting-guide-no-audio-output-error/"><u>Quick Troubleshooting Guide: No Audio Output Error</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-the-process-termination-failure-error-window/"><u>Remedying the 'Process Termination Failure' Error Window</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/1722874570235-resetting-your-kindle-paperwhites-time-zone-and-hour-easy-instructions-inside/"><u>Resetting Your Kindle Paperwhite's Time Zone and Hour – Easy Instructions Inside!</u></a></li>
<li><a href="https://windows11.techidaily.com/resolve-cannot-open-error-on-closed-folders-in-microsoft-mail-for-pc/"><u>Resolve Cannot Open Error on Closed Folders in Microsoft Mail for PC</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-steam-game-locks-in-windows-environment/"><u>Resolving Steam Game Locks in Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/reworking-default-view-of-task-manager-in-win11/"><u>Reworking Default View of Task Manager in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/steady-your-pc-controlling-high-cpu-load-with-windows-resource-tool/"><u>Steady Your PC: Controlling High CPU Load With Window's Resource Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-customizing-your-windows-11-notepad-appearance/"><u>Step-by-Step: Customizing Your Windows 11 Notepad Appearance</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-discords-auto-activation-at-pc-boot-sequence/"><u>Stop Discord's Auto-Activation at PC Boot Sequence</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-solutions-for-dotnet-health-in-pcs-max-156/"><u>Swift Solutions for DotNet Health in PCs (Max 156)</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-frustration-with-non-responsive-photoshop/"><u>Tackling Frustration with Non-Responsive Photoshop</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-screenscape-designing-distinctive-displays-on-each-window-of-win-1011/"><u>Tailored Screenscape: Designing Distinctive Displays on Each Window of Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-break-the-bond-onedrive-from-ms-account-on-windows/"><u>Techniques to Break the Bond: OneDrive From MS Account on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-fine-tuning-windows-11-alerts/"><u>The Art of Fine-Tuning Windows 11 Alerts</u></a></li>
<li><a href="https://windows11.techidaily.com/the-insiders-guide-to-bluescreenview-execution/"><u>The Insider’s Guide to BlueScreenView Execution</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-the-best-encoding-methods-on-pc/"><u>Understanding the Best Encoding Methods on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-the-angle-game-rotate-images-in-6-steps-w11/"><u>Winning the Angle Game: Rotate Images in 6 Steps W11</u></a></li>
</ul></div>
