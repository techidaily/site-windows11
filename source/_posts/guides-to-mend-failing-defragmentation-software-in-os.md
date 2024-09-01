---
title: Guides to Mend Failing Defragmentation Software in OS
date: 2024-08-31T22:07:28.460Z
updated: 2024-09-01T22:07:28.460Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guides to Mend Failing Defragmentation Software in OS
excerpt: This Article Describes Guides to Mend Failing Defragmentation Software in OS
keywords: Fix Defrag Issues,Optimize OS Performance,Restore File System Order,Correct Defrag Errors,Enhance Disk Efficiency,Solve Defrag Software,Improve Data Organization,Reorganize File System,Data Organization Tips
thumbnail: https://thmb.techidaily.com/73ab3c04255810df2615a2a01c8a14174dd9b221f2d60ec5b3831dd32989cbba.jpg
---

## Guides to Mend Failing Defragmentation Software in OS

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
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If you're still having trouble with your Disk Defragmenter tool after running an SFC scan, you may need to use the DISM utility. To do this, open the Command Prompt as an administrator and run the below command line:

`DISM /Online /Cleanup-Image /ScanHealth\nDism.exe /online /cleanup-image /restorehealth`

 Once the scan is complete, restart your computer and try defragmenting again.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Run the CHKDSK Utility

 If your computer's Disk Defragmenter is still not working, you can try[running the CHKDSK utility](http://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) . This is a computer program designed to check the integrity of your hard drive, identify errors, and fix them.

To run the CHKDSK utility, follow the below steps:

1. Press the Windows key and search for "Command Prompt".
2. Right-click on the search result and select**Run as administrator** .
3. Click**Yes** if UAC prompts on your computer screen. This will open a Command Prompt with admin access.  
![Run chkdsk command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Run-chkdsk-command.jpg)
4. When you're in Command Prompt, type the following command and press Enter:  
`chkdsk C: /f`

 In the command above,**"C:"** represents your drive, so you should replace it with the letter that refers to your drive.

 Once the scanning process is completed, and you have been informed that your drive has been scanned, try to defragment it again.

 As it turns out, it may take several minutes for the scan to complete, depending on the size of your partition and sometimes it seems to get stuck. However, you should let it complete its task uninterrupted.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->
## 4\. Close All Third-Party Applications

 Some third-party applications may interfere with Disk Defragmenter if they are running. In such a case, close all third-party programs and see if that helps the defragmenter to run properly.

 If you close all active windows and find that the defragmenter is still having issues, there might be a background process interfering with it. As such, you can try ending some third-party processes and see if that fixes it.

