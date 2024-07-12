---
title: "Command Line Conjuring: Windows' New Feature"
date: 2024-07-11T22:24:40.980Z
updated: 2024-07-12T22:24:40.980Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Command Line Conjuring: Windows' New Feature"
excerpt: "This Article Describes Command Line Conjuring: Windows' New Feature"
keywords: Command Line Magic,Window's CLI Tools,Windows Console Tricks,Cmdline Interface Enhancements,PowerShell Wizardry,Terminal Feature Updates,WinCLI Capabilities
thumbnail: https://thmb.techidaily.com/bbc14b435660c967866cf3c17d84e88db2c1688390de1d8678d61e0a94d5c4d0.png
---

## Command Line Conjuring: Windows' New Feature

 God Mode enables you to access hundreds of Control Panel applets from a single All Tasks window. That’s a handy thing to activate in Windows 11 for accessing Control Panel settings and creating shortcuts that open them.

 Many users activate God Mode by setting up desktop shortcuts that open the All Tasks window. However, you can instead add a **God Mode** option to the desktop’s context menu in Windows 11\. Then the All Tasks window will be directly accessible on your right-click menu. This is how you can add God Mode to Windows 11’s context menu.

## How to Add God Mode to the Context Menu by Manually Editing the Registry

 You can add God Mode to Windows 11’s desktop context menu by manually tweaking the registry. The tweaking required is relatively simple to apply and involves adding a couple of new registry entries to the Shell key. Follow these steps to manually add God Mode to Windows 11’s context menu:

