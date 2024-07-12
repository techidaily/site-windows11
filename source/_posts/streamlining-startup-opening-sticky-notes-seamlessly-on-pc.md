---
title: "Streamlining Startup: Opening Sticky Notes Seamlessly on PC"
date: 2024-07-11T21:24:57.843Z
updated: 2024-07-12T21:24:57.843Z
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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/9-ways-to-fix-mails-notifications-not-working-on-windows/"><u>9 Ways to Fix Mail's Notifications Not Working on Windows</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-mastering-bandicam-key-takeaways-and-tips/"><u>[New] In 2024, Mastering Bandicam - Key Takeaways and Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/4-ways-microsoft-is-replacing-cortana-in-windows/"><u>4 Ways Microsoft Is Replacing Cortana in Windows</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-boost-your-storytelling-on-instagram-with-loops-for-2024/"><u>[Updated] Boost Your Storytelling on Instagram With Loops for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/1719351366052-breathe-new-life-into-your-win11-printer-with-these-tips/"><u>Breathe New Life Into Your Win11 Printer with These Tips!</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-blue-screen-blues-fixing-error-740-on-winos/"><u>Avoiding Blue Screen Blues: Fixing Error 740 on WINOS</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-screen-free-serenity-top-10-indoor-games-for-non-networked-play-android/"><u>[New] 2024 Approved  Screen-Free Serenity  Top 10 Indoor Games for Non-Networked Play (Android)</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-efficiency-with-top-practices-for-wsl-2-usage-on-pcs/"><u>Boost Efficiency with Top Practices for WSL 2 Usage on PCs</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/full-guide-to-bypass-xiaomi-13t-pro-frp-by-drfone-android/"><u>Full Guide to Bypass Xiaomi 13T Pro FRP</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-why-no-video-suggestions-pop-up-in-your-social-media-world/"><u>[New] 2024 Approved  Why No Video Suggestions Pop Up in Your Social Media World?</u></a></li>
<li><a href="https://windows11.techidaily.com/1719314513697-combat-snip-and-sketch-failures-a-guide-to-capturing-entire-display/"><u>Combat Snip & Sketch Failures: A Guide to Capturing Entire Display.</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-2024-approved-streamlining-submission-a-podcasters-guide/"><u>[New] 2024 Approved  Streamlining Submission  A Podcaster's Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-services-that-dont-launch/"><u>Addressing Windows Services That Don't Launch</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-productivity-with-windows-11-strategies/"><u>Boosting Productivity with Windows 11 Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/a-list-of-frustrations-with-windows-11/"><u>A List of Frustrations with Windows 11</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/mini-2-and-air-2s-luts-free-trial-then-paid-upgrade/"><u>Mini 2 & Air 2S LUTS - Free Trial, Then Paid Upgrade</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-performance-of-docker-in-wsl-2-on-windows-devices/"><u>Boosting Performance of Docker in WSL 2 on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/6-expert-windows-programs-for-video-editors/"><u>6 Expert Windows Programs for Video Editors</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-the-right-approach-for-accurate-google-speech-to-text/"><u>[New] In 2024, The Right Approach for Accurate Google Speech-to-Text</u></a></li>
<li><a href="https://windows11.techidaily.com/classic-expanse-a-win-11-explorer-journey/"><u>Classic Expanse: A Win 11 Explorer Journey</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-the-blockade-fixing-obs-studios-server-error-window/"><u>Bypassing the Blockade: Fixing OBS Studio's Server Error Window</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-solutions-to-find-your-vivo-t2x-5g-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>3 Solutions to Find Your Vivo T2x 5G Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/prevent-unwanted-video-captures-in-qt-player/"><u>Prevent Unwanted Video Captures in QT Player</u></a></li>
<li><a href="https://windows11.techidaily.com/5-key-adjustments-for-a-mac-look-in-windows-environment/"><u>5 Key Adjustments for a Mac Look in Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-windows-with-top-2023-ms-store-winners/"><u>Boost Windows with Top 2023 MS Store Winners</u></a></li>
<li><a href="https://windows11.techidaily.com/beginner-friendly-steps-to-install-chrome-on-windows-11/"><u>Beginner-Friendly Steps to Install Chrome on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/bold-windows-11-remove-curved-edges/"><u>Bold Windows 11: Remove Curved Edges</u></a></li>
<li><a href="https://windows11.techidaily.com/add-compatibility-tool-to-windows-quick-access/"><u>Add Compatibility Tool to Windows' Quick Access</u></a></li>
<li><a href="https://windows11.techidaily.com/apexs-windows-woes-strategies-to-clear-no-server-error-(156-chars/"><u>Apex's Windows Woes: Strategies to Clear No-Server Error (<156 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/are-the-icons-on-your-windows-desktop-overlapping-here-are-some-solutions/"><u>Are the Icons on Your Windows Desktop Overlapping? Here Are Some Solutions</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-stream-the-best-beats-on-these-20-top-tier-youtube-music-outlets/"><u>In 2024, Stream the Best Beats on These 20 Top-Tier YouTube Music Outlets</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-premium-mix-picture-taking-plus-sounds-recorder-titles/"><u>[New] Premium Mix  Picture Taking + Sounds Recorder Titles</u></a></li>
<li><a href="https://ai-video.techidaily.com/updated-in-2024-a-complete-guide-of-top-7-video-language-translators/"><u>updated In 2024, A Complete Guide of Top 7 Video Language Translators</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-vscode-shutdown-troubles-in-new-os/"><u>Avoiding VSCode Shutdown Troubles in New OS</u></a></li>
<li><a href="https://android-frp.techidaily.com/top-5-samsung-galaxy-a23-5g-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 Samsung Galaxy A23 5G Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-essential-strategies-for-youtube-and-twitch-via-obs/"><u>2024 Approved  Essential Strategies for YouTube & Twitch via OBS</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-qt-plugin-initialization-failure-error/"><u>Addressing Qt Plugin Initialization Failure Error</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-efficiency-on-pc-best-apps-for-personalized-time-themed-screen-saver-creation/"><u>Boost Efficiency on PC: Best Apps for Personalized Time-Themed Screen Saver Creation</u></a></li>
<li><a href="https://windows11.techidaily.com/beat-windows-timer-troubles-reclaim-control/"><u>Beat Windows Timer Troubles, Reclaim Control</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-disruption-fixing-windows-minecraft-errors/"><u>Avoid Disruption - Fixing Windows Minecraft Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-the-incorrect-identifier-message-in-windows-11/"><u>Addressing the 'Incorrect Identifier' Message in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/amplify-tray-ui-add-scrolllock-and-number-keys-iconos/"><u>Amplify Tray UI: Add ScrollLock and Number Keys Iconos</u></a></li>
<li><a href="https://windows11.techidaily.com/changing-default-user-directory-labels-windows-11/"><u>Changing Default User Directory Labels (Windows 11)</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fake-the-location-to-get-around-the-mlb-blackouts-on-samsung-galaxy-m54-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Fake the Location to Get Around the MLB Blackouts on Samsung Galaxy M54 5G | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/optimizing-content-creation-on-tiktok-incorporating-siri-speech-functions-for-2024/"><u>Optimizing Content Creation on TikTok  Incorporating Siri Speech Functions for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-dissecting-the-capabilities-of-free2x-recording-software/"><u>2024 Approved  Dissecting the Capabilities of Free2X Recording Software</u></a></li>
<li><a href="https://windows11.techidaily.com/altering-windows-files-date-creation-and-modification-adjustments/"><u>Altering Windows Files: Date Creation & Modification Adjustments</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-minitool-movie-maker-vs-the-competition-a-comprehensive-review-and-alternatives/"><u>Updated Minitool Movie Maker Vs. The Competition A Comprehensive Review and Alternatives</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-roblox-error-262s-solutions/"><u>Breaking Down Roblox Error 262'S Solutions</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-in-2024-the-ultimate-selection-of-six-compelling-chrome-talk-transformers-to-experience-moviemagicsuite/"><u>New In 2024, The Ultimate Selection of Six Compelling Chrome Talk Transformers to Experience - MovieMagicSuite</u></a></li>
<li><a href="https://windows11.techidaily.com/assessing-usage-windows-hidden-reliability-vs-performance-tools/"><u>Assessing Usage: Windows' Hidden Reliability Vs. Performance Tools</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-achieving-high-quality-frequency-modulation-in-audacity/"><u>New 2024 Approved Achieving High-Quality Frequency Modulation in Audacity</u></a></li>
<li><a href="https://windows11.techidaily.com/choosing-your-win-software-downloader-choco-versus-wslm/"><u>Choosing Your Win Software Downloader: Choco Versus WSLM</u></a></li>
<li><a href="https://windows11.techidaily.com/ace-your-win-11-games-with-these-best-fps-tools/"><u>Ace Your Win 11 Games with These Best FPS Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-the-sluggishness-of-windows-discord-features/"><u>Addressing the Sluggishness of Windows Discord Features</u></a></li>
<li><a href="https://windows11.techidaily.com/avoidance-of-windows-updates-interruptions/"><u>Avoidance of Windows Updates Interruptions</u></a></li>
<li><a href="https://windows11.techidaily.com/booting-up-windows-sound-service-quick-fix-steps/"><u>Booting Up Windows Sound Service: Quick Fix Steps</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-watch-hulu-outside-us-on-honor-play-7t-drfone-by-drfone-virtual-android/"><u>How to Watch Hulu Outside US On Honor Play 7T | Dr.fone</u></a></li>
</ul></div>
