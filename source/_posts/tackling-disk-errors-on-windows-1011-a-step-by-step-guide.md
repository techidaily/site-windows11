---
title: "Tackling Disk Errors on Windows 10/11: A Step-by-Step Guide"
date: 2024-10-25T16:10:14.811Z
updated: 2024-10-30T17:15:43.997Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Tackling Disk Errors on Windows 10/11: A Step-by-Step Guide"
excerpt: "This Article Describes Tackling Disk Errors on Windows 10/11: A Step-by-Step Guide"
keywords: Win Disk Repair,Fixing Disk Errors,10/11 Disk Troubleshooting,Windows Disk Fix Steps,Stop Disk Issues,Clearing Disk Errors,Disk Correction Guide
thumbnail: https://thmb.techidaily.com/e475d95ff83684e67af3ed3b0fb046f03e477b4f885c10acf9d70c8e5fd03d37.jpg
---

## Tackling Disk Errors on Windows 10/11: A Step-by-Step Guide

 A file system error can occur in Windows 10 and 11 when you try to open files or Microsoft Store apps. When such an error occurs, a message pops up that says, “File system error (code).” File system errors have variable error codes like -2147219195, -2147219196, -2147163893, and -1073741521.

 The causes of such errors vary, but the result is much the same. Users can’t open the files or apps for which file system errors arise. These general resolutions can fix a wide variety of file system errors in Windows 10 and 11.

## 1\. Run the SFC and DISM Command Line Tools

 File system errors can often be related to system file corruption. Windows 11 and 10 have the same SFC and DISM command-line tools for repairing system files and Windows system image. Running those utilities in the Command Prompt could feasibly resolve numerous file system errors.

 Our guide on[how to run the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) tells you how to initiate an SFC scan. You can also run a Deployment Image Servicing Management scan in the Command Prompt before or after running the SFC tool. To do so, you’ll need to execute the following command:

`DISM.exe /Online /Cleanup-image /Restorehealth`

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139110/17108" target="_top" id="2139110">
  <img src="//a.impactradius-go.com/display-ad/17108-2139110" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139110/17108" style="position:absolute;visibility:hidden;" border="0" />
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
6. Click**Start > Power** to select**Restart** . The CHKDSK scan will start after the restart.

<!-- affiliate ads begin -->
<span id="1424528">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424528.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424528">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424528.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424528%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424528/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Run the Windows Store App Troubleshooter

 If a file system error occurs when you try launching MS Store apps or opening files with them, the Windows Store App troubleshooter might be useful for fixing it. That troubleshooter is there to resolve issues that stop UWP apps from working as they should. These are the steps for opening the Windows Store App troubleshooter:

1. To access Settings, press the**Windows** logo key +**E** keyboard shortcut that opens that app.
2. Scroll down the tab and click a**Troubleshoot navigation** option.
3. Select**Other trouble-shooters** to bring up a list of tools for troubleshooting Windows.
4. Then press the**Run** button for launching the Windows Store App troubleshooter.  
![The troubleshooter list in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-store-apps-troubleshooter1.jpg)
5. Apply any suggestions the troubleshooter provides.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068408/7443" target="_top" id="2068408">
  <img src="//a.impactradius-go.com/display-ad/7443-2068408" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068408/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-store-app-window.jpg)

## 4\. Check That the Windows License Manager Service Is Running

 Some file system errors can arise for opening files with UWP apps when the Windows License Manager service is disabled. That’s a service required for MS Store infrastructure support, and apps downloaded from the store don’t always work right when it’s disabled. This is how you can check that service is enabled and start it if necessary:

1. Bring up the Windows search tool and input**Services** inside its text box.
2. Select**Services** within the search results.
3. Double-click**Windows License Manager Service** to access its properties window.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-services-window2.jpg)
4. Click on the**Startup type** menu to open it and select**Automatic** .  
![The Windows License Manager server window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-license-service-manager.jpg)
5. If the service isn’t running, press**Start** within the properties window.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144310/7443" target="_top" id="2144310">
  <img src="//a.impactradius-go.com/display-ad/7443-2144310" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144310/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Select**Apply** to save settings for the Windows License Manager Service.
7. Click**OK** to close the Windows License Manager Service Properties window.

## 5\. Reinstall Any Affected App

 This potential solution is more applicable to fixing file system errors that occur for opening specific UWP apps. Reinstalling the app for which the error arises might resolve it in such a scenario. For example, users confirmed reinstalling Microsoft Photos can resolve file system error -2147219196.

 You can remove UWP apps with some of the methods in our guide for uninstalling software in Windows 11\. You can uninstall most apps with the Apps & Features tool in Settings. However, you might need to use the PowerShell method in our guide to remove some pre-installed Windows 11 apps.

![Apps & features in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/apps-features-window.jpg)

 When you’ve uninstalled the app, reinstall it from the MS Store. Bring up the Microsoft Store, and input the app’s title in its search box. Then select the app to reinstall in the search results, and click the**Get** button for it.

