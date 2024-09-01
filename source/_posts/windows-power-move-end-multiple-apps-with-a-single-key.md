---
title: "Windows Power Move: End Multiple Apps with a Single Key"
date: 2024-08-31T22:17:44.017Z
updated: 2024-09-01T22:17:44.017Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows Power Move: End Multiple Apps with a Single Key"
excerpt: "This Article Describes Windows Power Move: End Multiple Apps with a Single Key"
keywords: Windows Efficiency Button,Close All Apps Quickly,One-Key App Closure,Simplify App Management,Streamline Window Use,Unified App Termination,Rapid Multitasking End
thumbnail: https://thmb.techidaily.com/c4be10a970b234d5f6880acef4bdb2e4828d9b824f3ccac5078e8475f10ac115.jpg
---

## Windows Power Move: End Multiple Apps with a Single Key

 Running multiple apps simultaneously can usually affect your PC’s performance. This means you might often want to close some programs to speed up your device. But here’s the thing—closing your apps one by one can be quite tedious.

 So, how can you simplify things and close your multiple apps simultaneously on Windows? Let’s find out.

## 1\. Use the Taskbar

 The Windows taskbar displays all your active and pinned programs. This means you can easily close your active apps by scrolling to the relevant taskbar icon and clicking the “close” button.

 The good news is that you can also use the taskbar to close multiple windows of the same program. However, you won’t be able to close different apps simultaneously using the taskbar.

 Here's how to close multiple windows of the same program on the taskbar:

1. Navigate to the taskbar and locate an app that has multiple active windows.
2. Right-click on the app and select the **Close all windows** option.

![Closing multiple windows on the taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/closing-multiple-windows-on-the-taskbar.jpg)

