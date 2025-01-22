---
title: How To Reconcile Windows' Privileged Access Denial (Error 0X80070522)
date: 2025-01-21T20:11:26.421Z
updated: 2025-01-22T16:31:41.637Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How To Reconcile Windows' Privileged Access Denial (Error 0X80070522)
excerpt: This Article Describes How To Reconcile Windows' Privileged Access Denial (Error 0X80070522)
keywords: Windows Error Recovery Guide,Fixing Error 0X80070522,Reconcile Privileged Access Denial,Resolving WinError 70522,XP22 Windows Admin Fix,Unblock Privilege Error,Correcting WinError 0X80070522
thumbnail: https://thmb.techidaily.com/9e8b456962dede45b52947713c8978e1ca5454c2b93fe81ef27a5f8f7d593d55.jpg
---

## How To Reconcile Windows' Privileged Access Denial (Error 0X80070522)

 Error 0x80070522 is an issue that can arise when users try to save, move, or copy files in Windows 11/10\. That error often occurs when users try to save files in or copy them to root or system folders. The error 0x80070522 message says, “A required privilege is not held by the client.”

 That message sometimes serves as a security warning for modifying system files and folders. However, users can’t create (save), move, or copy files to certain locations when that error occurs. This is how you can resolve error 0x80070522 in Windows 11/10.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Run Software Packages as an Administrator Before Saving Files

 If error 0x80070522 occurs when you’re trying to save new files, try running the required software packages as administrator. Open any program with which you need to save a file by right-clicking its shortcut or EXE file and selecting**Run as administrator** . Then create or open a file and select to save it when utilizing the software with elevated user permissions.

 You can also set programs to always run as admin. To do so, select a**Run as administrator** setting within an app’s**Compatibility** tab. Check out our article about[always running apps with admin rights on Windows](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) for further details about how to permanently set elevated privileges.

![The Run this program in compatibility mode checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-run-as-administrator-option.jpg)

## 2\. Set an Admin Account on Windows

 The error 0x80070522 message highlights that this is a privilege (permissions) issue. Therefore, error 0x80070522 is more likely to occur within standard account types than administrator ones. If your current user account only has standard rights, change it to an administrator one. Our guide on[changing your account type on Windows](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) includes four methods for setting up an admin account in Windows 11/10.

![The Administrator radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-administrator-radio-button.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4YCkNXJjC3c?si=9Tn8KiqKGTZi1o7E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Turn Off User Account Control (in Three Different Ways)

 User Account Control is a Windows security feature that restricts software privileges. That feature is the most regular cause of error 0x80070522\. Follow the steps in our[g](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) uide to[disabling User Account Control](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) to set UAC to the lowest**Never notify** option.

 It’s not recommended to leave UAC off. Do what you must with the files when User Account Control is disabled. Then turn UAC back on after you’ve saved, moved, or copied the files as needed.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Rxyki8-Y630?si=dHLkIxG59zdlZeN0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Modify the Drive’s Sharing Permissions

 Error 0x80070522 can also arise because of restricted sharing permissions on a drive partition. You can remedy that by selecting the Full control permission setting for the drive. This is how you can modify a drive’s sharing permissions in Windows :

1. Open File Explorer and select**This PC** .
2. Right-click the Local Disk C: drive and select**Properties** . If error 0x80070522 occurs on a different drive, select**Properties** for whatever partition you need to fix the issue.  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-properties-option.jpg)
3. Click the**Sharing** tab.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xg3PHS_Ee80?si=fE_iGIqHjKvWFIN3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Press the**Advanced Sharing** button.
5. Select the**Share this folder** checkbox.  
![The Share this folder checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/share-this-folder-checkbox.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tkpBmccvJ_Q?si=J7ellPL1G1l8Axi_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Click the**Permissions** button.
2. Select the**Full control** option’s**Allow checkbox for the Everyone** group.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-full-control-checkbox.jpg)
3. Click the**Apply** and**OK** on the Permissions and Advanced Sharing windows.

4. Select**Close** to exit the properties window.
5. Then click**Power** and select**Restart** within your Start menu.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q_69vX9wnRE?si=FtLxkpRhPORqcMeE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Perform the Required File or Folder Actions on Windows

 Applying those potential solutions will probably fix error 0x80070522 and enable you to perform required file or folder actions without restriction. Most users have resolved this error by disabling User Account Control security one way or another.

 However, leaving UAC disabled will compromise your PC’s security. So, it’s recommended to set up a restore point before attempting to resolve error 0x80070522 with the third and fourth resolutions at least.

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
<li><a href="https://screen-recording.techidaily.com/updated-advanced-guide-to-documenting-online-sport-spectacles/"><u>[Updated] Advanced Guide to Documenting Online Sport Spectacles</u></a></li>
<li><a href="https://howto.techidaily.com/7-fixes-for-unfortunately-phone-has-stopped-on-samsung-galaxy-s23plus-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Fixes for Unfortunately, Phone Has Stopped on Samsung Galaxy S23+ | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/android-cache-purge-techniques-for-optimal-performance/"><u>Android Cache Purge Techniques for Optimal Performance</u></a></li>
<li><a href="https://win-hacks.techidaily.com/easy-solutions-correcting-boot-issues-on-windows-11-when-it-starts-up-on-the-incorrect-hardware/"><u>Easy Solutions: Correcting Boot Issues on Windows 11 When It Starts Up On the Incorrect Hardware</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-accelerate-your-contents-view-count-1kplus-in-time/"><u>In 2024, Accelerate Your Content's View Count 1K+ in Time</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-4-sim-location-trackers-to-easily-find-your-lost-lava-agni-2-5g-device-by-drfone-android/"><u>In 2024, Top 4 SIM Location Trackers To Easily Find Your Lost Lava Agni 2 5G Device</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/24-unleash-hd-playback-with-av1-on-youtube/"><u>In 2024, Unleash HD Playback with AV1 on YouTube</u></a></li>
<li><a href="https://solve-info.techidaily.com/missing-page-alert-content-doesnt-exist-here/"><u>Missing Page Alert: Content Doesn't Exist Here</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-tips-reactivate-your-calendar-and-mail-on-w11/"><u>Quick Tips: Reactivate Your Calendar & Mail on W11</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-windows-7-techniques-against-uac-intrusions/"><u>Securing Windows: 7 Techniques Against UAC Intrusions</u></a></li>
<li><a href="https://windows11.techidaily.com/speeding-up-epic-games-installation-windows-wise/"><u>Speeding Up Epic Games Installation Windows-Wise</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-spotify-link-failures-on-pcs-windows/"><u>Troubleshooting Spotify Link Failures on PCs (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/turn-onoff-text-emphasis-and-highlight-effects-on-pc/"><u>Turn On/Off Text Emphasis and Highlight Effects on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-copy-and-paste-features-with-application-guard-in-edge-w11-edition/"><u>Unlocking Copy & Paste Features with Application Guard in Edge, W11 Edition</u></a></li>
</ul></div>

