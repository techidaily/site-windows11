---
title: Combatting 'Memory Test Failed' In Windows
date: 2024-08-15T15:53:42.856Z
updated: 2024-08-16T15:53:42.856Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Combatting 'Memory Test Failed' In Windows
excerpt: This Article Describes Combatting 'Memory Test Failed' In Windows
keywords: Fixing Memory Errors in Win,Overcoming MemTest Fail,Troubleshooting MemError Win,Resolving Memory Test Error,Addressing Windows Memory Issue,Avoiding MemTest Crashes Win,Steps to Stop MemTest Failure
thumbnail: https://thmb.techidaily.com/68fb059a648e909d234d3bab20298ad1bdfcbd57c7ecdd3b24dbb573f2037e37.jpg
---

## Combatting 'Memory Test Failed' In Windows

 Using the Windows Memory Diagnostic tool, you can diagnose memory issues on your Windows computer. If there is a problem, it will return an error. One common Windows Memory Diagnostic error you may encounter is "Hardware problems were detected; contact manufacturer," followed by the "You have a memory problem" dialog.

 This error can be a false positive. You can also confirm the same by using a third-party memory diagnostic tool. In case of a hardware issue, you may need to replace the memory stick or repair the memory slot, if possible.

## What Causes the Windows Memory Diagnostic Hardware Problems Were Detected Error?

 This error is often triggered after a blue screen of death (BSOD) or the system freezing issues. The reason for the error can vary and include faulty memory slots and memory sticks. It can also be a false positive due to a Windows OS glitch.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## 1\. Check for Overclocking Issues

 Incorrect overclocking can cause hardware issues. While faster RAM can help you achieve good performance, it is important to consider the hardware limitations before applying the tweaks.

 If you have overclocked your RAM, try to lower the frequencies to see if the error goes away. Do this until you find a safe frequency, or reset it to factory default settings.

 If you are unsure about the default memory frequencies, try to perform a BIOS reset. Load the BIOS default, which should reset the RAM frequencies to its factory default. Refer to your motherboard manufacturer manual for specific instructions.

## 2\. Run the Hardware Troubleshooter

 The built-in Windows hardware troubleshooter can scan for hardware-related issues and even try to perform a repair if possible. If you haven’t tried already, run the hardware troubleshooter using the Command Prompt to resolve the problem.

 Note that it is a legacy troubleshooter, and you may not find it in the Windows 11 version newer than 22H2\.

 To run the Windows Hardware Troubleshooter:

1. Press the **Win** key and type **cmd**.
2. Right-click on **Command Prompt** and select **Run as administrator**. Click **Yes** if prompted by the User Account Control dialog.  
![run windows hardware troubleshooter command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-windows-hardware-troubleshooter-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. In the Command Prompt window, type the following command and press **Enter**:  
`msdt.exe -id DeviceDiagnostic`
4. In the **Hardware and Devices** dialog, click **Next**. By default, the troubleshooter is set to apply any repairs available. To disable automatic repair, click **Advanced** and uncheck the **Apply repairs automatically** option.  
![hardware and devices troubleshooter windows 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/hardware-and-devices-troubleshooter-windows-1.jpg)
5. It will scan your computer for issues, which may take a few minutes. If an issue is detected, select to automatically apply the repair.
6. If the suggested problem is unrelated to memory, you can skip it to see the next problem. The troubleshooter will detect additional issues. If an issue is found, apply the fixes and check for any improvements.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4708689&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Win： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
## 3\. Remove and Reinsert Your Memory Sticks

 If you work with multiple memory sticks, remove all the sticks and wipe the card to remove dust and debris. Reboot the computer and check for any improvements.

 Still not working? Remove all but one stick and reboot your computer to see if the error is resolved. If not, repeat the procedure with all the sticks individually to determine and detect a faulty memory stick. If you find a faulty memory module, you can get a replacement or claim a warranty if available.

 If the issue persists, check your memory (RAM) slots for fault. Insert a memory stick into one of the slots and reboot your computer. If there is no error, test other slots and check if you can find a malfunctioning slot.

 If you determine a faulty RAM slot to have caused the issue, repairing it is tedious. First, RAM slots aren’t easily accessible like memory sticks. Second, to replace the slot, you’ll need to find a spare but compatible motherboard with working slots and then solder the connections onto your motherboard.

 If repairing the slots is not possible, your only option is a motherboard replacement. Depending on your system configuration, this can be an expensive solution. Or you can continue to use the system without utilizing the faulty memory slot, albeit with reduced performance.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
## 4\. Test Your RAM with MemTest86+

 If the troubleshooter fails to detect any issue, you can perform a memory test using the MemTest86+ utility. It is an open-source memory testing tool to check for fails in your computer memory.

 MemTest86+ is a bootable utility and cannot be used from within Windows. To test your RAM with Memetst86+, you’ll need a USB drive. You can use the Memtest86+ Windows installer to create a bootable drive and boot from it.

 As of writing this article, Memtest86+ wasn’t compatible with Windows Secure Boot. So, you’ll need to disable Secure Boot to use the utility.

 To perform a memory test using Memtest86+:

1. Connect a USB flash drive to your computer. Take a backup of important data in the drive, as all the data will be deleted during the process.
2. Next, go to the [metest86+ page](https://www.memtest.org/) and download the latest version available.
3. Run the installer and select your USB drive. Make sure to select the format option.  
![memtest86 plus create bootable usb drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/memtest86-plus-create-bootable-usb-drive.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
4. Click **Next** and wait for the installer to create a bootable drive.
5. Next, if you haven’t already, [disable Secure Boot on your Windows computer](https://www.makeuseof.com/tag/disable-secure-uefi-dual-boot/).
6. Next, power off your computer. You may also need to clear your motherboard CMOS to reset your BIOS to factory default settings. You can also [reset BIOS to its default configuration](https://www.makeuseof.com/tag/reset-bios-default-settings-computer/) from the BIOS menu.  
![memtest86 plus memory integrity test in progress](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/memtest86-plus-memory-integrity-test-in-progress.png)
<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Next, plug the Memtest86+ bootable USB drive into your computer and turn it on.
8. Boot into the Boot Menu and select the bootable USB drive as the boot device. The hotkey key to enter the Boot Menu may vary depending on your computer manufacturer. You can press **F9** on an **HP** computer, **F12** on a **Dell** computer and so on to access the **Boot Menu**.
9. Memtest86+ will automatically start the memory integrity check. Let Memtest86+ complete at least 2 passes; the more, the better. Press the **Esc** key to stop the test if there are no errors after multiple passes.

 If an error is detected during testing, it is likely a case of faulty RAM and may need replacement. But to be on the safer side, ensure you test each RAM separately to find the odd one out.

 Not all the errors detected by the Memtest86+ are due to faulty hardware. Some errors may occur due to compatibility issues. Check your RAM module and the motherboard specifications to determine any compatibility issues. You can also test the RAM modules by inserting them into a different motherboard and see if it works.

## 5\. Perform a Repair Reinstall or Clean Install Windows

 If the Windows Memory Diagnostic tool continues to show the hardware problem was detected error, even after the Memtest86+ passed the test, check if the problem is due to issues with the Windows operating system.

 To fix critical issues with your Windows image, you can perform a [repair reinstall of Windows 11 without deleting apps](https://www.makeuseof.com/windows-11-reinstall-without-deleting-apps/). If that does not work, perform a clean install. This will reinstall the operating system but delete all your apps and data from the computer. So, backup any data you need before attempting a clean install.

## Fixing the Memory Diagnostic Tool "Hardware Problem Detected" Error

 When an error is detected with your memory modules, the Windows Memory Diagnostic tool will show an error. While memory-related issues are often due to faulty hardware, make sure to run the device hardware troubleshooter to detect and resolve minor glitches.

 Alternatively, perform a memory integrity check using the Memtest86 tool. If the memory modules pass the Memtest86, you may need to perform a Windows OS clean install to fix issues with the Windows system files.

 This error can be a false positive. You can also confirm the same by using a third-party memory diagnostic tool. In case of a hardware issue, you may need to replace the memory stick or repair the memory slot, if possible.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>



