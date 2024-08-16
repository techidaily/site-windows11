---
title: 5 Ways to Check Your Device Uptime on Windows 11
date: 2024-08-15T15:19:15.118Z
updated: 2024-08-16T15:19:15.118Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 5 Ways to Check Your Device Uptime on Windows 11
excerpt: This Article Describes 5 Ways to Check Your Device Uptime on Windows 11
keywords: Win11 Uptime Check,Windows Uptime Test,DevUptime Monitoring,PC Up Time Verify,Device Availability Windows,OS Health Status,System Downtime Check
thumbnail: https://thmb.techidaily.com/3df80ed0f3ba1234db4e3fe9b6b618140f5c8ecbd00a02e86f21f161aa5eef49.jpg
---

## 5 Ways to Check Your Device Uptime on Windows 11

 Checking your computer's uptime is something you might want to do to monitor its performance. This information can also come in handy when troubleshooting your system or performing regular maintenance tasks.

 Your Windows 11 PC provides several options for checking the device's uptime. Let’s go over all of them one by one.

## 1\. How to Find System Uptime Using Task Manager

 Windows Task Manager is an advanced tool that provides useful information about your PC’s hardware and software. Here's how you can use it to find your computer’s uptime.

1. Press**Ctrl + Shift + Esc** on your keyboard or use one of the [many ways to access Task Manager](https://www.makeuseof.com/how-to-access-task-manager-on-windows-11/) .
2. In the**Performance** tab, click on**CPU** .
3. Check the system uptime under the**Up time** section.  
![Check System Uptime Using Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-system-uptime-using-task-manager.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. How to Find System Uptime via the Settings App

 Another way to check your system's uptime is through the Windows Settings app. Here are the steps for the same.

1. Press**Win + I** to open the Settings app.
2. Select the**Network & internet** tab from the left sidebar.
3. Click on**Advanced network settings** .
4. Under the**Network adapters** section, click on the active network adapter and check the uptime mentioned next to**Duration** .  
![Check System Uptime Using Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-system-uptime-using-windows-settings-app.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Note that this method displays your network adapter’s uptime. So, the information displayed may not be accurate if you have reset your network connection after boot.

## 3\. How to Find System Uptime Using Control Panel

 If you prefer to do things the old-fashioned way, you can use the classic Control Panel to find your device’s uptime in Windows 11\. To do so, use the following steps:

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**control panel** in the box and select the first result that appears.
3. In the Control Panel window that appears, use the drop-down menu in the top right corner to change the view type to**Large icons** .
4. Click on**Network and Sharing Center** .
5. Click on**Change adapter settings** in the left pane.
6. Right-click on the active network adapter and select**Status** .
7. Under the**General** tab, you’ll find the uptime next to**Duration** .  
![Check System Uptime Using Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-system-uptime-using-control-panel.jpg)
<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
<!-- affiliate ads end -->
## 4\. How to Check System Uptime With Command Prompt

 If you're an advanced Windows user, you can also use Command Prompt to check your computer’s uptime. Here’s how:

1. Right-click on the Start icon or press**Win + X** to open the Power User menu.
2. Select**Terminal** from the list.
3. Type the following command in the console and press**Enter** .  
`systeminfo | find "System Boot Time"`  
![Check System Uptime Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-system-uptime-using-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->

 Once you run the above command, Command Prompt should display the time when your computer started operating. You can easily calculate the system uptime by subtracting the**System Boot Time** from the current time.

## 5\. How to Check System Uptime With PowerShell

 PowerShell is another command-line tool available on Windows. If you prefer using that, follow these steps to find your device’s uptime.

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**Windows PowerShell** and press**Enter** .
3. Paste the following command in the PowerShell window and press**Enter** .  
`(get-date) - (gcim Win32_OperatingSystem).LastBootUpTime`  
![Check System Uptime Using Windows PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-system-uptime-using-windows-powershell.jpg)

 PowerShell should display the number of days, hours, minutes, seconds, and milliseconds since the device was turned on.

 Like using PowerShell on Windows? Why not familiarize yourself with these [best PowerShell commands on Windows](https://www.makeuseof.com/windows-powershell-commands-cmdlets/) ?

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
<!-- affiliate ads end -->
## Checking Your Device Uptime on Windows 11

 As we just saw, finding your Windows 11 PC’s uptime is fairly simple. You can use any of the methods listed above to find that information.

 The total uptime of your computer may not provide you with accurate information about how much time you spend in front of it. For that, you’ll need to check Power & battery usage in the Windows Settings app.


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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-effective-engagement-incorporating-youtube-videos-into-slides/"><u>[New] 2024 Approved  Effective Engagement  Incorporating YouTube Videos Into Slides</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-essential-guide-to-top-hexacopter-models/"><u>[New] Essential Guide to Top Hexacopter Models</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-expert-techniques-for-capturing-and-recording-streamed-content-for-2024/"><u>[New] Expert Techniques for Capturing & Recording Streamed Content for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-jumpstart-your-filming-setups-8-sites-offering-free-eco-screens/"><u>[New] Jumpstart Your Filming Setups - 8 Sites Offering Free Eco-Screens</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/outubes-music-magic-best-free-tools-for-wav-conversion/"><u>[New] YouTube's Music Magic  Best Free Tools for WAV Conversion</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-elevate-your-digital-footprint-crafting-compelling-shorts-thumbnails/"><u>[Updated] 2024 Approved  Elevate Your Digital Footprint  Crafting Compelling Shorts Thumbnails</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-2024-approved-the-ultimate-guide-to-closing-videos-effectively/"><u>[Updated] 2024 Approved  The Ultimate Guide to Closing Videos Effectively</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-innovative-stop-motion-cinema-ranking-the-best-15/"><u>[Updated] Innovative Stop-Motion Cinema  Ranking the Best 15</u></a></li>
<li><a href="https://windows11.techidaily.com/10-easy-steps-for-a-working-windows-mouse/"><u>10 Easy Steps for a Working Windows Mouse</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-exquisite-home-designs-unlocked-in-blocky-landscapes/"><u>2024 Approved  Exquisite Home Designs Unlocked in Blocky Landscapes</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-how-to-prevent-youtube-from-starting-video-before-you-watch/"><u>2024 Approved  How to Prevent YouTube From Starting Video Before You Watch</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-sifting-through-the-elements-of-instagram-stories/"><u>2024 Approved  Sifting Through the Elements of Instagram Stories</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-ways-to-track-nokia-105-classic-without-them-knowing-drfone-by-drfone-virtual-android/"><u>3 Ways to Track Nokia 105 Classic without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/7-key-steps-to-overcome-google-chrome-profile-faults/"><u>7 Key Steps to Overcome Google Chrome Profile Faults</u></a></li>
<li><a href="https://windows11.techidaily.com/7-solutions-for-enabling-windows-11s-memory-check/"><u>7 Solutions for Enabling Windows 11'S Memory Check</u></a></li>
<li><a href="https://windows11.techidaily.com/a-leap-forward-for-windows-11-innovative-widget-features-proposal/"><u>A Leap Forward for Windows 11: Innovative Widget Features Proposal</u></a></li>
<li><a href="https://windows11.techidaily.com/a-simple-guide-to-activating-windows-hello-on-pc/"><u>A Simple Guide to Activating Windows Hello on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/a-users-guide-to-navigating-file-explorer-tabs-windows-11-style/"><u>A User's Guide to Navigating File Explorer Tabs, Windows 11 Style</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-delayed-auditory-feedback-on-pcs/"><u>Addressing Delayed Auditory Feedback on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-low-vram-issues-for-hogwarts-educational-virtual-adventure/"><u>Addressing Low VRAM Issues for Hogwarts Educational Virtual Adventure</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-spec-deficit-errors-from-windows-game-bar/"><u>Addressing Spec Deficit Errors From Window's Game Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-the-incorrect-identifier-message-in-windows-11/"><u>Addressing the 'Incorrect Identifier' Message in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-photo-snapshots-in-windows-11/"><u>Adjusting Photo Snapshots in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/arrows-at-a-standstill-try-these-remedies/"><u>Arrows at a Standstill? Try These Remedies</u></a></li>
<li><a href="https://windows11.techidaily.com/asus-zenbook-14-the-windows-mac-battle-continues/"><u>ASUS Zenbook 14: The Windows-Mac Battle Continues</u></a></li>
<li><a href="https://windows11.techidaily.com/audio-prowess-on-windows-a-comprehensible-drivers-upgrade-blueprint/"><u>Audio Prowess on Windows: A Comprehensible Drivers' Upgrade Blueprint</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-expiring-software-license-caution-in-windows-1011/"><u>Avoiding Expiring Software License Caution in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/awakening-hidden-pane-windows-effective-steps-for-win11/"><u>Awakening Hidden Pane Windows: Effective Steps for Win11</u></a></li>
<li><a href="https://program-issues.techidaily.com/banish-wow-lag-and-crash-glitches-with-these-painless-remedies/"><u>Banish WOW Lag and Crash Glitches with These Painless Remedies!</u></a></li>
<li><a href="https://windows11.techidaily.com/best-in-class-window-videomodding-tools-our-top-picks/"><u>Best-in-Class Window Videomodding Tools: Our Top Picks</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-your-windows-11-search-with-these-five-essentials/"><u>Boost Your Windows 11 Search with These Five Essentials</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-not-working-errors-for-your-pcs-win-based-software/"><u>Bypassing 'Not Working' Errors for Your PC’s Win-Based Software</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-or-see-text-messages-what-can-you-do-with-life360-on-oneplus-11-5g-drfone-by-drfone-virtual-android/"><u>Can Life360 Track Or See Text Messages? What Can You Do with Life360 On OnePlus 11 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/clandestine-data-storage-zip-archives-in-image-files-for-windows-enthusiasts/"><u>Clandestine Data Storage: ZIP Archives in Image Files for Windows Enthusiasts</u></a></li>
<li><a href="https://windows11.techidaily.com/clean-slate-optimizing-windowed-file-space/"><u>Clean Slate: Optimizing Windowed File Space</u></a></li>
<li><a href="https://windows11.techidaily.com/conjoining-android-and-windows-11-tablets-effortlessly/"><u>Conjoining Android and Windows 11 Tablets Effortlessly</u></a></li>
<li><a href="https://windows11.techidaily.com/conveniently-embedding-passwords-into-windows-text-archives/"><u>Conveniently Embedding Passwords Into Windows Text Archives</u></a></li>
<li><a href="https://windows11.techidaily.com/covert-communication-techniques-secure-file-exchanges-on-windows/"><u>Covert Communication Techniques: Secure File Exchanges on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-classic-visuals-a-guide-to-shader-magic-in-retroarc/"><u>Crafting Classic Visuals: A Guide to Shader Magic in RetroArc</u></a></li>
<li><a href="https://fox-info.techidaily.com/creative-clips-excellent-tools-for-photoshopping-with-frames-for-2024/"><u>Creative Clips  Excellent Tools for Photoshopping with Frames for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/cross-network-stealth-securing-data-flow-in-winos/"><u>Cross-Network Stealth: Securing Data Flow in WinOS</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-the-oculus-quest-for-windows-vr-use/"><u>Customizing the Oculus Quest for Windows VR Use</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-sound-misstep-solving-xc00d36b4-on-windows/"><u>Decoding Sound Misstep: Solving XC00D36B4 on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-windows-audio-graph-isolation/"><u>Decoding Windows Audio Graph Isolation</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-diablos-first-encounter-mechanics/"><u>Demystifying Diablo's First Encounter Mechanics</u></a></li>
<li><a href="https://win-howtos.techidaily.com/destiny-2-launch-issue-how-to-fix-the-initializing-hang-up/"><u>Destiny 2 Launch Issue: How to Fix the 'Initializing' Hang-Up</u></a></li>
<li><a href="https://windows11.techidaily.com/dial-up-the-velocity-fixing-your-stuttery-pc/"><u>Dial Up the Velocity: Fixing Your Stuttery PC</u></a></li>
<li><a href="https://windows11.techidaily.com/direct-methods-to-remove-a-peevous-print-spooler/"><u>Direct Methods to Remove a Peevous Print Spooler</u></a></li>
<li><a href="https://technical-tips.techidaily.com/discover-the-timeline-pioneering-milestones-in-electric-vehicle-development/"><u>Discover the Timeline: Pioneering Milestones in Electric Vehicle Development</u></a></li>
<li><a href="https://windows11.techidaily.com/dism-tactics-restoring-windows-11-os-images/"><u>DISM Tactics: Restoring Windows 11 OS Images</u></a></li>
<li><a href="https://windows11.techidaily.com/dive-into-game-worlds-playing-android-apps-in-windows-11-via-google-services/"><u>Dive Into Game Worlds: Playing Android Apps in Windows 11 via Google Services</u></a></li>
<li><a href="https://hardware-help.techidaily.com/enhance-print-quality-with-the-latest-hp-laserjet-p1007-driver-software-free-access/"><u>Enhance Print Quality with the Latest HP LaserJet P1^007 Driver Software - Free Access</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/expert-insights-in-depth-testing-and-review-of-the-linksys-wrt1900acs-for-wi-fi-enthusiasts/"><u>Expert Insights: In-Depth Testing and Review of the Linksys WRT1900ACS for Wi-Fi Enthusiasts</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722959258743-fix-hp-envy-7640-driver-issues-easily/"><u>Fix HP ENVY 7640 Driver Issues. Easily!</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ity-unleashed-top-7-amusing-youtube-channel-skits-for-2024/"><u>Hilarity Unleashed  Top 7 Amusing YouTube Channel Skits for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-can-i-get-more-stardust-in-pokemon-go-on-xiaomi-redmi-note-12r-drfone-by-drfone-virtual-android/"><u>How can I get more stardust in pokemon go On Xiaomi Redmi Note 12R? | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-teleport-your-gps-location-on-apple-iphone-14-pro-drfone-by-drfone-virtual-ios/"><u>How To Teleport Your GPS Location On Apple iPhone 14 Pro? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-vivo-t2-5g-phone-without-password-by-drfone-android/"><u>How To Unlock Vivo T2 5G Phone Without Password?</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-discover-the-top-reaction-video-creators-of-the-year/"><u>In 2024, Discover the Top Reaction Video Creators of the Year</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-oneplus-nord-ce-3-lite-5g-to-mac-drfone-by-drfone-android/"><u>In 2024, How to Mirror OnePlus Nord CE 3 Lite 5G to Mac? | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-use-pokemon-emerald-master-ball-cheat-on-nubia-z50-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, How to Use Pokémon Emerald Master Ball Cheat On Nubia Z50 Ultra | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/source-verification-in-ai-conversation-models/"><u>Source Verification in AI Conversation Models</u></a></li>
<li><a href="https://fox-helps.techidaily.com/transform-your-virtual-meetings-using-zoom-within-the-gmail-platform/"><u>Transform Your Virtual Meetings  Using Zoom Within the Gmail Platform</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-ultimate-wav-to-mp3-conversion-tool-speedy-flawless-converting/"><u>Updated In 2024, Ultimate WAV to MP3 Conversion Tool Speedy, Flawless Converting</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-when-vivo-v30-pro-has-black-screen-of-death-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do When Vivo V30 Pro Has Black Screen of Death? | Dr.fone</u></a></li>
</ul></div>
