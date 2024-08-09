---
title: Crafting an Efficient Menu Choice for Regular System Checks on Win11+11
date: 2024-08-08T06:00:24.852Z
updated: 2024-08-09T06:00:24.852Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Crafting an Efficient Menu Choice for Regular System Checks on Win11+11
excerpt: This Article Describes Crafting an Efficient Menu Choice for Regular System Checks on Win11+11
keywords: Win11 Menu Checkup,Regular PC Health,Win11 Diagnostics,System Optimize Win11,Win11 Maintenance Tips,Efficient Win11 Updates,Win11+11 SysCheck Routine
thumbnail: https://thmb.techidaily.com/cd61def31c266f510e96724b2a8477792657278ca4fb179ccb3f421fcf0aa55a.jpg
---

## Crafting an Efficient Menu Choice for Regular System Checks on Win11+11

 Microsoft regularly releases patch updates for both Windows 10 and 11 every month. These patch updates typically address security vulnerabilities and fix Windows bugs and issues. Although those updates are usually automatically installed, sometimes your PC will miss the memo. And sometimes, the update itself is an optional download.

 To ensure your Windows 11/10 PC has all the patch updates available for it, it’s a good idea to check for new ones via Settings. The **Windows Update** tab includes a **Check for updates** button. You can add a shortcut for that tab to the desktop’s context menu with the method below.

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Add a Check for Updates Shortcut to the Context Menu

 Windows 11 doesn’t include any built-in options for adding shortcuts to the desktop’s right-click context menu. However, you can still add a **Check for Updates** shortcut for the **Windows Update** tab to that menu by [manually editing the registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/). Once done, you can open the **Windows Update** tab directly from the desktop’s context menu.

 To add that context menu shortcut, edit the registry as follows:

1. Right-click the **Start** button and select the **Run** shortcut to launch that accessory.
2. [Open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) by typing **regedit** in the **Open** box and clicking **OK**.
3. Then navigate to the **Computer** \> **HKEY\_CLASSES\_ROOT** \> **DesktopBackground** \> **Shell** registry key.
4. Right-click the **Shell** key to select the **New** submenu option.
5. Select the **Key** option.  
<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Key option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/key-option.png)

1. Type **Check for Updates** to be the new key’s name.
2. Right-click the **Check for Updates** key and select **New** on the context menu.
3. Click the **Key** option again.
4. Now input **command** for the new key’s name.
5. Select the **Check for Updates** key, and then right-click a space on the right side of the Registry Editor to select **New > String Value**.  
![The String Value option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/string-value-option.png)

1. Type **SettingsURI** to be the new string’s name.
2. Double-click **SettingsURI** to open an Edit String window.
3. Type **ms-settings:windowsupdate-action** within the Value data box, and click **OK**.  
![The Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/edit-string-window.png)
4. Right-click the **command** key and select the **New** \> **String Value** options.
5. Enter the string title **DelegateExecute**, and press the **Return** key.  
![The DelegateExecute string for the command key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/delegateexecute_string.png)
6. Double-click the **DelegateExecute** string to bring up its Value data box.
7. Type **{556FF0D6-A1EE-49E5-9FA4-90AE116AD744}** in the Value data text box, and press the **OK** button.
8. Close the Registry Editor’s window.

 Now right-click an area of your Windows 11 desktop and select **Show more options** to bring up the classic context menu. If you’ve edited the registry correctly, that menu will include a **Check for Updates** option. Select that option to open Settings’ **Windows Update** tab. Then you can click the **Check for updates** button on that tab.

![The Check for Updates context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/check-for-updates-context-menu-option.png)

 Alternatively, press the **Shift** + **F10** hotkey to bring up the classic context menu without right-clicking the desktop. That keyboard shortcut opens the classic context menu at the top left of the desktop. Then you can select **Check for Updates** from there to bring up the tab shown below.

![The Windows Update tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/check_for_updates_button.png)

 This registry trick works much the same on Windows 10\. The only difference is that you won’t need to select **Show more options**. As Windows 10’s desktop context menu is the classic one, it doesn’t include **Show more options**. You can select **Check for Updates** on its primary context menu.

 If you ever want to remove the **Check for Updates** shortcut from the context menu, open the **Shell** key in the Registry Editor again. Then right-click the **Check for Updates** key to select **Delete**.

## Add a Windows Update Submenu to the Context Menu With Winaero Tweaker

 Winaero Tweaker is a freely available customization software for Windows with which you can customize the context menu in many ways. That software has an option you can select to add a **Windows Update** submenu to the context menu, which includes a **Check for updates** shortcut. This is how you can add a **Check for updates** shortcut to the desktop’s right-click menu with Winaero Tweaker:

