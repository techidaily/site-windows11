---
title: "Time to Get Back on Track: Recovering Windows Time Service"
date: 2024-07-11T21:35:31.012Z
updated: 2024-07-12T21:35:31.012Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Time to Get Back on Track: Recovering Windows Time Service"
excerpt: "This Article Describes Time to Get Back on Track: Recovering Windows Time Service"
keywords: Windows Time Fix,TimeSync Restore,WinTime Repair,TimeService Recovery,System Time Reset,TimeService Sync,Windows Service Patch
thumbnail: https://thmb.techidaily.com/d0b73eb28e24a2f2ed6215d7e2c211efc75eaeb77baea06879d148a0fe930510.jpg
---

## Time to Get Back on Track: Recovering Windows Time Service

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
<li><a href="https://windows11.techidaily.com/navigating-through-the-maze-of-windows-error-code-0xc00000f/"><u>Navigating Through the Maze of Windows Error Code 0Xc00000f</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-sniping-techniques-alternatives-to-windows-snipping-capability/"><u>Quick Sniping Techniques: Alternatives to Windows' Snipping Capability</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-win-os-extract-issues-saving-time-with-error-1152-solution/"><u>Overcoming Win OS Extract Issues: Saving Time with Error 1152 Solution</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/pioneering-teams-changing-vrs-course-for-2024/"><u>Pioneering Teams Changing VR's Course for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-in-2024-dynamic-visuals-excellence-in-4k-action-capture/"><u>[New] In 2024, Dynamic Visuals  Excellence in 4K Action Capture</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-revive-your-bricked-oppo-a58-4g-in-minutes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Revive Your Bricked Oppo A58 4G in Minutes | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/sound-revolution-for-your-pc-the-essential-guide-to-audio-drivers-updates/"><u>Sound Revolution for Your PC: The Essential Guide to Audio Drivers Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/overcome-hurdles-in-windows-hello-fingerprint-failures/"><u>Overcome Hurdles in Windows Hello Fingerprint Failures</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-culinary-challenges-and-triumphs-top-15-foodie-journeys-on-tiktok/"><u>In 2024, Culinary Challenges & Triumphs  Top 15 Foodie Journeys on TikTok</u></a></li>
<li><a href="https://windows11.techidaily.com/instructions-for-resetting-customized-windows-settings/"><u>Instructions for Resetting Customized Windows Settings</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-essential-guide-to-whatsapp-hacks-and-features/"><u>The Essential Guide to WhatsApp Hacks and Features</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-for-an-effortless-in-place-windows-11-revamp/"><u>Step-by-Step Guide for an Effortless, In-Place Windows 11 Revamp</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-monochrome-errors-with-marketplace/"><u>Fixing Monochrome Errors with Marketplace</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-tips-for-producing-compelling-podcast-introductions/"><u>In 2024, Tips for Producing Compelling Podcast Introductions</u></a></li>
<li><a href="https://windows11.techidaily.com/meeting-prep-101-test-your-windows-webcam-microphone/"><u>Meeting Prep 101: Test Your Windows Webcam, Microphone</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-the-reparse-point-buffer-tag-error-with-onedrive/"><u>Remedying the Reparse Point Buffer Tag Error with OneDrive</u></a></li>
<li><a href="https://windows11.techidaily.com/skyrocket-your-text-entry-speed-via-typingaid/"><u>Skyrocket Your Text Entry Speed via TypingAid</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-ultimate-selection-top-android-movie-making-apps/"><u>Updated Ultimate Selection Top Android Movie Making Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-error-printer-spooler-not-active-on-windows/"><u>Overcoming Error: “Printer Spooler Not Active” On Windows</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-top-cartoonizer-apps-transform-your-photos-on-mobile-devices/"><u>Updated In 2024, Top Cartoonizer Apps Transform Your Photos on Mobile Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-discord-updates-from-triggering-at-system-startup/"><u>Preventing Discord Updates From Triggering at System Startup</u></a></li>
<li><a href="https://windows11.techidaily.com/maintaining-constant-calc-display-in-windows/"><u>Maintaining Constant Calc Display in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-dism-error-code-0x800f082f-on-windows-systems/"><u>Resolving DISM Error Code: 0X800F082F on Windows Systems</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-how-to-integrate-titles-and-descriptions-into-your-youtube-video/"><u>[Updated] 2024 Approved  How to Integrate Titles and Descriptions Into Your YouTube Video</u></a></li>
<li><a href="https://windows11.techidaily.com/reimagining-your-pc-integrating-previous-apps-into-win-11/"><u>Reimagining Your PC: Integrating Previous Apps Into Win 11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-how-to-craft-powerful-tags-for-maximum-youtube-engagement/"><u>[New] How to Craft Powerful Tags for Maximum Youtube Engagement</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/vintage-film-effect-1920s-how-to-make-for-2024/"><u>Vintage Film Effect 1920S - How to Make for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-unleash-the-power-of-live-broadcast-recording-techniques-online/"><u>In 2024, Unleash the Power of Live Broadcast  Recording Techniques Online</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-enhance-copy-paste-efficiency-across-browsers/"><u>How to Enhance Copy-Paste Efficiency Across Browsers</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-the-nvidia-setup-not-available-glitch/"><u>Fixing the 'Nvidia Setup Not Available' Glitch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-time-display-on-windows-11-taskbar/"><u>Mastering Time Display on Windows 11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-shift-script-moving-windows-11-selected-files/"><u>Quick Shift Script: Moving Windows 11 Selected Files</u></a></li>
<li><a href="https://windows11.techidaily.com/initiating-chatgpt-with-windows-operating-system/"><u>Initiating ChatGPT with Windows Operating System</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/from-youtube-to-mp3-how-to-find-the-best-conversion-software/"><u>From YouTube to MP3 How to Find the Best Conversion Software</u></a></li>
<li><a href="https://video-capture.techidaily.com/top-5-innovative-mac-capturing-solutions-moving-past-bandicam-for-2024/"><u>Top 5 Innovative Mac Capturing Solutions, Moving Past Bandicam for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/full-guide-to-catch-100-iv-pokemon-using-a-map-on-tecno-spark-go-2024-drfone-by-drfone-virtual-android/"><u>Full Guide to Catch 100 IV Pokémon Using a Map On Tecno Spark Go (2024) | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-customize-and-reset-your-command-prompt/"><u>Guide to Customize and Reset Your Command Prompt</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-enhance-your-binge-watch-list-with-these-six-mac-methods-for-netflix-recording/"><u>2024 Approved  Enhance Your Binge-Watch List with These Six Mac Methods for Netflix Recording</u></a></li>
</ul></div>
