---
title: Correcting 'Another Program Uses Device' In Windows Sound System
date: 2024-08-15T15:11:21.283Z
updated: 2024-08-16T15:11:21.283Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting 'Another Program Uses Device' In Windows Sound System
excerpt: This Article Describes Correcting 'Another Program Uses Device' In Windows Sound System
keywords: Windows Sound Correction,Device Conflict Resolution,Sound System Error Fix,PC Audio Issue Troubleshoot,Correcting Windows Sound Devices,Managing Shared Device Usage,Avoiding Program Device Clashes
thumbnail: https://thmb.techidaily.com/2e153e0e621bce9ac8484d65d8c4dd2eb6f5a3b85fbf991174fd2d0ac26c3edd.png
---

## Correcting 'Another Program Uses Device' In Windows Sound System

 The audio device on your Windows computer can simultaneously play audio from multiple sources. However, at times, the audio stops playing with the error "this device is being used by another application".

 This is error is often a case of incorrectly configured Windows Audio service. Other times, the audio issue is due to a corrupt audio device driver. Here we show you how to troubleshoot the "this device is being used by another application" error and restore audio on Windows.

## 1\. Run the Windows Audio Troubleshooter

![Windows 11 settings troubleshoot other troubleshooters playing audio run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-11-settings-troubleshoot-other-troubleshooters-playing-audio-run.jpg)

 Windows has a built-in audio troubleshooter to find and fix issues with playing audio. The troubleshooter looks for common audio issues and tries to fix them automatically.

To run the audio troubleshooter:

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, click on**Troubleshoot** .
3. Click on**Other troubleshooters** .
4. Next, click the**Run** button for**Playing Audio** . Wait for the audio troubleshooter to scan for issues. Then select the affected audio device and click**Next** .
5. Follow the on-screen instructions and check if the error is resolved.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
<!-- affiliate ads end -->
## 2\. Disable Exclusive Mode for the Audio Device

 By default, Windows applications can take exclusive control of the audio device. While enabling this option shouldn’t cause any issues, some apps may prevent the device from being used by other audio services. To fix the problem, disable exclusive mode to stop applications from taking exclusive control of the audio device.

