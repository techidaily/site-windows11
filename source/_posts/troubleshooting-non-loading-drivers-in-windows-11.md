---
title: Troubleshooting Non-Loading Drivers in Windows 11
date: 2024-09-05T02:12:24.506Z
updated: 2024-09-06T02:12:24.506Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Non-Loading Drivers in Windows 11
excerpt: This Article Describes Troubleshooting Non-Loading Drivers in Windows 11
keywords: Windows Driver Fix,Loading Driver Error,Win11 Driver Trouble,Resolve Driver Load Issue,Update Windows Drivers,Non-Loading Driver Guide,Boot Without Drivers
thumbnail: https://thmb.techidaily.com/71005eecdd2fec9bde2d87e54e71962fc2dc07f266aaf5068a5f2270c6aff62a.jpeg
---

## Troubleshooting Non-Loading Drivers in Windows 11

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

 Now, check if the “a driver cannot load on this device” still pops up.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100542/7443" target="_top" id="2100542">
  <img src="//a.impactradius-go.com/display-ad/7443-2100542" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100542/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://appsumo.8odi.net/c/5597632/2082542/7443" target="_top" id="2082542">
  <img src="//a.impactradius-go.com/display-ad/7443-2082542" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082542/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Paste the following path into the address bar and press the **Enter** key:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Class\`
7. Press **Ctrl + F** to open the **Find** window. **Paste** the copied GUID and click on the **Find Next** option.
8. Go to the right-hand side pane of the found GUID key. Find the **UpperFilters** value.
9. Right-click on it and select the **Delete** option.  
![Modify the System Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/modify-the-system-registry.jpg)
10. Similarly, find the **LowerFilters** value and then delete it as well. Some devices may not have this value.
<!-- affiliate ads begin -->
<span id="1983551">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983551.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983551">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983551.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983551%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983551/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
11. **Restart** your PC for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2024326/7443" target="_top" id="2024326">
  <img src="//a.impactradius-go.com/display-ad/7443-2024326" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2024326/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Reinstall or Remove the Concerned Application

 Some users face an eny.sys driver issue which controls RGB lighting on PCs. This is a problem for many MSI and ASUS PC users. It is not a system utility and if it encounters an error every time, you must reinstall the concerned RGB-lighting-controlled application.

 Reinstalling the latest version will ensure that the application comes with signed drivers and fixes the driver issues with Windows 11 PCs. Here’s how to do it:

1. Right-click on the **Start** button to open the **Power User menu**.
2. Click on the **Installed apps** option.
3. Find the concerned RGB-controlling application and click on the **ellipsis** icon. Select the **Uninstall** option.
4. Click on the **Uninstall** button.  
![Remove a meddlesome application](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/remove-a-meddlesome-application.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948954/19272" target="_top" id="1948954">
  <img src="//a.impactradius-go.com/display-ad/19272-1948954" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948954/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 After removing the app, restart your PC and check if the error pops up now. Now, visit the app manufacturer's website and download the recent version of the RGB-control app. Install it and check if it causes the driver error. If that is the case, then you must remove the application.

<!-- affiliate ads begin -->
<span id="1982457">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982457.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982457">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982457.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982457%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982457/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Use System Restore

 System Restore is an excellent utility baked into Windows that helps you fix issues in one go. It will roll back your PC to an earlier state when there were no abrupt issues with your PC.

 Check our guide on [how to use System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/) and revert to an earlier PC state without losing your personal files. However, all the installed apps and updates after the restore point will be removed, if you adopt this route.

## Your Driver Issues on Windows 11, Fixed

 These are the best methods you can use to fix the "A driver can't load on this device" error on your Windows 11 PC. Update all the device drivers, install optional updates, and disable memory integrity. After that, modify the system registry and remove the meddlesome RGB application to get rid of this problem.

 In this guide, we will discuss some methods to resolve this issue and restore your PC drivers to a normal working state.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-exquisite-film-series-selection-youtube-edition/"><u>[New] In 2024, Exquisite Film Series Selection - YouTube Edition</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-in-2024-best-8-streamers-pick-high-end-cameras-reviewed/"><u>[Updated] In 2024, Best 8 Streamer's Pick  High-End Cameras Reviewed</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-unveiling-top-5-mac-snippet-applications/"><u>[Updated] In 2024, Unveiling Top 5 Mac Snippet Applications</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-navigating-the-best-hdr-cameras/"><u>2024 Approved  Navigating the Best HDR Cameras</u></a></li>
<li><a href="https://windows11.techidaily.com/discovering-value-with-the-2020-apple-iphone-se-where-smart-meets-affordable/"><u>Discovering Value with the 2020 Apple iPhone SE: Where Smart Meets Affordable</u></a></li>
<li><a href="https://video-capture.techidaily.com/dynamic-oratory-study-insights-part-8-for-2024/"><u>Dynamic Oratory Study Insights, Part 8 for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/elevating-educational-content-by-adding-youtube-music-to-vids/"><u>Elevating Educational Content by Adding YouTube Music to Vids</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-for-instantly-generating-numerous-subfolders-on-modern-windows-systems/"><u>Expert Tips for Instantly Generating Numerous Subfolders on Modern Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/fixed-attempt-connection-error-blocking-device-linkage/"><u>Fixed: 'Attempt Connection' Error Blocking Device Linkage</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-enable-or-disable-the-smartscreen-filter-in-windows-10-and-11/"><u>How to Enable or Disable the SmartScreen Filter in Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-rectify-error-code-0xa00f429f-on-windows-devices/"><u>How to Rectify Error Code 0xA00F429F on Windows Devices</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-videos-from-samsung-galaxy-s23plus-by-fonelab-android-recover-video/"><u>How to Rescue Lost Videos from Samsung Galaxy S23+</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-infinix-hot-40-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Infinix Hot 40 to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-unstick-apps-from-windows-11-installations/"><u>How to Unstick Apps From Windows 11 Installations</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-quick-tips-efficient-file-shifting-to-computer/"><u>In 2024, Quick Tips  Efficient File Shifting to Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-system-restore-your-key-to-past-windows-configurations/"><u>Leveraging System Restore: Your Key to Past Windows Configurations</u></a></li>
<li><a href="https://extra-resources.techidaily.com/live-streamers-predicament-pick-between-wirecast-and-obs/"><u>Live Streamer's Predicament  Pick Between Wirecast and OBS</u></a></li>
<li><a href="https://windows11.techidaily.com/microsoft-store-troubleshoot-guide-for-error-x80072f30/"><u>Microsoft Store Troubleshoot Guide for Error X80072F30</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-files-with-powertoys-a-comprehensive-tutorial/"><u>Optimizing Files with PowerToys: A Comprehensive Tutorial</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-dism-error-0x800f082f-in-microsofts-os/"><u>Overcoming DISM Error 0X800F082F in Microsoft's OS</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-no-sound-error-in-powerpoint-screen-capture/"><u>Overcoming No Sound Error in PowerPoint Screen Capture</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-in-game-communication-hurdles-with-windows-speech-tools/"><u>Rectifying In-Game Communication Hurdles with Windows Speech Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-for-inaudible-recordings-while-using-powerpoint/"><u>Remedy for Inaudible Recordings While Using PowerPoint</u></a></li>
<li><a href="https://windows11.techidaily.com/step-into-flexibility-opening-fax-editor-on-windows-11-pcs/"><u>Step Into Flexibility: Opening Fax Editor on Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-eradicating-installer-problems-on-windows-11/"><u>Strategies for Eradicating Installer Problems on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/sustained-calculator-visibility-on-windows-os/"><u>Sustained Calculator Visibility on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-for-fixing-no-available-on-nvidia-display-error/"><u>Tactics for Fixing 'No Available' On Nvidia Display Error</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-work-processes-embrace-the-power-of-flow-launcher/"><u>Transform Work Processes: Embrace the Power of Flow Launcher</u></a></li>
<li><a href="https://windows11.techidaily.com/unexplored-avenues-in-windows-11-boost-your-usability/"><u>Unexplored Avenues in Windows 11 - Boost Your Usability</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-potential-of-windows-11-for-advanced-fax-editors/"><u>Unlock the Potential of Windows 11 for Advanced Fax Editors</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-and-solving-windows-exit-point-error/"><u>Unraveling and Solving Windows Exit Point Error</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-windows-network-confusion-code-0x800704b3/"><u>Unraveling Windows' Network Confusion - Code: 0X800704B3</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-tips-for-better-mouseclicklock-implementation/"><u>Unveiling Tips for Better MouseClickLock Implementation</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-terminal-vs-powershell-decoding-what-makes-them-diverge/"><u>Windows Terminal Vs. PowerShell: Decoding What Makes Them Diverge</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-over-windows-11-22h2-fix-strategies/"><u>Winning Over Windows 11: 22H2 Fix Strategies</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>