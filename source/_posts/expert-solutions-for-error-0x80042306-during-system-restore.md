---
title: Expert Solutions for Error 0X80042306 During System Restore
date: 2024-08-15T15:28:52.402Z
updated: 2024-08-16T15:28:52.402Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Expert Solutions for Error 0X80042306 During System Restore
excerpt: This Article Describes Expert Solutions for Error 0X80042306 During System Restore
keywords: Error Code 0X80042306 Fix,System Restore Issue Resolved,Solve Restore Error 0X80042306,Troubleshoot Windows Error 0X80042306,Correcting Restore Error Code X,Overcoming Restore Error 0X42306,Fix Error 0X80042306 System Restore
thumbnail: https://thmb.techidaily.com/de2b8c65401e9876b1b1a5fbf84a14916f9f22a18062d51200fd6852f871f665.jpg
---

## Expert Solutions for Error 0X80042306 During System Restore

 The error code 0x80042306 occurs when attempting to create a restore point in Windows. It prevents the creation of new restore points in the system and typically occurs when your system does not have sufficient free space, there is a problem with the Volume Shadow Copy service (VSS), or a background process is conflicting with the restore utility.

 Below, we talk about the different troubleshooting methods you can try to fix the system restore error 0x80042306 in Windows. We recommend booting into the administrator account before you proceed.

## 1\. Make Sure You Have Sufficient Space

 Restore points require free space on the disk they are stored. This amount of space required by a restore point typically depends on on the size and complexity of your system configuration.

 If you do not have sufficient space on the disk, the restore utility is likely to return a 0x80042306 error. This is why, we recommend getting started by making sure that enough free space for the System Restore to function correctly. You can delete unnecessary items to increase the space manually, or [use the Disk Cleanup](https://www.makeuseof.com/tag/best-way-clean-windows-10-step-step-guide/) utility that is offered by Microsoft by default.

 Alternatively, you can also increase the amount of disk space allocated for System Restore in the System Protection settings. Here is how you can do that:

1. Type "Create a restore point" in the Windows search utility and click**Open** .
2. In the following dialog, head over to the**System Protection** tab.
3. Click on the**Configure** button and use the Max usage to slider to adjust the disk percentage according to your preference.  
![Adjust the Max usage slider](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/restore-point-usage.jpg)
4. Click**Apply** \>**OK** to save the changes.

 Once the changes are made, check if you can now create a restore point without any issues.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
## 2\. Restart the Volume Shadow Copy Service

 You might also be facing the problem if the Volume Shadow Copy service is disabled or simply not functioning properly.

 This service allows the creation of backup copies for files and volumes in Windows. It is used to by the restore utility to create snapshots of the items that are being backed up and if it fails to work due to any reason, you might encounter the problem at hand.

 To ensure this service is working properly, you can restart it using the Services utility. Follow the steps below to proceed:

1. Press the**Win** +**R** keys together to open Run.
2. Type "services.msc" in Run and click**Enter** .
3. In the services window, scroll down to locate the**Volume Shadow Copy** service and right-click on it.  
![Volume Shadow Copy service in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/volume-shadow-copy.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
4. Choose**Properties** from the context menu.
5. Now, click on the**Stop** button, wait for a few seconds, and hit**Start** again.
6. Make sure the Startup type is set to**Automatic** .  
![Start the VSS service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/start-vss-service.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
7. Finally, click**Apply** \>**OK** to save the changes.

 Do the same for the Windows Backup service and check if the issue is resolved.

## 3\. Re-Register VSS Components

 If restarting the Volume Shadow Copy service did not work, then you can also try re-registering the VSS components via Command Prompt.

Here is how to proceed:

1. Press the**Win** +**R** keys together to open Run.
2. Type "cmd" in Run and press the**Ctrl** +**Shift** +**Enter** keys together to open Command Prompt as an administrator.
3. Click**Yes** in the User Account Control prompt.
4. Now, execute the following commands one by one:  
`cd /d %windir%\system32net stop vssnet stop swprvregsvr32 /s ole32.dllregsvr32 /s oleaut32.dllregsvr32 /s vss_ps.dllvssvc /registerregsvr32 /s /i  

swprv.dllregsvr32 /s /i eventcls.dllregsvr32 /s es.dllregsvr32 /s stdprov.dllregsvr32 /s vssui.dllregsvr32 /s msxml.dllregsvr32 /s  

msxml3.dllregsvr32 /s msxml4.dllvssvc /registernet start swprvnet start vss`
5. Once you have re-registered VSS components, close Command Prompt and try creating a restore point again.

 If an issue within the VSS components was causing the problem, restarting the components should fix it.

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Create a Restore Point in Safe Mode

 In some cases, a conflicting background process can also prevent the System Restore utility from creating a restore point successfully. The best way to ensure there are no applications or programs in the background interrupting the functionality of System Restore, try creating a restore point in Safe Mode.

 This mode launches Windows with a minimal set of drivers and services, which can help isolate the issue and prevent any conflicts that may be occurring in normal mode.

Here is how you can boot in Safe Mode:

1. Type "System Configuration" in Windows search and click**Open** .
2. Head over to the**Boot** tab and under Boot Options, checkmark the Safe Boot option.
3. Choose**Minimal** and click on**Apply** \>**OK** to save the changes.  
![Minimal mode of Safe Boot](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/msconfig-boot-safe-mode-minimal.jpg)

 You can now restart your computer and upon reboot, you should enter the Safe Mode automatically. Try recreating a restore point and check if the problem is resolved.

## 5\. Scan the System For Corruption Errors

![Running Sfc scan in CMD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/running-sfc-scan.jpg)
<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The System Restore utility itself might be dealing with a corruption error, which is preventing it from functioning properly.

 To fix any corrupt system files, we suggest using the System File Checker (SFC) and Deployment Image Servicing and Management (DISM) tools. SFC works by scanning the protected system files for underlying problems. If an issue is discovered, it will replace the faulty file with its healthier cached counterpart.

 DISM, on the other hand, works by repairing corrupt system images. We have a guide on [how to use SFC and DISM in Windows](https://www.makeuseof.com/windows-built-in-repair-tools/) which you can refer to, to perform the steps correctly.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
## System Restore Back On Track

 The System Restore utility in Windows is a powerful tool that can save you from losing important data in case of unexpected system issues. That said, it can be annoying if you cannot create a restore point easily, especially when you are trying to do it before performing a critical action.

 By following the methods outlined in this guideline, you can diagnose the error and take necessary steps to resolve it. We recommend making sure all the relevant services stay enabled, and your system is up-to-date to avoid any such issues in the future.


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






