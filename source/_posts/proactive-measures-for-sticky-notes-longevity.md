---
title: Proactive Measures for Sticky Notes' Longevity
date: 2024-08-15T15:50:06.174Z
updated: 2024-08-16T15:50:06.174Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Proactive Measures for Sticky Notes' Longevity
excerpt: This Article Describes Proactive Measures for Sticky Notes' Longevity
keywords: Long-Lasting Sticky Notes,Extend Sticky Note Life,Durable Notes Tactic,Tips to Prolong Notes,Sticky Longevity Strategies,Enhancing Note Durability,Proactive Stickiness Preservation
thumbnail: https://thmb.techidaily.com/dd77f8cbbec8ed8ce40dfd9ce55bda6a399ba6919afea3bdd375bc2f3e522289.jpg
---

## Proactive Measures for Sticky Notes' Longevity

 Sticky Notes on Windows turn your computer into a virtual board for posting notes, reminders, lists, and pretty much anything that you need to remember at a glance. So it makes sense that you wouldn't want to lose them, whether you're switching computers or a problem with your PC has caused you to lose your data.

 In this guide, we're going to show you a couple of ways to back up your sticky notes on Windows.

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
![the Sync Now button in Sticky Notes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/sync-now-button-in-sticky-notes.jpg)

 To restore the notes on another computer, open the Sticky Notes app (make sure the PC is connected to the internet) and sign in with your Microsoft account. Once signed in, the app will load all the notes you previously synced. Furthermore, every time you finish writing a Sticky Note or edit one, the app will automatically back it up to the cloud.

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Manually Back Up and Restore Your Sticky Notes

 If you don't want to use a Microsoft account or want to have an extra backup of your sticky notes, then you can manually back them up yourself. While it's not as easy as just syncing them to the cloud, it can definitely come in handy when you don't have internet access and want to restore the notes.

 To manually back up your sticky notes, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.  
