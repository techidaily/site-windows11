---
title: Step-by-Step to Unleash Windows 11 Action Center Mixing
date: 2024-08-31T22:08:05.368Z
updated: 2024-09-01T22:08:05.368Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Step-by-Step to Unleash Windows 11 Action Center Mixing
excerpt: This Article Describes Step-by-Step to Unleash Windows 11 Action Center Mixing
keywords: Win11 Action Center,Mix Action Center,Windows 11 Setup,Step Win11 Guide,Unlock Action Center,Win11 Control Panel,Setup Win11 Basics
thumbnail: https://thmb.techidaily.com/e9f6abd8662955b9fc76151bcfa96786be75ef68a255d5c3126b3ad30bf05b53.jpg
---

## Step-by-Step to Unleash Windows 11 Action Center Mixing

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
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. Download the Latest Windows Insider Build and ViVeTool

 Currently, the volume mixer feature is an experimental feature hidden in Windows Insider build 25295\. So, you must install this Windows Insider build or a higher version to enable this feature. We recommend[using UUP Dump to download Windows Insider builds without subscribing to Windows Insider](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/) .

 Microsoft recently expanded the Insider program with a new Canary channel, and it makes it difficult to downgrade to another channel. So, you can use UPP Dump to avoid this program and get builds directly.

 You will also need to download[ViVeTool from GitHub](https://github.com/thebookisclosed/ViVe/releases) to enable the experimental volume mixer feature. It is a command-line tool that can both activate and deactivate experimental Windows features. However, extract the tool to an easily accessible location in the C drive.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
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
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
9. Log in and press**Win + A** to open Action Center. You will notice a new volume mixer icon next to the volume bar. Click on it to reveal the complete sound settings. Both the Spatial Audio and volume mixer will be present inside.  
![New Volume Settings in Action Center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/new-volume-settings-in-action-center.jpg)

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
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
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-leading-8-capture-tools-without-lag/"><u>[New] 2024 Approved  Leading 8 Capture Tools Without Lag</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-facebook-video-wonders-your-must-see-list/"><u>[New] Facebook Video Wonders - Your Must-See List</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-a-user-friendly-guide-to-efficiently-use-ez-grabber/"><u>[New] In 2024, A User-Friendly Guide to Efficiently Use EZ Grabber</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-a-quick-guide-downloading-fb-videos-on-multiple-oses/"><u>[Updated] A Quick Guide  Downloading FB Videos on Multiple OSes</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-navigating-the-top-10-for-streamed-television/"><u>[Updated] Navigating the Top 10 for Streamed Television</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-crafting-visual-stories-for-successful-fb-covers/"><u>2024 Approved  Crafting Visual Stories for Successful FB Covers</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-mac-high-quality-video-and-audible-recording/"><u>2024 Approved  Mac High-Quality Video & Audible Recording</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-art-of-monitoring-youtube-discussions/"><u>2024 Approved  The Art of Monitoring YouTube Discussions</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-easy-ways-to-change-location-on-youtube-tv-on-infinix-hot-40-pro-drfone-by-drfone-virtual-android/"><u>5 Easy Ways to Change Location on YouTube TV On Infinix Hot 40 Pro | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-chrome-crashes-or-wont-open-on-infinix-smart-7-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Chrome Crashes or Wont Open on Infinix Smart 7 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-windows-11-efficiency-key-modifications-to-apply/"><u>Boost Windows 11 Efficiency: Key Modifications to Apply</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ing-the-visual-language-of-live-videos-on-youtube-for-2024/"><u>Decoding the Visual Language of Live Videos on YouTube for 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/effective-fixes-for-stability-problems-in-the-world-of-tribes-of-midgard/"><u>Effective Fixes for Stability Problems in the World of 'Tribes of Midgard'</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/elevate-your-digital-storytelling-on-tiktok-with-5-key-caption-approaches/"><u>Elevate Your Digital Storytelling on TikTok With 5 Key Caption Approaches</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-insights-into-utilizing-microsofts-system-restore-feature/"><u>Essential Insights Into Utilizing Microsoft's System Restore Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/from-phones-playground-to-pc-realm-android-games-via-microsoft-and-google/"><u>From Phone's Playground to PC Realm: Android Games via Microsoft & Google</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-bypass-the-required-apple-store-verification-for-iphone-13-pro-by-drfone-ios/"><u>How To Bypass the Required Apple Store Verification For iPhone 13 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-convert-mkv-to-mp4-in-windows/"><u>How to Convert MKV to MP4 in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-correct-over-saturated-colors-on-laptops/"><u>How to Correct Over-Saturated Colors on Laptops</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-fix-iphone-se-2020-passcode-not-working-drfone-by-drfone-ios/"><u>How to Fix iPhone SE (2020) Passcode not Working? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-solve-microsoft-office-365-glitches-error-30015-26/"><u>How to Solve Microsoft Office 365 Glitches: Error 30015-26</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-vivo-v29-pro-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Vivo V29 Pro to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-tecno-camon-30-pro-5g-phone-without-password-by-drfone-android/"><u>How To Unlock Tecno Camon 30 Pro 5G Phone Without Password?</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-realme-12-5g-frp-by-drfone-android/"><u>In 2024, Step-by-Step Tutorial How To Bypass Realme 12 5G FRP</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-unseen-snaps-and-silence-could-be-a-block/"><u>In 2024, Unseen Snaps and Silence  Could Be a Block</u></a></li>
<li><a href="https://windows11.techidaily.com/journey-into-creativity-initiating-ms-paint-on-win11/"><u>Journey Into Creativity: Initiating MS Paint on Win11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/mastering-troubleshooting-how-to-overcome-a-103003-setback-in-cyberpunk-steel-tarkov/"><u>Mastering Troubleshooting: How to Overcome a #103003 Setback in Cyberpunk Steel (Tarkov)</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-w11s-auto-hdr-a-step-by-step-guide/"><u>Mastering W11's Auto HDR: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-xpatch-troubleshooting/"><u>Mastering Windows XPatch Troubleshooting</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-guide-navigating-and-controlling-windows-fn-key/"><u>Mastery Guide: Navigating and Controlling Windows' Fn Key</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-resolve-non-installed-windows-store-apps/"><u>Methods to Resolve Non-Installed Windows Store Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/microsoft-and-local-unpacking-key-contrasts-in-windows-login-mechanisms/"><u>Microsoft & Local: Unpacking Key Contrasts in Windows Login Mechanisms</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-windows-and-ea-connections-troubles/"><u>Navigating Through Windows and EA Connections Troubles</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-playback-problem-in-wmp/"><u>Overcoming Playback Problem in WMP</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-based-qbittorrent-halt-problems/"><u>Overcoming Windows-Based qBittorrent Halt Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/overhaul-your-privacy-by-switching-off-windows-trackers/"><u>Overhaul Your Privacy by Switching Off Windows Trackers</u></a></li>
<li><a href="https://windows11.techidaily.com/pinpointing-powerful-policies-in-windows-systems/"><u>Pinpointing Powerful Policies in Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-devices-from-suspending-during-energy-saver/"><u>Preventing Devices From Suspending During Energy Saver</u></a></li>
<li><a href="https://windows11.techidaily.com/redeeming-windows-reviving-ms-store-programs/"><u>Redeeming Windows: Reviving MS Store Programs</u></a></li>
<li><a href="https://windows11.techidaily.com/restore-windows-teams-screen-sharing/"><u>Restore Windows Teams Screen Sharing</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-accessibility-for-non-starting-store-programs/"><u>Restoring Accessibility for Non-Starting Store Programs</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-original-touchscreen-layout-on-windows-11/"><u>Restoring Original Touchscreen Layout on Windows 11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/revolutionary-screen-technology-elite-4k-options-for-mac-enthusiasts-for-2024/"><u>Revolutionary Screen Technology  Elite 4K Options for Mac Enthusiasts for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/sharpen-your-pc-queries-with-everythingapp/"><u>Sharpen Your PC Queries with EverythingApp</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlined-strategy-for-downloading-adobe-on-microsoft-platform/"><u>Streamlined Strategy for Downloading Adobe on Microsoft Platform</u></a></li>
<li><a href="https://windows11.techidaily.com/tidy-up-win11-desktop-by-removing-highlighted-icon/"><u>Tidy up Win11 Desktop by Removing Highlighted Icon</u></a></li>
<li><a href="https://windows11.techidaily.com/tidying-up-your-pc-a-compact-guide-to-uninstallation-in-windows-11-108-chars/"><u>Tidying Up Your PC: A Compact Guide to Uninstallation in Windows 11 (108 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/top-7-sketch-tools-on-windows-11/"><u>Top 7 Sketch Tools on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/triggering-windows-calculator-in-version-11/"><u>Triggering Windows Calculator in Version 11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-mail-error-code-zero-x-eight-oh-three-one-f/"><u>Troubleshooting Windows Mail Error Code: Zero X Eight Oh Three One F</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-addressing-audio-failure-xc00d36b4/"><u>Understanding and Addressing Audio Failure XC00D36B4</u></a></li>
<li><a href="https://some-skills.techidaily.com/unveiling-elite-choices-a-guide-to-hdr-cameras-for-2024/"><u>Unveiling Elite Choices  A Guide to HDR Cameras for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-steps-for-reclaiming-lost-vpn-links-in-winpc/"><u>Unveiling Steps for Reclaiming Lost VPN Links in WinPC</u></a></li>
<li><a href="https://windows11.techidaily.com/why-opt-out-of-wsl/"><u>Why Opt Out of WSL?</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-unveiled-a-dive-into-widgets/"><u>Windows 11 Unveiled - A Dive Into Widgets</u></a></li>
</ul></div>
