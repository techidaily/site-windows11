---
title: Tackling Error 0X80042306 on Windows to Reset Successfully
date: 2024-07-11T21:27:04.200Z
updated: 2024-07-12T21:27:04.200Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling Error 0X80042306 on Windows to Reset Successfully
excerpt: This Article Describes Tackling Error 0X80042306 on Windows to Reset Successfully
keywords: WinErrorReset,X80042306 Fix,0X80042306 Solve,Windows Error Reset,System XP Error,Successful Reset Window,OS Error Code 0X80042306
thumbnail: https://thmb.techidaily.com/109f8e41f016b710f8a0ad598776af950e5e0ec716fb01a083b32b51c83dd241.jpg
---

## Tackling Error 0X80042306 on Windows to Reset Successfully

 The error code 0x80042306 occurs when attempting to create a restore point in Windows. It prevents the creation of new restore points in the system and typically occurs when your system does not have sufficient free space, there is a problem with the Volume Shadow Copy service (VSS), or a background process is conflicting with the restore utility.

 Below, we talk about the different troubleshooting methods you can try to fix the system restore error 0x80042306 in Windows. We recommend booting into the administrator account before you proceed.

## 1\. Make Sure You Have Sufficient Space

 Restore points require free space on the disk they are stored. This amount of space required by a restore point typically depends on on the size and complexity of your system configuration.

 If you do not have sufficient space on the disk, the restore utility is likely to return a 0x80042306 error. This is why, we recommend getting started by making sure that enough free space for the System Restore to function correctly. You can delete unnecessary items to increase the space manually, or [use the Disk Cleanup](https://www.makeuseof.com/tag/best-way-clean-windows-10-step-step-guide/) utility that is offered by Microsoft by default.

 Alternatively, you can also increase the amount of disk space allocated for System Restore in the System Protection settings. Here is how you can do that:

1. Type "Create a restore point" in the Windows search utility and click**Open** .
2. In the following dialog, head over to the**System Protection** tab.
3. Click on the**Configure** button and use the Max usage to slider to adjust the disk percentage according to your preference.  
![Adjust the Max usage slider](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/restore-point-usage.jpg)
4. Click**Apply** \>**OK** to save the changes.

 Once the changes are made, check if you can now create a restore point without any issues.

## 2\. Restart the Volume Shadow Copy Service

 You might also be facing the problem if the Volume Shadow Copy service is disabled or simply not functioning properly.

 This service allows the creation of backup copies for files and volumes in Windows. It is used to by the restore utility to create snapshots of the items that are being backed up and if it fails to work due to any reason, you might encounter the problem at hand.

 To ensure this service is working properly, you can restart it using the Services utility. Follow the steps below to proceed:

1. Press the**Win** +**R** keys together to open Run.
2. Type "services.msc" in Run and click**Enter** .
3. In the services window, scroll down to locate the**Volume Shadow Copy** service and right-click on it.  
![Volume Shadow Copy service in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/volume-shadow-copy.jpg)
4. Choose**Properties** from the context menu.
5. Now, click on the**Stop** button, wait for a few seconds, and hit**Start** again.
6. Make sure the Startup type is set to**Automatic** .  
![Start the VSS service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/start-vss-service.jpg)
7. Finally, click**Apply** \>**OK** to save the changes.

 Do the same for the Windows Backup service and check if the issue is resolved.

## 3\. Re-Register VSS Components

 If restarting the Volume Shadow Copy service did not work, then you can also try re-registering the VSS components via Command Prompt.

Here is how to proceed:

1. Press the**Win** +**R** keys together to open Run.
2. Type "cmd" in Run and press the**Ctrl** +**Shift** +**Enter** keys together to open Command Prompt as an administrator.
3. Click**Yes** in the User Account Control prompt.
4. Now, execute the following commands one by one:  
`cd /d %windir%\system32net stop vssnet stop swprvregsvr32 /s ole32.dllregsvr32 /s oleaut32.dllregsvr32 /s vss_ps.dllvssvc /registerregsvr32 /s /i  

swprv.dllregsvr32 /s /i eventcls.dllregsvr32 /s es.dllregsvr32 /s stdprov.dllregsvr32 /s vssui.dllregsvr32 /s msxml.dllregsvr32 /s  

msxml3.dllregsvr32 /s msxml4.dllvssvc /registernet start swprvnet start vss`
5. Once you have re-registered VSS components, close Command Prompt and try creating a restore point again.

 If an issue within the VSS components was causing the problem, restarting the components should fix it.

## 4\. Create a Restore Point in Safe Mode

 In some cases, a conflicting background process can also prevent the System Restore utility from creating a restore point successfully. The best way to ensure there are no applications or programs in the background interrupting the functionality of System Restore, try creating a restore point in Safe Mode.

 This mode launches Windows with a minimal set of drivers and services, which can help isolate the issue and prevent any conflicts that may be occurring in normal mode.

Here is how you can boot in Safe Mode:

1. Type "System Configuration" in Windows search and click**Open** .
2. Head over to the**Boot** tab and under Boot Options, checkmark the Safe Boot option.
3. Choose**Minimal** and click on**Apply** \>**OK** to save the changes.  
![Minimal mode of Safe Boot](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/msconfig-boot-safe-mode-minimal.jpg)

 You can now restart your computer and upon reboot, you should enter the Safe Mode automatically. Try recreating a restore point and check if the problem is resolved.

## 5\. Scan the System For Corruption Errors

![Running Sfc scan in CMD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/running-sfc-scan.jpg)

 The System Restore utility itself might be dealing with a corruption error, which is preventing it from functioning properly.

 To fix any corrupt system files, we suggest using the System File Checker (SFC) and Deployment Image Servicing and Management (DISM) tools. SFC works by scanning the protected system files for underlying problems. If an issue is discovered, it will replace the faulty file with its healthier cached counterpart.

 DISM, on the other hand, works by repairing corrupt system images. We have a guide on [how to use SFC and DISM in Windows](https://www.makeuseof.com/windows-built-in-repair-tools/) which you can refer to, to perform the steps correctly.

## System Restore Back On Track

 The System Restore utility in Windows is a powerful tool that can save you from losing important data in case of unexpected system issues. That said, it can be annoying if you cannot create a restore point easily, especially when you are trying to do it before performing a critical action.

 By following the methods outlined in this guideline, you can diagnose the error and take necessary steps to resolve it. We recommend making sure all the relevant services stay enabled, and your system is up-to-date to avoid any such issues in the future.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>



<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/a-step-by-step-approach-to-fixing-to-do-sync-issues/"><u>A Step-by-Step Approach to Fixing To Do Sync Issues</u></a></li>
<li><a href="https://fix-guide.techidaily.com/samsung-galaxy-m14-4g-screen-unresponsive-heres-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Samsung Galaxy M14 4G Screen Unresponsive? Heres How to Fix It | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-windows-11-version-22h2-update-not-installing/"><u>How to Fix the Windows 11 Version 22H2 Update Not Installing</u></a></li>
<li><a href="https://windows11.techidaily.com/automating-network-drives-on-win11/"><u>Automating Network Drives on Win11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-messages-from-honor-x7b-by-fonelab-android-recover-messages/"><u>How to Rescue Lost Messages from Honor X7b</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-superior-satire-picture-styler/"><u>In 2024, Superior Satire Picture Styler</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-absence-of-files-alert-in-windows-11/"><u>Addressing Absence of Files Alert in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-preserves-7-ancient-features-for-modern-use/"><u>Windows 11 Preserves 7 Ancient Features for Modern Use</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-windows-discord-speed-a-step-by-step-guide/"><u>Boosting Windows Discord Speed: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-frozen-recycle-icon-status-in-win11/"><u>Resolving Frozen Recycle Icon Status in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/epic-backup-strategies-to-avoid-loss/"><u>Epic Backup Strategies to Avoid Loss</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-infinix-note-30-drfone-by-drfone-virtual-android/"><u>In 2024, 4 solution to get rid of pokemon fail to detect location On Infinix Note 30 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/curbing-the-constant-appearance-of-edge-icons/"><u>Curbing the Constant Appearance of Edge Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-chromes-black-pixels-issue/"><u>Bypassing Chrome's Black Pixels Issue</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-chromebooks-and-hp-perfect-your-video-capture/"><u>[Updated] Chromebooks and HP  Perfect Your Video Capture</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-15-pro-max-to-others-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 15 Pro Max To Others devices? | Dr.fone</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-2024-approved-reversing-time-lapse-videos-on-iphone-using-top-applications/"><u>New 2024 Approved Reversing Time Lapse Videos on iPhone Using Top Applications</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-1011-auto-cleanup-a-step-by-step-guide/"><u>Windows 10/11 Auto-Cleanup: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-the-application-encountered-an-unrecoverable-error-in-roblox-on-windows/"><u>How to Fix the “The Application Encountered an Unrecoverable Error in Roblox on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-window-11-ui-elements-larger-icons/"><u>Customizing Window 11 UI Elements - Larger Icons</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-2024-approved-transform-your-footage-how-to-add-stunning-effects-in-fcp-x-3-steps/"><u>Updated 2024 Approved Transform Your Footage How to Add Stunning Effects in FCP X (3 Steps)</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-top-5-podcast-apps-for-listening-to-podcasts-on-an-iphone/"><u>[New] Top 5 Podcast Apps for Listening to Podcasts on an iPhone</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-unearthing-absent-settings-in-control-panel/"><u>Windows 11: Unearthing Absent Settings in Control Panel</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-error-0x80071a90-explained-simply/"><u>Fixing Windows Error 0X80071A90 Explained Simply</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/the-comprehensive-starter-guide-to-german-pronunciation-and-script/"><u>The Comprehensive Starter Guide to German Pronunciation & Script</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/expertly-crafted-money-estimator-apps-for-tiktok-users/"><u>Expertly Crafted Money Estimator Apps for TikTok Users</u></a></li>
<li><a href="https://windows11.techidaily.com/ace-windows-with-key-based-configuration-tweaks/"><u>Ace Windows with Key-Based Configuration Tweaks</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-productivity-on-windows-by-adjusting-with-alomware/"><u>Boost Productivity on Windows by Adjusting with AlomWare</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/n-2024-direct-download-destiny-10-online-tool-reviewers-choice/"><u>[New] In 2024, Direct Download Destiny  #10 Online Tool Reviewers' Choice</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-something-went-wrong-with-outlook-on-pcs/"><u>Decoding Something Went Wrong with Outlook on PCs</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-realme-narzo-n53-phone-with-broken-screen-by-drfone-android/"><u>In 2024, How to Unlock Realme Narzo N53 Phone with Broken Screen</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-come-up-with-the-best-pokemon-team-on-vivo-y78plus-t1-edition-drfone-by-drfone-virtual-android/"><u>How to Come up With the Best Pokemon Team On Vivo Y78+ (T1) Edition? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-intellij-unison-not-working-a-guide-for-users-of-windows-11/"><u>Fixing IntelliJ Unison Not Working: A Guide for Users of Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-error-0x80300024-on-a-windows-pc/"><u>Addressing Error 0X80300024 on a Windows PC</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-best-tools-to-hard-reset-vivo-y02t-drfone-by-drfone-reset-android-reset-android/"><u>3 Best Tools to Hard Reset Vivo Y02T | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/authentication-error-occurred-on-infinix-hot-40i-here-are-10-proven-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Authentication Error Occurred on Infinix Hot 40i? Here Are 10 Proven Fixes | Dr.fone</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-bring-your-vision-to-life-8-leading-mac-video-editing-software/"><u>Updated 2024 Approved Bring Your Vision to Life 8 Leading Mac Video Editing Software</u></a></li>
<li><a href="https://windows11.techidaily.com/androidiphone-to-windows-recording-connection-guide/"><u>Android/iPhone to Windows Recording Connection Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-makeover-evolving-file-explorer-here-are-the-changes/"><u>Windows 11 Makeover: Evolving File Explorer, Here Are the Changes</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-precision-leaders-best-7-shooting-adventures/"><u>[New] In 2024, Precision Leaders  Best 7 Shooting Adventures</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/in-2024-should-you-buy-videopad-an-honest-review-and-recommendation/"><u>In 2024, Should You Buy Videopad? An Honest Review and Recommendation</u></a></li>
<li><a href="https://windows11.techidaily.com/confronting-and-overcoming-mmc-snaps-not-found-errors/"><u>Confronting and Overcoming MMC Snaps Not Found Errors</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-4-most-known-ways-to-find-someone-on-tinder-for-poco-c51-by-name-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Most-Known Ways to Find Someone on Tinder For Poco C51 by Name | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/enforcing-originality-windows-screensaver-non-alterability/"><u>Enforcing Originality: Windows Screensaver Non-Alterability</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-accelerating-your-ascension-to-instagram-a-list-status-our-fast-track-guide-of-15-must-try-strategies/"><u>In 2024, Accelerating Your Ascension to Instagram A-List Status  Our Fast Track Guide of 15 Must-Try Strategies</u></a></li>
<li><a href="https://facebook.techidaily.com/the-complete-strategy-for-securing-your-fb-images/"><u>The Complete Strategy for Securing Your FB Images</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-the-deadly-c0000022-breakdown-in-windows-10/"><u>Fixing the Deadly C0000022 Breakdown in Windows 10</u></a></li>
<li><a href="https://extra-resources.techidaily.com/crafting-perfect-tones-with-curvature-techniques/"><u>Crafting Perfect Tones with Curvature Techniques</u></a></li>
</ul></div>
