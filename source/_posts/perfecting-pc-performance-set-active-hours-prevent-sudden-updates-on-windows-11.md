---
title: "Perfecting PC Performance: Set Active Hours, Prevent Sudden Updates on Windows 11"
date: 2024-09-05T02:10:43.214Z
updated: 2024-09-06T02:10:43.214Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Perfecting PC Performance: Set Active Hours, Prevent Sudden Updates on Windows 11"
excerpt: "This Article Describes Perfecting PC Performance: Set Active Hours, Prevent Sudden Updates on Windows 11"
keywords: Win11 Boost Performance,Optimize PC Windows,Schedule PC Updates,Avoid Windows Disruptions,Active Hours Setting,Windows 11 Stability,Update Pause Benefits
thumbnail: https://thmb.techidaily.com/d0c9b7047797b18daa1e1aa41be92c363eb13ba8f8bfa2b570a90a8bfa430bd1.jpg
---

## Perfecting PC Performance: Set Active Hours, Prevent Sudden Updates on Windows 11

 Typically, the installation of Windows updates necessitates a system restart, which can cause disruptions during critical work sessions. However, by configuring active hours, you can define the specific times during which you generally use your computer for work. Once you do, Windows will schedule update installations to occur outside of these active hours, ensuring that your work sessions remain uninterrupted.

 You can set active hours in Windows via the Settings app, the Group Policy Editor, or the Registry Editor. Let’s go through each of these methods in detail.

## 1\. How to Set Active Hours Manually via the Settings App

 The Settings app in Windows gives you several options for managing the installation of Windows updates. Here's how you can use it to set active hours on Windows 11\.

1. Press **Win + I** to open the Settings app.
2. Navigate to the **Windows Update** tab using the left sidebar.
3. Select **Advanced options**.
4. Click on **Active hours** to expand it.
5. Use the drop-down menu next to **Adjust active hours** to select **Manually**.
6. In the **Start time** and **End time** fields, specify the hours during which you typically use your device.  
![Set Active Hours Manually via the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-the-settings-app.jpg)

