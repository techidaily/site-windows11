---
title: Transforming File System Visibility on Modern Windows PCs
date: 2024-08-08T06:08:00.928Z
updated: 2024-08-09T06:08:00.928Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Transforming File System Visibility on Modern Windows PCs
excerpt: This Article Describes Transforming File System Visibility on Modern Windows PCs
keywords: File Visibility Update,Windows PC Transformation,Modern OS Access Control,File System Reveal Tech,Enhanced System Insight,Windows Files Disclosure,Modern Desktop Privacy
thumbnail: https://thmb.techidaily.com/c0c3ff7158c5ed074bf14161f2b9dd7e6d6a38364c8a3f7d8b03f364961bda60.jpg
---

## Transforming File System Visibility on Modern Windows PCs

 If you’re running the latest version of Windows 11, the folders in This PC will be hidden by default. That's by design so you can pay more attention to your drives. However, there’s a way you can unhide them so you can access them.

 In this guide, we are going to show you how to add or remove the 3D Objects, Documents, Music, Video, Pictures, and Downloads in This PC by making a few Windows Registry tweaks.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->
## Before You Start Adding or Removing Folders in This PC…

 We are going to make changes to the Windows Registry by adding keys and values to it using the Registry Editor. To fire it up, press **Win + R** to bring up the Windows Run dialog box, enter **regedit** in the text box, and then click **OK**.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

 Before you proceed, we highly recommend reading our guide on [what the Windows Registry is and how to edit it](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) to familiarize yourself with what we will be doing next. Also important is knowing [how to back up the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). Considering this is the database that Windows stores the data it needs to operate properly, you will need this backup in case you make an error.

 For showing and hiding folders in This PC to work, make sure you’re running the latest version of Windows 11\. You'll know you have it if File Explorer has tabs.

 With the Registry Editor open, let's get to it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
<!-- affiliate ads end -->
## How to Show or Hide the 3D Objects Folder in This PC

 For the **3D Objects** folder, you need to add a key to the registry and the folder will pop up in This PC. So, in the address bar of the Registry Editor, enter the below path and then hit the **Enter** key:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace

 Next, right-click the **NameSpace** key in the left panel and select **New > Key**. Then, name that key **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}**. If the name is a bit too hard to type out, just copy and paste it.

![new-key-namespace-regedit-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/new-key-namespace-regedit-windows.jpg)

 Once done, refresh File Explorer by hitting **F5**. Now you will see that the **3D Objects** folder has appeared in This PC.

![3d-objects-this-pc](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/3d-objects-this-pc.jpg)

 To remove the folder again, just go back to the Registry Editor, right-click the **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}** key, and select **Delete**. After you refresh File Explorer, the folder will be gone.

## How to Show or Hide the Documents, Music, Videos, Pictures, and/or Downloads Folders in This PC

 To add the **Documents** folder to This PC, enter the below path in the address bar of the Registry Editor and then hit **Enter** on your keyboard to go where its key is located:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{d3162b92-9365-467a-956b-92703aca08af}

 Right-click the **HideIfEnabled** value in the right panel and select **Delete**.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
