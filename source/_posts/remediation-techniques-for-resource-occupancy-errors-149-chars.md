---
title: Remediation Techniques for Resource Occupancy Errors (149 Chars)
date: 2024-07-11T21:42:47.864Z
updated: 2024-07-12T21:42:47.864Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Remediation Techniques for Resource Occupancy Errors (149 Chars)
excerpt: This Article Describes Remediation Techniques for Resource Occupancy Errors (149 Chars)
keywords: Resource Error Remedies,Resource Allocation Fixes,Optimization Strategies,Efficient Resource Use,Minimizing Occupancy Mistakes,Reducing Resource Overlaps,Effective Occupancy Correction
thumbnail: https://thmb.techidaily.com/f353031385ec13b27002aeb25b2433c7b7f2839e202aee43a31b71787185171a.jpg
---

## Remediation Techniques for Resource Occupancy Errors (149 Chars)

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

## 4\. Disable Any Unknown Programs in Task Manager

 You might be able to disable a SmartService trojan from starting with Windows via Task Manager’s Startup tab. Look for and disable any suspicious programs listed on the **Startup** tab as follows:

1. Right-click a space on the taskbar to select a **Task Manager** context menu shortcut.
2. Next, click **Startup** to view that tab.
3. Look for any programs you don’t recognize on the **Startup** tab.
4. If you see anything suspicious, select that item and click the **Disable** button.  
![The Disable button on Task Manager's Startup tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-button.jpg)
5. Then restart your PC to see if the issue persists.

## 5\. Uninstall Any Suspicious-Looking Programs

 The SmartService trojan might also be listed within the Programs and Features Control Panel applet for uninstalling software. If you notice suspicious-looking software in Programs and Features, you can also select to uninstall it from there.

 Try uninstalling suspicious programs like this:

1. Bring up the Windows uninstaller tool with a method in our guide to opening Programs and Features.
2. Look through the list of installed software to see if there’s any suspicious-looking program there. Look for a program you can’t recall installing with an unknown publisher title.  
![The Uninstall option in Programs and Features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-uninstall-option4.jpg)
3. Right-click on the suspected SmartService malware and select **Uninstall**.
4. If you can’t uninstall the suspicious software, restart Windows in safe mode. Then try removing the same suspicious item via Programs and Features in safe mode.

 Also, clear temporary data after uninstalling SmartService to ensure the malware can’t re-emerge. To do so, you’ll need to clear out the Temp folder. This article about [deleting temporary files](https://www.makeuseof.com/windows-11-delete-temporary-files/) includes alternative methods for clearing data in the Temp folder.

## 6\. Perform a Factory Reset

 If the “requested resource is in use” error remains unresolved after trying all the potential resolutions above, performing a factory reset is the last resort. A factory reset will remove all programs not pre-installed with Windows and restore your PC to its default configuration. Applying this potential fix will likely eradicate malware causing the “requested resource is in use” error.

 The "Reset this PC" utility lets you factory reset Windows 11 and 10\. That tool includes an option you can select to stop the reset deleting user files. Our [how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) guide provides detailed guidelines for resetting the platform.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-keep-my-files-option.jpg)

## Get the “Requested Resource Is in Use” Error Sorted on Windows

 The potential solutions covered here are widely confirmed to resolve the “requested resource is in use” error. If it’s not caused by malware, disabling Explorer’s preview pane, as covered in resolution two, will usually fix the issue. Users confirm running an antivirus scan in safe mode (solution three) can fix the “required resource is in use” error when caused by malware.

 Here is how you can fix the “requested resource is in use” error on a Windows 10 or 11 PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/win11-desktop-from-chaotic-to-customized-in-minutes/"><u>Win11 Desktop: From Chaotic to Customized, in Minutes</u></a></li>
<li><a href="https://windows11.techidaily.com/revive-the-disappearing-link-top-9-methods-for-win-11s-bluetooth-woes/"><u>Revive the Disappearing Link: Top 9 Methods for Win 11'S Bluetooth Woes</u></a></li>
<li><a href="https://windows11.techidaily.com/merge-your-world-connecting-android-and-windows-11-tablets/"><u>Merge Your World: Connecting Android and Windows 11 Tablets</u></a></li>
<li><a href="https://windows11.techidaily.com/make-file-management-simple-using-windows-autodelete-feature/"><u>Make File Management Simple: Using Windows' Autodelete Feature</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-highlight-prime-iphone-gif-apps-to-try/"><u>[New] Highlight  Prime iPhone GIF Apps to Try</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-addressing-undetectable-disks/"><u>Strategies for Addressing Undetectable Disks</u></a></li>
<li><a href="https://windows11.techidaily.com/a-beginners-guide-to-managing-windows-11-wins/"><u>A Beginner's Guide to Managing Windows 11 Wins</u></a></li>
<li><a href="https://windows11.techidaily.com/turning-on-hyper-v-simplified-your-win11-how-to/"><u>Turning On Hyper-V Simplified - Your Win11 How-To</u></a></li>
<li><a href="https://windows11.techidaily.com/the-uncharted-territory-windows-11-and-the-future-of-ai/"><u>The Uncharted Territory: Windows 11 and the Future of AI</u></a></li>
<li><a href="https://windows11.techidaily.com/newbies-in-the-windows-world-steer-clear-of-these-top-8-faux-pas/"><u>Newbies in the Windows World: Steer Clear of These Top 8 Faux Pas</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-auto-detection-errors/"><u>Overcoming Windows Auto Detection Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-password-creation-companion-for-windows-users/"><u>The Ultimate Password Creation Companion for Windows Users</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-apple-iphone-se-to-pc-via-usb-drfone-by-drfone-ios/"><u>How to Mirror Apple iPhone SE to PC via USB? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-access-disabled-sign-in-on-windows/"><u>Restoring Access: Disabled Sign-In on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-correctly-installing-apps-from-ms-store/"><u>Mastering the Art of Correctly Installing Apps From MS Store</u></a></li>
<li><a href="https://video-capture.techidaily.com/top-10-ubuntu-screen-recorders-for-2024/"><u>Top 10 Ubuntu Screen Recorders for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/shaping-windows-11-square-it-off/"><u>Shaping Windows 11: Square It Off</u></a></li>
<li><a href="https://android-unlock.techidaily.com/6-proven-ways-to-unlock-sony-xperia-5-v-phone-when-you-forget-the-password-by-drfone-android/"><u>6 Proven Ways to Unlock Sony Xperia 5 V Phone When You Forget the Password</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-creative-processes-with-these-8-windows-best-apps/"><u>Streamline Creative Processes With These 8 Window's Best Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11-secrets-with-devhome-insights/"><u>Unlocking Windows 11 Secrets with DevHome Insights</u></a></li>
<li><a href="https://games-able.techidaily.com/crafting-an-efficient-strategy-for-low-memory-alerts-on-iphone/"><u>Crafting an Efficient Strategy for Low-Memory Alerts on iPhone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/outshine-xsplit-with-these-cutting-edge-alternatives-for-2024/"><u>Outshine Xsplit with These Cutting-Edge Alternatives for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-reducing-browsing-impact-on-system-performance/"><u>Tips for Reducing Browsing Impact on System Performance</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-discovering-the-global-tiktok-elite-our-top-15/"><u>[Updated] 2024 Approved  Discovering the Global TikTok Elite  Our Top 15</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-the-ultimate-list-of-preferred-mac-snipping-apps/"><u>[New] 2024 Approved  The Ultimate List of Preferred Mac Snipping Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-manual-reverting-windows-to-a-previous-state/"><u>Step-by-Step Manual: Reverting Windows to a Previous State</u></a></li>
<li><a href="https://windows11.techidaily.com/overhauling-write-operations-failure-fixes-on-windows/"><u>Overhauling Write Operations Failure Fixes on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/ultimate-bundle-premier-cost-free-windows-11-assistants/"><u>Ultimate Bundle: Premier Cost-Free Windows 11 Assistants</u></a></li>
<li><a href="https://windows11.techidaily.com/playnite-extension-virtual-games-collection/"><u>Playnite Extension: Virtual Games Collection</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-poco-c55-phone-without-any-data-loss-by-drfone-android/"><u>How to Unlock Poco C55 Phone without Any Data Loss</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/how-to-check-distance-and-radius-on-google-maps-for-your-apple-iphone-x-drfone-by-drfone-virtual-ios/"><u>How to Check Distance and Radius on Google Maps For your Apple iPhone X | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/1719377597268-legacy-software-understanding/"><u>Legacy Software Understanding:</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-update-halted-quick-solutions-for-a-perfect-installation/"><u>Windows Update Halted: Quick Solutions for a Perfect Installation</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-pitch-perfect-productions-integrating-songs-in-tiktok-vids/"><u>[New] Pitch-Perfect Productions  Integrating Songs in TikTok Vids</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/a-beginners-guide-to-seo-skyrocket-your-view-count-for-2024/"><u>A Beginner’s Guide to SEO  Skyrocket Your View Count for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/reestablish-wi-fi-masterful-solutions-for-windows-usb-adapters/"><u>Reestablish Wi-Fi: Masterful Solutions for Windows USB Adapters</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-tiktoks-hottest-culinary-trends-try-these-15-easy-delights-for-2024/"><u>[New] TikTok's Hottest Culinary Trends - Try These 15 Easy Delights for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-through-faulty-shift-in-windows/"><u>Navigate Through Faulty Shift in Windows</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-remove-an-airtag-from-your-apple-id-account-from-iphone-x-by-drfone-ios/"><u>In 2024, How to Remove an AirTag from Your Apple ID Account From iPhone X?</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-a-guide-to-conveniently-documenting-your-gaming-victories/"><u>[Updated] A Guide to Conveniently Documenting Your Gaming Victories</u></a></li>
<li><a href="https://windows11.techidaily.com/rapid-and-secure-firmware-update-guide-for-surface-systems/"><u>Rapid & Secure Firmware Update Guide for Surface Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/uniting-gmail-and-outlook-windows-setup-walkthrough/"><u>Uniting Gmail and Outlook: Windows Setup Walkthrough</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-correcting-incompatible-software-with-windows-operations/"><u>Strategies for Correcting Incompatible Software with Windows Operations</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-top-text-animation-tools/"><u>2024 Approved Top Text Animation Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/prying-into-hidden-taskbar-analysis-tool-in-windows-11/"><u>Prying Into Hidden Taskbar Analysis Tool in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-wi-fi-connectivity-hurdles-clearing-action-shortcomings/"><u>Overcoming Wi-Fi Connectivity Hurdles: Clearing Action Shortcomings</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/best-free-recorder-options-watermark-free/"><u>Best Free Recorder Options (Watermark-Free)</u></a></li>
<li><a href="https://windows11.techidaily.com/re-establishing-printer-linkage-in-windows-11-setup/"><u>Re-Establishing Printer Linkage in Windows 11 Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-caption-troubleshooting-made-simple/"><u>Win11 Caption Troubleshooting Made Simple</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-get-and-use-pokemon-go-promo-codes-on-lava-yuva-3-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Get and Use Pokemon Go Promo Codes On Lava Yuva 3 Pro | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-win-1011s-top-screencasting-applications-unveiled/"><u>[New] Win 10/11'S Top Screencasting Applications Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-and-fixing-invalid-temp-directories-on-win11/"><u>Preventing and Fixing Invalid Temp Directories on Win11</u></a></li>
<li><a href="https://change-location.techidaily.com/how-can-i-catch-the-regional-pokemon-without-traveling-on-samsung-galaxy-m34-5g-drfone-by-drfone-virtual-android/"><u>How Can I Catch the Regional Pokémon without Traveling On Samsung Galaxy M34 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/reversal-of-extra-privileges-win11-standardization-tutorial/"><u>Reversal of Extra Privileges: Win11 Standardization Tutorial</u></a></li>
</ul></div>
