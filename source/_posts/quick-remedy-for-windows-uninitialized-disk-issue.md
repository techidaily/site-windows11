---
title: Quick Remedy for Windows 'Uninitialized' Disk Issue
date: 2024-07-11T21:37:28.831Z
updated: 2024-07-12T21:37:28.831Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quick Remedy for Windows 'Uninitialized' Disk Issue
excerpt: This Article Describes Quick Remedy for Windows 'Uninitialized' Disk Issue
keywords: Fix Uninit Drives,Windows Disk Initialization,Quick Disk Repair,Resolve Disk Errors,Win OS Data Loss Prevention,Immediate Disk Fix,Stop 'Uninitialized' Issue
thumbnail: https://thmb.techidaily.com/7989d193b701c6c4112afd659656de357f20d61f1ee9fa4b40235e3cbfd62f11.jpg
---

## Quick Remedy for Windows 'Uninitialized' Disk Issue

 Does Disk Management display the message "Disk Unknown, Not Initialized" when you connect an external drive, an SSD, an HDD, or a pen drive to your computer? The issue occurs primarily due to MBR corruption. However, incorrectly connecting the drive to your system, bad disk sectors, data corruption, and a failing hard drive can also trigger the error.

 If you want to resolve this issue and successfully load the data, here are a few fixes you should try.

## 1\. Check for Connection Issues

