---
title: Reviving Erased Run Commands Logs
date: 2024-08-08T06:13:34.746Z
updated: 2024-08-09T06:13:34.746Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reviving Erased Run Commands Logs
excerpt: This Article Describes Reviving Erased Run Commands Logs
keywords: Command Log Recovery,Run Commands Restoration,Deleted Command Reinstate,Command Log Revival,Rebooted Commands Fixing,Erased Command Tracking,Redeeming Lost Logs
thumbnail: https://thmb.techidaily.com/a50833de398a016d5f4384db8ba343a7a22c031d122aae5cba2e71718d3b50f6.jpg
---

## Reviving Erased Run Commands Logs

 The Run command dialog box in Windows makes it easy to launch apps, access system tools, and perform various other tasks. It also has an auto-complete feature that makes it easy to re-use your commands later. However, the auto-complete feature in the Run tool may not work if it fails to save your command history in the first place.

 If you're encountering a similar problem, don’t fret. Below, we share some quick and useful tips that should get the Run tool to save your history once again.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Check Your Privacy Settings

 A common reason why Windows may not save the Run command history is if you have previously blocked it from tracking your app launches. Here’s how you can change that.

1. Press **Win + I** to open the Settings app.
2. Select **Privacy & security** from the left sidebar.
3. Under Windows permissions, click on **General**.
4. Enable the toggle next to **Let Windows improve Start and search results by tracking app launches**.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
![Allow Windows to Track App Launches on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-windows-to-track-app-launches-on-windows.jpg)

 After completing the above steps, try running a few commands via the Run dialog box. Then, check if it is saving your command history and providing auto-complete suggestions.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. Edit Registry Files

 Is the **Let Windows improve Start and search results by tracking app launches** option grayed out on your PC? If so, you can take help from the Registry Editor to get Windows to save your Run command history.

 As you may already be aware, registry files on your PC store essential settings for Windows and its services. Making incorrect modifications to these files can render your system inoperable. Hence, it’s a good idea to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

1. Click the search icon on the taskbar or press the **Win + S** keyboard shortcut to open the search menu.
2. Type **registry editor** in the search box and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_CURRENT\_USER > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer > Advanced**.
5. Locate the **Start\_TrackProgs** entry in the right pane. If you can’t find it, right-click on the **Advanced** key and select **New > DWORD (32-bit) Value**. Rename it to **Start\_TrackProgs**.
6. Double-click the newly created DWORD and enter **1** in the **Value data** field.
7. Click **OK**.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Edit Registry DWORD on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/edit-registry-dword-on-windows.jpg)

 Restart your PC after this for the changes to take effect. Following this, the Run command should start saving your history on Windows.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Apply Generic Fixes

 If the problem persists even after implementing the above tips, you can try applying some basic fixes to resolve the underlying issue.

