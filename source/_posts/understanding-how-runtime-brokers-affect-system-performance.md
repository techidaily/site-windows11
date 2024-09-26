---
title: Understanding How Runtime Brokers Affect System Performance
date: 2024-08-08T06:11:06.705Z
updated: 2024-08-09T06:11:06.705Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Understanding How Runtime Brokers Affect System Performance
excerpt: This Article Describes Understanding How Runtime Brokers Affect System Performance
keywords: System Speed Impact,Runtime Efficiency,Performance Dynamics,Broker Effects,Execution Time,Resource Management,Load Balancing Effects
thumbnail: https://thmb.techidaily.com/9d8448293885018e42ea0c2c618da231bf75f85bd2fb228b8b71882f24dcc32a.jpg
---

## Understanding How Runtime Brokers Affect System Performance

<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Quick Links

* [What Is Runtime Broker in Windows and What Does It Do?](#what-is-runtime-broker-in-windows-and-what-does-it-do)
* [Why Is Runtime Broker Using So Much Memory?](#why-is-runtime-broker-using-so-much-memory)

 Runtime Broker is a mystery to many PC users. You might have spotted it running in your Task Manager and hogging CPU resources. Let's find out what the Runtime Broker process is and whether you need it.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
<!-- affiliate ads end -->
## What Is Runtime Broker in Windows and What Does It Do?

 Runtime Broker (or Time Broker) is a Windows system process that manages permissions for the universal apps you install from the Microsoft Store. It was first introduced in Windows 8 and continues to appear in all subsequent versions.

<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
![Task Manager shows an active Runtime Broker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/task-manager-shows-an-active-runtime-broker.jpg)

 This process runs in the background and functions like a gatekeeper: it mediates between universal apps and system resources such as the network, camera, and location. In other words, it ensures that apps have the required permissions to function properly without compromising your system's security.

 When you launch an app from the Microsoft Store, the Runtime Broker checks if the app has the necessary permissions to use system resources. If not, it requests permission on behalf of the app. With the permission granted, Runtime Broker acts as an intermediary between the app and the resources it needs to use.

 For example, if you launch a photo editing app that needs access to your photos, the Runtime Broker will request permission to access those images. Upon approval, Runtime Broker will ensure the app only accesses photos, not other sensitive information. This way, Runtime Broker [protects Windows against unauthorized access](http://www.makeuseof.com/prevent-unauthorized-access-windows/) and security threats.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
## Why Is Runtime Broker Using So Much Memory?

 Now that you know what a Runtime Broker is, you might wonder why it sometimes uses a large amount of CPU resources. You might have noticed this process frequently appearing while [using Task Manager](https://www.makeuseof.com/how-to-use-windows-task-manager/).

 A Runtime Broker process only runs when a universal app needs access to system resources. Typically, this requires just a few megabytes of memory. But if an app constantly requests permission or has permission issues, the Runtime Broker will also run frequently and consume a lot of CPU power.

 However, it's not necessarily the Runtime Broker that's broken; it's more likely that the app is buggy. Since it's a core Windows component, you cannot disable the Runtime Broker process, but you can end it in Task Manager as a temporary solution.

 When Runtime Broker shows high CPU usage, check your open apps and their permissions to identify possible problems. We've shown [how to manage app permissions on Windows 10](https://www.makeuseof.com/how-to-change-app-permissions-in-windows-10/); on Windows 11, head to **Settings > Apps > Installed apps**. Choose an app, click the three-dot button, then choose **Advanced options** to check its **App permissions**.

 If restarting your computer and updating the app doesn't help, consider reinstalling the app as it may be damaged.

 Runtime Broker is a mystery to many PC users. You might have spotted it running in your Task Manager and hogging CPU resources. Let's find out what the Runtime Broker process is and whether you need it.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>