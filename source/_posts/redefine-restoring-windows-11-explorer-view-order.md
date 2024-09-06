---
title: "Redefine: Restoring Windows 11 Explorer View Order"
date: 2024-09-05T02:08:03.366Z
updated: 2024-09-06T02:08:03.366Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Redefine: Restoring Windows 11 Explorer View Order"
excerpt: "This Article Describes Redefine: Restoring Windows 11 Explorer View Order"
keywords: Win11ExplorerViewOrder,RewindWindowsView,ExploreWin11Order,ReorderWin11Explorer,WindowsRestoreView,ViewOrderResetWin11,ExplorerViewReboot
thumbnail: https://thmb.techidaily.com/0c50e9701859daef27aa4fad4bc3c104584c3b31a6d296c6daba235eb751bb08.jpg
---

## Redefine: Restoring Windows 11 Explorer View Order

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
7. From the left pane, select**Desktop** as the location.
8. Then click**Save** and close the text editor window.
9. Finally, double-click the batch file you created, and it will reset your Folder View Settings to the default view.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896510/19272" target="_top" id="1896510">
  <img src="//a.impactradius-go.com/display-ad/19272-1896510" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896510/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. Reset Folder View Settings to Default via File Explorer

 If you only need to reset the View Settings of all folders of the same type, this method is for you. Here's what you have to do:

1. Click on Start and search for**File Explorer Options** . To learn more about it, see our guide on[how to open the Folder Options on Windows](https://www.makeuseof.com/windows-10-open-folder-options/) .
2. Now, select the**View** tab in the top bar and tap on**Reset Folders** .  
![Reset Folder View Settings to Default Via File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-via-file-explorer.jpg)
3. Click**Yes** when prompted to confirm your action.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123737/7443" target="_top" id="2123737">
  <img src="//a.impactradius-go.com/display-ad/7443-2123737" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123737/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Finally, hit**OK** and the window will close.

 This will reset your Folder View Settings to Windows' default settings.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918684/19272" target="_top" id="1918684">
  <img src="//a.impactradius-go.com/display-ad/19272-1918684" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918684/19272" style="position:absolute;visibility:hidden;" border="0" />
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
5. Click**Yes** when asked to confirm your action.
<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657386/16446" target="_top" id="1657386">
  <img src="//a.impactradius-go.com/display-ad/16446-1657386" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657386/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Similarly, delete the**Bags** folder and close the Registry window.

<!-- affiliate ads begin -->
<span id="1982457">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982457.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982457">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982457.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982457%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982457/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-data.techidaily.com/024-approved-elevate-your-youtube-content-seo-methods-revealed/"><u>[New] 2024 Approved  Elevate Your YouTube Content  SEO Methods Revealed</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-essential-low-cost-digital-video-capture-software/"><u>[New] 2024 Approved  Essential Low-Cost Digital Video Capture Software</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-a-step-by-step-guide-to-creating-compelling-instagram-puzzles/"><u>[New] In 2024, A Step-by-Step Guide to Creating Compelling Instagram Puzzles</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-precision-in-reducing-image-size-the-essential-guide-to-thumbnails/"><u>[New] In 2024, Precision in Reducing Image Size  The Essential Guide to Thumbnails</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-ultimate-guide-to-live-streaming-fb-on-laptops-macs-and-pcs/"><u>[New] In 2024, Ultimate Guide to Live Streaming FB on Laptops, Macs, and PCs</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-premium-audio-narrative-compositions/"><u>[New] Premium Audio Narrative Compositions</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-ultimate-2024-vista-into-vivacuts-video-editing-world/"><u>[New] The Ultimate 2024 Vista Into VivaCut's Video Editing World</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-box-it-up-the-top-10-online-houses-for-customized-gift-boxes/"><u>[Updated] Box It Up! The Top 10 Online Houses for Customized Gift Boxes</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-disseminate-vimeo-videos-widely/"><u>[Updated] In 2024, Disseminate Vimeo Videos Widely</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-in-depth-analysis-calculating-your-podcasts-cost/"><u>[Updated] In-Depth Analysis  Calculating Your Podcast's Cost</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-peek-at-all-shared-images-and-videos-in-chats/"><u>[Updated] Peek at All Shared Images & Videos in Chats</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-the-blueprint-for-virtual-business-growth-for-2024/"><u>[Updated] The Blueprint for Virtual Business Growth for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-ultimate-psd-style-boosting/"><u>[Updated] Ultimate PSD Style Boosting</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unlock-the-secrets-of-effortless-editing-for-windows-11-videos/"><u>[Updated] Unlock the Secrets of Effortless Editing for Windows 11 Videos</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-full-reviewed-evaluation-hero4-black-capabilities/"><u>2024 Approved  Full Reviewed Evaluation  Hero4 Black Capabilities</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-preserving-periscope-content-tips-from-the-pros/"><u>2024 Approved  Preserving Periscope Content  Tips From the Pros</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/daily-dose-of-latvian-mastering-in-under-an-hour/"><u>Daily Dose of Latvian: Mastering in Under an Hour</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/detailed-review-of-doctorsim-unlock-service-for-iphone-15-by-drfone-ios/"><u>Detailed Review of doctorSIM Unlock Service For iPhone 15</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-fixes-for-unresponsive-windows-defender-security-shield/"><u>Essential Fixes for Unresponsive Windows Defender Security Shield</u></a></li>
<li><a href="https://windows11.techidaily.com/explore-extreme-device-integration-the-power-of-galaxys-dex-app/"><u>Explore Extreme Device Integration: The Power of Galaxy's DeX App</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-network-issues-with-anydesk-in-win11/"><u>Fixing Network Issues with AnyDesk in WIn11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-do-you-play-mov-files-on-samsung-galaxy-a25-5g-by-aiseesoft-video-converter-play-mov-on-android/"><u>How do you play .mov files on Samsung Galaxy A25 5G ?</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-remedy-the-usb-attachment-failure-in-virtualbox-instantly/"><u>How to Remedy the USB Attachment Failure in VirtualBox Instantly</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-turn-off-windows-surveillance-features/"><u>How To Turn Off Windows Surveillance Features</u></a></li>
<li><a href="https://windows11.techidaily.com/iis-mastery-guide-navigating-with-ease-and-speed/"><u>IIS Mastery Guide: Navigating with Ease and Speed</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-catchemall-celebrate-national-pokemon-day-with-virtual-location-on-apple-iphone-13-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, CatchEmAll Celebrate National Pokémon Day with Virtual Location On Apple iPhone 13 Pro | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-can-we-unlock-our-lenovo-thinkphone-phone-screen-by-drfone-android/"><u>In 2024, How Can We Unlock Our Lenovo ThinkPhone Phone Screen?</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-how-to-securely-download-youtubes-srt-subtitles/"><u>In 2024, How to Securely Download YouTube's SRT Subtitles</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-interactive-subscription-buttons-filmoras-guide-to-animated-sign-up-bars/"><u>In 2024, Interactive Subscription Buttons - Filmora's Guide to Animated Sign-Up Bars</u></a></li>
<li><a href="https://windows11.techidaily.com/keyboard-command-guide-to-streamline-win-11s-voice-input/"><u>Keyboard Command Guide to Streamline Win 11'S Voice Input</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-android-windows-integration-for-webcams/"><u>Mastering Android-Windows Integration for Webcams</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-rdp-troubleshooting-in-windows-oses/"><u>Mastering RDP Troubleshooting in Windows OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/microsoft-operatives-select-6-best-usage-trackers-for-windows/"><u>Microsoft Operatives: Select 6 Best Usage Trackers for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-new-era-of-win-pc-memory-capacity/"><u>Navigating the New Era of Win PC Memory Capacity</u></a></li>
<li><a href="https://windows11.techidaily.com/organizing-ideas-visual-note-taking-using-obsidian/"><u>Organizing Ideas: Visual Note-Taking Using Obsidian</u></a></li>
<li><a href="https://windows11.techidaily.com/power-through-print-settings-in-win11-quick-guide-max-48-chars/"><u>Power Through Print Settings in Win11 - Quick Guide (Max 48 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/proactive-pc-management-keeping-windows-11s-amd-drivers-current/"><u>Proactive PC Management: Keeping Windows 11'S AMD Drivers Current</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-recovery-actions-save-vanished-windows-content/"><u>Quick Recovery Actions: Save Vanished Windows Content</u></a></li>
<li><a href="https://windows11.techidaily.com/quickly-restart-print-spool-in-windows/"><u>Quickly Restart Print Spool in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/reconfiguring-system-settings-managed-by-your-organization-on-windows-11/"><u>Reconfiguring System Settings Managed by Your Organization on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-non-responsive-windows-netflix-application/"><u>Resolving Non-Responsive Windows Netflix Application</u></a></li>
<li><a href="https://windows11.techidaily.com/secrets-resolving-uncontrolled-mouse-jitter-in-win11/"><u>Secrets: Resolving Uncontrolled Mouse Jitter in Win11</u></a></li>
<li><a href="https://data-recovery.techidaily.com/solving-the-puzzle-a-step-by-step-guide-to-resolve-iphones-error-14/"><u>Solving the Puzzle: A Step-by-Step Guide to Resolve iPhone's Error 14</u></a></li>
<li><a href="https://windows11.techidaily.com/stepping-up-stalled-safety-settings-on-win-11/"><u>Stepping Up Stalled Safety Settings on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/stepwise-strategy-to-erase-wsl-from-windows-11-operating-system/"><u>Stepwise Strategy to Erase WSL From Windows 11 Operating System</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-windows-update-failures-with-these-fixes/"><u>Stop Windows Update Failures with These Fixes</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/stop-your-display-from-blinking-tips-and-tricks/"><u>Stop Your Display From Blinking: Tips & Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-coding-process-essential-wsl-2-tips-and-tricks-for-dev/"><u>Streamline Coding Process: Essential WSL 2 Tips and Tricks for Dev</u></a></li>
<li><a href="https://driver-error.techidaily.com/streamlined-methods-for-faulty-mtp-usbs/"><u>Streamlined Methods for Faulty MTP USBs</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-system-recovery-focus-on-net-max-156/"><u>Streamlining System Recovery: Focus on .NET (Max 156)</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-solutions-to-overcome-onedrives-immediate-folder-addition-error/"><u>Swift Solutions to Overcome OneDrive's Immediate Folder Addition Error</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-non-installed-disk-errors-in-win-11-with-ease-and-simplicity/"><u>Tackling Non-Installed Disk Errors in Win 11 with Ease and Simplicity</u></a></li>
<li><a href="https://windows11.techidaily.com/the-insiders-guide-accessing-onedrive-offline-on-windows/"><u>The Insider's Guide: Accessing OneDrive Offline on WINDOWS</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-tech-review-your-guide-to-the-latest-in-computer-hardware/"><u>Tom's Tech Review: Your Guide to the Latest in Computer Hardware</u></a></li>
<li><a href="https://driver-download.techidaily.com/troubleshooting-and-installing-huion-printertablet-drivers-in-windows-os/"><u>Troubleshooting and Installing Huion Printer/Tablet Drivers in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/understated-applications-the-real-throttlers-of-pc-performance/"><u>Understated Applications: The Real Throttlers of PC Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-smooth-gaming-on-windows-eradicate-errors/"><u>Unleash Smooth Gaming on Windows, Eradicate Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-divine-control-windows-11s-spiritual-command-center-guide/"><u>Unlocking Divine Control: Windows 11'S Spiritual Command Center Guide</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unlocking-the-potential-of-closeup-cinematography-for-2024/"><u>Unlocking the Potential of Closeup Cinematography for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-best-top-7-no-cost-password-tools-for-win-users/"><u>Unveiling the Best: Top 7 No-Cost Password Tools for Win Users</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-free-wmv-video-stitching-tools-expert-recommendations/"><u>Updated Free WMV Video Stitching Tools Expert Recommendations</u></a></li>
<li><a href="https://windows11.techidaily.com/waking-up-the-watches-5-fixes-for-lost-windows-server-time/"><u>Waking Up the Watches: 5 Fixes for Lost Windows Server Time</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-terminal-the-art-of-color-selection/"><u>Windows Terminal: The Art of Color Selection</u></a></li>
<li><a href="https://windows11.techidaily.com/winrar-archive-integrity-preventing-checksum-error-messages/"><u>WinRAR Archive Integrity: Preventing Checksum Error Messages</u></a></li>
<li><a href="https://vp-tips.techidaily.com/your-companion-in-choosing-high-grade-hdr-cameras-for-2024/"><u>Your Companion in Choosing High-Grade HDR Cameras for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/zip-file-chameleon-techniques-for-windows-images/"><u>ZIP File Chameleon Techniques for Windows Images</u></a></li>
</ul></div>
