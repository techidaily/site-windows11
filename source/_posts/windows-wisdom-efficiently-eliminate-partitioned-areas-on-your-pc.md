---
title: "Windows Wisdom: Efficiently Eliminate Partitioned Areas on Your PC"
date: 2024-07-11T21:14:42.425Z
updated: 2024-07-12T21:14:42.425Z
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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-network-error-0x800704b3-in-windows-11-and-11/"><u>How to Fix the Network Error 0X800704b3 in Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-ditch-intels-onboard-graphics-in-windows/"><u>How to Ditch Intel's Onboard Graphics in Windows</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-are-you-thinking-of-making-videos-and-marketing-on-instagram-here-is-everything-that-you-need-to-know-about-the-video-dimensions-for-insta/"><u>New 2024 Approved Are You Thinking of Making Videos and Marketing on Instagram? Here Is Everything that You Need to Know About the Video Dimensions for Instagram. Lets Have a Look at It</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-hacks-for-identifying-windows-age/"><u>Expert Hacks for Identifying Windows Age</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-mastering-your-unique-fashion-voice/"><u>[Updated] Mastering Your Unique Fashion Voice</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-ocam-screen-recorder-review-and-alternative/"><u>[Updated] In 2024, OCam Screen Recorder Review and Alternative</u></a></li>
<li><a href="https://extra-hints.techidaily.com/building-a-professional-online-network-hub/"><u>Building a Professional Online Network Hub</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-change-your-sim-pin-code-on-your-motorola-moto-g13-phone-by-drfone-android/"><u>How To Change Your SIM PIN Code on Your Motorola Moto G13 Phone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-boosting-your-businesss-productivity-with-top-fb-planners/"><u>[Updated] In 2024, Boosting Your Business's Productivity with Top FB Planners</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-digital-experience-process-control-and-thematic-aesthetics-in-w11/"><u>Elevate Your Digital Experience: Process Control & Thematic Aesthetics in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/analyzing-how-windows-11-fuels-microsofts-earnings/"><u>Analyzing How Windows 11 Fuels Microsoft's Earnings</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-writing-permission-failure-in-windows-10-and-11/"><u>Fixing Writing Permission Failure in Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/keyboard-knots-unraveling-win10-functional-issues/"><u>Keyboard Knots: Unraveling WIN10 Functional Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-to-retrieve-the-missing-windows-product-patch/"><u>Expert Tips to Retrieve the Missing Windows Product Patch</u></a></li>
<li><a href="https://windows11.techidaily.com/flipping-a-non-working-search-bar-in-windows-11s-settings/"><u>Flipping a Non-Working Search Bar in Windows 11’S Settings</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-ultimate-checklist-streamlining-and-maximizing-screencast-quality-with-mobizen/"><u>[Updated] Ultimate Checklist  Streamlining and Maximizing Screencast Quality with Mobizen</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-solutions-to-find-your-vivo-t2x-5g-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>3 Solutions to Find Your Vivo T2x 5G Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-tecno-pop-8-drfone-by-drfone-virtual-android/"><u>What is the best Pokemon for pokemon pvp ranking On Tecno Pop 8? | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-unlocking-viewer-analysis-on-your-instagram-snapshots/"><u>[New] In 2024, Unlocking Viewer Analysis on Your Instagram Snapshots</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-optimize-your-browsing-experience-use-defender-aguard-in-win-11-edge/"><u>How to Optimize Your Browsing Experience: Use Defender Aguard in Win 11 Edge</u></a></li>
<li><a href="https://windows11.techidaily.com/balancing-audio-dynamics-for-bluetooth-devices/"><u>Balancing Audio Dynamics for Bluetooth Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-a-hidden-items-context-menu-option-in-windows-10-and-11/"><u>How to Add a Hidden Items Context Menu Option in Windows 10 & 11</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-step-by-step-how-to-download-and-personalize-whatsapp-ringtone-on-mobile-for-2024/"><u>[New] Step-By-Step  How to Download and Personalize WhatsApp Ringtone on Mobile for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/ensure-office-applications-open-email-attachments-as-text-only-by-design/"><u>Ensure Office Applications Open Email Attachments as Text Only by Design</u></a></li>
<li><a href="https://audio-editing.techidaily.com/2024-approved-audio-free-video-formats-mastering-the-art-of-silence-removal-in-popular-file-types-mp4-mkv-avi-mov-wmv/"><u>2024 Approved Audio-Free Video Formats Mastering the Art of Silence Removal in Popular File Types (MP4, MKV, AVI, MOV, WMV)</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-linguistic-landscapes-smoothly-via-keyboard-shortcuts-in-win1011/"><u>Navigate Linguistic Landscapes Smoothly via Keyboard Shortcuts in Win10/11</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-top-quality-economical-cam-recorder-for-2024/"><u>[Updated] Top Quality Economical Cam Recorder for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-guide-to-optimal-vr-headset-selection-freedom-or-connection/"><u>2024 Approved  Guide to Optimal VR Headset Selection  Freedom or Connection?</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-transform-your-digital-assets-top-7-tools-to-create-nfts/"><u>[Updated] Transform Your Digital Assets - Top 7 Tools to Create NFTs</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-efail-error-code-0x80004005-in-virtualbox/"><u>Combatting E_FAIL (Error Code: 0X80004005) in Virtualbox</u></a></li>
<li><a href="https://windows11.techidaily.com/explore-worldwide-efficient-mouse-skills-via-powertoys/"><u>Explore Worldwide - Efficient Mouse Skills via PowerToys</u></a></li>
<li><a href="https://windows11.techidaily.com/launching-the-system-rescue-console-easily/"><u>Launching the System Rescue Console Easily</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-harnessing-the-benefits-with-creative-commons-licenses/"><u>In 2024, Harnessing the Benefits with Creative Commons Licenses</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/2024-approved-techniques-for-altering-decibel-settings-on-media-playback/"><u>2024 Approved Techniques for Altering Decibel Settings on Media Playback</u></a></li>
<li><a href="https://windows11.techidaily.com/from-backup-bin-to-picture-panel-guiding-games-on-pcs-with-w11/"><u>From Backup Bin to Picture Panel: Guiding Games on PCs with W11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-lan-world-play-in-windows-mc-game/"><u>Mastering LAN World Play in Windows MC Game</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-bsod-errors-tackling-interrupt-exceptions-on-windows-11/"><u>Fixing BSOD Errors: Tackling Interrupt Exceptions on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/initiating-changes-accessing-fax-editor-in-the-newest-os/"><u>Initiating Changes: Accessing Fax Editor in the Newest OS</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-pro-slow-motion-selecting-the-best-mobile-camera-apps/"><u>In 2024, Pro Slow Motion  Selecting the Best Mobile Camera Apps</u></a></li>
<li><a href="https://video-capture.techidaily.com/audio-enthusiasts-guide-to-the-best-10-spotify-recorders-for-2024/"><u>Audio Enthusiast's Guide to the Best 10 Spotify Recorders for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/engagingnotabledarkthemefornotepadwin/"><u>EngagingNotableDarkThemeForNotepadWin</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-labels-for-efficient-file-management-on-windows-11/"><u>Leveraging Labels for Efficient File Management on Windows 11</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-free-gamers-guide-to-selecting-best-screen-recorder-apps/"><u>[New] 2024 Approved  Free Gamers' Guide to Selecting Best Screen Recorder Apps</u></a></li>
<li><a href="https://fix-guide.techidaily.com/in-2024-how-to-sharefake-location-on-whatsapp-for-itel-p55t-drfone-by-drfone-virtual-android/"><u>In 2024, How to Share/Fake Location on WhatsApp for Itel P55T | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-itel-p55plus-device-by-drfone-android/"><u>The Ultimate Guide How to Bypass Swipe Screen to Unlock on Itel P55+ Device</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-premier-virtual-tts-services-a-comprehensive-list-of-online-resources/"><u>2024 Approved Premier Virtual TTS Services A Comprehensive List of Online Resources</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-from-realme-note-50-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock from Realme Note 50 Phones with/without a PC</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-ppt-file-saving-challenges-swift-solutions-in-windows-11/"><u>Conquer PPT File Saving Challenges: Swift Solutions in Windows 11</u></a></li>
</ul></div>
