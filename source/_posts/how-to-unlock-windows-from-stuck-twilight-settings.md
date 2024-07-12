---
title: How to Unlock Windows From Stuck Twilight Settings
date: 2024-07-11T22:02:28.331Z
updated: 2024-07-12T22:02:28.331Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Unlock Windows From Stuck Twilight Settings
excerpt: This Article Describes How to Unlock Windows From Stuck Twilight Settings
keywords: Lock Windows Remediation,Override Windows Freeze,Twilight Mode Fix,Restore Windows Start,Unlock Frozen Display,Reset Windows Settings,Bypass Screen Locking
thumbnail: https://thmb.techidaily.com/77611f2e0e7b4b101c92af3b172df9c62d2c1071591d3411a278cc0334c16e37.jpg
---

## How to Unlock Windows From Stuck Twilight Settings

 You might often enable dark mode on Windows to reduce eye strain, but it’s quite frustrating when you suddenly can’t switch from dark to normal mode again

 If you’re experiencing this issue, then we’ve got solutions for you. In this article, we’ll explore the five ways to fix your Windows PC when it’s stuck in dark mode.

## 1\. Configure Settings in the Local Group Policy Editor

 The Local Group Policy Editor (LGPE) is a tool that allows you to configure various settings on your device. Interestingly, you can also use the LGPE to troubleshoot various system issues.

 Now, let’s check out how this tool can help you when your device is stuck in dark mode:

1. Press **Win + R** to open the Run command dialog box.
2. Type **gpedit.msc** and press **Enter** to open the LGPE.
3. Navigate to **User Configuration > Administrative Templates > Control Panel > Personalization**.
4. Double-click on the **Prevent changing theme** option on the right-hand side pane.

![Using the Local Group Policy Editor to Prevent Others From Changing the Desktop Theme](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Using-the-Local-Group-Policy-Editor-to-Prevent-Others-From-Changing-the-Desktop-Theme.jpg)

 Next, select the **Not Configured** or **Disabled** option on the pop-up screen. From there, click **Apply** and then click **OK** to disable the **Prevent changing theme** option.

 If the issue persists, navigate to the **Personalization** folder as per the previous steps and then disable the following options:

* Prevent changing color and appearance
* Prevent changing desktop background
* Prevent changing screen saver
* Prevent changing color scheme
* Load a specific theme
* Force specific screen saver
* Force a specific visual style file or force Windows Classic

 Finally, restart your device to save these changes.

## 2\. Tweak the Contrast Theme Settings

 You might be stuck in dark mode simply because you’ve enabled the "High contrast" option on Windows. So, let’s check out how you can resolve this problem:

1. Press **Win + I** to open the system settings.
2. Select **Ease of Access** from the options.
3. Click **High contrast** on the left.
4. **Turn off** the button below the **Turn on high contrast** option and check if this resolves the issue.

![Turning off the button below the Turn on high contrast option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/turning-off-the-button-below-the-turn-on-high-contrast-option.jpg)

