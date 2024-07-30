---
title: Enabling OneDrive for Direct File Explorer Opens
date: 2024-07-29T04:23:49.564Z
updated: 2024-07-30T04:23:49.564Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enabling OneDrive for Direct File Explorer Opens
excerpt: This Article Describes Enabling OneDrive for Direct File Explorer Opens
keywords: File Explorer OneDrive Access,Direct Open Drives Filesync,OneDrive Share Through Explorer,Dedicated Drive Direct Opening,EnableDrive Direct Viewing,ExploreOneDrive File Opens,SyncFiles OneDrive Explorer
thumbnail: https://thmb.techidaily.com/069b298bfedee9c280f30a09eb725e41e8884f90fc111239be7bdf14c7e0c06b.jpg
---

## Enabling OneDrive for Direct File Explorer Opens

 When you launch Windows File Explorer, it automatically takes you to the "Quick Access" view. This page displays shortcuts to recently accessed folders and files and lists your favorite folders. It might be convenient for some users but not for others who prefer easy access to their cloud storage.

 Read this comprehensive guide if you want File Explorer to open OneDrive instead of Quick Access.

## 1\. Use the Folder Options

 If you want to make OneDrive the starting point of your File Explorer, you can do so using folder options. Here's how to do it:

1. Open the Start menu and type **File Explorer** in the search box. When the File Explorer icon appears, click it to launch the app. You can also use **Win + E** to open the program quickly.
2. In the File Explorer window, look for **See more** (three dots) at the top. Clicking on it opens the Folder Options dialog box.  
<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Open Folder Options in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-folder-options-in-file-explorer.jpg)
3. On the General tab, click the **Open File Explorer to** drop-down menu and select "Username Personal". Here, "Username" refers to your Windows account name.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->
![Open File Explorer to OneDrive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-file-explorer-to-onedrive.jpg)
4. Click **Apply** \> **OK** to close the dialog box.

 From now on, opening File Explorer will automatically launch OneDrive rather than Quick Access.

