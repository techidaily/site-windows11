---
title: Deciphering Win Errors Post-BSOD on Modern OSes
date: 2024-07-11T22:23:39.848Z
updated: 2024-07-12T22:23:39.848Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Deciphering Win Errors Post-BSOD on Modern OSes
excerpt: This Article Describes Deciphering Win Errors Post-BSOD on Modern OSes
keywords: BSOD Fix Guide,Win Error Solutions,OS Crash Recovery,Windows Diagnostic Tricks,Post-Error Boot Help,System Crash Analysis,Modern OS Blue Screen
thumbnail: https://thmb.techidaily.com/8dc1e121faf37e853cf5b4a2c9e429100f4acf86a44ca231431cd5b1e8fdd239.jpg
---

## Deciphering Win Errors Post-BSOD on Modern OSes

 When your computer crashes and you face a Blue Screen of Death (BSOD), your system saves the details of the crash as a BSOD log, in a pre-defined location in Windows. This information gives you details about when the crash happened, what caused it, and sometimes even what to do to fix the problem.

 In this guide, we will first discuss where are the BSOD files located in Windows and then how to identify them. Once you have located a BSOD file, we will show you how to read it properly to understand the potential causes of the error and resolve the problem.

## Where Are the BSOD Log Files Located in Windows?

 You can find the BSOD log files in the Event Viewer, Control Panel, and Registry Editor in Windows. Below, we have listed the detailed steps for finding these files in all three of these utilities.

