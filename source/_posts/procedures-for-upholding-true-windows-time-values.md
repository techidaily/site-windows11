---
title: Procedures for Upholding True Windows Time Values
date: 2024-08-15T15:43:48.058Z
updated: 2024-08-16T15:43:48.058Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Procedures for Upholding True Windows Time Values
excerpt: This Article Describes Procedures for Upholding True Windows Time Values
keywords: WindowTimeSync,TrueTimeUptime,RealWindowsTiming,VerifiedTimeWindows,AccurateWIndowsClock,TruthfulWindowsDateTime,ValidatedWindowsTimeSync
thumbnail: https://thmb.techidaily.com/a0961ee471b397828689bb0499e11bd310468db6e686996103528a8e584f7f95.jpg
---

## Procedures for Upholding True Windows Time Values

 You’re using your Windows device and notice something strange in the date and time settings. Someone has changed the settings without your knowledge or permission. This makes it difficult to stay on schedule with tasks and activities. In this guide, we’ll show how to stop anonymous users from changing date and time settings on Windows computers.

## How To Prevent Users From Changing the Date and Time on Windows

 There are two ways to prevent users from changing Windows date and time. The first is to use Group Policy Editor, a system administration tool designed to control computer behavior in an organization. While the second way is to use Registry Editor, which allows you to modify Windows registry settings.

 For both methods, you need administrative access to the computer to change it. Once you’ve made the changes, nobody can alter the date and time settings. Let’s look at each method in more detail.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
<!-- affiliate ads end -->
## 1\. Use the Group Policy Editor

 If your computer is part of an organization and users often change the date and time, use Group Policy Editor to stop it. This will prevent those with limited access to the computer from altering the date and time. However, this method only works for Windows Pro, Enterprise, or Education Editions.

 So, if you have Windows Home Edition, this won’t work. In that case, you must first [activate the Group Policy Editor for Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). If it seems complicated, skip it and try the next solution instead.

 Follow these steps to prevent users from changing the date and time:

1. Press **Win + R** on your keyboard to open the Run window.
2. Type **gpedit.msc** in the text box and press Enter. This will open the Group Policy Editor window.
3. On the left side of the window, navigate to the following path:  
Computer Configuration > Administrative Templates > System > Locale Services
4. In the right-side pane, double-click on **Disallow user override of locale settings**.  
![Disallow user override of locale settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/disallow-user-override-of-locale-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. In the pop-up window, check the **Enabled** radio button.
6. Then click **Apply** \> **OK** to save the changes.

 This will block anyone from changing the date and time settings on your computer. However, if you have administrative access to the computer, you can still alter the settings.

 If you want to revert to the default settings later, open Group Policy Editor again and change the value of Disallow user override of locale settings back to Not Configured or Disabled. This way, users can change the time and date again.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->
## 2\. Tweak the Registry Editor

 If you’re using Windows Home Edition or have disabled the Group Policy Editor, use the Registry Editor to protect date and time settings. This method is more advanced and has a higher risk of system damage.

 In that case, [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it. Doing so will restore settings if something goes wrong.

 Follow these steps to stop users from changing the time and date via the registry:

1. [Open the Run command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **regedit** in the field and press Enter. This will [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. In the Registry Editor window, navigate to the following path:  
HKEY_CURRENT_USER\Software\Policies\Microsoft\Control Panel\International\
4. If the International folder doesn’t exist, create one. To do that, right-click on Control Panel and select **New** \> **Key**. Name it **International**.
5. Then right-click on **International** and select New > DWORD (32-bit) Value.
6. Name the newly created value **PreventUserOverrides**.
7. Double-click on the **PreventUserOverrides** DWORD value.  
![Use Registry Editor to Prevent Users From Chaning date and time settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/use-registry-editor-to-prevent-users-from-chaning-date-and-time-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. In the pop-up window, change the Value data to **1** and click **OK**.

 Once you’ve made the changes, close the Registry Editor window and restart your computer.

 To undo this restriction, delete the **PreventUserOverrides** DWORD value from the registry or change the value to **0**. Doing so will enable users to change the time and date again.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698827&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3REpage-newmainscreenshot.png" border="0">DEX 3 RE is Easy-To-Use DJ Mixing Software for MAC and Windows Designed for Today's Versatile DJ. 

 Mix from your own library of music, iTunes or use the Pulselocker subsciprtion service for in-app access to over 44 million songs. Use with over 85 supported DJ controllers or mix with a keyboard and mouse.  

 DEX 3 RE is everything you need without the clutter - the perfect 2-deck mixing software solution for mobile DJs or hard-core hobbiests.  
 PCDJ DEX 3 RE (DJ Software for Win & MAC - Product Activation For 3 Machines)</a>
<!-- affiliate ads end -->
## Stop Windows Time and Date Changes

 Now stop unauthorized users from changing the date and time settings on your Windows computer. This keeps your tasks and activities on track. If necessary, you can always undo this restriction.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-information.techidaily.com/new-birds-bamboo-boogie/"><u>[New] Birds Bamboo Boogie</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-high-quality-hearables-leading-podcasters-on-googloud/"><u>[New] High-Quality Hearables  Leading Podcasters on GooGloud</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-the-top-10-frugal-video-communication-platforms-catering-to-corporate-and-educational-needs/"><u>[New] In 2024, The Top 10 Frugal Video Communication Platforms Catering to Corporate & Educational Needs</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-pro-stream-wars-choosing-between-vmix-and-wirecast/"><u>[New] Pro-Stream Wars  Choosing Between VMix and Wirecast</u></a></li>
<li><a href="https://article-files.techidaily.com/new-visionary-writing-spanning-eight-cinematic-divisions-for-2024/"><u>[New] Visionary Writing Spanning Eight Cinematic Divisions for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-bridge-the-gap-youtube-tweet-functionality/"><u>[Updated] Bridge the Gap  YouTube Tweet Functionality</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-how-to-remove-stickers-from-a-tiktok-video/"><u>[Updated] How To Remove Stickers From A Tiktok Video</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-capturing-every-aspect-of-minecraft-play/"><u>[Updated] In 2024, Capturing Every Aspect of Minecraft Play</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-meme-march-unstoppable-videos-hit-the-tweetsphere/"><u>[Updated] Meme March  Unstoppable Videos Hit the Tweetsphere</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-navigate-the-art-of-snapchat-filters-for-beginners-for-2024/"><u>[Updated] Navigate the Art of Snapchat Filters for Beginners for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/5-essential-tweaks-for-your-windows-11-search-settings/"><u>5 Essential Tweaks for Your Windows 11 Search Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/6-common-windows-screen-resolution-issues-and-fixes/"><u>6 Common Windows Screen Resolution Issues and Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/7-essential-fixes-to-tackle-the-http-too-many-requests-issue-in-windows/"><u>7 Essential Fixes to Tackle the HTTP Too Many Requests Issue in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/a-different-view-unique-changes-to-windows-11s-file-explorer/"><u>A Different View: Unique Changes to Windows 11'S File Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerate-profit-with-windows-11-pro-capture-best-offers/"><u>Accelerate Profit with Windows 11 Pro: Capture Best Offers</u></a></li>
<li><a href="https://windows11.techidaily.com/accessing-and-running-verifier-manager-in-windows-11/"><u>Accessing and Running Verifier Manager in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-rgb-customization-in-win11/"><u>Activating RGB Customization in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-gaps-in-time-remaining-estimates-of-windows-11-laptops/"><u>Addressing Gaps in Time Remaining Estimates of Windows 11 Laptops</u></a></li>
<li><a href="https://windows11.techidaily.com/amplify-tray-ui-add-scrolllock-and-number-keys-iconos/"><u>Amplify Tray UI: Add ScrollLock and Number Keys Iconos</u></a></li>
<li><a href="https://windows11.techidaily.com/amplify-your-pcs-wi-fi-with-8-effective-fixes-for-windows-11/"><u>Amplify Your PC's Wi-Fi with 8 Effective Fixes for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/asus-vivobook-s-15-the-ultimate-blend-of-style-and-functionality/"><u>ASUS Vivobook S 15: The Ultimate Blend of Style & Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/audible-overdrive-best-5-programs-for-higher-than-100-pc-audio/"><u>Audible Overdrive: Best 5 Programs for Higher-Than-100%% PC Audio</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-disruption-correcting-photo-package-issues-on-windows-1011/"><u>Avoiding Disruption: Correcting Photo Package Issues on Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/beginners-tutorial-on-windows-canary-usage/"><u>Beginner’s Tutorial on Windows Canary Usage</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-retrieve-lost-contacts-from-oppo-reno-10-5g-by-fonelab-android-recover-contacts/"><u>Best Android Data Recovery - Retrieve Lost Contacts from Oppo Reno 10 5G.</u></a></li>
<li><a href="https://windows11.techidaily.com/best-budget-single-board-windows-systems/"><u>Best Budget Single-Board Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/bold-stealth-for-your-wi-fi-on-windows-pcs/"><u>Bold Stealth for Your Wi-Fi on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/bootable-windows-11-flashdrive-top-3-efficient-techniques/"><u>Bootable Windows 11 Flashdrive: Top 3 Efficient Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/1719351366052-breathe-new-life-into-your-win11-printer-with-these-tips/"><u>Breathe New Life Into Your Win11 Printer with These Tips!</u></a></li>
<li><a href="https://windows11.techidaily.com/bridging-the-gap-reconnecting-legrl-after-drops/"><u>Bridging the Gap: Reconnecting LeGRL After Drops</u></a></li>
<li><a href="https://windows11.techidaily.com/building-your-signature-input-scheme-on-win11/"><u>Building Your Signature Input Scheme on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-the-add-folder-now-obstacle-in-windows-onedrive-for-a-smooth-experience/"><u>Bypassing the 'Add Folder Now' Obstacle in Windows OneDrive for a Smooth Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-1011-bluetooth-connect-failure/"><u>Bypassing Windows 10/11 Bluetooth Connect Failure</u></a></li>
<li><a href="https://windows11.techidaily.com/circumventing-error-code-0x800736cc-in-windows-update/"><u>Circumventing Error Code 0X800736CC in Windows Update</u></a></li>
<li><a href="https://windows11.techidaily.com/clear-path-to-app-removal-tackling-do-not-have-access-errors/"><u>Clear Path to App Removal: Tackling Do Not Have Access Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/confronting-error-code-0x8007045d-a-guide-for-windows-11-users/"><u>Confronting Error Code 0X8007045d: A Guide for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-microsofts-window-file-format-cab-for-ease-of-use/"><u>Deciphering Microsoft's Window File Format (CAB) for Ease of Use</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-significance-of-windows-subsystem-for-linux-error-4294967295/"><u>Deciphering the Significance of Windows Subsystem for Linux Error 4294967295</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-dism-a-practical-guide-to-fixing-win11-os/"><u>Decoding Dism: A Practical Guide to Fixing Win11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-blue-screen-errors-through-microsofts-tools-in-w11/"><u>Demystifying Blue Screen Errors Through Microsoft's Tools in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/detecting-7-critical-windows-steps-for-cyber-threats/"><u>Detecting 7 Critical Windows Steps for Cyber Threats</u></a></li>
<li><a href="https://windows11.techidaily.com/diminishing-drain-techniques-to-limit-vanguards-user-mode-cpu-use/"><u>Diminishing Drain: Techniques to Limit Vanguard's User-Mode CPU Use</u></a></li>
<li><a href="https://windows11.techidaily.com/1719266225421-eradicate-black-screen-on-win11-top-easy-fixes/"><u>Eradicate Black Screen on Win11: Top Easy Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/1719228177134-functions-not-working-on-win10-heres-what-to-do/"><u>Functions Not Working on Win10? Here's What to Do!</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-the-latest-amd-radeon-drivers-for-your-windows-pc/"><u>Get the Latest AMD Radeon Drivers for Your Windows PC</u></a></li>
<li><a href="https://change-location.techidaily.com/how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-samsung-galaxy-xcover-6-pro-tactical-edition-drfone-by-drfone-virtual-android/"><u>How PGSharp Save You from Ban While Spoofing Pokemon Go On Samsung Galaxy XCover 6 Pro Tactical Edition? | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-unbrick-a-dead-lava-storm-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Unbrick a Dead Lava Storm 5G | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-infinix-gt-10-pro-drfone-by-drfone-virtual-android/"><u>In 2024, 15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Infinix GT 10 Pro | Dr.fone</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-expanding-your-audience-stream-successfully-across-30plus-outlets/"><u>In 2024, Expanding Your Audience  Stream Successfully Across 30+ Outlets</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-from-individualist-to-institutional-influence-in-the-youtube-universe/"><u>In 2024, From Individualist to Institutional Influence in the YouTube Universe</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-your-oppo-a1x-5g-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>In 2024, How to Mirror Your Oppo A1x 5G Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-fake-gps-location-spoofer-a-good-choice-on-vivo-g2-drfone-by-drfone-virtual-android/"><u>In 2024, Is Fake GPS Location Spoofer a Good Choice On Vivo G2? | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-premium-selection-of-free-4k-software-for-windows-plus-os-x/"><u>In 2024, Premium Selection of Free 4K Software for Windows + OS X</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-streamline-your-playback-secrets-of-gameye/"><u>In 2024, Streamline Your Playback  Secrets of GamEye</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-the-art-of-sound-visualization-combining-waveform-graphics-and-animation-techniques-in-premiere-pro/"><u>In 2024, The Art of Sound Visualization Combining Waveform Graphics & Animation Techniques in Premiere Pro</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-unlocking-apple-iphone-11-lock-screen-3-foolproof-methods-that-actually-work-by-drfone-ios/"><u>In 2024, Unlocking Apple iPhone 11 Lock Screen 3 Foolproof Methods that Actually Work</u></a></li>
<li><a href="https://tech-hub.techidaily.com/navigating-the-pitfalls-of-bingchatgpts-cryptocurrency-cons-and-how-to-spot-them/"><u>Navigating the Pitfalls of BingChatGPT's Cryptocurrency Cons and How to Spot Them</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-from-cluttered-to-clean-learn-how-to-crop-unwanted-parts-of-your-video-with-avidemux-for-2024/"><u>New From Cluttered to Clean Learn How to Crop Unwanted Parts of Your Video with Avidemux for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/reducing-motion-illusion-in-vr-environments/"><u>Reducing Motion Illusion in VR Environments</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/revolutionizing-3d-printing-an-in-depth-look-at-bambu-labs-top-model-the-x1-carbon/"><u>Revolutionizing 3D Printing - An In-Depth Look at Bambu Lab's Top Model, The X1-Carbon</u></a></li>
<li><a href="https://extra-support.techidaily.com/selecting-the-best-equipment-for-expeditions-for-2024/"><u>Selecting the Best Equipment for Expeditions for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/streamline-your-audio-preferences-moving-spotify-playlists-to-youtube-music/"><u>Streamline Your Audio Preferences  Moving Spotify Playlists to YouTube Music</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unreal-development-hangs-on-d3d-device-lifespan/"><u>Unreal Development Hangs on D3D Device Lifespan</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ways-to-trade-pokemon-go-from-far-away-on-sony-xperia-5-v-drfone-by-drfone-virtual-android/"><u>Ways to trade pokemon go from far away On Sony Xperia 5 V? | Dr.fone</u></a></li>
</ul></div>
