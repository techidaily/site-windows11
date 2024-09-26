---
title: Ceasing Autonomous Openings in Microsoft Shop App
date: 2024-08-15T15:53:39.723Z
updated: 2024-08-16T15:53:39.723Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Ceasing Autonomous Openings in Microsoft Shop App
excerpt: This Article Describes Ceasing Autonomous Openings in Microsoft Shop App
keywords: MSOpenAutonomyEnd,AutoOpenShutdownMS,MSShopClosedown,EndOpennessMsApp,ShopMSCloseOpens,ClosingAutoMsStore,StopOpenerMsShop
thumbnail: https://thmb.techidaily.com/6de10ca092ea22440e0ee57b0e4d9c17ed8937d0ae7586606e65eab4d9ad7104.jpg
---

## Ceasing Autonomous Openings in Microsoft Shop App

 The Microsoft Store has come a long way since its introduction to Windows 8\. Every app, game, or movie available on the store is certified, so you don’t have to worry about infecting your computer with malware.

 But what if Windows keeps opening the Microsoft Store for no apparent reason? If you’ve run into the same issue, this guide should help you fix it.

##

## 1\. Close Microsoft Store's Background Processes

 Windows might keep opening the Microsoft Store if there’s a process still running in the background. To fix it, you should use Task Manager to stop any background activity.

 Press**Ctrl + Shift + Esc** to bring up Task Manager. There, right-click**Microsoft Store** and select**End task** .

![Close Windows Store with Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/task-manager-1.jpg)

##

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Restart the Microsoft Store Services

 There’s a chance that the Microsoft Store keeps acting up because of a service malfunction. The Microsoft Store Install Service is the one that works in the background to keep the store working.

 This is why restarting the service might be enough to fix Microsoft Store.

1. In the Start menu search bar, search for**services** and select**Run as administrator** .
2. In the Services window, locate and open**Microsoft Store Install Service** .
3. Click**Stop > Start** to restart it.
4. Restart your computer and monitor if Microsoft Store keeps opening.

![Restart Microsoft Store service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/store-service-1.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Re-register Microsoft Store

 If nothing worked until now, you could re-register the Microsoft Store app. To do it, launch PowerShell with administrative rights and paste this code:

`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}<strong> </strong>`

 Then, press**Enter** to run it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
## 4\. Apply Generic Fixes for Microsoft Store Issues

 You may encounter this problem if the cache has become corrupted. As such, check out [how to fix a damaged Microsoft Store cache](https://www.makeuseof.com/ways-to-fix-damaged-microsoft-store-cache/) for more ways to fix this annoying problem.

 Similarly, a virus may be causing the Microsoft Store to open. Check out [how to remove malware using a Microsoft Defender offline scan](https://www.makeuseof.com/how-to-remove-malware-using-microsoft-defenders-offline-scan/) and give your PC a deep clean.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->
## Fix the Microsoft Store App Opening Itself

 Having the Microsoft Store app open by itself can be very disruptive, especially if it opens on top of all windows. Hopefully, one of these solutions worked and Microsoft Store has stopped launching by itself.

 If you’ve had enough and uninstalled it, you can still get Microsoft apps without the Microsoft Store.


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






