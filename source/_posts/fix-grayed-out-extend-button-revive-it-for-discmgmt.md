---
title: Fix Grayed-Out Extend Button, Revive It for DiscMgmt
date: 2024-10-19T19:41:39.344Z
updated: 2024-10-24T20:05:53.094Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fix Grayed-Out Extend Button, Revive It for DiscMgmt
excerpt: This Article Describes Fix Grayed-Out Extend Button, Revive It for DiscMgmt
keywords: Fix Extend Button Issue,Resurrect Grayed-Out Button,Reverse Button Disability,Reactivate Disabled Button,Restore Extended Controls,Extend Button Functionality,Unlock Grayed-Out Buttons
thumbnail: https://thmb.techidaily.com/2b667f6d425e137d74634d5b5e43d01ba3b3015e34fc38e54ba016f1aa0f02aa.jpg
---

## Fix Grayed-Out Extend Button, Revive It for DiscMgmt

 The "extend volume" option in the Disk Management tool enables you to increase the size of a volume or partition. However, there may be a situation where the extend volume option may be grayed out, preventing you from increasing the volume.

 If this is happening to you, try the below solutions for a grayed-out "extend volume" option on Windows

## Why Is the Extend Volume Option Grayed Out on Windows?

 If you see the extend volume option is grayed out in the Disk Management tool, there are a few possible reasons:

1. The unallocated space is not located directly next to the partition you want to extend.
2. The partition's file system is not supported on Windows.
3. The extend volume option will be grayed out if your drive has no unallocated space.

 Now that you know all the possible culprits behind the issue, let's check out all the solutions that can help fix it.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135357/19272" target="_top" id="2135357">
  <img src="//a.impactradius-go.com/display-ad/19272-2135357" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135357/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. Convert the Partition to an NTFS File System

 Windows only supports certain [file systems](https://www.makeuseof.com/tag/from-fat-to-ntfs-to-zfs-file-systems-demystified-makeuseof-explains/) for partitions. If the partition you want to extend is formatted in a file system incompatible with Windows, you will not be able to extend it.

 To extend the partition, you must format the partition and convert it into an NTFS file system. However, formatting the partition will delete all the data, so make sure to [back up the data on the partition](https://www.makeuseof.com/ways-to-back-up-data/) first.

 To convert the partition to an NTFS file system, follow these steps:

1. Right-click on the partition and select **Format**.
2. Choose **NTFS** from the File system drop-down menu. Then, click **OK**.  
![File system option in Disk Management tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/file-system-option.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134223/18498" target="_top" id="2134223">
  <img src="//a.impactradius-go.com/display-ad/18498-2134223" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134223/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The formatting process may take some time, depending on the amount of data on the partition. Once done, restart your computer and check if the issue is resolved.

## 2\. Delete a Partition and Create Unallocated Space

 The "extend volume" option will gray out if there is no unallocated space next to the partition you want to extend. To create unallocated space, you will have to delete a partition that is next to the partition you want to extend.

 If the partition is a normal volume, you can simply right-click on it and select **Delete Volume**. However, if the partition contains data, make sure to back it up before deleting it.

![Delete Volume option in Disk Management tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-volume-option.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938721/19272" target="_top" id="1938721">
  <img src="//a.impactradius-go.com/display-ad/19272-1938721" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938721/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If the partition is a recovery partition, you cannot delete it using Disk Management. You'll have to delete it using the Command Prompt. Here are the steps to do it:

1. Press the **Win** key to open the Start Menu, type **Command** **Prompt**, and choose **Run as administrator** from the right pane. If this method doesn't work, check out other [ways to launch Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Type **DiskPart** and press **Enter**.
3. Type **list disk** and press **Enter**. This command will display all the available disks.  
![list disk command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/list-disk-command-2.jpg)
4. Select the disk that you want to extend. For example, if you want to extend disk 0, type **select disk 0** and press **Enter**.
5. Type **list partition** and press **Enter**. This will list all the partitions on the disk.  
![list partition command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/list-partition.jpg)
6. In the Type column, look for the partition that says **Recovery**. Note the partition number. For example, if the partition number is 4, type **select partition 4** and press **Enter**. This will select the recovery partition.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/857869/11832" target="_top" id="857869">
  <img src="//a.impactradius-go.com/display-ad/11832-857869" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/857869/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. To delete the recovery partition, type **delete partition override** and press **Enter**.  
![delete partition override command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-partition-override.jpg)

 You will see the message **DiskPart successfully deleted the selected partition**. This indicates that the recovery partition has been deleted.

![DiskPart successfully deleted the selected partition message in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/diskpart-successfully-deleted-the-selected-partition.jpg)

 Next, open the Disk Management tool, and you will see an unallocated space next to the partition you want to extend. Right-click on the partition, choose **Extend** **Volume**, and then click **Next**.

![Extend partition option in Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/extend-partition-option.jpg)

 Once the wizard completes, you will see the partition size has been increased.

## Extend Your Windows Partitions Without Any Further Issues

 If you run out of space on a drive, you can use the unallocated space to increase storage. However, you will not be able to do so if the extend volume option is grayed out in the Disk Management tool. Fortunately, you can quickly troubleshoot this issue using the solutions above.

 If this is happening to you, try the below solutions for a grayed-out "extend volume" option on Windows

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-how-to-buy-1-million-youtube-views-safely-from-trusted-providers/"><u>[New] 2024 Approved How to Buy 1 Million YouTube Views Safely From Trusted Providers</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-discover-top-8-best-ios-tools-for-video-editing-and-conversion/"><u>[New] Discover Top 8 Best iOS Tools for Video Editing & Conversion</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/n-2024-revealing-the-secrets-accessing-forgotten-youtube-vids/"><u>[New] In 2024, Revealing the Secrets Accessing Forgotten YouTube Vids</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-in-2024-guide-to-top-templates-for-youtube-previews/"><u>[Updated] In 2024, Guide to Top Templates for YouTube Previews</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-and-install-epson-wf-3520-printer-drivers-on-windows-pcs/"><u>Download and Install Epson WF-3520 Printer Drivers on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-common-onedrive-crash-code-in-w11-w10/"><u>Fixing Common OneDrive Crash Code in W11, W10</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-live-wallpapers-to-windows-11s-desktop-with-lively-wallpaper/"><u>How to Add Live Wallpapers to Windows 11’S Desktop With Lively Wallpaper</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-your-workflow-unlocking-the-potential-of-window-11s-search-bar/"><u>Optimize Your Workflow: Unlocking the Potential of Window 11'S Search Bar</u></a></li>
<li><a href="https://win-able.techidaily.com/overcoming-warcraft-3-reforged-issues-top-solutions-for-a-smooth-gameplay-experience-in-202/"><u>Overcoming Warcraft 3 Reforged Issues: Top Solutions for a Smooth Gameplay Experience in 202</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/shielded-seeker-of-social-snapshots/"><u>Shielded Seeker of Social Snapshots</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-the-networks-menu-win-11-wifi-cleanup/"><u>Simplifying the Networks Menu: Win 11 Wifi Cleanup</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/step-by-step-on-streaming-google-meet-directly-to-youtube-channel-for-2024/"><u>Step by Step on Streaming Google Meet Directly to YouTube Channel for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-mend-windows-11-assistive-tool/"><u>Strategies to Mend Windows 11 Assistive Tool</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/transform-clutter-to-clarity-with-the-all-inclusive-11-in-1-dock-pro-up-to-44-cheaper/"><u>Transform Clutter to Clarity with the All-Inclusive 11-in-1 Dock Pro, Up to 44% Cheaper !</u></a></li>
</ul></div>

