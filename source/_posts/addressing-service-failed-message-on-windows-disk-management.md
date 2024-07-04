---
title: Addressing 'Service Failed' Message on Windows Disk Management
date: 2024-07-03T11:19:51.748Z
updated: 2024-07-04T11:19:51.748Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing 'Service Failed' Message on Windows Disk Management
excerpt: This Article Describes Addressing 'Service Failed' Message on Windows Disk Management
keywords: Service Failure in Disk Manager,Windows Disk Error Fix,Manage Disk, Service Issue,Resolve Disk Service Errors,Windows Disk Services Problems,Stop 'Service Failed' Window,Addressing Disk Management Error
thumbnail: https://thmb.techidaily.com/606acaddc3ba9faf4d73376f1e2c554744034ba5ad463dfb82faf3689dc358c1.jpg
---

## Addressing 'Service Failed' Message on Windows Disk Management

 Disk Management is a Windows utility with which users can partition and rename drives. However, some users have reported this Windows error message pops up when they try to access Disk Management: “Disk Management could not start Virtual Disk Service (VDS).” A variation of that error message also says, “Unable to connect to Virtual Disk Service.”

 This error means users can’t access and utilize Disk Management. The issue more typically arises in remote connection environments. This is how you can fix the Disk Management Virtual Disk Service error in Windows 10 and 11\.

## 1\. Disconnect External Drives From Your PC

 First, try disconnecting all non-essential USB devices from your PC. Make sure there aren’t any external drives, USB sticks, mobile phones, or card readers connected to your PC. Then try [opening the Disk Management utility](https://www.makeuseof.com/ways-open-disk-management-windows-10/) again.

## 2\. Run System File and Image Repair Scans

 System file corruption could feasibly cause the Disk Management Virtual Disk Service error. So, check the integrity of system files on your PC with the Windows System File Checker command-line tool. That utility will also usually repair corrupted system files detected. This [how to run the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) guide includes instructions for utilizing that tool.

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command.jpg)

 If SFC detects corrupted system files but can’t repair them, you may need to run a Deployment Image Service Management scan. That’s a tool for fixing issues with the Windows system image. You can run that utility by executing this Deployment Image command within the Command Prompt:

`DISM /Online /Cleanup-Image /RestoreHealth`

## 3\. Enable and Run the Virtual Disk Service

 A disabled Virtual Disk service is a common cause of the Disk Management VDS error. Disk Management can’t connect to VDS when the Virtual Disk service is disabled. So, try enabling and running the Virtual Disk service like this:

1. To access Run, press **Win + R**.
2. Enter **services.msc** inside the Run command dialog and press **Return**.
3. Scroll down and double-click on **Virtual Disk** within the Services window.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/services-window.jpg)
4. Select the **Automatic** setting on the **Startup type** menu.  
![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/startup-type-drop-down-menu.jpg)
5. Press **Start** within the Virtual Disk Properties window.

1. Select the window’s **Log on** tab.
2. Next, click the **Allow service to interact with desktop** checkbox to select that option.  
![The Log On tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/log-on-tab.jpg)
3. Click **Apply** to save your new Virtual Disk service settings.
4. Select the Virtual Disk Properties window’s **OK** option.
5. If you encounter the Disk Management VDS error within a remote connection environment, repeat the above steps to check the Virtual Disk service is enabled on both the local and remote PCs.

## 4\. Allow Remote Volume Management Through Windows Defender Firewall

 Windows Defender Firewall can cause the Disk Management VDS error by blocking that utility from connecting with Virtual Disk. So, make sure Remote Volume Management is allowed through that firewall on both local and remote PCs. Our [guide to allowing apps through the Windows firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) includes instructions for applying this resolution.

![The allowed apps firewall settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/firewall-options.jpg)

## 5\. Turn Off Third-Party Security Software

 If your PC includes a third-party security (antivirus) app, that software could be blocking Disk Management from establishing a VDS connection. Remember that many third-party security apps also incorporate firewalls along with antivirus components. So, try temporarily disabling both the firewall and antivirus module within your third-party security software.

 To disable the firewall part, look for a turn-off firewall option within the settings tab of your antivirus software. You can usually turn off antivirus shields by right-clicking on security apps’ system tray icons and selecting disable options on their context menus. Select to turn off the antivirus shield for about an hour if you can, and try accessing Disk Management again to see if the issue persists.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

## Manage Your Drives With Disk Management Again

 The potential solutions in this guide aren’t totally guaranteed, but they’re the most likely ways to fix the Disk Management VDS error on a Windows PC. So, maybe one will get the Disk Management VDS issue sorted on your PC. Then you can manage and partition your drives with Disk Management again.

 This error means users can’t access and utilize Disk Management. The issue more typically arises in remote connection environments. This is how you can fix the Disk Management Virtual Disk Service error in Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/6-underestimated-downsides-of-saving-on-activation-keys/"><u>6 Underestimated Downsides of Saving on Activation Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-ms-sql-disconnects-malwarebytes-errors-in-1011-windows/"><u>Overcoming MS SQL Disconnects: Malwarebytes Errors in 10/11 Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-power-of-local-gpo-control-on-windows-11/"><u>Unlock the Power of Local GPO Control on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-resetting-rituals-the-ultimate-8/"><u>Windows Resetting Rituals: The Ultimate 8</u></a></li>
<li><a href="https://windows11.techidaily.com/diminishing-high-cpu-impact-of-tiworkerexe-applications/"><u>Diminishing High CPU Impact of TiWorker.exe Applications</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-through-samsung-flow-connected-life-for-devices/"><u>Navigate Through Samsung Flow - Connected Life for Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/swipe-to-learn-comparing-windows-10-ui-with-windows-11/"><u>Swipe to Learn: Comparing Windows 10 UI with Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/batch-processing-excellence-using-task-scheduler/"><u>Batch Processing Excellence Using Task Scheduler</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-unresponsive-windows-11-login-screens/"><u>Bypassing Unresponsive Windows 11 Login Screens</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-to-solutions-faster-configuring-shortcuts-for-win-1011-tools/"><u>Navigate to Solutions Faster: Configuring Shortcuts for Win 10/11 Tools</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-exploring-video-edits-is-inshot-top-choice/"><u>In 2024, Exploring Video Edits  Is InShot Top Choice?</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-ultimate-guide-to-gameplay-in-simulated-liquids/"><u>[Updated] Ultimate Guide to Gameplay in Simulated Liquids</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-making-yourself-laugh-with-snapchats-animated-filters/"><u>[New] In 2024, Making Yourself Laugh with Snapchat's Animated Filters</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-maintaining-digital-decorum-effective-techniques-for-filing-complaints-in-virtual-realms-like-discord/"><u>[New] Maintaining Digital Decorum  Effective Techniques for Filing Complaints in Virtual Realms Like Discord</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-master-guide-collages-creation-made-easy/"><u>[Updated] Master Guide  Collages Creation Made Easy</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-photobooth-playback-hang-up-seeking-solutions/"><u>2024 Approved  Photobooth Playback Hang-Up - Seeking Solutions</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/beginners-obs-techniques-for-youtube-live-streaming/"><u>Beginner's OBS Techniques for YouTube Live Streaming</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-tech-tips-streamlining-your-overwatch-video-recordings/"><u>[New] In 2024, Tech Tips  Streamlining Your Overwatch Video Recordings</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-champion-top-titles-best-free-video-caption-grabs/"><u>2024 Approved  Champion Top Titles  Best Free Video Caption Grabs</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-virtual-reality-use-in-healthcare/"><u>In 2024, Virtual Reality Use in Healthcare</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>