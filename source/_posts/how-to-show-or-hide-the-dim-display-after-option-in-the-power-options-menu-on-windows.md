---
title: How to Show or Hide the “Dim Display After” Option in the Power Options Menu on Windows
date: 2024-09-25T21:09:58.135Z
updated: 2024-09-26T16:03:21.105Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Show or Hide the “Dim Display After” Option in the Power Options Menu on Windows
excerpt: This Article Describes How to Show or Hide the “Dim Display After” Option in the Power Options Menu on Windows
keywords: Dim Display Control Windows,Hide/Show Display Option,Power Options Adjustments,Windows Display Settings,Change Display Mode Windows,Manage Screen Visibility Windows,Optimize Power Menu Windows
thumbnail: https://thmb.techidaily.com/344ccd42970473c822ce3d8647d1f132f07ed11b189d66bfa12739452e5e4fb4.jpg
---

## How to Show or Hide the “Dim Display After” Option in the Power Options Menu on Windows

 There are times when you need to step away from your PC, and if you’re gone long enough, the screen will automatically dim. Windows does this to preserve your battery, and you can adjust when your display should darken in the Power Options menu by editing the **Dim display after** option.

 If for some reason you can’t see the **Dim display after** option in the Power Options menu, or it’s there and you want to remove it, you can use PowerShell or the Registry Editor to show or hide it. Here’s how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Show or Hide the “Dim Display After” Option Using PowerShell

 First, launch Windows PowerShell. There are many [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/), but the easiest method is to press **Win + S** to open Windows Search. Then, enter **powershell** in the search box and click on **Windows PowerShell** when it appears in the search results.

![windows powershell in the windows search results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/windows-powershell-search.jpg)

 In PowerShell, enter the following command to show the **Dim Display after** option in the Power Options menu:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee -ATTRIB_HIDE

 To hide it, enter the following command:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee +ATTRIB_HIDE

 After entering the command you want, hit the **Enter** key on your keyboard for PowerShell to execute it. Afterward, the **Dim display after** option should appear or disappear accordingly in the Power Options menu.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925484/19272" target="_top" id="1925484">
  <img src="//a.impactradius-go.com/display-ad/19272-1925484" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925484/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Show or Hide the “Dim display after” Option Using the Registry Editor

 Considering how vital the [Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is for the smooth operation of Windows, you might want to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you edit it. Afterward, open the Registry Editor by pressing **Win + R**, typing **regedit** in the text box, and clicking **OK**.

![regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/regedit.jpg)

 Click **Yes** to bypass the UAC prompt.

 In the address bar of the Registry Editor, copy and paste the following text into it:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\7516b95f-f776-4464-8c53-06167f40cc99\17aaa29b-8b43-4b94-aafe-35f64daaf1ee

 On the right panel, double-click the **Attributes** entry to open it up for editing.

![the attributes entry in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-dim-display-after-attributes-entry.jpg)

<!-- affiliate ads begin -->
<a href="https://jalbum-affiliate-program.sjv.io/c/5597632/1838960/17916" target="_top" id="1838960">
  <img src="//a.impactradius-go.com/display-ad/17916-1838960" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://jalbum-affiliate-program.sjv.io/i/5597632/1838960/17916" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then, in the **Value data** text box, enter **1** to hide **Dim display after** in the Power Options menu or **2** to show it.

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135360/19272" target="_top" id="2135360">
  <img src="//a.impactradius-go.com/display-ad/19272-2135360" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135360/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now you can open the Power Options menu (see [how to open the power options on Windows 10](https://www.makeuseof.com/windows-10-open-power-options/)) and check under **Display** to see if the **Dim display after** option is there or not.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123508/26400" target="_top" id="2123508">
  <img src="//a.impactradius-go.com/display-ad/26400-2123508" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123508/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Controlling the “Dim Display After” Option in the Power Options Menu

 Now that you know how to show or hide **Dim display after**, you know what to do when you can’t find it in the Power Options menu or need to remove it. We recommend keeping it hidden and then bringing it up whenever you need it. This will make sure that no one messes with this important display setting when you’ve set it up perfectly.

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
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-digital-dynamos-8-youtube-channels-surging-forward/"><u>[Updated] 2024 Approved Digital Dynamos 8 YouTube Channels Surging Forward</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-ultimate-guide-to-using-vlc-from-mpeg-4-to-all-media-types/"><u>2024 Approved The Ultimate Guide to Using VLC From MPEG-4 to All Media Types</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-unlocking-successful-srt-shipping-out-of-premiere/"><u>2024 Approved Unlocking Successful SRT Shipping Out of Premiere</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-guide-on-faking-your-location-in-mozilla-firefox-on-xiaomi-14-drfone-by-drfone-virtual-android/"><u>A Detailed Guide on Faking Your Location in Mozilla Firefox On Xiaomi 14 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-tips-for-efficient-toolbar-usage-in-microsoft-win11-pcm/"><u>Advanced Tips for Efficient Toolbar Usage in Microsoft Win11 PCM</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-windows-11-camera-app-error-0xa00f425d-fixes/"><u>Disabling Windows 11 Camera App Error 0xA00F425D Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-vivetool-your-ticket-to-access-latest-windows-innovations/"><u>Discover ViVeTool: Your Ticket to Access Latest Windows Innovations</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-integration-portable-software-menus-for-w11plus/"><u>Easy Integration: Portable Software Menus for W11+</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-guide-to-mirror-your-infinix-note-30-vip-racing-edition-to-other-android-devices-drfone-by-drfone-android/"><u>In 2024, Guide to Mirror Your Infinix Note 30 VIP Racing Edition to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-the-slippery-slope-of-simulated-support-instagram-style/"><u>In 2024, The Slippery Slope of Simulated Support, Instagram Style</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-unleashing-radiance-skincare-and-haircare-secrets/"><u>In 2024, Unleashing Radiance Skincare and Haircare Secrets</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/inside-out-how-to-react-on-twitter-vids/"><u>Inside Out How to React on Twitter Vids</u></a></li>
<li><a href="https://windows11.techidaily.com/meeting-prep-101-test-your-windows-webcam-microphone/"><u>Meeting Prep 101: Test Your Windows Webcam, Microphone</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-to-become-a-win-11-insider/"><u>Step-by-Step to Become a Win 11 Insider</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-resolving-installation-issues-with-microsoft-store-apps/"><u>Steps for Resolving Installation Issues with Microsoft Store Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-pinpointing-device-serial-numbers-on-windows/"><u>The Ultimate Guide to Pinpointing Device Serial Numbers on Windows</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-macbook-videoleap-download-a-quick-and-simple-process/"><u>Updated In 2024, MacBook Videoleap Download A Quick and Simple Process</u></a></li>
</ul></div>

