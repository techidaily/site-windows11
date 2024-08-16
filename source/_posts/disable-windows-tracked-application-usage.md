---
title: Disable Windows' Tracked Application Usage
date: 2024-08-15T15:11:04.872Z
updated: 2024-08-16T15:11:04.872Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Disable Windows' Tracked Application Usage
excerpt: This Article Describes Disable Windows' Tracked Application Usage
keywords: Turn Off App Usage Tracker,Stop Windows Tracking Apps,End Windows App Data Logging,Disable Tracking in Windows,Block App Usage Monitoring,Remove Windows Application Watcher,Halt Windows Data Collection
thumbnail: https://thmb.techidaily.com/85034a62a15df819e619fec4e6d0909e5ab4845fbca98b126bdfe343d56fc596.jpg
---

## Disable Windows' Tracked Application Usage

 Windows records and monitors how often you use particular applications. While this may enhance productivity, it does also raise privacy concerns.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.

## 1\. How to Disable App Launch Tracking Through Windows Settings

 To disable app launch tracking, open the Start menu and type **Settings** in the search bar. Select the **Settings** option in the search results. In the left-side menu, click the **Privacy & security** tab. Then click **General** under the Windows permissions section.

 On the next page, locate **Let Windows improve Start and search results by tracking app launches** and toggle it off.

![Disable App Launch Tracking through Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-through-windows-settings.jpg)

 After making the changes, Windows will stop tracking and recording your app launches.

 If you ever need to re-enable the feature, repeat the same steps and toggle the switch back on. This will enable Windows to start tracking and recording your app launches.

<!-- affiliate ads begin -->

<!-- affiliate ads end -->
## 2\. How to Disable App Launch Tracking Using the Group Policy Editor

 You can also disable app launch tracking using the Group Policy Editor. But this method is only available in the Pro and Enterprise versions.

 If you don't have these Windows versions, [turn on the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) and follow these instructions.

