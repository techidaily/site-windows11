---
title: Steps to Reinstall Non-Loading Drivers in Windows 11
date: 2024-10-13T23:26:21.885Z
updated: 2024-10-18T21:57:40.091Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Reinstall Non-Loading Drivers in Windows 11
excerpt: This Article Describes Steps to Reinstall Non-Loading Drivers in Windows 11
keywords: Reinstall Driver,Windows 11 Driver Fix,Non-Loading Drivers Remedy,Load Non-Driver Issue,Windows 11 Update Drivers,Drivers Install Procedure,Windows Driver Reinstall Guide
thumbnail: https://thmb.techidaily.com/b1aabf9182a40f39eacfea832a56e2883c1058666aaa24cc7d5f400170f744e3.jpeg
---

## Steps to Reinstall Non-Loading Drivers in Windows 11

 Windows loads drivers every time you power on your PC. However, some users face the "A driver can't load on this device" error after they boot to the desktop. This error can arise while installing an unsigned driver or due to a meddlesome application.

 In this guide, we will discuss some methods to resolve this issue and restore your PC drivers to a normal working state.

## 1\. Check for Optional Windows Updates

 Optional updates can contain driver updates for your device components. So, you must check for available driver updates in the Windows Update Settings. Repeat the following steps:

1. Press **Win + I** to launch the Settings app.
2. Click on the **Windows Update** icon.
3. Now click on the **Advanced options**.
4. Scroll down to the **Additional Options** section. Click on the **Optional Updates** option.
5. Check if any optional updates related to the device you are facing issues with are available. Download and install it.  
![Install optional updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/install-optional-updates.jpg)
6. **Close** the Settings app.

 You can also visit the device manufacturer’s website to download the latest updated drivers, which will be digitally signed. These should pose no issues during installation.

## 2\. Disable the Memory Integrity Feature

 Memory Integrity is a security feature that leverages virtualization to protect unauthorized programs from making changes to important security processes. But this security setting can prevent a driver from loading old or unsigned drivers from running on your PC.

 So, you must disable Memory Integrity. Repeat the following steps:

1. Press **Win + I** to open the Settings app.
2. Click on the **Privacy & security** option in the left-hand side menu.
3. Now, click on the **Windows Security** option.
4. Scroll down and click on the **Device Security** option.
5. Navigate to the Core Isolation section. Click on the **Core isolation details** option.
6. Disable the **toggle** present below the **Memory Integrity** option.  
![Disable Memory Integrity](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/disable-memory-integrity.jpg)
7. **Restart** your PC to apply the changes.

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1167086/14483" target="_top" id="1167086">
  <img src="//a.impactradius-go.com/display-ad/14483-1167086" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://electronicx.pxf.io/i/5597632/1167086/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now, check if the “a driver cannot load on this device” still pops up.

## 3\. Uninstall Any Recent System Updates

 If you are encountering an issue with a driver after installing a recent Windows update, you should consider removing that from your PC. Rolling back the update won’t remove any of your personal files.

 Check our guide on [ways to manually uninstall Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) for more information. But remember that it is not possible to remove all installed updates.

## 4\. Modify the System Registry

 Corrupt registry entries for the device can also be a reason for the hardware device encountering the driver issue. So, you must modify the system registry and remove those corrupt entries for the device.

 Make sure to manually export a [backup of your PC registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) onto a removable drive, so you always have the option to revert to the last working configuration.

 Repeat the following steps:

1. Right-click on the **Start** button to open the **Power User menu**. Click on the **Device Manager** option.
2. Locate the device facing driver issues and double-click on it to open its **Properties**.
3. Switch to the **Details** tab.
4. Click on the drop-down tab and click on the **Class GUID** option. It will display the GUID. **Copy** it to the clipboard.  
![Checking GUID in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/checking-guid-in-device-manager.jpg)
5. Press **Win + R** to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **Regedit** and press the **Ctrl + Shift + Enter** keys to open the Registry editor.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134494/18498" target="_top" id="2134494">
  <img src="//a.impactradius-go.com/display-ad/18498-2134494" border="0" alt="https://techidaily.com" width="721" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134494/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Paste the following path into the address bar and press the **Enter** key:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Class\`
7. Press **Ctrl + F** to open the **Find** window. **Paste** the copied GUID and click on the **Find Next** option.
8. Go to the right-hand side pane of the found GUID key. Find the **UpperFilters** value.
9. Right-click on it and select the **Delete** option.  
![Modify the System Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/modify-the-system-registry.jpg)
10. Similarly, find the **LowerFilters** value and then delete it as well. Some devices may not have this value.
11. **Restart** your PC for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482">
  <img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Reinstall or Remove the Concerned Application

 Some users face an eny.sys driver issue which controls RGB lighting on PCs. This is a problem for many MSI and ASUS PC users. It is not a system utility and if it encounters an error every time, you must reinstall the concerned RGB-lighting-controlled application.

 Reinstalling the latest version will ensure that the application comes with signed drivers and fixes the driver issues with Windows 11 PCs. Here’s how to do it:

1. Right-click on the **Start** button to open the **Power User menu**.
2. Click on the **Installed apps** option.
3. Find the concerned RGB-controlling application and click on the **ellipsis** icon. Select the **Uninstall** option.
4. Click on the **Uninstall** button.  
![Remove a meddlesome application](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/remove-a-meddlesome-application.jpg)

 After removing the app, restart your PC and check if the error pops up now. Now, visit the app manufacturer's website and download the recent version of the RGB-control app. Install it and check if it causes the driver error. If that is the case, then you must remove the application.

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398455/3022" target="_top" id="398455">
  <img src="//a.impactradius-go.com/display-ad/3022-398455" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398455/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Use System Restore

 System Restore is an excellent utility baked into Windows that helps you fix issues in one go. It will roll back your PC to an earlier state when there were no abrupt issues with your PC.

 Check our guide on [how to use System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/) and revert to an earlier PC state without losing your personal files. However, all the installed apps and updates after the restore point will be removed, if you adopt this route.

## Your Driver Issues on Windows 11, Fixed

 These are the best methods you can use to fix the "A driver can't load on this device" error on your Windows 11 PC. Update all the device drivers, install optional updates, and disable memory integrity. After that, modify the system registry and remove the meddlesome RGB application to get rid of this problem.

 In this guide, we will discuss some methods to resolve this issue and restore your PC drivers to a normal working state.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-files.techidaily.com/new-craft-your-own-film-finale-templates-no-cost/"><u>[New] Craft Your Own Film Finale Templates, No Cost</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-superior-scripting-fx-vaults-for-2024/"><u>[New] Superior Scripting FX Vaults for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-2024-approved-switch-onoff-youtubes-pip-mode-on-your-iphone/"><u>[Updated] 2024 Approved Switch On/Off YouTube's PIP Mode on Your iPhone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-record-and-relive-your-guide-to-capturing-phonescreens-with-snapchat/"><u>[Updated] Record and Relive Your Guide to Capturing Phonescreens with Snapchat</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/analyzing-the-linksys-wrt1900ac-r7200-eaebody-multi-device-data-steering-and-performance-insights-an-in-depth-review/"><u>Analyzing the Linksys WRT1900AC R7200 (EAebody): Multi-Device Data Steering & Performance Insights - An In-Depth Review</u></a></li>
<li><a href="https://tech-haven.techidaily.com/boost-your-brainstorm-sessions-using-mind-maps-and-ai-insights-from-chatgpt/"><u>Boost Your Brainstorm Sessions Using Mind Maps and AI Insights From ChatGPT</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-11-best-location-changers-for-infinix-note-30-drfone-by-drfone-virtual-android/"><u>In 2024, 11 Best Location Changers for Infinix Note 30 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/innovative-design-techniques-for-customizing-windows-outlook-calendars/"><u>Innovative Design Techniques for Customizing Windows Outlook Calendars</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-copying-custom-powertoys-configurations/"><u>Mastering the Art of Copying Custom PowerToys Configurations</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-to-index-settings-on-windows/"><u>Navigate to Index Settings on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-the-maze-of-0x80860010-application-overload/"><u>Navigating Through the Maze of 0X80860010 Application Overload</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-non-functional-google-nearby-share-window/"><u>Steps to Resolve Non-Functional Google Nearby Share Window</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-erasing-windows-11s-task-view/"><u>The Art of Erasing Windows 11'S Task View</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-on-preventing-windows-notepad-hangouts/"><u>Tips on Preventing Windows Notepad Hangouts</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-10-fingerprint-lock-apps-to-lock-your-tecno-spark-20-phone-by-drfone-android/"><u>Top 10 Fingerprint Lock Apps to Lock Your Tecno Spark 20 Phone</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-code-0xa00f4289-in-windows-webcam-errors/"><u>Troubleshooting Code 0xA00F4289 in Windows Webcam Errors</u></a></li>
<li><a href="https://buynow-info.techidaily.com/unstoppable-gaming-thriving-on-a-sluggish-countryside-connection/"><u>Unstoppable Gaming: Thriving on a Sluggish Countryside Connection</u></a></li>
</ul></div>

