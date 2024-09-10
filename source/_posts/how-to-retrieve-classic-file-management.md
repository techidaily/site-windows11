---
title: How to Retrieve Classic File Management
date: 2024-09-09T11:59:06.771Z
updated: 2024-09-10T11:59:06.771Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Retrieve Classic File Management
excerpt: This Article Describes How to Retrieve Classic File Management
keywords: File Retrieval Basics,Classic Folder Access,Restoring Old Data Files,Manage Vintage Documents,Archive System Recovery,Retrieve Historical Files,Timeless File Management
thumbnail: https://thmb.techidaily.com/c9d63107d989d631581c5dbe79eb35fbfb926a1d51af5b4f90784c648af3957e.png
---

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136626/26400" target="_top" id="2136626">
  <img src="//a.impactradius-go.com/display-ad/26400-2136626" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136626/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Retrieve Classic File Management

 Microsoft redesigned File Explorer’s user interface for Windows 11\. Windows 11’s File Explorer has a command bar on which you can select options. That bar replaces the tabbed ribbon interface from Windows 10’s File Explorer.

 Do you prefer the tabbed File Explorer in Windows 10? If so, you don’t have to stick with File Explorer’s command bar in Windows 11\. This is how you can restore Explorer’s classic ribbon interface on a Windows 11 PC.

## 1\. Press the Up Button in the Control Panel

 File Explorer is accessible from the Control Panel. Furthermore, Explorer will still have the old, ribbon interface from Windows 10 when you open it from there. You can access the classic File Explorer in Windows 11 by clicking the up button in the Control Panel as follows:

