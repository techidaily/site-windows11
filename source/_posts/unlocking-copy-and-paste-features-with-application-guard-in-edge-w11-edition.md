---
title: Unlocking Copy & Paste Features with Application Guard in Edge, W11 Edition
date: 2024-12-06T16:16:45.846Z
updated: 2024-12-10T16:25:56.759Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unlocking Copy & Paste Features with Application Guard in Edge, W11 Edition
excerpt: This Article Describes Unlocking Copy & Paste Features with Application Guard in Edge, W11 Edition
keywords: Edge AppGuard Clipboard,Edge Security Paste,Windows 11 Safety Feature,AppGuard Copy Protection,W11 Enhanced Clipping,Secure Clipboard Edge,Paste with Application Guard
thumbnail: https://thmb.techidaily.com/2e153e0e621bce9ac8484d65d8c4dd2eb6f5a3b85fbf991174fd2d0ac26c3edd.png
---

## Unlocking Copy & Paste Features with Application Guard in Edge, W11 Edition

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/nWu29cqFjZA?si=TNZyCbPq68PQ0JIb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Enable Copy and Paste via Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-via-windows-settings.jpg)
7. The UAC prompt will appear on the screen. Click**Yes** to continue.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LdVT_-3gESA?si=_HfjpbUEHSRKTXjt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you’ve completed the steps, restart your computer for the changes to work. Now, you can securely transfer data between a virtualized environment and your device without any worries about security risks - malicious websites and applications will be blocked even with this setting enabled.

 If you ever need to disable copy and paste in Application Guard for Edge, you can follow the same steps mentioned above. Just be sure to toggle off the Copy and Paste setting from the Isolated browsing menu instead.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/VxFUhesNCKo?si=Ti0ui6DXYP12sjSs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/GPk8_xpN_rA?si=YbAdgsjAKsCn_UsB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you’ve completed the steps, close any running applications and restart your computer

 If you'd like to turn off this feature, just repeat the aforementioned steps, but set the Value data to**0** and click**OK** . That's all it takes for your changes to be put into effect!

 Now that you've read the above steps, you should have a clear understanding of how to enable and disable copy and paste within Application Guard for Edge on Windows 11.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PKZUYice-ws?si=L8iMa9T3h7TMSWdQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-docs.techidaily.com/ecoding-youtubes-user-comment-selection-criteria/"><u>[New] Decoding YouTube's User-Comment Selection Criteria</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-in-2024-how-to-add-text-to-photos-on-windows-and-mac/"><u>[Updated] In 2024, How to Add Text to Photos on Windows and Mac</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-perfecting-the-science-of-converting-speech-to-text-with-google/"><u>[Updated] Perfecting the Science of Converting Speech to Text with Google</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-revamp-iphone-photos-effective-red-eye-removal-for-free/"><u>[Updated] Revamp iPhone Photos Effective Red-Eye Removal for FREE</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/amplify-your-channel-popularity-instantly-for-2024/"><u>Amplify Your Channel Popularity Instantly for 2024</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/elevate-your-print-quality-with-the-newest-hp-laserjet-p1007-drivers-download-today/"><u>Elevate Your Print Quality with the Newest HP LaserJet P1007 Drivers – Download Today</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-awaken-divine-powers-within-windows-11-os/"><u>How to Awaken Divine Powers Within Windows 11 OS</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-maximizing-b-roll-value-essential-techniques/"><u>In 2024, Maximizing B-Roll Value Essential Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/making-windows-10-work-tips-if-you-cant-upgrade/"><u>Making Windows 10 Work: Tips if You Can't Upgrade</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-obstacles-fixing-outlook-issues-in-windows/"><u>Overcoming Obstacles: Fixing Outlook Issues in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/pro-tips-for-capturing-uac-alerts-in-windows/"><u>Pro Tips for Capturing UAC Alerts in Windows</u></a></li>
<li><a href="https://vp-tips.techidaily.com/proven-strategies-for-powerful-customer-success-stories-on-screen/"><u>Proven Strategies for Powerful Customer Success Stories on Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-missing-alerts-a-guide-for-non-working-phone-link-on-pc/"><u>Restoring Missing Alerts: A Guide for Non-Working Phone Link on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-steps-for-bypassing-endless-logon-prompts/"><u>Troubleshooting Steps for Bypassing Endless Logon Prompts</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/standing-tseries-financial-gain-in-youtube-space-for-2024/"><u>Understanding TSeries' Financial Gain in YouTube Space for 2024</u></a></li>
</ul></div>