## 6\. Set Up a New Local User Account on Windows

 File system errors can arise because of user account issues. Such errors might not arise if you set up and utilize a new local user account in Windows 11\. That might not be the most ideal resolution, but you can migrate user files to a newly established account.

 Our guide on[how to fix Windows issues by creating new accounts](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/) includes full instructions for how to apply this solution.

![The Add account button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/add-account-button.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137225/26400" target="_top" id="2137225">
  <img src="//a.impactradius-go.com/display-ad/26400-2137225" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137225/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 7\. Restore Windows to an Earlier Date

 System Restore is a troubleshooting tool that can potentially address various causes for file system errors, be it system file corruption, app conflicts, or recent Windows updates. It fixes many things by restoring Windows to an earlier date (system snapshot). However, restoring Windows to an earlier time will only likely work if you can select a restore point that predates the file system error on your PC.

 To apply this potential solution, read through our guide to[utilizing System Restore and creating restore points](https://www.makeuseof.com/windows-11-create-restore-point/) . Select a restoration date that will take your PC back to a time when there wasn’t a system file error on it. The oldest restore point available is the most likely one to do that.

![The System Restore tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/system-restore-window.jpg)

 However, restoring Windows to a previous time removes software not installed on the restoration point’s date. So, it’s likely you’ll have to reinstall some apps after rolling back Windows. Clicking**Scan for affected programs** in System Restore provides an overview of software that will be removed for a restore point.

## 8\. Reset Windows

 This final system file error solution is the most drastic of all since it amounts to reinstalling Windows 10 or 11\. Factory resetting restores Windows to a default system state, which can fix many errors caused by registry, third-party software, and system file issues. If you can’t fix a system file error with any other potential fix in this guide, then resetting is the last thing to try.

 Windows 11 and 10 have a Reset this PC tool that makes it easy to factory reset the platform. That tool also includes an option that enables you to keep user files in the process. Our guide on[how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) includes instructions for applying this potential resolution with this tool.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997648/19272" target="_top" id="1997648">
  <img src="//a.impactradius-go.com/display-ad/19272-1997648" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997648/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://some-knowledge.techidaily.com/new-how-much-money-do-podcasters-spend/"><u>[New] How Much Money Do Podcasters Spend?</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-mastering-color-grading-utilizing-luts-from-cg-central/"><u>2024 Approved Mastering Color Grading Utilizing LUTs From CG Central</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/achieving-optimal-image-quality-with-advanced-picture-settings-on-a-4k-smart-tv-from-samsung/"><u>Achieving Optimal Image Quality with Advanced Picture Settings on a 4K Smart TV From Samsung</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/elite-selection-of-android-smartwatch-apps-to-enhance-your-wearable-experience/"><u>Elite Selection of Android Smartwatch Apps to Enhance Your Wearable Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/free-up-local-space-in-win11-file-saving-techniques-max-156-chars/"><u>Free Up Local Space in Win11: File-Saving Techniques (Max 156 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-fixing-camera-unavailable-on-windows-11/"><u>Guide to Fixing “Camera Unavailable” On Windows 11</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-bypass-icloud-activation-lock-on-mac-for-iphone-6-by-drfone-ios/"><u>How To Bypass iCloud Activation Lock on Mac For iPhone 6?</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-get-rid-of-the-illustrations-inside-windows-search/"><u>How to Get Rid of the Illustrations Inside Windows Search</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-what-is-a-sim-network-unlock-pin-get-your-xiaomi-redmi-note-12t-pro-phone-network-ready-by-drfone-android/"><u>In 2024, What Is a SIM Network Unlock PIN? Get Your Xiaomi Redmi Note 12T Pro Phone Network-Ready</u></a></li>
<li><a href="https://vp-tips.techidaily.com/mastering-virtual-worlds-choosing-metavisors-wisely/"><u>Mastering Virtual Worlds Choosing Metavisors Wisely</u></a></li>
<li><a href="https://win-hacks.techidaily.com/secure-all-your-files-with-these-essential-steps-when-using-windows-eze-10-backup-tool/"><u>Secure All Your Files with These Essential Steps When Using Windows Eze 10 Backup Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-cure-windows-dism-failure-error-0x800f082f/"><u>Steps to Cure Windows' DISM Failure Error 0X800F082F</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-freeze-ups-of-psx-software-in-new-os-version/"><u>Tackling Freeze-Ups of PSX Software in New OS Version</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-troublesome-fail-to-work-in-win-based-apps/"><u>Tackling the Troublesome 'Fail to Work' In Win-Based Apps</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-rated-4k-video-editor-programs-a-comprehensive-guide/"><u>Top Rated 4K Video Editor Programs: A Comprehensive Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-how-windows-maintains-its-efficiency/"><u>Understanding How Windows Maintains Its Efficiency</u></a></li>
</ul></div>

