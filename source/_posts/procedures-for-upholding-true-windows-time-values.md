---
title: Procedures for Upholding True Windows Time Values
date: 2024-07-11T21:49:09.005Z
updated: 2024-07-12T21:49:09.005Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Procedures for Upholding True Windows Time Values
excerpt: This Article Describes Procedures for Upholding True Windows Time Values
keywords: WindowTimeSync,TrueTimeUptime,RealWindowsTiming,VerifiedTimeWindows,AccurateWIndowsClock,TruthfulWindowsDateTime,ValidatedWindowsTimeSync
thumbnail: https://thmb.techidaily.com/a0961ee471b397828689bb0499e11bd310468db6e686996103528a8e584f7f95.jpg
---

## Procedures for Upholding True Windows Time Values

 You’re using your Windows device and notice something strange in the date and time settings. Someone has changed the settings without your knowledge or permission. This makes it difficult to stay on schedule with tasks and activities. In this guide, we’ll show how to stop anonymous users from changing date and time settings on Windows computers.

## How To Prevent Users From Changing the Date and Time on Windows

 There are two ways to prevent users from changing Windows date and time. The first is to use Group Policy Editor, a system administration tool designed to control computer behavior in an organization. While the second way is to use Registry Editor, which allows you to modify Windows registry settings.

 For both methods, you need administrative access to the computer to change it. Once you’ve made the changes, nobody can alter the date and time settings. Let’s look at each method in more detail.

## 1\. Use the Group Policy Editor

 If your computer is part of an organization and users often change the date and time, use Group Policy Editor to stop it. This will prevent those with limited access to the computer from altering the date and time. However, this method only works for Windows Pro, Enterprise, or Education Editions.

 So, if you have Windows Home Edition, this won’t work. In that case, you must first [activate the Group Policy Editor for Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). If it seems complicated, skip it and try the next solution instead.

 Follow these steps to prevent users from changing the date and time:

1. Press **Win + R** on your keyboard to open the Run window.
2. Type **gpedit.msc** in the text box and press Enter. This will open the Group Policy Editor window.
3. On the left side of the window, navigate to the following path:  
Computer Configuration > Administrative Templates > System > Locale Services
4. In the right-side pane, double-click on **Disallow user override of locale settings**.  
![Disallow user override of locale settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/disallow-user-override-of-locale-settings.jpg)
5. In the pop-up window, check the **Enabled** radio button.
6. Then click **Apply** \> **OK** to save the changes.

 This will block anyone from changing the date and time settings on your computer. However, if you have administrative access to the computer, you can still alter the settings.

 If you want to revert to the default settings later, open Group Policy Editor again and change the value of Disallow user override of locale settings back to Not Configured or Disabled. This way, users can change the time and date again.

