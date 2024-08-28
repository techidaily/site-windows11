---
title: Filter Outuseless Windows Updates
date: 2024-08-27T16:08:01.168Z
updated: 2024-08-28T16:08:01.168Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Filter Outuseless Windows Updates
excerpt: This Article Describes Filter Outuseless Windows Updates
keywords: Filter Unwanted Windows Update,Stop Superfluous Windows Updates,Eliminate Frivolous Windows Updates,Windows Updates,Avoid Unnecessary Windows Patches,Minimize Irrelevant Windows Updates,Reduce Non-Critical Windows Changes
thumbnail: https://thmb.techidaily.com/069b298bfedee9c280f30a09eb725e41e8884f90fc111239be7bdf14c7e0c06b.jpg
---

## Filter Outuseless Windows Updates

 Are you tired of constantly seeing tips and suggestions on your computer screen? Want to mute them and concentrate on your work uninterrupted? Don’t worry - the process is quick and straightforward.

 In this article, we’ll discuss how to turn off or disable tips and suggestions notifications on Windows 11\.

## How to Turn Off or Disable Tips and Suggestions Notifications in Windows 11

 Tips and suggestions provide quick guides to Windows and its features. But if you find them annoying, you can turn them off. Here are two easy methods to turn off tips and suggestions notifications on Windows 11\.

### 1\. How to Turn Off Tips and Suggestions Using System Settings

 To turn off tips and suggestions on your computer, you can use the System Settings. This is the easiest and quickest way to mute these notifications. Here's how to do it:

1. Press **Win + I** to open the Settings window.
2. From the left panel, click on the **System** tab.
3. In the System Settings sub-panel, click on the **Notifications** section.  
![Open System Notification Section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/open-system-notification-section.jpg)
4. Next, scroll down to the bottom and expand **Additional settings**.  
![Get tips and suggestions when using Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/get-tips-and-suggestions-when-using-windows.jpg)
5. You will see a checkbox labeled **Get tips and suggestions when using Windows**. Uncheck it to turn off this feature.

 Now, you will not see any tips and suggestions notifications on your computer. If later you wish to re-enable this feature, follow the same steps outlined above and check the "Get tips and suggestions when using Windows" checkbox. Doing this will enable tips and suggestions notifications on your computer.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. Turn Off Tips and Suggestions Using a REG File

 If the system setting is unresponsive, you can use a REG file instead. This procedure creates a REG file with the necessary commands. Although it may seem complex, it is actually quite simple.

 Here are the steps to follow:

1. [Open the Notepad application](https://www.makeuseof.com/windows-11-open-notepad/).
2. Copy and paste the following code into it:  
`Windows Registry Editor Version 5.00  

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\ContentDeliveryManager]  
"SubscribedContent-338389Enabled"=dword:00000000`
3. Now save the file with the **.reg** extension.
4. Double-click on the file you just created to open it, and click **Yes** in the confirmation dialog box that appears.

 This will turn off tips and suggestions notifications in Windows 11\. To enable these notifications once again, delete the file you just created. Alternatively, double-click on it and click **No** in the confirmation dialog.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Disable Tips and Suggestions Notifications in Windows 11

 If you prefer to disable tips and suggestions notifications on your computer completely, there are several options available. You can utilize the Group Policy Editor, modify the registry editor, or create a REG file. Let's explore each method in detail to disable this feature.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->
### 1\. Disable Tips and Suggestions Notifications Using Group Policy Editor

 To turn off notifications for tips and suggestions, access the Group Policy Editor. This tool is available for Windows Pro, Education, and Enterprise users. However, it won't work if you use Windows Home Edition.

 In such cases, you must first [activate the Group Policy Editor for Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). Once done, follow the steps below to disable notifications for tips and suggestions:

1. Press **Win + R** to open the Run window.
2. Type **gpedit.msc** in the Run dialog box and press Enter. This will launch the Group Policy Editor window on your screen.
3. On the left side of the window, navigate to the following path:  
Computer Configuration > Administrative Templates > Windows Components > Cloud Content​
4. On the right side of the window, double-click on the **Do not show Windows tips** policy.  
![Do not Show Windows Tips](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/do-not-show-windows-tips.jpg)
5. From the box that appears, select the **Enabled** radio button.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
6. Click **Apply** \> **OK** to save the changes.

 Now, tips and suggestions notifications will be completely disabled on your computer. To re-enable the feature, follow the same steps and select the **Not Configured** or **Disabled** radio button instead.

### 2\. Disable Tips and Suggestions Notifications Using the Registry Editor

 If you can’t access the Group Policy Editor or activate it, you can modify the registry editor to disable these notifications. The procedure is slightly more technical and requires caution while making changes. It may even wreck your computer system, so proceed cautiously.

 To avoid risks, [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first. That way, you can restore the original settings if required. Once you have taken these precautionary steps, follow the instructions below to disable tips and suggestions notifications:

1. Press the **Windows** key to open the Start Menu.
2. Type **regedit** in the search box and select the **Registry Editor** app from the search results.
3. If the UAC window appears, click **Yes** to grant permission.
4. In the Registry Editor window, navigate to the following path:  
HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\CloudContent
5. If the **CloudContent** key is missing, create a new one. To do this, right-click on the Windows folder and select **New** \> **Key**. Name it **CloudContent**.
6. On the right side of the window, right-click on an empty area and select **New** \> **DWORD (32-bit) Value**.
7. Name the value **DisableSoftLanding** and hit Enter.  
![Disable Tips and Suggestions Notifications Using the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-tips-and-suggestions-notifications-using-the-registry-editor.jpg)
8. Double-click on this newly created entry and set its Value data to **1**.
9. Click **OK** to save the changes. Now, exit the registry editor window and restart your computer.

 After restarting, tips and suggestions notifications will be disabled on your computer. If you want to enable the feature, follow the same steps and change the Value data to **0**.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->
### 3\. Disable Tips and Suggestions Notifications Using a REG File

 You can also create a REG file to turn off tips and suggestions notifications on your Windows PC. This method is quite similar to the one we discussed above. However, the process is easier for those with little experience editing registry files.

 To disable tips and suggestions notifications using a REG file, follow the steps outlined below:

1. Search for **Notepad** and select the result from the list.
2. Copy and paste the code below into the Notepad window.  
`Windows Registry Editor Version 5.00  

[HKEY_CURRENT_USER\Software\Policies\Microsoft\Windows\CloudContent]  
"DisableSoftLanding"=dword:00000001`
3. Save the file with the .reg extension. Make sure that the Save as type field is set to **All files**.
4. Now, double-click on the file and click **Yes** at the prompt.

 That’s it! Tips and suggestions feature is now disabled on your computer.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4693127&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.videosoftdev.com/images/video_editor/screenshots/1.jpg" border="0">
VSDC Pro Video Editor is a light professional non-linear video editing suite for creating a movie of any complexity. It supports the most popular video/audio formats and codecs, including 4K, HD and GoPro videos. Preconfigured profiles make the creation of videos for various multimedia and mobile devices absolutely hassle-free.

Key features:

•	Import from any devices and cams, including GoPro and drones. All formats supported. Сurrently the only free video editor that allows users to export in a new H265/HEVC codec, something essential for those working with 4K and HD.
•	Everything for hassle-free basic editing: cut, crop and merge files, add titles and favorite music
•	Visual effects, advanced color correction and trendy Instagram-like filters   
•	All multimedia processing done from one app: video editing capabilities reinforced by  a video converter, a screen capture, a video capture, a disc burner and a YouTube uploader
•	Non-linear editing: edit several files with simultaneously 
•	Easy export to social networks: special profiles for YouTube, Facebook, Vimeo, Twitter and Instagram
•	High quality export – no conversion quality loss, double export speed even of HD files due to hardware acceleration
•	Stabilization tool will turn shaky or jittery footage into a more stable video automatically. 
•	Essential toolset for professional video editing: blending modes, Mask tool, advanced multiple-color Chroma Key  
</a>
<!-- affiliate ads end -->
## Stop the Windows Tips and Suggestions Notifications

 We hope that this article helped you understand how to turn off or disable tips and suggestions notifications in Windows 11\. All it takes are a few clicks or a simple REG file to enable or disable this feature.

 In this article, we’ll discuss how to turn off or disable tips and suggestions notifications on Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-videos.techidaily.com/new-bringing-heartwarmth-to-the-winter-5-snug-cinematographic-tips/"><u>[New] Bringing Heartwarmth to the Winter  5 Snug Cinematographic Tips</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-make-every-snap-count-with-these-top-tips/"><u>[New] In 2024, Make Every Snap Count with These Top Tips</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-top-ranked-4k-screen-recorders-summarized/"><u>[New] Top-Ranked 4K Screen Recorders Summarized</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-behind-the-scenes-insights-for-instagram-story-audience-for-2024/"><u>[Updated] Behind the Scenes  Insights for Instagram Story Audience for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-craft-a-compelling-narrative-with-your-igtv-video-titles-and-texts-for-2024/"><u>[Updated] Craft a Compelling Narrative with Your IGTV Video Titles & Texts for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-storage-galore-selecting-top-ps5-hddsssds-for-2024/"><u>[Updated] Storage Galore  Selecting Top PS5 HDDs/SSDs for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-the-ultimate-guide-to-selecting-frame-rate-for-hd-recording/"><u>[Updated] The Ultimate Guide to Selecting Frame Rate for HD Recording</u></a></li>
<li><a href="https://fox-links.techidaily.com/digital-filmmakers-lifeline-mastering-avi-conversions-into-dynamic-gifs-with-filmora-windowsmacos-for-2024/"><u>Digital Filmmakers' Lifeline  Mastering AVI Conversions Into Dynamic GIFs with Filmora (Windows/macOS) for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/expeditiously-mute-windows-11-pings/"><u>Expeditiously Mute Windows 11 Pings</u></a></li>
<li><a href="https://fake-location.techidaily.com/fixing-foneazy-mockgo-not-working-on-xiaomi-redmi-note-12r-drfone-by-drfone-virtual-android/"><u>Fixing Foneazy MockGo Not Working On Xiaomi Redmi Note 12R | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-through-windows-media-storage-woes-in-cam/"><u>Guiding Through Windows Media Storage Woes in Cam</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-combat-fall-guys-gameplay-interruptions-on-windows-devices/"><u>How To Combat Fall Guys Gameplay Interruptions on Windows Devices</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-convert-avchd-mts-to-mp4-for-redmi-note-12-4g-by-aiseesoft-video-converter-play-mts-on-android/"><u>How to convert AVCHD MTS to MP4 for Redmi Note 12 4G?</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-detect-and-stop-mspy-from-spying-on-your-xiaomi-14-ultra-drfone-by-drfone-virtual-android/"><u>How to Detect and Stop mSpy from Spying on Your Xiaomi 14 Ultra | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-unresponsive-keys-on-your-microsoft-windows-computer-versions-11-7-and-8/"><u>How to Fix Unresponsive Keys on Your Microsoft Windows Computer (Versions 11, 7 & 8)</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-a-damaged-video-file-of-lava-blaze-2-5g-using-video-repair-utility-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair a Damaged video file of Lava Blaze 2 5G using Video Repair Utility on Mac?</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-fix-pokemon-go-route-not-working-on-lava-yuva-2-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix Pokemon Go Route Not Working On Lava Yuva 2? | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-merge-soundtracks-and-cinematography-in-premiere-pro/"><u>In 2024, Merge Soundtracks and Cinematography in Premiere Pro</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-mirthful-browsings-your-ultimate-list-of-top-comedy-vids/"><u>In 2024, Mirthful Browsings  Your Ultimate List of Top Comedy Vids</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-the-pros-and-cons-of-tiktok-and-youtube-shorts-for-personal-usage/"><u>In 2024, The Pros & Cons of TikTok and YouTube Shorts for Personal Usage</u></a></li>
<li><a href="https://windows11.techidaily.com/is-the-intel-unison-app-not-working-on-windows-11-heres-how-to-fix-it/"><u>Is the Intel Unison App Not Working on Windows 11? Here's How to Fix It</u></a></li>
<li><a href="https://windows11.techidaily.com/launching-startup-repair-in-windows-a-guide/"><u>Launching Startup Repair in Windows: A Guide</u></a></li>
<li><a href="https://fox-access.techidaily.com/mastering-audio-file-transformation-srt-to-xmlssattml-for-2024/"><u>Mastering Audio File Transformation  SRT to XML/SSA/TTML for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/mitigating-virtual-reality-nausea/"><u>Mitigating Virtual Reality Nausea</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-fixed-windows-update-blockades/"><u>Navigating Fixed Windows Update Blockades</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-past-s-mode-a-windows-users-roadmap/"><u>Navigating Past 'S Mode': A Windows User's Roadmap</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-error-0x80070194-on-windows-onedrive/"><u>Overcoming Error 0X80070194 on Windows' OneDrive</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-dilemma-of-disrupted-device-use-by-other-software/"><u>Overcoming the Dilemma of Disrupted Device Use by Other Software</u></a></li>
<li><a href="https://windows11.techidaily.com/postponing-edges-tab-transition-on-windows-11/"><u>Postponing Edge's Tab Transition on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/power-up-your-command-line-discover-the-top-20-cmd-commands/"><u>Power Up Your Command Line: Discover the Top 20 CMD Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/proven-strategies-for-combining-diverse-windows-partitions/"><u>Proven Strategies for Combining Diverse Windows Partitions</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-to-mend-operation-0x0000011b-error-on-windows-11/"><u>Quick Guide to Mend Operation 0X0000011B Error on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-display-driver-startup-issue-in-windows-11/"><u>Remedying Display Driver Startup Issue in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-steam-cloud-connectivity-issues/"><u>Resolving Steam Cloud Connectivity Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/restarting-method-for-a-non-functional-windows-11-wi-fi-connection/"><u>Restarting Method for a Non-Functional Windows 11 Wi-Fi Connection</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-lost-wi-fi-connection-on-windows-11-devices/"><u>Restoring Lost Wi-Fi Connection on Windows 11 Devices</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/seamless-youtube-video-transfer-for-ios-devices-explained-for-2024/"><u>Seamless YouTube Video Transfer for iOS Devices Explained for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-video-lags-in-chromes-youtube-viewing/"><u>Solving Video Lags in Chrome's YouTube Viewing</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-for-windows-11-dolby-atmos-audio/"><u>Step-by-Step for Windows 11: Dolby Atmos Audio</u></a></li>
<li><a href="https://windows11.techidaily.com/stepwise-approach-enabling-wordpad-in-windows/"><u>Stepwise Approach: Enabling WordPad in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-avoid-perpetual-network-logon-errors/"><u>Strategies to Avoid Perpetual Network Logon Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/tech-tip-accessing-windows-11-sticky-notes-easily/"><u>Tech Tip: Accessing Windows 11 Sticky Notes Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-govern-devices-on-slumbering-pcs/"><u>Techniques to Govern Devices on Slumbering PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-making-your-cursor-stand-out-in-windows-11/"><u>The Ultimate Guide to Making Your Cursor Stand Out in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-to-address-steams-file-privilege-problem-in-win11/"><u>Tips to Address Steam's File Privilege Problem in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/turn-on-copy-and-paste-within-edges-protected-area-win-11-edition/"><u>Turn On Copy & Paste Within Edge's Protected Area, Win 11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/unblocking-msstore-from-error-0x0-issue-in-windows-os/"><u>Unblocking MsStore From Error 0X0 Issue in Windows OS</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/unveiling-streaming-screens-using-netflixs-pip-mode-for-2024/"><u>Unveiling Streaming Screens  Using Netflix's PIP Mode for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-power-of-openais-whisper-on-your-windows-pc/"><u>Unveiling the Power of OpenAI's Whisper on Your Windows PC</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-from-steps-to-strides-the-best-motion-tracking-apps/"><u>Updated From Steps to Strides The Best Motion Tracking Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/why-choose-linux-without-windows-subsystem/"><u>Why Choose Linux without Windows Subsystem?</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-faces-issue-file-thumbnails-not-appearing/"><u>Windows 11 Faces Issue: File Thumbnails Not Appearing</u></a></li>
<li><a href="https://sound-issues.techidaily.com/winning-strategies-for-repairing-audio-on-a-windows-10-pc-all-issues-addressed/"><u>Winning Strategies for Repairing Audio on a Windows 10 PC - All Issues Addressed</u></a></li>
<li><a href="https://windows11.techidaily.com/winwm-energy-hack-lowering-gpu-draw-in-windows-11/"><u>WinWM Energy Hack: Lowering GPU Draw in Windows 11</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>