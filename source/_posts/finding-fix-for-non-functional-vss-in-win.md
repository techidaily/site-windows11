---
title: Finding Fix for Non-Functional VSS in Win
date: 2024-10-25T16:25:37.555Z
updated: 2024-10-30T16:49:02.450Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Finding Fix for Non-Functional VSS in Win
excerpt: This Article Describes Finding Fix for Non-Functional VSS in Win
keywords: Vss Repair Win,Vss Non-Functional Fix,Windows VSS Issue,Solve VSS Error Win,VSS Failure Fix,Correcting Vss Problems,Addressing Vss Crashes
thumbnail: https://thmb.techidaily.com/7c98b3aa443d56db5acb03366d8aa2c1ee75e1644b06d32e3fca560857ba5e46.jpg
---

## Finding Fix for Non-Functional VSS in Win

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

## 2\. Repair Your System Files With the SFC and DISM Commands

 Corrupted system files can affect Windows services, such as Volume Shadow Copy. So, some users may need to repair system files to fix the Volume Shadow Copy Service when it’s not working. You can do that by running System File Checker and Deployment Image Servicing Management scans, as covered in this article about [repairing corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/).

![The sfc scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/sfc-scannow-error.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134246/18498" target="_top" id="2134246">
  <img src="//a.impactradius-go.com/display-ad/18498-2134246" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134246/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Run the Check Disk Utility

 Drive issues can cause Windows system backup VSS errors to occur, with codes like 0x807800A1 or 0x80042315\. In this case, running the Check Disk utility to scan for and address hard drive issues, such as bad sectors, is a potential fix for the Volume Shadow Copy Service not working. Check out this [guide to running the CHKDSK utility](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) for further details about how you can apply this potential resolution.

![The CHKDSK command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/chkdsk-scan-command.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094480/7443" target="_top" id="2094480">
  <img src="//a.impactradius-go.com/display-ad/7443-2094480" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094480/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2094421/7443" target="_top" id="2094421">
  <img src="//a.impactradius-go.com/display-ad/7443-2094421" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094421/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Set Windows to Perform a Clean Boot

![The Startup type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-tab.jpg)

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1175223/12108" target="_top" id="1175223">
  <img src="//a.impactradius-go.com/display-ad/12108-1175223" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1175223/12108" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-is-splitcam-the-premier-choice-for-video-capture/"><u>[New] 2024 Approved Is SplitCam the Premier Choice for Video Capture?</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-the-ultimate-zoom-strategy-for-fb-live-success/"><u>2024 Approved The Ultimate Zoom Strategy for FB Live Success</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-strategies-to-correct-steam-login-pause-in-rust-os/"><u>Essential Strategies to Correct Steam Login Pause in Rust OS</u></a></li>
<li><a href="https://howto.techidaily.com/gmail-not-working-on-oneplus-nord-n30-se-7-common-problems-and-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Gmail Not Working on OnePlus Nord N30 SE 7 Common Problems & Fixes | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-can-we-bypass-infinix-zero-5g-2023-turbo-frp-by-drfone-android/"><u>How Can We Bypass Infinix Zero 5G 2023 Turbo FRP?</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-lava-blaze-pro-5g-location-by-number-drfone-by-drfone-virtual-android/"><u>How to Track Lava Blaze Pro 5G Location by Number | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-solved-move-from-xiaomi-redmi-note-13-5g-to-ios-not-working-problems-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Solved Move from Xiaomi Redmi Note 13 5G to iOS not Working Problems | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/snooze-steadfast-windows-use-keyboard-and-mouse-to-wake-up/"><u>Snooze Steadfast Windows? Use Keyboard & Mouse to Wake Up</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-counteract-unwritable-files-error-in-windows-11/"><u>Steps to Counteract Unwritable Files Error in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-stopping-unwanted-terminal-surface/"><u>Techniques for Stopping Unwanted Terminal Surface</u></a></li>
<li><a href="https://some-skills.techidaily.com/unattached-audio-puzzle-resolution-guide-for-2024/"><u>Unattached Audio Puzzle Resolution Guide for 2024</u></a></li>
</ul></div>

