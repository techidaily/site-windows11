---
title: "Windows 11 Vigilance: Understanding and Monitoring Device Uptime"
date: 2024-08-15T16:13:07.234Z
updated: 2024-08-16T16:13:07.234Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows 11 Vigilance: Understanding and Monitoring Device Uptime"
excerpt: "This Article Describes Windows 11 Vigilance: Understanding and Monitoring Device Uptime"
keywords: Windows 11 Updates,Vigilant Device Checks,Monitor Uptime Windows,System Uptime Tracking,Vigilance in OS Management,Real-Time PC Status,Proactive OS Maintenance
thumbnail: https://thmb.techidaily.com/c10f5fc3a26c6243fb8c4940c266b426236bd87cd21bd2e8e71da4c4f75545bc.jpg
---

## Windows 11 Vigilance: Understanding and Monitoring Device Uptime

 Checking your computer's uptime is something you might want to do to monitor its performance. This information can also come in handy when troubleshooting your system or performing regular maintenance tasks.

 Your Windows 11 PC provides several options for checking the device's uptime. Let’s go over all of them one by one.

## 1\. How to Find System Uptime Using Task Manager

 Windows Task Manager is an advanced tool that provides useful information about your PC’s hardware and software. Here's how you can use it to find your computer’s uptime.

