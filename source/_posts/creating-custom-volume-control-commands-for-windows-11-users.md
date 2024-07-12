---
title: Creating Custom Volume Control Commands for Windows 11 Users
date: 2024-07-11T22:21:43.540Z
updated: 2024-07-12T22:21:43.540Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Creating Custom Volume Control Commands for Windows 11 Users
excerpt: This Article Describes Creating Custom Volume Control Commands for Windows 11 Users
keywords: W11 Volume Control,Windows Command Setup,Personalized Vol Control,User-Defined Commands,Customize Win Commands,Audio Control Scripting,Windows Voice Levels
thumbnail: https://thmb.techidaily.com/ae43e169f6c755c4c2193b461c421a8ddcf3ffe9401c395fee54d3c5c1d37695.jpg
---

## Creating Custom Volume Control Commands for Windows 11 Users

 Not all keyboards include volume control hotkeys for muting, maximizing, and adjusting audio levels. Nor does Windows 11 have any universal sound control keyboard shortcuts. Therefore, some users have to make do with their mouse for volume control.

 However, you can set up custom volume control hotkeys in Windows 11 with some third-party software. Once set up, you’ll be able to change the volume with the press of a few hotkeys instead of fiddling around with sound control bars. Here is how to set up keyboard shortcuts for muting, maximizing, increasing, and decreasing volume with NirCmd and Volume Control.

## How to Download and Extract NirCmd

 NirCmd is a command-line tool that can carry out many useful PC tasks. It has some volume control commands for muting, maximizing, increasing, and reducing sound levels. Although NirCmd doesn’t provide any built-in options for establishing volume control hotkeys, we can set up keyboard shortcuts for its commands.

 First, however, you’ll need to download and extract NirCmd. The app comes packed in a ZIP archive that you’ll need to extract. You can download and extract NirCmd like this.

