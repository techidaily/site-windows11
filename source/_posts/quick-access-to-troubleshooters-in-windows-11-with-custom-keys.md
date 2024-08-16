---
title: Quick Access to Troubleshooters in Windows 11 with Custom Keys
date: 2024-08-15T15:25:04.755Z
updated: 2024-08-16T15:25:04.755Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quick Access to Troubleshooters in Windows 11 with Custom Keys
excerpt: This Article Describes Quick Access to Troubleshooters in Windows 11 with Custom Keys
keywords: Windows Troubleshoot Tool,Quick Fix Window,Custom Key Troubleshooting,Win11 Access Tools,Easy Windows Repair,Troubleshooters Shortcut,Custom Fix Keys Windows
thumbnail: https://thmb.techidaily.com/b9d202f17312addc4751b6c7718b8073b057f0ff78d7cca6ec165bfb76c8c4ca.jpg
---

## Quick Access to Troubleshooters in Windows 11 with Custom Keys

 Windows 11 and 10 include various troubleshooting tools you can open via Settings and the Control Panel. There are troubleshooters for fixing Bluetooth, internet, Windows Update, audio, hardware, printer, video, and MS Store app-related errors that arise. Those troubleshooters detect issues and either automatically apply or suggest potential fixes to resolve them.

 Adding troubleshooter shortcuts to Windows 11/10 will save you from rummaging through Settings or the Control Panel whenever you need to access them. You can create troubleshooter shortcuts on the Windows 11/10 desktop, taskbar, Start menu, and even context menu with the methods below.

