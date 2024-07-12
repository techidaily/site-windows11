---
title: Enabling Secure Transfer of Textual Data via Edges Guardspace, Win11 Version
date: 2024-07-11T21:34:59.038Z
updated: 2024-07-12T21:34:59.038Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enabling Secure Transfer of Textual Data via Edges Guardspace, Win11 Version
excerpt: This Article Describes Enabling Secure Transfer of Textual Data via Edges Guardspace, Win11 Version
keywords: EdgeSecureDataTransfer,TextDataWinGuardSpace,SecureTextEdgesGuard,GuardspaceTextTransfer,Win11SafeDataEdge,EdgesTextSecurityWin,GuardspaceDataWinXPatch
thumbnail: https://thmb.techidaily.com/1eb9ced51df0b5377c33b33676973c39490da0549a761ceba775a1dae7d61065.jpg
---

## Enabling Secure Transfer of Textual Data via Edges Guardspace, Win11 Version

 Looking to improve the security of your device? Microsoft Edge's Application Guard feature is an ideal solution, as it creates a virtualized atmosphere and blocks malicious websites. However, copy and paste functionality is disabled by default in this setting for extra precautionary measures.

 If you would like to switch on copy and paste within Application Guard for Edge on Windows 11, then this guide will assist you in doing so.

## 1\. How to Enable Copy and Paste via Windows Settings

 To enable copy and paste in Application Guard for Edge, follow the steps below:

1. Right-click on Start and select**Settings** from the menu list. For more information, check out our guide on [how to open the Settings window](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Privacy & security** from the left pane.
3. Then click the**Windows Security** option on the right-hand side.
4. On the following screen, select**App & browser control** .
5. Go to the Isolated browsing section and click the link "Change Applications Guard settings."  
![Change Application Guard Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/change-application-guard-settings.jpg)
6. Search for the**Copy and paste** option, then click the toggle to enable it.  
![Enable Copy and Paste via Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-via-windows-settings.jpg)
7. The UAC prompt will appear on the screen. Click**Yes** to continue.

 Once you’ve completed the steps, restart your computer for the changes to work. Now, you can securely transfer data between a virtualized environment and your device without any worries about security risks - malicious websites and applications will be blocked even with this setting enabled.

 If you ever need to disable copy and paste in Application Guard for Edge, you can follow the same steps mentioned above. Just be sure to toggle off the Copy and Paste setting from the Isolated browsing menu instead.

## 2\. How to Enable Copy and Paste Using Registry Editor

 The Windows Registry is another method you can use to copy and paste within Application Guard for Edge on your Windows 11 PC. But, please be aware that editing the registry can have severe consequences if done incorrectly. To be safe,[back up the registry data](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you begin making any changes.

 Follow these steps to enable copy and paste using the Windows Registry Editor:

1. Press**Win + R** on your keyboard to open the Run dialog box.
2. Type "regedit" in the text box and press the Enter key.
3. If UAC prompts appear on the screen, click**Yes** to confirm your action.
4. In the Registry Editor window, navigate to the following location:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Hvsi`
5. If you don't find the Hvsi key there, you will need to create it. To do this, right-click on Microsoft and select**New > Key** .

1. In the box that appears, give it the name**Hvsi** , and then hit Enter to save the file.
2. Now right-click on**Hvsi** and select**New > DWORD (32-bit) Value** .  
![Creating a new DWORD (32-bit) Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-dword-enableclipboard-key.jpg)
3. Put**EnableClipboard** as the name for the new DWORD key, then press Enter.
4. Click twice on the newly created DWORD key to open a pop-up window.
5. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Copy and Paste with Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-with-application-guard-for-edge.jpg)
6. Finally, click**OK** to save your changes.

 Once you’ve completed the steps, close any running applications and restart your computer

 If you'd like to turn off this feature, just repeat the aforementioned steps, but set the Value data to**0** and click**OK** . That's all it takes for your changes to be put into effect!

 Now that you've read the above steps, you should have a clear understanding of how to enable and disable copy and paste within Application Guard for Edge on Windows 11.

## Copy and Paste Now Works With Edge Application Guard

 With Application Guard for Edge, your device can remain secure while browsing the web. Unfortunately, certain functionalities such as copy and paste are disabled by default - but don't worry! This guide will explain two methods to activate them quickly and easily.


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
<li><a href="https://windows11.techidaily.com/unveiling-systems-peak-performance-limits/"><u>Unveiling System's Peak Performance Limits</u></a></li>
<li><a href="https://windows11.techidaily.com/enabledarkinterfacefornotepad/"><u>EnableDarkInterfaceForNotepad</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-discover-the-best-10-mac-screenshot-and-recording-apps/"><u>[New] Discover the Best 10 Mac Screenshot and Recording Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/detailed-process-of-downloading-and-setting-up-windows-11-arm-iso/"><u>Detailed Process of Downloading and Setting up Windows 11 ARM ISO</u></a></li>
<li><a href="https://windows11.techidaily.com/ad-ds-and-printer-woes-a-guide-for-windows-11-users/"><u>AD DS and Printer Woes: A Guide for Windows 11 Users</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-the-premier-free-online-confluence-of-mp3-files-2023-reviewed/"><u>2024 Approved The Premier Free Online Confluence of MP3 Files 2023 Reviewed</u></a></li>
<li><a href="https://windows11.techidaily.com/diving-into-devs-how-to-use-the-dev-drive-on-windows-11/"><u>Diving Into Devs: How to Use the Dev Drive on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-wisdom-efficiently-eliminate-partitioned-areas-on-your-pc/"><u>Windows Wisdom: Efficiently Eliminate Partitioned Areas on Your PC</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/ultimate-guide-to-get-the-meltan-box-pokemon-go-for-nubia-z50s-pro-drfone-by-drfone-virtual-android/"><u>Ultimate guide to get the meltan box pokemon go For Nubia Z50S Pro | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-twitter-to-tween-creating-free-animated-videos/"><u>[New] In 2024, Twitter to Tween  Creating FREE Animated Videos</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-step-into-the-world-of-aplus-tiktok-videos-with-designed-video-templates/"><u>In 2024, Step Into the World of A+ TikTok Videos with Designed Video Templates</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-comparative-reviews-beyond-the-norms-of-sharex-for-2024/"><u>[Updated] Comparative Reviews  Beyond the Norms of ShareX for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/uncovering-digital-shadows-sid-extraction-in-win11/"><u>Uncovering Digital Shadows: SID Extraction in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-of-windows-blue-screen-error-0x8007007e/"><u>Unraveling the Mystery of Windows Blue Screen Error: 0X8007007E</u></a></li>
<li><a href="https://windows11.techidaily.com/early-bird-benefits-automatic-open-of-windows-sticky-notes/"><u>Early Bird Benefits: Automatic Open of Windows' Sticky Notes</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/mac-video-editing-software-the-cream-of-the-crop-for-2024/"><u>Mac Video Editing Software The Cream of the Crop for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-revival-mastering-the-explore-ui-reset/"><u>Effortless Revival: Mastering the Explore UI Reset</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-history-for-lately-used-pages/"><u>Unlocking Windows History for Lately Used Pages</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-basic-routines-for-recording-on-youtube/"><u>2024 Approved  Basic Routines for Recording on YouTube</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-enhancing-visual-aesthetics-adding-black-bar-and-box-to-videos/"><u>[New] 2024 Approved  Enhancing Visual Aesthetics  Adding Black Bar & Box to Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/3-simple-methods-for-identifying-windows-ram/"><u>3 Simple Methods for Identifying Windows RAM</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-incorporating-a-god-mode-shortcut/"><u>Windows 11: Incorporating a God Mode Shortcut</u></a></li>
<li><a href="https://windows11.techidaily.com/breakdown-of-windows-11s-enhancements-february-update-speaks/"><u>Breakdown of Windows 11'S Enhancements – February Update Speaks</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-10-best-fake-gps-location-spoofers-for-oppo-reno-9a-drfone-by-drfone-virtual-android/"><u>In 2024, 10 Best Fake GPS Location Spoofers for Oppo Reno 9A | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-win11-uis-image-summaries/"><u>Customize Win11 UI's Image Summaries</u></a></li>
<li><a href="https://change-location.techidaily.com/the-magnificent-art-of-pokemon-go-streaming-on-samsung-galaxy-s23-drfone-by-drfone-virtual-android/"><u>The Magnificent Art of Pokemon Go Streaming On Samsung Galaxy S23? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/2024-approved-youtube-thumbnails-revamp-with-vibrant-neon-borders/"><u>2024 Approved  YouTube Thumbnails Revamp with Vibrant Neon Borders</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-resource-utilization-monitors/"><u>Advanced Resource Utilization Monitors</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-shotcut-video-editor-review/"><u>New 2024 Approved Shotcut Video Editor Review</u></a></li>
<li><a href="https://windows11.techidaily.com/window-watchers-sticky-pad-software-reviews-8-picks/"><u>Window Watchers: Sticky Pad Software Reviews (8 Picks)</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-narrating-numbers-making-millions-from-your-micro-vlogs/"><u>2024 Approved  Narrating Numbers  Making Millions From Your Micro-Vlogs</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-your-windowed-discord-interface-in-windows/"><u>Unblocking Your Windowed Discord Interface in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-the-pitfalls-of-low-end-activation-codes-in-windows/"><u>Avoiding the Pitfalls of Low-End Activation Codes in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-device-synergy-with-google-nearby-sharing/"><u>Unlocking Device Synergy with Google Nearby Sharing</u></a></li>
</ul></div>
