---
title: Remedying Phantom Device Error in Windows 11
date: 2024-09-05T02:15:47.221Z
updated: 2024-09-06T02:15:47.221Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Remedying Phantom Device Error in Windows 11
excerpt: This Article Describes Remedying Phantom Device Error in Windows 11
keywords: WinError Fixing Guide,W11 Ghost Issue Solution,Resolve Windows Devices Error,Correcting Unseen Device Error,Phantom Error in Windows XP/W11,Troubleshoot Phantom Device,Windows 11 Ghost Device Fix
thumbnail: https://thmb.techidaily.com/9f78d218ca56a8e977ac9c156c6d3df029b653f49542887406f9b6531aa186a8.jpg
---

## Remedying Phantom Device Error in Windows 11

 Many users partition their hard drives or utilize external storage devices with their PCs. However, such drives become inaccessible when the “A device which does not exist was specified” error arises. Users have reported seeing this strange error message when they try to open connected external storage devices or drive partitions inside Windows File Explorer.

 That error is most unwelcome since it means users can’t open whatever drives it arises for. Consequently, they can’t access files on affected drives. This is how you can fix the “device which does not exist was specified” error in Windows 10 and 11.

## 1\. Plug the Affected Device Into a Different USB Slot

 If this error is affecting an external storage device, try reconnecting the USB drive. There might be an issue with the port you’ve connected the drive with. Plug the USB drive into a different port to see if the same error occurs.

 If you need to resolve this error for an internal drive, check the drive’s internal connections. To do that, you’ll need to open the case for a desktop PC. Then make sure none of the drive’s connection cables are in any way loose.

## 2\. Run the SFC Tool

 Users have confirmed the System File Checker tool can resolve this drive error. That highlights system file corruption can cause this issue, which an SFC scan will likely resolve. Our guide to[running a System File Checker scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) tells you how to execute the SFC command in Windows.

![The sfc /scannow](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/sfc-scannow.jpg)

## 3\. Run a Check Disk Scan for the Drive

 You might need to fix the “device which does not exist was specified” error because your drive has some bad sectors. Running a CHKDSK (Check Disk) scan command is a potential remedy for bad drive sectors. This is how you can run the Windows Check Disk tool from the Command Prompt:

1. Open the search tool by simultaneously pressing the**Windows** logo +**S** keys.
2. Enter the search phrase**cmd** inside the text box.
3. Click**Run as administrator** to start Command Prompt with elevated permissions.
4. Then execute the Check Disk scan by inputting this command:  
`chkdsk X: /f /r`  
![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/chkdsk-scan.jpg)
5. Press**Enter** to initiate the scan.

 You’ll need to replace X in the above command with the actual letter of the affected drive you need to scan. For example, the command for a drive labeled D would be:

`chkdsk D: /f /r`

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2052060/7443" target="_top" id="2052060">
  <img src="//a.impactradius-go.com/display-ad/7443-2052060" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2052060/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Try Changing the Drive’s Letter

 Changing the affected drive’s letter is a potential fix that users have confirmed to work. You can change the drive’s letter with the Disk Management tool like this:

1. If you need to fix this issue for an external drive, connect that storage device to your PC.
2. Open Disk Management by right-clicking**Start** and selecting the shortcut for that tool.
3. Right-click the affected drive and select**Change Drive Letter and Paths** .  
![The Change Drive Letter and Paths option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-drive-letter-paths.jpg)
4. Press the**Change** button.  
![The Change Drive Letter window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-drive-letter-window.jpg)
5. Click the drop-down menu for the**Assign the following drive lette** r option.  
<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1061528/11832" target="_top" id="1061528">
  <img src="//a.impactradius-go.com/display-ad/11832-1061528" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1061528/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Assign the following drive letter option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/assign-the-following-drive-letter.jpg)
6. Select a drive letter that you’ve never used.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925549/19272" target="_top" id="1925549">
  <img src="//a.impactradius-go.com/display-ad/19272-1925549" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925549/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Click**OK** on the Change Drive Letter or Path window.
8. Select**Yes** on the Disk Management confirmation dialog.

## 5\. Rescan a Drive

 Disk Management includes a**Rescan Disk** option for troubleshooting drives. That option detects disk changes and updates drive info accordingly when selected. So, rescanning the disk is a viable troubleshooting method for resolving this “device which does not exist” error. This is how you can rescan a drive:

1. Plug the drive into your PC if necessary.
2. Bring up the Disk Management tool.
3. Click the drive for which the error occurs in Disk Management.
4. Then click the**Action** menu.  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/properties-option2.jpg)
5. Select**Rescan Disks** on the menu.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975841/19272" target="_top" id="1975841">
  <img src="//a.impactradius-go.com/display-ad/19272-1975841" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975841/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Select the Full Control Option for a Drive Location

 The “device which does not exist” error can arise because of restricted drive permissions. In that scenario, users need to select a**Full control** permission option for their drives. These are the steps for selecting the**Full control** permission setting:

