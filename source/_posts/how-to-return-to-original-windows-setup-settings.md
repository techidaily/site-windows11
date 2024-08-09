---
title: How to Return to Original Windows Setup Settings
date: 2024-08-08T06:11:39.007Z
updated: 2024-08-09T06:11:39.007Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Return to Original Windows Setup Settings
excerpt: This Article Describes How to Return to Original Windows Setup Settings
keywords: WinXP Restore,Windows XP Recovery,Resetting Windows,XP Default State,Revert Windows Settings,Remove Windows Customization,XP Setup Return
thumbnail: https://thmb.techidaily.com/e874e7774ed1bae47e14908261fcbf31de304eed1c8fec16cc5f931b201e9fca.jpg
---

## How to Return to Original Windows Setup Settings

 Imagine you’ve just spent hours tweaking your Windows settings—and then you reboot. What you find is that all changes you made have been reset to default settings. Before you give up and reset your computer to factory defaults, give these solutions a shot.

 In this article, we’ll explain what causes the issue and how you can fix it.

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Why Does Windows Reset Its Settings on Reboot?

 The Windows settings reset on reboot for several reasons. The most common cause is a user profile change, either due to a system update or a user’s action. In other cases, a running background application can corrupt user profiles. This can happen if an application crashes or is not updated. It’s also possible that malware is responsible for the issue.

 Sometimes, if there is a system error or a hardware issue like a faulty hard drive, Windows settings may reset when the computer restarts. This could happen due to an unforeseen power outage.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Fix Windows Settings Resetting Upon Reboot

 The best way to fix Windows settings resetting upon reboot is to identify the cause of the problem and take corrective action. Here are some tips to get your settings back.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
### 1\. Look Out for Suspicious Programs

 The first step is to check for malicious programs and other suspicious applications that may be causing your issue. If you find any, remove them immediately and check if it solves the problem. Here's how to do it.

1. Right-click on your Taskbar area and select**Task Manager** from the context menu. You can also press**Ctrl + Shift + Esc** if you prefer using shortcut keys.  
![Look Out for Suspicious Programs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/look-out-for-suspicious-programs.jpg)
2. In the Task Manager window, switch to the**Processes** tab and look for any unfamiliar program or process that is hogging up your system resources.
3. Once you find a suspicious program, right-click on it and select**End task** to terminate the process.
4. Now go to the Windows Control Panel and uninstall the program.

 After uninstalling the program, restart your computer and check if the settings reset issue is resolved.

### 2\. Run Automatic Startup Repair

 If Windows continues to reset its settings upon reboot, you should try running the Automatic Startup Repair feature. This will help fix any system errors or corrupted files that may be causing the issue.

To run Automatic Startup Repair, follow these steps:

1. Press**Win + I** to open the Settings window.
2. From the left-hand menu, click the**System** tab.
3. On the right side of the window, scroll down and click the**Recovery** option.  
![Advanced startup in Recovery options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/advanced-startup-in-recovery-options.jpg)
4. Next to**Advanced startup** , click the**Restart now** button.
5. When your PC restarts, select**Troubleshoot** from the Choose an option screen.
6. Select**Advanced options** and then click**Startup Repair** .  
![Startup repair in Windows 10.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/startup-repair-1.jpg)

 Follow the on-screen instructions to run the automatic repair tool. After you complete the above process, restart your computer and check if it solves the issue.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->
### 3\. Check Your User Profile

 If the issue persists, check your user profile and make sure it’s not corrupt. If your user profile is corrupted, Windows will reset the settings when you restart. Here’s how to check it:

 Press**Windows + R** to open the Run command. In the dialog box, type**regedit** , and press Enter. If the User Account Control (UAC) window appears, click**Yes** to grant administrative privileges. This will launch the Registry Editor.

On the next screen, navigate to the following path:

