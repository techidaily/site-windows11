---
title: How To Reconcile Windows' Privileged Access Denial (Error 0X80070522)
date: 2024-12-30T21:31:54.813Z
updated: 2025-01-03T21:19:09.978Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qfCSLAhd4FY?si=CUBztmilaeAwl1lw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Run Software Packages as an Administrator Before Saving Files

 If error 0x80070522 occurs when you’re trying to save new files, try running the required software packages as administrator. Open any program with which you need to save a file by right-clicking its shortcut or EXE file and selecting**Run as administrator** . Then create or open a file and select to save it when utilizing the software with elevated user permissions.

 You can also set programs to always run as admin. To do so, select a**Run as administrator** setting within an app’s**Compatibility** tab. Check out our article about[always running apps with admin rights on Windows](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) for further details about how to permanently set elevated privileges.

![The Run this program in compatibility mode checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-run-as-administrator-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1CdWd06fCwc?si=wzg-68q0jAksPRXp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kx-Pb0otJCs?si=Mvr49yQVesmJA8-O" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Set an Admin Account on Windows

 The error 0x80070522 message highlights that this is a privilege (permissions) issue. Therefore, error 0x80070522 is more likely to occur within standard account types than administrator ones. If your current user account only has standard rights, change it to an administrator one. Our guide on[changing your account type on Windows](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) includes four methods for setting up an admin account in Windows 11/10.

![The Administrator radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-administrator-radio-button.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/epKTCSREjhI?si=Ez_hObK1FZrmEE7f" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Turn Off User Account Control (in Three Different Ways)

 User Account Control is a Windows security feature that restricts software privileges. That feature is the most regular cause of error 0x80070522\. Follow the steps in our[g](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) uide to[disabling User Account Control](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) to set UAC to the lowest**Never notify** option.

 It’s not recommended to leave UAC off. Do what you must with the files when User Account Control is disabled. Then turn UAC back on after you’ve saved, moved, or copied the files as needed.

## 4\. Modify the Drive’s Sharing Permissions

 Error 0x80070522 can also arise because of restricted sharing permissions on a drive partition. You can remedy that by selecting the Full control permission setting for the drive. This is how you can modify a drive’s sharing permissions in Windows :

1. Open File Explorer and select**This PC** .
2. Right-click the Local Disk C: drive and select**Properties** . If error 0x80070522 occurs on a different drive, select**Properties** for whatever partition you need to fix the issue.  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-properties-option.jpg)
3. Click the**Sharing** tab.

4. Press the**Advanced Sharing** button.
5. Select the**Share this folder** checkbox.  
![The Share this folder checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/share-this-folder-checkbox.jpg)

1. Click the**Permissions** button.
2. Select the**Full control** option’s**Allow checkbox for the Everyone** group.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-full-control-checkbox.jpg)
3. Click the**Apply** and**OK** on the Permissions and Advanced Sharing windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XS1nQCe95LU?si=A2dhdFkSAI61_nKA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Select**Close** to exit the properties window.
5. Then click**Power** and select**Restart** within your Start menu.

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
<li><a href="https://eaxpv-info.techidaily.com/updated-flipping-the-script-turning-online-games-into-channel-gold-for-2024/"><u>[Updated] Flipping the Script Turning Online Games Into Channel Gold for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/4-ways-to-fix-android-blue-screen-of-death-on-xiaomi-redmi-12-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>4 Ways to Fix Android Blue Screen of Death On Xiaomi Redmi 12 | Dr.fone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-drivers-and-install-logitech-g402-gaming-mouse-software-now/"><u>Download Drivers & Install Logitech G402 Gaming Mouse Software Now!</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209944138-how-to-fix-csgo-crashing-quickly-and-easily/"><u>How To Fix CSGO Crashing. Quickly & Easily</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-how-to-transfer-messages-from-apple-iphone-se-to-other-iphone-all-ios-versions-drfone-by-drfone-transfer-from-ios/"><u>In 2024, How To Transfer Messages From Apple iPhone SE to other iPhone All iOS Versions | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-disabled-apple-iphone-7-plusipad-without-computer-drfone-by-drfone-ios/"><u>In 2024, How to Unlock Disabled Apple iPhone 7 Plus/iPad Without Computer | Dr.fone</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-your-ultimate-guide-to-youtube-shorts/"><u>In 2024, Your Ultimate Guide to YouTube Shorts</u></a></li>
<li><a href="https://fox-within.techidaily.com/latest-party-tyme-singalong-collection-awaits-new-songs-added-11-13-17-join-the-dj-community/"><u>Latest Party Tyme Singalong Collection Awaits! New Songs Added 11-13-17 - Join the DJ Community!</u></a></li>
<li><a href="https://windows11.techidaily.com/preserving-torrent-performance-post-transfer-to-a-new-machine/"><u>Preserving Torrent Performance Post-Transfer to a New Machine</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-unable-to-connect-error-with-malwarebytes-in-windows/"><u>Resolving Unable to Connect Error with Malwarebytes in Windows</u></a></li>
<li><a href="https://tech-revival.techidaily.com/step-by-step-guide-developing-your-personalized-chatbot-using-custom-datasets/"><u>Step-by-Step Guide: Developing Your Personalized ChatBot Using Custom Datasets</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-your-touch-to-the-world-of-win11-keybindings/"><u>Tailoring Your Touch to the World of Win11 Keybindings</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-high-cpu-in-your-host-system/"><u>Taming High CPU in Your Host System</u></a></li>
</ul></div>

