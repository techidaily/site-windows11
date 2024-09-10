---
title: "Showing D: Drive Directories in Explorer View"
date: 2024-09-09T12:11:57.191Z
updated: 2024-09-10T12:11:57.191Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Showing D: Drive Directories in Explorer View"
excerpt: "This Article Describes Showing D: Drive Directories in Explorer View"
keywords: Drives Explorer Guide,Directory Display IE,Explore Drives Windows,File Explorer Showcase,Drives Listing Viewer,Directories in Explorer,Windows Drive Views
thumbnail: https://thmb.techidaily.com/acc4624304fa10f6661dcbd0f5aeeaf72266dc48176909da6153f980695e7df6.png
---

## Showing D: Drive Directories in Explorer View

 To access the D: drive, you normally have to open File Explorer, click on **This PC** in the Navigation pane, and expand the **Devices and drives** section. With a simple hack, you can add it to the Navigation pane so you can easily access it straight from there. It will require you to tweak the Windows Registry, but don’t worry; we'll show you an extremely easy way of going about it.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115925/19272" target="_top" id="2115925">
  <img src="//a.impactradius-go.com/display-ad/19272-2115925" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115925/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Before You Proceed…

 We are going to [create a Registry file](https://www.makeuseof.com/windows-registry-file-guide/) to add the D: drive to the Navigation Pane. This file will make changes to the Windows registry, and you need to be careful [not to mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/). A slip-up could make Windows unusable.

 Furthermore, we highly recommend that you learn how to [back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). That way, you have a way of returning it to the state it was in before you made any changes that broke it.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137203/26400" target="_top" id="2137203">
  <img src="//a.impactradius-go.com/display-ad/26400-2137203" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137203/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How Do I Add the D: Drive to the Navigation Pane in File Explorer?

 Start by pressing **Win + S** to bring up Windows Search. Then, type **notepad** in the Search box, and when Notepad shows up in the search results, click on it to launch it.

![The Notepad search result](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/notepad-search-result.png)

 Then copy and paste the below text into Notepad:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}]  
@="D: Drive"  
"System.IsPinnedToNamespaceTree"=dword:00000001  
"SortOrderIndex"=dword:00000050  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\DefaultIcon]  
@=hex(2):69,00,6d,00,61,00,67,00,65,00,72,00,65,00,73,00,2e,00,64,00,6c,00,6c,\  
  00,2c,00,2d,00,33,00,32,00,00,00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\InProcServer32]  
@=hex(2):43,00,3a,00,5c,00,57,00,49,00,4e,00,44,00,4f,00,57,00,53,00,5c,00,73,\  
  00,79,00,73,00,74,00,65,00,6d,00,33,00,32,00,5c,00,73,00,68,00,65,00,6c,00,\  
  6c,00,33,00,32,00,2e,00,64,00,6c,00,6c,00,00,00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\Instance]  
"CLSID"="{0E5AAE11-A475-4c5b-AB00-C66DE400274E}"  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\Instance\InitPropertyBag]  
"Attributes"=dword:00000011  
"TargetFolderPath"=hex(2):44,00,3a,00,5c,00,00,00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\ShellFolder]  
"FolderValueFlags"=dword:00000028  
"Attributes"=dword:f080004d  
  
[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\HideDesktopIcons\NewStartPanel]  
"{0525388b-89d9-4112-bf4d-2aaccb716a7f}"=dword:00000001  
  
[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace\{0525388b-89d9-4112-bf4d-2aaccb716a7f}]  
@="D: Drive"`

 Press **Ctrl + S**, name the file **add-d-drive-file-explorer.reg**, and then click **Save**. Don’t forget to add the REG file extension to let Windows know it’s working with a Registry file.

![saving a registry file in Notepad on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/save-reg-file-add-drive-nav-pane.jpg)

<!-- affiliate ads begin -->
<span id="1982462">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982462.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982462">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982462.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982462%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982462/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Next, double-click the Registry file you just created and click **Yes** on the UAC prompt. You’ll then be asked if you want to continue with the merge, so click **Yes**. Afterward, press **Win + E** to open File Explorer.

![the D drive showing in the bottom section of the Navigation pane on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/d-drive-nav-pane.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134228/18498" target="_top" id="2134228">
  <img src="//a.impactradius-go.com/display-ad/18498-2134228" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134228/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The D: drive should now be visible in the bottom part of the Navigation pane.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118314/7443" target="_top" id="2118314">
  <img src="//a.impactradius-go.com/display-ad/7443-2118314" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118314/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How Do I Remove the D: Drive From the Navigation Pane in File Explorer?

 To remove the D: drive from the navigation pane, open Notepad and then copy and paste the below text:

`Windows Registry Editor Version 5.00  
  
