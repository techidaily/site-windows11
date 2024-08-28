---
title: Tailoring Windows To Unlock After Hours
date: 2024-08-27T16:01:03.841Z
updated: 2024-08-28T16:01:03.841Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tailoring Windows To Unlock After Hours
excerpt: This Article Describes Tailoring Windows To Unlock After Hours
keywords: Home Security Access,After-Hours Login,Night Window Entry,Evening Alarm System,Auto Lock Windows,Secure Home Windows,Unlock Windows AFK (After Hours Key)
thumbnail: https://thmb.techidaily.com/cd3d2360a2d4ccd17e303566ba964ef54de4b2742b9a5d3bf951667fe61ff2f5.jpg
---

## Tailoring Windows To Unlock After Hours

 PC security is not just about having antivirus software on your computer. You should also restrict access to your documents on your PC while you're away from your machine.

 Read on to explore how you can automatically lock your PC after a set time, even when you leave it unattended.

## How to Keep Your Windows PC Inaccessible While Your Gone

 There are lots of places you could use a PC or laptop. It could be in the office, at a conference venue, or on the go at your favorite café. And there'll be times you just need to get up to attend to something pressing.

 Fortunately, you can set your PC to lock automatically after a custom amount of time without activity. This means you can safely leave your work desk, knowing your work is safe from prying eyes.

 Of course, you can also lock your PC manually when you walk away from it—just press the**Win + L** keys together or**Ctrl + Alt + Del** and then sign out. But you could miss doing that in a rush, or if you're distracted.

 Instead, check out these methods to configure your Windows PC to lock automatically when there is no activity after a specific amount of time.

## 1\. How to Lock Your Windows PC After a Set Time via the Local Security Policy

 Using the Local Security Policy, you can set the exact time in seconds after which your PC will lock itself automatically. Make sure you're signed in as an administrator to automatically lock your PC.

 Local Security Policy is only available in the Windows 10 and 11 Pro, Education, and Enterprise editions. If you're using the Home version, skip to method two.

1. Type**Local Security Policy** in Windows Search. Click the**Local Security Policy** under**Best match** to open it. Alternatively, press the**Win + R** keys together to open the**Run** box. Type**secpol.msc** in the**Open** navigation bar and click**OK** or hit**Enter** to launch it.  
![Open Local Security Policy via Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/open-local-security-policy-via-run.jpg)
2. Click the down arrow next to**Local Policies** in the left pane to expand it.
3. Click on**Security Options** to open it.
4. The Security Options will open up in the right pane. Now scroll down to the policy named**Interactive logon: Machine inactivity limit** and double-click on it to open its properties.  
![Machine Inactivity Limit Selected in Security Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/select-machine-inactivity-limit-in-security-options.jpg)
5. Under the section**Machine will be locked after** , enter the time in seconds after which you want your PC to get locked automatically. This time is the time of machine inactivity or the time when your PC is idle. You can enter the time between**0** to**599940** seconds. For this tutorial, we'll enter**300 seconds** which is five minutes. Now click on**Apply** and then**OK** .
6. Finally, close the Local Security Policy window and restart your computer for the change to take effect.

 Now, when you use your PC, you will experience that your PC will lock itself after your custom timer expires. And if someone tries to unlock your PC while you're gone, it'll ask them for your password, which should keep them at bay until you get back.

 If you ever want to reverse this action and not have your PC lock automatically, just open the**Interactive logon: Machine inactivity limit** policy in**Local Security Policy** . Then just change the time or seconds to**0** —this is the default setting and will not lock your PC automatically.

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. How to Lock Your Windows PC After a Specific Amount of Inactivity via the Registry Editor

 You can tweak settings in the Registry Editor to configure your PC to lock automatically after a set time. And you can do this in Windows Home and all the other Windows editions.

 However, you must be careful while making changes in the registry and should only make the changes as detailed below and not change anything else. It'd be a good idea to create a restore point in Windows before you change your registry settings. If something goes wrong, you can revert your PC to its last working state.

 Now let's go ahead and explore how to lock your PC automatically via the Registry Editor.

