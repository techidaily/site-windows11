---
title: Adjusting Time Display in the Taskbar of Window 11
date: 2025-01-18T19:05:52.848Z
updated: 2025-01-22T20:21:51.070Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting Time Display in the Taskbar of Window 11
excerpt: This Article Describes Adjusting Time Display in the Taskbar of Window 11
keywords: Windows 11 Taskbar Time Adjust,Taskbar Timer Change Win11,Alter Taskbar Clock W11,Display Clock Winbar Settings,Update Windows 11 Clock,Tweak Taskbar Time Format,Modify Winbar Clock Position
thumbnail: https://thmb.techidaily.com/dd7a824e4ab8b6d6473fb0116a606a013dd12f046dfa0556ebd9b84053509fd9.png
---

## Adjusting Time Display in the Taskbar of Window 11

 The system tray clock on the right side of the Windows taskbar shows the date and time. While most users find this information useful, others might consider it a source of distraction.

 As such, if you want to hide the clock and date from the taskbar, then this is the place where you need to be. We'll share three different ways by which you can configure the taskbar to hide or show the clock and date.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JAkb8Bv3AU4?si=2rHwnZYTzTLieKgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Hide or Show the Clock and Date from the Taskbar by Using Windows System Settings

 The System Settings is the central hub of a Windows PC. You can use it to update Windows, manage privacy settings,[customize the taskbar](https://www.makeuseof.com/windows-11-customize-taskbar/) , and more.

 It's also one of the places from where you can configure the taskbar to hide or show the clock and date. You can do this by following the below instructions:

 This method only works for Windows 10\. If you are using Windows 11, you can try any other method in this article.

1. Open the**Settings** menu by pressing the**Win + I** hotkeys.
2. Choose the**Personalization** option.
3. Select**Taskbar** from the left panel.
4. Scroll down and click the**Turn system icon on or off** option under the**Notification** area.  
![Turn system icons on or off option in Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-system-icons-on-or-off.png)
5. In the new window that crops up, disable the toggle next to**Clock.**  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q-mXUpVQijU?si=f1MzflPJ8-bD2_iQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Disable the Clock in System Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-the-clock.png)

 That's it. You've disabled the clock and date from the taskbar.

 To enable them again, head towards the above settings again and enable the toggle.

## 2\. Hide or Show the Clock and Date from the Taskbar by Using the Local Group Policy Editor

 The next utility that will help you hide or show the clock and date from the taskbar is the Local Group Policy Editor. You can use this utility to manage Windows features, sign-in and shutdown processes, and more.

 The Local Group Policy Editor is disabled by default in the Windows Home edition. To enable it, check out our guide on how to [access the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 Nevertheless, here's how to use Local Group Policy Editor to configure the taskbar to hide the clock and date.

1. Open the Run dialog box, type**gpedit.msc,** and press Enter.
2. In the Local Group Policy Editor, select the**Administrative Templates** folder under**User configuration.**
3. Click the**Start Menu and Taskbar** folder.
4. Click the**Setting** option in the right pane.
5. Search for and right-click on the**Remove Clock from the system notification area** policy. Then, choose**Edit** from the context menu.
6. In the policy edit window, choose the**Enabled** option.  
![Disabling Clock and Date using the local group policy editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disabling-clock-and-date.jpg)
7. Click**Apply** \>**OK** to save the changes.

 Next,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) for changes to take effect.

 If you want to add the clock and date again to the taskbar, open the edit window of the Remove Clock from the system notification area policy, choose the Disabled option and save the settings.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K7fATC_lI7o?si=UFotPJqflDRZr-mv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Hide or Show the Clock and Date from the Taskbar Using the Registry Editor

 The [Registry Editor](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is an extensive database of your Windows operating system configuration settings. You can use it to navigate the registry and edit its keys.

 Here's how to use the Registry Editor to hide the clock and date from the taskbar:

1. In the Run dialog box, type**regedit** and click**OK.** It'll [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Navigate to the following location:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies`
3. Right-click on the**Policies** key in the left panel, choose**New,** and then select**Key.**
4. Name the key**Explorer** and press Enter.  
![Creating new key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/creating-new-key.jpg)
5. In the Explorer key, right-click on the blank space, and choose**New** \>**DWORD (32-bit Value)** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hZsnjxeSh1U?si=hZIfzQPDNX5KtOCg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Name the value**HideClock** and press Enter.
7. Right-click on the HideClock value, type**1** in the**Value data** section, and click**OK.**  
![Modifying HideClock Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/modifying-hideclock-value.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xIP8ktrmOdg?si=zRnjbGzM6PDx2jCq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

## Remove Any Distraction from the Taskbar

 The system tray clock helps you to keep track of the date and time. But if it has become a distraction or you want to keep the taskbar clean, you can use either of the above methods to configure the taskbar to hide the clock and date.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-videos.techidaily.com/new-boosting-your-fb-pages-advanced-ranking-strategies-for-2024/"><u>[New] Boosting Your FB Pages Advanced Ranking Strategies for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-dream-weavers-the-marvel-interactive-sculptors/"><u>[New] In 2024, Dream Weavers The Marvel Interactive Sculptors</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-eden-echoes-best-rural-role-playing-realms/"><u>[Updated] 2024 Approved Eden Echoes Best Rural Role-Playing Realms</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-rapid-routines-sending-photos-from-iphone-to-computer/"><u>[Updated] Rapid Routines Sending Photos From iPhone to Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-steps-to-disable-amdnvidia-graphics-extras/"><u>Easy Steps to Disable AMD/Nvidia Graphics Extras</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-file-handling-in-windows-powertoys/"><u>Efficient File Handling in Windows PowerToys</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-techniques-for-purging-steams-dns-cache/"><u>Efficient Techniques for Purging Steam's DNS Cache</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-cortana-experience-use-of-vivetool/"><u>Elevate Cortana Experience: Use of ViveTool</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-ui-customization-adding-shortcut-keys-for-wordpad-to-menu-bar/"><u>Elevating UI Customization: Adding Shortcut Keys for Wordpad to Menu Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-non-appearing-screens-on-pc-startup/"><u>Eliminating Non-Appearing Screens on PC Startup</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-performance-lowering-edges-resource-load/"><u>Enhancing Performance: Lowering Edge's Resource Load</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-cortana-records-are-saved-windows-method/"><u>Ensuring Cortana Records Are Saved: Windows Method</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-depth-look-ultraedit-pro-for-video-cutting-2023/"><u>In-Depth Look UltraEdit Pro for Video Cutting 2023</u></a></li>
<li><a href="https://extra-information.techidaily.com/quip-collection-event-specific-jest-compilation/"><u>Quip Collection Event-Specific Jest Compilation</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/95702216-9781583949702-renegade-beauty/"><u>Renegade Beauty | Free Book</u></a></li>
<li><a href="https://article-helps.techidaily.com/sleepy-screenplays-for-nights-end/"><u>Sleepy Screenplays for Night's End</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/vanguard-visions-ultimate-laptop-choices-for-uhd-content-creators-for-2024/"><u>Vanguard Visions Ultimate Laptop Choices for UHD Content Creators for 2024</u></a></li>
</ul></div>

