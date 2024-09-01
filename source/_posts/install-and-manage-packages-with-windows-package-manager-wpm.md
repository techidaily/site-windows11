---
title: Install and Manage Packages with Windows Package Manager (WPM)
date: 2024-08-31T22:10:12.142Z
updated: 2024-09-01T22:10:12.142Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Install and Manage Packages with Windows Package Manager (WPM)
excerpt: This Article Describes Install and Manage Packages with Windows Package Manager (WPM)
keywords: Windows Package Management,WPM Installation Guide,Packages Management on Win,WPM Dependency Resolution,Windows WPM Command Line,Efficient Software Updates,Package Manager Automation
thumbnail: https://thmb.techidaily.com/e9c990e25117479e90a6a7012f47011623d3e85d5155cf7861b563822cc331cb.jpg
---

## Install and Manage Packages with Windows Package Manager (WPM)

 As Windows has developed over the years, we’ve seen Microsoft introduce some of Linux’s functionality into the Windows ecosystem. In addition to Windows 10 and 11 supporting a Linux subsystem through WSL 2, they also feature a package manager called the Windows Package Manager (or winget for short).

 So what exactly is the Windows Package Manager, and how do you use it? Read on as we answer all of your burning questions below.

## What Is a Package Manager?

 All modern apps and any projects that you build will utilize existing frameworks, libraries, and tools. If you’re building a simple React app, you’re going to require Node.js, ReactJS, and other libraries or tools for your project to function correctly. The underlying third-party software that essentially helps your project function is called dependencies.

 As you can imagine, managing the installation and updation of multiple dependencies within a project can become quite frustrating. You also need to make sure that your system is compatible with third-party software. If you were to integrate and update each third-party software manually, you’d be wasting a good chunk of your valuable time managing the software dependencies.

 To solve this problem (among others), developers came up with the ingenious idea of a package manager—a single tool that can manage all your project dependencies. Package managers typically perform several essential features such as:

* Finding the correct source files for your platform.
* Ensuring source files are free of malware and other security vulnerabilities.
* Integrating dependencies into your project.
* Allowing seamless installation, updation, and removal of software dependencies.

 Package managers also have a vast catalog of tools you can choose from and install with just a single command on the terminal.

Some examples of popular package managers include:

* Homebrew.
* Node Package Manager (NPM).
* Yarn.
* Advanced Packaging Tool (APT).

## What Is the Windows Package Manager?

 The Windows Package Manager, or winget as it is commonly referred to, is Microsoft’s version of a Linux-style package manager. Winget was released in 2020 as an open-source command-line utility package manager and contains a wide range of available applications for users to install from. Like other widely used package managers, Microsoft has made sure that the Windows Package Manager is free and available on GitHub.

