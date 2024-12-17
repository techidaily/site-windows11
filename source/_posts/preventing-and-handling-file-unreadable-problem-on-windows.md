---
title: Preventing and Handling ‘File Unreadable’ Problem on Windows
date: 2024-12-13T20:59:44.002Z
updated: 2024-12-16T21:07:35.092Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Preventing and Handling ‘File Unreadable’ Problem on Windows
excerpt: This Article Describes Preventing and Handling ‘File Unreadable’ Problem on Windows
keywords: Windows File Errors,Unreadable File Fixes,Handling File Issues,Prevent File Problems,Stop File Not Found,Resolve Filespace Error,Windows Data Access Fix
thumbnail: https://thmb.techidaily.com/c92572eed4dd2bbe96a0af1968717f74dd3686117855d1fc2a4babce9d7f3f12.png
---

## Preventing and Handling ‘File Unreadable’ Problem on Windows

 Users often need to copy (or transfer) files to or from external drives connected to Windows PCs. However, some users can’t do so because of an error that says, “Can’t read from the source file or disk.”

 This Windows error message can sometimes pop up when users try to copy certain files from or to external USB drives. As such, here is how you can fix the “Cannot read from the source file or disk” error.

## 1\. Check if the File Names Include Unsupported Characters

 Unsupported file name characters can cause the “Cannot read from the source file” error. Mac computers enable users to save files with characters like ?, <, >, :, \*, /, \\, |, and “. However, Windows 11 and 10 don’t support any of those characters for file names. Thus, users can’t copy files from external drives that include those characters onto a Windows PC.

 So, check if any files you’re trying to copy from an external drive include those characters. If you find any that do, right-click the files and select **Rename**. Then delete all unsupported characters from their file names. Or remove all kinds of special characters.

![The Rename option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/rename-option-1.jpg)

## 2\. Run a Check Disk Scan

 Running a Check Disk scan is a widely confirmed fix for the “Cannot read from the source file” error. That highlights this error is often caused by bad disk sectors on drives. Running a Check Disk scan via the Command Prompt for the drive that includes the files will usually remedy such a cause. Our [how to run a CHKDSK scan](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,to%20get%20stuck%20on%20occasion.) article tells you how to apply this potential fix.

