---
title: "Enhance Windows 11 Performance: Tweak NTFS File Compression"
date: 2024-07-11T21:15:58.756Z
updated: 2024-07-12T21:15:58.756Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Enhance Windows 11 Performance: Tweak NTFS File Compression"
excerpt: "This Article Describes Enhance Windows 11 Performance: Tweak NTFS File Compression"
keywords: Win11 Speed Boost,Optimize NTFS,Reduce File Size,Enhance PC Speed,Compress Files Less,Improve Windows Performance,Tweak File Compression
thumbnail: https://thmb.techidaily.com/61f1e99d6299e2b7e5df71d7f81a59ac930cb2c81d484489a08d43204f560599.jpg
---

## Enhance Windows 11 Performance: Tweak NTFS File Compression

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
<li><a href="https://windows11.techidaily.com/unlocking-image-precision-with-windows-11s-blurring-feature-in-photos-app/"><u>Unlocking Image Precision with Windows 11'S Blurring Feature in Photos App</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-track-imei-number-of-xiaomi-redmi-k70-pro-through-google-earth-by-drfone-android/"><u>How To Track IMEI Number Of Xiaomi Redmi K70 Pro Through Google Earth?</u></a></li>
<li><a href="https://windows11.techidaily.com/5-strategies-for-resolving-the-no-support-windows-error/"><u>5 Strategies for Resolving the No-Support Windows Error</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-streamlined-social-media-prime-twitter-unfollow-tools-overview/"><u>[New] 2024 Approved  Streamlined Social Media  Prime Twitter Unfollow Tools Overview</u></a></li>
<li><a href="https://windows11.techidaily.com/supercharge-efficiency-select-windows-software-for-success/"><u>Supercharge Efficiency: Select Windows Software for Success</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-chromeedge-from-hiding-taskbar-on-large-screens/"><u>Preventing Chrome/Edge From Hiding Taskbar on Large Screens</u></a></li>
<li><a href="https://windows11.techidaily.com/take-control-of-your-workflow-learn-these-essential-cmd-commands/"><u>Take Control of Your Workflow: Learn These Essential CMD Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-error-0x80042306-on-windows-to-reset-successfully/"><u>Tackling Error 0X80042306 on Windows to Reset Successfully</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-say-goodbye-to-shaky-cam-stabilizing-your-videos-in-premiere-pro/"><u>New 2024 Approved Say Goodbye to Shaky Cam Stabilizing Your Videos in Premiere Pro</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-harness-the-full-potential-of-video-tags-in-youtube/"><u>[New] In 2024, Harness the Full Potential of Video Tags in YouTube</u></a></li>
<li><a href="https://extra-hints.techidaily.com/leading-free-converters-ranking-the-10-for-jpg-to-gif-changeover/"><u>Leading Free Converters  Ranking the 10 for JPG to GIF Changeover</u></a></li>
<li><a href="https://youtube-web.techidaily.com/l-vocabulary-complimentary-youtube-art-tools-for-2024/"><u>Visual Vocabulary  Complimentary YouTube Art Tools for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/triggering-the-verification-toolset-for-win11-systems/"><u>Triggering the Verification Toolset for Win11 Systems</u></a></li>
<li><a href="https://review-topics.techidaily.com/nokia-data-retrieval-tool-restore-lost-data-from-nokia-130-music-by-fonelab-android-recover-data/"><u>Nokia Data Retrieval tool – restore lost data from Nokia 130 Music</u></a></li>
<li><a href="https://windows11.techidaily.com/win10s-method-for-onedrive-placement-shift/"><u>Win10's Method for OneDrive Placement Shift</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-sync-your-sound-instagrams-musical-world-for-2024/"><u>[New] Sync Your Sound  Instagram's Musical World for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-re-establish-winning-online-wol-experience/"><u>Steps to Re-Establish Winning Online WoL Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/the-path-to-professional-print-perfection-nine-key-techniques-for-powerpoint-on-pcs/"><u>The Path to Professional Print Perfection: Nine Key Techniques for PowerPoint on PCs</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ultimate-guide-to-get-the-meltan-box-pokemon-go-for-lenovo-thinkphone-drfone-by-drfone-virtual-android/"><u>Ultimate guide to get the meltan box pokemon go For Lenovo ThinkPhone | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/best-windows-laptops-a-forward-looking-2024-review/"><u>Best Windows Laptops: A Forward-Looking 2024 Review</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-non-attached-usb-device-dilemma-in-virtualbox-environment/"><u>Tackling Non-Attached USB Device Dilemma in VirtualBox Environment</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-proven-linux-programs-for-flawless-screen-captures/"><u>[Updated] Proven Linux Programs for Flawless Screen Captures</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-teach-you-to-transfer-files-from-honor-100-pro-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways To Teach You To Transfer Files from Honor 100 Pro to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/1719278005537-mastery-of-solutions-for-non-operational-wwinplusp-in-pc/"><u>Mastery of Solutions for Non-Operational WWin+P in PC.</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-shared-printer-issues-on-windows-11/"><u>Addressing Shared Printer Issues on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/sparkle-up-windows-11-for-the-festive-season/"><u>Sparkle Up Windows 11 for the Festive Season</u></a></li>
<li><a href="https://windows11.techidaily.com/reimagining-taskbar-functionality-essential-upgrades-to-improve-microsofts-user-interface/"><u>Reimagining Taskbar Functionality: Essential Upgrades to Improve Microsoft's User Interface</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-proven-techniques-to-take-your-obs-studio-videos-to-new-heights/"><u>[New] Proven Techniques to Take Your OBS Studio Videos to New Heights</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-in-2024-10-best-free-video-player-for-windows-11/"><u>Updated In 2024, 10 Best Free Video Player for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-to-mending-directdraw-glitches-in-11-series-oses/"><u>Quick Guide to Mending DirectDraw Glitches in 11-Series OSes</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-switching-spotify-playlists-transferring-to-youtube-music-format/"><u>In 2024, Switching Spotify Playlists  Transferring to YouTube Music Format</u></a></li>
<li><a href="https://windows11.techidaily.com/safekeep-your-files-setting-up-folder-restrictions-in-windows-11/"><u>Safekeep Your Files: Setting Up Folder Restrictions in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-roadblocks-activating-non-functional-scripts-in-windows/"><u>Overcoming Roadblocks: Activating Non-Functional Scripts in Windows</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/pinnacle-audio-software-for-iphoneipad-the-2023-edition-of-top-ranked-editors/"><u>Pinnacle Audio Software for iPhone/iPad The 2023 Edition of Top-Ranked Editors</u></a></li>
<li><a href="https://windows11.techidaily.com/removing-the-rust-of-access-denied-in-windows/"><u>Removing the Rust of 'Access Denied' In Windows</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-edit-mov-files-for-free-top-10-video-editing-software/"><u>New 2024 Approved Edit MOV Files for Free Top 10 Video Editing Software</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-windows-1111-shop-glitch-x800704cf/"><u>Preventing Windows 11/11 Shop Glitch X800704CF</u></a></li>
<li><a href="https://windows11.techidaily.com/augmenting-mac-operations-with-windows-tech/"><u>Augmenting Mac Operations with Windows Tech</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-seamless-integration-of-youtube-melodies-into-imovie/"><u>[Updated] Seamless Integration of YouTube Melodies Into iMovie</u></a></li>
<li><a href="https://windows11.techidaily.com/personalize-browser-security-incorporating-trusted-websites-in-windows-11/"><u>Personalize Browser Security: Incorporating Trusted Websites in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-tab-navigation-windows-11-enhanced-guide/"><u>The Art of Tab Navigation: Windows 11 Enhanced Guide</u></a></li>
<li><a href="https://extra-skills.techidaily.com/m1-advantages-in-high-quality-video-production-workstations-for-2024/"><u>M1 Advantages in High-Quality Video Production Workstations for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-spotify-connection-errors-in-win11/"><u>Tackling Spotify Connection Errors in Win11</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-a-thorough-introduction-to-gdocs-speech-to-text-capabilities/"><u>2024 Approved  A Thorough Introduction to GDoc's Speech-to-Text Capabilities</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-and-fixing-windows-11s-error-1132-in-zoom-app/"><u>Unraveling and Fixing Windows 11'S Error 1132 in Zoom App</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-complete-guide-twitter-reaction-videos/"><u>2024 Approved  Complete Guide | Twitter Reaction Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-and-streamlined-drive-access-via-new-os-win11/"><u>Secure & Streamlined Drive Access via New OS (Win11)</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-windows-notepad-malfunctions/"><u>Taming Windows Notepad Malfunctions</u></a></li>
<li><a href="https://ai-topics.techidaily.com/updated-guide-on-how-to-enable-the-text-to-speech-function-on-iphone-for-2024/"><u>Updated Guide on How to Enable the Text to Speech Function on iPhone for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-the-ultimate-guide-to-distinctive-tiktok-profiles-for-2024/"><u>[Updated] The Ultimate Guide to Distinctive TikTok Profiles for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-silent-reading-mode-on-ms-word-for-win-users/"><u>Troubleshooting Silent Reading Mode on MS Word for Win Users</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/top-choice-video-capture-apps-iphone-for-2024/"><u>Top Choice Video Capture Apps iPhone for 2024</u></a></li>
<li><a href="https://android-location.techidaily.com/3-effective-methods-to-fake-gps-location-on-android-for-your-honor-play-8t-drfone-by-drfone-virtual/"><u>3 Effective Methods to Fake GPS location on Android For your Honor Play 8T | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/exclusive-spotlight-on-tone-treasures-websites/"><u>Exclusive Spotlight on Tone Treasures Websites</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-your-digital-contents-full-value-winning-at-powerpoint-prints-in-windows/"><u>Unlocking Your Digital Content's Full Value: Winning at PowerPoint Prints in Windows</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-call-logs-on-itel-s23-by-fonelab-android-recover-call-logs/"><u>Complete guide for recovering call logs on Itel S23</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/in-2024-pro-videographers-guide-top-15-high-def-recorders/"><u>In 2024, Pro Videographer's Guide  Top 15 High-Def Recorders</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-techniques-to-elevate-your-facecam-video-quality/"><u>2024 Approved  Techniques to Elevate Your Facecam Video Quality</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-basic-knowledge-about-jazz-music-that-you-may-not-know/"><u>2024 Approved Basic Knowledge About Jazz Music That You May Not Know</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-ultimate-guide-on-oneplus-12r-frp-bypass-by-drfone-android/"><u>In 2024, Ultimate Guide on OnePlus 12R FRP Bypass</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-insider-clandestine-context-creation-techniques/"><u>Windows 11 Insider: Clandestine Context Creation Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/premium-collection-winning-windows-dsswitch-emulators-list/"><u>Premium Collection: Winning Windows DS/Switch Emulators List</u></a></li>
<li><a href="https://windows11.techidaily.com/recovering-failed-zip-operations-on-win-11-system/"><u>Recovering Failed ZIP Operations on Win 11 System</u></a></li>
</ul></div>
