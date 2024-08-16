---
title: "Optimize Visual Quality: DPI Settings Guide for Windows 11"
date: 2024-08-15T15:44:41.268Z
updated: 2024-08-16T15:44:41.268Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Optimize Visual Quality: DPI Settings Guide for Windows 11"
excerpt: "This Article Describes Optimize Visual Quality: DPI Settings Guide for Windows 11"
keywords: Windows DPI Tuning,High-Res Display,Image Clarity Window,Pixel Adjustment Tips,Visual Enhancement Windows,DPI Optimization Guide,Quality Images PC
thumbnail: https://thmb.techidaily.com/815fea7976911214190dec2e4ce8ef31c5b56fc35aca9555d7d0112a6571e067.jpg
---

## Optimize Visual Quality: DPI Settings Guide for Windows 11

 If you're looking to customize your computer experience, or just make things easier on the eyes, then changing the display DPI scaling on Windows is a great way to do that. In this helpful article, we'll provide you with an easy step-by-step guide for both registry tweaks and Windows settings so that customizing your computer can be done quickly and easily.

 Whether it's due to vision problems or if you simply want more control over how things look onscreen, these solutions are sure to help.

## What Is DPI Scaling on Windows?

 DPI stands for "dots per inch" and it refers to the number of individual dots that can be packed into an inch of space on your screen. The higher the number, the sharper and clearer the display. But here's the thing, sometimes you might want your text and images to be bigger, while at other times, you might want them smaller. That's where DPI scaling comes in; it's your very own personal adjustment tool.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
## How to Change Display DPI Scaling via Windows Settings

 The Settings app is the simplest and easiest way to change display scaling in Windows 11\. Here's how to do it.

