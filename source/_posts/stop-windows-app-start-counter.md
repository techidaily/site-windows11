---
title: Stop Windows App Start Counter
date: 2024-08-08T06:08:17.749Z
updated: 2024-08-09T06:08:17.749Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Stop Windows App Start Counter
excerpt: This Article Describes Stop Windows App Start Counter
keywords: Stop Window Apps,Halt App Launches,Prevent Windows Starts,Block App Initialization,Disable Windows Opening,End App Start Countdown,Prevent Startup Apps
thumbnail: https://thmb.techidaily.com/669bc1413d235f8908afbf69f357ad5578fda1c3066e7cdb610eb41a93c8a8ff.jpeg
---

## Stop Windows App Start Counter

 Windows records and monitors how often you use particular applications. While this may enhance productivity, it does also raise privacy concerns.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.

## 1\. How to Disable App Launch Tracking Through Windows Settings

 To disable app launch tracking, open the Start menu and type **Settings** in the search bar. Select the **Settings** option in the search results. In the left-side menu, click the **Privacy & security** tab. Then click **General** under the Windows permissions section.

 On the next page, locate **Let Windows improve Start and search results by tracking app launches** and toggle it off.

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->
![Disable App Launch Tracking through Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-through-windows-settings.jpg)

 After making the changes, Windows will stop tracking and recording your app launches.

 If you ever need to re-enable the feature, repeat the same steps and toggle the switch back on. This will enable Windows to start tracking and recording your app launches.

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. How to Disable App Launch Tracking Using the Group Policy Editor

 You can also disable app launch tracking using the Group Policy Editor. But this method is only available in the Pro and Enterprise versions.

 If you don't have these Windows versions, [turn on the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) and follow these instructions.

