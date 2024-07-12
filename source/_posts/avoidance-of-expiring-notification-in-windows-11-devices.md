---
title: Avoidance of ‘Expiring’ Notification in Windows 11 Devices
date: 2024-07-11T22:12:33.936Z
updated: 2024-07-12T22:12:33.936Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Avoidance of ‘Expiring’ Notification in Windows 11 Devices
excerpt: This Article Describes Avoidance of ‘Expiring’ Notification in Windows 11 Devices
keywords: Windows 11 Notify Expiry Avoidance,XP Devices Alert Prevention,W11 Notification Deferral,PC Warning Halt in W11,End-Date Alert Skip Window,Stop Expiry Prompt Window,Deferring Windows 11 Notify
thumbnail: https://thmb.techidaily.com/e6889a658e4bba9c2827feba4ea063c236adc8db7e5b5caf8c7f574f84c4eaab.jpg
---

## Avoidance of ‘Expiring’ Notification in Windows 11 Devices

 Have you encountered the alarming "your Windows license will expire soon" error message on your PC? That usually happens when the Windows license on your PC is expired or deemed invalid. However, if your Windows license is indeed genuine, there might be another issue preventing Microsoft from authenticating it properly.

 In the following sections, we will discuss the common causes behind this error and provide potential solutions to fix it.

## Why Does the “Your Windows License Will Expire Soon” Error Appear?

 The "Your Windows license will expire soon" error message can occur due to several factors, and here are the most prevalent ones:

* **Windows license is invalid:** Using an unauthorized or pirated version of Windows is one of the most common reasons why you might encounter this error message.
* **Hardware changes:** Performing hardware changes, such as replacing the motherboard in your system, can also lead to activation errors on Windows.
* **Connectivity issues:** Your computer might fail to connect to the Key Management Service (KMS) server due to network-related issues, resulting in activation errors.
* **Corrupt Activation Token files:** The **Tokens.dat** file contains the activation information for your Windows installation. If this file becomes inaccessible for some reason, you may encounter the “Your Windows license will expire soon” error on Windows.  
![Your Windows License Will Expire Soon Error on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/your-windows-license-will-expire-soon-error-on-windows.jpg)

 Now that you are aware of the common causes of this error, let's now focus on the potential solutions to resolve it.

## 1\. Apply Some Preliminary Fixes

 Before you try any advanced troubleshooting tips, it’s a good idea to start with some basic fixes.

