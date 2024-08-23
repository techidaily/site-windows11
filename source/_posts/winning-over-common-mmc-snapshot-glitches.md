---
title: Winning Over Common MMC Snapshot Glitches
date: 2024-08-22T21:34:47.760Z
updated: 2024-08-23T21:34:47.760Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Winning Over Common MMC Snapshot Glitches
excerpt: This Article Describes Winning Over Common MMC Snapshot Glitches
keywords: MMC Glitch Fix,MMC Snapshots Success,Eliminate MMC Errors,Snapshot MMC Winning,Overcoming MMC Glitches,Resolve MMC Snapshons,Combat MMC Disruptions
thumbnail: https://thmb.techidaily.com/34898e0ebb1abca68099d2acba8fac3a4c33b87872f768fed60cc168fcf66601.jpg
---

## Winning Over Common MMC Snapshot Glitches

 The "MMC could not create the snap-in" error has been around for some time and still seem to bug some users now and then. The error occurs when you try to open an administrative tool such as an Event Viewer, Task Scheduler, and so forth.

 Sometimes, the error may also pop up after a Blue Screen of Death (BSOD), causing one or more apps to crash. This error often occurs if the registry configuration of the snap-in is malfunctioning. Here we show a few ways to fix to help you resolve the "MMC could not create the snap-in" error and restore administrative tools access in Windows.

## 1\. Fix the Broken Registry Configuration for the Snap-In

