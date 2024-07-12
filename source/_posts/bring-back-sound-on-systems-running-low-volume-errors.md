---
title: Bring Back Sound on Systems Running Low Volume Errors
date: 2024-07-11T22:10:47.104Z
updated: 2024-07-12T22:10:47.104Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Bring Back Sound on Systems Running Low Volume Errors
excerpt: This Article Describes Bring Back Sound on Systems Running Low Volume Errors
keywords: System Audio Issue Resolution,Low Volume Fix in Devices,Reduce Sound Quality Errors,Troubleshoot Volume Drops,Correcting Silent Sounds,Addressing Low Speech Output,Enhance System Audio Clarity
thumbnail: https://thmb.techidaily.com/0a337b8d498c7856f1553f3aec6dd0a0ba10469da4dedfe1c7e2e3409bef7181.jpg
---

## Bring Back Sound on Systems Running Low Volume Errors

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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-skills.techidaily.com/roundabout-viewpoint-versus-threefold-imaging-for-2024/"><u>Roundabout Viewpoint Versus Threefold Imaging for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-breaking-down-asus-pa32u-a-4k-professional-review/"><u>[Updated] Breaking Down ASUS PA32U  A 4K Professional Review</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-windows-taskbar-recovery/"><u>Strategies for Windows Taskbar Recovery</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11-safe-mode-an-easy-six-step-plan/"><u>Unlocking Windows 11 Safe Mode: An Easy Six-Step Plan</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-no-audio-devices-in-windows/"><u>Addressing 'No Audio Devices' In Windows</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-use-pokemon-go-joystick-on-honor-80-pro-straight-screen-edition-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Pokemon Go Joystick on Honor 80 Pro Straight Screen Edition? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/the-magic-behind-the-scenes-in-photo-app-delete/"><u>The Magic Behind the Scenes in Photo App Delete</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-audiences-on-the-move-tracker-apps/"><u>[New] 2024 Approved  Audiences on the Move Tracker Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/top-essential-gratis-tools-for-windows-11-enthusiasts/"><u>Top Essential Gratis Tools for Windows 11 Enthusiasts</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-0xa00f4243-overlapping-camera-usage-in-apps/"><u>Troubleshooting 0xA00F4243: Overlapping Camera Usage in Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-insufficient-spec-on-game-captures/"><u>Troubleshooting Insufficient Spec on Game Captures</u></a></li>
<li><a href="https://windows11.techidaily.com/unwrapping-the-mystery-of-monitor-miscalibration/"><u>Unwrapping the Mystery of Monitor Miscalibration</u></a></li>
<li><a href="https://windows11.techidaily.com/tactile-hover-over-customizing-your-click-experience-in-win11/"><u>Tactile Hover Over: Customizing Your Click Experience in Win11</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-discords-favorite-font-makers-ios-and-android-edition/"><u>[New] 2024 Approved  Discord's Favorite Font Makers  IOS & Android Edition</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-explore-artistic-possibilities-premier-android-graphics-app-selection/"><u>2024 Approved  Explore Artistic Possibilities  Premier Android Graphics App Selection</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-circumvent-no-more-files-alert/"><u>Strategies to Circumvent No More Files Alert</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-top-10-desktop-and-phone-zoom-replacements/"><u>[Updated] 2024 Approved  Top 10 Desktop & Phone Zoom Replacements</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-in-2024-maximize-social-media-impact-tiktoks-top-data-analysis-resources/"><u>[New] In 2024, Maximize Social Media Impact  TikTok's Top Data Analysis Resources</u></a></li>
<li><a href="https://windows11.techidaily.com/skyrocketing-vm-potential-in-windows-implement-these-top-strategies/"><u>Skyrocketing VM Potential in Windows - Implement These Top Strategies</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-card-on-oppo-find-n3-flip-online-without-jailbreak-by-drfone-android/"><u>In 2024, How to Unlock SIM Card on Oppo Find N3 Flip online without jailbreak</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-winscomrssvrdll-anomaly-during-boot-up/"><u>Tackling the Winscomrssvr.dll Anomaly During Boot-Up</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-eliminate-windows-error-xc0f1103f-on-geforce/"><u>Steps to Eliminate Windows Error XC0F1103F on GeForce</u></a></li>
<li><a href="https://windows11.techidaily.com/win11s-unnecessary-filler-heres-how-to-tackle-it/"><u>Win11's Unnecessary Filler? Here’s How To Tackle It</u></a></li>
<li><a href="https://windows11.techidaily.com/systematic-approach-to-eliminate-flashing-on-windows/"><u>Systematic Approach to Eliminate Flashing on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/blocking-windows-update-prompts/"><u>Blocking Windows Update Prompts</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-audio-anonymization-in-multimedia-a-step-by-step-approach-updated/"><u>Updated Audio Anonymization in Multimedia A Step-by-Step Approach (Updated)</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/2024-approved-from-silence-to-soundtrack-transforming-video-narratives-using-filmoras-audio-tools/"><u>2024 Approved From Silence to Soundtrack Transforming Video Narratives Using Filmoras Audio Tools</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-strategies-for-dispelling-blue-screen-of-operation-requires-elevation-in-winos/"><u>Efficient Strategies for Dispelling Blue Screen of Operation Requires Elevation in WINOS</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-immersive-memories-a-compreeved-guide-to-saving-your-vr-gaming-journey/"><u>[New] In 2024, Immersive Memories  A Compreeved Guide to Saving Your VR Gaming Journey</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-lessening-high-cpu-demand-from-tiworkerexe-tasks/"><u>Strategies for Lessening High CPU Demand From TiWorker.exe Tasks</u></a></li>
<li><a href="https://windows11.techidaily.com/the-complete-surface-computing-firmware-upgrade-manual/"><u>The Complete Surface Computing Firmware Upgrade Manual</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-guide-to-brightening-the-windows-11-pointer/"><u>The Essential Guide to Brightening the Windows 11 Pointer</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-the-art-of-focusing-on-roblox-elements-closeup/"><u>In 2024, The Art of Focusing on Roblox Elements Closeup</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-how-to-share-vimeo-video-in-instagram-stories/"><u>2024 Approved  How to Share Vimeo Video in Instagram Stories</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/in-2024-rip-audio-from-instagram-fast-and-easy-methods/"><u>In 2024, Rip Audio From Instagram Fast and Easy Methods</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-voice-modulation-mastery-a-guide-to-installing-and-applying-autotune-in-audacity/"><u>New Voice Modulation Mastery A Guide to Installing and Applying Autotune in Audacity</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-the-full-capabilities-of-docker-in-wsl-2-windows/"><u>Unleashing the Full Capabilities of Docker in WSL 2 Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-biometric-control-in-w11-for-domain-users/"><u>Secure Biometric Control in W11 for Domain Users</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-premium-planet-friendly-recording-software-for-2024/"><u>[New] Premium, Planet-Friendly Recording Software for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-rootjunky-apk-to-bypass-google-frp-lock-for-poco-m6-5g-by-drfone-android/"><u>In 2024, Rootjunky APK To Bypass Google FRP Lock For Poco M6 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/the-blueprint-for-a-more-effective-and-reliable-windows-11/"><u>The Blueprint for a More Effective and Reliable Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/cherishing-the-slumber-of-your-computer/"><u>Cherishing the Slumber of Your Computer</u></a></li>
</ul></div>
