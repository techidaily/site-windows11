---
title: Modify Default Task Manager Viewport in Win11
date: 2024-08-27T16:13:22.432Z
updated: 2024-08-28T16:13:22.432Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Modify Default Task Manager Viewport in Win11
excerpt: This Article Describes Modify Default Task Manager Viewport in Win11
keywords: Win11 Task View Modification,Windows 11 User Interface Tweaks,Altering Task Manager Layout,Win11 Display Adjustments,Customizing Windows Taskbar,Change Windows Settings,Task Manager UI Enhancement
thumbnail: https://thmb.techidaily.com/5bfb2b2f01975a3eebb8a0b131dcc5bf0873594ba112a1d8a6d8b08b27b2cbba.jpg
---

## Modify Default Task Manager Viewport in Win11

 The Task Manager provides a quick overview of your system's current status and shows essential information. Its Start page displays useful details such as currently running background processes, applications, CPU, and memory utilization. If you'd like to customize its appearance, change the Start page. In this article, we’ll look at how to change the Task Manager Start page in Windows 11\.

## 1\. Use Task Manager Settings

 If you want to quickly change the Task Manager Start page, you can use its Settings tab. This option requires no modification to the registry editor or additional scripts to run.

 To change the Task Manager Start page using Task Manager settings, do the following.

1. Press **Win + R** to open the Run dialog box.
2. Type **taskmgr** and press **Enter** to launch Task Manager.
3. Once in Task Manager, click on **Settings** (the gear icon).
4. You'll see a **Default Start Page** drop-down menu at the top. This is where you can select the page to display when Task Manager opens.  
![Use Settings to Change Task Manager Start Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/use-settings-to-change-task-manager-start-page.jpg)

 The options available are the following:

1. Processes
2. Performance
3. App history
4. Startup apps
5. Users
6. Details
7. Services ​​​​

 Once you make a selection, Task Manager will remember the setting and open the page you chose from now on.

