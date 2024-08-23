---
title: Quick Access to System Status & Update Information via Menu Option in Win11
date: 2024-08-22T21:40:43.988Z
updated: 2024-08-23T21:40:43.988Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quick Access to System Status & Update Information via Menu Option in Win11
excerpt: This Article Describes Quick Access to System Status & Update Information via Menu Option in Win11
keywords: Windows 11 Status Menu,Quick Update Info Win11,Win11 System Check,Win11 Menu Updates,Access Win11 Diagnostics,Status Menu in Win11,Win11 Performance Menu
thumbnail: https://thmb.techidaily.com/8a64098fc8c00724b390ed4672a78681ea9b2ccc0c75a67c21e60baebffadabf.jpg
---

## Quick Access to System Status & Update Information via Menu Option in Win11

 Microsoft regularly releases patch updates for both Windows 10 and 11 every month. These patch updates typically address security vulnerabilities and fix Windows bugs and issues. Although those updates are usually automatically installed, sometimes your PC will miss the memo. And sometimes, the update itself is an optional download.

 To ensure your Windows 11/10 PC has all the patch updates available for it, it’s a good idea to check for new ones via Settings. The **Windows Update** tab includes a **Check for updates** button. You can add a shortcut for that tab to the desktop’s context menu with the method below.

## Add a Check for Updates Shortcut to the Context Menu

 Windows 11 doesn’t include any built-in options for adding shortcuts to the desktop’s right-click context menu. However, you can still add a **Check for Updates** shortcut for the **Windows Update** tab to that menu by [manually editing the registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/). Once done, you can open the **Windows Update** tab directly from the desktop’s context menu.

 To add that context menu shortcut, edit the registry as follows:

1. Right-click the **Start** button and select the **Run** shortcut to launch that accessory.
2. [Open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) by typing **regedit** in the **Open** box and clicking **OK**.
3. Then navigate to the **Computer** \> **HKEY\_CLASSES\_ROOT** \> **DesktopBackground** \> **Shell** registry key.
4. Right-click the **Shell** key to select the **New** submenu option.
5. Select the **Key** option.  
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
![The Add Windows Update submenu to Desktop context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-add-windows-update-to-context-menu-option.jpg)
6. Select the **Add Windows Update submenu to Desktop context menu** option.

 Now look at the new Windows Update submenu on the desktop’s context menu. Press **Shift** \+ **F10** to view the classic context menu. Move the cursor over the **Windows Update** submenu to view its options. There you can select a **Check for updates** option to bring up the **Check for updates** button.

![The Windows Update submenu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-windows-update-submenu.jpg)

 The **Windows Update** submenu also has four other shortcuts to update settings. Click **Update history** to view the installed update list. Or select **Advanced options** to bring up the additional settings for updates. The **Restart options** shortcut opens the settings for scheduling update times.

 Winaero Tweaker also has a customization option for adding a **Windows Update** shortcut to the Control panel. To access that option, click **Settings and** **Control Panel** \> **Add Windows Update** in Winaero Tweaker’s sidebar. Click the **Add Windows Update to Control Panel\\System and Security** checkbox to select that option.

