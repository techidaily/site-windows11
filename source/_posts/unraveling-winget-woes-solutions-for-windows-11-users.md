---
title: "Unraveling Winget Woes: Solutions for Windows 11 Users"
date: 2024-10-14T21:17:33.656Z
updated: 2024-10-18T16:08:28.944Z
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
<a href="https://appsumo.8odi.net/c/5597632/2037334/7443" target="_top" id="2037334">
  <img src="//a.impactradius-go.com/display-ad/7443-2037334" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037334/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2027176/19272" target="_top" id="2027176">
  <img src="//a.impactradius-go.com/display-ad/19272-2027176" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2027176/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Power on your system and try to run Winget using the Terminal app to check if it works now.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144282/7443" target="_top" id="2144282">
  <img src="//a.impactradius-go.com/display-ad/7443-2144282" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144282/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Update App Installer

 Winget is a part of Windows 10 and 11 now and is shipped to PCs using the App Installer application. If you haven’t updated the App Installer in a while, you can face issues in running Winget and managing packages. Winget is included only in version 1.11.11451 or higher of the App Installer. If you have a version older than that, you cannot use Winget from the terminal.

![Update App Installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/update-app-installer.jpg)

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
<a href="https://ursime.pxf.io/c/5597632/2136536/16384" target="_top" id="2136536">
  <img src="//a.impactradius-go.com/display-ad/16384-2136536" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ursime.pxf.io/i/5597632/2136536/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Manually Add the Path Environment Variable

 Ae wrongly configured Winget path can also produce errors. So, you must manually add the correct path in Environment Variables using the Advanced System Properties window. Repeat the following steps:

1. Press **Win + R** to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **sysdm.cpl ,3** in the text box and press the **Enter** key to open **Advanced System Properties**.
2. Click on the **Environment Variables** button. Click on the **Path** entry and then click on the **Edit** button.
3. Now, click on the New button and paste the following path: **%UserProfile%\\AppData\\Local\\Microsoft\\WindowsApps**  
![Manually Add the Path Environment Variable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/manually-add-the-path-environment-variable.jpg)
4. Click on the **OK** button. Restart your PC.
5. Open the Terminal app and check if Winget works or not.

## 7\. Re-register Winget Using PowerShell

 If Winget isn’t working on your PC, you can re-register it using PowerShell. Since it is a part of the App Installer which is a system app, it is possible to re-register it. Repeat the following steps:

1. Press **Win + R** to open the Run dialog box. Type **PowerShell** and press the **Ctrl + Shift + Enter** keys at once.
2. The PowerShell window will launch with admin rights. Paste the following code and press the **Enter** key to execute it:  
`Add-AppxPackage -DisableDevelopmentMode -Register "C:\Program Files\WindowsApps\Microsoft.Winget.Source_2021.718.1322.843_neutral__8wekyb3d8bbwe\AppXManifest.xml" -Verbose`
3. You won’t see any confirmation message after the command executes successfully. Close the PowerShell window and restart your PC.  
![Re-register Winget Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/re-register-winget-using-powershell.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136619/26400" target="_top" id="2136619">
  <img src="//a.impactradius-go.com/display-ad/26400-2136619" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136619/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 8\. Try Some Generic Windows Fixes

 If none of the methods work for you, try our generic fixes like SFC and DISM scans that find and fix the system file corruption and service Windows Image components. You must [run the SFC scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) first and allow it to find and replace the corrupt system files, if any. After that, [run the DISM scan](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) in online mode.

 After running these scans, you can use System Restore to revert the PC to a point in time when everything worked fine. Lastly, you can perform a complete system reset. You can choose the Keep my files option to preserve all your files while [factory resetting Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/).

## Make Winget Functional Again

 Winget is a fantastic package manager that helps you control and manage app packages from the terminal. Ensure robust internet connectivity and check if the app execution alias is active for Winget. Manually reconfigure the PATH for Winget and re-register the App Installer using PowerShell. If you want a GUI version of Winget, you can try Winstall which helps you batch-install apps.

 But some users report that Winget is not working on their PC. They face a "The system cannot execute the specified program" and cannot run any commands, This post will discuss multiple methods to resolve the issue and restore Winget to its working state. Let’s begin.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-access.techidaily.com/new-in-2024-m1-pro-vs-m1-max-identifying-core-differences/"><u>[New] In 2024, M1 Pro Vs. M1 Max Identifying Core Differences</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-building-brands-on-video-a-guide-to-partnering-with-popular-youtubers/"><u>[Updated] Building Brands on Video A Guide to Partnering with Popular YouTubers</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-captivating-cuts-editor-apps-that-liberate-android-users-for-2024/"><u>[Updated] Captivating Cuts Editor Apps That Liberate Android Users for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-top-conversion-suite-for-mp4fb-sharing-for-2024/"><u>[Updated] Top Conversion Suite for MP4/FB Sharing for 2024</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/forgot-locked-apple-iphone-14-pro-password-learn-the-best-methods-to-unlock-drfone-by-drfone-ios/"><u>Forgot Locked Apple iPhone 14 Pro Password? Learn the Best Methods To Unlock | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/from-standard-screen-to-vr-world-smartphone-conversion-guide/"><u>From Standard Screen to VR World Smartphone Conversion Guide</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-can-you-transfer-files-from-zte-axon-40-lite-to-iphone-151413-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How Can You Transfer Files From ZTE Axon 40 Lite To iPhone 15/14/13? | Dr.fone</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-mimicking-masterpieces-crafting-successful-parodies/"><u>In 2024, Mimicking Masterpieces Crafting Successful Parodies</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-remove-the-lock-screen-fingerprint-of-your-samsung-galaxy-a15-5g-by-drfone-android/"><u>In 2024, Remove the Lock Screen Fingerprint Of Your Samsung Galaxy A15 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-restarting-non-starting-windows-drivers/"><u>Mastering the Art of Restarting Non-Starting Windows Drivers</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-common-pin-hurdles-in-modern-windows-os-win10win11/"><u>Navigating Common PIN Hurdles in Modern Windows OS (Win10/Win11)</u></a></li>
<li><a href="https://windows11.techidaily.com/regaining-run-windows-past-execution/"><u>Regaining Run Window's Past Execution</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-chrome-setup-in-windows-11-systems/"><u>Seamless Chrome Setup in Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/speedy-access-to-repair-solutions-customizing-hotkeys-for-win-1011/"><u>Speedy Access to Repair Solutions: Customizing Hotkeys for Win 10/11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/turning-social-media-sounds-into-functional-phone-alarms-for-2024/"><u>Turning Social Media Sounds Into Functional Phone Alarms for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-of-error-code-9999-in-win-based-audacity/"><u>Unraveling the Mystery of Error Code 9999 in Win-Based Audacity</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-of-windows-11s-elevation-failures/"><u>Unraveling the Mystery of Windows 11’S Elevation Failures</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-end-task-control-capabilities-in-windows-11-ui-environment/"><u>Unveiling End Task Control Capabilities in Windows 11 UI Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-watchlist-7-tasks-to-inspect-for-hidden-viruses/"><u>Windows Watchlist: 7 Tasks to Inspect for Hidden Viruses</u></a></li>
</ul></div>

