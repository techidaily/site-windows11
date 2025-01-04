---
title: Easily Knock Off the OneDrive Feature From File Explorer
date: 2024-12-28T23:29:50.396Z
updated: 2025-01-03T20:21:58.425Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Easily Knock Off the OneDrive Feature From File Explorer
excerpt: This Article Describes Easily Knock Off the OneDrive Feature From File Explorer
keywords: Remove OneDrive in Explorer,Exclude DriveOneFeature,FileExplorerOneDrive-KnockOff,FileManagerNoDriveFeatures,EliminateDrivesInExplorer,UnlinkFileCenterToDrives,DropOneDriveSyncFromFinder
thumbnail: https://thmb.techidaily.com/75030bd59360efbfc2946329061573b90f37300b7251c4b711e0f5f10f28322c.jpg
---

## Easily Knock Off the OneDrive Feature From File Explorer

 The OneDrive cloud storage client comes pre-installed on your Windows 11 computer. By default, you'll notice a OneDrive shortcut in the left pane of File Explorer, allowing quick access to your OneDrive files and folders.

 However, if you find the shortcut cluttering or ruining your File Explorer experience, you can remove it using a registry hack. Here's how to remove the OneDrive icon from File Explorer without uninstalling OneDrive.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PUDdKOsEN74?si=tkZf-KVinjuwmgx9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Remove OneDrive Shortcut From File Explorer via the Registry Editor

 You can remove the OneDrive icon from File Explorer using a registry hack. This way, you can get rid of the icon in File Explorer without uninstalling the OneDrive client. If you would rather remove the app entirely, follow our guide on[removing OneDrive on Windows 11](https://www.makeuseof.com/windows-11-disable-remove-onedrive/) .

 Note that modifying the Windows registry involves risk. We recommend you[create a system restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed with the steps below. A restore point will help you restore your computer in case something goes wrong.

 Once done, follow these steps to remove the OneDrive shortcut from File Explorer:

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open Registry Editor. Click**Yes** if prompted by**User Account Control (UAC).**
3. Next, in the Registry Editor, navigate to the following location. Copy and paste the registry path in the editor for quicker navigation:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
4. In the right pane, right-click on**System.IsPinnedToNameSpaceTree** DWORD value and select**Modify** .  
![remove onedrive icon windows 11 registry editor modify system is pinned to name space free](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-modify-system-is-pinnedtonamespace-free.jpg)
5. In the**Value data** field, type**0** and click**OK** .  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0pSRlspzW-A?si=A82G3Yxwj_31cKDq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![remove onedrive icon windows 11 registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor.jpg)
6. Next, navigate to the following location in Registry Editor:  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SyMZxS9479s?si=0T6zZpyN2LBftFTM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace`
7. In the left pane, right-click on**{018D5C66-4533-4307-9B53-224DE2ED1FE6}** and select**Delete** to remove the entry.  
![remove onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)
8. Once done, close the Registry Editor.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/465CTOm8om0?si=63RxowNMCFA4fPUa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

9. When you open File Explorer, the OneDrive icon will not be visible anymore.

## How to Show the OneDrive Icon Again in File Explorer

![show onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/show-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)

 To show the OneDrive icon in File Explorer, you’ll need to modify a registry entry again. Here’s how to do it.

1. Press**Win + R** to open**Registry Editor.**
2. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
3. In the right pane, double-click on**System.IsPinnedToNameSpaceTree** DWORD value.
4. Next, type**1** in the**Value data f** ield and click**OK** to save the changes.
5. Relaunch File Explorer to see the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2En1CHbiYwA?si=jZKzTr9EIT2ShjGK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Remove OneDrive Icon Without Uninstalling OneDrive

 This registry hack is a handy way to make the OneDrive icon disappear without deleting the app entirely from your PC. Alternatively, if you don’t use the service, you can completely remove OneDrive on Windows 11 or disable the service using Group Policy Editor.

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
<li><a href="https://some-skills.techidaily.com/updated-transcendence-in-music-mixing-crossfade-unveiled/"><u>[Updated] Transcendence in Music Mixing Crossfade Unveiled</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-equality-and-innovation-an-easeus-analysis/"><u>2024 Approved Equality and Innovation - An EaseUS Analysis</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/1722881712723-apple-music-continuous-streaming-learn-how-to-pause-it/"><u>Apple Music Continuous Streaming? Learn How to Pause It</u></a></li>
<li><a href="https://sound-issues.techidaily.com/expert-advice-overcoming-sound-issues-in-the-popular-video-game-outriders/"><u>Expert Advice: Overcoming Sound Issues in the Popular Video Game, Outriders</u></a></li>
<li><a href="https://sound-issues.techidaily.com/expert-tips-for-overcoming-pubg-battlegrounds-voice-chat-issues/"><u>Expert Tips for Overcoming PUBG Battlegrounds' Voice Chat Issues</u></a></li>
<li><a href="https://program-issues.techidaily.com/fixing-hardware-and-driver-issues-for-optimal-rainbow-six-extraction-performance/"><u>Fixing Hardware and Driver Issues for Optimal Rainbow Six Extraction Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/harmonize-workflow-setting-active-hours-on-windows-11-for-peace-of-mind/"><u>Harmonize Workflow: Setting Active Hours on Windows 11 for Peace of Mind</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-pokemon-go-error-12-failed-to-detect-location-on-vivo-y100-drfone-by-drfone-virtual-android/"><u>In 2024, Pokemon Go Error 12 Failed to Detect Location On Vivo Y100? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/perfectly-presented-photos-mastering-the-art-of-crafting-captivating-slideshows-in-win11-photos-app/"><u>Perfectly Presented Photos: Mastering the Art of Crafting Captivating Slideshows in Win11 Photos App</u></a></li>
<li><a href="https://windows11.techidaily.com/pushing-boundaries-my-quest-to-overcome-app-guard-censorship/"><u>Pushing Boundaries: My Quest to Overcome App Guard Censorship</u></a></li>
<li><a href="https://windows11.techidaily.com/rectify-windows-error-reestablishing-java-vm/"><u>Rectify Windows Error: Reestablishing Java VM</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-searching-on-windows-techniques-beyond-ls-command/"><u>Seamless Searching on Windows: Techniques Beyond LS Command</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-fixing-windows-office-error-0x80041015/"><u>Solutions for Fixing Windows Office Error 0X80041015</u></a></li>
<li><a href="https://windows11.techidaily.com/the-savvy-buyers-guide-to-finding-windows-11-deals/"><u>The Savvy Buyer's Guide to Finding Windows 11 Deals</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/top-cameras-for-capturing-sporting-moments-for-2024/"><u>Top Cameras for Capturing Sporting Moments for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unveiling-legal-stewards-of-ai-driven-artistry/"><u>Unveiling Legal Stewards of AI-Driven Artistry</u></a></li>
</ul></div>

