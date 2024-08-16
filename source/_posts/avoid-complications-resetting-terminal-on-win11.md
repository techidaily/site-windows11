---
title: "Avoid Complications: Resetting Terminal on Win11"
date: 2024-08-15T15:15:05.367Z
updated: 2024-08-16T15:15:05.367Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Avoid Complications: Resetting Terminal on Win11"
excerpt: "This Article Describes Avoid Complications: Resetting Terminal on Win11"
keywords: Win11 Terminal Reset Guide,Avoiding Terminal Issues,Windows Terminal Troubleshooting,Fast Terminal Restart Tips,Safe Terminal Reset Steps,Preventing Terminal Errors,Secure Win11 Terminal Fix
thumbnail: https://thmb.techidaily.com/6e5f95b25124810982ee054b31aff132061c491b9479b9ba216941d7d9600153.jpg
---

## Avoid Complications: Resetting Terminal on Win11

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
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->
del /f /s /q /a "%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json"
3. Now press the**Enter** key to delete the settings.json file.
4. You can now exit the command prompt.

<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
## How to Reset Windows Terminal Settings Using Windows PowerShell

 Windows PowerShell is another command line application that you can use to restore Windows Terminal Settings to their default state. To figure out how, follow these steps:

1. Open Windows PowerShell. You can do this by pressing**Win + R** , typing "PowerShell", and then pressing**Enter** . You can also one of the other [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
2. In the PowerShell window, copy and paste the following command:  
![Reset Windows Terminal Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-powershell.jpg)  
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
Remove-Item -Path "$env:LOCALAPPDATA\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json" -Force
3. Press**Enter** to execute the command.

## How to Reset Windows Terminal Settings From File Explorer

 If you don't prefer the command line process, you can use Windows File Explorer to reset the settings. In this way, the Terminal will be reset to its default settings, and you can continue using it. Here's how to do it:

1. Open Windows File Explorer. For this, right-click Start and choose**File Explorer** , or press**Win + E** on your keyboard.
2. Copy and paste the following path into the address bar:  
![Reset Windows Terminal Using File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-file-explorer.jpg)  
<!-- affiliate ads begin -->
<span id="1793213">
					<video width="1080" height="1620" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19135-1793213">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:1080px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftinyland.pxf.io%2Fc%2F5597632%2F1793213%2F19135'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793213/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState
3. On the next page, right-click on**settings.json** and select**Delete** from the context menu.

 Once you perform the above steps, Settings.json will automatically be created with the default settings.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
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
<li><a href="https://article-tips.techidaily.com/new-in-2024-uncharted-territories-virtual-realitys-role-in-leisure/"><u>[New] In 2024, Uncharted Territories  Virtual Reality's Role in Leisure</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-storage-space-used-for-daily-extended-videography/"><u>[New] Storage Space Used for Daily Extended Videography</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-affordable-cameras-for-effective-vloggers-for-2024/"><u>[Updated] Affordable Cameras for Effective Vloggers for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-guide-to-incorited-visuals-in-text-without-cost/"><u>[Updated] In 2024, Guide to Incorited Visuals in Text Without Cost</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/10-best-luts-for-adobe-lightroom-for-2024/"><u>10 Best LUTs for Adobe LightRoom for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-itel-a05s-by-drfone-android/"><u>10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On Itel A05s</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-3-best-smartphones-for-recording-video/"><u>2024 Approved  3 Best Smartphones for Recording Video</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-36-epic-tiktok-comedy-moments/"><u>2024 Approved  36 Epic TikTok Comedy Moments</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/gamers-masterclass-advanced-recording-tips-unveiled-for-2024/"><u>Gamers' Masterclass  Advanced Recording Tips Unveiled for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722976268154-get-your-steelseries-game-controllers-upgraded-windows-10-compatible-driver-pack-available-now/"><u>Get Your SteelSeries Game Controllers Upgraded: Windows 10 Compatible Driver Pack Available Now!</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-for-a-constant-windows-printer/"><u>Guidelines for a Constant Windows Printer</u></a></li>
<li><a href="https://windows11.techidaily.com/harmonizing-windows-and-wsl-after-a-major-update/"><u>Harmonizing Windows and WSL After a Major Update</u></a></li>
<li><a href="https://windows11.techidaily.com/harnessing-automatic-deletion-for-effortless-disk-space-maintainance/"><u>Harnessing Automatic Deletion for Effortless Disk Space Maintainance</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-immediuate-switch-text-editor-to-a-dark-scheme-windows-11/"><u>How to Immediuate Switch Text Editor to a Dark Scheme, Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reactivate-a-unresponsive-windows-start-button/"><u>How to Reactivate a Unresponsive Window's Start Button</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-record-audio-while-screen-recording-in-the-windows-11-snipping-tool/"><u>How to Record Audio While Screen Recording in the Windows 11 Snipping Tool</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-music-from-samsung-galaxy-m14-5g-by-fonelab-android-recover-music/"><u>How to Rescue Lost Music from Samsung Galaxy M14 5G</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-5-best-route-generator-apps-you-should-try-on-xiaomi-14-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Best Route Generator Apps You Should Try On Xiaomi 14 | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-delete-icloud-account-on-apple-iphone-7-without-password-by-drfone-ios/"><u>In 2024, How to Delete iCloud Account On Apple iPhone 7 without Password?</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-unlock-apple-id-activation-lock-on-apple-iphone-se-2022-by-drfone-ios/"><u>In 2024, How to Unlock Apple ID Activation Lock On Apple iPhone SE (2022)?</u></a></li>
<li><a href="https://windows11.techidaily.com/masterful-tricks-for-completing-100-windows-update/"><u>Masterful Tricks for Completing 100%% Windows Update</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-installation-of-the-latest-win11-version-22h2-update/"><u>Mastering Installation of the Latest Win11 Version 22H2 Update</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-your-way-through-playstation-1-games-in-windows-with-duckstation/"><u>Mastering Your Way Through PlayStation 1 Games in Windows with Duckstation</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-reinstate-working-utorrent-installer-in-various-windows-versions/"><u>Methods to Reinstate Working uTorrent Installer in Various Windows Versions</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-windows-11-like-a-pro-essential-search-hacks-revealed/"><u>Navigate Windows 11 Like a Pro: Essential Search Hacks Revealed</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-native-tools-for-disk-replication/"><u>Navigating Native Tools for Disk Replication</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-setbacks-due-to-recent-windows-installation/"><u>Overcoming Setbacks Due to Recent Windows Installation</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/posting-videos-on-instagram-easy/"><u>Posting Videos on Instagram Easy</u></a></li>
<li><a href="https://windows11.techidaily.com/reactivating-faster-execution-of-excel-on-windows-pcs/"><u>Reactivating Faster Execution of Excel on Windows PCs</u></a></li>
<li><a href="https://driver-download.techidaily.com/scansnap-s1300i-update-made-easy-secure-and-instantaneous-drivers-for-optimal-performance/"><u>ScanSnap S1300i Update Made Easy - Secure and Instantaneous Drivers for Optimal Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-to-file-transfer-problems-on-windows-1011/"><u>Solutions to File Transfer Problems on Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-audio-recorder-crash-9999-on-windows-platforms/"><u>Solving Audio Recorder Crash 9999 on Windows Platforms</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-regaining-router-interface-on-pc/"><u>Strategies for Regaining Router Interface on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-user-experience-with-these-5-tips/"><u>Streamline Your User Experience with These 5 Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-boot-sequence-customizing-timeout-window-11/"><u>Streamlining Boot Sequence: Customizing Timeout Window 11</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-your-system-flush-steam-dns-cache-efficiently/"><u>Streamlining Your System: Flush Steam DNS Cache Efficiently</u></a></li>
<li><a href="https://windows11.techidaily.com/switching-search-highlights-onoff-windows-11-guide/"><u>Switching Search Highlights On/Off: Windows 11 Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-windows-files-delete-confirmations/"><u>Tailoring Windows Files' Delete Confirmations</u></a></li>
<li><a href="https://windows11.techidaily.com/the-experts-guide-to-navigating-with-windows-narrator/"><u>The Expert's Guide to Navigating with Windows Narrator</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-computer-tech-expert-gadget-reviews-and-guides/"><u>Tom's Computer Tech: Expert Gadget Reviews and Guides</u></a></li>
<li><a href="https://windows11.techidaily.com/top-6-strengths-of-win11-outshining-macos/"><u>Top 6 Strengths of Win11 Outshining MacOS</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-win-rpc-errors-a-5-step-guide/"><u>Troubleshooting Win RPC Errors - A 5-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/uncovering-development-power-with-windows-11s-dev-drive-insights/"><u>Uncovering Development Power with Windows 11’S Dev Drive Insights</u></a></li>
<li><a href="https://driver-download.techidaily.com/update-your-surface-book-2-drivers-easy-steps-for-a-smooth-experience/"><u>Update Your Surface Book 2 Drivers: Easy Steps for a Smooth Experience</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-mastering-final-cut-pro-how-to-flip-a-clip-in-4-simple-steps-for-2024/"><u>Updated Mastering Final Cut Pro How to Flip a Clip in 4 Simple Steps for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/ups-and-downs-on-the-desktop-frontier-comparing-w10-and-w11/"><u>Ups and Downs on the Desktop Frontier: Comparing W10 & W11</u></a></li>
<li><a href="https://windows11.techidaily.com/validate-your-gpus-mettle-using-these-6-tools-on-pc/"><u>Validate Your GPU's Mettle Using These 6 Tools on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-mastery-how-to-install-and-uninstall-optional-add-ons-successfully/"><u>Windows Mastery: How to Install and Uninstall Optional Add-Ons Successfully</u></a></li>
</ul></div>
