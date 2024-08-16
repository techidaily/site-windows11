---
title: Harnessing the Power of Linux Inside a Windows OS
date: 2024-08-15T16:16:24.646Z
updated: 2024-08-16T16:16:24.646Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Harnessing the Power of Linux Inside a Windows OS
excerpt: This Article Describes Harnessing the Power of Linux Inside a Windows OS
keywords: Linux on WinOS,Windows-Linux Integration,Linux in Windows Environment,Cross-OS Development with Linux,Linux Tools for Windows Users,Windows Supporting Linux Features,Enhancing OS Capabilities with Linux
thumbnail: https://thmb.techidaily.com/aca28fbc907b3b2134a063785955f99d7ee87845f83996484c29a6f763ca253a.jpg
---

## Harnessing the Power of Linux Inside a Windows OS

### Key Takeaways

* You must enable Windows Subsystem for Linux (WSL) before you can install a Linux distribution on a Windows PC.
* Not all Windows 10 versions are compatible with WSL, but all Windows 11 versions are.
* The updated WSL2 is more convenient and gives better performance, but you can switch to WSL1 to suit specific needs.

 If you want to run a Linux terminal on Windows, your best bet would be to enable Windows Subsystem for Linux (WSL), a gateway opener that allows you to install a Linux bash shell on a Windows OS. Once you’ve enabled WSL, you can install a Linux distro.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
## Requirements for Running WSL on Windows 10

 Before you enable Windows Subsystem for Linux, you should know of the minimum requirements needed to run WSL.

