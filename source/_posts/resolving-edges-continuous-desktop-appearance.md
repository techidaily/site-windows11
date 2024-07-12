---
title: Resolving Edges' Continuous Desktop Appearance
date: 2024-07-11T21:30:00.572Z
updated: 2024-07-12T21:30:00.572Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving Edges' Continuous Desktop Appearance
excerpt: This Article Describes Resolving Edges' Continuous Desktop Appearance
keywords: EdgeDeskAppearance,ResolveDesktopEdge,UniformEdgeDisplay,ConsistentDesktopView,EdgeContinuityFix,AppearanceControlUI,DesktopEdgeUniformity
thumbnail: https://thmb.techidaily.com/c7c73b7c4a7efc6c835802b5aee6775aac1b5aafcbc08ea28ac48bf90c458f91.jpg
---

## Resolving Edges' Continuous Desktop Appearance

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
<li><a href="https://windows11.techidaily.com/boost-mouse-click-agility-nine-strategies-to-tweak-speeds/"><u>Boost Mouse Click Agility: Nine Strategies to Tweak Speeds</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-new-era-of-filesystems-windows-11s-innovations/"><u>Navigating the New Era of Filesystems: Windows 11'S Innovations</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-realme-note-50-by-drfone-android/"><u>In 2024, Complete Review & Guide to Techeligible FRP Bypass and More For Realme Note 50</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-to-overcome-windows-code-error/"><u>Essential Tips to Overcome Window's Code Error</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-windows-11-performance-run-command-upgrade-guide/"><u>Boosting Windows 11 Performance: Run Command Upgrade Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/creating-a-dual-disk-on-windows-independently/"><u>Creating a Dual Disk on Windows, Independently</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-screen-mirroring-apple-iphone-14-plus-to-tv-or-pc-drfone-by-drfone-ios/"><u>In 2024, How Screen Mirroring Apple iPhone 14 Plus to TV or PC? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-windowed-discord-for-flawless-search-experience/"><u>Optimizing Windowed Discord for Flawless Search Experience</u></a></li>
<li><a href="https://vp-tips.techidaily.com/audio-endings-how-to-decrease-volume-gradually-in-pp-for-2024/"><u>Audio Endings  How to Decrease Volume Gradually in PP for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-offscreen-windows-errors/"><u>Addressing Offscreen Windows Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-art-of-elevating-notetaking-on-windows/"><u>Master the Art of Elevating Notetaking on Windows</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-t-open-mov-files-on-xiaomi-redmi-13c-5g-by-aiseesoft-video-converter-play-mov-on-android/"><u>Can't open MOV files on Xiaomi Redmi 13C 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-capabilities-directories-with-a-click-in-win11/"><u>Crafting Capabilities: Directories with a Click in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-classics-to-full-hd-perfection-with-windows-and-scummvm-expertise/"><u>Elevate Classics to Full HD Perfection with Windows & ScummVM Expertise</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-erase-an-iphone-13-pro-without-apple-id-password-by-drfone-ios/"><u>In 2024, How To Erase an iPhone 13 Pro Without Apple ID Password?</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-steam-library-synchronization-hitches/"><u>Navigating Through Steam Library Synchronization Hitches</u></a></li>
<li><a href="https://windows11.techidaily.com/craft-compelling-content-with-these-windows-tools/"><u>Craft Compelling Content with These Window's Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-high-cpu-usage-techniques-from-windows-resource-monitor/"><u>Decoding High CPU Usage: Techniques From Windows Resource Monitor</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-winos-stop-autominize-apps/"><u>Boosting WinOS: Stop Autominize Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-file-system-in-windows-unveiled-max-156/"><u>Effective File System in Windows Unveiled (Max 156)</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-mastering-your-influence-amidst-changing-social-media-ecosystem-for-2024/"><u>[New] Mastering Your Influence Amidst Changing Social Media Ecosystem for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-unleash-creativity-in-windows-10-how-to-trim-movies-and-more/"><u>2024 Approved  Unleash Creativity in Windows 10  How To Trim Movies and More</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-steps-to-create-a-personalized-windows-text-recognition-program/"><u>Easy Steps to Create a Personalized Windows Text Recognition Program</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-methods-to-mirror-xiaomi-redmi-a2plus-to-roku-drfone-by-drfone-android/"><u>In 2024, 3 Methods to Mirror Xiaomi Redmi A2+ to Roku | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-run-adobe-ps-in-windows-without-trouble-or-failure/"><u>How to Run Adobe PS in Windows without Trouble or Failure</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-increase-disk-size-in-windows-carefully/"><u>How to Increase Disk Size in Windows Carefully</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-keep-the-calculator-always-on-top-on-windows/"><u>How to Keep the Calculator Always on Top on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/integrating-google-play-store-into-win11-os/"><u>Integrating Google Play Store Into Win11 OS</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-2024-approved-seamless-tweet-integration-on-facebook-platform/"><u>[Updated] 2024 Approved  Seamless Tweet Integration on Facebook Platform</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-nokia-c12-phone-with-broken-screen-by-drfone-android/"><u>In 2024, How to Unlock Nokia C12 Phone with Broken Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/halt-spotifys-autoplay-behavior-on-pc/"><u>Halt Spotify's Autoplay Behavior on PC</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-reasons-why-pokemon-gps-does-not-work-on-apple-iphone-13-pro-max-drfone-by-drfone-virtual-ios/"><u>In 2024, Reasons why Pokémon GPS does not Work On Apple iPhone 13 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/convenient-methods-for-local-policies-on-windows-11/"><u>Convenient Methods for Local Policies on Windows 11</u></a></li>
<li><a href="https://article-files.techidaily.com/simplified-techniques-for-blurring-faces-in-pictures-for-2024/"><u>Simplified Techniques for Blurring Faces in Pictures for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/edging-into-the-non-edge-process-quagmire/"><u>Edging Into the Non-Edge Process Quagmire</u></a></li>
</ul></div>