## How to a Set Up a Desktop Shortcut for Opening the Troubleshooting Applet

 Most users probably go through Settings to bring up troubleshooters. However, Control Panel’s Troubleshooting applet includes more troubleshooters than the Settings app. Adding a [desktop shortcut](https://www.makeuseof.com/what-is-desktop-shortcut-how-work/) for opening the applet will enable you to access all troubleshooters included within it more quickly.

 You can create a Troubleshooting shortcut on the Windows desktop in the following steps:

1. Right-click any part of the desktop area and select**New** .
2. Click the**Shortcut** option on the**New** submenu.  
![The Shortcut option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/shortcut-option.jpg)
3. Input**explorer shell:::{C58C4893-3BE0-4B45-ABB5-A63E4B8C8651}** inside the location box, and select the Create Shortcut wizard’s**Next** option.  
![The Create Shortcut window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/create-shortcut-window.jpg)
4. Erase the default shortcut title, and type**Troubleshooting Applet** in the text box.
5. Select**Finish** to add the Troubleshooting Applet desktop shortcut.  
![The Troubleshooting Applet desktop shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/troubleshooting-applet-shortcut.jpg)

 Double-click the new desktop shortcut you just added to open the Troubleshooting applet. There you can click**Programs** ,**Hardware and Sound** ,**Network and Internet** , or**System and Security** to view and access different categories of troubleshooters. Alternatively, select**View all** open to bring up a full list of troubleshooters. You can click any troubleshooter there to open it.

![The Troubleshooting applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-troubleshooting-applet.jpg)

 The Troubleshooting shortcut will have the same folder library icon as Explorer’s taskbar button. If you would prefer something else, you can change the icon via the shortcut’s properties window. Check out our guide about [how to customize icons on Windows](https://www.makeuseof.com/tag/customize-icon-windows/) for details.

## How to Set Up Taskbar and Start Menu Troubleshooting Shortcuts

 You can easily convert the Troubleshooting Applet desktop shortcut into a taskbar or Start menu one. To do so in Windows 11, click the Troubleshooting Applet shortcut with the right mouse button and select**Show more options** . Select**Pin to taskbar** on the classic menu to stick the same shortcut on the taskbar. Or click**Pin to Start** to have one for opening the Troubleshooting applet from the pinned area of the Start menu.

![The Pin to taskbar option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/pin-to-taskbar-option.jpg)

 Then you may as well remove the desktop shortcut if a taskbar or Start menu one is preferred. Right-click Troubleshooting Applet to select**Delete** (the trash bin icon in Windows 11).

## How to Set Up a Troubleshooting Hotkey

 A Troubleshooting desktop shortcut can also become a convenient hotkey in a few quick steps. All you have to do is set a key combination for activating the desktop shortcut. Then you can open the Troubleshooting applet by pressing a**Ctrl** +**Alt** key combo. These are the steps for setting up a hotkey that opens the Troubleshooting applet:

1. Create a desktop shortcut for opening the Troubleshooting applet as outlined in the first method.
2. Right-click the Troubleshooting shortcut and select**Properties** .
3. Click inside the box labeled**Shortcut key** .
4. Press**T** (for troubleshooting) to establish a**Ctrl** +**Alt** +**T** key combination.  
![The Shortcut key box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/shortcut-key-option.jpg)
5. Select**Apply** to save your new troubleshooting hotkey.
6. Click**OK** or**X** to close the Shortcut tab and window.

 Now you can access the Troubleshooting applet with a key combo. Press**Ctrl** +**Alt** +**T** to open that applet and access its troubleshooters. That hotkey depends on the desktop shortcut you set it for. So, you’ve got to leave the shortcut on the desktop.

## How to Set Up Shortcuts for Opening Specific Troubleshooters

 You can also set up shortcuts for opening any specific troubleshooters included within the Troubleshooting Control Panel applet. Each troubleshooter there has a pack ID with which you can set up a desktop shortcut for opening it. You can set up a troubleshooter shortcut in such a way via the Create Shortcut wizard with the following command:

`msdt.exe /id <diagnostic_id>`

 The above command must include an actual diagnostic\_id for the troubleshooter. This [MSDT page](https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2008-R2-and-2008/ee424379%28v=ws.10%29?redirectedfrom=MSDN) has a list of troubleshooting pack IDs you can include in that command. These are the diagnostic ID commands for some of the more useful troubleshooters:

`msdt.exe /id WindowsUpdateDiagnostic  
  
msdt.exe /id SearchDiagnostic  
  
msdt.exe /id DeviceDiagnostic  
  
msdt.exe /id PrinterDiagnostic  
  
msdt.exe /id NetworkDiagnosticsWeb  
  
msdt.exe /id AudioPlaybackDiagnostic`

 You can set up a desktop shortcut for a specific troubleshooter much the same as the Troubleshooting applet. Go through the same steps in this guide’s instructions for setting up a desktop shortcut, but input a troubleshooter diagnostic ID command at step three instead. Enter a different name for the shortcut in step four, and select the**Finish** option.

![The Windows Update troubleshooter command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-update-troubleshooter-command.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->

 Double-clicking that desktop shortcut will open whatever troubleshooter you set it to with the diagnostic ID command. Then you can also pin that desktop shortcut to the taskbar or Start menu just the same as the Troubleshooting applet one. Or set up a hotkey for opening the troubleshooting tool as outlined in this guide’s keyboard shortcut instructions.

![The Windows Update troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-update-troubleshooter-and-shortcut.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->
## How to Add a Troubleshooters Submenu to the Context Menu

 The right-click context menu is another place you can add Troubleshooting shortcuts in Windows 11/10\. You can set up a**Troubleshooters** submenu on the Windows 11/10 context menu that includes shortcuts for opening different parts of the Troubleshooting applet. To do that, you only need to download and run a premade registry script like this:

1. Open the [Add Troubleshooters Context Menu Softpedia page](https://www.softpedia.com/get/Tweak/System-Tweak/Add-Troubleshooters-Context-Menu-in-Windows-10.shtml) .
2. Select that registry script’s**Download Now** option.
3. Click the**Secure Download (US)** option.
4. Go into File Explorer (press**Win** +**E** to open), and bring up the directory containing the registry script’s ZIP archive.  
![The Extract Compressed Folders tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/extract-compressed-folder-tool.jpg)
<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Select to extract the troubleshooters-context-menu.zip archive. Our guide to [unzipping ZIP files on Windows](https://www.makeuseof.com/unzip-files-windows-10/) includes instructions for extracting these archives.
6. Open the extracted troubleshooters-context-menu folder.
7. Double-click the**Add Troubleshooters To Desktop Context Menu.reg** file.  
![The troubleshooters-context-menu folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/troubleshooters-context-menu-folder.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
8. Click**Yes** on the prompt that asks for user confirmation to apply the script.

 You will now see a new**Troubleshooters** submenu on your desktop’s context menu. Right-click any space within the desktop wallpaper area and select**Show more options** on Windows 11’s context menu. Move the cursor over the**Troubleshooters** submenu to view its shortcuts.

![The Troubleshooters submenu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/troubleshooters-option.jpg)

 There you can select**Classic Troubleshooting applet** to bring up the Troubleshooting home screen in the Control Panel. Select**All Categories** to open the full list of troubleshooters. Or click**Programs** ,**Hardware and Sound** ,**Network and Internet** , and**System Security** to view category pages for opening troubleshooters.

 The troubleshooters-context-menu folder also includes a script for removing the Troubleshooters submenu. Double-click**Remove Troubleshooters From Desktop Context Menu.reg** in that folder to run that script. Then select**Yes** to erase the submenu from the context menu.

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Make Some Shortcuts for Accessing Troubleshooters in Windows

 So, now you can create Windows shortcuts for opening the Troubleshooting applet and more specific troubleshooters in various ways. You can create a general Troubleshooting Control Panel desktop, taskbar, keyboard, or context menu shortcut for accessing all troubleshooting tools. Or set up shortcuts that give you more direct access to the specific troubleshooting tools you utilize more regularly.

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
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-building-unique-instagram-profile-thumbnails/"><u>[New] In 2024, Building Unique Instagram Profile Thumbnails</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-leading-ipad-audio-recorder-software-list-3/"><u>[New] In 2024, Leading iPad Audio Recorder Software List #3</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-visualsizetweak-mastering-your-instagram-media/"><u>[Updated] 2024 Approved  VisualSizeTweak  Mastering Your Instagram Media</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-popular-pictures-the-backstage-story/"><u>[Updated] Popular Pictures  The Backstage Story</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-social-media-mirrors-the-science-of-true-ig-selfies-for-2024/"><u>[Updated] Social Media Mirrors  The Science of True IG Selfies for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-full-guide-to-adobe-cloud-storage-and-best-alternatives/"><u>2024 Approved  Full Guide to Adobe Cloud Storage and Best Alternatives</u></a></li>
<li><a href="https://windows11.techidaily.com/apk-quickstart-guide-for-widely-adopted-windows-11/"><u>APK Quickstart Guide for Widely-Adopted Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/best-options-to-windows-snipper-top-5-alternative-capture-apps/"><u>Best Options to Windows Snipper: Top 5 Alternative Capture Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/breaching-windows-denied-logins-with-smart-fixes/"><u>Breaching Windows' Denied Logins with Smart Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/bringing-lost-panes-back-top-techniques-for-windows-11/"><u>Bringing Lost Panes Back: Top Techniques for Windows 11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-call-logs-on-realme-by-fonelab-android-recover-call-logs/"><u>Complete guide for recovering call logs on Realme</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-clutter-best-windows-apps-to-disable/"><u>Cutting Clutter: Best Windows Apps to Disable</u></a></li>
<li><a href="https://windows11.techidaily.com/delaying-windows-10-shutdown-during-running-programs/"><u>Delaying Windows 10 Shutdown During Running Programs</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-steps-to-clean-up-steams-networking-caches/"><u>Easy Steps to Clean Up Steam's Networking Caches</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/essential-download-guide-keeping-your-ch340g-usb-devices-running-smoothly-on-windows-11/"><u>Essential Download Guide: Keeping Your CH340G USB Devices Running Smoothly on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-to-windows-arp-cache-and-its-clearance-136-chars-exceeds-limit-adjusted-to-fit-better-clearing-windows-arp/"><u>Essential Guide to Windows ARP Cache and Its Clearance (136 Chars, Exceeds Limit, Adjusted to Fit Better: Clearing Windows ARP</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tune-automatic-lock-settings-on-pcs/"><u>Fine-Tune Automatic Lock Settings on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-resolving-windows-service-response-errors/"><u>Guide to Resolving Windows Service Response Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-elevate-your-old-computer-into-a-windows-11-powerhouse/"><u>How to Elevate Your Old Computer Into a Windows 11 Powerhouse</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-navigate-and-utilize-windows-iscsi-initiator-efficiently/"><u>How to Navigate and Utilize Windows iSCSI Initiator Efficiently</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-undo-unintended-changes-to-mixer-volume-levels/"><u>How to Undo Unintended Changes to Mixer Volume Levels</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-apple-id-locked-or-disabled-from-iphone-11-pro-max-7-mehtods-you-cant-miss-by-drfone-ios/"><u>In 2024, Apple ID Locked or Disabled From iPhone 11 Pro Max? 7 Mehtods You Cant-Miss</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-the-complete-guide-to-oppo-a18-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Complete Guide to Oppo A18 FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://windows11.techidaily.com/iphoneandroid-as-windows-microphones-guide/"><u>IPhone/Android as Windows Microphones Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-access-steps-for-unlocking-windows-hidden-char-personality-tracker/"><u>Mastering Access: Steps for Unlocking Windows' Hidden Char Personality Tracker</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-cr2-to-jpg-conversion-using-windows-tools/"><u>Mastering the Art of CR2 to JPG Conversion Using Windows Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-windows-crash-0x800f0831-solution/"><u>Mastery Over Windows Crash: 0X800f0831 Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-user-not-valid-windows-1111-errors/"><u>Navigating Through 'User Not Valid' Windows 11/11 Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-software-management-using-the-windows-package-manager-wpm/"><u>Optimizing Software Management Using the Windows Package Manager (WPM)</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-network-failure-0x800704b3-in-windows-1011/"><u>Overcoming Network Failure 0X800704B3 in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/overriding-default-no-notify-camera-behavior-in-ws11/"><u>Overriding Default No-Notify Camera Behavior in WS11</u></a></li>
<li><a href="https://windows11.techidaily.com/peek-inside-windows-determining-your-computers-manufacturer/"><u>Peek Inside Windows: Determining Your Computer's Manufacturer</u></a></li>
<li><a href="https://windows11.techidaily.com/precise-strategies-resetting-razers-system-integration/"><u>Precise Strategies: Resetting Razer's System Integration</u></a></li>
<li><a href="https://windows11.techidaily.com/process-to-undo-system-image-fault-0x80780119/"><u>Process to Undo System Image Fault: 0X80780119</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-rpc-errors-on-windows-os/"><u>Quick Fixes for RPC Errors on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/reconnecting-mic-during-windows-powerpoint-screencast/"><u>Reconnecting Mic During Windows PowerPoint Screencast</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-imaginary-device-issue-in-win-11-os/"><u>Resolving Imaginary Device Issue in Win 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-win1011-network-failure-code-0x800704b3/"><u>Resolving Win10/11 Network Failure: Code 0X800704B3</u></a></li>
<li><a href="https://windows11.techidaily.com/revamp-desktop-by-removing-windows-11s-highlighted-icon/"><u>Revamp Desktop by Removing Windows 11'S Highlighted Icon</u></a></li>
<li><a href="https://windows11.techidaily.com/revitalizing-your-stalled-windows-11-mobile-network-connection/"><u>Revitalizing Your Stalled Windows 11 Mobile Network Connection</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionize-your-pc-clear-tpm-from-windows-11/"><u>Revolutionize Your PC: Clear TPM From Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-firmware-enhancement-for-surface-devices/"><u>Seamless Firmware Enhancement for Surface Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-shadowrunners-speed-up-your-bf2-experience/"><u>Seamless Shadowrunners: Speed up Your BF2 Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/strip-windows-11-of-the-store-application/"><u>Strip Windows 11 of the Store Application</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-your-security-settings-on-windows-11/"><u>Tailoring Your Security Settings on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-steams-online-potential-on-pc/"><u>Unlocking Steam's Online Potential on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/win-prints-back-on-fixing-an-offline-printer/"><u>Win-Prints Back On! Fixing an Offline Printer</u></a></li>
<li><a href="https://windows11.techidaily.com/win11s-file-explorer-glitches-learn-how-to-stop-them/"><u>Win11's File Explorer Glitches? Learn How To Stop Them</u></a></li>
</ul></div>