1. Press**Win + I** on your keyboard to open the Settings menu.
2. From the left pane of the window, click the**System** tab.
3. Click**Display** on the right side.
4. Scroll down to the**Scale and layout** section.
5. Next to the**Scale** option, click the dropdown menu and change the scaling.  
![Change DPI Scale in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/change-dpi-scale-in-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Select the one that best fits your needs.

 After you've made your changes, close the window and restart your computer, so the changes take effect.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
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
![Change Display DPI Scaling in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/change-display-dpi-scaling-in-windows.jpg)  
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
![Change Display DPI Scaling Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/change-display-dpi-scaling-using-registry.jpg)
<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. In the pop-up menu, set the Value data to**0** if you set Logpixels to 96, or**1** if you used any other value.
5. Select**Hexadecimal** as the base and click**OK** .

 After performing the above steps, restart your computer to take effect the changes. If you ever need to restore the default settings, just open Registry Editor and go to the same location. Then double-click on Win8DpiScaling and change the Value data to 0.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
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
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-mastering-access-facebooks-classic-stories/"><u>[New] In 2024, Mastering Access  Facebook's Classic Stories</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-how-to-get-just-the-essentials-from-youtube-videos/"><u>[Updated] How to Get Just the Essentials From YouTube Videos</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-unveiling-fb-instream-ad-strategies-from-configuration-to-evaluation/"><u>[Updated] In 2024, Unveiling FB Instream Ad Strategies  From Configuration to Evaluation</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-learning-ranks-top-10-education-centric-channels/"><u>[Updated] Learning Ranks  Top 10 Education-Centric Channels</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-legacy-linkup-software-for-2024/"><u>[Updated] Legacy Linkup Software for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-leveraging-background-footage-for-engaging-content/"><u>[Updated] Leveraging Background Footage for Engaging Content</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-ai-integration-for-vr-marketplaces/"><u>2024 Approved  AI Integration for VR Marketplaces</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-reel-in-riches-a-guide-to-earning-on-youtube-shorts/"><u>2024 Approved  Reel In Riches  A Guide to Earning on YouTube Shorts</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-guide-to-controlling-user-profiles-in-windows/"><u>Expert Guide to Controlling User Profiles in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-abnormal-display-of-text-on-pcs/"><u>Fixing Abnormal Display of Text on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-clearing-winsec-error-limited-administrator/"><u>Guide to Clearing WinSec Error - 'Limited Administrator'</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-to-reinvigorate-stuck-desktop-bar/"><u>Guidelines to Reinvigorate Stuck Desktop Bar</u></a></li>
<li><a href="https://change-location.techidaily.com/how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-xiaomi-redmi-note-12t-pro-drfone-by-drfone-virtual-android/"><u>How PGSharp Save You from Ban While Spoofing Pokemon Go On Xiaomi Redmi Note 12T Pro? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-change-the-microsoft-account-administrator-name-in-windows-11/"><u>How to Change the Microsoft Account Administrator Name in Windows 11</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-it-tecno-spark-10-pro-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix It Tecno Spark 10 Pro Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-guarantee-windows-screensaver-immobility/"><u>How to Guarantee Windows Screensaver Immobility</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-halt-windows-push-notifications-for-updates/"><u>How to Halt Windows Push Notifications for Updates</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-with-location-spoofer-on-realme-12-pro-5g-drfone-by-drfone-virtual-android/"><u>How To Simulate GPS Movement With Location Spoofer On Realme 12 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-tackle-winservicesexe-malfunctions/"><u>How To Tackle WinServices.exe Malfunctions</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-unlock-the-lock-screen-on-my-12-by-drfone-android-unlock-android-unlock/"><u>How to Unlock the Lock Screen on my 12</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/how-to-update-or-repair-faulty-graphics-drivers-for-an-optimized-oculus-session/"><u>How to Update or Repair Faulty Graphics Drivers for an Optimized Oculus Session</u></a></li>
<li><a href="https://windows11.techidaily.com/implementing-effective-end-task-controls-in-windows-11-interface-design/"><u>Implementing Effective End Task Controls in Windows 11 Interface Design</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-swipe-right-for-speed-quick-tiktok-video-acquisition/"><u>In 2024, Swipe Right for Speed - Quick TikTok Video Acquisition</u></a></li>
<li><a href="https://windows11.techidaily.com/key-strategies-top-tips-for-maximizing-wsl-2-performance/"><u>Key Strategies: Top Tips for Maximizing WSL 2 Performance</u></a></li>
<li><a href="https://extra-support.techidaily.com/laughlens-pictorial-humor-studio-for-2024/"><u>LaughLens  Pictorial Humor Studio for 2024</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/leading-portable-power-solutions-for-your-laptop-the-definitive-list-of-2024/"><u>Leading Portable Power Solutions for Your Laptop: The Definitive List of 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/leap-forward-in-workflow-mastering-window-redos-shortcuts/"><u>Leap Forward in Workflow: Mastering Window Redos Shortcuts</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-art-dependencies-prior-to-vbox-for-windows/"><u>Master the Art: Dependencies Prior to VBox for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-os-settings-with-confidence/"><u>Mastering OS Settings with Confidence</u></a></li>
<li><a href="https://windows11.techidaily.com/maximize-wi-fi-performance-in-windows-11-discover-the-top-7-tips/"><u>Maximize Wi-Fi Performance in Windows 11: Discover the Top 7 Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/multi-monitor-magic-custom-wallpapers-for-each-screen/"><u>Multi-Monitor Magic: Custom Wallpapers for Each Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-copy-pasting-like-a-pro-using-powertoys/"><u>Navigate Copy-Pasting Like a Pro Using PowerToys</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-the-virtualupgrade-virtualbox-70-for-new-windows-11-users/"><u>Navigate the VirtualUpgrade: VirtualBox 7.0 for New Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-servers-problems-quick-and-effective-tips/"><u>Navigating Through Servers Problems: Quick & Effective Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-unresizable-gifs-in-windows-11s-discord-woes/"><u>Navigating Through Unresizable GIFs in Windows 11'S Discord Woes</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-speed-fixing-slow-microsoft-edge-win10win11/"><u>Optimizing Speed: Fixing Slow Microsoft Edge (Win10/Win11)</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-missing-launcher-dilemma-for-ubisoft-games/"><u>Overcoming Missing Launcher Dilemma for Ubisoft Games</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-non-saving-windows-audio-configuration-issue/"><u>Overcoming Non-Saving Window's Audio Configuration Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-net-framework-not-installed-message/"><u>Overcoming Windows' .NET Framework Not Installed Message</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-for-blue-screen-on-windows-11/"><u>Quick Fix for Blue Screen on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/rejuvenating-pcs-essential-13-tricks-for-restoring-systems/"><u>Rejuvenating PCs: Essential 13 Tricks for Restoring Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-erased-run-commands-logs/"><u>Reviving Erased Run Commands Logs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reviving-gameplay-cured-dxgidll-in-pubg/"><u>Reviving Gameplay: Cured Dxgi.dll in PUBG</u></a></li>
<li><a href="https://windows11.techidaily.com/spruce-up-windows-mail-and-schedule-with-personal-photos/"><u>Spruce Up Windows Mail & Schedule With Personal Photos</u></a></li>
<li><a href="https://windows11.techidaily.com/steer-clear-of-incompatible-feature-stickers-in-win11/"><u>Steer Clear of Incompatible Feature Stickers in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-repairing-windows-fragmented-file-issue/"><u>Steps for Repairing Windows Fragmented File Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-preventing-dxgi-errors/"><u>Strategies for Preventing DXGI Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/sustaining-operational-diagnostics-in-modern-windows/"><u>Sustaining Operational Diagnostics in Modern Windows</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-art-and-science-of-capturing-stunning-gopro-time-lapse-for-2024/"><u>The Art & Science of Capturing Stunning GoPro Time Lapse for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-crafting-a-better-windows-11/"><u>The Art of Crafting a Better Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshoot-error-non-working-windows-11-voice-access/"><u>Troubleshoot Error: Non-Working Windows 11 Voice Access</u></a></li>
<li><a href="https://windows11.techidaily.com/uncover-9-steps-for-altering-the-auditory-elements-of-windows-11/"><u>Uncover 9 Steps for Altering the Auditory Elements of Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/why-does-tasker-show-other-processes/"><u>Why Does Tasker Show Other Processes?</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/why-does-the-pokemon-go-battle-league-not-available-on-realme-c67-4g-drfone-by-drfone-virtual-android/"><u>Why does the pokemon go battle league not available On Realme C67 4G | Dr.fone</u></a></li>
</ul></div>
