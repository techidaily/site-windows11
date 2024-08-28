---
title: "Methodology: Purging OneDrive Icon in File Explorer"
date: 2024-08-27T16:06:30.739Z
updated: 2024-08-28T16:06:30.739Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Methodology: Purging OneDrive Icon in File Explorer"
excerpt: "This Article Describes Methodology: Purging OneDrive Icon in File Explorer"
keywords: Dedup File Explorer,Remove OneDrive Icon,Methodology for Clearance,Delete OneDrive Symbol,Purge OneDrive Icons,Uncluttering Folder Views,Eliminate Redundant Icons
thumbnail: https://thmb.techidaily.com/b43da9b8fec14dde01c0becd6729005fd0db59f099a461c4a5b1f228776ffdea.jpg
---

## Methodology: Purging OneDrive Icon in File Explorer

 The OneDrive cloud storage client comes pre-installed on your Windows 11 computer. By default, you'll notice a OneDrive shortcut in the left pane of File Explorer, allowing quick access to your OneDrive files and folders.

 However, if you find the shortcut cluttering or ruining your File Explorer experience, you can remove it using a registry hack. Here's how to remove the OneDrive icon from File Explorer without uninstalling OneDrive.

## How to Remove OneDrive Shortcut From File Explorer via the Registry Editor

 You can remove the OneDrive icon from File Explorer using a registry hack. This way, you can get rid of the icon in File Explorer without uninstalling the OneDrive client. If you would rather remove the app entirely, follow our guide on[removing OneDrive on Windows 11](https://www.makeuseof.com/windows-11-disable-remove-onedrive/) .

 Note that modifying the Windows registry involves risk. We recommend you[create a system restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed with the steps below. A restore point will help you restore your computer in case something goes wrong.

 Once done, follow these steps to remove the OneDrive shortcut from File Explorer:

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open Registry Editor. Click**Yes** if prompted by**User Account Control (UAC).**
3. Next, in the Registry Editor, navigate to the following location. Copy and paste the registry path in the editor for quicker navigation:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
4. In the right pane, right-click on**System.IsPinnedToNameSpaceTree** DWORD value and select**Modify** .  
![remove onedrive icon windows 11 registry editor modify system is pinned to name space free](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-modify-system-is-pinnedtonamespace-free.jpg)
5. In the**Value data** field, type**0** and click**OK** .  
![remove onedrive icon windows 11 registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor.jpg)
6. Next, navigate to the following location in Registry Editor:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace`
7. In the left pane, right-click on**{018D5C66-4533-4307-9B53-224DE2ED1FE6}** and select**Delete** to remove the entry.  
![remove onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)
8. Once done, close the Registry Editor.
9. When you open File Explorer, the OneDrive icon will not be visible anymore.

## How to Show the OneDrive Icon Again in File Explorer

![show onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/show-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)

 To show the OneDrive icon in File Explorer, you’ll need to modify a registry entry again. Here’s how to do it.

1. Press**Win + R** to open**Registry Editor.**
2. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
3. In the right pane, double-click on**System.IsPinnedToNameSpaceTree** DWORD value.
4. Next, type**1** in the**Value data f** ield and click**OK** to save the changes.
5. Relaunch File Explorer to see the changes.

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Remove OneDrive Icon Without Uninstalling OneDrive

 This registry hack is a handy way to make the OneDrive icon disappear without deleting the app entirely from your PC. Alternatively, if you don’t use the service, you can completely remove OneDrive on Windows 11 or disable the service using Group Policy Editor.


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
<li><a href="https://youtube-lab.techidaily.com/024-approved-premium-video-gear-guide-selecting-the-right-lens-for-youtube/"><u>[New] 2024 Approved  Premium Video Gear Guide  Selecting the Right Lens for YouTube</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-complete-analysis-lg-27-oled-screens-visual-edge/"><u>[New] Complete Analysis  LG 27 OLED Screen's Visual Edge</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-innovative-interactions-in-virtuosity-the-top-30-quotes/"><u>[New] In 2024, Innovative Interactions in Virtuosity  The Top 30 Quotes</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-elevate-visibility-maximize-views-seo-for-videos/"><u>[Updated] 2024 Approved  Elevate Visibility, Maximize Views - SEO for Videos</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-in-2024-panasonic-hx-a1-actioncam-in-depth-review/"><u>[Updated] In 2024, Panasonic HX-A1 ActionCam  In-Depth Review</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-the-ultimate-manual-for-youtube-playlist-reordering/"><u>[Updated] In 2024, The Ultimate Manual for YouTube Playlist Reordering</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-three-foundational-elements-for-powerful-facebook-ad-headlines/"><u>[Updated] In 2024, Three Foundational Elements for Powerful Facebook Ad Headlines</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-magic-behind-luts-crafting-captivating-photos/"><u>[Updated] The Magic Behind LUTs  Crafting Captivating Photos</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-capture-twitter-gifs-on-your-computer-quickly/"><u>2024 Approved  Capture Twitter Gifs on Your Computer Quickly</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-key-landscapes-perfectly-capturing-live-streams/"><u>2024 Approved  Key Landscapes  Perfectly Capturing Live Streams</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-skyrocketing-sales-with-high-roi-in-dynamic-fb-ad-creations/"><u>2024 Approved  Skyrocketing Sales with High ROI in Dynamic FB Ad Creations</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/5-ways-to-restart-samsung-galaxy-s23-ultra-without-power-button-drfone-by-drfone-reset-android-reset-android/"><u>5 Ways to Restart Samsung Galaxy S23 Ultra Without Power Button | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/a-working-guide-for-pachirisu-pokemon-go-map-on-tecno-camon-30-pro-5g-drfone-by-drfone-virtual-android/"><u>A Working Guide For Pachirisu Pokemon Go Map On Tecno Camon 30 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/amazons-all-star-series-most-retweeted-and-watched-originals/"><u>Amazon's All-Star Series  Most Retweeted & Watched Originals</u></a></li>
<li><a href="https://screen-recording.techidaily.com/batch-save-presentations-in-video-format-for-2024/"><u>Batch Save Presentations in Video Format for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/capturing-the-journey-a-camera-buyers-guide-for-2024/"><u>Capturing the Journey  A Camera Buyer's Guide for 2024</u></a></li>
<li><a href="https://solve-helper.techidaily.com/discover-how-abbyy-shaped-future-financial-tactics-at-the-2017-strategietage-conference/"><u>Discover How ABBYY Shaped Future Financial Tactics at the 2017 StrategieTage Conference</u></a></li>
<li><a href="https://windows11.techidaily.com/executing-an-instant-in-place-windows-11-boost/"><u>Executing an Instant, In-Place Windows 11 Boost</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/expert-tweeting-tools-top-video-converters/"><u>Expert Tweeting Tools - Top Video Converters</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-your-mouses-dizzy-spins-in-windows/"><u>Fixing Your Mouse's Dizzy Spins in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-for-controlling-visual-cues-in-windows-11-search/"><u>Guide for Controlling Visual Cues in Windows 11 Search</u></a></li>
<li><a href="https://fox-that.techidaily.com/how-to-fix-on-hold-charging-glitches-on-your-iphone-8-methods-explored/"><u>How to Fix 'On Hold' Charging Glitches on Your iPhone - 8 Methods Explored</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-disabled-lock-screen-pause-timer/"><u>How to Fix Disabled Lock Screen Pause Timer</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-resolve-blue-screens-resulting-from-unhandled-exceptions/"><u>How to Resolve Blue Screens Resulting From Unhandled Exceptions</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-previous-version-of-excel-2016-file-stellar-by-stellar-guide/"><u>How to Restore Previous Version of Excel 2016 File? | Stellar</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-complete-guide-on-unlocking-apple-iphone-6s-plus-with-a-broken-screen-by-drfone-ios/"><u>In 2024, Complete Guide on Unlocking Apple iPhone 6s Plus with a Broken Screen?</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-easy-guide-to-oppo-a2-frp-bypass-with-best-methods-by-drfone-android/"><u>In 2024, Easy Guide to Oppo A2 FRP Bypass With Best Methods</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-lock-your-samsung-galaxy-s23-fe-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>In 2024, Lock Your Samsung Galaxy S23 FE Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/initiating-playback-with-windows-media-player-guide/"><u>Initiating Playback with Windows Media Player Guide</u></a></li>
<li><a href="https://fox-that.techidaily.com/is-your-find-my-iphone-not-working-discover-why-and-fix-it-here/"><u>Is Your Find My iPhone Not Working? Discover Why and Fix It Here!</u></a></li>
<li><a href="https://windows11.techidaily.com/learn-how-to-resurrect-the-non-functional-win-plus-p-feature-in-windows/"><u>Learn How to Resurrect the Non-Functional Win + P Feature in Windows.</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-bluescreenview-an-in-depth-analysis/"><u>Leveraging BlueScreenView - An In-Depth Analysis</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-the-art-of-using-the-openai-api-for-innovative-solutions/"><u>Mastering the Art of Using the OpenAI API for Innovative Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-mishaps-conquering-11-windows-11-glitches/"><u>Mastery Over Mishaps: Conquering 11 Windows 11 Glitches</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-for-correcting-roblox-windows-problems/"><u>Methods for Correcting Roblox Windows Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/modifying-metadata-in-windows-files-timestamp-tweaks-guide/"><u>Modifying Metadata in Windows Files: Timestamp Tweaks Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-to-sound-mastery-with-windows-11-volume-control/"><u>Navigate to Sound Mastery with Windows 11 Volume Control</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-error-code-0xc00ce556-in-windows/"><u>Navigating the Error Code 0xC00CE556 in WINDOWS</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-game-launch-issues-for-epic/"><u>Navigating Windows Game Launch Issues for Epic</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/razer-book-13-analysis-mini-marvel-unleashed/"><u>Razer Book 13 Analysis: Mini Marvel Unleashed</u></a></li>
<li><a href="https://windows11.techidaily.com/recovering-internet-router-settings-on-windows-pc/"><u>Recovering Internet Router Settings on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/refining-malfunctional-fixes-within-windows-1011-diagnostics/"><u>Refining Malfunctional Fixes Within Windows 10/11 Diagnostics</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-and-slim-filesystem-setting-up-auto-delete-in-win11/"><u>Secure and Slim Filesystem: Setting Up Auto Delete in Win11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/shedding-the-gloom-brighten-your-iphone-vids-for-2024/"><u>Shedding the Gloom  Brighten Your Iphone Vids for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/simplified-approach-to-batch-convert-heic-files-to-jpeg-in-windows-11/"><u>Simplified Approach to Batch Convert HEIC Files to JPEG in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-telnet-activation-in-latest-windows-versions/"><u>Simplifying Telnet Activation in Latest Windows Versions</u></a></li>
<li><a href="https://techidaily.com/solutions-to-restore-deleted-files-from-xiaomi-redmi-k70-pro-by-fonelab-android-recover-data/"><u>Solutions to restore deleted files from Xiaomi Redmi K70 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-video-lags-in-chromes-youtube-viewing/"><u>Solving Video Lags in Chrome's YouTube Viewing</u></a></li>
<li><a href="https://windows11.techidaily.com/startup-guide-for-windows-11s-immediate-help-tool/"><u>Startup Guide for Windows 11'S Immediate Help Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/stealthy-system-settings-hiding-windows-11-power-command/"><u>Stealthy System Settings: Hiding Windows 11 Power Command</u></a></li>
<li><a href="https://howto.techidaily.com/stuck-at-android-system-recovery-of-samsung-galaxy-f15-5g-fix-it-easily-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Stuck at Android System Recovery Of Samsung Galaxy F15 5G ? Fix It Easily | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/the-future-is-here-windows-11-changes-to-file-explorer/"><u>The Future Is Here: Windows 11 Changes to File Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-seamless-slideshow-creation-and-image-spot-repair-in-win11-photos/"><u>Tips for Seamless Slideshow Creation and Image Spot Repair in Win11 Photos</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshoot-unresponsive-inputs-when-waking-up-win11/"><u>Troubleshoot Unresponsive Inputs When Waking up Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-steam-friendship-disconnect-on-pc/"><u>Troubleshooting Steam Friendship Disconnect on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-altering-win-11-proxy-settings/"><u>Understanding and Altering Win 11 Proxy Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-potential-top-winning-apps-from-ms-store-2023/"><u>Unleash Potential: Top Winning Apps From MS Store, 2023</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-your-pc-easily-windows-hello-fingerprint-guide/"><u>Unlock Your PC Easily: Windows Hello Fingerprint Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-blue-screen-mystery-0xc0000001/"><u>Unraveling Blue Screen Mystery - 0xC0000001</u></a></li>
<li><a href="https://youtube-web.techidaily.com/s-to-viral-guide-for-computer-and-phone-upload-of-youtube-shorts-for-2024/"><u>Videos to Viral  Guide for Computer & Phone Upload of YouTube Shorts for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-expertise-required-for-successfully-repairing-directdraw-faults/"><u>Win11: Expertise Required for Successfully Repairing DirectDraw Faults</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-triple-widget-setup-made-simple/"><u>Windows 11'S Triple Widget Setup Made Simple</u></a></li>
</ul></div>