## 2\. Tweak the Registry Editor

 The Registry Editor is another way to change the default Start page for Task Manager. The procedure is slightly more complex than using Task Manager Settings, but it offers more customization options. Be careful when modifying entries in the Registry Editor, as incorrect changes can cause errors or system instability. To avoid losing data, [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it.

 To change the Task Manager Start page using the Registry Editor, follow these steps.

1. [Open the Registry Editor window](https://www.makeuseof.com/windows-11-open-registry-editor/).
2. If the UAC prompt pops up, click **Yes** to grant administrative rights.
3. In the left pane, navigate to the following key.  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\TaskManager`
4. Double-click **StartUpTab** in the right pane. If there is no such entry, then right-click on the Task Manager key.
5. From the context menu, select **New > DWORD (32-bit) Value**.
6. Now name the value **StartUpTab** and double-click on it.  
![Modify Registry to Change Task Manager Start Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modify-registry-to-change-task-manager-start-page.jpg)
7. Set its **Value data** to one of the following numbers to change the default start page:  
`0 = Processes  

1 = Performance  

2 = App history  

3 = Startup apps  

4 = Users  

5 = Details  

6 = Services`
8. Click **OK** to save the changes and close the Registry Editor window.

 Next time you open Task Manager, it will display a page according to your preferences.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Use a REG File

 If the registry editor isn't your thing, you can use a REG file to modify the Task Manager start page. The process does not require registry tweaking and is straightforward.

 To create a .reg file, [open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) and type the following:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\TaskManager]  
  
"StartUpTab"=dword:00000000`

 Here, the last digit reflects the type of Start page.

 For example, if you want to set **Processes** as your default start page, use **0** (**00000000**). Similarly, if you want the **Details** page to display as default, set it to **5** (**00000005**).

 The other options are:

`00000001 - Performance  
  
00000002 - App history  
  
00000003 - Startup apps  
  
00000004 - Users  
  
00000006 - Services`

 Now, click **File** and select **Save as**. In the Save as dialog box, click the Save as type drop-down menu and select **All files**. Name the file with the **.reg** extension. For example, **TaskManagerStartPage.reg**.

![Use a REG File to Change Task Manager Start Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/use-a-reg-file-to-change-task-manager-start-page.jpg)

<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Next, select **Desktop** from the left pane and click **Save**. Once saved, double-click on this newly created REG file. This adds the required details to the Registry Editor and changes the Task Manager start page.

 If you ever want to revert the changes, delete the REG file and restart your computer.

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Changing the Task Manager Start Page on Windows

 It’s easy to customize Task Manager and change its Start page according to your preference. You can use Task Manager Settings, the Registry Editor, or a REG file to set the desired page. Once you have set the Start page, Task Manager will remember it and open that page when you launch it.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-direct.techidaily.com/new-2024-approved-the-ultimate-list-for-google-pixel-tones/"><u>[New] 2024 Approved  The Ultimate List for Google Pixel Tones</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-comprehensive-audfreexpress-assessment-users/"><u>[New] The Comprehensive AudFreeXpress Assessment Users</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-top-strategies-for-capturing-discords-real-time-broadcasts/"><u>2024 Approved  Top Strategies for Capturing Discord's Real-Time Broadcasts</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/before-going-green-the-critical-checklist-of-owning-an-ev/"><u>Before Going Green: The Critical Checklist of Owning an EV</u></a></li>
<li><a href="https://extra-hints.techidaily.com/beyond-tiktok-horizons-the-essence-of-triller-for-2024/"><u>Beyond TikTok Horizons  The Essence of Triller for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/cooking-up-healthiness-can-chatgpt-be-your-dietary-mentor/"><u>Cooking Up Healthiness: Can ChatGPT Be Your Dietary Mentor?</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/cultural-etiquette-for-successful-socializing-in-south-america/"><u>Cultural Etiquette for Successful Socializing in South America</u></a></li>
<li><a href="https://article-helps.techidaily.com/deepening-dive-close-up-in-minecraft-worlds/"><u>Deepening Dive  Close-Up in Minecraft Worlds</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-airplane-mode-turn-off-gps-location-on-oppo-f25-pro-5g-drfone-by-drfone-virtual-android/"><u>Does Airplane Mode Turn off GPS Location On Oppo F25 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-airplane-mode-turn-off-gps-location-on-oppo-find-n3-flip-drfone-by-drfone-virtual-android/"><u>Does Airplane Mode Turn off GPS Location On Oppo Find N3 Flip? | Dr.fone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-bcm207e0-usb-drivers-fast-compatible-with-all-windows-versions/"><u>Download BCM207e0 USB Drivers Fast – Compatible with All Windows Versions</u></a></li>
<li><a href="https://tech-haven.techidaily.com/enhance-your-productivity-with-dual-monitor-setup-on-windows-11/"><u>Enhance Your Productivity with Dual Monitor Setup on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/evaluating-windows-n-models-should-you-upgrade/"><u>Evaluating Windows N Models: Should You Upgrade?</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-guide-to-streamline-program-access-via-context-menu/"><u>Expert Guide to Streamline Program Access via Context Menu</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/google-data-retrieval-tool-restore-lost-data-from-google-pixel-7a-by-fonelab-android-recover-data/"><u>Google Data Retrieval tool – restore lost data from Google Pixel 7a</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/guerrilla-marketing-for-youtube-upping-video-traffic/"><u>Guerrilla Marketing for YouTube  Upping Video Traffic</u></a></li>
<li><a href="https://screen-capture.techidaily.com/how-to-blur-the-video-background-in-a-microsoft-teams-meeting-for-2024/"><u>How to Blur the Video Background in a Microsoft Teams Meeting for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-deal-with-the-lava-yuva-3-screen-black-but-still-works-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Deal With the Lava Yuva 3 Screen Black But Still Works? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-nullify-windows-aural-overdrive/"><u>How To Nullify Windows Aural Overdrive</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-fake-android-location-without-rooting-for-your-motorola-moto-g73-5g-drfone-by-drfone-virtual/"><u>In 2024, Fake Android Location without Rooting For Your Motorola Moto G73 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/incorporating-visual-media-into-free-writings/"><u>Incorporating Visual Media Into Free Writings</u></a></li>
<li><a href="https://win-howtos.techidaily.com/keyboard-dysfunction-fixes-for-windows-1078-users-facing-typing-issues/"><u>Keyboard Dysfunction Fixes for Windows 10/7/8 Users Facing Typing Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/legacys-latest-look-instructions-for-windows-11-using-to-go-and-rufus-technology/"><u>Legacy's Latest Look: Instructions for Windows 11, Using To Go & Rufus Technology</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723015249753-logitech-g2n30-headset-mic-problems-quick-solutions-that-actually-work/"><u>Logitech G2n30 Headset Mic Problems: Quick Solutions That Actually Work</u></a></li>
<li><a href="https://windows11.techidaily.com/making-windows-easier-personalized-text-transcription-using-ahk-and-whisper/"><u>Making Windows Easier: Personalized Text Transcription Using AHK & Whisper</u></a></li>
<li><a href="https://program-issues.techidaily.com/mastering-borderlands-3-11-expert-fixes-for-a-seamless-startup-experience/"><u>Mastering Borderlands 3: 11 Expert Fixes for a Seamless Startup Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/microsoft-and-native-accounts-key-differences-unpacked-in-os-windows/"><u>Microsoft & Native Accounts: Key Differences Unpacked in OS Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-flashing-issues-on-windows-11-pcs/"><u>Overcoming Flashing Issues on Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-unyielding-mode-switches-on-win11/"><u>Overcoming Unyielding Mode Switches on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-operation-failure-x709/"><u>Overcoming Windows Operation Failure X709</u></a></li>
<li><a href="https://windows11.techidaily.com/pinpointing-your-internet-ip-using-terminal-commands/"><u>Pinpointing Your Internet IP Using Terminal Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/pioneering-the-future-running-windows-11-on-legacy-pcs-through-to-go-and-rufus/"><u>Pioneering the Future: Running Windows 11 on Legacy PCs Through To Go & Rufus</u></a></li>
<li><a href="https://windows11.techidaily.com/privacy-control-remove-your-email-in-login-screen/"><u>Privacy Control: Remove Your Email in Login Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-preventing-windows-dwarf-fortress-crashes/"><u>Quick Guide: Preventing Windows-Dwarf Fortress Crashes</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaim-missing-flight-copilot-on-new-os-ws11/"><u>Reclaim Missing Flight Copilot on New OS WS11</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-disconnected-messages-in-windows-discord/"><u>Rectifying Disconnected Messages in Windows Discord</u></a></li>
<li><a href="https://windows11.techidaily.com/rescuing-your-windows-application-performance-in-a-hurry-7-solutions/"><u>Rescuing Your Window's Application Performance in a Hurry (7 Solutions)</u></a></li>
<li><a href="https://windows11.techidaily.com/resolve-your-black-screen-woes-with-simple-tricks-for-win11/"><u>Resolve Your Black Screen Woes with Simple Tricks for Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/reversing-roblox-errors-on-microsoft-os/"><u>Reversing Roblox Errors on Microsoft OS</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-code-0xc0000142-on-windows-xp-1011/"><u>Solving Code 0XC0000142 on Windows XP, 10/11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/sonic-scenes-from-still-shots-for-2024/"><u>Sonic Scenes From Still Shots for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/tech-tricks-blend-taskbar-language-feature-win11-style/"><u>Tech Tricks: Blend Taskbar Language Feature, Win11 Style</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-best-5-artificial-intelligence-therapeutic-chatbots-and-tools-to-enhance-mental-wellness/"><u>The Best 5 Artificial Intelligence Therapeutic Chatbots & Tools to Enhance Mental Wellness</u></a></li>
<li><a href="https://windows11.techidaily.com/the-quintessence-of-productivity-win-11s-top-7-widgets/"><u>The Quintessence of Productivity: Win 11’S Top 7 Widgets</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-and-techniques-for-windows-11-diagnostic-rehabilitation/"><u>Tips and Techniques for Windows 11 Diagnostic Rehabilitation</u></a></li>
<li><a href="https://vp-tips.techidaily.com/top-10-smartphone-vr-gadgets-uncovered-for-2024/"><u>Top 10 Smartphone VR Gadgets Uncovered for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-unavailable-roblox-due-to-user-configs-on-windows/"><u>Troubleshooting Unavailable Roblox Due to User Configs on WINDOWS</u></a></li>
<li><a href="https://windows11.techidaily.com/tutorial-empowering-end-task-capability-on-windows-11/"><u>Tutorial: Empowering End Task Capability on Windows 11</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/ultimate-selection-of-cutting-edge-smart-glasses/"><u>Ultimate Selection of Cutting-Edge Smart Glasses</u></a></li>
<li><a href="https://windows11.techidaily.com/unfolding-windows-solutions-for-stubborn-folders-on-double-click/"><u>Unfolding Windows: Solutions for Stubborn Folders on Double-Click</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-file-past-mastering-windows-11s-history-access/"><u>Unlocking File Past: Mastering Windows 11'S History Access</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-over-common-mmc-snapshot-glitches/"><u>Winning Over Common MMC Snapshot Glitches</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>