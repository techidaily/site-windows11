---
title: Resetting the Explorer View for Better Management
date: 2024-07-11T22:08:09.760Z
updated: 2024-07-12T22:08:09.760Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resetting the Explorer View for Better Management
excerpt: This Article Describes Resetting the Explorer View for Better Management
keywords: ExploreViewReset,ManageExplorer,ResetExpVIEW,ViewManagement,ExplorerRefresh,BetterManageEXP,OptimizeEXPVIEW
thumbnail: https://thmb.techidaily.com/ecc3916e90aab64f99ff84f9c45d036bcf1e08682351feaa92b6a0ff146b14b9.jpg
---

## Resetting the Explorer View for Better Management

 Folder View Settings in Windows help you control how the contents of a particular folder are displayed and organized. If you’ve changed these settings, but now want to reset them to the default view, it’s easy. Read this guide to learn how to reset Folder View settings on your Windows 11 PC.

## How to Reset Folder View Settings to Default on Windows

 There are three ways to reset your Folder View Settings to the default view. The first method is to run a batch file, the second using File Explorer, whereas the third and final method involves tweaking the registry editor. This post explains each method in detail. Let's dive into it.

### 1\. Run a Batch File to Reset Folder View Settings to Default

 Resetting the Folder View Settings with this method requires creating and running a batch file. This will reset the settings for all folders across your computer. Here's how to do it:

1. Right-click on your desktop and select**New > Text Document** .
2. Name it**ResetFolderViewSettings** and press Enter to save it.
3. Open the newly created text file in Notepad or any other text editor of your choice.
4. Now copy and paste the following code into the file:  
`@echo off  

:: Resets folder view settings, window size and position of all folders  
Reg Delete "HKCU\SOFTWARE\Classes\Local Settings\Software\Microsoft\Windows\Shell\BagMRU" /F  
Reg Delete "HKCU\SOFTWARE\Classes\Local Settings\Software\Microsoft\Windows\Shell\Bags" /F  

:: To reset "Apply to Folders" views to default for all folder types  
REG Delete "HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\Streams\Defaults" /F  

:: To reset size of details, navigation, preview panes to default for all folders  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Modules\GlobalSettings\Sizer" /F  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Modules\NavPane" /F  

:: To reset size of Save as amd Open dialogs to default for all folders  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\CIDOpen" /F  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\CIDSave" /F  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\ComDlg32" /F  

:: To kill and restart explorer process  
taskkill /f /im explorer.exe  
start explorer.exe`
5. After adding the code, click**File** in the top menu, then select**Save As** .
6. Now select**All Files** in the Save as type menu, and add**.bat** to the end of the file’s name.  
![Run a Batch File to Reset Folder View Settings to Default](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-a-batch-file-to-reset-folder-view-settings-to-default.jpg)
7. From the left pane, select**Desktop** as the location.
8. Then click**Save** and close the text editor window.
9. Finally, double-click the batch file you created, and it will reset your Folder View Settings to the default view.

### 2\. Reset Folder View Settings to Default via File Explorer

 If you only need to reset the View Settings of all folders of the same type, this method is for you. Here's what you have to do:

1. Click on Start and search for**File Explorer Options** . To learn more about it, see our guide on [how to open the Folder Options on Windows](https://www.makeuseof.com/windows-10-open-folder-options/) .
2. Now, select the**View** tab in the top bar and tap on**Reset Folders** .  
![Reset Folder View Settings to Default Via File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-via-file-explorer.jpg)
3. Click**Yes** when prompted to confirm your action.
4. Finally, hit**OK** and the window will close.

 This will reset your Folder View Settings to Windows' default settings.

### 3\. Reset Folder View Settings to Default Using Registry Editor

 The last method to reset Folder View settings involves using the Windows Registry Editor. You should only use this method if you are an experienced user and know how it works, since messing with its keys could cause serious problems. To avoid data loss, you must [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before continuing.

 To reset folder view settings using the registry editor, do the following:

1. Press**Win + R** on your keyboard to [open the Run command](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**regedit** in the text box and press Enter. This will [open the Registry Editor window](https://www.makeuseof.com/windows-11-open-registry-editor/) .
3. Navigate to the following location:  
HKEY_CURRENT_USER\Software\Classes\Local Settings\Software\Microsoft\Windows\Shell
4. In the left sidebar, right-click on the**BagMRU** folder and select**Delete.**  
![Reset Folder View Settings to Default Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-using-registry-editor.jpg)
5. Click**Yes** when asked to confirm your action.
6. Similarly, delete the**Bags** folder and close the Registry window.

## Reset Folder View Settings to Default

 Folder View on Windows allows users to customize their view of files and folders. This includes settings such as the file size information, restoring the previous folder when logging in, and automatically entering words when searching.

 However, if you have changed the View settings, this guide will help you reset Folder Options to its default.


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
<li><a href="https://unlock-android.techidaily.com/in-2024-downloading-samfw-frp-tool-30-for-xiaomi-redmi-k70-by-drfone-android/"><u>In 2024, Downloading SamFw FRP Tool 3.0 for Xiaomi Redmi K70</u></a></li>
<li><a href="https://audio-editing.techidaily.com/2024-approved-voice-recording-on-android-unveiled-discovering-the-top-10-apps/"><u>2024 Approved Voice Recording on Android Unveiled Discovering the Top 10 Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-elderly-friendly-window-pc-usability/"><u>Boosting Elderly-Friendly Window PC Usability</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-disruption-fix-windows-gaming-woe-errors/"><u>Avoid Disruption, Fix Windows' Gaming WoE Errors</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-complete-insight-a-detailed-walkthrough-of-facetune-app/"><u>[New] 2024 Approved  Complete Insight  A Detailed Walkthrough of Facetune App</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-browsing-security-enhanced-graphics-on-edge/"><u>Boosting Browsing Security: Enhanced Graphics on Edge</u></a></li>
<li><a href="https://windows11.techidaily.com/a-practical-approach-to-windows-network-file-transfer-via-python/"><u>A Practical Approach to Windows Network File Transfer via Python</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-effortless-ways-to-transfer-data-from-your-apple-iphone-se-2020-to-iphone-15-drfone-by-drfone-transfer-from-ios/"><u>In 2024, Effortless Ways to Transfer Data from Your Apple iPhone SE (2020) to iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/discover-your-ideal-screen-recorder-pc-and-mac-edition-for-2024/"><u>Discover Your Ideal Screen Recorder - PC & Mac Edition for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-low-vram-issues-for-hogwarts-educational-virtual-adventure/"><u>Addressing Low VRAM Issues for Hogwarts Educational Virtual Adventure</u></a></li>
<li><a href="https://windows11.techidaily.com/broken-binkey-bastion-proceed-prudently-not-promptly/"><u>Broken Binkey Bastion: Proceed Prudently, Not Promptly</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-in-2024-creating-chat-hangouts-on-whatsapp/"><u>[Updated] In 2024, Creating Chat Hangouts on WhatsApp</u></a></li>
<li><a href="https://windows11.techidaily.com/a-detailed-approach-to-fixing-windows-error-code-30005/"><u>A Detailed Approach to Fixing Windows Error Code: 30005</u></a></li>
<li><a href="https://animation-videos.techidaily.com/in-2024-how-to-make-gif-instagram-quick-tips/"><u>In 2024, How to Make GIF Instagram | Quick Tips</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/g310-support-turn-off-screen-lock-by-drfone-android-unlock-android-unlock/"><u>G310 support - Turn Off Screen Lock.</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-complications-resetting-terminal-on-win11/"><u>Avoid Complications: Resetting Terminal on Win11</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-life360-notify-when-you-log-out-on-vivo-x100-drfone-by-drfone-virtual-android/"><u>In 2024, Does Life360 Notify When You Log Out On Vivo X100? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/a-shortcut-to-starting-wordpad-on-your-pc/"><u>A Shortcut to Starting WordPad on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/awakening-hidden-pane-windows-effective-steps-for-win11/"><u>Awakening Hidden Pane Windows: Effective Steps for Win11</u></a></li>
<li><a href="https://fox-blue.techidaily.com/unleash-marketing-potential-through-strategy-boxing/"><u>Unleash Marketing Potential Through Strategy Boxing</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-twist-tactics-achieving-angles-that-stand-out-on-social-media/"><u>[New] Twist Tactics  Achieving Angles That Stand Out on Social Media</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-best-practices-in-yt-thumbnail-sizing/"><u>[Updated] 2024 Approved  Best Practices in YT Thumbnail Sizing</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-mind-mavens-top-10-educational-youtube-hubs/"><u>In 2024, Mind Mavens  Top 10 Educational YouTube Hubs</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-the-no-connection-error-with-malwarebytes-in-win-1011/"><u>Addressing the “No Connection” Error with Malwarebytes in Win 10/11</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-fundamental-codex-for-online-video-communities/"><u>2024 Approved  Fundamental Codex for Online Video Communities</u></a></li>
<li><a href="https://windows11.techidaily.com/a-guide-to-uncovering-your-systems-identity-quickly/"><u>A Guide to Uncovering Your System's Identity Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/a-leap-forward-for-windows-11-innovative-widget-features-proposal/"><u>A Leap Forward for Windows 11: Innovative Widget Features Proposal</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/2024-approved-the-best-video-trailer-design-software-for-mac-and-pc-2023-update/"><u>2024 Approved The Best Video Trailer Design Software for Mac and PC (2023 Update)</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-crafting-a-chorus-of-images-and-sound-on-instagram-for-2024/"><u>[New] Crafting a Chorus of Images & Sound on Instagram for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-absence-of-ubisoft-launcher-in-windows/"><u>Addressing Absence of Ubisoft Launcher in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerate-filenames-processing-with-powertoys/"><u>Accelerate Filenames Processing with PowerToys</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-overcoming-the-invisible-barrier-in-tiktok-world/"><u>2024 Approved  Overcoming the Invisible Barrier in TikTok World</u></a></li>
<li><a href="https://windows11.techidaily.com/add-command-to-windows-11-context-menu-for-file-moves-and-copies/"><u>Add Command to Windows 11 Context Menu for File Moves & Copies</u></a></li>
<li><a href="https://windows11.techidaily.com/batch-heic-to-jpeg-images-in-windows-environment/"><u>Batch Heic to Jpeg Images in Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/7-proven-methods-to-enhance-your-windows-11-experience-35/"><u>7 Proven Methods to Enhance Your Windows 11 Experience (35)</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-oppo-a18-drfone-by-drfone-virtual-android/"><u>Will Pokémon Go Ban the Account if You Use PGSharp On Oppo A18 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/adding-windows-update-alerts-tooltip-menu-entry/"><u>Adding Windows Update Alerts Tooltip Menu Entry</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-from-dull-to-dazzling-best-video-brighten-apps/"><u>New 2024 Approved From Dull to Dazzling Best Video Brighten Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-techniques-locating-ip-and-mac-in-windows-ps/"><u>Advanced Techniques: Locating IP & MAC in Windows PS</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/budget-mp3-refiner-for-mac-enthusiasts-for-2024/"><u>Budget MP3 Refiner for Mac Enthusiasts for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-burnout-keeping-your-game-windows-laptop-cool/"><u>Avoiding Burnout: Keeping Your Game Windows Laptop Cool</u></a></li>
<li><a href="https://windows11.techidaily.com/5-key-steps-to-resolve-hypervisor-error-bsod-in-winos/"><u>5 Key Steps to Resolve Hypervisor Error BSOD in WINOS</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-windows-settings-for-visible-sticky-notes/"><u>Adjusting Windows Settings for Visible Sticky Notes</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-educators-essential-video-recording-gadgets-top-10-picks/"><u>[New] Educator's Essential Video Recording Gadgets  Top 10 Picks</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-the-hidden-powerhouses-in-your-instagram-toolkit-for-2024/"><u>[Updated] The Hidden Powerhouses in Your Instagram Toolkit for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-decibels-on-windows-integrated-bt-audio/"><u>Boosting Decibels on Windows-Integrated BT Audio</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/in-2024-a-step-by-step-guide-to-creating-stunning-stop-motion-videos-on-instagram/"><u>In 2024, A Step-by-Step Guide to Creating Stunning Stop Motion Videos on Instagram</u></a></li>
<li><a href="https://unlock-android.techidaily.com/can-i-bypass-a-forgotten-phone-password-of-honor-magic-5-by-drfone-android/"><u>Can I Bypass a Forgotten Phone Password Of Honor Magic 5?</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-low-power-options-for-better-battery-life/"><u>Adjusting Low-Power Options for Better Battery Life</u></a></li>
<li><a href="https://windows11.techidaily.com/breathing-life-into-your-dormant-windows-mouse/"><u>Breathing Life Into Your Dormant Windows Mouse</u></a></li>
</ul></div>
