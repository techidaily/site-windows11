---
title: "Resolving System Image Error: Code 0X80780119 in Windows"
date: 2024-10-04T01:04:12.074Z
updated: 2024-10-07T06:46:50.824Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Resolving System Image Error: Code 0X80780119 in Windows"
excerpt: "This Article Describes Resolving System Image Error: Code 0X80780119 in Windows"
keywords: WinErrorCode0x80780119Solution,ResolveWinImageError,FixWindowsSystemImgError,Code0X80780119Troubleshooting,WindowsImageErrorCorrection,ErrorCode0X80780119WindowsFix,SystemImgError0X80780119Resolve
thumbnail: https://thmb.techidaily.com/e788f79a8684ff135a50b06576e0943a8c2779cab90284e9a264c3a4912b0271.png
---

## Resolving System Image Error: Code 0X80780119 in Windows

 Creating a system image backup is essential in protecting your data and ensuring system recoverability, but the process of doing so might not always go smoothly. One such error that the users often encounter is the System Restore error 0x80780119, which prevents the users from completing the backup process.

 Below, we take a look at the common causes of this issue and discuss the different solutions you can try to get rid of this error for good.

## Why Are You Unable to Create a System Image?

 If you are unable to create a system image due to the error 0x80780119, it might be because of one or more of the following reasons:

* **Insufficient disk space**: Restore points take up space in the drive they are saved, and so to create new restore points on your computer, you must have sufficient disk space available. In case you are running out of space on your system, you are likely to face the error at hand.
* **Incorrect backup settings**: Your backup settings must be configured correctly. If there is an issue with these settings, the System Restore will encounter issues while creating a restore point.
* **External drive issues**: If you are using an external drive for backup, it is essential to ensure that it is connected to the system properly and is functioning. In case there is an issue with the external drive due to any of these problems, the System Restore utility might return the error 0x80780119\.
* **Corrupt system files**: The critical system files that are essential to create restore points and use the System Restore utility might have gotten corrupt, which is leading to the error under discussion.
* **Antivirus interruption**: If you are using a security program on your computer, there is a chance that it is blocking the restore tool from functioning properly. This typically happens when you are using a third-party antivirus solution.

 Regardless of what might be resulting in the problem in your case, the solutions we have listed below are sure to help you get the restore utility back on track. Proceed with the solutions one by one and follow the steps carefully for successful execution.

## 1\. Free Up Disk Space

 When you create a restore point in Windows, the system requires sufficient space on the destination drive to store all the backup files. If you do not have enough space, the System Restore is likely to return errors like the 0x80780119 error.

 This is why, before moving onto the complex troubleshooting methods, we recommend you ensure you have sufficient space available on the destination drive. If you are low on space, you can free it up by removing unnecessary files. Here are a few areas to focus on:

* **Temporary files**: Temporary files and other unnecessary data can be cleaned up by [using the Disk Cleanup tool](https://www.makeuseof.com/tag/best-way-clean-windows-10-step-step-guide/). It will list down all such files, and you can then specify which to remove. Simply type “Disk Cleanup” in the search area on your taskbar and click **Open** to launch the utility.
* **Downloads folder**: Access the Download folder in File Explorer and delete all the files you no longer need.
* **Uninstall unused programs**: If there are apps that you do not use anymore, head over to the Control Panel to uninstall them from the system. This will free up a great amount of space that can be used by the System Restore utility.

 In case you have large files or folders that you do not want to remove but also don’t need immediately, you can consider moving them to an external drive to free up space.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137206/26400" target="_top" id="2137206">
  <img src="//a.impactradius-go.com/display-ad/26400-2137206" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137206/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Check and Repair Disk Errors

 You might also be facing the system restore issue due to disk errors in the system.

 During the backup process, the system needs to read data from the targeted disk and write it to the backup destination. If there is an issue with the disk, the system may have issues reading the data or might write corrupted data in the backup file, which can result in different errors.

 Additionally, your disk might have bad sectors which cannot store data properly and might also prevent the system from reading data during the backup process.

 To ensure this isn’t the case in your situation, it is best to check the disk for errors using the built-in utilities offered by Windows. The first tool that we recommend[using is the CHKDSK utility](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) which can be used via Command Prompt. It works by scanning the system and checking the integrity of the disk. If a problem is identified, CHKDSK will attempt to fix it automatically.

 Alternatively, you can head over to the File Explorer and follow these steps:

1. In File Explorer, head over to the root of the drive you want to check and right-click on it.
2. Choose **Properties** from the context menu.
3. In the Properties dialog, navigate to the **Tools** tab and move to the **Error checking** section.
4. Click on the **Check** button here and wait for the system to complete the scan. This may take some time, depending upon the size of your disk.  
![Run the error checking tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/error-checking-tool.jpg)

 If any issues are found, Windows will prompt you to repair them. Follow the on-screen instructions to proceed.

## 3\. Enable System Protection

 Several users also noticed that they were facing the problem due to the system protection feature being disabled for the targeted drive. If you have this option disabled in your system, we suggest enabling it and checking if that makes any difference.

 Here is how you can do that:

1. Press the **Win** \+ **I** keys together to open the Settings app.
2. Navigate to **System** \> **About**.
3. Head over to the **Device specifications** section and click on the **System protection** option.  
![Click on the System protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-protection-options.jpg)
4. In the following dialog, head over to the **System Protection** tab.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144287/7443" target="_top" id="2144287">
  <img src="//a.impactradius-go.com/display-ad/7443-2144287" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144287/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Choose the targeted drive and click on the **Configure** button.  
![Click on the Configure button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/configure-button.jpg)
6. Enable the **Turn on system protection** option and click **Apply** \> **OK** to save the changes.  
![Enable system protection](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/enable-system-protection.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1959764/19272" target="_top" id="1959764">
  <img src="//a.impactradius-go.com/display-ad/19272-1959764" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959764/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can now close the System Protection dialog and check if the issue is resolved.

## 4\. Delete USN Journal

 The USN Journal (Update Sequence Number Journal) is a feature in the NTFS file system that tracks all the changes made on a disk. It is stored in the reserved partition and over time, it can consume a significant amount of your disk space, which may be preventing a restore point from being created.

 You can reclaim this disk space by deleting the USN Journal. Doing so will also eliminate the possibility of any conflicts that might be arising due to inconsistencies between the journal and the files being backed up.

 Here is how you can do that:

1. Type "Create and format hard disk partitions" in Windows search and click **Open**.
2. In the following window, right-click on the **System Reserved** volume and choose **Change Drive Letter and Paths** from the context menu.
3. Now, click on the **Add** button.
4. In the next dialog, choose **Assign the following drive letter** and click **OK**.  
![Change the USB Drive Letter Using Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/change-the-usb-drive-letter-using-disk-management.jpg)
5. Once done, press the **Win** \+ **R** keys together to open Run.
6. Type "cmd" in Run and click **Ctrl** \+ **Shift** \+ **Enter** to open Command Prompt as an administrator.
7. Confirm your action in the UAC prompt.
8. Execute the following commands in Command Prompt one by one:  
`fsutil usn queryjournal F:fsutil usn deletejournal /N /D F:`

 After the commands are executed, you can close Command Prompt and check if the issue is resolved.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087485/7443" target="_top" id="2087485">
  <img src="//a.impactradius-go.com/display-ad/7443-2087485" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087485/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Create a Backup Without Any More Errors on Windows

 Ensuring the protection of your data should be your foremost priority, and a system image backup plays a vital role in safeguarding against unforeseen data loss. With the solutions above, you should be able to get the System Restore utility up and running in no time. However, if the problem persists, you can consider reporting the issue to Microsoft and try the specific solutions they suggest. Till then, you can switch to a third-party backup tool to safeguard your data.

 Below, we take a look at the common causes of this issue and discuss the different solutions you can try to get rid of this error for good.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-docs.techidaily.com/ed-2024-approved-reversal-techniques-a-new-perspective-on-youtube-videos/"><u>[Updated] 2024 Approved Reversal Techniques A New Perspective on YouTube Videos</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-crafting-news-end-credits-a-step-by-step-guide-for-2024/"><u>[Updated] Crafting News End Credits A Step-by-Step Guide for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-top-livestream-tactics-best-practices-for-cricket-viewers/"><u>[Updated] Top Livestream Tactics Best Practices for Cricket Viewers</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-the-ultimate-list-of-key-apps-your-windows-computer-needs-explained/"><u>Discover the Ultimate List of Key Apps Your Windows Computer Needs, Explained!</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-connectivity-experience-swap-out-microsoft-phone-link-with-our-exceptional-app/"><u>Elevate Your Connectivity Experience - Swap Out Microsoft Phone Link with Our Exceptional App!</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-gameplay-experience-by-managing-keyboard-shortcuts-in-windows-and-preventing-altplustabsticky-key-issues/"><u>Enhancing Gameplay Experience by Managing Keyboard Shortcuts in Windows and Preventing Alt+Tab/Sticky Key Issues</u></a></li>
<li><a href="https://buynow-info.techidaily.com/experience-the-samsung-galaxy-budsplus-an-in-depth-review/"><u>Experience the Samsung Galaxy Buds+: An In-Depth Review</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-the-new-era-microsofts-wi-fi-7-experiments-with-windows-11-systems/"><u>Exploring the New Era: Microsoft's Wi-Fi 7 Experiments with Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-the-new-generation-of-windows-portables-and-beneath-the-surface-plans-from-spotify-your-weekly-tech-briefing/"><u>Exploring the New Generation of Windows Portables and Beneath-the-Surface Plans From Spotify – Your Weekly Tech Briefing</u></a></li>
<li><a href="https://howto.techidaily.com/gmail-not-working-on-vivo-y100-5g-7-common-problems-and-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Gmail Not Working on Vivo Y100 5G 7 Common Problems & Fixes | Dr.fone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/how-do-you-get-sun-stone-evolutions-in-pokemon-for-apple-iphone-12-pro-drfone-by-drfone-virtual-ios/"><u>How Do You Get Sun Stone Evolutions in Pokémon For Apple iPhone 12 Pro? | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-from-asus-rog-phone-8-pro-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock from Asus ROG Phone 8 Pro Phones with/without a PC</u></a></li>
<li><a href="https://windows11.techidaily.com/manage-your-memory-microsoft-edge-beta-rollout-with-integrated-ram-control-tools/"><u>Manage Your Memory: Microsoft Edge Beta Rollout with Integrated RAM Control Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-goal-setting-with-microsoft-word-a-unique-twist-on-digital-bullet-journaling/"><u>Mastering the Art of Goal-Setting with Microsoft Word: A Unique Twist on Digital Bullet Journaling</u></a></li>
<li><a href="https://windows11.techidaily.com/maximize-performance-on-the-go-the-asus-expertbook-p5-unveiled-offering-next-generation-power-efficiency-and-up-to-32gb-ram/"><u>Maximize Performance on the Go: The ASUS ExpertBook P5 Unveiled, Offering Next Generation Power Efficiency & Up to 32GB RAM</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/unravel-the-revenue-riddle-googles-guided-triple-steps-to-youtube-income-analysis-for-2024/"><u>Unravel the Revenue Riddle Google's Guided Triple Steps to YouTube Income Analysis for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/be-mastery-in-marketing-the-top-5-must-knows-for-brands/"><u>YouTube Mastery in Marketing The Top 5 Must-Knows for Brands</u></a></li>
</ul></div>

