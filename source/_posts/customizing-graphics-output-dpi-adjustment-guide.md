---
title: "Customizing Graphics Output: DPI Adjustment Guide"
date: 2024-08-08T06:00:23.897Z
updated: 2024-08-09T06:00:23.897Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Customizing Graphics Output: DPI Adjustment Guide"
excerpt: "This Article Describes Customizing Graphics Output: DPI Adjustment Guide"
keywords: Graphic DPI Tutorial,DPI Customization Steps,Increase Image Quality,High Precision Graphics,Adjusting Screen DPI,Optimize Visual Output,Fine-Tune Graphics Display
thumbnail: https://thmb.techidaily.com/545eb30532b146292d910492a3de0882f942d02de7b5ef10d79d0e3f377f7561.jpg
---

## Customizing Graphics Output: DPI Adjustment Guide

 If you're looking to customize your computer experience, or just make things easier on the eyes, then changing the display DPI scaling on Windows is a great way to do that. In this helpful article, we'll provide you with an easy step-by-step guide for both registry tweaks and Windows settings so that customizing your computer can be done quickly and easily.

 Whether it's due to vision problems or if you simply want more control over how things look onscreen, these solutions are sure to help.

## What Is DPI Scaling on Windows?

 DPI stands for "dots per inch" and it refers to the number of individual dots that can be packed into an inch of space on your screen. The higher the number, the sharper and clearer the display. But here's the thing, sometimes you might want your text and images to be bigger, while at other times, you might want them smaller. That's where DPI scaling comes in; it's your very own personal adjustment tool.

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
## How to Change Display DPI Scaling via Windows Settings

 The Settings app is the simplest and easiest way to change display scaling in Windows 11\. Here's how to do it.

