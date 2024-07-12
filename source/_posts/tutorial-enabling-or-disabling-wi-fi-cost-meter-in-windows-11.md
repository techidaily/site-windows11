---
title: "Tutorial: Enabling or Disabling Wi-Fi Cost Meter in Windows 11"
date: 2024-07-11T21:49:26.494Z
updated: 2024-07-12T21:49:26.494Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Tutorial: Enabling or Disabling Wi-Fi Cost Meter in Windows 11"
excerpt: "This Article Describes Tutorial: Enabling or Disabling Wi-Fi Cost Meter in Windows 11"
keywords: Wi-Fi Cost Meter Guide,Windows 11 Wi-Fi Control,Manage Wi-Fi Expenses,Disable Wi-Fi Monitoring,Enabling/Disabling Wi-Fi,Windows 11 Network Settings,Optimize Wi-Fi Costs in Win11
thumbnail: https://thmb.techidaily.com/c54c6148123e508341809a9f8c11fb6ca2958cb786ab2471b34202053c6a9248.jpg
---

## Tutorial: Enabling or Disabling Wi-Fi Cost Meter in Windows 11

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

## 2\. Enable or Disable Wi-Fi Metered Connections via the Command Prompt

 If you're a power user who prefers to make system changes with a command-line tool, you can use the [Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) to enable or disable metered connection for a Wi-Fi network on Windows. Here's how you can go about it.

1. Right-click the**Start icon** or use the**Win + X** keyboard shortcut to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the terminal window, type the following command and press**Enter** to view a list of network profiles on your computer:  
`netsh wlan show profiles`  
![Network Profiles in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-profiles-in-windows.jpg)
5. Note down the Wi-Fi network name for which you want to enable or disable the metered connection option.
6. Next, run the following command to determine whether your connection is metered or unmetered.  
`netsh wlan show profile name="Wi-Fi Name"`  
 Make sure you replace**Wi-Fi Name** in the above command with the actual name of the network noted in the last step.
7. Under the**Cost settings** section, check the value next to the**Cost** field. If it reads**Fixed** , the network is set as a metered connection. Conversely, if it reads**Unrestricted** , it is designated as an unmetered connection.
8. Type the following command and press**Enter** to mark the network as a metered connection.  
`netsh wlan set profileparameter name="Wi-Fi Name" cost=Fixed`  
![Disable Metered Connection in Windows 11 Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-metered-connection-in-windows-11-using-command-prompt.jpg)

 If you want to disable the metered connection for a network, run the following command instead.

