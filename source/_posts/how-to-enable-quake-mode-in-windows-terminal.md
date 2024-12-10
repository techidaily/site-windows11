---
title: How to Enable Quake Mode in Windows Terminal
date: 2024-12-08T21:44:52.392Z
updated: 2024-12-10T18:17:30.178Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Enable Quake Mode in Windows Terminal
excerpt: This Article Describes How to Enable Quake Mode in Windows Terminal
keywords: Enable Quake Mode,Windows Terminal,Quake Modes Setup,TTY Configuration,Terminal Mods Enable,Command Terminal Tweaks,Screen Quake Simulation
thumbnail: https://thmb.techidaily.com/cb70e57700d07e1f21d91f89b112cf1e7299f5606065c397aa28c9965f8c1a6d.jpg
---

## How to Enable Quake Mode in Windows Terminal

 The Windows Terminal is a Microsoft app used for working in command-line tools like PowerShell, Command Prompt, and WSL. It includes several useful features, including Quake Mode. And if you regularly need to enter command lines, Quake Mode is an efficient way to do it.

Here's how to enable and use Quake mode in Windows Terminal.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OZQJUTr44rA?si=ADA0nD1VnXjR_sH0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Is Quake Mode, and Why Should You Use It?

 Windows Terminal is a fast and efficient way to make using command-line tools easier. You can download it from the Microsoft Store.

![multiple tabs in the windows terminal app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/window-terminal-app.jpg)

 The key features of Windows Terminal include multiple tabs, panes, and a GPU-accelerated text rendering engine. There are also custom themes, styles, and configurations. And, of course, Quake mode which was added in version 1.9.

 When enabled, Quake mode lets you quickly open a new terminal instance from within any app. The terminal window opens from the top of the screen and fills the full-screen width. You can then hide the terminal window, keeping it ready to be opened whenever you need it.

 The name Quake mode refers to the similar-looking terminal window you could open in the iD Software game, Quake.

 If you don't know what Quake is, why not check out some[classic PC FPS games?](https://www.makeuseof.com/tag/play-classic-shooters-on-modern-computer/) Great fun, even if you have a modern PC.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/dKjioJQaUh8?si=Ls_AeuvGsSyL5ny2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Open Windows Terminal in Quake Mode

