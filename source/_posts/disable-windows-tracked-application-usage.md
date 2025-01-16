---
title: Disable Windows' Tracked Application Usage
date: 2025-01-10T18:03:13.991Z
updated: 2025-01-16T10:52:47.472Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Disable Windows' Tracked Application Usage
excerpt: This Article Describes Disable Windows' Tracked Application Usage
keywords: Turn Off App Usage Tracker,Stop Windows Tracking Apps,End Windows App Data Logging,Disable Tracking in Windows,Block App Usage Monitoring,Remove Windows Application Watcher,Halt Windows Data Collection
thumbnail: https://thmb.techidaily.com/85034a62a15df819e619fec4e6d0909e5ab4845fbca98b126bdfe343d56fc596.jpg
---

## Disable Windows' Tracked Application Usage

 Windows records and monitors how often you use particular applications. While this may enhance productivity, it does also raise privacy concerns.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.

## 1\. How to Disable App Launch Tracking Through Windows Settings

 To disable app launch tracking, open the Start menu and type **Settings** in the search bar. Select the **Settings** option in the search results. In the left-side menu, click the **Privacy & security** tab. Then click **General** under the Windows permissions section.

 On the next page, locate **Let Windows improve Start and search results by tracking app launches** and toggle it off.

![Disable App Launch Tracking through Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-through-windows-settings.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JlX-G8rBs1w?si=iIhUoWAq5x3YK9rA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After making the changes, Windows will stop tracking and recording your app launches.

 If you ever need to re-enable the feature, repeat the same steps and toggle the switch back on. This will enable Windows to start tracking and recording your app launches.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aqeO4ed766s?si=AWtKHxP4hvQRd_lk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Disable App Launch Tracking Using the Group Policy Editor

 You can also disable app launch tracking using the Group Policy Editor. But this method is only available in the Pro and Enterprise versions.

 If you don't have these Windows versions, [turn on the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) and follow these instructions.

1. Press **Win + R** on your keyboard to open the Run dialog box.
2. Type **gpedit.msc** in the text box and click **OK**.
3. In the Group Policy Editor window, navigate to the following path:  
`User Configuration > Administrative Templates > Windows Components > Edge UI​`
4. Go to the right side of the window and double-click on **Turn off tracking of app usage**.  
![Disable App Launch Tracking using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-using-group-policy-editor.jpg)
5. On the next page, check the **Enabled** box.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gyGoQi7hsZk?si=8OcKcPUj2wSBmVZ1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Click **Apply** \> **OK** to save your changes.

 This way, you can disable app launch tracking using the group policy editor.

 To enable the feature again, follow the same steps and navigate to _User Configuration > Administrative Templates > Windows Components > Edge UI_. Then double-click on **Turn off tracking of app usage** and check the **Not Configured** or **Disabled** option.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/g6xXIR_Uh1A?si=TMXzklPEY50MUM05" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. How to Disable App Launch Tracking Through the Registry Editor

 Registry Editor is another method to disable app launch tracking. The process is tricky as you need to manually modify the registry keys and one wrong move can cause serious problems. So, we suggest you [create a backup of the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it.

 To disable app launch tracking through Registry Editor, do the following:

1. Right-click on Start and select **Run** from the menu list.
2. Type **regedit** in the text field and click **OK**. This will [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. When the UAC window appears, click **Yes** to grant privileges.
4. In the left pane, navigate to the following path:  
`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. If you don't find the Advanced folder, right-click on **Explorer** and select **New** \> **Key**.
6. Name it **Advanced** and press the Enter key.
7. Now, right-click on the **Advanced** folder and choose **New** \> **DWORD (32-bit) Value**.
8. Name it **Start\_TrackProgs** and hit Enter.  
![Disable App Launch Tracking through the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-through-the-registry-editor.jpg)
9. Double-click on the **Start\_TrackProgs** DWORD and set its value to **0**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gMS5pm0SQlQ?si=gasOo6p2agrVlIb7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you're done, close the Registry Editor and restart your computer. Now, Windows won't track or record app launches.

 If you ever want to turn back on app launch tracking, double-click on the **Start\_TrackProgs** DWORD in Registry Editor and set its value to **1**. After that, restart your system for the changes to take effect.

## Windows Won’t Track or Monitor the Apps You Use

 If you don't want to mess with the Registry Editor or Group Policy Editor, use the Settings option to disable app launch tracking. Choose the method you prefer and enjoy a tracking-free experience.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-techniques.techidaily.com/new-immersive-film-experience-photography-plus-music/"><u>[New] Immersive Film Experience Photography + Music</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-streamlining-podcast-feed-creation-techniques-for-2024/"><u>[Updated] Streamlining Podcast Feed Creation Techniques for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-steps-to-address-winerror-0xc0000005-instantly/"><u>Essential Steps to Address WinError 0Xc0000005 Instantly</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-crashes-due-to-0x0000011b-errors/"><u>Fixing Windows Crashes Due to 0X0000011B Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-for-fixing-windows-11-support-tool/"><u>Guidelines for Fixing Windows 11 Support Tool</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-exit-android-factory-mode-on-vivo-y200-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Exit Android Factory Mode On Vivo Y200? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-your-headset-mic-not-working-on-windows/"><u>How to Fix Your Headset Mic Not Working on Windows</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-remove-screen-lock-pin-on-asus-rog-phone-8-pro-like-a-pro-5-easy-ways-by-drfone-android/"><u>How To Remove Screen Lock PIN On Asus ROG Phone 8 Pro Like A Pro 5 Easy Ways</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-reset-gmail-password-on-honor-magic-v2-devices-by-drfone-android/"><u>How to Reset Gmail Password on Honor Magic V2 Devices</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-realme-12plus-5g-drfone-by-drfone-android/"><u>How To Use Allshare Cast To Turn On Screen Mirroring On Realme 12+ 5G | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-lava-blaze-2-5g-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>In 2024, How to Cast Lava Blaze 2 5G Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/key-fixes-for-creative-block-photoshop-stuck-in-windows-1011/"><u>Key Fixes for Creative Block: Photoshop Stuck in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-chrome-integration-in-windows-11-devices/"><u>Quick Guide: Chrome Integration in Windows 11 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-checklist-for-saving-and-recovering-notes/"><u>The Ultimate Checklist for Saving and Recovering Notes</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-cannot-reach-server-error-in-win-10-and-11-for-mb/"><u>Troubleshooting Cannot Reach Server Error in Win 10 & 11 for MB</u></a></li>
<li><a href="https://win-premium.techidaily.com/unraveling-the-reasons-behind-blue-screen-issues-in-windows-insights-by-yl-computing/"><u>Unraveling the Reasons Behind Blue Screen Issues in Windows: Insights by YL Computing</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-2024-approved-unleash-your-creativity-wevideos-intuitive-video-creation-platform/"><u>Updated 2024 Approved Unleash Your Creativity WeVideos Intuitive Video Creation Platform</u></a></li>
</ul></div>

