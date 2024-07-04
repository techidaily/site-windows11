---
title: "Early Bird Benefits: Automatic Open of Windows' Sticky Notes"
date: 2024-06-25T11:58:18.042Z
updated: 2024-06-26T11:58:18.042Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Early Bird Benefits: Automatic Open of Windows' Sticky Notes"
excerpt: "This Article Describes Early Bird Benefits: Automatic Open of Windows' Sticky Notes"
keywords: Early Bird Tips,Sticky Notes Advantage,Quick Access Notebooks,Morning Alerts Efficiency,Timely Note Opening,Speed Reading Saves Time,Priority Content View
thumbnail: https://thmb.techidaily.com/693eb80266e384166dbf5061df1490b93fef1d7413beecc32c81165ba97ad08f.jpg
---

## Early Bird Benefits: Automatic Open of Windows' Sticky Notes

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
<li><a href="https://windows11.techidaily.com/windows-1011-auto-cleanup-a-step-by-step-guide/"><u>Windows 10/11 Auto-Cleanup: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/change-to-dark-theme-in-the-windows-calculator/"><u>Change to Dark Theme in the Windows Calculator</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-swiftly-handle-stalled-gpsvc-process/"><u>How to Swiftly Handle Stalled GPSVC Process</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-your-workflow-keep-gmail-pinned-for-easy-viewing/"><u>Optimize Your Workflow: Keep Gmail Pinned for Easy Viewing</u></a></li>
<li><a href="https://windows11.techidaily.com/enforcing-originality-windows-screensaver-non-alterability/"><u>Enforcing Originality: Windows Screensaver Non-Alterability</u></a></li>
<li><a href="https://windows11.techidaily.com/breakdown-of-windows-11s-enhancements-february-update-speaks/"><u>Breakdown of Windows 11'S Enhancements – February Update Speaks</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-your-pcs-potential-with-a-windows-11-in-place-step-by-step-guide/"><u>Elevating Your PC's Potential with a Windows 11, In-Place Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-google-chrome-to-full-color-in-windows/"><u>Restoring Google Chrome to Full Color in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-impact-of-copilot-key-on-your-windows-11-pc-performance/"><u>Deciphering the Impact of Copilot Key on Your Windows 11 PC Performance</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-choose-wisely-the-ultimate-list-of-mac-gif-tools/"><u>In 2024, Choose Wisely  The Ultimate List of Mac GIF Tools</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-troubleshooting-why-arent-your-recommended-fb-videos-displayed/"><u>In 2024, Troubleshooting  Why Aren't Your Recommended FB Videos Displayed?</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-infinix-hot-30i-drfone-by-drfone-virtual-android/"><u>Here Are Some Reliable Ways to Get Pokemon Go Friend Codes For Infinix Hot 30i | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-gastronomy-goals-attractive-food-network-branding-ideas-for-2024/"><u>[New] Gastronomy Goals  Attractive Food Network Branding Ideas for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-netflix-location-to-get-more-country-version-on-samsung-galaxy-a14-4g-drfone-by-drfone-virtual-android/"><u>How to Change Netflix Location to Get More Country Version On Samsung Galaxy A14 4G | Dr.fone</u></a></li>
<li><a href="https://article-helps.techidaily.com/mastering-youtube-to-mp4-the-ultimate-guide-for-2024/"><u>Mastering YouTube to MP4  The Ultimate Guide for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-perfect-places-to-procure-pixel-ringers-online/"><u>In 2024, Perfect Places to Procure Pixel Ringers Online</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-capturing-beats-studio-mac-basics/"><u>[New] In 2024, Capturing Beats  Studio Mac Basics</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-immediate-audience-monitoring-tools/"><u>2024 Approved  Immediate Audience Monitoring Tools</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-segment-screen-showdown-recorders-leader-status/"><u>[New] In 2024, Segment Screen Showdown  Recorder's Leader Status</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>