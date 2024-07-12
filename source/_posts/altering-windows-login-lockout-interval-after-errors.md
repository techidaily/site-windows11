---
title: Altering Windows Login Lockout Interval After Errors
date: 2024-07-11T22:10:19.081Z
updated: 2024-07-12T22:10:19.081Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Altering Windows Login Lockout Interval After Errors
excerpt: This Article Describes Altering Windows Login Lockout Interval After Errors
keywords: Windows Login Lockout,Alter Lockout Time,Reduce Lockout Errors,Lockout Interval Change,Account Security Settings,Password Reset Options,Prevent Lockout Failures
thumbnail: https://thmb.techidaily.com/b57bdcbb41c7763c82190be25c28d361f666df5033d9cd0a341320bf7b8e56fa.jpg
---

## Altering Windows Login Lockout Interval After Errors

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

## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
3. This will pull up information, among other things, about how long this account lockout duration is currently set.
4. To change account lockout duration on Windows 10 and 11, type the following command into the console and hit **Enter.** Replace the number “60” in the command with any other number from zero to 99,999 to set how many minutes a user will have to wait before being allowed to try and log in again.  
`net accounts /lockoutduration:60`  
![Use the command prompt to change account lockout duration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-duration-command-prompt.jpg)

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

## Find the Balance Between Security and Convenience

 Setting account lockout duration too high will cause inconvenience, but if you set it to zero, an administrator will have to be contacted each time a user locks themselves out. Find a balance between security and convenience when it comes to changing how long a user is locked out after a set number of failed login attempts.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/5-ways-to-fix-the-remote-procedure-call-failed-error-in-windows/"><u>5 Ways to Fix the Remote Procedure Call Failed Error in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/browser-woes-7-methods-to-reach-elusive-pages-on-pc/"><u>Browser Woes? 7 Methods to Reach Elusive Pages on PC</u></a></li>
