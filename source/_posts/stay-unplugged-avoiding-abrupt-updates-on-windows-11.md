---
title: "Stay Unplugged: Avoiding Abrupt Updates on Windows 11"
date: 2024-11-28T01:56:18.521Z
updated: 2024-12-03T22:46:26.378Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Stay Unplugged: Avoiding Abrupt Updates on Windows 11"
excerpt: "This Article Describes Stay Unplugged: Avoiding Abrupt Updates on Windows 11"
keywords: Windows 11 Update Trends,Stay Unplugged Tips,Preventing Windows Updates,Quick Fix for Updates,Avoiding System Changes,Steady Windows Experience,Sidestep Windows Patches
thumbnail: https://thmb.techidaily.com/e271cbb6eb6a65ff2648f6dddd1fc0c078a843660eba98a715724fa951b431ee.jpg
---

## Stay Unplugged: Avoiding Abrupt Updates on Windows 11

 Typically, the installation of Windows updates necessitates a system restart, which can cause disruptions during critical work sessions. However, by configuring active hours, you can define the specific times during which you generally use your computer for work. Once you do, Windows will schedule update installations to occur outside of these active hours, ensuring that your work sessions remain uninterrupted.

 You can set active hours in Windows via the Settings app, the Group Policy Editor, or the Registry Editor. Let’s go through each of these methods in detail.

## 1\. How to Set Active Hours Manually via the Settings App

 The Settings app in Windows gives you several options for managing the installation of Windows updates. Here's how you can use it to set active hours on Windows 11\.

1. Press **Win + I** to open the Settings app.
2. Navigate to the **Windows Update** tab using the left sidebar.
3. Select **Advanced options**.
4. Click on **Active hours** to expand it.
5. Use the drop-down menu next to **Adjust active hours** to select **Manually**.
6. In the **Start time** and **End time** fields, specify the hours during which you typically use your device.  
![Set Active Hours Manually via the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-the-settings-app.jpg)

