---
title: 15 Paths to Recover Missing Windows System Time Functionality
date: 2025-01-22T23:35:17.142Z
updated: 2025-01-29T18:27:01.824Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 15 Paths to Recover Missing Windows System Time Functionality
excerpt: This Article Describes 15 Paths to Recover Missing Windows System Time Functionality
keywords: Windows System Time Fix,Lost Clock Recovery,TimeSync Restore,SystemClock Reset,MissingTime Correction,RegistryTime Repair,NTPClient Guide
thumbnail: https://thmb.techidaily.com/c4aba1f1071f6153eef4e836db7e5ca4bdc93515fc62fa8fcf2e43a66dd6f0fc.jpg
---

## 15 Paths to Recover Missing Windows System Time Functionality

 Start your Windows computer and notice that the time is wrong. It might be a minor issue, or you accidentally changed the setting. But what if Windows Time Service is missing entirely?

 Fortunately, restoring the Windows Time Service is not complicated. This guide will discuss quickly restoring the missing Windows Time Service and setting the correct time on your computer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6KXVWj6Ar1M?si=Cd_jktmoN3e9OzH3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Reboot Your PC

 Restart your computer before attempting any major troubleshooting. While it may sound simple, restarting the computer resolves minor errors and glitches that prevent the service from running. It flushes out temporary files and refreshes the operating system to ensure everything works correctly.

1. Press **Alt + F4** to bring up the Shutdown dialog
2. Select **Restart** from the drop-down menu and then hit **OK**.

 Once the computer restarts, check if Windows Time Service is available. If it's still missing, move on to the next step.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/g6xXIR_Uh1A?si=TMXzklPEY50MUM05" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XA_wP7rS9ww?si=LarMG3sEHAhSoL6q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Once completed, click **OK** to save the changes and exit.

 After these steps, you should see the Windows Time Service running on your system. Check the time to ensure it is correct and make further adjustments.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/AcAYRX0cwwA?si=DxqWU39vqksZbe1s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/7JBG_O3Vnh4?si=lUO0fta6YPJ50qjg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-how-to-record-lol-gameplay3-methods/"><u>[Updated] 2024 Approved How To Record LOL Gameplay?(3 Methods)</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-2024-approved-the-ultimate-guide-to-mobile-image-mastery/"><u>[Updated] 2024 Approved The Ultimate Guide to Mobile Image Mastery</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-capture-and-store-videos-effortlessly-with-our-top-list-for-2024/"><u>[Updated] Capture & Store Videos Effortlessly with Our Top List for 2024</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-advanced-tools-tweet-with-converted-videos/"><u>2024 Approved Advanced Tools Tweet with Converted Videos</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-and-update-mbox-2-drivers-on-windows-a-step-by-step-guide/"><u>Download & Update MBox 2 Drivers on Windows: A Step-by-Step Guide</u></a></li>
<li><a href="https://tech-hub.techidaily.com/google-translate-vs-chatgpt-evaluating-the-top-contenders-in-effective-linguistic-translation/"><u>Google Translate Vs. ChatGPT – Evaluating the Top Contenders in Effective Linguistic Translation</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-resolve-issues-after-patching-the-escapists-game-on-windows-systems/"><u>How to Resolve Issues After Patching 'The Escapists' Game on Windows Systems</u></a></li>
<li><a href="https://tech-hub.techidaily.com/maximize-productivity-on-the-go-how-to-implement-chatgpt-into-your-iphone-or-ipad-experience/"><u>Maximize Productivity on the Go: How to Implement ChatGPT Into Your iPhone or iPad Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-steam-audio-latency-troubleshooting/"><u>Navigating Windows Steam Audio Latency Troubleshooting</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-portaudio-faults-in-audacity-for-windows-1111-os/"><u>Resolving PortAudio Faults in Audacity for Windows 11/11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-workflow-excellent-screen-savers-with-clock-features/"><u>Seamless Workflow: Excellent Screen Savers with Clock Features</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-the-power-of-windows-11-taskbar-for-maximum-output/"><u>Unleash the Power of Windows 11 Taskbar for Maximum Output</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11-access-a-step-by-step-guide/"><u>Unlocking Windows 11 Access: A Step-by-Step Guide</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-avoid-data-loss-essential-tips-for-saving-your-final-cut-pro-project/"><u>Updated 2024 Approved Avoid Data Loss Essential Tips for Saving Your Final Cut Pro Project</u></a></li>
</ul></div>

