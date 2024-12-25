---
title: Recovering Dormant Backup Service on OS X
date: 2024-12-19T17:49:04.135Z
updated: 2024-12-25T17:37:30.393Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5OmJZ4Z8jgk?si=YIoEaPI8geoiFSYE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Repair Your System Files With the SFC and DISM Commands

 Corrupted system files can affect Windows services, such as Volume Shadow Copy. So, some users may need to repair system files to fix the Volume Shadow Copy Service when it’s not working. You can do that by running System File Checker and Deployment Image Servicing Management scans, as covered in this article about [repairing corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/).

![The sfc scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/sfc-scannow-error.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15Ju8Cb4UZ8?si=5wdiQXdz1BOxIkDH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K7fATC_lI7o?si=UFotPJqflDRZr-mv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Run the Check Disk Utility

 Drive issues can cause Windows system backup VSS errors to occur, with codes like 0x807800A1 or 0x80042315\. In this case, running the Check Disk utility to scan for and address hard drive issues, such as bad sectors, is a potential fix for the Volume Shadow Copy Service not working. Check out this [guide to running the CHKDSK utility](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) for further details about how you can apply this potential resolution.

![The CHKDSK command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/chkdsk-scan-command.jpg)

## 4\. Disable Antivirus Shields

 Sometimes third-party antivirus software can interfere with and prevent Volume Shadow Copy from functioning correctly. So, try disabling third-party antivirus shields before attempting to back up or restore Windows. The usual way to do that is to right-click on an antivirus app’s system tray icon and select a disable/turn off shield protection option from there.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 Don’t leave your antivirus shield permanently disabled. If possible, select to disable it for a few hours before attempting the backup or system restoration operation again. Or manually re-enable your antivirus if you can’t select a temporary option.

## 5\. Disable Any Active Firewalls

 It’s also recommended to disable the firewall component of a third-party antivirus utility before attempting to perform a VSS operation. Turning off an antivirus shield won’t disable a firewall component. Look for firewall settings within your antivirus software’s tabs to see if it includes one. If it does, select to turn off the firewall.

 Try turning off the Windows firewall if you haven’t installed a third-party antivirus utility or firewall software. Check out this guide to [disabling Microsoft Defender Firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) for instructions for turning off that security component.

![The Turn off Windows Defender Firewall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-firewall-settings.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Sj2QNA-JXI?si=V-_h73iE3VlE214k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Set Windows to Perform a Clean Boot

![The Startup type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-tab.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eMEJvwMM0vk?si=EQF_jo_4u9v5iJ_C" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-data.techidaily.com/ed-elevate-your-online-video-quality-mastery-in-finalcut-for-youtube/"><u>[Updated] Elevate Your Online Video Quality Mastery in FinalCut for YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/1-mastering-image-to-excel-conversion-a-step-by-step-guide-for-microsoft-windows/"><u>1. Mastering Image-to-Excel Conversion: A Step-by-Step Guide for Microsoft Windows</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-augmented-commerce-frontiers/"><u>2024 Approved Augmented Commerce Frontiers</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-fixes-for-broken-usb-input-devices-in-microsofts-windows-xpvista7-platform/"><u>Effective Fixes for Broken USB Input Devices in Microsoft's Windows XP/Vista/7 Platform</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-without-backup-on-10t-5g-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to recover deleted photos from Android Gallery without backup on 10T 5G</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-remove-a-previously-synced-google-account-from-your-infinix-smart-8-pro-by-drfone-android/"><u>In 2024, How to Remove a Previously Synced Google Account from Your Infinix Smart 8 Pro</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-top-5-audio-manipulation-apps-perfecting-your-sound-waves/"><u>In 2024, Top 5 Audio Manipulation Apps Perfecting Your Sound Waves</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-excel-a-step-by-step-guide-to-searching-and-substituting-text-and-numbers/"><u>Mastering Excel: A Step-by-Step Guide to Searching and Substituting Text & Numbers</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-unit-conversions-a-step-by-step-guide-using-microsoft-excel/"><u>Mastering Unit Conversions: A Step-by-Step Guide Using Microsoft Excel</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-adding-images-to-your-microsoft-excel-spreadsheet/"><u>Step-by-Step Guide: Adding Images to Your Microsoft Excel Spreadsheet</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-properly-formatting-telephone-digits-in-excel-spreadsheets/"><u>Step-by-Step Guide: Properly Formatting Telephone Digits in Excel Spreadsheets</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-removing-a-pivottable-from-your-microsoft-excel-spreadsheet/"><u>Step-by-Step Guide: Removing a PivotTable From Your Microsoft Excel Spreadsheet</u></a></li>
<li><a href="https://hardware-help.techidaily.com/top-pick-tools-and-supplies-for-crafty-diy-enthusiasts-discover-the-perfect-apery-for-your-next-project-insights/"><u>Top Pick Tools and Supplies for Crafty DIY Enthusiasts: Discover the Perfect Apery for Your Next Project - Insights</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secrets-of-locating-data-positions-with-excel-match-function-a-comprehensive-guide/"><u>Unveiling the Secrets of Locating Data Positions with Excel MATCH Function: A Comprehensive Guide</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-adobe-premiere-pro-essentials-20-shortcuts-to-streamline-your-workflow/"><u>Updated Adobe Premiere Pro Essentials 20 Shortcuts to Streamline Your Workflow</u></a></li>
</ul></div>

