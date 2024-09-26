---
title: "Decoding OS Issues: Mastering the Art of Finding & Fixing Error Messages Using Commands"
date: 2024-08-08T05:57:17.995Z
updated: 2024-08-09T05:57:17.995Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Decoding OS Issues: Mastering the Art of Finding & Fixing Error Messages Using Commands"
excerpt: "This Article Describes Decoding OS Issues: Mastering the Art of Finding & Fixing Error Messages Using Commands"
keywords: OS Error Solving,Command Line Troubleshooting,Fixing OS Errors,Debugging Operating Systems,Error Message Repair,Commands for OS Fixed,Mastering OS Fixes
thumbnail: https://thmb.techidaily.com/cfa45c8957851b057661f0d98a0c4cd9830d27a0c465cacef45307df647411ca.jpg
---

## Decoding OS Issues: Mastering the Art of Finding & Fixing Error Messages Using Commands

 Encountering random errors and crashes while using the operating system without an explanation can be frustrating. It also makes it harder to find the appropriate solutions, because you have no clue what caused the problem in the first place.

 In this guide, we will show you how you can use the Command Prompt utility to identify potential culprits behind annoying Windows errors. We will also discuss how you fix the issue using CMD as well.

<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Diagnose Windows Errors in the Command Prompt

 To solve a problem in Windows, such as an update error or a Blue Screen of Death, it's important to identify the potential causes of the issue. Windows comes with several utilities that can help you with this, one of which is Command Prompt.

 Below, we have discussed different ways of using Command Prompt to look up Windows error codes.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->
### 1\. Use the NET HELPMSG Command

 The NET HELPMSG command helps convert error codes into strings, which you can use to find relevant solutions for the problem. However, this command can only help you with system error codes, which are specific numerical values. This means you cannot use it for BSOD errors like the INACCESSIBLE\_BOOT\_DEVICE error.

Moreover, the numerical value of the error code must also be precise.

Here is how you can use this command:

1. Press the**Win + R** keys together to open a Run dialog.
2. Type "cmd" in Run and press the**Ctrl + Shift + Enter** keys together to open Command Prompt with administrative privileges.
3. Click**Yes** in the User Account Control prompt.
4. Once you are inside the Command Prompt window, type the command mentioned below and hit**Enter** to execute it. Replace <error code> with the numerical value of the code.  
`NET HELPMSG <error code>`
5. For instance, if the error code you want lookup is 8242, your command will be:  
`NET HELPMSG 8242​​​`  
![Execute the net helpmsg command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/net-helpmsg-error.jpg)

 Once you have the details on the error code, you can either look for solutions online or jump to the solutions listed later in this guide.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->
### 2\. Use the CertUtil Command

 Another easy way to look up error descriptions using the Command Prompt is by using the CertUtil command. This command is typically used for managing certificates and certificate services, but can also be a helpful tool in finding short explanations for the error codes.

Here is how you can use it:

1. Open Command Prompt using the steps we have described above.
2. In the Command Prompt window, execute the command below. Replace <error code> with the error code you are encountering:  
`CertUtil /error <error code>`
3. So for instance, if you are encountering the update error 0x80070002, your command will be:  
`CertUtil /error 0x80070002​​​​`  
![Execute the entered command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/certutil-command.jpg)

 You should now be presented with a description of the error message. You can use this detail to identify the culprit and eliminate it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600114&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Mac： Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
### 3\. Access the Event Viewer

 When you encounter an error on Windows, a log file for the error is created in the Event Viewer. This log file contains the details of the event, including the time and date it occurred, the error code associated with it, and the source of the event.

 You can [access the Event Viewer using the Command Prompt](https://www.makeuseof.com/windows-open-event-viewer/) to identify the culprit behind the error, and then proceed with the relevant solutions to fix the problem.

## How to Resolve the Problem Using the Command Prompt

 Once you have identified the problem, you can use the Command Prompt utility to fix it as well. Windows comes with a set of troubleshooting utilities that can you can run via this command-line interface to resolve system issues once and for all.

 Here are some common ways you can use the Command Prompt to diagnose and resolve various issues with your Windows operating system.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->
### 1\. Fix Any Corruption Errors

 There are a number of problems that may result from corruption errors and bugs within the operating system, such as frequent crashes and freezes, boot problems, data loss, and slow performance.

 The easiest way to fix such issues is by [running the built-in SFC and DISM tools](https://www.makeuseof.com/windows-built-in-repair-tools/) via Command Prompt.

<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Run SFC and DISM scans](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/scannow-restorehealth-cmd-1.jpg)

 SFC or the System File Checker works by scanning the protected system files to check their integrity. It will compare the files to a stable version stored in the Windows component store or the installation media. If a problem with the file is identified, the utility will automatically replace the file with its healthier counterpart and generate a report based on it.

 DISM, on the other hand, can be used to repair a wide range of issues, including system files, problematic drivers, and a corrupt Windows image. It is considered to be more advanced and powerful than SFC.

 Once you have completed an SFC scan, you can check the log file for more detailed information as well. Simply execute this command:

`findstr /c:"[SR]" %windir%\logs\cbs\cbs.log >"%userprofile%\Desktop\sfcdetails.txt`

 Doing so will create a log file named sfcdetails.txt on your desktop, listing all the issues found during the scan.

### 2\. Uninstall Windows Updates

 There are times when an update you install on the system turns out to be buggy or corrupt, leading to different issues within the system.

 Since Windows provides you with the option to uninstall updates, you can use Command Prompt to achieve this.

 Simply open Command Prompt as an administrator and execute the command listed below to view a list of installed updates:

`wmic qfe list brief /format:table`

 To uninstall one, execute the following command. Replace <HotFixID> with the ID number of the update that you want to uninstall.

`wusa /uninstall /kb:<HotFixID>`

![Uninstall the update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-update-cmd.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
### 3\. Fix Boot Issues

 If you are having trouble booting into Windows, or the boot time is just painfully slow, the issue is likely to be related to the boot sector or boot configuration data (BCD).

You can use the bootrec command to repair these via Command Prompt.

Here is how you can do that:

1. [Boot into WinRE](https://www.makeuseof.com/ways-to-boot-into-the-windows-recovery-environment/) and head over to Repair your computer.
2. Navigate to**Troubleshoot** \>**Advanced options** .  
![WinRE-Advanced-Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/winre-advanced-options.jpg)
3. Choose**Command Prompt** from the list of options available.
4. Once you are in the Command Prompt window, execute the following commands:  
`bootrec /fixmbr bootrec /fixboot bootrec /rebuildbcd`
5. If you are prompted with Add installation to boot list?, type Y and hit Enter.
6. Once all the commands are executed, you can exit Command Prompt by typing exit and hitting Enter.
7. Restart your computer, and you should be able to boot into Windows successfully!

## The Command Prompt to the Rescue

 Having knowledge of certain Windows tools can come in handy when dealing with various computer-related issues. One such utility that can help you find solutions is Command Prompt and knowing how to use it can save you both time and frustration.

 We highly recommend backing up your essential data before making any changes to your operating system, just to be safe. With a little patience and some troubleshooting skills, you can get rid of annoying Windows errors for good.


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