![The CHKDSK command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-chkdsk-command2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xIP8ktrmOdg?si=zRnjbGzM6PDx2jCq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=LvxQhsEJoymsM2iZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Try a Different USB Cable or Port for External Drives

 Another possible cause for the “Cannot read from the source file or disk” error is that there’s an issue with your USB cable or a port on your PC. So, connect your external drive to a different USB port to see if that makes a difference. If you have an alternative USB cable available, try connecting the drive to your PC with it.

## 4\. Compress the Files You’re Trying to Copy Into a ZIP Folder

 Some users have been able to fix the “Cannot read from the source file or disk” error by compressing the files they need to copy into ZIP archives. Doing so will reduce the overall size of one or more files to copy. You can set up a ZIP archive before copy files onto a drive by following the instructions in our article about [creating ZIP files on Windows](https://www.makeuseof.com/easy-ways-create-zip-file-windows-10/).

![The Send to option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-send-to-option.jpg)

## 5\. Check the Permissions for the Affected Files

 You might need to fix the “Cannot read from the source file or disk” because one of the files you’re trying to copy doesn’t have full control permissions set. You can check and fix permissions for affected files as follows:

1. First, bring up Explorer (press**Win + E**) and navigate to the folder that includes the files you need to copy.
2. Right-click a file you need to copy and select **Properties**.
3. Then select **Edit** on the **Security** tab.  
![The Edit button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-edit-button.jpg)
4. Next, select the checkbox labeled **Full control** with the **Allow** column.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-full-control-checkbox.jpg)
5. Press **Apply** to save the file’s permission settings.
6. Click **OK** to exit.

 If you can’t see your account username within the Group box, you’ll need to add it. To do so, click **Add** on the **Security** tab to bring up a Select Users or Group window; then click **Advanced** \> **Find now** to select your user account. Click **OK** to add the selected account.

![The Find now option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-find-now-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_SbYznUy_zY?si=ThBkP934r3mizi48" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Access Files on Mac-Formatted Drives With Third-Party Software

 The “Can’t read from the source file” error can also occur because of file system incompatibility on source drives. For example, Mac-formatted HFS or APFS drives aren’t compatible with Windows PCs.

 You can check the file system of any connected drive by right-clicking it in File Explorer and selecting **Properties**. Then check the File system detail on the General tab. NTFS and FAT32 file systems are fine for Windows, but HFS and APFS aren’t.

![The File system detail](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-file-system-detail.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hXIq2G0nShk?si=5Z4Fwv7ZB6oKWsdd" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you’re trying to copy files from Mac-formatted drives, you can access them with third-party software. Software packages like MacDrive, UFS Explorer, and Paragon HFS+ enable users to access files on Mac-formatted drives on Windows PCs. Our article about [reading Mac-formatted drives on Windows](https://www.makeuseof.com/tag/4-ways-read-mac-formatted-drive-windows/) provides details on how to apply this potential resolution.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yr0yS_Ywrjs?si=QxzYiX1KmUaExmlo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Copy Files Between Drives on Your Windows PC Again

 Applying those solutions will usually resolve the “Cannot read from the source file” error on Windows. Then you can copy all the files you need between your Windows PC and external drives.

 One other resolution for this error recommended by some users is to utilize data recovery software. Such software provides another way to copy or transfer files from one drive to another. Stellar Data Recovery, Recuva, MiniTool Data Recovery, and Disk Drill are among the best data recovery software to utilize for that purpose.

 This Windows error message can sometimes pop up when users try to copy certain files from or to external USB drives. As such, here is how you can fix the “Cannot read from the source file or disk” error.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-posts.techidaily.com/new-optimal-text-movement-collections-for-2024/"><u>[New] Optimal Text Movement Collections for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-2024-approved-crafting-the-ideal-whatsapp-ringtone-ios-and-android-guide/"><u>[Updated] 2024 Approved Crafting the Ideal WhatsApp Ringtone - iOS & Android Guide</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-grip-it-right-tips-for-eliminating-jitter-in-action-cam-movies/"><u>[Updated] Grip It Right Tips for Eliminating Jitter in Action Cam Movies</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/decorum-en-francais-acceptons-cordialement/"><u>Décorum en Français: Acceptons Cordialement</u></a></li>
<li><a href="https://youtube-web.techidaily.com/tial-choices-top-10-best-video-editing-software-free-2023/"><u>Essential Choices Top 10 Best Video Editing Software (Free, 2023)</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-to-retrieve-the-missing-windows-product-patch/"><u>Expert Tips to Retrieve the Missing Windows Product Patch</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-unlock-locked-iphone-12-mini-without-passcode-by-drfone-ios-unlock-ios-unlock/"><u>How to Unlock locked iPhone 12 mini without Passcode</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-use-phone-clone-to-migrate-your-honor-x9a-data-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Use Phone Clone to Migrate Your Honor X9a Data? | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/instagram-engage-obs-live-streaming/"><u>Instagram Engage OBS Live Streaming</u></a></li>
<li><a href="https://windows11.techidaily.com/perfecting-the-art-shrink-or-enlarge-apps-using-shortcut-on-win11/"><u>Perfecting the Art: Shrink or Enlarge Apps Using Shortcut on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-unstartable-windows-vms-with-vmware/"><u>Solutions for Unstartable Windows VMs with VMware</u></a></li>
<li><a href="https://windows11.techidaily.com/speeding-up-typing-typingaids-expertise/"><u>Speeding Up Typing: TypingAid's Expertise</u></a></li>
<li><a href="https://unlock-android.techidaily.com/tips-and-tricks-for-setting-up-your-honor-100-phone-pattern-lock-by-drfone-android/"><u>Tips and Tricks for Setting Up your Honor 100 Phone Pattern Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-resolving-unresponsiveness-in-your-windows-downloads-hub/"><u>Tips for Resolving Unresponsiveness in Your Windows Downloads Hub</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-strategy-enhancing-hard-drive-performance/"><u>Win11 Strategy: Enhancing Hard Drive Performance</u></a></li>
</ul></div>