1. First, activate the file management tool with Explorer’s**Windows** logo +**E** hotkey.
2. Then click**This PC** in Explorer’s left sidebar.
3. Right-click the affected drive to select**Properties** .  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/properties-option2.jpg)
4. Click the drive’s**Security** tab.
<!-- affiliate ads begin -->
<span id="1982485">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982485.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982485">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982485.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982485%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982485/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. If the**Full control** option isn’t ticked, click the**Edit** button.
6. Select the**Allow** box for the**Full control** option.  
![The Full control option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/full-control-checkbox.jpg)
7. Click**Apply** \>**OK** on the drive’s permissions window.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997722/19272" target="_top" id="1997722">
  <img src="//a.impactradius-go.com/display-ad/19272-1997722" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997722/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 7\. Reinstall the Affected Drive

 If you need to fix this issue for an external storage device, try reinstalling the affected drive. Doing so will reinstall the drivers for the affected storage device. This is how you can reinstall the drive:

Insert the affected drive into one of your PC’s USB ports.

1. Click**Start** with the right mouse button to select a**Device Manager** shortcut.
2. Double-click**Disk drives** in Device Manager.
3. Right-click your drive and select**Uninstall device** .  
![The Uninstall device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/uninstall-device2.jpg)
4. Then select the**Uninstall** option on the dialog box prompt.  
![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/uninstall-option3.jpg)
5. Disconnect the drive plugged into the PC.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037351/7443" target="_top" id="2037351">
  <img src="//a.impactradius-go.com/display-ad/7443-2037351" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037351/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Plug the drive back into the computer to reinstall its driver.

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1828647/21290" target="_top" id="1828647">
  <img src="//a.impactradius-go.com/display-ad/21290-1828647" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://versadesk.pxf.io/i/5597632/1828647/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 8\. Update Your Motherboard’s Chipset Driver

 It might be necessary for some users to update motherboard drivers to fix this issue. To do so manually, you’ll need the motherboard model and manufacturer details. You can check those details as follows:

1. Open the Windows search box, and type a**System Information** keyword there.
2. Click**System Information** to view that app’s window.
3. Note down the**BaseBand Product** and**BaseBand Manufacturer** details.  
![Baseboard specs in System Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/baseboard-specs.jpg)
4. [Open the Command Prompt](https://www.makeuseof.com/windows-11-open-command-prompt/) if the System Information app doesn’t include a serial number for the motherboard.
5. Execute this baseboard command:  
`wmic baseboard get product,Manufacturer,version,serialnumber`  
![The baseboard command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/baseboard-command.jpg)
6. Copy and paste the serial number for the motherboard shown within the Command Prompt into Notepad or another text editor.

 Then open the download section of your motherboard manufacturer’s website. Select your motherboard model and download its latest chipset driver from there. You can install the new driver for your motherboard with the downloaded driver (setup.exe) package file.

 The driver package might be included within a ZIP archive, which you’ll need to extract as outlined within this guide to[unzipping files in Windows](https://www.makeuseof.com/unzip-files-windows-10/) .

<!-- affiliate ads begin -->
<span id="1977032">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977032.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977032">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977032.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977032%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977032/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Access Your Drive Again on Windows

 Those potential solutions will probably fix the “device which does not exist” drive error for most users. If they’re not enough, there could be an issue with your PC’s motherboard headers. In that case, consider taking your PC to a reputable repair service to resolve such an issue.

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
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-the-modern-gamers-guide-understanding-the-latest-on-bandicam/"><u>2024 Approved  The Modern Gamer's Guide  Understanding the Latest on Bandicam</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-airplane-mode-turn-off-gps-location-on-oneplus-12r-drfone-by-drfone-virtual-android/"><u>Does Airplane Mode Turn off GPS Location On OnePlus 12R? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-no-sound-device-error-in-windows-os/"><u>Fix No Sound Device Error in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-icue-how-to-resolve-no-device-found-error/"><u>Fixing ICUE: How to Resolve 'No Device Found' Error</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-cut-spotlight-wallpaper-icon-on-windows-11s-desk/"><u>Guide to Cut Spotlight Wallpaper Icon on Windows 11'S Desk</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-flash-dead-nokia-c300-safely-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Flash Dead Nokia C300 Safely | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-jailbreak-icloud-locked-iphone-14-pro-by-drfone-ios/"><u>How to jailbreak iCloud locked iPhone 14 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-jumpstart-your-qbittorrent-in-sluggish-state-windows/"><u>How to Jumpstart Your qBittorrent in Sluggish State (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-rescue-your-windows-11-from-hypervisor-bsos-blues/"><u>How to Rescue Your Windows 11 From Hypervisor BSOS Blues</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-text-messages-from-honor-v-purse-to-new-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Text Messages from Honor V Purse to New Phone | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-samsung-galaxy-m34-5g-drfone-by-drfone-android/"><u>How To Use Allshare Cast To Turn On Screen Mirroring On Samsung Galaxy M34 5G | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-crafting-engaging-bio-stories-a-guide-to-stand-out-on-fb/"><u>In 2024, Crafting Engaging Bio Stories – A Guide to Stand Out on FB</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-inspire-yourself-a-list-of-10-empowering-movie-experiences/"><u>In 2024, Inspire Yourself  A List of 10 Empowering Movie Experiences</u></a></li>
<li><a href="https://extra-hints.techidaily.com/integrate-xps-essential-movie-making-features/"><u>Integrate XP's Essential Movie Making Features</u></a></li>
<li><a href="https://extra-hints.techidaily.com/masters-choice-10-leading-photo-backdrop-swap-tools/"><u>Master's Choice  10 Leading Photo Backdrop Swap Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/masterful-strategies-for-resolving-zerox-typing-flaw-in-windows-11/"><u>Masterful Strategies for Resolving Zerox Typing Flaw in Windows 11</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-best-liked-platforms-to-access-compilation-of-guitar-chord-diagrams-and-visual-themes-for-2024/"><u>New Best-Liked Platforms to Access Compilation of Guitar Chord Diagrams & Visual Themes for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/overcome-highlighting-obstacles-in-windows-pdf-files/"><u>Overcome Highlighting Obstacles in Windows' PDF Files</u></a></li>
<li><a href="https://windows11.techidaily.com/prime-virtual-machines-designed-for-windows-11-devices/"><u>Prime Virtual Machines Designed for Windows 11 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-tips-overcoming-windows-winerror-messages/"><u>Quick Tips: Overcoming Windows WinError Messages</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-malfunctioning-windows-alt-codes/"><u>Rectifying Malfunctioning Windows ALT Codes</u></a></li>
<li><a href="https://windows11.techidaily.com/restore-bluetooth-connection-fixing-mice-on-windows-xpvista/"><u>Restore Bluetooth Connection: Fixing Mice on Windows XP/Vista</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-ccleaner-performance-in-win11/"><u>Reviving CCleaner Performance in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/rog-ally-vs-asus-who-wins-the-steam-deck-war/"><u>ROG Ally Vs. ASUS: Who Wins the Steam Deck War?</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/seamless-worldwide-engagement-with-chatgpt/"><u>Seamless Worldwide Engagement with ChatGPT</u></a></li>
<li><a href="https://windows11.techidaily.com/separate-and-align-win-11-taskbar-items/"><u>Separate and Align Win 11 Taskbar Items</u></a></li>
<li><a href="https://windows11.techidaily.com/speedy-deactivation-of-windows-11-notifications/"><u>Speedy Deactivation of Windows 11 Notifications</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-nvidia-related-windows-connections/"><u>Tackling Nvidia-Related Windows Connections</u></a></li>
<li><a href="https://windows11.techidaily.com/transforming-taskbar-functionality-6-essential-upgrades-for-windows-11/"><u>Transforming Taskbar Functionality: 6 Essential Upgrades for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-steps-for-non-responsive-windows-11-spotify/"><u>Troubleshooting Steps for Non-Responsive Windows 11 Spotify</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-disabled-lsa-security-signal/"><u>Troubleshooting Windows' Disabled LSA Security Signal</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-hidden-features-in-windows-snipping-tool-for-flawless-screen-shots/"><u>Unlock Hidden Features in Windows Snipping Tool for Flawless Screen Shots.</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-and-fixing-directdraw-errors-in-win1011-systems/"><u>Unraveling and Fixing DirectDraw Errors in WIN10/11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-installation-conundrums-a-windows-guide/"><u>Unraveling Installation Conundrums: A Windows Guide</u></a></li>
<li><a href="https://change-location.techidaily.com/ways-to-trade-pokemon-go-from-far-away-on-vivo-x-flip-drfone-by-drfone-virtual-android/"><u>Ways to trade pokemon go from far away On Vivo X Flip? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-guide-forcibly-remove-printers/"><u>Win11 Guide: Forcibly Remove Printers</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-uninstalling-made-easy-crafting-custom-shortcuts/"><u>Windows Uninstalling Made Easy: Crafting Custom Shortcuts</u></a></li>
</ul></div>
