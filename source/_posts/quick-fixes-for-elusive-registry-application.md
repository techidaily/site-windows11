---
title: Quick Fixes for Elusive 'Registry' Application
date: 2024-09-13T18:42:38.325Z
updated: 2024-09-15T23:47:11.350Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quick Fixes for Elusive 'Registry' Application
excerpt: This Article Describes Quick Fixes for Elusive 'Registry' Application
keywords: Registry Repair Tips,Elusive Registry Cleanup,App Registry Troubleshooting,Quick Registry Fixes,Hidden Registry Issues,Registry Correction Guide,Fixing Registry Errors
thumbnail: https://thmb.techidaily.com/1a0a225965c2ce4acfd77f7b81b0abb5e4b211b4f6a739d5a50d45eaa5fd443d.jpg
---

## Quick Fixes for Elusive 'Registry' Application

 Regedit.exe is the application file for Registry Editor, which is an app with which users tweak the registry. However, some users can’t open that app because of a regedit.exe error. Those users have reported this error message pops up when they try to launch Registry Editor: “Windows cannot find C:\\Windows\\regedit.exe.”

 This registry app error can arise in Windows 11/10 and earlier platforms of the same OS series. It effectively blocks registry access for users who need to resolve it. These are some of the ways to fix the “cannot find regedit.exe” error in Windows 11/10.

## 1\. Run a Full Antivirus Scan

 The “cannot find regedit.exe” error can sometimes be due to malware targeting the Registry Editor. So, we recommend all users who need to resolve this issue first run a full antivirus scan. If you haven’t got any antivirus software installed, try running a Windows Security scan as follows:

1. Double-click Windows Security’s shield icon within the system tray on the right of your taskbar.
2. Click the**Virus & threat** **protection** tab along the left of Windows Security.
3. Select**Scan options** to access all the scanning radio buttons.  
![The Virus & threat protection tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/virus-threat-protection-tab.jpg)
4. Next, click Windows Security’s**Full Scan** option.
5. Press**Scan now** to initiate the scanning.  
![The Scan now button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/scan-now-button.jpg)
6. If Windows Security detects something, select the**Remove action** options for everything detected.
7. Then click**Start actions** .

## 2\. Scan and Repair System Files

 Scanning system files is a potential solution for the “cannot find regedit.exe” error confirmed to work by some. Those users resolved the issue with the System File Checker Command Prompt utility. You can scan and repair system files with that SFC tool like this:

1. First, click the search box button along the taskbar.
2. Look for the Command Prompt by typing**cmd** inside the search tool.
3. Launch Command Prompt in its admin mode by clicking that search result with the mouse’s right button and selecting Run as administrator.
4. Before running an SFC scan, execute the following command:  
`DISM.exe /Online /Cleanup-image /Restorehealth`
5. Type in this SFC command text and press**Enter** :  
`sfc /scannow`  
![The SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-scannow-command.jpg)
6. Wait until that tool’s scan gets to 100 percent. Then you’ll see a Windows Resource Protection message in the Prompt’s window.

## 3\. Enable Registry Editor Access in Group Policy Editor

 Windows Pro and Enterprise editions have a Group Policy Editor tool that includes a**Prevent access to registry editing tools** option. If you’re a Pro or Enterprise user, check if that policy setting is enabled and causing the issue at hand. This is how you can enable Registry Editor access with Group Policy Editor:

1. Open Run (see[how to open Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) ), type**gpedit.msc** in that accessory’s command box, and select**OK** .
2. Select User Configuration in Group Policy Editor’s sidebar.
3. Double-click**Administrative Templates** \>**System** to reach the**Prevent access to registry editing tools** option.  
![The Local Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/local-group-policy-editor.jpg)
4. Then double-click**Prevent access to registry editing** tools to bring up the window for that policy setting.
5. Select the**Disabled** option, and click**Apply** to save.  
![The prevent access to registry editing tools policy setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/prevent-access-to-registry-edting-tools.jpg)
6. Press the Prevent access to registry editing tools window’s**OK** button.
7. Exit Group Policy Editor, and restart your PC.

