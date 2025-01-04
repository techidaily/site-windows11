---
title: Eliminating Non-Functional Behavior of CCleaner in Windows
date: 2024-12-31T04:32:52.209Z
updated: 2025-01-04T01:04:16.655Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eliminating Non-Functional Behavior of CCleaner in Windows
excerpt: This Article Describes Eliminating Non-Functional Behavior of CCleaner in Windows
keywords: CCleaner Efficiency,Functional Fixes Win,Remove Unused Clutter,Optimize PC Cleanliness,Eliminate Window Errors,Enhancing System Speed,Non-Functional Behavior Removal
thumbnail: https://thmb.techidaily.com/fa549a8f4ea78a6f19c6043f8b4168f45b8a02a01f09c9a4cfb746e3a5491976.jpg
---

## Eliminating Non-Functional Behavior of CCleaner in Windows

 CCleaner is one of the most widely utilized third-party system maintenance software packages for Windows 10 and 11 PCs. However, some users have reported on help forums they can’t utilize CCleaner because it’s not working for them. The CCleaner window doesn’t open when that software isn’t working.

 Many users report CCleaner not responding when they click to open that software. However, this Piriform software can also fail to start with error messages. This is how you can fix CCleaner not working on your Windows 11/10 PC.

## 1\. Try Opening CCleaner From Its Installation Directory

 Many users open CCleaner with desktop, taskbar, or Start menu shortcuts. However, CCleaner might not launch because of an issue with its shortcut. So, try opening CCleaner directly from its installation folder to see if that makes any difference. To do so, you’ll need to double-click the **CCleaner64.exe** application file within the software’s installation directory.

