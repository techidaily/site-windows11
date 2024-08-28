---
title: Leveraging NTFS Compression to Optimize Disk Storage
date: 2024-08-27T16:11:13.345Z
updated: 2024-08-28T16:11:13.345Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Leveraging NTFS Compression to Optimize Disk Storage
excerpt: This Article Describes Leveraging NTFS Compression to Optimize Disk Storage
keywords: NTFS Storage Optimization,File System Compression Benefits,Disk Space Reduction Techniques,NTFS Efficiency Improvement,Data Compression Features,Storage Utilization Enhancement,Disk Management via NTFS
thumbnail: https://thmb.techidaily.com/1950983d0af24cf7ccce7d0d9b553dd604417e3bd4a6dbac12c3df842a2a8fe2.jpg
---

## Leveraging NTFS Compression to Optimize Disk Storage

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
2. In the search bar, type**Command Prompt** and choose**Run as administrator** from the right pane. If this method is not working, you can use any other way to[open Command Prompt with admin rights](https://www.makeuseof.com/how-to-always-open-command-prompt-as-administrator-windows/) .
3. Type the following command and press**Enter** to enable file compression.  
`fsutil behavior set disablecompression 0`

![File compression command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/file-compression-command.jpg)

 You'll see the "**A reboot is required for this change to take effect** " message on the console. So, restart your computer to apply the changes.

 If you want to disable File Compression, execute the following command in the elevated Command Prompt window, followed by a system restart.

`fsutil behavior set disablecompression 1`

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
6. Type**Ntfsenablecompression** in the text field.
7. Select and right-click on**Ntfsenablecompression** again, and choose**Modify** .
8. Type**1** in the**Value data** .  
![Editing Ntfsenablecompression in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/editing-ntfsenablecompression.jpg)
9. Click**OK** to save the changes.
<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->

 File compression is now enabled on your computer. If you want to disable it, type 0 in Value data and save the changes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
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
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->

 You can disable the file compression by choosing the**Enabled** option in the**Do not allow compression on all NTFS volumes policy** properties window.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
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
<li><a href="https://youtube-blog.techidaily.com/024-approved-unlocking-the-secrets-of-youtubes-shorts-revenue-sharing/"><u>[New] 2024 Approved  Unlocking the Secrets of YouTube’s Shorts Revenue Sharing</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-from-wardrobe-to-webcam-your-macootd-tiktok-adventure/"><u>[New] From Wardrobe to Webcam  Your MacOOTD TikTok Adventure</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-how-to-download-install-and-use-obs-on-mac-for-2024/"><u>[New] How to Download, Install and Use OBS on Mac for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/n-2024-a-beginners-guide-to-elevating-auditory-experiences-on-youtube/"><u>[New] In 2024, A Beginner's Guide to Elevating Auditory Experiences on YouTube</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-stepping-into-the-unseen-mastering-windows-11-through-less-known-tips/"><u>[New] Stepping Into the Unseen  Mastering Windows 11 Through Less-Known Tips</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-swift-tactics-for-slideshow-storage-for-2024/"><u>[New] Swift Tactics for Slideshow Storage for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-advanced-techniques-for-crafting-dynamic-video-edits/"><u>[Updated] Advanced Techniques for Crafting Dynamic Video Edits</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-digital-diaries-top-picks-for-personal-recorders/"><u>[Updated] In 2024, Digital Diaries  Top Picks for Personal Recorders</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-the-best-mirrorless-cams-top-picks-for-your-next-vlog-project/"><u>[Updated] In 2024, The Best Mirrorless Cams  Top Picks for Your Next Vlog Project</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-the-enigmatic-functionality-of-the-blue-indicator-in-fb-messaging/"><u>[Updated] In 2024, The Enigmatic Functionality of the Blue Indicator in FB Messaging</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-macs-finest-the-leading-free-art-programs/"><u>[Updated] Mac's Finest - The Leading Free Art Programs</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-leveraging-dual-screen-on-apple-devices-through-safari/"><u>2024 Approved  Leveraging Dual-Screen on Apple Devices Through Safari</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-most-memorable-tiktok-videos-and-their-twitter-spreads/"><u>2024 Approved  Most Memorable TikTok Videos & Their Twitter Spreads</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-sketch-it-right-top-8-proficient-drawing-apps-for-iphone-users/"><u>2024 Approved  Sketch It Right  Top 8 Proficient Drawing Apps for iPhone Users</u></a></li>
<li><a href="https://apple-account.techidaily.com/a-step-by-step-guide-to-finding-your-apple-id-on-your-apple-iphone-6-by-drfone-ios/"><u>A Step-by-Step Guide to Finding Your Apple ID On Your Apple iPhone 6</u></a></li>
<li><a href="https://tech-hub.techidaily.com/ace-your-interview-with-a-professional-cover-letter-assistance-from-chatgpt/"><u>Ace Your Interview with a Professional Cover Letter - Assistance From ChatGPT</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/building-brand-buzz-the-power-of-instagram-story-quizzes-for-2024/"><u>Building Brand Buzz  The Power of Instagram Story Quizzes for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/cloud-mastery-the-best-of-unlimited-space-for-2024/"><u>Cloud Mastery  The Best of Unlimited Space for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/discover-6-free-image-editors-that-can-replace-photoshop-effectively/"><u>Discover 6 Free Image Editors That Can Replace Photoshop Effectively</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-cmd-commands-every-user-should-master/"><u>Essential CMD Commands Every User Should Master</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-resolving-11-windows-11-errors/"><u>Essential Guide: Resolving 11 Windows 11 Errors</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/expedited-srt-to-txt-conversion-2023s-efficient-method-for-2024/"><u>Expedited SRT to TXT Conversion  2023'S Efficient Method for 2024</u></a></li>
<li><a href="https://buynow-info.techidaily.com/expert-insights-on-the-garmin-venu-smartwatch-tracking-health-and-fitness-around-the-clock/"><u>Expert Insights on the Garmin Venu Smartwatch: Tracking Health and Fitness Around the Clock</u></a></li>
<li><a href="https://article-helps.techidaily.com/feathered-flamenco-flyers/"><u>Feathered Flamenco Flyers</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-installation-failed-for-discord-on-windows-11-and-11/"><u>Fix 'Installation Failed' For Discord on Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-it-faster-quick-solutions-for-winning-at-powerpoint-prints-in-windows/"><u>Fix It Faster: Quick Solutions for Winning at PowerPoint Prints in Windows</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-can-you-transfer-files-from-oppo-k11-5g-to-iphone-151413-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How Can You Transfer Files From Oppo K11 5G To iPhone 15/14/13? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-reset-a-locked-oneplus-nord-n30-se-phone-by-drfone-android/"><u>How to Reset a Locked OnePlus Nord N30 SE Phone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-change-credit-card-on-your-apple-iphone-14-plus-apple-id-and-apple-pay-by-drfone-ios/"><u>In 2024, How to Change Credit Card on Your Apple iPhone 14 Plus Apple ID and Apple Pay</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-use-pokemon-emerald-master-ball-cheat-on-google-pixel-fold-drfone-by-drfone-virtual-android/"><u>In 2024, How to Use Pokémon Emerald Master Ball Cheat On Google Pixel Fold | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/lost-features-a-step-by-step-guide-to-find-windows-11s-enhancement/"><u>Lost Features? A Step-by-Step Guide to Find Windows 11'S Enhancement</u></a></li>
<li><a href="https://fox-blue.techidaily.com/mastering-the-name-game-for-top-podcast-titles/"><u>Mastering the Name Game for Top Podcast Titles</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-mouse-cursor-visibility-and-clarity-windows-edition/"><u>Maximizing Mouse Cursor Visibility and Clarity - Windows Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-windows-1011-photography-troubles-with-ease/"><u>Navigate Windows 10/11 Photography Troubles with Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-error-signals-in-windows-a-guide-to-using-command-prompt-for-diagnostics/"><u>Navigating Error Signals in Windows: A Guide to Using Command Prompt for Diagnostics</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-pink-screen-crisis-on-your-system/"><u>Navigating the Pink Screen Crisis on Your System</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-windows-11-phone-to-pc-linkage/"><u>Optimizing Windows 11 Phone-to-PC Linkage</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-failed-task-runner-in-windows/"><u>Overcoming Failed Task Runner in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-hypervisorbsod-top-5-fixes-for-windows-os/"><u>Overcoming HYPERVISOR_BSOD: Top 5 Fixes for Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-microsofts-dism-hurdle-code-0x800f082f/"><u>Overcoming Microsoft's DISM Hurdle: Code 0X800F082F</u></a></li>
<li><a href="https://windows11.techidaily.com/python-server-setup-for-effective-windows-based-data-sharing/"><u>Python Server Setup for Effective Windows-Based Data Sharing</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-solution-fixing-try-connecting-your-device-on-win-11/"><u>Quick Solution: Fixing 'Try Connecting Your Device' On Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstating-default-organization-of-windows-files/"><u>Reinstating Default Organization of Windows Files</u></a></li>
<li><a href="https://windows11.techidaily.com/reversing-the-access-entry-corrupted-windows-malfunction/"><u>Reversing the 'Access Entry Corrupted' Windows Malfunction</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-the-obscured-off-screen-window-techniques-in-win10win11/"><u>Reviving the Obscured: Off-Screen Window Techniques in Win10/Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/shut-down-internal-keyboard-for-pcs-running-windows/"><u>Shut Down Internal Keyboard for PCs Running Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/steady-the-shaky-xbox-experience-in-windows/"><u>Steady the Shaky Xbox Experience in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/stopping-self-initiated-file-explorer-windows/"><u>Stopping Self-Initiated File Explorer Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-computer-experience-enabledisable-windows-key/"><u>Streamline Your Computer Experience: Enable/Disable Windows Key</u></a></li>
<li><a href="https://ai-voice.techidaily.com/the-most-straightforward-guide-to-learning-how-to-clone-your-voice-for-2024/"><u>The Most Straightforward Guide to Learning How to Clone Your Voice for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-necessity-of-vcplusplus-redistribution-packages/"><u>The Necessity of VC++ Redistribution Packages</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/the-ultimate-breakdown-of-netgear-ac1200-extender-ex6200-for-optimized-wifi-propagation-expert-reviews-and-comparisons/"><u>The Ultimate Breakdown of Netgear AC1200 Extender (EX6200) for Optimized WiFi Propagation: Expert Reviews and Comparisons</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-opening-windows-stubborn-folders-on-double-click/"><u>The Ultimate Guide: Opening Windows' Stubborn Folders on Double-Click</u></a></li>
<li><a href="https://windows11.techidaily.com/transition-smoothly-chrome-adaptation-tips-for-windows-11/"><u>Transition Smoothly: Chrome Adaptation Tips for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/turning-offlight-on-notepadwindows/"><u>Turning Offlight On NotepadWindows</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-the-potential-choose-best-6-android-apps-for-windows-11/"><u>Unleashing the Potential: Choose Best 6 Android Apps for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-full-potential-the-ultimate-wsl-2-and-docker-guide/"><u>Unlocking Full Potential: The Ultimate WSL 2 & Docker Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-puzzle-of-windows-subsystem-for-linux-error-4294967295/"><u>Unraveling the Puzzle of Windows Subsystem for Linux Error 4294967295</u></a></li>
<li><a href="https://driver-install.techidaily.com/update-and-installation-guide-for-netgear-a6200-dongle/"><u>Update & Installation Guide for Netgear A6200 Dongle</u></a></li>
<li><a href="https://windows11.techidaily.com/what-is-windows-modern-standby-and-why-does-it-suck/"><u>What Is Windows Modern Standby (and Why Does It Suck?)</u></a></li>
<li><a href="https://windows11.techidaily.com/why-your-windows-workstation-needs-specific-encoding-tech/"><u>Why Your Windows Workstation Needs Specific Encoding Tech</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-system-deciphering-report-creation-and-analysis/"><u>Windows System Deciphering: Report Creation & Analysis</u></a></li>
</ul></div>