![The Add Windows Update to Control Panel option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-add-windows-update-to-control-panel-option.jpg)

 Then you’ll see a **Windows Update** shortcut within the Control Panel. [Open the Control Panel](https://www.makeuseof.com/windows-11-open-control-panel/) and click the **System and Security** category. Clicking the **Windows Update** shortcut there will open the **Settings** tab with the **Check for updates** button.

![The Windows Update Control Panel shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-update-in-control-panel.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## Keep an Eye Out For New Windows Updates

 So, now you can select a handy **Check for Updates** shortcut on your desktop’s context menu. That shortcut will save you from having to manually open Settings and its **Windows Update** tab whenever you need to check for updates. Instead, you can simply click the **Check for Updates** context menu option to open the update tab directly from the desktop.

 Select that shortcut to keep an eye out for new updates regularly. When optional updates are available, you’ll see them listed on the tab with **Download and install** options. Clicking **Check for updates** will automatically download and install available updates.

 To ensure your Windows 11/10 PC has all the patch updates available for it, it’s a good idea to check for new ones via Settings. The **Windows Update** tab includes a **Check for updates** button. You can add a shortcut for that tab to the desktop’s context menu with the method below.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-hints.techidaily.com/new-achieving-realistic-blur-on-images-using-photoshop-techniques/"><u>[New] Achieving Realistic Blur on Images Using Photoshop Techniques</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-evaluating-every-aspect-of-du-recorder-design-and-function/"><u>[New] In 2024, Evaluating Every Aspect of Du Recorder Design & Function</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-which-cameras-rule-the-field-gopro-hero-vs-sony-x1000v-clashes/"><u>[New] Which Cameras Rule the Field? GoPro Hero Vs. Sony X1000V Clashes</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-propel-participation-through-unique-custom-story-queries/"><u>[Updated] 2024 Approved  Propel Participation Through Unique, Custom Story Queries</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-the-ultimate-editor-showdown-filmora-vs-democracy-creator/"><u>[Updated] The Ultimate Editor Showdown  Filmora Vs. Democracy Creator</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-mastering-the-art-of-video-discovery-on-facebook/"><u>2024 Approved  Mastering the Art of Video Discovery on Facebook</u></a></li>
<li><a href="https://activate-lock.techidaily.com/3-effective-ways-to-unlock-icloud-account-without-password-on-iphone-12-pro-by-drfone-ios/"><u>3 Effective Ways to Unlock iCloud Account Without Password On iPhone 12 Pro</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-solutions-to-hard-reset-poco-f5-pro-5g-phone-using-pc-drfone-by-drfone-reset-android-reset-android/"><u>3 Solutions to Hard Reset Poco F5 Pro 5G Phone Using PC | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/best-overlay-strategies-for-videographers/"><u>Best Overlay Strategies for Videographers</u></a></li>
<li><a href="https://extra-resources.techidaily.com/constructing-visually-captivating-photo-collections-for-2024/"><u>Constructing Visually Captivating Photo Collections for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-to-boost-your-speed-in-3d-paint-keys/"><u>Essential Tips to Boost Your Speed in 3D Paint Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/exclusive-w10w11-climate-software-roundup/"><u>Exclusive W10/W11 Climate Software Roundup</u></a></li>
<li><a href="https://windows11.techidaily.com/five-key-insights-into-how-win11-tracks-your-life/"><u>Five Key Insights Into How Win11 Tracks Your Life</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-activation-problem-eliminate-error-0x803f700f/"><u>Fixing Windows Activation Problem: Eliminate Error 0X803F700f</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-fixing-winrars-failed-file-sums-and-verifications/"><u>Guide to Fixing WinRAR's Failed File Sums and Verifications</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-correct-error-code-0xc0000005-on-windows-xp78/"><u>How To Correct Error Code 0XC0000005 on Windows XP/7/8</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-discord-fatal-javascript-error-in-windows-11-and-11/"><u>How to Fix the Discord Fatal Javascript Error in Windows 11 & 11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-use-google-assistant-on-your-lock-screen-of-poco-phone-by-drfone-android/"><u>How to Use Google Assistant on Your Lock Screen Of Poco Phone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-ispoofer-on-samsung-galaxy-s24-ultra-drfone-by-drfone-virtual-android/"><u>How to use iSpoofer on Samsung Galaxy S24 Ultra? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-solutions-for-win10win11-stuck-with-pin-lock/"><u>Immediate Solutions for Win10/Win11 Stuck with PIN Lock</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-oneplus-ace-3-drfone-by-drfone-virtual-android/"><u>In 2024, What is the best Pokemon for pokemon pvp ranking On OnePlus Ace 3? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/maintaining-harmony-keeping-your-gaming-system-steady-on-win/"><u>Maintaining Harmony: Keeping Your Gaming System Steady on Win</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-win-1011-domain-services-printer-fixation-techniques/"><u>Mastering Win 10/11 Domain Services Printer Fixation Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11-moving-vintage-games-into-picture-storage/"><u>Navigating Windows 11: Moving Vintage Games Into Picture Storage</u></a></li>
<li><a href="https://driver-install.techidaily.com/no-hassle-update-lenovo-z50-70-drivers/"><u>No Hassle: Update Lenovo Z50-70 Drivers</u></a></li>
<li><a href="https://windows11.techidaily.com/overcome-printer-errors-in-windows-11-easily/"><u>Overcome Printer Errors in Windows 11 Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-common-windows-error-with-lsassexe/"><u>Overcoming Common Windows Error with lsass.exe</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-common-wow-network-issues-on-pc/"><u>Overcoming Common WoW Network Issues on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-operation-failure-code-0x0000011b-in-win11-system/"><u>Overcoming Operation Failure Code 0X0000011B in Win11 System</u></a></li>
<li><a href="https://windows11.techidaily.com/precision-and-convenience-meet-with-our-winning-window-timers-list/"><u>Precision & Convenience Meet With Our Winning Window Timers List</u></a></li>
<li><a href="https://windows11.techidaily.com/prtscn-and-snipping-tool-tie-in-in-windows-11-how-to-break-it/"><u>PrtScn & Snipping Tool Tie-In in Windows 11 - How to Break It</u></a></li>
<li><a href="https://windows11.techidaily.com/quelling-the-flashing-phenomenon-windows-guide/"><u>Quelling the Flashing Phenomenon: Windows Guide</u></a></li>
<li><a href="https://technical-tips.techidaily.com/quick-guide-opening-the-windows-10-boot-menu/"><u>Quick Guide: Opening the Windows 10 Boot Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/re-establishing-classic-navigation-in-win-11/"><u>Re-Establishing Classic Navigation in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/realigning-disabled-menu-items-on-windows-10-and-11-pcs/"><u>Realigning Disabled Menu Items on Windows 10 & 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/rebooting-to-reactivate-dormant-snapshots/"><u>Rebooting to Reactivate Dormant Snapshots</u></a></li>
<li><a href="https://windows11.techidaily.com/reimagining-the-look-of-basic-text-editor-in-windows-11/"><u>Reimagining the Look of Basic Text Editor in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/rejuvenating-windows-a-comprehensive-guide-of-13-tips/"><u>Rejuvenating Windows: A Comprehensive Guide of 13 Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-cease-random-file-explorer-launch/"><u>Remedy: Cease Random File Explorer Launch</u></a></li>
<li><a href="https://sound-issues.techidaily.com/reviving-your-windows-scanner-a-step-by-step-guide/"><u>Reviving Your Windows Scanner: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-repair-disk-errors-in-windows-os/"><u>Steps to Repair Disk Errors in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/stepwise-navigation-through-bluescreenview-features/"><u>Stepwise Navigation Through BlueScreenView Features</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-your-wi-fi-networks-usage-metrics-with-windows-11/"><u>Tailoring Your Wi-Fi Network's Usage Metrics with Windows 11</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/the-abcs-of-amassing-affection-on-fb-squaring-up-your-video-strategy-for-2024/"><u>The ABC's of Amassing Affection on FB  Squaring Up Your Video Strategy for 2024</u></a></li>
<li><a href="https://activate-lock.techidaily.com/the-ultimate-guide-to-bypassing-icloud-activation-lock-on-apple-iphone-7-plus-by-drfone-ios/"><u>The Ultimate Guide to Bypassing iCloud Activation Lock on Apple iPhone 7 Plus</u></a></li>
<li><a href="https://windows11.techidaily.com/the-unplugged-play-linking-windows-to-ps3-gamepad/"><u>The Unplugged Play: Linking Windows to PS3 Gamepad</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-absence-of-files-on-windows-11/"><u>Troubleshooting Absence of Files on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/uncover-and-fix-hidden-5ghz-connections-in-windows-11-easily/"><u>Uncover & Fix Hidden 5GHz Connections in Windows 11 Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-your-pcs-true-power-with-enhanced-vram-settings-in-windows-10-and-11/"><u>Unleash Your PC's True Power with Enhanced VRAM Settings in Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-memory-write-hitches-in-windows/"><u>Unraveling 'Memory Write' Hitches in Windows</u></a></li>
<li><a href="https://extra-tips.techidaily.com/utilizing-b-roll-enhancing-video-quality/"><u>Utilizing B Roll  Enhancing Video Quality</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-setup-via-vmware-workstation-17-a-step-by-step-guide/"><u>Win11 Setup via VMware Workstation 17: A Step-by-Step Guide</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>