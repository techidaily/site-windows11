---
title: Troubleshooting Non-Operational Windows Defrag Tool
date: 2024-06-25T12:42:46.621Z
updated: 2024-06-26T12:42:46.621Z
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

1. Open the Services app (see[ways to open the Services app on Windows](https://www.makeuseof.com/windows-11-open-services-app/) ).
2. Scroll down to the "Optimise drives" service and double-click on it.
3. Click on the drop-down menu and set the Start type to "Manual."
4. Make sure the Service status is "Running." If it is not, then click on**Start** to run it.  
![Set Optimise drives Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Set-Optimise-drives-Properties.jpg)
5. Click**Apply > OK** to save it.

 After making the above changes, check if it solves the problem. If not, move on to the next solution.

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

## 4\. Close All Third-Party Applications

 Some third-party applications may interfere with Disk Defragmenter if they are running. In such a case, close all third-party programs and see if that helps the defragmenter to run properly.

 If you close all active windows and find that the defragmenter is still having issues, there might be a background process interfering with it. As such, you can try ending some third-party processes and see if that fixes it.

1. Press**Ctrl + Shift + Esc** on your keyboard to open the Task Manager.
2. On the Processes tab, find a non-essential third-party service and right-click on it.
3. Then select**End task** from the context menu.  
![Close Programs Via Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Close-Programs-Via-Task-Manager.jpg)

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
<li><a href="https://windows11.techidaily.com/optimizing-windowed-discord-for-flawless-search-experience/"><u>Optimizing Windowed Discord for Flawless Search Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/defining-windows-lockout-after-inactivity/"><u>Defining Windows Lockout After Inactivity</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-adjust-lockout-frequency-after-incorrect-user-credentials-for-windows-11/"><u>How to Adjust Lockout Frequency After Incorrect User Credentials for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-break-the-bond-onedrive-from-ms-account-on-windows/"><u>Techniques to Break the Bond: OneDrive From MS Account on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/perfecting-the-process-setting-up-msoffice-in-windows-11/"><u>Perfecting the Process: Setting Up MSOffice in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/engagingnotabledarkthemefornotepadwin/"><u>EngagingNotableDarkThemeForNotepadWin</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-visual-power-with-windows-11s-auto-hdr/"><u>Unlocking Visual Power with Windows 11'S Auto HDR</u></a></li>
<li><a href="https://windows11.techidaily.com/harnessing-the-power-of-microsofts-ai-code-helper/"><u>Harnessing the Power of Microsoft's AI Code Helper</u></a></li>
<li><a href="https://windows11.techidaily.com/reactivating-inputs-post-sleep-on-latest-windows/"><u>Reactivating Inputs Post-Sleep on Latest Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-the-root-of-windows-update-problems-0xc1900101/"><u>Eliminating the Root of Windows Update Problems (0xC1900101)</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-screensnapper-review-latest-tech/"><u>2024 Approved  ScreenSnapper Review - Latest Tech</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-efficient-methods-for-audio-trimming-in-apple-videos/"><u>Updated In 2024, Efficient Methods for Audio Trimming in Apple Videos</u></a></li>
<li><a href="https://some-guidance.techidaily.com/turn-off-youtubes-quick-video-buffering-feature-for-2024/"><u>Turn Off YouTube's Quick Video Buffering Feature for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/essential-tips-for-everyday-windows-10-users/"><u>Essential Tips for Everyday Windows 10 Users</u></a></li>
<li><a href="https://extra-resources.techidaily.com/a-beginners-guide-to-no-cost-countdown-usage/"><u>A Beginner's Guide to No-Cost Countdown Usage</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-android-unlock-code-sim-unlock-your-oneplus-nord-n30-5g-phone-and-remove-locked-screen-by-drfone-android/"><u>In 2024, Android Unlock Code Sim Unlock Your OnePlus Nord N30 5G Phone and Remove Locked Screen</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-the-10-best-free-dvd-players-compatible-with-windows-10/"><u>In 2024, The 10 Best Free DVD Players Compatible with Windows 10</u></a></li>
<li><a href="https://extra-information.techidaily.com/navigating-faster-tracks-in-spotify-while-preserving-quality/"><u>Navigating Faster Tracks in Spotify While Preserving Quality</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-expert-discord-video-capturing-apps-mobile-desktop/"><u>[Updated] In 2024, Expert Discord Video Capturing Apps  Mobile, Desktop</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-streamlined-techniques-for-rapid-mac-screen-recording/"><u>[Updated] 2024 Approved  Streamlined Techniques for Rapid Mac Screen Recording</u></a></li>
</ul></div>
