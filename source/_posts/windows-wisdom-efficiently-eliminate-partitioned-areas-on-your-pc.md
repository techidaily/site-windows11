---
title: "Windows Wisdom: Efficiently Eliminate Partitioned Areas on Your PC"
date: 2024-06-25T11:58:09.832Z
updated: 2024-06-26T11:58:09.832Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows Wisdom: Efficiently Eliminate Partitioned Areas on Your PC"
excerpt: "This Article Describes Windows Wisdom: Efficiently Eliminate Partitioned Areas on Your PC"
keywords: Windows Cleanup Guide,PC Partition Removal,Optimize Hard Drive Space,Simplify PC Layout,Efficient Disk Management,Streamline Windows System,Unclutter PC Hardware
thumbnail: https://thmb.techidaily.com/fdc872e52961baec6923b458dbd6d98e67f3ed40f9ab2afdf7e0f1b821a0cc59.jpg
---

## Windows Wisdom: Efficiently Eliminate Partitioned Areas on Your PC

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
<li><a href="https://windows11.techidaily.com/how-to-troubleshoot-windows-obs-studio-crashes/"><u>How to Troubleshoot Windows OBS Studio Crashes</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-to-become-a-win-11-insider/"><u>Step-by-Step to Become a Win 11 Insider</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-grayed-out-memory-protection-in-win11-update/"><u>Fixing Grayed-Out Memory Protection in Win11 Update</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essence-of-personalization-through-ai-at-ms-store/"><u>The Essence of Personalization Through AI at MS Store</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-power-of-shortcuts-for-app-size-adjustment-on-windows-11/"><u>Unlocking the Power of Shortcuts for App Size Adjustment on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-common-issues-with-windows-shared-printers/"><u>Solving Common Issues with Windows Shared Printers</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-prints-with-microsoft-defender-smartscreen-edge/"><u>Configuring Prints with Microsoft Defender SmartScreen Edge</u></a></li>
<li><a href="https://windows11.techidaily.com/getting-acquainted-with-apple-maps-on-windows-desktops/"><u>Getting Acquainted with Apple Maps on Windows Desktops</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-how-to-fade-inout-audio-with-keyframes-in-filmora-for-mac-for-2024/"><u>New How to Fade In/Out Audio with Keyframes in Filmora for Mac for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-gamings-finest-top-10-gpu-picks-for-clear-online-broadcasts/"><u>[Updated] 2024 Approved  Gaming's Finest Top 10 GPU Picks for Clear Online Broadcasts</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/in-2024-say-goodbye-to-shaky-footage-top-free-video-stabilizers/"><u>In 2024, Say Goodbye to Shaky Footage Top Free Video Stabilizers</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-premium-lineup-8-prime-5k-display-models/"><u>2024 Approved  Premium Lineup  8 Prime 5K Display Models</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-google-ar-stickers-an-introduction-and-comparisons-for-2024/"><u>[New] Google AR Stickers  An Introduction & Comparisons for 2024</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-remove-passcode-from-apple-iphone-8-plus-complete-guide-drfone-by-drfone-ios/"><u>How To Remove Passcode From Apple iPhone 8 Plus? Complete Guide | Dr.fone</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-the-directors-toolkit-youtube-lessons-on-film-making/"><u>[New] 2024 Approved  The Director's Toolkit  YouTube Lessons on Film Making</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-how-to-record-voice-memo-on-iphone/"><u>2024 Approved  How to Record Voice Memo on iPhone?</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-the-ultimate-fcpx-shortcut-guide-40-time-saving-keys/"><u>New 2024 Approved The Ultimate FCPX Shortcut Guide 40 Time-Saving Keys</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>