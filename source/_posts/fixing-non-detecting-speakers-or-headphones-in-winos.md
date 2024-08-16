---
title: Fixing Non-Detecting Speakers or Headphones in WinOS
date: 2024-08-15T15:36:15.582Z
updated: 2024-08-16T15:36:15.582Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Non-Detecting Speakers or Headphones in WinOS
excerpt: This Article Describes Fixing Non-Detecting Speakers or Headphones in WinOS
keywords: Windows Audio Fix,Detect Sound Issues,WinOS Headphone Troubleshoot,No Sound on PC,Headset Non-Detection WinXP,Speaker Detection Error,WinOS Audio Not Working
thumbnail: https://thmb.techidaily.com/ba4d76a3836c79aa2d1ffbc408b14921a58fa2b19ac7a8b8eb3ad2286e02cfeb.jpg
---

## Fixing Non-Detecting Speakers or Headphones in WinOS

 Sometimes, you may notice a red X on the sound icon on the Windows taskbar. If you hover the cursor over it, it shows a no speaker, or headphones are plugged in error. This error can occur due to issues with the audio driver or Windows audio services.

 To fix the error, run the built-in audio troubleshooter that can find and fix common audio issues with the sound device. If not, you can perform an audio driver rollback or manually reinstall the audio driver to restore your system's audio.

 Here are a few troubleshooting steps to help you fix the no speaker or headphones are plugged in error on Windows.

## 1\. Run the Windows Audio Troubleshooter

 You can troubleshoot sound problems on Windows using the built-in audio troubleshooter. It scans your Windows system for common audio issues and tries to fix them automatically.

