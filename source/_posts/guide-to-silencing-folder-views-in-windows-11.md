---
title: Guide to Silencing Folder Views in Windows 11
date: 2024-12-29T03:14:58.055Z
updated: 2025-01-04T03:35:04.386Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Silencing Folder Views in Windows 11
excerpt: This Article Describes Guide to Silencing Folder Views in Windows 11
keywords: Silence Windows Folders,Disable Folder Shows,Stop Explorer Previews,Hide Folder Listings,No Prefetch Window Views,Reduce Vista Icon Display,Suppress Windows 11 Shows
thumbnail: https://thmb.techidaily.com/7463aefc3bf7373e7e8450adfdbb24d271ecbb972a6b7c25ccc1795bc56f580e.jpg
---

## Guide to Silencing Folder Views in Windows 11

 Microsoft was hoping to launch the tabs feature in the File Explorer app for Windows 10\. But it scrapped the idea later on. However, with the Windows 11 22H2 update, users can now try out the tabs feature in File Explorer. The participants of the Windows Insider Program got early access to the feature and Microsoft could soon apply the tabs idea to Windows Notepad as well.

 But what if you want to turn the File Explorer Tabs feature off? An immediate idea would be to uninstall the update, but that is a temporary workaround. You can use ViVeTool to enable or disable the tabs feature or any other new feature of Windows 11.

## What Is ViVeTool?

 ViVeTool is an open-source command line tool that can enable or disable Windows operating system features. Microsoft continuously works on many experimental features and does a lot of testing before rolling out a stable version of a feature. But if you are impatient, you can use ViVeTool to enable an otherwise hidden feature. It is free and the developers recently launched a GUI version of the tool as well.

## How to Disable File Explorer Tabs In Windows 11

 You can disable the File Explorer Tabs by either using the ViVeTool or the ViVeTool GUI version. The latter is much simpler to use because you can search for a feature and activate or deactivate it in one click. But before doing that, download and install both of these tools on your system. Also,[create a system restore point](https://www.makeuseof.com/windows-11-create-restore-point/) for added precaution, in case the tool wrecks something on your Windows 11 computer.

**Download:** [ViVeTool](https://github.com/thebookisclosed/ViVe/releases)

**Download:** [ViVeTool GUI](https://github.com/PeterStrick/ViVeTool-GUI/releases)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RvR5PNhspKE?si=uJcMYK9v-_Xq7fAg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 1\. Disable File Explorer Tabs Using the ViVeTool

 Since it is a command line tool, you can access it from a terminal window. Here’s how to do it:

1. Press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**CMD** in the text input area and press**Ctrl + Shift + Enter** key to launch the command prompt with administrator privileges.
3. Type**cd Drive Name:\\path** . Here, you need to enter the exact location where you extracted the tool after downloading it. For example, we extracted it to a folder name Vive in C drive. So, our command is**cd C:\\Vive** .
4. Now, you will be in the directory where ViVeTool exists. Type**vivetool** and press the**Enter** key. You will see a bunch of parameters you can use with the tool.  
![Disable File Explorer Tabs Using the ViVeTool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool.jpg)
5. Type the following two commands, one by one in the CMD and press the**Enter** key.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S3Th6oa_isA?si=TTQ013BB9beUM4x6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

vivetool /disable /id:37634385  
vivetool /disable /id:36354489
6. You will see the “**Successfully set feature configuration(s)** ” if the command executes successfully.
7. Now,**restart** your system for the changes to take effect. The File Explorer Tabs feature will no longer be active on your system.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hZsnjxeSh1U?si=hZIfzQPDNX5KtOCg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2\. Disable File Explorer Tabs Using the ViVeTool GUI version

 The GUI version of ViVeTool works similarly. You can manually enter the feature ID or use the search function to find a feature in the list. Repeat the following steps to disable File Explorer Tabs using the ViVeTool GUI.

1. Launch the ViVeTool GUI with admin privileges.
2. Click on the drop-down list and select the latest Windows build number. Wait for the tool to list all the feature IDs available for the Windows build.
3. Type**37634385** in the search bar. Select the highlighted feature and click on the**Perform Action** button.  
![Disable File Explorer Tabs Using the ViVeTool GUI version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool-gui-version.jpg)
4. Select the**Deactivate Feature** option. Similarly, find the feature ID**36354489** and deactivate it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c17xsnbinCQ?si=xHKslFgC3QbxY4qW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Now, close the ViVeTool GUI and**restart** your system.
6. Open the File Explorer and you won’t see the tabs feature anymore.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nl0Z0eth1u4?si=0eecOBNfc--51AJO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Disable Any Windows 11 Feature Using ViVeTool

 File Explorer tabs are more useful than you think. But if you use another File Explorer program or can make do without it, ViVeTool is a great utility to disable/enable it. Moreover, it is completely free, and you can even enable other experimental features of Windows 11.

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
<li><a href="https://fox-boxes.techidaily.com/updated-samsung-photo-editor-review-pros-con-features-and-guide/"><u>[Updated] Samsung Photo Editor Review - Pros, Con, Features, and Guide</u></a></li>
<li><a href="https://vp-tips.techidaily.com/billboard-music-awards-2022-live-performance-full-hd-streaming-and-download/"><u>Billboard Music Awards 2022 Live Performance - Full HD Streaming and Download</u></a></li>
<li><a href="https://windows11.techidaily.com/explaining-0xc000003e-error-windows-app-failure-diagnosis/"><u>Explaining 0xC000003E Error: Windows App Failure Diagnosis</u></a></li>
<li><a href="https://win-webmaster.techidaily.com/guide-detaille-pour-changer-gif-en-video-mp4-gratuite-decouvrez-comment-le-faire-avec-laide-de-movavi/"><u>Guide Détaillé Pour Changer GIF en Vidéo MP4 Gratuite – Découvrez Comment Le Faire Avec L'Aide De Movavi</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-open-sticky-notes-at-startup-on-windows/"><u>How to Open Sticky Notes at Startup on Windows</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-mastering-visual-storytelling-the-cutting-edge-6-instagram-reel-tools/"><u>In 2024, Mastering Visual Storytelling The Cutting-Edge 6 Instagram Reel Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/incorinas-technology-and-apple-maps-for-windows-users/"><u>Incorinas Technology and Apple Maps for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-troubles-avoiding-sudden-game-stoppages/"><u>Navigating Windows Troubles: Avoiding Sudden Game Stoppages</u></a></li>
<li><a href="https://driver-install.techidaily.com/optimize-system-performance-with-new-hardware-drivers/"><u>Optimize System Performance with New Hardware Drivers</u></a></li>
<li><a href="https://windows11.techidaily.com/powershell-expertise-uncovering-network-details-in-windows/"><u>PowerShell Expertise: Uncovering Network Details in Windows</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/solved-how-to-transfer-from-apple-iphone-6s-to-iphone-15-drfone-by-drfone-transfer-from-ios/"><u>Solved How To Transfer From Apple iPhone 6s to iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/the-finest-videophone-tools-free-edition-listed-here/"><u>The Finest Videophone Tools Free Edition Listed Here</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unlocking-system-files-tips-for-managing-trustedinstaller-privileges-on-windows-11/"><u>Unlocking System Files: Tips for Managing TrustedInstaller Privileges on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/winerror-woes-be-gone-fixing-oculus-app-for-winxc/"><u>WinError Woes Be Gone: Fixing Oculus App for WinXC</u></a></li>
<li><a href="https://windows11.techidaily.com/wsl-and-the-surge-in-linux-popularity/"><u>WSL and the Surge in Linux Popularity</u></a></li>
</ul></div>

