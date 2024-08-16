---
title: "Streamlining Startup: Opening Sticky Notes Seamlessly on PC"
date: 2024-08-15T16:07:41.071Z
updated: 2024-08-16T16:07:41.071Z
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
3. In the first step, give your task a name and click **Next**.  
![Startup Sticky Notes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/startup-sticky-notes.jpg)
4. Now select **When I log on** as the trigger and click **Next** at the bottom.  
![Create Basic Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-basic-task-wizard.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
5. Choose **Start a program** in the Action window and click **Next**.  
![Start a program in Action tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-a-program-in-action-tab.jpg)
6. In the **Program/script** field, type the path below:  
C:\Windows\System32\cmd.exe
7. In the Add arguments (optional) field, copy and paste the following command:  
/c start shell:appsfolder\Microsoft.MicrosoftStickyNotes_8wekyb3d8bbwe!App  
![Start a Program in Task Scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-a-program-in-task-scheduler.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
8. Click **Next** and review all the settings.
9. Now click **Finish** to save your work.  
![Finish Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/finish-task-wizard.jpg)
<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->

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
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->
6. Change the Value data from 0 to **1** in the Edit DWORD (32-bit) Value window and click **OK**.  
 If you can't find the **LaunchOnNextUserSession** key, right-click on the **Notes** folder and select **New > DWORD (32-bit) Value**. Name the newly created key “LaunchOnNextUserSession” and assign it the Value data of **1**.
7. Close the Registry Editor and restart your computer to save the changes. Sticky Notes should now open at startup.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-journey-through-the-land-of-costless-image-mastery/"><u>[New] 2024 Approved  Journey Through the Land of Costless Image Mastery</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-craft-stunning-designs-learn-to-cleanse-images-background-in-canva/"><u>[New] Craft Stunning Designs  Learn to Cleanse Images' Background in Canva</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-how-to-archive-your-minecraft-sessions-on-a-mac-computer-for-2024/"><u>[New] How to Archive Your Minecraft Sessions on a Mac Computer for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-creating-impactful-youtube-thumbnails-and-ads/"><u>[New] In 2024, Creating Impactful YouTube Thumbnails & Ads</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-from-novice-to-virtuoso-taking-control-with-screen-recordings-in-macos/"><u>[Updated] 2024 Approved  From Novice to Virtuoso  Taking Control with Screen Recordings in macOS</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-unlocking-the-art-of-pc-games-screen-capture/"><u>[Updated] 2024 Approved  Unlocking the Art of PC Games Screen Capture</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-visionenhance-pro-high-fidelity-video-upgrade-for-2024/"><u>[Updated] VisionEnhance Pro - High Fidelity Video Upgrade for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-best-subtitle-converters-reviewed-the-top-8-win-osx-sbt-to-srts-software/"><u>2024 Approved  Best Subtitle Converters Reviewed  The Top 8 Win-OSX SBT to SRTS Software</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/approved-grassroots-video-marketing-strategies/"><u>2024 Approved  Grassroots Video Marketing Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/4-ways-to-check-your-network-adapter-speed-on-windows/"><u>4 Ways to Check Your Network Adapter Speed on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/6-fixes-for-windows-gone-dark-and-unresponsive/"><u>6 Fixes for Windows Gone Dark and Unresponsive</u></a></li>
<li><a href="https://windows11.techidaily.com/a-detailed-guide-turning-off-windows-update-restrictions/"><u>A Detailed Guide: Turning Off Windows Update Restrictions</u></a></li>
<li><a href="https://windows11.techidaily.com/a-short-tale-on-wintoys-unveiling-a-compelling-windows-application/"><u>A Short Tale on 'WinToys': Unveiling a Compelling Windows Application</u></a></li>
<li><a href="https://windows11.techidaily.com/adding-comprehensive-firewall-tools-to-windows-11s-menu-bar/"><u>Adding Comprehensive Firewall Tools to Windows 11’S Menu Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-security-automating-passwords-in-windows-texts/"><u>Advanced Security: Automating Passwords in Windows Texts</u></a></li>
<li><a href="https://windows11.techidaily.com/archiving-acumen-covertly-concealing-zip-in-photos-win11/"><u>Archiving Acumen: Covertly Concealing ZIP in Photos (Win11)</u></a></li>
<li><a href="https://windows11.techidaily.com/avoidance-of-memory-limitations-strategies-for-windows/"><u>Avoidance of Memory Limitations: Strategies for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/blue-screen-decoded-understanding-and-fixing-0x0000003b-in-win-os/"><u>Blue Screen Decoded: Understanding and Fixing 0X0000003B in Win OS</u></a></li>
<li><a href="https://article-posts.techidaily.com/choreographing-ideal-canon-sequential-shots-for-2024/"><u>Choreographing Ideal Canon Sequential Shots for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-windows-11s-directive-non-empty-problem-0x80070091/"><u>Clearing Up Windows 11'S Directive Non-Empty Problem #0X80070091</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-common-downloads-dilemmas-on-windows-pcs/"><u>Combatting Common Downloads Dilemmas on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/command-center-for-direct-access-to-windows-11s-appsfolders/"><u>Command Center for Direct Access to Windows 11'S AppsFolders</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-compatibility-issues-windows-troubleshooting-blueprint/"><u>Conquer Compatibility Issues: Windows Troubleshooting Blueprint</u></a></li>
<li><a href="https://windows11.techidaily.com/control-windows-11s-emphasis-and-search-highlight/"><u>Control Windows 11'S Emphasis and Search Highlight</u></a></li>
<li><a href="https://windows11.techidaily.com/cool-off-cycles-in-the-world-of-computers/"><u>Cool-Off Cycles in the World of Computers</u></a></li>
<li><a href="https://windows11.techidaily.com/countering-compromised-windows-defender-on-win-11/"><u>Countering Compromised Windows Defender on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-unique-room-backgrounds-with-windows-spotlight-pics/"><u>Crafting Unique Room Backgrounds with Windows Spotlight Pics</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-pc-audio-with-windows-11s-volume-mixer-tutorial/"><u>Customize PC Audio with Windows 11'S Volume Mixer Tutorial</u></a></li>
<li><a href="https://windows11.techidaily.com/decode-and-resolve-uninitialized-disk-message-on-pc/"><u>Decode and Resolve Uninitialized Disk Message on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-bsod-0x0000003b-and-resolution-steps-in-windows-os/"><u>Decoding BSOD -0X0000003B & Resolution Steps in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/diagnosing-and-repairing-dormant-window-control/"><u>Diagnosing and Repairing Dormant Window Control</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-fatal-component-error-in-win10win11-system/"><u>Disabling Fatal Component Error in Win10/Win11 System</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/elevate-your-videos-best-3d-animation-and-video-software/"><u>Elevate Your Videos Best 3D Animation and Video Software</u></a></li>
<li><a href="https://windows11.techidaily.com/1719271997711-enable-high-contrast-mode-go-to-ease-of-access-settings-and-enable-high-contrast-mode-if-it-improves-visibility/"><u>Enable High Contrast Mode: Go to 'Ease of Access' Settings and Enable High Contrast Mode if It Improves Visibility.</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-iphone-se-2020-without-passcode-4-easy-methods-by-drfone-ios/"><u>How To Unlock iPhone SE (2020) Without Passcode? 4 Easy Methods</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-cut-to-perfection-producing-captivating-loop-content-for-instagram/"><u>In 2024, Cut to Perfection  Producing Captivating Loop Content for Instagram</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-sim-unlock-xiaomi-redmi-k70-pro-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>In 2024, Sim Unlock Xiaomi Redmi K70 Pro Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-superior-systems-best-of-the-desk-lineup/"><u>In 2024, Superior Systems  Best of the Desk Lineup</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-6-best-sim-unlock-services-that-actually-work-on-your-nokia-device-by-drfone-android/"><u>In 2024, The 6 Best SIM Unlock Services That Actually Work On Your Nokia Device</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/in-2024-video-valedictions-sign-off-strategies-for-online-platforms/"><u>In 2024, Video Valedictions  Sign-Off Strategies for Online Platforms</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-2024-approved-gif-tempo-tweakers-the-best-online-and-mobile-solutions/"><u>New 2024 Approved GIF Tempo Tweakers The Best Online and Mobile Solutions</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/quick-and-painless-ways-to-screen-record-stories-for-2024/"><u>Quick & Painless Ways to Screen Record Stories for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/streamline-your-wedding-countdown-the-best-androidios-clock-apps-guide/"><u>Streamline Your Wedding Countdown  The Best Android/iOS Clock Apps Guide</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ior-streams-with-av1-activate-on-youtube/"><u>Superior Streams with AV1  Activate on YouTube</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-6-best-sim-unlock-services-that-actually-work-on-your-gionee-device-by-drfone-android/"><u>The 6 Best SIM Unlock Services That Actually Work On Your Gionee Device</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/troubleshooting-microsoft-word-when-files-refuse-to-launch/"><u>Troubleshooting Microsoft Word: When Files Refuse to Launch</u></a></li>
</ul></div>
