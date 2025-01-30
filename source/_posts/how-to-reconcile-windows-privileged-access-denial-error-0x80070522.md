---
title: How To Reconcile Windows' Privileged Access Denial (Error 0X80070522)
date: 2025-01-23T00:42:59.110Z
updated: 2025-01-30T04:06:09.883Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9ECz3oZ8NrQ?si=86vkwkDJo9HQXpzt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Set an Admin Account on Windows

 The error 0x80070522 message highlights that this is a privilege (permissions) issue. Therefore, error 0x80070522 is more likely to occur within standard account types than administrator ones. If your current user account only has standard rights, change it to an administrator one. Our guide on[changing your account type on Windows](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) includes four methods for setting up an admin account in Windows 11/10.

![The Administrator radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-administrator-radio-button.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/T-ssCD10v2M?si=WVWGNayUiCAkMZzZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Turn Off User Account Control (in Three Different Ways)

 User Account Control is a Windows security feature that restricts software privileges. That feature is the most regular cause of error 0x80070522\. Follow the steps in our[g](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) uide to[disabling User Account Control](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) to set UAC to the lowest**Never notify** option.

 It’s not recommended to leave UAC off. Do what you must with the files when User Account Control is disabled. Then turn UAC back on after you’ve saved, moved, or copied the files as needed.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xg3PHS_Ee80?si=fE_iGIqHjKvWFIN3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Modify the Drive’s Sharing Permissions

 Error 0x80070522 can also arise because of restricted sharing permissions on a drive partition. You can remedy that by selecting the Full control permission setting for the drive. This is how you can modify a drive’s sharing permissions in Windows :

1. Open File Explorer and select**This PC** .
2. Right-click the Local Disk C: drive and select**Properties** . If error 0x80070522 occurs on a different drive, select**Properties** for whatever partition you need to fix the issue.  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-properties-option.jpg)
3. Click the**Sharing** tab.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E3yY7lZ-FKA?si=g8VEuExP8GH59B69" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Press the**Advanced Sharing** button.
5. Select the**Share this folder** checkbox.  
![The Share this folder checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/share-this-folder-checkbox.jpg)

1. Click the**Permissions** button.
2. Select the**Full control** option’s**Allow checkbox for the Everyone** group.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-full-control-checkbox.jpg)
3. Click the**Apply** and**OK** on the Permissions and Advanced Sharing windows.

4. Select**Close** to exit the properties window.
5. Then click**Power** and select**Restart** within your Start menu.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hHPljBHrvkA?si=HwdfDM9rlbABSIrx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-docs.techidaily.com/ltimate-guide-selecting-8-exquisite-weddings-vids-for-2024/"><u>[New] Ultimate Guide Selecting 8 Exquisite Weddings - Vids for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/approved-how-to-make-youtube-video-the-ultimate-guide/"><u>2024 Approved How to Make YouTube Video The Ultimate Guide</u></a></li>
<li><a href="https://tech-hub.techidaily.com/a-new-era-of-editing-unlocked-how-fcpxs-latest-ipad-innovations-are-transforming-filmmaking-zdnet/"><u>A New Era of Editing Unlocked: How FCPx's Latest iPad Innovations Are Transforming Filmmaking - ZDNet</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-ceasing-built-in-laptop-input-through-windows/"><u>Guide: Ceasing Built-In Laptop Input Through Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-unresponsive-clicks-in-the-latest-windows/"><u>Handling Unresponsive Clicks in the Latest Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-keep-sticky-notes-always-on-top-on-windows-10-and-11/"><u>How to Keep Sticky Notes Always on Top on Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-maximize-all-available-ram-in-your-windows-environment/"><u>How to Maximize All Available RAM in Your Windows Environment</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-2-ways-to-monitor-xiaomi-redmi-13c-5g-activity-drfone-by-drfone-virtual-android/"><u>In 2024, 2 Ways to Monitor Xiaomi Redmi 13C 5G Activity | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-forgot-pattern-lock-heres-how-you-can-unlock-honor-90-gt-pattern-lock-screen-by-drfone-android/"><u>In 2024, Forgot Pattern Lock? Heres How You Can Unlock Honor 90 GT Pattern Lock Screen</u></a></li>
<li><a href="https://article-files.techidaily.com/in-2024-learn-to-master-character-voice-customization-the-ultimate-guide-to-transforming-in-game-speech-free/"><u>In 2024, Learn to Master Character Voice Customization The Ultimate Guide to Transforming In-Game Speech (Free)</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/in-2024-phantom-camera-pause-tips/"><u>In 2024, Phantom Camera Pause Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-post-update-linux-integration-on-win-11/"><u>Mastery Over Post-Update Linux Integration on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-unresolved-roblox-issues-on-windows/"><u>Overcoming Unresolved Roblox Issues on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-expired-semaphore-in-win1110-systems/"><u>Troubleshooting Expired Semaphore in Win11/10 Systems</u></a></li>
<li><a href="https://tech-haven.techidaily.com/youtube4kpc/"><u>YouTubeの高解像度4K動画PCでダウンロードテクニック</u></a></li>
</ul></div>

