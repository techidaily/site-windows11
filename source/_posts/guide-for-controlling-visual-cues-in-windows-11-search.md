---
title: Guide for Controlling Visual Cues in Windows 11 Search
date: 2024-11-18T19:11:21.025Z
updated: 2024-11-24T17:07:56.601Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide for Controlling Visual Cues in Windows 11 Search
excerpt: This Article Describes Guide for Controlling Visual Cues in Windows 11 Search
keywords: Windows 11 Vision Control,Visual Cues Management,11 Search Interface Guide,Windows 11 UI Optimization,PC Search Feature Adjustment,Altering Window 11 Display,Enhancing Search Visibility
thumbnail: https://thmb.techidaily.com/f0dbd5a21adf0257efb4cfc535a5b1745bbe68be5c6511e0bd704dc50cbfa331.jpg
---

## Guide for Controlling Visual Cues in Windows 11 Search

 Search highlights is a feature that helps you discover interesting content whenever you launch Windows Search. If you find that they aren’t popping up, there are several ways for you to turn them on. And if you find them to be bothersome, well, you can turn them off and continue enjoying Windows as if they never existed.

 So, keep on reading to find out three ways to turn search highlights on and off.

## 1\. How to Turn Search Highlights On and Off in the Settings App

 Press **Win + I** to open the Settings app. Then, select **Privacy & security** on the left side menu, and then click on **Search permissions** in the right panel.

![the privacy and security page on Windows with Search permissions showing in the right panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/TJCye_oCTTw?si=6bVyBphcSgSFdyuq&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Scroll down to the **More settings** section, and then click the toggle under **Show search highlights** to turn the feature on or off.

![the Seach permissions page on Windows 11 with the More settings section showing and the toggle for Show search highlights set to on](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions-settings.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/T-ssCD10v2M?si=WVWGNayUiCAkMZzZ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You should no longer see search lights now.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9sk53d1bBhY?si=yaTeDogLb3D4dYu1&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Turn Search Highlights On and Off in the Local Group Policy Editor

 Press **Win + R** to open the Windows Run dialog box, type **gpedit.msc** in the text box, and then hit the **Enter** key. For more ways to launch the tool, read our guide on [ways to open the Local Group Policy Editor on Windows 11](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

 On the left side menu, navigate to **Computer Configuration > Administrative Templates > Windows Components > Search**. Then, in the right panel, double-click the **Allow search highlights** policy to edit it.

![the Local Group Policy Editor on Windows with the Allow search highlights policy highlighted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/lgpe-windows-allow-search-highlights-policy.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mHFtYJppXFk?si=ylFaAT4nXqCmlV8F&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/58KlTPHv8dU?si=7ICagyNgrao7OkVO&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In the right panel, double-click **IsDynamicSearchBoxEnabled** (the value you just created) and then enter **1** in the **Value data** text box to turn search highlights on. Then, click **OK** to apply the change.

![the IsDynamicSearchBoxEnabled value in the Registry Editor and Value data has been set to 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/editing-isdynamicsearchboxenabled-value-windows-registry.jpg)

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
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-unearthing-the-top-10-sleeper-social-media-stars/"><u>[Updated] In 2024, Unearthing the Top 10 Sleeper Social Media Stars</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-unveiling-how-you-can-profit-from-youtube-content/"><u>[Updated] In 2024, Unveiling How You Can Profit From YouTube Content</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-lose-yourself-to-laughter-best-10-jokes-for-2024/"><u>[Updated] Lose Yourself to Laughter Best 10 Jokes for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-complete-digest-exploring-google-podcast-apps-essence/"><u>2024 Approved Complete Digest Exploring Google Podcast App's Essence</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/a-deep-dive-into-elegoo-saturn-4-ultra-pioneering-innovation-in-next-gen-resin-3d-printing/"><u>A Deep Dive Into Elegoo Saturn 4 Ultra: Pioneering Innovation in Next-Gen Resin 3D Printing</u></a></li>
<li><a href="https://android-frp.techidaily.com/a-quick-guide-to-poco-f5-pro-5g-frp-bypass-instantly-by-drfone-android/"><u>A Quick Guide to Poco F5 Pro 5G FRP Bypass Instantly</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/our-shots-top-cameras-and-lenses-for-youtubers/"><u>Ace Your Shots Top Cameras & Lenses for YouTubers</u></a></li>
<li><a href="https://howto.techidaily.com/app-wont-open-on-your-huawei-nova-y71-here-are-all-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>App Wont Open on Your Huawei Nova Y71? Here Are All Fixes | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/microsoft-brings-ai-to-windows-11-revolutionizing-the-taskbar-experience/"><u>Microsoft Brings AI to Windows 11, Revolutionizing the Taskbar Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-secure-boot-snags-with-these-5-proven-fixes/"><u>Navigate Secure Boot Snags with These 5 Proven Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-pin-lock-problems-in-11-edition/"><u>Overcoming Windows PIN Lock Problems in 11 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-phantom-device-error-in-windows-11/"><u>Remedying Phantom Device Error in Windows 11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/remove-the-lock-screen-fingerprint-of-your-infinix-hot-40i-by-drfone-android/"><u>Remove the Lock Screen Fingerprint Of Your Infinix Hot 40i</u></a></li>
<li><a href="https://windows11.techidaily.com/the-rejuvenation-routine-top-13-methods-for-restoring-windows/"><u>The Rejuvenation Routine: Top 13 Methods for Restoring Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-file-unpreviews-in-windows-based-outlook/"><u>Troubleshooting File Unpreviews in Windows-Based Outlook</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-family-safety-rescue-quick-corrections-listed-here/"><u>Windows Family Safety Rescue: Quick Corrections Listed Here</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-hour-hand-healed-harmonize-system-time/"><u>Windows Hour Hand Healed: Harmonize System Time</u></a></li>
</ul></div>