![delete-registry-key-mmc-snap-in-windows-registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/delete-registry-key-mmc-snap-in-windows-registry.jpg)

 If the registry configuration for the affected snap-in is broken, it may trigger the "MMC could not create the snap-in" error. To fix the issue, you’ll need to delete the corrupt registry entry associated with the snap-in. Here’s how to do it.

 Making incorrect modifications to the Windows Registry involves risk and may cause your system to malfunction. We recommend you [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and [make a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) to be on the safe side.

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK**.
3. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\MMC\SnapIns`
4. The **SnapIns** key consists of multiple sub-keys. You need to locate the sub-key identical to the **CLSID** shown in the error message.
5. For example, if the error occurs when opening Event Viewer, you’ll likely see **CLSID: c7b8fb06-bfe1-4c2e-9217-7a69a95bbac4**, and so on. So, note down the **CLSID** shown in the error screen.

1. In the **Registry Editor**, select the sub-key folder with the same name as the error **CLSID**.
2. Next, right-click on the same sub-key folder and select **Delete**.
3. Click **Yes** to confirm the action.
4. Close the **Registry Editor** and restart your computer.
5. After the restart, open the administrative tool snap-in to see if the error is resolved.

## 2\. Enable .NET Framework

![enable net framework 3 5 windows features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-net-framework-3-5-windows-features.jpg)

 You can also fix this error by enabling .NET Framework 3.5\. The idea is that one of the snap-ins on your PC may need .NET Framework 3.5 to work. So, if the feature is disabled, you may encounter an error.

 Fortunately, you can easily enable the .NET Framework feature using the Turn Windows features on or off dialog. Here’s how to do it.

 To enable .NET Framework 3.5:

1. Press the **Win** key and type **Windows features** and click on **Turn Windows features on or off** from the search results.
2. In the **Windows Features** dialog, select the **.NET Framework 3.5 (include .NET 2.0 and 3.0)**.
3. Next, click the **Plus** icon to expand the section and select the options ‘**Windows Communications Foundation HTTP Activation**’ and **‘Windows Communications Foundation Non-HTTP Activation**’.
4. Next, click to **Apply** the changes and install the feature.
5. Once installed, you’ll be prompted to restart the computer. Restart your system, and the MMC snap-in should work now.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
## 3\. Check for and Repair Corrupt System Files

![DISM scan health restore health command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dism-scan-health-restore-health-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
<!-- affiliate ads end -->
 If you have one or more corrupt system files, it may cause issues with the system apps. You can run the System File Checker tool to determine if the problem is due to system file issues. It will scan and check the integrity of systems files and automatically repair them to fix the problem.

 Microsoft recommends running its built-in Windows image check and repair utility, Deployment Image Servicing and Management (DISM), before running the System File Checker utility.

 If you're not sure how to run either of these tools, we cover both in our guide on [how to repair corrupt Windows files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

<!-- affiliate ads begin -->
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Remove and Reinstall the Microsoft Visual C++ Redistributable

![repair microsoft visual c plus plus distributable package](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/repair-microsoft-visual-c-plus-plus-distributable-package.jpg)

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If the issue persists, try to fix and repair issues with the Visual C++ Redistributable package. If there are any issues with the package, it can cause the MMC snap-ins to stop working.

 To repair the Visual C++ Redistributable package:

1. Press **Win + R** to open Run.
2. Type "control" and click **OK** to open Control Panel.
3. In Control Panel, click on **Uninstall a program** under **Programs**.
4. Locate and select the **Microsoft Visual C++ Redistributable** entry and click **Uninstall**.
5. In the **Modify Setup** dialog, click **Repair**. The repair process may take a few minutes to complete.
6. Once done, restart your computer and check for any improvements.

 If the issue persists, reinstalling the Visual C++ Redistributable package may be required. To reinstall the package:

![uninstall microsoft visual c plus plus distributable package](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/uninstall-microsoft-visual-c-plus-plus-distributable-package.jpg)

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
1. Select the **Microsoft Visual C++ package** in Control Panel and click on **Uninstall**.
2. Click **Uninstall** in the **Modify Setup** dialog.
3. Click **Finish** to complete uninstallation. Repeat the process for all the Visual C++ Redistributable packages.
4. Once done, head over to the [Microsoft Visual C++ Redistributable package page](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170).
5. Download the latest version of the package available on your computer. Depending on your system compatibility, you can select from ARM64, X86, and X64 architecture versions.
6. Run the executable file to install the package and follow the on-screen instructions.
7. Once installed, restart your computer and check if MMC snap-ins are now working.

<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
## Fix the MMC Snap-In and Restore Your Administrative Tools on Windows

 This error is triggered when a snap-in malfunctions, which is often a case of broken registry configuration. To fix the issue, you can delete the broken registry sub-key for the affected snap-in. Additionally, enable/re-enable the .NET Framework 3.5\. If not, scan the system for file integrity issues with the DISM and System File Checker utility.

 Alternatively, you can use the Remote Server Administration Tools (RSAT), which has additional features. RSAT is only available on the Pro and Enterprise edition of the Windows OS. However, you can run a PowerShell script to install it on the Windows Home version easily.

 Sometimes, the error may also pop up after a Blue Screen of Death (BSOD), causing one or more apps to crash. This error often occurs if the registry configuration of the snap-in is malfunctioning. Here we show a few ways to fix to help you resolve the "MMC could not create the snap-in" error and restore administrative tools access in Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-pixel-perfect-playback-fixing-blurry-videos-on-smartphones/"><u>[New] 2024 Approved  Pixel Perfect Playback  Fixing Blurry Videos on Smartphones</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-creating-a-seamless-virtual-workspace-slack-filmora-combo-for-teams/"><u>[New] Creating a Seamless Virtual Workspace  Slack-Filmora Combo for Teams</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-get-more-from-tiny-screens-top-6-youtube-shorts-downloader-apps-for-2024/"><u>[New] Get More From Tiny Screens  Top 6 YouTube Shorts Downloader Apps for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-step-by-step-guide-to-joining-and-initiating-zoom-meetings-on-android/"><u>[Updated] 2024 Approved  Step-By-Step Guide to Joining & Initiating Zoom Meetings on Android</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-in-2024-20-easygoing-country-rhythms-to-boogie-down-and-unwind-on-tiktok/"><u>[Updated] In 2024, 20 Easygoing Country Rhythms to Boogie Down & Unwind on TikTok</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-easy-guide-to-start-product-review-channel/"><u>2024 Approved  Easy Guide to Start Product Review Channel</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-journey-through-visual-innovation-navigating-to-the-top-10-inexpensive-platforms-for-digital-painters/"><u>2024 Approved  Journey Through Visual Innovation  Navigating to the Top 10 Inexpensive Platforms for Digital Painters</u></a></li>
<li><a href="https://tech-hub.techidaily.com/chatgpt-your-virtual-partner-in-navigating-personal-health-7-perspectives/"><u>ChatGPT: Your Virtual Partner in Navigating Personal Health - 7 Perspectives</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-insights-selecting-the-right-os-for-gaming-glory/"><u>Expert Insights: Selecting the Right OS for Gaming Glory</u></a></li>
<li><a href="https://windows11.techidaily.com/festive-glamour-unveiled-in-decorative-windows/"><u>Festive Glamour Unveiled in Decorative Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-error-lost-access-to-ubisoft-game-launcher/"><u>Fixing Windows Error: Lost Access to Ubisoft Game Launcher</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-it-samsung-galaxy-f15-5g-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix It Samsung Galaxy F15 5G Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-error-code-e84-on-steam-for-windows/"><u>How to Fix the Error Code E84 on Steam for Windows</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-changefake-your-vivo-s18-pro-location-on-viber-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change/Fake Your Vivo S18 Pro Location on Viber | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-fix-apple-iphone-15-passcode-not-working-drfone-by-drfone-ios/"><u>In 2024, How to Fix Apple iPhone 15 Passcode not Working? | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-use-pokemon-go-joystick-on-poco-x6-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Pokemon Go Joystick on Poco X6? | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-instagram-engagement-strategies-with-these-powerful-25-hashtags/"><u>In 2024, Instagram Engagement Strategies with These Powerful 25 Hashtags</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-jump-into-todays-buzzing-tiktok-trials/"><u>In 2024, Jump Into Today's Buzzing TikTok Trials</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/innovate-your-intonation-ranking-the-best-audio-modification-apps-for-mobile/"><u>Innovate Your Intonation  Ranking the Best Audio Modification Apps for Mobile</u></a></li>
<li><a href="https://windows11.techidaily.com/innovative-synergy-windows-enables-iphone-and-ipad-with-desktop-power/"><u>Innovative Synergy: Windows Enables iPhone & iPad with Desktop Power</u></a></li>
<li><a href="https://windows11.techidaily.com/instant-wallpaper-update-the-simple-windows-method/"><u>Instant Wallpaper Update: The Simple Windows Method</u></a></li>
<li><a href="https://windows11.techidaily.com/launching-wordpad-windows-users-handbook/"><u>Launching WordPad: Windows User's Handbook</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11s-fast-flip-buttons/"><u>Mastering Windows 11'S Fast Flip Buttons</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-in-moving-between-focused-and-unfocused-states-within-windows-terminal/"><u>Mastery in Moving Between Focused and Unfocused States Within Windows Terminal</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-muted-powershell-scripts-four-tactics-to-counter-error-message/"><u>Mastery Over Muted PowerShell Scripts: Four Tactics to Counter Error Message</u></a></li>
<li><a href="https://windows11.techidaily.com/minmax-cpu-states-navigating-windows-power-control/"><u>Min/Max CPU States: Navigating Windows Power Control</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-tasks-like-a-pro-admin-mode-for-task-manager-on-windows-11/"><u>Navigate Tasks Like a Pro: Admin Mode for Task Manager on Windows 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/nikon-j5-in-4k-the-ultimate-camera-review/"><u>Nikon J5 in 4K  The Ultimate Camera Review</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/precision-in-capturing-androids-best-techniques/"><u>Precision in Capturing  Android's Best Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-glance-at-recent-files-in-windows/"><u>Quick Glance at Recent Files in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-disappearing-results-from-windows-1011-search-tool/"><u>Solving Disappearing Results From Windows 10/11 Search Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-the-invalid-system-id-issue-on-windows-11/"><u>Solving the Invalid System ID Issue on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-enforce-local-policies-to-a-specific-user-in-windows-11/"><u>Steps to Enforce Local Policies to a Specific User in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-microsoft-store-glitch-error-code-0x800704cf/"><u>Steps to Resolve Microsoft Store Glitch (Error Code 0X800704CF)</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-repairing-crashing-ccleaner-in-windows-1011/"><u>Strategies for Repairing Crashing CCleaner in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-tracking-storage-spent-on-apps/"><u>Strategies for Tracking Storage Spent on Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-presentations-windows-11-remove-pin-lock/"><u>Streamline Presentations: Windows 11, Remove PIN Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-screen-hotkey-based-program-minimization-techniques/"><u>Streamline Your Screen: Hotkey-Based Program Minimization Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-guidance-for-choosing-between-nvidia-gamestudio-drivers/"><u>Tailored Guidance for Choosing Between Nvidia Game/Studio Drivers</u></a></li>
<li><a href="https://windows11.techidaily.com/unearthing-bsod-traces-within-windows-vista2008/"><u>Unearthing BSOD Traces Within Windows Vista/2008</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-productivity-a-guide-to-making-multiple-directories-at-once-in-windows/"><u>Unleashing Productivity: A Guide to Making Multiple Directories at Once in Windows</u></a></li>
<li><a href="https://some-skills.techidaily.com/venturing-into-new-realities-best-metaverse-headsets-guide-for-2024/"><u>Venturing Into New Realities  Best Metaverse Headsets Guide for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-10-product-key-our-guide-to-the-top-deals/"><u>Windows 10 Product Key: Our Guide to the Top Deals</u></a></li>
<li><a href="https://windows11.techidaily.com/zeroing-out-wsl-complete-uninstallation-in-windows-11/"><u>Zeroing Out WSL: Complete Uninstallation in Windows 11</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>