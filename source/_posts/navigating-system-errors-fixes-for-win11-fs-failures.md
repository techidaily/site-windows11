---
title: "Navigating System Errors: Fixes for Win11 FS Failures"
date: 2024-12-28T03:16:18.548Z
updated: 2025-01-04T03:43:31.652Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Navigating System Errors: Fixes for Win11 FS Failures"
excerpt: "This Article Describes Navigating System Errors: Fixes for Win11 FS Failures"
keywords: Win11 Error Fixes,FS System Repair Windows,Win11 Stability Solutions,Troubleshoot Win11 FS,Resolve Win11 Failures,Win11 OS Recovery Steps,Addressing Win11 FileSystem Errors
thumbnail: https://thmb.techidaily.com/7ac9924553405319fc34adce73b50933080c4e0b7ab947e877cf6636c606146d.jpg
---

## Navigating System Errors: Fixes for Win11 FS Failures

 A file system error can occur in Windows 10 and 11 when you try to open files or Microsoft Store apps. When such an error occurs, a message pops up that says, “File system error (code).” File system errors have variable error codes like -2147219195, -2147219196, -2147163893, and -1073741521.

 The causes of such errors vary, but the result is much the same. Users can’t open the files or apps for which file system errors arise. These general resolutions can fix a wide variety of file system errors in Windows 10 and 11.

## 1\. Run the SFC and DISM Command Line Tools

 File system errors can often be related to system file corruption. Windows 11 and 10 have the same SFC and DISM command-line tools for repairing system files and Windows system image. Running those utilities in the Command Prompt could feasibly resolve numerous file system errors.

 Our guide on[how to run the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) tells you how to initiate an SFC scan. You can also run a Deployment Image Servicing Management scan in the Command Prompt before or after running the SFC tool. To do so, you’ll need to execute the following command:

`DISM.exe /Online /Cleanup-image /Restorehealth`

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ME5-sAQJVE4?si=ZfcvJSnhQevWtjI0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Scan Your Hard Drive

 Hard drive integrity issues such as bad sectors also cause file system errors to occur in Windows 11/10\. For that reason, scanning your hard drive with the Check Disk tool is a recommended troubleshooting method for file system errors. The Check Disk utility (otherwise CHKDSK) scans for and repairs bad drive sectors detected. This is how you can run CHKDSK in the Command Prompt:

1. Open the file and app search box by pressing the**Win + S** key combination.
2. Select Command Prompt’s**Run as administrator** option within the search results to launch the app with elevated privileges.
3. Then type this command in the Prompt’s window and press**Enter** :  
`chkdsk c: /f /r`
4. You’ll need to press**Y** to schedule the scan for a restart.  
![The chkdsk command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/chkdsk.jpg)
5. Exit the Command Prompt window.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5OmJZ4Z8jgk?si=YIoEaPI8geoiFSYE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Click**Start > Power** to select**Restart** . The CHKDSK scan will start after the restart.

## 3\. Run the Windows Store App Troubleshooter

 If a file system error occurs when you try launching MS Store apps or opening files with them, the Windows Store App troubleshooter might be useful for fixing it. That troubleshooter is there to resolve issues that stop UWP apps from working as they should. These are the steps for opening the Windows Store App troubleshooter:

1. To access Settings, press the**Windows** logo key +**E** keyboard shortcut that opens that app.
2. Scroll down the tab and click a**Troubleshoot navigation** option.
3. Select**Other trouble-shooters** to bring up a list of tools for troubleshooting Windows.
4. Then press the**Run** button for launching the Windows Store App troubleshooter.  
![The troubleshooter list in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-store-apps-troubleshooter1.jpg)
5. Apply any suggestions the troubleshooter provides.  
![The Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-store-app-window.jpg)

## 4\. Check That the Windows License Manager Service Is Running

 Some file system errors can arise for opening files with UWP apps when the Windows License Manager service is disabled. That’s a service required for MS Store infrastructure support, and apps downloaded from the store don’t always work right when it’s disabled. This is how you can check that service is enabled and start it if necessary:

1. Bring up the Windows search tool and input**Services** inside its text box.
2. Select**Services** within the search results.
3. Double-click**Windows License Manager Service** to access its properties window.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-services-window2.jpg)
4. Click on the**Startup type** menu to open it and select**Automatic** .  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sXLLPY11of0?si=-3YNnpnO0wbc0K_-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![The Windows License Manager server window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-license-service-manager.jpg)
5. If the service isn’t running, press**Start** within the properties window.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/7JBG_O3Vnh4?si=lUO0fta6YPJ50qjg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Select**Apply** to save settings for the Windows License Manager Service.
7. Click**OK** to close the Windows License Manager Service Properties window.

## 5\. Reinstall Any Affected App

 This potential solution is more applicable to fixing file system errors that occur for opening specific UWP apps. Reinstalling the app for which the error arises might resolve it in such a scenario. For example, users confirmed reinstalling Microsoft Photos can resolve file system error -2147219196.

 You can remove UWP apps with some of the methods in our guide for uninstalling software in Windows 11\. You can uninstall most apps with the Apps & Features tool in Settings. However, you might need to use the PowerShell method in our guide to remove some pre-installed Windows 11 apps.

