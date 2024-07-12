---
title: How to Fix the Xbox Game Pass 0X800700e9 Error in Windows 11 & 11
date: 2024-07-11T21:33:57.916Z
updated: 2024-07-12T21:33:57.916Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix the Xbox Game Pass 0X800700e9 Error in Windows 11 & 11
excerpt: This Article Describes How to Fix the Xbox Game Pass 0X800700e9 Error in Windows 11 & 11
keywords: Fix Xbox Game Pass 0X800700E9 Error,Resolve Xbox Game Pass Error,Xbox Game Pass Windows Fix,Clear Xbox Game Pass Error Win11,Troubleshoot Game Pass Error,Stop Xbox Game Pass 0X8007 Error,Repair Game Pass Issue Windows 11
thumbnail: https://thmb.techidaily.com/3b3b313aac4422406d268b9ec86a52f71522ac5dfd6eae7e41b861cd70dad021.png
---

## How to Fix the Xbox Game Pass 0X800700e9 Error in Windows 11 & 11

 The Xbox Game Pass is a popular Microsoft subscription service for games. However, some users encounter a 0x800700e9 error when they try to download and install Xbox Game Pass titles via the Xbox app or Microsoft Store. The 0x800700e9 error code message says “Something unexpected happened,” which provides no clue as to how to resolve that issue.

 Users can’t download and install Xbox Game Pass content because of error 0x800700e9\. However, you can fix error 0x800700e9 with these potential resolutions.

## 1\. Run the Microsoft Store App Troubleshooter

 The Windows Store App troubleshooter might help fix the error 0x800700e9\. This is how you can access the Windows Store App troubleshooter in Windows 11:

1. Use one of the many [ways to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Click the**Troubleshoot** box that has a spanner icon.
3. Next, click**Other-troubleshooters** to access the Settings app’s list of troubleshooting tools.
4. Select**Run** for activating the Windows Store Apps.  
![The Run button for the Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/run-button-for-windows-store-apps-troubleshooter.jpg)
5. Apply any suggestions the troubleshooter provides.

 The Windows 10 troubleshooters are available within the**Update & Security** category of Settings. Click the**Troubleshoot** tab in that category and select**Additional troubleshooters** . Then you can select Windows Store Apps from there and click**Run** to access the tool.

## 2\. Turn Delivery Optimization On in Settings

 Delivery Optimization is a service that enables Windows Update downloads from other PCs. Error 0x800700e9 often arises when Delivery Optimization is disabled in Windows. You can turn on Delivery Optimization via Settings like this:

1. Open the**Windows Update** tab in Settings.
2. Click**Advanced options** to view more settings.
3. Select the**Delivery Optimization** navigation option.  
![The Delivery Optimization navigation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/delivery-optimization-navigation-option.jpg)
4. Turn on the**Allow downloads from other PCs** option to enable Delivery Optimization.  
![The Allow downloads from other PCs option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/allow-downloads-from-other-pcs-option.jpg)
5. Click the**Devices on my local network** radio button.

 You can enable Delivery Optimization in Windows 10’s Settings app much the same. However, you’ll need to select the**Windows Update** category. Then click the**Deliver Optimization** tab in the**Windows Update** category to access and turn on the same**Allow downloads from other PCs** setting.

## 3\. Enable the Delivery Optimization and BITS Services

 Some Xbox Game Pass users have resolved error 0x800700e9 by enabling and running the Delivery Optimization and BITS services. You can enable and start those services via that app as follows:

1. To access Run, press**Win + R** .
2. Type**services.msc** inside Run’s**Open** command box.
3. Select**OK** to open Services.
4. Double-click the Delivery Optimization service.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/services-window2.jpg)
5. Select**Start** if it’s not running.
6. Click**Automatic** on Delivery Optimization’s**Startup type** menu.  
![The Delivery Optimization Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/delivery-optimization-properties-window.jpg)
7. Select**Apply** \>**OK** to save the service’s new settings.
8. Repeat steps four to seven for the Background Intelligent Transfer service.

 If the services are already running, try restarting them. Right-click the services and select their**Stop** options. Then you can start those services again by right-clicking them and selecting**Restart** .