## 2\. How to Set Active Hours Manually Using the Group Policy Editor

 Although the Group Policy Editor on Windows is commonly used to manage advanced system-level settings, you can also use it to set active hours on your computer.

 Note that Group Policy Editor is only available on Professional, Education, and Enterprise editions of Windows. If you use Windows Home, check our guide on [how to access Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

 Follow these steps to set active hours on Windows using the Group Policy Editor.

1. Press **Win + R** to open the Run dialog box.
2. Type **gpedit.msc** in the box and press **Enter**.
3. Use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Update > Manage end user experience**.
4. Double-click the **Turn off auto-restart for updates during active hours** policy on your right.
5. Select the **Enabled** option.
6. Under **Options**, use the drop-down menus next to **Start** and **End** to specify your active hours.
7. Hit **Apply** followed by **OK**.  
![Set Active Hours Manually via Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-group-policy-editor.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037351/7443" target="_top" id="2037351">
  <img src="//a.impactradius-go.com/display-ad/7443-2037351" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037351/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. How to Set Active Hours Manually With the Registry Editor

 Another method for setting active hours involves tweaking the Windows Registry.

 Although setting active hours via the Registry Editor is a straightforward process, it’s important to be cautious, as incorrect changes made to registry files can render your PC inoperable. If you opt for this method, make sure you either [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

1. Press **Win + S** to access the search menu.
2. Type **registry editor** in the text box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > WindowsUpdate > UX > Settings**.
5. Double-click the **ActiveHoursStart** entry.
6. In the **Value data** field, enter the desired value for the start time of your active hours in a 24-hour format. If you were to set the start time to **9:00 AM**, for instance, you would enter **9** in the text box.
7. Click **OK** to save the value.  
![Set Active Hours Manually via Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-registry-editor.jpg)
8. Double-click the **ActiveHoursEnd** entry to set the end time of your active hours in the 24-hour format. For instance, if you want to set the end time to **5:00 PM**, type **17** in the Value data field and click **OK**.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1884002/19272" target="_top" id="1884002">
  <img src="//a.impactradius-go.com/display-ad/19272-1884002" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1884002/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
9. Exit the Registry Editor window.  
![Set Active Hours Manually via the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-the-registry-editor.jpg)

<!-- affiliate ads begin -->
<span id="1982508">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982508.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982508">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982508.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982508%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982508/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068408/7443" target="_top" id="2068408">
  <img src="//a.impactradius-go.com/display-ad/7443-2068408" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068408/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. How to Configure Windows to Set Active Hours Automatically

 You can also configure Windows to set active hours automatically. Doing so will allow Windows to analyze your usage patterns and automatically adjust the active hours accordingly.

 To configure Windows to set active hours automatically:

1. Use one of [the many ways to open the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/).
2. Navigate to **Windows Update > Advanced options > Active hours**.
3. Click the drop-down menu next to **Adjust active hours** and select **Automatically**.  
![Set Active Hours Automatically on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-automatically-on-windows.jpg)

<!-- affiliate ads begin -->
<span id="1982461">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982461.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982461">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982461.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982461%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982461/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006960/19272" target="_top" id="2006960">
  <img src="//a.impactradius-go.com/display-ad/19272-2006960" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006960/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Setting Active Hours on Windows Is Easy

 Once you set the active hours using one of the above methods, Windows will avoid initiating automatic restarts for updates during the specified period. As a result, you won’t be interrupted by sudden reboots during your work hours.

 You can set active hours in Windows via the Settings app, the Group Policy Editor, or the Registry Editor. Let’s go through each of these methods in detail.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-clips.techidaily.com/new-securely-save-your-favorite-facebook-films-on-chrome/"><u>[New] Securely Save Your Favorite Facebook Films on Chrome</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-xbox-screen-sharing-setting-up-for-fb-livestreaming/"><u>[New] Xbox Screen Sharing  Setting Up for FB Livestreaming</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-cultivating-inquisitive-interview-habits/"><u>[Updated] Cultivating Inquisitive Interview Habits</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-leading-microphones-for-enhanced-4k-video-clarity-and-sound/"><u>[Updated] In 2024, Leading Microphones for Enhanced 4K Video Clarity and Sound</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-mastering-stardew-on-ginger-islet/"><u>[Updated] Mastering Stardew on Ginger Islet</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-navigating-auto-captioned-content-in-social-media-visuals-for-2024/"><u>[Updated] Navigating Auto-Captioned Content in Social Media Visuals for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-top-tips-for-efficient-macos-sierra-system-updates/"><u>[Updated] Top Tips for Efficient macOS Sierra System Updates</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-unleash-flawless-footage-overcome-instagram-video-hurdles-for-2024/"><u>[Updated] Unleash Flawless Footage  Overcome Instagram Video Hurdles for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unveiling-the-magic-of-ar-mastering-lut-applications/"><u>[Updated] Unveiling the Magic of AR  Mastering LUT Applications</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1-unveiling-the-wonders-of-home-assistant-a-comprehensive-guide/"><u>1. Unveiling the Wonders of Home Assistant: A Comprehensive Guide</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/p-tier-cameras-that-will-transform-your-vlogging-experience/"><u>12 Top-Tier Cameras That Will Transform Your Vlogging Experience</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-30-groundbre-writers-making-metaverse-memes-thrive/"><u>2024 Approved  30 Groundbre Writers  Making Metaverse Memes Thrive</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-a-detailed-exposition-on-harnessing-power-of-adobes-cloud-data-vaults/"><u>2024 Approved  A Detailed Exposition on Harnessing Power of Adobe's Cloud Data Vaults</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-elevating-storytelling-voiceovers-as-a-central-element/"><u>2024 Approved  Elevating Storytelling  Voiceovers as a Central Element</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-keeping-memories-above-ground-selecting-the-best-cloud-storage/"><u>2024 Approved  Keeping Memories Above Ground  Selecting the Best Cloud Storage</u></a></li>
<li><a href="https://android-location-track.techidaily.com/best-anti-tracker-software-for-itel-p40plus-drfone-by-drfone-virtual-android/"><u>Best Anti Tracker Software For Itel P40+ | Dr.fone</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/capture-the-essence-of-your-journey-with-canons-retro-styled-powershot-g9-x2/"><u>Capture the Essence of Your Journey with Canon’s Retro-Styled PowerShot G9 X2</u></a></li>
<li><a href="https://buynow-help.techidaily.com/comprehensive-analysis-of-nokia-e72-exceeding-mid-range-expectations/"><u>Comprehensive Analysis of Nokia E7.2 - Exceeding Mid-Range Expectations</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-advice-to-erase-dark-steam-display/"><u>Expert Advice to Erase Dark Steam Display</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-management-issues-5-approaches-with-windows-11-focus/"><u>Fixing Management Issues: 5 Approaches with Windows 11 Focus</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-through-the-signature-verification-failure-of-windows-1011/"><u>Guide Through the Signature Verification Failure of Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-audio-error-0xc00d36b4-in-windows-11-and-11/"><u>How to Fix the Audio Error 0Xc00d36b4 in Windows 11 & 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-contacts-from-google-by-fonelab-android-recover-contacts/"><u>How to recover deleted contacts from Google .</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-10-best-fake-gps-location-spoofers-for-itel-p40plus-drfone-by-drfone-virtual-android/"><u>In 2024, 10 Best Fake GPS Location Spoofers for Itel P40+ | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-full-guide-to-unlock-apple-iphone-x-with-itunes-by-drfone-ios/"><u>In 2024, Full Guide to Unlock Apple iPhone X with iTunes</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-top-6-appsservices-to-trace-any-apple-iphone-7-location-by-mobile-number-drfone-by-drfone-virtual-ios/"><u>In 2024, Top 6 Apps/Services to Trace Any Apple iPhone 7 Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/linux-desktops-analyzing-wsl-role/"><u>Linux Desktops: Analyzing WSL Role?</u></a></li>
<li><a href="https://windows11.techidaily.com/master-lately-opened-files-in-windows-os/"><u>Master Lately Opened Files in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-for-alleviating-power-management-issues-on-windows-devices/"><u>Methods for Alleviating Power Management Issues on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-remove-access-error-in-windows-file-explorer/"><u>Methods to Remove Access Error in Windows File Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/muting-windows-update-alerts-and-reminders/"><u>Muting Windows Update Alerts and Reminders</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-0xc00000f-on-pc-a-step-by-step-guide/"><u>Overcoming 0Xc00000f on PC: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-updating-problem-error-x8019/"><u>Overcoming Updating Problem: Error X8019</u></a></li>
<li><a href="https://windows11.techidaily.com/perfect-taskbar-alignment-with-win-11-tips/"><u>Perfect Taskbar Alignment with Win 11 Tips</u></a></li>
<li><a href="https://extra-support.techidaily.com/protecting-beats-on-instagram-for-2024/"><u>Protecting Beats on Instagram for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-fixing-erroneous-game-status-in-discord-pc/"><u>Quick Guide: Fixing Erroneous Game Status in Discord (PC)</u></a></li>
<li><a href="https://tech-revival.techidaily.com/quick-reset-guide-for-iphones-struggling-with-chatgpt-apps/"><u>Quick Reset Guide for iPhones Struggling with ChatGPT Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-organization-owned-chromeedge-issues-on-desktops/"><u>Resolving Organization-Owned Chrome/Edge Issues on Desktops</u></a></li>
<li><a href="https://windows11.techidaily.com/retrace-to-original-directory-view-in-windows-11/"><u>Retrace to Original Directory View in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-dotnet-top-5-reparations-for-pcs-max-156/"><u>Reviving DotNet: Top 5 Reparations for PCs (Max 156)</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-your-system-save-big-keys-fans-black-friday-treat-for-windows-11/"><u>Secure Your System, Save Big - Keys Fan's Black Friday Treat for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/skyrocket-your-tech-game-with-these-top-7-windows-tips-40/"><u>Skyrocket Your Tech Game with These Top 7 Windows Tips (40)</u></a></li>
<li><a href="https://windows11.techidaily.com/stay-fixed-no-change-in-your-windows-wallpaper/"><u>Stay Fixed: No Change in Your Windows Wallpaper</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-cooling-computers-running-hot-w11/"><u>Steps for Cooling Computers Running Hot W11</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-display-with-speed-meter-widget/"><u>Streamline Your Display with Speed Meter Widget</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-a-shimmering-window-title-bar-in-win11/"><u>Tips for A Shimmering Window Title Bar in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshoot-your-windows-xbox-app-woes/"><u>Troubleshoot Your Windows Xbox App Woes</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-a-non-operational-media-player-in-windows-11/"><u>Troubleshooting a Non-Operational Media Player in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-disappearing-windows-screen/"><u>Troubleshooting Disappearing Windows Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-windows-11-how-to-resolve-elevation-error-740/"><u>Unblocking Windows 11: How to Resolve Elevation Error #740</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-resolving-0x8007007e-windows-error/"><u>Understanding and Resolving 0X8007007E Windows Error</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-your-music-library-tackling-w10w11-errors/"><u>Unlocking Your Music Library: Tackling W10/W11 Errors</u></a></li>
<li><a href="https://vp-tips.techidaily.com/videokassetten-von-vhs-zu-dvd-auf-ihrem-computer-konvertieren-schritt-fur-schritt-anleitung/"><u>Videokassetten Von VHS Zu DVD Auf Ihrem Computer Konvertieren - Schritt-Für-Schritt-Anleitung</u></a></li>
<li><a href="https://windows11.techidaily.com/ways-to-deal-with-laptop-screen-tint-issue/"><u>Ways to Deal with Laptop Screen Tint Issue</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>