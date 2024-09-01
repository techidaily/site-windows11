---
title: Fixing Unlisted Device Detected Error in Win10/11
date: 2024-08-31T22:17:12.184Z
updated: 2024-09-01T22:17:12.184Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Unlisted Device Detected Error in Win10/11
excerpt: This Article Describes Fixing Unlisted Device Detected Error in Win10/11
keywords: Windows Unlisted Devices Fix,Win10 Device Error Resolution,Win11 Unlisted Error Fixing,Listed Devices Issue Solve,Windows Update Troubleshoot,Device Not Found Correction,Boot Loop Repair Guide
thumbnail: https://thmb.techidaily.com/b35a9a46671dd373ee6fb76f2e7c8c289a52fdab2f2b7f6dd74a2f0921700773.jpg
---

## Fixing Unlisted Device Detected Error in Win10/11

 Many users partition their hard drives or utilize external storage devices with their PCs. However, such drives become inaccessible when the “A device which does not exist was specified” error arises. Users have reported seeing this strange error message when they try to open connected external storage devices or drive partitions inside Windows File Explorer.

 That error is most unwelcome since it means users can’t open whatever drives it arises for. Consequently, they can’t access files on affected drives. This is how you can fix the “device which does not exist was specified” error in Windows 10 and 11.

## 1\. Plug the Affected Device Into a Different USB Slot

 If this error is affecting an external storage device, try reconnecting the USB drive. There might be an issue with the port you’ve connected the drive with. Plug the USB drive into a different port to see if the same error occurs.

 If you need to resolve this error for an internal drive, check the drive’s internal connections. To do that, you’ll need to open the case for a desktop PC. Then make sure none of the drive’s connection cables are in any way loose.

## 2\. Run the SFC Tool

 Users have confirmed the System File Checker tool can resolve this drive error. That highlights system file corruption can cause this issue, which an SFC scan will likely resolve. Our guide to[running a System File Checker scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) tells you how to execute the SFC command in Windows.

![The sfc /scannow](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/sfc-scannow.jpg)

## 3\. Run a Check Disk Scan for the Drive

 You might need to fix the “device which does not exist was specified” error because your drive has some bad sectors. Running a CHKDSK (Check Disk) scan command is a potential remedy for bad drive sectors. This is how you can run the Windows Check Disk tool from the Command Prompt:

1. Open the search tool by simultaneously pressing the**Windows** logo +**S** keys.
2. Enter the search phrase**cmd** inside the text box.
3. Click**Run as administrator** to start Command Prompt with elevated permissions.
4. Then execute the Check Disk scan by inputting this command:  
`chkdsk X: /f /r`  
![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/chkdsk-scan.jpg)
5. Press**Enter** to initiate the scan.

 You’ll need to replace X in the above command with the actual letter of the affected drive you need to scan. For example, the command for a drive labeled D would be:

`chkdsk D: /f /r`

## 4\. Try Changing the Drive’s Letter

 Changing the affected drive’s letter is a potential fix that users have confirmed to work. You can change the drive’s letter with the Disk Management tool like this:

1. If you need to fix this issue for an external drive, connect that storage device to your PC.
2. Open Disk Management by right-clicking**Start** and selecting the shortcut for that tool.
3. Right-click the affected drive and select**Change Drive Letter and Paths** .  
![The Change Drive Letter and Paths option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-drive-letter-paths.jpg)
4. Press the**Change** button.  
![The Change Drive Letter window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-drive-letter-window.jpg)
5. Click the drop-down menu for the**Assign the following drive lette** r option.  
![The Assign the following drive letter option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/assign-the-following-drive-letter.jpg)
6. Select a drive letter that you’ve never used.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->
7. Click**OK** on the Change Drive Letter or Path window.
8. Select**Yes** on the Disk Management confirmation dialog.

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Rescan a Drive

 Disk Management includes a**Rescan Disk** option for troubleshooting drives. That option detects disk changes and updates drive info accordingly when selected. So, rescanning the disk is a viable troubleshooting method for resolving this “device which does not exist” error. This is how you can rescan a drive:

1. Plug the drive into your PC if necessary.
2. Bring up the Disk Management tool.
3. Click the drive for which the error occurs in Disk Management.
4. Then click the**Action** menu.  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/properties-option2.jpg)
5. Select**Rescan Disks** on the menu.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Select the Full Control Option for a Drive Location

 The “device which does not exist” error can arise because of restricted drive permissions. In that scenario, users need to select a**Full control** permission option for their drives. These are the steps for selecting the**Full control** permission setting:

1. First, activate the file management tool with Explorer’s**Windows** logo +**E** hotkey.
2. Then click**This PC** in Explorer’s left sidebar.
3. Right-click the affected drive to select**Properties** .  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/properties-option2.jpg)
4. Click the drive’s**Security** tab.
5. If the**Full control** option isn’t ticked, click the**Edit** button.
6. Select the**Allow** box for the**Full control** option.  
![The Full control option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/full-control-checkbox.jpg)
7. Click**Apply** \>**OK** on the drive’s permissions window.
<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->

