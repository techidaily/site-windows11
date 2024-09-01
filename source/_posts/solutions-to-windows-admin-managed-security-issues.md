---
title: Solutions to Windows Admin-Managed Security Issues
date: 2024-08-31T22:14:55.536Z
updated: 2024-09-01T22:14:55.536Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Solutions to Windows Admin-Managed Security Issues
excerpt: This Article Describes Solutions to Windows Admin-Managed Security Issues
keywords: WinSecManageSolutions,WindowsSecurityAdmin,ManagedWinSysSecurity,AdminWindowsSecurityCare,SecureWindowsAdministration,WindowsSysSecurityFixes,AdminManagedSysSecurity
thumbnail: https://thmb.techidaily.com/e43b0bc66a6afa452744238286fc0843b9dfd431ddd2cd63d446736a0115992b.png
---

## Solutions to Windows Admin-Managed Security Issues

 Some users have reported they can’t set Windows Security options because of an error that says, “This setting is managed by your administrator.” Those users see that error message just above options within the**Virus & threat protection** and**App & browser tabs** of that app. Consequently, they can’t turn on important Windows Security settings there that are grayed out and disabled.

 That issue has little to do with admin rights. Many users who encounter the issue are already utilizing Windows administrator accounts. This is how you can fix the “setting is managed by your administrator” error in Windows 11.

## 1\. Check for and Install Available Windows 11 Updates

 Although not the most likely potential solution, some users have said installing available Windows 11 updates helped them resolve this error. Patchers for Windows 11 usually address Windows bugs reported by users.

 If you're not sure how to do this, visit[how to install Windows 11 updates](https://www.makeuseof.com/windows-11-install-updates/) for a step-by-step guide.

