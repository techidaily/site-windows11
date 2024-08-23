---
title: "Win11 Audio Levels on Your Terms: Designing Your Shortcuts"
date: 2024-08-22T21:36:17.402Z
updated: 2024-08-23T21:36:17.402Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Win11 Audio Levels on Your Terms: Designing Your Shortcuts"
excerpt: "This Article Describes Win11 Audio Levels on Your Terms: Designing Your Shortcuts"
keywords: Win11 Sound Customization,Windows 11 Audio Control,Win11 Volume Modes,Personalize Win11 Sounds,Win11 Shortcuts for Music,Win11 Auditory Preferences,Optimizing Win11 Sound Settings
thumbnail: https://thmb.techidaily.com/06629510e11e9d29470adf181e231bb23d34ab4b20d9291b76fb465837bc25f3.jpg
---

## Win11 Audio Levels on Your Terms: Designing Your Shortcuts

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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->
## How to Create Volume Up and Down Hotkeys

 NirCmd also has commands that increase or decrease volume by specific values. You can set up hotkeys that activate those commands for raiding or reducing the decibel level. Again, you’ll need to first [set up desktop shortcuts](https://www.makeuseof.com/what-is-desktop-shortcut-how-work/) for those NirCmd commands just the same as for muting or maximizing sound. These are the commands you’ll need to enter into the "Create Shortcut" window’s location box:

 Increase volume by 2,000 units: **“NirCmd folder path\\nircmd.exe” changesysvolume 2000**

 Decrease volume by 5,000 units: **“NirCmd folder path\\nircmd.exe” changesysvolume -5000**

![The changesysvolume command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/changesysvolume-command.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901410&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix Pro - Software based live production. vMix Pro includes everything in vMix 4K plus 8 channels of Replay and 8 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
 Note that you can change the unit values in those commands. To configure a shortcut to increase volume more, for example, you could input **changesysvolume 5000** in the location box instead. Or enter **changesysvolume -10000** to decrease the decibel level by twice as much. However, all values must be below the maximum of 65,535\.

 When you’ve set up some desktop shortcuts for increasing and reducing volume, right-click them and select **Properties**. You can add new hotkeys to them with their **Shortcut key** boxes as outlined for the mute command. Then press the NirCmd volume up and down hotkeys to your heart’s content to increase and lower the decibel level.

<!-- affiliate ads begin -->

<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
5. Click the **Lock** checkbox to ensure the volume control hotkeys always remain assigned to the selected software.

 Try out the custom volume hotkeys you’ve set for the software. Play a video within your software if you can. Press the keyboard shortcuts you’ve assigned to the app to raise, lower, and mute its volume. Those hotkeys will only affect the app’s volume level and won’t change the general system sound beyond it. The Volume bar within the **Mixer** tab shows you the audio level for the software.

![A YouTube video in the Opera browser](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/a-youtube-video.jpg)

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You can also create new volume control hotkeys from scratch with Volume Control. To do so, select the **Advanced Hotkeys** checkbox on the **Settings** tab. Then you’ll see a **Create New Hotkey** button on the **Hotkeys** tab you can press to set up new keyboard shortcuts. You can select options on an **Action** drop-down menu with advanced hotkeys enabled.

![The Action drop-down menu for advanced hotkeys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-create-new-hotkey-button.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## Adjust Playback Volume With Your New Sound Control Hotkeys

 So, you don’t need to get a new keyboard if your current one lacks volume control hotkeys. Simply set up a few custom keyboard shortcuts for muting, maximizing, lowering, and increasing volume with the NirCmd command-line utility or Volume Control. Then you can quickly mute, max out, or raise/lower the decibel level for video and music playback in Windows 11 by pressing those hotkeys.

 However, you can set up custom volume control hotkeys in Windows 11 with some third-party software. Once set up, you’ll be able to change the volume with the press of a few hotkeys instead of fiddling around with sound control bars. Here is how to set up keyboard shortcuts for muting, maximizing, increasing, and decreasing volume with NirCmd and Volume Control.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-clash-for-dominance-leading-royale-games/"><u>[New] 2024 Approved  Clash for Dominance  Leading Royale Games</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-best-practices-for-high-quality-remote-podcasts/"><u>[New] Best Practices for High-Quality Remote Podcasts</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-masterclass-in-capturing-video-frames/"><u>[New] In 2024, Masterclass in Capturing Video Frames</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-innovative-strategies-for-recording-in-audacity/"><u>[New] Innovative Strategies for Recording in Audacity</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-finding-icons-a-targeted-approach-to-instas-powerful-voices/"><u>[Updated] In 2024, Finding Icons  A Targeted Approach to Insta's Powerful Voices</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-srt-decoding-for-windows-and-mac-users/"><u>[Updated] SRT Decoding for Windows & Mac Users</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-analyzing-the-roi-of-sns-hdr-pro-vs-other-hdr-tools/"><u>2024 Approved  Analyzing the ROI of SNS HDR Pro Vs. Other HDR Tools</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-infusing-life-into-jujutsu-kaisen-with-tiktok-videos/"><u>2024 Approved  Infusing Life Into Jujutsu Kaisen with TikTok Videos</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-teach-you-to-transfer-files-from-infinix-smart-8-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways To Teach You To Transfer Files from Infinix Smart 8 to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/discover-the-premier-shopping-hubs-for-bespoke-gift-wraps-and-cases-for-2024/"><u>Discover the Premier Shopping Hubs for Bespoke Gift Wraps & Cases for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-empty-sections-of-navigation-view/"><u>Fixing Empty Sections of Navigation View</u></a></li>
<li><a href="https://windows11.techidaily.com/from-mobile-to-desktop-utilizing-smartphone-mic/"><u>From Mobile to Desktop: Utilizing Smartphone Mic</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1722975860705-get-your-logitech-g29-steering-wheel-drivers-for-pcs-running-windows-10117-now/"><u>Get Your Logitech G29 Steering Wheel Drivers for PCs Running Windows 10/11/7 Now!</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-maintain-a-single-wallpaper-in-win11/"><u>How to Maintain a Single Wallpaper in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-rectify-windows-auditory-restart-troubles-on-wake/"><u>How to Rectify Windows Auditory Restart Troubles on Wake</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-to-resurrect-your-chatgpt-usage-post-block/"><u>How to Resurrect Your ChatGPT Usage Post-Block</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-av1-triumph-surpassing-vp9-performance/"><u>In 2024, AV1 Triumph  Surpassing VP9 Performance</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-sharefake-location-on-whatsapp-for-vivo-y100a-drfone-by-drfone-virtual-android/"><u>In 2024, How to Share/Fake Location on WhatsApp for Vivo Y100A | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-icloud-separation-how-to-disconnect-apple-iphone-6s-plus-and-ipad-by-drfone-ios/"><u>In 2024, iCloud Separation How To Disconnect Apple iPhone 6s Plus and iPad</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/income-accumulation-with-cosmetic-videos/"><u>Income Accumulation with Cosmetic Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/instant-fix-resetting-windows-11-search-preferences/"><u>Instant Fix: Resetting Windows 11 Search Preferences</u></a></li>
<li><a href="https://fake-location.techidaily.com/ispoofer-is-not-working-on-infinix-hot-40-fixed-drfone-by-drfone-virtual-android/"><u>iSpoofer is not working On Infinix Hot 40? Fixed | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/microsoft-enhances-windows-11-with-ai-taskbar-companion-for-effortless-management/"><u>Microsoft Enhances Windows 11 with AI Taskbar Companion for Effortless Management</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-in-pc-device-activation-during-sleep/"><u>Navigating In-PC Device Activation During Sleep</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-microsoft-works-installation-on-latest-windows/"><u>Navigating Microsoft Works Installation on Latest Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-limited-admin-rights-in-winsec-errors/"><u>Overcoming Limited Admin Rights in WinSec Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/reducing-unnecessary-batch-jobs/"><u>Reducing Unnecessary Batch Jobs</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-for-non-functional-audio-on-win-10/"><u>Remedy for Non-Functional Audio on Win 10</u></a></li>
<li><a href="https://windows11.techidaily.com/resolve-system-hiccups-with-these-10-windows-tools/"><u>Resolve System Hiccups with These 10 Windows Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-regedit-absent-on-windows-systems/"><u>Resolving Regedit Absent on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/saying-goodbye-to-apps-on-windows-11-a-compact-guide-98-chars/"><u>Saying Goodbye to Apps on Windows 11 - A Compact Guide (98 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-social-connectivity-winning-at-fbm-glitches/"><u>Seamless Social Connectivity: Winning at FBM Glitches</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-your-computer-with-windows-hello-fingerprint/"><u>Securing Your Computer with Windows Hello Fingerprint</u></a></li>
<li><a href="https://windows11.techidaily.com/signs-of-trouble-is-factory-reset-right-for-your-pc/"><u>Signs of Trouble: Is Factory Reset Right for Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/terminal-tactics-pinpointing-your-ip-in-windows/"><u>Terminal Tactics: Pinpointing Your IP in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-guide-to-twinning-your-tablet-and-pc-in-w11/"><u>The Essential Guide to Twinning Your Tablet and PC in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-to-eradicate-the-abrupt-termination-error-in-roblox-games/"><u>Tips to Eradicate the Abrupt Termination Error in Roblox Games</u></a></li>
<li><a href="https://howto.techidaily.com/top-10-fixes-for-phone-keep-disconnecting-from-wi-fi-on-vivo-y100i-power-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 10 Fixes for Phone Keep Disconnecting from Wi-Fi On Vivo Y100i Power 5G | Dr.fone</u></a></li>
<li><a href="https://win-able.techidaily.com/troubleshooting-steps-resolving-crashes-in-forza-horizon-5-on-windows/"><u>Troubleshooting Steps: Resolving Crashes in Forza Horizon 5 on Windows</u></a></li>
<li><a href="https://change-location.techidaily.com/ultimate-guide-to-get-the-meltan-box-pokemon-go-for-samsung-galaxy-a05-drfone-by-drfone-virtual-android/"><u>Ultimate guide to get the meltan box pokemon go For Samsung Galaxy A05 | Dr.fone</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-how-to-create-a-movie-in-minutes-a-quick-start-guide-for-2024/"><u>Updated How to Create a Movie in Minutes A Quick Start Guide for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/-editing-essentials-building-youtube-trailers-in-filmora-for-2024/"><u>Video Editing Essentials  Building YouTube Trailers in Filmora for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/win-your-way-out-of-secure-boot-stumbles-with-these-fixes/"><u>Win Your Way Out of Secure Boot Stumbles with These Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/workaround-to-avoid-discord-autostarting-on-pc/"><u>Workaround to Avoid Discord Autostarting on PC</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>