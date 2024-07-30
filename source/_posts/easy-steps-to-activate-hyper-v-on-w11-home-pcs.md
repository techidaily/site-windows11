---
title: Easy Steps to Activate Hyper-V on W11 Home PCs
date: 2024-07-29T04:28:50.793Z
updated: 2024-07-30T04:28:50.793Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Easy Steps to Activate Hyper-V on W11 Home PCs
excerpt: This Article Describes Easy Steps to Activate Hyper-V on W11 Home PCs
keywords: Hyper-V Activation Guide,Enable Hyper-V Windows W11,Hyper-V Setup for Home Users,Turning on Hyper-V W11 Home PC,Activate W11 Hyper-V Easily,Simple Hyper-V Activate W11,How to Use Hyper-V in Windows W11
thumbnail: https://thmb.techidaily.com/44cba3f77a25fb10a15058a95ecd605b31dd154fe2d91aae028e5e688022e444.jpg
---

## Easy Steps to Activate Hyper-V on W11 Home PCs

 You can enable Hyper-V in Windows 11 as an optional feature included by default with the operating system. It lets you create virtual machines to install and run the guest OS on virtual hardware. However, Hyper-V is only available for the Pro, Education, and Enterprise edition of the OS. If you are using the Home edition, you have to rely on a third-party virtual machine manager.

 If you don’t want to use a third-party virtual machine manager, here is how to install Hyper-V on Windows 11 Home using a batch script hack.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## How to Enable Hardware Virtualization in Windows 11

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254762&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/11_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->
## Run Hyper-V on Windows 11 Home

 Microsoft has officially restricted the use of Hyper-V to the Pro, Education, and Enterprise edition of the OS. However, a little tweak in the BIOS and a handy batch script can help you install Hyper-V on Windows 11 Home.

 Once you have Hyper-V up and running, you can install Windows, Ubuntu, and other supported operating systems in a virtual machine.

 If you don’t want to use a third-party virtual machine manager, here is how to install Hyper-V on Windows 11 Home using a batch script hack.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-best-recorders-for-lecture-recording/"><u>[New] 2024 Approved  Best Recorders for Lecture Recording</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-effortlessly-traverse-facebooks-past-posts-for-2024/"><u>[New] Effortlessly Traverse Facebook’s Past Posts for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-initial-steps-to-instagram-video-discussion-success-for-2024/"><u>[New] Initial Steps to Instagram Video Discussion Success for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-scrutinizing-the-legalities-of-youtube-versus-creative-commons/"><u>[New] Scrutinizing the Legalities of Youtube Versus Creative Commons</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-skycheap-fileserver-economical-efficient-large-data/"><u>[New] SkyCheap Fileserver  Economical, Efficient Large Data</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-captivate-viewers-the-art-of-crafting-short-videos/"><u>[Updated] 2024 Approved  Captivate Viewers  The Art of Crafting Short Videos</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-comprehensive-srt-handbook-for-enthusiasts/"><u>[Updated] The Comprehensive SRT Handbook for Enthusiasts</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-unlocking-the-metaverse-simplified-avatar-designs/"><u>[Updated] Unlocking the Metaverse  Simplified Avatar Designs</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-two-pocket-strategies-for-effective-google-meet-documentation/"><u>2024 Approved  Two Pocket Strategies for Effective Google Meet Documentation</u></a></li>