## 4\. Enable Delivery Optimization via the Windows Registry

 If the above methods didn't work for you, try enabling Delivery Optimization service by editing the registry. You can back up the registry or set up a restore point before editing the registry if you want to be extra careful. To apply this potential solution, edit the**DoSvc** key like this:

1. First, bring up Registry Editor, which you can open with one of the methods in our guide on [how to open Regedit](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Click inside the address bar at the top of Registry Editor and erase the current key location.
3. Input this**DoSvc** key location in the address bar and hit**Return** :  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\DoSvc`  
![The DoSvc key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dovsc-key.jpg)
4. Select the**DoSvc** key, and right-click the**Start** DWORD to select**Modify** .  
![The Modify option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/modify-option.jpg)
5. Input**3** in the**Value** box and click**OK** .  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/start-dword-key.jpg)
6. Exit Regedit, and restart the PC.

## 5\. Reset or Repair the Xbox App

 Many users go through the Xbox app to get at their Xbox Game Pass titles on Windows. As such, you might be able to fix error 0x800700e9 by selecting**Reset and Repair** options for the Xbox app inside Settings.

 Check out our guide on [resetting apps in Windows 11 and 10](https://www.makeuseof.com/windows-reset-app/) to clear the Xbox app’s data. The**Repair** option for the Xbox app in Settings is available just above its**Reset** button.

![The Reset option for the Xbox app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reset-option.jpg)

## 6\. Reset the Microsoft Store Cache

 A corrupted Microsoft Store cache data can cause download and installation issues to arise for apps available on Microsoft’s online store. So, resetting the Store’s cache could be another potential solution for the 0x800700e9 error. Try resetting Microsoft Store’s cache in the following steps:

1. Bring up the Windows Search by clicking the magnifying glass or**Search** box on your taskbar.
2. Type**WSReset.exe** within the search box to find that Run command file.
3. Click**WSReset.exe** to run the command.  
![The wsreset.exe Run command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/wsreset-exe-command.jpg)
4. Wait for MS Store to open automatically, and then try downloading Xbox Game Pass titles again.

## 7\. Reinstall the Microsoft Store

 Reinstalling the Microsoft Store can fix deeper issues with that app that could be causing error 0x800700e9\. Although you can’t select to uninstall Microsoft Store, you can still reinstall that app with a PowerShell command. Here are the steps for reinstalling the Microsoft Store via PowerShell:

1. Bring up Run with the**Win + R** keyboard shortcut, and input**PowerShell** within the text box.
2. Right-click PowerShell to bring up a context menu, and select the**Run as administrator** option.
3. Execute this PowerShell command for reinstalling Microsoft Store:  
`Get-AppxPackage -allusers Microsoft.WindowsStore | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reinstall Microsoft Store command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reinstall-microsoft-store-command.jpg)
4. Wait for the command to finish, and then exit the command app.

## 8\. Reset Your Network

