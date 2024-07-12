---
title: Navigating File System Woes on Windows 11
date: 2024-07-11T21:15:08.481Z
updated: 2024-07-12T21:15:08.481Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating File System Woes on Windows 11
excerpt: This Article Describes Navigating File System Woes on Windows 11
keywords: WinFileSystemTroubleshoot,Windows11FSIssuesHelp,FixWindowsFileError,Windows11FilesCorrect,FileManagementWin11,SolveWin11FSErrors,TroubleshootWindowsFiles
thumbnail: https://thmb.techidaily.com/b918b2416ccc3c3bc24e5dbb4922efd59cd6316c83a82113344d8ae306f1223c.jpg
---

## Navigating File System Woes on Windows 11

 A file system error can occur in Windows 10 and 11 when you try to open files or Microsoft Store apps. When such an error occurs, a message pops up that says, “File system error (code).” File system errors have variable error codes like -2147219195, -2147219196, -2147163893, and -1073741521.

 The causes of such errors vary, but the result is much the same. Users can’t open the files or apps for which file system errors arise. These general resolutions can fix a wide variety of file system errors in Windows 10 and 11.

## 1\. Run the SFC and DISM Command Line Tools

 File system errors can often be related to system file corruption. Windows 11 and 10 have the same SFC and DISM command-line tools for repairing system files and Windows system image. Running those utilities in the Command Prompt could feasibly resolve numerous file system errors.

 Our guide on [how to run the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) tells you how to initiate an SFC scan. You can also run a Deployment Image Servicing Management scan in the Command Prompt before or after running the SFC tool. To do so, you’ll need to execute the following command:

`DISM.exe /Online /Cleanup-image /Restorehealth`

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
![The Windows License Manager server window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-license-service-manager.jpg)
5. If the service isn’t running, press**Start** within the properties window.
6. Select**Apply** to save settings for the Windows License Manager Service.
7. Click**OK** to close the Windows License Manager Service Properties window.

## 5\. Reinstall Any Affected App

 This potential solution is more applicable to fixing file system errors that occur for opening specific UWP apps. Reinstalling the app for which the error arises might resolve it in such a scenario. For example, users confirmed reinstalling Microsoft Photos can resolve file system error -2147219196.

 You can remove UWP apps with some of the methods in our guide for uninstalling software in Windows 11\. You can uninstall most apps with the Apps & Features tool in Settings. However, you might need to use the PowerShell method in our guide to remove some pre-installed Windows 11 apps.

![Apps & features in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/apps-features-window.jpg)

 When you’ve uninstalled the app, reinstall it from the MS Store. Bring up the Microsoft Store, and input the app’s title in its search box. Then select the app to reinstall in the search results, and click the**Get** button for it.

## 6\. Set Up a New Local User Account on Windows

 File system errors can arise because of user account issues. Such errors might not arise if you set up and utilize a new local user account in Windows 11\. That might not be the most ideal resolution, but you can migrate user files to a newly established account.

 Our guide on [how to fix Windows issues by creating new accounts](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/) includes full instructions for how to apply this solution.

![The Add account button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/add-account-button.jpg)

