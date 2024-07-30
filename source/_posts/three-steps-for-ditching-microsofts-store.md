---
title: Three Steps for Ditching Microsoft's Store
date: 2024-07-29T04:22:33.948Z
updated: 2024-07-30T04:22:33.948Z
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

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
## How to Uninstall Microsoft Store App From Windows 11

 You can remove the Microsoft Store app from Windows 11 using the winget tool and run it using the command prompt. In addition, you can use the PowerShell cmdlet to remove the Microsoft Store application package from your system or use a batch file.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. Using PowerShell

 Before winget was officially integrated into Windows 10 and 11, there was a method to [remove the Microsoft Store app using PowerShell](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) . The method still works and all you need to do is list the package name and then use the**Remove-AppxPackage** cmdlet to uninstall the Microsoft Store app from your system. Make sure to run PowerShell with elevated permissions.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
### 3\. Using a Batch File

 If you want to save the hassle of typing commands every time you want to uninstall the Microsoft Store app, you can use a batch file. It will help you to remove Microsoft Store app from your system in a couple of clicks whenever the normal troubleshooting methods don’t work for you. Repeat the following steps:

1. Press**Win + D** to switch to the Desktop. Right-click on the Desktop and select the**New > Text Document** option.
2. Open the newly created text document file on the desktop. A Notepad window will pop up. Paste the following text in it:  
@echo off winget uninstall "Microsoft Store" exit
3. Now, press**Ctrl + Shift + S** to open the "Save as" window. Name the batch file as**UninstallStore.bat** and keep the**Save as** type option as**All files** .  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075475/7443" target="_top" id="2075475"><img src="//a.impactradius-go.com/display-ad/7443-2075475" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Uninstall Microsoft Store App using batch file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-batch-file.jpg)
4. Click on the**Save** button. Close the Notepad window.
5. Press**Win + D** to switch to the desktop again. Right-click on the batch file and select the**Run as administrator** option from the context menu.
6. A command prompt window will open, run the Microsoft Store app uninstallation command, and close automatically. You don’t need to interact with the window.
7. Open the Start menu and search for Microsoft Store. You won’t find any matching app on your system.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://some-techniques.techidaily.com/new-from-pixels-to-spirit-nurturing-memories-through-live-photo-to-video-conversion/"><u>[New] From Pixels to Spirit  Nurturing Memories Through Live Photo to Video Conversion</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/n-2024-premium-online-platforms-for-video-intro-creation/"><u>[New] In 2024, Premium Online Platforms for Video Intro Creation</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-enhance-call-clarity-choose-from-the-best-10-free-recorders-for-2024/"><u>[Updated] Enhance Call Clarity  Choose From the Best 10 Free Recorders for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-scrutinizing-the-economics-behind-short-video-earnings/"><u>[Updated] Scrutinizing the Economics Behind Short Video Earnings</u></a></li>
<li><a href="https://windows11.techidaily.com/9-steps-to-resolve-windows-hello-fingerprint-lockout/"><u>9 Steps to Resolve Windows Hello Fingerprint Lockout</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerate-vm-performance-on-windows-6-precise-tips-and-tricks/"><u>Accelerate VM Performance on Windows: 6 Precise Tips & Tricks</u></a></li>
<li><a href="https://extra-resources.techidaily.com/ace-your-films-with-these-top-15-gopro-video-luts-for-2024/"><u>Ace Your Films with These Top 15 GoPro Video LUTs for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-the-crashes-resource-monitor-on-windows-11/"><u>Addressing the Crashes: Resource Monitor on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/altering-failed-logon-wait-duration-settings-in-windows/"><u>Altering Failed Logon Wait Duration Settings in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-your-productivity-with-w11-desktop-organization/"><u>Boost Your Productivity with W11 Desktop Organization</u></a></li>
<li><a href="https://windows11.techidaily.com/ceasing-chrome-notifications-on-windows-desktop/"><u>Ceasing Chrome Notifications on Windows Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-tips-to-access-pcs-health-metrics/"><u>Decoding Tips to Access PC's Health Metrics</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminate-troubleshooting-roadblocks-for-compatibility-issues/"><u>Eliminate Troubleshooting Roadblocks for Compatibility Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/empowering-windows-users-introducing-a-customized-run-helper-app/"><u>Empowering Windows Users: Introducing a Customized Run Helper App</u></a></li>
<li><a href="https://windows11.techidaily.com/fasten-up-your-windows-devices-with-top-fixes-for-slow-web-linkage/"><u>Fasten Up Your Windows Devices with Top Fixes for Slow Web Linkage</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-an-uninstall-shortcut-to-the-context-menu-in-windows-1110/"><u>How to Add an Uninstall Shortcut to the Context Menu in Windows 11/10</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-rectify-non-existent-lock-screen-countdown/"><u>How to Rectify Non-Existent Lock Screen Countdown</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-repair-your-broken-wireless-keyboard-for-windows-users-step-by-step-solutions/"><u>How to Repair Your Broken Wireless Keyboard for Windows Users - Step by Step Solutions</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-best-value-for-money-8-ace-free-srt-apps-reviewed/"><u>In 2024, Best Value for Money  8 Ace Free SRT Apps Reviewed</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-boosting-video-conference-quality-a-guide-to-using-zoom-and-skype/"><u>In 2024, Boosting Video Conference Quality  A Guide to Using ZOOM & SKYPE</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-lock-your-samsung-galaxy-a14-4g-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>In 2024, Lock Your Samsung Galaxy A14 4G Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
<li><a href="https://extra-hints.techidaily.com/leading-speedy-visualizer-in-windows/"><u>Leading Speedy Visualizer in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-ais-pitfalls-the-risks-of-chatbots-in-windows-keys/"><u>Navigating AI's Pitfalls: The Risks of Chatbots in Windows Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-pc-performance-top-6-monitoring-apps-recommended-for-win/"><u>Optimize PC Performance: Top 6 Monitoring Apps Recommended for Win</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-win-strategies-boosting-frames-in-cs-go/"><u>Quick Win Strategies - Boosting Frames in CS GO</u></a></li>
<li><a href="https://windows11.techidaily.com/remedial-tactics-for-loading-errors-in-discord-software/"><u>Remedial Tactics for Loading Errors in Discord Software</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-device-disconnection-problems-for-windows-users-with-virtualbox/"><u>Resolving Device Disconnection Problems for Windows Users with VirtualBox</u></a></li>
<li><a href="https://windows11.techidaily.com/stopping-google-chrome-alerts-tips-for-windows/"><u>Stopping Google Chrome Alerts: Tips for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-controlling-file-compression-in-windows-11/"><u>Strategies for Controlling File Compression in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-complete-list-of-windows-11s-narrator-keyboard-shortcuts/"><u>The Complete List of Windows 11'S Narrator Keyboard Shortcuts</u></a></li>
<li><a href="https://windows11.techidaily.com/the-phasing-out-of-microsofts-windows-xp-7-and-81-lifeline/"><u>The Phasing Out of Microsoft's Windows XP, 7 & 8.1 Lifeline</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-power-of-shortcuts-for-app-size-adjustment-on-windows-11/"><u>Unlocking the Power of Shortcuts for App Size Adjustment on Windows 11</u></a></li>
</ul></div>
