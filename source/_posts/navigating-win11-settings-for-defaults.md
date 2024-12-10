---
title: Navigating Win11 Settings for Defaults
date: 2024-12-03T16:52:31.031Z
updated: 2024-12-10T21:12:17.274Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating Win11 Settings for Defaults
excerpt: This Article Describes Navigating Win11 Settings for Defaults
keywords: Win11 Default Config,Win11 Setup Guide,Win11 Initial Preferences,Setting Win11 Norm,Optimize Win11 Settings,Windows Defaults Tuning,Win11 Standard Options
thumbnail: https://thmb.techidaily.com/ce4adb63fa2c2ea65274491b10b565805f9f069cb38a9de890519fca2ccb2732.jpg
---

## Navigating Win11 Settings for Defaults

 Windows Terminal is the next-generation command line platform in Windows 11\. It provides an improved user experience with modern command line tools that enable you to access multiple command lines in a single window. The tool is essential for developers and administrators alike, but sometimes your terminal settings need to be reset to default.

 In this article, we will explain how to reset your Windows Terminal settings back to their original state.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/On0Jw2oMZf0?si=Pm-FJoEt8XWmtMbr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Would You Reset Your Windows Terminal?

 Windows Terminal is an amazing tool for power users and developers. It allows you to access a variety of tools, all in one place, with custom settings and themes that make it easy to work from anywhere. But over time, your Windows Terminal may become cluttered with old settings or themes that have become redundant or are no longer relevant.

 It also helps clear out any potentially harmful malware or corrupt files that might be lurking in the background of your system, hindering your productivity. By doing so, you will ensure that your computer works as fast and as smoothly as possible - giving you the most optimal experience when using this powerful tool.

 Let's now move to the below sections and see how it can be reset.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2ipTu54inBo?si=gRegjvtVq5gm_PHo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Reset Windows Terminal Settings by Clearing JSON Files

 In order to reset the settings back to the original defaults, you will need to delete the settings.json file. Here's how to do it.

1. Right click on Start and select**Terminal** from the menu list.
2. Next, click the down-arrow icon and select**Settings** .
3. From the left pane of the Settings page, click**Open JSON file** .  
![Open JSON file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-json-file.jpg)
4. If you're asked which app to use to open the file, then double-click on**Notepad** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RhLjZsruC9M?si=-861oUSfrUde2Ykt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. On the next page, select all the contents and**Delete** them.
6. Now press**Ctrl + S** on your keyboard to save it.

 Next time you open the app, a new configuration with all the default settings will be created automatically.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JNxZ4Z6BVCg?si=522oz1OPSQDhNYWT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gMS5pm0SQlQ?si=gasOo6p2agrVlIb7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://some-techniques.techidaily.com/new-highest-quality-noiseless-text-converters/"><u>[New] Highest Quality Noiseless Text Converters</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-techniques-to-apply-watermarks-on-fb-content/"><u>[Updated] 2024 Approved Techniques to Apply Watermarks on FB Content</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-maximize-game-time-top-10-ps5-external-hddssd/"><u>[Updated] In 2024, Maximize Game Time Top 10 PS5 External HDD/SSD</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-in-2024-zooming-in-clearer-faces-better-discussions/"><u>[Updated] In 2024, Zooming In Clearer Faces, Better Discussions</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/comprehensive-list-zoom-recording-must-haves/"><u>Comprehensive List Zoom Recording Must-Haves</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/helmet-up-surroundings-down-a-bikers-review-of-days-gone-during-a-global-infection-scare/"><u>Helmet Up, Surroundings Down: A Biker's Review of Days Gone During a Global Infection Scare</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-mend-interruptexception-crash-on-pcs-running-windows-1011/"><u>How to Mend INTERRUPT_EXCEPTION Crash on PCs Running Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-regain-control-over-faulty-anydesk-service/"><u>How To Regain Control Over Faulty AnyDesk Service</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-intercept-text-messages-on-vivo-y27-4g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Intercept Text Messages on Vivo Y27 4G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/master-your-windows-workspace-5-folder-tips-revealed/"><u>Master Your Windows Workspace: 5 Folder Tips Revealed</u></a></li>
<li><a href="https://fox-place.techidaily.com/mastering-the-art-of-ios-11-screenshots-a-step-by-step-tutorial-on-inbuilt-annotation-tools/"><u>Mastering the Art of iOS 11 Screenshots: A Step-by-Step Tutorial on Inbuilt Annotation Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-remedies-for-windows-nine-solutions-to-revive-your-non-responsive-keyboard-shortcuts/"><u>Quick Remedies for Windows: Nine Solutions to Revive Your Non-Responsive Keyboard Shortcuts</u></a></li>
<li><a href="https://windows11.techidaily.com/redirecting-and-reinstating-windows-1011s-ms-store/"><u>Redirecting and Reinstating Windows 10/11'S MS Store</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/step-by-step-snagging-stunning-pexels-pictures-for-2024/"><u>Step-by-Step Snagging Stunning Pexels Pictures for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-the-full-potential-of-win-for-ps1-gaming-duckstations-insight/"><u>Unleashing the Full Potential of WIN for PS1 Gaming - Duckstation's Insight</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-full-potential-of-your-computers-booting-process-with-configurations/"><u>Unlock the Full Potential of Your Computer's Booting Process with Configurations</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-aesthetic-edge-maximizing-backdrop-impact/"><u>Windows 11'S Aesthetic Edge: Maximizing Backdrop Impact</u></a></li>
</ul></div>

