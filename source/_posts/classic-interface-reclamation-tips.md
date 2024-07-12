---
title: Classic Interface Reclamation Tips
date: 2024-07-11T21:43:19.572Z
updated: 2024-07-12T21:43:19.572Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Classic Interface Reclamation Tips
excerpt: This Article Describes Classic Interface Reclamation Tips
keywords: Classic UI Revival,Interface Upgrade Hacks,Restoring Design Elegance,Modernize Old UI,Retro UX Redesign Tips,Vintage Interface Revamp,Timeless UI Refresh Guide
thumbnail: https://thmb.techidaily.com/e271cbb6eb6a65ff2648f6dddd1fc0c078a843660eba98a715724fa951b431ee.jpg
---

## Classic Interface Reclamation Tips

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
7. Then you'll need to [restart File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) or Windows 11 for the registry tweak to take effect.

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

 ExplorerPatcher might also automatically apply changes to the Start menu and taskbar when installed. You can restore the original Windows 11 taskbar by selecting the **Windows 11 (default)** option on the **Taskbar** tab. To restore the original menu, select **Windows 11 (default)** for ExplorerPatcher’s **Start menu style** setting.

 ExplorerPatcher has other settings with which you can further restore the Windows 10 File Explorer design. For example, File Explorer in Windows 10 has square corners. You can restore those square corners by clicking **Other** \> **Disable rounded corners for applications windows** in ExplorerPatcher.

![The Disable rounded corners option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/disable-rounded-corners-option.jpg)

 Windows 11’s File Explorer also has a redesigned context menu. You can disable that new right-click menu by clicking the **Disable the Windows 11 context menu** option on the **File Explorer** tab. Then right-clicking a file in Explorer will show only the classic context menu, as in Windows 10\.

## Restore a Tabbed User Interface in Windows 11's File Explorer

 Although Windows 11’s command bar has its advantages, there are some good reasons to restore File Explorer’s tabbed ribbon UI of old with the methods above.

 For example, restoring the tabbed ribbon UI will enable you to select a **Slideshow** option for images on the **Picture Tool** tab, which isn’t accessible from the command bar. You can also select additional options for sharing files on the **Share** tab.

 Do you prefer the tabbed File Explorer in Windows 10? If so, you don’t have to stick with File Explorer’s command bar in Windows 11\. This is how you can restore Explorer’s classic ribbon interface on a Windows 11 PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/steps-to-repair-windows-event-viewer-in-windows-11/"><u>Steps to Repair Windows Event Viewer in Windows 11</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-identify-malfunctioning-your-drivers-with-windows-device-manager-in-windows-10-and-7-by-drivereasy-guide/"><u>Use Device Manager to identify malfunctioning your drivers with Windows Device Manager in Windows 10 & 7</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-fast-access-to-textual-explanations/"><u>Windows 11: Fast Access to Textual Explanations</u></a></li>
