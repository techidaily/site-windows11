---
title: Reverting Terminal Setup on the Latest Windows 11
date: 2025-02-26T11:02:06.071Z
updated: 2025-03-02T01:21:22.118Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reverting Terminal Setup on the Latest Windows 11
excerpt: This Article Describes Reverting Terminal Setup on the Latest Windows 11
keywords: Windows 11 Setup Revert,Terminal Configuration Back,Windows Update Changes,Resetting Win11 Terminal,Uninstalling Latest Updates,Undo OS Tweaks,Windows Settings Restore
thumbnail: https://thmb.techidaily.com/b55c24263d5a9a2d0075e95ed2cba33cc134d0a45b0aad772e33e1d818e77a97.jpg
---

## Reverting Terminal Setup on the Latest Windows 11

 Windows Terminal is the next-generation command line platform in Windows 11\. It provides an improved user experience with modern command line tools that enable you to access multiple command lines in a single window. The tool is essential for developers and administrators alike, but sometimes your terminal settings need to be reset to default.

 In this article, we will explain how to reset your Windows Terminal settings back to their original state.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Why Would You Reset Your Windows Terminal?

 Windows Terminal is an amazing tool for power users and developers. It allows you to access a variety of tools, all in one place, with custom settings and themes that make it easy to work from anywhere. But over time, your Windows Terminal may become cluttered with old settings or themes that have become redundant or are no longer relevant.

 It also helps clear out any potentially harmful malware or corrupt files that might be lurking in the background of your system, hindering your productivity. By doing so, you will ensure that your computer works as fast and as smoothly as possible - giving you the most optimal experience when using this powerful tool.

 Let's now move to the below sections and see how it can be reset.

## How to Reset Windows Terminal Settings by Clearing JSON Files

 In order to reset the settings back to the original defaults, you will need to delete the settings.json file. Here's how to do it.

1. Right click on Start and select**Terminal** from the menu list.
2. Next, click the down-arrow icon and select**Settings** .
3. From the left pane of the Settings page, click**Open JSON file** .  
![Open JSON file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-json-file.jpg)
4. If you're asked which app to use to open the file, then double-click on**Notepad** .

5. On the next page, select all the contents and**Delete** them.
6. Now press**Ctrl + S** on your keyboard to save it.

 Next time you open the app, a new configuration with all the default settings will be created automatically.

## How to Reset Windows Terminal Settings Using Command Prompt

 The Command Prompt is a command line tool that can help you accomplish a number of tasks on your computer. It lets you run programs, manage files, and even troubleshoot problems with the operating system. We covered a lot of its functionality in our[beginner's guide to the Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) , but for now, we'll just explore resetting the Windows Terminal settings.

 To reset Windows Terminal Settings back to their defaults, follow these steps:

1. Open the Command Prompt. For this, use the Taskbar search or type "cmd" in the Run dialog.
2. In the Command Prompt window, copy and paste the following command:  
![Reset Windows Terminal Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-command-prompt.jpg)  
del /f /s /q /a "%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json"

3. Now press the**Enter** key to delete the settings.json file.
4. You can now exit the command prompt.

## How to Reset Windows Terminal Settings Using Windows PowerShell

 Windows PowerShell is another command line application that you can use to restore Windows Terminal Settings to their default state. To figure out how, follow these steps:

1. Open Windows PowerShell. You can do this by pressing**Win + R** , typing "PowerShell", and then pressing**Enter** . You can also one of the other[ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
2. In the PowerShell window, copy and paste the following command:  
![Reset Windows Terminal Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-powershell.jpg)  
Remove-Item -Path "$env:LOCALAPPDATA\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json" -Force

3. Press**Enter** to execute the command.

## How to Reset Windows Terminal Settings From File Explorer

 If you don't prefer the command line process, you can use Windows File Explorer to reset the settings. In this way, the Terminal will be reset to its default settings, and you can continue using it. Here's how to do it:

1. Open Windows File Explorer. For this, right-click Start and choose**File Explorer** , or press**Win + E** on your keyboard.
2. Copy and paste the following path into the address bar:  
![Reset Windows Terminal Using File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-file-explorer.jpg)  
%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState

3. On the next page, right-click on**settings.json** and select**Delete** from the context menu.

 Once you perform the above steps, Settings.json will automatically be created with the default settings.

## Resetting the Windows Terminal, Made Easy

 After reading this post, you now know some useful tips that will help you reset the terminal to default settings in Windows 11\. Try them out and find out which one works best for you.

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
<li><a href="https://fox-direct.techidaily.com/updated-2024-approved-seamless-steps-to-gather-thousands-of-videos-on-tiktok/"><u>[Updated] 2024 Approved Seamless Steps to Gather Thousands of Videos on TikTok</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-a-comprehensive-guide-to-mastering-vivocuts-new-capabilities-for-2024/"><u>[Updated] A Comprehensive Guide to Mastering VivoCut's New Capabilities for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-elevate-performance-top-ranked-os-xwin-mods-for-srt-systems/"><u>[Updated] Elevate Performance Top-Ranked OS X/Win Mods for SRT Systems</u></a></li>
<li><a href="https://win-deluxe.techidaily.com/best-free-software-options-for-reliable-computer-backups-a-comprehensive-guide/"><u>Best Free Software Options for Reliable Computer Backups: A Comprehensive Guide</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/bridging-the-gap-integrating-spotify-and-youtube-music-playlists/"><u>Bridging the Gap Integrating Spotify and YouTube Music Playlists</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-utorrent-non-installation-on-pcs-running-windows-os/"><u>Fixing uTorrent Non-Installation on PCs Running Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-eliminate-call-not-successful-problems-in-windows-malwarebytes/"><u>How to Eliminate Call Not Successful Problems in Windows Malwarebytes</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-merge-windows-id-with-microsoft-profile/"><u>How to Merge Windows ID with Microsoft Profile</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-update-your-msi-b350-toms-hardware-graphics-card-on-windows-117-driver-downloads-inside/"><u>How to Update Your MSI B350 TOM'S Hardware Graphics Card on Windows 11/7 - Driver Downloads Inside!</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-did-your-apple-iphone-11-passcode-change-itself-unlock-it-now-drfone-by-drfone-ios/"><u>In 2024, Did Your Apple iPhone 11 Passcode Change Itself? Unlock It Now | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-your-network-the-windows-iscsi-initiator-explained/"><u>Mastering Your Network: The Windows iSCSI Initiator Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/resize-images-in-win11-a-step-by-step/"><u>Resize Images in Win11: A Step-by-Step</u></a></li>
<li><a href="https://fox-zero.techidaily.com/shaping-a-civilization-the-enduring-legacy-of-the-han-dynasty-in-chinese-culture-with-yl-solutions/"><u>Shaping a Civilization: The Enduring Legacy of the Han Dynasty in Chinese Culture with YL Solutions</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-definitive-guide-to-fugeteks-high-end-selfie-stick-ft-568-reviewed/"><u>The Definitive Guide to Fugetek's High-End Selfie Stick - FT-568 Reviewed</u></a></li>
<li><a href="https://windows11.techidaily.com/tutorial-initiating-clipboard-operations-within-microsoft-edges-protected-environment-windows-11/"><u>Tutorial: Initiating Clipboard Operations Within Microsoft Edge's Protected Environment, Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-future-of-shopping-microsoft-ai-hub/"><u>Unveiling the Future of Shopping: Microsoft AI Hub</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-keyboard-graphic-helper/"><u>Windows 11'S Keyboard Graphic Helper</u></a></li>
</ul></div>

