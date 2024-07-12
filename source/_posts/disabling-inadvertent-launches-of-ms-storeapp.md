---
title: Disabling Inadvertent Launches of MS StoreApp
date: 2024-07-11T22:23:32.233Z
updated: 2024-07-12T22:23:32.233Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Disabling Inadvertent Launches of MS StoreApp
excerpt: This Article Describes Disabling Inadvertent Launches of MS StoreApp
keywords: Disable Unintentional MS Apps,Stop MS App Errors,Prevent MS App Crashes,Halt MS App Glitches,Avoid MS App Launch Mistakes,Fix MS Store App Triggers,Eliminate MS App Spontaneity
thumbnail: https://thmb.techidaily.com/18d1ae3b93316df7253b6d9ca3430e2e7b9da85a6ae22dbb42da5be064fc57fa.png
---

## Disabling Inadvertent Launches of MS StoreApp

 The Microsoft Store has come a long way since its introduction to Windows 8\. Every app, game, or movie available on the store is certified, so you don’t have to worry about infecting your computer with malware.

 But what if Windows keeps opening the Microsoft Store for no apparent reason? If you’ve run into the same issue, this guide should help you fix it.

##

## 1\. Close Microsoft Store's Background Processes

 Windows might keep opening the Microsoft Store if there’s a process still running in the background. To fix it, you should use Task Manager to stop any background activity.

 Press**Ctrl + Shift + Esc** to bring up Task Manager. There, right-click**Microsoft Store** and select**End task** .

![Close Windows Store with Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/task-manager-1.jpg)

##

## 2\. Restart the Microsoft Store Services

 There’s a chance that the Microsoft Store keeps acting up because of a service malfunction. The Microsoft Store Install Service is the one that works in the background to keep the store working.

 This is why restarting the service might be enough to fix Microsoft Store.

1. In the Start menu search bar, search for**services** and select**Run as administrator** .
2. In the Services window, locate and open**Microsoft Store Install Service** .
3. Click**Stop > Start** to restart it.
4. Restart your computer and monitor if Microsoft Store keeps opening.

![Restart Microsoft Store service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/store-service-1.jpg)

## 3\. Re-register Microsoft Store

 If nothing worked until now, you could re-register the Microsoft Store app. To do it, launch PowerShell with administrative rights and paste this code:

`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}<strong> </strong>`

 Then, press**Enter** to run it.

