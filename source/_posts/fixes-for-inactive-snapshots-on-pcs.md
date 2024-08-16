---
title: Fixes for Inactive Snapshots on PCs
date: 2024-08-15T15:54:49.271Z
updated: 2024-08-16T15:54:49.271Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixes for Inactive Snapshots on PCs
excerpt: This Article Describes Fixes for Inactive Snapshots on PCs
keywords: Fix PC Inactive Snapshots,Active Snapshots Resolution,Preventing Snapshot Failures,Troubleshoot PC Snapshots,Activating Stale PC Snaps,Enable Snapshots on PCs,Eliminate Inactive Snapshots
thumbnail: https://thmb.techidaily.com/4703b9d657812b3886216df90e44b1d9ef5fb3878b6869f4909ce7c65740d3ae.jpg
---

## Fixes for Inactive Snapshots on PCs

 If the Volume Shadow Copy service isn't working, you'll see error messages when you try to use Backup and Restore or System Restore in Windows. We'll show you how you can fix Volume Shadow Copy when it's not working on a Windows PC, so you can get your backups going once more.

## 1\. Enable and Start Volume Shadow Copy Services

 VSS errors can often arise because the Volume Shadow Copy and Microsoft Software Shadow Copy Provider services aren’t enabled or running. For example, many users have confirmed enabling those services can fix VSS error codes 0x81000202 and 0x81000203, which affect the System Restore tool. So, you may be able to resolve numerous Volume Shadow Copy errors by enabling VSS services like this:

1. First, press the **Windows** logo key + **S** and enter a Services search phrase to find that app.
2. Click **Services** inside the search results.
3. Double-click the **Volume Shadow Copy Service**.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/services-window.jpg)
4. Click the drop-down menu labeled **Startup type** and select **Automatic** if the service is set differently.  
![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-type-drop-down-menu.jpg)
5. Press **Start** in the Volume Shadow Copy Service window.
6. Click on the service window’s **Apply** and **OK** buttons to set the changed options.
7. Repeat steps three to six for the Microsoft Software Shadow Copy Provider service.
8. Also, check that the RPC Endpoint Mapper and DCOM Server Process dependency services for Volume Shadow Copy are enabled and running.

 Restart those shadow copy services if they’re already set as required. You can do that by right-clicking on those services and selecting the Restart context menu options for them.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Repair Your System Files With the SFC and DISM Commands

 Corrupted system files can affect Windows services, such as Volume Shadow Copy. So, some users may need to repair system files to fix the Volume Shadow Copy Service when it’s not working. You can do that by running System File Checker and Deployment Image Servicing Management scans, as covered in this article about [repairing corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/).

![The sfc scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/sfc-scannow-error.jpg)

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Run the Check Disk Utility

 Drive issues can cause Windows system backup VSS errors to occur, with codes like 0x807800A1 or 0x80042315\. In this case, running the Check Disk utility to scan for and address hard drive issues, such as bad sectors, is a potential fix for the Volume Shadow Copy Service not working. Check out this [guide to running the CHKDSK utility](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) for further details about how you can apply this potential resolution.

