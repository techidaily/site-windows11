---
title: Three Steps for Ditching Microsoft's Store
date: 2024-07-11T21:15:31.213Z
updated: 2024-07-12T21:15:31.213Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Three Steps for Ditching Microsoft's Store
excerpt: This Article Describes Three Steps for Ditching Microsoft's Store
keywords: Eject Microsoft Store,Quit Windows Shop,Escape MS Marketplace,Leave Microsoft Outlet,Drop Microsoft Hub,Steer Clear MSCore,Avoid Microsoft Apps
thumbnail: https://thmb.techidaily.com/81ce373281fd9aff14dae5d82f0fff51572cdd8c291988609733f2ca1401739f.jpg
---

## Three Steps for Ditching Microsoft's Store

 Microsoft Store is the go-to place for Windows users if they want to install an app. The app library is slowly expanding, and you will find all the popular apps without any difficulty. But sometimes the Microsoft Store application behaves abnormally and requires troubleshooting.

 But what if it still doesn’t work, even after repairing and resetting? There is no uninstall option in the Settings app, so it is possible to uninstall Microsoft Store? Well, it is possible to remove and reinstall the Microsoft Store app. Here’s how.

## Why Should You Uninstall the Microsoft Store App?

 Microsoft Store houses all the useful and popular applications for Windows devices. Moreover, it guarantees safe and malware-free application downloads. But if the app fails to start or doesn’t work properly, removing it makes sense.

 But don’t worry. You can remove the app and then reinstall it if you want. Reinstallation can fix persistent issues with the current version of the Microsoft Store app. It will remove the current app installation and all its related files and corrupt data. After that, you can reinstall the Microsoft app with a single command.

## How to Uninstall Microsoft Store App From Windows 11

 You can remove the Microsoft Store app from Windows 11 using the winget tool and run it using the command prompt. In addition, you can use the PowerShell cmdlet to remove the Microsoft Store application package from your system or use a batch file.

### 1\. Using Winget

 Winget is a handy Windows package manager tool available with the newer releases of Windows 10 and 11\. It makes it ridiculously easy to search and manage applications on your system. You can use it to remove any application, even the Microsoft Store app from your system. Here’s how:

1. Press the**Win + R** key to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**cmd** and press the**Ctrl + Shift + Enter** keys to launch the Command Prompt with administrator privileges.
2. Now, we need to locate the ID of the Microsoft Store app installed on the system. Type the following command in the command prompt window and press the enter key:**Winget list Store**
3. Winget will list all the installed programs on your system containing the string “store” in their name. Find the Microsoft Store app in the list and**copy** its**ID** .
4. After that, you need to run the uninstall command using winget. The syntax is**winget uninstall \[app ID\]** . So, the command will be:  
winget uninstall Microsoft.WindowsStore_8wekyb3d8bb
5. Press enter to execute the command and wait for it to execute successfully.  
![Uninstall Microsoft Store App using winget](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-winget.jpg)
6. Type**exit** in the command prompt window and press enter to close it.

### 2\. Using PowerShell

 Before winget was officially integrated into Windows 10 and 11, there was a method to [remove the Microsoft Store app using PowerShell](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) . The method still works and all you need to do is list the package name and then use the**Remove-AppxPackage** cmdlet to uninstall the Microsoft Store app from your system. Make sure to run PowerShell with elevated permissions.

### 3\. Using a Batch File

 If you want to save the hassle of typing commands every time you want to uninstall the Microsoft Store app, you can use a batch file. It will help you to remove Microsoft Store app from your system in a couple of clicks whenever the normal troubleshooting methods don’t work for you. Repeat the following steps:

1. Press**Win + D** to switch to the Desktop. Right-click on the Desktop and select the**New > Text Document** option.
2. Open the newly created text document file on the desktop. A Notepad window will pop up. Paste the following text in it:  
@echo off winget uninstall "Microsoft Store" exit
3. Now, press**Ctrl + Shift + S** to open the "Save as" window. Name the batch file as**UninstallStore.bat** and keep the**Save as** type option as**All files** .  
![Uninstall Microsoft Store App using batch file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-batch-file.jpg)
4. Click on the**Save** button. Close the Notepad window.
5. Press**Win + D** to switch to the desktop again. Right-click on the batch file and select the**Run as administrator** option from the context menu.
6. A command prompt window will open, run the Microsoft Store app uninstallation command, and close automatically. You don’t need to interact with the window.
7. Open the Start menu and search for Microsoft Store. You won’t find any matching app on your system.

