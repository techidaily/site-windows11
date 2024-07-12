---
title: "Stop Error: Non-Compliant Windows Generic Audio Problems"
date: 2024-07-11T21:37:36.355Z
updated: 2024-07-12T21:37:36.355Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Stop Error: Non-Compliant Windows Generic Audio Problems"
excerpt: "This Article Describes Stop Error: Non-Compliant Windows Generic Audio Problems"
keywords: Windows Error Fixing,Compliant Audio Windows,Stop Windows Audio Issue,Resolve Non-Compliant Audio,Generic Audio Windows Error,Correct Windows Sound Problems,Eliminate Audio Glitches in Win
thumbnail: https://thmb.techidaily.com/6cb4391f5b78a0bded981255e816f25b4a4f4175f4c2d7396281a9558ff75db1.jpg
---

## Stop Error: Non-Compliant Windows Generic Audio Problems

 It’s advisable to safely eject a USB drive inserted in your Windows 11/10 PC. However, upon doing so, some users report seeing an error message that reads “Windows can’t stop your generic volume device.” Consequently, users can’t safely eject USB drives with their PCs on.

 Of course, you can still safely remove a USB drive with a PC off. However, many users still prefer to be able to safely eject their connected drives without shutting down their computer. This is how you can fix the “Windows can’t stop your generic volume device” error.

## 1\. Disable Background App Processes

 Disabling background app processes is the first thing you should try when you see the “Windows can’t stop your generic volume device” error. Even the error message suggests closing programs that could still be using the device.

 Make sure there aren’t any minimized software windows on your taskbar; close unneeded apps within the system tray area by right-clicking their icons and selecting exit options.

