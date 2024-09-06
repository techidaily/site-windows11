---
title: Mastering the Art of Clearing Blocked Windows Files
date: 2024-09-05T02:08:07.801Z
updated: 2024-09-06T02:08:07.801Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering the Art of Clearing Blocked Windows Files
excerpt: This Article Describes Mastering the Art of Clearing Blocked Windows Files
keywords: File Unblocking Skills,Window File Recovery,Clearing Blocked Files,Data Accessibility Tricks,Solving File Restrictions,Windows Error Fixes,File Permission Management
thumbnail: https://thmb.techidaily.com/9e5ef4400f63e7f920ad051c5a9167da56f0ec84a54929789d005136b7898918.jpg
---

## Mastering the Art of Clearing Blocked Windows Files

 So you’ve downloaded files onto a directory on your PC, but Windows doesn’t trust them? This is understandable because some files from the internet can harm your computer, but what if you know for sure that the files are safe? Luckily there’s an easy PowerShell command you can use to unblock all of them.

## How Do I Unblock Multiple Files Using PowerShell on Windows?

 You can easily unblock a file by right-clicking on it and going to**Properties** — If you're on Windows 11, you'll need to click**Show more options** first before you can see the**Properties** option in the context menu. And once you're there, select the**General** tab and tick**Unblock** at the bottom in the**Security** section.

![unblocking a file in Properties on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unblock-file-properties-windows.jpg)

 But what if you have more than one file you need to unblock? Doing this one by one can get tedious. Alternatively, you can execute a single PowerShell command to unblock multiple files in a directory. Here is the command structure you need to use:

`dir [path] | unblock-file -confirm`

 Just replace**path** in the square brackets with the file path of the directory that has the blocked files. You can grab the file path of the directory by right-clicking on it and selecting**Copy as path** .

![copying file path on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/copy-as-path-windows-11.jpg)

 With the file path handy, follow the instructions below to use the unblock command in PowerShell:

1. Press**Win + S** to open Windows Search.
2. Type**powershell** in the search box and when the program appears in the search results, right-click on it and select**Run as administrator** . For more ways to open it, please read our guide on[ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
3. Enter the unblock command in PowerShell and hit the**Enter** key to run it. This is what it looks like on our computer:  
![entering the unblock file command in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-command.jpg)
4. You will be asked to confirm each file you want to unblock, so type either**Y** for**Yes** or**N** for**No** and hit the**Enter** key. This confirmation step is due to the**\-confirm** portion of the command. It is completely optional, and you can omit it or type**A** to confirm all the files in the directory.  
![confirming files to unblock in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-confirm.jpg)

 There’s a way you can tell Windows to always trust files you download from the internet. To do that, please read our guide on[how to stop Windows 10 from blocking your downloaded files](https://www.makeuseof.com/stop-windows-10-from-blocking-your-downloaded-files/) . The instructions in the tutorial use the Registry Editor and Local Group Policy Editor, so they should also work on Windows 11.

## Now You Know How to Unblock Files You Know Are Safe

 With the instruction above unlocking a bunch of downloaded files in a directory should be easier. Keep in mind that you shouldn’t do this on files you don’t trust. The last thing you want to do is put your Windows PC at risk unnecessarily


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
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-time-travel-through-snapshots-using-camera-roll-on-snapchat/"><u>[New] 2024 Approved  Time-Travel Through Snapshots Using Camera Roll on Snapchat</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-from-beginner-to-maestro-a-comprehensive-gif-tutorial-for-snapchat/"><u>[New] In 2024, From Beginner to Maestro  A Comprehensive Gif Tutorial for Snapchat</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-meme-madness-twitters-funniest-video-threads-for-2024/"><u>[New] Meme Madness  Twitter's Funniest Video Threads for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-obs-vs-shadowplay-which-to-choose-for-2024/"><u>[New] OBS vs ShadowPlay - Which to Choose for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-install-windows-movie-lab-for-creative-windows-11-users/"><u>[Updated] Install Windows Movie Lab for Creative Windows 11 Users</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-transform-your-videos-with-magix-video-pro-x/"><u>[Updated] Transform Your Videos with Magix Video Pro X</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/8-best-apps-for-screen-mirroring-itel-s23plus-pc-drfone-by-drfone-android/"><u>8 Best Apps for Screen Mirroring Itel S23+ PC | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/analyzing-user-feedback-the-latest-on-lg-bp350-display-tech/"><u>Analyzing User Feedback  The Latest on LG BP350 Display Tech</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-your-ft232r-usb-to-uart-bridge-driver-instantly/"><u>Download Your FT232R USB to UART Bridge Driver Instantly!</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ng-equations-decoding-the-mathematics-behind-youtube-income-monitoring/"><u>Earning Equations  Decoding the Mathematics Behind YouTube Income Monitoring</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/cing-engagement-imovie-techniques-for-youtube-intros/"><u>Enhancing Engagement  IMovie Techniques for YouTube Intros</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-steps-for-swiftly-dealing-with-unspecified-obs-recording-problem/"><u>Expert Steps for Swiftly Dealing with Unspecified OBS Recording Problem</u></a></li>
<li><a href="https://windows11.techidaily.com/exposing-the-trojan-terror-defending-your-windows-against-wacatacbml/"><u>Exposing the Trojan Terror: Defending Your Windows Against Wacatac.B!ml</u></a></li>
<li><a href="https://windows11.techidaily.com/from-version-6-to-7-smoothly-upgrading-virtualbox-on-your-win11-device/"><u>From Version 6 to 7: Smoothly Upgrading VirtualBox on Your Win11 Device</u></a></li>
<li><a href="https://windows11.techidaily.com/get-ahead-top-strategies-to-master-the-windows-11-taskbar/"><u>Get Ahead: Top Strategies to Master the Windows 11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-users-through-privilege-related-setup-hiccups/"><u>Guiding Users Through Privilege-Related Setup Hiccups</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-nokia-g22-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Nokia G22 in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-mute-windows-11-monitoring-tools/"><u>How to Mute Windows 11 Monitoring Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-snapping-windows-uac-alerts/"><u>How-To: Snapping Windows UAC Alerts</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-11-best-location-changers-for-xiaomi-redmi-13c-drfone-by-drfone-virtual-android/"><u>In 2024, 11 Best Location Changers for Xiaomi Redmi 13C | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-infinix-smart-8-pro-to-other-android-devices-using-bluetooth-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Infinix Smart 8 Pro to Other Android Devices Using Bluetooth? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-imei-unlokers-for-apple-iphone-11-pro-and-android-phones-by-drfone-ios/"><u>In 2024, Top IMEI Unlokers for Apple iPhone 11 Pro and Android Phones</u></a></li>
<li><a href="https://extra-skills.techidaily.com/journey-through-the-top-10-sites-offering-an-array-of-impressive-3d-texts-for-2024/"><u>Journey Through The Top 10 Sites Offering an Array of Impressive 3D Texts for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-fast-filesaving-top-6-tips-for-powerpoint-in-win11/"><u>Mastering the Art of Fast Filesaving: Top 6 Tips for PowerPoint in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/modify-winterrals-theme-picture/"><u>Modify WinTerral's Theme Picture</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-stabilize-your-footage-for-free-the-best-online-video-stabilizers/"><u>New 2024 Approved Stabilize Your Footage for Free The Best Online Video Stabilizers</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-to-overcome-the-errortoomanypatterns-in-wsl/"><u>Quick Fixes to Overcome the ERROR_TOO_MANY_PATTERNS in WSL</u></a></li>
<li><a href="https://windows11.techidaily.com/razer-synapse-issues-step-by-step-troubleshooting-for-w11w10/"><u>Razer Synapse Issues: Step-by-Step Troubleshooting for W11/W10</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-unsuccessful-discord-updates-for-windows-users/"><u>Resolving Unsuccessful Discord Updates for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-printer-service-offline-errors/"><u>Resolving Windows Printer Service Offline Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/seven-strong-points-that-make-windows-10-preferable-over-win11/"><u>Seven Strong Points That Make Windows 10 Preferable over Win11</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/h-cinematography-best-stabilizers-listed/"><u>Smooth Cinematography  Best Stabilizers Listed</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-the-background-load-a-windows-guide/"><u>Taming the Background Load: A Windows Guide</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/techniques-to-apply-watermarks-on-fb-content/"><u>Techniques to Apply Watermarks on FB Content</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-effective-toolbar-navigation-with-mspcm-on-w11/"><u>The Art of Effective Toolbar Navigation with MSPCM on W11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-note-management-on-obsidian-canvas/"><u>The Art of Note Management on Obsidian Canvas</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/the-ultimate-4k-odyssey-unveiling-the-power-of-gigabytes-aorus-fo32u2p-monitor-a-fusion-of-elegance-and-buttery-smooth-240-hz-gaming/"><u>The Ultimate 4K Odyssey: Unveiling the Power of Gigabyte's Aorus FO32U2P Monitor, a Fusion of Elegance & Buttery-Smooth 240 Hz Gaming</u></a></li>
<li><a href="https://extra-tips.techidaily.com/top-tier-gopro-cases-unveiled-1-10-ranking/"><u>Top-Tier GoPro Cases Unveiled - #1-10 Ranking</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-unresponsive-inputs-in-win11s-sleep-mode/"><u>Troubleshooting Unresponsive Inputs in Win11's Sleep Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-unresponsive-programs-in-windows-os/"><u>Troubleshooting Unresponsive Programs in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/unveil-sd-card-windows-explorer-fix-guide/"><u>Unveil SD Card: Windows Explorer Fix Guide</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unveiling-the-need-for-strict-ai-policies-who-holds-the-responsibility/"><u>Unveiling the Need for Strict AI Policies: Who Holds the Responsibility?</u></a></li>
<li><a href="https://windows11.techidaily.com/voice-commands-mastery-keyboard-shortcut-compendium-on-win-11/"><u>Voice Commands Mastery: Keyboard Shortcut Compendium on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/w11-pros-best-offers-save-and-elevate-your-spend/"><u>W11 Pro's Best Offers: Save & Elevate Your Spend</u></a></li>
<li><a href="https://location-social.techidaily.com/why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-meizu-21-drfone-by-drfone-virtual-android/"><u>Why Your WhatsApp Live Location is Not Updating and How to Fix on your Meizu 21 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/win11s-ingenious-techniques-for-gathering-info/"><u>Win11's Ingenious Techniques for Gathering Info</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-bridging-gaps-between-pc-and-phone/"><u>Windows 11: Bridging Gaps Between PC and Phone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1983473">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983473.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983473">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983473.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983473%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983473/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->