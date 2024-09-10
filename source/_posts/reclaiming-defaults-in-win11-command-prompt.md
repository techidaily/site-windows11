---
title: Reclaiming Defaults in Win11 Command Prompt
date: 2024-09-09T12:02:24.639Z
updated: 2024-09-10T12:02:24.639Z
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2132161/7443" target="_top" id="2132161">
  <img src="//a.impactradius-go.com/display-ad/7443-2132161" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2132161/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Reset Windows Terminal Settings by Clearing JSON Files

 In order to reset the settings back to the original defaults, you will need to delete the settings.json file. Here's how to do it.

1. Right click on Start and select**Terminal** from the menu list.
2. Next, click the down-arrow icon and select**Settings** .
3. From the left pane of the Settings page, click**Open JSON file** .  
![Open JSON file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-json-file.jpg)
4. If you're asked which app to use to open the file, then double-click on**Notepad** .
<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139110/17108" target="_top" id="2139110">
  <img src="//a.impactradius-go.com/display-ad/17108-2139110" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139110/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. On the next page, select all the contents and**Delete** them.
6. Now press**Ctrl + S** on your keyboard to save it.

 Next time you open the app, a new configuration with all the default settings will be created automatically.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137212/26400" target="_top" id="2137212">
  <img src="//a.impactradius-go.com/display-ad/26400-2137212" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137212/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Reset Windows Terminal Settings Using Command Prompt

 The Command Prompt is a command line tool that can help you accomplish a number of tasks on your computer. It lets you run programs, manage files, and even troubleshoot problems with the operating system. We covered a lot of its functionality in our[beginner's guide to the Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) , but for now, we'll just explore resetting the Windows Terminal settings.

 To reset Windows Terminal Settings back to their defaults, follow these steps:

1. Open the Command Prompt. For this, use the Taskbar search or type "cmd" in the Run dialog.
2. In the Command Prompt window, copy and paste the following command:  
![Reset Windows Terminal Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-command-prompt.jpg)  
del /f /s /q /a "%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json"
<!-- affiliate ads begin -->
<span id="1982457">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982457.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982457">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982457.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982457%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982457/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Now press the**Enter** key to delete the settings.json file.
4. You can now exit the command prompt.

## How to Reset Windows Terminal Settings Using Windows PowerShell

 Windows PowerShell is another command line application that you can use to restore Windows Terminal Settings to their default state. To figure out how, follow these steps:

1. Open Windows PowerShell. You can do this by pressing**Win + R** , typing "PowerShell", and then pressing**Enter** . You can also one of the other[ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
2. In the PowerShell window, copy and paste the following command:  
![Reset Windows Terminal Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-powershell.jpg)  
Remove-Item -Path "$env:LOCALAPPDATA\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json" -Force
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134228/18498" target="_top" id="2134228">
  <img src="//a.impactradius-go.com/display-ad/18498-2134228" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134228/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123512/26400" target="_top" id="2123512">
  <img src="//a.impactradius-go.com/display-ad/26400-2123512" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123512/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-helps.techidaily.com/new-how-to-add-motion-blur-to-photos-in-adobe-illustrator/"><u>[New] How to Add Motion Blur to Photos In Adobe Illustrator</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-break-into-the-heart-of-a-tiktok-live-session/"><u>[Updated] 2024 Approved Break Into the Heart of a TikTok Live Session</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-efficient-screen-capture-devices-for-education/"><u>[Updated] 2024 Approved Efficient Screen Capture Devices for Education</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-2024-approved-understanding-legal-bounds-of-youtube-video-screencaps/"><u>[Updated] 2024 Approved Understanding Legal Bounds of YouTube Video Screencaps</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-lenovo-thinkphone-drfone-by-drfone-virtual-android/"><u>4 solution to get rid of pokemon fail to detect location On Lenovo ThinkPhone | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-access-denied-roblox-game-due-to-pc-settings/"><u>Fixing Access Denied Roblox Game Due To PC Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-error-2e-to-enable-windows-update/"><u>Fixing Error 2E to Enable Windows Update</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-it-xiaomi-redmi-a2plus-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix It Xiaomi Redmi A2+ Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-requested-operation-requires-elevation-error-740-on-windows-11-and-11/"><u>How to Fix the “Requested Operation Requires Elevation” Error 740 on Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-open-windows-media-player-simple-instructions/"><u>How to Open Windows Media Player: Simple Instructions</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-realme-note-50-phone-without-pin-by-drfone-android/"><u>In 2024, How to Unlock Realme Note 50 Phone without PIN</u></a></li>
<li><a href="https://windows11.techidaily.com/minimizing-delays-boosting-speed-of-windows-discord-app/"><u>Minimizing Delays: Boosting Speed of Windows Discord App</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-frequent-rainmeter-quirks-on-your-system/"><u>Navigating Through Frequent Rainmeter Quirks on Your System</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-to-file-explorer-bypassing-quick-access-with-onedrive/"><u>Navigating to File Explorer Bypassing Quick Access with OneDrive</u></a></li>
<li><a href="https://windows11.techidaily.com/no-apps-needed-windows-11-note-hacks/"><u>No Apps Needed: Windows 11 Note Hacks</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-contacts-from-meizu-21-by-fonelab-android-recover-contacts/"><u>Possible solutions to restore deleted contacts from Meizu 21.</u></a></li>
<li><a href="https://fake-location.techidaily.com/prevent-cross-site-tracking-on-nokia-c110-and-browser-drfone-by-drfone-virtual-android/"><u>Prevent Cross-Site Tracking on Nokia C110 and Browser | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-overcoming-fullscreen-obstacles-on-windows/"><u>Quick Guide: Overcoming Fullscreen Obstacles on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/redefining-initial-web-portal-for-new-windows-user/"><u>Redefining Initial Web Portal for New Windows User</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-directx-install-failures-on-pcs/"><u>Resolving DirectX Install Failures on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-accuracy-fixed-discord-games-status-errors-windows/"><u>Restoring Accuracy: Fixed Discord Games Status Errors (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-system-security-top-5-techniques-to-resolve-keys-mismatches-in-win11/"><u>Seamless System Security: Top 5 Techniques to Resolve Keys Mismatches in Win11</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/simplified-speech-to-text-integration-into-visual-content/"><u>Simplified Speech-to-Text Integration Into Visual Content</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-invisible-additional-screen/"><u>Tackling Invisible Additional Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-command-setup-easy-access-shortcuts-next-to-win11-writes/"><u>Tailored Command Setup: Easy Access Shortcuts Next to Win11' Writes</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-power-restarting-file-explorer-on-win-11/"><u>Unlock the Power: Restarting File Explorer on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-rdp-access-on-windows-11-no-password/"><u>Unlocking RDP Access on Windows 11 No Password</u></a></li>
<li><a href="https://windows11.techidaily.com/win10win11-fixing-unidentified-device-errors/"><u>Win10/Win11: Fixing Unidentified Device Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-recover-unseen-additional-monitor/"><u>Windows 11: Recover Unseen Additional Monitor</u></a></li>
</ul></div>
