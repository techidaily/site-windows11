---
title: Configuring Account Lockout Reset in Successive Login Attempts Windows 10/11
date: 2024-08-08T05:55:52.853Z
updated: 2024-08-09T05:55:52.853Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Configuring Account Lockout Reset in Successive Login Attempts Windows 10/11
excerpt: This Article Describes Configuring Account Lockout Reset in Successive Login Attempts Windows 10/11
keywords: Windows Lockout Policy,Login Retry Limit,Secure Passwords,Reset Account Lockouts,Access Control Enhancements,Password Management Windows 10/11,User Security Settings Update,Lockout Policy Window,Retry Limit Security,Strong Passwords Essential,Reset User Lockouts,Access Control Windows,Password Settings Windows,Update Security Settings
thumbnail: https://thmb.techidaily.com/c01f488742f525379e15c90538d56863d279883606cc35ff29b3863a4d78b16e.jpg
---

## Configuring Account Lockout Reset in Successive Login Attempts Windows 10/11

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  
<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  
![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.
4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
<!-- affiliate ads begin -->
<a href="https://uperfect.sjv.io/c/5597632/1246754/15155" target="_top" id="1246754"><img src="//a.impactradius-go.com/display-ad/15155-1246754" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1246754/15155" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-record-videos.techidaily.com/new-boost-your-projects-quality-rankings-of-the-best-free-editing-apps-top-9-for-2024/"><u>[New] Boost Your Projects' Quality  Rankings of the Best Free Editing Apps (Top 9) for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-breaking-down-augmented-realitys-mysteries/"><u>[New] Breaking Down Augmented Reality's Mysteries</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-costlesscapture-revolutionizing-how-you-record-play/"><u>[New] CostlessCapture  Revolutionizing How You Record Play</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-in-2024-pixlr-essentials-10-pro-tips-to-transform-your-images/"><u>[New] In 2024, Pixlr Essentials  10 Pro Tips to Transform Your Images</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-the-enigma-of-missing-video-suggestions-in-your-feed/"><u>[New] In 2024, The Enigma of Missing Video Suggestions in Your Feed</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-the-definitive-guide-to-avoiding-youtube-copyright-issues/"><u>[New] The Definitive Guide to Avoiding YouTube Copyright Issues</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-crafting-quality-videos-a-guide-to-apple-device-screen-recording/"><u>[Updated] In 2024, Crafting Quality Videos  A Guide to Apple Device Screen Recording</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-peer-into-the-future-with-apeaksofts-screen-capture-trends-2023-for-2024/"><u>[Updated] Peer Into the Future with Apeaksoft’s Screen Capture Trends 2023 for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-twitters-top-10-viral-tiktoks-uncovered-for-2024/"><u>[Updated] Twitter's Top 10 Viral TikToks Uncovered for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-beyond-boundaries-the-five-pinnacle-cloud-storage-innovations/"><u>2024 Approved  Beyond Boundaries  The Five Pinnacle Cloud Storage Innovations</u></a></li>
<li><a href="https://fox-helps.techidaily.com/curating-background-beats-for-video-releases/"><u>Curating Background Beats for Video Releases</u></a></li>
<li><a href="https://windows11.techidaily.com/double-click-magic-apks-in-windows-11/"><u>Double-Click Magic: APKs in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-approaches-reviving-your-windows-11-search-feature/"><u>Effective Approaches: Reviving Your Windows 11 Search Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-use-of-notes-on-modern-windows-systems/"><u>Efficient Use of Notes on Modern Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-arrow-navigation-post-fixes/"><u>Effortless Arrow Navigation Post-Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-pc-mainteninas-auto-update-switch-latest-amd-video/"><u>Effortless PC Mainteninas: Auto Update, Switch Latest AMD Video</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-pc-experience-with-smart-windows-app-restarts/"><u>Elevate Your PC Experience with Smart Windows App Restarts</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-pcs-outlook-speeds-on-windows/"><u>Elevate Your PC's Outlook Speeds on Windows</u></a></li>
<li><a href="https://fox-direct.techidaily.com/elevating-enthrallment-yt-storytellers-to-track-in-23-for-2024/"><u>Elevating Enthrallment  YT Storytellers to Track in '23 for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminate-the-shrinkage-your-guide-to-a-stable-window/"><u>Eliminate the Shrinkage: Your Guide to a Stable Window</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-disk-read-errors-on-windows-os/"><u>Eliminating Disk Read Errors on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/empower-windows-11-notepad-via-smart-assistant/"><u>Empower Windows 11 Notepad via Smart Assistant</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-effortless-cross-platform-file-exchange/"><u>Enabling Effortless Cross-Platform File Exchange</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-local-storage-for-onedrive-windows-guide/"><u>Enabling Local Storage for OneDrive - Windows Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-text-interaction-on-windows-pdfs-step-by-step-guide/"><u>Enabling Text Interaction on Windows PDFs: Step by Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-images-on-windows-11-six-proven-scaling-strategies/"><u>Enhance Images on Windows 11: Six Proven Scaling Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-printer-functionality-in-windows-11-today/"><u>Enhance Printer Functionality in Windows 11 Today</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-tech-performance-with-live-interface-elements/"><u>Enhance Tech Performance with Live Interface Elements</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-typing-speed-mastering-windows-powertools/"><u>Enhance Typing Speed: Mastering Windows' PowerTools</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-your-system-navigating-the-smooth-windows-11-upgrade-process/"><u>Enhance Your System: Navigating the Smooth Windows 11 Upgrade Process</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-your-view-remove-windows-overscan-effects/"><u>Enhance Your View: Remove Windows Overscan Effects</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-your-workflow-with-a-customized-windows-outlook-schedule/"><u>Enhance Your Workflow with a Customized Windows Outlook Schedule</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-gameplay-selecting-the-ideal-install-drives/"><u>Enhancing Gameplay: Selecting the Ideal Install Drives</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-windows-experience-finding-your-missing-system-tab/"><u>Enhancing Window's Experience: Finding Your Missing System Tab</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-wsl2-android-resource-management/"><u>Enhancing WSL2: Android Resource Management</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-complete-screen-images-with-snip-and-sketch-tips/"><u>Ensuring Complete Screen Images with Snip & Sketch Tips.</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-continuous-access-to-your-digital-post-its/"><u>Ensuring Continuous Access to Your Digital Post-Its</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-data-verification-in-winrar-archives-with-six-solutions/"><u>Ensuring Data Verification in WinRAR Archives with Six Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-seamless-remote-device-connectivity-on-windows/"><u>Ensuring Seamless Remote Device Connectivity on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicating-directory-not-empty-fault-in-win11-os/"><u>Eradicating Directory Not Empty Fault in Win11 OS</u></a></li>
<li><a href="https://fox-http.techidaily.com/film-and-media-professionals-top-windows-edits-picks/"><u>Film & Media Professionals' Top Windows Edits Picks</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/ideal-drawing-programs-a-compreenasaurus-rex-guide-to-chromebooks-art-tools-for-2024/"><u>Ideal Drawing Programs  A Compreenasaurus Rex Guide to Chromebook's Art Tools for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-vivo-s17t-by-drfone-android/"><u>In 2024, Complete Review & Guide to Techeligible FRP Bypass and More For Vivo S17t</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-oneplus-ace-3-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>In 2024, How to Cast OnePlus Ace 3 to Computer for iPhone and Android? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-top-4-sim-location-trackers-to-easily-find-your-lost-nubia-red-magic-9-pro-device-by-drfone-android/"><u>In 2024, Top 4 SIM Location Trackers To Easily Find Your Lost Nubia Red Magic 9 Pro Device</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/leverage-online-platform-features-to-spread-your-music/"><u>Leverage Online Platform Features to Spread Your Music</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/safekeep-stories-the-unlimited-save-service/"><u>Safekeep Stories  The Unlimited Save Service</u></a></li>
<li><a href="https://extra-skills.techidaily.com/seamless-zooms-check-out-our-top-10-video-editors-for-2024/"><u>Seamless Zooms? Check Out Our Top 10 Video Editors for 2024</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/step-by-step-instructions-to-get-your-samsung-960-evo-ssd-running-on-windows/"><u>Step-by-Step Instructions to Get Your Samsung 960 EVO SSD Running on Windows</u></a></li>
<li><a href="https://howto.techidaily.com/want-to-uninstall-google-play-service-from-oneplus-nord-3-5g-here-is-how-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Want to Uninstall Google Play Service from OnePlus Nord 3 5G? Here is How | Dr.fone</u></a></li>
</ul></div>
