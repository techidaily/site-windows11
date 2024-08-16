---
title: Modifying Account Lockout Period Post-Failed Logon
date: 2024-08-15T16:19:54.039Z
updated: 2024-08-16T16:19:54.039Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Modifying Account Lockout Period Post-Failed Logon
excerpt: This Article Describes Modifying Account Lockout Period Post-Failed Logon
keywords: Login Cooldown Adjustment,Failed Access Revocation,Passcode Expiry Modification,Unauthorized Attempt Limitation,Lockout Period Revision,Security Lock Failover,Account Reset Timeframe
thumbnail: https://thmb.techidaily.com/98af3c33462a260586336a96ddc2cbdb473875d7a720808faf7dee8c99a861a3.jpg
---

## Modifying Account Lockout Period Post-Failed Logon

 Windows has a policy setting that can lock someone out from signing in if they enter the wrong local account password too many times. The user is not allowed to sign in for a set number of minutes after being locked out, but you can change this lockout duration.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

## How to Change the Duration a User Is Locked Out of Their Account via Local Security Policy

 This method will work as long as the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press **Windows key + R** to open the **Run** dialogue.
2. Type “secpol.msc” into the text field and hit **Enter**.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, click on the **Account Lockout Policy** folder under **Account Policies**.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on **Account lockout duration**.  
![Increase or decrease local account lockout](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-change-local-account-lockout-duration.jpg)
5. Type in a number between zero and 99,999, and hit **OK**. This will set how long (in minutes) the system will need before it accepts another login attempt.  
![Choose how long a local account is locked out](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-set-local-account-lockout-duration.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. This will pull up information, among other things, about how long this account lockout duration is currently set.
4. To change account lockout duration on Windows 10 and 11, type the following command into the console and hit **Enter.** Replace the number “60” in the command with any other number from zero to 99,999 to set how many minutes a user will have to wait before being allowed to try and log in again.  
`net accounts /lockoutduration:60`  
![Use the command prompt to change account lockout duration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-duration-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->
## Find the Balance Between Security and Convenience

 Setting account lockout duration too high will cause inconvenience, but if you set it to zero, an administrator will have to be contacted each time a user locks themselves out. Find a balance between security and convenience when it comes to changing how long a user is locked out after a set number of failed login attempts.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-clips.techidaily.com/new-dive-into-fixes-for-your-troublesome-instagram-video-for-2024/"><u>[New] Dive Into Fixes for Your Troublesome Instagram Video for 2024</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-interactive-twit-narratives-a-compendium-for-23/"><u>[New] Interactive Twit-Narratives - A Compendium for '23</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-mastering-the-art-of-online-passport-photography-our-top-picks/"><u>[New] Mastering the Art of Online Passport Photography - Our Top Picks</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-mastering-video-structure-a-comprehensive-guide-to-chapter-addition-on-youtube/"><u>[New] Mastering Video Structure  A Comprehensive Guide to Chapter Addition on YouTube</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-perfecting-posts-how-to-border-videos-on-instagram/"><u>[New] Perfecting Posts  How to Border Videos on Instagram</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-spotlight-series-celebrating-top-10-game-bloggers/"><u>[New] Spotlight Series  Celebrating Top 10 Game Bloggers</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-ultimate-drone-buying-roadmap-pre-purchase-essentials/"><u>[New] The Ultimate Drone Buying Roadmap  Pre-Purchase Essentials</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-integrating-obs-recording-capabilities-into-zoom-sessions/"><u>[Updated] 2024 Approved  Integrating OBS Recording Capabilities Into Zoom Sessions</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-expert-tips-finding-the-best-text-design-resources/"><u>[Updated] Expert Tips  Finding the Best Text Design Resources</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-trending-topics-the-best-10-music-videos-on-fb/"><u>[Updated] In 2024, Trending Topics  The Best 10 Music Videos on FB</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-the-future-of-social-sharing-youtube-to-fb-techniques-for-2024/"><u>[Updated] The Future of Social Sharing  YouTube to FB Techniques for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-mastering-google-meets-grid-view-functionality/"><u>2024 Approved  Mastering Google Meet's Grid View Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/averting-self-triggered-openings-on-msdnstoreapp/"><u>Averting Self-Triggered Openings on MSDN/StoreApp</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-unresponsive-clicks-with-these-fixes/"><u>Conquer Unresponsive Clicks with These Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/dealing-with-interrupt-at-breakpoint-issue-in-windows-debugging/"><u>Dealing with Interrupt at Breakpoint Issue in Windows Debugging</u></a></li>
<li><a href="https://windows11.techidaily.com/dial-up-speed-strategies-to-revive-your-sluggish-pc/"><u>Dial Up Speed: Strategies to Revive Your Sluggish PC</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/different-methods-to-unlock-your-iphone-15-plus-drfone-by-drfone-ios/"><u>Different Methods To Unlock Your iPhone 15 Plus | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-macos-with-cross-operating-system-tools/"><u>Elevating macOS with Cross-Operating System Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-windows-11-quality-first-fun-second/"><u>Elevating Windows 11: Quality First, Fun Second</u></a></li>
<li><a href="https://windows11.techidaily.com/explore-safest-windows-free-software-hubs/"><u>Explore Safest Windows Free Software Hubs</u></a></li>
<li><a href="https://windows11.techidaily.com/fast-track-favorites-windows-11-shortcuts-for-uwp-apps/"><u>Fast-Track Favorites: Windows 11 Shortcuts for UWP Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-sharing-errors-with-nvidias-gui/"><u>Fixing Sharing Errors with NVIDIA's GUI</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-for-resolving-missing-drivers-alert-on-windows-setup/"><u>Guidelines for Resolving Missing Drivers Alert on Windows Setup</u></a></li>
<li><a href="https://facebook.techidaily.com/how-to-create-a-memorable-3d-image-for-facebook-friends/"><u>How to Create a Memorable 3D Image for Facebook Friends</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-extend-the-pin-length-in-windows-11-and-11/"><u>How to Extend the PIN Length in Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-local-security-authority-protection-is-off-security-warning-on-windows/"><u>How to Fix the “Local Security Authority Protection Is Off” Security Warning on Windows</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-imei-unlokers-for-your-vivo-v30-phone-by-drfone-android/"><u>In 2024, Top IMEI Unlokers for Your Vivo V30 Phone</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-application-failure-the-notorious-error-the-application-couldnt-start-xc000003e-on-win11-and-11/"><u>Navigating Application Failure: The Notorious Error The Application Couldn’t Start Xc000003e on Win11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/optimal-system-settings-reducing-resource-drain-while-playing/"><u>Optimal System Settings: Reducing Resource Drain While Playing</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-your-subnet-in-the-latest-os-win11/"><u>Optimizing Your Subnet in the Latest OS: Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-microsoft-m365-glitch-with-code-30015-26/"><u>Remedy Microsoft M365 Glitch with Code 30015-26</u></a></li>
<li><a href="https://windows11.techidaily.com/reset-chronology-fix-windows-time-errors/"><u>Reset Chronology: Fix Windows Time Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-non-existence-of-powershell-in-windows/"><u>Tackling the Non-Existence of PowerShell in Windows</u></a></li>
<li><a href="https://android-unlock.techidaily.com/top-4-sim-location-trackers-to-easily-find-your-lost-vivo-t2x-5g-device-by-drfone-android/"><u>Top 4 SIM Location Trackers To Easily Find Your Lost Vivo T2x 5G Device</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-office-suites-strict-safe-mode-on-windows-operations/"><u>Troubleshooting Office Suite's Strict Safe Mode on Windows Operations</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-device-control-for-sleep-state-wakefulness/"><u>Unlocking Device Control for Sleep State Wakefulness</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/unveiling-the-beginning-an-in-depth-guide-to-tracking-originality-on-insta-for-2024/"><u>Unveiling The Beginning  An In-Depth Guide to Tracking Originality on Insta for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/unveiling-the-secrets-to-youtube-highlighted-remarks-for-2024/"><u>Unveiling the Secrets to YouTube Highlighted Remarks for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windowsstore-app-folder-hidden-entry-points/"><u>Unveiling WindowsStore App Folder Hidden Entry Points</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>