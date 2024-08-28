---
title: Securing Administrator-Level PowerShell Execution Window in W11
date: 2024-08-27T16:09:58.054Z
updated: 2024-08-28T16:09:58.054Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Securing Administrator-Level PowerShell Execution Window in W11
excerpt: This Article Describes Securing Administrator-Level PowerShell Execution Window in W11
keywords: PowerShell Admin Security,Windows 11 Secure Scripts,Elevate Execution Protection,Restrict PowerShell Access,Limit Admin Commands WS11,Enhance Window Control,Prevent Privilege Abuse WS11
thumbnail: https://thmb.techidaily.com/802df3d91ab6daf6d905273698ce2644dd2e6aa605c087ae0dc1d7ad5065d08f.jpg
---

## Securing Administrator-Level PowerShell Execution Window in W11

 PowerShell is a task-based command-line shell and scripting language built on .NET technology. It's designed especially for system administrators and power users, so it has more features than the standard Command Prompt. If you want to use PowerShell to do anything more than basic tasks, you must run it as an administrator.

 In this guide, we'll show you ten simple ways to open an elevated PowerShell prompt on Windows 11.

## 1\. How to Open Windows PowerShell as an Administrator Using the Power User Menu

 The Power User Menu is a great way to quickly access important system tools and settings in Windows 11\. To open Windows PowerShell using the Power User Menu, do the following:

1. Right-click on**Start** to open the quick access menu. You can also access it by pressing**Win + X** on your keyboard.
2. From the menu list, select**Terminal (Admin)** .  
![Open Windows PowerShell Using Power User Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/open-windows-powershell-using-power-user-menu.jpg)
3. If UAC appears on the screen, click**Yes** to grant permission.

## 2\. How to Open Windows PowerShell as an Administrator From the Windows Search Tool

 Alternatively, you can open Windows PowerShell as an administrator using the Windows Search tool. This process is relatively simple and only takes a few steps. Here is how to do it:

1. Press the**Win + S** keyboard shortcut to open Windows Search.
2. Type "PowerShell" into the search bar.
3. From the right pane, select**Run as administrator** .  
![Open Windows PowerShell Using Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/open-windows-powershell-using-windows-search.jpg)
4. If User Account Control prompts you, click**Yes** to grant admin privileges.

 PowerShell will now open with administrative privileges. Here you can type any PowerShell command you want to execute. To exit PowerShell, type "Exit" and press**Enter** .

## 3\. How to Open Windows PowerShell as an Administrator Through the Run Command

 There is a powerful tool in Windows 11 called Run Command that lets you access files, launch programs, and adjust many system settings. You can also use it to launch Windows PowerShell as an administrator. Here's how:

1. Press**Win + R** on your keyboard. This will open the Run dialog box.
2. From here, type in "PowerShell" and press**Ctrl + Shift + Enter** key combination.  
![Open Windows PowerShell Using Run Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/open-windows-powershell-using-run-command.jpg)
3. If a confirmation prompt pops up, click**Yes** to continue. This will launch PowerShell as an administrator.
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. How to Open Windows PowerShell as an Administrator From Windows File Explorer

 Another method for opening Windows PowerShell as an administrator is through File Explorer's address bar. To do this, follow these steps:

1. Press**Win + E** on your keyboard to open Windows File Explorer.
2. In the File Explorer address bar, type the following command and press Enter.  
C:\Windows\System32\WindowsPowerShell\v1.0\
3. Next to the address bar, search for "PowerShell".
4. Right-click on the PowerShell executable file and select**Run as administrator** .  
![Open Windows PowerShell Using File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/open-windows-powershell-using-file-explorer.jpg)
5. When UAC appears, click**Yes** to grant admin rights.
<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. How to Open Windows PowerShell as an Administrator Using Command Prompt

 A command prompt lets you run almost any program or application on your Windows device. To run Windows PowerShell using this tool, follow these steps:

1. Run Command Prompt as an Administrator (see[how to open the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for instructions).  
![Open Windows PowerShell Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/open-windows-powershell-using-command-prompt.jpg)
2. In the elevated command prompt, copy and paste the given command line:  
`powershell Start-Process powershell -Verb runAs`

 As soon as you type the above command line in the elevated command prompt window, Windows PowerShell will start running as an administrator.

## 6\. How to Open Windows PowerShell as an Administrator From the Start Menu

 The Start Menu contains a wide range of software programs and files that provide a central place for launching applications and other tasks. Start Windows PowerShell with these steps:

1. Click the**Start** button at the bottom left of your screen.
2. Select**All apps** from the upper right corner.
3. Scroll down and click the**Windows Tools** option
4. Now right-click on**Windows PowerShell** and select**Run as administrator** .  
![Open Windows PowerShell Using Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/open-windows-powershell-using-control-panel.jpg)
5. The UAC will appear on the screen. If it does, click**Yes** to grant administrative privileges.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->

## 7\. How to Open Windows PowerShell as an Administrator Through Task Manager

 Task Manager is a powerful tool that can help you troubleshoot and fix problems with your PC. Besides this, you can also use this tool to launch programs on your Windows device.

 Here's how to start Windows PowerShell as an administrator with this tool.

1. Press**Ctrl + Shift + Esc** on your keyboard to open Task Manager (see[how to open the Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) for more tips).
2. Select**Run new task** from the top of the page.
3. In the pop-up menu, type "PowerShell" and check the "Create this task with administrative privileges" box.  
![Open Windows PowerShell Using Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/open-windows-powershell-using-task-manager.jpg)
4. Click**OK** and Windows PowerShell will start as an administrator.

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
## 8\. How to Open Windows PowerShell as an Administrator Using the Control Panel

 Windows Control Panel is a software program that contains many tools for managing settings on Windows. With this tool, you can launch almost any application installed on your computer. Follow these steps to open Windows PowerShell as an administrator:

1. Use one of the many[ways to open the Control Panel](https://www.makeuseof.com/windows-open-control-panel/) .
2. Click on**System and Security** .
3. Scroll down to the bottom and select**Windows Tools** .
4. Right-click on**Windows PowerShell** and select**Run as administrator** .  
![Open Windows PowerShell Using Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/open-windows-powershell-using-control-panel.jpg)
5. A User Account Control pop-up window will appear asking if you want to allow this app to make changes to your PC; click**Yes** to continue.
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 PowerShell will now launch as an administrator, and you can run commands with full privileges. If you need to exit PowerShell, type Exit and press Enter.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 9\. How to Open Windows PowerShell as an Administrator With a Desktop Shortcut

 If you often run commands that require administrative privileges, consider creating a desktop shortcut. Here's how to do it with Windows PowerShell.

1. Right-click on your Desktop and select**New > Shortcut** .
2. Next, type the following command in the "Create Shortcut" window.  
C:\WINDOWS\System32\WindowsPowerShell\v1.0\powershell.exe
3. Then click**Next** to continue.  
![Open Windows PowerShell With Desktop Shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/open-windows-powershell-with-desktop-shortcut.jpg)
4. Type in a name for the shortcut and click Finish.

 Now, whenever you want to open PowerShell as an administrator, simply double-click on the shortcut.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 10\. How to Open Windows PowerShell as an Administrator Using a Batch File

 This method involves creating a batch file to open Windows PowerShell as an administrator. Here's how to do it:

1. Press**Win + R** , type "Notepad", and hit**Enter** to open it (see[how to open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) for more ways).
2. In Notepad, copy and paste the following command line:  
Powershell.exe -Command "& {Start-Process Powershell.exe -Verb RunAs}"
3. Now click on**File** and select**Save as** from the menu list.
4. Put "PowerShell.bat" in the file name. You can name your file anything you like with the .bat extension.
5. Choose the location where you'd like to save it, and then click**Save** .  
![Open Windows PowerShell With a Batch File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/open-windows-powershell-with-a-batch-file.jpg)

 This will create the Windows PowerShell batch file. To open Windows PowerShell with administrator access, double-click the batch file. When the UAC prompt appears, click**Yes** to continue.

## Get an Elevated Windows PowerShell Running

 When you are working with files or folders that need elevated permissions, you may need to open PowerShell as an administrator. This is because some tasks require elevation in order to complete them successfully. As shown above, there are several ways to open Windows PowerShell as an administrator.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-resources.techidaily.com/new-10-groundbreaking-final-cut-pro-extensions/"><u>[New] 10 Groundbreaking Final Cut Pro Extensions</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-protecting-ideas-avoidance-of-rash-removals/"><u>[New] Protecting Ideas  Avoidance of Rash Removals</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-top-tips-mastering-music-on-instagram/"><u>[Updated] 2024 Approved  Top Tips  Mastering Music on Instagram</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-in-2024-the-ultimate-plan-to-grow-your-subscriber-base/"><u>[Updated] In 2024, The Ultimate Plan to Grow Your Subscriber Base</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-anonymous-story-consumption-navigating-through-instagram-stories-on-desktopmobile-free/"><u>2024 Approved  Anonymous Story Consumption  Navigating Through Instagram Stories on Desktop/Mobile [Free]</u></a></li>
<li><a href="https://android-location.techidaily.com/9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-sony-xperia-5-v-drfone-by-drfone-virtual/"><u>9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Sony Xperia 5 V | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/adding-command-tab-to-taskmanager-in-windows-11-pro/"><u>Adding Command Tab to TaskManager in Windows 11 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/executing-an-instant-in-place-windows-11-boost/"><u>Executing an Instant, In-Place Windows 11 Boost</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-your-mouses-dizzy-spins-in-windows/"><u>Fixing Your Mouse's Dizzy Spins in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-for-controlling-visual-cues-in-windows-11-search/"><u>Guide for Controlling Visual Cues in Windows 11 Search</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-access-your-iphone-12-when-you-forget-the-passcode-by-drfone-ios/"><u>How to Access Your iPhone 12 When You Forget the Passcode?</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-check-if-your-infinix-note-30i-is-unlocked-by-drfone-android/"><u>How To Check if Your Infinix Note 30i Is Unlocked</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-disabled-lock-screen-pause-timer/"><u>How to Fix Disabled Lock Screen Pause Timer</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-resolve-blue-screens-resulting-from-unhandled-exceptions/"><u>How to Resolve Blue Screens Resulting From Unhandled Exceptions</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-pinnacle-motorsport-replicas-top-5/"><u>In 2024, Pinnacle Motorsport Replicas (Top 5)</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-pranks-and-puns-playbook-7-clever-gags-for-video-virtuosos/"><u>In 2024, Pranks & Puns Playbook  7 Clever Gags for Video Virtuosos</u></a></li>
<li><a href="https://windows11.techidaily.com/launching-startup-repair-in-windows-a-guide/"><u>Launching Startup Repair in Windows: A Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-for-correcting-roblox-windows-problems/"><u>Methods for Correcting Roblox Windows Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-to-sound-mastery-with-windows-11-volume-control/"><u>Navigate to Sound Mastery with Windows 11 Volume Control</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-past-s-mode-a-windows-users-roadmap/"><u>Navigating Past 'S Mode': A Windows User's Roadmap</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-through-windows-11s-built-in-bios-utility-features/"><u>Navigating Through Windows 11'S Built-In BIOS Utility Features</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-game-launch-issues-for-epic/"><u>Navigating Windows Game Launch Issues for Epic</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-error-0x80070194-on-windows-onedrive/"><u>Overcoming Error 0X80070194 on Windows' OneDrive</u></a></li>
<li><a href="https://extra-tips.techidaily.com/photographic-precision-against-shake/"><u>Photographic Precision Against Shake</u></a></li>
<li><a href="https://windows11.techidaily.com/power-up-your-command-line-discover-the-top-20-cmd-commands/"><u>Power Up Your Command Line: Discover the Top 20 CMD Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-lost-steam-connections-on-pc/"><u>Quick Fixes for Lost Steam Connections on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/recovering-internet-router-settings-on-windows-pc/"><u>Recovering Internet Router Settings on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/refining-malfunctional-fixes-within-windows-1011-diagnostics/"><u>Refining Malfunctional Fixes Within Windows 10/11 Diagnostics</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-steam-cloud-connectivity-issues/"><u>Resolving Steam Cloud Connectivity Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/restarting-method-for-a-non-functional-windows-11-wi-fi-connection/"><u>Restarting Method for a Non-Functional Windows 11 Wi-Fi Connection</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-telnet-activation-in-latest-windows-versions/"><u>Simplifying Telnet Activation in Latest Windows Versions</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-video-lags-in-chromes-youtube-viewing/"><u>Solving Video Lags in Chrome's YouTube Viewing</u></a></li>
<li><a href="https://windows11.techidaily.com/startup-guide-for-windows-11s-immediate-help-tool/"><u>Startup Guide for Windows 11'S Immediate Help Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/stealthy-system-settings-hiding-windows-11-power-command/"><u>Stealthy System Settings: Hiding Windows 11 Power Command</u></a></li>
<li><a href="https://windows11.techidaily.com/stepwise-approach-enabling-wordpad-in-windows/"><u>Stepwise Approach: Enabling WordPad in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-avoid-perpetual-network-logon-errors/"><u>Strategies to Avoid Perpetual Network Logon Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/tech-tip-accessing-windows-11-sticky-notes-easily/"><u>Tech Tip: Accessing Windows 11 Sticky Notes Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-govern-devices-on-slumbering-pcs/"><u>Techniques to Govern Devices on Slumbering PCs</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/the-definitive-verdict-on-the-gaomon-pd1n560-is-it-the-perfect-pen-display-for-your-creative-ventures/"><u>The Definitive Verdict on the Gaomon PD1n560: Is It the Perfect Pen Display for Your Creative Ventures?</u></a></li>
<li><a href="https://windows11.techidaily.com/the-future-is-here-windows-11-changes-to-file-explorer/"><u>The Future Is Here: Windows 11 Changes to File Explorer</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/5-online-and-desktop-platforms-to-create-gifs/"><u>Top 15 Online & Desktop Platforms to Create GIFs</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/forming-youtube-descriptions-leveraging-template-power/"><u>Transforming YouTube Descriptions  Leveraging Template Power</u></a></li>
<li><a href="https://windows11.techidaily.com/turn-on-copy-and-paste-within-edges-protected-area-win-11-edition/"><u>Turn On Copy & Paste Within Edge's Protected Area, Win 11 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-altering-win-11-proxy-settings/"><u>Understanding and Altering Win 11 Proxy Settings</u></a></li>
<li><a href="https://win-forum.techidaily.com/understanding-the-big-four-in-social-networking-insights-on-facebook-twitter-instagram-and-youtube/"><u>Understanding the Big Four in Social Networking: Insights on Facebook, Twitter, Instagram and YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-power-of-openais-whisper-on-your-windows-pc/"><u>Unveiling the Power of OpenAI's Whisper on Your Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/why-choose-linux-without-windows-subsystem/"><u>Why Choose Linux without Windows Subsystem?</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-triple-widget-setup-made-simple/"><u>Windows 11'S Triple Widget Setup Made Simple</u></a></li>
</ul></div>
