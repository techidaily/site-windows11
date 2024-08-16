---
title: A Compreenasian Approach to Fixing Winget on Windows 11
date: 2024-08-15T15:16:22.385Z
updated: 2024-08-16T15:16:22.385Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Compreenasian Approach to Fixing Winget on Windows 11
excerpt: This Article Describes A Compreenasian Approach to Fixing Winget on Windows 11
keywords: Winget for Win11,Windows 11 Installation,CI Enhanced Windows,CI Tool Update Win11,Canadian Dev Fixes,Win11 CI Tools,Windows Updates CI
thumbnail: https://thmb.techidaily.com/e9d9b71440a916b77a73a65e520d732ec704accfc7970398f4d716c0fa346167.jpg
---

## A Compreenasian Approach to Fixing Winget on Windows 11

 Winget is a command-line tool that can download and install app packages from MS Store and the apps listed in its repository. It saves a lot of time that would be otherwise wasted in searching the Microsoft Store or the web for a particular app, downloading it, and then manually installing it.

 But some users report that Winget is not working on their PC. They face a "The system cannot execute the specified program" and cannot run any commands, This post will discuss multiple methods to resolve the issue and restore Winget to its working state. Let’s begin.

## Reasons Why Winget Stops Working on Windows

 Here are the following reasons why Winget is not working on your Windows PC:

1. You are running an outdated version of the App Installer.
2. Winget servers are down, or you don’t have an active internet connection.
3. The app execution alias is not configured or inactive for Winget.
4. App Installer failed to add the PATH environment variable automatically while installing.

 Now, you know the reasons behind Winget not working issue. Try out these eight methods to resolve the issue and use your favorite package manager again.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Close and Reopen Winget in the Terminal App

 Before moving on to advanced fixes, completely close the Command Prompt or PowerShell instance you are running on the PC. You can use the Task Manager to stop an unresponsive instance of either of these command-line tools.

 After that, open Command Prompt or PowerShell with administrator privileges on your system. Type Winget and press the **Enter** key to check if Winget works now.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600114&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Mac： Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
