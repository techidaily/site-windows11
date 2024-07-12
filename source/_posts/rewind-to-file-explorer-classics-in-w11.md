---
title: Rewind to File Explorer Classics in W11
date: 2024-07-11T21:44:54.840Z
updated: 2024-07-12T21:44:54.840Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Rewind to File Explorer Classics in W11
excerpt: This Article Describes Rewind to File Explorer Classics in W11
keywords: FileExplorerW11Classic,Win10FileExplorer,WindowsFileManager,ClassicWinFileExplore,WindowsFileVault,WIndowsOldFxvr,LegacyWindowsFileNav
thumbnail: https://thmb.techidaily.com/8774783d28d2d78a2030ac7e0dc1d6230634beecdba672087a8494366974e451.jpg
---

## Rewind to File Explorer Classics in W11

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
<li><a href="https://windows11.techidaily.com/stop-windows-from-notifying-you-of-updates/"><u>Stop Windows From Notifying You of Updates</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-navigating-optimal-youtube-aesthetics-for-maximum-engagement/"><u>2024 Approved  Navigating Optimal YouTube Aesthetics for Maximum Engagement</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-windows-11s-compatibility-checker-usage-guide/"><u>Understanding Windows 11'S Compatibility Checker: Usage Guide</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-pixel-perfect-photography-excelling-in-the-best-6-4k-dslrs/"><u>[Updated] In 2024, Pixel Perfect Photography  Excelling in the Best 6 4K DSLRs</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-11-camera-app-eradicating-error-a00f425d/"><u>Troubleshooting Windows 11 Camera App: Eradicating Error A00F425D</u></a></li>
<li><a href="https://windows11.techidaily.com/starting-windows-terminal-with-quake-effects/"><u>Starting Windows Terminal with Quake Effects</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-absent-windows-extras-a-comprehensive-guide/"><u>Reviving Absent Windows Extras: A Comprehensive Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-stalled-netflix-app-on-windows/"><u>Troubleshooting Stalled Netflix App on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/steering-onedrive-destination-on-windows-pc/"><u>Steering OneDrive Destination on Windows PC</u></a></li>
<li><a href="https://some-techniques.techidaily.com/how-to-choose-engaging-tiktok-backgrounds-for-2024/"><u>How to Choose Engaging TikTok Backgrounds for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-microsoft-store-issues-overcoming-0x80072f30/"><u>Unraveling Microsoft Store Issues: Overcoming 0X80072F30</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-quick-recording-visuals-plus-verbal-input/"><u>In 2024, Quick Recording  Visuals + Verbal Input</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-workspace-malfunctions-essential-tips-for-office-on-winos/"><u>Resolving Workspace Malfunctions: Essential Tips for Office on WINOS</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-searching-on-windows-techniques-beyond-ls-command/"><u>Seamless Searching on Windows: Techniques Beyond LS Command</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-screen-glitches-in-windows-11-a-step-by-step-guide/"><u>Solving Screen Glitches in Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-how-to-estimate-income-from-youtube-video-snippets/"><u>2024 Approved  How to Estimate Income From YouTube Video Snippets</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-free-gif-maker-tools-for-seamless-loops-2023-update/"><u>2024 Approved Free GIF Maker Tools for Seamless Loops 2023 Update</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-correct-sound-hiccup-in-audacity-on-windows-11/"><u>Strategies to Correct Sound Hiccup in Audacity on Windows 11</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/2024-approved-the-ultimate-fcpx-freebie-list-10-plugins-to-elevate-your-workflow/"><u>2024 Approved The Ultimate FCPX Freebie List 10 Plugins to Elevate Your Workflow</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-find-ispoofer-pro-activation-key-on-vivo-y28-5g-drfone-by-drfone-virtual-android/"><u>How to Find iSpoofer Pro Activation Key On Vivo Y28 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlined-startup-routines-in-modern-windows/"><u>Streamlined Startup Routines in Modern Windows</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-10-fantastic-online-tools-to-change-image-dimensions/"><u>In 2024, 10 Fantastic Online Tools to Change Image Dimensions</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-from-novice-to-pro-key-edits-and-tips-to-maximize-mp3-potential-for-2024/"><u>New From Novice to Pro Key Edits and Tips to Maximize MP3 Potential for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/sound-struggles-winning-back-noise-from-windows-spacebar/"><u>Sound Struggles: Winning Back Noise From Windows' Spacebar</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-solve-iphone-picture-failure-in-pcs-windows/"><u>Steps to Solve iPhone Picture Failure in PCs (Windows)</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-what-should-consider-when-converting-mp3-into-mp4/"><u>2024 Approved What Should Consider when Converting MP3 Into MP4</u></a></li>
<li><a href="https://techidaily.com/how-to-hard-reset-samsung-galaxy-a15-5g-without-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Hard Reset Samsung Galaxy A15 5G Without Password | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-your-system-without-relying-on-bitlocker/"><u>Securing Your System without Relying on Bitlocker</u></a></li>
<li><a href="https://windows11.techidaily.com/seeking-entry-into-the-windows-11-insider-circle/"><u>Seeking Entry Into the Windows 11 Insider Circle</u></a></li>
<li><a href="https://windows11.techidaily.com/surface-go-3-with-latest-chip-reviewed-mixed-outcomes-noted/"><u>Surface Go 3 with Latest Chip Reviewed: Mixed Outcomes Noted</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-effortless-4k-video-conversion-top-free-and-paid-options/"><u>2024 Approved Effortless 4K Video Conversion Top Free and Paid Options</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-can-you-cast-your-apple-iphone-13-pro-max-to-windows-pc-with-ease-drfone-by-drfone-ios/"><u>In 2024, How Can You Cast Your Apple iPhone 13 Pro Max to Windows PC With Ease? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-videos-from-lava-blaze-curve-5g-to-ipad-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Videos from Lava Blaze Curve 5G to iPad | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/the-explorers-guide-6-steps-to-property-expertise/"><u>The Explorer's Guide: 6 Steps to Property Expertise</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/cross-platform-success-televisions-and-facebook-collaboration/"><u>Cross-Platform Success  Televisions & Facebook Collaboration</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-sony-ps-players-voice-modification-techniques/"><u>[New] Sony PS Players' Voice Modification Techniques</u></a></li>
</ul></div>