1. Press**Win + I** on your keyboard to open the Settings menu.
2. From the left pane of the window, click the**System** tab.
3. Click**Display** on the right side.
4. Scroll down to the**Scale and layout** section.
5. Next to the**Scale** option, click the dropdown menu and change the scaling.  
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Change DPI Scale in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/change-dpi-scale-in-settings.jpg)
6. Select the one that best fits your needs.

 After you've made your changes, close the window and restart your computer, so the changes take effect.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411"><img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Change Display DPI Scaling Using the Registry Editor

 If the Settings app isn't working, or you don't have access to it, you can change the scaling through the Registry Editor. But keep in mind that it can be a bit tricky, and you should [back up your registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before making any changes.

 To change Display DPI Scaling using Registry Editor, follow these steps:

1. Press**Win + R** on your keyboard to [open the Run command](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**regedit** in the dialog box and hit Enter.
3. If UAC prompts on your screen, click**Yes** to continue.
4. Once you're in the Registry Editor window, navigate to the following path:  
HKEY_CURRENT_USER\Control Panel\Desktop
5. In the right pane, right-click on**LogPixels** and select**Modify** from the context menu.  
 If you don't see the LogPixels DWORD key, you need to manually create it. For this, right-click on the empty space in the right pane and select**New > DWORD (32-bit) Value** . Upon creating the DWORD key, give it the name**LogPixels** and save it. Now click twice on the key you just created, and a pop-up will appear.

1. Choose one of the following Value data fields and set the base to**Decimal** .  
<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Change Display DPI Scaling in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/change-display-dpi-scaling-in-windows.jpg)  
| Value data | DPI scale                  |  
| ---------- | -------------------------- |  
| 96         | Smaller 100% (Recommended) |  
| 120        | Medium 125%                |  
| 144        | Larger 150%                |  
| 192        | Extra Large 200%           |  
| 240        | Custom 250%                |  
| 288        | Custom 300%                |  
| 384        | Custom 400%                |  
| 480        | Custom 500%                |
2. When you're done making these changes, click**OK** to save them.
3. Next, double-click**Win8DpiScaling** in the right pane. If you don't see the Win8DpiScaling DWORD key there, you must create it manually in the same way as you created LogPixels.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
![Change Display DPI Scaling Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/change-display-dpi-scaling-using-registry.jpg)
4. In the pop-up menu, set the Value data to**0** if you set Logpixels to 96, or**1** if you used any other value.
5. Select**Hexadecimal** as the base and click**OK** .

 After performing the above steps, restart your computer to take effect the changes. If you ever need to restore the default settings, just open Registry Editor and go to the same location. Then double-click on Win8DpiScaling and change the Value data to 0.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Scale the Display DPI on Windows

 If you're in search of ways to give your screen a sharper and crisper look, change the DPI scaling! You can customize different elements displayed on your device like text size, icons, and more so that it's easier for you to read and navigate.


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
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-elevate-your-brand-explore-these-10-essential-youtube-creators/"><u>[New] In 2024, Elevate Your Brand  Explore These 10 Essential YouTube Creators</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-unlinking-from-youtube-shorts-the-complete-process/"><u>[New] Unlinking From YouTube Shorts - The Complete Process</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-achieve-financial-success-with-youtube-ad-profit-techniques/"><u>[Updated] 2024 Approved  Achieve Financial Success with YouTube Ad Profit Techniques</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-elite-10-survival-skirmishes/"><u>[Updated] Elite 10 Survival Skirmishes</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-prime-6-mp3-generators-from-tiktok-videos-for-no-cost/"><u>[Updated] In 2024, Prime 6 MP3 Generators From TikTok Videos for No Cost</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-the-symphony-of-well-being-learn-from-asmr/"><u>[Updated] In 2024, The Symphony of Well-Being – Learn From ASMR</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-turbocharged-triumphs-unveiling-five-pinnacle-racer-simulators/"><u>[Updated] In 2024, Turbocharged Triumphs  Unveiling Five Pinnacle Racer Simulators</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-strategic-interaction-for-sustainable-subscriber-acquisition/"><u>[Updated] Strategic Interaction for Sustainable Subscriber Acquisition</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-unleashing-your-creative-spark-stylistic-self-discovery-high-ctr-for-2024/"><u>[Updated] Unleashing Your Creative Spark  Stylistic Self-Discovery [High CTR] for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/9-ways-to-fix-the-0x8004def5-onedrive-error-code-on-windows-11/"><u>9 Ways to Fix the 0X8004def5 OneDrive Error Code on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/a-stepwise-guide-to-banishing-the-onedrive-icon-from-explorer/"><u>A Stepwise Guide to Banishing the OneDrive Icon From Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-non-admin-privilege-levels-in-windows-os/"><u>Adjusting Non-Admin Privilege Levels in Windows OS</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/all-you-need-to-know-about-the-samsung-galaxy-ring-price-points-launch-dates-and-core-features-explained/"><u>All You Need to Know About the Samsung Galaxy Ring - Price Points, Launch Dates & Core Features Explained</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-is-greyed-out-on-apple-iphone-se-2022-how-to-bypass-by-drfone-ios/"><u>Apple ID is Greyed Out On Apple iPhone SE (2022) How to Bypass?</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/asmr-tactics-your-path-to-nocturnal-serenity/"><u>ASMR Tactics  Your Path to Nocturnal Serenity</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-windows-11-stumbling-blocks-the-most-crucial-tips/"><u>Avoiding Windows 11 Stumbling Blocks: The Most Crucial Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-windows-updates-0x80242016-hurdles/"><u>Avoiding Windows Update's 0X80242016 Hurdles</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-error-code-x80131500-at-store/"><u>Breaking Down Error Code: X80131500 at Store</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/canva-tutorial-for-flawless-image-border-clearance/"><u>Canva Tutorial for Flawless Image Border Clearance</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-to-rectify-windows-security-faults/"><u>Comprehensive Guide to Rectify Windows Security Faults</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-fn-keys-to-maximize-pc-efficiency-in-wins/"><u>Customizing FN Keys to Maximize PC Efficiency in Wins</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-down-energy-waste-without-slowing-down-games/"><u>Cutting Down Energy Waste Without Slowing Down Games</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/data-recovery-recover-lost-data-from-13t-pro-by-fonelab-android-recover-data/"><u>Data Recovery – recover lost data from 13T Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/digital-dream-team-top-windows-apps-for-a-winning-start/"><u>Digital Dream Team: Top Windows Apps for a Winning Start</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-clutter-software-uninstallation-tricks-for-windows-11-106-chars/"><u>Eliminating Clutter: Software Uninstallation Tricks for Windows 11 (106 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-windows-11s-functionality-top-strategies-for-widget-upgrades/"><u>Enhancing Windows 11'S Functionality: Top Strategies for Widget Upgrades</u></a></li>
<li><a href="https://screen-capture.techidaily.com/farm-frenzy-the-ultimate-group-game-guide-for-farms-for-2024/"><u>Farm Frenzy  The Ultimate Group Game Guide for Farms for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-a-non-compatible-device-after-windows-11-installation/"><u>Fixing a Non-Compatible Device After Windows 11 Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/get-ahead-in-passwords-7-best-free-generation-tools-for-windows/"><u>Get Ahead in Passwords: 7 Best Free Generation Tools for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/hidden-harmony-seamlessly-blending-image-and-zip-archives-win1011/"><u>Hidden Harmony: Seamlessly Blending Image and ZIP Archives WIN10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-removing-windows-11s-taskbar-chatter-affects-you-the-user/"><u>How Removing Windows 11'S Taskbar Chatter Affects You, The User?</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-pause-life360-location-sharing-for-xiaomi-13t-pro-drfone-by-drfone-virtual-android/"><u>How To Pause Life360 Location Sharing For Xiaomi 13T Pro | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-revive-your-bricked-xiaomi-13t-in-minutes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Revive Your Bricked Xiaomi 13T in Minutes | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-complete-fixes-to-solve-apple-iphone-se-2020-randomly-asking-for-apple-id-password-drfone-by-drfone-ios/"><u>In 2024, Complete Fixes To Solve Apple iPhone SE (2020) Randomly Asking for Apple ID Password | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/1715860847011-in-2024-efficient-image-capture-try-these-top-5-pc-tools/"><u>In 2024, Efficient Image Capture? Try These Top 5 PC Tools!</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-for-people-wanting-to-mock-gps-on-motorola-moto-g84-5g-devices-drfone-by-drfone-virtual/"><u>In 2024, For People Wanting to Mock GPS on Motorola Moto G84 5G Devices | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-your-infinix-hot-30i-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>In 2024, How to Mirror Your Infinix Hot 30i Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-vivo-x100-phone-with-broken-screen-by-drfone-android/"><u>In 2024, How to Unlock Vivo X100 Phone with Broken Screen</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-universal-unlock-pattern-for-xiaomi-redmi-k70-by-drfone-android/"><u>In 2024, Universal Unlock Pattern for Xiaomi Redmi K70</u></a></li>
<li><a href="https://windows11.techidaily.com/master-your-timers-fixing-scheduler-errors/"><u>Master Your Timers: Fixing Scheduler Errors</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/messvid-grabber-for-social-media/"><u>MessVid Grabber for Social Media</u></a></li>
<li><a href="https://windows11.techidaily.com/microsofts-helpers-quick-fixes-for-window-woes/"><u>Microsoft's Helpers: Quick Fixes for Window Woes!</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-your-experience-adding-uninstall-shortcut-in-windows-10/"><u>Optimize Your Experience: Adding Uninstall Shortcut in Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/personalize-your-desktop-space-win-os-snap-configurations/"><u>Personalize Your Desktop Space: Win OS Snap Configurations</u></a></li>
<li><a href="https://windows11.techidaily.com/recovering-robustness-of-ccleaner-on-your-win11-pc/"><u>Recovering Robustness of CCleaner on Your Win11 PC</u></a></li>
<li><a href="https://windows11.techidaily.com/resurrect-corrupted-files-win-11s-zip-fix-guide/"><u>Resurrect Corrupted Files: Win 11'S ZIP Fix Guide</u></a></li>
<li><a href="https://technical-tips.techidaily.com/seven-notable-smartphone-alarm-clock-apps-to-start-your-day-right/"><u>Seven Notable Smartphone Alarm Clock Apps to Start Your Day Right</u></a></li>
<li><a href="https://windows11.techidaily.com/simplified-guide-to-shift-your-qbittorrent-installation/"><u>Simplified Guide to Shift Your qBittorrent Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/solve-no-errors-on-win11-quick-fix-guide/"><u>Solve No Errors on Win11 - Quick Fix Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-window-11s-missing-clickables-problem/"><u>Solving Window 11'S Missing Clickables Problem</u></a></li>
<li><a href="https://windows11.techidaily.com/success-reinstalling-microsofts-pc-manager-in-win8/"><u>Success! Reinstalling Microsoft's PC Manager in Win8</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-the-winds-of-windows-fix-for-non-openable-exes/"><u>Taming the Winds of Windows: Fix for Non-Openable EXEs</u></a></li>
<li><a href="https://windows11.techidaily.com/tech-enthusiasts-treasure-hunt-unlock-free-lifetime-windows-11-from-black-fridays-best-price/"><u>Tech Enthusiasts’ Treasure Hunt: Unlock Free Lifetime Windows 11 From Black Friday's Best Price</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-unblock-application-packages-on-windows-servers/"><u>Techniques to Unblock Application Packages on Windows Servers</u></a></li>
<li><a href="https://windows11.techidaily.com/triumph-over-the-quiet-shop-microsoft-writes-on-error-x00000000/"><u>Triumph over the Quiet Shop: Microsoft' Writes on Error X00000000</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/unova-stone-pokemon-go-evolution-list-and-how-catch-them-for-motorola-moto-g73-5g-drfone-by-drfone-virtual-android/"><u>Unova Stone Pokémon Go Evolution List and How Catch Them For Motorola Moto G73 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-power-of-dism-in-win11-image-management/"><u>Unveiling the Power of Dism in Win11 Image Management</u></a></li>
<li><a href="https://windows11.techidaily.com/why-task-managers-feature-extras-under-edge/"><u>Why Task Managers Feature Extras Under Edge?</u></a></li>
<li><a href="https://windows11.techidaily.com/zeroing-out-bloatware-windows-11-edition/"><u>Zeroing Out Bloatware: Windows 11 Edition</u></a></li>
</ul></div>
