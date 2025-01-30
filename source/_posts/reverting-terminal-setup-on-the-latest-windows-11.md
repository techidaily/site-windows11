---
title: Reverting Terminal Setup on the Latest Windows 11
date: 2025-01-28T08:31:52.020Z
updated: 2025-01-30T05:54:11.620Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=EdMRoNAFi0Q6mP7G" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. On the next page, select all the contents and**Delete** them.
6. Now press**Ctrl + S** on your keyboard to save it.

 Next time you open the app, a new configuration with all the default settings will be created automatically.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3hS27nZVi9Y?si=_Zqj_l4a4XkPqT2S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Reset Windows Terminal Settings Using Command Prompt

 The Command Prompt is a command line tool that can help you accomplish a number of tasks on your computer. It lets you run programs, manage files, and even troubleshoot problems with the operating system. We covered a lot of its functionality in our[beginner's guide to the Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) , but for now, we'll just explore resetting the Windows Terminal settings.

 To reset Windows Terminal Settings back to their defaults, follow these steps:

1. Open the Command Prompt. For this, use the Taskbar search or type "cmd" in the Run dialog.
2. In the Command Prompt window, copy and paste the following command:  
![Reset Windows Terminal Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-command-prompt.jpg)  
del /f /s /q /a "%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json"

3. Now press the**Enter** key to delete the settings.json file.
4. You can now exit the command prompt.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3C51hzX46eY?si=o5qiDSkT7mXUGm3F" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Reset Windows Terminal Settings Using Windows PowerShell

 Windows PowerShell is another command line application that you can use to restore Windows Terminal Settings to their default state. To figure out how, follow these steps:

1. Open Windows PowerShell. You can do this by pressing**Win + R** , typing "PowerShell", and then pressing**Enter** . You can also one of the other[ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
2. In the PowerShell window, copy and paste the following command:  
![Reset Windows Terminal Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-powershell.jpg)  
Remove-Item -Path "$env:LOCALAPPDATA\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json" -Force

3. Press**Enter** to execute the command.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DCARjc5g5VI?si=9OfovbKBrpoJeXTY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Reset Windows Terminal Settings From File Explorer

 If you don't prefer the command line process, you can use Windows File Explorer to reset the settings. In this way, the Terminal will be reset to its default settings, and you can continue using it. Here's how to do it:

1. Open Windows File Explorer. For this, right-click Start and choose**File Explorer** , or press**Win + E** on your keyboard.
2. Copy and paste the following path into the address bar:  
![Reset Windows Terminal Using File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-file-explorer.jpg)  
%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/f3PFn06LijE?si=zHrmlTOzrKxXe-k4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-diy-movie-making-on-youtube-and-comparable-creative-tools/"><u>[New] In 2024, DIY Movie Making on YouTube & Comparable Creative Tools</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-mac-ready-detailed-screenflow-review-with-v4/"><u>[Updated] In 2024, Mac Ready Detailed ScreenFlow Review with V4</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-a-critical-look-at-the-action-focused-polaroid-cubeplus/"><u>2024 Approved A Critical Look at the Action-Focused Polaroid Cube+</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/anticipated-moves-for-apple-to-outshine-competitors-microsoft-and-google-in-next-years-wwdc-showcase/"><u>Anticipated Moves for Apple to Outshine Competitors Microsoft and Google in Next Year's WWDC Showcase</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-steams-read-only-mode-for-library-folders-in-win-11/"><u>Fixing Steam's Read-Only Mode for Library Folders in Win 11</u></a></li>
<li><a href="https://sound-issues.techidaily.com/fixing-the-unresponsive-microphone-issue-in-zoom-on-windows-11-and-10/"><u>Fixing the Unresponsive Microphone Issue in Zoom on Windows 11 and 10</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-manage-windows-11s-online-scanning-option/"><u>How to Manage Windows 11'S Online Scanning Option</u></a></li>
<li><a href="https://windows11.techidaily.com/immersive-soundwaves-dolby-atmos-in-windows-1011/"><u>Immersive Soundwaves: Dolby Atmos in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/make-every-day-better-with-these-6-must-have-android-apps-for-window-11/"><u>Make Every Day Better with These 6 Must-Have Android Apps for Window 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-rectifying-wow-crashes-error-132/"><u>Mastering the Art of Rectifying WoW Crashes: Error 132</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-discover-free-sound-fx-websites-and-integrate-with-final-cut-pro/"><u>New Discover Free Sound FX Websites and Integrate with Final Cut Pro</u></a></li>
<li><a href="https://article-files.techidaily.com/quintessential-5-filters-for-depth-video/"><u>Quintessential 5 Filters for Depth Video</u></a></li>
<li><a href="https://windows11.techidaily.com/swiftly-transform-heic-pics-to-jpeg-with-windows-11-tech/"><u>Swiftly Transform HEIC Pics to JPEG with Windows 11 Tech</u></a></li>
<li><a href="https://windows11.techidaily.com/triumph-in-tpm-deactivation-on-windows-11/"><u>Triumph in TPM Deactivation on Windows 11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/unlocking-made-easy-the-best-10-apps-for-unlocking-your-vivo-v30-device-by-drfone-android/"><u>Unlocking Made Easy The Best 10 Apps for Unlocking Your Vivo V30 Device</u></a></li>
</ul></div>

