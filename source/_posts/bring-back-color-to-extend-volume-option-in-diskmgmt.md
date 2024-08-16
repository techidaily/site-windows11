---
title: Bring Back Color to Extend Volume Option in DiskMgmt
date: 2024-08-15T16:06:06.292Z
updated: 2024-08-16T16:06:06.292Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Bring Back Color to Extend Volume Option in DiskMgmt
excerpt: This Article Describes Bring Back Color to Extend Volume Option in DiskMgmt
keywords: Extend Volume Color Enhance,Restore Disk Colors,Volume Brightening Tech,Dynamic Volume Shading,Increase Disk Luminosity,Volume Amplification,Revive Disk Hue Options
thumbnail: https://thmb.techidaily.com/192f81e62d92a192c6756d4acefa6e25619bd0109c72bd43d2bf00cf25a87ef6.png
---

## Bring Back Color to Extend Volume Option in DiskMgmt

 The "extend volume" option in the Disk Management tool enables you to increase the size of a volume or partition. However, there may be a situation where the extend volume option may be grayed out, preventing you from increasing the volume.

 If this is happening to you, try the below solutions for a grayed-out "extend volume" option on Windows

## Why Is the Extend Volume Option Grayed Out on Windows?

 If you see the extend volume option is grayed out in the Disk Management tool, there are a few possible reasons:

1. The unallocated space is not located directly next to the partition you want to extend.
2. The partition's file system is not supported on Windows.
3. The extend volume option will be grayed out if your drive has no unallocated space.

 Now that you know all the possible culprits behind the issue, let's check out all the solutions that can help fix it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