<li><a href="https://windows11.techidaily.com/sneak-peek-at-windows-11-writers-seven-vintage-traits/"><u>Sneak Peek at Windows 11' Writers: Seven Vintage Traits</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-tips-for-syncing-two-windows-displays/"><u>Quick Tips for Syncing Two Windows Displays</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-inshot-analysis-video-edition-showdown/"><u>In 2024, InShot Analysis  Video Edition Showdown</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-microsoft-store-error-0x80072efd/"><u>Unblocking Microsoft Store Error 0X80072EFD</u></a></li>
<li><a href="https://windows11.techidaily.com/perfecting-taskbar-setup-in-windows-11/"><u>Perfecting Taskbar Setup in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-invisibility-of-task-view-on-bar/"><u>Techniques for Invisibility of Task View on Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/procedures-for-upholding-true-windows-time-values/"><u>Procedures for Upholding True Windows Time Values</u></a></li>
<li><a href="https://windows11.techidaily.com/tutorial-enabling-or-disabling-wi-fi-cost-meter-in-windows-11/"><u>Tutorial: Enabling or Disabling Wi-Fi Cost Meter in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/proven-file-sync-software-the-most-trusted-windows-picks/"><u>Proven File Sync Software: The Most Trusted Windows Picks</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-vivo-y200e-5g-bootloader-easily-by-drfone-android/"><u>In 2024, How to Unlock Vivo Y200e 5G Bootloader Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-turning-onoff-the-registry-editor/"><u>Techniques for Turning On/Off the Registry Editor</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-troubleshooting-ms-to-do-sync-failures/"><u>Tips for Troubleshooting MS To-Do Sync Failures</u></a></li>
<li><a href="https://windows11.techidaily.com/reconfiguring-start-menu-and-browser-by-defaults/"><u>Reconfiguring Start Menu and Browser by Defaults</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-a-functional-taskbar-for-windows-11-tablets/"><u>Activating a Functional Taskbar for Windows 11 Tablets</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/premium-portable-switch-game-clones-for-2024/"><u>Premium Portable Switch Game Clones for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/bidfarewelltomycam-the-quest-for-improved-options-for-2024/"><u>BidFarewellToMyCam  The Quest for Improved Options for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-gateway-to-information-conquering-windows-qr-code-scan/"><u>The Gateway to Information: Conquering Windows' QR Code Scan</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-reclaiming-windows-photo-viewer-in-windows-10-methods-demystified/"><u>[New] Reclaiming Windows Photo Viewer in Windows 10 - Methods Demystified</u></a></li>
<li><a href="https://windows11.techidaily.com/rejoining-lost-astra-pilot-on-windows-11-machines/"><u>Rejoining Lost Astra Pilot on Windows 11 Machines</u></a></li>
<li><a href="https://windows11.techidaily.com/supercharging-download-speeds-tips-and-tricks-for-ms-marketplace/"><u>Supercharging Download Speeds: Tips & Tricks for MS Marketplace</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-microsoft-store-error-code-0x80072f30/"><u>Troubleshooting Microsoft Store: Error Code 0X80072F30</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-access-your-outlook-preview/"><u>Unlocking Windows: Access Your Outlook Preview</u></a></li>
<li><a href="https://windows11.techidaily.com/the-clarity-compass-directing-you-through-a-fuzzy-screen-fix-up/"><u>The Clarity Compass: Directing You Through a Fuzzy Screen Fix-Up</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-to-resolving-pin-check-errors-on-windows-devices/"><u>Quick Guide to Resolving Pin Check Errors on Windows Devices</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-still-using-pattern-locks-with-realme-narzo-n55-tips-tricks-and-helpful-advice-by-drfone-android/"><u>In 2024, Still Using Pattern Locks with Realme Narzo N55? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://windows11.techidaily.com/precision-tools-for-crafting-custom-windows-filename-dates/"><u>Precision Tools for Crafting Custom Windows Filename Dates</u></a></li>
<li><a href="https://video-capture.techidaily.com/improving-remote-work-communications-with-4-strategies/"><u>Improving Remote Work Communications with #4 Strategies</u></a></li>
<li><a href="https://article-tips.techidaily.com/in-2024-home-cinema-mastery-top-10-hd-players-list/"><u>In 2024, Home Cinema Mastery  Top 10 HD Players' List</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-aesthetics-for-windows-terminal/"><u>Tailoring Aesthetics for Windows Terminal</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/in-2024-youtube-101-tips-for-a-distraction-free-video-backdrop/"><u>In 2024, YouTube 101  Tips for a Distraction-Free Video Backdrop</u></a></li>
<li><a href="https://windows11.techidaily.com/biometric-betrayal-windows-hellos-security-under-fire/"><u>Biometric Betrayal: Windows Hello's Security Under Fire?</u></a></li>
<li><a href="https://extra-tips.techidaily.com/13-best-ways-to-make-money-on-reddit-no-experience-needed/"><u>13 Best Ways to Make Money on Reddit - No Experience Needed</u></a></li>
<li><a href="https://windows11.techidaily.com/6-cutting-edge-windows-programs-for-media-editing/"><u>6 Cutting-Edge Windows Programs for Media Editing</u></a></li>
<li><a href="https://windows11.techidaily.com/uninstalling-epic-games-with-ease-on-your-w11-computer/"><u>Uninstalling Epic Games with Ease on Your W11 Computer</u></a></li>
</ul></div>
