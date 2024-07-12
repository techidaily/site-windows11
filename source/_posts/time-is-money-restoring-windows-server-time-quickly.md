---
title: "Time Is Money: Restoring Windows Server Time Quickly"
date: 2024-07-11T22:04:08.701Z
updated: 2024-07-12T22:04:08.701Z
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
<li><a href="https://ai-editing-video.techidaily.com/updated-in-2024-how-to-convert-time-lapse-to-normal-video/"><u>Updated In 2024, How to Convert Time-Lapse to Normal Video</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/budget-friendly-recorder-options-1-to-10-free-software-guide-for-2024/"><u>Budget-Friendly Recorder Options  #1 to #10 Free Software Guide for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/simple-steps-for-screen-position-changes/"><u>Simple Steps for Screen Position Changes</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-illuminate-images-top-3-methods-for-captivating-comments/"><u>In 2024, Illuminate Images  Top 3 Methods for Captivating Comments</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshoot-and-fix-windows-autoshrink-issue/"><u>Troubleshoot & Fix Windows' Autoshrink Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-for-no-sound-during-system-tests/"><u>Remedy for No Sound During System Tests</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-add-background-to-video-withwithout-a-green-screen/"><u>New Add Background to Video With/Without a Green Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-unblock-windows-nvidia-setup-window/"><u>Strategies to Unblock Windows Nvidia Setup Window</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-text-messages-from-honor-magic-vs-2-to-new-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Text Messages from Honor Magic Vs 2 to New Phone | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-access-permissions-biometrics-on-w11-domains/"><u>Streamlining Access Permissions: Biometrics on W11, Domains</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-the-process-anydesk-fixes-for-windows-users/"><u>Simplifying the Process: AnyDesk Fixes for Windows Users</u></a></li>
<li><a href="https://extra-information.techidaily.com/craft-engaging-titlescaptions-with-microsofts-photos-app-win-11/"><u>Craft Engaging Titles/Captions with Microsoft's Photos App (Win 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-eliminate-startup-disruption-due-to-winscombsvc-errors/"><u>Quick Fix: Eliminate Startup Disruption Due to WinScombSvc Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-windows-11-in-place-update-mastery/"><u>Step-by-Step Windows 11, In-Place Update Mastery</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-camera-error-code-0xa00f425d/"><u>Overcoming Windows Camera Error Code: 0XA00F425D</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-in-2024-looking-beyond-imovie-10-impressive-android-video-editing-options/"><u>Updated In 2024, Looking Beyond iMovie 10 Impressive Android Video Editing Options</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-edges-continuous-desktop-appearance/"><u>Resolving Edges' Continuous Desktop Appearance</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-window-11-email-app-error-code-0x800713f/"><u>Overcoming Window 11 Email App Error Code 0X800713F</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-swift-guide-eliminating-images-backdrops-with-affinity-photo/"><u>In 2024, Swift Guide  Eliminating Images' Backdrops with Affinity Photo</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-discover-the-best-audio-conversion-solutions-for-2024/"><u>New Discover the Best Audio Conversion Solutions for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-your-experience-using-w11s-auto-hdr/"><u>Tailoring Your Experience: Using W11's Auto HDR</u></a></li>
<li><a href="https://windows11.techidaily.com/procedures-for-fixing-inoperative-ccleaner-on-windows-os/"><u>Procedures for Fixing Inoperative CCleaner on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/responding-to-click-failures-in-windows-11-environment/"><u>Responding to Click Failures in Windows 11 Environment</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/free-to-use-methods-for-attaching-tracks-to-digital-clips/"><u>Free-to-Use Methods for Attaching Tracks to Digital Clips</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-recording-live-videos-on-periscope-with-maximum-quality/"><u>2024 Approved  Recording Live Videos on Periscope with Maximum Quality</u></a></li>
<li><a href="https://driver-install.techidaily.com/gtx-760-upgrades-now-simpler-than-ever/"><u>GTX 760 Upgrades Now Simpler Than Ever</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-error-0x80072f8f-0x20000-in-windows/"><u>Troubleshooting Error 0X80072f8f - 0X20000 in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-xbox-mic-issues-on-windows-1111-pro/"><u>Resolving Xbox Mic Issues on Windows 11/11 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-win-1011-zoom-fatal-error-1132/"><u>Resolving Win 10/11 Zoom Fatal Error 1132</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-cam-showdown-spectacle-ultimate-legendary-sj6-meets-yis-visionary-4k/"><u>In 2024, Cam Showdown Spectacle  Ultimate Legendary SJ6 Meets Yi's Visionary 4K</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-complication-windows-11-plus-nvidia-x0001/"><u>Rectifying Complication: Windows 11 + Nvidia X0001</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-launch-hacks-opening-windows-11-apps-faster/"><u>Quick Launch Hacks: Opening Windows 11 Apps Faster</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-early-bird-winners-youtubes-quick-favorites/"><u>[New] In 2024, Early Bird Winners  Youtube's Quick Favorites</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-2024-approved-crew-collaboration-the-vital-roles-and-responsibilities-on-a-film-production-team/"><u>New 2024 Approved Crew Collaboration The Vital Roles and Responsibilities on a Film Production Team</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-making-the-cursor-more-noticeable-in-windows/"><u>Step-by-Step: Making the Cursor More Noticeable in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/reinventing-tech-windows-leap-from-version-11/"><u>Reinventing Tech: Windows' Leap From Version 11</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-say-goodbye-to-physical-media-converting-dvds-to-digital-files/"><u>New Say Goodbye to Physical Media Converting DVDs to Digital Files</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-does-the-stardust-trade-cost-in-pokemon-go-on-samsung-galaxy-f34-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How does the stardust trade cost In pokemon go On Samsung Galaxy F34 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/top-secure-password-vaults-elevating-windows-11-standards/"><u>Top Secure Password Vaults Elevating Windows 11 Standards</u></a></li>
<li><a href="https://windows11.techidaily.com/sharpening-performance-with-optimized-news-and-video-consumption/"><u>Sharpening Performance with Optimized News & Video Consumption</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-up-a-unique-win11-screenscape-display/"><u>Setting Up a Unique Win11 Screenscape Display</u></a></li>
<li><a href="https://windows11.techidaily.com/tricks-to-launch-websites-after-installation/"><u>Tricks to Launch Websites After Installation</u></a></li>
</ul></div>
