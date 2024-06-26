---
title: Procedures for Upholding True Windows Time Values
date: 2024-06-25T12:27:59.908Z
updated: 2024-06-26T12:27:59.908Z
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/rectifying-thx-not-working-in-windows-setup/"><u>Rectifying THX Not Working in Windows Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-preventing-google-chromes-autopilot-tabs/"><u>Guide to Preventing Google Chrome's Autopilot Tabs</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-transition-from-ical-to-windows-calendar/"><u>Navigating the Transition: From iCal to Windows Calendar</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-pause-auto-updates-no-more-prompts/"><u>Windows Pause Auto-Updates: No More Prompts!</u></a></li>
<li><a href="https://windows11.techidaily.com/saving-screen-time-by-hushing-file-explorer-tabs/"><u>Saving Screen Time by Hushing File Explorer Tabs</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-missing-device-alert-in-windows-10/"><u>Steps to Resolve 'Missing' Device Alert in Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/visualize-resource-consumption-windows-tray-update-guide/"><u>Visualize Resource Consumption: Windows Tray Update Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-common-errors-during-windows-11-system-rollout/"><u>Tackling Common Errors During Windows 11 System Rollout</u></a></li>
<li><a href="https://windows11.techidaily.com/gain-control-of-costs-windows-11-pro-key-advantages/"><u>Gain Control of Costs: Windows 11 Pro Key Advantages</u></a></li>
<li><a href="https://windows11.techidaily.com/rise-above-ethernet-ceiling-overcome-the-windows-100mbps-limit/"><u>Rise Above Ethernet Ceiling: Overcome the Windows 100Mbps Limit</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-sharefake-location-on-whatsapp-for-nokia-150-2023-drfone-by-drfone-virtual-android/"><u>In 2024, How to Share/Fake Location on WhatsApp for Nokia 150 (2023) | Dr.fone</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-2024-approved-film-team-dynamics-how-every-crew-member-contributes-to-the-final-product/"><u>Updated 2024 Approved Film Team Dynamics How Every Crew Member Contributes to the Final Product</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-mi-11s-screen-recording-elevate-your-digital-storytelling/"><u>[Updated] 2024 Approved  Mi 11'S Screen Recording  Elevate Your Digital Storytelling</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-cutting-through-the-clutter-a-comprehensive-approach-to-sound-management-in-video-editing/"><u>In 2024, Cutting Through the Clutter A Comprehensive Approach to Sound Management in Video Editing</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/voice-translation-english-to-bangla-online-and-offline-apps/"><u>Voice Translation English to Bangla Online and Offline Apps</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-preserving-your-nintendo-switch-experiences-a-guide-for-2024/"><u>[Updated] Preserving Your Nintendo Switch Experiences  A Guide for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/thriving-on-both-sides-work-and-youtubing-tips-for-2024/"><u>Thriving on Both Sides  Work and YouTubing Tips for 2024</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/how-to-intercept-text-messages-on-apple-iphone-15-plus-drfone-by-drfone-virtual-ios/"><u>How to Intercept Text Messages on Apple iPhone 15 Plus | Dr.fone</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/the-pathway-to-pristine-recordings-removing-unwanted-noises-for-crystal-clear-sound/"><u>The Pathway to Pristine Recordings Removing Unwanted Noises for Crystal-Clear Sound</u></a></li>
<li><a href="https://animation-videos.techidaily.com/2024-approved-ways-to-stop-animation-from-looping-in-unity/"><u>2024 Approved Ways to Stop Animation From Looping in Unity</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>