* **Restart Your PC:** This may appear rudimentary, but temporary OS-related glitches can sometimes cause such anomalies. If it’s nothing major, [restarting your PC](https://www.makeuseof.com/windows-restart-methods/) should fix any issues with the Run command.
* **Run an SFC Scan:** Such issues can also arise if some of the critical system files on your PC are corrupt. [Running a System File Checker (SFC) scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) can help detect and repair any damaged system files on your PC.
* **Scan for Malware:** It’s possible that your system is infected by malware, which is why the Run command is having trouble saving your history. To rule out this possibility, you can [scan Windows for malware using PowerShell](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/) or Windows Defender.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4742929&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/boxshot(2).png" border="0">Kanto Player Professional</a>
<!-- affiliate ads end -->
## Get the Run Tool to Save Your History on Windows

 It can be inconvenient if the Run command dialog box stops saving your history on Windows. Hopefully, one of the solutions provided above has successfully resolved the issue for you.

 If you feel that the Run utility in Windows lacks advanced features, you can always switch to alternative tools like Run-Command or PowerToys Run.

 If you're encountering a similar problem, don’t fret. Below, we share some quick and useful tips that should get the Run tool to save your history once again.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-adopting-new-norms-analyzing-changes-in-social-media-with-tiktok-vs-snapchat/"><u>[New] 2024 Approved  Adopting New Norms  Analyzing Changes in Social Media with TikTok Vs Snapchat</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-how-to-add-music-to-imovie-from-youtube-for-2024/"><u>[New] How to Add Music to iMovie From YouTube for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-a-step-by-step-aspect-ratio-guide-for-youtube-creators/"><u>[New] In 2024, A Step-by-Step Aspect Ratio Guide for YouTube Creators</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-facebooks-countdown-the-best-10-music-videos-of-now/"><u>[Updated] 2024 Approved  Facebook's Countdown  The Best 10 Music Videos of Now</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-timeless-treasures-accessing-fbs-historic-stories/"><u>[Updated] 2024 Approved  Timeless Treasures  Accessing FB's Historic Stories</u></a></li>
<li><a href="https://windows11.techidaily.com/11-fixes-if-windows-11-cant-detect-a-wi-fi-network/"><u>11 Fixes if Windows 11 Can’t Detect a Wi-Fi Network</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-quantum-realms-unraveling-new-worlds-with-10-sci-fi-titles/"><u>2024 Approved  Quantum Realms  Unraveling New Worlds with 10 Sci-Fi Titles</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-the-key-to-smooth-segments-crossfade-logic-pro-steps/"><u>2024 Approved  The Key to Smooth Segments  Crossfade Logic Pro Steps</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-unlocking-the-art-of-iphone-podcast-downloads-with-ease/"><u>2024 Approved  Unlocking the Art of iPhone Podcast Downloads with Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/a-deep-dive-into-winning-windows-captures-with-printscreen-or-snip-tool/"><u>A Deep Dive Into Winning Windows Captures with Printscreen or Snip Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/accessing-windows-11s-screen-capture-shortcut/"><u>Accessing Windows 11'S Screen Capture Shortcut</u></a></li>
<li><a href="https://windows11.techidaily.com/adapting-to-new-gear-your-powertoys-configuration-guide/"><u>Adapting To New Gear: Your PowerToys Configuration Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-steam-vac-denial-for-gaming-sessions/"><u>Addressing Steam VAC Denial for Gaming Sessions</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-why-files-cant-sync-in-steam-library/"><u>Addressing Why Files Can't Sync in Steam Library</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-11-system-call-failures-quickly/"><u>Addressing Windows 11 System Call Failures Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-silencing-windows-11-alerts-benefits-unveiled/"><u>Avoid Silencing Windows 11 Alerts: Benefits Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/banish-os-requirement-warning-labels-in-windows-11/"><u>Banish OS Requirement Warning Labels in Windows 11</u></a></li>
<li><a href="https://vp-tips.techidaily.com/basketball-enthusiasts-guide-to-online-viewing/"><u>Basketball Enthusiast's Guide to Online Viewing</u></a></li>
<li><a href="https://windows11.techidaily.com/beat-windows-timer-troubles-reclaim-control/"><u>Beat Windows Timer Troubles, Reclaim Control</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-steam-auth-blocks-in-rust-on-windows-devices/"><u>Breaking Down Steam Auth Blocks in Rust on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/bridging-windows-prefixes-with-microsoft-services/"><u>Bridging Windows Prefixes with Microsoft Services</u></a></li>
<li><a href="https://windows11.techidaily.com/bypass-the-troubleshooter-effective-fixes-in-vista-and-7/"><u>Bypass the Troubleshooter: Effective Fixes in Vista & 7</u></a></li>
<li><a href="https://fox-info.techidaily.com/clean-slates-mastering-the-eraser-tool-in-photoshop/"><u>Clean Slates  Mastering the Eraser Tool in Photoshop</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-tutorial-downloading-and-setting-up-msixbundle-and-msix-file-types/"><u>Comprehensive Tutorial: Downloading & Setting Up Msixbundle & MSIX File Types</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-immediate-failure-effective-strategies-to-tackle-onedrive-folder-issues-on-pc/"><u>Conquering Immediate Failure: Effective Strategies to Tackle OneDrive Folder Issues on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-common-errors-in-windows-onedrive/"><u>Correcting Common Errors in Windows' OneDrive</u></a></li>
<li><a href="https://windows11.techidaily.com/creating-personalized-music-cds-with-mp3s-a-compreenasive-guide-for-windows-users-imgburn/"><u>Creating Personalized Music CDs with Mp3s: A Compreenasive Guide for Windows Users (ImgBurn)</u></a></li>
<li><a href="https://windows11.techidaily.com/critiquing-7-perplexing-windows-11-aesthetics/"><u>Critiquing 7 Perplexing Windows 11 Aesthetics</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/cultural-insights-into-french-greetings-for-travelers-and-residents-alike/"><u>Cultural Insights Into French Greetings for Travelers & Residents Alike</u></a></li>
<li><a href="https://windows11.techidaily.com/curing-white-screen-problems-on-store-platform/"><u>Curing White Screen Problems on Store Platform</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-runtime-broker-its-essential-role-in-operating-systems/"><u>Decoding Runtime Broker: Its Essential Role in Operating Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-windows-error-code-31-and-network-adapter-issues/"><u>Demystifying Windows Error Code 31 and Network Adapter Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-windows-aggregatehostexe-its-functionality-and-dangers/"><u>Demystifying Windows' AggregateHost.exe: Its Functionality & Dangers</u></a></li>
<li><a href="https://windows11.techidaily.com/desk-clean-up-restoring-windows-11-desktop-symbols/"><u>Desk Clean-Up: Restoring Windows 11 Desktop Symbols</u></a></li>
<li><a href="https://windows11.techidaily.com/diagnosing-voice-commands-malfunction-in-valorant-games/"><u>Diagnosing Voice Commands Malfunction in Valorant Games</u></a></li>
<li><a href="https://windows11.techidaily.com/differences-between-cloud-based-windows-installations/"><u>Differences Between Cloud-Based Windows Installations</u></a></li>
<li><a href="https://windows11.techidaily.com/direct-routes-to-windows-11s-user-authorization-screen/"><u>Direct Routes to Windows 11'S User Authorization Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-ways-to-free-disk-space-without-deleting-windows-11-files-max-156-chars/"><u>Discover Ways to Free Disk Space Without Deleting Windows 11 Files (Max 156 Chars)</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-tecno-pova-6-pro-5gwithwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Tecno Pova 6 Pro 5Gwith/without a PC</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-a-quick-guide-to-vivo-y100-frp-bypass-instantly-by-drfone-android/"><u>In 2024, A Quick Guide to Vivo Y100 FRP Bypass Instantly</u></a></li>
<li><a href="https://iphone-location.techidaily.com/in-2024-how-to-fix-the-apple-iphone-14-gps-not-working-issue-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Fix the Apple iPhone 14 GPS not Working Issue | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-display-adjustment-overcoming-overscan/"><u>Mastering Windows Display Adjustment: Overcoming Overscan</u></a></li>
<li><a href="https://driver-install.techidaily.com/quick-reinstall-how-to-setup-bluetooth-drivers-on-win-1011/"><u>Quick Reinstall: How To Setup Bluetooth Drivers on Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/1719293537225-resurrect-your-chrome-on-win11-with-ease/"><u>Resurrect Your Chrome on Win11 with Ease</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>