---
title: Postponing Edge's Tab Transition on Windows 11
date: 2024-08-22T21:38:46.667Z
updated: 2024-08-23T21:38:46.667Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Postponing Edge's Tab Transition on Windows 11
excerpt: This Article Describes Postponing Edge's Tab Transition on Windows 11
keywords: Win11 Tab Shift,Delayed Edge Update,Edge Transition Postpone,Window 11 Tab Change,Tab Changes in Windows 11,Delaying Edge Switch,Pause Edge Update Windows
thumbnail: https://thmb.techidaily.com/9828bf793f93780e9596bdf90064698c2faf8ab4424f88be5c51fa1662b48994.jpg
---

## Postponing Edge's Tab Transition on Windows 11

 Microsoft Edge is the default browser in Windows and comes pre-installed on the operating system without any easy way of getting rid of it. The browser uses "tab preloading," which preloads the Start and New Tab page while you sign in to your PC.

 For Edge lovers, it is a boon, but if you don’t use the default browser and prefer something else, it is a waste of resources. Fortunately, you can easily disable Edge's tab preloading in Windows 11\.

## 1\. How to Disable Edge Tab Preloading Using the Group Policy Editor

 Windows Pro, Education, and Enterprise users get the perks of the Group Policy Editor by default. You can use it to configure system policies on your PC and personalize it. If you're on Windows Home, check out [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

 Repeat the following steps to disable Edge tab preloading using the Group Policy Editor:

1. Press **Win + S** to open Windows Search. Type **gpedit.msc** in the text box and press the **Enter** key to open the Group Policy Editor.
2. Click on the **User Configuration** option in the left-hand side pane.
3. Navigate to **Administrative Templates > Windows Components > Microsoft Edge**.
4. Find the “**Allow Microsoft Edge to start and load the Start and New Tab page at Windows startup and each time Microsoft Edge is closed**” policy. Right-click on it and select the **Edit** option from the context menu.  
![Disable Microsoft Edge Tab Preloading Using GPE](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-gpe.jpg)
5. Click on the **Enabled** radio button.
6. Scroll down and click on the drop-down list next to the **Configure tab preloading** option. Select the **Prevent tab preloading** option.
7. Click on the **Apply** button. Then click on the **OK** button to save the changes.  
![Disable Microsoft Edge Tab Preloading Using GPE 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-gpe-2.jpg)
8. **Exit** the Group Policy Editor window.
9. **Restart** your PC for the policy changes to take effect and disable the tab preloading feature.

## 2\. How to Disable Edge Tab Preloading Using the Registry Editor

 If you use the Home version of Windows 11, it may be easier to take a different approach instead of going through the Group Policy Editor method. If you want, you can tweak the registry manually to disable the Edge tab preloading feature in Windows 11\. Repeat the following steps to do so:

 Before making changes to the Windows Registry, [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) for safety purposes.

1. Press **Win + R** to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **regedit** in the text box and press the **Enter** key.
2. Go to the address bar at the top and click on it. Paste the following path in the text box and press the **Enter** key:  
HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\MicrosoftEdge\Main
3. Go to the right-hand side section and right-click on the empty area. Select **New > DWORD (32-bit) Value**.
4. Click on the newly created DWORD value and name it “**AllowPrelaunch**”.
5. Right-click on the **AllowPrelaunch** value and select the **Modify** option from the context menu.
6. Go to the **Value Data** field and type **0** in it. Set the **Base** to **Hexadecimal** and click on the **OK** button.  
![Disable Microsoft Edge Tab Preloading Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-registry-editor.jpg)

 Now, you need to create a new subkey and add a new DWORD value:

1. Right-click on the Microsoft Edge key and select the **New > Key** option.
2. Name the key “**TabPreloader**” and click on it to select it.
3. Go to the right-hand side section and right-click on it. Select **New > DWORD (32-bit) Value**.
4. Click on the DWORD value and name it “**AllowTabPreloading**”.
5. Right-click on the **AllowTabPreloading** value and select the **Modify** option.
6. Go to the **Value Data** field and type **0** in it. Set the **Base** to **Hexadecimal** and click on the **OK** button.  
![Disable Microsoft Edge Tab Preloading Using Registry Editor 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-registry-editor-2.jpg)
7. **Close** the Registry Editor window.
8. **Restart** your PC to apply the changes made to the registry.

<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. How to Disable Edge Tab Preloading Using CMD or PowerShell

 If you find the Registry Editor method too cumbersome, you can use the Command Prompt or PowerShell to modify the Registry and disable Edge tab preloading. Here’s how to do it:

1. [Open the Command Prompt with administrator privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/) on your PC.
2. Execute the following commands to add two new registry entries:  
`reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\MicrosoftEdge\Main" /v AllowPrelaunch /t REG_DWORD /d 00000000 /f  
 reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\MicrosoftEdge\TabPreloader" /v AllowTabPreloading /t REG_DWORD /d 00000000 /f`
