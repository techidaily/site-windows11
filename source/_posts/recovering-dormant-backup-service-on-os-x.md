---
title: Recovering Dormant Backup Service on OS X
date: 2024-09-14T19:05:38.539Z
updated: 2024-09-20T19:50:49.470Z
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

## 3\. Run the Check Disk Utility

 Drive issues can cause Windows system backup VSS errors to occur, with codes like 0x807800A1 or 0x80042315\. In this case, running the Check Disk utility to scan for and address hard drive issues, such as bad sectors, is a potential fix for the Volume Shadow Copy Service not working. Check out this [guide to running the CHKDSK utility](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) for further details about how you can apply this potential resolution.

![The CHKDSK command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/chkdsk-scan-command.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037356/7443" target="_top" id="2037356">
  <img src="//a.impactradius-go.com/display-ad/7443-2037356" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037356/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Disable Antivirus Shields

 Sometimes third-party antivirus software can interfere with and prevent Volume Shadow Copy from functioning correctly. So, try disabling third-party antivirus shields before attempting to back up or restore Windows. The usual way to do that is to right-click on an antivirus app’s system tray icon and select a disable/turn off shield protection option from there.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 Don’t leave your antivirus shield permanently disabled. If possible, select to disable it for a few hours before attempting the backup or system restoration operation again. Or manually re-enable your antivirus if you can’t select a temporary option.

## 5\. Disable Any Active Firewalls

 It’s also recommended to disable the firewall component of a third-party antivirus utility before attempting to perform a VSS operation. Turning off an antivirus shield won’t disable a firewall component. Look for firewall settings within your antivirus software’s tabs to see if it includes one. If it does, select to turn off the firewall.

 Try turning off the Windows firewall if you haven’t installed a third-party antivirus utility or firewall software. Check out this guide to [disabling Microsoft Defender Firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) for instructions for turning off that security component.

![The Turn off Windows Defender Firewall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-firewall-settings.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938677/19272" target="_top" id="1938677">
  <img src="//a.impactradius-go.com/display-ad/19272-1938677" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938677/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Set Windows to Perform a Clean Boot

![The Startup type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-tab.jpg)

 Conflicting background apps or services are another potential cause of Volume Shadow Copy errors. Third-party backup utilities with snapshot managers are the most likely software packages to conflict with the Volume Shadow Copy Service. If you know you’ve installed a third-party backup manager, uninstalling it could be the best way to ensure it doesn’t cause any conflicts.

 However, you can [perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) to stop third-party apps and services from starting with Windows to prevent conflicts from arising. This involves disabling startup items and services with Task Manager and MSConfig and restarting Windows. Then try utilizing the Windows Backup and Restore or System Restore tools after clean booting your PC to see if the VSS error persists.

 If it does, this means something you disabled during the clean boot is causing the problem. Now you can slowly re-enable each app until the problem reappears, then either uninstall or update the offending app.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148644/16836" target="_top" id="2148644">
  <img src="//a.impactradius-go.com/display-ad/16836-2148644" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148644/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://vp-tips.techidaily.com/new-in-2024-complete-roadmap-implementing-subtitle-track-within-mp4s/"><u>[New] In 2024, Complete Roadmap Implementing Subtitle Track Within MP4s</u></a></li>
<li><a href="https://youtube-data.techidaily.com/approved-streamlining-access-to-subscriber-information/"><u>2024 Approved Streamlining Access to Subscriber Information</u></a></li>
<li><a href="https://techtrends.techidaily.com/a-comprehensive-guide-on-utilizing-the-internet-archives-wayback-machine/"><u>A Comprehensive Guide on Utilizing the Internet Archive's Wayback Machine</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-microsofts-phone-link-for-android-usage-guide/"><u>Exploring Microsoft's Phone Link for Android: Usage Guide</u></a></li>
<li><a href="https://sound-issues.techidaily.com/google-hangouts-sound-failures-heres-how-you-can-get-your-mic-working-again/"><u>Google Hangouts Sound Failures? Here's How You Can Get Your Mic Working Again</u></a></li>
<li><a href="https://driver-download.techidaily.com/1722974820474-hp-envy-amo-5055-essential-drives-download-without-hassle/"><u>HP Envy Amo 5055 Essential Drives - Download Without Hassle</u></a></li>
<li><a href="https://win11.techidaily.com/is-your-wireless-mouse-not-working-on-windows-8-ways-to-fix-it/"><u>Is Your Wireless Mouse Not Working on Windows? 8 Ways to Fix It</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-between-google-share-and-windows-direct-network-links/"><u>Navigating Between Google Share and Windows Direct Network Links</u></a></li>
<li><a href="https://windows11.techidaily.com/revel-in-easy-entry-unlocking-windows-11s-application-archive/"><u>Revel in Easy Entry: Unlocking Windows 11'S Application Archive</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/reverse-your-videos-with-the-best-online-tools-for-2024/"><u>Reverse Your Videos with the Best Online Tools for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/seamlessly-blend-windows-11-and-android-top-6-integrative-apps/"><u>Seamlessly Blend Windows 11 and Android: Top 6 Integrative Apps</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/the-artisans-touch-skillfully-applying-face-centric-motion-blur-using-picsart/"><u>The Artisan’s Touch Skillfully Applying Face-Centric Motion Blur Using Picsart</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-and-overcoming-errorinvalidargument-in-wsl/"><u>Unraveling and Overcoming ERROR_INVALID_ARGUMENT in WSL</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-hurdles-apps-with-dull-facades-draining-energy/"><u>Windows 11 Hurdles: Apps With Dull Facades Draining Energy</u></a></li>
</ul></div>

