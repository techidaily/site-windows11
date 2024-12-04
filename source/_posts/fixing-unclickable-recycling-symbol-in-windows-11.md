---
title: Fixing Unclickable Recycling Symbol in Windows 11
date: 2024-12-01T17:07:00.396Z
updated: 2024-12-03T21:13:01.455Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gSKkJrJ57EA?si=WDOmInPE9EgQa_tB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Bring Back the Recycle Bin Using the Group Policy Editor

 The Group Policy Editor lets you show or hide the Recycle Bin icon from the desktop. Check if you have modified and accidentally disabled the Recycle Bin group policy recently. If so you can set the Remove Recycle Bin icon from the desktop policy to "Not Configured" which will restore it.

 You may not find the Local Group Policy Editor in Windows Home Edition. However, you can run a batch script to [enable Group Policy Editor on the Windows Home edition](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) or skip to the Registry Editor-based fix in the next step.

 To restore the Recycle Bin icon using the Group Policy Editor:

1. Press **Win + R** to open **Run**.
2. Type **gpedit.msc** and click **OK** to open the **Group Policy Editor**.  
![gpedit msc windows 11 run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/gpedit-msc-windows-11-run.jpg)
3. Next, navigate to the following location:  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qn1XkPJde9Y?si=i6ZJARXO8sJhy2FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLO5dwmJAVs?si=1OYH8rv8aPaMsCiU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. In the **Desktop Icon Settings** dialog, select **Recycle Bin**.  
![enable recycle bin desktop icon settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/enable-recycle-bin-desktop-icon-settings-windows-11.jpg)
6. Click **Apply** and **OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/M5pwd2mwaQQ?si=qyZHgdTlbQbc32Mp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hHPljBHrvkA?si=HwdfDM9rlbABSIrx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-http.techidaily.com/new-2024-approved-free-mobile-live-stream-apps-essentials-for-smartphones/"><u>[New] 2024 Approved Free Mobile Live Stream Apps Essentials for Smartphones</u></a></li>
<li><a href="https://driver-download.techidaily.com/download-and-install-sony-vaio-driver-software-for-windows-systems/"><u>Download & Install Sony Vaio Driver Software for Windows Systems</u></a></li>
<li><a href="https://tech-hub.techidaily.com/easy-methods-for-downloading-and-converting-dvd-content-into-digital-format/"><u>Easy Methods for Downloading and Converting DVD Content Into Digital Format</u></a></li>
<li><a href="https://win-dash.techidaily.com/effortless-updates-how-to-improve-your-dell-precision-3820-g7-performance-with-newest-driver-installation/"><u>Effortless Updates: How To Improve Your Dell Precision 3820 G7 Performance with Newest Driver Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/evolving-taskbar-in-windows-an-annual-look-back/"><u>Evolving Taskbar in Windows: An Annual Look-Back</u></a></li>
<li><a href="https://discover-guides.techidaily.com/faites-le-moi-de-avenir-conversion-flac-vers-wav-gratuit-sur-internet-avec-le-convertisseur-rapide-movavi/"><u>Faites-Le Moi De Avenir: Conversion FLAC Vers WAV Gratuit Sur Internet Avec Le Convertisseur Rapide Movavi</u></a></li>
<li><a href="https://sound-issues.techidaily.com/guide-to-restoring-microphone-functionality-on-logitech-cameras/"><u>Guide to Restoring Microphone Functionality on Logitech Cameras</u></a></li>
<li><a href="https://windows11.techidaily.com/harnessing-file-operations-techniques-to-archive-and-extract/"><u>Harnessing File Operations: Techniques to Archive and Extract</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-counteract-dxgi-errors-after-device-loss/"><u>How to Counteract DXGI Errors After Device Loss</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-5-solutions-for-motorola-moto-g24-unlock-without-password-by-drfone-android/"><u>In 2024, 5 Solutions For Motorola Moto G24 Unlock Without Password</u></a></li>
<li><a href="https://windows11.techidaily.com/reconfigure-windows-11-task-manager-interface-view/"><u>Reconfigure Windows 11 Task Manager Interface View</u></a></li>
<li><a href="https://windows11.techidaily.com/recovering-from-disrupted-asana-use-a-focused-approach-for-pc-users/"><u>Recovering From Disrupted Asana Use: A Focused Approach for PC Users</u></a></li>
<li><a href="https://review-topics.techidaily.com/reinstall-hardware-drivers-with-device-manager-in-windows-11107-by-drivereasy-guide/"><u>Reinstall hardware drivers with Device Manager in Windows 11/10/7</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-secrets-to-windows-camera-media-storage/"><u>Unlocking the Secrets to Windows Camera Media Storage</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-undetected-toolbar-for-windows-11-users/"><u>Unlocking the Undetected Toolbar for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secrets-of-windows-process-aggregatehostexe/"><u>Unveiling the Secrets of Windows' Process AggregateHost.exe</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/video-editing-on-a-shoestring-16-free-and-intuitive-movie-makers-for-2024/"><u>Video Editing on a Shoestring 16 Free and Intuitive Movie Makers for 2024</u></a></li>
</ul></div>