## Easily Remove the Microsoft Store From Windows

 Windows 10 and 11 don’t offer an option to uninstall Microsoft Store. So, you are only left at the mercy of a system restore or reset. However, you can now uninstall the Microsoft Store app from your system using any of the three methods mentioned above. You can also reinstall it using the PowerShell cmdlet and continue using the app again.


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
<li><a href="https://windows11.techidaily.com/what-is-and-isnt-allowed-in-windows-11-s-mode/"><u>What Is and Isn’t Allowed in Windows 11 S Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-permission-restrictions-on-windows/"><u>Deciphering Permission Restrictions on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/why-your-wallet-may-regret-inexpensive-windows-keys/"><u>Why Your Wallet May Regret Inexpensive Windows Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/tech-integration-connect-ps3-dualshock-wirelessly/"><u>Tech Integration: Connect PS3 DualShock Wirelessly</u></a></li>
<li><a href="https://windows11.techidaily.com/11-ways-to-open-the-credential-manager-on-windows-11/"><u>11 Ways to Open the Credential Manager on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/top-8-common-slip-ups-for-first-time-windows-11-enthusiasts/"><u>Top 8 Common Slip-Ups for First-Time Windows 11 Enthusiasts</u></a></li>
<li><a href="https://windows11.techidaily.com/removing-obstacles-in-windows-update-code-0xc004f050/"><u>Removing Obstacles in Windows Update (Code 0XC004F050)</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-windows-11-audio-adjustment-tools/"><u>Unveiling the Windows 11 Audio Adjustment Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-high-dynamic-range-mastered-for-the-modern-user/"><u>Windows 11'S High Dynamic Range Mastered for the Modern User</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-excessive-cpu-load-by-dropbox-app-on-windows-devices/"><u>Addressing Excessive CPU Load by Dropbox App on Windows Devices</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-diy-gif-making-transforming-youtube-videos-into-animated-forms-for-2024/"><u>[Updated] DIY GIF Making  Transforming YouTube Videos Into Animated Forms for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/the-exciting-spectrum-of-tiktok-music-dance-and-humor/"><u>The Exciting Spectrum of TikTok  Music, Dance and Humor</u></a></li>
<li><a href="https://windows11.techidaily.com/1719329285690-resolve-programming-discrepancies-with-no-troubleshoot-tool/"><u>Resolve Programming Discrepancies with No Troubleshoot Tool.</u></a></li>
<li><a href="https://windows11.techidaily.com/solve-icloud-download-issues-with-these-helpful-steps/"><u>Solve iCloud Download Issues with These Helpful Steps</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-a-journey-through-the-landscape-of-human-computer-interaction/"><u>In 2024, A Journey Through the Landscape of Human-Computer Interaction</u></a></li>
<li><a href="https://ai-topics.techidaily.com/updated-what-is-an-ai-avatar-in-2024/"><u>Updated What Is an AI Avatar, In 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/transforming-security-change-account-password-for-win-11/"><u>Transforming Security: Change Account Password for Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/say-farewell-to-windows-subsys-embracing-alternatives-for-android/"><u>Say Farewell to Windows Subsys: Embracing Alternatives for Android</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-securing-a-stable-stream-of-earnings-on-youtube/"><u>[Updated] Securing a Stable Stream of Earnings on YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-security-implementing-custom-pattern-locks-in-windows/"><u>Tailored Security: Implementing Custom Pattern Locks in Windows</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-turn-off-google-location-to-stop-tracking-you-on-gionee-f3-pro-drfone-by-drfone-virtual-android/"><u>How to Turn Off Google Location to Stop Tracking You on Gionee F3 Pro | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-converting-in-meeting-google-meet-to-youtube-broadcasts-your-guide/"><u>[Updated] Converting In-Meeting Google Meet to YouTube Broadcasts  Your Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/three-easy-steps-to-unlock-your-network-with-telnet-on-wins/"><u>Three Easy Steps to Unlock Your Network with Telnet on Wins</u></a></li>
<li><a href="https://games-able.techidaily.com/optimal-high-refresh-monitor-selection/"><u>Optimal High Refresh Monitor Selection</u></a></li>
<li><a href="https://windows11.techidaily.com/reversing-the-tide-fixing-xbox-11-stranded-app-issue/"><u>Reversing the Tide: Fixing Xbox 11 Stranded App Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/show-your-connection-status-update-windows-icon-bar/"><u>Show Your Connection Status: Update Windows Icon Bar</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-what-you-want-to-know-about-two-factor-authentication-for-icloud-on-your-apple-iphone-13-pro-by-drfone-ios/"><u>In 2024, What You Want To Know About Two-Factor Authentication for iCloud On your Apple iPhone 13 Pro</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-iphone-12-mini-data-from-icloud-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover iPhone 12 mini Data From iCloud? | Dr.fone</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-excellence-in-emoji-creation-leading-discotools-for-2024/"><u>[Updated] Excellence in Emoji Creation  Leading DiscoTools for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unauthorized-ai-assistance-in-generating-win-11-keys/"><u>Unauthorized AI Assistance in Generating Win 11 Keys</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-quickly-fix-bluetooth-not-working-on-xiaomi-redmi-note-13-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Quickly Fix Bluetooth Not Working on Xiaomi Redmi Note 13 5G | Dr.fone</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-in-2024-what-is-an-ai-video-generator/"><u>New In 2024, What Is an AI Video Generator?</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-frozen-windows-handbraked-vaults/"><u>Unlock Frozen Windows-Handbraked Vaults</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/sim-unlock-oppo-reno-10-pro-5g-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>Sim Unlock Oppo Reno 10 Pro 5G Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://howto.techidaily.com/top-4-android-system-repair-software-for-oneplus-ace-2v-bricked-devices-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 4 Android System Repair Software for OnePlus Ace 2V Bricked Devices | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/a-peek-at-your-gadgets-soul-6-methods-to-discover-its-make/"><u>A Peek at Your Gadget's Soul: 6 Methods to Discover Its Make</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-easily-combine-videos-and-audios-with-5-simple-online-tools/"><u>New Easily Combine Videos and Audios with 5 Simple Online Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-disconnected-windows-printer-linkup/"><u>Restoring Disconnected Windows Printer Linkup</u></a></li>
<li><a href="https://windows11.techidaily.com/your-window-to-artistry-in-windows-1011/"><u>Your Window to Artistry in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-secrets-of-winnettoolbox/"><u>Unlocking the Secrets of WinNetToolbox</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-swift-transformations-top-5-no-download-online-gif-to-video-tools/"><u>[New] Swift Transformations  Top 5 No-Download, Online GIF to Video Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/achieving-optimal-security-in-win-11-with-ms-defender-application-guard-for-edge/"><u>Achieving Optimal Security in Win 11 with MS Defender Application Guard for Edge</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-innovative-boomers-for-dynamic-snaps-on-snapchat/"><u>[Updated] 2024 Approved  Innovative Boomers for Dynamic Snaps on Snapchat</u></a></li>
<li><a href="https://facebook.techidaily.com/messenger-notifications-track-vanished-screenshots/"><u>Messenger Notifications: Track Vanished Screenshots</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-apps-and-online-tools-to-track-samsung-galaxy-s24-phone-withwithout-imei-number-by-drfone-android/"><u>In 2024, Top Apps and Online Tools To Track Samsung Galaxy S24 Phone With/Without IMEI Number</u></a></li>
<li><a href="https://fix-guide.techidaily.com/strategies-for-apps-that-wont-download-from-play-store-on-infinix-smart-8-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Strategies for Apps That Wont Download From Play Store On Infinix Smart 8 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-of-winerrors-your-guide-to-fixes/"><u>Unraveling the Mystery of WinErrors: Your Guide to Fixes</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-lava-yuva-2-pro-drfone-by-drfone-virtual-android/"><u>In 2024, What is the best Pokemon for pokemon pvp ranking On Lava Yuva 2 Pro? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/unplugged-os-easy-win11-setup-without-internet/"><u>Unplugged OS: Easy Win11 Setup without Internet</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/profit-prospects-analyzing-youtubes-monetization-mechanisms-for-2024/"><u>Profit Prospects  Analyzing YouTube's Monetization Mechanisms for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-beginners-guide-to-youtube-image-sharing-for-2024/"><u>The Beginner's Guide to YouTube Image Sharing for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/bridging-the-gap-between-wi-fi-and-ethernet-in-windows/"><u>Bridging the Gap Between Wi-Fi and Ethernet in Windows</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-facebook-dating-for-your-apple-iphone-11-drfone-by-drfone-virtual-ios/"><u>How to Change Location On Facebook Dating for your Apple iPhone 11 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-security-a-comprehensive-guide-to-lock-patterns-in-windows-11/"><u>Customizing Security: A Comprehensive Guide to Lock Patterns in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-launching-works-on-windows-10plus/"><u>Step-by-Step: Launching Works on WIndows 10+</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-unlock-iphone-12-pro-max-without-passcode-easily-drfone-by-drfone-ios/"><u>In 2024, Unlock iPhone 12 Pro Max Without Passcode Easily | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-how-to-use-google-trends-to-come-up-with-video-ideas/"><u>[New] 2024 Approved  How to Use Google Trends to Come up with Video Ideas?</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-photos-files-on-honor-x50iplus-by-fonelab-android-recover-photos/"><u>Complete guide for recovering photos files on Honor X50i+.</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-software-integration-the-windows-11-troubleshooter/"><u>Unlocking Software Integration: The Windows 11 Troubleshooter</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-data-disaster-save-and-recover-snippets/"><u>Avoiding Data Disaster: Save & Recover Snippets</u></a></li>
<li><a href="https://windows11.techidaily.com/amp-up-your-vehicles-performance-with-these-top-windows-upgraders/"><u>Amp up Your Vehicle's Performance with These Top Windows Upgraders</u></a></li>
<li><a href="https://facebook.techidaily.com/digital-connectivitys-silver-lining-7-social-perks/"><u>Digital Connectivity's Silver Lining: 7 Social Perks</u></a></li>
</ul></div>
