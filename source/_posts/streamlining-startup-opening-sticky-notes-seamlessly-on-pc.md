---
title: "Streamlining Startup: Opening Sticky Notes Seamlessly on PC"
date: 2024-06-25T12:06:58.905Z
updated: 2024-06-26T12:06:58.905Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Streamlining Startup: Opening Sticky Notes Seamlessly on PC"
excerpt: "This Article Describes Streamlining Startup: Opening Sticky Notes Seamlessly on PC"
keywords: Startup Efficiency Tips,Note-Taking Software Guide,Streamlined Workflows,Quick Access Notes,Productivity Tools,PC Sticky Note Apps,Simplified Note Management
thumbnail: https://thmb.techidaily.com/cb2689090616a1ba21a99aa6be50929e603a0dc8061abd47262715b07e4d29cd.jpg
---

## Streamlining Startup: Opening Sticky Notes Seamlessly on PC

 Are you tired of opening Sticky Notes every time you turn on your computer? What if it could open automatically each time Windows starts?

 Well, there's good news for you: Sticky Notes can launch at startup in Windows. This article illustrates how to set up and use Sticky Notes at startup.

## 1\. Keep Sticky Notes Open at Shutdown

 When you're done working with Sticky Notes, make sure not to close the window. Instead, leave it open as you shut down your computer. This will ensure that when you turn on your computer, Sticky Notes opens automatically.

 Although the solution is simple, it may not work, or you may find it difficult to remember to keep it open when you turn off your PC. In that case, there are other alternatives; add Sticky Notes to the startup folder or use Task Scheduler.

## 2\. Add Sticky Notes to the Startup Folder

 If you don't want to keep Sticky Notes open at shutdown, you can add it to the startup folder. The Startup folder is a special directory in File Explorer. It stores applications that launch automatically when Windows starts.

 To add Sticky Notes to the Startup folder, follow these steps.

1. Press **Win + R** and type **shell:startup** in the Run dialog.
2. Click **OK** or press Enter. This opens a folder containing all the applications that launch at startup.
3. Press **Windows** to open the Start menu, then click **All apps**. Now scroll down and find **Sticky Notes** in the list.
4. Drag and drop **Sticky Notes** into the Startup folder.

 After performing these steps, close File Explorer and restart your computer. Sticky Notes should now open at startup.

## 3\. Use the Task Scheduler

 Task Scheduler is another way to open Sticky Notes at startup. This Windows feature schedules and automates tasks at specific times or conditions.

 To add Sticky Notes using this tool, follow these steps:

1. [Open Task Scheduler](https://www.makeuseof.com/windows-11-open-task-scheduler/).
2. Click **Create Basic Task** from the **Actions** panel on the right. This opens a wizard that guides you through the setup.  
![Create Basic Task in Task Scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-basic-task-in-task-scheduler.jpg)
3. In the first step, give your task a name and click **Next**.  
![Startup Sticky Notes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/startup-sticky-notes.jpg)
4. Now select **When I log on** as the trigger and click **Next** at the bottom.  
![Create Basic Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-basic-task-wizard.jpg)
5. Choose **Start a program** in the Action window and click **Next**.  
![Start a program in Action tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-a-program-in-action-tab.jpg)
6. In the **Program/script** field, type the path below:  
C:\Windows\System32\cmd.exe
7. In the Add arguments (optional) field, copy and paste the following command:  
/c start shell:appsfolder\Microsoft.MicrosoftStickyNotes_8wekyb3d8bbwe!App  
![Start a Program in Task Scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-a-program-in-task-scheduler.jpg)
8. Click **Next** and review all the settings.
9. Now click **Finish** to save your work.  
![Finish Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/finish-task-wizard.jpg)

 The Task Scheduler will now run Sticky Notes each time you log in. This way, Sticky Notes launches automatically at startup.

## 4\. Tweak the Registry Editor

 If you're comfortable editing the Windows registry, you can tweak it to open Sticky Notes at startup. This method requires knowledge of how the Registry Editor works and caution when editing it. If done incorrectly, it can cause serious system errors. It's best to [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing anything.

 To open Sticky Notes at startup using the Registry Editor, follow these steps:

1. [Open Windows Search](https://www.makeuseof.com/windows-search-use-guide/).
2. Type **regedit** in the search bar and click on the Registry Editor option.
3. If the UAC dialog appears, click **Yes** to grant access.
4. In the Registry Editor window, navigate to the following path:  
Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\PenWorkspace\Notes
5. Double-click the **LaunchOnNextUserSession** key on the right.  
![Tweak Registry Editor to Open Sticky Notes at Startup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tweak-registry-editor-to-open-sticky-notes-at-startup.jpg)
6. Change the Value data from 0 to **1** in the Edit DWORD (32-bit) Value window and click **OK**.  
 If you can't find the **LaunchOnNextUserSession** key, right-click on the **Notes** folder and select **New > DWORD (32-bit) Value**. Name the newly created key “LaunchOnNextUserSession” and assign it the Value data of **1**.
7. Close the Registry Editor and restart your computer to save the changes. Sticky Notes should now open at startup.

## Windows Now Starts With Sticky Notes Open

 This article outlines several ways to open Sticky Notes at startup in Windows. If you want an easier solution, leave Sticky Notes open when you shut down your computer; it will launch automatically when Windows starts. If not, add Sticky Notes to the startup folder. If you want more control over when Sticky Notes launches, use Task Scheduler or tweak the Registry Editor.

 Well, there's good news for you: Sticky Notes can launch at startup in Windows. This article illustrates how to set up and use Sticky Notes at startup.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/remedying-absence-of-display-in-boot-process/"><u>Remedying Absence of Display in Boot Process</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-printer-sharing-challenges-in-windows/"><u>Navigating Printer Sharing Challenges in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/choosing-a-fresh-pdf-file-reader-for-os-use/"><u>Choosing a Fresh PDF File Reader for OS Use</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-prevalent-anydesk-errors-in-windows/"><u>Decoding Prevalent AnyDesk Errors in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-bt-speakers-volume-level-on-windows-11-pcs/"><u>Optimizing BT Speakers Volume Level on Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-solutions-for-correction-of-network-security-discrepancy-in-windows-11/"><u>Top 5 Solutions for Correction of Network Security Discrepancy in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-visibility-of-missing-cameras-on-device-management-screen/"><u>Enhance Visibility of Missing Cameras on Device Management Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaim-default-speaker-levels-post-windows-update/"><u>Reclaim Default Speaker Levels Post-Windows Update</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-productivity-choosing-terminal-as-primary-command-line-interface/"><u>Enhancing Productivity: Choosing Terminal as Primary Command Line Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-elevate-pre-windows-upgrade-machines-into-win11/"><u>How to Elevate Pre-Windows Upgrade Machines Into Win11</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-breakdown-of-steps-perfecting-idevice-video-features-on-youtube/"><u>2024 Approved  Breakdown of Steps  Perfecting iDevice Video Features on YouTube</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-easy-steps-to-change-fins-sounds-in-windows-for-2024/"><u>[Updated] Easy Steps to Change Fins' Sounds in Windows for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-unleash-the-past-sharing-snaps-from-your-camera-roll/"><u>In 2024, Unleash the Past - Sharing Snaps From Your Camera Roll</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-understanding-and-utilizing-facebooks-updated-marketing-techniques/"><u>[New] In 2024, Understanding & Utilizing Facebook’s Updated Marketing Techniques</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-navigating-final-cut-pro-with-ease-an-insiders-guide-for-2024/"><u>[Updated] Navigating Final Cut Pro with Ease  An Insider's Guide for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-comprehensive-tutorial-adding-timer-functionality-to-obs/"><u>[Updated] 2024 Approved  Comprehensive Tutorial  Adding Timer Functionality to OBS</u></a></li>
<li><a href="https://activate-lock.techidaily.com/new-multiple-ways-how-to-remove-icloud-activation-lock-from-your-iphone-15-pro-by-drfone-ios/"><u>New Multiple Ways How To Remove iCloud Activation Lock From your iPhone 15 Pro</u></a></li>
<li><a href="https://android-location-track.techidaily.com/best-anti-tracker-software-for-tecno-pop-7-pro-drfone-by-drfone-virtual-android/"><u>Best Anti Tracker Software For Tecno Pop 7 Pro | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-7-top-ways-to-resolve-apple-id-not-active-issue-for-iphone-se-2020-drfone-by-drfone-ios/"><u>In 2024, 7 Top Ways To Resolve Apple ID Not Active Issue For iPhone SE (2020) | Dr.fone</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/in-2024-the-ultimate-guide-to-split-screen-video-apps-for-mobile/"><u>In 2024, The Ultimate Guide to Split Screen Video Apps for Mobile</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>