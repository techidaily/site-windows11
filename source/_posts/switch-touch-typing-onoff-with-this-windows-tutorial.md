---
title: Switch Touch Typing On/Off with This Windows Tutorial
date: 2024-06-25T12:16:07.092Z
updated: 2024-06-26T12:16:07.092Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Switch Touch Typing On/Off with This Windows Tutorial
excerpt: This Article Describes Switch Touch Typing On/Off with This Windows Tutorial
keywords: Touch Typing Tutorial,Windows Typing Switch,Typing Software Guide,Turn Off Typing Mode,Windows User Typing,Enable Touch Type,Typing Techniques Window
thumbnail: https://thmb.techidaily.com/80e5cdef4afad3cdaa6f71026bfd555865de3d18de62989f967049cc703431b5.jpg
---

## Switch Touch Typing On/Off with This Windows Tutorial

 The fingertip writing feature in Windows allows users to write on a touch-enabled device using their fingertips, without a stylus or a pen. You can use it to input text directly into documents or applications easily.

 Below, we talk about the different ways to enable or disable the fingertip writing feature in the Handwriting Panel in Windows.

## 1\. Use the Settings App to Enable/Disable Fingertip Writing

 The easiest, most straightforward way to enable or disable the fingertip writing feature is by using the Settings app. You can make these changes in the Bluetooth & devices section and do not need to have administrative access to the system as well.

Here is how you can proceed:

1. Press the**Win** +**I** keys to open the Settings app.
2. Choose**Bluetooth & devices** from the left pane.
3. Move to the right side of the window and click on**Pen & Windows Ink** .  
![Access the Pen & Windows Ink section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/pen-and-windows-ink.jpg)
4. Expand the**Use your handwriting to enter text** section under Handwriting.
5. Checkmark the box associated with**Write with your fingertip** .  
![Write with your fingertip option in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/write-with-you-fingertip-1.jpg)

 You can now close the Settings app if you want. To disable the feature in the future, simply follow these steps again and uncheck the Write with your fingertip option.

