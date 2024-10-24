---
title: "Tutorial: Switching to Quake with Terminal"
date: 2024-10-23T17:07:17.846Z
updated: 2024-10-24T17:50:25.227Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Tutorial: Switching to Quake with Terminal"
excerpt: "This Article Describes Tutorial: Switching to Quake with Terminal"
keywords: Quake Tutorial Guide,Terminal Installation,Game Conversion Guide,Windows Gaming Update,Quake Console Commands,Terminal Based Switching,Quick Gaming Changeover
thumbnail: https://thmb.techidaily.com/6304baca930779dbe6ae3412704c6577c66eb8d788b6fe6b67667ffd209c0a5f.jpg
---

## Tutorial: Switching to Quake with Terminal

 The Windows Terminal is a Microsoft app used for working in command-line tools like PowerShell, Command Prompt, and WSL. It includes several useful features, including Quake Mode. And if you regularly need to enter command lines, Quake Mode is an efficient way to do it.

Here's how to enable and use Quake mode in Windows Terminal.

## What Is Quake Mode, and Why Should You Use It?

 Windows Terminal is a fast and efficient way to make using command-line tools easier. You can download it from the Microsoft Store.

![multiple tabs in the windows terminal app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/window-terminal-app.jpg)

 The key features of Windows Terminal include multiple tabs, panes, and a GPU-accelerated text rendering engine. There are also custom themes, styles, and configurations. And, of course, Quake mode which was added in version 1.9.

 When enabled, Quake mode lets you quickly open a new terminal instance from within any app. The terminal window opens from the top of the screen and fills the full-screen width. You can then hide the terminal window, keeping it ready to be opened whenever you need it.

 The name Quake mode refers to the similar-looking terminal window you could open in the iD Software game, Quake.

 If you don't know what Quake is, why not check out some[classic PC FPS games?](https://www.makeuseof.com/tag/play-classic-shooters-on-modern-computer/) Great fun, even if you have a modern PC.

## How to Open Windows Terminal in Quake Mode

