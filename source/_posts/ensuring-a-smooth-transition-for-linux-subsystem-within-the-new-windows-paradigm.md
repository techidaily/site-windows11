---
title: Ensuring a Smooth Transition for Linux Subsystem Within the New Windows Paradigm
date: 2024-07-29T04:27:51.282Z
updated: 2024-07-30T04:27:51.282Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Ensuring a Smooth Transition for Linux Subsystem Within the New Windows Paradigm
excerpt: This Article Describes Ensuring a Smooth Transition for Linux Subsystem Within the New Windows Paradigm
keywords: Windows & Linux Integration,Subsystem Seamless Switching,Linux in Windows OS,WinLinux Ease-of-Use,Transition to Linux Windows,Smooth Linux Shell,New Windows-Linux Synergy
thumbnail: https://thmb.techidaily.com/58d6990fb1aba3befeda20029d053fd2dc8e67729321f3227eadd737a516d064.jpg
---

## Ensuring a Smooth Transition for Linux Subsystem Within the New Windows Paradigm

 There are several potential reasons why Windows Subsystem for Linux (WSL) stopped working after your PC was upgraded to Windows 11\. Thankfully, the breakdown is unlikely to be terminal, although you might have to try a few different fixes to get it working once again.

 **MUO VIDEO OF THE DAY**

 **SCROLL TO CONTINUE WITH CONTENT**

 Here are several ways to get the Windows Subsystem for Linux working again after upgrading to Windows 11.

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Check That WSL Is Enabled

 It isn't unusual that upgrading to a newer version of the OS will break some apps and features. So although it might sound obvious, checking WSL hasn't simply been disabled during the upgrade process should be your first step. Here's how to check:

![checking if WSL is enabled in Windows Features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-enabled.jpg)

1. In Windows Search, type**Turn Windows features on or off** and click the search result that should appear at the top.
2. In the Windows System dialog, scroll down until you see**Windows Subsystem for Linux** .
3. If the checkbox for the feature is not selected, do so now. Then click**Ok** .
4. You might also need to restart your computer before checking to see if that fixed the problem.

 Hopefully, WSL is now working, and you can begin using the tool. If not, read on for some other possible solutions.

 Learn more about the[things you can do with WSL and Linux](https://www.makeuseof.com/pros-cons-windows-subsystem-for-linux/) on your Windows computer.

## 2\. Enable Hyper-V and Virtual Machine Platform

 If you want to use a subsystem such as WSL in Windows, you'll also need to enable the virtualization tools. These include Hyper-V and the Virtual Machine Platform.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35408920&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/FR-200-1.png" border="0">Glarysoft File Recovery Pro - Helps to recover your lost file/data, even permanently deleted data. </a>
<!-- affiliate ads end -->
![Error message in the command line interface](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-feature-missing.jpg)

 If a command line interface opens, telling you a required feature is not installed, when you try to run your Linux distribution, this is likely what it refers to.

1. Search for**Turn Windows features on or off** and click the search result.
2. In Windows Features, scroll down to find**Virtual Machine Platform** and**Windows Hypervisor Platform** .
3. Check the boxes next to each of these features and then click**Ok** .
4. You will need to restart your computer to complete the installation of these tools.

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Repair the Linux Distribution App

 Your Linux distribution app, such as Ubuntu, Kali, or Debian, could be corrupted or require updating. This can cause WSL to appear to be broken. Repairing Windows apps is very easy.

1. Open**Settings > Apps > App & Features** .
2. Scroll down to the list of your apps to find your Linux distro app.
3. Click the**three dots** to the right of the app name, and select**Advanced options** .  
<!-- affiliate ads begin -->
<span id="1993652">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Advanced app options in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl.jpg)
4. Click the**Repair** button and follow the on-screen instructions if repairs are necessary.  
![repairing an app in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl-app.jpg)

 Check if WSL is working. If not, try uninstalling and reinstalling the Linux distribution app.

## 4\. Force WSL to Open Using the Microsoft Store

 If WSL is enabled but still refuses to open, you can try forcing launch through the Microsoft Store app. This can sometimes fix temporary glitches when opening WSL directly doesn't work.

