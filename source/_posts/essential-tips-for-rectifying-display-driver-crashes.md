---
title: Essential Tips for Rectifying Display Driver Crashes
date: 2024-08-27T16:11:39.289Z
updated: 2024-08-28T16:11:39.289Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Essential Tips for Rectifying Display Driver Crashes
excerpt: This Article Describes Essential Tips for Rectifying Display Driver Crashes
keywords: Fixing Screen Errors,Display Fix Guide,BIOS Update Steps,Graphics Card Repair,Drivers Troubleshoot,OS Reboot Tips,Crash Resolution Hints
thumbnail: https://thmb.techidaily.com/cf1ae4b3cdb5debdafe3b02949517a45048f6142dd7f5f842e985181e8a620c0.jpg
---

## Essential Tips for Rectifying Display Driver Crashes

 The “display driver failed to start” error message usually appears when you try to launch a game on Windows. The error message appears in the form of a Windows notification above the system tray area. When this error occurs, it causes your screen to go completely black. Sometimes it will recover, but sometimes it will require a hard reset.

 When this error is at its worst, it can prevent you from playing your favorite games. As such, here is how you can fix the “display driver failed to start” error on a Windows 10 or 11 PC.

## 1\. Perform Some Display Driver-Related Fixes

 The error message points to your display driver as the main culprit. As such, before you try anything else, you can try these display driver-related fixes to see if they do the job.

### Roll Back the Latest Graphics Driver Update

![The Roll Back Driver option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/roll-back-driver-button.jpg)

 If your graphics card’s driver has recently been updated, try rolling back to the old GPU driver. A **Roll Back Driver** option is usually only available for a short time (typically a few days) after updating a driver. Check out our guide to [rolling back drivers in Windows](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) for further details about how to apply this potential resolution.

