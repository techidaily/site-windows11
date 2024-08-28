---
title: Unlock Default Windows 11 Terminal Features
date: 2024-08-27T16:07:13.224Z
updated: 2024-08-28T16:07:13.224Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unlock Default Windows 11 Terminal Features
excerpt: This Article Describes Unlock Default Windows 11 Terminal Features
keywords: WinTerminalFeaturesUnlocked,Windows11DefaultAccess,TerminalEnhancementsWin11,EnableWindows11Ter,DefaultWinTerMgmt,UnlockTerminalWin11,AccessWinTermSetup
thumbnail: https://thmb.techidaily.com/d3c3a020a8c3e31354179c514456d8a6b689ea566aeb576eef913d65398f2493.jpg
---

## Unlock Default Windows 11 Terminal Features

 Windows Terminal is the next-generation command line platform in Windows 11\. It provides an improved user experience with modern command line tools that enable you to access multiple command lines in a single window. The tool is essential for developers and administrators alike, but sometimes your terminal settings need to be reset to default.

 In this article, we will explain how to reset your Windows Terminal settings back to their original state.

## Why Would You Reset Your Windows Terminal?

 Windows Terminal is an amazing tool for power users and developers. It allows you to access a variety of tools, all in one place, with custom settings and themes that make it easy to work from anywhere. But over time, your Windows Terminal may become cluttered with old settings or themes that have become redundant or are no longer relevant.

 It also helps clear out any potentially harmful malware or corrupt files that might be lurking in the background of your system, hindering your productivity. By doing so, you will ensure that your computer works as fast and as smoothly as possible - giving you the most optimal experience when using this powerful tool.

 Let's now move to the below sections and see how it can be reset.

## How to Reset Windows Terminal Settings by Clearing JSON Files

 In order to reset the settings back to the original defaults, you will need to delete the settings.json file. Here's how to do it.

