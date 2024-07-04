---
title: 5 Steps to Reclaim Your Windows' Daylight Look
date: 2024-07-03T11:13:55.432Z
updated: 2024-07-04T11:13:55.432Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 5 Steps to Reclaim Your Windows' Daylight Look
excerpt: This Article Describes 5 Steps to Reclaim Your Windows' Daylight Look
keywords: Windows Restore,Brighten Windows,Fresh Window Gloss,Revive Windows,Lighten Up Windows,Shine Windows Clearly,Refresh Windows Appearance
thumbnail: https://thmb.techidaily.com/63dab56e4ce75698d2495662d618f28dc10e8ea5781384709b703dd0571829f2.jpg
---

## 5 Steps to Reclaim Your Windows' Daylight Look

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
<li><a href="https://windows11.techidaily.com/enhance-windows-videography-leverage-advanced-distributive-transcoding-by-tdarr/"><u>Enhance Window's Videography: Leverage Advanced Distributive Transcoding by Tdarr</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-system-interaction-in-command-prompt/"><u>Elevate Your System Interaction in Command Prompt</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-this-file-is-alone-error-on-pcs/"><u>Overcoming This File Is Alone Error on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/time-is-money-restoring-windows-server-time-quickly/"><u>Time Is Money: Restoring Windows Server Time Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/1719297453407-mastery-overprint-how-to-reactivate-the-missing-windows-functionality/"><u>Mastery Overprint: How to Reactivate the Missing Windows Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-windows-default-no-spotify-autoplay/"><u>Avoid Windows Default: No Spotify Autoplay</u></a></li>
<li><a href="https://windows11.techidaily.com/what-is-ftdibussys-on-windows-and-why-does-it-disable-memory-integrity/"><u>What Is ftdibus.sys on Windows and Why Does It Disable Memory Integrity?</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprerant-users-resourceful-approach-to-processes-and-themes-in-windows-11/"><u>A Compreran't User's Resourceful Approach to Processes and Themes in Windows 11</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-revive-your-bricked-samsung-galaxy-a34-5g-in-minutes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Revive Your Bricked Samsung Galaxy A34 5G in Minutes | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/audio-archiving-pc-noises-and-dialogue-storage-for-2024/"><u>Audio Archiving  PC Noises & Dialogue Storage for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-compiling-top-notch-video-grabbers-for-win11-devices/"><u>[New] Compiling Top-Notch Video Grabbers for Win11 Devices</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-become-a-discord-conversation-maestro-expert-pinning-tips/"><u>2024 Approved  Become a Discord Conversation Maestro  Expert Pinning Tips</u></a></li>
<li><a href="https://extra-resources.techidaily.com/enhancing-tiktok-visuals-through-zoom-mastery/"><u>Enhancing TikTok Visuals Through Zoom Mastery</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/speed-it-up-or-slow-down-the-netflix-guide-for-2024/"><u>Speed It Up or Slow Down  The Netflix Guide for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-the-ultimate-guide-to-navigating-steam-with-switch-pro/"><u>[New] 2024 Approved  The Ultimate Guide to Navigating Steam with Switch Pro</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-compressor-in-fcpx-expert-techniques-for-professional-results-for-2024/"><u>Updated Compressor in FCPX Expert Techniques for Professional Results for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-farm-fun-quest-the-leading-10-farm-themed-gaming-titles/"><u>In 2024, Farm Fun Quest  The Leading 10 Farm-Themed Gaming Titles</u></a></li>
</ul></div>
