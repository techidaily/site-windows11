---
title: Resolving Non-Existent Device Alerts on Windows 10/11
date: 2024-08-15T15:37:35.309Z
updated: 2024-08-16T15:37:35.309Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving Non-Existent Device Alerts on Windows 10/11
excerpt: This Article Describes Resolving Non-Existent Device Alerts on Windows 10/11
keywords: Fixing WinAlerts,NoDeviceErrorWin,DevAlertWindowsFix,UnrecognizedDevWin,DeviceNotFoundWin,StopWinNonExistent,SolveWinDevErrors
thumbnail: https://thmb.techidaily.com/93e8b8eb6bc88169936766a6461fe23e663eb59793bd9736b13ed221555fa6ea.jpg
---

## Resolving Non-Existent Device Alerts on Windows 10/11

 Many users partition their hard drives or utilize external storage devices with their PCs. However, such drives become inaccessible when the “A device which does not exist was specified” error arises. Users have reported seeing this strange error message when they try to open connected external storage devices or drive partitions inside Windows File Explorer.

 That error is most unwelcome since it means users can’t open whatever drives it arises for. Consequently, they can’t access files on affected drives. This is how you can fix the “device which does not exist was specified” error in Windows 10 and 11.

## 1\. Plug the Affected Device Into a Different USB Slot

 If this error is affecting an external storage device, try reconnecting the USB drive. There might be an issue with the port you’ve connected the drive with. Plug the USB drive into a different port to see if the same error occurs.

 If you need to resolve this error for an internal drive, check the drive’s internal connections. To do that, you’ll need to open the case for a desktop PC. Then make sure none of the drive’s connection cables are in any way loose.

## 2\. Run the SFC Tool

 Users have confirmed the System File Checker tool can resolve this drive error. That highlights system file corruption can cause this issue, which an SFC scan will likely resolve. Our guide to [running a System File Checker scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) tells you how to execute the SFC command in Windows.

![The sfc /scannow](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/sfc-scannow.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Run a Check Disk Scan for the Drive

 You might need to fix the “device which does not exist was specified” error because your drive has some bad sectors. Running a CHKDSK (Check Disk) scan command is a potential remedy for bad drive sectors. This is how you can run the Windows Check Disk tool from the Command Prompt:

1. Open the search tool by simultaneously pressing the**Windows** logo +**S** keys.
2. Enter the search phrase**cmd** inside the text box.
3. Click**Run as administrator** to start Command Prompt with elevated permissions.
4. Then execute the Check Disk scan by inputting this command:  
`chkdsk X: /f /r`  
![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/chkdsk-scan.jpg)
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Press**Enter** to initiate the scan.

 You’ll need to replace X in the above command with the actual letter of the affected drive you need to scan. For example, the command for a drive labeled D would be:

`chkdsk D: /f /r`

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
## 4\. Try Changing the Drive’s Letter

 Changing the affected drive’s letter is a potential fix that users have confirmed to work. You can change the drive’s letter with the Disk Management tool like this:

1. If you need to fix this issue for an external drive, connect that storage device to your PC.
2. Open Disk Management by right-clicking**Start** and selecting the shortcut for that tool.
3. Right-click the affected drive and select**Change Drive Letter and Paths** .  
![The Change Drive Letter and Paths option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-drive-letter-paths.jpg)
4. Press the**Change** button.  
![The Change Drive Letter window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-drive-letter-window.jpg)
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
5. Click the drop-down menu for the**Assign the following drive lette** r option.  
![The Assign the following drive letter option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/assign-the-following-drive-letter.jpg)
<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
6. Select a drive letter that you’ve never used.
7. Click**OK** on the Change Drive Letter or Path window.
8. Select**Yes** on the Disk Management confirmation dialog.

## 5\. Rescan a Drive

 Disk Management includes a**Rescan Disk** option for troubleshooting drives. That option detects disk changes and updates drive info accordingly when selected. So, rescanning the disk is a viable troubleshooting method for resolving this “device which does not exist” error. This is how you can rescan a drive:

1. Plug the drive into your PC if necessary.
2. Bring up the Disk Management tool.
3. Click the drive for which the error occurs in Disk Management.
4. Then click the**Action** menu.  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/properties-option2.jpg)
5. Select**Rescan Disks** on the menu.

## 6\. Select the Full Control Option for a Drive Location

 The “device which does not exist” error can arise because of restricted drive permissions. In that scenario, users need to select a**Full control** permission option for their drives. These are the steps for selecting the**Full control** permission setting:

1. First, activate the file management tool with Explorer’s**Windows** logo +**E** hotkey.
2. Then click**This PC** in Explorer’s left sidebar.
3. Right-click the affected drive to select**Properties** .  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/properties-option2.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Click the drive’s**Security** tab.
5. If the**Full control** option isn’t ticked, click the**Edit** button.
6. Select the**Allow** box for the**Full control** option.  
![The Full control option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/full-control-checkbox.jpg)
7. Click**Apply** \>**OK** on the drive’s permissions window.

## 7\. Reinstall the Affected Drive

 If you need to fix this issue for an external storage device, try reinstalling the affected drive. Doing so will reinstall the drivers for the affected storage device. This is how you can reinstall the drive:

Insert the affected drive into one of your PC’s USB ports.

1. Click**Start** with the right mouse button to select a**Device Manager** shortcut.
2. Double-click**Disk drives** in Device Manager.
3. Right-click your drive and select**Uninstall device** .  
![The Uninstall device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/uninstall-device2.jpg)
<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Then select the**Uninstall** option on the dialog box prompt.  
![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/uninstall-option3.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
5. Disconnect the drive plugged into the PC.
6. Plug the drive back into the computer to reinstall its driver.

## 8\. Update Your Motherboard’s Chipset Driver

 It might be necessary for some users to update motherboard drivers to fix this issue. To do so manually, you’ll need the motherboard model and manufacturer details. You can check those details as follows:

1. Open the Windows search box, and type a**System Information** keyword there.
2. Click**System Information** to view that app’s window.
3. Note down the**BaseBand Product** and**BaseBand Manufacturer** details.  
![Baseboard specs in System Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/baseboard-specs.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
4. [Open the Command Prompt](https://www.makeuseof.com/windows-11-open-command-prompt/) if the System Information app doesn’t include a serial number for the motherboard.
5. Execute this baseboard command:  
`wmic baseboard get product,Manufacturer,version,serialnumber`  
![The baseboard command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/baseboard-command.jpg)
<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Copy and paste the serial number for the motherboard shown within the Command Prompt into Notepad or another text editor.

 Then open the download section of your motherboard manufacturer’s website. Select your motherboard model and download its latest chipset driver from there. You can install the new driver for your motherboard with the downloaded driver (setup.exe) package file.

 The driver package might be included within a ZIP archive, which you’ll need to extract as outlined within this guide to [unzipping files in Windows](https://www.makeuseof.com/unzip-files-windows-10/) .

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
<li><a href="https://printer-issues.techidaily.com/compatibility-canon-pixma-mp620-and-windows-11-clash/"><u>[Compatibility] Canon Pixma MP620 and Windows 11 Clash</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/024-approved-unveiling-creative-possibilities-anime-subscribe-buttons-for-your-youtube-channel-filmora/"><u>[New] 2024 Approved  Unveiling Creative Possibilities  Anime Subscribe Buttons for Your YouTube Channel (Filmora)</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-in-2024-exclusive-selection-winning-16-free-video-tools/"><u>[New] In 2024, Exclusive Selection  Winning 16 Free Video Tools</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/remier-content-creators-colloquy/"><u>[New] Premier Content Creators Colloquy</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-stop-the-mute-add-sound-to-tweeted-clips-for-2024/"><u>[New] Stop the Mute  Add Sound to Tweeted Clips for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-streamline-your-workflow-macos-screencast-tutorial-for-2024/"><u>[New] Streamline Your Workflow  MacOS Screencast Tutorial for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-accelerated-windows-content-verification-for-2024/"><u>[Updated] Accelerated Windows Content Verification for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-splash-to-fame-surfers-choice-camera-picks-2e3/"><u>[Updated] Splash to Fame  Surfer's Choice Camera Picks (2E3)</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-swift-skim-windows-file-compilation/"><u>[Updated] Swift Skim Windows File Compilation</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-audio-clarity-commandments-choosing-from-the-best-6-livestreaming-mics/"><u>2024 Approved  Audio Clarity Commandments  Choosing From the Best 6 Livestreaming Mics</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-free-fast-and-easy-top-5-choices-for-pinterest-video-downloaders/"><u>2024 Approved  Free, Fast & Easy  Top 5 Choices for Pinterest Video Downloaders</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-how-to-use-a-whiteboard-in-google-meet/"><u>2024 Approved  How to Use a Whiteboard in Google Meet</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/audiovisual-debut-breakdown-for-2024/"><u>Audiovisual Debut Breakdown for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/broadcast-battles-obs-clashes-with-shadowgl-for-2024/"><u>Broadcast Battles  OBS Clashes with ShadowGL for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-your-digital-footprints-in-windows-11/"><u>Exploring Your Digital Footprints in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-xbox-game-pass-0x800700e9-error-in-windows-11-os/"><u>Fixing Xbox Game Pass 0X800700E9 Error in Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-visual-studio-code-crashing-on-windows-11/"><u>How to Fix Visual Studio Code Crashing on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reduce-overhead-from-real-time-scanners/"><u>How to Reduce Overhead From Real-Time Scanners</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-use-slideshow-and-spot-fix-in-the-windows-11-photos-app/"><u>How to Use Slideshow and Spot Fix in the Windows 11 Photos App</u></a></li>
<li><a href="https://windows11.techidaily.com/how-windows-blue-screen-data-assists-diagnosis/"><u>How Windows Blue Screen Data Assists Diagnosis</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-boost-your-exercise-motivation-with-top-20-music-choices/"><u>In 2024, Boost Your Exercise Motivation with Top 20 Music Choices</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-expert-guide-to-instagram-data-decoding-and-actionable-strategies/"><u>In 2024, Expert Guide to Instagram Data Decoding and Actionable Strategies</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-iphone-14-pro-max-without-passcode-or-face-id-by-drfone-ios/"><u>In 2024, How to Unlock iPhone 14 Pro Max without Passcode or Face ID</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-comprehensive-guide-to-enhancing-your-video-gaming-channels/"><u>In 2024, The Comprehensive Guide to Enhancing Your Video Gaming Channels</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-transfer-your-apple-iphone-14-apps-to-new-iphone-drfone-by-drfone-transfer-from-ios/"><u>In 2024, Transfer your Apple iPhone 14 Apps to New iPhone | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/instagram-edge-techniques-for-effective-video-cropping-and-exporting-for-2024/"><u>Instagram Edge  Techniques for Effective Video Cropping and Exporting for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/instructional-insights-into-activating-windows-11s-wireless-feature/"><u>Instructional Insights Into Activating Windows 11'S Wireless Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/make-your-file-explorer-reliable-fixes-that-work-in-windows-11/"><u>Make Your File Explorer Reliable: Fixes That Work in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-startup-fixes-for-frozen-windows-obs-studio/"><u>Mastering Startup Fixes for Frozen Windows OBS Studio</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-smartly-minimizing-applications-using-ctrlplustab/"><u>Navigate Smartly: Minimizing Applications Using Ctrl+Tab</u></a></li>
<li><a href="https://windows11.techidaily.com/resetting-the-system-how-to-reinitialize-windows-11-programs/"><u>Resetting the System: How to Reinitialize Windows 11 Programs</u></a></li>
<li><a href="https://windows11.techidaily.com/restore-smooth-operation-to-windows-timer-tasks/"><u>Restore Smooth Operation to Windows Timer Tasks</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-window-cookie-expiry-post-login-errors/"><u>Setting Window' Cookie Expiry Post-Login Errors</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/smooth-cinematography-ideal-stabilizer-tools-for-vloggers-for-2024/"><u>Smooth Cinematography  Ideal Stabilizer Tools for Vloggers for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-stopping-bsod-events-with-vmware-on-win11/"><u>Solutions for Stopping BSOD Events with VMware on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/speeding-up-android-studio-tasks-on-windows-os/"><u>Speeding Up Android Studio Tasks on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-to-windows-media-player-launch/"><u>Step-by-Step Guide to Windows Media Player Launch</u></a></li>
<li><a href="https://windows11.techidaily.com/the-edge-dilemma-ethical-choices-amidst-societal-controls/"><u>The Edge Dilemma: Ethical Choices Amidst Societal Controls</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshoot-interface-not-recognized-a-win-to-success-guide/"><u>Troubleshoot 'Interface Not Recognized': A Win to Success Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/tweaking-internet-security-features-for-win-1011/"><u>Tweaking Internet Security Features for Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-blocked-functionality-of-ccleaner-on-win11/"><u>Unblocking Blocked Functionality of CCleaner on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-potential-extending-your-pin-on-windows-11/"><u>Unlocking the Potential: Extending Your PIN on Windows 11</u></a></li>
<li><a href="https://techidaily.com/will-mov-files-play-on-g24-power-by-aiseesoft-video-converter-play-mov-on-android/"><u>Will MOV files play on G24 Power ?</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-at-speedy-epic-games-installations/"><u>Winning at Speedy Epic Games Installations</u></a></li>
<li><a href="https://windows11.techidaily.com/your-guide-to-developing-an-automatic-voice-to-text-application-for-windows/"><u>Your Guide to Developing an Automatic Voice-to-Text Application for Windows</u></a></li>
</ul></div>
