---
title: Troubleshooting Non-Loading Drivers in Windows 11
date: 2024-09-09T11:58:19.951Z
updated: 2024-09-10T11:58:19.951Z
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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134234/18498" target="_top" id="2134234">
  <img src="//a.impactradius-go.com/display-ad/18498-2134234" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134234/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Troubleshooting Non-Loading Drivers in Windows 11

 Windows loads drivers every time you power on your PC. However, some users face the "A driver can't load on this device" error after they boot to the desktop. This error can arise while installing an unsigned driver or due to a meddlesome application.

 In this guide, we will discuss some methods to resolve this issue and restore your PC drivers to a normal working state.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2128842/7443" target="_top" id="2128842">
  <img src="//a.impactradius-go.com/display-ad/7443-2128842" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2128842/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Check for Optional Windows Updates

 Optional updates can contain driver updates for your device components. So, you must check for available driver updates in the Windows Update Settings. Repeat the following steps:

1. Press **Win + I** to launch the Settings app.
2. Click on the **Windows Update** icon.
3. Now click on the **Advanced options**.
4. Scroll down to the **Additional Options** section. Click on the **Optional Updates** option.
5. Check if any optional updates related to the device you are facing issues with are available. Download and install it.  
![Install optional updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/install-optional-updates.jpg)
6. **Close** the Settings app.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135363/19272" target="_top" id="2135363">
  <img src="//a.impactradius-go.com/display-ad/19272-2135363" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135363/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<span id="1977004">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977004.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977004">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977004.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977004%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977004/22993" style="position:absolute;visibility:hidden;" border="0" />
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
6. Paste the following path into the address bar and press the **Enter** key:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Class\`
7. Press **Ctrl + F** to open the **Find** window. **Paste** the copied GUID and click on the **Find Next** option.
8. Go to the right-hand side pane of the found GUID key. Find the **UpperFilters** value.
9. Right-click on it and select the **Delete** option.  
![Modify the System Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/modify-the-system-registry.jpg)
10. Similarly, find the **LowerFilters** value and then delete it as well. Some devices may not have this value.
11. **Restart** your PC for the changes to take effect.

## 5\. Reinstall or Remove the Concerned Application

 Some users face an eny.sys driver issue which controls RGB lighting on PCs. This is a problem for many MSI and ASUS PC users. It is not a system utility and if it encounters an error every time, you must reinstall the concerned RGB-lighting-controlled application.

 Reinstalling the latest version will ensure that the application comes with signed drivers and fixes the driver issues with Windows 11 PCs. Here’s how to do it:

1. Right-click on the **Start** button to open the **Power User menu**.
2. Click on the **Installed apps** option.
3. Find the concerned RGB-controlling application and click on the **ellipsis** icon. Select the **Uninstall** option.
4. Click on the **Uninstall** button.  
![Remove a meddlesome application](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/remove-a-meddlesome-application.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123740/7443" target="_top" id="2123740">
  <img src="//a.impactradius-go.com/display-ad/7443-2123740" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123740/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 After removing the app, restart your PC and check if the error pops up now. Now, visit the app manufacturer's website and download the recent version of the RGB-control app. Install it and check if it causes the driver error. If that is the case, then you must remove the application.

## 6\. Use System Restore

 System Restore is an excellent utility baked into Windows that helps you fix issues in one go. It will roll back your PC to an earlier state when there were no abrupt issues with your PC.

 Check our guide on [how to use System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/) and revert to an earlier PC state without losing your personal files. However, all the installed apps and updates after the restore point will be removed, if you adopt this route.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136619/26400" target="_top" id="2136619">
  <img src="//a.impactradius-go.com/display-ad/26400-2136619" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136619/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Your Driver Issues on Windows 11, Fixed

 These are the best methods you can use to fix the "A driver can't load on this device" error on your Windows 11 PC. Update all the device drivers, install optional updates, and disable memory integrity. After that, modify the system registry and remove the meddlesome RGB application to get rid of this problem.

 In this guide, we will discuss some methods to resolve this issue and restore your PC drivers to a normal working state.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>