---
title: Bypassing Verification Barrier when Installing Non-Microsoft Apps
date: 2024-07-11T22:15:06.806Z
updated: 2024-07-12T22:15:06.806Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Bypassing Verification Barrier when Installing Non-Microsoft Apps
excerpt: This Article Describes Bypassing Verification Barrier when Installing Non-Microsoft Apps
keywords: Bypass Verification,Non-Microsoft Apps,Installation Hurdles,Unofficial Software,Security Loopholes,Alternative Apps,Microsoft Barrier Skip
thumbnail: https://thmb.techidaily.com/cf88e87b734b5b9f59ddbd2f8f99680f9b1ec3ba8de831308f2fd3fe15c5bbed.jpg
---

## Bypassing Verification Barrier when Installing Non-Microsoft Apps

 Have you encountered the error"the app you're trying to install isn't a Microsoft-verified app"while installing an app? The error occurs if you have configured your system to only install apps from the Microsoft Store. You could have set this permission on purpose, or it might have been set by default.

 Other than that, a corrupted Microsoft Store cache, installing an app from an unofficial source, and enabling Windows S mode can also cause the error. Below, you will find a few checks and fixes you should apply to resolve the error and install the app successfully.

## 1\. Install the App From the Microsoft Store

 Considering you get the error when downloading apps outside the Microsoft Store, it makes sense to first check if the same app is available there. If the app is available, you can download it from there, and there won't be any need to go through advanced troubleshooting.

 Therefore, [open the Microsoft Store](https://www.makeuseof.com/windows-open-microsoft-store/) and search for the app. If you find the app in the store, click the **Get** button to install it. However, if the app isn't available in the store and can only be downloaded from another source, ensure it is safe to download.

## 2\. Make Sure the App You're Downloading Is Safe

 Microsoft doesn't allow untrusted publishers to list their apps on the Microsoft Store. If you haven't found the app on the store, it could be unsafe and infect your computer. Thus, ensure that the app you want to download is secure before downloading.

 To determine if an app is safe, copy its download link and paste it into [VirusTotal's URL search box](https://www.virustotal.com/gui/home/url). After that, press **Enter**.

![Check the Authenticity of a Software by Entering its URL in VirusTotal’s Official Website](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/1-check-the-authenticity-of-a-software-by-entering-its-url-in-virustotal-s-official-website.jpg)

 If the scanner doesn't find any problems with the download link, it's probably safe. After ensuring that, you can apply the remaining fixes to enable app installation outside the store.

## 3\. Change the Operating System App Settings

 Microsoft cares about the safety and security of its Windows users. To facilitate that, Windows offers a feature that blocks the installation of apps outside the Microsoft Store. The downside of enabling this feature is that it prevents users from installing popular and safe applications from the web.

 When users try to install an app with this restriction turned on, Windows will likely display an error message saying that the app isn't a Microsoft-verified app. Therefore, to avoid encountering the error described above, you should allow Windows to install apps outside the Microsoft Store.

 To modify the app permissions on Windows 10, follow the steps below:

1. Open the **Settings** app.
2. Open **Apps** settings and select **Apps and Features** from the left sidebar.
3. Select **Anywhere** from the dropdown menu under **Choose where to get apps**.

 To modify app permissions on Windows 11, open the **Settings** app, select the **Apps** tab, and then go to **Advanced app settings**.

![Go to Advanced Apps Settings in Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/2-go-to-advanced-apps-settings-in-windows-settings-app.jpg)

 Select **Anywhere** from the dropdown menu next to **Choose where to get apps**.

![Select Anywhere From the Dropdown Menu Next to Choose Where to Get Apps Option in Apps Settings in Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/3-select-anywhere-from-the-dropdown-menu-next-to-choose-where-to-get-apps-option-in-apps-settings-in-windows-settings-app.jpg)

## 4\. Turn Off the App Install Control Policy

 The App Install Control is a Microsoft Defender SmartScreen feature that prevents users from installing apps outside the Microsoft Store. It does this to prevent users from infecting their devices with third-party applications.

 Therefore, you should turn off this feature to remove any restrictions. To turn it off, follow these steps:

1. Open the Local Group Policy Editor. To do this, check out [how to open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) if you're not using Windows Home edition, and learn [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) if you are.
2. Navigate to **Computer Configuration > Administrative Templates > Windows Components > Windows Defender SmartScreen > Explorer**.  
![Go to Explorer Folder by Navigating to the Path in Windows Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/4-go-to-explorer-folder-by-navigating-to-the-path-in-windows-local-group-policy-editor.jpg)
3. Open the policy for **Configure App Install Control**.
4. Select **Disabled** to turn off this feature.  
![Disable the Policy for Configure App Install Control in Windows Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/5-disable-the-policy-for-configure-app-install-control-in-windows-local-group-policy-editor.jpg)

## 5\. Change the App Install Control Permission in the Registry Editor

 To modify the App Install Control permissions via the Registry Editor, follow the below steps:

1. Open the Registry Editor.
2. Navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer**.  
![Go to Explorer Folder by Navigating to the Path in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/6-go-to-explorer-folder-by-navigating-to-the-path-in-windows-registry-editor.jpg)
3. Right-click on **Explorer** and select **New > String value**.  
![Create New String Value in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/7-create-new-string-value-in-windows-registry-editor.jpg)
4. Name this new value **"AicEnabled."**  
![Name the Newly Created String Value AicEnabled in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/8-name-the-newly-created-string-value-aicenabled-in-windows-registry-editor.jpg)
5. Double-click on the newly created string and type "**Anywhere"** in the **Value data** field.  
![Type Anywhere in the Value Data Field of Newly Created String in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/9-type-anywhere-in-the-value-data-field-of-newly-created-string-in-windows-registry-editor.jpg)
6. Restart the computer for the changes to take effect.

 If the above Registry tweak does not resolve the issue, turn off S mode.

## 6\. Disable Windows S Mode

 Windows S mode is primarily the most secure environment you can get in Windows. It mainly serves as a means of protecting your children and keeping sensitive documents away from prying eyes.

 When this mode is active, users can only download apps from the Microsoft Store, can't use the command line or code editors, and can't modify the Windows Registry Editor.

 Therefore, if you have recently bought a new device and this mode is enabled there by default, Windows will probably throw the error if you attempt to install any app outside the store. Therefore, you should make sure it isn't enabled and disable it if it is.

 To determine whether your device is running S mode, open the **Settings** app, select the **System** tab on the left, and open the **About** page.

 If the S mode is enabled on your device, you'll see it there. If the feature is active, turn it off by following these steps:

1. Open the **Settings** app.
2. Navigate to the **System** tab and go to **Activation**.
3. Click on **Go to the store** under **Switch to Windows 11 Home/Pro**, which will take you to the Microsoft Store page where you can opt out of S mode.
4. Click the **Get** button and follow the on-screen instructions to get out of S mode.

## 7\. Run the Windows Store Apps Troubleshooter

 If the Windows S mode isn't enabled, and you haven't restricted your operating system from downloading apps from outside Microsoft, the error could be caused by an underlying issue with the Microsoft Store. To ensure this is not the case, you should run the Windows Store Apps troubleshooter, which is a built-in tool for troubleshooting issues with the Store.

 If you've never run the troubleshooter before, refer to our guide on [how to run a troubleshooter on Windows 10 or 11](https://www.makeuseof.com/run-troubleshooter-windows-10-11/).

## Successfully Install Third-Party Applications Again on Windows

 Microsoft blocks the installation of third-party apps for your security, but it's pointless if it prevents you from installing vital apps. Hopefully, you now better understand why the Microsoft Store presents the "the app you're trying to install isn't a Microsoft-verified app" error. Following the fixes above will enable you to download the apps from unofficial sources.

 Have you encountered the error"the app you're trying to install isn't a Microsoft-verified app"while installing an app? The error occurs if you have configured your system to only install apps from the Microsoft Store. You could have set this permission on purpose, or it might have been set by default.

 Other than that, a corrupted Microsoft Store cache, installing an app from an unofficial source, and enabling Windows S mode can also cause the error. Below, you will find a few checks and fixes you should apply to resolve the error and install the app successfully.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/the-complete-list-of-windows-11s-narrator-keyboard-shortcuts/"><u>The Complete List of Windows 11'S Narrator Keyboard Shortcuts</u></a></li>
<li><a href="https://windows11.techidaily.com/slowing-down-windows-11-shutdown-tips-for-live-tasks/"><u>Slowing Down Windows 11 Shutdown: Tips for Live Tasks</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/sleek-skill-using-watch-to-unlock-mac-for-2024/"><u>Sleek Skill  Using Watch to Unlock Mac for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/4-ways-to-transfer-music-from-honor-magic-5-lite-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>4 Ways to Transfer Music from Honor Magic 5 Lite to iPhone | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-acoustiquest-investigating-soundscape/"><u>[New] In 2024, AcoustiQuest  Investigating Soundscape</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-top-tier-business-data-haven-selection/"><u>[Updated] Top-Tier Business Data Haven Selection</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/praise-in-pixels-the-new-marketing-trend-for-2024/"><u>Praise in Pixels  The New Marketing Trend for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-for-overcoming-license-expiration-notice-in-win11/"><u>Tactics for Overcoming License Expiration Notice in Win11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/from-blurred-to-clean-picsarts-background-elimination/"><u>From Blurred to Clean  Picsart's Background Elimination</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-microphone-errors-in-xbox-app-on-windows-11-systems/"><u>Navigating Microphone Errors in Xbox App on Windows 11 Systems</u></a></li>
<li><a href="https://extra-hints.techidaily.com/iphone-techniques-for-seamless-image-to-pdf-conversion/"><u>IPhone Techniques for Seamless Image-to-PDF Conversion</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-win-strategies-boosting-frames-in-cs-go/"><u>Quick Win Strategies - Boosting Frames in CS GO</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-an-uninstall-shortcut-to-the-context-menu-in-windows-1110/"><u>How to Add an Uninstall Shortcut to the Context Menu in Windows 11/10</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-device-disconnection-problems-for-windows-users-with-virtualbox/"><u>Resolving Device Disconnection Problems for Windows Users with VirtualBox</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-revolutionary-recording-techniques-for-ipads/"><u>2024 Approved  Revolutionary Recording Techniques for iPads</u></a></li>
<li><a href="https://windows11.techidaily.com/fasten-up-your-windows-devices-with-top-fixes-for-slow-web-linkage/"><u>Fasten Up Your Windows Devices with Top Fixes for Slow Web Linkage</u></a></li>
<li><a href="https://review-topics.techidaily.com/identify-missing-your-hardware-drivers-with-windows-device-manager-on-windows-10-and-7-by-drivereasy-guide/"><u>Identify missing your hardware drivers with Windows Device Manager on Windows 10 & 7</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-strategy-become-system-admin-now/"><u>Swift Strategy: Become System Admin Now</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-regain-missing-router-interface-on-pc/"><u>How to Regain Missing Router Interface on PC</u></a></li>
<li><a href="https://unlock-android.techidaily.com/10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-honor-magic-6-by-drfone-android/"><u>10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On Honor Magic 6</u></a></li>
<li><a href="https://windows11.techidaily.com/significance-of-redistributing-visual-cplusplus/"><u>Significance of Redistributing Visual C++</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-the-complete-process-of-logging-google-voice-calls/"><u>In 2024, The Complete Process of Logging Google Voice Calls</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-power-of-shortcuts-for-app-size-adjustment-on-windows-11/"><u>Unlocking the Power of Shortcuts for App Size Adjustment on Windows 11</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-clandestine-glimpse-at-fb-flashbacks/"><u>[Updated] Clandestine Glimpse at Fb Flashbacks</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-rectify-non-existent-lock-screen-countdown/"><u>How to Rectify Non-Existent Lock Screen Countdown</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-pc-performance-top-6-monitoring-apps-recommended-for-win/"><u>Optimize PC Performance: Top 6 Monitoring Apps Recommended for Win</u></a></li>
<li><a href="https://extra-tips.techidaily.com/elevate-the-listening-experience-with-garageband-edits/"><u>Elevate the Listening Experience with GarageBand Edits</u></a></li>
<li><a href="https://extra-resources.techidaily.com/streamline-your-windows-11-photo-videos/"><u>Streamline Your Windows 11 Photo Videos</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-whatsapp-status-creator-best-apps-to-try/"><u>Updated WhatsApp Status Creator Best Apps to Try</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-open-installation-packages-resolving-windows-errors/"><u>Guide to Open Installation Packages: Resolving Windows Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/the-6-best-to-do-list-apps-for-windows-10-and-11/"><u>The 6 Best To-Do List Apps for Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-your-computers-clock-display-with-animated-screensaver-apps/"><u>Transform Your Computer's Clock Display with Animated Screensaver Apps</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-the-top-5-android-apps-that-use-fingerprint-sensor-to-lock-your-apps-on-vivo-v27e-by-drfone-android/"><u>In 2024, The Top 5 Android Apps That Use Fingerprint Sensor to Lock Your Apps On Vivo V27e</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-for-frozen-downloads-restart-tracker-resume-progress/"><u>Quick-Fix for Frozen Downloads: Restart Tracker, Resume Progress</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-premium-home-cinema-picks-for-best-3d-blu-ray-systems/"><u>[New] Premium Home Cinema  Picks for Best 3D Blu-Ray Systems</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-fixing-obscured-content-on-youtube-platform/"><u>[New] Fixing Obscured Content on YouTube Platform</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-elevating-your-content-strategy-youtube-keywords-explained/"><u>[Updated] In 2024, Elevating Your Content Strategy  YouTube Keywords Explained</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-the-magnificent-art-of-pokemon-go-streaming-on-samsung-galaxy-xcover-6-pro-tactical-edition-drfone-by-drfone-virtual-android/"><u>In 2024, The Magnificent Art of Pokemon Go Streaming On Samsung Galaxy XCover 6 Pro Tactical Edition? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/remedial-tactics-for-loading-errors-in-discord-software/"><u>Remedial Tactics for Loading Errors in Discord Software</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-windows-repeatedly-entering-cmos-settings/"><u>Solutions for Windows Repeatedly Entering CMOS Settings</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/audio-engineering-wizardry-mastering-the-art-of-vocal-elimination-for-2024/"><u>Audio Engineering Wizardry Mastering the Art of Vocal Elimination for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-resolve-windows-11s-update-error-0x800f0922/"><u>How to Resolve Windows 11'S Update Error 0X800f0922</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-controlling-file-compression-in-windows-11/"><u>Strategies for Controlling File Compression in Windows 11</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/eradicating-refresh-glitches-in-windows-10/"><u>Eradicating Refresh Glitches in Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-ais-pitfalls-the-risks-of-chatbots-in-windows-keys/"><u>Navigating AI's Pitfalls: The Risks of Chatbots in Windows Keys</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-expert-strategies-for-audio-smoothness/"><u>[Updated] Expert Strategies for Audio Smoothness</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-in-2024-stream-selection-simplified-top-10-actionable-tips/"><u>[New] In 2024, Stream Selection Simplified  Top 10 Actionable Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/stopping-google-chrome-alerts-tips-for-windows/"><u>Stopping Google Chrome Alerts: Tips for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-to-bypass-admin-access-denied-message-on-pc/"><u>Tactics to Bypass 'Admin Access Denied' Message on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/the-phasing-out-of-microsofts-windows-xp-7-and-81-lifeline/"><u>The Phasing Out of Microsoft's Windows XP, 7 & 8.1 Lifeline</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-your-windows-11-9-solutions-for-lost-bluetooth/"><u>Reviving Your Windows 11: 9 Solutions for Lost Bluetooth</u></a></li>
</ul></div>