### Install the Latest Driver for Your PC’s Graphics Card

 People plagued with this error message have confirmed that updating your graphics drivers is a good solution for the “display driver failed to start” error. And while Windows usually handles driver updates through Windows Update, it sometimes won't update NVIDIA and AMD GPU drivers.

 You can update your graphics card’s driver yourself with the methods discussed in our guide to [updating GPU drivers on Windows](http://www.makeuseof.com/update-graphics-drivers-in-windows-10/).

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
### Reinstall Your Graphics Driver

 If your PC’s GPU already has the newest graphics driver available, consider reinstalling the graphics driver. It's best to do a clean install to ensure your GPU's driver is back to its factory defaults.

 Check out [how to cleanly install and reinstall GPU drivers on Windows](https://www.makeuseof.com/how-to-cleanly-install-and-reinstall-gpu-drivers-on-windows/) for more information.

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Utilize the Hardware and Devices Troubleshooter

 Windows has a Hardware and Devices troubleshooter that can help resolve the “display driver failed to start” error. This troubleshooting tool is no longer available within Settings or Control Panel, but it is still accessible via Command Prompt.

 You can access and run the Hardware and Devices troubleshooting utility like this:

1. First, locate the Command Prompt by pressing **Win + S**, typing "cmd," and clicking on **Command Prompt**.
2. Enter and execute the Hardware and Devices command:  
`msdt.exe -id DeviceDiagnostic`
3. Click **Next** to start the troubleshooting.  
![The Hardware and Devices troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/hardware-and-devices-troubleshooter-troubleshooter-2.jpg)
4. Select **Apply this fix** to rectify any issues Windows finds.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Lower the Windows Visual Effect Settings

 Windows has various visual effect settings that can affect performance. Having too many visual effects enabled can potentially cause issues on PCs with more limited GPUs.

 So, it’s recommended to select the "adjust for best performance" mode in the visual effect settings like this:

1. Right-click **Start**, select **Search**, and input "advanced system settings" in the text box.
2. Press the **Settings** button in the **Performance** category.  
![The Advanced tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/advanced-tab-2.jpg)
3. Click the **Adjust for best performance** radio button, which will deselect most if not all of the effect checkboxes.  
![The "adjust for best performance" button selected](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/adjust-for-best-performance-radio-button.jpg)
4. Select **Apply** to set the new performance settings.
5. Click the Performance Options window’s **OK** button.

## 4\. Edit the GraphicsDrivers Registry Key

 Some users have got the “display driver failed to start” error fixed by editing the GraphicsDriver registry key. This tweaking involves adding a new **TdrDelay** DWORD value to that key for extending Timeout Detection Delay.

 You can edit the GraphicsDriver registry key like this:

1. Open the Run dialog with **Win + R** and enter "regedit".
2. Click **OK** or press **Enter** to open the Registry Editor window.
3. Then enter this GraphicsDrivers key location inside the registry address bar:  
`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\GraphicsDrivers`
4. Right-click **GraphicsDrivers** and select the **New** context menu option.
5. Select **DWORD (32-bit) Value** to add a new entry.  
![The New > DWORD options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dword-32-bit-value-2.jpg)
6. Type **TdrDelay** within the new DWORD’s text box.
<!-- affiliate ads begin -->
<span id="1993652">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Double-click the **TdrDelay** DWORD.
8. Input a value of **5** in the data box and select **OK**.  
![The Value data box the TdrDelay](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/value-data-box-2.jpg)
9. Now close the Registry Editor and reboot your PC.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->

## 5\. Roll Back Windows to a Previous Restore Point

![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/system-restore-window.jpg)

 If you have System Restore enabled, restoring Windows to an earlier date is worth a try if nothing else has worked so far. Rolling back Windows will undo every system change made after a selected date.

 As such, you can use System Restore to put your PC "back in time" to a moment when the error didn't occur. It does mean you may lose some apps or data, so be sure to back up anything you want to keep.

 Our guide to [utilizing System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/) provides step-by-step instructions for how to roll back Windows 10 and 11\. Select a restore point date created before you needed to fix the “display driver failed to start” error.

 If this fixes the problem, be careful when re-installing the apps and drivers that got wiped during the restore. If you do, keep tabs on what you reinstalled and when. If the "display driver failed to start" error resurfaces, uninstall everything you recently reinstalled.

## 6\. Perform a Windows Factory Reset

 If System Restore is not an option or it doesn't resolve the issue, you can try a factory reset as the last resort. Performing a factory reset will likely fix the “display driver failed to start” error. However, factory resetting a PC deletes all the apps that weren't pre-installed with Windows. So, be prepared to reinstall all third-party apps you installed yourself.

![The Keep my Files option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/keep-my-files-option.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->
 You can apply a factory reset with the Reset this PC utility. That tool includes a **Keep my files** option you can select to keep files in your user folders (Documents, Pictures, Videos, etc). Our guide for [factory resetting Windows 10 and 11](http://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer) provides details on how to access and utilize that tool.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901410&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix Pro - Software based live production. vMix Pro includes everything in vMix 4K plus 8 channels of Replay and 8 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## Enjoy Your Windows Gaming Again

 Applying those potential solutions will almost certainly be enough to fix the “display driver failed to start” error in most cases. However, you may need to try applying more than one of them to find one that works on your PC. Then you can get back to playing all your favorite Windows games again without further issues.

 When this error is at its worst, it can prevent you from playing your favorite games. As such, here is how you can fix the “display driver failed to start” error on a Windows 10 or 11 PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-videos.techidaily.com/new-boost-engagement-advanced-youtube-tag-strategies-revealed/"><u>[New] Boost Engagement  Advanced YouTube Tag Strategies Revealed</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-powerdirector-unveiled-a-detailed-24-review-and-tutorial/"><u>[New] PowerDirector Unveiled  A Detailed '24 Review & Tutorial</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-premiere-discord-recording-tools-online-desktop-mobile/"><u>[New] Premiere Discord Recording Tools - Online, Desktop, Mobile</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-superior-sonic-aligner-android-version-for-2024/"><u>[New] Superior Sonic Aligner, Android Version for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-2024-approved-unveiling-the-secrets-to-perfect-green-screen-in-kinemaster/"><u>[Updated] 2024 Approved  Unveiling the Secrets to Perfect Green Screen in Kinemaster</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-click-worthy-chronicles-shaping-successful-meme-videos-for-instafb-for-2024/"><u>[Updated] Click-Worthy Chronicles  Shaping Successful Meme Videos for Insta/FB for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-must-try-titles-for-tranquil-touchscreen-time/"><u>[Updated] Must-Try Titles for Tranquil Touchscreen Time</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-xiaomi-civi-3-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Xiaomi Civi 3</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/following-fades-track-losses-on-insta-for-2024/"><u>Following Fades  Track Losses on Insta for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/guaranteeing-presence-of-startup-applications/"><u>Guaranteeing Presence of Startup Applications</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/high-quality-sound-capture-top-10-for-spotify-lovers/"><u>High-Quality Sound Capture  Top 10 for Spotify Lovers</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-no-audio-output-device-is-installed-error-on-windows/"><u>How to Fix the No Audio Output Device Is Installed Error on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-hide-the-power-button-from-the-start-menu-on-windows-10-and-11/"><u>How to Hide the Power Button From the Start Menu on Windows 10 & 11</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-hook-up-a-new-screen-to-your-portable-computer/"><u>How to Hook Up a New Screen to Your Portable Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-mend-nvidias-geforce-experience-errors-in-windows/"><u>How to Mend Nvidia's GeForce Experience Errors in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/idea-integration-with-obsidians-creative-canvas/"><u>Idea Integration with Obsidian's Creative Canvas</u></a></li>
<li><a href="https://windows11.techidaily.com/ifas-premier-laptop-showcase-the-ultimate-finds/"><u>IFA's Premier Laptop Showcase - The Ultimate Finds</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-google-pixel-8-pro-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Google Pixel 8 Pro to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/lost-thumbnail-images-on-windows-11-a-step-by-step-resolution/"><u>Lost Thumbnail Images on Windows 11: A Step-by-Step Resolution</u></a></li>
<li><a href="https://windows11.techidaily.com/maximize-space-and-speed-with-these-5-win-folders-methods/"><u>Maximize Space and Speed with These 5 Win Folders Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-charge-readiness-notification-tips-for-win11-users/"><u>Maximizing Charge Readiness: Notification Tips for Win11 Users</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-digital-landscape-an-overview-of-facebook-twitter-instagram-and-youtube/"><u>Navigating the Digital Landscape: An Overview of Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-nvidias-failed-configuration-retrieval-in-1011-windows/"><u>Overcoming NVIDIA's Failed Configuration Retrieval in 10/11 Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/path-proficiency-unlocking-6-winning-techniques-for-file-and-folder-location-capture/"><u>Path Proficiency: Unlocking 6 Winning Techniques for File & Folder Location Capture</u></a></li>
<li><a href="https://windows11.techidaily.com/personalizing-permanent-trash-settings-in-windows-1011/"><u>Personalizing Permanent Trash Settings in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/premium-climate-apps-for-modern-windows-users/"><u>Premium Climate Apps for Modern Windows Users</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/premium-sound-waves-review-paww-hearing-triad/"><u>Premium Sound Waves Review: Paww Hearing Triad</u></a></li>
<li><a href="https://windows11.techidaily.com/printscreen-vs-snip-and-sketch-choosing-your-screen-capture-companion/"><u>PrintScreen Vs. Snip & Sketch: Choosing Your Screen Capture Companion</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-your-windows-keys-quick-solutions-for-non-responsive-shortcuts/"><u>Reviving Your Windows Keys: Quick Solutions for Non-Responsive Shortcuts</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-logins-quick-solutions-for-windows-11-issues/"><u>Streamlining Logins: Quick Solutions for Windows 11 Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/swiftly-solve-error-code-1132-in-microsofts-zoom-app/"><u>Swiftly Solve Error Code 1132 in Microsoft's Zoom App</u></a></li>
<li><a href="https://windows11.techidaily.com/the-hidden-value-in-preserving-your-windows-11-notification-alerts/"><u>The Hidden Value in Preserving Your Windows 11 Notification Alerts</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-accessing-photos-via-windows-11s-explorer/"><u>Tips for Accessing Photos via Windows 11'S Explorer</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/top-10-airplay-apps-in-oppo-find-x6-pro-for-streaming-drfone-by-drfone-android/"><u>Top 10 AirPlay Apps in Oppo Find X6 Pro for Streaming | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooters-tackling-chrome-profile-anomalies-in-windows/"><u>Troubleshooters: Tackling Chrome Profile Anomalies in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-1110-stop-pin-connection-hurdle/"><u>Troubleshooting Windows 11/10: Stop PIN Connection Hurdle</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11s-veiled-bar-search-feature/"><u>Unlocking Windows 11'S Veiled Bar Search Feature</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-the-best-of-both-worlds-lumafusion-for-mac-and-its-alternatives/"><u>Updated In 2024, The Best of Both Worlds Lumafusion for Mac and Its Alternatives</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-bar-through-time-1985-2023-retrospective/"><u>Windows Bar Through Time: 1985-2023 Retrospective</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>