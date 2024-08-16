---
title: Invisible Disk Hiding Tricks in Win11/W10
date: 2024-08-15T15:58:08.243Z
updated: 2024-08-16T15:58:08.243Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Invisible Disk Hiding Tricks in Win11/W10
excerpt: This Article Describes Invisible Disk Hiding Tricks in Win11/W10
keywords: Windows Hide Secrets,Win11 Stealth Tech,W10 Invisibility Trick,Discrete OS Feature,Bypass Vista Disc Visibility,Hidden Storage in Win11,Concealed Files WinOS
thumbnail: https://thmb.techidaily.com/a6ef7d238dd7bb214a3984e4799089ad86b5e4b6f433cd32ec9f580258b7206c.jpg
---

## Invisible Disk Hiding Tricks in Win11/W10

 File Explorer in Windows displays any internal or external drives that are connected to your system by default. However, if you don't want a certain drive to appear in File Explorer, you can always hide it.

 By hiding a drive on Windows, you can prevent others from accessing sensitive files within that drive and keep them safe. If you're interested in doing that, this guide will walk you through four different methods to hide drives on Windows.

## 1\. Hide a Drive Using the Disk Management App

 The Disk Management tool on Windows makes it easy to perform various storage-related tasks such as formatting hard disk partitions, assigning drive letters, managing disk space, and more. You can also use it to hide a drive partition on Windows. Here's how:

1. Press**Win + R** or use one of the [many ways to open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**diskmgmt.msc** in the text field and press**Enter** .
3. In the Disk Management window that opens, right-click on the drive you wish to hide and select**Change Drive Letter and Paths** .
4. Now, click the**Remove** button from the pop-up window.
5. Choose**Yes** when the warning message appears.  
![Hide a Drive Using Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/hide-a-drive-using-disk-management.jpg)

 Once you complete the above steps, your drive will no longer appear in File Explorer.

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Hide a Drive in Windows With Diskpart Command

 If you're a power user who prefers to make changes via the command-line interface, you can use the diskpart command to hide a drive on Windows. Fortunately, this isn't as intimidating as it might sound.

To hide a drive in Windows with Command Prompt, follow these steps:

1. Press**Win + X** and select**Terminal (Admin)** from the menu that appears.
2. Select**Yes** when the User Account Control (UAC) prompt shows up.
3. In the console, type**diskpart** and press**Enter** .
4. Input the following command in the console and press**Enter** to view a list of drives connected to your system:  
`list volume`  
![List of Drives in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/list-of-drives-in-command-prompt.jpg)
5. Note down the letter of the drive you want to hide from the**Ltr** column.
6. Type the following command to select your drive. Make sure you replace**X** in the command with the drive letter noted in the last step.  
`select volume X`
7. Lastly, run the following command to remove the drive letter and hide the volume.  
`remove letter X`  
![Hide a Drive Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/hide-a-drive-using-command-prompt.jpg)

 You should see a message that reads **Diskpart successfully removed the drive letter or mount point** . Following that, the drive will no longer appear on your PC.

 If you like using Command Prompt, why not check our guide on [how to master the Command Prompt in Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) ?

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->
## 3\. Hide a Drive Using the Group Policy Editor

 The Local Group Policy Editor is a tool that allows you to configure a wide range of settings on your computer. You can use it to hide a drive from your Windows computer.

 The Local Group Policy Editor is only available in Professional, Enterprise, and Education editions of Windows. If you're using the Windows Home edition, check our guide on [how to access the Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

Here's what you need to do:

1. Press**Win + R** to open the Run dialog box.
2. Type**gpedit.msc** in the box and click**OK** .
3. Select**Yes** when the User Account Control (UAC) prompt shows up.
4. In the Local Group Policy Editor window, use the left pane to navigate to **User Configuration > Administrative Templates > Windows Components > File Explorer** .
5. Double-click the**Hide these specified drives in My Computer** policy on your right.  
![Hide a Drive With Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/hide-a-drive-with-group-policy-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->
6. Select the**Enabled** option.
7. Under**Options** , select the drive you want to hide.
8. Click**Apply** followed by**OK** .

 Once you complete the above steps, Windows will hide the specified drive from File Explorer. If you want to unhide the drive later, use the same steps and set the**Hide these specified drives in My Computer policy** to**Not configured** .

## 4\. Hide a Drive in Windows via the Registry Editor

 Another brilliant tool that allows you to configure system settings in Windows easily is the Registry Editor. You can use Registry Editor to hide a drive if none of the above methods work. However, you must be careful [not to accidentally mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/) in the process.

 To be safe, you should back up all the registry files before proceeding. If you need help with that, check our guide on [how to back up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and follow the steps outlined there.

 Once you're done with that, use the following steps to hide a drive using Windows Registry:

1. Press**Win + S** to open the search menu.
2. Type**registry editor** in the box and select the first result that appears.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > Software > Microsoft > Windows > CurrentVersion > Policies > Explorer** .
5. Right-click on the**Explorer** key and go to**New** and select**DWORD (32-bit) Value** from the sub-menu.
6. Rename the DWORD to**NoDrives** .
7. Double-click the**NoDrives** DWORD.
8. In the**Edit DWORD (32-bit) Value** dialog box, select**Decimal** as the Base.  
![Hide a Drive via Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/hide-a-drive-via-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
9. Enter a number corresponding to the drive you want to hide in the**Value data** field and click**OK** . Refer to the table below to determine which number to use.  
![Drive Letter Refrence for Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/drive-letter-refrence-for-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->

 For instance, if you were to hide the**E:** drive from your computer, you'd enter**16** in the Value data field.

 You can also use this method to hide multiple drives at the same time. To do so, add the decimal numbers for both drives and enter the total in the Value data field. For example, if you're looking to hide drive**G:** and**H:** from your computer, you should enter**192** (64 + 128) in the Value data field.

 You'll have to restart your PC to apply the changes. Following that, the drive will not appear in File Explorer. You can undo the above changes at any point by deleting the**NoDrives** DWORD.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->
## Hiding Drives in Windows Is Easy

 Regardless of the method you use, hiding a drive on Windows is fairly simple and shouldn't take more than a few minutes.

 Alternatively, if you don't want to hide an entire drive, Windows also lets you hide specific files and folders in a few easy steps.


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
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-orchestrate-instagram-reel-magic-with-music-and-voiceovers/"><u>[New] In 2024, Orchestrate Instagram Reel Magic with Music & Voiceovers</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-crafting-compelling-tiktok-tweets-for-engagement/"><u>[Updated] 2024 Approved  Crafting Compelling TikTok Tweets for Engagement</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-key-screenshot-utilities-1-8/"><u>[Updated] 2024 Approved  Key Screenshot Utilities #1-8</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-ultimate-guide-to-efficient-mobile-video-management/"><u>[Updated] The Ultimate Guide to Efficient Mobile Video Management</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-top-5-cozy-winter-scenes-for-youtube-backdrops/"><u>[Updated] Top 5 Cozy Winter Scenes for YouTube Backdrops</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-comprehensive-degree-of-view-analysis/"><u>2024 Approved  Comprehensive Degree of View Analysis</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-from-novice-to-notable-launching-a-trending-solo-show/"><u>2024 Approved  From Novice to Notable  Launching a Trending Solo Show</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-innovative-cameras-for-high-stakes-athletics/"><u>2024 Approved  Innovative Cameras for High-Stakes Athletics</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/7-essential-secrets-for-delectable-cooking-clips/"><u>7 Essential Secrets for Delectable Cooking Clips</u></a></li>
<li><a href="https://howto.techidaily.com/8-quick-fixes-unfortunately-snapchat-has-stopped-on-realme-narzo-n55-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Quick Fixes Unfortunately, Snapchat has Stopped on Realme Narzo N55 | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-i-recover-permanently-deleted-photos-from-itel-a60s-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>Can I recover permanently deleted photos from Itel A60s</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-color-discrepancies-on-microsoft-windows/"><u>Fixing Color Discrepancies on Microsoft Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-through-setting-up-and-adjusting-net-settings/"><u>Guide Through Setting Up and Adjusting Net Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-fix-invalid-label-alert-in-win11/"><u>Guide to Fix Invalid Label Alert in Win11</u></a></li>
<li><a href="https://win-amazing.techidaily.com/how-to-fix-realtek-hd-graphics-card-drivers-a-comprehensive-guide/"><u>How to Fix Realtek HD Graphics Card Drivers: A Comprehensive Guide</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-apple-iphone-13-pro-official-method-to-unlock-your-apple-iphone-13-pro-by-drfone-ios/"><u>How To Unlock Apple iPhone 13 Pro Official Method to Unlock Your Apple iPhone 13 Pro</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-dive-deep-into-the-world-of-creator-studio/"><u>In 2024, Dive Deep Into the World of Creator Studio</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-ipogo-will-be-the-new-ispoofer-on-realme-11-5g-drfone-by-drfone-virtual-android/"><u>In 2024, iPogo will be the new iSpoofer On Realme 11 5G? | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-mastering-multitask-media-consumption-harnessing-pip-feature-in-netflix/"><u>In 2024, Mastering Multitask Media Consumption  Harnessing PIP Feature in Netflix</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/in-2024-slow-down-or-freeze-time-expert-fcpx-editing-techniques/"><u>In 2024, Slow Down or Freeze Time Expert FCPX Editing Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/manipulating-image-summary-dimensions-w11/"><u>Manipulating Image Summary Dimensions W11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-off-game-lists-in-win11/"><u>Mastering Off Game Lists in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/minimizing-resource-waste-during-device-integration-on-windows/"><u>Minimizing Resource Waste During Device Integration on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-win11-with-ease-mastering-package-control-using-wingetui/"><u>Navigate Win11 with Ease: Mastering Package Control Using WingetUI</u></a></li>
<li><a href="https://windows11.techidaily.com/perfect-speech-capture-on-a-windows-device/"><u>Perfect Speech Capture on a Windows Device</u></a></li>
<li><a href="https://windows11.techidaily.com/precision-tools-for-program-harmony-on-pc/"><u>Precision Tools for Program Harmony on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-guide-for-degraded-windows-based-excel-performance/"><u>Quick-Fix Guide for Degraded Windows-Based Excel Performance</u></a></li>
<li><a href="https://driver-error.techidaily.com/seagate-disk-vanished-on-windows-10-heres-how-to-fetch-it-back/"><u>Seagate Disk Vanished on Windows 10? Here's How to Fetch It Back</u></a></li>
<li><a href="https://windows11.techidaily.com/selecting-a-window-for-your-needs-the-win11-homepro-showdown/"><u>Selecting a Window for Your Needs: The Win11 Home/Pro Showdown</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-solve-chrome-not-saving-or-uploading-issues-on-windows/"><u>Steps to Solve Chrome Not Saving or Uploading Issues on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-accurate-interpretation-of-task-manager-writings/"><u>Strategies for Accurate Interpretation of Task Manager' Writings</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-rescuing-non-transferring-usbs-in-windows/"><u>Strategies for Rescuing Non-Transferring USBs in Windows</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/superior-third-ranked-ipad-recording-apps-for-2024/"><u>Superior Third-Ranked iPad Recording Apps for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-shifting-windows-taskbar-a-historical-view/"><u>The Shifting Windows Taskbar: A Historical View</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-unseen-hdd-in-windows/"><u>Troubleshooting Unseen HDD in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/turn-your-windows-11-pc-into-a-portable-wireless-router/"><u>Turn Your Windows 11 PC Into a Portable Wireless Router</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-typing-potential-essentials-for-crafting-shortcuts-in-the-latest-windows-version/"><u>Unlock Typing Potential: Essentials for Crafting Shortcuts in the Latest Windows Version</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-efficiency-9-gains-from-the-newest-outlook-update/"><u>Unlocking Efficiency: 9 Gains From the Newest Outlook Update</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-power-of-outlook-preview-on-windows-11/"><u>Unlocking the Power of Outlook Preview on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-yourphoneexe-usefulness-on-modern-windows/"><u>Unlocking YourPhone.exe: Usefulness on Modern Windows?</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-invisible-windows-methods-to-bring-them-back-in-win10win11/"><u>Unveiling Invisible Windows: Methods to Bring Them Back in Win10/Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-steps-to-fix-rockalldlldll-not-found-error/"><u>Unveiling Steps to Fix 'Rockalldll.dll Not Found Error'</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-top-7-pencil-powerhouses-for-windows-creators/"><u>Unveiling the Top 7 Pencil Powerhouses for Windows Creators</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-upgraded-the-future-of-using-sudo/"><u>Windows Upgraded: The Future of Using Sudo</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-with-virtualbox-deps-before-the-big-setup/"><u>Winning with VirtualBox: Deps Before the Big Setup</u></a></li>
</ul></div>
