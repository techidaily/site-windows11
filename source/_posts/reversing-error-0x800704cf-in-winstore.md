---
title: Reversing Error 0X800704CF in WinStore
date: 2024-07-11T21:54:27.940Z
updated: 2024-07-12T21:54:27.940Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reversing Error 0X800704CF in WinStore
excerpt: This Article Describes Reversing Error 0X800704CF in WinStore
keywords: WinErrorX04CF Fix,WindowsStore Issue,0X800704CF Solution,WinStore Error Resolution,Windows Store Crash Repair,0X800704CF Correction,WinOS Error Fixing Guide
thumbnail: https://thmb.techidaily.com/b84b835099bbd2f060100cf1ff53df1a6537fd5a4b5a03be31336b43fbf43c35.jpg
---

## Reversing Error 0X800704CF in WinStore

 Many Microsoft Store users have reported they can’t use the app in both Windows 10 and 11 because of error 0x800704CF. Error 0x800704CF occurs when those users attempt to log into Microsoft Store. Its error message says, “You’ll need the internet for this… 0x800704CF.” This issue arises even when users are connected to the internet and can open web pages.

 Thus, error 0x800704CF is seemingly a Microsoft Store connection issue that renders the app inoperative in Windows 11 and 10\. If you're facing this issue this is how you can resolve error 0x800704CF.

## 1\. Run the Internet Connection and Network Adapters Troubleshooters

 Windows 11 and 10 have a handy collection of troubleshooters that can be a good starting point for fixing many issues. The Internet Connection and Network Adapters troubleshooters could be useful for resolving error 0x800704CF. You can access those troubleshooters via the Control Panel in Windows 11 and 10 as follows:

1. Press**Win + R** at the same time to launch a Run dialog accessory.
2. Input Control Panel in Run and click**OK** .
3. Select the**Large icons** option on Control Panel’s**View by** menu.  
![The Control Panel's large icon view](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/control-panel.jpg)
4. Click**Troubleshooting** to access that applet.
5. Select the**View all** option to see the full list of troubleshooters.  
![The troubleshooting list](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/troubleshooter-list.jpg)
6. Then double-click**Internet Connections** or**Network Adapter** to open one of those troubleshooters.  
![The troubleshooting list](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/troubleshooter-list.jpg)
7. Click**Next** in those troubleshooters and apply any potential fixes suggested.

 Windows Store App is also a troubleshooting tool that could be useful for addressing error 0x800704CF. That one might fix issues with the Microsoft Store app. So, consider running that troubleshooter as well if the others don't provide a fix.

## 2\. Repair and Reset the Microsoft Store App

 Windows has two troubleshooting options for fixing Microsoft Store when it’s not working right. Those Repair and Reset options can resolve all kinds of app bugs and corruption errors. So, those options could feasibly resolve error 0x800704CF for some users. Check out our guide about [how to reset apps in Windows](https://www.makeuseof.com/windows-reset-app/) for details about how to apply this resolution.

![The Reset and Repair buttons](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/repair-button.jpg)

## 3\. Set a Different DNS Server

 Changing DNS server settings is a resolution that’s worked for some users who’ve needed to fix error 0x800704CF. To apply this solution, change your PC’s DNS server to Google via the Control Panel. Our guide for [how to change your DNS server](https://www.makeuseof.com/windows-11-alternate-ways-change-dns-server-settings/) includes step-by-step instructions for how to do that along with the required Google DNS addresses.

![DNS server settings on the Internet Protocol Version window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/internet-protocal-window.jpg)

## 4\. Execute the Remove Proxy Server Command

 Another confirmed method for fixing error 0x800704CF is to run a command for removing the proxy server. Users who’ve confirmed this potential solution ran the Netsh.exe utility to disable proxy, which sets more direct internet access. This is how you can remove the proxy server with the Command Prompt:

1. First, locate the Command Prompt by opening the search box (press**Win** +**S**) and inputting cmd.
2. Open Command Prompt with elevated privileges by clicking a**Run as administrator** option for that app inside the search tool.
3. Input the Netsch.exe command and hit**Enter** :  
`netsh winhttp reset proxy`  
![The remove proxy command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/remove-proxy-command.jpg)
4. Restart Windows 11 or 10 after executing the command.

## 5\. Disable the Microsoft Network Component Setting Client

 Some users have been able to fix error 0x800704CF by disabling the**Microsoft Network Connection** setting, which is enabled by default. It’s ok to disable that component for your connection so long as you don’t need to access resources on a Microsoft network. You can disable the**Client for Microsoft Network** option as follows:

1. Open the Run dialog with the**Win +** **R** key combination.
2. Type input**ncpa.cpl** inside Run.
3. Click**OK** to access the Network Connections Control Panel applet.
4. Right-click your internet network adapter to select a**Properties** option for it.  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/properties-option2.jpg)
5. Deselect the**Client for Microsoft Networks** checkbox.  
![The Client for Microsoft Networks checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/client-for-microsoft-network-option.jpg)
6. Select**OK** to save the new property setting, and restart your computer.

## 6\. Reinstall the Network Adapter Driver

 Error 0x800704CF can occur because of a network adapter driver issue. If your PC’s network driver is faulty, reinstalling it could be the potential solution for you. Try reinstalling your PC’s network adapter driver like this:

1. Use one of the many [ways to open Device Manager](https://www.makeuseof.com/windows-open-device-manager/) and expand the**Network adapters** category.
2. Then right-click your PC’s internet network adapter to select an**Uninstall** **device** option for it.  
![The Uninstall device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/properties-context-menu-option.jpg)
3. Select the**Delete the driver** (or**Attempt to remove the driver**) checkbox.
4. ![The Delete the driver software for this device checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/uninstall-device-window.jpg)  
 Click**Uninstall** inside the confirmation dialog window.
5. To reinstall, click the**Action** menu.  
![The Scan for hardware changes option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/scan-for-hardware-changes.jpg)
6. Select**Scan for hardware changes** on the menu to detect and reinstall the missing network driver.

## 7\. Reregister the Microsoft Store App

 Reregistering the Microsoft Store app will reset it to a default configuration, which is the closest thing to reinstalling that app (it doesn’t have an option for uninstalling).

 To apply this solution, open Command Prompt with admin rights, as outlined in steps one and two of resolution four in this guide. Then execute this command:

`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml&}`

## 8\. Reset Your PC’s Network

 Another potential cause of error 0x800704CF is misconfigured network settings. To address such a potential cause, you can reset your PC’s network components to default settings. Doing so also reinstalls network adapters.

![The Network Reset option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/network-reset-option.jpg)

 A network reset will erase saved connection details. So, make sure you’ve got your network password handy for re-establishing your connection. Our [how to reset your network settings on Windows](https://www.makeuseof.com/reset-network-settings-windows-11/) guide tells you how to apply this possible error 0x800704CF solution in Windows 11\. Fortunately, the steps for Windows 10 are the same.

## 9\. Set Up an Alternative User Account

 You might need to fix error 0x800704CF because of an issue with your current user account. Some Windows troubleshooting tools could feasibly resolve that user account glitch. However, setting up and migrating to a new user account is an alternative troubleshooting method that you can try.

![The Add account button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/add-account-option2.jpg)

 To apply this solution, check out our post for [resolving Windows issues by setting up a new user account](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/) . Create a new local user account as instructed in that article, and then log in to the new account to see if error 0x800704CF occurs there. If not, you can migrate your user files to the new account as covered in that guide.

## Get Microsoft Store Error 0x800704CF Sorted on Your PC

 Error 0x800704CF can be a taxing issue to resolve in Windows. It can seemingly arise because of networking, the Microsoft Store app, and Windows account issues, which makes troubleshooting that issue a bit of a slog. However, the troubleshooting methods outlined above will probably get error 0x800704CF sorted on most users’ PCs.

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
<li><a href="https://windows11.techidaily.com/the-undetectable-file-hiding-technique-on-windows-systems/"><u>The Undetectable File Hiding Technique on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-microsoft-store-programs-on-windows-1011-systems/"><u>Restoring Microsoft Store Programs on Windows 10/11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/top-10-windows-diagnostics-powerhouses/"><u>Top 10 Windows Diagnostics Powerhouses</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/aspect-ratio-mastery-boost-your-tiktok-presence/"><u>Aspect Ratio Mastery Boost Your TikTok Presence</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-advanced-file-navigation-skills-steering-clear-of-ls/"><u>Unraveling Advanced File Navigation Skills: Steering Clear of LS</u></a></li>
<li><a href="https://extra-hints.techidaily.com/stabilizing-shaky-images-a-realistic-benefit-or-hype/"><u>Stabilizing Shaky Images  A Realistic Benefit or Hype?</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-methods-for-verifying-windows-11-installation/"><u>The Essential Methods for Verifying Windows 11 Installation</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-stop-life360-from-tracking-you-on-infinix-note-30-vip-drfone-by-drfone-virtual-android/"><u>How to Stop Life360 from Tracking You On Infinix Note 30 VIP? | Dr.fone</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-the-best-of-google-play-top-android-apps-for-2024/"><u>Updated The Best of Google Play Top Android Apps for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/transforming-text-to-art-obsidian-canvas-techniques/"><u>Transforming Text to Art: Obsidian Canvas Techniques</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-queue-unavailable-on-local-pc/"><u>Print Queue Unavailable on Local PC</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-error-x0001-in-nvidias-windows-11-app/"><u>Troubleshooting Error X0001 in Nvidia's Windows 11 App</u></a></li>
<li><a href="https://extra-resources.techidaily.com/dive-into-films-at-zero-price-versatile-vob-player-software/"><u>Dive Into Films at Zero Price  Versatile VOB PLAYER Software</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-the-potential-of-task-scheduler-in-windows/"><u>Unleash the Potential of Task Scheduler in Windows</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-2024-approved-maximizing-roi-setting-up-and-assessing-fb-instream-ads/"><u>[New] 2024 Approved  Maximizing ROI  Setting Up & Assessing FB Instream Ads</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-wsl-2-for-efficient-docker-workflows/"><u>Optimizing WSL 2 for Efficient Docker Workflows</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-editing-essentials-how-to-turn-your-home-videos-into-works-of-art/"><u>Updated In 2024, Editing Essentials How to Turn Your Home Videos Into Works of Art</u></a></li>
<li><a href="https://windows11.techidaily.com/turbocharge-android-studio-for-peak-performance-in-windows/"><u>Turbocharge Android Studio for Peak Performance in Windows</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-essential-tips-on-calculating-your-youtube-traffic-and-earnings/"><u>[Updated] 2024 Approved  Essential Tips on Calculating Your YouTube Traffic & Earnings</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-process-windows-11-ms-work-installation/"><u>Unveiling the Process: Windows 11 MS Work Installation</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-best-10-apps-to-enhance-your-instagram-story-slideshow-for-2024/"><u>Updated Best 10 Apps to Enhance Your Instagram Story Slideshow for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-hollywood-hacks-a-filmmakers-guide-to-cinematic-excellence/"><u>2024 Approved  Hollywood Hacks  A Filmmaker’s Guide to Cinematic Excellence</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-error-0x8024a205-in-winupdate/"><u>Troubleshooting Error 0X8024a205 in WinUpdate</u></a></li>
<li><a href="https://windows11.techidaily.com/protect-your-passwords-in-windows-files-easily/"><u>Protect Your Passwords in Windows Files Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-reset-of-windows-icon-positions/"><u>Swift Reset of Windows Icon Positions</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-your-nubia-z50-ultra-auto-does-not-work-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do if Your Nubia Z50 Ultra Auto Does Not Work | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-forging-partnerships-with-brands-5-instagram-strategies-for-growth/"><u>In 2024, Forging Partnerships with Brands  5 Instagram Strategies for Growth</u></a></li>
<li><a href="https://windows11.techidaily.com/rejuvenating-your-apathetic-windows-start-button-click/"><u>Rejuvenating Your Apathetic Windows Start Button Click</u></a></li>
<li><a href="https://activate-lock.techidaily.com/3-effective-ways-to-bypass-activation-lock-on-iphone-7-by-drfone-ios/"><u>3 Effective Ways to Bypass Activation Lock on iPhone 7</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-non-active-thermal-management-on-pcs/"><u>Reviving Non-Active Thermal Management on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/tapping-into-your-true-essence-guide-for-accessing-windows-silent-personal-analyzer/"><u>Tapping Into Your True Essence: Guide for Accessing Windows' Silent Personal Analyzer</u></a></li>
<li><a href="https://howto.techidaily.com/google-play-services-wont-update-12-fixes-are-here-on-realme-narzo-60x-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Google Play Services Wont Update? 12 Fixes are Here on Realme Narzo 60x 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ultimate-yt-shorts-companion-for-2024/"><u>Your Ultimate YT Shorts Companion for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-efficiency-in-consuming-tiktok-media-for-2024/"><u>[New] Efficiency in Consuming TikTok Media for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-your-drive-enable-file-cleanup-in-win11-operating-system/"><u>Optimize Your Drive: Enable File Cleanup in Win11 Operating System</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-microsoft-store-hiccup-0x80131500/"><u>Remedying Microsoft Store Hiccup 0X80131500</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-evade-social-media-shunning-fbs-hidden-dos-and-donts/"><u>[Updated] Evade Social Media Shunning  FB's Hidden Do's & Don'ts</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-speed-and-efficiency-windows-shortcuts-for-uwp/"><u>Unleash Speed and Efficiency: Windows Shortcuts for UWP</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-missing-msvcr110dll-in-windows-environment/"><u>Overcoming Missing msvcr110.dll in Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-frozen-netflix-on-windows/"><u>Troubleshooting Frozen Netflix on Windows</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-enhance-visibility-with-any-channel-title-through-free-makers/"><u>[Updated] In 2024, Enhance Visibility With Any Channel Title Through Free Makers</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-using-wireless-and-cable-in-harmony-on-windows/"><u>The Ultimate Guide: Using Wireless and Cable in Harmony on Windows</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-gamify-success-15-best-capture-software-for-pc-and-mac/"><u>2024 Approved  Gamify Success  #15 Best Capture Software for PC and Mac</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-printer-in-use-issue-on-windows-11/"><u>Overcoming Printer In Use Issue on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolve-compromised-windows-defender-in-windows-11/"><u>Resolve Compromised Windows Defender in Windows 11</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-the-essential-guide-to-transferring-tunes-across-platforms/"><u>[Updated] The Essential Guide to Transferring Tunes Across Platforms</u></a></li>
<li><a href="https://driver-install.techidaily.com/free-tp-link-drivers-for-wireless-pcs-secure-downloads/"><u>Free TP Link Drivers for Wireless PCs - Secure Downloads!</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlined-graphics-the-key-to-optimal-radeon-performance-in-windows-11/"><u>Streamlined Graphics: The Key to Optimal Radeon Performance in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-workflow-key-windows-programs-for-taskmasters/"><u>Optimizing Workflow: Key Windows Programs for Taskmasters</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-chkdsk-vs-scan-disk-dissecting-windows-tools/"><u>Understanding Chkdsk Vs. Scan Disk: Dissecting Windows Tools</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/2024-approved-essential-tools-for-creating-dynamic-talking-avatars/"><u>2024 Approved Essential Tools for Creating Dynamic Talking Avatars</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-correct-wsl-error-code-4294967295-in-windows/"><u>Steps to Correct WSL Error Code 4294967295 in Windows</u></a></li>
</ul></div>
