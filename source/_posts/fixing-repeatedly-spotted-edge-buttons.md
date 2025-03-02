---
title: Fixing Repeatedly Spotted Edge Buttons
date: 2025-02-22T22:01:21.733Z
updated: 2025-03-02T08:47:29.904Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Repeatedly Spotted Edge Buttons
excerpt: This Article Describes Fixing Repeatedly Spotted Edge Buttons
keywords: Button Fix Guide,Edge Error Resolution,UI Repair Tips,Button Placement Correction,Edge Buttons Troubleshoot,Design Flaw Solutions,Interface Anomaly Fixes
thumbnail: https://thmb.techidaily.com/738343d11636524e97e883ecdfb55ee8c179338e8409002b7334f65b8debc634.jpg
---

## Fixing Repeatedly Spotted Edge Buttons

 Does Windows keep showing the Microsoft Edge shortcut on your desktop even after you delete it? Don’t worry, your computer hasn't been compromised. Several users have shared their experiences of Windows automatically generating the Edge shortcut after a system restart or update.

 Fortunately, there's no requirement to manually delete the Edge desktop shortcut repeatedly. Here are some helpful tips that should help resolve the issue in no time.

## 1\. Prevent Microsoft Edge From Opening at Startup

 By default, Microsoft Edge runs every time you start your Windows computer. Several users on the Microsoft forums reported fixing this particular issue by preventing Microsoft Edge from opening at startup. Hence, it’s the first thing you should try.

 You can use Task Manager to review all the apps that are configured to run at boot and disable Edge from there. Here are the steps you can follow:

1. Press **Win + X** to open the Power User menu.
2. Select **Task Manager** from the resulting menu.
3. Select **Startup apps** from the left pane.
4. Locate and select **Microsoft Edge** on the list. Right-click on it and select **Disabled** from the context menu.  
![Startup Apps in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Startup-Apps-in-Task-Manager.jpg)

 Additionally, you should also [access the startup folder on your Windows PC](https://www.makeuseof.com/access-startup-folder-windows/) and delete any shortcuts labeled Microsoft Edge.

## 2\. Edit Registry Files

 Another way to prevent the Microsoft Edge shortcut from reappearing on your desktop involves editing registry files.

 Making incorrect changes to the registry files can cause serious damage to your system. Hence, it’s a good idea to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

 Even if you are familiar with the registry editor, make sure you follow the steps carefully to [avoid accidentally messing up the Windows registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/).

 Use the following instructions:

1. Press **Win + R** to open the Run dialog box.
2. Type **regedit** in the text box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft**.
5. Right-click on the **Microsoft** key and select **New > Key**. Name it **EdgeUpdate**.
6. Right-click on the **EdgeUpdate** key and select **New > DWORD (32-bit) Value**. Rename it **CreateDesktopShortcutDefault**.
7. Double-click the newly created DWORD and enter **0** in the Value data field. Then, click **OK**.
8. Within the **EdgeUpdate** key, create another DWORD and name it **RemoveDesktopShortcutDefault**.
9. Double-click the **RemoveDesktopShortcutDefault** DWORD and enter **0** in the Value data field.
10. Click **OK**.  
![EdgeUpdate Key in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edgeupdate-key-in-registry.jpg)

 Close the Registry Editor window and restart your PC. After that, check if the issue is resolved.

## 3\. Modify Group Policy Settings

 If the issue remains even after you edit registry files, you can try modifying the group policy settings.

 The Group Policy Editor is only available in the Professional, Education, or Enterprise editions of Windows. That said, you can [access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) with a simple workaround.

 Follow these steps to modify Group Policy settings:

1. Press **Win + S** to open the search menu.
2. Type **gpedit.msc** in the search box and press **Enter**.
3. Select **Yes** if the User Account Control (UAC) prompt appears.
4. In the Local Group Policy Editor window, use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Components > Microsoft Edge**.
5. Double-click the **Allow Microsoft Edge to pre-launch at Windows startup, when the system is idle, and each time Microsoft Edge is closed** policy in the right pane.
6. Select the **Disabled** option.  
![Microsoft Edge pre-launch policy selected in the Local Group Policy Editor Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Local-Group-Policy-Editor-Window.jpg)
7. Hit Apply followed by **OK**.
8. Similarly, disable the **Allow Microsoft Edge to start and load the Start and New Tab page at Windows startup, and each time Microsoft Edge is closed** policy as well.

 Restart your PC one more time and check if the issue is resolved.

## 4\. Remove Microsoft Edge as the Default Browser

 Another reason why the Microsoft Edge shortcut may keep showing up on your Windows desktop is if you have set it as the default browser.

 Try [changing the default browser on your Windows PC](https://www.makeuseof.com/windows-11-change-default-browser/) to something other than Microsoft Edge and see if that fixes the issue.

 If you need help picking a reliable browser, you can check out [the best browsers for Windows](https://www.makeuseof.com/windows-11-best-browsers/).

## 5\. Restrict Other Users From Creating Desktop Shortcuts

 If you share your computer with others, someone else may be creating shortcuts for Edge without your permission. If you don't want this to happen, you can use the Group Policy Editor to prevent other users from creating desktop shortcuts.

 Here are the steps for the same:

1. Click the search icon on the taskbar to access the search menu.
2. Type **edit group policy** or **gpedit** in the search box and select the first result that appears.
3. Use the left pane to navigate to **User Configuration > Administrative Templates > Control Panel > Personalization**.
4. Double-click on the **Prevent changing desktop icons** policy in the right pane.
5. Select the **Enabled** option.
6. Click **Apply** and then **OK**.  
![Using the Local Group Policy to Prevent Others From Changing Desktop Icons](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Using-the-Local-Group-Policy-to-Prevent-Others-From-Changing-Desktop-Icons.jpg)

 And that's about it. Once you make the above changes, the other users won't be able to create, modify, or delete your desktop icons.

## 6\. Review Scheduled Tasks

 It is possible that a scheduled task is causing Windows to create a desktop shortcut for Edge repeatedly. To check for this possibility, you need to review tasks in the Task Scheduler app.

 Use these steps to check automated tasks in Task Scheduler:

1. Right-click on the **Start icon** and select **Run** from the menu that appears.
2. Type **taskschd.msc** in the box and press **Enter** to open the Task Scheduler app.
3. Select **Task Scheduler Library** in the left pane to view a list of tasks in the middle pane.
4. Locate and select any Edge-related tasks.
5. Click the **Disable** option in the right pane.  
![An Automated task selected in the Task Scheduler window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Task-Scheduler-Window.jpg)

 Further, you can [restrict others from creating and running tasks in the Task Scheduler app](https://www.makeuseof.com/windows-block-task-manager/) by modifying the group policy settings or the registry files.

## 7\. Uninstall Microsoft Edge From Your PC

 If none of the above tips help, you can consider uninstalling Microsoft Edge to fix the problem. This can be useful if Microsoft Edge isn’t your preferred browser anyway.

 Use Command Prompt or PowerShell to [uninstall Microsoft Edge from your Windows computer](https://www.makeuseof.com/windows-11-uninstall-microsoft-edge/). Once you remove the browser, the issue should be resolved.

## Prevent Microsoft Edge From Appearing on Your Desktop

 It can be confusing if Microsoft Edge’s shortcut keeps appearing on your desktop for no apparent reason. Hopefully, one of the above-mentioned fixes has helped fix the issue for good, and you are at peace.

 Does your Windows desktop look like a jumbled mess? If so, you can easily organize it by grouping desktop shortcut icons with a third-party program.

 Fortunately, there's no requirement to manually delete the Edge desktop shortcut repeatedly. Here are some helpful tips that should help resolve the issue in no time.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-record-videos.techidaily.com/new-new-youtube-earning-rules-unveiled/"><u>[New] New YouTube Earning Rules Unveiled</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-the-ultimate-guide-to-magix-music-maker-2024-review/"><u>[New] The Ultimate Guide to Magix Music Maker 2024 Review</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-leading-corporate-cloud-vault-selection/"><u>[Updated] 2024 Approved Leading Corporate Cloud Vault Selection</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-best-freefire-youtube-hashtags-and-tips-for-youtube-gaming-videos/"><u>[Updated] In 2024, Best FreeFire YouTube Hashtags and Tips For YouTube Gaming Videos</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-step-into-the-world-of-text-animation-14-must-see-examples/"><u>2024 Approved Step Into the World of Text Animation 14 Must-See Examples</u></a></li>
<li><a href="https://buynow-info.techidaily.com/cyberpunk-2077-evaluation-striking-despite-its-unpolished-edges/"><u>Cyberpunk 2077 Evaluation: Striking Despite Its Unpolished Edges</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-code-0x0000004e-hiccups/"><u>Fixing Windows' Code 0X0000004E Hiccups</u></a></li>
<li><a href="https://windows11.techidaily.com/from-obscurity-back-to-the-desktop-restoring-deleted-files-on-windows/"><u>From Obscurity Back To the Desktop: Restoring Deleted Files on Windows</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-change-your-zte-nubia-flip-5g-location-on-twitter-drfone-by-drfone-virtual-android/"><u>How to Change your ZTE Nubia Flip 5G Location on Twitter | Dr.fone</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/in-depth-maxsun-terminator-z790m-d5-ice-motherboard-analysis-featuring-5-m2-slots-and-ultrawhite-design/"><u>In-Depth Maxsun Terminator Z790M D5 Ice Motherboard Analysis – Featuring 5 M.2 Slots & Ultrawhite Design</u></a></li>
<li><a href="https://windows11.techidaily.com/masterful-mix-select-5-free-pc-audio-programs/"><u>Masterful Mix: Select 5 FREE PC Audio Programs</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/mastering-gadgets-the-ultimate-resource-from-toms-hardware/"><u>Mastering Gadgets: The Ultimate Resource From Tom's Hardware</u></a></li>
<li><a href="https://windows11.techidaily.com/mitigating-high-tiworkerexe-cpu-load-in-os/"><u>Mitigating High TiWorker.exe CPU Load in OS</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-the-admin-labyrinth-of-windows/"><u>Navigating Through the Admin Labyrinth of Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionize-your-speech-recording-experience-with-shortcuts-in-win-11/"><u>Revolutionize Your Speech Recording Experience with Shortcuts in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/simple-steps-to-activate-classic-photo-viewer-in-modern-windows-1111/"><u>Simple Steps to Activate Classic Photo Viewer in Modern Windows 11/11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-power-of-windows-11-overcome-11-errors/"><u>Unlock the Power of Windows 11 - Overcome 11 Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-premium-windows-laptops-of-year-2024/"><u>Unveiling the Premium Windows Laptops of Year 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/win10s-best-practices-for-gaming-video-capture-for-2024/"><u>Win10's Best Practices for Gaming Video Capture for 2024</u></a></li>
</ul></div>

