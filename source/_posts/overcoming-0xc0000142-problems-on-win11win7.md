---
title: Overcoming 0XC0000142 Problems on Win11/Win7
date: 2024-06-25T12:01:12.950Z
updated: 2024-06-26T12:01:12.950Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming 0XC0000142 Problems on Win11/Win7
excerpt: This Article Describes Overcoming 0XC0000142 Problems on Win11/Win7
keywords: Win11 Crash Fixing Guide,Win11 ZeroCode Error Resolution,Win7 Overheating Solutions,Win7 Freezing Issue Remedies,WinXP Boot Problems,WinXP ZeroCode Correction Steps,Windows XP Stability Improvement
thumbnail: https://thmb.techidaily.com/a333bfbef34affdca1048ed2699696db5230242a15d7fcb3455927615d5179aa.JPG
---

## Overcoming 0XC0000142 Problems on Win11/Win7

 Error 0xc0000142 occurs when users try launching some Windows software packages. Those who encountered this issue usually see an error message that says, "The application was unable to start correctly (0xc0000142)." When that happens, the affected program refuses to launch.

 Unfortunately, error 0xc0000142 is a generic code that could affect many Windows software packages. However, many users report that it usually comes from Microsoft Office applications and games.

 So, if you're running into this issue, this is how you can fix error 0xc0000142 in Windows 11 and 10\.

## 1\. Run Affected Software With Admin Permissions

 Start your error 0xc0000142 troubleshooting by setting the affected software to run as an administrator. That will ensure the program can access more restricted file locations. You could potentially stop this error code by [setting the affected app to always run as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/).

## 2\. Set Affected Software to Run in Compatibility Mode

 If error 0xc0000142 arises for older software, there could be a compatibility issue with your PC's Windows 11/10 platform. Setting up an app or game to run in compatibility mode for an older Windows platform could resolve such an issue.

 This is how you can set your software to run in compatibility mode:

1. Press the **Windows** logo + **E** keyboard buttons and open the installation folder for your affected software.
2. Right-click the software's EXE (application) file to select **Properties**.  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-properties-option.jpg)
3. Click on the properties window's **Compatibility** tab.
4. Select the checkbox labeled **Run this program in compatibility mode**.  
![Run this program as an administrator checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-this-program-in-compatibility-mode-checkbox.jpg)
5. Choose the Windows OS that was the latest one in your software's release year within the drop-down menu. Selecting Windows 8 or 7 there will probably be sufficient for most apps.
6. Click **Apply** to set the new compatibility mode.
7. Select **OK** to exit the properties window.

 An alternative method is to [use the Windows 11 Program Compatibility Troubleshooter](https://www.makeuseof.com/program-compatibility-troubleshooter-windows-11-guide/). That tool automatically applies recommended compatibility settings, saving you time and effort.

## 3\. Scan Your PC's System Files

 Corrupted DLL (Dynamic Link Library) system files can cause error 0xc0000142\. You can check for and remedy system file corruption by [running the Windows System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/).

![The SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-sfc-scannow-command5.jpg)

 We also recommend running a Deployment Imaging Servicing Management scan command. That utility can remedy issues with the Windows system image. To run that tool, execute this command in the Command Prompt:

`DISM.exe /Online /Cleanup-image /Restorehealth`

## 4\. Set the Right System Locale

 Setting a correct system locale is an error 0xc0000142 fix that's worked for some uses. To apply this fix, you must select a system locale setting for non-unicode software that matches the correct region for your PC. You can set the suitable system locale as follows:

1. Press **Windows** key + **R**, type **Control Panel** in Run, and select **OK**.
2. Click on **Region** inside the All Control Panel Items window.  
![The Region applet in Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/region-in-control-panel.jpg)
3. Next, click on the **Administrative** tab.
4. Press the **Change system locale** button.  
![The Change system locale button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-system-locale-button.jpg)
5. Select the correct region for your PC in the drop-down menu.
6. Press **OK** in the Region Settings window.
7. Click on the **Apply** button to save your regional settings and **OK** to exit.

## 5\. Reregister DLL Files in Windows

 Lots of users have said reregistering all DLL files works for fixing error 0xc0000142\. This highlights that error 0xc0000142 arises because some required DLL files aren't correctly registered. There are many DLL files, but you can reregister them all by executing a single command as follows:

1. Press the **Windows** logo + **S** key simultaneously and input Command Prompt.
2. [Open the Command Prompt with admin privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/) by selecting **Run as administrator** for that app's search result.
3. Input this command for reregistering DLLs and hit **Return**:  
`for %1 in (*.dll) do regsvr32 /s %1`  
![The reregister all DLLs command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/re-register-all-command.jpg)
4. Then wait until all the DLLs have been registered before closing the Command Prompt.

## 6\. Run a CHKDSK (Check Disk) Scan

 Another possible reason for the error 0xc0000142 is that your PC has bad disk sectors. You can check for and repair bad disk sectors by [running a CHKDSK (Check Disk) scan](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) in the Command Prompt.

![The CHKDSK command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/chkdsk-scan.jpg)

## 7\. Update the Driver for Your PC's GPU (Graphics Processing Unit)

 If you need to fix the error 0xc0000142 for a Windows game, [updating your PC's graphics driver](https://www.makeuseof.com/update-graphics-drivers-in-windows-10/) might help. You can do that manually, using a third-party driver updater tool or AMD or NVIDIA software like GeForce Experience.

![A Download option in GeForce Experience](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/geforce-experience.jpg)

## 8\. Enable the .NET Framework 3.5 Feature

 Some programs need older .NET Framework versions to run in Windows. So, you might need to [enable .NET Framework 3.5 on Windows](https://www.makeuseof.com/windows-10-install-net-framework-version-35/) if that feature isn't available on your computer.

![The .NET Framework option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/net-framework-3-5.jpg)

## 9\. Edit the Windows Registry Key

 Many users who've fixed error 0xc0000142 confirm editing a Windows registry worked for them. Those users modified the value of a LoadAppInit\_DLL DWORD within the Windows key. These are the exact steps for applying this potential resolution:

 It's risky to edit the Registry. Always [back up your Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before making any changes to ensure you can revert to the original if you encounter issues after applying this fix.

1. Click on your taskbar's magnifying glass icon or the Search box to activate a file finder tool.
2. Enter the search phrase **regedit** into the file finder tool.
3. Select **Registry Editor** to view the registry window.
4. Go to this key location by entering the following path within Registry Editor's address bar:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\Current Version\Windows`  
![The Windows key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-key.jpg)
5. Double-click on the **LoadAppInit\_DLLs** DWORD.
6. Then input **0** in the **Value data** box if that DWORD is set differently.  
![The EDIT DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/edit-dword-window.jpg)
7. Click **OK** to apply the new value for the LoadAppInit\_DLLs DWORD.
8. Close out of the Registry Editor and restart your PC.

## 10\. Reinstall Affected Software Packages

 The final potential solution is reinstalling software packages for which the 0xc0000142 error occurs. Doing so will refresh and repair the software's files, which might be necessary if other resolutions don't work. Reinstalling is also another way to update apps.

![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-uninstall-option.jpg)

 There are [many ways to uninstall software in Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/), and you can choose any method to remove the app. However, if the error occurs when you open a game, you may need to uninstall it with its client software, such as the Epic Games Launcher. Then, reinstall the latest version of the app or game by downloading it from its website or gaming client.

## Get Error 0xc0000142 Sorted Out in Windows 11 and Windows 10

 Fixing error 0xc0000142 isn't always simple because that's an issue with many possible causes. There are numerous confirmed ways to fix that issue, many of which are covered here. So, you'll probably have to try applying at least a few of those troubleshooting methods to find one that gets error 0xc0000142 sorted out on your PC.

 Various third-party repair tools for Windows 11 and Windows 10 might also be useful for fixing error 0xc0000142\. Windows Repair, Advanced SystemCare, and Windows Repair Toolbox are among the best freeware repair tools for software troubleshooting.

 Unfortunately, error 0xc0000142 is a generic code that could affect many Windows software packages. However, many users report that it usually comes from Microsoft Office applications and games.

 So, if you're running into this issue, this is how you can fix error 0xc0000142 in Windows 11 and 10\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/simplify-system-upkeep-automatic-driver-replacement-for-amd/"><u>Simplify System Upkeep: Automatic Driver Replacement for AMD</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-counteract-d3d11-hardware-failures-in-w11w10/"><u>Strategies to Counteract D3D11 Hardware Failures in W11/W10</u></a></li>
<li><a href="https://windows11.techidaily.com/why-choosing-windows-11-is-a-wise-decision-over-macos/"><u>Why Choosing Windows 11 Is a Wise Decision over MacOS</u></a></li>
<li><a href="https://windows11.techidaily.com/resetting-grammarly-settings-in-windows/"><u>Resetting Grammarly Settings in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/utilizing-windows-widgets-for-real-time-resource-tracking/"><u>Utilizing Windows Widgets for Real-Time Resource Tracking</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-the-not-an-empty-directory-alert-error-code-0x80070091-in-win11/"><u>Conquering the Not an Empty Directory Alert (Error Code: 0X80070091) in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/reverse-c-drive-data-hoarding-in-windows-systems/"><u>Reverse C: Drive Data Hoarding in Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-rectify-and-resolve-onedrive-errors-in-os/"><u>How to Rectify and Resolve OneDrive Errors in OS</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-application-startup-hexadecimal-issue-error/"><u>Unraveling The Application Startup Hexadecimal Issue (Error)</u></a></li>
<li><a href="https://windows11.techidaily.com/declutter-your-disk-space-auto-deletion-settings-for-windows-11/"><u>Declutter Your Disk Space: Auto-Deletion Settings for Windows 11</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/how-to-download-part-of-youtube-video/"><u>How to Download Part of YouTube Video?</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-professional-linux-sound-capture-a-rundown-of-top-software-for-studio-quality-audio/"><u>New Professional Linux Sound Capture A Rundown of Top Software for Studio-Quality Audio</u></a></li>
<li><a href="https://android-location-track.techidaily.com/2-ways-to-monitor-honor-play-7t-activity-drfone-by-drfone-virtual-android/"><u>2 Ways to Monitor Honor Play 7T Activity | Dr.fone</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-audio-fade-infade-out-secrets-unleash-the-power-of-final-cut-pro-for-2024/"><u>Updated Audio Fade-In/Fade-Out Secrets Unleash the Power of Final Cut Pro for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/024-approved-the-ultimate-list-of-12-top-notch-youtube-gaming-intros-freepaid/"><u>[New] 2024 Approved  The Ultimate List of 12 Top-Notch YouTube Gaming Intros (Free/Paid)</u></a></li>
<li><a href="https://fake-location.techidaily.com/read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-apple-iphone-14-plus-drfone-by-drfone-virtual-ios/"><u>Read This Guide to Find a Reliable Alternative to Fake GPS On Apple iPhone 14 Plus | Dr.fone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/the-ultimate-guide-to-time-lapse-apps-for-mobile-phones/"><u>The Ultimate Guide to Time-Lapse Apps for Mobile Phones</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-video-rotation-made-easy-top-10-online-tools-for-2024/"><u>New Video Rotation Made Easy Top 10 Online Tools for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-turning-snapchat-videos-inside-out-easily/"><u>[Updated] In 2024, Turning Snapchat Videos Inside Out Easily</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/in-2024-screen-format-options-on-amazon-prime/"><u>In 2024, Screen Format Options on Amazon Prime</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>