## 7\. Restore Windows to an Earlier Date

 System Restore is a troubleshooting tool that can potentially address various causes for file system errors, be it system file corruption, app conflicts, or recent Windows updates. It fixes many things by restoring Windows to an earlier date (system snapshot). However, restoring Windows to an earlier time will only likely work if you can select a restore point that predates the file system error on your PC.

 To apply this potential solution, read through our guide to [utilizing System Restore and creating restore points](https://www.makeuseof.com/windows-11-create-restore-point/) . Select a restoration date that will take your PC back to a time when there wasn’t a system file error on it. The oldest restore point available is the most likely one to do that.

![The System Restore tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/system-restore-window.jpg)

 However, restoring Windows to a previous time removes software not installed on the restoration point’s date. So, it’s likely you’ll have to reinstall some apps after rolling back Windows. Clicking**Scan for affected programs** in System Restore provides an overview of software that will be removed for a restore point.

## 8\. Reset Windows

 This final system file error solution is the most drastic of all since it amounts to reinstalling Windows 10 or 11\. Factory resetting restores Windows to a default system state, which can fix many errors caused by registry, third-party software, and system file issues. If you can’t fix a system file error with any other potential fix in this guide, then resetting is the last thing to try.

 Windows 11 and 10 have a Reset this PC tool that makes it easy to factory reset the platform. That tool also includes an option that enables you to keep user files in the process. Our guide on [how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) includes instructions for applying this potential resolution with this tool.

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
<li><a href="https://windows11.techidaily.com/boosting-boot-speed-with-simple-steps-in-windows-11-setup/"><u>Boosting Boot Speed with Simple Steps in Windows 11 Setup</u></a></li>
<li><a href="https://extra-skills.techidaily.com/pixel-perfect-viewing-comparing-worlds-top-8k-televisions-for-2024/"><u>Pixel-Perfect Viewing  Comparing World's Top 8K Televisions for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/leading-techniques-for-facebook-ads/"><u>Leading Techniques for Facebook Ads</u></a></li>
<li><a href="https://windows11.techidaily.com/accessing-stealthed-elements-in-windows-11-ui/"><u>Accessing Stealthed Elements in Windows 11 UI</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-2024-approved-slow-down-or-speed-up-videos-with-the-best-converter-tools/"><u>Updated 2024 Approved Slow Down or Speed Up Videos with the Best Converter Tools</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-simplifying-streaming-key-tactics-for-youtube-and-twitch-via-obs/"><u>[New] 2024 Approved  Simplifying Streaming  Key Tactics for YouTube & Twitch via OBS</u></a></li>
<li><a href="https://windows11.techidaily.com/actions-for-correcting-windows-11-0x800f0922-error/"><u>Actions for Correcting Windows 11 0X800F0922 Error</u></a></li>
<li><a href="https://windows11.techidaily.com/christmas-theme-makeovers-for-windows-11/"><u>Christmas Theme Makeovers for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/cant-insert-new-cells-in-microsoft-excel-for-windows-try-these-fixes/"><u>Can’t Insert New Cells in Microsoft Excel for Windows? Try These Fixes</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-fix-oem-unlock-missing-on-oppo-a1-5g-by-drfone-android/"><u>How To Fix OEM Unlock Missing on Oppo A1 5G?</u></a></li>
<li><a href="https://windows11.techidaily.com/bold-stealth-for-your-wi-fi-on-windows-pcs/"><u>Bold Stealth for Your Wi-Fi on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-errors-manage-deps-for-virtualbox-on-windows/"><u>Avoid Errors: Manage Deps for VirtualBox on Windows</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-easy-steps-for-sharing-your-xbox-playtime/"><u>[New] In 2024, Easy Steps for Sharing Your Xbox Playtime</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-mcuicnt-file-execution-failure-on-windows/"><u>Addressing McUICnt File Execution Failure on Windows</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-save-your-fb-pages-download-8-best-tools-online-and-free/"><u>[Updated] 2024 Approved  Save Your FB Pages  Download 8 Best Tools Online & Free</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-panic-recover-lost-data-with-these-steps/"><u>Avoid Panic, Recover Lost Data with These Steps</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-ios-champions-best-ps2-emulation-programs/"><u>[Updated] In 2024, IOS Champions  Best PS2 Emulation Programs</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-cpu-utilization-checkers/"><u>Advanced CPU Utilization Checkers</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-printer-usage-errors-efficiently/"><u>Bypassing Printer Usage Errors Efficiently</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-transform-your-chromebook-into-a-linux-powerhouse-2023-edition-for-2024/"><u>Updated Transform Your Chromebook Into a Linux Powerhouse (2023 Edition) for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-the-cycle-how-to-fix-your-disconnected-ps4-remote-control-on-windows/"><u>Breaking the Cycle: How to Fix Your Disconnected PS4 Remote Control on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-back-windows-photo-viewer-a-1111-edition-guide/"><u>Bring Back Windows Photo Viewer: A 11/11 Edition Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/bridging-windows-prefixes-with-microsoft-services/"><u>Bridging Windows Prefixes with Microsoft Services</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerating-epic-launcher-on-pcs-a-quick-guide/"><u>Accelerating Epic Launcher on PCs: A Quick Guide</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-insights-on-engaging-top-tier-visual-storytellers-for-2024/"><u>[Updated] Insights on Engaging Top-Tier Visual Storytellers for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-personalized-settings-alomwares-pathway-to-customization/"><u>Achieve Personalized Settings - AlomWare's Pathway to Customization</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-5-ways-to-track-xiaomi-redmi-note-12-proplus-5g-without-app-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Ways to Track Xiaomi Redmi Note 12 Pro+ 5G without App | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/best-wsl-2-methods-for-efficient-windows-coding/"><u>Best WSL 2 Methods for Efficient Windows Coding</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-security-the-art-of-updating-gpo-in-windows/"><u>Boosting Security: The Art of Updating GPO in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-ui-skills-with-windows-11-widgets/"><u>Accelerate Your UI Skills with Windows 11 Widgets</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-mastering-3d-text-in-adobe-photoshop/"><u>[Updated] Mastering 3D Text in Adobe Photoshop</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-a-marketer-writes-guide-to-utilizing-hashtags-effectively-on-facebook/"><u>In 2024, A Marketer' Writes Guide to Utilizing Hashtags Effectively on Facebook</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensive-overview-using-bluescreenview/"><u>A Comprehensive Overview: Using BlueScreenView</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-how-to-edit-youtube-videos-in-windows-movie-maker/"><u>[New] 2024 Approved  How to Edit YouTube Videos in Windows Movie Maker</u></a></li>
<li><a href="https://windows11.techidaily.com/1719374504396-dive-into-the-depth-of-complete-screenshots-via-windows-snipping-tool/"><u>Dive Into the Depth of Complete Screenshots via Windows' Snipping Tool.</u></a></li>
</ul></div>