## 4\. Edit the Path Environment Variable

 A wrongly configured or missing path environment variable can cause the “cannot find regedit.exe” error. Some users may need to edit an environment variable to resolve this issue. To do so, follow these steps for editing the Path variable:

1. Press**Win + S** to access the search box.
2. Enter**View advanced system settings** inside the**Type here to search** box.
3. Select**View advanced system settings** to view a System Properties window.
4. Click**Environment Variables** to open up that window.  
![The Environment Variables button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/environment-variables-button.jpg)
5. Select**Path** , and click the**Edit** button.  

<!-- affiliate ads begin -->
<span id="1975562">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975562.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975562">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975562.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975562%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975562/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Environment Variables window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/environment-varibles-window.jpg)
6. Click**Edit** on the environment variable window.
7. Input this variable:  
`%USERPROFILE%\AppData\Local\Microsoft\WindowsApps`
8. Select the Edit environment variable window’s**OK** option.  
![The Edit environment variables window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/edit-environent-variables-window.jpg)
9. Reboot your Windows desktop or laptop.

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014850/22899" target="_top" id="2014850">
  <img src="//a.impactradius-go.com/display-ad/22899-2014850" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014850/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Restore the Registry Editor’s Default Registry Values

 This error can occur because some of the Registry Editor’s registry values have been altered. So, restoring the default registry values for the regedit.exe could be a solution for some users. You can restore those values to default without the Registry Editor app by setting up a script as follows:

1. Bring up the Windows text editor with a method in our guide for opening Notepad.
2. Select this script code and press the**Ctrl** +**C** key combination:  
`[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion]  

 "SM_GamesName"="Games"  

 "SM_ConfigureProgramsName"="Set Program Access and Defaults"  

 "CommonFilesDir"="C:\\Program Files\\Common Files"  

 "CommonFilesDir (x86)"="C:\\Program Files (x86)\\Common Files"  

 "CommonW6432Dir"="C:\\Program Files\\Common Files"  

 "DevicePath"=hex(2):25,00,53,00,79,00,73,00,74,00,65,00,6d,00,52,00,6f,00,6f,\  

 00,74,00,25,00,5c,00,69,00,6e,00,66,00,3b,00,00,00  

 "MediaPathUnexpanded"=hex(2):25,00,53,00,79,00,73,00,74,00,65,00,6d,00,52,00,\  

 6f,00,6f,00,74,00,25,00,5c,00,4d,00,65,00,64,00,69,00,61,00,00,00  

 "ProgramFilesDir"="C:\\Program Files"  

 "ProgramFilesDir (x86)"="C:\\Program Files (x86)"  

 "ProgramFilesPath"=hex(2):25,00,50,00,72,00,6f,00,67,00,72,00,61,00,6d,00,46,\  

 00,69,00,6c,00,65,00,73,00,25,00,00,00  

 "ProgramW6432Dir"="C:\\Program Files"  

 Windows Registry Editor Version 5.00`
3. Click inside the Notepad window, and press the**Ctrl** +**V** keyboard shortcut for pasting.  
![The registry script for restoring default values](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/edit-registry-script.jpg)
4. Press Notepad’s**Ctrl** +**Shift** +**S** keyboard shortcut for opening the "Save as" window.

<!-- affiliate ads begin -->
<span id="1993645">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993645.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993645">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993645.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993645%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993645/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Select the**All files** option in the**Save as type** menu.  
![The All Files option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/all-files-option.jpg)
6. Type**Registry Fix.reg** inside the name box.
7. Choose to save the script on the desktop area.
8. Select the**Save** option, and then close Notepad.
9. Right-click the saved**Registry Fix.reg** script on the desktop and select**Show more options** \>**Merge** .
10. Click**Yes** to confirm the selected option.

