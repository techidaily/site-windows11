---
title: Strategies for Controlling File Compression in Windows 11
date: 2024-07-11T22:09:03.867Z
updated: 2024-07-12T22:09:03.867Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strategies for Controlling File Compression in Windows 11
excerpt: This Article Describes Strategies for Controlling File Compression in Windows 11
keywords: Win11 Compression Control,File Size Reduction,Decompressing Files,Limit Data Loss,Optimize Storage Space,Compression Techniques Windows,Windows 11 Save Space
thumbnail: https://thmb.techidaily.com/ba715f0751b3e95d85d54c2de37214787de2fc86eeb6be2647ab887e34352c43.jpg
---

## Strategies for Controlling File Compression in Windows 11

 Is your Windows computer running out of storage? There are plenty of ways to remove redundant data and free up some extra space. Among all, the most preferred method is using NTFS file compression.

 NTFS file compression is a Windows feature that compresses files and folders by removing reductant data from them. The best part about this feature is that it does its job without damaging the file and losing the data.

 Nevertheless, let's check out some ways to enable NTFS file compression in Windows 11.

## 1\. Enable NTFS File Compression Through the File Explorer

 The quickest way to enable NTFS [file compression](https://www.makeuseof.com/windows-11-file-compression-guide/) is through File Explorer. Below are the steps to compress a folder:

1. Open the File Explorer and head toward the folder you want to compress.
2. Right-click on the target folder and choose**Properties** from the context menu.
3. In the**General** tab, select the**Advanced** option.
4. Under the**Compress or Encrypt attributes** section, check the**Compress contents to save disk space** box and click**OK** .  
![Compress content to save disk option in Folder properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/compress-content-to-save-disk-option.jpg)
5. Click**Apply** \>**OK** to save the changes.
6. In the confirmation dialog box that crops up, choose the **Apply changes to this folder, subfolders, and files option** .  
![Apply changes option in folder properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/apply-changes-option.jpg)
7. Click**OK.**

 That's it, the folder has now been compressed. You can confirm this by comparing the current folder size with its previous size.

 From now on, every file or folder that you will move inside the compressed folder will be compressed automatically. To disable compression, uncheck the**Compress contents to save disk space** box and save the changes.

Similarly, you can compress an entire drive. Here's how:

1. Open the File Explorer, and right-click on the drive you want to compress.
2. In the**General** tab, check the**Compress this drive to save disk space** box.  
![Driver properties in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/driver-properties.jpg)
3. Click**Apply** and then click**OK** on the confirmation box that crops up.

## 2\. Enable NTFS File Compression Using the Command Prompt

 If you are a power user, you can use the Command Prompt to enable file compression on Windows 11\. Here are the steps to do it:

1. Press the**Win + S** hotkeys to open the**Windows Search.**
2. In the search bar, type**Command Prompt** and choose**Run as administrator** from the right pane. If this method is not working, you can use any other way to [open Command Prompt with admin rights](https://www.makeuseof.com/how-to-always-open-command-prompt-as-administrator-windows/) .
3. Type the following command and press**Enter** to enable file compression.  
`fsutil behavior set disablecompression 0`

![File compression command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/file-compression-command.jpg)

 You'll see the "**A reboot is required for this change to take effect** " message on the console. So, restart your computer to apply the changes.

 If you want to disable File Compression, execute the following command in the elevated Command Prompt window, followed by a system restart.

`fsutil behavior set disablecompression 1`

## 3\. Enable NTFS File Compression Using the Registry Editor

 Another quick way to enable compression is through the Registry Editor. Follow the below steps to do it:

1. Open the**Run dialog box** by pressing the**Win + R** hotkeys.
2. Type**regedit** in the text field and click**OK.**
3. In the Registry Editor, navigate to the below location:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Policies`
4. Right-click on the**Policies** folder in the left sidebar, hover the cursor to**New,** and choose**DWORD** **(32-bit) Value** from the context menu.  
![Choosing DWORD in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/choosing-dword.jpg)
5. Right-click on the newly created value and choose**Rename** .
6. Type**Ntfsenablecompression** in the text field.
7. Select and right-click on**Ntfsenablecompression** again, and choose**Modify** .
8. Type**1** in the**Value data** .  
![Editing Ntfsenablecompression in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/editing-ntfsenablecompression.jpg)
9. Click**OK** to save the changes.

 File compression is now enabled on your computer. If you want to disable it, type 0 in Value data and save the changes.

## 4\. Enable NTFS File Compression Using the Local Group Policy Editor

 The Local Group Policy Editor is the go-to place to configure important Windows policies. To use it to enable file compression, follow the below instructions:

1. In the Run dialog box, type**gpedit.msc** and click**OK.**
2. Head towards the following location in the Local Group Policy Editor:  
`Computer Configuration\Administrative Templates\System\Filesystem\NTFS`
3. Double-click on the**Do not allow compression on all NTFS volumes policy** to open its properties window.
4. Choose the**Disabled** option.  
![Disabling policy in LGPE](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/disabling-policy.jpg)
5. Click**Apply** \>**OK** to enable file compression.

 You can disable the file compression by choosing the**Enabled** option in the**Do not allow compression on all NTFS volumes policy** properties window.

## Free Up Space on Windows 11 With File Compression

 Enabling file compression is a great way to free up some space on Windows 11\. Using this feature can come in handy when you are running out of space but also don't want to compress your files using third-party compression tools.

 Meanwhile, you might be interested in learning more about the NTFS file system.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>



<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/overcoming-windows-auto-detection-errors/"><u>Overcoming Windows Auto Detection Errors</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-hassle-free-solutions-to-fake-location-on-find-my-friends-of-honor-play-40c-drfone-by-drfone-virtual-android/"><u>5 Hassle-Free Solutions to Fake Location on Find My Friends Of Honor Play 40C | Dr.fone</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-exploring-options-a-treasure-hunt-for-your-tiktok-symbol/"><u>[New] In 2024, Exploring Options  A Treasure Hunt for Your TikTok Symbol</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-2024-approved-modifying-sound-intensity-in-video-and-music-files/"><u>Updated 2024 Approved Modifying Sound Intensity in Video and Music Files</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-halt-microsoft-edge-icons-regularity/"><u>How to Halt Microsoft Edge Icons' Regularity</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-channel-boosting-strategies-effortless-sponsorship-securing-tips/"><u>[New] 2024 Approved  Channel Boosting Strategies  Effortless Sponsorship Securing Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/overhauling-write-operations-failure-fixes-on-windows/"><u>Overhauling Write Operations Failure Fixes on Windows</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-the-enhanced-experience-of-movavi-video-pro/"><u>2024 Approved  The Enhanced Experience of Movavi Video Pro</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-seamless-streaming-tackle-instagram-video-woes/"><u>[New] In 2024, Seamless Streaming  Tackle Instagram Video Woes</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-through-faulty-shift-in-windows/"><u>Navigate Through Faulty Shift in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-empty-folder-warning-in-windows-11/"><u>Eliminating 'Empty Folder' Warning in Windows 11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-best-android-sim-unlock-code-generators-unlock-your-asus-phone-hassle-free-by-drfone-android/"><u>The Best Android SIM Unlock Code Generators Unlock Your Asus Phone Hassle-Free</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-2024-approved-direct-download-wizardry-turning-tiktok-to-perfect-mp4s/"><u>[New] 2024 Approved  Direct Download Wizardry  Turning TikTok to Perfect MP4s</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-integrating-seamlessly-into-tiktok-lives-a-blueprint/"><u>In 2024, Integrating Seamlessly Into TikTok Lives  A Blueprint</u></a></li>
<li><a href="https://windows11.techidaily.com/newbies-in-the-windows-world-steer-clear-of-these-top-8-faux-pas/"><u>Newbies in the Windows World: Steer Clear of These Top 8 Faux Pas</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-utilize-windows-for-handwritten-input/"><u>How to Utilize Windows for Handwritten Input</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-nvidia-connect-failure-on-windows-11-systems/"><u>Fixing Nvidia Connect Failure on Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/rapid-and-secure-firmware-update-guide-for-surface-systems/"><u>Rapid & Secure Firmware Update Guide for Surface Systems</u></a></li>
<li><a href="https://extra-tips.techidaily.com/unlocking-10plus-top-free-subtitle-converter-websites/"><u>Unlocking 10+ Top Free Subtitle Converter Websites</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-wi-fi-connectivity-hurdles-clearing-action-shortcomings/"><u>Overcoming Wi-Fi Connectivity Hurdles: Clearing Action Shortcomings</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-smile-and-watch-your-guide-to-the-top-15-funny-youtubers/"><u>[New] Smile and Watch  Your Guide to the Top 15 Funny YouTubers</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-reinstalling-failing-drivers-in-win11-system/"><u>Guide to Reinstalling Failing Drivers in Win11 System</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-stabilize-an-unstable-printer-on-windows/"><u>How to Stabilize an Unstable Printer on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-wire-free-audio-on-windows-airpods/"><u>Guide to Wire-Free Audio on Windows (AirPods)</u></a></li>
<li><a href="https://windows11.techidaily.com/distinguishing-between-hdd-and-ssd-drives-on-pc/"><u>Distinguishing Between HDD & SSD Drives on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/merge-your-world-connecting-android-and-windows-11-tablets/"><u>Merge Your World: Connecting Android and Windows 11 Tablets</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/rhythm-research-capture-and-review-music-files-for-2024/"><u>Rhythm Research  Capture & Review Music Files for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-the-cutting-edge-gaming-earpieces-for-youtubers/"><u>[New] The Cutting-Edge Gaming Earpieces for YouTubers</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-mysteries-of-ram-in-windows-devices/"><u>Decoding the Mysteries of RAM in Windows Devices</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-expert-voice-editing-software-for-video-content-makers/"><u>[Updated] In 2024, Expert Voice Editing Software for Video Content Makers</u></a></li>
<li><a href="https://windows11.techidaily.com/guides-to-mastering-your-fax-interface-with-w11s-tools/"><u>Guides to Mastering Your Fax Interface with W11's Tools</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-how-do-you-get-sun-stone-evolutions-in-pokemon-for-apple-iphone-8-drfone-by-drfone-virtual-ios/"><u>In 2024, How Do You Get Sun Stone Evolutions in Pokémon For Apple iPhone 8? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/re-establishing-printer-linkage-in-windows-11-setup/"><u>Re-Establishing Printer Linkage in Windows 11 Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-the-not-an-empty-directory-alert-error-code-0x80070091-in-win11/"><u>Conquering the Not an Empty Directory Alert (Error Code: 0X80070091) in Win11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-ranking-the-real-heavies-youtube-video-watch-hours-top-10/"><u>[New] Ranking the Real Heavies  YouTube Video Watch Hours Top 10</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-elevated-privileges-for-power-users-a-guide/"><u>Enabling Elevated Privileges for Power Users: A Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/reestablish-wi-fi-masterful-solutions-for-windows-usb-adapters/"><u>Reestablish Wi-Fi: Masterful Solutions for Windows USB Adapters</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-walking-through-time-a-guide-to-inverted-videos-on-instagram/"><u>In 2024, Walking Through Time  A Guide to Inverted Videos on Instagram</u></a></li>
<li><a href="https://windows11.techidaily.com/live-transcribing-made-easy-the-whisper-way/"><u>Live Transcribing Made Easy - The Whisper Way</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-your-window-experience-mastering-the-start-menu/"><u>Enhance Your Window Experience: Mastering the Start Menu</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-ultimate-video-upgrade-pathway-sdr-to-hdri-transformation-techniques/"><u>In 2024, The Ultimate Video Upgrade Pathway  SDR to HDRI Transformation Techniques</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-youtube-video-dimension-standards/"><u>[Updated] 2024 Approved  YouTube Video Dimension Standards</u></a></li>
<li><a href="https://windows11.techidaily.com/prying-into-hidden-taskbar-analysis-tool-in-windows-11/"><u>Prying Into Hidden Taskbar Analysis Tool in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-correctly-installing-apps-from-ms-store/"><u>Mastering the Art of Correctly Installing Apps From MS Store</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-sync-up-to-share-live-moments-on-tiktok-for-2024/"><u>[Updated] Sync Up to Share Live Moments on TikTok for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/playnite-extension-virtual-games-collection/"><u>Playnite Extension: Virtual Games Collection</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/in-2024-this-article-presents-the-guide-to-using-magic-effects-for-creating-competent-films-with-step-by-step-instructions-and-filmoras-grow-and-win-program/"><u>In 2024, This Article Presents the Guide to Using Magic Effects for Creating Competent Films with Step-by-Step Instructions and Filmoras Grow and Win Program Contest</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-and-fixing-invalid-temp-directories-on-win11/"><u>Preventing and Fixing Invalid Temp Directories on Win11</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/top-9-amv-makers-for-computer/"><u>Top 9 AMV Makers for Computer</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/avoiding-common-nocturnal-photography-errors-for-2024/"><u>Avoiding Common Nocturnal Photography Errors for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/direct-path-to-spooler-restart/"><u>Direct Path to Spooler Restart</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-your-vivo-x-flip-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>In 2024, How to Mirror Your Vivo X Flip Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-bypass-android-lock-screen-using-emergency-call-on-oppo-reno-11-5g-by-drfone-android/"><u>In 2024, How to Bypass Android Lock Screen Using Emergency Call On Oppo Reno 11 5G?</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-managing-events-with-windows-11-calendar/"><u>Efficiently Managing Events with Windows 11 Calendar</u></a></li>
<li><a href="https://techidaily.com/hard-resetting-an-samsung-galaxy-a05s-device-made-easy-drfone-by-drfone-reset-android-reset-android/"><u>Hard Resetting an Samsung Galaxy A05s Device Made Easy | Dr.fone</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-essential-color-grading-techniques-a-beginners-guide/"><u>2024 Approved  Essential Color Grading Techniques  A Beginner's Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-xbox-game-pass-0x800700e9-error-in-windows-11-and-11/"><u>How to Fix the Xbox Game Pass 0X800700e9 Error in Windows 11 & 11</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/the-essence-of-great-edu-videos-a-compreenasion-guide-to-youtube-excellence/"><u>The Essence of Great Edu-Videos  A Compreenasion Guide to YouTube Excellence</u></a></li>
<li><a href="https://windows11.techidaily.com/hidden-sd-card-regain-access-with-troubleshooting-guide/"><u>Hidden SD Card: Regain Access with Troubleshooting Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/make-file-management-simple-using-windows-autodelete-feature/"><u>Make File Management Simple: Using Windows' Autodelete Feature</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-nintendo-switch-capturing-your-playtime/"><u>[New] Nintendo Switch  Capturing Your Playtime</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-discovering-the-best-8-android-compatible-daws-for-musicians-and-producers/"><u>New Discovering the Best 8 Android-Compatible DAWs for Musicians and Producers</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-top-20-mobiles-transforming-dji-aerial-video-art/"><u>In 2024, Top 20 Mobiles Transforming DJi Aerial Video Art</u></a></li>
<li><a href="https://windows11.techidaily.com/invisible-disk-hiding-tricks-in-win11w10/"><u>Invisible Disk Hiding Tricks in Win11/W10</u></a></li>
</ul></div>