![Apps & features in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/apps-features-window.jpg)

 When you’ve uninstalled the app, reinstall it from the MS Store. Bring up the Microsoft Store, and input the app’s title in its search box. Then select the app to reinstall in the search results, and click the**Get** button for it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/P6Wfzj6YNDM?si=WRZQD9zCdQ1_tW1b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Set Up a New Local User Account on Windows

 File system errors can arise because of user account issues. Such errors might not arise if you set up and utilize a new local user account in Windows 11\. That might not be the most ideal resolution, but you can migrate user files to a newly established account.

 Our guide on[how to fix Windows issues by creating new accounts](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/) includes full instructions for how to apply this solution.

![The Add account button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/add-account-button.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/slm2NjVPNtk?si=9ow6g1ucmf0TnT4T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 7\. Restore Windows to an Earlier Date

 System Restore is a troubleshooting tool that can potentially address various causes for file system errors, be it system file corruption, app conflicts, or recent Windows updates. It fixes many things by restoring Windows to an earlier date (system snapshot). However, restoring Windows to an earlier time will only likely work if you can select a restore point that predates the file system error on your PC.

 To apply this potential solution, read through our guide to[utilizing System Restore and creating restore points](https://www.makeuseof.com/windows-11-create-restore-point/) . Select a restoration date that will take your PC back to a time when there wasn’t a system file error on it. The oldest restore point available is the most likely one to do that.

![The System Restore tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/system-restore-window.jpg)

 However, restoring Windows to a previous time removes software not installed on the restoration point’s date. So, it’s likely you’ll have to reinstall some apps after rolling back Windows. Clicking**Scan for affected programs** in System Restore provides an overview of software that will be removed for a restore point.

## 8\. Reset Windows

 This final system file error solution is the most drastic of all since it amounts to reinstalling Windows 10 or 11\. Factory resetting restores Windows to a default system state, which can fix many errors caused by registry, third-party software, and system file issues. If you can’t fix a system file error with any other potential fix in this guide, then resetting is the last thing to try.

 Windows 11 and 10 have a Reset this PC tool that makes it easy to factory reset the platform. That tool also includes an option that enables you to keep user files in the process. Our guide on[how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) includes instructions for applying this potential resolution with this tool.

## Get File System Errors Sorted in Windows

 Users often report file system errors on support forums much the same as BSOD (Blue Screen of Death) and missing DLL file issues. You can't ignore them when they stop you from opening important user files or apps. Whatever file system error you need to fix in Windows 10 and 11, you’ll probably be able to resolve it with at least one of the potential resolutions above.

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
<li><a href="https://fox-helps.techidaily.com/new-2024-approved-optimize-your-video-conferencing-experience-with-zoom-and-win10/"><u>[New] 2024 Approved Optimize Your Video Conferencing Experience with Zoom & Win10</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-mirrorless-mastery-with-best-gimbals-selection/"><u>[New] Mirrorless Mastery with Best Gimbals Selection</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-professional-webcam-recording-solutions-explored-for-2024/"><u>[Updated] Professional WebCam Recording Solutions Explored for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-10-cost-free-innovative-photo-overlays-for-mobile-devices/"><u>2024 Approved 10 Cost-Free, Innovative Photo Overlays for Mobile Devices</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-quick-scan-recorder-for-chrome-devices/"><u>2024 Approved Quick Scan Recorder for Chrome Devices</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-process-system-isnt-responding-error-on-oppo-a2-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Process System Isnt Responding Error on Oppo A2 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-unlock-windows-after-failed-sign-in/"><u>How to Unlock Windows After Failed Sign-In</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-10-best-fake-gps-location-spoofers-for-nokia-c02-drfone-by-drfone-virtual-android/"><u>In 2024, 10 Best Fake GPS Location Spoofers for Nokia C02 | Dr.fone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-seamless-saving-of-snapchat-images-on-device-memory/"><u>In 2024, Seamless Saving of SnapChat Images on Device Memory</u></a></li>
<li><a href="https://windows11.techidaily.com/innovative-windows-11-disk-space-strategies-without-deleting-files-max-156-chars/"><u>Innovative Windows 11 Disk Space Strategies Without Deleting Files (Max 156 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/is-split-screen-not-working-on-windows-heres-what-to-do/"><u>Is Split Screen Not Working on Windows? Here's What to Do</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-to-protected-windowsapps-directory/"><u>Navigating to Protected WindowsApps Directory</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-non-operative-grammarly-on-your-computer/"><u>Overcoming Non-Operative Grammarly on Your Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/powerful-tools-to-simultaneously-release-numerous-zip-archives/"><u>Powerful Tools to Simultaneously Release Numerous Zip Archives</u></a></li>
<li><a href="https://windows11.techidaily.com/speedy-excel-operations-restored-a-guide-for-windows-users/"><u>Speedy Excel Operations Restored: A Guide for Windows Users</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/stay-connected-on-the-go-our-selection-of-top-of-the-line-travel-routers-for-202absolutely-here-are-five-seo-friendly-titles-that-convey-similar-meanings-to12/"><u>Stay Connected on the Go: Our Selection of Top-of-the-Line Travel Routers for 202Absolutely! Here Are Five SEO-Friendly Titles that Convey Similar Meanings to The Best Wireless Travel Routers of 2024:</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/step-by-step-tutorial-how-to-bypass-samsung-galaxy-a15-4g-frp-by-drfone-android/"><u>Step-by-Step Tutorial How To Bypass Samsung Galaxy A15 4G FRP</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-decipher-group-policy-on-your-computer/"><u>Strategies to Decipher Group Policy on Your Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-the-prime-viewing-experience-on-windows-11-devices/"><u>Streamline the Prime Viewing Experience on Windows 11 Devices</u></a></li>
</ul></div>

