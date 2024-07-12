---
title: Activating Clipboard Operations in Application Guard (Edge) - Win11 Guide
date: 2024-07-11T22:20:26.874Z
updated: 2024-07-12T22:20:26.874Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Activating Clipboard Operations in Application Guard (Edge) - Win11 Guide
excerpt: This Article Describes Activating Clipboard Operations in Application Guard (Edge) - Win11 Guide
keywords: Edge AppGuard Clipboard Activation,Win11 Clipboard Enable,Application Guard Keyboard Use,Windows 11 Security Feature,Edge Operations Guide,Clipboard Management in Edge,Enabling AppGuard Functions
thumbnail: https://thmb.techidaily.com/c2342fb5e25c5a967555cf815791bd2b9698b049e69b2eb389ba72dc308a7ad2.jpeg
---

## Activating Clipboard Operations in Application Guard (Edge) - Win11 Guide

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
<li><a href="https://windows11.techidaily.com/customizing-security-a-comprehensive-guide-to-lock-patterns-in-windows-11/"><u>Customizing Security: A Comprehensive Guide to Lock Patterns in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/achieving-optimal-security-in-win-11-with-ms-defender-application-guard-for-edge/"><u>Achieving Optimal Security in Win 11 with MS Defender Application Guard for Edge</u></a></li>
<li><a href="https://windows11.techidaily.com/11-ways-to-open-the-credential-manager-on-windows-11/"><u>11 Ways to Open the Credential Manager on Windows 11</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-best-vocal-modification-software-for-content-creators/"><u>[New] 2024 Approved  Best Vocal Modification Software for Content Creators</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-permission-restrictions-on-windows/"><u>Deciphering Permission Restrictions on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-software-integration-the-windows-11-troubleshooter/"><u>Unlocking Software Integration: The Windows 11 Troubleshooter</u></a></li>
<li><a href="https://windows11.techidaily.com/disregard-met-not-fulfilled-emblem-on-win11/"><u>Disregard Met Not Fulfilled Emblem on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-excessive-cpu-load-by-dropbox-app-on-windows-devices/"><u>Addressing Excessive CPU Load by Dropbox App on Windows Devices</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-learn-to-quickly-cut-videos-using-built-in-windows-features/"><u>In 2024, Learn to Quickly Cut Videos Using Built-In Windows Features</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reactivate-muted-system-sound-output-quickly/"><u>How to Reactivate Muted System Sound Output Quickly</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-in-2024-how-to-create-a-youtube-intro/"><u>New In 2024, How To Create A YouTube Intro</u></a></li>
<li><a href="https://windows11.techidaily.com/flushing-dns-on-windows-best-practices/"><u>Flushing DNS on Windows: Best Practices</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-secrets-of-winnettoolbox/"><u>Unlocking the Secrets of WinNetToolbox</u></a></li>
<li><a href="https://windows11.techidaily.com/a-peek-at-your-gadgets-soul-6-methods-to-discover-its-make/"><u>A Peek at Your Gadget's Soul: 6 Methods to Discover Its Make</u></a></li>
<li><a href="https://windows11.techidaily.com/1719329285690-resolve-programming-discrepancies-with-no-troubleshoot-tool/"><u>Resolve Programming Discrepancies with No Troubleshoot Tool.</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-start-the-narrator-in-windows-11/"><u>How to Start the Narrator in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-onedrive-login-hiccup-zero-based-code-error-on-win11/"><u>Fixing OneDrive Login Hiccup: Zero-Based Code Error on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-taskmgr-with-command-line-interface-cli-feature/"><u>Enhance TaskMgr with Command Line Interface (CLI) Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/why-your-wallet-may-regret-inexpensive-windows-keys/"><u>Why Your Wallet May Regret Inexpensive Windows Keys</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-remove-forgotten-pin-of-your-xiaomi-redmi-note-12t-pro-by-drfone-android/"><u>How to Remove Forgotten PIN Of Your Xiaomi Redmi Note 12T Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-system-stability-automatic-windows-and-amd-driver-shift/"><u>Elevate System Stability: Automatic Windows & AMD Driver Shift</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-choosing-superior-tools-for-vocal-change-in-content-making/"><u>[Updated] 2024 Approved  Choosing Superior Tools for Vocal Change in Content Making</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-sonic-sharpening-advanced-techniques-for-precise-de-reverberation-in-audio-processing-for-2024/"><u>New Sonic Sharpening Advanced Techniques for Precise De-Reverberation in Audio Processing for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/voice-driven-document-creation-speech-transcription-with-ms-word/"><u>Voice-Driven Document Creation  Speech Transcription with MS Word</u></a></li>
<li><a href="https://windows11.techidaily.com/your-window-to-artistry-in-windows-1011/"><u>Your Window to Artistry in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/bridging-the-gap-between-wi-fi-and-ethernet-in-windows/"><u>Bridging the Gap Between Wi-Fi and Ethernet in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-users-through-fixing-nvidias-unreachable-error/"><u>Guiding Users Through Fixing NVIDIA's 'Unreachable' Error</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-uninstall-oneself-avoiding-admin-restrictions-in-windows/"><u>How To Uninstall Oneself: Avoiding Admin Restrictions in WINDOWS</u></a></li>
<li><a href="https://windows11.techidaily.com/what-is-and-isnt-allowed-in-windows-11-s-mode/"><u>What Is and Isn’t Allowed in Windows 11 S Mode</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-teleport-your-gps-location-on-samsung-galaxy-s24plus-drfone-by-drfone-virtual-android/"><u>How To Teleport Your GPS Location On Samsung Galaxy S24+? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/unplugged-os-easy-win11-setup-without-internet/"><u>Unplugged OS: Easy Win11 Setup without Internet</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-windows-11-audio-adjustment-tools/"><u>Unveiling the Windows 11 Audio Adjustment Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-of-winerrors-your-guide-to-fixes/"><u>Unraveling the Mystery of WinErrors: Your Guide to Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-looks-like-youre-stranded-xbox-app-error-in-windows-11-and-11/"><u>How to Fix the “Looks Like You’re Stranded” Xbox App Error in Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-high-dynamic-range-mastered-for-the-modern-user/"><u>Windows 11'S High Dynamic Range Mastered for the Modern User</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-windows-innovations-to-enrich-macos/"><u>Leveraging Windows Innovations to Enrich macOS</u></a></li>
<li><a href="https://windows11.techidaily.com/amp-up-your-vehicles-performance-with-these-top-windows-upgraders/"><u>Amp up Your Vehicle's Performance with These Top Windows Upgraders</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-instagram-blast-your-favorite-episode-now/"><u>[Updated] Instagram Blast Your Favorite Episode Now</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/the-ultimate-strategy-for-crafting-viral-gadget-unboxings/"><u>The Ultimate Strategy for Crafting Viral Gadget Unboxings</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-data-disaster-save-and-recover-snippets/"><u>Avoiding Data Disaster: Save & Recover Snippets</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-gopro-hero-4-vs-sony-dslr-for-extreme-sports-which-rules-the-arena/"><u>2024 Approved  GoPro Hero 4 Vs Sony DSLR for Extreme Sports  Which Rules the Arena?</u></a></li>
<li><a href="https://windows11.techidaily.com/launching-windows-file-explorer-directly-via-onedrive/"><u>Launching Windows File Explorer Directly via OneDrive</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-manage-windows-deletion-prompt-actions/"><u>Efficiently Manage Windows' Deletion Prompt Actions</u></a></li>
<li><a href="https://android-frp.techidaily.com/latest-guide-how-to-bypass-samsung-galaxy-s23-ultra-frp-without-computer-by-drfone-android/"><u>Latest Guide How To Bypass Samsung Galaxy S23 Ultra FRP Without Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-iphone-photographic-file-import-failures-on-windows-pcs/"><u>Handling iPhone Photographic File Import Failures on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/from-standard-to-stylish-personalize-each-window-11-screen/"><u>From Standard to Stylish: Personalize Each Window 11 Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-system-resource-usage-details-to-the-windows-system-tray/"><u>How to Add System Resource Usage Details to the Windows System Tray</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-actions-for-windows-interface-crashing/"><u>Immediate Actions for Windows Interface Crashing</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/here-are-some-of-the-best-pokemon-discord-servers-to-join-on-zte-axon-40-lite-drfone-by-drfone-virtual-android/"><u>Here are Some of the Best Pokemon Discord Servers to Join On ZTE Axon 40 Lite | Dr.fone</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/ultimate-guide-to-the-best-10-online-platforms-for-vimeo-downloading-for-2024/"><u>Ultimate Guide to the Best  10 Online Platforms for Vimeo Downloading for 2024</u></a></li>
</ul></div>