## 4\. Apply Generic Fixes for Microsoft Store Issues

 You may encounter this problem if the cache has become corrupted. As such, check out [how to fix a damaged Microsoft Store cache](https://www.makeuseof.com/ways-to-fix-damaged-microsoft-store-cache/) for more ways to fix this annoying problem.

 Similarly, a virus may be causing the Microsoft Store to open. Check out [how to remove malware using a Microsoft Defender offline scan](https://www.makeuseof.com/how-to-remove-malware-using-microsoft-defenders-offline-scan/) and give your PC a deep clean.

## Fix the Microsoft Store App Opening Itself

 Having the Microsoft Store app open by itself can be very disruptive, especially if it opens on top of all windows. Hopefully, one of these solutions worked and Microsoft Store has stopped launching by itself.

 If you’ve had enough and uninstalled it, you can still get Microsoft apps without the Microsoft Store.


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
<li><a href="https://windows11.techidaily.com/clearing-updates-fault-0x8019/"><u>Clearing Updates Fault 0X8019</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-windows-cab-and-its-method-for-installed-content/"><u>Deciphering Windows CAB & Its Method for Installed Content</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-remote-smile-engineer/"><u>[New] Remote Smile Engineer</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-to-rectifying-windows-11-search-issues/"><u>Comprehensive Guide to Rectifying Windows 11 Search Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-dual-users-fixing-their-windows-account-error/"><u>Clearing Up Dual Users: Fixing Their Windows Account Error</u></a></li>
<li><a href="https://windows11.techidaily.com/concealing-windows-11s-taskbar-search-function/"><u>Concealing Windows 11'S Taskbar Search Function</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-the-clutter-soundcard-irq-solutions/"><u>Cutting the Clutter: Soundcard IRQ Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-the-secret-to-smoothly-controlling-your-touchpad-in-windows-11/"><u>Discover the Secret to Smoothly Controlling Your Touchpad in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-blue-screen-errors-through-microsofts-tools-in-w11/"><u>Demystifying Blue Screen Errors Through Microsoft's Tools in W11</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/mobile-video-to-audio-conversion-made-easy-top-apps-reviewed-for-2024/"><u>Mobile Video to Audio Conversion Made Easy Top Apps Reviewed for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/4-ways-to-transfer-music-from-realme-12-5g-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>4 Ways to Transfer Music from Realme 12 5G to iPhone | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-disconnect-adjustable-gif-sizes-for-discord-on-windows/"><u>Deciphering Disconnect: Adjustable GIF Sizes for Discord on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-windows-ram-allocation-strategies/"><u>Deciphering Windows' RAM Allocation Strategies</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-animate-like-a-pro-the-top-7-drawing-software-for-aspiring-animators/"><u>In 2024, Animate Like a Pro The Top 7 Drawing Software for Aspiring Animators</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-your-nokia-c110-location-on-twitter-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change your Nokia C110 Location on Twitter | Dr.fone</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/transform-your-photos-into-engaging-mac-slideshows-with-ezvid-for-2024/"><u>Transform Your Photos Into Engaging Mac Slideshows with Ezvid for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/custom-menus-on-windows-1111-with-psoft-tools/"><u>Custom Menus on Windows 11/11 with PSoft Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-windows-arp-caches-made-simple/"><u>Clearing Windows ARP Caches Made Simple</u></a></li>
<li><a href="https://windows11.techidaily.com/detailed-steps-for-running-sfc-in-windows-os/"><u>Detailed Steps for Running SFC in Windows OS</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-capture-every-moment-the-premier-8-free-screen-capture-apps-for-android/"><u>[New] Capture Every Moment  The Premier 8 Free Screen Capture Apps for Android</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-expert-advice-on-achieving-high-quality-gopro-videos/"><u>[Updated] Expert Advice on Achieving High-Quality GoPro Videos</u></a></li>
<li><a href="https://extra-resources.techidaily.com/virtual-world-warfare-understanding-meta-and-omniverse-differences/"><u>Virtual World Warfare  Understanding Meta and Omniverse Differences</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-gopro-karma-drone-review/"><u>In 2024, GoPro Karma Drone Review</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-complexity-of-wintoys-your-guide-to-a-versatile-tool/"><u>Decoding the Complexity of 'WinToys': Your Guide to a Versatile Tool</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-top-tunes-palette-for-video-storytelling/"><u>2024 Approved  Top Tunes Palette for Video Storytelling</u></a></li>
<li><a href="https://windows11.techidaily.com/dive-into-customization-windows-11s-potential-unlocked/"><u>Dive Into Customization: Windows 11'S Potential Unlocked</u></a></li>
<li><a href="https://windows11.techidaily.com/command-line-interface-cli-addition-to-task-manager-in-windows-11/"><u>Command Line Interface (CLI) Addition to Task Manager in Windows 11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/pro-cams-face-off-gopro-hero5-black-and-garmin-virb-ultra-30/"><u>Pro Cams Face-Off  GoPro Hero5 Black and Garmin VIRB Ultra 30</u></a></li>
<li><a href="https://windows11.techidaily.com/direct-routes-to-windows-11s-user-authorization-screen/"><u>Direct Routes to Windows 11'S User Authorization Screen</u></a></li>
<li><a href="https://howto.techidaily.com/full-solutions-to-fix-error-code-920-in-google-play-on-vivo-x100-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Solutions to Fix Error Code 920 In Google Play on Vivo X100 | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/a-quick-guide-to-oppo-a18-frp-bypass-instantly-by-drfone-android/"><u>A Quick Guide to Oppo A18 FRP Bypass Instantly</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-dealing-with-steam-installation-fiascos-win11-style/"><u>Decoding and Dealing with Steam Installation Fiascos, Win11-Style</u></a></li>
<li><a href="https://extra-resources.techidaily.com/unveiling-10-hidden-powers-of-photoshop-newbies/"><u>Unveiling 10 Hidden Powers of Photoshop Newbies</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-2024-approved-the-elite-selection-of-8-dictation-technologies-for-desktop-operations-on-various-os-and-online-platforms/"><u>New 2024 Approved The Elite Selection of 8 Dictation Technologies for Desktop Operations on Various OS and Online Platforms</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-into-the-blueprint-cutting-edge-techniques-for-drones/"><u>2024 Approved  Into the Blueprint  Cutting-Edge Techniques for Drones</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-best-tips-for-camtasia-freeze-frame/"><u>2024 Approved Best Tips for Camtasia Freeze-Frame</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-significance-of-windows-subsystem-for-linux-error-4294967295/"><u>Deciphering the Significance of Windows Subsystem for Linux Error 4294967295</u></a></li>
<li><a href="https://windows11.techidaily.com/concealing-windows-firewall-areas-a-step-by-step-guide/"><u>Concealing Windows Firewall Areas: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/direct-methods-to-remove-a-peevous-print-spooler/"><u>Direct Methods to Remove a Peevous Print Spooler</u></a></li>
<li><a href="https://windows11.techidaily.com/command-the-past-mastering-file-history-navigation/"><u>Command the Past: Mastering File History Navigation</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-vintage-video-card-patch/"><u>2024 Approved  Vintage Video Card Patch</u></a></li>
</ul></div>
