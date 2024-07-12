---
title: The Art of Unseen Wi-Fi in Windows
date: 2024-07-11T21:15:28.558Z
updated: 2024-07-12T21:15:28.558Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Art of Unseen Wi-Fi in Windows
excerpt: This Article Describes The Art of Unseen Wi-Fi in Windows
keywords: Unseen Wi-Fi Windows,Hidden Wifi Tips,Stealthy Connectivity,Invisible Networks,Wi-Fi Camouflage,Discreet Signal Boost,Covert Access Windows
thumbnail: https://thmb.techidaily.com/7ec641d0887205acbcfc6836f03618d0eee863811c5fb186d0f0c958e752d87a.jpg
---

## The Art of Unseen Wi-Fi in Windows

 By default, Windows displays all available Wi-Fi networks close to your device. Even if the networks are insecure, don't have parental controls enabled, or are just named inappropriately, Windows does not make an exception to block or hide them automatically.

 If you spot such a network and want to stop it from appearing among available Wi-Fi networks to prevent your children or yourself from viewing or accidentally connecting to it, here's how you can do that.

## How to Hide or Block a Wi-Fi Network on Windows

 Follow these steps to [use the Windows Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) to stop a Wi-Fi network from showing up among the available networks:

1. Type"Command Prompt" into Windows Search, right-click on the **Command Prompt** app and then click **Run as administrator**.
2. Note the full name of the network you intend to block or hide.
3. Enter the name of the Wi-Fi network next to the SSID field in the following command:  
`netsh wlan add filter permission=block ssid="add the name of the Wi-Fi network you want to block here" networktype=infrastructure`
4. Copy and paste the command into the Command Prompt app and press **Enter**.  
![Block the Wi-Fi Network By Running a Command in Command Prompt on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/block-the-wi-fi-network-by-running-a-command-in-command-prompt-on-windows.jpg)

 If you see the message "The filter is added on the system successfully," the Wi-Fi network has been blocked, and it'll no longer appear in your Wi-Fi list. While the above steps will indeed block the Wi-Fi network, it will reappear among the available networks if the owner decides to [rename the Wi-Fi adapter](https://www.makeuseof.com/windows-11-rename-network-adapter/).

 If you change your mind and want to unblock the network you just blocked, enter the following command into the Command Prompt after entering the blocked network name:

`netsh wlan delete filter permission=block ssid="add the of the name of the Wi-Fi network you want to unblock here" networktype=infrastructure`

![Remove the Blocked Filter to Unblock the Wi-Fi Network Using the Windows Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/remove-the-blocked-filter-to-unblock-the-wi-fi-network-using-the-windows-command-prompt.jpg)

## Block Suspicious Wi-Fi Networks on Windows

 When a network is named inappropriately or looks suspicious owing to the lack of a password or protection, blocking it becomes imperative. Hopefully, now you know how to block and unblock a Wi-Fi network in the Command Prompt by running simple commands.

 While blocking other networks is essential, securing your network from prying eyes is equally important in maintaining your security and privacy.

 If you spot such a network and want to stop it from appearing among available Wi-Fi networks to prevent your children or yourself from viewing or accidentally connecting to it, here's how you can do that.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://sound-tweaking.techidaily.com/new-from-noisy-to-pristine-revolutionizing-sound-quality-with-artificial-intelligence-for-2024/"><u>New From Noisy to Pristine Revolutionizing Sound Quality with Artificial Intelligence for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-leading-edge-techniques-for-video-based-seminars/"><u>[Updated] Leading Edge Techniques for Video-Based Seminars</u></a></li>
