---
title: "Conquering Outlook's Glitch: The Path to Fixed Error 0X80072746"
date: 2024-07-11T21:34:50.503Z
updated: 2024-07-12T21:34:50.503Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Conquering Outlook's Glitch: The Path to Fixed Error 0X80072746"
excerpt: "This Article Describes Conquering Outlook's Glitch: The Path to Fixed Error 0X80072746"
keywords: Fixing Outlook Error 0X80072746,Resolve Outlook Glitches,Overcoming Outlook Issues,Mend Outlook Failures,Tackling Outlook Errors,Debugging Outlook Crashes,Eliminating Outlook Faults
thumbnail: https://thmb.techidaily.com/64fc45e8712465207f2977b50077b33434cfc78bbcc61824e624b36663dd238a.jpg
---

## Conquering Outlook's Glitch: The Path to Fixed Error 0X80072746

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
<li><a href="https://android-transfer.techidaily.com/in-2024-best-3-software-to-transfer-files-tofrom-your-realme-c53-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Best 3 Software to Transfer Files to/from Your Realme C53 via a USB Cable | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-realme-narzo-n53-bootloader-easily-by-drfone-android/"><u>How to Unlock Realme Narzo N53 Bootloader Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-scanning-issues-with-your-geforce-experience-on-windows/"><u>Avoid Scanning Issues with Your GeForce Experience on Windows</u></a></li>
<li><a href="https://fox-access.techidaily.com/in-2024-unlocking-the-potential-of-onestream-live-streaming/"><u>In 2024, Unlocking the Potential of OneStream Live Streaming</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-mouse-click-agility-nine-strategies-to-tweak-speeds/"><u>Boost Mouse Click Agility: Nine Strategies to Tweak Speeds</u></a></li>
<li><a href="https://windows11.techidaily.com/7-must-know-factors-for-buying-your-ideal-windows-computer/"><u>7 Must-Know Factors for Buying Your Ideal WIndows Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/a-step-by-step-approach-for-cleaning-up-ms-audit-records/"><u>A Step-by-Step Approach for Cleaning Up MS Audit Records</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-scripts-not-active-top-4-fixes-to-powershell-load-issue/"><u>Bypassing 'Scripts Not Active': Top 4 Fixes to PowerShell Load Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/3-ways-to-check-if-windows-11-is-activated/"><u>3 Ways to Check If Windows 11 Is Activated</u></a></li>
<li><a href="https://fake-location.techidaily.com/spoofing-life360-how-to-do-it-on-itel-p40plus-drfone-by-drfone-virtual-android/"><u>Spoofing Life360 How to Do it on Itel P40+? | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/2024-approved-the-ultimate-guide-top-8-mac-daws-with-in-depth-analysis/"><u>2024 Approved The Ultimate Guide Top 8 Mac DAWs with In-Depth Analysis</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-clipboard-operations-in-application-guard-edge-win11-guide/"><u>Activating Clipboard Operations in Application Guard (Edge) - Win11 Guide</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-stream-and-save-a-guide-to-xbox-broadcasting/"><u>In 2024, Stream and Save  A Guide to Xbox Broadcasting</u></a></li>
<li><a href="https://windows11.techidaily.com/bridging-the-gap-top-6-ways-to-solve-network-hardware-issues-in-windows-systems/"><u>Bridging the Gap - Top 6 Ways to Solve Network Hardware Issues in Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/calendar-setup-made-simple-windows-11-edition/"><u>Calendar Setup Made Simple: Windows 11 Edition</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-leverage-both-platforms-youtube-and-facebook-integration/"><u>[New] Leverage Both Platforms  YouTube and Facebook Integration</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-lost-messages-how-to-fix-notifications-that-fail/"><u>Avoiding Lost Messages: How to Fix Notifications That Fail</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-spec-deficit-errors-from-windows-game-bar/"><u>Addressing Spec Deficit Errors From Window's Game Bar</u></a></li>
<li><a href="https://youtube-help.techidaily.com/mastering-the-art-of-youtube-to-facebook-shares-for-2024/"><u>Mastering the Art of YouTube to Facebook Shares for 2024</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-bring-your-vision-to-life-adobe-premiere-pro-for-mac-creators-for-2024/"><u>New Bring Your Vision to Life Adobe Premiere Pro for Mac Creators for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-offscreen-windows-errors/"><u>Addressing Offscreen Windows Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-invalid-captcha-on-steam/"><u>Bypassing Invalid CAPTCHA on Steam</u></a></li>
<li><a href="https://windows11.techidaily.com/1719355454943-opera-installer-dilemma-on-windows-solutions-now/"><u>Opera Installer Dilemma on Windows - Solutions Now</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-winos-stop-autominize-apps/"><u>Boosting WinOS: Stop Autominize Apps</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-realme-12plus-5g-drfone-by-drfone-virtual-android/"><u>How to get the dragon scale and evolution-enabled pokemon On Realme 12+ 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-windows-techniques-for-diverse-partition-merging/"><u>Advanced Windows Techniques for Diverse Partition Merging</u></a></li>
<li><a href="https://windows11.techidaily.com/break-the-cycle-of-a-non-opening-notepad-on-your-windows-device/"><u>Break the Cycle of a Non-Opening Notepad on Your Windows Device</u></a></li>
<li><a href="https://windows11.techidaily.com/blue-screen-decoded-understanding-and-fixing-0x0000003b-in-win-os/"><u>Blue Screen Decoded: Understanding and Fixing 0X0000003B in Win OS</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-instant-techniques-to-shuffle-youtube-song-sequences/"><u>[New] Instant Techniques to Shuffle YouTube Song Sequences</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-windows-11-performance-run-command-upgrade-guide/"><u>Boosting Windows 11 Performance: Run Command Upgrade Guide</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/ways-to-trade-pokemon-go-from-far-away-on-honor-x50iplus-drfone-by-drfone-virtual-android/"><u>Ways to trade pokemon go from far away On Honor X50i+? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerating-media-playback-in-vlc-for-pc-users/"><u>Accelerating Media Playback in VLC for PC Users</u></a></li>
<li><a href="https://windows11.techidaily.com/clarifying-windows-approach-to-isolated-audiosystems/"><u>Clarifying Windows' Approach to Isolated Audiosystems</u></a></li>
<li><a href="https://windows11.techidaily.com/audible-improvements-for-windows-users-stepwise-audio-driver-revamp/"><u>Audible Improvements for Windows Users: Stepwise Audio Driver Revamp</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-11-get-support-disruption/"><u>Addressing Windows 11 'Get Support' Disruption</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-manage-disks-keyways-into-windows-11s-storage-manager/"><u>Swiftly Manage Disks: Keyways Into Windows 11'S Storage Manager</u></a></li>
<li><a href="https://discord-videos.techidaily.com/mastering-the-art-of-adding-unique-emojis-to-your-discord-avatar-pcmobile-for-2024/"><u>Mastering the Art of Adding Unique Emojis to Your Discord Avatar (PC/Mobile) for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/7-methods-for-correcting-unreachable-display-responses-in-windows/"><u>7 Methods for Correcting Unreachable Display Responses in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/a-guide-to-all-the-windows-photos-keyboard-shortcuts/"><u>A Guide to All the Windows Photos Keyboard Shortcuts</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-0x80070194-fixes-for-windows-onedrive/"><u>Bypassing 0X80070194: Fixes for Windows OneDrive</u></a></li>
<li><a href="https://windows11.techidaily.com/bringing-windows-backups-back-to-basics/"><u>Bringing Windows Backups Back to Basics</u></a></li>
<li><a href="https://windows11.techidaily.com/banish-baffling-silence-solutions-for-windows-spacebar/"><u>Banish Baffling Silence: Solutions for Windows Spacebar</u></a></li>
<li><a href="https://windows11.techidaily.com/bless-your-pc-god-mode-enhancements/"><u>Bless Your PC: God Mode Enhancements</u></a></li>
<li><a href="https://windows11.techidaily.com/a-novel-approach-to-combining-data-units-on-windows-11/"><u>A Novel Approach to Combining Data Units on Windows 11</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-video-editing-made-easy-for-kids-top-free-and-paid-apps/"><u>New 2024 Approved Video Editing Made Easy for Kids Top Free and Paid Apps</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-turbo-charge-your-tiktok-experience-with-fast-forwarding/"><u>[New] 2024 Approved  Turbo Charge Your TikTok Experience with Fast Forwarding</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-the-unsuccessful-capture-problem-in-win11/"><u>Addressing the 'Unsuccessful Capture' Problem in Win11</u></a></li>
</ul></div>