3. **Close** the Command Prompt window and **restart** your PC.  
![Disable Microsoft Edge Tab Preloading Using CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-cmd.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
## 4\. How to Disable Edge Tab Preloading Using the Ultimate Windows Tweaker App

 You can also use a third-party app like the Ultimate Windows Tweaker to disable Edge tab preloading in Windows 11\. Download the [Ultimate Windows Tweaker](https://www.thewindowsclub.com/ultimate-windows-tweaker-4-windows-10) app and install it on your PC. After that, repeat the following steps:

1. Press **Win + S** to open the Windows Search app. Type **Ultimate Windows Tweaker** and then click on the **Run as administrator** option.
2. Click on the **Search For Tweaks** option. Type “**edge tab**” in the search box and click on the **Go** button.  
![Disable Microsoft Edge Tab Preloading Using Ultimate Windows Tweaker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-ultimate-windows-tweaker.jpg)
3. Click on the **Disable Edge Tab Preloading** checkbox to enable it. Then, click on the **Apply Tweaks** button.  
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
![Disable Microsoft Edge Tab Preloading Using Ultimate Windows Tweaker 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-ultimate-windows-tweaker-2.jpg)
4. **Close** the Ultimate Windows Tweaker app and **restart** your PC to apply the changes.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Disable Edge Tab Preloading for Good on Windows 11

 Edge tab preloading serves no useful purpose if you use other browsers. You can disable it using the Group Policy Editor or the Registry Editor. Lastly, if you want a GUI app to disable the feature, you can use the Ultimate Windows Tweaker app.

 For Edge lovers, it is a boon, but if you don’t use the default browser and prefer something else, it is a waste of resources. Fortunately, you can easily disable Edge's tab preloading in Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-2023-fix-facebook-videos-not-playing-on-androidiphonechrome/"><u>[New] 2024 Approved  2023 | Fix Facebook Videos Not Playing on Android/iPhone/Chrome</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-elevating-your-igtv-presence-with-stunning-covers/"><u>[New] 2024 Approved  Elevating Your IGTV Presence with Stunning Covers</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-elite-10-audio-boosters-for-os-x-ios-android/"><u>[New] 2024 Approved  Elite 10 Audio Boosters for OS X, iOS, Android</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-keep-it-flowing-repasting-content-on-ig/"><u>[New] 2024 Approved  Keep It Flowing  Repasting Content on IG</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-techniques-for-engaging-google-meet-audiences-with-laptop-based-ppt/"><u>[New] 2024 Approved  Techniques for Engaging Google Meet Audiences with Laptop-Based PPT</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-evaluating-the-future-of-video-editing-with-movavis-plus-2024/"><u>[New] Evaluating the Future of Video Editing with Movavi's Plus 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-spark-interest-on-instagram-with-top-unboxing-video-techniques/"><u>[New] Spark Interest on Instagram with Top Unboxing Video Techniques</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-find-hidden-watch-tile-artwork/"><u>[Updated] 2024 Approved  Find Hidden Watch Tile Artwork</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-unlock-your-potential-best-instagram-video-editors-android-pc/"><u>[Updated] In 2024, Unlock Your Potential  Best Instagram Video Editors (Android, PC)</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-the-elite-selection-of-instagram-image-boosters-for-2024/"><u>[Updated] The Elite Selection of Instagram Image Boosters for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-greener-marketing-blend-screens-subscription-tech/"><u>2024 Approved  Greener Marketing  Blend Screens, Subscription Tech</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-peeling-back-the-layers-of-magix-image-suite/"><u>2024 Approved  Peeling Back the Layers of MAGIX Image Suite</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-top-picks-professional-ringtone-designer-guide/"><u>2024 Approved  Top Picks  Professional Ringtone Designer Guide</u></a></li>
<li><a href="https://android-frp.techidaily.com/about-realme-c67-4g-frp-bypass-by-drfone-android/"><u>About Realme C67 4G FRP Bypass</u></a></li>
<li><a href="https://games-able.techidaily.com/bring-to-life-the-world-of-bg3-seamlessly-with-mac-and-crossover/"><u>Bring to Life the World of BG3 Seamlessly with Mac and CrossOver</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-music-files-on-nubia-red-magic-8s-proplus-by-fonelab-android-recover-music/"><u>Complete guide for recovering music files on Nubia Red Magic 8S Pro+</u></a></li>
<li><a href="https://win-answers.techidaily.com/comprehensive-guide-resolve-logitech-g-hub-connectivity-problems-on-windows/"><u>Comprehensive Guide: Resolve Logitech G Hub Connectivity Problems on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-to-boost-your-speed-in-3d-paint-keys/"><u>Essential Tips to Boost Your Speed in 3D Paint Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/exclusive-w10w11-climate-software-roundup/"><u>Exclusive W10/W11 Climate Software Roundup</u></a></li>
<li><a href="https://windows11.techidaily.com/faster-printouts-with-easy-windows-troubleshooting/"><u>Faster Printouts with Easy WIndows Troubleshooting</u></a></li>
<li><a href="https://windows11.techidaily.com/five-key-insights-into-how-win11-tracks-your-life/"><u>Five Key Insights Into How Win11 Tracks Your Life</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-activation-problem-eliminate-error-0x803f700f/"><u>Fixing Windows Activation Problem: Eliminate Error 0X803F700f</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-fixing-winrars-failed-file-sums-and-verifications/"><u>Guide to Fixing WinRAR's Failed File Sums and Verifications</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-a-device-which-does-not-exist-was-specified-error-in-windows-10-and-11/"><u>How to Fix the “A Device Which Does Not Exist Was Specified” Error in Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-discord-fatal-javascript-error-in-windows-11-and-11/"><u>How to Fix the Discord Fatal Javascript Error in Windows 11 & 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-xs-to-androidios-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone XS to Android/iOS? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-poco-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>How to Unlock Poco Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-for-people-wanting-to-mock-gps-on-lava-yuva-3-pro-devices-drfone-by-drfone-virtual/"><u>In 2024, For People Wanting to Mock GPS on Lava Yuva 3 Pro Devices | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/learn-to-circumvent-windows-11-lock-without-fuss/"><u>Learn to Circumvent Windows 11 Lock Without Fuss</u></a></li>
<li><a href="https://fox-http.techidaily.com/live-sound-perfection-our-selections-of-the-top-6-stream-friendly-mics/"><u>Live Sound Perfection  Our Selections of the Top 6 Stream-Friendly Mics</u></a></li>
<li><a href="https://windows11.techidaily.com/maintaining-harmony-keeping-your-gaming-system-steady-on-win/"><u>Maintaining Harmony: Keeping Your Gaming System Steady on Win</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-win-1011-domain-services-printer-fixation-techniques/"><u>Mastering Win 10/11 Domain Services Printer Fixation Techniques</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/maximizing-roi-with-snapchat-for-biz-leaders-for-2024/"><u>Maximizing ROI with Snapchat for Biz Leaders for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/new-era-of-productivity-microsofts-ai-integration-in-windows-11-taskbar/"><u>New Era of Productivity: Microsoft's AI Integration in Windows 11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-windows-for-productivity-add-software-actions/"><u>Optimizing Windows for Productivity: Add Software Actions</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-common-windows-error-with-lsassexe/"><u>Overcoming Common Windows Error with lsass.exe</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-operation-failure-code-0x0000011b-in-win11-system/"><u>Overcoming Operation Failure Code 0X0000011B in Win11 System</u></a></li>
<li><a href="https://windows11.techidaily.com/precision-and-convenience-meet-with-our-winning-window-timers-list/"><u>Precision & Convenience Meet With Our Winning Window Timers List</u></a></li>
<li><a href="https://windows11.techidaily.com/prtscn-and-snipping-tool-tie-in-in-windows-11-how-to-break-it/"><u>PrtScn & Snipping Tool Tie-In in Windows 11 - How to Break It</u></a></li>
<li><a href="https://windows11.techidaily.com/purpose-behind-visual-cplusplus-distributable/"><u>Purpose Behind Visual C++ Distributable</u></a></li>
<li><a href="https://windows11.techidaily.com/re-establishing-classic-navigation-in-win-11/"><u>Re-Establishing Classic Navigation in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/rebooting-to-reactivate-dormant-snapshots/"><u>Rebooting to Reactivate Dormant Snapshots</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-missing-apps-icon-issue/"><u>Rectifying Missing Apps Icon Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/reimagining-the-look-of-basic-text-editor-in-windows-11/"><u>Reimagining the Look of Basic Text Editor in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-cease-random-file-explorer-launch/"><u>Remedy: Cease Random File Explorer Launch</u></a></li>
<li><a href="https://windows11.techidaily.com/restarting-windows-security-fix-for-flawed-functions/"><u>Restarting Windows Security: Fix for Flawed Functions</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-a-smooth-setup-for-microsoft-works-in-w11/"><u>Securing a Smooth Setup for Microsoft Works in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-repair-disk-errors-in-windows-os/"><u>Steps to Repair Disk Errors in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/stepwise-navigation-through-bluescreenview-features/"><u>Stepwise Navigation Through BlueScreenView Features</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-windows-install-9-methods-to-bypass-verification-lag/"><u>Streamlining Windows Install: 9 Methods to Bypass Verification Lag</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-your-wi-fi-networks-usage-metrics-with-windows-11/"><u>Tailoring Your Wi-Fi Network's Usage Metrics with Windows 11</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/the-budding-gardeners-handbook-to-sustainable-veggie-gardening-from-seedling-to-harvest/"><u>The Budding Gardener's Handbook to Sustainable Veggie Gardening From Seedling to Harvest</u></a></li>
<li><a href="https://windows11.techidaily.com/the-unplugged-play-linking-windows-to-ps3-gamepad/"><u>The Unplugged Play: Linking Windows to PS3 Gamepad</u></a></li>
<li><a href="https://windows11.techidaily.com/top-7-windows-cryptography-tools-under-156-chars/"><u>Top 7 Windows Cryptography Tools (Under 156 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-absence-of-files-on-windows-11/"><u>Troubleshooting Absence of Files on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/uncover-and-fix-hidden-5ghz-connections-in-windows-11-easily/"><u>Uncover & Fix Hidden 5GHz Connections in Windows 11 Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-your-pcs-true-power-with-enhanced-vram-settings-in-windows-10-and-11/"><u>Unleash Your PC's True Power with Enhanced VRAM Settings in Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-memory-write-hitches-in-windows/"><u>Unraveling 'Memory Write' Hitches in Windows</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>