There are two ways to open the Windows Terminal in Quake mode.

 The first is to press**Win + R** to open the**Run dialog** . In the text field, type**wt -w \_quake** . Make sure you include the spaces after the t and before the underscore.

 You can also open the Windows Terminal app in the normal way. You can find it in the main Start Menu apps list if you are new to the app. With the app open in standard mode, press**Win + \`** (the grave accent button below Esc on the keyboard).

![The windows terminal in quake mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-terminal-quake.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123729/7443" target="_top" id="2123729">
  <img src="//a.impactradius-go.com/display-ad/7443-2123729" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123729/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you want the command-line tool to be run as an administrator, you will need to use the second method. Learn how to open[Windows PowerShell or Command Prompt as an administrator](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .

## Hiding and Restoring the Terminal Window

 The idea of the Quake mode is to give the ability to have a terminal window always available. Even when in a full-screen app or if you can't click a terminal shortcut in the Taskbar.

 Once the Windows Terminal is in Quake mode, you can hide it by pressing**Win + \`** . It remains active but is hidden off-screen.

To reveal the window again, press the same keyboard shortcut.

 The Quake mode terminal window stretches the entire width of the screen. By default, it will fill about half the height of the screen. Unfortunately, you can't change the width, but you can click and drag the bottom edge of the panel to make it less intrusive.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1972665/19272" target="_top" id="1972665">
  <img src="//a.impactradius-go.com/display-ad/19272-1972665" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1972665/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Closing the Quake Mode Terminal Window

 As mentioned, the**Windows Key + \`** shortcut doesn't close the terminal window; it only hides it. Even closing the original Windows Terminal window won't remove the Quake mode window.

 When the Quake mode terminal window is on-screen, a terminal icon will appear in the Taskbar. You can hover over this icon and click the**X** on the peek preview window.

![The peek window for the Windows Terminal in quake mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/closing-quake-mode-window.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938682/19272" target="_top" id="1938682">
  <img src="//a.impactradius-go.com/display-ad/19272-1938682" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938682/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you don't see a peek preview, you can right-click on the terminal icon in the Taskbar and select**Close Window** .

 If the[Windows Taskbar is not working](https://www.makeuseof.com/tag/5-steps-fix-windows-10-taskbar-issues/) for some reason, these options won't be available. Instead, you can close the Quake mode terminal window by typing**EXIT** in the terminal and pressing**Return** .

## Start Windows Terminal in Quake Mode at Logon

 You can set the Terminal to open at logon in the PowerShell settings. But even if you have previously used Quake mode, the terminal will start in a normal window. You can get around this by creating a modified shortcut in shell:startup.

1. Type**Run** into Windows Search and open the Run Dialog.
2. Open the startup items folder by typing**shell:startup** , then click**Ok** .  
![creating a shortcut to quake mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/auto-open-quake-mode.jpg)
3. Right-click anywhere in the folder and select**New > Shortcut** .
4. For the location of the item, type:**wt.exe -w \_quake** . Click**Next** .  
![shortcut to automatically open quake mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/quake-mode-shortcut.jpg)
5. Give the shortcut a name you will recognize, such as**Terminal Quake** . Then click**Finish** .

 The next time you log on to Windows, the terminal will open automatically in Quake Mode. You can then use it, or press the**Windows + \`** shortcut to minimize it.

 If you have[disabled app execution aliases](https://www.makeuseof.com/app-execution-aliases-guide/) , you will have to type or browse to the full path for the Windows Terminal. So instead of typing**wt.exe -w \_quake** , enter **C:\\Users\\\[username\]\\AppData\\Local\\Microsoft\\WindowssApps\\wt.exe -w \_quake** .

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014849/22899" target="_top" id="2014849">
  <img src="//a.impactradius-go.com/display-ad/22899-2014849" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014849/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Using the Windows Terminal's Quake Mode

 The Windows Terminal is a great way to work in command-line apps such as PowerShell and Windows Subsystem for Linux. Being able to run it in Quake mode means that you always have access to the terminal you need, no matter what you do on your PC.

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
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-capture-every-detail-on-mac-free/"><u>[New] 2024 Approved Capture Every Detail on Mac - Free</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-breakdown-of-pewdiepies-monthly-earning-trends/"><u>[New] Breakdown of PewDiePie's Monthly Earning Trends</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-insight-into-highlighted-video-discussion-threads-for-2024/"><u>[Updated] Insight Into Highlighted Video Discussion Threads for 2024</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/6-top-ranked-danish-movies-for-mastering-dialect/"><u>6 Top-Ranked Danish Movies for Mastering Dialect</u></a></li>
<li><a href="https://blog-min.techidaily.com/comprehensive-withings-scanwatch-light-analysis-a-stylish-and-smart-hybrid-timepiece/"><u>Comprehensive Withings ScanWatch Light Analysis: A Stylish and Smart Hybrid Timepiece</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-errors-in-windows-discord-query-system/"><u>Fixing Errors in Windows' Discord Query System</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-ceasing-built-in-laptop-input-through-windows/"><u>Guide: Ceasing Built-In Laptop Input Through Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-unresponsive-clicks-in-the-latest-windows/"><u>Handling Unresponsive Clicks in the Latest Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-maximize-all-available-ram-in-your-windows-environment/"><u>How to Maximize All Available RAM in Your Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/innovative-ways-to-generate-numerous-folders-on-modern-windows-pcs/"><u>Innovative Ways to Generate Numerous Folders on Modern Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-post-update-linux-integration-on-win-11/"><u>Mastery Over Post-Update Linux Integration on Win 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/maximize-efficiency-with-google-maps-discover-why-saving-places-is-a-must-use-function/"><u>Maximize Efficiency with Google Maps – Discover Why Saving Places Is a Must-Use Function!</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-unresolved-roblox-issues-on-windows/"><u>Overcoming Unresolved Roblox Issues on Windows</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/pokemon-go-no-gps-signal-heres-every-possible-solution-on-honor-100-drfone-by-drfone-virtual-android/"><u>Pokemon Go No GPS Signal? Heres Every Possible Solution On Honor 100 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-expired-semaphore-in-win1110-systems/"><u>Troubleshooting Expired Semaphore in Win11/10 Systems</u></a></li>
<li><a href="https://techtrends.techidaily.com/ultimate-tips-and-techniques-for-optimizing-meta-quest-headset-audio/"><u>Ultimate Tips & Techniques for Optimizing Meta Quest Headset Audio</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-fix-for-error-afc-windows-11-camera-app-crash/"><u>Unveiling Fix for Error AFC: Windows 11 Camera App Crash</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-in-2024-fcpx-power-user-mastering-freeze-frames-slow-motion-and-beyond/"><u>Updated In 2024, FCPX Power User Mastering Freeze Frames, Slow Motion, and Beyond</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-is-fake-gps-location-pro-and-is-it-good-on-apple-iphone-6s-drfone-by-drfone-virtual-ios/"><u>What is Fake GPS Location Pro and Is It Good On Apple iPhone 6s? | Dr.fone</u></a></li>
</ul></div>