## 2\. Using the Registry Editor

 You can also use the Registry Editor to set OneDrive as your default File Explorer view. But be warned: if you make an incorrect change to the system registry, you could damage your computer. We recommend [backing up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it.

 Once backed up, follow these steps to make OneDrive the default view:

1. [Open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **regedit** in the text box and hit **Enter**.
3. If you're prompted for permission, select **Yes** to continue. The Registry Editor window will open.
4. In the Registry Editor window, navigate to this path:  
`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. In the right pane, locate and double-click the **LaunchTo** entry. If the entry isn't present, you'll need to create it. For that, right-click on the **Advanced** folder and select **New > DWORD (32-bit) Value**. Name the value "LaunchTo" and press Enter. Doing so will create a new DWORD in the registry.  
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Set File Explorer to Open OneDrive Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/set-file-explorer-to-open-onedrive-using-registry.jpg)
6. Double-click on this newly created value and set its value to **4**.
7. Click **OK** and close the registry window.

 After that, restart your computer for the changes to take effect. Once your PC restarts, launch File Explorer. With this method, you will launch File Explorer directly to your cloud storage without navigating through Quick Access.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->
## 3\. Using a Reg File

 The third and final method to set OneDrive as the default view involves using a reg file. It contains the necessary instructions that modify the registry on your behalf. So, if you're not comfortable using the registry editor, this is the right way to go.

 To create the reg file, follow these steps:

1. Right-click on your desktop and select **New > Text Document**.
2. Name the file **OneDrive.reg** and hit **Enter**.
3. Now open the file in a text editor such as Notepad.
4. Copy and paste the following code into the text document:  
`<code>Windows Registry Editor Version 5.00  

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced]  
"LaunchTo"=dword:00000004`
5. After pasting the given code, click **File** \> **Save as**.
6. In the Save as dialog box, select **All files** from the Save as type drop-down menu and hit Enter. Make sure the file is saved as a **.reg** file and not as a .txt file.  
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->
![Open File Explorer to OneDrive Using REG File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-file-explorer-to-onedrive-using-reg-file.jpg)
7. Double-click the REG file you just created. If you're prompted for permission to change your computer, click **Yes**.
8. Finally, restart your computer for the changes to take effect.

 After your system restarts, launch File Explorer. You'll see OneDrive as the main view instead of Quick Access.

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Set File Explorer to Open OneDrive Instead of Quick Access

 There you have it; three different methods to make OneDrive your default File Explorer view. If you like, you can also change other folder views, such as Downloads or This PC, using the same techniques we discussed above. I hope this guide helped you get things done quickly and easily.

 Read this comprehensive guide if you want File Explorer to open OneDrive instead of Quick Access.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-tips.techidaily.com/024-approved-fixing-the-no-thumbnail-issue-in-youtubes-shorts-videos/"><u>[New] 2024 Approved  Fixing the No-Thumbnail Issue in YouTubes Shorts Videos</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/024-approved-harmonious-hubs-your-guide-to-posting-audio-on-youtube/"><u>[New] 2024 Approved  Harmonious Hubs  Your Guide to Posting Audio on YouTube</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-mastering-live-stream-capture-tv-show-recording-techniques/"><u>[New] 2024 Approved  Mastering Live Stream Capture  TV Show Recording Techniques</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-enhancing-viewership-with-effective-obs-use-on-youtube-and-twitch-for-2024/"><u>[New] Enhancing Viewership with Effective OBS Use on YouTube & Twitch for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-hear-the-difference-mastering-instagram-voice-customizations-for-2024/"><u>[New] Hear the Difference  Mastering Instagram Voice Customizations for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-prime-screen-capture-tools-no-lag-just-clarity/"><u>[New] In 2024, Prime Screen Capture Tools - No Lag, Just Clarity</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-tips-for-faster-vimeo-video-viewing/"><u>[New] In 2024, Tips for Faster Vimeo Video Viewing</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-zoom-calls-with-flair-filters-application-101/"><u>[New] In 2024, Zoom Calls with Flair  Filters Application 101</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/egitimate-protocols-for-achieving-over-a-million-viewership/"><u>[New] Legitimate Protocols for Achieving Over a Million Viewership</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-snappy-zoom-calls-for-improved-engagement/"><u>[New] Snappy Zoom Calls for Improved Engagement</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-top-5-cheap-drones-under-100/"><u>[New] Top 5 Cheap Drones Under $100</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-top-ranked-cloud-stores-analysis-and-pricing-insights/"><u>[New] Top-Ranked Cloud Stores  Analysis & Pricing Insights</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-perfecting-obs-broadcasts-for-facebook-audience/"><u>[Updated] 2024 Approved  Perfecting OBS Broadcasts for Facebook Audience</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-selecting-the-ultimate-steadicams-for-flawless-dslr-shoots/"><u>[Updated] In 2024, Selecting the Ultimate Steadicams for Flawless DSLR Shoots</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-lgs-ultrafine-vision-a-thorough-4k-screen-evaluation/"><u>[Updated] LG's UltraFine Vision  A Thorough 4K Screen Evaluation</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-silence-zoom-distortion-swift-remedies-unveiled/"><u>[Updated] Silence Zoom Distortion  Swift Remedies Unveiled</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-superior-photos-repository-hubs/"><u>[Updated] Superior Photos Repository Hubs</u></a></li>
<li><a href="https://windows11.techidaily.com/11-common-windows-11-problems-with-easy-solutions/"><u>11 Common Windows 11 Problems With Easy Solutions</u></a></li>
<li><a href="https://howto.techidaily.com/11-proven-solutions-to-fix-google-play-store-not-working-issue-on-realme-narzo-n55-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Proven Solutions to Fix Google Play Store Not Working Issue on Realme Narzo N55 | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-adjust-your-timeline-facebook-look-back-guide/"><u>2024 Approved  Adjust Your Timeline  Facebook Look Back Guide</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-best-music-player-software-for-android/"><u>2024 Approved  Best Music Player Software for Android</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-twitterscape-in-focus-your-route-to-watching-hd-videos/"><u>2024 Approved  Twitterscape in Focus  Your Route to Watching HD Videos</u></a></li>
<li><a href="https://ai-topics.techidaily.com/2024-approved-the-top-english-voice-generator-to-convert-text-into-desired-accent/"><u>2024 Approved The Top English Voice Generator To Convert Text Into Desired Accent</u></a></li>
<li><a href="https://windows11.techidaily.com/8-ways-to-fix-the-windows-pin-not-working-in-windows-10-and-11/"><u>8 Ways to Fix the Windows PIN Not Working in Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/a-complete-look-at-windows-11s-audio-recorder-keys/"><u>A Complete Look at Windows 11'S Audio Recorder Keys</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-guide-on-faking-your-location-in-mozilla-firefox-on-apple-iphone-12-pro-drfone-by-drfone-virtual-ios/"><u>A Detailed Guide on Faking Your Location in Mozilla Firefox On Apple iPhone 12 Pro | Dr.fone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/a-working-guide-for-pachirisu-pokemon-go-map-on-apple-iphone-14-pro-drfone-by-drfone-virtual-ios/"><u>A Working Guide For Pachirisu Pokemon Go Map On Apple iPhone 14 Pro | Dr.fone</u></a></li>
<li><a href="https://fox-http.techidaily.com/breathtaking-bounds-of-2022-skaters-for-2024/"><u>Breathtaking Bounds of 2022 Skaters for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-how-to-deal-with-non-terminatable-errors/"><u>Bypassing Windows: How to Deal with Non-Terminatable Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/cease-uncontrolled-system-shutdowns-on-windows-11/"><u>Cease Uncontrolled System Shutdowns on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/changing-terminals-default-backdrop/"><u>Changing Terminal's Default Backdrop</u></a></li>
<li><a href="https://windows11.techidaily.com/choosing-the-right-nearby-share-software-for-secure-collaboration/"><u>Choosing the Right Nearby Share Software for Secure Collaboration</u></a></li>
<li><a href="https://windows11.techidaily.com/decluttering-windows-11-icon-pile-up/"><u>Decluttering Windows 11 Icon Pile-Up</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-hardware-utilization-in-windows-11/"><u>Decoding Hardware Utilization in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-tips-for-reactivating-file-explorer-ui/"><u>Easy Tips for Reactivating File Explorer UI</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-system-launch-by-configuring-services-in-windows-11/"><u>Elevate Your System Launch by Configuring Services in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-windows-volume-preserve-data/"><u>Enhance Windows Volume, Preserve Data</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-flaky-windows-apps-a-step-by-step-guide/"><u>Fixing Flaky Windows Apps: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-white-or-gray-microsoft-store-display/"><u>Fixing White or Gray Microsoft Store Display</u></a></li>
<li><a href="https://windows11.techidaily.com/getting-acquainted-with-apple-maps-on-windows-desktops/"><u>Getting Acquainted with Apple Maps on Windows Desktops</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/guide-to-mirror-your-vivo-s17-pro-to-other-android-devices-drfone-by-drfone-android/"><u>Guide to Mirror Your Vivo S17 Pro to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-customize-sound-levels-with-dedicated-win11-keys/"><u>How to Customize Sound Levels with Dedicated Win11 Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-develop-windows-custom-text-to-voice-software-using-whisper-and-ahk/"><u>How to Develop Window's Custom Text-To-Voice Software Using Whisper & AHK</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reactivate-nonfunctional-wsreset-service-in-windows/"><u>How to Reactivate Nonfunctional WSReset Service in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/improving-memory-footprint-in-ms-teams/"><u>Improving Memory Footprint in MS Teams</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-8-ways-to-transfer-photos-from-xiaomi-13t-pro-to-iphone-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 8 Ways to Transfer Photos from Xiaomi 13T Pro to iPhone Easily | Dr.fone</u></a></li>
<li><a href="https://article-helps.techidaily.com/in-2024-compreenhensive-review-djis-new-drone-the-inspire-1/"><u>In 2024, Compreenhensive Review  DJI's New Drone, The Inspire 1</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-apple-iphone-14-pro-max-activation-lock-by-drfone-ios/"><u>In 2024, How to Remove Apple iPhone 14 Pro Max Activation Lock</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-realme-11-proplus-phone-password-without-factory-reset-by-drfone-android/"><u>In 2024, How to Unlock Realme 11 Pro+ Phone Password Without Factory Reset?</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-market-mastery-strategys-first-impressions/"><u>In 2024, Market Mastery  Strategy's First Impressions</u></a></li>
<li><a href="https://windows11.techidaily.com/integrating-nas-into-mobile-device-setups/"><u>Integrating NAS Into Mobile Device Setups</u></a></li>
<li><a href="https://windows11.techidaily.com/1719382274392-is-your-hardware-upgraded-for-win11-find-out/"><u>Is Your Hardware Upgraded For Win11? Find Out</u></a></li>
<li><a href="https://windows11.techidaily.com/method-for-handling-device-access-issues-with-audacity-win/"><u>Method for Handling Device Access Issues with Audacity (Win)</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-securely-enabling-controlled-folder-access-in-windows-11/"><u>Navigate Securely: Enabling Controlled Folder Access in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-restrictions-to-write-files-in-windows-11-os/"><u>Overcoming Restrictions to Write Files in Windows 11 OS</u></a></li>
<li><a href="https://extra-tips.techidaily.com/pushing-the-boundaries-of-fb-video-speed/"><u>Pushing the Boundaries of FB Video Speed</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaim-default-speaker-levels-post-windows-update/"><u>Reclaim Default Speaker Levels Post-Windows Update</u></a></li>
<li><a href="https://windows11.techidaily.com/safeguard-files-with-windows-controlled-access-feature/"><u>Safeguard Files with Window's Controlled Access Feature</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/screen-recorder-mac-with-audio-for-2024/"><u>Screen Recorder Mac with Audio for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-reliable-remote-connections-in-windows-environment/"><u>Securing Reliable Remote Connections in Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/steering-clear-of-disconnect-issues-in-nvidia-software/"><u>Steering Clear of Disconnect Issues in Nvidia Software</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-setting-up-a-trio-of-widget-boards-in-windows-11/"><u>Step by Step: Setting Up a Trio of Widget Boards in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-reactivate-apps-hindered-by-qt-plugin-issue/"><u>Steps to Reactivate Apps Hindered by Qt Plugin Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-rectify-faulty-cpu-usage-in-windows-management-console/"><u>Steps to Rectify Faulty CPU Usage in Windows Management Console</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-rectify-preview-failures-in-outlook-for-pcs/"><u>Steps to Rectify Preview Failures in Outlook for PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-gaming-experience-installing-windows-on-steam-deck/"><u>Streamline Your Gaming Experience: Installing Windows on Steam Deck</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-flush-for-your-win11-dns-cache/"><u>The Ultimate Flush for Your Win11 DNS Cache</u></a></li>
<li><a href="https://windows11.techidaily.com/tricks-to-extend-the-wait-window-in-windows-10-before-restarting/"><u>Tricks to Extend the Wait Window in Windows 10 Before Restarting</u></a></li>
<li><a href="https://fox-that.techidaily.com/ultimate-guide-top-15-solutions-to-common-issues-on-any-iphone/"><u>Ultimate Guide: Top 15 Solutions to Common Issues on Any iPhone</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-disabled-programs-in-windows/"><u>Unblocking Disabled Programs in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-power-of-local-gpo-control-on-windows-11/"><u>Unlock the Power of Local GPO Control on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-10-keys-a-step-by-step-guide/"><u>Unlocking Windows 10 Keys: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-hidden-potential-essential-tips-on-windows-narrator-commands/"><u>Unveiling the Hidden Potential: Essential Tips on Windows Narrator Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/wireless-mouse-woes-on-windows-heres-what-to-do/"><u>Wireless Mouse Woes on Windows? Here's What to Do</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>