## 7\. Reinstall the Affected Drive

 If you need to fix this issue for an external storage device, try reinstalling the affected drive. Doing so will reinstall the drivers for the affected storage device. This is how you can reinstall the drive:

Insert the affected drive into one of your PC’s USB ports.

1. Click**Start** with the right mouse button to select a**Device Manager** shortcut.
2. Double-click**Disk drives** in Device Manager.
3. Right-click your drive and select**Uninstall device** .  
![The Uninstall device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/uninstall-device2.jpg)
4. Then select the**Uninstall** option on the dialog box prompt.  
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698998&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/MacBook_Pro_lyrx-withsinger-tv.png" border="0">LYRX is an easy-to-use karaoke software with the professional features karaoke hosts need to perform with precision. LYRX is karaoke show hosting software that supports all standard karaoke file types as well as HD video formats, and it’s truly fun to use. 
LYRX Karaoke Software MAC/WINDOWS (Includes Activation For 3 Machines)</a>
<!-- affiliate ads end -->
![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/uninstall-option3.jpg)
5. Disconnect the drive plugged into the PC.
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
6. Plug the drive back into the computer to reinstall its driver.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->
## 8\. Update Your Motherboard’s Chipset Driver

 It might be necessary for some users to update motherboard drivers to fix this issue. To do so manually, you’ll need the motherboard model and manufacturer details. You can check those details as follows:

1. Open the Windows search box, and type a**System Information** keyword there.
2. Click**System Information** to view that app’s window.
3. Note down the**BaseBand Product** and**BaseBand Manufacturer** details.  
![Baseboard specs in System Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/baseboard-specs.jpg)
4. [Open the Command Prompt](https://www.makeuseof.com/windows-11-open-command-prompt/) if the System Information app doesn’t include a serial number for the motherboard.
5. Execute this baseboard command:  
`wmic baseboard get product,Manufacturer,version,serialnumber`  
![The baseboard command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/baseboard-command.jpg)
6. Copy and paste the serial number for the motherboard shown within the Command Prompt into Notepad or another text editor.
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->

 Then open the download section of your motherboard manufacturer’s website. Select your motherboard model and download its latest chipset driver from there. You can install the new driver for your motherboard with the downloaded driver (setup.exe) package file.

 The driver package might be included within a ZIP archive, which you’ll need to extract as outlined within this guide to[unzipping files in Windows](https://www.makeuseof.com/unzip-files-windows-10/) .

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
## Access Your Drive Again on Windows

 Those potential solutions will probably fix the “device which does not exist” drive error for most users. If they’re not enough, there could be an issue with your PC’s motherboard headers. In that case, consider taking your PC to a reputable repair service to resolve such an issue.

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
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-twitch-content-integration-boosting-engagement-with-fb-sharing/"><u>[New] 2024 Approved  Twitch Content Integration  Boosting Engagement with FB Sharing</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-pro-gear-bundle-elevating-your-experience-with-yi-4k-for-2024/"><u>[New] Pro Gear Bundle  Elevating Your Experience with YI 4K for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-unveiled-list-leading-top-10-facebook-video-downloaders-for-android/"><u>[New] Unveiled List  Leading Top 10 Facebook Video Downloaders for Android</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-expert-insights-into-timecode-manipulation-in-macos-srt-files/"><u>[Updated] Expert Insights Into Timecode Manipulation in macOS SRT Files</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-directly-stream-webcam-feed-with-vlc-software/"><u>[Updated] In 2024, Directly Stream Webcam Feed with VLC Software</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-how-to-measure-the-performance-of-igtv-videos/"><u>[Updated] In 2024, How to Measure the Performance of IGTV Videos?</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/1-get-your-free-holiday-e-book-collection-today/"><u>1. Get Your Free Holiday E-Book Collection Today!</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-perfect-wedding-timers-android-and-ios-top-10-picks/"><u>2024 Approved  Perfect Wedding Timers  Android & iOS' Top 10 Picks</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-selecting-the-perfect-drone-stabilizer-a-guide/"><u>2024 Approved  Selecting the Perfect Drone Stabilizer  A Guide</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-streamlabs-versus-obs-a-compreran-analysis-for-broadcasters/"><u>2024 Approved  Streamlabs Versus OBS  A Compreran Analysis for Broadcasters</u></a></li>
<li><a href="https://tech-revival.techidaily.com/chatbot-advice-selecting-your-perfect-viewing-experience-with-chatgpt/"><u>Chatbot Advice: Selecting Your Perfect Viewing Experience with ChatGPT</u></a></li>
<li><a href="https://windows11.techidaily.com/fixer-upper-for-missing-second-display-on-w11/"><u>Fixer-Upper for Missing Second Display on W11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-a-twitchy-pointer-in-your-desktop-environment/"><u>Fixing a Twitchy Pointer in Your Desktop Environment</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/how-to-come-up-with-the-best-pokemon-team-on-apple-iphone-xr-drfone-by-drfone-virtual-ios/"><u>How to Come up With the Best Pokemon Team On Apple iPhone XR? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-get-rid-of-the-illustrations-inside-windows-search/"><u>How to Get Rid of the Illustrations Inside Windows Search</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-overcome-windows-11-cortana-non-responsiveness/"><u>How to Overcome Windows 11 Cortana Non-Responsiveness</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-honor-90-pro-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Honor 90 Pro to New Android? | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-a-complete-breakdown-of-googles-podcast-system/"><u>In 2024, A Complete Breakdown of Google's Podcast System</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-samsung-galaxy-a23-5g-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Samsung Galaxy A23 5G Phones with/without a PC</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-must-haves-for-capturing-movies-on-the-move/"><u>In 2024, Must-Haves for Capturing Movies on the Move</u></a></li>
<li><a href="https://windows11.techidaily.com/introducing-vivetool-unleashing-upcoming-features-for-windows-users/"><u>Introducing ViVeTool: Unleashing Upcoming Features for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/jingle-all-the-way-making-windows-11-celebrate/"><u>Jingle All the Way: Making Windows 11 Celebrate</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11s-hidden-themes-a-registry-guide/"><u>Mastering Windows 11'S Hidden Themes: A Registry Guide</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ize-money-from-youtube-shorts-tactics-and-tricks-for-2024/"><u>Maximize Money From YouTube Shorts  Tactics & Tricks for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/mystery-of-the-missing-gpu-expose-with-device-hub-fixes/"><u>Mystery of the Missing GPU - Expose with Device Hub Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-and-compute-file-sizes-an-in-depth-look-at-powershell/"><u>Navigate and Compute File Sizes: An In-Depth Look at PowerShell</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-powertoys-to-tailor-snap-layouts/"><u>Navigating PowerToys to Tailor Snap Layouts</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-speaker-or-headphones-non-detection-errors-on-pc/"><u>Navigating Speaker or Headphones Non-Detection Errors on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-to-windows-11-on-mac-via-parallels-installer/"><u>Navigating to Windows 11 on Mac via Parallels Installer</u></a></li>
<li><a href="https://windows11.techidaily.com/one-key-to-close-clustered-applications-windows-edition/"><u>One Key to Close Clustered Applications: Windows Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-video-ram-limitations-in-magic-educational-platforms/"><u>Overcoming Video RAM Limitations in Magic-Educational Platforms</u></a></li>
<li><a href="https://windows11.techidaily.com/personalize-your-workspace-adding-an-indicator-of-the-current-weather-on-windows-11-taskbar/"><u>Personalize Your Workspace: Adding an Indicator of the Current Weather on Windows 11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/proactive-approach-to-prevent-dwarven-woes-on-win/"><u>Proactive Approach to Prevent Dwarven Woes on WIN</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-microsofts-0x800713f-mail-glitch-in-win11/"><u>Remedying Microsoft's 0X800713F Mail Glitch in Win11</u></a></li>
<li><a href="https://win-answers.techidaily.com/resolved-issues-how-to-stop-tower-of-fantasy-from-crashing-on-desktop/"><u>Resolved Issues: How to Stop 'Tower of Fantasy' From Crashing on Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-slow-or-inactive-windows-downloads-directory/"><u>Reviving Slow or Inactive Windows Downloads Directory</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-overwatch-2-writable-device-error/"><u>Solving Overwatch 2' Writable Device Error</u></a></li>
<li><a href="https://windows11.techidaily.com/steam-deck-ready-instructions-for-windows-installation/"><u>Steam Deck Ready: Instructions for Windows Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-strategies-for-re-booting-windows-explorer-11/"><u>Swift Strategies for Re-Booting Windows Explorer 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-freeze-ups-of-psx-software-in-new-os-version/"><u>Tackling Freeze-Ups of PSX Software in New OS Version</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-troublesome-fail-to-work-in-win-based-apps/"><u>Tackling the Troublesome 'Fail to Work' In Win-Based Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/the-proven-method-for-stepsigning-in-steam-titles/"><u>The Proven Method for Stepsigning in Steam Titles</u></a></li>
<li><a href="https://fox-that.techidaily.com/top-6-solutions-when-family-sharing-isnt-working-a-comprehensive-guide/"><u>Top 6 Solutions When Family Sharing Isn't Working: A Comprehensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-app-setup-utilizing-winstall-in-the-windows-11-landscape/"><u>Transforming App Setup: Utilizing Winstall in the Windows 11 Landscape</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-wu-and-wuo-sync-mechanisms/"><u>Understanding WU & WUO Sync Mechanisms</u></a></li>
<li><a href="https://some-skills.techidaily.com/unlocking-digital-reading-how-to-easily-download-and-read-google-ebooks-on-amazons-kindle-fire/"><u>Unlocking Digital Reading: How to Easily Download & Read Google eBooks on Amazon's Kindle Fire</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-discover-the-best-top-10-free-mp4-video-editing-tools/"><u>Updated Discover the Best Top 10 Free MP4 Video Editing Tools</u></a></li>
<li><a href="https://howto.techidaily.com/xiaomi-redmi-13c-5g-screen-unresponsive-heres-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Xiaomi Redmi 13C 5G Screen Unresponsive? Heres How to Fix It | Dr.fone</u></a></li>
</ul></div>
