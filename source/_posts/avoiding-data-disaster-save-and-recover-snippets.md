---
title: "Avoiding Data Disaster: Save & Recover Snippets"
date: 2024-07-29T04:20:28.403Z
updated: 2024-07-30T04:20:28.403Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Avoiding Data Disaster: Save & Recover Snippets"
excerpt: "This Article Describes Avoiding Data Disaster: Save & Recover Snippets"
keywords: Data Safety Tips,Snippet Protection,Save Data Quickly,Avoid Data Loss,Backup Solutions,Secure Snippets,Recovery Methods
thumbnail: https://thmb.techidaily.com/fddafecbf8d052882c8613835d6b91422875b8a8af17428f6e6ddf368419a301.jpg
---

## Avoiding Data Disaster: Save & Recover Snippets

 Sticky Notes on Windows turn your computer into a virtual board for posting notes, reminders, lists, and pretty much anything that you need to remember at a glance. So it makes sense that you wouldn't want to lose them, whether you're switching computers or a problem with your PC has caused you to lose your data.

 In this guide, we're going to show you a couple of ways to back up your sticky notes on Windows.

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Back Up and Restore YourSticky Notes Using a Microsoft Account

 The easiest way to back up your sticky notes is to use a Microsoft account, which stores the notes on the cloud. If you don't have one already, then you can [learn how to create a Microsoft account](https://www.makeuseof.com/your-microsoft-account-things-windows-user-should-know/) or skip to the next section to learn how to back up the notes manually.

 If you've been using Windows with your Microsoft account all along, the notes could be synced to the cloud already. If you're not, you can [switch from a local account to a Microsoft account](https://www.makeuseof.com/windows-switch-local-account-to-microsoft-account/) for that to happen.

 To be sure if Sticky Notes is syncing your notes already or, if you're using a local account, give the app the ability to do so, follow the steps below:

1. Connect your Windows PC to the internet and open Sticky Notes.
2. Click on **Settings** (the gear icon) in the top right corner.
3. If you've already signed in, you'll see the details of your Microsoft account at the top with a **Sign out** link. If that's the case, you can skip to step #7 to sync the notes. If you're not signed in, click **Sign in**.
4. In the **Use one of these accounts** section, select the Microsoft account you want to sign in with. If there are no accounts there, select either **Microsoft account** or **Work or school account** in the **Use a different account** section.
5. Click **Continue** and follow the instructions to complete the sign-in process.
6. Once you're signed in, click on **Settings** again in the top right corner.
7. Scroll down and click **Sync now**.  
<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
![the Sync Now button in Sticky Notes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/sync-now-button-in-sticky-notes.jpg)

 To restore the notes on another computer, open the Sticky Notes app (make sure the PC is connected to the internet) and sign in with your Microsoft account. Once signed in, the app will load all the notes you previously synced. Furthermore, every time you finish writing a Sticky Note or edit one, the app will automatically back it up to the cloud.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Manually Back Up and Restore Your Sticky Notes

 If you don't want to use a Microsoft account or want to have an extra backup of your sticky notes, then you can manually back them up yourself. While it's not as easy as just syncing them to the cloud, it can definitely come in handy when you don't have internet access and want to restore the notes.

 To manually back up your sticky notes, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.  
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->
![opening tne Local State folder in Windows Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/opening-local-state-folder-in-windows-run.jpg)
3. In the **LocalState** folder, copy the **plum.sqlite** file.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
![the plum database for Sticky Notes on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/the-plum-database-for-sticky-notes-on-windows.jpg)
4. Paste the **plum.sqlite** file to an external drive, such as a flash drive or external SDD, or upload it to cloud storage, such as OneDrive or Google Drive, for safekeeping.

 To manually restore your sticky notes on another Windows computer, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.
3. Go to where you saved the backup of your sticky notes (the **plum.sqlite** file) and copy it.
4. In the **LocalState** folder, delete the current **plum.sqlite** file.
5. Paste the backup **plum.sqlite** file in the **LocalState** folder.

 Now when you open Sticky Notes, it will load the **plum.sqlite** file, and you should see all your notes appear in the app.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->
## Never Lose Your Sticky Notes Again

 Losing your sticky notes means you could lose potentially important information. So it makes sense to always have a copy stored somewhere in case you need to restore them. We recommend using your Microsoft account to back up the notes, considering it's convenient to both sync and restore them later on, but it's also a good idea to know that there's a manual option available.

 In this guide, we're going to show you a couple of ways to back up your sticky notes on Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-gamers-guide-to-video-recording/"><u>[New] 2024 Approved  Gamer's Guide to Video Recording</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-perfecting-mp4-conversion-ipv-techniques-for-high-quality-videos/"><u>[New] 2024 Approved  Perfecting MP4 Conversion  IPV Techniques for High-Quality Videos</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-mastering-conversations-and-sharing-in-facebook-world/"><u>[New] In 2024, Mastering Conversations and Sharing in Facebook World</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-unlocking-insta-stardom-15-effortless-steps-towards-rapid-and-sustained-fame/"><u>[New] In 2024, Unlocking Insta Stardom  15 Effortless Steps Towards Rapid and Sustained Fame</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-instagram-mastery-the-top-10-steps-to-optimize-engagement-for-2024/"><u>[New] Instagram Mastery  The Top 10 Steps to Optimize Engagement for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-thriving-as-a-team-on-youtube-perfect-pairings-for-success/"><u>[New] Thriving as a Team on YouTube  Perfect Pairings for Success</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-ultimate-storage-enhancement-for-sony-alpha-7s-ii/"><u>[New] Ultimate Storage Enhancement for Sony Alpha 7S II</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-win-10s-best-webcam-recording-software-guide/"><u>[Updated] 2024 Approved  Win 10'S Best Webcam Recording Software Guide</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-in-2024-unlock-new-dimensions-in-tiktok-videos-through-exquisite-bg-selection/"><u>[Updated] In 2024, Unlock New Dimensions in TikTok Videos Through Exquisite BG Selection</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-step-by-step-guide-to-excelling-at-final-cut-pro/"><u>[Updated] Step-by-Step Guide to Excelling at Final Cut Pro</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-crafting-contrast-and-depth-in-hdr-portraits/"><u>2024 Approved  Crafting Contrast and Depth in HDR Portraits</u></a></li>
<li><a href="https://games-able.techidaily.com/5-reasons-gamefi-will-never-take-off-or-attract-real-gamers/"><u>5 Reasons GameFi Will Never Take Off or Attract Real Gamers</u></a></li>
<li><a href="https://windows11.techidaily.com/9-steps-to-resolve-windows-hello-fingerprint-lockout/"><u>9 Steps to Resolve Windows Hello Fingerprint Lockout</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerate-vm-performance-on-windows-6-precise-tips-and-tricks/"><u>Accelerate VM Performance on Windows: 6 Precise Tips & Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-the-crashes-resource-monitor-on-windows-11/"><u>Addressing the Crashes: Resource Monitor on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-xp709-crash-in-windows/"><u>Addressing XP709 Crash in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/altering-failed-logon-wait-duration-settings-in-windows/"><u>Altering Failed Logon Wait Duration Settings in Windows</u></a></li>
<li><a href="https://techidaily.com/best-fixes-for-poco-c51-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Poco C51 Hard Reset | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-your-productivity-with-w11-desktop-organization/"><u>Boost Your Productivity with W11 Desktop Organization</u></a></li>
<li><a href="https://fox-access.techidaily.com/boosting-brand-visibility-through-youtube-sponsorships/"><u>Boosting Brand Visibility Through YouTube Sponsorships</u></a></li>
<li><a href="https://windows11.techidaily.com/ceasing-chrome-notifications-on-windows-desktop/"><u>Ceasing Chrome Notifications on Windows Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/confronting-error-code-xc0f1103f-in-nvidias-geforce-now/"><u>Confronting Error Code Xc0f1103f in NVIDIA's GeForce Now</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-tips-to-access-pcs-health-metrics/"><u>Decoding Tips to Access PC's Health Metrics</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminate-troubleshooting-roadblocks-for-compatibility-issues/"><u>Eliminate Troubleshooting Roadblocks for Compatibility Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/empowering-windows-users-introducing-a-customized-run-helper-app/"><u>Empowering Windows Users: Introducing a Customized Run Helper App</u></a></li>
<li><a href="https://windows11.techidaily.com/fasten-up-your-windows-devices-with-top-fixes-for-slow-web-linkage/"><u>Fasten Up Your Windows Devices with Top Fixes for Slow Web Linkage</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/fine-tuning-the-small-scenes-of-minecraft-for-2024/"><u>Fine-Tuning the Small Scenes of Minecraft for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-open-installation-packages-resolving-windows-errors/"><u>Guide to Open Installation Packages: Resolving Windows Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-an-uninstall-shortcut-to-the-context-menu-in-windows-1110/"><u>How to Add an Uninstall Shortcut to the Context Menu in Windows 11/10</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-bypass-icloud-activation-lock-on-mac-for-apple-iphone-6s-plus-by-drfone-ios/"><u>How To Bypass iCloud Activation Lock on Mac For Apple iPhone 6s Plus?</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-rectify-non-existent-lock-screen-countdown/"><u>How to Rectify Non-Existent Lock Screen Countdown</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-iphone-se-2020-online-here-are-6-easy-ways-by-drfone-ios/"><u>How to Unlock iPhone SE (2020) Online? Here are 6 Easy Ways</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-easy-ways-to-manage-your-xiaomi-redmi-note-12-5g-location-settings-drfone-by-drfone-virtual/"><u>In 2024, Easy Ways to Manage Your Xiaomi Redmi Note 12 5G Location Settings | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-samsung-galaxy-f15-5g-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>In 2024, How to Unlock Samsung Galaxy F15 5G Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://extra-tips.techidaily.com/master-class-adding-podcasts-to-instagram-features/"><u>Master Class  Adding Podcasts to Instagram Features</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-ais-pitfalls-the-risks-of-chatbots-in-windows-keys/"><u>Navigating AI's Pitfalls: The Risks of Chatbots in Windows Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-pc-performance-top-6-monitoring-apps-recommended-for-win/"><u>Optimize PC Performance: Top 6 Monitoring Apps Recommended for Win</u></a></li>
<li><a href="https://extra-support.techidaily.com/premier-action-cams-with-exceptional-image-stability-for-2024/"><u>Premier Action Cams with Exceptional Image Stability for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-win-strategies-boosting-frames-in-cs-go/"><u>Quick Win Strategies - Boosting Frames in CS GO</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-for-frozen-downloads-restart-tracker-resume-progress/"><u>Quick-Fix for Frozen Downloads: Restart Tracker, Resume Progress</u></a></li>
<li><a href="https://windows11.techidaily.com/remedial-tactics-for-loading-errors-in-discord-software/"><u>Remedial Tactics for Loading Errors in Discord Software</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-device-disconnection-problems-for-windows-users-with-virtualbox/"><u>Resolving Device Disconnection Problems for Windows Users with VirtualBox</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-your-windows-11-9-solutions-for-lost-bluetooth/"><u>Reviving Your Windows 11: 9 Solutions for Lost Bluetooth</u></a></li>
<li><a href="https://extra-skills.techidaily.com/revolutionizing-fields-with-virtual-reality-for-2024/"><u>Revolutionizing Fields with Virtual Reality for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/share-audio-waves-with-followers-on-instagram/"><u>Share Audio Waves with Followers on Instagram</u></a></li>
<li><a href="https://windows11.techidaily.com/significance-of-redistributing-visual-cplusplus/"><u>Significance of Redistributing Visual C++</u></a></li>
<li><a href="https://windows11.techidaily.com/slowing-down-windows-11-shutdown-tips-for-live-tasks/"><u>Slowing Down Windows 11 Shutdown: Tips for Live Tasks</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-windows-repeatedly-entering-cmos-settings/"><u>Solutions for Windows Repeatedly Entering CMOS Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/stopping-google-chrome-alerts-tips-for-windows/"><u>Stopping Google Chrome Alerts: Tips for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-controlling-file-compression-in-windows-11/"><u>Strategies for Controlling File Compression in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-6-best-to-do-list-apps-for-windows-10-and-11/"><u>The 6 Best To-Do List Apps for Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-complete-list-of-windows-11s-narrator-keyboard-shortcuts/"><u>The Complete List of Windows 11'S Narrator Keyboard Shortcuts</u></a></li>
<li><a href="https://windows11.techidaily.com/the-phasing-out-of-microsofts-windows-xp-7-and-81-lifeline/"><u>The Phasing Out of Microsoft's Windows XP, 7 & 8.1 Lifeline</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-your-computers-clock-display-with-animated-screensaver-apps/"><u>Transform Your Computer's Clock Display with Animated Screensaver Apps</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/unlock-poco-c65-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>Unlock Poco C65 Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-power-of-shortcuts-for-app-size-adjustment-on-windows-11/"><u>Unlocking the Power of Shortcuts for App Size Adjustment on Windows 11</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/yielding-income-a-streamers-guide-to-earning-for-2024/"><u>Yielding Income  A Streamer's Guide to Earning for 2024</u></a></li>
</ul></div>
