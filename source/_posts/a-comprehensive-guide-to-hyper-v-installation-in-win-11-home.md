---
title: A Comprehensive Guide to Hyper-V Installation in Win 11 Home
date: 2024-07-11T21:41:02.602Z
updated: 2024-07-12T21:41:02.602Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Comprehensive Guide to Hyper-V Installation in Win 11 Home
excerpt: This Article Describes A Comprehensive Guide to Hyper-V Installation in Win 11 Home
keywords: Win 11 Hyper-V Setup,Hyper-V Installer Win 11,Win 11 Virtualization Guide,Win 11 VM Configuration,Home Win 11 Hyper-V Install,Win 11 Hyper-V Basics,Quick Win 11 Hyper-V Setup
thumbnail: https://thmb.techidaily.com/65d1648a69e474032218f98a4f9088236faaaabb296646cc458aad0041a1d229.png
---

## A Comprehensive Guide to Hyper-V Installation in Win 11 Home

 You can enable Hyper-V in Windows 11 as an optional feature included by default with the operating system. It lets you create virtual machines to install and run the guest OS on virtual hardware. However, Hyper-V is only available for the Pro, Education, and Enterprise edition of the OS. If you are using the Home edition, you have to rely on a third-party virtual machine manager.

 If you don’t want to use a third-party virtual machine manager, here is how to install Hyper-V on Windows 11 Home using a batch script hack.

## How to Enable Hardware Virtualization in Windows 11

