---
title: Preserving Default Time on Windows PCs
date: 2025-02-26T12:05:54.492Z
updated: 2025-03-02T03:01:02.745Z
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
<li><a href="https://instagram-video-recordings.techidaily.com/updated-enhance-your-footage-reducing-size-for-instagram-on-a-mac/"><u>[Updated] Enhance Your Footage Reducing Size for Instagram on a Mac</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-mastering-instagrams-hashtag-language-for-enhanced-engagement/"><u>[Updated] In 2024, Mastering Instagram's Hashtag Language for Enhanced Engagement</u></a></li>
<li><a href="https://win-hacks.techidaily.com/44cm44oh44k444k44or44kr44oh44op44gu5lin6ygp5yih44gq5pu45byp6kit5a6a44gr5rcx44gl44gn44gplus44gx44gf77yb44ov44kh44kk44or5b6p5ywd5oml6acg5a6m5ywo44ks44kk44oj44171/"><u>「デジタルカメラの不適切な書式設定に気づきました！ファイル復元手順完全ガイド」</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-conveniently-capture-top-chrome-utilities-for-fb-video-downloads/"><u>2024 Approved Conveniently Capture Top Chrome Utilities for FB Video Downloads</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-windows-11-performance-run-command-upgrade-guide/"><u>Boosting Windows 11 Performance: Run Command Upgrade Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/convenient-methods-for-local-policies-on-windows-11/"><u>Convenient Methods for Local Policies on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/creating-a-dual-disk-on-windows-independently/"><u>Creating a Dual Disk on Windows, Independently</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-high-cpu-usage-techniques-from-windows-resource-monitor/"><u>Decoding High CPU Usage: Techniques From Windows Resource Monitor</u></a></li>
<li><a href="https://change-location.techidaily.com/here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-vivo-y100-5g-drfone-by-drfone-virtual-android/"><u>Here Are Some Reliable Ways to Get Pokemon Go Friend Codes For Vivo Y100 5G | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-whatsapp-messages-on-poco-c55-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track WhatsApp Messages on Poco C55 Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-steam-library-synchronization-hitches/"><u>Navigating Through Steam Library Synchronization Hitches</u></a></li>
<li><a href="https://win-reviews.techidaily.com/seamless-guide-save-your-iphone-videos-on-windowsmac-with-these-3-simple-steps/"><u>Seamless Guide: Save Your iPhone Videos on Windows/Mac with These 3 Simple Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/silencing-the-cacophony-soundcard-irq-fixes/"><u>Silencing the Cacophony: Soundcard IRQ Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-how-to-recover-vanishing-desktop-icons-on-your-windows-10-pc/"><u>Solved: How to Recover Vanishing Desktop Icons on Your Windows 10 PC</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-disabling-onedrive-icon-on-windows-11-explore/"><u>Strategies for Disabling OneDrive Icon on Windows 11 Explore</u></a></li>
<li><a href="https://buynow-info.techidaily.com/top-rated-usb-c-chargers-and-adapters-a-comprehensive-guide/"><u>Top Rated USB-C Chargers & Adapters : A Comprehensive Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-11-eliminating-invisible-logins/"><u>Troubleshooting Windows 11: Eliminating Invisible Logins</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-lava-blaze-curve-5g-drfone-by-drfone-virtual-android/"><u>Will Pokémon Go Ban the Account if You Use PGSharp On Lava Blaze Curve 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-elevate-with-25-customization-tips/"><u>Windows 11: Elevate with 25 Customization Tips</u></a></li>
</ul></div>