![delete-hideifenabled-value-regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/delete-hideifenabled-value-regedit.jpg)

 Now, refresh File Explorer with **F5** and the **Documents** folder will appear in This PC.

 To hide it, right-click the key on the left panel and select **New > DWORD (32-bit) Value** and name it **HideIfEnabled**. Double-click the newly-created value in the right panel, set **Value data** to **22ab9b9**, and then click **OK**.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![set-hideifenabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/set-hideifenabled.jpg)

 Now when you refresh This PC in File Explorer, you will see that the **Documents** folder is gone.

 The steps to show or hide the other folders from this point on are the same. Just go to the respective key in the Registry Editor and either delete the **HideIfEnabled** value to show the folder in this PC or create the value and set it to **22ab9b9** to hide the folder.

 Here’s the path to the **Music** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{3dfdf296-dbec-4fb4-81d1-6a3438bcf4de}

 Here’s the path to the **Video** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{f86fa3ab-70d2-4fc7-9c99-fcbf05467f3a}

 Here’s the path to the **Pictures** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{24ad3ad4-a569-4530-98e1-ab02f9417aa8}

 Here’s the path to the **Downloads** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{088e3905-0323-4b02-9826-5d99428e115f}

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Choose the Folders You Want to Appear on This PC in Windows 11

 If you want to see folders on This PC, you can do so by making a couple of edits to the Windows Registry. While we do recommend that you know what you’re doing if you proceed, we have made the instructions relatively simple to follow so there's minimal chance of messing up the registry.

 As long as you take the necessary steps not to mess up the Windows Registry, you should be able to hide and show the folders you want easily.


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
<li><a href="https://youtube-tips.techidaily.com/024-approved-how-to-download-youtube-playlist-step-by-step/"><u>[New] 2024 Approved  How to Download YouTube Playlist-Step by Step</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-harmonizing-music-and-video-on-tiktok/"><u>[Updated] Harmonizing Music and Video on TikTok</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-streamlining-design-with-new-fonts-in-after-effects/"><u>[Updated] Streamlining Design with New Fonts in After Effects</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-tackling-youtube-challenges-head-on-with-insights-from-hub-of-creators/"><u>[Updated] Tackling YouTube Challenges Head-On with Insights From Hub of Creators</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-writers-guide-embedding-images-in-articles-without-spending/"><u>[Updated] Writers' Guide  Embedding Images in Articles Without Spending</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-instant-interaction-the-art-of-crafting-instagram-stories-questions/"><u>2024 Approved  Instant Interaction  The Art of Crafting Instagram Stories Questions</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-tune-and-time-lapses-creating-music-videos-with-your-phone/"><u>2024 Approved  Tune & Time Lapses  Creating Music Videos with Your Phone</u></a></li>
<li><a href="https://windows11.techidaily.com/4-ways-microsoft-is-replacing-cortana-in-windows/"><u>4 Ways Microsoft Is Replacing Cortana in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/7-techniques-for-reviving-a-stuck-dark-screen-mode/"><u>7 Techniques for Reviving a Stuck Dark Screen Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/a-peek-into-the-soulful-machine-activating-windows-private-character-analysis-platform/"><u>A Peek Into the Soulful Machine: Activating Windows’ Private Character Analysis Platform</u></a></li>
<li><a href="https://windows11.techidaily.com/a-simple-way-to-inspect-and-erase-window-logs/"><u>A Simple Way to Inspect & Erase Window Logs</u></a></li>
<li><a href="https://windows11.techidaily.com/accessible-windows-for-new-users-and-learners/"><u>Accessible Windows for New Users & Learners</u></a></li>
<li><a href="https://windows11.techidaily.com/achieving-perfect-boot-strategies-to-configure-startup-services-in-win11/"><u>Achieving Perfect Boot: Strategies to Configure Startup Services in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-time-display-in-the-taskbar-of-window-11/"><u>Adjusting Time Display in the Taskbar of Window 11</u></a></li>
<li><a href="https://windows11.techidaily.com/affordable-access-to-windows-11-licenses/"><u>Affordable Access to Windows 11 Licenses</u></a></li>
<li><a href="https://windows11.techidaily.com/apexs-windows-woes-strategies-to-clear-no-server-error-(156-chars/"><u>Apex's Windows Woes: Strategies to Clear No-Server Error (<156 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/banish-file-explorer-errors-essential-fixes-for-win11-users/"><u>Banish File Explorer Errors: Essential Fixes for Win11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/bluescreenview-explained-for-everyday-users/"><u>BlueScreenView Explained for Everyday Users</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-productivity-with-windows-11-strategies/"><u>Boosting Productivity with Windows 11 Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/cant-insert-new-cells-in-microsoft-excel-for-windows-try-these-fixes/"><u>Can’t Insert New Cells in Microsoft Excel for Windows? Try These Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/circumventing-firewall-restriction-chrome-connectivity-solution/"><u>Circumventing Firewall Restriction: Chrome Connectivity Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-windows-11s-application-could-not-be-started-error-xc000003e/"><u>Combatting Windows 11'S Application Could Not Be Started Error Xc000003e</u></a></li>
<li><a href="https://windows11.techidaily.com/contrasting-the-workflow-of-cloud-based-and-disk-installed-windows-oses/"><u>Contrasting the Workflow of Cloud-Based & Disk Installed Windows OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/cost-saving-strategies-for-new-windows-11-users/"><u>Cost-Saving Strategies for New Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/curbing-resource-conflicts-on-pcs-running-windows-1011-153-chars/"><u>Curbing Resource Conflicts on PCs Running Windows 10/11 (153 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-edge-tweaks-for-your-pc-explore-alomwares-capabilities/"><u>Cutting-Edge Tweaks for Your PC: Explore AlomWare's Capabilities</u></a></li>
<li><a href="https://windows11.techidaily.com/dealing-with-access-issues-fixing-the-no-write-allowed-error/"><u>Dealing with Access Issues: Fixing the No Write Allowed Error</u></a></li>
<li><a href="https://windows11.techidaily.com/decode-and-dissolve-rectifying-win11-webcam-issue-error-a00f4289/"><u>Decode & Dissolve: Rectifying Win11 Webcam Issue - Error A00F4289</u></a></li>
<li><a href="https://windows11.techidaily.com/diagnosing-and-fixing-printmanagement-error-on-windows-os/"><u>Diagnosing and Fixing 'PrintManagement' Error on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/diagnosing-and-fixing-microsoft-windows-nearby-share-malfunction/"><u>Diagnosing and Fixing Microsoft Windows Nearby Share Malfunction</u></a></li>
<li><a href="https://windows11.techidaily.com/discovering-new-horizons-for-galaxy-users-on-pc/"><u>Discovering New Horizons for Galaxy Users on PC</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-discovering-the-most-trusted-mac-snipers/"><u>In 2024, Discovering the Most Trusted Mac Snipers</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/optimal-video-intros-selecting-the-top-16-to-increase-views-for-2024/"><u>Optimal Video Intros  Selecting the Top 16 to Increase Views for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-your-photos-after-nokia-c22-has-been-deleted-by-fonelab-android-recover-photos/"><u>Recover your photos after Nokia C22 has been deleted.</u></a></li>
<li><a href="https://driver-install.techidaily.com/reinstall-audio-driver-to-fix-sound-problems-on-windows-10/"><u>Reinstall Audio Driver to Fix Sound Problems on Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/1719256266387-repairing-email-notification-shortcom-written-exercise/"><u>Repairing Email Notification Shortcom Written Exercise</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/resolving-the-issue-of-diagonal-or-sideways-straight-line-distortions-in-your-display/"><u>Resolving the Issue of Diagonal or Sideways Straight Line Distortions in Your Display</u></a></li>
<li><a href="https://howto.techidaily.com/xiaomi-redmi-note-13-pro-5g-camera-not-working-unexpected-error-fix-it-now-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Xiaomi Redmi Note 13 Pro 5G Camera Not Working Unexpected Error? Fix It Now | Dr.fone</u></a></li>
</ul></div>
