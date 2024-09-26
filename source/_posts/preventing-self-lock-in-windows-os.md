---
title: Preventing Self-Lock in Windows OS
date: 2024-08-22T21:35:22.477Z
updated: 2024-08-23T21:35:22.477Z
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

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
### Disabling Windows Sign-In

 Outright disabling Windows’ sign-in requirement is the most serious step that you can take to disable auto-locking on Windows. To disable the sign-in requirement:

* Hit the Windows keys, type “sign in”, and choose**Sign-in options** .
* In the**Require sign-in** section, select**Never** from the dropdown menu.
* While you are in Sign-in options, make sure to disable Dynamic lock by unchecking the option in the**Dynamic lock** section.

![Disable Windows sign-in](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-sign-in-2.JPG)

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
 Dynamic lock automatically locks your PC if a Bluetooth-connected device, for instance, your smartphone, goes out of range. So, disabling this option will ensure that your PC doesn’t lock up when you walk away from it.

<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Disabling Sleep Mode and Screen Saver

 Next, because Windows automatically locks itself when in sleep mode, you can effectively disable auto-locking by keeping your computer from entering sleep mode. To do this:

* Hit the Windows key, type “power and sleep”, and choose**Power & sleep settings** .
* In the Power & sleep section, set disable mode by choosing**Never** from both dropdowns under**Sleep** .  
![Disable sleep mode on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-sleep-mode.JPG)

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
 If you’ve set a screen saver active on your PC, we also recommend turning it off, as it can, sometimes, cause Windows to automatically lock itself. To disable the screen saver:

* Hit the Windows key again, type “screen saver”, and click**Turn screen saver on or off** to open**Screen Saver Settings** .
* In the Screen Saver Settings, set**Screen saver** to**None** and uncheck**On resume, display the logon screen** .

![Disable screen saver on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-screen-saver.JPG)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
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


