---
title: Unlocking Windows Safeguards Restricted by Admins
date: 2024-09-12T23:43:13.649Z
updated: 2024-09-15T16:58:50.279Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unlocking Windows Safeguards Restricted by Admins
excerpt: This Article Describes Unlocking Windows Safeguards Restricted by Admins
keywords: Windows Restrict Admin Access,Bypass Admin Security Measures,Unlock Windows Admin Protections,Override Admin Locks in Windows,Evasion of Admin Safeguards Windows,Disabling Windows Admin Controls,Circumventing Admin Windows Limits
thumbnail: https://thmb.techidaily.com/64bcba811dca59ee452fde50283dc6af9516c46b5a87dc01f6fa89f4e4093f9a.jpg
---

## Unlocking Windows Safeguards Restricted by Admins

 Some users have reported they can’t set Windows Security options because of an error that says, “This setting is managed by your administrator.” Those users see that error message just above options within the**Virus & threat protection** and**App & browser tabs** of that app. Consequently, they can’t turn on important Windows Security settings there that are grayed out and disabled.

 That issue has little to do with admin rights. Many users who encounter the issue are already utilizing Windows administrator accounts. This is how you can fix the “setting is managed by your administrator” error in Windows 11.

## 1\. Check for and Install Available Windows 11 Updates

 Although not the most likely potential solution, some users have said installing available Windows 11 updates helped them resolve this error. Patchers for Windows 11 usually address Windows bugs reported by users.

 If you're not sure how to do this, visit[how to install Windows 11 updates](https://www.makeuseof.com/windows-11-install-updates/) for a step-by-step guide.

