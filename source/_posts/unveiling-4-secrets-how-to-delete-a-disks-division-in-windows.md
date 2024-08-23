---
title: "Unveiling 4 Secrets: How to Delete a Disk's Division in Windows"
date: 2024-08-22T21:32:19.848Z
updated: 2024-08-23T21:32:19.848Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unveiling 4 Secrets: How to Delete a Disk's Division in Windows"
excerpt: "This Article Describes Unveiling 4 Secrets: How to Delete a Disk's Division in Windows"
keywords: Windows Data Removal,Disk Divide Deletion,Unknown Disk Hide,Secret Disk Erase,File System Restore,Windows Recovery Procedures,Safe PC Cleanup
thumbnail: https://thmb.techidaily.com/7f4ae1b9b31cac38f7f5bddb79d648495e38c22783ddea3f0c620d5fbd42617b.jpg
---

## Unveiling 4 Secrets: How to Delete a Disk's Division in Windows

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
 Enjoy working with the Command Prompt? If so, you will surely love our guide on [customizing the Command Prompt on Windows](https://www.makeuseof.com/windows-customize-command-prompt/).

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Once you run the above commands, PowerShell will delete the specified partition.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## There Are Many Ways to Delete Drive Partitions on Windows

 As we just saw, deleting a drive partition on Windows is a simple process, regardless of the method you use. Once you delete a partition, the space on that drive will be unallocated. You can then create a new partition on the empty space or use the space to expand an existing partition.

 This guide will show you how to delete a drive partition using the Settings app, Disk Management tool, Command Prompt, and PowerShell.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-enhance-your-stream-the-top-5-cameras-to-stand-out-on-twitch/"><u>[New] 2024 Approved  Enhance Your Stream  The Top 5 Cameras to Stand Out on Twitch</u></a></li>
<li><a href="https://article-files.techidaily.com/new-a-guide-to-pinpointing-a-list-video-creators-for-2024/"><u>[New] A Guide to Pinpointing A-List Video Creators for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-conveniently-altering-resolution-on-ios-devices/"><u>[New] Conveniently Altering Resolution on iOS Devices</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-top-3-affordable-switch-game-counterparts/"><u>[New] In 2024, Top 3 Affordable Switch Game Counterparts</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-off-mode-how-to-deactivate-igtv-for-2024/"><u>[New] Off Mode  How to Deactivate IGTV for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-starting-vlogging-right-the-top-equipmentsoftware/"><u>[New] Starting Vlogging Right  The Top Equipment/Software</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-the-untold-story-of-instagram-story-consumers/"><u>[Updated] 2024 Approved  The Untold Story of Instagram Story Consumers</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-free-meme-mastery-top-resources-for-creative-folks-for-2024/"><u>[Updated] Free Meme Mastery  Top Resources for Creative Folks for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-mc-homestead-plans-the-top-6/"><u>[Updated] MC Homestead Plans  The Top 6</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-exploring-beyond-boundaries-top-10-vlc-secrets/"><u>2024 Approved  Exploring Beyond Boundaries  Top 10 VLC Secrets</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-reactivate-and-enhance-photo-viewing-with-ease-win-11/"><u>2024 Approved  Reactivate and Enhance Photo Viewing with Ease (Win 11)</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-the-fourfold-path-to-blurring-iphone-images/"><u>2024 Approved  The Fourfold Path to Blurring iPhone Images</u></a></li>
<li><a href="https://driver-download.techidaily.com/download-xbox-wireless-controller-drivers-fast-and-simple-installation-guide/"><u>Download Xbox Wireless Controller Drivers - Fast and Simple Installation Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/file-explorer-missing-sd-card-resolution-guide/"><u>File Explorer Missing SD Card: Resolution Guide</u></a></li>
<li><a href="https://howto.techidaily.com/fix-app-not-available-in-your-country-play-store-problem-on-motorola-moto-g04-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix App Not Available in Your Country Play Store Problem on Motorola Moto G04 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-utorrent-connectivity-problems-on-pcs/"><u>Fixing uTorrent Connectivity Problems on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-voice-typing-malfunction-error-code-0x80049dd3-on-windows-11/"><u>Fixing Voice Typing Malfunction (Error Code: 0X80049DD3) on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-showhide-directories-on-modern-windows-11-pcs/"><u>Guide to Show/Hide Directories on Modern Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-error-code-0xc00000f-with-ease-on-pcs/"><u>Handling Error Code 0xC00000F with Ease on PCs</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-install-the-latest-ios-beta-version-on-iphone-6s-plus-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Install the Latest iOS Beta Version on iPhone 6s Plus? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-plain-out-windows-edges/"><u>How to Plain Out Windows Edges</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-frp-from-vivo-y200e-5g-by-drfone-android/"><u>In 2024, How to Bypass FRP from Vivo Y200e 5G?</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-x-marked-moments-in-the-22-snowboard-games/"><u>In 2024, X-Marked Moments in the '22 Snowboard Games</u></a></li>
<li><a href="https://windows11.techidaily.com/integrating-dns-client-service-in-windows-11-with-precision/"><u>Integrating DNS Client Service in Windows 11 with Precision</u></a></li>
<li><a href="https://windows11.techidaily.com/iphoneandroid-your-smartphone-as-a-windows-microphone/"><u>IPhone/Android: Your Smartphone as a Windows Microphone</u></a></li>
<li><a href="https://windows11.techidaily.com/key-collectors-rejoice-get-the-perfect-pair-of-keys-and-essential-windows-11-612lifetime/"><u>Key Collectors Rejoice – Get the Perfect Pair of Keys & Essential Windows 11, $6.12/Lifetime!</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-image-spin-6-tactics-for-windows-11/"><u>Mastering Image Spin: 6 Tactics for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-guide-to-inspecting-windows-11-history/"><u>Mastery Guide to Inspecting Windows 11 History</u></a></li>
<li><a href="https://windows11.techidaily.com/minimizing-distractions-with-wins-management-on-win-11/"><u>Minimizing Distractions with Wins Management on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-local-gpo-on-windows-with-ease/"><u>Navigating Local GPO on Windows with Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-past-windows-terminal-lockup/"><u>Navigating Past Windows Terminal Lockup</u></a></li>
<li><a href="https://windows11.techidaily.com/old-meets-new-a-windows-11-transformation-into-98-style/"><u>Old Meets New: A Windows 11 Transformation Into 98 Style</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-error-x8019-on-windows-xp/"><u>Preventing Error X8019 on Windows XP</u></a></li>
<li><a href="https://windows11.techidaily.com/purge-your-pcs-defender-footprint-with-easy-steps/"><u>Purge Your PC’s Defender Footprint with Easy Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-linguistic-leap-translating-words-via-windows-1011-hotkeys/"><u>Quick Linguistic Leap: Translating Words via Windows 10/11 Hotkeys</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-tips-reactivate-your-calendar-and-mail-on-w11/"><u>Quick Tips: Reactivate Your Calendar & Mail on W11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-discords-loading-failures-in-windows/"><u>Resolving Discord's Loading Failures in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-non-functional-activation-in-os-11/"><u>Resolving Non-Functional Activation in OS 11</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-note-taking-tips-for-windows-11-users/"><u>Seamless Note-Taking Tips for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-windows-7-techniques-against-uac-intrusions/"><u>Securing Windows: 7 Techniques Against UAC Intrusions</u></a></li>
<li><a href="https://windows11.techidaily.com/speeding-up-epic-games-installation-windows-wise/"><u>Speeding Up Epic Games Installation Windows-Wise</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-rectify-non-registered-hdds/"><u>Techniques to Rectify Non-Registered HDDs</u></a></li>
<li><a href="https://fox-that.techidaily.com/1721441494783-the-mystery-of-an-offline-find-my-iphone-device-heres-what-you-can-do/"><u>The Mystery of an Offline Find My iPhone Device? Here’s What You Can Do</u></a></li>
<li><a href="https://data-wizards.techidaily.com/the-totan-banerjee-technique-for-bringing-lost-files-back-to-life/"><u>The Totan Banerjee Technique for Bringing Lost Files Back to Life</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-tech-reviews-insights-from-the-leading-hardware-experts/"><u>Tom's Tech Reviews: Insights From the Leading Hardware Experts</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-spotify-link-failures-on-pcs-windows/"><u>Troubleshooting Spotify Link Failures on PCs (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/turn-onoff-text-emphasis-and-highlight-effects-on-pc/"><u>Turn On/Off Text Emphasis and Highlight Effects on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/turn-onoff-windows-key-like-a-pro/"><u>Turn On/Off Windows Key Like a Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-copy-and-paste-features-with-application-guard-in-edge-w11-edition/"><u>Unlocking Copy & Paste Features with Application Guard in Edge, W11 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-7-key-windows-11-widgets-for-enhanced-productivity/"><u>Unveiling 7 Key Windows 11 Widgets for Enhanced Productivity</u></a></li>
<li><a href="https://windows11.techidaily.com/visualizing-disks-wisely-the-windows-methodology/"><u>Visualizing Disks Wisely: The Windows Methodology</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>