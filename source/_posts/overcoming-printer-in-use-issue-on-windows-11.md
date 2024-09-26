---
title: Overcoming Printer In Use Issue on Windows 11
date: 2024-08-15T16:10:32.773Z
updated: 2024-08-16T16:10:32.773Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Printer In Use Issue on Windows 11
excerpt: This Article Describes Overcoming Printer In Use Issue on Windows 11
keywords: Win11 Print Fix,PC Printer Error,Resolve XP On Windows,Stop XP Freeze,Inkjet Issue Fix,Toner Troubleshoot,HP Printer Support
thumbnail: https://thmb.techidaily.com/fbf47cff7f90b38c5c4bfba881d1b7d8a9950edbba1743d545a40ebc632bb6c9.jpg
---

## Overcoming Printer In Use Issue on Windows 11

 Printing documents and images is essential for many users. However, some users’ printers don’t print because of a Windows error message that says, “Another computer is using the printer.” Users have reported this error message appears when they select to print in Windows software packages.

 This error message suggests the printer can’t print because it’s already in use by another computer. However, the error also arises for home users who aren’t sharing their printers with other computers on organization networks. This is how you can fix the “Another computer is using the printer” error on Windows 10 & 11\.

## 1\. Restart the Printer

 Restarting the printer is a simple possible fix that’s worth a try. The printer could be stuck with a preceding request, which applying this solution might resolve. So, power off your printer for a few minutes and then turn it back on to see if that makes a difference.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
<!-- affiliate ads end -->
## 2\. Deselect the "Allow Windows to Manage My Default Printer" Option

 The **Allow Windows to manage my default printer** option sets the most recently used printer to be the default one when enabled. This can cause issues if the printer with which you’re trying to print isn’t set as default. You can turn off that setting as follows:

1. Right-click the button for opening the Start menu to select **Search**.
2. Type **printers & scanners** inside the search utility.
3. Select **Printers & scanners** to open that Settings section.
4. Turn off the **Allow Windows to manage my default printer** setting by clicking that option’s toggle switch.  
![The Allow Windows to manage my default printer option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/allow-windows-to-manage-default-print-driver.jpg)
5. Then select your printer in Setting to click its **Set as default** button.  
![The Set as default button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/set-as-default.jpg)

 You might see an alternative WS printer listed in Settings (most typically for Canon models). The WS stands for web services, and that printer shouldn’t be your default one. Make sure your standard printer is set as default.

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
## 3\. Utilize the Print Troubleshooter

 Windows has a Printer troubleshooter that’s there to detect and resolve all manner of printing issues. So, that troubleshooter could feasibly offer a solution for the “Another computer is using the printer” error. This [how to run any troubleshooter post](https://www.makeuseof.com/run-troubleshooter-windows-10-11/) explains how you can access that troubleshooter in the Windows 11/10 Settings app.

![The Printer troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/printer-troubleshooter.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600114&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Mac： Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->

 Make sure the printer’s cable is connected to your PC before running the Printer troubleshooter if it’s a non-wireless one. Then select your printer model within the troubleshooter and apply the potential fixes suggested.

## 4\. Start or Restart the Print Spooler

 Print spooler is a service for handling print jobs. Some users say they’ve been able to fix the “Another computer is using the printer” error by restarting that service. You can apply that resolution by following the step-by-step instructions in our [how-to restart the printer spooler article](https://www.makeuseof.com/windows-restart-print-spooler-service/). If the service isn’t already running, click its **Start** option.

![The Restart option for the Print Spooler service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-restart-option.jpg)

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Clear the Printers Folder

 The Printers folder is a spooler directory that stores print jobs in the queue. Deleting files in that folder is a potential solution for the “Another computer is using the printer” error as that will clear the print queue. This is how you can clear the Printers folder on Windows 11/10:

1. To open Services, press the **Windows** logo + **R** key combination, type **services.msc** into Run, and select **OK**.
2. Right-click the **Print spooler** service and select **Stop**.  
![The Stop option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-stop-option.jpg)
3. Press the **Windows** \+ **E** keyboard keys to activate the file manager tool.
4. Go to this folder path:  
`C:\Windows\System32\spool\PRINTERS`
5. Select everything in the Printers folder by pressing **Ctrl** \+ **A**.  
![The PRINTERS folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-printers-folder.jpg)
6. Press the **Del** keyboard button to erase the selected files.
7. Return to the Services app, right-click **Print** **spooler**, and select **Start**.

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Disconnect Previous Users

 If you share your PC with other users, the “Another computer is using the printer” error could be due to a previous user who hasn’t been completely logged off. You can remedy that by disconnecting previous users with Task Manager like this:

1. Right-click any space on the taskbar to select the **Task Manager** shortcut.
2. Click the **Users** tab.
3. Right-click a previous user shown on the **Users** tab and select **Disconnect**.  
![The Disconnect option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-users-tab.jpg)
4. Repeat the previous step to disconnect all users other than yourself shown within Task Manager.

## 7\. Update the Printer’s Driver

 Antiquated printer drivers can cause lots of printing issues. So, you may need to update your printer’s driver to resolve the “Another computer is using the printer” error if other potential solutions aren’t effective.

 You can update a printer’s driver by manually downloading it from the manufacturer’s website. The Epson, HP, Cannon, Brother, and Xerox sites include driver download sections for their respective printer models. When you’ve downloaded the driver for your printer, you can double-click on the driver setup package to install it. This article about [finding and replacing outdated drivers on Windows](https://www.makeuseof.com/tag/find-replace-outdated-windows-drivers/) provides further details for updating device drivers.

![The printer driver downloads section on the HP website](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/printer-driver-downloads-section.jpg)
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## Print, Print, and Print Again on Windows

 Getting the “Another computer is using the printer” error fixed is essential for the many users who can’t afford to lose printing functionality. Fortunately, lots of users have resolved that printing issue with the potential Windows 11/10 fixes covered here. So, applying them will probably get that issue sorted on your Windows PC, and then you can print to your heart’s content again.

 This error message suggests the printer can’t print because it’s already in use by another computer. However, the error also arises for home users who aren’t sharing their printers with other computers on organization networks. This is how you can fix the “Another computer is using the printer” error on Windows 10 & 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>



