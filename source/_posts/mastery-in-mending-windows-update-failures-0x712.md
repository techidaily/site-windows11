---
title: "Mastery in Mending Windows Update Failures: 0X712"
date: 2025-01-18T18:44:23.343Z
updated: 2025-01-22T16:22:29.207Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastery in Mending Windows Update Failures: 0X712"
excerpt: "This Article Describes Mastery in Mending Windows Update Failures: 0X712"
keywords: Fixing Windows Updates,Xbox Error Repair,Windows XP712 Fix,Update Issue Resolution,Mending Update Failures,Master Windows Recovery,Xbox 0xWindows Fix
thumbnail: https://thmb.techidaily.com/0a18a6b406ce9f21eda937adac64825b459ee3a87d13a642256000f5335eb2cc.jpg
---

## Mastery in Mending Windows Update Failures: 0X712

 Microsoft frequently releases updates to fix security issues, and introduce new features and stability to the Windows OS. But not all updates install smoothly on your system and trigger an error code while doing so. Many users share their woes with the 0x80073712 update error code with the error message that some files are missing from the system.

 If you experience the same update error code and are unable to install the latest Windows update, don’t worry. We will list out all the possible fixes that you can try to resolve the 0x80073712 error code.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Use the Windows Troubleshooter

 Before jumping onto major fixes, leverage the in-built troubleshooter on Windows 10 and 11\. It tries to find out existing problems with Windows Update and try to fix them. Repeat the following steps:

1. Press**Win + I** to launch the settings app.
2. Navigate to the**System > Troubleshoot** section.
3. Click on the**Other Troubleshooter** option.
4. Locate the**Windows Update troubleshooter** option from the list.
5. Then, click on the**Run** button to start the troubleshooter.  
![Windows Update Troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-update-troubleshooter.jpg)
6. Wait for the Windows Update troubleshooter to identify problems. Click on the**Next** button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vQbNyknjJJ8?si=RGVIEWLdPbvRC_r6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Close the troubleshooter window and reattempt the Windows update installation.

## 2\. Perform a Complete system shutdown

 Windows OS enables the fast startup option by default. Even if you restart your system, or shut it down, it preserves the system state using hibernate. So, you need to perform a complete system shutdown and then power it back on to close and restart all background services.

Here’s how to perform a complete system shutdown:

1. Press**Win + X** to launch the Power user menu. Scroll down and select the**Terminal (Admin)** option from the list.
2. The Terminal app will open with an instance of a command prompt with admin privileges.
3. Type the**shutdown /s /f /t 0** command and press the**enter** key.
4. Your system will power off. It will take a tad bit longer that a normal shutdown procedure.
5. Now, restart your Windows PC and try to install the Windows update.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n-66V-LRK3Y?si=fNeB2pXCePeQli6E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Restart Windows Update services

 Windows Update uses a bunch of background services to fetch and download updates. If these services aren’t running automatically, you will encounter an error. These include**Windows Update Service** ,**Windows Installer Service** ,**Cryptographic Services** , and**Background Intelligent Transfer Service** .

Repeat the following steps to start the necessary services:

1. Press**Win + R** to[launch the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**services.msc** and press the**enter** key
2. Services utility will launch on your system. Now locate the**Background Intelligent Transfer** service in the list.
3. Double-click on the BITS service to open the**properties** window. Set the**Startup Type** as**Automatic** and click on the**Apply** button.  
![Disabling Windows Update Services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/disabling-windows-update-services.jpg)
4. Click on the**OK** button and close the Properties windows. Now, right-click on the service and select the**Start** option from the context menu.

5. Similarly, set all the services as automatic and manually start them.
6. **Close** the Services window and reattempt the Windows update.

## 4\. Run the Disk Cleanup Tool

 Disk Cleanup can wipe the delivery optimization files, old Windows update files as well as the Temp folder. If files in these locations are corrupted, they can interfere with the normal update process. Here’s how to run disk cleanup on Windows:

1. Press**Win + S** to open the search utility in Windows.
2. Type**cleanmgr.exe** and press the enter key to open the Disk Cleanup tool.
3. It will select the system drive (C) by default. Click on the**OK** button to continue.
4. Select the checkboxes of files that you want the tool to clean up. Then, click on the**Clean up system files** button.  
![Disk Cleanup App in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/disk-cleanup-app-in-windows-11.jpg)
5. Disk Cleanup will close and redirect you to pick the appropriate drive. Click on the**OK** button.

6. Lastly, click on the**Delete files** button.

## 5\. Rename the SoftwareDistribution Folder

 Windows update stores its content in the SoftwareDistribution folder. Since it is located inside the Windows folder in the C drive, you mustn’t delete it. Instead, you can rename the folder to force the update service to recreate the folder again.

Repeat the following steps:

1. Open the Start menu and search CMD. Press Ctrl + Shift + Enter to open the command prompt with admin privileges.
2. Type the following commands to stop all the Windows update-related services:  
 net stop wuauserv net stop cryptSvc net stop bits net stop msiserver  
![Rename the SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/rename-the-softwaredistribution-folder.jpg)
3. Once these services stop running, type**cls** in the command prompt windows. Then enter the following commands:  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RAnyQ0uj9Yg?si=Es4_ulcdM_-LuDcq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 ren C:\\Windows\\SoftwareDistribution SoftwareDistribution.old ren C:\\Windows\\System32\\catroot2 Catroot2.old  
![Rename the SoftwareDistribution Folder 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/rename-the-softwaredistribution-folder-2.jpg)
4. Both the above commands rename the**SoftwareDistribution** folder and**Catroot2** folder.

5. Now, you need to restart all the Windows services you stopped in step 3\. Enter the following commands:  
net start wuauserv net start cryptSvc net start bits net start msiserver  
![Rename the SoftwareDistribution Folder 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/rename-the-softwaredistribution-folder-3.jpg)
6. Lastly,**restart** your system and visit the following folder location:**C:\\Windows** . You will notice that there is a new SoftwareDistribution folder in that location.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qNrOsjUdRz0?si=xGzhmNmtgxNTsRxN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Open the Windows update in Settings and try to download and install updates.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iPCr_bxZjMQ?si=ubOsoq5umPEXL9xL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Delete the Pending.xml file

 The pending.xml file contains all the pending Windows update tasks. Oftentimes, it can interfere with installing new updates because there are already multiple incomplete old update tasks. So, you must delete this file and proceed with the Windows update.

Retrace the following steps to delete the pending.xml file:

1. Log in with an administrator account. Then, press**Win + E** to launch the file explorer.
2. Navigate to the**C:\\Windows\\WinSxS** folder.
3. Locate the**pending.xml** in the**WinSxS** folder and right-click on it.
4. Press the**Shift** key and click on the**Delete** option.
5. Restart your computer.

## 7\. Manually Download Windows Updates

 If you are unable to download a specific Windows update using the Settings page, consider a direct download and install approach. Visit the Microsoft Update Catalog website and search for the KB update you want to download. However, you first have to check the corresponding update number which is failing to download and install on your system.

![Manually Download Windows Updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/manually-download-windows-updates.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/rBnnLFJbvr4?si=LlHYrYlOBp7NLMec" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 8\. Reset Windows

 Resetting Windows is the last resort you have if none of the above methods work in your favor. However, before learning[how to perform a Windows system reset](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) , try out general fixes such as[SFC, CHKDSK, and DISM](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) scans on your system. Also,[disable Windows Defender](https://www.makeuseof.com/how-to-turn-off-windows-defender/) and try updating your system before hitting the reset button.

## Update Windows Without Hiccups

 Windows updates can be tricky to install sometimes. Use the inbuilt troubleshooter to identify and fix problems. After that restart, all the crucial Windows update services and run the Disk Cleanup tool. If everything else fails, try doing a manual update or performing a Windows Reset.

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
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-the-essentials-of-navigating-ez-grabber-interface/"><u>[New] 2024 Approved The Essentials of Navigating EZ Grabber Interface</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-expert-strategies-to-master-the-instagram-query-tag/"><u>[Updated] 2024 Approved Expert Strategies to Master the Instagram Query Tag</u></a></li>
<li><a href="https://youtube-data.techidaily.com/approved-quality-upgrade-switch-codecs-to-av1-for-youtube-viewing/"><u>2024 Approved Quality Upgrade Switch Codecs to AV1 for YouTube Viewing</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-step-by-step-guide-to-3d-text-effects-in-photos/"><u>2024 Approved Step-by-Step Guide to 3D Text Effects in PHOTOS</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-subtlety-matters-fading-out-sounds-in-logic-pro/"><u>2024 Approved Subtlety Matters Fading Out Sounds in Logic Pro</u></a></li>
<li><a href="https://some-guidance.techidaily.com/essential-laugh-out-loud-flicks-featuring-hollywoods-finest-talent/"><u>Essential Laugh-Out-Loud Flicks Featuring Hollywood's Finest Talent</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-find-ispoofer-pro-activation-key-on-meizu-21-drfone-by-drfone-virtual-android/"><u>How to Find iSpoofer Pro Activation Key On Meizu 21? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-unlocking-made-easy-the-best-10-apps-for-unlocking-your-xiaomi-redmi-note-13-proplus-5g-device-by-drfone-android/"><u>In 2024, Unlocking Made Easy The Best 10 Apps for Unlocking Your Xiaomi Redmi Note 13 Pro+ 5G Device</u></a></li>
<li><a href="https://windows11.techidaily.com/locating-open-tcp-ports-in-windows-os/"><u>Locating Open TCP Ports in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-challenge-interrupt-exception-in-windows-os/"><u>Overcoming the Challenge: Interrupt Exception in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-how-to-correct-windows-11s-keyboard-type-trouble-code-0x80049dd3/"><u>Quick Guide: How to Correct Windows 11'S Keyboard Type Trouble (Code: 0X80049DD3)</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resurrect-your-disconnected-controller/"><u>Steps to Resurrect Your Disconnected Controller</u></a></li>
<li><a href="https://vp-tips.techidaily.com/tips-for-reducing-unsteady-shots/"><u>Tips for Reducing Unsteady Shots</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-overcoming-windows-terminal-access-issues/"><u>Troubleshooting: Overcoming Windows Terminal Access Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-fixing-windows-roblox-code-403-issue/"><u>Understanding & Fixing Windows Roblox Code 403 Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/visual-illusion-blending-image-and-archive-data-without-notice-win1011/"><u>Visual Illusion: Blending Image and Archive Data without Notice WIN10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-offline-the-essential-manual/"><u>Win11 Offline: The Essential Manual</u></a></li>
</ul></div>

