---
title: Overcoming CCleaner Issues in Windows 11
date: 2024-07-11T21:36:19.215Z
updated: 2024-07-12T21:36:19.215Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming CCleaner Issues in Windows 11
excerpt: This Article Describes Overcoming CCleaner Issues in Windows 11
keywords: Fixing CCleaner on Win11,CCleaner Troubleshooting Windows 11,Resolve Win11 CCleaner Errors,Fix Win11 CCleaner Issues,Addressing CCleaner in Windows 11,Tackle Win11 CCleaner Glitches,Overcoming CCleaner on Windows 11
thumbnail: https://thmb.techidaily.com/fbf47cff7f90b38c5c4bfba881d1b7d8a9950edbba1743d545a40ebc632bb6c9.jpg
---

## Overcoming CCleaner Issues in Windows 11

 CCleaner is one of the most widely utilized third-party system maintenance software packages for Windows 10 and 11 PCs. However, some users have reported on help forums they can’t utilize CCleaner because it’s not working for them. The CCleaner window doesn’t open when that software isn’t working.

 Many users report CCleaner not responding when they click to open that software. However, this Piriform software can also fail to start with error messages. This is how you can fix CCleaner not working on your Windows 11/10 PC.

## 1\. Try Opening CCleaner From Its Installation Directory

 Many users open CCleaner with desktop, taskbar, or Start menu shortcuts. However, CCleaner might not launch because of an issue with its shortcut. So, try opening CCleaner directly from its installation folder to see if that makes any difference. To do so, you’ll need to double-click the **CCleaner64.exe** application file within the software’s installation directory.

![The CCleaner.exe file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/ccleaner-exe-file.jpg)

 If you can launch CCleaner from the installation directory, there must be an issue with the shortcut for opening that software. In this case, set up a new Windows desktop shortcut by right-clicking the CCleaner EXE file and selecting **Send to (Desktop)**. Then try opening the software with the new CCleaner shortcut.

## 2\. Run CCleaner With Administrator Rights

 It’s not usually an essential requirement to run CCleaner with admin rights for that software to work. However, sometimes CCleaner can fail to start because of permissions issues that running it as an administrator might address. You can quickly see if this potential resolution works by right-clicking CCleaner’s shortcut or the EXE file in the installation directory and selecting **Run as administrator**.

 If that works, set CCleaner to always run with elevated privileges. Then you won’t need to manually select to run CCleaner with admin rights every time you need to open it. This guide about [how to always run apps as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) includes instructions for permanently setting programs to start with elevated privileges.

![The RUn this program as an administrator checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/run-this-program-as-adminstrator-option.jpg)

## 3\. Delete the CCleanerx64 Registry Key

 Many users have confirmed they’ve fixed CCleaner not working by deleting a CCleanerx64 registry key. Although a confirmed fix, we still recommend backing up the Windows registry before deleting keys. Then erase the CCleaner registry key as follows:

1. First, hold the **Windows** logo key and press **R** to start the Run accessory.
2. Type **regedit** into Run’s **Open** command box and click **O**K.
3. Then go to this registry location either by entering it into the address bar or by clicking the keys in the sidebar:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options`  
![The Image File Execution Options registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-image-file-executions-key.jpg)
4. Right-click on the **CCleaner64.exe** key and select **Delete**.  
![The Delete context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/delete-ccleaner.jpg)
5. Select **Yes** on the Confirm Key Delete window prompt.
6. Click the Registry Editor app’s **X** Close window button and try opening CCleaner.

## 4\. Add CCleaner to Your Antivirus Software’s Exceptions List

 Antivirus programs that flag CCleaner as unwanted software can block that app from running. That’s more likely considering that this Piriform software has had its malware incidents in the past. Microsoft Defender was widely reported to flag CCleaner as unwanted software in 2020\. Some users have also confirmed disabling Trend Micro antivirus fixed CCleaner not working on their PCs.

 So, you might need to add CCleaner’s installation folder to your antivirus software’s exceptions list to fix that app not working. Our [guide to setting Windows Security exclusions](https://www.makeuseof.com/windows-11-security-exclusions/) provides guidelines for whitelisting software from the Microsoft Defender antivirus. If you utilize a third-party security app, add CCleaner to that software’s antivirus exclusion list.

![The Add an exclusion button in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/add-an-exclusion-button.jpg)

## 5\. Disable Your Active Firewalls

 CCleaner needs internet connectivity for updates, bug reporting, and its online features. Therefore, firewall blocks can be another cause for CCleaner not working. Disabling your PC’s firewall will ensure that it isn’t blocking CCleaner’s internet connectivity.

 This guide for [disabling Microsoft Defender Firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) provides full instructions for turning off that firewall protection. Users with third-party firewalls installed can select to turn them off via their settings tabs. If you’ve installed third-party antivirus software, disable its firewall component if it has one.

![The Turn off Windows Defender Firewall options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/turn-off-windows-defender-firewall3.jpg)

 Run CCleaner after turning off the firewall on your PC. The firewall was most likely causing the issue if the CCleaner software works when it's disabled. Add CCleaner to your firewall’s allowed app list to utilize that software with the firewall enabled. Our article about [allowing apps through the Windows firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) tells you how to add programs to Microsoft Defender Firewall’s allowed list.

## 6\. Run CCleaner After Clean-Booting Windows

 An app conflicting with the Piriform software could be another possible reason for CCleaner not working on your PC. Clean-booting Windows 11/10 will likely eliminate that potential cause. Setting a clean boot will disable most third-party startup programs and services that run in the background. Clean boot is like entering Windows safe mode, but it doesn’t disable any device drivers.

 To apply this possible solution for CCleaner not working, follow the instructions in this [how-to perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) guide. Restart Windows after disabling startup items via Task Manager and MSConfig, and then try opening CCleaner again. If the CCleaner software works after the clean boot, a disabled app or service is likely the culprit.

![The Services tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/services-tab4.jpg)

 What you do then is up to you. You can leave the boot setup as set or try to find out what was conflicting with the CCleaner software. To find what’s causing the issue, re-enable disabled startup items in a one-at-a-time fashion before every reboot until CCleaner stops working again. Then either permanently disable or uninstall the conflicting service or app.

## 7\. Reinstall CCleaner

 If CCleaner still isn’t working after applying the other troubleshooting methods in this guide, you might have to reinstall the software. This will refresh all CCleaner’s files and registry entries. You can remove CCleaner with most of the methods outlined in this article about [uninstalling Windows software](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/). We recommend uninstalling with one of the best uninstaller utilities to remove all leftover debris.

![The Uninstall option for CCleaner](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/programs-and-features-applet.jpg)

 You can reinstall a CCleaner UWP or desktop app. To get the desktop app, click **Free Download** on this [CCleaner page](https://www.anrdoezrs.net/links/7251228/type/dlg/sid/UUmuoUeUpU2029956/https://www.ccleaner.com/ccleaner/download?ppc%5Fcode=012&ppc=a&gclsrc=aw.ds&gclid=CjwKCAjwu4WoBhBkEiwAojNdXkgjDRZcy77PTMyhMnePxm%5FBXllDabqSn%5FMd9yAkWVbfhL5dYhBFjBoCYbYQAvD%5FBwE). Double-click the **ccsetup615.exe** file in the folder it downloads to view the setup window. Then you can click **Install** within the setup wizard to reinstall CCleaner.

 If you want to try the UWP app instead, open the [CCleaner Microsoft Store page](https://apps.microsoft.com/store/detail/ccleaner/XPFCWP0SQWXM3V), click on the **Get in Store app**, and **Open Microsoft Store** options to access an installation option for CCleaner. Press the **Install** button for the app.

## Clean Up Your PC With CCleaner Again

 There’s no guaranteed way to fix CCleaner not working. However, the troubleshooting methods above will probably kick-start the CCleaner software for Windows 11/10 in most cases. Then you can clean up your Windows 11/10 PC with all the tools CCleaner has to offer again.

 Many users report CCleaner not responding when they click to open that software. However, this Piriform software can also fail to start with error messages. This is how you can fix CCleaner not working on your Windows 11/10 PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/remedying-pc-performance-hurdles-with-intel-graphics-updates/"><u>Remedying PC Performance Hurdles with Intel Graphics Updates</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/1714316007212-new-2024-approved-top-rated-quicktime-editors-free-and-easy-to-use/"><u>New 2024 Approved Top Rated QuickTime Editors Free and Easy to Use</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-for-inverted-keyboard-input-windows/"><u>Quick Fix for Inverted Keyboard Input Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-how-to-stop-game-proposals/"><u>Win11: How To Stop Game Proposals</u></a></li>
<li><a href="https://windows11.techidaily.com/cost-effective-solutions-affordable-windows-11-key-access/"><u>Cost-Effective Solutions: Affordable Windows 11 Key Access</u></a></li>
<li><a href="https://windows11.techidaily.com/timeless-upgrades-essential-time-saver-tools-for-pcs/"><u>Timeless Upgrades: Essential Time Saver Tools for PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/the-artisans-approach-to-high-dynamic-range-mastery-on-windows-11/"><u>The Artisan’s Approach to High Dynamic Range Mastery on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/1719258336470-escalate-emulation-faster-yuzu-win-users/"><u>Escalate Emulation: Faster Yuzu, WIN Users!</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-2024-approved-integrate-music-files-with-sony-vegas-pro-projects/"><u>New 2024 Approved Integrate Music Files with Sony Vegas Pro Projects</u></a></li>
<li><a href="https://windows11.techidaily.com/automate-image-display-7-clever-strategies-for-windows-11/"><u>Automate Image Display: 7 Clever Strategies for Windows 11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-gopro-hero5-footage-analysis/"><u>[New] GoPro Hero5 Footage Analysis</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/in-2024-uncover-the-best-green-screen-software-for-mac-video-editing/"><u>In 2024, Uncover the Best Green Screen Software for Mac Video Editing</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-zippyzoom-echoframe-capture-for-2024/"><u>[New] ZippyZoom EchoFrame Capture for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-system-shutdown-alerts-due-to-roblox-glitches/"><u>Overcoming System Shutdown Alerts Due to Roblox Glitches</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-11-zoom-malfunction-1132/"><u>Overcoming Windows 11 Zoom Malfunction #1132</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-can-oppo-a18mirror-share-to-pc-drfone-by-drfone-android/"><u>In 2024, How Can Oppo A18Mirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/revive-lost-control-secrets-for-steam-in-windows/"><u>Revive Lost Control: Secrets for Steam in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-default-usb-suspension-on-windows-11/"><u>Overcoming Default USB Suspension on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooters-and-their-role-on-windows-11-systems/"><u>Troubleshooters and Their Role on Windows 11 Systems</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-genuine-tiktok-following-where-to-safely-invest-yourself/"><u>[New] Genuine TikTok Following  Where to Safely Invest Yourself</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-realme-note-50-drfone-by-drfone-virtual/"><u>In 2024, 9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Realme Note 50 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/perfecting-the-process-setting-up-msoffice-in-windows-11/"><u>Perfecting the Process: Setting Up MSOffice in Windows 11</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-in-depth-study-of-cartoon-painting-starts-for-2024/"><u>New In-Depth Study of Cartoon Painting Starts for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/supporting-the-unsupported-life-after-windows-781/"><u>Supporting the Unsupported: Life After Windows 7/8.1</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-in-2024-for-students-discover-the-top-10-historical-youtube-channels-now/"><u>[Updated] In 2024, For Students, Discover the Top 10 Historical YouTube Channels Now</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-audacity-paudio-operations-in-windows-os/"><u>Streamlining Audacity PAudio Operations in Windows OS</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-access-your-iphone-15-when-you-forget-the-passcode-drfone-by-drfone-ios/"><u>In 2024, How to Access Your iPhone 15 When You Forget the Passcode? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-separate-bunched-system-icons/"><u>Strategies to Separate Bunched System Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/zap-zaps-revitalizing-a-sluggish-windows-11-experience/"><u>Zap Zaps: Revitalizing a Sluggish Windows 11 Experience</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-free-software-showdown-the-leading-10-audio-capture-utilities/"><u>2024 Approved  Free Software Showdown  The Leading 10 Audio Capture Utilities</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-advanced-audio-cleanup-tactics-to-remove-unwanted-elements-from-your-video-content/"><u>New Advanced Audio Cleanup Tactics to Remove Unwanted Elements From Your Video Content</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-storing-error-during-new-app-installation/"><u>Solutions for Storing Error During New App Installation</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-turn-off-find-my-iphone-6s-plus-when-phone-is-broken-drfone-by-drfone-ios/"><u>How to Turn Off Find My iPhone 6s Plus when Phone is Broken? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-vivo-s18e-drfone-by-drfone-virtual-android/"><u>How PGSharp Save You from Ban While Spoofing Pokemon Go On Vivo S18e? | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-step-by-step-guide-to-cutting-edge-unboxing/"><u>In 2024, Step-by-Step Guide to Cutting-Edge Unboxing</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-call-history-from-realme-c51-by-fonelab-android-recover-call-logs/"><u>Easy steps to recover deleted call history from Realme C51</u></a></li>
<li><a href="https://windows11.techidaily.com/volume-vanishing-act-top-remedies-for-muted-keys-in-windows/"><u>Volume Vanishing Act? Top Remedies for Muted Keys in Windows</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/sony-digital-camcorder-video-post-production-made-easy/"><u>Sony Digital Camcorder Video Post-Production Made Easy</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-in-2024-4-methods-how-to-make-a-recap-video/"><u>Updated In 2024, 4 Methods How To Make a Recap Video</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-upcoming-moment-anticipated-new-features/"><u>Windows 11'S Upcoming Moment: Anticipated New Features</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-camera-app-malfunctions-windows-0xa00f429f-error/"><u>Overcoming Camera App Malfunctions: Windows' 0XA00F429F Error</u></a></li>
<li><a href="https://windows11.techidaily.com/combat-the-frustration-7-methods-for-restoring-windows-notepad/"><u>Combat the Frustration: 7 Methods for Restoring Window's Notepad</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-partedpicture-breakdown/"><u>In 2024, PartedPicture Breakdown</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-non-existent-device-alerts-on-windows-1011/"><u>Resolving Non-Existent Device Alerts on Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-stopping-auto-recommended-game-suggestion/"><u>Steps for Stopping Auto-Recommended Game Suggestion</u></a></li>
<li><a href="https://windows11.techidaily.com/changing-home-screen-settings-without-start-menu/"><u>Changing Home Screen Settings Without Start Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/breach-ethernet-speed-barriers-past-windows-100mbps-ceiling/"><u>Breach Ethernet Speed Barriers: Past Windows' 100Mbps Ceiling</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-flipping-the-script-on-instagrams-video-content-for-2024/"><u>[New] Flipping the Script on Instagram's Video Content for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/turn-your-windows-11-pc-into-a-self-contained-internet-station/"><u>Turn Your Windows 11 PC Into a Self-Contained Internet Station</u></a></li>
<li><a href="https://windows11.techidaily.com/ultimate-7-list-cost-free-windows-media-centers/"><u>Ultimate 7 List: Cost-Free Windows Media Centers</u></a></li>
<li><a href="https://windows11.techidaily.com/1719348778059-troubleshooting-wwinplusp-glitch-on-pc-solutions-included/"><u>Troubleshooting: WWin+P Glitch on PC, Solutions Included!</u></a></li>
<li><a href="https://windows11.techidaily.com/taskbar-chatting-feature-in-windows-11-user-implications/"><u>Taskbar Chatting Feature in Windows 11: User Implications</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-error-0x887a0006-on-windows-devices/"><u>Addressing Error 0X887A0006 on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-keyboard-magic-custom-shortcuts-w11-style/"><u>Tailored Keyboard Magic: Custom Shortcuts W11 Style</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/how-to-find-facebook-recently-watched-videos-for-2024/"><u>How to Find Facebook Recently Watched Videos for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-simplified-processes-for-adobe-presenter-video-saves-for-2024/"><u>[Updated] Simplified Processes for Adobe Presenter Video Saves for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-the-battle-against-windows-software-problems-7-ways/"><u>Winning the Battle Against Windows Software Problems (7 Ways)</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-2024-approved-the-ultimate-technique-for-noiseless-iphone-movies/"><u>New 2024 Approved The Ultimate Technique for Noiseless iPhone Movies</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-tailored-fit-videos-the-key-to-great-instagram-posts/"><u>[New] In 2024, Tailored-Fit Videos  The Key to Great Instagram Posts</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-ftdibussys-the-impact-on-windows-memory-standards-and-safety/"><u>Unraveling ftdibus.sys: The Impact on Windows' Memory Standards and Safety</u></a></li>
<li><a href="https://windows11.techidaily.com/winrars-corrected-compression-overcoming-sum-errors/"><u>WinRAR's Corrected Compression: Overcoming Sum Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-failed-jvm-launch-windows-guide/"><u>Remedying Failed JVM Launch: Windows Guide</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/filter-not-working-error-in-excel-2023-fix-2024-stellar-by-stellar-guide/"><u>Filter Not Working Error in Excel 2023 Fix 2024 | Stellar</u></a></li>
<li><a href="https://windows11.techidaily.com/sync-software-unlocking-the-fourfold-compatibility-troubleshooter/"><u>Sync Software: Unlocking the Fourfold Compatibility Troubleshooter</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/how-to-spy-on-text-messages-from-computer-and-apple-iphone-14-pro-max-drfone-by-drfone-virtual-ios/"><u>How to Spy on Text Messages from Computer & Apple iPhone 14 Pro Max | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-overview-of-the-best-realme-10t-5g-screen-mirroring-app-drfone-by-drfone-android/"><u>In 2024, Overview of the Best Realme 10T 5G Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-erroneous-non-existing-device-alert-on-win-11/"><u>Overcoming Erroneous Non-Existing Device Alert on Win 11</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-quick-route-to-joy-embracing-the-ifunny-meme-app/"><u>In 2024, The Quick Route to Joy  Embracing the iFunny Meme App</u></a></li>
<li><a href="https://windows11.techidaily.com/quelling-overzealousness-after-a-peak-life-period-on-windows/"><u>Quelling Overzealousness After a Peak Life Period on Windows</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-top-5-vivo-y17s-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>In 2024, Top 5 Vivo Y17s Bypass FRP Tools for PC That Actually Work</u></a></li>
</ul></div>
