---
title: Unlock Your Screen Without PIN in Window's 11
date: 2024-07-11T21:43:04.077Z
updated: 2024-07-12T21:43:04.077Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unlock Your Screen Without PIN in Window's 11
excerpt: This Article Describes Unlock Your Screen Without PIN in Window's 11
keywords: Unlock Windows 11,Password-Free Login,Remove PIN,Easy Access Windows,Bypass Screen Lock,No PIN Entry,Unblock Windows Gate
thumbnail: https://thmb.techidaily.com/5e974938dbb660ea80a93e16c035b60b79b36010696a635f2d59959383d55084.jpg
---

## Unlock Your Screen Without PIN in Window's 11

 Windows requires a PIN when projecting your computer onto another screen, such as a projector or a second monitor. Doing so prevents others from accessing your private information or projecting their content onto your computer.

 However, if you’re the only person using your computer, you may find this extra security measure unnecessary. Let’s explore how to disable the "require PIN for pairing" setting when projecting to your PC in Windows 11\.

## 1\. Using Windows Settings

 Windows has a built-in app that allows you to change various settings. You can use this app to turn off the “require PIN for pairing” setting when projecting to your PC. Here’s how to do it:

1. [Open the Settings menu](https://www.makeuseof.com/windows-ways-to-open-system-settings/).
2. From the left sidebar, select the **System** tab.
3. Scroll down to the **Projecting to this PC** section and click on it.

 On the next page, look for the **Require a PIN for pairing** setting. Click on its drop-down menu, and you’ll see three options:

* **Never:** Never ask for a PIN for pairing when projecting to this PC.
* **First Time:** Require a PIN the first time you’re projecting to this PC.
* **Always:** Always requiring a PIN for pairing when projecting to this PC.

 Choose the **Never** option and exit the Settings window. The settings will be saved automatically, and you won’t need to enter a PIN when projecting your computer onto another display.

 If you don’t see **Require a PIN for pairing** in the **Projecting to this PC** section, the feature is disabled on your computer.

 To enable this feature, click on the **Optional features** link. You can also navigate to **Settings** \> **Apps** \> **Optional features** to access the same page. Doing so will open the optional features window.

![Add the Wireless Display optional feature](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/add-the-wireless-display-optional-feature.jpg)

 Click the **Add an optional feature** button and search for **Wireless Display**. You should see the Wireless Display feature listed in the search results. Check the box next to it and click **Next** \> **Install**.

![Add an optional feature](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/add-an-optional-feature.jpg)

 Once the feature is installed, return to the Projecting to this PC section in Settings. You should now see the “require a PIN for pairing” setting. Choose the **Never** option and close the window.

## 2\. Using the Group Policy Editor

 Another option is to use the Group Policy Editor. This method requires you to have a Pro or Enterprise Windows version. However, you can [activate the Group Policy Editor in Windows Home Edition](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 Once you’ve done that, follow these steps to turn off the feature:

1. Press **Win + R** on your keyboard to open the Run dialog box.
2. Type **gpedit.msc** in the text field and press **Enter**. This will open the Group Policy Editor window.
3. From the left sidebar, navigate to the following path:  
`Computer Configuration > Administrative Templates > Windows Components > Connect​`
4. On the right side of the window, look for **Require pin for pairing** and double-click on it. Doing so will open the policy settings page.  
![Disable the Require pin for pairing policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-the-require-pin-for-pairing-policy.jpg)
5. Select the **Enabled** radio button and select **Never** from the drop-down menu.  
![Never Require Pin For Pairing in GPE](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/never-require-pin-for-pairing-in-gpe.jpg)
6. Click **Apply** \> **OK** to save the changes.

 After that, exit out of the window. When projecting your computer onto another screen, you won’t need a PIN anymore.

## 3\. Using the Registry Editor

 If you can’t access the Group Policy Editor, you can use the Registry Editor to disable the “Require PIN for Pairing” setting. This method involves editing the Windows registry, so [creating a system restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and [backing up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before proceeding is essential. That way, you can easily restore your computer if anything goes wrong.

 Once you’ve done that, follow these steps to turn off the feature:

1. Press the **Windows** key to open the Start menu.
2. Type **regedit** in the search bar and hit **Enter** to open the Registry Editor.
3. If the User Account Control window prompts, click **Yes** to give the program permission.
4. In the left sidebar, navigate to this path:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\Connect`
5. If you don’t see the Connect key at this location, right-click on Windows and select **New > Key**. Name it **Connect** and press **Enter**.
6. Now, right-click on Connect and select **New** \> **DWORD (32-bit) Value**.
7. Name the value **RequirePinForPairing** and press **Enter**. Doing so will create a new DWORD in the registry.
8. Double-click on this newly created value to open its Properties window.  
![Tweak Registry to Disable Require PIN for Pairing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/tweak-registry-to-disable-require-pin-for-pairing.jpg)
9. Set the **Value data** to **0** and click **OK** to save the changes.

 Once you've done that, exit the Registry Editor window and restart your computer. After restart, you won't need a PIN when projecting your computer onto another screen.

 To turn the feature back on, follow the same steps but set the **Value data** to **1**. This will enable the required PIN for pairing settings when projecting to a Windows 11 PC​​​​​.

## 4\. Using a REG File

 The fourth and final option is to use a REG file. This method is for those who have little or no experience with the Registry Editor. The REG file contains instructions that edit the Windows registry on your behalf. If you'd rather use this method, here’s what you need to do:

1. Right-click on Start and select **Run** from the menu.
2. Type **Notepad** in the text field and press **Enter**.
3. In the Notepad window, type or copy-paste the following code lines:  
`<code>Windows Registry Editor Version 5.00  

[HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\Connect]  
"RequirePinForPairing"=dword:00000001`
4. Click **File** and select **Save as** from the menu.
5. In the Save As window, click the **Save as type** drop-down menu and select **All files**.
6. Name the file **DisableRequirePin.reg** and select **Desktop** from the left sidebar.  
![Disable the Required PIN for Pairing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-the-required-pin-for-pairing.jpg)
7. Now click **Save** and exit Notepad. You'll find the REG file on your desktop.
8. Double-click on it and select **Yes** when prompted. This will edit the registry on your behalf.

 Once done, restart your computer and the settings will be saved automatically. You won't need to enter a PIN when projecting your PC onto another screen.

 If you ever want to re-enable this feature, repeat the same steps as above and use this code in Notepad:

`<code>Windows Registry Editor Version 5.00  
  
[HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\Connect]  
"RequirePinForPairing"=dword:00000003`

 Save the file with the **EnableRequirePin.reg** filename and double-click on it to edit the registry.

 After that, restart your computer and the setting will be enabled. You'll now need to enter a PIN each time you project the PC onto another screen.

## Project to a Windows 11 PC Without Requiring a PIN

 Projecting your PC onto another display is a useful feature that allows you to mirror or extend your computer screen. Now you know how to do so without needing to enter your PIN every time.

 However, if you’re the only person using your computer, you may find this extra security measure unnecessary. Let’s explore how to disable the "require PIN for pairing" setting when projecting to your PC in Windows 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-helps.techidaily.com/2024-approved-navigating-tiny-worlds-5-ways-to-zoom-in-on-minecraft/"><u>2024 Approved  Navigating Tiny Worlds  5 Ways to Zoom In on Minecraft</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-and-discord-fixing-the-deadly-js-error-quickly/"><u>Win 11 and Discord: Fixing The Deadly JS Error Quickly</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-discovering-the-hidden-truth-behind-youtubes-viewer-numbers-for-2024/"><u>[Updated] Discovering the Hidden Truth Behind YouTube's Viewer Numbers for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-windows-backup-configuration-recollection/"><u>Steps for Windows Backup Configuration Recollection</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-top-7-sites-for-swapping-outringtone-files-on-snapchat/"><u>[New] Top 7 Sites for Swapping Outringtone Files on Snapchat</u></a></li>
<li><a href="https://windows11.techidaily.com/dodging-unsupported-issue-in-windows-5-fixes/"><u>Dodging 'Unsupported' Issue in Windows: 5 Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-msvcr110dll-absence-a-solution-walkthrough/"><u>Tackling the Msvcr110.dll Absence: A Solution Walkthrough</u></a></li>
<li><a href="https://windows11.techidaily.com/deleting-persistent-epic-launcher-without-hurdles-in-w11/"><u>Deleting Persistent Epic Launcher Without Hurdles in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-continuous-play-fixing-fall-guys-errors-in-windows-os/"><u>Ensuring Continuous Play: Fixing Fall Guys Errors in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/expedite-photo-corrections-ps-and-windows-strategy/"><u>Expedite Photo Corrections: PS & Windows Strategy</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-vidvibes-merge-android-and-ios-insta-photos/"><u>2024 Approved  VidVibes  Merge Android & iOS Insta Photos</u></a></li>
<li><a href="https://windows11.techidaily.com/disarming-the-windows-11-afc-error-camera-app-solution/"><u>Disarming the Windows 11 AFC Error: Camera App Solution</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-achieving-high-res-on-twitter-vids/"><u>[New] In 2024, Achieving High-Res on Twitter Vids</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-navigating-noise-sensational-success-in-telegram-marketing/"><u>In 2024, Navigating Noise  Sensational Success in Telegram Marketing</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11s-printer-interface-max-48-chars/"><u>Unlocking Windows 11'S Printer Interface (Max 48 Chars)</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-maximizing-video-impact-on-youtube-top-video-formats/"><u>[Updated] Maximizing Video Impact on YouTube – Top Video Formats</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-razer-device-absence-in-win-1011-via-synapse/"><u>Addressing Razer Device Absence in Win 10/11 via Synapse</u></a></li>
<li><a href="https://audio-editing.techidaily.com/the-future-of-speech-recognition-audio-conversion-into-written-language-for-2024/"><u>The Future of Speech Recognition Audio Conversion Into Written Language for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-a-beginners-guide-understanding-discord-stickers/"><u>[Updated] 2024 Approved  A Beginner's Guide  Understanding Discord Stickers</u></a></li>
<li><a href="https://windows11.techidaily.com/unplugged-no-more-six-methods-to-restore-functioning-network-hardware-on-your-pc/"><u>Unplugged No More: Six Methods to Restore Functioning Network Hardware on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/find-your-windows-11-backdrops-saving-spot/"><u>Find Your Windows 11 Backdrop's Saving Spot</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-mastering-the-art-of-free-music-integration-into-video-media/"><u>2024 Approved Mastering the Art of Free Music Integration Into Video Media</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-solve-missing-dll-rockalldlldll-error/"><u>Steps to Solve Missing DLL: Rockalldll.dll Error</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-print-guide-to-making-your-powerpoint-shine-on-a-windows-system/"><u>The Ultimate Print Guide to Making Your PowerPoint Shine on a Windows System</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/pro-audio-advantages-unveiling-the-top-4-video-volume-enhancers-on-the-net-for-2024/"><u>Pro Audio Advantages Unveiling the Top 4 Video Volume Enhancers on the Net for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-from-clueless-to-confident-configuring-zoom-made-simple/"><u>2024 Approved  From Clueless to Confident  Configuring Zoom Made Simple</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-updating-obstacles-a-compreeher-guide-to-fixes/"><u>Clearing Updating Obstacles: A Compreeher Guide to Fixes</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-error-code-963-on-google-play-of-samsung-galaxy-s23plus-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Error Code 963 on Google Play Of Samsung Galaxy S23+ | Dr.fone</u></a></li>
<li><a href="https://driver-install.techidaily.com/hp-printer-model-p1102w-driver-for-windows-os/"><u>HP Printer Model P1102w Driver for Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/accurate-assessment-of-system-resources-in-windows-11/"><u>Accurate Assessment of System Resources in Windows 11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-the-art-of-video-marketing-titles-and-tags-on-youtube/"><u>[Updated] The Art of Video Marketing  Titles & Tags on YouTube</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-in-2024-best-timecode-calculators-online-mobile-and-more/"><u>Updated In 2024, Best Timecode Calculators Online, Mobile, and More</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-the-ultimate-guide-to-converting-text-to-mp3-with-ease/"><u>New The Ultimate Guide to Converting Text to MP3 with Ease</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-all-about-dji-inspire-1-detailed-survey/"><u>[New] All About  DJI Inspire 1 Detailed Survey</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-window-11-safety-with-best-in-class-password-protectors/"><u>Elevating Window 11 Safety with Best-in-Class Password Protectors</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-to-extending-windows-1011-contextual-commands/"><u>Step-by-Step Guide to Extending Windows 10/11 Contextual Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/delaying-windows-11-shutdown-managing-ongoing-processes/"><u>Delaying Windows 11 Shutdown: Managing Ongoing Processes</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-unwanted-hibernation-usb-tweaks-for-windows-11/"><u>Avoid Unwanted Hibernation - USB Tweaks for Windows 11</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-proven-hashtag-hacks-for-amplifying-your-tiktok-presence-for-2024/"><u>[New] Proven Hashtag Hacks for Amplifying Your TikTok Presence for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-battlenet-accessibility-on-1011-systems/"><u>Unlocking Battle.net Accessibility on 10/11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-reset-account-lockout-counter-post-failed-sign-in-attempts/"><u>Adjusting Reset Account Lockout Counter Post-Failed Sign-In Attempts</u></a></li>
<li><a href="https://windows11.techidaily.com/time-tinkering-tools-top-windows-programs-for-date-adjustment/"><u>Time Tinkering Tools: Top Windows Programs for Date Adjustment</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-service-disruptions-with-steam-windows-11-style/"><u>Addressing Service Disruptions with Steam, Windows 11 Style</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-tasteful-audio-enhancer-for-video-based-platforms/"><u>In 2024, Tasteful Audio Enhancer for Video-Based Platforms</u></a></li>
<li><a href="https://windows11.techidaily.com/black-friday-extravaganza-save-big-612-forever-win10/"><u>Black Friday Extravaganza: Save Big - $6.12 Forever Win10</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-essential-techniques-for-vimeo-video-submission-from-mmc/"><u>In 2024, Essential Techniques for Vimeo Video Submission From MMC</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/what-legendaries-are-in-pokemon-platinum-on-huawei-nova-y91-drfone-by-drfone-virtual-android/"><u>What Legendaries Are In Pokemon Platinum On Huawei Nova Y91? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/why-sudo-is-revolutionizing-windows-systems/"><u>Why Sudo Is Revolutionizing Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/discovering-the-path-into-windows-11-insider-group/"><u>Discovering the Path Into Windows 11 Insider Group</u></a></li>
<li><a href="https://windows11.techidaily.com/file-finder-simplicity-windowed-explorer-reduction-technique/"><u>File Finder Simplicity: Windowed Explorer Reduction Technique</u></a></li>
<li><a href="https://windows11.techidaily.com/taskers-edge-enigma-hidden-processes/"><u>Tasker's Edge Enigma: Hidden Processes?</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-path-to-perfect-visuals-an-advanced-course-in-vce-22/"><u>The Path to Perfect Visuals  An Advanced Course in VCE 2.2</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-memory-integrity-on-windows-11-methods-77/"><u>Unlocking Memory Integrity on Windows 11: Methods 7/7</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-speed-of-microsoft-edge-on-win10plus11/"><u>Enhancing Speed of Microsoft Edge on Win10+11</u></a></li>
<li><a href="https://windows11.techidaily.com/utilizing-windows-widgets-for-real-time-resource-tracking/"><u>Utilizing Windows Widgets for Real-Time Resource Tracking</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-windows-update-fixes-for-error-0x800736cc/"><u>Streamlining Windows Update Fixes for Error 0X800736CC</u></a></li>
</ul></div>