1. Press the **Windows + S** key combination to access Windows 11’s search box.
2. Input **Control Panel** and select to open the matching search result.
3. If the Control Panel opens in an icon view, click the **View by** drop-down menu and select **Category**.  
![The View by menu in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/view-by-menu.jpg)
4. Then click the **Up to “Desktop”** button (up arrow) button on the Control Panel’s navigation bar. Alternatively, press the **Alt + Up arrow key** keyboard shortcut.  
![The Up to Desktop button in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/up-button.jpg)

 Now you’ll see the classic File Explorer from Windows 10 that incorporates a tab bar. You’ll always need to open the Control Panel first to access classic File Explorer through it. So, consider [setting up a Control Panel shortcut](https://www.makeuseof.com/windows-11-set-up-control-panel-shortcuts/) in Windows 11 to give you more direct access.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137214/26400" target="_top" id="2137214">
  <img src="//a.impactradius-go.com/display-ad/26400-2137214" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137214/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Manually Edit the Registry

 Users utilizing Windows 11 21H2 or earlier versions can restore the classic File Explorer ribbon by manually tweaking the registry. However, the same registry tweak will not work in Windows 11 22H2 or later builds. This is how you can restore the classic File Explorer ribbon interface by manually editing the registry:

1. Open Windows 11’s Registry Editor app. Our guide to [opening Registry Editor on Windows](https://www.makeuseof.com/windows-11-open-registry-editor/) includes various methods for launching that app.
2. Go to the **ShellExtensions** key by inputting this location in the Registry Editor’s address bar:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Shell Extensions\`
3. If you can’t see a **Blocked** subkey, right-click ShellExtensions and select New and Key. You can skip through to step five if you can already see a Blocked key.  
![The New and Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-key-option.jpg)
4. Input **Blocked** to create that key.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135413/19272" target="_top" id="2135413">
  <img src="//a.impactradius-go.com/display-ad/19272-2135413" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135413/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Right-click the **Blocked** key and select **New** \> **String Value**.
6. Input **{e2bf9676-5f8f-435c-97eb-11607a5bedf7**} in the new string’s text box. You can copy and paste that string name in by selecting its text, pressing **Ctrl** \+ **C**, and then pressing **Ctrl** \+ **V**.  
![The string value for restoring File Explorer's ribbon UI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-string-value.jpg)
7. Then you'll need to [restart File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) or Windows 11 for the registry tweak to take effect.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135394/19272" target="_top" id="2135394">
  <img src="//a.impactradius-go.com/display-ad/19272-2135394" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135394/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now press the **File Explorer** taskbar button to see the change. Or open that file manager app with any other method you prefer to [open File Explorer on Windows](https://www.makeuseof.com/windows-open-file-explorer/). The File Explorer that opens will have the tabbed ribbon interface from Windows 10\.

![The tabbed ribbon interface in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-tabbed-ribbon-file-explorer.jpg)

 If you ever want to go back to the original command bar, delete the string you added. To do so, right-click **{e2bf9676-5f8f-435c-97eb-11607a5bedf7}** within the **Blocked** key and select **Delete**. Click **Yes** when asked to confirm deletion.

![The Delete option in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/delete-option.jpg)

## 3\. Execute a Registry Command via Command Prompt

 Alternatively, you can restore File Explorer’s classic ribbon interface by executing a command that adds the **{e2bf9676-5f8f-435c-97eb-11607a5bedf7}** string value. Note that this is another method that won’t work in Windows 11 22H2\.

 However, you can restore Explorer’s classic ribbon UI in Windows 11 21H1 and earlier build versions via the Command Prompt as follows:

1. Press **Win + S**, input the **CMD** search phrase, and select Command Prompt’s **Run as administrator** option.
2. Execute this command to restore Explorer’s classic ribbon UI:  
`reg add "HKCU\Software\Classes\CLSID\{d93ed569-3b3e-4bff-8355-3c44f6a52bb5}\InprocServer32" /f /ve`  
![The command for restoring File Explorer's ribbon UI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/restore-classic-file-explorer-ribbon-command.jpg)
3. You can bring back the command bar by executing this command:  
<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098701/14409" target="_top" id="2098701">
  <img src="//a.impactradius-go.com/display-ad/14409-2098701" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098701/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
`reg delete "HKCU\Software\Classes\CLSID\{d93ed569-3b3e-4bff-8355-3c44f6a52bb5}" /f`

 This method is somewhat more straightforward than manually editing the registry. The first command adds the **{d93ed569-3b3e-4bff-8355-3c44f6a52bb5}** string value. Entering the second command deletes that string, which restores Explorer’s default command bar.

 If the command for restoring classic File Explorer doesn’t work when you execute it, there might be spaces at the end of it. Make sure there aren’t any extra spaces included at the end of the command before executing.

## 4\. Restore Explorer’s Classic Ribbon UI With ExplorerPatcher

 You can still restore Explorer’s ribbon interface in Windows 11 22H2 and all other build versions with ExplorerPatcher. ExplorerPatcher is freeware software that enables you to customize Windows 11’s Start menu, taskbar, File Explorer, and system tray. It includes many options for [making Windows 11 look more like Windows 10](https://www.makeuseof.com/windows-11-look-like-windows-10-explorerpatcher/).

 This is how you can restore tabs in Windows 11’s File Explorer with ExplorerPatcher.

1. Open this [ExplorerPatcher Softpedia page](https://www.softpedia.com/get/Tweak/System-Tweak/Explorer-Patcher-for-Windows-11.shtml) and download the file.
2. Double-click the **ep\_setup** file to install Explorer Patcher.
3. Activate the Power User menu by right-clicking the **Start** taskbar button to select **Search**.
4. Enter **ExplorerPatcher** in the Windows 11 search box and click **Properties (ExplorerPatcher)**.
5. Click the **File Explorer** tab in ExplorerPatcher.
6. Next, click the **Control interface** option to select **Windows 10 Ribbon**.  
![The Windows 10 Ribbon option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-10-ribbon.jpg)
7. Click **Restart File Explorer** on the Properties window.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130870/7443" target="_top" id="2130870">
  <img src="//a.impactradius-go.com/display-ad/7443-2130870" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130870/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 ExplorerPatcher might also automatically apply changes to the Start menu and taskbar when installed. You can restore the original Windows 11 taskbar by selecting the **Windows 11 (default)** option on the **Taskbar** tab. To restore the original menu, select **Windows 11 (default)** for ExplorerPatcher’s **Start menu style** setting.

 ExplorerPatcher has other settings with which you can further restore the Windows 10 File Explorer design. For example, File Explorer in Windows 10 has square corners. You can restore those square corners by clicking **Other** \> **Disable rounded corners for applications windows** in ExplorerPatcher.

![The Disable rounded corners option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/disable-rounded-corners-option.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123740/7443" target="_top" id="2123740">
  <img src="//a.impactradius-go.com/display-ad/7443-2123740" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123740/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Windows 11’s File Explorer also has a redesigned context menu. You can disable that new right-click menu by clicking the **Disable the Windows 11 context menu** option on the **File Explorer** tab. Then right-clicking a file in Explorer will show only the classic context menu, as in Windows 10\.

## Restore a Tabbed User Interface in Windows 11's File Explorer

 Although Windows 11’s command bar has its advantages, there are some good reasons to restore File Explorer’s tabbed ribbon UI of old with the methods above.

 For example, restoring the tabbed ribbon UI will enable you to select a **Slideshow** option for images on the **Picture Tool** tab, which isn’t accessible from the command bar. You can also select additional options for sharing files on the **Share** tab.

 Do you prefer the tabbed File Explorer in Windows 10? If so, you don’t have to stick with File Explorer’s command bar in Windows 11\. This is how you can restore Explorer’s classic ribbon interface on a Windows 11 PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-earn-big-on-youtube-shorts-tips-for-profitable-content-creation/"><u>[New] 2024 Approved Earn Big on YouTube Shorts Tips for Profitable Content Creation</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-2024-approved-ultimate-list-of-10-online-free-jpg-to-gif-conversion-programs/"><u>[New] 2024 Approved Ultimate List of 10 Online, Free JPG to GIF Conversion Programs</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-boost-your-media-library-top-20-freeware-tools-turning-instagram-videos-into-mp4-for-2024/"><u>[New] Boost Your Media Library Top 20 Freeware Tools Turning Instagram Videos Into MP4 for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-unlockingluxurycameratech-post-mycam/"><u>[New] In 2024, UnlockingLuxuryCameraTech Post-MyCam</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-unparalleled-top-5-lightweight-cinematography-devices/"><u>[Updated] Unparalleled Top 5 Lightweight Cinematography Devices</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-your-ultimate-guide-to-downloading-youtube-on-ios-for-2024/"><u>[Updated] Your Ultimate Guide to Downloading YouTube on iOS for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/calls-on-honor-x50iplus-go-straight-to-voicemail-12-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Calls on Honor X50i+ Go Straight to Voicemail? 12 Fixes | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/comprehensive-guide-understanding-everything-on-netflix/"><u>Comprehensive Guide: Understanding Everything on Netflix</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-strategies-for-winning-back-defective-windows-apps/"><u>Essential Strategies for Winning Back Defective Windows Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/extending-windows-11-shutdown-for-active-tasks-tips-and-tricks/"><u>Extending Windows 11 Shutdown for Active Tasks: Tips & Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/fixes-for-application-flood-conquering-0x80860010/"><u>Fixes for Application Flood: Conquering 0X80860010</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-crashes-caused-by-windows-0x0000011b-error/"><u>Fixing Crashes Caused by Windows' 0X0000011B Error</u></a></li>
<li><a href="https://windows11.techidaily.com/google-chrome-unresponsiveness-solved-expert-troubleshooting-tips/"><u>Google Chrome Unresponsiveness Solved: Expert Troubleshooting Tips</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-add-a-digital-signature-block-to-docx-by-ldigisigner-sign-a-word-sign-a-word/"><u>How to add a digital signature block to .docx </u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-clean-up-and-customize-your-windows-11-desktop/"><u>How to Clean Up and Customize Your Windows 11 Desktop</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-4-ways-to-transfer-music-from-infinix-note-30-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 4 Ways to Transfer Music from Infinix Note 30 to iPhone | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-realme-note-50-to-samsung-galaxy-s21-ultra-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos From Realme Note 50 to Samsung Galaxy S21 Ultra | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-tecno-pova-5-pro-phone-without-pin-by-drfone-android/"><u>In 2024, How to Unlock Tecno Pova 5 Pro Phone without PIN</u></a></li>
<li><a href="https://windows11.techidaily.com/mend-cure-your-windows-11-function-key-woes/"><u>Mend: Cure Your Windows 11 Function Key Woes</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-obstacles-in-installation-for-windo-users/"><u>Overcoming Obstacles in Installation for Windo Users</u></a></li>
<li><a href="https://windows11.techidaily.com/quieting-chrome-bugs-on-windows-systems/"><u>Quieting Chrome Bugs on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/resetting-lost-web-interfaces-of-router-on-windows/"><u>Resetting Lost Web Interfaces of Router on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-audio-communication-via-xbox-mic-and-windows-11/"><u>Restoring Audio Communication via Xbox Mic & Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-insert-isp-info-on-taskbar/"><u>Step-by-Step Guide: Insert ISP Info on Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-disabling-discordutation-at-windows-boot-up/"><u>Techniques for Disabling Discord'utation at Windows Boot-Up</u></a></li>
<li><a href="https://windows11.techidaily.com/the-threat-within-detecting-and-disabling-wacatacbml-trojan-on-pcs/"><u>The Threat Within: Detecting and Disabling Wacatac.B!ml Trojan on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-windows-key-filter-settings/"><u>The Ultimate Guide to Windows Key Filter Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/thriving-on-windows-11-essential-methods/"><u>Thriving on Windows 11: Essential Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-fixing-non-responsive-pc-gamepad-issues/"><u>Tips for Fixing Non-Responsive PC Gamepad Issues</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-10-xiaomi-14-pro-android-sim-unlock-apk-by-drfone-android/"><u>Top 10 Xiaomi 14 Pro Android SIM Unlock APK</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-print-spooler-down-on-windows-pcs/"><u>Troubleshooting Print Spooler Down on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/tutorial-reverting-the-search-bar-design-of-windows-11/"><u>Tutorial: Reverting the Search Bar Design of Windows 11</u></a></li>
<li><a href="https://win-able.techidaily.com/ultimate-guide-to-enhancing-performance-and-increasing-fps-on-watch-dogs-legion/"><u>Ultimate Guide to Enhancing Performance & Increasing FPS on Watch Dogs: Legion</u></a></li>
<li><a href="https://windows11.techidaily.com/uniting-android-tabs-with-windows-11-for-enhanced-workflow/"><u>Uniting Android Tabs with Windows 11 for Enhanced Workflow</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-potential-of-ai-in-microsoft-store/"><u>Unlocking the Potential of AI in Microsoft Store</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>