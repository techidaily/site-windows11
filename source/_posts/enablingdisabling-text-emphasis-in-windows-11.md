---
title: Enabling/Disabling Text Emphasis in Windows 11
date: 2024-06-25T12:15:44.866Z
updated: 2024-06-26T12:15:44.866Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enabling/Disabling Text Emphasis in Windows 11
excerpt: This Article Describes Enabling/Disabling Text Emphasis in Windows 11
keywords: Emphasize Text Windows 11,Disable Text Stressing,Enable Highlight Window,Turn Off Bold Text Win,Activate Italics Windows,Deactivate Font Stress,Change Text Emphasis Win11
thumbnail: https://thmb.techidaily.com/5996397f505d52b0f60ffe77c36fd8859621590a57dd0707f44eeaa06c560dbc.jpg
---

## Enabling/Disabling Text Emphasis in Windows 11

 Search highlights is a feature that helps you discover interesting content whenever you launch Windows Search. If you find that they aren’t popping up, there are several ways for you to turn them on. And if you find them to be bothersome, well, you can turn them off and continue enjoying Windows as if they never existed.

 So, keep on reading to find out three ways to turn search highlights on and off.

## 1\. How to Turn Search Highlights On and Off in the Settings App

 Press **Win + I** to open the Settings app. Then, select **Privacy & security** on the left side menu, and then click on **Search permissions** in the right panel.

![the privacy and security page on Windows with Search permissions showing in the right panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions.jpg)

 Scroll down to the **More settings** section, and then click the toggle under **Show search highlights** to turn the feature on or off.

![the Seach permissions page on Windows 11 with the More settings section showing and the toggle for Show search highlights set to on](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions-settings.jpg)

 You should no longer see search lights now.

## 2\. Turn Search Highlights On and Off in the Local Group Policy Editor

 Press **Win + R** to open the Windows Run dialog box, type **gpedit.msc** in the text box, and then hit the **Enter** key. For more ways to launch the tool, read our guide on [ways to open the Local Group Policy Editor on Windows 11](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

 On the left side menu, navigate to **Computer Configuration > Administrative Templates > Windows Components > Search**. Then, in the right panel, double-click the **Allow search highlights** policy to edit it.

![the Local Group Policy Editor on Windows with the Allow search highlights policy highlighted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/lgpe-windows-allow-search-highlights-policy.jpg)

 To show search highlights, make sure the **Not Configured** or **Enabled** radio button is checked, and then click **OK**.

![the Allow search highlights policy being edited on Windows and it is set to Not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-search-highlights-not-configured-windows.jpg)

 To disable search highlights, check the **Disabled** radio button, and then click **OK**.

## 3\. Turn Search Highlights On and Off in the Registry Editor

 Press **Win + R** to open the Windows Run dialog box, type **regedit** in the text box, and then hit the **Enter** key. Click **Yes** in the UAC prompt to finally launch the Registry Editor.

 Before you proceed, we recommend that you read our guide on [how to back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). This may come in handy in case you accidentally break the Windows Registry.

 In the address bar of the Registry Editor, copy and paste the below text, and then press **Enter**:

`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\SearchSettings`

 Right-click the **SearchSettings** key on the left side menu and select **New > DWORD (32-bit) Value** in the menu that appears. Then, name the value **IsDynamicSearchBoxEnabled**.

![creating a dword value in the Windows registry for the SearchSettings key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/creating-dword-windows-registry.jpg)

 In the right panel, double-click **IsDynamicSearchBoxEnabled** (the value you just created) and then enter **1** in the **Value data** text box to turn search highlights on. Then, click **OK** to apply the change.

![the IsDynamicSearchBoxEnabled value in the Registry Editor and Value data has been set to 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/editing-isdynamicsearchboxenabled-value-windows-registry.jpg)

 To turn search highlights off, enter **0** in the **Value data** text box, and then click **OK**.

## Control Your Search Highlights on Windows 11

 Windows 11 being customizable is what makes interacting with the OS enjoyable. The power is in your hands whether you want to see search highlights or not in Windows Search. And now you know three ways to enable or disable them.

 So, keep on reading to find out three ways to turn search highlights on and off.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/a-comprerant-users-resourceful-approach-to-processes-and-themes-in-windows-11/"><u>A Compreran't User's Resourceful Approach to Processes and Themes in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-absence-of-windows-1011-search-outcomes/"><u>Solving Absence of Windows 10/11 Search Outcomes</u></a></li>
<li><a href="https://windows11.techidaily.com/from-edge-to-frontline-quick-fixes-for-lost-off-screen-windows/"><u>From Edge to Frontline: Quick Fixes for Lost Off-Screen Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-elevate-pre-windows-upgrade-machines-into-win11/"><u>How to Elevate Pre-Windows Upgrade Machines Into Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-solutions-to-the-windows-too-many-requests-challenge/"><u>Swift Solutions to the Windows Too Many Requests Challenge</u></a></li>
<li><a href="https://windows11.techidaily.com/revamp-desktop-by-removing-windows-11s-highlighted-icon/"><u>Revamp Desktop by Removing Windows 11'S Highlighted Icon</u></a></li>
<li><a href="https://windows11.techidaily.com/highlighting-key-windows-processes-for-virus-alerts/"><u>Highlighting Key Windows Processes for Virus Alerts</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-integrating-alternative-antiviruses-with-ms-defender/"><u>Tips for Integrating Alternative Antiviruses with MS Defender</u></a></li>
<li><a href="https://windows11.techidaily.com/maximize-output-win-based-time-management-apps-reviewed/"><u>Maximize Output: Win-Based Time Management Apps Reviewed</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/advanced-steps-for-documenting-online-meetings/"><u>Advanced Steps for Documenting Online Meetings</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-get-your-facebook-data-fast-and-free-online/"><u>[Updated] In 2024, Get Your Facebook Data Fast & Free Online</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-redefine-your-online-persona-with-a-new-tiktok-profile/"><u>[New] In 2024, Redefine Your Online Persona with a New TikTok Profile</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-easy-fixes-how-to-recover-forgotten-icloud-password-on-your-apple-iphone-6-plus-by-drfone-ios/"><u>In 2024, Easy Fixes How To Recover Forgotten iCloud Password On your Apple iPhone 6 Plus</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-unlock-the-power-of-beginnings-with-imovies-creative-tools/"><u>In 2024, Unlock the Power of Beginnings with iMovie's Creative Tools</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-best-online-video-reversers/"><u>New Best Online Video Reversers</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-sculpted-sound-diminishment-for-impact/"><u>2024 Approved  Sculpted Sound Diminishment for Impact</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-10-best-spy-watches-for-your-motorola-moto-g-5g-2023-drfone-by-drfone-virtual-android/"><u>Top 10 Best Spy Watches For your Motorola Moto G 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-from-buzz-to-sales-transforming-social-media-into-traffic/"><u>[New] In 2024, From Buzz to Sales  Transforming Social Media Into Traffic</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-poco-c55-by-drfone-android/"><u>10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On Poco C55</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>