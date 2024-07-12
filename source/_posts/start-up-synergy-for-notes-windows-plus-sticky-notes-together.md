---
title: "Start-Up Synergy for Notes: Windows + Sticky Notes Together"
date: 2024-07-11T21:33:15.588Z
updated: 2024-07-12T21:33:15.588Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Start-Up Synergy for Notes: Windows + Sticky Notes Together"
excerpt: "This Article Describes Start-Up Synergy for Notes: Windows + Sticky Notes Together"
keywords: Start-Up Synergy,Windows Sticky Notes,Note Integration,Cross-Platform Collaboration,Productivity Enhancement,Software Amalgamation,Unified Note System
thumbnail: https://thmb.techidaily.com/3ccfed125e4471bfeef796f7e1d53a32e1cb3d7aef2eb6fc1425b4243cea5954.jpg
---

## Start-Up Synergy for Notes: Windows + Sticky Notes Together

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
<li><a href="https://windows11.techidaily.com/streamlining-secure-logins-with-5-tips-against-key-conflicts-in-win11/"><u>Streamlining Secure Logins with 5 Tips Against Key Conflicts in Win11</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-joke-jigsaw-puzzles-build-with-kapwingenasian-memes/"><u>In 2024, Joke Jigsaw Puzzles  Build with Kapwing’enasian Memes</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-the-not-an-empty-directory-alert-error-code-0x80070091-in-win11/"><u>Conquering the Not an Empty Directory Alert (Error Code: 0X80070091) in Win11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-lost-files-from-samsung-galaxy-m34-by-fonelab-android-recover-data/"><u>How to retrieve lost files from Samsung Galaxy M34?</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-nvidia-opengl-glitches-in-windows-11/"><u>Troubleshooting NVIDIA OpenGL Glitches in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/distinguishing-between-hdd-and-ssd-drives-on-pc/"><u>Distinguishing Between HDD & SSD Drives on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-to-repair-keyboard-issues-with-windows-snipper/"><u>Tips to Repair Keyboard Issues with Windows Snipper</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-crafting-the-perfect-soundtrack-for-your-vimeo-content/"><u>In 2024, Crafting the Perfect Soundtrack for Your Vimeo Content</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/the-insiders-guide-to-creating-stunning-iphone-hdr-photos/"><u>The Insider's Guide to Creating Stunning iPhone HDR Photos</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-telnet-enablement-steps-explained/"><u>Windows 11 Telnet Enablement Steps Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-power-start-cmd-as-administrator/"><u>Boosting Power: Start CMD as Administrator</u></a></li>
<li><a href="https://windows11.techidaily.com/surviving-windows-11-blue-screen-adopting-11-key-approaches/"><u>Surviving Windows 11 Blue Screen: Adopting 11 Key Approaches</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-and-tricks-solving-the-try-connecting-bluetooth-issue/"><u>Tips and Tricks: Solving the 'Try Connecting' Bluetooth Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-empty-folder-warning-in-windows-11/"><u>Eliminating 'Empty Folder' Warning in Windows 11</u></a></li>
<li><a href="https://driver-install.techidaily.com/simplified-steps-updating-hardware-drivers-for-latest-wins/"><u>Simplified Steps: Updating Hardware Drivers for Latest Wins</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-elevated-privileges-for-power-users-a-guide/"><u>Enabling Elevated Privileges for Power Users: A Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-diagnostics-enhancing-windows-11-troubleshooters/"><u>Reviving Diagnostics: Enhancing Windows 11 Troubleshooters</u></a></li>
<li><a href="https://windows11.techidaily.com/winerror-correction-bypassing-the-perplexing-0x80072746-mail-issue/"><u>WinError Correction: Bypassing the Perplexing 0X80072746 Mail Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-causes-of-pc-disk-issues/"><u>Addressing Causes of PC Disk Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-camera-app-malfunction-in-windows-11/"><u>Addressing Camera App Malfunction in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-your-window-experience-mastering-the-start-menu/"><u>Enhance Your Window Experience: Mastering the Start Menu</u></a></li>
<li><a href="https://fake-location.techidaily.com/which-is-the-best-fake-gps-joystick-app-on-lava-blaze-2-5g-drfone-by-drfone-virtual-android/"><u>Which is the Best Fake GPS Joystick App On Lava Blaze 2 5G? | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-speedy-sonic-transformation-altering-audio-velocity-with-ease-for-2024/"><u>New Speedy Sonic Transformation Altering Audio Velocity with Ease for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-a-guide-to-perfect-portraits-with-background-blur/"><u>[New] A Guide to Perfect Portraits with Background Blur</u></a></li>
<li><a href="https://windows11.techidaily.com/the-anticipation-surrounding-windows-11s-moment-22h2/"><u>The Anticipation Surrounding Windows 11’S Moment #22H2</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-pause-auto-updates-no-more-prompts/"><u>Windows Pause Auto-Updates: No More Prompts!</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-for-fixing-unopenable-windows-folders-on-double-click/"><u>Tactics for Fixing Unopenable Windows Folders on Double-Click</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-nvidia-connect-failure-on-windows-11-systems/"><u>Fixing Nvidia Connect Failure on Windows 11 Systems</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-after-switching-from-oppo-f23-5g-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data After Switching From Oppo F23 5G to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-regain-lost-connection-on-pcs-running-windows/"><u>Strategies to Regain Lost Connection on PCs Running Windows</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-catchemall-celebrate-national-pokemon-day-with-virtual-location-on-motorola-moto-g23-drfone-by-drfone-virtual-android/"><u>In 2024, CatchEmAll Celebrate National Pokémon Day with Virtual Location On Motorola Moto G23 | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-harmonizing-social-media-twitter-plus-tumblr-videos/"><u>[New] In 2024, Harmonizing Social Media  Twitter + Tumblr Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-preventing-windows-autolock-timed-out/"><u>Tips for Preventing Windows Autolock Timed Out</u></a></li>
<li><a href="https://windows11.techidaily.com/direct-path-to-spooler-restart/"><u>Direct Path to Spooler Restart</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-unmarked-eyes-facebook-story-viewer/"><u>[Updated] In 2024, Unmarked Eyes  Facebook Story Viewer</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-winerror-x80780119-resolution/"><u>Techniques for WinError X80780119 Resolution</u></a></li>
<li><a href="https://windows11.techidaily.com/blueprints-to-build-secure-window-for-hardware-unhook/"><u>Blueprints to Build Secure Window for Hardware Unhook</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-chatgpt-on-your-windows-pc/"><u>Configuring ChatGPT on Your Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/can-you-get-rid-of-the-windows-bt-directories/"><u>Can You Get Rid of the Windows ~BT Directories?</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-role-of-ai-in-windows-11-updates/"><u>Unveiling the Role of AI in Windows 11 Updates</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/syncopate-sound-and-picture-youtubes-audio-editing-techniques/"><u>Syncopate Sound and Picture  YouTube's Audio Editing Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-mysteries-of-ram-in-windows-devices/"><u>Decoding the Mysteries of RAM in Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-managing-events-with-windows-11-calendar/"><u>Efficiently Managing Events with Windows 11 Calendar</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-non-functional-inbox-alerts-on-windows-os/"><u>Tackling Non-Functional Inbox Alerts on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-user-interface-integrating-emoji-15-into-win11/"><u>Boosting User Interface: Integrating Emoji 15 Into Win11</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-synchronized-aesthetics-audio-meets-picture/"><u>2024 Approved  Synchronized Aesthetics  Audio Meets Picture</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-green-up-your-cta-strategy-with-tools-for-2024/"><u>[Updated] Green Up Your CTA Strategy with Tools for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/vercoming-video-shadows-youtube-fix-tips-for-2024/"><u>[New] Overcoming Video Shadows  YouTube Fix Tips for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-chromes-erroneous-virus-warning-on-pc/"><u>Clearing Chrome's Erroneous Virus Warning on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/the-importance-of-keeping-active-wins-11-notification-sounds/"><u>The Importance of Keeping Active Wins 11 Notification Sounds</u></a></li>
</ul></div>
