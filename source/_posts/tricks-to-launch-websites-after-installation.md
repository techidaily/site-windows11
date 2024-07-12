---
title: Tricks to Launch Websites After Installation
date: 2024-07-11T21:30:16.104Z
updated: 2024-07-12T21:30:16.104Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tricks to Launch Websites After Installation
excerpt: This Article Describes Tricks to Launch Websites After Installation
keywords: Post-Launch Site Setup,Website Launch Tips,Site Deployment Strategies,Initial Web Launching,Online Platform Initiation,Website Activation Steps,Launch Website Methods
thumbnail: https://thmb.techidaily.com/9d8448293885018e42ea0c2c618da231bf75f85bd2fb228b8b71882f24dcc32a.jpg
---

## Tricks to Launch Websites After Installation

 Vowed to not touch Edge for as long as you live? You might feel cornered after installing a fresh copy of Windows. With only Edge installed by default, most users just use Edge to download another browser. While this approach works fine, you can't use it if you've uninstalled Edge from your computer.

 Fortunately, installing a browser without another browser is possible on Windows. Start by selecting the browser you want to install because in most cases, you'll only be able to download the most popular browsers. We explain how you can download a browser without using a browser in this guide.

## 1\. Use the Microsoft Store

 Before you move forward with this method, note that Google Chrome is unavailable on the Microsoft Store. If you want to install Chrome, skip to the next method.

 Fortunately, Windows 10 and 11 come with a preinstalled Microsoft Store app. The app lets you download the most popular apps, including web browsers like Firefox, Opera, and Brave.

 To install a browser, start by launching the Microsoft Store. Search for Microsoft Store in the Start Menu and search for the browser you want to install. Select the browser and click**Install** . Wait for the browser to finish installing.

 When installing a browser, be sure to check the publisher to avoid installing fake apps.

## 2\. How to Install Browsers Using Commands

 You can use PowerShell or Command Prompt to download a browser using a command as well. For simplicity, we'll use PowerShell throughout this guide. You don't need to know any commands or scripting to use this method. Just follow the steps illustrated below.

 First, let's talk about ways you can use PowerShell or Command Prompt to install a browser. There are two utilities that enable you to download files:

* **Winget:** [Winget](https://www.makeuseof.com/how-to-download-install-and-use-the-windows-package-manager-winget/) is the Windows package manager available on the Windows 10 v1809 and later.
* **Curl:** The Curl command allows you to make web requests and download files and is available on all versions after the April 2018 update (Windows 10 v1803).
* **Chocolatey:** Chocolatey is a third-party package manager that allows installing and uninstalling applications.

Let's talk about how you can use these to download a browser.

### Use Winget

 If you're running Windows 10 v1809 or later, Winget is one of the easiest ways to download a browser without a browser. Start by launching PowerShell by searching for it in the Start Menu. Then, execute one of the following commands based on the browser you want to download:

`winget install --id=Google.Chromewinget install --id=Mozilla.Firefoxwinget install --id=Opera.OperaGXwinget install --id BraveSoftware.BraveBrowser`

 When asked for confirmation, press**Y** .

![installing chrome using the winget packet manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-chrome-winget.jpg)

 Exit the PowerShell window after the browser has been installed and you'll be ready to start browsing.

### Download a Browser Using the Curl Command

 Launch PowerShell by searching for it in the Start Menu. Navigate to the desktop by executing the following command:

`cd Desktop`

 Type the link for the browser you want to download ([Chrome](https://dl.google.com/chrome/install/standalonesetup64.exe) ,[Firefox](https://download.mozilla.org/?product=firefox-latest&os=win64) ,[Opera](https://net.geo.opera.com/opera/stable/windows) , and [Brave](https://referrals.brave.com/latest/BraveBrowserSetup.exe) ) and execute the following command:

`curl -L "link" -o download.exe`

Paste the link in quotation marks like so:

![installing chrome using the curl command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-chrome-curl.jpg)

 The command essentially asks Curl to navigate to a specific URL, make a download request, follow HTTP redirects, and save the files as download.exe.

 Once the file has been downloaded, run the installation wizard to complete the installation process.

### Download a Browser Using Chocolatey

 Chocolatey is a third-party package manager that functions similarly to Windows' winget and [Ubuntu's APT](https://www.makeuseof.com/tag/beginners-guide-installing-software-ubuntu-apt/) . It's a tool that helps install and uninstall apps using PowerShell or Command Prompt.

 However, Chocolatey doesn't come preinstalled with Windows. You'll need to first allow the running of executable scripts and then install Chocolatey using PowerShell.

 Of course, using Winget makes more sense since it's already installed on all the latest versions of WIndows. But if you want a third-party manager for better control or a larger repository, you might choose [Chocolatey over Winget](https://www.makeuseof.com/chocolatey-vs-windows-package-manager/) .

 To get started, search for PowerShell in the Start Menu and launch it as an administrator. Execute the following command to allow executable scripts:

`Set-ExecutionPolicy AllSigned`

Next, run the following command:

`Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('<a class="url" href="https://community.chocolatey.org/install.ps1" target="_blank">https://community.chocolatey.org/install.ps1</a>'))`

 That's quite long, and since you're probably viewing this on a different device, your best bet would be to email the command to yourself and copy it over from a client like Outlook. As a last resort, you can always manually type this into PowerShell.

 When you're done, you can install all apps in Chocolatey's repository by typing their name after "choco install". Here are the commands for downloading the most popular browsers:

`choco install googlechromechoco install firefoxchoco install operachoco install brave`

![installing chrome using chocolatey](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-chrome-choco.jpg)

Once the process is complete, you can start using the new browser.

## 3\. Use a Invoke-WebRequest PowerShell Script

 PowerShell is a command-line environment you can use to download files from the internet. This means you can also download browsers a browser's setup file using PowerShell and run the installation without using another browser.

 Start by [launching PowerShell](https://www.makeuseof.com/windows-11-powershell-administrator/) on your computer by searching for it in the Start Menu. Type the following command into the PowerShell:

`cd Desktop`

 The command takes PowerShell to your desktop. When you run the command for downloading a file, PowerShell will save the file to your desktop.

 Next, grab the download link for the browser you want to install. Here are the installation links for the most popular browsers—[Chrome](https://dl.google.com/chrome/install/standalonesetup64.exe) ,[Firefox](https://download.mozilla.org/?product=firefox-latest&os=win64) ,[Opera](https://net.geo.opera.com/opera/stable/windows) , and [Brave](https://referrals.brave.com/latest/BraveBrowserSetup.exe) .

Run the following command in PowerShell:

`Invoke-WebRequest link -o download.exe`

![installing chrome using powershell scripting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-chrome-powershell-script.jpg)

 Replace the word link with the link to your browser's setup file. Once you execute the command, you'll see PowerShell downloading the file. Once the download is complete, exit PowerShell and run the download.exe file stored on your desktop. Follow the installation wizard's instructions and you're set.

## Start Browsing on Your Fave Browser From Day One

 Hopefully, you were able to download a browser and install it using one of these methods. Windows offers a ton of options to get things done. Take your pick when installing a browser without a browser. What matters is installing a browser you think best suits your needs.


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
<li><a href="https://snapchat-videos.techidaily.com/updated-telltale-signs-your-chat-is-hidden/"><u>[Updated] Telltale Signs Your Chat Is Hidden</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-potential-of-windows-without-using-the-compatibility-tool/"><u>Unlock Potential of Windows without Using the Compatibility Tool.</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-windows-tray-for-numeric-lock-signifiers/"><u>Customizing Windows Tray for Numeric Lock Signifiers</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-microsoft-store-eliminating-code-x80072f30-errors/"><u>Mastering the Microsoft Store: Eliminating Code X80072F30 Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-win-1011s-geforce-notaxc0f1103f-error/"><u>Fixing Win 10/11'S GeForce NotaXC0F1103F Error</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-and-overcoming-microsoft-offices-error-code-0x80040610/"><u>Deciphering and Overcoming Microsoft Office's Error Code 0X80040610</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-error-code-0x8007251d-in-microsofts-os-activation/"><u>Demystifying Error Code 0X8007251d in Microsoft's OS Activation</u></a></li>
<li><a href="https://windows11.techidaily.com/microsofts-profit-mechanisms-in-windows-11/"><u>Microsoft's Profit Mechanisms in Windows 11</u></a></li>
<li><a href="https://audio-editing.techidaily.com/imovie-audio-editing-tips-everything-you-need-to-know/"><u>IMovie Audio Editing Tips - Everything You Need to Know</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-compact-cameras-for-mobile-cinematography/"><u>2024 Approved  Compact Cameras for Mobile Cinematography</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-ultimate-free-toolset-for-win11-pcs/"><u>Unveiling the Ultimate Free Toolset for Win11 PCs</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/2024-approved-mac-video-editing-made-easy-with-mkvtoolnix-software/"><u>2024 Approved Mac Video Editing Made Easy with MKVtoolnix Software</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-expand-start-menu-pin-scope/"><u>Strategies to Expand Start Menu Pin Scope</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-windows-11-deployment-on-vmware-17-platform/"><u>Effortless Windows 11 Deployment on VMWare 17 Platform</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-full-potential-of-taskbar-in-win11/"><u>Unlock the Full Potential of Taskbar in Win11</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-in-2024-top-10-free-speech-to-text-apps-for-android-and-ios/"><u>New In 2024, Top 10 FREE Speech-to-Text Apps for Android & iOS,</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-the-barrier-of-windows-11-updates/"><u>Breaking Down the Barrier of Windows 11 Updates</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-combine-power-tweeting-and-snapping-with-snapchat/"><u>[Updated] Combine Power  Tweeting and Snapping with Snapchat</u></a></li>
<li><a href="https://windows11.techidaily.com/identify-and-solve-hidden-disk-space-problems-in-windows/"><u>Identify & Solve Hidden Disk Space Problems in Windows</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-in-2024-the-ultimate-guide-to-exceptional-live-streamers/"><u>[New] In 2024, The Ultimate Guide to Exceptional Live Streamers</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-improve-steam-download-speeds-on-windows/"><u>Strategies to Improve Steam Download Speeds on Windows</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-10-leading-mobile-vr-headsets-ranked/"><u>In 2024, 10 Leading Mobile VR Headsets Ranked</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-spotify-link-reset-strategies/"><u>Mastering Windows Spotify Link Reset Strategies</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-use-google-assistant-on-your-lock-screen-of-nubia-red-magic-8s-proplus-phone-by-drfone-android/"><u>In 2024, How to Use Google Assistant on Your Lock Screen Of Nubia Red Magic 8S Pro+ Phone</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/dawn-dialogues-how-to-wake-up-the-world-with-good-morning/"><u>Dawn Dialogues: How to Wake Up the World with 'Good Morning'</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-requirement-errors-in-gaming/"><u>Bypassing Windows Requirement Errors in Gaming</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-master-earning-plan-top-5-highest-paying-ig-posts/"><u>[Updated] Master Earning Plan  Top 5 Highest Paying IG Posts</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/youtube-and-instagram-syncing-up-your-media/"><u>YouTube and Instagram  Syncing Up Your Media</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/explore-the-top-5-snipping-utilities-for-chrome-os-users-for-2024/"><u>Explore The Top 5 Snipping Utilities For Chrome OS Users for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-guide-deciphering-and-fixing-error-x800704cf/"><u>Expert Guide: Deciphering and Fixing Error X800704CF</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-mastering-the-exchange-of-fb-vids-on-whatsapp-for-2024/"><u>[Updated] Mastering the Exchange of FB Vids on WhatsApp for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-0x80072af9-error-code-instantly/"><u>Eliminating 0X80072AF9 Error Code Instantly</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-workspace-potential-discover-the-best-window-folder-methods/"><u>Unlock Workspace Potential: Discover the Best Window Folder Methods</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-advanced-virtual-meeting-spaces-beyond-discord/"><u>[New] Advanced Virtual Meeting Spaces Beyond Discord</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-outstanding-mac-screen-recording-options-beyond-bandicamp/"><u>[Updated] In 2024, Outstanding Mac Screen Recording Options  Beyond Bandicamp</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-launching-into-the-spotlight-instagram-lives/"><u>[Updated] 2024 Approved  Launching Into the Spotlight  Instagram Lives</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-driver-verifier-management-in-windows-11/"><u>Guide: Driver Verifier Management in Windows 11</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-unraveling-the-purpose-behind-facebooks-blue-icon/"><u>In 2024, Unraveling the Purpose Behind Facebook's Blue Icon</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-captivate-your-audience-professional-end-screen-creations-for-2024/"><u>[New] Captivate Your Audience  Professional End Screen Creations for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-transform-your-memories-into-a-beautiful-video/"><u>Updated In 2024, Transform Your Memories Into a Beautiful Video</u></a></li>
<li><a href="https://windows11.techidaily.com/install-and-enhance-edge-security-with-the-defender-application-guard-from-ms/"><u>Install and Enhance Edge Security with the Defender Application Guard From MS</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-windows-unlocking-diskusage-insights-for-storage-management/"><u>Maximizing Windows: Unlocking DiskUsage Insights for Storage Management</u></a></li>
<li><a href="https://windows11.techidaily.com/creating-personalized-themes-in-wt-terminal/"><u>Creating Personalized Themes in WT Terminal</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-ultimate-techniques-for-producing-stellar-videotutorials/"><u>[New] 2024 Approved  Ultimate Techniques for Producing Stellar Videotutorials</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-faster-typing-the-powertoys-way/"><u>Unlock Faster Typing: The PowerToys Way</u></a></li>
<li><a href="https://windows11.techidaily.com/unbridled-upgrade-choose-bare-essentials-win11/"><u>Unbridled Upgrade: Choose Bare Essentials Win11</u></a></li>
<li><a href="https://fox-glue.techidaily.com/boxing-vs-streaming-ultimate-showdown-for-2024/"><u>Boxing vs Streaming  Ultimate Showdown for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-correcting-failed-java-setup-in-windows/"><u>Techniques for Correcting Failed Java Setup in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-pin-count-on-the-w11-start-screen/"><u>Boosting Pin Count on the W11 Start Screen</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-optimizing-video-calls-a-guide-from-skype-to-zoom/"><u>2024 Approved  Optimizing Video Calls  A Guide From Skype to Zoom</u></a></li>
<li><a href="https://windows11.techidaily.com/supercharge-utorrent-downloads-elevate-your-file-speed/"><u>Supercharge uTorrent Downloads, Elevate Your File Speed</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-new-horizons-in-personalizing-windows-11/"><u>Exploring New Horizons in Personalizing Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-preventing-google-chromes-autopilot-tabs/"><u>Guide to Preventing Google Chrome's Autopilot Tabs</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-winpcs-fatal-pink-flash/"><u>Troubleshooting WinPC's Fatal Pink Flash</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-the-mystic-art-of-invisible-storytelling-on-snapchat-for-2024/"><u>[Updated] The Mystic Art of Invisible Storytelling on Snapchat for 2024</u></a></li>
<li><a href="https://techidaily.com/repair-broken-or-corrupt-video-files-of-huawei-mate-x3-by-stellar-video-repair-mobile-video-repair/"><u>Repair broken or corrupt video files of Huawei Mate X3</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/unlock-your-realme-12plus-5g-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>Unlock Your Realme 12+ 5G Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-guide-eradicating-pending-videos-on-your-youtube-queue/"><u>In 2024, Guide  Eradicating Pending Videos on Your YouTube Queue</u></a></li>
<li><a href="https://android-location-track.techidaily.com/5-ways-to-track-nubia-red-magic-8s-proplus-without-app-drfone-by-drfone-virtual-android/"><u>5 Ways to Track Nubia Red Magic 8S Pro+ without App | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/strategizing-your-path-through-original-diablo/"><u>Strategizing Your Path Through Original Diablo</u></a></li>
<li><a href="https://windows11.techidaily.com/10-swift-routes-to-the-control-panel-interface/"><u>10 Swift Routes to the Control Panel Interface</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-navigating-fb-lives-dual-screen-dynamics-essential-insights/"><u>In 2024, Navigating FB Live's Dual-Screen Dynamics  Essential Insights</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-venture-into-virtuality-comprehensively-reviewing-top-10-vr-streamers/"><u>In 2024, Venture Into Virtuality  Comprehensively Reviewing Top 10 VR Streamers</u></a></li>
</ul></div>