### 1\. Find and Read the BSOD Log Files in the Event Viewer

 The Event Viewer is a tool developed by Microsoft for users to view system and program-related events in Windows. These events can include system errors, warnings, informational messages, and more. In other words, every issue you encounter (whether a minor glitch or a major crash) will be logged in the Event Viewer for later investigation and sharing with Microsoft.

 You can check out our detailed guide on [what the Event Viewer is and how it can be useful](https://www.makeuseof.com/windows-event-viewer-guide/) if you are unfamiliar with it.

 Here is how you can find the BSOD log files in the Event Viewer:

1. Right-click on the Windows icon in the taskbar and choose **Event Viewer** from the context menu.  
![Choose Event Viewer in the context menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/event-viewer.jpg)
2. Head over to the **Action** menu located at the top, and choose **Create Custom View** from the context menu.  
![Create a custom view in the Event viewer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/create-custom-view.jpg)
3. In the following dialog, expand the dropdown for **Logged** and choose the time when you encountered the issue.  
![Check the logged section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/custom-time.jpg)
4. Now, move to the Event Level section and choose **Error**.  
![Event level of the error](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/error-event-level.jpg)
5. Expand the dropdown for **Event Logs** and checkmark the box for **Windows Logs**.  
![Choose Windows logs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/windows-logs.jpg)

1. Click **OK** to proceed.
2. You will now be prompted to enter a name and description for the custom view you just created. Enter these details and click **OK**.  
![Create a filter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/name-event-viewer.jpg)
3. Once the view is created, you will be presented with a list of errors that occurred during the time frame you selected earlier. You can sort this information further in the Date and time section.  
![Check the Event Viewer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/event-viewer-11.jpg)
4. Next, locate the BSOD using details like the date and time again.
5. Once you find the targeted log, click on it.
6. Check both the General and Details tabs to get information about this error.

 Once you find the error code associated with the crash and the cause, you can look for solutions online, or head over to our guide that discusses [how to fix blue screen errors in Windows](https://www.makeuseof.com/tag/4-tips-fix-blue-screen-error/) if it's a bsod.

### 2\. Find and Read the BSOD Log Files in the Registry Editor

 In case using the Event Viewer does not work for you for some reason, you can use another Windows utility to locate and study the BSOD log files—the Registry Editor.

 Windows Registry Editor is an administrative-level utility that lets you control how Windows operates and interacts with hardware and software. The Registry stores information related to the hardware and software components of your system. This information in the Registry is stored in the form of keys and values, and by modifying these with the dedicated Registry Editor, you can customize the operations of your system.

 Listed below are the steps for finding the BSOD log files in the Registry Editor. Make sure you are logged into your system as an administrator before you proceed.

1. Press the **Win + R** keys to open Run.
2. Type "regedit" in Run and press **Ctrl + Shift + Enter** to launch the Registry Editor as an administrator.
3. Now, select **Yes** in the User Account Prompt.
4. Once you are inside the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\System\CurrentControlSet\Control\CrashControl`
5. Next, move to the right pane and right-click on an empty space anywhere.
6. Choose **New** \> **DWORD (32-bit) Value**.  
![Create a new DWORD value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/dword-policies.jpg)
7. Name this value as **DisplayParameters** and double-click on it.
8. Under Value data, type 1 and click **OK**.  
![Change the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/value-data-1.jpg)
9. Once done, restart your PC.

 Upon reboot, you should be able to view the log files without any problems.

### 3\. Find and Read the BSOD Log Files in the Control Panel

 The third way of finding and reading the BSOD log files is via the Control Panel. This approach offers a graphical representation of the log files using the Windows Reliability Monitor, unlike the methods we have explored previously.

 The Reliability Monitor, which is different than the Performance Monitor (see [Reliability Monitor vs. Performance Monitor](https://www.makeuseof.com/reliability-monitor-vs-performance-monitor/)) will show you a timeline of important system events that occurred on your computer including BSOD occurrences, software installations, application crashes, and other relevant events.

 Here is how you can use it to identify and fix problems that may affect your system:

1. Type Control Panel in the search area of the taskbar and click **Open**.
2. In the following window, choose **System and Security** \> **Security and Maintenance**.  
![Security and maintenance settings in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/security-maintenance.jpg)
3. Click on **Maintenance** and then select **View reliability history**.  
![Check the reliability history of the system](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/view-realability-history.jpg)
4. You should now see a graph showing the reliability data. Look for red cross icons and blue (i) icons in the graph, as they show problematic events.  
![Reliability graph](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/realability-graph.jpg)
5. Click on each of the icons to view its details. Keep repeating the process to locate the event you are looking for.

 You will be presented with information like the faulting application path, its name, fault module timestamp, exception code, etc. If this app caused a BSOD crash, then you can try ending its process via the Task Manager or uninstalling the app if it is not necessary.

 It is also a good idea to copy this information and send it to Microsoft for review if you cannot find a solution online.

## Learn How to Read Your BSOD Log Files and Resolve Your Crashes

 ​​​​​​Windows blue screen errors are nothing new, but since they only display messages like "Your PC encountered a problem" without describing the cause, it can be difficult to find a fix. Understanding how to read BSOD log files can not only help you identify the exact cause of the problem but also help you find the right solution.

 Whenever a component causes your system to crash, you can disable it and switch to a better alternative to avoid the problem.

 In this guide, we will first discuss where are the BSOD files located in Windows and then how to identify them. Once you have located a BSOD file, we will show you how to read it properly to understand the potential causes of the error and resolve the problem.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-to-rectifying-windows-11-search-issues/"><u>Comprehensive Guide to Rectifying Windows 11 Search Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/concealing-windows-11s-taskbar-search-function/"><u>Concealing Windows 11'S Taskbar Search Function</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-in-2024-exploring-google-play-music-and-its-podcast-feature-functionality/"><u>Updated In 2024, Exploring Google Play Music and Its Podcast Feature Functionality</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/elite-zero-cost-fb-picturemovie-composer-for-2024/"><u>Elite Zero-Cost FB Picture/Movie Composer for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-dealing-with-steam-installation-fiascos-win11-style/"><u>Decoding and Dealing with Steam Installation Fiascos, Win11-Style</u></a></li>
<li><a href="https://extra-support.techidaily.com/seamless-audio-prime-websites-for-turning-video-melodies-into-sound-effects-for-2024/"><u>Seamless Audio  Prime Websites for Turning Video Melodies Into Sound Effects for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/command-the-past-mastering-file-history-navigation/"><u>Command the Past: Mastering File History Navigation</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-audio-transformation-from-instagram-visuals-mp3/"><u>[New] 2024 Approved  Audio Transformation From Instagram Visuals (MP3)</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-exploring-vidma-revolutionizing-the-recording-industry/"><u>[New] Exploring Vidma  Revolutionizing the Recording Industry</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-innovative-social-media-tag-trackers-facebook-tweet-and-instagram/"><u>[New] In 2024, Innovative Social Media Tag Trackers  Facebook, Tweet & Instagram</u></a></li>
<li><a href="https://windows11.techidaily.com/dealing-with-non-selectable-items-in-win11-setup/"><u>Dealing with Non-Selectable Items in Win11 Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-blue-screen-errors-through-microsofts-tools-in-w11/"><u>Demystifying Blue Screen Errors Through Microsoft's Tools in W11</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-2024-approved-step-by-step-process-to-create-big-heads-on-your-tiktok-content-3-methods/"><u>[New] 2024 Approved  Step-By-Step Process to Create Big Heads on Your TikTok Content (3 Methods)</u></a></li>
<li><a href="https://windows11.techidaily.com/direct-methods-to-remove-a-peevous-print-spooler/"><u>Direct Methods to Remove a Peevous Print Spooler</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/premier-call-customization-and-editing-software/"><u>Premier Call Customization and Editing Software</u></a></li>
<li><a href="https://windows11.techidaily.com/concealing-windows-firewall-areas-a-step-by-step-guide/"><u>Concealing Windows Firewall Areas: A Step-by-Step Guide</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/downloading-insta-videos-in-two-simple-ways-for-2024/"><u>Downloading Insta Videos in Two Simple Ways for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-windows-cab-and-its-method-for-installed-content/"><u>Deciphering Windows CAB & Its Method for Installed Content</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-updates-fault-0x8019/"><u>Clearing Updates Fault 0X8019</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-without-backup-on-lava-blaze-2-5g-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to recover deleted photos from Android Gallery without backup on Lava Blaze 2 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/cybersecurity-commandments-winning-access-prevention-on-windows/"><u>Cybersecurity Commandments: Winning Access Prevention on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/command-your-computer-mastery-of-windows-through-alomware/"><u>Command Your Computer: Mastery of Windows Through AlomWare</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-six-innovative-approaches-for-recording-and-storing-mov-files-on-windows-11/"><u>In 2024, Six Innovative Approaches for Recording and Storing MOV Files on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-complexity-of-wintoys-your-guide-to-a-versatile-tool/"><u>Decoding the Complexity of 'WinToys': Your Guide to a Versatile Tool</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-can-we-bypass-xiaomi-redmi-note-12-5g-frp-by-drfone-android/"><u>How Can We Bypass Xiaomi Redmi Note 12 5G FRP?</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-inspiring-abodes-for-minifigure-residences/"><u>[Updated] 2024 Approved  Inspiring Abodes for Minifigure Residences</u></a></li>
<li><a href="https://windows11.techidaily.com/dive-into-customization-windows-11s-potential-unlocked/"><u>Dive Into Customization: Windows 11'S Potential Unlocked</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-initiate-into-a-tiktok-live-with-ease/"><u>[Updated] Initiate Into a TikTok Live with Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/controlling-heat-levels-on-your-windows-11-pc/"><u>Controlling Heat Levels on Your Windows 11 PC</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-the-clutter-soundcard-irq-solutions/"><u>Cutting the Clutter: Soundcard IRQ Solutions</u></a></li>
<li><a href="https://fake-location.techidaily.com/fixing-foneazy-mockgo-not-working-on-realme-narzo-60-pro-5g-drfone-by-drfone-virtual-android/"><u>Fixing Foneazy MockGo Not Working On Realme Narzo 60 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-dual-users-fixing-their-windows-account-error/"><u>Clearing Up Dual Users: Fixing Their Windows Account Error</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-premier-virtual-microphones-for-2024/"><u>[Updated] Premier Virtual Microphones for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/custom-menus-on-windows-1111-with-psoft-tools/"><u>Custom Menus on Windows 11/11 with PSoft Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/dealing-with-ios-photos-import-errors-on-windows-devices/"><u>Dealing with iOS Photos Import Errors on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-windows-ram-allocation-strategies/"><u>Deciphering Windows' RAM Allocation Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/covert-communication-techniques-secure-file-exchanges-on-windows/"><u>Covert Communication Techniques: Secure File Exchanges on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/decreasing-visual-noise-windows-11-tab-control/"><u>Decreasing Visual Noise: Windows 11 Tab Control</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-disabled-copy-operation-on-windows-11/"><u>Overcoming Disabled Copy Operation on Windows 11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/improving-online-sessions-with-increased-zoom-for-2024/"><u>Improving Online Sessions with Increased Zoom for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-ultimate-win10-strategy-for-successful-zoom-sessions/"><u>[New] The Ultimate Win10 Strategy for Successful Zoom Sessions</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-significance-of-windows-subsystem-for-linux-error-4294967295/"><u>Deciphering the Significance of Windows Subsystem for Linux Error 4294967295</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-5-car-locator-apps-for-oppo-find-x6-drfone-by-drfone-virtual-android/"><u>In 2024, Top 5 Car Locator Apps for Oppo Find X6 | Dr.fone</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-a-complete-beginners-guide-to-tiktok-on-mac/"><u>[Updated] A Complete Beginner's Guide to TikTok on Mac</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-windows-11s-failed-device-connection-attempts/"><u>Correcting Windows 11'S Failed Device Connection Attempts</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-disconnect-adjustable-gif-sizes-for-discord-on-windows/"><u>Deciphering Disconnect: Adjustable GIF Sizes for Discord on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-inadvertent-launches-of-ms-storeapp/"><u>Disabling Inadvertent Launches of MS StoreApp</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-making-funny-photos-no-fees-involved-for-2024/"><u>[New] Making Funny Photos  No Fees Involved for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-the-secret-to-smoothly-controlling-your-touchpad-in-windows-11/"><u>Discover the Secret to Smoothly Controlling Your Touchpad in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/detailed-steps-for-running-sfc-in-windows-os/"><u>Detailed Steps for Running SFC in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/direct-routes-to-windows-11s-user-authorization-screen/"><u>Direct Routes to Windows 11'S User Authorization Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-windows-arp-caches-made-simple/"><u>Clearing Windows ARP Caches Made Simple</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-instagram-to-tiktok-the-ultimate-connector/"><u>[Updated] Instagram to TikTok  The Ultimate Connector</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-cutting-edge-converters-the-premier-5-audio-video-mixers-for-optimal-integration/"><u>New Cutting-Edge Converters The Premier 5 Audio Video Mixers for Optimal Integration</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-the-runtime-broker-its-job-in-computing-architecture/"><u>Dissecting the Runtime Broker: Its Job in Computing Architecture</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>