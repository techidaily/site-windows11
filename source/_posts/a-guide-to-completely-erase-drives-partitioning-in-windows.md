---
title: A Guide to Completely Erase Drive's Partitioning in Windows
date: 2024-07-11T22:10:32.224Z
updated: 2024-07-12T22:10:32.224Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Guide to Completely Erase Drive's Partitioning in Windows
excerpt: This Article Describes A Guide to Completely Erase Drive's Partitioning in Windows
keywords: Erase Drive Partition,Delete Windows Partition,Wipe Drive Cleanly,Remove Windows Partition,Clear Data Partitions,Format Windows Drives,Reset Drive Settings
thumbnail: https://thmb.techidaily.com/fb9dc69321147c58e76f643c816e11fbbc732b6fd56c746767b53b83551e6f78.jpg
---

## A Guide to Completely Erase Drive's Partitioning in Windows

 Your Windows computer provides several options for deleting unwanted drive partitions, whether you are looking to consolidate space, restructure data allocation, or simply start over. However, before you do that, make sure to backup or move any important data on the partition, as the process removes all the data on the drive.

 This guide will show you how to delete a drive partition using the Settings app, Disk Management tool, Command Prompt, and PowerShell.

## 1\. How to Delete a Drive Partition on Windows Using the Settings App

 The Windows Settings app makes it easy to manage drive partitions and perform advanced storage-related tasks. It also provides the most straightforward way to delete a drive partition on Windows.To delete a drive partition via the Settings app:

1. Press **Win + I** to open the Settings app.
2. In the **System** tab, click on **Storage**.
3. Expand **Advanced storage settings** and click **Disks & volumes**.
4. Click the **Properties** button next to the drive you wish to delete.
5. Under the **Format** section, click the **Delete** button.
6. Select **Delete volume** to confirm.  
![Delete a Drive Partition Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-the-settings-app.jpg)

 Once you complete the steps, the partition and everything on it will be gone.

## 2\. How to Delete a Drive Partition on Windows Using the Disk Management Utility

 Another way to delete a drive partition on Windows is via the Disk Management tool. If you want to use that, follow these steps:

1. Press **Win + R** to open the Run dialog box.
2. Type **diskmgmt.msc** in the text field and press **Enter**.
3. In the Disk Management window, right-click the unwanted partition and click the **Delete Volume** option.
4. Select **Yes** to confirm.  
![Delete a Drive Partition Using the Disk Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-the-disk-management-tool.jpg)

 Don't want to get rid of a drive altogether? You can also choose to [hide the drive on Windows](https://www.makeuseof.com/how-to-hide-a-drive-in-windows/) using the Disk Management tool.

