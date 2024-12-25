---
title: Switching Off Search Highlight Features in Windows 11
date: 2024-12-18T19:00:27.246Z
updated: 2024-12-25T18:38:31.186Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Switching Off Search Highlight Features in Windows 11
excerpt: This Article Describes Switching Off Search Highlight Features in Windows 11
keywords: Turn Off Highlights,Disable Search Feature,Hide Text on Screen,Deactivate Highlighter,Remove Search Glow,Suppress Search Box Lighting,Mute Windows 11 Searches
thumbnail: https://thmb.techidaily.com/83a5e7f4b304717df57e5c96a8beb60fe39d761265a0a53063f5a3b844f4f838.png
---

## Switching Off Search Highlight Features in Windows 11

 Search highlights is a feature that helps you discover interesting content whenever you launch Windows Search. If you find that they aren’t popping up, there are several ways for you to turn them on. And if you find them to be bothersome, well, you can turn them off and continue enjoying Windows as if they never existed.

 So, keep on reading to find out three ways to turn search highlights on and off.

## 1\. How to Turn Search Highlights On and Off in the Settings App

 Press **Win + I** to open the Settings app. Then, select **Privacy & security** on the left side menu, and then click on **Search permissions** in the right panel.

![the privacy and security page on Windows with Search permissions showing in the right panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions.jpg)

 Scroll down to the **More settings** section, and then click the toggle under **Show search highlights** to turn the feature on or off.

![the Seach permissions page on Windows 11 with the More settings section showing and the toggle for Show search highlights set to on](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions-settings.jpg)

 You should no longer see search lights now.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/43goO8X0iX0?si=48Cqf6td2q_6T6h3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Turn Search Highlights On and Off in the Local Group Policy Editor

 Press **Win + R** to open the Windows Run dialog box, type **gpedit.msc** in the text box, and then hit the **Enter** key. For more ways to launch the tool, read our guide on [ways to open the Local Group Policy Editor on Windows 11](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

 On the left side menu, navigate to **Computer Configuration > Administrative Templates > Windows Components > Search**. Then, in the right panel, double-click the **Allow search highlights** policy to edit it.

![the Local Group Policy Editor on Windows with the Allow search highlights policy highlighted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/lgpe-windows-allow-search-highlights-policy.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kTHQrw8e1gk?si=gTPIa7KjhSZ0Vz97" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To show search highlights, make sure the **Not Configured** or **Enabled** radio button is checked, and then click **OK**.

![the Allow search highlights policy being edited on Windows and it is set to Not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-search-highlights-not-configured-windows.jpg)

 To disable search highlights, check the **Disabled** radio button, and then click **OK**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/l4R7_qNIQvY?si=2zJOPfEcm6_3udzn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Turn Search Highlights On and Off in the Registry Editor

 Press **Win + R** to open the Windows Run dialog box, type **regedit** in the text box, and then hit the **Enter** key. Click **Yes** in the UAC prompt to finally launch the Registry Editor.

 Before you proceed, we recommend that you read our guide on [how to back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). This may come in handy in case you accidentally break the Windows Registry.

 In the address bar of the Registry Editor, copy and paste the below text, and then press **Enter**:

`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\SearchSettings`

 Right-click the **SearchSettings** key on the left side menu and select **New > DWORD (32-bit) Value** in the menu that appears. Then, name the value **IsDynamicSearchBoxEnabled**.

![creating a dword value in the Windows registry for the SearchSettings key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/creating-dword-windows-registry.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wVVp-GggK3U?si=RJb1ClNQV7GjTu_3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In the right panel, double-click **IsDynamicSearchBoxEnabled** (the value you just created) and then enter **1** in the **Value data** text box to turn search highlights on. Then, click **OK** to apply the change.

![the IsDynamicSearchBoxEnabled value in the Registry Editor and Value data has been set to 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/editing-isdynamicsearchboxenabled-value-windows-registry.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YZma8PBO0D8?si=9-qQgGVTuChYd27a" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To turn search highlights off, enter **0** in the **Value data** text box, and then click **OK**.

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
<li><a href="https://facebook-video-content.techidaily.com/new-effortless-facebook-live-streams-from-your-smartphone-for-2024/"><u>[New] Effortless Facebook Live Streams From Your Smartphone for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-expert-tips-for-seamless-iphone-screen-recordings-for-2024/"><u>[New] Expert Tips for Seamless iPhone Screen Recordings for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/n-2024-enhance-creativity-in-video-editing-these-7-sources/"><u>[New] In 2024, Enhance Creativity in Video Editing - These 7 Sources</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-in-2024-unrivaled-vr-sets-for-aerial-adventures/"><u>[New] In 2024, Unrivaled VR Sets for Aerial Adventures</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-maximizing-engagement-through-creator-studio-insights/"><u>[New] Maximizing Engagement Through Creator Studio Insights</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-a-step-by-step-framework-for-iconic-podcast-visuals/"><u>2024 Approved A Step-by-Step Framework for Iconic Podcast Visuals</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-the-latest-validity-fingerprint-sensor-driver-fast-and-simple-installation/"><u>Download the Latest Validity Fingerprint Sensor Driver: Fast and Simple Installation</u></a></li>
<li><a href="https://fox-that.techidaily.com/guide-to-restoring-iphone-flashlight-functionality-discover-12-repair-techniques/"><u>Guide to Restoring iPhone Flashlight Functionality - Discover 12 Repair Techniques</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-free-versatile-video-tools-for-linux-windows-and-macos/"><u>In 2024, Free, Versatile Video Tools for Linux, Windows & MacOS</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-link-loss-in-winvpn-a-step-by-step-solution/"><u>Restoring Link Loss in WinVPN: A Step-By Step Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resurrect-your-disconnected-controller/"><u>Steps to Resurrect Your Disconnected Controller</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-overcoming-windows-terminal-access-issues/"><u>Troubleshooting: Overcoming Windows Terminal Access Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/tutorial-navigating-to-windows-11-phone-dialer/"><u>Tutorial: Navigating to Windows 11 Phone Dialer</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-fixing-windows-roblox-code-403-issue/"><u>Understanding & Fixing Windows Roblox Code 403 Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-offline-the-essential-manual/"><u>Win11 Offline: The Essential Manual</u></a></li>
</ul></div>

