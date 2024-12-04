---
title: Recovering Dormant Backup Service on OS X
date: 2024-12-01T22:48:52.713Z
updated: 2024-12-04T01:12:13.887Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Recovering Dormant Backup Service on OS X
excerpt: This Article Describes Recovering Dormant Backup Service on OS X
keywords: OS X Recovery Services,Backup Restoration OS,OS X Data Rescue,Dormant Backup Fix OSX,Mac OS Backup Service,OS X Backup Service Revival,Reactivate OS X Backups
thumbnail: https://thmb.techidaily.com/207578e24a0a184b7539ba9edecf41bf44046bb6668830fc6d1ed96db57dfa6c.png
---

## Recovering Dormant Backup Service on OS X

 If the Volume Shadow Copy service isn't working, you'll see error messages when you try to use Backup and Restore or System Restore in Windows. We'll show you how you can fix Volume Shadow Copy when it's not working on a Windows PC, so you can get your backups going once more.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xg3PHS_Ee80?si=fE_iGIqHjKvWFIN3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

## 2\. Repair Your System Files With the SFC and DISM Commands

 Corrupted system files can affect Windows services, such as Volume Shadow Copy. So, some users may need to repair system files to fix the Volume Shadow Copy Service when it’s not working. You can do that by running System File Checker and Deployment Image Servicing Management scans, as covered in this article about [repairing corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/).

![The sfc scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/sfc-scannow-error.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/szUqw4TLvWs?si=srv1OeLOe579gLwj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RBN1gYY5hUs?si=p89CMiMzeJzU0wGu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Run the Check Disk Utility

 Drive issues can cause Windows system backup VSS errors to occur, with codes like 0x807800A1 or 0x80042315\. In this case, running the Check Disk utility to scan for and address hard drive issues, such as bad sectors, is a potential fix for the Volume Shadow Copy Service not working. Check out this [guide to running the CHKDSK utility](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) for further details about how you can apply this potential resolution.

![The CHKDSK command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/chkdsk-scan-command.jpg)

## 4\. Disable Antivirus Shields

 Sometimes third-party antivirus software can interfere with and prevent Volume Shadow Copy from functioning correctly. So, try disabling third-party antivirus shields before attempting to back up or restore Windows. The usual way to do that is to right-click on an antivirus app’s system tray icon and select a disable/turn off shield protection option from there.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6xGqSETroqA?si=4C1GPgXi-AksR_oO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Don’t leave your antivirus shield permanently disabled. If possible, select to disable it for a few hours before attempting the backup or system restoration operation again. Or manually re-enable your antivirus if you can’t select a temporary option.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FATJWpNYmio?si=72ugPTb3vJXz6cAM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Disable Any Active Firewalls

 It’s also recommended to disable the firewall component of a third-party antivirus utility before attempting to perform a VSS operation. Turning off an antivirus shield won’t disable a firewall component. Look for firewall settings within your antivirus software’s tabs to see if it includes one. If it does, select to turn off the firewall.

 Try turning off the Windows firewall if you haven’t installed a third-party antivirus utility or firewall software. Check out this guide to [disabling Microsoft Defender Firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) for instructions for turning off that security component.

![The Turn off Windows Defender Firewall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-firewall-settings.jpg)

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
<li><a href="https://youtube-videos.techidaily.com/new-erasing-extra-borders-for-smooth-youtube-playback/"><u>[New] Erasing Extra Borders for Smooth YouTube Playback</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-kids-car-clubbing-capers/"><u>[New] In 2024, Kids' Car Clubbing Capers</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-2024-approved-chromebook-audio-revamp-guide-selecting-the-leading-speech-converters-online/"><u>[Updated] 2024 Approved Chromebook Audio Revamp Guide Selecting the Leading Speech Converters Online</u></a></li>
<li><a href="https://windows11.techidaily.com/from-obscurity-back-to-the-desktop-restoring-deleted-files-on-windows/"><u>From Obscurity Back To the Desktop: Restoring Deleted Files on Windows</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/24-peeking-at-the-reason-behind-highlighted-comments-on-youtube/"><u>In 2024, Peeking at the Reason Behind Highlighted Comments on YouTube</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-reset-itunes-backup-password-of-apple-iphone-14-pro-max-prevention-and-solution-drfone-by-drfone-ios/"><u>In 2024, Reset iTunes Backup Password Of Apple iPhone 14 Pro Max Prevention & Solution | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mitigating-high-tiworkerexe-cpu-load-in-os/"><u>Mitigating High TiWorker.exe CPU Load in OS</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-the-admin-labyrinth-of-windows/"><u>Navigating Through the Admin Labyrinth of Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionize-your-speech-recording-experience-with-shortcuts-in-win-11/"><u>Revolutionize Your Speech Recording Experience with Shortcuts in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/simple-steps-to-activate-classic-photo-viewer-in-modern-windows-1111/"><u>Simple Steps to Activate Classic Photo Viewer in Modern Windows 11/11</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/solving-common-youtube-issues-effective-strategies-and-hacks/"><u>Solving Common YouTube Issues: Effective Strategies & Hacks</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-ultimate-test-chatgpt-vs-innovative-ai-claude/"><u>The Ultimate Test: ChatGPT Vs. Innovative AI Claude</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-premium-windows-laptops-of-year-2024/"><u>Unveiling the Premium Windows Laptops of Year 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/where-is-the-best-place-to-catch-dratini-on-nokia-c12-drfone-by-drfone-virtual-android/"><u>Where Is the Best Place to Catch Dratini On Nokia C12 | Dr.fone</u></a></li>
</ul></div>