![opening tne Local State folder in Windows Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/opening-local-state-folder-in-windows-run.jpg)
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. In the **LocalState** folder, copy the **plum.sqlite** file.  
![the plum database for Sticky Notes on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/the-plum-database-for-sticky-notes-on-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
4. Paste the **plum.sqlite** file to an external drive, such as a flash drive or external SDD, or upload it to cloud storage, such as OneDrive or Google Drive, for safekeeping.

 To manually restore your sticky notes on another Windows computer, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.
3. Go to where you saved the backup of your sticky notes (the **plum.sqlite** file) and copy it.
4. In the **LocalState** folder, delete the current **plum.sqlite** file.
5. Paste the backup **plum.sqlite** file in the **LocalState** folder.

 Now when you open Sticky Notes, it will load the **plum.sqlite** file, and you should see all your notes appear in the app.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
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
<li><a href="https://graphic-issues.techidaily.com/corrected-drivers-display-system-back-to-normal/"><u>[Corrected] Drivers: Display System Back to Normal</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-best-practices-for-uploading-windows-media-content-to-vimeo/"><u>[New] 2024 Approved  Best Practices for Uploading Windows Media Content to Vimeo</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-your-comprehensive-pathway-to-hidden-youtube-treasures/"><u>[New] 2024 Approved  Your Comprehensive Pathway to Hidden YouTube Treasures</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-balancing-dimensions-the-ultimate-guide-to-social-media-video-sizes-on-fb-for-2024/"><u>[New] Balancing Dimensions  The Ultimate Guide to Social Media Video Sizes on FB for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-essential-techniques-for-screen-casts-ezvide-edition/"><u>[New] In 2024, Essential Techniques for Screen Casts - EZvide Edition</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-recording-realities-evaluating-the-power-and-precision-of-apeaksoftware/"><u>[New] In 2024, Recording Realities – Evaluating the Power and Precision of Apeaksoftware</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-problem-missing-driver-in-os/"><u>[PRINTER PROBLEM] Missing Driver in OS</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-best-low-cost-smartwatches-with-gaming-features/"><u>[Updated] Best Low-Cost Smartwatches with Gaming Features</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-how-to-add-music-to-youtubevideo-with-youtube-video-editor/"><u>[Updated] How to Add Music to YouTubeVideo with YouTube Video Editor</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-how-to-know-if-someone-blocked-you-on-snapchat/"><u>[Updated] How to Know if Someone Blocked You on Snapchat</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-depth-look-top-6-screen-recording-software-reviewed/"><u>[Updated] In-Depth Look  Top 6 Screen Recording Software Reviewed</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-pioneering-sites-for-downloading-text-aesthetics-for-2024/"><u>[Updated] Pioneering Sites for Downloading Text Aesthetics for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-pushing-past-vimeos-limits-with-top-10-editors/"><u>[Updated] Pushing Past Vimeo's Limits with Top 10 Editors</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-the-essentials-2023s-highest-ranked-twitter-content/"><u>[Updated] The Essentials  2023'S Highest-Ranked Twitter Content</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-ultimate-route-to-rejuvenate-and-refine-your-vhs-collection-online/"><u>[Updated] The Ultimate Route to Rejuvenate and Refine Your VHS Collection Online</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-direct-screen-capture-chrome-os-tool/"><u>2024 Approved  Direct Screen Capture Chrome OS Tool</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-instagrams-mirror-reflecting-true-selfie-essence/"><u>2024 Approved  Instagram's Mirror  Reflecting True Selfie Essence</u></a></li>
<li><a href="https://howto.techidaily.com/9-quick-fixes-to-unfortunately-touchwiz-has-stopped-of-honor-90-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Quick Fixes to Unfortunately TouchWiz has stopped Of Honor 90 Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/alleviating-overuse-of-wmi-in-windows-installer/"><u>Alleviating Overuse of WMI in Windows Installer</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-productivity-select-6-crucial-android-apps-for-windows-11/"><u>Boosting Productivity: Select 6 Crucial Android Apps for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/camouflage-computing-integrating-archives-into-digital-image-win/"><u>Camouflage Computing: Integrating Archives Into Digital Image WIN</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-windows-0xfffffff-confusion-quick-fixes/"><u>Clearing Windows' 0XFFFFFFF Confusion: Quick Fixes</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-vpna-to-fake-gps-location-on-oppo-reno-11-5g-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use VPNa to Fake GPS Location On Oppo Reno 11 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-and-solving-hard-drive-failures/"><u>Deciphering and Solving Hard Drive Failures</u></a></li>
<li><a href="https://windows11.techidaily.com/declutter-your-disk-space-auto-deletion-settings-for-windows-11/"><u>Declutter Your Disk Space: Auto-Deletion Settings for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-file-error-puzzle-finding-solution-for-0x80070570-on-windows-11/"><u>Decoding the File Error Puzzle - Finding Solution for 0X80070570 on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/diagnosing-absent-monitor-display-issue/"><u>Diagnosing Absent Monitor Display Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/ditch-the-dated-wallpapers-triple-technique-trick/"><u>Ditch the Dated Wallpapers: Triple Technique Trick</u></a></li>
<li><a href="https://extra-information.techidaily.com/essential-know-how-for-video-filter-integration-on-digital-platforms/"><u>Essential Know-How for Video Filter Integration on Digital Platforms</u></a></li>
<li><a href="https://some-techniques.techidaily.com/ghostly-glimpses-innovation-highlights-for-2024/"><u>Ghostly Glimpses  Innovation Highlights for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-rectifying-memory-issues-on-pcs/"><u>Guide to Rectifying Memory Issues on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-address-geforce-nows-error-code-xc0f1103f/"><u>How To Address GeForce Now's Error Code Xc0f1103f</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-dive-into-and-remove-windows-usage-logs/"><u>How to Dive Into and Remove Windows Usage Logs</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-do-oppo-find-x6-screen-sharing-drfone-by-drfone-android/"><u>How To Do Oppo Find X6 Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-se-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone SE without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-honor-magic-6-pro-if-i-forgot-security-code-or-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Honor Magic 6 Pro If I Forgot Security Code or Password? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-an-attempt-was-made-to-reference-a-token-error-in-windows-1110/"><u>How to Fix the “An Attempt Was Made to Reference a Token” Error in Windows 11/10</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-lock-apps-on-realme-11-pro-to-protect-your-individual-information-by-drfone-android/"><u>In 2024, How to Lock Apps on Realme 11 Pro to Protect Your Individual Information</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-remove-and-reset-face-id-on-apple-iphone-15-drfone-by-drfone-ios/"><u>In 2024, How to Remove and Reset Face ID on Apple iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-reset-a-vivo-x100-phone-that-is-locked-by-drfone-android/"><u>In 2024, How to Reset a Vivo X100 Phone that is Locked?</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-ten-powerful-tiktok-strategies-for-viral-success/"><u>In 2024, Ten Powerful TikTok Strategies for Viral Success</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-unlock-software-for-motorola-g54-5g-device-top-5-picks-to-remove-android-locks-by-drfone-android/"><u>In 2024, The Best Android Unlock Software For Motorola G54 5G Device Top 5 Picks to Remove Android Locks</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-understanding-facebook-reels-and-their-production-techniques/"><u>In 2024, Understanding Facebook Reels and Their Production Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/instant-change-of-windows-dashboard-background/"><u>Instant Change of Windows Dashboard Background</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/investigating-the-power-of-4-second-youtube-subscriptions-for-2024/"><u>Investigating the Power of 4-Second YouTube Subscriptions for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/master-syncing-how-to-rectify-non-syncing-in-ms-to-do/"><u>Master Syncing: How to Rectify Non-Syncing In MS To Do</u></a></li>
<li><a href="https://windows11.techidaily.com/master-your-gaming-journey-optimizing-ps1-experience-in-win-using-duckstations-guide/"><u>Master Your Gaming Journey: Optimizing PS1 Experience in WIN Using Duckstation's Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-camera-access-notification-controls-on-win11/"><u>Mastering Camera Access Notification Controls on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-to-windows-ease-of-access-in-5-steps/"><u>Navigating to Windows Ease of Access in 5 Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-your-way-installing-google-maps-on-pc/"><u>Navigating Your Way: Installing Google Maps on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/preserving-windows-default-time-configuration/"><u>Preserving Windows' Default Time Configuration</u></a></li>
<li><a href="https://windows11.techidaily.com/1719373513910-reawaken-chrome-on-win11-essential-troubleshooting-steps/"><u>Reawaken Chrome on Win11 – Essential Troubleshooting Steps.</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-0x800700e9-error-within-xbox-game-pass-and-windows-11/"><u>Rectifying 0X800700E9 Error Within Xbox Game Pass & Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/reignite-your-windows-11-search-top-11-fixes-here/"><u>Reignite Your Windows 11 Search: Top 11 Fixes Here</u></a></li>
<li><a href="https://review-topics.techidaily.com/reinstall-your-drivers-with-device-manager-on-windows-10-by-drivereasy-guide/"><u>Reinstall your drivers with Device Manager on Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-solo-side-windows-earbud-sound-problems/"><u>Resolving Solo Side Windows Earbud Sound Problems</u></a></li>
<li><a href="https://video-capture.techidaily.com/secure-your-conversations-on-the-go-with-top-10-mobile-chat-apps/"><u>Secure Your Conversations on the Go with Top 10 Mobile Chat Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/1719374357320-seven-big-mistakes-new-users-could-make-in-windows-11-to-avoid/"><u>Seven Big Mistakes New Users Could Make in Windows 11 - To Avoid!</u></a></li>
<li><a href="https://windows11.techidaily.com/sky-high-internet-beyond-100mbps-overcoming-windows-speed-ceiling/"><u>Sky-High Internet Beyond 100Mbps: Overcoming Windows' Speed Ceiling</u></a></li>
<li><a href="https://windows11.techidaily.com/slashing-gpu-energy-on-desktop-window-manager/"><u>Slashing GPU Energy on Desktop Window Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-address-systemsettings-errors-in-windows-11/"><u>Steps to Address SystemSettings Errors in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-install-non-verified-windows-applications/"><u>Steps to Install Non-Verified Windows Applications</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-mend-windows-network-proxy-errors/"><u>Steps to Mend Windows Network Proxy Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-visual-comfort-notebook-themes-and-fonts-in-windows-11/"><u>Tailoring Visual Comfort: Notebook Themes and Fonts in Windows 11</u></a></li>
<li><a href="https://buynow-help.techidaily.com/the-mini-marvel-unpacking-the-full-capabilities-of-amazons-3rd-gen-echo-dot/"><u>The Mini Marvel - Unpacking the Full Capabilities of Amazon's 3Rd Gen Echo Dot.</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-complex-windows-partition-unification/"><u>The Ultimate Guide to Complex Windows Partition Unification</u></a></li>
<li><a href="https://windows11.techidaily.com/three-strategies-to-redo-windows-11-user-preferences/"><u>Three Strategies to Redo Windows 11 User Preferences</u></a></li>
<li><a href="https://windows11.techidaily.com/time-is-money-restoring-windows-server-time-quickly/"><u>Time Is Money: Restoring Windows Server Time Quickly</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-imei-unlokers-for-your-nokia-g42-5g-phone-by-drfone-android/"><u>Top IMEI Unlokers for Your Nokia G42 5G Phone</u></a></li>
<li><a href="https://windows11.techidaily.com/top-techniques-to-quell-input-delay-on-windows-11/"><u>Top Techniques to Quell Input Delay on Windows 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/unlock-lunapics-secret-to-stunning-visuals/"><u>Unlock LunaPic's Secret to Stunning Visuals</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-package-not-registered-image-glitches-in-win11/"><u>Unraveling 'Package Not Registered' Image Glitches in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-overhaul-pretend-its-windows-98-edition/"><u>Windows Overhaul: Pretend It's Windows 98 Edition</u></a></li>
</ul></div>