<li><a href="https://windows11.techidaily.com/6-methods-for-reviving-windows-command-line-interface/"><u>6 Methods for Reviving Windows' Command Line Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/additional-updates-available-in-windows-11s-latest-release/"><u>Additional Updates Available in Windows 11'S Latest Release</u></a></li>
<li><a href="https://windows11.techidaily.com/address-common-printer-glitches-in-windows-11/"><u>Address Common Printer Glitches in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-blank-display-in-windows-remoting-services/"><u>Addressing Blank Display in Windows Remoting Services</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-offline-status-of-valve-games-via-steam-desktop-client/"><u>Addressing Offline Status of Valve Games via Steam Desktop Client</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-distracting-notifications-messages-on-windows-11/"><u>Avoid Distracting Notifications, Messages on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-dual-defense-opt-for-single-antivirus-in-windows-systems/"><u>Avoid Dual Defense: Opt for Single Antivirus in Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-error-0xc00000f-by-implementing-proper-fixes/"><u>Avoiding Error 0xC00000F by Implementing Proper Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/banishing-glitches-fix-windows-11-screen-flash/"><u>Banishing Glitches: Fix Windows 11 Screen Flash</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/does-galaxy-m34-5g-support-mkv-video-files-by-aiseesoft-video-converter-play-mkv-on-android/"><u>Does Galaxy M34 5G support MKV video files?</u></a></li>
<li><a href="https://unlock-android.techidaily.com/downloading-samfw-frp-tool-30-for-honor-magic-6-lite-by-drfone-android/"><u>Downloading SamFw FRP Tool 3.0 for Honor Magic 6 Lite</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-restricted-settings-due-to-user-level-administrator-controls/"><u>Eliminating Restricted Settings Due to User-Level Administrator Controls</u></a></li>
<li><a href="https://windows11.techidaily.com/ending-system-crashes-fix-for-code-0x0000011b-errors/"><u>Ending System Crashes: Fix for Code 0X0000011B Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-steps-to-switch-off-stuck-theme-on-pc/"><u>Essential Steps to Switch Off Stuck Theme on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-display-glitch-geforce-experience-x0001/"><u>Fixing Display Glitch: GeForce Experience X0001</u></a></li>
<li><a href="https://windows11.techidaily.com/future-proof-computing-with-top-windows-laptop-choices/"><u>Future-Proof Computing with Top Windows Laptop Choices</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-dismantle-spotlight-icons-in-win11/"><u>Guide to Dismantle Spotlight Icons in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-change-the-default-pdf-reader-on-windows/"><u>How to Change the Default PDF Reader on Windows</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-does-motorola-edge-2023-have-find-my-friends-drfone-by-drfone-virtual-android/"><u>In 2024, Does Motorola Edge 2023 Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-motorola-g24-power-drfone-by-drfone-virtual-android/"><u>In 2024, Here Are Some Reliable Ways to Get Pokemon Go Friend Codes For Motorola G24 Power | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-remove-the-two-factor-authentication-on-apple-iphone-14-pro-by-drfone-ios/"><u>In 2024, How To Remove the Two Factor Authentication On Apple iPhone 14 Pro</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-photo-magic-weaving-text-into-your-imagery-journey/"><u>In 2024, Photo Magic  Weaving Text Into Your Imagery Journey</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-two-ways-to-track-my-boyfriends-apple-iphone-6s-plus-without-him-knowing-drfone-by-drfone-virtual-ios/"><u>In 2024, Two Ways to Track My Boyfriends Apple iPhone 6s Plus without Him Knowing | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-nokia-c12-pro-drfone-by-drfone-virtual-android/"><u>In 2024, What is the best Pokemon for pokemon pvp ranking On Nokia C12 Pro? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/innovative-ways-to-initiate-windows-based-software/"><u>Innovative Ways to Initiate Windows-Based Software</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-manual-methods-for-malware-detection-on-desktops/"><u>Mastering Manual Methods for Malware Detection on Desktops</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-reactivating-adobe-on-windows-os/"><u>Mastering the Art of Reactivating Adobe on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/minimize-high-usage-windows-11-news-and-media-feats/"><u>Minimize High Usage Windows 11 News & Media Feats</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-intel-unison-app-for-seamless-windows-phone-calls/"><u>Navigating Intel Unison App for Seamless Windows Phone Calls</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-windows-update-pitfalls-0x30017/"><u>Navigating Through Windows Update Pitfalls (0X30017)</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-your-workflow-keep-gmail-pinned-for-easy-viewing/"><u>Optimize Your Workflow: Keep Gmail Pinned for Easy Viewing</u></a></li>
<li><a href="https://fix-guide.techidaily.com/poco-x6-pro-screen-unresponsive-heres-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Poco X6 Pro Screen Unresponsive? Heres How to Fix It | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/precision-in-picture-editing-eliminating-backgrounds-effectively/"><u>Precision in Picture Editing: Eliminating Backgrounds Effectively</u></a></li>
<li><a href="https://windows11.techidaily.com/recover-lost-windows-customizations-on-reboot/"><u>Recover Lost Windows Customizations on Reboot</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/reveal-whats-hidden-in-lenovo-screens/"><u>Reveal What's Hidden in Lenovo Screens</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-integration-windows-pc-plus-galaxy-via-samsung-flow/"><u>Seamless Integration: Windows PC + Galaxy via Samsung Flow</u></a></li>
<li><a href="https://windows11.techidaily.com/speed-up-taskbar-interaction-enabledisable-ai-on-win-11/"><u>Speed Up Taskbar Interaction: Enable/Disable AI on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-choosing-and-changing-screensavers-in-win11/"><u>The Art of Choosing and Changing Screensavers in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-premier-lineup-of-zero-cost-must-haves-for-windows-11/"><u>The Premier Lineup of Zero-Cost Must-Haves for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-alomware-resource-for-windows-tweakers/"><u>The Ultimate AlomWare Resource for Windows Tweakers</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-ultimate-guide-to-selecting-5-online-title-makers/"><u>The Ultimate Guide to Selecting 5 Online Title Makers</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-capturing-and-organizing-uac-alert-snaps/"><u>Tips for Capturing and Organizing UAC Alert Snaps</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-5-tracking-apps-to-track-vivo-y27-4g-without-them-knowing-drfone-by-drfone-virtual-android/"><u>Top 5 Tracking Apps to Track Vivo Y27 4G without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/top-notch-solutions-for-disabled-apple-id-from-apple-iphone-se-making-it-possible-by-drfone-ios/"><u>Top-Notch Solutions for Disabled Apple ID From Apple iPhone SE Making It Possible</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-stopping-discord-startup-and-updates/"><u>Troubleshooting: Stopping Discord Startup and Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-sleep-mode-anomalies-why-it-frustrates-users/"><u>Windows' Sleep Mode Anomalies: Why It Frustrates Users</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>