There are two ways to open the Windows Terminal in Quake mode.

 The first is to press**Win + R** to open the**Run dialog** . In the text field, type**wt -w \_quake** . Make sure you include the spaces after the t and before the underscore.

 You can also open the Windows Terminal app in the normal way. You can find it in the main Start Menu apps list if you are new to the app. With the app open in standard mode, press**Win + \`** (the grave accent button below Esc on the keyboard).

![The windows terminal in quake mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-terminal-quake.jpg)

 If you want the command-line tool to be run as an administrator, you will need to use the second method. Learn how to open[Windows PowerShell or Command Prompt as an administrator](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zAzTErKy6h8?si=vi5z3M9_7fW6qiAJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Hiding and Restoring the Terminal Window

 The idea of the Quake mode is to give the ability to have a terminal window always available. Even when in a full-screen app or if you can't click a terminal shortcut in the Taskbar.

 Once the Windows Terminal is in Quake mode, you can hide it by pressing**Win + \`** . It remains active but is hidden off-screen.

To reveal the window again, press the same keyboard shortcut.

 The Quake mode terminal window stretches the entire width of the screen. By default, it will fill about half the height of the screen. Unfortunately, you can't change the width, but you can click and drag the bottom edge of the panel to make it less intrusive.

## Closing the Quake Mode Terminal Window

 As mentioned, the**Windows Key + \`** shortcut doesn't close the terminal window; it only hides it. Even closing the original Windows Terminal window won't remove the Quake mode window.

 When the Quake mode terminal window is on-screen, a terminal icon will appear in the Taskbar. You can hover over this icon and click the**X** on the peek preview window.

![The peek window for the Windows Terminal in quake mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/closing-quake-mode-window.jpg)

 If you don't see a peek preview, you can right-click on the terminal icon in the Taskbar and select**Close Window** .

 If the[Windows Taskbar is not working](https://www.makeuseof.com/tag/5-steps-fix-windows-10-taskbar-issues/) for some reason, these options won't be available. Instead, you can close the Quake mode terminal window by typing**EXIT** in the terminal and pressing**Return** .

## Start Windows Terminal in Quake Mode at Logon

 You can set the Terminal to open at logon in the PowerShell settings. But even if you have previously used Quake mode, the terminal will start in a normal window. You can get around this by creating a modified shortcut in shell:startup.

1. Type**Run** into Windows Search and open the Run Dialog.
2. Open the startup items folder by typing**shell:startup** , then click**Ok** .  
![creating a shortcut to quake mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/auto-open-quake-mode.jpg)
3. Right-click anywhere in the folder and select**New > Shortcut** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c-BHGGIC0zE?si=FzUQKZa-bx8OlKuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. For the location of the item, type:**wt.exe -w \_quake** . Click**Next** .  
![shortcut to automatically open quake mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/quake-mode-shortcut.jpg)
5. Give the shortcut a name you will recognize, such as**Terminal Quake** . Then click**Finish** .

 The next time you log on to Windows, the terminal will open automatically in Quake Mode. You can then use it, or press the**Windows + \`** shortcut to minimize it.

 If you have[disabled app execution aliases](https://www.makeuseof.com/app-execution-aliases-guide/) , you will have to type or browse to the full path for the Windows Terminal. So instead of typing**wt.exe -w \_quake** , enter **C:\\Users\\\[username\]\\AppData\\Local\\Microsoft\\WindowssApps\\wt.exe -w \_quake** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DBMTAJBx-X4?si=sje5pFJXiHzJJGbP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://extra-support.techidaily.com/updated-stock-photography-hits-and-heartfelt-tales/"><u>[Updated] Stock Photography Hits & Heartfelt Tales</u></a></li>
<li><a href="https://howto.techidaily.com/6-solutions-to-fix-error-505-in-google-play-store-on-oneplus-nord-n30-se-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Solutions to Fix Error 505 in Google Play Store on OnePlus Nord N30 SE | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/complete-epson-wf-2760-printer-drivers-for-windows-11-10-and-8-secure-download-resource/"><u>Complete Epson WF 2760 Printer Drivers for Windows 11, 10 & 8 – Secure Download Resource</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/efficiently-avoid-unproductive-gatherings-5-tips-from-industry-experts-biztech-today/"><u>Efficiently Avoid Unproductive Gatherings: 5 Tips From Industry Experts | BizTech Today</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-elevate-windows-11-audio-capabilities-dolby-atmos/"><u>How to Elevate Windows 11 Audio Capabilities - Dolby Atmos</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-a-comprehensive-guide-to-iphone-x-blacklist-removal-tips-and-tools-by-drfone-ios/"><u>In 2024, A Comprehensive Guide to iPhone X Blacklist Removal Tips and Tools</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/24-eyes-on-the-digital-winners-top-channels/"><u>In 2024, Eyes on the Digital Winners Top Channels</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-network-access-enabling-telnet-on-win-10-and-11/"><u>Mastering Network Access: Enabling Telnet on Win 10 and 11</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-your-pcs-auditory-experience-with-updated-drivers-guide/"><u>Optimize Your PC's Auditory Experience with Updated Drivers Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-auto-opens-of-windows-11s-search-bar/"><u>Preventing Auto-Opens of Windows 11'S Search Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/resetting-and-redoing-reactivating-ms-store-for-windows-users/"><u>Resetting and Redoing: Reactivating MS Store for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-functionality-of-your-windows-11-key/"><u>Restoring Functionality of Your Windows 11 Key</u></a></li>
<li><a href="https://sound-issues.techidaily.com/seamless-chats-restored-overcoming-glitches-in-your-discord-voice-connection/"><u>Seamless Chats Restored: Overcoming Glitches in Your Discord Voice Connection</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-windows-defense-plan-7-methods/"><u>The Ultimate Windows Defense Plan (7 Methods)</u></a></li>
<li><a href="https://win-web.techidaily.com/une-approche-complete-pour-resetting-ntfs-permissions-in-windows-ebn-techniques-faciles-et-eprouvees-5-options-performantes/"><u>Une Approche Complète Pour Resetting NTFS Permissions in Windows Ebn: Techniques Faciles Et Éprouvées - 5 Options Performantes</u></a></li>
<li><a href="https://windows11.techidaily.com/unfreezing-wow-update-windows-troubleshooting-guide/"><u>Unfreezing WoW Update: Windows Troubleshooting Guide</u></a></li>
<li><a href="https://change-location.techidaily.com/unova-stone-pokemon-go-evolution-list-and-how-catch-them-for-samsung-galaxy-s23-fe-drfone-by-drfone-virtual-android/"><u>Unova Stone Pokémon Go Evolution List and How Catch Them For Samsung Galaxy S23 FE | Dr.fone</u></a></li>
<li><a href="https://fox-that.techidaily.com/unsuccessful-iphoneipad-os-update-try-these-9-fixes-immediately/"><u>Unsuccessful iPhone/iPad OS Update? Try These 9 Fixes Immediately.</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-streamline-your-screens-with-a-three-column-board-setup/"><u>Windows 11: Streamline Your Screens with a Three-Column Board Setup</u></a></li>
</ul></div>