![enable hardware virtualization bios hp laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hardware-virtualization-bios-hp-laptoop-1.jpg)

 Hyper-V is a bare-metal hypervisor and requires [Hardware Virtualization enabled in BIOS to work](https://www.makeuseof.com/what-is-virtualization-and-what-is-it-for/). Most modern systems support Hardware Virtualization, and you can enable it in BIOS.

 The below steps are for an HP laptop. Refer to the user manual or Knowledge Base resources on the computer manufacturer's website for other systems.

 To enable Hardware Virtualization in BIOS:

1. Shut down your PC if it is powered on.
2. Press the **Power** button to turn on the computer and then start pressing the **F10 key** to enter BIOS. The BIOS setup key varies depending on the manufacturer. So, use **F10, F2, F12, F1,** or **DEL** and see which one works for you.
3. Once in the BIOS Setup utility, open the **Configuration** tab.
4. Use the down arrow key and highlight **Virtualization Technology.**
5. Hit **Enter** and then select **Enabled**. Press **Enter** again to make the selection.
6. Next, press **F10** to save the changes and exit **BIOS**.
7. Your PC will restart with the Hardware Virtualization enabled. Now you can continue to install Hyper-V on your system.

## How to Install Hyper-V on Windows 11 Home

 The next step is to create and run a batch script to install the required files to enable Hyper-V in Windows 11 Home.

 Before you proceed with the next set of steps, [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/). This will help you restore your computer to its current state if something goes wrong during the process.

 To enable Hyper-V in Windows 11 Home:

 1\. Open a new Notepad file. To do this, press **Win + R**, type notepad, and click **OK.**

![hyper v install windows 11 home script](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/hyper-v-install-windows-11-home-script.png)

 2\. In the Notepad file, copy and paste the following script:

`pushd "%~dp0"  
dir /b %SystemRoot%\servicing\Packages\*Hyper-V*.mum >hyper-v.txt  
for /f %%i in ('findstr /i . hyper-v.txt 2^>nul') do dism /online /norestart /add-package:"%SystemRoot%\servicing\Packages\%%i"  
del hyper-v.txt  
Dism /online /enable-feature /featurename:Microsoft-Hyper-V -All /LimitAccess /ALL  
pause`

 3\. Press **Ctrl + S** to open the save dialog.

 4\. In the file name field, type **hyperv.bat.** The **.bat** extension at the end of the file name is important to execute the script.

![save hyperv install script](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/save-hyperv-install-script.png)

 5\. Next, click the drop-down for **Save as type** and select **All Files.**

 6\. Click the **Save** button to save the file.

![run hyperv bat script administrator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/run-hyperv-bat-script-administrator.png)

 7\. Next, right-click on the **hyperv.bat** file and select **Run as administrator**. Click **Yes** if prompted by User Account Control.

 8\. The scrip will start executing in the Command Prompt to install Hyper-V. It may take a while, so wait till the process is complete.

 9.Once completed, you will see the Operation completed successfully message.

![install hyper v install windows 11 home](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/install-hyper-v-install-windows-11-home.png)

 10\. Type **Y** to confirm and restart your PC. If not, enter N to exit the Command Prompt.

 Note that you will need to restart your PC to apply the changes. After the restart, you should have Hyper-V installed in Windows 11 Home. Type Hyper-V in Windows search and click on Hyper-V Manager to create new a virtual machine.

 If it is still not available, you can [enable Hyper-V using the Windows Features dialog](https://www.makeuseof.com/windows-11-enable-hyper-v/), Command Prompt, and Windows PowerShell.

 Here's how you can quickly add Hyper-V to Windows 11 using Command Prompt:

1. Press the **Win** key and type **cmd**. Then right-click on **Command Prompt** and select **Run as administrator.**  
![enable hyper v command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hyper-v-command-prompt.png)
2. In the Command Prompt window, type the following command and press **Enter**:  
`<code>DISM /Online /Enable-Feature /All /FeatureName:Microsoft-Hyper-V`
3. The above command uses the Deployment Imaging Service and Management (DISM) tool to enable Microsoft Hyper-V and the necessary dependencies on your Windows computer. The operation completed successfully message means you have successfully enabled Hyper-V.

## How to Disable Hyper-V on Windows 11 Home

![disable hyper v windows 11 windows features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/disable-hyper-v-windows-11-windows-features.jpg)

 You can disable Hyper-V in Windows 11 Home using the Windows Features dialog.

 To disable Hyper-V:

1. Press **Win + R** to open the **Run** dialog box.
2. Type **optionalfeatures.exe** and click **OK**.
3. In the **Windows Features** dialog, locate the Hyper-V option.
4. Uncheck the **Hyper-V** option and click **OK**. Wait for the uninstallation process to complete.
5. Next, click on **Restart Now** to restart your PC and apply the changes.

 Apart from Hyper-V, the Windows OS features another nifty virtualization solution, Windows Sandbox—a lightweight desktop environment to run applications in isolation. You can [enable Windows Sandbox from Windows Features](https://www.makeuseof.com/enable-set-up-windows-sandbox-windows-11/), but only on the Pro and Enterprise edition of the OS.

 Unlike Hyper-V, there is no batch script hack to install the sandbox app on the Home edition of Windows 11\. Instead, you can use one of the [Windows Sandbox Alternatives for Windows](https://www.makeuseof.com/windows-11-sandbox-alternatives/) to run and test applications in isolation.

## Run Hyper-V on Windows 11 Home

 Microsoft has officially restricted the use of Hyper-V to the Pro, Education, and Enterprise edition of the OS. However, a little tweak in the BIOS and a handy batch script can help you install Hyper-V on Windows 11 Home.

 Once you have Hyper-V up and running, you can install Windows, Ubuntu, and other supported operating systems in a virtual machine.

 If you don’t want to use a third-party virtual machine manager, here is how to install Hyper-V on Windows 11 Home using a batch script hack.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/easing-through-policy-restrictions-in-admin-blocked-installations/"><u>Easing Through Policy Restrictions in Admin-Blocked Installations</u></a></li>
<li><a href="https://windows11.techidaily.com/reestablishing-copy-pasting-efficiency-across-browsers/"><u>Reestablishing Copy-Pasting Efficiency Across Browsers</u></a></li>
<li><a href="https://windows11.techidaily.com/redefining-virtual-meetings-a-lightweight-approach/"><u>Redefining Virtual Meetings: A Lightweight Approach</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-zero-price-mac-video-maker-for-2024/"><u>[New] Zero-Price Mac Video Maker for 2024</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-oppo-a56s-5g-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Oppo A56s 5G without Losing Data | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/in-2024-how-to-change-infinix-zero-5g-2023-turbo-location-on-skout-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Infinix Zero 5G 2023 Turbo Location on Skout | Dr.fone</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/024-approved-a-closer-look-at-youtubes-payment-system-and-its-potential/"><u>[New] 2024 Approved  A Closer Look at YouTube's Payment System and Its Potential</u></a></li>
<li><a href="https://howto.techidaily.com/want-to-uninstall-google-play-service-from-vivo-y100a-here-is-how-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Want to Uninstall Google Play Service from Vivo Y100A? Here is How | Dr.fone</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/the-art-of-crafting-gopro-time-lapses/"><u>The Art of Crafting GoPro Time-Lapses</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-edge-solutions-exclusive-windows-systems-for-dsswitch-players/"><u>Cutting-Edge Solutions: Exclusive Windows Systems for DS/Switch Players</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/streaming-made-simple-free-downloader-to-mp3s-now-in-2024/"><u>Streaming Made Simple  Free Downloader to MP3s Now, In 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/achieve-flawless-display-setups-with-win11/"><u>Achieve Flawless Display Setups with Win11</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/superior-speech-logging-apps-for-ipads-3-for-2024/"><u>Superior Speech Logging Apps for iPads #3 for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/an-intuitive-guide-to-performing-a-windows-rollback-via-system-restore/"><u>An Intuitive Guide to Performing a Windows Rollback via System Restore</u></a></li>
<li><a href="https://extra-hints.techidaily.com/enriching-your-video-content-advanced-voiceover-strategies/"><u>Enriching Your Video Content  Advanced Voiceover Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/smoothening-playback-speed-in-vlc-for-windows/"><u>Smoothening Playback Speed in VLC for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/triumph-over-outdated-updates-winning-strategies-revealed/"><u>Triumph Over Outdated Updates: Winning Strategies Revealed</u></a></li>
<li><a href="https://windows11.techidaily.com/secrets-to-savings-on-windows-10-key-focused-strategies/"><u>Secrets to Savings on Windows 10: Key-Focused Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-file-scooping-6-routes-to-data-secrets/"><u>Swift File Scooping: 6 Routes to Data Secrets</u></a></li>
<li><a href="https://windows11.techidaily.com/disentangling-compact-icons-on-desktop-shelf/"><u>Disentangling Compact Icons on Desktop Shelf</u></a></li>
<li><a href="https://windows11.techidaily.com/banishing-0x800700e9-glitches-in-xbox-game-pass-on-windows-11-devices/"><u>Banishing 0X800700E9 Glitches in Xbox Game Pass on Windows 11 Devices</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-beyond-basics-pro-tips-for-sticker-queries-on-instagram-for-2024/"><u>[Updated] Beyond Basics  Pro Tips for Sticker Queries on Instagram for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-swift-circulation-of-playlists-on-youtube/"><u>[Updated] 2024 Approved  Swift Circulation of Playlists on YouTube</u></a></li>
<li><a href="https://youtube-web.techidaily.com/approved-the-executive-mind-how-neuroscience-can-inform-better-management-strategies/"><u>2024 Approved  The Executive Mind  How Neuroscience Can Inform Better Management Strategies</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-monitors-unveiled-the-ultimate-guide-for-sourcing-a-stellar-4k-screen/"><u>[New] Monitors Unveiled  The Ultimate Guide for Sourcing a Stellar 4K Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-inaccessible-page-errors-for-windows-store-apps/"><u>Addressing Inaccessible Page Errors for Windows Store Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-homes-unlocked-your-guide-to-installing-hyper-v/"><u>Win 11 Homes Unlocked: Your Guide to Installing Hyper-V</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-no-sync-option-on-steam-library-error/"><u>Tackling the No Sync Option on Steam Library Error</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-resolve-high-dpi-screen-problems-on-pc/"><u>Strategies to Resolve High DPI Screen Problems on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-guide-to-generating-gpo-data-with-gpresult/"><u>The Essential Guide to Generating GPO Data with GPResult</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-securing-an-annotate-free-video-experience-tips-for-new-avi-users-for-2024/"><u>Updated Securing an Annotate-Free Video Experience Tips for New AVI Users for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-memory-write-error-windows-fixes/"><u>Disabling 'Memory Write' Error: Windows Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-pc-performance-hiccups-in-warhammer-40k-boltgun/"><u>Tackling PC Performance Hiccups in Warhammer 40K Boltgun</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-best-6-celebrity-text-to-speech-ai-voice-generators-you-may-like/"><u>New Best 6 Celebrity Text to Speech AI Voice Generators You May Like</u></a></li>
<li><a href="https://windows11.techidaily.com/banishing-desktop-colors-8-fixes-when-windows-turns-rare-hues/"><u>Banishing Desktop Colors: 8 Fixes When Windows Turns Rare Hues</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-essential-tools-for-perfect-linux-screenshots/"><u>2024 Approved  Essential Tools for Perfect Linux Screenshots</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-top-iphone-photo-hacks-to-enhance-your-landscapes/"><u>2024 Approved  Top iPhone Photo Hacks to Enhance Your Landscapes</u></a></li>
<li><a href="https://windows11.techidaily.com/what-is-bluescreenview-and-how-do-you-use-it/"><u>What Is BlueScreenView and How Do You Use It?</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-maximizing-impact-using-youtube-analytics-for-content-strategy/"><u>[New] Maximizing Impact  Using YouTube Analytics for Content Strategy</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-mastering-voice-overs-for-videos-step-by-step-guide-for-2024/"><u>[New] Mastering Voice-Overs for Videos  Step-by-Step Guide for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-how-mycam-changes-video-recording-at-home-an-in-depth-review/"><u>[New] How MyCam Changes Video Recording at Home – An In-Depth Review</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-oppo-a78-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some Pro Tips for Pokemon Go PvP Battles On Oppo A78 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-screen-resets-for-windows-users/"><u>Streamlining Screen Resets for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/the-path-to-defaults-resetting-win11-admin-permissions/"><u>The Path to Defaults: Resetting Win11 Admin Permissions</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-win11-with-powertoys-installation/"><u>Streamlining Win11 with PowerToys Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/decluttering-your-win11-desktop-wallpaper-symbol/"><u>Decluttering Your Win11 Desktop Wallpaper Symbol</u></a></li>
<li><a href="https://windows11.techidaily.com/browser-bugs-and-breakages-fixing-website-issues-on-your-windows-pc/"><u>Browser Bugs & Breakages: Fixing Website Issues on Your Window's PC</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/capturing-quality-lens-recommendations-for-content-makers/"><u>Capturing Quality  Lens Recommendations for Content Makers</u></a></li>
<li><a href="https://windows11.techidaily.com/curb-high-gpu-demand-with-proven-fixes-for-wm-on-windows/"><u>Curb High GPU Demand with Proven Fixes for WM on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/win-back-missing-5ghz-connection-on-your-windows-pc/"><u>Win Back Missing 5GHz Connection on Your Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-productivity-best-apps-to-turn-your-pcs-clock-into-an-animated-screensaver/"><u>Streamline Productivity: Best Apps to Turn Your PC’s Clock Into an Animated Screensaver</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-the-windows-application-net-demand-error/"><u>Resolving the Windows Application .NET Demand Error</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-steps-for-online-printer-on-windows/"><u>Quick Steps for Online Printer on Windows</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-webinar-playback-recordings-for-2024/"><u>[New] Webinar Playback Recordings for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-your-visual-impact-journey-begins-with-our-50-free-banners/"><u>[Updated] Your Visual Impact Journey Begins with Our 50 FREE Banners</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-failed-auto-detection-of-windows-proxy/"><u>Troubleshooting Failed Auto-Detection of Windows Proxy</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-a-samsung-galaxy-a15-5g-easily-by-drfone-android/"><u>How To Unlock a Samsung Galaxy A15 5G Easily?</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-the-incompatible-gpu-mystery-wins11-and-win10-edition/"><u>Demystifying the Incompatible GPU Mystery: Wins11 & Win10 Edition</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/top-10-airplay-apps-in-oppo-reno-10-5g-for-streaming-drfone-by-drfone-android/"><u>Top 10 AirPlay Apps in Oppo Reno 10 5G for Streaming | Dr.fone</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-are-you-looking-for-an-ideal-halloween-countdown-video-clip-for-your-video-this-article-will-walk-you-through-the-best-ones-you-can-use-to/"><u>New 2024 Approved Are You Looking for an Ideal Halloween Countdown Video Clip for Your Video? This Article Will Walk You Through the Best Ones You Can Use to Get the Job Done Perfectly</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-reimagined-make-it-mirror-macos-style-in-5-easy-ways/"><u>Windows Reimagined: Make It Mirror macOS Style in 5 Easy Ways</u></a></li>
</ul></div>