## 2\. Enable/Disable Fingertip Writing via the Registry Editor

 If the "Write with your fingertip" option is disabled in the Settings app, you can also make these changes using the Registry Editor.

 Windows Registry is a powerful tool that is typically used to manage important system settings and configurations. This is an administrative-level utility, so you will need to log into your administrator account if you are using a standard user account to use it. You can also[convert your standard user account into an administrator account](https://www.makeuseof.com/windows-standard-adminstrator-account-differences/) .

 Once you have logged into Windows as an administrator,[create a Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) , just to be safe.

Then, proceed with these steps:

1. Press the**Win** +**R** keys together to open Run.
2. Type "regedit" in the text field of Run and click**Enter** .
3. Click**Yes** in the User Account Control prompt.
4. Once you have launced the Registry Editor, navigate to the location below:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\TabletTip`
5. Right-click on**TableTip** and choose**New** \>**Key** .  
![Create a new key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/create-new-key.jpg)

1. Name this key as EmbeddedInkControl.
2. Now, move to the right pane and right-click anywhere on an empty space.
3. Choose**New** \>**DWORD (32-bit) Value** .
4. Rename this key as EnableInkingWithTouch.
5. Double-click on**EnableInkingWithTouch** and under Value data, type 1\. This will enable the fingertip writing feature.  
![Enter 1 under Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enableinking-with-touch.jpg)
6. Click**OK** to save the changes.
7. Close the Registry Editor and restart your computer.

 Upon reboot, you should be able to use the fingertip writing feature. To disable this feature, follow the aforementioned steps again and change the value data of the EnableInkingWithTouch key to 0.

## 3\. Enable/Disable Fingertip Writing Via the Group Policy Editor

 The third way of enabling/disabling the fingertip writing feature is via the Group Policy Editor. Like the Windows Registry, this utility also allows the administrators to manage the advanced-level system settings in Windows.

 To use the Group Policy Editor for managing the fingertip writing feature, follow these steps:

1. Press the**Win** +**R** keys simultaneously to open Run.
2. Type "gpedit.msc" in Run and click**Enter** .
3. Click**Yes** in the User Account Control prompt.
4. Once you are in the Group Policy Editor, navigate to the location below:  
`Computer Configuration > Administrative Templates > Windows Components > Handwriting`
5. Locate the**Handwriting Panel Default Mode Docked** policy in the right pane and double-click on it.  
![Access the Handwriting panel default mode docked policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/handwriting-policy.jpg)
6. To enable the feature, choose**Not configured** . If you want to disable it, choose**Disable** .  
![Enable the handwriting panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-handwriting-panel-1.jpg)
7. Click**Apply** \>**OK** to save the changes.

 You can now close the Group Policy Editor and begin using the fingertip writing feature with ease.

## Use Your Fingertips to Write Away on Windows

 The fingertip writing feature can be a great tool for those who do not prefer using a stylus or a writing pen. You can use it to take handwritten notes and have them automatically converted into digital text which you then further organize and share.

 The three methods we have listed above should help you manage this feature easily. However, it is important to exercise caution and create a backup before you make any changes to the system settings and configurations.


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
<li><a href="https://windows11.techidaily.com/enhance-productivity-hotkey-tricks-to-reconfigure-windows/"><u>Enhance Productivity: Hotkey Tricks to Reconfigure Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-entry-techniques-for-your-windows-11-appshouse/"><u>Seamless Entry Techniques for Your Windows 11 AppsHouse</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-windows-steam-streams-stopping-zero-rate-issues/"><u>Optimize Windows Steam Streams: Stopping Zero-Rate Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-reversion-of-graphics-settings-for-optimal-viewing/"><u>Quick Reversion of Graphics Settings for Optimal Viewing</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-deadly-windows-1011-error-0x8007045d/"><u>Bypassing Deadly Windows 10/11 Error 0X8007045D</u></a></li>
<li><a href="https://windows11.techidaily.com/masking-task-view-button-on-win-11-bar/"><u>Masking Task View Button on Win 11 Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-memory-test-failed-in-windows/"><u>Combatting 'Memory Test Failed' In Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/peeling-back-the-layers-of-runtime-brokers-on-pcs/"><u>Peeling Back the Layers of Runtime Brokers on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-program-use-in-windows-via-right-click-options/"><u>Optimizing Program Use in Windows via Right-Click Options</u></a></li>
<li><a href="https://extra-information.techidaily.com/examining-the-best-technology-for-crystal-clear-4k-visuals/"><u>Examining the Best Technology for Crystal-Clear 4K Visuals</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-streamlining-the-process-vimeo-to-mp3-conversion/"><u>[Updated] 2024 Approved  Streamlining the Process  Vimeo to MP3 Conversion</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-navigating-mobile-recorders-to-capture-snapchat-moments/"><u>[New] Navigating Mobile Recorders to Capture Snapchat Moments</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-zoom-talks-with-a-twist-select-6-vocal-enhancement-tools-to-spice-up-video-calls-and-evoke-laughter/"><u>In 2024, Zoom Talks with a Twist Select 6 Vocal Enhancement Tools to Spice Up Video Calls and Evoke Laughter</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/leading-tools-for-extracting-fb-videos-top-5/"><u>Leading Tools for Extracting FB Videos - TOP 5</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-vivo-y78plus-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>In 2024, Vivo Y78+ ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://extra-support.techidaily.com/storage-capacity-64gb-vs-128gb-for-video-files-for-2024/"><u>Storage Capacity  64GB vs 128GB for Video Files for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-art-of-youtube-editing-a-compreenasive-guidebook/"><u>In 2024, The Art of YouTube Editing  A Compreenasive Guidebook</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-nokia-g42-5g-frp-by-drfone-android/"><u>In 2024, Step-by-Step Tutorial How To Bypass Nokia G42 5G FRP</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-analyzing-the-features-of-vegaspros-latest-release/"><u>2024 Approved  Analyzing the Features of VegasPro's Latest Release</u></a></li>
</ul></div>