## 2\. How to Set Active Hours Manually Using the Group Policy Editor

 Although the Group Policy Editor on Windows is commonly used to manage advanced system-level settings, you can also use it to set active hours on your computer.

 Note that Group Policy Editor is only available on Professional, Education, and Enterprise editions of Windows. If you use Windows Home, check our guide on [how to access Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

 Follow these steps to set active hours on Windows using the Group Policy Editor.

1. Press **Win + R** to open the Run dialog box.
2. Type **gpedit.msc** in the box and press **Enter**.
3. Use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Update > Manage end user experience**.
4. Double-click the **Turn off auto-restart for updates during active hours** policy on your right.
5. Select the **Enabled** option.
6. Under **Options**, use the drop-down menus next to **Start** and **End** to specify your active hours.
7. Hit **Apply** followed by **OK**.  
![Set Active Hours Manually via Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-group-policy-editor.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yDuvbv0QOYI?si=byottcEM_Rrvi4EL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. How to Set Active Hours Manually With the Registry Editor

 Another method for setting active hours involves tweaking the Windows Registry.

 Although setting active hours via the Registry Editor is a straightforward process, it’s important to be cautious, as incorrect changes made to registry files can render your PC inoperable. If you opt for this method, make sure you either [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

1. Press **Win + S** to access the search menu.
2. Type **registry editor** in the text box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > WindowsUpdate > UX > Settings**.
5. Double-click the **ActiveHoursStart** entry.
6. In the **Value data** field, enter the desired value for the start time of your active hours in a 24-hour format. If you were to set the start time to **9:00 AM**, for instance, you would enter **9** in the text box.
7. Click **OK** to save the value.  
![Set Active Hours Manually via Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-registry-editor.jpg)
8. Double-click the **ActiveHoursEnd** entry to set the end time of your active hours in the 24-hour format. For instance, if you want to set the end time to **5:00 PM**, type **17** in the Value data field and click **OK**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gkdZ3A1mock?si=2zeR5GtTU2VujM_w" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

9. Exit the Registry Editor window.  
![Set Active Hours Manually via the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-the-registry-editor.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RBN1gYY5hUs?si=p89CMiMzeJzU0wGu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. How to Configure Windows to Set Active Hours Automatically

 You can also configure Windows to set active hours automatically. Doing so will allow Windows to analyze your usage patterns and automatically adjust the active hours accordingly.

 To configure Windows to set active hours automatically:

1. Use one of [the many ways to open the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/).
2. Navigate to **Windows Update > Advanced options > Active hours**.
3. Click the drop-down menu next to **Adjust active hours** and select **Automatically**.  
![Set Active Hours Automatically on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-automatically-on-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15TKQ-BOENI?si=Ri4B2AuxAdi0Bglz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/TJCye_oCTTw?si=6bVyBphcSgSFdyuq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Setting Active Hours on Windows Is Easy

 Once you set the active hours using one of the above methods, Windows will avoid initiating automatic restarts for updates during the specified period. As a result, you won’t be interrupted by sudden reboots during your work hours.

 You can set active hours in Windows via the Settings app, the Group Policy Editor, or the Registry Editor. Let’s go through each of these methods in detail.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-skyrocket-your-e-commerce-game-with-these-essential-15-social-media-insights/"><u>[New] 2024 Approved Skyrocket Your E-Commerce Game with These Essential 15 Social Media Insights</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/nhance-every-viewing-moment-with-these-top-6-free-platforms-for-youtube-short-downloads/"><u>[New] Enhance Every Viewing Moment with These Top 6 Free Platforms for YouTube Short Downloads</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-how-to-achieve-and-share-your-most-lengthy-instagram-videos-for-2024/"><u>[New] How to Achieve and Share Your Most Lengthy Instagram Videos for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-best-hidden-downloaders-1-8-unveiled/"><u>[New] In 2024, Best Hidden Downloaders - #1-8 Unveiled</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-2024-approved-prime-online-destinations-featuring-3d-art-and-metallic-text/"><u>[Updated] 2024 Approved Prime Online Destinations Featuring 3D Art & Metallic Text</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-word-lookups-for-newbies-to-win11/"><u>Efficient Word Lookups for Newbies to Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/effortlessly-access-the-microsoft-store/"><u>Effortlessly Access the Microsoft Store</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-boltguns-lags-winning-techniques-for-windows-users/"><u>Eliminating Boltgun's Lags: Winning Techniques for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-win1011-error-0xc0000001/"><u>Eliminating Win10/11 Error 0xC0000001</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-performance-with-customized-windows-11-configurations/"><u>Enhance Performance with Customized Windows 11 Configurations</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-productivity-unleash-potential-via-flow-launcher/"><u>Enhance Productivity: Unleash Potential via Flow Launcher</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-user-identity-management-in-win11-pro/"><u>Enhancing User Identity Management in Win11 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/escalate-typing-pace-via-windows-powertoys/"><u>Escalate Typing Pace via Windows' PowerToys</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-pictures-files-from-tecno-camon-20-by-fonelab-android-recover-pictures/"><u>How To Restore Missing Pictures Files from Tecno Camon 20.</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-obs-timer-mastery-building-a-custom-countdown-timer/"><u>In 2024, OBS Timer Mastery Building a Custom Countdown Timer</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-instructions-for-turning-onoff-cookies-on-popular-browsers-chrome-firefox-opera-and-edge-running-on-windows-ebox/"><u>Step-by-Step Instructions for Turning On/Off Cookies on Popular Browsers (Chrome, Firefox, Opera & Edge) Running on Windows Ebox</u></a></li>
<li><a href="https://win11.techidaily.com/transform-your-classic-gaming-journey-add-trophy-features-through-retroarch/"><u>Transform Your Classic Gaming Journey - Add Trophy Features Through Retroarch</u></a></li>
</ul></div>

