---
title: Restoring Memory Safety in Windows 11'S System Settings
date: 2024-09-05T02:08:02.674Z
updated: 2024-09-06T02:08:02.674Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Memory Safety in Windows 11'S System Settings
excerpt: This Article Describes Restoring Memory Safety in Windows 11'S System Settings
keywords: Win11 Memory Safe,Memory Fix Windows,Secure Mem Sys Win,Memory Safety Settings,Protect Memory Windows,Guard Memory Win,SafeMem Win11 Settings
thumbnail: https://thmb.techidaily.com/0f5fc285546b265c973fbaa96cd3591b73387ac3a0f71577bc77fa3f28f478c0.jpg
---

## Restoring Memory Safety in Windows 11'S System Settings

 Does the memory integrity feature in Windows Security appear grayed out? Is your PC saying, "Memory integrity is off. Your device may be vulnerable," but you can't turn on the toggle? The memory integrity feature prevents malicious software from accessing high-security processes when your device is invaded by malware.

 But what causes this feature to be grayed out? In this article, we'll discuss why you cannot turn on this feature and how to identify and fix the underlying problem.

## What Causes Memory Integrity to Become Grayed Out on Windows 11?

 The primary cause of memory integrity not working on Windows 11 is your drivers. When they become outdated or corrupt, you are likely to run into this problem. Likewise, if your system is outfitted with incompatible drivers, the memory integrity feature may stop working.

 The error message itself usually explains where the problem lies, so fixing the problem is simple. You can fix faulty drivers, repair corrupted system files, update your operating system, revert an update, or remove incompatible drivers. Let's discuss some fixes to get the feature working again.

 As you apply each fix listed below, go to the Windows Security app and try enabling memory integrity again. It will help you identify what was causing the problem and fix it quickly without going through unnecessary fixes.

## 1\. Identify and Fix Driver Issues

 In most cases, the primary cause of the problem under discussion is outdated or incompatible drivers, so let's start by checking your drivers. To begin with, uninstall any third-party drivers you installed recently. After that, open the **Windows Security** app, click on the **Device security** tab from the left sidebar, and click on **Core isolation details**.

![Clicking on the Core Isolation Details Option in the Device Security Tab of Windows Security App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/1-Clicking-on-the-Core-Isolation-Details-Option-in-the-Device-Security-Tab-of-Windows-Security-App.jpg)

 Here, enable Memory integrity. If you encounter an error saying, **"Resolve any driver incompatibilities and scan again,"** click on the **Review incompatible drivers** link.

![Clicking on the Review Incompatible Drivers Link in Core Isolation Settings of Windows Security App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/2-Clicking-on-the-Review-Incompatible-Drivers-Link-in-Core-Isolation-Settings-of-Windows-Security-App.jpg)

 Then, note down any drivers Memory Integrity suspects are incompatible.

![Noting Down the List of Incompatible Drivers in the Core Isolation Settings Within Windows Security App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/3-Noting-Down-the-List-of-Incompatible-Drivers-in-the-Core-Isolation-Settings-Within-Windows-Security-App.jpg)

 Following the above checks, follow these steps to rule out driver-related problems:

1. Right-click on the Windows **Start** button and select **Device Manager**.
2. Go to the **View** tab and click **Show hidden devices**.  
![Clicking on the Show Hidden Devices Option in the View Tab Dropdown Menu Of Windows Device Manager App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/4-Clicking-on-the-Show-Hidden-Devices-Option-in-the-View-Tab-Dropdown-Menu-Of-Windows-Device-Manager-App.jpg)
3. Look for the device that has a yellow triangle on it with an exclamation mark inside it or the driver(s) with problems indicated by the Memory integrity.
4. Right-click on that device and select **Update driver**.  
![Clicking on the Update Driver Option by Right-clicking on the Incompatible Driver in Windows Device Manager App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/5-Clicking-on-the-Update-Driver-Option-by-Right-clicking-on-the-Incompatible-Driver-in-Windows-Device-Manager-App.jpg)
5. If updating the driver does not solve the problem, right-click it and select **Properties**.
6. Under the **General** tab, read the message in the **Device status** box.  
![Checking the Message in the Device Status Box Under the General Tab of Properties Window of Driver in Windows Device Manager App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/6-Checking-the-Message-in-the-Device-Status-Box-Under-the-General-Tab-of-Properties-Window-of-Driver-in-Windows-Device-Manager-App.jpg)
7. Take note of the error code and visit the [official Microsoft Support documentation](https://support.microsoft.com/en-us/topic/error-codes-in-device-manager-in-windows-524e9e89-4dee-8883-0afa-6bca0456324e) where all Device Manager-related errors are listed.
8. Find the relevant code information and apply the Microsoft recommended fix to fix the problem.

 What if applying the Microsoft recommended fix doesn't fix the problem with the driver, or there is no driver with a yellow triangle? In that case, you'll have to use third-party software to locate and uninstall the incompatible or corrupt driver.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123728/7443" target="_top" id="2123728">
  <img src="//a.impactradius-go.com/display-ad/7443-2123728" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123728/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Find and Uninstall Incompatible Drivers

 If you cannot locate the incompatible driver in Device Manager, use a third-party program, such as Autoruns, to identify corrupt or incompatible drivers and uninstall them.

 You can follow these steps to do that:

1. Download **Autoruns** from the [Microsoft website](https://learn.microsoft.com/en-us/sysinternals/downloads/autoruns).
2. Unzip the compressed file.
3. To run the app as an administrator, right-click on its executable file and select **Run as administrator**.
4. Go to the **Drivers** tab.
5. The drivers with issues will be highlighted, so locate them.  
![Checking the Corrupt Drivers Highlighted in the Autoruns Software](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/7-Clicking-on-the-Run-as-Administrator-Option-by-Right-clicking-on-the-Autoruns-Executable-File-in-Windows-File-Explorer.jpg)
6. Once they have been located, uncheck the box to disable them.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043594/7443" target="_top" id="2043594">
  <img src="//a.impactradius-go.com/display-ad/7443-2043594" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043594/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Unchecking the Box for the Incompatible Driver in the Drivers Tab of Autoruns App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/8-Unchecking-the-Box-for-the-Incompatible-Driver-in-the-Drivers-Tab-of-Autoruns-App.jpg)
7. If any driver gives an error when disabling, right-click it and select **Delete**.
8. Install the latest drivers from the official website or reboot your device to let Windows install them automatically.

 If you can't locate drivers identified as incompatible by Memory integrity before, the Autoruns app will facilitate finding and removing them.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528688/16446" target="_top" id="1528688">
  <img src="//a.impactradius-go.com/display-ad/16446-1528688" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528688/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Uninstall Relevant Apps

 If uninstalling the incompatible drivers does not work, you should uninstall the apps or software you installed from the same manufacturer as the drivers. Follow these steps to do that:

1. Right-click on the Windows **Start** button and select **Apps and Features**.  
![Clicking on the Apps and Features by Right-clicking on the Windows Start Button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/9-Clicking-on-the-Apps-and-Features-by-Right-clicking-on-the-Windows-Start-Button.jpg)
2. In the list of installed apps, locate the software from the same manufacturer.
3. Upon finding them, click on the **three vertical dots** next to them and select **Uninstall**.  
![Clicking on the Uninstall Button After Clicking on the Three Vertical Dots Next to Software in the Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/10-Clicking-on-the-Uninstall-Button-After-Clicking-on-the-Three-Vertical-Dots-Next-to-Software-in-the-Windows-Settings-App.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082536/7443" target="_top" id="2082536">
  <img src="//a.impactradius-go.com/display-ad/7443-2082536" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082536/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Uninstalling the relevant apps from the same manufacturer should resolve the issue. If it does not, ensure it isn't a Windows Update issue.

## 4\. Fix Update-Related Issues

 If incompatible or corrupt drivers aren't the problem, you should ensure your system is up-to-date and no updates are pending. To do this, right-click on the Windows **Start** button and select **Settings**. Next, navigate to **Windows Update** and click the **Check for updates** button on the right.

![Check for Updates Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Check-for-Updates-Windows.jpg)

 If they are paused, click **Resume updates** to let Windows update your system.

![Resuming Windows Update by Clicking on Resume Updates Button in Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Image-4-Resuming-Windows-Update-by-Clicking-on-Resume-Button-in-Windows-Settings-App.jpg)

 Moreover, if you've encountered a problem after installing an update recently, you should uninstall it. Our guide on [uninstalling updates in Windows 10 and 11](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) explains how to do it. If pending or recently installed updates are not to blame, apply the next fix.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118312/7443" target="_top" id="2118312">
  <img src="//a.impactradius-go.com/display-ad/7443-2118312" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118312/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Fix Corrupt System Files

 Corrupt system files are also a major cause of unforeseen issues with Windows features. The Memory integrity feature may have stopped working after a virus invaded your device and corrupted your system files. Thus, you must ensure that your system files are intact to rule out this possibility. An SFC scan can be helpful in this case.

 Search for **"Command Prompt"** in Windows Search, right-click on the **Command Prompt** in search results and click **Run as administrator**. Then type **"SFC /scannow"** and press **Enter**.

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/sfc-scannow-command-1.jpg)

 Once the scan is complete, refer to our guide on repairing corrupt system files with Windows built-in tools so you can properly analyze the results.

<!-- affiliate ads begin -->
<span id="1993650">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Reset the Windows Security App

 Issues with the Windows Security app can also interfere with the functionality of security features, like memory integrity.

 One way to rule out such issues is to reset the Windows Security app. Keep one caveat in mind, though: resetting Windows Security will revert any security customizations you've made to date. If you don't mind that, you can reset Windows Security.

 The process of resetting Windows Security is similar to [resetting any other Windows app](https://www.makeuseof.com/windows-reset-app/). Do that, and hopefully, the grayed-out memory integrity problem will resolve itself.

## 7\. Alternative Method to Enable the Memory Integrity Feature

 Using the Windows Security app isn't the only way to enable Windows' memory integrity feature. You can also adjust this setting within Registry Editor, which lets you access and modify Windows OS configuration settings. Therefore, if you are unable to turn on this feature from Windows Security, try enabling it from the Registry Editor.

 Follow these steps to enable the memory integrity feature from Registry Editor:

1. Type **"Registry Editor"** in Windows Search and open the **Registry Editor**.
2. Navigate to the following path:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\DeviceGuard\Scenarios\HypervisorEnforcedCodeIntegrity`
3. Right-click on the **Enabled** key in the right pane and select **Modify...**
4. Enter **"1"** under **Value data** if it is not already there.  
![Tweaking a Key Related to Memory Integrity in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/tweaking-a-key-realted-to-memory-integrity-in-windows-registry-editor.jpg)

 Misconfiguring keys in the Registry Editor can have unintended consequences. If you are unfamiliar with tweaking the registry, you can skip this step.

<!-- affiliate ads begin -->
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1576477/17382" target="_top" id="1576477">
  <img src="//a.impactradius-go.com/display-ad/17382-1576477" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1576477/17382" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Turn On the Memory Integrity Feature Again

 Memory integrity is a critical security feature, and if it is not enabled, it can seriously compromise the security of your device. Hopefully, by applying the fixes mentioned in the article, you will solve the problem and easily turn on Memory Integrity.

 But what causes this feature to be grayed out? In this article, we'll discuss why you cannot turn on this feature and how to identify and fix the underlying problem.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>