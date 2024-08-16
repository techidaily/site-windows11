---
title: "Synchronize the Seconds: Windows Time Repair Guide"
date: 2024-08-15T15:46:05.738Z
updated: 2024-08-16T15:46:05.738Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Synchronize the Seconds: Windows Time Repair Guide"
excerpt: "This Article Describes Synchronize the Seconds: Windows Time Repair Guide"
keywords: Windows Time Fix,Second Sync Tool,Windows Timeline Correction,Seconds Alignment Trick,System Time Repair Guide,Windows Clock Restore,Date & Time Patch Guide
thumbnail: https://thmb.techidaily.com/ba4d76a3836c79aa2d1ffbc408b14921a58fa2b19ac7a8b8eb3ad2286e02cfeb.jpg
---

## Synchronize the Seconds: Windows Time Repair Guide

 Is your Windows system clock out of sync? Are you receiving an error message saying “Time synchronization failed”? It may cause various issues like missing reminders or emails with the wrong timestamp. Read this guide to learn how to fix the issue and synchronize your system clock accurately.

## What Causes Time Synchronization to Fail on Windows?

 Time synchronization issues on Windows can occur for several reasons. Here are some common causes.

1. **Incorrect timezone settings:** The time set on your PC must be accurate for synchronization to work properly. If the time zone is incorrect, synchronization will fail.
2. **Firewall settings:** Firewalls block the Windows Time service from connecting to its hosts. This prevents time synchronization from occurring.
3. **System viruses and malware:** Viruses or malicious software corrupt system files related to time synchronization, causing failure.
4. **Problems with the Windows Time service:** The Windows Time (W32Time) service controls time synchronization on your system. If it's not running properly, synchronization will fail.

 Now that you know the possible causes of time synchronization failure, let’s discuss how to fix this issue.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
## 1\. Restart the Windows Time Service

 The Windows Time Service keeps the computer’s time and date synchronized with other computers on the network. If this service is stopped or not functioning, it leads to time synchronization issues.

 To restart the Windows Time Service, follow these steps:

1. Press **Win + R** on your keyboard to open the Run dialog box.
2. Type **services.msc** in the search box and hit Enter. This will open the Services window.
3. Locate the **Windows Time** service and right-click on it.
4. Select **Restart** from the context menu.  
![Restart Windows Time service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restart-windows-time-service.jpg)

 Once the service is restarted, close the window and check the time synchronization.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. Configure the Windows Time Service

 If restarting the Windows Time Service doesn't resolve the time synchronization issue, configure its settings to see if that helps.

 To configure the Windows Time Service, follow these steps:

1. [Open the Services window](https://www.makeuseof.com/windows-11-open-services-app/).
2. Double-click on **Windows Time** to open its properties window.
3. On the **General** tab, set the Startup Typeto **Automatic**.  
![Windows Time Service Status](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-time-service-status.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
<!-- affiliate ads end -->
4. Now go to Service Status and click on the **Start** button. If the service is running, click on **Stop** and then **Start**.
5. Switch to the **Log On** tab and select **Local System account**.  
![Windows Time Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-time-properties-window.jpg)
<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
6. Check the **Allow Service** **to Interact with desktop** option.
7. Click **Apply > OK** to save the changes.

 Now that you have configured the Windows Time Service, close the window. After that, restart your computer and check if time synchronization works.

## 3\. Change the Time Server

 This method is suitable when the time synchronization service fails to sync with an internet time server. It syncs to a reliable internet clock manually.

 To modify internet time settings, follow these steps:

1. [Open the Run Command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **timedate.cpl** in the text box and press Enter. This will open the Date and Time window.
3. Switch to the **Internet Time** tab and click on **Change settings**.
4. Check the box next to **Synchronize with an Internet time server**.  
![Change the Time Server](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/change-the-time-server.jpg)
5. Select a different time server from the **Server** list.
6. Click **Update now** to sync your PC with the selected time server.

 Once you perform the above action, close all windows and restart your computer. After restarting, check if the time synchronization issue is fixed.

## 4\. Add More Time Servers

 If changing the time server doesn't work, add more servers to the list. That way, Windows try different servers to keep time in sync. To add more time servers, follow these steps:

1. Press **Win + S** on your keyboard to open the Windows Search box.
2. Type **regedit** in the search box and hit Enter.
3. If UAC (User Account Control) dialog appears, click **Yes** to continue.
4. In the registry editor, navigate the following steps.  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\DateTime\Servers`
5. Right-click on the **Servers** key and select **New** \> **String Value**.  
![Add More Time Servers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/add-more-time-servers.jpg)
6. Name the new string value **ServerX**, where X is the server number.
7. Double-click on the new **String Value** and enter a valid time server URL in the Value data box.
8. Repeat the above steps until you have added all the time servers to the list.

 Once you are done, close the registry editor. After synchronization completes, close all windows and restart your computer. Then verify if the time is accurate.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## 5\. Scan for Malicious Programs

 If other methods fail to fix the time synchronization issue on your Windows computer, scan for malicious programs. Malicious software interrupts time synchronization processes and causes errors.

 To scan for malicious programs, follow these steps:

1. Press **Win + S** on your keyboard to open the Windows Search box.
2. Type **Windows Security** in the search box and hit Enter.
3. In the Windows Security window, click on **Virus & threat protection**.  
![Scan options in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/scan-options-in-windows-security.jpg)
<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Under **Current threats**, click **Scan options** and check **Full scan** from the list.  
![Full Scan Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/full-scan-windows-security.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
5. Now click **Scan now** to initiate a full scan.

 Once you perform the above action, close the Windows Security window and restart your computer. If malicious programs were responsible for the issue, it should now keep the time synchronized correctly.

## 6\. Try Some Generic Fixes

 Besides the specific solutions mentioned above, there are some general fixes that troubleshoot time synchronization problems.

 Try these suggestions to fix time synchronization failed errors:

1. [Run the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/). This tool scans system files and replaces any corrupted files that cause the time synchronization to fail.
2. [Perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) and check if that helps. It’s possible that some software or process running on your PC interferes with time synchronization. Doing a clean boot identifies the culprit and solves the issue.
3. [Temporarily disable firewall and antivirus programs](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/). Firewall or antivirus settings can sometimes block the Windows Time service from connecting to its hosts, resulting in synchronization failure. Temporarily disabling your firewall and antivirus programs can resolve this issue.
4. [Run the Windows Network Connections tool](https://www.makeuseof.com/windows-open-network-connections-tool/) to diagnose and repair network issues.

 These fixes resolve time synchronization problems on your Windows computer.

## Fixing Time Synchronization Issues on Windows

 We hope this article resolved any timing issues you encountered on your Windows computer. If the issue continues, perform a system restore. This reverses any recent modifications that could cause the issue. Meanwhile, it is advised to regularly backup your data in case of sudden system failures.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-comparing-the-leading-tunefab-screen-recorders/"><u>[New] 2024 Approved  Comparing the Leading Tunefab Screen Recorders</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-easy-access-luxury-free-access-to-your-dreamset-of-50-banners/"><u>[New] 2024 Approved  Easy-Access Luxury - Free Access to Your Dreamset of 50 Banners!</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-seamless-skype-call-recordings-a-cross-platform-approach/"><u>[New] 2024 Approved  Seamless Skype Call Recordings  A Cross-Platform Approach</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-unleashing-your-viewing-experience-screen-recording-solutions/"><u>[New] 2024 Approved  Unleashing Your Viewing Experience  Screen Recording Solutions</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-essential-gif-sharing-on-snapchat-easy-tutorial/"><u>[New] In 2024, Essential Gif Sharing on Snapchat [Easy Tutorial]</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-insta-rapid-rise-mastering-engagement-with-likes-and-vids/"><u>[New] Insta Rapid Rise  Mastering Engagement with Likes & Vids</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-transforming-your-tiktok-profile-altering-account-numbers-for-2024/"><u>[New] Transforming Your TikTok Profile  Altering Account Numbers for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-unleashing-originality-in-virtual-meme-worlds/"><u>[New] Unleashing Originality in Virtual Meme Worlds</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-crafting-a-personalized-auditory-experience-on-ios/"><u>[Updated] Crafting a Personalized Auditory Experience on iOS</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-designing-youtube-ads-that-grab-attention-a-compreeher-guide/"><u>[Updated] Designing Youtube Ads That Grab Attention  A Compreeher Guide</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-ideal-6-innovative-minecraft-dwellings/"><u>[Updated] Ideal 6 Innovative Minecraft Dwellings</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-digital-doppelganger-deliberation-building-caricatured-characters/"><u>[Updated] In 2024, Digital Doppelganger Deliberation  Building Caricatured Characters</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-proper-techniques-for-streaming-from-gopro-camera-to-social-networks/"><u>[Updated] In 2024, Proper Techniques for Streaming From GoPro Camera to Social Networks</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-leading-gimbal-selections-for-iphoneandroiddslrs-revealed/"><u>[Updated] Leading Gimbal Selections for iPhone/Android/DSLRs Revealed</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-seeking-outstanding-user-contributions/"><u>[Updated] Seeking Outstanding User Contributions</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-ultimate-list-of-3d-animation-and-modelling-programs/"><u>[Updated] The Ultimate List of 3D Animation and Modelling Programs</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-trust-the-right-sources-for-safe-and-effective-view-count-increase/"><u>[Updated] Trust the Right Sources for Safe and Effective View Count Increase</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-sightline-synopsis-study/"><u>2024 Approved  Sightline Synopsis Study</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-move-contacts-from-honor-90-lite-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways to Move Contacts From Honor 90 Lite to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/6-cutting-edge-windows-programs-for-media-editing/"><u>6 Cutting-Edge Windows Programs for Media Editing</u></a></li>
<li><a href="https://windows11.techidaily.com/cease-windows-system-notification-for-upgrades/"><u>Cease Windows System Notification for Upgrades</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-task-managers-initial-screen-on-win11/"><u>Customizing Task Manager's Initial Screen on Win11</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/discovering-the-best-10-online-tools-for-vimeo-videos/"><u>Discovering the Best  10 Online Tools for Vimeo Videos</u></a></li>
<li><a href="https://facebook.techidaily.com/effective-techniques-to-unlock-fb-accounts-in-emergency/"><u>Effective Techniques to Unlock Fb Accounts in Emergency</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-initiating-the-snip-and-sketch-function-on-win-11/"><u>Efficiently Initiating the Snip and Sketch Function on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-external-monitors-without-graphics-card/"><u>Enabling External Monitors without Graphics Card</u></a></li>
<li><a href="https://windows11.techidaily.com/ending-dual-access-to-your-camera-error-0xa00f4243/"><u>Ending Dual Access to Your Camera (Error 0xA00F4243)</u></a></li>
<li><a href="https://windows11.techidaily.com/enlighten-your-windows-with-free-handbrake/"><u>Enlighten Your Windows with Free HandBrake</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-privacy-with-best-windows-crypto-apps-152-chars/"><u>Ensuring Privacy with Best Windows Crypto Apps (152 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-preparations-for-revitalizing-your-pc-with-windows/"><u>Essential Preparations for Revitalizing Your PC with Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/harnessing-the-power-of-microsofts-ai-code-helper/"><u>Harnessing the Power of Microsoft's AI Code Helper</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-migrate-android-data-from-google-pixel-8-pro-to-new-android-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Migrate Android Data From Google Pixel 8 Pro to New Android Phone? | Dr.fone</u></a></li>
<li><a href="https://win-solutions.techidaily.com/how-to-resolve-frostpunk-crashes-on-your-pc/"><u>How To Resolve Frostpunk Crashes On Your PC</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-card-on-infinix-note-30i-online-without-jailbreak-by-drfone-android/"><u>How to Unlock SIM Card on Infinix Note 30i online without jailbreak</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-premier-audio-broadcasts-networks/"><u>In 2024, Premier Audio Broadcasts Networks</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-imei-unlokers-for-iphone-15-and-android-phones-by-drfone-ios/"><u>In 2024, Top IMEI Unlokers for iPhone 15 and Android Phones</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/mastering-management-top-8-tools-for-effective-task-allocation/"><u>Mastering Management  Top 8 Tools for Effective Task Allocation</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-hello-fingerprint-setup-on-11/"><u>Mastering Windows Hello Fingerprint Setup on 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-xp-error-code-0x80300024/"><u>Navigating Windows XP Error Code: 0X80300024</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/new-auto-translate-youtube-videos-into-different-languages-for-2024/"><u>New Auto Translate YouTube Videos Into Different Languages for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/no-more-fbm-hurdles-top-windows-troubleshooting-tips/"><u>No More FBM Hurdles: Top Windows Troubleshooting Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-credential-vault-hurdles/"><u>Overcoming Credential Vault Hurdles</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-invalid-verification-error-by-steams-vac/"><u>Overcoming Invalid Verification Error by Steam's VAC</u></a></li>
<li><a href="https://windows11.techidaily.com/perfecting-taskbar-setup-in-windows-11/"><u>Perfecting Taskbar Setup in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/personalize-your-digital-notepad-a-guide-to-windows-11-customization/"><u>Personalize Your Digital Notepad: A Guide to Windows 11 Customization</u></a></li>
<li><a href="https://windows11.techidaily.com/precision-tools-for-crafting-custom-windows-filename-dates/"><u>Precision Tools for Crafting Custom Windows Filename Dates</u></a></li>
<li><a href="https://windows11.techidaily.com/procedures-for-upholding-true-windows-time-values/"><u>Procedures for Upholding True Windows Time Values</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-to-resolving-pin-check-errors-on-windows-devices/"><u>Quick Guide to Resolving Pin Check Errors on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/reconnecting-to-ea-servers-in-a-windows-environment/"><u>Reconnecting to EA Servers in a Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/reestablishing-clear-audio-conversations-on-valorant-pc/"><u>Reestablishing Clear Audio Conversations on Valorant PC</u></a></li>
<li><a href="https://windows11.techidaily.com/rejoining-lost-astra-pilot-on-windows-11-machines/"><u>Rejoining Lost Astra Pilot on Windows 11 Machines</u></a></li>
<li><a href="https://windows11.techidaily.com/scrutinizing-underused-windows-features-for-system-checks/"><u>Scrutinizing Underused Windows Features for System Checks</u></a></li>
<li><a href="https://windows11.techidaily.com/silencing-the-audio-stutter-taming-winirq-errors/"><u>Silencing the Audio Stutter: Taming WinIRQ Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-solutions-to-prevent-not-working-on-your-pc/"><u>Swift Solutions to Prevent 'Not Working' On Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/the-clarity-compass-directing-you-through-a-fuzzy-screen-fix-up/"><u>The Clarity Compass: Directing You Through a Fuzzy Screen Fix-Up</u></a></li>
<li><a href="https://windows11.techidaily.com/the-gateway-to-information-conquering-windows-qr-code-scan/"><u>The Gateway to Information: Conquering Windows' QR Code Scan</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-picking-a-software-dependency-provider/"><u>The Ultimate Guide to Picking a Software Dependency Provider</u></a></li>
<li><a href="https://tech-haven.techidaily.com/1722137877059-top-9-benefits-of-switching-to-chatgpt-plus-now/"><u>Top 9 Benefits of Switching to ChatGPT Plus Now!</u></a></li>
<li><a href="https://windows11.techidaily.com/tracking-windows-logins-identifying-successes-and-failures/"><u>Tracking Windows Logins: Identifying Successes & Failures</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-registry-shortcomings-solutions/"><u>Unveiling Windows Registry Shortcomings: Solutions</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-one-look-one-feel-the-ultimate-guide-to-color-matching-in-final-cut-pro/"><u>Updated One Look, One Feel The Ultimate Guide to Color Matching in Final Cut Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/why-is-nvidia-control-panel-inaccessible-on-win11/"><u>Why Is Nvidia Control Panel Inaccessible on Win11?</u></a></li>
</ul></div>