[According to Microsoft](https://learn.microsoft.com/en-us/windows/wsl/install), you should be running Windows 10 (64-bit) version 2004 or higher with Build 19041 or higher.

 All Windows 11 versions can run WSL.

 If you’re not sure of your Windows 10 flavor, it’s easy to [check which version of Windows 10 you have installed](https://www.makeuseof.com/tag/how-to-check-windows-10-version-build/).

 Some older versions of Windows 10 can also work, but you’ll have to manually install WSL.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
## How to Enable Windows Subsystem for Linux

 In order to install the Linux bash shell on Windows 10, you first have to enable Windows Subsystem for Linux.

 You’ll know if WSL isn't enabled because you’ll run into the error: “The Windows Subsystem for Linux optional component is not enabled. Please enable it and try again.”

 Here’s how to enable WSL in Windows 10:

 You first need to get into Windows **Programs and Features**.

1. Open Windows 10 **Settings** and select **Apps**.
2. On the right side of the window, under **Related settings**, click on **Programs and Features**.

![Programs and Features option under the Related settings section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/program-and-features-option-in-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
<!-- affiliate ads end -->

 Once you’re in, click on **Turn Windows features on or off** on the left panel. Then scroll down and check the corresponding box to enable Windows Subsystem for Linux.

![Windows Subsystem for Linux option in Windows Features page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/enable-wsl-windows-10.jpg)
<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Click **OK** to save your changes and hit **Restart now** to finish the process.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
### Installing WSL on a Windows Machine

 With WSL enabled on your Windows device, you can [install Windows Subsystem for Linux](https://www.makeuseof.com/tag/linux-bash-shell-on-windows-10/). After that, you can install any supported Linux distro right inside your Windows PC. Choosing a [small, lightweight Linux distro](https://www.makeuseof.com/tag/linux-distro-space/) might be helpful.

 You can also [install a Linux desktop in Windows](https://www.makeuseof.com/tag/linux-desktop-windows-subsystem/) that gives you a graphical UI to work with.

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## WSL1 or WSL2: Which Is Better For You?

 WSL2 is an upgraded version of Windows Subsystem for Linux and is now the default when installing a Linux distribution in Windows. It works with Windows 11 or Windows 10, Version 1903, Build 18362 or higher.

 There are a few differences between the two versions of WSL; chiefly, WSL2 offers better performance in addition to support for full system call compatibility and IPv6 support. Also, WSL2 uses a full Linux kernel inside a managed virtual machine (VM), so you don’t have to set up and manage a VM to run a Linux distro.

### Reasons to Switch to WSL1

 While the latest version of WSL offers better performance and a wider range of support, there are reasons you may want to use the older version. This is because WSL1 runs with older versions of VMware and VirtualBox—and WSL2 does not, although it is compatible with the latest versions of VirtualBox and VMware, which both support Hyper-V.

 The main reason to use WSL1 instead of WSL2 is that it offers better performance across OS file systems—a hurdle that can be overcome by creating your project files in the Linux file system.

 With WSL enabled and a Linux distro installed, you’ll be on your way to executing commands.

 If you want to run a Linux terminal on Windows, your best bet would be to enable Windows Subsystem for Linux (WSL), a gateway opener that allows you to install a Linux bash shell on a Windows OS. Once you’ve enabled WSL, you can install a Linux distro.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-essential-free-video-editing-apps-for-iphonesipads-for-2024/"><u>[New] Essential Free Video Editing Apps for iPhones/iPads for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-professional-screenshot-and-video-recorder-win10/"><u>[New] Professional Screenshot & Video Recorder, Win10</u></a></li>
<li><a href="https://youtube-data.techidaily.com/triking-a-chord-with-effective-youtube-imagery-sizes/"><u>[New] Striking a Chord with Effective YouTube Imagery Sizes</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-unveiling-hidden-shared-memories-in-messenger/"><u>[Updated] 2024 Approved  Unveiling Hidden Shared Memories in Messenger</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-emancipate-your-engagement-facebook-restored/"><u>[Updated] In 2024, Emancipate Your Engagement  Facebook Restored</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-synergy-in-copywriting-the-trio-technique-to-boost-your-fb-campaigns-performance/"><u>[Updated] In 2024, Synergy in Copywriting  The Trio Technique to Boost Your FB Campaign's Performance</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-in-2024-unlock-humor-potential-quickly-kapwings-app/"><u>[Updated] In 2024, Unlock Humor Potential Quickly - Kapwing's App</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-master-the-art-of-video-presentations-with-these-themes/"><u>[Updated] Master the Art of Video Presentations with These Themes</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-ultimate-android-screen-recorder-options-list/"><u>2024 Approved  Ultimate Android Screen Recorder Options List</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-unveiling-simple-techniques-for-effortless-undersea-vids/"><u>2024 Approved  Unveiling Simple Techniques for Effortless Undersea Vids</u></a></li>
<li><a href="https://windows11.techidaily.com/a-beginners-roadmap-to-understanding-windows-iscsi-initiator/"><u>A Beginner's Roadmap to Understanding Windows iSCSI Initiator</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensible-approach-to-fixing-notepad-non-openness-in-windows/"><u>A Comprehensible Approach to Fixing Notepad Non-Openness in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensive-guide-to-fixing-0xc00000f-error/"><u>A Comprehensive Guide to Fixing 0xC00000F Error</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/apcs-be6bat-ups-model-m1-expert-analysis-on-efficiency-and-features-including-built-in-charger-functionality/"><u>APC's BE6BAT UPS Model M1: Expert Analysis on Efficiency and Features Including Built-In Charger Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/averting-self-triggered-openings-on-msdnstoreapp/"><u>Averting Self-Triggered Openings on MSDN/StoreApp</u></a></li>
<li><a href="https://win-solutions.techidaily.com/bypassing-steams-stagnation-issues-fix-unfreezing-and-non-responsive-errors-in/"><u>Bypassing Steam's Stagnation Issues - Fix Unfreezing & Non-Responsive Errors In</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/comprehensive-analysis-of-google-stadia-areas-needing-upgrades/"><u>Comprehensive Analysis of Google Stadia - Areas Needing Upgrades</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-windows-pe-file-system/"><u>Decoding Windows' PE File System</u></a></li>
<li><a href="https://windows11.techidaily.com/dial-up-speed-strategies-to-revive-your-sluggish-pc/"><u>Dial Up Speed: Strategies to Revive Your Sluggish PC</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-techniques-for-altering-credentials-on-windows-11/"><u>Easy Techniques for Altering Credentials on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/1719261046850-experience-gptclone-at-home-for-free-on-windows/"><u>Experience GPTClone at Home for FREE on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tuning-fn-keys-windows-10-and-11-techniques/"><u>Fine-Tuning FN Keys: Windows 10 and 11 Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-unresponsive-f-keys-troubleshooting-in-windows-11-os/"><u>Fix: Unresponsive F Keys - Troubleshooting in Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/1719202743817-function-failures-on-win10-quick-remedies-available/"><u>Function Failures on Win10? Quick Remedies Available</u></a></li>
<li><a href="https://windows11.techidaily.com/granting-correct-permissions-to-solve-windows-installer-error/"><u>Granting Correct Permissions to Solve Windows Installer Error</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-bypass-android-lock-screen-using-emergency-call-on-itel-p55-5g-by-drfone-android/"><u>How to Bypass Android Lock Screen Using Emergency Call On Itel P55 5G?</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-change-your-sim-pin-code-on-your-google-pixel-7a-phone-by-drfone-android/"><u>How To Change Your SIM PIN Code on Your Google Pixel 7a Phone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-correct-hardware-detection-errors-in-win/"><u>How To Correct Hardware Detection Errors in Win</u></a></li>
<li><a href="https://windows11.techidaily.com/howtodarkennotepadwindesktop/"><u>HowToDarkenNotepadWinDesktop</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-best-8-3d-gold-text-effect-websites/"><u>In 2024, Best 8 3D Gold Text Effect Websites</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/24-rhythmic-repository-perfect-dj-templates-instantly-downloadable/"><u>In 2024, Rhythmic Repository  Perfect DJ Templates, Instantly Downloadable</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-unlock-software-for-vivo-y56-5g-device-top-5-picks-to-remove-android-locks-by-drfone-android/"><u>In 2024, The Best Android Unlock Software For Vivo Y56 5G Device Top 5 Picks to Remove Android Locks</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-xiaomi-13t-pro-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>In 2024, Xiaomi 13T Pro ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://windows11.techidaily.com/investigating-and-fixing-create-failed-on-windows-error-30005/"><u>Investigating and Fixing Create Failed on Windows Error 30005</u></a></li>
<li><a href="https://os-tips.techidaily.com/locating-your-itunes-backups-a-step-by-step-guide-to-finding-and-managing-backup-files/"><u>Locating Your iTunes Backups: A Step-by-Step Guide to Finding and Managing Backup Files</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-efficiency-how-copilot-key-shapes-your-windows-11-experience/"><u>Mastering Efficiency: How Copilot Key Shapes Your Windows 11 Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-unstoppable-methods-to-turn-off-ms-defender/"><u>Mastering Unstoppable Methods to Turn Off MS Defender</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-performance-with-5-wsl-2-enhancements/"><u>Maximizing Performance with 5 WSL 2 Enhancements</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-call-issue-fixed-runtime-errors-in-malwarebytes-for-win10win11/"><u>Overcoming the Call Issue: Fixed Runtime Errors in Malwarebytes for Win10/Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-this-file-is-alone-error-on-pcs/"><u>Overcoming This File Is Alone Error on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/proven-strategies-for-comprehensible-comic-consumption-on-win11/"><u>Proven Strategies for Comprehensible Comic Consumption on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/redoing-power-schemes-with-lost-settings-win-11/"><u>Redoing Power Schemes with Lost Settings (Win 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-read-only-status-in-1011s-file-directories/"><u>Remedying Read-Only Status in 10/11'S File Directories</u></a></li>
<li><a href="https://windows11.techidaily.com/reset-chronology-fix-windows-time-errors/"><u>Reset Chronology: Fix Windows Time Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-gl-driver-error-3-on-windows-11-a-step-by-step-guide/"><u>Resolving GL Driver Error 3 on Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/restore-and-revitalize-13-ways-to-rejuvenate-windows-systems/"><u>Restore & Revitalize: 13 Ways to Rejuvenate Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/restore-full-size-to-your-windows-11-icons/"><u>Restore Full Size to Your Windows 11 Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/securely-clearing-email-details-post-login/"><u>Securely Clearing Email Details Post-Login</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-your-system-without-relying-on-bitlocker/"><u>Securing Your System without Relying on Bitlocker</u></a></li>
<li><a href="https://windows11.techidaily.com/seeking-entry-into-the-windows-11-insider-circle/"><u>Seeking Entry Into the Windows 11 Insider Circle</u></a></li>
<li><a href="https://windows11.techidaily.com/starting-windows-terminal-with-quake-effects/"><u>Starting Windows Terminal with Quake Effects</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-correct-sound-hiccup-in-audacity-on-windows-11/"><u>Strategies to Correct Sound Hiccup in Audacity on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlined-startup-routines-in-modern-windows/"><u>Streamlined Startup Routines in Modern Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/surface-go-3-with-latest-chip-reviewed-mixed-outcomes-noted/"><u>Surface Go 3 with Latest Chip Reviewed: Mixed Outcomes Noted</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-non-existence-of-powershell-in-windows/"><u>Tackling the Non-Existence of PowerShell in Windows</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-complete-guide-to-assembling-a-summer-ready-everyday-carry-list-top-7-picks/"><u>The Complete Guide to Assembling a Summer-Ready Everyday Carry List (Top 7 Picks)</u></a></li>
<li><a href="https://windows11.techidaily.com/the-elusive-guide-to-unseen-menu-adjustments-windows-style/"><u>The Elusive Guide to Unseen Menu Adjustments, Windows Style</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-steps-resolving-issues-with-samsung-smart-tv-applications/"><u>Troubleshooting Steps: Resolving Issues with Samsung Smart TV Applications</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/uncover-the-best-gadgets-toms-authoritative-hardware-analysis/"><u>Uncover the Best Gadgets: Tom's Authoritative Hardware Analysis</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-windows-11s-compatibility-checker-usage-guide/"><u>Understanding Windows 11'S Compatibility Checker: Usage Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/visualize-resource-consumption-windows-tray-update-guide/"><u>Visualize Resource Consumption: Windows Tray Update Guide</u></a></li>
<li><a href="https://tech-hub.techidaily.com/what-is-llama-2-and-how-can-you-use-it/"><u>What Is Llama 2 and How Can You Use It?</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/wild-wonders-the-ultimate-list-of-strange-and-exciting-tiktok-games-for-2024/"><u>Wild Wonders  The Ultimate List of Strange and Exciting TikTok Games for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>