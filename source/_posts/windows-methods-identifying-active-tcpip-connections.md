---
title: "Windows Methods: Identifying Active TCP/IP Connections"
date: 2024-09-09T11:59:55.908Z
updated: 2024-09-10T11:59:55.908Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows Methods: Identifying Active TCP/IP Connections"
excerpt: "This Article Describes Windows Methods: Identifying Active TCP/IP Connections"
keywords: Windows TCP/IP Check,IP Connection Status,Windows Netstat Command,Tracking Active Network,TCP/IP Interface Monitor,Identify Network Connections (Windows),Detect Live TCP/IP Ports
thumbnail: https://thmb.techidaily.com/0ad1f89069cff4b2779ade10913206262c7bed58531552359326ac17834a5d8d.jpg
---

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134243/18498" target="_top" id="2134243">
  <img src="//a.impactradius-go.com/display-ad/18498-2134243" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134243/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Windows Methods: Identifying Active TCP/IP Connections

 Sometimes it's worth finding out which TCP/IP ports are open on your device. For example, let’s say your device is communicating with another PC, but the connection suddenly gets interrupted. In this case, you can check all the open TCP/IP ports. From there, you could try to resolve the issue at hand by troubleshooting any faulty port.

 This article covers the various ways to check active TCP/IP ports on Windows. But first, let’s find out how these ports work.

<!-- affiliate ads begin -->
<a href="https://bluettiit.sjv.io/c/5597632/2114267/17093" target="_top" id="2114267">
  <img src="//a.impactradius-go.com/display-ad/17093-2114267" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettiit.sjv.io/i/5597632/2114267/17093" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What Are TCP/IP Ports, and How Do They Work?

