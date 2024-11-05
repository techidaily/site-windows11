---
title: Navigating the Background Run of Microsoft Edge on Win11
date: 2024-10-30T08:45:11.729Z
updated: 2024-11-04T19:26:49.392Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating the Background Run of Microsoft Edge on Win11
excerpt: This Article Describes Navigating the Background Run of Microsoft Edge on Win11
keywords: Edge Browser Win11,Windows 11 Edge Optimization,Microsoft Edge Performance,Win11 Browsing Efficiency,Edge Compatibility Win11,Enhancing Edge Experience,Microsoft Edge Features Win11
thumbnail: https://thmb.techidaily.com/1dd490a8bd0fd9490b2a1a7e2f3e07f4fe288167493a224a8c1401933c662484.jpeg
---

## Navigating the Background Run of Microsoft Edge on Win11

 If Edge is always runing in the background on Windows, it will use up your device's CPU and negatively impacts its memory, performance, and battery.

 Here are simple methods you can undertake to keep Edge from running in the background to improve your device’s performance.

## 1\. Change the Power Settings on Edge

 The easiest and most effective way to keep Edge from running undetected in the background on Windows 11 is to update its permissions from Settings.

1. Go to**Microsoft Edge** , click on the three vertical dots at the top-right (or press**Alt + F**), and select**Settings** .
2. Select**Settings** and click on**Systems and Performance** .
3. Find the toggle button for the option called **Continue running background extensions and apps when Microsoft Edge is closed** and turn it off.  
![changing settings in Microsoft Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/edge-settings.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2016165/19272" target="_top" id="2016165">
  <img src="//a.impactradius-go.com/display-ad/19272-2016165" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016165/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Edit the Windows Registry

 Another method to prevent Edge from running in the background is to tweak the Registry. Microsoft Edge is set to automatically start background processes at Windows startup. You can[disable processes set to run on startup](https://www.makeuseof.com/windows-pc-too-many-background-processes/) from the Registry.

 Before you make any changes to the Registry, make sure you[back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) to be safe in case something goes wrong.

 Press**Win + R,** type in regedit in the Run window, and press**Enter** . Once the Registry Editor opens, copy and paste the following path in the navigation bar at the top and press**Enter** :

`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Microsoft Edge\Main`

1. Right-click in the empty space in the right pane.
2. Select**New option > DWORD (32-bit) Value** .
3. Name the new file**AllowPrelaunch** .
4. After renaming the new file, double-click on the file and set its**Value data** to 0.  
![editing registry to disable automatic edge process startup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/edit-registry-edge-processes.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938745/19272" target="_top" id="1938745">
  <img src="//a.impactradius-go.com/display-ad/19272-1938745" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938745/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2047406/19272" target="_top" id="2047406">
  <img src="//a.impactradius-go.com/display-ad/19272-2047406" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047406/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Stop Edge Running in the Background to Ensure the Smooth Functioning of Your Device

 While Edge running in the background isn’t a major issue, preventing this from happening can go a long way in improving your device’s performance and freeing up its memory. Of course, Edge uses a lot of resources anyway, just like Chrome and Firefox. If you're trying to improve performance, you might consider looking for a light browser that isn't resource-intensive.

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
<li><a href="https://article-tips.techidaily.com/new-2024-approved-starlight-and-storms-in-high-fidelity-hdr-sky-websites/"><u>[New] 2024 Approved Starlight and Storms in High Fidelity HDR Sky Websites</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-whats-winning-in-the-world-of-2023-tweets/"><u>[Updated] In 2024, What's Winning in the World of 2023 Tweets</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/all-about-factory-reset-what-is-it-and-what-it-does-to-your-samsung-galaxy-s23-drfone-by-drfone-reset-android-reset-android/"><u>All About Factory Reset, What Is It and What It Does to Your Samsung Galaxy S23? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-common-fails-on-your-first-day-with-windows-11/"><u>Avoiding Common Fails on Your First Day with Windows 11</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/dvdmacpro/"><u>DVDMacPro</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-projector-disconnected-error-on-your-pc/"><u>Fixing Projector Disconnected Error on Your PC</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unresponsive-touch-screen-on-vivo-x-flip-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Touch Screen on Vivo X Flip | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-infinix-note-30-5g-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset Infinix Note 30 5G phone? | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-mastering-media-subtitles-transformation/"><u>In 2024, Mastering Media Subtitles Transformation</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-ai-to-enhance-shopping-on-the-ms-store/"><u>Leveraging AI to Enhance Shopping on the MS Store</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-new-horizinas-with-ease-top-8-windows-11-avoidances/"><u>Navigating New Horizinas with Ease: Top 8 Windows 11 Avoidances</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-gameplay-low-lag-high-fps-on-roblox-pcs/"><u>Optimizing Gameplay: Low Lag, High FPS on Roblox PCs</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/perfectly-smooth-window-snap-tool-for-2024/"><u>Perfectly Smooth Window Snap Tool for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/supercharge-win11s-notes-via-wise-mentor/"><u>Supercharge Win11's Notes via Wise Mentor</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-power-of-windows-internet-services-manager/"><u>Unlocking the Power of Windows Internet Services Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-dynamic-ui-embracing-the-new-widget-era/"><u>Windows 11'S Dynamic UI: Embracing the New Widget Era</u></a></li>
</ul></div>

