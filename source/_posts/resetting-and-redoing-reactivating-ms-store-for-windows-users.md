---
title: "Resetting and Redoing: Reactivating MS Store for Windows Users"
date: 2024-09-09T11:58:18.770Z
updated: 2024-09-10T11:58:18.770Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Resetting and Redoing: Reactivating MS Store for Windows Users"
excerpt: "This Article Describes Resetting and Redoing: Reactivating MS Store for Windows Users"
keywords: Reset MS Store,Reactivate MS Store,Redo MS Store,WinMS Store Fix,MSI Store Restore,Reinstalling MS Store,Windows MS Store Activation
thumbnail: https://thmb.techidaily.com/20be038a3e48f613b2c652d4cbdf605ae5da9fdcfecec9d6029a84b03a72309d.jpg
---

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123750/7443" target="_top" id="2123750">
  <img src="//a.impactradius-go.com/display-ad/7443-2123750" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123750/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Resetting and Redoing: Reactivating MS Store for Windows Users

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

<!-- affiliate ads begin -->
<span id="1160850">
					<video width="576" height="324" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1160850.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1160850">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1160850.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1160850%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1160850/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Re-Register Microsoft Store Apps for Current Users

![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135407/19272" target="_top" id="2135407">
  <img src="//a.impactradius-go.com/display-ad/19272-2135407" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135407/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If the[Microsoft Store app issue](https://www.makeuseof.com/tag/5-tips-fix-windows-store-app-issues-windows-10/) exists with a specific user account, you don’t need to re-register the app for all the user accounts on your computer. Instead, you can re-register the app only for the current user account.

To re-register Microsoft Store apps for the current user:

1. Press the**Win** key and type "powershell" into the Search bar.
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell console, type the following command and press**Enter** :  
`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
4. Wait for the command to execute and complete. You may see a blue loading graphic.
5. Once done, type**exit** and press**Enter** to close PowerShell.

 During the process, you may see some errors highlighted in red. It is due to PowerShell trying to reinstall existing apps on Windows. So, ignore the error and wait for the process to complete.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115925/19272" target="_top" id="2115925">
  <img src="//a.impactradius-go.com/display-ad/19272-2115925" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115925/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118313/7443" target="_top" id="2118313">
  <img src="//a.impactradius-go.com/display-ad/7443-2118313" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118313/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135412/19272" target="_top" id="2135412">
  <img src="//a.impactradius-go.com/display-ad/19272-2135412" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135412/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Install and Re-Register All Microsoft Store Apps on Windows 11

 Re-registering Windows apps is often necessary when Microsoft Store is not working. It can also help deal with other Windows settings and apps. If the issue persists, try the built-in Windows Store Apps troubleshooter to fix common Microsoft Store app issues.


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
<li><a href="https://youtube-zero.techidaily.com/024-approved-discover-the-top-8-services-to-amplify-video-content/"><u>[New] 2024 Approved  Discover the Top 8 Services to Amplify Video Content</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/-deep-dive-into-digital-platform-wealth-dailymotion-and-youtube-comparison-for-2024/"><u>[New] A Deep-Dive Into Digital Platform Wealth  Dailymotion & YouTube Comparison for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-capturing-flawless-footage-premium-pcmac-options-reviewed-for-2024/"><u>[New] Capturing Flawless Footage  Premium PC/Mac Options Reviewed for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-melodies-of-the-night-king-recommended-sites-for-tts-downloads/"><u>[New] Melodies of the Night King  Recommended Sites for TTS Downloads</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-top-10-best-meme-templates-for-2024/"><u>[New] Top 10 Best Meme Templates for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-from-vids-to-dollars-navigating-youtubes-monetization-landscape-for-2024/"><u>[Updated] From Vids to Dollars  Navigating YouTube's Monetization Landscape for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-integrating-video-conferencing-mastering-skypes-screen-sharing-functionality/"><u>[Updated] In 2024, Integrating Video Conferencing  Mastering Skype's Screen Sharing Functionality</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-perfect-guide-iosipad-podcast-recording-tips-for-engaging-interviews/"><u>[Updated] In 2024, Perfect Guide  IOS/iPad Podcast Recording Tips for Engaging Interviews</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-panoramic-photo-showdown-deciding-360-supremacy/"><u>[Updated] Panoramic Photo Showdown  Deciding 360 Supremacy</u></a></li>
<li><a href="https://android-location.techidaily.com/10-free-location-spoofers-to-fake-gps-location-on-your-nubia-red-magic-9-pro-drfone-by-drfone-virtual/"><u>10 Free Location Spoofers to Fake GPS Location on your Nubia Red Magic 9 Pro | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-augment-your-design-abilities-the-10-most-powerful-android-graphics-tools/"><u>2024 Approved  Augment Your Design Abilities  The 10 Most Powerful Android Graphics Tools</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-empower-your-imagery-free-lut-techniques-for-ar/"><u>2024 Approved  Empower Your Imagery  Free LUT Techniques for AR</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-premium-vr-headset-picks-for-uavs/"><u>2024 Approved  Premium VR Headset Picks for UAVs</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-speedy-recorder-device-with-guided-soundtrack/"><u>2024 Approved  Speedy Recorder Device with Guided Soundtrack</u></a></li>
<li><a href="https://change-location.techidaily.com/4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-vivo-y17s-drfone-by-drfone-virtual-android/"><u>4 solution to get rid of pokemon fail to detect location On Vivo Y17s | Dr.fone</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/advanced-methods-for-creating-quick-quality-thumbnails/"><u>Advanced Methods for Creating Quick, Quality Thumbnails</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/ai-powered-productivity-6-essential-chatgpt-tools-for-remote-jobs/"><u>AI-Powered Productivity: 6 Essential ChatGPT Tools for Remote Jobs</u></a></li>
<li><a href="https://extra-hints.techidaily.com/best-of-breed-premium-4k-camera-mounts-for-pros-for-2024/"><u>Best of Breed  Premium 4K Camera Mounts for Pros for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-gps-joystick-to-fake-gps-location-on-vivo-t2-pro-5g-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use GPS Joystick to Fake GPS Location On Vivo T2 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/cook-up-clashes-top-10-tiktok-food-faceoffs-for-2024/"><u>Cook-Up Clashes  Top 10 TikTok Food Faceoffs for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/elaborate-analysis-of-simple-hdr-imaging/"><u>Elaborate Analysis of Simple HDR Imaging</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-virtual-machine-lineup-for-windows-11-users/"><u>Essential Virtual Machine Lineup for Windows 11 Users</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-your-hands-on-euros-latest-processor-craze-amd-ryzen-9-price-drop-to-750-in-france/"><u>Get Your Hands on Euro's Latest Processor Craze: AMD Ryzen 9 Price Drop to €750 in France!</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-for-reviving-stalled-windows-11-menus/"><u>Guidelines for Reviving Stalled Windows 11 Menus</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-can-you-transfer-files-from-oppo-a18-to-iphone-151413-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How Can You Transfer Files From Oppo A18 To iPhone 15/14/13? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-activate-the-forgotten-windows-patcher/"><u>How to Activate the Forgotten Windows Patcher</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-entry-point-not-found-error-on-windows/"><u>How to Fix the Entry Point Not Found Error on Windows</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-complete-guide-for-apple-iphone-12-mini-lock-screen-by-drfone-ios/"><u>In 2024, Complete Guide For Apple iPhone 12 mini Lock Screen</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-vivo-v30-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Vivo V30 to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/is-wsl-functional-post-windows-11-install-solutions-explored/"><u>Is WSL Functional Post-Windows 11 Install? Solutions Explored</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/list-of-leading-sites-for-buying-youtube-tones-for-2024/"><u>List of Leading Sites for Buying YouTube Tones for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/master-fn-key-tips-on-activation-and-deactivation/"><u>Master Fn Key: Tips on Activation and Deactivation</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-efficiency-your-ultimate-guide-to-wsl-2-and-docker/"><u>Maximizing Efficiency: Your Ultimate Guide to WSL 2 & Docker</u></a></li>
<li><a href="https://windows11.techidaily.com/morning-magic-startup-seamlessly-unlock-notepad-quickly/"><u>Morning Magic: Startup Seamlessly, Unlock Notepad Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-through-windows-key-settings-easily/"><u>Navigate Through Windows Key Settings Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-intricacies-of-w11s-auto-hdr/"><u>Navigating the Intricacies of W11's Auto HDR</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-windows-memory-trouble/"><u>Navigating Through Windows' Memory Trouble</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/obs-vs-twitch-studio-which-one-is-better/"><u>OBS Vs Twitch Studio  Which One Is Better?</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-vram-in-windows-a-comprehensive-guide-for-gamers/"><u>Optimizing VRAM in Windows - A Comprehensive Guide for Gamers</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-0x800700e1-in-win10-and-11-pcs/"><u>Overcoming 0X800700E1 in Win10 & 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-access-barrier-to-roblox-on-windows-pc/"><u>Overcoming Access Barrier to Roblox on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/prime-virtual-machines-elevating-windows-11-tech/"><u>Prime Virtual Machines Elevating Windows 11 Tech</u></a></li>
<li><a href="https://windows11.techidaily.com/prolific-tools-in-windows-11-top-7-productivity-widgets/"><u>Prolific Tools in Windows 11: Top 7 Productivity Widgets</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-at-hand-assigning-shortcuts-for-win-11-problem-tools/"><u>Quick Fixes at Hand: Assigning Shortcuts for Win 11 Problem Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-on-correction-of-network-error-0x800704b3-in-windows/"><u>Quick Guide on Correction of Network Error 0X800704B3 in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-tips-how-to-overcome-restricted-file-viewers-in-windows/"><u>Quick Tips: How to Overcome Restricted File Viewers in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstating-windows-notification-banners/"><u>Reinstating Windows Notification Banners</u></a></li>
<li><a href="https://windows11.techidaily.com/revisiting-the-classics-uncovering-7-older-windows-functionalities-in-11/"><u>Revisiting the Classics: Uncovering 7 Older Windows Functionalities in 11</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-conversion-of-your-mp3-library-into-widespread-high-quality-audio-cds-with-imgburn/"><u>Seamless Conversion of Your Mp3 Library Into Widespread, High-Quality Audio Cds with ImgBurn</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-sound-management-in-windows-11/"><u>Simplifying Sound Management in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/sound-expertise-for-beginners-in-microsofts-new-os/"><u>Sound Expertise for Beginners in Microsoft's New OS</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-windows-11-setup-without-internet/"><u>Step-by-Step: Windows 11 Setup Without Internet</u></a></li>
<li><a href="https://windows11.techidaily.com/stepwise-approach-to-windows-11-arm-setup-from-iso/"><u>Stepwise Approach to Windows 11 ARM Setup From ISO</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlined-windows-11-upsize-an-in-place-methodology-overview/"><u>Streamlined Windows 11 Upsize: An In-Place Methodology Overview</u></a></li>
<li><a href="https://windows11.techidaily.com/swiftly-adapt-windows-settings-via-hotkey-techniques/"><u>Swiftly Adapt Windows Settings via Hotkey Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-printer-service-disabled-message-in-winos/"><u>Tackling Printer Service Disabled Message in WinOS</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-w11-tuning-lessen-resource-usage-for-users/"><u>Tailored W11 Tuning: Lessen Resource Usage for Users</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ssential-guide-to-free-attractive-youtube-intros/"><u>The Essential Guide to Free, Attractive YouTube Intros</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/top-5-emulators-the-ultimate-guide-for-classic-ps1-games-on-pc-for-2024/"><u>Top 5 Emulators  The Ultimate Guide for Classic PS1 Games on PC for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/transforming-user-access-control-on-common-windows-systems/"><u>Transforming User Access Control on Common Windows Systems</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/trouble-with-apple-iphone-se-2022-swipe-up-try-these-11-solutions-drfone-by-drfone-ios/"><u>Trouble with Apple iPhone SE (2022) Swipe-Up? Try These 11 Solutions | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-chrome-blackout-on-pcs/"><u>Troubleshooting Chrome Blackout on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-the-other-users-microsoft-account-problem/"><u>Unblocking the Other User’s Microsoft Account Problem</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-fixing-virtualbox-efail-windows-error/"><u>Understanding and Fixing Virtualbox E_FAIL (Windows) Error</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/unlocking-apple-iphone-xr-passcode-without-a-computer-drfone-by-drfone-ios/"><u>Unlocking Apple iPhone XR Passcode without a Computer | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/what-is-hardware-accelerated-gpu-scheduling-on-windows-heres-how-to-disable-it/"><u>What Is Hardware-Accelerated GPU Scheduling on Windows? Here's How to Disable It</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/what-should-be-your-priority-while-picking-out-a-non-carrier-locked-smartphone/"><u>What Should Be Your Priority While Picking Out a Non-Carrier Locked Smartphone?</u></a></li>
<li><a href="https://windows11.techidaily.com/win-storage-management-finding-and-reducing-high-space-items/"><u>Win Storage Management: Finding and Reducing High-Space Items</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-xpvista7-hacks-beat-non-compatible-problems/"><u>Windows XP/Vista/7 Hacks: Beat Non-Compatible Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/wintools-insight-exploring-differences-in-chkdsk-and-sfcs-use/"><u>WinTools Insight: Exploring Differences in CHKDSK and SFC's Use</u></a></li>
</ul></div>
