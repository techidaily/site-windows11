---
title: Recovering Dormant Backup Service on OS X
date: 2025-01-26T20:51:33.542Z
updated: 2025-01-30T04:19:33.969Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/E3yY7lZ-FKA?si=g8VEuExP8GH59B69" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jf0JvOqiAXc?si=kHEHQGC_PhBv4xij" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Repair Your System Files With the SFC and DISM Commands

 Corrupted system files can affect Windows services, such as Volume Shadow Copy. So, some users may need to repair system files to fix the Volume Shadow Copy Service when it’s not working. You can do that by running System File Checker and Deployment Image Servicing Management scans, as covered in this article about [repairing corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/).

![The sfc scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/sfc-scannow-error.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/43goO8X0iX0?si=48Cqf6td2q_6T6h3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RCYs8keh-Vs?si=uDC28-9yh-k6HLj4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Run the Check Disk Utility

 Drive issues can cause Windows system backup VSS errors to occur, with codes like 0x807800A1 or 0x80042315\. In this case, running the Check Disk utility to scan for and address hard drive issues, such as bad sectors, is a potential fix for the Volume Shadow Copy Service not working. Check out this [guide to running the CHKDSK utility](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) for further details about how you can apply this potential resolution.

![The CHKDSK command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/chkdsk-scan-command.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlVkEwpjKKo?si=hXi-mchMaJvbnIzM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Disable Antivirus Shields

 Sometimes third-party antivirus software can interfere with and prevent Volume Shadow Copy from functioning correctly. So, try disabling third-party antivirus shields before attempting to back up or restore Windows. The usual way to do that is to right-click on an antivirus app’s system tray icon and select a disable/turn off shield protection option from there.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 Don’t leave your antivirus shield permanently disabled. If possible, select to disable it for a few hours before attempting the backup or system restoration operation again. Or manually re-enable your antivirus if you can’t select a temporary option.

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
<li><a href="https://fox-links.techidaily.com/updated-reimagine-video-narratives-with-windows-10s-story-remix-tool-for-2024/"><u>[Updated] Reimagine Video Narratives with Windows 10'S Story Remix Tool for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-narrative-strategies-for-engaging-docu-films/"><u>2024 Approved Narrative Strategies for Engaging Docu-Films</u></a></li>
<li><a href="https://win-help.techidaily.com/die-weise-der-automatischen-altbackup-entfernung-im-windows-server-umfeld/"><u>Die Weise Der Automatischen Altbackup-Entfernung Im Windows Server Umfeld</u></a></li>
<li><a href="https://windows11.techidaily.com/guides-to-reinstate-windows-print-spooler/"><u>Guides to Reinstate Windows Print Spooler</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-easy-ways-to-copy-contacts-from-samsung-galaxy-a05-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Easy Ways to Copy Contacts from Samsung Galaxy A05 to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-sound-surprises-10-androidios-audio-twisters/"><u>In 2024, Sound Surprises 10 Android/iOS Audio Twisters</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/is-a-133-screen-size-ideal-for-your-new-e-reader-purchase/"><u>Is a 13.3 Screen Size Ideal for Your New E-Reader Purchase?</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/lenovos-latest-powerhouse-the-thinkpad-z13-gen-2-with-advanced-amd-chipset-unveiled/"><u>Lenovo's Latest Powerhouse: The ThinkPad Z13 Gen 2 with Advanced AMD Chipset Unveiled!</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/network-locked-sim-card-inserted-on-your-oneplus-ace-2-pro-phone-unlock-it-now-by-drfone-android/"><u>Network Locked SIM Card Inserted On Your OnePlus Ace 2 Pro Phone? Unlock It Now</u></a></li>
<li><a href="https://windows11.techidaily.com/post-cortana-era-windows-four-changes/"><u>Post-Cortana Era: Windows’ Four Changes</u></a></li>
<li><a href="https://discover-bytes.techidaily.com/resolved-issue-absence-of-bitlocker-feature-on-windows-10/"><u>Resolved Issue: Absence of BitLocker Feature on Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-workflow-integration-to-do-plus-ifttt/"><u>Seamless Workflow Integration: To-Do + IFTTT</u></a></li>
<li><a href="https://windows11.techidaily.com/steam-deck-to-windows-os-a-guide/"><u>Steam Deck to Windows OS: A Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-workflow-integrating-a-functional-taskbar-on-slate-devices-windows-11/"><u>Streamlining Workflow: Integrating a Functional Taskbar on Slate Devices (Windows 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-error-0xc00d36b4-on-windows-11-pcs/"><u>Tackling Error 0XC00D36B4 on Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-re-establish-router-page-on-pc/"><u>Techniques to Re-Establish Router Page on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-modern-standby-demystified-with-pros-and-cons/"><u>Windows Modern Standby Demystified with Pros & Cons</u></a></li>
</ul></div>