## 3\. How to Delete a Drive Partition on Windows With the Command Prompt

 Not a fan of GUI? No problem. Windows also lets you delete a drive partition using the Command Prompt. Here are the steps for the same.

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the menu that appears.
2. Select **Yes** when the User Account Control (UAC) prompt shows up.
3. In the console, run the following commands to view a list of drives connected to your system.  
`diskpart  
list volume`
4. Note down the number associated with the drive you want to delete in the **Volume** column.
5. Type the following command and press **Enter** to select the volume. Make sure you replace **N** in the command with the drive number noted earlier.  
`select volume N`
6. Copy and paste the following command and press **Enter** to delete the partition.  
`delete volume`  
![Delete a Drive Partition Using the Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-the-command-prompt.jpg)

 Enjoy working with the Command Prompt? If so, you will surely love our guide on [customizing the Command Prompt on Windows](https://www.makeuseof.com/windows-customize-command-prompt/).

## 4\. How to Delete a Drive Partition on Windows via PowerShell

 Windows PowerShell is another command-line tool that you can use to delete a disk partition. Here are the steps you need to follow.

1. Press **Win + S** to open the search menu.
2. Type in **Windows PowerShell** and select **Run as administrator**.
3. Select **Yes** when the User Account Control (UAC) prompt appears to [open PowerShell with admin rights](https://www.makeuseof.com/windows-powershell-always-open-as-administrator/).
4. Run the following command to view a list of drives on your PC:  
`Get-volume`
5. Note down the letter assigned to the drive you want to delete in the **DriveLetter** column.
6. Copy and paste the following command to delete the partition. Replace **X** in the command with the actual drive letter noted in the previous step.  
`Remove-Partition -DriveLetter X`
7. Type **Y** and press **Enter** to confirm.  
![Delete a Drive Partition Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-powershell.jpg)

 Once you run the above commands, PowerShell will delete the specified partition.

## There Are Many Ways to Delete Drive Partitions on Windows

 As we just saw, deleting a drive partition on Windows is a simple process, regardless of the method you use. Once you delete a partition, the space on that drive will be unallocated. You can then create a new partition on the empty space or use the space to expand an existing partition.

 This guide will show you how to delete a drive partition using the Settings app, Disk Management tool, Command Prompt, and PowerShell.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/banish-file-explorer-errors-essential-fixes-for-win11-users/"><u>Banish File Explorer Errors: Essential Fixes for Win11 Users</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/how-do-you-get-sun-stone-evolutions-in-pokemon-for-apple-iphone-8-drfone-by-drfone-virtual-ios/"><u>How Do You Get Sun Stone Evolutions in Pokémon For Apple iPhone 8? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-security-sync-windows-11-remotely-easily/"><u>Bypassing Security, Sync Windows 11 Remotely Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-11-mode-switch-failures/"><u>Bypassing Windows 11 Mode Switch Failures</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/the-ultimate-checklist-for-utilizing-adobe-audition-in-sound-production/"><u>The Ultimate Checklist for Utilizing Adobe Audition in Sound Production</u></a></li>
<li><a href="https://windows11.techidaily.com/bypass-black-screen-in-win11-fast-and-straightforward/"><u>Bypass Black Screen in Win11, Fast & Straightforward</u></a></li>
<li><a href="https://windows11.techidaily.com/androidios-to-windows-pc-microphone-conversion-guide/"><u>Android/iOS to Windows PC Microphone Conversion Guide</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-simplified-method-for-youtubers-to-dailymotion/"><u>[New] Simplified Method for YouTubers to Dailymotion</u></a></li>
<li><a href="https://windows11.techidaily.com/blending-digital-worlds-androidpc-connections-made-simple/"><u>Blending Digital Worlds: Android/PC Connections Made Simple</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-asking-too-many-hands-at-once-error/"><u>Bypassing Asking Too Many Hands at Once Error</u></a></li>
<li><a href="https://windows11.techidaily.com/academic-excellence-with-these-top-8-study-tips-for-windows-users/"><u>Academic Excellence with These Top 8 Study Tips for Windows Users</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-begin-with-no-cost-video-intro-tools/"><u>In 2024, Begin with No-Cost Video Intro Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/automating-windows-auditory-restart-post-boot-issue/"><u>Automating Windows Auditory Restart Post-Boot Issue</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-evaluating-streamlabs-vs-competitive-embedders/"><u>[New] In 2024, Evaluating StreamLabs Vs. Competitive Embedders</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-youtube-for-educators-maximizing-its-classroom-potential/"><u>[New] YouTube for Educators  Maximizing Its Classroom Potential</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-through-disabled-script-barrier-4-key-techniques-to-load-ps-successfully/"><u>Breaking Through Disabled Script Barrier: 4 Key Techniques to Load PS Successfully</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-boosting-viewership-with-animated-subscribe-buttons-in-filmora-easy-guide/"><u>[Updated] In 2024, Boosting Viewership with Animated Subscribe Buttons in Filmora (Easy Guide)</u></a></li>
<li><a href="https://windows11.techidaily.com/5-essential-tweaks-for-your-windows-11-search-settings/"><u>5 Essential Tweaks for Your Windows 11 Search Settings</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-here-is-a-list-of-top-five-free-wmv-video-editing-tools-which-feature-almost-all-sorts-of-casual-video-editing-needs/"><u>New 2024 Approved Here Is a List of Top Five Free WMV Video Editing Tools, Which Feature Almost All Sorts of Casual Video Editing Needs</u></a></li>
<li><a href="https://windows11.techidaily.com/a-compreenasian-approach-to-fixing-winget-on-windows-11/"><u>A Compreenasian Approach to Fixing Winget on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/9-insights-on-how-pc-outperforms-a-mac-in-essential-areas/"><u>9 Insights on How PC Outperforms a Mac in Essential Areas</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-in-2024-efficiently-record-your-periscope-experience-now/"><u>[Updated] In 2024, Efficiently Record Your Periscope Experience Now</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/mastering-jaycut-a-step-by-step-guide-to-free-online-video-editing-for-2024/"><u>Mastering Jaycut A Step-by-Step Guide to Free Online Video Editing for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-vivo-y27s-frp-by-drfone-android/"><u>In 2024, Step-by-Step Tutorial How To Bypass Vivo Y27s FRP</u></a></li>
<li><a href="https://windows11.techidaily.com/7-solutions-when-apps-arent-working-properly-on-windows/"><u>7 Solutions When Apps Aren't Working Properly on Windows</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-2024-approved-lightning-fast-video-delivery-on-facebook-select-extensions-and-apps/"><u>[Updated] 2024 Approved  Lightning-Fast Video Delivery on Facebook  Select Extensions & Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-power-hungry-unrealcefsubprocess-a-windows-guide/"><u>Addressing Power-Hungry UnrealCEFSubprocess: A Windows Guide</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-top-voice-altering-tool-for-free-enhance-your-valorant-experience/"><u>In 2024, Top Voice Altering Tool for Free - Enhance Your Valorant Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-peak-performance-with-multi-task-proficiency-on-windows-11-pcs/"><u>Achieve Peak Performance with Multi-Task Proficiency on Windows 11 PCs</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-mastering-closer-video-in-google-meet-sessions/"><u>[Updated] Mastering Closer Video in Google Meet Sessions</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-performance-with-windows-11-power-options/"><u>Boost Performance with Windows 11 Power Options</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-back-your-teams-screens/"><u>Bring Back Your Teams Screens</u></a></li>
<li><a href="https://windows11.techidaily.com/beat-nvidias-windows-scanner-errors-today/"><u>Beat Nvidia's Windows Scanner Errors Today</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ree-apps-for-youtube-gallery-downloading/"><u>Top FREE Apps for YouTube Gallery Downloading</u></a></li>
<li><a href="https://windows11.techidaily.com/balancing-system-resources-with-microsoft-edge/"><u>Balancing System Resources with Microsoft Edge</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-a-comprehensive-overview-of-adding-roles-in-discord/"><u>[New] In 2024, A Comprehensive Overview of Adding Roles in Discord</u></a></li>
<li><a href="https://windows11.techidaily.com/augmenting-windows-functionality-with-these-top-6-android-apps/"><u>Augmenting Windows Functionality with These Top 6 Android Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-11-system-call-failures-quickly/"><u>Addressing Windows 11 System Call Failures Quickly</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-magnify-memories-unaltered-resolution/"><u>[Updated] Magnify Memories  Unaltered Resolution</u></a></li>
<li><a href="https://windows11.techidaily.com/7-techniques-for-reviving-a-stuck-dark-screen-mode/"><u>7 Techniques for Reviving a Stuck Dark Screen Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerating-problem-solving-in-windows-10-and-11-via-shortcuts/"><u>Accelerating Problem-Solving in Windows 10 & 11 via Shortcuts</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerating-file-download-rates-in-utorrent-win-os-style/"><u>Accelerating File Download Rates in uTorrent, WIN OS Style</u></a></li>
<li><a href="https://driver-install.techidaily.com/optimize-scansnap-s1500-performance-with-new-software/"><u>Optimize ScanSnap S1500 Performance with New Software</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-wwinplusprint-error-on-your-computer-successfully/"><u>Addressing WWin+Print Error on Your Computer Successfully.</u></a></li>
</ul></div>