## 2\. Reset the Windows Security and Settings Apps

 Users who’ve fixed the “setting is managed by your administrator” error have confirmed resetting the Windows Security and Settings apps can work. Resetting those apps will clear their data. You can reset Windows Security via Settings, as outlined in our[how to reset apps on Windows](https://www.makeuseof.com/windows-reset-app/) guide.

![The Reset button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reset-option.jpg)

 To reset Settings, you must open the Start menu and right-click the app’s shortcut. Select**App settings** to bring up some troubleshooting options for it. Then select the**Reset** troubleshooting option for the app.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
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
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
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
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
9. Repeat the previous three steps for all real-time protection policies set to enabled.

<!-- affiliate ads begin -->
<span id="1993652">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Reinstall Windows Security

 You can’t reinstall Windows Security by uninstalling that app via Settings and downloading it from Microsoft Store. However, you can run a more general PowerShell command that reinstalls all apps pre-installed with Windows 11\. Try reinstalling Windows Security with that command as follows:

1. Open PowerShell with administrative rights. Our guide on[how to open PowerShell](https://www.makeuseof.com/windows-11-powershell-administrator/) includes various methods for opening that app.
2. Then input the following PowerShell command for reinstalling apps:  
`Get-AppXPackage -AllUsers | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reinstall app PowerShell command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reinstall-app-command.jpg)
3. Press**Enter** and wait for the command to finish.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Restart your laptop or desktop from the Start menu.

## 7\. Reinstall Windows 11 With the Media Creation Tool

 Reinstalling Windows 11 by downloading an ISO with Media Creation Tool is a drastic potential solution. However, users have confirmed updating Windows 11 in such a way works for fixing this error. Furthermore, you can select to preserve apps and files when reinstalling. This is how to reinstall Windows 11:

1. Download the latest Windows 11 ISO with the Media Creation Tool. Our guide on[how to download a Windows 11 ISO](https://www.makeuseof.com/windows-11-download-iso/) includes step-by-step instructions for how to do so.
2. Then double-click your downloaded Windows 11 ISO file.
3. Click**setup.exe** to open the Windows 11 installer.  
![The Windows 11 Setup window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-setup-window.jpg)
4. Select**Next** to initiate a system check.
<!-- affiliate ads begin -->
<a href="https://uperfect.sjv.io/c/5597632/1246754/15155" target="_top" id="1246754"><img src="//a.impactradius-go.com/display-ad/15155-1246754" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1246754/15155" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Press the**Accept** button for the license terms.
6. The**Keep personal files and apps** option will probably be set by default at the ready-to-install stage. However, you click**Change what to keep** to make sure the**Keep personal files and apps** option is selected.  
![The Keep personal files and apps radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/keep-personal-files-option.jpg)
7. Then select**Next** to proceed to the last step.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
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
<li><a href="https://youtube-blog.techidaily.com/024-approved-optimizing-engagement-using-cards-and-annotations/"><u>[New] 2024 Approved  Optimizing Engagement  Using Cards and Annotations</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-front-seat-recreation-10-non-athletic-delights/"><u>[New] Front Seat Recreation  10 Non-Athletic Delights</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-navigating-through-io-screenshot-functionality/"><u>[New] Navigating Through IO Screenshot Functionality</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-easy-guide-to-instagram-post-duplication/"><u>[Updated] In 2024, Easy Guide to Instagram Post Duplication</u></a></li>
<li><a href="https://program-issues.techidaily.com/easy-fixes-for-common-hp-screen-issues-step-by-step-guide-to-restoring-display-functionality/"><u>Easy Fixes for Common HP Screen Issues - Step-by-Step Guide to Restoring Display Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/expedite-data-access-seamless-entry-into-windows-11-disk-editor/"><u>Expedite Data Access: Seamless Entry Into Windows 11 Disk Editor</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-advice-how-to-reset-win11-search-default-configurations/"><u>Expert Advice: How to Reset Win11 Search Default Configurations</u></a></li>
<li><a href="https://windows11.techidaily.com/fast-track-to-enabling-telnet-in-win11-pcs/"><u>Fast Track to Enabling Telnet in Win11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-roblox-on-screen-stop-issues-on-windows-systems/"><u>Fixing Roblox On-Screen Stop Issues on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-turn-off-windows-from-starting-spotify/"><u>Guide to Turn Off Windows From Starting Spotify</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-a-portable-software-menu-to-windows-10-and-11/"><u>How to Add a Portable Software Menu to Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-copy-and-paste-not-working-in-windows-11/"><u>How to Fix Copy and Paste Not Working in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-irq-problems-with-your-soundcard-on-windows/"><u>How to Fix IRQ Problems With Your Soundcard on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-rectify-unmovable-scrolling-in-excel-windows/"><u>How to Rectify Unmovable Scrolling in Excel (Windows)</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-6-to-other-iphone-11-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 6 To Other iPhone 11 devices? | Dr.fone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/hp-m404n-laserjet-drivers-fresh-download-and-update-options/"><u>HP M404n LaserJet Drivers: Fresh Download & Update Options</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-discover-the-best-video-capture-tools-for-windows-users/"><u>In 2024, Discover the Best Video Capture Tools for Windows Users</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/in-2024-essential-top-5-iphone-podcast-apps/"><u>In 2024, Essential Top 5 iPhone Podcast Apps</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-and-where-to-find-a-shiny-stone-pokemon-for-honor-magic-5-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How and Where to Find a Shiny Stone Pokémon For Honor Magic 5 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launching-windows-11s-snip-and-sketch-shortcut/"><u>Launching Windows 11'S Snip & Sketch Shortcut</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-disconnected-spotify-sessions-in-w10w11/"><u>Mending Disconnected Spotify Sessions in W10/W11</u></a></li>
<li><a href="https://windows11.techidaily.com/modify-your-windows-personalized-spotlight-image/"><u>Modify Your Windows Personalized Spotlight Image</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-and-understanding-how-to-use-imessage-on-your-computer/"><u>Navigating and Understanding How to Use iMessage on Your Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-windows-11-registry-for-obscured-themes/"><u>Navigating the Windows 11 Registry for Obscured Themes</u></a></li>
<li><a href="https://windows11.techidaily.com/peering-into-major-complaints-about-windows-11-launch/"><u>Peering Into Major Complaints About Windows 11 Launch</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/perfecting-screenshots-editing-vids-vertically-on-fcpx-for-2024/"><u>Perfecting Screenshots  Editing Vids Vertically on FCPX for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/pioneering-retro-upgrades-atlasos-transformation/"><u>Pioneering Retro Upgrades: AtlasOS Transformation</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-recovery-reviving-a-vanished-windows-update/"><u>Quick Recovery: Reviving a Vanished Windows Update</u></a></li>
<li><a href="https://windows11.techidaily.com/recover-lost-audio-output-in-non-responsive-os/"><u>Recover Lost Audio Output in Non-Responsive OS</u></a></li>
<li><a href="https://windows11.techidaily.com/reversing-game-launch-hurdles-with-epic-logins/"><u>Reversing Game Launch Hurdles with Epic Logins</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-browsing-at-fingertips-activating-gestures-in-microsoft-edge-win-11-edition/"><u>Seamless Browsing at Fingertips: Activating Gestures in Microsoft Edge, Win 11 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-the-mystery-of-error-0x0000004e-on-windows/"><u>Solving the Mystery of Error 0X0000004E on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/spotting-the-green-light-and-red-alert-windows-login-status/"><u>Spotting the Green Light & Red Alert: Windows Login Status</u></a></li>
<li><a href="https://windows11.techidaily.com/stopping-missteps-in-mouse-travel-with-simple-fixes/"><u>Stopping Missteps in Mouse Travel with Simple Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-voice-input-in-windows-11-with-shortcuts-guide/"><u>Streamlining Voice Input in Windows 11 with Shortcuts Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-your-workspace-integrating-directories-into-taskbar-menu/"><u>Streamlining Your Workspace: Integrating Directories Into Taskbar Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/tackle-non-working-shift-with-simple-tweaks/"><u>Tackle Non-Working Shift with Simple Tweaks</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-your-first-load-webpage-on-win11/"><u>Tailoring Your First Load Webpage on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-winning-package-tool-for-you-a-choco-vs-wm-quest/"><u>The Winning Package Tool for You: A Choco VS. WM Quest</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-for-resolving-error-0x8024002e-during-windows-updates/"><u>Ultimate Guide for Resolving Error 0X8024002E During Windows Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-against-windowss-notorious-pink-screens/"><u>Winning Against Windows's Notorious Pink Screens</u></a></li>
<li><a href="https://howto.techidaily.com/xiaomi-redmi-note-13-proplus-5g-camera-not-working-unexpected-error-fix-it-now-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Xiaomi Redmi Note 13 Pro+ 5G Camera Not Working Unexpected Error? Fix It Now | Dr.fone</u></a></li>
</ul></div>
