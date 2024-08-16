---
title: "Command Prompt Magic: Utilize Windows' WSL Feature"
date: 2024-08-15T15:56:48.355Z
updated: 2024-08-16T15:56:48.355Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Command Prompt Magic: Utilize Windows' WSL Feature"
excerpt: "This Article Describes Command Prompt Magic: Utilize Windows' WSL Feature"
keywords: CommandLineMagic,WSLUtilization,WindowsWSL,PowerShellWSL,BashWindows,LinuxCMD,SystemLSCommand
thumbnail: https://thmb.techidaily.com/1f343cc2ca566c6b496acac107d8a3cfc474691f655f34c60ef016476e0a8a74.jpg
---

## Command Prompt Magic: Utilize Windows' WSL Feature

### Key Takeaways

* You must enable Windows Subsystem for Linux (WSL) before you can install a Linux distribution on a Windows PC.
* Not all Windows 10 versions are compatible with WSL, but all Windows 11 versions are.
* The updated WSL2 is more convenient and gives better performance, but you can switch to WSL1 to suit specific needs.

 If you want to run a Linux terminal on Windows, your best bet would be to enable Windows Subsystem for Linux (WSL), a gateway opener that allows you to install a Linux bash shell on a Windows OS. Once you’ve enabled WSL, you can install a Linux distro.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Requirements for Running WSL on Windows 10

 Before you enable Windows Subsystem for Linux, you should know of the minimum requirements needed to run WSL.

