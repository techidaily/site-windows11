---
title: "Including D: Drive Paths in File Explorer List"
date: 2024-08-27T16:12:57.411Z
updated: 2024-08-28T16:12:57.411Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Including D: Drive Paths in File Explorer List"
excerpt: "This Article Describes Including D: Drive Paths in File Explorer List"
keywords: File Explorer PATHS,DRIVE_PATH Explore,Navigate FileDrive,Include DrivePaths,ViewEXplorerDrives,ExplorerDriveListing,DisplayFilePaths
thumbnail: https://thmb.techidaily.com/8f13b229b4309cc607ca12c22275ed95f06f33bc5a9a2ad4f10fdb3f8f16d4fd.jpeg
---

## Including D: Drive Paths in File Explorer List

 To access the D: drive, you normally have to open File Explorer, click on **This PC** in the Navigation pane, and expand the **Devices and drives** section. With a simple hack, you can add it to the Navigation pane so you can easily access it straight from there. It will require you to tweak the Windows Registry, but don’t worry; we'll show you an extremely easy way of going about it.

## Before You Proceed…

 We are going to [create a Registry file](https://www.makeuseof.com/windows-registry-file-guide/) to add the D: drive to the Navigation Pane. This file will make changes to the Windows registry, and you need to be careful [not to mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/). A slip-up could make Windows unusable.

 Furthermore, we highly recommend that you learn how to [back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). That way, you have a way of returning it to the state it was in before you made any changes that broke it.

## How Do I Add the D: Drive to the Navigation Pane in File Explorer?

 Start by pressing **Win + S** to bring up Windows Search. Then, type **notepad** in the Search box, and when Notepad shows up in the search results, click on it to launch it.

![The Notepad search result](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/notepad-search-result.png)

 Then copy and paste the below text into Notepad:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}]  
@="D: Drive"  
"System.IsPinnedToNamespaceTree"=dword:00000001  
"SortOrderIndex"=dword:00000050  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\DefaultIcon]  
@=hex(2):69,00,6d,00,61,00,67,00,65,00,72,00,65,00,73,00,2e,00,64,00,6c,00,6c,\  
  00,2c,00,2d,00,33,00,32,00,00,00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\InProcServer32]  
@=hex(2):43,00,3a,00,5c,00,57,00,49,00,4e,00,44,00,4f,00,57,00,53,00,5c,00,73,\  
  00,79,00,73,00,74,00,65,00,6d,00,33,00,32,00,5c,00,73,00,68,00,65,00,6c,00,\  
  6c,00,33,00,32,00,2e,00,64,00,6c,00,6c,00,00,00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\Instance]  
"CLSID"="{0E5AAE11-A475-4c5b-AB00-C66DE400274E}"  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\Instance\InitPropertyBag]  
"Attributes"=dword:00000011  
"TargetFolderPath"=hex(2):44,00,3a,00,5c,00,00,00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\ShellFolder]  
"FolderValueFlags"=dword:00000028  
"Attributes"=dword:f080004d  
  
[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\HideDesktopIcons\NewStartPanel]  
"{0525388b-89d9-4112-bf4d-2aaccb716a7f}"=dword:00000001  
  
[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace\{0525388b-89d9-4112-bf4d-2aaccb716a7f}]  
@="D: Drive"`

 Press **Ctrl + S**, name the file **add-d-drive-file-explorer.reg**, and then click **Save**. Don’t forget to add the REG file extension to let Windows know it’s working with a Registry file.

![saving a registry file in Notepad on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/save-reg-file-add-drive-nav-pane.jpg)

 Next, double-click the Registry file you just created and click **Yes** on the UAC prompt. You’ll then be asked if you want to continue with the merge, so click **Yes**. Afterward, press **Win + E** to open File Explorer.

![the D drive showing in the bottom section of the Navigation pane on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/d-drive-nav-pane.jpg)

 The D: drive should now be visible in the bottom part of the Navigation pane.

<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How Do I Remove the D: Drive From the Navigation Pane in File Explorer?

 To remove the D: drive from the navigation pane, open Notepad and then copy and paste the below text:

`Windows Registry Editor Version 5.00  
  