1. Press **Win + R** on your keyboard to open the Run dialog box.
2. Type **gpedit.msc** in the text box and click **OK**.
3. In the Group Policy Editor window, navigate to the following path:  
`User Configuration > Administrative Templates > Windows Components > Edge UI​`
4. Go to the right side of the window and double-click on **Turn off tracking of app usage**.  
![Disable App Launch Tracking using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-using-group-policy-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->
5. On the next page, check the **Enabled** box.
6. Click **Apply** \> **OK** to save your changes.

 This way, you can disable app launch tracking using the group policy editor.

 To enable the feature again, follow the same steps and navigate to _User Configuration > Administrative Templates > Windows Components > Edge UI_. Then double-click on **Turn off tracking of app usage** and check the **Not Configured** or **Disabled** option.

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. How to Disable App Launch Tracking Through the Registry Editor

 Registry Editor is another method to disable app launch tracking. The process is tricky as you need to manually modify the registry keys and one wrong move can cause serious problems. So, we suggest you [create a backup of the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it.

 To disable app launch tracking through Registry Editor, do the following:

1. Right-click on Start and select **Run** from the menu list.
2. Type **regedit** in the text field and click **OK**. This will [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. When the UAC window appears, click **Yes** to grant privileges.
4. In the left pane, navigate to the following path:  
`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. If you don't find the Advanced folder, right-click on **Explorer** and select **New** \> **Key**.
6. Name it **Advanced** and press the Enter key.
7. Now, right-click on the **Advanced** folder and choose **New** \> **DWORD (32-bit) Value**.
8. Name it **Start\_TrackProgs** and hit Enter.  
![Disable App Launch Tracking through the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-through-the-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4531356&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8fdd149fcaa7058caccc9c4ad5b0d89a/products/tss-box.JPG" border="0">The Tube Sites Submitter is a fast and efficient tool for anyone who needs to upload videos quickly, easily and automatically to hundreds of tube sites in mere minutes . </a>
<!-- affiliate ads end -->
9. Double-click on the **Start\_TrackProgs** DWORD and set its value to **0**.

 Once you're done, close the Registry Editor and restart your computer. Now, Windows won't track or record app launches.

 If you ever want to turn back on app launch tracking, double-click on the **Start\_TrackProgs** DWORD in Registry Editor and set its value to **1**. After that, restart your system for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
## Windows Won’t Track or Monitor the Apps You Use

 If you don't want to mess with the Registry Editor or Group Policy Editor, use the Settings option to disable app launch tracking. Choose the method you prefer and enjoy a tracking-free experience.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-hints.techidaily.com/new-composite-skies-a-drone-video-editors-strategic-guide/"><u>[New] Composite Skies  A Drone Video Editor’s Strategic Guide</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-building-connections-through-collaborative-playlists/"><u>[New] In 2024, Building Connections Through Collaborative Playlists</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-downloading-videos-directly-to-iphoneipad-youtubes-quick-guide/"><u>[Updated] Downloading Videos Directly to iPhone/iPad - YouTube's Quick Guide</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-pixel-powerhouse-review-amd-radeon/"><u>[Updated] Pixel Powerhouse Review  AMD Radeon</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-precision-in-upload-a-deep-dive-into-youtube-video-size-settings/"><u>[Updated] Precision in Upload  A Deep-Dive Into YouTube Video Size Settings</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-voice-logger-innovations-for-mac-users-unveiling-the-best-5-apps-for-2024/"><u>[Updated] Voice Logger Innovations for Mac Users  Unveiling the Best 5 Apps for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/all-you-need-to-know-about-mega-greninja-for-infinix-smart-8-drfone-by-drfone-virtual-android/"><u>All You Need To Know About Mega Greninja For Infinix Smart 8 | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/easy-guide-how-to-bypass-nokia-g42-5g-frp-android-10111213-by-drfone-android/"><u>Easy Guide How To Bypass Nokia G42 5G FRP Android 10/11/12/13</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/easy-guide-to-infinix-note-30-vip-racing-edition-frp-bypass-with-best-methods-by-drfone-android/"><u>Easy Guide to Infinix Note 30 VIP Racing Edition FRP Bypass With Best Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-the-freeze-troubleshooting-windows-obs-not-starting/"><u>Fixing the Freeze: Troubleshooting Windows OBS Not Starting</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-store-failure-codes/"><u>Fixing Windows Store Failure Codes</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-code-0x0000004e-hiccups/"><u>Fixing Windows' Code 0X0000004E Hiccups</u></a></li>
<li><a href="https://windows11.techidaily.com/from-obscurity-back-to-the-desktop-restoring-deleted-files-on-windows/"><u>From Obscurity Back To the Desktop: Restoring Deleted Files on Windows</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/guide-on-how-to-change-your-apple-id-email-address-on-apple-iphone-11-pro-max-drfone-by-drfone-ios/"><u>Guide on How To Change Your Apple ID Email Address On Apple iPhone 11 Pro Max | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-self-clearing-windows-recycle-bin/"><u>Guide to Self-Clearing Windows Recycle Bin</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-no-supported-devices-problem-in-windows-update/"><u>Handling 'No Supported Devices' Problem in Windows Update</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-halt-windows-desktop-keys-effectively/"><u>How to Halt Windows Desktop Keys Effectively</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-repair-unable-to-fetch-error-in-nvidia-geforce-experience/"><u>How To Repair 'Unable To Fetch' Error in NVIDIA GeForce Experience</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-ways-to-track-nokia-c22-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Track Nokia C22 without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-netflix-location-to-get-more-country-version-on-honor-magic-6-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Netflix Location to Get More Country Version On Honor Magic 6 Pro | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-use-ispoofer-on-honor-100-drfone-by-drfone-virtual-android/"><u>In 2024, How to use iSpoofer on Honor 100? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-repairing-windows-email-failures-error-code-0x800713f/"><u>Mastering the Art of Repairing Windows' Email Failures (Error Code 0X800713F)</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-task-scheduler-for-file-batch-execution/"><u>Mastering Windows Task Scheduler for File Batch Execution</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-two-users-shared-ms-login-fails/"><u>Navigating Through Two Users' Shared MS Login Fails</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-and-handling-file-unreadable-problem-on-windows/"><u>Preventing and Handling ‘File Unreadable’ Problem on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/proven-tactics-for-heic-to-jpeg-conversion-process-on-windows-11-systems/"><u>Proven Tactics for Heic to JPEG Conversion Process on Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-for-read-from-disk-failed-error/"><u>Quick Fix for Read From Disk Failed Error</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-steps-for-restarting-windows-apps/"><u>Quick Steps for Restarting Windows Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-html-errors-in-windows-11-mail-app-email-views/"><u>Rectifying HTML Errors in Windows 11 Mail App Email Views</u></a></li>
<li><a href="https://windows11.techidaily.com/redefining-phones-role-in-windows-11-networking/"><u>Redefining Phones' Role in Windows 11 Networking</u></a></li>
<li><a href="https://windows11.techidaily.com/reinvigorate-discolored-volume-settings-in-win/"><u>Reinvigorate Discolored Volume Settings in Win</u></a></li>
<li><a href="https://windows11.techidaily.com/rejuvenating-win11-drive-non-destructive-freeing-methods-max-156-chars/"><u>Rejuvenating Win11 Drive: Non-Destructive Freeing Methods (Max 156 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-problematic-windows-protection-protocol/"><u>Resolving Problematic Windows Protection Protocol</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-accessibility-to-essential-windows-command-center/"><u>Restoring Accessibility to Essential Windows Command Center</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/rhythmic-recording-music-infused-snapchat-adventures/"><u>Rhythmic Recording  Music-Infused Snapchat Adventures</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-a-static-backdrop-on-modern-windows-11-pcs/"><u>Secure a Static Backdrop on Modern Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/simple-steps-to-activate-classic-photo-viewer-in-modern-windows-1111/"><u>Simple Steps to Activate Classic Photo Viewer in Modern Windows 11/11</u></a></li>
<li><a href="https://windows11.techidaily.com/steering-users-clear-of-disconnection-hurdles-from-nvidia/"><u>Steering Users Clear of Disconnection Hurdles From Nvidia</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-entering-windows-11-home-settings/"><u>Step-by-Step: Entering Windows 11 Home Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-tackle-physical-ram-limitations-on-windows-vmware/"><u>Steps to Tackle Physical RAM Limitations on Windows VMware</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-optimizing-win-11s-taskbar/"><u>The Ultimate Guide to Optimizing Win 11'S Taskbar</u></a></li>
<li><a href="https://some-guidance.techidaily.com/ultimate-selection-top-hdr-camera-picks-for-2024/"><u>Ultimate Selection  Top HDR Camera Picks for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/uncovering-and-correcting-cant-access-mail-errors-in-windows-11-mail-app/"><u>Uncovering and Correcting Can't Access Mail Errors in Windows 11 Mail App</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-premium-windows-laptops-of-year-2024/"><u>Unveiling the Premium Windows Laptops of Year 2024</u></a></li>
<li><a href="https://win-able.techidaily.com/1723011528804-why-isnt-my-amazon-prime-video-working-expert-solutions-inside/"><u>Why Isn't My Amazon Prime Video Working? Expert Solutions Inside</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-transition-phasing-out-old-traits/"><u>Windows Transition: Phasing Out Old Traits</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-strategies-for-simultaneous-folder-proliferation-on-windows-systems/"><u>Winning Strategies for Simultaneous Folder Proliferation on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-windows-timers-for-efficient-pomodoros/"><u>Winning Windows Timers for Efficient Pomodoros</u></a></li>
</ul></div>
