---
title: Can You Get Rid of the Windows ~BT Directories?
date: 2024-08-15T15:57:46.525Z
updated: 2024-08-16T15:57:46.525Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Can You Get Rid of the Windows ~BT Directories?
excerpt: This Article Describes Can You Get Rid of the Windows ~BT Directories?
keywords: Eliminate Windows BT Folders,Remove BT Directory Files,Delete BT System Files,Cleanup BT Temp Directories,Erase Windows BT Data,Clear BT File Cache,Uninstall BT Templates
thumbnail: https://thmb.techidaily.com/cbf529e05dd3135fe67a52edb00f230c5ea15121620c8f38c53b6edc4bb0734a.jpg
---

## Can You Get Rid of the Windows ~BT Directories?

 Deleting the hidden "$Windows.\~BT" folder and recovering gigabytes of space on your hard drive is tempting. But what is this cryptically named folder for, and how critical is it to your Windows installation?

## What Is the “$Windows.\~BT” Folder, and Should You Delete It?

 Windows creates the "$Windows.\~BT" folder when you upgrade the operating system to a newer build. This folder contains all the essential files for the upgrade process, like temporary installation files and logs from the previous Windows installation.

 Windows automatically removes the "$Windows.\~BT" folder after 10 days. As manually deleting this folder will [remove old Windows installation files](https://www.makeuseof.com/tag/delete-old-windows-update-files/), you won't be able to roll back to the previous Windows build using the **Go back** option in the Recovery menu within that time (for example, to [downgrade from Windows 11 to Windows 10](https://www.makeuseof.com/windows-11-downgrade-to-windows-10/)). Hence, you should only get rid of this folder if you are satisfied with the current Windows build on your PC. You can also safely delete the massive folder if Windows fails to do it automatically after the grace period.

 But you shouldn't just delete this hidden folder like any other folder on the desktop. Instead, you should turn to the Disk Cleanup tool or the Command Prompt.

<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Find and Delete the "$Windows.\~BT" Folder

 As "$Windows.\~BT" is a hidden folder, you need to [configure Windows to show hidden files and folders](https://www.makeuseof.com/windows-11-show-hidden-files-folders/) to find it in File Explorer. Once you do, the **C:\\$Windows.\~BT** directory will become visible.

 You can’t delete the "$Windows.\~BT" folder directly, though. To do so, you need to run the Disk Cleanup tool. Here's how:

1. Press **Win + R** to open the Run dialog box.
2. Type **cleanmgr** in the box and press **Enter**.
3. Use the dropdown menu to select the system drive (usually **C:**) and click **OK**.
4. Click the **Clean up system files** button.
5. Under **Files to delete**, use the checkboxes to select these options: **Previous Windows Installations**, **Windows Update Cleanup**, **Windows upgrade log files**, **Temporary Windows installation files**, and **Temporary files**.
6. Click **OK**.
7. Choose **Delete Files** to confirm.  
![Delete the $Windows.~BT Folder Using the Disk Cleanup Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/delete-the-windows-bt-folder-using-the-disk-cleanup-tool.jpg)
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If the "$Windows.\~BT" folder shows up even after you run the Disk Cleanup tool, you'll need to execute a few commands in Command Prompt. For that, [open Command Prompt with administrative rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) and then run the following commands one by one.

`takeown /F C:\$Windows.~BT\* /R /A
icacls C:\$Windows.~BT\*.* /T /grant administrators:F
rmdir /S /Q C:\$Windows.~BT\`

 Once you run the above commands, the "$Windows.\~BT" folder will be deleted for good.

 Now that you understand the purpose of the "$Windows.\~BT" folder, you can decide how to handle it. Beyond the "$Windows.\~BT" folder, you may also come across folders like "Windows.old," "$WinREAgent," "$SysReset," and others which can also be deleted safely using the Disk Cleanup tool.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-techniques.techidaily.com/new-how-to-remove-image-background-with-photopea/"><u>[New] How to Remove Image Background With Photopea</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-in-2024-quintessential-5-for-elevated-slow-videos/"><u>[New] In 2024, Quintessential 5 for Elevated Slow Videos</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-the-quintessential-quest-for-stories-worlds-best-1-8-schools/"><u>[New] The Quintessential Quest for Stories – World's Best #1-#8 Schools</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-yuneec-typhoon-h-review/"><u>[New] Yuneec Typhoon H Review</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-2024-approved-crystal-clarity-in-depth-comparison-of-premium-8k-monitors/"><u>[Updated] 2024 Approved  Crystal Clarity  In-Depth Comparison of Premium 8K Monitors</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-c-span-archive-download-legally-without-expense/"><u>[Updated] C-Span Archive  Download Legally Without Expense</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-cross-border-tech-assessment-by-experts-for-2024/"><u>[Updated] Cross-Border Tech Assessment by Experts for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-reimagine-your-storytelling-with-smartly-scaled-instagram-videos/"><u>[Updated] Reimagine Your Storytelling with Smartly Scaled Instagram Videos</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-ultimate-png-alterations-guide/"><u>[Updated] Ultimate PNG Alterations Guide</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-ultimate-selection-of-video-capture-tools-for-streaming/"><u>2024 Approved  Ultimate Selection of Video Capture Tools for Streaming</u></a></li>
<li><a href="https://windows11.techidaily.com/5-great-free-podcast-editing-programs-for-windows/"><u>5 Great Free Podcast Editing Programs for Windows</u></a></li>
<li><a href="https://howto.techidaily.com/8-ultimate-fixes-for-google-play-your-itel-a70-isnt-compatible-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Ultimate Fixes for Google Play Your Itel A70 Isnt Compatible | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/accessing-the-internet-without-a-browser-post-setup/"><u>Accessing the Internet Without a Browser Post-Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-a-clean-desktop-with-automatic-trash-emptying-in-windows/"><u>Achieve a Clean Desktop with Automatic Trash Emptying in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-crisp-visuals-leveraging-background-blur-in-w11s-photos-app/"><u>Achieve Crisp Visuals: Leveraging Background Blur in W11's Photos App</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-cpu-overload-with-wmi-service-tweaks/"><u>Addressing Cpu Overload with WMI Service Tweaks</u></a></li>
<li><a href="https://windows11.techidaily.com/automating-windows-auditory-restart-post-boot-issue/"><u>Automating Windows Auditory Restart Post-Boot Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-burnout-keeping-your-game-windows-laptop-cool/"><u>Avoiding Burnout: Keeping Your Game Windows Laptop Cool</u></a></li>
<li><a href="https://windows11.techidaily.com/beginners-blueprint-to-conquering-diablo/"><u>Beginner’s Blueprint to Conquering Diablo</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-why-obs-wont-start-on-your-pc/"><u>Breaking Down Why OBS Won't Start on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-grayed-out-delete-feature-for-windows-11-pins/"><u>Breaking Grayed-Out Delete Feature for Windows 11 PINs</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-back-your-teams-screens/"><u>Bring Back Your Teams Screens</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-printer-usage-errors-efficiently/"><u>Bypassing Printer Usage Errors Efficiently</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-the-gpsvc-wait-issue-on-pcs/"><u>Bypassing the GPSVC Wait Issue on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/classic-game-storage-integrating-into-the-windows-photos-space/"><u>Classic Game Storage: Integrating Into the Windows Photos Space</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-chrome-display-glitches-on-pc/"><u>Clearing Chrome Display Glitches on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-color-issues-in-legacy-bios/"><u>Clearing Up Color Issues in Legacy BIOS</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-windows-11s-obstacle-overcoming-error-code-22/"><u>Clearing Windows 11'S Obstacle: Overcoming Error Code 22</u></a></li>
<li><a href="https://windows11.techidaily.com/compelling-windows-applications-for-video-transformation/"><u>Compelling Windows Applications for Video Transformation</u></a></li>
<li><a href="https://buynow-info.techidaily.com/comprehensive-analysis-of-apples-2019-ipad-air-the-ultimate-media-device/"><u>Comprehensive Analysis of Apple's 2019 iPad Air: The Ultimate Media Device</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-tutorial-onedrive-plus-microsoft-login-on-pc/"><u>Comprehensive Tutorial: OneDrive + Microsoft Login on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/convenient-telnet-setup-for-modern-windows-systems-wins/"><u>Convenient Telnet Setup for Modern Windows Systems (Wins)</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-non-deletable-keys-a-windows-guide/"><u>Correcting Non-Deletable Keys: A Windows Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-a-user-friendly-guide-for-shortcut-placement-on-desktop/"><u>Crafting a User-Friendly Guide for Shortcut Placement on Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-windows-11-a-guide-to-a-unique-environment/"><u>Customizing Windows 11: A Guide to a Unique Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/cyber-armor-top-7-techniques-to-guard-your-os/"><u>Cyber Armor: Top 7 Techniques to Guard Your OS</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-windows-cab-and-its-method-for-installed-content/"><u>Deciphering Windows CAB & Its Method for Installed Content</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-ftdibussys-a-windows-memory-security-paradox/"><u>Decoding ftdibus.sys: A Windows Memory Security Paradox</u></a></li>
<li><a href="https://windows11.techidaily.com/delving-into-disparities-unveiling-the-distinctive-aspects-of-each-login-type/"><u>Delving Into Disparities: Unveiling The Distinctive Aspects of Each Login Type</u></a></li>
<li><a href="https://windows11.techidaily.com/delving-into-what-windows-11s-new-updates-signify-for-users/"><u>Delving Into What Windows 11'S New Updates Signify For Users</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-resource-locks-in-windows-11-environments/"><u>Disabling Resource Locks in Windows 11 Environments</u></a></li>
<li><a href="https://windows11.techidaily.com/disarming-error-dism-0x800f082f-on-microsoft-os/"><u>Disarming Error: DISM 0X800F082F on Microsoft OS</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-the-divine-interface-of-windows-11-os/"><u>Discover the Divine Interface of Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/dive-into-windows-11-auditory-setup-and-use/"><u>Dive Into Windows 11 Auditory Setup and Use</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/easy-guide-to-honor-x8b-frp-bypass-with-best-methods-by-drfone-android/"><u>Easy Guide to Honor X8b FRP Bypass With Best Methods</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/elevate-your-facebook-profile-with-these-11-superior-tools/"><u>Elevate Your Facebook Profile with These 11 Superior Tools</u></a></li>
<li><a href="https://games-able.techidaily.com/expert-advice-on-epic-steam-linkage/"><u>Expert Advice on Epic-Steam Linkage</u></a></li>
<li><a href="https://howto.techidaily.com/fixes-for-apps-keep-crashing-on-vivo-y78-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixes for Apps Keep Crashing on Vivo Y78 5G | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/guide-to-fade-out-music-in-premiere-pro/"><u>Guide To Fade Out Music In Premiere Pro</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-xiaomi-redmi-a2-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>How to Track Xiaomi Redmi A2 Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-7-ways-to-unlock-a-locked-oneplus-ace-2-phone-by-drfone-android/"><u>In 2024, 7 Ways to Unlock a Locked OnePlus Ace 2 Phone</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-cameras-collide-in-motorsport-showdown-gopro-vs-drift-ghost-s/"><u>In 2024, Cameras Collide in Motorsport Showdown! GoPro Vs. Drift Ghost-S</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-check-distance-and-radius-on-google-maps-for-your-xiaomi-redmi-note-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Check Distance and Radius on Google Maps For your Xiaomi Redmi Note 12 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-fix-icloud-lock-from-your-iphone-14-plus-and-ipad-by-drfone-ios/"><u>In 2024, How to fix iCloud lock from your iPhone 14 Plus and iPad</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-optimal-lens-selection-for-smooth-vlogging-experience/"><u>In 2024, Optimal Lens Selection for Smooth Vlogging Experience</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-the-complete-guide-to-xiaomi-redmi-note-12-proplus-5g-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Complete Guide to Xiaomi Redmi Note 12 Pro+ 5G FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-ways-to-trade-pokemon-go-from-far-away-on-vivo-y78t-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to trade pokemon go from far away On Vivo Y78t? | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-failure-alert-domain-service-down/"><u>Print Failure Alert: Domain Service Down</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solutions-for-when-your-hamachi-connection-drops-unexpectedly/"><u>Quick Solutions for When Your Hamachi Connection Drops Unexpectedly</u></a></li>
<li><a href="https://network-issues.techidaily.com/racing-through-internet-speed-on-windows-xp7/"><u>Racing Through Internet Speed on Windows XP/7</u></a></li>
<li><a href="https://tech-haven.techidaily.com/streamline-document-drafting-using-chatgpt-for-microsoft-word-users/"><u>Streamline Document Drafting Using ChatGPT for Microsoft Word Users</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/top-8-linux-screenshot-utilities-compared/"><u>Top 8 Linux Screenshot Utilities Compared</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/turning-horizons-into-heights-uploading-videos-to-igtv-for-2024/"><u>Turning Horizons Into Heights  Uploading Videos to IGTV for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/yosemite-video-editing-101-a-beginners-tutorial-for-mac-os-x/"><u>Yosemite Video Editing 101 A Beginners Tutorial for Mac OS X</u></a></li>
</ul></div>
