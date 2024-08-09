---
title: Quick Fixes for LSA Errors on Windows PCs
date: 2024-08-08T06:08:21.868Z
updated: 2024-08-09T06:08:21.868Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quick Fixes for LSA Errors on Windows PCs
excerpt: This Article Describes Quick Fixes for LSA Errors on Windows PCs
keywords: Fix RPC Errors Windows,Win RPC Quick Troubleshooting,Solve Windows RPC Issues,RPC Errors in Windows XP,Windows OS RPC Failures,Rush Repair for Windows Errors,Addressing Windows RPC Problems
thumbnail: https://thmb.techidaily.com/5a836c04a4d923a2e47e122afc97ffb5e93afa98d18b4563b5a8924a658295ed.jpg
---

## Quick Fixes for LSA Errors on Windows PCs

 LSA protection is a vital security feature on Windows that prevents unauthorized access to system resources. However, corrupt system files or malware infections may lead to an error stating "this change requires you to restart your device". This error persists even after enabling Local Security Authority (LSA) protection or restarting the computer.

 It suggests an underlying problem that requires resolution to restore system security. If you have the same problem, these solutions might help.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What Causes the LSA Protection Error?

 The exact cause of the “this change requires you to restart your device” error can vary, but it may be due to corrupted system files or malware infections. Malware can install malicious services and components that interfere with Windows' smooth functioning, including disabling Local Security Authority (LSA) protection. It can also occur if antivirus software incorrectly removes system files and causes instability.

 This error is usually triggered when Windows attempts to enable Local Security Authority (LSA) protection and fails. In some cases, the error may also appear after you enabled LSA protection and restarted your computer.

## 1\. Restart Your PC

 As the error message suggests, you first restart your Windows system. This minor step can fix several system-level errors and is worth a try. Restarting your computer involves shutting down all running programs and starting it up again.

## 2\. Scan for Malicious Programs

 If restarting the computer doesn't solve the issue, check your system for malicious software. Malware infections may corrupt system files and prevent LSA protection from working.

 To check if any malicious programs are on your system, do the following.

1. Press **Win + Q** on your keyboard to open the Taskbar search window.
2. Type **Windows Security** in the search bar and hit Enter.
3. On the left pane of Windows Security, click the **Virus & threat protection** tab.
4. Click **Scan options** on the right side of the screen.  
![Full Scan Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/full-scan-windows-security.jpg)
5. Select **Full scan** and click **Scan now**.

 Now wait for the scan to finish. If malicious programs are detected, Windows Security will remove them from your system automatically.

## 3\. Change the Group Policy Settings

 If the above steps don't help, you might need to configure LSA manually. It involves editing the Local Group Policy Editor and setting some specific settings. However, this tool only works with Windows 11 Professional and Enterprise editions.

 So, if you're running Windows Home Edition, you won't have access to Local Group Policy. To make this work, [enable the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/), then follow these steps:

1. Press **Win + R** on your keyboard to open the Run dialogue box.
2. Type **gpedit.msc** in the search box and hit Enter.
3. In the Local Group Policy Editor, expand **Computer Configuration** on the left side.
4. Then navigate to the following:  
Administrative Templates > System > Local Security Authority
5. Double-click **Configure LSASS to run as a protected process** in the right pane.  
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->
![Change the Group Policy Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-the-group-policy-settings.jpg)
6. Now, in the window that appears, alter the settings from **Not Configured** to **Enabled**.
7. Under the Options section, click the drop-down menu for **Configure LSASS to run as a protected process** and select **Enabled with UEFI Lock**.  
![Set as Enabled with UEFI Lock](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-as-enabled-with-uefi-lock.jpg)
8. Now click **Apply > OK** to save the changes.

 After making the above changes, restart your computer and check if the error is resolved.

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. Tweak the Registry Editor

 If you're running Windows Home edition, you can tweak the Registry Editor to modify Local Security Authority protection values. The steps are pretty straightforward, but be aware that making incorrect changes to the registry can cause serious problems. To be safe, [back up the Windows Registry data](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before making any changes.

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **regedit** in the dialog box and press the Enter key.
3. If UAC prompts appear on the screen, click **Yes** to grant permission.
4. In the Registry Editor window, navigate to the following location:  
Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Lsa  
 You can also copy and paste the given path into the address bar at the top of the Registry window. Then, hit Enter to jump directly to the folder.
