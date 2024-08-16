---
title: Troubleshooting Non-Operational Windows Defrag Tool
date: 2024-08-15T15:27:23.509Z
updated: 2024-08-16T15:27:23.509Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Non-Operational Windows Defrag Tool
excerpt: This Article Describes Troubleshooting Non-Operational Windows Defrag Tool
keywords: Fixing Windows Defrag Errors,Active Defrag Tool Failure,Windows Defrag Trouble Resolution,Stop Non-Functional Defrag Feature,Enable Windows Defrag Service,Recover Windows Defrag Functionality,Restarting Failed Defrag Process
thumbnail: https://thmb.techidaily.com/d91a8e4d3e328994798cbf4d4f5c1573225bbff13640403fc40b5c32e2b3cd22.jpg
---

## Troubleshooting Non-Operational Windows Defrag Tool

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

1. Open the Services app (see [ways to open the Services app on Windows](https://www.makeuseof.com/windows-11-open-services-app/) ).
2. Scroll down to the "Optimise drives" service and double-click on it.
3. Click on the drop-down menu and set the Start type to "Manual."
4. Make sure the Service status is "Running." If it is not, then click on**Start** to run it.  
![Set Optimise drives Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Set-Optimise-drives-Properties.jpg)
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Click**Apply > OK** to save it.

 After making the above changes, check if it solves the problem. If not, move on to the next solution.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
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

 If you're still having trouble with your Disk Defragmenter tool after running an SFC scan, you may need to use the DISM utility. To do this, open the Command Prompt as an administrator and run the below command line:

`DISM /Online /Cleanup-Image /ScanHealth\nDism.exe /online /cleanup-image /restorehealth`

 Once the scan is complete, restart your computer and try defragmenting again.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Run the CHKDSK Utility

 If your computer's Disk Defragmenter is still not working, you can try [running the CHKDSK utility](http://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) . This is a computer program designed to check the integrity of your hard drive, identify errors, and fix them.

To run the CHKDSK utility, follow the below steps:

1. Press the Windows key and search for "Command Prompt".
2. Right-click on the search result and select**Run as administrator** .
3. Click**Yes** if UAC prompts on your computer screen. This will open a Command Prompt with admin access.  
![Run chkdsk command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Run-chkdsk-command.jpg)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. When you're in Command Prompt, type the following command and press Enter:  
`chkdsk C: /f`

 In the command above,**"C:"** represents your drive, so you should replace it with the letter that refers to your drive.

 Once the scanning process is completed, and you have been informed that your drive has been scanned, try to defragment it again.

 As it turns out, it may take several minutes for the scan to complete, depending on the size of your partition and sometimes it seems to get stuck. However, you should let it complete its task uninterrupted.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
## 4\. Close All Third-Party Applications

 Some third-party applications may interfere with Disk Defragmenter if they are running. In such a case, close all third-party programs and see if that helps the defragmenter to run properly.

 If you close all active windows and find that the defragmenter is still having issues, there might be a background process interfering with it. As such, you can try ending some third-party processes and see if that fixes it.

1. Press**Ctrl + Shift + Esc** on your keyboard to open the Task Manager.
2. On the Processes tab, find a non-essential third-party service and right-click on it.
3. Then select**End task** from the context menu.  
![Close Programs Via Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Close-Programs-Via-Task-Manager.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->

 After closing one, check if the disk defragmenter works again. If it does, the service you just closed is the culprit. Now you can either update, re-install, or even uninstall the problematic app so it stops interfering with Disk Defragmenter.

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
<li><a href="https://digital-screen-recording.techidaily.com/new-download-install-and-utilize-obs-effectively-on-a-macpc-for-2024/"><u>[New] Download, Install, and Utilize OBS Effectively on a MacPC for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-flip-photo-trail-on-fb-3-techniques-explored/"><u>[New] In 2024, Flip Photo Trail on FB - 3 Techniques Explored</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-mastering-the-art-of-combining-igtv-with-insta-stories/"><u>[Updated] In 2024, Mastering the Art of Combining IGTV with Insta Stories</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-navigating-rights-in-instagram-songs-for-2024/"><u>[Updated] Navigating Rights in Instagram Songs for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-solutions-to-clear-up-fuzzy-videos-for-mobile-users/"><u>[Updated] Solutions to Clear Up Fuzzy Videos for Mobile Users</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-understanding-the-mechanism-for-personalizing-social-media-visuals-for-2024/"><u>[Updated] Understanding the Mechanism for Personalizing Social Media Visuals for 2024</u></a></li>
<li><a href="https://android-location.techidaily.com/10-free-location-spoofers-to-fake-gps-location-on-your-infinix-smart-8-drfone-by-drfone-virtual/"><u>10 Free Location Spoofers to Fake GPS Location on your Infinix Smart 8 | Dr.fone</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-best-route-generator-apps-you-should-try-on-htc-u23-pro-drfone-by-drfone-virtual-android/"><u>5 Best Route Generator Apps You Should Try On HTC U23 Pro | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-call-history-from-meizu-21-by-fonelab-android-recover-call-logs/"><u>Easy steps to recover deleted call history from Meizu 21</u></a></li>
<li><a href="https://windows11.techidaily.com/evaluating-the-significance-of-audio-device-isolation-in-windows/"><u>Evaluating the Significance of Audio Device Isolation in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/examining-why-drive-letters-are-missing-from-windows-systems/"><u>Examining Why Drive Letters Are Missing From Windows Systems</u></a></li>
<li><a href="https://fox-blue.techidaily.com/experts-picks-the-best-10-photography-lenses/"><u>Expert's Picks  The Best 10 Photography Lenses</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-11-ignore-or-prevent-expiry-errors/"><u>Fixing Windows 11: Ignore or Prevent 'Expiry' Errors?</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-cease-built-in-desktop-keyboard-in-windows-os/"><u>Guide to Cease Built-In Desktop Keyboard in Windows OS</u></a></li>
<li><a href="https://extra-hints.techidaily.com/harness-kinemasters-power-techniques-for-professionals-and-top-online-platforms/"><u>Harness KineMaster's Power  Techniques for Professionals & Top Online Platforms</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-android-app-not-installed-error-on-infinix-note-30-vip-racing-edition-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android App Not Installed Error on Infinix Note 30 VIP Racing Edition Quickly? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-install-and-activate-defender-application-guard-on-edge-for-enhanced-safety/"><u>How to Install and Activate Defender Application Guard on Edge for Enhanced Safety</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-reset-a-locked-gionee-f3-pro-phone-by-drfone-android/"><u>How to Reset a Locked Gionee F3 Pro Phone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-unlink-your-onedrive-from-your-microsoft-account-on-windows/"><u>How to Unlink Your OneDrive From Your Microsoft Account on Windows</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-i-transferred-messages-from-infinix-smart-8-plus-to-iphone-12xs-max-in-seconds-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How I Transferred Messages from Infinix Smart 8 Plus to iPhone 12/XS (Max) in Seconds | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-nokia-c02-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>In 2024, How to Cast Nokia C02 Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-incorporating-yt-playlists-into-web-design/"><u>In 2024, Incorporating YT Playlists Into Web Design</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-network-locked-sim-card-inserted-on-your-asus-rog-phone-7-phone-unlock-it-now-by-drfone-android/"><u>In 2024, Network Locked SIM Card Inserted On Your Asus ROG Phone 7 Phone? Unlock It Now</u></a></li>
<li><a href="https://windows11.techidaily.com/interactive-insights-microsofts-innovative-ai-hub/"><u>Interactive Insights: Microsoft's Innovative AI Hub</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-fixing-nvidia-cp-errors-in-ws1110/"><u>Mastering the Art of Fixing Nvidia CP Errors in WS11/10</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-winerror-fixes-for-oculus-app-installation/"><u>Mastering WinError Fixes for Oculus App Installation</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/pixel-power-redesigned-radeon/"><u>Pixel Power  Redesigned Radeon</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/resolving-the-ntfssys-blue-screen-of-death-on-windows-10-a-step-by-step-guide/"><u>Resolving the ntfs.sys Blue Screen of Death on Windows 10: A Step-by-Step Guide</u></a></li>
<li><a href="https://video-capture.techidaily.com/scrutinizing-the-latest-in-screen-recording-tech-by-tunefab-for-2024/"><u>Scrutinizing the Latest in Screen Recording Tech by Tunefab for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-pathway-to-start-elevated-powershell-on-win11-systems/"><u>Secure Pathway to Start Elevated PowerShell on Win11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-unsupported-device-for-windows-hello-login/"><u>Solving 'Unsupported Device' For Windows Hello Login</u></a></li>
<li><a href="https://windows11.techidaily.com/stay-ahead-of-the-game-with-w11-pro-special-deals/"><u>Stay Ahead of the Game with W11 Pro Special Deals</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-to-correctly-handle-windows-updater-issue-error-0x80070003/"><u>Step-by-Step Guide to Correctly Handle Windows' Updater Issue (Error 0X80070003)</u></a></li>
<li><a href="https://windows11.techidaily.com/sustained-prominence-of-win-calculator-display/"><u>Sustained Prominence of Win Calculator Display</u></a></li>
<li><a href="https://windows11.techidaily.com/synchronize-access-controls-with-powertoys-locksmith/"><u>Synchronize Access Controls with PowerToys' Locksmith</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-crafting-a-better-windows-11/"><u>The Art of Crafting a Better Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshoot-non-functional-shift-in-windows/"><u>Troubleshoot Non-Functional Shift in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unblock-onedrive-windows-methods-to-reclaim-file-storage/"><u>Unblock OneDrive: Windows Methods to Reclaim File Storage</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-power-of-component-services-in-windows-11/"><u>Unlocking the Power of Component Services in Windows 11</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-the-ultimate-shortcut-making-reaction-videos-with-filmora/"><u>Updated In 2024, The Ultimate Shortcut Making Reaction Videos with Filmora</u></a></li>
<li><a href="https://windows11.techidaily.com/wake-lock-woes-keyboard-mouse-in-win11/"><u>Wake Lock Woes: Keyboard, Mouse in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/waking-up-off-screen-windows-mastering-6-strategies-in-win11/"><u>Waking Up Off-Screen Windows: Mastering 6 Strategies in Win11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ways-to-trade-pokemon-go-from-far-away-on-oppo-a18-drfone-by-drfone-virtual-android/"><u>Ways to trade pokemon go from far away On Oppo A18? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/what-should-i-do-if-i-dont-find-the-deleted-iphone-11-pro-files-after-scanning-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>What should I do if I dont find the deleted iPhone 11 Pro files after scanning? | Stellar</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11s-official-app-three-ways-to-erase-it/"><u>Win 11'S Official App: Three Ways to Erase It</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-adjusting-your-personalized-fn-keys/"><u>Windows 11: Adjusting Your Personalized FN Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-paper-management-reboot-steps/"><u>Windows Paper Management Reboot Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-sign-in-how-to-delete-your-email/"><u>Windows Sign In: How to Delete Your Email</u></a></li>
</ul></div>
