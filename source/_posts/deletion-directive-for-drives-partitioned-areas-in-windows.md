---
title: Deletion Directive for Drives' Partitioned Areas in Windows
date: 2024-07-11T22:25:25.124Z
updated: 2024-07-12T22:25:25.124Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Deletion Directive for Drives' Partitioned Areas in Windows
excerpt: This Article Describes Deletion Directive for Drives' Partitioned Areas in Windows
keywords: Drive Deletion Guide,Partition Erasure Windows,WIN-Drive Space Clearance,Freeing Up Disk Space,Removing Drives' Segments,Unpartition Windows Systems,Secure Drive Wipe Windows
thumbnail: https://thmb.techidaily.com/9083264d1e9ed82c0a8d3858961cbcacf8dd6e0e896428761bc70aaa3b066e45.jpg
---

## Deletion Directive for Drives' Partitioned Areas in Windows

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
<li><a href="https://windows11.techidaily.com/construct-ai-driven-artistry-with-win11-and-paint-tool-sai-your-ultimate-guide-to-image-creation/"><u>Construct AI-Driven Artistry with Win11 & Paint Tool SAI: Your Ultimate Guide to Image Creation</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-win11s-startup-configuration-for-unmatched-performance/"><u>Conquer Win11's Startup Configuration for Unmatched Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/diagnosing-and-fixing-printmanagement-error-on-windows-os/"><u>Diagnosing and Fixing 'PrintManagement' Error on Windows OS</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-metaverse-quest-10-innovative-sci-fi-films-worldwide-travels/"><u>[New] Metaverse Quest  10 Innovative Sci-Fi Films Worldwide Travels</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-the-oculus-quest-for-windows-vr-use/"><u>Customizing the Oculus Quest for Windows VR Use</u></a></li>
<li><a href="https://windows11.techidaily.com/comparative-overview-of-installation-methods-exe-and-msi-files/"><u>Comparative Overview of Installation Methods: Exe & Msi Files</u></a></li>
<li><a href="https://extra-information.techidaily.com/filmmaking-revolution-15-essential-gopro-luts-revealed/"><u>Filmmaking Revolution  15 Essential GoPro LUTs Revealed</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-unleash-potential-with-strategic-use-of-snapkit-features/"><u>[New] 2024 Approved  Unleash Potential with Strategic Use of SnapKit Features</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-the-full-picture-of-ustream-and-analogous-services/"><u>[New] The Full Picture of Ustream & Analogous Services</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-efficient-video-sharing-on-twitter-from-smartphones/"><u>2024 Approved  Efficient Video Sharing on Twitter From Smartphones</u></a></li>
<li><a href="https://windows11.techidaily.com/credential-control-in-win11-quick-ways-to-unlock-passwords/"><u>Credential Control in Win11: Quick Ways to Unlock Passwords</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-unleashing-your-audio-journey-in-ubuntu-installation-and-removal-of-audacity/"><u>Updated Unleashing Your Audio Journey in Ubuntu Installation and Removal of Audacity</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-mastering-windows-movie-maker-a-step-by-step-guide-for-windows-8-users/"><u>In 2024, Mastering Windows Movie Maker  A Step-by-Step Guide for Windows 8 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/cool-off-cycles-in-the-world-of-computers/"><u>Cool-Off Cycles in the World of Computers</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-tailoring-your-obs-feeds-for-best-social-media-impact/"><u>[New] In 2024, Tailoring Your OBS Feeds for Best Social Media Impact</u></a></li>
<li><a href="https://windows11.techidaily.com/command-line-convenience-with-windows-task-scheduler/"><u>Command Line Convenience with Windows Task Scheduler</u></a></li>
<li><a href="https://windows11.techidaily.com/decades-of-taskbars-windows-journey-19852023/"><u>Decades of Taskbars: Windows' Journey (1985–2023)</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-honor-magic-v2-drfone-by-drfone-virtual-android/"><u>Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Honor Magic V2 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/compact-guide-best-windows-forecasting-tools/"><u>Compact Guide: Best Windows Forecasting Tools</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-reset-a-locked-itel-p55-5g-phone-by-drfone-android/"><u>In 2024, How to Reset a Locked Itel P55 5G Phone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/perfect-proportions-for-professional-videos/"><u>Perfect Proportions for Professional Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-another-users-microsoft-account-on-shared-device/"><u>Disabling Another User's Microsoft Account on Shared Device</u></a></li>
<li><a href="https://windows11.techidaily.com/decrease-resource-load-managing-news-app-consumption/"><u>Decrease Resource Load: Managing News App Consumption</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-digital-domination-rise-from-thousands-to-a-million-on-youtube/"><u>[New] In 2024, Digital Domination  Rise From Thousands to a Million on YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-win11s-cursor-blackout-quickly/"><u>Clearing Up Win11's Cursor Blackout Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-drives-c-vs-d-explanation/"><u>Deciphering Drives: C: Vs D: Explanation</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-parsing-setback-code-0xc00ce556/"><u>Conquering Parsing Setback: Code 0xC00CE556</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-culinary-callings-innovative-naming-for-foodie-channels/"><u>[New] Culinary Callings  Innovative Naming for Foodie Channels</u></a></li>
<li><a href="https://windows11.techidaily.com/coherent-organization-of-windows-files-max-156/"><u>Coherent Organization of Windows Files (Max 156)</u></a></li>
<li><a href="https://screen-recording.techidaily.com/dive-into-retro-gaming-the-5-highest-rated-android-ps2-emulators-for-2024/"><u>Dive Into Retro Gaming  The 5 Highest-Rated Android PS2 Emulators for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/cleanse-your-screen-history-3-strategies/"><u>Cleanse Your Screen History - 3 Strategies</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-streamlining-online-meetings-zoom-for-win10/"><u>2024 Approved  Streamlining Online Meetings  Zoom for WIN10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-wide-applications-mf4770n-firmware-update/"><u>Windows-Wide Applications: MF4770n Firmware Update</u></a></li>
<li><a href="https://extra-resources.techidaily.com/integrating-extra-footage-crafting-engaging-visual-narratives/"><u>Integrating Extra Footage  Crafting Engaging Visual Narratives</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-magix-vision-enhancement-a-detailed-review/"><u>[Updated] MAGIX Vision Enhancement  A Detailed Review</u></a></li>
<li><a href="https://windows11.techidaily.com/command-your-way-through-windows-11-nircmd-tips-and-tricks/"><u>Command Your Way Through Windows 11: NirCmd Tips & Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-and-rectifying-non-functional-batches-in-windows/"><u>Deciphering and Rectifying Non-Functional Batches in Windows</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-your-realme-gt-neo-5-se-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How to Change Your Realme GT Neo 5 SE Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-a-user-friendly-guide-for-shortcut-placement-on-desktop/"><u>Crafting a User-Friendly Guide for Shortcut Placement on Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-for-clarity-windows-terminal-as-main-app/"><u>Customize for Clarity: Windows Terminal As Main App</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-in-2024-ultimate-guide-converting-4k-videos-to-mp4-for-easy-download/"><u>New In 2024, Ultimate Guide Converting 4K Videos to MP4 for Easy Download</u></a></li>
<li><a href="https://windows11.techidaily.com/cracked-codekeepers-stay-secure-in-the-now/"><u>Cracked Codekeepers: Stay Secure in the Now</u></a></li>
<li><a href="https://extra-tips.techidaily.com/exclusive-5-ios-backdrop-change-programs-for-apple-devices/"><u>Exclusive 5 iOS Backdrop Change Programs for Apple Devices</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-spark-business-visibility-affordable-logos-from-template-to-original/"><u>In 2024, Spark Business Visibility  Affordable Logos From Template to Original</u></a></li>
<li><a href="https://windows11.techidaily.com/direct-console-connection-joining-win-to-ps3-controller/"><u>Direct Console Connection: Joining Win to PS3 Controller</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>