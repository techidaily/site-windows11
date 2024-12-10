---
title: Turn On/Off Text Emphasis and Highlight Effects on PC
date: 2024-12-07T20:57:38.127Z
updated: 2024-12-10T17:52:01.403Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Turn On/Off Text Emphasis and Highlight Effects on PC
excerpt: This Article Describes Turn On/Off Text Emphasis and Highlight Effects on PC
keywords: Text Emphasis Toggle,Highlight Control,Font Style Switch,Bold & Italic Change,Strong Font Application,Underline Text Adjust,Color Text Effects
thumbnail: https://thmb.techidaily.com/8887df92f9a6ef29a9a0f4d11045d6b1c0399eebd3f27cb0d07dfb8b59734a92.jpg
---

## Turn On/Off Text Emphasis and Highlight Effects on PC

 Search highlights is a feature that helps you discover interesting content whenever you launch Windows Search. If you find that they aren’t popping up, there are several ways for you to turn them on. And if you find them to be bothersome, well, you can turn them off and continue enjoying Windows as if they never existed.

 So, keep on reading to find out three ways to turn search highlights on and off.

## 1\. How to Turn Search Highlights On and Off in the Settings App

 Press **Win + I** to open the Settings app. Then, select **Privacy & security** on the left side menu, and then click on **Search permissions** in the right panel.

![the privacy and security page on Windows with Search permissions showing in the right panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XoC2TGp1PLY?si=iH9xs76NhWn4pP-E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Scroll down to the **More settings** section, and then click the toggle under **Show search highlights** to turn the feature on or off.

![the Seach permissions page on Windows 11 with the More settings section showing and the toggle for Show search highlights set to on](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions-settings.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2Iv3DjT2Fyw?si=pR_z8ZDDVGF2MvKJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You should no longer see search lights now.

## 2\. Turn Search Highlights On and Off in the Local Group Policy Editor

 Press **Win + R** to open the Windows Run dialog box, type **gpedit.msc** in the text box, and then hit the **Enter** key. For more ways to launch the tool, read our guide on [ways to open the Local Group Policy Editor on Windows 11](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

 On the left side menu, navigate to **Computer Configuration > Administrative Templates > Windows Components > Search**. Then, in the right panel, double-click the **Allow search highlights** policy to edit it.

![the Local Group Policy Editor on Windows with the Allow search highlights policy highlighted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/lgpe-windows-allow-search-highlights-policy.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UUPt2zKtJ5k?si=LLHdsFDLzVByJsKj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To show search highlights, make sure the **Not Configured** or **Enabled** radio button is checked, and then click **OK**.

![the Allow search highlights policy being edited on Windows and it is set to Not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-search-highlights-not-configured-windows.jpg)

 To disable search highlights, check the **Disabled** radio button, and then click **OK**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tkpBmccvJ_Q?si=J7ellPL1G1l8Axi_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/8dH3yHH9IX8?si=geiW5KbIljSFT9pz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-info.techidaily.com/new-2024-approved-adding-chronological-markers-to-youtube-media/"><u>[New] 2024 Approved Adding Chronological Markers to YouTube Media</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-2024-approved-elevating-visual-storytelling-the-mavic-pro-journey/"><u>[New] 2024 Approved Elevating Visual Storytelling The Mavic Pro Journey</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-achieve-aesthetic-11-best-instagram-enhancers/"><u>[New] In 2024, Achieve Aesthetic 11 Best Instagram Enhancers</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-earths-highest-paid-online-video-personality/"><u>[Updated] 2024 Approved Earth's Highest-Paid Online Video Personality</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-in-2024-standard-youtube-licenses-versus-cc/"><u>[Updated] In 2024, Standard Youtube Licenses Versus CC</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-origami-homes-in-minecraft-japanese-vistas/"><u>2024 Approved Origami Homes in Minecraft Japanese Vistas</u></a></li>
<li><a href="https://windows11.techidaily.com/extending-windows-11-shutdown-for-active-tasks-tips-and-tricks/"><u>Extending Windows 11 Shutdown for Active Tasks: Tips & Tricks</u></a></li>
<li><a href="https://android-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-from-realme-gt-3-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock from Realme GT 3 Phones with/without a PC</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-clean-up-and-customize-your-windows-11-desktop/"><u>How to Clean Up and Customize Your Windows 11 Desktop</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/in-2024-dynamic-dimensions-adobes-approach-to-photo-motion-effects/"><u>In 2024, Dynamic Dimensions Adobe's Approach to Photo Motion Effects</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/personalized-melodies-made-easy-building-a-youtube-music-collection-on-webmobile-for-2024/"><u>Personalized Melodies Made Easy Building a YouTube Music Collection on Web/Mobile for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-audio-communication-via-xbox-mic-and-windows-11/"><u>Restoring Audio Communication via Xbox Mic & Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tutorial-reverting-the-search-bar-design-of-windows-11/"><u>Tutorial: Reverting the Search Bar Design of Windows 11</u></a></li>
</ul></div>

