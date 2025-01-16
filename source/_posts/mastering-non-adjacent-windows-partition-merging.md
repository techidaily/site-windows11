---
title: Mastering Non-Adjacent Windows Partition Merging
date: 2025-01-11T23:40:24.185Z
updated: 2025-01-16T14:14:17.206Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering Non-Adjacent Windows Partition Merging
excerpt: This Article Describes Mastering Non-Adjacent Windows Partition Merging
keywords: Non-Adj Partitions Merge,Data Partition Merger,Advanced Partition Alignment,Large Disk Optimization,Windows Partition Management,Seamless Data Merge,Unified Storage System
thumbnail: https://thmb.techidaily.com/298f3a51b5ad96cf99ca78528e1cf7576a8f7bf919402e8696c70895bc723b47.jpg
---

## Mastering Non-Adjacent Windows Partition Merging

 Have you run out of space on one of your drives and want to expand it by merging in it another drive with free space? If so, you can easily do this if the partitions you want to merge are adjacent; if they are not adjacent, the process would be more complicated. This begs the question: how do adjacent and nonadjacent partitions differ?

 Below, we'll show you how to merge adjacent and non-adjacent partitions using Device Management and NIUBI Partition Editor, a third-party app.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How Do Adjacent and Non-Adjacent Partitions Differ?

 As the name implies, adjacent partitions are located next to each other. If you have two drives right next to each other, C and D, they are considered adjacent partitions. In contrast, if you have three partitions, C, D, and E, then C and E are nonadjacent partitions because drive D separates them.

 It's straightforward to merge adjacent partitions using the Windows built-in tool and any third-party app. However, merging two non-adjacent partitions could be complicated.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4YCkNXJjC3c?si=9Tn8KiqKGTZi1o7E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Merge Adjacent Partitions Using Windows Disk Management

 Disk Management is a Windows built-in utility that allows us to manage the hard drives installed on our device. The tool enables us to create, format, and delete partitions, shrink the drive volume by creating a new partition, expand the drive volume by merging space from another drive, and much more.

 When merging a partition with the Disk Management tool, it is necessary to delete an existing volume (adjacent to the drive you wish to extend) and release some space first. Later, you can merge this unallocated space into a partition of your choice.

 Therefore, you'll lose all your data on the drive you want to merge (or delete), which is a major disadvantage. Because of that, you'll need to [relocate your essential Windows apps](https://www.makeuseof.com/tag/move-installed-apps-programs-windows-10/) and files from that drive, and then delete the volume.

 Let's say you want to merge drive D with drive C. This will require you to delete drive D first and merge it into drive C after that. You can delete the volume by following these steps:

1. Type **"Create and format"** in the Windows Search box and click **Create and format hard disk partitions**.  
![Type Create and Format in Windows Search to Open the Disk Management Utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/1-type-create-and-format-in-windows-search-to-open-the-disk-management-utility.jpg)
2. Right-click the volume (the drive you want to merge into another) and select **Delete Volume**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_dOmuXhsV6Y?si=aT6vgPbDx4ajjvdr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Delete Volume D From Windows Disk Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/2-delete-volume-d-from-windows-disk-management-tool.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3AGmFrtBLHw?si=VhvpUaXHPBHl6OT6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you've got enough unallocated space available, follow these steps to merge it into your preferred drive:

1. Right-click the drive you want to extend and select **Extend Volume**.  
![Right-Click the Drive You Want to Extend and select Extend Volume in the Windows Disk Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/3-right-click-the-drive-you-want-to-extend-and-select-extend-volume-in-the-windows-disk-management-tool.jpg)
2. Click **Next**, then select the amount of space you want to merge in the box next to **Select the amount of space in MB**. Following that, click **Next** a second time.  

![Click Next After Selecting the Amount of Space in MB You Want to Extend the Volume By in Windows Disk Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/4-click-next-after-selecting-the-amount-of-space-in-mb-you-want-to-extend-the-volume-by-in-windows-disk-management-tool.jpg)
3. Then, click **Finish** to merge the unallocated space into your destination drive.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YfEPmG_O6F8?si=93ZTVtH_zjFRz5eh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Merge Non-Adjacent Partitions With Disk Management

 If you have unallocated space non-adjacent to the destination drive, the Extend Volume option will appear grayed out in Disk Management, meaning you can't merge the non-adjacent space into the destination drive. You need to first delete the volumes between your destination drive and unallocated space.

 Deleting the in-between volumes will increase the unallocated space and it'll become adjacent to your destination drive. Later, you can merge some portion of the unallocated space into the destination drive and use the rest to recreate the in-between volumes you deleted earlier.

![Delete the Volumes Between Your Destination Drive and Unallocated Space in Windows Disk Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/6-delete-the-volumes-between-your-destination-drive-and-unallocated-space-in-windows-disk-management-tool.jpg)

 Because deleting a volume also deletes its data, you have to [create a backup of all drives](https://www.makeuseof.com/windows-11-create-complete-backup/) en route to your destination and unallocated space before deleting them. Because of this, merging nonadjacent partitions using Device Management is considered ineffective and time-consuming. An easy way to avoid this hassle is to use third-party tools.

## How to Merge Two Non-Adjacent Partitions Using NIUBI Partition Editor

 NIUBI Partition Editor makes merging nonadjacent partitions easy and doesn't require you to delete partitions between the unallocated space and destination partition. Here's how you can merge two non-adjacent partitions, say C and E, using NIUBI:

1. Download the NIUBI Partition Editor software from the [HDD-Tool official website](https://www.hdd-tool.com/download.html). There are two ways to use the software: download and install the setup file or download the portable version and use it without installing it.
2. Search for **NIUBI** in Windows Search to open the software.
3. Right-click the **E** drive you want to merge into **C** and click **Delete volume**. Click **Yes** to confirm; this will release the space.  
![Delete Volume E in NIUBI Partition Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/8-delete-volume-e-in-niubi-partition-editor.jpg)
4. Now, right-click on partition **D,** which is between partition **C** and unallocated space, and click **Resize/Move volume**.  

![Click on ResizeMode to Relocate the Partition D in NIUBI Partition Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/9-click-on-resizemode-to-relocate-the-partition-d-in-niubi-partition-editor.jpg)
5. Then, move the whole volume (don't extend the volume) to the unallocated space right next to it, which will move drive **D** to where the unallocated space was, making the unallocated space adjacent to drive **C**.  

![Drag the Drive D towards the Unallocated Space to Make the Free Space Adjacent to the Drive C](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/10-drag-the-drive-d-towards-the-unallocated-space-to-make-the-free-space-adjacent-to-the-drive-c.jpg)
6. Once adjacent, right-click the **C** drive, click **Resize/Move Volume**, then expand the **C** drive's space to cover the unallocated space. It will merge the unallocated space into the **C** drive.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Bov2KfWQ_Y?si=MnVczisgeJ-sGW2r" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Extend the C Drive to Merge the Unallocated Space into It in the NUIBI Partition Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/11-extend-the-c-drive-to-merge-the-unallocated-space-into-it-in-the-nuibi-partition-editor.jpg)

 That's how you can merge two non-adjacent drives without deleting the drives between the source and destination.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MTb4xHzeQEk?si=9Sqq-gFWnHc8x3_P" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Can You Resize and Move Partitions if NIUBI Partition Editor Doesn't Let You?

 The third-party disk management software, such as NIUBI Partition Editor, sometimes doesn't allow users to move or resize their drives. They either find these options grayed out or missing altogether. It usually happens when you try to move or resize an encrypted drive.

 If you see either of these options missing or grayed out for a specific drive, you should first remove the drive encryption, which is Bitlocker by default in Windows. While you can turn off encryption from individual partitions in different ways, we recommend turning off encryption at the device level for a short period of time. Here's how:

1. Search for **"Device Encryption"** in the Windows Search and click on **Device encryption settings**.
2. Turn the toggle next to **Device encryption** off.  
![Turn the Device Encryption Off in Windows Device Encryption Settings in Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/12-turn-the-device-encryption-off-in-windows-device-encryption-settings-in-windows-settings-app.jpg)

 Turning off encryption can take a long time, so be patient while the process finishes, and you see the toggle next to **Device encryption** turned off. Once that's done, you can resize and move all the drives without restrictions. Once you're done merging the partitions, re-enable the device encryption.

## Merge Partitions With Ease on Windows

 You can merge partitions to use free space better or expand the volume of a drive running low on storage. Hopefully, you'll now be able to merge adjacent and non-adjacent partitions more easily. Don't forget to turn off device encryption if you cannot resize the drive.

 Also, it is not necessary to use NIUBI Partition Editor; you can use any disk management software of your choice.

 Below, we'll show you how to merge adjacent and non-adjacent partitions using Device Management and NIUBI Partition Editor, a third-party app.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-links.techidaily.com/new-in-2024-optimal-focus-techniques-for-videoleap-users/"><u>[New] In 2024, Optimal Focus Techniques for Videoleap Users</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-compelling-macos-sierra-coders-for-vids/"><u>[Updated] Compelling MacOS Sierra Coders for Vids</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-exclusive-guide-to-top-youtube-to-webm-conversion-software/"><u>[Updated] Exclusive Guide to Top YouTube-to-WebM Conversion Software</u></a></li>
<li><a href="https://tech-haven.techidaily.com/corporate-clashes-reimagined-microsoft-blizzard-alliance-and-ai-innovations-audio-show/"><u>Corporate Clashes Reimagined: Microsoft-Blizzard Alliance and AI Innovations [Audio Show]</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-unpredictable-power-estimator-display-on-windows-11/"><u>Correcting Unpredictable Power Estimator Display on Windows 11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/deciphering-the-impact-of-generative-systems-on-truth/"><u>Deciphering the Impact of Generative Systems on Truth</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-resolving-winirq-conflicts-for-clear-audio/"><u>Decoding and Resolving WinIRQ Conflicts for Clear Audio</u></a></li>
<li><a href="https://vp-tips.techidaily.com/het-woordelijke-overzicht-van-een-wav-audio-bestand-kennis-voor-nederlands-speelers/"><u>Het Woordelijke Overzicht Van Een .wav Audio Bestand - Kennis Voor Nederlands Speelers</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-does-the-stardust-trade-cost-in-pokemon-go-on-xiaomi-redmi-note-13-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How does the stardust trade cost In pokemon go On Xiaomi Redmi Note 13 Pro+ 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/initiating-chatgpt-with-windows-operating-system/"><u>Initiating ChatGPT with Windows Operating System</u></a></li>
<li><a href="https://windows11.techidaily.com/reimagining-your-pc-integrating-previous-apps-into-win-11/"><u>Reimagining Your PC: Integrating Previous Apps Into Win 11</u></a></li>
<li><a href="https://discover-hacks.techidaily.com/reverting-network-settings-to-original-state-in-windows-os-expert-tips-from-yl-software/"><u>Reverting Network Settings to Original State in Windows OS: Expert Tips From YL Software</u></a></li>
<li><a href="https://windows11.techidaily.com/skyrocket-your-text-entry-speed-via-typingaid/"><u>Skyrocket Your Text Entry Speed via TypingAid</u></a></li>
<li><a href="https://win-remarkable.techidaily.com/solving-the-infamous-bsod-issue-with-tips-from-yl-software-experts/"><u>Solving the Infamous BSOD Issue with Tips From YL Software Experts</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-for-an-effortless-in-place-windows-11-revamp/"><u>Step-by-Step Guide for an Effortless, In-Place Windows 11 Revamp</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-0x80070194-winos-onedrive-fixes/"><u>Tackling the 0X80070194: WinOS OneDrive Fixes</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-skys-boldest-workhorses-top-10-drones/"><u>The Sky's Boldest Workhorses - Top 10 Drones</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secrets-of-registry-edits-in-cmd/"><u>Unveiling the Secrets of Registry Edits in CMD</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-resetting-rituals-the-ultimate-8/"><u>Windows Resetting Rituals: The Ultimate 8</u></a></li>
</ul></div>

