---
title: "The Key to Efficient Storage: How to Manage NTFS Compression in Win11"
date: 2024-08-27T16:09:38.568Z
updated: 2024-08-28T16:09:38.568Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes The Key to Efficient Storage: How to Manage NTFS Compression in Win11"
excerpt: "This Article Describes The Key to Efficient Storage: How to Manage NTFS Compression in Win11"
keywords: NTFS Storage Efficiency,Compressing NTFS Files,Win11 Compression Tips,Enhancing Data Storage,Managing NTFS Compression,Win11 File Compression,Optimize Win11 NTFS
thumbnail: https://thmb.techidaily.com/1040d06f8d0aa10730551351f9cb44d3bcea699d80952a8774c562402ba30c3b.jpg
---

## The Key to Efficient Storage: How to Manage NTFS Compression in Win11

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
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Type**Ntfsenablecompression** in the text field.
7. Select and right-click on**Ntfsenablecompression** again, and choose**Modify** .
8. Type**1** in the**Value data** .  
![Editing Ntfsenablecompression in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/editing-ntfsenablecompression.jpg)
9. Click**OK** to save the changes.
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->

 File compression is now enabled on your computer. If you want to disable it, type 0 in Value data and save the changes.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->

 You can disable the file compression by choosing the**Enabled** option in the**Do not allow compression on all NTFS volumes policy** properties window.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-recording.techidaily.com/new-2023-compendium-of-techniques-to-archive-your-online-interactions/"><u>[New] 2023 Compendium of Techniques to Archive Your Online Interactions</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-expert-tips-for-efficient-use-of-movie-maker-in-windows-8/"><u>[New] Expert Tips for Efficient Use of Movie Maker in Windows 8</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-gamers-blueprint-for-money-making/"><u>[New] Gamer’s Blueprint for Money-Making</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-legitimate-strategies-to-amass-over-a-million-youtube-views/"><u>[New] Legitimate Strategies to Amass Over a Million YouTube Views</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-how-to-make-instagram-slow-motion-video-for-2024/"><u>[Updated] How to Make Instagram Slow Motion Video for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-elevating-your-ride-the-sj4000-must-haves-list/"><u>2024 Approved  Elevating Your Ride - The SJ4000 Must-Haves List</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/2024-approved-reviewing-the-live-streaming-shopping-industry-in-china/"><u>2024 Approved Reviewing the Live Streaming Shopping Industry in China</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-i-recover-permanently-deleted-photos-from-itel-p55plus-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>Can I recover permanently deleted photos from Itel P55+</u></a></li>