## 2\. Check if the Winget Servers Are Down

 Winget is an online tool that needs a robust internet connection to search for a package in various repositories and then download and install them. If the Winget servers are down or inactive, it won’t be able to fetch results from repositories. So, check if Winget servers are down using [DownDetector](https://redirect.viglink.com/?format=go&jsonp=vglnk%5F168667664973511&key=eac202ea7a96cf485281d6c4ffa2069e&libId=liuggg0i0103es17000ULlmtlntd&loc=https%3A%2F%2Fwww.makeuseof.com%2Fhow-to-fix-0x8004def5-onedrive-error-code-windows-11%2F&ccpaConsent=1---&v=1&opt=true&optExText=false&out=https%3A%2F%2Fdowndetector.com%2F&ref=https%3A%2F%2Fwww.makeuseof.com%2Fauthor%2Fabhishekkumar-mishra%2F&title=9%20Ways%20to%20Fix%20the%200x8004def5%20OneDrive%20Error%20Code%20on%20Windows%2011&txt=DownDetector) or a similar website.

 You can also check if your Windows PC can connect to the internet. Simply open a web browser and access a website or run a web-based app to confirm internet connectivity. If the servers are down, you will have to wait until they come up live again to use Winget.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Perform a Complete System Shutdown

 Windows uses Fast Startup to hibernate kernel-level processes and if any of these glitch, they remain in that state after your power on the system. So, perform a complete shutdown to close and relaunch all the core services and then try to run Winget. Here’s how to do it:

1. Press **Win + R** to open the Run dialog box. Type **cmd** and press **Ctrl + Shift + Enter** keys to [open the Command Prompt with administrator privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Now, type the following command and press the Enter key: **shutdown /s /f /t 0**  
![Completely Shutdown your PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/completely-shutdown-your-pc.jpg)
3. Your system will shut down. It will take longer than a usual shutdown because Windows will close everything.
4. Power on your system and try to run Winget using the Terminal app to check if it works now.

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
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

## 6\. Manually Add the Path Environment Variable

 Ae wrongly configured Winget path can also produce errors. So, you must manually add the correct path in Environment Variables using the Advanced System Properties window. Repeat the following steps:

1. Press **Win + R** to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **sysdm.cpl ,3** in the text box and press the **Enter** key to open **Advanced System Properties**.
2. Click on the **Environment Variables** button. Click on the **Path** entry and then click on the **Edit** button.
3. Now, click on the New button and paste the following path: **%UserProfile%\\AppData\\Local\\Microsoft\\WindowsApps**  
![Manually Add the Path Environment Variable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/manually-add-the-path-environment-variable.jpg)
<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->

## 8\. Try Some Generic Windows Fixes

 If none of the methods work for you, try our generic fixes like SFC and DISM scans that find and fix the system file corruption and service Windows Image components. You must [run the SFC scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) first and allow it to find and replace the corrupt system files, if any. After that, [run the DISM scan](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) in online mode.

 After running these scans, you can use System Restore to revert the PC to a point in time when everything worked fine. Lastly, you can perform a complete system reset. You can choose the Keep my files option to preserve all your files while [factory resetting Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/).

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://youtube-blog.techidaily.com/024-approved-cozy-up-your-videos-best-winter-bgs-revealed/"><u>[New] 2024 Approved  Cozy Up Your Videos  Best Winter Bg's Revealed</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/xploring-earning-potential-an-uncomplicated-triad-technique-for-youtube-profit-analysis-for-2024/"><u>[New] Exploring Earning Potential  An Uncomplicated Triad Technique for YouTube Profit Analysis for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-in-2024-building-a-strong-visual-narrative-in-youtube-videos/"><u>[Updated] In 2024, Building a Strong Visual Narrative in YouTube Videos</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-transform-your-videos-without-youtube-with-these-top-5-alternatives/"><u>[Updated] In 2024, Transform Your Videos Without Youtube with These Top 5 Alternatives</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-insider-secrets-to-properly-tag-your-youtube-videos/"><u>2024 Approved  Insider Secrets to Properly Tag Your YouTube Videos</u></a></li>
<li><a href="https://location-fake.techidaily.com/4-methods-to-turn-off-life-360-on-xiaomi-redmi-12-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>4 Methods to Turn off Life 360 On Xiaomi Redmi 12 without Anyone Knowing | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/a-step-by-step-for-placing-antique-games-into-photos-folder/"><u>A Step-by-Step for Placing Antique Games Into Photos Folder</u></a></li>
<li><a href="https://windows11.techidaily.com/academic-excellence-with-these-top-8-study-tips-for-windows-users/"><u>Academic Excellence with These Top 8 Study Tips for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/accessing-the-internet-without-a-browser-post-setup/"><u>Accessing the Internet Without a Browser Post-Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-cpu-overload-with-wmi-service-tweaks/"><u>Addressing Cpu Overload with WMI Service Tweaks</u></a></li>
<li><a href="https://windows11.techidaily.com/automating-windows-auditory-restart-post-boot-issue/"><u>Automating Windows Auditory Restart Post-Boot Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-burnout-keeping-your-game-windows-laptop-cool/"><u>Avoiding Burnout: Keeping Your Game Windows Laptop Cool</u></a></li>
<li><a href="https://facebook.techidaily.com/1719152115012-awaiting-the-call-facebook-orders-ruling-on-prohibited-access/"><u>Awaiting the Call: Facebook Orders Ruling on Prohibited Access.</u></a></li>
<li><a href="https://windows11.techidaily.com/beginners-blueprint-to-conquering-diablo/"><u>Beginner’s Blueprint to Conquering Diablo</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-why-obs-wont-start-on-your-pc/"><u>Breaking Down Why OBS Won't Start on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-grayed-out-delete-feature-for-windows-11-pins/"><u>Breaking Grayed-Out Delete Feature for Windows 11 PINs</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-printer-usage-errors-efficiently/"><u>Bypassing Printer Usage Errors Efficiently</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-color-issues-in-legacy-bios/"><u>Clearing Up Color Issues in Legacy BIOS</u></a></li>
<li><a href="https://techtrends.techidaily.com/comparing-prices-is-hailing-an-uber-a-cheaper-alternative-to-cabs/"><u>Comparing Prices: Is Hailing an Uber a Cheaper Alternative to Cabs?</u></a></li>
<li><a href="https://windows11.techidaily.com/comparing-w10-and-w11-a-detailed-look-at-key-updates/"><u>Comparing W10 & W11: A Detailed Look at Key Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/compelling-windows-applications-for-video-transformation/"><u>Compelling Windows Applications for Video Transformation</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-tutorial-onedrive-plus-microsoft-login-on-pc/"><u>Comprehensive Tutorial: OneDrive + Microsoft Login on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-the-windows-device-abandonment-issue/"><u>Correcting the Windows Device Abandonment Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/cyber-armor-top-7-techniques-to-guard-your-os/"><u>Cyber Armor: Top 7 Techniques to Guard Your OS</u></a></li>
<li><a href="https://windows11.techidaily.com/delving-into-disparities-unveiling-the-distinctive-aspects-of-each-login-type/"><u>Delving Into Disparities: Unveiling The Distinctive Aspects of Each Login Type</u></a></li>
<li><a href="https://windows11.techidaily.com/delving-into-what-windows-11s-new-updates-signify-for-users/"><u>Delving Into What Windows 11'S New Updates Signify For Users</u></a></li>
<li><a href="https://windows11.techidaily.com/disarming-error-dism-0x800f082f-on-microsoft-os/"><u>Disarming Error: DISM 0X800F082F on Microsoft OS</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-the-divine-interface-of-windows-11-os/"><u>Discover the Divine Interface of Windows 11 OS</u></a></li>
<li><a href="https://fox-that.techidaily.com/ending-iphone-app-annoyances-a-step-by-step-guide-to-keeping-them-running-smoothly/"><u>Ending iPhone App Annoyances: A Step-by-Step Guide to Keeping Them Running Smoothly</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-frp-on-google-pixel-7a-by-drfone-android-unlock-remove-google-frp/"><u>How To Bypass FRP on Google Pixel 7a</u></a></li>
<li><a href="https://win-amazing.techidaily.com/how-to-keep-your-toshiba-satellite-drivers-current-on-a-windows-operating-system/"><u>How to Keep Your Toshiba Satellite Drivers Current on a Windows Operating System</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-iphone-8-plus-icloud-activation-lock-bypass-by-drfone-ios/"><u>In 2024, iPhone 8 Plus iCloud Activation Lock Bypass</u></a></li>
<li><a href="https://fox-direct.techidaily.com/in-2024-soft-shadows-on-smiles-introducing-motion-blur-to-faces-in-photos-with-picsart/"><u>In 2024, Soft Shadows on Smiles  Introducing Motion Blur to Faces in Photos with Picsart</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-voice-over-advantage-elevating-video-quality/"><u>In 2024, The Voice-Over Advantage  Elevating Video Quality</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/innovative-copywriting-routines-adopting-three-key-approaches-to-fb-advertising/"><u>Innovative Copywriting Routines  Adopting Three Key Approaches to FB Advertising</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/masterclass-in-selecting-prime-hdr-cameras/"><u>Masterclass in Selecting Prime HDR Cameras</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/prime-pick-simple-effective-gaming-edit-suites/"><u>Prime Pick  Simple, Effective Gaming Edit Suites</u></a></li>
<li><a href="https://win-dash.techidaily.com/seamlessly-update-your-amd-smbus-drivers-fast-and-hassle-free-solutions/"><u>Seamlessly Update Your AMD SMBus Drivers: Fast and Hassle-Free Solutions</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/simplified-strategies-for-google-voice-call-records/"><u>Simplified Strategies for Google Voice Call Records</u></a></li>
<li><a href="https://unlock-android.techidaily.com/unlocking-the-power-of-smart-lock-a-beginners-guide-for-itel-p55-users-by-drfone-android/"><u>Unlocking the Power of Smart Lock A Beginners Guide for Itel P55 Users</u></a></li>
</ul></div>