1. Open the Microsoft Store app and search for**WSL** .
2. On the store page for WSL, you should see an**Open** button. If the button says**Update** , click it to update the app.  
![opening the WSL app in the Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/force-open-store.jpg)
3. Click the**Open** button, and the default Linux distro app should launch.
4. If a command line interface window opens instead, it will probably tell you a required feature is missing. See**Enable Hyper-V and Virtual Machine Platform** above.

 If forcing WSL to open doesn't work, try the same with the Linux distro app you are using. Open the Store, search for your distro, and click the**Open** button.

## 5\. Uninstall Recent Updates to Fix WSL

 If WSL stopped working after installing an update, the update could be the cause. You can uninstall the most recent update to see if that fixes the problem.

[Uninstalling Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) isn't a complicated process, even if you have never done it before.

 If, after uninstalling the update, WSL still does not work, it is a good idea to reinstall it. Updates can often include security and performance tweaks, so it is generally recommended to keep Windows updated.

<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Check That Malware Isn't Blocking WSL

 The final thing to try to get WSL working is scanning for malware. The potential for malware to prevent Windows Subsystem for Linux from working is low but not unheard of.

 Run a[full scan in Microsoft Defender](https://www.makeuseof.com/easy-ways-boost-security-microsoft-defender-and-windows-10/) or whichever third-party antivirus software you use. Quarantine or remove any malware your antivirus scan finds. Then restart your computer and try using WSL to see if that was the issue.

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fixing WSL After Upgrading to Windows 11

 Upgrading to Windows 11 usually goes smoothly, but apps and features can occasionally break. If you find that WSL is no longer working after upgrading to the newest Windows OS, don't worry, there is usually an easy fix. You might only need to re-enable the feature in the Windows system settings, but if not, running through the other fixes here will usually solve the problem.


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
<li><a href="https://vp-tips.techidaily.com/new-elevate-your-video-content-with-effective-unboxing-tactics-for-2024/"><u>[New] Elevate Your Video Content with Effective Unboxing Tactics for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-step-by-step-crafting-a-masterpiece-with-collages/"><u>[New] Step-by-Step  Crafting a Masterpiece with Collages</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-top-9-cross-platform-communication-apps-iphone-vs-android-comparison-for-2024/"><u>[New] Top 9 Cross-Platform Communication Apps  IPhone vs Android Comparison for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-how-to-become-a-youtube-partner-you-need-10000-views-now/"><u>[Updated] 2024 Approved  How to Become a YouTube Partner - You Need 10,000 Views Now</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-mastering-twitter-setup-in-5-steps/"><u>[Updated] 2024 Approved  Mastering Twitter Setup in 5 Steps</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-alleviate-chromes-video-viewing-problem/"><u>[Updated] Alleviate Chrome's Video Viewing Problem</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-auto-captioned-mastery-enhancing-visual-narratives/"><u>[Updated] Auto-Captioned Mastery  Enhancing Visual Narratives</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-learn-and-master-io-screen-recording-today/"><u>[Updated] In 2024, Learn and Master IO Screen Recording Today</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-secure-swift-airdrop-connections-on-all-apple-devices-fix-guide-for-2024/"><u>[Updated] Secure Swift Airdrop Connections on All Apple Devices - Fix Guide for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/a-stepwise-guide-to-banishing-the-onedrive-icon-from-explorer/"><u>A Stepwise Guide to Banishing the OneDrive Icon From Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-non-admin-privilege-levels-in-windows-os/"><u>Adjusting Non-Admin Privilege Levels in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-windows-updates-0x80242016-hurdles/"><u>Avoiding Windows Update's 0X80242016 Hurdles</u></a></li>
<li><a href="https://printer-issues.techidaily.com/compact-bundle-optimized-hp-officejet-pro-8600-drivers-win32/"><u>Compact Bundle: Optimized HP Officejet Pro 8600 Drivers, Win32</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-fn-keys-to-maximize-pc-efficiency-in-wins/"><u>Customizing FN Keys to Maximize PC Efficiency in Wins</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-down-energy-waste-without-slowing-down-games/"><u>Cutting Down Energy Waste Without Slowing Down Games</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/deciding-on-itop-recorder-an-indispensable-tool/"><u>Deciding on ITop Recorder - An Indispensable Tool?</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-windows-11s-functionality-top-strategies-for-widget-upgrades/"><u>Enhancing Windows 11'S Functionality: Top Strategies for Widget Upgrades</u></a></li>
<li><a href="https://extra-resources.techidaily.com/enhancing-zoom-picture-resolution-simple-upgrades/"><u>Enhancing Zoom Picture Resolution  Simple Upgrades</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-combatting-windows-not-found-problem/"><u>Essential Tips: Combatting Windows Not Found Problem</u></a></li>
<li><a href="https://windows11.techidaily.com/how-removing-windows-11s-taskbar-chatter-affects-you-the-user/"><u>How Removing Windows 11'S Taskbar Chatter Affects You, The User?</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-itel-p55-5g-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Itel P55 5G in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-make-win11s-canvas-come-alive-the-guide-to-creating-intriguing-ai-images-via-paint-tool-sai/"><u>How to Make Win11's Canvas Come Alive: The Guide to Creating Intriguing AI Images via Paint Tool SAI</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-reset-a-vivo-x100-phone-that-is-locked-by-drfone-android/"><u>How to Reset a Vivo X100 Phone that is Locked?</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-3-things-you-must-know-about-fake-snapchat-location-on-samsung-galaxy-f15-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Things You Must Know about Fake Snapchat Location On Samsung Galaxy F15 5G | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-oppo-a59-5g-by-phone-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Oppo A59 5G by Phone Number | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/live-stream-frontier-deciding-between-obs-and-twitch-space/"><u>Live Stream Frontier  Deciding Between OBS and Twitch Space</u></a></li>
<li><a href="https://windows11.techidaily.com/master-your-timers-fixing-scheduler-errors/"><u>Master Your Timers: Fixing Scheduler Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/microsofts-helpers-quick-fixes-for-window-woes/"><u>Microsoft's Helpers: Quick Fixes for Window Woes!</u></a></li>
<li><a href="https://youtube-help.techidaily.com/navigating-the-seo-landscape-top-keyword-research-instruments-for-2024/"><u>Navigating the SEO Landscape  Top Keyword Research Instruments for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/personalize-your-desktop-space-win-os-snap-configurations/"><u>Personalize Your Desktop Space: Win OS Snap Configurations</u></a></li>
<li><a href="https://windows11.techidaily.com/pursue-peak-performance-customizing-graphics-settings-for-games/"><u>Pursue Peak Performance: Customizing Graphics Settings for Games</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-vibrance-to-dull-desktop-windows-effects/"><u>Restoring Vibrance to Dull Desktop Windows Effects</u></a></li>
<li><a href="https://windows11.techidaily.com/resurrect-corrupted-files-win-11s-zip-fix-guide/"><u>Resurrect Corrupted Files: Win 11'S ZIP Fix Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/solve-no-errors-on-win11-quick-fix-guide/"><u>Solve No Errors on Win11 - Quick Fix Guide</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/step-up-your-income-game-with-these-13-unbeatable-reddit-tactics-for-2024/"><u>Step Up Your Income Game with These 13 Unbeatable Reddit Tactics for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-amend-non-interactive-menu-bar-on-windows-11/"><u>Steps to Amend Non-Interactive Menu Bar on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/success-reinstalling-microsofts-pc-manager-in-win8/"><u>Success! Reinstalling Microsoft's PC Manager in Win8</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-code-4-error-a-compre-cookie-guide/"><u>Tackling the Code 4 Error: A Compre Cookie Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-the-winds-of-windows-fix-for-non-openable-exes/"><u>Taming the Winds of Windows: Fix for Non-Openable EXEs</u></a></li>
<li><a href="https://windows11.techidaily.com/tech-enthusiasts-treasure-hunt-unlock-free-lifetime-windows-11-from-black-fridays-best-price/"><u>Tech Enthusiasts’ Treasure Hunt: Unlock Free Lifetime Windows 11 From Black Friday's Best Price</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/the-ultimate-5-star-fluids-and-flows-in-video-games/"><u>The Ultimate 5-Star Fluids and Flows in Video Games</u></a></li>
<li><a href="https://windows11.techidaily.com/transformingnotepadlighttodarkwin/"><u>TransformingNotepadLightToDarkWin</u></a></li>
<li><a href="https://windows11.techidaily.com/triumph-over-the-quiet-shop-microsoft-writes-on-error-x00000000/"><u>Triumph over the Quiet Shop: Microsoft' Writes on Error X00000000</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-pictures-from-nokia-c110-by-fonelab-android-recover-pictures/"><u>Undelete lost pictures from Nokia C110.</u></a></li>
</ul></div>