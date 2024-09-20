---
title: Fixing Unclickable Recycling Symbol in Windows 11
date: 2024-09-19T18:37:15.155Z
updated: 2024-09-20T17:47:26.714Z
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
6. Rename the value as **{645FF040-5081-101B-9F08-00AA002F954E}**.
7. Next, double-click on the new DWORD value to open its properties.  
![registry editor nonnum new dword value edit 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/registry-editor-nonnum-new-dword-value-edit-0.jpg)
8. Type **0** in the Value data field and click **OK** to save the changes.
9. Close Registry Editor and restart your computer. Sometimes, you’ll need to restart your computer for the new registry modifications to work.

 If the issue persists, try to [create a new user account with administrative rights](https://www.makeuseof.com/windows-11-create-local-user-account/), [perform a system restore](https://www.makeuseof.com/use-system-restore-windows/), or [repair corrupted Windows files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

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
<li><a href="https://facebook-video-share.techidaily.com/updated-incorruptible-approach-to-disabling-youtubes-mini-videos/"><u>[Updated] Incorruptible Approach to Disabling YouTube’s Mini Videos</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-mastering-the-art-of-videotutorials-an-in-depth-guidebook/"><u>[Updated] Mastering the Art of Videotutorials An In-Depth Guidebook</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/embrace-1500-days-of-easy-learning-access/"><u>Embrace 1,500 Days of Easy Learning Access</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-unstartable-windows-speech-to-text-error/"><u>Fixing Unstartable Windows Speech-to-Text Error</u></a></li>
<li><a href="https://fox-blue.techidaily.com/in-2024-max-360-vs-hero-11-evaluating-the-best-gopro-for-action-videos/"><u>In 2024, Max 360 Vs. Hero 11 Evaluating the Best GoPro for Action Videos</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-the-magnificent-art-of-pokemon-go-streaming-on-honor-90-gt-drfone-by-drfone-virtual-android/"><u>In 2024, The Magnificent Art of Pokemon Go Streaming On Honor 90 GT? | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/preserving-clarity-in-editing-guide-to-non-interlaced-video-processing/"><u>Preserving Clarity in Editing: Guide to Non-Interlaced Video Processing</u></a></li>
<li><a href="https://facebook.techidaily.com/social-media-synergy-sending-instagram-reels-via-facebook/"><u>Social Media Synergy: Sending Instagram Reels via Facebook</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-error-0x800700e1-in-windows-11-os/"><u>Solutions for Error 0X800700E1 in Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-failed-display-sharing-on-windows-devices/"><u>Solutions for Failed Display Sharing on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-remedy-for-win-11-store-failures-code-x00000000/"><u>Swift Remedy for Win 11 Store Failures: Code X00000000</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-busy-resource-issue-in-windows-environments-153-chars/"><u>Tackling the Busy Resource Issue in Windows Environments (153 Chars)</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/transform-your-document-handling-at-home-or-in-a-small-business-with-the-fujitsu-scansnap-ix1400-an-in-depth-review/"><u>Transform Your Document Handling at Home or in a Small Business with the Fujitsu ScanSnap iX1400 - An In-Depth Review</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-overcoming-onedrives-add-folder-unsuccessful-on-pc/"><u>Troubleshooting: Overcoming OneDrive's 'Add Folder Unsuccessful' On PC</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134230/18498" target="_top" id="2134230">
  <img src="//a.impactradius-go.com/display-ad/18498-2134230" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134230/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

