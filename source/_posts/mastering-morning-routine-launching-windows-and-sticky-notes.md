---
title: "Mastering Morning Routine: Launching Windows & Sticky Notes"
date: 2024-08-15T16:02:08.139Z
updated: 2024-08-16T16:02:08.139Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Morning Routine: Launching Windows & Sticky Notes"
excerpt: "This Article Describes Mastering Morning Routine: Launching Windows & Sticky Notes"
keywords: Morning Rituals Guide,Wake Up Tips,Start-Up Tricks,Productivity Mornings,Task Automation,Quick Notetaking,Focus Booster Routine
thumbnail: https://thmb.techidaily.com/9f88f4d439bd19afe08962ae532d3a6f41b689b2a4dc10b0fa384c3313d41768.jpg
---

## Mastering Morning Routine: Launching Windows & Sticky Notes

 Are you tired of opening Sticky Notes every time you turn on your computer? What if it could open automatically each time Windows starts?

 Well, there's good news for you: Sticky Notes can launch at startup in Windows. This article illustrates how to set up and use Sticky Notes at startup.

## 1\. Keep Sticky Notes Open at Shutdown

 When you're done working with Sticky Notes, make sure not to close the window. Instead, leave it open as you shut down your computer. This will ensure that when you turn on your computer, Sticky Notes opens automatically.

 Although the solution is simple, it may not work, or you may find it difficult to remember to keep it open when you turn off your PC. In that case, there are other alternatives; add Sticky Notes to the startup folder or use Task Scheduler.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. Add Sticky Notes to the Startup Folder

 If you don't want to keep Sticky Notes open at shutdown, you can add it to the startup folder. The Startup folder is a special directory in File Explorer. It stores applications that launch automatically when Windows starts.

 To add Sticky Notes to the Startup folder, follow these steps.

1. Press **Win + R** and type **shell:startup** in the Run dialog.
2. Click **OK** or press Enter. This opens a folder containing all the applications that launch at startup.
3. Press **Windows** to open the Start menu, then click **All apps**. Now scroll down and find **Sticky Notes** in the list.
4. Drag and drop **Sticky Notes** into the Startup folder.

 After performing these steps, close File Explorer and restart your computer. Sticky Notes should now open at startup.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
5. Choose **Start a program** in the Action window and click **Next**.  
![Start a program in Action tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-a-program-in-action-tab.jpg)
<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. In the **Program/script** field, type the path below:  
C:\Windows\System32\cmd.exe
7. In the Add arguments (optional) field, copy and paste the following command:  
/c start shell:appsfolder\Microsoft.MicrosoftStickyNotes_8wekyb3d8bbwe!App  
![Start a Program in Task Scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-a-program-in-task-scheduler.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://facebook-video-footage.techidaily.com/new-efficient-editing-for-quick-youtube-content-for-2024/"><u>[New] Efficient Editing for Quick YouTube Content for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-introduction-to-interactive-graphic-design/"><u>[New] Introduction to Interactive Graphic Design</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-2024-approved-audience-engagement-where-to-captivate-viewers/"><u>[Updated] 2024 Approved  Audience Engagement  Where to Captivate Viewers</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-transform-every-moment-top-ideas-for-enriching-life-through-podcasts/"><u>[Updated] Transform Every Moment  Top Ideas for Enriching Life Through Podcasts</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-becoming-a-reel-virtuoso-in-the-social-media-arena/"><u>2024 Approved  Becoming a Reel Virtuoso in the Social Media Arena</u></a></li>
<li><a href="https://windows11.techidaily.com/blocking-windows-update-prompts/"><u>Blocking Windows Update Prompts</u></a></li>
<li><a href="https://windows11.techidaily.com/cherishing-the-slumber-of-your-computer/"><u>Cherishing the Slumber of Your Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/clear-and-constructive-icon-arrangement-ideas/"><u>Clear and Constructive Icon Arrangement Ideas</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-exploration-of-windows-narrators-legacy-keys/"><u>Comprehensive Exploration of Windows Narrator's Legacy Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-windows-errors-during-amd-195-installation/"><u>Eliminating Windows Errors During AMD 195 Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-and-forge-a-friendly-startup-in-windows-amidst-errors/"><u>Fix and Forge a Friendly Startup in Windows Amidst Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/hidden-windows-11-theme-treasures-revealed/"><u>Hidden Windows 11 Theme Treasures Revealed</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reveal-hidden-sd-card-in-file-explorer/"><u>How to Reveal Hidden SD Card in File Explorer?</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-actions-to-mend-post-windows-update-issues/"><u>Immediate Actions to Mend Post-Windows Update Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/interpreting-launch-identifiers-for-applications/"><u>Interpreting Launch Identifiers for Applications</u></a></li>
<li><a href="https://windows11.techidaily.com/launching-the-driver-verifier-in-win11-os/"><u>Launching the Driver Verifier in Win11 OS</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-learn-how-everything-works-on-tecno-pop-8-drfone-by-drfone-virtual-android/"><u>Life360 Learn How Everything Works On Tecno Pop 8 | Dr.fone</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/mac-stellar-file-cleaner-basic-plan-with-automated-deletion-features/"><u>Mac Stellar File Cleaner - Basic Plan with Automated Deletion Features</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-of-internet-options-tweaks-for-windows-11/"><u>Mastery of Internet Options Tweaks for Windows 11</u></a></li>
<li><a href="https://technical-tips.techidaily.com/maximize-your-music-experience-by-connecting-different-bluetooth-speakers-to-the-same-electronic-apparatus/"><u>Maximize Your Music Experience by Connecting Different Bluetooth Speakers to the Same Electronic Apparatus</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-chromes-erroneous-threat-detection-a-guide/"><u>Navigating Chrome's Erroneous Threat Detection: A Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-common-windo-errors-quickly/"><u>Navigating Through Common Windo Errors, Quickly</u></a></li>
<li><a href="https://fix-guide.techidaily.com/play-store-not-working-on-vivo-t2x-5g-8-solutions-inside-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Not Working On Vivo T2x 5G? 8 Solutions Inside | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/premium-listing-high-performing-15-camcorders-for-2024/"><u>Premium Listing  High-Performing 15 Camcorders for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/procedures-to-enable-or-disable-windows-build-service/"><u>Procedures to Enable or Disable Windows Build Service</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-guide-to-restore-windows-11-troubleshooters/"><u>Quick FIX Guide to Restore Windows 11 Troubleshooters</u></a></li>
<li><a href="https://windows11.techidaily.com/quiet-windows-11-feedback-and-hints/"><u>Quiet Windows 11 Feedback and Hints</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-for-unsupported-audio-device-windowss/"><u>Remedy for Unsupported Audio Device Windowss</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-smooth-operation-fix-frozen-epic-games-launcher/"><u>Securing Smooth Operation: Fix Frozen Epic Games Launcher</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-ipad-image-import-issues-in-windows-1111-pro/"><u>Solving iPad Image Import Issues in Windows 11/11 Pro</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-ultimate-handbook-for-swapping-music-libraries-for-2024/"><u>The Ultimate Handbook for Swapping Music Libraries for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-device-synergy-with-google-nearby-sharing/"><u>Unlocking Device Synergy with Google Nearby Sharing</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-of-windows-blue-screen-error-0x8007007e/"><u>Unraveling the Mystery of Windows Blue Screen Error: 0X8007007E</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-systems-peak-performance-limits/"><u>Unveiling System's Peak Performance Limits</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-incorporating-a-god-mode-shortcut/"><u>Windows 11: Incorporating a God Mode Shortcut</u></a></li>
</ul></div>
