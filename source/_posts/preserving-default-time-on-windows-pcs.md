---
title: Preserving Default Time on Windows PCs
date: 2024-09-12T20:52:29.172Z
updated: 2024-09-15T18:28:52.958Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Preserving Default Time on Windows PCs
excerpt: This Article Describes Preserving Default Time on Windows PCs
keywords: Save Windows Time Default,Maintain Windows Time Setting,Retain Standard PC Time,Preserve PC Time Standard,Keep Default Time Windows,Hold Default Time Windows PC,Uphold Windows Default Time
thumbnail: https://thmb.techidaily.com/e8596feeaa10b5decf0ac423846001bcbe9ce2de917f68ea7f6f367d6a2483c3.jpg
---

## Preserving Default Time on Windows PCs

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

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123465/16836" target="_top" id="2123465">
  <img src="//a.impactradius-go.com/display-ad/16836-2123465" border="0" alt="https://techidaily.com" width="80" height="31"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123465/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-creating-impact-with-high-converting-youtube-advertising-banners/"><u>[New] In 2024, Creating Impact with High-Converting YouTube Advertising Banners</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-preserving-your-nintendo-switch-experiences-a-guide/"><u>[New] In 2024, Preserving Your Nintendo Switch Experiences A Guide</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-step-by-step-approach-to-crafting-youtube-intros/"><u>[Updated] In 2024, Step-by-Step Approach to Crafting YouTube Intros</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/5-ways-to-restart-oppo-reno-11-pro-5g-without-power-button-drfone-by-drfone-reset-android-reset-android/"><u>5 Ways to Restart Oppo Reno 11 Pro 5G Without Power Button | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-infinix-note-30-5g-drfone-by-drfone-virtual-android/"><u>9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Infinix Note 30 5G | Dr.fone</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/acclaimed-ideas-top-tone-creators-for-apple-phones-for-2024/"><u>Acclaimed Ideas Top Tone Creators for Apple Phones for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-updater-failures-eliminate-xerror-0x80246007-in-win1011/"><u>Fixing Updater Failures: Eliminate XError 0X80246007 in Win10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-phone-link-app-notifications-not-working-on-windows/"><u>How to Fix Phone Link App Notifications Not Working on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-use-imessage-on-windows/"><u>How to Use iMessage on Windows</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-5-best-route-generator-apps-you-should-try-on-poco-m6-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Best Route Generator Apps You Should Try On Poco M6 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-window-10s-captions-with-minimal-trouble/"><u>Mastering Window 10'S Captions with Minimal Trouble</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-must-have-apps-to-maximize-your-windows-workflow/"><u>Top 5 Must-Have Apps to Maximize Your Windows Workflow</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-frozen-epic-launcher-steps-for-win-users/"><u>Troubleshooting Frozen Epic Launcher: Steps for Win Users</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-full-potential-of-windows-startup-options/"><u>Unlocking the Full Potential of Windows Startup Options</u></a></li>
<li><a href="https://screen-capture.techidaily.com/windows-pc-broadcasting-prodigy-mastering-the-art-of-live-tv-recording/"><u>Windows PC Broadcasting Prodigy Mastering the Art of Live TV Recording</u></a></li>
</ul></div>

