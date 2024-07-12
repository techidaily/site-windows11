---
title: "Boosting Sync: Launch Sticky Notes with Windows Start-Up"
date: 2024-07-11T22:19:09.186Z
updated: 2024-07-12T22:19:09.186Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Boosting Sync: Launch Sticky Notes with Windows Start-Up"
excerpt: "This Article Describes Boosting Sync: Launch Sticky Notes with Windows Start-Up"
keywords: Sync Windows Start-Up,Sticky Notes Launch,Boost Startup Speed,Sync Windows Apps,Quick Start Windows,Notebook Launch Tool,Fast System Boot
thumbnail: https://thmb.techidaily.com/468b7a50fb837089e10cec38dd44fa01aaab4078b704b313fd2f69558ac117bb.png
---

## Boosting Sync: Launch Sticky Notes with Windows Start-Up

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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://sim-unlock.techidaily.com/in-2024-tutorial-to-change-vivo-y200-imei-without-root-a-comprehensive-guide-by-drfone-android/"><u>In 2024, Tutorial to Change Vivo Y200 IMEI without Root A Comprehensive Guide</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-exploring-mobile-youtube-usage-on-different-oses/"><u>2024 Approved  Exploring Mobile YouTube Usage on Different OSes</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-motorola-edge-40-to-mac-drfone-by-drfone-android/"><u>In 2024, How to Mirror Motorola Edge 40 to Mac? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tracker-tools-the-ultimate-6-list-for-windows-users/"><u>Essential Tracker Tools: The Ultimate 6 List For Windows Users</u></a></li>
<li><a href="https://extra-hints.techidaily.com/strengthen-virtual-communication-overcoming-audio-distortion/"><u>Strengthen Virtual Communication  Overcoming Audio Distortion</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-crafting-chorus-in-a-click-essential-insights-into-shortform-song-videos/"><u>[New] Crafting Chorus in a Click  Essential Insights Into Shortform Song Videos</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-navigating-the-maze-of-youtube-endorsements-with-a-famebit-perspective/"><u>2024 Approved  Navigating the Maze of YouTube Endorsements with a FameBit Perspective</u></a></li>
<li><a href="https://windows11.techidaily.com/easily-identify-last-opened-files-in-windows-explorer/"><u>Easily Identify Last Opened Files in Windows Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/unbroken-streams-winos-stability-verification-guide/"><u>Unbroken Streams: WinOS Stability Verification Guide</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-dissective-review-of-sharex-criticism-and-substitutes/"><u>In 2024, Dissective Review of ShareX  Criticism & Substitutes</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-2024-approved-top-3d-video-creation-tools-you-need-to-try/"><u>New 2024 Approved Top 3D Video Creation Tools You Need to Try</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-virtual-fraud-tips-for-discerning-true-windows-apps/"><u>Avoid Virtual Fraud: Tips for Discerning True Windows Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-failed-application-launches-windows-11s-error-0xc000003e-explained/"><u>Correcting Failed Application Launches: Windows 11'S Error 0XC000003E Explained</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-2024-approved-guiding-imovie-content-from-home-studio-to-youtube-hub/"><u>[Updated] 2024 Approved  Guiding iMovie Content From Home Studio to YouTube Hub</u></a></li>
<li><a href="https://windows11.techidaily.com/10-command-prompt-wonders-you-didnt-know/"><u>10 Command Prompt Wonders You Didn’t Know!</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-the-absence-of-drive-letters-in-windows-environments/"><u>Dissecting the Absence of Drive Letters in Windows Environments</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-7-essential-secrets-for-delectable-cooking-clips/"><u>[New] 7 Essential Secrets for Delectable Cooking Clips</u></a></li>
<li><a href="https://windows11.techidaily.com/a-guide-to-direct-access-for-the-curious-explorer-in-windows-11/"><u>A Guide to Direct Access for the Curious Explorer in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/vanishing-acts-concealing-keys-without-notice/"><u>Vanishing Acts: Concealing Keys Without Notice</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-common-issues-for-intel-unison-on-windows-11/"><u>Fixing Common Issues for Intel Unison on Windows 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-unlock-your-samsung-galaxy-m34-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>In 2024, Unlock Your Samsung Galaxy M34 Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-virtual-potential-hyper-v-for-windows-11-users/"><u>Unlocking Virtual Potential: Hyper-V for Windows 11 Users</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-clear-video-borders-streamline-webcam-footage/"><u>[New] In 2024, Clear Video Borders  Streamline Webcam Footage</u></a></li>
<li><a href="https://windows11.techidaily.com/ensure-seamless-fullscreen-launch-on-windows-pcs/"><u>Ensure Seamless Fullscreen Launch on Windows PCs</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-streamlined-scheduling-making-the-most-of-zoom-calls/"><u>[Updated] 2024 Approved  Streamlined Scheduling  Making the Most of Zoom Calls</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-advice-overcoming-printer-error-0xfffffff/"><u>Expert Advice: Overcoming Printer Error 0xFFFFFFF</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/macbook-cam-recording-tutorial/"><u>MacBook Cam Recording Tutorial</u></a></li>
<li><a href="https://windows11.techidaily.com/when-windows-acts-up-reboot-or-reset/"><u>When Windows Acts Up, Reboot or Reset?</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-your-windows-onedrive-hurdles-now/"><u>Fix Your Windows OneDrive Hurdles Now</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-resource-scheduling-for-android-on-windows-wsl/"><u>Efficient Resource Scheduling for Android on Windows WSL</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-win11-potential-essential-commands-and-tricks-with-nircmd/"><u>Unlock Win11 Potential: Essential Commands & Tricks with NirCmd</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-differences-how-exe-files-function-compared-to-msi/"><u>Dissecting Differences: How Exe Files Function Compared to Msi</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-developers-rejoice-unveiling-microsoft-copilot/"><u>Windows Developers Rejoice: Unveiling Microsoft Copilot</u></a></li>
<li><a href="https://windows11.techidaily.com/unblock-windows-task-scheduler-issues-quickly/"><u>Unblock Windows Task Scheduler Issues Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-solving-microsoft-offices-0x80041015/"><u>Understanding & Solving Microsoft Office's 0X80041015</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/how-to-leverage-slug-lines-in-articles-for-2024/"><u>How to Leverage Slug Lines in Articles for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-bypass-android-lock-screen-using-emergency-call-on-oppo-a1x-5g-by-drfone-android/"><u>How to Bypass Android Lock Screen Using Emergency Call On Oppo A1x 5G?</u></a></li>
<li><a href="https://extra-support.techidaily.com/5-best-podcast-visualizers-for-podcasts-updated-for-2024/"><u>5 Best Podcast Visualizers for Podcasts (Updated) for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-deal-with-the-honor-x8b-screen-black-but-still-works-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Deal With the Honor X8b Screen Black But Still Works? | Dr.fone</u></a></li>
</ul></div>
