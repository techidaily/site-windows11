---
title: Preventing Constant Display of Edge Buttons
date: 2024-09-09T11:58:54.034Z
updated: 2024-09-10T11:58:54.034Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Preventing Constant Display of Edge Buttons
excerpt: This Article Describes Preventing Constant Display of Edge Buttons
keywords: Edge Button Prevention,No Edge Buttons,Stop Edges Display,Eliminate Bottom Corners,Hide UI Edges,Remove Screen Fringe,Avoid Extra Margins
thumbnail: https://thmb.techidaily.com/1a08c8dedd48664d90b507bda304483e40c9a1d2dac0696255a8394fc453f16e.jpg
---

<!-- affiliate ads begin -->
<span id="1834906">
					<video width="864" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1834906.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16836-1834906">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1834906.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2F25home.pxf.io%2Fc%2F5597632%2F1834906%2F16836'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1834906/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Preventing Constant Display of Edge Buttons

 Does Windows keep showing the Microsoft Edge shortcut on your desktop even after you delete it? Don’t worry, your computer hasn't been compromised. Several users have shared their experiences of Windows automatically generating the Edge shortcut after a system restart or update.

 Fortunately, there's no requirement to manually delete the Edge desktop shortcut repeatedly. Here are some helpful tips that should help resolve the issue in no time.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139118/17108" target="_top" id="2139118">
  <img src="//a.impactradius-go.com/display-ad/17108-2139118" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139118/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Prevent Microsoft Edge From Opening at Startup

 By default, Microsoft Edge runs every time you start your Windows computer. Several users on the Microsoft forums reported fixing this particular issue by preventing Microsoft Edge from opening at startup. Hence, it’s the first thing you should try.

 You can use Task Manager to review all the apps that are configured to run at boot and disable Edge from there. Here are the steps you can follow:

1. Press **Win + X** to open the Power User menu.
2. Select **Task Manager** from the resulting menu.
3. Select **Startup apps** from the left pane.
4. Locate and select **Microsoft Edge** on the list. Right-click on it and select **Disabled** from the context menu.  
![Startup Apps in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Startup-Apps-in-Task-Manager.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137221/26400" target="_top" id="2137221">
  <img src="//a.impactradius-go.com/display-ad/26400-2137221" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137221/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137222/26400" target="_top" id="2137222">
  <img src="//a.impactradius-go.com/display-ad/26400-2137222" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137222/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134503/19576" target="_top" id="2134503">
  <img src="//a.impactradius-go.com/display-ad/19576-2134503" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134503/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134241/18498" target="_top" id="2134241">
  <img src="//a.impactradius-go.com/display-ad/18498-2134241" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134241/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Further, you can [restrict others from creating and running tasks in the Task Scheduler app](https://www.makeuseof.com/windows-block-task-manager/) by modifying the group policy settings or the registry files.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130886/7443" target="_top" id="2130886">
  <img src="//a.impactradius-go.com/display-ad/7443-2130886" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130886/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 7\. Uninstall Microsoft Edge From Your PC

 If none of the above tips help, you can consider uninstalling Microsoft Edge to fix the problem. This can be useful if Microsoft Edge isn’t your preferred browser anyway.

 Use Command Prompt or PowerShell to [uninstall Microsoft Edge from your Windows computer](https://www.makeuseof.com/windows-11-uninstall-microsoft-edge/). Once you remove the browser, the issue should be resolved.

## Prevent Microsoft Edge From Appearing on Your Desktop

 It can be confusing if Microsoft Edge’s shortcut keeps appearing on your desktop for no apparent reason. Hopefully, one of the above-mentioned fixes has helped fix the issue for good, and you are at peace.

 Does your Windows desktop look like a jumbled mess? If so, you can easily organize it by grouping desktop shortcut icons with a third-party program.

 Fortunately, there's no requirement to manually delete the Edge desktop shortcut repeatedly. Here are some helpful tips that should help resolve the issue in no time.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-churning-charts-todays-1-backdrop-music-for-youtube-shorts/"><u>[Updated] 2024 Approved Churning Charts Today's #1 Backdrop Music for YouTube Shorts</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-in-2024-deciphering-and-dodging-tiktoks-hidden-rules/"><u>[Updated] In 2024, Deciphering and Dodging TikTok's Hidden Rules</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-ultimate-exploration-inside-xcreative-media-suite/"><u>2024 Approved The Ultimate Exploration Inside XCreative Media Suite</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-uninstall-tactics-for-windows-11-os-108-chars/"><u>Essential Uninstall Tactics for Windows 11 OS (108 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/get-up-to-speed-on-windows-11s-user-friendly-taskbar-search-feature/"><u>Get up to Speed on Windows 11’S User-Friendly Taskbar Search Feature</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/gpu-excellence-in-4k-gameplay-experience-for-2024/"><u>GPU Excellence in 4K Gameplay Experience for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-microsoft-store-error-code-0x00000000-in-windows-11-and-11/"><u>How to Fix the Microsoft Store Error Code 0X00000000 in Windows 11 & 11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-realme-12-pro-5g-bootloader-easily-by-drfone-android/"><u>How to Unlock Realme 12 Pro 5G Bootloader Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-window-11-search-bar-camouflage/"><u>Mastering the Art of Window 11 Search Bar Camouflage</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-process-of-fixing-disabled-hard-drive-on-your-windows-11-pc/"><u>Mastering the Process of Fixing Disabled Hard Drive on Your Windows 11 PC</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-window-11-stealthy-hiding-of-linguistic-signal/"><u>Mastering Window 11: Stealthy Hiding of Linguistic Signal</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-security-pin-fix-strategies/"><u>Mastering Windows Security: PIN Fix Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/perfecting-papyrus-best-note-taking-tabs-in-windows/"><u>Perfecting Papyrus: Best Note-Taking Tabs in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/personalize-window-11s-system-monitor-screen/"><u>Personalize Window 11'S System Monitor Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-access-to-windows-photos-functions-via-shortcuts/"><u>Quick Access to Windows Photos Functions via Shortcuts</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-to-turn-off-windows-11-notifies/"><u>Quick Guide to Turn Off Windows 11 Notifies</u></a></li>
<li><a href="https://windows11.techidaily.com/rapid-dns-flush-techniques-for-win11-devices/"><u>Rapid DNS Flush Techniques for Win11 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/redefining-innovation-in-windows-with-enhancements/"><u>Redefining Innovation in Windows with Enhancements</u></a></li>
<li><a href="https://windows11.techidaily.com/reigniting-disappearing-windows-on-your-screen-top-6-fixes-for-win11/"><u>Reigniting Disappearing Windows on Your Screen: Top 6 Fixes for Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/reinvigorating-deactivated-alerts-of-phone-link-app-in-windows/"><u>Reinvigorating Deactivated Alerts of Phone Link App in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-not-available-status-codes-in-windows-os/"><u>Resolving 'Not Available' Status Codes in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/slash-clutter-not-performance-unnecessary-windows-applications-you-can-delete/"><u>Slash Clutter, Not Performance: Unnecessary Windows Applications You Can Delete</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-to-unlocking-windows-11-desktop-toolbar/"><u>Step-by-Step to Unlocking Windows 11 Desktop Toolbar</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-counteract-error-x80300024-in-winxp/"><u>Steps to Counteract Error X80300024 in WinXP</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-tackle-corrupted-files-and-directories-win10-11-edition/"><u>Strategies to Tackle 'Corrupted' Files & Directories: Win10-11 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/taking-control-a-comprehensive-guide-to-touchpad-adjustment-on-windows-11/"><u>Taking Control: A Comprehensive Guide to Touchpad Adjustment on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-harnessing-powertoys-10-must-knows/"><u>The Ultimate Guide to Harnessing PowerToys' 10 Must-Knows</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-5-car-locator-apps-for-tecno-spark-10-5g-drfone-by-drfone-virtual-android/"><u>Top 5 Car Locator Apps for Tecno Spark 10 5G | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/top-6-frequent-challenges-during-agv-setup-and-easy-fix-solutions/"><u>Top 6 Frequent Challenges During AGV Setup & Easy Fix Solutions</u></a></li>
<li><a href="https://os-tips.techidaily.com/troubleshooting-steps-when-icloud-backup-fails-to-initialize/"><u>Troubleshooting Steps When iCloud Backup Fails to Initialize</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-resolving-winrars-sum-verification-failures/"><u>Troubleshooting: Resolving WinRAR's Sum Verification Failures</u></a></li>
<li><a href="https://sound-issues.techidaily.com/ultimate-2024-guide-resolving-sound-synchronization-issues/"><u>Ultimate 2024 Guide: Resolving Sound Synchronization Issues</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unlock-the-potential-of-claude-3/"><u>Unlock the Potential of Claude 3</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-secure-access-a-comprehensive-look-at-fixes-for-key-errors-in-win11/"><u>Unlocking Secure Access: A Comprehensive Look at Fixes for Key Errors in Win11</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/unveiling-performance-excellence-review-of-apples-2020-arm-powered-mac-mini-outshining-competitors/"><u>Unveiling Performance Excellence: Review of Apple's 2020 ARM-Powered Mac Mini Outshining Competitors</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-design-faux-pas-a-list-of-7/"><u>Windows 11'S Design Faux Pas: A List of 7</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>