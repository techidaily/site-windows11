---
title: "Windows 11: Incorporating a God Mode Shortcut"
date: 2024-07-29T04:21:56.148Z
updated: 2024-07-30T04:21:56.148Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows 11: Incorporating a God Mode Shortcut"
excerpt: "This Article Describes Windows 11: Incorporating a God Mode Shortcut"
keywords: Win11 GodMode,Windows GodShortcut,ModifyWin11,QuickGodModi,AccessWin11God,CreateWin11Short,ShortcutToGodMode
thumbnail: https://thmb.techidaily.com/a27b3a3de27d6b4c9a23aaf5bc90c6e51b30c3f5343bae186756d50b06815cf1.jpg
---

## Windows 11: Incorporating a God Mode Shortcut

 God Mode enables you to access hundreds of Control Panel applets from a single All Tasks window. That’s a handy thing to activate in Windows 11 for accessing Control Panel settings and creating shortcuts that open them.

 Many users activate God Mode by setting up desktop shortcuts that open the All Tasks window. However, you can instead add a **God Mode** option to the desktop’s context menu in Windows 11\. Then the All Tasks window will be directly accessible on your right-click menu. This is how you can add God Mode to Windows 11’s context menu.

## How to Add God Mode to the Context Menu by Manually Editing the Registry

 You can add God Mode to Windows 11’s desktop context menu by manually tweaking the registry. The tweaking required is relatively simple to apply and involves adding a couple of new registry entries to the Shell key. Follow these steps to manually add God Mode to Windows 11’s context menu:

1. Open the Registry Editor (see [how to open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) for instructions).
2. Click in the address bar at the top of Registry Editor to delete the current key location.
3. Input this Shell key path in the address bar and hit **Enter**:  
`Computer\HKEY_CLASSES_ROOT\DesktopBackground\Shell\`
4. Right-click on **Shell** in Registry Editor’s navigation sidebar to select **New** and **Key**.  
![The New > Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/new-key-options.jpg)
5. Type **God Mode** in the key’s text box.

1. Right-click **God Mode** and select the **New** \> **Key** context menu options again.
2. Input **command** within the subkey’s text box.  
![The God Mode registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/god-mode-key.jpg)
3. Double-click on the **(Default)** string for the new command key you’ve added to the registry.
4. Input **explorer** **shell:::{ED7BA470-8E54-465E-825C-99712043E01C}** within the **Data value** box and click **OK**.  
<!-- affiliate ads begin -->

<!-- affiliate ads end -->
![The Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/edit-string-window.jpg)
5. Click on the Registry Editor’s **X** button.

 Check out the new **God Mode** option on your context menu for opening Task View. Right-click somewhere on the desktop background image and select **Show more options**. Then select **God Mod** to bring up the **Task View** window. You can open a multitude of Control Panel applets from there.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->
![A God Mode context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/god-mode-option.jpg)

 If you ever change your mind about having a **God Mode** context menu option, open the Shell key in Registry Editor again. Then right-click on the **God Mode** key you added and select delete. Click **Yes** to erase the **God Mode** key along with its **command** subkey.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537546&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/7_copy_2_2_hdpro.png" border="0">HD Video Converter Factory Pro</a>
<!-- affiliate ads end -->
![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-delete-option.jpg)

## How to Add God Mode to the Context Menu With Right-Click Extender

 The manual registry tweak method is straightforward, but you can add God Mode to the context menu with third-party software instead if preferred. Right-Click Extender is customization software that includes an option for adding God Mode to the context menu. This is how you can add God Mode to your context menu with Right-Click Extender:

1. Open this [Right-Click Extender](https://www.softpedia.com/get/Tweak/System-Tweak/Right-Click-Extender.shtml) download page.
2. Click on the **Download** and **Secure Download (US)** options and download the file.
3. Extract the Right-Click Extender archive by following the instructions within this guide to [unzipping ZIP files in Windows](https://www.makeuseof.com/unzip-files-windows-10/).  
![The Extract Compressed (Zipped) Folders window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/extract-compressed-zip-folder.jpg)
4. Open the extracted Right-Click Extender directory and its Right-Click Extender v2 subfolder.
5. Double-click the Right-Click Extender v2 application file.
6. Click on the **Desktop** tab in Right-Click Extender.
7. Select the **All Tasks (GodMode)** setting and its Icon checkbox.  
<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Right-Click Extender v2 window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-all-tasks-setting.jpg)
8. Press the green **Apply** button.

 Now you’ll see a new **God Mode** option on Windows 11’s classic context menu. This option will also have an icon by it. Click on **God Mode** to view the list of Control Panel applets.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->
## How to Create Control Panel Shortcuts From God Mode's All Tasks Window

 The Task View window the God Mode context menu option opens makes hundreds of Control Panel applets more accessible. You can open whatever Control Panel settings you need from that window. However, the list of applets shown in that window is quite long.

 Task View makes it easy to create desktop shortcuts for opening the Control Panel applets you need to access more regularly. To do so, left-click an applet or utility in the Task View window, drag it onto the desktop, and release the mouse button. Then you can click on the desktop shortcut to open its Control Panel applet whenever needed.

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The All Tasks (God Mode) window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-all-tasks-window.jpg)

## Make the Most of God Mode on Windows

 Adding God Mode to your desktop’s context menu will enable you to access a plethora of Control Panel applets and tools within a single window in a couple of clicks. That will save you from rummaging through the Control Panel to find certain applets and settings when needed. Plus, you can make more essential Control Panel applets even more accessible by creating shortcuts for them from the Task View window.

 Many users activate God Mode by setting up desktop shortcuts that open the All Tasks window. However, you can instead add a **God Mode** option to the desktop’s context menu in Windows 11\. Then the All Tasks window will be directly accessible on your right-click menu. This is how you can add God Mode to Windows 11’s context menu.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-alives-low-residue-sound-technique/"><u>[New] 2024 Approved  Alive's Low-Residue Sound Technique</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-finding-the-social-beacons-in-your-interests-digital-landscape/"><u>[New] 2024 Approved  Finding the Social Beacons in Your Interests’ Digital Landscape</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-recording-revolution-tactics-for-extracting-live-data/"><u>[New] 2024 Approved  Recording Revolution  Tactics for Extracting LIVE Data</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-fabricate-funnier-photos/"><u>[New] Fabricate Funnier Photos</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-navigating-content-size-on-igtv-top-5-expert-tips-to-consider/"><u>[New] Navigating Content Size on IGTV  Top 5 Expert Tips to Consider</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-a-pictures-worth-a-thousand-dollars-online-top-photo-cloud-services-reviewed/"><u>[Updated] A Picture's Worth a Thousand Dollars Online  Top Photo Cloud Services Reviewed</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-elevating-your-brand-with-intriguing-instagram-puzzle-feeds/"><u>[Updated] Elevating Your Brand with Intriguing Instagram Puzzle Feeds</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-streamline-capturing-and-saving-tweets-visuals-on-android-for-2024/"><u>[Updated] Streamline  Capturing and Saving Tweets' Visuals on Android for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-the-ultimate-list-of-superior-real-time-streaming-networks/"><u>[Updated] The Ultimate List of Superior Real-Time Streaming Networks</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-infographic-dji-mavic-air-vs-dji-spark-a-gamer-changer-again/"><u>2024 Approved  [Infographic] DJI Mavic Air Vs. DJI Spark - A Gamer Changer Again</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-best-practices-in-altering-igtv-video-titles/"><u>2024 Approved  Best Practices in Altering IGTV Video Titles</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-top-5-effortlessly-converted-gif-to-professional-videos-online/"><u>2024 Approved  Top 5 Effortlessly Converted  GIF to Professional Videos Online</u></a></li>
<li><a href="https://extra-resources.techidaily.com/9-ways-to-facebook-video-black-screen-issues-on-chromesafarifir/"><u>9 Ways to Facebook Video Black Screen Issues on Chrome/Safari/Fir</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-your-workflow-with-windows-11s-widget-toolbar/"><u>Boost Your Workflow with Windows 11'S Widget Toolbar</u></a></li>
<li><a href="https://windows11.techidaily.com/breathing-life-into-winget-a-windows-11-solution/"><u>Breathing Life Into Winget: A Windows 11 Solution</u></a></li>
<li><a href="https://extra-tips.techidaily.com/brief-cinematic-story-outline-for-2024/"><u>Brief Cinematic Story Outline for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-i-recover-permanently-deleted-photos-from-samsung-galaxy-a05-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>Can I recover permanently deleted photos from Samsung Galaxy A05</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-old-user-credentials-issue-on-win-11-os/"><u>Clearing Up 'Old User Credentials' Issue on Win 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-breakdown-using-toolbar-in-mspcm-on-windows-11/"><u>Comprehensive Breakdown: Using Toolbar in MSPCM on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-alternate-pdf-reader-on-windows/"><u>Configuring Alternate PDF Reader on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/decreasing-the-impact-of-high-cpu-tiworkerexe-applications/"><u>Decreasing the Impact of High-CPU TiWorker.exe Applications</u></a></li>
<li><a href="https://windows11.techidaily.com/detailed-guide-extracting-device-ids-on-windows-pcs/"><u>Detailed Guide: Extracting Device IDs on Windows PCs</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/did-your-iphone-11-pro-max-passcode-change-itself-unlock-it-now-by-drfone-ios/"><u>Did Your iPhone 11 Pro Max Passcode Change Itself? Unlock It Now</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/disabling-iphone-13-pro-max-parental-restrictions-withwithout-password-by-drfone-ios/"><u>Disabling iPhone 13 Pro Max Parental Restrictions With/Without Password</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-versatility-top-10-innovative-ways-to-use-powertoys-tools/"><u>Discover Versatility: Top 10 Innovative Ways to Use PowerToys Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/dismantling-tpm-in-win11-using-the-power-of-rufus/"><u>Dismantling TPM in Win11 Using the Power of Rufus</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/dividedlens-testimonial-for-2024/"><u>DividedLens Testimonial for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-visuals-perfect-windows-desktop-backdrops/"><u>Elevating Visuals: Perfect Windows Desktop Backdrops</u></a></li>
<li><a href="https://windows11.techidaily.com/elusive-network-how-to-conceal-on-windows-pc/"><u>Elusive Network: How to Conceal on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-cyber-safety-trustable-domains-on-windows-11/"><u>Enhance Cyber Safety: Trustable Domains on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-for-restarting-windows-update-process/"><u>Essential Tips for Restarting Windows Update Process</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-windows-version-numbers-post-update/"><u>Exploring Windows Version Numbers Post-Update</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-installation-failed-in-discord-for-windows-os/"><u>Fix 'Installation Failed' In Discord for Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-sync-errors-in-nvidia-cp-windows-11/"><u>Fixing Sync Errors in NVidia CP Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-fatal-discord-errors-on-windows-1011-a-comprehensible-guide/"><u>Handling Fatal Discord Errors on Windows 10/11: A Comprehensible Guide</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-my-oneplus-11-5g-location-is-wrong-drfone-by-drfone-virtual-android/"><u>How to Fix My OnePlus 11 5G Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reprogram-windows-11s-preferred-programs-effectively/"><u>How to Reprogram Windows 11'S Preferred Programs Effectively</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-a-found-iphone-6-plus-drfone-by-drfone-ios/"><u>How To Unlock A Found iPhone 6 Plus? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-card-on-tecno-camon-20-pro-5g-online-without-jailbreak-by-drfone-android/"><u>How to Unlock SIM Card on Tecno Camon 20 Pro 5G online without jailbreak</u></a></li>
<li><a href="https://windows11.techidaily.com/illuminating-windows-multi-monitor-setup-selecting-the-best-control-tools/"><u>Illuminating Windows Multi-Monitor Setup: Selecting the Best Control Tools</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-5-easy-ways-to-change-location-on-youtube-tv-on-google-pixel-8-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Easy Ways to Change Location on YouTube TV On Google Pixel 8 | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-full-guide-to-unlock-your-oppo-a1x-5g-by-drfone-android/"><u>In 2024, Full Guide to Unlock Your Oppo A1x 5G</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-come-up-with-the-best-pokemon-team-on-motorola-moto-g14-drfone-by-drfone-virtual-android/"><u>In 2024, How to Come up With the Best Pokemon Team On Motorola Moto G14? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-oppo-a79-5g-to-outlook-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Oppo A79 5G to Outlook | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-ingenious-strategies-for-selecting-trailer-soundtracks/"><u>In 2024, Ingenious Strategies for Selecting Trailer Soundtracks</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-navigating-the-art-of-film-making-on-facebook/"><u>In 2024, Navigating the Art of Film Making on Facebook</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-apple-iphone-8-drfone-by-drfone-virtual-ios/"><u>In 2024, The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Apple iPhone 8 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/innovative-2024-windows-devices-you-cant-miss/"><u>Innovative 2024 Windows Devices You Can't Miss</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/launch-live-fb-broadcast-from-any-device-with-obs-guide/"><u>Launch Live FB Broadcast From Any Device with OBS Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/masterful-dns-management-in-windows-11/"><u>Masterful DNS Management in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-win-11-issue-resolution/"><u>Mastering the Art of WIN 11 Issue Resolution</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-correct-event-viewer-glitches-in-win-11/"><u>Methods to Correct Event Viewer Glitches in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-windows-package-unopenable-woes/"><u>Navigating Through Windows Package Unopenable Woes</u></a></li>
<li><a href="https://windows11.techidaily.com/personalizing-win11-screen-saver-settings/"><u>Personalizing Win11 Screen Saver Settings</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/protect-your-privacy-with-bitraser-drive-eraser-shop-today/"><u>Protect Your Privacy with BitRaser Drive Eraser - Shop Today</u></a></li>
<li><a href="https://review-topics.techidaily.com/quickly-remove-google-frp-lock-on-realme-12-5g-by-drfone-android-unlock-remove-google-frp/"><u>Quickly Remove Google FRP Lock on Realme 12 5G</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/ranchers-revelry-best-friendly-farming-titles-for-gathering-pals/"><u>Ranchers' Revelry  Best Friendly Farming Titles for Gathering Pals</u></a></li>
<li><a href="https://windows11.techidaily.com/revisiting-exe-execution-hurdles-in-windows/"><u>Revisiting EXE Execution Hurdles in Windows</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/scripting-your-storys-visual-heartbeat-at-home-for-2024/"><u>Scripting Your Story's Visual Heartbeat at Home for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-windows-11s-frustrating-5ghz-link-failures/"><u>Solving Windows 11'S Frustrating 5GHz Link Failures</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-quieting-geforces-visual-flourishes/"><u>Step-By-Step: Quieting GeForce's Visual Flourishes</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-overcome-win-11s-store-error-x00000000/"><u>Steps to Overcome Win 11'S Store Error X00000000</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-and-personalize-the-ultimate-desktop-guide-for-win11-users/"><u>Streamline & Personalize: The Ultimate Desktop Guide for Win11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-windows-experience-by-fixing-prerequisites-first/"><u>Streamline Windows Experience by Fixing Prerequisites First</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-address-game-pass-connection-errors-in-windows/"><u>Techniques to Address Game Pass Connection Errors in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/trimming-down-linux-overheads-in-android-wsl-setup/"><u>Trimming Down Linux Overheads in Android WSL Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshoot-non-functional-windows-security-on-win-11/"><u>Troubleshoot Non-Functional Windows Security on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unblock-windows-task-scheduler-issues-quickly/"><u>Unblock Windows Task Scheduler Issues Quickly</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-lumafusion-offers-various-look-up-table-presets-or-luts-such-as-filmic-delog-and-filmic-deflat-and-several-stylistic-luts-for-use-with-neutral-use-v/"><u>Updated LumaFusion Offers Various Look Up Table Presets, or LUTs, Such as FiLMiC deLog and FiLMiC DeFlat, and Several Stylistic LUTs for Use with Neutral Use Video. You Can Also Manually Add the LUTs</u></a></li>
<li><a href="https://windows11.techidaily.com/vanishing-acts-concealing-keys-without-notice/"><u>Vanishing Acts: Concealing Keys Without Notice</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-developers-rejoice-unveiling-microsoft-copilot/"><u>Windows Developers Rejoice: Unveiling Microsoft Copilot</u></a></li>
</ul></div>
