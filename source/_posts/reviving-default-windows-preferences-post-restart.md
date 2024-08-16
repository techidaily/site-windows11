---
title: Reviving Default Windows Preferences Post-Restart
date: 2024-08-15T15:45:57.179Z
updated: 2024-08-16T15:45:57.179Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reviving Default Windows Preferences Post-Restart
excerpt: This Article Describes Reviving Default Windows Preferences Post-Restart
keywords: Restore Win Settings,Post-Restart Configs,Reinstate Defaults,Windows Regain,Reset PC Preferences,Reclaim OS State,Reboot Customize
thumbnail: https://thmb.techidaily.com/7486378233cc28bc02135cae36845cee27a44d59f904615df4dae698bbf74beb.jpg
---

## Reviving Default Windows Preferences Post-Restart

 Imagine you’ve just spent hours tweaking your Windows settings—and then you reboot. What you find is that all changes you made have been reset to default settings. Before you give up and reset your computer to factory defaults, give these solutions a shot.

 In this article, we’ll explain what causes the issue and how you can fix it.

## Why Does Windows Reset Its Settings on Reboot?

 The Windows settings reset on reboot for several reasons. The most common cause is a user profile change, either due to a system update or a user’s action. In other cases, a running background application can corrupt user profiles. This can happen if an application crashes or is not updated. It’s also possible that malware is responsible for the issue.

 Sometimes, if there is a system error or a hardware issue like a faulty hard drive, Windows settings may reset when the computer restarts. This could happen due to an unforeseen power outage.

## How to Fix Windows Settings Resetting Upon Reboot

 The best way to fix Windows settings resetting upon reboot is to identify the cause of the problem and take corrective action. Here are some tips to get your settings back.

### 1\. Look Out for Suspicious Programs

 The first step is to check for malicious programs and other suspicious applications that may be causing your issue. If you find any, remove them immediately and check if it solves the problem. Here's how to do it.

1. Right-click on your Taskbar area and select**Task Manager** from the context menu. You can also press**Ctrl + Shift + Esc** if you prefer using shortcut keys.  
![Look Out for Suspicious Programs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/look-out-for-suspicious-programs.jpg)
2. In the Task Manager window, switch to the**Processes** tab and look for any unfamiliar program or process that is hogging up your system resources.
3. Once you find a suspicious program, right-click on it and select**End task** to terminate the process.
4. Now go to the Windows Control Panel and uninstall the program.

 After uninstalling the program, restart your computer and check if the settings reset issue is resolved.

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
### 2\. Run Automatic Startup Repair

 If Windows continues to reset its settings upon reboot, you should try running the Automatic Startup Repair feature. This will help fix any system errors or corrupted files that may be causing the issue.

To run Automatic Startup Repair, follow these steps:

1. Press**Win + I** to open the Settings window.
2. From the left-hand menu, click the**System** tab.
3. On the right side of the window, scroll down and click the**Recovery** option.  
![Advanced startup in Recovery options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/advanced-startup-in-recovery-options.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->
4. Next to**Advanced startup** , click the**Restart now** button.
5. When your PC restarts, select**Troubleshoot** from the Choose an option screen.
6. Select**Advanced options** and then click**Startup Repair** .  
![Startup repair in Windows 10.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/startup-repair-1.jpg)
<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Follow the on-screen instructions to run the automatic repair tool. After you complete the above process, restart your computer and check if it solves the issue.

### 3\. Check Your User Profile

 If the issue persists, check your user profile and make sure it’s not corrupt. If your user profile is corrupted, Windows will reset the settings when you restart. Here’s how to check it:

 Press**Windows + R** to open the Run command. In the dialog box, type**regedit** , and press Enter. If the User Account Control (UAC) window appears, click**Yes** to grant administrative privileges. This will launch the Registry Editor.

On the next screen, navigate to the following path:

`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\ProfileList`

 In the**ProfileList** folder, you should see several profiles starting with**S-1-5** . Each of these profiles corresponds to a user account on your computer. Now you have to identify which profile belongs to your user account.

 To do this, click on each**S-1-5 profile** and look for**ProfileImagePath** in the right pane. Check if anyone of them matches your username.

![Modify Registry to repair user profile](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/modify-registry-to-repair-user-profile.jpg)
<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->

 Once you find the correct profile, double-click on the**State** field and change the value from**1 to 0** . Similarly, change the**RefCount** field from**1 to 0** .

 In case the RefCount field is missing in the right pane, you’ll have to create it manually. For this, right-click on the right pane and select**New > DWORD (32-bit) Value** . Name the new value**RefCount** and press**Enter** .

 Then double-click on the newly created RefCount and enter**0** in the Value data field. Click**OK** to save your changes and exit Registry Editor. After this, restart your computer and check whether the settings reset problem is fixed.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 4\. Create a New User Profile

 If you weren’t able to repair the corrupt profile in the Registry Editor, you may have to [create a new user profile on Windows](https://www.makeuseof.com/windows-11-create-local-user-account/) . Creating a new user profile does not delete the old one, so all your data will remain intact, but you will have to reconfigure your settings. After creating it, log out of your current user account and switch to the newly created one. Check if this fixes the settings reset issue.

### 5\. Uninstall Recent Updates

 Microsoft releases Windows updates periodically to keep your system secure. But sometimes these updates fail to install properly and cause various issues. If you recently installed any programs or updates, uninstall them to check if that fixes the problem.

 You can also try rolling back any drivers that might be causing the issue. To do this, right-click on Start and select**Device Manager** . In the Device Manager window, find the device you want to roll back and right-click on it. Select**Properties** from the context menu and then click on the**Driver** tab.

 Click**Roll Back Driver** and then follow the instructions on-screen to complete the process. After rolling back the driver, restart your computer to apply the changes and check if it solves the settings reset issue.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
### 6\. Perform Some Generic Windows Fixes

 There are some general Windows-based fixes you can apply to fix this issue.

[Running your Windows computer in a Clean Boot state](https://www.makeuseof.com/clean-boot-windows-11/) is another way to fix the reset settings problem. Clean Boot helps you identify any third-party applications that might be causing the issue. It stops all non-Microsoft services and programs from running during startup, which helps you pinpoint the cause of the issue.

 If the methods mentioned earlier don't fix the issue,[consider doing a System Restore](https://www.makeuseof.com/windows-11-create-restore-point/) . This will take your computer back to a previous state when it was functioning well.

 Keep in mind that all files and applications installed after the selected restore point will be deleted. To avoid losing important data, create a backup before performing a System Restore.

## Fixing Windows Settings Reset on Reboot

 The Windows settings reset on reboot issue can occur for a number of reasons, including corrupt user profiles, corrupted installed programs or updates, and driver issues. This guide provides several methods to fix this issue. Check out these solutions and see which one work for you.


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
<li><a href="https://fox-hovers.techidaily.com/new-essential-10-mobile-apps-boosting-photo-flair-on-iphonesandroids-for-2024/"><u>[New] Essential 10 Mobile Apps  Boosting Photo Flair on iPhones/Androids for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-navigating-auto-captioned-content-in-social-media-visuals/"><u>[New] Navigating Auto-Captioned Content in Social Media Visuals</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-revolutionize-video-crafting-mastering-the-integration-of-windows-11-and-storyremix/"><u>[New] Revolutionize Video Crafting  Mastering the Integration of Windows 11 & StoryRemix</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-10-best-free-video-conferencing-services-with-screen-sharing/"><u>[Updated] 10 Best Free Video Conferencing Services with Screen Sharing</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-downloading-fb-videos-made-easy-our-top-5-selection-for-2024/"><u>[Updated] Downloading FB Videos Made Easy  Our Top 5 Selection for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-facebook-file-to-mp3-converter-tool-for-2024/"><u>[Updated] Facebook File to MP3 Converter Tool for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-from-ordinary-to-extraordinary-profile-videos-for-2024/"><u>[Updated] From Ordinary to Extraordinary  Profile Videos for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-zd-soft-screen-recorder-key-features-and-review/"><u>[Updated] In 2024, ZD Soft Screen Recorder  Key Features and Review</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-step-by-step-powerdirector-app-review-2024/"><u>[Updated] Step-by-Step PowerDirector App Review  2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-beyond-acid-the-future-of-graphic-vectors/"><u>2024 Approved  Beyond ACID  The Future of Graphic Vectors</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-efficient-screen-capture-strategies-for-effective-facetime-recording/"><u>2024 Approved  Efficient Screen-Capture Strategies for Effective FaceTime Recording</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-optimize-your-media-output-with-our-top-10-online-subtitles-tools/"><u>2024 Approved  Optimize Your Media Output With Our Top 10 Online Subtitles Tools</u></a></li>
<li><a href="https://howto.techidaily.com/calls-on-vivo-y100i-go-straight-to-voicemail-12-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Calls on Vivo Y100i Go Straight to Voicemail? 12 Fixes | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-old-user-credentials-issue-on-win-11-os/"><u>Clearing Up 'Old User Credentials' Issue on Win 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/correction-of-microsoft-store-error-0x80073cf3-on-windows-11/"><u>Correction of Microsoft Store Error 0X80073cf3 on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/curb-intrusive-windows-scrolling-for-smooth-screens/"><u>Curb Intrusive Windows Scrolling for Smooth Screens</u></a></li>
<li><a href="https://windows11.techidaily.com/curing-stale-boot-option-imagery/"><u>Curing Stale BOOT Option Imagery</u></a></li>
<li><a href="https://fox-http.techidaily.com/detailed-syma-x8c-assessment/"><u>Detailed Syma X8C Assessment</u></a></li>
<li><a href="https://windows11.techidaily.com/dismantling-tpm-in-win11-using-the-power-of-rufus/"><u>Dismantling TPM in Win11 Using the Power of Rufus</u></a></li>
<li><a href="https://windows11.techidaily.com/dispatching-windows-11s-silent-search-instigator/"><u>Dispatching Windows 11'S Silent Search Instigator</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/elevate-your-filming-flair-with-free-green-screen-insights-from-4-youtube-authorities-for-2024/"><u>Elevate Your Filming Flair with Free Green Screen Insights From 4 YouTube Authorities for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-visuals-perfect-windows-desktop-backdrops/"><u>Elevating Visuals: Perfect Windows Desktop Backdrops</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-cyber-safety-trustable-domains-on-windows-11/"><u>Enhance Cyber Safety: Trustable Domains on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-windows-videography-leverage-advanced-distributive-transcoding-by-tdarr/"><u>Enhance Window's Videography: Leverage Advanced Distributive Transcoding by Tdarr</u></a></li>
<li><a href="https://windows11.techidaily.com/experience-true-tech-fusion-windows-android-via-samsung/"><u>Experience True Tech Fusion – Windows, Android via Samsung</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/find-the-disappeared-watch-tile/"><u>Find the Disappeared Watch Tile</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-sync-errors-in-nvidia-cp-windows-11/"><u>Fixing Sync Errors in NVidia CP Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-fatal-discord-errors-on-windows-1011-a-comprehensible-guide/"><u>Handling Fatal Discord Errors on Windows 10/11: A Comprehensible Guide</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-tecno-spark-20-pro-drfone-by-drfone-virtual-android/"><u>Here Are Some Reliable Ways to Get Pokemon Go Friend Codes For Tecno Spark 20 Pro | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-a-working-guide-for-pachirisu-pokemon-go-map-on-oppo-find-x6-pro-drfone-by-drfone-virtual-android/"><u>In 2024, A Working Guide For Pachirisu Pokemon Go Map On Oppo Find X6 Pro | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-enhance-your-content-utilizing-the-green-screen-on-instagram/"><u>In 2024, Enhance Your Content  Utilizing the Green Screen on Instagram</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-change-your-apple-id-on-iphone-se-2020-with-or-without-password-drfone-by-drfone-ios/"><u>In 2024, How To Change Your Apple ID on iPhone SE (2020) With or Without Password | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-navigate-motion-sickness-in-virtual-reality-with-ease/"><u>In 2024, Navigate Motion Sickness in Virtual Reality with Ease</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-easy-way-to-modify-iphone-photo-dimensions/"><u>In 2024, The Easy Way to Modify iPhone Photo Dimensions</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-things-you-should-know-when-unlocking-total-wireless-of-apple-iphone-se-2020-by-drfone-ios/"><u>In 2024, Things You Should Know When Unlocking Total Wireless Of Apple iPhone SE (2020)</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-unlocking-made-easy-the-best-10-apps-for-unlocking-your-vivo-y100a-device-by-drfone-android/"><u>In 2024, Unlocking Made Easy The Best 10 Apps for Unlocking Your Vivo Y100A Device</u></a></li>
<li><a href="https://windows11.techidaily.com/innovative-2024-windows-devices-you-cant-miss/"><u>Innovative 2024 Windows Devices You Can't Miss</u></a></li>
<li><a href="https://windows11.techidaily.com/least-ram-and-cpu-hungry-browsers-on-triple-operating-systems/"><u>Least RAM and CPU-Hungry Browsers on Triple Operating Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/maintaining-calculator-prominence-in-windows-os/"><u>Maintaining Calculator Prominence in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/master-wins-control-in-windows-11-easy-steps/"><u>Master Wins Control in Windows 11: Easy Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/masterful-dns-management-in-windows-11/"><u>Masterful DNS Management in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-multi-monitor-setup-changes/"><u>Mastering Multi-Monitor Setup Changes</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-obs-troubleshooting-techniques-for-win-11-users/"><u>Mastering OBS Troubleshooting Techniques for Win 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-correct-event-viewer-glitches-in-win-11/"><u>Methods to Correct Event Viewer Glitches in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mitigating-code-xc0000142-on-windows-xp-10/"><u>Mitigating Code XC0000142 on Windows XP, 10</u></a></li>
<li><a href="https://win-answers.techidaily.com/quick-fixes-for-your-league-of-legends-issues-resolve-crashes-instantly/"><u>Quick Fixes for Your League of Legends Issues - Resolve Crashes Instantly</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-making-winget-work-again-in-windows/"><u>Quick Fixes: Making Winget Work Again in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-adding-speed-meter-to-taskbar/"><u>Quick Guide: Adding Speed Meter to Taskbar</u></a></li>
<li><a href="https://review-topics.techidaily.com/quickly-remove-google-frp-lock-on-open-by-drfone-android-unlock-remove-google-frp/"><u>Quickly Remove Google FRP Lock on Open</u></a></li>
<li><a href="https://windows11.techidaily.com/revisiting-exe-execution-hurdles-in-windows/"><u>Revisiting EXE Execution Hurdles in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/rewind-to-file-explorer-classics-in-w11/"><u>Rewind to File Explorer Classics in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-up-controlled-temperature-policy-on-windows-pcs/"><u>Setting up Controlled Temperature Policy on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-windows-11s-frustrating-5ghz-link-failures/"><u>Solving Windows 11'S Frustrating 5GHz Link Failures</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-and-personalize-the-ultimate-desktop-guide-for-win11-users/"><u>Streamline & Personalize: The Ultimate Desktop Guide for Win11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-windows-experience-by-fixing-prerequisites-first/"><u>Streamline Windows Experience by Fixing Prerequisites First</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-policy-settings-with-proven-gpo-update-methods/"><u>Streamlining Policy Settings with Proven GPO Update Methods</u></a></li>
<li><a href="https://android-frp.techidaily.com/top-5-oppo-k11x-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 Oppo K11x Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://win-solutions.techidaily.com/troubleshooting-persistent-crashes-of-microsoft-edge-on-win10-systems/"><u>Troubleshooting Persistent Crashes of Microsoft Edge on Win10 Systems</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/why-government-entities-should-consider-alternatives-to-leading-technology-firms-like-microsoft-during-outages/"><u>Why Government Entities Should Consider Alternatives to Leading Technology Firms Like Microsoft During Outages</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-shortcut-for-character-viewing/"><u>Windows 11 Shortcut for Character Viewing</u></a></li>
</ul></div>