1. Open the [NirCmd download](https://www.nirsoft.net/utils/nircmd.html) page.
2. Scroll down to the bottom of that page, and click the **Download NirCmd 64-bit** link.
3. Double-click NirCmd’s ZIP to open it.
4. Click **Extract all** on File Explorer’s command bar.  
![The Extract all button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/extract-all-button2.png)
5. Select the **Browse** option to choose an extraction path.
6. Click the **Show extracted files when complete** checkbox to select it.  
![The Extract compressed window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/extract-compressed-window.png)
7. Press the **Extract** button to [extract the ZIP archive in Windows](https://www.makeuseof.com/how-to-extract-zip-files-windows-11/).

## How to Set Up a Mute Hotkey

 When you’ve extracted NirCmd’s archive, no program installation is required. Nor do you even need to launch it in any way. You will, however, need to note down, or copy, NirCmd’s extracted path. Then you can set up volume control shortcuts based on that utility’s commands. This is how you can establish a mute hotkey with NirCmd.

1. First, open the extracted NirCmd folder.
2. Right-click the nircmd EXE and select **Copy as path**.
3. Next, right-click an area of your desktop to select the **New** context menu option.
4. Click **Shortcut** on the submenu.  
![The Shortcut context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/shortcut-option.png)
5. Press the **Ctrl + V** keyboard shortcut to paste the copied NirCmd path into the location box.
6. Then press **Space** key once after the NirCmd path, and enter **mutesysvolume 2** in the location box as shown directly below. The location box should then include: **“NirCmd folder path\\nircmd.exe” mutesysvolume 2**.  
![The mutesysvolume command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/mutesysvolume-command.png)
7. Click **Next** to continue.
8. Enter **Mute** in the shortcut name box, and select the **Finish** option.

 Now you’ve got a Mute shortcut on your desktop. Start playing a video in a browser or media player, and click that shortcut to mute it. You can add a hotkey to that desktop Mute button as follows.

1. Right-click your Mute desktop shortcut to select **Properties** on its context menu.
2. Click inside the **Shortcut key** box to place a text cursor there.
3. Press **M** to set up a **Ctrl + Alt + M** hotkey.  
![The Shortcut key box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/shortcut-key-box3.png)
4. Select **Apply** to save.

 Start playing a video, and press the **Ctrl + Alt + M** keyboard shortcut. You can unmute the sound by pressing **Ctrl + Alt + M** again. Pressing that hotkey both mutes and unmutes audio.

 Don’t delete the Mute desktop shortcut. Deleting that shortcut will also erase the hotkey added to it. So, you’ll need to keep all audio control shortcuts on the desktop for their hotkeys to work.

 If you like, you can also change the icon for the desktop shortcut to a more appealing one. To do that, right-click the shortcut and select **Properties**. Click the **Change shortcut** button, and choose an icon on the window. Select the **OK** and **Apply** options to add the icon.

![The Change icon window and Mute desktop shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/change-icon-window.png)

## How to Set Up a Hotkey for Maximizing Volume

 Aside from a mute hotkey, you can [set up a keyboard shortcut](https://www.makeuseof.com/what-is-a-hotkey-how-to-make-custom/) for maximizing volume. If you want a hotkey to max out volume (just don’t disturb the neighbors), you can create one with NirCmd’s **setsysvolume 65535** command. You can establish a max volume desktop shortcut much the same as a mute one with the Create Shortcut tool. The only difference is that you’ll need to input this command in the location box instead: **“NirCmd folder path\\nircmd.exe” setsysvolume 65535**.

![The setsysvolume command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/setsysvolcommand.png)

 The 65,535 in that command is NirCmd’s maximum decibel value. Clicking your new maximum audio desktop shortcut will max out playback volume. Thereafter, you can apply a hotkey to the max volume desktop shortcut just the same as for the mute one.

## How to Create Volume Up and Down Hotkeys

 NirCmd also has commands that increase or decrease volume by specific values. You can set up hotkeys that activate those commands for raiding or reducing the decibel level. Again, you’ll need to first [set up desktop shortcuts](https://www.makeuseof.com/what-is-desktop-shortcut-how-work/) for those NirCmd commands just the same as for muting or maximizing sound. These are the commands you’ll need to enter into the "Create Shortcut" window’s location box:

 Increase volume by 2,000 units: **“NirCmd folder path\\nircmd.exe” changesysvolume 2000**

 Decrease volume by 5,000 units: **“NirCmd folder path\\nircmd.exe” changesysvolume -5000**

![The changesysvolume command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/changesysvolume-command.png)

 Note that you can change the unit values in those commands. To configure a shortcut to increase volume more, for example, you could input **changesysvolume 5000** in the location box instead. Or enter **changesysvolume -10000** to decrease the decibel level by twice as much. However, all values must be below the maximum of 65,535\.

 When you’ve set up some desktop shortcuts for increasing and reducing volume, right-click them and select **Properties**. You can add new hotkeys to them with their **Shortcut key** boxes as outlined for the mute command. Then press the NirCmd volume up and down hotkeys to your heart’s content to increase and lower the decibel level.

## How to Set Up Custom Volume Control Hotkeys for a Specific App

 Volume Control is a portable third-party app with which you can set up custom volume control hotkeys and assign them to specific apps. Then the custom keyboard shortcuts set will only change the volume for a program you’ve assigned it to. This is how you can set custom volume control hotkeys for a specific app in Windows 11 with Volume Control:

1. Open the [Volume Control](https://www.softpedia.com/get/Multimedia/Audio/Other-AUDIO-Tools/Volume-Control-radj307.shtml) page on Softpedia.
2. Click **Free Download** to view the location options.
3. Select **Secure Download (US)**, which is best for North America.
4. Right-click Windows 11’s **Start** taskbar button to select **File Explorer**.
5. Open the folder that contains the downloaded Volume Control file.

1. Double-click the **VolumeControl** file to open the software (no installation is needed).
2. Click the **Hotkeys** tab in the Volume Control window.
3. Select the **Volume up** checkbox.
4. Click the **Key** drop-down menu and select a key for your hotkey there. You can also select the **Alt**, **Ctrl**, **Shift**, or **Win** checkboxes to extend your hotkey with one of those modifier keys.  
![The Hotkeys tab in Volume Control](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/hotkeys-tab.jpg)
5. Select the **Volume** **up** checkbox and repeat the previous step to set a hotkey for raising the volume.

1. Then select **Toggle Mute** and repeat step nine to set a keyboard shortcut for muting the volume.
2. Now open a program to assign the hotkeys to. A web browser or media player from which you can play music and videos would be ideal.
3. Click the **Mixer** tab to view a list of open apps.  
![The Mixer tab in Volume Control](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-mixer-tab.jpg)
4. Press the **Select** button beside the software to which you want to assign the custom hotkeys.
5. Click the **Lock** checkbox to ensure the volume control hotkeys always remain assigned to the selected software.

 Try out the custom volume hotkeys you’ve set for the software. Play a video within your software if you can. Press the keyboard shortcuts you’ve assigned to the app to raise, lower, and mute its volume. Those hotkeys will only affect the app’s volume level and won’t change the general system sound beyond it. The Volume bar within the **Mixer** tab shows you the audio level for the software.

![A YouTube video in the Opera browser](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/a-youtube-video.jpg)

 You can also create new volume control hotkeys from scratch with Volume Control. To do so, select the **Advanced Hotkeys** checkbox on the **Settings** tab. Then you’ll see a **Create New Hotkey** button on the **Hotkeys** tab you can press to set up new keyboard shortcuts. You can select options on an **Action** drop-down menu with advanced hotkeys enabled.

![The Action drop-down menu for advanced hotkeys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-create-new-hotkey-button.jpg)

## Adjust Playback Volume With Your New Sound Control Hotkeys

 So, you don’t need to get a new keyboard if your current one lacks volume control hotkeys. Simply set up a few custom keyboard shortcuts for muting, maximizing, lowering, and increasing volume with the NirCmd command-line utility or Volume Control. Then you can quickly mute, max out, or raise/lower the decibel level for video and music playback in Windows 11 by pressing those hotkeys.

 However, you can set up custom volume control hotkeys in Windows 11 with some third-party software. Once set up, you’ll be able to change the volume with the press of a few hotkeys instead of fiddling around with sound control bars. Here is how to set up keyboard shortcuts for muting, maximizing, increasing, and decreasing volume with NirCmd and Volume Control.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/decoding-dism-your-ultimate-toolkit-for-fixing-win11/"><u>Decoding DISM: Your Ultimate Toolkit for Fixing Win11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-the-ultimate-noise-free-recording-strategy/"><u>[New] 2024 Approved  The Ultimate Noise-Free Recording Strategy</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-the-purpose-of-pagefilesys-within-os-structure/"><u>Dissecting the Purpose of Pagefile.sys Within OS Structure</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-best-10-gratuitous-online-transformers-for-srt-files/"><u>[New] Best 10 Gratuitous Online Transformers for Srt Files</u></a></li>
<li><a href="https://windows11.techidaily.com/diagnosing-and-fixing-microsoft-windows-nearby-share-malfunction/"><u>Diagnosing and Fixing Microsoft Windows Nearby Share Malfunction</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-display-apple-iphone-8-plus-screen-on-pc-easily-drfone-by-drfone-ios/"><u>How to Display Apple iPhone 8 Plus Screen on PC Easily? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensible-guide-to-counteracting-winerror-0x80071a90/"><u>Comprehensible Guide to Counteracting WinError 0X80071a90</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-visual-voyages-the-most-motivating-instagram-images/"><u>[New] Visual Voyages  The Most Motivating Instagram Images</u></a></li>
<li><a href="https://windows11.techidaily.com/controlling-clock-display-in-windows-11-taskbar/"><u>Controlling Clock Display in Windows 11 Taskbar</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-4-ways-to-trace-motorola-moto-g84-5g-location-drfone-by-drfone-virtual-android/"><u>Top 4 Ways to Trace Motorola Moto G84 5G Location | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/clear-path-to-app-removal-tackling-do-not-have-access-errors/"><u>Clear Path to App Removal: Tackling Do Not Have Access Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/decode-and-dissolve-rectifying-win11-webcam-issue-error-a00f4289/"><u>Decode & Dissolve: Rectifying Win11 Webcam Issue - Error A00F4289</u></a></li>
<li><a href="https://windows11.techidaily.com/consistent-experience-migrating-powertoys-on-new-pcs/"><u>Consistent Experience: Migrating PowerToys on New PCs</u></a></li>
<li><a href="https://extra-support.techidaily.com/perfect-moment-for-podcast-debuts-for-2024/"><u>Perfect Moment for Podcast Debuts for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/disarming-error-dism-0x800f082f-on-microsoft-os/"><u>Disarming Error: DISM 0X800F082F on Microsoft OS</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-the-ultimate-guide-to-unlocking-apple-watch-or-apple-iphone-12-pro-max-from-icloud-by-drfone-ios/"><u>In 2024, The Ultimate Guide to Unlocking Apple Watch Or Apple iPhone 12 Pro Max from iCloud</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-html-display-issues-in-windows-11-email-client/"><u>Correcting HTML Display Issues in Windows 11 Email Client</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-camera-access-overlap-in-windows-apps/"><u>Correcting Camera Access Overlap in Windows Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-discord-setup-woes-on-windows-11/"><u>Correcting Discord Setup Woes on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-clock-divergence-chrome-vs-windows/"><u>Correcting Clock Divergence: Chrome vs Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/dial-back-the-dread-of-an-unresponsive-esc-button-in-windows/"><u>Dial Back the Dread of an Unresponsive Esc Button in Windows</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-from-sd-to-hd-a-beginners-guide-to-pixel-size-and-video-quality-for-2024/"><u>New From SD to HD A Beginners Guide to Pixel Size and Video Quality for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-error-code-zero-on-your-gaming-machine/"><u>Disabling Error Code Zero on Your Gaming Machine</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/transcoding-vimeo-to-mp3-audio-file/"><u>Transcoding Vimeo to MP3 Audio File</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-sound-misstep-solving-xc00d36b4-on-windows/"><u>Decoding Sound Misstep: Solving XC00D36B4 on Windows</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-download-kinemaster-for-macos-a-beginners-guide/"><u>Updated 2024 Approved Download KineMaster for macOS A Beginners Guide</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-secrets-of-snapping-finding-missing-private-images/"><u>2024 Approved  Secrets of Snapping  Finding Missing Private Images</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-expert-picks-8-superior-linux-snapshot-tools/"><u>[Updated] 2024 Approved  Expert Picks  8 Superior Linux Snapshot Tools</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-ace-your-edits-in-depth-guide-to-high-quality-youtube-videos/"><u>2024 Approved  Ace Your Edits  In-Depth Guide to High-Quality YouTube Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-windows-error-code-31-and-network-adapter-issues/"><u>Demystifying Windows Error Code 31 and Network Adapter Issues</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-essential-windows-and-macos-daw-software-ranking-the-best/"><u>New Essential Windows & macOS DAW Software Ranking the Best</u></a></li>
<li><a href="https://windows11.techidaily.com/decode-your-digital-identity-how-to-find-out-what-computer-you-have/"><u>Decode Your Digital Identity: How to Find Out What Computer You Have</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-in-2024-aspect-ratio-made-simple-a-calculator-for-image-enthusiasts/"><u>Updated In 2024, Aspect Ratio Made Simple A Calculator for Image Enthusiasts</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-pc-and-macs-leading-choice-in-screen-recording-tools/"><u>[Updated] In 2024, PC & Mac's Leading Choice in Screen Recording Tools</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-guffaw-generation-generating-7-hilarious-video-moments-online-for-2024/"><u>[Updated] Guffaw Generation  Generating 7 Hilarious Video Moments Online for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-to-unfreezing-window-taskbar/"><u>Comprehensive Guide to Unfreezing Window TaskBar</u></a></li>
<li><a href="https://windows11.techidaily.com/cut-through-the-frustration-swift-solutions-for-ms-teams-error-80080300-in-win11/"><u>Cut Through the Frustration: Swift Solutions for MS Teams Error 80080300 in Win11</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-how-to-turn-off-a-discord-server-device-wise/"><u>[Updated] 2024 Approved  How to Turn Off a Discord Server Device-Wise</u></a></li>
<li><a href="https://techidaily.com/complete-guide-to-hard-reset-your-nokia-xr21-drfone-by-drfone-reset-android-reset-android/"><u>Complete Guide to Hard Reset Your Nokia XR21 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensible-guide-to-revoking-custom-search-on-windows-11/"><u>Comprehensible Guide to Revoking Custom Search on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/diving-into-windows-n-types-benefits-and-downfalls/"><u>Diving Into Windows N Types: Benefits and Downfalls</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-transforming-plain-words-into-3d-marvels-ps-guide/"><u>[Updated] Transforming Plain Words Into 3D Marvels  PS Guide</u></a></li>
<li><a href="https://apple-account.techidaily.com/everything-to-know-about-apple-id-password-requirements-for-iphone-xs-max-by-drfone-ios/"><u>Everything To Know About Apple ID Password Requirements For iPhone XS Max</u></a></li>
<li><a href="https://windows11.techidaily.com/curing-windows-security-hiccups-in-win-11-system/"><u>Curing Windows Security Hiccups in Win 11 System</u></a></li>
<li><a href="https://windows11.techidaily.com/command-prompt-mastery-the-fundamental-20-cmd-commands-to-know/"><u>Command Prompt Mastery: The Fundamental 20 CMD Commands to Know</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-rise-to-greatness-with-these-10-elevating-films/"><u>[Updated] Rise to Greatness with These 10 Elevating Films</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-unveiling-the-backbone-of-music-techniques-to-extract-and-adapt-rhythmic-structures/"><u>Updated In 2024, Unveiling the Backbone of Music Techniques to Extract and Adapt Rhythmic Structures</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-resource-locks-in-windows-11-environments/"><u>Disabling Resource Locks in Windows 11 Environments</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-mobile-audio-enhancers-for-swift-soundplay/"><u>[Updated] Mobile Audio Enhancers for Swift Soundplay</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-how-to-add-and-change-thumbnails-of-twitter-videos/"><u>[New] 2024 Approved  How to Add and Change Thumbnails of Twitter Videos?</u></a></li>
<li><a href="https://windows11.techidaily.com/dial-down-display-flicker-in-windows-11-devices/"><u>Dial Down Display Flicker in Windows 11 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/compre-written-guide-to-repair-xbox-live-glitches/"><u>Compre Written Guide To Repair Xbox Live Glitches</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/perfecting-youtube-videos-with-angle-rotation-mastery/"><u>Perfecting YouTube Videos with Angle Rotation Mastery</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-easy-to-follow-guide-recording-non-root-android-sounds/"><u>In 2024, Easy-to-Follow Guide  Recording Non-Root Android Sounds</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>