## 2\. Reset the Windows Security and Settings Apps

 Users who’ve fixed the “setting is managed by your administrator” error have confirmed resetting the Windows Security and Settings apps can work. Resetting those apps will clear their data. You can reset Windows Security via Settings, as outlined in our[how to reset apps on Windows](https://www.makeuseof.com/windows-reset-app/) guide.

![The Reset button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reset-option.jpg)

 To reset Settings, you must open the Start menu and right-click the app’s shortcut. Select**App settings** to bring up some troubleshooting options for it. Then select the**Reset** troubleshooting option for the app.

## 3\. Uninstall Third-Party Antivirus Software

 Some third-party antivirus utilities can disable Windows Security features they effectively replace. If you’ve installed an overlapping third-party antivirus product, uninstalling it may resolve Windows Security’s administrator error. Uninstall antivirus software with a method within our guide on[how to remove Windows programs](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) to see if that resolves the issue.

![The uninstaller tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-uninstaller-tool.jpg)

 Should this solution work, the issue will likely reoccur if you reinstall the same third-party antivirus virus software. Then you would have to choose between using the third-party antivirus utility or Windows Security.

## 4\. Edit the Registry

 Many users have been able to fix the Windows Security administrator error by applying this confirmed registry solution. This registry tweak involves modifying a DWORD value, but you don’t need to delete any key. To apply this potential resolution, edit the registry like this:

1. Run the Windows Registry Editor app, which you can open with any method included in our[how to open Regedit](https://www.makeuseof.com/windows-11-open-registry-editor/) [g](https://www.makeuseof.com/windows-11-open-registry-editor/) uide.
2. Click inside the address box at the top of Registry Editor and erase the text in it.
3. Input this key path in the registry address bar and press**Return** :  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\DeviceGuard\Scenarios\HypervisorEnforcedCodeIntegrity`
4. Then double-click the**Enabled** DWORD within the**HypervisorEnforcedCodeIntegrity** key.  
![The HypervisorEnforced registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-hypervisor-key.jpg)
5. Clear the**Data value** box, and then input**0** there.
6. Select**OK** to set the**Enabled** DWORD’s value.  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/edit-dword-window.jpg)
7. Exit Registry Editor and click the**Power** \>**Restart** Start menu options.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130533/26400" target="_top" id="2130533">
  <img src="//a.impactradius-go.com/display-ad/26400-2130533" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130533/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118322/7443" target="_top" id="2118322">
  <img src="//a.impactradius-go.com/display-ad/7443-2118322" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118322/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Set Group Policy’s Real-time Protection Settings to "Not Configured"

 A possibility for Windows 11 Pro and Enterprise users to consider is that Group Policy Editor could be blocking changes to Windows Security settings. If you can open Group Policy Editor on your PC, check real-time protection policy settings aren’t enabled there. This is how you can set real-time protection settings to not configured in Group Policy Editor:

1. Find Group Policy Editor by clicking the search magnifying glass icon and inputting**gpedit.msc** .
2. Select**gpedit.msc** to open the Group Policy Editor window.
3. Then select**Computer Configuration** to extend that category.
4. Double-click**Administrative Template** to access several setting categories.
5. Next, double-click**Windows Components** \>**Microsoft Defender Antivirus** \>**Real-time Protection** in the navigation sidebar.  
![The Real-time Protection policy settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-real-time-protection-policy-settings.jpg)
6. Double-click any policy setting that’s with an enabled state.
7. Then select the**Not configured radio** button.  
![The Not Configured radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/not-configured-option.jpg)
8. Click**Apply** \>**OK** in the window to set the change.
9. Repeat the previous three steps for all real-time protection policies set to enabled.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123476/16836" target="_top" id="2123476">
  <img src="//a.impactradius-go.com/display-ad/16836-2123476" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123476/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Reinstall Windows Security

 You can’t reinstall Windows Security by uninstalling that app via Settings and downloading it from Microsoft Store. However, you can run a more general PowerShell command that reinstalls all apps pre-installed with Windows 11\. Try reinstalling Windows Security with that command as follows:

1. Open PowerShell with administrative rights. Our guide on[how to open PowerShell](https://www.makeuseof.com/windows-11-powershell-administrator/) includes various methods for opening that app.
2. Then input the following PowerShell command for reinstalling apps:  
`Get-AppXPackage -AllUsers | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reinstall app PowerShell command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reinstall-app-command.jpg)
3. Press**Enter** and wait for the command to finish.
4. Restart your laptop or desktop from the Start menu.

<!-- affiliate ads begin -->
<span id="1983582">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983582.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983582">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983582.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983582%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983582/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 7\. Reinstall Windows 11 With the Media Creation Tool

 Reinstalling Windows 11 by downloading an ISO with Media Creation Tool is a drastic potential solution. However, users have confirmed updating Windows 11 in such a way works for fixing this error. Furthermore, you can select to preserve apps and files when reinstalling. This is how to reinstall Windows 11:

1. Download the latest Windows 11 ISO with the Media Creation Tool. Our guide on[how to download a Windows 11 ISO](https://www.makeuseof.com/windows-11-download-iso/) includes step-by-step instructions for how to do so.
2. Then double-click your downloaded Windows 11 ISO file.
3. Click**setup.exe** to open the Windows 11 installer.  
![The Windows 11 Setup window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-setup-window.jpg)
4. Select**Next** to initiate a system check.
5. Press the**Accept** button for the license terms.
6. The**Keep personal files and apps** option will probably be set by default at the ready-to-install stage. However, you click**Change what to keep** to make sure the**Keep personal files and apps** option is selected.  
![The Keep personal files and apps radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/keep-personal-files-option.jpg)
7. Then select**Next** to proceed to the last step.
8. Click**Install** to reinstall Windows 11.

## Change Windows Security’s Settings Again

 Those are the most widely cited ways to fix the “setting is managed by your administrator” error in Windows 11\. So, applying those potential resolutions will probably resolve the “setting is managed by your administrator” issue on your PC. Then you’ll be able to set all the options within Windows Security as required.

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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-pinpointing-the-leading-10-invisible-story-enthusiasts/"><u>[New] 2024 Approved Pinpointing the Leading 10 Invisible Story Enthusiasts</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-the-blueprint-for-gathering-free-pictorial-video-files/"><u>[New] The Blueprint for Gathering Free Pictorial Video Files</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-crafting-a-jujutsu-kaisen-tiktok-challenge/"><u>[Updated] 2024 Approved Crafting a Jujutsu Kaisen TikTok Challenge</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-how-to-and-where-download-unboxing-video-background-music-for-2024/"><u>[Updated] How To & Where Download Unboxing Video Background Music for 2024</u></a></li>
<li><a href="https://app-tips.techidaily.com/comprehensive-guide-to-youcut-tool-insights-and-essential-information/"><u>Comprehensive Guide to YouCut Tool : Insights & Essential Information</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/-yoga-routines-youtubes-leading-fitness-sites/"><u>Elite Yoga Routines YouTube's Leading Fitness Sites</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-missing-drivers-on-windows-11-start-up-process/"><u>Fixing Missing Drivers on Windows 11 Start-Up Process</u></a></li>
<li><a href="https://windows11.techidaily.com/introducing-cli-to-taskmanager-for-enhanced-computing-experience/"><u>Introducing CLI to TaskManager for Enhanced Computing Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-a-guide-to-reading-qr-codes/"><u>Mastering Windows: A Guide to Reading QR Codes</u></a></li>
<li><a href="https://windows11.techidaily.com/mute-unwanted-tips-and-hints-in-windows-notification-hub/"><u>Mute Unwanted Tips and Hints in Windows Notification Hub</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-address-write-access-failure-on-windows-11/"><u>Strategies to Address Write Access Failure on Windows 11</u></a></li>
<li><a href="https://win-amazing.techidaily.com/successfully-resolving-intel-dptf-driver-installation-issues-a-step-by-step-guide/"><u>Successfully Resolving Intel DPTF Driver Installation Issues: A Step-by-Step Guide</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/system-graphics-not-initializing-correctly/"><u>System Graphics Not Initializing Correctly</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-defective-xbox-mic-in-windows-1011/"><u>Troubleshooting Defective Xbox Mic in Windows 10/11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/what-does-enter-puk-code-mean-and-why-did-the-sim-get-puk-blocked-on-poco-x6-device-by-drfone-android/"><u>What Does Enter PUK Code Mean And Why Did The Sim Get PUK Blocked On Poco X6 Device</u></a></li>
</ul></div>

