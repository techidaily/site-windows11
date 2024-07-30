---
title: Eradicating Microsoft Edge on Win11
date: 2024-07-29T04:25:33.500Z
updated: 2024-07-30T04:25:33.500Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eradicating Microsoft Edge on Win11
excerpt: This Article Describes Eradicating Microsoft Edge on Win11
keywords: Eliminate Edge Issue,Fixing Windows 11 Edge,Removing Edge Problems,Eradicate Microsoft Edge,Get Rid of Edge Browser,Resolve Win11 Edge,Disable Windows Edge
thumbnail: https://thmb.techidaily.com/b138b868d1835e887dd60f251ee7ea4ef4f6730ac1d9438afe31e96762be6b28.jpg
---

## Eradicating Microsoft Edge on Win11

 Although Microsoft Edge has made significant progress in recent years, it still lags far behind its biggest rival—Google Chrome. If you’re someone who does not like using Microsoft Edge, you may want to get rid of the browser entirely.

 It’s no secret that Microsoft wants users to use its own browser on Windows 11\. To that end, the company has made it difficult to remove the browser from Windows 11\. However, it’s still possible to do so. Here we'll show you three different ways to uninstall Microsoft Edge from your Windows 11 PC.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
## 1\. How to Uninstall Microsoft Edge Using the Command Prompt

 You can uninstall Microsoft Edge from your PC by running a few commands in the command prompt. The process requires you to know the version number of Microsoft Edge on your computer. Once you have that, you can get rid of the browser.

Here are the steps you need to follow.

1. Open Microsoft Edge on your PC.
2. Click the**three-dot menu icon** in the top right corner and select**Help and feedback > About Microsoft Edge** .
3. Copy Microsoft Edge's version number from the**About** section.  
![Check Microsoft Edge Version Number](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Microsoft-Edge-Version-Number.jpg)
4. Press**Win + X** and select**Terminal (Admin)** from the menu that appears.
5. Select**Yes** when the User Account Control (UAC) prompt shows up.
6. In the console, run the following commands to navigate to the directory where Microsoft Edge is installed:  
`cd/  
cd %Program Files (x86)%\Microsoft\Edge\Application\EdgeVersion\Installer`  
 Replace**EdgeVersion** in the above command with the actual version number noted earlier.
7. Paste the following command and press**Enter** to uninstall Microsoft Edge.  
`setup --uninstall --force-uninstall --system-level`  
![Uninstall Microsoft Edge Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Using-Command-Prompt.jpg)

 Once you run the above commands, Microsoft Edge will be removed from your PC. If you want to install the browser in the future, you can do so by downloading it from the Microsoft Store.

 If you'd like to get more out of this tool, be sure to check out[the Windows Command Prompt commands you must know](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/) .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. How to Uninstall Microsoft Edge Using Windows PowerShell

 Like Command Prompt, you can also use Windows PowerShell to uninstall Microsoft Edge from your Windows 11 PC. Unlike the previous method, this one does not require you to know Microsoft Edge's version number. Here's how it works.