1. Press **Win + R** on your keyboard to open the Run dialog box.
2. Type **gpedit.msc** in the text box and click **OK**.
3. In the Group Policy Editor window, navigate to the following path:  
`User Configuration > Administrative Templates > Windows Components > Edge UI​`
4. Go to the right side of the window and double-click on **Turn off tracking of app usage**.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->
![Disable App Launch Tracking using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-using-group-policy-editor.jpg)
5. On the next page, check the **Enabled** box.
6. Click **Apply** \> **OK** to save your changes.

 This way, you can disable app launch tracking using the group policy editor.

 To enable the feature again, follow the same steps and navigate to _User Configuration > Administrative Templates > Windows Components > Edge UI_. Then double-click on **Turn off tracking of app usage** and check the **Not Configured** or **Disabled** option.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. How to Disable App Launch Tracking Through the Registry Editor

 Registry Editor is another method to disable app launch tracking. The process is tricky as you need to manually modify the registry keys and one wrong move can cause serious problems. So, we suggest you [create a backup of the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it.

 To disable app launch tracking through Registry Editor, do the following:

1. Right-click on Start and select **Run** from the menu list.
2. Type **regedit** in the text field and click **OK**. This will [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. When the UAC window appears, click **Yes** to grant privileges.
4. In the left pane, navigate to the following path:  
`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. If you don't find the Advanced folder, right-click on **Explorer** and select **New** \> **Key**.
6. Name it **Advanced** and press the Enter key.
7. Now, right-click on the **Advanced** folder and choose **New** \> **DWORD (32-bit) Value**.
8. Name it **Start\_TrackProgs** and hit Enter.  
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Disable App Launch Tracking through the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-through-the-registry-editor.jpg)
9. Double-click on the **Start\_TrackProgs** DWORD and set its value to **0**.

 Once you're done, close the Registry Editor and restart your computer. Now, Windows won't track or record app launches.

 If you ever want to turn back on app launch tracking, double-click on the **Start\_TrackProgs** DWORD in Registry Editor and set its value to **1**. After that, restart your system for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
## Windows Won’t Track or Monitor the Apps You Use

 If you don't want to mess with the Registry Editor or Group Policy Editor, use the Settings option to disable app launch tracking. Choose the method you prefer and enjoy a tracking-free experience.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-sure.techidaily.com/024-approved-trick-automated-audiences-into-authentic-engagement/"><u>[New] 2024 Approved  Trick Automated Audiences Into Authentic Engagement</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-creative-annotation-warping-tactics/"><u>[New] Creative Annotation Warping Tactics</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-decoding-the-social-code-top-30-tips-for-marketing-mastery/"><u>[New] In 2024, Decoding the Social Code  Top 30 Tips for Marketing Mastery</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-dish-to-screen-your-recipe-video-blueprint/"><u>[New] In 2024, Dish to Screen  Your Recipe Video Blueprint</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-the-art-of-filmmaking-demystified-on-youtube/"><u>[New] The Art of Filmmaking Demystified on YouTube</u></a></li>
<li><a href="https://win-answers.techidaily.com/solved-msedgeexe-application-error-on-windows/"><u>[Solved] msedge.exe Application Error on Windows</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-masterclass-series-incorporating-timekeepers-into-live-production/"><u>[Updated] 2024 Approved  Masterclass Series  Incorporating Timekeepers Into Live Production</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-discoemote-studio-crafting-the-ultimate-emojis/"><u>[Updated] DiscoEmote Studio - Crafting the Ultimate Emojis</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-how-to-add-stickers-to-instagram-story-and-post/"><u>[Updated] How to Add Stickers to Instagram Story and Post?</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-a-deep-dive-into-the-world-of-youtubes-minis/"><u>[Updated] In 2024, A Deep Dive Into the World of Youtube's Minis</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-laugh-ledger-the-ultimate-list-of-hilarious-tweets/"><u>[Updated] In 2024, Laugh Ledger  The Ultimate List of Hilarious Tweets</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-overcoming-obs-fullscreen-issues/"><u>[Updated] In 2024, Overcoming OBS Fullscreen Issues</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-mastering-pc-gaming-capturing-your-adventures-on-win10-for-2024/"><u>[Updated] Mastering PC Gaming  Capturing Your Adventures on Win10 for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-enhancing-workflow-meeting-management-on-zoom/"><u>2024 Approved  Enhancing Workflow  Meeting Management on Zoom</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-history-in-action-top-7-engaging-civilization-wars/"><u>2024 Approved  History in Action  Top 7 Engaging Civilization Wars</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-innovative-hexa-drones-2023s-best/"><u>2024 Approved  Innovative Hexa-Drones 2023'S Best</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-quick-scan-recorder-for-chrome-devices/"><u>2024 Approved  Quick Scan Recorder for Chrome Devices</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-the-artisans-secret-to-viral-youtube-success/"><u>2024 Approved  The Artisan's Secret to Viral YouTube Success</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-tiny-film-plot-proposal/"><u>2024 Approved  Tiny Film Plot Proposal</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-undo-history-rewinding-videos-on-apple-devices/"><u>2024 Approved  Undo History  Rewinding Videos on Apple Devices</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/a-guide-motorola-razr-40-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>A Guide Motorola Razr 40 Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/bridging-the-gap-an-introduction-to-av1-for-2024/"><u>Bridging the Gap  An Introduction to AV1 for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/canons-lut-collection-maximize-image-impact-free-and-paid-choices/"><u>Canon’s LUT Collection  Maximize Image Impact - FREE & Paid Choices</u></a></li>
<li><a href="https://windows11.techidaily.com/drive-discretion-in-windows-1011/"><u>Drive Discretion in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/dual-display-designs-selective-screen-splendor-in-win-1011/"><u>Dual-Display Designs: Selective Screen Splendor in Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/dynamic-tray-display-live-system-usage-statistics-on-desktop/"><u>Dynamic Tray Display: Live System Usage Statistics on Desktop</u></a></li>
<li><a href="https://video-capture.techidaily.com/easy-guide-to-converting-mov-files-to-different-formats-on-win-11/"><u>Easy Guide to Converting MOV Files to Different Formats on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-steps-to-bypass-renaming-restrictions-on-windows-11/"><u>Easy Steps to Bypass Renaming Restrictions on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-data-management-controlling-ntfs-compression/"><u>Efficient Data Management: Controlling NTFS Compression</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-fixes-for-the-frozen-search-in-windows-11-settings-app/"><u>Efficient Fixes for the Frozen Search in Windows 11 Settings App</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-managing-frame-rates-to-reduce-delay/"><u>Efficiently Managing Frame Rates to Reduce Delay</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-win-based-open-ai-discussions/"><u>Effortless WIN-Based Open AI Discussions</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-multisystem-video-processing-on-a-single-windows-setup-with-tdarr/"><u>Elevate Multisystem Video Processing on a Single Windows Setup with Tdarr</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-sound-top-5-apps-for-windows-beyond-maxed-volume/"><u>Elevate Sound: Top 5 Apps for Windows Beyond Maxed Volume</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-account-unlock-admin-potential/"><u>Elevate Your Account - Unlock Admin Potential</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-vm-game-six-key-tips-for-windows-optimization/"><u>Elevate Your VM Game: Six Key Tips for Windows Optimization</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-mouse-interaction-with-clicklock-in-windows/"><u>Elevating Mouse Interaction with ClickLock in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-ssd-speed-in-windows-using-ssd-fresh/"><u>Elevating SSD Speed in Windows Using SSD Fresh</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-vintage-gameplay-experience-with-achievement-boost-via-retroarch/"><u>Elevating Vintage Gameplay Experience with Achievement Boost via Retroarch</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-user-not-valid-error-on-windows-11-and-11/"><u>Eliminating 'User Not Valid' Error on Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-error-code-0x80300024-from-pc/"><u>Eliminating Error Code: 0X80300024 From PC</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-error-unknown-value-in-windows-systems/"><u>Eliminating Error: Unknown Value in Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-gpu-freeze-fix-code-0x887a0006/"><u>Eliminating GPU Freeze: Fix Code 0X887A0006</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-shutdown-restart-and-sign-out-errors-by-suspicious-apps/"><u>Eliminating Shutdown, Restart, and Sign Out Errors by Suspicious Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/enabledisable-tpm-support-within-virtualbox-70-settings/"><u>Enable/Disable TPM Support Within VirtualBox 7.0 Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-pc-finding-leverage-everywhereapp/"><u>Enhance PC Finding: Leverage EverywhereApp</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-the-real-time-update-speed-of-task-manager/"><u>Enhance the Real-Time Update Speed of Task Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-user-experience-add-portable-software-to-windows/"><u>Enhance User Experience: Add Portable Software to Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-win-gpgpu-capabilities-using-1-6-tools/"><u>Enhance Win GPGPU Capabilities Using #1-#6 Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-your-typing-speed-via-typingaid-tactics/"><u>Enhance Your Typing Speed via TypingAid Tactics</u></a></li>
<li><a href="https://windows11.techidaily.com/enhanced-docker-functionality-via-optimized-wsl-2-use/"><u>Enhanced Docker Functionality via Optimized WSL 2 Use</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-alt-code-function-on-windows-46-characters/"><u>Enhancing ALT Code Function on Windows (46 Characters)</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-buffer-free-browsing-chromium-and-youtube/"><u>Enhancing Buffer-Free Browsing: Chromium & YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-discord-performance-on-windows-systems/"><u>Enhancing Discord Performance on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-graphics-with-updated-amd-drivers-windows-edition/"><u>Enhancing Graphics with Updated AMD Drivers, Windows Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-power-indicators-set-up-fully-charged-notifications-on-windows-11/"><u>Enhancing Power Indicators: Set up Fully Charged Notifications on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-productivity-grouped-software-installs-on-windows-11-using-winstall/"><u>Enhancing Productivity: Grouped Software Installs on Windows 11 Using Winstall</u></a></li>
<li><a href="https://windows11.techidaily.com/enlighten-your-way-to-printer-success-on-windows-11/"><u>Enlighten Your Way to Printer Success on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-clear-audio-a-quick-guide-for-windows-users/"><u>Ensuring Clear Audio: A Quick Guide for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-proper-rights-in-fixing-insufficient-privilege-install-errors/"><u>Ensuring Proper Rights in Fixing Insufficient Privilege Install Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicating-service-did-not-respond-error-in-windows-os/"><u>Eradicating Service Did Not Respond Error in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-advice-for-resolving-cc-problems-in-the-latest-os/"><u>Essential Advice for Resolving CC Problems in the Latest OS</u></a></li>
<li><a href="https://fake-location.techidaily.com/full-guide-to-fix-itoolab-anygo-not-working-on-tecno-pop-7-pro-drfone-by-drfone-virtual-android/"><u>Full Guide to Fix iToolab AnyGO Not Working On Tecno Pop 7 Pro | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/hacking-the-meme-game-master-kinemaster-skills/"><u>Hacking the Meme Game  Master KineMaster Skills</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-use-device-manager-to-reinstall-drivers-on-windows-11-by-drivereasy-guide/"><u>How to use Device Manager to reinstall drivers on Windows 11</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-masterful-mac-microphone-software-ranking-the-excellent-five/"><u>In 2024, Masterful Mac Microphone Software  Ranking the Excellent Five</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-mastering-image-quality-a-guide-without-watermarks/"><u>In 2024, Mastering Image Quality  A Guide Without Watermarks</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-spark-ar-graphics-mastering-the-art-with-downloadable-color-lookups/"><u>In 2024, Spark AR Graphics  Mastering the Art with Downloadable Color Lookups</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-ultimate-guide-to-budget-friendly-4k-cameras/"><u>In 2024, Ultimate Guide to Budget-Friendly 4K Cameras</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/optimal-audio-options-for-online-speakers-for-2024/"><u>Optimal Audio Options for Online Speakers for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/reasons-why-pokemon-gps-does-not-work-on-motorola-edge-2023-drfone-by-drfone-virtual-android/"><u>Reasons why Pokémon GPS does not Work On Motorola Edge 2023? | Dr.fone</u></a></li>
<li><a href="https://win-able.techidaily.com/solving-the-epic-games-launcher-error-a-step-by-step-guide/"><u>Solving the Epic Games Launcher Error - A Step-by-Step Guide</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-9-vivo-v30-lite-5g-monitoring-apps-for-parental-controls-drfone-by-drfone-virtual-android/"><u>Top 9 Vivo V30 Lite 5G Monitoring Apps for Parental Controls | Dr.fone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/visual-storytelling-on-facebook-crafting-compelling-slideshows-for-2024/"><u>Visual Storytelling on Facebook  Crafting Compelling Slideshows for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>