5. In the right pane, double-click on **RunAsPPL** to open Edit DWORD (32-bit) Value.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->
![Change RunAsPPL regsitry values](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-runasppl-regsitry-values.jpg)
6. Change the Value data from 0 to **2** and click **OK**.
7. Similarly, find the **RunAsPPLBoot** key and set its value to **2**.  
 If you don't find the **RunAsPPL** and **RunAsPPLBoot** keys in the LSA folder, you'll need to create them manually. To do this, right-click on the LSA folder and select **New > DWORD (32-bit) Value**. Name the new value **RunAsPPL** and set its value to 2\. Then repeat this process for the **RunAsPPLBoot** key.

 Once you're done, close the Registry Editor and restart your computer. This should fix the problem.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Reset the Windows Security App

 Windows Security is an integrated antivirus program built into the Windows OS. It's responsible for scanning your system and removing malicious content. If there's something wrong with the Windows Security app, it might trigger this error. To fix the issue, reset the app and see if it helps. Here's how to do it:

1. Press **Win + I** on your keyboard to open the system settings.
2. Select **Apps** on the left side of the window.
3. Click **Installed apps** in the right pane
4. Scroll down the list of apps until you see **Windows Security**. You can also type Windows Security into the search bar to find it quickly.
5. Now click the three dots icon and select **Advanced options** from the menu.
6. On the next page, scroll down to the **Reset** section and click **Reset**.  
![Reset Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-windows-security.jpg)
7. If the confirmation window pops up, click **Reset** to continue.

 Wait for the reset process to finish and restart your computer. After restarting, check if the error is still present.

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
## 6\. Perform Some Generic Fixes

 There are also some generic fixes to resolve the issue. First, [run the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) command to repair incorrect or damaged system files. You may also want to use the Deployment Image Servicing and Management tool to diagnose issues with local system images. If the problem persists, try [updating Windows to the latest version](https://www.makeuseof.com/update-windows-manually/) to resolve any glitches or bugs.

 Some antivirus and security programs can be too aggressive in protecting your system. They could prevent access to the LSA feature, leading to this problem. To be sure, you can [temporarily disable your security software](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) and check if it solves the issue.

## Fixing the LSA Protection Error on Windows

 Local Security Authority protection safeguards unauthorized access to system resources, such as passwords or other sensitive information. However, this feature might not work as expected due to LSA Protection Error. Thanks to the potential solutions discussed in this guide, solving the problem is easy.

 It suggests an underlying problem that requires resolution to restore system security. If you have the same problem, these solutions might help.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-guidance.techidaily.com/new-tackling-blurred-images-in-online-meetings-with-zoom-techniques/"><u>[New] Tackling Blurred Images in Online Meetings with Zoom Techniques</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-top-5-best-capture-cards-for-nintendo-switch/"><u>[New] Top 5 Best Capture Cards for Nintendo Switch</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-mastering-negative-space-reverse-video-tricks-for-instagram/"><u>[Updated] 2024 Approved  Mastering Negative Space  Reverse Video Tricks for Instagram</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-5-tools-for-cutting-edge-video-title-and-tag-generation/"><u>[Updated] 5 Tools for Cutting Edge Video Title & Tag Generation</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-goofy-flick-an-analysis-of-the-goofy-movie/"><u>[Updated] Goofy Flick  An Analysis of 'The Goofy Movie'</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-in-2024-top-10-mobile-selections-efficiently-save-facebook-videos-on-android/"><u>[Updated] In 2024, Top 10 Mobile Selections  Efficiently Save Facebook Videos on Android</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-complete-catalog-of-livestreaming-cameras-review/"><u>[Updated] The Complete Catalog of Livestreaming Cameras Review</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-the-future-of-mobile-photography-with-xiaomis-mi-11-for-2024/"><u>[Updated] The Future of Mobile Photography with Xiaomi's Mi 11 for 2024</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-harmony-color-calibrator/"><u>2024 Approved  Harmony Color Calibrator</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/4-easy-ways-for-your-vivo-v30-lite-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>4 Easy Ways for Your Vivo V30 Lite 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/a-working-guide-for-pachirisu-pokemon-go-map-on-poco-c50-drfone-by-drfone-virtual-android/"><u>A Working Guide For Pachirisu Pokemon Go Map On Poco C50 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-windows-1011s-s-mode-bond-quickly/"><u>Breaking Windows 10/11’S S Mode Bond Quickly</u></a></li>
<li><a href="https://win-able.techidaily.com/complete-guide-fix-fifa-20-crashes-on-your-pc-without-a-glitch/"><u>Complete Guide: Fix FIFA 20 Crashes on Your PC Without a Glitch</u></a></li>
<li><a href="https://windows11.techidaily.com/drive-pc-tasks-swiftly-5-keyboard-cars-expertise/"><u>Drive PC Tasks Swiftly: 5 Keyboard Cars Expertise</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-dns-clearing-on-the-newest-windows-os/"><u>Effective DNS Clearing on the Newest Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-ways-to-erase-defenders-security-chronicles-in-windows/"><u>Efficient Ways to Erase Defender's Security Chronicles in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-transform-heic-photos-to-jpeg-via-windows-11/"><u>Efficiently Transform HEIC Photos to JPEG via Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-reminder-placement-on-windows-11-and-10/"><u>Effortless Reminder Placement on Windows 11 & 10</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-theme-changes-for-a-stylish-windows-11-desktop/"><u>Effortless Theme Changes for a Stylish Windows 11 Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-windows-updates-switching-to-new-amd-drivers/"><u>Effortless Windows Updates: Switching to New AMD Drivers</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-your-windows-screenshot-game-with-these-fixes/"><u>Elevating Your Windows Screenshot Game with These Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-ad-ds-errors-impacting-windows-11-printing/"><u>Eliminating AD DS Errors Impacting Windows 11 Printing</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-error-0x8024a205-in-windows-update/"><u>Eliminating Error 0X8024a205 in Windows Update</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-internal-failure-on-desktop-connections/"><u>Eliminating Internal Failure on Desktop Connections</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-issues-with-windows-alt-key-functions-47-characters/"><u>Eliminating Issues with Windows ALT Key Functions (47 Characters)</u></a></li>
<li><a href="https://windows11.techidaily.com/embedding-apple-calendar-data-in-windows-desktop-app/"><u>Embedding Apple Calendar Data in Windows Desktop App</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-failed-driver-loading-in-windows-11/"><u>Enabling Failed Driver Loading in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-printer-use-within-windows-11-edge-protection/"><u>Enabling Printer Use Within Windows 11 Edge Protection</u></a></li>
<li><a href="https://windows11.techidaily.com/end-the-saga-how-to-smoothly-sync-chromebook-files-in-windows/"><u>End the Saga: How to Smoothly Sync Chromebook Files in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/energy-efficiency-windows-rest-states-analysis/"><u>Energy Efficiency: Windows' Rest States Analysis</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-diagnostics-in-the-latest-windows-versions/"><u>Enhancing Diagnostics in the Latest Windows Versions</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-efficiency-crafting-shortcuts-next-to-power-on-windows-11/"><u>Enhancing Efficiency: Crafting Shortcuts Next to Power on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-user-experience-reactivating-silent-notifications/"><u>Enhancing User Experience: Reactivating Silent Notifications</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-window-operations-no-more-minimizing/"><u>Enhancing Window Operations: No More Minimizing</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicating-installation-failed-message-on-discord-for-windows/"><u>Eradicating 'Installation Failed' Message on Discord for Windows</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/essential-techniques-for-expanding-your-follower-base-on-twitter/"><u>Essential Techniques for Expanding Your Follower Base on Twitter</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-samsung-galaxy-a15-5g-phone-without-password-by-drfone-android/"><u>In 2024, How To Unlock Samsung Galaxy A15 5G Phone Without Password?</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-perfect-your-snapchat-boomerangs-quickly/"><u>In 2024, Perfect Your Snapchat Boomerangs Quickly</u></a></li>
<li><a href="https://article-tips.techidaily.com/in-2024-reviving-dull-images-the-most-effective-10-web-editing-aids/"><u>In 2024, Reviving Dull Images  The Most Effective 10 Web Editing Aids</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-skys-finest-cameras-clash-dji-air-2-vs-gopro-hero9-k4/"><u>In 2024, Sky's Finest Cameras Clash  DJi Air 2 VS GoPro HERO9 K4</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-ways-to-stop-parent-tracking-your-vivo-y78t-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to stop parent tracking your Vivo Y78t | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/sony-a6400-the-unseen-movie-problem/"><u>Sony A6400  The Unseen Movie Problem</u></a></li>
<li><a href="https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-htc-u23-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Troubleshooting Guide How to Fix an Unresponsive HTC U23 Screen | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-are-location-permissions-life360-on-samsung-galaxy-s24-ultra-drfone-by-drfone-virtual-android/"><u>What are Location Permissions Life360 On Samsung Galaxy S24 Ultra? | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>