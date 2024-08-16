---
title: Adjusting Metric Monitoring of Wifi Networks via Win11 Settings
date: 2024-08-15T15:17:39.970Z
updated: 2024-08-16T15:17:39.970Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting Metric Monitoring of Wifi Networks via Win11 Settings
excerpt: This Article Describes Adjusting Metric Monitoring of Wifi Networks via Win11 Settings
keywords: WiFi Monitoring in Windows,Win11 Wireless Settings,Wifi Performance Tracking,Network Latency Checker,Signal Strength Analysis,Optimize Win11 Wi-Fi,Metric Management Tool
thumbnail: https://thmb.techidaily.com/c35bb55569306b5428a10bd1ab44596d5c722993db7a19d5db6d527a1da8e1b4.png
---

## Adjusting Metric Monitoring of Wifi Networks via Win11 Settings

 If you're using a capped internet connection, such as a mobile hotspot, you'd want to limit your Windows PC's background data usage. That way, you ensure that background processes, like OneDrive or Steam, do not use up all your data while your computer's on.

 But how do you configure your PC to treat a Wi-Fi network as a metered or unmetered connection? Luckily, Windows 11 provides a couple of different ways to enable or disable metered connections for a Wi-Fi network. Let's go over both of them in detail.

## 1\. Enable or Disable Metered Connections for a Wi-Fi Network Using the Settings App

 The**Network & internet** section in the Settings app serves as a central location for all the network-related settings on Windows. You can visit that section to quickly enable or disable a metered connection for your computer's Wi-Fi network. Here are the steps for the same.

