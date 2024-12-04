---
title: Reverting Terminal Setup on the Latest Windows 11
date: 2024-12-02T03:14:10.766Z
updated: 2024-12-03T20:39:23.373Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/NC0rdKEQ98o?si=HYgqC8CxF_WTO5if" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/zAzTErKy6h8?si=vi5z3M9_7fW6qiAJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/AQn0MYjIfyI?si=rIdjT-qMRpjpJXXa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. Press**Enter** to execute the command.

## How to Reset Windows Terminal Settings From File Explorer

 If you don't prefer the command line process, you can use Windows File Explorer to reset the settings. In this way, the Terminal will be reset to its default settings, and you can continue using it. Here's how to do it:

1. Open Windows File Explorer. For this, right-click Start and choose**File Explorer** , or press**Win + E** on your keyboard.
2. Copy and paste the following path into the address bar:  
![Reset Windows Terminal Using File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-file-explorer.jpg)  
%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cDNwgyE0nbY?si=3k_WBhpIw3WudJot" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. On the next page, right-click on**settings.json** and select**Delete** from the context menu.

 Once you perform the above steps, Settings.json will automatically be created with the default settings.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pejPLJBLmXw?si=WD97jA3doqbMCkCX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://instagram-video-files.techidaily.com/new-gain-instagram-reel-fame-emulate-top-tiktok-trends-and-insights/"><u>[New] Gain Instagram Reel Fame Emulate Top TikTok Trends & Insights</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-acid-pro-analysis-and-related-tools-reviewed-for-2024/"><u>[Updated] ACID Pro Analysis and Related Tools Reviewed for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-connecting-twitter-videos-with-facebook-friends/"><u>[Updated] Connecting Twitter Videos with Facebook Friends</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-cut-edge-video-enhancement-merging-windows-11-and-storyremix-for-creative-edits-for-2024/"><u>[Updated] Cut-Edge Video Enhancement Merging Windows 11 & StoryRemix for Creative Edits for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-system-error-allow-blocked-program/"><u>Fix System Error: Allow Blocked Program</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-call-logs-from-asus-rog-phone-7-ultimate-by-fonelab-android-recover-call-logs/"><u>How to retrieve erased call logs from Asus ROG Phone 7 Ultimate?</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-how-to-use-pokemon-emerald-master-ball-cheat-on-apple-iphone-11-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Use Pokémon Emerald Master Ball Cheat On Apple iPhone 11 Pro | Dr.fone</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/maximizing-money-smart-tactics-for-video-monetization/"><u>Maximizing Money Smart Tactics for Video Monetization</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-screen-stumbles-winning-at-full-screen-in-sonic-frontiers-on-windows-11/"><u>Overcoming Screen Stumbles: Winning at Full-Screen in Sonic Frontiers on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-saturated-load-on-windows-chatgpt/"><u>Preventing Saturated Load on Windows ChatGPT</u></a></li>
<li><a href="https://windows11.techidaily.com/proven-methods-for-mastering-the-mspcm-toolbar-windows-11-edition/"><u>Proven Methods for Mastering the MSPCM Toolbar, Windows 11 Edition</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/cket-to-the-top-on-youtube-secrets-of-effective-seo-tactics-1-11-for-2024/"><u>Skyrocket to the Top on YouTube Secrets of Effective SEO Tactics (1-11) for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-reverse-non-downloading-challenges-with-chrome-windows/"><u>Steps to Reverse Non-Downloading Challenges with Chrome, Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-system-resources-for-better-gaming-experience/"><u>Streamlining System Resources for Better Gaming Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essentials-of-seamless-interoperability-via-nearby-share/"><u>The Essentials of Seamless Interoperability via Nearby Share</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-restoring-windows-dashboard-functionality/"><u>Tips for Restoring Windows Dashboard Functionality</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ultimate-guide-resolving-the-phase0exception-stop-error-0x00000078/"><u>Ultimate Guide: Resolving the PHASE0_EXCEPTION - Stop Error 0X00000078</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/understanding-ip-sounds-and-songs-on-instagram/"><u>Understanding IP Sounds and Songs on Instagram</u></a></li>
<li><a href="https://windows11.techidaily.com/what-are-the-best-bottleneck-calculators-for-windows-how-to-check-your-hardware-for-bottlenecks-manually/"><u>What Are the Best Bottleneck Calculators for Windows? How to Check Your Hardware for Bottlenecks Manually</u></a></li>
</ul></div>