`netsh wlan set profileparameter name="Wi-Fi Name" cost=Unrestricted`

 The Command Prompt should display a message once the network profile is updated. After that, you can close the terminal window.

 Aside from the above, you can view important details about your Wi-Fi network using the Command Prompt. If you're interested in doing that, check our guide on [the best commands to manage wireless networks on Windows](https://www.makeuseof.com/tag/commands-manage-wireless-networks-windows/) .

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
<li><a href="https://video-ai-editor.techidaily.com/new-the-art-of-color-correction-in-final-cut-pro-2023/"><u>New The Art of Color Correction in Final Cut Pro 2023</u></a></li>
<li><a href="https://windows11.techidaily.com/win-1011-printer-uninstallation-a-quick-and-direct-guide/"><u>Win 10/11 Printer Uninstallation: A Quick & Direct Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/time-travel-tech-windows-7-product-key-for-11-activation/"><u>Time-Travel Tech: Windows 7 Product Key for 11 Activation</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-additional-tips-about-sinnoh-stone-for-oppo-f25-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Additional Tips About Sinnoh Stone For Oppo F25 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-the-hover-over-sensitivity-and-visibility-in-windows-11/"><u>Tailoring the Hover Over Sensitivity and Visibility in Windows 11</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-bypassing-iphones-in-app-audio-limitation-feature-for-2024/"><u>New Bypassing iPhones In-App Audio Limitation Feature for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-fbm-issues-on-your-pc-screen/"><u>Unblocking FBM Issues on Your PC Screen</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unlock-clarity-in-photos-leading-10-online-edits-at-a-glance/"><u>[Updated] Unlock Clarity in Photos  Leading 10 Online Edits at a Glance</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-master-the-art-of-live-streaming-snapchat-videos-for-2024/"><u>[Updated] Master the Art of Live Streaming Snapchat Videos for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-giggle-galore-games-a-guide-to-hilarity-filled-tiktok-quests/"><u>[New] Giggle Galore Games  A Guide to Hilarity-Filled TikTok Quests</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/unleash-your-game-top-gaming-intro-makers-for-2024/"><u>Unleash Your Game Top Gaming Intro Makers for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-explore-the-best-8-mirrorless-cameras-for-youtube-vloggers/"><u>[Updated] In 2024, Explore the Best  8 Mirrorless Cameras for YouTube Vloggers</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-in-2024-the-leading-free-platforms-for-professional-vocal-enhancement-techniques/"><u>New In 2024, The Leading Free Platforms for Professional Vocal Enhancement Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/simplify-software-management-with-new-context-menu-addition/"><u>Simplify Software Management with New Context Menu Addition</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-reimagined-analyzing-the-core-upgrades-of-windows-11/"><u>Windows Reimagined: Analyzing the Core Upgrades of Windows 11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-simplified-video-transferring-techniques-for-youtube-enthusiasts/"><u>In 2024, Simplified Video Transferring Techniques for YouTube Enthusiasts</u></a></li>
<li><a href="https://discord-videos.techidaily.com/premiere-platform-pictographs-enthralling-artwork/"><u>Premiere Platform Pictographs  Enthralling Artwork</u></a></li>
<li><a href="https://windows11.techidaily.com/1719290153300-quick-fix-guide-resurrect-your-chrome-browser-in-w11/"><u>Quick Fix Guide: Resurrect Your Chrome Browser in W11.</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-charting-the-course-to-trending-youtubers-for-2024/"><u>[Updated] Charting the Course to Trending YouTubers for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-remove-the-lock-screen-fingerprint-of-your-xiaomi-redmi-k70-by-drfone-android/"><u>In 2024, Remove the Lock Screen Fingerprint Of Your Xiaomi Redmi K70</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-steam-content-restricted-on-pc-a-step-by-step-guide/"><u>Solving Steam Content Restricted on PC: A Step-by-Step Guide</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-maximize-your-linkedin-video-views-with-these-proven-aspect-ratios-for-2024/"><u>Updated Maximize Your LinkedIn Video Views with These Proven Aspect Ratios for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-failed-speech-recognition-startup-error-windows/"><u>Addressing 'Failed' Speech Recognition Startup Error Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-windows-pc-boosters-for-speed-and-efficiency/"><u>Top 5 Windows PC Boosters for Speed and Efficiency</u></a></li>
<li><a href="https://windows11.techidaily.com/slowing-down-windows-10-shutdown-keep-programs-open/"><u>Slowing Down Windows 10 Shutdown: Keep Programs Open</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-instructions-for-software-icons-on-desktop-menu/"><u>Tailored Instructions for Software Icons on Desktop Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/unfreezing-windows-updates-top-6-strategies-to-resolve-sticking-issues/"><u>Unfreezing Windows Updates: Top 6 Strategies to Resolve Sticking Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/10-tips-to-restore-bluetooth-functionality-on-windows-11/"><u>10 Tips to Restore Bluetooth Functionality on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-network-overview-understanding-arp-caches/"><u>Windows Network Overview: Understanding ARP Caches</u></a></li>
<li><a href="https://windows11.techidaily.com/a-curated-list-of-6-essential-android-apps-for-windows-11-users/"><u>A Curated List of 6 Essential Android Apps for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/three-steps-for-ditching-microsofts-store/"><u>Three Steps for Ditching Microsoft's Store</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-icon-organization-made-simple/"><u>Windows Icon Organization Made Simple</u></a></li>
<li><a href="https://windows11.techidaily.com/snap-opera-download-into-action-windows-style/"><u>Snap Opera Download Into Action, Windows Style</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-of-windows-law-filter-mechanics-and-output/"><u>Unraveling the Mystery of Window's LAW Filter Mechanics and Output</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-whats-the-best-orientation-horizontalvertical-on-facebook-for-2024/"><u>[New] What's The Best Orientation  Horizontal/Vertical on Facebook for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-move-contacts-from-oppo-find-x6-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways to Move Contacts From Oppo Find X6 to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-in-2024-open-source-audio-sources-a-filmmakers-resource-list/"><u>New In 2024, Open Source Audio Sources A Filmmakers Resource List</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-can-i-use-a-fake-gps-without-mock-location-on-realme-c53-drfone-by-drfone-virtual-android/"><u>In 2024, How Can I Use a Fake GPS Without Mock Location On Realme C53? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-full-gpu-potential-in-windows-10-and-11-via-vram/"><u>Unleashing Full GPU Potential in Windows 10 & 11 via VRAM</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-removing-onedrive-linkage-on-windows-os/"><u>Steps for Removing OneDrive Linkage on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-student-laptop-asus-s15-oled-in-focus/"><u>The Ultimate Student Laptop: ASUS S15 OLED in Focus</u></a></li>
<li><a href="https://extra-information.techidaily.com/transforming-footage-a-guide-to-gopro-color-tweaks/"><u>Transforming Footage  A Guide to GoPro Color Tweaks</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-desk-icons-clashing-find-harmony/"><u>Windows Desk Icons Clashing - Find Harmony!</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-top-choices-for-instrumental-scores-in-video-production/"><u>In 2024, Top Choices for Instrumental Scores in Video Production</u></a></li>
<li><a href="https://windows11.techidaily.com/the-9-best-features-in-the-windows-11-february-2023-update/"><u>The 9 Best Features in the Windows 11 February 2023 Update</u></a></li>
<li><a href="https://extra-skills.techidaily.com/introduction-to-plot-and-character-dynamics-for-2024/"><u>Introduction to Plot and Character Dynamics for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/timeless-shots-perfecting-the-art-of-date-placement-in-pictures/"><u>Timeless Shots  Perfecting the Art of Date Placement in Pictures</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-unseen-wi-fi-in-windows/"><u>The Art of Unseen Wi-Fi in Windows</u></a></li>
<li><a href="https://unlock-android.techidaily.com/a-complete-guide-to-oem-unlocking-on-itel-a60-by-drfone-android/"><u>A Complete Guide To OEM Unlocking on Itel A60</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-step-by-step-process-to-master-color-grading-with-luts-in-pscc/"><u>In 2024, Step-by-Step Process to Master Color Grading with LUTs in PSCC</u></a></li>
</ul></div>
