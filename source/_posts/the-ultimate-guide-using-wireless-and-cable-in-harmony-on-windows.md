---
title: "The Ultimate Guide: Using Wireless and Cable in Harmony on Windows"
date: 2024-07-11T21:21:48.761Z
updated: 2024-07-12T21:21:48.761Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes The Ultimate Guide: Using Wireless and Cable in Harmony on Windows"
excerpt: "This Article Describes The Ultimate Guide: Using Wireless and Cable in Harmony on Windows"
keywords: Windows Connectivity Tips,Wireless PC Integration,Balancing Cables & Wireless,Harmonizing PC Connections,Optimal Windows Networking,Seamless Tech Setup Windows,Combining Cable, Wi-Fi in Windows
thumbnail: https://thmb.techidaily.com/029b0eb85077c27446243e8d1c815878a76764b760390b18a7b33382115f2d0b.jpg
---

## The Ultimate Guide: Using Wireless and Cable in Harmony on Windows

 You can have your Windows computer connected to Wi-Fi and Ethernet simultaneously, but the system won't use both connections at the same. Windows automatically configures the network adapter order priority to provide the best Internet connection via Ethernet or Wi-Fi.

 However, if you have multiple ISP connections or have a local media server, you can configure your Windows laptop to use Wi-Fi and Ethernet simultaneously. To do this, you must disable packet priority for both Wi-Fi and Ethernet network adapter.

