---
title: Resolving Failures of File Segmentation Service
date: 2024-08-22T21:37:05.953Z
updated: 2024-08-23T21:37:05.953Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving Failures of File Segmentation Service
excerpt: This Article Describes Resolving Failures of File Segmentation Service
keywords: FileSegmentFail,SegmentErrorCure,FixFileSeparate,ResolveSegmentFault,DefectiveFileSplit,ServiceFailureRevamp,CorrectSegmentService
thumbnail: https://thmb.techidaily.com/33139754522d3393b0a998cc016bffa1b55254150a3f5abcd672e5d0c2f8e9f3.jpg
---

## Resolving Failures of File Segmentation Service

 The Disk Defragmenter tool is a Windows user's best friend. This tool fixes fragmentation issues so that your hard drive runs smoother, but it itself sometimes comes across problems of its own. If you're having trouble with your disk defragmenter, there are a few things you can do to resolve the problem.

 In this article, you will learn how to fix the Disk Defragmenter so it works properly again.

## What Is the Disk Defragmenter? Why Does It Stop Working?

 The Disk Defragmenter tool rearranges files on your hard drive so that they are stored in a contiguous manner. This helps to improve file access speed and overall system performance. Disk fragmentation can occur over time as you add, remove, and modify files on your hard drive.

 Although a disk defragmenter is an important tool for keeping your computer running smoothly, sometimes it does not work as it should. Here are a few things that can cause the disk defragmenter to stop working:

1. The tool won't work if you have a solid-state drive (SSD). SSDs don't need to be defragmented because they don't have the same type of moving parts that traditional hard drives do.
2. Another possibility is that you have a virus or malware on your computer that's interfering with the disk defragmenter. You can try running a virus scan to see if that fixes the problem.
3. Corrupt system files can also cause the service to malfunction. In such a case, it may be worthwhile running an SFC (System File Checker) scan as a way to diagnose the problem.

 Now we know what causes the Disk Defragmenter to stop working, it's time to look at some solutions that may help you fix the problem.

## 1\. Check Disk Defragmenter's Status

 If your computer is running slowly, one potential reason could be that the Disk Defragmenter service is not running properly. This service helps to optimize your hard drive by rearranging files so that they can be read more quickly and efficiently.

 To check if the Disk Defragmenter service is running properly, follow the steps:

1. Open the Services app (see[ways to open the Services app on Windows](https://www.makeuseof.com/windows-11-open-services-app/) ).
2. Scroll down to the "Optimise drives" service and double-click on it.
3. Click on the drop-down menu and set the Start type to "Manual."
4. Make sure the Service status is "Running." If it is not, then click on**Start** to run it.  
![Set Optimise drives Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Set-Optimise-drives-Properties.jpg)
5. Click**Apply > OK** to save it.

 After making the above changes, check if it solves the problem. If not, move on to the next solution.

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Run the System File Checker tool

 Another way to fix your disk defragmenter is to run the System File Checker tool. This tool will scan all of your system files and replace any that are corrupt or missing.

To run the System File Checker, follow these steps:

1. Press**Win + X** on your keyboard to open the Power User menu.
2. Select the**Run** option from the menu list.
3. In the Run command dialog box, type "cmd" and press**Ctrl + Shift + Enter** at the same time.
4. When UAC appears on the screen, select**Yes** to approve administrator access.
5. Once you're in the Command Prompt window, type "sfc /scannow", and press**Enter** .

 It may take a while for the scan to complete, so be patient. Once the scan is complete, restart your computer and try running Disk Defragmenter again. It should now work properly.

![SFC and DISM Scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/SFC-and-DISM-Scan.jpg)

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->
 If you're still having trouble with your Disk Defragmenter tool after running an SFC scan, you may need to use the DISM utility. To do this, open the Command Prompt as an administrator and run the below command line:

`DISM /Online /Cleanup-Image /ScanHealth\nDism.exe /online /cleanup-image /restorehealth`

 Once the scan is complete, restart your computer and try defragmenting again.

## 3\. Run the CHKDSK Utility

 If your computer's Disk Defragmenter is still not working, you can try[running the CHKDSK utility](http://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) . This is a computer program designed to check the integrity of your hard drive, identify errors, and fix them.

To run the CHKDSK utility, follow the below steps:

1. Press the Windows key and search for "Command Prompt".
2. Right-click on the search result and select**Run as administrator** .
3. Click**Yes** if UAC prompts on your computer screen. This will open a Command Prompt with admin access.  
![Run chkdsk command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Run-chkdsk-command.jpg)
4. When you're in Command Prompt, type the following command and press Enter:  
<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->
`chkdsk C: /f`

 In the command above,**"C:"** represents your drive, so you should replace it with the letter that refers to your drive.

 Once the scanning process is completed, and you have been informed that your drive has been scanned, try to defragment it again.

 As it turns out, it may take several minutes for the scan to complete, depending on the size of your partition and sometimes it seems to get stuck. However, you should let it complete its task uninterrupted.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
<!-- affiliate ads end -->
## 4\. Close All Third-Party Applications

 Some third-party applications may interfere with Disk Defragmenter if they are running. In such a case, close all third-party programs and see if that helps the defragmenter to run properly.

 If you close all active windows and find that the defragmenter is still having issues, there might be a background process interfering with it. As such, you can try ending some third-party processes and see if that fixes it.

1. Press**Ctrl + Shift + Esc** on your keyboard to open the Task Manager.
2. On the Processes tab, find a non-essential third-party service and right-click on it.
3. Then select**End task** from the context menu.  
![Close Programs Via Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Close-Programs-Via-Task-Manager.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
 After closing one, check if the disk defragmenter works again. If it does, the service you just closed is the culprit. Now you can either update, re-install, or even uninstall the problematic app so it stops interfering with Disk Defragmenter.

<!-- affiliate ads begin -->
<a href="https://uperfect.sjv.io/c/5597632/1246754/15155" target="_top" id="1246754"><img src="//a.impactradius-go.com/display-ad/15155-1246754" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1246754/15155" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fixing Windows Disk Defragmenter's Opening Issues

 Disk defragmentation can improve the situation by rearranging files so that they can be evenly distributed throughout the drive. However, sometimes the Disk Defragmenter tool doesn't work as expected. If you encounter this problem, the methods described above should help you resolve it.


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


