---
title: Muting Windows Update Notifications
date: 2024-08-15T15:47:46.028Z
updated: 2024-08-16T15:47:46.028Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Muting Windows Update Notifications
excerpt: This Article Describes Muting Windows Update Notifications
keywords: Mute Update Alerts,Stop Update Noise,Hush Update Tones,Quiet Updates Notification,Disable Update Chimes,Silence Windows Notify,Turn Off Updater Sound
thumbnail: https://thmb.techidaily.com/2a29084ef28c5d6ebf693615660d627bf6405cc5a8ac614e41f7b335143de3df.jpg
---

## Muting Windows Update Notifications

 Microsoft regularly releases patch updates to enhance your device's performance and security. When you download this update, Windows often replaces the usual Shut Down and Restart buttons with “Update and shut down” to remind you not to miss the update.

 However, you may sometimes encounter the same message prompting even after performing these actions. Read this guide to resolve this issue and stop getting such annoying notifications.

## 1\. Restart the Computer From Settings

 If restarting your computer with the power button does not work, do it via the Settings Menu. This trick has worked for many users who encountered the same issue. Try it and see if that helps.

1. [Open the Settings menu](https://www.makeuseof.com/windows-ways-to-open-system-settings/).
2. Click **Windows Update** in the left sidebar.
3. Under Windows Update, you will find the **Restart now** option.
4. Select this option to restart your computer and install the pending updates.

<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. Install Pending Updates

 If your computer keeps reminding you to update and shuts down, check for pending updates. It is possible that the updates were not installed properly and Windows is now asking you to complete them.

 To check for pending updates, follow these steps.

1. Press **Win + I** on your keyboard to open the Settings menu.
2. From the left sidebar, click on the **Windows Update** tab.
3. Select the **Check for updates** option from the right pane.

 This will search for available updates and install them if there are any. If you see no updates, continue to the next solution.

## 3\. Run the Windows Update Troubleshooter

 Windows operating system comes with troubleshooting tools specific to each problem. To solve update-related issues, use the Windows Update troubleshooter. This tool detects corrupted, or faulty files associated with updates and fixes them automatically.

 To run the Windows Update Troubleshooter, follow these steps:

1. Right-click on **Start** and select **Settings** from the menu list.
2. Select **Windows Update** in the left sidebar, then click **Troubleshoot**.
3. On the next page, click **Other trouble-shooters**.  
![Other troubleshooters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/other-troubleshooters.jpg)
<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Look for **Windows Update** and click **Run** next to it.  
![Run Windows Update Troubleshooter-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/run-windows-update-troubleshooter-1.jpg)

 Follow the instructions on the screen to let Windows Update Troubleshooter detect and fix problems. After running the troubleshooter, restart your computer and check if it solves the issue.

## 4\. Clear the Software Distribution Folder

 The Software Distribution folder contains downloaded updates and installation files. If these files become corrupted, it could lead to this issue. To fix it, clear the Software Distribution directory and check if that solves the problem.

1. Open the Start menu and type CMD in the search bar.
2. Press **Ctrl + Shift + Enter** on your keyboard. This will open the Command Prompt as an administrator.
3. If a User Account Control window appears, click **Yes** to grant administrative privileges.
4. In the command prompt window, type the following commands in the order given and press Enter after each command:  
`net stop wuauserv  
net stop bits  
net stop cryptSvc  
net stop msiserver`
5. After that, open File Explorer and navigate to this path:  
`C:\Windows\SoftwareDistribution`
6. In the SoftwareDistribution folder, select all the files and delete them permanently.  
![Clear SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/clear-softwaredistribution-folder.jpg)
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. When a permissions pop-up appears, select the checkbox and click **Continue**.
8. After you delete the Software Distribution folder, you must restart the services you stopped. To do so, go back to the Command Prompt window and run the following command:  
`net start wuauserv  
net start bits  
net start cryptSvc  
net start msiserver`

 Now exit the Command Prompt window and restart your computer. After running these commands, check if the issue is solved.

 ​​​​

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35408920&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/FR-200-1.png" border="0">Glarysoft File Recovery Pro - Helps to recover your lost file/data, even permanently deleted data. </a>
<!-- affiliate ads end -->
## 5\. Disable Windows Update

 If you keep encountering the issue, disable the Windows Update service. This will stop Windows from automatically downloading updates and showing the message.

 To disable Windows Update, follow these steps:

1. Press **Win + R** on your keyboard to open the Run command window.
2. Type **services.msc** in the dialog box and press Enter. This will open the Services console.
3. Search for **Windows Update**, right-click on it, and select **Stop**.  
![Stop Windows Update Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/stop-windows-update-service.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
4. Now double-click on **Windows Update** to open the Properties window.
5. On the **General** tab, click the **Startup type** drop-down and select **Disabled**.  
![Disable Windows Update Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-windows-update-service.jpg)
<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Click **Apply** \> **OK** to save the changes.
7. Now close the window and restart your computer.

 Sometimes you may not see the Restart option in the Start menu. In that case, [run the command prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). Now type **shutdown -s -t 0** in the command prompt and hit Enter. This will restart your computer immediately.

 Here **0** is the time in seconds. If you want to delay the restart, use a higher number. For example, shutdown -s -t 10 will delay the restart by 10 seconds.

 ​​​​​After restarting, you should no longer see the “Update and Restart” or “Update and Shut Down” message.

## 6\. Reset the Windows Update Components

 If none of the solutions above work, reset Windows Update components. It deletes all the temporary download files and resets the registry keys containing information about Windows Update. This process also clears any corrupted files associated with updates and allows Windows to download the updates again.

 To reset the Windows Update components, follow these steps:

1. [Open the Notepad application](https://www.makeuseof.com/windows-11-open-notepad/).
2. Copy the following commands and paste them into the Notepad window.  
`net stop bits  
net stop wuauserv  
net stop appidsvc  
net stop cryptsvc  
Del "%ALLUSERSPROFILE%\Application Data\Microsoft\Network\Downloader\*.*"  
rmdir %systemroot%\SoftwareDistribution /S /Q  
rmdir %systemroot%  
system32\catroot2 /S /Q  
sc.exe sdset bits D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
sc.exe sdset wuauserv D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
cd /d %windir%  
system32  
regsvr32.exe /s atl.dll  
regsvr32.exe /s urlmon.dll  
regsvr32.exe /s mshtml.dll  
regsvr32.exe /s shdocvw.dll  
regsvr32.exe /s browseui.dll  
regsvr32.exe /s jscript.dll  
regsvr32.exe /s vbscript.dll  
regsvr32.exe /s scrrun.dll  
regsvr32.exe /s msxml.dll  
regsvr32.exe /s msxml3.dll  
regsvr32.exe /s msxml6.dll  
regsvr32.exe /s actxprxy.dll  
regsvr32.exe /s softpub.dll  
regsvr32.exe /s wintrust.dll  
regsvr32.exe /s dssenh.dll  
regsvr32.exe /s rsaenh.dll  
regsvr32.exe /s gpkcsp.dll  
regsvr32.exe /s sccbase.dll  
regsvr32.exe /s slbcsp.dll  
regsvr32.exe /s cryptdlg.dll  
regsvr32.exe /s oleaut32.dll  
regsvr32.exe /s ole32.dll  
regsvr32.exe /s shell32.dll  
regsvr32.exe /s initpki.dll  
regsvr32.exe /s wuapi.dll  
regsvr32.exe /s wuaueng.dll  
regsvr32.exe /s wuaueng1.dll  
regsvr32.exe /s wucltui.dll  
regsvr32.exe /s wups.dll  
regsvr32.exe /s wups2.dll  
regsvr32.exe /s wuweb.dll  
regsvr32.exe /s qmgr.dll  
regsvr32.exe /s qmgrprxy.dll  
regsvr32.exe /s wucltux.dll  
regsvr32.exe /s muweb.dll  
regsvr32.exe /s wuwebv.dll  
netsh winsock reset  
netsh winsock reset proxy  
net start bits  
net start wuauserv  
net start appidsvc  
net start cryptsvc`
3. Click **File** and select **Save as** from the menu list.
4. In the dialog box, select **All Files** from the **Save as type** drop-down menu.
5. Save the file as **ResetWindowsUpdate.bat** and close Notepad.  
![Reset Windows Update Components](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reset-windows-update-components.jpg)
6. Now right-click on the .bat file and select **Run as administrator**.
7. When the UAC window appears, select **Yes** to continue.

 The script will start resetting the Windows Update components and may take a few minutes to complete. Once done, restart your computer and this should solve the issue.

## Resolving Incorrect Notifications for Updates and Restarts

 Now that you know how to fix incorrect notifications for updates and restarts, you can avoid this issue in the future. Make sure Windows Update is configured correctly and reset components. Also, keep your computer updated with the latest security patches. Doing this will also ensure smooth system operation.

 However, you may sometimes encounter the same message prompting even after performing these actions. Read this guide to resolve this issue and stop getting such annoying notifications.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-cinematography-secrets-unveiled-by-youtube-pros/"><u>[New] In 2024, Cinematography Secrets Unveiled by YouTube Pros</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-mastering-the-art-of-finding-pixel-tone-sites-for-2024/"><u>[New] Mastering the Art of Finding Pixel Tone Sites for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/amazons-social-stardom-liking-and-viewing-leaderships-for-2024/"><u>Amazon's Social Stardom  Liking and Viewing Leaderships for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/consumers-speak-the-vllo-narrative-for-2024/"><u>Consumers Speak  The VLLO Narrative for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/drive-letter-dilemma-in-windows-understanding-the-issues-fixes-presented/"><u>Drive Letter Dilemma in Windows - Understanding The Issues, Fixes Presented</u></a></li>
<li><a href="https://windows11.techidaily.com/easily-knock-off-the-onedrive-feature-from-file-explorer/"><u>Easily Knock Off the OneDrive Feature From File Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-steps-to-activatedeactivate-secure-boot-and-tpm-in-virtualbox/"><u>Easy Steps to Activate/Deactivate Secure Boot & TPM in VirtualBox</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-file-transfers-the-top-5-windows-apps/"><u>Effortless File Transfers: The Top 5 Windows Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/effortlessly-syncing-files-in-windows-1011/"><u>Effortlessly Syncing Files in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-workflow-choosing-the-best-6-to-do-list-apps-on-windows-11/"><u>Elevate Your Workflow: Choosing the Best 6 To-Do List Apps on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-virtual-battles-why-windows-reigns-supreme/"><u>Elevating Virtual Battles: Why Windows Reigns Supreme</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminate-chrome-aw-snap-glitch-on-windows/"><u>Eliminate Chrome “Aw, Snap!” Glitch on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminate-cursor-blanking-on-win11-instantly/"><u>Eliminate Cursor Blanking on Win11 Instantly</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-common-roadblocks-in-windows-11/"><u>Eliminating Common Roadblocks in WINDOWS 11</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-steam-hurdles-to-play-your-favorite-game-on-win-11/"><u>Eliminating Steam Hurdles to Play Your Favorite Game on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-visibility-of-windows-11-task-view/"><u>Eliminating Visibility of Windows 11 Task View</u></a></li>
<li><a href="https://windows11.techidaily.com/enforcing-controlled-directory-access-on-modern-windows-os/"><u>Enforcing Controlled Directory Access on Modern Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-your-system-without-microsofts-core-software/"><u>Enhance Your System Without Microsoft's Core Software</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-power-feedback-setting-up-fully-charged-notifications-in-win11/"><u>Enhancing Power Feedback: Setting Up Fully Charged Notifications in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-user-experience-with-automatic-updates-toolbar-in-windows-11plus11/"><u>Enhancing User Experience with Automatic Updates Toolbar in Windows 11+11</u></a></li>
<li><a href="https://windows11.techidaily.com/enriching-linux-experience-via-windows-collaboration/"><u>Enriching Linux Experience via Windows Collaboration</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-a-smooth-transition-for-linux-subsystem-within-the-new-windows-paradigm/"><u>Ensuring a Smooth Transition for Linux Subsystem Within the New Windows Paradigm</u></a></li>
<li><a href="https://windows11.techidaily.com/entering-quake-modes-through-windows-terminal/"><u>Entering Quake Modes Through Windows Terminal</u></a></li>
<li><a href="https://windows11.techidaily.com/escalate-emulation-faster-yuzu-win-users/"><u>Escalate Emulation: Faster Yuzu, WIN Users</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-stream-anything-from-itel-a70-to-apple-tv-drfone-by-drfone-android/"><u>How To Stream Anything From Itel A70 to Apple TV | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-music-from-samsung-galaxy-xcover-7-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Music from Samsung Galaxy XCover 7 to iPod | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-achieving-smooth-volume-decreases-using-lumafusion/"><u>In 2024, Achieving Smooth Volume Decreases Using Lumafusion</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-latest-guide-how-to-bypass-samsung-galaxy-s24-ultra-frp-without-computer-by-drfone-android/"><u>In 2024, Latest Guide How To Bypass Samsung Galaxy S24 Ultra FRP Without Computer</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-ultimate-guide-to-design-and-build-your-own-4k-editing-system/"><u>In 2024, The Ultimate Guide to Design and Build Your Own 4K Editing System</u></a></li>
<li><a href="https://extra-resources.techidaily.com/key-destinations-enhancing-youtube-video-impact/"><u>Key Destinations Enhancing YouTube Video Impact</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-reddit-who-get-instant-access-to-filmora-promo-codes/"><u>New Reddit Who? Get Instant Access to Filmora Promo Codes</u></a></li>
<li><a href="https://fake-location.techidaily.com/thinking-about-changing-your-netflix-region-without-a-vpn-on-oppo-a78-drfone-by-drfone-virtual-android/"><u>Thinking About Changing Your Netflix Region Without a VPN On Oppo A78? | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/unraveling-the-mystery-behind-windows-notorious-blue-screen/"><u>Unraveling the Mystery Behind Windows' Notorious Blue Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-wrinkle-free-up-operator-installation/"><u>Windows Wrinkle? Free Up Operator Installation</u></a></li>
</ul></div>
