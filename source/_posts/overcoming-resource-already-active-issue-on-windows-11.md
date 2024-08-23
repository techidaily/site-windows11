---
title: Overcoming Resource Already Active Issue on Windows 11
date: 2024-08-22T21:39:41.527Z
updated: 2024-08-23T21:39:41.527Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Resource Already Active Issue on Windows 11
excerpt: This Article Describes Overcoming Resource Already Active Issue on Windows 11
keywords: Win11 Resource Fix,Overcome Win11 Problems,Resolve Win11 Errors,Stop Win11 Issues,Solve Windows 11 Hangs,Unblock Win11 Status,Clear Win11 Errors
thumbnail: https://thmb.techidaily.com/11bd493dd0576b5128c521759756af9ef0469248903e298828d7682c78b82237.jpg
---

## Overcoming Resource Already Active Issue on Windows 11

 Users have reported “the requested resource in use” error message pops up on their PCs when trying to copy or move files from mobile devices to their Windows PCs. That error message’s heading also says, “error copying file or folder.” As a result, users can’t copy the files they need to.

 Here is how you can fix the “requested resource is in use” error on a Windows 10 or 11 PC.

## 1\. Check if the File Is Already in Use

![The End task option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-end-task-option.jpg)

 The “requested resource is in use” error message hints that the file (resource) you’re trying to copy is already in use. Thus, the copy operation cannot be completed because something else is using the file or folder. So, you might need to close some background processes to address this issue.

 First, move your mouse’s cursor over the File Explorer taskbar icon to see if there are any windows for active file operations. Cancel any active file operations you see. Then try copying the file again.

 If that doesn’t work, go into Task Manager and close superfluous third-party app background processes. Our guide to [fixing too many background processes on Windows](https://www.makeuseof.com/windows-pc-too-many-background-processes/) provides further instructions for how you can do that.

## 2\. Disable File Explorer’s Preview Pane

 Many users have fixed the “requested resource is in use” error by disabling File Explorer’s preview pane. That preview pane can hinder the file copy operation. You can disable File Explorer’s preview pane in Windows 11 as follows:

1. Press the **Win + E** key combination to launch File Explorer.
2. Then click the **View** menu button.
3. Select the **Show** submenu.
4. Deselect the **Preview pane** option.  
![The Preview pane option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/preview-pane-option.jpg)
5. Then try moving or copying your files again.

 The layout in Windows 10 File Explorer is a little different. To disable preview panes in that file manager, you’ll need to click the **View** tab. Then click **Preview pane** to deselect that option.

![The View tab in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-view-tab.jpg)

 Note that just disabling the preview pane might not always be enough. If that doesn’t work, try turning off the icon file view. To do so in Windows 11 File Explorer, click **View** and select the **List** or **Details view** option. You can select the same options on the **View** tab in Windows 10 File Explorer.

## 3\. Run a Malware Scan

 If the previous two resolutions don’t work for you, it’s probably the case that malware is causing the “requested resource is in use” error on your PC. SmartService is a trojan known to cause the “required source is in use” error. So, try running an antivirus scan with third-party software or Windows Security to kill SmartService. You can run an antivirus scan with Windows Security like this:

1. Double-click Windows Security’s icon in the system tray (the shield).
2. Click **Virus & threat protection** \> **Scan options** to access the Microsoft Defender antivirus tool.  
![The Scan options navigation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-scan-options.jpg)
3. Select the **Full scan** setting.
4. Click **Scan now** to initiate the malware scanning.  
![The Scan now button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-full-scan-radio-button.jpg)
5. Wait for the scanning to finish and select **Start actions** to remove detected malware.

 If you find Microsoft Defender is disabled and cannot turn it on, that’s a surefire sign the SmartService malware has infected your PC. SmartService is a rootkit trojan that blocks users from utilizing antivirus tools. That malware can also block the installation of some antivirus apps. In this case, the “requested resource in use” error can also occur when you try to run security apps.

 To circumvent such a block, try running a Windows Security or third-party app antivirus scan in safe mode instead. Our guide to [booting into safe mode on Windows](https://www.makeuseof.com/windows-11-boot-safe-mode/) includes a few different methods for entering that troubleshooting mode. Select to enable safe mode with networking.

![windows 11 startup settings safe mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-startup-settings-safe-mode.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<span id="1997795">
					<video width="250" height="250" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/23621-1997795">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:250px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fproteahair.pxf.io%2Fc%2F5597632%2F1997795%2F23621'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997795/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Disable Any Unknown Programs in Task Manager

 You might be able to disable a SmartService trojan from starting with Windows via Task Manager’s Startup tab. Look for and disable any suspicious programs listed on the **Startup** tab as follows:

1. Right-click a space on the taskbar to select a **Task Manager** context menu shortcut.
2. Next, click **Startup** to view that tab.
3. Look for any programs you don’t recognize on the **Startup** tab.
4. If you see anything suspicious, select that item and click the **Disable** button.  
![The Disable button on Task Manager's Startup tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-button.jpg)
5. Then restart your PC to see if the issue persists.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
## 5\. Uninstall Any Suspicious-Looking Programs

 The SmartService trojan might also be listed within the Programs and Features Control Panel applet for uninstalling software. If you notice suspicious-looking software in Programs and Features, you can also select to uninstall it from there.

 Try uninstalling suspicious programs like this:

1. Bring up the Windows uninstaller tool with a method in our guide to opening Programs and Features.
2. Look through the list of installed software to see if there’s any suspicious-looking program there. Look for a program you can’t recall installing with an unknown publisher title.  
![The Uninstall option in Programs and Features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-uninstall-option4.jpg)
3. Right-click on the suspected SmartService malware and select **Uninstall**.
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->
4. If you can’t uninstall the suspicious software, restart Windows in safe mode. Then try removing the same suspicious item via Programs and Features in safe mode.

 Also, clear temporary data after uninstalling SmartService to ensure the malware can’t re-emerge. To do so, you’ll need to clear out the Temp folder. This article about [deleting temporary files](https://www.makeuseof.com/windows-11-delete-temporary-files/) includes alternative methods for clearing data in the Temp folder.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
## 6\. Perform a Factory Reset

 If the “requested resource is in use” error remains unresolved after trying all the potential resolutions above, performing a factory reset is the last resort. A factory reset will remove all programs not pre-installed with Windows and restore your PC to its default configuration. Applying this potential fix will likely eradicate malware causing the “requested resource is in use” error.

 The "Reset this PC" utility lets you factory reset Windows 11 and 10\. That tool includes an option you can select to stop the reset deleting user files. Our [how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) guide provides detailed guidelines for resetting the platform.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-keep-my-files-option.jpg)

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get the “Requested Resource Is in Use” Error Sorted on Windows

 The potential solutions covered here are widely confirmed to resolve the “requested resource is in use” error. If it’s not caused by malware, disabling Explorer’s preview pane, as covered in resolution two, will usually fix the issue. Users confirm running an antivirus scan in safe mode (solution three) can fix the “required resource is in use” error when caused by malware.

 Here is how you can fix the “requested resource is in use” error on a Windows 10 or 11 PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-content.techidaily.com/new-beat-to-freedom-online-fb-music-downloads-for-2024/"><u>[New] Beat to Freedom  Online FB Music Downloads for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-advanced-tips-for-adding-effects-on-digital-videos/"><u>[Updated] 2024 Approved  Advanced Tips for Adding Effects on Digital Videos</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-audio-addition-for-snapchat-videos/"><u>[Updated] 2024 Approved  Audio Addition for Snapchat Videos</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-exploring-the-nuances-of-audio-overlap-crossfade/"><u>[Updated] Exploring the Nuances of Audio Overlap (Crossfade)</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-the-ultimate-battle-for-ephemeral-content-youtube-shorts-versus-tiktok/"><u>[Updated] In 2024, The Ultimate Battle for Ephemeral Content  YouTube Shorts Versus TikTok</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/efficient-methods-for-renaming-users-in-google-meet-for-2024/"><u>Efficient Methods for Renaming Users in Google Meet for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-drawing-software-like-procreate-for-windows/"><u>Essential Drawing Software Like Procreate, For Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-for-steams-persistent-error-code-e84/"><u>Expert Tips for Steam's Persistent Error Code E84</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-check-your-public-ip-address-using-command-prompt-in-windows-1110/"><u>How to Check Your Public IP Address Using Command Prompt in Windows 11/10</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-zte-axon-40-lite-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my ZTE Axon 40 Lite | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fake-gps-on-oneplus-ace-3-for-mobile-legends-drfone-by-drfone-virtual-android/"><u>How To Fake GPS On OnePlus Ace 3 For Mobile Legends? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-error-495-while-downloadupdating-android-apps-on-vivo-y78plus-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Error 495 While Download/Updating Android Apps On Vivo Y78+ | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-spy-on-text-messages-from-computer-and-oppo-a78-drfone-by-drfone-virtual-android/"><u>How to Spy on Text Messages from Computer & Oppo A78 | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-infinix-zero-5g-2023-turbo-phone-without-pin-by-drfone-android/"><u>How to Unlock Infinix Zero 5G 2023 Turbo Phone without PIN</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-update-iphone-se-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update iPhone SE without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-fake-snapchat-location-without-jailbreak-on-oneplus-ace-3-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fake Snapchat Location without Jailbreak On OnePlus Ace 3 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-art-of-logging-into-windows-11-with-password-instead-of-pin/"><u>Master the Art of Logging Into Windows 11 with Password Instead of PIN</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-your-files-adding-movecopy-to-windows-context-menu/"><u>Mastering Your Files: Adding 'Move'/'Copy' To Windows Context Menu</u></a></li>
<li><a href="https://extra-hints.techidaily.com/melody-of-affection-greatest-love-songs-to-sweeten-a-proposal/"><u>Melody of Affection  Greatest Love Songs to Sweeten a Proposal</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-low-usb-support-error-in-windows/"><u>Overcoming Low USB Support Error in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-outdated-windows-password-a-guide/"><u>Overcoming Outdated Window's Password: A Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/pioneering-windows-interface-next-chapter-after-11/"><u>Pioneering Windows Interface: Next Chapter After 11</u></a></li>
<li><a href="https://windows11.techidaily.com/propel-your-teams-potential-a-complete-guide-to-microsoft-teams-error-resolution-in-win11/"><u>Propel Your Teams' Potential: A Complete Guide to Microsoft Teams Error Resolution in Win11</u></a></li>
<li><a href="https://fake-location.techidaily.com/read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-xiaomi-redmi-a2-drfone-by-drfone-virtual-android/"><u>Read This Guide to Find a Reliable Alternative to Fake GPS On Xiaomi Redmi A2 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstate-your-image-tiles-on-windows-11-quick-guide/"><u>Reinstate Your Image Tiles on Windows 11 – Quick Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/safe-sailing-in-the-sea-of-windows-11-upgrades-top-8/"><u>Safe Sailing in the Sea of Windows 11 Upgrades (Top 8)</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-winrar-data-transfers-addressing-checksum-mistakes/"><u>Securing WinRAR Data Transfers: Addressing Checksum Mistakes</u></a></li>
<li><a href="https://windows11.techidaily.com/speedy-acquisition-download-tips-from-microsofts-app-marketplace/"><u>Speedy Acquisition: Download Tips From Microsoft's App Marketplace</u></a></li>
<li><a href="https://windows11.techidaily.com/stay-unplugged-avoiding-abrupt-updates-on-windows-11/"><u>Stay Unplugged: Avoiding Abrupt Updates on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategic-use-of-powertoys-locksmith-for-files/"><u>Strategic Use of PowerToys Locksmith for Files</u></a></li>
<li><a href="https://windows11.techidaily.com/take-charge-of-your-workspace-filter-and-theme-mastery-in-the-windows-11-task-manager/"><u>Take Charge of Your Workspace: Filter and Theme Mastery in the Windows 11 Task Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essentials-of-using-microsoft-family-safety/"><u>The Essentials of Using Microsoft Family Safety</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-enhanced-windows-11-taskbar/"><u>Unlocking Enhanced Windows 11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/unshackling-power-the-fourfold-path-to-user-deactivation-in-windows-11/"><u>Unshackling Power: The Fourfold Path to User Deactivation in Windows 11</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/unveiling-the-mobvoi-ticwatch-pro-4g-the-ultimate-smarthome-companion-with-unlimited-internet-connection/"><u>Unveiling the Mobvoi Ticwatch Pro 4G: The Ultimate Smarthome Companion with Unlimited Internet Connection</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-vintage-conversion-the-98-experience/"><u>Windows 11 Vintage Conversion: The ’98 Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-based-guide-recognizing-your-cpus-generational-status-8-ways/"><u>Windows-Based Guide: Recognizing Your CPU’s Generational Status (8 Ways)</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>