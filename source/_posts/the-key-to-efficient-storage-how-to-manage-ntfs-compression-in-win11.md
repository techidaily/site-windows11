---
title: "The Key to Efficient Storage: How to Manage NTFS Compression in Win11"
date: 2024-10-25T16:53:31.843Z
updated: 2024-10-30T16:05:44.411Z
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2027162/19272" target="_top" id="2027162">
  <img src="//a.impactradius-go.com/display-ad/19272-2027162" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2027162/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139113/17108" target="_top" id="2139113">
  <img src="//a.impactradius-go.com/display-ad/17108-2139113" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139113/17108" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://25home.pxf.io/c/5597632/2148646/16836" target="_top" id="2148646">
  <img src="//a.impactradius-go.com/display-ad/16836-2148646" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148646/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can disable the file compression by choosing the**Enabled** option in the**Do not allow compression on all NTFS volumes policy** properties window.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934183/19272" target="_top" id="1934183">
  <img src="//a.impactradius-go.com/display-ad/19272-1934183" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934183/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://some-techniques.techidaily.com/new-evaluating-the-efficacy-of-magix-picture-tool/"><u>[New] Evaluating the Efficacy of MAGIX Picture Tool</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-in-2024-how-to-extract-youtube-srt-effortlessly-in-3-ways/"><u>[New] In 2024, How to Extract YouTube SRT Effortlessly in 3 Ways</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-boost-call-quality-and-creativity-learn-to-apply-filters-in-zoom/"><u>[Updated] 2024 Approved Boost Call Quality & Creativity Learn to Apply Filters in Zoom</u></a></li>
<li><a href="https://windows11.techidaily.com/1-enhance-your-site-with-complimentary-microsoft-live-widgets/"><u>1. Enhance Your Site with Complimentary Microsoft Live Widgets</u></a></li>
<li><a href="https://windows11.techidaily.com/1-mastering-excel-a-step-by-step-guide-on-implementing-the-less-than-or-equal-to-operator/"><u>1. Mastering Excel: A Step-by-Step Guide on Implementing the 'Less than or Equal To' Operator</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-restoring-clear-vision-fixing-iphone-lens-out-of-focus/"><u>2024 Approved Restoring Clear Vision Fixing iPhone Lens Out-of-Focus</u></a></li>
<li><a href="https://extra-hints.techidaily.com/accessing-hidden-reaction-mechanisms-of-youtube-users-for-2024/"><u>Accessing Hidden Reaction Mechanisms of YouTube Users for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/ditch-the-expensive-software-mastering-project-management-with-just-excel/"><u>Ditch the Expensive Software - Mastering Project Management with Just Excel</u></a></li>
<li><a href="https://discover-cloud.techidaily.com/1725286242583-dvddvd/"><u>DVD長持ちに保護！高品質なDVD保管術と適切な容器選びのコツ</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/is-it-possible-to-stream-spotify-simultaneously-with-a-friend/"><u>Is It Possible to Stream Spotify Simultaneously with a Friend?</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-cell-references-seamlessly-linking-data-across-excel-workbooks/"><u>Mastering Cell References: Seamlessly Linking Data Across Excel Workbooks</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-number-formatting-how-to-precisely-add-prefixes-like-zeroes-in-excel-cells/"><u>Mastering Number Formatting: How To Precisely Add Prefixes Like Zeroes in Excel Cells</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-hidden-feature-starting-word-excel-and-powerpoint-with-enhanced-security-settings/"><u>Mastering the Hidden Feature: Starting Word, Excel, and PowerPoint with Enhanced Security Settings</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/quick-and-easy-extracting-hd-videos-from-vimeo-to-mp4-format-for-2024/"><u>Quick & Easy Extracting HD Videos From Vimeo to MP4 Format for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-dividing-data-across-several-excel-sheet-columns/"><u>Step-by-Step Guide: Dividing Data Across Several Excel Sheet Columns</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-insights-in-numbers-a-guide-to-excel-quick-analysis-for-impactful-data-graphs-and-charts/"><u>Unlocking Insights in Numbers: A Guide to Excel Quick Analysis for Impactful Data Graphs and Charts</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-in-2024-the-artisans-approach-to-integrating-fade-out-effects-in-audio-design-updated-for-today/"><u>Updated In 2024, The Artisans Approach to Integrating Fade-Out Effects in Audio Design, Updated for Today</u></a></li>
</ul></div>

