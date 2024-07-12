---
title: 9 Steps to Resolve Windows Hello Fingerprint Lockout
date: 2024-07-11T22:08:28.295Z
updated: 2024-07-12T22:08:28.295Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 9 Steps to Resolve Windows Hello Fingerprint Lockout
excerpt: This Article Describes 9 Steps to Resolve Windows Hello Fingerprint Lockout
keywords: Fix Windows Fingerprint,Unlock Windows Logon,Bypass Hello Lockout,Login After Lockout,Recover Fingerprint Error,Resolve Hello Failure,Reactivate Fingerprint Access
thumbnail: https://thmb.techidaily.com/5d29a63e1845651f830e0124c103033fe9ea8d7a1b11e86673f2ac375d1ce40d.jpeg
---

## 9 Steps to Resolve Windows Hello Fingerprint Lockout

 Using a fingerprint scanner is perhaps the most convenient way to log in to your Windows computer. It not only eliminates the need to type in a complex password or PIN every time you want to access your computer but also saves you time. But what if Windows Hello fingerprint authentication stops working on your computer?

 Fortunately, there are several ways to fix this annoying issue. So, let’s dive in and explore what you should do when Windows Hello fingerprint login isn’t working.

## 1\. Remove and Re-Register Your Fingerprint

 Your first step is to remove your Windows Hello fingerprint and register it again. This may sound basic, but it is one of the most straightforward ways to get your fingerprint reader to work again. Here are the steps you can follow.

1. Press **Win + I** to open the Settings app.
2. Head to **Accounts > Sign-in options**.
3. Under the **Windows Hello** section, click the **Remove** button.  
![Windows Sign-in Options window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Remove-Windows-Hello-Fingerprint-1.jpg)
4. Once removed, click the **Set up** button and follow the on-screen instructions to register your fingerprint again.

 If the issue persists or if you are unable to remove and re-add your fingerprint due to the "This option is currently unavailable" error on the Windows Hello page, there may be a problem with the Biometric drivers on your PC.

## 2\. Reinstall the Biometric Device Driver

 Biometric drivers on your PC help Windows communicate with your PC's fingerprint scanner. If these drivers are outdated or malfunctioning, you may run into problems.

 Most of the time, you can fix the problem by simply uninstalling and reinstalling the driver on your PC. Here’s how you can go about it.

1. Right-click on the **Start** icon to open the Power User menu.
2. Select **Device Manager** from the list.
3. Expand **Biometric devices**.  
![Biometric Driver selected in Device Manager window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Biometric-Driver-in-Device-Manager-1.jpg)
4. Right-click on your fingerprint scanner device and select **Uninstall device**.
5. Select **Uninstall** to confirm.

 Additionally, you should also expand the **Universal Serial Bus Controllers** section in the Device Manager and look for any entries with a yellow exclamation. If you find any, right-click on them one by one and select **Uninstall device** to remove them.

 Restart your PC after completing the above steps and check if the issue still occurs.