[-HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}][HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\HideDesktopIcons\NewStartPanel]  
"{0525388b-89d9-4112-bf4d-2aaccb716a7f}"=-  
  
[-HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace\{0525388b-89d9-4112-bf4d-2aaccb716a7f}]`

 Save the file as **remove-d-drive-file-explorer.reg**. Afterward, double-click the registry file and click **Yes** on the UAC prompt. When asked if you want to continue with the merge, click **Yes** again.

 Now the D: drive should be gone from the navigation pane in File Explorer.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134235/18498" target="_top" id="2134235">
  <img src="//a.impactradius-go.com/display-ad/18498-2134235" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134235/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Create an Easier Way to Access the D: Drive on Your Windows Computer

 With this guide, you will remove an extra step when accessing the D: drive on your Windows computer. Once you have created the registry files, adding and removing the D: drive from the Navigation pane will be easy. While the registry files are safe, don’t forget to create a backup of your Registry or a system restore point for good measure.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-tips.techidaily.com/024-approved-from-script-to-screenplay-expert-video-editing-insights/"><u>[New] 2024 Approved From Script to Screenplay Expert Video Editing Insights</u></a></li>
<li><a href="https://article-files.techidaily.com/new-2024-approved-mastering-podcast-writing-tips-and-free-template-samples/"><u>[New] 2024 Approved Mastering Podcast Writing Tips & Free Template Samples</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-crafting-your-virtual-identity-the-metaverse-simplified/"><u>[Updated] Crafting Your Virtual Identity - The Metaverse Simplified</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-exploring-the-world-of-digital-color-grading/"><u>[Updated] Exploring the World of Digital Color Grading</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-how-do-beginners-make-a-cool-video-for-youtube-on-mac/"><u>[Updated] In 2024, How Do Beginners Make a Cool Video for YouTube on Mac</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-instagram-intonations-choosing-the-right-notes-for-your-snap/"><u>[Updated] Instagram Intonations Choosing the Right Notes for Your Snap</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-transition-tactics-in-audio-leveraging-adobes-fading-effects-for-2024/"><u>[Updated] Transition Tactics in Audio Leveraging Adobe’s Fading Effects for 2024</u></a></li>
<li><a href="https://win-able.techidaily.com/comprehensive-assessment-of-the-lenovo-yoga-a940-laptop/"><u>Comprehensive Assessment of the Lenovo Yoga A940 Laptop</u></a></li>
<li><a href="https://extra-information.techidaily.com/comprehensive-srt-education-and-resources/"><u>Comprehensive SRT Education and Resources</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/engaging-excellence-best-story-filter-compilation/"><u>Engaging Excellence Best Story Filter Compilation</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-flawed-setups-a-guide-to-windo-package-fixing/"><u>Fixing Flawed Setups: A Guide to Windo Package Fixing</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-non-responsive-nvidia-control-panel-in-w11/"><u>Fixing Non-Responsive NVidia Control Panel in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-the-random-selection-of-default-windows-printer/"><u>Fixing the Random Selection of Default Windows Printer</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/full-guide-to-catch-100-iv-pokemon-using-a-map-on-htc-u23-drfone-by-drfone-virtual-android/"><u>Full Guide to Catch 100 IV Pokémon Using a Map On HTC U23 | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-delete-icloud-account-on-apple-iphone-13-pro-without-password-by-drfone-ios/"><u>How to Delete iCloud Account On Apple iPhone 13 Pro without Password?</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-remove-activation-lock-on-the-apple-iphone-xs-max-without-previous-owner-by-drfone-ios/"><u>How to Remove Activation Lock On the Apple iPhone XS Max Without Previous Owner?</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-tackle-windows-no-write-file-saving-problems/"><u>How to Tackle Windows No Write File Saving Problems</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-oneplus-12-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On OnePlus 12 | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-apple-id-is-greyed-out-from-iphone-xr-how-to-bypass-by-drfone-ios/"><u>In 2024, Apple ID is Greyed Out From iPhone XR How to Bypass?</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-seamless-live-broadcasting-on-facebook-a-simple-guide/"><u>In 2024, Seamless Live Broadcasting on Facebook A Simple Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/indispensable-items-on-the-agenda-prior-to-os-clean-slate/"><u>Indispensable Items on the Agenda Prior to OS Clean Slate</u></a></li>
<li><a href="https://windows11.techidaily.com/innovating-user-experience-ais-role-in-windows-11/"><u>Innovating User Experience: AI's Role in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/is-the-antimalware-service-executable-hogging-your-memory-heres-how-to-turn-it-off/"><u>Is the Antimalware Service Executable Hogging Your Memory? Here's How to Turn It Off</u></a></li>
<li><a href="https://windows11.techidaily.com/keyboard-command-compendium-masterful-win11-narrator-use/"><u>Keyboard Command Compendium: Masterful Win11 Narrator Use</u></a></li>
<li><a href="https://windows11.techidaily.com/master-swift-keystrokes-using-powertoys/"><u>Master Swift Keystrokes Using PowerToys</u></a></li>
<li><a href="https://windows11.techidaily.com/missing-astra-pilot-in-windows-11-heres-what-you-need/"><u>Missing Astra Pilot in Windows 11? Here's What You Need</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-system-performance-metrics/"><u>Navigating Through System Performance Metrics</u></a></li>
<li><a href="https://windows11.techidaily.com/navigational-aids-shortcut-mastery-with-windows-narrator/"><u>Navigational Aids: Shortcut Mastery with Windows Narrator</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-disappearing-panes-top-strategies-in-the-world-of-windows-11/"><u>Overcoming Disappearing Panes: Top Strategies in the World of Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-11-microsoft-store-hurdles/"><u>Overcoming Windows 11 Microsoft Store Hurdles</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-music-from-realme-c55-by-fonelab-android-recover-music/"><u>Possible solutions to restore deleted music from Realme C55</u></a></li>
<li><a href="https://windows11.techidaily.com/preserve-your-tailored-powertoys-environment-at-new-devices/"><u>Preserve Your Tailored PowerToys Environment at New Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-conflicts-easy-access-to-your-printer/"><u>Resolving Conflicts: Easy Access to Your Printer</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-error-0xc0000001-a-step-by-step-guide/"><u>Resolving Windows Error 0xC0000001: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/retrieving-hidden-pin-after-system-error-on-windows-11/"><u>Retrieving Hidden PIN After System Error on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/simplified-tracking-of-recently-active-windows-items/"><u>Simplified Tracking of Recently Active Windows Items</u></a></li>
<li><a href="https://windows11.techidaily.com/steer-clear-of-stuck-startup-screen-lotr-style/"><u>Steer Clear of Stuck Startup Screen, LOTR Style</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-to-unleash-windows-11-action-center-mixing/"><u>Step-by-Step to Unleash Windows 11 Action Center Mixing</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-if-windows-ignores-or-cannot-find-powershell-command/"><u>Steps if Windows Ignores or Cannot Find PowerShell Command</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-partition-management-in-windows-os/"><u>Streamlining Partition Management in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-the-printer-busy-state-in-win11/"><u>Taming the Printer Busy State in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-importance-of-microsofts-family-safety-in-todays-world/"><u>The Importance of Microsoft's Family Safety in Today’s World</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-procedure-for-restoring-icons-on-windows-11s-search-bar/"><u>The Procedure for Restoring Icons on Windows 11'S Search Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/transition-without-trouble-moving-from-virtualbox-62-to-70-windows-11-edition/"><u>Transition Without Trouble: Moving From VirtualBox 6.2 to 7.0, Windows 11 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/trimming-down-onedrive-icon-from-the-file-explorer-palette/"><u>Trimming Down OneDrive Icon From the File Explorer Palette</u></a></li>
<li><a href="https://windows11.techidaily.com/triumph-over-trapped-windows-update-5-effective-fixes/"><u>Triumph Over Trapped Windows Update: 5 Effective Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-guide-solving-virtualboxs-usb-error-on-windows-os/"><u>Troubleshooting Guide: Solving VirtualBox's 'USB Error' On Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-unretrievable-graphics-settings-via-geforce-experience-windows-11/"><u>Troubleshooting Unretrievable Graphics Settings via GeForce Experience, Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-10-resolving-error-0x80042306-with-system-restore/"><u>Troubleshooting Windows 10: Resolving Error 0X80042306 with System Restore</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-the-potential-for-in-depth-storage-analysis-with-diskusage-on-windows/"><u>Unleashing the Potential for In-Depth Storage Analysis with DiskUsage on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-winning-strategies-in-old-chessboard-manager/"><u>Unlocking Winning Strategies in Old Chessboard Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/unwanted-file-explorer-activation-stopped/"><u>Unwanted File Explorer Activation Stopped</u></a></li>
<li><a href="https://windows11.techidaily.com/vmstart-errors-in-win11-try-these-top-7-solutions-vmware/"><u>VMstart Errors in Win11? Try These Top 7 Solutions, VMware</u></a></li>
<li><a href="https://windows11.techidaily.com/xbox-crash-reset-and-restart-to-fix-it/"><u>Xbox Crash? Reset and Restart to Fix It</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>