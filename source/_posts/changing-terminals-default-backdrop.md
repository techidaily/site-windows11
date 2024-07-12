---
title: Changing Terminal's Default Backdrop
date: 2024-07-11T21:37:59.287Z
updated: 2024-07-12T21:37:59.287Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Changing Terminal's Default Backdrop
excerpt: This Article Describes Changing Terminal's Default Backdrop
keywords: Terminal Wallpaper Change,Default Backdrop Update,Changing Terminal Background,Set Terminal Backdrop,Customize Terminal Appearance,Alter Terminal Design,Terminal Theme Adjustment
thumbnail: https://thmb.techidaily.com/a9af59315aea8cc232d9e9df37ddf4fb252ec7cdb030d740feb1460fb864db26.jpg
---

## Changing Terminal's Default Backdrop

 Changing the background image of the Windows Terminal is an easy way to customize your command line experience. This adds a personal touch and makes your experience visually appealing.

 This tutorial will explain three methods to change the Terminal background image in Windows 11.

## How to Change Windows Terminal Background Image

 You can change the background image of Windows Terminal in three ways: using the**Default** option within the Terminal app or manually editing the settings.json file using**File Explorer** and**Run** dialog box. All three methods achieve the same result and are easy to use.

 Using the default option is the simplest way to change your background image while editing the settings.json file provides more control and customization options. Below, we will guide you through each option.

## 1\. Change Windows Terminal Background Image via Its Options

 The easiest way to change the background image of Windows Terminal is by using its option. This can be done by opening Windows Terminal and changing settings within the app. Here's how to do it:

 To get started, open the Windows Terminal application first. For this, click on the Windows icon to open the Start menu. Then type**Terminal** into the search box, and select it from the list.

 Once you open the Terminal application, click on the dropdown menu icon in the top left corner, and select the**Settings** option.

 In the settings window's left column, go to**Defaults** . Now move to the right side of the page and tap**Appearance** to expand it.