1. Press**Win + S** to open the search menu. Type in**Windows PowerShell** and select**Run as administrator** .
2. Select**Yes** when the[User Account Control (UAC)](https://www.makeuseof.com/tag/user-account-control-windows-10/) prompt appears.
3. Paste the following command and press**Enter** .  
`get-appxpackage *edge*`  
![Uninstall Microsoft Edge With Windows PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Using-Windows-PowerShell-1.jpg)
4. Highlight the text next to**PackageFullName** and press**Ctrl + C** to copy it.
5. Run the following command to uninstall Microsoft Edge.  
`Remove-appxpackage <PackageFullName>`  
 Replace**<PackageFullName>** in the above command with the package name copied earlier.

 Once you execute the above command, Microsoft Edge will be uninstalled.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. How to Uninstall Microsoft Edge Beta, Dev, or Canary Channel Builds Using the Settings App

 Unlike the stable version, removing a preview build of Microsoft Edge is relatively simple. You can uninstall it just like any other app. Here's how to do it using[Windows 11 Settings app](https://www.makeuseof.com/windows-11-settings-whats-new/) .

1. Press**Win + I** to open the Settings app.
2. Navigate to the**Apps** tab and click on**Installed apps** .
3. Scroll down to locate Microsoft Edge's preview build.
4. Click the**three-dot menu icon** next to it and select**Uninstall** .
5. Select**Uninstall** again when the confirmation pop-up appears.  
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Uninstall Microsoft Edge Beta From Windows 11 Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Beta-From-Windows-11-1.jpg)

 Aside from the Settings app, you can uninstall the browser from the Start menu or the Control Panel. See our guide to learn different[ways to uninstall built-in apps on Windows 11](https://www.makeuseof.com/ways-to-uninstall-apps-windows-11/) .

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Stop Microsoft Edge From Reinstalling on Windows 11

 Although uninstalling Edge from your computer is easy, it does not prevent newer Windows updates from potentially reinstalling the browser. To get around this, you need to[edit a few registry files](https://www.makeuseof.com/windows-registry-file-guide/) on your PC. For that, use the following steps:

1. Press**Win + R** to open the Run dialog box.
2. Type**regedit** in the box and press**Enter** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the Registry Editor window that appears, navigate to**HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft** key.
5. Right-click on the**Microsoft** key, go to**New** , and select**Key** from the submenu. Rename the key to**EdgeUpdate** .
6. Right-click on the**EdgeUpdate** key and select**New > DWORD (32-bit) Value** . Rename the DWORD to**DoNotUpdateToEdgeWithChromium** .
7. Double-click on the newly created DWORD and change its value data to**1** . Then, hit**OK** .  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
![Edit DWORD in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/edit-dword-in-registry-editor.jpg)

 Once you complete the above steps, Windows will not reinstall Microsoft Edge with future updates.

## Get Rid of Microsoft Edge

 With Windows 11, Microsoft tried everything possible to entice users to switch to Microsoft Edge. Unfortunately, it hasn't worked out very well, as many people still prefer to use alternatives like Google Chrome. If you are one of them, you can get rid of Microsoft Edge using the steps outlined above.

 Now that you've uninstalled Microsoft Edge, you might want to make your preferred web browser the default option on Windows 11.


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
<li><a href="https://screen-recording.techidaily.com/new-discovering-the-10-leading-low-cost-mobile-video-conferencing-for-2024/"><u>[New] Discovering the 10 Leading Low-Cost, Mobile Video Conferencing for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-profit-from-youtube-monetize-youtube-shorts-and-boost-your-income-for-2024/"><u>[New] Profit From YouTube  Monetize YouTube Shorts and Boost Your Income for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-the-creators-guide-to-the-top-9-affordable-video-editing-apps/"><u>[New] The Creator's Guide to the Top 9 Affordable Video Editing Apps</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-ultimate-guide-to-record-games-on-windows-10-pc/"><u>[New] Ultimate Guide to Record Games on Windows 10 PC</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-2024-approved-dive-into-dynamic-editing-windows-xp-edition-guide/"><u>[Updated] 2024 Approved  Dive Into Dynamic Editing  Windows XP Edition Guide</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-bursting-laughter-crafting-engaging-reaction-videos-on-youtube-3-methods-for-2024/"><u>[Updated] Bursting Laughter  Crafting Engaging Reaction Videos on YouTube (3 Methods) for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-earn-online-via-youtube-how-reaching-500-subscribers-pays-off/"><u>[Updated] Earn Online via YouTube  How Reaching 500 Subscribers Pays Off</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-dance-the-viral-dance-mix-in-some-tiktok-flavor-for-insta-success/"><u>[Updated] In 2024, Dance the Viral Dance  Mix in Some TikTok Flavor for Insta Success</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-misconfigured-duo-apps-on-windows/"><u>Addressing Misconfigured Duo Apps on Windows</u></a></li>
<li><a href="https://extra-hints.techidaily.com/best-podcasts-on-google-podcasts/"><u>Best Podcasts on Google Podcasts</u></a></li>
<li><a href="https://windows11.techidaily.com/beyond-boundaries-3-tools-that-elevate-pc-audio-above-100/"><u>Beyond Boundaries: 3 Tools That Elevate PC Audio Above 100%%</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-dismantling-the-win10-blue-screen/"><u>Decoding and Dismantling the Win10 Blue Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/detailed-exploration-retrieving-the-true-nature-of-device-ids-in-windows/"><u>Detailed Exploration: Retrieving the True Nature of Device IDs in Windows</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/different-methods-to-unlock-your-apple-iphone-13-pro-max-by-drfone-ios/"><u>Different Methods To Unlock Your Apple iPhone 13 Pro Max</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-windows-1011-unsigned-update-errors/"><u>Eliminating Windows 10/11 'Unsigned' Update Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/empowering-your-system-bypass-tpm-and-secure-boot-via-rufus/"><u>Empowering Your System: Bypass TPM & Secure Boot via Rufus</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-system-diagnostics-a-guide-to-windows-ping-usage/"><u>Enhancing System Diagnostics: A Guide to Windows Ping Usage</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-steps-to-prevent-and-resolve-onedrive-errors-on-your-pc/"><u>Essential Steps to Prevent and Resolve OneDrive Errors on Your PC</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/excellent-choices-best-windows-8-podcasting-for-2024/"><u>Excellent Choices  Best Windows 8 Podcasting for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/executing-policies-for-a-single-user-target-in-modern-windows-systems/"><u>Executing Policies for a Single-User Target in Modern Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-cant-detect-camera-error-on-windows-11-pc/"><u>Fixing Can't Detect Camera Error on Windows 11 PC</u></a></li>
<li><a href="https://windows11.techidaily.com/get-a-free-glimpse-into-the-realm-of-ocm-football/"><u>Get a FREE Glimpse Into the Realm of OCM Football</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-silencing-game-recommendations-on-w11/"><u>Guide to Silencing Game Recommendations on W11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-alleviate-windows-1011s-devastating-discord-js-failure/"><u>How to Alleviate Windows 10/11'S Devastating Discord JS Failure</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-google-play-location-on-samsung-galaxy-a15-5g-drfone-by-drfone-virtual-android/"><u>How to Change Google Play Location On Samsung Galaxy A15 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-stop-snipping-tool-activation-from-pressing-prtscn-in-11/"><u>How to Stop Snipping Tool Activation From Pressing PrtScn in 11</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-here-are-some-of-the-best-pokemon-discord-servers-to-join-on-tecno-spark-20-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some of the Best Pokemon Discord Servers to Join On Tecno Spark 20 | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-pro-tips-for-effortless-photos-and-videos-in-windows-11/"><u>In 2024, Pro Tips for Effortless Photos & Videos in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/master-your-computers-potential-a-wintoy-guidebook/"><u>Master Your Computer's Potential: A Wintoy Guidebook</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-memory-management-in-new-os/"><u>Mastering Memory Management in New OS</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-window-gloss-your-guide-to-a-clearer-taskbar-in-win11/"><u>Mastering Window Gloss: Your Guide to a Clearer Taskbar in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-and-protect-enabling-powershell-script-policy/"><u>Optimize & Protect: Enabling PowerShell Script Policy</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-your-drive-enable-file-cleanup-in-win11-operating-system/"><u>Optimize Your Drive: Enable File Cleanup in Win11 Operating System</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-printer-in-use-issue-on-windows-11/"><u>Overcoming Printer In Use Issue on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolve-compromised-windows-defender-in-windows-11/"><u>Resolve Compromised Windows Defender in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-microsoft-store-programs-on-windows-1011-systems/"><u>Restoring Microsoft Store Programs on Windows 10/11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-correct-wsl-error-code-4294967295-in-windows/"><u>Steps to Correct WSL Error Code 4294967295 in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-methods-for-verifying-windows-11-installation/"><u>The Essential Methods for Verifying Windows 11 Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-using-wireless-and-cable-in-harmony-on-windows/"><u>The Ultimate Guide: Using Wireless and Cable in Harmony on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-chkdsk-vs-scan-disk-dissecting-windows-tools/"><u>Understanding Chkdsk Vs. Scan Disk: Dissecting Windows Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/unfreezing-and-reviving-windows-11s-stuck-media-player/"><u>Unfreezing and Reviving Windows 11'S Stuck Media Player</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-speed-and-efficiency-windows-shortcuts-for-uwp/"><u>Unleash Speed and Efficiency: Windows Shortcuts for UWP</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-advanced-file-navigation-skills-steering-clear-of-ls/"><u>Unraveling Advanced File Navigation Skills: Steering Clear of LS</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-11-and-galaxy-ties-with-samsung-dex/"><u>Unveiling Windows 11 & Galaxy Ties with Samsung DeX</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/visionaries-of-interactive-marvel-worlds-for-2024/"><u>Visionaries of Interactive Marvel Worlds for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/what-purpose-does-a-directory-like-windows-bt-serve/"><u>What Purpose Does a Directory Like Windows ~BT Serve?</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-when-tecno-camon-20-pro-5g-has-black-screen-of-death-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do When Tecno Camon 20 Pro 5G Has Black Screen of Death? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-photo-wizardry-made-easy-mastering-slideshow-creation-and-spot-repair/"><u>Windows 11'S Photo Wizardry Made Easy: Mastering Slideshow Creation & Spot Repair</u></a></li>
</ul></div>