## Why You May Need to Use Both the Wi-Fi and Ethernet Connections Simultaneously

 While you may not get an additional speed advantage when using the same ISP for your Wi-Fi and Ethernet, you can have both connections up and running as a backup for critical Internet-dependent services. Also, if you have access to multiple ISP connections, you can [merge multiple connections to increase your internet speed](https://www.makeuseof.com/how-to-merge-internet-connections/) .

 Additionally, it is also useful if you have a local server and want to be connected to both the Internet and the local server simultaneously. You can connect to the local media server via Ethernet and access the internet over Wi-Fi without dropping the connection.

 On the flip side, there are chances of packet loss due to duplicate packets being transmitted via both the Wi-Fi and Ethernet connection. Lower-end routers may also notice decreased speed due to increased load on your network device. This is part of the reasons [why you may want to replace your ISP's router](http://www.makeuseof.com/tag/reasons-replace-isp-router/) .

## How to Configure Windows to Use Wi-Fi and Ethernet Connections Simultaneously

 Since Windows automatically prioritizes the network adapter to use only one adapter at a time, you'll need to disable the packet priority option in the network adapter's network configuration. Doing so will allow Windows to use multiple connections simultaneously.

To disable packet priority and VLAN on Windows:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel** .
3. Next, go to**Network and Internet** and click on**Network and Sharing Center.**  
![control panel network change adapter settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/control-panel-network-change-adapter-settings.jpg)
4. In the left pane, click on**Change adapter settings.**
5. Right-click on your**Ethernet network adapter** and select**Properties** . Alternatively, double-click on the**Ethernet adapter** and then click on**Properties** .  
![ethernet properties configure networking control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/ethernet-properties-configure-networking-control-panel.jpg)

1. In the**Networking** tab, click the**Configure** button.
2. Next, open the**Advanced** tab.
3. Select**Priority and VLAN** under the**Property** section.
4. Click the drop-down under**Value** .  
![priority vlan disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/priority-vlan-disabled.jpg)
5. Select**Priority and VLAN Disabled.**
6. Click**OK** to save the changes.
7. Next, you need to repeat the steps for your Wi-Fi adapter. So, open Properties for your Wi-Fi adapter and set its**Priority and VLAN** value to**Priority & VLAN Disabled** .
8. Click**OK** to save the changes.

 With the network adapter priority option disabled, Windows will now use both network connections simultaneously.

## How to Set the Network Priority for Wi-Fi or Ethernet Using Interface Metric

 By default, Windows uses an automatic metric to detect and use the best network connectivity option available. However, if you need, you can manually set network priority to force Windows to use Ethernet or Wi-Fi as the preferred connectivity option.

To change network priority on Windows:

1. Press**Win + R** to open**Run** .
2. Type**ncpa.cpl** and click**OK** .  
![ncpa cpl open control panel network and sharing center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/ncpa-cpl.jpg)
3. Right-click on your Ethernet adapter and select**Properties** . If you want to prioritize your Wi-Fi adapter, choose that instead.
4. Next, select**Internet Protocol Version 4 (TCP/IPv4)** and click on**Properties** .  
![tcp ip v4 properties control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tcp-ip-v4-properties-control-panel.jpg)
5. Click the**Advanced** button in the**Properties** dialog.
6. Next, uncheck**Automatic metric** and type**5** in the**Interface metric** field.
7. Click**OK** on all the open windows to save the changes.
8. Note that if you use Internet Protocol Version 6 (IPv6) protocol, you’ll need to assign an interface metric for it as well.

 With the changes saved, Windows will prioritize your preference when multiple network adapters are connected to your computer. To undo the changes, open**Advanced TCP/IP Settings** and check the**Automatic** **metric** option. Then, click**OK** to save the changes.

## Make Your Computer Use Your Wi-Fi and Ethernet at the Same Time

 You can configure the network adapter on your computer to use both Wi-Fi and Ethernet connection simultaneously. While it has many advantages, it won't increase your Internet speed. Instead, you’ll need multiple Internet connections powering your Wi-Fi and Ethernet networks to see increased speed.

 Alternatively, if you have multiple Wi-Fi connections at home or office, you can configure your Windows computer to automatically switch to the strongest Wi-Fi network available when you move around.


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
<li><a href="https://ai-video-editing.techidaily.com/updated-complete-how-to-tutorials-of-kapwing-collage-maker/"><u>Updated Complete How-To Tutorials of Kapwing Collage Maker</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-install-hyper-v-on-windows-11-home/"><u>How to Install Hyper-V on Windows 11 Home</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-guiding-principles-of-track-matte-and-tracking-in-adobe-after-effects/"><u>New 2024 Approved Guiding Principles of Track Matte and Tracking in Adobe After Effects</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-failed-jvm-launch-windows-guide/"><u>Remedying Failed JVM Launch: Windows Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/ensure-smooth-os-operation-autoupdate-and-change-amd-drivers/"><u>Ensure Smooth OS Operation: Autoupdate & Change AMD Drivers</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-change-your-riot-games-username-and-tagline/"><u>How to Change Your Riot Games Username and Tagline</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-gps-location-on-vivo-v29e-easily-and-safely-drfone-by-drfone-virtual-android/"><u>How to Change GPS Location on Vivo V29e Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-windows-security-entry-error/"><u>Navigating Through Windows 'Security Entry Error'</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-app-on-samsung-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to Recover Deleted Photos from Android Gallery App on Samsung</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-2024-approved-filmora-x-takes-a-leap-introducing-arm-support/"><u>New 2024 Approved Filmora X Takes a Leap Introducing ARM Support</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-non-existent-device-alerts-on-windows-1011/"><u>Resolving Non-Existent Device Alerts on Windows 10/11</u></a></li>
<li><a href="https://fox-access.techidaily.com/transform-your-gaming-experience-kinemaster-pros-and-10-online-counterparts/"><u>Transform Your Gaming Experience  KineMaster Pros & 10 Online Counterparts</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-pin-gmail-to-the-taskbar-on-a-windows-pc/"><u>How to Pin Gmail to the Taskbar on a Windows PC</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-top-5-best-free-3gp-video-rotators/"><u>New 2024 Approved Top 5 Best Free 3GP Video Rotators</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-most-common-blue-screen-errors-on-windows/"><u>How to Fix the Most Common Blue Screen Errors on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-a-faulty-windows-11-temporary-storage/"><u>Fixing a Faulty Windows 11 Temporary Storage</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-awaken-the-peaceful-warrior-within-discover-the-ultimate-channels/"><u>[New] In 2024, Awaken the Peaceful Warrior Within - Discover the Ultimate Channels</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-default-usb-suspension-on-windows-11/"><u>Overcoming Default USB Suspension on Windows 11</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-2024-approved-get-filmora-free-no-cost-no-malware-no-worries/"><u>Updated 2024 Approved Get Filmora Free No Cost, No Malware, No Worries</u></a></li>
<li><a href="https://windows11.techidaily.com/end-the-ebb-and-flow-top-strategies-for-smooth-windows-streaming/"><u>End the Ebb and Flow: Top Strategies for Smooth Windows Streaming</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-strategies-for-effortless-integration-of-directories-win-11/"><u>Expert Strategies for Effortless Integration of Directories, Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-muted-audio-recordings-in-obs-studio-on-windows-11-pcs/"><u>How to Fix Muted Audio Recordings in OBS Studio on Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-incomplete-updates-in-your-windows-based-discord/"><u>Handling Incomplete Updates in Your Windows-Based Discord</u></a></li>
<li><a href="https://windows11.techidaily.com/maximize-your-taskbar-attaching-items-in-windows-11/"><u>Maximize Your Taskbar: Attaching Items in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-11-zoom-malfunction-1132/"><u>Overcoming Windows 11 Zoom Malfunction #1132</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-10-best-online-video-call-free-to-use/"><u>[New] 2024 Approved  10 Best Online Video Call (Free to Use)</u></a></li>
<li><a href="https://windows11.techidaily.com/fast-factor-essential-steps-for-assessing-lan-router-speed/"><u>Fast Factor: Essential Steps for Assessing LAN Router Speed</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-turn-off-google-location-to-stop-tracking-you-on-xiaomi-redmi-note-12-5g-drfone-by-drfone-virtual-android/"><u>How to Turn Off Google Location to Stop Tracking You on Xiaomi Redmi Note 12 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-pc-management-with-customized-windows-troubleshooters-buttons/"><u>Optimize PC Management with Customized Windows Troubleshooters Buttons</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-mastering-your-tech-skills-unlock-macs-full-screen-recording-power-with-shortcuts/"><u>[New] Mastering Your Tech Skills  Unlock Mac's Full Screen Recording Power with Shortcuts</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-transforming-facebook-videos-steps-to-high-definition-for-2024/"><u>[Updated] Transforming Facebook Videos  Steps to High Definition for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-work-around-microsoft-verified-app-restrictions/"><u>Methods to Work Around Microsoft-Verified App Restrictions</u></a></li>
<li><a href="https://windows11.techidaily.com/decreasing-cpu-and-ram-usage-tackling-unrealcefsubprocess-issues/"><u>Decreasing CPU and RAM Usage: Tackling UnrealCEFSubprocess Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/quelling-overzealousness-after-a-peak-life-period-on-windows/"><u>Quelling Overzealousness After a Peak Life Period on Windows</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/2024-approved-rise-above-the-rest-enhancing-speech-clarity-and-volume-with-filmora/"><u>2024 Approved Rise Above the Rest Enhancing Speech Clarity and Volume with Filmora</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-vivo-y55s-5g-2023-phone-frp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Vivo Y55s 5G (2023) Phone FRP Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/gpresult-command-guide-for-policy-reporting/"><u>GPResult Command Guide for Policy Reporting</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/how-to-create-a-light-sweep-shine-effect-with-filmora-for-2024/"><u>How to Create a Light Sweep (Shine) Effect with Filmora for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-reclaiming-one-headphone-harmony/"><u>2024 Approved  Reclaiming One-Headphone Harmony</u></a></li>
<li><a href="https://windows11.techidaily.com/ideal-guide-efficiently-change-heic-images-to-jpeg-format-on-windows-11/"><u>Ideal Guide: Efficiently Change HEIC Images to JPEG Format on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-system-shutdown-alerts-due-to-roblox-glitches/"><u>Overcoming System Shutdown Alerts Due to Roblox Glitches</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-pc-performance-hurdles-with-intel-graphics-updates/"><u>Remedying PC Performance Hurdles with Intel Graphics Updates</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-smartphone-solutions-top-voice-changer-applications/"><u>[New] In 2024, Smartphone Solutions  Top Voice Changer Applications</u></a></li>
<li><a href="https://windows11.techidaily.com/perfecting-the-process-setting-up-msoffice-in-windows-11/"><u>Perfecting the Process: Setting Up MSOffice in Windows 11</u></a></li>
<li><a href="https://driver-install.techidaily.com/quick-cure-fixing-drivers-delays-and-errors/"><u>Quick Cure: Fixing Drivers' Delays and Errors</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/elevating-your-earning-game-with-youtube-monetization-strategies/"><u>Elevating Your Earning Game with YouTube Monetization Strategies</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-reducing-volume-stealthily-on-computers-os-x-and-windows/"><u>[Updated] 2024 Approved  Reducing Volume Stealthily on Computers (OS X & Windows)</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-overcoming-missed-frames-in-real-time-streaming/"><u>[Updated] 2024 Approved  Overcoming Missed Frames in Real-Time Streaming</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-camera-app-malfunctions-windows-0xa00f429f-error/"><u>Overcoming Camera App Malfunctions: Windows' 0XA00F429F Error</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-blank-login-issues-on-win1011-pcs/"><u>Clearing Up Blank Login Issues on WIN10/11 PCs</u></a></li>
<li><a href="https://howto.techidaily.com/fixing-persistent-pandora-crashes-on-realme-c33-2023-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixing Persistent Pandora Crashes on Realme C33 2023 | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-explore-the-best-spots-for-acquiring-got-tones/"><u>[New] Explore the Best Spots for Acquiring GoT Tones</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-strategies-for-overcoming-windows-error-code-0x80040610/"><u>Essential Strategies for Overcoming Windows Error Code 0X80040610</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-professional-livestream-tools-outside-of-standard-obs/"><u>2024 Approved  Professional Livestream Tools Outside of Standard OBS</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-top-video-editing-software-for-pc-gopro-quik-and-more/"><u>New Top Video Editing Software for PC GoPro Quik and More</u></a></li>
<li><a href="https://extra-hints.techidaily.com/breakthrough-methodology-introducing-chapters-in-your-youtube-videos-for-2024/"><u>Breakthrough Methodology  Introducing Chapters in Your YouTube Videos for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/lessen-malware-apps-resource-usage-for-performance-gain/"><u>Lessen Malware App’s Resource Usage for Performance Gain</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-terminal-personalize-colors-and-style/"><u>Mastering Terminal: Personalize Colors & Style</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-something-went-wrong-office-error-on-windows/"><u>How to Fix the “Something Went Wrong” Office Error on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-download-fonts-for-all-languages-on-windows/"><u>How to Download Fonts for All Languages on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-for-inverted-keyboard-input-windows/"><u>Quick Fix for Inverted Keyboard Input Windows</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/best-solutions-for-asus-network-unlock-by-drfone-android/"><u>Best Solutions for Asus Network Unlock</u></a></li>
</ul></div>
