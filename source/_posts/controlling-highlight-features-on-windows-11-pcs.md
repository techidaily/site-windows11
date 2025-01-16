---
title: Controlling Highlight Features on Windows 11 PCs
date: 2025-01-11T10:10:59.181Z
updated: 2025-01-16T04:16:18.658Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Controlling Highlight Features on Windows 11 PCs
excerpt: This Article Describes Controlling Highlight Features on Windows 11 PCs
keywords: Win11 Highlighter Control,Highlight Management Win11,Win11 Feature Adjustment,Windows 11 Color Editor,Highlight Tweak Windows 11,Windows 11 Light Effects,Highlight Settings Win11 PC
thumbnail: https://thmb.techidaily.com/65fba9a952c6564fd879ce858daef732be8f2531c9874f65aafa43e482841322.jpg
---

## Controlling Highlight Features on Windows 11 PCs

 Search highlights is a feature that helps you discover interesting content whenever you launch Windows Search. If you find that they aren’t popping up, there are several ways for you to turn them on. And if you find them to be bothersome, well, you can turn them off and continue enjoying Windows as if they never existed.

 So, keep on reading to find out three ways to turn search highlights on and off.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bXmwwSmYqq4?si=Bb-eJfLnlpeeClyt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Turn Search Highlights On and Off in the Settings App

 Press **Win + I** to open the Settings app. Then, select **Privacy & security** on the left side menu, and then click on **Search permissions** in the right panel.

![the privacy and security page on Windows with Search permissions showing in the right panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions.jpg)

 Scroll down to the **More settings** section, and then click the toggle under **Show search highlights** to turn the feature on or off.

![the Seach permissions page on Windows 11 with the More settings section showing and the toggle for Show search highlights set to on](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions-settings.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c-BHGGIC0zE?si=FzUQKZa-bx8OlKuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You should no longer see search lights now.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UJJbj1vbzs8?si=X3zd8thLJKprfuEa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Turn Search Highlights On and Off in the Local Group Policy Editor

 Press **Win + R** to open the Windows Run dialog box, type **gpedit.msc** in the text box, and then hit the **Enter** key. For more ways to launch the tool, read our guide on [ways to open the Local Group Policy Editor on Windows 11](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

 On the left side menu, navigate to **Computer Configuration > Administrative Templates > Windows Components > Search**. Then, in the right panel, double-click the **Allow search highlights** policy to edit it.

![the Local Group Policy Editor on Windows with the Allow search highlights policy highlighted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/lgpe-windows-allow-search-highlights-policy.jpg)

 To show search highlights, make sure the **Not Configured** or **Enabled** radio button is checked, and then click **OK**.

![the Allow search highlights policy being edited on Windows and it is set to Not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-search-highlights-not-configured-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/l-SCWTWpegY?si=oxTsHQkIu1v4-I6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Lp78eFEGwVU?si=-4orJBLvJJrggCJ2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Control Your Search Highlights on Windows 11

 Windows 11 being customizable is what makes interacting with the OS enjoyable. The power is in your hands whether you want to see search highlights or not in Windows Search. And now you know three ways to enable or disable them.

 So, keep on reading to find out three ways to turn search highlights on and off.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-10-best-video-tools-perfect-your-webcam-vids/"><u>[New] 2024 Approved 10 Best Video Tools Perfect Your Webcam Vids</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-precision-in-preservation-expert-techniques-for-skype-call-recordings/"><u>[New] 2024 Approved Precision in Preservation Expert Techniques for Skype Call Recordings</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-illustrator-way-adding-realistic-blur-to-your-pics/"><u>[New] The Illustrator Way Adding Realistic Blur to Your Pics</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-entrepreneurs-blueprint-for-profiting-from-video-content/"><u>2024 Approved The Entrepreneur's Blueprint for Profiting From Video Content</u></a></li>
<li><a href="https://win-able.techidaily.com/banishing-cannot-connect-to-the-server-error-from-your-lost-ark-gaming-experience/"><u>Banishing 'Cannot Connect to the Server' Error From Your Lost Ark Gaming Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-steps-to-resurrect-itunes-on-windows-devices/"><u>Essential Steps to Resurrect iTunes on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-overcome-repetitive-login-failures-in-teams/"><u>How to Overcome Repetitive Login Failures in Teams</u></a></li>
<li><a href="https://windows11.techidaily.com/instant-internet-jump-after-installing-os/"><u>Instant Internet Jump After Installing OS</u></a></li>
<li><a href="https://windows11.techidaily.com/personalizing-window-writable-wallpaper-with-confidence/"><u>Personalizing Window' Writable Wallpaper with Confidence</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/proven-ways-to-cash-in-instagrams-leading-revenue-methods-for-2024/"><u>Proven Ways to Cash In Instagram's Leading Revenue Methods for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/silent-steps-a-quick-guide-to-stopping-windows-11-activities/"><u>Silent Steps: A Quick Guide to Stopping Windows 11 Activities</u></a></li>
<li><a href="https://windows11.techidaily.com/steady-your-cursor-fixing-erratic-movements-in-windows-11/"><u>Steady Your Cursor: Fixing Erratic Movements in Windows 11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-15-apps-to-hack-wifi-password-on-xiaomi-13-ultra-by-drfone-android/"><u>Top 15 Apps To Hack WiFi Password On Xiaomi 13 Ultra</u></a></li>
<li><a href="https://win-howtos.techidaily.com/top-15-gratis-videovy-konverter-typu-mac/"><u>Top 15 Grátis Vídeový Konvertér Typu Mac</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/what-does-instantaneous-video-removal-mean-for-user-privacy-for-2024/"><u>What Does Instantaneous Video Removal Mean for User Privacy for 2024</u></a></li>
</ul></div>

