---
title: Strip Windows 11 of the Store Application
date: 2024-08-15T15:52:20.336Z
updated: 2024-08-16T15:52:20.336Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strip Windows 11 of the Store Application
excerpt: This Article Describes Strip Windows 11 of the Store Application
keywords: Remove Win11 Store App,Uninstall Windows Store,Strip 11 Store Integration,Eliminate Store From Win11,Disable Windows Store,Exclude Store App,Ditch Win11 Store Feature
thumbnail: https://thmb.techidaily.com/c6b90e18ceea22d6abdcc88044c37b5416ce971b6cd304d4b06dc96901e8f1f1.jpg
---

## Strip Windows 11 of the Store Application

 Microsoft Store is the go-to place for Windows users if they want to install an app. The app library is slowly expanding, and you will find all the popular apps without any difficulty. But sometimes the Microsoft Store application behaves abnormally and requires troubleshooting.

 But what if it still doesn’t work, even after repairing and resetting? There is no uninstall option in the Settings app, so it is possible to uninstall Microsoft Store? Well, it is possible to remove and reinstall the Microsoft Store app. Here’s how.

## Why Should You Uninstall the Microsoft Store App?

 Microsoft Store houses all the useful and popular applications for Windows devices. Moreover, it guarantees safe and malware-free application downloads. But if the app fails to start or doesn’t work properly, removing it makes sense.

 But don’t worry. You can remove the app and then reinstall it if you want. Reinstallation can fix persistent issues with the current version of the Microsoft Store app. It will remove the current app installation and all its related files and corrupt data. After that, you can reinstall the Microsoft app with a single command.

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Uninstall Microsoft Store App From Windows 11

 You can remove the Microsoft Store app from Windows 11 using the winget tool and run it using the command prompt. In addition, you can use the PowerShell cmdlet to remove the Microsoft Store application package from your system or use a batch file.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. Using Winget

 Winget is a handy Windows package manager tool available with the newer releases of Windows 10 and 11\. It makes it ridiculously easy to search and manage applications on your system. You can use it to remove any application, even the Microsoft Store app from your system. Here’s how:

1. Press the**Win + R** key to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**cmd** and press the**Ctrl + Shift + Enter** keys to launch the Command Prompt with administrator privileges.
2. Now, we need to locate the ID of the Microsoft Store app installed on the system. Type the following command in the command prompt window and press the enter key:**Winget list Store**
3. Winget will list all the installed programs on your system containing the string “store” in their name. Find the Microsoft Store app in the list and**copy** its**ID** .
4. After that, you need to run the uninstall command using winget. The syntax is**winget uninstall \[app ID\]** . So, the command will be:  
winget uninstall Microsoft.WindowsStore_8wekyb3d8bb
5. Press enter to execute the command and wait for it to execute successfully.  
![Uninstall Microsoft Store App using winget](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-winget.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->
6. Type**exit** in the command prompt window and press enter to close it.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
### 2\. Using PowerShell

 Before winget was officially integrated into Windows 10 and 11, there was a method to [remove the Microsoft Store app using PowerShell](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) . The method still works and all you need to do is list the package name and then use the**Remove-AppxPackage** cmdlet to uninstall the Microsoft Store app from your system. Make sure to run PowerShell with elevated permissions.

### 3\. Using a Batch File

 If you want to save the hassle of typing commands every time you want to uninstall the Microsoft Store app, you can use a batch file. It will help you to remove Microsoft Store app from your system in a couple of clicks whenever the normal troubleshooting methods don’t work for you. Repeat the following steps:

1. Press**Win + D** to switch to the Desktop. Right-click on the Desktop and select the**New > Text Document** option.
2. Open the newly created text document file on the desktop. A Notepad window will pop up. Paste the following text in it:  
@echo off winget uninstall "Microsoft Store" exit
3. Now, press**Ctrl + Shift + S** to open the "Save as" window. Name the batch file as**UninstallStore.bat** and keep the**Save as** type option as**All files** .  
![Uninstall Microsoft Store App using batch file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-batch-file.jpg)
<!-- affiliate ads begin -->
<a href="https://uperfect.sjv.io/c/5597632/1246754/15155" target="_top" id="1246754"><img src="//a.impactradius-go.com/display-ad/15155-1246754" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1246754/15155" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Click on the**Save** button. Close the Notepad window.
5. Press**Win + D** to switch to the desktop again. Right-click on the batch file and select the**Run as administrator** option from the context menu.
6. A command prompt window will open, run the Microsoft Store app uninstallation command, and close automatically. You don’t need to interact with the window.
7. Open the Start menu and search for Microsoft Store. You won’t find any matching app on your system.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
## Easily Remove the Microsoft Store From Windows

 Windows 10 and 11 don’t offer an option to uninstall Microsoft Store. So, you are only left at the mercy of a system restore or reset. However, you can now uninstall the Microsoft Store app from your system using any of the three methods mentioned above. You can also reinstall it using the PowerShell cmdlet and continue using the app again.


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
<li><a href="https://youtube-sure.techidaily.com/024-approved-daily-dharma-the-best-yoga-channels-for-self-growth/"><u>[New] 2024 Approved  Daily Dharma  The Best Yoga Channels for Self-Growth</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/024-approved-score-high-on-youtube-with-these-ranking-factors/"><u>[New] 2024 Approved  Score High on YouTube with These Ranking Factors</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/-premier-resources-download-free-high-quality-green-screen-footage/"><u>[New] 8 Premier Resources  Download Free, High-Quality Green Screen Footage</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-guide-to-sharing-on-instagram-videos-and-more/"><u>[New] Guide to Sharing on Instagram  Videos & More</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-discovering-the-best-mac-cam-tech-without-bandicam/"><u>[New] In 2024, Discovering the Best Mac Cam Tech Without Bandicam</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-in-2024-srt-to-sub-pivotal-approaches-for-content-transformation/"><u>[New] In 2024, SRT to SUB  Pivotal Approaches for Content Transformation</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-tactical-steps-to-download-securely-free-vlc-media-on-mac/"><u>[New] Tactical Steps to Download Securely Free VLC Media on MAC</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-top-15-youtube-openers-that-boost-viewership-and-engagement/"><u>[New] Top 15 YouTube Openers That Boost Viewership and Engagement</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-top-fareless-webcam-viewer-with-recording/"><u>[New] Top Fareless Webcam Viewer with Recording</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-assessment-of-vidmas-impact-on-modern-screen-recorders-for-2024/"><u>[Updated] Assessment of Vidma's Impact on Modern Screen Recorders for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-captivate-your-audience-professional-end-screen-creations/"><u>[Updated] In 2024, Captivate Your Audience  Professional End Screen Creations</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-online-obsession-the-8-must-watch-titles/"><u>[Updated] Online Obsession  The 8 Must-Watch Titles</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-understanding-youtube-shorts-revenue-strategy/"><u>[Updated] Understanding YouTube Shorts Revenue Strategy</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/15-strategies-to-supercharge-your-learning-with-podcasts-for-2024/"><u>15 Strategies to Supercharge Your Learning with Podcasts for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-influencer-secrets-making-your-vids-hits-hard/"><u>2024 Approved  Influencer Secrets  Making Your Vids Hits Hard</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-the-ultimate-collection-of-favorite-ig-after-effects-plugins/"><u>2024 Approved  The Ultimate Collection of Favorite IG After Effects Plugins</u></a></li>
<li><a href="https://windows11.techidaily.com/6-quick-ways-to-fix-the-powerpoint-cant-save-file-error-in-windows-11/"><u>6 Quick Ways to Fix the PowerPoint Can't Save File Error in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-tips-for-efficient-toolbar-usage-in-microsoft-win11-pcm/"><u>Advanced Tips for Efficient Toolbar Usage in Microsoft Win11 PCM</u></a></li>
<li><a href="https://howto.techidaily.com/android-screen-stuck-general-xiaomi-redmi-note-12-proplus-5g-partly-screen-unresponsive-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Android Screen Stuck General Xiaomi Redmi Note 12 Pro+ 5G Partly Screen Unresponsive | Dr.fone</u></a></li>
<li><a href="https://win-solutions.techidaily.com/bust-the-dark-curse-solve-black-screen-glitch-in-resident-evil-village-for-pc-gamers/"><u>Bust the Dark Curse: Solve Black Screen Glitch in Resident Evil Village for PC Gamers</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-pictures-files-on-oneplus-nord-3-5g-by-fonelab-android-recover-pictures/"><u>Complete guide for recovering pictures files on OnePlus Nord 3 5G.</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-tecno-spark-20c-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Tecno Spark 20C Hard Reset | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/curating-edthemes-experience-on-windows-11/"><u>Curating EdThemes Experience on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-windows-11-camera-app-error-0xa00f425d-fixes/"><u>Disabling Windows 11 Camera App Error 0xA00F425D Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-vivetool-your-ticket-to-access-latest-windows-innovations/"><u>Discover ViVeTool: Your Ticket to Access Latest Windows Innovations</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-integration-portable-software-menus-for-w11plus/"><u>Easy Integration: Portable Software Menus for W11+</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-stable-windows-printer-connections/"><u>Ensuring Stable Windows-Printer Connections</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicating-your-input-cant-be-opened-vlc-error/"><u>Eradicating 'Your Input Can't Be Opened' VLC Error</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-advice-for-seamlessly-entering-fullscreen-mode/"><u>Expert Advice for Seamlessly Entering Fullscreen Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-missing-initialization-message-on-windows-pc/"><u>Fixing 'Missing Initialization' Message on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-monochrome-errors-with-marketplace/"><u>Fixing Monochrome Errors with Marketplace</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-the-nvidia-setup-not-available-glitch/"><u>Fixing the 'Nvidia Setup Not Available' Glitch</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-do-i-add-my-signature-to-wbk-file-by-ldigisigner-sign-a-word-sign-a-word/"><u>How do i add my signature to .wbk file</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-conquer-common-errors-during-windows-11-rollout/"><u>How to Conquer Common Errors During Windows 11 Rollout</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-detect-and-remove-spyware-on-samsung-galaxy-s24-drfone-by-drfone-virtual-android/"><u>How to Detect and Remove Spyware on Samsung Galaxy S24? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fake-gps-on-xiaomi-redmi-note-12t-pro-for-mobile-legends-drfone-by-drfone-virtual-android/"><u>How To Fake GPS On Xiaomi Redmi Note 12T Pro For Mobile Legends? | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-unlink-apple-id-from-iphone-12-mini-by-drfone-ios/"><u>How To Unlink Apple ID From iPhone 12 mini</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/how-to-use-pokemon-emerald-master-ball-cheat-on-apple-iphone-7-drfone-by-drfone-virtual-ios/"><u>How to Use Pokémon Emerald Master Ball Cheat On Apple iPhone 7 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/illuminate-with-joy-magical-holiday-window-decor/"><u>Illuminate with Joy: Magical Holiday Window Decor</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-additional-tips-about-sinnoh-stone-for-nubia-red-magic-9-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Additional Tips About Sinnoh Stone For Nubia Red Magic 9 Pro | Dr.fone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-beyond-obs-streamer-friendly-broadcast-software/"><u>In 2024, Beyond OBS  Streamer-Friendly Broadcast Software</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-learn-how-everything-works-on-itel-a70-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Learn How Everything Works On Itel A70 | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-speech-synthesis-simplified-from-ssa-to-compelling-srt-files/"><u>In 2024, Speech Synthesis Simplified  From SSA to Compelling SRT Files</u></a></li>
<li><a href="https://windows11.techidaily.com/legacy-unlocks-employing-a-windows-7-key-in-11-setup/"><u>Legacy Unlocks: Employing a Windows 7 Key in 11 Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/meeting-prep-101-test-your-windows-webcam-microphone/"><u>Meeting Prep 101: Test Your Windows Webcam, Microphone</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-onedrive-errors-on-windows-11-an-experts-fix-list/"><u>Navigating OneDrive Errors on Windows 11: An Expert's Fix List</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-the-maze-of-windows-error-code-0xc00000f/"><u>Navigating Through the Maze of Windows Error Code 0Xc00000f</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-nullnone-value-dilemmas-on-windows/"><u>Overcoming Null/None Value Dilemmas on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-win-os-extract-issues-saving-time-with-error-1152-solution/"><u>Overcoming Win OS Extract Issues: Saving Time with Error 1152 Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-shift-script-moving-windows-11-selected-files/"><u>Quick Shift Script: Moving Windows 11 Selected Files</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-tip-addressing-winscomrsvc-system-crashes/"><u>Quick Tip: Addressing WinscomrsVc System Crashes</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-marketplace-failures-x80131500/"><u>Resolving Windows Marketplace Failures X80131500</u></a></li>
<li><a href="https://windows11.techidaily.com/sound-revolution-for-your-pc-the-essential-guide-to-audio-drivers-updates/"><u>Sound Revolution for Your PC: The Essential Guide to Audio Drivers Updates</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/step-by-step-telegram-web-setup-for-novices-for-2024/"><u>Step-by-Step Telegram Web Setup for Novices for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-to-become-a-win-11-insider/"><u>Step-by-Step to Become a Win 11 Insider</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-resolving-installation-issues-with-microsoft-store-apps/"><u>Steps for Resolving Installation Issues with Microsoft Store Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-frozen-pages-and-scrolling-issues-in-excel/"><u>Stop Frozen Pages and Scrolling Issues in Excel</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-pinpointing-device-serial-numbers-on-windows/"><u>The Ultimate Guide to Pinpointing Device Serial Numbers on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-the-finest-free-car-performance-fixes/"><u>The Ultimate Guide to the Finest Free Car Performance Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/top-6-windows-11-prime-fps-monitors-and-trackers/"><u>Top 6 Windows 11: Prime FPS Monitors & Trackers</u></a></li>
<li><a href="https://windows11.techidaily.com/top-solutions-for-windows-pin-access-issues-10plus11/"><u>Top Solutions for Windows PIN Access Issues (10+11)</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-trending-hashtags-on-instagram-for-boosting-your-posts-visibility/"><u>Top Trending Hashtags on Instagram for Boosting Your Posts' Visibility</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-text-selection-power-in-windows-pdf-files/"><u>Unleashing Text Selection Power in Windows PDF Files</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/unveiling-the-best-8-free-streaming-channels-on-roku/"><u>Unveiling the Best 8 Free Streaming Channels on Roku</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/unveiling-the-secrets-of-self-playing-fb-videos/"><u>Unveiling the Secrets of Self-Playing FB Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-11-entry-into-the-insider-trials/"><u>Unveiling Windows 11: Entry Into the Insider Trials</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-revolution-essential-replacement-tools-to-consider/"><u>Win 11 Revolution: Essential Replacement Tools to Consider</u></a></li>
<li><a href="https://windows11.techidaily.com/win11s-guide-to-stable-background-fixes/"><u>Win11's Guide to Stable Background Fixes</u></a></li>
</ul></div>