1. Open the Registry Editor (see [how to open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) for instructions).
2. Click in the address bar at the top of Registry Editor to delete the current key location.
3. Input this Shell key path in the address bar and hit **Enter**:  
`Computer\HKEY_CLASSES_ROOT\DesktopBackground\Shell\`
4. Right-click on **Shell** in Registry Editor’s navigation sidebar to select **New** and **Key**.  
![The New > Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/new-key-options.jpg)
5. Type **God Mode** in the key’s text box.

1. Right-click **God Mode** and select the **New** \> **Key** context menu options again.
2. Input **command** within the subkey’s text box.  
![The God Mode registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/god-mode-key.jpg)
3. Double-click on the **(Default)** string for the new command key you’ve added to the registry.
4. Input **explorer** **shell:::{ED7BA470-8E54-465E-825C-99712043E01C}** within the **Data value** box and click **OK**.  
![The Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/edit-string-window.jpg)
5. Click on the Registry Editor’s **X** button.

 Check out the new **God Mode** option on your context menu for opening Task View. Right-click somewhere on the desktop background image and select **Show more options**. Then select **God Mod** to bring up the **Task View** window. You can open a multitude of Control Panel applets from there.

![A God Mode context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/god-mode-option.jpg)

 If you ever change your mind about having a **God Mode** context menu option, open the Shell key in Registry Editor again. Then right-click on the **God Mode** key you added and select delete. Click **Yes** to erase the **God Mode** key along with its **command** subkey.

![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-delete-option.jpg)

## How to Add God Mode to the Context Menu With Right-Click Extender

 The manual registry tweak method is straightforward, but you can add God Mode to the context menu with third-party software instead if preferred. Right-Click Extender is customization software that includes an option for adding God Mode to the context menu. This is how you can add God Mode to your context menu with Right-Click Extender:

1. Open this [Right-Click Extender](https://www.softpedia.com/get/Tweak/System-Tweak/Right-Click-Extender.shtml) download page.
2. Click on the **Download** and **Secure Download (US)** options and download the file.
3. Extract the Right-Click Extender archive by following the instructions within this guide to [unzipping ZIP files in Windows](https://www.makeuseof.com/unzip-files-windows-10/).  
![The Extract Compressed (Zipped) Folders window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/extract-compressed-zip-folder.jpg)
4. Open the extracted Right-Click Extender directory and its Right-Click Extender v2 subfolder.
5. Double-click the Right-Click Extender v2 application file.
6. Click on the **Desktop** tab in Right-Click Extender.
7. Select the **All Tasks (GodMode)** setting and its Icon checkbox.  
![The Right-Click Extender v2 window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-all-tasks-setting.jpg)
8. Press the green **Apply** button.

 Now you’ll see a new **God Mode** option on Windows 11’s classic context menu. This option will also have an icon by it. Click on **God Mode** to view the list of Control Panel applets.

## How to Create Control Panel Shortcuts From God Mode's All Tasks Window

 The Task View window the God Mode context menu option opens makes hundreds of Control Panel applets more accessible. You can open whatever Control Panel settings you need from that window. However, the list of applets shown in that window is quite long.

 Task View makes it easy to create desktop shortcuts for opening the Control Panel applets you need to access more regularly. To do so, left-click an applet or utility in the Task View window, drag it onto the desktop, and release the mouse button. Then you can click on the desktop shortcut to open its Control Panel applet whenever needed.

![The All Tasks (God Mode) window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-all-tasks-window.jpg)

## Make the Most of God Mode on Windows

 Adding God Mode to your desktop’s context menu will enable you to access a plethora of Control Panel applets and tools within a single window in a couple of clicks. That will save you from rummaging through the Control Panel to find certain applets and settings when needed. Plus, you can make more essential Control Panel applets even more accessible by creating shortcuts for them from the Task View window.

 Many users activate God Mode by setting up desktop shortcuts that open the All Tasks window. However, you can instead add a **God Mode** option to the desktop’s context menu in Windows 11\. Then the All Tasks window will be directly accessible on your right-click menu. This is how you can add God Mode to Windows 11’s context menu.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://android-frp.techidaily.com/in-2024-frp-hijacker-by-hagard-download-and-bypass-your-realme-c67-5g-frp-locks-by-drfone-android/"><u>In 2024, FRP Hijacker by Hagard Download and Bypass your Realme C67 5G FRP Locks</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-fixing-error-0x80040610-in-microsoft-office-suite/"><u>Decoding and Fixing Error 0X80040610 in Microsoft Office Suite</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-windows-11s-user-identity-framework/"><u>Dissecting Windows 11'S User Identity Framework</u></a></li>
<li><a href="https://extra-resources.techidaily.com/excessive-tiktok-drafts-simplify-with-smart-editing-techniques/"><u>Excessive TikTok Drafts? Simplify with Smart Editing Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/conjoining-android-and-windows-11-tablets-effortlessly/"><u>Conjoining Android and Windows 11 Tablets Effortlessly</u></a></li>
<li><a href="https://windows11.techidaily.com/correct-keyboard-fixes-for-windows-11s-unresponsive-f-keys/"><u>Correct: Keyboard Fixes for Windows 11'S Unresponsive F Keys</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/boosting-views-with-captivating-intros-filmed-in-imovie-for-2024/"><u>Boosting Views with Captivating Intros Filmed in iMovie for 2024</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-can-i-utilize-frequency-slicing-for-superior-acoustic-performance-for-2024/"><u>Updated Can I Utilize Frequency Slicing for Superior Acoustic Performance for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/dial-up-the-velocity-fixing-your-stuttery-pc/"><u>Dial Up the Velocity: Fixing Your Stuttery PC</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-check-if-your-samsung-galaxy-m14-4g-is-unlocked-by-drfone-android/"><u>How To Check if Your Samsung Galaxy M14 4G Is Unlocked</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-overcoming-the-windows-virtualbox-efail-error/"><u>Decoding and Overcoming the Windows Virtualbox E_FAIL Error</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-fcps-ultimate-editing-aid-best-10-plug-ins/"><u>[Updated] FCP's Ultimate Editing Aid  Best 10 Plug-Ins</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-compatibility-issues-windows-troubleshooting-blueprint/"><u>Conquer Compatibility Issues: Windows Troubleshooting Blueprint</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/2024-approved-master-your-audio-projects-with-these-5-indispensable-android-applications-for-audio-editing/"><u>2024 Approved Master Your Audio Projects with These 5 Indispensable Android Applications for Audio Editing</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-transformational-tools-in-youtube-studio-for-creators/"><u>[Updated] Transformational Tools in YouTube Studio for Creators</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/stop-motion-made-easy-top-5-online-tools-free-and-paid-for-2024/"><u>Stop Motion Made Easy Top 5 Online Tools (Free and Paid) for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-solution-to-stop-0xf0831-in-windows-11/"><u>Comprehensive Solution to Stop 0xF0831 in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-auto-triggered-console-crashes-on-windows/"><u>Disabling Auto-Triggered Console Crashes on Windows</u></a></li>
<li><a href="https://facebook.techidaily.com/becoming-meta-facebook-reveals-its-visionary-transformation-strategy/"><u>Becoming Meta: Facebook Reveals Its Visionary Transformation Strategy</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-correcting-unspecified-obs-recording-glitches/"><u>Decoding and Correcting Unspecified OBS Recording Glitches</u></a></li>
<li><a href="https://windows11.techidaily.com/combining-audioscapes-and-visuals-snipping-tool-guide-max-156/"><u>Combining Audioscapes & Visuals: Snipping Tool Guide (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-power-management-on-win-11/"><u>Efficient Power Management on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/ditch-default-home-port-on-w11-settings-interface/"><u>Ditch Default Home Port on W11 Settings Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/controlling-highlight-features-on-windows-11-pcs/"><u>Controlling Highlight Features on Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-ms-resouce-issue-for-text-display/"><u>Correcting Ms-Resouce Issue for Text Display</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-comprehensive-list-of-high-quality-game-entrance-makers-online/"><u>[Updated] 2024 Approved  Comprehensive List of High-Quality Game Entrance Makers Online</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-the-obscure-fixing-white-out-screens-in-win1011/"><u>Clearing the Obscure: Fixing White Out Screens in WIN10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/determining-hddssd-in-windows-a-step-by-step-guide/"><u>Determining HDD/SSD in Windows: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/ditching-the-default-store-on-new-windows-11/"><u>Ditching the Default Store on New Windows 11</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-complete-guide-to-crafting-killer-youtube-outros/"><u>[Updated] Complete Guide to Crafting Killer YouTube Outros</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-camera-not-detected-error-on-windows-11-pcs/"><u>Correcting “Camera Not Detected” Error on Windows 11 PCs</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-10-fake-gps-location-apps-on-android-of-your-oppo-a38-drfone-by-drfone-virtual/"><u>In 2024, 10 Fake GPS Location Apps on Android Of your Oppo A38 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-dual-monitor-mishaps-on-your-pc/"><u>Correcting Dual Monitor Mishaps on Your PC</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-learning-the-process-of-acquiring-movie-maker-6/"><u>[Updated] Learning the Process of Acquiring Movie Maker 6</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-film-like-a-pro-easy-movie-creation-for-beginners/"><u>New In 2024, Film Like a Pro Easy Movie Creation for Beginners</u></a></li>
<li><a href="https://iphone-location.techidaily.com/in-2024-hide-location-on-apple-iphone-6-plus-and-android-without-others-knowing-drfone-by-drfone-virtual-ios/"><u>In 2024, Hide location on Apple iPhone 6 Plus and Android without others knowing | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/thinking-about-changing-your-netflix-region-without-a-vpn-on-infinix-note-30-5g-drfone-by-drfone-virtual-android/"><u>Thinking About Changing Your Netflix Region Without a VPN On Infinix Note 30 5G? | Dr.fone</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-unveiling-hand-trackings-evolution-and-practice/"><u>2024 Approved  Unveiling Hand Tracking's Evolution and Practice</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-soundtrack-strategists-guide-to-youtube-playlists/"><u>In 2024, The Soundtrack Strategist's Guide to YouTube Playlists</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-asus-proart-pa-329q-a-deep-dive-into-high-resolution-monitoring/"><u>[Updated] Asus ProArt PA 329Q  A Deep Dive Into High-Resolution Monitoring</u></a></li>
<li><a href="https://windows11.techidaily.com/directing-system-thermal-output-with-customization/"><u>Directing System Thermal Output with Customization</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-a-guide-to-enhancing-obs-with-free-lut-downloads/"><u>[Updated] A Guide to Enhancing OBS with Free LUT Downloads</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-where-windows-keeps-snaps/"><u>Discover Where Windows Keeps Snaps</u></a></li>
<li><a href="https://windows11.techidaily.com/critiquing-7-perplexing-windows-11-aesthetics/"><u>Critiquing 7 Perplexing Windows 11 Aesthetics</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-dance-away-worries-with-these-20-soothing-country-hits-tiktok-edition/"><u>[New] 2024 Approved  Dance Away Worries with These 20 Soothing Country Hits (TikTok Edition)</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-fix-for-msvcr110dll-absence/"><u>Comprehensive Fix for msvcr110.dll Absence</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-deciphering-calm-techniques-to-reduce-audio-disturbances-from-natural-sources-in-digital-recordings/"><u>Updated 2024 Approved Deciphering Calm Techniques to Reduce Audio Disturbances From Natural Sources in Digital Recordings</u></a></li>
<li><a href="https://windows11.techidaily.com/disable-windows-11s-covert-surveillance/"><u>Disable Windows 11'S Covert Surveillance</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-windows-screen-size-setsbacks-7-easy-solutions/"><u>Conquering Windows' Screen Size Setsbacks: 7 Easy Solutions</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-cast-oppo-find-x6-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>How to Cast Oppo Find X6 Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/full-guide-to-unlock-apple-iphone-15-pro-max-with-itunes-by-drfone-ios/"><u>Full Guide to Unlock Apple iPhone 15 Pro Max with iTunes</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-systemsettings-executable-errors-on-windows-11/"><u>Correcting SystemSettings Executable Errors on Windows 11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-enhancing-user-experience-a-quick-how-to-for-youtube-cc-and-subtitles-for-2024/"><u>[Updated] Enhancing User Experience  A Quick How-To for YouTube CC & Subtitles for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/dealing-with-inaccessible-steam-servers-in-home-pc-setups/"><u>Dealing With Inaccessible Steam Servers in Home PC Setups</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-best-video-editing-software-for-adding-music-and-soundtracks/"><u>Updated Best Video Editing Software for Adding Music and Soundtracks</u></a></li>
<li><a href="https://windows11.techidaily.com/delving-into-windows-pe-file-structure/"><u>Delving Into Windows PE File Structure</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-device-disabled-issue-with-error-code-22-on-windows-11/"><u>Correcting Device Disabled Issue with Error Code 22 on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/dism-tactics-restoring-windows-11-os-images/"><u>DISM Tactics: Restoring Windows 11 OS Images</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/2024-approved-coqui-voice-cloning-the-ultimate-solution-to-streamline-audio-content/"><u>2024 Approved Coqui Voice Cloning The Ultimate Solution to Streamline Audio Content</u></a></li>
<li><a href="https://windows11.techidaily.com/clean-windows-search-interface-no-icons/"><u>Clean Windows Search Interface: No Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-idle-computing-with-auto-sleep-in-w10w11/"><u>Conquering Idle Computing with Auto Sleep in W10/W11</u></a></li>
<li><a href="https://windows11.techidaily.com/curtailing-spontaneous-terminal-trigger-activations/"><u>Curtailing Spontaneous Terminal Trigger Activations</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-facebook-streaming-made-simple-tips-for-android-and-iphones-for-2024/"><u>[Updated] Facebook Streaming Made Simple  Tips for Android & iPhones for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/covertly-masking-taskbars-language-feature-in-win11/"><u>Covertly Masking Taskbar's Language Feature in Win11</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-elevate-your-youtube-presence-uncovering-the-6-key-strategies-to-boost-retention-rates/"><u>[New] In 2024, Elevate Your YouTube Presence  Uncovering the 6 Key Strategies to Boost Retention Rates</u></a></li>
<li><a href="https://windows11.techidaily.com/connected-scribbles-using-stickies-across-all-devices-in-win11/"><u>Connected Scribbles: Using Stickies Across All Devices in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-a-plan-for-file-explorer-in-windows-11/"><u>Crafting a Plan for File Explorer in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-folder-tab-glitches-in-windows-11/"><u>Conquering Folder Tab Glitches in Windows 11</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-decoding-the-top-rival-to-sharex/"><u>[New] In 2024, Decoding the Top Rival to ShareX</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>