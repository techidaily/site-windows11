---
title: Unlocking Power Settings for CPU State Insights
date: 2024-08-15T15:43:01.696Z
updated: 2024-08-16T15:43:01.696Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unlocking Power Settings for CPU State Insights
excerpt: This Article Describes Unlocking Power Settings for CPU State Insights
keywords: CPU Performance Tuning,Advanced CPU States,Energy Efficient CPUs,Power Management Techniques,CPU Insight Analysis,Temperature Control Systems,Optimize CPU State
thumbnail: https://thmb.techidaily.com/65fba9a952c6564fd879ce858daef732be8f2531c9874f65aafa43e482841322.jpg
---

## Unlocking Power Settings for CPU State Insights

 Have you ever tried to tweak the minimum and maximum processor states on your Windows PC, only to find them hidden? Or perhaps you want to hide the options to prevent others from tampering with them?

 Whichever you're trying to do, we're here to help by showing you how to add or remove them in the Power Options menu.

## How to Show or Hide the Minimum or Maximum Processor State Using Command Prompt

 To use Command Prompt to show or hide these power states, press**Win + R** to open Windows Run. Then, enter**cmd** in the text box and hit the**Enter** key on your keyboard. You can also use one of the many [ways to open the Command Prompt on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .

![Cmd in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/win11-cmd.jpg)

To show the minimum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR 893dee8e-2bef-41e0-89c6-b55d0929964c -ATTRIB_HIDE`

To hide the minimum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR 893dee8e-2bef-41e0-89c6-b55d0929964c +ATTRIB_HIDE`

To show the maximum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR bc5038f7-23e0-4960-96da-33abaf5935ec -ATTRIB_HIDE`

To hide the maximum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR bc5038f7-23e0-4960-96da-33abaf5935ec +ATTRIB_HIDE`

 After you have typed in the command you want in the CMD window, hit the**Enter** key on your keyboard to run it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->
## How to Show or Hide the Minimum or Maximum Processor State Using the Registry Editor

 You can also show or hide these options using the Registry Editor. However, before you do so, create a restore point as a backup in case you make a mistake and need to return your Windows computer to a previously-working state. Check out [how to create a restore point in Command Prompt](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) for more information.

 After creating the system restore point, press**Win + R** to open the Run dialog box. Then, enter**regedit** in the text box and hit the**Enter** key to open the Registry Editor.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)