![USB cable plugged into a laptop's USB port](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/laptop-and-usb-cable.jpg)

 Check for possible connection issues between the hard drive and your computer before investigating any other causes. To start, unplug and re-plug the hard drive into your laptop to eliminate any temporary connection problems.

 In addition, make sure the hard drive's connection cable is intact and there is no visible damage to any part of it. Also, clean both ends of the cable with a cloth to ensure no dust or debris is stuck inside them, preventing the disk from initializing.

 If none of the above temporary issues appear to be the culprit, look for possible port issues.

## 2\. Ensure Your USB Port Isn't Faulty

![Close-up picture of a Laptop’s USB ports](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/pexels-castorly-stock-4065705.jpg)

 A faulty USB port can also prevent your system from detecting the hard drive, resulting in the issue under discussion. Hence, it's imperative to ensure that the USB port is functioning correctly. To confirm that, just swap ports, i.e., plug the external drive into a different port than where it was connected before.

 If the external drive starts working immediately after switching ports, the port it was connected to earlier is either incompatible with your drive or has a problem. Thus, you should either keep using the other USB port or apply the fixes covered in our guide on [how to fix USB port issues on Windows](https://www.makeuseof.com/tag/dead-usb-port-heres-how-to-diagnose-and-fix-it/) to make the faulty port work again.

## 3\. Scan and Resolve Hard Drive Issues

 If there is no connection issue and your USB port is functioning correctly, you should scan and fix file system issues with your hard drive. Windows offers a utility named CHKDSK, which assesses the file system structure, addresses file name linkage issues, and looks for bad clusters, among other operations. Usually, running this utility fixes hard drive problems.

 Before running the scan, open the File Explorer and find the drive letter marked as **disk unknown, not initialized**. After you have that in mind, follow these steps:

1. In Windows Search, enter **"cmd,"** right-click on the **Command Prompt** app, and select **Run as administrator**.
2. Type the following command in Command Prompt and press **Enter**:  
`Chkdsk <drive letter>: /r /f`

![Scanning the Bad Disk Sectors Using the CHKDSK Command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/scanning-the-bad-disk-sectors-using-the-chkdsk-command-in-command-prompt.jpg)

 Ensure you enter the correct drive letter for the scan to work.

## 4\. Update the Disk Drive Drivers

 Having outdated drivers can also disrupt the normal functioning of your disk drive, making it impossible for it to initialize. To ensure that's not the cause of the issue, you should update the disk drive drivers. Here are the steps you need to take:

1. Right-click on the Windows **Start** button and open **Device Manager**.
2. Expand the **Disk drives** category.
3. Right-click on your desired drive and click **Update driver**.  
![updating the disk drive drivers in the device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/updating-the-disk-drive-drivers-1.jpg)

## 5\. Rebuild the MBR

 If the above fixes do not resolve the issue, rebuild the MBR, which is a boot sector at the beginning of the hard drive. When it gets corrupted, you're likely to encounter problems. You can rebuild the MBR in several ways, but using a third-party app like Minitool Partition Wizard is the easiest. Here are the steps you should follow:

1. Go to [MiniTool's official website](https://www.partitionwizard.com/download.html) and download the **MiniTool Partition Wizard**.
2. Install the software by running the setup file and following the on-screen instructions. You don't need to buy the premium edition; the free version will do the job.
3. Once installed, search for **"MiniTool Partition Wizard"** in Windows Search, and then run the app.
4. Right-click on the problematic disk and select **Initialize to MBR Disk**. Then, click **Apply**.  
![Click on Initialize to MBR Disk in the MiniTool Partition Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/click-on-initialize-to-mbr-disk-in-the-minitool-partition-wizard.jpg)
5. Right-click on the disk again, and then click **Rebuild MBR**. Then, click **Apply** once more.  
![Click on Rebuild MBR in the MiniTool Partition Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/click-on-rebuild-mbr-in-the-minitool-partition-wizard.jpg)
6. Right-click the disk again and select **Create**. Then, click **OK**.

## 6\. Format the Disk and Create a New Partition

 If the drive that fails to initialize is empty or contains no essential data, you should format it. Then, you can create a new partition by converting its format to GPT and assigning the new volume. It is the most recommended method for resolving the issue and has worked for many users. To accomplish that, follow these steps:

1. In Windows Search, type **"cmd,"** then right-click on the **Command Prompt** app and choose **Run as administrator**.
2. In Command Prompt, type **"diskpart"** and press **Enter.**
3. Then, type **"list disk"** and hit **Enter**. Then, you'll see how many drives you have on your device.
4. Depending on which drive you are having problems with, type **"Disk 0"** or **"Disk 1"** and hit **Enter**.
5. Once the disk is selected, type **"clean"** and press **Enter** to format it.  
![run the clean disk disk part command in windows command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/clean-disk-disk-part-command-prompt.jpg)
6. Then, type **"GPT"** and press **Enter** to convert the disk to GPT format.
7. To create a new partition on a formatted drive, type **"create partition primary"** and hit **Enter**.
8. Then, type **"format quick fs=ntfs"** and hit **Enter** to format the volume.  
![quick format ntfs usb drive command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/quick-format-ntfs-usb-drive-command-prompt.jpg)
9. Lastly, type **"assign"** and hit **Enter** to assign the drive letter.

 If the external drive presenting the error under discussion contains essential data, you shouldn't format it, as you'll lose data this way. Before taking this route, keep that in mind.

 Some [data recovery tools](https://www.makeuseof.com/best-data-recovery-software/) allow you to recover deleted files from formatted drives. If you need to format your external hard drive containing important data as a last resort, you can use these tools to retrieve your deleted data. However, they may not work in every situation.

## Bring Your Disk Drive Back to Life

 The "disk unknown, not initialized" error in Disk Management means your drive hasn't been recognized by your system. Hopefully, you now have a better understanding of what causes the error under discussion and what you can do about it. Apply the fixes covered above to bring your disk drive back to life.

 If the problem persists, a hardware issue could be preventing your drive from working. To rule out hardware problems, have it inspected by a technician.

 If you want to resolve this issue and successfully load the data, here are a few fixes you should try.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-ai-editor.techidaily.com/updated-gopro-quik-on-pc-how-to-use-it-and-explore-other-options/"><u>Updated GoPro Quik on PC How to Use It and Explore Other Options</u></a></li>
<li><a href="https://windows11.techidaily.com/cure-for-hidden-second-display-on-w11/"><u>Cure for Hidden Second Display on W11</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-elevate-your-profile-expertise-in-fb-video-coverage-creation/"><u>[Updated] 2024 Approved  Elevate Your Profile  Expertise in FB Video Coverage Creation</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-clear-pin-lockouts-with-ease/"><u>Windows 11: Clear PIN Lockouts with Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-efficiency-advanced-tips-for-task-juggling-in-windows-11/"><u>Unlock Efficiency: Advanced Tips for Task Juggling in Windows 11</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/align-video-content-with-instagram-viewer-preferences-for-2024/"><u>Align Video Content with Instagram Viewer Preferences for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/controlling-winoss-priority-setting-for-hardware-acceleration/"><u>Controlling WinOS's Priority Setting for Hardware Acceleration</u></a></li>
<li><a href="https://android-location.techidaily.com/9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-oneplus-nord-ce-3-lite-5g-drfone-by-drfone-virtual/"><u>9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your OnePlus Nord CE 3 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-managing-applications-with-wpm-in-windows-11/"><u>Efficiently Managing Applications with WPM in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/combat-apex-crashes-effective-solutions-for-windows-11-users/"><u>Combat Apex Crashes: Effective Solutions for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-error-0x80070570-a-guide-for-fixed-damaged-files/"><u>Bypassing Error 0X80070570: A Guide for Fixed Damaged Files</u></a></li>
<li><a href="https://windows11.techidaily.com/using-ports-without-built-in-pc-graphics-hardware/"><u>Using Ports Without Built-In PC Graphics Hardware</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-2024-approved-want-amazing-opening-effects-today-we-will-share-with-you-20-best-places-that-are-free-to-download-title-intro-templates-for-adobe-premier/"><u>New 2024 Approved Want Amazing Opening Effects? Today, We Will Share with You 20 Best Places that Are Free to Download Title, Intro Templates for Adobe Premiere Pro</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-mastering-gaming-nostalgia-discovering-the-most-acclaimed-gb-console-emulators-on-pc/"><u>[Updated] 2024 Approved  Mastering Gaming Nostalgia  Discovering The Most Acclaimed GB Console Emulators on PC</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-shotsizesavvy-fine-tuning-your-social-media-content-for-instagram/"><u>[Updated] In 2024, ShotSizeSavvy  Fine-Tuning Your Social Media Content for Instagram</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-organization-controlled-errors-in-windows-11-systems/"><u>Addressing Organization-Controlled Errors in Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/the-easy-way-opening-sticky-notes-on-win11/"><u>The Easy Way: Opening Sticky Notes on Win11</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-your-easy-guide-to-proficient-voice-recording-on-a-mac-for-non-tech-savvy-individuals/"><u>New Your Easy Guide to Proficient Voice Recording on a Mac for Non-Tech Savvy Individuals</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-speed-kings-guide-to-fast-frame-gathering/"><u>2024 Approved  Speed King's Guide to Fast Frame Gathering</u></a></li>
<li><a href="https://windows11.techidaily.com/zeroing-in-on-error-0x800f0831-for-windows-repair/"><u>Zeroing in on Error 0X800F0831 for Windows Repair</u></a></li>
<li><a href="https://windows11.techidaily.com/defining-new-default-for-reading-pdfs-on-pc/"><u>Defining New Default for Reading PDFs on PC</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-teleport-your-gps-location-on-vivo-y78plus-drfone-by-drfone-virtual-android/"><u>How To Teleport Your GPS Location On Vivo Y78+? | Dr.fone</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-useful-tips-how-can-you-use-voxal-voice-changer-on-discord/"><u>New 2024 Approved Useful Tips How Can You Use Voxal Voice Changer on Discord?</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-sluggish-excel-experience/"><u>Fixing Windows' Sluggish Excel Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-stifling-random-cmd-entrance/"><u>Techniques for Stifling Random CMD Entrance</u></a></li>
<li><a href="https://windows11.techidaily.com/1719346558796-why-your-pc-needs-only-one-guardian-antivirus-software/"><u>Why Your PC Needs Only One Guardian - Antivirus Software!</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-windows-errors-top-10-diagnostic-aids/"><u>Decoding Windows Errors: Top 10 Diagnostic Aids</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-in-2024-flipping-out-a-step-by-step-guide-to-rotating-clips-in-final-cut-pro/"><u>Updated In 2024, Flipping Out A Step-by-Step Guide to Rotating Clips in Final Cut Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/4-ways-to-flush-the-dns-cache-on-windows-11/"><u>4 Ways to Flush the DNS Cache on Windows 11</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-ideal-mac-recording-solutions-for-efficient-documentation/"><u>[Updated] Ideal Mac Recording Solutions for Efficient Documentation</u></a></li>
<li><a href="https://android-location-track.techidaily.com/ways-to-stop-parent-tracking-your-samsung-galaxy-f34-5g-drfone-by-drfone-virtual-android/"><u>Ways to stop parent tracking your Samsung Galaxy F34 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-inoperative-drive-not-detected-by-os/"><u>Fixing Inoperative Drive Not Detected by OS</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-simply-turn-off-your-insta-tv/"><u>[New] 2024 Approved  Simply Turn Off Your Insta TV</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-taskbar-history-from-start-to-now/"><u>Windows Taskbar History: From Start to Now</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-in-use-device-naming-5-fixes-for-windows-errors/"><u>Avoiding In-Use Device Naming: 5 Fixes for Windows Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/what-to-do-if-you-cant-access-your-router-page-or-web-interfaces-on-windows/"><u>What to Do if You Can't Access Your Router Page or Web Interfaces on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-chromes-non-downloading-problems-on-windows/"><u>Addressing Chrome's Non-Downloading Problems on Windows</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/android-unlock-code-sim-unlock-your-motorola-phone-and-remove-locked-screen-by-drfone-android/"><u>Android Unlock Code Sim Unlock Your Motorola Phone and Remove Locked Screen</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-the-ultimate-guide-to-distinctive-tiktok-pfps/"><u>[New] In 2024, The Ultimate Guide to Distinctive TikTok PFPs</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-steam-library-folder-editability-in-win-11/"><u>Enabling Steam Library Folder Editability in Win 11</u></a></li>
<li><a href="https://fix-guide.techidaily.com/simple-solutions-to-fix-android-systemui-has-stopped-error-for-nokia-c32-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Simple Solutions to Fix Android SystemUI Has Stopped Error For Nokia C32 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-virtualbox-0x80004005-failure-on-windows-pcs/"><u>Addressing VirtualBox 0X80004005 Failure on Windows PCs</u></a></li>
</ul></div>
