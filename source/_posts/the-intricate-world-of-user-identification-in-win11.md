---
title: The Intricate World of User Identification in Win11
date: 2024-08-22T21:40:17.359Z
updated: 2024-08-23T21:40:17.359Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Intricate World of User Identification in Win11
excerpt: This Article Describes The Intricate World of User Identification in Win11
keywords: Windows ID Basics,Win11 User Recognition,Identity Verification Win11,Advanced User Profiles,Win11 Authentication Features,Identifying Users in Win11,Secure Login in Win11
thumbnail: https://thmb.techidaily.com/b366957cb2f5f0bbc845d34641faf6413a6383aa8049e6555ff0f80bdf97ed47.jpg
---

## The Intricate World of User Identification in Win11

 The Security Identifier (SID) is a unique number tied to a user account on a Windows PC. It comes in handy while finding and identifying a user on Windows, and no two SIDs can be identical.

 The most common means to find a SID on Windows is using the "whoami"command. But there are several other ways to view the SID of one or all users on your Windows PC. Let’s discuss them in detail.

## 1\. Using the Command Prompt

 The simplest way to check the SID of the currently logged-in user on your PC is by using the whoami command. It will display the SID with the help of the “user” argument with the command. The only drawback is that it cannot display more than one user’s SID.

 Here’s how to do it:

1. Press **Win + R** to [launch the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **cmd** in the text box and press the **Ctrl + Shift + Enter** keys to open Command Prompt.
2. The User Account Control window will pop up. Click on the **Yes** button to open the app with admin rights if prompted.
3. Now, type the following command to view the SID of the currently logged-in user account:  
whoami /user  
![Check SID Using the Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-sid-using-the-command-prompt-1.jpg)
4. You will see the currently logged-in user’s name and the corresponding SID. You can directly select and copy the text from the Command Prompt window. But if you want to export the details to a text file for future use, you can do so by entering the following command:  
whoami /user > C:\SID.txt
5. The above command will create a text file named **SID** in the **C** drive. You can open it with Notepad or any other text editor app.
6. Close the Command Prompt window.

## 2\. Using WMIC

 You can easily view the SID of all the users or a single user on your PC using the WMIC command-line tool. You don’t need to [open an elevated Command Prompt window](https://www.makeuseof.com/windows-run-command-prompt-admin/) for using WMIC to view the SIDs.

 Repeat the following steps to do so:

1. Right-click on the **Start** button to open the Power User menu. Click on the **Terminal** option.
2. Type the following command and press the **Enter** key to execute it:  
wmic useraccount get name,sid
3. The above command will display the user name and the corresponding SID of all the user accounts. In our instance, it shows three local accounts (a,b, and t), and the administrator, guest, default account, and WDAGUtility account.
4. You can export all this data into a text file on the D drive by executing the following command:  
wmic useraccount get name,sid > D:\SID.txt  
![Check SID Using the WMIC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-sid-using-the-wmic-1.jpg)
5. If you want to get the details of a specific user account on your PC, the syntax of the command is:  
wmic useraccount where name="USER" get sid
6. Replace the **USER** part of the command with an actual username. In our case, the command becomes:  
wmic useraccount where name="a" get sid  
![Check SID Using the WMIC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-sid-using-the-wmic-2-1.jpg)
7. Close the Command Prompt window.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Using a PowerShell Cmdlet

 PowerShell offers the Get-WmiObject cmdlet using which you can view the SID of all the user accounts on a Windows PC. Like the WMIC method, you can view the SIDs of all users with a single command.

 Repeat the following steps to do so:

1. Press **Win + R** to launch the Run dialog box. Type **powershell** in the text box and press the **Ctrl + Shift + Enter** keys to open PowerShell.
2. The User Account Control window will pop up. Click on the **Yes** button to open the app with admin rights if prompted.
3. Type the following command and press the Enter key:  
Get-WmiObject win32_useraccount | Select name,sid  
![Check SID Using the Powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-sid-using-the-powershell-1.jpg)
4. The above command will display all the user accounts and their respective SIDs. To export the results in a text file, execute the following command:  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
Get-WmiObject win32_useraccount | Select name,sid > C:\SID.txt
5. The command will save the file in the **C** drive. Visit the location using File Explorer and open the file in a text editor app.
6. Close the PowerShell window.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. Using the Registry Editor

 If the Command Prompt or [PowerShell isn’t working on your PC](https://www.makeuseof.com/windows-powershell-has-stopped-working-error-fix/), you can use the Registry Editor to view all the SIDs on your PC. This method isn’t as convenient as viewing the complete SID list in the terminal or in a text file. You will have to do some manual digging to find the SIDs and their user name.

 Here’s how to do it:

1. Press **Win + R** to launch the Run dialog box. Type **regedit** in the text box and press the **Ctrl + Shift + Enter** keys simultaneously.
2. The User Account Control window will pop up. Click on the **Yes** button.
3. Go to the address bar at the top, paste the following path, and press the **Enter** key:  
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\ProfileList
4. Click on any **SID** subkey to select it and go to the right pane.
5. Now, find the **ProfileImagePath** value and double-click on it to open the **Edit** window. You will see the user name of the SID in the **Value Data** field.  
![Check SID Using Regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-sid-using-regedit-1.jpg)
6. Similarly, you can check the other SID keys and open their **ProfileImagePath** value to find their corresponding user name.
7. Close the Registry Editor app afterward.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
## 5\. Using a Batch File

 If you find the Terminal route cumbersome, you can create a batch file to display the SID of all the users at once. Repeat the following steps to create a batch file:

1. Press **Win + D** to switch to the Desktop.
2. Right-click on an empty space on the desktop and click on the **New > Text Document** option.
3. A new text file will appear on the desktop. Double-click on the file to open it in a Notepad window.
4. Now, paste the following code snippet into the Notepad file:  
`@echo off  
 cmd.exe /k wmic useraccount get name,sid  
 pause`
5. Press **Ctrl + Shift + S** to open the **Save as** window. Keep the file name as **SID.bat** and the **Save as Type** field as **All Files**.  
![Check SID Using the Batch FIle](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-sid-using-the-batch-file-1.jpg)
6. Navigate to the folder location where you saved the batch file. Double-click on it to run it.
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. A Terminal window will launch and display all the users on your PC and their respective SIDs.  
![Check SID Using the Batch FIle](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-sid-using-the-batch-file-2-1.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->
## Check SIDs in a Jiffy

 These were the methods to check the SID of a user or all the users on your Windows PC. Use the first method if you only want to see the currently logged-in user’s SID.

 The rest of the methods will display the SID of one or all the users on your PC. Lastly, create a batch file to display the SIDs of all users whenever you need it.

 The most common means to find a SID on Windows is using the "whoami"command. But there are several other ways to view the SID of one or all users on your Windows PC. Let’s discuss them in detail.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-simple-steps-to-document-online-meetings-on-os-xwindows/"><u>[New] 2024 Approved  Simple Steps to Document Online Meetings on OS X/Windows</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-windowsmac-interface-for-srt-file-access/"><u>[New] 2024 Approved  Windows/Mac Interface for SRT File Access</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-amplify-impact-strategies-for-instagram-video-waves-for-2024/"><u>[New] Amplify Impact  Strategies for Instagram Video Waves for 2024</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-change-twitter-video-box-art-for-2024/"><u>[New] Change Twitter Video Box Art for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-top-mp4-to-fb-transcoder-for-2024/"><u>[New] Top MP4-to-FB Transcoder for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-capturing-movie-scenes-as-single-image-snapshots-windows-10/"><u>[Updated] Capturing Movie Scenes as Single Image Snapshots (Windows 10)</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-ice-warriors-battle-the-spectacular-winter-olympics-snowboard-showdown/"><u>[Updated] Ice Warriors Battle - The Spectacular Winter Olympics Snowboard Showdown</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-optimal-transfer-methods-iphone-camera-roll-to-snapchat-journey/"><u>[Updated] In 2024, Optimal Transfer Methods  IPhone Camera Roll to Snapchat Journey</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-surf-in-focus-cutting-edge-action-cameras/"><u>[Updated] Surf in Focus  Cutting-Edge Action Cameras</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-tips-and-tricks-elevating-your-images-with-text-editing/"><u>2024 Approved  Tips & Tricks  Elevating Your Images with Text Editing</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-airplane-mode-turn-off-gps-location-on-xiaomi-redmi-note-12t-pro-drfone-by-drfone-virtual-android/"><u>Does Airplane Mode Turn off GPS Location On Xiaomi Redmi Note 12T Pro? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-insights-selecting-the-right-os-for-gaming-glory/"><u>Expert Insights: Selecting the Right OS for Gaming Glory</u></a></li>
<li><a href="https://windows11.techidaily.com/festive-glamour-unveiled-in-decorative-windows/"><u>Festive Glamour Unveiled in Decorative Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-device-freeze-addressing-error-0x887a0006-windows/"><u>Fixing Device Freeze: Addressing Error 0X887A0006 Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-error-lost-access-to-ubisoft-game-launcher/"><u>Fixing Windows Error: Lost Access to Ubisoft Game Launcher</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-error-code-e84-on-steam-for-windows/"><u>How to Fix the Error Code E84 on Steam for Windows</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-realme-narzo-n55-drfone-by-drfone-virtual-android/"><u>How to Get and Use Pokemon Go Promo Codes On Realme Narzo N55 | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-share-location-in-messenger-on-xiaomi-redmi-note-12r-drfone-by-drfone-virtual-android/"><u>How to Share Location in Messenger On Xiaomi Redmi Note 12R? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-sharefake-gps-on-uber-for-lava-yuva-2-drfone-by-drfone-virtual-android/"><u>How to share/fake gps on Uber for Lava Yuva 2 | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-pokemon-go-joystick-on-samsung-galaxy-s24-ultra-drfone-by-drfone-virtual-android/"><u>How to use Pokemon Go Joystick on Samsung Galaxy S24 Ultra? | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-dissecting-the-new-features-of-camstudio/"><u>In 2024, Dissecting the New Features of CamStudio</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-find-my-iphone-without-apple-id-from-your-iphone-11-by-drfone-ios/"><u>In 2024, How to Remove Find My iPhone without Apple ID From your iPhone 11?</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-to-use-ispoofer-on-xiaomi-redmi-note-12-4g-drfone-by-drfone-virtual-android/"><u>In 2024, How to use iSpoofer on Xiaomi Redmi Note 12 4G? | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/in-2024-leap-into-the-spotlight-with-tiktok-lives/"><u>In 2024, Leap Into the Spotlight with TikTok Lives</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-strategic-monetization-for-game-streams/"><u>In 2024, Strategic Monetization for Game Streams</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-strategies-to-remove-youtube-trailers-and-clips/"><u>In 2024, Strategies to Remove YouTube Trailers and Clips</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-the-ultimate-solution-of-iphone-x-face-id-not-working/"><u>In 2024, The Ultimate Solution of iPhone X Face ID Not Working</u></a></li>
<li><a href="https://windows11.techidaily.com/innovative-synergy-windows-enables-iphone-and-ipad-with-desktop-power/"><u>Innovative Synergy: Windows Enables iPhone & iPad with Desktop Power</u></a></li>
<li><a href="https://windows11.techidaily.com/instant-wallpaper-update-the-simple-windows-method/"><u>Instant Wallpaper Update: The Simple Windows Method</u></a></li>
<li><a href="https://windows11.techidaily.com/launching-wordpad-windows-users-handbook/"><u>Launching WordPad: Windows User's Handbook</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11s-fast-flip-buttons/"><u>Mastering Windows 11'S Fast Flip Buttons</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-in-moving-between-focused-and-unfocused-states-within-windows-terminal/"><u>Mastery in Moving Between Focused and Unfocused States Within Windows Terminal</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-of-access-control-regedit-in-win11/"><u>Mastery of Access Control: RegEdit in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-muted-powershell-scripts-four-tactics-to-counter-error-message/"><u>Mastery Over Muted PowerShell Scripts: Four Tactics to Counter Error Message</u></a></li>
<li><a href="https://windows11.techidaily.com/minmax-cpu-states-navigating-windows-power-control/"><u>Min/Max CPU States: Navigating Windows Power Control</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-tasks-like-a-pro-admin-mode-for-task-manager-on-windows-11/"><u>Navigate Tasks Like a Pro: Admin Mode for Task Manager on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-through-time-windows-11-file-history-essentials/"><u>Navigate Through Time: Windows 11 File History Essentials</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-rotate-avi-videos-for-free-top-picks-for-windows-mac-mobile-and-web/"><u>New Rotate AVI Videos for Free Top Picks for Windows, MAC, Mobile & Web</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-s-leading-online-vertical-video-editor-platforms-for-2024/"><u>New S Leading Online Vertical Video Editor Platforms for 2024</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/performance-assessment-of-the-hp-15-inch-notebook-featuring-an-amd-chip-is-it-practical/"><u>Performance Assessment of the HP 15 Inch Notebook Featuring an AMD Chip - Is It Practical?</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-glance-at-recent-files-in-windows/"><u>Quick Glance at Recent Files in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-unsupported-boots-a-5-step-windows-guide/"><u>Resolving Unsupported Boots: A 5-Step Windows Guide</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/simplified-method-for-youtubers-to-dailymotion-for-2024/"><u>Simplified Method for YouTubers to Dailymotion for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/skip-bloatware-embrace-pure-windows-11-experience/"><u>Skip Bloatware: Embrace Pure Windows 11 Experience!</u></a></li>
<li><a href="https://techidaily.com/solved-bad-and-corrupt-videos-that-wont-play-on-vivo-by-stellar-video-repair-mobile-video-repair/"><u>Solved  Bad and Corrupt Videos that won't Play on Vivo</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-disappearing-results-from-windows-1011-search-tool/"><u>Solving Disappearing Results From Windows 10/11 Search Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-the-invalid-system-id-issue-on-windows-11/"><u>Solving the Invalid System ID Issue on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-enforce-local-policies-to-a-specific-user-in-windows-11/"><u>Steps to Enforce Local Policies to a Specific User in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-microsoft-store-glitch-error-code-0x800704cf/"><u>Steps to Resolve Microsoft Store Glitch (Error Code 0X800704CF)</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-repairing-crashing-ccleaner-in-windows-1011/"><u>Strategies for Repairing Crashing CCleaner in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-tracking-storage-spent-on-apps/"><u>Strategies for Tracking Storage Spent on Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-fix-windows-11-assistive-application/"><u>Strategies to Fix Windows 11 Assistive Application</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-presentations-windows-11-remove-pin-lock/"><u>Streamline Presentations: Windows 11, Remove PIN Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-screen-hotkey-based-program-minimization-techniques/"><u>Streamline Your Screen: Hotkey-Based Program Minimization Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-guide-to-identify-your-graphic-model-in-win11/"><u>Swift Guide to Identify Your Graphic Model in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-guidance-for-choosing-between-nvidia-gamestudio-drivers/"><u>Tailored Guidance for Choosing Between Nvidia Game/Studio Drivers</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-tech-review-the-ultimate-guide-to-hardware/"><u>Tom's Tech Review: The Ultimate Guide to Hardware</u></a></li>
<li><a href="https://windows11.techidaily.com/tweaking-device-settings-on-windows-11-a-step-by-step-guide/"><u>Tweaking Device Settings on Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/unearthing-bsod-traces-within-windows-vista2008/"><u>Unearthing BSOD Traces Within Windows Vista/2008</u></a></li>
<li><a href="https://windows11.techidaily.com/unhurried-mobile-migration-with-easy-installation-in-windows-11/"><u>Unhurried Mobile Migration with Easy Installation in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-productivity-a-guide-to-making-multiple-directories-at-once-in-windows/"><u>Unleashing Productivity: A Guide to Making Multiple Directories at Once in Windows</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-approaches-to-silence-echoes-in-professional-audio-recording/"><u>Updated In 2024, Approaches to Silence Echoes in Professional Audio Recording</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-10-product-key-our-guide-to-the-top-deals/"><u>Windows 10 Product Key: Our Guide to the Top Deals</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-breaks-boundaries-with-iosmacwindows-pc-support/"><u>Windows Breaks Boundaries with iOS/Mac/Windows PC Support</u></a></li>
<li><a href="https://windows11.techidaily.com/wintools-strategy-the-ultimate-performance-boost/"><u>WinTools Strategy: The Ultimate Performance Boost</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/youtube-clip-maker/"><u>Youtube Clip Maker</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/youtube-for-filmmakers-revolutionizing-visual-storytelling-for-2024/"><u>Youtube for Filmmakers  Revolutionizing Visual Storytelling for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/zeroing-out-wsl-complete-uninstallation-in-windows-11/"><u>Zeroing Out WSL: Complete Uninstallation in Windows 11</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>