![The CHKDSK command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/chkdsk-scan-command.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->
## 4\. Disable Antivirus Shields

 Sometimes third-party antivirus software can interfere with and prevent Volume Shadow Copy from functioning correctly. So, try disabling third-party antivirus shields before attempting to back up or restore Windows. The usual way to do that is to right-click on an antivirus app’s system tray icon and select a disable/turn off shield protection option from there.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 Don’t leave your antivirus shield permanently disabled. If possible, select to disable it for a few hours before attempting the backup or system restoration operation again. Or manually re-enable your antivirus if you can’t select a temporary option.

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Disable Any Active Firewalls

 It’s also recommended to disable the firewall component of a third-party antivirus utility before attempting to perform a VSS operation. Turning off an antivirus shield won’t disable a firewall component. Look for firewall settings within your antivirus software’s tabs to see if it includes one. If it does, select to turn off the firewall.

 Try turning off the Windows firewall if you haven’t installed a third-party antivirus utility or firewall software. Check out this guide to [disabling Microsoft Defender Firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) for instructions for turning off that security component.

![The Turn off Windows Defender Firewall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-firewall-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->

## 6\. Set Windows to Perform a Clean Boot

![The Startup type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-tab.jpg)

 Conflicting background apps or services are another potential cause of Volume Shadow Copy errors. Third-party backup utilities with snapshot managers are the most likely software packages to conflict with the Volume Shadow Copy Service. If you know you’ve installed a third-party backup manager, uninstalling it could be the best way to ensure it doesn’t cause any conflicts.

 However, you can [perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) to stop third-party apps and services from starting with Windows to prevent conflicts from arising. This involves disabling startup items and services with Task Manager and MSConfig and restarting Windows. Then try utilizing the Windows Backup and Restore or System Restore tools after clean booting your PC to see if the VSS error persists.

 If it does, this means something you disabled during the clean boot is causing the problem. Now you can slowly re-enable each app until the problem reappears, then either uninstall or update the offending app.

## Back up and Restore Windows Again

 These solutions can potentially resolve many variable Volume Shadow Copy Service error messages and codes that pop up during system backup and restore operations. With Volume Shadow Copy fixed, you can back up and restore Windows with built-in system tools again.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-webster.techidaily.com/024-approved-decoding-digital-dynamics-unveiling-the-secret-sauce-for-youtube-success-and-revenue/"><u>[New] 2024 Approved  Decoding Digital Dynamics  Unveiling the Secret Sauce for YouTube Success & Revenue</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-unmatched-video-downloads-top-8/"><u>[New] 2024 Approved  Unmatched Video Downloads  Top 8</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-crafting-content-for-insta-clout-a-9-step-playbook-for-fame/"><u>[New] Crafting Content for Insta Clout  A 9-Step Playbook for Fame</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-deciding-on-the-best-upgrade-for-your-4k-vision/"><u>[New] Deciding on the Best Upgrade for Your 4K Vision</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-ultimate-selection-8-must-have-laptop-backgrounds/"><u>[New] Ultimate Selection  8 Must-Have Laptop Backgrounds</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-rethinking-streaming-new-platforms-challenge-obs-for-2024/"><u>[Updated] Rethinking Streaming  New Platforms Challenge OBS for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-step-by-step-guide-to-facebook-mastery-pro-and-novice-edition-for-2024/"><u>[Updated] Step-by-Step Guide to Facebook Mastery  Pro & Novice Edition for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-timeless-stop-motion-gems-in-the-top-15/"><u>[Updated] Timeless Stop-Motion Gems in the Top 15</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-best-applications-for-transforming-photo-content-into-video/"><u>2024 Approved  Best Applications for Transforming Photo Content Into Video</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-pinnacle-choices-superior-mac-apps-for-grabbing-videos/"><u>2024 Approved  Pinnacle Choices  Superior Mac Apps for Grabbing Videos</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-unpacking-presenter-8s-features-against-the-best/"><u>2024 Approved  Unpacking Presenter 8’S Features Against the Best</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-error-code-963-on-google-play-of-infinix-hot-30-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Error Code 963 on Google Play Of Infinix Hot 30 5G | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-honor-100-pro-by-drfone-android/"><u>AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Honor 100 Pro</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/child-friendly-alarms-redefined-in-depth-analysis-of-the-mirari-wake-up-device/"><u>Child-Friendly Alarms Redefined: In-Depth Analysis of the Mirari Wake-Up Device</u></a></li>
<li><a href="https://video-capture.techidaily.com/customizing-teams-background-priorpost-meeting/"><u>Customizing Teams Background Prior/Post-Meeting</u></a></li>
<li><a href="https://activate-lock.techidaily.com/easy-tutorial-for-activating-icloud-from-iphone-x-safe-and-legal-by-drfone-ios/"><u>Easy Tutorial for Activating iCloud from iPhone X Safe and Legal</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/elevate-your-tiktok-videos-speedy-filming-secrets-for-2024/"><u>Elevate Your TikTok Videos  Speedy Filming Secrets for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/elite-screening-pacts-how-to-choose-a-cms-for-2024/"><u>Elite Screening Pacts  How to Choose a CMS for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-win-compatibility-troubleshooting-guide/"><u>Expert Tips: Win Compatibility Troubleshooting Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-windows-pathways-to-filefolder-secrets/"><u>Expert Windows Pathways to File/Folder Secrets</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-error-0x8019-in-windows-updates/"><u>Fixing Error 0X8019 in Windows Updates</u></a></li>
<li><a href="https://unlock-android.techidaily.com/forgot-pattern-lock-heres-how-you-can-unlock-honor-70-lite-5g-pattern-lock-screen-by-drfone-android/"><u>Forgot Pattern Lock? Heres How You Can Unlock Honor 70 Lite 5G Pattern Lock Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/from-novice-to-pro-mastering-github-desktop-on-windows-11/"><u>From Novice to Pro: Mastering GitHub Desktop on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/hide-or-show-clock-secrets-of-the-taskbar/"><u>Hide or Show Clock - Secrets of the Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-activatedeactivate-vm-security-with-secure-boot-on-virtualbox-70/"><u>How to Activate/Deactivate VM Security with Secure Boot on VirtualBox 7.0</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-without-jailbreak-on-realme-12-pro-5g-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location without Jailbreak On Realme 12 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-stop-win11-from-showing-00-error-codes/"><u>How to Stop Win11 From Showing 00 Error Codes</u></a></li>
<li><a href="https://windows11.techidaily.com/ideal-choices-premium-windows-systems-for-switch-gaming/"><u>Ideal Choices: Premium Windows Systems for Switch Gaming</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-catchemall-celebrate-national-pokemon-day-with-virtual-location-on-apple-iphone-14-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, CatchEmAll Celebrate National Pokémon Day with Virtual Location On Apple iPhone 14 Pro | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-master-meeting-magic-key-ways-to-tweak-with-zoom-converter/"><u>In 2024, Master Meeting Magic  Key Ways to Tweak with Zoom Converter</u></a></li>
<li><a href="https://buynow-info.techidaily.com/leading-storm-watch-applications-of-2024-find-your-perfect-match/"><u>Leading Storm Watch Applications of 2024: Find Your Perfect Match</u></a></li>
<li><a href="https://windows11.techidaily.com/leap-ahead-in-workflow-management-embrace-flow-launcher-advantage/"><u>Leap Ahead in Workflow Management: Embrace Flow Launcher Advantage</u></a></li>
<li><a href="https://windows11.techidaily.com/managing-windows-modules-installer-resource-demand/"><u>Managing Windows Modules Installer Resource Demand</u></a></li>
<li><a href="https://windows11.techidaily.com/master-note-taking-on-win11-easy-as-pie/"><u>Master Note-Taking on Win11, Easy as Pie</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-1drive-operation-restoration-in-windows-os/"><u>Mastering 1Drive Operation Restoration in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-inter-system-file-transfer-with-nearby-share-protocols/"><u>Mastering Inter-System File Transfer with Nearby Share Protocols</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-sefx-windows-11-sfx-creation/"><u>Mastering SEFX: Windows 11 SFX Creation</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-xbox-live-service-recovery-steps/"><u>Mastering Xbox Live Service Recovery Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-windows-x709-problems/"><u>Mending Windows X709 Problems</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/merging-markets-youtube-and-brand-collaboration-concepts-for-2024/"><u>Merging Markets  YouTube and Brand Collaboration Concepts for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/navigating-network-growth-strategies-for-instagram-success/"><u>Navigating Network Growth  Strategies for Instagram Success</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-the-windows-and-wsl-harmony-in-post-update-phase/"><u>Navigating Through The Windows & WSL Harmony in Post-Update Phase</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-fcp-x-effects-made-simple-a-quick-3-step-tutorial/"><u>New In 2024, FCP X Effects Made Simple A Quick 3-Step Tutorial</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-say-goodbye-to-clutter-how-to-convert-your-dvd-library-to-digital-files/"><u>New In 2024, Say Goodbye to Clutter How to Convert Your DVD Library to Digital Files</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-microphone-performance-with-xbox-app-windows-11/"><u>Optimizing Microphone Performance with Xbox App Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-grayscale-windows-backdrops-tips-for-enhancement/"><u>Overcoming Grayscale Windows Backdrops: Tips for Enhancement</u></a></li>
<li><a href="https://windows11.techidaily.com/preventive-measures-for-csgo-launch-woes-on-windows-11/"><u>Preventive Measures for CS:GO Launch Woes on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-lsa-errors-on-windows-pcs/"><u>Quick Fixes for LSA Errors on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/reducing-the-heat-lowering-cpu-consumption-in-setups/"><u>Reducing the Heat: Lowering CPU Consumption in Setups</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-issues-for-microsoft-store-access-on-windows-11/"><u>Resolving Issues for Microsoft Store Access on Windows 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/securing-comfort-in-vr-experiences/"><u>Securing Comfort in VR Experiences</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/sim-unlock-sony-xperia-10-v-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>Sim Unlock Sony Xperia 10 V Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solution-for-when-your-usb-and-hdmi-adapter-fails/"><u>Step-by-Step Solution for When Your USB and HDMI Adapter Fails</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-ax201-wi-fi-6-error-on-windows/"><u>Steps to Resolve AX201 Wi-Fi 6 Error on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-windows-app-start-counter/"><u>Stop Windows App Start Counter</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-account-associations-between-win-and-microsoft/"><u>Streamlining Account Associations Between WIN and MICROSOFT</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-calls-using-intel-unison-with-windows-11-pcs/"><u>Streamlining Calls: Using Intel Unison with Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-development-essential-wsl-2-tips-for-pcs/"><u>Streamlining Development: Essential WSL 2 Tips for PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/systematic-steps-for-nullifying-your-windows-drive-partitions/"><u>Systematic Steps for Nullifying Your Windows Drive Partitions</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-deal-with-missing-values-on-pcs-running-winos/"><u>Techniques to Deal with Missing Values on PCs Running WinOS</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/top-15-apps-to-hack-wifi-password-on-nokia-g22-by-drfone-android/"><u>Top 15 Apps To Hack WiFi Password On Nokia G22</u></a></li>
<li><a href="https://windows11.techidaily.com/transforming-file-system-visibility-on-modern-windows-pcs/"><u>Transforming File System Visibility on Modern Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-overcoming-key-issues-on-win11/"><u>Understanding and Overcoming Key Issues on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-hidden-potential-in-vintage-video-gaming-titles-using-retroarch/"><u>Unlocking Hidden Potential in Vintage Video Gaming Titles Using Retroarch</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-microsoft-family-safety-potential/"><u>Unlocking Microsoft Family Safety Potential</u></a></li>
<li><a href="https://windows11.techidaily.com/unmasking-windows-not-found-top-fixes-and-strategies/"><u>Unmasking Windows 'Not Found': Top Fixes and Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-vivetool-enable-unseen-features-on-windows-pcs/"><u>Unraveling ViVeTool: Enable Unseen Features on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/what-is-the-0x0000003b-bsod-in-windows-heres-how-to-fix-it/"><u>What Is the 0X0000003B BSOD in Windows? Here's How to Fix It</u></a></li>
<li><a href="https://windows11.techidaily.com/workaround-for-win10-and-11s-audacity-device-opening-issue/"><u>Workaround for Win10 & 11’S Audacity Device Opening Issue</u></a></li>
</ul></div>