![The Network reset option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-reset-option.jpg)

 Error 0x800700e9 can also sometimes occur because of network issues. Performing a network reset is a good way to troubleshoot issues in this area; however, do note that this will restore your network components to their factory defaults and erase your Wi-Fi and Ethernet connections.

 Have a look at our [how to reset your network settings on Windows](https://www.makeuseof.com/reset-network-settings-windows-11/) guide for details about how to apply this troubleshooting method.

## Enjoy Your Xbox Game Pass Games Again

 Fortunately, you don’t have to cancel your Xbox Game Pass subscription because of error 0x800700e9\. A lot of users have fixed this installation issue for Xbox Game Pass titles with the resolutions in this guide.

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
<li><a href="https://windows11.techidaily.com/the-comprehensive-manual-for-component-settings-in-w11/"><u>The Comprehensive Manual for Component Settings in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/5-tips-for-turning-around-a-frozen-windows-hello-system/"><u>5 Tips for Turning Around a Frozen Windows Hello System</u></a></li>
<li><a href="https://windows11.techidaily.com/fast-factor-essential-steps-for-assessing-lan-router-speed/"><u>Fast Factor: Essential Steps for Assessing LAN Router Speed</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/5-ways-to-reset-vivo-y100-without-volume-buttons-drfone-by-drfone-reset-android-reset-android/"><u>5 Ways to Reset Vivo Y100 Without Volume Buttons | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-full-potential-adding-portable-apps-to-w11/"><u>Unlock Full Potential: Adding Portable Apps to W11</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-photos-from-oppo-k11-5g-by-fonelab-android-recover-photos/"><u>Undelete lost photos from Oppo K11 5G.</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-the-ultimate-guide-to-selecting-5-online-title-makers-for-2024/"><u>[New] The Ultimate Guide to Selecting 5 Online Title Makers for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-5-winter-youtube-background-ideas-to-warm-up-your-videos/"><u>[Updated] 5 Winter YouTube Background Ideas to Warm Up Your Videos</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-the-most-useful-tips-for-pokemon-go-ultra-league-on-vivo-y100-drfone-by-drfone-virtual-android/"><u>In 2024, The Most Useful Tips for Pokemon Go Ultra League On Vivo Y100 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/ensure-smooth-os-operation-autoupdate-and-change-amd-drivers/"><u>Ensure Smooth OS Operation: Autoupdate & Change AMD Drivers</u></a></li>
<li><a href="https://windows11.techidaily.com/what-makes-users-grumble-in-windows-11/"><u>What Makes Users Grumble in Windows 11?</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-strategies-for-effortless-integration-of-directories-win-11/"><u>Expert Strategies for Effortless Integration of Directories, Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-strategies-for-overcoming-windows-error-code-0x80040610/"><u>Essential Strategies for Overcoming Windows Error Code 0X80040610</u></a></li>
<li><a href="https://windows11.techidaily.com/gpresult-command-guide-for-policy-reporting/"><u>GPResult Command Guide for Policy Reporting</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-something-went-wrong-office-error-on-windows/"><u>How to Fix the “Something Went Wrong” Office Error on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-mystery-of-yourphoneexe-in-w10/"><u>Unveiling the Mystery of YourPhoneExe in W10</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-crack-the-code-of-imagerys-roots-with-our-reverse-analysis-tools-for-instagram/"><u>2024 Approved  Crack the Code of Imagery's Roots with Our Reverse Analysis Tools for Instagram</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-incomplete-updates-in-your-windows-based-discord/"><u>Handling Incomplete Updates in Your Windows-Based Discord</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-sharefake-location-on-whatsapp-for-oneplus-11r-drfone-by-drfone-virtual-android/"><u>In 2024, How to Share/Fake Location on WhatsApp for OnePlus 11R | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/unexpected-rav-guard-find-its-source-and-quit-methods/"><u>Unexpected Rav Guard? Find Its Source & Quit Methods</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-threefold-mastery-in-copy-for-social-media-campaigns-increasing-impact-with-every-word-for-2024/"><u>[Updated] Threefold Mastery in Copy for Social Media Campaigns – Increasing Impact with Every Word for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/achieving-a-clearer-taskbar-windows-11-guide/"><u>Achieving a Clearer Taskbar: Windows 11 Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/window-brightness-prodigies-a-list-of-premier-tools-for-multiscreeners/"><u>Window Brightness Prodigies: A List of Premier Tools for Multiscreeners</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-at-workplace-presentations-fixing-powerpoints-print-problems-in-windows/"><u>Winning at Workplace Presentations: Fixing PowerPoint's Print Problems in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-to-quicken-windows-edge-on-w10-and-w11/"><u>Tips to Quicken Windows Edge on W10 & W11</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-facebook-slideshow-how-to-create-a-slideshow-on-facebook/"><u>[Updated] In 2024, Facebook Slideshow  How to Create a Slideshow on Facebook</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-layers-impact-on-linux-dominance/"><u>Windows Layer's Impact on Linux Dominance</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secrets-to-overcome-directdraw-challenges-in-11-series-windows/"><u>Unveiling the Secrets to Overcome DirectDraw Challenges in 11-Series Windows</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-stolen-apple-iphone-11-in-different-conditionsin-by-drfone-ios/"><u>How To Unlock Stolen Apple iPhone 11 In Different Conditionsin</u></a></li>
<li><a href="https://fox-glue.techidaily.com/3-simple-ways-to-color-grading-in-adobe-photoshop/"><u>3 Simple Ways to Color Grading in Adobe Photoshop</u></a></li>
<li><a href="https://windows11.techidaily.com/lessen-malware-apps-resource-usage-for-performance-gain/"><u>Lessen Malware App’s Resource Usage for Performance Gain</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-a-faulty-windows-11-temporary-storage/"><u>Fixing a Faulty Windows 11 Temporary Storage</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-most-common-blue-screen-errors-on-windows/"><u>How to Fix the Most Common Blue Screen Errors on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-download-fonts-for-all-languages-on-windows/"><u>How to Download Fonts for All Languages on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/decreasing-cpu-and-ram-usage-tackling-unrealcefsubprocess-issues/"><u>Decreasing CPU and RAM Usage: Tackling UnrealCEFSubprocess Issues</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-step-up-and-snap-top-10-must-try-viral-tiktok-stunts/"><u>[New] Step Up and Snap  Top 10 Must-Try Viral TikTok Stunts</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secrets-of-a-smoother-click-lock-in-windows/"><u>Unveiling the Secrets of a Smoother Click Lock in Windows</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-essential-guide-to-cheap-webcam-capture-tech-for-2024/"><u>[Updated] Essential Guide to Cheap Webcam Capture Tech for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-in-2024-whats-the-best-video-size-for-instagram-weve-got-the-answer/"><u>New In 2024, Whats the Best Video Size for Instagram? Weve Got the Answer</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-charge-awareness-customizing-battery-indicators-in-win11/"><u>Boosting Charge Awareness: Customizing Battery Indicators in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/ideal-guide-efficiently-change-heic-images-to-jpeg-format-on-windows-11/"><u>Ideal Guide: Efficiently Change HEIC Images to JPEG Format on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-comprehensive-guide-to-getting-most-out-of-windows-11s-startup-screen/"><u>The Comprehensive Guide to Getting Most Out of Windows 11'S Startup Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/activate-virtualization-your-step-by-step-guide-for-win-11-homes/"><u>Activate Virtualization: Your Step by Step Guide for Win 11 Homes</u></a></li>
<li><a href="https://windows11.techidaily.com/beginners-manual-discovering-windows-aids-and-assists/"><u>Beginner's Manual: Discovering Windows Aids and Assists</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-blank-login-issues-on-win1011-pcs/"><u>Clearing Up Blank Login Issues on WIN10/11 PCs</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-infuse-rhythms-into-your-whatsapp-story/"><u>[New] Infuse Rhythms Into Your WhatsApp Story</u></a></li>
<li><a href="https://activate-lock.techidaily.com/effective-ways-to-fix-checkra1n-error-31-on-iphone-se-2022-by-drfone-ios/"><u>Effective Ways To Fix Checkra1n Error 31 On iPhone SE (2022)</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-pin-gmail-to-the-taskbar-on-a-windows-pc/"><u>How to Pin Gmail to the Taskbar on a Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/brushstrokes-begin-accessing-microsoft-paint-in-windows-11/"><u>Brushstrokes Begin: Accessing Microsoft Paint in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/end-the-ebb-and-flow-top-strategies-for-smooth-windows-streaming/"><u>End the Ebb and Flow: Top Strategies for Smooth Windows Streaming</u></a></li>
<li><a href="https://screen-recording.techidaily.com/survivals-thrill-top-picks-for-heart-pounding-zombie-games-for-2024/"><u>Survival's Thrill  Top Picks for Heart-Pounding Zombie Games for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-quick-and-quiet-recording-of-games/"><u>2024 Approved  Quick and Quiet Recording of Games</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-cross-platform-guide-extracting-facebook-video-content/"><u>2024 Approved  Cross-Platform Guide  Extracting Facebook Video Content</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-innovative-gb-recorder-for-games-on-fbx/"><u>[Updated] 2024 Approved  Innovative GB Recorder for Games on FBX</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-install-hyper-v-on-windows-11-home/"><u>How to Install Hyper-V on Windows 11 Home</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-2024-approved-explore-sj7s-high-definition-action-footage-in-new-review/"><u>[Updated] 2024 Approved  Explore SJ7's High-Definition Action Footage in New Review</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-muted-audio-recordings-in-obs-studio-on-windows-11-pcs/"><u>How to Fix Muted Audio Recordings in OBS Studio on Windows 11 PCs</u></a></li>
</ul></div>
