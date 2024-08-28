---
title: "Waking Up the Watches: 5 Fixes for Lost Windows Server Time"
date: 2024-08-27T16:05:45.556Z
updated: 2024-08-28T16:05:45.556Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Waking Up the Watches: 5 Fixes for Lost Windows Server Time"
excerpt: "This Article Describes Waking Up the Watches: 5 Fixes for Lost Windows Server Time"
keywords: Windows Time Sync,Server Date Fix,Lost Time Resolution,Patched Window Time,Secure Time Update,Tick-Tock Window Patch,Server Clock Correction
thumbnail: https://thmb.techidaily.com/ea90fc8c45e04f560568c92780cb489093bd55fc49ac8140b1c1038ab7e89004.jpg
---

## Waking Up the Watches: 5 Fixes for Lost Windows Server Time

 Start your Windows computer and notice that the time is wrong. It might be a minor issue, or you accidentally changed the setting. But what if Windows Time Service is missing entirely?

 Fortunately, restoring the Windows Time Service is not complicated. This guide will discuss quickly restoring the missing Windows Time Service and setting the correct time on your computer.

## 1\. Reboot Your PC

 Restart your computer before attempting any major troubleshooting. While it may sound simple, restarting the computer resolves minor errors and glitches that prevent the service from running. It flushes out temporary files and refreshes the operating system to ensure everything works correctly.

1. Press **Alt + F4** to bring up the Shutdown dialog
2. Select **Restart** from the drop-down menu and then hit **OK**.

 Once the computer restarts, check if Windows Time Service is available. If it's still missing, move on to the next step.

## 2\. Change the Time Server

 If restarting the computer does not work, you must change the time server. Changing the time server synchronizes your system clock with an online one, displaying your computer's correct date and time.

 Follow the steps to change the time server:

1. Press the **Windows key** to open the Start Menu.
2. Type **control panel** in the search box and click the result. This opens the Control Panel window.
3. Select **View by: Large icons** and click **Date and Time**.
4. Switch to the **Internet Time** tab and click **Change settings**.
5. Check the **Synchronize with an Internet time server** box and select a time server from the drop-down menu.  
![Change the Time Server](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/change-the-time-server.jpg)
6. Click the **Update now** button to synchronize your computer with the time server.
7. Once completed, click **OK** to save the changes and exit.

 After these steps, you should see the Windows Time Service running on your system. Check the time to ensure it is correct and make further adjustments.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Add More Time Servers

 If the Windows Time Service is still missing, you can try adding more time servers to the list. Multiple time servers increase the chance of finding an active server and keeping your system in sync. If one server goes down, your computer can automatically switch to another.

 The solution requires editing the Windows registry. Even a small mistake can damage your system, so proceed with caution. To avoid data loss, [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing.

 To add time servers, do the following:

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **regedit** in the dialog box and click **OK**.
3. If the UAC window pops up on the screen, click **Yes** to grant permission.
4. In the Registry Editor window, navigate to the following directory.  
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\DateTime\Servers  
 Copy and paste the path into the Registry Editor address bar and press Enter. This will take you to the Location key.
5. From the left navigation panel, right-click the Servers folder and select **New** \> **String Value**.  
![Add More Time Servers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/add-more-time-servers.jpg)
6. Name the new value **Server N**, and replace **N** with a number starting from 1.  
 You can't have the same number twice. That means if there are already 3 values named _Server 1_, _Server 2_, and _Server 3_, you must call the new one as **Server 4**.
7. Double-click the newly created value and add a time server address in the Value data field.
8. Here are some time server addresses:  
`time.windows.com  

time.nist.gov  

time-a-wwv.nist.gov  

time-c-wwv.nist.gov  

ntp-wwv.nist.gov`

 After adding the time server, click **OK** and close the Registry Editor window. Now restart your computer to apply the changes and check if Windows Time Service is available.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
## 4\. Re-register the Windows Time Service

 If the above steps fail, you can try re-registering the Windows Time Service. Re-registering a service refreshes its configuration and forces it to start again. Doing this may fix the missing Windows Time Service and recover clock synchronization.

 To re-register the Windows Time Service, follow these steps:

1. Press the **Win + S** keys to open the Windows Search.
2. Type **cmd** in the search box and simultaneously press **Ctrl + Shift + Enter**. This opens the Command Prompt with administrative privileges.
3. If the UAC window pops up, click **Yes** to grant permission.
4. Type the following command in the Command Prompt and press Enter:  
net stop w32time
5. This command will stop the Windows Time Service. Now type the following command to unregister the service and press **Enter**:  
w32tm /unregister
6. After that, run the following command to register the service:  
w32tm /register
7. Next, type the following command and hit **Enter**. This starts the Windows Time Service.  
net start w32time

 After performing these steps, close the Command Prompt window and restart your system. You should see that the Windows Time Service is running, and your clock syncs with the time server.

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Repair Corrupted System Files

![SFC Command Preview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/sfc-command-preview.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Corrupt system files can also cause Windows services to fail. So, if the Windows Time Service is still missing, try repairing corrupt system files. You can do this using the System File Checker tool. This tool scans your system for missing files and repairs the errors it finds.

 Wait for the scan to complete, and restart your computer. After that, check if the Windows Time Service is still missing. If it is, try running the Deployment Image Servicing and Management tool. This tool repairs corrupted system files and restores your Windows installation's health.

 If you're not sure how to run either of these tools, check out how to repair corrupt Windows files with its built-in tools for instructions.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
## 6\. Scan for Malware

 Sometimes, malware is to blame for Windows services acting a little odd. As such, it's worth [running a full system scan](https://www.makeuseof.com/scan-for-viruses-without-buying-antivirus-software/) and removing all detected threats.

![Full Scan Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/full-scan-windows-security.jpg)

 If you feel your PC isn't as secure as it could be, you could try downloading one of the [best antivirus apps for Windows](http://www.makeuseof.com/windows-11-antivirus-apps/). These will both actively block malicious program from installing themselves on your PC, and remove any that are currently infesting your computer.

 For those who prefer a command-line approach, you can [use Windows PowerShell to scan Windows for malware](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/).

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
<!-- affiliate ads end -->
## Restore the Missing Windows Time Service

 Hopefully, one or more of these tips worked for you. Missing Windows services can be a huge pain, but hopefully, one of these methods has brought back the Windows Time Service back to working order.

 Fortunately, restoring the Windows Time Service is not complicated. This guide will discuss quickly restoring the missing Windows Time Service and setting the correct time on your computer.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-guidance.techidaily.com/new-maximizing-4k-imaging-top-lens-choices/"><u>[New] Maximizing 4K Imaging  Top Lens Choices</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-unlock-more-views-the-art-of-crafting-titles-and-tags-for-youtube/"><u>[New] Unlock More Views  The Art of Crafting Titles & Tags for YouTube</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-amplifying-your-playlists-on-instagram-for-2024/"><u>[Updated] Amplifying Your Playlists on Instagram for 2024</u></a></li>
<li><a href="https://win-amazing.techidaily.com/comprehensive-tutorial-upgrading-the-firmware-of-your-usb-serial-device-driver/"><u>Comprehensive Tutorial: Upgrading the Firmware of Your USB-Serial Device Driver</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-the-latest-thrustmaster-t300-steering-wheel-drivers-compatible-with-windows-10-and-11-pcs/"><u>Download the Latest ThrustMaster T300 Steering Wheel Drivers Compatible with Windows 10 and 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-to-microsoft-works-on-windows-latest-editions/"><u>Essential Guide to Microsoft Works on Windows Latest Editions</u></a></li>
<li><a href="https://howto.techidaily.com/full-solutions-to-fix-error-code-920-in-google-play-on-tecno-spark-go-2023-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Solutions to Fix Error Code 920 In Google Play on Tecno Spark Go (2023) | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-avoid-auto-snip-from-prtscreen-keypress-in-11-windows/"><u>How to Avoid Auto-Snip From PrtScreen Keypress in 11 Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-execute-the-windows-startup-check/"><u>How to Execute the Windows Startup Check</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-the-soft-bricked-infinix-hot-30-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix the Soft Bricked Infinix Hot 30 5G? | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/how-to-guide-advanced-techniques-for-skype-screenshots-via-obs-for-2024/"><u>How-To Guide  Advanced Techniques for Skype Screenshots via OBS for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/identifying-and-correcting-uninstalled-hdd-errors-on-windows-11-pc/"><u>Identifying & Correcting Uninstalled HDD Errors on Windows 11 PC</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-platform-picks-for-prominent-content-creators/"><u>In 2024, Platform Picks for Prominent Content Creators</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-vivo-y36-drfone-by-drfone-virtual-android/"><u>In 2024, Why Your WhatsApp Location is Not Updating and How to Fix On Vivo Y36 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/live-conversion-of-speech-to-text-using-whisper/"><u>Live Conversion of Speech to Text Using Whisper</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11-netstat-to-monitor-tcpip-activity/"><u>Navigating Windows 11 Netstat to Monitor TCP/IP Activity</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-win11s-installer-lacks-permissions-issue/"><u>Overcoming Win11's Installer Lacks Permissions Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/proactive-battery-status-enabling-full-charge-alerts-in-windows-11/"><u>Proactive Battery Status: Enabling Full Charge Alerts in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-onedrive-x-error-code-sign-in-woes-on-windows-11/"><u>Quick Fixes for OneDrive X-Error Code: Sign In Woes on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-external-monitor-connectivity-problems-in-windows/"><u>Resolving External Monitor Connectivity Problems in Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-puzzling-windows-update-error-code-0x8007001f/"><u>Resolving the Puzzling Windows Update Error Code 0X8007001F</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-lost-contacts-steam-fixes-for-windows-11/"><u>Restoring Lost Contacts: Steam Fixes for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-normalcy-notepad-on-windows-recovery/"><u>Restoring Normalcy: Notepad on Windows Recovery</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-your-system-with-these-7-budget-friendly-password-tools/"><u>Secure Your System with These 7 Budget-Friendly Password Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/sidestep-denied-login-issues-in-windows-with-easy-fixes/"><u>Sidestep Denied Login Issues in Windows with Easy Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/strengthening-windows-11-enhanced-mobile-accessibility/"><u>Strengthening Windows 11: Enhanced Mobile Accessibility</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-usb-non-attachment-problems-in-virtualbox-on-your-pc/"><u>Tackling USB Non-Attachment Problems in VirtualBox on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-using-dism-on-windows-11/"><u>The Ultimate Guide to Using DISM on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-to-rescue-your-zip-extraction-mishaps-on-windows-11/"><u>Tips to Rescue Your ZIP Extraction Mishaps on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tutorial-adjust-win11-connection-preferences/"><u>Tutorial: Adjust Win11 Connection Preferences</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-full-task-mastery-administrative-run-in-task-manager-on-win11/"><u>Unlocking Full Task Mastery: Administrative Run in Task Manager on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-hidden-windows-startup-items/"><u>Unveiling Hidden Windows Startup Items</u></a></li>
<li><a href="https://windows11.techidaily.com/what-hides-in-ftdibussys-windows-memory-integrity-disruption/"><u>What Hides in ftdibus.sys: Windows' Memory Integrity Disruption</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/where-is-the-best-place-to-catch-dratini-on-motorola-moto-g73-5g-drfone-by-drfone-virtual-android/"><u>Where Is the Best Place to Catch Dratini On Motorola Moto G73 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-guide-nullify-local-account-security-prompts/"><u>Win 11 Guide: Nullify Local Account Security Prompts</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-tips-disabling-unwanted-mouse-speed-boosting/"><u>Win 11 Tips: Disabling Unwanted Mouse Speed Boosting</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-and-10-home-enabling-administrator-access/"><u>Win11 & 10 Home: Enabling Administrator Access</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-ready-effective-microsoft-works-installation/"><u>Win11 Ready: Effective Microsoft Works Installation</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>