---
title: Adding Windows Update Alerts Tooltip Menu Entry
date: 2024-07-11T22:17:49.459Z
updated: 2024-07-12T22:17:49.459Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adding Windows Update Alerts Tooltip Menu Entry
excerpt: This Article Describes Adding Windows Update Alerts Tooltip Menu Entry
keywords: Update Alerts Menu Tooltip,Windows Update Notifications,System Update Tips,Alert Window Popup,Windows Updater Tip,Software Alert Help,Menu Entry Advice for Windows
thumbnail: https://thmb.techidaily.com/2453bc5c0249af0de921ee166f14d8e128b375913b07ba9cca730be764e6c410.jpg
---

## Adding Windows Update Alerts Tooltip Menu Entry

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
<li><a href="https://windows11.techidaily.com/batch-heic-to-jpeg-images-in-windows-environment/"><u>Batch Heic to Jpeg Images in Windows Environment</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/2024-approved-youtube-audio-made-simple-for-imovie-editors/"><u>2024 Approved  YouTube Audio, Made Simple for iMovie Editors</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-moto-z2-play-smartphone-review/"><u>[Updated] MOTO Z2 Play Smartphone Review</u></a></li>
<li><a href="https://driver-install.techidaily.com/uncompromising-webcam-software-for-windows/"><u>Uncompromising Webcam Software for Windows</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/overview-of-the-best-realme-c67-5g-screen-mirroring-app-drfone-by-drfone-android/"><u>Overview of the Best Realme C67 5G Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-whats-ideal-fps-for-capturing-stunning-slow-motion-cinematography/"><u>2024 Approved  What's Ideal FPS for Capturing Stunning Slow Motion Cinematography?</u></a></li>
<li><a href="https://windows11.techidaily.com/a-harmonious-symphony-taming-your-computers-audio-irqs/"><u>A Harmonious Symphony: Taming Your Computer’s Audio IRQs</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fake-gps-on-vivo-y78plus-for-mobile-legends-drfone-by-drfone-virtual-android/"><u>How To Fake GPS On Vivo Y78+ For Mobile Legends? | Dr.fone</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/dance-your-way-to-fame-with-tiktok-on-mac/"><u>Dance Your Way to Fame with TikTok on Mac</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-slowly-quieting-tracks-with-fl-studio/"><u>[Updated] Slowly Quieting Tracks with FL Studio</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-the-best-free-video-editing-apps-for-32-bit-windows-systems-for-2024/"><u>Updated The Best Free Video Editing Apps for 32-Bit Windows Systems for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/crafting-unique-valorant-thumbnails-with-style-and-flair-for-2024/"><u>Crafting Unique Valorant Thumbnails with Style and Flair for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-transforming-live-photos-into-time-lapse-videos/"><u>[Updated] Transforming Live Photos Into Time-Lapse Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-failed-rpc-calls-top-tips-for-windows-users/"><u>Addressing Failed RPC Calls: Top Tips for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/9-ways-to-fix-blurry-screen-issues-on-windows-11/"><u>9 Ways to Fix Blurry Screen Issues on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-unresponsive-windows-11-login-screens/"><u>Bypassing Unresponsive Windows 11 Login Screens</u></a></li>
<li><a href="https://windows11.techidaily.com/1719361633854-enhance-your-pcs-screen-glow-with-these-fixes/"><u>Enhance Your PC's Screen Glow with These Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-rgb-customization-in-win11/"><u>Activating RGB Customization in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/7-solutions-for-enabling-windows-11s-memory-check/"><u>7 Solutions for Enabling Windows 11'S Memory Check</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-in-2024-the-uninitiateds-guide-to-finding-rhythmic-foundations-for-rap-lyrics/"><u>Updated In 2024, The Uninitiateds Guide to Finding Rhythmic Foundations for Rap Lyrics</u></a></li>
<li><a href="https://windows11.techidaily.com/a-step-by-step-guide-to-modifying-windows-file-attributes/"><u>A Step-by-Step Guide to Modifying Windows File Attributes</u></a></li>
<li><a href="https://windows11.techidaily.com/1719306890834-key-collectors-rejoice-get-the-perfect-pair-of-keys-and-essential-windows-11-612lifetime/"><u>Key Collectors Rejoice – Get the Perfect Pair of Keys & Essential Windows 11, $6.12/Lifetime</u></a></li>
<li><a href="https://windows11.techidaily.com/antiquated-tech-awakened-atlasos-upgrade/"><u>Antiquated Tech Awakened: AtlasOS Upgrade</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-infinix-note-30-drfone-by-drfone-virtual-android/"><u>How to Get and Use Pokemon Go Promo Codes On Infinix Note 30 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-forbidden-page-in-windows-setup/"><u>Addressing Forbidden Page in Windows Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/5-proven-strategies-for-superior-windows-11-search-performance/"><u>5 Proven Strategies for Superior Windows 11 Search Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/altering-start-page-in-windows-11-task-manager/"><u>Altering Start Page in Windows 11 Task Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/best-data-shields-on-windows-encryption-apps-analysis-150-chars/"><u>Best Data Shields on Windows: Encryption Apps Analysis (150 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/a-new-look-for-you-top-methods-to-alter-windows-11-themes/"><u>A New Look for You: Top Methods to Alter Windows 11 Themes</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-non-existent-files-message-on-windows-11/"><u>Addressing Non-Existent Files Message on Windows 11</u></a></li>
<li><a href="https://discord-videos.techidaily.com/top-5-creative-logo-motion-in-the-social-sphere/"><u>Top 5 Creative Logo Motion in the Social Sphere</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-master-video-cutting-and-splicing-with-vimeo-for-free/"><u>[Updated] Master Video Cutting & Splicing with Vimeo, for Free</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-avoid-posting-mistakes-on-twitter-by-knowing-the-aspect-ratio-for-2024/"><u>[New] Avoid Posting Mistakes on Twitter by Knowing the Aspect Ratio for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/a-step-by-step-for-placing-antique-games-into-photos-folder/"><u>A Step-by-Step for Placing Antique Games Into Photos Folder</u></a></li>
<li><a href="https://windows11.techidaily.com/best-practices-choosing-the-right-win-video-codec/"><u>Best Practices: Choosing the Right Win Video Codec</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-revolutionary-marketing-tactics-keyword-essentials/"><u>[New] Revolutionary Marketing Tactics  Keyword Essentials</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-10-upgrade-fault-code-0xc004f050/"><u>Bypassing Windows 10 Upgrade Fault: Code 0XC004F050</u></a></li>
<li><a href="https://windows11.techidaily.com/5-ways-to-close-multiple-apps-simultaneously-on-windows/"><u>5 Ways to Close Multiple Apps Simultaneously on Windows</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-tecno-camon-20-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 4 solution to get rid of pokemon fail to detect location On Tecno Camon 20 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-precision-in-recordings-discover-the-best-10-free-slack-apps/"><u>[Updated] Precision in Recordings  Discover the Best 10 Free Slack Apps</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-in-2024-echo-fabricator-bundle/"><u>[New] In 2024, Echo Fabricator Bundle</u></a></li>
<li><a href="https://windows11.techidaily.com/briefly-explain-what-cultural-relativism-means-in-your-own-words/"><u>Briefly Explain What Cultural Relativism Means in Your Own Words.</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-changing-printer-behavior-on-windows/"><u>Avoiding Changing Printer Behavior on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-faulty-alerts-from-windows-10s-shield/"><u>Addressing Faulty Alerts From Windows 10'S Shield</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-customizable-rgb-in-windows-11-os/"><u>Activating Customizable RGB in Windows 11 OS</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/standout-tiktok-pfp-designs-that-set-you-apart/"><u>Standout TikTok PFP Designs That Set You Apart</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-strongholds-in-minecraft-the-ultimate-guide/"><u>[New] 2024 Approved  Strongholds in Minecraft  The Ultimate Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/a-guide-to-overhauling-the-settings-app-in-win11/"><u>A Guide to Overhauling the Settings App in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/best-practices-for-disabling-noncritical-windows-11-services/"><u>Best Practices for Disabling Noncritical Windows 11 Services</u></a></li>
<li><a href="https://windows11.techidaily.com/amplify-your-pcs-wi-fi-with-8-effective-fixes-for-windows-11/"><u>Amplify Your PC's Wi-Fi with 8 Effective Fixes for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/access-androids-gaming-joy-on-pc-from-phone-to-window-11-via-google-linkup/"><u>Access Android's Gaming Joy on PC: From Phone to Window 11 via Google Linkup</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-a-step-by-step-guide-to-crafting-facebook-visual-stories/"><u>[Updated] In 2024, A Step-by-Step Guide to Crafting Facebook Visual Stories</u></a></li>
</ul></div>
