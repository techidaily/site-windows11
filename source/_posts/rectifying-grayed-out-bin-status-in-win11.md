---
title: Rectifying Grayed Out Bin Status in Win11
date: 2025-02-27T18:01:14.063Z
updated: 2025-03-02T09:06:34.175Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Rectifying Grayed Out Bin Status in Win11
excerpt: This Article Describes Rectifying Grayed Out Bin Status in Win11
keywords: Fix Windows Bin Error,Clear Grayed Bins,Resolve Bin Issues,Enable Bin Access,Unblock Bin Icon,Restart Bin Status,Activate Bin Functions
thumbnail: https://thmb.techidaily.com/08b59308ea1479863a214168a367629cf0b1393331c870e52c284f342d82b8ac.jpeg
---

## Rectifying Grayed Out Bin Status in Win11

 The Recycle Bin has been a staple on Windows for a long time, but not everyone wants it on the desktop. You can disable it via the Desktop Icon Settings, but there is a bug where if you try to re-enable it, the "Recycle Bin" option is grayed out and cannot be toggled.

 Fortunately, you can fix the issue by reverting specific changes in the Registry Editor or the Group Policy Editor.

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
<li><a href="https://youtube-tips.techidaily.com/n-2024-crafting-a-youtube-future-scaling-up-or-staying-independent/"><u>[New] In 2024, Crafting a YouTube Future Scaling Up or Staying Independent?</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-cutting-through-steps-posting-tiktok-videos-on-twitter/"><u>[New] In 2024, Cutting Through Steps Posting TikTok Videos on Twitter</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-pushing-boundaries-with-vr-choosing-your-ultimate-game-platform/"><u>[New] Pushing Boundaries with VR Choosing Your Ultimate Game Platform</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-2024-approved-premiere-pros-finest-10-text-plans/"><u>[Updated] 2024 Approved Premiere Pro's Finest 10 Text Plans</u></a></li>
<li><a href="https://location-social.techidaily.com/4-most-known-ways-to-find-someone-on-tinder-for-nubia-red-magic-8s-proplus-by-name-drfone-by-drfone-virtual-android/"><u>4 Most-Known Ways to Find Someone on Tinder For Nubia Red Magic 8S Pro+ by Name | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-your-digital-footprints-in-windows-11/"><u>Exploring Your Digital Footprints in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-visual-studio-code-crashing-on-windows-11/"><u>How to Fix Visual Studio Code Crashing on Windows 11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-iconic-visual-alteration-suite-imagefusion-xtreme/"><u>In 2024, Iconic Visual Alteration Suite ImageFusion Xtreme</u></a></li>
<li><a href="https://hardware-help.techidaily.com/intel-core-i9-and-i7-cpus-experience-majority-of-warframe-incidents-developer-insight/"><u>Intel Core I9 and I7 CPUs Experience Majority of Warframe Incidents: Developer Insight</u></a></li>
<li><a href="https://windows11.techidaily.com/personalizing-your-workspace-on-pc-themes-from-the-microsoft-store/"><u>Personalizing Your Workspace on PC: Themes From the Microsoft Store</u></a></li>
<li><a href="https://windows11.techidaily.com/propel-workflow-speed-with-windows-smart-launcher/"><u>Propel Workflow Speed with Windows' Smart Launcher</u></a></li>
<li><a href="https://hardware-help.techidaily.com/quick-and-effective-methods-for-keeping-your-gtx-1660-drivers-current/"><u>Quick and Effective Methods for Keeping Your GTX 1660 Drivers Current</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-to-windows-media-player-launch/"><u>Step-by-Step Guide to Windows Media Player Launch</u></a></li>
<li><a href="https://windows11.techidaily.com/the-edge-dilemma-ethical-choices-amidst-societal-controls/"><u>The Edge Dilemma: Ethical Choices Amidst Societal Controls</u></a></li>
<li><a href="https://windows11.techidaily.com/tweaking-internet-security-features-for-win-1011/"><u>Tweaking Internet Security Features for Win 10/11</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/unlock-your-disabled-apple-iphone-12-pro-max-without-itunes-in-5-ways-by-drfone-ios/"><u>Unlock Your Disabled Apple iPhone 12 Pro Max Without iTunes in 5 Ways</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-potential-extending-your-pin-on-windows-11/"><u>Unlocking the Potential: Extending Your PIN on Windows 11</u></a></li>
</ul></div>

