---
title: Recovering Dormant Backup Service on OS X
date: 2025-01-20T19:59:50.824Z
updated: 2025-01-22T16:57:03.828Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/May-pLCUkEA?si=PGlcFZAlsp3S3beI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-type-drop-down-menu.jpg)
5. Press **Start** in the Volume Shadow Copy Service window.

6. Click on the service window’s **Apply** and **OK** buttons to set the changed options.
7. Repeat steps three to six for the Microsoft Software Shadow Copy Provider service.
8. Also, check that the RPC Endpoint Mapper and DCOM Server Process dependency services for Volume Shadow Copy are enabled and running.

 Restart those shadow copy services if they’re already set as required. You can do that by right-clicking on those services and selecting the Restart context menu options for them.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=3YDfzJAZMDp1gFRz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Repair Your System Files With the SFC and DISM Commands

 Corrupted system files can affect Windows services, such as Volume Shadow Copy. So, some users may need to repair system files to fix the Volume Shadow Copy Service when it’s not working. You can do that by running System File Checker and Deployment Image Servicing Management scans, as covered in this article about [repairing corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/).

![The sfc scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/sfc-scannow-error.jpg)

## 3\. Run the Check Disk Utility

 Drive issues can cause Windows system backup VSS errors to occur, with codes like 0x807800A1 or 0x80042315\. In this case, running the Check Disk utility to scan for and address hard drive issues, such as bad sectors, is a potential fix for the Volume Shadow Copy Service not working. Check out this [guide to running the CHKDSK utility](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) for further details about how you can apply this potential resolution.

![The CHKDSK command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/chkdsk-scan-command.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LBCobAYzzcc?si=J3eSTQ3AdyxWAjGo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/BR4gsW-J7as?si=9a56UDKZKhREZnwz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Set Windows to Perform a Clean Boot

![The Startup type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-tab.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Un9G2_OdSRI?si=vAcGbco8DuWt4ypP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://youtube-tips.techidaily.com/n-2024-crafting-a-youtube-video-essential-writing-guide/"><u>[New] In 2024, Crafting a YouTube Video Essential Writing Guide</u></a></li>
<li><a href="https://youtube-web.techidaily.com/aximizing-your-youtube-income-through-understanding-cpm/"><u>[New] Maximizing Your YouTube Income Through Understanding CPM</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-in-2024-top-pick-unlimited-valorant-sound-transformation-tool-free/"><u>[Updated] In 2024, Top Pick Unlimited Valorant Sound Transformation Tool (Free)</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-viral-video-ventures-crafting-addictive-loops-on-ig/"><u>[Updated] Viral Video Ventures Crafting Addictive Loops on IG</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-harmonizing-different-footage-sources-on-ios-device/"><u>2024 Approved Harmonizing Different Footage Sources on iOS Device</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-mastering-text-overlays-on-digital-pictures/"><u>2024 Approved Mastering Text Overlays on Digital Pictures</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-tips-for-trimming-down-facebook-vids-intrusions/"><u>2024 Approved Tips for Trimming Down Facebook Vids' Intrusions</u></a></li>
<li><a href="https://solve-popular.techidaily.com/automatische-dokumentverarbeitung-in-wilmington-mit-abbyy-software/"><u>Automatische Dokumentverarbeitung in Wilmington Mit ABBYY Software</u></a></li>
<li><a href="https://fox-links.techidaily.com/best-overlay-strategies-for-videographers-for-2024/"><u>Best Overlay Strategies for Videographers for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-disabled-trash-can-symbol-on-win11-os/"><u>Mending Disabled Trash Can Symbol on Win11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-stop-vmware-blue-screen-in-win11/"><u>Strategies to Stop VMware Blue Screen in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-prolong-windows-10-closure-with-ongoing-processes/"><u>Techniques to Prolong Windows 10 Closure with Ongoing Processes</u></a></li>
<li><a href="https://windows11.techidaily.com/top-9-pc-advantages-over-macs/"><u>Top 9: PC Advantages Over Macs</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-required-items-not-met-in-win11win11/"><u>Troubleshooting Required Items Not Met in Win11/Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/why-choose-dxvk-a-game-changer-on-your-windows-system/"><u>Why Choose DXVK: A Game Changer on Your Windows System?</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-meets-virtual-box-70-a-detailed-guide-for-the-tech-savvy/"><u>Windows 11 Meets Virtual Box 7.0: A Detailed Guide for the Tech-Savvy</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-reclaiming-precise-search-functionality/"><u>Windows 11: Reclaiming Precise Search Functionality</u></a></li>
</ul></div>

