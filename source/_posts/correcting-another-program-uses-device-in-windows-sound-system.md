---
title: Correcting 'Another Program Uses Device' In Windows Sound System
date: 2025-01-09T21:13:27.669Z
updated: 2025-01-16T11:12:53.623Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/620kcQ7Dw7w?si=a5ussGs5HV7sG3hF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Run the Windows Audio Troubleshooter

![Windows 11 settings troubleshoot other troubleshooters playing audio run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-11-settings-troubleshoot-other-troubleshooters-playing-audio-run.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jjGL9wFdlbo?si=Vb1JgZqRXNc03UGG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Windows has a built-in audio troubleshooter to find and fix issues with playing audio. The troubleshooter looks for common audio issues and tries to fix them automatically.

To run the audio troubleshooter:

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, click on**Troubleshoot** .
3. Click on**Other troubleshooters** .
4. Next, click the**Run** button for**Playing Audio** . Wait for the audio troubleshooter to scan for issues. Then select the affected audio device and click**Next** .
5. Follow the on-screen instructions and check if the error is resolved.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n4cc4BSqJls?si=Hkd9vwQDqeCGN7XG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Disable Exclusive Mode for the Audio Device

 By default, Windows applications can take exclusive control of the audio device. While enabling this option shouldn’t cause any issues, some apps may prevent the device from being used by other audio services. To fix the problem, disable exclusive mode to stop applications from taking exclusive control of the audio device.

To disable Exclusive Mode for the audio device on Windows:

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, click on**Sound** .
3. Scroll down and click on**More sound settings** .  
![more sound settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/more-sound-settings-windows-11.jpg)
4. Select the audio device in the**Sound** dialog and click the**Properties** button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/58KlTPHv8dU?si=7ICagyNgrao7OkVO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Open the**Advanced** tab in the**Properties** dialog.  
![disable exclusive mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-exclusive-mode.jpg)
6. Uncheck the **Allow application to take exclusive control of this device** and**Give exclusive mode application priority** options.
7. Click**Apply** and**OK** to save the changes.

 Restart your computer and check if the error is resolved and if the audio device is working again.

## 3\. Change Windows Audio Service Startup Type

 Windows Audio service is responsible for managing audio devices connected to your computer. If the service is disabled or not running, your audio device can stop working.

 By default, it is set to start automatically as you power on your device. Check if the Startup type for Windows Audio is set to Manually. If yes, reconfigure it to start automatically to fix audio problems.

To change the Windows Audio service Startup type:

1. Press**Win + R** to open**Run** .
2. Type**services.msc** and click**OK** to open the**Services** snap-in.
3. In the**Services** window, locate and double-click on**Windows Audio** service.  
![windows audio service properties services snap in](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-audio-service-properties-services-snap-in.jpg)
4. Click the**Startup** type drop-down and select**Automatic** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UcplMvRBulA?si=iBonbwDS1v7RAlHK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Click**Apply** and**OK** to save the changes.  
![windows audio service startup type automatic](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-audio-service-startup-type-automatic.jpg)
6. If the service is not running, right-click on**Windows Audio** and select**Start** .
7. Close the Services snap-in and restart your PC. After the restart, your audio device should start working again.

## 4\. Disable and Re-Enable the Sound Output Device

 You can temporarily disable and re-enable the audio device to fix any glitches causing the device to malfunction. You can [disable the audio device](https://www.makeuseof.com/enable-disable-sound-output-devices-in-windows/) using the Settings app and Device Manager.

 To disable the audio device, right-click on the audio device and select**Disable device** in**Device Manager** . Next, right-click on the audio device and**Enable Device** . Close Device Manager and check for any improvements.

## 5\. Uninstall and Reinstall the Audio Device and Driver

![Uninstalling an audio device in Windows 11.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/uninstalling-audio-device-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XIUatTFH0Zw?si=ZCtoBtIy18y2F5Vc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 If it is a Windows-specific issue, installing pending Windows updates can fix the problem. Check the Windows updates page for newer updates and install them to see if that helps resolve the issue.

 To install Windows update, go to**Settings > Windows Update** and click**Check for updates** . Windows will populate the screen with all the pending updates. You can install the updates or selectively install any audio device updates.

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
<li><a href="https://facebook-video-files.techidaily.com/updated-unpacking-the-limitations-of-video-sharing-in-facebooks-community-for-2024/"><u>[Updated] Unpacking the Limitations of Video Sharing in Facebook's Community for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/achieve-peak-meeting-performance-a-detailed-zoom-guide/"><u>Achieve Peak Meeting Performance A Detailed Zoom Guide</u></a></li>
<li><a href="https://extra-hints.techidaily.com/creating-a-tranquil-auditory-space-with-tech-for-2024/"><u>Creating a Tranquil Auditory Space with Tech for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-code-0x0001-nvidia-glitch-in-w10w11/"><u>Fixing Code 0X0001 Nvidia Glitch in W10/W11</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-correct-oculus-app-errors-in-winxiwinxc/"><u>Guide to Correct Oculus App Errors in WinXI/WinXC</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-3-ways-for-android-pokemon-go-spoofing-on-infinix-hot-40i-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways for Android Pokemon Go Spoofing On Infinix Hot 40i | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-ways-to-track-sony-xperia-10-v-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Track Sony Xperia 10 V without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-the-essential-escape-function-in-windows-78/"><u>Restoring the Essential Escape Function in Windows 7/8</u></a></li>
<li><a href="https://windows11.techidaily.com/ten-steps-to-clear-win11-dns-cache/"><u>Ten Steps to Clear Win11 DNS Cache</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/updated-free-tv-streaming-9-sites-you-need-to-know-for-2024/"><u>Updated Free TV Streaming 9 Sites You Need To Know for 2024</u></a></li>
</ul></div>

