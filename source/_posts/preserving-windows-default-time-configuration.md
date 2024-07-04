---
title: Preserving Windows' Default Time Configuration
date: 2024-06-25T12:41:32.710Z
updated: 2024-06-26T12:41:32.710Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Preserving Windows' Default Time Configuration
excerpt: This Article Describes Preserving Windows' Default Time Configuration
keywords: Save Windows Time Settings,Keep Windows Clock,Retain Default Windows Time,Preserve Win Time Defaults,Maintain Windows Date & Time,Unaltered Windows Time Setting,Uphold Standard Windows Time
thumbnail: https://thmb.techidaily.com/1b4d426689bd18514a96cb95968cc5a755b1ea7a22bc00e9feef5b8e8bfa78d1.jpg
---

## Preserving Windows' Default Time Configuration

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/monitoring-login-trials-detecting-successfulfailed-windows-access/"><u>Monitoring Login Trials: Detecting Successful/Failed Windows Access</u></a></li>
<li><a href="https://windows11.techidaily.com/resetting-grammarly-settings-in-windows/"><u>Resetting Grammarly Settings in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/winrars-corrected-compression-overcoming-sum-errors/"><u>WinRAR's Corrected Compression: Overcoming Sum Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-reimagined-make-it-mirror-macos-style-in-5-easy-ways/"><u>Windows Reimagined: Make It Mirror macOS Style in 5 Easy Ways</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-correct-steam-ui-dll-not-loaded-error/"><u>Steps to Correct Steam UI DLL Not Loaded Error</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-bsod-understanding-and-fixing-blue-screen/"><u>Win11 BSOD: Understanding & Fixing Blue Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-continuous-credential-entry-alerts-in-os/"><u>Overcoming Continuous Credential Entry Alerts in OS</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-the-widget-toolbar-functionality-in-win11/"><u>Understanding the Widget Toolbar Functionality in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-windows-cars-keyboard-magic-boosts-speed/"><u>Top 5 Windows Cars: Keyboard Magic Boosts Speed</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-comprehensive-analysis-of-video-editing-powerdirector-pro-suite-review/"><u>2024 Approved  Comprehensive Analysis of Video Editing  PowerDirector Pro Suite Review</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-splitstream-analysis-top-video-camera-champion/"><u>2024 Approved  SplitStream Analysis  Top Video Camera Champion?</u></a></li>
<li><a href="https://vp-tips.techidaily.com/the-animators-dream-tools-premium-choices-for-3d-mastery/"><u>The Animator’s Dream Tools  Premium Choices for 3D Mastery</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-immerse-slides-with-audio-harmony/"><u>[New] Immerse Slides with Audio Harmony</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-from-playback-to-printout-top-five-methods-of-documenting-minecraft-on-a-mac-for-2024/"><u>[Updated] From Playback to Printout  Top Five Methods of Documenting Minecraft on a Mac for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/from-zero-to-hero-learning-the-art-of-youtube-content-for-2024/"><u>From Zero to Hero  Learning the Art of YouTube Content for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-voice-to-word-made-easy-discovering-the-best-free-android-and-ios-transcription-tools/"><u>Updated 2024 Approved Voice to Word Made Easy Discovering the Best Free Android and iOS Transcription Tools</u></a></li>
<li><a href="https://some-approaches.techidaily.com/timeless-stop-motion-gems-in-the-top-15-for-2024/"><u>Timeless Stop-Motion Gems in the Top 15 for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-full-insight-gecata-game-logging-system-reviewed/"><u>2024 Approved  Full Insight  Gecata Game Logging System Reviewed</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-overcoming-sync-issues-ensuring-smooth-video-sharing-on-mobile-messengers/"><u>[Updated] In 2024, Overcoming Sync Issues  Ensuring Smooth Video Sharing on Mobile Messengers</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>