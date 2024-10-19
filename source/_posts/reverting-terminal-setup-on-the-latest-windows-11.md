---
title: Reverting Terminal Setup on the Latest Windows 11
date: 2024-10-15T23:08:21.354Z
updated: 2024-10-19T01:04:36.326Z
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

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148645/16836" target="_top" id="2148645">
  <img src="//a.impactradius-go.com/display-ad/16836-2148645" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148645/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137201/26400" target="_top" id="2137201">
  <img src="//a.impactradius-go.com/display-ad/26400-2137201" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137201/26400" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<span id="1983539">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983539.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983539">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983539.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983539%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983539/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://aligracehair.sjv.io/c/5597632/2135408/19272" target="_top" id="2135408">
  <img src="//a.impactradius-go.com/display-ad/19272-2135408" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135408/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://article-knowledge.techidaily.com/updated-in-2024-elevate-your-experience-with-windows-11-games/"><u>[Updated] In 2024, Elevate Your Experience with Windows 11 Games</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/boost-views-through-effective-youtube-thumbnail-selection-for-2024/"><u>Boost Views Through Effective YouTube Thumbnail Selection for 2024</u></a></li>
<li><a href="https://fox-that.techidaily.com/dealing-with-iphones-slow-display-shutdown-here-are-effective-fixes/"><u>Dealing with iPhone's Slow Display Shutdown? Here Are Effective Fixes!</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-error-495-while-downloadupdating-android-apps-on-nokia-105-classic-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Error 495 While Download/Updating Android Apps On Nokia 105 Classic | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-rectifying-fatal-javascript-glitch-in-win-based-discord/"><u>Mastering the Art of Rectifying Fatal Javascript Glitch in Win-Based Discord</u></a></li>
<li><a href="https://fix-guide.techidaily.com/play-store-not-working-on-infinix-smart-8-pro-8-solutions-inside-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Not Working On Infinix Smart 8 Pro? 8 Solutions Inside | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/samsung-phone-debut-a-glimpse-into-cutting-edge-technology-and-design/"><u>Samsung Phone Debut: A Glimpse Into Cutting-Edge Technology and Design</u></a></li>
<li><a href="https://fox-that.techidaily.com/simplify-your-digital-album-by-merging-duplicate-personal-photographs-on-iphonemac/"><u>Simplify Your Digital Album by Merging Duplicate Personal Photographs on iPhone/Mac</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-windows-11-search-issue-unlocking-the-settings-apps-search-bar/"><u>Solving Windows 11 Search Issue: Unlocking the Settings App's Search Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-solutions-overcome-blue-screen-on-win11s-hypervisor/"><u>Swift Solutions: Overcome Blue Screen on Win11's HYPERVISOR</u></a></li>
<li><a href="https://windows11.techidaily.com/tackle-microsoft-store-login-challenges/"><u>Tackle Microsoft Store Login Challenges</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/unlock-your-disabled-apple-iphone-12-mini-without-itunes-in-5-ways-by-drfone-ios/"><u>Unlock Your Disabled Apple iPhone 12 mini Without iTunes in 5 Ways</u></a></li>
</ul></div>

