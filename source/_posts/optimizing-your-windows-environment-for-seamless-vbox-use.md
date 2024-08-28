---
title: Optimizing Your Windows Environment for Seamless VBox Use
date: 2024-08-27T16:10:58.889Z
updated: 2024-08-28T16:10:58.889Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Optimizing Your Windows Environment for Seamless VBox Use
excerpt: This Article Describes Optimizing Your Windows Environment for Seamless VBox Use
keywords: VBox Optimize Windows,Seamless VMware,Windows VRBoosting,Streamlined Virtual PC,Enhance VBox Experience,Efficient VBox Use,Boost Windows Virtualization
thumbnail: https://thmb.techidaily.com/d6abae0f7e3d8fb5f7c3d204845ee10283f20e49e0d3d6312bf5d54b51961985.jpg
---

## Optimizing Your Windows Environment for Seamless VBox Use

 VirtualBox is a virtualization platform that allows you to run multiple operating systems on a single computer. It's installation on Windows requires a couple of packages available upfront. Without meeting these dependencies, VirtualBox installation will end up with an error.

 Visual C++ Redistributable is a straightforward installation, it is not the same case with Python as it requires configuring as well. The good thing is it is easy to do.

## Dependencies for Installation of VirtualBox on Windows

 VirtualBox is a cross-platform software. Apart from Windows, you can [install VirtualBox on Linux](https://www.makeuseof.com/install-ubuntu-virtualbox/) and Mac as well. The installation package is available for download from the official [VirtualBox site](https://www.virtualbox.org/wiki/Downloads).

![VirtualBox download page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/01-virtualbox-download-page.jpg)

 Before you install VirtualBox, you must install these packages:

* Microsoft Visual C++ 2019 Redistributable Package
* Python core / win32ap

 If they are not installed already, VirtualBox will ask you during installation to set them up first. See the following images for reference:

![Popup window in VirtualBox asks for Visual C++ Redistributable Package](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/02-popup-window-in-virtualbox-asks-for-visual-c-redistributable-package-2.jpg)

![VirtualBox window displays the need for Missing Dependencies Python Core win32api](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/03-virtualbox-window-displays-the-need-for-missing-dependencies-python-core-win32api.jpg)

Close

 If you try to continue the installation of VirtualBox without meeting the dependencies, the installation will end up in an error and show the following error message:

![VirtualBox Installation failed! Fatal error during installation](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/04-virtualbox-installation-failed-fatal-error-during-installation.jpg)

## How to Install Visual C++ Redistributable on Windows

 You can download Microsoft Visual C++ Redistributable from the [Microsoft Learn webpage](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170). You need to download the version that suits your operating system (x86/32-bit or x64/64-bit). Once downloaded, proceed with the installation, the process is straightforward.

![Microsoft Visual C++ Redistributable download page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/05-microsoft-visual-c-redistributable-download-page.jpg)

![Microsoft Visual C++ Redistributable download choose architechture](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/06-microsoft-visual-c-redistributable-download-choose-architechture.jpg)

![Microsoft Visual C++ Redistributable installation](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/07-microsoft-visual-c-redistributable-installation.jpg)

Close

## How to Install and Configure Python / win32api on Windows

 Python is another dependency for VirtualBox. You can download it from the official [Python website](https://www.python.org/downloads/).

![Download Python win32api for Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/08-download-python-win32api-for-windows.jpg)

 Once downloaded, start the installation. You need to check **Add python.exe to PATH**, and complete the installation. When added to PATH, Python packages and scripts can be accessed from any directory. Complete the installation.

![Install Python win32api for Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/09-install-python-win32api-for-windows.jpg)

 Now, configure Python for Win32 extensions. It provides access to Windows APIs from Python. To do this, open the Command Prompt or PowerShell as administrator and run the command:

`pip install pywin32`

![Command to install pywin32 in WIndows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/10-command-to-install-pywin32-in-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
 Your computer has now met all the dependencies to install VirtualBox.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35408920&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/FR-200-1.png" border="0">Glarysoft File Recovery Pro - Helps to recover your lost file/data, even permanently deleted data. </a>
<!-- affiliate ads end -->
## Error Free Installation of VirtualBox on Windows

 Start the installation of VirtualBox, and it will complete without any errors. Browse the following images for reference:

![Install VirtualBox in WIndows using the wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/11-install-virtualbox-in-windows-using-the-wizard.jpg)

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Install VirtualBox in WIndows custom setup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/12-install-virtualbox-in-windows-custom-setup.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
![Install VirtualBox in WIndows network interfaces warning](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/13-install-virtualbox-in-windows-network-interfaces-warning.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Install VirtualBox in WIndows ready to install](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/14-install-virtualbox-in-windows-ready-to-install.jpg)

![VirtualBox in WIndows installation complete](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/15-virtualbox-in-windows-installation-complete.jpg)

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![VirtualBox manager in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/16-virtualbox-manager-in-windows.jpg)

Close

## Run a Guest Operating System of Your Choice via VirtualBox

 With its simple interface and impressive features, VirtualBox is a strong contender among virtualization applications.

 With its ability to create snapshots, VirtualBox can even help safeguard the data of the guest operating systems against virus or ransomware attacks.

 Visual C++ Redistributable is a straightforward installation, it is not the same case with Python as it requires configuring as well. The good thing is it is easy to do.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-information.techidaily.com/new-chuckle-inducing-snaps-applying-the-cartoon-face-effect-on-snapchat/"><u>[New] Chuckle-Inducing Snaps  Applying the Cartoon Face Effect on Snapchat</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-freeze-your-favorite-moves-explore-these-top-9-windows-gif-recipes/"><u>[New] Freeze Your Favorite Moves! Explore These Top 9 Windows GIF Recipes</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-full-unveiling-of-picsart-complete-users-guide/"><u>[New] Full Unveiling of PicsArt  Complete User's Guide</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-in-2024-embark-on-a-textual-adventure-14-spectacular-examples/"><u>[New] In 2024, Embark on a Textual Adventure  14 Spectacular Examples</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-final-cut-pro-x-a-guide-to-instagrams-vertical-preference/"><u>[Updated] 2024 Approved  Final Cut Pro X  A Guide to Instagram’s Vertical Preference</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-premium-9-clandestine-content-getters/"><u>[Updated] 2024 Approved  Premium 9 Clandestine Content Getters</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-the-insiders-tips-for-youtube-shorts-mastery/"><u>[Updated] 2024 Approved  The Insider's Tips for YouTube Shorts Mastery</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-content-hub-hierarchy-stand-out-amongst-titans-vimeo-youtube-and-dailymotion-for-2024/"><u>[Updated] Content Hub Hierarchy  Stand Out Amongst Titans – Vimeo, YouTube & Dailymotion for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-easy-going-20-country-tunes-to-relax-and-dance-on-tiktok/"><u>[Updated] Easy-Going 20 Country Tunes to Relax and Dance on TikTok</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-from-twitters-tube-to-your-whatsapp-buddy-list-for-2024/"><u>[Updated] From Twitter's Tube to Your WhatsApp Buddy List for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-unleash-creativity-on-instagrams-reels-frontier/"><u>[Updated] In 2024, Unleash Creativity on Instagram's Reels Frontier</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-mastering-the-art-of-crafting-compelling-content-in-60-second-videos/"><u>[Updated] Mastering the Art of Crafting Compelling Content in 60-Second Videos</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-scope-to-screen-partnerships-for-mcns/"><u>[Updated] Scope-to-Screen Partnerships for MCNs</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-twist-and-turn-the-screen-unleashing-your-inner-dancer-with-tiktok-and-macos/"><u>[Updated] Twist & Turn the Screen  Unleashing Your Inner Dancer with TikTok and MacOS</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-mastering-image-enhancement-for-breathtaking-results/"><u>2024 Approved  Mastering Image Enhancement for Breathtaking Results</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/comprehensive-tutorial-how-to-clean-up-installed-apps-on-macos/"><u>Comprehensive Tutorial: How to Clean Up Installed Apps on macOS</u></a></li>
<li><a href="https://program-issues.techidaily.com/curbing-the-starfield-apps-high-cpu-consumption-strategies-for-202n4/"><u>Curbing the Starfield App’s High CPU Consumption: Strategies for 202N4</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-steps-for-powertoys-on-win11/"><u>Essential Steps for PowerToys on Win11</u></a></li>
<li><a href="https://extra-information.techidaily.com/exploring-premier-applications-for-changing-vtuber-sounds/"><u>Exploring Premier Applications for Changing Vtuber Sounds</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-effortlessly-engage-with-windows-11-service-tools/"><u>How to Effortlessly Engage with Windows 11 Service Tools</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-lava-yuva-2-pro-find-my-friends-no-location-found-drfone-by-drfone-virtual-android/"><u>How to Fix Lava Yuva 2 Pro Find My Friends No Location Found? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-a-damaged-video-file-of-infinix-hot-40-using-video-repair-utility-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair a Damaged video file of Infinix Hot 40 using Video Repair Utility on Windows?</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-speed-up-the-yuzu-emulator-on-windows/"><u>How to Speed Up the Yuzu Emulator on Windows</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-iphone-14-without-swiping-up-6-ways-drfone-by-drfone-ios/"><u>How To Unlock iPhone 14 Without Swiping Up? 6 Ways | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-from-stills-to-songs-the-art-of-audio-visual-fusion/"><u>In 2024, From Stills to Songs  The Art of Audio-Visual Fusion</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-use-pokemon-emerald-master-ball-cheat-on-oppo-a58-4g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Use Pokémon Emerald Master Ball Cheat On Oppo A58 4G | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-samsung-galaxy-a14-5g-phone-frp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Samsung Galaxy A14 5G Phone FRP Lock</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-uncharted-sci-fi-dimensions-top-10-metaverse-movie-experiences/"><u>In 2024, Uncharted Sci-Fi Dimensions  Top 10 Metaverse Movie Experiences</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-universal-unlock-pattern-for-poco-x6-pro-by-drfone-android/"><u>In 2024, Universal Unlock Pattern for Poco X6 Pro</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-which-pokemon-can-evolve-with-a-moon-stone-for-motorola-edgeplus-2023-drfone-by-drfone-virtual-android/"><u>In 2024, Which Pokémon can Evolve with a Moon Stone For Motorola Edge+ (2023)? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/is-enhancement-or-extra-cost-justified-for-win-11s-add-ons/"><u>Is Enhancement or Extra Cost Justified for Win 11'S Add-Ons?</u></a></li>
<li><a href="https://windows11.techidaily.com/learn-how-to-resurrect-the-non-functional-win-plus-p-feature-in-windows/"><u>Learn How to Resurrect the Non-Functional Win + P Feature in Windows.</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-bluescreenview-an-in-depth-analysis/"><u>Leveraging BlueScreenView - An In-Depth Analysis</u></a></li>
<li><a href="https://windows11.techidaily.com/making-the-right-windows-11-call-home-vs-premium-features/"><u>Making the Right Windows 11 Call: Home Vs. Premium Features</u></a></li>
<li><a href="https://windows11.techidaily.com/master-email-attachment-handling-in-microsoft-words-read-pane-mode/"><u>Master Email Attachment Handling in Microsoft Word's Read Pane Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-successful-files-transfer-in-windows/"><u>Mastering the Art of Successful Files Transfer in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-fixes-reconciling-obs-server-disconnections-on-windows/"><u>Mastering the Fixes: Reconciling OBS Server Disconnections on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11-a-guide-to-overcoming-stubborn-gif-size-errors-discord/"><u>Mastering Windows 11: A Guide to Overcoming Stubborn GIF Size Errors (Discord)</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-keeping-windows-time-unchanged/"><u>Mastery over Keeping Windows Time Unchanged</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-prevent-windows-pc-from-booting-into-bios/"><u>Methods to Prevent Windows PC From Booting Into BIOS</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-error-code-0xc00ce556-in-windows/"><u>Navigating the Error Code 0xC00CE556 in WINDOWS</u></a></li>
<li><a href="https://windows11.techidaily.com/reimagining-windows-ui-adding-menus-and-subitems/"><u>Reimagining Windows UI: Adding Menus and Subitems</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-checksum-accuracy-in-winrar-archives-with-6-tips/"><u>Restoring Checksum Accuracy in WinRAR Archives with 6 Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-taskbar-button-image-rendering/"><u>Restoring Taskbar Button Image Rendering</u></a></li>
<li><a href="https://windows11.techidaily.com/reversing-operation-failure-0x709-on-pc/"><u>Reversing Operation Failure 0X709 on PC</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/revolutionizing-playtime-with-the-wonder-workshop-dash-a-comprehensive-product-overview/"><u>Revolutionizing Playtime with the Wonder Workshop Dash - A Comprehensive Product Overview</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/scan-for-collective-shared-content-on-messenger-for-2024/"><u>Scan for Collective Shared Content on Messenger for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-and-protect-win-11-edge-instalment-of-microsofts-aguard-feature/"><u>Secure and Protect Win 11 Edge: Instalment of Microsoft's Aguard Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-and-slim-filesystem-setting-up-auto-delete-in-win11/"><u>Secure and Slim Filesystem: Setting Up Auto Delete in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-your-deal-black-friday-612-for-full-life-win10/"><u>Secure Your Deal: Black Friday - $6.12 for Full-Life Win10</u></a></li>
<li><a href="https://windows11.techidaily.com/simplified-approach-to-batch-convert-heic-files-to-jpeg-in-windows-11/"><u>Simplified Approach to Batch Convert HEIC Files to JPEG in Windows 11</u></a></li>
<li><a href="https://driver-download.techidaily.com/step-by-step-process-for-installing-latest-drivers-on-razer-blade-17-windows-compatibility/"><u>Step-by-Step Process for Installing Latest Drivers on Razer Blade 17 | Windows Compatibility</u></a></li>
<li><a href="https://windows11.techidaily.com/strategic-tips-to-optimize-amd-radeon-gaming/"><u>Strategic Tips to Optimize AMD Radeon Gaming</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-tackling-windows-disk-errors/"><u>The Ultimate Guide to Tackling Windows Disk Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/title-perfecting-space-between-windows-widgets/"><u>Title: Perfecting Space Between Windows Widgets</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshoot-unresponsive-inputs-when-waking-up-win11/"><u>Troubleshoot Unresponsive Inputs When Waking up Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-non-responsive-windows-enter-key/"><u>Troubleshooting Non-Responsive Windows Enter Key</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-steam-friendship-disconnect-on-pc/"><u>Troubleshooting Steam Friendship Disconnect on PC</u></a></li>
<li><a href="https://extra-resources.techidaily.com/understanding-and-leveraging-influencers-on-snapchat/"><u>Understanding and Leveraging Influencers on Snapchat</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-new-network-possibilities-with-win11s-settings/"><u>Unlock New Network Possibilities with Win11's Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-your-pc-easily-windows-hello-fingerprint-guide/"><u>Unlock Your PC Easily: Windows Hello Fingerprint Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-new-horizons-rethinking-user-rights-on-windows/"><u>Unlocking New Horizons: Rethinking User Rights on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-diagnostic-info-a-quick-guide/"><u>Unlocking Windows' Diagnostic Info: A Quick Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-blue-screen-mystery-0xc0000001/"><u>Unraveling Blue Screen Mystery - 0xC0000001</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-gif-size-limits-a-guide-to-fixed-errors-in-discord-win11/"><u>Unraveling GIF Size Limits: A Guide to Fixed Errors in Discord (Win11)</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-filmora-scrn-tutorial-recording-your-desktop-made-easy-for-2024/"><u>Updated Filmora Scrn Tutorial Recording Your Desktop Made Easy for 2024</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-best-in-class-text-tracking-and-animation-software-2023/"><u>Updated In 2024, Best in Class Text Tracking and Animation Software 2023</u></a></li>
<li><a href="https://windows11.techidaily.com/uptime-expertise-for-win11-devices-discover-the-top-5-methods/"><u>Uptime Expertise for Win11 Devices - Discover the Top 5 Methods</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/vocabverve-at-dubai-2020-pioneering-multilingualism/"><u>VocabVerve at Dubai 2020: Pioneering Multilingualism</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-drop-issue-effective-solutions-needed/"><u>Win11 Drop Issue: Effective Solutions Needed</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>