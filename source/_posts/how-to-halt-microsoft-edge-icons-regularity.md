---
title: How to Halt Microsoft Edge Icons' Regularity
date: 2024-08-15T15:58:05.039Z
updated: 2024-08-16T15:58:05.039Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Halt Microsoft Edge Icons' Regularity
excerpt: This Article Describes How to Halt Microsoft Edge Icons' Regularity
keywords: Stop Edge Icon Changes,Stopping Microsoft Edge Update,Freeze Edge Icon Positioning,Prevent Edge Icon Rotation,Halt Edge Icons Frequency,Disable Edge Icon Updates,Pause Microsoft Edge Icon Movement
thumbnail: https://thmb.techidaily.com/b5dfde40e2a9ad5275b840b5f0fbb161aac4de7d7745911720b5a34076945390.jpg
---

## How to Halt Microsoft Edge Icons' Regularity

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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->

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
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Hit Apply followed by **OK**.
8. Similarly, disable the **Allow Microsoft Edge to start and load the Start and New Tab page at Windows startup, and each time Microsoft Edge is closed** policy as well.

 Restart your PC one more time and check if the issue is resolved.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254762&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/11_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->

 Further, you can [restrict others from creating and running tasks in the Task Scheduler app](https://www.makeuseof.com/windows-block-task-manager/) by modifying the group policy settings or the registry files.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
## 7\. Uninstall Microsoft Edge From Your PC

 If none of the above tips help, you can consider uninstalling Microsoft Edge to fix the problem. This can be useful if Microsoft Edge isn’t your preferred browser anyway.

 Use Command Prompt or PowerShell to [uninstall Microsoft Edge from your Windows computer](https://www.makeuseof.com/windows-11-uninstall-microsoft-edge/). Once you remove the browser, the issue should be resolved.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411"><img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-critical-selection-of-best-screen-recorders-android-for-2024/"><u>[New] Critical Selection of Best Screen Recorders (Android) for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ulti-channel-mastery-coordinated-content-consumption-for-2024/"><u>[New] Multi-Channel Mastery  Coordinated Content Consumption for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-the-ultimate-guide-to-effective-screen-recorders/"><u>[New] The Ultimate Guide to Effective Screen Recorders</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-pixelperfect-screen-capture-software/"><u>[Updated] 2024 Approved  PixelPerfect Screen Capture Software</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-step-up-your-photo-game-with-these-ingenious-pixlr-techniques-for-2024/"><u>[Updated] Step Up Your Photo Game with These Ingenious Pixlr Techniques for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-transformative-strategies-for-broadcast-excellence-wirecast-on-youtube/"><u>[Updated] Transformative Strategies for Broadcast Excellence  WireCast on YouTube</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-optimal-transformation-tool-for-hd-videos/"><u>2024 Approved  Optimal Transformation Tool for HD Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-fatigued-performance-in-win10plusedge-browser/"><u>Fixing Fatigued Performance in Win10+Edge Browser</u></a></li>
<li><a href="https://windows11.techidaily.com/gaming-past-present-atlasos-enablement/"><u>Gaming Past, Present: AtlasOS Enablement</u></a></li>
<li><a href="https://windows11.techidaily.com/hidden-screens-revealed-the-most-effective-6-techniques-to-recover-off-screen-apps-in-win/"><u>Hidden Screens Revealed: The Most Effective 6 Techniques to Recover Off-Screen Apps in Win</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-can-i-unlock-my-iphone-7-plus-after-forgetting-my-pin-code-drfone-by-drfone-ios/"><u>How Can I Unlock My iPhone 7 Plus After Forgetting my PIN Code? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-disable-amdnvidia-graphics-ui-extras/"><u>How to Disable AMD/Nvidia Graphics UI Extras</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-ignore-microsofts-app-verification-warnings/"><u>How to Ignore Microsoft's App Verification Warnings</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reactivate-a-unresponsive-windows-start-button/"><u>How to Reactivate a Unresponsive Window's Start Button</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-resolve-offline-printer-problems-in-os/"><u>How To Resolve Offline Printer Problems in OS</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-revert-your-windows-backup-settings/"><u>How To Revert Your Windows Backup Settings</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-androids-gaming-revolution-experience-the-power-of-kinemaster-app/"><u>In 2024, Android's Gaming Revolution  Experience the Power of KineMaster App</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-fake-snapchat-location-on-nokia-150-2023-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fake Snapchat Location on Nokia 150 (2023) | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/isolating-and-resolving-unilateral-sound-issue-on-win-os/"><u>Isolating and Resolving Unilateral Sound Issue on WIN OS</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-calculators-dark-scheme/"><u>Mastering Windows Calculator's Dark Scheme</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-reinstate-working-utorrent-installer-in-various-windows-versions/"><u>Methods to Reinstate Working uTorrent Installer in Various Windows Versions</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-and-resolving-steam-setup-errors-with-win11/"><u>Navigating and Resolving Steam Setup Errors with Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-setbacks-due-to-recent-windows-installation/"><u>Overcoming Setbacks Due to Recent Windows Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-battlenet-being-inaccessible-in-windows-1011/"><u>Quick Fixes for Battle.net Being Inaccessible in Windows 10/11</u></a></li>
<li><a href="https://extra-information.techidaily.com/simple-steps-for-quick-file-migration/"><u>Simple Steps for Quick File Migration</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-fixing-windows-updates-error-xcode-0x80246007/"><u>Solutions for Fixing Windows Updates Error – XCode 0X80246007</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-to-file-transfer-problems-on-windows-1011/"><u>Solutions to File Transfer Problems on Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-failed-page-loading-on-ms-store/"><u>Steps to Resolve Failed Page Loading on MS Store</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-tackle-stranded-error-on-xbox-app-windows-devices/"><u>Steps to Tackle 'Stranded' Error on Xbox App Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-resolve-windows-1110s-nvidia-access-problem/"><u>Strategies to Resolve Windows 11/10'S NVidia Access Problem</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-collection-of-task-management-tools-for-windows-11-users/"><u>The Ultimate Collection of Task Management Tools for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-file-download-issues-on-windows-11-6/"><u>Troubleshooting File Download Issues on Windows 11 (6)</u></a></li>
<li><a href="https://windows11.techidaily.com/unchained-gpt-on-your-machine-using-freedomgpt/"><u>Unchained GPT on Your Machine: Using FreedomGPT</u></a></li>
<li><a href="https://windows11.techidaily.com/what-are-windows-bsod-memory-dumps-and-how-can-they-help-you/"><u>What Are Windows BSoD Memory Dumps, and How Can They Help You?</u></a></li>
</ul></div>
