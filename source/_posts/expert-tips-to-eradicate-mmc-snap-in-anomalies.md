---
title: Expert Tips to Eradicate MMC Snap-In Anomalies
date: 2024-07-29T04:22:56.992Z
updated: 2024-07-30T04:22:56.992Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Expert Tips to Eradicate MMC Snap-In Anomalies
excerpt: This Article Describes Expert Tips to Eradicate MMC Snap-In Anomalies
keywords: Snapping Fix Guide,Expert MMC Troubleshooting,Eliminate Snap-In Errors,Eradicate MMC Anomalies,Tips for MMC Repair,MMC Issue Resolution,Professional MMC Fixing
thumbnail: https://thmb.techidaily.com/8ec7f9d19b5395810145f1bf31b1db142a6ba9be6ed8b5f1e4a621d2eef1f390.jpg
---

## Expert Tips to Eradicate MMC Snap-In Anomalies

 The "MMC could not create the snap-in" error has been around for some time and still seem to bug some users now and then. The error occurs when you try to open an administrative tool such as an Event Viewer, Task Scheduler, and so forth.

 Sometimes, the error may also pop up after a Blue Screen of Death (BSOD), causing one or more apps to crash. This error often occurs if the registry configuration of the snap-in is malfunctioning. Here we show a few ways to fix to help you resolve the "MMC could not create the snap-in" error and restore administrative tools access in Windows.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
## 1\. Fix the Broken Registry Configuration for the Snap-In

![delete-registry-key-mmc-snap-in-windows-registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/delete-registry-key-mmc-snap-in-windows-registry.jpg)

 If the registry configuration for the affected snap-in is broken, it may trigger the "MMC could not create the snap-in" error. To fix the issue, you’ll need to delete the corrupt registry entry associated with the snap-in. Here’s how to do it.

 Making incorrect modifications to the Windows Registry involves risk and may cause your system to malfunction. We recommend you [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and [make a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) to be on the safe side.

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK**.
3. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\MMC\SnapIns`
4. The **SnapIns** key consists of multiple sub-keys. You need to locate the sub-key identical to the **CLSID** shown in the error message.
5. For example, if the error occurs when opening Event Viewer, you’ll likely see **CLSID: c7b8fb06-bfe1-4c2e-9217-7a69a95bbac4**, and so on. So, note down the **CLSID** shown in the error screen.

1. In the **Registry Editor**, select the sub-key folder with the same name as the error **CLSID**.
2. Next, right-click on the same sub-key folder and select **Delete**.
3. Click **Yes** to confirm the action.
4. Close the **Registry Editor** and restart your computer.
5. After the restart, open the administrative tool snap-in to see if the error is resolved.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698998&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/MacBook_Pro_lyrx-withsinger-tv.png" border="0">LYRX is an easy-to-use karaoke software with the professional features karaoke hosts need to perform with precision. LYRX is karaoke show hosting software that supports all standard karaoke file types as well as HD video formats, and it’s truly fun to use. 
LYRX Karaoke Software MAC/WINDOWS (Includes Activation For 3 Machines)</a>
<!-- affiliate ads end -->
## 2\. Enable .NET Framework

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=14095146&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8b6cc3ee5ec407721ce3bf5ff4c0f56b/PRO_BUY_728x90-EN.jpg" border="0"></a>
<!-- affiliate ads end -->
![enable net framework 3 5 windows features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-net-framework-3-5-windows-features.jpg)

 You can also fix this error by enabling .NET Framework 3.5\. The idea is that one of the snap-ins on your PC may need .NET Framework 3.5 to work. So, if the feature is disabled, you may encounter an error.

 Fortunately, you can easily enable the .NET Framework feature using the Turn Windows features on or off dialog. Here’s how to do it.

 To enable .NET Framework 3.5:

1. Press the **Win** key and type **Windows features** and click on **Turn Windows features on or off** from the search results.
2. In the **Windows Features** dialog, select the **.NET Framework 3.5 (include .NET 2.0 and 3.0)**.
3. Next, click the **Plus** icon to expand the section and select the options ‘**Windows Communications Foundation HTTP Activation**’ and **‘Windows Communications Foundation Non-HTTP Activation**’.
4. Next, click to **Apply** the changes and install the feature.
5. Once installed, you’ll be prompted to restart the computer. Restart your system, and the MMC snap-in should work now.

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Check for and Repair Corrupt System Files

![DISM scan health restore health command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dism-scan-health-restore-health-command-prompt.jpg)

 If you have one or more corrupt system files, it may cause issues with the system apps. You can run the System File Checker tool to determine if the problem is due to system file issues. It will scan and check the integrity of systems files and automatically repair them to fix the problem.

 Microsoft recommends running its built-in Windows image check and repair utility, Deployment Image Servicing and Management (DISM), before running the System File Checker utility.

 If you're not sure how to run either of these tools, we cover both in our guide on [how to repair corrupt Windows files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Remove and Reinstall the Microsoft Visual C++ Redistributable

![repair microsoft visual c plus plus distributable package](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/repair-microsoft-visual-c-plus-plus-distributable-package.jpg)

 If the issue persists, try to fix and repair issues with the Visual C++ Redistributable package. If there are any issues with the package, it can cause the MMC snap-ins to stop working.

 To repair the Visual C++ Redistributable package:

1. Press **Win + R** to open Run.
2. Type "control" and click **OK** to open Control Panel.
3. In Control Panel, click on **Uninstall a program** under **Programs**.
4. Locate and select the **Microsoft Visual C++ Redistributable** entry and click **Uninstall**.
5. In the **Modify Setup** dialog, click **Repair**. The repair process may take a few minutes to complete.
6. Once done, restart your computer and check for any improvements.

 If the issue persists, reinstalling the Visual C++ Redistributable package may be required. To reinstall the package:

![uninstall microsoft visual c plus plus distributable package](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/uninstall-microsoft-visual-c-plus-plus-distributable-package.jpg)

1. Select the **Microsoft Visual C++ package** in Control Panel and click on **Uninstall**.
2. Click **Uninstall** in the **Modify Setup** dialog.
3. Click **Finish** to complete uninstallation. Repeat the process for all the Visual C++ Redistributable packages.
4. Once done, head over to the [Microsoft Visual C++ Redistributable package page](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170).
5. Download the latest version of the package available on your computer. Depending on your system compatibility, you can select from ARM64, X86, and X64 architecture versions.
6. Run the executable file to install the package and follow the on-screen instructions.
7. Once installed, restart your computer and check if MMC snap-ins are now working.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->
## Fix the MMC Snap-In and Restore Your Administrative Tools on Windows

 This error is triggered when a snap-in malfunctions, which is often a case of broken registry configuration. To fix the issue, you can delete the broken registry sub-key for the affected snap-in. Additionally, enable/re-enable the .NET Framework 3.5\. If not, scan the system for file integrity issues with the DISM and System File Checker utility.

 Alternatively, you can use the Remote Server Administration Tools (RSAT), which has additional features. RSAT is only available on the Pro and Enterprise edition of the Windows OS. However, you can run a PowerShell script to install it on the Windows Home version easily.

 Sometimes, the error may also pop up after a Blue Screen of Death (BSOD), causing one or more apps to crash. This error often occurs if the registry configuration of the snap-in is malfunctioning. Here we show a few ways to fix to help you resolve the "MMC could not create the snap-in" error and restore administrative tools access in Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>