* **Restart Windows Explorer:** Temporary issues with the Windows Explorer process can sometimes trigger the “Your Windows license will expire soon” error on your PC. If it’s nothing major, you should be able to fix it by simply [restarting the Windows Explorer process](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/).
* **Run the SFC Scan:** It’s possible that Microsoft is having trouble authenticating your Windows license due to corrupt or damaged system files. To repair these files, you can try [running the System File Checker (SFC) scan on your PC](https://www.makeuseof.com/system-file-checker-sfc-windows/).
* **Scan for Malware:** Another potential factor contributing to Windows activation issues is malware infection. To address this, you can try [scanning your PC for malware using PowerShell](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/) or Microsoft Defender.

## 2\. Run the Activation Troubleshooter

 Both Windows 10 and 11 offer various troubleshooters for addressing common system issues. In this case, you can take help from the Windows Activation troubleshooter to fix any issues that may have caused the “Your Windows license will expire soon” error on your PC.

 To run the Activation troubleshooter, use these steps:

1. Press **Win + I** to open the Settings app.
2. Navigate to **System > Activation**.
3. Click the **Troubleshooter** button.  
![Running the Windows Activation Troubleshooter-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/running-the-windows-activation-troubleshooter-1.jpg)

 Wait for the troubleshooter to do its thing, and then check if it resolves the error.

## 3\. Find Your Product Key and Activate Windows

 Another thing you can do to fix this error is to find your product key using the ShowKeyPlus app and then attempt to activate Windows again. Several users on the forums reported fixing the error with this method. You can also give it a go.

1. [Download the ShowKeyPlus app](https://www.microsoft.com/store/productId/9PKVZCPRX9NV) from the Microsoft Store.
2. Open the ShowKeyPlus app using the search menu.
3. Note down the **OEM key** in the **Home** tab.  
![ShowKeyPlus App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/showkeyplus-app-on-windows.jpg)
4. Press **Win + I** to open the Settings app.
5. In the **System** tab, click on **Activation**.
6. Click the **Change** button next to **Change product key**.
7. Enter the **OEM key** noted earlier and click **Next**.
8. Click the **Activate** button to confirm.  
![Update Product Key on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/update-product-key-on-windows.jpg)

## 4\. Activate Windows Using Command Prompt

 If you are unable to activate Windows via the Settings app, you can try to activate it through the Command Prompt. To do so, make sure that your PC is connected to the internet, and then use these steps:

1. Click the **magnifying icon** on the taskbar to access the search menu.
2. Type **cmd** in the box and select **Run as administrator**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Type **slmgr /ato** in the console and press Enter.  
![Activate Windows via Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/activate-windows-via-command-prompt.jpg)

 Wait for Command Prompt to validate your product key. You will see a message confirming the outcome of the activation process, whether it was successful or not. If the activation is successful, you should not see the “Your Windows license will expire soon” error after this.

## 5\. Rebuild the Tokens.dat File

 Tokens.dat is a system file related to Windows activation and licensing. If this file somehow gets corrupted, Windows may have trouble verifying the authenticity of your license and trouble you with the “Your Windows license will expire soon” error.

 You can try rebuilding the Tokens.dat file on your PC to see if that fixes the error. Here are the steps for the same.

1. Right-click on the **Start icon** or use the **Win + X** keyboard shortcut to open the Power User menu.
2. Select **Terminal (Admin)** from the list.
3. Type the following commands one by one and press **Enter** after each.  
`net stop sppsvc  
cd %windir%\system32\spp\store\2.0  
ren tokens.dat tokens.bar  
net start sppsvc  
cscript.exe %windir%\system32\slmgr.vbs /rilc`

 Restart your computer after running the above commands and then check if you still get the “Your Windows license will expire soon” error on your PC.

## 6\. Reset the Licensing Status

 In case your Windows license is not genuine, there's a workaround to dismiss the “Your Windows license will expire soon” message. This workaround involves resetting the activation period and [hiding the Activate Windows watermark](https://www.makeuseof.com/tag/remove-activate-windows-10-watermark/) via Command Prompt. Here are the steps you can follow.

1. [Open Command Prompt with administrative privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Type **slmgr /rearm** in the console and press **Enter**.
3. Restart your PC after running the command.  
![Reset the Activation Timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-the-activation-timer.jpg)

 It's worth noting that you can only utilize the above command a few times. Eventually, you will have to obtain a genuine Windows license to eliminate the error message permanently.

## Fixing the “Your Windows License Will Expire Soon” Error on Windows

 Since Microsoft limits access to various personalization and security features on systems with inactivated Windows licenses, it’s vital to troubleshoot errors like the “Your Windows license will expire soon”. One of the above fixes should help you resolve the error message on your Windows computer. However, if nothing works, you can consider reaching out to Microsoft tech support as a last resort.

 Have you encountered the alarming "your Windows license will expire soon" error message on your PC? That usually happens when the Windows license on your PC is expired or deemed invalid. However, if your Windows license is indeed genuine, there might be another issue preventing Microsoft from authenticating it properly.

 In the following sections, we will discuss the common causes behind this error and provide potential solutions to fix it.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/mastering-camera-access-notification-controls-on-win11/"><u>Mastering Camera Access Notification Controls on Win11</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-diving-deep-the-intricacies-of-the-mukbang-phenomenon/"><u>[Updated] 2024 Approved  Diving Deep  The Intricacies of the Mukbang Phenomenon</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/2024-approved-say-goodbye-to-stock-photo-fees-free-alternatives/"><u>2024 Approved Say Goodbye to Stock Photo Fees Free Alternatives</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-top-android-and-iphone-apps-for-free-photo-overlay-artistry/"><u>[New] Top Android & iPhone Apps for FREE Photo Overlay Artistry</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-ultimate-collection-free-tiktok-edits-for-mac-users/"><u>[Updated] 2024 Approved  Ultimate Collection  Free TikTok Edits for Mac Users</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-top-5-chrome-add-ons-optimal-vimeo-video-downloads/"><u>[Updated] In 2024, Top 5 Chrome Add-Ons  Optimal Vimeo Video Downloads</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-fix-pokemon-go-route-not-working-on-motorola-g24-power-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix Pokemon Go Route Not Working On Motorola G24 Power? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-start-guide-to-windows-11-apps/"><u>Quick Start Guide to Windows 11 Apps</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/complete-guide-for-macos-sierra-patches-and-plug-ins-for-2024/"><u>Complete Guide for macOS Sierra Patches and Plug-Ins for 2024</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-in-2024-best-8-ai-video-denoise-software/"><u>Updated In 2024, Best 8 AI Video Denoise Software</u></a></li>
<li><a href="https://windows11.techidaily.com/master-syncing-how-to-rectify-non-syncing-in-ms-to-do/"><u>Master Syncing: How to Rectify Non-Syncing In MS To Do</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-enable-driver-verification-on-windows-11-pcs/"><u>How to Enable Driver Verification on Windows 11 PCs</u></a></li>
<li><a href="https://android-location.techidaily.com/3-effective-methods-to-fake-gps-location-on-android-for-your-poco-c50-drfone-by-drfone-virtual/"><u>3 Effective Methods to Fake GPS location on Android For your Poco C50 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-based-itunes-freeze-problems/"><u>Overcoming Windows-Based iTunes Freeze Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tune-your-system-control-delete-confirmations/"><u>Fine-Tune Your System: Control Delete Confirmations</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-your-way-installing-google-maps-on-pc/"><u>Navigating Your Way: Installing Google Maps on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-dive-into-and-remove-windows-usage-logs/"><u>How to Dive Into and Remove Windows Usage Logs</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-13-ways-to-fine-tune-colors-in-photoshop-effortlessly/"><u>2024 Approved  13 Ways to Fine-Tune Colors in Photoshop Effortlessly</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-long-term-snappiness-keeping-streaks-uninterrupted-for-2024/"><u>[New] Long-Term Snappiness  Keeping Streaks Uninterrupted for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-address-systemsettings-errors-in-windows-11/"><u>Steps to Address SystemSettings Errors in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-rectifying-memory-issues-on-pcs/"><u>Guide to Rectifying Memory Issues on PCs</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-amplifying-your-impact-voice-customization-in-instagram-media-for-2024/"><u>[Updated] Amplifying Your Impact  Voice Customization in Instagram Media for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-solo-side-windows-earbud-sound-problems/"><u>Resolving Solo Side Windows Earbud Sound Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-window-terminals-shutdown-procedures-entryexit-tactics/"><u>Mastering Window Terminal's Shutdown Procedures: Entry/Exit Tactics</u></a></li>
<li><a href="https://screen-capture.techidaily.com/master-mac-audio-an-in-depth-look-at-using-audacity-for-recordings-for-2024/"><u>Master Mac Audio  An In-Depth Look at Using Audacity for Recordings for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/reimagining-fn-key-usage-within-windows-11-platform/"><u>Reimagining FN Key Usage Within Windows 11 Platform</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/your-ultimate-guide-best-mac-screen-recorders/"><u>Your Ultimate Guide  Best Mac Screen Recorders</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-unraveling-failed-system-call-issues-in-win1011/"><u>Steps to Unraveling 'Failed System Call' Issues in Win10/11</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-dazzle-and-stand-out-50-free-youtube-branding-pieces/"><u>[Updated] 2024 Approved  Dazzle and Stand Out  50 FREE YouTube Branding Pieces</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-new-territory-altering-default-app-choices-in-windows-11/"><u>Navigating New Territory: Altering Default App Choices in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-0x800700e9-error-within-xbox-game-pass-and-windows-11/"><u>Rectifying 0X800700E9 Error Within Xbox Game Pass & Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/instant-change-of-windows-dashboard-background/"><u>Instant Change of Windows Dashboard Background</u></a></li>
<li><a href="https://windows11.techidaily.com/rediscover-the-lost-treasures-within-windows-11s-features/"><u>Rediscover the Lost Treasures Within Windows 11'S Features</u></a></li>
<li><a href="https://windows11.techidaily.com/innovative-windows-search-techniques-that-dont-use-ls/"><u>Innovative Windows Search Techniques That Don't Use LS</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-access-to-disabled-windows-apps/"><u>Restoring Access to Disabled Windows Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-mend-windows-network-proxy-errors/"><u>Steps to Mend Windows Network Proxy Errors</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-in-2024-unveiling-the-secrets-an-in-depth-look-at-pexelscoms-image-library/"><u>New In 2024, Unveiling the Secrets An In-Depth Look at Pexels.coms Image Library</u></a></li>
<li><a href="https://windows11.techidaily.com/regain-usb-connectivity-in-windows-os-amidst-issues/"><u>Regain USB Connectivity in Windows OS Amidst Issues</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-mastering-dynamic-volume-control-in-final-cut-pro-x-an-introduction-to-automatic-audio-ducking/"><u>New Mastering Dynamic Volume Control in Final Cut Pro X An Introduction to Automatic Audio Ducking</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-camera-app-crash-microsofts-windows-error-0xa00f425d/"><u>Eliminating Camera App Crash: Microsoft's Windows Error 0xA00F425D</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-to-reduce-high-wmi-cpu-consumption/"><u>Solutions to Reduce High WMI CPU Consumption</u></a></li>
<li><a href="https://android-frp.techidaily.com/latest-guide-how-to-bypass-sony-xperia-10-v-frp-without-computer-by-drfone-android/"><u>Latest Guide How To Bypass Sony Xperia 10 V FRP Without Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-speedier-net-transfers-on-battlenet-windows/"><u>Mastering Speedier Net Transfers on Battle.net Windows</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-unleash-your-creativity-top-14-video-editing-software-for-vloggers/"><u>Updated Unleash Your Creativity Top 14 Video Editing Software for Vloggers</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-melodic-melding-understanding-sound-transition/"><u>2024 Approved  Melodic Melding  Understanding Sound Transition</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-fixing-non-working-display-driver-on-windows-11/"><u>Guide to Fixing Non-Working Display Driver on Windows 11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-nighttime-iphone-photography-secrets-revealed/"><u>In 2024, Nighttime iPhone Photography Secrets Revealed</u></a></li>
<li><a href="https://windows11.techidaily.com/file-location-artistry-in-windows-11-exploring-best-practices-6-advanced-methods/"><u>File Location Artistry in Windows 11: Exploring Best Practices (6 Advanced Methods)</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-from-gameplay-to-recording-expert-techniques-for-ps3-screenshots/"><u>2024 Approved  From Gameplay to Recording  Expert Techniques for PS3 Screenshots</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-black-screens-with-simple-win11-tweaks/"><u>Resolving Black Screens with Simple Win11 Tweaks</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-the-secrets-of-squaring-up-making-square-format-videos-with-imovie-for-instagram/"><u>In 2024, The Secrets of Squaring Up  Making Square-Format Videos with iMovie for Instagram</u></a></li>
<li><a href="https://youtube-data.techidaily.com/n-2024-secrets-to-an-effective-youtube-closure/"><u>[New] In 2024, Secrets to an Effective YouTube Closure</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-unifying-visual-experience-in-iphone-recording/"><u>[New] Unifying Visual Experience in iPhone Recording</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-memory-management-for-edges-webview2/"><u>Mastering Memory Management for Edge's WebView2</u></a></li>
<li><a href="https://windows11.techidaily.com/stepwise-guide-to-deploying-themes-from-microsoft-store/"><u>Stepwise Guide to Deploying Themes From Microsoft Store</u></a></li>
<li><a href="https://windows11.techidaily.com/masking-task-view-button-on-win-11-bar/"><u>Masking Task View Button on Win 11 Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/preserving-torrent-performance-post-transfer-to-a-new-machine/"><u>Preserving Torrent Performance Post-Transfer to a New Machine</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-vivo-s18e-by-drfone-android/"><u>AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Vivo S18e</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-erase-no-server-errors-in-pc-apex-legends-(156-chars/"><u>Strategies To Erase No-Server Errors in PC Apex Legends (<156 Chars)</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/uilding-a-powerhouse-business-channel-in-under-5-minutes/"><u>[New] Building a Powerhouse Business Channel in Under 5 Minutes</u></a></li>
<li><a href="https://windows11.techidaily.com/preserving-windows-default-time-configuration/"><u>Preserving Windows' Default Time Configuration</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-make-your-instagram-feed-pop-with-stop-motion-animation/"><u>Updated 2024 Approved Make Your Instagram Feed Pop with Stop Motion Animation</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-navigating-steam-with-your-switch-pro-device/"><u>[Updated] In 2024, Navigating Steam with Your Switch Pro Device</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-nvidia-control-panel-not-saving-settings-in-windows-11/"><u>How to Fix the NVIDIA Control Panel Not Saving Settings in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-inactive-windows-headsets-communication-line/"><u>Fixing Inactive Windows Headset's Communication Line</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-unable-to-connect-error-with-malwarebytes-in-windows/"><u>Resolving Unable to Connect Error with Malwarebytes in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-mending-non-responsive-windows-network/"><u>Strategies for Mending Non-Responsive Windows Network</u></a></li>
</ul></div>
