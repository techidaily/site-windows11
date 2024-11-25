---
title: Preventing Self-Lock in Windows OS
date: 2024-11-19T17:52:51.326Z
updated: 2024-11-25T01:14:08.052Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Preventing Self-Lock in Windows OS
excerpt: This Article Describes Preventing Self-Lock in Windows OS
keywords: Lockout Prevention Windows,Anti-SelfLock Features,Security,Secure Windows System,Bypass Window Locks,OS Safety,Safe Windows Access Control
thumbnail: https://thmb.techidaily.com/22aa5877473f7aef18423fbe77d7ea5e7e2937ae2cb99e9b5ca8066747f3813d.jpg
---

## Preventing Self-Lock in Windows OS

 If your Windows PC is protected by a password, the computer will auto-lock whenever you restart it or put it into Sleep mode. While this auto-locking behavior is a security measure, it can be annoying on occasion.

 Fortunately, you can keep Windows from automatically locking itself. Here’s how.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaWcXdTn5SE?si=QbxEkX-4a17J5RVs&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Is Windows 10 Automatically Locking Itself?

 Windows automatically locks itself for one simple reason: to protect your privacy.

 Imagine a scenario where you have to leave your computer unattended for an extended period. If there is no auto-lock on Windows, anyone can use your PC for any reason without any repercussions.

 By locking itself automatically once your PC goes into sleep mode, Windows ensures that your data stays private and nobody except you has access to your computer.

## How to Stop Windows From Automatically Locking Itself

You can stop Windows from automatically locking itself by:

* Disabling Windows sign-in.
* Disabling sleep mode and screen saver.
* Editing the[Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) to disable auto-locking.

Now that we know how to do it, let's dive into the steps.

### Disabling Windows Sign-In

 Outright disabling Windows’ sign-in requirement is the most serious step that you can take to disable auto-locking on Windows. To disable the sign-in requirement:

* Hit the Windows keys, type “sign in”, and choose**Sign-in options** .
* In the**Require sign-in** section, select**Never** from the dropdown menu.
* While you are in Sign-in options, make sure to disable Dynamic lock by unchecking the option in the**Dynamic lock** section.

![Disable Windows sign-in](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-sign-in-2.JPG)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2NU63YqpVqw?si=uoJs0-nZYAkILqXx&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Dynamic lock automatically locks your PC if a Bluetooth-connected device, for instance, your smartphone, goes out of range. So, disabling this option will ensure that your PC doesn’t lock up when you walk away from it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gkdZ3A1mock?si=2zeR5GtTU2VujM_w&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Disabling Sleep Mode and Screen Saver

 Next, because Windows automatically locks itself when in sleep mode, you can effectively disable auto-locking by keeping your computer from entering sleep mode. To do this:

* Hit the Windows key, type “power and sleep”, and choose**Power & sleep settings** .
* In the Power & sleep section, set disable mode by choosing**Never** from both dropdowns under**Sleep** .  
![Disable sleep mode on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-sleep-mode.JPG)

 If you’ve set a screen saver active on your PC, we also recommend turning it off, as it can, sometimes, cause Windows to automatically lock itself. To disable the screen saver:

* Hit the Windows key again, type “screen saver”, and click**Turn screen saver on or off** to open**Screen Saver Settings** .
* In the Screen Saver Settings, set**Screen saver** to**None** and uncheck**On resume, display the logon screen** .

![Disable screen saver on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-screen-saver.JPG)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wNhKhWc0wLc?si=1XLYV0sXV52Xc0lu&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Editing Windows Registry to Disable Auto-Locking

 Finally, you can also edit Windows Registry to stop Windows from automatically locking itself. Before we show you how to do this, make sure you understand that editing Windows Registry can make your system unstable requiring you to restart or even[perform a fresh Windows install](https://www.makeuseof.com/windows-11-set-up-without-internet-connection/) for your PC to work properly again.

So, edit Windows Registry only when nothing else works.

* Hit the Windows keys, type “registry”, right-click on**Registry Editor** , and select**Run as administrator** .
* In Registry Editor, navigate to**HKEY\_LOCAL\_MACHINE** \>**Software** \>**Policies** \>**Microsoft** .
* Next, right-click on**Windows** , select**New** , and choose**Key** to define a new key/create a new folder in Windows Registry. Name the new folder something like “Disable autoLock”.
* Now, right-click on the folder you just created, place the mouse cursor over**New** , and select**DWORD (32-bit) Value** . Change the name of this new element to “NoLockScreen”.
* Open**NoLockScreen** and set the Value data to 1\. Press ok to finish the process.

![Disable auto-lock from Windows Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-auto-lock-registry.JPG)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLlUft1ZxI0?si=pBd5QdHEE27qsNlN&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Finally, restart your computer to see if a lock screen appears.

## Use Windows Hello to Make Windows’ Auto-Locking Bearable

 If your PC or notebook has facial recognition or a fingerprint reader, you can set up Windows Hello to make sign-ins a breeze.

 On supported computers, Windows Hello can instantly recognize your face/fingerprint to log you in, taking the hassle out of typing a password in case of Windows auto-locking itself.

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
<li><a href="https://article-knowledge.techidaily.com/new-in-2024-motion-control-in-vr-keeping-nausea-at-bay/"><u>[New] In 2024, Motion Control in VR Keeping Nausea at Bay</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-step-by-step-process-for-adding-unique-emojis-to-your-discord-avatar-pcmobile/"><u>[Updated] Step-By-Step Process for Adding Unique Emojis to Your Discord Avatar (PC/Mobile)</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-retrieve-lost-contacts-from-realme-by-fonelab-android-recover-contacts/"><u>Best Android Data Recovery - Retrieve Lost Contacts from Realme .</u></a></li>
<li><a href="https://buynow-info.techidaily.com/expert-insight-into-the-fujitsu-scansnap-ix1600-the-ultimate-desktop-document-scanner-solution/"><u>Expert Insight Into the Fujitsu ScanSnap iX1600 - The Ultimate Desktop Document Scanner Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-manage-windows-11s-online-scanning-option/"><u>How to Manage Windows 11'S Online Scanning Option</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-show-or-hide-the-dim-display-after-option-in-the-power-options-menu-on-windows/"><u>How to Show or Hide the “Dim Display After” Option in the Power Options Menu on Windows</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-successfully-patch-your-pc-with-windows-10-version-2004-and-new-conexant-support/"><u>How To Successfully Patch Your PC with Windows 10 Version 2004 and New Conexant Support</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-steams-captcha-rejection/"><u>Overcoming Steam's CAPTCHA Rejection</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-bios-secure-boot-a-step-by-step-guide-for-windows-users/"><u>Reviving BIOS Secure Boot: A Step-by-Step Guide for Windows Users</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/still-on-sale-top-bargains-of-amazon-prime-day-2024-in-october-techradar/"><u>Still on Sale - Top Bargains of Amazon Prime Day 2024 in October | TechRadar</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-the-top-8-timers-for-effective-pomodoro/"><u>The Ultimate Guide to the Top 8 Timers for Effective Pomodoro</u></a></li>
</ul></div>