<li><a href="https://android-unlock.techidaily.com/unlocking-the-power-of-smart-lock-a-beginners-guide-for-vivo-v27e-users-by-drfone-android/"><u>Unlocking the Power of Smart Lock A Beginners Guide for Vivo V27e Users</u></a></li>
<li><a href="https://windows11.techidaily.com/accessing-and-running-verifier-manager-in-windows-11/"><u>Accessing and Running Verifier Manager in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/batch-enhancement-using-winstall-to-streamline-windows-11-updates/"><u>Batch Enhancement: Using Winstall to Streamline Windows 11 Updates</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-melody-match-masters-unveiling-the-hottest-tunes-on-web-platforms/"><u>2024 Approved Melody Match Masters Unveiling the Hottest Tunes on Web Platforms</u></a></li>
<li><a href="https://windows11.techidaily.com/breached-byte-bastion-maintain-reflect-then-switch/"><u>Breached Byte Bastion: Maintain, Reflect, Then Switch</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-screen-flickers-on-microsoft-os/"><u>Addressing Screen Flickers on Microsoft OS</u></a></li>
<li><a href="https://windows11.techidaily.com/7-things-to-try-when-the-epic-games-launcher-fails-to-send-a-security-code-on-windows/"><u>7 Things to Try When the Epic Games Launcher Fails to Send a Security Code on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/1719340671976-run-a-zero-cost-locally-accessible-gpt-on-your-pc-use-gpt4all/"><u>Run a Zero-Cost, Locally Accessible GPT on Your PC – Use GPT4All</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-lag-pro-level-valorant-fps-strategies/"><u>Avoiding Lag: Pro-Level Valorant FPS Strategies</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-pause-life360-location-sharing-for-samsung-galaxy-a14-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How To Pause Life360 Location Sharing For Samsung Galaxy A14 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-unable-to-start-application-error-xc000003e-in-windows-11/"><u>Avoiding Unable to Start Application Error Xc000003e in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/bluescreenview-explained-for-everyday-users/"><u>BlueScreenView Explained for Everyday Users</u></a></li>
<li><a href="https://windows11.techidaily.com/bridging-the-gap-fix-for-non-openable-windows-exe-files/"><u>Bridging the Gap: Fix for Non-Openable Windows .exe Files</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-in-depth-analysis-of-youtube-adrevenue-average-payout-per-1000-viewers-engagement/"><u>[New] In-Depth Analysis of YouTube AdRevenue  Average Payout per 1,000 Viewers' Engagement</u></a></li>
<li><a href="https://windows11.techidaily.com/beginners-tutorial-on-windows-canary-usage/"><u>Beginner’s Tutorial on Windows Canary Usage</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-back-sound-on-systems-running-low-volume-errors/"><u>Bring Back Sound on Systems Running Low Volume Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/bridging-gaps-quick-fixes-for-microsoft-to-do-discrepancies/"><u>Bridging Gaps: Quick Fixes for Microsoft To Do Discrepancies</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-photo-snapshots-in-windows-11/"><u>Adjusting Photo Snapshots in Windows 11</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-in-2024-journey-through-updates-unveiling-lg-bp550-new/"><u>[New] In 2024, Journey Through Updates  Unveiling LG BP550 New</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-mobile-media-posting-videos-not-retweets/"><u>In 2024, Mobile Media Posting  Videos, Not Retweets</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-export-ppt-as-animated-film-for-2024/"><u>[New] Export PPT as Animated Film for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-from-planning-to-performance-tips-for-wirecast-and-facebook-livestreaming/"><u>2024 Approved  From Planning to Performance  Tips for Wirecast & Facebook Livestreaming</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-wacatacbml-barriers-a-guide-for-safe-windows-navigation/"><u>Bypassing Wacatac.B!ml Barriers - A Guide for Safe Windows Navigation</u></a></li>
<li><a href="https://games-able.techidaily.com/xbox-s-excellence-achieving-perfect-blue-ray/"><u>XBox S Excellence - Achieving Perfect Blue-Ray</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-chrome-block-strategies-for-w11-users/"><u>Bypassing Chrome Block: Strategies for W11 Users</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-refined-connections-zoom-insight-for-professional-google-meets/"><u>[Updated] Refined Connections  Zoom Insight for Professional Google Meets</u></a></li>
<li><a href="https://windows11.techidaily.com/clarifying-the-concept-of-windows-ram-caching/"><u>Clarifying the Concept of Window's RAM Caching</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-acclaimed-20-open-source-pubg-thumbnail-bundles/"><u>[Updated] Acclaimed 20 Open Source PUBG Thumbnail Bundles</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-best-release-dates-for-podcast-episodes/"><u>In 2024, Best Release Dates for Podcast Episodes</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/gopro-video-editing-software-for-pc-quik-and-its-competitors/"><u>GoPro Video Editing Software for PC Quik and Its Competitors</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/15-superior-podcast-publishing-venues/"><u>15 Superior Podcast Publishing Venues</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-detect-and-stop-mspy-from-spying-on-your-vivo-v29e-drfone-by-drfone-virtual-android/"><u>In 2024, How to Detect and Stop mSpy from Spying on Your Vivo V29e | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-transform-your-streams-best-4k-video-downloaders-summarized/"><u>In 2024, Transform Your Streams  Best 4K Video Downloaders Summarized</u></a></li>
<li><a href="https://windows11.techidaily.com/capitalizing-on-windows-capabilities-for-macos/"><u>Capitalizing on Windows Capabilities for macOS</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-review-and-insight-into-movavi-editor-plus-now-available/"><u>In 2024, Review & Insight Into Movavi Editor Plus, Now Available</u></a></li>
<li><a href="https://windows11.techidaily.com/account-annihilation-simple-ways-to-render-user-non-existent-on-win11/"><u>Account Annihilation: Simple Ways to Render User Non-Existent on Win11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/9-best-phone-monitoring-apps-for-realme-11x-5g-drfone-by-drfone-virtual-android/"><u>9 Best Phone Monitoring Apps for Realme 11X 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-peak-performance-self-update-system-with-new-amd-drivers/"><u>Achieve Peak Performance: Self-Update System with New AMD Drivers</u></a></li>
<li><a href="https://windows11.techidaily.com/9-benefits-adopting-new-outlook-for-windows-users/"><u>9 Benefits: Adopting New Outlook for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/a-guide-to-completely-erase-drives-partitioning-in-windows/"><u>A Guide to Completely Erase Drive's Partitioning in Windows</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-essential-linux-software-for-efficient-screen-capture-for-2024/"><u>[Updated] Essential Linux Software for Efficient Screen Capture for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-latency-issues-when-connecting-external-monitors/"><u>Addressing Latency Issues When Connecting External Monitors</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-avoiding-blur-on-instagram-with-smart-zooms/"><u>In 2024, Avoiding Blur on Instagram with Smart Zooms</u></a></li>
<li><a href="https://windows11.techidaily.com/advance-windows-11-task-manager-refresh-speeds/"><u>Advance Windows 11 Task Manager Refresh Speeds</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-the-art-of-video-presentation-in-adobe-captivate/"><u>[Updated] The Art of Video Presentation in Adobe Captivate</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/mastering-macos-sierra-installation-procedures-for-2024/"><u>Mastering macOS Sierra Installation Procedures for 2024</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-call-history-from-xiaomi-redmi-13c-5g-by-fonelab-android-recover-call-logs/"><u>The way to get back lost call history from Xiaomi Redmi 13C 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/7-effective-ways-to-reopen-a-hidden-windows-terminal/"><u>7 Effective Ways to Reopen a Hidden Windows Terminal</u></a></li>
<li><a href="https://youtube-help.techidaily.com/making-a-channels-story-visible-in-snippets-for-2024/"><u>Making a Channel's Story Visible in Snippets for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-black-backgrounds-on-your-windows-pc/"><u>Bypassing Black Backgrounds on Your Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-update-four-techniques/"><u>Bypassing Windows Update: Four Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/a-practical-guide-to-creating-and-managing-a-win-11-hotspot/"><u>A Practical Guide to Creating and Managing a Win 11 Hotspot</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-key-games-for-every-sandbox-enthusiast/"><u>[Updated] Key Games for Every Sandbox Enthusiast</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-maximizing-mobile-profits-enabling-youtubers-revenue/"><u>2024 Approved  Maximizing Mobile Profits  Enabling YouTubers' Revenue</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-crafting-a-content-schedule-the-path-to-gaining-traction-on-youtube/"><u>[New] 2024 Approved  Crafting a Content Schedule  The Path to Gaining Traction on YouTube</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-cutting-edge-podcasting-garageband-edition/"><u>2024 Approved  Cutting Edge Podcasting  GarageBand Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/7-reasons-to-choose-windows-10-over-windows-11/"><u>7 Reasons to Choose Windows 10 Over Windows 11</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-unraveling-the-meaning-and-purpose-of-tiktoks-pfp-for-2024/"><u>[Updated] Unraveling the Meaning and Purpose of TikTok’s PFP for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-loss-the-top-8-windows-recovery-tips/"><u>Avoiding Loss: The Top 8 Windows Recovery Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-xbox-game-pass-failure-the-0x800700e9-factor/"><u>Addressing Xbox Game Pass Failure: The 0X800700E9 Factor</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-call-logs-from-your-nokia-by-fonelab-android-recover-call-logs/"><u>How to recover old call logs from your Nokia ?</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-print-speed-on-pcs-tips-for-windows-users/"><u>Boosting Print Speed on PCs: Tips for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/browser-breakdowns-heres-how-to-get-past-the-roadblocks-in-win-os/"><u>Browser Breakdowns? Here's How to Get Past the Roadblocks in WIN OS</u></a></li>
<li><a href="https://windows11.techidaily.com/brighten-up-windows-11-screens-with-easy-adjustments/"><u>Brighten Up Windows 11 Screens with Easy Adjustments!</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-exploring-hidden-realms-a-comprehensive-guide-to-youtubes-unlisted-videos/"><u>[Updated] 2024 Approved  Exploring Hidden Realms  A Comprehensive Guide to YouTube’s ‘Unlisted’ Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/bypass-the-troubleshooter-effective-fixes-in-vista-and-7/"><u>Bypass the Troubleshooter: Effective Fixes in Vista & 7</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-swiftly-upgrade-your-videos-with-professional-level-fb-subtitle-making-for-2024/"><u>[New] Swiftly Upgrade Your Videos with Professional-Level FB Subtitle Making for 2024</u></a></li>
</ul></div>