## 2\. Use the Resource Monitor

 You probably know that you can [force close your PC programs](https://www.makeuseof.com/tag/how-to-kill-unresponsive-programs-without-the-task-manager/) using the Task Manager. But the problem is that this tool doesn’t let you close your programs simultaneously.

 Wondering if there's an alternative tool you can use? Try the Resource Monitor!

 Here are the steps for closing multiple apps simultaneously using the Resource Monitor:

1. Type **Resource Monitor** in the Start menu search bar and select the **Best match**.
2. Navigate to the **Overview** tab.
3. Check the boxes of the apps you want to close.
4. Right-click on one of the results and select the **End Process** option. This should simultaneously close all the programs you selected.

![Closing multiple apps using the Resource Monitor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/closing-multiple-apps-using-the-resource-monitor.jpg)

 Want to know the best part about using the Resource Monitor? This tool allows you to re-open multiple apps simultaneously with just a few clicks!

 Here's how to reopen your apps with the Resource Monitor:

1. Access the **Resource Monitor** by applying the previous steps.
2. Check the boxes of all the apps you want to re-open.
3. Right-click on one of the results and select **Resume Process**.

<!-- affiliate ads begin -->
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Use the Command Prompt

![Person using a Windows PC while placing it on a lap](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Person-using-a-Windows-PC-while-placing-it-on-a-lap.jpg)

 The Command Prompt can help you troubleshoot PC issues, configure some system settings, and run your Windows apps.

 Interestingly, this tool can also help you simultaneously close multiple windows of the same app. However, the Command Prompt might not be the best option if you want to close different apps simultaneously.

 Here’s how you can close multiple windows of the same app using the Command Prompt:

1. Type **Command Prompt** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as administrator**.

![Opening the Command Prompt using the Start menu search bar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/opening-the-command-prompt-using-the-start-menu-search-bar.jpg)

 Let’s say you want to close multiple File Explorer windows simultaneously. To do that, type the following command in the Command Prompt and press **Enter**:

taskkill /f /im explorer.exe

 The “taskkill /f /im” command is the one that closes the program, and the “explorer.exe” command is the name of the app. To close multiple windows of your other apps, replace the “explorer.exe” part with the relevant command.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Create a Batch Script for Closing Multiple Apps Simultaneously

![A person using a Windows device on a desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/A-person-using-a-Windows-device-on-a-desk.jpg)

<!-- affiliate ads begin -->
<a href="https://martinic.evyy.net/c/5597632/1422856/4482" target="_top" id="1422856"><img src="//a.impactradius-go.com/display-ad/4482-1422856" border="0" alt="" width="580" height="309"/></a>
<!-- affiliate ads end -->
 We’ve already discovered that the Command Prompt can only help you close multiple windows of the same app.

 But if you apply a few tricks, you can close multiple apps using some commands. However, you’d need to [create a batch script](https://www.makeuseof.com/tag/write-simple-batch-bat-file/) for that.

 Here's how you can create a batch script for closing multiple apps on Windows:

1. Press **Win + D** to access the desktop. Alternatively, check out the [various ways to access the Windows desktop](https://www.makeuseof.com/windows-quickly-access-desktop/).
2. Right-click on a blank space and select **New > Text Document**. This will create an untitled document on your desktop.

 Now, let’s say you want to close the **Snipping Tool** and the **Paint.net** app simultaneously. Here are the steps you need to follow:

1. Navigate to the desktop and double-click on the text document you’ve just created.
2. Type the following command to close the Snipping Tool:

taskkill /f /im SnippingTool.exe /T > nul

 Next, type the following command to close the Paint.net app:

taskkill /f /im paintdotnet.exe /T > nul

![Creating a Batch Script for Closing Multiple Apps Simultaneously](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/creating-a-batch-script-for-closing-multiple-apps-simultaneously.jpg)

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 From there, follow these steps:

1. Press the **File** tab in the top-left corner of the text file.
2. Select the **Save As** option.
3. Type **Close Multiple Apps Simultaneously.bat** in the **File name** box.
4. Press the **Save** button.

 Now, you can close the Snipping Tool and the Paint.net app simultaneously by following these steps:

1. Press **Win + E** to access File Explorer.
2. Select the **Desktop** option on the left.
3. Click the **Close Multiple Apps Simultaneously.bat** batch file.

![Clicking a batch script on the desktop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/clicking-a-batch-script-on-the-desktop.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
 You can add as many apps as you want to your batch script.

 And when using the batch script, ensure that it doesn’t end up closing some important apps by mistake. This means it might be worth regularly checking what’s on the script first before running it.

## 5\. Use the Close All Windows Tool

![The Close All Windows Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-close-all-windows-tool.jpg)

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
 You can also quickly close your multiple active apps using a third-party program like the [Close All Windows tool](https://www.softpedia.com/get/System/System-Miscellaneous/AA-Close-All-Windows.shtml). The tool is lightweight, which means it won’t take up much of your disk space.

 This app works almost like the Windows built-in Resource Monitor. However, it comes with a basic and easy-to-understand interface. When you open the tool, it immediately displays all your active apps. All you need to do is tick the relevant boxes and then click the **OK** button to close those apps.

 The tool displays all your apps and places them under a specific category. For example, it displays all your Google Chrome windows under the Google Chrome category.

 To select all the apps on the screen, press **Ctrl + A** or navigate to the **Command** tab and click **Select All**. And if you want to uncheck all the apps, press **Ctrl + D** or click the **Deselect All** option from the **Command** tab.

 You can customize the Close All Windows tool by clicking the **View** tab and ticking the relevant boxes. And if the tool seems a bit too complicated to use, then you can navigate to the **Help** tab to get some assistance.

**Download**: Close All Windows for [Windows](https://www.softpedia.com/get/System/System-Miscellaneous/AA-Close-All-Windows.shtml) (Free, subscription available)

## Close Your Multiple Apps Simultaneously With Just a Few Clicks

 It’s always frustrating when your Windows device suddenly becomes slow or buggy. In most cases, such issues are caused by running tons of apps simultaneously.

 Want a quick way to speed up your device? Close your multiple active programs simultaneously using the tips we’ve covered. And if you end up closing some apps by mistake, you can apply some quick tricks to restore them again.


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
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-tailored-content-personalizing-facebook-ad-videos-effectively/"><u>[New] 2024 Approved  Tailored Content  Personalizing Facebook Ad Videos Effectively</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-top-5-pc-emulators-bringing-ps1-to-life/"><u>[New] 2024 Approved  Top 5 PC Emulators Bringing PS1 to Life</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-deciphering-past-visual-content-inverse-queries-and-fb-techniques/"><u>[New] In 2024, Deciphering Past Visual Content  Inverse Queries and FB Techniques</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-pro-audio-recordings-the-11-best-tools-for-live-events/"><u>[New] In 2024, Pro Audio Recordings  The 11 Best Tools for Live Events</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-mitigating-high-bitrate-in-obs-outputs/"><u>[New] Mitigating High-Bitrate in OBS Outputs</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-top-6-android-apps-for-immersive-music-videos/"><u>[New] Top 6 Android Apps for Immersive Music Videos</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-2024-approved-which-pro-stream-software-reigns-supreme-vmix-vs-wirecast/"><u>[Updated] 2024 Approved  Which Pro-Stream Software Reigns Supreme? VMix Vs. Wirecast</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-to-customizing-windows-11-default-apps/"><u>Essential Guide to Customizing Windows 11 Default Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-filenames-5-windows-utilities-for-date-manipulation/"><u>Fix Filenames: 5 Windows Utilities for Date Manipulation</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-absent-mfc71udll-steps-for-windows-users/"><u>Fixing Absent Mfc71u.dll: Steps for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-video-playback-issues-with-error-0xc10100bf/"><u>Fixing Video Playback Issues with Error 0XC10100BF</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-windows-components-administration-tool/"><u>Guide to Windows Components Administration Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/has-windows-subsystem-shifted-linux-desktops/"><u>Has Windows Subsystem Shifted Linux Desktops?</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-bypass-icloud-by-checkra1n-even-on-iphone-14-if-youve-tried-everything-by-drfone-ios/"><u>How To Bypass iCloud By Checkra1n Even On iPhone 14 If Youve Tried Everything</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-gps-location-on-apple-iphone-se-easily-and-safely-drfone-by-drfone-virtual-ios/"><u>How to Change GPS Location on Apple iPhone SE Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-change-lock-screen-wallpaper-on-oppo-reno-10-pro-5g-by-drfone-android/"><u>How to Change Lock Screen Wallpaper on Oppo Reno 10 Pro 5G</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-android-app-not-installed-error-on-meizu-21-pro-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android App Not Installed Error on Meizu 21 Pro Quickly? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-windows-activation-error-0x803f700f/"><u>How to Fix the Windows Activation Error 0X803F700F</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-swiftly-overcome-directdraw-errors-in-win1011-environments/"><u>How to Swiftly Overcome DirectDraw Errors in Win10/11 Environments</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-your-iphone-15-passcode-4-easy-methods-with-or-without-itunes-by-drfone-ios/"><u>In 2024, How to Unlock Your iPhone 15 Passcode 4 Easy Methods (With or Without iTunes)</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-inside-the-world-of-kinemaster-a-deeper-look-at-gaming/"><u>In 2024, Inside the World of KineMaster  A Deeper Look at Gaming</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-prime-prospects-the-hottest-google-cardboard-vr-gaming-titles/"><u>In 2024, Prime Prospects  The Hottest Google Cardboard VR Gaming Titles</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/in-depth-analysis-by-tom-the-hardware-guide/"><u>In-Depth Analysis by Tom - The Hardware Guide</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/master-incognito-mode-how-to-stay-anonymous-across-different-browsers-like-chrome-edge-firefox-safari-and-opera/"><u>Master Incognito Mode: How to Stay Anonymous Across Different Browsers Like Chrome, Edge, FireFox, Safari & Opera</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-winscombsvr-crashes-in-windows/"><u>Navigating Through WinScombSvr Crashes in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/optimal-pc-protection-activating-tpm-and-secure-boot-in-win-11/"><u>Optimal PC Protection: Activating TPM & Secure Boot in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-security-updating-user-passwords-on-win-11/"><u>Optimizing Security: Updating User Passwords on Win 11</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/purchase-your-own-bitraser-the-ultimate-disk-wipe-tool/"><u>Purchase Your Own BitRaser: The Ultimate Disk Wipe Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-instant-addition-problems-with-windows-onedrive-a-compreenhensive-guide/"><u>Resolving Instant Addition Problems with Windows OneDrive - A Compreenhensive Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/secrets-for-locating-vanished-registry-management-utility/"><u>Secrets for Locating Vanished Registry Management Utility</u></a></li>
<li><a href="https://windows11.techidaily.com/simplified-steps-to-alter-your-cursors-look/"><u>Simplified Steps to Alter Your Cursor's Look</u></a></li>
<li><a href="https://win-forum.techidaily.com/social-giants-unveiled-how-to-excel-on-facebook-twitter-instagram-and-youtube/"><u>Social Giants Unveiled: How to Excel on Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-inability-to-run-os-disk-organizer/"><u>Tackling Inability to Run OS Disk Organizer</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-pubg-save-settings-breakdown-on-win-oses/"><u>Tackling PUBG Save Settings Breakdown on Win OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshoot-windows-not-recognizing-an-interface/"><u>Troubleshoot Windows Not Recognizing an Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-upgraded-widget-choice-interface-in-win11/"><u>Unlocking Upgraded Widget Choice Interface in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11-with-non-admin-steps/"><u>Unlocking Windows 11 With Non-Admin Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secrets-of-fax-cover-page-editing-in-win11/"><u>Unveiling the Secrets of Fax Cover Page Editing in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/your-guide-to-next-gen-computing-at-ifa-2023/"><u>Your Guide to Next-Gen Computing at IFA 2023</u></a></li>
</ul></div>