[According to Microsoft](https://learn.microsoft.com/en-us/windows/wsl/install), you should be running Windows 10 (64-bit) version 2004 or higher with Build 19041 or higher.

 All Windows 11 versions can run WSL.

 If you’re not sure of your Windows 10 flavor, it’s easy to [check which version of Windows 10 you have installed](https://www.makeuseof.com/tag/how-to-check-windows-10-version-build/).

 Some older versions of Windows 10 can also work, but you’ll have to manually install WSL.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537546&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/7_copy_2_2_hdpro.png" border="0">HD Video Converter Factory Pro</a>
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
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->

 Once you’re in, click on **Turn Windows features on or off** on the left panel. Then scroll down and check the corresponding box to enable Windows Subsystem for Linux.

![Windows Subsystem for Linux option in Windows Features page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/enable-wsl-windows-10.jpg)

 Click **OK** to save your changes and hit **Restart now** to finish the process.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
### Installing WSL on a Windows Machine

 With WSL enabled on your Windows device, you can [install Windows Subsystem for Linux](https://www.makeuseof.com/tag/linux-bash-shell-on-windows-10/). After that, you can install any supported Linux distro right inside your Windows PC. Choosing a [small, lightweight Linux distro](https://www.makeuseof.com/tag/linux-distro-space/) might be helpful.

 You can also [install a Linux desktop in Windows](https://www.makeuseof.com/tag/linux-desktop-windows-subsystem/) that gives you a graphical UI to work with.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## WSL1 or WSL2: Which Is Better For You?

 WSL2 is an upgraded version of Windows Subsystem for Linux and is now the default when installing a Linux distribution in Windows. It works with Windows 11 or Windows 10, Version 1903, Build 18362 or higher.

 There are a few differences between the two versions of WSL; chiefly, WSL2 offers better performance in addition to support for full system call compatibility and IPv6 support. Also, WSL2 uses a full Linux kernel inside a managed virtual machine (VM), so you don’t have to set up and manage a VM to run a Linux distro.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->
### Reasons to Switch to WSL1

 While the latest version of WSL offers better performance and a wider range of support, there are reasons you may want to use the older version. This is because WSL1 runs with older versions of VMware and VirtualBox—and WSL2 does not, although it is compatible with the latest versions of VirtualBox and VMware, which both support Hyper-V.

 The main reason to use WSL1 instead of WSL2 is that it offers better performance across OS file systems—a hurdle that can be overcome by creating your project files in the Linux file system.

 With WSL enabled and a Linux distro installed, you’ll be on your way to executing commands.

 If you want to run a Linux terminal on Windows, your best bet would be to enable Windows Subsystem for Linux (WSL), a gateway opener that allows you to install a Linux bash shell on a Windows OS. Once you’ve enabled WSL, you can install a Linux distro.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-videos.techidaily.com/new-create-compelling-animation-subscribe-bars-for-your-youtube-channel-filmora/"><u>[New] Create Compelling Animation Subscribe Bars for Your YouTube Channel (Filmora)</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-detailed-survey-gecatas-game-capture-utility-for-2024/"><u>[New] Detailed Survey  Gecata's Game Capture Utility for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-mastering-youtube-video-cuts-a-beginners-guide/"><u>[New] In 2024, Mastering YouTube Video Cuts  A Beginner's Guide</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-in-2024-optimizing-your-project-b-roll-utilization-tips/"><u>[New] In 2024, Optimizing Your Project  B-Roll Utilization Tips</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-saving-linkedin-videos-made-easy-with-this-6-app-selection-guide/"><u>[New] In 2024, Saving LinkedIn Videos Made Easy with This 6-App Selection Guide</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-in-2024-unveiling-the-secrets-of-medical-ad-success-on-fb/"><u>[New] In 2024, Unveiling the Secrets of Medical Ad Success on FB</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-masterclass-in-capturing-conversations-for-later-review/"><u>[New] Masterclass in Capturing Conversations for Later Review</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-how-to-dominate-the-viral-video-edit-scene-on-tiktok/"><u>[Updated] 2024 Approved  How to Dominate the Viral Video Edit Scene on TikTok</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-a-detailed-comparison-vsdc-vs-other-recorders/"><u>[Updated] A Detailed Comparison  VSDC vs Other Recorders</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-insights-into-instagram-an-in-depth-analysis-guide-for-professionals/"><u>[Updated] In 2024, Insights Into Instagram  An In-Depth Analysis Guide for Professionals</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-choosing-a-font-for-impactful-youtube-credits/"><u>2024 Approved  Choosing a Font for Impactful YouTube Credits</u></a></li>
<li><a href="https://extra-resources.techidaily.com/6-competitive-video-apps-as-periscope-substitutes/"><u>6 Competitive Video Apps as Periscope Substitutes</u></a></li>
<li><a href="https://windows11.techidaily.com/6-ways-to-recover-an-off-screen-window-in-windows-10-and-11/"><u>6 Ways to Recover an Off-Screen Window in Windows 10 and 11</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-11-unable-to-load-driver-errors/"><u>Addressing Windows 11: Unable to Load Driver Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-onedrives-abode-in-the-windows-11-ecosystem/"><u>Adjusting OneDrive's Abode in the Windows 11 Ecosystem</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-file-sorting-empowering-checkbox-selection-in-win11/"><u>Advanced File Sorting: Empowering Checkbox Selection in Win11</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/all-you-need-to-know-about-teslas-upcoming-robotaxi-price-predictions-specs-and-launch-timeline/"><u>All You Need to Know About Tesla's Upcoming Robotaxi: Price Predictions, Specs & Launch Timeline</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-anarchy-how-to-heal-fractured-win11-registry-elements/"><u>Avoiding Anarchy: How to Heal Fractured Win11 Registry Elements</u></a></li>
<li><a href="https://win-able.techidaily.com/beat-the-blitz-prevent-war-thunder-from-crashing-this-year-with-proven-solutions/"><u>Beat the Blitz: Prevent War Thunder From Crashing This Year with Proven Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-an-everlasting-bin-for-deletion-in-the-windows-interface/"><u>Configuring an Everlasting Bin for Deletion in the Windows Interface</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/crafting-a-vocal-identity-steps-for-impactful-video-overdubs/"><u>Crafting a Vocal Identity  Steps for Impactful Video Overdubs</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-edge-techniques-for-launching-programs-in-windows/"><u>Cutting-Edge Techniques for Launching Programs in Windows</u></a></li>
<li><a href="https://fox-helps.techidaily.com/delving-into-historical-masterpieces-without-copyrights-for-2024/"><u>Delving Into Historical Masterpieces without Copyrights for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/detailed-guide-to-dollar-counts-a-stepwise-strategy-to-track-youtube-earnings-for-2024/"><u>Detailed Guide to Dollar Counts  A Stepwise Strategy to Track YouTube Earnings for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-windows-watcher-functionality/"><u>Disabling Windows Watcher Functionality</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-and-update-samsung-960-evo-ssd-drive-software-on-windows-pc/"><u>Download & Update Samsung 960 EVO SSD Drive Software on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/download-adobe-reader-seamlessly-with-microsoft-store/"><u>Download Adobe Reader Seamlessly with Microsoft Store</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-aggregatorhostexe-in-windows-how-it-works-and-safety-aspects/"><u>Exploring AggregatorHost.exe in Windows: How It Works and Safety Aspects</u></a></li>
<li><a href="https://windows11.techidaily.com/free-windows-11-slideshows-the-seventh-way-unveiled/"><u>Free Windows 11 Slideshows - The Seventh Way Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/from-handheneld-to-hardware-android-titles-on-windows-via-google-service/"><u>From Handheneld to Hardware: Android Titles on Windows via Google Service</u></a></li>
<li><a href="https://games-able.techidaily.com/gaming-on-steroids-keychron-and-lemokey-reviewed/"><u>Gaming on Steroids: Keychron & Lemokey Reviewed</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-google-frp-lock-from-xiaomi-13t-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock from Xiaomi 13T Devices</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-do-honor-magic-5-screen-sharing-drfone-by-drfone-android/"><u>How To Do Honor Magic 5 Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-turn-off-chrome-prompts-windows-users/"><u>How to Turn Off Chrome Prompts Windows Users</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-vivo-s17e-to-other-android-devices-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Vivo S17e to Other Android Devices Devices? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-samsung-galaxy-s23plus-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Snapchat Location Spoofer to Protect Your Privacy On Samsung Galaxy S23+? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-7-phone-number-locators-to-track-nokia-c110-location-drfone-by-drfone-virtual-android/"><u>In 2024, Top 7 Phone Number Locators To Track Nokia C110 Location | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/infographic-mind-numbing-youtube-factsfigures-and-statistics-2017-for-2024/"><u>Infographic - Mind Numbing YouTube Facts,Figures and Statistics 2017 for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windowed-play-top-6-windows-11-fps-counters/"><u>Mastering Windowed Play: Top 6 Windows 11 FPS Counters</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-lav-filters-a-comprehensive-guide-to-effective-use-in-windows/"><u>Mastery Over LAV Filters: A Comprehensive Guide to Effective Use in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-printer-sharing-challenges-in-windows/"><u>Navigating Printer Sharing Challenges in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-to-resolve-winerror-0x8007043c/"><u>Navigating to Resolve WinError 0X8007043C</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/new-unlocking-global-audiences-top-video-language-converters/"><u>New Unlocking Global Audiences Top Video Language Converters</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-error-0x80300024-in-windows-xp/"><u>Overcoming Error 0X80300024 in Windows XP</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-video-lag-during-steam-livestreams/"><u>Overcoming Video Lag During Steam Livestreams</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-tips-for-windows-camera-glitches/"><u>Quick-Fix Tips for Windows Camera Glitches</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reliable-user-guide-to-fix-samsung-galaxy-m54-5g-running-slow-and-freezing-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reliable User Guide to Fix Samsung Galaxy M54 5G Running Slow and Freezing | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-original-settings-post-deletion-win-11/"><u>Restoring Original Settings Post Deletion (Win 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-support-functionality-in-windows-11-help/"><u>Restoring Support Functionality in Windows 11 Help</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-windows-sluggish-discord-overlay-performance/"><u>Reviving Windows' Sluggish Discord Overlay Performance</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/seamless-streams-expert-guide-to-facebook-screen-sharing/"><u>Seamless Streams  Expert Guide to Facebook Screen Sharing</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-memory-integrity-with-win11-tweaks-and-tricks/"><u>Securing Memory Integrity with Win11 Tweaks & Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/slowing-down-the-high-life-excess-in-windowed-worlds/"><u>Slowing Down the High Life Excess in Windowed Worlds</u></a></li>
<li><a href="https://windows11.techidaily.com/software-selection-showdown-on-windows-choc-vs-wm/"><u>Software Selection Showdown on Windows: Choc vs WM</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-effortlessly-switch-between-windows-terminal-focus-and-normal-states/"><u>Steps to Effortlessly Switch Between Windows Terminal Focus and Normal States</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-tasks-in-windows-11-with-a-customized-run-command-setup/"><u>Streamline Tasks in Windows 11 with a Customized Run Command Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-your-windows-11-program-choices/"><u>Streamlining Your Windows 11 Program Choices</u></a></li>
<li><a href="https://windows11.techidaily.com/supercharge-performance-conquering-windows-lag-issues/"><u>Supercharge Performance: Conquering Windows Lag Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-to-troubleshoot-loaded-lol-screens/"><u>Tactics to Troubleshoot Loaded LOL Screens</u></a></li>
<li><a href="https://windows11.techidaily.com/the-8-different-ways-to-restart-your-windows-computer/"><u>The 8 Different Ways to Restart Your Windows Computer</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-magnificent-art-of-pokemon-go-streaming-on-oneplus-12r-drfone-by-drfone-virtual-android/"><u>The Magnificent Art of Pokemon Go Streaming On OnePlus 12R? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-silent-sounds-on-windows-devices/"><u>Troubleshooting Silent Sounds on Windows Devices</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/unova-stone-pokemon-go-evolution-list-and-how-catch-them-for-apple-iphone-11-drfone-by-drfone-virtual-ios/"><u>Unova Stone Pokémon Go Evolution List and How Catch Them For Apple iPhone 11 | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/video-fixer-software-for-all-corrupt-videos-of-huawei-mate-x5-by-stellar-video-repair-mobile-video-repair/"><u>Video Fixer Software for all Corrupt Videos of Huawei Mate X5</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-right-click-customization-compatibility-tool-inclusion/"><u>Windows Right-Click Customization: Compatibility Tool Inclusion</u></a></li>
</ul></div>