1. Press**Ctrl + Shift + Esc** on your keyboard or use one of the [many ways to access Task Manager](https://www.makeuseof.com/how-to-access-task-manager-on-windows-11/) .
2. In the**Performance** tab, click on**CPU** .
3. Check the system uptime under the**Up time** section.  
![Check System Uptime Using Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-system-uptime-using-task-manager.jpg)

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. How to Find System Uptime via the Settings App

 Another way to check your system's uptime is through the Windows Settings app. Here are the steps for the same.

1. Press**Win + I** to open the Settings app.
2. Select the**Network & internet** tab from the left sidebar.
3. Click on**Advanced network settings** .
4. Under the**Network adapters** section, click on the active network adapter and check the uptime mentioned next to**Duration** .  
![Check System Uptime Using Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-system-uptime-using-windows-settings-app.jpg)
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Note that this method displays your network adapter’s uptime. So, the information displayed may not be accurate if you have reset your network connection after boot.

## 3\. How to Find System Uptime Using Control Panel

 If you prefer to do things the old-fashioned way, you can use the classic Control Panel to find your device’s uptime in Windows 11\. To do so, use the following steps:

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**control panel** in the box and select the first result that appears.
3. In the Control Panel window that appears, use the drop-down menu in the top right corner to change the view type to**Large icons** .
4. Click on**Network and Sharing Center** .
5. Click on**Change adapter settings** in the left pane.
6. Right-click on the active network adapter and select**Status** .
7. Under the**General** tab, you’ll find the uptime next to**Duration** .  
![Check System Uptime Using Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-system-uptime-using-control-panel.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->
## 4\. How to Check System Uptime With Command Prompt

 If you're an advanced Windows user, you can also use Command Prompt to check your computer’s uptime. Here’s how:

1. Right-click on the Start icon or press**Win + X** to open the Power User menu.
2. Select**Terminal** from the list.
3. Type the following command in the console and press**Enter** .  
`systeminfo | find "System Boot Time"`  
![Check System Uptime Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-system-uptime-using-command-prompt.jpg)

 Once you run the above command, Command Prompt should display the time when your computer started operating. You can easily calculate the system uptime by subtracting the**System Boot Time** from the current time.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->
## 5\. How to Check System Uptime With PowerShell

 PowerShell is another command-line tool available on Windows. If you prefer using that, follow these steps to find your device’s uptime.

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**Windows PowerShell** and press**Enter** .
3. Paste the following command in the PowerShell window and press**Enter** .  
`(get-date) - (gcim Win32_OperatingSystem).LastBootUpTime`  
![Check System Uptime Using Windows PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-system-uptime-using-windows-powershell.jpg)

 PowerShell should display the number of days, hours, minutes, seconds, and milliseconds since the device was turned on.

 Like using PowerShell on Windows? Why not familiarize yourself with these [best PowerShell commands on Windows](https://www.makeuseof.com/windows-powershell-commands-cmdlets/) ?

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->
## Checking Your Device Uptime on Windows 11

 As we just saw, finding your Windows 11 PC’s uptime is fairly simple. You can use any of the methods listed above to find that information.

 The total uptime of your computer may not provide you with accurate information about how much time you spend in front of it. For that, you’ll need to check Power & battery usage in the Windows Settings app.


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
<li><a href="https://extra-tips.techidaily.com/new-10-free-legal-chants-and-sounds-for-meditation-practice/"><u>[New] 10 Free Legal Chants and Sounds for Meditation Practice</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-how-often-should-you-upload-youtube-videos-to-get-more-views/"><u>[New] 2024 Approved  How Often Should You Upload YouTube Videos to Get More Views</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-unlocking-viral-potential-through-strategic-fb-videos/"><u>[New] 2024 Approved  Unlocking Viral Potential Through Strategic FB Videos</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-brief-blotter-for-film-blueprint/"><u>[New] Brief Blotter for Film Blueprint</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/1715860443796-new-employing-inbuilt-screen-recording-tools-on-mate-p-models-p20-p10/"><u>[New] Employing Inbuilt Screen Recording Tools on Mate, P Models (P20, P10).</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-make-a-video-from-photo-with-music/"><u>[New] Make a Video From Photo with Music</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-simplifying-large-screen-viewing-for-youtubers/"><u>[New] Simplifying Large-Screen Viewing for YouTubers</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/treaming-to-profit-youtube-policy-changes/"><u>[New] Streaming to Profit  YouTube Policy Changes</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-quick-steps-for-recording-insta-stories/"><u>[Updated] 2024 Approved  Quick Steps for Recording Insta Stories</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-inside-out-how-to-react-on-twitter-vids-for-2024/"><u>[Updated] Inside Out  How to React on Twitter Vids for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-apples-mobile-posting-playbook-for-youtube-success/"><u>2024 Approved  Apple's Mobile Posting Playbook for YouTube Success</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-strategies-to-maintain-synchronization-between-cameras-and-streaming-software/"><u>2024 Approved  Strategies to Maintain Synchronization Between Cameras and Streaming Software</u></a></li>
<li><a href="https://windows11.techidaily.com/6-quick-ways-to-fix-the-powerpoint-cant-save-file-error-in-windows-11/"><u>6 Quick Ways to Fix the PowerPoint Can't Save File Error in Windows 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/achieving-flawless-visual-balance-aspect-ratios-matter-for-2024/"><u>Achieving Flawless Visual Balance  Aspect Ratios Matter for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-tips-for-efficient-toolbar-usage-in-microsoft-win11-pcm/"><u>Advanced Tips for Efficient Toolbar Usage in Microsoft Win11 PCM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-efficiency-integrating-new-folders-into-windows-11-menu/"><u>Boosting Efficiency: Integrating New Folders Into Windows 11 Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-terminal-for-quake-in-windows/"><u>Configuring Terminal for Quake in Windows</u></a></li>
<li><a href="https://facebook.techidaily.com/connectors-guide-to-facebooks-emerging-zones/"><u>Connectors' Guide to Facebook’s Emerging Zones</u></a></li>
<li><a href="https://windows11.techidaily.com/curating-edthemes-experience-on-windows-11/"><u>Curating EdThemes Experience on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/cut-the-clutter-quickly-reduce-programs-with-system-tray-keys/"><u>Cut the Clutter: Quickly Reduce Programs with System Tray Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-windows-11-camera-app-error-0xa00f425d-fixes/"><u>Disabling Windows 11 Camera App Error 0xA00F425D Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-vivetool-your-ticket-to-access-latest-windows-innovations/"><u>Discover ViVeTool: Your Ticket to Access Latest Windows Innovations</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-integration-portable-software-menus-for-w11plus/"><u>Easy Integration: Portable Software Menus for W11+</u></a></li>
<li><a href="https://tech-haven.techidaily.com/elevate-your-home-cooking-7-ai-inspired-ideas-from-gpt/"><u>Elevate Your Home Cooking: 7 AI-Inspired Ideas From GPT</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-stable-windows-printer-connections/"><u>Ensuring Stable Windows-Printer Connections</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicating-your-input-cant-be-opened-vlc-error/"><u>Eradicating 'Your Input Can't Be Opened' VLC Error</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-advice-for-seamlessly-entering-fullscreen-mode/"><u>Expert Advice for Seamlessly Entering Fullscreen Mode</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/expert-advice-on-fixing-windows-msstdfmtdll-error-and-restoring-system-stability/"><u>Expert Advice on Fixing Windows Msstdfmt.dll Error and Restoring System Stability</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-monochrome-errors-with-marketplace/"><u>Fixing Monochrome Errors with Marketplace</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-the-nvidia-setup-not-available-glitch/"><u>Fixing the 'Nvidia Setup Not Available' Glitch</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-guide-on-how-to-remove-apple-id-from-iphone-15-plus-by-drfone-ios/"><u>In 2024, Guide on How To Remove Apple ID From iPhone 15 Plus</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-turn-off-google-location-to-stop-tracking-you-on-motorola-moto-g34-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Turn Off Google Location to Stop Tracking You on Motorola Moto G34 5G | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-peer-reviews-unpacking-vllo-experience/"><u>In 2024, Peer Reviews  Unpacking VLLO Experience</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-top-12-prominent-zte-axon-40-lite-fingerprint-not-working-solutions-by-drfone-android/"><u>In 2024, Top 12 Prominent ZTE Axon 40 Lite Fingerprint Not Working Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/legacy-unlocks-employing-a-windows-7-key-in-11-setup/"><u>Legacy Unlocks: Employing a Windows 7 Key in 11 Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/maintaining-constant-calc-display-in-windows/"><u>Maintaining Constant Calc Display in Windows</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/maximize-impact-mastering-igtv-content-submission/"><u>Maximize Impact  Mastering IGTV Content Submission</u></a></li>
<li><a href="https://windows11.techidaily.com/meeting-prep-101-test-your-windows-webcam-microphone/"><u>Meeting Prep 101: Test Your Windows Webcam, Microphone</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-onedrive-errors-on-windows-11-an-experts-fix-list/"><u>Navigating OneDrive Errors on Windows 11: An Expert's Fix List</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-the-maze-of-windows-error-code-0xc00000f/"><u>Navigating Through the Maze of Windows Error Code 0Xc00000f</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/optimizing-your-browsing-mastering-firefoxs-pip-for-2024/"><u>Optimizing Your Browsing  Mastering Firefox's PIP for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-nullnone-value-dilemmas-on-windows/"><u>Overcoming Null/None Value Dilemmas on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-win-os-extract-issues-saving-time-with-error-1152-solution/"><u>Overcoming Win OS Extract Issues: Saving Time with Error 1152 Solution</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722977363016-quick-setup-get-your-brother-mfc-7360n-ready-on-windows-systems-with-latest-driver-updates/"><u>Quick Setup: Get Your Brother MFC-7360N Ready on Windows Systems with Latest Driver Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-shift-script-moving-windows-11-selected-files/"><u>Quick Shift Script: Moving Windows 11 Selected Files</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reasons-for-nokia-g42-5g-stuck-on-boot-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Nokia G42 5G Stuck on Boot Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-lost-data-from-tecno-spark-20-proplus-by-fonelab-android-recover-data/"><u>Recover lost data from Tecno Spark 20 Pro+</u></a></li>
<li><a href="https://windows11.techidaily.com/sound-revolution-for-your-pc-the-essential-guide-to-audio-drivers-updates/"><u>Sound Revolution for Your PC: The Essential Guide to Audio Drivers Updates</u></a></li>
<li><a href="https://sound-issues.techidaily.com/steelseries-arctis-prime-headset-effective-solutions-to-restore-mic-working-status/"><u>SteelSeries Arctis Prime Headset: Effective Solutions to Restore Mic Working Status</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-to-become-a-win-11-insider/"><u>Step-by-Step to Become a Win 11 Insider</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-resolving-installation-issues-with-microsoft-store-apps/"><u>Steps for Resolving Installation Issues with Microsoft Store Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-frozen-pages-and-scrolling-issues-in-excel/"><u>Stop Frozen Pages and Scrolling Issues in Excel</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/omplete-analysts-toolkit-for-tracking-youtube-audiences-and-money-flow/"><u>The Complete Analyst's Toolkit for Tracking YouTube Audiences & Money Flow</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-pinpointing-device-serial-numbers-on-windows/"><u>The Ultimate Guide to Pinpointing Device Serial Numbers on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-the-finest-free-car-performance-fixes/"><u>The Ultimate Guide to the Finest Free Car Performance Fixes</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/top-10-tips-recording-your-youtube-livestreams/"><u>Top 10 Tips  Recording Your Youtube Livestreams</u></a></li>
<li><a href="https://windows11.techidaily.com/top-6-windows-11-prime-fps-monitors-and-trackers/"><u>Top 6 Windows 11: Prime FPS Monitors & Trackers</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-8-effective-chatgpt-commands-for-cutting-out-online-interruptions/"><u>Top 8 Effective ChatGPT Commands for Cutting Out Online Interruptions</u></a></li>
<li><a href="https://windows11.techidaily.com/top-solutions-for-windows-pin-access-issues-10plus11/"><u>Top Solutions for Windows PIN Access Issues (10+11)</u></a></li>
<li><a href="https://windows11.techidaily.com/turn-around-scheduler-setbacks-with-ease/"><u>Turn Around Scheduler Setbacks with Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-11-entry-into-the-insider-trials/"><u>Unveiling Windows 11: Entry Into the Insider Trials</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-auditory-technology-insight-understanding-sound-forge/"><u>Updated In 2024, Auditory Technology Insight Understanding Sound Forge</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-optimal-music-file-converter-transforming-mpa-files-into-high-quality-mp3s-without-cost/"><u>Updated Optimal Music File Converter Transforming MPA Files Into High-Quality MP3s Without Cost</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-revolution-essential-replacement-tools-to-consider/"><u>Win 11 Revolution: Essential Replacement Tools to Consider</u></a></li>
<li><a href="https://windows11.techidaily.com/win11s-guide-to-stable-background-fixes/"><u>Win11's Guide to Stable Background Fixes</u></a></li>
</ul></div>