## 6\. Perform a System Restore

 Restoring Windows to an earlier date can fix corrupted files. If you have the System Restore tool turned on, that might be worth a try. You can roll back Windows as outlined in our guide for[creating restore points in Windows](https://www.makeuseof.com/windows-11-create-restore-point/) and utilizing System Restore. Select a restore point predating the “cannot find regedit.exe” error on your PC if you can.

![The System Restore tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/system-restore-tool.jpg)

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2005183/22899" target="_top" id="2005183">
  <img src="//a.impactradius-go.com/display-ad/22899-2005183" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2005183/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You may need to reinstall some software after performing system restoration. Software installed after any restore point’s date is not preserved. Click the**Scan for affected programs** option for whatever restoration point you chose to see what software it removes.

## 7\. Reset Windows

 This last resolution will restore Windows 11/10 to a factory default configuration, which will likely resolve the “cannot find regedit.exe” issue. However, this is the last thing you should try since resetting Windows will also remove software packages that weren’t preinstalled. Our guide about[factory resetting a Windows PC](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) includes the steps for applying this fix.

![The Reset this PC button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-reset-this-pc-button.jpg)

## Edit the Registry With Registry Editor Once More

 We hope and expect the potential resolutions in this guide will fix the “cannot find regedit.exe” error on your PC. Those possible solutions don’t come with a 100 percent guarantee, but they’ll probably get that issue sorted in most cases. Try applying them all as ordered above to get the Registry Editor working again.

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
<li><a href="https://youtube-data.techidaily.com/imple-steps-for-incorporating-videos-into-articles-for-2024/"><u>[New] Simple Steps for Incorporating Videos Into Articles for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-the-ultimate-guide-to-recording-gaming-with-fraps/"><u>[Updated] The Ultimate Guide to Recording Gaming with Fraps</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-bandicam-unveiled-the-complete-review/"><u>2024 Approved Bandicam Unveiled The Complete, Review</u></a></li>
<li><a href="https://unlock-android.techidaily.com/a-perfect-guide-to-remove-or-disable-google-smart-lock-on-xiaomi-redmi-12-by-drfone-android/"><u>A Perfect Guide To Remove or Disable Google Smart Lock On Xiaomi Redmi 12</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-life360-shows-wrong-location-on-oneplus-ace-2v-drfone-by-drfone-virtual-android/"><u>How to Fix Life360 Shows Wrong Location On OnePlus Ace 2V? | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-ultimate-guide-to-youtube-editing-in-imovie-software/"><u>In 2024, The Ultimate Guide to YouTube Editing in iMovie Software</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-login-fixes-for-denied-users/"><u>Mastering Windows Login Fixes for Denied Users</u></a></li>
<li><a href="https://windows11.techidaily.com/re-engineering-your-typing-experience-layout-changes-in-win-11/"><u>Re-Engineering Your Typing Experience: Layout Changes in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-sniptools-performance-9-key-actions/"><u>Reviving SnipTool's Performance: 9 Key Actions</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/schritt-fur-schritt-anleitung-zum-konvertieren-von-hevc-zu-mp4-ohne-qualitatsverluste/"><u>Schritt-Für-Schritt-Anleitung Zum Konvertieren Von HEVC Zu MP4 Ohne Qualitätsverluste</u></a></li>
<li><a href="https://windows11.techidaily.com/skip-past-stalled-wow-65-updates-on-pc/"><u>Skip Past Stalled WoW 6.5 Updates on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-to-fixed-outlooks-non-previewable-files-problem/"><u>Solutions to Fixed Outlook's Non-Previewable Files Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-handling-service-delays-and-avoiding-error-1053/"><u>Troubleshooting Guide: Handling Service Delays and Avoiding Error 1053</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-windows-n-variants-for-software-developers/"><u>Understanding Windows N Variants: For Software Developers</u></a></li>
<li><a href="https://windows11.techidaily.com/uninterrupted-play-overcoming-fall-guys-network-errors-on-pc/"><u>Uninterrupted Play: Overcoming Fall Guys Network Errors on PC</u></a></li>
</ul></div>

