---
title: Altering Windows Login Lockout Interval After Errors
date: 2024-08-15T15:22:37.705Z
updated: 2024-08-16T15:22:37.705Z
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. This will pull up information, among other things, about how long this account lockout duration is currently set.
4. To change account lockout duration on Windows 10 and 11, type the following command into the console and hit **Enter.** Replace the number “60” in the command with any other number from zero to 99,999 to set how many minutes a user will have to wait before being allowed to try and log in again.  
`net accounts /lockoutduration:60`  
![Use the command prompt to change account lockout duration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-duration-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

<!-- affiliate ads begin -->
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://fox-blue.techidaily.com/new-2024-approved-360-aerial-panoramas-with-yuneec-breeze-drone-review/"><u>[New] 2024 Approved  360 Aerial Panoramas with Yuneec Breeze Drone Review</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-decoding-mycam-cams-video-quality-and-recording-speed/"><u>[New] 2024 Approved  Decoding MyCam Cam’s Video Quality and Recording Speed</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-master-video-cutting-and-splicing-with-vimeo-for-free/"><u>[New] 2024 Approved  Master Video Cutting & Splicing with Vimeo, for Free</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-the-quick-guide-to-capturing-and-storing-twitter-animated-content/"><u>[New] 2024 Approved  The Quick Guide to Capturing and Storing Twitter Animated Content</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-iphones-ultimate-podcast-downloading-manual/"><u>[New] IPhone's Ultimate Podcast Downloading Manual</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-quick-editing-incorporating-jump-cuts-in-video-content/"><u>[New] Quick Editing  Incorporating Jump Cuts in Video Content</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-exploring-the-future-with-av1-over-vp9/"><u>[Updated] Exploring the Future with AV1 over VP9</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-androids-best-moba-games-roundup-10-edition/"><u>[Updated] In 2024, Android's Best MOBA Games Roundup - #10 Edition</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-from-first-to-last-your-guide-to-youtube-video-looping-101/"><u>[Updated] In 2024, From First to Last  Your Guide to YouTube Video Looping 101</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-how-to-download-facebook-videos-on-windows-and-mac/"><u>[Updated] In 2024, How to Download Facebook Videos on Windows and Mac</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-pioneering-companies-for-haptic-rich-views/"><u>[Updated] Pioneering Companies for Haptic-Rich Views</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-skys-dynamic-range-masterpieces-website-roundup/"><u>[Updated] Sky's Dynamic Range Masterpieces - Website Roundup</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-top-12-flip-screen-cams-for-dynamic-videography/"><u>[Updated] Top 12 Flip-Screen Cams for Dynamic Videography</u></a></li>
<li><a href="https://windows11.techidaily.com/10-ways-to-fix-onedrive-sync-issues-on-windows-11/"><u>10 Ways to Fix OneDrive Sync Issues on Windows 11</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-streamlined-method-windows-clown-fish-audio-tweaker/"><u>2024 Approved  Streamlined Method  Windows Clown Fish Audio Tweaker</u></a></li>
<li><a href="https://windows11.techidaily.com/7-methods-for-correcting-unreachable-display-responses-in-windows/"><u>7 Methods for Correcting Unreachable Display Responses in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/8-ways-to-fix-the-windows-pin-not-working-in-windows-11-and-11/"><u>8 Ways to Fix the Windows PIN Not Working in Windows 11 & 11</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-process-system-isnt-responding-error-on-xiaomi-redmi-13c-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Process System Isnt Responding Error on Xiaomi Redmi 13C 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/a-list-of-frustrations-with-windows-11/"><u>A List of Frustrations with Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-windows-file-concordance-with-aoemi-tutorial/"><u>Achieve Windows File Concordance with AOEMi Tutorial</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-automatic-color-tuning-on-win11-devices/"><u>Activating Automatic Color Tuning on Win11 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-faulty-alerts-from-windows-10s-shield/"><u>Addressing Faulty Alerts From Windows 10'S Shield</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-the-high-demand-of-ntoskrnlexe-processes/"><u>Addressing the High Demand of Ntoskrnl.exe Processes</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-win-based-office-glitches-effectively/"><u>Addressing Win-Based Office Glitches Effectively</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-system-maintenance-locating-and-resolving-win-os-error-codes-via-command-prompt-expertise/"><u>Advanced System Maintenance: Locating and Resolving Win-OS Error Codes via Command Prompt Expertise</u></a></li>
<li><a href="https://sound-issues.techidaily.com/astro-a10-mic-not-working-heres-how-you-can-get-it-up-and-running-again/"><u>Astro A10 Mic Not Working? Here's How You Can Get It Up & Running Again</u></a></li>
<li><a href="https://windows11.techidaily.com/asus-vs-rog-the-battle-for-the-ultimate-portable-pc/"><u>ASUS Vs. ROG: The Battle for the Ultimate Portable PC?</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-changing-printer-behavior-on-windows/"><u>Avoiding Changing Printer Behavior on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-missed-emojis-activating-the-latest-on-windows-11/"><u>Avoiding Missed Emojis: Activating the Latest on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-performance-pitfalls-high-cpu-usage-with-rm/"><u>Avoiding Performance Pitfalls: High CPU Usage with RM</u></a></li>
<li><a href="https://windows11.techidaily.com/batch-folder-generation-in-windows-11-for-efficiency-boost/"><u>Batch Folder Generation in Windows 11 for Efficiency Boost</u></a></li>
<li><a href="https://windows11.techidaily.com/bestow-magical-menus-on-your-pc/"><u>Bestow Magical Menus on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-print-speed-on-pcs-tips-for-windows-users/"><u>Boosting Print Speed on PCs: Tips for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-black-backgrounds-on-your-windows-pc/"><u>Bypassing Black Backgrounds on Your Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/cant-choose-a-drive-to-install-games-on-the-xbox-app-for-windows-try-these-fixes/"><u>Can't Choose a Drive to Install Games on the Xbox App for Windows? Try These Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/clear-the-way-to-privacy-with-simple-steps-for-ms-defender/"><u>Clear the Way to Privacy with Simple Steps for MS Defender</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-windows-java-installation-roadblocks/"><u>Clearing Windows Java Installation Roadblocks</u></a></li>
<li><a href="https://windows11.techidaily.com/command-your-way-through-windows-11-nircmd-tips-and-tricks/"><u>Command Your Way Through Windows 11: NirCmd Tips & Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/compreeable-approach-to-tackle-type-troubles-in-windows-11-error-0x80049dd3/"><u>Compreeable Approach to Tackle Type Troubles in Windows 11 (Error: 0X80049DD3)</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-to-rectifying-windows-11-search-issues/"><u>Comprehensive Guide to Rectifying Windows 11 Search Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-frequent-anydesk-windows-complications/"><u>Conquering Frequent AnyDesk Windows Complications</u></a></li>
<li><a href="https://windows11.techidaily.com/converting-your-notepad-to-nighttime-mode-with-ease-on-windows-11/"><u>Converting Your Notepad to Nighttime Mode with Ease on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/coordinating-connections-dual-net-usage-on-a-single-windows-pc/"><u>Coordinating Connections: Dual Net Usage on a Single Windows PC</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/crafted-elegance-and-innovation-the-nixplay-iris-story/"><u>Crafted Elegance & Innovation - The Nixplay Iris Story</u></a></li>
<li><a href="https://windows11.techidaily.com/credential-control-in-win11-quick-ways-to-unlock-passwords/"><u>Credential Control in Win11: Quick Ways to Unlock Passwords</u></a></li>
<li><a href="https://windows11.techidaily.com/cure-the-save-issue-in-microsoft-oses/"><u>Cure the Save Issue in Microsoft OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/de-cluttering-notifications-tips-for-windows-11-users/"><u>De-Cluttering Notifications: Tips for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-and-rectifying-non-functional-batches-in-windows/"><u>Deciphering and Rectifying Non-Functional Batches in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/declutter-for-growth-optimize-with-win11-tiny/"><u>Declutter for Growth: Optimize With Win11 Tiny</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-mysteries-of-invisible-context-options-in-windows-11/"><u>Decoding the Mysteries of Invisible Context Options in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/decrease-resource-load-managing-news-app-consumption/"><u>Decrease Resource Load: Managing News App Consumption</u></a></li>
<li><a href="https://windows11.techidaily.com/delving-into-windows-11s-data-preservation-capabilities/"><u>Delving Into Windows 11'S Data Preservation Capabilities</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/digital-dojo-learn-lithuanian-with-precision-and-flair/"><u>Digital Dojo: Learn Lithuanian with Precision and Flair</u></a></li>
<li><a href="https://windows11.techidaily.com/disentangling-common-errors-in-windows-11-zoom-app/"><u>Disentangling Common Errors in Windows 11 Zoom App</u></a></li>
<li><a href="https://win-amazing.techidaily.com/easy-guide-to-get-epson-v700-driver-for-various-windows-versions/"><u>Easy Guide to Get Epson V700 Driver for Various Windows Versions</u></a></li>
<li><a href="https://android-unlock.techidaily.com/forgotten-the-voicemail-password-of-sony-try-these-fixes-by-drfone-android/"><u>Forgotten The Voicemail Password Of Sony? Try These Fixes</u></a></li>
<li><a href="https://driver-install.techidaily.com/free-netgear-wireless-usb-adapter-download/"><u>Free Netgear Wireless USB Adapter Download</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/from-raw-footage-to-mov-windows-10-filming-techniques-for-2024/"><u>From Raw Footage to MOV  Windows 10 Filming Techniques for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-lava-s-lock-screen-pattern-pin-or-password-by-drfone-android-unlock-android-unlock/"><u>How to bypass Lava ’s lock screen pattern, PIN or password</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-4-ways-to-unlock-apple-iphone-15-to-use-usb-accessories-without-passcode-by-drfone-ios/"><u>In 2024, 4 Ways to Unlock Apple iPhone 15 to Use USB Accessories Without Passcode</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-best-3-software-to-transfer-files-tofrom-your-honor-x50iplus-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Best 3 Software to Transfer Files to/from Your Honor X50i+ via a USB Cable | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-infinix-smart-7-hd-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Infinix Smart 7 HD? | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-the-complete-guide-to-google-pixel-7a-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Complete Guide to Google Pixel 7a FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-the-ultimate-gag-reel-collection-comical-cells-and-cell-blocks-on-facebook/"><u>In 2024, The Ultimate Gag Reel Collection  Comical Cells and Cell Blocks on Facebook</u></a></li>
<li><a href="https://windows11.techidaily.com/1719366391353-keyboards-on-the-ropes-reclaim-your-arrows/"><u>Keyboards on the Ropes? Reclaim Your Arrows!</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-wevideo-the-fast-and-easy-way-to-create-amazing-videos/"><u>New WeVideo The Fast and Easy Way to Create Amazing Videos</u></a></li>
<li><a href="https://network-issues.techidaily.com/overcoming-limitations-in-unsupported-freesync-setup/"><u>Overcoming Limitations in Unsupported FreeSync Setup</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/perfect-harmony-music-in-instagram-storytelling-for-2024/"><u>Perfect Harmony  Music in Instagram Storytelling for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/1719211883980-tackling-the-challenge-of-non-working-win-plus-printer-feature-in-windows/"><u>Tackling the Challenge of Non-Working Win + Printer Feature in Windows</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-battle-of-the-console-generation-a-deep-dive-into-ps5-slim-vs-regular-ps5/"><u>The Battle of the Console Generation: A Deep Dive Into PS5 Slim Vs. Regular PS5</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/ultimate-guide-pairing-your-samsung-earbuds-with-a-pc/"><u>Ultimate Guide: Pairing Your Samsung Earbuds with a PC</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/understanding-the-page-not-found-mistake-explanation-and-solutions/"><u>Understanding the 'Page Not Found' Mistake: Explanation & Solutions</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/unmatched-value-top-tier-asmr-microphones-on-a-budget/"><u>Unmatched Value  Top-Tier ASMR Microphones on a Budget</u></a></li>
</ul></div>