## 3\. Edit the Relevant Registry Files

 Editing some Registry files could also help you tackle the issue at hand. But to be on the safe side, [back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first before you proceed. This tool is sensitive and could wreak havoc on your PC if you tweak the wrong keys.

 Now, here’s how to fix the “dark mode” problem using the Registry Editor:

1. Press **Win + R** to open the Run command dialog box.
2. Type **regedit** and press **Enter** to open the Registry Editor. Alternatively, check out [the various ways to access the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. Type the following command into the address bar:

HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Themes\Personalize

 Next, double-click on the **AppsUseLightTheme** value on the right-hand side pane.

![Clicking the AppsUseLightTheme value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/clicking-the-appsuselighttheme-value.jpg)

 Type **0** in the **Value data** box and then click **OK**.

 From there, set the **Value data** as **0** for the **ColorPrevalence**, **EnableTransparency**, and **SystemUsesLightTheme** values. When you finish, restart your device and check if this resolves the problem.

## 4\. Disable Third-Party Apps Like the Auto Dark Mode Tool

 Apps like the [Microsoft Auto Dark Mode](https://apps.microsoft.com/store/detail/auto-dark-mode/XP8JK4HZBVF435) tool switch between dark and light modes at scheduled times. If you’ve configured its settings unknowingly, then it might end up enabling the dark mode feature unexpectedly.

 To resolve the issue, the best solution would be to disable this tool (and any other similar third-party app). Alternatively, you can configure the tool’s settings to your liking. That way, your device will only go into dark mode when you want it to.

## 5\. Perform Some Generic Windows-Based Fixes

 Still struggling to resolve the issue? Perhaps the error is caused by corrupted system files. In this case, the best solution is to [repair corrupted Windows files using its built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

 And if all else fails, [update your Windows device](https://www.makeuseof.com/update-windows-manually/) and see if that helps.

## No More Getting Stuck in Dark Mode

 There’s no denying that the Windows dark mode option is quite convenient. However, being unable to switch from dark to normal mode is quite unpleasant. If your device is stuck in dark mode, try any of the solutions we’ve covered.


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
<li><a href="https://on-screen-recording.techidaily.com/the-top-tiers-of-treasured-valheim-trees/"><u>The Top Tiers of Treasured Valheim Trees</u></a></li>
<li><a href="https://windows11.techidaily.com/hidden-behind-pretense-apps-slowdown-your-modern-windows/"><u>Hidden Behind Pretense: Apps Slowdown Your Modern Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-registry-shortcomings-solutions/"><u>Unveiling Windows Registry Shortcomings: Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-restore-your-desktop-icon-positions-on-windows/"><u>How to Restore Your Desktop Icon Positions on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-optimal-performance-self-updating-updated-amd-driver/"><u>Achieve Optimal Performance: Self-Updating, Updated AMD Driver</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-power-settings-for-cpu-state-insights/"><u>Unlocking Power Settings for CPU State Insights</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/in-2024-camtasia-vs-captivate-which-to-choose/"><u>In 2024, Camtasia Vs Captivate - Which to Choose?</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-2023-revised-insights-on-samsungs-ubd-k850u/"><u>[Updated] 2023 Revised Insights on Samsung's UBD-K850U</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-from-cluttered-to-clear-a-beginners-guide-to-freeing-up-space-for-fcpx-for-2024/"><u>New From Cluttered to Clear A Beginners Guide to Freeing Up Space for FCPX for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-remove-or-bypass-knox-enrollment-service-on-nokia-by-drfone-android/"><u>How To Remove or Bypass Knox Enrollment Service On Nokia</u></a></li>
<li><a href="https://windows11.techidaily.com/7-tricks-for-rejuvenating-non-responsive-windows-service-explorer/"><u>7 Tricks for Rejuvenating Non-Responsive Windows Service Explorer</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-beginners-guide-adding-text-overlays-on-youtube/"><u>[New] In 2024, Beginner's Guide  Adding Text Overlays on YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/future-screens-innovating-beyond-windows-11/"><u>Future Screens: Innovating Beyond Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/automatic-windows-tweak-transition-to-latest-amd-driver/"><u>Automatic Windows Tweak: Transition to Latest AMD Driver</u></a></li>
<li><a href="https://windows11.techidaily.com/curate-your-own-win11-screen-saver/"><u>Curate Your Own Win11 Screen Saver</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-self-designed-instagram-ringtone-creation-steps/"><u>In 2024, Self-Designed Instagram Ringtone Creation Steps</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-seamless-integration-of-slideshows-into-facebook-layouts/"><u>[Updated] 2024 Approved  Seamless Integration of Slideshows Into Facebook Layouts</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-top-explainer-video-tools-a-comprehensive-review/"><u>New In 2024, Top Explainer Video Tools A Comprehensive Review</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-20-must-have-graduation-songs-for-2024/"><u>New 20 Must-Have Graduation Songs for 2024</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-android-hd-viewing-your-10-app-must-have-guide-for-2024/"><u>[New] Android Hd Viewing  Your 10-App Must-Have Guide for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/ideal-mobile-software-for-windows-pc-owners-on-android/"><u>Ideal Mobile Software for Windows PC Owners on Android</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-global-lens-local-tales-how-to-transform-your-travel-experiences-into-content/"><u>2024 Approved  Global Lens, Local Tales  How to Transform Your Travel Experiences Into Content</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-the-power-of-background-blur-a-windows-11-photo-guide/"><u>Discover the Power of Background Blur: A Windows 11 Photo Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/why-is-nvidia-control-panel-inaccessible-on-win11/"><u>Why Is Nvidia Control Panel Inaccessible on Win11?</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-expert-strategies-to-maximize-income-with-video-ads-on-youtube/"><u>[New] In 2024, Expert Strategies to Maximize Income with Video Ads on Youtube</u></a></li>
<li><a href="https://location-fake.techidaily.com/3utools-virtual-location-not-working-on-apple-iphone-15-plus-fix-now-drfone-by-drfone-virtual-ios/"><u>3uTools Virtual Location Not Working On Apple iPhone 15 Plus? Fix Now | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/elevating-pics-to-perfection-without-expenditure/"><u>Elevating Pics to Perfection Without Expenditure</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-evolution-unveiling-the-latest-system-updates/"><u>Windows 11'S Evolution: Unveiling the Latest System Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-file-selection-adding-directories-to-context-menu/"><u>Enhancing File Selection: Adding Directories to Context Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-data-handling-navigate-4-steps-to-open-disk-management-in-windows-11/"><u>Effortless Data Handling: Navigate 4 Steps to Open Disk Management in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/circumventing-windows-security-controlled-by-domain-admins/"><u>Circumventing Windows Security Controlled by Domain Admins</u></a></li>
<li><a href="https://windows11.techidaily.com/correction-of-inaccessible-device-path-issue-in-win/"><u>Correction of Inaccessible Device Path Issue in Win</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-to-vanquish-your-pcs-win11-blue-screen/"><u>Expert Tips to Vanquish Your PC's Win11 Blue Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-solving-win-1011-ad-ds-printer-problems-efficiently/"><u>Guide to Solving Win 10/11 AD DS Printer Problems Efficiently</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-user-interface-fastest-uninstall-actions-with-context/"><u>Elevate User Interface: Fastest Uninstall Actions with Context</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-what-makes-a-great-video-to-audio-converter-key-features-to-look-for-for-2024/"><u>New What Makes a Great Video to Audio Converter? Key Features to Look For for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-rejuvenate-a-dysfunctional-search-bar-in-windows-11/"><u>Guide to Rejuvenate a Dysfunctional Search Bar in Windows 11</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/snapchats-visual-language-mastering-the-art-of-gifting-with-gifs-for-2024/"><u>Snapchat's Visual Language  Mastering the Art of Gifting with Gifs for 2024</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-google-frp-lock-from-realme-c33-2023-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock from Realme C33 2023 Devices</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-revel-in-pubgs-simplified-voice-transformation-methods/"><u>[New] Revel in PUBG's Simplified Voice Transformation Methods</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-unlocking-the-power-of-smart-lock-a-beginners-guide-for-xiaomi-redmi-12-5g-users-by-drfone-android/"><u>In 2024, Unlocking the Power of Smart Lock A Beginners Guide for Xiaomi Redmi 12 5G Users</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-direction-and-intensity-in-video-lighting-for-2024/"><u>[Updated] Direction and Intensity in Video Lighting for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-desktop-aesthetics-best-pc-time-saver-apps-listed/"><u>Boost Desktop Aesthetics – Best PC Time Saver Apps Listed</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-teachers-handbook-building-a-successful-youtube-channel-10-must-dos/"><u>In 2024, Teachers' Handbook  Building a Successful YouTube Channel – 10 Must-Dos</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-full-potential-mastering-multiple-screens-in-win11/"><u>Unlock Full Potential: Mastering Multiple Screens in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-overcoming-unidentified-obs-recording-issue-on-win-11/"><u>Decoding and Overcoming Unidentified OBS Recording Issue on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/highlighting-key-windows-processes-for-virus-alerts/"><u>Highlighting Key Windows Processes for Virus Alerts</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-transform-lives-10-cinematic-inspirations/"><u>2024 Approved  Transform Lives  10 Cinematic Inspirations</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-overcome-media-error-input-not-recognized-by-vlc/"><u>How to Overcome Media Error: Input Not Recognized by VLC</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-mastery-in-minimal-spending-finding-instagrams-free-filter-cache/"><u>[New] Mastery in Minimal Spending  Finding Instagram’s Free Filter Cache</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-microsofts-enhancements-in-februarys-win11-patch/"><u>Exploring Microsoft's Enhancements in February's Win11 Patch</u></a></li>
<li><a href="https://windows11.techidaily.com/a-visual-journey-top-7-windows-10-drawing-tools-unveiled/"><u>A Visual Journey: Top 7 Windows 10 Drawing Tools Unveiled</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-maximizing-reach-uploading-twitch-videos-on-youtube/"><u>In 2024, Maximizing Reach  Uploading Twitch Videos on YouTube</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-the-anatomy-of-apple-m1-chip-redefining-tech/"><u>2024 Approved  The Anatomy of Apple M1 Chip, Redefining Tech</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-mastering-the-art-of-audio-detachment-top-software-picks-for-video-files/"><u>In 2024, Mastering the Art of Audio Detachment Top Software Picks for Video Files</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-folders-to-the-context-menu-in-windows-11/"><u>How to Add Folders to the Context Menu in Windows 11</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-step-by-step-methods-for-easy-instagram-video-uploads-from-desktop/"><u>[New] Step-by-Step Methods for Easy Instagram Video Uploads From Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-control-for-apps-and-browsers/"><u>Unveiling Windows Control for Apps & Browsers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-keyboard-commands-to-sharpen-your-3d-skills/"><u>Essential Keyboard Commands to Sharpen Your 3D Skills</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-beat-junkies-essentials-online-cost-free-software/"><u>In 2024, Beat Junkies' Essentials  Online, Cost-Free Software</u></a></li>
</ul></div>
