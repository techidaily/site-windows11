---
title: Fixing Inaccessible Files on Windows Platform
date: 2024-07-11T21:28:40.263Z
updated: 2024-07-12T21:28:40.263Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Inaccessible Files on Windows Platform
excerpt: This Article Describes Fixing Inaccessible Files on Windows Platform
keywords: Windows File Accessibility,Overcoming File Errors,Resolving Win Errors,Enhancing File Usability,Fixing OS File Issues,Improving File Integrity,Streamlining File Functionality
thumbnail: https://thmb.techidaily.com/c9b8fd1733901244b30160c420a56660fbc28694609982153cd6de4dd43a450d.jpg
---

## Fixing Inaccessible Files on Windows Platform

 Are you encountering the "Windows cannot access the specified device, path, or file." error on Windows 10 or 11? This issue usually appears when you try to run an EXE application or open a document. When this error happens, you can't run some programs or access some documents, limiting your computer's usefulness.

 So, how do you solve the "cannot access the specified device" error? Check out some of the troubleshooting steps you can take below.

## 1\. Run the App as an Administrator

 Some programs, for a variety of reasons, need administrator privileges to perform specific tasks. In fact in certain situations, you might not be able to open them either.

 In your case, the "Windows Cannot Access the Specified Device, Path or File” error might be the result of this error as well. So if you are looking to fix this error, running it as an administrator will be your best bet. Here’s how you can get started:

1. Right-click on the app you want to run.
2. From the context menu, select **Run as administrator**.

 If the issue was the lack of administrator privileges, your app will run by the end of these steps.