1. Type**Registry Editor** in**Windows Search** and select**Registry Editor** under**Best match** . Or use one of the many[ways to open the Registry Editor in Windows 11](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Click on**Yes** on the UAC prompt.
3. In the left pane, use the following path to reach the**System** registry key: **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System**  
![Navigate to System Key in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/navigate-to-system-key-in-registry-editor.jpg)
4. Click on the**System** key in the left pane and its components will open up in the right pane. Now scroll down to get to the**InactivityTimeoutSecs** DWORD.  
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Scroll to InactivityTimeoutSecs in System Key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/scroll-to-inactivitytimeoutsecs.jpg)
5. Double-click on the**InactivityTimeoutSecs** DWORD to modify its value. Select**Decimal** under**Base** , and under**Value data** , enter a number between**0** to**599940** —this is the time in seconds after which your PC will get locked automatically. Like in the Local Security Policy method, we'll give it a time of**300 seconds** or five minutes. Now tap on**OK** .
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
6. In case you do not find the**InactivityTimeoutSecs** DWORD in your registry, you can create it. Right-click on the**System** key folder in the left pane or right-click on a space in the right pane of the**System** key. Select**New** , then select**DWORD (32-bit) Value** .  
![Create InactivityTimeoutSecs DWORD in System Key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/create-inactivitytimeoutsecs-dword.jpg)  
 A new value will be created in the right pane. Name it**InactivityTimeoutSecs** . Then press**Enter** .
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
7. Now double-click on**InactivityTimeoutSecs** DWORD, and enter the time after which you want your PC to get locked.
8. Finally, close the Registry Editor and restart your PC to apply the changes.

 Now your PC will get locked if you're not using it or are away from it after the time you have set in the Registry Editor. If you're on a Windows 11 machine, you can also[explore a few other ways to lock your PC](https://www.makeuseof.com/windows-11-ways-to-lock/) .

 To stop your PC from getting locked automatically, modify the**InactivityTimeoutSecs** DWORD value in the Registry Editor by changing the time to**0** seconds.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Work Worry-Free on Your Windows PC With a Custom Time-Out Lock

 Now never be tense about someone getting access to your PC or your work getting stolen while you're away from your PC. Use one of the above methods to automatically lock your PC after a set time.

 You can also explore how to set up Dynamic Lock using your phone to automatically lock your PC when you move away from it.


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
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-leading-5-high-quality-webcams-with-audio-support/"><u>[New] 2024 Approved  Leading 5 High-Quality Webcams with Audio Support</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/est-live-stream-screen-recorders-for-youtube-for-2024/"><u>[New] Best Live Stream Screen Recorders for YouTube for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-exploring-the-lowest-rates-on-cloud-services-2024-edition/"><u>[New] Exploring the Lowest Rates on Cloud Services, 2024 Edition</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-alternate-avenues-10-great-games-like-gta-v/"><u>[New] In 2024, Alternate Avenues  10 Great Games Like GTA V</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-in-2024-choreographing-compelling-cinematic-hooks/"><u>[New] In 2024, Choreographing Compelling Cinematic Hooks</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-5-tips-to-get-more-views-with-youtube-optimization/"><u>[Updated] 5 Tips to Get More Views with YouTube Optimization</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-tips-for-including-vimeo-content-on-instagram/"><u>[Updated] In 2024, Tips for Including Vimeo Content on Instagram</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-innovative-approaches-to-saving-your-instagram-highlights/"><u>[Updated] Innovative Approaches to Saving Your Instagram Highlights</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-mastering-ig-videos-for-marketing-blueprint-for-victory-for-2024/"><u>[Updated] Mastering IG Videos for Marketing  Blueprint for Victory for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-top-8-metaverse-headsets-and-glasses-to-dive-into-metaverse-for-2024/"><u>[Updated] Top 8 Metaverse Headsets and Glasses to Dive Into Metaverse for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-crafting-visual-brilliance-mastering-luts-in-ae/"><u>2024 Approved  Crafting Visual Brilliance  Mastering LUTs in AE</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-guide-to-correcting-and-confirming-your-age-information-on-tiktok/"><u>2024 Approved  Guide to Correcting & Confirming Your Age Information on TikTok</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-samsungs-visionary-leap-the-ubd-k850-ultrablade-2023/"><u>2024 Approved  Samsung’s Visionary Leap - The UBD K850 UltraBlade 2023</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-transform-your-movies-tips-for-amazing-slow-motion-on-android-phones/"><u>2024 Approved  Transform Your Movies  Tips for Amazing Slow Motion on Android Phones</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/auroras-hdv-does-it-elevate-your-home-cinema-for-2024/"><u>Aurora's HDV  Does It Elevate Your Home Cinema for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/effortless-installation-get-your-latest-amd-ati-radeon-hd-graphics-card-drivers-installed-today/"><u>Effortless Installation: Get Your Latest AMD ATI Radeon HD Graphics Card Drivers Installed Today</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/ever-changing-era-of-ai-video-translation-a-reality-to-be-fulfilled/"><u>Ever-Changing Era of AI Video Translation A Reality to Be Fulfilled</u></a></li>
<li><a href="https://windows11.techidaily.com/executing-an-instant-in-place-windows-11-boost/"><u>Executing an Instant, In-Place Windows 11 Boost</u></a></li>
<li><a href="https://facebook.techidaily.com/facebooks-momentum-stalled-by-5-infamous-incidents/"><u>Facebook’s Momentum Stalled by 5 Infamous Incidents</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-your-mouses-dizzy-spins-in-windows/"><u>Fixing Your Mouse's Dizzy Spins in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-for-controlling-visual-cues-in-windows-11-search/"><u>Guide for Controlling Visual Cues in Windows 11 Search</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-combat-fall-guys-gameplay-interruptions-on-windows-devices/"><u>How To Combat Fall Guys Gameplay Interruptions on Windows Devices</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-15-pro-max-without-losing-any-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone 15 Pro Max without Losing Any Data? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-disabled-lock-screen-pause-timer/"><u>How to Fix Disabled Lock Screen Pause Timer</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-unresponsive-keys-on-your-microsoft-windows-computer-versions-11-7-and-8/"><u>How to Fix Unresponsive Keys on Your Microsoft Windows Computer (Versions 11, 7 & 8)</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-resolve-blue-screens-resulting-from-unhandled-exceptions/"><u>How to Resolve Blue Screens Resulting From Unhandled Exceptions</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-8-best-apps-for-screen-mirroring-honor-x8b-pc-drfone-by-drfone-android/"><u>In 2024, 8 Best Apps for Screen Mirroring Honor X8b PC | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-catchemall-celebrate-national-pokemon-day-with-virtual-location-on-infinix-smart-8-hd-drfone-by-drfone-virtual-android/"><u>In 2024, CatchEmAll Celebrate National Pokémon Day with Virtual Location On Infinix Smart 8 HD | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-tecno-spark-10c-to-iphone-xs11-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Tecno Spark 10C to iPhone XS/11 | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-twitterscape-in-focus-your-route-to-watching-hd-videos/"><u>In 2024, Twitterscape in Focus  Your Route to Watching HD Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/initiating-playback-with-windows-media-player-guide/"><u>Initiating Playback with Windows Media Player Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/launching-startup-repair-in-windows-a-guide/"><u>Launching Startup Repair in Windows: A Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-mishaps-conquering-11-windows-11-glitches/"><u>Mastery Over Mishaps: Conquering 11 Windows 11 Glitches</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-for-correcting-roblox-windows-problems/"><u>Methods for Correcting Roblox Windows Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/modifying-metadata-in-windows-files-timestamp-tweaks-guide/"><u>Modifying Metadata in Windows Files: Timestamp Tweaks Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-to-sound-mastery-with-windows-11-volume-control/"><u>Navigate to Sound Mastery with Windows 11 Volume Control</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-past-s-mode-a-windows-users-roadmap/"><u>Navigating Past 'S Mode': A Windows User's Roadmap</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-game-launch-issues-for-epic/"><u>Navigating Windows Game Launch Issues for Epic</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-error-0x80070194-on-windows-onedrive/"><u>Overcoming Error 0X80070194 on Windows' OneDrive</u></a></li>
<li><a href="https://windows11.techidaily.com/power-up-your-command-line-discover-the-top-20-cmd-commands/"><u>Power Up Your Command Line: Discover the Top 20 CMD Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/recovering-internet-router-settings-on-windows-pc/"><u>Recovering Internet Router Settings on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/refining-malfunctional-fixes-within-windows-1011-diagnostics/"><u>Refining Malfunctional Fixes Within Windows 10/11 Diagnostics</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-steam-cloud-connectivity-issues/"><u>Resolving Steam Cloud Connectivity Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/restarting-method-for-a-non-functional-windows-11-wi-fi-connection/"><u>Restarting Method for a Non-Functional Windows 11 Wi-Fi Connection</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-telnet-activation-in-latest-windows-versions/"><u>Simplifying Telnet Activation in Latest Windows Versions</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-video-lags-in-chromes-youtube-viewing/"><u>Solving Video Lags in Chrome's YouTube Viewing</u></a></li>
<li><a href="https://windows11.techidaily.com/startup-guide-for-windows-11s-immediate-help-tool/"><u>Startup Guide for Windows 11'S Immediate Help Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/stealthy-system-settings-hiding-windows-11-power-command/"><u>Stealthy System Settings: Hiding Windows 11 Power Command</u></a></li>
<li><a href="https://windows11.techidaily.com/stepwise-approach-enabling-wordpad-in-windows/"><u>Stepwise Approach: Enabling WordPad in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-avoid-perpetual-network-logon-errors/"><u>Strategies to Avoid Perpetual Network Logon Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/tech-tip-accessing-windows-11-sticky-notes-easily/"><u>Tech Tip: Accessing Windows 11 Sticky Notes Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-govern-devices-on-slumbering-pcs/"><u>Techniques to Govern Devices on Slumbering PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/the-future-is-here-windows-11-changes-to-file-explorer/"><u>The Future Is Here: Windows 11 Changes to File Explorer</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-music-from-poco-m6-pro-5g-by-fonelab-android-recover-music/"><u>The way to get back lost music from Poco M6 Pro 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-seamless-slideshow-creation-and-image-spot-repair-in-win11-photos/"><u>Tips for Seamless Slideshow Creation and Image Spot Repair in Win11 Photos</u></a></li>
<li><a href="https://some-tips.techidaily.com/transforming-photos-with-easy-online-cropping-steps-for-2024/"><u>Transforming Photos with Easy Online Cropping Steps for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/turn-on-copy-and-paste-within-edges-protected-area-win-11-edition/"><u>Turn On Copy & Paste Within Edge's Protected Area, Win 11 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-altering-win-11-proxy-settings/"><u>Understanding and Altering Win 11 Proxy Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-potential-top-winning-apps-from-ms-store-2023/"><u>Unleash Potential: Top Winning Apps From MS Store, 2023</u></a></li>
<li><a href="https://win-answers.techidaily.com/unlock-the-solution-removing-you-dont-have-access-to-play-fortnite-barrier/"><u>Unlock the Solution: Removing 'You Don't Have Access to Play Fortnite' Barrier</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-power-of-openais-whisper-on-your-windows-pc/"><u>Unveiling the Power of OpenAI's Whisper on Your Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/why-choose-linux-without-windows-subsystem/"><u>Why Choose Linux without Windows Subsystem?</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-expertise-required-for-successfully-repairing-directdraw-faults/"><u>Win11: Expertise Required for Successfully Repairing DirectDraw Faults</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-triple-widget-setup-made-simple/"><u>Windows 11'S Triple Widget Setup Made Simple</u></a></li>
</ul></div>