## 1\. Convert the Partition to an NTFS File System

 Windows only supports certain [file systems](https://www.makeuseof.com/tag/from-fat-to-ntfs-to-zfs-file-systems-demystified-makeuseof-explains/) for partitions. If the partition you want to extend is formatted in a file system incompatible with Windows, you will not be able to extend it.

 To extend the partition, you must format the partition and convert it into an NTFS file system. However, formatting the partition will delete all the data, so make sure to [back up the data on the partition](https://www.makeuseof.com/ways-to-back-up-data/) first.

 To convert the partition to an NTFS file system, follow these steps:

1. Right-click on the partition and select **Format**.
2. Choose **NTFS** from the File system drop-down menu. Then, click **OK**.  
![File system option in Disk Management tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/file-system-option.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->

 The formatting process may take some time, depending on the amount of data on the partition. Once done, restart your computer and check if the issue is resolved.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
## 2\. Delete a Partition and Create Unallocated Space

 The "extend volume" option will gray out if there is no unallocated space next to the partition you want to extend. To create unallocated space, you will have to delete a partition that is next to the partition you want to extend.

 If the partition is a normal volume, you can simply right-click on it and select **Delete Volume**. However, if the partition contains data, make sure to back it up before deleting it.

![Delete Volume option in Disk Management tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-volume-option.jpg)

 If the partition is a recovery partition, you cannot delete it using Disk Management. You'll have to delete it using the Command Prompt. Here are the steps to do it:

1. Press the **Win** key to open the Start Menu, type **Command** **Prompt**, and choose **Run as administrator** from the right pane. If this method doesn't work, check out other [ways to launch Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Type **DiskPart** and press **Enter**.
3. Type **list disk** and press **Enter**. This command will display all the available disks.  
![list disk command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/list-disk-command-2.jpg)
4. Select the disk that you want to extend. For example, if you want to extend disk 0, type **select disk 0** and press **Enter**.
5. Type **list partition** and press **Enter**. This will list all the partitions on the disk.  
![list partition command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/list-partition.jpg)
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
6. In the Type column, look for the partition that says **Recovery**. Note the partition number. For example, if the partition number is 4, type **select partition 4** and press **Enter**. This will select the recovery partition.
7. To delete the recovery partition, type **delete partition override** and press **Enter**.  
![delete partition override command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-partition-override.jpg)

 You will see the message **DiskPart successfully deleted the selected partition**. This indicates that the recovery partition has been deleted.

![DiskPart successfully deleted the selected partition message in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/diskpart-successfully-deleted-the-selected-partition.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->

 Next, open the Disk Management tool, and you will see an unallocated space next to the partition you want to extend. Right-click on the partition, choose **Extend** **Volume**, and then click **Next**.

![Extend partition option in Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/extend-partition-option.jpg)

 Once the wizard completes, you will see the partition size has been increased.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://youtube-docs.techidaily.com/024-approved-direct-conversion-convert-and-upload-mp3-songs-on-youtube/"><u>[New] 2024 Approved  Direct Conversion  Convert & Upload MP3 Songs on YouTube</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-commanding-voice-performance-analysis-edition-8/"><u>[New] Commanding Voice Performance Analysis, Edition 8</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-how-much-money-does-mr-beast-make/"><u>[New] How Much Money Does Mr. Beast Make</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-mastering-hue-shifts-a-guide-to-efficient-photoshop-corrections/"><u>[New] Mastering Hue Shifts  A Guide to Efficient Photoshop Corrections</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-voip-excellence-showdown-discord-vs-skype-analysis/"><u>[New] VoIP Excellence Showdown  Discord vs Skype Analysis</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-crafting-an-epic-tiktok-farewell-sequence/"><u>[Updated] 2024 Approved  Crafting An Epic TikTok Farewell Sequence</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-universal-method-for-screen-recording-across-systems/"><u>[Updated] In 2024, Universal Method for Screen Recording Across Systems</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-record-gameplay-with-obs-studio-for-2024/"><u>[Updated] Record Gameplay with OBS Studio for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-commanders-clash-the-ultimate-ranking-of-7-total-war-games/"><u>2024 Approved  Commanders' Clash  The Ultimate Ranking of 7 Total War Games</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-simplifying-slide-sharing-using-your-webcam-effectively/"><u>2024 Approved  Simplifying Slide Sharing  Using Your Webcam Effectively</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-the-ultimate-guide-to-crafting-exquisite-hdr-portraits/"><u>2024 Approved  The Ultimate Guide to Crafting Exquisite HDR Portraits</u></a></li>
<li><a href="https://windows11.techidaily.com/6-quick-ways-to-fix-the-powerpoint-cant-save-file-error-in-windows-11/"><u>6 Quick Ways to Fix the PowerPoint Can't Save File Error in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-tips-for-efficient-toolbar-usage-in-microsoft-win11-pcm/"><u>Advanced Tips for Efficient Toolbar Usage in Microsoft Win11 PCM</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-vpna-to-fake-gps-location-on-realme-v30t-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use VPNa to Fake GPS Location On Realme V30T | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/curating-edthemes-experience-on-windows-11/"><u>Curating EdThemes Experience on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-windows-11-camera-app-error-0xa00f425d-fixes/"><u>Disabling Windows 11 Camera App Error 0xA00F425D Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-vivetool-your-ticket-to-access-latest-windows-innovations/"><u>Discover ViVeTool: Your Ticket to Access Latest Windows Innovations</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-acer-wi-fi-drivers-for-free-simple-setup-tutorial/"><u>Download Acer Wi-Fi Drivers for Free – Simple Setup Tutorial</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-integration-portable-software-menus-for-w11plus/"><u>Easy Integration: Portable Software Menus for W11+</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/elevate-your-engagement-with-real-time-tweets-for-2024/"><u>Elevate Your Engagement with Real-Time Tweets for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminate-loadlibrary-error-87-misconfiguration/"><u>Eliminate LoadLibrary Error 87 Misconfiguration</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/enrich-your-visuals-captions-on-the-go-in-instagram-for-2024/"><u>Enrich Your Visuals  Captions on the Go in Instagram for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicating-your-input-cant-be-opened-vlc-error/"><u>Eradicating 'Your Input Can't Be Opened' VLC Error</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/essential-game-picks-ghost-of-tsushima-rival-edition-in-2024/"><u>Essential Game Picks  Ghost of Tsushima Rival Edition, In 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-advice-for-seamlessly-entering-fullscreen-mode/"><u>Expert Advice for Seamlessly Entering Fullscreen Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-missing-initialization-message-on-windows-pc/"><u>Fixing 'Missing Initialization' Message on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-monochrome-errors-with-marketplace/"><u>Fixing Monochrome Errors with Marketplace</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-the-nvidia-setup-not-available-glitch/"><u>Fixing the 'Nvidia Setup Not Available' Glitch</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/honor-x50-gt-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>Honor X50 GT ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-frp-from-xiaomi-13t-pro-by-drfone-android/"><u>How to Bypass FRP from Xiaomi 13T Pro?</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-conquer-common-errors-during-windows-11-rollout/"><u>How to Conquer Common Errors During Windows 11 Rollout</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-lock-apps-on-honor-play-40c-to-protect-your-individual-information-by-drfone-android/"><u>How to Lock Apps on Honor Play 40C to Protect Your Individual Information</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-share-location-in-messenger-on-vivo-x100-pro-drfone-by-drfone-virtual-android/"><u>How to Share Location in Messenger On Vivo X100 Pro? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/illuminate-with-joy-magical-holiday-window-decor/"><u>Illuminate with Joy: Magical Holiday Window Decor</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-a-comprehensive-guide-to-mastering-ipogo-for-pokemon-go-on-apple-iphone-15-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, A Comprehensive Guide to Mastering iPogo for Pokémon GO On Apple iPhone 15 Pro | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-a-working-guide-for-pachirisu-pokemon-go-map-on-xiaomi-13t-drfone-by-drfone-virtual-android/"><u>In 2024, A Working Guide For Pachirisu Pokemon Go Map On Xiaomi 13T | Dr.fone</u></a></li>
<li><a href="https://article-helps.techidaily.com/in-2024-augment-slides-with-sonic-enhancements/"><u>In 2024, Augment Slides with Sonic Enhancements</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-gps-joystick-to-fake-gps-location-on-vivo-v30-lite-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Complete Tutorial to Use GPS Joystick to Fake GPS Location On Vivo V30 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-elite-ipad-speech-recording-tools-3/"><u>In 2024, Elite iPad Speech Recording Tools #3</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-12-pro-apples-new-iphone-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone 12 Pro, Apples New iPhone</u></a></li>
<li><a href="https://fox-glue.techidaily.com/in-2024-mobile-tools-optimize-and-enhance-audio-faster/"><u>In 2024, Mobile Tools  Optimize and Enhance Audio Faster</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-strategies-for-selecting-and-syncing-music-with-visuals/"><u>In 2024, Strategies for Selecting and Syncing Music with Visuals</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-unlock-infinix-hot-30-5g-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>In 2024, Unlock Infinix Hot 30 5G Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://windows11.techidaily.com/legacy-unlocks-employing-a-windows-7-key-in-11-setup/"><u>Legacy Unlocks: Employing a Windows 7 Key in 11 Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/meeting-prep-101-test-your-windows-webcam-microphone/"><u>Meeting Prep 101: Test Your Windows Webcam, Microphone</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-onedrive-errors-on-windows-11-an-experts-fix-list/"><u>Navigating OneDrive Errors on Windows 11: An Expert's Fix List</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-the-maze-of-windows-error-code-0xc00000f/"><u>Navigating Through the Maze of Windows Error Code 0Xc00000f</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-nullnone-value-dilemmas-on-windows/"><u>Overcoming Null/None Value Dilemmas on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-win-os-extract-issues-saving-time-with-error-1152-solution/"><u>Overcoming Win OS Extract Issues: Saving Time with Error 1152 Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-shift-script-moving-windows-11-selected-files/"><u>Quick Shift Script: Moving Windows 11 Selected Files</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-tip-addressing-winscomrsvc-system-crashes/"><u>Quick Tip: Addressing WinscomrsVc System Crashes</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-marketplace-failures-x80131500/"><u>Resolving Windows Marketplace Failures X80131500</u></a></li>
<li><a href="https://youtube-web.techidaily.com/-the-momentum-channels-best-inspirational-videos/"><u>Spark the Momentum  Channel's Best Inspirational Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-to-become-a-win-11-insider/"><u>Step-by-Step to Become a Win 11 Insider</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-resolving-installation-issues-with-microsoft-store-apps/"><u>Steps for Resolving Installation Issues with Microsoft Store Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-frozen-pages-and-scrolling-issues-in-excel/"><u>Stop Frozen Pages and Scrolling Issues in Excel</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/the-influence-of-learning-english-on-careers/"><u>The Influence of Learning English on Careers</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-pinpointing-device-serial-numbers-on-windows/"><u>The Ultimate Guide to Pinpointing Device Serial Numbers on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-the-finest-free-car-performance-fixes/"><u>The Ultimate Guide to the Finest Free Car Performance Fixes</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/to-upgrade-or-not-evaluating-the-need-for-an-rtx-graphics-processor/"><u>To Upgrade or Not: Evaluating the Need for an RTX Graphics Processor</u></a></li>
<li><a href="https://windows11.techidaily.com/top-6-windows-11-prime-fps-monitors-and-trackers/"><u>Top 6 Windows 11: Prime FPS Monitors & Trackers</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-text-selection-power-in-windows-pdf-files/"><u>Unleashing Text Selection Power in Windows PDF Files</u></a></li>
<li><a href="https://activate-lock.techidaily.com/unlock-your-device-icloud-dns-bypass-explained-and-tested-plus-easy-alternatives-on-apple-iphone-8-by-drfone-ios/"><u>Unlock Your Device iCloud DNS Bypass Explained and Tested, Plus Easy Alternatives On Apple iPhone 8</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-11-entry-into-the-insider-trials/"><u>Unveiling Windows 11: Entry Into the Insider Trials</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-revolution-essential-replacement-tools-to-consider/"><u>Win 11 Revolution: Essential Replacement Tools to Consider</u></a></li>
<li><a href="https://windows11.techidaily.com/win11s-guide-to-stable-background-fixes/"><u>Win11's Guide to Stable Background Fixes</u></a></li>
</ul></div>