[-HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}][HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\HideDesktopIcons\NewStartPanel]  
"{0525388b-89d9-4112-bf4d-2aaccb716a7f}"=-  
  
[-HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace\{0525388b-89d9-4112-bf4d-2aaccb716a7f}]`

 Save the file as **remove-d-drive-file-explorer.reg**. Afterward, double-click the registry file and click **Yes** on the UAC prompt. When asked if you want to continue with the merge, click **Yes** again.

 Now the D: drive should be gone from the navigation pane in File Explorer.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Create an Easier Way to Access the D: Drive on Your Windows Computer

 With this guide, you will remove an extra step when accessing the D: drive on your Windows computer. Once you have created the registry files, adding and removing the D: drive from the Navigation pane will be easy. While the registry files are safe, don’t forget to create a backup of your Registry or a system restore point for good measure.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-webster.techidaily.com/-unique-workout-concepts-for-a-pulse-raising-video-channel-for-2024/"><u>[New] 8 Unique Workout Concepts for a Pulse-Raising Video Channel for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-culinary-vloggers-top-10-foodie-tiktok-creations/"><u>[New] Culinary Vloggers  Top 10 Foodie TikTok Creations</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-historical-imagery-unleashed-from-copyrights/"><u>[New] Historical Imagery Unleashed From Copyrights</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-overcoming-delayed-or-non-sending-videos-in-facebooks-popular-chat-application-for-mobile-users-for-2024/"><u>[New] Overcoming Delayed or Non-Sending Videos in Facebook's Popular Chat Application for Mobile Users for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-accelerate-follower-count-key-strategies-unlocked/"><u>[Updated] 2024 Approved  Accelerate Follower Count  Key Strategies Unlocked</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-masterclass-in-crafting-empowerment-videos-for-viewers/"><u>[Updated] 2024 Approved  Masterclass in Crafting Empowerment Videos for Viewers</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-navigate-networking-needs-8-free-fb-downloader-apps/"><u>[Updated] 2024 Approved  Navigate Networking Needs - 8 Free FB Downloader Apps</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-cutting-edge-converters-the-best-6-video-editing-tools-for-macos-big-sur-for-2024/"><u>[Updated] Cutting-Edge Converters  The Best 6 Video Editing Tools for macOS Big Sur for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-explore-leading-platforms-offering-premium-vectr-art-resources/"><u>[Updated] Explore Leading Platforms Offering Premium Vectr Art Resources</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-a-compilation-of-best-video-chatting-applications-mobilepluspc/"><u>[Updated] In 2024, A Compilation of Best Video Chatting Applications (Mobile+PC)</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-innovative-approaches-to-capturing-moments-with-zooms-snaps/"><u>[Updated] In 2024, Innovative Approaches to Capturing Moments with Zoom's Snaps</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-lightning-leap-into-facebook-id-sleuthing/"><u>[Updated] In 2024, Lightning Leap Into Facebook ID Sleuthing</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-inspire-your-physical-endeavors-the-most-motivating-track-list-for-gym-goers/"><u>2024 Approved  Inspire Your Physical Endeavors  The Most Motivating Track List for Gym Goers</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-moving-photos-and-videos-from-pc-to-iphone-effortlessly/"><u>2024 Approved  Moving Photos & Videos From PC to iPhone Effortlessly</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-transformative-power-of-no-fee-text-animation-tools/"><u>2024 Approved  Transformative Power of No-Fee Text Animation Tools</u></a></li>
<li><a href="https://howto.techidaily.com/9-quick-fixes-to-unfortunately-touchwiz-has-stopped-of-xiaomi-14-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Quick Fixes to Unfortunately TouchWiz has stopped Of Xiaomi 14 | Dr.fone</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/analyzing-the-robustness-in-sport-friendly-bose-hp-tech/"><u>Analyzing the Robustness in Sport-Friendly Bose HP Tech</u></a></li>
<li><a href="https://facebook.techidaily.com/apples-vision-for-technology-not-chasing-after-virtual-space/"><u>Apple's Vision for Technology: Not Chasing After Virtual Space</u></a></li>
<li><a href="https://video-capture.techidaily.com/capturing-desktop-image-in-windows-versions-11-7-for-2024/"><u>Capturing Desktop Image in Windows Versions (11-7) for 2024</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/discovering-comfort-and-convenience-in-mods-revolutionary-new-sidecar-e-bike/"><u>Discovering Comfort and Convenience in Mod's Revolutionary New Sidecar E-Bike</u></a></li>
<li><a href="https://extra-hints.techidaily.com/essential-sites-for-high-end-vector-images/"><u>Essential Sites for High-End Vector Images</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-steps-for-powertoys-on-win11/"><u>Essential Steps for PowerToys on Win11</u></a></li>
<li><a href="https://youtube-web.techidaily.com/rific-guide-to-hauls-and-hair-care/"><u>Glam-Rific Guide to Hauls and Hair Care</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-effortlessly-engage-with-windows-11-service-tools/"><u>How to Effortlessly Engage with Windows 11 Service Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-disabled-lock-screen-pause-timer/"><u>How to Fix Disabled Lock Screen Pause Timer</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unresponsive-touch-screen-on-xiaomi-14-ultra-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Touch Screen on Xiaomi 14 Ultra | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-facts-you-need-to-know-about-screen-mirroring-xiaomi-redmi-a2-drfone-by-drfone-android/"><u>In 2024, 3 Facts You Need to Know about Screen Mirroring Xiaomi Redmi A2 | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-capture-clarity-strip-away-background-noise/"><u>In 2024, Capture Clarity  Strip Away Background Noise</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-capture-the-chuckles-a-guide-to-using-snapchats-laughing-lenses/"><u>In 2024, Capture the Chuckles  A Guide to Using Snapchat’s Laughing Lenses</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-exploring-the-new-frontier-of-android-gaming-with-kinemaster/"><u>In 2024, Exploring the New Frontier of Android Gaming with KineMaster</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-learn-how-to-lock-stolen-your-apple-iphone-15-pro-max-properly-by-drfone-ios/"><u>In 2024, Learn How To Lock Stolen Your Apple iPhone 15 Pro Max Properly</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-ultimate-guide-from-infinix-smart-8-plus-frp-bypass-by-drfone-android/"><u>In 2024, Ultimate Guide from Infinix Smart 8 Plus FRP Bypass</u></a></li>
<li><a href="https://windows11.techidaily.com/initiating-playback-with-windows-media-player-guide/"><u>Initiating Playback with Windows Media Player Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/learn-how-to-resurrect-the-non-functional-win-plus-p-feature-in-windows/"><u>Learn How to Resurrect the Non-Functional Win + P Feature in Windows.</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-bluescreenview-an-in-depth-analysis/"><u>Leveraging BlueScreenView - An In-Depth Analysis</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/lost-access-learn-how-to-recover-your-ipad-passcode-easily/"><u>Lost Access? Learn How to Recover Your iPad Passcode Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/master-email-attachment-handling-in-microsoft-words-read-pane-mode/"><u>Master Email Attachment Handling in Microsoft Word's Read Pane Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-fixes-reconciling-obs-server-disconnections-on-windows/"><u>Mastering the Fixes: Reconciling OBS Server Disconnections on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11-a-guide-to-overcoming-stubborn-gif-size-errors-discord/"><u>Mastering Windows 11: A Guide to Overcoming Stubborn GIF Size Errors (Discord)</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-mishaps-conquering-11-windows-11-glitches/"><u>Mastery Over Mishaps: Conquering 11 Windows 11 Glitches</u></a></li>
<li><a href="https://windows11.techidaily.com/modifying-metadata-in-windows-files-timestamp-tweaks-guide/"><u>Modifying Metadata in Windows Files: Timestamp Tweaks Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-to-sound-mastery-with-windows-11-volume-control/"><u>Navigate to Sound Mastery with Windows 11 Volume Control</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-error-code-0xc00ce556-in-windows/"><u>Navigating the Error Code 0xC00CE556 in WINDOWS</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-bokeh-perfection-top-rated-mobile-apps-for-photography-enthusiasts-for-2024/"><u>New Bokeh Perfection Top-Rated Mobile Apps for Photography Enthusiasts for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/reimagining-windows-ui-adding-menus-and-subitems/"><u>Reimagining Windows UI: Adding Menus and Subitems</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-checksum-accuracy-in-winrar-archives-with-6-tips/"><u>Restoring Checksum Accuracy in WinRAR Archives with 6 Tips</u></a></li>
<li><a href="https://program-issues.techidaily.com/1722994543080-scavenger-race-victory-guide-master-your-match-on-pc/"><u>Scavenger Race Victory Guide - Master Your Match on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-and-protect-win-11-edge-instalment-of-microsofts-aguard-feature/"><u>Secure and Protect Win 11 Edge: Instalment of Microsoft's Aguard Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-and-slim-filesystem-setting-up-auto-delete-in-win11/"><u>Secure and Slim Filesystem: Setting Up Auto Delete in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-your-deal-black-friday-612-for-full-life-win10/"><u>Secure Your Deal: Black Friday - $6.12 for Full-Life Win10</u></a></li>
<li><a href="https://windows11.techidaily.com/simplified-approach-to-batch-convert-heic-files-to-jpeg-in-windows-11/"><u>Simplified Approach to Batch Convert HEIC Files to JPEG in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategic-tips-to-optimize-amd-radeon-gaming/"><u>Strategic Tips to Optimize AMD Radeon Gaming</u></a></li>
<li><a href="https://win-dash.techidaily.com/techkey-universal-bluetooth-adapter-supported-by-windows-11-7-and-8-drivers/"><u>Techkey Universal Bluetooth Adapter Supported by Windows 11, 7 and 8 Drivers</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-double-edged-sword-of-generative-ai/"><u>The Double-Edged Sword of Generative AI</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-tackling-windows-disk-errors/"><u>The Ultimate Guide to Tackling Windows Disk Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-seamless-slideshow-creation-and-image-spot-repair-in-win11-photos/"><u>Tips for Seamless Slideshow Creation and Image Spot Repair in Win11 Photos</u></a></li>
<li><a href="https://windows11.techidaily.com/title-perfecting-space-between-windows-widgets/"><u>Title: Perfecting Space Between Windows Widgets</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/top-6-iphone-security-software-the-best-antivirus-applications/"><u>Top 6 iPhone Security Software: The Best Antivirus Applications</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshoot-unresponsive-inputs-when-waking-up-win11/"><u>Troubleshoot Unresponsive Inputs When Waking up Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-non-responsive-windows-enter-key/"><u>Troubleshooting Non-Responsive Windows Enter Key</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-steam-friendship-disconnect-on-pc/"><u>Troubleshooting Steam Friendship Disconnect on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-altering-win-11-proxy-settings/"><u>Understanding and Altering Win 11 Proxy Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-potential-top-winning-apps-from-ms-store-2023/"><u>Unleash Potential: Top Winning Apps From MS Store, 2023</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-new-network-possibilities-with-win11s-settings/"><u>Unlock New Network Possibilities with Win11's Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-your-pc-easily-windows-hello-fingerprint-guide/"><u>Unlock Your PC Easily: Windows Hello Fingerprint Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-new-horizons-rethinking-user-rights-on-windows/"><u>Unlocking New Horizons: Rethinking User Rights on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-diagnostic-info-a-quick-guide/"><u>Unlocking Windows' Diagnostic Info: A Quick Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-blue-screen-mystery-0xc0000001/"><u>Unraveling Blue Screen Mystery - 0xC0000001</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-gif-size-limits-a-guide-to-fixed-errors-in-discord-win11/"><u>Unraveling GIF Size Limits: A Guide to Fixed Errors in Discord (Win11)</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-in-2024-mkvtoolnix-for-macos-a-beginners-guide-to-video-editing-2023/"><u>Updated In 2024, MKVtoolnix for macOS A Beginners Guide to Video Editing 2023</u></a></li>
<li><a href="https://windows11.techidaily.com/uptime-expertise-for-win11-devices-discover-the-top-5-methods/"><u>Uptime Expertise for Win11 Devices - Discover the Top 5 Methods</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-identify-missing-hardware-drivers-with-windows-device-manager-in-windows-10-by-drivereasy-guide/"><u>Use Device Manager to identify missing hardware drivers with Windows Device Manager in Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-drop-issue-effective-solutions-needed/"><u>Win11 Drop Issue: Effective Solutions Needed</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-expertise-required-for-successfully-repairing-directdraw-faults/"><u>Win11: Expertise Required for Successfully Repairing DirectDraw Faults</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>