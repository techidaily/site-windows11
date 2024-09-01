---
title: "Unraveling Winget Woes: Solutions for Windows 11 Users"
date: 2024-08-31T22:17:49.079Z
updated: 2024-09-01T22:17:49.079Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unraveling Winget Woes: Solutions for Windows 11 Users"
excerpt: "This Article Describes Unraveling Winget Woes: Solutions for Windows 11 Users"
keywords: Win11 Woes Fix,Wingset Troubleshoot,PC Performance Tips,Windows 11 Optimize,XP Error Solutions,System Speed Enhance,User-Friendly Windows
thumbnail: https://thmb.techidaily.com/bae70dc1da321109f70e787435e8a7bf8638e992652aa5e9b27c3e355526ca4c.jpg
---

## Unraveling Winget Woes: Solutions for Windows 11 Users

 Winget is a command-line tool that can download and install app packages from MS Store and the apps listed in its repository. It saves a lot of time that would be otherwise wasted in searching the Microsoft Store or the web for a particular app, downloading it, and then manually installing it.

 But some users report that Winget is not working on their PC. They face a "The system cannot execute the specified program" and cannot run any commands, This post will discuss multiple methods to resolve the issue and restore Winget to its working state. Let’s begin.

## Reasons Why Winget Stops Working on Windows

 Here are the following reasons why Winget is not working on your Windows PC:

1. You are running an outdated version of the App Installer.
2. Winget servers are down, or you don’t have an active internet connection.
3. The app execution alias is not configured or inactive for Winget.
4. App Installer failed to add the PATH environment variable automatically while installing.

 Now, you know the reasons behind Winget not working issue. Try out these eight methods to resolve the issue and use your favorite package manager again.

