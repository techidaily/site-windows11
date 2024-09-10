---
title: The Ultimate Guide to NTFS File Size Reduction
date: 2024-09-09T12:05:17.099Z
updated: 2024-09-10T12:05:17.099Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Ultimate Guide to NTFS File Size Reduction
excerpt: This Article Describes The Ultimate Guide to NTFS File Size Reduction
keywords: NTFS File Compression,Limit NTFS Filesize,Optimizing NTFS Size,Minimize NTFS Disk Space,NTFS Reduce Storage,Control NTFS Filesize,Enhance NTFS Efficiency
thumbnail: https://thmb.techidaily.com/cb769af3708fc15b594c9ede31a115d7b902d54d4fbcec56dcebaeb9d186f784.jpg
---

## The Ultimate Guide to NTFS File Size Reduction

 Is your Windows computer running out of storage? There are plenty of ways to remove redundant data and free up some extra space. Among all, the most preferred method is using NTFS file compression.

 NTFS file compression is a Windows feature that compresses files and folders by removing reductant data from them. The best part about this feature is that it does its job without damaging the file and losing the data.

 Nevertheless, let's check out some ways to enable NTFS file compression in Windows 11.

## 1\. Enable NTFS File Compression Through the File Explorer

 The quickest way to enable NTFS[file compression](https://www.makeuseof.com/windows-11-file-compression-guide/) is through File Explorer. Below are the steps to compress a folder:

1. Open the File Explorer and head toward the folder you want to compress.
2. Right-click on the target folder and choose**Properties** from the context menu.
3. In the**General** tab, select the**Advanced** option.
4. Under the**Compress or Encrypt attributes** section, check the**Compress contents to save disk space** box and click**OK** .  
![Compress content to save disk option in Folder properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/compress-content-to-save-disk-option.jpg)
5. Click**Apply** \>**OK** to save the changes.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118323/7443" target="_top" id="2118323">
  <img src="//a.impactradius-go.com/display-ad/7443-2118323" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118323/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://bluettiit.sjv.io/c/5597632/2114265/17093" target="_top" id="2114265">
  <img src="//a.impactradius-go.com/display-ad/17093-2114265" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettiit.sjv.io/i/5597632/2114265/17093" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Enable NTFS File Compression Using the Command Prompt

 If you are a power user, you can use the Command Prompt to enable file compression on Windows 11\. Here are the steps to do it:

1. Press the**Win + S** hotkeys to open the**Windows Search.**
2. In the search bar, type**Command Prompt** and choose**Run as administrator** from the right pane. If this method is not working, you can use any other way to[open Command Prompt with admin rights](https://www.makeuseof.com/how-to-always-open-command-prompt-as-administrator-windows/) .
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
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135369/19272" target="_top" id="2135369">
  <img src="//a.impactradius-go.com/display-ad/19272-2135369" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135369/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Type**Ntfsenablecompression** in the text field.
7. Select and right-click on**Ntfsenablecompression** again, and choose**Modify** .
8. Type**1** in the**Value data** .  
![Editing Ntfsenablecompression in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/editing-ntfsenablecompression.jpg)
9. Click**OK** to save the changes.

 File compression is now enabled on your computer. If you want to disable it, type 0 in Value data and save the changes.

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2005196/22899" target="_top" id="2005196">
  <img src="//a.impactradius-go.com/display-ad/22899-2005196" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2005196/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Enable NTFS File Compression Using the Local Group Policy Editor

 The Local Group Policy Editor is the go-to place to configure important Windows policies. To use it to enable file compression, follow the below instructions:

1. In the Run dialog box, type**gpedit.msc** and click**OK.**
2. Head towards the following location in the Local Group Policy Editor:  
`Computer Configuration\Administrative Templates\System\Filesystem\NTFS`
3. Double-click on the**Do not allow compression on all NTFS volumes policy** to open its properties window.
4. Choose the**Disabled** option.  
![Disabling policy in LGPE](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/disabling-policy.jpg)
5. Click**Apply** \>**OK** to enable file compression.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123737/7443" target="_top" id="2123737">
  <img src="//a.impactradius-go.com/display-ad/7443-2123737" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123737/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can disable the file compression by choosing the**Enabled** option in the**Do not allow compression on all NTFS volumes policy** properties window.

<!-- affiliate ads begin -->
<span id="1936838">
					<video width="374" height="48" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1936838.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18409-1936838">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1936838.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:234px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fcoinrule.sjv.io%2Fc%2F5597632%2F1936838%2F18409'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1936838/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-pixelpilot-expert-tips-for-screen-snagging/"><u>[New] 2024 Approved PixelPilot Expert Tips for Screen Snagging</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-accessing-facebook-videos-via-apple-tv-essential-tips/"><u>[New] In 2024, Accessing Facebook Videos via Apple TV Essential Tips</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-unveiling-fake-followers-on-instagram-effortlessly/"><u>[New] In 2024, Unveiling Fake Followers on Instagram, Effortlessly</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-in-2024-youtubes-picture-posting-made-simple/"><u>[New] In 2024, YouTube's Picture Posting Made Simple</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-mobile-audio-enhancers-for-swift-soundplay-for-2024/"><u>[New] Mobile Audio Enhancers for Swift Soundplay for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-quality-assured-the-best-10-online-converters-for-jpg-to-gif-for-2024/"><u>[New] Quality Assured The Best 10 Online Converters for JPG to GIF for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-unveiling-the-secrets-of-movie-maker-on-windows-8/"><u>[New] Unveiling the Secrets of Movie Maker on Windows 8</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-2024-approved-zero-in-on-transparent-design-with-figmas-bg-removal/"><u>[Updated] 2024 Approved Zero In on Transparent Design with Figma's BG Removal</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-comprehensive-vita-edit-suite-review-and-tutorial-2024/"><u>[Updated] Comprehensive Vita Edit Suite Review & Tutorial 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-harness-the-power-of-keywords-top-selection-software-unveiled-for-2024/"><u>[Updated] Harness the Power of Keywords Top Selection Software Unveiled for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-perfecting-sound-integrating-music-into-vimeo-video-projects/"><u>[Updated] In 2024, Perfecting Sound Integrating Music Into Vimeo Video Projects</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-ranked-elite-12-best-camcorders-sporting-gps-mapping-technology-for-2024/"><u>[Updated] Ranked Elite 12 Best Camcorders Sporting GPS Mapping Technology for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-aerial-device-typologies/"><u>2024 Approved Aerial Device Typologies</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-decoding-toolwizs-capabilities-in-mobile-photo-editing/"><u>2024 Approved Decoding Toolwiz's Capabilities in Mobile Photo Editing</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-expert-techniques-for-crafting-stunning-collage-photos-on-iphone/"><u>2024 Approved Expert Techniques for Crafting Stunning Collage Photos on iPhone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-navigating-video-sources-and-uploading-on-instagram/"><u>2024 Approved Navigating Video Sources and Uploading on Instagram</u></a></li>
<li><a href="https://win-blog.techidaily.com/banish-errors-the-ultimate-fixes-for-you-have-lost-connection-to-destiny-2-servers/"><u>Banish Errors: The Ultimate Fixes for 'You Have Lost Connection to Destiny 2 Servers'</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/celestial-wonders-at-your-fingertips-hd-sky-website-guide/"><u>Celestial Wonders at Your Fingertips - HD Sky Website Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-fixes-for-windows-remote-desktop-problems/"><u>Essential Fixes for Windows Remote Desktop Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-pathways-for-opening-hardware-spaces-on-w10w11/"><u>Essential Pathways for Opening Hardware Spaces on W10/W11</u></a></li>
<li><a href="https://windows11.techidaily.com/examining-windows-memory-management-insights-into-pagefilesys/"><u>Examining Windows' Memory Management: Insights Into Pagefile.sys</u></a></li>
<li><a href="https://windows11.techidaily.com/exposing-limits-the-cpu-performance-spectrum/"><u>Exposing Limits: The CPU Performance Spectrum</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-d3dx939-error-steps-to-recover-dll/"><u>Fixing D3DX9_39 Error: Steps to Recover DLL</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-to-selectively-turn-off-windows-11-services/"><u>Guidelines to Selectively Turn Off Windows 11 Services</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-frp-from-vivo-y100i-by-drfone-android/"><u>How to Bypass FRP from Vivo Y100i?</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-alt-codes-not-working-on-windows/"><u>How to Fix ALT Codes Not Working on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-internal-error-has-occurred-remote-desktop-connection-error-in-windows-11-and-11/"><u>How to Fix the “Internal Error Has Occurred” Remote Desktop Connection Error in Windows 11 & 11</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-apple-iphone-15-pro-max-data-from-icloud-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Apple iPhone 15 Pro Max Data From iCloud? | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-best-15-video-cameras-to-elevate-your-vlogging-game/"><u>In 2024, Best 15 Video Cameras to Elevate Your Vlogging Game</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-tiktok-to-see-more-content-on-your-realme-c55-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Location on TikTok to See More Content On your Realme C55 | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-your-xiaomi-redmi-13c-location-on-twitter-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change your Xiaomi Redmi 13C Location on Twitter | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-how-to-find-the-optimal-balance-equipment-for-drone-photography/"><u>In 2024, How To Find the Optimal Balance Equipment for Drone Photography</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-how-to-go-live-on-facebook/"><u>In 2024, How to Go Live on Facebook?</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-mastering-pc-games-screenshots-top-6-methods/"><u>In 2024, Mastering PC Games Screenshots Top 6 Methods</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-meme-mastery-iphone-edition/"><u>In 2024, Meme Mastery IPhone Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/is-error-code-2e-blocking-windows-updates/"><u>Is Error Code 2E Blocking Windows Updates?</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-code-with-microsoft-copilot-on-windows/"><u>Mastering Code with Microsoft Copilot on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-microsoft-store-crash-fixes-for-error-0x0-on-pcs/"><u>Mastering Microsoft Store Crash Fixes for Error 0X0 on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-prevent-data-loss-in-unresponsive-usb-cases-windows/"><u>Methods to Prevent Data Loss in Unresponsive USB Cases (Windows)</u></a></li>
<li><a href="https://data-wizards.techidaily.com/methods-to-prevent-video-degradation-after-output/"><u>Methods to Prevent Video Degradation After Output</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-rectify-frozen-and-unresponsive-windows-discord-elements/"><u>Methods to Rectify Frozen and Unresponsive Windows Discord Elements</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-to-win-11s-insider-program-enrollment/"><u>Navigating to Win 11'S Insider Program Enrollment</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-mcuicntexe-missing-problems-on-pcs/"><u>Overcoming McUICnt.exe Missing Problems on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-pin-lock-problems-in-11-edition/"><u>Overcoming Windows PIN Lock Problems in 11 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/perfecting-image-clarity-windows-11s-background-blur-tricks/"><u>Perfecting Image Clarity: Windows 11'S Background Blur Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/personalize-your-pcs-clock-view-ideal-screensaver-creation-apps-in-windows-platform/"><u>Personalize Your PC's Clock View: Ideal Screensaver Creation Apps in Windows Platform</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-systemsettings-errors-in-windows-11/"><u>Preventing SystemSettings Errors in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/quicken-pace-elevating-gameplay-with-better-frames/"><u>Quicken Pace: Elevating Gameplay with Better Frames</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-fingerprint-scanning-not-found-in-windows/"><u>Remedying Fingerprint Scanning Not Found in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-phantom-device-error-in-windows-11/"><u>Remedying Phantom Device Error in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resetting-error-with-windows-shadow-copy-service/"><u>Resetting Error with Windows' Shadow Copy Service</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-windows-services-command-prompt-tool-a-list-of-7-remedies/"><u>Reviving Windows Services Command Prompt Tool: A List of 7 Remedies</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-up-a-safe-workspace-windows-sandbox-11/"><u>Setting Up a Safe Workspace: Windows Sandbox 11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/starting-line-the-basics-of-picture-resolution/"><u>Starting Line The Basics of Picture Resolution</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-resolving-non-functional-windows-alt-keys/"><u>Steps for Resolving Non-Functional Windows Alt Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-mouse-accel-tips-for-win-11-users/"><u>Stop Mouse Accel: Tips for Win 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-excessive-gpu-load-in-games-on-pc/"><u>Tackling Excessive GPU Load in Games on PC</u></a></li>
<li><a href="https://network-issues.techidaily.com/taming-turbulent-windows-11-views/"><u>Taming Turbulent Windows 11 Views</u></a></li>
<li><a href="https://windows11.techidaily.com/the-network-navigator-guiding-you-through-obs-connectivity-troubles-7-ways/"><u>The Network Navigator: Guiding You Through OBS Connectivity Troubles (7 Ways)</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-next-leap-forward-for-bing-microsofts-implementation-of-cutting-edge-ai-technology/"><u>The Next Leap Forward for Bing: Microsoft's Implementation of Cutting-Edge AI Technology</u></a></li>
<li><a href="https://windows11.techidaily.com/touching-your-world-better-the-ultimate-guide-to-pc-touch-adjustment/"><u>Touching Your World Better: The Ultimate Guide to PC Touch Adjustment</u></a></li>
<li><a href="https://android-unlock.techidaily.com/universal-unlock-pattern-for-oppo-find-n3-by-drfone-android/"><u>Universal Unlock Pattern for Oppo Find N3</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-your-windows-start-windows-media-player-now/"><u>Unleash Your Windows: Start Windows Media Player Now</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-torrent-speed-resetting-stalled-status-on-windows/"><u>Unlocking Torrent Speed: Resetting Stalled Status on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-non-essential-windows-applications-for-elimination/"><u>Unveiling Non-Essential Windows Applications for Elimination</u></a></li>
<li><a href="https://windows11.techidaily.com/upgrade-pcs-for-efficient-scalable-transcoding-using-tdarr/"><u>Upgrade PCs for Efficient, Scalable Transcoding Using Tdarr</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-woes-alternatives-without-upgrading/"><u>Windows 11 Woes: Alternatives Without Upgrading</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-family-safety-rescue-quick-corrections-listed-here/"><u>Windows Family Safety Rescue: Quick Corrections Listed Here</u></a></li>
</ul></div>
