---
title: Hide or Show Clock - Secrets of the Taskbar
date: 2024-12-24T19:10:37.873Z
updated: 2024-12-25T18:32:56.368Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Hide or Show Clock - Secrets of the Taskbar
excerpt: This Article Describes Hide or Show Clock - Secrets of the Taskbar
keywords: Hide Clock Applet,Show Timebar,Taskbar Timer,Taskbar Clock UI,Manage Taskbar Clock,Adjust Windows Clock,Clock Bar Settings
thumbnail: https://thmb.techidaily.com/474c5054a0eaa723712bc3725331bacf73663ebfef0031bd8bc1879804e39c8f.jpg
---

## Hide or Show Clock - Secrets of the Taskbar

 The system tray clock on the right side of the Windows taskbar shows the date and time. While most users find this information useful, others might consider it a source of distraction.

 As such, if you want to hide the clock and date from the taskbar, then this is the place where you need to be. We'll share three different ways by which you can configure the taskbar to hide or show the clock and date.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/umvX4ZdWbxk?si=tPXL0-Kzf9SQaY8z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/LeKJBWb6Jhk?si=AnViizAPiIT1YCRA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Disable the Clock in System Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-the-clock.png)

 That's it. You've disabled the clock and date from the taskbar.

 To enable them again, head towards the above settings again and enable the toggle.

## 2\. Hide or Show the Clock and Date from the Taskbar by Using the Local Group Policy Editor

 The next utility that will help you hide or show the clock and date from the taskbar is the Local Group Policy Editor. You can use this utility to manage Windows features, sign-in and shutdown processes, and more.

 The Local Group Policy Editor is disabled by default in the Windows Home edition. To enable it, check out our guide on how to[access the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 Nevertheless, here's how to use Local Group Policy Editor to configure the taskbar to hide the clock and date.

1. Open the Run dialog box, type**gpedit.msc,** and press Enter.
2. In the Local Group Policy Editor, select the**Administrative Templates** folder under**User configuration.**
3. Click the**Start Menu and Taskbar** folder.
4. Click the**Setting** option in the right pane.
5. Search for and right-click on the**Remove Clock from the system notification area** policy. Then, choose**Edit** from the context menu.
6. In the policy edit window, choose the**Enabled** option.  
![Disabling Clock and Date using the local group policy editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disabling-clock-and-date.jpg)
7. Click**Apply** \>**OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uSfA74aeYeA?si=HdJSMdeS7HVtS6-j" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Next,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) for changes to take effect.

 If you want to add the clock and date again to the taskbar, open the edit window of the Remove Clock from the system notification area policy, choose the Disabled option and save the settings.

## 3\. Hide or Show the Clock and Date from the Taskbar Using the Registry Editor

 The[Registry Editor](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is an extensive database of your Windows operating system configuration settings. You can use it to navigate the registry and edit its keys.

 Here's how to use the Registry Editor to hide the clock and date from the taskbar:

1. In the Run dialog box, type**regedit** and click**OK.** It'll[open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Navigate to the following location:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies`
3. Right-click on the**Policies** key in the left panel, choose**New,** and then select**Key.**
4. Name the key**Explorer** and press Enter.  
![Creating new key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/creating-new-key.jpg)
5. In the Explorer key, right-click on the blank space, and choose**New** \>**DWORD (32-bit Value)** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gSKkJrJ57EA?si=WDOmInPE9EgQa_tB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Name the value**HideClock** and press Enter.
7. Right-click on the HideClock value, type**1** in the**Value data** section, and click**OK.**  
![Modifying HideClock Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/modifying-hideclock-value.jpg)

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Bov2KfWQ_Y?si=MnVczisgeJ-sGW2r" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-links.techidaily.com/new-2024-approved-harness-the-power-of-color-grading-a-guide-to-luts-in-photoshop-cs6/"><u>[New] 2024 Approved Harness the Power of Color Grading A Guide to LUTs in Photoshop CS6</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-cutting-edge-techniques-for-spotify-ad-success-for-2024/"><u>[New] Cutting-Edge Techniques for Spotify Ad Success for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-movavi-screencapturer-pro-review-and-analysis/"><u>[New] In 2024, Movavi ScreenCapturer Pro Review & Analysis</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-screen-review-snapshot-is-active-8-top-tier-or-not/"><u>[New] In 2024, Screen Review Snapshot Is Active 8 Top-Tier or Not?</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-mastering-photopeas-background-erase-technique/"><u>[New] Mastering Photopea's Background Erase Technique</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-instagrams-best-kept-trick-for-stunning-collages/"><u>[Updated] Instagram's Best-Kept Trick for Stunning Collages</u></a></li>
<li><a href="https://discover-exceptional.techidaily.com/assessing-and-maintaining-your-windows-memory-integrity-tips-from-yl-software-experts/"><u>Assessing and Maintaining Your Windows' Memory Integrity: Tips From YL Software Experts</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-4-feasible-ways-to-fake-location-on-facebook-for-your-samsung-galaxy-z-flip-5-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Feasible Ways to Fake Location on Facebook For your Samsung Galaxy Z Flip 5 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11s-fast-flip-buttons/"><u>Mastering Windows 11'S Fast Flip Buttons</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-enforce-local-policies-to-a-specific-user-in-windows-11/"><u>Steps to Enforce Local Policies to a Specific User in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-repairing-crashing-ccleaner-in-windows-1011/"><u>Strategies for Repairing Crashing CCleaner in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-tracking-storage-spent-on-apps/"><u>Strategies for Tracking Storage Spent on Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-presentations-windows-11-remove-pin-lock/"><u>Streamline Presentations: Windows 11, Remove PIN Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-screen-hotkey-based-program-minimization-techniques/"><u>Streamline Your Screen: Hotkey-Based Program Minimization Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/zeroing-out-wsl-complete-uninstallation-in-windows-11/"><u>Zeroing Out WSL: Complete Uninstallation in Windows 11</u></a></li>
</ul></div>