![remove reinstall microsoft store windows 11](https://thmb.techidaily.com/99bb08ac4320921b1ffab3e5a5166b4c117aac2cf8ab3a2d0b2277eb6b26d486.jpg)

 By using the Windows Package Manager, you can easily install, update, and delete applications with just a single command in the terminal. Say goodbye to the days of downloading setup files and manually installing each application.

 Winget utilizes a YAML package manifest format that makes it easy to understand and configure. Developers typically use the YAML manifest format to bundle their applications to be compatible with the Windows Package Manager.

 Previously, Windows users had to rely on Chocolatey—a third-party package manager specialized for Windows OS. Chocolatey is quite powerful and widely adopted by the larger Windows fraternity. On the other hand, most Windows users are not familiar or comfortable with the Windows Package Manager yet; we hope this guide will help change that.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
## How to Set Up Windows Package Manager on Windows 11

 The Windows Package Manager does not come pre-installed on Windows, so you’ll have to download it manually. Fortunately, the installation process is straightforward and shouldn’t pose any hurdles.

 Microsoft requires your Windows system to run Windows 10 1709 or later to use winget. You will also have to[log in using your Microsoft Account](https://www.makeuseof.com/windows-switch-local-account-to-microsoft-account/) and ensure you’re logged in on the Microsoft Store app as well.

 There are two main ways of installing the Windows Package Manager on Windows 11.

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### How to Install Winget Using the Microsoft Store

 The easiest way to install the Windows Package Manager is through the Microsoft Store. You can download the Windows Package Manager through Microsoft’s official App Installer to do so:

1. Launch the**Microsoft Store** using the**Start menu** .
2. Search for**App Installer** and select the best match.  
![app installer win11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-installer.jpg)
3. Click on the**Install** button if you see it. Otherwise,**App Installer** already exists on your PC, and you will just have to make sure it’s updated.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851655&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
### How to Install Winget Through PowerShell

 If you’re having issues in the Microsoft Store, you should consider installing winget using Windows PowerShell. Once you’ve connected to the internet, follow the below steps:

1. From the**Start** menu, search for**PowerShell** , and select**Run as administrator** .
2. In the command line, paste the below command and press**Enter**  
`Invoke-WebRequest -Uri https://aka.ms/winget -OutFile winget.zip; Expand-Archive winget.zip -DestinationPath $Env:ProgramFiles\WindowsPowerShell\Modules\`
3. Once the installation is completed, type the following command and press**Enter** to verify your installation.

## How to Use Winget on Windows 11

 Now that you’ve set up winget, you’ll have to learn how to use commands associated with the winget tool, including downloading, config configuring, and viewing installed applications.

### 1\. How to Download New Applications

 There’s a vast range of available applications within winget, and you can download apps such as Google Chrome, 7-Zip, etc.

To download an application using winget, use the following command:

`winget install <APP_NAME>`

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->
### 2\. How to Browse for Applications

 If you’re looking for a new app to install but don’t know how to browse the available apps, you can use the search feature of winget. One method is to use the search command of winget within the command line. Enter a search query with the below command, and you’ll get a list of available apps that satisfy your search criteria.

![winget search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/winget-search.jpg)

For example, to search for zipping programs, you can type:

`winget search zip`

 Alternatively, you can use a[third-party tool](https://winstall.app/) that provides an easy-to-use user interface for winget.

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 3\. How to View Installed Applications

 You can view applications that have been installed on your PC through:

`winget list`

### 4\. How to View Application Details

![winget show](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/winget-show.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
 To look into the installation details and software version of a specific app, you can use the following command:

`winget show <APP_NAME>`

## Are Package Managers Worth the Hassle on Windows?

 Winget is incredible at installing applications on your Windows 11 PC. You no longer need to hunt for malware-free download links on the internet; simply open up a terminal and download the application you need via winget.


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
<li><a href="https://fox-info.techidaily.com/new-in-2024-ideal-chipset-selection-for-uhd-rendering/"><u>[New] In 2024, Ideal Chipset Selection for UHD Rendering</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-navigating-the-seas-of-saving-facebook-gifs-on-various-tech-platforms/"><u>[New] Navigating the Seas of Saving Facebook GIFs on Various Tech Platforms</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-uncomplicatedscreensave-free-recording-software/"><u>[New] UncomplicatedScreenSave  Free Recording Software</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-how-to-create-a-channel-that-dominates-the-business-world/"><u>[Updated] In 2024, How to Create a Channel that Dominates the Business World</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-in-depth-look-10-must-have-terraria-mods/"><u>[Updated] In 2024, In-Depth Look  10 Must-Have Terraria Mods</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-top-30-webcams-elevating-audio-quality/"><u>[Updated] In 2024, Top 30 Webcams Elevating Audio Quality</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-simplified-guide-integrating-snapchat-with-your-mac/"><u>2024 Approved  Simplified Guide  Integrating Snapchat with Your Mac</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/crafting-effective-in-stream-ad-campaigns-on-facebook-a-comprehensive-guide/"><u>Crafting Effective In-Stream Ad Campaigns on Facebook  A Comprehensive Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-taskbar-upgrades-in-windows-11/"><u>Exploring Taskbar Upgrades in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/future-proofing-windows-how-to-leverage-vivetool-advantages/"><u>Future-Proofing Windows: How to Leverage ViVeTool Advantages</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-principles-to-consider-in-a-new-os-rollout/"><u>Guiding Principles to Consider in a New OS Rollout</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-modify-the-visual-cues-in-windows-11-search/"><u>How to Modify the Visual Cues in Windows 11 Search</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-prevent-and-cure-system-settings-failures-in-win11/"><u>How to Prevent and Cure System Settings Failures in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-rectify-shaky-cursor-on-modern-windows/"><u>How to Rectify Shaky Cursor on Modern Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-resurrect-a-freeze-fixing-error-code-x-in-windows-11/"><u>How to Resurrect a Freeze: Fixing Error Code X in Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-with-location-spoofer-on-apple-iphone-7-drfone-by-drfone-virtual-ios/"><u>How To Simulate GPS Movement With Location Spoofer On Apple iPhone 7? | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-essential-tips-and-tricks-for-powerdirector-24-mastery/"><u>In 2024, Essential Tips and Tricks for PowerDirector '24 Mastery</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-mastering-lock-screen-settings-how-to-enable-and-disable-on-vivo-y17s-by-drfone-android/"><u>In 2024, Mastering Lock Screen Settings How to Enable and Disable on Vivo Y17s</u></a></li>
<li><a href="https://windows11.techidaily.com/insider-secrets-the-edge-of-windows-for-gamers/"><u>Insider Secrets: The Edge of Windows for Gamers</u></a></li>
<li><a href="https://windows11.techidaily.com/insights-on-windows-portable-application-formats/"><u>Insights on Windows Portable Application Formats</u></a></li>
<li><a href="https://windows11.techidaily.com/keeping-taskmanager-above-all-windows/"><u>Keeping TaskManager Above All Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-charging-notifications-in-modern-windows-os/"><u>Leveraging Charging Notifications in Modern Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/masterclass-guide-to-overcoming-opengl-glitch-3/"><u>Masterclass Guide to Overcoming OpenGL Glitch #3</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-nat-type-adjustment-in-modern-windows-oses/"><u>Mastering NAT Type Adjustment in Modern Windows OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-system-debugging-locating-and-resolving-error-codes-via-windows-command-prompt/"><u>Mastering System Debugging: Locating & Resolving Error Codes via Windows Command Prompt</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-batch-conversion-heic-to-jpeg-in-windows-11/"><u>Mastering the Art of Batch Conversion: Heic to JPEG in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-fixing-install-failed-on-windows-1011/"><u>Mastering the Art of Fixing Install Failed on Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11-keys-best-offers/"><u>Mastering Windows 11 Keys: Best Offers</u></a></li>
<li><a href="https://windows11.techidaily.com/methodology-purging-onedrive-icon-in-file-explorer/"><u>Methodology: Purging OneDrive Icon in File Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-windows-arp-cache-world-and-purge-processes-129-chars-exceeds-limit-adjusted-to-fit-better-clearing-windows-arp/"><u>Navigating the Windows ARP Cache World and Purge Processes (129 Chars, Exceeds Limit, Adjusted to Fit Better: Clearing Windows ARP</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-errors-fixing-the-termination-denial/"><u>Navigating Windows Errors - Fixing the Termination Denial</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-backspace-failures-in-windows-environments/"><u>Overcoming Backspace Failures in Windows Environments</u></a></li>
<li><a href="https://windows11.techidaily.com/preserving-your-preferred-windows-volume-mixer-state/"><u>Preserving Your Preferred Windows Volume Mixer State</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-unsolicited-terminal-window-flashes/"><u>Preventing Unsolicited Terminal Window Flashes</u></a></li>
<li><a href="https://windows11.techidaily.com/re-initiate-audio-playback-on-frozen-systems/"><u>Re-Initiate Audio Playback on Frozen Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/reducing-unrealcefsubprocess-power-footprint-on-windows-os/"><u>Reducing UnrealCEFSubprocess Power Footprint on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/reigniting-your-wifi-detection-capabilities-in-win11/"><u>Reigniting Your Wifi Detection Capabilities in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/revive-your-pc-navigating-through-windows-8-options/"><u>Revive Your PC: Navigating Through Windows' 8 Options</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-overcoming-steam-permissions-in-windows-11/"><u>Solutions for Overcoming Steam Permissions in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/solve-your-windows-dilemma-help-strategies-revealed/"><u>Solve Your Windows Dilemma: Help Strategies Revealed!</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-for-removing-isdonedll-from-w11-pc/"><u>Step-By-Step Guide for Removing ISDone.dll From W11 PC</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-keeping-calculator-visible-at-top/"><u>Strategies for Keeping Calculator Visible at Top</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-knowledge-of-command-line-nicknames/"><u>The Essential Knowledge of Command Line Nicknames</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-access-control-corruption-resolution/"><u>Troubleshooting Windows: Access Control Corruption Resolution</u></a></li>
<li><a href="https://windows11.techidaily.com/unchaining-the-microsoft-store-on-windows-11-devices/"><u>Unchaining the Microsoft Store on Windows 11 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-windows-arp-caches-deletion-guide/"><u>Understanding Windows ARP Caches: Deletion Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-cause-of-winmedia-error/"><u>Unveiling the Cause of WinMedia Error</u></a></li>
<li><a href="https://change-location.techidaily.com/what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-xiaomi-redmi-note-12-pro-4g-drfone-by-drfone-virtual-android/"><u>What is the best Pokemon for pokemon pvp ranking On Xiaomi Redmi Note 12 Pro 4G? | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/winning-the-battle-against-recurrent-windows-explorer-failures-tips-and-tricks/"><u>Winning the Battle Against Recurrent Windows Explorer Failures: Tips & Tricks</u></a></li>
</ul></div>