1. Go to this [Winaero Tweaker webpage](https://winaero.com/download-winaero-tweaker/) in your browsing software.
2. Next, click the **Click here to download file** link.
3. Install and run the Winaero Tweaker software with the downloaded setup file. This [Winaero Tweaker customization guide](https://www.makeuseof.com/windows-11-winaero-tweaker-guide/) includes full installation instructions for that software.
4. Double-click the **Context menu** category within Winaero Tweaker’s left sidebar.
5. Click on the **Windows Update** setting.  
<!-- affiliate ads begin -->
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Add Windows Update submenu to Desktop context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-add-windows-update-to-context-menu-option.jpg)
6. Select the **Add Windows Update submenu to Desktop context menu** option.

 Now look at the new Windows Update submenu on the desktop’s context menu. Press **Shift** \+ **F10** to view the classic context menu. Move the cursor over the **Windows Update** submenu to view its options. There you can select a **Check for updates** option to bring up the **Check for updates** button.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->
![The Windows Update submenu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-windows-update-submenu.jpg)

 The **Windows Update** submenu also has four other shortcuts to update settings. Click **Update history** to view the installed update list. Or select **Advanced options** to bring up the additional settings for updates. The **Restart options** shortcut opens the settings for scheduling update times.

 Winaero Tweaker also has a customization option for adding a **Windows Update** shortcut to the Control panel. To access that option, click **Settings and** **Control Panel** \> **Add Windows Update** in Winaero Tweaker’s sidebar. Click the **Add Windows Update to Control Panel\\System and Security** checkbox to select that option.

![The Add Windows Update to Control Panel option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-add-windows-update-to-control-panel-option.jpg)

 Then you’ll see a **Windows Update** shortcut within the Control Panel. [Open the Control Panel](https://www.makeuseof.com/windows-11-open-control-panel/) and click the **System and Security** category. Clicking the **Windows Update** shortcut there will open the **Settings** tab with the **Check for updates** button.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Windows Update Control Panel shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-update-in-control-panel.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->
## Keep an Eye Out For New Windows Updates

 So, now you can select a handy **Check for Updates** shortcut on your desktop’s context menu. That shortcut will save you from having to manually open Settings and its **Windows Update** tab whenever you need to check for updates. Instead, you can simply click the **Check for Updates** context menu option to open the update tab directly from the desktop.

 Select that shortcut to keep an eye out for new updates regularly. When optional updates are available, you’ll see them listed on the tab with **Download and install** options. Clicking **Check for updates** will automatically download and install available updates.

 To ensure your Windows 11/10 PC has all the patch updates available for it, it’s a good idea to check for new ones via Settings. The **Windows Update** tab includes a **Check for updates** button. You can add a shortcut for that tab to the desktop’s context menu with the method below.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-data.techidaily.com/024-approved-comprehensive-strategies-for-tracking-yt-traffic-and-gains/"><u>[New] 2024 Approved  Comprehensive Strategies for Tracking YT Traffic and Gains</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-the-ultimate-xbox-one-shutterbug-techniques/"><u>[New] 2024 Approved  The Ultimate Xbox One Shutterbug Techniques</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-ultimate-leaderboard-locator-youtubes-most-pop-videos/"><u>[New] 2024 Approved  Ultimate Leaderboard Locator  YouTube's Most Pop Videos</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-decoding-facebooks-automatic-video-advancements-for-2024/"><u>[New] Decoding Facebook's Automatic Video Advancements for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-2024-approved-game-masters-top-ten-female-gaming-influencers/"><u>[Updated] 2024 Approved  Game Masters  Top Ten Female Gaming Influencers</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-composers-toolkit-for-flawless-image-finishing/"><u>[Updated] The Composer's Toolkit for Flawless Image Finishing</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-comprehensive-overview-of-youtube-shorts/"><u>2024 Approved  The Comprehensive Overview of YouTube Shorts</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-ultrawide-uhd-dilemranc-which-monitor-wins/"><u>2024 Approved  The Ultrawide-UHD Dilemranc  Which Monitor Wins?</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/a-streamlined-approach-to-virtual-meeting-setup-zooming-on-android-devices-for-2024/"><u>A Streamlined Approach to Virtual Meeting Setup  Zooming on Android Devices for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-non-compliance-overcoming-intel-hd-graphics-errors/"><u>Addressing Non-Compliance: Overcoming Intel HD Graphics Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/command-prompt-oddities-learn-5-amusing-anomalies/"><u>Command Prompt Oddities: Learn 5 Amusing Anomalies</u></a></li>
<li><a href="https://windows11.techidaily.com/discreetly-putting-an-end-to-invisible-window-tasks/"><u>Discreetly Putting an End to Invisible Window Tasks</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-data-retrieval-how-to-master-the-art-of-qr-scanning-with-windows/"><u>Effortless Data Retrieval: How to Master the Art of QR Scanning with Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-hidden-programs-on-windows-pc/"><u>Enabling Hidden Programs on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-smart-color-settings-in-windows-11-apps/"><u>Enabling Smart Color Settings in Windows 11 Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-real-time-performance-for-smooth-vlc-viewing/"><u>Enhancing Real-Time Performance for Smooth VLC Viewing</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-to-using-windows-11s-compatibility-fixer/"><u>Essential Guide to Using Windows 11’S Compatibility Fixer</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-for-diablo-gameplay-enthusiasts/"><u>Essential Tips for Diablo Gameplay Enthusiasts</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-to-fully-erase-wsl-from-windows-11-systems/"><u>Expert Tips to Fully Erase WSL From Windows 11 Systems</u></a></li>
<li><a href="https://win-answers.techidaily.com/far-cry-6-black-screen-errors-cracked-learn-how-you-can-play-without-issues/"><u>Far Cry 6 Black Screen Errors Cracked! Learn How You Can Play Without Issues</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tune-auto-lock-and-screensaver-on-pc/"><u>Fine-Tune Auto-Lock & Screensaver on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-correctly-handle-iomap64sys-failures-in-winos/"><u>How To Correctly Handle IOMap64.sys Failures in WinOS</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reset-freezes-and-crashes-in-virtual-worlds/"><u>How to Reset Freezes & Crashes in Virtual Worlds</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-delete-icloud-account-remove-your-apple-id-permanently-from-apple-iphone-7-by-drfone-ios/"><u>In 2024, How To Delete iCloud Account Remove Your Apple ID Permanently From Apple iPhone 7</u></a></li>
<li><a href="https://windows11.techidaily.com/introducing-real-space-sound-on-windows-11/"><u>Introducing Real-Space Sound on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-corruption-unlock-write-permissions-in-win10win11/"><u>Overcoming Corruption: Unlock Write Permissions in Win10/Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-roadblocks-activating-non-functional-scripts-in-windows/"><u>Overcoming Roadblocks: Activating Non-Functional Scripts in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/personalize-browser-security-incorporating-trusted-websites-in-windows-11/"><u>Personalize Browser Security: Incorporating Trusted Websites in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-chromeedge-from-hiding-taskbar-on-large-screens/"><u>Preventing Chrome/Edge From Hiding Taskbar on Large Screens</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-removing-isdonedll-malfunctions-from-windows-11/"><u>Quick Guide: Removing ISDone.dll Malfunctions From Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/recovering-failed-zip-operations-on-win-11-system/"><u>Recovering Failed ZIP Operations on Win 11 System</u></a></li>
<li><a href="https://windows11.techidaily.com/safekeep-your-files-setting-up-folder-restrictions-in-windows-11/"><u>Safekeep Your Files: Setting Up Folder Restrictions in Windows 11</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/steer-clear-of-obscurity-secure-a-top-spot-with-youtube-seo-tips-for-2024/"><u>Steer Clear of Obscurity  Secure a Top Spot with YouTube SEO Tips for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/streamline-your-film-production-process-using-studio-editor-for-2024/"><u>Streamline Your Film Production Process Using Studio Editor for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/supercharge-efficiency-select-windows-software-for-success/"><u>Supercharge Efficiency: Select Windows Software for Success</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-error-0x80042306-on-windows-to-reset-successfully/"><u>Tackling Error 0X80042306 on Windows to Reset Successfully</u></a></li>
<li><a href="https://printer-issues.techidaily.com/technical-snafu-printer-configuration-gone-awry/"><u>Technical Snafu: Printer Configuration Gone Awry</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-tab-navigation-windows-11-enhanced-guide/"><u>The Art of Tab Navigation: Windows 11 Enhanced Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/top-4-microcomputers-pure-windows-environment/"><u>Top 4 Microcomputers: Pure Windows Environment</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/ultimate-tutorial-adding-straight-lines-in-microsoft-word-efficiently/"><u>Ultimate Tutorial: Adding Straight Lines in Microsoft Word Efficiently</u></a></li>
<li><a href="https://youtube-web.techidaily.com/-quality-comparison-mirrorless-or-dslr-cameras/"><u>Video Quality Comparison  Mirrorless or DSLR Cameras?</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-insider-clandestine-context-creation-techniques/"><u>Windows 11 Insider: Clandestine Context Creation Techniques</u></a></li>
</ul></div>
