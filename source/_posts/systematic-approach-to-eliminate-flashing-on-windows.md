---
title: Systematic Approach to Eliminate Flashing on Windows
date: 2024-07-11T21:13:25.468Z
updated: 2024-07-12T21:13:25.468Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Systematic Approach to Eliminate Flashing on Windows
excerpt: This Article Describes Systematic Approach to Eliminate Flashing on Windows
keywords: Flash Elimination Guide,Stop Flashy Windows,Windows Glitch Fix,Avoid Screen Flicker,Tackle Screen Shimmer,Eradicate Display Flashes,Remove Window Flashing Issues
thumbnail: https://thmb.techidaily.com/288c4a8a533b0f1094aca3a28c5db0188ea8b5a3c3aca95005c1c84fe62729c2.jpg
---

## Systematic Approach to Eliminate Flashing on Windows

 If your Windows 10 or Windows 11 screen is constantly flickering, it's likely because you have a troublesome application installed or an unsuitable display driver. It's time for you to resolve that annoying screen flash.

 The problem often begins when upgrading to Windows 10/11 from a previous version of the operating system, but it can occur at any time. We're going to show you various methods to fix a Windows 10 or Windows 11 flashing screen.

## Perform This Screen Flickering Test First

 First, you need to establish what might be causing the flickering screen. To do this,[open Task Manager](https://www.makeuseof.com/how-to-access-task-manager-on-windows-11/) by pressing**Ctrl + Shift + Esc** simultaneously.

 Alternatively, on Windows 10 you can**right-click** your taskbar and select**Task Manager** . You don't actually need to use Task Manager, but you do need it open.

![windows 11 desktop with task manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/windows-11-desktop-with-task-manager.jpg)

 Now, watch your screen to see if Task Manager flickers. If it does, along with everything else on the screen, the problem is likely caused by your hardware or a faulty display driver. On the other hand, if everything except Task Manager flickers, the issue is likely due to an application.

 If it's the former, follow the instructions below in order. If it's the latter, skip to step five. That said, if the advice there doesn't work, check the advice in the other sections too.

## 1\. Check Your Monitor and Cables

 If you have a flashing screen, the first thing to rule out is the hardware. Check all the cable connections from the monitor to the computer—take them out and plug them back in to ensure the cables are secure.

 If you have a spare monitor cable, try using it instead. Or buy a replacement online, since it's an inexpensive purchase. Cables can degrade over time, or maybe a pet has had a sneaky chew. Either way, switch the cable and see if it stops the screen flickering.

 If you can, try a different monitor. If this resolves the problem, you know it's your monitor that's the issue. At that point, contact the manufacturer for support or to raise a warranty claim.

## 2\. Set the Correct Refresh Rate

 A monitor's refresh rate is the speed at which the screen updates the image per second, measured in hertz (Hz). Basic monitors can usually only handle a 60Hz refresh rate, while more advanced ones—typically aimed at gamers—can go to 360Hz and beyond.

 It's important that you [set a suitable refresh rate for your monitor](https://www.makeuseof.com/tag/60hz-vs-144hz/) . Sometimes a monitor manufacturer will support an overclocked refresh rate, but this can cause screen flickering.

To adjust your refresh rate:

![windows 11 advanced display](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/windows-11-advanced-display.jpg)

1. Press**Windows key + I** to open Settings.
2. Click**System** \>**Display** .
3. Click**Advanced display settings** (Windows 10) or**Advanced display** (Windows 11).
4. Use the**Refresh rate** dropdown and incrementally select lower rates until the screen flashing stops. If the flashing continues, revert to your monitor's recommended refresh rate.

## 3\. Reset Your Display Driver

 The screen flashing could be caused by your display driver. You might have an old driver or a faulty new one. Let's make sure you are running the right version for your system.

### Step 1: Remove the Driver

 First,[boot Windows in safe mode](https://www.makeuseof.com/windows-11-boot-safe-mode/ "How to Boot Into Windows 10 Safe Mode") :

![windows 11 recovery](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/windows-11-recovery.jpg)

1. Press**Windows key + I** to open Settings.
2. Select**Update & Security >** **Recovery** (Windows 10) or**System > Recovery** (Windows 11).
3. Underneath**Advanced start-up** , click**Restart now** .
4. When your system restarts, select **Troubleshoot > Advanced options > Startup settings > Restart** .
5. Again, once restarted, select option five to launch your PC into**Safe Mode with Networking** .

Next, use Device Manager to uninstall the display driver:

![uninstall display device drivers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/06/uninstall-display-device-drivers.png)

1. Press**Windows key + X** and click**Device Manager** .
2. **Double-click** on**Display adapters** to expand the category.
3. **Right-click** your graphics card, click**Uninstall device** , check**Delete the driver software for this device** and then click**OK** .
4. Restart your system again.

 Alternatively, you can use third-party software [Display Driver Uninstaller](https://www.guru3d.com/files-details/display-driver-uninstaller-download.html) , which will completely wipe any traces of the driver from your system.

### Step 2: Install a New Driver

 You now want to [install the latest driver](https://www.makeuseof.com/tag/find-replace-outdated-windows-drivers/) for your system. Windows Update will provide the driver it thinks is compatible with your system. To do this:

1. Press**Windows Key + I** to open Settings.
2. Click**Update & Security** (Windows 10) or**Windows Update** (Windows 11).
3. Click**Check for updates** .

 Alternatively, you can go to your graphics card manufacturer's website (likely [AMD](https://www.amd.com/en/support) ,[NVIDIA](https://www.nvidia.com/Download/Find.aspx) , or [Intel](https://downloadcenter.intel.com/product/80939/Graphics) ) and manually download the driver from there.

 Download the driver, install it, and see if the screen flashing problem has ceased.

### Roll Back to an Older Driver

 If the problem continues, it might be that the newest driver hasn't patched the problem. If the screen flickering occurred after a driver update, try rolling back to an older version.

 Follow the steps above to uninstall the driver, then head to the old driver page for either [AMD](https://www.amd.com/en/support) ,[NVIDIA](https://www.nvidia.com/Download/Find.aspx) , or [Intel](https://downloadcenter.intel.com/product/80939/Graphics) . This might be a bit of trial and error, but try selecting one released when your screen wasn't flickering.

## 4\. Reseat Your Graphics Card

 If the problem isn't with your display driver, it doesn't mean your graphics card isn't to blame. If your graphics card isn't seated correctly in your motherboard, it can cause your monitor display to flicker on and off.

 You can easily check this if your motherboard has inbuilt graphics. Remove the monitor cable from your graphics card and plug it into the motherboard's display slot instead. If the flashing stops, you know the graphics card is the problem.

[Power off your PC](https://www.makeuseof.com/windows-11-how-to-shut-down/) , unplug everything, open the case, and remove your graphics card from the motherboard. Then carefully reseat it, ensuring the card firmly clips into the motherboard. Of course, don't do this if you're not comfortable working inside a computer because you might make things worse.

 If this doesn't fix it,[your graphics card might be faulty or dying](https://www.makeuseof.com/signs-graphics-card-is-dying/) . Contact the manufacturer for support or to claim on the warranty.

## 5\. Uninstall Problematic Applications

 Some apps are incompatible with Windows 10/11 and can cause screen flickering. Think about whether you installed any new software before the screen flashing began or if an app recently updated. In the past, three problematic apps have been Norton Antivirus, iCloud, and IDT Audio.

 Across all your applications, make sure you're running the latest versions. Either update within the app itself or head to the respective official websites and download the most up-to-date release. Alternatively, check the developer's support page for recently updated apps to see if screen flashing is known as a recent bug.

![windows 11 apps and features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/windows-11-apps-and-features.jpg)

If this doesn't work, uninstall the program. To do so:

1. Press**Windows Key + I** to open Settings.
2. Click**Apps** \>**Apps & features** .
3. Click**Sort by** and choose**Installation date** .
4. Click the offending app and click**Uninstall** . You may need to restart your system for the changes to take full effect.

## 6\. Create a New Windows User Profile

 How do you stop your laptop or computer screen from flickering? Well, many Windows 10 and Windows 11 problems can often be solved by [creating a new user profile](https://www.makeuseof.com/windows-11-create-local-user-account/) . Screen flickering is one of them.

![windows 11 family and other users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/windows-11-family-and-other-users.jpg)

To create a new account:

1. Press**Windows Key + I** to open Settings.
2. Go to**Accounts > Family & other users** .
3. Click**Add someone else to this PC** (Windows 10) or**Add account** (Windows 11) and follow the wizard.

## Windows Screen Flickers... No More

 As with most Windows 10/11 issues, no single fix will work for everyone. Hopefully, one of the steps above has solved your Windows 10 or Windows 11 screen flashing problem.

 If it is time for a new monitor, there are plenty of productive and fun things you can do with the old one. Otherwise, take it off for recycling so it can rest in monitor heaven.


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
<li><a href="https://twitter-videos.techidaily.com/in-2024-tweet-to-tune-video-to-audible-file/"><u>In 2024, Tweet-to-Tune  Video to Audible File</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-top-discount-emblem-artist-tools-now-available-free/"><u>2024 Approved  Top Discount Emblem Artist Tools - Now Available FREE</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-92-chuckle-fest-an-analyzed-goofy-film-vhs/"><u>2024 Approved  '92 Chuckle Fest'  An Analyzed Goofy Film VHS</u></a></li>
<li><a href="https://change-location.techidaily.com/how-can-i-get-more-stardust-in-pokemon-go-on-samsung-galaxy-a05s-drfone-by-drfone-virtual-android/"><u>How can I get more stardust in pokemon go On Samsung Galaxy A05s? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-audio-recorder-snag-with-error-9999-solution/"><u>Navigating Windows' Audio Recorder Snag with Error 9999 Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-ad-ds-printing-issues-in-windows-11-pro/"><u>Overcoming AD DS Printing Issues in Windows 11 Pro</u></a></li>
<li><a href="https://howto.techidaily.com/best-methods-for-nubia-red-magic-9-pro-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Best Methods for Nubia Red Magic 9 Pro Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/significance-and-uses-for-vcplusplus-releases/"><u>Significance and Uses for VC++ Releases</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-overview-of-the-best-sony-xperia-5-v-screen-mirroring-app-drfone-by-drfone-android/"><u>In 2024, Overview of the Best Sony Xperia 5 V Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-unresponsive-spotify-on-windows-11/"><u>Troubleshooting Unresponsive Spotify on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-mp3s-into-listenable-audio-cds-using-windows-and-imgburn-techniques/"><u>Optimizing MP3s Into Listenable Audio Cds Using Windows and ImgBurn Techniques</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-sharecast-mobilepc-video-extractor/"><u>2024 Approved  Sharecast  Mobile/PC Video Extractor</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-the-ultimate-audio-edition-understanding-avs-softwares-core-strengths-and-evaluating-other-choices/"><u>Updated In 2024, The Ultimate Audio Edition Understanding AVS Softwares Core Strengths and Evaluating Other Choices</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-restarting-resistant-spotify-program/"><u>Quick Fix: Restarting Resistant Spotify Program</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-data-from-lava-by-fonelab-android-recover-data/"><u>Undelete lost data from Lava</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-transform-your-videos-a-beginners-guide-to-editing-with-windows-movie-maker/"><u>In 2024, Transform Your Videos A Beginners Guide to Editing with Windows Movie Maker</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-visibility-of-missing-disk-in-win/"><u>Restoring Visibility of Missing Disk in Win</u></a></li>
<li><a href="https://windows11.techidaily.com/restore-your-window-11-drag-functionality/"><u>Restore Your Window 11 Drag Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/seamlessly-access-lately-used-documents-in-windows/"><u>Seamlessly Access Lately Used Documents in Windows</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-amplify-your-brands-voice-with-these-pivotal-promotion-tactics/"><u>[New] 2024 Approved  Amplify Your Brand's Voice with These Pivotal Promotion Tactics</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-in-2024-from-imovie-to-hollywood-mastering-movie-making-on-mac/"><u>New In 2024, From iMovie to Hollywood Mastering Movie Making on Mac</u></a></li>
<li><a href="https://windows11.techidaily.com/top-screen-notebook-techniques-for-win-1011/"><u>Top-Screen Notebook Techniques for Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-to-open-adobe-ps-in-w11-after-updates/"><u>Step-by-Step to Open Adobe PS in W11 After Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-for-curtailing-windows-eyes-on-you/"><u>Tactics for Curtailing Windows' Eyes on You</u></a></li>
<li><a href="https://network-issues.techidaily.com/making-basic-drivers-better-on-ws-2-ws-8/"><u>Making Basic Drivers Better on WS-2, WS-8</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/the-ultimate-method-to-conquer-slow-mo-filming-in-tiktok/"><u>The Ultimate Method to Conquer Slow Mo Filming in TikTok</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-exploring-the-leading-10-macwindows-srt-enhancers/"><u>[New] Exploring the Leading 10 Mac/Windows SRT Enhancers</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-steam-setup-obstacles-on-windows-11-devices/"><u>Overcoming Steam Setup Obstacles on Windows 11 Devices</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-cards-of-samsung-galaxy-s24-ultra-without-puk-codes-by-drfone-android/"><u>In 2024, How To Unlock SIM Cards Of Samsung Galaxy S24 Ultra Without PUK Codes</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/secrets-to-super-views-hashtag-hacks-for-game-streams/"><u>Secrets to Super Views  Hashtag Hacks for Game Streams</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resurrect-a-dormant-windows-tab-key/"><u>Steps to Resurrect a Dormant Windows Tab Key</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-balancing-consistency-and-quality-a-key-to-increasing-youtube-viewership/"><u>[Updated] Balancing Consistency & Quality  A Key to Increasing YouTube Viewership</u></a></li>
<li><a href="https://windows11.techidaily.com/the-special-features-that-define-artificited-computers/"><u>The Special Features that Define Artificited Computers</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-tasks-effortlessly-top-8-pomodoro-timer-reviews-on-pc/"><u>Mastering Tasks Effortlessly - Top 8 Pomodoro Timer Reviews on PC</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-pixelgrabber-evaluation-with-vendors-offerings/"><u>[Updated] PixelGrabber Evaluation with Vendors' Offerings</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-fixing-the-application-was-unable-error/"><u>Understanding and Fixing The Application Was Unable Error</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-usage-settings-on-windows-11-your-how-to-guide/"><u>Navigating Usage Settings on Windows 11: Your How-To Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-rectify-win-1011-onedrive-issues/"><u>Steps to Rectify Win 10/11 OneDrive Issues</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/planning-to-use-a-pokemon-go-joystick-on-tecno-spark-10-5g-drfone-by-drfone-virtual-android/"><u>Planning to Use a Pokemon Go Joystick on Tecno Spark 10 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-offline-errors-for-windows-11s-printer-port/"><u>Resolving Offline Errors for Windows 11'S Printer Port</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-task-execution-on-windows-adding-an-improved-run-utility/"><u>Optimizing Task Execution on Windows: Adding an Improved Run Utility</u></a></li>
<li><a href="https://windows11.techidaily.com/the-pathway-for-effortless-changes-of-file-extensions/"><u>The Pathway for Effortless Changes of File Extensions</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-content-creators-dilemma-which-site-reigns-vimeo-youtube/"><u>[New] Content Creators' Dilemma  Which Site Reigns - Vimeo, YouTube?</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-common-errors-in-microsoft-office-activation/"><u>Overcoming Common Errors in Microsoft Office Activation</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-unveiling-the-secrets-of-librecam-studio/"><u>[New] 2024 Approved  Unveiling the Secrets of LibreCam Studio</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-gaming-hits-with-powerful-hashtag-strategies-for-2024/"><u>[Updated] Gaming Hits with Powerful Hashtag Strategies for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/redefine-window-management-embrace-adaptive-wmlayouts/"><u>Redefine Window Management: Embrace Adaptive WMLayouts</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-troubleshooting-overcoming-error-e84-on-steam/"><u>Mastering the Art of Troubleshooting: Overcoming Error E84 on Steam</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-little-gamers-treasure-trove-of-joy/"><u>[Updated] 2024 Approved  Little Gamers' Treasure Trove of Joy</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-erase-an-iphone-13-pro-without-apple-id-by-drfone-ios/"><u>In 2024, How to Erase an iPhone 13 Pro without Apple ID?</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-avoiding-frequent-sign-ins-on-ms-teams-platform/"><u>Solutions for Avoiding Frequent Sign-Ins on MS Teams Platform</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-windows-11-programs-for-faster-startups/"><u>Optimizing Windows 11 Programs for Faster Startups</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-twitter-vids-analysis-the-holistic-2023-guide/"><u>[New] Twitter Vids Analysis  The Holistic 2023 Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-solve-no-device-camera-error-in-win11/"><u>Steps to Solve No Device: Camera Error in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-user-accounts-to-local-groups-policy-in-windows-11-and-11/"><u>Tailoring User Accounts to Local Groups Policy in Windows 11 & 11</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-mastering-the-art-of-screen-sharing-in-zoom/"><u>[Updated] In 2024, Mastering the Art of Screen Sharing in Zoom</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-tweaking-mouse-speeds-in-win-1011/"><u>The Ultimate Guide to Tweaking Mouse Speeds in Win 10/11</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-unleash-the-full-potential-of-your-images-with-powerful-pixlr-hacks/"><u>[Updated] Unleash the Full Potential of Your Images with Powerful Pixlr Hacks</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-top-10-non-youtube-video-platforms-for-iphone-and-android-enthusiasts/"><u>In 2024, Top 10 Non-YouTube Video Platforms for iPhone & Android Enthusiasts</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-value-not-found-error-message-in-windows-setups/"><u>Solving 'Value Not Found' Error Message in Windows Setups</u></a></li>
<li><a href="https://windows11.techidaily.com/pro-tips-for-mastering-local-user-groups-on-win1110/"><u>Pro Tips for Mastering Local User Groups on Win11/10</u></a></li>
<li><a href="https://windows11.techidaily.com/swiftly-overcoming-disruptions-after-a-windows-update/"><u>Swiftly Overcoming Disruptions After a Windows Update</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-11-free-apps-to-check-imei-on-vivo-t2x-5g-phones-by-drfone-android/"><u>In 2024, Top 11 Free Apps to Check IMEI on Vivo T2x 5G Phones</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/international-friendship-starters/"><u>International Friendship Starters</u></a></li>
</ul></div>
