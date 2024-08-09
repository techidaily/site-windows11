---
title: Guide to Cease Built-In Desktop Keyboard in Windows OS
date: 2024-08-08T06:13:14.946Z
updated: 2024-08-09T06:13:14.946Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Cease Built-In Desktop Keyboard in Windows OS
excerpt: This Article Describes Guide to Cease Built-In Desktop Keyboard in Windows OS
keywords: Keyboard Disable Windows,Disable Keyboard Shortcut,BIOS Reset Keyboards,WinOS Keyboard Deactivate,Keyboard Stop Built-In Windows,Erase Desktop Keys OSX,Remote Desktop No Keyboard,Disable Built-In Keyboard Win10,Keyboard Disable Option Win10,Reset WinOS Keyboard Settings,Hide WIN OS Keyboard Keys,Remove Win Keyboards Remotely,Bypass Windows Default Keyboard,Unbind Windows Desktop Keys,Stop Built-In Windows Keyboard
thumbnail: https://thmb.techidaily.com/4b0cf62f8598176374094f1d5008db55cda943f9c34511f05e37067a05b873ab.jpg
---

## Guide to Cease Built-In Desktop Keyboard in Windows OS

 Sometimes you don't want your laptop's keyboard to take inputs. This is usually because you're plugging in an external keyboard, either because the built-in one is broken or you just want a larger typing space with a full-sized keyboard.

 However, since the keyboard is an integral part of your portable computer, disabling its primary input method is a little tricky. Here, we show you how to temporarily and permanently disable the laptop keyboard on Windows 10 and 11\.

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Find Your Laptop Keyboard in Device Manager

 Whether you want to disable your laptop keyboard temporarily or permanently, you will need to uninstall the input device from Device Manager.

 For this, you’ll need to identify the integrated keyboard in Device Manager. Since Device Manager will list all the recognized keyboards, including external keyboards, here’s how you can identify your laptop keyboard from the list.

 To identify the built-in keyboard in Device Manager:

1. Press **Win + R** to open **Run**.
2. Type **devmgmt.msc** and click **OK** to open Device Manager.
3. In Device Manager, expand the **Keyboards** section.  
![device manager keyboards 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/device-manager-keyboards-1.jpg)
4. Right-click on the first keyboard entry **(HID/Standard)** and select **Properties**.
5. In the **General** tab, check the **Location** section. If it says **Location 1** or **Plugged into keyboard port**, it is likely your laptop’s internal keyboard.
6. Bluetooth and USB keyboards will show **On Bluetooth Low Energy** and **On US Input Device**, respectively as its location.

 If you don't find your keyboard listed, make sure you have [set Device Manager to show hidden devices.](https://www.makeuseof.com/view-hidden-devices-in-windows/)

## How to Disable the Laptop Keyboard Temporarily

 To disable your laptop’s keyboard temporarily:

1. Right-click on all the **HID** and **PS/2 Keyboard** entries with the **Properties Location** set to **Location 1** or **Plugged into keyboard.**  
![uninstall keyboard device device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/uninstall-keyboard-device-device-manager.jpg)
2. Next, select **Uninstall Device** from the context menu.
3. Click **Yes** to confirm the action.
4. That’s it. You have disabled your laptop’s internal keyboard successfully.

 That said, this is a temporary solution. As soon as you restart your system, Windows will look for the connected but unrecognized devices and install the necessary drivers to make them functional.

## How to Disable Your Laptop Keyboard Permanently

![disable ps 2 port 18042prt command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/disable-ps-2-port-18042prt-command-prompt.jpg)

 If you want to disable your laptop keyboard permanently, you can disable your laptop’s built-in keyboard driver PS/2 i8042prt service using the Command Prompt. We'll use the sc command-line utility to configure the service and set its start parameter to disabled.

 To disable the laptop keyboard permanently:

1. Press the **Win key** and type **cmd** in the Windows search bar.
2. Right-click on **Command Prompt** and select **Run as Administrator**. Click **Yes** when the UAC prompt appears.
3. In the Command Prompt window, type the following command and press Enter:  
`sc config i8042prt start= disabled`
4. When the success message appears, close the Command Prompt, and restart your PC. After the restart, your laptop keyboard will stop registering any inputs.

 Note that, for this to work, you will need to uninstall your keyboard from Device Manager as shown above and restart your PC.

 If you change your mind and want to re-enable the keyboard, you can use the following command in an [elevated Command Prompt](https://www.makeuseof.com/windows-11-open-command-prompt/).

`sc config i8042prt start= auto`

 Once you see the success message, restart your PC to apply the changes.

## Disable the Built-in Keyboard Using an Incompatible Driver

 Another quirky solution to disable a built-in keyboard is to install an incompatible driver for the input device. Here's how to do it.

1. Open Device Manager and expand the **Keyboard** section.
2. Right-click on your laptop keyboard device and select **Update driver**.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
![Update the Relevant Keyboard Driver in Windows Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/5-update-the-relevant-keyboard-driver-in-windows-device-manager.jpg)
3. Select **Browse my computer for drivers**.  
<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![update driver search automatically for drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-search-automatically-for-drivers-device-manager.jpg)
4. Next, select **Let me pick from a list of available drivers on my computer**.  
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![update driver keyboard pick from list of available drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-keyboard-pick-from-list-of-available-drivers-device-manager.jpg)
5. Uncheck the **Show compatible hardware** option.
6. Select a random manufacturer under the **Manufacturer** column.  
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->
![install incompatible keyboard driver windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/install-incompatible-keyboard-driver0windows.jpg)
7. Click **Next**. Click **Yes** if an **Update Driver Warning** dialog appears.
8. Once installed, close Device Manager and reboot your computer.

 After the restart, your laptop keyboard will stop working. If you need to install the correct driver again to enable the keyboard, right-click on the keyboard device and select **Update driver**. Next, select **Search automatically for drivers**. Windows will look for a compatible driver and install it.

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![update driver search automatically for drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-search-automatically-for-drivers-device-manager.jpg)

 Alternatively, select **Browse my computer for drivers** in the Update Drivers dialogue. Next, select **Let me pick from a list of available drivers on my computer**. Make sure the **Show compatible hardware** option is enabled. Select an **HID Keyboard Device** driver from the list and click **Next**.

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![install compatible hardware driver keyboard device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/install-compatible-hardware-driver-keyboard-device-manager.jpg)

 Wait for the driver to install. Once done, reboot your computer, and the keyboard will start working again.

## Disable Your Laptop Keyboard Permanently on Windows

 The built-in chiclet keyboard on your laptop is the primary input method available, so there is no way to disable it with a single click. Also, you wouldn’t want to disable your keyboard accidentally. If you determine your keyboard to have gone rogue and typing on its own, you can permanently disable it using the Command Prompt and Device Manager.

 That said, apart from the hardware issues, your laptop keyboard can act up for many other reasons. To fix your keyboard, check for pending driver updates, use the built-in troubleshooter, or simply disable the individual keys.

 Sometimes you don't want your laptop's keyboard to take inputs. This is usually because you're plugging in an external keyboard, either because the built-in one is broken or you just want a larger typing space with a full-sized keyboard.

 However, since the keyboard is an integral part of your portable computer, disabling its primary input method is a little tricky. Here, we show you how to temporarily and permanently disable the laptop keyboard on Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-audio-aesthetics-high-quality-dj-template-videos-downloaded/"><u>[New] 2024 Approved  Audio Aesthetics  High-Quality DJ Template Videos Downloaded</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-how-to-effortlessly-eradicate-unwanted-youtube-feedback/"><u>[Updated] 2024 Approved  How to Effortlessly Eradicate Unwanted YouTube Feedback</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-broadcast-bliss-the-most-accurate-local-and-online-tv-services/"><u>[Updated] Broadcast Bliss  The Most Accurate Local and Online TV Services</u></a></li>
<li><a href="https://windows11.techidaily.com/10-ways-to-fix-onedrive-sync-issues-on-windows-11/"><u>10 Ways to Fix OneDrive Sync Issues on Windows 11</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-discreetly-explore-instagram-stories-with-us/"><u>2024 Approved  Discreetly Explore Instagram Stories With Us</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-tumblr-mavens-live-on-snapchat-feed/"><u>2024 Approved  Tumblr Mavens Live on Snapchat Feed</u></a></li>
<li><a href="https://windows11.techidaily.com/7-methods-for-correcting-unreachable-display-responses-in-windows/"><u>7 Methods for Correcting Unreachable Display Responses in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/a-list-of-frustrations-with-windows-11/"><u>A List of Frustrations with Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-windows-file-concordance-with-aoemi-tutorial/"><u>Achieve Windows File Concordance with AOEMi Tutorial</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-automatic-color-tuning-on-win11-devices/"><u>Activating Automatic Color Tuning on Win11 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-the-high-demand-of-ntoskrnlexe-processes/"><u>Addressing the High Demand of Ntoskrnl.exe Processes</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-win-based-office-glitches-effectively/"><u>Addressing Win-Based Office Glitches Effectively</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-system-maintenance-locating-and-resolving-win-os-error-codes-via-command-prompt-expertise/"><u>Advanced System Maintenance: Locating and Resolving Win-OS Error Codes via Command Prompt Expertise</u></a></li>
<li><a href="https://windows11.techidaily.com/asus-vs-rog-the-battle-for-the-ultimate-portable-pc/"><u>ASUS Vs. ROG: The Battle for the Ultimate Portable PC?</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-changing-printer-behavior-on-windows/"><u>Avoiding Changing Printer Behavior on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-missed-emojis-activating-the-latest-on-windows-11/"><u>Avoiding Missed Emojis: Activating the Latest on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-performance-pitfalls-high-cpu-usage-with-rm/"><u>Avoiding Performance Pitfalls: High CPU Usage with RM</u></a></li>
<li><a href="https://windows11.techidaily.com/bestow-magical-menus-on-your-pc/"><u>Bestow Magical Menus on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/cant-choose-a-drive-to-install-games-on-the-xbox-app-for-windows-try-these-fixes/"><u>Can't Choose a Drive to Install Games on the Xbox App for Windows? Try These Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/clear-the-way-to-privacy-with-simple-steps-for-ms-defender/"><u>Clear the Way to Privacy with Simple Steps for MS Defender</u></a></li>
<li><a href="https://windows11.techidaily.com/command-your-way-through-windows-11-nircmd-tips-and-tricks/"><u>Command Your Way Through Windows 11: NirCmd Tips & Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-to-rectifying-windows-11-search-issues/"><u>Comprehensive Guide to Rectifying Windows 11 Search Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-frequent-anydesk-windows-complications/"><u>Conquering Frequent AnyDesk Windows Complications</u></a></li>
<li><a href="https://windows11.techidaily.com/converting-your-notepad-to-nighttime-mode-with-ease-on-windows-11/"><u>Converting Your Notepad to Nighttime Mode with Ease on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/cure-the-save-issue-in-microsoft-oses/"><u>Cure the Save Issue in Microsoft OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-and-rectifying-non-functional-batches-in-windows/"><u>Deciphering and Rectifying Non-Functional Batches in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/declutter-for-growth-optimize-with-win11-tiny/"><u>Declutter for Growth: Optimize With Win11 Tiny</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-mysteries-of-invisible-context-options-in-windows-11/"><u>Decoding the Mysteries of Invisible Context Options in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/delving-into-windows-11s-data-preservation-capabilities/"><u>Delving Into Windows 11'S Data Preservation Capabilities</u></a></li>
<li><a href="https://windows11.techidaily.com/disentangling-common-errors-in-windows-11-zoom-app/"><u>Disentangling Common Errors in Windows 11 Zoom App</u></a></li>
<li><a href="https://games-able.techidaily.com/high-speed-vs-precision-the-polling-conundrum/"><u>High-Speed Vs. Precision: The Polling Conundrum</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-bypass-activation-lock-from-apple-iphone-12-4-easy-ways-by-drfone-ios/"><u>In 2024, Bypass Activation Lock From Apple iPhone 12 - 4 Easy Ways</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-the-functionality-of-unmanned-aerial-vehicles-explored/"><u>In 2024, The Functionality of Unmanned Aerial Vehicles Explored</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/in-2024-vsdc-not-your-cup-of-tea-try-these-mac-video-editor-alternatives/"><u>In 2024, VSDC Not Your Cup of Tea? Try These Mac Video Editor Alternatives</u></a></li>
<li><a href="https://windows11.techidaily.com/1719366391353-keyboards-on-the-ropes-reclaim-your-arrows/"><u>Keyboards on the Ropes? Reclaim Your Arrows!</u></a></li>
<li><a href="https://screen-recording.techidaily.com/navigating-virtual-board-functions-across-zoom-devices/"><u>Navigating Virtual Board Functions Across Zoom Devices</u></a></li>
<li><a href="https://some-approaches.techidaily.com/palette-playbook-utilizing-theoretical-knowledge-for-2024/"><u>Palette Playbook  Utilizing Theoretical Knowledge for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/pioneering-posts-a-facebook-guide-to-going-viral-for-2024/"><u>Pioneering Posts  A Facebook Guide to Going Viral for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/1719211883980-tackling-the-challenge-of-non-working-win-plus-printer-feature-in-windows/"><u>Tackling the Challenge of Non-Working Win + Printer Feature in Windows</u></a></li>
<li><a href="https://extra-resources.techidaily.com/the-complete-handbook-of-xbox-one-zoom-communication/"><u>The Complete Handbook of Xbox One Zoom Communication</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/nsights-into-2018-fifa-football-videos-on-youtube-infographic/"><u>Top Insights Into 2018 FIFA Football Videos On YouTube [Infographic]</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>