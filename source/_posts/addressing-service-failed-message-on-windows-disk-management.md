---
title: Addressing 'Service Failed' Message on Windows Disk Management
date: 2024-07-11T22:20:11.463Z
updated: 2024-07-12T22:20:11.463Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing 'Service Failed' Message on Windows Disk Management
excerpt: This Article Describes Addressing 'Service Failed' Message on Windows Disk Management
keywords: Service Failure in Disk Manager,Windows Disk Error Fix,Manage Disk, Service Issue,Resolve Disk Service Errors,Windows Disk Services Problems,Stop 'Service Failed' Window,Addressing Disk Management Error
thumbnail: https://thmb.techidaily.com/606acaddc3ba9faf4d73376f1e2c554744034ba5ad463dfb82faf3689dc358c1.jpg
---

## Addressing 'Service Failed' Message on Windows Disk Management

 Disk Management is a Windows utility with which users can partition and rename drives. However, some users have reported this Windows error message pops up when they try to access Disk Management: “Disk Management could not start Virtual Disk Service (VDS).” A variation of that error message also says, “Unable to connect to Virtual Disk Service.”

 This error means users can’t access and utilize Disk Management. The issue more typically arises in remote connection environments. This is how you can fix the Disk Management Virtual Disk Service error in Windows 10 and 11\.

## 1\. Disconnect External Drives From Your PC

 First, try disconnecting all non-essential USB devices from your PC. Make sure there aren’t any external drives, USB sticks, mobile phones, or card readers connected to your PC. Then try [opening the Disk Management utility](https://www.makeuseof.com/ways-open-disk-management-windows-10/) again.

## 2\. Run System File and Image Repair Scans

 System file corruption could feasibly cause the Disk Management Virtual Disk Service error. So, check the integrity of system files on your PC with the Windows System File Checker command-line tool. That utility will also usually repair corrupted system files detected. This [how to run the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) guide includes instructions for utilizing that tool.

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command.jpg)

 If SFC detects corrupted system files but can’t repair them, you may need to run a Deployment Image Service Management scan. That’s a tool for fixing issues with the Windows system image. You can run that utility by executing this Deployment Image command within the Command Prompt:

`DISM /Online /Cleanup-Image /RestoreHealth`

## 3\. Enable and Run the Virtual Disk Service

 A disabled Virtual Disk service is a common cause of the Disk Management VDS error. Disk Management can’t connect to VDS when the Virtual Disk service is disabled. So, try enabling and running the Virtual Disk service like this:

1. To access Run, press **Win + R**.
2. Enter **services.msc** inside the Run command dialog and press **Return**.
3. Scroll down and double-click on **Virtual Disk** within the Services window.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/services-window.jpg)
4. Select the **Automatic** setting on the **Startup type** menu.  
![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/startup-type-drop-down-menu.jpg)
5. Press **Start** within the Virtual Disk Properties window.

1. Select the window’s **Log on** tab.
2. Next, click the **Allow service to interact with desktop** checkbox to select that option.  
![The Log On tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/log-on-tab.jpg)
3. Click **Apply** to save your new Virtual Disk service settings.
4. Select the Virtual Disk Properties window’s **OK** option.
5. If you encounter the Disk Management VDS error within a remote connection environment, repeat the above steps to check the Virtual Disk service is enabled on both the local and remote PCs.

## 4\. Allow Remote Volume Management Through Windows Defender Firewall

 Windows Defender Firewall can cause the Disk Management VDS error by blocking that utility from connecting with Virtual Disk. So, make sure Remote Volume Management is allowed through that firewall on both local and remote PCs. Our [guide to allowing apps through the Windows firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) includes instructions for applying this resolution.

![The allowed apps firewall settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/firewall-options.jpg)