<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 On the UAC prompt, click**Yes** to continue.

 To get to the key for the minimum processor state in the Registry editor, copy and paste the following file path into the Registry Editor’s address bar and hit**Enter** :

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\bc5038f7-23e0-4960-96da-33abaf5935ec`

 Right-click the**Attributes** value in the right panel and select**Modify** .

![modifying the attributes value in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-modify-attributes.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->

 Then, set**Value data** to**1** to hide the minimum processor state. To show it, set**Value data** to**2** .

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)
<!-- affiliate ads begin -->
<span id="1997795">
					<video width="250" height="250" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/23621-1997795">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:250px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fproteahair.pxf.io%2Fc%2F5597632%2F1997795%2F23621'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997795/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 For the maximum processor state, enter the below file path in the Registry Editor's address bar to get to its key:

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\893dee8e-2bef-41e0-89c6-b55d0929964c`

 Double-click the**Attributes** entry to modify it, and then change**Value data** to**1** to hide the maximum processor state or**2** to show it.

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Add or Remove the Minimum and Maximum Processor States From Power Options

 Setting the minimum or maximum processor state on your Windows computer is vital to helping you get the performance you want from it. If you can’t see these options in the Power Options menu, you can easily reveal them with either Command Prompt or the Registry Editor. And after you’re done tweaking the states, you can hide them for their protection.


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
<li><a href="https://youtube-web.techidaily.com/024-approved-elevating-income-with-mobile-video-monetization-techniques-for-youtubers/"><u>[New] 2024 Approved  Elevating Income with Mobile Video Monetization Techniques for YouTubers</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-master-the-art-of-easy-webinar-recordings-windows-and-macos-advice/"><u>[New] 2024 Approved  Master the Art of Easy Webinar Recordings  Windows & macOS Advice</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-from-high-speed-to-leisurely-the-pathway-to-stellar-ig-reel-slow-motion-for-2024/"><u>[New] From High-Speed to Leisurely  The Pathway to Stellar IG Reel Slow Motion for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-cutting-edge-iphone-techniques-for-slow-motion/"><u>[Updated] 2024 Approved  Cutting Edge iPhone Techniques for Slow Motion</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-how-to-sing-your-own-song-with-an-iphone-ringtone/"><u>[Updated] How to Sing Your Own Song with an iPhone Ringtone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-blueprint-for-creating-viral-trailers-in-the-world-of-youtube/"><u>[Updated] In 2024, Blueprint for Creating Viral Trailers in the World of YouTube</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-selecting-superior-sound-10-top-mic-recommendations/"><u>[Updated] Selecting Superior Sound  10 Top Mic Recommendations</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-tactics-to-determine-igtv-viewership-success/"><u>[Updated] Tactics to Determine IGTV Viewership Success</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-top-10-games-like-ghost-of-tsushima-you-must-try/"><u>[Updated] Top 10 Games Like Ghost of Tsushima You Must Try</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-top-places-to-find-background-music-for-videos/"><u>[Updated] Top Places to Find Background Music for Videos</u></a></li>
<li><a href="https://blog-min.techidaily.com/2-ways-to-transfer-text-messages-from-itel-a60-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>2 Ways to Transfer Text Messages from Itel A60 to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-best-free-non-intrusive-android-screen-recorders/"><u>2024 Approved  Best Free Non-Intrusive Android Screen Recorders</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-best-online-destinations-for-sparkling-and-metallic-letters/"><u>2024 Approved  Best Online Destinations for Sparkling and Metallic Letters</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-cutting-edge-narratives-on-airwaves/"><u>2024 Approved  Cutting-Edge Narratives on Airwaves</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-diving-deep-into-vidmas-screen-recording-features/"><u>2024 Approved  Diving Deep Into Vidma's Screen Recording Features</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-from-mundane-to-magical-a-guide-to-chromatic-brilliance/"><u>2024 Approved  From Mundane to Magical  A Guide to Chromatic Brilliance</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-in-search-of-excellence-top-10-4k-displays/"><u>2024 Approved  In Search of Excellence  #Top 10 4K Displays</u></a></li>
<li><a href="https://windows11.techidaily.com/5-key-fixes-to-stop-rpc-failures-in-windows/"><u>5 Key Fixes to Stop RPC Failures in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/best-digital-journals-navigate-your-pen-for-windows/"><u>Best Digital Journals: Navigate Your Pen for Windows</u></a></li>
<li><a href="https://tech-haven.techidaily.com/claude-confrontation-wholl-win-at-chatbot-battles/"><u>Claude Confrontation: Who'll Win at ChatBot Battles?</u></a></li>
<li><a href="https://windows11.techidaily.com/defining-windows-corners-straighten-them-out/"><u>Defining Windows' Corners: Straighten Them Out</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-non-response-from-printmanagement-msc-errors/"><u>Eliminating Non-Response From 'Printmanagement' MSC Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/expanding-linux-horizons-through-windows-apps/"><u>Expanding Linux Horizons Through Windows Apps</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/1722900063658-exploring-a-ravaged-world-on-motorcycle-in-days-gone-our-comprehhavis-review/"><u>Exploring a Ravaged World on Motorcycle in 'Days Gone': Our Comprehhavis Review.</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-update-issue-with-error-0x8024800c/"><u>Fixing Windows Update Issue with Error 0X8024800C</u></a></li>
<li><a href="https://windows11.techidaily.com/future-proof-computing-with-top-windows-laptop-choices/"><u>Future-Proof Computing with Top Windows Laptop Choices</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-newest-hp-840-g3-device-drivers-installation-guide/"><u>Get the Newest HP 840 G3 Device Drivers: Installation Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-pathway-merging-emulated-game-titles-with-playnite-software/"><u>Guiding Pathway: Merging Emulated Game Titles with Playnite Software</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-and-where-to-find-a-shiny-stone-pokemon-for-nokia-130-music-drfone-by-drfone-virtual-android/"><u>How and Where to Find a Shiny Stone Pokémon For Nokia 130 Music? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-double-clicking-not-opening-folders-on-windows-1110/"><u>How to Fix Double-Clicking Not Opening Folders on Windows 11/10</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/immersion-in-metaverse-leading-hmds-reviewed/"><u>Immersion in Metaverse  Leading HMDs Reviewed</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-a-quick-guide-to-poco-m6-pro-5g-frp-bypass-instantly-by-drfone-android/"><u>In 2024, A Quick Guide to Poco M6 Pro 5G FRP Bypass Instantly</u></a></li>
<li><a href="https://ai-voice.techidaily.com/in-2024-best-10-free-and-best-text-to-speech-generators/"><u>In 2024, Best 10 Free and Best Text-to-Speech Generators</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-direct-stream-from-fb-to-whatsapp-group-chat/"><u>In 2024, Direct Stream From FB to WhatsApp Group Chat</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-easily-unlock-your-honor-magic-5-pro-device-sim-by-drfone-android/"><u>In 2024, Easily Unlock Your Honor Magic 5 Pro Device SIM</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-use-google-assistant-on-your-lock-screen-of-nubia-red-magic-9-proplus-phone-by-drfone-android/"><u>In 2024, How to Use Google Assistant on Your Lock Screen Of Nubia Red Magic 9 Pro+ Phone</u></a></li>
<li><a href="https://windows11.techidaily.com/key-to-performance-enhancement-with-windows-lav-filters-use/"><u>Key to Performance Enhancement with Window's LAV Filters Use</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-use-of-toolbars-an-insight-into-mspcm-windows-11/"><u>Mastering the Use of Toolbars: An Insight Into MSPCM, Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-user-isolation-for-security-in-win-11/"><u>Mastering User Isolation for Security in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-bypass-enforced-driver-signatures-loading-unverified-drivers/"><u>Methods to Bypass Enforced Driver Signatures, Loading Unverified Drivers</u></a></li>
<li><a href="https://driver-install.techidaily.com/nvidia-hd-sound-drivers-the-modern-windows-guide/"><u>NVIDIA HD Sound Drivers: The Modern Windows Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/peeling-back-the-layers-of-runtime-brokers-on-pcs/"><u>Peeling Back the Layers of Runtime Brokers on PCs</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/-pinching-picks-microphones-under-50/"><u>Penny-Pinching Picks  Microphones Under $50</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-vmwares-non-boot-windows-11-mistakes/"><u>Preventing VMware's Non-Boot Windows 11 Mistakes</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-bypassing-the-components-not-found-issue-on-w10w11/"><u>Quick Fix: Bypassing the Components Not Found Issue on W10/W11</u></a></li>
<li><a href="https://windows11.techidaily.com/re-establish-missing-5ghz-connection-easily-in-windows-11/"><u>Re-Establish Missing 5GHz Connection Easily in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-grayed-out-bin-status-in-win11/"><u>Rectifying Grayed Out Bin Status in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-cutting-back-cpu-overuse-in-windows-systems/"><u>Strategies for Cutting Back CPU Overuse in Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-screen-settings-with-these-10-win-11-tricks/"><u>Streamline Your Screen Settings with These 10 Win 11 Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-to-mask-dimming-functionality-in-system-preferences/"><u>Tactics to Mask Dimming Functionality in System Preferences</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/the-complete-guide-to-recording-flawless-zoom-based-podcasts/"><u>The Complete Guide to Recording Flawless Zoom-Based Podcasts</u></a></li>
<li><a href="https://windows11.techidaily.com/the-premier-lineup-of-zero-cost-must-haves-for-windows-11/"><u>The Premier Lineup of Zero-Cost Must-Haves for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-alomware-resource-for-windows-tweakers/"><u>The Ultimate AlomWare Resource for Windows Tweakers</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-capturing-and-organizing-uac-alert-snaps/"><u>Tips for Capturing and Organizing UAC Alert Snaps</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-the-red-x-on-your-pcs-file-system/"><u>Understanding the Red X on Your PC's File System</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-your-devices-through-windows-live-panels/"><u>Understanding Your Devices Through Windows Live Panels</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-speed-tackling-torrent-stagnation-in-windows/"><u>Unlocking Speed: Tackling Torrent Stagnation in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unmasking-wintoys-your-essential-introduction-to-an-underused-powerhouse-tool-in-windows/"><u>Unmasking WinToys: Your Essential Introduction to an Underused Powerhouse Tool in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-access-denial-in-windows-11-with-these-5-steps/"><u>Unraveling Access Denial in Windows 11 with These 5 Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-cause-of-unregistered-packages-in-windows/"><u>Unraveling the Cause of Unregistered Packages in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/utilizing-portable-gpus-no-internal-graphic-needed/"><u>Utilizing Portable GPUs: No Internal Graphic Needed</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-tips-implementing-scheduled-file-purging/"><u>Win11 Tips: Implementing Scheduled File Purging</u></a></li>
</ul></div>
