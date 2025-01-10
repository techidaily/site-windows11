---
title: "Configuring Terminal in Win11: Start Fresh"
date: 2025-01-06T21:13:06.436Z
updated: 2025-01-10T16:41:10.851Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Configuring Terminal in Win11: Start Fresh"
excerpt: "This Article Describes Configuring Terminal in Win11: Start Fresh"
keywords: Windows Terminal Setup Guide,Win11 Terminal Configuration,Fresh Win11 Terminal Start,Revamping Terminal in Win11,New Terminal Setup Win11,Initializing Win11 Terminal,Win11 Terminal Freshness
thumbnail: https://thmb.techidaily.com/474c5054a0eaa723712bc3725331bacf73663ebfef0031bd8bc1879804e39c8f.jpg
---

## Configuring Terminal in Win11: Start Fresh

 Windows Terminal is the next-generation command line platform in Windows 11\. It provides an improved user experience with modern command line tools that enable you to access multiple command lines in a single window. The tool is essential for developers and administrators alike, but sometimes your terminal settings need to be reset to default.

 In this article, we will explain how to reset your Windows Terminal settings back to their original state.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UUPt2zKtJ5k?si=LLHdsFDLzVByJsKj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

 The Command Prompt is a command line tool that can help you accomplish a number of tasks on your computer. It lets you run programs, manage files, and even troubleshoot problems with the operating system. We covered a lot of its functionality in our [beginner's guide to the Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) , but for now, we'll just explore resetting the Windows Terminal settings.

 To reset Windows Terminal Settings back to their defaults, follow these steps:

1. Open the Command Prompt. For this, use the Taskbar search or type "cmd" in the Run dialog.
2. In the Command Prompt window, copy and paste the following command:  
![Reset Windows Terminal Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-command-prompt.jpg)  
del /f /s /q /a "%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json"
3. Now press the**Enter** key to delete the settings.json file.
4. You can now exit the command prompt.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nWu29cqFjZA?si=TNZyCbPq68PQ0JIb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Reset Windows Terminal Settings Using Windows PowerShell

 Windows PowerShell is another command line application that you can use to restore Windows Terminal Settings to their default state. To figure out how, follow these steps:

1. Open Windows PowerShell. You can do this by pressing**Win + R** , typing "PowerShell", and then pressing**Enter** . You can also one of the other [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
2. In the PowerShell window, copy and paste the following command:  
![Reset Windows Terminal Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-powershell.jpg)  
Remove-Item -Path "$env:LOCALAPPDATA\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json" -Force

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K4lRBnNnd9k?si=5e0MbdOz-fF6Ry_k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. Press**Enter** to execute the command.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fo4lNZ84x9Q?si=WdcYPZp-9VJnZEnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Reset Windows Terminal Settings From File Explorer

 If you don't prefer the command line process, you can use Windows File Explorer to reset the settings. In this way, the Terminal will be reset to its default settings, and you can continue using it. Here's how to do it:

1. Open Windows File Explorer. For this, right-click Start and choose**File Explorer** , or press**Win + E** on your keyboard.
2. Copy and paste the following path into the address bar:  
![Reset Windows Terminal Using File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-file-explorer.jpg)  
%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState
3. On the next page, right-click on**settings.json** and select**Delete** from the context menu.

 Once you perform the above steps, Settings.json will automatically be created with the default settings.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/r_wWybMqZEM?si=0nPjCQDLS2MCaQbG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-direct.techidaily.com/1718569497187-new-how-to-listen-to-podcasts-on-your-iphone-for-2024/"><u>[New] How to Listen to Podcasts on Your iPhone for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-screencapture-hq-top-browsers-for-digital-footprints/"><u>[New] ScreenCapture HQ Top Browsers for Digital Footprints</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-visualloger-12-professional/"><u>[Updated] 2024 Approved VisualLoger 12 Professional</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-essential-strategies-for-profitable-youtube-videos-for-2024/"><u>[Updated] Essential Strategies for Profitable YouTube Videos for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/identifying-your-cpus-gen-in-windows-top-8-techniques/"><u>Identifying Your CPU's Gen in Windows: Top 8 Techniques</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-changefake-your-vivo-y100a-location-on-viber-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change/Fake Your Vivo Y100A Location on Viber | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-stop-google-chrome-from-tracking-your-location-on-xiaomi-civi-3-disney-100th-anniversary-edition-drfone-by-drfone-virtual-android/"><u>In 2024, How to Stop Google Chrome from Tracking Your Location On Xiaomi Civi 3 Disney 100th Anniversary Edition? | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/leading-visual-voice-mail-solutions-for-the-current-year-2024/"><u>Leading Visual Voice Mail Solutions for the Current Year, 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/master-snippet-pasting-windows-shortcuts-for-speed/"><u>Master Snippet Pasting: Windows Shortcuts for Speed</u></a></li>
<li><a href="https://windows11.techidaily.com/masterful-icloud-setup-tips-for-windows-os/"><u>Masterful iCloud Setup Tips for Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-color-calibration-challenges/"><u>Overcoming Windows Color Calibration Challenges</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/preventing-unwanted-filming-in-quicktime/"><u>Preventing Unwanted Filming in QuickTime</u></a></li>
<li><a href="https://win-solutions.techidaily.com/quick-troubleshooting-guide-for-palworld-launch-issues/"><u>Quick Troubleshooting Guide for Palworld Launch Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-graphics-connectivity-dxgi-fix-methods/"><u>Restoring Graphics Connectivity: DXGI Fix Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/revealing-resolution-riddles-making-windows-monitor-work/"><u>Revealing Resolution Riddles: Making Windows Monitor Work</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-and-simplifying-docker-operations-on-windows/"><u>Streamlining and Simplifying Docker Operations on Windows</u></a></li>
<li><a href="https://fox-direct.techidaily.com/the-ultimate-guide-to-windows-10-picture-and-media-importer/"><u>The Ultimate Guide to Windows 10 Picture & Media Importer</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-to-regain-access-to-mb-services-on-win11-systems/"><u>Tips to Regain Access to MB Services on Win11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-full-potential-of-emojis-in-windows-11/"><u>Unleash Full Potential of Emojis in Windows 11</u></a></li>
</ul></div>

