---
title: Turn On Copy & Paste Within Edge's Protected Area, Win 11 Edition
date: 2024-11-22T23:05:30.999Z
updated: 2024-11-24T19:02:35.641Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Turn On Copy & Paste Within Edge's Protected Area, Win 11 Edition
excerpt: This Article Describes Turn On Copy & Paste Within Edge's Protected Area, Win 11 Edition
keywords: Turn on Paste in Windows 11,Win 11 Copy Shortcut,Enable Edge Clipboard,Copy & Paste Win 11 Edge,Protected Area Copying,Pasting Within Windows,Windows 11 Protection Features
thumbnail: https://thmb.techidaily.com/ae6df8d795ccb00d61125315956262434c01d350a9cd0692f6268b3c3a74de3f.jpg
---

## Turn On Copy & Paste Within Edge's Protected Area, Win 11 Edition

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DBMTAJBx-X4?si=sje5pFJXiHzJJGbP&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Enable Copy and Paste via Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-via-windows-settings.jpg)
7. The UAC prompt will appear on the screen. Click**Yes** to continue.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLO5dwmJAVs?si=1OYH8rv8aPaMsCiU&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you’ve completed the steps, restart your computer for the changes to work. Now, you can securely transfer data between a virtualized environment and your device without any worries about security risks - malicious websites and applications will be blocked even with this setting enabled.

 If you ever need to disable copy and paste in Application Guard for Edge, you can follow the same steps mentioned above. Just be sure to toggle off the Copy and Paste setting from the Isolated browsing menu instead.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/B2MlLvGxMwI?si=q_blGjXyJrGtzT8d&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fqBKCGAKHmA?si=OkoaI17nE5qNqTHj&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you’ve completed the steps, close any running applications and restart your computer

 If you'd like to turn off this feature, just repeat the aforementioned steps, but set the Value data to**0** and click**OK** . That's all it takes for your changes to be put into effect!

 Now that you've read the above steps, you should have a clear understanding of how to enable and disable copy and paste within Application Guard for Edge on Windows 11.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-0Ww1YIIUe4?si=cQ-Gkh9UCJABuPZU&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-8-best-multiple-video-call-and-chat-tools-for-conference-and-friends/"><u>[Updated] 2024 Approved 8 Best Multiple Video Call & Chat Tools for Conference and Friends</u></a></li>
<li><a href="https://tech-revival.techidaily.com/ogvmp4-movavi/"><u>網上免費OGV變更成MP4 - 使用Movavi編輯器進行流暢轉換</u></a></li>
<li><a href="https://blog-min.techidaily.com/encoder-av1-con-handbrake-possibili-e-non-piu-supportati/"><u>Encoder AV1 Con Handbrake: Possibili E Non Più Supportati?</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/future-proof-your-career-key-insights-into-effective-skype-interview-preparation/"><u>Future-Proof Your Career: Key Insights Into Effective Skype Interview Preparation</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-oppo-find-n3-to-other-android-devices-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from Oppo Find N3 to Other Android Devices Devices? | Dr.fone</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-best-free-flv-video-editors-for-beginners-and-pros-alike-for-2024/"><u>New Best Free FLV Video Editors for Beginners and Pros Alike for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/next-gen-cuts-select-best-6-video-editing-apps-for-mac-big-sur/"><u>Next-Gen Cuts Select Best 6 Video Editing Apps for Mac Big Sur</u></a></li>
<li><a href="https://windows11.techidaily.com/perfect-light-settings-on-windows-screens-with-best-brightools/"><u>Perfect Light Settings on Windows Screens with Best BrighTools</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-systemsettings-errors-in-windows-11/"><u>Preventing SystemSettings Errors in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resetting-error-with-windows-shadow-copy-service/"><u>Resetting Error with Windows' Shadow Copy Service</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-up-a-safe-workspace-windows-sandbox-11/"><u>Setting Up a Safe Workspace: Windows Sandbox 11</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ng-symbols-dynamic-animation-for-text-effects/"><u>Swaying Symbols Dynamic Animation for Text Effects</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/the-path-to-corporate-verbal-mastery-unveiled/"><u>The Path to Corporate Verbal Mastery Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/turbo-valorant-setup-escape-the-01kbs-download-drought/"><u>Turbo Valorant Setup: Escape the 0.1KB/S Download Drought</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-of-error-code-80080300-with-microsoft-teams/"><u>Unraveling the Mystery of Error Code 80080300 with Microsoft Teams</u></a></li>
</ul></div>