## 2\. Tweak the Registry Editor

 If you’re using Windows Home Edition or have disabled the Group Policy Editor, use the Registry Editor to protect date and time settings. This method is more advanced and has a higher risk of system damage.

 In that case, [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it. Doing so will restore settings if something goes wrong.

 Follow these steps to stop users from changing the time and date via the registry:

1. [Open the Run command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **regedit** in the field and press Enter. This will [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. In the Registry Editor window, navigate to the following path:  
HKEY_CURRENT_USER\Software\Policies\Microsoft\Control Panel\International\
4. If the International folder doesn’t exist, create one. To do that, right-click on Control Panel and select **New** \> **Key**. Name it **International**.
5. Then right-click on **International** and select New > DWORD (32-bit) Value.
6. Name the newly created value **PreventUserOverrides**.
7. Double-click on the **PreventUserOverrides** DWORD value.  
![Use Registry Editor to Prevent Users From Chaning date and time settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/use-registry-editor-to-prevent-users-from-chaning-date-and-time-settings.jpg)
8. In the pop-up window, change the Value data to **1** and click **OK**.

 Once you’ve made the changes, close the Registry Editor window and restart your computer.

 To undo this restriction, delete the **PreventUserOverrides** DWORD value from the registry or change the value to **0**. Doing so will enable users to change the time and date again.

## Stop Windows Time and Date Changes

 Now stop unauthorized users from changing the date and time settings on your Windows computer. This keeps your tasks and activities on track. If necessary, you can always undo this restriction.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/bypass-windows-folder-permission-snags-swiftly/"><u>Bypass Windows Folder Permission Snags Swiftly</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/videopad-video-editor-2023-a-comprehensive-review-and-recommendation/"><u>Videopad Video Editor 2023 A Comprehensive Review and Recommendation</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-efficient-edits-encapsulating-powerpoint-talks/"><u>[Updated] In 2024, Efficient Edits  Encapsulating PowerPoint Talks</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-tecno-phantom-v-flip-to-other-android-devices-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Tecno Phantom V Flip to Other Android Devices Devices? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-android-app-not-installed-error-on-realme-narzo-n55-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android App Not Installed Error on Realme Narzo N55 Quickly? | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/how-to-connect-instagram-to-facebook/"><u>How to Connect Instagram to Facebook</u></a></li>
<li><a href="https://howto.techidaily.com/my-videos-arent-playing-on-samsung-galaxy-s23-fe-what-can-i-do-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>My Videos Arent Playing on Samsung Galaxy S23 FE – What Can I Do? | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/ace-the-hd-audiovideo-experience-in-android-for-2024/"><u>Ace the HD Audio/Video Experience in Android for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-streamlining-audio-capture-in-windows-11/"><u>2024 Approved  Streamlining Audio Capture in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-blue-screen-blues-fixing-error-740-on-winos/"><u>Avoiding Blue Screen Blues: Fixing Error 740 on WINOS</u></a></li>
<li><a href="https://windows11.techidaily.com/booting-up-windows-sound-service-quick-fix-steps/"><u>Booting Up Windows Sound Service: Quick Fix Steps</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-perfecting-your-valorant-thumbnails-a-comprehensive-tutorial/"><u>In 2024, Perfecting Your Valorant Thumbnails  A Comprehensive Tutorial</u></a></li>
<li><a href="https://windows11.techidaily.com/beginner-friendly-steps-to-install-chrome-on-windows-11/"><u>Beginner-Friendly Steps to Install Chrome on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/are-the-icons-on-your-windows-desktop-overlapping-here-are-some-solutions/"><u>Are the Icons on Your Windows Desktop Overlapping? Here Are Some Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/6-expert-windows-programs-for-video-editors/"><u>6 Expert Windows Programs for Video Editors</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-performance-of-docker-in-wsl-2-on-windows-devices/"><u>Boosting Performance of Docker in WSL 2 on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/avoidance-of-windows-updates-interruptions/"><u>Avoidance of Windows Updates Interruptions</u></a></li>
<li><a href="https://windows11.techidaily.com/1719351366052-breathe-new-life-into-your-win11-printer-with-these-tips/"><u>Breathe New Life Into Your Win11 Printer with These Tips!</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-efficiency-with-top-practices-for-wsl-2-usage-on-pcs/"><u>Boost Efficiency with Top Practices for WSL 2 Usage on PCs</u></a></li>
<li><a href="https://games-able.techidaily.com/the-ultimate-game-boy-advance-emulator-showdown-on-ios/"><u>The Ultimate Game Boy Advance Emulator Showdown on iOS</u></a></li>
<li><a href="https://windows11.techidaily.com/add-compatibility-tool-to-windows-quick-access/"><u>Add Compatibility Tool to Windows' Quick Access</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-limited-it-admin-power-in-security-warning/"><u>Bypassing 'Limited IT Admin Power' In Security Warning</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-vpna-to-fake-gps-location-on-samsung-galaxy-s23-fe-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use VPNa to Fake GPS Location On Samsung Galaxy S23 FE | Dr.fone</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-2024-approved-video-stabilization-magic-transforming-shaky-clips-in-adobe-premiere-pro/"><u>Updated 2024 Approved Video Stabilization Magic Transforming Shaky Clips in Adobe Premiere Pro</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-apple-iphone-14-pro-without-passcode-by-drfone-ios/"><u>How to Unlock Apple iPhone 14 Pro Without Passcode?</u></a></li>
<li><a href="https://windows11.techidaily.com/batch-processing-excellence-using-task-scheduler/"><u>Batch Processing Excellence Using Task Scheduler</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-the-sluggishness-of-windows-discord-features/"><u>Addressing the Sluggishness of Windows Discord Features</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/top-5-cozy-winter-scenes-for-video-aesthetics/"><u>Top 5 Cozy Winter Scenes for Video Aesthetics</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-become-a-snapchat-pro-securing-and-sharing-screen-videos/"><u>[New] 2024 Approved  Become a Snapchat Pro  Securing & Sharing Screen Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-the-incorrect-identifier-message-in-windows-11/"><u>Addressing the 'Incorrect Identifier' Message in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-restoration-features-your-pathway-through-windows-11/"><u>Activating Restoration Features: Your Pathway Through Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-services-that-dont-launch/"><u>Addressing Windows Services That Don't Launch</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-qt-plugin-initialization-failure-error/"><u>Addressing Qt Plugin Initialization Failure Error</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/harnessing-metaverse-promotion-power-for-2024/"><u>Harnessing Metaverse Promotion Power for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-professional-drones-pro-level-editing-software-showdown/"><u>[New] Professional Drones, Pro-Level Editing Software Showdown</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/2024-approved-pro-level-video-editing-on-mac-adobe-premiere-pro/"><u>2024 Approved Pro-Level Video Editing on Mac Adobe Premiere Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/apexs-windows-woes-strategies-to-clear-no-server-error-(156-chars/"><u>Apex's Windows Woes: Strategies to Clear No-Server Error (<156 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-disruption-fixing-windows-minecraft-errors/"><u>Avoid Disruption - Fixing Windows Minecraft Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/beneath-radar-outstanding-windows-11-customization/"><u>Beneath Radar: Outstanding Windows 11 Customization</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-vscode-shutdown-troubles-in-new-os/"><u>Avoiding VSCode Shutdown Troubles in New OS</u></a></li>
<li><a href="https://windows11.techidaily.com/changing-default-user-directory-labels-windows-11/"><u>Changing Default User Directory Labels (Windows 11)</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-enhance-stories-interaction-with-custom-queries-design-for-2024/"><u>[New] Enhance Stories Interaction with Custom Queries Design for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-top-innovators-defining-next-gen-vr-experiences/"><u>2024 Approved  Top Innovators Defining Next-Gen VR Experiences</u></a></li>
<li><a href="https://windows11.techidaily.com/classic-expanse-a-win-11-explorer-journey/"><u>Classic Expanse: A Win 11 Explorer Journey</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-synchronizing-sonic-elements-controlling-audio-duration-and-tonality-in-adobe-rush-for-2024/"><u>New Synchronizing Sonic Elements Controlling Audio Duration and Tonality in Adobe Rush for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/a-list-of-frustrations-with-windows-11/"><u>A List of Frustrations with Windows 11</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-in-2024-minecraft-banner-templates-get-them-here/"><u>[Updated] In 2024, Minecraft Banner Templates  Get Them Here</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-pro-tips-for-pioneering-board-use-in-webinars-android-iphone-and-windows-users-for-2024/"><u>[New] Pro Tips for Pioneering Board Use in Webinars  Android, iPhone & Windows Users for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/venture-into-the-best-sites-for-innovative-text-manipulation-tools/"><u>Venture Into the Best Sites for Innovative Text Manipulation Tools</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-ravenhill-resonance-essential-websites-to-download-hearing-heroes-tones/"><u>[Updated] Ravenhill Resonance  Essential Websites to Download Hearing Heroes' Tones</u></a></li>
<li><a href="https://windows11.techidaily.com/captivating-yuletide-atmosphere-in-window-artistry/"><u>Captivating Yuletide Atmosphere in Window Artistry</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-individuality-at-your-fingertips-setting-your-own-tones-for-android-devices/"><u>[New] Individuality at Your Fingertips  Setting Your Own Tones for Android Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/5-key-adjustments-for-a-mac-look-in-windows-environment/"><u>5 Key Adjustments for a Mac Look in Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/amplify-tray-ui-add-scrolllock-and-number-keys-iconos/"><u>Amplify Tray UI: Add ScrollLock and Number Keys Iconos</u></a></li>
<li><a href="https://howto.techidaily.com/motorola-moto-g73-5g-not-receiving-texts-10-hassle-free-solutions-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Motorola Moto G73 5G Not Receiving Texts? 10 Hassle-Free Solutions Here | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/1719366391353-keyboards-on-the-ropes-reclaim-your-arrows/"><u>Keyboards on the Ropes? Reclaim Your Arrows!</u></a></li>
<li><a href="https://windows11.techidaily.com/a-history-of-the-windows-taskbar-from-1985-to-2023/"><u>A History of the Windows Taskbar From 1985 to 2023</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-focus-on-yourself-insta-stylezoom-techniques-explained/"><u>[New] 2024 Approved  Focus on Yourself  Insta Style—Zoom Techniques Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/altering-windows-files-date-creation-and-modification-adjustments/"><u>Altering Windows Files: Date Creation & Modification Adjustments</u></a></li>
<li><a href="https://windows11.techidaily.com/choosing-your-win-software-downloader-choco-versus-wslm/"><u>Choosing Your Win Software Downloader: Choco Versus WSLM</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-windows-with-top-2023-ms-store-winners/"><u>Boost Windows with Top 2023 MS Store Winners</u></a></li>
<li><a href="https://windows11.techidaily.com/ace-your-win-11-games-with-these-best-fps-tools/"><u>Ace Your Win 11 Games with These Best FPS Tools</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-2023s-top-contenders-gopro-hero5-vs-yi-4k-action-cameras-for-2024/"><u>[New] 2023'S Top Contenders  GoPro Hero5 Vs. Yi 4K Action Cameras for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-ranking-the-top-8-innovators-video-platforms-with-blistering-speed/"><u>[New] Ranking the Top 8 Innovators  Video Platforms with Blistering Speed</u></a></li>
</ul></div>