## 5\. Turn Off Third-Party Security Software

 If your PC includes a third-party security (antivirus) app, that software could be blocking Disk Management from establishing a VDS connection. Remember that many third-party security apps also incorporate firewalls along with antivirus components. So, try temporarily disabling both the firewall and antivirus module within your third-party security software.

 To disable the firewall part, look for a turn-off firewall option within the settings tab of your antivirus software. You can usually turn off antivirus shields by right-clicking on security apps’ system tray icons and selecting disable options on their context menus. Select to turn off the antivirus shield for about an hour if you can, and try accessing Disk Management again to see if the issue persists.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

## Manage Your Drives With Disk Management Again

 The potential solutions in this guide aren’t totally guaranteed, but they’re the most likely ways to fix the Disk Management VDS error on a Windows PC. So, maybe one will get the Disk Management VDS issue sorted on your PC. Then you can manage and partition your drives with Disk Management again.

 This error means users can’t access and utilize Disk Management. The issue more typically arises in remote connection environments. This is how you can fix the Disk Management Virtual Disk Service error in Windows 10 and 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/bring-life-to-windows-11-desktops-with-interactive-wallpapers/"><u>Bring Life to Windows 11 Desktops with Interactive Wallpapers</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-world-meal-mastery-favorite-international-creations/"><u>[Updated] 2024 Approved  World Meal Mastery  Favorite International Creations</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-mastering-the-art-of-mobile-based-interview-and-travel-podcasts/"><u>[New] Mastering the Art of Mobile-Based Interview & Travel Podcasts</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-win-1011s-xc0f1103f-with-geforce-error/"><u>Addressing Win 10/11'S XC0F1103F with GeForce Error</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/in-2024-the-ultimate-guide-to-free-vob-video-editing-tools/"><u>In 2024, The Ultimate Guide to Free VOB Video Editing Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-why-files-cant-sync-in-steam-library/"><u>Addressing Why Files Can't Sync in Steam Library</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-whats-buzzing-the-social-sphere-tiktok-and-twitter-hits/"><u>[New] 2024 Approved  What's Buzzing the Social Sphere? TikTok & Twitter Hits</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/video-editing-on-a-mac-here-are-10-fantastic-vegas-pro-alternatives/"><u>Video Editing on a Mac? Here Are 10 Fantastic Vegas Pro Alternatives</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-making-every-frame-count-in-instagram-videos/"><u>In 2024, Making Every Frame Count in Instagram Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/adopting-a-context-menu-toolbar-alert-for-routine-update-checks-on-windows-11plus11/"><u>Adopting a Context Menu Toolbar Alert for Routine Update Checks on Windows 11+11</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/mastering-the-art-of-old-facebook-features-step-by-step-for-2024/"><u>Mastering the Art of Old Facebook Features  Step-by-Step for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/alter-ip-settings-with-confidence-windows-11/"><u>Alter IP Settings with Confidence (Windows 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/banish-os-requirement-warning-labels-in-windows-11/"><u>Banish OS Requirement Warning Labels in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/banish-the-blues-of-a-non-opening-notepad-streamlined-fixes-for-windows-pcs/"><u>Banish the Blues of a Non-Opening Notepad: Streamlined Fixes for Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/a-guide-to-overcoming-windows-resolution-riddles/"><u>A Guide to Overcoming Windows Resolution Riddles</u></a></li>
<li><a href="https://windows11.techidaily.com/bootable-windows-11-flashdrive-top-3-efficient-techniques/"><u>Bootable Windows 11 Flashdrive: Top 3 Efficient Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/bridge-the-mc-lan-chasm-7-key-fixes-for-windows-users/"><u>Bridge the MC LAN Chasm: 7 Key Fixes for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-blunders-fix-windows-color-management-fiascos/"><u>Bypassing Blunders: Fix Windows Color Management Fiascos</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-spotlight-on-cities-for-virtual-viewing/"><u>[Updated] Spotlight on Cities for Virtual Viewing</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerate-profit-with-windows-11-pro-capture-best-offers/"><u>Accelerate Profit with Windows 11 Pro: Capture Best Offers</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-accelerate-how-to-swiftly-broadcast-playlists/"><u>[Updated] In 2024, Accelerate  How To Swiftly Broadcast Playlists</u></a></li>
<li><a href="https://windows11.techidaily.com/1719369938575-run-a-free-locally-stored-gpt-on-your-pc-with-gpt4all/"><u>Run a Free, Locally-Stored GPT on Your PC with GPT4All.</u></a></li>
<li><a href="https://windows11.techidaily.com/bridging-gap-restore-invisible-bluetooth-items-mgr/"><u>Bridging Gap: Restore Invisible Bluetooth Items Mgr</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-win11-boot-time-quick-tips-for-speedier-launches/"><u>Boosting Win11 Boot Time: Quick Tips for Speedier Launches</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-webcam-selection-guide-the-10-best-picks-unveiled/"><u>[New] 2024 Approved  Webcam Selection Guide  The 10 Best Picks Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-why-obs-wont-start-on-your-pc/"><u>Breaking Down Why OBS Won't Start on Your PC</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-captivating-clips-with-cleverly-chosen-lights/"><u>[New] Captivating Clips with Cleverly Chosen Lights</u></a></li>
<li><a href="https://windows11.techidaily.com/adapting-oculus-quest-3-for-windows-os-vr-environment/"><u>Adapting Oculus Quest 3 for Windows OS VR Environment</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/the-art-of-audio-amalgamation-in-vimeo-videos-for-2024/"><u>The Art of Audio Amalgamation in Vimeo Videos for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/asus-vivobook-s-15-the-ultimate-blend-of-style-and-functionality/"><u>ASUS Vivobook S 15: The Ultimate Blend of Style & Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-metric-monitoring-of-wifi-networks-via-win11-settings/"><u>Adjusting Metric Monitoring of Wifi Networks via Win11 Settings</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-samsung-galaxy-a15-4g-pin-codepattern-lockpassword-by-drfone-android/"><u>In 2024, How to Unlock Samsung Galaxy A15 4G PIN Code/Pattern Lock/Password</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-silencing-windows-11-alerts-benefits-unveiled/"><u>Avoid Silencing Windows 11 Alerts: Benefits Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerate-taskbar-interaction-with-bings-ai/"><u>Accelerate Taskbar Interaction with Bing's AI</u></a></li>
<li><a href="https://windows11.techidaily.com/altering-windows-service-for-installation-controls/"><u>Altering Windows Service for Installation Controls</u></a></li>
<li><a href="https://windows11.techidaily.com/begin-your-media-adventure-windows-media-player/"><u>Begin Your Media Adventure: Windows Media Player</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/android-users-ultimate-selection-top-10-fb-video-extractor-tools-for-2024/"><u>Android Users' Ultimate Selection  Top 10 FB Video Extractor Tools for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/fix-cant-take-screenshot-due-to-security-policy-on-realme-c55-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Cant Take Screenshot Due to Security Policy on Realme C55 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/beginners-blueprint-to-conquering-diablo/"><u>Beginner’s Blueprint to Conquering Diablo</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-reimagining-home-entertainment-with-lgs-bp550-update/"><u>2024 Approved  Reimagining Home Entertainment with LG's BP550 Update</u></a></li>
<li><a href="https://windows11.techidaily.com/8-essential-fixes-for-resistant-windows-pin-locks/"><u>8 Essential Fixes for Resistant Windows PIN Locks</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-efficiency-best-keys-for-auto-clicking/"><u>Boost Efficiency: Best Keys for Auto Clicking</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/how-to-transfer-from-apple-iphone-6s-to-samsung-galaxy-s20-drfone-by-drfone-transfer-from-ios/"><u>How to Transfer from Apple iPhone 6s to Samsung Galaxy S20? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/automation-made-simple-windows-task-scheduler-batch/"><u>Automation Made Simple: Windows Task Scheduler Batch</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-immerse-in-imagery-top-10-sticker-apps-for-appleandroid-users/"><u>[New] Immerse in Imagery – Top 10 Sticker Apps for Apple/Android Users</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-realme-11-5g-phone-without-pin-by-drfone-android/"><u>In 2024, How to Unlock Realme 11 5G Phone without PIN</u></a></li>
<li><a href="https://windows11.techidaily.com/8-essential-steps-to-bring-back-lost-windows-files/"><u>8 Essential Steps to Bring Back Lost Windows Files</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-beginners-bible-to-your-youtube-audio-visual-arsenal/"><u>[Updated] In 2024, Beginner's Bible to Your YouTube Audio-Visual Arsenal</u></a></li>
<li><a href="https://windows11.techidaily.com/aoemi-made-simple-unifying-dual-window-desktops/"><u>AOEMi Made Simple: Unifying Dual Window Desktops</u></a></li>
<li><a href="https://windows11.techidaily.com/bypass-windows-11-pc-life-hacks-for-older-systems/"><u>Bypass Windows 11: PC Life Hacks for Older Systems</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/in-2024-smooth-operator-the-top-free-online-video-stabilizers-compared/"><u>In 2024, Smooth Operator The Top Free Online Video Stabilizers Compared</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-steam-downloads-enhancing-windows-performance/"><u>Boosting Steam Downloads: Enhancing Windows Performance</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-make-unforgettable-music-videos-from-your-favorite-photos-with-these-top-tools-for-2024/"><u>Updated Make Unforgettable Music Videos From Your Favorite Photos with These Top Tools for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/accessing-the-internet-without-a-browser-post-setup/"><u>Accessing the Internet Without a Browser Post-Setup</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-playlist-perfection-weaving-youtube-videos-into-webpages/"><u>[New] Playlist Perfection  Weaving YouTube Videos Into Webpages</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-time-management-for-weekly-video-conferencing-sessions-for-2024/"><u>[Updated] Time Management for Weekly Video Conferencing Sessions for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/8-ways-to-fix-the-windows-pin-not-working-in-windows-11-and-11/"><u>8 Ways to Fix the Windows PIN Not Working in Windows 11 & 11</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-perfecting-visuals-on-instagram-a-video-guide/"><u>[New] Perfecting Visuals on Instagram  A Video Guide</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-premiere-streaming-for-performance-artists/"><u>[Updated] Premiere Streaming for Performance Artists</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/2024-approved-best-10-hindi-video-translators-with-step-by-step-guidance/"><u>2024 Approved Best 10 Hindi Video Translators with Step-by-Step Guidance</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerate-win-valorant-loading-times-quickly/"><u>Accelerate Win-Valorant Loading Times Quickly</u></a></li>
<li><a href="https://review-topics.techidaily.com/insert-signature-in-wpd-file-by-ldigisigner-sign-a-word-sign-a-word/"><u>Insert signature in .wpd file</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-how-to-get-verified-on-instagram-6-tips-to-grow-followers/"><u>[Updated] In 2024, How to Get Verified on Instagram  6 Tips to Grow Followers</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-facebook-content-at-your-fingertips-best-downloader-apps-for-ios/"><u>In 2024, Facebook Content at Your Fingertips  Best Downloader Apps for iOS</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-10-must-have-plug-ins-for-final-cut-cinematography/"><u>2024 Approved  10 Must-Have Plug-Ins for Final Cut Cinematography</u></a></li>
<li><a href="https://windows11.techidaily.com/camouflage-linguistic-separator-on-win11-status-bar/"><u>Camouflage Linguistic Separator on Win11 Status Bar</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/top-10-airplay-apps-in-oppo-find-x7-ultra-for-streaming-drfone-by-drfone-android/"><u>Top 10 AirPlay Apps in Oppo Find X7 Ultra for Streaming | Dr.fone</u></a></li>
</ul></div>
