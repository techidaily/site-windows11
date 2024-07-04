---
title: Enabling Secure Transfer of Textual Data via Edges Guardspace, Win11 Version
date: 2024-06-25T12:15:43.470Z
updated: 2024-06-26T12:15:43.470Z
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

1. Right-click on Start and select**Settings** from the menu list. For more information, check out our guide on[how to open the Settings window](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
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
<li><a href="https://windows11.techidaily.com/tapping-into-your-true-essence-guide-for-accessing-windows-silent-personal-analyzer/"><u>Tapping Into Your True Essence: Guide for Accessing Windows' Silent Personal Analyzer</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-windows-version-numbers-post-update/"><u>Exploring Windows Version Numbers Post-Update</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11s-software-compatibility-tool/"><u>Navigating Windows 11’S Software Compatibility Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/phase-out-announcement-end-for-windows-781-on-microsoft-platforms/"><u>Phase-Out Announcement: End for Windows 7/8.1 on Microsoft Platforms</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tracker-tools-the-ultimate-6-list-for-windows-users/"><u>Essential Tracker Tools: The Ultimate 6 List For Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-creativity-in-calendar-design-a-windows-outlook-method/"><u>Unleashing Creativity in Calendar Design - A Windows Outlook Method</u></a></li>
<li><a href="https://windows11.techidaily.com/prevent-windows-stop-recurrent-file-explorer-launches/"><u>Prevent Windows: Stop Recurrent File Explorer Launches</u></a></li>
<li><a href="https://fix-guide.techidaily.com/quick-fixes-for-why-is-my-poco-c55-black-and-white-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Quick Fixes for Why Is My Poco C55 Black and White | Dr.fone</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-advanced-role-management-techniques-in-discord/"><u>[New] In 2024, Advanced Role Management Techniques in Discord</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/what-legendaries-are-in-pokemon-platinum-on-oppo-a58-4g-drfone-by-drfone-virtual-android/"><u>What Legendaries Are In Pokemon Platinum On Oppo A58 4G? | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-strategies-to-enhance-stability-of-win-11s-photo-viewer/"><u>[New] Strategies to Enhance Stability of Win 11'S Photo Viewer</u></a></li>
<li><a href="https://screen-capture.techidaily.com/leading-screen-grabbers-top-picks-for-windows-11-for-2024/"><u>Leading Screen Grabbers  Top Picks for Windows 11 for 2024</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-the-ultimate-video-editing-decision-final-cut-pro-or-lumafusion/"><u>New 2024 Approved The Ultimate Video Editing Decision Final Cut Pro or LumaFusion?</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-get-started-with-free-video-blurring-a-beginners-guide/"><u>Updated Get Started with Free Video Blurring A Beginners Guide</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-mastering-mind-games-top-trivia-channels-for-24/"><u>[Updated] Mastering Mind Games – Top Trivia Channels for '24</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-pacing-perfection-controlling-frame-rates-on-snapchat-for-2024/"><u>[New] Pacing Perfection  Controlling Frame Rates on Snapchat for 2024</u></a></li>
</ul></div>