## 3\. Run the Hardware and Devices Troubleshooter

 Windows 10 and 11 include a number of [troubleshooters for resolving various system-related issues](https://www.makeuseof.com/windows-11-troubleshooters/). In this case, you should run the Hardware and Devices troubleshooter. It will scan your computer’s fingerprint scanner for any issues and attempt to fix them.

 Follow these steps to run the Hardware and Devices troubleshooter on Windows:

1. Press **Win + R** to open the Run dialog box.
2. Type **msdt.exe -id DeviceDiagnostic** in the Open field and press **Enter**.
3. In the Hardware and Devices window, click **Next**.  
![Hardware and Devices Troubleshooter Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Hardware-and-Devices-Troubleshooter-Window.jpg)

 Wait for Windows to diagnose any issues with your computer. If any issues are detected, follow the on-screen instructions to apply the recommended fixes.

## 4\. Turn Off Fast Startup

 Fast Startup is a handy Windows feature that speeds up your PC's boot time after shutdown. However, this feature might sometimes prevent Windows from loading properly. When this happens, the fingerprint scanner may not work on your Windows 10 or 11 PC.

 Use one of the many ways to [disable Fast Startup on your Windows computer](https://www.makeuseof.com/windows-11-turn-on-or-off-fast-startup/) and see if that gets the fingerprint scanner to work.

## 5\. Configure Windows Biometric Service to Start Automatically

 The Windows Biometric Service is an essential program for Windows Hello, as it captures and manages your fingerprint data. Ideally, the service should start automatically every time Windows boots. However, this might not happen if the service is not configured correctly.

 Use these steps to configure the Windows Biometric Service:

1. Open the **Services** app using the search menu.
2. Scroll down to locate the **Windows Biometric Service** on the list.
3. Right-click on it and select **Properties**.
4. Click the drop-down menu to change the **Startup type** to **Automatic**.
5. Hit **Apply** followed by **OK**.  
![Windows Biometric Service Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Windows-Biometric-Service-Properties.jpg)

 Restart your PC after this. Following that, you should be able to sign in with your fingerprint.

## 6\. Enable Biometrics via the Local Group Policy Editor

 Another reason why Windows Hello fingerprint sign-in may not work is if the feature is disabled from the Local Group Policy. It's important to note that Group Policy Settings are only available on Professional, Education, and Enterprise editions of Windows. If you are on Windows Home, you don't need to worry about this step.

 To enable fingerprint authentication via the Local Group Policy Editor, use these steps:

1. Press **Win + S** to open the search menu.
2. Type **gpedit.msc** in the search box and press **Enter** to [open the Local Group Policy Editor](https://www.makeuseof.com/tag/open-local-group-policy-editor-windows/).
3. Use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Components > Biometrics**.
4. Check if all the policies within the Biometrics folder are enabled. If not, double-click each policy one by one and set them to **Enabled**.  
![Biometric Policies in Local Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Local-Group-Policy-Editor-Window-1.jpg)

 Restart your PC one more time and check if the issue is still there.

## 7\. Create a New User Account

 An issue with your current user account can also cause certain Windows features to stop working. This usually happens when your user account files get corrupted. If you suspect that to be the case, you can [create and switch to a new user account](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/) to fix the issue. Here’s how you can go about it.

1. Press **Win + I** to open the Settings app.
2. Head to **Accounts > Other users**.
3. Click the **Add account** button.
4. In the Microsoft account window, click on **I don't have this person's sign-in information** and follow the on-screen prompts to create a new user account.  
![Microsoft Account Sign In Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Microsoft-Account-Sign-In-Window.jpg)

 Set up Windows Hello fingerprint login for your new user account and see if you can sign in with your fingerprint.

## 8\. Perform a System Restore

 If the fingerprint not working issue only occurred recently, you can use System Restore to revert Windows to a previous state. This will allow you to undo any changes that may have caused the issue. Note that this is only possible if you have previously [enabled System Restore on your PC](https://www.makeuseof.com/windows-11-enable-system-restore/).

 Follow these steps to perform a system restore on Windows:

1. Press **Win + S** to open the search menu.
2. Type **Create a restore point in the search box** and press **Enter**.
3. Under the **System Protection** tab, click on **System Restore**.
4. Click **Next**.
5. Select a restore point before the issue first appeared and hit **Next**.
6. Review all the details one more time before hitting **Finish**.  
![System Restore Dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/System-Restore-Dialog.jpg)

 Windows will restart and revert to the specified restore point. After that, the fingerprint should work as before.

## 9\. Install the Latest Windows Updates

 Microsoft regularly releases software updates for Windows 10 and Windows 11 to add new features, improve performance, and—crucially for our purposes—fix bugs. If the fingerprint not working issue is caused by a system bug, updating Windows to its most recent version should help.

 You can check for new updates by going to the **Windows Update** tab in the **Settings** app. Download and install any pending updates on your PC. Hopefully, this will resolve the issue.

## Fixing Windows Hello's Fingerprint Check

 It’s annoying when your PC's fingerprint scanner stops working all of a sudden. However, that shouldn’t force you to use your password or PIN to sign in to your computer.

 We hope one of the methods mentioned above has helped and you are able to sign in with your fingerprint again. However, if all else fails, you may want to consider resetting your Windows computer.

 Fortunately, there are several ways to fix this annoying issue. So, let’s dive in and explore what you should do when Windows Hello fingerprint login isn’t working.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/demystifying-access-to-windows-print-services-dashboard/"><u>Demystifying Access to Windows Print Services Dashboard</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-windows-update-blockage-error-e/"><u>Mending Windows Update Blockage, Error E</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-complete-guide-to-selecting-best-free-srt-translators-online/"><u>[Updated] The Complete Guide to Selecting Best FREE SRT Translators Online</u></a></li>
<li><a href="https://windows11.techidaily.com/best-practices-for-avoidable-file-explorer-foibles/"><u>Best Practices for Avoidable File Explorer Foibles</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-unleash-marketing-potential-with-unpacked-plans-for-2024/"><u>[New] Unleash Marketing Potential with Unpacked Plans for 2024</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/translate-video-speech-to-text-with-speech-to-text-converters-for-2024/"><u>Translate Video Speech to Text with Speech-to-Text Converters for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-to-user-management-settings-in-windows-11-and-10/"><u>Navigate to User Management Settings in Windows 11 & 10</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-your-pcs-performance-dispose-of-bloatware/"><u>Enhance Your PC's Performance: Dispose of Bloatware</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-flash-dead-xiaomi-14-safely-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Flash Dead Xiaomi 14 Safely | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/guidelines-for-authoritative-life-lesson-videos/"><u>Guidelines for Authoritative Life Lesson Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-the-electrical-footprint-of-your-windows-device/"><u>Exploring the Electrical Footprint of Your Windows Device</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-to-eradicate-mmc-snap-in-anomalies/"><u>Expert Tips to Eradicate MMC Snap-In Anomalies</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-essential-list-free-costless-desktop-and-web-screening-solutions/"><u>[New] Essential List  Free, Costless Desktop & Web Screening Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-unify-your-cloud-storage-onedrive-plus-microsoft-service/"><u>How to Unify Your Cloud Storage: OneDrive + Microsoft Service</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-downgrade-iphone-15-pro-max-to-the-previous-iosipados-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade iPhone 15 Pro Max to the Previous iOS/iPadOS Version? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/guaranteeing-gaming-glory-resolve-full-screen-woes-in-sonic-on-windows-11/"><u>Guaranteeing Gaming Glory: Resolve Full-Screen Woes in Sonic on Windows 11</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/2024-approved-detailed-guide-on-video-speech-to-text-conversion/"><u>2024 Approved Detailed Guide on Video Speech to Text Conversion</u></a></li>
<li><a href="https://windows11.techidaily.com/making-disabled-overlays-functional-again-on-windows-pc/"><u>Making Disabled Overlays Functional Again on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaim-soundfulness-overcoming-muted-mouses-cry/"><u>Reclaim Soundfulness: Overcoming Muted Mouse's Cry</u></a></li>
<li><a href="https://windows11.techidaily.com/command-guide-win11-starting-high-privilege-powershell/"><u>Command Guide: Win11 - Starting High-Privilege PowerShell</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-crafting-powerful-narratives-with-these-30-video-plans/"><u>[Updated] Crafting Powerful Narratives with These 30 Video Plans</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/streamline-your-pc-screens-free-app-for-2024/"><u>Streamline Your PC Screens, Free App for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-windows-11-performance-tweak-ntfs-file-compression/"><u>Enhance Windows 11 Performance: Tweak NTFS File Compression</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-superior-10-audio-enhancement-solutions-your-guide-to-richer-mobile-sound/"><u>In 2024, Superior 10 Audio Enhancement Solutions Your Guide to Richer Mobile Sound</u></a></li>
<li><a href="https://windows11.techidaily.com/hunt-down-elusive-control-panel-options-on-windows-11/"><u>Hunt Down Elusive Control Panel Options on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-efficiently-managing-windows-11-features/"><u>Mastering the Art of Efficiently Managing Windows 11 Features</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-top-15-pcmac-apps-that-turn-your-gameplay-into-art/"><u>[Updated] Top 15 Pc/Mac Apps That Turn Your Gameplay Into Art</u></a></li>
<li><a href="https://windows11.techidaily.com/automate-email-attachment-openness-ms-word-read-mode-only/"><u>Automate Email Attachment Openness: MS Word Read Mode Only</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-strategies-to-stay-in-clear-view-after-a-tiktok-ban-for-2024/"><u>[New] Strategies to Stay in Clear View After a TikTok Ban for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-amplify-your-creative-voice-on-tiktok-designed-themes-for-you/"><u>[New] In 2024, Amplify Your Creative Voice on TikTok  Designed Themes for You</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-immediinate-and-rectify-the-iomap64-system-freeze-error/"><u>How To Immediinate and Rectify the IOMap64 System Freeze Error</u></a></li>
<li><a href="https://windows11.techidaily.com/introducing-a-new-search-option-in-windows-11-task-manager/"><u>Introducing a New Search Option in Windows 11 Task Manager</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/everlasting-impressions-save-instagram-stories-endlessly/"><u>Everlasting Impressions  Save Instagram Stories Endlessly</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-hidden-windows-bar-when-browser-frames-are-enlarged/"><u>Fixing Hidden Windows Bar when Browser Frames Are Enlarged</u></a></li>
<li><a href="https://howto.techidaily.com/google-play-services-wont-update-12-fixes-are-here-on-sony-xperia-10-v-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Google Play Services Wont Update? 12 Fixes are Here on Sony Xperia 10 V | Dr.fone</u></a></li>
<li><a href="https://facebook.techidaily.com/strategies-to-monitor-and-record-teen-activity-online-fb-focused/"><u>Strategies to Monitor and Record Teen Activity Online, FB-Focused</u></a></li>
<li><a href="https://fox-links.techidaily.com/peak-performance-pfv-settings-for-easy-movement/"><u>Peak Performance PFV Settings for Easy Movement</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-crafting-a-celebrity-online-presence-nine-strategies-for-social-media-success/"><u>[New] Crafting a Celebrity Online Presence  Nine Strategies for Social Media Success</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-in-depth-study-androids-lightroom-app-functionality/"><u>[New] In-Depth Study  Android's Lightroom App Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-solutions-freeing-up-stuck-windows-11-pins/"><u>Quick Solutions: Freeing Up Stuck Windows 11 PINs</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-achievements-to-your-retro-games-with-retroarch/"><u>How to Add Achievements to Your Retro Games With Retroarch</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/streamlining-virtual-screen-display-in-google-meet-chats-for-2024/"><u>Streamlining Virtual Screen Display in Google Meet Chats for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-edge-how-pcs-beat-macs-in-9-aspects/"><u>Decoding the Edge: How PCs Beat Macs in 9 Aspects</u></a></li>
<li><a href="https://windows11.techidaily.com/instructional-path-resetting-windows-preferences-post-reboot/"><u>Instructional Path: Resetting Windows Preferences Post-Reboot</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-admin-error-for-apps/"><u>Bypassing Windows Admin Error for Apps</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-unleashing-popularity-the-best-discord-screen-names-ever/"><u>[Updated] 2024 Approved  Unleashing Popularity  The Best Discord Screen Names Ever</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-honor-magic-6-to-laptop-without-usb-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Honor Magic 6 to Laptop Without USB | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-absent-bluetooth-devices-manager/"><u>Remedy Absent Bluetooth Devices Manager</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-edu-stream-100-cutting-edge-learning-yt/"><u>[Updated] Edu-Stream 100  Cutting-Edge Learning YT</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-breathing-life-into-art-top-6-for-revolutionary-nftos/"><u>In 2024, Breathing Life Into Art  Top 6 for Revolutionary NFTOs</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-elevating-your-cinematic-expedition-through-border-techniques/"><u>In 2024, Elevating Your Cinematic Expedition Through Border Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/choosing-a-fresh-pdf-file-reader-for-os-use/"><u>Choosing a Fresh PDF File Reader for OS Use</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-restore-error-0x80042306-quickly/"><u>Overcoming Windows Restore Error 0X80042306 Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-camera-app-when-it-cant-save-photos-or-videos-in-windows/"><u>How to Fix the Camera App When It Can't Save Photos or Videos in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-windows-activate-derailed-handbrake/"><u>Conquer Windows: Activate Derailed HandBrake</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/yielding-yearly-yield-channel-to-currency-conversion-for-2024/"><u>Yielding Yearly Yield  Channel to Currency Conversion for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unveiling-top-quality-hdr-camera-brands-and-models-for-2024/"><u>Unveiling Top-Quality HDR Camera Brands and Models for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-facebooks-vision-for-video-unpacking-the-short-form-movement/"><u>[Updated] 2024 Approved  Facebook's Vision for Video   Unpacking the Short Form Movement</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reactivate-a-non-operational-wsreset-process-in-windows/"><u>How to Reactivate a Non-Operational WSReset Process in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-your-window-preferences-on-win11/"><u>Customize Your Window Preferences on Win11</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-total-recording-tool-az-app-examination-guide-for-2024/"><u>[Updated] Total Recording Tool - AZ App Examination Guide for 2024</u></a></li>
</ul></div>
