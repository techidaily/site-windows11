---
title: Unsupported Devices? Here’s How to Elevate with Win11 22H2
date: 2024-08-27T16:14:00.362Z
updated: 2024-08-28T16:14:00.362Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unsupported Devices? Here’s How to Elevate with Win11 22H2
excerpt: This Article Describes Unsupported Devices? Here’s How to Elevate with Win11 22H2
keywords: Upgrade Windows 11,Elevate Unsupported PCs,Installing Win11 22H2,Fix Device Issues W11,Enhance Old Computers,Run Latest Windows OS,Optimize Devices with Win11
thumbnail: https://thmb.techidaily.com/7cdccda0c1b455cde02be352d145a5b4b55f977ca27570cd9c8cff441c6409c8.jpg
---

## Unsupported Devices? Here’s How to Elevate with Win11 22H2

 If you have installed Windows 11 on unsupported hardware, the upgrade process will be a tough task. When you try to look for an update, Windows 11 shows everything as up to date and has no option to install the 22H2 version.

 While you can use the ISO-based clean install method, the upgrade process lets you install the latest version without deleting your apps and other data. Here’s how to upgrade to Windows 11 22H2 on unsupported hardware using the Windows 11 setup file.

## How to Upgrade to Windows 11 22H2 on Unsupported Hardware

