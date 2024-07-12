---
title: Rectify Stalling Windows Guard Mechanism in Win 11
date: 2024-07-11T21:46:54.489Z
updated: 2024-07-12T21:46:54.489Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Rectify Stalling Windows Guard Mechanism in Win 11
excerpt: This Article Describes Rectify Stalling Windows Guard Mechanism in Win 11
keywords: Fix Windows Freeze,Stop System Halt,End Windows Lag,Resolve Win 11 Pause,Unblock Windows Error,Eliminate Freezing Delay,Eradicate Stall in Win 11
thumbnail: https://thmb.techidaily.com/3f943451ad9f20674a4982a12bf6e3782b7a46fb4a594b07cf7ffe549e83acd7.jpg
---

## Rectify Stalling Windows Guard Mechanism in Win 11

 Windows Security is a free and default antivirus program provided by Microsoft to protect your PC from outside threats. However, there are times when the security software might stop working properly, or in some cases, not start at all. And to top off, if you’re also not using a third-party antivirus app, you're basically wide open to a myriad of security attacks.

 It's therefore crucial that Windows security is working at its best; this will keep your computer security airtight. In this article, we’ve laid down some of the best tricks that will help you fix Windows Security on your Windows 11\.

## 1\. Turn on Windows Security

 In rare cases when a PC undergoes a malicious attack one of the first things that the malicious program does is [turn off all the antivirus defenses like Microsoft Defender](https://www.makeuseof.com/how-to-turn-off-microsoft-defender-windows-11/). If your PC has undergone such an attack recently, then it might be possible that you're facing the same issue.

 If that's indeed the case then you'll have to manually enable Windows Security on your PC. Follow these steps to continue:

1. Head to the **Start menu** search bar, type in 'security,' and select the best match.
2. From there, click on **Turn on** to enable the **Virus & threat protection** of your PC.
3. A new dialog box will pop up asking you to confirm if you want to go ahead with the changes; click on **Yes** to proceed.

![security at glance menu in windows security settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/windows-security.jpg)

 The Windows Security app will be enabled instantly.

## 2\. Update Windows 11

 How long has it been since you last updated your Windows? If it’s been a while, it might be a good time to brush off the dust from your updates.

 Follow these steps to check for updates on your Windows PC:

1. Go to the **Start menu** search bar, type in ‘settings,’ and select the Best match. Alternatively, press **Win + I** together.
2. Scroll down and select **Windows Update**.
3. Now click on **Check for updates** and Windows will start checking for updates on your PC. (If any new updates are available, they’ll be displayed on the **Windows Update** screen.)
4. Finally, click on **Download & install** to get the ball rolling.

![windows update section in the settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/windows-update-1.png)

 When the updates download is complete, give your PC a quick restart and see if the problem with Windows Security persists. If it does, then jump below to the next method.

## 3\. Disable Third-Party Antivirus

 If you have an additional antivirus installed on your PC, it might be a good time to get rid of it.

 Running Windows Security along with third-party antivirus apps has been known to cause many kinds of disruption in Windows computers. So removing the additional antivirus might, in fact, be a fair approach—remove the antivirus and see if it can get everything back to normal.

 To get started, launch the **Settings** again. Go to **Apps > Apps & features**, search for the antivirus, and when you find it, click on options (three dots) and select **Uninstall**.

![apps and features in the apps settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/apps-and-feature.png)

 The third-party antivirus will be removed. Now restart your Windows 11 and see if the problem with Windows Security persists. It shouldn’t.

## 4\. Reset the Windows Security App

 Removing the third-party antivirus app from your PC should get your Windows Security back to work in most cases. However, in cases where it's not, it might be time to do a complete reset of your Security app.

 Follow these steps to reset the Windows Security app:

1. Go to the **Settings** menu again by pressing the **Windows key + I**.
2. Select **App > Apps & features** and type in ‘security’ in the search menu box.
3. An icon for Windows Security will pop open. From there, click on the **options** (three dots) and select **Advanced options**.
4. Now scroll down to **Reset** section and click on **Reset**.

 You’ll get a confirmation asking if you really want to reset the app, along with your whole app data. Click on **Reset** to go with it.

![reset and repair option in the windows security settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/reset-and-repair.jpg)

 You can also try the **Repair** option if you don't want to reset the app right off. It’s right there above the **Reset** option. As soon you click on **Repair**, the process will begin. When the Repair is complete, it’ll leave a tick option adjacent to **Repair** box.

## 5\. Run an SFC and DISM Scan

 SFC, short for System File Checker, is a Windows utility that can be fallen back upon when some of your Windows files malfunction. In short, it checks for file corruption and then tries to repair it.

 It is accessed through the Command prompt. To get started, go to the **Start menu** search bar, type in ‘command prompt,’ and then launch it as administrator.

 This launches your Command prompt in an elevated mode, something necessary to run the SFC utility.

 In the Command prompt, type the following command and hit **Enter**:

`sfc/ scannow`

 The tool will scan your PC and you should be able to run the Security app by the end.

![execution of sfc scan in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/sfc-scan-in-command-prompt.png)

 If the SFC tool doesn't work, don't fret just yet. Another tool that you can try your luck with is the DISM; it's not the same as SFC, but it works almost similarly. You can check out the [differences between SFC and DISM](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) if you'd like to learn more.

 Much like how the SFC tool helps you fix your PC, a DISM scan finds and fixes any issues with your system image that might be causing problems with your PC's functioning.

 Like with SFC scan above, you’ll have to launch the DISM as an administrator as well. Go to the **Start menu,** type in ‘DISM,’ and run it as administrator. When you launch the DISM scan, enter the following command and hit **Enter**:

`DISM /Online /Cleanup-Image /ScanHealth`

![execution of dsim scan in the command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/dsim-scan-command-prompt.png)

 As soon as the command finishes executing, your files would've been scanned and all the corruption issues would most possibly have been resolved.

 When you’re done, [simply restart your PC](https://www.makeuseof.com/windows-restart-methods/) for the changes to take effect, and see if the problem persists.

## 6\. Restart the Windows Security Service

 Windows Security makes use of a host of programs and services for smooth functioning on your PC. One of those handy services is the Windows Security Center service which monitors the security state of the important components of your system.

 So, if your Windows Security app stopped opening, or if it crashed midway, we suggest you restart your Windows Security Center Service right away. To get started, follow the steps below:

1. Press **Win + R** and type "services.msc" and hit the Enter key.
2. Here, scroll down to find and right-click on **Security-Center** and then select **Restart**.

![security services process in the services app on windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/services-app-windows-11.jpg)

 That's it. Follow any other on-screen instructions and wait for the service to reboot of the service. When that's done, restart your PC and the Windows Security service will be fixed by the next boot-up.

## 7\. Reset Your PC

 A panacea for almost all [the common Windows bugs](https://www.makeuseof.com/common-windows-11-problems/), the **Reset Your PC** setting resets your computer and brings it to its initial state. It’s far better than reinstalling the whole Windows, as you can reset your PC while also keeping your personal files and folders intact.

 To get started, follow the steps below:

1. Go to the **Start menu** search bar, type in ‘settings,’ and select the Best match.
2. In the **Settings** menu, click on **System > Recovery**.
3. In the **Recovery options** tab, click on Reset PC.
4. Then select **Keep my files > Local reinstall** and click on **Next**.

![two types of reset options in the reset this pc on windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/reset-this-pc-windows-11.png)

 That’s it. Follow the onscreen instructions ahead and your Windows will be formatted and reinstalled in no time. When your PC restarts, all your settings will be at ground zero again.

 The whole process is fairly straightforward, but if you face any difficulties during the reset, make sure you go through a [complete guide on Windows 10 factory reset](http://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) and verify if you're making any slip-ups in between the steps.

## Fixing the Issues With Windows Security

 Windows Security is a must-have for Windows health. However, the app can sometimes malfunction and stop working properly. Hopefully, one of the methods laid out above helped you get it working once again.

 But that's not all; There are a ton of ways you can dial up your PC’s security, so make sure you aren’t simply relying only on Windows security for your PC's cyber protection.

 It's therefore crucial that Windows security is working at its best; this will keep your computer security airtight. In this article, we’ve laid down some of the best tricks that will help you fix Windows Security on your Windows 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/bridging-the-gap-top-6-ways-to-solve-network-hardware-issues-in-windows-systems/"><u>Bridging the Gap - Top 6 Ways to Solve Network Hardware Issues in Windows Systems</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-methods-to-mirror-honor-magic-6-to-roku-drfone-by-drfone-android/"><u>3 Methods to Mirror Honor Magic 6 to Roku | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-windows-techniques-for-diverse-partition-merging/"><u>Advanced Windows Techniques for Diverse Partition Merging</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-bring-your-photos-to-life-with-music-and-video-editing-for-2024/"><u>Updated Bring Your Photos to Life with Music and Video Editing for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/7-methods-for-correcting-unreachable-display-responses-in-windows/"><u>7 Methods for Correcting Unreachable Display Responses in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/a-step-by-step-approach-for-cleaning-up-ms-audit-records/"><u>A Step-by-Step Approach for Cleaning Up MS Audit Records</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-smart-recording-solutions-for-schools-and-colleges-for-2024/"><u>[New] Smart Recording Solutions for Schools & Colleges for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/break-the-cycle-of-a-non-opening-notepad-on-your-windows-device/"><u>Break the Cycle of a Non-Opening Notepad on Your Windows Device</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/2024-approved-morph-your-mug-the-top-face-swap-apps-for-ios-and-android/"><u>2024 Approved Morph Your Mug The Top Face Swap Apps for iOS and Android</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-the-unsuccessful-capture-problem-in-win11/"><u>Addressing the 'Unsuccessful Capture' Problem in Win11</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/best-practices-for-exporting-youtube-videos-to-facebook-for-2024/"><u>Best Practices for Exporting YouTube Videos to Facebook for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/banish-baffling-silence-solutions-for-windows-spacebar/"><u>Banish Baffling Silence: Solutions for Windows Spacebar</u></a></li>
<li><a href="https://windows11.techidaily.com/clarifying-windows-approach-to-isolated-audiosystems/"><u>Clarifying Windows' Approach to Isolated Audiosystems</u></a></li>
<li><a href="https://windows11.techidaily.com/calendar-setup-made-simple-windows-11-edition/"><u>Calendar Setup Made Simple: Windows 11 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-clipboard-operations-in-application-guard-edge-win11-guide/"><u>Activating Clipboard Operations in Application Guard (Edge) - Win11 Guide</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-best-10-volume-magnifiers-for-windowsmacos/"><u>[Updated] Best 10 Volume Magnifiers for Windows/MacOS</u></a></li>
<li><a href="https://windows11.techidaily.com/bless-your-pc-god-mode-enhancements/"><u>Bless Your PC: God Mode Enhancements</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/in-2024-remove-tiktok-watermarks-in-seconds-best-online-methods/"><u>In 2024, Remove TikTok Watermarks in Seconds Best Online Methods</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-can-you-transfer-files-from-xiaomi-redmi-k70e-to-iphone-151413-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How Can You Transfer Files From Xiaomi Redmi K70E To iPhone 15/14/13? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-lost-messages-how-to-fix-notifications-that-fail/"><u>Avoiding Lost Messages: How to Fix Notifications That Fail</u></a></li>
<li><a href="https://windows11.techidaily.com/achieving-a-peaceful-state-disable-background-tasks/"><u>Achieving a Peaceful State: Disable Background Tasks</u></a></li>
<li><a href="https://windows11.techidaily.com/a-guide-to-all-the-windows-photos-keyboard-shortcuts/"><u>A Guide to All the Windows Photos Keyboard Shortcuts</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/songbird-scribes-writing-the-script-for-youtube/"><u>Songbird Scribes  Writing the Script for YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-scripts-not-active-top-4-fixes-to-powershell-load-issue/"><u>Bypassing 'Scripts Not Active': Top 4 Fixes to PowerShell Load Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-spec-deficit-errors-from-windows-game-bar/"><u>Addressing Spec Deficit Errors From Window's Game Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-11-get-support-disruption/"><u>Addressing Windows 11 'Get Support' Disruption</u></a></li>
<li><a href="https://windows11.techidaily.com/audible-improvements-for-windows-users-stepwise-audio-driver-revamp/"><u>Audible Improvements for Windows Users: Stepwise Audio Driver Revamp</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-the-most-user-friendly-photo-music-video-creation-software/"><u>New 2024 Approved The Most User-Friendly Photo Music Video Creation Software</u></a></li>
<li><a href="https://windows11.techidaily.com/7-must-know-factors-for-buying-your-ideal-windows-computer/"><u>7 Must-Know Factors for Buying Your Ideal WIndows Computer</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-diy-techniques-transforming-smartphones-into-webcams-for-2024/"><u>[New] DIY Techniques  Transforming Smartphones Into Webcams for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/masterminds-of-making-magic-top-6-in-nft-innovation-for-2024/"><u>Masterminds of Making Magic  Top 6 in NFT Innovation for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-10-vivo-y200e-5g-android-sim-unlock-apk-by-drfone-android/"><u>Top 10 Vivo Y200e 5G Android SIM Unlock APK</u></a></li>
<li><a href="https://windows11.techidaily.com/blue-screen-decoded-understanding-and-fixing-0x0000003b-in-win-os/"><u>Blue Screen Decoded: Understanding and Fixing 0X0000003B in Win OS</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-pro-tips-for-streaming-and-screening-netflix-on-mac/"><u>2024 Approved  Pro-Tips for Streaming & Screening Netflix on Mac</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-detailed-guide-of-ispoofer-for-pogo-installation-on-apple-iphone-11-pro-max-drfone-by-drfone-virtual-ios/"><u>In 2024, Detailed guide of ispoofer for pogo installation On Apple iPhone 11 Pro Max | Dr.fone</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-a-beginners-guide-to-tell-you-what-3d-animation-is/"><u>New A Beginners Guide to Tell You What 3D Animation Is</u></a></li>
<li><a href="https://windows11.techidaily.com/bringing-windows-backups-back-to-basics/"><u>Bringing Windows Backups Back to Basics</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-androidprocessmedia-has-stopped-on-nubia-z50s-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android.Process.Media Has Stopped on Nubia Z50S Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-scanning-issues-with-your-geforce-experience-on-windows/"><u>Avoid Scanning Issues with Your GeForce Experience on Windows</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-update-drivers-on-windows-11-and-10-by-drivereasy-guide/"><u>Use Device Manager to update drivers on Windows 11 & 10</u></a></li>
<li><a href="https://windows11.techidaily.com/3-ways-to-check-if-windows-11-is-activated/"><u>3 Ways to Check If Windows 11 Is Activated</u></a></li>
<li><a href="https://audio-editing.techidaily.com/mellow-newsroom-soundtracks-15th-edition/"><u>Mellow Newsroom Soundtracks, 15Th Edition</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/mastering-access-to-royalty-free-design-tools-for-2024/"><u>Mastering Access to Royalty-Free Design Tools for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-navigating-instas-archive-maze-for-optimal-results/"><u>[New] In 2024, Navigating Insta’s Archive Maze for Optimal Results</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-0x80070194-fixes-for-windows-onedrive/"><u>Bypassing 0X80070194: Fixes for Windows OneDrive</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-binge-on-savings-top-tiktok-items-now-at-bargain-prices-on-amazon/"><u>[New] 2024 Approved  Binge on Savings  Top TikTok Items Now at Bargain Prices on Amazon</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-sharpen-your-footage-with-videoleaps-zoom/"><u>In 2024, Sharpen Your Footage with Videoleap's ZOOM</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerating-media-playback-in-vlc-for-pc-users/"><u>Accelerating Media Playback in VLC for PC Users</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-invalid-captcha-on-steam/"><u>Bypassing Invalid CAPTCHA on Steam</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fake-the-location-to-get-around-the-mlb-blackouts-on-vivo-y100i-drfone-by-drfone-virtual-android/"><u>In 2024, Fake the Location to Get Around the MLB Blackouts on Vivo Y100i | Dr.fone</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-2024-approved-5-best-audio-editor-for-android-that-you-should-know/"><u>New 2024 Approved 5 Best Audio Editor for Android That You Should Know</u></a></li>
</ul></div>