## 1\. Close and Reopen Winget in the Terminal App

 Before moving on to advanced fixes, completely close the Command Prompt or PowerShell instance you are running on the PC. You can use the Task Manager to stop an unresponsive instance of either of these command-line tools.

 After that, open Command Prompt or PowerShell with administrator privileges on your system. Type Winget and press the **Enter** key to check if Winget works now.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. Check if the Winget Servers Are Down

 Winget is an online tool that needs a robust internet connection to search for a package in various repositories and then download and install them. If the Winget servers are down or inactive, it won’t be able to fetch results from repositories. So, check if Winget servers are down using [DownDetector](https://redirect.viglink.com/?format=go&jsonp=vglnk%5F168667664973511&key=eac202ea7a96cf485281d6c4ffa2069e&libId=liuggg0i0103es17000ULlmtlntd&loc=https%3A%2F%2Fwww.makeuseof.com%2Fhow-to-fix-0x8004def5-onedrive-error-code-windows-11%2F&ccpaConsent=1---&v=1&opt=true&optExText=false&out=https%3A%2F%2Fdowndetector.com%2F&ref=https%3A%2F%2Fwww.makeuseof.com%2Fauthor%2Fabhishekkumar-mishra%2F&title=9%20Ways%20to%20Fix%20the%200x8004def5%20OneDrive%20Error%20Code%20on%20Windows%2011&txt=DownDetector) or a similar website.

 You can also check if your Windows PC can connect to the internet. Simply open a web browser and access a website or run a web-based app to confirm internet connectivity. If the servers are down, you will have to wait until they come up live again to use Winget.

## 3\. Perform a Complete System Shutdown

 Windows uses Fast Startup to hibernate kernel-level processes and if any of these glitch, they remain in that state after your power on the system. So, perform a complete shutdown to close and relaunch all the core services and then try to run Winget. Here’s how to do it:

1. Press **Win + R** to open the Run dialog box. Type **cmd** and press **Ctrl + Shift + Enter** keys to [open the Command Prompt with administrator privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Now, type the following command and press the Enter key: **shutdown /s /f /t 0**  
![Completely Shutdown your PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/completely-shutdown-your-pc.jpg)
3. Your system will shut down. It will take longer than a usual shutdown because Windows will close everything.
<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Power on your system and try to run Winget using the Terminal app to check if it works now.

## 4\. Update App Installer

 Winget is a part of Windows 10 and 11 now and is shipped to PCs using the App Installer application. If you haven’t updated the App Installer in a while, you can face issues in running Winget and managing packages. Winget is included only in version 1.11.11451 or higher of the App Installer. If you have a version older than that, you cannot use Winget from the terminal.

![Update App Installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/update-app-installer.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 So, open Microsoft Store and check the library section for any pending updates for the App Installer. Manually search and install the update and check if Winget works now.

## 5\. Enable the App Execution Alias

 If the App Execution Alias for Winget is disabled, it won’t work when you try accessing Winget from the terminal. So, you must enable it in the app settings. Repeat the following steps:

1. Right-click on the **Start** button to open the **Power User** menu. Click on the **Settings** app.
2. Navigate to the left-hand side menu and click on the **Apps** option.
3. Now, click on the **Advanced app settings** option. Then click on the **App execution aliases** option.
4. Locate the **Windows Package Manager Client** option. Check the toggle next to it. If it is disabled, click on it to **enable** the app execution alias for the app.  
![Enable the App Execution Alias-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/enable-the-app-execution-alias-1.jpg)
5. Close the Settings app.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4742929&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/boxshot(2).png" border="0">Kanto Player Professional</a>
<!-- affiliate ads end -->

## 6\. Manually Add the Path Environment Variable

 Ae wrongly configured Winget path can also produce errors. So, you must manually add the correct path in Environment Variables using the Advanced System Properties window. Repeat the following steps:

1. Press **Win + R** to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **sysdm.cpl ,3** in the text box and press the **Enter** key to open **Advanced System Properties**.
2. Click on the **Environment Variables** button. Click on the **Path** entry and then click on the **Edit** button.
3. Now, click on the New button and paste the following path: **%UserProfile%\\AppData\\Local\\Microsoft\\WindowsApps**  
![Manually Add the Path Environment Variable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/manually-add-the-path-environment-variable.jpg)
4. Click on the **OK** button. Restart your PC.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
5. Open the Terminal app and check if Winget works or not.

## 7\. Re-register Winget Using PowerShell

 If Winget isn’t working on your PC, you can re-register it using PowerShell. Since it is a part of the App Installer which is a system app, it is possible to re-register it. Repeat the following steps:

1. Press **Win + R** to open the Run dialog box. Type **PowerShell** and press the **Ctrl + Shift + Enter** keys at once.
2. The PowerShell window will launch with admin rights. Paste the following code and press the **Enter** key to execute it:  
`Add-AppxPackage -DisableDevelopmentMode -Register "C:\Program Files\WindowsApps\Microsoft.Winget.Source_2021.718.1322.843_neutral__8wekyb3d8bbwe\AppXManifest.xml" -Verbose`
3. You won’t see any confirmation message after the command executes successfully. Close the PowerShell window and restart your PC.  
![Re-register Winget Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/re-register-winget-using-powershell.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
## 8\. Try Some Generic Windows Fixes

 If none of the methods work for you, try our generic fixes like SFC and DISM scans that find and fix the system file corruption and service Windows Image components. You must [run the SFC scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) first and allow it to find and replace the corrupt system files, if any. After that, [run the DISM scan](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) in online mode.

 After running these scans, you can use System Restore to revert the PC to a point in time when everything worked fine. Lastly, you can perform a complete system reset. You can choose the Keep my files option to preserve all your files while [factory resetting Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/).

## Make Winget Functional Again

 Winget is a fantastic package manager that helps you control and manage app packages from the terminal. Ensure robust internet connectivity and check if the app execution alias is active for Winget. Manually reconfigure the PATH for Winget and re-register the App Installer using PowerShell. If you want a GUI version of Winget, you can try Winstall which helps you batch-install apps.

 But some users report that Winget is not working on their PC. They face a "The system cannot execute the specified program" and cannot run any commands, This post will discuss multiple methods to resolve the issue and restore Winget to its working state. Let’s begin.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-cumulative-community-capture/"><u>[New] 2024 Approved  Cumulative Community Capture</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-enhance-your-photos-with-top-insta-editors/"><u>[New] 2024 Approved  Enhance Your Photos with Top Insta Editors</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-end-to-end-camera-rotation-explained-for-2024/"><u>[New] End-to-End Camera Rotation Explained for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-in-2024-aviations-new-titans-dji-phantom-pro-and-gopro-k20-ii/"><u>[New] In 2024, Aviation's New Titans  DJI Phantom Pro & GoPro K20 II</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-beginning-creators-guide-top-8-free-youtube-tutorials/"><u>[New] In 2024, Beginning Creator's Guide  Top 8 Free YouTube Tutorials</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-innovative-8-image-collections-for-macbook-screens/"><u>[New] Innovative 8 Image Collections for MacBook Screens</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-simplify-satire-funniest-memes-made-simple/"><u>[New] Simplify Satire  Funniest Memes Made Simple</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-harmonize-your-content-a-guide-to-musical-instagrams/"><u>[Updated] Harmonize Your Content  A Guide to Musical Instagrams</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-amplify-impact-strategies-for-growing-youtube-fans/"><u>[Updated] In 2024, Amplify Impact  Strategies for Growing YouTube Fans</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-in-2024-exploring-the-nuances-in-physical-gesture-detection/"><u>[Updated] In 2024, Exploring the Nuances in Physical Gesture Detection</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-audience-captivation-for-personal-podcasts/"><u>2024 Approved  Audience Captivation for Personal Podcasts</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-collective-chronicle-converter/"><u>2024 Approved  Collective Chronicle Converter</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/catchemall-celebrate-national-pokemon-day-with-virtual-location-on-realme-gt-5-drfone-by-drfone-virtual-android/"><u>CatchEmAll Celebrate National Pokémon Day with Virtual Location On Realme GT 5 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-to-microsoft-works-on-windows-latest-editions/"><u>Essential Guide to Microsoft Works on Windows Latest Editions</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-windows-junk-uninstall-list-revealed/"><u>Essential Windows Junk: Uninstall List Revealed</u></a></li>
<li><a href="https://windows11.techidaily.com/financial-success-in-w11-microsofts-blueprint/"><u>Financial Success in W11: Microsoft's Blueprint</u></a></li>
<li><a href="https://windows11.techidaily.com/ftdibussys-dissected-why-it-causes-disturbances-in-windows-memory/"><u>Ftdibus.sys Dissected: Why It Causes Disturbances in Windows Memory</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/how-to-attract-and-retain-more-viewers-on-youtube-for-2024/"><u>How to Attract and Retain More Viewers on YouTube for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-execute-the-windows-startup-check/"><u>How to Execute the Windows Startup Check</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-jump-start-your-pc-beyond-s-mode-limits/"><u>How to Jump-Start Your PC Beyond S Mode Limits</u></a></li>
<li><a href="https://win-solutions.techidaily.com/how-to-tackle-excessive-cpu-usage-on-discord-a-comprehensive-guide/"><u>How to Tackle Excessive CPU Usage on Discord: A Comprehensive Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/identifying-and-correcting-uninstalled-hdd-errors-on-windows-11-pc/"><u>Identifying & Correcting Uninstalled HDD Errors on Windows 11 PC</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-unlock-your-honor-play-8t-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>In 2024, Unlock Your Honor Play 8T Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/master-cortana-archive-windows-based-steps/"><u>Master Cortana Archive: Windows-Based Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-empty-folder-location-and-deletion-in-windows/"><u>Mastering Empty Folder Location and Deletion in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-wi-fi-settings-seamless-action-integration-on-microsoft-devices/"><u>Mastering Wi-Fi Settings: Seamless Action Integration on Microsoft Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11-folder-access-top-techniques-explored/"><u>Mastering Windows 11 Folder Access: Top Techniques Explored</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-wpm-in-windows-11-a-step-by-step-guide/"><u>Mastering WPM in Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-of-common-obs-error-fixes-on-windows-11/"><u>Mastery of Common OBS Error Fixes on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11-netstat-to-monitor-tcpip-activity/"><u>Navigating Windows 11 Netstat to Monitor TCP/IP Activity</u></a></li>
<li><a href="https://extra-tips.techidaily.com/nikon-1-j5-4k-camera-review/"><u>Nikon 1 J5 4K Camera Review</u></a></li>
<li><a href="https://win-blog.techidaily.com/overcoming-bugs-and-glitches-how-to-keep-your-robocop-rogue-city-running-smoothly-on-pc/"><u>Overcoming Bugs and Glitches - How to Keep Your RoboCop: Rogue City Running Smoothly on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-win11s-installer-lacks-permissions-issue/"><u>Overcoming Win11's Installer Lacks Permissions Issue</u></a></li>
<li><a href="https://howto.techidaily.com/play-store-not-working-on-oppo-find-x6-pro-8-solutions-inside-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Not Working On Oppo Find X6 Pro? 8 Solutions Inside | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/premium-free-excellence-analyzing-and-sharing-best-free-luts/"><u>Premium-Free Excellence  Analyzing and Sharing Best Free LUTs</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-onedrive-x-error-code-sign-in-woes-on-windows-11/"><u>Quick Fixes for OneDrive X-Error Code: Sign In Woes on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-operational-issues-with-windows-tablet-stylus/"><u>Rectifying Operational Issues with Windows Tablet Stylus</u></a></li>
<li><a href="https://windows11.techidaily.com/reimagine-windows-11-notepad-aesthetics-and-readability/"><u>Reimagine Windows 11 Notepad: Aesthetics & Readability</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-external-monitor-connectivity-problems-in-windows/"><u>Resolving External Monitor Connectivity Problems in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-lost-contacts-steam-fixes-for-windows-11/"><u>Restoring Lost Contacts: Steam Fixes for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-vanished-windows-badge-icons/"><u>Reviving Vanished Windows Badge Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-phone-integration-for-retailers-using-windows-11-and-intel-unison/"><u>Seamless Phone Integration for Retailers Using Windows 11 & Intel Unison</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-your-system-with-these-7-budget-friendly-password-tools/"><u>Secure Your System with These 7 Budget-Friendly Password Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-disregard-error-components-not-present-in-win10win11/"><u>Steps to Disregard Error: Components Not Present in Win10/Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/stepwise-method-to-activate-dark-mode-in-notepad-on-windows-11-pcs/"><u>Stepwise Method to Activate Dark Mode in Notepad on Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/swiftly-syncing-spotify-on-windows-11-systems/"><u>Swiftly Syncing Spotify on Windows 11 Systems</u></a></li>
<li><a href="https://hardware-help.techidaily.com/the-hardware-hub-a-comprehensive-resource-for-savvy-technology-enthusiasts/"><u>The Hardware Hub: A Comprehensive Resource for Savvy Technology Enthusiasts</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-ultimate-guide-to-creating-and-managing-slack-notifications/"><u>The Ultimate Guide to Creating and Managing Slack Notifications</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-disabling-onedrive-on-windows-11s-explore/"><u>Tips for Disabling OneDrive on Windows 11'S Explore</u></a></li>
<li><a href="https://android-frp.techidaily.com/top-5-realme-11-proplus-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 Realme 11 Pro+ Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-remedying-windows-11-logins/"><u>Understanding & Remedying Windows 11 Logins</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-full-task-mastery-administrative-run-in-task-manager-on-win11/"><u>Unlocking Full Task Mastery: Administrative Run in Task Manager on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/unsupported-devices-heres-how-to-elevate-with-win11-22h2/"><u>Unsupported Devices? Here’s How to Elevate with Win11 22H2</u></a></li>
<li><a href="https://windows11.techidaily.com/what-hides-in-ftdibussys-windows-memory-integrity-disruption/"><u>What Hides in ftdibus.sys: Windows' Memory Integrity Disruption</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-tips-disabling-unwanted-mouse-speed-boosting/"><u>Win 11 Tips: Disabling Unwanted Mouse Speed Boosting</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-ready-effective-microsoft-works-installation/"><u>Win11 Ready: Effective Microsoft Works Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-powered-disk-cloning-no-add-ons-needed/"><u>Windows-Powered Disk Cloning, No Add-Ons Needed</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>