![Change Windows Terminal Background Image via Default Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-windows-terminal-background-image-via-default-option.jpg)

 Scroll down to the**Background image** section, then click the**Background image path** option. Next, click the**Browse** option and select an image you want to use as a background.

 Click**Open** to confirm your selection. Now you should be able to see the selected image as the background of the terminal.

 You can also copy and paste the file path of an image directly into the Background image path option. Finally, click the**Save** button and the background image will be set.

 To improve the appearance of your image in the Windows Terminal, you can customize it using several options. You can use**Background image stretch mode** to change how the image is resized to fill the window. Further, you can change the**Background image alignment** to adjust the image position, and**Background image opacity** to make it more or less transparent.

 Once you are satisfied with the changes, click the**Save** button in order to apply them. Your custom background image should now be visible in the Windows Terminal.

 If you want to switch to the default image,[reset the Windows Terminal to its default settings](https://www.makeuseof.com/windows-11-reset-terminal-settings/) . This will automatically restore your background to the default image.

## 2\. Change the Windows Terminal Background Image via Windows File Explorer

 Manually editing settings.json is another great way to customize your Windows Terminal background image. For this, you need to open the settings.json file in any text editor, such as Notepad. Here's how to do it:

1. Open Windows File Explorer (see our guide on [how to open File Explorer on a Windows PC](https://www.makeuseof.com/windows-open-file-explorer/) ).
2. Once you're in File Explorer, navigate to your**C:** drive and select the**Users** folder.
3. Locate your**username** in this folder, then open the**AppData** folder and the**Local** folder.
4. In the Local folder, find and open the**Packages** folder.
5. Look for the**Microsoft.WindowsTerminal\_8wekyb3d8bbwe** folder and open it.
6. Finally, in this folder, double-click on**Settings** to open settings.json in any text editor.

 In the settings.json file, you will find a section called**backgroundImage** . You can use**Ctrl + F** to find it quickly.

 This is where you can enter the path of your own image to set as the Windows Terminal background. To do this, first copy the full file path for the image you want to use, including the file name.

![How to Change Windows Terminal Background Image From Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/how-to-change-windows-terminal-background-image-from-windows-file-explorer.jpg)

 Then paste this path into the**backgroundImage** section of settings.json. Remember to include a comma (**,**) after the path, as shown in the image above.

 Once you have pasted the path of your image, save the settings file and close the text editor. To apply this new background image, simply restart your Windows Terminal. The new background image should be displayed on the terminal window.

 You can adjust the image transparency using the same method. Simply input values for the**backgroundImageOpacity** parameters to modify the settings. These additional settings allow you to personalize your Windows Terminal background image even further.

 Restart Windows Terminal for the changes to take effect. In this way, you can easily customize your Windows Terminal background image using the settings.json file.

## 3\. Change the Windows Terminal Background Image Using the Run Command

 The Run Command can also help you change your Windows Terminal background image. Instead of searching for the settings.json file in Windows File Explorer, you can directly access and modify it using this tool.

 Follow these instructions to customize your Windows Terminal background image using the Run Command tool:

1. Right-click on Start and select**Run** from the menu list. If you prefer using shortcut keys, press**Win + R** on your keyboard to open the tool directly.
2. In the text box, type the following command and press Enter:  
`%localappdata%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState`
3. This will open the Local State folder containing the settings.json file. Right-click on**Settings** and select**Open with** \>**Notepad** .  
![Change Windows Terminal Background Image From Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-windows-terminal-background-image-from-windows-file-explorer.jpg)
4. Scroll down to the**backgroundImage** section and replace the image path with your own.
5. Then press**Ctrl + S** on your keyboard to save the changes.
6. Close Notepad, then open Windows Terminal to see your new background image.

 You’re done! Now you know how to customize your Windows Terminal background image using the Run Command tool. You can further explore the settings.json file or use other tools to [customize and personalize your Windows Terminal](https://www.makeuseof.com/windows-terminal-customization/) .

## Set a New Background Image for Windows Terminal

 It's easy to customize your Windows Terminal by adding or changing the background image. All you need to do is access the settings.json file, where you can also adjust your image's transparency. Just remember to restart Windows Terminal after making changes. Read this guide to learn how to customize your Windows Terminal background image easily.

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
<li><a href="https://windows11.techidaily.com/start-up-synergy-for-notes-windows-plus-sticky-notes-together/"><u>Start-Up Synergy for Notes: Windows + Sticky Notes Together</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-crafting-spectaculous-1080p-streams-on-fb-groups/"><u>In 2024, Crafting Spectaculous 1080P Streams on FB Groups</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-telnet-enablement-steps-explained/"><u>Windows 11 Telnet Enablement Steps Explained</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-exclusive-mp4-extraction-software-for-tiktok-content/"><u>[New] Exclusive MP4 Extraction Software for TikTok Content</u></a></li>
<li><a href="https://windows11.techidaily.com/surviving-windows-11-blue-screen-adopting-11-key-approaches/"><u>Surviving Windows 11 Blue Screen: Adopting 11 Key Approaches</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-diagnostics-enhancing-windows-11-troubleshooters/"><u>Reviving Diagnostics: Enhancing Windows 11 Troubleshooters</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-causes-of-pc-disk-issues/"><u>Addressing Causes of PC Disk Issues</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-basic-to-breakthrough-content-crafting-the-top-10-simplest-youtube-projects-for-2024/"><u>[New] Basic to Breakthrough Content  Crafting the Top 10 Simplest YouTube Projects for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/distinguishing-between-hdd-and-ssd-drives-on-pc/"><u>Distinguishing Between HDD & SSD Drives on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/the-importance-of-keeping-active-wins-11-notification-sounds/"><u>The Importance of Keeping Active Wins 11 Notification Sounds</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-to-repair-keyboard-issues-with-windows-snipper/"><u>Tips to Repair Keyboard Issues with Windows Snipper</u></a></li>
<li><a href="https://extra-hints.techidaily.com/expert-guide-selecting-the-ideal-sites-and-techniques-for-trimming-tamil-melodies/"><u>Expert Guide  Selecting the Ideal Sites & Techniques for Trimming Tamil Melodies</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-your-window-experience-mastering-the-start-menu/"><u>Enhance Your Window Experience: Mastering the Start Menu</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-top-8-gold-text-wonders-in-the-vast-world-of-3d-sites/"><u>2024 Approved  Top 8 Gold-Text Wonders in the Vast World of 3D Sites</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-seamless-live-recording-on-fb-uncover-4-critical-steps-for-2024/"><u>[New] Seamless Live Recording on FB  Uncover 4 Critical Steps for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-precision-editing-for-professionalism-adding-chapter-breakpoints-on-youtube/"><u>[Updated] 2024 Approved  Precision Editing for Professionalism  Adding Chapter Breakpoints on YouTube</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-what-legendaries-are-in-pokemon-platinum-on-vivo-x-flip-drfone-by-drfone-virtual-android/"><u>In 2024, What Legendaries Are In Pokemon Platinum On Vivo X Flip? | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-brief-sequences-lasting-impressions-time-lapse-with-samsung/"><u>2024 Approved  Brief Sequences, Lasting Impressions  Time-Lapse with Samsung</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-pause-auto-updates-no-more-prompts/"><u>Windows Pause Auto-Updates: No More Prompts!</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-connecting-in-real-time-advanced-tips-for-streaming-screens-via-fb/"><u>[Updated] In 2024, Connecting in Real Time  Advanced Tips for Streaming Screens via Fb</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-managing-events-with-windows-11-calendar/"><u>Efficiently Managing Events with Windows 11 Calendar</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-the-not-an-empty-directory-alert-error-code-0x80070091-in-win11/"><u>Conquering the Not an Empty Directory Alert (Error Code: 0X80070091) in Win11</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/innovations-unveiled-discover-the-11-breakthroughs-in-voice-alteration-tech-for-2024/"><u>Innovations Unveiled Discover the 11 Breakthroughs in Voice Alteration Tech for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-10-telegram-spy-tools-on-oneplus-12-for-parents-drfone-by-drfone-virtual-android/"><u>Top 10 Telegram Spy Tools On OnePlus 12 for Parents | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-a18-frp-by-drfone-android/"><u>In 2024, Step-by-Step Tutorial How To Bypass Oppo A18 FRP</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-linking-youtubes-harmony-to-imovie-clips-effortlessly/"><u>In 2024, Linking Youtube's Harmony to iMovie Clips Effortlessly</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/in-2024-how-to-make-after-effects-gifs/"><u>In 2024, How to Make After Effects Gifs</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-science-of-quadcopters-understanding-their-flight-patterns/"><u>The Science of Quadcopters  Understanding Their Flight Patterns</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-role-of-ai-in-windows-11-updates/"><u>Unveiling the Role of AI in Windows 11 Updates</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-best-10-screen-recorders-for-mac/"><u>[New] Best 10 Screen Recorders for Mac</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-preventing-windows-autolock-timed-out/"><u>Tips for Preventing Windows Autolock Timed Out</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-reimagining-art-top-6-influencers-shaping-nft-culture/"><u>In 2024, Reimagining Art  Top 6 Influencers Shaping NFT Culture</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-secure-logins-with-5-tips-against-key-conflicts-in-win11/"><u>Streamlining Secure Logins with 5 Tips Against Key Conflicts in Win11</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-google-chrome-from-tracking-your-location-on-tecno-spark-10c-drfone-by-drfone-virtual-android/"><u>How to Stop Google Chrome from Tracking Your Location On Tecno Spark 10C? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-regain-lost-connection-on-pcs-running-windows/"><u>Strategies to Regain Lost Connection on PCs Running Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-anticipation-surrounding-windows-11s-moment-22h2/"><u>The Anticipation Surrounding Windows 11’S Moment #22H2</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-elevated-privileges-for-power-users-a-guide/"><u>Enabling Elevated Privileges for Power Users: A Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-chromes-erroneous-virus-warning-on-pc/"><u>Clearing Chrome's Erroneous Virus Warning on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-mysteries-of-ram-in-windows-devices/"><u>Decoding the Mysteries of RAM in Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-non-functional-inbox-alerts-on-windows-os/"><u>Tackling Non-Functional Inbox Alerts on Windows OS</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-best-free-video-editors-easy-peasy-for-newbies/"><u>2024 Approved Best Free Video Editors Easy Peasy for Newbies</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-and-tricks-solving-the-try-connecting-bluetooth-issue/"><u>Tips and Tricks: Solving the 'Try Connecting' Bluetooth Issue</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-when-samsung-galaxy-z-flip-5-has-black-screen-of-death-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do When Samsung Galaxy Z Flip 5 Has Black Screen of Death? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/blueprints-to-build-secure-window-for-hardware-unhook/"><u>Blueprints to Build Secure Window for Hardware Unhook</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-reinstalling-failing-drivers-in-win11-system/"><u>Guide to Reinstalling Failing Drivers in Win11 System</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-convenient-snipping-identify-the-top-5-apps-for-pc-captures/"><u>In 2024, Convenient Snipping  Identify the Top 5 Apps for PC Captures</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-power-start-cmd-as-administrator/"><u>Boosting Power: Start CMD as Administrator</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-nvidia-opengl-glitches-in-windows-11/"><u>Troubleshooting NVIDIA OpenGL Glitches in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-winerror-x80780119-resolution/"><u>Techniques for WinError X80780119 Resolution</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-empty-folder-warning-in-windows-11/"><u>Eliminating 'Empty Folder' Warning in Windows 11</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-crafting-compelling-content-with-macootd-tiktoks/"><u>[New] Crafting Compelling Content with MacOOTD TikToks</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-app-functionality-after-qt-plugin-initialization-breakdown/"><u>Restoring App Functionality After Qt Plugin Initialization Breakdown</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-chatgpt-on-your-windows-pc/"><u>Configuring ChatGPT on Your Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-for-fixing-unopenable-windows-folders-on-double-click/"><u>Tactics for Fixing Unopenable Windows Folders on Double-Click</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-learn-to-navigate-large-tiktok-files-editing-made-simple-and-swift/"><u>In 2024, Learn to Navigate Large TikTok Files  Editing Made Simple and Swift</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-a-step-by-step-tutorial-on-video-angles-using-vlc/"><u>In 2024, A Step-by-Step Tutorial on Video Angles Using VLC</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-user-interface-integrating-emoji-15-into-win11/"><u>Boosting User Interface: Integrating Emoji 15 Into Win11</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-ideal-techniques-for-noiseless-recording-for-2024/"><u>[New] Ideal Techniques for Noiseless Recording for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-how-to-watch-vr-video-on-iphone-ios/"><u>2024 Approved  How to Watch VR Video on Iphone (Ios)</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-camera-app-malfunction-in-windows-11/"><u>Addressing Camera App Malfunction in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-wire-free-audio-on-windows-airpods/"><u>Guide to Wire-Free Audio on Windows (AirPods)</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-nvidia-connect-failure-on-windows-11-systems/"><u>Fixing Nvidia Connect Failure on Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/winerror-correction-bypassing-the-perplexing-0x80072746-mail-issue/"><u>WinError Correction: Bypassing the Perplexing 0X80072746 Mail Issue</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/demystifying-the-vectorscope-a-comprehensive-guide-for-premiere-pro-color-correction/"><u>Demystifying the Vectorscope A Comprehensive Guide for Premiere Pro Color Correction</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-playful-prodigies-the-ultimate-kids-game-compilation/"><u>[New] Playful Prodigies  The Ultimate Kids' Game Compilation</u></a></li>
<li><a href="https://windows11.techidaily.com/can-you-get-rid-of-the-windows-bt-directories/"><u>Can You Get Rid of the Windows ~BT Directories?</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/fastest-video-speed-editors-for-windows-and-macos-for-2024/"><u>Fastest Video Speed Editors for Windows and macOS for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/inizing-the-financial-lifelines-that-drive-tseries-youtube-success/"><u>Scrutinizing the Financial Lifelines that Drive TSeries' Youtube Success</u></a></li>
<li><a href="https://windows11.techidaily.com/direct-path-to-spooler-restart/"><u>Direct Path to Spooler Restart</u></a></li>
<li><a href="https://audio-editing.techidaily.com/boosting-windows-volume-without-spending-a-dime-free-techniques-revealed-for-2024/"><u>Boosting Windows Volume Without Spending a Dime - Free Techniques Revealed for 2024</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-vivid-melodies-for-youtube-content-enhancement-for-2024/"><u>New Vivid Melodies for YouTube Content Enhancement for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-making-excel-viewable-in-notepad/"><u>Strategies: Making Excel Viewable in Notepad</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-convert-soundcloud-music-to-mp3-with-ease-proven-methods/"><u>Updated 2024 Approved Convert Soundcloud Music to MP3 with Ease Proven Methods</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-final-cut-pro-x-jump-cuts-take-your-editing-to-the-next-level-for-2024/"><u>Updated Final Cut Pro X Jump Cuts Take Your Editing to the Next Level for 2024</u></a></li>
</ul></div>
