---
title: A Guide to Completely Erase Drive's Partitioning in Windows
date: 2024-07-03T11:10:46.258Z
updated: 2024-07-04T11:10:46.258Z
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/navigating-usage-settings-on-windows-11-your-how-to-guide/"><u>Navigating Usage Settings on Windows 11: Your How-To Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-command-line-capabilities-in-latest-windows-releases/"><u>Boost Command-Line Capabilities in Latest Windows Releases</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-linux-on-windows-top-wsl-2-tips-and-tricks/"><u>Optimize Linux on Windows: Top WSL 2 Tips and Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-old-user-credentials-issue-on-win-11-os/"><u>Clearing Up 'Old User Credentials' Issue on Win 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-nitpicking-colors-8-tips-for-a-neutral-desktop/"><u>Navigating Nitpicking Colors: 8 Tips for a Neutral Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/4-warning-signs-for-considering-pc-reset/"><u>4 Warning Signs for Considering PC Reset</u></a></li>
<li><a href="https://windows11.techidaily.com/mindfulness-meets-the-mind-cognitive-and-emotional-responses-to-meditation/"><u>Mindfulness Meets the Mind: Cognitive & Emotional Responses to Meditation</u></a></li>
<li><a href="https://windows11.techidaily.com/minimize-high-usage-windows-11-news-and-media-feats/"><u>Minimize High Usage Windows 11 News & Media Feats</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/additional-tips-about-sinnoh-stone-for-realme-c55-drfone-by-drfone-virtual-android/"><u>Additional Tips About Sinnoh Stone For Realme C55 | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-capture-and-share-your-win10-gaming-life/"><u>[Updated] In 2024, Capture and Share Your Win10 Gaming Life</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-honor-magic-v2-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Honor Magic V2 without Losing Data | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-best-storytelling-channels-for-impactful-yt-watching/"><u>In 2024, Best Storytelling Channels for Impactful YT Watching</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-best-free-3gp-video-rotation-software-top-picks/"><u>Updated 2024 Approved Best Free 3GP Video Rotation Software Top Picks</u></a></li>
<li><a href="https://driver-install.techidaily.com/unlocking-simple-techniques-for-amd-driver-downloads/"><u>Unlocking Simple Techniques for AMD Driver Downloads</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-foremost-innovative-logos-for-social-platforms-animations-for-2024/"><u>[Updated] Foremost Innovative Logos for Social Platforms' Animations for 2024</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-iphone-is-disabled-here-is-the-way-to-unlock-disabled-apple-iphone-12-pro-drfone-by-drfone-ios/"><u>In 2024, iPhone Is Disabled? Here Is The Way To Unlock Disabled Apple iPhone 12 Pro | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/4-ways-to-transfer-music-from-samsung-galaxy-f04-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>4 Ways to Transfer Music from Samsung Galaxy F04 to iPhone | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>