---
title: Navigate to Sound Mastery with Windows 11 Volume Control
date: 2024-08-22T21:38:04.148Z
updated: 2024-08-23T21:38:04.148Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigate to Sound Mastery with Windows 11 Volume Control
excerpt: This Article Describes Navigate to Sound Mastery with Windows 11 Volume Control
keywords: Sound Mastery Windows 11,Windows 11 Audio Control,Volume Management Windows,Mastering Windows Volume,Sound Control Windows 11,Windows 11 Sounds Adjust,Proficient Windows Volumes
thumbnail: https://thmb.techidaily.com/4c2c83dc76ea031999e2259b4bcb5ed3cf0b94afcaf6c4463fe69d20d044b80c.jpg
---

## Navigate to Sound Mastery with Windows 11 Volume Control

 Remember the old volume mixer which you could access from the system tray notifications? Windows 11 seems to be missing that ever since its release. When you click on the Volume icon in the Action Center, you only see an option to change the sound output device. There are no means to directly access the volume mixer from there. But Microsoft isn’t done with the volume settings on Windows 11.

 In a new experimental feature, Microsoft is revamping the sound settings in the Action Center. You will be able to switch output devices and adjust the volume of each of the apps listed in the Volume Mixer. Wondering how to get the feature on your system? Here's how.

