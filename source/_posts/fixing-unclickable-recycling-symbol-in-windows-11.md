---
title: Fixing Unclickable Recycling Symbol in Windows 11
date: 2024-10-28T16:25:04.574Z
updated: 2024-10-30T16:53:15.018Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Unclickable Recycling Symbol in Windows 11
excerpt: This Article Describes Fixing Unclickable Recycling Symbol in Windows 11
keywords: Fix Click Issue,Recycle Symbol Non-Functional,Resolve W11 Recycling Error,Unclickable Symbol on Windows,Rectify Recycling Icon Error,Windows 11 Recycling Fix,Troubleshoot Click Problem
thumbnail: https://thmb.techidaily.com/4278a11dc73e1c0d6c218af281491c5ebbfcb593f38d324f2ddde851d89b6bd2.jpeg
---

## Fixing Unclickable Recycling Symbol in Windows 11

 The Recycle Bin has been a staple on Windows for a long time, but not everyone wants it on the desktop. You can disable it via the Desktop Icon Settings, but there is a bug where if you try to re-enable it, the "Recycle Bin" option is grayed out and cannot be toggled.

 Fortunately, you can fix the issue by reverting specific changes in the Registry Editor or the Group Policy Editor.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Bring Back the Recycle Bin Using the Group Policy Editor

 The Group Policy Editor lets you show or hide the Recycle Bin icon from the desktop. Check if you have modified and accidentally disabled the Recycle Bin group policy recently. If so you can set the Remove Recycle Bin icon from the desktop policy to "Not Configured" which will restore it.

 You may not find the Local Group Policy Editor in Windows Home Edition. However, you can run a batch script to [enable Group Policy Editor on the Windows Home edition](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) or skip to the Registry Editor-based fix in the next step.

 To restore the Recycle Bin icon using the Group Policy Editor:

1. Press **Win + R** to open **Run**.
2. Type **gpedit.msc** and click **OK** to open the **Group Policy Editor**.  
![gpedit msc windows 11 run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/gpedit-msc-windows-11-run.jpg)
3. Next, navigate to the following location:  
`User Configuration > Administrative Templates > Desktop`
4. In the right pane, locate and double-click on the **Remove Recycle Bin icon from the desktop** option to open its properties.  
![edit remove recycle bin icon from settings gpedit policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-remove-recycle-bin-icon-from-settings-gpedit-policy.jpg)
5. In the **Properties** dialog, select **Not Configured**.  
![edit remove recycle bin icon from settings gpedit policy not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-remove-recycle-bin-icon-from-settings-gpedit-policy-not-configured.jpg)
6. Click **Apply** and **OK** to save the changes.

 Close the Group Policy Editor and check your desktop to see if you can access the Recycle Bin. If not, make sure the Recycle Bin is set to show in Desktop Icon Settings.

 To enable Recycle Bin in Desktop Icon Settings:

1. Press **Win + I** to open **Settings**.
2. Next, open the **Personalization** tab in the left panel.
3. Click on **Themes**.  
![desktop icon settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/desktop-icon-settings-windows-11.jpg)
4. Click on **Desktop icon settings** under the **Related settings** section.
5. In the **Desktop Icon Settings** dialog, select **Recycle Bin**.  
![enable recycle bin desktop icon settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/enable-recycle-bin-desktop-icon-settings-windows-11.jpg)
6. Click **Apply** and **OK** to save the changes.

 If you can’t access Group Policy Editor or if the issue persists, you can use the Registry Editor to fix this problem.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135415/19272" target="_top" id="2135415">
  <img src="//a.impactradius-go.com/display-ad/19272-2135415" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135415/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Modify the Recycle Bin Registry Settings

 Another way to resolve and restore the grayed-out Recycle Bin icon in the Desktop settings is via the Windows Registry. You can modify the registry entry value responsible for the settings and configurations of Recycle Bin working to restore the functionality.

 Making modifications to the Windows registry involves tweaking settings that may harm your device if performed incorrectly. We recommend you [create a Windows restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and [take a Windows registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before attempting to modify the Windows registry.

 To modify the Recycle Bin registry value:

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK**. Click **Yes** if prompted by **User Account Control**.
3. In the Registry Editor, navigate to the following location. You can copy and paste the path in the editor for quicker navigation:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\NonEnum`
4. In the right pane, locate the **{645FF040-5081-101B-9F08-00AA002F954E}** DWORD (32-bit) value.  
![registry editor nonnum new dword value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/registry-editor-nonnum-new-dword-value.jpg)
5. If it does not exist, you’ll need to create a new value. To do this, right-click on the **NonEnum** subkey folder in the left pane and select **New > DWORD (32-bit) Value**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043618/7443" target="_top" id="2043618">
  <img src="//a.impactradius-go.com/display-ad/7443-2043618" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043618/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Rename the value as **{645FF040-5081-101B-9F08-00AA002F954E}**.
7. Next, double-click on the new DWORD value to open its properties.  
![registry editor nonnum new dword value edit 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/registry-editor-nonnum-new-dword-value-edit-0.jpg)
8. Type **0** in the Value data field and click **OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2052060/7443" target="_top" id="2052060">
  <img src="//a.impactradius-go.com/display-ad/7443-2052060" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2052060/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

9. Close Registry Editor and restart your computer. Sometimes, you’ll need to restart your computer for the new registry modifications to work.

 If the issue persists, try to [create a new user account with administrative rights](https://www.makeuseof.com/windows-11-create-local-user-account/), [perform a system restore](https://www.makeuseof.com/use-system-restore-windows/), or [repair corrupted Windows files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2112007/7443" target="_top" id="2112007">
  <img src="//a.impactradius-go.com/display-ad/7443-2112007" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2112007/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get Access to the Recycle Bin Desktop Icon Setting Again

 An incorrectly modified group policy can gray out the Recycle Bin icon in the Desktop Icon Settings dialog. Fortunately, it's an easy fix, and you should now have your Recycle Bin back to how you like it.

 Fortunately, you can fix the issue by reverting specific changes in the Registry Editor or the Group Policy Editor.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-audiovisual-excellence-the-premier-video-formats-for-youtube/"><u>[New] In 2024, Audiovisual Excellence The Premier Video Formats for YouTube</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-unlocking-vimeo-content-step-by-step-free-and-licensed-tools-guide-for-2024/"><u>[New] Unlocking Vimeo Content Step-by-Step Free & Licensed Tools Guide for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-whats-the-price-tag-for-1m-youtube-sights/"><u>[New] What's the Price Tag for 1M YouTube Sights?</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-11-free-youtube-audio-rippers-to-download-audio-from-youtube/"><u>[Updated] 11 FREE YouTube Audio Rippers to Download Audio From YouTube</u></a></li>
<li><a href="https://app-tips.techidaily.com/chatgpt-2024-ultimate-review-unpacking-advanced-features-and-solving-internal-server-malfunctions/"><u>ChatGPT 2024 Ultimate Review: Unpacking Advanced Features and Solving Internal Server Malfunctions</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/free-premiere-pro-starter-kit-with-top-templates-for-2024/"><u>Free Premiere Pro Starter Kit with Top Templates for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-error-495-while-downloadupdating-android-apps-on-lenovo-thinkphone-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Error 495 While Download/Updating Android Apps On Lenovo ThinkPhone | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-how-to-apply-a-classic-video-transition-with-camtasia-9/"><u>In 2024, How to Apply a Classic Video Transition with Camtasia 9</u></a></li>
<li><a href="https://windows11.techidaily.com/minimizing-delays-boosting-speed-of-windows-discord-app/"><u>Minimizing Delays: Boosting Speed of Windows Discord App</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-frequent-rainmeter-quirks-on-your-system/"><u>Navigating Through Frequent Rainmeter Quirks on Your System</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-to-file-explorer-bypassing-quick-access-with-onedrive/"><u>Navigating to File Explorer Bypassing Quick Access with OneDrive</u></a></li>
<li><a href="https://windows11.techidaily.com/no-apps-needed-windows-11-note-hacks/"><u>No Apps Needed: Windows 11 Note Hacks</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/python-solution-for-silencing-bursty-fan-noises-and-reducing-app-bloat-on-nzxt-kraken-aio-systems/"><u>Python Solution for Silencing Bursty Fan Noises & Reducing App Bloat on NZXT Kraken AIO Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-overcoming-fullscreen-obstacles-on-windows/"><u>Quick Guide: Overcoming Fullscreen Obstacles on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-accuracy-fixed-discord-games-status-errors-windows/"><u>Restoring Accuracy: Fixed Discord Games Status Errors (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-rdp-access-on-windows-11-no-password/"><u>Unlocking RDP Access on Windows 11 No Password</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-recover-unseen-additional-monitor/"><u>Windows 11: Recover Unseen Additional Monitor</u></a></li>
</ul></div>