To disable Exclusive Mode for the audio device on Windows:

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, click on**Sound** .
3. Scroll down and click on**More sound settings** .  
![more sound settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/more-sound-settings-windows-11.jpg)
4. Select the audio device in the**Sound** dialog and click the**Properties** button.
5. Open the**Advanced** tab in the**Properties** dialog.  
![disable exclusive mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-exclusive-mode.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
6. Uncheck the **Allow application to take exclusive control of this device** and**Give exclusive mode application priority** options.
7. Click**Apply** and**OK** to save the changes.

 Restart your computer and check if the error is resolved and if the audio device is working again.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Change Windows Audio Service Startup Type

 Windows Audio service is responsible for managing audio devices connected to your computer. If the service is disabled or not running, your audio device can stop working.

 By default, it is set to start automatically as you power on your device. Check if the Startup type for Windows Audio is set to Manually. If yes, reconfigure it to start automatically to fix audio problems.

To change the Windows Audio service Startup type:

1. Press**Win + R** to open**Run** .
2. Type**services.msc** and click**OK** to open the**Services** snap-in.
3. In the**Services** window, locate and double-click on**Windows Audio** service.  
![windows audio service properties services snap in](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-audio-service-properties-services-snap-in.jpg)
4. Click the**Startup** type drop-down and select**Automatic** .
5. Click**Apply** and**OK** to save the changes.  
![windows audio service startup type automatic](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-audio-service-startup-type-automatic.jpg)
6. If the service is not running, right-click on**Windows Audio** and select**Start** .
7. Close the Services snap-in and restart your PC. After the restart, your audio device should start working again.

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
## 4\. Disable and Re-Enable the Sound Output Device

 You can temporarily disable and re-enable the audio device to fix any glitches causing the device to malfunction. You can [disable the audio device](https://www.makeuseof.com/enable-disable-sound-output-devices-in-windows/) using the Settings app and Device Manager.

 To disable the audio device, right-click on the audio device and select**Disable device** in**Device Manager** . Next, right-click on the audio device and**Enable Device** . Close Device Manager and check for any improvements.

## 5\. Uninstall and Reinstall the Audio Device and Driver

![Uninstalling an audio device in Windows 11.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/uninstalling-audio-device-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can also troubleshoot your audio problems by uninstalling the audio device and the associated drivers. Reinstalling the audio device can help if the sound problem is due to corrupt audio drivers.

To uninstall your audio device on Windows:

1. Press**Win + X** to open the**WinX menu** .
2. Select**Device Manager** for the menu.
3. In Device Manager, expand the**Audio inputs and output section** .
4. Right-click on your audio device and select**Uninstall device** .
5. Read the warning and click**Uninstall** to confirm the action. Wait for the device to uninstall.

 You may see a yellow exclamation mark on the uninstalled audio device. To reinstall the driver, click on**File** and select**Scan for hardware changes** . This should reinstall the sound device and driver. If not, restart your computer. As the system restarts, Windows will reinstall the missing audio device driver and restore sound on your computer.

## 6\. Perform a Driver Rollback

 If you have an external sound card and have installed an update, try a driver rollback. A new driver update can sometimes create more problems than it intends to fix. You can use the device driver rollback feature in Device Manager to undo the changes and reinstall the older version of the driver.

 You can [roll back a driver using Windows Device Manager](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) . In Device Manager, expand the**Sound, Video, and Game Controllers** section. Next, access your external sound card properties to perform a rollback.

 If the Roll Back Driver option is greyed out, it means the option is unavailable for the selected device. In this instance, uninstall the existing audio device driver and download an older version of the driver from your sound card manufacturer's website. Your sound card manufacturer may also have a newer driver version available. If available, install the latest version and check for any improvements.

## 7\. Install Pending Windows Updates

![windows 11 view update history](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/winodws-11-view-update-history.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->

 If it is a Windows-specific issue, installing pending Windows updates can fix the problem. Check the Windows updates page for newer updates and install them to see if that helps resolve the issue.

 To install Windows update, go to**Settings > Windows Update** and click**Check for updates** . Windows will populate the screen with all the pending updates. You can install the updates or selectively install any audio device updates.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
## 8\. Check for Third-Party App Conflict

![volume mixer windows 11 view audio applications](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/volume-mixer-windows-11-view-audio-applications.jpg)

 If the issue persists, check if there is a third-party app conflict. You can use Volume Mixer to view applications accessing the audio devices and close the problematic app to fix the problem. Here’s how to do it.

1. Press**Win + R** to open Run.
2. Type**sndvol** and click**OK** to open Volume Mixer.
3. The**Application** column will show all the apps using your audio device.

 To close the app, open the system tray, right-click the app icon, and select**Quit** . You can also force close the app using Task Manager. If the issue persists, uninstall the problematic app to restore the audio to your computer.

## Fixing the Audio Device in Use By Another Application Error

 This error is often the result of an audio device driver problem. To fix the error, check if a new driver is available. If not, perform a rollback to install the previous driver version. Also, disable exclusive application access to audio devices and configure the Windows Audio service to start automatically.


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
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-maximize-story-exposure-with-linked-fb-profile/"><u>[New] 2024 Approved  Maximize Story Exposure with Linked FB Profile</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-expert-tips-on-angling-videos-unlocking-full-potential-with-vlc/"><u>[New] In 2024, Expert Tips on Angling Videos  Unlocking Full Potential with VLC</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-premier-programs-to-transform-webcam-footage-for-2024/"><u>[New] Premier Programs to Transform Webcam Footage for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-steps-for-initiating-a-social-media-charity-drive/"><u>[New] Steps for Initiating a Social Media Charity Drive</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-minimalist-obs-adjustments-for-under-500-pcs/"><u>[Updated] 2024 Approved  Minimalist OBS Adjustments for Under-$500 PCs</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-achieving-comprehensive-participant-visualization-on-meet-for-2024/"><u>[Updated] Achieving Comprehensive Participant Visualization on Meet for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-break-free-from-routine-with-these-unique-snapchat-ideas/"><u>[Updated] Break Free From Routine with These Unique Snapchat Ideas</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-expert-analysis-zdsoft-for-screen-recording-for-2024/"><u>[Updated] Expert Analysis  ZDSoft for Screen Recording for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-explore-how-you-can-do-speech-to-text-in-powerpoint/"><u>[Updated] Explore How You Can Do Speech-To-Text in Powerpoint</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-how-to-record-a-voice-over-for-a-video-for-2024/"><u>[Updated] How To Record A Voice Over For A Video for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-facebook-cover-makeovers-the-most-trusted-design-tools-ranked/"><u>[Updated] In 2024, Facebook Cover Makeovers  The Most Trusted Design Tools Ranked</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-mastering-close-up-shots-zooming-into-action-films/"><u>2024 Approved  Mastering Close-Up Shots  Zooming Into Action Films</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-mastering-instagram-the-ultimate-guide-to-viral-popularity/"><u>2024 Approved  Mastering Instagram  The Ultimate Guide to Viral Popularity</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unveiling-hidden-potential-mastering-the-art-of-morphvox/"><u>2024 Approved  Unveiling Hidden Potential  Mastering the Art of MorphVOX</u></a></li>
<li><a href="https://tech-revival.techidaily.com/can-you-rely-on-chatgpts-accuracy-examining-its-truthfulness/"><u>Can You Rely on ChatGPT's Accuracy: Examining Its Truthfulness</u></a></li>
<li><a href="https://win-amazing.techidaily.com/effective-solutions-to-common-driver-errors-for-acer-laptopsdesktops-in-windows/"><u>Effective Solutions to Common Driver Errors for Acer Laptops/Desktops in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-for-win11-defender-firewall-control/"><u>Essential Tips for Win11 Defender Firewall Control</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tactics-to-unite-windows-directories/"><u>Expert Tactics to Unite Windows Directories</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/fake-it-top-online-face-generators-for-creating-artificial-faces/"><u>Fake It! Top Online Face Generators for Creating Artificial Faces</u></a></li>
<li><a href="https://windows11.techidaily.com/five-fun-flicks-in-windows-cmd-world/"><u>Five Fun Flicks in Windows' CMD World</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-print-server-not-responding-issue/"><u>Fixing Print Server Not Responding Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/gauge-your-windows-workhorse-power-efficiency-explored/"><u>Gauge Your Window's Workhorse - Power Efficiency Explored</u></a></li>
<li><a href="https://windows11.techidaily.com/getting-the-0x0-0x0-error-code-in-windows-11-heres-how-to-fix-it/"><u>Getting the 0X0 0X0 Error Code in Windows 11? Here's How to Fix It</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-abnormal-character-output-windows-wise/"><u>Handling Abnormal Character Output Windows-Wise</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-full-screen-in-obs-no-more-worry/"><u>In 2024, Full Screen in Obs, No More Worry</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-realme-c51-to-iphone-xs11-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Realme C51 to iPhone XS/11 | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-ispoofer-is-not-working-on-realme-11-pro-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, iSpoofer is not working On Realme 11 Pro? Fixed | Dr.fone</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-shine-on-mastering-the-art-of-illumination-for-youtube-videos/"><u>In 2024, Shine On  Mastering the Art of Illumination for YouTube Videos</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-unlocking-the-potential-of-audacitys-audio-features/"><u>In 2024, Unlocking the Potential of Audacity's Audio Features</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/innovative-practices-in-creating-powerful-youtube-summaries/"><u>Innovative Practices in Creating Powerful YouTube Summaries</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-hardware-space-exploring-disks-in-w10-and-w11/"><u>Mastering Hardware Space: Exploring Disks in W10 & W11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-restarting-non-starting-windows-drivers/"><u>Mastering the Art of Restarting Non-Starting Windows Drivers</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11-showhide-system-directories/"><u>Mastering Windows 11: Show/Hide System Directories</u></a></li>
<li><a href="https://windows11.techidaily.com/meet-asuss-latest-rivals-to-rog-ally-in-gaming/"><u>Meet ASUS’s Latest Rivals to ROG Ally in Gaming</u></a></li>
<li><a href="https://windows11.techidaily.com/mend-your-meeting-screen-display/"><u>Mend Your Meeting Screen Display</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/movie-editor-complete-guide-on-how-to-edit-movies-or-video/"><u>Movie Editor Complete Guide on How to Edit Movies or Video</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-essential-elements-warning-in-windows-11/"><u>Navigating Through Essential Elements Warning in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-non-detected-proxy-setup/"><u>Navigating Windows Non-Detected Proxy Setup</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/cting-pics-and-videos-on-iphones-and-androids-with-best-apps/"><u>Perfecting Pics & Videos on iPhones and Androids with Best Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-tip-erasing-microsoft-edge-on-windows-11/"><u>Quick Tip: Erasing Microsoft Edge on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/regaining-run-windows-past-execution/"><u>Regaining Run Window's Past Execution</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-sequence-errors-for-running-tasks-windows-guide/"><u>Resolving Sequence Errors for Running Tasks: Windows Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/revitalize-your-search-on-windows-11-11-key-fixes-included/"><u>Revitalize Your Search on Windows 11: 11 Key Fixes Included</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-chrome-setup-in-windows-11-systems/"><u>Seamless Chrome Setup in Windows 11 Systems</u></a></li>
<li><a href="https://driver-error.techidaily.com/solving-screen-reset-on-windows-with-elan-tablet-driver/"><u>Solving Screen Reset on Windows with Elan Tablet Driver</u></a></li>
<li><a href="https://windows11.techidaily.com/speedy-access-to-repair-solutions-customizing-hotkeys-for-win-1011/"><u>Speedy Access to Repair Solutions: Customizing Hotkeys for Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-address-non-successful-disco-update-windows-errors/"><u>Steps to Address Non-Successful Disco Update Windows Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-successful-v22h2-updater-execution-on-win11/"><u>Strategies for Successful V22H2 Updater Execution on WIN11</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-driving-experience-with-free-upgrades-for-windows-users/"><u>Streamline Driving Experience with Free Upgrades for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/the-hidden-the-forgotten-now-revealed-restoring-your-windows-on-win10win11/"><u>The Hidden, The Forgotten, Now Revealed: Restoring Your Windows on Win10/Win11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-11-free-apps-to-check-imei-on-xiaomi-redmi-note-12-4g-phones-by-drfone-android/"><u>Top 11 Free Apps to Check IMEI on Xiaomi Redmi Note 12 4G Phones</u></a></li>
<li><a href="https://windows11.techidaily.com/transforming-chaos-organizing-with-windows-11-calendar/"><u>Transforming Chaos: Organizing with Windows 11 Calendar</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-vlc-lag-on-windows-devices/"><u>Troubleshooting VLC Lag on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-unraveling-color-management-issues/"><u>Troubleshooting Windows: Unraveling Color Management Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-quick-deletion-windows-customization-for-instant-removal/"><u>Unleashing Quick Deletion: Windows Customization for Instant Removal</u></a></li>
<li><a href="https://youtube-web.techidaily.com/king-the-full-potential-innovative-techniques-for-youtube-end-screen-designs-for-2024/"><u>Unlocking the Full Potential  Innovative Techniques for Youtube End Screen Designs for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-end-task-control-capabilities-in-windows-11-ui-environment/"><u>Unveiling End Task Control Capabilities in Windows 11 UI Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/utilizing-rgb-lighting-on-win11-pcs/"><u>Utilizing RGB Lighting on Win11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-establishing-kids-online-boundaries/"><u>Windows 11: Establishing Kids' Online Boundaries</u></a></li>
<li><a href="https://tech-haven.techidaily.com/your-guide-to-understanding-openai-impact/"><u>Your Guide to Understanding OpenAI Impact</u></a></li>
</ul></div>