<li><a href="https://apple-account.techidaily.com/can-i-remove-the-apple-watch-activation-lock-by-iphone-7-without-the-previous-owner-by-drfone-ios/"><u>Can I Remove the Apple Watch Activation Lock By iPhone 7 without the Previous Owner?</u></a></li>
<li><a href="https://os-tips.techidaily.com/comprehensive-guide-eradicating-viruses-in-android-phones-and-tablet-computers/"><u>Comprehensive Guide: Eradicating Viruses in Android Phones and Tablet Computers</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-resolving-11-windows-11-errors/"><u>Essential Guide: Resolving 11 Windows 11 Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-installation-failed-for-discord-on-windows-11-and-11/"><u>Fix 'Installation Failed' For Discord on Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-it-faster-quick-solutions-for-winning-at-powerpoint-prints-in-windows/"><u>Fix It Faster: Quick Solutions for Winning at PowerPoint Prints in Windows</u></a></li>
<li><a href="https://driver-download.techidaily.com/get-the-newest-brother-hl-l2300d-printer-driver-for-your-pc-or-mac/"><u>Get the Newest Brother HL-L2300D Printer Driver for Your PC or Mac</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-contacts-files-from-vivo-s17-pro-by-fonelab-android-recover-contacts/"><u>How To  Restore Missing Contacts Files from Vivo S17 Pro.</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-unexpected-vertical-tilt-in-instagram-vids-why/"><u>In 2024, Unexpected Vertical Tilt in Instagram Vids? Why?</u></a></li>
<li><a href="https://windows11.techidaily.com/lost-features-a-step-by-step-guide-to-find-windows-11s-enhancement/"><u>Lost Features? A Step-by-Step Guide to Find Windows 11'S Enhancement</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-mouse-cursor-visibility-and-clarity-windows-edition/"><u>Maximizing Mouse Cursor Visibility and Clarity - Windows Edition</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/music-infused-content-sharing-strategies-for-facebook-for-2024/"><u>Music-Infused Content Sharing Strategies for Facebook for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-windows-1011-photography-troubles-with-ease/"><u>Navigate Windows 10/11 Photography Troubles with Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-error-signals-in-windows-a-guide-to-using-command-prompt-for-diagnostics/"><u>Navigating Error Signals in Windows: A Guide to Using Command Prompt for Diagnostics</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-pink-screen-crisis-on-your-system/"><u>Navigating the Pink Screen Crisis on Your System</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-failed-task-runner-in-windows/"><u>Overcoming Failed Task Runner in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-hypervisorbsod-top-5-fixes-for-windows-os/"><u>Overcoming HYPERVISOR_BSOD: Top 5 Fixes for Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-microsofts-dism-hurdle-code-0x800f082f/"><u>Overcoming Microsoft's DISM Hurdle: Code 0X800F082F</u></a></li>
<li><a href="https://windows11.techidaily.com/python-server-setup-for-effective-windows-based-data-sharing/"><u>Python Server Setup for Effective Windows-Based Data Sharing</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-solution-fixing-try-connecting-your-device-on-win-11/"><u>Quick Solution: Fixing 'Try Connecting Your Device' On Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstating-default-organization-of-windows-files/"><u>Reinstating Default Organization of Windows Files</u></a></li>
<li><a href="https://windows11.techidaily.com/reversing-the-access-entry-corrupted-windows-malfunction/"><u>Reversing the 'Access Entry Corrupted' Windows Malfunction</u></a></li>
<li><a href="https://buynow-info.techidaily.com/review-of-the-acclaimed-xiaomi-mi-smart-band-best-value-in-a-wristband-tracker/"><u>Review of the Acclaimed Xiaomi Mi Smart Band - Best Value in a Wristband Tracker</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-the-obscured-off-screen-window-techniques-in-win10win11/"><u>Reviving the Obscured: Off-Screen Window Techniques in Win10/Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/shut-down-internal-keyboard-for-pcs-running-windows/"><u>Shut Down Internal Keyboard for PCs Running Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/stopping-self-initiated-file-explorer-windows/"><u>Stopping Self-Initiated File Explorer Windows</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-metaverse-vs-omniverse-showdown-a-comprehensive-overview-for-2024/"><u>The Metaverse Vs. Omniverse Showdown  A Comprehensive Overview for 2024</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-realme-v30-drfone-by-drfone-virtual-android/"><u>The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Realme V30 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-opening-windows-stubborn-folders-on-double-click/"><u>The Ultimate Guide: Opening Windows' Stubborn Folders on Double-Click</u></a></li>
<li><a href="https://windows11.techidaily.com/transition-smoothly-chrome-adaptation-tips-for-windows-11/"><u>Transition Smoothly: Chrome Adaptation Tips for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/turning-offlight-on-notepadwindows/"><u>Turning Offlight On NotepadWindows</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-puzzle-of-windows-subsystem-for-linux-error-4294967295/"><u>Unraveling the Puzzle of Windows Subsystem for Linux Error 4294967295</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/unveiling-youtube-pros-tubebuddys-edge-for-2024/"><u>Unveiling YouTube Pros  TubeBuddy's Edge for 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/upcoming-android-16-release-leaked-details-on-pricing-launch-date-and-specs-stay-ahead-of-the-curve/"><u>Upcoming Android 16 Release: Leaked Details on Pricing, Launch Date & Specs - Stay Ahead of the Curve!</u></a></li>
<li><a href="https://change-location.techidaily.com/why-does-the-pokemon-go-battle-league-not-available-on-samsung-galaxy-a14-5g-drfone-by-drfone-virtual-android/"><u>Why does the pokemon go battle league not available On Samsung Galaxy A14 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/why-your-windows-workstation-needs-specific-encoding-tech/"><u>Why Your Windows Workstation Needs Specific Encoding Tech</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-system-deciphering-report-creation-and-analysis/"><u>Windows System Deciphering: Report Creation & Analysis</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-realme-c55-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset Realme C55 | Dr.fone</u></a></li>
</ul></div>
