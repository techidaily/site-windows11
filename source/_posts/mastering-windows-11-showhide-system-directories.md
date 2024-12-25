---
title: "Mastering Windows 11: Show/Hide System Directories"
date: 2024-12-23T19:43:22.455Z
updated: 2024-12-25T18:11:30.322Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Windows 11: Show/Hide System Directories"
excerpt: "This Article Describes Mastering Windows 11: Show/Hide System Directories"
keywords: Win11 System Folders,Hide System DIRs Windows 11,Display System Folders PC,Conceal Windows 11 Directories,Expertly View/Hide Windows 11,Navigate Hidden Windows 11,Master Windows 11 Directory Visibility
thumbnail: https://thmb.techidaily.com/e12cb801e0d6f6813ed277d29658e5821adadea3db742df23467e5bb2d5168a7.jpg
---

## Mastering Windows 11: Show/Hide System Directories

 If you’re running the latest version of Windows 11, the folders in This PC will be hidden by default. That's by design so you can pay more attention to your drives. However, there’s a way you can unhide them so you can access them.

 In this guide, we are going to show you how to add or remove the 3D Objects, Documents, Music, Video, Pictures, and Downloads in This PC by making a few Windows Registry tweaks.

## Before You Start Adding or Removing Folders in This PC…

 We are going to make changes to the Windows Registry by adding keys and values to it using the Registry Editor. To fire it up, press **Win + R** to bring up the Windows Run dialog box, enter **regedit** in the text box, and then click **OK**.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Dn-24B6AURY?si=ErES2KWVnintY6h9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Before you proceed, we highly recommend reading our guide on [what the Windows Registry is and how to edit it](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) to familiarize yourself with what we will be doing next. Also important is knowing [how to back up the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). Considering this is the database that Windows stores the data it needs to operate properly, you will need this backup in case you make an error.

 For showing and hiding folders in This PC to work, make sure you’re running the latest version of Windows 11\. You'll know you have it if File Explorer has tabs.

 With the Registry Editor open, let's get to it.

## How to Show or Hide the 3D Objects Folder in This PC

 For the **3D Objects** folder, you need to add a key to the registry and the folder will pop up in This PC. So, in the address bar of the Registry Editor, enter the below path and then hit the **Enter** key:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace

 Next, right-click the **NameSpace** key in the left panel and select **New > Key**. Then, name that key **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}**. If the name is a bit too hard to type out, just copy and paste it.

![new-key-namespace-regedit-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/new-key-namespace-regedit-windows.jpg)

 Once done, refresh File Explorer by hitting **F5**. Now you will see that the **3D Objects** folder has appeared in This PC.

![3d-objects-this-pc](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/3d-objects-this-pc.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/W5aJC8okA8s?si=L2rnYAp-gmGlLQSf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To remove the folder again, just go back to the Registry Editor, right-click the **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}** key, and select **Delete**. After you refresh File Explorer, the folder will be gone.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/slm2NjVPNtk?si=9ow6g1ucmf0TnT4T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show or Hide the Documents, Music, Videos, Pictures, and/or Downloads Folders in This PC

 To add the **Documents** folder to This PC, enter the below path in the address bar of the Registry Editor and then hit **Enter** on your keyboard to go where its key is located:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{d3162b92-9365-467a-956b-92703aca08af}

 Right-click the **HideIfEnabled** value in the right panel and select **Delete**.

![delete-hideifenabled-value-regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/delete-hideifenabled-value-regedit.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/h5uImbOWmTg?si=z4kP-R0QbXbBAJTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now, refresh File Explorer with **F5** and the **Documents** folder will appear in This PC.

 To hide it, right-click the key on the left panel and select **New > DWORD (32-bit) Value** and name it **HideIfEnabled**. Double-click the newly-created value in the right panel, set **Value data** to **22ab9b9**, and then click **OK**.

![set-hideifenabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/set-hideifenabled.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sXLLPY11of0?si=-3YNnpnO0wbc0K_-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-hovers.techidaily.com/new-2024-approved-full-tutorial-on-exploiting-googles-ai-driven-speech-transcription-service/"><u>[New] 2024 Approved Full Tutorial on Exploiting Google's AI-Driven Speech Transcription Service</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-crafting-content-that-captivates-instagrams-roadmap-to-success/"><u>[New] In 2024, Crafting Content that Captivates Instagram’s Roadmap to Success</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/nveiling-the-ultimate-list-of-budget-friendly-video-editors-for-2024/"><u>[New] Unveiling the Ultimate List of Budget-Friendly Video Editors for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-movavi-plus-review-a-detailed-look-at-its-version/"><u>[Updated] Movavi Plus Review – A Detailed Look at Its Version</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/4-quick-ways-to-transfer-contacts-from-apple-iphone-xs-max-to-iphone-withwithout-itunes-drfone-by-drfone-transfer-from-ios/"><u>4 Quick Ways to Transfer Contacts from Apple iPhone XS Max to iPhone With/Without iTunes | Dr.fone</u></a></li>
<li><a href="https://app-tips.techidaily.com/exploring-the-best-digital-signing-applications-a-zdnet-recommendation/"><u>Exploring the Best Digital Signing Applications: A ZDNet Recommendation</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-through-windows-media-storage-woes-in-cam/"><u>Guiding Through Windows Media Storage Woes in Cam</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-combat-fall-guys-gameplay-interruptions-on-windows-devices/"><u>How To Combat Fall Guys Gameplay Interruptions on Windows Devices</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-change-lock-screen-wallpaper-on-realme-note-50-by-drfone-android/"><u>In 2024, How to Change Lock Screen Wallpaper on Realme Note 50</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-dilemma-of-disrupted-device-use-by-other-software/"><u>Overcoming the Dilemma of Disrupted Device Use by Other Software</u></a></li>
<li><a href="https://windows11.techidaily.com/proven-strategies-for-combining-diverse-windows-partitions/"><u>Proven Strategies for Combining Diverse Windows Partitions</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-to-mend-operation-0x0000011b-error-on-windows-11/"><u>Quick Guide to Mend Operation 0X0000011B Error on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-lost-wi-fi-connection-on-windows-11-devices/"><u>Restoring Lost Wi-Fi Connection on Windows 11 Devices</u></a></li>
<li><a href="https://games-able.techidaily.com/sparse-simplicity-dive-into-indolent-gaming/"><u>Sparse Simplicity: Dive Into Indolent Gaming</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-solutions-for-when-usb-tethering-fails/"><u>Step-by-Step Solutions for When USB Tethering Fails</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-making-your-cursor-stand-out-in-windows-11/"><u>The Ultimate Guide to Making Your Cursor Stand Out in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-faces-issue-file-thumbnails-not-appearing/"><u>Windows 11 Faces Issue: File Thumbnails Not Appearing</u></a></li>
</ul></div>