1. Press**Ctrl + Shift + Esc** on your keyboard to open the Task Manager.
2. On the Processes tab, find a non-essential third-party service and right-click on it.
3. Then select**End task** from the context menu.  
![Close Programs Via Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Close-Programs-Via-Task-Manager.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->
 After closing one, check if the disk defragmenter works again. If it does, the service you just closed is the culprit. Now you can either update, re-install, or even uninstall the problematic app so it stops interfering with Disk Defragmenter.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-simplifying-media-sharing-how-to-enable-autoplay-in-facebook-video-spaces/"><u>[New] 2024 Approved  Simplifying Media Sharing  How to Enable Autoplay in Facebook Video Spaces</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-transforming-challenges-into-triumphs-with-these-30-tips-for-2024/"><u>[New] Transforming Challenges Into Triumphs with These 30 Tips for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-expert-speaker-change-devices-for-youtube-gurus/"><u>[Updated] In 2024, Expert Speaker Change Devices for YouTube Gurus</u></a></li>
<li><a href="https://extra-resources.techidaily.com/6-competitive-video-apps-as-periscope-substitutes/"><u>6 Competitive Video Apps as Periscope Substitutes</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-life360-notify-when-you-log-out-on-honor-magic5-ultimate-drfone-by-drfone-virtual-android/"><u>Does Life360 Notify When You Log Out On Honor Magic5 Ultimate? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-windows-junk-uninstall-list-revealed/"><u>Essential Windows Junk: Uninstall List Revealed</u></a></li>
<li><a href="https://windows11.techidaily.com/finding-fix-for-non-functional-vss-in-win/"><u>Finding Fix for Non-Functional VSS in Win</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-media-player-server-crash/"><u>Fixing Media Player Server Crash</u></a></li>
<li><a href="https://android-location.techidaily.com/getting-the-pokemon-go-gps-signal-not-found-11-error-in-lava-blaze-2-drfone-by-drfone-virtual/"><u>Getting the Pokemon Go GPS Signal Not Found 11 Error in Lava Blaze 2 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-steps-for-ms-office-installation-on-windows-1011/"><u>Guiding Steps for MS Office Installation on Windows 10/11</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-transforming-video-aesthetics-on-tiktok-dual-approach/"><u>In 2024, Transforming Video Aesthetics on TikTok (Dual Approach)</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-transforming-your-living-space-into-a-podcast-studio/"><u>In 2024, Transforming Your Living Space Into a Podcast Studio</u></a></li>
<li><a href="https://windows11.techidaily.com/leverage-latest-proven-wsl-2-methods-on-windows-systems/"><u>Leverage Latest: Proven WSL 2 Methods on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-keyboard-interface-with-personalized-fn-keys-in-windows-11/"><u>Optimizing Keyboard Interface with Personalized FN Keys in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcome-task-failures-restore-windows-schedules/"><u>Overcome Task Failures, Restore Windows Schedules</u></a></li>
<li><a href="https://win-answers.techidaily.com/pc-masterclass-diagnosing-and-repairing-persistent-errors-in-your-fortnite-gameplay/"><u>PC Masterclass: Diagnosing & Repairing Persistent Errors in Your Fortnite Gameplay</u></a></li>
<li><a href="https://windows11.techidaily.com/regain-your-control-restoring-synapse-on-w10-and-w11/"><u>Regain Your Control: Restoring Synapse on W10 & W11</u></a></li>
<li><a href="https://windows11.techidaily.com/reigniting-frozen-discord-overlay-a-stepwise-guide-for-windows-users/"><u>Reigniting Frozen Discord Overlay: A Stepwise Guide for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-error-code-0x0001-on-nvidias-geforce-with-windows-11/"><u>Resolving Error Code 0X0001 on Nvidia's GeForce with Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-vanished-windows-badge-icons/"><u>Reviving Vanished Windows Badge Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-phone-integration-for-retailers-using-windows-11-and-intel-unison/"><u>Seamless Phone Integration for Retailers Using Windows 11 & Intel Unison</u></a></li>
<li><a href="https://windows11.techidaily.com/security-refresh-windows-firewalls-five-commandments/"><u>Security Refresh: Windows Firewall's Five Commandments</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-disregard-error-components-not-present-in-win10win11/"><u>Steps to Disregard Error: Components Not Present in Win10/Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategic-shopping-for-cost-efficient-windows-11-keys/"><u>Strategic Shopping for Cost-Efficient Windows 11 Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-decrease-high-cpu-consumption-by-dropbox-on-windows/"><u>Strategies to Decrease High CPU Consumption by Dropbox on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-picture-previews-in-windows-11-ui/"><u>Tailoring Picture Previews in Windows 11 UI</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-ultimate-guide-to-leveraging-the-quick-settings-menu-on-your-android-phone/"><u>The Ultimate Guide to Leveraging the Quick Settings Menu on Your Android Phone</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-access-denial-in-windows-11-a-quick-guide-to-5-solutions/"><u>Troubleshooting Access Denial in Windows 11: A Quick Guide to 5 Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/ultimate-list-wins-premier-video-trimming-tools/"><u>Ultimate List: Win's Premier Video Trimming Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-of-a-flapping-discord-overlay-on-pc/"><u>Unraveling the Mystery of a Flapping Discord Overlay on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-superiority-win11-vs-macos-facts/"><u>Unveiling the Superiority: Win11 vs MacOS Facts</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-sony-camcorder-video-editing-essentials-a-beginners-guide-to-pro-results/"><u>Updated Sony Camcorder Video Editing Essentials A Beginners Guide to Pro Results</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-virtual-machines-matching-windows-11-specs/"><u>Winning Virtual Machines Matching Windows 11 Specs</u></a></li>
<li><a href="https://windows11.techidaily.com/wireless-gaming-ps3-pad-to-windows-network/"><u>Wireless Gaming: PS3 Pad to Windows Network</u></a></li>
</ul></div>
