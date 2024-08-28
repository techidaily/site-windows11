---
title: The Essential Knowledge of Command Line Nicknames
date: 2024-08-27T16:06:44.018Z
updated: 2024-08-28T16:06:44.018Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Essential Knowledge of Command Line Nicknames
excerpt: This Article Describes The Essential Knowledge of Command Line Nicknames
keywords: CLI Basics,Command Names,Shell Shortcuts,Coding Etiquette,Terminal Tips,Scripting Syntax,OS Naming Conventions
thumbnail: https://thmb.techidaily.com/14598feaeb4d0e61d08a761998cd6976c067dba5c944d538d367654e5b9adad2.jpg
---

## The Essential Knowledge of Command Line Nicknames

 If you're trying to open an app like Microsoft Paint in the Run Dialog and see an error message, it could be caused by your app aliases. But what exactly are App Execution Aliases, where do you find them, and how do you use them?

## What Are App Execution Aliases?

 An alias is an alternative name given to something. The most obvious example is the codename given to a spy or undercover agent. On Windows, aliases have nothing to do with spying. Instead, they are used for streamlining tasks, such as entering commands.

 Windows 10 and 11 both allow aliases to be declared for some apps by default. The available apps vary but are often those commonly associated with command line tools. Giving an app an alias allows it to be executed using a shorter title rather than the full name or path.

 App aliases can be used in several[Windows Command Line Interfaces](https://www.makeuseof.com/what-is-cli-what-does-it-stand-for/) (CLI), including the Run Dialog, Command Prompt, and[PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) . If you use these tools with any regularity, app aliases can help to streamline entering commands.

## How to Enable App Execution Aliases in Settings

 You can enable and disable aliases for compatible apps in the main settings in both Windows 10 and 11\. If more than one app uses the same alias name, you can choose which has the alias applied to it.

In Windows 11:

1. Open**Settings > Apps** , and look for**Advanced app settings** .
2. In the advanced app settings, click**App execution aliases** to see the list of compatible apps.
3. Use the slider switches to enable or disable the alias for each app. You can see the alias name below each app.

![app aliases in windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win11.jpg)

In Windows 10:

1. If you're using Windows 10, you'll find the aliases in**Settings > Apps & features** .
2. Click the**App execution aliases** link near the top of the Apps & features page.
3. You can then enable and disable aliases using the switches.

![app aliases in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win10.jpg)

 By default, in both Windows 10 and 11, you can only enable or disable existing app aliases. But if you don't mind editing the Registry, you can create new aliases for many other apps.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Create App Execution Aliases in Registry Editor

 Before editing or creating registry keys, it is advisable to[create a full backup of the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . Of course, you should also ensure you understand how to restore the Registry from that backup.

 The process below for creating app execution aliases in the Registry Editor should be the same in both Windows 10 and 11.

1. Open**Windows Search** , type**Registry Editor** , and click on the search result to open it.
2. In the editor, navigate to **HKEY\_CURRENT\_USER\\Software\\Microsoft\\Windows\\CurrentVersion\\App Paths** .
3. Next, right-click on the**App Paths** key in the left-hand pane, and select**New > Key** .
4. Give the new key an alias name that relates to the app and ends with .exe. For example, if the alias is for Calendar, call it something like cal.exe.
5. With the alias selected, double-click the**Default** value in the right-hand pane.  
![editing app aliases in registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-regedit.jpg)
6. In the Value data field, you will need to enter the full path to the app executable file. For example**C:\\Program Files (x86)\\Calendar.exe** .
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
7. Right-click in the right pane and select**New > String value** . Name the string**path** . The change the Value data to the same path as above, but without the app filename.

 You can now close the Registry Editor. The new App Execution Alias will now be available to use in the Windows CLIs.

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Using and Creating App Execution Aliases

 Entering commands into tools such as Command Prompt and PowerShell can be laborious. You can streamline that process by enabling or creating aliases for apps that commonly feature in those commands. Why type out a full path to an executable file when you can point to it with a few keystrokes?


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
<li><a href="https://screen-sharing-recording.techidaily.com/new-screen-savvy-taking-screenshots-on-windows/"><u>[New] Screen Savvy  Taking Screenshots on Windows</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-the-essentials-for-classic-gaming-top-5-ps1-emulators-reviewed-for-2024/"><u>[New] The Essentials for Classic Gaming  Top 5 PS1 Emulators Reviewed for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-outwiththeold-camerasbeyondmycam/"><u>[Updated] 2024 Approved  OutWithTheOld  CamerasBeyondMyCam</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-live-recording-analyzer/"><u>[Updated] In 2024, Live Recording Analyzer</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-the-artisans-guide-to-flawless-free-and-paid-software-video-downloads/"><u>[Updated] In 2024, The Artisan's Guide to Flawless Free and Paid Software Video Downloads</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-briskbounce-momentmirror-tape/"><u>2024 Approved  BriskBounce MomentMirror Tape</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-laying-the-groundwork-15-basic-shots-every-director-needs/"><u>2024 Approved  Laying the Groundwork  15 Basic Shots Every Director Needs</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-lifelike-broadcasts-which-aspect-holds-the-high-ground/"><u>2024 Approved  Lifelike Broadcasts  Which Aspect Holds the High Ground?</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-ustream-live-and-comparable-platforms/"><u>2024 Approved  Ustream Live & Comparable Platforms</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-you-when-your-google-pixel-8-is-off-drfone-by-drfone-virtual-android/"><u>Can Life360 Track You When Your Google Pixel 8 is off? | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/cyber-satirist-studio/"><u>Cyber Satirist Studio</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-and-install-m-audio-fast-track-drivers-for-various-windows-versions-today/"><u>Download & Install M-Audio Fast Track Drivers for Various Windows Versions Today!</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-to-microsoft-works-on-windows-latest-editions/"><u>Essential Guide to Microsoft Works on Windows Latest Editions</u></a></li>
<li><a href="https://windows11.techidaily.com/explore-and-connect-advanced-drives-mapping-on-windows-11/"><u>Explore & Connect: Advanced Drives Mapping on Windows 11</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723862750484-eyoyo-em105-review-the-perfect-blend-of-size-value-and-power-in-a-105-inch-screen/"><u>Eyoyo EM105 Review: The Perfect Blend of Size, Value & Power in a 10.5-Inch Screen</u></a></li>
<li><a href="https://some-techniques.techidaily.com/hdr-camera-mastery-essential-buying-tips-for-2024/"><u>HDR Camera Mastery  Essential Buying Tips for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-contacts-files-from-nokia-c12-by-fonelab-android-recover-contacts/"><u>How To  Restore Missing Contacts Files from Nokia C12.</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-change-xiaomi-redmi-k70-location-on-skout-drfone-by-drfone-virtual-android/"><u>How to Change Xiaomi Redmi K70 Location on Skout | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-execute-the-windows-startup-check/"><u>How to Execute the Windows Startup Check</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-get-the-apple-id-verification-code-on-apple-iphone-8-in-the-best-ways-by-drfone-ios/"><u>How To Get the Apple ID Verification Code On Apple iPhone 8 in the Best Ways</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-turn-off-google-location-to-stop-tracking-you-on-oppo-find-n3-drfone-by-drfone-virtual-android/"><u>How to Turn Off Google Location to Stop Tracking You on Oppo Find N3 | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-xiaomi-14-ultra-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>How to Unlock Xiaomi 14 Ultra Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://windows11.techidaily.com/identifying-and-correcting-uninstalled-hdd-errors-on-windows-11-pc/"><u>Identifying & Correcting Uninstalled HDD Errors on Windows 11 PC</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-an-easy-to-follow-methodology-for-initiating-a-productive-skype-conversation-among-various-os-users/"><u>In 2024, An Easy-to-Follow Methodology for Initiating a Productive Skype Conversation Among Various OS Users</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-6-appsservices-to-trace-any-nokia-c22-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, Top 6 Apps/Services to Trace Any Nokia C22 Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/indoor-games-galore-top-9-screen-less-titles-for-android-gamers-for-2024/"><u>Indoor Games Galore  Top 9 Screen-Less Titles for Android Gamers for 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/infinix-note-30-screen-unresponsive-heres-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Infinix Note 30 Screen Unresponsive? Heres How to Fix It | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/insight-into-windows-maintenance-framework/"><u>Insight Into Windows Maintenance Framework</u></a></li>
<li><a href="https://windows11.techidaily.com/installation-woes-practical-solutions-for-optional-features-on-windows-11-and-11-pro/"><u>Installation Woes: Practical Solutions for Optional Features on Windows 11 & 11 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/live-conversion-of-speech-to-text-using-whisper/"><u>Live Conversion of Speech to Text Using Whisper</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-printer-fixes-on-windows-11-with-ease/"><u>Mastering Printer Fixes on Windows 11 with Ease</u></a></li>
<li><a href="https://techtrends.techidaily.com/maximizing-your-education-perks-steps-to-obtain-a-microsoft-student-reduction/"><u>Maximizing Your Education Perks: Steps to Obtain a Microsoft Student Reduction</u></a></li>
<li><a href="https://windows11.techidaily.com/methodology-to-fix-inactive-thumbnails/"><u>Methodology to Fix Inactive Thumbnails</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11-netstat-to-monitor-tcpip-activity/"><u>Navigating Windows 11 Netstat to Monitor TCP/IP Activity</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-windows-11-hidden-folders-reveal/"><u>Optimizing Windows 11: Hidden Folders Reveal</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-win11s-installer-lacks-permissions-issue/"><u>Overcoming Win11's Installer Lacks Permissions Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/proactive-methods-to-uncover-system-vulnerabilities/"><u>Proactive Methods to Uncover System Vulnerabilities</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-onedrive-x-error-code-sign-in-woes-on-windows-11/"><u>Quick Fixes for OneDrive X-Error Code: Sign In Woes on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstating-active-windows-11-taskbar/"><u>Reinstating Active Windows 11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-external-monitor-connectivity-problems-in-windows/"><u>Resolving External Monitor Connectivity Problems in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-lost-contacts-steam-fixes-for-windows-11/"><u>Restoring Lost Contacts: Steam Fixes for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/safe-navigation-in-windows-11-the-top-8-to-steer-clear-of/"><u>Safe Navigation in Windows 11: The Top 8 To Steer Clear Of</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-your-system-with-these-7-budget-friendly-password-tools/"><u>Secure Your System with These 7 Budget-Friendly Password Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/swiftly-overcoming-frustrations-with-failed-discord-install-on-windows/"><u>Swiftly Overcoming Frustrations with Failed Discord Install on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-for-clearing-and-refreshing-icons/"><u>The Ultimate Guide for Clearing and Refreshing Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-using-dism-on-windows-11/"><u>The Ultimate Guide to Using DISM on Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/tips-of-transferring-messages-from-oneplus-nord-ce-3-lite-5g-to-iphone-1415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Tips of Transferring Messages from OnePlus Nord CE 3 Lite 5G to iPhone 14/15 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-to-rescue-your-zip-extraction-mishaps-on-windows-11/"><u>Tips to Rescue Your ZIP Extraction Mishaps on Windows 11</u></a></li>
<li><a href="https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-realme-12-pro-5g-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Troubleshooting Guide How to Fix an Unresponsive Realme 12 Pro 5G Screen | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/tutorial-adjust-win11-connection-preferences/"><u>Tutorial: Adjust Win11 Connection Preferences</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-full-task-mastery-administrative-run-in-task-manager-on-win11/"><u>Unlocking Full Task Mastery: Administrative Run in Task Manager on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11s-latest-driver-compatibility/"><u>Unlocking Windows 11'S Latest Driver Compatibility</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-hidden-windows-startup-items/"><u>Unveiling Hidden Windows Startup Items</u></a></li>
<li><a href="https://windows11.techidaily.com/what-hides-in-ftdibussys-windows-memory-integrity-disruption/"><u>What Hides in ftdibus.sys: Windows' Memory Integrity Disruption</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-tips-disabling-unwanted-mouse-speed-boosting/"><u>Win 11 Tips: Disabling Unwanted Mouse Speed Boosting</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-ready-effective-microsoft-works-installation/"><u>Win11 Ready: Effective Microsoft Works Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-display-reclaiming-optimal-performance/"><u>Windows 11 Display: Reclaiming Optimal Performance</u></a></li>
</ul></div>