## Why Do You Need a Volume Mixer in Action Center?

 The present state of volume settings in Windows 11 is quite lackluster. You can only adjust the volume of the system and cycle between multiple audio devices. For opening any other settings, even something as trivial as a volume mixer: you need to dive deep into system sound settings.

 It is baffling how Microsoft missed something so crucial in Windows 11\. These missing volume settings gave rise to apps like[EarTrumpet](https://apps.microsoft.com/store/detail/9NBLGGH516XP?hl=en-us&gl=US&ranMID=24542&ranEAID=nOD%2FrLJHOac&ranSiteID=nOD%5FrLJHOac-kFXVOqcgmh%5FMcUkQutiXeg&epi=nOD%5FrLJHOac-kFXVOqcgmh%5FMcUkQutiXeg&irgwc=1&OCID=AID2200057%5Faff%5F7593%5F1243925&activetab=pivot%3Aoverviewtab&ranMID=43674&ranEAID=RIg0ReKk7DI&ranSiteID=RIg0ReKk7DI-SCKmwfBirhtH6ExPZ%5FEJzQ&epi=RIg0ReKk7DI-SCKmwfBirhtH6ExPZ%5FEJzQ&irgwc=1&OCID=AID2200057%5Faff%5F7795%5F1243925&tduid=%28ir%5F%5Fwdc06dt9wokfbgsgxdjh3vgezv2x6gcmodrafe9c00%29%287795%29%281243925%29%28RIg0ReKk7DI-SCKmwfBirhtH6ExPZ%5FEJzQ%29%28%29&irclickid=%5Fwdc06dt9wokfbgsgxdjh3vgezv2x6gcmodrafe9c00) which offered rich sound customization settings. Along with that, you can even access the old volume mixers, adjust the sound levels of each app, and map shortcuts.

![Old Volume Settings in Action Center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/old-volume-settings-in-action-center.jpg)

 However, Microsoft is slowly identifying such missing features in Windows 11 and is adding an inbuilt solution for it. Recently,[Microsoft began testing an RGB lighting feature](https://www.makeuseof.com/enable-rgb-lighting-controls-windows-11/) that will eliminate the need for third-party customization apps. So, it is pretty clear that Microsoft wants to reduce the reliance on third-party apps for vital system features and tweaks.

## How to Enable the Volume Mixer in Windows 11's Action Center

 To enable the volume mixer in Windows 11, you will need to do the following:

<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. Download the Latest Windows Insider Build and ViVeTool

 Currently, the volume mixer feature is an experimental feature hidden in Windows Insider build 25295\. So, you must install this Windows Insider build or a higher version to enable this feature. We recommend[using UUP Dump to download Windows Insider builds without subscribing to Windows Insider](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/) .

 Microsoft recently expanded the Insider program with a new Canary channel, and it makes it difficult to downgrade to another channel. So, you can use UPP Dump to avoid this program and get builds directly.

 You will also need to download[ViVeTool from GitHub](https://github.com/thebookisclosed/ViVe/releases) to enable the experimental volume mixer feature. It is a command-line tool that can both activate and deactivate experimental Windows features. However, extract the tool to an easily accessible location in the C drive.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->
### 2\. Enable Volume Mixer in Windows Using ViVeTool

After you have the ViVeTool ready, repeat the following steps:

1. Press the**Win** key to open the Start menu. Type**cmd** and press the**Ctrl + Shift + Enter** key.
2. UAC will pop up. Click on the**Yes** button to[open the Command Prompt with administrator privileges](https://www.makeuseof.com/how-to-always-open-command-prompt-as-administrator-windows/) .
3. Now, you need to navigate to the location where the ViVeTool folder exists. We extracted the tool to a folder named ViVeTool in**C** drive for easy access, and suggest you do the same. Otherwise, you have to change the directory multiple time to get to the tool’s folder.
4. Type the**cd C:\\** command and press the enter key to go to the main C drive directory.
5. After that, type**cd ViVeTool** command and press the enter key. Now, you are in the directory where ViVeTool executable file is present.
6. Type the following command and press the enter key to enable the hidden volume mixer:  
vivetool /enable /id:42106010
7. You will see a “**Successfully set feature configuration(s)** ” message. Type the**exit** command and press the enter key to close the command prompt window.  
![Enabling New Volume Settings in Action Center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enabling-new-volume-settings-in-action-center.jpg)
8. Restart your system to allow the changes to take effect.
<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
9. Log in and press**Win + A** to open Action Center. You will notice a new volume mixer icon next to the volume bar. Click on it to reveal the complete sound settings. Both the Spatial Audio and volume mixer will be present inside.  
![New Volume Settings in Action Center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/new-volume-settings-in-action-center.jpg)

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
## Adjust Your Volume Like A Pro on Windows 11

 Windows 11 uprooted a lot of useful settings and features. Users resorted to registry hacks and third-party programs to fix this issue. However, the new volume mixer attempts to fix that to some extent. Microsoft might improve the volume mixer further to overshadow apps like EarTrumpet, but that’s a very slim possibility.


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
<li><a href="https://remote-screen-capture.techidaily.com/new-best-ios-psp-emulators-our-top-5-selections-for-2024/"><u>[New] Best iOS PSP Emulators   Our Top 5 Selections for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-exclusive-action-cam-colorization-top-15-luts-to-enhance-cinematography/"><u>[New] Exclusive Action Cam Colorization  Top 15 LUTs to Enhance Cinematography</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-professional-broadcasting-tools-excluding-obs/"><u>[Updated] 2024 Approved  Professional Broadcasting Tools Excluding OBS</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-the-modern-broadcasters-guide-to-iphone-and-android-streaming/"><u>[Updated] In 2024, The Modern Broadcaster's Guide to iPhone and Android Streaming</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-journey-from-photographic-moments-to-sequential-videos/"><u>[Updated] Journey From Photographic Moments to Sequential Videos</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-privacy-preserving-recordings-methods-to-shield-sensitive-data/"><u>[Updated] Privacy-Preserving Recordings  Methods to Shield Sensitive Data</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-top-15-activities-perfect-for-podcast-lovers/"><u>2024 Approved  Top 15 Activities Perfect for Podcast Lovers</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-best-tools-to-hard-reset-oppo-reno-10-pro-5g-drfone-by-drfone-reset-android-reset-android/"><u>3 Best Tools to Hard Reset Oppo Reno 10 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/apples-next-gen-marvel-iphone-15-pro-vs-pro-max-showdown/"><u>Apple's Next-Gen Marvel: IPhone 15 Pro Vs. Pro Max Showdown</u></a></li>
<li><a href="https://extra-tips.techidaily.com/budget-videography-choosing-the-best-panoramic-cameras/"><u>Budget Videography  Choosing the Best Panoramic Cameras</u></a></li>
<li><a href="https://network-issues.techidaily.com/dell-display-hiccups-ended-successfully/"><u>Dell Display Hiccups Ended Successfully</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/empower-your-campaigns-using-the-advanced-technology-of-cookiebot/"><u>Empower Your Campaigns Using the Advanced Technology of Cookiebot</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-insights-selecting-the-right-os-for-gaming-glory/"><u>Expert Insights: Selecting the Right OS for Gaming Glory</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-strategies-for-windows-activation-failure-0x803f700f/"><u>Expert Strategies for Windows Activation Failure: 0X803F700f</u></a></li>
<li><a href="https://windows11.techidaily.com/festive-glamour-unveiled-in-decorative-windows/"><u>Festive Glamour Unveiled in Decorative Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-error-lost-access-to-ubisoft-game-launcher/"><u>Fixing Windows Error: Lost Access to Ubisoft Game Launcher</u></a></li>
<li><a href="https://extra-hints.techidaily.com/from-commonplace-phones-to-cutting-edge-vr-headsets/"><u>From Commonplace Phones to Cutting-Edge VR Headsets</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/growth-hackers-guide-the-ultimate-list-of-top-strategies-to-retain-youtube-viewers/"><u>Growth Hackers Guide  The Ultimate List of Top Strategies to Retain YouTube Viewers</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-overcoming-the-msvcr110dll-deficit/"><u>Guide to Overcoming the Msvcr110.dll Deficit</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-re-implementing-windows-11s-search-bar-as-an-icon/"><u>Guide: Re-Implementing Windows 11'S Search Bar as an Icon</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-change-your-sim-pin-code-on-your-realme-c33-2023-phone-by-drfone-android/"><u>How To Change Your SIM PIN Code on Your Realme C33 2023 Phone</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-my-xiaomi-redmi-13c-5g-location-is-wrong-drfone-by-drfone-virtual-android/"><u>How to Fix My Xiaomi Redmi 13C 5G Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-infinix-phone-with-broken-screen-by-drfone-android/"><u>How to Unlock Infinix Phone with Broken Screen</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-blueprint-for-a-viral-solitary-audio-experience/"><u>In 2024, Blueprint for a Viral Solitary Audio Experience</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-come-up-with-the-best-pokemon-team-on-nubia-z50-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, How to Come up With the Best Pokemon Team On Nubia Z50 Ultra? | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-no-limit-story-saving-at-the-tap-of-a-button/"><u>In 2024, No-Limit Story Saving at the Tap of a Button</u></a></li>
<li><a href="https://windows11.techidaily.com/launching-wordpad-windows-users-handbook/"><u>Launching WordPad: Windows User's Handbook</u></a></li>
<li><a href="https://extra-support.techidaily.com/leading-virtual-reality-enhancements-for-gamers-for-2024/"><u>Leading Virtual Reality Enhancements for Gamers for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/low-cost-high-risks-9-concerns-with-sub-standard-windows-keys/"><u>Low Cost, High Risks: 9 Concerns with Sub-Standard Windows Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/masterful-manipulation-of-your-identity-name-on-windows-11/"><u>Masterful Manipulation of Your Identity Name on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-booting-windows-11-3-key-usb-methods/"><u>Mastering Booting Windows 11: 3 Key USB Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-github-desktop-on-windows-step-by-step-guide/"><u>Mastering GitHub Desktop on Windows: Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11s-context-menu-with-additional-software-icons/"><u>Mastering Windows 11'S Context Menu with Additional Software Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-errors-with-amd-195-setup/"><u>Mastering Windows Errors with AMD 195 Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-of-windows-11-text-illumination-control/"><u>Mastery of Windows 11 Text Illumination Control</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-maintaining-your-note-apps-data/"><u>Mastery Over Maintaining Your Note App's Data</u></a></li>
<li><a href="https://windows11.techidaily.com/microsoft-family-safety-your-complete-reference/"><u>Microsoft Family Safety: Your Complete Reference</u></a></li>
<li><a href="https://windows11.techidaily.com/minmax-cpu-states-navigating-windows-power-control/"><u>Min/Max CPU States: Navigating Windows Power Control</u></a></li>
<li><a href="https://win-able.techidaily.com/minecraft-dungeon-keeps-freezing-learn-how-to-optimize-and-fix-your-game-on-pc/"><u>Minecraft Dungeon Keeps Freezing? Learn How to Optimize and Fix Your Game on PC</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-2024-approved-discover-the-best-pc-intro-creators-free-and-paid-options/"><u>New 2024 Approved Discover the Best PC Intro Creators Free and Paid Options</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-in-2024-online-stop-motion-animation-studios-top-5-free-and-paid-options/"><u>New In 2024, Online Stop Motion Animation Studios Top 5 Free and Paid Options</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722969305670-newest-driver-release-for-rtx-2080-compatible-with-windows-11-7-and-8-download-now/"><u>Newest Driver Release for RTX 2080: Compatible with Windows 11, 7 & 8 – Download Now!</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-user-interface-manage-filter-key-options-in-windows/"><u>Optimize User Interface: Manage Filter Key Options in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-device-access-barriers-in-audacity-windows/"><u>Overcoming Device Access Barriers in Audacity (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaiming-off-screen-windows-in-win11-6-step-guide/"><u>Reclaiming Off-Screen Windows in Win11: 6 Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/reinitializing-windows-updates-a-step-by-step-guide/"><u>Reinitializing Windows Updates: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-unsupported-boots-a-5-step-windows-guide/"><u>Resolving Unsupported Boots: A 5-Step Windows Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-input-devices-after-sleep-on-win11/"><u>Reviving Input Devices After Sleep on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-disappearing-results-from-windows-1011-search-tool/"><u>Solving Disappearing Results From Windows 10/11 Search Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/speedy-valorant-download-fix-for-windows-users/"><u>Speedy Valorant Download Fix for Windows Users</u></a></li>
<li><a href="https://android-frp.techidaily.com/step-by-step-tutorial-how-to-bypass-motorola-moto-g-stylus-5g-2023-frp-by-drfone-android/"><u>Step-by-Step Tutorial How To Bypass Motorola Moto G Stylus 5G (2023) FRP</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-mending-the-the-service-did-not-respond-windows-issue/"><u>Strategies for Mending the 'The Service Did Not Respond' Windows Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlined-method-for-enabling-windows-11-calculator/"><u>Streamlined Method for Enabling Windows 11 Calculator</u></a></li>
<li><a href="https://windows11.techidaily.com/system-resuscitation-modernizing-windows-driver-technology/"><u>System Resuscitation: Modernizing Windows Driver Technology</u></a></li>
<li><a href="https://windows11.techidaily.com/the-smart-way-to-mitigate-pc-cpu-spikes-via-resource-monitor/"><u>The Smart Way to Mitigate PC CPU Spikes via Resource Monitor</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/top-15-augmented-reality-games-like-pokemon-go-to-play-on-motorola-moto-g13-drfone-by-drfone-virtual-android/"><u>Top 15 Augmented Reality Games Like Pokémon GO To Play On Motorola Moto G13 | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/top-5-vivo-y02t-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 Vivo Y02T Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://win-solutions.techidaily.com/ultimate-guide-how-to-stop-dirt-5-from-freezing-and-crashing-on-pc/"><u>Ultimate Guide: How to Stop Dirt 5 From Freezing and Crashing on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/unearthing-bsod-traces-within-windows-vista2008/"><u>Unearthing BSOD Traces Within Windows Vista/2008</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-power-top-10-must-have-msistore-picks/"><u>Unleash Power: Top 10 Must-Have MSIStore Picks</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-productivity-a-guide-to-making-multiple-directories-at-once-in-windows/"><u>Unleashing Productivity: A Guide to Making Multiple Directories at Once in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-full-potential-of-windows-11s-tabbed-views/"><u>Unlock the Full Potential of Windows 11'S Tabbed Views</u></a></li>
<li><a href="https://windows11.techidaily.com/unpack-and-deploy-quick-apk-installation-guide-in-windows-11/"><u>Unpack and Deploy: Quick APK Installation Guide in Windows 11</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-2024-approved-best-android-video-editor-apps-for-chromebook/"><u>Updated 2024 Approved Best Android Video Editor Apps for Chromebook</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-unleash-your-creativity-the-best-animation-makers-for-beginners-and-pros-for-2024/"><u>Updated Unleash Your Creativity The Best Animation Makers for Beginners and Pros for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-troubleshooting-alternatives-to-rename-folder-functions/"><u>Win 11 Troubleshooting: Alternatives to Rename Folder Functions</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-10-product-key-our-guide-to-the-top-deals/"><u>Windows 10 Product Key: Our Guide to the Top Deals</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/zero-price-audio-excellence-ranking-of-top-10-desktop-tools/"><u>Zero-Price Audio Excellence  Ranking of Top 10 Desktop Tools</u></a></li>
</ul></div>