![An illustration of questions and answers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/An-illustration-of-questions-and-answers.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135398/19272" target="_top" id="2135398">
  <img src="//a.impactradius-go.com/display-ad/19272-2135398" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135398/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Let’s break down the “TCP/IP” term and explain what it means.

 TCP (Transmission Control Protocol) refers to a connection-oriented protocol. And in simple terms, protocols are the rules that determine how data is transferred between devices.

 Meanwhile, the "IP" (Internet Protocol) part refers to the internet protocol address. This is a unique value assigned to a network device, and it’s used to identify that particular device.

 Now, TCP/IP ports are simply the ports that ensure that all the data you send reaches its recipient. These ports ensure that internet-connected devices can communicate with each other. Some examples of TCP/IP ports include the IMAP port (143) for emails and the File Transfer Protocol ports (20 and 21).

 Let's now explore the various ways to check active TCP/IP ports.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123474/16836" target="_top" id="2123474">
  <img src="//a.impactradius-go.com/display-ad/16836-2123474" border="0" alt="https://techidaily.com" width="300" height="50"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123474/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Check the Open TCP/IP Ports and Their Process Names Using the Command Prompt

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

 When checking the TCP/IP ports that are open, you might also want to discover some additional information.

 For example, let’s say you want to check out active TCP/IP ports along with their process names. In such an instance, you can apply these methods:

1. Press **Win + R** to open the Run command dialog box.
2. Type **CMD** and press **Ctrl + Shift + Enter** to open an elevated Command Prompt.
3. Type the following command and press **Enter**.

netstat -ab

 The results will display four columns: **Proto, Local Address, Foreign Address,** and **State**.

![Checking the TCP-IP ports that are open](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/checking-the-tcp-ip-ports-that-are-open.jpg)

 The process names are the values displayed in square brackets below the port names.

 For example, you might see the “\[svchost.exe\]” process name under one of the TCP ports.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123478/16836" target="_top" id="2123478">
  <img src="//a.impactradius-go.com/display-ad/16836-2123478" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123478/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Check the Open TCP/IP Ports and the Process Identifiers Using the Command Prompt

![Person using a Windows PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/Person-using-a-Windows-PC.jpg)

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/2139563/4704" target="_top" id="2139563">
  <img src="//a.impactradius-go.com/display-ad/4704-2139563" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/2139563/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 In some instances, you might want to check out the TCP/IP ports along with their Process Identifiers (the unique numbers that identify processes). This method could be useful if you can’t find the process names using the previous method.

 When you’re done [searching for the Process Identifier (PID) on Windows](https://www.makeuseof.com/ways-to-find-application-process-id-in-windows-10/), you can check out the task name linked to the PID in the Task Manager.

 Let’s start by checking out how to check the open TCP/IP ports and their PIDs:

1. Press **Win + R** to open the Run command dialog box.
2. Type **CMD** and press **Ctrl + Shift + Enter** to open an elevated Command Prompt.
3. Type the following command and press **Enter**.

netstat -aon

 Your screen should display five columns: **Proto, Local Address, Foreign Address, State,** and **PID**.

![Checking TCP-IP ports and process identifiers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/checking-tcp-ip-ports-and-process-identifiers.jpg)

 Once you've found the PID of a certain port, here’s how you can use the Task Manager to find the task linked to that PID:

1. Type **Task Manager** in the Start menu search bar and select the **Best match**.
2. Navigate to the **Details** tab.
3. Look for your PID value in the **PID section** and locate the task name from the results on the left.

![Checking the PID value and task name on the Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/checking-the-pid-value-and-task-name-on-the-task-manager.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130889/7443" target="_top" id="2130889">
  <img src="//a.impactradius-go.com/display-ad/7443-2130889" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130889/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Check Which TCP/IP Ports Are Open Using Third-Party Apps

 If you’re a fan of third-party apps, here are some tools that can help you check active TCP/IP ports on your device.

### TCPView

![The TCPView Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-tcpview-tool.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135402/19272" target="_top" id="2135402">
  <img src="//a.impactradius-go.com/display-ad/19272-2135402" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135402/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The TCPView app shows a detailed list of all the [TCP and UDP (User Datagram Protocol) ports](https://www.makeuseof.com/what-are-tcp-and-udp-ports/). It also shows you the Process Name, Process IDs (PIDs), the Local Address, the Remote Address, the Local Port, the Remote Port, and more.

 You can customize the TCPView screen by clicking the **View** tab and selecting the relevant option.

 If you’d like to change the window to dark mode, head to the **Options** tab, select **Theme**, and then pick the **Dark** option. You can also tweak other settings (such as changing the font size) on the Options tab.

 And if you’d like to close one of the processes on the screen, select the process in question, click the **Process** tab, and then select the **Kill…** option.

 If you want to edit a process, click on the process in question, click the **Edit** tab, and then select the relevant option. And if you need some assistance, head to the **Help** tab.

**Download**: TCPView for [Windows](https://learn.microsoft.com/en-us/sysinternals/downloads/tcpview) (Free)

### CurrPorts

![The CurrPorts Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-currports-tool.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135413/19272" target="_top" id="2135413">
  <img src="//a.impactradius-go.com/display-ad/19272-2135413" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135413/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 CurrPorts almost looks similar to TCPView, but it has a couple of additional tabs that display critical information. For example, this tool also shows you the Process Path (file path), the Product Name, the File Description, and the File Version (for apps).

 The tool displays all the open TCP/IP and UDP ports on your PC.

 If you want to close some ports, highlight them and then click the “close” icon. To filter your results, click the “filter” icon, select your filter, and then click **OK**.

 If you want to search for specific ports, click the “find” icon, type the name of the port, and then click **Find Next**.

 To edit your ports, navigate to the **Edit** tab and then select the relevant option.

 If you want to customize the CurrPorts tool, click the **View** tab and select the relevant option. And if you want to discover more customization features, head to the **Options** tab.

**Download**: CurrPorts for [Windows](https://www.nirsoft.net/utils/cports.html) (Free)

### TCP Monitor Plus

![The TCP Monitor Plus Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-tcp-monitor-plus-tool.jpg)

 TCP Monitor Plus comprises 11 tabs that you can use for various purposes. But in this case, we’ll focus on the Session Monitor tab because that’s where the TCP/IP information is located.

 Once you’re on the Session Monitor tab, you should see various sections containing information about the TCP/IP ports. The "Status" tab tells you whether the ports are open or connecting. The other tabs display information such as the IP address, hostname, process name, and more.

 If you want to make changes to a specific port, right-click on it and select a relevant option.

**Download**: TCP Monitor Plus for [Windows](https://www.softpedia.com/get/Network-Tools/Network-Monitoring/TCP-Monitor-Plus.shtml) (Free)

## Finding All Your Active TCP/IP Ports Shouldn't Be Difficult

 Are you communicating with a remote computer but suddenly run into connection issues? Maybe the problem comes from TCP/IP ports. In this case, you can simply check which TCP/IP ports are open using the tips we’ve covered. From there, you can apply the relevant troubleshooting steps to fix the faulty port.

 And if you run into other problems while connecting to a remote device, check out some common remote desktop connection issues and their fixes.


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
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-first-look-at-organizing-zoom-session-rooms/"><u>[New] In 2024, First Look at Organizing Zoom Session Rooms</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-becoming-a-director-top-film-tips-and-tricks-on-youtube/"><u>[Updated] 2024 Approved Becoming a Director Top Film Tips & Tricks on YouTube</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-in-2024-innovative-8-cameras-transforming-online-broadcasting/"><u>[Updated] In 2024, Innovative 8 Cameras Transforming Online Broadcasting</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-trending-platforms-clash-a-look-at-tiktok-and-snaps-features/"><u>[Updated] Trending Platforms Clash A Look at TikTok & Snap's Features</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-convert-your-room-into-a-professional-studio-via-vlc/"><u>2024 Approved Convert Your Room Into a Professional Studio via VLC</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-talent-passes-for-independent-film-viewing/"><u>2024 Approved Talent Passes for Independent Film Viewing</u></a></li>
<li><a href="https://extra-information.techidaily.com/capture-striking-shots-using-leading-lines-iphone/"><u>Capture Striking Shots Using Leading Lines (iPhone)</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-crashed-epic-games-launcher-on-windows-systems/"><u>Fixing Crashed Epic Games Launcher on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-the-notorious-0xc00d36b4-windows-sound-issue/"><u>Fixing the Notorious 0XC00D36B4 Windows Sound Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/highlighting-the-superiority-win11-over-macos-details/"><u>Highlighting The Superiority: Win11 over MacOS Details</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-active-directory-domain-services-printer-error-in-windows-10-and-11/"><u>How to Fix the “Active Directory Domain Services” Printer Error in Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-revive-and-restart-stuck-spotify-on-w10w11-pcs/"><u>How to Revive and Restart Stuck Spotify on W10/W11 PCs</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-10-best-fake-gps-location-spoofers-for-vivo-y17s-drfone-by-drfone-virtual-android/"><u>In 2024, 10 Best Fake GPS Location Spoofers for Vivo Y17s | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-androids-compendium-for-synchronized-and-curved-videography/"><u>In 2024, Android's Compendium for Synchronized & Curved Videography</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-industrys-largest-uav-payload-carriers/"><u>In 2024, Industry's Largest UAV Payload Carriers</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-key-view-figures-for-earning-living-on-youtube/"><u>In 2024, Key View Figures for Earning Living on YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/insider-tips-for-manual-windows-security-scanning/"><u>Insider Tips for Manual Windows Security Scanning</u></a></li>
<li><a href="https://win-amazing.techidaily.com/mastering-excel-the-ultimate-techniques-for-labeling-your-cell-arrays/"><u>Mastering Excel: The Ultimate Techniques for Labeling Your Cell Arrays</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/mastering-the-music-merger-for-captivating-social-media-vids-for-2024/"><u>Mastering the Music Merger for Captivating Social Media Vids for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-of-images-on-the-lock-screen-on-or-off-windows-style/"><u>Mastery of Images on the Lock Screen: On or Off, Windows Style</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-graphics-drivers-a-windows-10-and-11-fixation/"><u>Navigating Graphics Drivers: A Windows 10 & 11 Fixation</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-steam-audio-latency-troubleshooting/"><u>Navigating Windows Steam Audio Latency Troubleshooting</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-the-anatomy-of-great-lower-thirds-a-guide-for-fcpx-editors/"><u>New 2024 Approved The Anatomy of Great Lower Thirds A Guide for FCPX Editors</u></a></li>
<li><a href="https://windows11.techidaily.com/optimal-6-tracking-applications-to-enhance-pc-productivity/"><u>Optimal 6 Tracking Applications to Enhance PC Productivity</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-0x80246007-update-obstacle-on-windows-1011/"><u>Overcoming 0X80246007 Update Obstacle on Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-cameras-unsaved-photos-hurdle/"><u>Overcoming Windows Camera's Unsaved Photos Hurdle</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-offline-printer-woes/"><u>Overcoming Windows' Offline Printer Woes</u></a></li>
<li><a href="https://windows11.techidaily.com/perfecting-pc-performance-set-active-hours-prevent-sudden-updates-on-windows-11/"><u>Perfecting PC Performance: Set Active Hours, Prevent Sudden Updates on Windows 11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/phantom-camera-pause-tips/"><u>Phantom Camera Pause Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/recovering-lost-access-to-windows-command-center/"><u>Recovering Lost Access to Windows Command Center</u></a></li>
<li><a href="https://windows11.techidaily.com/removing-aw-snap-from-your-chrome-browser-on-windows/"><u>Removing “Aw, Snap!” From Your Chrome Browser on Windows</u></a></li>
<li><a href="https://win-blog.techidaily.com/resolved-fixing-the-issue-of-minecraft-failure-during-setup-on-windows-11/"><u>Resolved: Fixing the Issue of Minecraft Failure During Setup on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-portaudio-faults-in-audacity-for-windows-1111-os/"><u>Resolving PortAudio Faults in Audacity for Windows 11/11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-workflow-excellent-screen-savers-with-clock-features/"><u>Seamless Workflow: Excellent Screen Savers with Clock Features</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-the-windows-search-interface-no-graphics/"><u>Simplifying the Windows Search Interface: No Graphics</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-icon-cache-revival-in-win10win11/"><u>Techniques for Icon Cache Revival in Win10/Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-core-skills-for-conquering-classic-diablos-world/"><u>The Core Skills for Conquering Classic Diablo's World</u></a></li>
<li><a href="https://some-tips.techidaily.com/the-essential-iphone-hdr-photography-skills-for-2024/"><u>The Essential iPhone HDR Photography Skills for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-overwatch-2-renderer-issues-on-windows/"><u>Troubleshooting Overwatch 2 Renderer Issues on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-the-power-of-windows-11-taskbar-for-maximum-output/"><u>Unleash the Power of Windows 11 Taskbar for Maximum Output</u></a></li>
<li><a href="https://unlock-android.techidaily.com/unlocking-the-power-of-smart-lock-a-beginners-guide-for-xiaomi-redmi-a2plus-users-by-drfone-android/"><u>Unlocking the Power of Smart Lock A Beginners Guide for Xiaomi Redmi A2+ Users</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-1011-old-login-logon-error/"><u>Unlocking Windows 10/11: Old Login Logon Error</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11-access-a-step-by-step-guide/"><u>Unlocking Windows 11 Access: A Step-by-Step Guide</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unraveling-the-mystery-of-your-ps4s-colorful-led-meanings-behind-blue-white-red-orange-alerts/"><u>Unraveling the Mystery of Your PS4's Colorful LED: Meanings Behind Blue, White, Red, Orange Alerts</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-copilot-microsofts-ai-code-companion/"><u>Unveiling Copilot: Microsoft's AI Code Companion</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-ftdibussys-the-enigma-of-memory-standards-violation/"><u>Unveiling ftdibus.sys: The Enigma of Memory Standards Violation</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-methods-for-vanished-folder-recovery-on-windows/"><u>Unveiling Methods for Vanished Folder Recovery on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secrets-of-microsoft-family-safety/"><u>Unveiling the Secrets of Microsoft Family Safety</u></a></li>
<li><a href="https://windows11.techidaily.com/websites-as-apps-step-by-step-windows-installation/"><u>Websites as Apps: Step-by-Step Windows Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/winvolume-fix-resetting-saving-settings-for-audio/"><u>WinVolume Fix: Resetting Saving Settings for Audio</u></a></li>
</ul></div>