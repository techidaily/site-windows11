---
title: How To Reconcile Windows' Privileged Access Denial (Error 0X80070522)
date: 2024-11-20T16:01:46.710Z
updated: 2024-11-24T22:08:41.878Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/oP8grXxuy2o?si=uIRNhTYbecTcaC7J&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Run Software Packages as an Administrator Before Saving Files

 If error 0x80070522 occurs when you’re trying to save new files, try running the required software packages as administrator. Open any program with which you need to save a file by right-clicking its shortcut or EXE file and selecting**Run as administrator** . Then create or open a file and select to save it when utilizing the software with elevated user permissions.

 You can also set programs to always run as admin. To do so, select a**Run as administrator** setting within an app’s**Compatibility** tab. Check out our article about[always running apps with admin rights on Windows](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) for further details about how to permanently set elevated privileges.

![The Run this program in compatibility mode checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-run-as-administrator-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-G7cU8dYvuI?si=JaKqRcW6qq9CDvty&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U_aNKnMTPjo?si=Og_mEt7NP3Fbsg2n&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Set an Admin Account on Windows

 The error 0x80070522 message highlights that this is a privilege (permissions) issue. Therefore, error 0x80070522 is more likely to occur within standard account types than administrator ones. If your current user account only has standard rights, change it to an administrator one. Our guide on[changing your account type on Windows](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) includes four methods for setting up an admin account in Windows 11/10.

![The Administrator radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-administrator-radio-button.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LW6wNx3XAj8?si=VaIuFIIx8MM_RhUR&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/d-COuhPT5mk?si=wLZU6jkkAdJuAn6h&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://remote-screen-capture.techidaily.com/updated-platform-power-playout-which-streams-better-obs-or-twitch-studio-in-2024/"><u>[Updated] Platform Power Playout Which Streams Better - OBS or Twitch Studio, In 2024</u></a></li>
<li><a href="https://location-fake.techidaily.com/8-solutions-to-fix-find-my-friends-location-not-available-on-vivo-y56-5g-drfone-by-drfone-virtual-android/"><u>8 Solutions to Fix Find My Friends Location Not Available On Vivo Y56 5G | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/conversion-gratuite-de-videos-convertir-des-fichiers-wmv-en-swf-directement-sur-internet-grace-a-movavi-media-converter/"><u>Conversion Gratuite De Vidéos : Convertir Des Fichiers WMV en SWF Directement Sur Internet Grâce À Movavi Media Converter</u></a></li>
<li><a href="https://fox-helps.techidaily.com/craft-movies-on-windows-11-using-the-free-movie-maker-app/"><u>Craft Movies on Windows 11 Using the Free Movie Maker App</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-the-dichotomy-microsoft-vs-native-user-account-on-windows-os/"><u>Dissecting the Dichotomy: Microsoft vs Native User Account on Windows OS</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-2-ways-to-monitor-google-pixel-8-pro-activity-drfone-by-drfone-virtual-android/"><u>In 2024, 2 Ways to Monitor Google Pixel 8 Pro Activity | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-easy-ways-to-manage-your-oneplus-ace-3-location-settings-drfone-by-drfone-virtual/"><u>In 2024, Easy Ways to Manage Your OnePlus Ace 3 Location Settings | Dr.fone</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-how-do-i-stop-someone-from-tracking-my-apple-iphone-7-drfone-by-drfone-virtual-ios/"><u>In 2024, How Do I Stop Someone From Tracking My Apple iPhone 7? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-error-printer-spooler-not-active-on-windows/"><u>Overcoming Error: “Printer Spooler Not Active” On Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-sniping-techniques-alternatives-to-windows-snipping-capability/"><u>Quick Sniping Techniques: Alternatives to Windows' Snipping Capability</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-dism-error-code-0x800f082f-on-windows-systems/"><u>Resolving DISM Error Code: 0X800F082F on Windows Systems</u></a></li>
</ul></div>

