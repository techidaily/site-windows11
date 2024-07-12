---
title: Ditch Default Home Port on W11 Settings Interface
date: 2024-07-11T22:24:09.925Z
updated: 2024-07-12T22:24:09.925Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Ditch Default Home Port on W11 Settings Interface
excerpt: This Article Describes Ditch Default Home Port on W11 Settings Interface
keywords: Ditch Default Home,W11 Customization,Reset Home Port,Set Interface Options,Disable Default Layout,Windows 11 Personalize,Interactive Settings Guide
thumbnail: https://thmb.techidaily.com/e99583f6b5b06e719853b0ad4d8e79890585ba4f6bebb22736b51161b0bbe49e.jpg
---

## Ditch Default Home Port on W11 Settings Interface

### Key Takeaways

* You can remove the Home page from the Settings app in Windows 11 using the Group Policy Editor or the Registry Editor.
* The Group Policy Editor is only available in certain editions of Windows, but there are workarounds for enabling it in the Home edition.
* It's important to back up registry files or create a restore point before making changes, as incorrect modifications can cause serious issues.

 The Home page in the Settings app displays interactive cards that provide information about the system and offer shortcuts to common settings. However, if you're not a fan of the new Home section, removing it from the Settings app is possible with two quick methods.

 You can hide the Home page using the Group Policy Editor or the Registry Editor. This guide will walk you through both methods.

## 1\. Use the Group Policy Editor to Remove the Home Page

 The Local Group Policy Editor on Windows makes modifying various advanced system settings easy. Among the many options, it allows you to manage the pages shown in the Settings app. So, you can use the Local Group Policy Editor to hide the Home tab from the Windows 11 Settings app.

 The Group Policy Editor is only accessible on the Professional, Education, and Enterprise editions of Windows. If you are using Windows Home, you can [enable the Local Group Policy Editor in Windows](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) with workarounds.

1. Press **Win + S** to access the search menu.
2. Type **gpedit.msc** in the box and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. In the Local Group Policy Editor window, use the left pane to navigate to **Computer Configuration > Administrative Templates > Control Panel**.
5. Double-click the **Settings Page Visibility** policy in the right pane.
6. Select the **Enabled** option.
7. In the Options box, type **hide:home** in the text field next to Settings Page Visibility.
8. Click **Apply** followed by **OK**.  
![Settings Page Visibility Policy on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/settings-page-visibility-policy-on-windows.jpg)

 The Home page will be hidden on the Settings app. If you want to view the Home tab at any point, repeat the above steps and set the **Settings Page Visibility** policy to **Disabled** or **Not configured**.

## 2\. Use the Registry Editor to Remove the Home Page

 Can't access the Group Policy Editor on your Windows PC? You can also remove the Home tab from the Windows 11 Settings app by making a few changes to the registry files.

 As you may already know, registry files store critical settings for Windows and your apps. Making incorrect changes to the registry can lead to serious problems. Hence, it’s a good idea to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/use-system-restore-windows/) before proceeding. This will allow you to restore the Windows registry to its previous state if something goes wrong.

 To hide the Home tab from the Settings app using Registry Editor, follow these steps:

1. Press **Win + R** to open the Run dialog.
2. Type **regedit** in the text box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Policies > Explorer**.
5. Right-click the **Explorer** key, click **New**, and select **String Value** from the submenu. Rename it to **SettingsPageVisibility**.
6. Double-click the **SettingsPageVisibility** value to edit it.
7. Type **hide:home** in the Value data field and click **OK**.  
![Edit a String Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/edit-a-string-value-in-registry-editor.jpg)

 Restart your PC after completing the above steps. Then, open Settings to confirm the Home page is hidden. To restore the removed Home tab later, repeat the above steps and delete the **SettingsPageVisibility** string value.

## Get the Classic Windows 11 Settings Look

 While the Home screen provides quick and easy access to frequently used settings, you may prefer the older classic view. So, hide it from view and recover it when necessary.

 The Home page in the Settings app displays interactive cards that provide information about the system and offer shortcuts to common settings. However, if you're not a fan of the new Home section, removing it from the Settings app is possible with two quick methods.

 You can hide the Home page using the Group Policy Editor or the Registry Editor. This guide will walk you through both methods.

## 1\. Use the Group Policy Editor to Remove the Home Page

 The Local Group Policy Editor on Windows makes modifying various advanced system settings easy. Among the many options, it allows you to manage the pages shown in the Settings app. So, you can use the Local Group Policy Editor to hide the Home tab from the Windows 11 Settings app.

 The Group Policy Editor is only accessible on the Professional, Education, and Enterprise editions of Windows. If you are using Windows Home, you can [enable the Local Group Policy Editor in Windows](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) with workarounds.

