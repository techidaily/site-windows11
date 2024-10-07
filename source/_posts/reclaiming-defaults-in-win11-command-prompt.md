---
title: Reclaiming Defaults in Win11 Command Prompt
date: 2024-10-04T17:05:38.933Z
updated: 2024-10-06T19:49:57.158Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reclaiming Defaults in Win11 Command Prompt
excerpt: This Article Describes Reclaiming Defaults in Win11 Command Prompt
keywords: Win11 CMD Reclamation,Command Prompt Windows,Reclaiming Default Values,Command Line Fixes,System Commands Reset,Default Settings Restore,Win11 Console Adjustments
thumbnail: https://thmb.techidaily.com/8614a77f9e633f7b68cb429db560c3992306d2b5be6c80ea6d2432a854e4bb42.jpg
---

## Reclaiming Defaults in Win11 Command Prompt

 Windows Terminal is the next-generation command line platform in Windows 11\. It provides an improved user experience with modern command line tools that enable you to access multiple command lines in a single window. The tool is essential for developers and administrators alike, but sometimes your terminal settings need to be reset to default.

 In this article, we will explain how to reset your Windows Terminal settings back to their original state.

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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137211/26400" target="_top" id="2137211">
  <img src="//a.impactradius-go.com/display-ad/26400-2137211" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137211/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2047406/19272" target="_top" id="2047406">
  <img src="//a.impactradius-go.com/display-ad/19272-2047406" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047406/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Reset Windows Terminal Settings Using Windows PowerShell

 Windows PowerShell is another command line application that you can use to restore Windows Terminal Settings to their default state. To figure out how, follow these steps:

1. Open Windows PowerShell. You can do this by pressing**Win + R** , typing "PowerShell", and then pressing**Enter** . You can also one of the other[ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
2. In the PowerShell window, copy and paste the following command:  
![Reset Windows Terminal Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-powershell.jpg)  
Remove-Item -Path "$env:LOCALAPPDATA\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json" -Force

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1868575/19272" target="_top" id="1868575">
  <img src="//a.impactradius-go.com/display-ad/19272-1868575" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868575/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. Press**Enter** to execute the command.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105859/7443" target="_top" id="2105859">
  <img src="//a.impactradius-go.com/display-ad/7443-2105859" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105859/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://fox-blue.techidaily.com/updated-preventing-disorientation-in-virtual-environments-for-2024/"><u>[Updated] Preventing Disorientation in Virtual Environments for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/champions-5-wearable-devices-for-top-fpv-racing/"><u>Champion's 5 Wearable Devices for Top FPV Racing</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/diy-fixes-how-to-resolve-the-critical-stop-error-phase0exception-and-code-0x00000078/"><u>DIY Fixes: How to Resolve the Critical Stop Error PHASE0_EXCEPTION and Code 0X00000078</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/drive-participation-with-artisanal-story-inquiries-for-2024/"><u>Drive Participation with Artisanal Story Inquiries for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-unable-to-launch-java-vm-on-windows-systems/"><u>Fixing Unable to Launch Java VM on Windows Systems</u></a></li>
<li><a href="https://hardware-help.techidaily.com/getting-the-newest-canon-mg3n-driver-version-free-download-instructions/"><u>Getting the Newest Canon MG3n Driver Version – Free Download Instructions</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-to-fix-non-working-google-writes-on-pc/"><u>Guidelines to Fix Non-Working Google' Writes on PC</u></a></li>
<li><a href="https://fox-blue.techidaily.com/in-2024-cutting-edge-tools-for-watchable-gaming/"><u>In 2024, Cutting-Edge Tools for Watchable Gaming</u></a></li>
<li><a href="https://windows11.techidaily.com/overhauling-the-default-administrator-model-for-windows-users/"><u>Overhauling the Default Administrator Model for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-your-input-not-recognized-by-vlc/"><u>Resolving Windows: Your Input Not Recognized by VLC</u></a></li>
<li><a href="https://windows11.techidaily.com/secrets-of-storage-the-top-6-win11-techniques-for-capturing-file-and-directory-paths/"><u>Secrets of Storage: The Top 6 Win11 Techniques for Capturing File & Directory Paths</u></a></li>
<li><a href="https://techidaily.com/three-methods-to-recover-lost-data-on-gionee-f3-pro-by-fonelab-android-recover-data/"><u>Three methods to recover lost data on Gionee F3 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/traversing-the-digital-landscape-with-ease/"><u>Traversing the Digital Landscape with Ease</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/unleashing-lightning-speeds-with-the-netgear-nighthawk-rax120-an-in-depth-analysis/"><u>Unleashing Lightning Speeds with the Netgear Nighthawk RAX120: An In-Depth Analysis</u></a></li>
</ul></div>

