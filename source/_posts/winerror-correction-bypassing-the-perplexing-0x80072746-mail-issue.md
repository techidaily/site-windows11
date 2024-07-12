---
title: "WinError Correction: Bypassing the Perplexing 0X80072746 Mail Issue"
date: 2024-07-11T21:33:33.816Z
updated: 2024-07-12T21:33:33.816Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes WinError Correction: Bypassing the Perplexing 0X80072746 Mail Issue"
excerpt: "This Article Describes WinError Correction: Bypassing the Perplexing 0X80072746 Mail Issue"
keywords: WinError Fix Guide,Error 0X80072746 Resolution,Bypassing Windows Error,Email Correction Steps,0X80072746 Solutions,Troubleshoot WinError,Overcome Mail Error Code
thumbnail: https://thmb.techidaily.com/7e6ef4621c16da1cc3052591a34945a12afa2e9a08849b7c43976fa93370f632.jpg
---

## WinError Correction: Bypassing the Perplexing 0X80072746 Mail Issue

 The Mail app error 0x80072746 often occurs when users try to access their newly received emails, and it indicates network-related issues within Windows. This error message typically points towards a problem with the mail server or the network connection.

 Below, we take a look at the different troubleshooting methods that can help fix this issue for good.

## 1\. Allow svchost.exe in the Firewall

 The 0x80072746 error in the Mail app commonly occurs when a third-party firewall interferes with a critical Windows program called svchost.exe.

 This process is responsible to host various essential services necessary for the proper functioning of your Windows operating system. Among these services, the Mail app heavily relies on svchost.exe to establish network connections and download messages.

 If you have installed a third-party security program on your computer, there is a possibility that it is mistakenly blocking svchost.exe. This might be preventing the Mail app from fetching or sending emails, leading to the 0x80072746 error.

 To address this issue, you can check your firewall settings and whitelist svchost.exe. Alternatively, you can [temporarily disable the security program](https://www.makeuseof.com/windows-features-error-0x80071a90/) and check if that fixes the problem.

![Disable antivirus in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-antivirus-windows.jpg)

 It's worth noting that the exact steps of performing this action can vary depending on the specific program you are using. Typically, this information is available in the application settings of the app.

## 2\. Modify VPN Settings

 Active VPNs can also interfere with the Mail app's ability to establish network connections, leading to the problem at hand.

 If you are using a VPN on your computer, you can try the following steps to troubleshoot the issue:

* **Disconnect from the VPN**: Temporarily disable the VPN and then try loading messages in the Mail app again. If this fixes the problem, it implies that VPN was causing the problem.
* **Whitelist Mail app or email server**: Launch the VPN settings and look to whitelist the Mail app or email server’s IP address to prevent VPN from interfering with the program’s network connections.
* **Modify VPN protocols or settings**: If it is essential to use the VPN while using the Mail app, you can modify the protocol and check if that makes any difference.

 Here is how you can modify the VPN settings to resolve the Mail app error:

1. Press the **Win** \+ **I** keys together to open the Settings app.
2. Choose **Network & Internet** \> **VPN**.  
![VPN settings in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/vpn-settings-windows.jpg)
3. Enable the **Allow VPN over metered network** option.  
![Allow VPN over metered network in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/vpn-over-metered-network.jpg)
4. Now, head over to the "Related settings" section and choose **Change adapter options**.
5. Right-click on your LAN (Wi-Fi) connectivity and choose **Properties** from the context menu.
6. Select **Internet Protocol Version 6 (TCP/PV6)** and click **OK** to save the changes.

 You can now close the Settings app and check if the issue is resolved.

## 3\. Set Up Your Account Manually

 Another reason behind the Mail error 0x80072746 is incorrect server settings and incompatibility with specific email providers, which typically occurs when you rely on the automatic setup process.

 You can eliminate these potential issues with the automatic configuration process by setting up your account manually.

 Therefore, if you previously configured your Mail account using the automatic setup process, you might want to try setting it up manually this time in order to bypass any errors or conflicts.

 Here is how you can do that:

1. Launch the Mail client and click on the **gear icon** at the bottom.
2. Choose **Manage Accounts**.  
![Manage accounts option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/manage-accounts.jpg)
3. Select the problematic email and choose **Delete account from this device** from the options available.  
![Delete the account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/delete-mail-app.jpg)
4. Confirm your action in the next window.
5. Once the email account is removed, launch the official website of your email provider and copy the manual settings for IMAP. If these settings are not available, choose POP3\.

1. Now, head back to the Mail client and launch the settings.
2. Head over to the Manage Account section and choose **Add account**.  
![Add account option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/add-account.jpg)
3. Scroll down and choose **Advanced Setup**.  
![Choose Advanced setup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/advanced-setup-option.jpg)
4. Click on **Internet email** and enter the manual settings you copied earlier.  
![Click Internet email](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/internet-email-option.jpg)
5. Finally, click on **Sign in** and check if the issue is resolved.

## 4\. Update the Mail App

 Your Mail app might also be outdated, which is preventing it from being fully compatible with the latest email server configurations and security protocols, leading to the error at hand.

 To check if this is the case, you can head over to Microsoft Store and check for the pending updates that might be available for the Mail app. If you find any, take your time to install them and then check if the Mail app can display emails.

 Follow these steps to proceed:

1. Click on the **Microsoft Store icon** in the taskbar to launch the program.
2. Choose the **Library icon** in the bottom left pane.
3. In the following window, click on the **Get updates** button. This should display all the available updates for the installed apps. MS Store will begin to download them automatically.  
![The Get updates button in MS Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-get-updates-button.jpg)
4. Wait for the updates to download and check if the problem is resolved.

 While you are at it, we also recommend installing any system updates that might be available in the Settings app.

## 5\. Fix Corruption Issues Within the Mail App

 If updating the application did not help, there are also some other fixes that can help you resolve any corruption issues within the Mail app that might be leading to the problem. This involves [repairing and resetting the Mail application](https://www.makeuseof.com/mail-app-cant-get-mail-windows/).

 The Repair option attempts to fix any damaged or missing files that might be contributing to the error, while the Reset option will restore the default, error-free state of the application. It is important to note, however, that while these solutions are effective at fixing the underlying problem, you are likely to lose your settings and preferences within the Mail app.

## Multiple Ways to Fix the Windows Mail App

 Encountering issues with the Mail app can be incredibly frustrating, especially if you rely on it for your important work. Hopefully, the solutions listed above will help you fix the 0x80072746 error once and for all.

 To avoid problems like this from occurring in the future, we recommend keeping your Mail app up-to-date and whitelisting it in the firewall as well as the VPN.

 Below, we take a look at the different troubleshooting methods that can help fix this issue for good.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/windows-wifi-wisdom-accelerating-network-speed-assessment/"><u>Windows WiFi Wisdom: Accelerating Network Speed Assessment</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-forth-dormant-windows-11-control-panel-options/"><u>Bring Forth Dormant Windows 11 Control Panel Options</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-6-proven-ways-to-unlock-xiaomi-14-phone-when-you-forget-the-password-by-drfone-android/"><u>In 2024, 6 Proven Ways to Unlock Xiaomi 14 Phone When You Forget the Password</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-windows-modern-standbys-drawbacks/"><u>Decoding Windows Modern Standby's Drawbacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-failed-speech-recognition-launch-in-windows/"><u>Troubleshooting Failed Speech Recognition Launch in Windows</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-tecno-camon-30-pro-5g-to-mac-drfone-by-drfone-android/"><u>In 2024, How to Mirror Tecno Camon 30 Pro 5G to Mac? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/brighten-control-navigating-windows-11-display-settings/"><u>Brighten Control: Navigating Windows 11 Display Settings</u></a></li>
<li><a href="https://techidaily.com/recover-apple-iphone-6s-plus-data-from-itunes-backup-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>Recover Apple iPhone 6s Plus Data From iTunes Backup | Dr.fone</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-in-2024-how-to-be-a-good-podcast-host/"><u>New In 2024, How to Be a Good Podcast Host</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-workflow-efficiency-mastering-flow-launcher/"><u>Boost Workflow Efficiency: Mastering Flow Launcher</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-10-telegram-spy-tools-on-vivo-y100-for-parents-drfone-by-drfone-virtual-android/"><u>Top 10 Telegram Spy Tools On Vivo Y100 for Parents | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/easing-wow-start-up-issues-after-updates/"><u>Easing WoW Start-Up Issues After Updates</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-11-innovative-metaverse-projects-for-insightful-analysis/"><u>[Updated] 11 Innovative Metaverse Projects for Insightful Analysis</u></a></li>
<li><a href="https://windows11.techidaily.com/classic-interface-reclamation-tips/"><u>Classic Interface Reclamation Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/beat-the-blank-screen-blues-faster-input-in-windows-11/"><u>Beat the Blank Screen Blues: Faster Input in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/activatedeactivate-smartscreen-filter-on-windows-11/"><u>Activate/Deactivate SmartScreen Filter on Windows 11</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/best-audio-waveform-generator-for-2024/"><u>Best Audio Waveform Generator for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-cleanup-stripping-out-microsoft-store/"><u>Win11 Cleanup: Stripping Out Microsoft Store</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-simple-paths-to-start-recording-on-hp-computers/"><u>[New] Simple Paths to Start Recording on HP Computers</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-your-creative-potential-with-win11s-photos-app-creating-dynamic-slideshows-and-image-spot-repair/"><u>Unlock Your Creative Potential with Win11's Photos App: Creating Dynamic Slideshows & Image Spot Repair</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-shadowed-swords-and-honored-combatants-must-try-titles-inspired-by-ghost-of-tsushi/"><u>[Updated] In 2024, Shadowed Swords & Honored Combatants  Must-Try Titles Inspired by Ghost of Tsushi</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-how-windows-sustains-ongoing-optimization/"><u>Deciphering How Windows Sustains Ongoing Optimization</u></a></li>
<li><a href="https://windows11.techidaily.com/a-users-guide-to-windows-11-system-anomalies-analysis/"><u>A User’s Guide to Windows 11 System Anomalies Analysis</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/step-by-step-approach-for-stellar-gopro-videos-for-2024/"><u>Step-By-Step Approach for Stellar GoPro Videos for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-resolving-m365-error-30015-26-on-pcs/"><u>Understanding and Resolving M365 Error 30015-26 on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-chromiums-firewall-connection-within-windows-safeguards/"><u>Enabling Chromium's Firewall Connection Within Windows Safeguards</u></a></li>
<li><a href="https://vp-tips.techidaily.com/asus-mg28uq-screen-a-4k-odyssey-of-immersion-and-fidelity-for-2024/"><u>ASUS MG28UQ Screen - A 4K Odyssey of Immersion and Fidelity for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-guide-to-top-frame-rates-in-slow-motion-video-production/"><u>2024 Approved  Guide to Top Frame Rates in Slow-Motion Video Production</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/guidelines-for-exporting-audio-from-audacity-to-mp3/"><u>Guidelines for Exporting Audio From Audacity to MP3</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-barriers-to-maximize-windows-ram/"><u>Breaking Down Barriers to Maximize Windows' RAM</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-your-screen-without-pin-in-windows-11/"><u>Unlock Your Screen Without PIN in Window's 11</u></a></li>
<li><a href="https://windows11.techidaily.com/3-ways-to-adjust-the-mouse-double-click-speed-on-windows/"><u>3 Ways to Adjust the Mouse Double-Click Speed on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-editing-skills-mastering-jumps-and-pastes/"><u>Elevate Editing Skills: Mastering Jumps & Pastes</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-become-an-insta-celebrity-overnight-top-15-strategies-from-social-media-experts/"><u>[New] 2024 Approved  Become an Insta Celebrity Overnight  Top 15 Strategies From Social Media Experts</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-and-correcting-windows-security-faults-in-windows-11/"><u>Avoiding and Correcting Windows Security Faults in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-error-messages-post-installed-application-failure/"><u>Deciphering Error Messages Post Installed Application Failure</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-quick-mac-screen-capture-tips-and-shortcuts-guide-for-2024/"><u>[New] Quick Mac Screen Capture Tips and Shortcuts Guide for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-unlock-your-phone-camera-free-and-easy/"><u>[New] Unlock Your Phone Camera, Free & Easy</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/in-2024-the-ultimate-list-of-video-brightness-editors-online-desktop-and-mobile/"><u>In 2024, The Ultimate List of Video Brightness Editors Online, Desktop, and Mobile</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-troubleshooting-silent-voice-calls-in-valorant/"><u>Windows Troubleshooting: Silent Voice Calls in Valorant</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/cting-your-yt-earning-monetization-verification-steps-for-2024/"><u>Perfecting Your YT Earning  Monetization Verification Steps for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/9-ways-to-fix-windows-hello-fingerprint-recognition-not-working/"><u>9 Ways to Fix Windows Hello Fingerprint Recognition Not Working</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-best-camcorders-featuring-direct-faceviewing/"><u>In 2024, Best Camcorders Featuring Direct FaceViewing</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-broken-video-files-of-galaxy-m34-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair Broken video files of Galaxy M34 on Windows??</u></a></li>
<li><a href="https://fake-location.techidaily.com/which-is-the-best-fake-gps-joystick-app-on-itel-s23plus-drfone-by-drfone-virtual-android/"><u>Which is the Best Fake GPS Joystick App On Itel S23+? | Dr.fone</u></a></li>
</ul></div>