1. Press **Win + S** to access the search menu.
2. Type **gpedit.msc** in the box and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. In the Local Group Policy Editor window, use the left pane to navigate to **Computer Configuration > Administrative Templates > Control Panel**.
5. Double-click the **Settings Page Visibility** policy in the right pane.
6. Select the **Enabled** option.
7. In the Options box, type **hide:home** in the text field next to Settings Page Visibility.
8. Click **Apply** followed by **OK**.  
![Settings Page Visibility Policy on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/settings-page-visibility-policy-on-windows.jpg)

 The Home page will be hidden on the Settings app. If you want to view the Home tab at any point, repeat the above steps and set the **Settings Page Visibility** policy to **Disabled** or **Not configured**.

## 2\. Use the Registry Editor to Remove the Home Page

 Can't access the Group Policy Editor on your Windows PC? You can also remove the Home tab from the Windows 11 Settings app by making a few changes to the registry files.

 As you may already know, registry files store critical settings for Windows and your apps. Making incorrect changes to the registry can lead to serious problems. Hence, it’s a good idea to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/use-system-restore-windows/) before proceeding. This will allow you to restore the Windows registry to its previous state if something goes wrong.

 To hide the Home tab from the Settings app using Registry Editor, follow these steps:

1. Press **Win + R** to open the Run dialog.
2. Type **regedit** in the text box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Policies > Explorer**.
5. Right-click the **Explorer** key, click **New**, and select **String Value** from the submenu. Rename it to **SettingsPageVisibility**.
6. Double-click the **SettingsPageVisibility** value to edit it.
7. Type **hide:home** in the Value data field and click **OK**.  
![Edit a String Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/edit-a-string-value-in-registry-editor.jpg)

 Restart your PC after completing the above steps. Then, open Settings to confirm the Home page is hidden. To restore the removed Home tab later, repeat the above steps and delete the **SettingsPageVisibility** string value.

## Get the Classic Windows 11 Settings Look

 While the Home screen provides quick and easy access to frequently used settings, you may prefer the older classic view. So, hide it from view and recover it when necessary.

 The Home page in the Settings app displays interactive cards that provide information about the system and offer shortcuts to common settings. However, if you're not a fan of the new Home section, removing it from the Settings app is possible with two quick methods.

 You can hide the Home page using the Group Policy Editor or the Registry Editor. This guide will walk you through both methods.

## 1\. Use the Group Policy Editor to Remove the Home Page

 The Local Group Policy Editor on Windows makes modifying various advanced system settings easy. Among the many options, it allows you to manage the pages shown in the Settings app. So, you can use the Local Group Policy Editor to hide the Home tab from the Windows 11 Settings app.

 The Group Policy Editor is only accessible on the Professional, Education, and Enterprise editions of Windows. If you are using Windows Home, you can [enable the Local Group Policy Editor in Windows](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) with workarounds.

1. Press **Win + S** to access the search menu.
2. Type **gpedit.msc** in the box and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. In the Local Group Policy Editor window, use the left pane to navigate to **Computer Configuration > Administrative Templates > Control Panel**.
5. Double-click the **Settings Page Visibility** policy in the right pane.
6. Select the **Enabled** option.
7. In the Options box, type **hide:home** in the text field next to Settings Page Visibility.
8. Click **Apply** followed by **OK**.  
![Settings Page Visibility Policy on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/settings-page-visibility-policy-on-windows.jpg)

 The Home page will be hidden on the Settings app. If you want to view the Home tab at any point, repeat the above steps and set the **Settings Page Visibility** policy to **Disabled** or **Not configured**.

## 2\. Use the Registry Editor to Remove the Home Page

 Can't access the Group Policy Editor on your Windows PC? You can also remove the Home tab from the Windows 11 Settings app by making a few changes to the registry files.

 As you may already know, registry files store critical settings for Windows and your apps. Making incorrect changes to the registry can lead to serious problems. Hence, it’s a good idea to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/use-system-restore-windows/) before proceeding. This will allow you to restore the Windows registry to its previous state if something goes wrong.

 To hide the Home tab from the Settings app using Registry Editor, follow these steps:

1. Press **Win + R** to open the Run dialog.
2. Type **regedit** in the text box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Policies > Explorer**.
5. Right-click the **Explorer** key, click **New**, and select **String Value** from the submenu. Rename it to **SettingsPageVisibility**.
6. Double-click the **SettingsPageVisibility** value to edit it.
7. Type **hide:home** in the Value data field and click **OK**.  
![Edit a String Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/edit-a-string-value-in-registry-editor.jpg)

 Restart your PC after completing the above steps. Then, open Settings to confirm the Home page is hidden. To restore the removed Home tab later, repeat the above steps and delete the **SettingsPageVisibility** string value.

## Get the Classic Windows 11 Settings Look

 While the Home screen provides quick and easy access to frequently used settings, you may prefer the older classic view. So, hide it from view and recover it when necessary.

 The Home page in the Settings app displays interactive cards that provide information about the system and offer shortcuts to common settings. However, if you're not a fan of the new Home section, removing it from the Settings app is possible with two quick methods.

 You can hide the Home page using the Group Policy Editor or the Registry Editor. This guide will walk you through both methods.

## 1\. Use the Group Policy Editor to Remove the Home Page

 The Local Group Policy Editor on Windows makes modifying various advanced system settings easy. Among the many options, it allows you to manage the pages shown in the Settings app. So, you can use the Local Group Policy Editor to hide the Home tab from the Windows 11 Settings app.

 The Group Policy Editor is only accessible on the Professional, Education, and Enterprise editions of Windows. If you are using Windows Home, you can [enable the Local Group Policy Editor in Windows](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) with workarounds.

1. Press **Win + S** to access the search menu.
2. Type **gpedit.msc** in the box and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. In the Local Group Policy Editor window, use the left pane to navigate to **Computer Configuration > Administrative Templates > Control Panel**.
5. Double-click the **Settings Page Visibility** policy in the right pane.
6. Select the **Enabled** option.
7. In the Options box, type **hide:home** in the text field next to Settings Page Visibility.
8. Click **Apply** followed by **OK**.  
![Settings Page Visibility Policy on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/settings-page-visibility-policy-on-windows.jpg)

 The Home page will be hidden on the Settings app. If you want to view the Home tab at any point, repeat the above steps and set the **Settings Page Visibility** policy to **Disabled** or **Not configured**.

## 2\. Use the Registry Editor to Remove the Home Page

 Can't access the Group Policy Editor on your Windows PC? You can also remove the Home tab from the Windows 11 Settings app by making a few changes to the registry files.

 As you may already know, registry files store critical settings for Windows and your apps. Making incorrect changes to the registry can lead to serious problems. Hence, it’s a good idea to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/use-system-restore-windows/) before proceeding. This will allow you to restore the Windows registry to its previous state if something goes wrong.

 To hide the Home tab from the Settings app using Registry Editor, follow these steps:

1. Press **Win + R** to open the Run dialog.
2. Type **regedit** in the text box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Policies > Explorer**.
5. Right-click the **Explorer** key, click **New**, and select **String Value** from the submenu. Rename it to **SettingsPageVisibility**.
6. Double-click the **SettingsPageVisibility** value to edit it.
7. Type **hide:home** in the Value data field and click **OK**.  
![Edit a String Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/edit-a-string-value-in-registry-editor.jpg)

 Restart your PC after completing the above steps. Then, open Settings to confirm the Home page is hidden. To restore the removed Home tab later, repeat the above steps and delete the **SettingsPageVisibility** string value.

## Get the Classic Windows 11 Settings Look

 While the Home screen provides quick and easy access to frequently used settings, you may prefer the older classic view. So, hide it from view and recover it when necessary.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/cut-costs-not-compromise-top-5-free-media-software/"><u>Cut Costs, Not Compromise: Top 5 Free Media Software</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-daily-dosage-of-serenity-top-yoga-channels-for-life/"><u>[Updated] Daily Dosage of Serenity  Top Yoga Channels for Life</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-ten-step-window-repair-journey/"><u>Decoding the Ten-Step Window Repair Journey</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/top-10-airplay-apps-in-tecno-pop-8-for-streaming-drfone-by-drfone-android/"><u>Top 10 AirPlay Apps in Tecno Pop 8 for Streaming | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/complete-guide-to-hard-reset-your-tecno-camon-30-pro-5g-drfone-by-drfone-reset-android-reset-android/"><u>Complete Guide to Hard Reset Your Tecno Camon 30 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/conjoining-android-and-windows-11-tablets-effortlessly/"><u>Conjoining Android and Windows 11 Tablets Effortlessly</u></a></li>