[Windows 11 runs a hardware compatibility check](https://www.makeuseof.com/check-computer-compatible-windows-11-22h2/) during the upgrade process. To perform a successful upgrade, you’ll need to work around this hardware compatibility assessment. To achieve this, we’ll replace the appraiserress.dll file in Windows 11 ISO with the appraiserress.dll from Windows 10 ISO.

 If you have Windows 11 22H2 and Windows 10 ISO available, skip to the third step below. If not, follow all the steps to download the necessary ISOs and then perform an upgrade.

 While these steps shouldn’t cause any issues, it is better to[create a backup of any important Windows 11 data](https://www.makeuseof.com/windows-11-create-complete-backup/) on your system drive just in case something goes wrong and you need to perform a clean install.

## 1\. Download the Windows 11 22H2 ISO

![iso file download windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/iso-file-download-windows-11.jpg)

 You can[legally download the Windows 11 ISO](https://www.makeuseof.com/windows-11-download-iso/) from the Microsoft server directly or using Media Creation Tool. For this guide, we’ll use Media Creation Tool to download the ISO image file.

1. Go to the[Microsoft Software Download page](https://www.microsoft.com/software-download/windows11) .
2. Click on**Download Now** under**Create Windows 11 Installation Media.**
3. Run the**mediacreationtool.exe** file and accept the license terms.
4. Review the selected language and edition. To change the language, uncheck**Use the recommended options for this PC** and select your preferred language.
5. Click**Next** .
6. Select the**ISO file** option in the**Choose which media to use** dialog.
7. Select the download location and click**Save** . Make sure the selected partition has enough space available.
8. Media Creation Tool will start downloading the ISO to your local drive. This process may take some time, depending on your Internet connection. So wait for the download to complete.
9. Once the download is complete, click**Finish** and follow the next step to download Windows 10 ISO.

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->
## 2\. Download a Windows 10 ISO

![windows 10 download ISO preference](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-10-download-iso-preference.jpg)

 You’ll need to modify the Windows 11 ISO by replacing the appraiserress.dll with a version available in Windows 10 ISO. This DLL file is responsible for performing a hardware check during an upgrade.

To download Windows 10 ISO:

1. Go to[Windows 10 download page](https://www.microsoft.com/en-us/software-download/windows10) .
2. Click the**Download Now** button under**Create Windows 10 installation media** .
3. Run the**mediacreationtool.exe** file to open Windows 10 Setup dialog.
4. Click on**Accept** .
5. In the**What do you want to do** screen, select**Create installation media** and click**Next** .
6. Check if the language, edition, and architecture preferences are set correctly. If not, click on**Use the recommended options for this** **device** and set your preferences.
7. Next, select the**ISO file** option and click**Next** .
8. Select the download location and click**Save** .
9. The downloading process may take several minutes to complete. So wait for the process to complete and click**Finish** once done.

 Once you have both the ISO files saved, follow the next step to extract and modify the Windows 11 ISO.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Modify the Windows 11 ISO to Bypass Hardware Check During the Upgrade

 The following steps involve extracting the Windows 10 ISO and copying the appraiserress.dll file. Next, move the copied DLL file to the Windows 11 ISO’s sources folder. Here’s how to do it.

1. Right-click on the**Windows 10 ISO** file and select**Mount** . This will create a new virtual DVD Drive and open the ISO folder.  
![mount windows 10 iso](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/mount-windows-10-iso.jpg)
2. Open the**Sources** folder and locate the**appraiserres.dll** file. Copy the**DLL** file and move it to a different folder.  
![copy appraiserres dll windows 10 iso](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/copy-appraiserres-dll-windows-10-iso.jpg)
3. Next, extract the Windows 11 ISO to a different folder. You can[use WinRAR to extract](https://www.win-rar.com/start.html?&L=0) the Windows 11 ISO file.  
<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->
![extract windows 11 iso](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/extract-windows-11-iso.jpg)
4. Open the Windows 11 ISO's extracted folder and then the**Source** folder.
5. Next, copy and paste the**appraiserres.dll** file copied from Windows 10 ISO into Windows 11 ISO's**Sources** folder.

1. Select**Replace the file in the destination** to confirm the action.  
![replace the file in the destination appraiserrs ll windows 11 iso](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/replace-the-file-in-the-destination-appraiserrs-ll-windows-11-iso.jpg)
2. Next, disconnect your PC from the Internet. This prevents the setup from downloading updated files during installation and overwriting the modified dll file.
3. Once the Internet is disabled, open the extracted Windows 11 ISO folder and double-click on the**Setup file** . Click**Yes** if prompted by UAC.
4. In the**Windows 11 Setup** dialog, click on**Change how Setup downloads updates.**  
![windows 11 setup not right now updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-11-setup-not-right-now-updates.jpg)
5. Next, select**Note right now.** This will prevent the Windows setup from finding and installing newer updates causing the upgrade process to fail on unsupported hardware.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![windows 11 setup choose what to install](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-11-setup-choose-what-to-install.jpg)
6. In the**Choose what to keep** screen, select**Keep personal files and apps.**
<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Click**Next** and then click on**Accept** .  
![windows 11 setup ready to install](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-11-setup-ready-to-install.jpg)
8. Next, click on**Install** to install Windows 11 version 22H2 while keeping your personal files and apps.
<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
9. Leave your computer idle until the installation process is complete. After the restart, you’ll have the latest Windows 11 22H2 running on your computer.

To check your Windows specification:

![check windows specification windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/check-windows-specification-windows-11.jpg)

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, scroll down and click on**About** .
3. Under Windows specifications, you’ll see**Version 22H2** if the upgrade was successful.

## 4\. Go Back to the Previous Version

![go back windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/go-back-windows-11.jpg)

 If you run into an issue after the upgrade, you can use the**Go back** option to undo the update and restore the earlier version of Windows 11\. However, the "Go back" option is only available for seven days since the upgrade. After that, the option will be greyed out.

To go back to the previous version:

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, scroll down and click on**Recovery** .
3. Click on**Go back** under**Recovery options** . Then, follow the on-screen instructions to uninstall the Windows 22H2 update.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Installing Windows 11 22H2 on Unsupported Hardware

 It is easy to bypass the Windows 11 system hardware requirements when you want to perform a clean install. However, to perform an upgrade, you’ll need to modify the appraiserress.dll file and then run the setup.

 While the upgrade is possible for now, the lack of future automatic Windows updates makes maintaining the PC a complicated task. If upgrading to Windows 11 is not a must, you can stick to Windows 10 on older hardware, which will continue to receive support until late 2025.


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
<li><a href="https://facebook-video-share.techidaily.com/new-audience-wow-factor-the-best-camera-lenses-for-youtube-stars-for-2024/"><u>[New] Audience Wow Factor  The Best Camera Lenses for YouTube Stars for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-enter-the-arena-your-guide-to-social-tiktok-streaming-for-2024/"><u>[New] Enter the Arena  Your Guide to Social TikTok Streaming for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-screencapture-simplified-an-in-depth-camstudio-review-for-2024/"><u>[Updated] ScreenCapture Simplified  An In-Depth CamStudio Review for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-solutions-for-restarting-frozen-obs-fullscreen/"><u>[Updated] Solutions for Restarting Frozen OBS Fullscreen</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-unlocking-your-online-opportunities-a-complete-guide-to-measuring-views-revenue-and-growth/"><u>[Updated] Unlocking Your Online Opportunities  A Complete Guide to Measuring Views, Revenue, and Growth</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-ascending-altitudes-in-depth-analysis-of-the-gopro-karma-drone/"><u>2024 Approved  Ascending Altitudes  In-Depth Analysis of the GoPro Karma Drone</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-techniques-to-transfer-data-from-tecno-spark-20-pro-to-iphone-15141312-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Techniques to Transfer Data from Tecno Spark 20 Pro to iPhone 15/14/13/12 | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/clearview-techniques-for-superior-video-with-vce-2-written-by-john-doe-phd/"><u>ClearView Techniques for Superior Video with VCE 2 Written by John Doe, PhD</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/diagnosing-and-resolving-issues-with-a-malfunctioning-samsung-soundbar/"><u>Diagnosing and Resolving Issues with a Malfunctioning Samsung Soundbar</u></a></li>
<li><a href="https://windows11.techidaily.com/expeditiously-mute-windows-11-pings/"><u>Expeditiously Mute Windows 11 Pings</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-semaphore-timeout-period-has-expired-error-0x80070079-in-windows-1110/"><u>How to Fix the “Semaphore Timeout Period Has Expired” Error 0X80070079 in Windows 11/10</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-remove-the-onedrive-icon-from-file-explorer-in-windows-11/"><u>How to Remove the OneDrive Icon From File Explorer in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-set-up-your-own-keyboard-shortcuts-in-windows-11/"><u>How to Set Up Your Own Keyboard Shortcuts in Windows 11</u></a></li>
<li><a href="https://techidaily.com/how-to-update-or-downgrade-apple-iphone-6s-plus-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade Apple iPhone 6s Plus? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-4-most-known-ways-to-find-someone-on-tinder-for-asus-rog-phone-7-ultimate-by-name-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Most-Known Ways to Find Someone on Tinder For Asus ROG Phone 7 Ultimate by Name | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-8-best-apps-for-screen-mirroring-honor-magic-6-pro-pc-drfone-by-drfone-android/"><u>In 2024, 8 Best Apps for Screen Mirroring Honor Magic 6 Pro PC | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-icecream-screen-recorder-indepth-review/"><u>In 2024, Icecream Screen Recorder Indepth Review</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-optimal-media-transfer-top-free-youtube-mp3-apps-revealed/"><u>In 2024, Optimal Media Transfer  Top Free YouTube-MP3 Apps Revealed</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-solutions-to-spy-on-vivo-y27s-with-and-without-jailbreak-drfone-by-drfone-virtual-android/"><u>In 2024, Solutions to Spy on Vivo Y27s with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-unlock-your-oppo-f25-pro-5g-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>In 2024, Unlock Your Oppo F25 Pro 5G Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/integrating-ios-calendar-with-windows-a-practical-guide/"><u>Integrating iOS Calendar with Windows: A Practical Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/is-the-intel-unison-app-not-working-on-windows-11-heres-how-to-fix-it/"><u>Is the Intel Unison App Not Working on Windows 11? Here's How to Fix It</u></a></li>
<li><a href="https://windows11.techidaily.com/merge-functionality-and-elegance-in-windows-10plus/"><u>Merge Functionality and Elegance in Windows 10+</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-fixed-windows-update-blockades/"><u>Navigating Fixed Windows Update Blockades</u></a></li>
<li><a href="https://windows11.techidaily.com/postponing-edges-tab-transition-on-windows-11/"><u>Postponing Edge's Tab Transition on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/proven-strategies-for-combining-diverse-windows-partitions/"><u>Proven Strategies for Combining Diverse Windows Partitions</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-display-driver-startup-issue-in-windows-11/"><u>Remedying Display Driver Startup Issue in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/removing-curved-edges-from-windows-11/"><u>Removing Curved Edges From Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-for-windows-11-dolby-atmos-audio/"><u>Step-by-Step for Windows 11: Dolby Atmos Audio</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-reversing-loadlibrary-misload-on-windows/"><u>Techniques for Reversing LoadLibrary Misload on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-hidden-power-of-windows-firewall-management/"><u>The Hidden Power of Windows' Firewall Management</u></a></li>
<li><a href="https://windows11.techidaily.com/the-quickest-way-to-shift-your-windows-qbittorrent-software/"><u>The Quickest Way to Shift Your Windows qBittorrent Software</u></a></li>
<li><a href="https://windows11.techidaily.com/the-transformation-ai-integration-into-windows-11/"><u>The Transformation: AI Integration Into Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-to-address-steams-file-privilege-problem-in-win11/"><u>Tips to Address Steam's File Privilege Problem in Win11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-6-appsservices-to-trace-any-poco-x5-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>Top 6 Apps/Services to Trace Any Poco X5 Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/turbocharge-your-windows-printer-with-quick-fixes/"><u>Turbocharge Your WIndows Printer with Quick Fixes</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-unlock-pro-level-videos-top-10-free-green-screen-apps-for-mobile/"><u>Updated In 2024, Unlock Pro-Level Videos Top 10 Free Green Screen Apps for Mobile</u></a></li>
<li><a href="https://windows11.techidaily.com/what-to-do-when-your-recent-discord-updates-breakdown-on-windows/"><u>What to Do When Your Recent Discord Updates Breakdown on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/winwm-energy-hack-lowering-gpu-draw-in-windows-11/"><u>WinWM Energy Hack: Lowering GPU Draw in Windows 11</u></a></li>
</ul></div>