![System tray icons](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/system-tray-programs.jpg)

 Beyond the taskbar and system tray, you’ll need to look for and disable background app processes with Task Manager. Task Manager is a tool that provides a comprehensive overview of app and service background processes.

 Our guide on [fixing too many background processes running](https://www.makeuseof.com/windows-pc-too-many-background-processes/) provides more detail on how to terminate unneeded background apps and services with Task Manager.

## 2\. End and Restart the Windows Explorer Process

 Some users confirm ending and restarting the File Explorer process fixes the “Windows can’t stop your generic volume device” error. That highlights File Explorer is causing the error and needs to be stopped from utilizing the USB drive.

 Follow these steps to end and restart File Explorer:

1. Right-click a taskbar space and select the **Task Manager** context menu option.
2. Scroll down the **Processes** tab in Task Manager until you see Windows Explorer.
3. Right-click Windows Explorer and select **End task**. Your desktop will go blank, but restarting Explorer will restore it.  
![The End task option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/end-task-option.jpg)
4. Click Task Manager’s **File** menu.
5. Select **Run new task** on the menu.
6. Then input **explorer** in Create new task.  
![The Create a new task tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-create-a-new-task-window.jpg)
7. Select **Create this task with administrative privileges**.
8. Click **OK** to restart Explorer.

## 3\. Troubleshoot the Device

 You can troubleshoot a USB device by running the Hardware and Devices troubleshooter with the drive connected. That troubleshooter might address some drive ejection issues.

 The Hardware and Devices troubleshooter isn’t listed in Settings. However, you can still find and use it by opening it via the Command Prompt using these steps:

1. Press **Windows** key **+** **S** to activate a file search tool, and input Command Prompt within its text box.
2. Select **Command Prompt** to open it from the search results.
3. Input and execute this Hardware and Devices command:  
`msdt.exe -id DeviceDiagnostic`  
![The Hardware and Devices troubleshooter command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hardware-and-devices-troubleshooter.jpg)
4. Click **Next** to run the troubleshooting tool.  
![The Hardware and Devices troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hardware-and-devices-troubleshooter4.jpg)
5. The troubleshooter might ask you to select a device. If it does, select your connected USB storage device.  
![A USB Attached option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/usb-attached-option.jpg)
6. Click **Apply this fix** if the Hardware and Devices troubleshooter suggests a resolution.

## 4\. Select the Quick Removal Option

 Selecting the **Quick Removal** option is another confirmed fix for the “Windows can’t stop your generic volume device” error. The **Quick Removal** option disables write caching. You can select the **Quick Removal** option for an affected drive using the following steps:

1. Click File Explorer’s taskbar shortcut and select This PC.
2. Right-click your USB drive and select **Properties**.
3. Click the **Hardware** tab.  
![The Hardware tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-hardware-tab.jpg)
4. Then press the **Properties** button.
5. Click **Change settings** to bring up another window.  
![The Change settings button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-settings-button.jpg)
6. Select **Policies** in the second window.
7. Then click the **Quick removal (default)** option.  
![The Quick removal radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/quick-removal-option.jpg)
8. Select **OK** to exit the device properties window.

## 5\. Deselect the Index Drive Setting

 Having file indexing enabled for an external USB drive can cause the “Windows can’t stop your generic volume” error. If that option is enabled, files copied onto your USB drive will be indexed, which can keep it in use for some time after transferring lots of files onto it.

 Follow these steps to deselect indexing for a USB drive:

1. Go to This PC in File Explorer.
2. Right-click the USB drive connected and select **Properties**.
3. Deselect the **Allow files on this drive to have contents indexed in addition to file properties** option.  
![The Allow files on this drive to have contents indexed box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/index-option.jpg)
4. Select **Apply** and **OK** to set the drive’s new setting.

## 6\. Set the Connected USB Drive to Be in Offline Mode

 A lot of users have fixed the “Windows can’t stop your generic volume device” error by setting their USB drives into offline mode. So, try setting your connected USB drive to offline mode with the DiskPart command-line line tool using these steps:

1. Press the **Windows** logo + **R** key combo for activating Run.
2. Input **cmd** into Run, and press **Ctrl** \+ **Shift** \+ **Enter** to [open Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
3. Then input this Diskpart command and hit **Enter**:  
`diskpart`
4. To view a drive list, input the following text and press **Return**:  
`list disk`  
![The diskpart command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/list-disk-command.jpg)
5. Next, execute this command to select your USB drive:  
`select disk <drive number>`
6. Finally, set the selected disk to offline by executing this command:  
`offline disk`  
![The offline command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/offline-command.jpg)

 You will need to replace **<drive number>** for the select disk command with the actual number of your USB drive listed by Diskpart. For example, if your USB drive is disk 1, the required command would look like this:

`select disk 1`

 Setting a drive offline changes its status to missing. You can set the same drive back to an online status by repeating steps one to five above and then executing this command:

`online disk`

## 7\. Assign a Different Letter to the USB Drive

 Some users have also resolved the “Windows can’t stop your generic volume device” by changing the letters of their USB drives. Assigning a different letter to a USB drive will disconnect it from certain processes.

 You can even change the drive letter back to what it originally was another time. To apply this fix, check out this [guide to changing a drive’s letter in Windows](https://www.makeuseof.com/tag/change-drive-letter-windows/).

![The Disk Management tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disk-management-window.jpg)

## Safely Eject Your USB Drive

 Removing a USB drive from a PC without safely ejecting it can corrupt the data on it. So, it’s not a good idea to ignore the “Windows can’t stop your generic volume device” error.

 Applying the potential solutions covered here will resolve the error for most users. Then, you can safely remove your USB drive in Windows 11/10 with alternative methods.

 Of course, you can still safely remove a USB drive with a PC off. However, many users still prefer to be able to safely eject their connected drives without shutting down their computer. This is how you can fix the “Windows can’t stop your generic volume device” error.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/fix-unresponsive-f-keys-troubleshooting-in-windows-11-os/"><u>Fix: Unresponsive F Keys - Troubleshooting in Windows 11 OS</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-reverse-viewing-crafts-creative-youtube-video-methods/"><u>2024 Approved  Reverse Viewing Crafts  Creative Youtube Video Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tuning-fn-keys-windows-10-and-11-techniques/"><u>Fine-Tuning FN Keys: Windows 10 and 11 Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/granting-correct-permissions-to-solve-windows-installer-error/"><u>Granting Correct Permissions to Solve Windows Installer Error</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ing-allure-in-online-visuals-for-beauty/"><u>Crafting Allure in Online Visuals for Beauty</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-air-vs-pro-with-m1-optimal-laptop-for-your-needs/"><u>[Updated] Air Vs. Pro with M1  Optimal Laptop for Your Needs?</u></a></li>
<li><a href="https://windows11.techidaily.com/empowering-your-system-bypass-tpm-and-secure-boot-via-rufus/"><u>Empowering Your System: Bypass TPM & Secure Boot via Rufus</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-expert-analysis-on-slomo-video-softwares-performance/"><u>2024 Approved  Expert Analysis on SloMo Video Software's Performance</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-quickscreencapture-mastery-for-everyday-use/"><u>[New] In 2024, QuickScreenCapture Mastery for Everyday Use</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-unresponsive-clicks-with-these-fixes/"><u>Conquer Unresponsive Clicks with These Fixes</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-how-to-tutorials-of-kapwing-collage-maker/"><u>Updated How-To Tutorials of Kapwing Collage Maker</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-to-use-pokemon-emerald-master-ball-cheat-on-samsung-galaxy-f54-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Use Pokémon Emerald Master Ball Cheat On Samsung Galaxy F54 5G | Dr.fone</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/2024-approved-the-ultimate-guide-to-establishing-a-twitter-presence/"><u>2024 Approved  The Ultimate Guide to Establishing a Twitter Presence</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-system-diagnostics-a-guide-to-windows-ping-usage/"><u>Enhancing System Diagnostics: A Guide to Windows Ping Usage</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-steps-to-prevent-and-resolve-onedrive-errors-on-your-pc/"><u>Essential Steps to Prevent and Resolve OneDrive Errors on Your PC</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-adding-emojis-in-youtube-discussions/"><u>[Updated] In 2024, Adding Emojis in YouTube Discussions</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-sharing-errors-with-nvidias-gui/"><u>Fixing Sharing Errors with NVIDIA's GUI</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-dismantling-the-win10-blue-screen/"><u>Decoding and Dismantling the Win10 Blue Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-windows-11-quality-first-fun-second/"><u>Elevating Windows 11: Quality First, Fun Second</u></a></li>
<li><a href="https://windows11.techidaily.com/fast-track-favorites-windows-11-shortcuts-for-uwp-apps/"><u>Fast-Track Favorites: Windows 11 Shortcuts for UWP Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-ftdibussys-explaining-its-effect-on-memory-security/"><u>Deciphering ftdibus.sys: Explaining Its Effect on Memory Security</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/2024-approved-online-photo-editing-best-free-background-blur-software/"><u>2024 Approved Online Photo Editing Best Free Background Blur Software</u></a></li>
<li><a href="https://windows11.techidaily.com/ensure-peaceful-navigation-maintain-stability-in-windows-net/"><u>Ensure Peaceful Navigation: Maintain Stability in Windows Net</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-techniques-for-altering-credentials-on-windows-11/"><u>Easy Techniques for Altering Credentials on Windows 11</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-screen-capture-mastery-windows-edition-free-3-methods/"><u>[New] Screen Capture Mastery  Windows Edition (Free, 3 Methods)</u></a></li>
<li><a href="https://windows11.techidaily.com/executing-policies-for-a-single-user-target-in-modern-windows-systems/"><u>Executing Policies for a Single-User Target in Modern Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/dial-up-speed-strategies-to-revive-your-sluggish-pc/"><u>Dial Up Speed: Strategies to Revive Your Sluggish PC</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/process-of-screen-sharing-samsung-galaxy-f14-5g-to-pc-detailed-steps-drfone-by-drfone-android/"><u>Process of Screen Sharing Samsung Galaxy F14 5G to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/averting-self-triggered-openings-on-msdnstoreapp/"><u>Averting Self-Triggered Openings on MSDN/StoreApp</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-misconfigured-duo-apps-on-windows/"><u>Addressing Misconfigured Duo Apps on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/explore-safest-windows-free-software-hubs/"><u>Explore Safest Windows Free Software Hubs</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-macos-with-cross-operating-system-tools/"><u>Elevating macOS with Cross-Operating System Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/dealing-with-interrupt-at-breakpoint-issue-in-windows-debugging/"><u>Dealing with Interrupt at Breakpoint Issue in Windows Debugging</u></a></li>
</ul></div>