## 2\. Disable Potentially Unwanted App Blocking

 Unwanted app blocking is a [Windows Security](https://www.makeuseof.com/windows-11-quick-security-guide/) feature that prevents low-reputation apps and software from running. That feature can cause the "cannot access the specified device" error when enabled. You can check if unwanted app blocking is enabled and disable it as follows:

1. Double-click the shield (Windows Security) icon inside the system tray area on the right of the taskbar. You may also need to click a small up arrow on the taskbar to see the system tray icons.
2. Select the **App & browser control** tab in Windows Security.
3. Then click the **Reputation-based protection** **settings** link to view more settings.  
![The Reputation-based protection settings option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reputation-based-settings-option.jpg)
4. Deselect the **Block apps** checkbox if that feature is enabled.  
![The Block apps checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-block-apps-checkbox.jpg)

## 3\. Deselect the "Unblock File" Setting

 Sometimes [Windows blocks access to files or folders](https://www.makeuseof.com/windows-askadmin-guide/) downloaded from untrusted online sources, which can cause the "cannot access the specified device" error. When that happens, you'll see an **Unblock** checkbox on an affected files properties window. This is how you can deselect the "unblock file" setting:

 Make sure that you trust the file's source before doing this. If you unblock an infected file, it can damage your computer and cause file loss.

1. Right-click **Start** (the taskbar button) and select the **File Explorer** option from the menu.  
![The File Explorer shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/file-explorer.jpg)
2. Open a folder that includes a file for which the error occurs.
3. Right-click the affected file and select **Properties**.  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/properties-option.jpg)
4. Click **General** if the properties window doesn't open with that tab by default.
5. Then uncheck the selected **Unblock** checkbox if you can see one.  
![The Unblock checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/unblock-checkbox.jpg)
6. Select **Apply** to save the new file settings.
7. Click **OK** to close the file's properties window.

## 4\. Edit the File's Permissions

 Another cause of the "cannot access the specified device" error message is insufficient file permissions. That's something you can remedy by editing the permissions for affected files. So, try editing an affected file's permissions as follows:

1. Bring up a directory with a file that throws up the "cannot access the specified device" error.
2. Click an affected file with the right mouse button and select its **Properties** option.
3. Select **Security** in the properties window.
4. Then select the Windows user account you signed into.
5. Press the **Edit** button.
6. Select your Windows user account on the permissions window that opens.
7. Deselect (uncheck) all selected **Deny** permission checkboxes.  
![The Deny checkboxes for file permissions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/deny-checkboxes.jpg)
8. Select **Apply** to set the new permission settings.
9. Press the **OK** buttons on all windows.

## 5\. Recreate a Program's Shortcut

 If the "cannot access the specified device" error occurs when you try to run a program shortcut, the issue might lie within the shortcut itself. In this case, setting up a new shortcut for affected software could resolve the issue. This is how to do so on your desktop:

1. Right-click any part of the desktop without overlapping icons to select **New**.
2. Click **Shortcut** to bring up a tool for adding desktop shortcuts.  
![The Shortcut option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/shortcut-option.jpg)
3. Then click **Browse** to select an EXE file the error occurs for and press the **OK** button.  
![The Create Shortcut tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/create-shortcut-window.jpg)
4. Select **Next** and input a shortcut title in the text box.
5. Click **Finish** to add the new program shortcut.
6. Right-click the program's old shortcut to select **Delete** (the trash can button in Windows 11).

## 6\. Double-Check the File's Location

 Do you install software and save some files to an external or network drive? If so, it could be the case that the access error is occurring because a file is on a drive that's not currently accessible.

 Double-check the locations of the files you're trying to run or open by right-clicking desktop shortcuts for them and selecting **Properties**. Then you can check the path for the shortcut in the **Targe**t box shown directly below.

![The Target box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-target-box.jpg)

 That **Target** box will show whether the file is on another drive. If it is, connect the external drive that includes the file to your PC to access it. Double-check that the file specified hasn't been deleted if the **Target** box references the local C: drive. To do that, open the folder path specified in File Explorer.

 Should you discover a shortcut's file has been deleted, you might be able to retrieve it. Open the Recycle Bin to see if the file is in it. If so, right-click the file and select **Restore**.

## 7\. Enable Admin Permissions With the Group Policy Editor

 Users have confirmed enabling admin approval mode in Group Policy Editor can resolve this file access error. However, Group Policy Editor is only available in Windows 11 and 10 Pro and Enterprise editions. If you can utilize Group Policy Editor, try enabling admin approval mode as follows:

1. [Open Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and select **Computer Configuration** in that utility.
2. Double-click **Windows Settings** to expand that configuration category.
3. Then double-click **Security Settings** \> **Local Policies** \> **Security Options** in Group Policy Editor's sidebar.  
![The Local Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/group-policy-editor.jpg)
4. Double-click the **Admin Approval Mode for Built-in Administrator** account policy.
5. Then select the **Enabled** radio button.  
![The Admin Approval Mode policy setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-admin-approval-mode-policy-settings.jpg)
6. Click **Apply** to set the policy.
7. Select **OK** to exit the window for the policy setting and close the Group Policy Manager utility.

## 8\. Set Up a Windows Security Exclusion Affected Software or File

 As Windows Security blocks can cause this error, we recommend users add affected files to that antivirus app's exclusion list. Doing so will exclude the file from Defender's antivirus protection. Check out our guide to [whitelisting files in Microsoft (formerly Windows) Defender](https://www.makeuseof.com/how-to-whitelist-files-windows-defender/) for details about how to apply this potential solution.

![Add an exclusion button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/add-an-exclusion-button.jpg)

## 9\. Temporarily Disable Any Active Third-Party Security Software

 Some third-party antivirus apps share similar app-blocking features to Windows Security. Thus, alternative security software can also feasibly cause the same issue to occur much the same. So, try turning off any third-party antivirus software installed on your PC before attempting to run affected EXE software.

![A laptop computer is seen on a desk during an antivirus scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/manual-antivirus-scan.jpg)

 How exactly you turn off different third-party antivirus apps varies slightly. However, most have context menus from which you can select to disable their shields. Click the system tray icon for your antivirus software with the right mouse button to view its context menu. Then choose an option for disabling its antivirus shield from there.

 Should this potential solution work, you'll know what's causing it. However, don't leave your antivirus software disabled. Add affected files to the security software's exceptions list.

## 10\. Repair or Reinstall the File

 If you are facing this issue due to corruption in the file, then repairing or reinstalling it is your best bet. Using the Control Panel will be your best bet in this case. Here's how you can do it:

1. Head to the **Start menu** search bar, type in 'control panel', and select the best match.
2. From there, head to the **Programs**.
3. Then, select **Programs and Features**.
4. Right-click on any program and select **Uninstall/Change**.

![control panel on windows pc](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/control-panel-on-windows-pc.jpg)

 Depending on the app, you will get an option to either uninstall the app or change its settings. That's it—from there just follow the on-screen instructions, and you will be done in no time. If you installed the app, make sure you get it from a trusted source again and then see if you are facing the same error again.

## Get the "Cannot Access the Specified Device" Error Sorted in Windows 10 and 11

 We don't promise guaranteed solutions, but the potential resolutions here will likely resolve the "cannot access the specified device" error on your PC. Many users have sorted that file access issue out in Windows by applying the above fixes.

 So, how do you solve the "cannot access the specified device" error? Check out some of the troubleshooting steps you can take below.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/sudos-arrival-in-windows-os-explained/"><u>Sudo's Arrival in Windows OS Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/learn-9-keys-to-tweaking-windows-audio-properties/"><u>Learn 9 Keys to Tweaking Windows Audio Properties</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-insta-cover-chronicles-top-tier-tech-edition-for-2024/"><u>[New] Insta Cover Chronicles  Top-Tier Tech Edition for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-failed-capture-issue-in-win11-photoapp/"><u>Overcoming 'Failed Capture' Issue in Win11 PhotoApp</u></a></li>
<li><a href="https://windows11.techidaily.com/reactivating-inputs-post-sleep-on-latest-windows/"><u>Reactivating Inputs Post-Sleep on Latest Windows</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-contacts-from-oppo-reno-11-pro-5g-by-fonelab-android-recover-contacts/"><u>Undelete lost contacts from Oppo Reno 11 Pro 5G.</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-folder-menu-enhancement-with-new-commands-win-11/"><u>Step-by-Step Guide: Folder Menu Enhancement with New Commands (Win 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/nine-pathways-out-of-the-window-11s-0x8004def5-puzzle/"><u>Nine Pathways Out of the Window 11'S 0X8004DEF5 Puzzle</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-expressive-imagery-premier-snapchat-filters-and-lenses/"><u>In 2024, Expressive Imagery  Premier Snapchat Filters and Lenses</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-discover-efficiency-the-top-10-screen-capture-software-for-mac-users/"><u>In 2024, Discover Efficiency  The Top 10 Screen Capture Software for Mac Users</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-and-resolving-outlooks-error-0x80040610/"><u>Navigating Through and Resolving Outlook's Error 0X80040610</u></a></li>
<li><a href="https://windows11.techidaily.com/installation-essentials-intel-network-adapters-for-windows-users/"><u>Installation Essentials: Intel Network Adapters for Windows Users</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/in-2024-a-comprehensive-guide-on-vhs-technology-and-its-influence-on-video-editing/"><u>In 2024, A Comprehensive Guide on VHS Technology and Its Influence on Video Editing</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-deleting-account-info-from-windows-logon/"><u>Steps for Deleting Account Info From Windows Logon</u></a></li>
<li><a href="https://windows11.techidaily.com/pro-tips-for-buying-windows-11-vcs/"><u>Pro Tips for Buying Windows 11 VCs</u></a></li>
<li><a href="https://youtube-data.techidaily.com/our-step-by-step-pathway-to-youtube-video-enhancement/"><u>[New] Your Step-By-Step Pathway to YouTube Video Enhancement</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/the-complete-guide-to-netflix-screen-capture-discover-six-efficient-ways-on-macos/"><u>The Complete Guide to Netflix Screen Capture - Discover Six Efficient Ways on macOS</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unveiling-the-secrets-to-profitable-brands-partnerships-on-youtube-for-2024/"><u>Unveiling the Secrets to Profitable Brands Partnerships on YouTube for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/ftdibussys-and-windows-exploring-the-memory-integrity-dilemshift/"><u>Ftdibus.sys and Windows: Exploring the Memory Integrity Dilemshift</u></a></li>
<li><a href="https://windows11.techidaily.com/proactive-measures-for-sticky-notes-longevity/"><u>Proactive Measures for Sticky Notes' Longevity</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-widgets-to-the-windows-11-desktop/"><u>How to Add Widgets to the Windows 11 Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-challenge-of-0x8007045d-error-on-windows-11/"><u>Overcoming the Challenge of 0X8007045d Error on Windows 11</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-ultimate-guide-on-oppo-reno-11-5g-frp-bypass-by-drfone-android/"><u>In 2024, Ultimate Guide on Oppo Reno 11 5G FRP Bypass</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-15-to-other-iphone-14-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 15 To Other iPhone 14 devices? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-potential-of-windows-11s-configurable-fn-keys/"><u>Mastering the Potential of Windows 11'S Configurable FN Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/nullify-specification-shortfalls-alerts-in-win11/"><u>Nullify Specification Shortfalls Alerts in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-microsoft-teams-instability-on-ws11ws10-devices/"><u>Preventing Microsoft Teams Instability on WS11/WS10 Devices</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-discovering-top-webinar-platforms/"><u>[New] 2024 Approved  Discovering Top Webinar Platforms</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-an-incorrect-cpu-usage-in-the-windows-task-manager/"><u>How to Fix an Incorrect CPU Usage in the Windows Task Manager</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-cutting-edge-community-emblems-motion-showcase/"><u>[Updated] 2024 Approved  Cutting-Edge Community Emblems  Motion Showcase</u></a></li>
<li><a href="https://win11.techidaily.com/systematic-solutions-locating-and-correcting-windows-errors-via-the-power-of-command-prompt/"><u>Systematic Solutions: Locating & Correcting Windows Errors via the Power of Command Prompt</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/harting-the-course-to-youtube-fame-strategic-video-release-frequency/"><u>[New] Charting the Course to YouTube Fame  Strategic Video Release Frequency</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/the-future-of-remote-work-unveiling-the-best-vocal-manipulation-apps-for-google-meet-users/"><u>The Future of Remote Work Unveiling the Best Vocal Manipulation Apps for Google Meet Users</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11s-software-compatibility-tool/"><u>Navigating Windows 11’S Software Compatibility Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/simplified-docx-to-pdf-workflow-in-windows-11-systems/"><u>Simplified DOCX to PDF Workflow in Windows 11 Systems</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-vocal-vanishing-act-how-to-seamlessly-remove-singers-voice-from-an-audio-track-using-audacity-tools-for-2024/"><u>Updated Vocal Vanishing Act How to Seamlessly Remove Singers Voice From an Audio Track Using Audacity Tools for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-essential-adobe-premiere-keyboard-shortcuts-to-boost-productivity/"><u>New In 2024, Essential Adobe Premiere Keyboard Shortcuts to Boost Productivity</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-the-essential-user-manual-for-music-licensing-on-insta-for-2024/"><u>[Updated] The Essential User Manual for Music Licensing on Insta for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/expert-e-learning-title-engineer-for-2024/"><u>Expert E-Learning Title Engineer for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/a-guide-to-30-compelling-video-presentation-ideas/"><u>A Guide to 30 Compelling Video Presentation Ideas</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-page-could-not-be-loaded-error-in-the-microsoft-store-for-windows/"><u>How to Fix the Page Could Not Be Loaded Error in the Microsoft Store for Windows</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ring-desktopmobile-adjust-youtube-video-pace/"><u>Mastering Desktop/Mobile  Adjust YouTube Video Pace</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-youtube-to-mp3-how-to-choose-the-right-converter-for-you/"><u>Updated YouTube to MP3 How to Choose the Right Converter for You</u></a></li>
<li><a href="https://windows11.techidaily.com/find-your-windows-11-backdrops-saving-spot/"><u>Find Your Windows 11 Backdrop's Saving Spot</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/the-top-ten-ways-to-propel-your-tiktok-campaigns-forward-for-2024/"><u>The Top Ten Ways to Propel Your TikTok Campaigns Forward for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-chart-topping-stock-photos-and-their-narratives/"><u>2024 Approved  Chart-Topping Stock Photos and Their Narratives</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-workflow-multitask-with-windows-11-expertise/"><u>Optimizing Workflow: Multitask with Windows 11 Expertise</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-error-xc0000142-with-windows-oses/"><u>Fixing Error XC0000142 with Windows OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/remediation-techniques-for-resource-occupancy-errors-149-chars/"><u>Remediation Techniques for Resource Occupancy Errors (149 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-notebook-interface-with-themes-and-fonts/"><u>Streamline Your Notebook Interface with Themes & Fonts</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-asana-not-working-on-windows/"><u>How to Fix Asana Not Working on Windows</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-crafting-a-story-unique-to-you-amongst-tiktok-titans-for-2024/"><u>[New] Crafting a Story Unique to You Amongst TikTok Titans for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-do-you-remove-restricted-mode-on-iphone-xr-by-drfone-ios/"><u>In 2024, How Do You Remove Restricted Mode on iPhone XR</u></a></li>
<li><a href="https://windows11.techidaily.com/flawless-system-transition-mastering-windows-11s-in-place-update-process/"><u>Flawless System Transition: Mastering Windows 11'S In-Place Update Process</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-group-policy-editor-navigation-windows-11-style/"><u>Mastering Group Policy Editor Navigation, Windows 11 Style</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-your-oneplus-nord-ce-3-5g-location-on-twitter-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change your OnePlus Nord CE 3 5G Location on Twitter | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-from-fading-to-flourishing-top-strategies-for-overcoming-zero-views/"><u>2024 Approved  From Fading to Flourishing  Top Strategies for Overcoming Zero Views</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-dual-monitor-setup-problems/"><u>Resolving Dual Monitor Setup Problems</u></a></li>
</ul></div>
