---
title: Addressing Qt Plugin Initialization Failure Error
date: 2024-08-15T15:15:49.510Z
updated: 2024-08-16T15:15:49.510Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Qt Plugin Initialization Failure Error
excerpt: This Article Describes Addressing Qt Plugin Initialization Failure Error
keywords: Qt Plugin Fix Guide,Resolve QtErrorInit,QtPlugin Loading Issue,Correct Qt Plugin Error,QT Init Fail Solutions,Debugging Qt Initialization,Qt Plugin Troubleshooting Steps
thumbnail: https://thmb.techidaily.com/da7734e84e246f918bdf5e60b91499ba1ad1512932f71cc8b0057c6b83a1e49f.jpg
---

## Addressing Qt Plugin Initialization Failure Error

 Have you recently run into the “Application failed to start because no Qt platform plugin could be initialized” error? QT is a cross-platform app that is used to generate graphical user interfaces. Even if QT support for Windows platforms is extensive, your system might display the error message when you try to open OneDrive, OBS Studio, Python, or even video games.

 While this isn’t one of the common errors on Windows, you can still fix it using the tips below.

## 1\. Change the QT Files Location

 Sometimes, a simple trick such as changing the QT files location is enough to get rid of the error. Here’s how you can do it:

1. Launch File Explorer and open**This PC** .
2. Using the**Search** field, search for**pyqt5\_tools** .
3. When Windows finishes the search, right-click the**pyqt5\_tools** and head to**Open folder location** .
4. Head to**PyQt5 > Qt > bin** . Copy the**platforms** folder.  
![Fix qt error](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/platforms-folder-1.jpg)
5. Make a new search for**site-packages** and open the folder.
6. There, paste the**platforms** folder.
7. Windows will warn you there’s already a folder with the same name. Click**Replace the files in the destination** .

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Run an SFC Scan

 There’s a chance Windows display the “Application failed because no QT platform plugin could be initialized” error due to corrupt system files. Fortunately, Windows has a built-in tool to help you fix the problem.

 In the Start menu search bar, search for**command prompt** and select**Run as administrator** . Then, run the**sfc /scannow** command line. Windows will scan and automatically replace any corrupted system file.

![sfc-scan-1-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/sfc-scan-1-1.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->

 If the System File Checker didn’t fix the problem, there are [more built-in tools to repair corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) .

## 3\. Perform a Clean Boot

 One of the installed third-party apps might be the reason why you get the “Application failed because no QT platform plugin could be initialized” error. To test it,[perform a clean boot on Windows](https://www.makeuseof.com/clean-boot-windows-11/) , which will force it to boot with a minimal list of programs and drivers.

 If Windows stops displaying the error, it means something you've installed on your PC is causing the problem. Take a look at your installed apps, and remove any software that might be causing the problem. If you're unsure as to what might be doing it, slowly re-enable apps through the clean boot until the issue reappears.

## 4\. Update the Malfunctioning App

 An outdated version of the app you're trying to use might be the reason for the QT error. In this case, simply updating the app should solve the issue.

 If you’ve downloaded the app from Microsoft Store, launch it and head to**Library** . There, you’ll see a list of available updates. You can update the apps individually, or click**Get updates** to update them all.

![Update Microsoft Store apps](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/mcirosoft-store-1.jpg)
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
## 5\. Reinstall the Troublesome App

 As the error message hints, reinstalling the app might fix the problem. When reinstalling the app, make sure you get it from its official website, to avoid any future problems.

 If you're having issues getting rid of the app, check out [how to fix Windows when it won't allow you to uninstall a program](https://www.makeuseof.com/windows-cant-uninstall-program-fix/) .

## 6\. Uninstall Any Recent Windows Updates

 Sometimes, Windows display the “Application failed because no QT platform plugin could be initialized” error after a system update. In this case, you can load a restore point to undo the change and get rid of the error.

 But if there’s no restore point available, you can manually uninstall Windows updates.

1. Launch Windows Settings by pressing**Win + I** .
2. From the left pane, click**Windows Update > Update History** .
3. Head to**Related Settings** and click**Uninstall updates** .
4. Right-click the latest update and select**Uninstall** .

![Uninstall recent Windows updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/uninstall-updates-1.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
## Get Rid of the QT Error on Windows

 Hopefully, one or more of the above solutions helped you fix the “Application failed to start because no Qt platform plugin could be initialized” error.

 Sometimes, it’s difficult to figure out the exact cause of a Windows error, and reinstalling the app every time might not be the most efficient solution. To speed up the troubleshooting process, you should use one of the many Windows repair tools.


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