1. Right click on Start and select**Terminal** from the menu list.
2. Next, click the down-arrow icon and select**Settings** .
3. From the left pane of the Settings page, click**Open JSON file** .  
![Open JSON file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-json-file.jpg)
4. If you're asked which app to use to open the file, then double-click on**Notepad** .
5. On the next page, select all the contents and**Delete** them.
6. Now press**Ctrl + S** on your keyboard to save it.

 Next time you open the app, a new configuration with all the default settings will be created automatically.

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
## How to Reset Windows Terminal Settings Using Command Prompt

 The Command Prompt is a command line tool that can help you accomplish a number of tasks on your computer. It lets you run programs, manage files, and even troubleshoot problems with the operating system. We covered a lot of its functionality in our[beginner's guide to the Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) , but for now, we'll just explore resetting the Windows Terminal settings.

 To reset Windows Terminal Settings back to their defaults, follow these steps:

1. Open the Command Prompt. For this, use the Taskbar search or type "cmd" in the Run dialog.
2. In the Command Prompt window, copy and paste the following command:  
![Reset Windows Terminal Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-command-prompt.jpg)  
del /f /s /q /a "%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json"
3. Now press the**Enter** key to delete the settings.json file.
4. You can now exit the command prompt.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Reset Windows Terminal Settings Using Windows PowerShell

 Windows PowerShell is another command line application that you can use to restore Windows Terminal Settings to their default state. To figure out how, follow these steps:

1. Open Windows PowerShell. You can do this by pressing**Win + R** , typing "PowerShell", and then pressing**Enter** . You can also one of the other[ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
2. In the PowerShell window, copy and paste the following command:  
![Reset Windows Terminal Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-powershell.jpg)  
Remove-Item -Path "$env:LOCALAPPDATA\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json" -Force
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4693127&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.videosoftdev.com/images/video_editor/screenshots/1.jpg" border="0">
VSDC Pro Video Editor is a light professional non-linear video editing suite for creating a movie of any complexity. It supports the most popular video/audio formats and codecs, including 4K, HD and GoPro videos. Preconfigured profiles make the creation of videos for various multimedia and mobile devices absolutely hassle-free.

Key features:

•	Import from any devices and cams, including GoPro and drones. All formats supported. Сurrently the only free video editor that allows users to export in a new H265/HEVC codec, something essential for those working with 4K and HD.
•	Everything for hassle-free basic editing: cut, crop and merge files, add titles and favorite music
•	Visual effects, advanced color correction and trendy Instagram-like filters   
•	All multimedia processing done from one app: video editing capabilities reinforced by  a video converter, a screen capture, a video capture, a disc burner and a YouTube uploader
•	Non-linear editing: edit several files with simultaneously 
•	Easy export to social networks: special profiles for YouTube, Facebook, Vimeo, Twitter and Instagram
•	High quality export – no conversion quality loss, double export speed even of HD files due to hardware acceleration
•	Stabilization tool will turn shaky or jittery footage into a more stable video automatically. 
•	Essential toolset for professional video editing: blending modes, Mask tool, advanced multiple-color Chroma Key  
</a>
<!-- affiliate ads end -->
3. Press**Enter** to execute the command.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Reset Windows Terminal Settings From File Explorer

 If you don't prefer the command line process, you can use Windows File Explorer to reset the settings. In this way, the Terminal will be reset to its default settings, and you can continue using it. Here's how to do it:

1. Open Windows File Explorer. For this, right-click Start and choose**File Explorer** , or press**Win + E** on your keyboard.
2. Copy and paste the following path into the address bar:  
![Reset Windows Terminal Using File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-file-explorer.jpg)  
%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
3. On the next page, right-click on**settings.json** and select**Delete** from the context menu.

 Once you perform the above steps, Settings.json will automatically be created with the default settings.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Resetting the Windows Terminal, Made Easy

 After reading this post, you now know some useful tips that will help you reset the terminal to default settings in Windows 11\. Try them out and find out which one works best for you.


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
<li><a href="https://youtube-docs.techidaily.com/isabling-youtube-ads-across-chrome-firefox-android-and-ios-browsers/"><u>[New] Disabling YouTube Ads Across Chrome, Firefox, Android & iOS Browsers</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-the-ultimate-amazon-prime-series-most-liked-and-watched-on-twitter-for-2024/"><u>[New] The Ultimate Amazon Prime Series  Most Liked & Watched on Twitter for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-bite-size-broadcasting-battle-which-platform-dominates-in-shorter-videos/"><u>[Updated] Bite-Size Broadcasting Battle  Which Platform Dominates in Shorter Videos?</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-securing-perfection-top-10-free-mac-screen-recorders-unveiled/"><u>[Updated] Securing Perfection  TOP 10 FREE Mac Screen Recorders Unveiled</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-streamlabs-rival-in-the-eye-of-a-streamer/"><u>[Updated] Streamlabs' Rival in the Eye of a Streamer</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/capturing-high-fidelity-games-for-2024/"><u>Capturing High Fidelity Games for 2024</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/enhance-your-websites-performance-using-the-advanced-capabilities-of-cookiebot-technology/"><u>Enhance Your Website's Performance Using the Advanced Capabilities of Cookiebot Technology</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-to-microsoft-works-on-windows-latest-editions/"><u>Essential Guide to Microsoft Works on Windows Latest Editions</u></a></li>
<li><a href="https://windows11.techidaily.com/explore-and-connect-advanced-drives-mapping-on-windows-11/"><u>Explore & Connect: Advanced Drives Mapping on Windows 11</u></a></li>
<li><a href="https://youtube-data.techidaily.com/re-and-evaluate-top-7-free-android-adblockers-unveiled-for-2024/"><u>Explore & Evaluate  Top 7 Free Android AdBlockers Unveiled for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/harvest-heartbeats-top-farm-games-for-friendly-fun-for-2024/"><u>Harvest Heartbeats  Top Farm Games for Friendly Fun for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-troubleshoot-common-anydesk-errors-on-windows/"><u>How to Troubleshoot Common AnyDesk Errors on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/identifying-and-correcting-uninstalled-hdd-errors-on-windows-11-pc/"><u>Identifying & Correcting Uninstalled HDD Errors on Windows 11 PC</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-get-and-use-pokemon-go-promo-codes-on-honor-play-7t-drfone-by-drfone-virtual-android/"><u>In 2024, How to Get and Use Pokemon Go Promo Codes On Honor Play 7T | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-vivo-y100i-power-5g-mirror-screen-to-pc-drfone-by-drfone-android/"><u>In 2024, How Vivo Y100i Power 5G Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-share-screen-on-zoom-meeting-guide/"><u>In 2024, Share Screen on Zoom Meeting Guide</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-the-instagram-reel-formula-for-unrivaled-fame/"><u>In 2024, The Instagram Reel Formula for Unrivaled Fame</u></a></li>
<li><a href="https://windows11.techidaily.com/insight-into-windows-maintenance-framework/"><u>Insight Into Windows Maintenance Framework</u></a></li>
<li><a href="https://windows11.techidaily.com/installation-woes-practical-solutions-for-optional-features-on-windows-11-and-11-pro/"><u>Installation Woes: Practical Solutions for Optional Features on Windows 11 & 11 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/live-conversion-of-speech-to-text-using-whisper/"><u>Live Conversion of Speech to Text Using Whisper</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-printer-fixes-on-windows-11-with-ease/"><u>Mastering Printer Fixes on Windows 11 with Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11-cc-settings-and-fixes/"><u>Mastering Windows 11 CC Settings & Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/methodology-to-fix-inactive-thumbnails/"><u>Methodology to Fix Inactive Thumbnails</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-realm-of-windows-tech-mastery/"><u>Navigating the Realm of Windows Tech Mastery</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-let-us-talk-about-the-famous-photoshop-and-most-commonly-used-glitch-effect-the-article-understudy-will-discuss-in-detail-about-photo-glitch-effect-for-/"><u>New Let Us Talk About the Famous Photoshop and Most Commonly Used Glitch Effect. The Article Understudy Will Discuss in Detail About Photo Glitch Effect for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-windows-11-hidden-folders-reveal/"><u>Optimizing Windows 11: Hidden Folders Reveal</u></a></li>
<li><a href="https://fix-guide.techidaily.com/play-store-not-working-on-tecno-camon-20-8-solutions-inside-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Not Working On Tecno Camon 20? 8 Solutions Inside | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/proactive-methods-to-uncover-system-vulnerabilities/"><u>Proactive Methods to Uncover System Vulnerabilities</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstating-active-windows-11-taskbar/"><u>Reinstating Active Windows 11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-external-monitor-connectivity-problems-in-windows/"><u>Resolving External Monitor Connectivity Problems in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-lost-contacts-steam-fixes-for-windows-11/"><u>Restoring Lost Contacts: Steam Fixes for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/safe-navigation-in-windows-11-the-top-8-to-steer-clear-of/"><u>Safe Navigation in Windows 11: The Top 8 To Steer Clear Of</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-your-system-with-these-7-budget-friendly-password-tools/"><u>Secure Your System with These 7 Budget-Friendly Password Tools</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/selecting-your-channel-weighing-up-the-merits-of-igtv-and-youtube-for-2024/"><u>Selecting Your Channel  Weighing Up the Merits of IGTV & YouTube for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/steady-the-shaky-xbox-experience-in-windows/"><u>Steady the Shaky Xbox Experience in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/swiftly-overcoming-frustrations-with-failed-discord-install-on-windows/"><u>Swiftly Overcoming Frustrations with Failed Discord Install on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-necessity-of-vcplusplus-redistribution-packages/"><u>The Necessity of VC++ Redistribution Packages</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-for-clearing-and-refreshing-icons/"><u>The Ultimate Guide for Clearing and Refreshing Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-using-dism-on-windows-11/"><u>The Ultimate Guide to Using DISM on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-to-rescue-your-zip-extraction-mishaps-on-windows-11/"><u>Tips to Rescue Your ZIP Extraction Mishaps on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tutorial-adjust-win11-connection-preferences/"><u>Tutorial: Adjust Win11 Connection Preferences</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11s-latest-driver-compatibility/"><u>Unlocking Windows 11'S Latest Driver Compatibility</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-hidden-windows-startup-items/"><u>Unveiling Hidden Windows Startup Items</u></a></li>
<li><a href="https://windows11.techidaily.com/why-are-ai-computers-distinct-an-exploration/"><u>Why Are AI Computers Distinct? An Exploration</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-ready-effective-microsoft-works-installation/"><u>Win11 Ready: Effective Microsoft Works Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-display-reclaiming-optimal-performance/"><u>Windows 11 Display: Reclaiming Optimal Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-arp-cache-insights-and-clearing-methods/"><u>Windows ARP Cache Insights & Clearing Methods</u></a></li>
</ul></div>
