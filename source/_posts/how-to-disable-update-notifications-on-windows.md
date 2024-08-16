---
title: How to Disable Update Notifications on Windows
date: 2024-08-15T16:03:14.950Z
updated: 2024-08-16T16:03:14.950Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Disable Update Notifications on Windows
excerpt: This Article Describes How to Disable Update Notifications on Windows
keywords: Turn Off Windows Updates,Stop Update Alerts WIN,Halt WIN Update Notifies,Stop Update WIN Push,Disable Windows Update Tips,End WIN Update Messages,Quieten Windows Update Alarms
thumbnail: https://thmb.techidaily.com/9333e7c75e292a0b83b1e16b6df5d6742dede6cee3e1ad9fc6da9c95dfc95571.jpg
---

## How to Disable Update Notifications on Windows

 When an update is ready for installation, Windows notifies you and prompts you to restart your computer. As helpful as these reminders are, they can also be distracting at times. Fortunately, it’s possible to disable update notifications on Windows.

 You can disable Windows update notifications using the Settings app, Group Policy Editor, or Registry Editor. Let's go over each of these methods one by one.

## 1\. Disable Windows Update Notifications via the Settings App

 The quickest way to disable update notifications on Windows is through the Settings app. Here are the steps for the same.

1. Press**Win + I** to open Windows Settings. You can also use any method we cover in [how to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Update & Security > Windows Update** .
3. Select**Advanced options** .
4. Disable the toggle for**Notify me when a restart is required to finish updating** .
5. Disable the toggle for**Get me up to date** so that Windows does not display a restart warning when an update is ready for installation.  
![Disable Windows Update Notifications Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-the-settings-app.jpg)

 Once you complete the above steps, Windows should not bother you with update notifications.

<!-- affiliate ads begin -->
<span id="1793213">
					<video width="1080" height="1620" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19135-1793213">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:1080px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftinyland.pxf.io%2Fc%2F5597632%2F1793213%2F19135'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793213/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Disable Windows Update Notifications Using Group Policy Editor

 Group Policy Editor is a powerful tool for configuring various settings on your Windows computer. If you have the Enterprise or Professional edition of Windows, you can disable update notifications using the Group Policy Editor. If you don't have either of those versions, read our guide on [how to access Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

To disable Windows update notifications using Group Policy Editor:

1. Press**Win + R** to open the Run dialog box.
2. Type**gpedit.msc** in the box and press**Enter** .
3. In the Local Group Policy Editor window, use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Update > Manage end use experience.**
4. Double-click the**Display options for update notifications** policy on your right.
5. Select the**Disabled** option.
6. Click**Apply** followed by**OK** .  
![Disable Windows Update Notifications Using the Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-group-policy-editor-1.jpg)
<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you want to re-enable the Windows update notifications later, follow the same steps above and set the**Display options for update notifications** policy to**Not configured** .

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Disable Windows Update Notifications With Registry Editor

 If you can’t seem to access the Group Policy Editor for some reason, you can use the Registry Editor to disable update notifications.

 Since Registry Editor is a powerful tool that needs to be handled with care, we recommend that you back up all the registry files or create a restore point before proceeding with the changes below. If you need help, check our guides on [how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [how to create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) .

To disable Windows update notifications using Registry Editor:

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** in the box and press**Enter** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the Registry Editor window, use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft > Windows** .
5. Locate the**WindowsUpdate** key. If you can’t find it, right-click on the**Windows** key and select**New > Key** . Rename the key as**WindowsUpdate** .
6. Right-click the**WindowsUpdate** key and select**New > DWORD (32-bit) Value** .
7. Rename the DWORD as**SetUpdateNotificationLevel** .
8. Double-click the newly created DWORD and change its**Value data** to**0** .
9. Click**OK** .  
![Disable Windows Update Notifications Using the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-the-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->

 Exit the Registry Editor window and restart your PC to apply the changes. Following that, Windows will not display update notifications on your computer.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## No More Update Notifications on Windows

 Windows updates are critical for the overall stability of your computer. That said, turning off Windows update notifications makes sense if you're not in a rush to install updates as soon as they are ready for installation.

 If you find Windows notifications to be distracting in general, you can use Focus Assist to silence all alerts and stay productive.


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
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-chorus-chronicles-music-gadgets/"><u>[New] In 2024, Chorus Chronicles  Music Gadgets</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-say-goodbye-to-bloatware-with-these-44-superb-android-video-reducers/"><u>[New] In 2024, Say Goodbye to Bloatware with These 44 Superb Android Video Reducers</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-the-roadmap-to-fandom-10-secrets-for-rampant-fb-engagement/"><u>[New] In 2024, The Roadmap to Fandom  10 Secrets for Rampant FB Engagement</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-step-by-step-guide-mastering-ez-grabber/"><u>[New] Step-by-Step Guide  Mastering EZ Grabber</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-unlock-content-revenue-accessing-youtubes-partner-benefits/"><u>[New] Unlock Content Revenue  Accessing YouTube's Partner Benefits</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-finding-your-voice-on-youtube-a-guide-to-selective-audiences/"><u>[Updated] 2024 Approved  Finding Your Voice on YouTube  A Guide to Selective Audiences</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-explore-the-best-top-10-4k-mirrorless-camera-lists-for-2024/"><u>[Updated] Explore the Best  Top 10 4K Mirrorless Camera Lists for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-crafting-the-perfect-minecraft-playback-experience/"><u>[Updated] In 2024, Crafting the Perfect Minecraft Playback Experience</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-in-2024-the-realm-of-ring-vs-reality-stream/"><u>[Updated] In 2024, The Realm of Ring vs Reality Stream</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-video-editing-journeys-end-discover-the-best-10-tools-for-2024/"><u>[Updated] Video Editing Journey's End  Discover the Best 10 Tools for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-breakthroughs-in-ergonomic-office-design-for-high-efficiency/"><u>2024 Approved  Breakthroughs in Ergonomic Office Design for High Efficiency</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-hasten-your-windows-doc-analysis-process/"><u>2024 Approved  Hasten Your Windows Doc Analysis Process</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-secure-privacy-blur-out-details-efficiently-ps/"><u>2024 Approved  Secure Privacy  Blur Out Details Efficiently PS</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-top-picks-for-optimal-cloud-space-solutions/"><u>2024 Approved  Top Picks for Optimal Cloud Space Solutions</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/a-visual-journey-mastering-the-art-of-incorporating-text-into-images-on-pcmacos-for-2024/"><u>A Visual Journey  Mastering the Art of Incorporating Text Into Images on PC/MacOS for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/access-exclusive-content-prime-and-twitch-duo/"><u>Access Exclusive Content: Prime & Twitch Duo</u></a></li>
<li><a href="https://windows11.techidaily.com/automate-your-photo-display-craft-the-ultimate-win11-slideshow/"><u>Automate Your Photo Display - Craft the Ultimate Win11 Slideshow</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-download-velocity-in-steam-fending-off-drops/"><u>Boosting Download Velocity in Steam: Fending Off Drops</u></a></li>
<li><a href="https://windows11.techidaily.com/cease-windows-system-notification-for-upgrades/"><u>Cease Windows System Notification for Upgrades</u></a></li>
<li><a href="https://windows11.techidaily.com/chronological-corrections-6-utilities-to-edit-file-timestamps/"><u>Chronological Corrections: 6 Utilities to Edit File Timestamps</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-fixes-for-common-windows-monitor-mishaps/"><u>Comprehensive Fixes for Common Windows Monitor Mishaps</u></a></li>
<li><a href="https://windows11.techidaily.com/converting-oculus-q2-to-windows-pc-for-vr/"><u>Converting Oculus Q2 to Windows PC for VR</u></a></li>
<li><a href="https://windows11.techidaily.com/diagnosing-and-repairing-win-lsa-errors/"><u>Diagnosing and Repairing Win LSA Errors</u></a></li>
<li><a href="https://extra-information.techidaily.com/discovering-movavis-advanced-video-editor-plus-plus/"><u>Discovering Movavi's Advanced Video Editor Plus +</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-mouse-customization-tips-for-win11s-pointer-accessibility/"><u>Easy Mouse Customization Tips for Win11's Pointer Accessibility</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-initiating-the-snip-and-sketch-function-on-win-11/"><u>Efficiently Initiating the Snip and Sketch Function on Win 11</u></a></li>
<li><a href="https://program-issues.techidaily.com/essential-tricks-to-eliminate-lag-in-street-fighter-6-optimize-your-pc-gameplay/"><u>Essential Tricks to Eliminate Lag in Street Fighter 6: Optimize Your PC Gameplay</u></a></li>
<li><a href="https://windows11.techidaily.com/evaluating-the-new-windows-11-interface/"><u>Evaluating the New Windows 11 Interface</u></a></li>
<li><a href="https://tech-haven.techidaily.com/1721964614254-experience-ai-like-never-before-dive-into-openais-freshly-launched-gpt-custom-store-today/"><u>Experience AI Like Never Before - Dive Into OpenAI's Freshly Launched GPT Custom Store Today</u></a></li>
<li><a href="https://howto.techidaily.com/fix-unfortunately-settings-has-stopped-on-vivo-v30-lite-5g-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Unfortunately Settings Has Stopped on Vivo V30 Lite 5G Quickly | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/from-voice-to-text-in-minutes-harnessing-whispers-potential/"><u>From Voice to Text in Minutes: Harnessing Whisper's Potential</u></a></li>
<li><a href="https://youtube-data.techidaily.com/-gems-2017s-statistical-youtube-surprises-for-2024/"><u>Graph Gems  2017'S Statistical YouTube Surprises for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/harnessing-the-power-of-microsofts-ai-code-helper/"><u>Harnessing the Power of Microsoft's AI Code Helper</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-mfc71udll-not-found-or-missing-on-windows/"><u>How to Fix Mfc71u.dll Not Found or Missing on Windows</u></a></li>
<li><a href="https://facebook.techidaily.com/how-to-prepare-for-and-execute-an-effective-fb-account-shutdown/"><u>How to Prepare For and Execute an Effective FB Account Shutdown</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-fb-video-hacks-instant-mp4-downloads/"><u>In 2024, FB Video Hacks  Instant MP4 Downloads</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-universal-unlock-pattern-for-samsung-galaxy-m34-by-drfone-android/"><u>In 2024, Universal Unlock Pattern for Samsung Galaxy M34</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-unlocking-instagrams-secrets-detailed-guide-to-user-engagement-and-reach/"><u>In 2024, Unlocking Instagram's Secrets  Detailed Guide to User Engagement and Reach</u></a></li>
<li><a href="https://windows11.techidaily.com/low-ram-footprint-webbrowsers-an-intensive-benchmark-analysis/"><u>Low RAM Footprint Webbrowsers: An Intensive Benchmark Analysis</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-hello-fingerprint-setup-on-11/"><u>Mastering Windows Hello Fingerprint Setup on 11</u></a></li>
<li><a href="https://windows11.techidaily.com/method-for-startingstopping-windows-installer/"><u>Method for Starting/Stopping Windows Installer</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-in-2024-text-animation-made-easy-top-phone-apps-for-video-editing/"><u>New In 2024, Text Animation Made Easy Top Phone Apps for Video Editing</u></a></li>
<li><a href="https://windows11.techidaily.com/no-more-fbm-hurdles-top-windows-troubleshooting-tips/"><u>No More FBM Hurdles: Top Windows Troubleshooting Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-package-discrepinas-in-windows-photos-with-step-by-step-tips/"><u>Overcoming Package Discrepinas in Windows Photos with Step-by-Step Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-resource-monitor-stalls-in-windows-11/"><u>Overcoming Resource Monitor Stalls in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-obstacle-fixing-windows-system-function-interruption/"><u>Overcoming the Obstacle: Fixing Windows System Function Interruption</u></a></li>
<li><a href="https://windows11.techidaily.com/path-to-start-driver-verifier-toolset-in-windows-11/"><u>Path to Start Driver Verifier Toolset in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/precision-tools-for-crafting-custom-windows-filename-dates/"><u>Precision Tools for Crafting Custom Windows Filename Dates</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-to-resolving-pin-check-errors-on-windows-devices/"><u>Quick Guide to Resolving Pin Check Errors on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/reconfiguring-start-menu-and-browser-by-defaults/"><u>Reconfiguring Start Menu and Browser by Defaults</u></a></li>
<li><a href="https://windows11.techidaily.com/sneak-peek-at-windows-11-writers-seven-vintage-traits/"><u>Sneak Peek at Windows 11' Writers: Seven Vintage Traits</u></a></li>
<li><a href="https://windows11.techidaily.com/supercharging-download-speeds-tips-and-tricks-for-ms-marketplace/"><u>Supercharging Download Speeds: Tips & Tricks for MS Marketplace</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-invisibility-of-task-view-on-bar/"><u>Techniques for Invisibility of Task View on Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-turning-onoff-the-registry-editor/"><u>Techniques for Turning On/Off the Registry Editor</u></a></li>
<li><a href="https://windows11.techidaily.com/the-clarity-compass-directing-you-through-a-fuzzy-screen-fix-up/"><u>The Clarity Compass: Directing You Through a Fuzzy Screen Fix-Up</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-troubleshooting-ms-to-do-sync-failures/"><u>Tips for Troubleshooting MS To-Do Sync Failures</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/top-screener-solution-for-flawless-youtube-content-creation-for-2024/"><u>Top Screener Solution  For Flawless YouTube Content Creation for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-microsoft-store-error-code-0x80072f30/"><u>Troubleshooting Microsoft Store: Error Code 0X80072F30</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-microsoft-store-error-0x80072efd/"><u>Unblocking Microsoft Store Error 0X80072EFD</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/unleashing-creative-potential-making-youtube-trailers-in-filmora-for-2024/"><u>Unleashing Creative Potential  Making YouTube Trailers in Filmora for 2024</u></a></li>
</ul></div>
