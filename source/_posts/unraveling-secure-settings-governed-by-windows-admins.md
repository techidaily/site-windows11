---
title: Unraveling Secure Settings Governed by Windows Admins
date: 2024-12-09T17:27:16.359Z
updated: 2024-12-10T16:41:26.579Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unraveling Secure Settings Governed by Windows Admins
excerpt: This Article Describes Unraveling Secure Settings Governed by Windows Admins
keywords: Windows Admin Security,Windows Controls,Admin Access Rules,Security Policy Management,Admin Privileges Limit,Secure Admin Settings,System Admin Restrictions
thumbnail: https://thmb.techidaily.com/c2d843fc2e375187b2194dd914e4e340539dd6293ab4433f92ecd542eef0fd55.jpg
---

## Unraveling Secure Settings Governed by Windows Admins

 Some users have reported they can’t set Windows Security options because of an error that says, “This setting is managed by your administrator.” Those users see that error message just above options within the**Virus & threat protection** and**App & browser tabs** of that app. Consequently, they can’t turn on important Windows Security settings there that are grayed out and disabled.

 That issue has little to do with admin rights. Many users who encounter the issue are already utilizing Windows administrator accounts. This is how you can fix the “setting is managed by your administrator” error in Windows 11.

## 1\. Check for and Install Available Windows 11 Updates

 Although not the most likely potential solution, some users have said installing available Windows 11 updates helped them resolve this error. Patchers for Windows 11 usually address Windows bugs reported by users.

 If you're not sure how to do this, visit[how to install Windows 11 updates](https://www.makeuseof.com/windows-11-install-updates/) for a step-by-step guide.

## 2\. Reset the Windows Security and Settings Apps

 Users who’ve fixed the “setting is managed by your administrator” error have confirmed resetting the Windows Security and Settings apps can work. Resetting those apps will clear their data. You can reset Windows Security via Settings, as outlined in our[how to reset apps on Windows](https://www.makeuseof.com/windows-reset-app/) guide.

![The Reset button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reset-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/97ydpSmzTJw?si=tFcelmtQX4u-b3u5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To reset Settings, you must open the Start menu and right-click the app’s shortcut. Select**App settings** to bring up some troubleshooting options for it. Then select the**Reset** troubleshooting option for the app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aG3NRuHrIJg?si=HwzwD0RXmrzIXX1V" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9hsPbiic0O8?si=58mZ2Cu6wicQfsUP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

9. Repeat the previous three steps for all real-time protection policies set to enabled.

## 6\. Reinstall Windows Security

 You can’t reinstall Windows Security by uninstalling that app via Settings and downloading it from Microsoft Store. However, you can run a more general PowerShell command that reinstalls all apps pre-installed with Windows 11\. Try reinstalling Windows Security with that command as follows:

1. Open PowerShell with administrative rights. Our guide on[how to open PowerShell](https://www.makeuseof.com/windows-11-powershell-administrator/) includes various methods for opening that app.
2. Then input the following PowerShell command for reinstalling apps:  
`Get-AppXPackage -AllUsers | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reinstall app PowerShell command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reinstall-app-command.jpg)
3. Press**Enter** and wait for the command to finish.
4. Restart your laptop or desktop from the Start menu.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GFHH14XlFCk?si=2HcjQbDx5eG0ZQAt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oP8grXxuy2o?si=uIRNhTYbecTcaC7J" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

8. Click**Install** to reinstall Windows 11.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/P6Wfzj6YNDM?si=WRZQD9zCdQ1_tW1b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://youtube-lab.techidaily.com/024-approved-bring-your-vision-online-mobilizing-content-creation-with-ease-and-simplicity/"><u>[New] 2024 Approved Bring Your Vision Online Mobilizing Content Creation with Ease and Simplicity</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-elevate-creations-get-free-high-quality-templates-today-for-2024/"><u>[New] Elevate Creations - Get FREE High-Quality Templates Today for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-a-comprehensive-introduction-to-color-grading-with-luts/"><u>[Updated] A Comprehensive Introduction to Color Grading with LUTs</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-exclusive-screensaver-pro-for-smartphones/"><u>[Updated] In 2024, Exclusive ScreenSaver Pro for Smartphones</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-top-platforms-for-amplifying-youtube-content/"><u>2024 Approved Top Platforms for Amplifying YouTube Content</u></a></li>
<li><a href="https://win-web.techidaily.com/einfach-klassisch-wie-man-iphones-durch-bluetooth-miteinander-verbindet-um-musik-zu-teilen/"><u>Einfach Klassisch: Wie Man iPhones Durch Bluetooth Miteinander Verbindet, Um Musik Zu Teilen</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-in-search-of-quality-identifying-the-top-5-virtual-title-designers/"><u>In 2024, In Search of Quality Identifying the Top 5 Virtual Title Designers</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-windows-11-to-launch-outlook-preview/"><u>Navigating Through Windows 11 to Launch Outlook Preview</u></a></li>
<li><a href="https://extra-information.techidaily.com/screencentral-exclusive-global-views-with-homeside-links/"><u>ScreenCentral Exclusive Global Views with Homeside Links</u></a></li>
<li><a href="https://driver-install.techidaily.com/seamlessly-updating-amd-with-windows-oss-versions-included/"><u>Seamlessly Updating AMD with Windows OSs, Versions Included</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-content-unreachable-issue-with-steam-desktop-client/"><u>Solving Content Unreachable Issue with Steam Desktop Client</u></a></li>
<li><a href="https://windows11.techidaily.com/uncomplicated-upgrade-the-essence-of-windows-11-installation/"><u>Uncomplicated Upgrade: The Essence of Windows 11 Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-best-matched-nvidia-drivers-gaming-studios/"><u>Unveiling Best Matched Nvidia Drivers – Gaming, Studios</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-solutions-for-unzipped-files-woes/"><u>Win 11: Solutions for Unzipped Files Woes</u></a></li>
</ul></div>