<li><a href="https://windows11.techidaily.com/correct-windows-11s-no-error-zero-error-flaw-quickly/"><u>Correct Windows 11'S No Error, Zero-Error Flaw Quickly</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-20-essentials-every-new-creator-should-own-for-2024/"><u>[New] 20 Essentials Every New Creator Should Own for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-unified-event-tracking-harmonizing-phone-and-tablet-with-pc-zoom/"><u>[Updated] 2024 Approved  Unified Event Tracking  Harmonizing Phone & Tablet with PC Zoom</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-the-obscure-fixing-white-out-screens-in-win1011/"><u>Clearing the Obscure: Fixing White Out Screens in WIN10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/covertly-masking-taskbars-language-feature-in-win11/"><u>Covertly Masking Taskbar's Language Feature in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/clean-windows-search-interface-no-icons/"><u>Clean Windows Search Interface: No Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-win11-remote-storage-paths/"><u>Configuring Win11 Remote Storage Paths</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-top-video-editing-software-for-windows-10/"><u>2024 Approved Top Video Editing Software for Windows 10</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-itel-a05s-phone-without-pin-by-drfone-android/"><u>In 2024, How to Unlock Itel A05s Phone without PIN</u></a></li>
<li><a href="https://windows11.techidaily.com/delving-into-windows-pe-file-structure/"><u>Delving Into Windows PE File Structure</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-windows-file-explorer-path-settings/"><u>Customizing Windows File Explorer Path Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-fixing-error-0x80040610-in-microsoft-office-suite/"><u>Decoding and Fixing Error 0X80040610 in Microsoft Office Suite</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-audio-addition-for-snapchat-videos-for-2024/"><u>[New] Audio Addition for Snapchat Videos for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-optimized-vimeo-video-exporting-apps/"><u>[New] 2024 Approved  Optimized Vimeo Video Exporting Apps</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/direct-sharing-integrating-twitter-video-into-instagram-experience/"><u>Direct Sharing  Integrating Twitter Video Into Instagram Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-diablos-first-encounter-mechanics/"><u>Demystifying Diablo's First Encounter Mechanics</u></a></li>
<li><a href="https://vp-tips.techidaily.com/mastering-media-importer-strategies-in-windows-10-for-2024/"><u>Mastering Media Importer Strategies in Windows 10 for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-windows-screensaver-tactics/"><u>Comprehensive Guide: Windows Screensaver Tactics</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-perfect-pathway-insta-to-tiktok-junction/"><u>[New] The Perfect Pathway  Insta to TikTok Junction</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-shrink-mpeg2-files-download-virtualdub-for-video-compression/"><u>New Shrink MPEG2 Files Download VirtualDub for Video Compression</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-overcoming-the-windows-virtualbox-efail-error/"><u>Decoding and Overcoming the Windows Virtualbox E_FAIL Error</u></a></li>
<li><a href="https://windows11.techidaily.com/cyber-armor-top-7-techniques-to-guard-your-os/"><u>Cyber Armor: Top 7 Techniques to Guard Your OS</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-revive-your-bricked-lava-blaze-2-pro-in-minutes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Revive Your Bricked Lava Blaze 2 Pro in Minutes | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-windows-aggregatehostexe-its-functionality-and-dangers/"><u>Demystifying Windows' AggregateHost.exe: Its Functionality & Dangers</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-to-rectifying-windows-error-code-0x800704b3/"><u>Comprehensive Guide to Rectifying Windows Error Code 0X800704B3</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-your-window-11-experience-dynamic-wallpapers-guide/"><u>Customize Your Window 11 Experience: Dynamic Wallpapers Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/distinguishing-characteristics-of-exe-and-msi-files/"><u>Distinguishing Characteristics of EXE and MSI Files</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-value-oriented-pc-visual-logging-suites/"><u>2024 Approved  Value-Oriented PC Visual Logging Suites</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-social-media-sound-conversion-for-2024/"><u>[New] Social Media Sound Conversion for 2024</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-methods-of-exporting-audio-from-audacity-in-mp3-format-for-2024/"><u>New Methods of Exporting Audio From Audacity in MP3 Format for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-prime-picks-leading-mac-recording-software/"><u>[New] Prime Picks  Leading Mac Recording Software</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/unleash-the-pro-in-you-turn-everyday-moments-into-breathtaking-films-for-2024/"><u>Unleash the Pro in You Turn Everyday Moments Into Breathtaking Films for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-auto-triggered-console-crashes-on-windows/"><u>Disabling Auto-Triggered Console Crashes on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/dism-tactics-restoring-windows-11-os-images/"><u>DISM Tactics: Restoring Windows 11 OS Images</u></a></li>
</ul></div>
