---
title: Fixing Unclickable Recycling Symbol in Windows 11
date: 2025-01-24T21:39:15.295Z
updated: 2025-01-29T22:31:22.231Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/9ECz3oZ8NrQ?si=86vkwkDJo9HQXpzt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KaqfZcWg5sE?si=LPmSKk7AFp8VxDFD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/pRR3Oq03EuE?si=ZTy8-WH0AesA9zRh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. In the **Desktop Icon Settings** dialog, select **Recycle Bin**.  
![enable recycle bin desktop icon settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/enable-recycle-bin-desktop-icon-settings-windows-11.jpg)
6. Click **Apply** and **OK** to save the changes.

 If you can’t access Group Policy Editor or if the issue persists, you can use the Registry Editor to fix this problem.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_SbYznUy_zY?si=ThBkP934r3mizi48" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/slm2NjVPNtk?si=9ow6g1ucmf0TnT4T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://article-knowledge.techidaily.com/updated-2024-approved-cutting-edge-tools-for-online-subtitle-editing/"><u>[Updated] 2024 Approved Cutting-Edge Tools for Online Subtitle Editing</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-2024-approved-skyline-your-videos-reach-writing-captivating-youtube-descs-using-templates/"><u>[Updated] 2024 Approved Skyline Your Video's Reach Writing Captivating Youtube Descs Using Templates</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-effortless-transformation-of-your-fb-video-content-to-mp3/"><u>[Updated] In 2024, Effortless Transformation of Your Fb Video Content to MP3</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-optimal-focus-techniques-for-videoleap-users/"><u>[Updated] Optimal Focus Techniques for Videoleap Users</u></a></li>
<li><a href="https://blog-min.techidaily.com/6-ways-to-transfer-contacts-from-lava-yuva-3-pro-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>6 Ways To Transfer Contacts From Lava Yuva 3 Pro to iPhone | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/affordable-xr-solutions-tackle-tech-induced-envy-for-apple-users-saving-you-money/"><u>Affordable XR Solutions Tackle Tech-Induced Envy for Apple Users, Saving You Money!</u></a></li>
<li><a href="https://howto.techidaily.com/android-safe-mode-how-to-turn-off-safe-mode-on-xiaomi-redmi-note-12-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Android Safe Mode - How to Turn off Safe Mode on Xiaomi Redmi Note 12 5G? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-a-network-locked-htc-u23-pro-phone-by-drfone-android/"><u>How to Unlock a Network Locked HTC U23 Pro Phone?</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-windows-11-to-launch-outlook-preview/"><u>Navigating Through Windows 11 to Launch Outlook Preview</u></a></li>
<li><a href="https://win-blog.techidaily.com/pc-gaming-woes-addressed-resolving-the-dual-fps-decrease-issue/"><u>PC Gaming Woes Addressed: Resolving the Dual FPS Decrease Issue</u></a></li>
<li><a href="https://ai-topics.techidaily.com/power-of-ai-thumbnail-generators-for-2024/"><u>Power of AI Thumbnail Generators for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/seamlessly-retrieve-content-from-a-shared-windows-space/"><u>Seamlessly Retrieve Content From a Shared Windows Space</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-content-unreachable-issue-with-steam-desktop-client/"><u>Solving Content Unreachable Issue with Steam Desktop Client</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-reactivate-windows-11s-silent-wireless-hotspot/"><u>Strategies to Reactivate Windows 11'S Silent Wireless Hotspot</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-concealment-start-menu-command-hideout/"><u>The Art of Concealment: Start Menu Command Hideout</u></a></li>
<li><a href="https://windows11.techidaily.com/top-essentials-for-selecting-a-win-pc-a-must-know-guide/"><u>Top Essentials for Selecting a Win PC: A Must-Know Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/uncomplicated-upgrade-the-essence-of-windows-11-installation/"><u>Uncomplicated Upgrade: The Essence of Windows 11 Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-best-matched-nvidia-drivers-gaming-studios/"><u>Unveiling Best Matched Nvidia Drivers – Gaming, Studios</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-solutions-for-unzipped-files-woes/"><u>Win 11: Solutions for Unzipped Files Woes</u></a></li>
</ul></div>

