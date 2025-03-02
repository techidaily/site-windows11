---
title: "Time Is Money: Restoring Windows Server Time Quickly"
date: 2025-02-28T12:01:23.000Z
updated: 2025-03-02T02:42:45.067Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Time Is Money: Restoring Windows Server Time Quickly"
excerpt: "This Article Describes Time Is Money: Restoring Windows Server Time Quickly"
keywords: WinServer Time Fix,Timing Servers Rush,Fast Server Time Set,Server Time Correction,Repair Time Server,Windows Time Restore,Quick Time Server Fixed
thumbnail: https://thmb.techidaily.com/0ad1f89069cff4b2779ade10913206262c7bed58531552359326ac17834a5d8d.jpg
---

## Time Is Money: Restoring Windows Server Time Quickly

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

## 5\. Repair Corrupted System Files

![SFC Command Preview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/sfc-command-preview.jpg)

 Corrupt system files can also cause Windows services to fail. So, if the Windows Time Service is still missing, try repairing corrupt system files. You can do this using the System File Checker tool. This tool scans your system for missing files and repairs the errors it finds.

 Wait for the scan to complete, and restart your computer. After that, check if the Windows Time Service is still missing. If it is, try running the Deployment Image Servicing and Management tool. This tool repairs corrupted system files and restores your Windows installation's health.

 If you're not sure how to run either of these tools, check out how to repair corrupt Windows files with its built-in tools for instructions.

## 6\. Scan for Malware

 Sometimes, malware is to blame for Windows services acting a little odd. As such, it's worth [running a full system scan](https://www.makeuseof.com/scan-for-viruses-without-buying-antivirus-software/) and removing all detected threats.

![Full Scan Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/full-scan-windows-security.jpg)

 If you feel your PC isn't as secure as it could be, you could try downloading one of the [best antivirus apps for Windows](http://www.makeuseof.com/windows-11-antivirus-apps/). These will both actively block malicious program from installing themselves on your PC, and remove any that are currently infesting your computer.

 For those who prefer a command-line approach, you can [use Windows PowerShell to scan Windows for malware](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/).

## Restore the Missing Windows Time Service

 Hopefully, one or more of these tips worked for you. Missing Windows services can be a huge pain, but hopefully, one of these methods has brought back the Windows Time Service back to working order.

 Fortunately, restoring the Windows Time Service is not complicated. This guide will discuss quickly restoring the missing Windows Time Service and setting the correct time on your computer.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-resources.techidaily.com/new-best-titles-google-cardboards-most-immersive-vr-games/"><u>[New] Best Titles Google Cardboard's Most Immersive VR Games</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-elevate-your-content-strategies-for-youtube-success-for-2024/"><u>[Updated] Elevate Your Content Strategies for YouTube Success for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-global-gross-earnings-of-youtube-luminaries-for-2024/"><u>[Updated] Global Gross Earnings of YouTube Luminaries for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/building-an-effective-monetization-plan-for-video-content-on-vimeo-for-2024/"><u>Building an Effective Monetization Plan for Video Content on Vimeo for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/easily-enlarge-or-decrease-taskbar-in-win11/"><u>Easily Enlarge or Decrease Taskbar in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/effortlessly-accessing-windows-mixer-settings/"><u>Effortlessly Accessing Window's Mixer Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-chrome-profiles-errors-on-your-workstation/"><u>Eliminating Chrome Profiles Errors on Your Workstation</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-icon-grouping-in-windows-11/"><u>Eliminating Icon Grouping in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-windows-notepad-system-breakdowns/"><u>Eliminating Windows Notepad System Breakdowns</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-device-detection-for-razer-gear-in-windows-11/"><u>Enabling Device Detection for Razer Gear in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicate-performance-hiccups-a-guide-to-optimizing-warhammer-on-windows/"><u>Eradicate Performance Hiccups: A Guide to Optimizing Warhammer on Windows</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-12-without-passcode-or-face-id-drfone-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone 12 without Passcode or Face ID | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-10-nubia-z50s-pro-android-sim-unlock-apk-by-drfone-android/"><u>In 2024, Top 10 Nubia Z50S Pro Android SIM Unlock APK</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/optimize-your-play-streaming-in-obs-studio/"><u>Optimize Your Play Streaming in OBS Studio</u></a></li>
<li><a href="https://youtube-data.techidaily.com/itize-tags-the-essentials-for-your-youtube-video-posting-for-2024/"><u>Prioritize Tags The Essentials for Your YouTube Video Posting for 2024</u></a></li>
<li><a href="https://win-solutions.techidaily.com/resolved-fixes-for-starfield-game-crashingfreezing-issues-on-windows/"><u>Resolved: Fixes for Starfield Game Crashing/Freezing Issues on Windows</u></a></li>
</ul></div>