<li><a href="https://windows11.techidaily.com/refinement-of-your-touchpad-settings-for-optimal-interaction/"><u>Refinement of Your Touchpad Settings for Optimal Interaction</u></a></li>
<li><a href="https://windows11.techidaily.com/the-complete-gamers-manual-to-winning-with-windows/"><u>The Complete Gamers' Manual to Winning With Windows</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-precision-in-preservation-expert-techniques-for-skype-call-recordings/"><u>[Updated] Precision in Preservation  Expert Techniques for Skype Call Recordings</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-contacts-from-nubia-red-magic-9-pro-by-fonelab-android-recover-contacts/"><u>Possible solutions to restore deleted contacts from Nubia Red Magic 9 Pro.</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-disabling-onedrive-icon-on-windows-11-explore/"><u>Strategies for Disabling OneDrive Icon on Windows 11 Explore</u></a></li>
<li><a href="https://fox-helps.techidaily.com/the-ultimate-resource-for-microsoft-azure-speech-services/"><u>The Ultimate Resource for Microsoft Azure Speech Services</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-elevate-your-zoom-sessions-utilizing-filters-effectively/"><u>[Updated] In 2024, Elevate Your Zoom Sessions  Utilizing Filters Effectively</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-tips-for-optimizing-wsl-2-on-modern-windows/"><u>Top 5 Tips for Optimizing WSL 2 on Modern Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-image-enhancement-building-engaging-slideshows-and-fixing-windows-11-photo-flaws/"><u>The Art of Image Enhancement: Building Engaging Slideshows & Fixing Windows 11 Photo Flaws</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-up-a-permanent-delete-toolbar-in-windows-1011s-trash/"><u>Setting Up a Permanent Delete Toolbar in Windows 10/11'S Trash</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/resolve-your-apple-iphone-12-pro-max-keeps-asking-for-outlook-password-drfone-by-drfone-ios/"><u>Resolve Your Apple iPhone 12 Pro Max Keeps Asking for Outlook Password | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/reveal-hidden-5ghz-networks-on-windows-11-quick-remedies/"><u>Reveal Hidden 5GHz Networks on Windows 11: Quick Remedies</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-elevate-with-25-customization-tips/"><u>Windows 11: Elevate with 25 Customization Tips</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unparalleled-top-5-agile-camcorders-guide-for-2024/"><u>Unparalleled Top 5 Agile Camcorders Guide for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/mac-studio-screen-and-sounds-recording-feature-for-2024/"><u>Mac Studio  Screen & Sounds Recording Feature for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/silencing-the-cacophony-soundcard-irq-fixes/"><u>Silencing the Cacophony: Soundcard IRQ Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-win1011-system-breakdown-code-0xc0000001/"><u>Addressing Win10/11 System Breakdown: Code 0xC0000001</u></a></li>
<li><a href="https://games-able.techidaily.com/tips-for-pinpointing-your-steam-user-code/"><u>Tips for Pinpointing Your Steam User Code</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-android-music-integration-a-guide-to-social-media-playlists/"><u>[New] In 2024, Android Music Integration  A Guide to Social Media Playlists</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-straightforward-steps-upside-down-video-with-vlc-software/"><u>[Updated] In 2024, Straightforward Steps  Upside-Down Video with VLC Software</u></a></li>
<li><a href="https://windows11.techidaily.com/access-control-microphone-and-camera-via-edge-protection/"><u>Access Control: Microphone and Camera via Edge Protection</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-adjusting-touchpad-sensitivity-in-windows/"><u>The Ultimate Guide to Adjusting Touchpad Sensitivity in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionize-your-security-crafting-unique-lock-patterns-for-windows-11/"><u>Revolutionize Your Security: Crafting Unique Lock Patterns for Windows 11</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-capture-twitter-gifs-on-your-computer-quickly-for-2024/"><u>[New] Capture Twitter Gifs on Your Computer Quickly for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-enhance-engagement-with-effective-yt-summary-writing/"><u>[Updated] Enhance Engagement with Effective YT Summary Writing</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-11-eliminating-invisible-logins/"><u>Troubleshooting Windows 11: Eliminating Invisible Logins</u></a></li>
<li><a href="https://windows11.techidaily.com/best-windows-11-weather-software-compared/"><u>Best Windows 11 Weather Software Compared</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-code-0x0001-complication-in-windows-11/"><u>Unraveling Code 0X0001 Complication in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-windows-no-audio-output-issue/"><u>Solving Windows: 'No Audio Output' Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/revitalizing-fall-guys-gaming-experience-after-disconnections-on-windows/"><u>Revitalizing Fall Guys Gaming Experience After Disconnections on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/altering-winterrals-visual-theme/"><u>Altering WinTerral's Visual Theme</u></a></li>
<li><a href="https://windows11.techidaily.com/tricks-save-and-access-onedrive-around-clients/"><u>Tricks: Save & Access OneDrive Around Clients</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-lost-nvidia-configuration-a-guide-for-winx-users/"><u>Restoring Lost NVIDIA Configuration: A Guide for WinX Users</u></a></li>
<li><a href="https://youtube-help.techidaily.com/how-do-you-transform-into-a-digital-entertainer-vtuber-for-2024/"><u>How Do You Transform Into a Digital Entertainer (Vtuber) for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/split-screen-style-selecting-separate-themes-for-each-windows-display/"><u>Split Screen Style: Selecting Separate Themes for Each Windows Display</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-i-recover-permanently-deleted-photos-from-spark-go-2023-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>Can I recover permanently deleted photos from Spark Go (2023)</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-resizing-discover-the-top-six-efficient-methods/"><u>Windows 11 Resizing: Discover the Top Six Efficient Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-search-bar-autonomy-in-windows-11-interface/"><u>Preventing Search Bar Autonomy in Windows 11 Interface</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-revolutionize-tiktok-live-top-techniques-from-desktop-viewers/"><u>2024 Approved  Revolutionize TikTok Live  Top Techniques From Desktop Viewers</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-closed-folder-issues-via-double-clicks-in-w10w11/"><u>Resolving Closed Folder Issues via Double-Clicks in W10/W11</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-a-dive-into-the-premium-list-of-top-10-budget-friendly-youtube-designers/"><u>[New] 2024 Approved  A Dive Into the Premium List of Top 10 Budget-Friendly YouTube Designers</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-2024-approved-the-ultimate-list-of-firefox-plugins-for-easy-facebook-video-retrieval-2023-edition/"><u>[Updated] 2024 Approved  The Ultimate List of Firefox Plugins for Easy Facebook Video Retrieval, 2023 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-list-of-6-performance-monitor-apps-for-pcs/"><u>The Ultimate List of 6 Performance Monitor Apps For PCs</u></a></li>
<li><a href="https://howto.techidaily.com/authentication-error-occurred-on-samsung-galaxy-a05-here-are-10-proven-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Authentication Error Occurred on Samsung Galaxy A05? Here Are 10 Proven Fixes | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/unlock-apple-id-without-phone-number-from-iphone-13-pro-max-by-drfone-ios/"><u>Unlock Apple ID without Phone Number From iPhone 13 Pro Max</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-lift-run-dance-select-the-most-motivating-exercise-tracks/"><u>[New] Lift, Run, Dance - Select the Most Motivating Exercise Tracks</u></a></li>
<li><a href="https://windows11.techidaily.com/reconciling-windows-game-bar-with-inferior-hardware/"><u>Reconciling Windows Game Bar with Inferior Hardware</u></a></li>
</ul></div>
