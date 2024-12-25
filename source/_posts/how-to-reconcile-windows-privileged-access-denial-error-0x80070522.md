---
title: How To Reconcile Windows' Privileged Access Denial (Error 0X80070522)
date: 2024-12-23T17:44:20.843Z
updated: 2024-12-25T18:13:58.058Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/e4Nt2xXXtmE?si=CtKwFry4b0AJXnaN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lxv4NM-89CU?si=Uj5rOkhrwZ_6QIuW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Set an Admin Account on Windows

 The error 0x80070522 message highlights that this is a privilege (permissions) issue. Therefore, error 0x80070522 is more likely to occur within standard account types than administrator ones. If your current user account only has standard rights, change it to an administrator one. Our guide on[changing your account type on Windows](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) includes four methods for setting up an admin account in Windows 11/10.

![The Administrator radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-administrator-radio-button.jpg)

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/7JBG_O3Vnh4?si=lUO0fta6YPJ50qjg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Press the**Advanced Sharing** button.
5. Select the**Share this folder** checkbox.  
![The Share this folder checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/share-this-folder-checkbox.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15TKQ-BOENI?si=Ri4B2AuxAdi0Bglz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Click the**Permissions** button.
2. Select the**Full control** option’s**Allow checkbox for the Everyone** group.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-full-control-checkbox.jpg)
3. Click the**Apply** and**OK** on the Permissions and Advanced Sharing windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/M5pwd2mwaQQ?si=qyZHgdTlbQbc32Mp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://article-helps.techidaily.com/new-2024-approved-optimizing-viewing-experience-video-filters-for-all-screens/"><u>[New] 2024 Approved Optimizing Viewing Experience Video Filters for All Screens</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-a-step-by-step-igtv-translation-guide/"><u>[Updated] A Step-By-Step IGTV Translation Guide</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-effortless-youtube-content-crafting-10-basic-video-ideas-for-all-for-2024/"><u>[Updated] Effortless YouTube Content Crafting 10 Basic Video Ideas for All for 2024</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-locked-or-disabled-from-apple-iphone-15-7-mehtods-you-cant-miss-by-drfone-ios/"><u>Apple ID Locked or Disabled From Apple iPhone 15? 7 Mehtods You Cant-Miss</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/high-fidelity-enhances-virtual-universe-with-second-life-acquisition-insights-from-zdnet/"><u>High Fidelity Enhances Virtual Universe with Second Life Acquisition: Insights From ZDNet</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-0x0000004e-error-in-windows-10-and-11/"><u>How to Fix the 0X0000004E Error in Windows 10 and 11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-bypassing-google-account-with-vnrom-bypass-for-oppo-a1-5g-by-drfone-android/"><u>In 2024, Bypassing Google Account With vnROM Bypass For Oppo A1 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/is-sleep-hibernate-or-shutdown-best-for-your-windows-computer/"><u>Is Sleep, Hibernate, or Shutdown Best for Your Windows Computer?</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaiming-control-from-a-wildly-wandering-mouse/"><u>Reclaiming Control From a Wildly Wandering Mouse</u></a></li>
<li><a href="https://windows11.techidaily.com/sayonara-to-sluggish-keys-top-tricks-for-win-11s-faster-typing/"><u>Sayonara to Sluggish Keys: Top Tricks for Win 11'S Faster Typing</u></a></li>
<li><a href="https://windows11.techidaily.com/simplified-gpo-analysis-via-gpresult-command/"><u>Simplified GPO Analysis via GPResult Command</u></a></li>
</ul></div>