![The CCleaner.exe file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/ccleaner-exe-file.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=heERQcpMi77lqToE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gOyLy8DeizY?si=GkAmK0hChZw6_2tW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Add CCleaner to Your Antivirus Software’s Exceptions List

 Antivirus programs that flag CCleaner as unwanted software can block that app from running. That’s more likely considering that this Piriform software has had its malware incidents in the past. Microsoft Defender was widely reported to flag CCleaner as unwanted software in 2020\. Some users have also confirmed disabling Trend Micro antivirus fixed CCleaner not working on their PCs.

 So, you might need to add CCleaner’s installation folder to your antivirus software’s exceptions list to fix that app not working. Our [guide to setting Windows Security exclusions](https://www.makeuseof.com/windows-11-security-exclusions/) provides guidelines for whitelisting software from the Microsoft Defender antivirus. If you utilize a third-party security app, add CCleaner to that software’s antivirus exclusion list.

![The Add an exclusion button in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/add-an-exclusion-button.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n4cc4BSqJls?si=Hkd9vwQDqeCGN7XG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Disable Your Active Firewalls

 CCleaner needs internet connectivity for updates, bug reporting, and its online features. Therefore, firewall blocks can be another cause for CCleaner not working. Disabling your PC’s firewall will ensure that it isn’t blocking CCleaner’s internet connectivity.

 This guide for [disabling Microsoft Defender Firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) provides full instructions for turning off that firewall protection. Users with third-party firewalls installed can select to turn them off via their settings tabs. If you’ve installed third-party antivirus software, disable its firewall component if it has one.

![The Turn off Windows Defender Firewall options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/turn-off-windows-defender-firewall3.jpg)

 Run CCleaner after turning off the firewall on your PC. The firewall was most likely causing the issue if the CCleaner software works when it's disabled. Add CCleaner to your firewall’s allowed app list to utilize that software with the firewall enabled. Our article about [allowing apps through the Windows firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) tells you how to add programs to Microsoft Defender Firewall’s allowed list.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wNhKhWc0wLc?si=1XLYV0sXV52Xc0lu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Run CCleaner After Clean-Booting Windows

 An app conflicting with the Piriform software could be another possible reason for CCleaner not working on your PC. Clean-booting Windows 11/10 will likely eliminate that potential cause. Setting a clean boot will disable most third-party startup programs and services that run in the background. Clean boot is like entering Windows safe mode, but it doesn’t disable any device drivers.

 To apply this possible solution for CCleaner not working, follow the instructions in this [how-to perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) guide. Restart Windows after disabling startup items via Task Manager and MSConfig, and then try opening CCleaner again. If the CCleaner software works after the clean boot, a disabled app or service is likely the culprit.

![The Services tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/services-tab4.jpg)

 What you do then is up to you. You can leave the boot setup as set or try to find out what was conflicting with the CCleaner software. To find what’s causing the issue, re-enable disabled startup items in a one-at-a-time fashion before every reboot until CCleaner stops working again. Then either permanently disable or uninstall the conflicting service or app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bXmwwSmYqq4?si=Bb-eJfLnlpeeClyt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 7\. Reinstall CCleaner

 If CCleaner still isn’t working after applying the other troubleshooting methods in this guide, you might have to reinstall the software. This will refresh all CCleaner’s files and registry entries. You can remove CCleaner with most of the methods outlined in this article about [uninstalling Windows software](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/). We recommend uninstalling with one of the best uninstaller utilities to remove all leftover debris.

![The Uninstall option for CCleaner](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/programs-and-features-applet.jpg)

 You can reinstall a CCleaner UWP or desktop app. To get the desktop app, click **Free Download** on this [CCleaner page](https://www.anrdoezrs.net/links/7251228/type/dlg/sid/UUmuoUeUpU2029956/https://www.ccleaner.com/ccleaner/download?ppc%5Fcode=012&ppc=a&gclsrc=aw.ds&gclid=CjwKCAjwu4WoBhBkEiwAojNdXkgjDRZcy77PTMyhMnePxm%5FBXllDabqSn%5FMd9yAkWVbfhL5dYhBFjBoCYbYQAvD%5FBwE). Double-click the **ccsetup615.exe** file in the folder it downloads to view the setup window. Then you can click **Install** within the setup wizard to reinstall CCleaner.

 If you want to try the UWP app instead, open the [CCleaner Microsoft Store page](https://apps.microsoft.com/store/detail/ccleaner/XPFCWP0SQWXM3V), click on the **Get in Store app**, and **Open Microsoft Store** options to access an installation option for CCleaner. Press the **Install** button for the app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hHPljBHrvkA?si=HwdfDM9rlbABSIrx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://youtube-blog.techidaily.com/tep-by-step-guide-to-elevating-video-presence-through-thumbnails-for-2024/"><u>[New] Step-by-Step Guide to Elevating Video Presence Through Thumbnails for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-enriching-videos-with-no-cost-sounds-legally/"><u>[Updated] In 2024, Enriching Videos with No-Cost Sounds Legally</u></a></li>
<li><a href="https://windows11.techidaily.com/a-step-by-step-for-erasing-sign-in-email-in-win/"><u>A Step-By-Step for Erasing Sign-In Email in Win</u></a></li>
<li><a href="https://fox-access.techidaily.com/background-beats-guide-tunes-for-visuals-for-2024/"><u>Background Beats Guide Tunes for Visuals for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-endorsed-top-10-for-windows-free-app-safety/"><u>Expert-Endorsed Top 10 for Windows FREE App Safety</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-videos-from-infinix-gt-10-pro-by-fonelab-android-recover-video/"><u>How to retrieve erased videos from Infinix GT 10 Pro</u></a></li>
<li><a href="https://hardware-help.techidaily.com/hp-officejet-pro-groovy-get-your-printer-drivers-for-windows-11108/"><u>HP OfficeJet Pro Groovy: Get Your Printer Drivers for Windows [11/10/8]</u></a></li>
<li><a href="https://windows11.techidaily.com/keeping-notes-prominent-on-windows-10-and-11/"><u>Keeping Notes Prominent on Windows 10 & 11</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/mastering-the-challenges-of-uploading-and-streaming-in-4k-on-youtube-a-comprehensive-guide/"><u>Mastering the Challenges of Uploading and Streaming in 4K on YouTube: A Comprehensive Guide</u></a></li>
<li><a href="https://blog-min.techidaily.com/pcm/"><u>PCM音声ファイル再生手順とトラブルシューティング</u></a></li>
<li><a href="https://windows11.techidaily.com/proactive-upgrade-implementing-tpm-and-secure-boot-on-w11-systems/"><u>Proactive Upgrade: Implementing TPM and Secure Boot on W11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaim-shift-control-with-easy-fixes/"><u>Reclaim Shift Control with Easy Fixes</u></a></li>
<li><a href="https://fake-location.techidaily.com/spoofing-life360-how-to-do-it-on-samsung-galaxy-a23-5g-drfone-by-drfone-virtual-android/"><u>Spoofing Life360 How to Do it on Samsung Galaxy A23 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/steering-clear-of-windows-11-blunders-top-8-tips/"><u>Steering Clear of Windows 11 Blunders: Top 8 Tips</u></a></li>
<li><a href="https://solve-outstanding.techidaily.com/step-by-step-tutorial-on-preparing-and-reformatting-a-macs-internal-and-external-drives-for-optimal-performance/"><u>Step-by-Step Tutorial on Preparing and Reformatting a Mac's Internal & External Drives for Optimal Performance</u></a></li>
</ul></div>

