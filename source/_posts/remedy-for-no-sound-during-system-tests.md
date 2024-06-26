---
title: Remedy for No Sound During System Tests
date: 2024-06-25T12:11:20.865Z
updated: 2024-06-26T12:11:20.865Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Remedy for No Sound During System Tests
excerpt: This Article Describes Remedy for No Sound During System Tests
keywords: System Test Silence Fix,Audio Issue Resolution,Testing Sound Loss Remedy,Diagnostic Sound Failure,Zero Volume System Check,Noise Absence Solution,Sync Tester Mute Trick
thumbnail: https://thmb.techidaily.com/8eb0a52f331cadec1455be55279efe68c9588c11451977d41c23dfeca435c0f3.jpg
---

## Remedy for No Sound During System Tests

 So you've tested your sound drivers and found that the test tone isn't playing on Windows. This problem occurs with an error message such as "Failed to play test tone" or something similar.

 Dealing with audio problems on Windows is sometimes frustrating, but there are simple solutions available. This guide shows you how to troubleshoot the issue and get your speakers working again.

## 1\. Restart Your Computer

 If the test tone isn't playing, restart your computer first. This often refreshes the system and solves small glitches that may have developed. It's a simple workaround but sometimes effective.

![A Windows PC Getting Started](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/restarting-a-windows-pc.jpg)

 To restart your computer, close any running applications. After that, press **Alt + F4**, or right-click the **Start** menu and select **Shut down or sign out** \> **Shut down**.

## 2\. Run the Audio Troubleshooter

 Windows comes with a built-in troubleshooter for minor audio problems. It diagnoses and fixes issues related to audio hardware, settings, and driver configuration. Here's how to use this tool.

1. Press **Win + I** on your keyboard to open the Settings app.
2. In the Settings menu, navigate to **System** \> **Troubleshoot**.
3. Click **Other troubleshooters** on the next page.
4. Next to the **Playing Audio** troubleshooter, click the **Run** button.  
![Run the Audio Troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-the-audio-troubleshooter.jpg)

 Wait for a while until Windows scans and fixes the issue. After this, see if the test tone is working.

## 3\. Restart the Windows Audio Service

 The Windows Audio service is responsible for controlling the sound on your computer. It's possible that this service stopped running and caused the test tone to fail. In this case, you must restart the Windows Audio service to get your sound back. Here's how.

1. Click on Start, type **services.msc**, and press **Enter**.
2. In the Services window, scroll down to find the **Windows Audio** service.  
![Open Windows Audio Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/open-windows-audio-service.jpg)
3. Once found, double-click it to open its Properties window.
4. In the General tab, click on the **Start type** drop down menu and select **Automatic**.  
![Restart Windows Audio Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/restart-windows-audio-service.jpg)
5. Now go to the **Service status** section and click on **Stop**.
6. Wait for a few moments, then press **Start** to restart the service.
7. Click **Apply** \> **OK** to save the changes.

 After doing this, close the Services window and open any audio application to check if the test tone is playing.

## 4\. Turn Off Audio Enhancements

 The audio enhancement feature on Windows enhances audio quality and adds additional effects to audio playback. However, it sometimes leads to audio problems and glitches. Disabling this feature may fix any sound issues you have.

 To disable audio enhancement, do the following:

1. Press **Win + X** on your keyboard and select **Run** from the menu list.
2. Type "Control Panel" in the search field and hit Enter.
3. Click **Hardware and Sound** in the Control Panel.
4. On the right side of the window, click **Sound**.
5. In the Sound window, select the **Playback** tab.
6. Right-click any device with a green check mark and select **Properties**.
7. On the **Advanced** tab, uncheck the box for **Enable audio enhancements**.  
![Disable Audo Enhancements](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-audo-enhancements.jpg)
8. Now click **Apply > OK** to save the changes.

 Audio enhancements should now be disabled, and you may find your sound issues resolved. If you have multiple audio devices, repeat the process for each device. Once you have completed these steps, restart your computer and check if your audio issues have been resolved.

## 5\. Update the Audio Driver

 Outdated or corrupted audio drivers may lead to the test tone not working. You will need to update them to get your sound back on Windows.

 To update the audio driver:

1. Press **Win + R** on your keyboard to [open the Run command](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **devmgmt.msc** in the dialog box and press Enter.
3. In the Device Manager window, expand the **Audio inputs and outputs** section.  
![Update Audio driver Via Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/update-audio-driver-via-device-manager.jpg)
4. Find your audio device. Note the manufacturer and model name.
5. Search online for drivers for your device. Usually, these will be on the manufacturer's website.

 These drivers usually install with a double-click, but if it doesn't, go back to Device Manager and do this:

1. Right-click your audio device and select **Update driver**.
2. On the next page, select **Search automatically for drivers**. If it doesn't find anything, select **Browse my computer for drivers** and select it manually.  
![Search automatically for drivers-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/search-automatically-for-drivers-1.jpg)

 Wait until Windows downloads and installs the latest driver version. Once done, restart your device and check if the test tone is now playing.

## 6\. Reinstall the Audio Drivers

 If you're still having the same issue, then your audio drivers might be corrupted. So uninstall and reinstall them and check if it works. This process completely removes and reinstalls the driver package on your computer.

 It's a bit more time-consuming but worth trying if the above solutions fail. Here's how to do it:

1. Right-click on the Start menu and select **Device Manager**.
2. Expand the **Audio inputs and outputs** section.
3. Right-click your audio device and select **Uninstall device**.  
![Uninstall Audio driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/uninstall-audio-driver.jpg)
4. If a warning pops up, click **Uninstall** to continue.
5. Now follow the on-screen instructions to uninstall the audio driver.

 After this, close the window and restart your computer. Once your system is up, Windows will automatically detect the audio device and install its driver. This will fix the issue if the driver was corrupted.

## 7\. Try Different Audio Formats

 Sample rate and a bit depth are two important settings that affect the sound quality on your computer. If these settings are not configured correctly, audio glitches may occur, causing the test tone to fail. Based on your device specs, you can change the sample rate and see if it helps.

 To change these settings, do the following:

1. Open the Control Panel and view it as the Category.
2. Click **Hardware and Sound** in the Control Panel, then select **Sound**.
3. On the **Playback** tab, right-click on your audio device and select **Properties**.
4. Next switch to the **Advanced** tab and check the box next to **Allow applications to take exclusive control of this device**.
5. Under **Default format**, select your desired sample rate from the drop-down menu.  
![Try Different Audio Formats](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/try-different-audio-formats.jpg)
6. Now try playing a test tone and see if it works.

 If this solution works, you should leave the settings at their current values. If it doesn't work, go back and select a different sample rate. Once you find the correct settings, click **Apply** \> **OK** to save the changes.

## 8\. Perform a Few General Fixes

 Besides the methods mentioned above, you can try a few general fixes that may help you get the test tone working.

* Disconnecting & reconnecting the audio device. Sometimes, this is all you need to do to fix it.
* [Updating Windows to the latest version](https://www.makeuseof.com/update-windows-manually/).
* You can also [perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/). It disables unnecessary third-party software running in the background, which may cause the issue. I
* If the problem persists, [use the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/). This utility scans all protected system files and replaces them if they are corrupted.

## Playing the Test Tone Again on Windows

 It appears that you are having problems with your sound card and the Windows test tone is not playing. Hopefully, one of these tips worked for you, and your speakers are now working.

 Dealing with audio problems on Windows is sometimes frustrating, but there are simple solutions available. This guide shows you how to troubleshoot the issue and get your speakers working again.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/taming-the-wild-waters-of-xbox-errors-in-win11/"><u>Taming the Wild Waters of Xbox Errors in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-combatting-windows-not-found-problem/"><u>Essential Tips: Combatting Windows Not Found Problem</u></a></li>
<li><a href="https://windows11.techidaily.com/solution-for-fixing-the-invalid-file-history-options-in-windows/"><u>Solution for Fixing the Invalid File History Options in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-locked-status-tips-for-windows-users-153-chars/"><u>Preventing Locked Status: Tips for Windows Users (153 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/redefine-window-management-embrace-adaptive-wmlayouts/"><u>Redefine Window Management: Embrace Adaptive WMLayouts</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-win11-upgrades-eradicate-error-0xc1900101/"><u>Streamline Your Win11 Upgrades, Eradicate Error 0xC1900101</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-duo-app-configurations-to-resolve-errors/"><u>Correcting Duo App Configurations to Resolve Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-the-8-anomalies-in-windows-11s-ui/"><u>Dissecting the 8 Anomalies in Windows 11'S UI</u></a></li>
<li><a href="https://windows11.techidaily.com/reestablishing-clear-audio-conversations-on-valorant-pc/"><u>Reestablishing Clear Audio Conversations on Valorant PC</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-slip-up-on-tiktok-how-to-get-back-content-for-2024/"><u>[Updated] Slip-Up on TikTok  How to Get Back Content for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/best-free-video-communication-apps-for-iphone-and-android-users-for-2024/"><u>Best Free Video Communication Apps for iPhone & Android Users for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-novices-guide-to-selecting-simple-film-cameras/"><u>2024 Approved  Novice's Guide to Selecting Simple Film Cameras</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-exploring-syma-x8c-battery-life/"><u>2024 Approved  Exploring Syma X8C Battery Life</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-mastering-slow-motion-on-kapwing-tips-and-tricks-for-amazing-videos/"><u>New 2024 Approved Mastering Slow Motion on Kapwing Tips and Tricks for Amazing Videos</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-vivo-v27-phone-with-broken-screen-by-drfone-android/"><u>In 2024, How to Unlock Vivo V27 Phone with Broken Screen</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-unmatched-mounting-premier-photos-tripods-for-2024/"><u>[Updated] Unmatched Mounting  Premier Photos Tripods for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-top-rated-mobile-devices-for-pocket-sized-gaming/"><u>[Updated] Top-Rated Mobile Devices for Pocket-Sized Gaming</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/best-online-gif-to-image-pngjpg-converter-for-2024/"><u>Best Online GIF to Image (PNG/JPG) Converter for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/foundations-of-video-editing-in-the-gaming-world-for-2024/"><u>Foundations of Video Editing in the Gaming World for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>