`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\ProfileList`

 In the**ProfileList** folder, you should see several profiles starting with**S-1-5** . Each of these profiles corresponds to a user account on your computer. Now you have to identify which profile belongs to your user account.

 To do this, click on each**S-1-5 profile** and look for**ProfileImagePath** in the right pane. Check if anyone of them matches your username.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
![Modify Registry to repair user profile](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/modify-registry-to-repair-user-profile.jpg)

 Once you find the correct profile, double-click on the**State** field and change the value from**1 to 0** . Similarly, change the**RefCount** field from**1 to 0** .

 In case the RefCount field is missing in the right pane, you’ll have to create it manually. For this, right-click on the right pane and select**New > DWORD (32-bit) Value** . Name the new value**RefCount** and press**Enter** .

 Then double-click on the newly created RefCount and enter**0** in the Value data field. Click**OK** to save your changes and exit Registry Editor. After this, restart your computer and check whether the settings reset problem is fixed.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
<!-- affiliate ads end -->
### 4\. Create a New User Profile

 If you weren’t able to repair the corrupt profile in the Registry Editor, you may have to[create a new user profile on Windows](https://www.makeuseof.com/windows-11-create-local-user-account/) . Creating a new user profile does not delete the old one, so all your data will remain intact, but you will have to reconfigure your settings. After creating it, log out of your current user account and switch to the newly created one. Check if this fixes the settings reset issue.

### 5\. Uninstall Recent Updates

 Microsoft releases Windows updates periodically to keep your system secure. But sometimes these updates fail to install properly and cause various issues. If you recently installed any programs or updates, uninstall them to check if that fixes the problem.

 You can also try rolling back any drivers that might be causing the issue. To do this, right-click on Start and select**Device Manager** . In the Device Manager window, find the device you want to roll back and right-click on it. Select**Properties** from the context menu and then click on the**Driver** tab.

 Click**Roll Back Driver** and then follow the instructions on-screen to complete the process. After rolling back the driver, restart your computer to apply the changes and check if it solves the settings reset issue.

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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-block-spontaneous-youtube-video-triggers/"><u>[New] 2024 Approved  Block Spontaneous YouTube Video Triggers</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/024-approved-getting-started-with-your-youtube-channel-essentials/"><u>[New] 2024 Approved  Getting Started with Your YouTube Channel – Essentials</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-listenguide-examination/"><u>[New] ListenGuide Examination</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-no-cash-needed-for-youtube-audio-check-out-this-list-of-23-crackers/"><u>[New] No Cash Needed for YouTube Audio? Check Out This List of 23 Crackers</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-online-video-arena-showdown-who-wins-vimeo-or-giants-like-youtubeplusdailymotion/"><u>[New] Online Video Arena Showdown  Who Wins – Vimeo or Giants Like YouTube+DailyMotion?</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-unveiling-the-secrets-of-premiere-pros-full-screen-magic/"><u>[New] Unveiling the Secrets of Premiere Pro's Full Screen Magic</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-fbx-methods-for-perfect-gaming-saves/"><u>[Updated] FBX Methods for Perfect Gaming Saves</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-discover-these-popular-periscope-alternatives-on-smartphones/"><u>[Updated] In 2024, Discover These  Popular Periscope Alternatives on Smartphones</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-key-applications-for-superior-vtuber-audible-identity/"><u>[Updated] Key Applications for Superior Vtuber Audible Identity</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-the-ultimate-guide-fine-tuning-snapchat-video-velocity/"><u>2024 Approved  The Ultimate Guide  Fine-Tuning Snapchat Video Velocity</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-best-tools-to-hard-reset-samsung-galaxy-a25-5g-drfone-by-drfone-reset-android-reset-android/"><u>3 Best Tools to Hard Reset Samsung Galaxy A25 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/a-beginners-roadmap-to-understanding-windows-iscsi-initiator/"><u>A Beginner's Roadmap to Understanding Windows iSCSI Initiator</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/a-comprehensive-guide-to-apple-iphone-8-plus-blacklist-removal-tips-and-tools-by-drfone-ios/"><u>A Comprehensive Guide to Apple iPhone 8 Plus Blacklist Removal Tips and Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensive-guide-to-fixing-0xc00000f-error/"><u>A Comprehensive Guide to Fixing 0xC00000F Error</u></a></li>
<li><a href="https://windows11.techidaily.com/averting-self-triggered-openings-on-msdnstoreapp/"><u>Averting Self-Triggered Openings on MSDN/StoreApp</u></a></li>
<li><a href="https://windows11.techidaily.com/dealing-with-interrupt-at-breakpoint-issue-in-windows-debugging/"><u>Dealing with Interrupt at Breakpoint Issue in Windows Debugging</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-windows-pe-file-system/"><u>Decoding Windows' PE File System</u></a></li>
<li><a href="https://windows11.techidaily.com/dial-up-speed-strategies-to-revive-your-sluggish-pc/"><u>Dial Up Speed: Strategies to Revive Your Sluggish PC</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-techniques-for-altering-credentials-on-windows-11/"><u>Easy Techniques for Altering Credentials on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-macos-with-cross-operating-system-tools/"><u>Elevating macOS with Cross-Operating System Tools</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/epic-recordings-the-best-timelapse-software-for-2024/"><u>Epic Recordings  The Best Timelapse Software for 2024</u></a></li>
<li><a href="https://data-wizards.techidaily.com/expert-clips-repair-glowing-client-reviews/"><u>Expert Clips Repair - Glowing Client Reviews</u></a></li>
<li><a href="https://some-techniques.techidaily.com/explore-top-5-non-samsung-360-cameras-today-for-2024/"><u>Explore Top 5 Non-Samsung 360 Cameras Today for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tuning-fn-keys-windows-10-and-11-techniques/"><u>Fine-Tuning FN Keys: Windows 10 and 11 Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-unresponsive-f-keys-troubleshooting-in-windows-11-os/"><u>Fix: Unresponsive F Keys - Troubleshooting in Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/1719202743817-function-failures-on-win10-quick-remedies-available/"><u>Function Failures on Win10? Quick Remedies Available</u></a></li>
<li><a href="https://windows11.techidaily.com/granting-correct-permissions-to-solve-windows-installer-error/"><u>Granting Correct Permissions to Solve Windows Installer Error</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-can-vivo-v30-promirror-share-to-pc-drfone-by-drfone-android/"><u>How Can Vivo V30 ProMirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-correct-hardware-detection-errors-in-win/"><u>How To Correct Hardware Detection Errors in Win</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-revive-your-bricked-realme-c33-2023-in-minutes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Revive Your Bricked Realme C33 2023 in Minutes | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/howtodarkennotepadwindesktop/"><u>HowToDarkenNotepadWinDesktop</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-essential-screen-recording-tools-a-comprehensive-educators-guide/"><u>In 2024, Essential Screen Recording Tools  A Comprehensive Educator's Guide</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-from-text-to-screen-srt-to-subc-transformation-tips/"><u>In 2024, From Text to Screen  SRT-to-SUBC Transformation Tips</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-sony-xperia-10-v-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>In 2024, How to Cast Sony Xperia 10 V Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-linguistic-strategies-in-film-scriptwriting/"><u>In 2024, Linguistic Strategies in Film Scriptwriting</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-pristineai-designs-crafting-visuals-with-ai/"><u>In 2024, PristineAI Designs  Crafting Visuals with AI</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-youtube-instagram-connection-posting-video-content/"><u>In 2024, YouTube-Instagram Connection  Posting Video Content</u></a></li>
<li><a href="https://windows11.techidaily.com/investigating-and-fixing-create-failed-on-windows-error-30005/"><u>Investigating and Fixing Create Failed on Windows Error 30005</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/iphone-se-2022-asking-for-passcode-after-ios-1714-update-what-to-do-drfone-by-drfone-ios/"><u>iPhone SE (2022) Asking for Passcode after iOS 17/14 Update, What to Do? | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/laughing-matters-how-effective-is-ai-like-chatgpt-at-making-us-chuckle/"><u>Laughing Matters: How Effective Is AI Like ChatGPT at Making Us Chuckle?</u></a></li>
<li><a href="https://windows11.techidaily.com/optimal-system-settings-reducing-resource-drain-while-playing/"><u>Optimal System Settings: Reducing Resource Drain While Playing</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-your-subnet-in-the-latest-os-win11/"><u>Optimizing Your Subnet in the Latest OS: Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-call-issue-fixed-runtime-errors-in-malwarebytes-for-win10win11/"><u>Overcoming the Call Issue: Fixed Runtime Errors in Malwarebytes for Win10/Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-this-file-is-alone-error-on-pcs/"><u>Overcoming This File Is Alone Error on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/proven-strategies-for-comprehensible-comic-consumption-on-win11/"><u>Proven Strategies for Comprehensible Comic Consumption on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/reset-chronology-fix-windows-time-errors/"><u>Reset Chronology: Fix Windows Time Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-gl-driver-error-3-on-windows-11-a-step-by-step-guide/"><u>Resolving GL Driver Error 3 on Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/restore-and-revitalize-13-ways-to-rejuvenate-windows-systems/"><u>Restore & Revitalize: 13 Ways to Rejuvenate Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/restore-full-size-to-your-windows-11-icons/"><u>Restore Full Size to Your Windows 11 Icons</u></a></li>
<li><a href="https://win-blog.techidaily.com/say-goodbye-to-interruptions-bypass-common-halo-infinite-lag-issues-on-pc-with-these-7-expert-fixes/"><u>Say Goodbye to Interruptions: Bypass Common Halo Infinite Lag Issues on PC With These 7 Expert Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/securely-clearing-email-details-post-login/"><u>Securely Clearing Email Details Post-Login</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-your-system-without-relying-on-bitlocker/"><u>Securing Your System without Relying on Bitlocker</u></a></li>
<li><a href="https://windows11.techidaily.com/seeking-entry-into-the-windows-11-insider-circle/"><u>Seeking Entry Into the Windows 11 Insider Circle</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/skyrocket-with-subscribers-5-proven-methods-for-igtv-success-for-2024/"><u>Skyrocket with Subscribers  5 Proven Methods for IGTV Success for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/starting-windows-terminal-with-quake-effects/"><u>Starting Windows Terminal with Quake Effects</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-correct-sound-hiccup-in-audacity-on-windows-11/"><u>Strategies to Correct Sound Hiccup in Audacity on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlined-startup-routines-in-modern-windows/"><u>Streamlined Startup Routines in Modern Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/surface-go-3-with-latest-chip-reviewed-mixed-outcomes-noted/"><u>Surface Go 3 with Latest Chip Reviewed: Mixed Outcomes Noted</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-non-existence-of-powershell-in-windows/"><u>Tackling the Non-Existence of PowerShell in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-elusive-guide-to-unseen-menu-adjustments-windows-style/"><u>The Elusive Guide to Unseen Menu Adjustments, Windows Style</u></a></li>
<li><a href="https://techidaily.com/the-way-to-recover-deleted-photos-on-itel-s23-without-backup-by-fonelab-android-recover-photos/"><u>The way to recover deleted photos on Itel S23 without backup.</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-windows-11s-compatibility-checker-usage-guide/"><u>Understanding Windows 11'S Compatibility Checker: Usage Guide</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unlocking-hdr-potential-with-photo-hdr-techniques-for-2024/"><u>Unlocking HDR Potential with Photo-HDR Techniques for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windowsstore-app-folder-hidden-entry-points/"><u>Unveiling WindowsStore App Folder Hidden Entry Points</u></a></li>
<li><a href="https://windows11.techidaily.com/visualize-resource-consumption-windows-tray-update-guide/"><u>Visualize Resource Consumption: Windows Tray Update Guide</u></a></li>
</ul></div>