1. Open the**Start menu** and click the**gear-shaped icon** to [launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Network & internet** from the left sidebar.
3. Click on**Wi-Fi** from the right pane.
4. Go to**Manage known networks** .
5. Select the network you want to configure.
6. Enable the toggle next to**Metered connection** to set the Wi-Fi network as metered. If you want to set the network as an unmetered connection, disable the toggle.  
![Enable or Disable Metered Connection in Windows 11 Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/enable-or-disable-metered-connection-in-windows-11-using-settings-app.jpg)

 Note that you'll have to repeat the above steps for each Wi-Fi network separately. Following that, Windows will remember your network preferences.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Enable or Disable Wi-Fi Metered Connections via the Command Prompt

 If you're a power user who prefers to make system changes with a command-line tool, you can use the [Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) to enable or disable metered connection for a Wi-Fi network on Windows. Here's how you can go about it.

1. Right-click the**Start icon** or use the**Win + X** keyboard shortcut to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the terminal window, type the following command and press**Enter** to view a list of network profiles on your computer:  
`netsh wlan show profiles`  
![Network Profiles in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-profiles-in-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Note down the Wi-Fi network name for which you want to enable or disable the metered connection option.
6. Next, run the following command to determine whether your connection is metered or unmetered.  
`netsh wlan show profile name="Wi-Fi Name"`  
 Make sure you replace**Wi-Fi Name** in the above command with the actual name of the network noted in the last step.
7. Under the**Cost settings** section, check the value next to the**Cost** field. If it reads**Fixed** , the network is set as a metered connection. Conversely, if it reads**Unrestricted** , it is designated as an unmetered connection.
8. Type the following command and press**Enter** to mark the network as a metered connection.  
`netsh wlan set profileparameter name="Wi-Fi Name" cost=Fixed`  
![Disable Metered Connection in Windows 11 Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-metered-connection-in-windows-11-using-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you want to disable the metered connection for a network, run the following command instead.

`netsh wlan set profileparameter name="Wi-Fi Name" cost=Unrestricted`

 The Command Prompt should display a message once the network profile is updated. After that, you can close the terminal window.

 Aside from the above, you can view important details about your Wi-Fi network using the Command Prompt. If you're interested in doing that, check our guide on [the best commands to manage wireless networks on Windows](https://www.makeuseof.com/tag/commands-manage-wireless-networks-windows/) .

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
## Efficiently Manage Your Data With Metered Connection

 Enabling or disabling the metered connection option for Wi-Fi networks in Windows is relatively simple, regardless of the method you use.

 If you have a limited data plan, you can also set a data usage limit for your Wi-Fi connection. This way, Windows will notify you when you approach the set data limit.


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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-from-chords-to-chart-toppers-essential-musician-focused-youtube-content/"><u>[New] 2024 Approved  From Chords to Chart-Toppers  Essential Musician-Focused YouTube Content</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-harmonizing-in-tiktoks-duo-videos-for-2024/"><u>[New] Harmonizing in TikTok's Duo Videos for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-sync-facebook-media-for-larger-display-views/"><u>[New] Sync Facebook Media for Larger Display Views</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-audio-enthusiasts-guide-to-premier-9-mic-devices-for-2024/"><u>[Updated] Audio Enthusiasts Guide to Premier 9 Mic Devices for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-budgeting-basics-starting-a-successful-podcast/"><u>[Updated] Budgeting Basics  Starting a Successful Podcast</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-easy-peasy-ffvegior-grab-facebook-video-mp4-files/"><u>[Updated] Easy Peasy FFVEGIOR  Grab Facebook Video MP4 Files</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-in-2024-hashtag-heroes-twitters-trending-talk/"><u>[Updated] In 2024, Hashtag Heroes  Twitter's Trending Talk</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-the-ultimate-guide-to-visiting-friends-lives-on-tiktok/"><u>[Updated] In 2024, The Ultimate Guide to Visiting Friends' Lives on TikTok</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-master-your-space-essential-bot-selections-for-discord/"><u>[Updated] Master Your Space  Essential Bot Selections for Discord</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-step-up-your-content-learn-how-to-make-captivating-youtube-shorts/"><u>[Updated] Step Up Your Content  Learn How to Make Captivating YouTube Shorts</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-affordable-wireless-charging-pads-for-modern-phones/"><u>2024 Approved  Affordable Wireless Charging Pads for Modern Phones</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-streamline-youtube-sounds-to-mp3-using-mac/"><u>2024 Approved  Streamline YouTube Sounds to MP3 Using Mac</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-ultimate-guide-for-crafting-engaging-shareable-youtube-shorts/"><u>2024 Approved  The Ultimate Guide for Crafting Engaging, Shareable YouTube Shorts</u></a></li>
<li><a href="https://games-able.techidaily.com/6-insights-integrating-raspberry-pi-into-old-school-games/"><u>6 Insights: Integrating Raspberry Pi Into Old-School Games</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-non-compliance-overcoming-intel-hd-graphics-errors/"><u>Addressing Non-Compliance: Overcoming Intel HD Graphics Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-windows-11-stumbling-blocks-the-most-crucial-tips/"><u>Avoiding Windows 11 Stumbling Blocks: The Most Crucial Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-error-code-x80131500-at-store/"><u>Breaking Down Error Code: X80131500 at Store</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-gap-elevating-your-windows-experience-by-reclaiming-offscreen-panes/"><u>Bridging the Gap: Elevating Your Windows Experience by Reclaiming Offscreen Panes</u></a></li>
<li><a href="https://windows11.techidaily.com/command-prompt-oddities-learn-5-amusing-anomalies/"><u>Command Prompt Oddities: Learn 5 Amusing Anomalies</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-to-rectify-windows-security-faults/"><u>Comprehensive Guide to Rectify Windows Security Faults</u></a></li>
<li><a href="https://windows11.techidaily.com/digital-dream-team-top-windows-apps-for-a-winning-start/"><u>Digital Dream Team: Top Windows Apps for a Winning Start</u></a></li>
<li><a href="https://windows11.techidaily.com/discreetly-putting-an-end-to-invisible-window-tasks/"><u>Discreetly Putting an End to Invisible Window Tasks</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-compatible-samsung-printer-drivers-for-windows-step-by-step-instructions/"><u>Download Compatible Samsung Printer Drivers for Windows - Step by Step Instructions</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-call-history-from-infinix-gt-10-pro-by-fonelab-android-recover-call-logs/"><u>Easy steps to recover deleted call history from Infinix GT 10 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-clutter-software-uninstallation-tricks-for-windows-11-106-chars/"><u>Eliminating Clutter: Software Uninstallation Tricks for Windows 11 (106 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-real-time-performance-for-smooth-vlc-viewing/"><u>Enhancing Real-Time Performance for Smooth VLC Viewing</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-to-using-windows-11s-compatibility-fixer/"><u>Essential Guide to Using Windows 11’S Compatibility Fixer</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-for-diablo-gameplay-enthusiasts/"><u>Essential Tips for Diablo Gameplay Enthusiasts</u></a></li>
<li><a href="https://tech-revival.techidaily.com/1722093182035-experience-cutting-edge-ai-search-on-the-go-with-bings-new-app-support-for-android-and-ios/"><u>Experience Cutting-Edge AI Search on the Go with Bing's New App Support for Android and iOS</u></a></li>
<li><a href="https://some-techniques.techidaily.com/expert-methods-for-incorporating-links-into-tiktok-bios-for-2024/"><u>Expert Methods for Incorporating Links Into TikTok Bios for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-to-fully-erase-wsl-from-windows-11-systems/"><u>Expert Tips to Fully Erase WSL From Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-a-non-compatible-device-after-windows-11-installation/"><u>Fixing a Non-Compatible Device After Windows 11 Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/get-ahead-in-passwords-7-best-free-generation-tools-for-windows/"><u>Get Ahead in Passwords: 7 Best Free Generation Tools for Windows</u></a></li>
<li><a href="https://change-location.techidaily.com/how-do-you-get-sun-stone-evolutions-in-pokemon-for-vivo-v29-drfone-by-drfone-virtual-android/"><u>How Do You Get Sun Stone Evolutions in Pokémon For Vivo V29? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-correctly-handle-iomap64sys-failures-in-winos/"><u>How To Correctly Handle IOMap64.sys Failures in WinOS</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-get-the-apple-id-verification-code-on-apple-iphone-12-in-the-best-ways-by-drfone-ios/"><u>How To Get the Apple ID Verification Code On Apple iPhone 12 in the Best Ways</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reset-freezes-and-crashes-in-virtual-worlds/"><u>How to Reset Freezes & Crashes in Virtual Worlds</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-swiftly-download-the-lexar-usb-driver-today/"><u>How to Swiftly Download the Lexar USB Driver Today!</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-teach-you-to-transfer-files-from-poco-c55-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways To Teach You To Transfer Files from Poco C55 to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-infinix-smart-8-hd-drfone-by-drfone-virtual/"><u>In 2024, 9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Infinix Smart 8 HD | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-can-i-use-a-fake-gps-without-mock-location-on-tecno-pova-5-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How Can I Use a Fake GPS Without Mock Location On Tecno Pova 5 Pro? | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-ideal-video-player-apps-for-windows-os-enthusiasts/"><u>In 2024, Ideal Video Player Apps for Windows OS Enthusiasts</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-sim-unlock-realme-11-pro-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>In 2024, Sim Unlock Realme 11 Pro Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-top-ranked-spots-for-boosting-youtube-videos/"><u>In 2024, Top-Ranked Spots for Boosting YouTube Videos</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-valorant-screenshots-transformed-by-rapid-skilled-designers/"><u>In 2024, Valorant Screenshots Transformed by Rapid, Skilled Designers</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-motorola-razr-40-drfone-by-drfone-virtual-android/"><u>In 2024, What is the best Pokemon for pokemon pvp ranking On Motorola Razr 40? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/introducing-real-space-sound-on-windows-11/"><u>Introducing Real-Space Sound on Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/my-computer-wont-recognize-my-latest-era-logitech-prodigy-cam-post-10-update-heres-why-and-how-to-fix-it-solved/"><u>My Computer Won't Recognize My Latest-Era Logitech Prodigy Cam, Post 10 Update – Here’s Why and How to Fix It ![Solved]</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-in-2024-fcp-voice-over-mastery-top-tips-for-beginners/"><u>New In 2024, FCP Voice Over Mastery Top Tips for Beginners</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-top-10-best-audio-mixer-software-for-free/"><u>New Top 10 Best Audio Mixer Software for FREE</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-your-experience-adding-uninstall-shortcut-in-windows-10/"><u>Optimize Your Experience: Adding Uninstall Shortcut in Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-corruption-unlock-write-permissions-in-win10win11/"><u>Overcoming Corruption: Unlock Write Permissions in Win10/Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-roadblocks-activating-non-functional-scripts-in-windows/"><u>Overcoming Roadblocks: Activating Non-Functional Scripts in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/personalize-browser-security-incorporating-trusted-websites-in-windows-11/"><u>Personalize Browser Security: Incorporating Trusted Websites in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-chromeedge-from-hiding-taskbar-on-large-screens/"><u>Preventing Chrome/Edge From Hiding Taskbar on Large Screens</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-removing-isdonedll-malfunctions-from-windows-11/"><u>Quick Guide: Removing ISDone.dll Malfunctions From Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/recovering-failed-zip-operations-on-win-11-system/"><u>Recovering Failed ZIP Operations on Win 11 System</u></a></li>
<li><a href="https://windows11.techidaily.com/recovering-robustness-of-ccleaner-on-your-win11-pc/"><u>Recovering Robustness of CCleaner on Your Win11 PC</u></a></li>
<li><a href="https://windows11.techidaily.com/safekeep-your-files-setting-up-folder-restrictions-in-windows-11/"><u>Safekeep Your Files: Setting Up Folder Restrictions in Windows 11</u></a></li>
<li><a href="https://win-amazing.techidaily.com/seamless-asus-vg248qe-driver-downloads-and-installation-tutorial-for-windows-computers/"><u>Seamless Asus VG248QE Driver Downloads & Installation Tutorial for Windows Computers</u></a></li>
<li><a href="https://windows11.techidaily.com/simplified-guide-to-shift-your-qbittorrent-installation/"><u>Simplified Guide to Shift Your qBittorrent Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-window-11s-missing-clickables-problem/"><u>Solving Window 11'S Missing Clickables Problem</u></a></li>
<li><a href="https://hardware-help.techidaily.com/step-by-step-installing-and-updating-hp-printer-drivers-in-windows-11/"><u>Step-by-Step: Installing and Updating HP Printer Drivers in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/supercharge-efficiency-select-windows-software-for-success/"><u>Supercharge Efficiency: Select Windows Software for Success</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-error-0x80042306-on-windows-to-reset-successfully/"><u>Tackling Error 0X80042306 on Windows to Reset Successfully</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-unblock-application-packages-on-windows-servers/"><u>Techniques to Unblock Application Packages on Windows Servers</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/the-ultimate-guide-to-realme-v30-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>The Ultimate Guide to Realme V30 Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://windows11.techidaily.com/top-4-microcomputers-pure-windows-environment/"><u>Top 4 Microcomputers: Pure Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-power-of-dism-in-win11-image-management/"><u>Unveiling the Power of Dism in Win11 Image Management</u></a></li>
<li><a href="https://windows11.techidaily.com/why-task-managers-feature-extras-under-edge/"><u>Why Task Managers Feature Extras Under Edge?</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-insider-clandestine-context-creation-techniques/"><u>Windows 11 Insider: Clandestine Context Creation Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/zeroing-out-bloatware-windows-11-edition/"><u>Zeroing Out Bloatware: Windows 11 Edition</u></a></li>
</ul></div>
