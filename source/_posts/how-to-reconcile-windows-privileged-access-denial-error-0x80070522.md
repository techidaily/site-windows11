---
title: How To Reconcile Windows' Privileged Access Denial (Error 0X80070522)
date: 2024-12-07T21:08:19.743Z
updated: 2024-12-10T16:14:37.558Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/YZma8PBO0D8?si=9-qQgGVTuChYd27a" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UcplMvRBulA?si=iBonbwDS1v7RAlHK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Set an Admin Account on Windows

 The error 0x80070522 message highlights that this is a privilege (permissions) issue. Therefore, error 0x80070522 is more likely to occur within standard account types than administrator ones. If your current user account only has standard rights, change it to an administrator one. Our guide on[changing your account type on Windows](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) includes four methods for setting up an admin account in Windows 11/10.

![The Administrator radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-administrator-radio-button.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fqBKCGAKHmA?si=OkoaI17nE5qNqTHj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fvAC8jgs62o?si=xqEXZ7dpAXZ4sZ7A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/OFDHJnZLwTA?si=WThcb2h76AnZDzcQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-sharing-recording.techidaily.com/new-a-deep-dive-into-zdsoft-recorder-features-for-2024/"><u>[New] A Deep Dive Into ZDSoft Recorder Features for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-paint-picture-humor/"><u>[New] Paint Picture Humor</u></a></li>
<li><a href="https://extra-information.techidaily.com/exploring-the-infinite-a-look-at-lgs-vr-technology/"><u>Exploring the Infinite A Look at LG's VR Technology</u></a></li>
<li><a href="https://android-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-samsung-galaxy-m14-5g-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Samsung Galaxy M14 5G Phones with/without a PC</u></a></li>
<li><a href="https://windows11.techidaily.com/initiating-chatgpt-with-windows-operating-system/"><u>Initiating ChatGPT with Windows Operating System</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-error-printer-spooler-not-active-on-windows/"><u>Overcoming Error: “Printer Spooler Not Active” On Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-sniping-techniques-alternatives-to-windows-snipping-capability/"><u>Quick Sniping Techniques: Alternatives to Windows' Snipping Capability</u></a></li>
<li><a href="https://windows11.techidaily.com/reimagining-your-pc-integrating-previous-apps-into-win-11/"><u>Reimagining Your PC: Integrating Previous Apps Into Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-dism-error-code-0x800f082f-on-windows-systems/"><u>Resolving DISM Error Code: 0X800F082F on Windows Systems</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/transform-your-viewers-experience-with-top-mac-streamers/"><u>Transform Your Viewers' Experience with Top Mac Streamers</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/virtual-space-clearing-perfecting-your-backdrop-in-zoom-and-google-meet/"><u>Virtual Space Clearing Perfecting Your Backdrop in Zoom & Google Meet</u></a></li>
<li><a href="https://some-guidance.techidaily.com/whatsapp-upgrades-communication-with-enhanced-selection-of-colorful-stickers/"><u>WhatsApp Upgrades Communication with Enhanced Selection of Colorful Stickers</u></a></li>
</ul></div>

