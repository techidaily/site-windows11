---
title: Re-Establishing Classic Navigation in Win 11
date: 2024-08-15T16:16:57.415Z
updated: 2024-08-16T16:16:57.415Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Re-Establishing Classic Navigation in Win 11
excerpt: This Article Describes Re-Establishing Classic Navigation in Win 11
keywords: Win 11 Nav Update,Classic Nav Reinstate,Modern Windows Navigate,New OS Navigation Guide,Restore Old Win Menus,Classic Desktop Layouts,Win 11 Navigation Redesign
thumbnail: https://thmb.techidaily.com/aa9290eddc8ec2cc97b63ee765b598d95b8b81e9c2cca36d2d92b110af8ad1f5.jpg
---

## Re-Establishing Classic Navigation in Win 11

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

## 2\. Manually Edit the Registry

 Users utilizing Windows 11 21H2 or earlier versions can restore the classic File Explorer ribbon by manually tweaking the registry. However, the same registry tweak will not work in Windows 11 22H2 or later builds. This is how you can restore the classic File Explorer ribbon interface by manually editing the registry:

1. Open Windows 11’s Registry Editor app. Our guide to [opening Registry Editor on Windows](https://www.makeuseof.com/windows-11-open-registry-editor/) includes various methods for launching that app.
2. Go to the **ShellExtensions** key by inputting this location in the Registry Editor’s address bar:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Shell Extensions\`
3. If you can’t see a **Blocked** subkey, right-click ShellExtensions and select New and Key. You can skip through to step five if you can already see a Blocked key.  
![The New and Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-key-option.jpg)
4. Input **Blocked** to create that key.
5. Right-click the **Blocked** key and select **New** \> **String Value**.
6. Input **{e2bf9676-5f8f-435c-97eb-11607a5bedf7**} in the new string’s text box. You can copy and paste that string name in by selecting its text, pressing **Ctrl** \+ **C**, and then pressing **Ctrl** \+ **V**.  
![The string value for restoring File Explorer's ribbon UI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-string-value.jpg)
<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Then you'll need to [restart File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) or Windows 11 for the registry tweak to take effect.

 Now press the **File Explorer** taskbar button to see the change. Or open that file manager app with any other method you prefer to [open File Explorer on Windows](https://www.makeuseof.com/windows-open-file-explorer/). The File Explorer that opens will have the tabbed ribbon interface from Windows 10\.

![The tabbed ribbon interface in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-tabbed-ribbon-file-explorer.jpg)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you ever want to go back to the original command bar, delete the string you added. To do so, right-click **{e2bf9676-5f8f-435c-97eb-11607a5bedf7}** within the **Blocked** key and select **Delete**. Click **Yes** when asked to confirm deletion.

![The Delete option in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/delete-option.jpg)

## 3\. Execute a Registry Command via Command Prompt

 Alternatively, you can restore File Explorer’s classic ribbon interface by executing a command that adds the **{e2bf9676-5f8f-435c-97eb-11607a5bedf7}** string value. Note that this is another method that won’t work in Windows 11 22H2\.

 However, you can restore Explorer’s classic ribbon UI in Windows 11 21H1 and earlier build versions via the Command Prompt as follows:

1. Press **Win + S**, input the **CMD** search phrase, and select Command Prompt’s **Run as administrator** option.
2. Execute this command to restore Explorer’s classic ribbon UI:  
`reg add "HKCU\Software\Classes\CLSID\{d93ed569-3b3e-4bff-8355-3c44f6a52bb5}\InprocServer32" /f /ve`  
![The command for restoring File Explorer's ribbon UI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/restore-classic-file-explorer-ribbon-command.jpg)
<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. You can bring back the command bar by executing this command:  
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
<!-- affiliate ads begin -->
<a href="https://martinic.evyy.net/c/5597632/1422856/4482" target="_top" id="1422856"><img src="//a.impactradius-go.com/display-ad/4482-1422856" border="0" alt="" width="580" height="309"/></a>
<!-- affiliate ads end -->
7. Click **Restart File Explorer** on the Properties window.

 ExplorerPatcher might also automatically apply changes to the Start menu and taskbar when installed. You can restore the original Windows 11 taskbar by selecting the **Windows 11 (default)** option on the **Taskbar** tab. To restore the original menu, select **Windows 11 (default)** for ExplorerPatcher’s **Start menu style** setting.

 ExplorerPatcher has other settings with which you can further restore the Windows 10 File Explorer design. For example, File Explorer in Windows 10 has square corners. You can restore those square corners by clicking **Other** \> **Disable rounded corners for applications windows** in ExplorerPatcher.

![The Disable rounded corners option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/disable-rounded-corners-option.jpg)
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->

 Windows 11’s File Explorer also has a redesigned context menu. You can disable that new right-click menu by clicking the **Disable the Windows 11 context menu** option on the **File Explorer** tab. Then right-clicking a file in Explorer will show only the classic context menu, as in Windows 10\.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->
## Restore a Tabbed User Interface in Windows 11's File Explorer

 Although Windows 11’s command bar has its advantages, there are some good reasons to restore File Explorer’s tabbed ribbon UI of old with the methods above.

 For example, restoring the tabbed ribbon UI will enable you to select a **Slideshow** option for images on the **Picture Tool** tab, which isn’t accessible from the command bar. You can also select additional options for sharing files on the **Share** tab.

 Do you prefer the tabbed File Explorer in Windows 10? If so, you don’t have to stick with File Explorer’s command bar in Windows 11\. This is how you can restore Explorer’s classic ribbon interface on a Windows 11 PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-activity-recording.techidaily.com/new-10-pro-ways-to-upgrade-your-twitch-broadcast-experience/"><u>[New] 10 Pro Ways to Upgrade Your Twitch Broadcast Experience</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ssential-errors-to-dodge-beginner-youtubers-guide-for-2024/"><u>[New] Essential Errors to Dodge  Beginner YouTuber's Guide for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-hack-the-art-of-instagram-reels-creation-for-2024/"><u>[New] Hack the Art of Instagram Reels Creation for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-discover-the-5-best-android-software-for-ps2-games/"><u>[New] In 2024, Discover the 5 Best Android Software for PS2 Games</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-windowsmac-meeting-record-skype-guide/"><u>[New] In 2024, Windows/Mac Meeting Record - Skype Guide</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-soaring-visions-with-dji-mavic-pro-insight-for-2024/"><u>[New] Soaring Visions with DJI Mavic Pro Insight for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-pro-photo-expertise-at-your-fingertips-with-these-tips/"><u>[Updated] Pro Photo Expertise at Your Fingertips with These Tips</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-quick-start-installing-vrecorder-effortlessly-for-2024/"><u>[Updated] Quick Start  Installing VRecorder Effortlessly for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/11-common-windows-11-problems-with-easy-solutions/"><u>11 Common Windows 11 Problems With Easy Solutions</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-recording-google-voice-a-comprehensive-tutorial/"><u>2024 Approved  Recording Google Voice  A Comprehensive Tutorial</u></a></li>
<li><a href="https://windows11.techidaily.com/8-ways-to-fix-the-windows-pin-not-working-in-windows-10-and-11/"><u>8 Ways to Fix the Windows PIN Not Working in Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/a-complete-look-at-windows-11s-audio-recorder-keys/"><u>A Complete Look at Windows 11'S Audio Recorder Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-how-to-deal-with-non-terminatable-errors/"><u>Bypassing Windows: How to Deal with Non-Terminatable Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/cease-uncontrolled-system-shutdowns-on-windows-11/"><u>Cease Uncontrolled System Shutdowns on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/decluttering-windows-11-icon-pile-up/"><u>Decluttering Windows 11 Icon Pile-Up</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-hardware-utilization-in-windows-11/"><u>Decoding Hardware Utilization in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-tips-for-reactivating-file-explorer-ui/"><u>Easy Tips for Reactivating File Explorer UI</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-windows-volume-preserve-data/"><u>Enhance Windows Volume, Preserve Data</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-flaky-windows-apps-a-step-by-step-guide/"><u>Fixing Flaky Windows Apps: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-white-or-gray-microsoft-store-display/"><u>Fixing White or Gray Microsoft Store Display</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-customize-sound-levels-with-dedicated-win11-keys/"><u>How to Customize Sound Levels with Dedicated Win11 Keys</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-poco-m6-5g-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Poco M6 5G without Losing Data | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reactivate-nonfunctional-wsreset-service-in-windows/"><u>How to Reactivate Nonfunctional WSReset Service in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/improving-memory-footprint-in-ms-teams/"><u>Improving Memory Footprint in MS Teams</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-6-ways-to-transfer-contacts-from-infinix-note-30i-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 6 Ways To Transfer Contacts From Infinix Note 30i to iPhone | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/integrating-nas-into-mobile-device-setups/"><u>Integrating NAS Into Mobile Device Setups</u></a></li>
<li><a href="https://windows11.techidaily.com/1719382274392-is-your-hardware-upgraded-for-win11-find-out/"><u>Is Your Hardware Upgraded For Win11? Find Out</u></a></li>
<li><a href="https://windows11.techidaily.com/method-for-handling-device-access-issues-with-audacity-win/"><u>Method for Handling Device Access Issues with Audacity (Win)</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-setting-up-a-trio-of-widget-boards-in-windows-11/"><u>Step by Step: Setting Up a Trio of Widget Boards in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-rectify-preview-failures-in-outlook-for-pcs/"><u>Steps to Rectify Preview Failures in Outlook for PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-gaming-experience-installing-windows-on-steam-deck/"><u>Streamline Your Gaming Experience: Installing Windows on Steam Deck</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/techniques-to-stabilize-photos-and-movies-on-ios/"><u>Techniques to Stabilize Photos and Movies on iOS</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-flush-for-your-win11-dns-cache/"><u>The Ultimate Flush for Your Win11 DNS Cache</u></a></li>
<li><a href="https://windows11.techidaily.com/tricks-to-extend-the-wait-window-in-windows-10-before-restarting/"><u>Tricks to Extend the Wait Window in Windows 10 Before Restarting</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-disabled-programs-in-windows/"><u>Unblocking Disabled Programs in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-hidden-potential-essential-tips-on-windows-narrator-commands/"><u>Unveiling the Hidden Potential: Essential Tips on Windows Narrator Commands</u></a></li>
<li><a href="https://howto.techidaily.com/vivo-y36-not-connecting-to-wi-fi-12-quick-ways-to-fix-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Vivo Y36 Not Connecting to Wi-Fi? 12 Quick Ways to Fix | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/wireless-mouse-woes-on-windows-heres-what-to-do/"><u>Wireless Mouse Woes on Windows? Here's What to Do</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>