To run the troubleshooter:

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, scroll down and click on**Troubleshoot** .
3. Next, click on**Other** **troubleshooters** .  
![Windows 11 troubleshoot other troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-troubleshoot-other-troubleshooter.jpg)
4. Click the**Run** button for**Playing Audio** . It will check your audio service status and prompt you to select your audio device.  
![Windows 11 settings troubleshoot other troubleshooters playing audio run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-settings-troubleshoot-other-troubleshooters-playing-audio-run.jpg)
5. Select your device speaker and click**Next** .
6. Click**NO** ,**Do not open Audio Enhancements** in the**Turn off Sound Effects and Enhancements** dialog.
7. Apply any recommended fixes and check for any improvements.

 If the troubleshooter left a good impression on you, check out our [guide to every troubleshooter on Windows 11](https://www.makeuseof.com/windows-11-troubleshooters/) for more of them.

## 2\. Perform an Audio Device Driver Rollback

 If a Windows or driver update has messed up your audio device, you can perform a driver rollback to reinstall the last known good driver. You can use the Device Manager to [roll back a driver in Windows](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) .

 To roll back an audio device driver, follow our guide on [how to roll back a driver in Windows](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) . You'll likely find your audio drivers in the**Sound, video, and game controllers** section of Device Manager.

## 3\. Add Network Service and Local Services to the Local Administrator Group

 Another way to fix this error is to add**Network service** and**Local Services** to the Local Administrator Group. Network Service and Local Service are predefined accounts part of the service control manager. Adding these accounts to the Local Administrator Group should help you fix the sound problem on your Windows PC.

 Note that Local Users and Groups is not available on the Windows Home edition. Home users, however, can add Network Service and Local Services to the local administrator group using Command Prompt.

 To add Network Service and Local Services to the Local Administrator Group using Local Users and Groups:

1. Press**Win + X** to open the**WinX** **Menu** .
2. Click on**Computer Management.**
3. In**Computer Management** , click on**Local User and Groups.**  
![computer management windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/computer-management-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
4. In the right pane, double-click on**Groups** to view all the local accounts.  
![local users and groups administrator properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/local-users-and-groups-administrator-properties.jpg)
5. Select and right-click on the**Administrators** account and select**Properties** .  
![administrator properties local users and groups](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/administrator-properties-local-users-and-groups.jpg)

1. Click the**Add** button in the**Administrator Properties** dialog.
2. ![administrator properties local users and groups](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/administrator-properties-local-users-and-groups.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
<!-- affiliate ads end -->
3. Next, type**network service** and click**Check Names** . It should change the object name to**NETWORK SERVICE.**  
![add network service local administrator group](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/add-network-service-local-administrator-group.jpg)
4. Click**OK** to add network service to the local user group.
5. In the**Administrator Properties** dialog, you'll see**NT Authority\\Network Service added as the member.**
6. Click the**Add** button again and repeat the steps to add**Local Services** to the group as well.
7. Once done, click**Apply** and**OK** to save the changes.

 If you use the Windows Home edition, you can use Command Prompt to add Local Network and Local Services to the local administrator group. Here's how to do it.

![add network service local administrator group command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/add-network-service-local-administrator-group-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->

1. Press the**Win** key and type**cmd** .
2. Right-click on**Command Prompt** and select**Run as administrator.**
3. In the Command Prompt window, type the following to add "local service" to the Local Group Administrator:  
`net localgroup Administrators /add localservice`
4. Next, type the following command to add "network service" to the Local Group Administrator account:  
`net localgroup Administrators /add networkservice`
5. If both the commands are executed successfully, type**exit** and press**Enter** to close Command Prompt.
6. Restart your PC and check if the error is resolved.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Uninstall the Audio Device and Driver

 Temporary glitches with the audio device driver can cause this error on Windows. To fix the issue, uninstall the audio device and the associated driver from Device Manager. After the restart, Windows will automatically reinstall the driver to resolve the issue.

To uninstall an audio device:

1. Press**Win + X** to open the**WinX** menu.
2. Click on**Device Manager** from the context menu.
3. In Device Manager, expand the**Sound, video, and game controllers** section.
4. Right-click on your audio device, like**Realtek** **Audio** .  
![uninstall audio device device manager 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-audio-device-device-manager-1.jpg)
5. Select**Attempt to remove the driver for this device** option in the**Uninstall Device** dialog.  
![uninstall audio device device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-audio-device-device-manager.jpg)
6. Click**Uninstall** to remove the device.
7. Once uninstalled, restart your PC. Windows will automatically install the necessary drivers for your audio device.

 If the issue persists, manually reinstall the audio device driver from the manufacturer.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Manually Reinstall the Audio Device Driver

 If the automatic reinstall doesn't work, check if your computer manufacturer or the audio device OEM has a stable driver version available. On a laptop, visit your computer manufacturer's website and download the latest audio drivers. On a desktop, you can download the latest drivers for your sound card from the manufacturer's website.

 Alternatively, you can also manually reinstall the existing drivers for your audio device. Check out [how to update Windows, Apps, and drivers](https://www.makeuseof.com/tag/update-windows-software-guide/) for more information.

 If the issue persists, change the device installation settings and then reinstall the driver. To change device installation settings:

![device installation settings windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/device-installation-settings-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. Press the**Win** key, and type**device installation settings.**
2. Next, click on**Change device installation settings** from the search result.
3. Select the**No (your device might not work as expected)** option in the**Device installation settings** dialog.
4. Click**Save Changes** . Click**Yes** if prompted by**User Account Control.**

 With the automatic driver download disabled, reinstall the existing driver to fix the no audio issue.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->
## Fixing the "No Speaker or Headphones Are Plugged In" Error

 The error often occurs due to a bad driver update. To fix it, you can perform a rollback or manually reinstall the audio device driver. In addition, try to update the audio device driver from the manufacturer's website.


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
<li><a href="https://some-knowledge.techidaily.com/new-exploring-why-photo-booth-videos-freeze-suddenly/"><u>[New] Exploring Why Photo Booth Videos Freeze Suddenly</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-harmony-in-digital-15-high-fidelity-bots-transforming-discord-soundscape/"><u>[Updated] 2024 Approved  Harmony in Digital  15 High-Fidelity Bots Transforming Discord Soundscape</u></a></li>
<li><a href="https://windows11.techidaily.com/alleviating-overuse-of-wmi-in-windows-installer/"><u>Alleviating Overuse of WMI in Windows Installer</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/android-unlock-code-sim-unlock-your-nokia-g22-phone-and-remove-locked-screen-by-drfone-android/"><u>Android Unlock Code Sim Unlock Your Nokia G22 Phone and Remove Locked Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/best-approaches-to-regulate-device-connections-in-windows/"><u>Best Approaches to Regulate Device Connections in Windows</u></a></li>
<li><a href="https://article-files.techidaily.com/bring-life-to-your-photos-motion-blur-techniques-for-illustration/"><u>Bring Life to Your Photos  Motion Blur Techniques for Illustration</u></a></li>
<li><a href="https://windows11.techidaily.com/camouflage-computing-integrating-archives-into-digital-image-win/"><u>Camouflage Computing: Integrating Archives Into Digital Image WIN</u></a></li>
<li><a href="https://extra-information.techidaily.com/clever-ways-to-neglect-edge-academy-vids/"><u>Clever Ways to Neglect EDGE Academy Vids</u></a></li>
<li><a href="https://windows11.techidaily.com/create-a-convenient-windows-environment-portable-software-icons/"><u>Create a Convenient Windows Environment: Portable Software Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/diagnosing-absent-monitor-display-issue/"><u>Diagnosing Absent Monitor Display Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/downloading-woes-how-to-fix-windows-11-transfer-issues-2/"><u>Downloading Woes: How to Fix Windows 11 Transfer Issues (2)</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-steps-to-correct-windows-11-0x800f0922-error/"><u>Effective Steps to Correct Windows 11 0X800F0922 Error</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-camera-app-crash-microsofts-windows-error-0xa00f425d/"><u>Eliminating Camera App Crash: Microsoft's Windows Error 0xA00F425D</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/essential-hashtags-propel-your-posts-to-the-top-for-2024/"><u>Essential #Hashtags  Propel Your Posts to the Top for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/file-location-artistry-in-windows-11-exploring-best-practices-6-advanced-methods/"><u>File Location Artistry in Windows 11: Exploring Best Practices (6 Advanced Methods)</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tune-your-system-control-delete-confirmations/"><u>Fine-Tune Your System: Control Delete Confirmations</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-inactive-windows-headsets-communication-line/"><u>Fixing Inactive Windows Headset's Communication Line</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-nvidia-control-panel-not-saving-settings-in-windows-11/"><u>How to Fix the NVIDIA Control Panel Not Saving Settings in Windows 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-data-from-iphone-12-pro-max-to-other-iphone-14-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 12 Pro Max To Other iPhone 14 devices? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-i-transferred-messages-from-infinix-hot-30-5g-to-iphone-12xs-max-in-seconds-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How I Transferred Messages from Infinix Hot 30 5G to iPhone 12/XS (Max) in Seconds | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-activation-lock-on-the-apple-iphone-11-pro-max-without-previous-owner-by-drfone-ios/"><u>In 2024, How to Remove Activation Lock On the Apple iPhone 11 Pro Max Without Previous Owner?</u></a></li>
<li><a href="https://windows11.techidaily.com/innovative-windows-search-techniques-that-dont-use-ls/"><u>Innovative Windows Search Techniques That Don't Use LS</u></a></li>
<li><a href="https://windows11.techidaily.com/masking-task-view-button-on-win-11-bar/"><u>Masking Task View Button on Win 11 Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-memory-management-for-edges-webview2/"><u>Mastering Memory Management for Edge's WebView2</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-speedier-net-transfers-on-battlenet-windows/"><u>Mastering Speedier Net Transfers on Battle.net Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-window-terminals-shutdown-procedures-entryexit-tactics/"><u>Mastering Window Terminal's Shutdown Procedures: Entry/Exit Tactics</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-new-territory-altering-default-app-choices-in-windows-11/"><u>Navigating New Territory: Altering Default App Choices in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/preserving-torrent-performance-post-transfer-to-a-new-machine/"><u>Preserving Torrent Performance Post-Transfer to a New Machine</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-start-guide-to-windows-11-apps/"><u>Quick Start Guide to Windows 11 Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/rediscover-the-lost-treasures-within-windows-11s-features/"><u>Rediscover the Lost Treasures Within Windows 11'S Features</u></a></li>
<li><a href="https://windows11.techidaily.com/reimagining-fn-key-usage-within-windows-11-platform/"><u>Reimagining FN Key Usage Within Windows 11 Platform</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-black-screens-with-simple-win11-tweaks/"><u>Resolving Black Screens with Simple Win11 Tweaks</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-unable-to-connect-error-with-malwarebytes-in-windows/"><u>Resolving Unable to Connect Error with Malwarebytes in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-access-to-disabled-windows-apps/"><u>Restoring Access to Disabled Windows Apps</u></a></li>
<li><a href="https://win-solutions.techidaily.com/say-goodbye-to-crashes-fnaf-pc-version-corrects-the-infamous-security-breach-issue/"><u>Say Goodbye to Crashes: FNAF PC Version Corrects the Infamous 'Security Breach' Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-to-reduce-high-wmi-cpu-consumption/"><u>Solutions to Reduce High WMI CPU Consumption</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-unraveling-failed-system-call-issues-in-win1011/"><u>Steps to Unraveling 'Failed System Call' Issues in Win10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-mending-non-responsive-windows-network/"><u>Strategies for Mending Non-Responsive Windows Network</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-erase-no-server-errors-in-pc-apex-legends-(156-chars/"><u>Strategies To Erase No-Server Errors in PC Apex Legends (<156 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-your-touch-to-the-world-of-win11-keybindings/"><u>Tailoring Your Touch to the World of Win11 Keybindings</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-high-cpu-in-your-host-system/"><u>Taming High CPU in Your Host System</u></a></li>
<li><a href="https://extra-information.techidaily.com/three-tech-titles-to-choose-from/"><u>Three Tech Titles to Choose From</u></a></li>
<li><a href="https://windows11.techidaily.com/top-methods-to-enhance-utorrent-download-speed-win-edition/"><u>Top Methods to Enhance uTorrent Download Speed, WIN Edition</u></a></li>
<li><a href="https://some-skills.techidaily.com/understanding-film-a-beginners-guide-to-essential-shots-for-2024/"><u>Understanding Film  A Beginner's Guide to Essential Shots for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-storage-type-ssd-vs-hdd/"><u>Unveiling Storage Type: SSD vs HDD</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-11s-hidden-calendar-and-email-fixes/"><u>Unveiling Windows 11'S Hidden Calendar & Email Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-and-edge-background-runs-how-to-control/"><u>Win11 and Edge Background Runs - How to Control</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-tips-avoiding-discords-auto-start-and-update-checks/"><u>Windows Tips: Avoiding Discord's Auto-Start & Update Checks</u></a></li>
</ul></div>
