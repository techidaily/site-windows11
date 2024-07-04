---
title: Learn to Handle Text Emphasis on Windows 11
date: 2024-06-25T12:31:22.956Z
updated: 2024-06-26T12:31:22.956Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Learn to Handle Text Emphasis on Windows 11
excerpt: This Article Describes Learn to Handle Text Emphasis on Windows 11
keywords: Text Emphasis Basics,WinTextFormatting,Highlighting Text W11,Bold Windows Text,Italicize Win11 Text,Underline Text in W11,Stressed Windows Text
thumbnail: https://thmb.techidaily.com/97b0ddc570e6ff11d98aa739ad9094bf8b6916f3ca7d54eab5f1d4007ba674c0.JPG
---

## Learn to Handle Text Emphasis on Windows 11

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
<li><a href="https://windows11.techidaily.com/windows-update-halted-quick-solutions-for-a-perfect-installation/"><u>Windows Update Halted: Quick Solutions for a Perfect Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-your-typing-speed-top-7-fixes-on-win-os/"><u>Elevating Your Typing Speed: Top 7 Fixes on WIN OS</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-efficiency-folders-and-files-converge-in-win-11/"><u>Unlocking Efficiency: Folders & Files Converge in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-ineffectual-window-11-desktop-options/"><u>Fixing Ineffectual Window 11 Desktop Options</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-of-winerrors-your-guide-to-fixes/"><u>Unraveling the Mystery of WinErrors: Your Guide to Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-clouds-hurdle-7-ways-to-reconnect-google-drive/"><u>Overcoming the Cloud's Hurdle: 7 Ways to Reconnect Google Drive</u></a></li>
<li><a href="https://windows11.techidaily.com/instant-permadelete-configuring-your-desktop-trash-bin-on-windows-11-devices/"><u>Instant PermaDelete: Configuring Your Desktop Trash Bin on Windows 11 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/recovering-faulty-tab-key-on-your-pc/"><u>Recovering Faulty Tab Key on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/command-guide-win11-starting-high-privilege-powershell/"><u>Command Guide: Win11 - Starting High-Privilege PowerShell</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/in-2024-streamline-your-color-workflow-final-cut-pro-essentials/"><u>In 2024, Streamline Your Color Workflow Final Cut Pro Essentials</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-unleashing-the-power-of-playback-turning-youtube-content-into-engaging-gifs-pcmobile/"><u>In 2024, Unleashing the Power of Playback  Turning YouTube Content Into Engaging GIFs (PC/Mobile)</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-the-essential-guide-to-earnings-monetizing-content-on-vimeo/"><u>2024 Approved  The Essential Guide to Earnings  Monetizing Content on Vimeo</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-discover-the-best-12-free-and-paid-video-game-openings-for-yt-for-2024/"><u>[Updated] Discover the Best 12 Free and Paid Video Game Openings for YT for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/guide-to-mirror-your-samsung-galaxy-s24-ultra-to-other-android-devices-drfone-by-drfone-android/"><u>Guide to Mirror Your Samsung Galaxy S24 Ultra to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-in-2024-epic-formula-to-animate-photos-from-these-10-animate-pictures-app/"><u>New In 2024, Epic Formula to Animate Photos From These 10 Animate Pictures App</u></a></li>
<li><a href="https://extra-resources.techidaily.com/create-an-individualistic-meme-masterpiece-for-2024/"><u>Create an Individualistic Meme Masterpiece for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-boosting-profile-videos-a-guide-to-allure/"><u>In 2024, Boosting Profile Videos  A Guide to Allure</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-crafting-compelling-combinations-a-guide-to-creating-your-own-youtube-playlists/"><u>[New] 2024 Approved  Crafting Compelling Combinations  A Guide to Creating Your Own YouTube Playlists</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-ipad-users-create-professional-time-lapse-videos/"><u>[Updated] 2024 Approved  IPad Users  Create Professional Time-Lapse Videos</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>